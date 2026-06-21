---
layout: page
title: "Privacy Policy — TestDraft — AI Test Case Generator for Jira (BYOK)"
permalink: /testdraft-ai-test-case-generator-for-jira-byok/privacy/
---

# Privacy Policy — TestDraft: AI Test Case Generator for Jira (BYOK)

**Publisher:** Steelyman Lab
**Effective Date:** 21 June 2026
**Marketplace:** Atlassian Marketplace (Forge-hosted app)

---

## 1. Overview

TestDraft is a Jira app that uses your own Large Language Model (LLM) API key ("Bring Your Own Key") to generate test cases from Jira issues. Because you supply the API key, **you control which AI provider receives your data** — Steelyman Lab never routes your Jira content through our own servers.

This policy explains what data we collect, why we collect it, how long we keep it, and what your rights are.

---

## 2. Data We Collect

| Data | Why We Collect It | Where It Is Stored |
|---|---|---|
| **LLM API Key** (e.g. an OpenAI or Anthropic key you provide) | To authenticate requests to your chosen LLM provider on your behalf | Encrypted in Atlassian Forge KV Storage, scoped to your Jira site |
| **Jira Issue Content** (summary, description, acceptance criteria of issues you act on) | To send to your configured LLM provider and generate test cases | **Not stored by us.** Transmitted to your LLM provider only at the moment you click "Generate", then discarded |
| **Per-Issue Generation History** (last 3 generated results per issue) | So you can review previous outputs without re-running generation | Atlassian Forge KV Storage, scoped to your Jira site |
| **Per-Workspace Monthly Usage Counter** (a simple integer count of generations) | To enforce freemium tier limits | Atlassian Forge KV Storage, scoped to your Jira site |

We do **not** collect:

- Names, email addresses, or other identity information
- Payment information (billing is handled entirely by the Atlassian Marketplace)
- Any Jira content beyond the specific issue you are actively generating test cases for
- Analytics, crash reports, or behavioural tracking data

---

## 3. How Your Data Is Used

- **LLM API Key** — used only to make API calls to your chosen provider. It is never shared with third parties other than that provider, and only when you trigger a generation.
- **Jira Issue Content** — passed directly to your LLM provider in real time. We treat this as transient: we do not log, cache, or store it after the API call completes.
- **Generation History** — displayed inside the TestDraft panel within Jira. Not used for analytics or shared with anyone.
- **Usage Counter** — checked against your plan's monthly limit. Not linked to any personal identity.

---

## 4. Third-Party Services

### 4.1 Atlassian Forge

TestDraft runs entirely on the **Atlassian Forge** platform. All stored data (API key, history, usage counter) lives in Forge KV Storage, which is managed by Atlassian under their own infrastructure and data-residency policies. Atlassian's privacy policy applies to data stored on Forge: [https://www.atlassian.com/legal/privacy-policy](https://www.atlassian.com/legal/privacy-policy).

### 4.2 Your Chosen LLM Provider

When you click "Generate", the content of the selected Jira issue is sent to the LLM provider whose API key you have configured (for example, OpenAI, Anthropic, or another compatible provider). **You are responsible for ensuring your use of that provider complies with their terms of service and any applicable data-processing obligations.** We recommend reviewing your provider's privacy policy before using TestDraft with sensitive issue content.

Steelyman Lab has no affiliation with any LLM provider and receives no data from those calls.

### 4.3 Atlassian Marketplace

Subscription and billing are managed by Atlassian Marketplace. Steelyman Lab does not collect or process payment details.

---

## 5. Data Retention

| Data | Retention Period |
|---|---|
| LLM API Key | Retained until you remove it in the app settings, or until the app is uninstalled from your Jira site |
| Jira Issue Content | **Not retained.** Discarded immediately after the LLM API call completes |
| Generation History (last 3 per issue) | Retained until the app is uninstalled, or until you clear history in the app (if that option is available), or upon a verified deletion request |
| Monthly Usage Counter | Reset automatically at the start of each calendar month; deleted upon app uninstallation |

When you uninstall TestDraft, Atlassian's Forge platform permanently deletes all app-scoped storage data associated with your site.

---

## 6. Data Security

- Your LLM API key is **encrypted at rest** using Atlassian Forge's built-in secret storage mechanisms.
- All data in transit is protected by TLS/HTTPS.
- TestDraft operates under the principle of least privilege: it requests only the Jira scopes necessary to read the issue content you are actively working with.
- Steelyman Lab employees do not have routine access to your stored data.

---

## 7. Your Rights

Regardless of where you are located, we honour the following rights:

- **Access** — You can request a copy of any personal data we hold about you.
- **Correction** — You can update your LLM API key at any time within the app.
- **Deletion** — You can request deletion of your data at any time (see Section 8). Uninstalling the app also triggers deletion of all Forge-stored data.
- **Portability** — You can request an export of your stored data in a machine-readable format.
- **Objection / Restriction** — You can ask us to stop processing your data for a specific purpose.

**GDPR (EU/EEA/UK users):** Our legal basis for processing is **legitimate interest** in providing the service you have installed and configured. Where applicable (e.g. for API key storage), the basis is **performance of a contract** (i.e. delivering the app functionality you have subscribed to).

**CCPA (California users):** We do not sell or share personal information for cross-context behavioural advertising. You have the right to know, delete, and opt out of sale (though no sale occurs).

---

## 8. Contact & Deletion Requests

For any privacy questions, data access requests, or deletion requests, please contact:

**Steelyman Lab**
📧 [CONTACT_EMAIL]

Please include "Privacy Request — TestDraft" in the subject line and identify your Jira site URL so we can locate and action your data promptly. We will respond within **30 days**.

---

## 9. Children's Privacy

TestDraft is a professional developer tool intended for use in workplace Jira environments. We do not knowingly collect data from anyone under the age of 16.

---

## 10. Changes to This Policy

If we make material changes to this policy, we will update the effective date at the top and, where feasible, post a notice in the Atlassian Marketplace listing. Continued use of the app after the updated date constitutes acceptance of the revised policy.

---

*This policy was last updated on 21 June 2026.*

---

> **📌 Note for publisher:** Replace `[CONTACT_EMAIL]` with your support or privacy contact address before publishing.