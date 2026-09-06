## Nathan Knapp

Computational scientist turned software engineer, with 8+ years across scientific
computing, distributed data systems, and applied AI. Most recently I stood up the
generative AI capability at a biotech company as the sole engineer on the work.

**Santa Fe, NM · Open to work · U.S. citizen**

---

### Experience

**Gate Bioscience** — Informatics Developer II, 2024–2026. Sole engineer on most
projects, embedded with research and operations staff and owning problems from
framing through production.

- Built the company's generative AI capability from nothing: LLMs connected to
  internal databases and analysis tools over the Model Context Protocol, with the
  tool interfaces, structured outputs, and grounding needed for non-technical
  staff to rely on the answers.
- Defined the evaluation loops and acceptance criteria for AI behavior — tool
  invocation correctness and response quality against fixed tasks — which caught
  regressions before users hit them.
- Architected the production PostgreSQL schema and built Python and R pipelines
  on AWS, Docker, and Nextflow to ingest, validate, and integrate large datasets
  from external and vendor systems.

**OpenEye / Cadence Molecular Sciences** — Technical Developer II, 2020–2024,
Santa Fe. Cloud-native scientific data platform for industrial R&D. Promoted twice.

- Led technical direction of a major product, translating requirements from
  application scientists, product, and customers into shipped capability.
- Architected a configurable distributed search system over billion-scale
  molecular databases in Go, Python, and C++ — data representation, indexing
  strategy, and parallelized query execution under latency constraints.
- Set development standards, mentored developers and scientists, and managed an
  intern across a matrixed organization.

**Earlier** — meshing for cloud CFD at **SimScale** (Munich); C++ for U.S. defense
and satellite analysis at **Stellar Science**; subsurface flow simulation on HPC
clusters at **Los Alamos National Laboratory**.

**Education** — M.S. Computational Science & Engineering, TU München ·
B.S. Chemical Engineering, Yale

---

### Projects

**[climatelens](https://github.com/deknapp/climatelens)** — pick any point on
Earth and see what has already changed there, computed from ERA5 reanalysis
against a 1951–1980 baseline rather than recalled by a model. Includes a local
El Niño composite: NOAA's index says which winters since 1950 were El Niño, ERA5
says what those winters were like at that point, detrended so the warming signal
isn't double-counted, with hit rates and a permutation test on every result.

**[chilecule](https://github.com/deknapp/chilecule)** — agentic drug discovery on
entirely open-source tooling: RDKit, AutoDock Vina, fpocket, and ChEMBL exposed as
MCP tool servers and driven by Claude agents. Includes a retrospective validation
harness that runs the agents against programs whose outcomes are already known, so
the output can be scored rather than assumed.

**[otowi](https://github.com/deknapp/otowi)** — traffic simulation for northern
New Mexico: the Los Alamos commute over Otowi Bridge, and getting across Santa Fe.
Most traffic models built outside transport agencies are an OpenStreetMap network
plus randomly generated trips — they animate beautifully and mean nothing, because
the demand is invented. Here the origin–destination flows come from census LEHD
LODES data. Early, and labelled as such: nothing is calibrated yet, so no number
it produces should be believed until it is.

**[xcpredict](https://github.com/deknapp/xcpredict)** — predicts FIS Cross-Country
World Cup results from athletes' prior races, driven by the **published start list**
for the specific race. A season-long ranking will happily tell you the favourite
wins Sunday's 20 km; it does not know they skipped the trip. Elo ratings feed a
Monte-Carlo simulation, and the field comes from FIS itself, so a prediction never
contains someone who is not starting.

**[polarswim](https://github.com/deknapp/polarswim)** — Polar computes per-length
swim data in its cloud, shows it in the web app, and omits it from every file
export. This pulls it out of the private API into local SQLite. 7,600 lengths and
counting.

**[jobscout](https://github.com/deknapp/jobscout)** — an agentic job finder that
reads the applications you've already written, searches employers' own ATS boards
rather than aggregators, and enforces location constraints in code instead of
asking a model to remember them.

**[taper](https://github.com/deknapp/taper)** — a running simulator grounded in
exercise-physiology research. Oregon Trail for runners, built on a decade of my
own Strava data.

**[waxcast](https://github.com/deknapp/waxcast)** — kick and glide wax calls for
Anchorage ski trails, with the reasoning attached. Every wax chart online asks for
the air temperature, which is the wrong input twice over: wax responds to snow
temperature, and snow that has thawed and refrozen for three days behaves nothing
like fresh snow at the same reading. This works from the three-day history instead.
No build step, no server, no API key.

**[mtg_ai](https://github.com/deknapp/mtg_ai)** — sealed-deck builder that reads
your Arena pool straight from the game log, scores all ten color pairs on real
17Lands win-rate data, and checks the manabase against Frank Karsten's
castability thresholds. Python API, React front end.

**[covered-call-copilot](https://github.com/deknapp/covered-call-copilot)** —
turns a brokerage export into one ranked options-income plan. Runs on localhost;
nothing leaves the machine.

---

Reach me at nathaniel.knapp@gmail.com or on
[LinkedIn](https://www.linkedin.com/in/nathan-knapp-63012741/).
