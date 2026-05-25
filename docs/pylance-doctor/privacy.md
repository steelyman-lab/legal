---
layout: page
title: "Privacy Policy — Pylance Doctor"
permalink: /pylance-doctor/privacy/
---

> ⚠️ **Heads up:** Your prompt included `[CONTACT_EMAIL]` as a placeholder. I've kept it in the document — make sure to replace it with your real support/privacy email before publishing.

---

# Privacy Policy — Pylance Doctor

**Publisher:** Steelyman Lab
**Effective date:** 2026-05-25

---

## 1. Overview

Pylance Doctor is a Visual Studio Code extension that helps you understand and fix Pylance / Pyright diagnostics using AI-powered explanations and suggested edits. This policy explains what data the extension collects, why it collects it, how long we keep it, and what rights you have over it.

We've written this in plain English on purpose. If anything is unclear, please reach out.

---

## 2. What Data We Collect

We collect the minimum amount of data needed to make the extension work well and improve over time. Here is a precise breakdown:

### 2.1 Data sent to process your requests

When you ask for an explanation or a fix, we send the following to our backend API:

| Data item | Description | Example |
|---|---|---|
| **Diagnostic message & rule code** | The error or warning text and its Pylance rule identifier | `"reportMissingImports"` |
| **Code snippet** | Up to 40 lines of source code surrounding the diagnostic | Lines 10–50 of your active file |
| **Import block** | The import statements at the top of the active file, capped at 2 KB | `import os`, `from pathlib import Path`, … |
| **Pyright config** | The contents of `pyrightconfig.json` or the `[tool.pyright]` section of `pyproject.toml`, if present | Your project's type-checking settings |

> **We never collect** your full file, your entire project, credentials, secrets, or any data outside the items listed above.

### 2.2 Data stored locally and/or sent for account purposes

| Data item | Description |
|---|---|
| **Anonymous install ID (UUID)** | A randomly generated identifier created the first time you install the extension. It contains no personally identifiable information. |
| **License key** | If you enter a paid license key, it is sent to our licensing service to verify your subscription. |

### 2.3 Optional anonymous telemetry (opt-in only)

If you explicitly enable telemetry in the extension settings, we collect **event counts only** — no code, no identifiers beyond the install UUID:

- `explain.requested` — you asked for an explanation
- `fix.applied` — you accepted and applied a suggested fix
- `quota.exhausted` — you hit your plan's usage limit
- `license.activated` — a license key was successfully verified

Telemetry is **off by default**. You can toggle it at any time in VS Code settings under `pylanceDoctor.telemetry.enabled`.

---

## 3. Why We Collect This Data

| Data | Purpose | Legal basis (GDPR) |
|---|---|---|
| Diagnostic info, code snippet, import block, Pyright config | Required to generate accurate, context-aware explanations and fix suggestions | Performance of a contract / legitimate interest |
| Anonymous install ID | Ties your session to a usage quota and prevents abuse | Legitimate interest |
| License key | Verifies your entitlement to paid features | Performance of a contract |
| Opt-in event counts | Helps us understand which features are useful and where the extension breaks down | Consent |

We do **not** use your data for advertising, profiling, or sale to third parties.

---

## 4. How Long We Keep Your Data

| Data | Retention period |
|---|---|
| Code snippets and diagnostic data sent to the API | Deleted from our servers within **30 days** of the request |
| License key validation records | Kept for the life of your subscription, then deleted within **90 days** of cancellation |
| Anonymous install ID and opt-in event counts | Retained in aggregate analytics for up to **2 years**, then purged |

We may retain data longer if required by law, but only to the minimum extent required.

---

## 5. Third-Party Services

Pylance Doctor relies on the following third-party services to function. Each has its own privacy policy.

| Service | Purpose | Privacy policy |
|---|---|---|
| **AI inference provider** (e.g., OpenAI or equivalent) | Powers the explanation and fix generation | [openai.com/policies/privacy-policy](https://openai.com/policies/privacy-policy) *(update if different)* |
| **Licensing service** (e.g., Paddle, LemonSqueezy, or equivalent) | Validates license keys and manages subscriptions | *(add your provider's URL)* |
| **Cloud hosting / API infrastructure** (e.g., AWS, Fly.io, or equivalent) | Hosts the backend API that processes requests | *(add your provider's URL)* |

Code snippets and diagnostic data sent to the AI inference provider are processed under a **data processing agreement (DPA)** that prohibits the provider from training on your data or retaining it beyond the request window.

---

## 6. Your Rights

### If you are in the European Economic Area or UK (GDPR)

You have the right to:

- **Access** — ask us what data we hold about you
- **Erasure ("right to be forgotten")** — ask us to delete your data
- **Rectification** — ask us to correct inaccurate data
- **Portability** — receive a copy of your data in a machine-readable format
- **Object** — object to processing based on legitimate interest
- **Withdraw consent** — disable opt-in telemetry at any time in VS Code settings

To exercise any of these rights, email us at **[CONTACT_EMAIL]** with the subject line `Privacy Request`. We will respond within **30 days**.

If you are unsatisfied with our response, you have the right to lodge a complaint with your local data protection authority (e.g., the ICO in the UK, or your national supervisory authority in the EU).

### If you are a California resident (CCPA / CPRA)

You have the right to:

- **Know** what personal information we collect and how it is used
- **Delete** your personal information (subject to certain exceptions)
- **Opt out of sale** — we do **not** sell personal information
- **Non-discrimination** — we will not treat you differently for exercising your rights

To submit a verifiable consumer request, email **[CONTACT_EMAIL]** with the subject line `CCPA Request`. We will respond within **45 days**.

---

## 7. Children's Privacy

Pylance Doctor is a developer tool not directed at children under 13 (or under 16 in the EEA). We do not knowingly collect data from anyone under these ages. If you believe a minor has submitted data, contact us and we will delete it promptly.

---

## 8. Data Security

We use industry-standard measures including TLS encryption in transit and access controls at rest to protect your data. No system is perfectly secure, but we take reasonable precautions and will notify affected users of any breach as required by law.

---

## 9. Changes to This Policy

If we make material changes, we will update the effective date at the top of this document and post a notice in the extension's VS Code Marketplace page. For significant changes, we may also post a notification in the extension itself.

Continued use of Pylance Doctor after a policy update constitutes acceptance of the revised terms.

---

## 10. Contact Us

For privacy questions, data deletion requests, or anything else covered by this policy:

**Steelyman Lab**
📧 [CONTACT_EMAIL]

Please include your anonymous install ID (found in VS Code settings under `Pylance Doctor › About`) if you are requesting data deletion — this is the only way we can locate your records, since we have no names or email addresses on file.

---

*This policy was last updated on 2026-05-25.*