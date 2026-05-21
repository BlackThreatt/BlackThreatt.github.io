# Embedded Systems Self-Training Programme

A structured self-training curriculum I built with the help of Claude while job searching to bridge the gap between STM32 support/validation work and embedded software development. Covers layered C architecture, FreeRTOS internals, control theory, and motor control on STM32 — the kind of hands-on development experience that debugging someone else's system doesn't naturally give you.

The site is hosted on GitHub Pages and documents the full programme: weekly breakdowns, hardware BOM and helpful resources. Everything is public and reproducible. If you're in a similar position transitioning from support or validation into development, the curriculum is designed to be followed as-is.

---

## What's covered

**Phase 1 — Foundations** (6 weeks): layered C architecture, HAL design, state machines, memory management, unit testing with Unity and Ceedling.

**Phase 2 — RTOS** (8 weeks): FreeRTOS internals, IPC primitives, priority inversion and deadlock, DMA integration, LwIP Ethernet, SystemView profiling, fault handlers.

**Phase 3 — Control theory and motor control** (10 weeks): PID design and simulation, DC motor modelling, BLDC trapezoidal commutation, Field-Oriented Control (FOC) on STM32, CAN telemetry, multi-layer fault protection.

**Phase 4 — Professional readiness** (5 weeks): MISRA-C 2012 compliance, Ceedling CI pipeline on GitHub Actions, portfolio documentation, embedded C and RTOS interview preparation.

---

## Site structure

| File | Contents |
|---|---|
| `index.html` | Curriculum overview and phase navigation |
| `phase1–4.html` | Week-by-week detail: reading, exercises, daily schedule, project milestones |
| `hardware-bom.html` | Hardware BOM with prices, software tools, books, free references |
| `about.html` | Personal page |
| `blog.html` | Technical posts from the programme |

---

## Stack

Pure HTML and CSS — no framework, no build step, no dependencies. Works offline. Open any HTML file in a browser or serve locally with `python3 -m http.server 8000`.

---

## Background

I spent a year doing STM32 application engineering at STMicroelectronics (Ethernet stack debugging, PHY configuration, firmware validation) and seven months doing embedded software development at Aptyx (C/C++ on RTOS platforms, hardware-software integration). Support and validation work builds real debugging depth but doesn't naturally build the architecture and design muscle that development roles expect. This programme was built to close that gap deliberately.

---

*Mohamed Ali Bessaidi · [linkedin.com/in/MohamedABessaidi](https://linkedin.com/in/MohamedABessaidi) · BessaidiMohamedAli99@gmail.com*
