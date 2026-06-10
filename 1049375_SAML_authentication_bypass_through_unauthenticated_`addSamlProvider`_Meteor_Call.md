# SAML authentication bypass through unauthenticated `addSamlProvider` Meteor Call

- **Report ID:** [1049375](https://hackerone.com/reports/1049375)
- **Severity:** Critical
- **CWE:** Improper Access Control - Generic
- **Substate:** resolved
- **Bounty:** None USD
- **Program:** rocket_chat
- **Disclosed:** 2021-01-08T15:43:08.658Z
- **Votes:** 5

## URL
https://hackerone.com/reports/1049375

## Summary
An unauthenticated attacker could bypass SAML authentication on a Rocket.Chat instance by exploiting an unauthenticated Meteor method called `addSamlProvider`. This method allowed disabling SAML signature verification, which could enable an attacker to log in as an arbitrary user with administrative privileges. The vulnerability affected all versions of Rocket.Chat that supported SAML authentication using a provider named `Default`.

## Notes
> Use this report for training your bug-hunting agent.
> Study the vulnerability type, impact, and proof-of-concept details.
