```mermaid
graph TD
    subgraph Development
        A((Code Changes))
    end
    subgraph Operations
        B((CI/CD))
    end
    A -->|Trigger| B
    B -->|Deploy| A
```
