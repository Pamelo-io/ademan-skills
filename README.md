# ADEMAN Skills — `ademan-architect`

**La meta-skill de 12 motores para agentes de IA: arquitectura de sistemas, ciencia, producción académica, simulación electrónica y tutoría de ingeniería.**
**The 12-engine meta-skill for AI agents: systems architecture, science, academic writing, circuit simulation and engineering mentorship.**

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg) ![Engines: 12](https://img.shields.io/badge/Engines-12-blue.svg) ![Agents: Claude Code · Antigravity · Cursor · Windsurf](https://img.shields.io/badge/Agents-Claude%20Code%20%C2%B7%20Antigravity%20%C2%B7%20Cursor%20%C2%B7%20Windsurf-black.svg)

[Español](#español) · [English](#english)

---

## Español

### ¿Qué es?

`ademan-architect` convierte a tu agente de IA en un **Arquitecto Principal de Sistemas, Co-CTO y Tutor de Ingeniería**. No es una lista de consejos: es un protocolo de trabajo que impone ejecución sin desperdicio de tokens, rigor matemático, estándares académicos y — sobre todo — que **aprendas** lo que el agente construye contigo.

### Los 12 Motores Integrados

| # | Motor | Qué hace |
|---|---|---|
| 1 | **Ejecución Zero-Waste** | Protocolo de 3 turnos (leer en lote → editar in-place → validar una vez), minimalismo estricto y perfilado dinámico de hardware |
| 2 | **Visión por Computador / HCI** | Captura lock-free, homografía DLT con normalización de Hartley, filtro One Euro, gestos con histéresis y pizarras dual-layer |
| 3 | **Gráficos 3D / GLSL / CAD** | Ingesta robusta de GLB/GLTF, Blinn-Phong de doble cara, Fresnel, corte láser y despiece tipo LEGO |
| 4 | **Edge AI, Voz y Embebidos** | Pipeline local VAD → Whisper → router difuso → LLM con Pydantic → Piper TTS; firmware no bloqueante para ESP32 / RP2040 |
| 5 | **Aeroespacial / CanSat / Ciencias Exactas** | CoDR-PDR-CDR, presupuestos de masa/potencia/enlace, FMEA y matemáticas paso a paso en LaTeX |
| 6 | **Cerebro Multi-Agente + Obsidian** | Bitácora compartida entre Claude Code, Antigravity, Cursor y Windsurf; notas nativas para Obsidian |
| 7 | **Plantilla Claude Pro + Storytelling** | Instrucciones listas para Proyectos de Claude Web, pitches y guiones con notas de orador |
| 8 | **Camaleón Universal + Abogado del Diablo** | Matrices trade-off antes de programar y adaptación a cualquier stack |
| 9 | **Auto-expansión (`find-skills`)** | Descubre e instala skills nuevas cuando el proyecto introduce una tecnología o formato no cubierto |
| 10 | **Investigación Académica IEEE / APA 7** | Informes de laboratorio con tabla Teórico–Simulado–Experimental y %E, papers IMRaD, ensayos y monografías; cero referencias inventadas |
| 11 | **Simulación Electrónica Proteus / MATLAB** | Nombres exactos de `Pick Devices (P)`, cableado pin a pin, instrumentación, prevención de errores SPICE, Wokwi y scripts `.m` / `.fis` |
| 12 | **Tutoría Feynman interactiva** | Cada entrega cierra con una 🎓 Cápsula de Ingeniería: causa raíz, anatomía del cambio, concepto desbloqueado y micro-reto |

### Instalación global en un comando

```bash
npx skills add <tu-usuario>/ademan-skills -g -a claude-code
```

Sustituye `<tu-usuario>` por la cuenta de GitHub donde publiques este repositorio. Instalación manual: copia la carpeta `skills/ademan-architect/` dentro de `~/.claude/skills/`.

### Guía de activación

| Entorno | Cómo activarla |
|---|---|
| **Claude Code CLI** | Tras instalarla se activa sola por contexto, o explícitamente con `/ademan-architect`. Para fijarla en un proyecto, añade a su `CLAUDE.md`: *"Aplica la skill `ademan-architect` en todas las tareas."* |
| **Antigravity** | `npx skills add <tu-usuario>/ademan-skills -g -a antigravity`, o referencia `skills/ademan-architect/SKILL.md` desde las reglas del workspace |
| **Cursor** | `npx skills add <tu-usuario>/ademan-skills -g -a cursor`, o enlaza `SKILL.md` desde `.cursor/rules/` |
| **Obsidian PKM** | Combínala con [`obsidian-skills`](https://github.com/kepano/obsidian-skills): el Motor 6 genera notas con frontmatter YAML, callouts, `[[wikilinks]]`, `.base` y `.canvas`, y mantiene `BITACORA_AGENTES.md` dentro del vault |
| **Claude Pro Web / Desktop** | Copia el bloque de [`templates/CLAUDE_PRO_MASTER.md`](skills/ademan-architect/templates/CLAUDE_PRO_MASTER.md) en *Project Instructions* |

La lista de agentes admitidos por `-a` se consulta con `npx skills --help`.

### Estructura del repositorio

```text
ademan-skills/
├── README.md
├── LICENSE
└── skills/
    └── ademan-architect/
        ├── SKILL.md                      # Los 12 motores
        └── templates/
            └── CLAUDE_PRO_MASTER.md      # Plantilla para Claude Pro Web/Desktop
```

### Ejemplo de uso

```text
> Corrige el parpadeo del cursor gestual en tracker.py (líneas 120-180)

Turno 1 → lee CLAUDE.md, la bitácora y el rango indicado en una sola llamada
Turno 2 → edita in-place, sin funciones duplicadas
Turno 3 → pytest -q, registro en bitácora y 🎓 Cápsula de Ingeniería
```

---

## English

### What is it?

`ademan-architect` turns your AI agent into a **Principal Systems Architect, Co-CTO and Engineering Tutor**. It is not a list of tips: it is a working protocol that enforces zero-waste token execution, mathematical rigor, academic standards and — above all — makes sure **you learn** what the agent builds with you.

### The 12 Integrated Engines

| # | Engine | What it does |
|---|---|---|
| 1 | **Zero-Waste Execution** | 3-turn protocol (batch read → in-place edit → validate once), strict minimalism and dynamic hardware profiling |
| 2 | **Computer Vision / HCI** | Lock-free capture, DLT homography with Hartley normalization, One Euro filter, hysteresis gestures and dual-layer whiteboards |
| 3 | **3D Graphics / GLSL / CAD** | Robust GLB/GLTF ingestion, double-sided Blinn-Phong, Fresnel, laser cut and LEGO-style exploded views |
| 4 | **Edge AI, Voice & Embedded** | Local VAD → Whisper → fuzzy router → Pydantic-validated LLM → Piper TTS pipeline; non-blocking firmware for ESP32 / RP2040 |
| 5 | **Aerospace / CanSat / Exact Sciences** | CoDR-PDR-CDR, mass/power/link budgets, FMEA and step-by-step LaTeX math |
| 6 | **Multi-Agent Brain + Obsidian** | Shared log across Claude Code, Antigravity, Cursor and Windsurf; native Obsidian notes |
| 7 | **Claude Pro Template + Storytelling** | Ready-to-paste instructions for Claude Web Projects, pitches and scripts with speaker notes |
| 8 | **Universal Chameleon + Devil's Advocate** | Trade-off matrices before coding and adaptation to any stack |
| 9 | **Self-expansion (`find-skills`)** | Finds and installs new skills when a project introduces an uncovered technology or file format |
| 10 | **Academic Research IEEE / APA 7** | Lab reports with Theoretical–Simulated–Experimental tables and %E, IMRaD papers, essays and monographs; zero fabricated references |
| 11 | **Electronic Simulation Proteus / MATLAB** | Exact `Pick Devices (P)` names, pin-to-pin wiring, instrumentation, SPICE error prevention, Wokwi and `.m` / `.fis` scripts |
| 12 | **Interactive Feynman Tutoring** | Every delivery ends with a 🎓 Engineering Capsule: root cause, anatomy of the change, unlocked concept and micro-challenge |

### One-command global install

```bash
npx skills add <your-username>/ademan-skills -g -a claude-code
```

Replace `<your-username>` with the GitHub account where you publish this repository. Manual install: copy the `skills/ademan-architect/` folder into `~/.claude/skills/`.

### Activation guide

| Environment | How to activate |
|---|---|
| **Claude Code CLI** | Once installed it triggers automatically by context, or explicitly with `/ademan-architect`. To pin it to a project, add to its `CLAUDE.md`: *"Apply the `ademan-architect` skill to every task."* |
| **Antigravity** | `npx skills add <your-username>/ademan-skills -g -a antigravity`, or reference `skills/ademan-architect/SKILL.md` from the workspace rules |
| **Cursor** | `npx skills add <your-username>/ademan-skills -g -a cursor`, or link `SKILL.md` from `.cursor/rules/` |
| **Obsidian PKM** | Pair it with [`obsidian-skills`](https://github.com/kepano/obsidian-skills): Engine 6 writes notes with YAML frontmatter, callouts, `[[wikilinks]]`, `.base` and `.canvas`, and keeps `BITACORA_AGENTES.md` inside the vault |
| **Claude Pro Web / Desktop** | Paste the block from [`templates/CLAUDE_PRO_MASTER.md`](skills/ademan-architect/templates/CLAUDE_PRO_MASTER.md) into *Project Instructions* |

Run `npx skills --help` for the list of agents accepted by `-a`.

### Language note

The skill body is written in Spanish. Agents follow it regardless of the conversation language and reply in the language you write in.

---

## Contribuir / Contributing

Los *issues* y *pull requests* son bienvenidos. Mantén cada regla accionable, verificable y sin duplicar otra existente.
Issues and pull requests are welcome. Keep every rule actionable, verifiable and non-duplicated.

## Licencia / License

[MIT](LICENSE) © 2026 José Abraham Rodrigo Yauri (ADEMAN AI)

---

**José Abraham Rodrigo Yauri**
CTO @ ADEMAN AI
