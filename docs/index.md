---
layout: default
# `image` powers og:image / twitter:image — jekyll-seo-tag reads it from the
# page, not from _config.yml.
image: /img/photo.jpg
---

<style>
details.tldr {
  margin: 0 0 1.6em 0;
}
/* close the gap between a publication's author line and its TL;DR */
p:has(+ details.tldr) {
  margin-bottom: 0.2em;
}
details.tldr > summary {
  cursor: pointer;
  list-style: none;
  font-style: italic;
  color: #444;
}
details.tldr > summary::-webkit-details-marker { display: none; }
details.tldr > summary::before {
  content: "▸ ";
  color: #999;
  font-style: normal;
}
details.tldr[open] > summary::before { content: "▾ "; }
details.tldr > summary:hover { color: #000; }
details.tldr > p {
  margin: 0.5em 0 0 1.1em;
  font-style: italic;
  color: #555;
}
</style>

## About Me

👋 Hi! I am Zixuan (Eve) Yi, a third-year PhD student in CS at the University of Pennsylvania, advised by [Ryan Marcus](https://rmarcus.info/blog/) and [Zack Ives](https://www.cis.upenn.edu/~zives/). Before this, I earned my bachelor degree in CS from Tsinghua University.

I’m always happy to chat about research, collaborations, or interesting problems in ML and systems. Feel free to [reach out](mailto:zixy@upenn.edu)! 😄

## News
- ☕️ **VLDB'26 (Aug 31 - Sep 4):** I’ll be in **Boston** for VLDB'26. DM me if you want to grab coffee and chat!
- 🧋 **COLM'26 (October 6 - 9):** I’ll be in **SF** for COLM'26. Looking forward to meeting researchers working on LLM agents, agentic systems, and related areas!
- 🎉 **Data Canvas** was accepted to **COLM'26**! 
- 🔦 **Theory-Level Autoformalization** was selected as a **Spotlight** at the **ICML'26 Position Track**.


## Research Interests

I work at the intersection of **machine learning and systems**: using ML to make systems more intelligent, and systems techniques to make AI applications **efficient and reliable in real-world environments**.

Three questions run through my work:
- **Learning & Adaptation:** How can systems learn from their own execution history and adapt to new workloads and feedback? *(LimeQO, LLMSteer)*
- **Efficiency:** How can learning and decision-making stay cheap when every trial costs a real execution? *(LimeQO)*
- **Reliability & Control:** How can we tell where an intelligent system went wrong, and repair just that part? *(Data Canvas)*


## Publications

**Data Canvas: A Provenance-Guided Harness for Agentic Data Engineering** \
**COLM'26** \
**Zixuan Yi**, Yuanming Shao, Shaun Wallace, Zachary Ives, Ryan Marcus \
*Code and paper coming soon!*

<details class="tldr" markdown="1">
<summary>When an agent goes wrong, can we identify the responsible step and repair only what it affected?</summary>

*Agent workflows are difficult to inspect and repair when their outputs come from long, opaque execution traces. Data Canvas structures agent execution into semantic operators and tracks fine-grained provenance, allowing feedback to be traced to the responsible computation, propagated to related outputs, and repaired by replaying only the affected parts of the workflow.*

</details>


**Theory-Level Autoformalization: From Isolated Statements to Unified Formal Knowledge Bases** \
**ICML'26 Position Track (🔦Spotlight)** \
Marcus J Min, Mike He, Zhaoyu Li, **Zixuan Yi**, Sharad Malik, Aarti Gupta, Xujie Si, Osbert Bastani 
[[code]](https://github.com/marcusm117/Awesome-Autoformalization) [[paper]](https://arxiv.org/pdf/2607.13292)

<details class="tldr" markdown="1">
<summary>Should autoformalization build whole theories instead of translating isolated statements?</summary>

*Most autoformalization (turning informal math into machine-checkable formal math) assumes that the surrounding definitions, notation, lemmas, and dependencies already exist. We argue for **theory-level autoformalization**: constructing coherent formal libraries and their dependency structure, rather than treating each statement as an independent translation problem.*

</details>


**LimeQO: Low-Rank Learning for Offline Query Optimization.** \
**SIGMOD'25** \
**Zixuan Yi**, Yao Tian, Zachary G. Ives, Ryan Marcus [[code]](https://github.com/zixy17/LimeQO)[[paper]](https://zixy17.github.io/pdf/limeqo_sigmod25.pdf)[[poster]](https://zixy17.github.io/pdf/limeqo-poster.pdf) 

<details class="tldr" markdown="1">
<summary>Can we learn good decisions across an entire workload without exhaustively evaluating every possibility?</summary>

*Learning good optimization decisions can require many expensive system executions. **LimeQO treats an entire workload as a partially observed low-rank matrix**, allowing information from a small number of executions to generalize across queries and guide where exploration is most useful, dramatically reducing learning overhead while avoiding regressions. **Try it out at [LimeQO](https://github.com/zixy17/LimeQO/blob/main/limeqo.ipynb)**.*

</details>


**The Unreasonable Effectiveness of LLMs for Query Optimization.** \
**ML4Systems@NeurIPS'24 (🔦Spotlight)** \
Peter Akioyamen, **Zixuan Yi**, Ryan Marcus [[code]](https://github.com/peter-ai/LLMSteer)[[paper]](https://arxiv.org/pdf/2411.02862)[[talk]](https://neurips.cc/virtual/2024/103605) 

<details class="tldr" markdown="1">
<summary>How much does a pretrained language model already know about the behavior of a SQL query?</summary>

*Learned query optimizers often rely on specialized representations and database-specific features. **LLMSteer** shows that pretrained embeddings of raw SQL already contain useful signals for optimization: a lightweight classifier over these representations can steer an existing optimizer without complex model architectures or deep integration with database internals.*


</details>

## Experiences

**Microsoft** Research Intern @ [MSR](https://www.microsoft.com/en-us/research/group/datasystems/), 2026 Summer \
*Worked on efficient decision-making under expensive execution feedback, including cost-aware validation and adaptive evaluation strategies.*

**Google** Student Researcher @ [SRG](https://techsysinfra.google/research/srg/), 2024 Summer \
*Worked on lightweight online learning from historical execution behavior for efficient adaptation on real-world workloads.*

**Google** STEP Intern @ Google Search, 2021 Summer\
*Built a human-in-the-loop analytics and evaluation pipeline combining expert feedback with NLP models.*