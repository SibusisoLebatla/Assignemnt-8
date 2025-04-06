```mermaid
stateDiagram-v2
    [*] --> Assigned
    Assigned --> InProgress : Staff accepts
    InProgress --> Completed : Staff finishes
    Assigned --> Reassigned : Reallocation
