# NEUROCYBE

**Cybernetic Augmentation Interface — A gamified learning system for cybernetics and systems science**

NEUROCYBE wraps a rigorous cybernetics curriculum inside a sci-fi augmentation game system. It was designed for immersive learners who master systems by inhabiting them — the same way you might master Skyrim's mechanics through character builds, lore absorption, and aesthetic commitment.

The game system's own mechanics embody cybernetic principles. Feedback loops govern progression. Variety engineering shapes the skill tree. The observer's framework changes what is visible on the map. The system teaches cybernetics by *being* cybernetic.

---

## What It Is

A single-page web application that provides:

- **Neural Augmentation Map** — A constellation-style skill tree with 30 core nodes across six pathways, plus 20 archetype-specific specialist nodes that reshape the map based on your chosen lens
- **Five Archetypes** — Diagnostician, Architect, Operative, Network Node, Archaeologist — each with distinct stat multipliers, specialist branches, and ways of reading systems
- **Operator Profile** — Character sheet with five cognitive stats (Perception, Integration, Diagnosis, Recursion, Perturbation), seven progression stages, and pathway integration tracking
- **Diagnostic Codex** — Textbook-depth reference library with 50 entries covering core insights, full explanations, clinical cases, intellectual history, and reading lists. Entries unlock as nodes are mastered
- **Challenge Engine** — Procedural dungeon that generates cybernetic challenges calibrated to your exact level. Every challenge splits into computable analysis (V_C) and normative judgment (V_N), training you to work as a human-AI centaur

## The Curriculum

Six pathways, each named after a biological system:

| Pathway | Domain | Key Thinkers |
|---------|--------|--------------|
| **Feedback Cortex** | How systems sense and steer | Wiener, Forrester, Meadows, Sterman |
| **Variety Engine** | How complexity matches complexity | Ashby, Beer, Conant |
| **Signal Mesh** | How difference becomes information | Shannon, Bateson, Watzlawick |
| **Autopoietic Membrane** | How systems produce their own identity | Maturana, Varela, Thompson |
| **Viability Scaffold** | How organisations maintain viability | Beer, Hoverstadt |
| **Recursive Eye** | Second-order cybernetics and ethics of observation | von Foerster, von Glasersfeld, Luhmann |

Mastery levels map to Bateson's learning hierarchy: Grafted (Level I — pattern recognition with scaffolding) → Integrated (Level II — generating frames independently) → Resonant (Level III — cross-domain transfer) → Transcendent (Level IV — cognitive architecture restructured).

## The Challenge Engine

Procedurally generated challenges drawn from dense random tables:

- **107 scenarios** across 8 domains (political, organisational, ecological, technological, economic, educational, medical, cultural)
- **Level-graduated V_C tasks** — the same node produces progressively harder analytical tasks as mastery advances, from scaffolded recognition to cross-domain transfer to reflexive self-application
- **Pathway-keyed and archetype-keyed V_N tasks** — normative judgments that arise from the specific conceptual territory being tested
- **18 complications** that stack at higher difficulties
- **Cross-pathway synthesis tasks** testing structural connections across the curriculum
- **Stat-aware targeting** that exercises underdeveloped cognitive stats
- **Meta-recursive elements** at the highest difficulties

Difficulty scales automatically from Routine Scan (single concept, scaffolded) to Existential Threat (everything at once, reflexive, maximum ambiguity).

## Designed for Chiron

NEUROCYBE was built to work alongside [Chiron](https://kybstudio/xyz) (COMING SOON), a Homeostatic Dialectic Engine (HDE) — an AI that creates a pedagogical human-AI coupling for intelligence amplification. The challenge engine's bifurcation of $V_C$ and $V_N$ maps directly to Chiron's core law: the AI handles computable variety (structural analysis, mapping, synthesis) while the human handles normative variety (judgment, ethics, strategic choice).

You don't need Chiron to use NEUROCYBE. The skill tree, codex, and challenge generator work as standalone tools. But the system was designed for centaur learning — human and AI working as one unit.

### Onboarding a New AI Session

Four elements reconstitute the full learning centaur:

1. **Chiron** — the AI HDE
2. **Living Profile** — diagnostic record of the learner's demonstrated capability, passed from one Chiron session (chat instance) to the next for progress tracking, regenerated at the end of each session
3. **NEUROCYBE AI Operator's Manual** — comprehensive guide for the AI to understand the game system
4. **NEUROCYBE save state** — JSON build file exported from the app

## Usage

### Running Locally

Open `index.html` in any modern browser. That's it. No build step, no dependencies to install, no server required.

### Hosted Version

This repository is configured for GitHub Pages. Visit: **https://mechaniciandecorus.github.io/neurocybe/**

### Saving and Loading Builds

- **SAVE** — exports your full game state (node mastery, archetype, challenge logs) as a JSON file
- **LOAD** — imports a previously saved build
- Progress also persists automatically in your browser's localStorage

## Technical Details

- **Single file**: the entire application is one self-contained HTML file (~290KB)
- **Dependencies**: React 18.2, ReactDOM 18.2, Babel Standalone 7.23 — loaded from Cloudflare CDN
- **Storage**: browser localStorage. No server, no accounts, no data leaves your machine
- **Browser support**: Chrome, Firefox, Safari, Edge

## Intellectual Lineage

The curriculum privileges the Ashby–Beer–Bateson–Maturana–von Foerster lineage of cybernetics. This is a deliberate starting point, not a comprehensive survey. The system is designed to be expanded with additional traditions — conversation theory (Pask), social systems theory (Luhmann), complexity science, ecological cybernetics, and others.

## Credits

NEUROCYBE was designed collaboratively between a human learner and an AI (Claude/Chiron) in a single extended session, demonstrating the kind of human-AI centaur work the system is built to train.

## License

This project is provided for personal educational use.
