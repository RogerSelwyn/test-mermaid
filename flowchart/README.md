Starup sequence flow

```mermaid
sequenceDiagram
participant I as Integration
participant M as Module
participant J as 9006
I->>M: system/deviceinformation
M->>J: system/deviceinformation
M->>J: system/information
M->>J: system/time
```
