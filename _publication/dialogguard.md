---
title: "DialogGuard: Multi-Agent Psychosocial Safety Evaluation Interface of Sensitive LLM Responses"
slug: "dialogguard"
authors:
  - "Han Luo"
  - "Guy Laban"
venue: "ACL 2026 System Demonstrations"
venue_full: "Proceedings of the 64th Annual Meeting of the Association for Computational Linguistics: System Demonstrations"
year: 2026
month: 4
category:
  - Demo
publication_type: "conference"
pdf: "/assets/pdf/DialogGuard.pdf"
demo: "https://anonymous.4open.science/r/dialogguard-web-CE7E"
image: "/assets/images/publication/dialogguard-interface.png"
abstract: "DialogGuard is an open-source web interface for psychosocial safety assessment in sensitive LLM-mediated interactions. It wraps arbitrary generative models with four LLM-as-a-judge pipelines: single-agent scoring, dual-agent correction, multi-agent debate, and majority voting. The system supports live chat and manual input workflows, visualizes per-dimension risk scores, and provides natural-language rationales for practitioner-facing auditing and supervisory decision-making."
bibtex: |
  @inproceedings{luo2026dialogguard,
    title = {DialogGuard: Multi-Agent Psychosocial Safety Evaluation Interface of Sensitive LLM Responses},
    author = {Han Luo and Guy Laban},
    booktitle = {Proceedings of the 64th Annual Meeting of the Association for Computational Linguistics: System Demonstrations},
    year = {2026}
  }
---

DialogGuard provides a practitioner-facing interface for inspecting prompted LLM agents across five psychosocial safety dimensions. It keeps practitioners in the loop by exposing both risk scores and the reasoning traces behind multi-agent judgments.

![DialogGuard evaluation mechanisms](/assets/images/publication/dialogguard-evaluation-pipelines.png)

The evaluation layer supports single-agent scoring, dual-agent correction, majority voting, and multi-agent debate over shared psychosocial safety rubrics.

![DialogGuard reasoning panel](/assets/images/publication/dialogguard-reasoning.png)

The reasoning panel surfaces step-by-step critiques and agreement signals, making the audit trail easier to inspect.
