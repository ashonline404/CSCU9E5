# State Chart

```mermaid
stateDiagram-v2
    [*] --> A
    A --> B : beta
    A --> A : alpha
    B --> C : delta
    B --> A : beta
    C --> B : gamma[P]
