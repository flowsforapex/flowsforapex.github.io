---
layout: splash
permalink: /Flows4APEX261Features/
header:
  overlay_color: "#000"
  overlay_filter: "0.6"
  overlay_image: /assets/images/ahsp-261-manual-def.png
title: "New in Enterprise Edition for 26.1"
excerpt: >
  Release highlights for Flows for APEX Enterprise Edition 26.1.
row1:
  - excerpt: >
      This page summarizes the 26.1 wave for Flows for APEX Enterprise Edition, including new runtime flexibility,
      AI-driven orchestration, async execution support, and developer tooling improvements.
row2-title:
  - title: "New in Enterprise Edition for 26.1"
row2:
  - image_path: /assets/images/ahsp-261-manual-def.png
    alt: "Adhoc Sub Processes"
    title: "Adhoc Sub Processes"
    excerpt: "Give knowledge workers controlled flexibility by letting them choose the next relevant action at runtime while BPMN still defines the guardrails and completion rules."
    actions:
      - url: "/adhoc-subprocesses-basics/"
        class: "btn--primary"
        label: "Learn more"
  - image_path: /assets/images/ahsp-261-autonomous-def.png
    alt: "AI-Driven BPMN Agents"
    title: "AI-Driven BPMN Agents"
    excerpt: "Move from recommendations to hybrid or fully autonomous BPMN-defined agents while keeping workflow behavior auditable and governed."
    actions:
      - url: "/adhoc-subprocesses-ai-agents/"
        class: "btn--primary"
        label: "Learn more"
  - image_path: /assets/images/async-task-261.png
    alt: "Async Workflow Execution"
    title: "Async Workflow Execution"
    excerpt: "Push selected long-running work into background async execution for better resilience, improved user experience, and safer orchestration of external services or AI calls."
    actions:
      - url: "https://flowsforapex.org/latest/async-tasks-and-background-execution/"
        target: "_blank"
        class: "btn--primary"
        label: "Learn more"
row3:
  - image_path: /assets/images/261-ai-dev-bundle.png
    alt: "AI Development Support Toolkit"
    title: "AI-Powered Development Support Toolkit"
    excerpt: "This release includes XSD definition of Flows for APEX BPMN extensions, read-only MCP schema scripts, and Flows for APEX skill definitions to accelerate consistent AI-powered workflow development across teams."
  - image_path: /assets/images/261-dev-features.png
    alt: "Subjects, Task Parameters and JSONPath"
    title: "Developer Improvements"
    excerpt: "Use declarative task subjects, task parameters and JSONPath variable expressions to define cleaner task contracts, simpler data mapping, and more maintainable process applications."
    actions:
      - url: "https://flowsforapex.org/latest/task-parameters/"
        target: "_blank"
        class: "btn--primary"
        label: "Learn more"
row4:
  - title: "Enterprise Edition"
    excerpt: >
      Flows for APEX Enterprise Edition builds on the open-source Community Edition with additional advanced functionality, including Adhoc Sub Process and AI orchestration features, plus product support from Flowquest.
    actions:
      - url: "mailto:info@flowquest.net"
        target: "_blank"
        class: "btn--info"
        label: "Contact us"
      - url: "https://cal.com/rallen2010/15min"
        target: "_blank"
        class: "btn--info"
        label: "Arrange Introductory Zoom Call"
---

{% include feature_row id="row1" type="center" %}
{% include feature_row id="row2-title" type="center" %}
{% include feature_row id="row2" %}
{% include feature_row id="row3" %}
{% include feature_row id="row4" type="center" %}
