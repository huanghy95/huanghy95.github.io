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

📚 Haiyu Huang is currently a research assistant at [Sun Yat-Sen University](https://cse.sysu.edu.cn/), advised by Professor [Pengfei Chen](https://cse.sysu.edu.cn/content/3747). Previously, he received a B.E. in CSE from Sun Yat-Sen University in 2023. He has interned at [Alibaba Cloud](https://cn.aliyun.com/), [Huawei](https://www.huawei.com/), and [Ant Group](https://www.antgroup.com/) in Cloud Native Application Performance Management related departments, developing algorithms and solving real-world problems.

💡 His research interest lies in microservices reliabilty (e.g., developing observability tools for cloud systems.), AI for DevOps (e.g., automating software debugging and troubleshooting during development or operations, especially using LLMs) and MLOps (e.g., automating AI system operations).


# 🔥 News
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

- &nbsp; <span class="badge">ASPLOS '25</span> &nbsp;**Mint: Cost-Efficient Tracing with All Requests Collection via Commonality and Variability Analysis**

  <span style="font-size:14px;"> **Haiyu Huang**, Cheng Chen, Kunyi Chen, Pengfei Chen, Guangba Yu, Zilong He, Yilun Wang, Huxing Zhang and Qi Zhou. </span>

  <span style="font-size:14px;"> *The ACM International Conference on Architectural Support for Programming Languages and Operating Systems, Rotterdam, the Netherlands, March-April 2025.* </span>

  [[Paper](https://huanghy95.github.io/files/asplos25/asplos25Mint.pdf)]
  [Code]
  [Slides]
  [DOI]

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

- &nbsp; <span class="badge">ASE '24</span> &nbsp;**FaaSConf: QoS-aware Hybrid Resources Configuration for Serverless Workflows**

  <span style="font-size:14px;"> Yilun Wang, Pengfei Chen, Hui Dou, Guangba Yu, Zilong He and **Haiyu Huang**. </span>

  <span style="font-size:14px;"> *The 39th IEEE/ACM International Conference on Automated Software Engineering, California, United States, October 2024.* </span>

  [[Paper](https://huanghy95.github.io/files/ase24/ase24faasconf.pdf)]
  [[Code](https://github.com/wiluen/FaaSConf)]
  [Slides]
  [[DOI](https://dl.acm.org/doi/10.1145/3691620.3695477)]

- &nbsp; <span class="badge">IWQOS '25</span> &nbsp;**LLMConf: Knowledge-Enhanced Configuration Optimization for Large Language Model Inference**

  <span style="font-size:14px;"> Jingkai He, Pengfei Chen, Yilun Wang, **Haiyu Huang**, Chuanfu Zhang, Haojia Huang, Danwen Chen. </span>

  <span style="font-size:14px;"> *IEEE/ACM International Symposium on Quality of Service, Gold Coast, Australia, July 2025.* </span> 

  [Paper]
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


# 🎖 Honors and Awards
- *2025.04* Hong Kong PhD Fellowship (HKPFS), Hong Kong University Grants Committee
- *2025.02* CUHK Vice-Chancellor's Scholarship, The Chinese University of Hong Kong
- *2024.10* National Scholarship, Ministry of Education of the P.R. China. 
- *2024.06* ACM SIGSOFT Distinguished Paper award, FSE 2024.
- *2023.12* 3rd Prize, CCF International AIOps Challenge (Ranked 1st among student teams) (**As Team Leader**).
- *2020.10* National Scholarship, Ministry of Education of the P.R. China. 

# 📖 Educations
- *2023.09 - (now)*, research assistant, Sun Yat-Sen University
- *2019.09 - 2023.06*, Bachelor degree, Sun Yat-Sen University

# 💬 Services
- *Reviewer:*  WWW 2024

<!-- # 💻 Internships -->