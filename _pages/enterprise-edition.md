---
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.6"
  overlay_image: /assets/images/RunningFlows.gif
  actions:
  
  - label: '<i class="far fa-play-circle" aria-hidden="true" style="padding-right: 5px;"></i>Try now'
    url: "https://flowsforapex.com/preview/engine"
    target: "_blank"
  - label: '<i class="fas fa-envelope-open-text" aria-hidden="true" style="padding-right: 5px;"></i>Subscribe'
    url: "https://apex.mt-ag.com/ords/portal/r/apex/newsletter-page?p8_source_page=FLOWSFORAPEX"
    target: "_blank"
title: "Flows for APEX Enterprise Edition"
excerpt: >
  Advanced Functionality plus Product Support
row1:
  - excerpt: >
      Building on the success of the open-source [**Flows for APEX**](https://flowsforapex.org) project, we introduce the **Flows for APEX Enterprise Edition** -- the latest features of Flows for APEX with  **additional functionality**, and coming with **product support** and an **annual advisory session** with the product team.  The Flows for APEX Enterprise Edition is available from Flowquest on an annual subscription basis.
func-row-title:
  - title: "Unlock additional functionality, starting with ..."
func-row:
  - image_path: /assets/images/messageflow-241-tutorial7-diagram.png
    alt: "extra functionality"
    title: "Process Collaboration"
    excerpt: "Enable your processes to start, collaborate and message other workflows with Message Flow."
    actions:
      - url: "https://flowsforapex.org/latest/about-messageflow/"
        class: "btn--primary"
        label: "Learn more"
  - image_path: /assets/images/bpmn-iteration-loops.png
    alt: "BPMN Iteration and Loops"
    title: "BPMN Iteration and Loops"
    excerpt: "Loop or repeat process steps for each item on a List or SQL Query, sequentially or in parallel."
    actions:
      - url: "https://flowsforapex.org/latest/iteration-loop-intro/"
        class: "btn--primary"
        label: "Learn more"
  - image_path: /assets/images/ask-flo-model-summary.png
    alt: "AI Support"
    title: "GenAI for Smarter Workflows"
    excerpt: "Gain GenAI assistance in understanding, improving, verifying and translating business processes"
    actions:
      - url: "/docs/license/"
        class: "btn--primary"
        label: "Learn more"  
svc-row-title:
  - title: "Support for Enterprise Use"
svc-row:
  - image_path: /assets/icons/contact_support_66dp_156082.png
    alt: "Product Support"
    title: "Product Support"
    excerpt: "Benefit from professional-grade support to ensure smooth operations and rapid troubleshooting when you need it most."
    url: "/customer-portal"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/icons/alt_route_66dp_156082.png
    alt: "Annual Advisory"
    title: "Annual Advisory Session"
    excerpt: "Receive hands-on guidance from the creators of Flows for APEX, with access to 1 day per year of exclusive advisory services."
    url: "/docs/license/"
    btn_class: "btn--primary"
    btn_label: "Learn more"  
  - image_path: /assets/icons/trending_up_66dp_156082.png
    alt: "Investment protection"
    title: "Protecting Your Investment"
    excerpt: "Support the long-term viability of Flows for APEX and safeguard your investment in applications and processes"
    url: "/docs/layouts/"
    btn_class: "btn--primary"
    btn_label: "Learn more"

row-pricing:
  - title: "Pricing"
    excerpt: >
      Flows for APEX Enterprise Edition is licensed on an annual subscription basis.
      Subscription includes:
        - unlimited licence for one Oracle APEX production instance.
        - included license for development instance
        - included license for test and staging instances
        - included license for any non-active failover systems
        - software updates to future releases, as released.
        - product support and helpdesk
        - annual advisory consultation with the product developers (upto 1 day per year).
  
      Price: EUR 9,900 per year
  
row10:
  - title: "Available Now"
    excerpt: "Contact Flowquest for details"
    actions:
    - url: "mailto:info@flowquest.net"
      target: "_blank"
      class: "btn--info"
      label: '<i class="fab fa-github" aria-hidden="true" style="padding-right: 5px;"></i>Contact Us'
---
{% include feature_row id="row1" type="center"%}
{% include feature_row id="func-row-title" type="center"%}
{% include feature_row id="func-row"%}
{% include feature_row id="svc-row-title" type="center"%}
{% include feature_row id="svc-row"%}
{% include feature_row id="row-pricing" type="left"%}
{% include feature_row id="row10" type="center"%}
