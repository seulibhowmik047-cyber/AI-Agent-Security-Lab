# AI Security Architecture

## Layered Security Model

```text
                    AI / Agents
                         |
                         v
                Microsoft Entra ID
                         |
                  Identity Security
                         |
                         v
               Conditional Access
                         |
                         v
                  Least Privilege
                         |
                         v
               Microsoft Defender XDR
                         |
              Detection & Investigation
                         |
                         v
             Defender for Cloud
                         |
                Security Posture
                         |
                         v
          Defender for Cloud Apps
                         |
                  Runtime Security
                         |
                         v
               Microsoft Purview
                         |
             Data Security & DLP
