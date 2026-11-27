<!-- markdownlint-disable MD033-->
# STRIDE Threat Modeling: SecureTask

Analyzing each element of the app using the famous methodology **STRIDE** and where of the six threats apply. Each one will have their own mitigation and rank depending on their own risk.

## Table with Threats and Mitigations

| Element | Threat | STRIDE | Mitigation |
| :--- | :--- | :--- | :--- |
| User of web app | Session token stolen<br />and replayed | S | HttpOnly, Secure<br/>cookies; MFA for<br/>sensitive actions |
| Administrator | Session token stolen<br />or credential phishing | S | Hardware MFA (FIDO2) &<br /> Privileged Access<br /> Workstations (PAWs) |
| API | User changes invoice<br />ID to read another<br />account's invoice | I, E | Object-level<br />authorization on every<br />lookup |
| API | User negates an<br />administrative<br />action | R | Least privilege,<br />Role-Based Access<br />Control (RBAC) |
| API | Normal user calls<br />admin endpoints | E | Server-side role<br />check; deny by<br />default |
| API | Normal User obtain<br />admin privileges | E | Server-side role<br />checks, Least<br />privilege |
| API | Excessive requests<br />to the API | D | Rate limits and job<br />quotas |
| API to Database | SQL injection<br />through search<br />parameter | T, I | Parameterised<br />queries |
| API to Notification service | API Key leaked<br />from repository | S, I | Secret manager;<br /> secret scanning |
