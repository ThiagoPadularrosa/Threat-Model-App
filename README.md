# Threat Model SecureTask

The fictional app that i come up with Is **SecureTask**, a web app to administrate tasks and users. His **objective** is
Identify threats, evaluate risks, propose mitigations and define mechanisms of detection.

## Simulated Architecture

- Frontend: Web Interface
- Backend: API REST
- Authentication: Sessions.
- Admin Panel: Management of users.
- Storage: Fictional database.
- Logs: register of security events.

**Components and Functionalities**:

| Components        |  Functionalities                  |
| :---------:       | :---------------:                 |
| User              | Register and log in of session    |
| Session           | Maintained the user authenticated |
| Admin             | Management of all the users       |
| API               | Process requests                  |
| Database          | Store Users and tasks             |
| Logging           | Register events                   |
