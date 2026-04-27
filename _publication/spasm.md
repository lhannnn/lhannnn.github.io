---
title: "SPASM: Stable Persona-driven Agent Simulation for Multi-turn Dialogue Generation"
slug: "spasm"
authors:
  - "Han Luo"
  - "Guy Laban"
venue: "Findings of ACL 2026"
venue_full: "Findings of the 64th Annual Meeting of the Association for Computational Linguistics"
year: 2026
month: 4
category:
  - Findings
publication_type: "conference"
pdf: "/assets/pdf/SPASM.pdf"
code: "https://github.com/lhannnn/SPASM"
image: "/assets/images/publication/spasm-framework.png"
abstract: "Large language models are increasingly deployed in multi-turn settings such as tutoring, support, and counseling, where reliability depends on preserving consistent roles, personas, and goals across long horizons. SPASM is a stability-first framework for persona-driven LLM-LLM dialogue simulation. It introduces Egocentric Context Projection, which stores dialogue history in a perspective-agnostic representation and deterministically projects it into each agent's egocentric view before generation, reducing persona drift and role confusion in long-horizon simulations."
bibtex: |
  @inproceedings{luo2026spasm,
    title = {SPASM: Stable Persona-driven Agent Simulation for Multi-turn Dialogue Generation},
    author = {Han Luo and Guy Laban},
    booktitle = {Findings of the 64th Annual Meeting of the Association for Computational Linguistics},
    year = {2026}
  }
---

SPASM decomposes persona-driven simulation into persona generation, Client-Responder dialogue generation, and termination detection. The framework is designed to generate controllable multi-turn dialogue data while keeping agent roles and identities stable over long conversations.
