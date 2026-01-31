# Identity and Access Management (IAM) Lab

## Objective
Implement identity and access management controls using the principle of least privilege.

## Environment
- Windows 10/11 Virtual Machine
- Local user accounts and security groups

## Users and Groups Created
- sec_admin (Administrator)
- employee1 (Standard User)
- IT_Security (Security Group)

## Policies Configured
- Password complexity enabled
- Minimum password length: 10 characters
- Maximum password age: 90 days
- Account lockout after 5 failed login attempts

## Access Controls Implemented
- Created a sensitive folder (C:\SensitiveData)
- Full control granted to security administrators
- Access denied for standard users

## Testing and Validation
- Verified account lockout after multiple failed login attempts
- Confirmed standard user cannot access sensitive folder
- Administrative user maintained full access

## Security Principles Applied
- Least Privilege
- Role-Based Access Control (RBAC)
- Authentication and Authorization

## What I Learned
- How IAM controls reduce unauthorized access
- Importance of enforcing password and lockout policies
- How to validate access controls in a real environment
