


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

### **IAM Best Practice**
Design secure, scalable identity architectures with strong access controls.
Implementation: Use Azure AD, AWS IAM, or Google Cloud IAM to establish role-based access control (RBAC) and identity federation from the start, embedding identity security into cloud architecture, enabling least privilege, and implementing network segmentation for secure multi-tenancy.

---

## Domain 2: Cloud Data Security ![Badge](https://img.shields.io/badge/Data%20Security-Protection-blue?style=for-the-badge&logo=security)

Focuses on securing data in cloud environments throughout its lifecycle—at rest, in transit, and during processing. Techniques include cloud-specific encryption solutions (e.g., AWS KMS, Azure Key Vault), data masking, tokenization, and access control policies using cloud IAM. The domain also covers implementing Data Loss Prevention (DLP) tools integrated with cloud services, data classification frameworks, and privacy compliance (GDPR, HIPAA) to ensure proper data governance and protection in cloud platforms.

### **IAM Best Practice**
Secure infrastructure components with granular identity and access controls.
Implementation: Deploy Azure AD, AWS IAM, or Google Cloud IAM to control access to cloud resources such as VMs, containers, and networking. Use identity federation (e.g., AWS Cognito, Azure AD) and Infrastructure-as-Code (IaC) security practices to enforce access policies and automate vulnerability management with tools like AWS Security Hub or Azure Security Center.

---

## Domain 3: Cloud Platform and Infrastructure Security ![Badge](https://img.shields.io/badge/Platform%20&%20Infra-Security-orange?style=for-the-badge&logo=shield)

Centers on securing cloud infrastructure components such as virtual machines, containers, serverless functions, and networking. Participants learn to implement cloud-native security controls like firewalls, security groups, and identity federation (e.g., AWS Cognito, Azure AD). The focus includes securing infrastructure-as-code (IaC) templates, managing vulnerabilities through automated patching, and employing cloud-specific threat detection tools like AWS GuardDuty, Azure Security Center, and Google Cloud Security Command Center to monitor for threats and vulnerabilities.

### **IAM Best Practice**
Secure infrastructure components with granular identity and access controls.
Implementation: Deploy Azure AD, AWS IAM, or Google Cloud IAM to control access to cloud resources such as VMs, containers, and networking. Use identity federation (e.g., AWS Cognito, Azure AD) and Infrastructure-as-Code (IaC) security practices to enforce access policies and automate vulnerability management with tools like AWS Security Hub or Azure Security Center.

---

## Domain 4: Cloud Application Security ![Badge](https://img.shields.io/badge/Application-Dev-red?style=for-the-badge&logo=code)

Addresses securing cloud-native applications throughout their development lifecycle. Topics include secure coding practices, static and dynamic application security testing (SAST/DAST), and integrating security into CI/CD pipelines using tools like Jenkins, Azure DevOps, or GitLab. The domain emphasizes protecting APIs and microservices via OAuth, API gateways, and IAM policies, as well as defending against common cloud application threats such as injection, XSS, and insecure configurations.

### **IAM Best Practice**
Protect APIs and applications with strong authentication and authorization.
Implementation: Implement OAuth 2.0, OpenID Connect, and API gateways (e.g., Azure API Management, AWS API Gateway) integrated with Okta or Auth0 for secure API access. Apply role-based access policies and enforce secure coding practices, including SAST/DAST tools, to prevent common vulnerabilities.

---

## Domain 5: Cloud Security Operations ![Badge](https://img.shields.io/badge/Operations-Monitoring-yellow?style=for-the-badge&logo=eye)

Focuses on continuous security monitoring and incident response tailored for cloud environments. Participants implement and manage cloud-native SIEM solutions like Azure Sentinel, AWS Security Hub, or Google Chronicle, alongside IDS/IPS tools like Snort or Suricata. They learn to configure cloud monitoring services (AWS CloudWatch, Azure Monitor, Google Cloud Operations Suite), set up automated alerting, and utilize threat intelligence feeds and SOAR platforms to detect, analyze, and respond to security incidents efficiently. Emphasis is placed on maintaining operational resilience and automating response workflows in a dynamic cloud landscape.

### **IAM Best Practice**
Enable continuous monitoring of access and user activity.
Implementation: Use Azure Sentinel, AWS Security Hub, or Google Chronicle combined with CloudTrail, Azure Monitor, or Google Cloud Operations to track access logs. Configure alerts for suspicious activity, integrate with SOAR platforms, and enforce automated incident response workflows, ensuring proper access oversight.

---

