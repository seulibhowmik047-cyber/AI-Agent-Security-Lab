
# AI Agent Blast Radius Assessment

## What is Blast Radius?

Blast radius represents the potential impact if an AI agent identity is compromised.

## Assessment Areas

### 1. Permissions

What resources can the agent access?

### 2. Knowledge Sources

What data sources are connected to the agent?

### 3. Data Sensitivity

Does the agent access:

- Public data?
- Internal data?
- Confidential data?
- Financial information?
- Personal information?

### 4. Tools

What tools and APIs can the agent invoke?

### 5. Downstream Resources

What systems can be reached through the agent?

## Security Principle

The smaller the agent's permissions and connected resources, the smaller the potential blast radius.

## Recommended Control

Apply least privilege and limit knowledge sources to only what is required for the agent's business function.
