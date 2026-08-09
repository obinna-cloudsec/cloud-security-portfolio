# Microsoft 365 Cloud Security, Identity Protection and Information Governance Project

## Project Overview

This portfolio project demonstrates a Microsoft 365 cloud security and compliance implementation across Microsoft Entra ID, Microsoft Purview, Exchange Online, Teams, and Microsoft 365 administration. The project focuses on identity protection, privileged access, access reviews, Conditional Access, self-service password reset, sensitivity labels, label publishing, mailbox holds, information barriers, Data Loss Prevention, audit/sign-in log review, and eDiscovery readiness.

This public GitHub version is sanitized. Tenant identifiers, primary domains, organization names, user names, email addresses, UPNs, IP addresses, sign-in records, audit records, mailbox details, role request details, eDiscovery targets, and sensitive investigation details have been redacted.

## Architecture

![Microsoft 365 Cloud Security Architecture](architecture.png)

## Project Summary

| Area | Details |
|---|---|
| Project Type | Microsoft 365 cloud security, identity protection, information governance, and compliance |
| Project Level | Advanced security and compliance project |
| Environment | Microsoft 365, Microsoft Entra ID, Microsoft Purview, Exchange Online, Teams |
| Primary Role Alignment | Cloud Security Engineer, Identity and Access Engineer, Microsoft 365 Security Administrator, Purview Administrator |
| Evidence Count | 57 mapped screenshots |
| Public Version Note | Sensitive identity, tenant, policy, log, mailbox, and investigation details are redacted |

## Business Requirement

The organization required a secure Microsoft 365 environment with identity protection, privileged access controls, access governance, data protection, compliance preservation, and investigation readiness. The implementation needed to support Zero Trust-style controls, reduce identity and access risk, protect sensitive data, preserve mailbox content, and enable audit and eDiscovery review.

## Technologies Used

- Microsoft Entra ID
- Microsoft Entra Conditional Access
- Microsoft Entra Identity Protection
- Risky users, risky sign-ins, and risk detections
- User risk policy
- Sign-in risk policy
- Privileged Identity Management
- Access Reviews
- Self-Service Password Reset
- Microsoft Purview
- Sensitivity labels
- Label publishing policies
- Information Barriers
- Data Loss Prevention
- Exchange Online mailbox / litigation hold
- Audit logs and sign-in logs
- Microsoft Purview eDiscovery

## Implementation Evidence

The screenshots below use balanced redaction. Admin workflow context remains visible while sensitive tenant, user, mailbox, IP, audit, sign-in, policy, and investigation details are blocked.

## Departments Created

### Customer Service department membership evidence.

![Customer Service department membership evidence.](00a-department-customer-service.png)

### Facilities department membership evidence.

![Facilities department membership evidence.](00b-department-facilities.png)

### Sales department membership evidence.

![Sales department membership evidence.](00c-department-sales.png)

## Validation 1: Microsoft 365 License Assignment

### Active user selected for Microsoft 365 license assignment.

![Active user selected for Microsoft 365 license assignment.](01a-license-assignment-active-user.png)

### License and apps assignment screen showing service enablement.

![License and apps assignment screen showing service enablement.](01b-license-assignment-license-apps.png)

## Validation 2: Sensitivity Labels

### Sensitivity label created for Customer Support protection.

![Sensitivity label created for Customer Support protection.](02a-sensitivity-label-customer-support.png)

### Sensitivity label created for Finance protection.

![Sensitivity label created for Finance protection.](02b-sensitivity-label-finance.png)

## Validation 2: Label Publishing Policies

### Sensitivity label published to Customer Support group.

![Sensitivity label published to Customer Support group.](02c-label-publishing-customer-support.png)

### Finance group selected for label publishing policy.

![Finance group selected for label publishing policy.](02d-label-publishing-finance-step1.png)

### Finance label publishing policy review and completion evidence.

![Finance label publishing policy review and completion evidence.](02e-label-publishing-finance-step2.png)

## Validation 2: Sensitivity Label Enforcement Test

### Sensitivity label enforcement evidence showing blocked message behavior.

![Sensitivity label enforcement evidence showing blocked message behavior.](02f-label-enforcement-test.png)

## Validation 3: Mailbox Holds

