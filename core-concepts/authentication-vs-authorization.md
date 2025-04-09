# Authentication vs Authorization

In cybersecurity, **authentication** and **authorization** are two key but distinct processes. They often work together—but they’re not the same thing.

---

## Authentication

**Question Answered**: _Who are you?_

**Definition**: The process of verifying a user's identity.

### Examples:
- Entering a username and password
- Using biometric data (fingerprint, facial recognition)
- Receiving a code via SMS or authenticator app (MFA)

### Types:
- **Single-Factor Authentication (SFA)**: Password only
- **Multi-Factor Authentication (MFA)**: Password + something else (e.g., a code or fingerprint)
- **Single Sign-On (SSO)**: One login grants access to many systems

---

## Authorization

**Question Answered**: _What are you allowed to do?_

**Definition**: The process of granting access to resources or actions based on permissions.

### Examples:
- A regular user can't access the admin dashboard
- File permissions: read, write, execute
- Role-based access control (RBAC)

---

## Key Difference

| Feature | Authentication | Authorization |
|--------|----------------|----------------|
| **Purpose** | Confirms identity | Grants access rights |
| **Comes First?** | Yes | No |
| **Example** | Login with credentials | View or edit a document |
| **How?** | Passwords, MFA, biometrics | Access control lists, policies |

---

## Easy Way to Remember

> **Authentication** = Proving **you are who you say you are**  
> **Authorization** = Defining **what you're allowed to do**

---

Next: [Threat Actors & Attack Vectors](threat-actors-and-attack-vectors.md)
