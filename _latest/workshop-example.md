---
permalink: /:collection/workshop-example/
title: "Flows for APEX Workshop Example"
toc: true
typora-root-url: ../
---

# Workshop: Build the Expense Application

This tutorial covers the development of a siple expense reimbursement application using Flows for APEX. 

## Aims of the Tutorial:  

After completing this workshop, you should be able to:

- Navigate around the Flows for APEX Application, using the Flow Modeler and the Flow Monitor
- Use the Flow Modeler to 
  - Design, save,  and test-run a business proces diagram.
  - Edit the process model to add new activities and lanes
  - Add detail to the process model until becomes an executable model
  - Configure a BPMN User Task as an APEX Page Task or an APEX Human Task
  - Configure a BPMN Script Task to run a PL/SQL script
  - Configure a BPMN Service Task to send email using APEX Mail
  - Configure Exclusive, Inclusive, and Parallel Gateways
- Use the Flow Monitor to:
  - Create and Start a Process Instance from the Monitor
  - Step a Process Forward
  - Examine (and change) Process Variables
- Create an APEX App to implement a simple workflow
  - Prepare the App by Copying in the Flows for APEX Component Group 
  - Create and Configure an APEX Task List for Flows for APEX
  - Implement a User Task as an APEX Page, adding Plugin Processes
  - Implement a User Task using an APEX Human Task for an approval
  - Adding a Flow Viewer to your app

## Stage 1: Using the Flows for APEX Application.



## Stage 2: Modeling a Simple Process

We're going to build a simple workflow for approving and processing an expense report.

Here's the process model that we will end up with.

![Expense Application Model](/assets/images/workshop-expense-model.png)

Note that the process starts with an expense report - the first step is NOT creating the expense report.

{::comment}
**Step 1**.  In the Flows for APEX app, open the Flow Management page.  Click **+ Create Model** to create a new model.

Category: Demo
Name :  Expense Report
Version: 0

Click **Create**.

**Step 2:**  Click **Modify Diagram** to open the **Flow Modeler**.  The BPMN Modeler will open with a blank canvas.

- Start by dragging  a **Start Event** ( <span class="bpmn-icon bpmn-icon-start-event-none"></span> ) from the tool bar onto the canvas.  Name it with our starting condition, **Submitted Expense Report**.
- With Start Event selected, use the contextual menu to select a task ( <span class="bpmn-icon bpmn-icon-task-none"></span> ).  Name this **Manager Approval**.
- Follow this with an **Exclusive  Gateway** ( <span class="bpmn-icon bpmn-icon-gateway-xor"></span> ).  Name this **Approved?**.
- Follow this with another task  ( <span class="bpmn-icon bpmn-icon-task-none"></span> ). Name this **Update Status and Insert Payment Record**.

{:/comment}

## Code Snippets

### For Script Task

```sql
declare
    l_process_id        number := flow_globals.process_id;
    l_expense_id        expense_report.id%type;
    l_employee_username expense_report.employee_username%type;
    l_category          expense_report.category%type;
    l_amount            expense_report.amount%type;
begin
    -- get business reference from workflow instance
    l_expense_id := flow_process_vars.get_business_ref(pi_prcs_id => l_process_id);

    --update expense status
    update expense_report
       set status = 'APPROVED'
     where id =  l_expense_id
     returning employee_username, category, amount
     into l_employee_username, l_category, l_amount;

     -- insert a payment request 
    insert into payment_request
    (employee_username, category, amount)
    values 
    (l_employee_username, l_category, l_amount);
end;


```



### For Approved? Gateway - forward paths

```plsql
:F4A$APPROVAL_OUTCOME = 'APPROVED'
```



```plsql
:F4A$APPROVAL_OUTCOME = 'REJECTED'
```



## For Send Email Service Task

Create 4 Variable Expressions that execute `BEFORE TASK`

**EMAIL**:

```
select employee_username
  from expense_report
 where id = :F4A$BUSINESS_REF
```

**AMOUNT**:

```
select amount
  from expense_report
 where id = :F4A$BUSINESS_REF
```

**EXPENSE_DATE**

```
select to_char(expense_date, 'DD/MM/YYYY')
  from expense_report
 where id = :F4A$BUSINESS_REF
```

**CATEGORY**

```
select category
  from expense_report
 where id = :F4A$BUSINESS_REF
```
