---
layout: single
permalink: /deployment-global-support/
title: "Deployment & Global Support"
excerpt: "Deploy Flows for APEX anywhere APEX runs, with support for global audiences in 10 languages."
header:
  overlay_color: "#102532"
  overlay_filter: "0.45"
  overlay_image: /assets/images/nls-231-korean-chinese.png
toc: true
toc_sticky: true
---

Flows for APEX is built to deploy anywhere Oracle APEX runs. Whether you're targeting a single team or a global user base, Flows for APEX provides the flexibility and support needed for production success.

## What It Is

Deployment & Global Support covers the technical requirements, deployment flexibility, and multi-language capabilities of Flows for APEX. This includes APEX and Oracle database version requirements, deployment options ranging from on-premises to cloud, and support for 10 major languages.

## How It Works in Flows for APEX

Flows for APEX deployment is simple:

- **Minimal Requirements**: Oracle database 19c or later, Oracle APEX 24.1 or later. Runs on Oracle Free, enterprise databases, and any OCI environment.
- **Flexible Deployment**: On-premises, cloud, hybrid—Flows for APEX runs wherever Oracle APEX runs.
- **Database Architecture Advantage**: Since the system of record (your application data) and the workflow engine live in the same database, they share the same transaction. Transaction control is simple—no distributed transactions, no eventual consistency challenges. Your process-driven application is always consistent.
- **Multi-Language Support**: Out-of-the-box support for English, French, German, Spanish, Brazilian Portuguese, Italian, Japanese, Korean, Simplified Chinese, and Traditional Chinese.
- **Global Time Zone Support**: Proper handling of time zones, date formatting, and localized messaging across all supported languages.

## Business Capabilities Provided

- Deploy to any consistent hosting environment—whatever you use for APEX is enough
- Simplified application architecture due to single-database design
- Support for global teams across multiple time zones and languages
- Faster time-to-value through straightforward installation and setup
- Strong transaction semantics for mission-critical workflows
- Cost efficiency—no separate middleware or workflow server infrastructure

## Why Flows for APEX

Flows for APEX architecture keeps the system of record and the workflow engine in the same Oracle database, sharing the same transaction. This is fundamentally simpler than distributed workflow solutions that require network calls between application servers and separate workflow engines. When you need ACID compliance and strong consistency guarantees, same-database architecture eliminates complexity.

Many workflow products require separate servers, middleware, or network infrastructure. Flows for APEX deployments scale with your Oracle infrastructure—you already have the database; just add Flows for APEX.

The global language support means your applications can serve international teams without custom localization. And because deployment is simply "APEX + Flows for APEX," your deployment pipelines, backup strategies, and operational patterns remain unchanged.

## Best-Fit Use Cases

- Organizations with existing Oracle APEX infrastructure
- Application deployments that scale from small teams to global organizations
- Mission-critical applications requiring strong transaction semantics
- On-premises or cloud deployments running Oracle database
- Teams standardized on APEX who want workflow without new platform complexity

## Edition Notes

Flows for APEX Community Edition provides full deployment flexibility and global language support. Community Edition support is provided by the community via GitHub issues. **Enterprise Edition** includes:

- Dedicated product support to ensure production applications keep running smoothly
- Advanced admin features for large-scale deployments
- Annual technical advice sessions with product developers
- Priority access to new capabilities

Enterprise Edition support is available on an annual subscription basis from **Flowquest**.

## Related Resources

[Back to Product Overview](/Flows4APEXFeatures/){: .btn .btn--primary }
[Installation Guide](/latest/0100.installation/){: .btn .btn--info }
[System Requirements](/latest/0100.installation/){: .btn .btn--info }
[Explore Enterprise Edition](https://www.flowquest.net){: .btn .btn--info }
