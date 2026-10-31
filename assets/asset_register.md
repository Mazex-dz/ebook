# Asset Register

All figures, screenshots, diagrams, illustrations, and cover files required for the book. Asset IDs are referenced in the manuscript as `[FIG chNN-NN]`.

**Status:** `Planned` · `Captured` · `Edited` · `Approved` · `Placed`
**Types:** `SS` screenshot (real capture) · `DG` diagram (vector) · `IL` illustration · `CV` cover · `PR` project result screenshot

---

## 1. Capture Standards

### Screenshots (SS, PR)
- **Source:** real captures from the tested Antigravity version only. Generated images must never depict product UI.
- **Version stamp:** record Antigravity version/build, OS, and date for every capture (column below).
- **Window size:** fixed (proposed 1600 × 1000 logical px) at 2× scaling; same size for the whole book.
- **Theme:** one theme for the whole book (decide in `07_DESIGN/design_system.md`; light theme usually reproduces better in print).
- **Primary OS for captures:** to be decided (Windows or macOS); show the other OS only where UI differs.
- **Format:** PNG master, lossless. Export derivatives per `07_DESIGN/layout_specification.md`.
- **Redaction:** remove account emails, avatars, usernames in file paths, tokens, notifications.
- **Clean environment:** dedicated demo user profile, neutral sample project names, no unrelated extensions or tabs.
- **Annotations:** applied to copies, never to masters; numbered callouts per the design system.
- **Alt text:** written at capture time; describes purpose, not just appearance.
- **Naming:** `chNN_figNN_slug.png` in `05_ASSETS/screenshots/`.

### Diagrams (DG)
- Vector source (SVG or editable source file) retained in `05_ASSETS/diagrams/`.
- Text in diagrams uses book fonts; legible at EPUB minimum width.
- Meaning must not rely on color alone.

### Illustrations (IL)
- Conceptual only (chapter openers, part dividers). No fake UI, no fake logos, no real people's likenesses.
- If AI-generated: record tool, date, and license/terms permitting commercial use.

---

## 2. Asset List

### Front matter / Introduction

| ID | Type | Description | Status | Version/OS/Date |
|---|---|---|---|---|
| intro-01 | DG | The six-step workflow: brief → plan → build → verify → improve → publish | Planned | — |
| intro-02 | PR | Montage of the three finished projects | Planned | |
| intro-03 | DG | Callout legend (Verified, Recommendation, Workflow Tip, Warning, Version Note) | Planned | — |

### Chapter 1 — What AI Agents Can and Cannot Do

| ID | Type | Description | Status | Version/OS/Date |
|---|---|---|---|---|
| ch01-01 | DG | Autocomplete vs. chat assistant vs. agent (capabilities comparison) | Planned | — |
| ch01-02 | DG | Agent loop: goal → plan → act (edit/run) → observe → revise | Planned | — |
| ch01-03 | DG | Where humans stay in the loop (review points) | Planned | — |
| ch01-04 | IL | Chapter opener | Planned | — |

### Chapter 2 — Set Up Google Antigravity

| ID | Type | Description | Status | Version/OS/Date |
|---|---|---|---|---|
| ch02-01 | SS | Official download page | Planned | |
| ch02-02 | SS | Installer (Windows) | Planned | |
| ch02-03 | SS | Installer (macOS) | Planned | |
| ch02-04 | SS | First launch / sign-in screen (redacted) | Planned | |
| ch02-05 | SS | Onboarding choices (if any) | Planned | |
| ch02-06 | SS | Main interface, annotated with numbered regions | Planned | |
| ch02-07 | SS | Opening a folder as a workspace | Planned | |
| ch02-08 | SS | Where to find the version number | Planned | |
| ch02-09 | DG | Map of Antigravity surfaces (IDE / desktop app / CLI) — only after AG-009 verified | Planned | — |

### Chapter 3 — Your First Agent Conversation

| ID | Type | Description | Status | Version/OS/Date |
|---|---|---|---|---|
| ch03-01 | SS | Starting a new conversation | Planned | |
| ch03-02 | SS | Typing a first prompt | Planned | |
| ch03-03 | SS | `@` mention menu attaching a file | Planned | |
| ch03-04 | SS | Agent response with an artifact | Planned | |
| ch03-05 | SS | Proposed change shown as a diff | Planned | |
| ch03-06 | SS | Accepting / rejecting a change | Planned | |
| ch03-07 | SS | Model selector (only if AG-015 verified) | Planned | |

