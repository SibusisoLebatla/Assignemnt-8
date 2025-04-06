```mermaid
stateDiagram-v2
    [*] --> Registered
    Registered --> Active : Email confirmed
    Active --> Suspended : Rule violation
    Suspended --> Active : Appeal granted
    Active --> Deleted : User deletes account



Explanation:

Key States: Registered, Active, Suspended, Deleted
Requirement Mapping:
FR-002: User registration and login functionality.
FR-009: Allow users to delete accounts.
