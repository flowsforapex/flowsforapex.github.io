---
layout: splash
permalink: /Flows4APEX261Features/
header:
  overlay_color: "#000"
  overlay_filter: "0.6"
  overlay_image: /assets/images/RunningFlows.gif
title: "Flows for APEX v26.1"
excerpt: >
  Further details on v26.1 adhoc subprocess innovation for knowledge workers, AI-guided execution, and BPMN-defined autonomous agents
row1:
  - excerpt: "Flows for APEX v26.1 introduces a major upgrade in adaptive workflow execution with Adhoc Sub Processes. Adhoc Sub Processes let teams handle real knowledge work inside BPMN while preserving visibility, control, and completion governance. This page provides further details on the 26.1 Adhoc Sub Process release wave and the surrounding capabilities that make these patterns practical in production environments. Features marked with an asterisk (*) are Enterprise Edition highlights."
row2:
  - title: "Adhoc Sub Processes for Knowledge Workers*"
    excerpt: >
      Adhoc Sub Processes bring structured flexibility to dynamic work:
        - let knowledge workers choose the next relevant action at runtime
        - support investigations, case handling, and exception-driven service work
        - keep explicit BPMN completion rules, auditability, and process visibility
    image_path: "/assets/images/RunningFlows.gif"
    actions:
      - url: "/adhoc-subprocesses-basics/"
        class: "btn--info"
        label: "Learn more"
row3:
  - title: "AI-Driven Adhoc Sub Processes and BPMN-Defined Agents*"
    excerpt: >
      AI can now operate inside Adhoc Sub Process control modes, from guidance to autonomy:
        - recommendation mode proposes the next-best activity to run
        - hybrid mode combines human approval with AI orchestration
        - autonomous mode runs BPMN-defined agents inside modeled process boundaries
        - all modes stay aligned with workflow governance and audit trails
    image_path: "/assets/images/floAIAdvisor241.png"
    actions:
      - url: "/adhoc-subprocesses-ai-agents/"
        class: "btn--info"
        label: "Learn more"
row4:
  - title: "Async Workflow Execution for Long-Running Tasks*"
    excerpt: >
      Adhoc Sub Process and AI workloads often include slow external calls. v26.1 adds stronger async execution support:
        - push long-running steps into background workflow sessions
        - improve resilience for external APIs, AI services, and delayed responses
        - maintain clear orchestration and recoverability for background work
    image_path: "/assets/images/async-task-261.png"
    actions:
      - url: "https://flowsforapex.org/dev/async-tasks-and-background-execution/"
        target: "_blank"
        class: "btn--info"
        label: "Learn more"
row5:
  - title: "AI-Powered Developer Support Toolkit"
    excerpt: >
      This release includes XSD definition of Flows for APEX BPMN extensions, read-only MCP schema scripts, and Flows for APEX skill definitions to accelerate consistent AI-powered workflow development across teams.
    image_path: "/assets/images/task-subjects261.png"
row6:
  - title: "Developer Enhancements: Task Parameters and JSONPath"
    excerpt: >
      Developer productivity is improved with stronger data contracts and mapping tools:
        - task parameters define cleaner step inputs and outputs
        - JSONPath variable expressions simplify access to structured process data
        - low-code integration patterns become easier to configure and maintain
    image_path: "/assets/images/configureUserTask.png"
    actions:
      - url: "https://flowsforapex.org/dev/task-parameters/"
        target: "_blank"
        class: "btn--info"
        label: "Learn more"
row7:
  - title: "Auto-Created Input Forms (In Development)"
    excerpt: >
      UserTask Autoform and Start Event Autoform are currently under development for the 26.1 cycle and are designed to auto-create input forms for faster process delivery and simpler data capture.
    image_path: "/assets/images/configureUserTaskApproval.png"
row9:
  - title: "Enterprise Edition"
    excerpt: >
      Flows for APEX Enterprise Edition builds on the open-source Community Edition with additional advanced functionality, including Adhoc Sub Process and AI orchestration features, plus product support from Flowquest.
    actions:
      - url: "mailto:info@flowquest.net"
        target: "_blank"
        class: "btn--info"
        label: "Contact us"
---

{% include feature_row id="row1" type="center" %}
{% include feature_row id="row2" type="left" %}
{% include feature_row id="row3" type="right" %}
{% include feature_row id="row4" type="left" %}
{% include feature_row id="row5" type="left" %}
{% include feature_row id="row6" type="right" %}
{% include feature_row id="row7" type="left" %}
{% include feature_row id="row9" type="center" %}
