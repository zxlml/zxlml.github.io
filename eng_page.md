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

# 👨‍🎓 Education

I am a Ph.D. candidate (2022--) at College of Informatics, Huazhong Agricultural University, supervised by [Prof. Hong Chen](https://chenhongml.github.io/). Previously, I was persuing the M.S. degree (2020-2022) with assistance of [Prof. Lingjuan Wu](https://www.researchgate.net/profile/Lingjuan-Wu). I received the B.S. degree in Engineering from China Agricultural University in 2020. 

# 🔬 Research Area

My research interests lie in the areas of optimization and learning theory, with emphasis on the following topics:

- Automatic machine learning/LLM (e.g., **Hyperparameter Optimization**, **Hallucination Detection**)

- Robust/Interpretable machine learning (e.g., **Robust Metric**, Sparse/Neural **Additive Models**)

- Applications in hardware security (e.g., **Trojan Detection** at FPGA/Gate/LUT Synthetic Levels)

Some suggested videos for better understanding the [bilevel optimization](https://www.youtube.com/watch?v=hTDrSjBtKLc), [robust machine learning](https://www.youtube.com/watch?v=IgAPc0i0-9E), [interpretable additive models](https://www.youtube.com/watch?v=3aMB51GMUyQ) as well as the [hardware Trojans](https://www.youtube.com/watch?v=VL3kizVud9Q).

If you are interested or have any questions about my work, please feel free to contact me: zhangxuelin@webmail.hzau.edu.cn

# 🔥 News

- *2025.08*: &nbsp;🎉🎉  New Acceptance: "Interpretable Meta-weighted Sparse Neural Additive Networks for Datasets with Label Noise and Class Imbalance" to appear in **CIKM (ccf-B)**.

- *2025.05*: &nbsp;🎉🎉  New Acceptance: "On the Generalization Ability of Next-Token-Prediction Pretraining" to appear in **ICML (ccf-A)**. Congratulations to my co-authors!

- *2025.01*: &nbsp;🎉🎉  New Acceptance: "Towards Precise and Explainable Hardware Trojan Localization at LUT Level" to appear in **TCAD (ccf-A)**. Congratulations to my co-authors!

- *2024.12*: &nbsp;🎉🎉  New Activity: Attendance in CCF Wuhan 2024 Annual Conference and the 8th Outstanding Doctoral Student Academic Activity.

- *2024.11*: &nbsp;🎉🎉  New Award: **China Doctoral National Scholarship**.

# 📝 Publications in Machine Learning

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[13] ICML 2025 [ccf-A]</div><img src='images/icml2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[On the Generalization Ability of Next-Token-Prediction Pretraining](zxlml.github.io)

Zhihao Li, [Xue Jiang](https://scholar.google.com/citations?hl=zh-CN&user=ajVvHgwAAAAJ), Liyuan Liu, **Xuelin Zhang**, Hong Chen and [Feng Zheng](https://scholar.google.com/citations?user=PcmyXHMAAAAJ&hl).

**International Conference on Machine Learning 2025 [C]**

- This study establishes a theoretical framework for Next-Token-Prediction (NTP) pre-training based on Rademacher complexity, introduces a novel decomposition method, and provides the first generalization bounds for NTP. The findings offer valuable insights into how model parameters influence generalization and have been empirically validated, advancing both the theoretical comprehension and practical application of large language models.
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[12] ICDM 2024 [ccf-B]</div><img src='images/ICDM2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Generalized Sparse Additive Model with Unknown Link Function](https://icdm2024.org/accepted_papers/)

Peipei Yuan, Xinge You*, Hong Chen, **Xuelin Zhang**, and Qinmu Peng. 

**IEEE International Conference on Data Mining 2024 [C]**

- In this work, we propose a novel generalized additive model with a flexible link function automatically learned by a bilevel scheme. The proposed model is capable of nonlinear approximation, hidden interaction and feature selection, which also enjoys the theoretical guarantee of algorithmic convergence.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[11] ESWA 2024 [sci-1 Top]</div><img src='images/eswa24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Error Density-dependent Empirical Risk Minimization](https://www.sciencedirect.com/science/article/pii/S0957417424011989)

Hong Chen*, **Xuelin Zhang**, Tieliang Gong, Bin Gu, Feng Zheng. 

**Expert Systems With Applications 2024 [J]**

- This paper goes beyond the limitation of error value-dependent learning criterion and proposes the EDERM framework for robust regression against atypical data. The effectiveness of our method is validated by sufficient empirical evaluations. The implementation codes can be found at: [https://github.com/zhangxuelincode/EDERM](https://github.com/zhangxuelincode/EDERM)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[10] IJCAI 2024 [ccf-A]</div><img src='images/ijcai24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Fine-grained Analysis of Stability and Generalization for Stochastic Bilevel Optimization](https://www.ijcai.org/proceedings/2024/609)

**Xuelin Zhang**, Hong Chen*, Bin Gu, Tieliang Gong, Feng Zheng. 

**International Joint Conference on Artificial Intelligence 2024 [C] (Oral)**

- In this paper, we provide a systematical generalization analysis of the first-order gradient-based bilevel optimization methods, based on the (on-average argument) algorithmic stability technique. The verification codes are provided at: [https://github.com/zhangxuelincode/BilevelOptimization](https://github.com/zhangxuelincode/BilevelOptimization)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[9] IJCNN 2024 [ccf-C]</div><img src='images/ijcnn24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Improved Concentration Bound for CVaR](https://ieeexplore.ieee.org/abstract/document/10650860)

Peng Sima, Hao Deng*, **Xuelin Zhang**, Hong Chen. 

**International Joint Conference on Neural Networks 2024 [C]**

- This paper introduces a novel estimator that relies on an estimator of Value at Risk (VaR) and investigates the concentration inequalities in independent scenarios where the underlying distributions are sub-Gaussian, sub-exponential, or heavy-tailed, where the inequalities we derive are bilateral, exhibit exponential decay, and are not confined to bounded scenarios.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[8] FCS 2023 [ccf-B]</div><img src='images/fcs23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Neural Partially Linear Additive Model](https://link.springer.com/article/10.1007/s11704-023-2662-3)

Liangxuan Zhu, Han Li*, **Xuelin Zhang**, Lingjuan Wu, Hong Chen. 

**Frontiers of Computer Science 2023 [J]**

- This paper proposes a Neural  Partially  Linear  Additive  Model  (NPLAM),  which automatically  distinguishes  insignificant,  linear,  and  nonlinear features  in  neural  networks, which can realize model-level interpretability.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[7] AAAI 2023 [ccf-A]</div><img src='images/aaai23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Stepdown SLOPE for Controlled Feature Selection](https://ojs.aaai.org/index.php/AAAI/article/view/26050)

Jingxuan Liang, **Xuelin Zhang**, Hong Chen*, Weifu Li, Xin Tang. 

**Association for the Advancement of Artificial Intelligence 2023 [C] (Oral)**

- This paper goes beyond the previous concern of Sorted L-One Penalized Estimation (SLOPE) limited to the false discovery rate (FDR) control by considering the stepdown-based SLOPE in order to control the probability of k or more false rejections (k-FWER) and the false discovery proportion (FDP). The codes are shared at: [https://github.com/zxlml/SLOPE](https://github.com/zxlml/SLOPE)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[6] APIN 2023 [sci-2]</div><img src='images/apin23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Robust variable structure discovery based on tilted empirical risk minimization](https://dl.acm.org/doi/abs/10.1007/s10489-022-04409-z)

**Xuelin Zhang**, Yingjie Wang, Liangxuan Zhu, Hong Chen, Han Li, Lingjuan Wu*. 

**Applied Intelligence 2023 [J]**

- In this paper, we propose a new robust variable structure discovery method for group lasso based on a convergent bilevel optimization framework, where the robust tilted empirical risk minimization is adopted. The implementation codes can be found at: [https://github.com/zhangxuelincode/demoTERMGL](https://github.com/zhangxuelincode/demoTERMGL)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[5] ICCCS 2022</div><img src='images/icccs22.png' alt="sym" width="100%"></div></div>
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

[Towards Precise and Explainable Hardware Trojan Localization at LUT Level](https://ieeexplore.ieee.org/document/10833822)

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

- In this work, we propose a novel hardware Trojan detection method based on graph neural networks (GNNs) targeting FPGA netlist. We leverage the rich explicit structural features and behavioral characteristics at LUT, which offers an ideal abstraction level and granularity for Trojan detection. A GNN model with optimized class-balanced focal loss is trained for automated Trojan feature extraction and classification. Model implementation is available at [https://github.com/zxlml/XGNN_HT_Detection](https://github.com/zxlml/XGNN_HT_Detection)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[1] HOST 2022</div><img src='images/host22.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Hardware Trojan Detection at LUT: Where Structural Features Meet Behavioral Characteristics](https://ieeexplore.ieee.org/document/9840276)

Lingjuan Wu, **Xuelin Zhang**, Siyi Wang, Wei Hu. 

**International Symposium on Hardware Oriented Security and Trust 2022 [C]**

- This work proposes a novel hardware Trojan detection method that leverages static structural features and behavioral characteristics in field programmable gate array (FPGA) netlists. Mapping of hardware design sources to look-up-table (LUT) networks makes these features explicit, allowing automated feature extraction and further effective Trojan detection through machine learning. The implemented codes are available at: [https://github.com/zxlml/HOST22](https://github.com/zxlml/HOST22)
</div>
</div>



# 🎖️ Activities and Honors
- *2025.4:* A report is made at [**HBSIAM 2025**.](https://aisle.hzau.edu.cn/info/1097/2476.htm)
- *2024.12:* A report is made at [**CCF Wuhan 2024 Annual Conference and 8th Outstanding Doctoral Student Academic Forum**.](https://www.ccf.org.cn/Chapters/Chapters/Wuhan/hyhdzxdt/2024-12-23/836269.shtml)
- *2024.11:* [**China Doctoral National Scholarship**.](https://aisle.hzau.edu.cn/info/1097/2216.htm)
- *2024.11:* A poster is presented at [**CSIAM 2024**.](https://aisle.hzau.edu.cn/info/1097/2201.htm)
- *2024.8:* A report is made at Jeju, South Korea. [**Conference of IJCAI-2024**.](https://aisle.hzau.edu.cn/info/1097/1911.htm)
- *2024.4:* A report is made at [**HBSIAM 2024**.](https://aisle.hzau.edu.cn/info/1097/1901.htm)

# 🛠️ Authorized Patents
- *2024.06:* Hong Chen, **Xuelin Zhang**, Weifu Li, Feng Zheng. [**CN114580299A**.](https://patents.google.com/patent/CN114580299A/zh)

# 💬 Academic Services

- Conference reviewer for ICLR, ICML, NeurIPS, IJCNN, ACML.

- Journal reviewer for Expert Systems With Applications, Molecular & Cellular Biomechanics, Journal of Infrastructure, Policy and Development, International Journal of Applied and Computational Mathematics.
  
# 🌏 Visit Counter
<a href="https://info.flagcounter.com/LoqT"><img src="https://s05.flagcounter.com/countxl/LoqT/bg_FFFFFF/txt_061414/border_CC4BBB/columns_8/maxflags_12/viewers_0/labels_1/pageviews_1/flags_0/percent_0/" alt="Flag Counter" border="0"></a>
