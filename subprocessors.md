# Easy Agent For You – Sub-processor Policy

_Last updated: October 2025_

Easy Agent For You uses a minimal number of third-party service providers (“sub-processors”) to operate the platform securely.  
The app itself **does not process or store** customer data beyond what is necessary to execute automations in real time.  
All user-initiated connections to third-party AI models occur **through the user’s own API keys**, not Easy Agent For You’s.  
This means all LLM requests and data handling are performed directly by the provider the user selected.

---

## General Policy

- Easy Agent For You does **not store raw Slack data or LLM inputs/outputs**.  
- Any message or file from Slack is accessed **only at the time of request**, processed, and discarded immediately after the action is complete.  
- Minimal contextual information may be stored as **vector embeddings** to improve AI responses; these vectors contain no readable text and are deleted when the related agent or account is removed.  
- All data is transmitted securely via **TLS 1.2+** encryption.  
- We evaluate every integration and third-party API for compliance with major privacy frameworks (GDPR, CCPA, ISO 27001).  

---

## Current Sub-processors

| Sub-processor | Purpose |
|----------------|----------|
| **Amazon Web Services (AWS)** | Secure hosting environment and encrypted vector storage 

> **Note:**  
> Connections to AI models (e.g., OpenAI, Anthropic, Gemini, Azure, xAI) are **user-owned integrations**.  
> Users provide their own API keys, and data is sent **directly between the user and the LLM provider**.  
> Easy Agent For You does not intercept, log, or store any content from those exchanges.

---

## Oversight and Review

- Sub-processor relationships are reviewed annually to ensure privacy compliance.  
- Any changes to this list will be updated here before activation.  
- Users may contact us anytime for clarification or data deletion requests.

For questions or concerns, contact:  
**support@easyagentforyou.com**

---

© 2025 Easy Agent For You. All rights reserved.
