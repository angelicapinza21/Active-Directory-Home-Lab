# Enterprise Active Directory Home Lab

## Project Overview
This lab demonstrates the end-to-end deployment of a Windows Server 2019 Domain Controller within a virtualized environment. The project covers infrastructure initialization, network configuration, and Identity & Access Management (IAM) within the `Austinslab.local` domain.

## Tools Used
- VirtualBox
- Windows Server 2019
- Windows 10
- Active Directory Domain Services (AD DS)

---

## Phase 1: Infrastructure & Domain Deployment
| Step | Administrative Task | Technical Documentation |
| :--- | :--- | :--- |
| 01 | Server Manager Dashboard | ![01](screenshots/01-server-manager-dashboard.png) |
| 02 | AD DS Role Deployment | ![02](screenshots/02-ad-ds-deployment-wizard.png) |
| 03 | Active Directory Forest Setup | ![03](screenshots/03-active-directory-forest-setup.png) |
| 04 | Server Installation Progress | ![04](screenshots/04-server-installation-progress.png) |
| 05 | Active Directory Topology | ![05](screenshots/05-active-directory-topology.png) |
| 06 | Active Directory User Objects | ![06](screenshots/06-active-directory-user-objects.png) |

## Phase 2: Networking & Client Integration
| Step | Administrative Task | Technical Documentation |
| :--- | :--- | :--- |
| 07 | Static IP & DNS Configuration | ![07](screenshots/07-static-ip-dns-configuration.png) |
| 08 | Endpoint Domain Join Success | ![08](screenshots/08-endpoint-domain-join-success.png) |
| 09 | Domain Administrator Login | ![09](screenshots/09-domain-administrator-login.png) |

## Phase 3: Identity & Access Management (IAM)
| Step | Administrative Task | Technical Documentation |
| :--- | :--- | :--- |
| 10 | OU Logical Structure | ![10](screenshots/10-ou-logical-structure.png) |
| 11 | Security Group Management | ![11](screenshots/11-security-group-management.png) |
| 12 | Domain User Configuration | ![12](screenshots/12-domain-user-configuration.png) |
| 13 | Identity Validation | ![13](screenshots/13-identity-validation.png) |
| 14 | Password Reset Policy | ![14](screenshots/14-password-reset.png) |

---
*For a full technical breakdown and configuration logs, see [notes/lab-notes.txt](notes/lab-notes.txt).*
