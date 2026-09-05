## Nathan Knapp

Computational scientist turned software engineer. I build **agentic AI systems for scientific
work** — and the evaluation harnesses that decide whether their output can be trusted.

The interesting problem in applied AI isn't getting a system to produce an answer. It's getting
it to know which answers it has no business giving. Most of what I build ends up being that
second part.

**Santa Fe, NM · Open to work · U.S. citizen**

---

### Background

**Gate Bioscience** — stood up the company's generative AI capability from nothing: LLMs connected
to internal databases and analysis tools over the Model Context Protocol, with the tool interfaces,
structured outputs, and grounding needed for non-technical staff to rely on the answers. Defined
the evaluation loops and acceptance criteria that caught regressions before users hit them.

**OpenEye / Cadence Molecular Sciences** — led technical direction of a configurable distributed
search system over billion-scale molecular databases in Go, Python, and C++. Promoted twice.

Earlier: meshing for cloud CFD at **SimScale** (Munich), C++ for U.S. defense and satellite
analysis at **Stellar Science**, subsurface flow simulation on HPC clusters at **Los Alamos
National Laboratory**.

M.S. Computational Science & Engineering, TU München · B.S. Chemical Engineering, Yale

---

### What I'm building

**[chilecule](https://github.com/deknapp/chilecule)** — agentic drug discovery on entirely
open-source tooling: RDKit, AutoDock Vina, fpocket, and ChEMBL exposed as MCP tool servers and
driven by Claude agents. The part I care about is the retrospective validation harness — running
the agents against programs whose outcomes are already known, so the system's judgment can be
scored instead of trusted.

**[polarswim](https://github.com/deknapp/polarswim)** — Polar computes per-length swim data in its
cloud, shows it in the web app, and omits it from every file export. This pulls it out of the
private API into local SQLite. 7,600 lengths and counting.

**[jobscout](https://github.com/deknapp/jobscout)** — an agentic job finder that reads the
applications you've already written, searches employers' own ATS boards rather than aggregators,
and enforces location constraints in code instead of asking a model to remember them.

**[taper](https://github.com/deknapp/taper)** — a running simulator grounded in exercise-physiology
research. Oregon Trail for runners, built on a decade of my own Strava data.

**[mtg_ai](https://github.com/deknapp/mtg_ai)** — sealed-deck builder that reads your Arena pool
straight from the game log, scores all ten color pairs on real 17Lands win-rate data, and checks
the manabase against Frank Karsten's castability thresholds. Python API, React front end.

**[covered-call-copilot](https://github.com/deknapp/covered-call-copilot)** — turns a brokerage
export into one ranked options-income plan. Runs on localhost; nothing leaves the machine.

---

Reach me at nathaniel.knapp@gmail.com or on
[LinkedIn](https://www.linkedin.com/in/nathaniel-knapp-63012741/).