## Domain 6: Legal, Risk, and Compliance![Badge](https://img.shields.io/badge/Legal-Risk-green?style=for-the-badge&logo=gavel)

Covers the regulatory frameworks governing cloud security, such as GDPR, HIPAA, PCI DSS, ISO/IEC 27001, and FedRAMP. It explains the specific security controls, data handling requirements, and audit procedures mandated by each regulation. Participants learn to perform risk assessments aligned with NIST SP 800-30, conduct cloud-specific audits, and develop compliance strategies that incorporate cloud security controls. This ensures organizations meet legal obligations, protect sensitive data, and maintain audit readiness in cloud environments.

### **IAM Best Practice**
Ensure access controls and identity policies support regulatory compliance.
Implementation: Leverage tools like Saviynt, SailPoint, or CyberArk to automate access reviews, enforce policies aligned with standards like GDPR, HIPAA, and PCI DSS, and maintain audit trails. Conduct risk assessments and compliance audits regularly to verify that IAM controls meet legal and regulatory requirements.

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

## **Okta Labs** 

## **User Management and Role Assignment**
In this lab, we explored the process of creating and managing user accounts within the Okta Admin Console. We began by adding new users, then assigned the Super Admin role to elevate their permissions. The steps included selecting users, assigning roles, and saving changes to ensure proper access control. This hands-on experience demonstrated how to effectively manage user privileges and maintain security within the Okta identity management platform.

---

Creating Users in the Admin Console
---
1) Select Add Person
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/Add_Users.png)

Assigning Super Admin Role to a User
---
2) Select Admin
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/administrator_assignment_by_admin.png)

Assigning Super Admin Role to a User cont...
---
3) Select Role
---
Next

5) Save Changes
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/administrator_assignment_by_admin_2.png)
---
Last

6) User Elevated to Super Admin
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/administrator_assignment_by_admin_3.png)

## **Configure Group Membership Rules**
In this lab, participants learned how to automate user group management within an identity platform by configuring dynamic group membership rules. The exercise involved creating rules based on user attributes, such as job title or department, to automatically assign users to specific groups. This process streamlines access management, reduces manual administrative effort, and ensures consistent application of security policies. Through hands-on practice, participants gained experience in customizing rules to enforce organizational access controls effectively.

---

Creating Group Membership Rules
---
1) Add people
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_group_membership_rules.png)

2) Change Title to Manager
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_group_membership_rules2.png)

3) Go to Groups, then add Rules
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_group_membership_rules3.png)

4) Add Rule
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_group_membership_rules4.png)

## **Configure Salesforce application with SAML in Okta Admin Portal**
In this lab, participants learned how to set up Single Sign-On (SSO) for Salesforce using SAML 2.0 within the Okta Admin Portal. The process involved integrating Salesforce as a SAML application, configuring the sign-on options, and customizing the user identification format with expression language. Participants also configured Salesforce’s Single Sign-On settings, including issuer, identity provider certificate, and login URLs. This hands-on exercise demonstrated how to establish a secure and seamless authentication experience for users, enabling centralized access control and improved security through SAML-based federation.

---

   How to Configure SAML 2.0 for Salesforce: https://saml-doc.okta.com/SAML_Docs/How-to-Configure-SAML-2.0-in-Salesforce.html
   
---

1) Go to Applications, then click on Browse App Integration Catalog and search Salesforce
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_salesforce_application_with_SAML_in_okta_admin_portal.png)

2) Click on Salesforce to get to General Settings, then click next
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_salesforce_application_with_SAML_in_okta_admin_portal2.png)

3) At the Sign-On Options tab, select SAML 2.0 and for Application username format, select Custom
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_salesforce_application_with_SAML_in_okta_admin_portal3.png)

4) Note the Expression Language Reference, then click Done
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_salesforce_application_with_SAML_in_okta_admin_portal4.png)

5) Navigate to Single Sign-on Settings in Salesforce
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_salesforce_SSO_settings_in_salesforce_portal.png)

6) Click New for SAML Single Sign-On Settings and fill in the required fields(Issuer, Identity Provider Certificate, Identity Provider Login URL, Custom Logout URL, and Entity ID)
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_salesforce_SSO_settings_in_salesforce_portal2.png)

7) Click save and check settings
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_salesforce_SSO_settings_in_salesforce_portal3.png)

## **Configure SP-Initiated SAML between Salesforce and Okta**
In this lab, participants learned how to set up Service Provider (SP)-initiated SAML authentication to enable seamless single sign-on between Salesforce and Okta. The exercise involved configuring domain management within Salesforce, ensuring that the custom domain is available and properly set up for federated login. This configuration allows users to access Salesforce through Okta’s SSO portal, providing a unified and secure authentication experience. The hands-on process demonstrated how to establish a trust relationship between Salesforce and Okta, ensuring secure, streamlined access to organizational resources.

