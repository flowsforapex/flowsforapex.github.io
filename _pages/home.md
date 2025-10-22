---
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.6"
  overlay_image: /assets/images/RunningFlows.gif
  actions:
    - label: '<i class="fas fa-cloud-download-alt" aria-hidden="true" style="padding-right: 5px;"></i>Download'
      url: "https://github.com/flowsforapex/apex-flowsforapex/releases/download/v25.1/FlowsForAPEX_v25.1.zip"
    - label: '<i class="fas fa-envelope-open-text" aria-hidden="true" style="padding-right: 5px;"></i>Subscribe'
      url: "https://apex.mt-ag.com/ords/portal/r/apex/newsletter-page?p8_source_page=FLOWSFORAPEX"
      target: "_blank"
    - label: "Learn more"
      url: "/latest/getting-started/"
excerpt: >
  Oracle APEX extension for BPMN based workflows
row2:
  - title: >
      Watch "What's New in Flows for APEX v25.1" replay on APEX Office Hours
    excerpt: >
      Watch the replay of Moritz Klein and Richard Allen from the Flows for APEX team as they demoed our latest release, Flows for APEX v25.1, on a Oracle APEX Office Hours session on September 25th, 2025.  What's New in Flows for APEX v 25.1 - **Smarter BPMN Workflows with AI, Suspend and Rewind**.  See demos for:
        - AI Service Tasks - Adding GenAI into your Workflow
        - Suspend/Resume for running processes
        - Rewind to recover from bad user decisions
        - Improved APEX Human Tasks integration
        - Enhanced event logging, debugging, and usability
    image_path: "/assets/images/oh-flowsforapex-251-sm.png"
    actions: 
      - url: "/Flows4APEX251Features/"
        target: "_blank"
        class: "btn--info"
        label: '<i aria-hidden="true" style="padding-right: 5px;"></i>See More Details on 25.1'
      - url: "https://www.youtube.com/watch?v=fKYG71gdlOc&t=3s"
        target: "_blank"
        class: "btn--info"
        label: '<i class="far fa-play-circle" aria-hidden="true" style="padding-right: 5px;"></i>Watch the Replay'
row1:
  - excerpt: "Flows for APEX is a powerful workflow engine extension for Oracle APEX applications. Model your business processes with BPMN, develop your process steps in APEX, and monitor your running processes with the Flows for APEX application. Flows for APEX was created as a community project by team of experienced APEX professionals to meet the workflow requirements in many APEX applications."
row4:
  - title: >
      Watch "What's New in Flows for APEX v24.1" on APEX Office Hours
    excerpt: >
      Join Niels de Bruijn and Richard Allen from the Flows for APEX team as they demo Flows for APEX v24.1 new features in a live Oracle APEX Office Hours session on October 10th: What's New in Flows for APEX v 24.1.  See demos for:
        - User Task type "Simple Forms"
        - New sample app "Simple Process Starter"
        - JSON support for process variables
        - Support for iterations and loops
        - Improved process collaboration and messaging
        - Generative AI support
    image_path: "/assets/images/241-oh-global-flows-sm.png"
    actions: 
      - url: "/Flows4APEX241Features/"
        target: "_blank"
        class: "btn--info"
        label: '<i aria-hidden="true" style="padding-right: 5px;"></i>See More Details on 24.1'
      - url: "https://youtu.be/zSOBjRgtou8?si=fgIEo7CVSl1BlYHO"
        target: "_blank"
        class: "btn--info"
        label: '<i class="far fa-play-circle" aria-hidden="true" style="padding-right: 5px;"></i>Watch the Replay'
row3:
  - title: >
      Flows for APEX v24.1 Community Edition and Enterprise Edition now Available
    excerpt: >
      The Flows for APEX team is proud to announce the general availability of Flows for APEX v24.1 in two editions.   The Community Edition remains
      fully open source and free of charge with community support via Github issues.  The Enterprise Edition* adds additional functionality and comes with product support, and is available on an 
      annual subscription basis from Flowquest.
        - Simple Forms allow data inputs without development
        - New "Process Starter" sample app
        - JSON support for process variables
        - Support for iterations and loops*
        - Improved process collaboration and messaging*
        - Generative AI support*
    image_path: "/assets/images/floAIAdvisor241.png"
    actions: 
      - url: "/Flows4APEX241Features/"
        target: "_blank"
        class: "btn--info"
        label: '<i aria-hidden="true" style="padding-right: 5px;"></i>See More Details on 24.1'
      - url: "https://flowquest.net/"
        target: "_blank"
        class: "btn--info"
        label: "About Enterprise Edition"
row5:
  - title: "Expense Claims Sample App"
    excerpt: 'Test Flows for APEX with the sample app "Expense Claims", which is also included in the software.  Updated for v24.1'
    image_path: "/assets/images/demo-app.png"
    actions:
      - url: "https://flowsforapex.com/preview/demo"
        target: "_blank"
        class: "btn--info"
        label: '<i class="far fa-play-circle" aria-hidden="true" style="padding-right: 5px;"></i>Try now'
      - url: "https://github.com/flowsforapex/apex-flowsforapex/releases/download/v23.1/FlowsforAPEX_v23.1.zip"
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
      We also provide a light version of this tutorial in the documentation, accessible by clicking on Learn More.  Updated for v24.1.
    image_path: "/assets/images/Tutorial.png"
    actions:
      - url: "/assets/files/Tutorial_Flows_for_APEX_v23.1.zip"
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
{% include feature_row id="row7" type="left"%}
{% include feature_row id="row8" type="left"%}
{% include feature_row id="row9" type="left"%}
{% include feature_row id="row10" type="center"%}
