


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <p align="center">
  <img src="cloud_security_&_iam_portfolio.png" alt="Cloud Security & IAM Portfolio" style="width: 1020px; height: 620px; border-radius: 12px;" />
</p>
</body>
</html>


# Summary

This portfolio showcases my understanding of Cloud Security & IAM, protecting cloud environments, and managing user access effectively. Cloud Security involves implementing measures such as encryption, firewalls, and monitoring to safeguard data and resources in the cloud. Identity and Access Management (IAM) ensures that the right individuals have secure access to the appropriate resources, using tools like multi-factor authentication, role-based access control, and user policies. Together, they form the foundation for secure, compliant, and efficient cloud operations.

---

# Cloud Security & IAM Overview

Cloud Security encompasses the strategies, policies, and technologies used to protect cloud-based systems, data, and infrastructure from cyber threats. It involves measures such as encryption, intrusion detection systems, security groups, and continuous monitoring to ensure the confidentiality, integrity, and availability of cloud resources.

Identity and Access Management (IAM) is a critical component of cloud security that manages user identities and controls access to cloud resources. It involves creating and managing user accounts, setting permissions, and implementing authentication mechanisms like multi-factor authentication (MFA) to ensure that only authorized individuals can access specific data and services.

Key Components:

Encryption: Protects data at rest and in transit.
Access Controls: Define who can access what and under which conditions.
Monitoring & Auditing: Track activities for suspicious behavior and compliance.
Multi-Factor Authentication (MFA): Adds an extra layer of security for user verification.
Role-Based Access Control (RBAC): Assigns permissions based on user roles.
Importance:
Cloud Security & IAM are vital for safeguarding sensitive information, maintaining regulatory compliance, and ensuring operational resilience in cloud environments.:

Cloud Security Domains
---

## Domain 1: Cloud Concepts, Architecture, and Design ![Badge](https://img.shields.io/badge/Cloud%20Concepts-Architecture-brightblue?style=for-the-badge&logo=cloud)

This domain covers the foundational principles of cloud computing security, including deployment models (public, private, hybrid) and service models (IaaS, PaaS, SaaS). It emphasizes designing secure, scalable, and resilient cloud architectures that incorporate best practices such as network segmentation, secure multi-tenancy, and disaster recovery planning. Participants evaluate reference architectures and security design patterns to embed security controls into cloud solutions from the start, ensuring protection against threats and vulnerabilities.

---

## Domain 2: Cloud Data Security ![Badge](https://img.shields.io/badge/Data%20Security-Protection-blue?style=for-the-badge&logo=security)

Focuses on securing data in cloud environments throughout its lifecycle—at rest, in transit, and during processing. Techniques include cloud-specific encryption solutions (e.g., AWS KMS, Azure Key Vault), data masking, tokenization, and access control policies using cloud IAM. The domain also covers implementing Data Loss Prevention (DLP) tools integrated with cloud services, data classification frameworks, and privacy compliance (GDPR, HIPAA) to ensure proper data governance and protection in cloud platforms.

---

## Domain 3: Cloud Platform and Infrastructure Security ![Badge](https://img.shields.io/badge/Platform%20&%20Infra-Security-orange?style=for-the-badge&logo=shield)

Centers on securing cloud infrastructure components such as virtual machines, containers, serverless functions, and networking. Participants learn to implement cloud-native security controls like firewalls, security groups, and identity federation (e.g., AWS Cognito, Azure AD). The focus includes securing infrastructure-as-code (IaC) templates, managing vulnerabilities through automated patching, and employing cloud-specific threat detection tools like AWS GuardDuty, Azure Security Center, and Google Cloud Security Command Center to monitor for threats and vulnerabilities.

---

## Domain 4: Cloud Application Security ![Badge](https://img.shields.io/badge/Application-Dev-red?style=for-the-badge&logo=code)

Addresses securing cloud-native applications throughout their development lifecycle. Topics include secure coding practices, static and dynamic application security testing (SAST/DAST), and integrating security into CI/CD pipelines using tools like Jenkins, Azure DevOps, or GitLab. The domain emphasizes protecting APIs and microservices via OAuth, API gateways, and IAM policies, as well as defending against common cloud application threats such as injection, XSS, and insecure configurations.

