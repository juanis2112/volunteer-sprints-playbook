# Alignment: Our Playbook vs. Juanita's Volunteer Sprint Playbook

> Part of the [Sustaining Open Source Series runbook](README.md). Prep for the Alyssa and Juanita alignment meeting. Last updated 2026-10-27.

Compared:

* **Juanita's:** [Open Source Volunteer Sprint: Organizer Playbook](https://github.com/juanis2112/volunteer-sprints-playbook/blob/main/PLAYBOOK.MD) (Juanita Gomez, NVIDIA, last updated October 2026). Six time-based stages, from 3 months before to after the sprint, with copy-paste templates inline.
* **Ours:** [PLAYBOOK.md](PLAYBOOK.md), with 5 phases and 13 steps starting about 6 months before, plus the partner, office hours, and metrics pages.

## Where we already agree

* A 10-week cohort, weekly office hours, maintainer mentors, and hours matched by the employer.
* Three-part Slack structure: a mentor coordination channel, a participant announcement channel, and one channel per project.
* Partnership agreements must be in place before outreach.
* Curated good first issues, with **one named owner per project who keeps the list current**.
* Mid-cohort survey around week 5, an end survey, and a mentor retro.
* Archive each cycle and update the playbook before the next one.

## Differences to align on

### 1. Timeline: 3 months vs. about 6 months

* **Juanita:** Stage 1 starts 3 months before the sprint (recruit mentors, legal, docs, metrics).
* **Ours:** first foundation contact at T-24w, agreement started by T-16w (signature takes up to 2 months), Setup Sprints at T-13w to T-11w.
* **Why it matters:** a 3-month start doesn't leave time for the agreement (still unsigned at kickoff in 2026), multi-company recruiting, or Setup Sprints.
* **Proposal:** add a "Stage 0: 6 months before" for partnership, legal, and project scoping.

### 2. Who the playbook is for

* **Juanita:** a single program organizer, written company-neutral ("[your company]").
* **Ours:** a convening organizer (Bloomberg in 2026) plus partner companies, each with a Team Lead. See the [Partner Guide](PARTNER-GUIDE.md).
* **Question:** is the goal one shared multi-company playbook, or each company keeping its own with a shared core? Who convenes the next run?

### 3. Roles

* **Juanita:** three roles: program organizer, mentors (about 2 hrs/week), volunteers.
* **Ours:** the [InTech] roles doc splits company mentors (2 to 4 hrs/week, at least 2 office hours) from project mentors (about 2 hrs/week, at least 3 office hours). It adds a Team Lead per company (about 50 hrs), mini-cohort leads, and Philanthropy.
* **Adopt from Juanita:** a required **backup mentor per project**, plus a documented place to ask questions when the primary mentor is away.

### 4. Issue curation timing

* **Juanita:** curate good first issues in Stage 4, 1 week before the sprint, as a mentor-owned task.
* **Ours:** project profiles with 15+ series-ready issues are due T-14w. Every run says issue discovery was the bottleneck, not motivation.
* **Proposal:** ask for the starter backlog with the project profile (about 3 months out), then confirm the labels and refresh it 1 week before.

### 5. Recruitment window and info sessions

* **Juanita:** form open at least a month; two info sessions (about 1 and 2 weeks after the form opens); email the mailing list of prior interested people.
* **Ours (2026):** form open about 2.5 weeks with one info session, run as a BOB event.
* **Adopt from Juanita:** the longer window, a second info session, and a standing interest mailing list.

### 6. Selection

* **Juanita:** a group meeting against a criteria list (motivation, availability, project fit, mentor capacity, likely follow-through). Each person is marked accepted, waitlisted, declined, or needs follow-up in one live tracker.
* **Ours:** each reviewer scores 1-10 independently in their own tab, then we look at total, average, and variance. A gray-zone work session settles close calls. Rules: flag personal connections; don't score prior participation up or down; protect small projects; cap popular projects' primary slots.
* **Note:** her playbook links a "selection criteria document" and "email templates in this playbook folder," but the repo contains only PLAYBOOK.MD.
* **Question:** should we standardize on independent scoring for large applicant pools (300 in 2026) and her meeting format for small ones?

### 7. Intake form

* **Juanita:** asks about Python and data skills, a 1-5 rating per project for familiarity and excitement, open source story, and commitment.
* **Ours adds:** previous series, Setup Sprint attendance, Guild and InTech membership, a required GitHub handle, and an APAC flag.
* **Proposal:** a shared core form, with company-specific questions in a final section.

