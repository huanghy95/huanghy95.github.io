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

📚 Haiyu Huang is currently a second-year CSE Ph.D. student at [The Chinese University of Hong Kong](https://www.cse.cuhk.edu.hk/), advised by [Prof. Michael R. Lyu](https://www.cse.cuhk.edu.hk/lyu/). Previously, he worked as a research assistant at Sun Yat-sen University under the guidance of [Prof. Pengfei Chen](https://cse.sysu.edu.cn/content/3747). He received a B.E. in CSE from Sun Yat-Sen University in 2023. He has interned at [Alibaba Cloud](https://cn.aliyun.com/), [Huawei](https://www.huawei.com/), [Ant Group](https://www.antgroup.com/), and [ByteDance](https://www.bytedance.com/) in Cloud Native Application Performance Management related departments, developing algorithms and solving real-world problems.

💡 His research interest lies in microservices reliabilty (e.g., developing observability tools for cloud systems.), AI for DevOps (e.g., automating software debugging and troubleshooting during development or operations, especially using LLMs) and MLOps (e.g., automating AI system operations).


# 🔥 News
- *2026.08*: &nbsp;🎉🎉 Our paper "From General Agents to RCA Experts: A Self-Evolving Harness for Root Cause Analysis" is now available on [arXiv](https://arxiv.org/abs/2608.25661).
- *2026.08*: &nbsp;🎉🎉 Our paper "StaR: Stateful Dynamic-Graph Root Cause Analysis through Memory-Enhanced Causality Discovery" was published at [KDD'26](https://doi.org/10.1145/3770855.3817863).
- *2026.08*: &nbsp;🎉🎉 Our paper "SLOPE: Fine-Grained Log Parser Combining Syntax with LLM-Distilled Semantic" was published in [TOSEM](https://doi.org/10.1145/3838599).
- *2026.07*: &nbsp;🎉🎉 Our paper "Reliable Orchestration of Specialized Multi-Agents for Cloud Incident Diagnosis" was published at [ICWS'26](https://ieeexplore.ieee.org/abstract/document/11670046/) (REMS Workshop).
- *2026.06*: &nbsp;🎉🎉 Our paper "OpsLens: Runbook-Free Root Cause Analysis via Multi-agent Collaboration and Tool Management" was accepted by [ASE'26](https://conf.researchr.org/track/ase-2026/ase-2026-industry-showcase).
- *2026.04*: &nbsp;🎉🎉 Our paper "InferLog: Accelerating LLM Inference for Online Log Parsing via ICL-oriented Prefix Caching" was published at [ICSE'26](https://doi.org/10.1145/3744916.3764523).
- *2026.04*: &nbsp;🎉🎉 Our paper "LLMRCA: Multilevel Root Cause Analysis for LLM Applications Using Multimodal Observability Data" was published in [TOSEM](https://doi.org/10.1145/3806200).
- *2026.02*: &nbsp;🎉🎉 Our paper "Cloud-OpsBench: A Reproducible Benchmark for Agentic Root Cause Analysis in Cloud Systems" is now available on [arXiv](https://arxiv.org/abs/2603.00468).
- *2025.11*: &nbsp;🎉🎉 Our paper "LogPilot: Intent-aware and Scalable Alert Diagnosis for Large-scale Online Service Systems" was published at [ASE'25](https://ieeexplore.ieee.org/abstract/document/11334679/).
- *2025.05*: &nbsp;🎉🎉 Our paper "LLMConf: Knowledge-Enhanced Configuration Optimization for Large Language Model Inference" was accepted by IWQOS'25 Research Track.
- *2025.04*: &nbsp;🎉🎉 I’m honored to receive the Hong Kong PhD Fellowship (HKPFS) offer.
- *2025.02*: &nbsp;🎉🎉 I’m honored to receive the CUHK Vice-Chancellor's Scholarship offer.
- *2024.12*: &nbsp;🎉🎉 Our paper "Conan: Uncover Consensus Issues in Distributed Databases Using Fuzzing-driven Fault Injection" was accepted by SANER'25 Research Track.
- *2024.10*: &nbsp;🎉🎉 Our paper "Mint: Cost-Efficient Tracing with All Requests Collection via Commonality and Variability Analysis" was accepted by ASPLOS'25 Research Track.
- *2024.08*: &nbsp;🎉🎉 Our paper "FaaSConf: QoS-aware Hybrid Resources Configuration for Serverless Workflows" was accepted by ASE'24 Research Track.
- *2024.07*: &nbsp;🎉🎉 Our paper "FaaSRCA: Full Lifecycle Root Cause Analysis for Serverless Applications" was accepted by ISSRE'24 Research Track.
- *2024.06*: &nbsp;🎉🎉 Our paper "TraStrainer: Adaptive Sampling for Distributed Traces with System Runtime State" has won an **<font color="red">ACM SIGSOFT Distinguished Paper award</font> 🏆**.
- *2024.01*: &nbsp;🎉🎉 Our paper "TraStrainer: Adaptive Sampling for Distributed Traces with System Runtime State" was accepted by FSE'24 Research Track.
- *2023.12*: &nbsp;🎉🎉 Our LLM-based AIOps solutions won [3rd place🥉](https://mp.weixin.qq.com/s/KctBL78OgxSOzPXoeGfe5w) in the [2023 CCF International AIOps Challenge](https://competition.aiops-challenge.com/home/competition/1669253443434315819) \(ranking 1st🏅 among student teams\).

# 📝 Publications 

- &nbsp; <span class="badge">Arxiv</span> &nbsp;**From General Agents to RCA Experts: A Self-Evolving Harness for Root Cause Analysis**

  <span style="font-size:14px;"> **Haiyu Huang**, Jiewei Lyu, Zhihan Jiang, Jinyang Liu, Xiao He, Tieying Zhang, Wu Xiang and Michael R. Lyu. </span>

  [[Paper](https://arxiv.org/abs/2608.25661)]
  [Code]
  [Slides]
  [[DOI](https://doi.org/10.48550/arXiv.2608.25661)]

- &nbsp; <span class="badge">KDD '26</span> &nbsp;**StaR: Stateful Dynamic-Graph Root Cause Analysis through Memory-Enhanced Causality Discovery**

  <span style="font-size:14px;"> **Haiyu Huang**, Man Tik Ng, Jiewei Lyu, Yujie Huang, Guangba Yu, Yilun Wang and Michael R. Lyu. </span>

  <span style="font-size:14px;"> *The 32nd ACM SIGKDD Conference on Knowledge Discovery and Data Mining, Jeju Island, Republic of Korea, August 2026.* </span>

  [[Paper](https://dl.acm.org/doi/pdf/10.1145/3770855.3817863)]
  [[Code](https://github.com/huanghy95/StaR)]
  [Slides]
  [[DOI](https://doi.org/10.1145/3770855.3817863)]

- &nbsp; <span class="badge">TOSEM '26</span> &nbsp;**SLOPE: Fine-Grained Log Parser Combining Syntax with LLM-Distilled Semantic**

  <span style="font-size:14px;"> Shuting Lai, **Haiyu Huang**, Pengfei Chen, Zilong He, Min Li and Tong Shen. </span>

  <span style="font-size:14px;"> *ACM Transactions on Software Engineering and Methodology, 2026.* </span>

  [[Paper](https://dl.acm.org/doi/pdf/10.1145/3838599)]
  [Code]
  [Slides]
  [[DOI](https://doi.org/10.1145/3838599)]

- &nbsp; <span class="badge">ICWS '26</span> &nbsp;**Reliable Orchestration of Specialized Multi-Agents for Cloud Incident Diagnosis**

  <span style="font-size:14px;"> **Haiyu Huang**, Jiewei Lyu, Shuting Lai, Zhihan Jiang, Pengfei Chen and Michael R. Lyu. </span>

  <span style="font-size:14px;"> *The 2nd International Workshop on Reliable and Efficient Multi-agent Services, in conjunction with IEEE ICWS 2026, Sydney, Australia, July 2026.* </span>

  [[Paper](https://ieeexplore.ieee.org/abstract/document/11670046/)]
  [Code]
  [Slides]
  [DOI]

- &nbsp; <span class="badge">ASE '26</span> &nbsp;**OpsLens: Runbook-Free Root Cause Analysis via Multi-agent Collaboration and Tool Management**

  <span style="font-size:14px;"> **Haiyu Huang**, Jiewei Lyu, Gou Tan, Pengfei Chen, Zhihan Jiang, Guangba Yu, Penghui Mi, Fuqiang Wang, Jian Han, Chongkang Tan and Michael Lyu. </span>

  <span style="font-size:14px;"> *The 41st IEEE/ACM International Conference on Automated Software Engineering, Munich, Germany, October 2026.* </span>

  [Paper]
  [Code]
  [Slides]
  [DOI]

- &nbsp; <span class="badge">ICSE '26</span> &nbsp;**InferLog: Accelerating LLM Inference for Online Log Parsing via ICL-oriented Prefix Caching**

  <span style="font-size:14px;"> Yilun Wang, Pengfei Chen, **Haiyu Huang**, Zilong He, Gou Tan, Chuanfu Zhang, Jingkai He and Zibin Zheng. </span>

  <span style="font-size:14px;"> *The 48th IEEE/ACM International Conference on Software Engineering, Rio de Janeiro, Brazil, April 2026.* </span>

  [[Paper](https://arxiv.org/abs/2507.08523)]
  [[Code](https://github.com/wiluen/InferLog)]
  [Slides]
  [[DOI](https://doi.org/10.1145/3744916.3764523)]

- &nbsp; <span class="badge">TOSEM '26</span> &nbsp;**LLMRCA: Multilevel Root Cause Analysis for LLM Applications Using Multimodal Observability Data**

  <span style="font-size:14px;"> Gou Tan, Zilong He, Min Li, **Haiyu Huang**, Yilun Wang, Pengfei Chen, Giuliano Casale and Chuanfu Zhang. </span>

  <span style="font-size:14px;"> *ACM Transactions on Software Engineering and Methodology, 2026.* </span>

  [[Paper](https://dl.acm.org/doi/pdf/10.1145/3806200)]
  [[Code](https://github.com/IntelligentDDS/LLMRCA)]
  [Slides]
  [[DOI](https://doi.org/10.1145/3806200)]

- &nbsp; <span class="badge">Arxiv</span> &nbsp;**Cloud-OpsBench: A Reproducible Benchmark for Agentic Root Cause Analysis in Cloud Systems**

  <span style="font-size:14px;"> Yilun Wang, Guangba Yu, **Haiyu Huang**, Yujie Huang, Zirui Wang, Pengfei Chen and Michael R. Lyu. </span>

  [[Paper](https://arxiv.org/abs/2603.00468)]
  [[Code](https://github.com/LLM4Ops/Cloud-OpsBench)]
  [Slides]
  [[DOI](https://doi.org/10.48550/arXiv.2603.00468)]

- &nbsp; <span class="badge">ASE '25</span> &nbsp;**LogPilot: Intent-aware and Scalable Alert Diagnosis for Large-scale Online Service Systems**

  <span style="font-size:14px;"> Zhihan Jiang, Jinyang Liu, Yichen Li, **Haiyu Huang**, Xiao He, Tieying Zhang, Jianjun Chen, Yi Li, Rui Shi and Michael R. Lyu. </span>

  <span style="font-size:14px;"> *The 40th IEEE/ACM International Conference on Automated Software Engineering, 2025.* </span>

  [[Paper](https://arxiv.org/abs/2509.25874)]
  [Code]
  [Slides]
  [DOI]

- &nbsp; <span class="badge">IWQOS '25</span> &nbsp;**LLMConf: Knowledge-Enhanced Configuration Optimization for Large Language Model Inference**

  <span style="font-size:14px;"> Jingkai He, Pengfei Chen, Yilun Wang, **Haiyu Huang**, Chuanfu Zhang, Haojia Huang, Danwen Chen. </span>

  <span style="font-size:14px;"> *IEEE/ACM International Symposium on Quality of Service, Gold Coast, Australia, July 2025.* </span> 

  [Paper]
  [Code]
  [Slides]
  [DOI]

- &nbsp; <span class="badge">ASPLOS '25</span> &nbsp;**Mint: Cost-Efficient Tracing with All Requests Collection via Commonality and Variability Analysis**

  <span style="font-size:14px;"> **Haiyu Huang**, Cheng Chen, Kunyi Chen, Pengfei Chen, Guangba Yu, Zilong He, Yilun Wang, Huxing Zhang and Qi Zhou. </span>

  <span style="font-size:14px;"> *The ACM International Conference on Architectural Support for Programming Languages and Operating Systems, Rotterdam, the Netherlands, March-April 2025.* </span>

  [[Paper](https://huanghy95.github.io/files/asplos25/asplos25Mint.pdf)]
  [Code]
  [Slides]
  [DOI]

- &nbsp; <span class="badge">SANER '25</span> &nbsp;**Conan: Uncover Consensus Issues in Distributed Databases Using Fuzzing-driven Fault Injection**

  <span style="font-size:14px;"> Haojia Huang, Pengfei Chen, Guangba Yu, **Haiyu Huang**, Jia Chang, Jun Li and Jian Han. </span>

  <span style="font-size:14px;"> *The IEEE International Conference on Software Analysis, Evolution and Reengineering, Montréal, Québec, Canada, March 2025.* </span>

  [Paper]
  [Code]
  [Slides]
  [DOI]

- &nbsp; <span class="badge">ISSRE '24</span> &nbsp;**FaaSRCA: Full Lifecycle Root Cause Analysis for Serverless Applications**

  <span style="font-size:14px;"> Jin Huang, Pengfei Chen, Guangba Yu, Yilun Wang, **Haiyu Huang** and Zilong He. </span>

  <span style="font-size:14px;"> *The 35th International Symposium on Software Reliability Engineering, Tsukuba, Japan, October 2024.* </span>

  [Paper]
  [Code]
  [Slides]
  [DOI]

- &nbsp; <span class="badge">ASE '24</span> &nbsp;**FaaSConf: QoS-aware Hybrid Resources Configuration for Serverless Workflows**

  <span style="font-size:14px;"> Yilun Wang, Pengfei Chen, Hui Dou, Guangba Yu, Zilong He and **Haiyu Huang**. </span>

  <span style="font-size:14px;"> *The 39th IEEE/ACM International Conference on Automated Software Engineering, California, United States, October 2024.* </span>

  [[Paper](https://huanghy95.github.io/files/ase24/ase24faasconf.pdf)]
  [[Code](https://github.com/wiluen/FaaSConf)]
  [Slides]
  [[DOI](https://dl.acm.org/doi/10.1145/3691620.3695477)]

- &nbsp; <span class="badge">FSE '24</span> &nbsp;&nbsp;<span class="award">Distinguished Paper Award</span> **TraStrainer: Adaptive Sampling for Distributed Traces with System Runtime State**

  <span style="font-size:14px;"> **Haiyu Huang**, Xiaoyu Zhang, Pengfei Chen, Zilong He, Zhiming Chen, Guangba Yu, Hongyang Chen and Chen Sun. </span>

  <span style="font-size:14px;"> *The ACM International Conference on the Foundations of Software Engineering, Porto de Galinhas, Brazil, July 2024.* </span>

  [[Paper](https://huanghy95.github.io/files/fse24/fse2024TraStrainer.pdf)]
  [[Code](https://github.com/IntelligentDDS/TraStrainer)]
  [[Slides](https://huanghy95.github.io/files/fse24/fse351slides.pdf)]
  [[DOI](https://dl.acm.org/doi/abs/10.1145/3643748)]

- &nbsp; <span class="badge">Arxiv</span> &nbsp;**TraGraphRCA: Practical Multi-Level Root Cause Analysis for Microservice with Trace-Graph Fusion**

  <span style="font-size:14px;"> **Haiyu Huang**, Xiaoyu Zhang, Pengfei Chen, Guangba Yu, Zilong He, Qiuai Fu and Michael R. Lyu. </span>

  [[Paper](https://huanghy95.github.io/files/tosem24/TraGraphRCA_TOSEM.pdf)]
  [Code]
  [Slides]
  [DOI]


# 🎖 Honors and Awards
- *2025.04* Hong Kong PhD Fellowship (HKPFS), Hong Kong University Grants Committee
- *2025.02* CUHK Vice-Chancellor's Scholarship, The Chinese University of Hong Kong
- *2020.10, 2024.10* National Scholarship, Ministry of Education of the P.R. China. 
- *2024.06* ACM SIGSOFT Distinguished Paper award, FSE 2024.
- *2023.12* 3rd Prize, CCF International AIOps Challenge (Ranked 1st among student teams) (**As Team Leader**).

# 📖 Educations
- *2025.08 - (now)*, Ph.D. student, The Chinese University of Hong Kong
- *2023.09 - 2025.07*, research assistant, Sun Yat-Sen University
- *2019.09 - 2023.06*, Bachelor degree, Sun Yat-Sen University

# 💬 Services
- *Reviewer:*  WWW 2024

<!-- # 💻 Internships -->
