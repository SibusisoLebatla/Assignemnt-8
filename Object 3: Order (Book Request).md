stateDiagram-v2
    [*] --> Initiated
    Initiated --> Processing : Validated by system
    Processing --> Completed : Book dispatched
    Processing --> Canceled : User cancels or system fails
