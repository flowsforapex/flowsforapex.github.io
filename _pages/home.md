---
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.6"
  overlay_image: /assets/images/RunningFlows.gif
  actions:
    - label: '<i class="far fa-play-circle" aria-hidden="true" style="padding-right: 5px;"></i>Try now'
      url: "https://apex.oracle.com/pls/apex/mtflows/r/flowsforapex"
      target: "_blank"
    - label: '<i class="fas fa-cloud-download-alt" aria-hidden="true" style="padding-right: 5px;"></i>Download'
      url: "https://github.com/flowsforapex/apex-flowsforapex/releases/download/v22.1/FlowsforAPEX_v22.1.zip"
    - label: '<i class="fas fa-envelope-open-text" aria-hidden="true" style="padding-right: 5px;"></i>Subscribe'
      url: "https://apex.mt-ag.com/ords/portal/r/apex/newsletter-page?p8_source_page=FLOWSFORAPEX"
      target: "_blank"
    - label: "Learn more"
      url: "/latest/getting-started/"
excerpt: >
  Oracle APEX extension for BPMN based workflows
row1:
  - excerpt: "Flows for APEX is a powerful workflow engine extension for Oracle APEX applications. Model your business processes with BPMN, develop your process steps in APEX, and monitor your running processes with the Flows for APEX application. Flows for APEX was created as a community project by team of experienced APEX professionals to meet the workflow requirements in many APEX applications."
row2:
  - title: 'Flows for APEX v22.2 is coming soon!  Get a Sneak Peak...'
    excerpt: >
      The next release of Flows for APEX, v22.2, adds several exciting features to make workflows more powerful and easier to run:
        - re-use process components with Call Activities, allowing one process diagram to call another diagram
        - integrate Oracle APEX v22.1+ Approval Tasks into your BPMN workflow process
        - simpler and more intuitive definition of gateway routing with Gateway Routing Expressions
        - additional language support for Japanese (ja), Brazillian-Portuguese (pt-br), and German (de)
        - under the covers, we've added extensive regression testing, bug fixes, and more.
    image_path: "/assets/images/callActivityGenExample.png"
    actions:
      - url: "/development/getting-started/"
        class: "btn--info"
        label: 'Beta Doc'
      - url: "https://apex.oracle.com/pls/apex/r/f4a_222/flows4apex"
        target: "_blank"
        class: "btn--info"
        label: '<i class="far fa-play-circle" aria-hidden="true" style="padding-right: 5px;"></i>Tutorials - Try now'
      - url: "https://apex.oracle.com/pls/apex/r/f4a_222/expense-claims"
        target: "_blank"
        class: "btn--info"
        label: '<i class="far fa-play-circle" aria-hidden="true" style="padding-right: 5px;"></i>demo App - Try now'
row3:
  - title: "Flows for APEX v22.2 on APEX Office Hours - 29 September 2022"
    excerpt: The Flows for APEX team will be presenting 'What's New in Flows for APEX v22.2' in the next APEX Office Hours call on Thursday September 29th, 2022.  14:00 - 15:00 UTC.  Replay coming soon.
    image_path: "/assets/images/AOHSep22.png"

row5:
  - title: "Expense Claims Sample App"
    excerpt: 'Test Flows for APEX (v22.1) with the sample app "Expense Claims", which is also included in the software.'
    image_path: "/assets/images/demo-app.png"
    actions:
      - url: "https://apex.oracle.com/pls/apex/mtflows/r/flowsforapexdemo"
        target: "_blank"
        class: "btn--info"
        label: '<i class="far fa-play-circle" aria-hidden="true" style="padding-right: 5px;"></i>Try now'
      - url: "https://github.com/flowsforapex/apex-flowsforapex/releases/download/v22.1/FlowsforAPEX_v22.1.zip"
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
      - url: "/assets/files/Tutorial_Flows_for_APEX_v22.1.zip"
        class: "btn--info"
        label: '<i class="fas fa-cloud-download-alt" aria-hidden="true" style="padding-right: 5px;"></i>Download'
      - url: "/latest/getting-started/"
        class: "btn--info"
        label: 'Learn More'
row10:
  - title: "100% Open Source"
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
{% include feature_row id="row3" type="left"%}
{% include feature_row id="row5" type="left"%}
{% include feature_row id="row6" type="left"%}
{% include feature_row id="row7" type="left"%}
{% include feature_row id="row8" type="left"%}
{% include feature_row id="row9" type="left"%}
{% include feature_row id="row10" type="center"%}