# Weekly Run of Show

The internal, minute-by-minute plan for a standard 60-minute office hours session, with every role named.

**When:** Weekly, T+1w to T+8w. Draft 5 business days before each session; share with mentors 2 days before.

**Sent by / owner:** Program organizer (session host).

**Audience:** Presenters, mentors, Team Leads. Internal working document, not participant-facing.

## Template

```text
Week [N] mentor run of show: [Session title]
Slides: [Link]
Time: [Office hours day and time, with UTC]. [Clock-change note if relevant.]

Biggest risk: [one line, e.g. live demo fails, main room overruns into breakouts]

[HH:00] Welcome and recap (3 min)
Lead: [Host name]
- Recap last week; notes are in [Hub channel]
- Celebrate wins since last week by name: issues claimed, PRs opened or merged, first community meeting attended, first review given
- Frame today's topic in one line

[HH:03] Overview or deep dive (15 to 17 min)
Lead: [Presenter name]
- [Key point]
- [Key point]
- Landing line: [one sentence participants should remember]

[HH:20] Breakout logistics (2 min)
Lead: [Host name]
- Name each room out loud
- Any project room is welcome, not only your primary
- Breakouts close at [HH:54]; everyone back by [HH:55]

[HH:22] Breakouts (33 min)
Main room stays staffed so the host can open more rooms.
- [Project]: [Breakout host name]
- [Project]: [Breakout host name]
- Stuck room / hallway track: [Name]
Ask every room to cover:
- [Prompt tied to this week's topic]
- [Prompt tied to this week's topic]
- Check in on each person: what are you working on, what's blocking you?

[HH:55] Back to main: wins, homework, close (5 min)
Lead: [Name]
- Quick round of wins, or a 2-minute share-back per room
- Homework for Week [N+1]: [chains from this week's homework]
- Preview of Week [N+1] ([Date]): [Topic]
- Reminder: share wins in the channel

Roles during the session
- Host: [Name]
- Timekeeper: [Name or ?]
- Chat monitor (posts unanswered questions to the channel afterward): [Name or ?]
- Breakout hosts, one per room with Zoom co-host rights ([N] rooms): [Names]
- Attendance capture, same columns every week: [Name]

Open items before [MM/DD]
- [ ] [Unresolved decision]
- [ ] [Unconfirmed presenter or room host]
- [ ] [Fallback if the demo or screen share fails]
```

## How to use

- Give every section a wall-clock start time and a named lead. Use "?" rather than inventing a name.
- Protect breakout time: maintainers want 30+ minutes. If the overview runs long, cut it, not the breakouts.
- The open items list is the point of the document. If it's empty, look harder.
- Check each breakout prompt matches this week's topic. Copy-pasted prompts from a past week are a bug.
- Pre-grant Zoom co-host rights to breakout hosts; breakout rooms can't be recorded by default.

## Notes for alignment

- **Recommendation:** Public. Session shape and roles are company-neutral.
- **Company-specific parts:** meeting platform, recording policy, and [If your company counts office hours as a registered volunteer event: attendance capture feeds [Matching program name]].
- **Derived from:** NumFOCUS Week 4 Run of Show; numfocus-office-hours skill (run of show structure and timing rules); otel-agenda skill (internal agenda structure); Office Hours Kit.
