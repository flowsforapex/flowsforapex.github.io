---
layout: splash
permalink: /Flows4APEX251Features/
header:
  overlay_color: "#000"
  overlay_filter: "0.6"
  overlay_image: /assets/images/RunningFlows.gif
--  actions:
--    - label: '<i class="far fa-play-circle" aria-hidden="true" style="padding-right: 5px;"></i>Try now'
--      url: "https://flowsforapex.com/preview/engine"
--      target: "_blank"
--    - label: '<i class="fas fa-cloud-download-alt" aria-hidden="true" style="padding-right: 5px;"></--i>Download'
--      url: "https://github.com/flowsforapex/apex-flowsforapex/releases/download/v24.1/FlowsForAPEX_v24.1.zip"
--    - label: '<i class="fas fa-envelope-open-text" aria-hidden="true" style="padding-right: 5px;"></--i>Subscribe'
--      url: "https://apex.mt-ag.com/ords/portal/r/apex/newsletter-page?p8_source_page=FLOWSFORAPEX"
--      target: "_blank"
--    - label: "Learn more"
--      url: "/latest/getting-started/"
title: 'Flows for APEX v25.1'
excerpt: >
  New Features now available in v25.1 
row1:
  - excerpt: "Flows for APEX version 25.1 introduces powerful new features for both Community and Enterprise Editions.  The **Flows for APEX Community Edition** remains as a free-of-charge, community supported product - also with new features. The **Flows for APEX Enterprise Edition** adds more features for enterprise deployment and management, and comes with **support** from Flowquest.
Major features include:"
row2:
  - title: 'Build AI into your Workflows with AI Service Tasks'
    excerpt: >
      Embed AI-powered decisioning and generative tasks directly into business processes with simple, configurable service tasks for smarter automation:
        - Drive process routing with AI-based decision support outputs.
        - Generate summaries, reports, or personalised communications automatically.
        - Use RAD and vector search to ground AI in Oracle data.
        - Low-code design makes AI use simple and repeatable.
    image_path: "/assets/images/ai-service-task-tax-example-diagram.png"
row3:
  - title: "Suspend, Rewind and Resume*"
    excerpt: >
      Gain precise control over long-running workflows by suspending, resuming, or rewinding processes at any step without losing state or context.
        - Suspend process instances safely for investigation or waiting events.
        - Resume execution exactly where the process previously stopped.
        - Rewind selected steps for correction or re-execution when required.
        - Improve resilience and reliability of complex, long-lived workflows.
    image_path: "/assets/images/rewind-prev-gw-after-rw-to-abc.png"
row4:
  - title: "Better APEX Human Task Integration"
    excerpt: >
      Deliver smoother user experiences with tighter integration between APEX applications and workflow human tasks, improving usability, control, and developer productivity.
        - Support task owner and administrator assignment from the controlling workflow.
        - New plugin for declarative return of task state and outcome.
        - Better removal and cleanup of cancelled or expired tasks.
        - Integration of task definition and state into the Flows for APEX monitor.
    image_path: "/assets/images/AHT-configure-task-action.png"
row5:
  - title: "Enhancements to Event Logging"
    excerpt: >
      Gain clearer visibility into workflow execution with flexible, fine-grained event logging, improving both audit readiness and developer debugging capabilities:
        - Now captures fine-grained step-level processing events.
        - Flexible logging levels at system, diagram, or process instance.
        - Highlight instances and steps executed with admin intervention.
        - Improved control of log archiving and purging automations.
        - Flexible logging meets monitoring, forensic audit, and debugging needs.
    image_path: "/assets/images/log-instance-timeline-251.png"
row6:
  - title: "Other Developer Features"
    excerpt: >
      New developer-focused enhancements streamline modelling, improve error handling, and provide clearer visual cues for easier design and maintenance:
        - Script Task Error Boundary Events let PL/SQL throw BPMN errors.
        - Model-defined process naming simplifies deployment and version management.
        - Diagram badges highlight metadata directly within process diagrams.
        - Updated Flow Viewer plugin built on web component architecture.
        - Bundling plugins delivered as APEX Component Groups.
    image_path: "/assets/images/script-task-bpmn-error-exec2.png"
row7:
  - title: "Introducing the Flows for APEX Enterprise Edition"
    excerpt: >
      To support customers now running Flows for APEX in their mission-critical applications, we are introducing the **Flows for APEX Enterprise Edition** in 24.1.  
        - **Flows for APEX Enterprise Edition** includes additional advanced functionality, starting with 24.1 features process collaboration, iterations and loops, and GenAI modeling support.  
        - Enterprise customers have access to product support to keep their business processes running.
        - All Enterprise Edition licencees also have access to an annual advice session with the product developers.
        - Supporting the Enterprise Edition enables dedicated resources to continue the development, testing, and support of both the Enterprise and Community Editions of Flows for APEX.
  
      The Flows for APEX Enterprise Edition is available on an annual subscription basis from Flowquest Limited. * New features available in the Enterprise Edition.
    image_path: "assets/images/F4AEE-logo-onblue.png"
    actions: 
      - url: "https://www.flowquest.net"
        target: "_blank"
        class: "btn--info"
        label: "More Info"
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
{% include feature_row id="row4" type="left"%}
{% include feature_row id="row5" type="left"%}
{% include feature_row id="row6" type="left"%}
{% include feature_row id="row7" type="left"%}
{% include feature_row id="row10" type="center"%}
