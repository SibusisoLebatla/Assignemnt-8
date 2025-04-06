```mermaid
stateDiagram-v2
    [*] --> Registered
    Registered --> Active : Email confirmed
    Active --> Suspended : Rule violation
    Suspended --> Active : Appeal granted
    Active --> Deleted : User deletes account

 


