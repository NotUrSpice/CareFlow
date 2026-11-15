<div align="center">

# CareFlow Kerala

### Relaunching Kerala's Public Healthcare Referral Network

[![Ideathon](https://img.shields.io/badge/IEEE%20PELS%20Society-Disha%20CET-2563EB?style=for-the-badge)](https://github.com/NotUrSpice/CareFlow)
[![Achievement](https://img.shields.io/badge/Achievement-2nd%20Place-F4B400?style=for-the-badge)](https://github.com/NotUrSpice/CareFlow)

*Transforming referrals into intelligent care pathways.*

</div>

---

## Overview

Kerala's public healthcare network already includes Primary Health Centres (PHCs), Taluk Hospitals, District Hospitals, and Medical Colleges. The challenge addressed by **CareFlow Kerala** is not simply a lack of facilities—it is how patients move between the facilities that already exist.

CareFlow proposes a **digital coordination layer** for the public healthcare referral network. It aims to help patients reach the appropriate level of care, give facilities better visibility into capacity, and maintain continuity as patients move across the system.

> Kerala doesn't need more hospitals. It needs a smarter way to connect the ones it already has.

CareFlow is not intended to replace hospital management systems or act as an AI doctor. Its focus is referral coordination, capacity-aware routing, and continuity of care.

## The problem

The ideathon concept identifies a system-wide imbalance:

- Medical colleges can become overwhelmed with cases that may be manageable at lower-level facilities.
- PHCs and Taluk Hospitals may operate below their available capacity.
- Patients may bypass nearby facilities because they are uncertain about where to seek care.
- Tertiary hospitals can experience long waiting times.

### Why the existing referral journey can fail

- Paper-based referrals can lack a shared digital audit trail.
- Patients may need to register repeatedly at different facilities.
- Patients can drop off between referral stages.
- Facilities may not have visibility into the current load and capacity of other facilities.
- Patient information and care history may not follow them seamlessly through the network.

## Proposed solution

CareFlow connects existing healthcare facilities through a coordinated referral pathway.

The proposed system combines:

1. **AI-assisted intake** to support initial information collection and urgency classification.
2. **Referral intelligence** to identify an appropriate facility based on the patient's needs and network conditions.
3. **Capacity-aware routing** to account for facility availability and system-wide load.
4. **Digital Referral Passport** to carry referral information and relevant care context between facilities.
5. **Continuous care coordination** to improve visibility across the referral journey.

CareFlow is a coordination and decision-support concept. It does not replace clinical judgment or independently diagnose patients.

## How it works

The proposed patient journey follows six stages:

1. **Patient arrival** — The patient first approaches a healthcare facility, such as a PHC.
2. **AI-assisted intake** — Relevant information is collected to support initial triage and urgency classification.
3. **Referral intelligence engine** — The system considers the patient's requirements and available network information.
4. **Digital Referral Passport** — A digital referral record captures the referral context and accompanies the patient.
5. **Right facility** — The patient is directed through the referral network to an appropriate facility.
6. **Continuous care** — The referral journey and relevant information remain connected across participating facilities.

## The Digital Referral Passport

The Digital Referral Passport is CareFlow's central continuity feature.

Rather than making patients restart the administrative process at every facility, the proposed passport carries key referral information across the network.

### Proposed information in the passport

- Referral origin and destination.
- Digital referral authorization/signature.
- Urgency classification recorded at intake.
- Appointment window, where confirmed.
- Referring doctor's notes.
- Referral status updates for patients and providers.

**One document. Full continuity.**

The passport is intended to reduce repeated registrations, missing referral context, and uncertainty during transfers between facilities.

## The industrial engineering behind CareFlow

CareFlow places Operations Research and systems engineering at the centre of its proposed coordination model. AI is a supporting layer; the wider objective is to improve the flow of patients through a network of facilities.

| Engineering area | Role in CareFlow |
|---|---|
| Queue Optimization | Support dynamic load balancing across healthcare facilities. |
| Demand Forecasting | Estimate patient inflow and anticipate demand. |
| Capacity-Aware Routing | Consider available beds, staff, and facility capacity. |
| Bottleneck Analysis | Identify constraints that contribute to delays and congestion. |
| AI-Assisted Intake | Support initial information processing and urgency classification. |
| Facility Routing | Identify a suitable referral path based on patient requirements and network conditions. |

These are the proposed engineering capabilities described in the ideathon concept; they should not be read as claims of a fully deployed real-time optimization system.

## Who benefits?

### Patients
- A clearer path to the appropriate level of care.
- Reduced uncertainty about where to go.
- Less repeated registration and better referral continuity.
- The potential for shorter waits through improved network coordination.

### Doctors and healthcare staff
- Better referral context before a patient arrives.
- More accessible patient history across referral stages.
- Potentially reduced administrative repetition.

### Hospitals
- Better visibility into network-level demand and capacity.
- More balanced distribution of patients.
- Improved awareness of potential bottlenecks.

### Public healthcare administration
- A system-wide view of referral patterns and capacity.
- Better information for planning and resource allocation.
- A pathway toward more efficient use of existing infrastructure.

## Implementation roadmap

The concept proposes a phased rollout:

| Phase | Scope |
|---|---|
| Pilot | Two districts over six months, focusing on PHC-to-District Hospital routing. |
| District rollout | Expansion across all 14 districts, with facility integration and capacity dashboards. |
| Statewide network | Kerala-wide coverage and more extensive referral and network intelligence. |

These are proposed deployment stages, not completed implementation milestones.

## What CareFlow is — and isn't

**CareFlow is:**
- A coordination layer for existing public healthcare facilities.
- A referral-support and capacity-awareness concept.
- A way to connect PHCs, Taluk Hospitals, District Hospitals, and Medical Colleges.
- A proposed application of Industrial Engineering to public healthcare delivery.

**CareFlow is not:**
- A replacement for hospital management systems.
- An AI doctor or autonomous diagnostic system.
- A replacement for clinical judgment or healthcare professionals.
- A proposal to build an entirely new hospital network.

## Future scope

Potential next steps include:

- Prototyping the Digital Referral Passport.
- Building a facility directory and referral workflow.
- Simulating patient flows and facility queues.
- Developing capacity dashboards with sample or authorized data.
- Testing routing and load-balancing strategies using simulated scenarios.
- Exploring a limited pilot with relevant healthcare stakeholders and approvals.

## Recognition

**2nd Place — IEEE PELS Society, Disha CET**

## Repository

[github.com/NotUrSpice/CareFlow](https://github.com/NotUrSpice/CareFlow)

---

<div align="center">

*CareFlow Kerala — Every referral becomes a connected care journey.*

</div>
