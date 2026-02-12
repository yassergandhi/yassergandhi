# Yasser Gandhi Hernández Esquivel

**Technical Implementation & Integration Diagnostics**  
SaaS Onboarding · API Troubleshooting · Customer Enablement  

📍 Mexico City · Remote  
📫 yassergandhi.dev@gmail.com  
🌐 yassergandhi.dev  
🔗 linkedin.com/in/yassergandhi  

---

## 👋 What I Do

I help SaaS teams **reduce integration friction and support tickets** by diagnosing where technical systems and user expectations misalign.

I don't compete with full-time engineers. I collaborate with teams that need:
- A structured eye on their onboarding and authentication flows
- Clear documentation of **why** 4xx/5xx errors happen and how to communicate them
- Root-cause analysis of recurring integration issues (webhooks, API keys, token expiration)
- Translation between customer-reported symptoms and engineering-ready hypotheses

**This is not an aspirational title. This is what I actually do — and have done — across 15 years of structured teaching and 3+ years of focused technical work.**

---

## 🧠 How I Work

| Mode | What It Means | Evidence |
|------|---------------|----------|
| **Diagnose** | 20-minute structured analysis of registration, auth, onboarding, or webhook flows. I look for where the system **increases uncertainty** instead of reducing it. | `Friction_Lab/` repository (private, examples available on request) |
| **Document** | Translate technical errors (401/403/400/500) into human-readable, actionable messages. Formalize implicit knowledge into contracts. | HuhuGerman ADR (see below) |
| **Enable** | Explain API behavior, rate limits, retry logic, and error recovery to non-technical stakeholders without humiliation. | 15 years of pedagogy; UAM enablement programs |

---

## 🧪 Featured Project: HuhuGerman

**Not a "CSE Demo." Not a "Product."**  
**A personal learning artifact — now archived — that demonstrates how I detect, diagnose, and document technical friction.**

| Stage | What Happened | What It Demonstrates |
|-------|--------------|----------------------|
| **MVP** | Built a feedback tool for real German students (UAM). Worked, but IA overcorrected. | I can ship a functional system under real constraints. |
| **Friction detected** | "The IA corrects things I haven't taught yet." | I can identify **cognitive gaps** between system behavior and user expectation. |
| **ADR written** | Formalized domain schema (Zod), separated UI from pedagogy, documented limits. | I can translate implicit knowledge into **explicit contracts**. |
| **Archived** | Project fulfilled its learning purpose. No longer active. | I can **close** without trauma — a documented decision, not abandonment. |

🔗 [Repository: huhugerman](https://github.com/yassergandhi/huhugerman)  
📄 [Architecture Decision Record (ADR) — core decisions](https://github.com/yassergandhi/huhugerman/blob/main/ADR.md)

---

## 🛠 Technical Competencies (Diagnosis-Level, Not Engineering-Level)

| Area | Proficiency | How I Use It |
|------|------------|--------------|
| **REST APIs** | Diagnose | Inspect requests/responses, identify malformed payloads, missing headers, auth failures. |
| **HTTP Status Codes** | Explain | Translate 401/403/400/500 into user-facing or team-facing root causes. |
| **JWT / OAuth** | Understand | Detect expiration, scope issues, missing Bearer prefixes. |
| **Webhooks** | Audit | Identify missing observability, unclear retry policies, opaque errors. |
| **Browser DevTools / HAR** | Analyze | Trace failed requests, latency, client-side vs server-side failures. |
| **Zod / TypeScript** | Read / minor write | Formalize simple contracts. Not a production engineer. |
| **SQL** | Read | Verify existence of data, not optimization. |

---

## 📁 Structure I Use to Work

```bash
~/Friction_Lab/
├── analysis/          # Technical, cognitive, operational, integration gaps
├── history/           # Outreach, conversations, closed deals (when they happen)
├── templates/         # Audit checklists, communication, postmortems
├── outputs/           # Reports delivered to potential clients
└── personal/          # Limits, reflections, biathlon training