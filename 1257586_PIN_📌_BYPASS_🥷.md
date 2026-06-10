# PIN 📌 BYPASS 🥷

- **Report ID:** [1257586](https://hackerone.com/reports/1257586)
- **Severity:** High
- **CWE:** Improper Authentication - Generic
- **Substate:** resolved
- **Bounty:** None USD
- **Program:** yoti
- **Disclosed:** 2022-03-18T22:25:25.806Z
- **Votes:** 83

## URL
https://hackerone.com/reports/1257586

## Summary
The PIN bypass vulnerability was discovered in the iOS application, where the rate limiting mechanism for PIN attempts could be circumvented by manipulating the device's local date/time settings. The application implemented a 5-minute lockout period after 5-6 failed PIN attempts, but this security control relied on the device's local time settings rather than server-side validation. By altering the device's date/time settings, the lockout period could be bypassed, allowing for unlimited PIN attempts.

## Notes
> Use this report for training your bug-hunting agent.
> Study the vulnerability type, impact, and proof-of-concept details.
