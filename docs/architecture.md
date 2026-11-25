# Architecture and Components of SecureTask

Here In this document where we can see how it's structure the app and his principal components with the important assets that needs the most security focused.

## Architecture

- Frontend: Web Interface
- Backend: API REST
- Authentication: Sessions.
- Admin Panel: Management of users.
- Storage: Fictional database.
- Logs: register of security events.

## Components And Assets

**Components and Functionalities**:

| Components        |  Functionalities                           |
| :---------:       | :---------------:                          |
| User              | Register and log in of session             |
| Session           | Maintained the user authenticated          |
| Admin             | Management of all the users                |
| API               | Process requests                           |
| Database          | Store Users and tasks                      |
| Logging           | Register security events                   |

**Assets that we want to protect:**

- Credentials of the user
- User data
- Financial Data
- Business/Intelectual Data
- Server logic
- API availability
- Identifiers of sessions
