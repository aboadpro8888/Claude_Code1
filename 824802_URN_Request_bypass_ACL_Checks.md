# URN Request bypass ACL Checks

- **Report ID:** [824802](https://hackerone.com/reports/824802)
- **Severity:** Critical
- **CWE:** Improper Access Control - Generic
- **Substate:** resolved
- **Bounty:** None USD
- **Program:** ibb
- **Disclosed:** 2021-08-26T23:32:28.453Z
- **Votes:** 23

## URL
https://hackerone.com/reports/824802

## Summary
A vulnerability was discovered in Squid versions up to 4.8 that allowed an attacker to bypass all ACLs using an URN request, which could then be transformed into an HTTP request, giving the attacker access to restricted resources. The vulnerability was due to the URN request not going through the same ACL checks as incoming HTTP requests. The attacker was limited in what they could view from these requests, as only lines containing ":" were readable and the response had to be less than 4096 bytes. The vulnerability was fixed in Squid version 4.9.

## Notes
> Use this report for training your bug-hunting agent.
> Study the vulnerability type, impact, and proof-of-concept details.
