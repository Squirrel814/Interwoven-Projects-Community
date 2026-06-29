# Interwoven Projects Governance

**Public Draft** — This document is the living governance hub for the Interwoven-Projects organization. It is intentionally posted publicly for community review and comment (see the original repository description and the pinned X community page). All members should review and provide feedback via Issues or Discussions. Squirrel814 (creator and current Enforcement Moderator) has final say on foundational changes during the draft phase.

This document incorporates and formalizes the rough draft in [Community-Framework.md](Community-Framework.md) (X spaces policies and proposed moderation roles). It expands on the existing [ATTRIBUTION.md](ATTRIBUTION.md), [docs/attribution-guidelines.md](docs/attribution-guidelines.md), [CONTRIBUTING.md](CONTRIBUTING.md), and [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).

## Core Principles

1. **Free Core Materials** — All repository content (handbooks, labs, checklists, code, templates, pathways, infographics) in Interwoven-Projects repositories **must remain permanently free to access, use, fork, and improve**. No paywalling of core Interwoven materials is permitted.
2. **Mandatory Attribution** — "Commitment to keep all core Interwoven materials free and to credit all listed contributors in any paid product." Every paid offering, course, book, workshop, or derivative **must** prominently credit all contributors listed in the project's `ATTRIBUTION.md`, `CONTRIBUTORS.md`, or equivalent section. Credit must be visible in marketing, course descriptions, and materials.
3. **Transparent Tracking (Git History as Ultimate Source of Truth)** — Git history serves as the ultimate source of truth. This fulfills the original purpose of Interwoven-Projects: a clear way to track who contributed what should financial gain occur.

   **Phased Decision Process**:
   - When a project is proposed or activated, the creator(s) must decide and document (in the project proposal issue or `/projects/` entry) whether it is primarily **open-source** or **private**.
   - Anytime another person joins or a contribution is added, a **timestamped log entry** is created (using the Contribution Update issue template or a dedicated moderator log). 
   - Logs are either public (for open-source projects) or viewable only by Moderators/Admins (for private projects). Sensitive project details, IP, or proprietary information can be redacted or kept in a separate private moderator channel/issue.
   - This provides a record without putting the project at risk.

4. **Ethics and Safety** — All work and interactions must align with the Code of Conduct. Explicit ethics guidelines include:
   - Respect for all participants regardless of background or discipline.
   - No harmful, illegal, misleading, or deceptive content.
   - "Document-first" and evidence-based approaches (especially in Security-Library and education content).
   - Interdisciplinary kindness — celebrate contributions from many fields and ways of knowing.
   - **Free-core principle**: The core educational and reference materials (handbooks, labs, checklists, templates, pathways) must remain permanently free to access, use, fork, and improve with no paywalling. This is the foundational goal of Interwoven-Education and all Libraries (as clarified in your query).
   - No sexualized language, imagery, attention, or advances in any official, recorded, planned, scheduled, or course-related spaces (see Code of Conduct Scope for lounge space nuance).

5. **Moderation Hierarchy and Responsibilities** (formalizing [Community-Framework.md](Community-Framework.md)):
   - **Administrator** (Squirrel814): Final decision-making, Enforcement Moderator role, overall oversight.
   - **Ethics Enforcer**: Promote non-biased behavior, co-host spaces, handle warnings/mutes/expulsions, delete/report anti-community content.
   - **Facilitator**: Curate speaker lineups, host Lounge Spaces (goal: 24/7 coverage), intervene subtly in unbalanced conversations, archive key insights.
   - **Welcomer**: Hold open-mic/Q&A spaces, monitor facilitated spaces as co-host, verify respectful nature of new speakers in Lounge Spaces.
   - **Scheduler/Audits**: Prioritize scheduling to meet community goals, audit for DEI representation, refine via anonymous surveys.
   - **Community Ambassador**: Represent community externally, build partnerships with aligned groups.
   - **Junior Mod**: Sponsored/trained by current moderators; assist with above duties.
   
   **Future possible roles** (brainstorm for later expansion, not adding now):
   - **Technical Reviewer**: Code, architecture, and security audits for projects and libraries.
   - **Content Curator**: Maintains quality, updates handbooks/libraries, ensures consistency across subjects.
   - **DEI Auditor**: Reviews for inclusive representation, runs anonymous surveys, refines policies.
   - **Legal/Ethics Advisor**: Reviews for compliance, IP, and ethical AI use.
   - **Event Coordinator**: Manages official classes, recorded spaces, and scheduling.
   - **Library Maintainer (per-subject)**: Owns day-to-day updates for a specific Interwoven-[Subject]-Library.
   - **AI Ethics Specialist**: Tracks tool use, documents model strengths/weaknesses, updates Community Libraries with best practices and do's/don'ts.

