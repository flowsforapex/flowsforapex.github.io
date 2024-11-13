---
layout: splash
permalink: /news
header:
  overlay_color: "#000"
  overlay_filter: "0.6"
  overlay_image: /assets/images/RunningFlows.gif
  actions:
    - label: '<i class="fas fa-cloud-download-alt" aria-hidden="true" style="padding-right: 5px;"></i>Download Community Edition'
      url: "https://flowsforapex.com/downloads/FlowsForAPEX_v24.1.zip"
    - label: '<i class="fas fa-envelope-open-text" aria-hidden="true" style="padding-right: 5px;"></i>Subscribe'
      url: "https://apex.mt-ag.com/ords/portal/r/apex/newsletter-page?p8_source_page=FLOWSFORAPEX"
      target: "_blank"
    - label: "Learn more"
      url: "/documentation/"
excerpt: >
  Oracle APEX extension for BPMN based workflows
row1:
  - excerpt: "Flows for APEX is a powerful workflow engine extension for Oracle APEX applications. Model your business processes with BPMN, develop your process steps in APEX, and monitor your running processes with the Flows for APEX application. Flows for APEX was created as a community project by team of experienced APEX professionals to meet the workflow requirements in many APEX applications."
row2:
  - title: >
      Watch "What's New in Flows for APEX v24.1" on APEX Office Hours
    excerpt: >
      Join Niels de Bruijn and Richard Allen from the Flows for APEX team as they demo Flows for APEX v24.1 new features in a live Oracle APEX Office Hours session on October 10th: What's New in Flows for APEX v 24.1.  See demos for:
        - User Task type "Simple Forms"
        - New sample app "Simple Process Starter"
        - JSON support for process variables
        - Support for iterations and loops
        - Improved process collaboration and messaging
        - Generative AI support
    image_path: "/assets/images/241-oh-global-flows-sm.png"
    actions: 
      - url: "/Flows4APEX241Features/"
        target: "_blank"
        class: "btn--info"
        label: '<i aria-hidden="true" style="padding-right: 5px;"></i>See More Details on 24.1'
      - url: "https://youtu.be/zSOBjRgtou8?si=fgIEo7CVSl1BlYHO"
        target: "_blank"
        class: "btn--info"
        label: '<i class="far fa-play-circle" aria-hidden="true" style="padding-right: 5px;"></i>Watch the Replay'
row3:
  - title: >
      Flows for APEX Enterprise Edition nearing completion
    excerpt: >
      **Flows for APEX Enterprise Edition** is nearing completion and will be available very shortly under license from Flowquest Limited.  The Enterprise Edition is a new, supported edition of Flows for APEX that includes additional functionality and comes with product support from Flowquest.   Stay tuned for more information coming soon.
    image_path: "assets/images/F4AEE-logo-onblue.png"
    actions: 
      - url: "/enterprise-edition"
        target: "_blank"
        class: "btn--info"
        label: '<i aria-hidden="true" style="padding-right: 5px;"></i>See More Details on Enterprise Edition'
row10:
  - title: "Builds on the successful Flows for APEX Project"
    excerpt: "Flows for APEX is a project of the APEX community. Now available with support and additional functionality on a product basis from Flowquest Limited"
---
{% include feature_row id="row1" type="center"%}
{% include feature_row id="row3" type="left"%}
{% include feature_row id="row2" type="left"%}
{% include feature_row id="row10" type="center"%}