---

## Domain 5: Cloud Security Operations ![Badge](https://img.shields.io/badge/Operations-Monitoring-yellow?style=for-the-badge&logo=eye)

Focuses on continuous security monitoring and incident response tailored for cloud environments. Participants implement and manage cloud-native SIEM solutions like Azure Sentinel, AWS Security Hub, or Google Chronicle, alongside IDS/IPS tools like Snort or Suricata. They learn to configure cloud monitoring services (AWS CloudWatch, Azure Monitor, Google Cloud Operations Suite), set up automated alerting, and utilize threat intelligence feeds and SOAR platforms to detect, analyze, and respond to security incidents efficiently. Emphasis is placed on maintaining operational resilience and automating response workflows in a dynamic cloud landscape.

---

## Domain 6: Legal, Risk, and Compliance![Badge](https://img.shields.io/badge/Legal-Risk-green?style=for-the-badge&logo=gavel)

Covers the regulatory frameworks governing cloud security, such as GDPR, HIPAA, PCI DSS, ISO/IEC 27001, and FedRAMP. It explains the specific security controls, data handling requirements, and audit procedures mandated by each regulation. Participants learn to perform risk assessments aligned with NIST SP 800-30, conduct cloud-specific audits, and develop compliance strategies that incorporate cloud security controls. This ensures organizations meet legal obligations, protect sensitive data, and maintain audit readiness in cloud environments.

---

### **Identity and Access Management (IAM)**

**Identity and Access Management (IAM)** is a fundamental aspect of cloud security that involves managing digital identities and controlling access to cloud resources. It ensures that only authorized users and systems can perform specific actions, thereby safeguarding sensitive data and infrastructure.

**Core Features of IAM:**
- **User Identity Management:** Creating, updating, and deleting user accounts.
- **Authentication:** Verifying user identities through methods such as passwords, MFA, and federated identity providers.
- **Authorization:** Assigning permissions and roles to define what resources users can access and what actions they can perform.
- **Role-Based Access Control (RBAC):** Simplifies permission management by assigning predefined roles to users based on their responsibilities.
- **Policy Management:** Defining security policies that govern access rules and conditions.

**Best Practices:**
- Implement multi-factor authentication (MFA) for all users.
- Follow the principle of least privilege—grant only necessary permissions.
- Regularly review and audit access logs and permissions.
- Use roles and groups to streamline permission management.

**Benefits:**
- Enhanced security by controlling access tightly
- Simplified user management
- Improved compliance with regulatory standards
- Reduced risk of insider threats and data breaches

---

## **Okta Labs: User Management and Role Assignment**
In this lab, we explored the process of creating and managing user accounts within the Okta Admin Console. We began by adding new users, then assigned the Super Admin role to elevate their permissions. The steps included selecting users, assigning roles, and saving changes to ensure proper access control. This hands-on experience demonstrated how to effectively manage user privileges and maintain security within the Okta identity management platform.

Creating Users in the Admin Console
---
1) Select Add Person
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/Add_Users.png)

Assigning Super Admin Role to a User
---
2) Select Admin
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/administrator_assignment_by_admin.png)

Assigning Super Admin Role to a User cont...
---
3) Select Role
---
Next

5) Save Changes
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/administrator_assignment_by_admin_2.png)
---
Last

6) User Elevated to Super Admin
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/administrator_assignment_by_admin_3.png)

Configure Group Membership Rules
---
1) Add people
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/configure_group_membership_rules.png)

2) Change Title to Manager
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/configure_group_membership_rules2.png)

3) Go to Groups, then add Rules
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/configure_group_membership_rules3.png)

4) Add Rule
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/configure_group_membership_rules4.png)

Configure Salesforce application with SAML in Okta Admin Portal 
---
***How to Configure SAML 2.0 for Salesforce: https://saml-doc.okta.com/SAML_Docs/How-to-Configure-SAML-2.0-in-Salesforce.html

