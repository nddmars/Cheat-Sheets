graph LR
    A[RaaS Operator] -- "Provides RaaS tools & payloads" --> B(Affiliate)
    B -- "Revenue share (typically 20%)" --> A
    A -- "Deploys attack using RaaS kit" --> C(Victim)
    C -- "Victim pays ransom (crypto, PR damage)" --> A
