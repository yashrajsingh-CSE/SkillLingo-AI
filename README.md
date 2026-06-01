# SkillLingo AI — Multilingual Course Localization Platform

> **AI-powered platform that automatically translates, dubs, and localizes your courses into 47+ languages — in minutes, not months.**

[![Languages](https://img.shields.io/badge/Languages-47%2B-7c6ff7)](#)
[![Learners](https://img.shields.io/badge/Learners-10M%2B-22d3ee)](#)
[![Revenue Lift](https://img.shields.io/badge/Avg%20Revenue%20Lift-3.2%C3%97-34d399)](#)

---

## Table of Contents

- [Overview](#overview)
- [Screenshots](#screenshots)
- [Features](#features)
- [Pricing](#pricing)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Pages & Navigation](#pages--navigation)

---

## Overview

SkillLingo AI is a full-featured SaaS dashboard for course creators and L&D teams who want to reach global learners in their native language. The platform handles the entire localization pipeline — from AI translation and subtitle generation to voice dubbing and real-time analytics — all from a single interface.

---

## Screenshots

### 🏠 Landing Page
The marketing homepage with hero section, key metrics, features, pricing tiers, and testimonials.

![Landing Page](Screenshot_2026-06-01_203532.png)

---

### 📊 Dashboard
The main command center showing active courses, AI job statuses, learner counts, localization activity charts, and recent events.

![Dashboard](Screenshot_2026-06-01_203545.png)

---

### 🎬 Localization Studio
The core workspace for reviewing AI-generated translations, subtitle timecodes, confidence scores, audio waveforms, and configuring AI settings per language.

![Localization Studio](Screenshot_2026-06-01_203551.png)

---

### 📚 Course Library
Upload and manage your entire course catalog. Supports MP4, MP3, WAV, PDF, DOCX, PPTX, and SCORM formats with drag-and-drop ingestion.

![Course Library](Screenshot_2026-06-01_203556.png)

---

### 🤖 AI Tutor
An embedded conversational AI tutor that answers learner questions in their native language, with full course context awareness and progress tracking.

![AI Tutor](Screenshot_2026-06-01_203601.png)

---

### ⚙️ AI Job Queue
Real-time pipeline view of all localization jobs — running, queued, completed, and failed — with live progress bars and per-job actions.

![AI Job Queue](Screenshot_2026-06-01_203606.png)

---

### 📈 Analytics
Comprehensive reporting on watch time by language, completion rates, learner growth over time, and localization ROI metrics.

![Analytics](Screenshot_2026-06-01_203610.png)

---

### 👥 Team Management
Role-based access control — manage admins, reviewers, editors, and viewers with per-language assignments and invite workflows.

![Team Management](Screenshot_2026-06-01_203615.png)

---

### 💳 Billing & Credits
Plan management (Starter / Pro / Enterprise), AI credit usage breakdown, and invoice history with PDF download.

![Billing & Credits](Screenshot_2026-06-01_203620.png)

---

### ⚙️ Settings
Profile settings, organization config, language preferences, AI configuration, notifications, security, and API key management.

![Settings](Screenshot_2026-06-01_203625.png)

---

## Features

| Feature | Description |
|---|---|
| **AI Translation** | Context-aware translation that understands technical vocabulary, maintains tone, and adapts cultural nuances automatically |
| **Voice Dubbing** | Clone the original instructor's voice and dub courses with natural-sounding AI audio in 47 languages, with lip-sync support |
| **Subtitle Generation** | Auto-generate, time-sync, and export subtitles in SRT, VTT, and SCORM formats with AI confidence scoring |
| **AI Tutor** | Embedded AI tutor that answers learner questions in their native language, course-aware and context-sensitive |
| **Analytics & ROI** | Track engagement, completion rates, and revenue impact by language with real-time dashboards and exportable reports |
| **Team Collaboration** | Assign reviewers by language, manage permissions, track review status, with built-in approval workflows |

---

## Pricing

| Plan | Price | Credits | Languages | Highlights |
|---|---|---|---|---|
| **Starter** | $29/mo | 1,000/mo | 5 | Subtitles only, 2 team members |
| **Pro** | $99/mo | 5,000/mo | 10 | AI dubbing + cloning, analytics, 5 members |
| **Enterprise** | Custom | Unlimited | 47+ | Voice cloning, lip sync, SSO + SLA, unlimited team |

---

## Tech Stack

- **Frontend:** Vanilla HTML/CSS/JavaScript — no framework dependencies
- **Fonts:** [Syne](https://fonts.google.com/specimen/Syne) (headings) + [DM Sans](https://fonts.google.com/specimen/DM+Sans) (body) via Google Fonts
- **Icons:** [Tabler Icons](https://tabler-icons.io/) (webfont, v3.11.0)
- **Charts:** Pure CSS bar charts and SVG donut charts
- **Layout:** CSS Grid + Flexbox, fully responsive

### Key UI Patterns

- Dark theme with CSS custom properties (`--ink`, `--violet`, `--cyan`, etc.)
- Single-page application (SPA) routing via vanilla JS `nav()` function
- Live progress bar animations using `setInterval`
- Collapsible sidebar with slim mode
- Slide-in notification drawer
- Waveform visualization generated dynamically in JS

---

## Getting Started

No build step required. This is a standalone HTML file.

```bash
# Clone or download the project
git clone https://github.com/your-org/skilllingo-ai.git
cd skilllingo-ai

# Open directly in your browser
open index.html
```

Or serve it locally:

```bash
npx serve .
# → http://localhost:3000
```

---

## Pages & Navigation

| Route (JS) | Page | Description |
|---|---|---|
| `dashboard` | Dashboard | Overview stats, charts, active jobs, recent activity |
| `studio` | Localization Studio | Video preview, subtitle editor, waveform, AI config |
| `courses` | Course Library | Upload + manage all courses |
| `tutor` | AI Tutor | Chat interface with course context panel |
| `jobs` | AI Job Queue | Real-time pipeline with live progress |
| `analytics` | Analytics | ROI metrics, language performance, learner growth |
| `team` | Team Management | Member roles, permissions, invite flow |
| `billing` | Billing & Credits | Plan comparison, credit usage, invoices |
| `settings` | Settings | Profile, organization, AI config, security |

### Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `⌘K` / `Ctrl+K` | Open search |

---

## Live Interactions

- **Progress bars** — AI job progress increments automatically every 900ms to simulate a live pipeline
- **Chat** — The AI Tutor responds to messages with rotating contextual replies and a typing indicator
- **Sidebar** — Collapsible to icon-only slim mode via the hamburger toggle
- **Notifications** — Bell icon opens a slide-in drawer with recent system events
- **Studio waveform** — Dynamically generated bars with active segment highlighting
- **Drag & drop uploads** — Drop zone in Course Library responds to drag events

---

## Testimonials

> *"SkillLingo cut our localization time from 6 weeks to 3 days."*
> — **Rohan Kumar**, Head of L&D, Infosys

> *"We expanded from English-only to 12 languages in one month. Our course completion rates jumped 84% for non-English learners."*
> — **Aiko Tanaka**, Founder, LearnJapan Pro

> *"The AI tutor feature is a game-changer. Learners in rural India now get real-time help in Hindi. Support tickets dropped by 70%."*
> — **Marie Petit**, CPO, EduScale Africa

---

## License

© 2026 SkillLingo AI. All rights reserved.
