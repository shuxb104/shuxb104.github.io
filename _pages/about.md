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


<p style="text-align: justify;font-family: Roboto;">
I am currently a Professor in 
<a href="https://imag-njust.net/">Intelligent Media Analysis Group      (IMAG)</a>, at School of Computer Science and Engineering, Nanjing University of Science and Technology, China. I received the Ph.D. degree from School of Computer Science and Engineering, Nanjing University of Science and Technology, China, under the supervisor Prof. Jinhui Tang, a leader professor of Intelligent Media Analysis Group (IMAG). Previously, I am also an visiting scholar supervised by Prof. Shuicheng Yan in <a href="http://www.lv-nus.org/"> Learning and Vision Research Group</a> at the Department of Electrical and Computer Engineering, National University of Singapore. I am and the CCF Senior Member, and ACM Member, and IEEE Senior Member.
</p>
<span class='anchor' id='r-interests'></span>




# <font color="#2B6ADD" > Researh Interests </font>
<p style="font-family: Roboto;">
Human behavior computing, Video understanding, Action analysis, and other related human-centric problems in Artificial Intelligence, Computer Vision and Multimedia.</p>
<br>
<font color=Brown>
<i style="font-family: Roboto;">*Positions for Interns/Master/PhD's Programme*</i>
<br>
 <i style="font-family: Roboto;">We are looking for students, who are self-motivated and have a solid foundation in mathematics and programming. Please feel free to drop me an email (shuxb@njust.edu.cn) if you are interested.</i>
</font>

<span class='anchor' id='news'></span>
# <font color="#2B6ADD"> News </font>
- Four papers have been accepted by ICCV 2025.
- One paper "Reliable and Diverse Hierarchical Adapter for Zero-shot Video Classification" has been accepted by IJCAI 2025.
I was invited to serve as an Area Chair for ACM MM 2025.
- Two Papers have been published in TNNLS 2025.
- One paper "Seeing What Matters: Empowering CLIP with Patch Generation-to-Selection" has been accepted by CVPR 2025.
- One paper "Surgical video workflow analysis via visual-language learning" has been accepted by npj Health Systems.
- One paper has been accepted by ICLR 2024.
- Two papers "3D-aware Select, Expand, and Squeeze Token for Aerial Action Recognition", and "Kernel-Aware Graph Prompt Learning for Few-Shot Anomaly Detection" have been accepted by AAAI 2024.
- One paper "DoFIT: Domain-aware Federated Instruction Tuning with Alleviated Catastrophic Forgetting" has been accepted by NeurIPS 2024.
- One paper "DTS-TPT: Dual Temporal-Sync Test-time Prompt Tuning for Zero-shot Activity Recognition" has been accepted by IJCAI 2024.
- Our work GPT4Ego targeting on Unleashing the Potential of Pre-trained Models for Zero-Shot Egocentric Action Recognition was accepted by TMM.
- Our work (Semantic-Disentangled Transformer) was accepted by TIP.


<span class='anchor' id='pub'></span>
# <font color="#2B6ADD"> Selected Publications </font>

<style>
  table {
    border-collapse: collapse;
  }
  table, th, td {
    border-color: transparent;
  }
</style>

