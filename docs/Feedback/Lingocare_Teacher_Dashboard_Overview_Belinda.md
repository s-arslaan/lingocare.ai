# Lingocare AI – Teacher Dashboard
## Structural Overview for Designer Meeting

---

## Framework

- A teacher typically manages **multiple classes** – the dashboard must always account for this at every level
- The entire dashboard is **AI-supported** – all areas include AI-generated recommendations and analysis
- The AI interface uses a **guided dropdown** ("What would you like to do today?") with a free-text escape hatch – designed to work for both traditional and AI-forward teachers
- **Consistent AI interaction pattern across all areas:** every area opens with a guided dropdown prompt, identical in structure to the start page. Free text input always available as escape hatch.

---

## Start Page: My Overview (all classes)

The welcome page shows a cross-class status overview – before the teacher drills into any single class. The AI prompt sits directly on this page.

**AI prompt on page** *(display):* "Was möchtest du heute tun?" *(What would you like to do today?)*

### What is visible on this page

**One card per class** – intentionally lean, to avoid overwhelming the page:

| Element | Content |
|---|---|
| Class name + last activity | *(display):* e.g. "Klasse 2B · zuletzt aktiv: heute" *(Class 2B · last active: today)* |
| Curriculum status (traffic light) | *(display):* "Im Plan" *(On track)* / "Leicht hinterher" *(Slightly behind)* / "Deutlich hinterher" *(Significantly behind)* |
| One warning signal (if present) | *(display):* e.g. "2 Lernende mit Rückstand" *(2 learners falling behind)* or "PF2 in LU3 macht Schwierigkeiten" *(PF2 in LU3 is causing difficulties)* |
| Next recommended action (AI-generated) | *(display):* e.g. "Klasse B sollte diese Woche AD1.3 abschließen" *(Class B should complete AD1.3 this week)* |

**Not on the card** (intentionally omitted – only visible after drill-down):
- Individual scores
- Competency area (KB) breakdown
- Any table-style detail data

### AI dropdown options *(display language)*

1. "Stunde vorbereiten" *(Prepare a lesson)*
2. "Live-Unterricht starten" *(Start live class)*
3. "Klassendetails ansehen" *(View class details)*
4. "Einzelne Lernende ansehen" *(View individual learners)*
5. Free text input field

---

## Library (separate entry point, accessible from anywhere)

The library is not a primary workflow – it is a browsing space. It is accessible as a **persistent element** throughout the entire dashboard (e.g. icon or tab always visible), not tied to any specific area.

### What the library contains
- **Lingocare catalogue:** all built-in LUs and knowledge modules (Wissensbausteine), browsable by topic, competency area (KB), or practice focus (PF)
- **Own materials:** materials previously uploaded by the teacher or school

### What teachers can do here
- Browse for inspiration or to check what already exists before preparing a lesson
- Preview any LU or module
- Assign content directly to a class and a date: *(display):* "Diese LU zuweisen" *(Assign this LU)* → select class → select date

### Contextual appearance in Area 1
When a teacher is preparing a lesson (Area 1 / Block B), the AI proactively checks the library and may suggest: *(display):* "Zu diesem Thema gibt es bereits 2 LUs in der Bibliothek – möchtest du sie ansehen?" *(There are already 2 LUs on this topic in the library – would you like to view them?)*
This is a suggestion, not a gate.

---

## Area 1: Lesson Preparation

**AI prompt:** *(display):* "Was möchtest du vorbereiten?" *(What would you like to prepare?)*

Dropdown options:
1. "Lehrplanstatus ansehen" *(View curriculum status)*
2. "Material hinzufügen" *(Add material)*
3. "Test planen" *(Schedule a test)*
4. Free text input

Teacher selects a class first → then three blocks:

---

### Block A – Curriculum Status (where does the class stand?)

**Curriculum progress bar** *(display):*

> [1. Ausbildungsdrittel ████████░░] [2. Ausbildungsdrittel ░░░░░░░░░░] [3. Ausbildungsdrittel ░░░░░░░░░░]
> "Woche 14 von 36 · 1. Ausbildungsdrittel · Im Plan" *(Week 14 of 36 · 1st training third · On track)*

**⚠️ [PFK ONLY – PFA structure TBD]**
The three-part structure below applies to PFK training (3-year programme). PFA curriculum phasing will be adapted once the PFA framework is finalized (planned 2027).

