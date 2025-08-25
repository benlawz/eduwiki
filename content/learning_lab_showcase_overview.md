---
title: "The Learning Lab Showcase — Full Structure"
date: 2025-08-12
tags: [agency, motivation, ai, resilience, learningdesign, showcase]
summary: "A big-picture view of the Quartz site structure, features, and design patterns, including the hub-and-spoke model."
status: draft
---

# The Learning Lab

This is the **display-ready overview** of how the site will look and work once we’ve implemented all my suggested features. It’s built to explain the big picture to collaborators and show how each part connects.

---

## 1) Vision

The Learning Lab is a **human‑first knowledge base** for agency, motivation, AI in learning, and resilience with potential to grow in many directions. It blends:

- **Personal voice** — relatable but informed.
- **Evidence + practice** — research meets action.
- **Navigation designed for exploration** — readers never hit a dead end.
- **Weekly publishing cadence** — always fresh.

- The Goal? -> **Engineering as Marketing** - building useful tools, features, and technical resources — not just for existing customers, but as a way to attract new ones.

---

## 2) Core Navigation Framework

We’ll use a **three-layer structure**:

### Layer 1 — Homepage (Entry Point)

- **Welcome intro**: short, clear value proposition.
- **Start Here section**: direct links to the 4–6 main Hubs.
- **Latest Updates section**: 3 newest posts (any type).
- **Featured Playbook or Tool**: rotating callout.

### Layer 2 — Hub-and-Spoke (Pillar Pages)

- **Hubs**: Agency, Motivation, AI & Learning Design, Resilience, Playbooks, Tools.
- Each hub lists and links all relevant content by type (Notes, Research, Playbooks, Tools).
- Spokes (individual content pages) link back to their hub with `Related:` links.
- Benefits: clear navigation, strong backlink graph, natural content clusters.

### Layer 3 — Content Pages (Spokes)

- **Notes** — short, resonant insights.
- **Research Synths** — 150–300 words, 3–5 findings + 1–2 implications.
- **Essays** — 1,000–1,500 words, opinion + evidence.
- **Playbooks** — step-by-step application guides.
- **Tools** — interactive/downloadable resources.
- **Changelog** — public updates & experiments log.

---

## 3) Content Flow

We maintain a **Note → Essay → Playbook → Tool** progression.

- Notes capture sparks.
- Essays explore context and argument.
- Playbooks turn it into repeatable action.
- Tools make it hands-on.

---

## 4) Key Features

### 4.1 Reusable Blocks

- **Try This Now**: always ends with a small action.
- **Related Links**: connects each page to others manually.

### 4.2 Tag Strategy

- Small, consistent set: `#agency #motivation #ai #resilience #learningdesign #playbook #tool #essay #research #changelog`.
- 2–4 tags per page max.

### 4.3 Visual Enhancements

- Callouts with rounded corners.
- Section dividers for readability.
- Optional light CSS tweaks for brand feel.

### 4.4 Graph & Backlink Surfing

- Quartz graph view shows hubs as central nodes.
- Clicking any spoke reveals its hub and related spokes.

### 4.5 Weekly Rhythm

- Mon/Tue: Note
- Wed/Thu: Research Synth or Essay
- Fri: Playbook or Tool update
- Changelog updated end of week.

---

## 5) Example Navigation Flow (Reader’s Journey)

```
Homepage → Hub: Agency → Playbook: Agency Starter → Tool: Inertia Breaker → Back to Hub → Explore a Research Synth → Click Related: Resilience Hub

```

The reader never hits a dead end — always another branch to follow.

---

## 6) Folder Structure in Quartz

```
/content/
  /hubs/
    agency.md
    motivation.md
    ai-learning-design.md
    resilience.md
    playbooks.md
    tools.md
  /notes/
  /essays/
  /research/
  /playbooks/
  /tools/
  /changelog/
```

---

## 7) Immediate Next Steps to Implement

1. Create `/content/hubs/` and draft **Agency** hub.
2. Add `Related` links from at least 5 spokes to that hub.
3. Update `/index.md` with Start Here + Latest Updates.
4. Add CSS tweaks for callouts.
5. Preview in Quartz and adjust.

---

**Related:** [[/hubs/agency]] · [[/playbooks/agency-starter]] · [[/tools/inertia-breaker]]

