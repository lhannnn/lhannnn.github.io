---
title: "Plan in Sandbox, Navigate in Open Worlds: Learning Physics-Grounded Abstracted Experience for Embodied Navigation"
slug: "plan-in-sandbox-navigate"
authors:
  - "Zhixuan Shen"
  - "Jiawei Du"
  - "Ziyu Guo"
  - "Han Luo"
  - "Lilan Peng"
  - "Joey Tianyi Zhou"
  - "Haonan Luo"
  - "Tianrui Li"
venue: "ICML 2026"
venue_full: "Proceedings of the International Conference on Machine Learning"
year: 2026
month: 5
category:
  - Conference
publication_type: "conference"
pdf: "/assets/pdf/Plan_in_Sandbox_Navigate.pdf"
image: "/assets/images/publication/plan-in-sandbox-sage-agent.png"
abstract: "This work introduces SAGE, a generative experience-driven framework for embodied navigation that trains agents through physics-grounded semantic abstractions rather than relying only on photorealistic simulation. The framework synthesizes sandbox tasks, distills structured embodied experience through reinforcement learning, and transfers learned priors into open-world navigation, improving navigation performance and real-world generalization."
bibtex: |
  @inproceedings{shen2026plan,
    title = {Plan in Sandbox, Navigate in Open Worlds: Learning Physics-Grounded Abstracted Experience for Embodied Navigation},
    author = {Zhixuan Shen and Jiawei Du and Ziyu Guo and Han Luo and Lilan Peng and Joey Tianyi Zhou and Haonan Luo and Tianrui Li},
    booktitle = {Proceedings of the International Conference on Machine Learning},
    year = {2026}
  }
---

The project studies how embodied agents can plan in simplified, physics-grounded semantic environments and transfer those abstracted experiences to open-world navigation. It was accepted to ICML 2026 on May 1, 2026.

<img class="publication-detail-wide-image" src="/assets/images/publication/plan-in-sandbox-sage-agent.png" alt="SAGE agent overview">

<p class="publication-figure-caption"><b>SAGE agent overview.</b> The framework uses a physics-grounded sandbox for self-evolving data generation and policy optimization, then transfers learned priors to open-world embodied navigation.</p>

<img class="publication-detail-wide-image" src="/assets/images/publication/plan-in-sandbox-sage-framework.png" alt="SAGE framework">

<p class="publication-figure-caption"><b>SAGE framework.</b> The system operates through Genesis, Evolution, and Navigation phases, connecting sandbox task synthesis, hybrid prompt-augmented policy optimization, and real-world planning and actuation.</p>