| Phase | PFK Content |
|---|---|
| **1. Ausbildungsdrittel** *(1st training third)* | Orientierungseinsatz – foundational care actions, first nursing situations, professional orientation |
| **2. Ausbildungsdrittel** *(2nd training third)* | Pflichteinsätze in 3 allgemeinen Versorgungsbereichen (inpatient, outpatient, long-term care) + paediatric placement |
| **3. Ausbildungsdrittel** *(3rd training third)* | Psychiatric placement + Vertiefungseinsatz (specialisation by qualification track: Pflegefachmann/-frau, paediatric, geriatric) |

**AI recommendation** (always shown):
*(display):* e.g. "Empfehlung für heute: AD1.3 · PF2 – die Klasse hat PF1 abgeschlossen" *(Recommendation for today: AD1.3 · PF2 – the class has completed PF1)*

---

### Block B – Add / Upload Material

- Teacher uploads own material (case, document, scenario)
- System automatically assigns it to a competency area (KB) → enables targeted language support
- All 4 Practice Foci (PFs) are generated from the material automatically
- KB-specific language tasks are embedded automatically
- *(display):* "Material einfügen" *(Add material)*

**Contextual library suggestion** appears here if relevant content already exists (see Library section above).

---

### Block C – Schedule & Create Tests

Teacher can schedule a test for an upcoming lesson. Three creation modes:

**Mode 1 – Auto-generate**
AI generates the test based on defined scope.
*(display):* "Test automatisch erstellen" *(Auto-generate test)*
- Time range: *(display):* "Material von [Datum] bis [Datum]" *(Material from [date] to [date])*
- Topic / LU: *(display):* "Thema oder Lerneinheit auswählen" *(Select topic or learning unit)*
- Source: from existing library content, from uploaded material, or both

**Mode 2 – Manual**
Teacher builds the test themselves, question by question.
*(display):* "Test manuell erstellen" *(Create test manually)*

**Mode 3 – Hybrid**
AI generates a draft, teacher reviews, edits and finalises.
*(display):* "KI-Vorschlag bearbeiten" *(Edit AI suggestion)*

---

## Area 2: Class Details

**AI prompt:** *(display):* "Was möchtest du über deine Klasse wissen?" *(What would you like to know about your class?)*

Three zoom levels of the same question – as a drill-down:

**Level 1 – Time perspective**
Are we on track with the curriculum? Where is the class falling behind overall?
*(display):* "Lehrplanstatus" *(Curriculum status)*
→ same progress bar as Block A, but here clickable for full drill-down

**Level 2 – Competency perspective**
- Areas of strength & weakness by competency area (KB): e.g. strong in AD, weak in KI
- Areas of strength & weakness by topic / LU
- *(display):* "Stärken & Entwicklungsfelder der Klasse" *(Class strengths & areas for development)*

**Level 3 – Content perspective (drill-down)**
- Which specific LU or PF is causing difficulty?
- Which tasks have high error rates?
- AI recommendation for next steps
- *(display):* e.g. "68% der Klasse hatte Schwierigkeiten mit Aufgabe 3 in AD1.2 · PF2" *(68% of the class had difficulties with task 3 in AD1.2 · PF2)*

---

## Area 3: Individual Learners

**AI prompt:** *(display):* "Wen möchtest du dir genauer ansehen?" *(Who would you like to look at more closely?)*

Three modes:

---

**Mode 1 – Learners with difficulties (early warning system)**
System-flagged automatically.
- Skipped tasks
- Low scores
- Low activity
- Goal: no learner "gets lost" before it's too late
- *(display):* "Lernende, die Unterstützung brauchen könnten" *(Learners who may need support)*

---

**Mode 2 – High-performing learners**
System-flagged automatically.
- Consistently high scores (near 100%)
- Fast completion across all PFs
- Goal: targeted differentiation, avoid underchallenge
- *(display):* "Lernende mit besonderer Stärke" *(Learners with particular strength)*

---

**Mode 3 – Look up an individual learner**
Teacher manually selects a specific learner by name – e.g. before a 1:1 meeting or feedback conversation.
*(display):* "Lernende Person auswählen" *(Select a learner)*

Shows:
- **Strengths:** where is this person performing particularly well? (by KB and topic)
- **Development areas:** where does more work need to go in?
- **Activity pattern:** is this person regularly active, or are there gaps?
- **[future] AI conversation profile:** a short AI-generated summary (1–2 sentences) to help the teacher prepare the conversation in a targeted way.
  *(display):* e.g. "Amara zeigt besondere Stärken in AD und KI, hat aber PF2 in BD bisher kaum bearbeitet. Ein guter Gesprächseinstieg wäre, ihre Stärken zu benennen und gemeinsam zu überlegen, was sie in BD noch erkunden möchte." *(Amara shows particular strengths in AD and KI, but has so far barely worked on PF2 in BD. A good conversation opener would be to name her strengths and explore together what she would still like to discover in BD.)*

