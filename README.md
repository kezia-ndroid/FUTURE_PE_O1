#  FUTURE_PE_01                                                      
** AI Website Copy Generator — GlowRoots Skincare**


---

## Business Chosen

**Business:** GlowRoots Skincare
**Type:** D2C skincare brand (Indian market)
**Location:** Kerala, India (ships pan-India)
**Product Focus:** Natural face serum with niacinamide + turmeric
**Target Audience:** Women aged 18–32 dealing with pigmentation, dark spots, and dull skin
**Tone:** Warm, trustworthy, science-backed but approachable

---

## What This Repository Contains

| File | Description |
|---|---|
| `README.md` | Project overview, business context, prompt logic |
| `prompt.md` | Structured prompts for homepage, services, and CTA sections |
| `homepage_copy.md` | Headline, sub-headline, intro, value proposition copy |
| `services_copy.md` | Product/service descriptions for each offering |
| `cta_copy.md` | All CTA sections — booking, trust, urgency, location |

---

## Prompt Logic Explained

The prompt system was built in 3 layers:

### Layer 1 — Business Context Block
Every prompt starts with a standard context block:
```
Business name, type, location, target audience, tone, USP
```
This prevents generic AI output and anchors all copy to one real business.

### Layer 2 — Section-Specific Instructions
Each section (homepage / services / CTA) has its own prompt with:
- The goal of that section (e.g. "make the visitor trust us in 8 seconds")
- Word count or length guidance
- Specific elements required (headline, sub-headline, bullet points, etc.)

### Layer 3 — Tone Rules
Explicit tone instructions added to every prompt:
- Write as if talking to a 24-year-old Indian woman
- Never use buzzwords like "revolutionary" or "game-changing"
- Keep sentences short — max 15 words each
- Benefit-first, feature-second

---

## Tools Used

| Tool | Purpose |
|---|---|
| Claude (claude.ai) | Primary copy generation |
| ChatGPT-4o | Headline A/B variations |
| Google Gemini | SEO keyword research for Indian skincare market |

---

## How to Reuse These Prompts for Other Clients

1. Open `prompt.md`
2. Replace the **BUSINESS DETAILS** section with your client's info
3. Keep all tone rules and section instructions unchanged
4. Run in Claude or ChatGPT
5. Minor edits only — copy is structured to be near-ready on first generation

Estimated time per new client: **15–20 minutes**

---

## Author

Built as part of the **Future Interns Prompt Engineering Internship (2026)**
Task 1: AI Website Copy Generator for Local Businesses
