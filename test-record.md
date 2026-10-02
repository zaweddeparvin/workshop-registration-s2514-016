# Workshop Registration Lab — Test Record

Student: Zawedde Parvin Peace
Student Number: S25D14/016

| Test | Expected Result | Result |
|---|---|---|
| Empty required fields | Blocked with feedback; no success message | PASS |
| Email: amina | Invalid value blocked | PASS |
| Telephone: 123 | Invalid value blocked | PASS |
| Telephone: +256700123456 | Accepted | PASS |
| Portfolio blank | Accepted | PASS |
| Portfolio: https://example.com | Accepted | PASS |
| Portfolio: not-a-url | Blocked | PASS |
| Yesterday | Blocked | PASS |
| Today/future date | Accepted | PASS |
| Seats: 0 | Blocked | PASS |
| Seats: 5 | Blocked | PASS |
| Seats: 1.5 | Blocked | PASS |
| Seats: 1 | Individual booking | PASS |
| Seats: 4 | Group booking | PASS |
| Short password | Blocked | PASS |
| Mismatched confirmation | Blocked | PASS |
| Agreement unchecked | Blocked | PASS |
| All fields valid | Green preview; password never shown | PASS |
| 390px-wide view | No sideways scrolling | PASS |
| Tab navigation | Visible keyboard focus | PASS |
