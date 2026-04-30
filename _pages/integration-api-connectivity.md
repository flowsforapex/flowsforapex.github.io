---
layout: single
permalink: /integration-api-connectivity/
title: "Integration & API Connectivity"
excerpt: "Simple, declarative ways to integrate workflow into APEX applications and external systems."
header:
  overlay_color: "#102532"
  overlay_filter: "0.45"
  overlay_image: /assets/images/APEXTaskList.png
toc: true
toc_sticky: true
---

Business Processes and workflows don't exist in isolation. They must integrate seamlessly with APEX applications, coordinate with external systems, and allow your business logic to start, monitor, and control process instances.

## What It Is

Integration & API Connectivity is the layer that lets you embed workflow into your APEX applications and connect to external systems. It provides PL/SQL APIs, APEX plugins, and RESTful web services—all designed to integrate workflow into your application architecture with minimal friction.

## How It Works in Flows for APEX

Flows for APEX provides:

- **APEX Process Plugins**: Simple, declarative plugins that integrate workflow into APEX processes—Start Process, Monitor Status, Complete Steps, Update Variables—all configured without code.
- **PL/SQL APIs**: Full programmatic control over process instances, steps, and variables when you need custom integration logic.
- **APEX Human Tasks Integration**: Seamless integration with APEX Approval Tasks and Task Lists—leveraging APEX's built-in human task infrastructure.
- **RESTful Web Services**: Connect APEX workflows to external systems via standard REST interfaces.
- **APEX Automations**: Start process instances from APEX Automations for event-driven workflow triggers.
- **Declarative configuration**: Most integrations use APEX-style declarative configuration, not code—keeping your APEX way of working intact.

The entire integration model is built to be simple, easy, and *APEX-like*—meaning your APEX developers will recognize the patterns and feel immediately at home.

## Business Capabilities Provided

- Workflow feels native to APEX—not bolted on or foreign to your application architecture
- Faster application development through declarative integration plugins
- Reduced custom code through API-based control of workflow instances and data
- Easier maintenance of process-aware applications over time
- Cleaner separation between application UI, business logic, and process control
- Support for both synchronous and asynchronous workflow patterns
- Simplified task management through APEX Human Tasks integration

## Why Flows for APEX

Flows for APEX is built to integrate _into_ APEX applications, not require separate systems or middleware. The plugins are declarative and APEX-native—you configure them the way you configure other APEX plugins. The PL/SQL APIs are straightforward and work naturally with your database logic.

Many workflow approaches require middle-tier application servers, network calls, or special integration patterns. Flows for APEX keeps integration simple because everything lives in the same database—your system of record and your workflow engine share the same transaction and the same data model.

External workflow engines add integration overhead, network latency, and separate security models. Flows for APEX integration is frictionless for APEX teams.

## Best-Fit Use Cases

- APEX applications where workflow is a functional requirement, not an afterthought
- Processes that need to coordinate across APEX pages and PL/SQL logic
- Applications using APEX Approval Tasks or Task Lists that want to extend into richer workflow
- Event-driven process triggering through APEX Automations
- Systems where application performance depends on single-database, single-transaction execution

## Edition Notes

Core integration and API functionality are available in Flows for APEX Community Edition. **Enterprise Edition** provides additional integration features, message flow collaboration between process instances, richer API capabilities for complex scenarios, and dedicated support for mission-critical integrations.

## Related Resources

[Back to Product Overview](/Flows4APEXFeatures/){: .btn .btn--primary }
[API Documentation](/latest/0200.getting-started/){: .btn .btn--info }
[Integration Patterns](/latest/getting-started/){: .btn .btn--info }
[Explore Enterprise Edition](https://www.flowquest.net){: .btn .btn--info }
