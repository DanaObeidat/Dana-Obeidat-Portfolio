
<img src="HydroCode%20logo.png" alt="HydroCode logo" width="300">

# HydroCode — Digital Water Infrastructure & Intelligence

**Project strategy, system architecture and operational governance**  
Developed by Dana Obeidat

## Overview

HydroCode is a water infrastructure project designed to connect fragmented measurements, asset records and operational evidence to traceable decisions.

The proposed architecture brings together water quality, flow, pressure, maintenance and field verification records to support investigation, intervention and management review.

The project includes a working virtual demonstrator and supporting technical, governance and pilot-planning documentation.

## The Design Challenge

A water measurement alone does not establish what happened or what action is justified.

HydroCode addresses the questions between detection and response:

- Is the reading reliable?
- What evidence supports the interpretation?
- What needs verification?
- Who has authority to act?
- How will the outcome be recorded?

## My Design Contribution

I developed the project concept and supporting documentation covering:

- A four-phase technical architecture
- Data sources, measurement assurance and evidence traceability
- Anomaly review, confidence assessment and escalation workflows
- Integration requirements for existing water and asset systems
- Human oversight and controlled automation
- Pilot scope, validation protocols and acceptance criteria
- Implementation planning and technical due diligence materials

## Proposed Operational Workflow

**Receive data → Check measurement quality → Review signals → Verify evidence → Authorise action → Record the outcome**

The design includes **Watch / Verify / Intervene / Escalate** decision states, with responsible reviewers and documented follow-up.

These states support investigation and authorised action. They do not represent guaranteed failure predictions.

## Four-Phase Roadmap

### 1. Foundation

Source identity, asset records, data quality, measurement assurance and baseline indicators.

### 2. Intelligence

Anomaly review, early-warning workflows, confidence assessment and evidence packs.

### 3. Optimisation

Maintenance priorities and operational recommendations subject to verification and operational constraints.

### 4. Integration and Scale

Enterprise interfaces, governance, secure access and planning for multiple sites.

These phases describe the planned development structure. The demonstrator implements selected functions rather than the complete roadmap.

## Working Prototype

A HydroCode virtual demonstrator was deployed on Vercel in August 2026, with a Supabase connection recorded during development testing.

Recorded testing covered:

- Display of synthetic pressure and flow readings
- Navigation across seven interface sections
- Additional local scenario playback for baseline conditions, water quality, energy drift and pressure drop

The additional scenario tests were performed locally; their inclusion in the deployed version has not been established.

[Open HydroCode virtual demonstrator](https://hydrocode-virtual-demonstrator.vercel.app)

The demonstrator uses synthetic data. Its readings and decision outputs are illustrative and should not be used for operational water management.

## Development Status and Validation

**Working virtual demonstrator, documented system design and proposed pilot.**

Prototype testing demonstrates selected interface and workflow behaviour. It does not establish:

- Completed field deployment
- Validated predictive accuracy
- Production readiness
- Certified integrations
- Regulatory approval
- Measured operational savings

Site-specific performance requires testing against agreed baselines and acceptance criteria.

## Proposed Pilot Evaluation

A controlled pilot would examine:

- Data availability, source identity and measurement quality
- Baseline indicators and reproducibility of alerts
- Verification of suspected anomalies
- Human review and intervention authority
- Evidence completeness and audit traceability
- Operational handoff and criteria for further deployment

Pilot scope, duration and success thresholds must be agreed for the selected site.

## Relationship with GIG

HydroCode focuses on water measurements and operational evidence.

GIG focuses on location-specific terrain, drainage, ground conditions and asset exposure.

Their proposed connection would support joint review of operational events and surrounding geospatial risks. This remains a design-level integration.

[View GIG](../GIG/README.md)

## About This Portfolio

This page presents a selected public summary of my independent project design work for employment and professional review.

Detailed internal methods, sensitive information and confidential commercial materials are excluded.

[Contact Dana Obeidat on LinkedIn](https://www.linkedin.com/in/dana-tariq-obeidat/)

[Back to portfolio](../../README.md)
