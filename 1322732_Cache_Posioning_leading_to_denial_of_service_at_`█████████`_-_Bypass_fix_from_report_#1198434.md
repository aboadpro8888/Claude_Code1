# Cache Posioning leading to denial of service at `█████████` - Bypass fix from report #1198434	

- **Report ID:** [1322732](https://hackerone.com/reports/1322732)
- **Severity:** High
- **CWE:** Uncontrolled Resource Consumption
- **Substate:** resolved
- **Bounty:** None USD
- **Program:** deptofdefense
- **Disclosed:** 2021-10-13T22:15:38.530Z
- **Votes:** 11

## URL
https://hackerone.com/reports/1322732

## Summary
The cache server of a domain was vulnerable to cache poisoning, which allowed an attacker to store a false value and later deliver it to all users that view the domain page, leading to a denial of service. The vulnerability was not fully fixed after a previous report, and an attacker could exploit different paths to crash the domain.

## Notes
> Use this report for training your bug-hunting agent.
> Study the vulnerability type, impact, and proof-of-concept details.
