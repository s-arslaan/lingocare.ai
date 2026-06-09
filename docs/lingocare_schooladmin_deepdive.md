# Lingocare — School Admin Deep-Dive
### Navigation · Page Anatomy · Connected Flows

**Version:** 1.0 · June 2026  
**Part of:** Lingocare Application Document Series  
**Related files:** App Vision v2 · Learner Deep-Dive v2 · Instructor Deep-Dive v2  
**This document covers:** The School Admin — what they see, where they go, how everything connects  
**Language note:** Document in English. App UI in German. German curriculum and nursing terms preserved throughout (*Themenfeld, Unterrichtseinheit, Lehrplan, Pflegefachassistenz*, etc.).
---

## Contents

1. [The School Admin's Real Problems — JTBD](#1-the-school-admins-real-problems--jtbd)
2. [Who the School Admin Actually Is](#2-who-the-school-admin-actually-is)
3. [Simple on the Surface. Powerful Underneath.](#3-simple-on-the-surface-powerful-underneath)
4. [The Navigation Sidebar](#4-the-navigation-sidebar)
5. [Page Anatomy — What Each Screen Contains](#5-page-anatomy--what-each-screen-contains)
6. [Lingo — Agentic AI for School Operations](#6-lingo--agentic-ai-for-school-operations)
7. [How Everything Connects — The Workflows](#7-how-everything-connects--the-workflows)
8. [The Cross-Surface Principle](#8-the-cross-surface-principle)

---

## 1. The School Admin's Real Problems — JTBD

### Job 1: Know whether the school is on track — without asking anyone

**The problem:** At any given moment, a school director's picture of the school is assembled from conversations, emails, and manually updated spreadsheets. "Is Block 2 on schedule for all classes?" requires contacting three teachers and checking two documents. By the time the answer arrives, a week has passed.

**What Lingocare does:** The School Admin dashboard gives an always-current picture: which programmes are on track, which classes are behind, which teachers have flags, how many learners are at risk — all from one screen, no asking required. Clicking into any widget reveals depth. Ask Lingo the same question in plain language and get an answer in seconds.

---

### Job 2: Manage teacher workload without over- or under-scheduling anyone

**The problem:** Teacher burnout is real and preventable — but most schools have no tool that shows workload against contracted hours. An overloaded teacher produces worse lessons, takes more sick leave, and eventually leaves. The school director finds out after the damage is done.

**What Lingocare does:** The Teachers page shows every teacher's scheduled hours vs. contracted hours, colour-coded by status. Lingo surfaces the imbalance proactively: "Belinda Kleinhans has 47 hours planned this month against a 40-hour contract." The administrator can rebalance assignments before it becomes a problem.

---

### Job 3: Fill teaching gaps immediately when someone is absent

**The problem:** A teacher calls in sick on Monday morning. Three classes are affected today. The school director has to call around, check availability, and manually update class assignments — all before 09:00. This happens multiple times a term.

**What Lingocare does:** Marking a teacher as absent triggers Lingo to flag the affected sessions immediately: "Belinda is on leave Monday–Wednesday. 3 sessions affected." Lingo checks available teacher schedules, suggests replacements based on topic expertise and current workload, and with one confirmation assigns the replacement — notifying the substitute and the affected learners automatically.

---

### Job 4: Plan and update the curriculum without a spreadsheet

**The problem:** Curriculum planning happens in Excel. When dates shift, teacher assignments change, or blocks get reorganised, the spreadsheet has to be manually updated — and those changes don't automatically flow anywhere. Teachers may not be notified. Calendars are not updated. Nothing is connected.

**What Lingocare does:** The full-edit curriculum view in Programs is the single place where the school's academic plan lives. Every change — add a block, move a lesson, assign a teacher to a *Themenfeld* — immediately reflects in the teacher's Lingocare calendar and syncs to their connected external calendar (Google or Outlook). The plan and the schedules are one thing, not two.

---

### Job 5: Control exactly who can access and do what — without IT support

**The problem:** Schools hire a range of roles: instructors, coordinators, content creators, administrative staff. Each role needs different levels of access. Currently, either everyone has the same access (too permissive) or access requests go through the school's IT department (too slow).

**What Lingocare does:** The Team & Roles page is a fully self-service RBAC (role-based access control) panel. The school admin creates custom roles, defines their permissions across every feature area, and assigns them to staff — without contacting Lingocare or IT. A "Content Creator" role with access only to the Studio and Library takes two minutes to configure.

---

### Job 6: Spot at-risk learners and programmes before they become a crisis

**The problem:** A school director typically discovers a problem — a class falling behind, a cohort of at-risk learners, an instructor whose class is performing poorly — at a formal review. By then, the window for early intervention has closed.

**What Lingocare does:** School-wide Analytics shows dropout risk trends, programme completion rates, and learner at-risk counts across all classes — updated continuously. Lingo surfaces the critical ones proactively, without the director having to query the data: "3 classes in Programme 2 are unlikely to finish Block 2 before the scheduled exam at current pace."

---

### Job 7: Assign and track tasks to staff without email chains

**The problem:** "Please make sure KI1-LU3 materials are published before the 3rd" goes into an email. Whether it was actioned lives in the reply chain. Nothing is tracked. Nothing is visible.

**What Lingocare does:** From the Lingo chat or from any page, the school admin can assign actions to specific staff members — directly in the platform. "Material for KI1-LU3 hasn't been published — class starts in 8 days. Want to notify the responsible instructor?" One tap. The instructor receives a notification in their Startseite. Completion is trackable.

---

### Job 8: Get onboarding and ongoing support without a support ticket queue

**The problem:** When something is unclear about how the platform works, the answer takes a support ticket, a response cycle, and time the school admin does not have. New staff need onboarding guidance that doesn't require a training day.

**What Lingocare does:** The Help section is a searchable knowledge base built for Lingocare specifically — not generic software help. Every article has a "Want more help?" button that sends a direct form to the Lingocare team. For questions answerable within the app, Ask Lingo explains how anything works in plain language. For complex operational questions, the response goes to a human at Lingocare.

---

## 2. Who the School Admin Actually Is

**Junis Braun, 48, School Director.** Runs a medium-sized *Pflegeschule* with three programmes (*Pflegefachassistenz, Altenpflegehilfe, Sozialbetreuung*), 12 instructors, and 240 learners across eight classes. His day is 40% administration and 60% management — he wants that ratio inverted. He lives in the Analytics page and Ask Lingo. He does not touch the Content Studio — that is his instructors' territory.

**Sarah Müller, 35, Deputy Head and curriculum coordinator.** Her job is building and maintaining the academic year plan. She uses the Programs page more than anyone else at the school. The teacher schedule overlay in Calendar is her most-used feature — she checks it every Monday to see who is teaching what and whether anything conflicts.

**Klaus-Peter Fischer, 52, sole director of a small Pflegeschule.** Two programmes, four instructors, 60 learners. He is the School Admin, HR manager, and curriculum coordinator in one person. He uses every part of the platform but needs everything to be fast — he has no time for complex workflows.

---

## 3. Simple on the Surface. Powerful Underneath.

This principle applies to every role in Lingocare. For the School Admin, it is especially important to state explicitly because the depth of the platform could be overwhelming if the surface presented everything at once.

**What the school admin sees first:** A clean dashboard with five widgets, three numbers per widget, and Ask Lingo. That is it.

**What clicking into any widget reveals:** Full detail, full history, full controls.

**What Ask Lingo unlocks without clicking into anything:** Insights, actions, reports, and cross-system operations — all in plain language, all with one-tap confirmation.

The surface is the school director checking in. The depth is a full operational system. The AI is the bridge between them. The school admin should never have to go looking for something they cannot name — they ask Lingo, and Lingo either answers or navigates.

---

## 4. The Navigation Sidebar

Fixed left sidebar on desktop. Collapsed icon rail on tablet. Bottom navigation on mobile. School admin's name, school name, and date always visible at the top.

```
────────────────────────────────────────────
  Hi Junis 👋
  Pflegeschule Frankfurt
  School Admin  ·  Thu 28 May
────────────────────────────────────────────

  🏠  Home                   (Startseite)

  📅  Calendar               (Kalender)

  ─── MY SCHOOL ──────────────────────────
  📚  Programs               (Programme)
  👩‍🏫  Teachers              (Lehrkräfte)
  🧑‍🎓  Learners              (Lernende)

  ─── MANAGE ─────────────────────────────
  📊  Analytics              (Auswertungen)

  ─── ADMIN ──────────────────────────────
  👥  Team & Roles           (Team & Rollen)
  ⚙️  Settings               (Einstellungen)

  ─── SUPPORT ────────────────────────────
  ❓  Help                   (Hilfe)

────────────────────────────────────────────
  [🦦 Ask Lingo — always visible]
────────────────────────────────────────────
```

**What each item is:**

`Home` — School overview. Five widgets showing teachers, programmes, learners, calendar snapshot, and Ask Lingo. Starts simple. Everything clickable for depth.

`Calendar` — Personal + school calendar with teacher schedule overlay. Google/Outlook integration. The scheduling command centre.

`Programs` — All active programmes at this school. Each opens a full curriculum view with edit mode for planning and teacher assignment.

`Teachers` — Full teacher roster: workload, schedule, leave management, performance signals, replacement flow.

`Learners` — All learners across the school. Enrollment management, at-risk view, programme assignment.

`Analytics` — School-wide performance. Programme completion, learner outcomes, engagement trends, teacher workload overview.

`Team & Roles` — Staff accounts, role definitions, and granular permission configuration. The RBAC control panel.

`Settings` — School profile, calendar integrations, notification preferences, programme defaults.

`Help` — Searchable knowledge base, guides, direct contact form to Lingocare.

**The floating Ask Lingo button:** Always in the bottom-right corner. Tapping opens a full-panel Lingo chat — context-aware of the current page. On the Home dashboard, Lingo already knows the state of the school. On the Teachers page, Lingo knows who is being viewed.

---

## 5. Page Anatomy — What Each Screen Contains

### 5.1 Home (Startseite) — School Overview with Widgets

The school admin's daily starting point. At a glance, the state of the entire school. Simple surface, deep on click.

```
────────────────────────────────────────────────────────────────
  Good morning, Junis ☀️
  Pflegeschule Frankfurt · Thu 28 May

  ─── OVERVIEW ────────────────────────────────────────────────
  [3 Programmes]   [12 Teachers]   [240 Learners]   [78% On Track]
    → Click any stat for full detail

  ─── WIDGETS ─────────────────────────────────────────────────

  ┌─────────────────────────────┐  ┌─────────────────────────────┐
  │  👩‍🏫 TEACHERS               │  │  📚 PROGRAMMES               │
  │                             │  │                             │
  │  Active:         10         │  │  PFA Hessen  ████░░  74%    │
  │  On leave:        1         │  │  APH Hessen  ██████  88%    │
  │  Flags:           2         │  │  SBP Hessen  ███░░░  51%    │
  │    ⚠ Belinda — overloaded   │  │                             │
  │    ⚠ Thomas — 3 gaps Jul    │  │  [View all programmes →]    │
  │  [View all teachers →]      │  │                             │
  └─────────────────────────────┘  └─────────────────────────────┘

  ┌─────────────────────────────┐  ┌─────────────────────────────┐
  │  🧑‍🎓 LEARNERS               │  │  📅 CALENDAR                 │
  │                             │  │                             │
  │  Total enrolled:      240   │  │  Today:                     │
  │  Active this week:    196   │  │  09:00 Class 9B · KI1 PF2   │
  │  At risk:              14   │  │  11:00 Class 8A · AD1 PF1   │
  │  Inactive (7+ days):   22   │  │  14:00 Class 10C · BD1 PF3  │
  │                             │  │                             │
  │  [View at-risk learners →]  │  │  [Open full calendar →]     │
  └─────────────────────────────┘  └─────────────────────────────┘

  ┌────────────────────────────────────────────────────────────┐
  │  🦦 ASK LINGO                                              │
  │  Your AI for the entire school — insights, actions, checks │
  │                                                            │
  │  > Show me the state of the school this week               │
  │  > Who has unassigned classes in July?                     │
  │  > Which programmes are behind schedule?                   │
  │  > Are there any material gaps before next week?           │
  │                                                            │
  │  [Type anything or tap a suggestion above]                 │
  └────────────────────────────────────────────────────────────┘
```

**The Ask Lingo widget on the dashboard is larger and more prominent** than on instructor or learner dashboards. The school admin's role requires more cross-system queries, and Lingo is the interface through which most complex operations happen.

**Every widget number is clickable.** Tapping "14 at risk" in the Learners widget opens the Learners page filtered to at-risk. Tapping "2 flags" in the Teachers widget opens the Teachers page filtered to flagged staff. The dashboard is a navigation shortcut to everything, not just a display.

---

### 5.2 Calendar (Kalender) — School Schedule + Teacher Overlay

The scheduling command centre. The school admin's personal calendar, the school's event calendar, and the ability to overlay any teacher's schedule — all in one view.

**Calendar view modes:**
- Day · Week (default) · Month
- Personal events + school events shown by default

**Left sidebar — Teacher Schedule Panel:**

```
─── Teacher Schedules ────────────────
🔍 Search teachers...

☐ 🟠 Belinda Kleinhans
☐ 🔵 Thomas Brandt
☐ 🟢 Laura Hoffmann
☑ 🟣 Fatima Al-Rashidi      ← checked = overlay visible
☐ 🟡 Klaus Weigand
☐ 🔴 Maria Steinberg
...

[All]  [On leave]  [Flagged]
─────────────────────────────────────
```

Each teacher has a unique colour. Checking a teacher adds their schedule as a coloured overlay on the calendar. Multiple teachers can be checked simultaneously — their events stack visually, so the admin can instantly see overlaps, conflicts, and free slots.

**Reading the overlaid calendar:**
- Solid coloured blocks: scheduled teaching sessions
- Striped blocks: personal calendar events (pulled from connected Google/Outlook — event title visible to admin, details private)
- Grey blocks: marked leave / unavailability
- Empty slots: available for assignment

**Tapping a teacher's calendar event:**
Opens an event card:
- Session details: class, LU/PF, room, time
- Assigned teacher: with "Reassign" option
- Learner count for this session
- "Open class in Analytics" link

**Creating a school event:**
Tap any empty slot → create event:
- Title, date, time, type (class session, meeting, administrative, school-wide)
- Assign to teacher(s) (multi-select from staff list)
- "Notify assigned teachers" toggle
- If type = class session: link to LU/PF in the programme
- On save → event appears in teacher's Lingocare calendar AND syncs to their connected external calendar if integration is enabled

**Calendar integrations:**
Banner at top of calendar:
```
📅 Connected: Google Calendar (Junis Braun) ✓
📅 Connected: Microsoft Outlook (School events) ✓
[Manage integrations →]
```

When an instructor has connected their own Google or Outlook calendar to Lingocare, their external events (shown as striped blocks to the school admin, title only — no details) are visible in the overlay. This lets the admin know a teacher is unavailable without breaching their personal calendar privacy.

**Leave management from Calendar:**
Right-click or long-press any teacher's slot → "Mark as leave" → sets leave for that period → Lingo immediately runs: *"Belinda is marked on leave. 3 sessions are affected. Want me to suggest replacements?"*

---

### 5.3 Programs (Programme) — Curriculum Ownership

Every academic programme at the school lives here. This is where the year is built, maintained, and connected to the teaching team.

**Entry view — Programme cards:**

```
Programme — Pflegeschule Frankfurt

┌──────────────────────────────────┐  ┌──────────────────────────────────┐
│  📚 PFA Hessen                   │  │  📚 APH Hessen                   │
│  Pflegefachassistenz             │  │  Altenpflegehilfe                │
│  12 months · 3 active classes    │  │  10 months · 2 active classes    │
│  Block 2 of 6 · ████░░░░ 42%     │  │  Block 3 of 5 · ██████░░ 62%    │
│  4 assigned teachers             │  │  3 assigned teachers             │
│  [Open programme →]              │  │  [Open programme →]              │
└──────────────────────────────────┘  └──────────────────────────────────┘

┌──────────────────────────────────┐
│  📚 SBP Hessen                   │
│  Sozialbetreuung Pflege          │
│  8 months · 2 active classes     │
│  Block 3 of 4 · ███░░░░░ 38%    │
│  2 assigned teachers             │
│  [Open programme →]              │
└──────────────────────────────────┘

[+ Create new programme]
```

---

**Inside a programme — Curriculum View with Full Edit Mode**

This is the school admin's version of the *Lehrplan* page. It starts in read mode (same as instructors see). A prominent button unlocks full edit mode.

```
Programme: PFA Hessen · Pflegefachassistenz
Class: [ All classes ▾ ] or [ Klasse 9B ▾ ]

[Full Edit Mode 🖊]  ← top right, always visible
────────────────────────────────────────────────────────────────

READ MODE (default):
Block 1 · Jan–Mar · ████████░░ 81%
Block 2 · Apr–Jun · ████░░░░░░ 42%  [expanded]
  └── Themenfeld: Kommunikation & Interaktion · Apr 12 – Jun 15
        Assigned teacher: Belinda Kleinhans  ·  [Change teacher]
        └── Unterrichtseinheit · May 26  [Tue 09:00 · Belinda]
              ├── LU: KI1-LU1  ● ○ ○ ○  (Klasse 9B)
              ├── LU: KI1-LU2  ○ ○ ○ ○
              └── Praxiseinheit 🧪
Block 3 · Jul–Sep  ⚠ 3 Unterrichtseinheiten have no teacher assigned
```

**Entering Full Edit Mode:**

```
[Full Edit Mode 🖊] toggled ON

─── EDITING: PFA Hessen · Block 2 ───────────────────────────────
⚠ Unsaved changes will not take effect until you publish.
[Discard changes]  [Publish changes ✓]

All blocks, Themenfelder, Unterrichtseinheiten, and LUs are now:
• Drag-and-drop rearrangeable
• Editable (click to rename, change dates)
• Addable (+ buttons throughout)
• Teacher-assignable (teacher field on every Themenfeld and Unterrichtseinheit)

Block 2 · Apr–Jun  [🖊 Rename]  [📅 Change dates]  [+ Add Themenfeld]  [× Remove]
  └── Themenfeld: Kommunikation & Interaktion  [🖊]  [📅]  [+ Add Unterrichtseinheit]
        Teacher: [ Belinda Kleinhans ▾ ]  ← dropdown from active staff
        └── Unterrichtseinheit · May 26  [📅 Change date]  [+ Add LU]  [× Remove]
              ├── LU: KI1-LU1  [× Remove]  [+ Add KBB]
              └── [+ Add LU from library]

[+ Add Block]
```

**When a teacher is assigned or changed in Full Edit Mode:**
- The assignment queues up as a pending change
- On "Publish changes": the teacher's Lingocare calendar is updated immediately
- If that teacher has a connected external calendar (Google/Outlook): a sync event is pushed
- A notification appears in the teacher's Startseite: "Junis has updated your teaching assignment for Block 2 PFA. See your updated schedule."

**Lingo in Full Edit Mode:**
Ask Lingo is context-aware during editing:
- "Which teachers are available for Block 3 Themenfeld AD2?" → Lingo checks schedules and workload, shows available + recommended options
- "Check Block 3 for gaps" → Lingo scans the block, lists *Unterrichtseinheiten* with no teacher, no materials, or missing LUs
- "Who should cover the July 28 session?" → Lingo checks that date, suggests based on availability + expertise

---

### 5.4 Teachers (Lehrkräfte) — Roster, Workload, and Scheduling

**Entry view — teacher list:**

```
Teachers — Pflegeschule Frankfurt  (12 active · 1 on leave)

[🔍 Search teachers...]  [Filter: All | Active | On leave | Flagged]
[+ Invite teacher]

Name                  Classes  Hours/mo  Contract   Status      Flags
─────────────────────────────────────────────────────────────────────────
Belinda Kleinhans     3        47h       40h        🟡 Over     Overloaded
Thomas Brandt         2        38h       40h        🟢 Ok       —
Laura Hoffmann        1        22h       20h        🟢 Ok       —
Fatima Al-Rashidi     2        36h       40h        🟢 Ok       —
Klaus Weigand         2        41h       40h        🟡 Over     Minor
Maria Steinberg       0        —         40h        ⚫ On leave  Leave: Jun 1–12
─────────────────────────────────────────────────────────────────────────
[Click any row → teacher detail]
```

**Inside a teacher's detail page:**

Three tabs:

*Overview:*
- Name, contact details, assigned classes and programmes
- Scheduled hours this month vs contracted hours (visual bar — red if over, green if aligned, grey if under)
- Assigned *Themenfelder* and *Unterrichtseinheiten* across all programmes
- Active leave: dates and affected sessions
- "Edit assignment" button → opens their assignments in Full Edit Mode within the relevant programme

*Schedule:*
- Mini calendar showing this teacher's scheduled sessions
- Quick view: conflicts, gaps, leave periods
- "Open in full calendar" → opens Calendar page with this teacher pre-checked in the overlay

*Signals:*
- Learner performance signals from this teacher's classes (aggregate, not individual class analytics)
- Completion rates across their assigned LUs
- Alert flags: unassigned sessions, unpublished materials approaching a deadline

**Leave management from teacher detail:**

```
[Mark leave] → date range picker → reason (optional)
→ Lingo immediately: "Maria is on leave Jun 1–12.
   2 sessions affected:
   · Jun 3: Klasse 8A · KI1 PF2
   · Jun 10: Klasse 8A · KI1 PF3
   
   Want me to suggest replacements?"
   [Yes, show options]  [I'll handle it manually]
```

```
[Yes, show options]

Lingo: "Available teachers for those dates:
  · Fatima Al-Rashidi — teaches KI cluster, 4 free hours that week
  · Thomas Brandt — available Jun 3, busy Jun 10
  · Klaus Weigand — available both dates, no KI experience

  Recommended: Fatima for both sessions.
  [Assign Fatima to both →]  [Assign individually]"
  
[Assign Fatima to both →]
Lingo: "This will assign Fatima Al-Rashidi to:
  · Jun 3: Klasse 8A · KI1 PF2
  · Jun 10: Klasse 8A · KI1 PF3
  
  Fatima and affected learners will be notified. Confirm?"
  [Confirm]  [Cancel]
```

---

### 5.5 Learners (Lernende) — School-wide View

Every learner enrolled at the school — across all programmes and classes.

**Entry view:**

```
Learners — Pflegeschule Frankfurt  (240 enrolled)

[🔍 Search learners...]  
Filter: [ All programmes ▾ ]  [ All classes ▾ ]  [ Status: All ▾ ]

Name             Programme      Class      Level   Last active   Status
──────────────────────────────────────────────────────────────────────────
Leila Hassan     PFA Hessen     Klasse 9B  L1      Today         🟢
Dmitri K.        PFA Hessen     Klasse 9B  L2      Yesterday     🟢
Priya M.         PFA Hessen     Klasse 8A  L2      3 days ago    🟡
Tom Becker       PFA Hessen     Klasse 9A  L2      15 days ago   🔴
Amina Traoré     APH Hessen     Klasse 4B  L1      Today         🟢
──────────────────────────────────────────────────────────────────────────
[Click any row → Learner Profile]
[Select multiple → Bulk actions: Message · Export · Move class]
```

**At-risk filter:** Selecting "At risk" shows only learners with 🟡 or 🔴 status — their name, programme, class, last active, and the specific signal (inactive / low score / missed submissions). This is the school-wide early warning view.

**Learner Profile (from school admin view):**
Identical to what instructors see — Progress, Performance, Engagement, Communication tabs — with one addition: the school admin can see which teacher is responsible for this learner's class and directly message that teacher or the learner.

**Enrollment management:**
- Add a learner to a programme: search existing learner accounts or send an invitation
- Move a learner to a different class within the same programme
- Unenroll a learner from a programme (requires confirmation)
- All enrollment changes immediately update the affected teacher's class rosters

---

### 5.6 Analytics (Auswertungen) — School-Wide Performance

The school admin's analytics spans the entire school — not a single class. The data is richer and more aggregated than what instructors see.

**Entry view — school snapshot:**

```
Analytics — Pflegeschule Frankfurt
Period: [ This month ▾ ]    Programme: [ All ▾ ]

─── School Overview ──────────────────────────────────────────────
┌────────────────────┐  ┌────────────────────┐  ┌────────────────────┐
│  78%               │  │  14                │  │  196 / 240         │
│  Avg programme     │  │  At-risk learners  │  │  Active learners   │
│  completion        │  │  across school     │  │  this week         │
└────────────────────┘  └────────────────────┘  └────────────────────┘
  [Click → programme    [Click → at-risk list]   [Click → engagement
   breakdown]                                     detail]
```

**Programme completion chart:**
Bar chart — one bar per programme (PFA Hessen, APH Hessen, SBP Hessen), showing average LU completion rate across all classes. Clickable to drill into per-class breakdown within that programme.

**Learner outcomes trend:**
Line chart showing active learner percentage and at-risk count week-over-week for the last 8 weeks. Allows the admin to see whether things are improving or deteriorating at the school level.

**Teacher workload overview:**
Bar chart — one bar per teacher, showing scheduled hours vs contracted hours this month. Overloaded teachers appear in red. Underloaded in grey. This is an at-a-glance equity check.

**Programme-level analytics tab:**
Select any programme → see per-class completion, per-block progress, which LUs have the lowest completion rates across all classes (signals content difficulty or scheduling issues), and which classes are trailing relative to the programme schedule.

**Learner outcome tab:**
Aggregated learner performance across the school — broken down by language level (L1/L2/L3), by programme, and by block. Useful for spotting systemic issues: "L1 learners in PFA Hessen consistently score lower in Block 3 — is this a content issue or a language support gap?"

**Export:**
Any view in Analytics can be exported as a CSV or PDF report. Useful for generating reports for the *Behörde* (state regulatory body) or for internal school board reporting.

---

### 5.7 Team & Roles (Team & Rollen) — RBAC Control Panel

The full staff management and permission configuration centre. Everything about who works here and what they can do.

**Two sections: Staff Accounts + Roles**

---

**Staff Accounts:**

```
Team — Pflegeschule Frankfurt  (14 staff)
                                ← the 50-account limit is shown here only when you are reached 45 accounts and can be changed by Lingocare support if needed, but is not a number the school admin can change themselves. It's there as context but never shown in daily use

[+ Invite staff member]

Name                Role                  Last active   Status
──────────────────────────────────────────────────────────────────
Junis Braun         School Admin          Today         🟢 Active
Belinda Kleinhans   Instructor            Today         🟢 Active
Thomas Brandt       Instructor            Yesterday     🟢 Active
Laura Hoffmann      Instructor            2 days ago    🟢 Active
Fatima Al-Rashidi   Instructor            Today         🟢 Active
Klaus Weigand       Instructor            3 days ago    🟢 Active
Maria Steinberg     Instructor            8 days ago    ⚫ On leave
Anna Fuchs          Coordinator           Today         🟢 Active
Max Lehmann         Content Creator       Yesterday     🟢 Active
──────────────────────────────────────────────────────────────────
[Click any row → view/edit role + permissions]
```

**Inviting a new staff member:**
Enter email + select role → invitation sent. The recipient clicks the link, creates their account, and lands in the experience defined by their role — with exactly the access the school admin configured.

---

**Roles:**

```
Roles — Pflegeschule Frankfurt

SYSTEM ROLES (protected core — adjustable but not deletable)
─────────────────────────────────────────────────────────────────
School Admin    Full access to all school features
Instructor      Default instructor permissions  [Adjust ▾]
Learner         Default learner permissions    [Adjust ▾]

CUSTOM ROLES (school-created)
─────────────────────────────────────────────────────────────────
Coordinator     Calendar + Teacher view + Analytics read
Content Creator Studio + Content Library write
[+ Create new role]
```

**Creating a custom role — the permission matrix:**

```
New Role: Content Creator
─────────────────────────────────────────────────────────────────
Permission Area              None    View    Edit    Full
─────────────────────────────────────────────────────────────────
Programs & Curriculum         ○       ●       ○       ○
Teachers management           ●       ○       ○       ○
Learner management            ●       ○       ○       ○
School Analytics              ●       ○       ○       ○
Class Analytics               ○       ●       ○       ○
Content Studio                ○       ○       ●       ○   ← can create & edit
Content Library               ○       ○       ●       ○   ← can publish own
Scheduling                    ●       ○       ○       ○
Team & Roles                  ●       ○       ○       ○
Settings                      ●       ○       ○       ○
Help                          ○       ●       ○       ○
─────────────────────────────────────────────────────────────────
[Save role]  [Cancel]
```

**Adjusting the Instructor role:**
The Instructor role has a set of default permissions that can be adjusted by the school admin without creating a custom role. Examples:
- Disable the ability to create new content from scratch (restrict to editing existing)
- Restrict Analytics to their own classes only (already default, but can be loosened)
- Enable or disable the ability to invite learners

**Adjusting the Learner role:**
The school admin can turn specific learner features on or off for their school:
- Class Leaderboard: on by default, can be turned off if the school prefers non-competitive learning
- Language Garden: on by default, can be restricted to during-school-hours only
- Knowledge Garden: on by default, always on

**Privacy-protected areas — never configurable:**
Regardless of what permissions are granted, these areas remain private and are not accessible by any role other than the individual themselves:

> *The following are always private and cannot be unlocked by role configuration:*
> - *Learner self-study activity (voluntary KBB completions, Language Practice sessions)*
> - *Instructor private notes on learner profiles*
> - *Unpublished drafts in Content Studio*
> - *Learner personal profile settings (language level, mother tongue)*

---

### 5.8 Settings (Einstellungen) — School Configuration

**School profile:**
- School name, address, contact details
- School logo (used in the platform header and any generated reports)
- Timezone (auto-set to Europe/Berlin for German schools, adjustable)
- Academic year start and end dates (used by Calendar and Analytics for date-based reporting)

**Calendar integrations:**
```
Calendar Connections

Google Calendar      ✓ Connected (Junis Braun personal)  [Disconnect]
Microsoft Outlook    ✓ Connected (School admin account)  [Disconnect]

[Connect another calendar]

Note: Teacher calendar connections are managed by each teacher in their
own Profile settings. The school can see event presence (busy/free)
but not event details from connected personal calendars.
```

**Notification settings:**
- At-risk learner alerts: threshold (inactivity days, score threshold), on/off
- Programme delay alerts: when a class falls behind by N days
- Teacher workload flags: when a teacher exceeds contracted hours by N%
- Upcoming sessions with no teacher assigned: flagged N days before
- Upcoming sessions with no materials published: flagged N days before

**Content defaults:**
- Default language level display for new learners: L1
- Default programme settings (pre-fills when creating a new programme)

---

### 5.9 Help (Hilfe) — Support and Guidance

The Help section is designed for school admins managing the platform without an IT department and for new staff who need to get productive quickly.

**Structure:**

```
Help — Pflegeschule Frankfurt
─────────────────────────────────────────────────────────────────
🔍 Search...

Getting started
  • Setting up your school for the first time
  • Inviting teachers and staff
  • Creating your first programme
  • Connecting your calendar

Managing programmes
  • Using Full Edit Mode
  • Assigning teachers to Themenfelder
  • Understanding Blocks, Themenfelder, and Unterrichtseinheiten

Managing teachers
  • Managing workload and leave
  • Setting up replacement teachers
  • Understanding teacher workload analytics

Managing learners
  • Enrolling learners
  • Understanding at-risk signals
  • School-wide learner analytics

Team & Roles
  • Creating custom roles
  • Understanding the permission matrix
  • What school admins can and cannot configure

Ask Lingo for school admins
  • What Lingo can do for your school
  • Agentic actions and permission confirmations
  • Example questions and commands
```

**Inside any article:**
At the bottom:

```
Was this helpful?  [👍 Yes]  [👎 No]

─── Want more help? ──────────────────────────────────────
Didn't find what you were looking for? Get in touch with
the Lingocare team directly.

[Contact Lingocare →]

Opens a short form:
  Your name: [pre-filled]
  School: [pre-filled]
  Topic: [Article title pre-filled, editable]
  Message: [______________]
  [Send to Lingocare]
  
  Response within 1 business day.
```

The "Contact Lingocare" form goes directly to the Lingocare customer success team — not a generic support ticket queue. School admins who submit a form get a response addressed to their specific school and situation.

---

## 6. Lingo — Agentic AI for School Operations

This is the most powerful version of Lingo in the platform. For learners, Lingo is a companion and guide. For instructors, Lingo is a preparation and analytics assistant. For school admins, Lingo is an operations system — it monitors, surfaces, suggests, and acts.

### The Four Modes Lingo Operates In

**Mode 1: Proactive monitoring (no prompt needed)**
Lingo scans the school's data continuously and surfaces issues on the dashboard and in the Lingo panel without being asked.

Examples of proactive flags:
- *"You have 3 sessions in the last week of July with no teacher assigned — 8 days away."*
- *"Block 3 in PFA Hessen has 5 days with no Unterrichtseinheiten scheduled."*
- *"KI1-LU3 materials haven't been published — that lesson starts in 8 days. Belinda Kleinhans is the assigned instructor."*
- *"Belinda Kleinhans now has 47 teaching hours planned this month. Her contract is 40 hours."*
- *"3 classes in PFA Hessen are unlikely to finish Block 2 before the scheduled exam at current pace."*

**Mode 2: Query answering (text prompt)**
Ask anything about the school in plain language.

Examples:
- *"Who in Klasse 9B is most at risk right now?"* → specific learners, specific signals
- *"How many teaching hours does Thomas have this month?"* → exact number, compared to contract
- *"Which programme has the lowest completion rate?"* → immediate answer with context
- *"What's happening in the school calendar next week?"* → summary of sessions, who teaches what
- *"Is there any content not yet published for classes starting next week?"* → specific LUs, specific instructors responsible

**Mode 3: Action execution (with permission confirmation)**
Lingo can execute changes in the system. Always with a clear confirmation step before anything is modified.

Action examples:

```
Ask Lingo: "Assign an available teacher to the July 28 session"

Lingo: "The July 28 session is:
  Klasse 10C · BD1-LU2 · 09:00–11:00

  Available teachers on July 28:
  ● Thomas Brandt — 2 free hours, teaches BD cluster ✓
  ○ Klaus Weigand — available, no BD experience
  ○ Laura Hoffmann — on leave that day

  Recommendation: Thomas Brandt.
  [Assign Thomas →]  [Choose someone else]"

[Assign Thomas →]

Lingo: "This will assign Thomas Brandt to:
  Klasse 10C · BD1-LU2 · July 28, 09:00–11:00

  Thomas and the 24 learners in Klasse 10C will be notified.
  Thomas's Lingocare calendar will be updated.
  If his Outlook is connected, a calendar event will sync there too.

  Confirm?"
  [Confirm ✓]  [Cancel]"
```

```
Ask Lingo: "Notify Belinda that KI1-LU3 material needs to be published"

Lingo: "Draft message to Belinda Kleinhans:
  'Hi Belinda — KI1-LU3 is scheduled to start in 8 days and
  the materials haven't been published yet. Can you review
  and publish when you get a chance? — Junis'

  [Send as-is]  [Edit first]  [Cancel]"
```

```
Ask Lingo: "Check Programme PFA Hessen for gaps or issues"

Lingo: "I found 4 issues in PFA Hessen:

  ⚠ Block 3: 3 Unterrichtseinheiten have no teacher assigned
     → Jul 21, Jul 28, Aug 4 · all in Klasse 10C
     [Assign teachers now →]

  ⚠ Block 2: KI1-LU3 materials unpublished (due in 8 days)
     → Assigned instructor: Belinda Kleinhans
     [Notify Belinda →]

  ℹ Block 3: 5 days have no Unterrichtseinheiten scheduled
     → Apr 14–18 appear empty in the Lehrplan
     [Open in Full Edit Mode →]

  ✓ Block 1: Complete. All sessions assigned and published.

  Would you like me to help resolve any of these now?"
```

**Mode 4: Report generation**
Lingo generates formatted summaries on request.

- *"Give me a summary of the school's performance this month"* → 8-line summary with key metrics
- *"Generate a teacher workload report for June"* → table format, exportable
- *"Which learners have been inactive for more than 2 weeks?"* → named list with last-active dates

---

### What Lingo Will Not Do Without Asking

Lingo never makes changes silently. For any action that modifies data — assigning a teacher, sending a notification, updating a schedule — Lingo always presents the proposed action first, explains what it will do, who will be notified, and waits for explicit confirmation.

The school admin is always in control. Lingo is the interface to the controls, not an autonomous agent.

---

## 7. How Everything Connects — The Workflows

---

### Workflow 1: Morning School Check — Dashboard to Action

```
Home (Startseite) · Monday 08:00
  │
  Dashboard widgets:
  Teachers widget: ⚠ 2 flags
    → Belinda — overloaded (47h vs 40h contract)
    → Thomas — 3 unassigned sessions in July
  │
  [Tap "2 flags"]  → Teachers page filtered to flagged
  │
  Teachers page:
  Thomas Brandt  ·  2 classes  ·  38h  ·  🟡  3 gaps in July
  [View detail →]
  │
  Teacher detail · Thomas:
  "3 sessions in July have no teacher assignment:
   Jul 21, Jul 28, Aug 4 · Klasse 10C · BD1"
  │
  [Ask Lingo]: "Fix the July gaps for Klasse 10C"
  
  Lingo: "3 sessions in Klasse 10C · BD1 are unassigned.
  I checked available teachers for those dates:
  
  · Jul 21: Thomas Brandt (free), Fatima (busy)
  · Jul 28: Thomas Brandt (free), Klaus (free, no BD)
  · Aug 4:  Thomas Brandt (busy), Fatima (free, BD ✓)
  
  Recommended: Thomas Jul 21+28, Fatima Aug 4.
  [Assign all three →]  [Decide individually]"
  
  [Assign all three →]
  
  Lingo: "This will assign:
   · Thomas Brandt: Jul 21 + Jul 28 · Klasse 10C BD1
   · Fatima Al-Rashidi: Aug 4 · Klasse 10C BD1
   
   Both teachers and Klasse 10C learners will be notified.
   Calendars will be updated. Confirm?"
   [Confirm ✓]
  │
  ↓
  Dashboard: Thomas's flag clears. School overview: 1 flag remaining.
  Lingo: "Done. Thomas and Fatima have been notified.
  The remaining flag is Belinda's workload — want to review her schedule?"
```

---

### Workflow 2: Teacher Absence — Replacement in Two Minutes

```
Monday 08:15 · Belinda calls in sick · Leave: Mon–Wed
  │
  Teachers page → Belinda Kleinhans → [Mark leave]
  Date range: Monday Jun 2 – Wednesday Jun 4
  [Save]
  │
  Lingo immediately:
  "Belinda is marked on leave Jun 2–4.
  3 sessions are affected:
  · Jun 2: Klasse 9B · KI1 PF2  ·  09:00
  · Jun 3: Klasse 8A · AD1 PF1  ·  11:00
  · Jun 4: Klasse 10C · KI1 PF3 ·  14:00
  
  Want me to suggest replacements?"
  [Yes →]
  │
  Lingo: "Best available options:
  
  Jun 2 KI1 PF2 (Klasse 9B):
    ● Fatima Al-Rashidi — teaches KI, 2h free Jun 2 ✓
  
  Jun 3 AD1 PF1 (Klasse 8A):
    ● Thomas Brandt — teaches AD, available ✓
  
  Jun 4 KI1 PF3 (Klasse 10C):
    ● Fatima Al-Rashidi — available, KI ✓
    ○ Klaus Weigand — available, no KI experience
  
  [Assign all three with recommendations →]"
  [Assign all three →]
  
  Lingo: "This will assign:
   Fatima → Jun 2 Klasse 9B, Jun 4 Klasse 10C
   Thomas → Jun 3 Klasse 8A
   
   Fatima, Thomas, affected learners, and class parents notified.
   Calendars updated. Confirm?"
   [Confirm ✓]
  │
  Done in under 2 minutes.
  Belinda's classes are covered.
  Teachers have calendar updates.
  Learners have notifications.
```

---

### Workflow 3: Curriculum Planning in Full Edit Mode

```
Programs → PFA Hessen → [Open programme]
  │
  Curriculum view in read mode.
  Admin notices Block 3 has a warning: "3 Unterrichtseinheiten unassigned"
  │
  [Full Edit Mode 🖊] toggled ON
  │
  Block 3 · Jul–Sep expanded:
  └── Themenfeld: Hygiene & Infection Control [AD]
        Teacher: [ Unassigned ▾ ]  ← dropdown
        └── Unterrichtseinheit · Jul 21  [no teacher]
        └── Unterrichtseinheit · Jul 28  [no teacher]
        └── Unterrichtseinheit · Aug 4   [no teacher]
  │
  Admin opens teacher dropdown for the Themenfeld:
  [ Belinda Kleinhans ▾ ] — 44h already planned (over)
  [ Thomas Brandt ▾ ]     — 34h planned (has capacity) ← select
  │
  Thomas Brandt assigned to all 3 sessions via Themenfeld assignment
  │
  "Pending: Thomas Brandt assigned to AD1 Themenfeld Block 3 (3 sessions)"
  │
  Admin also adds a new Unterrichtseinheit:
  [+ Add Unterrichtseinheit] → title, date, LUs from library
  LU: AD1-LU5 "Isolation measures" added
  │
  [Publish changes ✓]
  
  "Publishing will:
   · Assign Thomas Brandt to 3 sessions in Block 3
   · Add AD1-LU5 'Isolation measures' to Aug 4 session
   · Update Thomas's Lingocare calendar
   · Sync to Thomas's connected Outlook calendar
   · Notify Thomas of the assignment
   
   Confirm? [Publish ✓] [Review again]"
```

---

### Workflow 4: School-wide At-Risk Review

```
Analytics → Learner outcomes tab
  │
  Filter: At-risk status = 🔴 (highest risk)
  Result: 14 learners across 3 programmes
  │
  Top 3:
  Tom Becker    · PFA · Klasse 9A · 🔴 · Inactive 15 days
  Amira Hassan  · APH · Klasse 4B · 🔴 · Score trend declining 3 weeks
  Felix Kramer  · SBP · Klasse 2A · 🔴 · 5 missed submissions
  │
  [Ask Lingo]: "What's the best action for each of these three?"
  
  Lingo: "Tom Becker (PFA 9A):
  Inactive 15 days, PF2 overdue. His instructor (Fatima) hasn't
  contacted him yet. Suggest a check-in message from Fatima.
  [Notify Fatima to reach out →]
  
  Amira Hassan (APH 4B):
  Score dropping on all BD-cluster LUs. L1 language level.
  She hasn't done any KI Language Practice.
  Recommend: enable KI language practice suggestions for her class.
  [Enable for Klasse 4B →]
  
  Felix Kramer (SBP 2A):
  5 missed submissions across 3 weeks. His class instructor Maria
  is currently on leave. Klaus is covering. Felix may not know.
  Suggest a direct message to Felix.
  [Draft message to Felix →]"
  │
  Admin works through each suggestion with one tap per action.
  Total time: ~5 minutes for three at-risk interventions.
```

---

### Workflow 5: Setting Up a Custom Role for a New Content Creator

```
Team & Roles → Roles → [+ Create new role]
  │
  Role name: "Content Creator"
  
  Permission matrix (filling in):
  Programs & Curriculum:    View ●
  Teachers management:      None ●
  Learner management:       None ●
  School Analytics:         None ●
  Class Analytics:          View ●
  Content Studio:           Edit ●
  Content Library:          Edit (own) ●
  Scheduling:               None ●
  Team & Roles:             None ●
  Settings:                 None ●
  Help:                     View ●
  
  [Save role]
  │
  → Staff Accounts → [+ Invite staff member]
  Email: max.lehmann@pflegeschule-frankfurt.de
  Role: Content Creator
  [Send invitation]
  │
  Max receives invitation email → creates account →
  Lands in Content Studio immediately (his first screen is the Studio,
  not a full admin dashboard — his role determines his starting view)
```

---

## 8. The Cross-Surface Principle

Every piece of information the school admin needs is reachable from multiple places. They never have to remember where things live.

**A curriculum gap is visible from:**
- Home dashboard (Teachers widget flags or Programmes widget warning)
- Programs page (warning icons on blocks with issues)
- Analytics (completion chart shows which LUs are at 0%)
- Ask Lingo ("Check the Lehrplan for gaps")

**A teacher's schedule is visible from:**
- Calendar (overlay with checkbox)
- Teachers page (individual detail → Schedule tab)
- Programs → Full Edit Mode (teacher assignment view)
- Ask Lingo ("What is Thomas teaching next week?")

**A teacher assignment change:**
- Made in Programs → Full Edit Mode
- Made via Calendar (create/edit an event and assign a teacher)
- Made via Ask Lingo ("Assign Thomas to the July 28 session")
- All three paths update the same data and sync the same calendars

**A learner at-risk signal is visible from:**
- Home dashboard (Learners widget)
- Learners page (status column, filter by at-risk)
- Analytics (learner outcomes tab)
- Ask Lingo ("Who are my highest-risk learners right now?")
- Individual learner profile (signal bar at top)

**The Help section is reachable from:**
- Left sidebar (Help item)
- Any error state or empty state in the app (contextual "Need help?" link)
- Ask Lingo ("How do I create a custom role?") → Lingo answers and links to the Help article

**The underlying rule:** The school admin should be able to run the entire school from Ask Lingo if they want to, and they should also be able to find anything by navigating directly if they prefer. Both paths are equally valid. Neither is a workaround for the other.

---

*Next in this series:*
- *Lingocare Application — Tenant Director Deep-Dive*

---

*Lingocare GmbH · Frankfurt, Hessen · hello@lingocare.ai · www.lingocare.ai*  
*Where AI, Healthcare & Social Impact meet*