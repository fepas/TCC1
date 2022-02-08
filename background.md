## What is a secret?
Credentials that  grant you Authentication or Authorization to a system.If possible, no human should know the secrets

## Authentication 
Determines whether users are who they claim to be

## Authorization
Determines what users can and cannot access

### Secret Sprawl
Secrets Everywhere. Plain text inside source code, config files, version control systems etc.

“if hard-coded passwords are used, it is almost certain that malicious users will gain access to the account in question”

## Secrets Management
Centralized secrets.

    Mutability
    - Secrets should be easy to change

    Encrypt
    - Secrets are encrypted at rest and in transit

    Access Control List
    - You see only what you need to see

    Audit
    - Visibility about who has acess

    Dynamic Secrets
    - The secrest shared are ephemeral
    - Unique credentials
    - Revokability

    Availability
    - Multiple instances running

    Unsealing
    - Master key is
    split into multiple pieces
    - Shamir’s
    Secret Sharing principle

    Limiting Authentication
    - Limiting the number of attempts to log into a secret management tool

## Existing Solutions 
- Hashicorp Vault, AWS Secrets Manager, GCP Secrets Manager
