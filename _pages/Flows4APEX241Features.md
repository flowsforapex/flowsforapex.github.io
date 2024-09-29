---
layout: splash
permalink: /Flows4APEX241Features/
header:
  overlay_color: "#000"
  overlay_filter: "0.6"
  overlay_image: /assets/images/RunningFlows.gif
--  actions:
--    - label: '<i class="far fa-play-circle" aria-hidden="true" style="padding-right: 5px;"></i>Try now'
--      url: "https://flowsforapex.com/preview/engine"
--      target: "_blank"
--    - label: '<i class="fas fa-cloud-download-alt" aria-hidden="true" style="padding-right: 5px;"></--i>Download'
--      url: "https://github.com/flowsforapex/apex-flowsforapex/releases/download/v23.1/FlowsforAPEX_v23.1.zip"
--    - label: '<i class="fas fa-envelope-open-text" aria-hidden="true" style="padding-right: 5px;"></--i>Subscribe'
--      url: "https://apex.mt-ag.com/ords/portal/r/apex/newsletter-page?p8_source_page=FLOWSFORAPEX"
--      target: "_blank"
--    - label: "Learn more"
--      url: "/latest/getting-started/"
title: 'Flows for APEX v24.1'
excerpt: >
  New Features coming soon in 24.1 
row1:
  - excerpt: "In addition to new features, Flows for APEX version 24.1 introduces the **Flows for APEX Enterprise Edition** - with powerful new enterprise features and  technical support available on an annual subscription basis.  The **Flows for APEX Community Edition** remains as a free-of-charge, community supported product - also with new features."
row2:
  - title: 'Full Process Collaboration with BPMN Message Flow*'
    excerpt: >
      Building on 23.1, BPMN Message Flow now supports a full range BPMN events for inter process communication:
        - start a new process from incoming message with BPMN Message Start
        - subscribe and wait for, or send a message to another process
        - interrupt or change process flow based on a received message
        - emit messages from a process or sub-process end event
    image_path: "/assets/images/msgFlowSendRxInvoice241.png"
row3:
  - title: 'Iterating and Looping Process Steps*'
    excerpt: >
      Repeat a step for each item in a list or query, sequentially or in parallel 
        - works on tasks and sub-processes
        - execute sequentally or in parallel
        - driven by a list, array, or SQL query
        - also supports BPMN loops
        - completion conditions define 
        - process viewer allows drilldown into iteration and loop status
    image_path: "/assets/images/iterationsLoops241.PNG"
row5:
  - title: "Developer-free Simple Form Task"
    excerpt: >
      Allow business users to create simple business processes without APEX development or database skills
        - create simple process data input forms without APEX knowledge
        - store process data in JSON column
    image_path: "/assets/images/SimpleForm.png"
row6:
  - title: "askFlo - GenAI Support for Process Modeler*"
    excerpt: >
      Use GenAI to assist process modelling
        - explain BPMN process models in business English
        - suggest modeling, technical, or business process improvements
        - assist in model error detection and explanation
        - provide text summaries of process models in other languages
        - support for GPT-4o and other LLMs
    image_path: "/assets/images/floAIAdvisor241.png"
row7:
  - title: "Process Viewer Enhancements"
    excerpt: >
      The BPMN Process Viewer, which can be added into your workflow application to show users the current ststus of all the steps in their business process, now is enhanced:
        - open user task steps by clicking on the process viewer
        - highlight model steps with BPMN Color
        - drill into iterating or looping steps*
    image_path: "/assets/images/nls-231-korean-chinese.png"

row9:
  - title: "Introducing the Flows for APEX Enterprise Edition"
    excerpt: >
      To support customers now running Flows for APEX in their mission-critical applications, we are introducing the **Flows for APEX Enterprise Edition** in 24.1.  
        - **Flows for APEX Enterprise Edition** includes additional advanced functionality, starting with 24.1 features process collaboration, iterations and loops, and GenAI modeling support.  
        - Enterprise customers have access to product support to keep their business processes running.
        - All Enterprise Edition licencees also have access to an annual advice session with the product developers.
        - Supporting the Enterprise Edition enables dedicated resources to continue the development, testing, and support of both the Enterprise and Community Editions of Flows for APEX.
  
      The Flows for APEX Enterprise Edition is available on an annual subscription basis from Flowquest Limited. * New features available in the Enterprise Edition.
row10:
  - title: "The Flows for APEX Community Edition remains 100% Open Source"
    excerpt: "The core of Flows for APEX, now called the **Flows for APEX Community Edition**, remains as an open source project. You can continue to share and/or modify it, always under the adherence of the MIT-license.  Support for Community Edition is provided by the Flows for APEX community, via the github issues and discussions pages."
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
{% include feature_row id="row9" type="center"%}
{% include feature_row id="row10" type="center"%}
