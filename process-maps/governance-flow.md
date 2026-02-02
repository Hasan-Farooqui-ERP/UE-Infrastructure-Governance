```mermaid
graph TD
    subgraph "AS-IS: THE EMAIL TRAP"
    A[SCADA Support Email] --> B{Shared Inbox}
    B --> C[Staff 1]
    B --> D[Staff 2]
    B --> E[Staff 3...22]
    C & D & E --> F[Duplicate Work / Dropped Tasks]
    F --> G[SLA Breaches < 90%]
    end

    subgraph "TO-BE: ACCOUNTABILITY FRAMEWORK"
    H[SCADA Support Email] --> I[Triage Gate / Lead]
    I --> J{MS Planner Buckets}
    J --> K[Priority 1: SLA Critical]
    J --> L[Priority 2: Data Analysis]
    J --> M[Priority 3: Field Engineering]
    K & L & M --> N[Single Assigned Owner]
    N --> O[Validation / UAT]
    O --> P[SLA Restored > 90%]
    end

    style G fill:#f96,stroke:#333
    style P fill:#9f9,stroke:#333```