---

1) Search for Domain Management in Quick Search
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_SP-Initiated_SAML_between_salesforce_and_okta.png)

2) Click edit for My Domain Details and check domain availability, then click save
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_SP-Initiated_SAML_between_salesforce_and_okta2.png)

3) Deploy New Domain (oktafundamentals7-dev-ed)
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_SP-Initiated_SAML_between_salesforce_and_okta4.png)

4) Copy the Domain Name, then paste it into the browser
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_SP-Initiated_SAML_between_salesforce_and_okta3.png)

5) Single Sign-on into Salesforce
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_SP-Initiated_SAML_between_salesforce_and_okta4.png)

## **Configure Salesforce Provisioning in Okta**
In this lab, participants learned how to enable and configure provisioning between Okta and Salesforce to automate user lifecycle management. The exercise involved setting up provisioning settings within the Salesforce application in Okta, including enabling user creation, updates, and deactivation. Participants explored how to synchronize user data, assign appropriate roles, and manage user access dynamically. This process enhances operational efficiency, ensures accurate and consistent user information, and maintains security by automating account provisioning and deprovisioning across the integrated systems.

---

Okta Labs Guide: https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/okta_labs.pdf

---

1) Go to Salesforce and switch to Lightning Experience view and search for App Manager
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_salesforce_provisioning_in_okta.png)

2) Click on New External Client App
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_salesforce_provisioning_in_okta2.png)

4) Fill Basic Information
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_salesforce_provisioning_in_okta3.png)

5) Copy Consumer Details
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_salesforce_provisioning_in_okta4.png)

6) Log ack into Okta and enable API integration. Enter the OAuth Consumer Key and the OAuth Consumer Secret, click Authenticate with Salesforce.com, then click Save.
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_salesforce_provisioning_in_okta6.png)

7) Integration complete
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_salesforce_provisioning_in_okta7.png)

## **LCM: Configure Salesforce for Life Cycle Management**
In this lab, participants learned how to implement and manage the entire user lifecycle in Salesforce using Okta’s lifecycle management capabilities. The exercise involved configuring automated workflows for user onboarding, updates, and offboarding to ensure that user access is consistently aligned with their current role and status. Participants set up policies for automatic account provisioning, deactivation, and synchronization, enabling secure and efficient management of Salesforce user accounts throughout their employment lifecycle. This process helps organizations reduce manual effort, minimize security risks, and ensure compliance through automated lifecycle workflows.

1) Click edit, then enable Create Users, Update User Attributes, and Deactivate Users
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/LCM_configure_salesforce_for_life_cycle_management.png)

2) Assign Users
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/LCM_configure_salesforce_for_life_cycle_management2.png)

3) User Created
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/LCM_configure_salesforce_for_life_cycle_management4.png)

5) Go back to Salesforce and click on Manage Users and search for the user account created
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/LCM_configure_salesforce_for_life_cycle_management3.png)

6) LCM: Looking at System Logs and checking for errors
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/LCM_configure_salesforce_for_life_cycle_management5.png)

7) LCM: Deprovision Salesforce Users/ Click x sign next to the user's name to Unassign User
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/LCM_configure_salesforce_for_life_cycle_management6.png)

8) Lastly, view the logs to verify deprovisioning for Fisto Asajj
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/LCM_configure_salesforce_for_life_cycle_management7.png)

9) User is no longer active in Salesforce
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/LCM_configure_salesforce_for_life_cycle_management8.png)

---

## **Multi-Factor Authentication (MFA) Policy**
In this lab, participants learned how to create and manage MFA policies to enhance the security of user authentication. The exercise involved configuring MFA requirements within an identity management platform, including selecting authentication factors such as SMS, authenticator apps, or hardware tokens. Participants set policies based on user roles, locations, or risk levels to enforce multi-factor authentication for sensitive applications and access scenarios. This process helps organizations strengthen security, reduce the risk of compromised credentials, and ensure compliance with security standards.

1) Create Network Policy. Click on the Security tab, then Network, click on the dropdown "Add Zone", then choose IP Zone
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/multi_factor_authentication.png)

2) Add Zone name, Gateway IPs, then click Save
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/multi_factor_authentication3.png)

3) Next, add Dynamic Zone. Fill in the Zone name and Locations. Then click Save
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/multi_factor_authentication4.png)

