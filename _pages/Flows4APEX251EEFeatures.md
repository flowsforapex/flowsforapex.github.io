---
layout: splash
permalink: /Flows4APEX251Features/
header:
  overlay_color: "#000"
  overlay_filter: "0.6"
  overlay_image: /assets/images/oh-flowsforapex-251-sm.png
title: "New in Enterprise Edition for 25.1"
excerpt: >
  Release highlights for Flows for APEX Enterprise Edition 25.1.
row1:
  - excerpt: >
      Flows for APEX Enterprise Edition 25.1 introduced major runtime control and recovery capabilities,
      practical AI integration patterns, and stronger operational tooling for process applications on Oracle APEX.
row2-title:
  - title: "New in Enterprise Edition for 25.1"
row2:
  - image_path: /assets/images/suspend-251.png
    alt: "Suspend and Resume"
    title: "Suspend and Resume"
    excerpt: "Suspend running process instances safely and resume them later when operations can continue."
    actions:
      - url: "https://flowsforapex.org/latest/suspend-resume/"
        target: "_blank"
        class: "btn--primary"
        label: "Learn more"
  - image_path: /assets/images/rewind-251.png
    alt: "Process Rewind"
    title: "Process Rewind"
    excerpt: "Rewind a running process to an earlier point to recover from bad data, incorrect decisions, or failed execution paths."
    actions:
      - url: "https://flowsforapex.org/latest/rewind/"
        target: "_blank"
        class: "btn--primary"
        label: "Learn more"
  - image_path: /assets/images/ai-service-task-tax-example-diagram.png
    alt: "AI Service Tasks"
    title: "AI Service Tasks"
    excerpt: "Integrate GenAI services directly into BPMN workflows using controlled, model-driven service task patterns."
    actions:
      - url: "https://flowsforapex.org/latest/"
        target: "_blank"
        class: "btn--primary"
        label: "Learn more"
row3:
  - image_path: /assets/images/APEXTaskList.png
    alt: "APEX Human Tasks Integration"
    title: "Improved APEX Human Tasks Integration"
    excerpt: "Use tighter APEX Human Task integration for better inbox experiences, cleaner hand-offs, and stronger operational usability."
  - image_path: /assets/images/dashboard.png
    alt: "Logging and Debugging"
    title: "Enhanced Logging and Debugging"
    excerpt: "Gain better visibility into process execution with improved event logging and debugging support for day-to-day operations."
  - image_path: /assets/images/ask-flo-model-summary.png
    alt: "GenAI Modeling Support"
    title: "GenAI for Smarter Workflow Delivery"
    excerpt: "Use GenAI-assisted process understanding and modeling support to improve workflow design quality and team productivity."
    actions:
      - url: "/posts/genai-helps-bpmn/"
        class: "btn--primary"
        label: "Learn more"
row4:
  - title: "Enterprise Edition"
    excerpt: >
      Flows for APEX Enterprise Edition builds on the open-source Community Edition with additional advanced functionality,
      product support, and advisory access to help teams run business-critical workflows with confidence.
    actions:
      - url: "mailto:info@flowquest.net"
        target: "_blank"
        class: "btn--info"
        label: "Contact us"
---

{% include feature_row id="row1" type="center" %}
{% include feature_row id="row2-title" type="center" %}
{% include feature_row id="row2" %}
{% include feature_row id="row3" %}
{% include feature_row id="row4" type="center" %}
