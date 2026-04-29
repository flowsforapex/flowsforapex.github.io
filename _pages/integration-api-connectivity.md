---
layout: single
permalink: /integration-api-connectivity/
title: "Integration and API Connectivity"
excerpt: "How Flows for APEX connects BPMN workflows to PL/SQL logic, Oracle APEX applications, REST services, and external systems."
header:
  overlay_color: "#102532"
  overlay_filter: "0.45"
  overlay_image: /assets/images/configureScriptTask.png
toc: true
toc_sticky: true
---

Workflows only deliver value when they can interact with real business systems. In practice that means reading and writing application data, calling services, exchanging events, and coordinating external actions without turning the process model into a tangle of custom glue code.

## What It Is

Integration and API Connectivity in Flows for APEX is the set of capabilities that allow workflow models to interact with Oracle APEX applications, PL/SQL services, REST endpoints, and other enterprise systems.

## How It Works in Flows for APEX

Flows for APEX lets BPMN models invoke technical work in structured ways. Process steps can interact with application logic, service endpoints, and background execution patterns while the BPMN engine retains control over process state and sequencing.

For Oracle-centric teams this is especially important because it means the process model can remain the orchestration layer while existing PL/SQL and APEX assets continue to provide business logic and UI services.

Typical integration patterns include:

- declarative integration of workflow into your APEX application via Flows for APEX plugins that can start and stop a workflow instance, step a workflow forward, and set- and get- process variables.
- alternatively, a PL/SQL-based API to access application logic from workflow steps
- invoking REST services from BPMN tasks
- coordinating asynchronous or long-running technical work
- moving process data cleanly between workflow and application layers

## Business Capabilities Provided

- workflow-driven integration across internal applications and services
- reduced need for bespoke orchestration code in each APEX app
- clearer contracts between process design and system execution
- better support for mixed human and system workflows
- easier extension of process applications over time

## Why Flows for APEX

Flows for APEX gives teams a BPMN-centered orchestration model for integrations, which is useful when service interactions, technical waits, and multi-step process behavior need to be modeled explicitly rather than embedded in application logic.

External automation tools may connect many systems, but they often move orchestration away from the Oracle data and APEX application context. Flows for APEX is a better fit when the core business system already lives in Oracle and teams want tighter governance and lower architectural friction.

Building orchestration directly into PL/SQL packages works up to a point, but process visibility and maintainability degrade as complexity grows. Flows for APEX keeps orchestration visible in BPMN while still reusing existing technical services.

## Best-Fit Use Cases

- APEX applications coordinating multiple backend systems
- service-rich business processes with approval and integration steps
- long-running workflows that involve both user actions and technical calls
- modernization projects that need orchestration without abandoning Oracle-native assets

## Edition Notes

Core integration patterns are part of the broader platform approach. Enterprise Edition adds value where organizations also need advanced operational patterns, AI-related extensions, and commercial support.

## Related Resources

[Read the product overview](/flows4apex/){: .btn .btn--primary }
[Browse documentation](/documentation/){: .btn .btn--info }
[See release highlights](/releases/){: .btn .btn--info }