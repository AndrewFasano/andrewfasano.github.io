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
I am a member of the Technical Staff at MIT Lincoln Laboratory in the [Cyber System Assessments Group](https://www.ll.mit.edu/r-d/cyber-security-and-information-sciences/cyber-system-assessments) where I research the intersection of dynamic program analysis, firmware security, and vulnerability discovery. In particular, I am interested in **rehosting** firmware into virtual environments where it will run correctly while also being closely analyzed and monitored. Towards this end, I have contributed to the development of a number of open source tools. I've also developed courses focused on dynamic program analysis, whole system dynamic analysis, and firmware security which I've taught at various universities and companies both in the US and abroad. I am a proud alumnus of Northeastern University, where I earned my PhD in Computer Science, and Rensselaer Polytechnic Institute, where I earned a BS in Computer Science and was an active member of RPISEC.

All my publications are available as open access, at <a href='https://scholar.google.com/citations?user=Y9XVfSIAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. Training materials can be shared upon request, and I am always happy to discuss my research and teaching.

# 🔥 News
- *2022.11*: Ran my first international training course in Munich, Germany!
- *2022.01*: Created and taught <emph>CS 4910</emph> &quot;Dynamic Program Analysis for System Security &quot; at Northeastern University
- *2021.06*: Presented our paper <emph>PyPANDA: taming the PANDAmonium of whole system dynamic analysis</emph> at NDSS BAR 2021
- *2021.05*: Presented our SoK paper <emph>Enabling security analyses of embedded systems via rehosting</emph> at AsiaCCS 2021
- *2017.07*: Led the Lab RATs to a 10th place finish in <a href="https://www.defcon.org/html/links/dc-ctf.html" target="_blank">DEF CON CTF CTF finals</a>. <a href="https://news.mit.edu/2017/mit-team-lincoln-laboratory-scores-big-at-def-con-hacking-competition-0918" target="_blank">News coverage</a>
- *2016.12*: Discovered 10 CVEs in a McAfee product. <a href="https://nation.state.actor">Technical write-up</a> and <a href="https://www.theregister.com/2016/12/13/boffin_dishes_10_mcafee_enterprise_bugs_for_chained_rce_root_death/" target="_blank">news coverage</a>

# 🧑‍💻 Open Source Projects
- **PANDA.re**: A whole-system dynamic analysis platform for reverse engineering and software understanding. (GitHub Repository)[https://github.com/panda-re/panda] | (Project Website)[https://panda.re]
- **LAVA**: An automated framework for injecting vulnerabilities into software to evaluate bug-finding systems. (GitHub Repository)[https://github.com/panda-re/lava] (No longer maintained)
- **Rode0day**: A vulnerability discovery competition powered by LAVA where users compete to find new bugs each month. (Project website)[https://rode0day.mit.edu] (No longer maintained)
- **Firmware Rehosting**: _New tools for automated firmware rehosting to be released late 2024_

# 📝 Academic Publications 

- [Homo in Machina: Improving Fuzz Testing Coverage via Compartment Analysis](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=Y9XVfSIAAAAJ&citation_for_view=Y9XVfSIAAAAJ:YsMSGLbcyi4C) Josh Bundt, **Andrew Fasano**, Brendan Dolan-Gavitt, William Robertson, Timothy Leek. **ACM AsiaCCS 2021**. [View pdf](https://arxiv.org/pdf/2212.11162.pdf)

- [PyPANDA: Taming the PANDAmonium of Whole System Dynamic Analysis](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=Y9XVfSIAAAAJ&citation_for_view=Y9XVfSIAAAAJ:zYLM7Y9cAGgC) Luke Craig, **Andrew Fasano**,  Tiemoko Ballo, Timothy Leek, Brendan Dolan-Gavitt, William Robertson. **NDSS BAR 2021**. [View pdf](https://www.ndss-symposium.org/wp-content/uploads/bar2021_23001_paper.pdf) 

- [Evaluating Synthetic bugs](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=Y9XVfSIAAAAJ&citation_for_view=Y9XVfSIAAAAJ:Tyk-4Ss8FVUC) Josh Bundt, **Andrew Fasano**, Brendan Dolan-Gavitt, William Robertson, Timothy Leek. **ACM AsiaCCS 2021**. [View pdf](https://dl.acm.org/doi/pdf/10.1145/3433210.3453096)

- [SoK: Enabling Security Analyses of Embedded Systems via Rehosting](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=Y9XVfSIAAAAJ&citation_for_view=Y9XVfSIAAAAJ:IjCSPb-OGe4C)
**Andrew Fasano**, Tiemoko Ballo, Marius Muench, Tim Leek, Alexander Bulekov, Brendan Dolan-Gavitt, Manuel Egele, Aurelien Francillon, Long Lu, Nick Gregory, Davide Balzarotti, William Robertson. **ACM AsisaCCS 2021**. [View pdf](https://dspace.mit.edu/handle/1721.1/130505)

- [The Rode0day to Less Buggy Programs](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=Y9XVfSIAAAAJ&citation_for_view=Y9XVfSIAAAAJ:2osOgNQ5qMEC) **Andrew Fasano**, Tim Leek, Brendan Dolan-Gavitt, Josh Bundt. **IEEE Security and Privacy Magazine 2019**. [View pdf](https://messlab.moyix.net/papers/rode0day_spmag19.pdf)

# 💬 Invited Talks
- *2019.10*, **AvengerCon**: "The LAVA has Hardened! Building a Better Bug Corpora to Evaluate Bug-Finders"
- *2019.08*, **USENIX WOOT** "Rode0day: A Year of Bug-Finding Evaluations"
- *2018.08*, **USENIX WOOT** "Rode0day: Searching for Truth with a Bug-Finding Competition"
- *2018.10*, **MIT Techsec** "Intro to Web Security"

# 🎖 Honors and Awards
- *2020.09* **R&D100 Award**: LAVA was [awarded an R&D100 award](https://www.rdworldonline.com/rd-100-2020-winner/lava-large-scale-vulnerability-addition/) for its impact advancing the state of the art in vulnerability discovery.
- *2019.09* **MIT Lincoln Scholar Award**: Selected to receive special funding through a competitive process to pursue my research on firmware rehosting.
- *2017.06* **MIT Lincoln Laboratory Team Award**: One of my projects was award a Team Award for outstanding technical achievement.
