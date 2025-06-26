flowchart TD
    A[RaaS Operator<br/>(e.g., DragonForce)] -->|Provides tools, payloads, infrastructure| B[Affiliate<br/>(e.g., Scattered Spider)]
    B -->|Launches attack with ransomware kit| C[Victim<br/>(e.g., M&S)]
    C -->|Pays ransom<br/>(crypto or data leak pressure)| B
    B -->|Shares revenue (e.g., 20%)| A

    classDef boxStyle fill:#f9f,stroke:#333,stroke-width:1px;
    class A,B,C boxStyle;
