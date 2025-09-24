---
title: "The Future of Flows for APEX"
last_modified_at: 2024-10-29T11:30:00+01:00
permalink: /:collection/F4Afutures/
author: Richard
tags:
  - "Enterprise Edition"
  - "24.1"
---
The Future of Flows for APEX

Flows for APEX is a BPMN-based process automation and workflow management system for Oracle APEX, the world’s most popular low-code application platform.  Flows for APEX  enables organizations to model their business processes diagrammatically using the industry standard Business Process Model and Notation (BPMN), then use the power of the Oracle APEX low code development platform to rapidly develop process automation applications.  Flows for APEX provides facilities to execute workflow processes, while providing tools to monitor and manage running workflows.Flows for APEX is an APEX community project that started in 2020, and was initially by Hyand GmbH (formerly MT AG) at ODTUG Kscope 2020.  Subsequent major contributors to the project have come from Hyand, Talan, Oracle Corporation, Solicon, and Flowquest.  Flows for APEX has been downloaded over 10,000 times, and is now in production use at many large organizations, worldwide.

Starting with Flows for APEX version 24.1, Flows for APEX will be available in two editions:

* Flows for APEX Community Edition.  The Community Edition will remain an Open Source, APEX Community Project.   The software will continue to be available free of charge on an MIT license by download from flowsforapex.org.  Community support available via the project’s GitHub pages.
  
* Flows for APEX Enterprise Edition.   The Enterprise Edition is a new offering including major new product features, backed up with technical support, on an annual subscription basis from Flowquest Limited.  Major new features in 24.1 will include support for process collaboration with BPMN Message Flow, process step iteration and looping, and a GenAI assistant in the process modeler.

The launch of Flows for APEX Enterprise Edition will allow the project to become financially self supporting, and ensure it has the dedicated resources required to support current and future users and for the product to continue to be enhanced with an exciting future development agenda.

Flows for APEX version 24.1 will include exciting new capabilities in both the community and enterprise editions.  Community Edition will include:

* APEX Simple Form, enabling an input form page to be specified without having to specify an underlying database table or APEX page by using a flexible JSON region plugin.
* Process Starter.  A pre-built end-user application that enables a user to view the catalog of business processes that they can initiate, pick and start a business process, and shows their current task inbox.  This eases process deployment into the organization.
* JSON-typed Process Variables.
  Support for BPMN Color, allowing user-defined coloring of process steps in BPMN diagrams.

In addition to these features, the Enterprise Edition will also add the following major features:

* BPMN Iteration and Looping.  Workflow steps often need to be executed repeatedly for each item in a list.  Iteration and Looping enables a BPMN task or  sub-process to be repeated once for each item in a list or a query result set, either sequentially or in parallel.  It also allows tasks or sub-processes to be executed continuously in a loop until a complete condition is met.
* Process Collaboration with BPMN Message Flow.  Enable processes to message each other, whether on the same APEX instance or to a remote endpoint via REST.  Message Flow allows a process instance to message another process instance, subscribe and wait for an incoming message, start another process instance, interrupt or change the process flow in another instance with message boundary events, or emit a message on completion of a process or sub-process.

* AI Assistance to the Process Modeler.  The current set of LLMs understand BPMN, and so are able to summarize, detect and explain model errors, suggest technical, modeling or business process improvements, and explain models built in different languages.  Additional AI use cases and features are planned in later releases.

Development of release 24.1 is almost complete, and we are planning to release this imminently, usual caveats notwithstanding.

We are excited about the future of Flows for APEX and to be shipping the next release soon.

Niels De Bruijn						Richard Allen
Hyand GmbH							Flowquest Limited
