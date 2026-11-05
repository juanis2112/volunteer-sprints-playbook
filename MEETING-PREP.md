# Juanita Alignment Meeting: Proposed Resolutions

> Part of the [Sustaining Open Source Series runbook](README.md). Prep for the Alyssa and Juanita alignment meeting. Draft by Stephen Augustus for Alyssa's review, last updated 2026-10-30. Sources, notes, and evidence: [soss-research](https://bbgithub.dev.bloomberg.com/saugustus2/soss-research).

Each item below is an open question from the [suggested meeting agenda](ALIGNMENT.md#suggested-meeting-agenda), with what each playbook does now, a proposed resolution, and the decision we need from Juanita. Items are grouped by priority: tracking and follow-up first, then logistics and coordination, then messaging and community management. Agenda numbers are in brackets.

"Ours" is [PLAYBOOK.md](PLAYBOOK.md) and its companion pages. "Juanita's" is her [PLAYBOOK.MD](https://github.com/juanis2112/volunteer-sprints-playbook/blob/7d03a592a7b58ef8aad1cb15e49156c415d64b86/PLAYBOOK.MD) at commit `7d03a59`.

## 1. Tracking and follow-up

### Metrics [6]

* **Juanita's:** locks metrics before outreach, with targets or good/acceptable/needs-improvement bands, in four groups: participation, contribution, experience, program health. "Retention" means active through the final week.
* **Ours:** tracks hours, PRs authored and merged, comment threads, attendance, sentiment, and continuity 3 and 6 months after close. Every number carries its period, population, and source; survey intent stays internal; no leaderboards.
* **Proposed:**
  * Adopt her four groups, the bands, and the rule to lock them before outreach.
  * Add a fifth group, community engagement: meetings attended, triage and reviews, channel participation, later roles. This keeps PRs from dominating.
  * Name two metrics: **completion** (active in the final week) and **retention** (still engaging 3 and 6 months after close).
  * Add our three reporting rules to the shared core.
* **Ask Juanita:** does the fifth group fit her stakeholders' reporting, and will she rename her "retention" to "completion"?

### Follow-up during the series

* **Juanita's:** a light-touch follow-up for inactive volunteers before assuming they dropped, and a waitlist replacement if timing allows.
* **Ours:** an engagement triage at about T+4w (hours, GitHub activity, attendance), then 1:1 follow-up through mini-cohort leads. In 2026, 33 of 56 participants showed no activity at T+4w.
* **Proposed:** put the T+4w triage in the shared core as the point where her light-touch follow-up happens. Mini-cohorts are under [7] below.

### Wrap-up and archive

* **Juanita's:** Stage 6 done within 2 weeks of close: a one-page outcomes summary, a named cycle folder, and playbook updates.
* **Ours:** end survey open 2 to 3 weeks, retro about 4 weeks after close, and a frozen report date with the query archived. OTel's final figures couldn't be traced to a dated report.
* **Proposed:** adopt her 2-week deadline for the outcomes summary and archive. Hold the retro and final metrics freeze to our later dates, and require the archived query in the summary. Not on the agenda; raise it under [6].

## 2. Logistics and coordination

### Stage 0: 6 months before [2]

* **Juanita's:** starts 3 months out.
* **Ours:** first foundation contact at T-24w, agreement started by T-16w. Signature can take 2 months, and the 2026 agreement was still unsigned at kickoff.
* **Proposed:** add Stage 0 (foundation and maintainer conversations, the agreement, partner company recruiting, metrics and dates). Her Stage 1 tasks stay where they are.
* **Ask Juanita:** has she hit agreement or partner lead times that a 3-month start couldn't absorb?

### Who convenes a multi-company run [1]

* **Juanita's:** written for a single organizer at one company.
* **Ours:** [PARTNER-GUIDE.md](PARTNER-GUIDE.md) assumes one convening organizer who runs the shared Zoom, tracker, drive, cross-company sync, and channels doc. Each partner names a Team Lead.
* **Proposed:** one named convener per run, chosen at Stage 0. Any company can take the role; the playbook's partner guide describes the hand-off. A rotating role with no named owner risks splitting the shared infrastructure.
* **Ask Juanita:** would NVIDIA convene a run, and what would it need from the playbook to do so?

### Contribution pathways timing [3]

* **Juanita's:** good first issues curated 1 week before, as a mentor-owned task.
* **Ours:** 15+ series-ready issues due with the project profile at T-14w. Every run found issue discovery, not motivation, was the bottleneck.
* **Proposed:** each project's profile, at about T-14w, includes starter issues plus community pathways (meetings, channels, triage, docs, reviews). Her 1-week step becomes the refresh and label check. One named owner per project keeps the list current; both playbooks agree on this.
* **Ask Juanita:** will maintainers commit to a list 3 months out?

### Selection by pool size [5]

* **Juanita's:** one live criteria meeting (motivation, availability, project fit, mentor capacity, follow-through).
* **Ours:** independent 1-10 scoring, then a gray-zone meeting. 2026 pools ran 135 and about 300 applicants for about 45 slots each.
* **Proposed:** her meeting for pools under about 60; independent scoring plus a gray-zone meeting above that. Both use her criteria, our guardrails, and credit for interest in community engagement. Our guardrails: flag connections, don't score prior participation up or down, protect small projects, usage alone never earns 7+.
* **Ask Juanita:** is 60 the right threshold?

### Mini-cohorts, Setup Sprints, regional cohorts [7]

* **Juanita's:** none of the three.
* **Ours:** all three are standard since 2026.
* **Proposed:** all three go in the shared core as standard features. Company details (in-person format, events, which regions) stay out. Evidence: setup was the top friction in pandas 2023 and 2024; the T+4w inactivity figure above.
* **Ask Juanita:** which of the three NVIDIA could run, and whether any should be optional.

## 3. Messaging and community management

### Program name [9]

* **Juanita's:** "Volunteer Sprint," "volunteers."
* **Ours:** "Sustaining Open Source Series," "participants."
* **Proposed:** "Sustaining Open Source Series" for the shared program and playbook. Each company can title its own cycle, for example on a volunteer page. "Sprint" also names the in-person Setup Sprints, so using it for the 10-week program would be confusing.
* **Ask Juanita:** must align.

### Matching is optional [4]

* **Juanita's:** her form header and ad copy assume a matching program.
* **Ours:** not every company has one.
* **Proposed:** matching appears only as a conditional line ("If your company has a volunteer-hour matching program: ..."), which the templates already do. Report logged and matched hours separately. Her volunteer-page guide becomes an optional company add-on.

### Templates and repo format [8]

* 45 templates in [public-draft/templates/](public-draft/templates/README.md), each marked Public or "Public core + company add-on." Her interest form, recruitment message, newsletter pitch, and selection criteria are merged in.
* **Proposed:**
  * One file per template, linked from the playbook. Inline, 45 templates would bury the playbook text.
  * Company add-ons as conditional lines inside each template, not a separate appendix, so organizers fill in one file.
  * Recruitment opens at T-10w with two info sessions, her longer window, as the templates already assume. Update the internal playbook from T-8w to match.
  * Walk the six templates drafted without a direct source together.
* **Ask Juanita:** confirm the merged versions of her templates.

## 4. TODO Group landing [10]

Decided: the TODO Group hosts it; Stephen and the TODO Group maintain the org; Alyssa and Juanita are repo admins.

* **Proposed:** a dedicated repo under the TODO Group org for the playbook and templates, with a guide page on the site that links to it. A dedicated repo lets Alyssa and Juanita hold admin rights without admin on the website repo.
* **Before publishing:**
  * Pick the license with the TODO Group.
  * Juanita's repo has no LICENSE, so her text needs her explicit contribution under the chosen license.
  * Bloomberg's open source contribution approval for Alyssa's content.
* **Ask Juanita:** confirm she's in, and who else to add as admins.
