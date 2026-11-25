# SecureTask Diagram

![Threat Model App](SecureTask%20Threat%20Model.png)

## Interpretation

**How to interpretate the diagram:**

- The users and administrator are external entities
- The frontend receives information from the user
- The backend process the requests sent to him and apply authentication and authorization
- The administrator have more available permissions
- The database manages all user data changes and session verification
- The backend sends external notifications to a simulated version of a external notification service (such as email, push, SMS, etc.) creating a communication between them.
- The trust boundaries separates components with different levels of trust.