---

## Area 4: Live Class Mode

This mode is active **during the lesson** – while learners are working in the app. It has two phases: live monitoring and debrief.

**Entry:** *(display):* "Live-Unterricht starten" *(Start live class)* – available from the start page dropdown and as a persistent quick-access button throughout the dashboard.

---

### Phase 1 – Live Monitoring (while learners are working)

The teacher sees a real-time overview of the class:

| Element | Content |
|---|---|
| Per-learner progress indicator | Who has started / is working / has completed the current PF |
| Ping / help request | Automatic alert when a learner signals they need help – teacher can assist that person without interrupting the rest of the class |
| Completion tracker | How many learners have finished the current PF – helps teacher judge when to move to debrief |

**Deliberate omissions during live mode:**
- No individual scores visible in real time (avoids competitive atmosphere)
- No detailed error breakdown (that comes in debrief)

---

### Phase 2 – Debrief (after a PF is completed)

When enough learners have finished a PF, the teacher transitions directly into debrief mode – shareable via screen share with the class.

**Shareable debrief screens** (teacher chooses which to show):

- **Heat map:** which tasks did the class struggle with most? Visual overview of error distribution across all tasks
  *(display):* e.g. "Aufgabe 3 · 68% Fehler" *(Task 3 · 68% errors)*

- **Word cloud / answer distribution:** for open or sorting tasks – what answers did the class give? Where were they split?
  *(display):* e.g. Grauzonenkarten-Verteilung *(grey zone card distribution)*

- **Discussion prompts (AI-generated):** ready-made Diskussionseinstiege the teacher can use directly
  *(display):* e.g. "Hier haben 60% anders entschieden – warum?" *(60% decided differently here – why?)* · "Ergänzt das mit eurer Praxiserfahrung." *(Add your own practical experience.)*

- **Praxistransfer prompt** (if flagged by content author): reminder to practise the physical action in the room
  *(display):* e.g. "Nehmen Sie sich jetzt 5–10 Minuten: Führen Sie die Händedesinfektion gemeinsam durch." *(Take 5–10 minutes now: practise hand disinfection together.)*

- **Content fixpoints** (set by content author): pedagogically significant moments from the LU that are always shown, regardless of class performance
  *(display):* e.g. "Amara handelt aus Empathie – und gefährdet dabei die Asepsis. Diskussion: Wie kann man Herrn Jansen beruhigen, ohne das sterile Feld zu gefährden?" *(Amara acts out of empathy – but compromises asepsis in doing so. Discussion: how can you calm Mr Jansen without endangering the sterile field?)*

**Display order in debrief (fixed):**
1. Word cloud / answer distribution (if present) – start with what the class actually did
2. Grey zone / answer distribution flags (sorted by % "unsure", descending)
3. Low-accuracy flags (sorted by error rate, descending)
4. Content fixpoints (always shown)
5. Free discussion prompt (if present)
6. Praxistransfer prompt (if set) – always last, as a closing physical action

**Note for designer:** debrief screens must be clean and projectable – large text, minimal UI chrome, optimised for being shared on a classroom screen.

---

## Designer Notes

- The three areas (Lesson Prep / Class Details / Individual Learners) are **modes within a single class view** – class selection is a **persistent UI element** (e.g. dropdown or tab, always visible and switchable), not a separate screen
- The Start Page ("My Overview") is the **only cross-class view** in the entire dashboard
- The **Library** is a persistent element accessible from anywhere in the dashboard
- **Area 4 (Live Mode)** is also accessible as a persistent quick-access button – teachers may need to reach it fast at the start of a lesson
- A clear **"back to overview"** navigation element should always be visible – teachers move between areas frequently and need reliable orientation
- All AI-generated text appears in German (the teacher-facing display language)
- The guided dropdown is the primary navigation entry point; free text input is the escape hatch for power users
- **Curriculum progress bar [PFK only – PFA TBD]:** use PFK 3-Drittel structure as design placeholder; PFA phasing will be defined later
- **Debrief screens** must be optimised for classroom projection: large text, minimal UI chrome, shareable via screen share
