---
layout: splash
permalink: /flows4apex/
header:
  overlay_color: "#000"
  overlay_filter: "0.6"
  overlay_image: /assets/images/RunningFlows.gif
title: "Flows for APEX: Product Overview"
excerpt: >
  Community and Enterprise Edition capabilities across design, execution, integration, operations, and AI-enabled delivery.
row1:
  - excerpt: "Flows for APEX is a BPMN-based business process modeling and workflow platform for Oracle APEX with both Community and Enterprise Edition offerings. Use this page as your map of the product areas and follow each section for deeper detail."
row2:
  - title: "BPMN Modeling Foundation"
    excerpt: >
      Model business processes with the BPMN 2.0 standard:
        - visual process design in the embedded modeler
        - business and technical collaboration on one notation
        - progressive complexity from simple flows to advanced orchestration
        - extension properties for Flows for APEX execution behavior
    image_path: "/assets/images/RunningFlows.gif"
    actions:
      - url: "/bpmn-modeling-foundation/"
        class: "btn--info"
        label: "Explore BPMN foundation"
row3:
  - title: "Runtime Execution and Control"
    excerpt: >
      Execute and manage process instances reliably in production:
        - start, monitor, and complete workflow instances
        - assign and route work to people and systems
        - suspend, resume, and recover running process work
        - inspect execution history for operational transparency
    image_path: "/assets/images/flowMonitor.png"
    actions:
      - url: "/runtime-execution-control/"
        class: "btn--info"
        label: "See runtime execution"
row4:
  - title: "Human Tasks and User Experience"
    excerpt: >
      Deliver clear and actionable work to business users:
        - user and approval tasks integrated with Oracle APEX experiences
        - improved task subjects and inbox readability
        - configurable task payloads and hand-off data
        - support for high-volume operational workflows
    image_path: "/assets/images/APEXTaskList.png"
    actions:
      - url: "/human-tasks-user-experience/"
        class: "btn--info"
        label: "See human task UX"
row5:
  - title: "Integration and API Connectivity"
    excerpt: >
      Connect workflows to your application landscape:
        - PL/SQL APIs and APEX plugins for in-app integration
        - service tasks for REST-based system interactions
        - event-driven and asynchronous orchestration patterns
        - clean contracts for robust external integration
    image_path: "/assets/images/configureScriptTask.png"
    actions:
      - url: "/integration-api-connectivity/"
        class: "btn--info"
        label: "See integration patterns"
row6:
  - title: "Monitoring, Audit, and Operations"
    excerpt: >
      Operate workflows with enterprise-grade observability:
        - instance tracking and timeline visibility
        - process and task performance statistics
        - auditable execution logs and summaries
        - controls to investigate and manage exceptions
    image_path: "/assets/images/dashboard.png"
    actions:
      - url: "/monitoring-audit-operations/"
        class: "btn--info"
        label: "See operational visibility"
row7:
  - title: "Adaptive Work with Adhoc Sub Processes"
    excerpt: >
      Support knowledge work inside controlled BPMN boundaries:
        - model optional activities and runtime discretion
        - allow repeatable or conditional activity execution
        - preserve completion governance and auditability
        - generate runtime UIs from process definitions
    image_path: "/assets/images/ahsp-261-manual-def.png"
    actions:
      - url: "/adhoc-subprocesses-basics/"
        class: "btn--info"
        label: "Adhoc Sub Process basics"
row8:
  - title: "AI-Assisted and Agentic Execution"
    excerpt: >
      Add AI while retaining process governance and explainability:
        - recommendation, hybrid, and autonomous control modes
        - BPMN guardrails around AI decision making
        - runtime rationale capture for traceability
        - support for modern AI integration patterns
    image_path: "/assets/images/ahsp-261-autonomous-def.png"
    actions:
      - url: "/adhoc-subprocesses-ai-agents/"
        class: "btn--info"
        label: "AI and agents"
row9:
  - title: "Deployment, Editions, and Commercial Support"
    excerpt: >
      Choose the edition and support model that matches your needs:
        - Community Edition for open-source workflow delivery
        - Enterprise Edition for advanced capability and support
        - annual subscription model with product helpdesk and advisory
        - clear path from experimentation to mission-critical operations
    image_path: "assets/images/F4AEE-logo-onblue.png"
    actions: 
      - url: "/"
        class: "btn--info"
        label: "Enterprise Edition details"
row10:
  - title: "Community Edition is Open Source"
    excerpt: "Flows for APEX Community Edition is open source under the MIT license and developed with strong community participation."
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
{% include feature_row id="row8" type="left"%}
{% include feature_row id="row9" type="left"%}
{% include feature_row id="row10" type="center"%}
