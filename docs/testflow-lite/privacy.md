---
layout: page
title: "Privacy Policy — TestFlow Lite"
permalink: /testflow-lite/privacy/
---

```markdown
# Privacy Policy — TestFlow Lite

**Publisher:** Steelyman Lab
**Marketplace:** Atlassian Marketplace
**Effective Date:** June 14, 2026

---

## 1. Overview

TestFlow Lite is a Jira app built by Steelyman Lab that helps teams manage test cases and track test execution results. We take your privacy seriously. This policy explains, in plain English, what data we collect, why we collect it, how long we keep it, and what rights you have over it.

---

## 2. What Data We Collect

We collect only the minimum data necessary to make the app work.

| Data Type | Description |
|-----------|-------------|
| **Atlassian Account IDs** | The unique identifier Atlassian assigns to each user. We use this to associate test execution results with the person who ran them. We do **not** collect names, email addresses, or profile pictures directly. |
| **Test Case Content** | Text and structured data you write inside Jira issues when creating test cases (e.g., test steps, expected results, descriptions). |
| **Test Execution Results** | Pass/fail outcomes, execution timestamps, and any notes recorded when a test is run. These are stored using the Atlassian Forge Storage API. |

We do **not** collect passwords, payment information, or any data from Jira issues that are unrelated to test cases managed by TestFlow Lite.

---

## 3. Why We Collect This Data

Each piece of data has a specific, functional purpose:

- **Atlassian Account IDs** — To track who executed a test run and display accurate activity history within the app.
- **Test Case Content** — To display, organize, and manage your test cases inside Jira. This data lives within your Jira instance and is accessed by the app only to render and operate its features.
- **Test Execution Results** — To record the outcome of test runs, show historical trends, and generate reports for your team.

We do **not** use your data for advertising, profiling, or any purpose beyond operating TestFlow Lite.

---

## 4. How Long We Keep Your Data

| Data Type | Retention Period |
|-----------|-----------------|
| Atlassian Account IDs | Retained for as long as your workspace has TestFlow Lite installed. Deleted within **30 days** of app uninstallation. |
| Test Case Content | Stored in Jira issues and subject to your own Jira data retention settings. We do not maintain a separate copy. |
| Test Execution Results | Retained in Forge Storage for as long as the app is installed on your site. Deleted within **30 days** of app uninstallation. |

If you request early deletion (see Section 7), we will delete your data within **14 days** of receiving the request.

---

## 5. Where Your Data Is Stored

TestFlow Lite is built on the **Atlassian Forge** platform. Data stored by the app (specifically test execution results) is kept in **Atlassian Forge Storage**, which is infrastructure operated and secured by Atlassian, Inc.

- Forge Storage is hosted on Atlassian's infrastructure and is subject to [Atlassian's own privacy and security policies](https://www.atlassian.com/legal/privacy-policy).
- Test case content remains inside your Jira instance and is never exported to servers outside of Atlassian's platform by this app.

Steelyman Lab does **not** operate independent servers that store your data.

---

## 6. Third-Party Services

| Service | Purpose | Link |
|---------|---------|------|
| **Atlassian Forge** | App hosting, runtime, and secure storage | [atlassian.com/legal](https://www.atlassian.com/legal/privacy-policy) |
| **Atlassian Jira** | Issue data access via official Jira APIs | [atlassian.com/legal](https://www.atlassian.com/legal/privacy-policy) |

We do not share your data with any other third parties. We do not sell your data — ever.

---

## 7. Your Rights

Depending on where you live, you may have the following rights over your personal data.

### GDPR (European Union / UK)

If you are in the EU or UK, you have the right to:

- **Access** — Request a copy of the data we hold about you.
- **Rectification** — Ask us to correct inaccurate data.
- **Erasure ("Right to be Forgotten")** — Ask us to delete your data.
- **Restriction** — Ask us to stop processing your data in certain ways.
- **Data Portability** — Request your data in a machine-readable format.
- **Object** — Object to our processing of your data.

You also have the right to lodge a complaint with your local data protection authority (e.g., the ICO in the UK, or your country's supervisory authority in the EU).

### CCPA (California, USA)

If you are a California resident, you have the right to:

- **Know** what personal information we collect and how it is used.
- **Delete** your personal information.
- **Opt-Out of Sale** — We do not sell personal information, so this right is already satisfied.
- **Non-Discrimination** — We will not treat you differently for exercising your privacy rights.

### How to Exercise Your Rights

Send an email to **[CONTACT_EMAIL]** with the subject line `"Privacy Request — TestFlow Lite"`. Please include:

1. Your Atlassian Account ID or the Atlassian site URL where the app is installed.
2. A description of your request (e.g., access, deletion, export).

We will respond within **14 days**.

---

## 8. Security

Because TestFlow Lite runs entirely within the Atlassian Forge sandbox, your data benefits from Atlassian's enterprise-grade security controls, including encryption at rest and in transit. Steelyman Lab follows Atlassian's security guidelines for all app development and does not store credentials or tokens outside the Forge platform.

---

## 9. Children's Privacy

TestFlow Lite is a professional tool intended for use in workplace environments. We do not knowingly collect data from anyone under the age of 16. If you believe a minor's data has been collected, please contact us at the address below so we can delete it promptly.

---

## 10. Changes to This Policy

If we make material changes to this policy, we will update the **Effective Date** above and post a notice in the Atlassian Marketplace listing. We encourage you to review this policy periodically. Continued use of the app after changes are posted means you accept the updated policy.

---

## 11. Contact Us

For any privacy questions, requests, or concerns:

**Steelyman Lab**
Email: **[CONTACT_EMAIL]**

We aim to respond to all privacy-related inquiries within **14 business days**.

---

*This privacy policy applies solely to the TestFlow Lite app published by Steelyman Lab on the Atlassian Marketplace. It does not govern Atlassian's own products or services.*
```

---

**A few things to note before publishing:**

1. **`[CONTACT_EMAIL]`** — Replace this placeholder with your actual support/privacy email address throughout the document (there are three instances).
2. **Data Processor vs. Controller** — If you plan to sell into EU enterprise accounts, you may want to add a brief note clarifying that Steelyman Lab acts as a **data processor** and the Jira workspace owner is the **data controller**. Happy to add that section if needed.
3. **Legal review** — This document is written to be accurate and clear, but for full GDPR compliance (especially if you process EU personal data at scale), having a qualified privacy attorney review it is recommended.