# 📘 Module 2: Managing and Protecting Devices

> Source: [Module Link](https://learn.microsoft.com/en-us/training/modules/protect-endpoints-with-endpoint-manager/2-managing-protecting-devices)

---

### 🔹 Device Enrollment and Management

- 🔑 **Key:** Devices must be enrolled in Intune to receive policies and be secured.
- ❗ **Important:** Enrollment gives Intune visibility and control over device settings.
- 🧩 **Supporting Details:**
  - Enrollment methods vary: automatic, manual, or using tools like Autopilot.
  - Once enrolled, devices can receive compliance, configuration, and security policies.
- 📌 **Example:** A Windows laptop is automatically enrolled via Autopilot and receives Wi-Fi, email, and antivirus settings.
- 💬 **Scenario:** A new employee turns on their work laptop — it configures itself through Intune with the right settings and security.

---

### 🔹 Compliance and Device Protection

- 🔑 **Key:** Compliance policies ensure devices meet security standards before accessing corporate data.
- ❗ **Important:** Non-compliant devices can be blocked or limited via Conditional Access.
- 🧩 **Supporting Details:**
  - Policies check for things like encryption, OS version, passcode, antivirus status.
  - Can work alongside Microsoft Defender and other endpoint security tools.
- 📌 **Example:** A phone without a PIN is marked non-compliant and blocked from accessing Outlook.
- 💬 **Scenario:** IT enforces encryption and password policies — devices failing those get flagged and can't access company data until fixed.

---
https://learn.microsoft.com/en-us/training/endpoint-manager/protect-endpoints-with-endpoint-manager/media/intro-to-endpoint-manager-13.png#lightbox