# Lab 01: Identity and Access Management (AWS Real Environment)

## Objective
Establish a secure multi-user environment and service roles for the Guanago application.

## Actions Performed
1. **MFA Implementation:** Enabled Multi-Factor Authentication for the Root and Admin accounts.
2. **Programmatic Access:** Configured AWS CLI with a dedicated IAM user (`Gabi-Dev`).
3. **Service Roles:** Created a role for EC2 with `AmazonS3FullAccess` and `AmazonRekognitionReadOnlyAccess`.

## Security Evidence
- No Root account usage for daily tasks.
- Password policy enforced (Minimum 12 characters, symbols, and numbers).