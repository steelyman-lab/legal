---
layout: page
title: "Privacy Policy — WorklogIQ — Lightweight Jira Timesheet Reporter"
permalink: /worklogiq-lightweight-jira-timesheet-reporter/privacy/
---

# Privacy Policy — WorklogIQ: Lightweight Jira Timesheet Reporter

**Publisher:** Steelyman Lab
**Effective Date:** 18 June 2026
**Marketplace:** Atlassian Marketplace (Forge platform)

---

## 1. Overview

WorklogIQ is a Jira app built on the **Atlassian Forge platform**. We take your privacy seriously and have designed this app to handle as little data as necessary to do its job.

This policy explains what data we collect, why we collect it, how long we keep it, and what rights you have over it.

---

## 2. What Data We Collect

We collect only two categories of data:

### 2.1 Jira Worklog Data (within your Atlassian instance)

When you use WorklogIQ to generate timesheet reports, the app reads **worklog entries already stored in your own Jira instance**. This includes:

- Worklog author (Atlassian account display name and account ID)
- Time logged and date of the log entry
- Issue key and summary associated with the worklog
- Any comment attached to the worklog entry

> **Important:** This data never leaves your Atlassian environment. WorklogIQ reads it in real time via the Forge runtime and Jira APIs. We do not copy it to any external server or database we own.

### 2.2 User-Saved Report Configurations (Forge Storage)

When you save a report configuration (e.g., a custom date range, project filter, or grouping preference), that configuration is stored using **Atlassian Forge Storage** — a key-value store provided and hosted by Atlassian, scoped exclusively to your Atlassian site.

This data includes:

- Report name and filter settings you choose to save
- Your Atlassian account ID (used to associate the configuration with you)

---

## 3. Why We Collect This Data

| Data | Purpose |
|---|---|
| Jira worklog data | To generate timesheet and worklog reports on demand |
| Saved report configurations | To let you reuse and manage your preferred report settings |

We do not use your data for advertising, profiling, analytics beyond the app's core function, or any other secondary purpose.

---

## 4. How Long We Keep Your Data

| Data | Retention |
|---|---|
| Jira worklog data | Not retained — read in real time and discarded after report generation |
| Saved report configurations | Kept in Forge Storage until you delete them within the app, or until you uninstall WorklogIQ from your Atlassian site |

When you uninstall WorklogIQ, Atlassian automatically purges all data stored in Forge Storage associated with your site.

---

## 5. Third-Party Services

WorklogIQ is built entirely on the **Atlassian Forge platform**. There is no external backend, no third-party analytics, no advertising SDKs, and no external databases.

The only infrastructure involved is:

- **Atlassian Forge Runtime** — executes the app's logic in a sandboxed environment managed by Atlassian
- **Atlassian Forge Storage** — stores saved configurations, governed by [Atlassian's own privacy policy](https://www.atlassian.com/legal/privacy-policy)

We do not sell, share, or transfer your data to any third party.

---

## 6. Data Location

Because WorklogIQ runs entirely on the Atlassian Forge platform, data residency is determined by **Atlassian's infrastructure**, not by Steelyman Lab. Please refer to [Atlassian's data residency documentation](https://www.atlassian.com/trust/data-residency) for details about where your data is stored geographically.

---

## 7. Your Rights (GDPR & CCPA)

Depending on where you are located, you may have the following rights:

### Under GDPR (EEA, UK, and Switzerland)

- **Right of access** — request a copy of personal data we hold about you
- **Right to rectification** — ask us to correct inaccurate data
- **Right to erasure** — ask us to delete your personal data
- **Right to restriction** — ask us to limit how we process your data
- **Right to data portability** — receive your data in a portable format
- **Right to object** — object to certain types of processing
- **Right to lodge a complaint** — with your local data protection authority

### Under CCPA (California residents)

- **Right to know** — what personal information we collect and how it is used
- **Right to delete** — request deletion of your personal information
- **Right to opt out of sale** — we do not sell personal information, so this right is not applicable
- **Right to non-discrimination** — exercising your rights will not affect your access to the app

### How to Exercise Your Rights

Because almost all data lives within your own Atlassian instance, you or your Jira administrator can manage most data directly. For saved report configurations, you can delete them from within the app at any time.

For any other requests — including deletion requests, access requests, or questions — contact us at:

📧 **[CONTACT_EMAIL]**

We will respond within **30 days** of receiving your request.

---

## 8. Security

WorklogIQ does not store credentials or tokens. All API access is handled automatically and securely by the Atlassian Forge platform using OAuth 2.0 scopes that you approve at installation time. We request only the minimum permissions needed to read worklog data.

---

## 9. Children's Privacy

WorklogIQ is a business productivity tool. It is not directed at children under the age of 16, and we do not knowingly collect personal data from children.

---

## 10. Changes to This Policy

If we make material changes to this privacy policy, we will update the effective date at the top of this document and, where appropriate, notify users via the Atlassian Marketplace listing. Continued use of the app after any changes constitutes acceptance of the updated policy.

---

## 11. Contact

**Steelyman Lab**
📧 [CONTACT_EMAIL]

If you have any questions about this policy or about how WorklogIQ handles your data, please don't hesitate to get in touch.

---

*This privacy policy applies solely to WorklogIQ: Lightweight Jira Timesheet Reporter, published by Steelyman Lab on the Atlassian Marketplace.*