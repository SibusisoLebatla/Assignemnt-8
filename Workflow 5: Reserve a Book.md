```mermaid
flowchart TD
    A[Start] --> B[Search Book]
    B --> C[Click Reserve]
    C --> D{Available?}
    D -- Yes --> E[Add to Reserved]
    D -- No --> F[Notify Unavailable]
    E --> G[End]
