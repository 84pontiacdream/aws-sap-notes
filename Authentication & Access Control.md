# Authentication & Access Control

## IAM Identities & Policies

IAM Users: given permissions by directly assigned IAM policies or being assigned to an IAM user group.  

IAM Roles: used to provide temporary credentials to entities (individuals, AWS services or applications)  

IAM user or role **<span style="color:indianred">cannot span multiple AWS accounts</span>**


IAM Policy: an object assigned to IAM identities / an AWS resource allowing access control.  

Policy Types:
* identity-based policies
* resource-based policies
* permissions boundaries
* organizations service control policies (SCPs)
* access control lists (ACLs)
* session policies.

Identity based: 
* JSON policy documents
* attached to IAM identities
* managed / inline policies

IAM Policies

<span style="color:lightblue">Identity Based policies</span> 

Leveraging Access Delegation

Security  
* Security of iam users can be enhanced by enabling MFA