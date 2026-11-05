# Dev environment setup guide outline

A skeleton for a per-project setup guide that takes a participant from accounts to passing tests, including common errors and where to get help.

**When:** Draft by T-14w; test at the Setup Sprint (T-13w to T-11w); finalize with all comments closed before T0.
**Sent by / owner:** Program organizer, with company mentors writing each project's section and project mentors reviewing
**Audience:** Participants (and the Setup Sprint groups who test it)

## Template

### Part 1: General setup (shared by all projects)

**Before you start**
- [If your company has a standard dev machine setup: Re-run [Company setup tool] so your tools are current.]
- [If you use a company VPN or proxy: Note which steps need it off or on.]
- Add comments to this guide whenever something fails or you find a fix.

**Step 1: Accounts**
- Create a personal account on [Code hosting platform, e.g. GitHub] if you do not have one.
- [If your company has an open source policy on emails: Add your work email as a secondary address, never primary, per [Company policy name].]
- Sign any contributor license agreement (CLA) the project requires, using the email your company's guidance specifies.
- Join the project channel listed in the Official Channels doc.

**Step 2: Git configuration**
- Install git.
- Set your name and email for open source work:

```text
git config --global user.name "First Last"
git config --global user.email "you@personal-email.example"
```

- [If you use the same machine for work repos: Set the email per repository instead of globally, so work and open source commits do not mix.]
- Authenticate (for example with a personal access token or the platform's CLI).

**Step 3: Fork and clone**
- Fork the project repository: [Repository URL].
- Clone your fork and add the upstream remote:

```text
git clone https://github.com/<your-username>/<project>.git
cd <project>
git remote add upstream https://github.com/<upstream-org>/<project>.git
git fetch upstream
```

- Project-specific values: list `<project>` and `<upstream-org>` for each project here.

### Part 2: Per-project guide (one per project)

**[Project] setup**

Resources
- Contributor guide: [Link]
- Development workflow: [Link]
- Build from source: [Link]
- Docs build (if separate): [Link]

Build the environment (one subsection per environment)
- macOS: [Recommended tool, e.g. conda, venv, pixi], commands in order.
- Windows (via WSL or native): commands in order.
- Linux: commands in order.
- Cloud dev environment (fallback): how to open one and any differences.
- [If your company uses managed laptops: Managed laptop notes: proxy, certificates, internal package mirrors.]
- State which option the testers found most reliable, and why.

Verify it works
- Command to confirm the dev build is installed (for example, print the version and check it shows a development tag).
- Command to run a quick subset of tests.
- Expected output, and how long a full test run takes.

Common errors and fixes
- [Error message]: [Cause]. Fix: [Steps].
- [Error message]: [Cause]. Fix: [Steps].
- Typical categories: package mirror or index redirects, proxy and SSL certificate errors, compiler or system library issues, solver timeouts, tests that need network access.

Find your first contribution
- Where series-ready issues live (label, list, or channel).
- Other ways to start: reproduce an old bug report, improve an example in the docs, join a community meeting, help answer a question.
- How to claim an issue in this project (for example, a comment or bot command).
- If an issue already has someone on it, or a long unresolved debate, choose another.

Sync before you start

```text
git checkout main
git fetch upstream
git rebase upstream/main
git checkout -b <feature-branch-name>
```

Make, test, and open your contribution
- Commit as you go with clear messages; write tests that fail before your change and pass after.
- Follow the project's title and description conventions; if undocumented, copy recently merged examples.
- Keep descriptions concise and in your own words. Disclose AI use per the project's policy.
- Be respectful and responsive to feedback. Reviewers are volunteers.
- If a week passes with no response, post a gentle nudge in [Project channel].
- Maintainers handle merging.

### Part 3: Where to get help
- Setup questions: [Project channel] or [Hub channel].
- Your company mentor or mini-cohort lead: [Contact or "see Official Channels doc"].
- Office hours: [Office hours day and time, with UTC].
- Add a comment in this guide describing the error and what you tried, so the next person benefits.

## How to use

- Start each project section from the project's own contributor docs; add only what your environments need.
- Test every environment at the Setup Sprint and record who tested what and when.
- Keep company-only steps (proxies, internal mirrors, managed laptops) in clearly marked conditional sections so the rest can be shared upstream.
- Close every open comment before T0 and publish at one stable link.
- Offer improvements that help all new contributors back to the project's own docs.

## Notes for alignment

- **Recommendation:** Public core + company add-on. Accounts, git, fork, verify, and contribution steps are universal; network, mirror, and managed-device notes are company-specific.
- **Company-specific parts:** email policy, CLA signing rules, VPN and proxy steps, internal package mirrors, managed cloud dev environments, company setup tools.
- **Derived from:** "NumFOCUS OSS Setup Guides" (structure only); PLAYBOOK.md Step 5a.