### Chapter 4 — Stay in Control: Permissions, Review, and Git

| ID | Type | Description | Status | Version/OS/Date |
|---|---|---|---|---|
| ch04-01 | SS | Settings: command execution policy | Planned | |
| ch04-02 | SS | Settings: file access and internet access policies | Planned | |
| ch04-03 | SS | Settings: artifact review mode | Planned | |
| ch04-04 | SS | Agent requesting approval to run a command | Planned | |
| ch04-05 | SS | Source control view after an agent change | Planned | |
| ch04-06 | SS | Terminal: `git diff` / `git log` output | Planned | |
| ch04-07 | DG | Commit-before-change safety loop | Planned | — |
| ch04-08 | DG | Risk vs. autonomy matrix for permission settings | Planned | — |

### Chapter 5 — Write Briefs Agents Can Follow

| ID | Type | Description | Status | Version/OS/Date |
|---|---|---|---|---|
| ch05-01 | DG | Anatomy of a project brief | Planned | — |
| ch05-02 | SS | Weak prompt and resulting output | Planned | |
| ch05-03 | SS | Strong brief and resulting output | Planned | |

### Chapter 6 — Plan Before You Build

| ID | Type | Description | Status | Version/OS/Date |
|---|---|---|---|---|
| ch06-01 | SS | Enabling/choosing planning mode | Planned | |
| ch06-02 | SS | A generated plan artifact | Planned | |
| ch06-03 | SS | Commenting on / revising a plan | Planned | |
| ch06-04 | SS | Task list progressing during execution | Planned | |
| ch06-05 | DG | Breaking a feature into verifiable steps | Planned | — |

### Chapter 7 — Verify Everything: Testing Agent Work

| ID | Type | Description | Status | Version/OS/Date |
|---|---|---|---|---|
| ch07-01 | SS | Local dev server running in the terminal | Planned | |
| ch07-02 | SS | Agent-driven browser test in progress | Planned | |
| ch07-03 | SS | Browser screenshot/recording evidence artifact | Planned | |
| ch07-04 | SS | Browser setup/extension prompt (if AG-051 requires) | Planned | |
| ch07-05 | SS | Reviewing a diff with an error highlighted | Planned | |
| ch07-06 | SS | Validation or test results output | Planned | |
| ch07-07 | DG | Verification ladder: run → inspect → test → criteria | Planned | — |

### Chapter 8 — Customize Your Agent: Rules and Skills

| ID | Type | Description | Status | Version/OS/Date |
|---|---|---|---|---|
| ch08-01 | SS | Customizations panel / settings | Planned | |
| ch08-02 | SS | Workspace `.agents/` folder structure in explorer (if AG-031 verified) | Planned | |
| ch08-03 | SS | Example rule file | Planned | |
| ch08-04 | SS | Example `SKILL.md` | Planned | |
| ch08-05 | SS | Agent applying a rule (before/after) | Planned | |
| ch08-06 | DG | How rules, skills, workflows, and MCP relate | Planned | — |

### Chapter 9 — Project 1: Personal Portfolio

| ID | Type | Description | Status | Version/OS/Date |
|---|---|---|---|---|
| ch09-01 | DG | Site map and section wireframe | Planned | — |
| ch09-02 | SS | Project brief in the workspace | Planned | |
| ch09-03 | SS | Agent plan for the portfolio | Planned | |
| ch09-04 | PR | First generated version (desktop) | Captured | Chrome 1280x850 / Windows / 2026-10-26 |
| ch09-05 | PR | Revised version after review (desktop) | Planned | |
| ch09-06 | PR | Mobile view | Captured | Chrome 390x844 / Windows / 2026-10-26 |
| ch09-07 | SS | Accessibility check results | Planned | |
| ch09-08 | PR | Final result | Captured | Chrome 1280x850 / Windows / 2026-10-26 |

### Chapter 10 — Project 2: Small Business Website

