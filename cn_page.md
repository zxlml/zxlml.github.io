---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

[English](./pages/about.md) 

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

本科就读于中国农业大学，研究生就读于华中农业大学。硕士期间（2020-2022）在[武玲娟教授](https://www.researchgate.net/profile/Lingjuan-Wu)的指导下研究**可解释稳健机器学习**算法设计以及在**硬件安全领域**的应用；博士期间（2022-）在[陈洪教授](https://chenhongml.github.io/)的指导下研究**可解释稳健优化算法设计与统计理论分析**。

我的研究方向主要包括：

- 自动机器学习（双层优化、元学习）

- 可解释/鲁棒算法设计（鲁棒度量函数设计、稀疏可加建模）

- 硬件安全应用（基于 自然语言与拓扑结构 等策略的硬件特洛伊木马检测）
  
我预计2026年中旬毕业。如果你对我的研究方向感兴趣，或者愿意给俺个offer，请联系: zhangxuelin@webmail.hzau.edu.cn

# 🔥 新闻

- *2025.01*: &nbsp;🎉🎉  合作论文接收在**TCAD (ccf-A)**类期刊. 

- *2024.12*: &nbsp;🎉🎉  参加CCF2024年会暨第八届优秀博士论坛.

- *2024.11*: &nbsp;🎉🎉  荣获 **博士国家奖学金**.

# 📝 Publications in Machine Learning

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[8] ICDM 2024 [ccf-B]</div><img src='images/ICDM2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Generalized Sparse Additive Model with Unknown Link Function](https://icdm2024.org/accepted_papers/)

Peipei Yuan, Xinge You*, Hong Chen, **Xuelin Zhang**, and Qinmu Peng. 

**IEEE International Conference on Data Mining 2024 [C]**

- In this work, we propose a novel generalized additive model with a flexible link function automatically learned by a bilevel scheme. The proposed model is capable of nonlinear approximation, hidden interaction and feature selection, which also enjoys the theoretical guarantee of algorithmic convergence.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[7] ESWA 2024 [sci-1 Top]</div><img src='images/eswa24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Error Density-dependent Empirical Risk Minimization](https://www.sciencedirect.com/science/article/pii/S0957417424011989)

Hong Chen*, **Xuelin Zhang**, Tieliang Gong, Bin Gu, Feng Zheng. 

**Expert Systems With Applications 2024 [J]**

- This paper goes beyond the limitation of error value-dependent learning criterion and proposes the EDERM framework for robust regression against atypical data. The effectiveness of our method is validated by sufficient empirical evaluations. The implementation codes can be found at: [https://github.com/zhangxuelincode/EDERM](https://github.com/zhangxuelincode/EDERM)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[6] IJCAI 2024 [ccf-A]</div><img src='images/ijcai24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Fine-grained Analysis of Stability and Generalization for Stochastic Bilevel Optimization](https://www.ijcai.org/proceedings/2024/609)

**Xuelin Zhang**, Hong Chen*, Bin Gu, Tieliang Gong, Feng Zheng. 

**International Joint Conference on Artificial Intelligence 2024 [C] (Oral)**

- In this paper, we provide a systematical generalization analysis of the first-order gradient-based bilevel optimization methods, based on the (on-average argument) algorithmic stability technique. The verification codes are provided at: [https://github.com/zhangxuelincode/BilevelOptimization](https://github.com/zhangxuelincode/BilevelOptimization)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[5] IJCNN 2024 [ccf-C]</div><img src='images/ijcnn24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Improved Concentration Bound for CVaR](https://ieeexplore.ieee.org/abstract/document/10650860)

Peng Sima, Hao Deng*, **Xuelin Zhang**, Hong Chen. 

**International Joint Conference on Neural Networks 2024 [C]**

- This paper introduces a novel estimator that relies on an estimator of Value at Risk (VaR) and investigates the concentration inequalities in independent scenarios where the underlying distributions are sub-Gaussian, sub-exponential, or heavy-tailed, where the inequalities we derive are bilateral, exhibit exponential decay, and are not confined to bounded scenarios.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[4] FCS 2023 [ccf-B]</div><img src='images/fcs23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Neural Partially Linear Additive Model](https://link.springer.com/article/10.1007/s11704-023-2662-3)

Liangxuan Zhu, Han Li*, **Xuelin Zhang**, Lingjuan Wu, Hong Chen. 

**Frontiers of Computer Science 2023 [J]**

- This paper proposes a Neural  Partially  Linear  Additive  Model  (NPLAM),  which automatically  distinguishes  insignificant,  linear,  and  nonlinear features  in  neural  networks, which can realize model-level interpretability.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[3] AAAI 2023 [ccf-A]</div><img src='images/aaai23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Stepdown SLOPE for Controlled Feature Selection](https://ojs.aaai.org/index.php/AAAI/article/view/26050)

Jingxuan Liang, **Xuelin Zhang**, Hong Chen*, Weifu Li, Xin Tang. 

**Association for the Advancement of Artificial Intelligence 2023 [C] (Oral)**

- This paper goes beyond the previous concern of Sorted L-One Penalized Estimation (SLOPE) limited to the false discovery rate (FDR) control by considering the stepdown-based SLOPE in order to control the probability of k or more false rejections (k-FWER) and the false discovery proportion (FDP).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[2] APIN 2023 [sci-2]</div><img src='images/apin23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Robust variable structure discovery based on tilted empirical risk minimization](https://dl.acm.org/doi/abs/10.1007/s10489-022-04409-z)

**Xuelin Zhang**, Yingjie Wang, Liangxuan Zhu, Hong Chen, Han Li, Lingjuan Wu*. 

**Applied Intelligence 2023 [J]**

- In this paper, we propose a new robust variable structure discovery method for group lasso based on a convergent bilevel optimization framework, where the robust tilted empirical risk minimization is adopted. The implementation codes can be found at: [https://github.com/zhangxuelincode/demoTERMGL](https://github.com/zhangxuelincode/demoTERMGL)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[1] ICCCS 2022</div><img src='images/icccs22.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Robustness of classifier to adversarial examples under imbalanced data](https://ieeexplore.ieee.org/document/9846074)

Wenqian Zhao, Han Li, Lingjuan Wu*, Liangxuan Zhu, **Xuelin Zhang**, Yizhi Zhao. 

**International Conference on Computer and Communication Systems 2022 [C]**

- In this paper, we provide a theoretical framework to analyze the robustness of classifier to AE under imbalanced dataset from the perspective of AUC (Area under the ROC curve), and derive an interpretable upper bound.
</div>
</div>


# 📝 Publications in Hardware Security

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[4] TCAD 2025 [ccf-A]</div><img src='images/tcad2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Precise and Explainable Hardware Trojan Localization at LUT Level](https://zxlml.github.io/)

Hao Su, Wei Hu, **Xuelin Zhang**, Dan Zhu, Lingjuan Wu*. 

**IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems 2025 [J]**

- The proposed approach aims to extract the rich structural and behavioral features at look-up-table (LUT) level to train an explainable graph neural network (GNN) model for classifying design nodes in FPGA netlists and identifying the Trojan-infected ones. The implementation codes can be found at: [https://github.com/zhangxuelincode/node_label](https://github.com/zhangxuelincode/node_label)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[3] ITC-Asia 2024 [ccf-C]</div><img src='images/itc24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Pinpointing Hardware Trojans Through Semantic Feature Extraction and Natural Language Processing](https://ieeexplore.ieee.org/abstract/document/10661348)

Yichen Li, Wei Hu, Hao Su, **Xuelin Zhang**, Yizhi Zhao, Lingjuan Wu*. 

**International Test Conference in Asia 2024 [C]**

- In this work, we propose a novel hardware Trojan detection method at RTL. Our approach involves the transformation of hardware design into CDFG, followed by path extraction and segmentation. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[2] ICCAD 2023 [ccf-B]</div><img src='images/iccad23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Automated Hardware Trojan Detection at LUT Using Explainable Graph Neural Networks](https://ieeexplore.ieee.org/document/10323915)

Lingjuan Wu, Hao Su, **Xuelin Zhang**, Yu Tai, Han Li, Wei Hu*. 

**International Conference on Computer-Aided Design 2023 [C]**

- In this work, we propose a novel hardware Trojan detection method based on graph neural networks (GNNs) targeting FPGA netlist. We leverage the rich explicit structural features and behavioral characteristics at LUT, which offers an ideal abstraction level and granularity for Trojan detection. A GNN model with optimized class-balanced focal loss is trained for automated Trojan feature extraction and classification. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[1] HOST 2022</div><img src='images/host22.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Hardware Trojan Detection at LUT: Where Structural Features Meet Behavioral Characteristics](https://ieeexplore.ieee.org/document/9840276)

Lingjuan Wu, **Xuelin Zhang**, Siyi Wang, Wei Hu*. 

**International Symposium on Hardware Oriented Security and Trust 2022 [C]**

- This work proposes a novel hardware Trojan detection method that leverages static structural features and behavioral characteristics in field programmable gate array (FPGA) netlists. Mapping of hardware design sources to look-up-table (LUT) networks makes these features explicit, allowing automated feature extraction and further effective Trojan detection through machine learning.
</div>
</div>



# 🎖️ Activities and Honors
- *2024.12:* 受邀汇报： [**CCF Wuhan 2024 Annual Conference and 8th Outstanding Doctoral Student Academic Forum**.](https://www.ccf.org.cn/Chapters/Chapters/Wuhan/hyhdzxdt/2024-12-23/836269.shtml)
- *2024.11:* 荣获 [**博士国家奖学金**.](https://aisle.hzau.edu.cn/info/1097/2216.htm)
- *2024.11:* 海报参展： [**CSIAM 2024**.](https://aisle.hzau.edu.cn/info/1097/2201.htm)
- *2024.8:* 受邀汇报： [**Conference of IJCAI-2024**.](https://aisle.hzau.edu.cn/info/1097/1911.htm)
- *2024.4:* 受邀汇报： [**HBSIAM 2024**.](https://aisle.hzau.edu.cn/info/1097/1901.htm)

# 🛠️ Authorized Patents
- *2024.06:* 陈洪, **张学林**, 李伟夫, 郑锋. [**CN114580299A**.](https://patents.google.com/patent/CN114580299A/zh)

# 💬 学术服务

- 会议审稿人: ICLR, ICML, IJCNN.

- 期刊审稿人: Expert Systems With Applications, Journal of Infrastructure, Policy and Development.
  
# 🌏 Visit Counter
<a href="https://info.flagcounter.com/LoqT"><img src="https://s05.flagcounter.com/countxl/LoqT/bg_FFFFFF/txt_061414/border_CC4BBB/columns_8/maxflags_12/viewers_0/labels_1/pageviews_1/flags_0/percent_0/" alt="Flag Counter" border="0"></a>
