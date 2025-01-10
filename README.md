# Intune iOS Device Management Project

## Overview
This project demonstrates the complete process of **managing iOS devices using Microsoft Intune**. The steps cover the enrollment of devices, configuring security policies, integrating **PKI**, and implementing **Conditional Access** for secure access to corporate resources.

## Table of Contents
1. [Initial Setup and Configuration](#1-initial-setup-and-configuration)
2. [Device Enrollment](#2-device-enrollment)
3. [Integrating PKI](#3-integrating-pki)
4. [Implementing MIM](#4-implementing-mim)
5. [Mobile Endpoint Management](#5-mobile-endpoint-management)
6. [Ongoing Monitoring and Maintenance](#6-ongoing-monitoring-and-maintenance)
7. [User Experience and Support](#7-user-experience-and-support)

---

## 1. Initial Setup and Configuration
In this phase, the **Intune environment** was configured, including setting up **MDM authority**, **device enrollment settings**, and ensuring **PKI** was integrated for secure communications.

- Configured **Intune** environment for **device management**.
- Set up **MDM authority** to manage iOS devices.
- Ensured all necessary **security policies** and **enrollment settings** were configured for smooth device enrollment.
  
**Screenshots**: 
- [MDM Authority Settings](./images/mdm_authority_settings.png)
- [Device Enrollment Configuration](./images/device_enrollment_configuration.png)

---

## 2. Device Enrollment
The devices were enrolled into **Intune** using **manual enrollment** methods through the **Company Portal app**.

- **iOS devices** were enrolled into **Intune** manually via the **Company Portal**.
- The device was successfully enrolled and the **management profile** was installed.
- Device settings like **Wi-Fi**, **VPN**, and **email** were automatically configured.

**Screenshots**:
- [Device Enrollment Success](./images/device_enrollment_success.png)
- [Profile Installation](./images/profile_installation.png)

---

## 3. Integrating PKI
This step integrates **PKI** for managing certificates used in securing **Wi-Fi**, **VPN**, and **other corporate apps**.

- **Root certificates** were deployed to devices to ensure secure communication with corporate resources.
- **Certificate profiles** were configured for **Wi-Fi** and **VPN** connectivity, utilizing **PKI** for authentication.

**Screenshots**:
- [PKI Configuration](./images/pki_configuration.png)
- [Certificate Profiles](./images/certificate_profiles.png)

---

## 4. Implementing MIM
**Microsoft Identity Manager (MIM)** was integrated for managing **identity** and **access controls**, ensuring that only compliant devices can access **corporate resources**.

- **MIM** was integrated with **Azure Active Directory (AAD)** and **Intune**.
- **Conditional Access** policies were configured to allow only compliant devices to access corporate apps.

**Screenshots**:
- [MIM Integration](./images/mim_integration.png)
- [Conditional Access Policies](./images/conditional_access_policies.png)

---

## 5. Mobile Endpoint Management
Devices were managed by applying various **compliance policies** and distributing corporate apps using **Intune**.

- **Compliance policies** were applied to enforce **password complexity** and **encryption**.
- **Corporate apps** were distributed to the enrolled devices through **Intune**.

**Screenshots**:
- [Compliance Policies](./images/compliance_policies.png)
- [App Deployment](./images/app_deployment.png)

---

## 6. Ongoing Monitoring and Maintenance
The **Intune Admin Console** was used to monitor the devices for compliance, manage **device lifecycle**, and address any **compliance issues**.

- Devices' **compliance status** was regularly monitored.
- **Profiles** and **policies** were updated as necessary.
- **Device health** was continuously checked to ensure they met corporate security standards.

**Screenshots**:
- [Device Compliance Dashboard](./images/device_compliance_dashboard.png)
- [Profile Update](./images/profile_update.png)

---

## 7. User Experience and Support
End-user experience was carefully considered, and support was provided for any **device-related issues** or troubleshooting.

- **Company Portal** was used to ensure users could access corporate apps easily.
- Support was provided to users experiencing **non-compliant devices** or enrollment issues.

**Screenshots**:
- [Company Portal User Interface](./images/company_portal_user_interface.png)
- [Support Desk Scenario](./images/support_desk_scenario.png)

---

## Conclusion
This project demonstrates the complete workflow of managing **iOS devices** using **Microsoft Intune**, from enrollment and configuration to ongoing management and user support. The steps outlined above were fully implemented in a homelab environment, showcasing the ability to **securely manage mobile endpoints** and maintain compliance with corporate security policies.

---

## How to Run This Project
If you'd like to replicate this setup, follow the steps outlined in each section and adjust according to your organization's **device management policies**. Please ensure you have an **Intune** subscription and the necessary permissions to manage devices.