| ID | Type | Description | Status | Version/OS/Date |
|---|---|---|---|---|
| ch10-01 | DG | Page structure and navigation map | Planned | — |
| ch10-02 | SS | Brief and plan | Planned | |
| ch10-03 | PR | Home page (desktop + mobile) | Captured | Chrome 1280x850 & 390x844 / Windows / 2026-10-26 |
| ch10-04 | PR | Services / about pages | Captured | Chrome 1280x900 / Windows / 2026-10-26 |
| ch10-05 | PR | Contact form and success state | Captured | Chrome 1280x850 / Windows / 2026-10-26 |
| ch10-06 | SS | Page source showing meta tags | Planned | |
| ch10-07 | PR | Final result / About page | Captured | Chrome 1280x850 / Windows / 2026-10-26 |
| ch10-08 | IL | Fictional business imagery (licensed or generated, non-UI) | Planned | — |

### Chapter 11 — Project 3: A Web Application

| ID | Type | Description | Status | Version/OS/Date |
|---|---|---|---|---|
| ch11-01 | DG | App architecture (UI, state, storage) | Planned | — |
| ch11-02 | DG | User flow | Planned | — |
| ch11-03 | SS | Brief and plan | Planned | |
| ch11-04 | PR | Empty state / Kanban Board View | Captured | Chrome 1366x850 & 390x844 / Windows / 2026-10-26 |
| ch11-05 | PR | Core feature in use | Planned | |
| ch11-06 | PR | Error state | Planned | |
| ch11-07 | SS | Automated tests passing | Planned | |
| ch11-08 | SS | Iteration: plan for a new feature | Planned | |
| ch11-09 | PR | Final result | Planned | |

### Chapter 12 — Debug and Improve with Agents

| ID | Type | Description | Status | Version/OS/Date |
|---|---|---|---|---|
| ch12-01 | SS | Real error in terminal/browser console | Planned | |
| ch12-02 | SS | Giving the agent an error and reproduction steps | Planned | |
| ch12-03 | SS | Agent's fix as a diff | Planned | |
| ch12-04 | SS | Reverting a bad change with Git | Planned | |
| ch12-05 | DG | Debugging loop: reproduce → isolate → fix → verify | Planned | — |

### Chapter 13 — Publish Your Project

| ID | Type | Description | Status | Version/OS/Date |
|---|---|---|---|---|
| ch13-01 | DG | Local → repository → host flow | Planned | — |
| ch13-02 | SS | Pre-publish checklist run | Planned | |
| ch13-03 | SS | Hosting provider setup steps (after approval; redacted) | Planned | |
| ch13-04 | PR | Published site in browser (test site) | Planned | |

### Chapter 14 — Working Responsibly

| ID | Type | Description | Status | Version/OS/Date |
|---|---|---|---|---|
| ch14-01 | DG | Responsible-use checklist (disclosure, licensing, privacy) | Planned | — |
| ch14-02 | DG | Freelance client workflow with agent checkpoints | Planned | — |

### Part dividers and design elements

| ID | Type | Description | Status |
|---|---|---|---|
| part-01 – part-04 | IL | Part divider illustrations (Foundations, Workflow, Projects, Shipping) | Planned |
| ch-openers | IL | Chapter opener style (one per chapter or a consistent motif) | Planned |
| icons | IL | Callout icons (5) | Planned |

### Cover

| ID | Type | Description | Status |
|---|---|---|---|
| cv-01 | CV | 2–3 cover concepts for approval | Planned |
| cv-02 | CV | Final front cover, e-book (size per sales channel, e.g., 1600 × 2560 px; verify channel specs) | Planned |
| cv-03 | CV | Thumbnail legibility test (small sizes) | Planned |
| cv-04 | CV | Marketing mockup (optional) | Planned |
| cv-05 | CV | Print wrap (only if print edition approved) | Planned |

> [!NOTE]
> The cover must not use Google or Antigravity logos unless official brand guidelines permit it (claim AG-063).

---

## 3. Totals (planned)

| Type | Count |
|---|---|
| Screenshots (SS) | 52 |
| Project results (PR) | 14 |
| Diagrams (DG) | 20 |
| Illustrations (IL) | ~25 (incl. openers, dividers, icons) |
| Cover files (CV) | 5 |
