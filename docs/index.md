# Zixuan (Eve) Yi
**PhD Student @ UPenn · Machine Learning × Data × Systems**

[Google Scholar](https://scholar.google.com/citations?user=yN_59vUAAAAJ&hl=en) · [GitHub](https://github.com/zixy17) · [Twitter](https://twitter.com/yi_zixuan) · [LinkedIn](https://www.linkedin.com/in/zixuan-yi-073ab01b0/) · [Email](mailto:zixy@seas.upenn.edu)

## About Me

👋 Hi! I am Zixuan (Eve) Yi, a third-year PhD student in CS at the University of Pennsylvania, advised by [Ryan Marcus](https://rmarcus.info/blog/) and [Zack Ives](https://www.cis.upenn.edu/~zives/). Before this, I earned my bachelor degree in CS from Tsinghua University.

I work at the intersection of **machine learning and systems**, with a growing focus on building **efficient and reliable AI systems**.

I’m always happy to chat about research, collaborations, or interesting problems in ML and systems. Feel free to reach out! 😄

## News

☕️ **VLDB'26 (Aug 31 - Sep 4):** I’ll be in **Boston** for VLDB'26. If you’re attending too, feel free to reach out — I’d love to grab coffee and chat!

🧋 **COLM'26 (October 6 - 9):** I’ll be in **SF** for COLM'26. Looking forward to meeting researchers working on LLM agents, agentic systems, and related areas!

🎉 **Data Canvas** was accepted to **COLM'26**! 

🔦 **Theory-Level Autoformalization** was selected as a **Spotlight** at the **ICML'26 Position Track**.


## Research Interests

I am broadly interested in building intelligent systems that are **efficient, adaptive, and reliable in real-world environments**. My previous works explored how **machine learning can make systems more intelligent**, and how **systems techniques can make AI applications more efficient and reliable**. 

In particular, I’m interested in three broad questions:
- **Learning & Adaptation:** How can intelligent systems learn from experience and adapt to new tasks, environments, and feedback?
- **Efficiency:** How can we make learning and decision-making efficient when computation, interaction, or evaluation is expensive?
- **Reliability & Control:** How can we make intelligent systems easier to understand, steer, and correct when they make mistakes?


## Publications

**Data Canvas: A Provenance-Guided Harness for Agentic Data Engineering** \
**COLM'26** \
**Zixuan Yi**, Yuanming Shao, Shaun Wallace, Zachary Ives, Ryan Marcus \
*Code and paper comming soon!*

*LLM agents can execute increasingly complex workflows, but their failures are often difficult to inspect or correct. **Data Canvas** wraps agent execution in structured semantic operators and tracks fine-grained provenance across actions and outputs. This lets sparse feedback be traced back to responsible reasoning steps and enables targeted repair instead of rerunning the entire agent workflow.*


**LimeQO: Low-Rank Learning for Offline Query Optimization.** \
**SIGMOD'25** \
**Zixuan Yi**, Yao Tian, Zachary G. Ives, Ryan Marcus [[code]](https://github.com/zixy17/LimeQO)[[paper]](https://zixy17.github.io/pdf/limeqo_sigmod25.pdf)[[poster]](https://zixy17.github.io/pdf/limeqo-poster.pdf) 

*Learning good optimization decisions can require many expensive system executions. **LimeQO treats an entire workload as a partially observed low-rank matrix**, allowing information from a small number of executions to generalize across queries and guide where exploration is most useful, dramatically reducing learning overhead while avoiding regressions. **Try it out at [LimeQO](https://github.com/zixy17/LimeQO/blob/main/limeqo.ipynb)**.*

**Theory-Level Autoformalization: From Isolated Statements to Unified Formal Knowledge Bases** \
**ICML'26 Position Track (🔦Spotlight)** \
Marcus J Min, Mike He, Zhaoyu Li, **Zixuan Yi**, Sharad Malik, Aarti Gupta, Xujie Si, Osbert Bastani 
[[code]](https://github.com/marcusm117/Awesome-Autoformalization) [[paper]](https://arxiv.org/pdf/2607.13292)

*Most autoformalization (turning informal math into machine-checkable formal math) research focuses on translating isolated statements, even though real formalization requires constructing the definitions, notation, lemmas, and dependencies around them. We argue for moving toward **theory-level autoformalization**: automatically building coherent formal libraries rather than solving individual translation problems in isolation.*


**The Unreasonable Effectiveness of LLMs for Query Optimization.** \
**ML4Systems@NeurIPS'24 (🔦Spotlight)** \
Peter Akioyamen, **Zixuan Yi**, Ryan Marcus [[code]](https://github.com/peter-ai/LLMSteer)[[paper]](https://arxiv.org/pdf/2411.02862)[[talk]](https://neurips.cc/virtual/2024/103605) 

*We explore a surprisingly simple way to use pretrained language-model representations for system decision making. **LLMSteer** embeds raw SQL queries using an LLM and trains a lightweight classifier to select optimization decisions, outperforming substantially more specialized approaches without requiring deep integration with database internals.*

## Experiences

**Microsoft** Research Intern @ [MSR](https://www.microsoft.com/en-us/research/group/datasystems/), 2026 Summer \
*Worked on efficient decision-making under expensive execution feedback, including cost-aware validation and adaptive evaluation strategies.*

**Google** Student Researcher @ [SRG](https://techsysinfra.google/research/srg/), 2024 Summer \
*Worked on lightweight online learning from historical execution behavior for efficient adaptation on real-world workloads.*

**Google** STEP Intern @ Google Search, 2021 Summer\
*Built a human-in-the-loop analytics and evaluation pipeline combining expert feedback with NLP models.*