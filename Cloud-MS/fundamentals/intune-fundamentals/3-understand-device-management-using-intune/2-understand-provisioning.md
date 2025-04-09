# 📘 Module 2: Understand Provisioning

> Source: [Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/manage-devices-with-microsoft-endpoint-manager/2-understand-provisioning)

---

## 🔹 What is Provisioning?

- 🔑 **Key:** Provisioning sets up devices with apps, policies, and settings before users start using them.
- ❗ **Important:** It supports secure, standardized deployments at scale—ideal for remote or hybrid workforces.
- 🧩 **Supporting Details:**
  - Can be automated using Windows Autopilot, Apple ADE, or Android enrollment programs.
  - Reduces IT workload and speeds up setup time.
- 📌 **Example:** A user receives a laptop that auto-configures itself with apps and settings on first login.
- 💬 **Scenario:** IT provisions 200 devices remotely to ship to new employees with zero-touch setup.

---

## 🔹 Modern Provisioning Benefits

- 🔑 **Key:** Modern provisioning offers flexibility across platforms while maintaining compliance and consistency.
- ❗ **Important:** Improves end-user experience and enhances security posture from day one.
- 🧩 **Supporting Details:**
  - Supports remote and hybrid device readiness.
  - Eliminates the need for imaging.
  - Integrates with Azure AD and Intune.
- 📌 **Example:** Devices join Microsoft Entra ID and get policies via Intune automatically.
- 💬 **Scenario:** A company uses Autopilot to replace manual setup for hundreds of laptops across regions.

---

## 🔹 Windows Provisioning Options

- 🔑 **Key:** Windows Autopilot supports multiple deployment modes.
- ❗ **Important:** Each mode fits different use cases—like shared devices, pre-deployment, or self-setup.
- 🧩 **Deployment Modes:**
  - **Self-Deploying Mode**
  - **White Glove (Pre-provisioning)**
  - **User-Driven Mode**
  - **Autopilot for Existing Devices**
- 📌 **Example:** IT pre-provisions devices with White Glove for shipping to employees.
- 💬 **Scenario:** A school sets up student laptops using user-driven Autopilot deployment.

---

## 🔹 Apple Device Provisioning

- 🔑 **Key:** Apple Automated Device Enrollment simplifies setup for iOS/iPadOS/macOS.
- ❗ **Important:** Devices are supervised and locked to the organization.
- 🧩 **Supporting Details:**
  - Zero-touch setup via Apple Business/School Manager.
  - Enforces corporate restrictions and configurations.
- 📌 **Example:** Students receive iPads pre-loaded with education apps and restrictions.
- 💬 **Scenario:** A healthcare provider configures iPads with limited access for field staff.

---

## 🔹 Android Device Provisioning

- 🔑 **Key:** Android supports corporate provisioning via Zero-touch and QR code.
- ❗ **Important:** Different enrollment types support BYOD and corporate-owned scenarios.
- 🧩 **Supporting Details:**
  - Android Enterprise supports fully managed, work profile, and dedicated modes.
- 📌 **Example:** Field tablets run only a company app in kiosk mode.
- 💬 **Scenario:** A delivery service provisions rugged Android devices with tracking software.

---
