# Youality – helloworld

Welcome to **helloworld**, the working lab for everything related to **Youality** – your personal navigation system for living with clarity, focus, and intention.

This repo is a **sandbox for experiments**:
- early UI prototypes  
- landing pages & micro-sites  
- interaction concepts  
- brand & visual explorations  

If it helps Youality come to life, it probably belongs here.

## 🌍 What is Youality?

**Youality** is a personal “life OS” designed to help people:

- Map their life areas and priorities with clarity  
- Create rhythms and rituals that support focus and wellbeing  
- Reflect intentionally and adjust course over time  
- Navigate their reality more **masterfully**, not just more efficiently  

This repo holds the **work-in-progress reality** of that vision.

## 📁 Repository Purpose

Think of this repo as:

- A **playground** for trying ideas fast  
- A **prototype archive** so good concepts aren’t lost in random folders  
- A **design + dev bridge** between brand, UX, and implementation  

Nothing here is “final.” Everything is allowed to evolve.

## 🧱 Suggested Structure

> Adjust paths and names to match your actual repo layout.

- `docs/`  
  - Notes, concept documents, diagrams, and planning  
  - High-level product thinking, flows, and architecture

- `branding/`  
  - Logos, marks, exports  
  - Brand guideline PDFs (e.g. `Youality-Brand-Guidelines.pdf`) :contentReference[oaicite:0]{index=0}  

- `web/`  
  - Landing pages, “coming soon” pages, loading screens  
  - Simple one-file HTML/CSS/JS prototypes

- `prototypes/`  
  - Larger UI explorations (e.g. React/Vite/Next)  
  - Interface concepts for Life Map, Daily Rhythm, Focus Space, etc.

- `playground/`  
  - Spike code, quick tests, and “just trying something” experiments  

## 🎨 Brand & Design System (High-Level)

Youality’s visual language is intentionally **calm, modern, and alive**.

**Core elements (see brand guidelines for full detail):**

- **Primary Palette**
  - Soft off-white background base (e.g. `#EDF4F3`)  
  - Deep teal/blue gradients (e.g. `#369799–#24769C`) for highlights  
  - Dark greys/charcoal (e.g. `#1E1E24`, black) for text and depth  

- **Typography**
  - **Manrope** as the primary typeface for all UI and communication  
  - Clear hierarchy, generous spacing, and a focus on legibility  

- **Overall Feel**
  - Clean, minimal, professional  
  - Subtle motion / micro-interactions that make things feel **quietly alive**  
  - Lots of breathing room; nothing should feel cramped or noisy  

For precise colors, typography scales, and logo usage, refer to the **Youality Brand Guideline** PDF in the repo.


## 🚀 Getting Started

Because this repo may contain different kinds of prototypes, setup is intentionally lightweight.

1. **Clone the repo**
   ```
   bash
   git clone https://github.com/<your-username>/helloworld.git
   cd helloworld
2. **Static prototypes (pure HTML/CSS/JS)**
    Open the file directly in your browser, or
    Use a simple static server:
    ```
    npx serve .
2. **JS/TS / React prototypes**
    Check the README inside each prototype folder (if present).
    Typical pattern:
    ```
    cd prototypes/<project-name>
    npm install
    npm run dev
  Or the equivalent for your chosen toolchain.


## 🧪 How to Use This Repo
Create new folders for new ideas rather than overloading one prototype.
Use folders like v1, v2, archive/ when refactoring big concepts.
Keep quick notes (NOTES.md) inside each prototype folder with:
- Intent of the experiment
- What works / doesn’t
- Next ideas
This keeps future-you (and collaborators) oriented.

## 🤝 Contribution & Workflow (for future collaborators)
Suggested simple workflow:
Branching
main – stable WIP (runs, not necessarily “shipped”)
feature branches: feature/<area>-<short-description>
e.g. feature/life-map-layout-exploration

Commits
Prefer small, clear commits:
- chore: setup base HTML scaffold
- feat: add life map sidebar navigation
- style: refine Youality gradient background
Merging
- Open a PR when a prototype is at a meaningful checkpoint.
- Document what you explored and what you learned.

## 🗺️ Roadmap (WIP)
Some example tracks this repo can support:

Brand & Visual
- Refine logo applications across light/dark backgrounds
- Define motion principles (hover, loading, transitions)

Web Presence
- “Coming Soon” page(s) that feel calm and alive
- Loading / initializing screens (Youality boot-up feel)
- Simple public landing for youality.io

Core Interface Concepts
- Life Map (overview of life areas / garden of life)
- Daily Rhythm (routines, energy patterns)
- Focus Space (deep work mode)
- Reflection (journaling, review flows)
- Technical Foundations
- Shared layout + component primitives
- Theme tokens (colors, spacing, typography)
- Update this section as the vision sharpens.

## 📝 License & Ownership
© 2025 Youality / All rights reserved

Internal WIP repository for design and development explorations.
Not intended for public reuse without explicit permission.

## 💡 Intent
This repo exists to reduce friction to experimentation.
If an idea might make Youality more aligned, more intentional, or more alive for real humans navigating their reality — it belongs here.
Happy experimenting ✨
