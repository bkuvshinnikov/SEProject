# Flow: Create Item

```mermaid
flowchart TD
    A[User opens Create Item form] --> B[User enters Name]
    B --> C[User enters Description]
    C --> D[User selects Color]
    D --> E[User submits form]

    E --> F{Is Name valid?}
    F -- No --> G[Show validation error]
    G --> B

    F -- Yes --> H[Create new Item]
    H --> I[Save Item to database]
    I --> J[Return success response]
    J --> K[Display updated item list]
    K --> L[Show newly created Item]
