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

I am a Ph.D. candidate at College of Informatics, Huazhong Agricultural University, supervised by [Prof. Hong Chen](https://chenhongml.github.io/). Previously, I was persuing the M.S. degree with assistance of [Prof. Lingjuan Wu](https://www.researchgate.net/profile/Lingjuan-Wu). I received the B.S. degree in Engineering from China Agricultural University in 2019. Recently, I have been conducting academic exchanges at Sun Yat-sen University.

My research interests lie in the areas of optimization and learning theory, with emphasis on the following topics:

- Automatic machine learning (e.g., Hyperparameter Optimization)

- Robust/Interpretable machine learning (e.g., Robust Metric, Sparse/Neural additive models)

- Applications on hardware Trojan detection (e.g., FPGA/Gate/LUT synthetic levels)

If you are interested or have any question on my works, please feel free to contact me: zhangxuelin@webmail.hzau.edu.cn

# 🔥 News
- *2024.09*: &nbsp;🎉🎉  New Acceptance: Peipei Yuan, Xinge You, Hong Chen, **Xuelin Zhang**, and Qinmu Peng. Generalized Sparse Additive Model with Unknown Link Function. ICDM 2024.

- *2024.06*: &nbsp;🎉🎉  New authorized patent: Hong Chen, **Xuelin Zhang**, Weifu Li, Feng Zheng. CN114580299A.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[11] ICDM 2024 </div><img src='images/ICDM2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Generalized Sparse Additive Model with Unknown Link Function](https://zxlml.github.io/)

Peipei Yuan, Xinge You*, Hong Chen, **Xuelin Zhang**, and Qinmu Peng. 

**IEEE International Conference on Data Mining 2024 [C]**

- In this work, we propose a novel generalized additive model with a flexible link function automatically learned by a bilevel scheme. The proposed model is capable of nonlinear approximation, hidden interaction and feature selection, which also enjoys the theoretical guarantee of algorithmic convergence.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[10] ITC-Asia 2024</div><img src='images/itc24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Pinpointing Hardware Trojans Through Semantic Feature Extraction and Natural Language Processing](https://ieeexplore.ieee.org/abstract/document/10661348)

Yichen Li, Wei Hu, Hao Su, **Xuelin Zhang**, Yizhi Zhao, Lingjuan Wu*. 

**International Test Conference in Asia 2024 [C]**

- In this work, we propose a novel hardware Trojan detection method at RTL. Our approach involves the transformation of hardware design into CDFG, followed by path extraction and segmentation. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[9] ESWA 2024</div><img src='images/eswa24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Error Density-dependent Empirical Risk Minimization](https://www.sciencedirect.com/science/article/pii/S0957417424011989)

Hong Chen*, **Xuelin Zhang**, Tieliang Gong, Bin Gu, Feng Zheng. 

**Expert Systems With Applications 2024 [J]**

- This paper goes beyond the limitation of error value-dependent learning criterion and proposes the EDERM framework for robust regression against atypical data. The effectiveness of our method is validated by sufficient empirical evaluations. The implementation codes can be found at: https://github.com/zhangxuelincode/EDERM
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[8] IJCAI 2024</div><img src='images/ijcai24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Fine-grained Analysis of Stability and Generalization for Stochastic Bilevel Optimization](https://www.ijcai.org/proceedings/2024/0609.pdf)

**Xuelin Zhang**, Hong Chen*, Bin Gu, Tieliang Gong, Feng Zheng. 

**International Joint Conference on Artificial Intelligence 2024 [C] (Oral)**

- In this paper, we provide a systematical generalization analysis of the first-order gradient-based bilevel optimization methods, based on the (on-average argument) algorithmic stability technique. The verification codes are provided at: https://github.com/zhangxuelincode/BilevelOptimization
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[7] IJCNN 2024</div><img src='images/ijcnn24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Improved Concentration Bound for CVaR](https://ieeexplore.ieee.org/abstract/document/10650860)

Peng Sima, Hao Deng*, **Xuelin Zhang**, Hong Chen. 

**International Joint Conference on Neural Networks 2024 [C]**

- This paper introduces a novel estimator that relies on an estimator of Value at Risk (VaR) and investigates the concentration inequalities in independent scenarios where the underlying distributions are sub-Gaussian, sub-exponential, or heavy-tailed, where the inequalities we derive are bilateral, exhibit exponential decay, and are not confined to bounded scenarios.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[6] ICCAD 2023</div><img src='images/iccad23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Automated Hardware Trojan Detection at LUT Using Explainable Graph Neural Networks](https://ieeexplore.ieee.org/document/10323915)

Lingjuan Wu, Hao Su, **Xuelin Zhang**, Yu Tai, Han Li, Wei Hu*. 

**International Conference on Computer-Aided Design 2023 [C]**

- In this work, we propose a novel hardware Trojan detection method based on graph neural networks (GNNs) targeting FPGA netlist. We leverage the rich explicit structural features and behavioral characteristics at LUT, which offers an ideal abstraction level and granularity for Trojan detection. A GNN model with optimized class-balanced focal loss is trained for automated Trojan feature extraction and classification. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[5] FCS 2023</div><img src='images/fcs23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Neural Partially Linear Additive Model](https://link.springer.com/article/10.1007/s11704-023-2662-3)

Liangxuan Zhu, Han Li*, **Xuelin Zhang**, Lingjuan Wu, Hong Chen. 

**Frontiers of Computer Science 2023 [J]**

- This paper proposes a Neural  Partially  Linear  Additive  Model  (NPLAM),  which automatically  distinguishes  insignificant,  linear,  and  nonlinear features  in  neural  networks, which can realize model-level interpretability.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[4] AAAI 2023</div><img src='images/aaai23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Stepdown SLOPE for Controlled Feature Selection](https://ojs.aaai.org/index.php/AAAI/article/view/26050)

Jingxuan Liang, **Xuelin Zhang**, Hong Chen*, Weifu Li, Xin Tang. 

**Association for the Advancement of Artificial Intelligence 2023 [C] (Oral)**

- This paper goes beyond the previous concern of Sorted L-One Penalized Estimation (SLOPE) limited to the false discovery rate (FDR) control by considering the stepdown-based SLOPE in order to control the probability of k or more false rejections (k-FWER) and the false discovery proportion (FDP).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[3] APIN 2023</div><img src='images/apin23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Robust variable structure discovery based on tilted empirical risk minimization](https://dl.acm.org/doi/abs/10.1007/s10489-022-04409-z)

**Xuelin Zhang**, Yingjie Wang, Liangxuan Zhu, Hong Chen, Han Li, Lingjuan Wu*. 

**Applied Intelligence 2023 [J]**

- In this paper, we propose a new robust variable structure discovery method for group lasso based on a convergent bilevel optimization framework, where the robust tilted empirical risk minimization is adopted. The implementation codes can be found at: https://github.com/zhangxuelincode/demoTERMGL
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[2] HOST 2022</div><img src='images/host22.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Hardware Trojan Detection at LUT: Where Structural Features Meet Behavioral Characteristics](https://ieeexplore.ieee.org/document/9840276)

Lingjuan Wu, **Xuelin Zhang**, Siyi Wang, Wei Hu*. 

**International Symposium on Hardware Oriented Security and Trust 2022 [C]**

- This work proposes a novel hardware Trojan detection method that leverages static structural features and behavioral characteristics in field programmable gate array (FPGA) netlists. Mapping of hardware design sources to look-up-table (LUT) networks makes these features explicit, allowing automated feature extraction and further effective Trojan detection through machine learning.
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

# 🎖 Honors
- *2024.11:* China National Scholarship

# 🔖 Authorized Patents
- *2024.06:* Hong Chen, **Xuelin Zhang**, Weifu Li, Feng Zheng. CN114580299A.



# 💬 Academic Services

[^_^]: #  - Journals reviewer for IEEE Transactions on Pattern Analysis and Machine Intelligence, IEEE Transactions on Neural Networks and Learning System, Pattern Recognition, Neural Networks, IEEE Transactions on Circuits and Systems II: Express Briefs, Journal of Complexity, Journal of Mathematical Analysis and Applications, Artificial Intelligence in Medicine, Applied Mathematics Letters, Neural Processing Letters, Information Sciences, Neurocomputing, International Journal of Computer Mathematics, etc.
  
- Conference reviewer for ICLR, ICML.

- Journal reviewer for Expert Systems With Applications, Journal of Infrastructure, Policy and Development.
  
# 💻 Visitor Maps
<script type="text/javascript" src="//rf.revolvermaps.com/0/0/6.js?i=54e0ojatafc&amp;m=7&amp;c=e63100&amp;cr1=ffffff&amp;f=arial&amp;l=0&amp;bv=90&amp;lx=-420&amp;ly=420&amp;hi=20&amp;he=7&amp;hc=a8ddff&amp;rs=80" async="async"></script>
