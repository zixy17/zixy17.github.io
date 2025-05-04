## About Me

Hi, I am Zixuan (Eve) Yi. I am a second-year CS PhD student at University of Pennsylvania, advised by [Ryan Marcus](https://rmarcus.info/blog/) and [Zack Ives](https://www.cis.upenn.edu/~zives/). Before this, I earned my bachelor degree in CS from Tsinghua University.

You can find me at Twitter [@yi_zixuan](https://twitter.com/yi_zixuan),  [linkedin](https://www.linkedin.com/in/zixuan-yi-073ab01b0/) or email me [zixy@seas.upenn.edu](mailto:zixy@seas.upenn.edu). 

## News

🇩🇪 I will be attending the SIGMOD'25 Conference at Berlin, Germany.

## Research Interests

I am broadly interested in Machine Learning and Systems.

## Publications

**LimeQO: Low-Rank Learning for Offline Query Optimization.** \
**SIGMOD'25** \
**Zixuan Yi**, Yao Tian, Zachary G. Ives, Ryan Marcus [[code]](https://github.com/zixy17/LimeQO)[[paper]](https://zixy17.github.io/pdf/limeqo_sigmod25.pdf)[[poster]](https://zixy17.github.io/pdf/NEDB2024.pdf) 

<em>Regressions and large overhead time are the major concerns when machine learning based query optimizers are put into production system. We proposed the first "workload-level" query optimizer that optimize the whole workload all at once without any regressions. Leveraging the similarities between queries, we cast the problem as low-rank matrix completion - using this pure linear method gives us 100x overhead time gain! **Try it out at [LimeQO](https://github.com/zixy17/LimeQO/blob/main/limeqo.ipynb)**.</em>

**The Unreasonable Effectiveness of LLMs for Query Optimization.** \
**MLForSystems'24** \
Peter Akioyamen, **Zixuan Yi**, Ryan Marcus [[code]](https://github.com/peter-ai/LLMSteer)[[paper]](https://arxiv.org/pdf/2411.02862)[[talk]](https://neurips.cc/virtual/2024/103605) 

<em>We present LLMSteer, a novel approach that leverages LLMs to enhance SQL query optimization. By embedding raw SQL queries using LLMs and training a simple binary classifier on a small labeled dataset, the method predicts optimal query plan hints. Remarkably, this approach outperforms traditional heuristic-based systems and complex machine learning models that require deep integration with database internals.</em>
