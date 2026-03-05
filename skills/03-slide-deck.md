# Skill 03 — Interactive Slide Deck (Web PPT)

## What this skill does
Create a PPT-style **interactive web presentation** using a single HTML file.
Designed for **ideathon demos, pitches, and storytelling**.
Slides are navigable via keyboard or click and can be deployed on GitHub Pages.

---

## When to use
- Ideathon / Hackathon pitch
- Product or concept demo
- Strategy storytelling
- Executive-friendly presentations (non-technical audience)

---

## Input you should give Copilot
- Topic or project name
- Target audience (e.g. judges, business leaders)
- Number of slides (recommended: 5–7)
- Tone (business / visionary / simple)
- Language (Chinese / English / mixed)

Example:
> Build a 7-slide ideathon pitch for “Work Sphere”.
> Audience: business judges.
> Tone: clear, visionary, non-technical.
> Language: Chinese with simple English headings.

---

## Expected output
- A **single `index.html` file**
- Includes embedded CSS + JavaScript
- Features:
  - Full-screen slides
  - Keyboard navigation (← → / space)
  - Simple animations (fade / slide)
  - Clean, professional layout

---

## Recommended slide structure
1. Title / Vision  
2. Problem  
3. Insight or Opportunity  
4. Solution / Concept  
5. Value / Impact  
6. Demo or Scenario  
7. Call to Action  

Each slide:
- 1 headline
- 3–5 concise bullet points
- Judge-friendly language

---

## Usage prompt (copy to Copilot Chat)
Use **Skill 03 – Interactive Slide Deck**.

Create a web-based slide deck as a single HTML file.
Follow the structure and rules defined in skills/03-slide-deck.md.
Output `index.html` only.
Ensure it works when deployed via GitHub Pages.

---

## Deployment
1. Commit `index.html` to the repo
2. Enable GitHub Pages (deploy from branch)
3. Share the generated URL for live presentation

---

## Quality checklist
- Slides are readable on laptop screen
- No technical jargon unless explained
- Story flows logically
- Works with keyboard navigation
