# Virtual Data Room / Hide download on collabora is easy to bypass

- **Report ID:** [1194606](https://hackerone.com/reports/1194606)
- **Severity:** High
- **CWE:** Improper Access Control - Generic
- **Substate:** resolved
- **Bounty:** 150 USD
- **Program:** nextcloud
- **Disclosed:** 2021-08-07T14:28:34.326Z
- **Votes:** 14

## URL
https://hackerone.com/reports/1194606

## Summary
A vulnerability was discovered in Nextcloud's Virtual Data Room feature, which allows users to view and modify documents in a watermark-protected way while disabling downloads and other apps using File Access Control. An attacker could bypass the hide download feature by intercepting the WOPI endpoint and access token, allowing them to download the unwatermarked file. This vulnerability makes the Virtual Data Room feature inherently broken and the claims made on the Nextcloud website misleading.

## Notes
> Use this report for training your bug-hunting agent.
> Study the vulnerability type, impact, and proof-of-concept details.
