# Cache Manager ACL Bypass

- **Report ID:** [824203](https://hackerone.com/reports/824203)
- **Severity:** Critical
- **CWE:** Authentication Bypass Using an Alternate Path or Channel
- **Substate:** resolved
- **Bounty:** None USD
- **Program:** ibb
- **Disclosed:** 2021-08-26T23:28:49.164Z
- **Votes:** 22

## URL
https://hackerone.com/reports/824203

## Summary
A vulnerability in Squid Cache Manager ACL allowed non-authorized users to access the cache manager, bypassing restrictions. This flaw could allow attackers to gain information on Squid clients, requests being made, usernames, peer servers, servers being reversed proxied, in-memory objects, and addresses of objects which can be used to break ASLR. The vulnerability was silently fixed in Squid 4.8.

## Notes
> Use this report for training your bug-hunting agent.
> Study the vulnerability type, impact, and proof-of-concept details.
