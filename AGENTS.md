# Agent Instructions

This repository contains a standalone HR Assistant built with Microsoft Foundry, Foundry IQ, and Azure AI Search.

- Keep the assistant independent from Student Services or other agents unless an approved architecture explicitly adds an integration.
- Put deterministic safety and escalation ahead of model answers.
- Ground only on approved general HR reference content; never use employee records or personal data as knowledge.
- Do not log message bodies, credentials, or employee data by default.
- Treat HRIS status and benefit transactions as separate, gated integrations. Do not imply they are enabled by this baseline.
- Use Microsoft Entra ID, managed identity, least privilege, and source-system authorization.
- Preserve the portal and Python paths in the customer build guide.

This project was built with the microsoft-foundry skill. Before working on or answering questions about Foundry agents, read the microsoft-foundry skill first. If you are in VS Code, read the vscode-microsoft-foundry skill first.
