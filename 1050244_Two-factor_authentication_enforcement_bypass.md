# Two-factor authentication enforcement bypass

- **Report ID:** [1050244](https://hackerone.com/reports/1050244)
- **Severity:** High
- **CWE:** None
- **Substate:** resolved
- **Bounty:** 750 USD
- **Program:** nextcloud
- **Disclosed:** 2021-07-31T14:05:14.810Z
- **Votes:** 61

## URL
https://hackerone.com/reports/1050244

## Summary
Two-factor authentication enforcement in Nextcloud was bypassed, allowing attackers to gain access to user dashboards. An attacker with administrator access could create a new user and add them to a group with two-factor authentication enforcement. The attacker could then log in as the new user and bypass the two-factor authentication enforcement by replacing the oc_sessionPassphrase token with the first oc_sessionPassphrase session.

## Notes
> Use this report for training your bug-hunting agent.
> Study the vulnerability type, impact, and proof-of-concept details.