### Finance mailbox selected for litigation hold configuration.

![Finance mailbox selected for litigation hold configuration.](03a-group-mailbox-hold-finance-step1.png)

### Finance mailbox litigation hold configuration evidence.

![Finance mailbox litigation hold configuration evidence.](03b-group-mailbox-hold-finance-step2.png)

### Individual mailbox selected for hold configuration.

![Individual mailbox selected for hold configuration.](03c-individual-mailbox-hold-customer-support-step1.png)

### Individual mailbox litigation hold configuration evidence.

![Individual mailbox litigation hold configuration evidence.](03d-individual-mailbox-hold-customer-support-step2.png)

## Validation 4: Privileged Identity Management

### Privileged Identity Management landing page.

![Privileged Identity Management landing page.](04a-pim-home.png)

### Eligible User Administrator role assignment configuration.

![Eligible User Administrator role assignment configuration.](04b-pim-user-admin-assignment.png)

### PIM assignment details and notification evidence.

![PIM assignment details and notification evidence.](04c-pim-user-admin-assignment-confirmation.png)

## Validation 4: PIM Role Activation Test

### Password reset failed before privileged role activation.

![Password reset failed before privileged role activation.](04d-pim-failed-reset-before-activation.png)

### Password reset succeeded after privileged role activation.

![Password reset succeeded after privileged role activation.](04e-pim-successful-reset-after-activation.png)

## Validation 5: Access Reviews

### Customer Support group access review creation/configuration.

![Customer Support group access review creation/configuration.](05a-access-review-customer-support-step1.png)

### Customer Support group access review listing/status.

![Customer Support group access review listing/status.](05b-access-review-customer-support-step2.png)

### Teams Administrator role access review creation.

![Teams Administrator role access review creation.](05c-access-review-teams-admin-step1.png)

### Teams Administrator access review list/status.

![Teams Administrator access review list/status.](05d-access-review-teams-admin-step2.png)

### Reviewer approve/deny workflow for Teams Administrator access.

![Reviewer approve/deny workflow for Teams Administrator access.](05e-access-review-approve-or-deny.png)

### Teams Administrator access request approval evidence.

![Teams Administrator access request approval evidence.](05f-access-review-approval-confirmed.png)

## Validation 6: Audit Logs

### Navigation toward Audit Logs in Microsoft Entra.

![Navigation toward Audit Logs in Microsoft Entra.](06a-audit-log-navigation-step1.png)

### Monitoring section and Audit Logs navigation.

![Monitoring section and Audit Logs navigation.](06b-audit-log-navigation-step2.png)

### Audit Logs navigation evidence.

![Audit Logs navigation evidence.](06c-audit-log-navigation-step3.png)

### Audit Logs page evidence.

![Audit Logs page evidence.](06d-audit-logs-page.png)

### Audit log activity detail review.

![Audit log activity detail review.](06e-audit-log-details.png)

## Validation 6: Sign-in Logs

### Navigation to Sign-in Logs.

![Navigation to Sign-in Logs.](06f-signin-log-navigation.png)

### Sign-in log detail review.

![Sign-in log detail review.](06g-signin-log-details.png)

## Validation 7: Self-Service Password Reset

### SSPR configuration enabled for a target group.

![SSPR configuration enabled for a target group.](07a-sspr-configuration.png)

### SSPR verification workflow step 1.

![SSPR verification workflow step 1.](07b-sspr-test-step1.png)

### SSPR verification workflow step 2.

![SSPR verification workflow step 2.](07c-sspr-test-step2.png)

### SSPR new password step after verification.

![SSPR new password step after verification.](07d-sspr-test-step3.png)

### SSPR completion confirmation.

![SSPR completion confirmation.](07e-sspr-test-completion.png)

### Audit log confirming SSPR activity.

![Audit log confirming SSPR activity.](07f-sspr-audit-log.png)

## Validation 8: Information Barriers

### Scoped directory setting enabled.

![Scoped directory setting enabled.](08a-scoped-directory-enabled.png)

### Finance segment created for information barrier policy.

![Finance segment created for information barrier policy.](08b-finance-segment.png)

### Internal Audit segment created for information barrier policy.

![Internal Audit segment created for information barrier policy.](08c-internal-audit-segment.png)