4) Corporate Locations and Corporate Office are Active
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/multi_factor_authentication5.png)

5) Add another Dynamic Zone for Blocklisted. Fill in the Zone name and Locations. Then click Save
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/multi_factor_authentication6.png)

6) Blocklisted Countries is now Active
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/multi_factor_authentication7.png)

7) Set Password Policy. Click on Authenticator
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/multi_factor_authentication8.png)

8) Add Okta Verify
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/multi_factor_authentication9.png)

9) Go to Password Policy, click on Action, then Edit. Add New Password Policy
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/multi_factor_authentication10.png)

10) Add Policy name, Policy description, Add group, and Password age
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/multi_factor_authentication11.png)

11) Add Policy name, Policy description, Add group, Password, then Create Policy age cont..
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/multi_factor_authentication12.png)

12) Next, select Rule name, User's IP is, and Recovery authenticators, then Create Rule
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/multi_factor_authentication13.png)

13) Sales-Okta Password Policy is now Active
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/multi_factor_authentication14.png)

14) Sales-Okta Password Policy is now Active cont...
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/multi_factor_authentication15.png)

---

## **Global Authentication Policy in Action**
In this lab, participants explored how to implement and enforce a comprehensive authentication policy across an organization. The exercise involved configuring global policies that specify authentication requirements, such as multi-factor authentication (MFA), adaptive risk-based authentication, and password policies. Participants observed how these policies apply universally to all users and applications, ensuring consistent security standards. The session demonstrated how to monitor policy enforcement and adjust settings as needed to balance security with user convenience, thereby strengthening overall organizational security posture.

1) Navigate to Global Authentication Policy
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/global_authentication_policy.png)

2) Click Add Policy. Fill Policy name, Policy description, and Assign to groups. Then click Create Policy and Add Rule
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/global_authentication_policy2.png)

3) Corporate Policy Rule created
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/global_authentication_policy3.png)

---

## 📚 Microsoft Identity and Access Labs

### 🚀 Lab 1: Configure and manage built-in and custom Microsoft Entra roles
This lab guides you through configuring and managing Microsoft Entra (Azure AD) roles, including assigning built-in roles to users and creating custom roles tailored to specific administrative needs. You will learn how to assign roles securely, understand role scopes, and customize roles to implement the principle of least privilege effectively in your environment.

1) Add a new Custom Role. Add Name, then click next twice, then create
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_and_manage_built_in.png).

2) Add permission to Custom Role. Then click next
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_and_manage_built_in2.png).

3) Click Create
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_and_manage_built_in3.png).

4) Custom Role Created
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_and_manage_built_in4.png).

---
### 🔑 Lab 2: Setting up a domain controller

1) Click Manage, then Add Roles and Features
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/setting_up_a_domain_controller.png).

2) Choose Role-based or feature-based installation
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/setting_up_a_domain_controller2.png).

3) Select a server from the server pool
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/setting_up_a_domain_controller3.png).

4) Click next, then Add Features
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/setting_up_a_domain_controller4.png).

5) Features installing
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/setting_up_a_domain_controller5.png).

6) Click on Promote this server to a domain
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/setting_up_a_domain_controller6.png).

7) Deployment Configuration, click Next
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/setting_up_a_domain_controller7.png).

8) Fill out Domain Controller Options, then click next
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/setting_up_a_domain_controller9.png).

9) Enter the NetBIOS Domain name, then click Next twice
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/setting_up_a_domain_controller10.png).

10) Verify Prerequisites(Check and fix prerequisites errors before proceeding)
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/setting_up_a_domain_controller11.png).

11) AD Domain Controller Installed 
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/setting_up_a_domain_controller12.png).

### 🔑 Lab 2: Configure and manage built-in and custom Microsoft Entra roles
This lab walks you through the process of configuring and managing Microsoft Entra (Azure AD) roles. You will learn how to assign and modify built-in roles to meet organizational needs, as well as create and customize custom roles for specific administrative tasks. This exercise emphasizes the importance of role-based access control (RBAC) to enforce the principle of least privilege and enhance security within your Azure environment.

1) Select New Custom Role
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_and_manage_built-in_and_custom_microsoft_entra_roles.png).

2) Add name, then click next
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_and_manage_built-in_and_custom_microsoft_entra_roles2.png).

3) Search user, then select permission, then click next
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_and_manage_built-in_and_custom_microsoft_entra_roles3.png).

4) Review + Create
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_and_manage_built-in_and_custom_microsoft_entra_roles4.png).

5) Custom Helpdesk User Properties Tier 1 role successfully created
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_and_manage_built-in_and_custom_microsoft_entra_roles5.png).
---

