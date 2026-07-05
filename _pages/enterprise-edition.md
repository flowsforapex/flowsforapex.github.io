---
layout: splash
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.6"
  overlay_image: /assets/images/RunningFlows.gif

title: "Flows for APEX Enterprise Edition"
excerpt: >
  Advanced workflow capabilities, product support, and advisory services for mission-critical Oracle APEX process applications.
row1:
  - excerpt: >
      Building on the success of the open-source [**Flows for APEX**](/flows4apex/) project, **Flows for APEX Enterprise Edition** is the supported edition for organizations running business-critical workflows. It adds advanced functionality, product support, and annual advisory access so your team can deliver and operate BPMN process applications with confidence.
func-row-title:
  - title: "Enterprise Edition Overview"
func-row:
  - image_path: /assets/images/RunningFlows.gif
    alt: "Enterprise Runtime Capabilities"
    title: "Advanced Runtime Capabilities"
    excerpt: "Run complex BPMN workflows with enterprise-grade capabilities including process collaboration, iterations and loops, message flow enhancements, and operational controls."
    actions:
      - url: "/flows4apex/"
        class: "btn--primary"
        label: "Learn more"
  - image_path: /assets/images/ahsp-261-autonomous-def.png
    alt: "Adaptive AI and Knowledge Work"
    title: "Adaptive AI and Knowledge Work"
    excerpt: "Enable Adhoc Sub Processes for knowledge workers and move from AI recommendations to hybrid or autonomous BPMN-defined agents with governance built in."
    actions:
      - url: "/Flows4APEX261Features/"
        class: "btn--primary"
        label: "See 26.1 highlights"
  - image_path: /assets/images/async-task-261.png
    alt: "Support and Confidence"
    title: "Support and Confidence"
    excerpt: "Combine platform capability with responsive product support and annual advisory services to reduce delivery risk and keep process operations stable over time."
    actions:
      - url: "/customer-portal/"
        class: "btn--primary"
        label: "Learn more"
func-row2:
  - image_path: /assets/images/261-ai-dev-bundle.png
    alt: "AI Development Support Toolkit"
    title: "AI-Powered Development Support Toolkit"
    excerpt: "Includes XSD definition of Flows for APEX BPMN extensions, read-only MCP schema scripts, and Flows for APEX skill definitions to accelerate consistent AI-powered workflow development across teams."
  - image_path: /assets/images/rewind-251.png
    alt: "Enterprise Administration Controls"
    title: "Enterprise Administration Support"
    excerpt: "Support real-world production operations with logging, archiving, and essential administrator controls including process suspend, rewind, and resume capabilities introduced in 25.1."
    actions:
      - url: "/Flows4APEX251Features/"
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
partners-row-title:
  - title: "Reseller and Implementation Partners"
  - excerpt: "Our partner network provides regional coverage and implementation expertise for Enterprise Edition rollout and adoption."
partners-row:
  - image_path: /assets/icons/alt_route_66dp_156082.png
    alt: "Reseller and Implementation Partners"
    title: "Reseller and Implementation Partners"
    excerpt: "Our partner network provides regional coverage and implementation expertise for Enterprise Edition rollout and adoption."
partners-join-row:
  - title: "Join the Partners Program"
    excerpt: "Partner with Flowquest as a reseller or implementation specialist."
    actions:
      - url: "mailto:info@flowquest.com?subject=Join%20the%20Partners%20Program"
        class: "btn--primary"
        label: "Get info"
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
{% include feature_row id="partners-row-title" type="center"%}

<style>
  .partner-logo-grid {
    display: grid;
    grid-template-columns: repeat(4, minmax(0, 1fr));
    gap: 1rem;
    margin: 1rem 0 2rem;
  }

  .partner-logo-card {
    align-items: center;
    border: 1px solid #d7dce2;
    border-radius: 8px;
    color: #3e4a57;
    display: flex;
    font-size: 0.95rem;
    font-weight: 600;
    justify-content: center;
    min-height: 110px;
    padding: 0.75rem;
    text-align: center;
    text-decoration: none;
    background: #ffffff;
  }

  .partner-logo-card img {
    display: block;
    max-height: 54px;
    max-width: 100%;
    object-fit: contain;
  }

  .partner-logo-card .partner-logo-placeholder {
    color: #6a7686;
    font-size: 0.9rem;
    font-weight: 600;
  }

  .partner-logo-note {
    color: #596678;
    font-size: 0.9rem;
    margin: 0.25rem 0 1.5rem;
    text-align: center;
  }

  @media (max-width: 900px) {
    .partner-logo-grid {
      grid-template-columns: repeat(2, minmax(0, 1fr));
    }
  }

  @media (max-width: 560px) {
    .partner-logo-grid {
      grid-template-columns: 1fr;
    }
  }
</style>

<div class="partner-logo-grid">
  <a class="partner-logo-card" href="#" aria-label="Talan">
    <img src="/assets/logos/talan-logo.svg" alt="Talan" />
  </a>
  <a class="partner-logo-card" href="#" aria-label="HyPlus"><img src="/assets/logos/HyPlus_rgb.png" alt="Hyand" /></a>
  <a class="partner-logo-card" href="#" aria-label="Solicon-IT"><img src="/assets/logos/solicon-logo-400.png" alt="Solicon-IT" /></a>
  <a class="partner-logo-card" href="#" aria-label="TGC"><img src="/assets/logos/TGC_blue.png" alt="TGC" /></a>
  <a class="partner-logo-card" href="#" aria-label="Radicle"><img src="/assets/logos/Radicle-red-900-450png.png" alt="Radicle" style="max-height: 100px; max-width: 90%;" /></a>
  <a class="partner-logo-card" href="#" aria-label="Miracle"><img src="/assets/logos/miracle-logo.png" alt="Miracle" style="max-height: 120px; max-width: 90%;"/></a>
  <!--
  <a class="partner-logo-card" href="#" aria-label="Partner Logo 6"><span class="partner-logo-placeholder">Partner Logo 6</span></a>
  <a class="partner-logo-card" href="#" aria-label="Partner Logo 7"><span class="partner-logo-placeholder">Partner Logo 7</span></a>
  <a class="partner-logo-card" href="#" aria-label="Partner Logo 8"><span class="partner-logo-placeholder">Partner Logo 8</span></a>
  -->
</div>

{% include feature_row id="partners-join-row" type="center"%}
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
