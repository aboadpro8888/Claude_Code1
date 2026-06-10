# Authentication token and CSRF token bypass

- **Report ID:** [998457](https://hackerone.com/reports/998457)
- **Severity:** High
- **CWE:** Improper Access Control - Generic
- **Substate:** resolved
- **Bounty:** 300 USD
- **Program:** enjin
- **Disclosed:** 2022-06-19T12:11:40.319Z
- **Votes:** 43

## URL
https://hackerone.com/reports/998457

## Summary
A vulnerability was discovered in the CORS rules of a system that allowed an attacker to execute certain functions on behalf of another user. This was possible due to a CSRF token bypass that was made possible by using the `GET` method to query the GraphQL interface. The issue was resolved by restricting the GraphQL interface to only accept traffic over `POST` and limiting the scope of the CORS rules.

## Notes
> Use this report for training your bug-hunting agent.
> Study the vulnerability type, impact, and proof-of-concept details.
