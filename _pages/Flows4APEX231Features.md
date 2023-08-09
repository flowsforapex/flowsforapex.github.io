---
layout: splash
permalink: /Flows4APEX231Features/
header:
  overlay_color: "#000"
  overlay_filter: "0.6"
  overlay_image: /assets/images/RunningFlows.gif
  actions:
    - label: '<i class="far fa-play-circle" aria-hidden="true" style="padding-right: 5px;"></i>Try now'
      url: "https://apex.oracle.com/pls/apex/r/mtflows/flows4apex"
      target: "_blank"
    - label: '<i class="fas fa-cloud-download-alt" aria-hidden="true" style="padding-right: 5px;"></i>Download'
      url: "https://github.com/flowsforapex/apex-flowsforapex/releases/download/v22.2/FlowsforAPEX_v22.2.zip"
    - label: '<i class="fas fa-envelope-open-text" aria-hidden="true" style="padding-right: 5px;"></i>Subscribe'
      url: "https://apex.mt-ag.com/ords/portal/r/apex/newsletter-page?p8_source_page=FLOWSFORAPEX"
      target: "_blank"
    - label: "Learn more"
      url: "/latest/getting-started/"
title: 'Flows for APEX v23.1'
excerpt: >
  New Features
row1:
  - excerpt: "Flows for APEX is a powerful workflow engine extension for Oracle APEX applications. Model your business processes with BPMN, develop your process steps in APEX, and monitor your running processes with the Flows for APEX application. Version 23.1 adds powerful new features, speeds application development, and eases adminstration."
row2:
  - title: 'Introducing BPMN Message Flow'
    excerpt: >
      Introduces BPMN Message Flow for inter process communication:
        - Send Messages between Processes
        - Adds BPMN Send Task and Receive Task
        - Adds BPMN Message Catch and Throw Events
        - Process can wait for Message and Payload from Outside
        - Inbound messaging REST enabled
    image_path: "/assets/images/F4A-OOH-03Aug23.png"
row3:
  - title: 'Major Upgrade to BPMN Modeler and Viewer'
    excerpt: >
      Major revision and modernization of the BPMN Modeler and Viewer tools:
        - Modern properties panel and easier to use controls
        - Supports drill down into collapsed SubProcesses for cleaner process models
        - Process Viewer allows drilldown into Subprocess and Call Activity status
    image_path: "/assets/images/231_preview.PNG"
row4:
  - title: "Watch 'What's New in Flows for APEX v22.2' on APEX Office Hours"
    excerpt: >
      The Flows for APEX team presented 'What's New in Flows for APEX v22.2' in the last APEX Office Hours call on September 29th, 2022.  This included a detailed demo of Flows for APEX v22.2 new features, including:
        -  Call Activities
        -  Improved Gateway Routing Expressions
        -  Integration with APEX Approval Tasks and the Unified Task Inbox
    image_path: "/assets/images/AOHSep22.png"
    actions:
      - url: "https://asktom.oracle.com/pls/apex/f?p=100:551::::551:P551_CLASS_ID,P551_INVITED:18506,N&cs=1461622C90E5945B28E6001AE2A9D7031"
        target: "_blank"
        class: "btn--info"
        label: '<i class="far fa-play-circle" aria-hidden="true" style="padding-right: 5px;"></i>Watch the Replay'
row5:
  - title: "Expense Claims Sample App"
    excerpt: 'Test Flows for APEX with the sample app "Expense Claims", which is also included in the software.'
    image_path: "/assets/images/demo-app.png"
    actions:
      - url: "https://apex.oracle.com/pls/apex/r/mtflows/expense-claims"
        target: "_blank"
        class: "btn--info"
        label: '<i class="far fa-play-circle" aria-hidden="true" style="padding-right: 5px;"></i>Try now'
      - url: "https://github.com/flowsforapex/apex-flowsforapex/releases/download/v22.2/FlowsforAPEX_v22.2.zip"
        class: "btn--info"
        label: '<i class="fas fa-cloud-download-alt" aria-hidden="true" style="padding-right: 5px;"></i>Download'
row6:
  - title: "Graphical Workflow Editor"
    excerpt: 'Model your business processes by adding activities and gateways in a graphical way.'
    image_path: "/assets/images/modeler.gif"
    actions:
      - url: "/latest/getting-started/"
        class: "btn--info"
        label: 'Learn More'
row7:
  - title: "Integration in your APEX application"
    excerpt: >
      3 process plug-ins are part of the distribution to make the integration easier:
        - Manage Flow Instance: start, stop, terminate, reset and delete the entire flow instance
        - Manage Flow Instance Step: start, reserve, release and complete a single step
        - Manage Flow Instance Variables: set and get process variables
    image_path: "/assets/images/process-plugins.png"
    actions:
      - url: "/latest/plugins/"
        class: "btn--info"
        label: 'Learn More'
row8:
  - title: "Monitor your running instances"
    excerpt: >
      The engine app can be use:
        - to monitor the running instances
        - to identify errors by viewing the events logs 
        - to restart steps in error after fixing the issue
    image_path: "/assets/images/dashboard.png"
    actions:
      - url: "/latest/getting-started"
        class: "btn--info"
        label: 'Learn More'
row9:
  - title: "Flows for APEX integration tutorial"
    excerpt: >
      This tutorial provides an introduction to the usage and integration of Flows for APEX into a process-driven APEX application.
      We also provide a light version of this tutorial in the documentation, accessible by clicking on Learn More.
    image_path: "/assets/images/Tutorial.png"
    actions:
      - url: "/assets/files/Tutorial_Flows_for_APEX_v22.2.zip"
        class: "btn--info"
        label: '<i class="fas fa-cloud-download-alt" aria-hidden="true" style="padding-right: 5px;"></i>Download'
      - url: "/latest/getting-started/"
        class: "btn--info"
        label: 'Learn More'
row10:
  - title: "Still 100% Open Source"
    excerpt: "Flows for APEX is open source. You can share and/or modify it, always under the adherence of the MIT-license."
    actions:
      - url: "https://github.com/flowsforapex/apex-flowsforapex"
        target: "_blank"
        class: "btn--info"
        label: '<i class="fab fa-github" aria-hidden="true" style="padding-right: 5px;"></i>Browse code'
      - url: "https://github.com/flowsforapex/apex-flowsforapex/issues/new/choose"
        target: "_blank"
        class: "btn--info"
        label: "Open an issue"
---
{% include feature_row id="row1" type="center"%}
{% include feature_row id="row2" type="left"%}
{% include feature_row id="row3" type="right"%}
{% include feature_row id="row10" type="center"%}