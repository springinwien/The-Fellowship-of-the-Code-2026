```mermaid
flowchart TD

%% Start
A([Fellowship member detects danger])

%% Decision 1
B{Send emergency alert?}

%% Alert path
C[Alert is sent to the Fellowship]
E[Location and situation are shared]
F[Fellowship receives the alert]

%% Decision 2
G{Can they respond in time?}

%% Positive outcome
H[Help arrives]
I([End: Situation is stabilized])

%% Negative outcome (delay)
J[Help is delayed]
K([End: Risk remains])

%% No alert path
D[No alert is sent]
L[User continues alone]
M([End: Danger increases])

%% Flow
A --> B
B -- Yes --> C
B -- No --> D

C --> E --> F --> G

G -- Yes --> H --> I
G -- No --> J --> K

D --> L --> M

%% Styling
style A fill:#e0f2fe,stroke:#0284c7,stroke-width:2px
style B fill:#fef9c3,stroke:#ca8a04,stroke-width:2px
style G fill:#fef9c3,stroke:#ca8a04,stroke-width:2px

style I fill:#dcfce7,stroke:#16a34a,stroke-width:2px
style K fill:#fee2e2,stroke:#dc2626,stroke-width:2px
style M fill:#fee2e2,stroke:#dc2626,stroke-width:2px
```
