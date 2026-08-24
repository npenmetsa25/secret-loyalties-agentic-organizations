# Secret Loyalties in Agentic Organizations — Code

Supplementary code for the Apart Research Secret Loyalties Hackathon (July 2026) submission
*"Secret Loyalties in Agentic Organizations"* (Nabita Penmetsa).

## What's here

`budget_allocation_colab.ipynb` — a single, self-contained Colab notebook implementing all
three experiments reported in the paper:

1. **Mechanical detectability** — a naive secret loyalty in a single centralized budget-allocation
   agent, checked against an auditable policy formula.
2. **Detection-awareness and input ambiguity** — a stress test crossing whether the agent is told
   it may be audited against whether the input data is ambiguous.
3. **Centralized vs. decentralized blast radius** — splitting decision rights across two
   independent regional agents, under clean / one-compromised / both-compromised conditions.

Each section includes the scenario data, prompts, parsing/scoring logic, and the statistical
analysis (Welch's t-tests) reported in the paper's Results section.

## Paper

Full write-up, including the coordination-structure framing (Anand & Mendelson, 1997; Anand &
Penmetsa, 2023) and the "organizational leverage" concept this code tests, is in the submitted
report.