---

1) Go to Applications, then click on Browse App Integration Catalog and search Salesforce
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/configure_salesforce_application_with_SAML_in_okta_admin_portal.png)

2) Click on Salesforce to get to General Settings, then click next
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/configure_salesforce_application_with_SAML_in_okta_admin_portal2.png)

3) At the Sign-On Options tab, select SAML 2.0 and for Application username format, select Custom
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/configure_salesforce_application_with_SAML_in_okta_admin_portal3.png)

4) Note the Expression Language Reference, then click Done
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/configure_salesforce_application_with_SAML_in_okta_admin_portal4.png)

5) Navigate to Single Sign-on Settings in Salesforce
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/configure_salesforce_SSO_settings_in_salesforce_portal.png)

6) Click New for SAML Single Sign-On Settings and fill in the required fields(Issuer, Identity Provider Certificate, Identity Provider Login URL, Custom Logout URL, and Entity ID)
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/configure_salesforce_SSO_settings_in_salesforce_portal2.png)

7) Click save and check settings
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/configure_salesforce_SSO_settings_in_salesforce_portal3.png)

Configure SP-Initiated SAML between Salesforce and Okta
---
1) Search for Domain Management in Quick Search
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/configure_SP-Initiated_SAML_between_salesforce_and_okta.png)

2) Click edit for My Domain Details and check domain availability, then click save
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/configure_SP-Initiated_SAML_between_salesforce_and_okta2.png)

Configure Salesforce Provisioning in Okta
---

LCM: Configure Salesforce for Life Cycle Management
---

Active Directory: User Import into Okta
---

SSO: Inbound SAML - Okta Org 1 Configuration
---

SSO: Inbound SAML - Federation Test
---

Multi-Factor Authentication (MFA) Policy
---

Global Authentication Policy in Action
---

Creating an Okta API key
---

Setup: Get the Authorization Server & Token Endpoint URLs
---

## ☁️ Cloud Provider Native IAM Tools
- **AWS IAM**: Comprehensive IAM solution for managing access to Amazon Web Services resources.
- **Azure Active Directory (Azure AD)**: Microsoft's identity management platform supporting single sign-on and multi-factor authentication.
- **Google Cloud IAM**: Google's IAM service for managing access and permissions across Google Cloud resources.

---

## 🛠️ Third-Party IAM Solutions
- **Okta**: Unified identity management and Single Sign-On (SSO), supporting multi-cloud environments and enterprise integrations.
- **Ping Identity**: Advanced authentication and access management supporting multi-factor authentication and zero-trust security.
- **Auth0**: Developer-friendly identity platform with support for various authentication methods and custom rules.
- **SailPoint**: Built-in identity and access management features within the Salesforce ecosystem, enabling secure user access and federation.

---

## 🚀 4. Best Practices & Technical Considerations

---

### ✅ 1. Use Standards-Based Protocols
- **Adopt protocols like** **SAML**, **OAuth 2.0**, and **OpenID Connect** to ensure interoperability across diverse IAM systems and cloud platforms.

---

### 🔑 2. Maintain a Single Source of Truth
- Centralize user identities within a trusted identity provider to prevent discrepancies and simplify management.

---

### ⚙️ 3. Automate User Provisioning & Deprovisioning
- Utilize **SCIM (System for Cross-domain Identity Management)** or **API integrations** to automate account creation, updates, and revocations based on organizational changes.

---

### 🔐 4. Enforce MFA & Least Privilege
- Mandate **Multi-Factor Authentication (MFA)** for all users to enhance security.
- Follow the **least privilege principle**—grant only permissions necessary for each user's role to minimize risk.

---

### 🔍 5. Regularly Review Policies & Logs
- Conduct periodic audits of **trust policies**, **access logs**, and **permissions**.
- Adjust policies as organizational needs evolve to maintain security and compliance.

---

### 📝 Summary
Implementing these best practices ensures a robust, secure, and manageable IAM environment across your cloud and on-premises infrastructure.



Still in progress.....