<table align="center" border="none">
    <tr>
      <td>
        <img align="left" width="330" height="240" src="../images/Te-LoRA.png"/>
      </td>
      <td>
        <p text-align="left">
        Zhixuan Li, Binqian Xu, <b>Xiangbo Shu*</b>, Jiachao Zhang, Yazhou Yao, Guosen Xie, Jinhui Tang. Tensor-aggregated LoRA in Federated Fine-tuning. IEEE International Conference on Computer Vision (ICCV), 2025.
        </p>
      </td>
    </tr>
    <tr>
      <td>
        <img align="left" width="330" height="240" src="../images/EMP.png"/>
      </td>
      <td>
        <p text-align="left">
        Meiqi Cao, <b>Xiangbo Shu*</b>, Xin jiang, Rui Yan, Yazhou Yao, Jinhui Tang. Exploiting Frequency Dynamics for Enhanced Multimodal Event-based Action Recognition. IEEE International Conference on Computer Vision (ICCV), 2025.
        </p>
      </td>
    </tr>
    <tr>
      <td>
        <img align="left" width="330" height="240" src="../images/cluspro.png"/>
      </td>
      <td>
        <p text-align="left">
        Hongyu Qu, Jianan Wei, <b>Xiangbo Shu*</b>, Wenguan Wang. Learning Clustering-based Prototypes for Compositional Zero-shot Learning. The Thirteenth International Conference on Learning Representations (ICLR), 2025.
        <a href="https://arxiv.org/pdf/2502.06501">[PDF-Link]</a>
        <a href="https://github.com/quhongyu/ClusPro">[Code-Link]</a>
        </p>
      </td>
    </tr>

    <tr>
      <td>
        <img align="left" width="330" height="240" src="../images/DoFIT.png"/>
      </td>
      <td>
        <p text-align="left">
        Binqian Xu, <b>Xiangbo Shu*</b>, Haiyang Mei, Zechen Bai, Basura Fernando, Mike Zheng Shou, Jinhui Tang. DoFIT: Domain-aware Federated Instruction Tuning with Alleviated Catastrophic Forgetting. The Thirty-eighth Annual Conference on Neural Information Processing Systems (NeurIPS), 2024.
        <a href="https://openreview.net/pdf?id=FDfrPugkGU">[PDF-Link]</a>
        <a href="https://github.com/1xbq1/DoFIT">[Code-Link]</a>
        </p>
      </td>
    </tr>
    <tr>
      <td>
        <img align="left" width="330" height="240" src="../images/MAGC.png"/>
      </td>
      <td>
        <p text-align="left">
        <b>Xiangbo Shu</b>, Binqian Xu, Liyan Zhang, Jinhui Tang. Multi-Granularity Anchor-Contrastive Representation Learning for Semi-supervised Skeleton-based Action Recognition. IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2023.
        <b>(ESI Highly Cited Paper)</b>
        <a href="https://github.com/shuxb1s04/shuxb104.github.io/blob/main/paper/MGAC.pdf">[PDF-Link]</a>
        <a href="https://github.com/1xbq1/MAC-Learning">[Code-Link]</a>
        </p>
      </td>
    </tr>
    <tr>
      <td>
        <img align="left" width="330" height="240" src="../images/CCGL.png"/>
      </td>
      <td>
        <p text-align="left">
        Jinhui Tang, <b>Xiangbo Shu*</b>, Rui Yan, and Liyan Zhang. Coherence Constrained Graph LSTM for Group Activity Recognition. IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2022. <b>(ESI Highly Cited Paper)</b>, <b>(ESI Hot Paper)</b> 
        <a href="https://github.com/shuxb104/shuxb104.github.io/blob/main/paper/CCGL.pdf">[PDF-Link]</a>
        </p>
      </td>
    </tr>
    <tr>
      <td>
        <img align="left" width="330" height="240" src="../images/SCRN.png"/>
      </td>
      <td>
        <p text-align="left">
        <b>Xiangbo Shu</b>, Liyan Zhang*, Guo-Jun Qi, Wei Liu, and Jinhui Tang. Spatiotemporal co-attention recurrent neural networks for human-skeleton motion prediction. IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI), 2021. <b>(ESI Highly Cited Paper)</b>
        <a href="https://arxiv.org/pdf/1909.13245.pdf">[PDF-Link]</a>
        </p>
      </td>
    </tr>
    <tr>
      <td>
        <img align="left" width="330" height="240" src="../images/GLIL.png"/>
      </td>
      <td>
        <p text-align="left">
        <b>Xiangbo Shu</b>, Liyan Zhang, Yunlian Sun, and Jinhui Tang. Host-Parasite: Graph LSTM-In-LSTM for Group Activity Recognition. IEEE Transactions on Neural Networks and Learning Systems (TNNLS), 2021. <b>(ESI Highly Cited Paper)</b>
        <a href="https://github.com/shuxb104/shuxb104.github.io/blob/main/paper/HPGL.pdf">[PDF-Link]</a>
        </p>
      </td>
    </tr>
    <tr>
      <td>
        <img align="left" width="330" height="240" src="../images/H-LSCTM.png"/>
      </td>
      <td>
        <p text-align="left">
        <b>Xiangbo Shu</b>, Jinhui Tang, Guo-Jun Qi, Wei Liu, and Jian Yang. Hierarchical Long Short-Term Concurrent Memory for Human Interaction Recognition. IEEE Transacti on Pattern Analysis and Machine Intelligence (TPAMI), 2021. <b>(ESI Highly Cited Paper)</b>, <b>(ESI Hot Paper)</b>
        <a href="https://arxiv.org/pdf/1811.00270.pdf">[PDF-Link]</a>
        </p>
      </td>
    </tr>
    <tr>
      <td>
        <img align="left" width="330" height="240" src="../images/SUGAR.png"/>
      </td>
      <td>
        <p text-align="left">
        Jinhui Tang, <b>Xiangbo Shu</b>, Zechao Li, Yu-Gang Jiang, Qi Tian. Social Anchor-Unit Graph Regularized Tensor Completion for Large-Scale Image Retagging. IEEE Transactions on Pattern Analysis and Machine Intelligenc (TPAMI), 2019.
        <a href="https://arxiv.org/pdf/1804.04397.pdf">[PDF-Link]</a>
        </p>
      </td>
    </tr>
    <tr>
      <td>
        <img align="left" width="330" height="240" src="../images/PAP.png"/>
      </td>
      <td>
        <p text-align="left">
        <b>Xiangbo Shu</b>, Jinhui Tang, Zechao Li, Hanjiang Lai, Liyan Zhang, and Shuicheng Yan. Personalized Age Progression with Bi-level Aging Dictionary Learning. IEEE Transaction on Pattern Analysis and Machine Intelligence (TPAMI), 2018.
        <a href="https://arxiv.org/pdf/1706.01039.pdf">[PDF-Link]</a>
        </p>
      </td>
    </tr>
    <tr>
      <td>
        <img align="left" width="330" height="240" src="../images/CFR.png"/>
      </td>
      <td>
        <p text-align="left">
        <b>Xiangbo Shu</b>, Liyan Zhang, Jinhui Tang, Guo-Sen Xie, Shuicheng Yan. Computational Face Reader. MultiMedia Modeling (MMM), 2016. <b>(Best Student Paper)</b>
        <a href="https://link.springer.com/chapter/10.1007/978-3-319-27671-7_10">[PDF-Link]</a>
        </p>
      </td>
    </tr>
    <tr>
      <td>
        <img align="left" width="330" height="240" src="../images/DTNs.png"/>
      </td>
      <td>
        <p text-align="left">
        <b>Xiangbo Shu</b>, Guo-Jun Qi, Jinhui Tang, Jingdong Wang. Weekly-Shared Deep Transfer Networks for Heterogeneous-Domain Knowledge Propagation. ACM Multimedia (MM), 2015. <b>(Best Paper Candidate)</b>        
        <a href="https://shuxb104.github.io/paper/WSDT.pdf">[PDF-Link]</a>
        </p>
      </td>
    </tr>
    <tr>
      <td>
        <img align="left" width="330" height="240" src="../images/PAPD.png"/>
      </td>
      <td>
        <p text-align="left">
        <b>Xiangbo Shu</b>, Jinhui Tang, Hanjiang Lai, Luoqi Liu, Shuicheng Yan. Personalized Age Progression with Aging Dictionary. IEEE International Conference on Computer Vision (ICCV), 2015.
        <a href="https://openaccess.thecvf.com/content_iccv_2015/papers/Shu_Personalized_Age_Progression_ICCV_2015_paper.pdf">[PDF-Link]</a>
        </p>
      </td>
    </tr>
