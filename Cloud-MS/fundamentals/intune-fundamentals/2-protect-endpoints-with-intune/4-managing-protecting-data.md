# 📘 Module 4: Managing and Protecting Data

> Source: [Module Link](https://learn.microsoft.com/en-us/training/modules/protect-endpoints-with-endpoint-manager/4-managing-protecting-data)

---

### 🔹 Data Loss Prevention (DLP)

- 🔑 **Key:** DLP policies prevent sensitive data from being leaked or mishandled.
- ❗ **Important:** You can control how users interact with corporate data in apps.
- 🧩 **Supporting Details:**
  - Restrict copy/paste, saving, or sharing data externally.
  - Can work across M365 apps like Outlook, Word, Excel.
- 📌 **Example:** Users can’t paste sensitive info from Outlook into WhatsApp.
- 💬 **Scenario:** A finance team member tries to forward a payroll spreadsheet — Intune blocks external sharing based on DLP rules.

---

### 🔹 Conditional Access

- 🔑 **Key:** Conditional Access restricts access to company data based on device, user, location, etc.
- ❗ **Important:** Works with Microsoft Entra ID to enforce real-time access decisions.
- 🧩 **Supporting Details:**
  - Blocks access from jailbroken/rooted devices or unknown IPs.
  - Requires device to be compliant before allowing access.
- 📌 **Example:** Access to SharePoint is allowed only from corporate devices within the corporate network.
- 💬 **Scenario:** A user logs in from a new country — Conditional Access requires MFA and a compliant device.

---
