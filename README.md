# Lab 08 – Multi-Factor Authentication (Conditional Access + Per-User)

## About

This lab covers three ways MFA gets enforced in Entra ID: reviewing tenant-wide MFA/authentication method settings, building a targeted Conditional Access policy that requires MFA for a specific user against a specific resource (Office 365), and enabling legacy per-user MFA directly on a user account — then testing sign-in behavior for both.

MFA enforcement design is a constant in Ardalyst's compliance work, especially for CMMC Level 2 clients where MFA isn't optional and the *method* of enforcement matters as much as whether it's on. Per-user MFA is the legacy model I still find lingering in some client tenants during audits — it's rigid, applies everywhere with no conditional logic, and is the first thing I flag for migration to Conditional Access-based enforcement, which lets us scope MFA by resource, network, risk level, or user group instead of an all-or-nothing switch. This lab is a clean side-by-side of exactly that gap, and it's the same policy-building muscle behind the risk-based Conditional Access framework I've been building out in my own hybrid lab.

**Covered in this lab:**
- Reviewing tenant-wide MFA authentication methods
- Building a Conditional Access policy scoped to a specific user and target resource, requiring MFA
<img width="1014" height="671" alt="image" src="https://github.com/user-attachments/assets/061abdcd-4e00-4878-aff4-ab00f929730d" />

- Verifying MFA registration and enforcement on sign-in
- <img width="1018" height="645" alt="image" src="https://github.com/user-attachments/assets/0141c79b-0ff1-44ec-85f4-7ccbf00097e4" />

- Enabling legacy per-user MFA and comparing it against the Conditional Access approach
<img width="1027" height="650" alt="image" src="https://github.com/user-attachments/assets/42d7a128-23ba-41e5-a487-4f3c91239382" />


## Video Walkthrough

📹 https://youtu.be/QOrOv3xESuw
