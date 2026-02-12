# Yasser Gandhi Hernández Esquivel

**Technical Implementation & Integration Diagnostics**  
SaaS Onboarding · API Troubleshooting · Customer Enablement  

📍 Mexico City · Remote · German C1 · English Professional**
📫 yassergandhi.dev@gmail.com  
🌐 yassergandhi.dev  
🔗 linkedin.com/in/yassergandhi  

# 👋 Yasser Gandhi Hernández Esquivel


I bridge the gap between **what a system delivers** and **what a user understands**. 
I don't just debug code; I diagnose why the user got confused in the first place.

I'm currently seeking a role in **Application Support, Implementation Engineering, or Technical Enablement** where I can use my hybrid background (Linguistics + Pedagogy + Systems) to reduce onboarding friction and prevent recurring production issues.

---

## 🧠 What I Actually Do

- **Formalize tacit knowledge** – Convert undocumented "rules" (pedagogy, business logic) into **executable contracts** (Zod, TypeScript).
- **Design for operational reality** – I build identity resolution systems that work on mobile phones without forcing users to log in.
- **Instrument for support** – I expose `Trace IDs`, `Latency`, and `Status Codes` in the UI so Support Engineers don't need to dig through logs.
- **Reduce Implementation Gaps** – I analyze where the system's *model* doesn't match the user's *mental model*, and fix the contract.

---

## 🔧 Technical Stack

**API & Integration:**  
`REST` · `JSON` · `HTTP` · `Authentication (JWT/OAuth)` · `Webhook Debugging` · `Postman` · `HAR Analysis`

**Languages & Frameworks:**  
`TypeScript` · `React` · `Astro` · `Node.js` · `Zod` · `Tailwind`

**Databases & Backend:**  
`Supabase` · `PostgreSQL` · `Google Apps Script`

**Practices:**  
`Domain-Driven Design (DDD)` · `Contract Testing` · `Root Cause Analysis` · `Incident Reproduction` · `Runbook Creation`

**Languages:**  
Spanish (Native) · English (Professional) · German (C1)

---

## 📌 Featured Projects

These are not tutorials. They are production-inspired systems built to solve real user friction.

### 🎓 **huhuGERMAN – Domain-Driven Pedagogy & Identity Resolution**
*[Archived · Post-Mortem · Learning Artifact]*

**Context:**  
University students (UAM) needed asynchronous writing feedback. They submitted via Google Forms on mobile. Google’s authentication was unreliable. Emails were misspelled. The system had to be **tolerant, not brittle**.

**What I built:**
- **Domain Model:** Formalized 10 weeks of A1/A2 curriculum into `Zod` schemas (200+ lines of constraints). The schema explicitly defines *what was taught* and *what the AI is forbidden to correct*.
- **Identity Resolution (Zero Auth):** SHA-256 fingerprinting using email, name, and student ID. UUID generation server-side. No user lockouts. No support tickets for "I can't log in."
- **Observability:** Pedagogical context is snapshotted in JSONB with every submission, enabling full auditability.

**Stack:** `Astro` · `Supabase` · `Zod` · `PostgreSQL` · `Google Apps Script`  
**Repositories:**
- [`huhugerman-portal`](https://github.com/yassergandhi/huhugerman-portal) – Student-facing UI, mobile-first.
- [`huhugerman-cse`](https://github.com/yassergandhi/huhugerman-cse) – Identity engine, ADR, sanitization logic.

---

### ⚙️ **Resilient API Integration Demo (Fault Injection)**
*[Active Demo]*

**Context:**  
I needed to practice diagnosing production issues (401s, 500s, latency) without crashing a real system. I built an SDK that intentionally breaks.

**What I built:**
- **Chaos Engineering SDK:** `lessonApi.ts` injects 20% failure rates (401/500) and 300-1500ms latency jitter.
- **Support Tooling:** A Debug Panel embedded in the UI displays `Trace ID`, `Latency`, and `Status Code` in real-time. This allows a support engineer to diagnose a customer issue without access to backend logs.
- **Error Boundaries:** Graceful degradation with "Retry" logic.

**Stack:** `React` · `TypeScript` · `Tailwind`  
**Live Demo:** [huhugerman-demo-cse.netlify.app](https://huhugerman-demo-cse.netlify.app/)  
**Repo:** [`huhugerman`](https://github.com/yassergandhi/huhugerman)

---

## 📈 Recent Activity

<!-- GITHUB ACTIVITY: This section is manually updated to show consistent work -->
- **[2026-02]** Refactored `week-context.schema.ts` to separate `gelernt` (learned) vs `nicht_gelernt` (not yet learned) – prevents AI over-correction.
- **[2026-01]** Published ADR: "Why we chose identity resolution over authentication."
- **[2026-01]** Built `identity-normalization.gs` – Google Apps Script to sanitize 500+ student records without manual intervention.

---

## 📫 Contact

- **Email:** yassergandhi.dev@gmail.com  
- **Portfolio:** [yassergandhi.dev](https://yassergandhi.dev)  
- **LinkedIn:** [linkedin.com/in/yassergandhi](https://linkedin.com/in/yassergandhi)

---

*"Sistema roto ≠ Persona defectuosa."*  
*I help teams understand why their system is breaking user trust.*
