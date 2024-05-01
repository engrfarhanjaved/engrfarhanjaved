flowchart TB
    subgraph Identification
    A[Trigger: Change request from client or internal stakeholders] --> B[Initiator: Project manager or relevant team member]
    B --> C[Document Variation: Detail the requested variation]
    end

    subgraph Assessment
    D[Review: Project team reviews the variation request] --> E[Scope Impact Analysis: Evaluate impact on scope, schedule, cost, and quality]
    E --> F[Feasibility Check: Determine if variation is feasible]
    end

    subgraph Approval
    G[Internal Approval]
    F --> |Within limits| G
    G --> I[Subcontractor Notification: Inform subcontractor of approved variation]
    G --> |Exceeds limits| H[Higher authority approval]
    H --> I
    I[Client Approval: Obtain client approval if contractual agreements are affected]
    end

    subgraph Implementation
    I --> J[Subcontractor executes varied work]
    J --> K[Monitoring: Project team monitors progress and quality]
    end

    subgraph Verification
    K --> L[Quality Check: Ensure varied work meets standards]
    L --> M[Client Acceptance: Seek if required]
    end

    subgraph Documentation
    M --> N[Record Keeping: Document all details related to the variation]
    N --> O[Filing: File documents appropriately]
    end

    subgraph Closure
    O --> P[Completion Confirmation: Confirm varied work completed satisfactorily]
    P --> Q[Finalization: Close out variation process]
    Q --> R[Review: Conduct post-implementation review]
    end

