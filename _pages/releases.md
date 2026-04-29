---
layout: splash
permalink: /releases
title: "Releases"
header:
  overlay_color: "#000"
  overlay_filter: "0.6"
  overlay_image: /assets/images/ahsp-261-manual-def.png
excerpt: >
  Latest release highlights for Flows for APEX, plus links to earlier release feature pages.
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
      - url: "https://flowsforapex.org/dev/async-tasks-and-background-execution/"
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
      - url: "https://flowsforapex.org/dev/task-parameters/"
        target: "_blank"
        class: "btn--primary"
        label: "Learn more"
  - image_path: /assets/images/261-temp-auto-form.png
    alt: "Autoforms"
    title: "Autoforms"
    excerpt: "UserTask Autoform and Start Event Autoform will auto-create input forms so that analysts can create simple data collection forms declaratively without APEX development skills."
row4-title:
  - title: "Earlier Releases"
row4:
  - image_path: /assets/images/rewind-251.png
    alt: "Flows for APEX 25.1"
    title: "Flows for APEX 25.1"
    excerpt: "Highlights include AI service tasks, suspend and resume, rewind for controlled recovery, and stronger operational tooling."
    actions:
      - url: "/Flows4APEX251Features/"
        class: "btn--info"
        label: "Open 25.1 page"
  - image_path: /assets/images/floAIAdvisor241.png
    alt: "Flows for APEX 24.1"
    title: "Flows for APEX 24.1"
    excerpt: "Introduced the first Enterprise Edition wave, including advanced capabilities and early GenAI support for process delivery."
    actions:
      - url: "/Flows4APEX241Features/"
        class: "btn--info"
        label: "Open 24.1 page"
---
{% include feature_row id="row1" type="center"%}
{% include feature_row id="row2-title" type="center"%}
{% include feature_row id="row2"%}
{% include feature_row id="row3"%}
{% include feature_row id="row4-title" type="center"%}
{% include feature_row id="row4" type="left"%}
