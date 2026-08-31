# Conditional Access for AI Agents

## Purpose

Conditional Access evaluates authentication requests using configured signals and policies.

## Authentication Flow

```text
AI Agent
   |
   | Request Token
   v
Microsoft Entra ID
   |
   | Conditional Access Evaluation
   |
   +---- Condition satisfied ----> Token Issued
   |
   +---- Condition failed -------> Access Blocked/Limited
   |
   v
Target Resource
   |
   v
Token Validation
   |
   v
Authorization
