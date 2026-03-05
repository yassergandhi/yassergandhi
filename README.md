# Yasser Gandhi Hernández Esquivel
**Learning Systems Architect · Germanista C1 · Senior Developer**  
📍 Mexico City · Remote  
🌐 [yassergandhi.dev](https://yassergandhi.dev) · [huhugerman.com](https://huhugerman.com)  
💼 [linkedin.com/in/yassergandhi](https://linkedin.com/in/yassergandhi)

---

## The problem this profile exists to solve

41% of international students in Germany drop out before graduating (DAAD, Reucher 2019).  
The dominant cause: the gap between *Hochdeutsch* taught in classrooms and  
*Umgangssprache* encountered on Day 1 in Hamburg, Berlin, or Munich.

I built the technical infrastructure for an instructional system designed  
specifically for this gap: **huhuGERMAN** — operational since 2011, first documented case 2022.

---

## What I actually do

Three competencies that rarely coexist in a single profile:

| Competency | What it means in practice | Verifiable evidence |
|---|---|---|
| **DaF Researcher-Practitioner** | 15 years A1–C1 instruction, CELEX-UAM Azcapotzalco. Two UNAM theses. 11 Scopus peer-review contributions. Active sinodal. | SEP credentials, RIEM, RDU UNAM Vol.18(5) |
| **C1 Germanist** | B.A. German Literature, UNAM. C1 certified Offenburg 2019. Hamburg fieldwork 2019. Documented acquisition episodes. | Offenburg certificate, lic. thesis 2015 |
| **Learning Systems Architect** | B.Sc. Web Development, UdeG — GPA 98.5. TypeScript, Zod, Astro, Google Apps Script. huhuGERMAN v10 in production. | SEP cédula 15344700, GitHub repositories |

The concrete intersection: someone who writes Zod schemas for pedagogical domains and publishes in Scopus-indexed journals.

---

## huhuGERMAN — technical overview

A data pipeline that turns classroom pedagogy into structured, analyzable evidence.
```
Google Form (async student input)
    → GAS v10 trigger (onFormSubmit)
    → ENTREGAS sheet (25-column typed schema)
    → Weekly analysis layer
```

**Key architectural decisions:**
- Domain-driven: pedagogical logic is the source of truth, not the backend
- `e.values[]` mapping over sheet reads — atomic, trigger-safe
- SHA-256 student ID hashing — privacy by design
- Branching by level (A1 / A2) within a single trigger function
- No external dependencies in the core pipeline (Notion and Supabase deliberately removed from v10)

**Stack:** Google Apps Script · TypeScript · Zod · Astro · Google Sheets API

---

## Research & academic record

**Current project:** *huhuGERMAN: authentic input with metacognitive scaffolding in A1 German for Mexican university students* — target journal: *Die Unterrichtspraxis* (AATG), submission May 2026.

**Central claim:** Authentic German input is processable from A1 *if and only if* four conditions are met: explicit metacognitive framing, operational distinction between global and selective comprehension, normalized repeated listening, and calibrated Umgangssprache exposure from initial stages.

**Theoretical framework:** Krashen · Long · Vygotsky · MacIntyre et al. 1998 (WTC) · Vandergrift · Byram 1997 · Norton/Block · Gadamer (Bildung) · Borg (practitioner-researcher) · Phillipson 1992 · Medgyes 1994

**Publication record:**
- 11 Scopus peer-review contributions (active reviewer, RIEM — UNAM Faculty of Medicine)
- "El viaje de Emilio" — RDU UNAM Vol. 18(5), 2017 (Case 01, documented)
- MEd thesis, UNAM Pedagogy, 2020 — diagnoses 41% dropout correlation with Hochdeutsch/Umgangssprache gap
- BA thesis, UNAM German Literature, 2015 — *Keine Panik*: first Vandergrift application at A1

---

## Current repositories

Work in this account documents real instructional systems, not tutorial projects.

- `huhuGERMAN-stack` — Google Apps Script pipeline, v10. Typed submission processing for A1/A2 cohorts.
- `huhugerman.com` — Astro-based academic site
- `yassergandhi.dev` — professional/portfolio site

---

## Languages

🇩🇪 German — C1 (Offenburg, 2019)  
🇲🇽 Spanish — native  
🇺🇸 English — professional working proficiency

---

## Contact

`yghe@azc.uam.mx` · UAM Azcapotzalco, CELEX  
Available for: AI annotation (linguistic + code quality, German/Spanish/English) · EdTech consulting · DaF curriculum development · TypeScript freelance (DACH market)
