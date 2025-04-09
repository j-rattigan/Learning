# 📘 Module 1: Introduction

> Source: [Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/manage-devices-with-microsoft-endpoint-manager/1-introduction)

---

## 🔹 Device Management Lifecycle

- 🔑 **Key:** Managing devices involves a comprehensive lifecycle, from provisioning to retirement.&#8203;:contentReference[oaicite:0]{index=0}
- ❗ **Important:** :contentReference[oaicite:1]{index=1}&#8203;:contentReference[oaicite:2]{index=2}
- 🧩 **Supporting Details:**
  - :contentReference[oaicite:3]{index=3}&#8203;:contentReference[oaicite:4]{index=4}
    1. **Provisioning:** Setting up devices with necessary configurations and policies.
    2. **Enrollment:** Registering devices into a management system like Microsoft Intune.
    3. **Configuration:** Applying settings and policies to meet organizational standards.
    4. **Protection:** Implementing security measures to safeguard data and access.
    5. **Retirement:** Decommissioning devices securely when they're no longer needed.
- 📌 **Example:** :contentReference[oaicite:5]{index=5}&#8203;:contentReference[oaicite:6]{index=6}
- 💬 **Scenario:** An organization automates device provisioning, ensuring all new devices are enrolled and compliant before deployment.&#8203;:contentReference[oaicite:7]{index=7}

---

## 🔹 Enrollment Methods in Microsoft Intune

- 🔑 **Key:** Microsoft Intune offers various enrollment methods tailored to different device ownership scenarios.&#8203;:contentReference[oaicite:8]{index=8}
- ❗ **Important:** Choosing the appropriate enrollment method is crucial for effective management and security.&#8203;:contentReference[oaicite:9]{index=9}
- 🧩 **Supporting Details:**
  - **Windows Devices:**
    - **Windows Autopilot:** Streamlines the setup and deployment of new devices.
    - **Manual Enrollment:** Users or IT staff manually enroll devices through settings.
  - **iOS/iPadOS Devices:**
    - **Apple Automated Device Enrollment (ADE):** Automates enrollment for devices purchased through Apple Business Manager.
    - **User-initiated Enrollment:** Users enroll their devices via the Intune Company Portal app.
  - **Android Devices:**
    - **Android Enterprise:** Supports work profiles for BYOD scenarios and full device management for corporate-owned devices.
    - **Device Administrator:** Legacy method for managing Android devices.
- 📌 **Example:** A company uses Windows Autopilot to automatically enroll and configure
