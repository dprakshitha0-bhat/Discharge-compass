# Discharge-compass
# 🚀 Discharge Compass AI
### Patient Discharge Instruction Simplifier System

<div align="center">

![Version](https://img.shields.io/badge/Version-2.0.0-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)
![Status](https://img.shields.io/badge/Status-Active-success)
![Stack](https://img.shields.io/badge/Stack-React%20%7C%20Node.js%20%7C%20MongoDB-informational)

> **Transforming complex clinical discharge notes into clear, actionable, life-saving patient care plans — powered by AI.**

</div>

---

## 📌 Table of Contents

1. [Problem Statement](#-problem-statement)
2. [Existing Solutions vs. Our Solution](#-existing-solutions-vs-our-solution-gap-analysis)
3. [Why Discharge Compass AI is the Best Non-Existing Solution](#-why-discharge-compass-ai-is-the-best-non-existing-solution)
4. [Core Features](#-core-features)
5. [Unique Judge-Winning Features](#-unique-judge-winning-features)
6. [System Architecture & Workflow](#-system-architecture--workflow)
7. [Tech Stack](#-tech-stack)
8. [Setup Guide](#-setup-guide)
9. [Implementation Plan](#-implementation-plan)
10. [Impact](#-impact)

---

## 🧠 Problem Statement

Hospitals discharge **thousands of patients daily** with instruction sheets written in dense clinical terminology.

Most patients:
- ❌ Misunderstand their dosage schedules
- ❌ Fail to recognise warning symptoms
- ❌ Miss critical follow-up timelines
- ❌ Have no caregiver support or language access

This leads to **preventable hospital readmissions**, medication errors, and in worst cases — patient fatalities.

> 💡 There is a **critical need** for a tool that bridges the gap between medical language and patient comprehension.

---

## 📊 Existing Solutions vs. Our Solution — Gap Analysis

| # | Problem Area | Existing Solutions | Problems with Existing Solutions | What Discharge Compass AI Solves |
|---|---|---|---|---|
| 1 | **Plain-language translation** | Manual nurse explanation, paper leaflets | One-time verbal explanation forgotten quickly; paper leaflets still use medical jargon | AI auto-rewrites clinical notes into simple, grade-5 reading level English instantly |
| 2 | **Medication scheduling** | Generic printed drug tables | No visual separation of morning/afternoon/night; patients confuse doses | Colour-coded medication schedule with AM/PM/Night tags and visual icons |
| 3 | **Red-flag symptom awareness** | Printed warning sheets | Buried in long paragraphs; patients don't know which symptoms are urgent | Dedicated visual Red-Flag Alert Card with emergency contact button |
| 4 | **Language accessibility** | English-only discharge sheets | Non-English-speaking patients receive zero comprehension support | Real-time multilingual translation into 10+ regional languages including Hindi, Kannada, Tamil, Telugu |
| 5 | **Caregiver coordination** | Phone calls between nurse and family | Inconsistent communication; family not informed of missed doses or emergencies | Automated Caregiver Alert System via SMS/Email for missed doses and danger signs |
| 6 | **Patient compliance tracking** | No tracking exists in most hospitals | No way to know if patient followed instructions post-discharge | Compliance Score System that tracks adherence and reports % to the healthcare provider |
| 7 | **Accessibility for elderly/illiterate** | Large-font printouts at best | Elderly or illiterate patients still cannot benefit from text-only materials | Voice Assistant reads out all instructions clearly in the patient's chosen language |
| 8 | **Portability of care plan** | Printed paper card — easily lost | Lost paper = lost care plan; no backup | QR Smart Patient Card — scan from phone anytime, anywhere, without internet |
| 9 | **High-risk patient identification** | Doctor intuition only | No system to flag high-risk patients before discharge | AI Risk Prediction Engine identifies high-readmission-risk patients at discharge |
| 10 | **Offline access** | None | Patients in rural or low-connectivity areas cannot access digital tools | Full Offline Mode using local browser storage — works without internet |
| 11 | **Recovery timeline visibility** | Not provided | Patients have no sense of expected recovery milestones | Visual Health Timeline showing day-by-day recovery progress and checkpoints |
| 12 | **Reminder intelligence** | Basic phone alarm | Static reminders; no adaptation for missed doses | Smart Reminder Intelligence that reschedules and escalates when a dose is missed |

---

## 💡 Why Discharge Compass AI is the Best Non-Existing Solution

> No current hospital system or consumer app combines **AI simplification + multilingual support + caregiver coordination + compliance tracking + offline access** in a single, patient-facing, zero-training-required interface.

**The Gap:**
- EHR systems (Epic, Cerner) generate discharge summaries FOR clinicians, not patients.
- Apps like MyChart show raw clinical notes — not simplified.
- Translation tools (Google Translate) work on raw text — not structured care plans.
- Reminder apps have no clinical context awareness.

**Discharge Compass AI uniquely combines:**

```
Clinical AI Simplification
        +
Structured Care Card (Medications + Red Flags + Follow-up)
        +
Multilingual Voice Output
        +
Caregiver Real-Time Alerts
        +
Compliance & Risk Intelligence
        +
Offline-First Architecture
= The most complete post-discharge patient support system ever built.
```

---

## 📋 Core Features

| Feature | Description |
|---|---|
| 🗣️ Plain-Language Rewrite | AI converts clinical text to simple, actionable language |
| 💊 Medication Schedule | Morning / Afternoon / Night colour-coded drug table |
| 🚨 Red-Flag Alert Section | Visual emphasis on danger symptoms with emergency action |
| 🖨️ Printable Care Card | Clean A5 layout for patient to carry home |
| 🤖 AI Auto-Simplification | Powered by OpenAI / Anthropic API |

---

## 🔥 Unique Judge-Winning Features

### 🎙️ 1. Voice Assistant
- Text-to-speech reads all care instructions aloud
- Supports multiple languages and adjustable speed
- Ideal for elderly, visually impaired, or low-literacy patients

### 🌐 2. Multilingual Support
- Converts entire care plan into 10+ regional languages
- Languages: Hindi, Kannada, Tamil, Telugu, Marathi, Bengali, Gujarati, Malayalam, Punjabi, Odia
- One-click toggle between languages

### 📲 3. QR Smart Patient Card
- Auto-generates a QR code for every care plan
- Patient or family scans to view full plan on any device
- Works offline after first load (cached)

### 👨‍👩‍👧 4. Caregiver Alert System
- Family members registered at discharge
- Receives SMS/Email if patient misses dose or if red-flag symptom is self-reported
- Emergency escalation button directly on the patient dashboard

### ⭐ 5. Compliance Score System
- Patient checks off completed medication doses and follow-up visits
- Live compliance percentage displayed
- Weekly report auto-sent to treating physician

### 🧠 6. AI Risk Prediction Engine
- Analyses patient history, diagnosis codes, and discharge complexity
- Flags patients with high readmission probability (>40%)
- Displays risk badge on physician dashboard

### 📴 7. Offline Mode
- Full care plan accessible without internet
- Uses browser localStorage / IndexedDB
- Automatic sync when connectivity is restored

### 📅 8. Visual Health Timeline
- Day-by-day recovery milestone display
- Colour-coded: Green (normal), Yellow (check in), Red (emergency)
- Patient marks daily status; physician reviews remotely

### ⏰ 9. Smart Reminder Intelligence
- Adaptive push notifications/SMS
- If dose is missed → escalates to caregiver alert → logs in compliance report
- Machine-learning pattern detection for optimal reminder timing

---

## 🏗️ System Architecture & Workflow

### High-Level Architecture

```
┌─────────────────────────────────────────────────────────────────┐
│                        DISCHARGE COMPASS AI                     │
│                                                                 │
│  ┌──────────────┐    ┌──────────────┐    ┌──────────────────┐  │
│  │   FRONTEND   │    │   BACKEND    │    │    AI ENGINE     │  │
│  │              │    │              │    │                  │  │
│  │ React.js     │◄──►│ Node.js +    │◄──►│ OpenAI GPT-4 /  │  │
│  │ Tailwind CSS │    │ Express.js   │    │ Rule-Based NLP   │  │
│  │              │    │              │    │                  │  │
│  └──────┬───────┘    └──────┬───────┘    └──────────────────┘  │
│         │                  │                                    │
│         │           ┌──────▼───────┐    ┌──────────────────┐  │
│         │           │   DATABASE   │    │ NOTIFICATION SYS │  │
│         │           │              │    │                  │  │
│         └──────────►│  MongoDB     │    │ Nodemailer (Email│  │
│                     │  Atlas       │    │ Twilio (SMS)     │  │
│                     │              │    │ Web Push API     │  │
│                     └──────────────┘    └──────────────────┘  │
│                                                                 │
│  ┌─────────────────────────────────────────────────────────┐   │
│  │                    OFFLINE LAYER                        │   │
│  │    Service Worker  +  IndexedDB  +  LocalStorage        │   │
│  └─────────────────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────────────────┘
```

### Component-Level Architecture

```
Frontend (React)
├── /pages
│   ├── DoctorInput.jsx         → Clinical note entry + AI trigger
│   ├── PatientDashboard.jsx    → Structured care card display
│   ├── CaregiverPortal.jsx     → Family monitoring panel
│   └── AdminDashboard.jsx      → Risk flags + compliance stats
│
├── /components
│   ├── MedicationCard.jsx      → Morning/Afternoon/Night table
│   ├── RedFlagAlert.jsx        → Danger symptom panel
│   ├── VoiceAssistant.jsx      → TTS reader
│   ├── QRCodeCard.jsx          → QR generator + display
│   ├── HealthTimeline.jsx      → Day-by-day recovery viewer
│   ├── ComplianceScore.jsx     → Adherence tracker
│   └── LanguageSelector.jsx    → Multilingual toggle
│
Backend (Node.js + Express)
├── /routes
│   ├── ai.routes.js            → /api/simplify, /api/risk
│   ├── patient.routes.js       → CRUD patient records
│   ├── alert.routes.js         → Trigger caregiver notifications
│   └── compliance.routes.js    → Log + retrieve compliance data
│
├── /services
│   ├── aiService.js            → OpenAI API wrapper
│   ├── translationService.js   → Language conversion
│   ├── notificationService.js  → Email + SMS dispatch
│   ├── qrService.js            → QR code generation
│   └── reminderService.js      → Cron-based smart reminders
│
├── /models (MongoDB Schemas)
│   ├── Patient.js
│   ├── CareRecord.js
│   ├── Compliance.js
│   └── AlertLog.js
```

### End-to-End System Workflow

```
STEP 1: DOCTOR INPUT
──────────────────────────────────────
Doctor enters raw clinical discharge note
        │
        ▼
STEP 2: AI SIMPLIFICATION
──────────────────────────────────────
AI Engine processes note →
    • Extracts medication names, doses, schedules
    • Identifies red-flag symptoms
    • Extracts follow-up dates
    • Detects risk indicators
        │
        ▼
STEP 3: STRUCTURED CARE PLAN GENERATED
──────────────────────────────────────
System builds:
    • Plain-language summary
    • Colour-coded medication schedule
    • Red-flag alert card
    • Follow-up checklist
    • AI Risk Score badge
        │
        ▼
STEP 4: DATA STORED
──────────────────────────────────────
Care plan saved to MongoDB
Patient profile created
Caregiver contacts registered
        │
        ▼
STEP 5: PATIENT DASHBOARD ACTIVATED
──────────────────────────────────────
Patient/caregiver accesses personalised dashboard
QR code generated and printed on care card
Voice assistant activated on first load
Language preference set
        │
        ▼
STEP 6: SMART REMINDERS ACTIVATED
──────────────────────────────────────
Cron job schedules:
    • Morning / Afternoon / Night medication alerts
    • Follow-up appointment reminders
    • Weekly compliance report to doctor
        │
        ▼
STEP 7: COMPLIANCE TRACKING
──────────────────────────────────────
Patient marks doses as taken
Compliance score updates in real-time
Timeline updated daily
        │
        ▼
STEP 8: RISK & ALERT MONITORING
──────────────────────────────────────
If dose missed → Caregiver SMS/Email alert
If red flag reported → Emergency alert triggered
If compliance < 60% → Physician dashboard flagged
High-risk patients → Auto-flagged for follow-up call
```

---

## ⚙️ Tech Stack

| Layer | Technology | Purpose |
|---|---|---|
| Frontend | React.js + Tailwind CSS | UI, responsive design |
| Backend | Node.js + Express.js | REST API, business logic |
| Database | MongoDB Atlas | Patient records, compliance logs |
| AI Engine | OpenAI GPT-4 API | Clinical text simplification |
| NLP Fallback | Rule-based regex parser | Offline AI processing |
| Translation | LibreTranslate / Google Translate API | Multilingual support |
| Notifications | Nodemailer + Twilio SMS | Caregiver alerts |
| QR Generation | qrcode npm library | Smart patient cards |
| Voice | Web Speech API (TTS) | Voice assistant |
| Offline | Service Worker + IndexedDB | Offline mode |
| Reminders | node-cron | Smart reminder scheduling |
| Auth | JWT + bcrypt | Secure doctor/patient login |
| Hosting | Vercel (Frontend) + Railway (Backend) | Deployment |

---

## 🚀 Setup Guide

### Prerequisites — Install These First

**Step 1:** Install Node.js (v18+)
```
Download from: https://nodejs.org
Verify: node --version && npm --version
```

**Step 2:** Install MongoDB
```
Option A — Local: https://www.mongodb.com/try/download/community
Option B — Cloud: Create free cluster at https://cloud.mongodb.com
```

**Step 3:** Get OpenAI API Key
```
Visit: https://platform.openai.com/api-keys
Create new secret key → copy it safely
```

**Step 4:** Get Twilio credentials (for SMS alerts)
```
Visit: https://www.twilio.com/try-twilio
Note your: Account SID, Auth Token, Phone Number
```

---

### Installation — Step by Step

**Step 5:** Clone the repository
```bash
git clone https://github.com/your-username/discharge-compass-ai.git
cd discharge-compass-ai
```

**Step 6:** Install backend dependencies
```bash
cd backend
npm install
```

**Step 7:** Install frontend dependencies
```bash
cd ../frontend
npm install
```

**Step 8:** Create the backend environment file
```bash
cd ../backend
cp .env.example .env
```

**Step 9:** Fill in your `.env` file with the following values
```env
# Server
PORT=5000
NODE_ENV=development

# MongoDB
MONGO_URI=mongodb+srv://your-username:your-password@cluster.mongodb.net/discharge-compass

# OpenAI
OPENAI_API_KEY=sk-your-openai-key-here
OPENAI_MODEL=gpt-4

# JWT Auth
JWT_SECRET=your-very-long-random-secret-string
JWT_EXPIRES_IN=7d

# Email (Nodemailer)
SMTP_HOST=smtp.gmail.com
SMTP_PORT=587
SMTP_USER=your-email@gmail.com
SMTP_PASS=your-app-password

# Twilio SMS
TWILIO_ACCOUNT_SID=ACxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
TWILIO_AUTH_TOKEN=your-auth-token
TWILIO_PHONE_NUMBER=+1234567890

# Translation (optional)
LIBRETRANSLATE_URL=https://libretranslate.com
GOOGLE_TRANSLATE_API_KEY=your-translate-key
```

**Step 10:** Create the frontend environment file
```bash
cd ../frontend
cp .env.example .env
```

```env
REACT_APP_API_URL=http://localhost:5000/api
REACT_APP_ENV=development
```

**Step 11:** Start the backend server
```bash
cd backend
node server.js
# Expected output: ✅ Server running on port 5000 | ✅ MongoDB connected
```

**Step 12:** Start the frontend in a new terminal
```bash
cd frontend
npm start
# Expected output: ✅ Compiled successfully | App opens at http://localhost:3000
```

**Step 13:** (Optional) Register a service worker for offline mode
```bash
# In frontend/public/service-worker.js — already included
# Browser will auto-register on first load
# Check: Chrome DevTools → Application → Service Workers
```

**Step 14:** Verify everything works
```
Open: http://localhost:3000
Login as Doctor → Enter a sample discharge note → Click "Simplify"
Expected: Structured care card generated in < 5 seconds
```

---

## 🛠️ Implementation Plan

### Phase 1 — Project Foundation (Days 1–2)

**Step 1:** Initialise the project structure
```
mkdir discharge-compass-ai
cd discharge-compass-ai
mkdir frontend backend
```

**Step 2:** Set up backend with Express
```bash
cd backend
npm init -y
npm install express mongoose dotenv cors bcryptjs jsonwebtoken
npm install nodemailer twilio qrcode node-cron openai
npm install --save-dev nodemon
```

**Step 3:** Create `server.js` entry point with MongoDB connection and all route imports

**Step 4:** Define MongoDB schemas for Patient, CareRecord, Compliance, and AlertLog

**Step 5:** Set up React frontend
```bash
cd ../frontend
npx create-react-app .
npm install axios tailwindcss react-router-dom react-qr-code
npx tailwindcss init
```

---

### Phase 2 — Core AI Feature (Days 3–4)

**Step 6:** Build the AI simplification service
```
backend/services/aiService.js
→ Accept raw clinical text
→ Send structured prompt to OpenAI
→ Parse response into: medications, symptoms, followup, summary
→ Return structured JSON
```

**Step 7:** Build the `/api/simplify` endpoint (POST)

**Step 8:** Test AI output with 5 real-world discharge note samples

**Step 9:** Build rule-based NLP fallback parser for offline environments

---

### Phase 3 — Frontend UI (Days 5–6)

**Step 10:** Build `DoctorInput.jsx` — two-panel layout with text input on left

**Step 11:** Build `PatientDashboard.jsx` — structured care card on right

**Step 12:** Build `MedicationCard.jsx` — colour-coded AM/PM/Night table
```
Morning = Yellow | Afternoon = Orange | Night = Blue
```

**Step 13:** Build `RedFlagAlert.jsx` — red banner with symptom list and emergency button

**Step 14:** Build `FollowUpChecklist.jsx` — interactive tick-off checklist

**Step 15:** Add print-to-PDF functionality using `window.print()` with custom CSS

---

### Phase 4 — Unique Features (Days 7–9)

**Step 16:** Implement Voice Assistant
```
frontend/components/VoiceAssistant.jsx
→ Use Web Speech API (SpeechSynthesis)
→ Play all care plan sections on button click
→ Language synced with selected translation
```

**Step 17:** Implement QR Smart Card
```
backend/services/qrService.js
→ Generate QR code pointing to /patient/:id/care-plan
→ Embed in printable card layout
→ Cache plan in IndexedDB for offline access
```

**Step 18:** Implement Multilingual Support
```
backend/services/translationService.js
→ Translate structured care plan fields
→ Cache translations in MongoDB
→ Frontend: LanguageSelector component with 10 language flags
```

**Step 19:** Implement Caregiver Alert System
```
backend/services/notificationService.js
→ Register caregiver email/phone at discharge
→ Send alert via Nodemailer + Twilio on:
    - Missed dose (after 2-hour grace window)
    - Red-flag symptom self-reported
    - Compliance < 50%
```

**Step 20:** Implement Compliance Score Tracker
```
frontend/components/ComplianceScore.jsx
→ Patient ticks doses daily
→ Score = (completed / total) × 100
→ Weekly auto-report emailed to doctor
```

---

### Phase 5 — AI Risk + Timeline (Days 10–11)

**Step 21:** Implement AI Risk Prediction Engine
```
backend/services/aiService.js (extended)
→ Analyse: diagnosis codes, number of medications, red-flag count
→ Assign: LOW / MEDIUM / HIGH risk score
→ HIGH risk = auto-flag on admin dashboard
```

**Step 22:** Implement Visual Health Timeline
```
frontend/components/HealthTimeline.jsx
→ Day-by-day milestone display
→ Patient marks daily status
→ Doctor views remotely on dashboard
```

**Step 23:** Implement Smart Reminder Intelligence
```
backend/services/reminderService.js
→ Schedule cron jobs per patient medication times
→ If dose missed: re-notify → escalate to caregiver → log in compliance
→ Adaptive: learns optimal notification time per patient
```

---

### Phase 6 — Offline Mode & PWA (Day 12)

**Step 24:** Register Service Worker for offline caching
```
frontend/public/service-worker.js
→ Cache: care plan HTML, assets, API responses
→ Fallback to cached data when offline
→ Sync compliance data when back online
```

**Step 25:** Implement IndexedDB storage for local care plan persistence

---

### Phase 7 — Auth & Security (Day 13)

**Step 26:** Implement Doctor registration + login with JWT

**Step 27:** Implement Patient/Caregiver access via QR token (no password required)

**Step 28:** Add HTTPS enforcement and input sanitisation

---

### Phase 8 — Testing & Deployment (Days 14–15)

**Step 29:** Test all features with real discharge note samples
```
Test cases:
1. Cardiac discharge with 5 medications
2. Post-surgery discharge with wound care instructions
3. Diabetic discharge with diet and insulin schedule
4. Paediatric discharge (children's ward)
5. Non-English-speaking patient simulation
```

**Step 30:** Deploy frontend to Vercel
```bash
cd frontend
npm run build
vercel deploy
```

**Step 31:** Deploy backend to Railway
```bash
cd backend
railway up
```

**Step 32:** Connect MongoDB Atlas to production backend

**Step 33:** Set all production environment variables in Vercel and Railway dashboards

**Step 34:** Final end-to-end smoke test on production URL

---

## 📈 Impact

| Metric | Expected Outcome |
|---|---|
| 🏥 Hospital Readmissions | 30–40% reduction in 30-day readmissions |
| 💊 Medication Errors | 50%+ reduction in patient-reported errors |
| 🌍 Language Inclusion | 10+ regional language communities served |
| 👴 Accessibility | Elderly + low-literacy patients fully supported via voice |
| 📊 Compliance | Real-time adherence tracking for 100% of discharged patients |
| ⚡ Response Time | Care plan generated in < 5 seconds from raw clinical text |

---

## 🏁 Conclusion

**Discharge Compass AI** is not just a tool — it is a **systemic healthcare intervention**.

By combining AI simplification, multilingual accessibility, caregiver coordination, offline resilience, and compliance intelligence into a single patient-facing platform, it directly addresses the most critical and underserved gap in the current healthcare delivery system: **the moment a patient walks out of the hospital door**.

> Built with ❤️ for patients who deserve to understand their own health.

---

## 💥 Built For

| Domain | Focus |
|---|---|
| 🏥 Healthcare | Patient Safety |
| 🤖 AI/ML | Clinical NLP |
| 🌍 Social Impact | Health Equity & Accessibility |
| 📱 Mobile-First | Rural & Low-Connectivity Regions |

---

<div align="center">

**⭐ Star this repo if Discharge Compass AI inspires you to build for impact.**

</div>
