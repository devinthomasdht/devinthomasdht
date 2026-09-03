# Devin Thomas | IAM Engineer

I build like the identity systems I'm securing actually matter, because in production, they do. Every project below covers a real IAM discipline end to end, from the actual business problem through a working, tested result, with the errors I hit along the way documented instead of edited out.

Most portfolios show you the clean final screenshot. Mine shows the broken config, the wrong assumption, and the fix, because that's what real engineering looks like, and it's the difference between someone who followed a tutorial and someone who can actually troubleshoot a production identity platform.

## What I'm working with

Okta, SailPoint IdentityIQ, Microsoft Entra ID, PowerShell, Python, MS Graph API, REST APIs, SAML 2.0, OAuth 2.0, OIDC, SCIM

## Featured projects

**[SailPoint IdentityIQ, Authoritative Source Configuration](https://github.com/devinthomasdht/sailpoint-identityiq-hr-source-aggregation)**
Configured a CSV based HR source as an authoritative identity source in SailPoint IdentityIQ, built a 13 attribute schema, and ran a full account aggregation. Includes real troubleshooting, a hidden file extension, a delimiter field, and a missing identity attribute, each traced back to its actual cause.

**[Okta SSO and Lifecycle Management](https://github.com/devinthomasdht/okta-sso-lcm)**
Connected three applications to Okta using three different integration methods, SAML 2.0, OIDC, and SCIM, with department based group rules automating provisioning. Captured a live SCIM POST at webhook.site to prove the pipeline actually fires, not just that it's configured to.

**[Microsoft Entra ID Conditional Access Framework](https://github.com/devinthomasdht/iam-conditional-access-framework)**
Built a 5 policy Conditional Access framework enforcing Zero Trust principles, MFA, compliant device requirements, risk based blocking, and named location restriction, tested in Report only mode before going live. Implemented break glass account monitoring and PIM just in time access for privileged roles.

**[IAM RBAC and Access Governance](https://github.com/devinthomasdht/IAM-RBAC-Access-Governance)**
Designed an enterprise RBAC model with 10 IT and 10 Business Roles with inheritance, built and tested 3 active SoD policies, and ran a full access certification campaign, catching and remediating a live SoD violation and generating audit ready evidence.

**[IAM Metrics Dashboard](https://github.com/devinthomasdht/iam-metrics-dashboard)**
A live Python and Streamlit dashboard integrating Microsoft Entra ID and Okta through their native APIs, calculating 6 identity risk indicators in real time, dormant accounts, orphaned accounts, and MFA adoption among them.

**[IAM Automation Scripts](https://github.com/devinthomasdht/iam-automation-portfolio)**
Three PowerShell scripts automating bulk user provisioning, inactive account detection, and group membership auditing, including a real provisioning gap the audit uncovered, ten new hires with working logins and zero actual access.

## Why this is different

Most people learning IAM stop at one platform. This portfolio spans identity governance, SSO, Zero Trust enforcement, and automation, because that's the actual shape of the job, and every project here was built, broken, and fixed by hand before it was documented. If you're evaluating me for an IAM engineering role, this is the realest signal I can give you of how I actually work.
