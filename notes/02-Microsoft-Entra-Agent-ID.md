# Microsoft Entra Agent ID

## Purpose

Microsoft Entra Agent ID provides an identity foundation for AI agents.

The agent identity can be used to control and govern access to organizational resources.

## Agent Identity

An AI agent can have an identity represented within Microsoft Entra.

The identity may use credentials such as:

- Certificate
- Managed identity
- Other supported authentication mechanisms

## Why Agent Identity Matters

Without proper identity controls, an AI agent may receive excessive access.

If the agent is compromised, an attacker may potentially use its permissions to reach downstream resources.

## Security Controls

Security engineers should:

- Identify the agent
- Define its purpose
- Assign least privilege
- Control credentials
- Apply Conditional Access where supported
- Review permissions
- Monitor activity
- Disable or retire unused agents
