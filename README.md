# Access Requests
Tracks issues for access requests to the environment that cannot be completed with other tools

# Kinds of Requests
1. Privileted access to the bastion server (ssh login plus sudo). Only granted to technical maintainers of the environment.

# Process to request privileged access to the bastion server

Three parties are involved in this request - the person requesting access, an approver, and an administrator who can grant access.

## Process for people requesting access
1. [Create a GitHub issue](https://github.com/CCI-MOC/access-requests/issues) in this repository for each user that needs access. Include out of band contact information and a justification.
2. Someone who is able to approve the request will be notified.
3. They will comment on the ticket granting their approval.
4. An access administrator be notified.
6. They will grant access and reach out with next steps (test login, change your password, etc.).

## Process for approvers
1. Watch this repository.
2. Comment with your approval when issues are created.

## Process for access administrators
1. Watch this repository.
2. Grant access when an approver comments stating that the request is performed. Use [these instructions](https://github.com/CCI-MOC/ai-ivp/blob/main/docs/README_BASTION_ADMINS.md).
