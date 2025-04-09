# 📘 Module 7: Monitor and Troubleshoot with Endpoint Manager

> Source: [Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/intro-to-endpoint-manager/7-monitor-and-troubleshoot)

## 🧩 Microlearning Chunks with Key Details

---

### 🔹 Chunk 1: Monitoring Devices and Policies

- 🔑 **Key:** Endpoint Manager provides dashboards to track device health, compliance, and policy status.
- ❗ **Important:** Real-time visibility helps admins catch issues quickly.
- 🧩 **Supporting Details:**
  - Overview pages show enrollment, compliance, and app status
  - Devices pane shows status per device or user
- 📌 **Example:** IT sees a spike in non-compliant devices after a new password policy is deployed.
- 💬 **Scenario:** An admin notices some devices haven’t checked in — they investigate and find a network firewall blocking Intune.

---

### 🔹 Chunk 2: Reports and Analytics

- 🔑 **Key:** Intune generates reports to help with decision-making and compliance tracking.
- ❗ **Important:** Reports can show deployment success, app installs, and update progress.
- 🧩 **Supporting Details:**
  - Endpoint analytics: measures startup times, crash rates, and user experience
  - Audit logs: track changes in configuration or user actions
- 📌 **Example:** A slow-booting device trend leads IT to phase out older hardware.
- 💬 **Scenario:** Reports show Teams crashes often on specific devices — IT pushes an app update.

---

### 🔹 Chunk 3: Troubleshooting Tools

- 🔑 **Key:** Endpoint Manager includes built-in tools to troubleshoot problems remotely.
- ❗ **Important:** You can diagnose from the cloud without needing physical access to devices.
- 🧩 **Supporting Details:**
  - Remote actions: wipe, restart, sync, retire devices
  - Error codes and logs are surfaced in the portal
- 📌 **Example:** An admin resets a device passcode remotely after a user is locked out.
- 💬 **Scenario:** A user can't access apps — the admin sees a failed policy in the portal, fixes the config, and forces a sync.

---
