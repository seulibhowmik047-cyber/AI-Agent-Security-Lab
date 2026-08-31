# AI-Agent-Security-Lab
Microsoft AI Agent Security using Entra ID, Defender XDR, and Copilot Studio


## Overview

This lab focuses on securing AI agents in Microsoft environments using:

* Microsoft Entra Agent ID
* Microsoft Entra Conditional Access
* Microsoft Defender XDR
* Microsoft Defender for Cloud Apps
* Microsoft Copilot Studio
* Microsoft Purview
* Microsoft Defender for Cloud

The lab demonstrates how security engineers can discover AI agents, control their identities and permissions, assess their security risks, analyze attack paths, and apply runtime protection.

---

## Objectives

By completing this lab, I will understand how to:

1. Identify AI agents in an organization.
2. Understand Microsoft Entra Agent ID.
3. Secure AI agent authentication.
4. Apply Conditional Access to AI agents.
5. Implement least-privilege access.
6. Manage AI agent identity lifecycle.
7. Discover AI agents using Microsoft Defender XDR.
8. Assess an AI agent's blast radius.
9. Analyze potential attack paths.
10. Understand Copilot Studio agent security.
11. Understand real-time protection for AI agents.
12. Understand Microsoft Purview AI data security.
13. Protect sensitive data used by AI systems.
14. Document AI security controls and evidence.

---

## AI Agent Security Architecture

The security approach is based on multiple security layers:

```text
                    AI Agent
                        |
                        v
               Microsoft Entra ID
                        |
                Identity & Access
                        |
                        v
             Conditional Access
                        |
                        v
              Least Privilege / RBAC
                        |
                        v
             Microsoft Defender XDR
                        |
             Agent Discovery & Risk
                        |
                        v
            Attack Path Analysis
                        |
                        v
        Defender for Cloud / Runtime
               Protection
                        |
                        v
              Microsoft Purview
                        |
              Data Protection / DLP
```

---

## Security Principles

### 1. Identity

Every AI agent should have a controlled identity.

### 2. Least Privilege

Agents should receive only the permissions required to perform their assigned tasks.

### 3. Conditional Access

Conditional Access can be used to control when and how agent identities can access resources.

### 4. Lifecycle Management

Agent identities should be reviewed, recertified, disabled, or retired when they are no longer required.

### 5. Monitoring

AI agent activity should be monitored for suspicious or malicious behavior.

### 6. Runtime Protection

Risky agent actions should be detected and blocked before execution where supported.

### 7. Data Security

Sensitive organizational data must remain protected when accessed or processed by AI.

---

## Lab Modules

| Module | Topic                              | Status        |
| ------ | ---------------------------------- | ------------- |
| 1      | Microsoft Entra Agent Identity     | Documentation |
| 2      | Conditional Access for AI Agents   | Documentation |
| 3      | Agent Identity Lifecycle           | Documentation |
| 4      | Defender XDR Agent Discovery       | Documentation |
| 5      | Blast Radius Assessment            | Documentation |
| 6      | Attack Path Analysis               | Documentation |
| 7      | Copilot Studio Security            | Documentation |
| 8      | Real-Time Protection               | Documentation |
| 9      | Microsoft Purview AI Data Security | Documentation |
| 10     | AI Security Architecture           | Completed     |

---

## Lab Environment

The practical exercises depend on Microsoft licensing and tenant capabilities.

Where the required Azure/Microsoft security licenses are unavailable, the lab records:

* Required configuration
* Expected behavior
* Security reasoning
* Required screenshots/evidence
* Licensing limitations

No credentials, secrets, API keys, or sensitive tenant information are included in this repository.

---

## Key Security Questions

### Identity

* Who is the AI agent?
* What identity does the agent use?
* Is the agent acting on behalf of a user?
* Is the agent autonomous?

### Access

* What resources can the agent access?
* Does the agent have excessive permissions?
* Are Conditional Access policies applied?
* Is least privilege implemented?

### Risk

* What happens if the agent identity is compromised?
* What is the blast radius?
* What downstream resources can be reached?
* Are there dangerous attack paths?

### Runtime

* Can risky actions be detected?
* Can risky actions be blocked before execution?
* Are agent activities monitored?

### Data

* What data sources can the agent access?
* Does the agent have access to sensitive information?
* Are Microsoft Purview controls applied?
* Can sensitive data be prevented from being sent to generative AI applications?

---

## Important Observation

AI agent security is not a single-product problem.

A layered security model is required:

**Microsoft Entra ID → Defender XDR → Defender for Cloud → Microsoft Purview → Copilot Studio**

Identity provides the foundation, Defender provides detection and investigation, Defender for Cloud helps with cloud and AI security posture, Purview protects organizational data, and Copilot Studio provides an environment for building agents.

---

## Conclusion

AI agents introduce a new security boundary because they can access data, invoke tools, communicate with other agents, and perform actions on behalf of users or organizations.

Therefore, security engineers should:

* Discover agents
* Secure agent identities
* Apply least privilege
* Configure Conditional Access
* Monitor agent activity
* Assess blast radius
* Analyze attack paths
* Protect sensitive data
* Enable runtime protection where supported
* Regularly review and retire unnecessary agents

This lab documents the security approach for protecting AI agents in Microsoft environments.
