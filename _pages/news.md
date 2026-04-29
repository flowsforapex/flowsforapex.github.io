---
layout: splash
permalink: /news
title: "News"
header:
  overlay_color: "#000"
  overlay_filter: "0.6"
  overlay_image: /assets/images/RunningFlows.gif
excerpt: >
  Latest release announcements, product updates, and events for Flows for APEX Enterprise Edition.
row1:
  - excerpt: "This page is the release and announcements feed for Flows for APEX. Find version highlights, event replays, and product updates for Community and Enterprise Edition."
row4:
  - title: >
      Preview what's coming in Flows for APEX v26.1
    excerpt: >
       Flows for APEX Enterprise Edition v26.1 brings a major step forward for adaptive, AI-assisted workflow automation.  Key highlights include:
        - adhoc sub processes for knowledge workers
        - AI-driven adhoc sub processes with recommendations or fully autonomous BPMN-defined agents
        - async workflow execution for long-running tasks
        - usability improvements with task subjects
        - developer enhancements with task parameters and JSONPath variable expressions
        - UserTask Autoform and Start Event Autoform currently under development.
  
       Flows for APEX Enterprise Edition v26.1 is completing testing and will be available during May 2026.
    image_path: "/assets/images/ahsp-261-autonomous-def.png"
    actions: 
      - url: "/Flows4APEX261Features/"
        target: "_blank"
        class: "btn--info"
        label: '<i aria-hidden="true" style="padding-right: 5px;"></i>See 26.1 Highlights'
      - url: "mailto:info@flowquest.net"
        target: "_blank"
        class: "btn--info"
        label: '<i class="fas fa-envelope-open-text" aria-hidden="true" style="padding-right: 5px;"></i>Contact Flowquest'
row2:
  - title: >
      Watch "What's New in Flows for APEX v25.1" replay on APEX Office Hours
    excerpt: >
      Watch the replay of Moritz Klein and Richard Allen from the Flows for APEX team as they demoed our current production release, Flows for APEX v25.1, on a Oracle APEX Office Hours session on September 25th, 2025.  What's New in Flows for APEX v 25.1 - **Smarter BPMN Workflows with AI, Suspend and Rewind**.  See demos for:
        - AI Service Tasks - Adding GenAI into your Workflow
        - Suspend/Resume for running processes
        - Rewind to recover from bad data or bad user decisions
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
row3:
  - title: >
      Flows for APEX Enterprise Edition now shipping!
    excerpt: >
      **Flows for APEX Enterprise Edition** is now available  under license from Flowquest Limited.  The Enterprise Edition is a supported edition of Flows for APEX that includes additional functionality and comes with product support from Flowquest.
    image_path: "assets/images/F4AEE-logo-onblue.png"
    actions: 
      - url: "/"
        target: "_blank"
        class: "btn--info"
        label: '<i aria-hidden="true" style="padding-right: 5px;"></i>See More Details on Enterprise Edition'
row10:
  - title: "Builds on the successful Flows for APEX Project"
    excerpt: "Flows for APEX is a project of the APEX community. Now available with support and additional functionality on a product basis from Flowquest Limited"
---
{% include feature_row id="row1" type="center"%}
{% include feature_row id="row4" type="left"%}
{% include feature_row id="row2" type="left"%}
{% include feature_row id="row3" type="left"%}
{% include feature_row id="row10" type="center"%}
