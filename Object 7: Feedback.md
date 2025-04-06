```mermaid
stateDiagram-v2
    [*] --> Submitted
    Submitted --> Reviewed : Admin reads feedback
    Reviewed --> Addressed : Action taken
