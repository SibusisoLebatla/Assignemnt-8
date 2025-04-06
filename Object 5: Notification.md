```mermaid
stateDiagram-v2
    [*] --> Queued
    Queued --> Sent : System triggers event
    Sent --> Read : User reads it
 
