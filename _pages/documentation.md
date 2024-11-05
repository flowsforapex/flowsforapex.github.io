---
title: "Documentation"
permalink: /documentation/
layout: splash
---
### Product Documentation

Flows for APEX documentation, including for the Flows for APEX Enterprise Edition, is on the [flowsforapex.org](https://flowsforapex.org/documentation) website.

### Installation Documentation (not yet complete)

Flows for APEX Enterprise Edition v24.1 is released with 2 install scripts:

* install_all_ee.sql .  Requires all features of Flows for APEX Enterprise Edition v24.1, including the GenAI features.   This requires APEX 24.1 or higher, and pre-creation of a workspace level GenAI service in APEX.
* install_all_ee_without_AI.sql.  Requires APEX 22.1 or later, and does not install GenAI features.

#### Requirements for Ask Flo GenAI Assistance Feature

The AskFlow AI assistance feature requires the AI support features in APEX 24.1, and currently requires the OpenAI gpt API service (the pay-as-you-go api service from OpenAI).
While we plan to support other AI services in the near future, we have found the ability of OpenAI gpt-4o to understand and process BPMN is currently significantly better than  other Gen AI services, icluding Cohere, llama, and OCI.  As such, only OpenAI gpt-4o is supported in our initial release.
All models are developing rapidly, so we hope to be able to support more soon.  If you have particular AI requirements, due to security or privacy, please discuss these with Flowquest.

If you want to use the AskFlo AI feature, you will need:

1. to be running Oracle APEX 24.1 or later
2. to have an OpenAI API key
3. to upgrade the Flows for APEX 24.1 Application to the APEX 24.1EE application included in the Enterprise Edition release.

If you do not want to use the AskFlo feature, you can install the Enterprise Edition without GenAI.  In this case, you will add additional PL/SQL packages and other objects that implement BPMN Loops and iterations and BPMN MessageFlow.

#### Pre-requisites

1. If you are running Flows for APEX 23.1 or earlier, complete your upgrade and migration to Flows for APEX 24.1 Community Edition first.  Flows for APEX Enterprise Edition v24.1 installs on top of Flows for APEX Community Edition v 24.1.
2. Download the file xx from the Customer Portal on www.flowquest.net, and unzip it.
3. SKIP THIS STEP IF YOU ARE NOT INSTALLING ASK FLO.
   Set Up Your Workspace-level Flows for APEX API service in APEX.
   1. Open APEX and go to Workspace Utilities
      [Workspace Utilities]({{ site.url }}{{ site.baseurl }}/assets/images/install/apex_wksp_svcs.png "Workspace Services"
   2. Select Generative AI

      [Generative AI Services]({{ site.url }}{{ site.baseurl }}/assets/images/install/apex_gen_AI.png "Gen AI Services"
   3. Click Create and create a GenAI service.  Create a Generative AI service named "Flows for APEX AI Service", with a static ID of "F4A_AI_SERVICE".

      You will need to get an API Key from [openai.com](https://platform.openai.com/settings/organization/api-keys) if you don't already have one stored in your workspace credentials.

      [Create Flows Gen AI Service]({{ site.url }}{{ site.baseurl }}/assets/images/install/F4A_AI_Service.png "Create the Flows for APEX AI Service".
4. Run the appropriate installer file
