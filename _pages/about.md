---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a senior cybersecurity researcher focused on the cyber capabilities of AI systems. At the US AI Safety Institute (AISI), I leverage my background in cyber capability evaluation to assess current and next-generation AI models, studying the relationship between the capability frontier and potential cyber harms while advancing the science of AI security evaluations.

Previously, I spent a decade at MIT Lincoln Laboratory in the [Cyber System Assessments Group](https://www.ll.mit.edu/r-d/cyber-security-and-information-sciences/cyber-system-assessments) where I led a research team focused on the intersection of dynamic program analysis, firmware security, and vulnerability discovery. In this role, I helped define the field of _firmware rehosting_ while building open-source tools and applying them to analyze critical systems' security. This work in systems security evaluation and testing methodology now informs my approach to understanding AI systems' capabilities and security implications.

I earned my PhD in Computer Science from Northeastern University and BS from Rensselaer Polytechnic Institute, where I was an active member of RPISEC. I'm passionate about cybersecurity education and have developed courses for universities, government agencies, and private companies. The materials from my System Security with Dynamic Program Analysis course are <a href="https://github.com/andrewFasano/dpa" target="_blank">publicly available</a>.

All my publications are available as open access on <a href='https://scholar.google.com/citations?user=Y9XVfSIAAAAJ'>Google Scholar</a>.


# 🔥 News
- *2024.11*: Joined the US AI Safety Institute as a senior advisor focused on cybersecurity
- *2024.08*: Gave a DEF CON talk about reverse engineering LLMs
- *2022.11*: Ran my first international training course in Munich, Germany focused on firmware security
- *2022.01*: Created and taught <emph>CS 4910</emph> &quot;Dynamic Program Analysis for System Security &quot; at Northeastern University
- *2021.05*: Presented our SoK paper <emph>Enabling security analyses of embedded systems via rehosting</emph> at AsiaCCS 2021
- *2017.07*: Led the Lab RATs to a 10th place finish in <a href="https://www.defcon.org/html/links/dc-ctf.html" target="_blank">DEF CON CTF CTF finals</a>. <a href="https://news.mit.edu/2017/mit-team-lincoln-laboratory-scores-big-at-def-con-hacking-competition-0918" target="_blank">News coverage</a>
- *2016.12*: Discovered <a href="https://nation.state.actor">10 CVEs in a McAfee antivirus product</a>. <a href="https://www.theregister.com/2016/12/13/boffin_dishes_10_mcafee_enterprise_bugs_for_chained_rce_root_death/" target="_blank">News coverage</a>

# 🧑‍💻 Open Source Projects
- **Hypervisor Dissociative Execution**: A framework for dynamic analysis of virtualized guest systems based on system call injection. [GitHub Repository](http://github.com/andrewFasano/hyde).
- **Firmware Rehosting**: _Suite of tools for automated firmware rehosting and dynamic analysis of firmware to be released alongside BAR 2025 publication_
- **PANDA.re**: A whole-system dynamic analysis platform for reverse engineering and software understanding. Fork of the QEMU codebase with significant modifications to enable record/replay, a plugin architecture, and Python based analyses. [GitHub Repository](https://github.com/panda-re/panda). [Project Website](https://panda.re)
- **LAVA**: An automated framework for injecting vulnerabilities into software to evaluate bug-finding systems. LAVA uses PANDA's whole-system dynamic taint analysis to identify how input data flow through a program and uses this information to propose and evaluate patches to soruce code to add vulnerabilities. [GitHub Repository](https://github.com/panda-re/lava) (No longer maintained)
- **Rode0day**: A vulnerability discovery competition powered by LAVA where users compete to find new bugs each month. Unlike prior self-evaluations, Rode0day competitors had no knowledge of where the bugs were until we released the solutions after each competition ended. [Project website](https://rode0day.mit.edu) (No longer maintained)

# 📝 Academic Publications 
- _Target-Centric Firmware Rehosting with Penguin_. **Andrew Fasano**, Zachary Estrada, Luke Craig, Ben Levy, Jordan McLeod, Jacques Becker, Elysia Witham, Cole DiLorenzo, Caden Kline, Ali Bobi, Dinko Dermendzhiev, Tim Leek, and William Robertson. **NDSS BAR 2025** (Preprint coming soon).

- _Hypervisor Dissociative Execution: Programming Guests for Monitoring, Management, and Security_. **Andrew Fasano**, Zak Estrada, Timothy Leek, William Robertson. **ACSAC 2024**. [View pdf](https://andrewfasano.com/assets/files/hyde.pdf)

- [Homo in Machina: Improving Fuzz Testing Coverage via Compartment Analysis](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=Y9XVfSIAAAAJ&citation_for_view=Y9XVfSIAAAAJ:YsMSGLbcyi4C). Josh Bundt, **Andrew Fasano**, Brendan Dolan-Gavitt, William Robertson, Timothy Leek. **ACM AsiaCCS 2021**. [View pdf](https://arxiv.org/pdf/2212.11162.pdf)

- [PyPANDA: Taming the PANDAmonium of Whole System Dynamic Analysis](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=Y9XVfSIAAAAJ&citation_for_view=Y9XVfSIAAAAJ:zYLM7Y9cAGgC). Luke Craig, **Andrew Fasano**,  Tiemoko Ballo, Timothy Leek, Brendan Dolan-Gavitt, William Robertson. **NDSS BAR 2021**. [View pdf](https://www.ndss-symposium.org/wp-content/uploads/bar2021_23001_paper.pdf)

- [Evaluating Synthetic bugs](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=Y9XVfSIAAAAJ&citation_for_view=Y9XVfSIAAAAJ:Tyk-4Ss8FVUC). Josh Bundt, **Andrew Fasano**, Brendan Dolan-Gavitt, William Robertson, Timothy Leek. **ACM AsiaCCS 2021**. [View pdf](https://dl.acm.org/doi/pdf/10.1145/3433210.3453096)

- [SoK: Enabling Security Analyses of Embedded Systems via Rehosting](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=Y9XVfSIAAAAJ&citation_for_view=Y9XVfSIAAAAJ:IjCSPb-OGe4C).
**Andrew Fasano**, Tiemoko Ballo, Marius Muench, Tim Leek, Alexander Bulekov, Brendan Dolan-Gavitt, Manuel Egele, Aurelien Francillon, Long Lu, Nick Gregory, Davide Balzarotti, William Robertson. **ACM AsisaCCS 2021**. [View pdf](https://dspace.mit.edu/handle/1721.1/130505)

- [The Rode0day to Less Buggy Programs](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=Y9XVfSIAAAAJ&citation_for_view=Y9XVfSIAAAAJ:2osOgNQ5qMEC). **Andrew Fasano**, Tim Leek, Brendan Dolan-Gavitt, Josh Bundt. **IEEE Security and Privacy Magazine 2019**. [View pdf](https://messlab.moyix.net/papers/rode0day_spmag19.pdf)

# 💬 Invited Talks
- *2024.08*, **DEFCON AIxCC**: "A Reverse Engineer’s Guide to Mechanistic Interpretability" [Video](https://vimeo.com/997479806) and [slides](https://nation.state.actor/2024/08/21/defcon.html).
- *2023.10*, **New York University**: "The Trials, Tribulations, and Triumphs of Whole System Dynamic Analysis: Lessons from a Decade in the Trenches"
- *2019.10*, **AvengerCon**: "The LAVA has Hardened! Building a Better Bug Corpora to Evaluate Bug-Finders"
- *2019.08*, **USENIX WOOT**: "Rode0day: A Year of Bug-Finding Evaluations"
- *2018.08*, **USENIX WOOT**: "Rode0day: Searching for Truth with a Bug-Finding Competition"
- *2018.10*, **MIT Techsec**: "Intro to Web Exploitation"

# 🎖 Honors and Awards
- *2020.09* **R&D100 Award**: LAVA was [awarded an R&D100 award](https://www.rdworldonline.com/rd-100-2020-winner/lava-large-scale-vulnerability-addition/) for its impact advancing the state of the art in vulnerability discovery.
- *2019.09* **MIT Lincoln Scholar Award**: Selected to receive special funding through a competitive process to pursue my research.
- *2017.06* **MIT Lincoln Laboratory Team Award**: Award for outstanding technical achievement.
