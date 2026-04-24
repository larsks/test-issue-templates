# Access Requests
Tracks issues for access requests to the environment that cannot be completed with other tools

# Kinds of Requests
1. Privileged access to the bastion server (ssh login plus sudo). Only granted to technical maintainers of the environment.

# Process to request privileged access to the bastion server
Three parties are involved in this request - the person requesting access, an approver, and an administrator who can grant access.

## Process for individuals requesting access

### Prerequisites:
* You will need to be able to SSH into the bastion. This means you need a local SSH client. For windows, you can use Putty, GitBash or an equivalent. Mac and Linux distributions generally have this built in.

### Instructions
1. [Create a GitHub issue](https://github.com/CCI-MOC/access-requests/issues) in this repository for each user that needs access.

  **Include these items in the issue description:**
  * Desired username
  * Justification for access
  * A phone number for the access administrator to reach you and provide your temporary sudo password. At this time, Slack and Email are not approved mediums to transmit temporary passwords for this environment.
  * A public SSH key to use to log in to the bation (do not share your private key!). This should use a supported cypher. At the time of writing, id-rsa is supported. ssh-ed25519 is not. Make sure to protect your private key with a passphrase.
3. Someone who is able to approve the request will be notified.
4. They will comment on the ticket granting their approval.
5. An access administrator be notified.
6. They will grant access and reach out with next steps (test login, change your password, etc.).

## Process for approvers
1. Watch this repository.
2. Comment with your approval when issues are created.

## Process for access administrators
1. Watch this repository.
2. Grant access when an approver comments stating that the request is performed. Use [these instructions](https://github.com/CCI-MOC/ai-ivp/blob/main/docs/README_BASTION_ADMINS.md).
