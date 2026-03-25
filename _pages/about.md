---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div style="font-family: 'Times New Roman', Times, serif;">

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a Lecturer at China University of Petroleum (East China), working on AI storage systems and LLM/AI systems at a national demonstrative software school (team lead: Shancheng Pang). I received my B.Eng. from China University of Petroleum (East China) in 2019 and my Ph.D. in Computer Science from Beihang University in 2025 (advisor: Limin Xiao). My research lies at the intersection of storage systems and AI systems, focusing on storage/memory hierarchy optimization, cross-domain data management, distributed systems, and compute-storage co-scheduling for emerging computing paradigms.

In recent years, I have published papers in top-tier venues such as ICDE, AAAI, ISCA, IEEE TC, and IEEE TCAD, with research spanning distributed consensus, offline multi-task reinforcement learning, storage systems, cloud computing, and AI system optimization.

# 🔥 News
- *2026*: One paper on distributed consensus was accepted by **ICDE 2026**.
- *2026*: One paper on offline multi-task reinforcement learning was accepted by **AAAI 2026**.
- *2025*: One paper on metadata replica consistency was published in *Frontiers of Computer Science*.
- *2024*: One paper on periodically replicated systems was published in *Frontiers of Computer Science*.

# 📝 Publications

## Conference Papers
- [R1] **Chenhao Zhang**, Jinquan Wang, Meng Han, Bing Wei, Xiaojian Liao*, et al. **RL-Paxos: Relieving the Leader's Burden with Efficient Task Offloading in Distributed Consensus**. *2026 IEEE 41st International Conference on Data Engineering (ICDE)*, Canada, 2026. <span style="color:#1f77b4;"><strong>CCF-A Conference</strong></span>

- [R2] Shudong Wang†, Xinfei Wang†, **Chenhao Zhang**\*†, et al. **Soft Conflict-Resolution Decision Transformer for Offline Multi-Task Reinforcement Learning**. *Proceedings of the AAAI Conference on Artificial Intelligence (AAAI)*, 2026. <span style="color:#1f77b4;"><strong>CCF-A Conference</strong></span>  
  (*co-first author, sole corresponding author*)

- [R3] Meng Han, Liang Wang, Limin Xiao, Hao Zhang, Tianhao Cai, and **Chenhao Zhang**. **BitNN: A Bit-Serial Accelerator for K-Nearest Neighbor Search in Point Clouds**. In *2024 ACM/IEEE 51st Annual International Symposium on Computer Architecture (ISCA)*, 2024: 1278–1292. <span style="color:#1f77b4;"><strong>CCF-A Conference</strong></span>

## Journal Papers
- [R4] **Chenhao Zhang**, Limin Xiao*, Liang Wang*, et al. **Minimizing the Cost of Periodically Replicated Systems via Model and Quantitative Analysis**. *Frontiers of Computer Science*, 2024. <span style="color:#1f77b4;"><strong>CCF-B Journal, Q1</strong></span>

- [R5] **Chenhao Zhang**, Limin Xiao*, Liang Wang*, et al. **Low-Cost and Efficient Consistency with Adaptive Synchronization for Metadata Replica**. *Frontiers of Computer Science*, 2025. <span style="color:#1f77b4;"><strong>CCF-B Journal, Q1</strong></span>

- [R6] Shanchen Pang, Miaomiao Fan, Xiao He, Wenhao Ji, Sibo Qiao, **Chenhao Zhang**\*. **Multi-agent DRL-based Task Offloading and Trajectory Optimization for Low Altitude UAV IoT Systems**. *Ad Hoc Networks*, 2026: 104164. <span style="color:#1f77b4;"><strong>CCF-C Journal, Q1</strong></span>  
  (*sole corresponding author*)

- [R7] **张晨浩**，肖利民，秦广军，宋尧，蒋世轩. **面向大数据处理应用的广域存算协同调度系统**. *大数据*, 2021. <span style="color:#1f77b4;"><strong>CCF T2 Journal</strong></span>

- [R8] Meng Han, Limin Xiao*, Liang Wang*, **Chenhao Zhang**. **QuickFPS: Architecture and Algorithm Co-Design for Farthest Point Sampling in Large-Scale Point Clouds**. *IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (IEEE TCAD)*. <span style="color:#1f77b4;"><strong>CCF-A Journal</strong></span>

- [R9] Meng Han, Liang Wang, Limin Xiao, Tianhao Cai, Zeyu Wang, Xiangrong Xu, and **Chenhao Zhang**. **ReDas: A Lightweight Architecture for Supporting Fine-Grained Reshaping and Multiple Dataflows on Systolic Array**. *IEEE Transactions on Computers (IEEE TC)*. <span style="color:#1f77b4;"><strong>CCF-A Journal</strong></span>

- [R10] Bing Wei, Limin Xiao*, Hanjie Zhou, Guangjun Qin*, Yao Song, and **Chenhao Zhang**. **Global Virtual Data Space for Unified Data Access across Supercomputing Centers**. *IEEE Transactions on Cloud Computing*, 2022, 11(2): 1822–1839. <span style="color:#1f77b4;"><strong>CCF-B Journal</strong></span>

# 🎖 Selected Research Highlights
- Research on **distributed consensus optimization**, represented by *RL-Paxos*, exploring intelligent task offloading for relieving the leader bottleneck in Paxos-like protocols.
- Research on **offline multi-task reinforcement learning**, represented by *Soft Conflict-Resolution Decision Transformer*, focusing on conflict mitigation and generalization across heterogeneous tasks.
- Research on **storage and data systems**, including metadata consistency, periodically replicated systems, and wide-area virtual data space for unified data access across supercomputing centers.
- Research on **AI systems and architecture optimization**, including point cloud processing acceleration and systolic-array-oriented architecture design.

# 📖 Education
- *2019.09 - 2025.06*, Ph.D. in Computer Science, **Beihang University**, China
- *2015.09 - 2019.06*, B.Eng., **China University of Petroleum (East China)**, China

# 💬 Research Interests
- AI Storage Systems
- LLM/AI Systems
- Distributed Systems and Consensus
- Storage/Memory Hierarchy Optimization
- Cross-domain Data Management
- Compute-Storage Co-Scheduling
- Offline Multi-Task Reinforcement Learning

</div>