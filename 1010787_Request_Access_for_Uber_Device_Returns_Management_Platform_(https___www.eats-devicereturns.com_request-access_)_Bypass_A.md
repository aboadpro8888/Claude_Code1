# Request Access for Uber Device Returns Management Platform (https://www.eats-devicereturns.com/request-access/) Bypass Allows Access to PII

- **Report ID:** [1010787](https://hackerone.com/reports/1010787)
- **Severity:** High
- **CWE:** Privilege Escalation
- **Substate:** resolved
- **Bounty:** None USD
- **Program:** uber
- **Disclosed:** 2021-05-14T17:24:53.061Z
- **Votes:** 13

## URL
https://hackerone.com/reports/1010787

## Summary
A vulnerability was found in the Uber Device Returns Management Platform registration page, which allowed unauthorized access to personally identifiable information (PII). The authentication was not integrated with Uber's central authentication, and a similar domain name could be registered to bypass the email domain restriction. Flat access control allowed access to site content and control of the entire platform.

## Notes
> Use this report for training your bug-hunting agent.
> Study the vulnerability type, impact, and proof-of-concept details.
