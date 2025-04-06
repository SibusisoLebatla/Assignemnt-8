```mermaid
stateDiagram-v2
    [*] --> Initiated
    Initiated --> Verified : Validated
    Verified --> Successful : Paid
    Verified --> Failed : Insufficient funds
 
