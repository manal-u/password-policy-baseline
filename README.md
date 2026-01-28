# Password Policy Baseline (Windows Security – Sign-in Password Review)

## Executive Summary
This project documents a baseline review of password-related settings on a Windows system using Windows Security. The goal is to verify credential hygiene controls by reviewing sign-in options and password requirements as presented by the operating system. Evidence is captured as screenshots and stored in `/proof`.

## Objectives
- Access Windows Security to review password-related configuration areas
- Review Account protection and Sign-in options
- Validate password settings visibility and document results with proof screenshots

## Environment
- OS: Windows 10 / Windows 11
- Tools: Windows Security (built-in)
- Account Type: Local User Account (standard desktop environment)

## Implementation (Step-by-Step)
1. Opened the **Start** menu, searched for **Windows Security**, and launched the application to access security settings.  
   *(Evidence: `/proof/01-windows-security-home.png`)*

2. Navigated to **Account protection** and opened **Sign-in options** to review authentication controls relevant to password security.  
   *(Evidence: `/proof/02-sign-in-options.png`)*

3. Opened the **Password** section and reviewed password-related requirements and sign-in behavior enforced by the system (including password rules and sign-in requirements).  
   *(Evidence: `/proof/03-password-settings.png`)*

## Proof of Work
Evidence screenshots are stored in `/proof`:
- `/proof/01-windows-security-home.png`
- `/proof/02-sign-in-options.png`
- `/proof/03-password-settings.png`

## Diagnostics & Corrective Learning
- No blocking errors were encountered during verification.
- If access to a setting is unavailable (e.g., due to account type or organization policy), the limitation is documented with a screenshot and the observed reason (when visible).

## Lessons Learned
- Windows Security provides a centralized interface for reviewing account protection and sign-in controls.
- Documenting visible password/security requirements creates verifiable evidence of security posture.
- Clear evidence naming and step-by-step reporting improves repeatability for audits and handoffs.

## References
- Microsoft Documentation: Windows Security and Account Protection settings

