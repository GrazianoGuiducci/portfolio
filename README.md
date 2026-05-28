# Graziano Guiducci AI-DND Portfolio

Dal 2022 sviluppo il livello operativo attorno all'IA agentica: sistemi che
preservano il contesto, verificano i propri risultati, ricordano i fallimenti,
rendono visibile il proprio stato e trasformano le modalità di fallimento
ricorrenti in strumenti riutilizzabili.

Questo portfolio presenta una selezione di lavori su laboratori autonomi,
kernel cognitivi, interfacce semantiche, logica D-ND, persistenza del contesto
e flussi di lavoro di agenti a lungo termine. È scritto per una revisione
tecnica: cosa esiste, cosa può essere ispezionato, cosa è maturo e cosa rimane
sperimentale.

Il ragionamento di alto livello sul modello D-ND è il livello di base di
questo lavoro. Dà forma a meta-prompt, strumenti, dashboard, misure di
sicurezza, cicli di valutazione e modelli operativi riutilizzabili.

## Start Here

1. [Evidence Map](docs/reviewer-evidence.md) — what to inspect first and why.
2. [D-ND Lab](projects/dnd-lab/README.md) — live autonomous lab system.
3. [d-nd-seed](projects/dnd-seed/README.md) — active portable AI-coder seed,
   hooks, memory, safety, and lab pattern.
4. [THIA](projects/thia/README.md) and [Gödel / CEC](projects/godel/README.md)
   — operating surface, crivello, inversion, memory, routing and public use.
5. [D-ND Physics Lab](projects/dnd-lab-physics/README.md) — applied research
   domain proving Lab transfer.
6. [D-ND Papers](projects/dnd-papers/README.md) — formal kernel and Paper Zero.
7. [Project Index](projects/index.md) — wider trajectory and maturity levels.
8. [Work Profile](work/one-page-profile.md) — compact profile for roles and
   collaborations.

## Il quadro tecnico

Il lavoro nasce da un problema operativo e da una direzione più ampia: rendere
i sistemi di IA capaci di occuparsi di processi complessi in modo affidabile,
ispezionabile e consapevole. La continuità comprende il recupero del contesto e
la capacità del sistema di osservare il proprio stato, verificare le proprie
uscite, imparare dai fallimenti e propagare le regole che funzionano.

Questo quadro include:

- continuità del contesto tra sessioni, compattazioni e passaggi di nodo;
- memoria esplicita di decisioni, fallimenti, residui e prossime azioni;
- cicli claim / contro-claim con crivello CEC, Domandatore, Gödel,
  controprove, Proiettore e cristallizzazione;
- dashboard e superfici che rendono visibile stato, incertezza, vincoli e
  traiettoria;
- kernel cognitivi, meta-prompt, skill, seed installabili e template di Lab;
- autologica e autopoiesi: il sistema osserva il proprio funzionamento e
  trasforma ciò che regge in regola operativa.

Il punto operativo è semplice: il lavoro dell'IA diventa affidabile quando
contesto, verifica, memoria, visibilità e crescita interna diventano
struttura.

## Portfolio Axes

- **Programmable awareness**: boot, memory, state, recovery, verification, and
  handoff rules for long-running AI agents.
- **Autonomous research labs**: cycles that generate claims, test them, record
  failures, and move across domains.
- **CEC, inversion and decision operators**: tools that turn a tension into a
  crivello, a shifted viewpoint, a residue, and a next question.
- **Agentic UX and state surfaces**: dashboards and interfaces that expose
  live state, constraints, uncertainty, and review paths.
- **Portable cognitive kernels**: seeds, skills, and local operating genomes
  that make useful agent behavior installable.

## Strongest Evidence

- **D-ND Lab**: a live multi-domain lab runtime with cycles, reports,
  falsification, state dashboard, and reusable domain templates.
- **d-nd-seed**: an active portable seed for AI coders, with hooks, compact
  recovery, safety guards, skills, install profiles, and the Lab pattern.
- **THIA / Gödel / CEC**: a live operating surface where memory, routing,
  public/private lenses, crivello, inversion and Lab workflows meet.
- **D-ND Physics Lab**: applied evidence that the lab engine transfers beyond a
  demo surface.
- **D-ND Papers / Paper Zero**: the compact formal source behind the D-ND
  operating logic.

## Current Public Surfaces

- Main site: https://d-nd.com
- Lab subdomain: https://lab.d-nd.com
- Lab dashboard: https://lab.d-nd.com/dashboard/
- Seed repository: https://github.com/GrazianoGuiducci/d-nd-seed
- Lab repository: https://github.com/GrazianoGuiducci/D-ND_LAB
- Portfolio repository: https://github.com/GrazianoGuiducci/portfolio

## How to Read It

The fastest path is practical first, theory second:

- open the live Lab dashboard;
- read the D-ND Lab and d-nd-seed cards;
- use the evidence map to decide which repository or document to inspect;
- then read Paper Zero with the systems already in view.

Older or archived projects provide trajectory context for the current systems.