</table>

For more papers, please kindly refer to [my Google Scholar page](https://scholar.google.com.hk/citations?user=FQfcm5oAAAAJ&hl=zh-CN&oi=ao).






<span class='anchor' id='ha'></span>

# <font color="#2B6ADD"> Honors and Awards </font>
- 2022 Distinguished Reviewer of IEEE TMI
- 2022 Outstanding Reviewer of IEEE TNNLS
- 2022 National Science Fund for Excellent Young Scholars by NSFC (国家优秀青年基金)
- 2021 Jiangsu Province Science Fund for Outstanding Young Scholars (江苏省杰出青年科学基金)
- 2017 CCF-Tencent Open Fund
- 2017 Excellent Doctoral Dissertation of CAAI (中国人工智能学会优博)
- 2017 Excellent Doctoral Dissertation of Jiangsu Province, China
- 2017 Excellent Doctoral Dissertation of Jiangsu Computer Society, China
- 2017 Excellent Doctoral Dissertation of Nanjing University of Science and Technology, China
- 2016 Best Student Paper in MMM 2016
- 2015 Best Paper Runner-up in ACM Multimedia 2015
- 2015 China National Scholarship
- 2015 ACM MM 2015 Travel Grant

<span class='anchor' id='teach'></span>

# <font color="#2B6ADD"> Teaching </font>
- 2019-now, Fundamentals of Multimedia Computing, for Postgraduate.
- 2016-now, Technology of Multimedia Computing, for Undergraduate.
- 2019-now, Introduction to Computers, for Undergraduate.

<span class='anchor' id='team'></span>

# <font color="#2B6ADD"> Team </font>
+ Current Member:
  + Ph.D. Candidates (2020-now): Peng Huang
  + Ph.D. Candidates (2022-now): Guangzhao Dai, <a href="https://1xbq1.github.io/">Binqian Xu</a>
  + Ph.D. Candidates (2023-now): Pengpeng Li, Meiqi Cao, Xingyu Zhu
  + Ph.D. Candidates (2024-now): Zhixuan Li, <a href="https://chengjian-li.github.io/">Chengjian Li</a>, Jinjin Gong, <a href="https://quhongyu.github.io/">Hongyu Qu</a>
  + Ph.D. Candidates (2025-now): Qun Dai, Fei Feng, Yuanqing Wang, Zheng Wang
  + M.S. Candidates (2023-now):  Luying Peng, Yumeng Su
  + M.S. Candidates (2024-now): Chenghao Hu, Yiran Yang, Zheng Yin, Jingyuan Wang, Wenxuan Ge
+ Alumni:
  + Ph.D. Candidates (2013-2020): Mengyin Wang
  + Ph.D. Candidates (2017-2022): Rui Yan
  + M.S. Candidates (2018-2021): Chenglong Shi, Ruipeng Zhang
  + M.S. Candidates (2019-2022): Jing Ding, Boning Li, Qian Jiang, Xiangyu Zhao
  + M.S. Candidates (2021-2023): Jiawen Yang, Yafei Cui
  + M.S. Candidates (2021-2024): Keke Chen, Zhewei Tu, Xiaojing Ge, Longjie Guo
  + M.S. Candidates (2022-2025): Hailiang Gao, Wei Liu, Yunguo Ma
<span class='anchor' id='Service'></span>

# <font color="#2B6ADD"> Academic Service </font>
+ **Associate Editors:**
  - IEEE Transactions on Neural Networks and Learning Systems (TNNLS)
  - IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)
  - Information Sciences
  - Visual Computer
