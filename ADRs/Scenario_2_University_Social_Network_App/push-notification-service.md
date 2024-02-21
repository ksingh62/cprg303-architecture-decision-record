# Architecture Decision Record: Push Notification Service

## Status

Accepted

## Context

To keep students and professors informed of new announcements, assignments, grades, and other updates, a reliable push notification service is essential.

## Decision

Firebase Cloud Messaging (FCM) will be used to implement the push notification service due to its robustness, cross-platform support, and no cost for basic usage.

## Consequences

- **Pros:**
  - Real-time notifications to keep users engaged and informed.
  - Cross-platform support ensures that notifications reach users on both iOS and Android devices.
  
- **Cons:**
  - Managing notification preferences and opt-out options is necessary to respect user choices and avoid overwhelming them.
  - Dependence on an external service (Firebase) for critical functionality.
