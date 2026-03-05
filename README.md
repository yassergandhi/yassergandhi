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

## Core architecture decision (ADR, 2025)

> "The AI does not decide: it obeys the domain."

In 2024, AI feedback was correcting *Perfekt* and *Akkusativ* for students  
who had not studied those structures yet. The fix was not a better prompt.  
It was a typed pedagogical domain that enforces what can and cannot  
be corrected at each instructional stage.

```typescript
export const WochenKontextSchema = z.object({
  gelernt:       z.array(z.string()),  // structures taught
  nicht_gelernt: z.array(z.string()),  // structures not yet taught
  korrektur:     KorrekturSchema       // what AI can / cannot correct
});