```mermaid
flowchart TD
    A[Start] --> B[Admin Assigns Task]
    B --> C[Task Notification to Staff]
    C --> D[Staff Accepts or Rejects]
    D --> E{Accepted?}
    E -- Yes --> F[Begin Task]
    E -- No --> G[Reassign Task]
    F --> H[Mark as Complete]
    H --> I[End]