### 🔒 Lab 3: Configure and manage administrative units
This lab guides you through the process of configuring and managing Administrative Units within Microsoft Entra (Azure AD). You will learn how to create administrative units to delegate management of specific groups or users, assign roles at the administrative unit level, and enforce scoped administrative permissions. This practice helps in segmenting administrative responsibilities and maintaining a secure, organized management structure in large or complex environments.

1) Create New User
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_and_manage_built-in_and_custom_microsoft_entra_roles.png).

2) Add User principal name, Display name, and password, then click next: properties
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_and_manage_built-in_and_custom_microsoft_entra_roles2.png).

2) Add Info, then click next: assignment
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_and_manage_built-in_and_custom_microsoft_entra_roles3.png).

3) Click Review + Create
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_and_manage_built-in_and_custom_microsoft_entra_roles4.png).

4) Click on Administrative Unit, then add Administrative Unit, then Review + Create
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_and_manage_built-in_and_custom_microsoft_entra_roles5.png).

5) Administrative Unit Created Successfully
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_and_manage_administrative_units6.png).

6) User added to Administrative Unit 
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_and_manage_administrative_units7.png).

### ✅ Lab 4: Configure and manage domains in Microsoft Entra ID and Microsoft 365
This lab covers the process of configuring and managing custom domains within Microsoft Entra ID (Azure AD) and Microsoft 365. You will learn how to add, verify, and troubleshoot domain ownership, set up domain-specific policies, and manage DNS records. This enables seamless integration of your organization’s branded domains, ensuring consistent identity management across Azure AD and Microsoft 365 services.

1) Add Domain 
![Add Users](https://raw.githubusercontent.com/agustus9/Cloud-Security-IAM-Portfolio/main/my-ng-files/configure_and_manage_domains_in_microsoft_entra_id_and_microsoft_365.png).
---

### ✅ Lab 5: Assign, classify, and manage users, groups, and app roles for enterprise apps
- **Objective:** Enforce MFA for selected users.
- **Steps:**
  1. Enable MFA in Azure AD.
  2. Require MFA for specific groups.
  3. Test login prompts with MFA.
- **Resources:** [Azure MFA Documentation](https://docs.microsoft.com/en-us/azure/active-directory/authenticate-mfa)

  ### ✅ Lab 5: Configure Azure Key Vault role-based access control (RBAC) and access policies

   ### ✅ Lab 7: Create, configure, and manage users

   ### ✅ Lab 6: Create a conditional access policy that blocks high risk Android...

  ### ✅ Lab 7: Create, configure, and manage groups in the Azure portal

  ### ✅ Lab 8: Configure external identity providers, including protocols such as SAML & WS-Fed

  ### ✅ Lab 9: Implement and manage Microsoft Entra Connect Sync with password hash sync

  ### ✅ Lab 10: Implement and manage authentication, certificate, temp access pass,OATH, & FIDO2

  ### ✅ Lab 11: Implement and manage tenant-wide Multi-factor Authentication (MFA) settings
  ### ✅ Lab 12: Use Defender for Cloud Apps & create a file policy for detection
  ### ✅ Lab 13: Create an access request catalog & package for Medical User
  ### ✅ Lab 14:  Use PIM and make Adam Young eligible for User Administrator...
  ### ✅ Lab 15: Use Sentinel. Run Failed Login Attempt Query.
  ### ✅ Lab 16: Azure AD activity by using Log Analytics / Sentinel, Workbooks excluding KQL use
  ### ✅ Lab 17: Configuring notifications

---

## ☁️ Implement and manage tenant-wide Multi-factor Authentication (MFA) settings
- **AWS IAM**: Comprehensive IAM solution for managing access to Amazon Web Services resources.
- **Microsoft Entra (Entra ID)**: Microsoft's identity management platform supporting single sign-on and multi-factor authentication.
- **Google Cloud IAM**: Google's IAM service for managing access and permissions across Google Cloud resources.

---

## 🛠️ Third-Party IAM Solutions
- **Okta**: Unified identity management and Single Sign-On (SSO), supporting multi-cloud environments and enterprise integrations.
- **SailPoint**: Built-in identity and access management features within the Salesforce ecosystem, enabling secure user access and federation.
- **CyberArk**: Security solution specializing in privileged access management and safeguarding critical assets.
- **Saviynt**: Identity governance platform for managing access and compliance across hybrid and multi-cloud environments.
- **Ping Identity**: Advanced authentication and access management supporting multi-factor authentication and zero-trust security.
  
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
