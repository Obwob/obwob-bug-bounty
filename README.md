# Obwob Bug Bounty

Thanks for helping us make Obwob better. Obwob is a real-time anonymous feedback platform that enables facilitators ("Leads") to run structured feedback rounds with participants ("Voices") via QR codes or join codes.

## Your Mission

Find bugs, usability issues and unexpected behaviour in the Obwob MVP during the week of **3 March 2026** to **11:59pm 9 March 2026**.

## Reward

[TO BE ADDED]

Will be announced in class on **10 March 2026**

## Access

Platform URL: **staging.obwob.app**

You'll receive an access code separately to create your Lead account. Do not share your access code or credentials outside the group.

## In Scope

- **Lead flow:** account creation, login, creating and managing rounds, adding questions, sharing rounds
- **Voice flow:** joining a round via QR code or join code, submitting feedback anonymously
- **Mobile and responsive behaviour:** please test on your phone as well as desktop
- **Accessibility:** keyboard navigation, screen reader behaviour, colour contrast
- **Authorisation**: once logged in, try to access rounds, questions, and responses belonging to other Lead accounts by manipulating URLs or request parameters. **Do not** exfiltrate, store or share any data you access, and do not attempt to access the underlying infrastructure, database or server directly.

## Out of Scope

- Authentication internals (the login, registration and password reset flow). This will be handled by a third-party provider so is out-of-scope for this exercise
- Infrastructure and hosting
- Attempting to access the underlying infrastructure, database or server directly
- Load or performance testing

## How to Submit a Bug

Use GitHub Issues in this repository. Click **New Issue** and the form will guide you through what to include.

**Please do not open a public issue for security vulnerabilities.** If you find something that could compromise user data or platform security, email **BSU emailbathspa.ac.uk** directly instead.

## Tips

- Try to break things — use unexpected inputs, skip steps, go back when you shouldn't
- Test the full round lifecycle: create a round as a Lead, then join it as a Voice from your phone
- If something feels confusing or unintuitive, report it — usability issues are as valuable as bugs
- Duplicate reports happen; check open issues before submitting

## Questions

Contact **Laura at BSU emailbathspa.ac.uk** or raise a discussion in this repo.
