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

I am a Ph.D. student at the [New Laboratory of Pattern Recognition(NLPR)](http://www.cripac.ia.ac.cn/CN/model/index.htm), Institute of Automation, Chinese Academy of Sciences, advised by Prof. [Yan Huang](https://yanrockhuang.github.io/). I am currently interning at JD Explore Academy, and have previously interned at Beijing Academy of Artificial Intelligence (BAAI), Kuaishou Technology, and Tsinghua AIR. 

My research is broadly about what agents can do — how far we can push their ability to search, reason, create, and even conduct research autonomously. My earlier work focused on search agents for video understanding, driven by a central question: what can models actually do when they must actively search and compare external evidence? I built agents that retrieve and reason over open-web evidence, and designed benchmarks that reveal where frontier multimodal models fall short when required to search, compare, and ground claims across multiple sources. I am now extending this to agentic video generation and autoresearch — moving from agents that understand the world to agents that actively create and explore it.

I believe impactful research comes from close collaboration across communities. If you're working on agentic AI, video generation, or autoresearch, or if you have internship or exchange opportunities, I'd be glad to connect.

# 🔥 News
- *2026.08*: &nbsp;🎉🎉 Two papers on Search Agent for Video Understanding (Misinformation Detection & Shot Retrieval) were accepted by EMNLP 2026 Findings!
- *2026.01*: &nbsp;🎉🎉 One paper on Browser Agent were accepted by TMLR 2025!
- *2025.11*: &nbsp;🎉🎉 Two papers on Multi-View Clustering and Deepfake were accepted by AAAI 2026!
- *2025.07*: &nbsp;🎉🎉 One technical report on Kwai Keye-VL was released!
- *2025.05*: &nbsp;🎉🎉 One paper on DPO (Direct Preference Optimization) was accepted by ICML 2025!
- *2025.02*: &nbsp;🎉🎉 One paper on GUI Agent was accepted by CVPR 2025!
- *2024.06*: &nbsp;🎉🎉 One paper on Knowledge Editing Benchmark was accepted by NeurIPS 2024 Datasets and Benchmarks Track!
- *2023.08*: &nbsp;🎉🎉 One paper on Mobile Agent was accepted by Mobicom 2024 Summer Round!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/SCOPE-Router.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SCOPE-Router: Cost-Aware Open-Set VLM Routing for Execution-Oriented Tasks](https://arxiv.org/abs/2608.12127)

![GitHub Repo stars](https://img.shields.io/github/stars/yutao1024/SCOPE-Router?style=social) &nbsp; [**Project**](https://github.com/yutao1024/SCOPE-Router)

**Tao Yu**, Yifei Qu, Zhiqing Cui, Pengfei Zhou, Zhongtian Luo, Yujia Yang, Shenghua Chai, Haopeng Jin, Zhenghao Zhang, Xinming Wang, Hongzhu Yi, Wangbo Zhao, Zhenglin Wan, Yan Huang, Yeshani, Jinwen Luo, Yang You

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2026 Findings</div><img src='images/EVID-Bench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[When Seeing Is Not Believing--A Benchmark for Search-Grounded Video Misinformation Detection](https://arxiv.org/abs/2606.04098)

![GitHub Repo stars](https://img.shields.io/github/stars/yutao1024/EVID-Bench?style=social) &nbsp; [**Project**](https://github.com/yutao1024/EVID-Bench)

**Tao Yu**, Yujia Yang, Shenghua Chai, Zhang Jinshuai, Haopeng Jin, Hao Wang, Minghui Zhang, Zhongtian Luo, Yuchen Long, Xinlong Chen, Jiabing Yang, Zhaolu Kang, Yuxuan Zhou, Zhengyu Man, Xinming Wang, Hongzhu Yi, Zheqi He, Xi Yang, Yan Huang, Liang Wang

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/EntCollabBench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Beyond the All-in-One Agent: Benchmarking Role-Specialized Multi-Agent Collaboration in Enterprise Workflows](https://arxiv.org/abs/2605.08761)

![GitHub Repo stars](https://img.shields.io/github/stars/yutao1024/EntCollabBench?style=social) &nbsp; [**Project**](https://github.com/yutao1024/EntCollabBench)

**Tao Yu**, Hao Wang, Changyu Li, Shenghua Chai, Minghui Zhang, Zhongtian Luo, Yuxuan Zhou, Haopeng Jin, Zhaolu Kang, Jiabing Yang, YiFan Zhang, Xinming Wang, Hongzhu Yi, Zheqi He, Jing-Shu Zheng, Xi Yang, Yan Huang, Liang Wang

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/Omni-Deepsearch.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Omni-DeepSearch: A Benchmark for Audio-Driven Omni-Modal Deep Search](https://arxiv.org/abs/2605.08762)

![GitHub Repo stars](https://img.shields.io/github/stars/yutao1024/Omni-DeepSearch?style=social) &nbsp; [**Project**](https://github.com/yutao1024/Omni-DeepSearch)

**Tao Yu**, Yiming Ding, Shenghua Chai, Minghui Zhang, Zhongtian Luo, Xinming Wang, Xinlong Chen, Zhaolu Kang, Junhao Gong, Yuxuan Zhou, Haopeng Jin, Zhiqing Cui, Jiabing Yang, YiFan Zhang, Hongzhu Yi, Zheqi He, Xi Yang, Yan Huang, Liang Wang

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/RVMS-Bench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Beyond Closed-Pool Video Retrieval: A Benchmark and Agent Framework for Real-World Video Search and Moment Localization](http://arxiv.org/abs/2602.10159)

![GitHub Repo stars](https://img.shields.io/github/stars/yutao1024/RACLO?style=social) &nbsp; [**Project**](https://github.com/yutao1024/RACLO)

**Tao Yu**, Yujia Yang, Haopeng Jin, Junhao Gong, Xinlong Chen, Yuxuan Zhou, Shanbin Zhang, Jiabing Yang, Xinming Wang, YiFan Zhang, Hongzhu Yi, Ping Nie, Kai Zou, Zhang Zhang, Yan Huang, Liang Wang, Yeshani, Ruiwen Tao, Jin Ma, Haijin Liang, Jinwen Luo

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/PaperX.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PaperX: A Unified Framework for Multimodal Academic Presentation Generation with Scholar DAG](https://arxiv.org/abs/2602.03866)

![GitHub Repo stars](https://img.shields.io/github/stars/yutao1024/PaperX?style=social) &nbsp; [**Project**](https://github.com/yutao1024/PaperX)

**Tao Yu**, Minghui Zhang, Zhiqing Cui, Hao Wang, Zhongtian Luo, Shenghua Chai, Junhao Gong, Yuzhao Peng, Yuxuan Zhou, Yujia Yang, Zhenghao Zhang, Haopeng Jin, Xinming Wang, Yufei Xiong, Jiabing Yang, Jiahao Yuan, Hanqing Wang, Hongzhu Yi, YiFan Zhang, Yan Huang, Liang Wang

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2026 Findings</div><img src='images/ShotFinder.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ShotFinder: Imagination-Driven Open-Domain Video Shot Retrieval via Web Search](https://arxiv.org/abs/2601.23232)

![GitHub Repo stars](https://img.shields.io/github/stars/yutao1024/ShotFinder?style=social) &nbsp; [**Project**](https://github.com/yutao1024/ShotFinder) &nbsp; [**Post**](https://x.com/ZhihuFrontier/status/2089969262261866584?s=20)

**Tao Yu**, Haopeng Jin, Hao Wang, Shenghua Chai, Yujia Yang, Junhao Gong, Jiaming Guo, Minghui Zhang, Xinlong Chen, Zhenghao Zhang, Yuxuan Zhou, Yufei Xiong, Shanbin Zhang, Jiabing Yang, Hongzhu Yi, Xinming Wang, Cheng Zhong, Xiao Ma, Zhang Zhang, Yan Huang, Liang Wang

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMLR 2025</div><img src='images/Browseragent.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[BrowserAgent: Building Web Agents with Human-Inspired Web Browsing Actions](https://arxiv.org/abs/2510.10666)

![GitHub Repo stars](https://img.shields.io/github/stars/TIGER-AI-Lab/BrowserAgent?style=social) &nbsp; [**Project**](https://github.com/TIGER-AI-Lab/BrowserAgent)

**Tao Yu**, Zhengbo Zhang, Zhiheng Lyu, Junhao Gong, Hongzhu Yi, Xinming Wang, Yuxuan Zhou, Jiabing Yang, Ping Nie, Yan Huang, Wenhu Chen

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/Aligning Multimodal LLM with Human Preference.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Aligning Multimodal LLM with Human Preference: A Survey](https://arxiv.org/abs/2503.14504)

![GitHub Repo stars](https://img.shields.io/github/stars/BradyFU/Awesome-Multimodal-Large-Language-Models?style=social) &nbsp; [**Project**](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/tree/Alignment) &nbsp; [**Post**](https://mp.weixin.qq.com/s/8djZcfyl3v0N1eZRQBk0Yg)

**Tao Yu**, Yi-Fan Zhang, Chaoyou Fu, Junkang Wu, Jinda Lu, Kun Wang, Xingyu Lu, Yunhang Shen, Guibin Zhang, Dingjie Song, Yibo Yan, Tianlong Xu, Qingsong Wen, Zhang Zhang, Yan Huang, Liang Wang, Tieniu Tan

</div>
</div>

## Others

- <br> **EMNLP 2026 Main**, [Why does Weak-OOD Help? A Further Step Towards Understanding Jailbreaking VLMs](https://arxiv.org/abs/2511.08367)      
Yuxuan Zhou, Yuzhao Peng, Yang Bai, Kuofeng Gao, Yihao Zhang, Yechao Zhang, Xun Chen, **Tao Yu**, Tao Dai, Shu-Tao Xia

- <br> **ACL 2026 Main**, [Scaling Law for Multimodal Large Language Model Supervised Fine-Tuning](https://aclanthology.org/2026.acl-long.603/)      
Yifan Zhang, **Tao Yu**, Feng Li, Chaoyou Fu, Yibo Hu, Kun Wang, Qingsong Wen, Zhang Zhang, Liang Wang, Rong Jin

- ![GitHub Repo stars](https://img.shields.io/github/stars/Yuxuan2003/CRDA?style=social) <br> **AAAI 2026**, [Improving Deepfake Detection with Reinforcement Learning-Based Adaptive Data Augmentation](https://arxiv.org/abs/2511.07051)      
Yuxuan Zhou, **Tao Yu**, Wen Huang, Yuheng Zhang, Tao Dai, Shu-Tao Xia

- ![GitHub Repo stars](https://img.shields.io/github/stars/PaddiHunter/DGIMVCM?style=social) <br> **AAAI 2026**, [Dynamic Deep Graph Learning for Incomplete Multi-View Clustering with Masked Graph Reconstruction Loss](https://arxiv.org/abs/2511.11181)    
Zhenghao Zhang, Jun Xie, Xingchen Chen, **Tao Yu**, Hongzhu Yi, Kaixin Xu, Yuanxiang Wang, Tianyu Zong, Xinming Wang, Jiahuan Chen, Guoqing Chao, Feng Chen, Zhepeng Wang, Jungang Xu

- ![GitHub Repo stars](https://img.shields.io/github/stars/Kwai-Keye/Keye?style=social) <br> **Technical Report**, [Kwai Keye-VL Technical Report](https://arxiv.org/abs/2507.01949)      
Kwai Keye Team
- ![GitHub Repo stars](https://img.shields.io/github/stars/Kwai-YuanQi/MM-RLHF?style=social) <br> **ICML 2025**, [MM-RLHF: The Next Step Forward in Multimodal LLM Alignment](https://arxiv.org/abs/2502.10391)      
Yi-Fan Zhang, **Tao Yu**, Haochen Tian, Chaoyou Fu, Peiyan Li, Jianshu Zeng, Wulin Xie, Yang Shi, Huanyu Zhang, Junkang Wu, Xue Wang, Yibo Hu, Bin Wen, Fan Yang, Zhang Zhang, Tingting Gao, Di Zhang, Liang Wang, Rong Jin, Tieniu Tan
- ![GitHub Repo stars](https://img.shields.io/github/stars/921112343/GUI-Xplore?style=social) <br> **CVPR 2025**, [GUI-Xplore: Empowering Generalizable GUI Agents with One Exploration](https://arxiv.org/abs/2503.17709)       
Yuchen Sun, Shanhui Zhao, **Tao Yu**, Hao Wen, Samith Va, Mengwei Xu, Yuanchun Li, Chongyang Zhang
- ![GitHub Repo stars](https://img.shields.io/github/stars/VLKEB/VLKEB?style=social) <br> **NeurIPS 2024**, [VLKEB: A Large Vision-Language Model Knowledge Editing Benchmark](https://arxiv.org/abs/2403.07350)       
Han Huang, Haitian Zhong, **Tao Yu**, Qiang Liu, Shu Wu, Liang Wang, Tieniu Tan
- ![GitHub Repo stars](https://img.shields.io/github/stars/MobileLLM/AutoDroid?style=social) <br> **Mobicom 2024**, [Autodroid: Llm-powered task automation in android](https://arxiv.org/abs/2308.15272)        
Hao Wen, Yuanchun Li, Guohong Liu, Shanhui Zhao, **Tao Yu**, Toby Jia-Jun Li, Shiqi Jiang, Yunhao Liu, Yaqin Zhang, Yunxin Liu

# 🎖 Honors and Awards
- *2024.12*, National Scholarship.(**0.4%**)
- *2023.12*, National Encouragement Scholarship.(**0.4%**)
- *2022.12*, National Scholarship.(**0.4%**)
- *2022.06*, First Grade Scholarship.(**0.4%**)

# 📖 Educations
- *2025.09 - Current*, Ph.D. Student in Pattern Recognition and Intelligent Systems (Institute of Automation, Chinese Academy of Sciences)
- *2021.09 - 2025.06*, Bachelor in Computer Science and Technology (School of Computer Science and Technology, Harbin Institute of Technology), GPA: 93.79/100 (Ranking: 2/135)

# 🤝 Collaborator

- *2022 Cohort*, Jinshuai Zhang (HIT->THU), Hao Wang (HIT->USTC)
- *2023 Cohort*, Yiming Ding (HIT->SJTU), Shenghua Chai (HIT->ZJU), Minghui Zhang (HIT->CASIA NLPR), Hao Wang (HIT->ICT VIPL), Zhongtian Luo (HIT->TencentxHIT), Yifei Qu (HIT->AILabxHIT)

# 💻 Internships
- *2026.08 - Present*, Big Data Engineering Department, JD Explore Academy (JD.com), China.
- *2026.03 - 2026.08*, Intelligent Evaluation Group, Beijing Academy of Artificial Intelligence (BAAI), China.
- *2025.01 - 2025.07*, Multimodal Understanding and Application Group, Kuaishou Technology, China.
- *2024.03 - 2024.06*, New Laboratory of Pattern Recognition(NLPR), Institute of Automation, China.
- *2023.05 - 2024.07*, Institute for AI Industry Research(AIR), Tsinghua University, China.