### 8. Hours tracking and matching

* **Juanita:** one volunteer page per cycle on the matching platform: invite-only, one shift for the whole window, self-tracked hours, submitted within the calendar year.
* **Ours:** participants file SDSK ADD 43571 with manager approval as the hours ledger. There is one BOB event per office hours session plus sprint and celebration events. The match is capped at 50 hours per person.
* **Company-specific, no need to align.** Not every company has a matching program, so the shared playbook should treat matching as optional ("if your company has a matching program"). It is worth sharing the reporting rule: report logged hours and matched hours separately.

### 9. Manager involvement

* **Juanita:** the ad tells people to "talk to their managers."
* **Ours:** formal manager approval through SDSK, an OSPO email to every accepted participant's manager, and manager recognition notes for year-end evaluations.
* **Proposal:** add the manager recognition step to the shared core. It costs little and helps retention.

### 10. Success metrics

* **Juanita:** lock metrics before outreach, with targets or good/acceptable/needs-improvement bands, across participation, contribution, experience, and program health.
* **Ours:** we track hours, PRs authored and merged, comment threads, attendance, sentiment, and retention 3 and 6 months after. Rules: every number carries its period, population, and source; self-reported intent stays internal; no leaderboards.
* **Adopt from Juanita:** pre-locked metrics with bands, and her program health metrics (office hours with full mentor coverage, waitlist replacements, time from form close to selection emails).
* **Align:** her "retention" means active through the final week; ours means still contributing 3 to 6 months later. Track both, and name them differently.

### 11. Things in ours that Juanita's doesn't cover

* Setup Sprints before applications open.
* Mini-cohorts with 1:1 weekly check-ins, plus an engagement triage at about week 4.
* The APAC sub-cohort with regional reviewers and a regional kickoff.
* Session shape and roles (timekeeper, chat monitor, breakout hosts) and a 10-week curriculum arc. See [OFFICE-HOURS.md](OFFICE-HOURS.md).
* AI guidance: a dedicated AI session; project AI policy overrides series guidance; a reminder for undisclosed AI PRs.
* CLA and legal approvals for contributions: personal email for CLAs, IPWG pre-clearance.
* Comms rules: company leads in every private channel, an Official Channels doc, a fallback for people without Slack.
* Comms review lead times for blogs and talks.

### 12. Things in Juanita's that ours doesn't cover

* **Copy-paste templates inline:** Slack/email ad, newsletter pitch, interest form, volunteer page description. Ours links to Drive, which partners couldn't always open.
* A **non-code contributions** section (docs, triage, testing, reproduction, community support), confirmed per project.
* A **document inventory with owners** set before outreach, and "one canonical version of each document." We had three roles docs.
* An internal tech talk with a maintainer as an outreach channel.
* A wrap-up deadline: Stage 6 done within 2 weeks of close, with a 1-page outcomes summary.

### 13. Naming and words

* **Juanita:** "Volunteer Sprint," "volunteers," "sprint."
* **Ours:** "Sustaining Open Source Series," "participants," "series" or "cohort."
* **Question:** one name for the shared program? It matters for the BOB and volunteer page titles, Tutti, and blog posts.

## Templates to review together

All 45 company-neutral templates in [public-draft/templates/](public-draft/templates/README.md) need a decision with Juanita: what goes in the public repo, what stays company-specific, and how her templates merge with ours. Recommendation key: **Public** = shared as is; **Public core + company add-on** = shared structure, each company fills in its own steps.

### Questions for the template discussion

1. **Public vs. company-specific:** walk the index. Agree the recommendation for each template, especially the "Public core + company add-on" ones: is the add-on a conditional line inside the template, or a separate company appendix?
2. **Merge with her playbook:** her interest form, recruitment message, newsletter pitch, and selection criteria are merged into 03-recruitment. Confirm she's happy with the merged versions, and whether her volunteer-page guide becomes a template here.
3. **Project pitch email:** new template modeled on Rich Bowen's draft to a project dev list (TL;DR first, "What it isn't," size the cohort to review capacity). Confirm it works for her companies.
4. **Fill her missing files:** her playbook points to selection criteria and email templates that aren't in her repo. 03-recruitment/06 and 04-selection cover them.
5. **Recruitment window:** these templates open applications at T-10w with two info sessions (her longer window). Our internal playbook says T-8w. Agree one.
6. **Placeholder set:** agree one shared list of placeholders and the program name (Alyssa: "Sustaining Open Source Series").
7. **Format for the public repo:** one file per template (this layout) or inline in the playbook (her layout)?

