---
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.6"
  overlay_image: /assets/images/RunningFlows.gif

title: "Flows for APEX Enterprise Edition"
excerpt: >
  Additional Functionality plus Product Support
row1:
  - excerpt: >
      Building on the success of the open-source [**Flows for APEX**](flows4apex/) project, the **Flows for APEX Enterprise Edition** adds advanced functionality, **product support**, and an **annual advisory session** with the product team.  The 26.1 release wave adds adhoc workflow control for knowledge workers, AI-driven BPMN agents, async execution for long-running work, and stronger low-code developer tooling.
func-row-title:
  - title: "New in 26.1 for Enterprise Edition"
func-row:
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
        class: "btn--primary"
        label: "Learn more"
func-row2:
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
        class: "btn--primary"
        label: "Learn more"
  - image_path: /assets/images/261-temp-auto-form.png
    alt: "Autoforms"
    title: "Autoforms"
    excerpt: "UserTask Autoform and Start Event Autoform will auto-create input forms so that analysts can create simple data collection forms declaratively without APEX development skills."
svc-row-title:
  - title: "Support for Enterprise Use"
svc-row:
  - image_path: /assets/icons/contact_support_66dp_156082.png
    alt: "Product Support"
    title: "Product Support"
    excerpt: >
        Benefit from professional-grade support to ensure smooth operations and rapid troubleshooting when you need it most.
          - Access dedicated **product support** for your team.
          - Resolve issues quickly with expert guidance.
          - Ensure stable operation of your applications with reliable support.
          - Receive timely updates and fixes tailored for your business needs.
    url: "/customer-portal"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/icons/alt_route_66dp_156082.png
    alt: "Annual Advisory"
    title: "Annual Advisory Session"
    excerpt: >
        Receive hands-on guidance from the creators of Flows for APEX, with access to 1 day per year of exclusive advisory services.
          - Get tailored advice for optimizing your workflows.
          - Discuss future enhancements and feature requests.
          - Collaborate with the product team to solve specific challenges.
          - Leverage expert insights to maximize the value of your solution.
    url: "/docs/license/"
    btn_class: "btn--primary"
    btn_label: "Learn more"  
  - image_path: /assets/icons/trending_up_66dp_156082.png
    alt: "Investment protection"
    title: "Protecting Your Investment"
    excerpt: >
      Support the long-term viability of Flows for APEX and safeguard your investment in applications and processes
        - Help secure the future development of both editions.
        - Ensure continued compatibility and feature growth.
        - Protect your investment with sustained innovation and maintenance.
        - Maintain confidence in the stability of your business processes.
    url: "/docs/layouts/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
pricing-row-title:
  - title: "Pricing"
row-pricing:
  - title: "Pricing"
    excerpt: >
      Flows for APEX Enterprise Edition is licensed on an annual subscription basis.
      Subscription includes:
        - unlimited license for one Oracle APEX production instance.
        - included license for development instance
        - included license for test and staging instances
        - included license for any non-active failover systems
        - software updates to future releases, as released.
        - product support and helpdesk
        - annual advisory consultation with the product developers (up to 1 day per year).
  
      Price: EUR 9,900 per year
  
row10:
  - title: "Available Now"
    excerpt: "Contact Flowquest for details"
    actions:
    - url: "mailto:info@flowquest.net"
      target: "_blank"
      class: "btn--info"
      label: '<i class="fab fa-github" aria-hidden="true" style="padding-right: 5px;"></i>Contact Us'
    - url: "https://cal.com/rallen2010/15min"
      target: "_blank"
      class: "btn--info"
      label: '<i class="fab fa-video" aria-hidden="true" style="padding-right:5 px;"></i>Arrange Introductory Call'
---
{% include feature_row id="row1" type="center"%}
{% include feature_row id="func-row-title" type="center"%}
{% include feature_row id="func-row"%}
{% include feature_row id="func-row2"%}
{% include feature_row id="svc-row-title" type="center"%}
{% include feature_row_icon id="svc-row"%}
{% include feature_row id="pricing-row-title" type="center"%}

<div>

    <section id="pricing" class="pricing">
      <container class="footer-container">

        <div class="edition">
            <div class="edition-description">
                <p><strong>Enterprise Edition</strong></p>
                <ul class="edition-features">
                    <li>everything in Community Edition</li>
                    <li>BPMN Iterations and Loops</li>
                    <li>Full BPMN Message Flow, including Inbound Message Queueing</li>
                    <li>AskFlo GenAI Support for Process Modeling</li>
                    <li>Adhoc Sub Processes for knowledge workers</li>
                    <li>AI-driven adhoc sub processes and BPMN agents</li>
                    <li>Async workflow execution for long-running tasks</li>
                    <li>Process Suspend and Resume</li>
                    <li>Process Rewind</li>
                    <li>One Oracle APEX Instance for Production usage</li>
                    <li>included license for Development instance</li>
                    <li>included license for Testing instance</li>
                    <li>included license for non-active failover instance</li>
                    <li>software updates to future releases, as released</li>
                    <li>standard product support and helpdesk</li>
                    <li>annual advisory consultation (up to 8 hrs per year)</li>
                </ul>
                                                
                <p ><strong>EUR 9,900 per year</strong></p>
            </div>
        </div><!-- .edition -->
    
      </container>


    </section><!-- .pricing -->
   </div>
  {% include feature_row id="row10" type="center"%}