### Information Barrier block policy between configured segments.

![Information Barrier block policy between configured segments.](08d-information-barrier-block-policy.png)

## Validation 9: Conditional Access

### Trusted named location configured for Conditional Access.

![Trusted named location configured for Conditional Access.](09a-trusted-location.png)

### Conditional Access policy protecting admin access.

![Conditional Access policy protecting admin access.](09b-conditional-access-policy.png)

## Validation 10: Identity Protection Monitoring

### Risky Users page in Microsoft Entra Identity Protection.

![Risky Users page in Microsoft Entra Identity Protection.](10a-identity-protection-risky-users.png)

### Risky Sign-ins page in Microsoft Entra Identity Protection.

![Risky Sign-ins page in Microsoft Entra Identity Protection.](10b-identity-protection-risky-signins.png)

### Risk detections page in Microsoft Entra Identity Protection.

![Risk detections page in Microsoft Entra Identity Protection.](10c-identity-protection-risk-detections.png)

## Validation 11: User Risk Policy

### User risk policy configured to require password change.

![User risk policy configured to require password change.](11a-user-risk-policy.png)

## Validation 12: Sign-in Risk Policy

### Sign-in risk policy configured to require MFA.

![Sign-in risk policy configured to require MFA.](12a-signin-risk-policy.png)

## Validation 13: Data Loss Prevention

### DLP policy creation step 1.

![DLP policy creation step 1.](13a-dlp-policy-step1.png)

### DLP policy rule configuration step.

![DLP policy rule configuration step.](13b-dlp-policy-step2.png)

### DLP policy review and completion step.

![DLP policy review and completion step.](13c-dlp-policy-step3.png)

### DLP policy completion evidence.

![DLP policy completion evidence.](13d-dlp-policy-complete.png)

## Validation 14: eDiscovery

### eDiscovery case created.

![eDiscovery case created.](14a-ediscovery-case.png)

### eDiscovery source selection including mailbox and Teams sources.

![eDiscovery source selection including mailbox and Teams sources.](14b-ediscovery-user-source.png)

### Search created within the eDiscovery case.

![Search created within the eDiscovery case.](14c-ediscovery-searches.png)

## Validation Results

| Validation Area | Result |
|---|---|
| Departments and security groups | Successful |
| Microsoft 365 license assignment | Successful |
| Sensitivity labels and publishing policies | Successful |
| Mailbox holds / litigation hold | Successful |
| Privileged Identity Management | Successful |
| Access Reviews | Successful |
| Audit and sign-in log review | Successful |
| Self-Service Password Reset | Successful |
| Information Barriers | Successful |
| Conditional Access | Successful |
| Identity Protection monitoring | Successful |
| User risk policy | Successful |
| Sign-in risk policy | Successful |
| Data Loss Prevention | Successful |
| eDiscovery | Successful |

## Key Skills Demonstrated

- Microsoft 365 cloud security implementation
- Microsoft Entra ID identity protection
- Conditional Access policy design
- Privileged Identity Management
- Access Reviews and identity governance
- Microsoft Purview Information Protection
- Microsoft Purview Data Loss Prevention
- Information Barriers
- Mailbox hold / litigation hold
- Audit log and sign-in log review
- eDiscovery case and search creation
- Security documentation and evidence handling

## Security and Confidentiality Notice

This public version has been sanitized. The following information must not be visible in any public screenshot:

- Tenant ID
- Primary domain
- Tenant or organization display name
- User names and display names
- User principal names and email addresses
- IP addresses
- Audit log user records
- Sign-in log user records
- Session IDs or diagnostic IDs
- eDiscovery targets and search details
- Sensitive policy names
- Sensitive group names
- Dates and timestamps where they identify private activity
- Profile or account panels

## Project Outcome

The Microsoft 365 environment was strengthened through layered identity, privileged access, data protection, compliance, and investigation controls. The project demonstrates practical Cloud Security Engineer-level work across Microsoft Entra ID and Microsoft Purview.

## Conclusion

This project is the flagship Microsoft 365 cloud security project in the portfolio because it brings together identity protection, privileged access governance, information protection, DLP, compliance preservation, audit review, and eDiscovery readiness in one implementation.
