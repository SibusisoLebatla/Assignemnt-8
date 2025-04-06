```mermaid
flowchart TD
    A[Start] --> B[Search for Book]
    B --> C[View Details]
    C --> D[Check Availability]
    D --> E{Available?}
    E -- Yes --> F[Checkout Book]
    E -- No --> G[Show Message]
    F --> H[Update Inventory]
    H --> I[Send Confirmation]
    I --> J[End]
 
