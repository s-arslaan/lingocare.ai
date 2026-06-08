# Feedback on LingoCare Learner Deep Dive

> Structured feedback from Sara — please review and revise as needed, Arslaan.

Reference doc: https://arslaanshaikh.me/lingocare.ai/pages/doc-viewer.html?file=lingocare_learner_deepdive.md

---

## 1. Job to Be Done — The Learner

There are two core jobs the learner persona needs Lingocare to fulfill:

**Job 1 — Exam readiness:**
> *"Prepare me for my practical and theoretical exams. I want to pass and be ready for my profession."*

This is the primary job. In early project research, when asked what mattered most, the majority of trainees answered: *"I want to be well prepared for the exam."* This signal should be front and center.

**Job 2 — Language confidence (for those with language barriers):**
> *"Help me feel safe and confident in German — so I can self-regulate, stay calm, and not feel anxious in professional situations."*

This is not just about language skills. It is about psychological safety and day-to-day readiness on the floor. Learners need to feel they can communicate without fear.

---

## 2. Navigation — Care Learning vs. Language Learning

The current "My Learning" section separates **Knowledge Garden** and **Language Practice**, which is a good starting point. The suggestion is to go one level higher and make the top-level distinction explicit:

**Proposed structure:**

```
My Learning
├── Learn Care        (Care-specific knowledge, clinical topics, exam prep)
│   └── e.g., Knowledge Garden, Practice Cases, Exam Prep
└── Learn Language    (German language development)
    └── e.g., Language Practice, Vocabulary, Situational Dialogs
```

This gives learners an immediate, clear choice when they enter the platform — and reflects the actual duality of their learning needs.

---

## 3. "My Progress" — What's Missing: A Call to Action

The current "My Progress" section shows achievements and a profile, but it lacks the most important element: **something that moves the learner to act**.

When a learner opens the platform and wants to learn, they are currently left without clear direction. The question they ask is:

> *"Where do I click if I want to learn the most important thing right now?"*

**Proposed improvement:** Add a clear, guided entry point — something like:

- **"Learn now"** — one-tap entry into the most relevant content for today
- **"My next learning"** — a proactive suggestion based on what comes next
- **"My state of learning"** — a clear view of where they are and what to focus on

This could live as a prominent action on the dashboard or progress view, and could dynamically adjust to what the learner should be preparing that week (e.g., an upcoming exam topic or a language skill they are building).

The learner workspace should also always offer two distinct entry points:
- **Care space** — full care learning curriculum
- **Language space** — language development track

These can coexist without one getting buried by the other.

---

## 4. Lingo's Character, Emotions, and Presence

Lingo is not just a tool — it is a character that interacts with learners. The way Lingo is designed and how it communicates has a huge impact on the learner experience.
**Critical legal and positioning note:**

> Lingo the otter only must be presented as a nurse, doctor, or patient (not any real imagery) — even if styled with healthcare imagery.

If Lingo is given a character costume (e.g., depicted in scrubs or as a healthcare professional), it must be **unambiguously clear that Lingo is a fictional character**, not a real clinical professional or substitute for one. A startup was recently sued for presenting an AI as a "doctor" — this is a live legal risk. Arslaan should audit all current depictions of Lingo and ensure no framing implies clinical authority or a real professional identity.
Or make sure the Lingo character is clearly a fictional, friendly otter — not a human at all and represents the learner himself. This would be the safest route.

---

## 5. Dashboard Language — Proactive and Strength-Oriented

This point applies across all of LingoCare but is especially relevant to the Learner experience.

**Do not say:**
- "You haven't been here in X days."
- "Your [skill] is getting weaker."
- "You're falling behind on [topic]."

**Instead, say:**
- "Welcome back — great to see you!"
- "Ready to pick up where we left off?"
- "It would be so cool to tackle [topic] together today."

The language must be consistently:
- **Warm** — like a trusted peer, not a system alert
- **Proactive** — Lingo initiates, not just responds
- **Strength-oriented** — surfaces what is going well and builds from there

---

## 6. Proficiency Levels (P1, P2, etc.) — Keep in the Background

Language proficiency levels (P1, P2, etc.) should be used internally as a framework for personalization — **but should not be surfaced directly to learners** in those terms.

Learners should experience a simple, accessible interface. The proficiency model should shape what content they see and how Lingo guides them, without making them feel labeled or categorized. Or if the levels are used, they should be framed in a way that feels empowering and growth-oriented, not like a fixed label, like a language difficulty slider with simple descriptors (e.g., "Basic," "Intermediate," "Advanced") rather than technical proficiency codes.

---

*Document prepared by Sara — June 2026*