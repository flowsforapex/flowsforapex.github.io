---
title: "Flows for APEX Enterprise Edition"
excerpt: "v25.1 Installation"
permalink: /install-doc-ee-251/
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.6"
  overlay_image: /assets/images/RunningFlows.gif
---

### Installation Documentation 

Flows for APEX Enterrise Edition v25.1 has a single installation process (unlike v24.1, where there were 2 different installations as 'Ask Flo AI' was optional).  

## Pre-Requisites 

-  You need a working Flows for APEX v25.1 Community Edition installation before you start - the Enterprise Edition instals on top of the Community Edition.  

    - If you have an existing Flows for APEX 24.1 or earlier installation, upgrade and migrate this to Flows for APEX v25.1 Community Edition first using the instructions [here](https://www.flowsforapex.org/latest/installation_251/){:target="_blank"}.
    
    - If  you are installing a new system, start by installing Flows  for APEX Community Edition v25.1.  You can do this by importing the Flows for APEX Community Edition app and installing its supporting objects using the instructions [here](https://www.flowsforapex.org/latest/installation_251/){:target="_blank"}.
    
- You should have Timers set up and working.  (Unlike v24.1, these are now set up for you as part of the Community Edition installation  - so this should already be the case)

- APEX Version.  Installation requires Oracle APEX v24.1 or later.

- Database: Installation requires Oracle Database 19c or later.

- Privileges:  To run Enterprise Edition, the Flows for APEX Schema requires the following privileges,  grants, and roles:

    | Type              | Required                                                     |
    | ----------------- | ------------------------------------------------------------ |
    | System Privileges | CREATE TABLE<br />CREATE PROCEDURE<br />CREATE SEQUENCE<br />CREATE VIEW<br />CREATE JOB<br />CREATE. TYPE |
    | System Roles      | AQ_ADMINISTRATOR_ROLE<br />AQ_USER_ROLE                      |
    | System Packages   | execute privilege on DBMS_AQ                                 |

    These are checked by the Installer before the Enterprise Edition can be installed.

- To run the AI feature, you need to set up a Workspace-level Generative AI service for Flows for APEX, using OpenAI with the `gpt-4o` model with a static ID defined in APEX as `F4A_AI_SERVICE`.  For detailed instructions, see below.  

- If you are not using / not able to use the AI features, the 25.1 Community Edition APEX app installation should have already created a dummy AI service for you named `F4A_AI_SERVICE` that just links to `example.com` and is non-functional.  This is sufficient.  You can edit this definition later (in Application Builder > Workspace Options), once you are ready to use AI.

Then follow one of these two paths to install a new environment or migrate an existing one.

## New Enterprise Edition install.

You will need:

1. to be running Oracle APEX 24.1 or later.
2. to be running Oracle database 19c or later.
3. have a running Flows for APEX 25.1 Community Edition installation.
4. to have the required privileges (see above).

You then install the Enterprise Edition **on-top** of the Community Edition.  The installation sets up Oracle Advanced Queueing, installs some missing PL/SQL package bodies and SQL views, recompiles everything, and gives you an Enterprise Edition system.  To do this:

1.  Download the Enterprise Edition package from the link given to you by Flowquest.
2.  Unzip the release into a folder on your computer.
3.  Change Directory to the folder containing the unzipped files.
4.  Using SQLcl, connect to the database as the Flows for APEX schema owner.
5.  Run the file `install_all_ee.sql`.  This should 
    1.  suspend the timer job
    2.  create Oracle AQ objects
    3.  Upgrade your schema by adding views and packages required for Enterprise Edition.
    4.  Recompile all of the Flows for APEX packages
    5.  Add your licence information to the Flows for APEX configurations
    6.  Restart your timer job.
6.  Flows for APEX Enterprise Edition should now be running.

## Existing Enterprise Edition v24.1 User migrating to v25.1

You will need:

1. to be running Oracle APEX 24.1 or later.
2. to be running Oracle database 19c or later.
3. to have the required privileges on the Flows for APEX Schema.  (Note new privileges required for 25.1)

The migration path in overview is:
 1. Prevent access to the system by users.

 2. Disable Timers.

 3. Backup your System.

 4. Follow. the [instructions](https://flowsforapex.org/latest/migration/){:target="_blank"} to migrate a Community Edition v24.1 installation to a CE v25.1 one.  This will temporarily make your system a v25.1 Community Edition.

 5. Install Enterprise Edition v25.1 **on-top** of the Community Edition.  The installation sets up Oracle Advanced Queueing, installs some missing PL/SQL package bodies and SQL views, recompiles everything, and gives you an Enterprise Edition system.  To do this:

    1.   Download the Enterprise Edition package from the link given to you by Flowquest.

    2. Unzip the release into a folder on your computer.

    3. Change Directory to the folder containing the unzipped files.

    4. Using SQLcl, connect to the database as the Flows for APEX schema owner.

    5. Run the file `install_all_ee.sql`.  This should 
       1.  suspend the timer job
       2.  create Oracle AQ objects
       3.  Upgrade your schema by adding views and packages required for Enterprise Edition.
       4.  Recompile all of the Flows for APEX package.
       5.  Add your licence information to the Flows for APEX configurations
       6.  Restart your timer job.

6. Flows for APEX Enterprise Edition should now be running.

#### Set up your APEX Workspace-level GenAI Service for Flows for APEX.

   To set Up Your Workspace-level Flows for APEX API service in APEX.

   1. Open APEX, go into the Application Builder, and select Workspace Utilities

   2. Select Generative AI

      ![Generative AI Services]({{site.url}}{{site.baseurl}}/assets/images/install/apex_gen_AI.png "Gen AI Services")

   3. Either edit the Generative AI service named "Flows for APEX AI Service", with a static ID of "F4A_AI_SERVICE", or create one if it doesn't already exist..

      You will need to get an API Key from [openai.com](https://platform.openai.com/settings/organization/api-keys) if you don't already have one stored in your workspace credentials.

      ![Create Flows Gen AI Service]({{site.url}}{{site.baseurl}}/assets/images/install/F4A_AI_Service.png "Create the Flows for APEX AI Service").

