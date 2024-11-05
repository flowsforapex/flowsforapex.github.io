---
layout: splash
permalink: /Flows4APEXFeatures/
header:
  overlay_color: "#000"
  overlay_filter: "0.6"
  overlay_image: /assets/images/RunningFlows.gif
  actions:
    - label: '<i class="far fa-play-circle" aria-hidden="true" style="padding-right: 5px;"></i>Try now'
      url: "https://flowsforapex.com/preview/engine"
      target: "_blank"
    - label: '<i class="fas fa-cloud-download-alt" aria-hidden="true" style="padding-right: 5px;"></i>Download'
      url: "https://github.com/flowsforapex/apex-flowsforapex/releases/download/v23.1/FlowsforAPEX_v23.1.zip"
    - label: '<i class="fas fa-envelope-open-text" aria-hidden="true" style="padding-right: 5px;"></i>Subscribe'
      url: "https://apex.mt-ag.com/ords/portal/r/apex/newsletter-page?p8_source_page=FLOWSFORAPEX"
      target: "_blank"
    - label: "Learn more"
      url: "/latest/getting-started/"
title: 'Flows for APEX Features'
excerpt: >
  Feature Overview
row1:
  - excerpt: "Flows for APEX is a visual workflow automation tool for Oracle APEX that allows users to design, manage, and execute business processes through a graphical interface. Built on the BPMN 2.0 standard, it offers a robust framework for creating complex workflows without extensive coding. With features like real-time monitoring, integration capabilities, and comprehensive error handling, Flows for APEX empowers both developers and non-developers to streamline business operations efficiently."
row2:
  - title: 'Simple but Powerful Workflow for APEX'
    excerpt: >
      Flows for APEX simplfies the creation and management of process automation and workflow applications:
        - Visual workflow automation tool running inside Oracle APEX
        - Simplifies complex business processes with a user-friendly interface
        - Designed for developers, business analysts and business users
    image_path: "/assets/images/RunningFlows.gif"
row3:
  - title: 'BPMN 2.0 -  the standard for process modeling'
    excerpt: >
        Flows for APEX is built on the BPMN 2.0 standard, ensuring compatibility and ease of understanding between business and development:
          - Adheres to the Business Process Model and Notation (BPMN) 2.0 standard
          - Provides a common language for defining business processes, compatible with other BPMN-compliant tools. 
          - Simple enough for your basic processes - but with power to grow when you need it.
          - Already understood by leading GenAI models, including GPT
    image_path: "/assets/images/ShipmentProcess.png"
row4:
  - title: "Creating Workflows"
    excerpt: >
      The Flow Designer offers an intuitive approach to modeling and automating processes:
        - Intuitive Flow Designer with drag and drop interface for creating workflows
        - Configurable properties and conditions allowing APEX-style declarative process definition
        - Model complex processes, including collaboration between processes
        - AI support available for process explanation, translation, and error detection*
    image_path: "/assets/images/modeler-tstz-bind.png"
row5:
  - title: "Managing Workflow Execution"
    excerpt: >
      Flow Monitor helpis in overseeeing and controlling workflow execution
        - Monitor execution with the Flow Monitor tool
        - Dynamicaly assign tasks, due dates and priorities to tasks
        - View real-time status and history of process instances
        - Options to pause, resume or terminate flows as needed.
    image_path: "/assets/images/flowMonitor.png"
row6:
  - title: "Integration with APEX"
    excerpt: >
      Easily integrate Flows for APEX with APEX applications and external systems:
        - Easy integrate workflows into your application using PL/SQL API or the supplied APEX process plugins
        - Optionally integrate with APEX Approval Tasks and Task Lists
        - Use RESTful web services to connect with external systems
        - Start Process Instances from an APEX Automation
    image_path: "/assets/images/APEXTaskList.png"
row7:
  - title: "Monitor, Manage, Audit and Report on Processes and Performance"
    excerpt: >
      Monitor the execution of business processes in your organization.
        - Generate detailed reports on workflow timeline, performance and efficiency
        - Audit trails for compliance and accountability
        - Built-in dashboard showing Process and Task statistics, including processing and waiting times
        - Automated creation of Instance Summary archive document
    image_path: "/assets/images/dashboard.png"
row8:
  - title: "Deploy On Any Modern Oracle APEX Environment "
    excerpt: >
      Flows for APEX can be deployed anywhere APEX runs, from Oracle Free to the largest OCI environment.
        - Requires Oracle database 19c or later, and Oracle APEX 22.1 or later.
        - AskFlo Gen AI support requires Oracle APEX 24.1 and OpenAI GPT api access

      <br>Deploy Globally 
        - Flows for APEX supports 10 major languages ( English, French, German, Spanish, Brazilian Portuguese, 
          Italian, Japanese, Korean, Simplified Chinese and Traditional Chinese).
    image_path: "/assets/images/nls-231-korean-chinese.png"
row9:
  - title: "Flows for APEX Enterprise Edition - advanced functionality, product support, and develop access"
    excerpt: >
      To support customers now running Flows for APEX in their mission-critical applications, we are introducing the **Flows for APEX Enterprise Edition** in 24.1.  
        - **Flows for APEX Enterprise Edition** includes additional advanced functionality, starting in 24.1 with features process collaboration, iterations and loops, and GenAI modeling support.  
        - Enterprise customers have access to product support to keep their business processes running.
        - All Enterprise Edition licencees also have access to an annual advice session with the product developers.
        - Supporting the Enterprise Edition enables dedicated resources to continue the development, testing, and support of both the Enterprise and Community Editions of Flows for APEX.
  
      The Flows for APEX Enterprise Edition is available on an annual subscription basis from Flowquest Limited. * Features available in the Enterprise Edition.
    image_path: "assets/images/F4AEE-logo-onblue.png"
    actions: 
      - url: "/F4AEEOverview"
        target: "_blank"
        class: "btn--info"
        label: '<i aria-hidden="true" style="padding-right: 5px;"></i>See More Details on Enterprise Edition'
row10:
  - title: "100% Open Source"
    excerpt: "Flows for APEX Community Edition is open source. You can share and/or modify it, always under the adherence of the MIT-license."
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
{% include feature_row id="row9" type="left"%}
{% include feature_row id="row8" type="left"%}
{% include feature_row id="row10" type="center"%}
