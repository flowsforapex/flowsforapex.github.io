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
    image_path: "/assets/images/messageflow-231.png"
row3:
  - title: 'Major Upgrade to Graphical Workflow Modeler and Viewer'
    excerpt: >
      Major revision and modernization of the BPMN Modeler and Viewer tools:
        - Modern properties panel and easier to use controls
        - Supports drill down into collapsed SubProcesses for cleaner process models
        - Process Viewer allows drilldown into Subprocess and Call Activity status
        - New support for BPMN Groups, Child Lanesets and Annotations
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
  - title: "Task Assignment, Due Dates and Priorities"
    excerpt: >
      Highly flexible, model driven rules control task assignment, process and task priority, and due dates.
        - Task Assignment by BPMN lane or explicit assignment to potential users and potential groups
        - Task- and Process- Level Management of Due Dates and Priority
        - Implement dynamic assignment and scheduling policies through runtime database access
        - Integrated to the APEX Unified Task List
    image_path: "/assets/images/integratedTaskList.png"
row6:
  - title: "Developer Experience Enhancements"
    excerpt: >
      Many new features to enhance the Develop Experience
        - New Timestamp with Time Zone Process Variable type
        - Process Variable binding into SQL, PL/SQL, and scripts everywhere
        - Improved Binding and Substitution of non varchar2-typed process variables
        - Better APEX Approval Task and Task List integration
        - New Plugin for Starting Process Instances from an APEX Automation
    image_path: "/assets/images/modeler-tstz-bind.png"
row7:
  - title: "Logging, Archiving, and Process Statistics Improvements"
    excerpt: >
      Major enhancement of the event logging system for System Administrators
        - Now includes logging of Process Diagram changes to Capture Process Changes
        - New Process Timeline view in Flow Monitor
        - Automated creation of Instance Summary Archive documents
        - Automated purging of old log entries
        - Generation of Process and Task Statistics, including processing and waiting times
    image_path: "/assets/images/instance-timeline-231.png"
row8:
  - title: "More Languages Supported"
    excerpt: >
      Flows for APEX now supports all 10 of the APEX development languages with new Korean, Chinese and Italian translations
        - English
        - French
        - German
        - Spanish
        - Portuguese (br-pt)
        - Italian
        - Japanese
        - Korean
        - Simplified Chinese
        - Traditional Chinese
    image_path: "/assets/images/nls-231-korean-chinese.png"
row9:
  - title: "REST Enablement"
    excerpt: >
      The Flows for APEX PL/SQL API is now REST-enabled, allowing remote execution of all API calls.
        - Allows easy integration of 3rd Party Systems with Flows
        - Enables Message Flow from Remote Systems
        - Eases Management as an Adminstrator
    image_path: "/assets/images/ords.png"
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
{% include feature_row id="row5" type="left"%}
{% include feature_row id="row2" type="left"%}
{% include feature_row id="row3" type="left"%}
{% include feature_row id="row9" type="left"%}
{% include feature_row id="row6" type="left"%}
{% include feature_row id="row7" type="left"%}
{% include feature_row id="row8" type="left"%}
{% include feature_row id="row10" type="center"%}