---
title: "Flows for APEX Enterprise Edition"
excerpt: "v24.1 Installation"
permalink: /install-doc-ee-241/
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.6"
  overlay_image: /assets/images/RunningFlows.gif
---

### Installation Documentation 

Flows for APEX Enterrise Edition v24.1 can be installed with or without the Ask Flo generative AI feature.  

-  If you are installing *WITH* the AI feature, you need to be running Oracle APEX v24.1 or later, and have an OpenAI API key with a pre-paid credit balance. This install will replace the Flows for APEX application with an APEX 24.1 app.

- If you can't meet these requirements, or choose not to run the AI feature, you can run Flows for APEX Enterprise Edition with Oracle APEX v22.1 or later.  This installation does not replace the Flows for APEX application that you installed with the Community Edition.

## Pre-Requisites 

-  You need a working Flows for APEX v24.1 Community Edition installation before you start - the Enterprise Edition instals on top of the Community Edition.  

    - If you have an existing Flows for APEX 23.1 or earlier installation, upgrade and migrate this to Flows for APEX v24.1 Community Edition first using the instructions at ...
    _ If  you are installing a new system, start by installing Flows  for APEX Community Edition v24.1.  You can do this by importing the Flows for APEX Community Edition app and installing its supporting objects.  
    
- You should have Timers set up and working.  Configure and enable the `DBMS_SCHEDULER` program and job required for Flows for APEX Timers.

- APEX Version.  Full installation requires Oracle APEX v24.1.  Installation without AI requires APEX v22.1 or later.

- To run the AI feature, you need to set up a Workspace-level Generative AI service for Flows for APEX, using OpenAI with the `gpt-4o` model with a static ID defined in APEX as `F4A_AI_SERVICE`.  For detailed instructions, see below.

Then follow one of these two paths to install with or without AI.

## Full Enterprise Edition install, including the Ask Flo GenAI Assistance Feature

The AskFlow AI assistance feature requires the AI support features in APEX 24.1, and currently requires the OpenAI gpt API service (the pay-as-you-go api service from OpenAI).
While we plan to support other AI services in the near future, we have found the ability of OpenAI gpt-4o to understand and process BPMN is currently significantly better than  other Gen AI services, icluding Cohere, llama, and OCI AI.  As such, only OpenAI gpt-4o is supported in our initial release.
All models are developing rapidly, so we hope to be able to support more soon.  If you have particular AI requirements, due to security or privacy, please discuss these with Flowquest.

If you want to use the AskFlo AI feature, you will need:

1. to be running Oracle APEX 24.1 or later
2. to have an OpenAI API key
3. to upgrade the Flows for APEX 24.1 Application to the APEX 24.1EE application included in the Enterprise Edition release.

If you do not want to use the AskFlo feature, you can install the Enterprise Edition without GenAI.  In this case, you will add additional PL/SQL packages and other objects that implement BPMN Loops and iterations and BPMN MessageFlow.

#### Set up your APEX Workspace-level GenAI Service for Flows for APEX.

   To set Up Your Workspace-level Flows for APEX API service in APEX.
   1. Open APEX, go into the Application Builder, and select Workspace Utilities

   2. Select Generative AI

      ![Generative AI Services]({{site.url}}{{site.baseurl}}/assets/images/install/apex_gen_AI.png "Gen AI Services")
   3. Click Create and create a GenAI service.  Create a Generative AI service named "Flows for APEX AI Service", with a static ID of "F4A_AI_SERVICE".

      You will need to get an API Key from [openai.com](https://platform.openai.com/settings/organization/api-keys) if you don't already have one stored in your workspace credentials.

      ![Create Flows Gen AI Service]({{site.url}}{{site.baseurl}}/assets/images/install/F4A_AI_Service.png "Create the Flows for APEX AI Service").

#### Install Flows for APEX Enterprise Edition v24.1 (Full Install)

1.  Download the Enterprise Edition package from the link given to you by Flowquest.
2.  Unzip the release into a folder on your computer.
3.  Change Directory to the `src` folder in the unzipped files.
4.  Using SQLcl, connect to the database as the Flows for APEX schema owner.
5.  Run the file `install_all_ee.sql`.  This should 
    1.  suspend the timer job
    2.  Upgrade your schema by adding tables, views, and packages required for Enterprise Edition.
    3.  Recompile all of the Flows for APEX packages
    4.  Add your licence information to the Flows for APEX configurations
    5.  Install the new APEX v24.1 Flows for APEX application on top of your existing one.
    6.  Restart your timer job.
6.  Flows for APEX Enterprise Edition should now be running.
   

## Enterprise Edition install without the Ask Flo GenAI Assistance Feature

If you want to use Enterprise Edition without the AskFlo AI feature, you will need:

1. to be running Oracle APEX 22.1 or later
2. Have a running Flows for APEX 24.1 Community Edition installation.
3. Have timers set up.

You will add additional PL/SQL packages and other objects that implement BPMN Loops and iterations and BPMN MessageFlow, then recopile your PL/SQL packages to  include the Enterprise Edition features.

#### Install Flows for APEX Enterprise Edition v24.1 (Without AI Install)

1.  Download the Enterprise Edition package from the link given to you by Flowquest.
2.  Unzip the release into a folder on your computer.
3.  Change Directory to the `src` folder in the unzipped files.
4.  Using SQLcl, connect to the database as the Flows for APEX schema owner.
5.  Run the file `install_all_ee_without_ai.sql`
    This should
    1.  Suspend the timer job
    2.  Upgrade your schema by adding tables, views, and packages required for Enterprise Edition.
    3.  Recompile all of the Flows for APEX packages
    4.  Add your licence information to the Flows for APEX configurations
    5.  Restart your timer job.
6.  Flows for APEX Enterprise Edition should now be running.


