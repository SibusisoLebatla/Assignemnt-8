```mermaid
flowchart TD
    A[Start] --> B[Check Outstanding Fines]
    B --> C[Choose Payment Option]
    C --> D[Verify Payment Info]
    D --> E{Valid?}
    E -- Yes --> F[Process Payment]
    F --> G[Update Records]
    G --> H[End]
    E -- No --> I[Show Error]
