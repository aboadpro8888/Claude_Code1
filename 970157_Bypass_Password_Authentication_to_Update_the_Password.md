# Bypass Password Authentication to Update the Password

- **Report ID:** [970157](https://hackerone.com/reports/970157)
- **Severity:** High
- **CWE:** Improper Authentication - Generic
- **Substate:** resolved
- **Bounty:** None USD
- **Program:** x
- **Disclosed:** 2021-01-11T18:42:17.336Z
- **Votes:** 58

## URL
https://hackerone.com/reports/970157

## Summary
A security vulnerability was discovered in Twitter that allowed hackers to bypass the old password screen and update a victim's password by using unrestricted rate limiting or password brute-forcing. This could lead to a complete takeover of the victim's account. The vulnerability was resolved by implementing rate limitation.

## Notes
> Use this report for training your bug-hunting agent.
> Study the vulnerability type, impact, and proof-of-concept details.
