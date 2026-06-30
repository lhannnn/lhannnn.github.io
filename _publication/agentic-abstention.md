---
title: "Agentic Abstention: Do Agents Know When to Stop Instead of Act?"
slug: "agentic-abstention"
authors:
  - "Han Luo"
  - "Bingbing Wen"
  - "Lucy Lu Wang"
coauthors:
  - "Han Luo"
  - "Bingbing Wen"
venue: "arXiv 2026"
note: "arXiv:2606.28733"
year: 2026
month: 6
category:
  - Preprint
publication_type: "preprint"
pdf: "https://arxiv.org/pdf/2606.28733"
arxiv: "https://arxiv.org/abs/2606.28733"
code: "https://github.com/lhannnn/agentic-abstention"
demo: "/agentic-abstention/"
image: "/assets/images/agentic-abstention/timely-abstention-teaser.png"
abstract: "This work introduces agentic abstention: the problem of deciding when a tool-using language model agent should stop acting under uncertainty. Unlike single-turn abstention, agentic abstention is sequential: an agent may answer, abstain, or gather more evidence at each step. The paper evaluates LLM-as-agent systems across web shopping, terminal environments, and interactive question answering, showing that many agents abstain too late or fail to abstain when continued interaction is unhelpful. It also introduces CONVOLVE, a context-engineering method that distills interaction trajectories into reusable stopping rules."
bibtex: |
  @misc{luo2026agenticabstention,
    title = {Agentic Abstention: Do Agents Know When to Stop Instead of Act?},
    author = {Han Luo and Bingbing Wen and Lucy Lu Wang},
    year = {2026},
    eprint = {2606.28733},
    archivePrefix = {arXiv},
    primaryClass = {cs.AI},
    url = {https://arxiv.org/abs/2606.28733},
    note = {Han Luo and Bingbing Wen contributed equally}
  }
---

Agentic abstention studies when an LLM agent should stop interacting with tools and abstain instead of continuing to act. The paper frames abstention as a sequential decision problem and evaluates agent behavior across web shopping, terminal, and question-answering settings.

<img class="publication-detail-wide-image" src="/assets/images/agentic-abstention/timely-abstention-teaser.png" alt="Timely, delayed, and failed abstention trajectories">

<p class="publication-figure-caption"><b>Timely abstention.</b> An agent can abstain as soon as infeasibility is known, delay after unnecessary tool calls, or fail to abstain within the interaction budget.</p>

<img class="publication-detail-wide-image" src="/assets/images/agentic-abstention/abstention-recall.png" alt="Abstention recall curves across Web, Terminal, and QA settings">

<p class="publication-figure-caption"><b>Abstention recall.</b> Eventual abstention improves with more turns, but timely abstention remains difficult across settings.</p>
