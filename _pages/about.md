---
permalink: /
title: "About Me"
# excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a final-year CS graduate student at [Fudan University](https://www.fudan.edu.cn/), and I am interning at Meituan, where I am working on developing a system to support the training of large, multi-modality models.

Before my internship at Meituan, I completed a remote research internship supervised by [Prof. Binhang Yuan](https://binhangyuan.github.io/site/) at [HKUST](https://cse.hkust.edu.hk). Prior to that, I was a research intern at [NTU](https://www.ntu.edu.sg/scse), where I worked under the mentorship of [Prof. Siqiang Luo](http://siqiangluo.com/).

I am passionate about developing AI systems for downstream applications, and my recent focus has been on building efficient training systems for large foundation models. Additionally, I am trying to participate in [SGLang](https://github.com/sgl-project/sglang), an fantastic framework for serving foundation models, as a side project.

I am currently exploring opportunities in the job market. If you are interested in my profile, feel free to reach out!


## Industry Experiences

- **Training System Engineering Intern**\
  *Meituan, Large Model Architecture Team, (01/2025 - Present)*
  - **Vision Encoder Long Context Training Support:** Designed and developed a context-parallelism mechanism for the vision encoder of a large multi-modality model.


- **Database System R&D Intern**\
  *ByteDance,  ByteHouse Runtime Team, (12/2023 - 04/2024)*
  - **[Geographic Data Aggregation Query Benchmark](https://mp.weixin.qq.com/s/DjvzJa_QZxH5zWcMLo-JXQ):** Developed and benchmarked geospatial aggregation queries on the NYC Taxi dataset, identifying performance disparities across major database platforms (StarRocks, ClickHouse, PostGIS, DuckDB, and ByteHouse-CE). This analysis provided actionable insights for optimizing geospatial query execution.  
  - **Geospatial Data Support for CNCH:** Integrated geometry data types into ByteHouse-CNCH (Cloud Native ClickHouse) via the geos library, enhancing its capabilities and improving data representation efficiency.  
  - **Geospatial Index Design:** Led the design and implementation of multi-level indexing (disk and memory cache) for geospatial data, reducing query latency by $50\%$ compared to the base ClickHouse implementation.


## Research Experiences

- **CE-LoRA: Computation-Efficient LoRA Fine-Tuning for Language Models [preprint]**\
  *Hong Kong University of Science and Technology, (03/2024 - 01/2025)*\
  *Collaborated with [Prof. Binhang Yuan](https://binhangyuan.github.io/site/) and [Prof. Kun Yuan](https://kunyuan827.github.io)*
  - **Algorithm Development:** Developed *CE-LoRA*, a high-efficiency algorithm for parameter-efficient fine-tuning (PEFT), which significantly reduced backpropagation costs in large language model training. By leveraging structured sparsity and low-rank approximation techniques, the model achieved a $3.39\times$ improvement in training efficiency without sacrificing accuracy.  
  - **Theoretical Analysis:** Conducted a rigorous convergence analysis, proving that *CE-LoRA* maintains the same convergence rate as LoRA, but with reduced computational overhead.


- **Oasis: An Optimal Disjoint Segmented Learned Range Filter [VLDB 24]**\
  *Nanyang Technological University, (02/2023 - 11/2023)*\
  *Collaborated with [Prof. Siqiang Luo](http://siqiangluo.com/)*
  - **Oasis:** Developed *Oasis*, a learned range filter that segments the key space into non-overlapping intervals and maps data into a bitmap using a linear model-simulated CDF as the hash function. The filter utilizes block-based Elias-Fano compression to reduce space overhead without compromising query efficiency.  
  - **Oasis+:** Created *Oasis+*, a hybrid range filter that combines learning-based and hash-based methods to enhance filter applicability and robustness across various workloads.  
  - **Integration into RocksDB:** Integrated *Oasis* and *Oasis+* into RocksDB and tested their performance, achieving up to $6.2\times$ improvement in query response times.

- **Gar: A Generate-and-Rank Approach for Natural Language to SQL Translation [ICDE 23]**\
  *Fudan University, (07/2021 - 02/2022)*\
  *Collaborated with [Prof. X. Sean Wang](https://daslab.fudan.edu.cn/61/83/c26852a287107/page.htm)*
  - **Text2SQL Framework Development:** Developed the GAR framework for Text2SQL translation, using a unique "Generate-and-Rank" approach that leverages parsing, generation, and ranking strategies for high-accuracy SQL generation from natural language queries.
  - **Benchmarking:** Built and tested a complex benchmark with self-joins, analyzing GAR's performance against other end-to-end models, providing crucial insights into its strengths in complex query generation.


## Publications

- **[preprint] CE-LoRA: Computation-Efficient LoRA Fine-Tuning for Language Models**\
  **<u>Guanduo Chen</u>**, <u>Yutong He</u>, Yipeng Hu, Kun Yuan, Binhang Yuan\
  [[Paper](https://arxiv.org/pdf/2502.01378)]

- **[VLDB 24] Oasis: An Optimal Disjoint Segmented Learned Range Filter**\
  **Guanduo Chen**, Zhenying He, Meng Li, Siqiang Luo\
  [[Paper](https://www.vldb.org/pvldb/vol17/p1911-luo.pdf), [Code](https://github.com/Woooooow-Pro/Oasis-RangeFilter)]

- **[ICDE 23] Gar: A Generate-and-Rank Approach for Natural Language to SQL Translation**\
  Y Fan, Z He, T Ren, D Guo, L Chen, R Zhu, **G Chen**, Y Jing, K Zhang, XS Wang\
  [[Paper](https://ieeexplore.ieee.org/document/10184517), [Code](https://github.com/Kaimary/GAR)]



## Education

- **M.S.** Computer Science Department Fudan University (09/2022 - 06/2025 Expected)
- **B.S.** Computer Science Department Fudan University (09/2018 - 06/2022)