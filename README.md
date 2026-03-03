# Obwob Bug Bounty

Obwob is a real-time anonymous feedback platform that enables facilitators ("Leads") to run structured feedback rounds with participants ("Voices") via QR codes or join codes.

## The Brief

Find bugs, usability issues, unexpected behaviour and security vulnerabilities in the Obwob MVP between **Tuesday 3 March 2026** and **11:59pm Monday 9 March 2026**.

## Reward

3 awards of **£50 Amazon vouchers** each, for:
- Most unique bugs found
- Most difficult to track down
- Best bug report — judged on clarity, reproducibility, and the significance of the bug found.

Will be announced in class on **10 March 2026**

## Access

Platform URL: **staging.obwob.app/login**

You'll receive an access code separately to create your Lead account. Do not share your access code or credentials outside the group. 

Voices do not need accounts - they join Rounds anonymously when a Lead shares the QR/join code with them. **Please note that the join code directs Voices to 'obwob.app' - for the purposes of testing, Voices should join at 'staging.obwob.app'.**

## In Scope

- **Lead flow:** account creation, login, creating and managing rounds, adding questions, sharing rounds
- **Voice flow:** joining a round via QR code or join code, submitting feedback anonymously
- **Mobile and responsive behaviour:** please test on your phone as well as desktop
- **Accessibility:** keyboard navigation, screen reader behaviour, colour contrast
- **Authorisation**: once logged in, try to access rounds, questions, and responses belonging to other Lead accounts by manipulating URLs or request parameters. **Do not** exfiltrate, store or share any data you access.

## Out of Scope

- Authentication - the login, registration and password reset flow. This will be handled by a third-party provider so is out-of-scope for this exercise
- Infrastructure and hosting
- Attempting to access the underlying infrastructure, database or server directly
- Load or performance testing

## How to Submit a Bug

Use GitHub Issues in this repository. Click **New Issue** and the form will guide you through what to include.

**Please do not open a public issue for security vulnerabilities.** If you find something that could compromise user data or platform security, email **Laura Gates at BSU email** directly instead.

## Tips

- Try to break things — use unexpected inputs, skip steps, go back when you shouldn't
- Test the full round lifecycle: create a round as a Lead, then join it as a Voice from your phone
- If something feels confusing or unintuitive, report it — usability issues are as valuable as bugs
- Duplicate reports happen; check open issues before submitting

## Questions

Contact **Laura Gates at BSU email** or raise a discussion in this repo.
