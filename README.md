# Azure-Resource-Manager-Security-Hardening
Assessed and secured Azure resources by cleaning up RBAC, assigning managed identities, and implementing security policies. Demonstrates junior-level cloud security skills.

This mini project demonstrates Azure resource security assessment and hardening using a demo subscription. The focus was on identifying misconfigured access permissions and improving the overall security posture of the resources.

The screenshot below shows the initial Resource Manager view before applying any security changes.


Resource Manager overview before RBAC hardening.
Problem Statement

While reviewing the Azure environment, I noticed:

Multiple resources with overly permissive roles.

Lack of least privilege enforcement for users and service principals.

No assigned managed identities on VMs for secure authentication.

These issues could lead to unauthorized access, data exposure, or accidental misconfiguration if not addressed.
Actions Taken

To improve the security posture, I applied the following measures:

RBAC Cleanup:

Removed unnecessary Owner and Contributor roles.

Applied the principle of least privilege using built-in roles.

User-Assigned Managed Identity (UAMI):

Assigned UAMI to critical VMs to allow secure resource access without storing credentials.

Resource Policies & Monitoring:

Enabled Azure policies to restrict public access to storage accounts and databases.

Set up alerts for high-risk configuration changes.

Security Recommendations Implementation:

Followed Security Center suggestions for identity and network hardening.
utcome

Hardened access control across all resources.

Improved security posture and reduced exposure risk.

Demonstrated ability to assess, plan, and implement Azure security best practices in a real-world scenario.

Skills Highlighted:

Azure RBAC, Resource Manager, Security Center

Identity hardening with UAMI

Resource-level access control and monitoring
