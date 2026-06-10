# Bypass the fix of report #1078283 due to poor validation

- **Report ID:** [1212337](https://hackerone.com/reports/1212337)
- **Severity:** High
- **CWE:** Open Redirect
- **Substate:** resolved
- **Bounty:** None USD
- **Program:** khanacademy
- **Disclosed:** 2021-07-08T19:25:27.515Z
- **Votes:** 13

## URL
https://hackerone.com/reports/1212337

## Summary
The URL validation implemented by Khan Academy on the endpoint "continue" did not have any boundary checking to ignore domains starting with ".org". An attacker could register a domain starting with "org" and have a subdomain entry of "khanacademy" to bypass the validation and lead the victim to their controlled page. This vulnerability allowed an attacker to send a phishing campaign and redirect the request to a server of their control.

## Notes
> Use this report for training your bug-hunting agent.
> Study the vulnerability type, impact, and proof-of-concept details.
