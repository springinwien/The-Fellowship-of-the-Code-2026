```mermaid

flowchart TD

%% --------------------
%% STYLES
%% --------------------
classDef success fill:#d4edda,stroke:#155724,stroke-width:2px,color:#155724;
classDef warning fill:#fff3cd,stroke:#856404,stroke-width:2px,color:#856404;
classDef danger fill:#f8d7da,stroke:#721c24,stroke-width:2px,color:#721c24;
classDef info fill:#e2e3ff,stroke:#3f51b5,stroke-width:1.5px,color:#3f51b5;

%% --------------------
%% START
%% --------------------
A([Emergency situation occurs]) --> B[Open Fellowship Companion]
B --> C{Send alert?}

class A,B,C info;

%% --------------------
%% YES PATH
%% --------------------
C -->|Yes| D[Send Emergency Alert]
D --> E[Share location]
D --> F[Report danger details]

E --> G[Build alert package]
F --> G

class D,E,F,G info;

%% Sending process
G --> H{Sending successful?}

H -->|Yes| I[Alert sent]

H -->|No| H1[Retry sending]
H1 --> H2{Retry successful?}

H2 -->|Yes| I
H2 -->|No| L([No alert was sent])

class H,H1,H2 warning;
class O2 danger;

%% --------------------
%% RECEPTION
%% --------------------
I --> J{Alert received by contacts?}

J -->|Yes| K([Contacts receive alert])
K --> K1[Help is being organized]

class I,J,K,K1 success;

J -->|No| J1[Delivery failure or no response]
J1 --> J2[Attempt alternative delivery channel]

J2 --> J3{Eventually received?}

J3 -->|Yes| K
J3 -->|No| O1([Alert not received])
O1 --> O3[Help is delayed]

class J1,J2,J3 warning;
class O1,O3 danger;

%% --------------------
%% NO PATH
%% --------------------
C -->|No| L[No alert sent]
L --> M[User continues without alert]
M --> N[No help is organized]

class L,M,N warning;
