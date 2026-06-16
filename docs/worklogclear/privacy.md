---
layout: page
title: "Privacy Policy — WorklogClear"
permalink: /worklogclear/privacy/
---

```markdown
# Privacy Policy — WorklogClear

**Publisher:** Steelyman Lab  
**Marketplace:** Atlassian Marketplace  
**Effective Date:** June 16, 2026  
**Contact:** [CONTACT_EMAIL]

---

## 1. Overview

WorklogClear is an Atlassian Forge app that helps teams view, filter, and report on Jira worklog data. This Privacy Policy explains what data we collect, why we collect it, how long we keep it, and what rights you have over your information.

We've written this in plain English on purpose. If anything is unclear, please reach out — we're happy to explain.

---

## 2. What Data We Collect

WorklogClear accesses and processes the following data from your Jira site:

### 2.1 Worklog Data
- **Time spent** on a Jira issue
- **Started date** of the worklog entry
- **Author display name** and **Atlassian account ID** of the person who logged the work

### 2.2 Jira Issue Metadata
- Issue **key** (e.g., `PROJ-123`)
- Issue **summary** (title)
- **Project** name and key
- **Status** (e.g., In Progress, Done)
- **Issue type** (e.g., Bug, Story, Task)
- **Labels** attached to the issue
- **Sprint** name and ID

### 2.3 User-Saved Report Definitions
- Report configurations you save within the app (filters, date ranges, groupings, display preferences), stored in **Atlassian Forge Storage** on your Jira site's infrastructure.

### 2.4 Anonymous Usage Counters
- Aggregate query counts used to power the admin dashboard (e.g., "reports generated this week").
- These counters contain **no personally identifiable information (PII)** and cannot be linked back to any individual user.

---

## 3. Why We Collect This Data

| Data | Purpose |
|---|---|
| Worklog entries | Display time-tracking information in reports and views within the app |
| Issue metadata | Provide context for each worklog entry (project, status, sprint, etc.) |
| Saved report definitions | Remember your report preferences between sessions |
| Anonymous query counters | Help the site administrator understand app usage and performance |

We do **not** use your data for advertising, profiling, or any purpose beyond making the app work as described.

---

## 4. How We Store and Process Data

WorklogClear is built entirely on the **Atlassian Forge platform**. This means:

- All data processing happens **within Atlassian's infrastructure**, on your own Jira site.
- Saved report definitions are stored in **Forge Storage**, which is scoped to your Jira site and managed by Atlassian.
- **Steelyman Lab does not operate any external servers** and does not transfer your Jira data outside of the Atlassian platform.

For details on how Atlassian secures Forge app data, see [Atlassian's Privacy Policy](https://www.atlassian.com/legal/privacy-policy).

---

## 5. Third-Party Services

WorklogClear does **not** share your data with any third-party services, analytics providers, or advertising networks.

The only external dependency is the **Atlassian Forge platform** itself, which provides the runtime, storage, and API access that the app requires. Atlassian's handling of that data is governed by Atlassian's own privacy policy and data processing agreements.

---

## 6. Data Retention

| Data | Retention Period |
|---|---|
| Worklog and issue data | Fetched live from the Jira API on demand; **not stored persistently** by WorklogClear |
| Saved report definitions | Kept in Forge Storage until you delete them within the app, or until the app is uninstalled from your Jira site |
| Anonymous usage counters | Reset periodically (no retention of historical aggregates beyond the current rolling window) |

When the app is **uninstalled** from your Jira site, all data in Forge Storage (including saved report definitions and usage counters) is permanently deleted in accordance with Atlassian's Forge data lifecycle policies.

---

## 7. Your Privacy Rights

Depending on where you are located, you may have the following rights regarding your personal data:

### GDPR (European Economic Area, UK, Switzerland)
- **Right to access** — request a copy of the personal data we hold about you.
- **Right to rectification** — ask us to correct inaccurate data.
- **Right to erasure ("right to be forgotten")** — request deletion of your personal data.
- **Right to restriction** — ask us to limit how we process your data.
- **Right to data portability** — receive your data in a structured, machine-readable format.
- **Right to object** — object to processing where we rely on legitimate interests.

### CCPA (California Residents)
- **Right to know** — request disclosure of the categories and specific pieces of personal information we have collected.
- **Right to delete** — request deletion of personal information we hold about you.
- **Right to opt out of sale** — we do **not** sell personal information, so this right is not applicable.
- **Right to non-discrimination** — we will never penalize you for exercising your privacy rights.

### How to Exercise Your Rights

To submit a data access, correction, or deletion request, contact us at:

**[CONTACT_EMAIL]**

Please include your **Atlassian account ID or display name** and the **name of your Jira site** so we can locate and process your request promptly. We will respond within **30 days** (or sooner where required by applicable law).

Because most personal data is held within your Jira site's Forge Storage and processed live from the Jira API, many requests can be fulfilled by the **Jira site administrator** directly (e.g., revoking app access, uninstalling the app, or deleting saved reports from within the app).

---

## 8. Children's Privacy

WorklogClear is a business productivity tool intended for workplace use. We do not knowingly collect personal data from anyone under the age of 16. If you believe a minor's data has been collected, please contact us at **[CONTACT_EMAIL]** so we can take appropriate action.

---

## 9. Changes to This Policy

If we make material changes to this Privacy Policy, we will update the **Effective Date** at the top of this document and publish the updated version to our Atlassian Marketplace listing. We encourage you to review this policy periodically.

---

## 10. Contact Us

For any privacy-related questions, concerns, or requests:

**Steelyman Lab**  
Email: **[CONTACT_EMAIL]**

We aim to respond to all inquiries within **5 business days**.

---

*This Privacy Policy applies solely to the WorklogClear app published by Steelyman Lab on the Atlassian Marketplace. It does not apply to Atlassian's own products or services.*
```

---

> ⚠️ **One thing to do before publishing:** Replace `[CONTACT_EMAIL]` with your actual support/privacy contact email address throughout the document. Everything else is ready to go.

A few notes on the policy decisions made:

- **No external servers** — Since Forge apps are sandboxed within Atlassian's infrastructure, I've made clear that Steelyman Lab itself doesn't operate servers or receive data, which is both accurate and a strong trust signal for buyers.
- **Live-fetch framing** — Worklog and issue data is described as fetched on demand (not stored), which keeps your retention obligations minimal.
- **GDPR + CCPA** — Both are covered since Atlassian has a global user base and marketplace listings reach both jurisdictions.
- **Uninstall = deletion** — This is a natural and honest data lifecycle boundary for Forge apps and satisfies the erasure expectation without requiring a manual process.