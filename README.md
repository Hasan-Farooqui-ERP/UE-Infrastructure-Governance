# Uisce Éireann Infrastructure Governance & SLA Optimization

### Overview
This repository documents the governance framework and task orchestration logic used to stabilize data accuracy and engineering SLAs for national infrastructure projects (Uisce Éireann).

### The Challenge
* **Legacy Tracking:** Siloed task management leading to SLA breaches.
* **Data Accuracy:** Metrics falling below the required 90% threshold due to reporting latency.

### The Solution: Agile Task Orchestration
I implemented a centralized accountability framework using **MS Planner** to bridge the gap between field telemetry and office-based data analysis.

#### Governance Logic:
1. **Intake:** SCADA telemetry gaps identified via daily data analysis.
2. **Allocation:** Automated task buckets in MS Planner assigned to field engineers.
3. **Validation:** Multi-stage UAT (User Acceptance Testing) for data corrections.
4. **Compliance:** All workflows mapped to NIS (Network and Information Systems) security standards.

### Impact
* **SLA Restoration:** Improved and maintained 90%+ data accuracy within 6 weeks.
* **Transparency:** 100% visibility for stakeholders on transformation milestones.

### [Process Transformation: From Email Trap to Managed Accountability](./process-maps/governance-flow.md)
