# Active-Directory-Fundamental-IAM
Hands-on Active Directory lab covering domains, users, groups, authentication, Group Policy, and IAM concepts using TryHackMe.
# Active Directory Fundamentals for IAM

## Overview

This repository documents my completion of the Active Directory Basics room on TryHackMe. The goal of this lab was to build a foundational understanding of Active Directory and explore how identity, authentication, authorization, and access management function within enterprise environments.

As I continue developing toward an Identity and Access Management (IAM) Engineer role, understanding Active Directory is essential because many IAM platforms integrate directly with AD as a primary identity source.

---

## Objectives

- Understand Windows Domains and Active Directory
- Learn how users and computers are managed in AD
- Explore Group Policy and centralized administration
- Understand authentication methods used in enterprise environments
- Learn how forests, trees, and trusts enable access across domains
- Connect Active Directory concepts to Identity and Access Management (IAM)

---

## Lab Information

- Platform: TryHackMe
- Room: Active Directory Basics
- Category: Windows & Active Directory Fundamentals
- Focus Areas:
  - Active Directory Domain Services (AD DS)
  - User Management
  - Computer Management
  - Group Policy
  - Authentication
  - Forests and Trust Relationships

---

## Topics Covered

### Windows Domains

A Windows Domain provides centralized administration and management of users, computers, security policies, and resources across an organization.

**Key Takeaways**
- Centralized authentication
- Centralized administration
- Improved security and scalability

**IAM Connection**
- Acts as a centralized identity store
- Often serves as the source of truth for enterprise identities

---

### Active Directory

Active Directory Domain Services (AD DS) is Microsoft's directory service used to manage identities, resources, and access within a Windows environment.

**Key Takeaways**
- Domain Controllers
- Directory Services
- User and Computer Objects
- Authentication and Authorization

**IAM Connection**
- Primary identity source for many organizations
- Integrates with platforms such as Okta, Microsoft Entra ID, SailPoint, and CyberArk

---

### Managing Users in Active Directory

User management involves creating, modifying, disabling, and deleting user accounts within the domain.

**Key Takeaways**
- User Accounts
- Password Management
- Account Administration

**IAM Connection**
- Joiner, Mover, Leaver processes
- User provisioning and deprovisioning
- Identity lifecycle management

---

### Managing Computers in Active Directory

Computers can be joined to a domain and managed centrally through Active Directory.

**Key Takeaways**
- Computer Objects
- Domain Membership
- Centralized Management

**IAM Connection**
- Device Identity
- Endpoint Security
- Conditional Access Policies

---

### Group Policies (GPOs)

Group Policy Objects allow administrators to enforce configurations and security settings across users and devices.

**Key Takeaways**
- Centralized Security Policies
- Configuration Management
- Administrative Control

**IAM Connection**
- Security Enforcement
- Compliance Controls
- Least Privilege Principles

---

### Authentication Methods

Active Directory supports multiple authentication protocols used to verify user identities.

**Key Takeaways**
- Kerberos
- NTLM
- Authentication Workflows

**IAM Connection**
- Single Sign-On (SSO)
- Identity Verification
- Authentication Security

---

### Trees, Forests, and Trusts

Trees and forests allow organizations to manage multiple domains while trusts enable access between them.

**Key Takeaways**
- Forest Structure
- Trust Relationships
- Cross-Domain Access

**IAM Connection**
- Federation
- Enterprise Identity Architecture
- Cross-Organization Access Management

---

## IAM Mapping

| Active Directory Component | IAM Concept |
|----------------------------|-------------|
| Users | Identity Lifecycle Management |
| Groups | Role-Based Access Control (RBAC) |
| Authentication | Single Sign-On (SSO) |
| Group Policy | Security Governance |
| Domain Controllers | Identity Sources |
| Forest Trusts | Federation & Trust Relationships |

---

## Skills Developed

- Active Directory Fundamentals
- Windows Domain Administration
- User Management
- Authentication Concepts
- Access Control
- Security Administration
- Identity Management Fundamentals

---

## Screenshots

### Lab Overview

_Add screenshots from the lab here._

### User Management

_Add screenshots here._

### Group Policy

_Add screenshots here._

### Authentication

_Add screenshots here._

---

## Key Takeaways

This lab reinforced the importance of Active Directory as a foundational technology in enterprise identity management. Understanding domains, authentication, users, groups, and access control provides the groundwork necessary for advancing into Identity and Access Management, Identity Governance, and Privileged Access Management roles.

---

## Future Learning

- Active Directory Administration
- PowerShell Automation
- Microsoft Entra ID
- Okta Administration
- CyberArk PAM
- SailPoint Identity Governance
- Identity Lifecycle Automation

---

## Author

**Daran Chambers Jr.**

IT Support Specialist | IAM Engineer in Development | Cybersecurity Student

GitHub: https://github.com/Kuhho
LinkedIn: www.linkedin.com/in/daran-chambers-jr
