# Registration bypass with leaked Invite Token

- **Report ID:** [1071102](https://hackerone.com/reports/1071102)
- **Severity:** High
- **CWE:** Improper Authentication - Generic
- **Substate:** resolved
- **Bounty:** None USD
- **Program:** rocket_chat
- **Disclosed:** 2024-08-10T21:58:46.526Z
- **Votes:** 29

## URL
https://hackerone.com/reports/1071102

## Summary
The Rocket.Chat API route 'validateInviteToken' was vulnerable to a registration bypass attack. The route allowed unauthenticated users to guess valid invite tokens by sending a crafted JSON payload with a regular expression. Once a valid token was obtained, the user could access private channels or register a new account on the server. The vulnerability was present in version 3.9.4 of Rocket.Chat.

## Notes
> Use this report for training your bug-hunting agent.
> Study the vulnerability type, impact, and proof-of-concept details.
