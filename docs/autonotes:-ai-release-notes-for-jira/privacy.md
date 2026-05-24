---
layout: page
title: "Privacy Policy — AutoNotes: AI Release Notes for Jira"
permalink: /autonotes:-ai-release-notes-for-jira/privacy/
---

# Privacy Policy — AutoNotes: AI Release Notes for Jira

**Publisher:** Steelyman Lab
**App:** AutoNotes: AI Release Notes for Jira (Atlassian Marketplace)
**Effective date:** 2026-05-24

---

## 1. Overview

AutoNotes is an Atlassian Connect app that automatically drafts release notes from your Jira issues using AI. We take your privacy seriously and have designed the app to collect only what is strictly necessary to make it work. This policy explains what data we collect, why we collect it, how long we keep it, and what rights you have.

---

## 2. What Data We Collect

### 2.1 Atlassian Connect Authentication Data

| Data | Purpose |
|---|---|
| **Tenant `clientKey`** | Uniquely identifies your Jira site so we can store your settings against the correct tenant. |
| **Shared secret** | Used to verify that incoming requests genuinely come from your Atlassian instance (JWT signature verification). |

This data is exchanged automatically by the Atlassian Connect framework when you install the app. We do not use it for any purpose beyond authentication and authorization.

### 2.2 Per-Tenant Settings

When you configure the app, we store the following preferences linked to your `clientKey`:

- **Tone** (e.g., formal, casual)
- **Brand name**
- **Default Confluence space key**
- **Custom prompt suffix** (any additional instructions you add to the AI prompt)

These settings exist solely to personalize the output of your release notes. They are never shared with third parties or used to train AI models.

### 2.3 Anonymous Usage Counts

We record aggregated, non-personal counters per tenant:

- Number of release note generations per month
- Number of Jira issues processed
- Approximate token counts consumed

These numbers help us monitor service health, manage API costs, and plan capacity. **No individual user identities, names, or email addresses are stored alongside these counts.**

---

## 3. What We Do NOT Collect

- We do **not** store the content of your Jira issues, comments, or fields after a generation request is complete.
- We do **not** store the generated release note text on our servers.
- We do **not** collect any personal data about individual Jira users (names, email addresses, avatars, etc.).
- We do **not** use your data to train or fine-tune any AI model.

---

## 4. How We Use Your Data

| Data | Why we use it |
|---|---|
| `clientKey` + shared secret | Authenticate and authorize API requests from your Jira site |
| Per-tenant settings | Apply your preferences when generating release notes |
| Anonymous usage counts | Monitor system health, track API usage, manage billing |

We do not sell, rent, or trade any data to third parties for marketing or advertising.

---

## 5. Third-Party Services

To provide the service, we share limited data with the following sub-processors:

### 5.1 OpenAI (AI Generation)

When you trigger a generation, the content of the relevant Jira issues (summaries, descriptions, fix versions) is sent to **OpenAI's API** to produce the draft release notes. This data is transmitted over HTTPS and is subject to [OpenAI's API data usage policy](https://openai.com/policies/api-data-usage-policies). Under OpenAI's current API terms, data sent via the API is **not used to train their models** and is retained by OpenAI for a limited period for abuse-monitoring purposes only.

### 5.2 Cloud Infrastructure

Our application runs on cloud infrastructure (such as AWS or similar providers). Data stored at rest is encrypted. Our infrastructure providers act as data processors and do not independently access or use your data.

---

## 6. Data Retention

| Data | Retention period |
|---|---|
| `clientKey` + shared secret | Kept for as long as the app is installed. Deleted automatically within **30 days** of uninstallation. |
| Per-tenant settings | Kept for as long as the app is installed. Deleted automatically within **30 days** of uninstallation. |
| Anonymous usage counts | Retained for up to **12 months** for capacity-planning purposes, then deleted. |

You can also request immediate deletion at any time — see Section 8.

---

## 7. Security

We protect your data using:

- **HTTPS/TLS** for all data in transit
- **Encryption at rest** for stored credentials and settings
- **JWT verification** on every request, as required by the Atlassian Connect security model
- Strict access controls limiting who on our team can access stored data

Despite these measures, no system is 100% secure. If we become aware of a security breach that affects your data, we will notify you as required by applicable law.

---

## 8. Your Rights (GDPR & CCPA)

Depending on where you are located, you may have the following rights:

**Under GDPR (EEA, UK, Switzerland):**
- **Access** — request a copy of the data we hold about your tenant
- **Rectification** — ask us to correct inaccurate settings or data
- **Erasure ("right to be forgotten")** — request deletion of all data associated with your tenant
- **Restriction** — ask us to stop processing your data while a complaint is being resolved
- **Portability** — receive your per-tenant settings in a machine-readable format
- **Objection** — object to certain types of processing

**Under CCPA (California residents):**
- **Know** — ask what personal information we have collected about you
- **Delete** — request deletion of your personal information
- **Opt-out of sale** — we do not sell personal information, so this right is already satisfied
- **Non-discrimination** — we will not penalize you for exercising your rights

To exercise any of these rights, contact us at the address in Section 9. We will respond within **30 days** (or sooner where required by law). We may ask you to verify your identity or your role as an admin for the relevant Jira tenant before fulfilling a request.

---

## 9. Contact & Deletion Requests

For privacy questions, data access requests, or to request deletion of your tenant's data, please contact:

**Steelyman Lab**
📧 [CONTACT_EMAIL]

Please include **"Privacy Request"** in the subject line and provide your Jira site URL so we can locate your tenant record quickly.

---

## 10. Changes to This Policy

If we make material changes to this policy, we will update the effective date at the top of this document and, where appropriate, notify you via the Atlassian Marketplace listing or an in-app notice. Continued use of the app after any changes take effect constitutes acceptance of the updated policy.

---

*This policy applies solely to AutoNotes: AI Release Notes for Jira published by Steelyman Lab. It does not cover Atlassian's own data practices — please refer to [Atlassian's Privacy Policy](https://www.atlassian.com/legal/privacy-policy) for those.*