+ **(Senior) Program Committee Member:**
  - Computer Vision and Pattern Recognition (CVPR)
  - International Conference on Computer Vision (ICCV)
  - ACM International Conference on Multimedia (ACM MM) 
  - Neural Information Processing Systems (NeurIPS)
  - AAAI Conference on Artificial Intelligence (AAAI)
  - International Joint Conference on Artificial Intelligence (IJCAI)
  - International Conference on Multimedia and Expo (ICME)
+ **Reviewer for Journals:**
  - IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)
  - International Journal of Computer Vision (IJCV)
  - IEEE Transactions on Image Processing (TIP)
  - IEEE Transactions on Neural Networks and Learning Systems (TNNLS)
  - ACM Transactions on Knowledge Discovery from Data (TKDD)
  - IEEE Transactions on Knowledge and Data Engineering (TKDE)
  - IEEE Transactions on Multimedia (TMM)
  - IEEE Transactions on Medical Imaging (TMI)
  - IEEE Transactions on Information Forensics and Security (TIFS)
  - IEEE Transactions on Big Data (TBD)
  - ACM Transactions on Intelligent Systems and Technology (TIST)
  - ACM Transactions on Multimedia Computing, Communications, and Applications (TOMM)
  - IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)
  - IEEE Transactions on Emerging Topics in Computational Intelligence (TETCI)
  - IEEE Transactions on Visualization and Computer Graphics (TVCG)
  - Pattern Recognition
  - Neural Networks
  - Information Sciences
  - Pattern Analysis and Applications
  - Multimedia Tools and Applications
  - Pattern Recognition Letters
  - Multimedia Systems
  

