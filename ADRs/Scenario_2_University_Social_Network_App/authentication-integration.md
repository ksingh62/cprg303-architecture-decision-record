# Architecture Decision Record: Authentication Integration

## Status

Accepted

## Context

Secure authentication is critical for protecting user data and ensuring that only authorized users can access their accounts. The app must support secure logins for students and professors.

## Decision

We will integrate OAuth 2.0 for authentication, leveraging the existing university Active Directory for secure and streamlined login processes. This approach supports social logins and institutional credentials, offering flexibility and security.

## Consequences

- **Pros:**
  - Enhanced security by using a proven authentication standard.
  - Simplified login process for users, improving user experience.
  - Supports future expansion for additional authentication methods.
  
- **Cons:**
  - Requires understanding and implementation of OAuth 2.0 protocols and secure token handling.
  - Dependency on the university's Active Directory infrastructure for authentication.
