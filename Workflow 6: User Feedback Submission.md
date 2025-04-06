```mermaid
flowchart TD
    A[Start] --> B[Fill Feedback Form]
    B --> C[Validate Inputs]
    C --> D{Valid?}
    D -- Yes --> E[Submit Feedback]
    E --> F[Notify Admin]
    F --> G[End]
    D -- No --> H[Show Error]
