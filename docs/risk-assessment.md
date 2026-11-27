<!-- markdownlint-disable MD033-->
# Risk Assessment Matrix

Here Is the table that works as a visual tool that let us see the probability of a cyber attack or incident with the impact on the web app to prioritize which threats needs the most attention.

## Table

| Threat | STRIDE | Impact | Probability |
| :--- | :--- | :--- | :--- |
| Session token stolen<br />and replayed | S | High | Medium |
| Session token stolen<br />or credential phishing | S | High | High |
| User changes invoice<br />ID to read another<br />account's invoice | I, E | High | High |
| User negates an<br />administrative<br />action | R | High | Medium |
| Normal user calls<br />admin endpoints | E | Medium | High |
| Normal User obtain<br />admin privileges | E | High | Low |
| Excessive requests<br />to the API | D | High | Medium |
| SQL injection<br />through search<br />parameter | T, I | High | Medium |
| API Key leaked<br />from repository | S, I | Medium | High |
