# Microsoft Endpoint Manager – Module 4: Understand Microsoft Configuration Manager

> Source: https://learn.microsoft.com/en-us/training/modules/intro-to-endpoint-manager/4-endpoint-configuration-manager

## 🧩 Microlearning Chunks with Key Details

---

### 🔹 Chunk 1: What is Microsoft Configuration Manager?

- 🔑 **Key:** Microsoft Configuration Manager is an on-premises tool to manage devices, apps, and updates in larger enterprise environments.
- ❗ **Important:** It provides deep control over how devices are configured, patched, and secured.
- 🧩 **Supporting Details:**
  - Used for OS deployment, software distribution, update management, and endpoint protection
  - Suitable for managing Windows PCs, servers, and some non-Windows devices
- 📌 **Example:** IT teams use Configuration Manager to deploy security updates to thousands of PCs.
- 💬 **Scenario:** A university uses Configuration Manager to image lab computers with pre-approved software before a new semester.

---

### 🔹 Chunk 2: Configuration Manager vs. Intune

- 🔑 **Key:** Intune is cloud-based; Configuration Manager is on-prem — both can be used together.
- ❗ **Important:** Co-management lets organizations transition to the cloud at their own pace.
- 🧩 **Supporting Details:**
  - Configuration Manager offers granular, high-control management
  - Intune provides modern, flexible, remote management
  - Together they support hybrid management scenarios
- 📌 **Example:** A healthcare org uses ConfigMgr for on-site PCs and Intune for mobile devices.
- 💬 **Scenario:** A company begins by managing desktops with ConfigMgr and slowly moves laptops to Intune for remote work.

---

### 🔹 Chunk 3: Integration and Cloud Attach

- 🔑 **Key:** Cloud attach allows Configuration Manager to connect with Microsoft Intune and other cloud services.
- ❗ **Important:** This enables a modern, cloud-powered experience while keeping on-prem control.
- 🧩 **Supporting Details:**
  - Endpoint analytics and reporting
  - Tenant attach: gives visibility into ConfigMgr devices from the Microsoft Intune portal
  - Better patching, compliance, and insights
- 📌 **Example:** IT can monitor both Intune and ConfigMgr devices from one cloud console.
- 💬 **Scenario:** A technician sees a performance issue on a Windows device via Endpoint analytics and pushes a fix — even though it’s managed on-prem.

---

https://learn.microsoft.com/en-us/training/endpoint-manager/intro-to-endpoint-manager/media/intro-to-endpoint-manager-03a.png#lightbox