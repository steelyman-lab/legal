---
layout: page
title: "Privacy Policy — EnvPilot — Python Environment Manager"
permalink: /envpilot-—-python-environment-manager/privacy/
---

# Privacy Policy — EnvPilot (Python Environment Manager)

**Publisher:** Steelyman Lab
**Marketplace:** Visual Studio Code Marketplace
**Effective Date:** 2026-05-23

---

## 1. Overview

Steelyman Lab ("we", "us", or "our") built EnvPilot as a Visual Studio Code extension. We take your privacy seriously and have designed EnvPilot to collect as little data as possible. This policy explains exactly what we collect, why, and what your rights are.

---

## 2. What Data We Collect

### 2a. Anonymous Usage Counters *(opt-in only)*

If you explicitly opt in to telemetry, EnvPilot records simple **anonymous event counters** — for example, how many times a command is run. These counters:

- contain **no personally identifiable information (PII)**
- cannot be traced back to you or your machine
- are **not collected at all** unless you have opted in

You can opt in or out at any time via the extension settings (`envpilot.telemetry.enabled`).

### 2b. License Key

If you purchase a license and enter your license key inside VS Code, that key is stored **locally on your own machine** using [VS Code's built-in `SecretStorage` API](https://code.visualstudio.com/api/references/vscode-api#SecretStorage). This is an encrypted, OS-level secret store (e.g., macOS Keychain, Windows Credential Manager, libsecret on Linux).

- The key is **never written to disk in plain text**
- The key is **not synced** to VS Code Settings Sync or any cloud service
- We do not have access to where or how VS Code stores it on your machine

### 2c. Random Instance ID *(license verification only)*

When your license key is verified against our licensing server, a **randomly generated, anonymous instance ID** is sent alongside the key. This ID:

- is created fresh and random — it is **not** your machine ID, username, or any device identifier
- is used solely to prevent a single license key from being used on an unreasonable number of installations simultaneously
- is not linked to any personal information

---

## 3. What We Do NOT Collect

To be explicit, EnvPilot does **not** collect:

- Your name, email address, or any account information
- Your source code, file paths, or project contents
- Your IP address (our licensing server may log it transiently in standard server logs; see Section 5)
- VS Code usage data beyond EnvPilot's own opt-in counters
- Any data from users who have not opted in to telemetry

---

## 4. Why We Collect This Data

| Data | Purpose |
|---|---|
| Anonymous event counters | Understand which features are useful so we can improve the extension |
| License key | Authenticate your paid license locally |
| Random instance ID | Prevent abuse of a single license key across unlimited machines |

We do not sell, rent, or share your data for advertising or marketing purposes.

---

## 5. Third-Party Services

### Licensing Server

License key verification is handled by Steelyman Lab's own licensing infrastructure. During verification, your license key and random instance ID are transmitted over HTTPS. Standard web server logs on our hosting provider may retain IP addresses for up to **30 days** for security and abuse-prevention purposes, after which they are automatically deleted.

### Telemetry (opt-in only)

If you opt in to telemetry, anonymous event counters are sent to a telemetry service operated by or on behalf of Steelyman Lab. No PII is included in these payloads.

We do not use Google Analytics, Facebook Pixel, or any advertising-network trackers.

---

## 6. How Long We Keep Data

| Data | Retention Period |
|---|---|
| Anonymous event counters | Aggregated indefinitely; raw events deleted after **90 days** |
| License key | Stored locally on your machine; deleted when you remove the extension or clear it manually |
| Random instance ID | Retained on our licensing server for the life of the license; can be reset on request |
| Server access logs (IP addresses) | **30 days**, then automatically purged |

---

## 7. Your Rights (GDPR & CCPA)

Depending on where you live, you may have the following rights:

- **Access** — ask us what data we hold about you
- **Deletion** — ask us to delete any data associated with your license key or instance ID
- **Correction** — ask us to correct inaccurate data
- **Portability** — ask for a copy of your data in a machine-readable format
- **Opt out** — disable telemetry at any time in the extension settings; this takes effect immediately
- **Non-discrimination** — we will never treat you differently for exercising any of these rights

Because we collect minimal data and nothing that directly identifies you by default, most requests will be straightforward to fulfill. To make a request, please contact us using the details in Section 8.

**California residents (CCPA):** We do not sell personal information. The data described in this policy is used solely for operating and improving EnvPilot.

**EU/EEA residents (GDPR):** Our legal basis for processing is **legitimate interest** (license verification, fraud prevention) and **consent** (opt-in telemetry). You may withdraw consent for telemetry at any time without affecting your use of the extension.

---

## 8. Contact & Deletion Requests

For privacy questions, data access requests, or deletion requests, please contact:

**Steelyman Lab**
📧 [CONTACT_EMAIL]

We aim to respond to all privacy requests within **30 days**.

---

## 9. Changes to This Policy

If we make material changes to this policy, we will update the **Effective Date** at the top and post the updated policy in the extension's repository and Marketplace listing. Continued use of EnvPilot after changes are posted constitutes acceptance of the revised policy.

---

*This policy applies solely to data collected by the EnvPilot VS Code extension. It does not cover the Visual Studio Code application itself or the VS Code Marketplace, which have their own privacy policies maintained by Microsoft.*