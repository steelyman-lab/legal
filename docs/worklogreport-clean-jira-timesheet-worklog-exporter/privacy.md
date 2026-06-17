---
layout: page
title: "Privacy Policy — WorklogReport – Clean Jira Timesheet & Worklog Exporter"
permalink: /worklogreport-clean-jira-timesheet-worklog-exporter/privacy/
---

```markdown
# Privacy Policy

**App:** WorklogReport – Clean Jira Timesheet & Worklog Exporter
**Publisher:** Steelyman Lab
**Marketplace:** Atlassian Marketplace (Atlassian Forge)
**Effective Date:** 17 June 2026

---

## 1. Introduction

This Privacy Policy explains what data WorklogReport – Clean Jira Timesheet & Worklog Exporter ("the App", "we", "us") collects, why we collect it, and how we handle it. We've written this in plain English so you don't need a law degree to understand it.

If you use the App, you agree to the practices described here.

---

## 2. Who We Are

The App is published by **Steelyman Lab**. If you have any privacy-related questions or requests, you can reach us at **[CONTACT_EMAIL]**.

---

## 3. What Data We Access

The App reads the following data from your Jira instance — and **only** the data needed to generate timesheets and worklog reports:

| Data Type | What It Is | Why We Need It |
|---|---|---|
| **Jira worklog entries** | Time entries logged against Jira issues (author, time spent, date, optional comment) | To build timesheet and worklog reports |
| **Jira user display names & account IDs** | The name shown in Jira and the internal account identifier | To group and label worklog entries by team member |
| **Jira project metadata** | Project name, key, and identifier | To filter and organise reports by project |

All access is **read-only**. The App never creates, modifies, or deletes any data in your Jira instance.

---

## 4. How We Process Your Data

The App is built on **Atlassian Forge**, Atlassian's secure, sandboxed cloud runtime. This means:

- **All data processing happens inside Atlassian's infrastructure.** Your Jira data is fetched and processed within the Forge sandbox — it never leaves Atlassian's platform or travels to any server owned or operated by Steelyman Lab.
- **We do not store, copy, or transmit your data externally.** We do not maintain our own database of your Jira information.
- **No data is sent to third-party analytics, tracking, or advertising services.**

In short: your data goes from Jira → Forge sandbox → your report. It doesn't go anywhere else.

---

## 5. How Long Data Is Kept

Because the App processes data in real time inside the Forge sandbox, **we do not retain your data**. Each time you generate a report, the App fetches the relevant data, produces the output, and discards it. Nothing is stored beyond what Atlassian's Forge platform itself temporarily holds to execute the request.

Atlassian's own data retention practices apply to any logs or telemetry held within the Forge infrastructure. You can review Atlassian's privacy policy at [https://www.atlassian.com/legal/privacy-policy](https://www.atlassian.com/legal/privacy-policy).

---

## 6. Third-Party Services

| Service | Purpose | Data Shared |
|---|---|---|
| **Atlassian Forge** | Runtime and infrastructure for the App | Jira data is processed within this platform per Atlassian's privacy policy |

We do not use any other third-party services, SDKs, tracking pixels, or analytics tools.

---

## 7. Cookies and Tracking

The App does not set cookies, use browser fingerprinting, or engage in any form of behavioural tracking.

---

## 8. Your Rights

Depending on where you're located, you may have legal rights over your personal data. Below is a summary of the main rights that apply.

### Under GDPR (European Economic Area & UK)

If you are located in the EEA or the UK, you have the right to:

- **Access** — request a copy of any personal data we hold about you.
- **Rectification** — ask us to correct inaccurate data.
- **Erasure ("right to be forgotten")** — ask us to delete your personal data.
- **Restriction** — ask us to limit how we process your data.
- **Portability** — receive your data in a structured, commonly used format.
- **Object** — object to processing based on our legitimate interests.
- **Lodge a complaint** — with your local data protection authority (e.g. your national DPA, or the ICO in the UK).

Because the App does not retain personal data on our own systems, most of these rights are most effectively exercised directly through your Atlassian/Jira account settings or by contacting your Jira administrator. However, you are always welcome to contact us and we will assist wherever we can.

### Under CCPA (California, USA)

If you are a California resident, you have the right to:

- **Know** what personal information is collected and how it is used.
- **Delete** personal information we hold about you.
- **Opt out of the sale** of your personal information — we do **not** sell personal information.
- **Non-discrimination** — we will never treat you differently for exercising your privacy rights.

### How to Submit a Request

Send an email to **[CONTACT_EMAIL]** with the subject line **"Privacy Request"**. Please include:

1. Your full name and Jira account email address.
2. The nature of your request (access, deletion, etc.).
3. The name of your Jira site/organisation (if applicable).

We will respond within **30 days** (or sooner where required by law).

---

## 9. Children's Privacy

The App is designed for use in professional and business environments and is **not directed at children under the age of 16**. We do not knowingly collect personal data from children. If you believe a child's data has been collected, please contact us immediately.

---

## 10. Security

We rely on Atlassian Forge's built-in security controls, which include encryption in transit (TLS), sandboxed execution, and access controls enforced by Atlassian. Because we do not operate our own servers or databases for this App, there is no separate Steelyman Lab data store that could be compromised.

---

## 11. Changes to This Policy

If we make material changes to this policy, we will update the **Effective Date** at the top and, where possible, notify users through the Atlassian Marketplace listing. We encourage you to review this policy periodically.

---

## 12. Contact Us

For any privacy questions, concerns, or data requests, please contact:

**Steelyman Lab**
📧 [CONTACT_EMAIL]

We're happy to help and will always respond in plain English.

---

*This policy was last updated on 17 June 2026.*
```

---

**A few things to note before you publish:**

- **Replace `[CONTACT_EMAIL]`** with your actual support or privacy contact address.
- **GDPR lawful basis:** If you ever move to a paid/enterprise model and start processing EU user data more actively, you may want to explicitly state your lawful basis (likely *legitimate interests* or *contract performance*). For now, since no data leaves Forge, the current framing is appropriate.
- **Atlassian requirement:** Atlassian Marketplace requires a publicly hosted URL for your privacy policy. Host this as a plain web page (e.g. via GitHub Pages or your own domain) and paste the link into your app listing.