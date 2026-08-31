# Real-Time Protection for AI Agents

## Objective

Real-time protection is designed to inspect AI agent activity and help identify or block risky actions before they are executed, where supported.

## Security Flow

```text
User Prompt
    |
    v
AI Agent
    |
    v
Tool / Resource Invocation
    |
    v
Security Inspection
    |
    +---- Safe ----> Execute
    |
    +---- Risky ---> Block / Alert