**Private Moderators Repository**: To handle sensitive community concerns, moderation decisions, action logs, and moderator coordination without public exposure, create a **private repository `Interwoven-Projects-Moderation-Log` under the Interwoven-Projects organization** (access restricted to approved moderators/admins only; add collaborators with Admin or Maintain permission). Use issues for logging decisions, sensitive reports, and notifications so the team stays informed at a glance. This keeps everything auditable and secure while protecting privacy. Private issues in the main repo (now enabled per your confirmation) can supplement it. 

A local stub with initial README, CODEOWNERS, and .gitignore has been created in `../Interwoven-Projects-Moderation-Log/`. Create the remote private repo on GitHub under the organization, then run from the local folder:

```powershell
git init
git add .
git commit -m "Initial moderation log repository per GOVERNANCE.md"
git remote add origin https://github.com/Interwoven-Projects/Interwoven-Projects-Moderation-Log.git
git branch -M main
git push -u origin main
```

Link from this GOVERNANCE.md: [Moderation-Log Repository](https://github.com/Interwoven-Projects/Interwoven-Projects-Moderation-Log).

**Recommendation**: Under the **Interwoven-Projects organization** (consistent with community branding and easier to add other moderators as collaborators). A personal Squirrel814 repo would also work but is less ideal long-term.

## Approval Process for Teaching, Official Classes, or Monetization

There is **no automatic qualification**, even for major contributors to a specific course or project. A formal process protects community standards, reputation, and the free-core principle. (The "Teaching Approval Request" issue template has been added in `.github/ISSUE_TEMPLATE/teaching-approval-request.md`.)

### Teaching / Monetization Approval Request
- Submit a **"Teaching Approval Request"** issue in this Community repository.
- **Required Information**:
  - Which course/project/library the teaching relates to.
  - Your prior contributions (linked to ATTRIBUTION records or PRs) or explanation of relevant experience.
  - Description of the proposed paid offering (class format, pricing transparency, how core free materials will be referenced and kept free).
  - Explicit commitment statement: "Commitment to keep all core Interwoven materials free and to credit all listed contributors in any paid product."
- **Review Criteria** (applied by Admins/Moderators):
  - Good-faith participation in the community (not necessarily direct contribution to that exact material).
  - Demonstrated alignment with values (attribution, free-core, ethics, quality of prior work).
  - No conflicts of interest or risk of misleading students.
- **Who Approves**: Squirrel814 (creator and Enforcement Moderator) or designated Moderators. Approval requires at least one moderator sign-off. Non-contributors *can* be approved if they meet the criteria (this allows experienced educators to teach official classes).
- **Outcome**: Approved instructors are listed in a central "Approved Instructors" section (maintained in this repo). The class can be listed/scheduled as official by the community. Approval can be revoked for violations.

This process applies uniformly to Education, Libraries, and other projects. **Content Submission** (PRs to Libraries, Education, or other repos) remains separate and follows the standard CONTRIBUTING.md process — no special approval needed beyond normal review and attribution update. Only the *teaching/monetization* step requires the formal request.

## Standards for Libraries and Education

See:
- [standards/LIBRARY-STANDARDS.md](standards/LIBRARY-STANDARDS.md)
- [standards/EDUCATION-STANDARDS.md](standards/EDUCATION-STANDARDS.md)

All standards are maintained in this Community repo so approvals and consistency flow through one place.

## Enforcement

See [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) for detailed **Community Impact** guidelines and *Example Actions*. The Enforcement Moderator (Squirrel814) coordinates with the moderation team defined above. Different levels of enforcement (Correction, Warning, Temporary Ban, Permanent Ban) are based on the severity of Community Impact. A private moderators repository is recommended for logging sensitive actions and keeping the team informed without public exposure.

## AI / Tool-assisted Work (Transparency)

If significant work was done with AI tools (including personal agents or models like Grok), we note the human guidance, curation, and final responsibility. The human(s) who directed, verified, and took ownership of the work receive primary credit. We strongly encourage citing the specific models and/or personal agents used (e.g. "Grok 4.3 assisted with initial drafting under human direction and review"). 

This supports one of our core goals: tracking ethical AI use, sharing strengths and weaknesses of current models, and updating our Community Libraries with proven do's and don'ts plus best practices for success.

## Updates to This Document

This is a living draft. Proposed changes are welcome via PR or Discussion. Major updates require Squirrel814 approval during the public review phase.

**Related Documents**
- [ATTRIBUTION.md](ATTRIBUTION.md) and [docs/attribution-guidelines.md](docs/attribution-guidelines.md)
- [CONTRIBUTING.md](CONTRIBUTING.md)
- [Community-Framework.md](Community-Framework.md) (rough draft of spaces policies and roles, now formalized here)
- Code of Conduct
- [Moderation-Log Repository](https://github.com/Interwoven-Projects/Interwoven-Projects-Moderation-Log) (private)

*Last updated: 2026-06-29. Public draft for community review. Markdown links use standard [text](url) format.*