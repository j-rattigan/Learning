# 📘 Module 3: Enroll Devices

> Source: [Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/manage-devices-with-microsoft-endpoint-manager/3-enroll-devices)

---

## 🔹 What is Device Enrollment?

- 🔑 **Key:** Enrollment is the process of registering a device with Microsoft Endpoint Manager so it can be managed.
- ❗ **Important:** Required for applying policies, pushing apps, and securing devices.
- 🧩 **Supporting Details:**
  - Devices can be user-driven or automatically enrolled.
  - Enrollment method depends on OS and ownership (personal vs corporate).
- 📌 **Example:** A personal iPhone enrolls via Company Portal to get secure email.
- 💬 **Scenario:** An organization mandates Intune enrollment for all corporate laptops and phones.

---

## 🔹 Windows Enrollment Options

- 🔑 **Key:** Windows devices can be enrolled through Autopilot, manual setup, or GPO.
- ❗ **Important:** User and device-based enrollment paths offer flexibility.
- 🧩 **Supporting Details:**
  - Azure AD Join with automatic MDM enrollment.
  - Manual enrollment for devices not in Azure AD.
- 📌 **Example:** An employee sets up a new laptop that automatically registers to Intune.
- 💬 **Scenario:** A small business uses Group Policy to enroll existing domain-joined PCs.

---

## 🔹 Apple Enrollment Options

- 🔑 **Key:** Apple devices use Automated Device Enrollment (ADE) or user-based enrollment.
- ❗ **Important:** ADE ensures supervision and streamlined setup for corporate iOS/macOS devices.
- 🧩 **Supporting Details:**
  - Requires Apple Business/School Manager integration.
  - iOS devices can also enroll via Company Portal.
- 📌 **Example:** ADE configures iPads for secure use in retail stores.
- 💬 **Scenario:** Teachers receive managed MacBooks set up via Apple School Manager and Intune.

---

## 🔹 Android Enrollment Options

- 🔑 **Key:** Android Enterprise supports multiple enrollment types tailored to business needs.
- ❗ **Important:** Differentiates between BYOD (work profile) and corporate-owned (fully managed).
- 🧩 **Supporting Details:**
  - Enrollment via QR code, Zero-touch, or NFC.
  - Dedicated device mode for kiosks.
- 📌 **Example:** Company-owned tablets are set up in kiosk mode for public use.
- 💬 **Scenario:** A logistics company provisions Android scanners using Zero-touch enrollment.

---