### Every template, by phase

#### 1. Partnership (T-24w to T-14w)

* [Foundation pitch email](public-draft/templates/01-partnership/01-foundation-pitch-email.md): Public core + company add-on
* [Project pitch email](public-draft/templates/01-partnership/02-project-pitch-email.md): Public. A [DISCUSS] post to a project's own list, run past its governance group first
* [Partner company outreach email](public-draft/templates/01-partnership/03-partner-company-outreach-email.md): Public
* [Company overview (one-pager)](public-draft/templates/01-partnership/04-company-overview.md): Public core + company add-on
* [Project profile request](public-draft/templates/01-partnership/05-project-profile-request.md): Public
* [Maintainer kickoff agenda](public-draft/templates/01-partnership/06-maintainer-kickoff-agenda.md): Public

#### 2. Setup (T-15w to T-4w)

* [Roles and expectations](public-draft/templates/02-setup/01-roles-and-expectations.md): Public core + company add-on
* [Collaboration guidance](public-draft/templates/02-setup/02-collaboration-guidance.md): Public core + company add-on
* [Official channels doc](public-draft/templates/02-setup/03-official-channels-doc.md): Public core + company add-on
* [Setup Sprint invitation](public-draft/templates/02-setup/04-setup-sprint-invite.md): Public core + company add-on
* [Setup Sprint recap](public-draft/templates/02-setup/05-setup-sprint-recap.md): Public core + company add-on
* [Dev environment setup guide outline](public-draft/templates/02-setup/06-dev-environment-setup-guide-outline.md): Public core + company add-on

#### 3. Recruitment (T-12w to T-5w)

* [Recruitment announcement](public-draft/templates/03-recruitment/01-recruitment-announcement.md): Public core + company add-on
* [Outreach tracker](public-draft/templates/03-recruitment/02-outreach-tracker.md): Public
* [Interest form](public-draft/templates/03-recruitment/03-interest-form.md): Public core + company add-on
* [Participant FAQ](public-draft/templates/03-recruitment/04-participant-faq.md): Public core + company add-on
* [Info session agenda](public-draft/templates/03-recruitment/05-info-session-agenda.md): Public
* [Selection rubric](public-draft/templates/03-recruitment/06-selection-rubric.md): Public

#### 4. Selection (T-5w to T-1w)

* [Acceptance email](public-draft/templates/04-selection/01-acceptance-email.md): Public core + company add-on
* [Waitlist email](public-draft/templates/04-selection/02-waitlist-email.md): Public core + company add-on
* [Waitlist-to-accepted email](public-draft/templates/04-selection/03-waitlist-to-accepted-email.md): Public core + company add-on
* [Not selected email](public-draft/templates/04-selection/04-not-selected-email.md): Public core + company add-on
* [Manager notification email](public-draft/templates/04-selection/05-manager-notification-email.md): Public core + company add-on
* [GitHub handle request](public-draft/templates/04-selection/06-github-handle-request.md): Public
* [Hub join and next steps](public-draft/templates/04-selection/07-hub-join-next-steps.md): Public core + company add-on
* [Regional cohort welcome](public-draft/templates/04-selection/08-regional-cohort-welcome.md): Public

#### 5. Running the series (T-4w to T+9w)

* [Mentor Meet-and-Greet Agenda](public-draft/templates/05-running-the-series/01-mentor-meet-and-greet-agenda.md): Public
* [Office Hours Calendar Hold](public-draft/templates/05-running-the-series/02-office-hours-calendar-hold.md): Public
* [Week 1 Kickoff Run of Show](public-draft/templates/05-running-the-series/03-week-1-kickoff-run-of-show.md): Public core + company add-on
* [Weekly Run of Show](public-draft/templates/05-running-the-series/04-weekly-run-of-show.md): Public
* [Weekly Slack Announcement](public-draft/templates/05-running-the-series/05-weekly-slack-announcement.md): Public
* ["Notes Are Live" Post](public-draft/templates/05-running-the-series/06-notes-live-post.md): Public
* [Office Hours Notes](public-draft/templates/05-running-the-series/07-office-hours-notes.md): Public
* [Mini-Cohort Check-In](public-draft/templates/05-running-the-series/08-mini-cohort-check-in.md): Public
* [Team Lead Reply Snippets](public-draft/templates/05-running-the-series/09-team-lead-reply-snippets.md): Public core + company add-on
* [Weekly Pulse Poll](public-draft/templates/05-running-the-series/10-weekly-pulse-poll.md): Public
* [AI Use Reminder](public-draft/templates/05-running-the-series/11-ai-use-reminder.md): Public
* [Midpoint Check-In Survey](public-draft/templates/05-running-the-series/12-midpoint-check-in-survey.md): Public
* [Stakeholder Recap Email](public-draft/templates/05-running-the-series/13-stakeholder-recap-email.md): Public core + company add-on

