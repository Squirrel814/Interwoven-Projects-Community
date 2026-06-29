# Interwoven Projects - Community Framework & Brochure

**Version:** 1.1 (Updated with user fixes and improvements)  
**Last Updated:** 2026-06-29  
**Purpose:** Easy reference for new and current members. This formalizes the rough draft into a welcoming brochure-style document with moderation hierarchy, spaces calendar, projects overview, and promotion assets. It serves as the "brochure for Interwoven Projects" with info-graphics and images (placeholders and generation prompts included for easy updating).

**How to Join the Community**
1. Read this brochure and [GOVERNANCE.md](GOVERNANCE.md).
2. Introduce yourself in the X community chat or open a Discussion ("Introductions & Skills").
3. Propose or join a project using the templates in this repo.
4. Follow attribution, free-core, ethics, and moderation rules.
5. Get credited for your contributions (see ATTRIBUTION.md).

**Current Official Calendar** (updated 2026-06-29 — expand with real dates as scheduled; link to X or Google Calendar for live updates)

| Type              | Frequency          | Description                                              | Status     | Link / Notes                                      |
|-------------------|--------------------|----------------------------------------------------------|------------|---------------------------------------------------|
| Lounge Spaces     | 24/7 goal          | Non-recorded, casual friend-like hangouts                | Active     | Speaker verification required (post in purple pill) |
| Open-Mic          | 2x weekly (Mon/Thu)| Q&A with timed introduction speaker positions            | Active     | Recorded; link to recording in X community        |
| Project Spaces    | As scheduled       | Planned speakers only for specific topics                | Active     | Recorded; see project proposal for schedule       |
| Official Courses  | Varies (monthly)   | Approved teaching sessions (free core materials linked) | Pending    | See Approved Instructors in GOVERNANCE.md         |
| Community Updates | Bi-weekly          | Moderation log summary and new project highlights        | Active     | Private Moderation-Log repo (moderators only)     |

**Moderation Hierarchy and Responsibilities** (formalized from original rough draft in this file)

- **Administrator** (Squirrel814): Final decision-making, Enforcement Moderator role, overall oversight, final approval on teaching/monetization requests.
- **Ethics Enforcer**: Promote non-biased behavior, co-host spaces, handle warnings/mutes/expulsions, delete/report anti-community content.
- **Facilitator**: Curate diverse speaker lineups for Project Spaces, host Lounge Spaces (goal: at least one 24/7), intervene subtly in unbalanced conversations, archive key insights.
- **Welcomer** (@rambosemporium, @ark__): Hold 2 open-mic/Q&A spaces weekly, monitor facilitated spaces as Co-Host, verify respectful nature of new speakers in Lounge Spaces (comment on verification post for speaker access).
- **Scheduler/Audits** (1 needed): Prioritize scheduling to meet community goals, audit for DEI representation, refine via anonymous surveys.
- **Community Ambassador** (1 needed): Represent community externally, build partnerships with aligned values.
- **Junior Mod** (@SamuriaMintTea, @monkey31336): Sponsored/trained by current moderators; assist with above duties.

**Future possible roles** (brainstorm for later expansion, not adding now): Technical Reviewer, Content Curator, DEI Auditor, Legal/Ethics Advisor, Event Coordinator, per-subject Library Maintainer, AI Ethics Specialist.

**Spaces Policies**
- **Lounge Spaces [Non-Recorded]**: Casual, friend-like hangouts. No unknown persons allowed into speaker positions without another speaker verifying the person's respectful nature. If hosting, post the verification rule in the purple pill and place in the nest. To gain speaker position, comment on the verification post for review.
- **Open-Mic [Recorded]**: 2 spaces weekly for questions and answers with timed introduction speaker positions.
- **Project/Specific Topic [Recorded]**: Planned speakers only.

Official/recorded spaces have stricter enforcement. Lounge spaces allow relaxed but respectful conversation among verified participants.

**Current Projects & How to Get Involved**
(See `/projects/` directory and GitHub Projects board for live status. No active projects listed yet — be the first!)

- **Propose a Project**: Use the Project Proposal template.
- **Join**: Use the Join Project template or comment on an active discussion.
- **Contribute**: Record updates via Contribution Update template. All contributions are credited per [ATTRIBUTION.md](ATTRIBUTION.md).

**Promotion & Visual Assets** (add these images for X, onboarding, and sharing)
- **Mermaid Hierarchy Diagram** (replace placeholder with exported PNG):
  ```mermaid
  graph TD
      Admin[Administrator / Enforcement Moderator<br/>Squirrel814] --> Ethics[Ethics Enforcer]
      Admin --> Facilitator[Facilitator]
      Facilitator --> Welcomer[Welcomer]
      Admin --> Scheduler[Scheduler/Audits]
      Admin --> Ambassador[Community Ambassador]
      ModeratorTeam[Moderator Team] --> Junior[Junior Mods]
  ```
- **Promotion Brochure Cover** (`promotion-brochure.png`): Image of community values, hierarchy, calendar, "How to Join" flow. (Generate with prompt: "Clean infographic for Interwoven Projects community brochure showing moderation hierarchy, spaces calendar, and how to join with interdisciplinary icons").
- **Values Infographic** (`values-poster.png`): "Free Core, Clear Credit, Ethical AI, Interdisciplinary Kindness".
- **How to Join Flowchart** (Mermaid or PNG): 5-step visual.
- **PDF Version**: Export this document as `Interwoven-Projects-Brochure.pdf` for easy sharing (use pandoc or online converter).

**Suggestions for Improvement** (already incorporated where possible):
- Clean PDF export version for sharing (add to repo root after generation).
- Live "Current Active Projects" table pulling from `/projects/`.
- Visual "Path to Contribution" flowchart (added as suggestion above).
- Pinned "Welcome Post" in the X community linking to this file.
- Expand calendar with actual dates and links (done above with examples).

For full governance, attribution, standards, teaching approval, AI transparency, and private moderation log, see [GOVERNANCE.md](GOVERNANCE.md) and the new private [Interwoven-Projects-Moderation-Log](https://github.com/Interwoven-Projects/Interwoven-Projects-Moderation-Log) repo.

*This is the easy reference brochure for new and current members. Updates welcome via PR. Images and PDF can be generated/added as needed.*