# 📘 Module 6: Platform Considerations

> Source: [Module Link](https://learn.microsoft.com/en-us/training/modules/protect-endpoints-with-endpoint-manager/6-platform-considerations)

---

### 🔹 Cross-Platform Support

- 🔑 **Key:** Intune supports Windows, macOS, iOS, and Android.
- ❗ **Important:** Each platform has different features and limitations for management.
- 🧩 **Supporting Details:**
  - Platform-specific settings: e.g., iOS uses Apple MDM protocols, Windows uses CSPs.
  - Management options differ: full management (MDM) vs. app protection (MAM).
- 📌 **Example:** macOS requires a management profile; iOS needs a push notification certificate.
- 💬 **Scenario:** A company uses iPhones for execs and Windows laptops for staff — Intune enforces passcode and encryption settings for both, but with platform-specific configs.

---

### 🔹 Choosing the Right Approach

- 🔑 **Key:** The management approach depends on device ownership, use case, and security requirements.
- ❗ **Important:** BYOD vs. corporate-owned devices will influence how much
https://learn.microsoft.com/en-us/training/endpoint-manager/protect-endpoints-with-endpoint-manager/media/intro-to-endpoint-manager-08.png