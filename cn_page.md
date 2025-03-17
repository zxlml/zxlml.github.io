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

# 👨‍🎓 教育经历

- 本科(2016-2020)就读于中国农业大学理科试验班(信息科学)，研究生(2020--)就读于华中农业大学信息学院.
- 硕士期间（2020-2022）在[武玲娟教授](https://www.researchgate.net/profile/Lingjuan-Wu)的指导下研究**可解释稳健机器学习**算法设计以及在**硬件安全领域**的应用.
- 博士期间（2022年转博后-至今）在[陈洪教授](https://chenhongml.github.io/)的指导下研究**可解释稳健优化算法设计**与**算法统计理论分析**.
- 预计于2026年中旬毕业.

# 🔬 研究方向

我的研究方向主要包括：

- 可解释/鲁棒的机器学习算法设计（鲁棒度量函数设计、稀疏可加建模）

- 传统算法与大模型的统计性质分析（收敛、泛化、一致性、可控性保障）

- 机器学习算法应用（基于 自然语言与电路拓扑结构 等策略的硬件安全检测）

推荐阅读论文：[可解释人工智能（XAI）](https://arxiv.org/abs/2501.09967), [鲁棒机器学习(Robustness)](https://ieeexplore.ieee.org/document/10571602).

如果对我的研究方向感兴趣, 或者有推荐的(实习/正式)Offer (优先Base 武汉/南昌) 😃, 烦请联系: xlinml@163.com

# 🔥 新闻

- *2025.01*: &nbsp;🎉🎉  合作论文被[**TCAD**](https://ieeexplore.ieee.org/document/10833822)(**体系结构领域CCF-A类**期刊)接收. 

- *2024.12*: &nbsp;🎉🎉 参加[**2024年湖北省工业与应用数学学会优秀研究生论文评选**.](http://hbsiam.whu.edu.cn/a/tongzhigonggao/86.html)

- *2024.12*: &nbsp;🎉🎉  参加[**CCF武汉2024年会暨第八届优秀博士论坛**](https://www.ccf.org.cn/Member_Activities/2024-12-23/836271.shtml)并作口头汇报.

- *2024.11*: &nbsp;🎉🎉  荣获 [**博士国家奖学金**](https://aisle.hzau.edu.cn/info/1097/2216.htm).

# 📝 机器学习方向论文

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[8] ICDM 2024 [ccf-B]</div><img src='images/ICDM2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Generalized Sparse Additive Model with Unknown Link Function](https://ieeexplore.ieee.org/abstract/document/10884346)

[Peipei Yuan](https://www.researchgate.net/profile/Peipei-Yuan-3), [Xinge You*](https://scholar.google.com/citations?user=v7bRZX8AAAAJ&hl=en), [Hong Chen](https://chenhongml.github.io/), **Xuelin Zhang**, and [Qinmu Peng](https://scholar.google.com/citations?user=frL8yhIAAAAJ&hl=en). 

**IEEE International Conference on Data Mining 2024 [C]**

- 在这项工作中，我们提出了一种新型的广义加性模型，该模型具有一个通过双层方案自动学习的灵活链接函数.所提出的模型能够进行非线性逼近、隐藏交互和特征选择，同时也享有算法收敛的理论保证.
- 广义可加模型，就应该多考虑一个灵活的外层映射函数嘛！ 这不，我们就用双层建模学出来.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[7] ESWA 2024 [sci-1 Top]</div><img src='images/eswa24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Error Density-dependent Empirical Risk Minimization](https://www.sciencedirect.com/science/article/pii/S0957417424011989)

[Hong Chen*](https://chenhongml.github.io/), **Xuelin Zhang**, [Tieliang Gong](https://gong-tl.github.io/), [Bin Gu](https://scholar.google.com/citations?user=Vo8OgCgAAAAJ), [Feng Zheng](https://scholar.google.com/citations?user=PcmyXHMAAAAJ&hl=en). 

**Expert Systems With Applications 2024 [J]**

- 这篇论文缓解了依赖误差值的稳健学习准则的局限性，并提出了误差密度依赖的经验风险最小化框架，用于对抗异常数据的稳健回归与分类.我们的方法的有效性通过充分的实验评估得到了验证.
- 这个原创的损失经历了漫长的打磨，从2021年就一直在不断地从实验做补充.尽管花了三年的时间反复揉搓，仍觉得它还是个需要从理论上进行打磨的半成品.
- 有幸读到了[林华珍教授](https://csr.swufe.edu.cn/info/1131/1501.htm)发表在[**JASA'24**上的最新工作](https://www.tandfonline.com/doi/full/10.1080/01621459.2024.2412364)，在理论上给了一些新的启发，并且佐证了我们这一建模思路的合理性、科学性.
- 实现代码： [github.com/zhangxuelincode/EDERM](https://github.com/zhangxuelincode/EDERM)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[6] IJCAI 2024 [ccf-A]</div><img src='images/ijcai24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Fine-grained Analysis of Stability and Generalization for Stochastic Bilevel Optimization](https://www.ijcai.org/proceedings/2024/609)

**Xuelin Zhang**, Hong Chen*, Bin Gu, Tieliang Gong, Feng Zheng. 

**International Joint Conference on Artificial Intelligence 2024 [C] (Oral)**

- 在这篇论文中，我们基于（平均参数）算法稳定性技术，对一阶基于梯度的双层优化方法进行了系统的泛化分析.
- 算法稳定性大法好，泛化分析中可以体现出优化的细节（迭代次数，算法设计，学习率，目标函数的光滑性/凸性等）.
- 实现代码：[github.com/zhangxuelincode/BilevelOptimization](https://github.com/zhangxuelincode/BilevelOptimization)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[5] IJCNN 2024 [ccf-C]</div><img src='images/ijcnn24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Improved Concentration Bound for CVaR](https://ieeexplore.ieee.org/abstract/document/10650860)

[Peng Sima](https://www.semanticscholar.org/author/Peng-Sima/2320582518), [Hao Deng*](https://scholar.google.com/citations?user=94-PGUAAAAAJ&hl=en), **Xuelin Zhang**, Hong Chen. 

**International Joint Conference on Neural Networks 2024 [C]**

- 这篇论文介绍了一种新颖的估计器，该估计器依赖于风险价值（Value at Risk，简称VaR）的估计，并研究了在独立场景中的集中不等式，其中底层分布是次高斯（sub-Gaussian）、次指数（sub-exponential）或重尾（heavy-tailed）的.我们推导出的不等式是双边的，表现出指数衰减，并且不局限于有界场景.
- VaR和CVaR其实都是经济学里的常见度量，同时也在机器学习得到了广泛应用.这篇工作也是从复杂情景下，推导了无界目标的上下界.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[4] FCS 2023 [ccf-B]</div><img src='images/fcs23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Neural Partially Linear Additive Model](https://link.springer.com/article/10.1007/s11704-023-2662-3)

[Liangxuan Zhu](https://dl.acm.org/profile/99660968082), [Han Li*](https://www.researchgate.net/profile/Han-Li-115), **Xuelin Zhang**, [Lingjuan Wu](https://www.researchgate.net/profile/Lingjuan-Wu), Hong Chen. 

**Frontiers of Computer Science 2023 [J]**

- 这篇论文提出了一种神经部分线性加性模型，该模型能够在神经网络中自动区分不显著、线性和非线性特征，从而实现模型级别的可解释性.
- 神经可加模型很牛的！  诺奖得主 Hinton 也做过这个方向 （[NeurIPS 2021](https://papers.nips.cc/paper/2021/hash/251bd0442dfcc53b5a761e050f8022b8-Abstract.html)）！ 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[3] AAAI 2023 [ccf-A]</div><img src='images/aaai23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Stepdown SLOPE for Controlled Feature Selection](https://ojs.aaai.org/index.php/AAAI/article/view/26050)

Jingxuan Liang, **Xuelin Zhang**, Hong Chen*, [Weifu Li](https://www.researchgate.net/profile/Weifu-Li), [Xin Tang](https://ieeexplore.ieee.org/author/37088421138). 

**Association for the Advancement of Artificial Intelligence 2023 [C] (Oral)**

- 这篇论文打破了以往对排序L-One惩罚估计（Sorted L-One Penalized Estimation，简称SLOPE）的局限，经典SLOPE仅限于控制假发现率（False Discovery Rate，简称FDR）.论文考虑了基于逐步下降的SLOPE，以控制k个或更多假拒绝的概率（k-FWER）和假发现比例（False Discovery Proportion，简称FDP）.这就实现了特征选择任务中的错选率可控性质!
- 其实我们后来还考虑了group情境下的gSLOPE算法设计与理论保障.
- 实现代码： [github.com/zxlml/SLOPE](https://github.com/zxlml/SLOPE)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[2] APIN 2023 [sci-2]</div><img src='images/apin23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Robust variable structure discovery based on tilted empirical risk minimization](https://dl.acm.org/doi/abs/10.1007/s10489-022-04409-z)

**Xuelin Zhang**, [Yingjie Wang](https://scholar.google.com/citations?user=jPJBUnoAAAAJ&hl=en), Liangxuan Zhu, Hong Chen, Han Li, Lingjuan Wu*. 

**Applied Intelligence 2023 [J]**

- 在这篇论文中，我们提出了一种新的基于收敛双层优化框架的鲁棒变量结构发现方法，用于基于组套索（group lasso），其中采用了鲁棒倾斜的经验风险最小化.
- 鲁棒性质是可以度量的喔，本文尝试分析了模型的击穿点,也就是能够忍受的最多的异常数据.
- 能够从高维数据中挖掘协同关系的组结构，挺有意思.不过做的有些粗糙，只考虑到了非重叠的分组结构.重叠情境比较复杂，这也是最近的考虑方向.
- 实现代码: [github.com/zhangxuelincode/demoTERMGL](https://github.com/zhangxuelincode/demoTERMGL)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[1] ICCCS 2022</div><img src='images/icccs22.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Robustness of classifier to adversarial examples under imbalanced data](https://ieeexplore.ieee.org/document/9846074)

Wenqian Zhao, Han Li, Lingjuan Wu*, Liangxuan Zhu, **Xuelin Zhang**, [Yizhi Zhao](https://www.researchgate.net/profile/Yizhi-Zhao-2). 

**International Conference on Computer and Communication Systems 2022 [C]**

- 在这篇论文中，我们提供了一个理论框架，用于从AUC（ROC曲线下面积）的角度分析分类器对AE（Adversarial Examples，对抗性样本）在不平衡数据集下的鲁棒性，并推导出一个可解释的上限.
</div>
</div>


# 📝 硬件安全方向论文

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[4] TCAD 2025 [ccf-A]</div><img src='images/tcad2025.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Precise and Explainable Hardware Trojan Localization at LUT Level](https://ieeexplore.ieee.org/document/10833822)

Hao Su, [Wei Hu](https://scholar.google.com.hk/citations?user=1kXI0YEAAAAJ&hl=en), **Xuelin Zhang**, [Dan Zhu](https://scholar.google.com/citations?user=vxiSH8kAAAAJ), Lingjuan Wu*. 

**IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems 2025 [J]**

- 提出的方法是旨在提取查找表（LUT）级别的丰富结构和行为特征，以训练一个可解释的图神经网络（GNN）模型，用于对FPGA网表中的设计节点进行分类，并识别感染木马的节点.
- 在跨年的这个夜晚，能够看到顶刊接收信息蛮开心的.希望2025年对我好一点 🙏 尤其是善良的编辑，领域主席和审稿人们.
- 实现代码: [github.com/zhangxuelincode/node_label](https://github.com/zhangxuelincode/node_label)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[3] ITC-Asia 2024 [ccf-C]</div><img src='images/itc24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Pinpointing Hardware Trojans Through Semantic Feature Extraction and Natural Language Processing](https://ieeexplore.ieee.org/abstract/document/10661348)

Yichen Li, Wei Hu, Hao Su, **Xuelin Zhang**, Yizhi Zhao, Lingjuan Wu*. 

**International Test Conference in Asia 2024 [C]**

- 在这项工作中，我们提出了一种新颖的RTL（寄存器传输级）硬件木马检测方法.我们的方法涉及将硬件设计转换为CDFG（控制数据流图），然后进行路径提取和分割.
- 这篇工作算是NLP技术在硬件木马检测任务上，比较早的应用.我们首次在RTL仿真阶段对代码直接进行建模，就可以高精度地检测出木马设计，无需进一步仿真或者流片.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[2] ICCAD 2023 [ccf-B]</div><img src='images/iccad23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Automated Hardware Trojan Detection at LUT Using Explainable Graph Neural Networks](https://ieeexplore.ieee.org/document/10323915)

Lingjuan Wu, Hao Su, **Xuelin Zhang**, [Yu Tai](https://ieeexplore.ieee.org/author/37086110235), Han Li, Wei Hu*. 

**International Conference on Computer-Aided Design 2023 [C]**

- 在这项工作中，我们提出了一种基于图神经网络（GNNs）的新型硬件木马检测方法，针对FPGA网表.我们利用LUT级别的丰富显式结构特征和行为特征，这为木马检测提供了一个理想的抽象层次和粒度.通过训练一个优化的类别平衡焦点损失的GNN模型，实现了自动化的木马特征提取和分类.
- 我们引入了一些很有意思的（基于格兰杰因果思想）可解释策略以及处理非均衡问题的策略，这也是我们初步尝试GNN的应用.
- 实现代码：[github.com/zxlml/XGNN_HT_Detection](https://github.com/zxlml/XGNN_HT_Detection)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">[1] HOST 2022</div><img src='images/host22.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Hardware Trojan Detection at LUT: Where Structural Features Meet Behavioral Characteristics](https://ieeexplore.ieee.org/document/9840276)

Lingjuan Wu, **Xuelin Zhang**, [Siyi Wang](https://scholar.google.com/citations?user=xZ6Hd2IAAAAJ), Wei Hu*. 

**International Symposium on Hardware Oriented Security and Trust 2022 [C]**

- 这项工作提出了一种新颖的硬件木马检测方法，该方法利用现场可编程门阵列（FPGA）网表中的静态结构特征和行为特征.将硬件设计源映射到查找表（LUT）网络使得这些特征变得明确，允许通过机器学习自动化特征提取，并进一步有效地检测木马.
- 这篇论文我们引入了混合高效重采样（过采样与欠采样结合）来处理非均衡问题，并在实验中得到了理想的性能提升.
- 😞 遗憾的是，尽管HOST会议在这个领域有着一定的知名度，但是ccf-C都没进.
- 实现代码：[github.com/zxlml/HOST22](https://github.com/zxlml/HOST22)
</div>
</div>


# 📝   审稿中工作

- **独立一作**
- Meta Additive Model: Learning Theory Analysis and Applications. (Under Review)
- S2MAM: Semi-supervised Meta Additive Model for Robust Estimation and Variable Selection. (Under Review)
- Robust Manifold Learning via Bilevel CycleGAN. (Under Review)
- **共同一作**
- Pairwise Generalized Importance Weighting for Metric Learning under Distribution Shift. (Second Review)
- Controlled Feature Interaction Selection for Deep Sparse Networks. (Submitting)
- Fine-grained Analysis on the Generalization of Multimodal Metric Learning. (Submitting)
- 基于YOLOv11-FS模型的柑橘花粉活力率检测. (Under Review)
- **其他合作**
- From Conflicts to Convergence: A Zeroth-order Method for Multi-Objective Learning. (Under Review)
- On the Generalization Ability of Next-Token-Prediction Pretraining. (Under Review)
- HDME: Hallucination Detection in LLMs Using Manifold Embedding. (Under Review)
- Explainable Hardware Trojan Detection and Localization in FPGA Netlists. (Major Revision)
<div style="display:none">
- Robust Hardware Trojan Detection at RTL Through Adversarial Training. (Submitting)
- Multi-objective Graph Neural Network for Robust and Interpretable Hardware Trojan Detection. (Submitting)
</div>



# 🎖️ 以往活动与奖项
- *2024.12:* 受邀汇报： [**2024年湖北省工业与应用数学学会优秀研究生论文评选**.](http://hbsiam.whu.edu.cn/a/tongzhigonggao/86.html)
- *2024.12:* 受邀汇报： [**CCF武汉2024年会暨第八届优秀博士生学术风采展示论坛**.](https://www.ccf.org.cn/Chapters/Chapters/Wuhan/hyhdzxdt/2024-12-23/836269.shtml)
- *2024.11:* 荣获 [2024年度**博士国家奖学金**.](https://aisle.hzau.edu.cn/info/1097/2216.htm)
- *2024.11:* 荣获 [2024年度**三好研究生**.](https://yjs.hzau.edu.cn/info/1192/10321.htm)
- *2024.11:* 海报参展： 江苏南京召开的[**第二十二届中国工业与应用数学学会年会**.](https://aisle.hzau.edu.cn/info/1097/2201.htm)
- *2024.8:* 受邀汇报： 韩国济州岛召开的[**IJCAI-2024国际人工智能会议口头汇报与海报展示**.](https://aisle.hzau.edu.cn/info/1097/1911.htm)
- *2024.6 - 2024.12:* 前往[**中山大学深圳校区交流学习**.](https://scst.sysu.edu.cn/about/about01/index.htm)
- *2024.5:* 荣获 2024年度党支部**优秀党员**.
- *2024.4:* 受邀汇报： 湖北荆州召开的[**湖北省工业与应用数学学会2024年学术交流大会**](https://aisle.hzau.edu.cn/info/1097/1901.htm)[**及颁奖仪式**.](http://hbsiam.whu.edu.cn/a/shouyehuandeng/85.html)
- *2023.11:* 荣获 **华中农业大学信息学院“电子信息研究生论坛”一等奖**.
- *2023.8:* 参会 浙江杭州召开的[**数据科学前沿国际研讨会**.](http://cds.zju.edu.cn/a/hyyg/3142.html)
- *2023.7:* 录取 **武汉大学国家天元数学中部中心[《高性能计算短期课程》.](https://tmcc.whu.edu.cn/info/1051/1571.htm)**
- *2023.7:* 参会 贵州贵阳召开的[**第四届全国大数据与人工智能科学大会**.](http://bda.pku.edu.cn/info/1003/2402.htm)
- *2023.3:* 参会 海南海口召开的[**第十一届全国空间环境及其应用专题研讨会**.](http://www.nssc.cas.cn/library/cyzy/rese/202304/t20230420_6742010.html)
- *2022.5:* 获选 [华中农业大学第十七次**研究生代表大会信息学院2022级代表（1人）**.](https://coi.hzau.edu.cn/info/1027/9450.htm)
- *2022.3:* 担任 2021年秋季学期本科生课程《数字逻辑与EDA技术》助教.
- *2021.9:* 担任 2021年秋季学期本科生课程《嵌入式系统》助教，并获评[**“课程思政”示范建设项目**.](https://coi.hzau.edu.cn/info/1015/9076.htm)
- *2021.3:* 担任 2021年春季学期本科生课程《C++高级程序设计实验》助教.
- *2018.7:* 荣获 [“民生杯”大学生数学建模竞赛三等奖](http://sci.cau.edu.cn/art/2018/7/6/art_3474_578123.html)
- *2017.8:* 担任 中国农业大学“新丝路暑期实践支队”的微信公众号负责人，历史回顾 [**1-启程**](https://mp.weixin.qq.com/s/Xt4DKLweN3KdBmz-v9CSFA), [**2-征程**](https://mp.weixin.qq.com/s/XePZcWS8f5cHk0K4J41HyQ), [**3-马尾区**](https://mp.weixin.qq.com/s/P3YMbiHi9Pk3ZmN3f-JpyQ), [**4-吐槽**](https://mp.weixin.qq.com/s/cDJHORkRZJoFeH4KhkMDBA), [**5-船政文化**](https://mp.weixin.qq.com/s/qZO5UI575KtJBSf6yhQbdg), [**6-塔兜村**](https://mp.weixin.qq.com/s/jPcF2tUUb3Y76YPHAhrqOA).
- *2017.4:* 担任 [北京国际长跑节-春季半马志愿者](http://ciee.cau.edu.cn/art/2017/5/10/art_26711_514437.html).


# 🛠️ 专利
- *2024.06:*  [**一种混凝土抗压能力预测方法、装置、设备及存储介质(已授权)**](https://patents.google.com/patent/CN114580299A/zh).
- *2024.06:*  **一种基于FPGA网表特征子图的硬件木马检测方法(实质审查中)**.
- *2024.10:*  **一种基于语义特征自动提取的硬件木马检测方法(实质审查中)**.
- *2023.01:*  **一种基于图神经网络的硬件木马自动检测方法(实质审查中)**.


# 💬 学术服务

- 会议审稿人: [ICLR](https://iclr.cc/), [ICML](https://icml.cc/), [IJCNN](https://2025.ijcnn.org/).

- 期刊审稿人: [Expert Systems With Applications](https://www.sciencedirect.com/journal/expert-systems-with-applications), [Molecular & Cellular Biomechanics](https://www.techscience.com/journal/mcb), [Journal of Infrastructure, Policy and Development](https://systems.enpress-publisher.com/index.php/jipd).
  
# 🌏 浏览记录
<a href="https://info.flagcounter.com/LoqT"><img src="https://s05.flagcounter.com/countxl/LoqT/bg_FFFFFF/txt_061414/border_CC4BBB/columns_8/maxflags_12/viewers_0/labels_1/pageviews_1/flags_0/percent_0/" alt="Flag Counter" border="0"></a>
