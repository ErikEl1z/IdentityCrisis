# IdentityCrisis

## Overview

IdentityCrisis is a hands-on Microsoft Entra ID lab focused on Identity and Access Management (IAM), authentication security, and Zero Trust principles. This project explores how organizations can strengthen their security posture through centralized identity management, role-based access control, and multi-factor authentication.

The objective of this lab was to gain practical experience with the identity layer of cloud security while developing familiarity with the administrative and security capabilities available within Microsoft Entra ID.

---

## Objectives

- Create and manage user identities within Microsoft Entra ID
- Implement role-based access control (RBAC)
- Configure groups and access assignments
- Explore Multi-Factor Authentication (MFA)
- Apply Zero Trust security concepts
- Understand identity governance and privileged access management
- Document security best practices for cloud identity management

---

## Technologies Used

- Microsoft Azure
- Microsoft Entra ID
- Microsoft 365
- Role-Based Access Control (RBAC)
- Multi-Factor Authentication (MFA)
- Zero Trust Security Model

---

## Lab Activities

### User Administration

Created and managed user accounts to understand identity lifecycle management, account provisioning, and administrative workflows.

### Group Management

Configured security groups and assigned users based on role requirements to demonstrate scalable access management.

### Role Assignments

Evaluated built-in administrative roles and implemented least-privilege access concepts using role-based access control.

### Role Assignment Validation

Exported Microsoft Entra role assignments and reviewed them outside the administrative portal to validate role assignments and administrative privileges.

The review confirmed:

| Identity | Role |
|-----------|---------|
| Erik Elizondo | Global Administrator |
| CloudAdmin01 | User Administrator |
| SOCAnalyst01 | Security Reader |

This process simulated a basic access review and demonstrated principles of identity governance and least privilege.
### Authentication Methods & MFA

Reviewed Microsoft Entra authentication methods and MFA capabilities, including Microsoft Authenticator, passkeys, software OATH tokens, email OTP, and Temporary Access Pass. Evaluated how strong authentication controls support Zero Trust identity strategies.

### Conditional Access

Reviewed Conditional Access concepts and policy design strategies used to enforce security requirements based on user, location, device, and risk signals.

### Zero Trust Principles

Applied core Zero Trust concepts by validating identities before granting access and minimizing excessive permissions wherever possible.

### Sign-In Monitoring

Reviewed Microsoft Entra sign-in activity to gain visibility into authentication events and account usage. This activity demonstrated the relationship between identity administration and security monitoring.

---

## Key Security Concepts

### Least Privilege

Users should only receive the permissions required to perform their assigned responsibilities.

### Identity as the Security Perimeter

Modern cloud environments rely heavily on identity controls as traditional network boundaries continue to evolve.

### Defense in Depth

Identity controls work alongside endpoint, network, and monitoring solutions to create layered security protections.

### Zero Trust

Trust is never assumed. Every access request should be verified and continuously evaluated.

---

## Lessons Learned

- Identity security serves as a foundational component of modern cloud environments.
- Proper role assignment reduces unnecessary administrative exposure.
- MFA remains one of the most effective controls against account compromise.
- Zero Trust architectures rely heavily on strong identity governance.
- Microsoft Entra ID provides centralized capabilities for identity security and access management.

---

## Screenshots

### Tenant Overview

### User Administration

### Security Groups

### Role Assignments

### Role Validation Audit

### Authentication Policies

### Sign-In Monitoring

---

## Future Enhancements

- Implement dynamic group membership
- Explore Privileged Identity Management (PIM)
- Configure additional Conditional Access policies
- Integrate identity monitoring with Microsoft Sentinel
- Evaluate Identity Protection risk detections

---



