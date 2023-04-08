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

I am a first-year PhD student at WestlakeNLP, where I am supervised by Professor Yue Zhang. Prior to this, I was a researcher at WeChatAI, Tencent, where I worked with Dr. Fandong Meng.
I obtained my master's degree in Computer Science from Tsinghua University, where I was supervised by Professor Jian Li and Professor Ying Liu.
I obtained my bachelor's degree from Beijing University of Posts and Telecommunications.

My research interest includes natural language generations, especially language models and machine translation. 


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/dcmbr.png' height="100%" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

*DC-MBR: Distributional Cooling for Minimum Bayesian Risk Decoding*

**Jianhao Yan**, Jin Xu, Fandong Meng, Jie Zhou, Yue Zhang

[Paper](https://arxiv.org/pdf/2212.04205)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2022</div><img src='images/digging_errors.png' height="100%" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

*Digging Errors in NMT: Evaluating and Understanding Model Errors from Partial Hypothesis Space*

**Jianhao Yan\***, Chenming Wu\*, Fandong Meng, Jie Zhou

[Paper](https://aclanthology.org/2022.emnlp-main.827.pdf) [Code](https://github.com/ElliottYan/digging_errors_nmt)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NIPS 2022</div><img src='images/ditto.png' height="100%" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

*Learning to Break the Loop: Analyzing and Mitigating Repetitions for Neural Text Generation*

Jin Xu, Xiaojiang Liu, **Jianhao Yan**, Deng Cai, Huayang Li, Jian Li

[Paper](https://openreview.net/forum?id=sexfswCc7B) [Code](https://github.com/Jxu-Thu/DITTO/)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2021</div><img src='images/selective_kd.png' height="100%" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

*Selective Knowledge Distillation for Neural Machine Translation*

Fusheng Wang, **Jianhao Yan\***, Fandong Meng, Jie Zhou

[Paper](https://aclanthology.org/2021.acl-long.504/) [Code](https://github.com/LeslieOverfitting/selective_distillation)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2020</div><img src='images/multi-unit.png' height="100%" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

*Multi-Unit Transformers for Neural Machine Translation*

**Jianhao Yan**, Fandong Meng, Jie Zhou

[Paper](https://aclanthology.org/2020.emnlp-main.77/) [Code](https://github.com/ElliottYan/Multi_Unit_Transformer)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WMT 2020 Winner in Zh-En</div><img src='images/wmt2020.png' height="100%" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

*WeChat Neural Machine Translation Systems for WMT20*

Fandong Meng, **Jianhao Yan**, Yijin Liu, Yuan Gao, Xianfeng Zeng, Qinsong Zeng, Peng Li, Ming Chen, Jie Zhou, Sifan Liu, Hao Zhou

[Paper](https://arxiv.org/pdf/2010.00247.pdf)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2020 Findings</div><img src='images/sent-control-emnlp22-findings.png' height="100%" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

*A Sentiment-Controllable Topic-to-Essay Generator with Topic Knowledge Graph*

Lin Qiao, **Jianhao Yan**, Fandong Meng, Zhendong Yang, Jie Zhou

[Paper](https://arxiv.org/pdf/2010.05511.pdf)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NAACL 2019</div><img src='images/temp-re.png' height="100%" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

*Relation Extraction with Temporal Reasoning based on Memory Augmented Distant Supervision*

**Jianhao Yan**, Lin He, Ruqin Huang, Jian Li, Ying Liu

[Paper](https://aclanthology.org/N19-1107.pdf) [Code](https://github.com/ElliottYan/DS_Temporal)
</div>
</div>



<!-- -

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2022</div><img src='images/TKK.png' height="100%" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Towards Generalizable and Robust Text-to-SQL Parsing

**Chang Gao**, Bowen Li, Wenxuan Zhang, Wai Lam, Binhua Li, Fei Huang, Luo Si, Yongbin Li

[Paper](https://aclanthology.org/2022.findings-emnlp.155/) [Code](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/tkk)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2022</div><img src='images/Yingxiu.png' width="100%" height="100%"></div></div>
<div class='paper-box-text' markdown="1">

Prompt Conditioned VAE: Enhancing Generative Replay for Lifelong Learning in Task-Oriented Dialogue

Yingxiu Zhao, Yinhe Zheng, Zhiliang Tian, **Chang Gao**, Jian Sun, Nevin L. Zhang

[Paper](https://aclanthology.org/2022.emnlp-main.766/) [Code](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/pcll)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2022</div><img src='images/UniGDD.png' width="100%" height="100%" ></div></div>
<div class='paper-box-text' markdown="1">

UniGDD: A Unified Generative Framework for Goal-Oriented Document-Grounded Dialogue

**Chang Gao**, Wenxuan Zhang, Wai Lam

[Paper](https://aclanthology.org/2022.acl-short.66/) [Code](https://github.com/gao-xiao-bai/UniGDD)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECIR 2022</div><img src='images/GACS.png' width="100%" height="100%"></div></div>
<div class='paper-box-text' markdown="1">

Search Clarification Selection via Query-Intent-Clarification Graph Attention

**Chang Gao**, Wai Lam

[Paper](https://www.researchgate.net/publication/364165129_Search_Clarification_Selection_via_Query-Intent-Clarification_Graph_Attention)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CIKM 2020</div><img src='images/Rotate3D.png' width="100%" height="100%"></div></div>
<div class='paper-box-text' markdown="1">

Rotate3D: Representing Relations as Rotations in Three-Dimensional Space for Knowledge Graph Embedding

**Chang Gao**, Chengjie Sun, Lili Shan, Lei Lin, Mingjiang Wang


[Paper](https://dl.acm.org/doi/10.1145/3340531.3411889) [Code](https://github.com/gao-xiao-bai/Rotate3D)
</div>
</div>
-->

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 📖 Educations
- *2022.08 - 2026.08 (now)*, PhD, Westlake University, Hangzhou, China
- *2016.09 - 2019.06*, Master, Tsinghua University, Beijing, China
- *2011.09 - 2015.06*, Undergraduate, Beijing University of Posts and Telecommunications, Beijing, China

<!-- # 📖 Working Experience -->

<!-- 
# 🎖 Honors and Awards
- *2020.09* ACM SIGIR Student Travel Grant 
- *2020.06* Outstanding Master Thesis Award
- *2018.06* Outstanding Graduate Award
- *2017.11* National Scholarship
- *2016.11* National Scholarship
-->



<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
 -->
# 💻 Work Experience
- *2019.07 - 2022.08*, Researcher, Wechat AI, China. 