#### 6. Close-out (T+6w to T+26w)

* [End-of-Series Survey](public-draft/templates/06-close-out/01-end-of-series-survey.md): Public
* [Mentor and Organizer Retro Agenda](public-draft/templates/06-close-out/02-mentor-retro-agenda.md): Public
* [Celebration Session Run of Show](public-draft/templates/06-close-out/03-celebration-session-run-of-show.md): Public core + company add-on
* [Manager Recognition Email](public-draft/templates/06-close-out/04-manager-recognition-email.md): Public core + company add-on
* [Keep Contributing Message](public-draft/templates/06-close-out/05-keep-contributing-message.md): Public core + company add-on
* [Outcomes Summary](public-draft/templates/06-close-out/06-outcomes-summary.md): Public core + company add-on

### Drafted without a direct source (flag to Juanita)

* 04-selection/05 manager notification email: no source email existed; drafted from the playbook and the recognition email tone.
* 03-recruitment/03 interest form: the original form couldn't be read; questions reconstructed from response-sheet headers and Juanita's form.
* 05-running-the-series/12 midpoint survey: questions inferred from a results report, not the original form.
* 06-close-out/01 end-of-series survey: the source cut off at question 10; the last question is reconstructed.
* 02-setup/01 roles: mini-cohort lead time commitment is [N]; the program organizer role was built from the playbook.
* 02-setup/02 collaboration guidance: general communication norms drafted from playbook context.
* All **When** timings: check against the internal playbook and Juanita's stages.

## Suggested meeting agenda

1. ~~Shared playbook or one per company?~~ Decided 2026-10-28: one shared public playbook (see DECISIONS.md). **Discuss with Juanita:** who convenes a multi-company run: one named company per run, or a rotating role any company can take? (Difference 2)
2. **Align with Juanita:** add "Stage 0: 6 months before". Alyssa's position: yes (see DECISIONS.md). (Difference 1)
3. **Align with Juanita:** curate contribution pathways as early as possible, not just issues: starter issues plus community participation (comms channels, SIG or community meetings, triage, docs, reviews). Don't over-index on GitHub PRs. Alyssa's position (see DECISIONS.md). (Difference 4)
4. **Align with Juanita:** volunteer-hour matching is optional and company-specific in the public playbook, since not every company has a program. Her form header and ad copy currently assume matching. (Difference 8)
5. **Discussion point:** selection by pool size: her criteria meeting for small pools (under about 60), independent scoring plus a gray-zone meeting for large ones. Her criteria plus our guardrails, plus scoring community-engagement interest. Alyssa's leaning, open for discussion. (Difference 6)
6. **Discussion point:** metrics. Starting proposal: adopt her pre-locked metrics with bands and her four groups; add a fifth group, community engagement (meetings attended, triage and reviews, channel participation, later roles), so PRs don't dominate; name two retention metrics, "completion" (active in the final week) and "retention" (still engaging 3 and 6 months after close); add the reporting rules (period, population, source on every number; survey intent internal; no leaderboards). (Difference 10)
7. **Discussion point:** Alyssa wants mini-cohorts, Setup Sprints, and regional cohorts (APAC) all in the shared playbook, with company details kept company-specific. (Difference 11)
8. **Discussion point: templates.** Walk all 45 templates and agree public vs. company-specific for each, including the merged versions of her inline templates and the non-code section (widened to contribution pathways). See "Templates to review together" above. (Difference 12)
9. **Must align with Juanita:** program name. Alyssa wants to keep "Sustaining Open Source Series" (hers: "Volunteer Sprint"). (Difference 13)
10. ~~Where it lives and who maintains it~~ Decided 2026-10-28: TODO Group. Stephen Augustus and the TODO Group maintain the org; Alyssa and Juanita (and possibly others) are repo admins. **Discuss with Juanita and Stephen:** confirm she's in, who else to add as admins, and repo vs. guides-section placement.
