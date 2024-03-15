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

I am a Researcher at [Midea Group](https://www.midea.com.cn/), AI Lab. My research interests primarily lie in the areas of model compression, multi-modal, and robotics.

I obtained my bachelor of science from the [University of Toronto](https://www.utoronto.ca/) in 2020, majored in Statistics. 



# 🔥 News
- *2024.03*: We release Mipha, a comprehensive overview of Multimodal Small Language Model. Our Mipha-3B outperforms LLaVA-1.5-13B on multiple benchmarks!
- *2024.02*: &nbsp;🎉🎉 One papers on MLLM + Robotics have been accepted in CVPR 2024
- *2024.02*: &nbsp;🎉🎉 Two papers on MLLM + Robotics have been accepted in ICRA 2024
- *2024.01*: :fire: We release a efficient multi-modal models called [LLaVA-Phi](https://github.com/zhuyiche/llava-phi), building upon Phi-2 and LLaVA.
- *2024.01*: Two papers accepted in AAAI 2024, one paper is presented as Oral (top 1.5%)
- *2023.12*: One paper accepted in ICASSP 2024 as Oral presentation (top 3%)
- *2023.08*: One paper accepted in ECML/PKDD 2024
- *2023.06*: Glad to annouce that our paper [LogAnomaly](https://www.ijcai.org/proceedings/2019/0658.pdf) is now the 4th most cited paper in IJCAI2019

# 📝 Selected Publications 
&dagger; Equal Contributions, &Dagger; Corresponding Author


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/mipha.png' alt="sym" width="300" height="150"></div></div>
<div class='paper-box-text' markdown="1">

Retrieval-Augmented Embodied Agents, **CVPR 2024**

**Yichen Zhu**, Zhicai Ou, Xiaofeng Mou, Jian Tang

***RAG + Robotics with cross-embodiment data.***

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv Jan 2024</div><img src='images/mipha.png' alt="sym" width="300" height="150"></div></div>
<div class='paper-box-text' markdown="1">

[Mipha: A Comprehensive Overhaul of Multimodal Assistant with Small Language Models, **Arxiv 2024**](https://arxiv.org/pdf/2403.06199.pdf)

Minjie Zhu&dagger;, **Yichen Zhu&dagger;**, Xin Liu, Ning Liu, et al.

***Analysis on how to make better multimodal small language models.***

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv Jan 2024</div><img src='images/llava-phi.png' alt="sym" width="300" height="150"></div></div>
<div class='paper-box-text' markdown="1">

[LLaVA-Phi: Efficient Multi-Modal Assistant with Small Language Model, **Arxiv 2024**](https://arxiv.org/pdf/2401.02330.pdf)

**Yichen Zhu**, Minjie Zhu, Zhicai Ou, Xiaofeng Mou, Jian Tang

***An early version of multi-modal small language model under 3B.***

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv Jan 2024</div><img src='images/query-rele.png' alt="sym" width="300" height="150"></div></div>
<div class='paper-box-text' markdown="1">

[Query-Relevant Images Jailbreak Large Multi-Modal Models, **Arxiv 2024**](https://arxiv.org/pdf/2311.17600.pdf)

Xin Liu&dagger;, **Yichen Zhu**&dagger;, Yunshi Lan, Chao Yang, Yu Qiao

***The first study on jailbreaking in large multi-modal models.***

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2024</div><img src='images/icra_rsft.png' alt="sym" width="300" height="150"></div></div>
<div class='paper-box-text' markdown="1">

[Language-Conditioned Robotic Manipulation with Fast and Slow Thinking, **ICRA 2024**](https://arxiv.org/pdf/2401.04181.pdf)

Minjie Zhu&dagger;, **Yichen Zhu**&dagger;, Jinming Li, Junjie Wen, Zhiyuan Xu, Chaomin Shen, Yaxin Peng, Dong Liu, Feifei Feng, Jian Tang

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2024</div><img src='images/icra_oci.png' alt="sym" width="300" height="150"></div></div>
<div class='paper-box-text' markdown="1">

[Object-Centric Instruction Augmentation for Robotic Manipulation, **ICRA 2024**](https://arxiv.org/pdf/2401.04181.pdf)

Junjie Wen&dagger;, **Yichen Zhu**&dagger;, Minjie Zhu, Jinming Li, Zhiyuan Xu, Chaomin Shen, Yaxin Peng, Dong Liu, Feifei Feng, Jian Tang


</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024, <span style="color:red">Oral</span> </div><img src='images/aaai_gail.png' alt="sym" width="300" height="150"></div></div>
<div class='paper-box-text' markdown="1">


[Exploring Gradient Explosion in Generative Adversarial Imitation Learning: A Probabilistic Perspective, **AAAI 2024, Oral (top 1.5%)**](https://arxiv.org/pdf/2312.11214)

Wanying Wang&dagger;, **Yichen Zhu**&dagger;, Yirui Zhou, Chaomin Shen, Jian Tang, Zhiyuan Xu, Yaxin Peng, Yangchun Zhang

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='aaai_early.png' alt="sym" width="300" height="150"></div></div>
<div class='paper-box-text' markdown="1">

[Early Pruning with Self-Distillation for Efficient Model Compression, **AAAI 2024**](https://arxiv.org/pdf/2402.00084.pdf)

Chen Dong&dagger;, Ning Liu&dagger;, **Yichen Zhu**, Fachao Zhang, Dong Liu, Feifei Feng, Jian Tang

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2024</div><img src='images/icassp.png' alt="sym" width="300" height="150"></div></div>
<div class='paper-box-text' markdown="1">

[When Training-Free NAS meets Vision Transformer: A Neural Tangent Kernel Perspective, **ICASSP 2024, Oral (top 3%)**]

Qiqi Zhou, **Yichen Zhu**&Dagger;

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECML/PKDD 2023</div><img src='images/ecml.png' alt="sym" width="300" height="150"></div></div>
<div class='paper-box-text' markdown="1">

[Make a Long Image Short: Adaptive Token Length for Vision Transformers, **ECMl/PKDD 2023**](https://arxiv.org/pdf/2307.02092.pdf)

Qiqi Zhou, **Yichen Zhu**&Dagger;

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/scalekd.png' alt="sym" width="300" height="150"></div></div>
<div class='paper-box-text' markdown="1">

[ScaleKD: Distilling Scale-Aware Knowledge in Small Object Detector, **CVPR 2023**](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhu_ScaleKD_Distilling_Scale-Aware_Knowledge_in_Small_Object_Detector_CVPR_2023_paper.pdf)

**Yichen Zhu**, Qiqi Zhou, Ning Liu, Zhiyuan Xu, Zhicai Ou, Xiaofeng Mou, Jian Tang

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/tllm.png' alt="sym" width="300" height="150"></div></div>
<div class='paper-box-text' markdown="1">

[Teach Less, Learn More: On the Undistillable Classes in Knowledge Distillation, **NeurIPS 2023, Spotlight (top 3%)**](https://proceedings.neurips.cc/paper_files/paper/2022/file/cf5c369c1bc070361477008e3f5210ed-Paper-Conference.pdf)

**Yichen Zhu**, Ning Liu, Zhiyuan Xu, Xin Liu, Weibin Meng, Louis Wang, Zhicai Ou, Jian Tang

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='images/lg3d.png' alt="sym" width="300" height="150"></div></div>
<div class='paper-box-text' markdown="1">

[Label-guided auxiliary training improves 3d object detector, **ECCV 2022**](https://arxiv.org/pdf/2207.11753)

Yaomin Huang&dagger;, Xinmei Liu&dagger;, **Yichen Zhu**, Zhiyuan Xu, Chaomin Shen, Zhengping Che, Guixu Zhang, Yaxin Peng, Feifei Feng, Jian Tang

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2021</div><img src='images/sckd.png' alt="sym" width="300" height="150"></div></div>
<div class='paper-box-text' markdown="1">

[Student customized knowledge distillation: Bridging the gap between student and teacher, **ICCV 2021, Oral (top 3%)**](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhu_Student_Customized_Knowledge_Distillation_Bridging_the_Gap_Between_Student_and_ICCV_2021_paper.pdf)

**Yichen Zhu**, Yi Wang

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
<!-- - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
<!-- </div> -->
<!-- </div> -->

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- # 🎖 Honors and Awards -->
<!-- - *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
<!-- - *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # 📖 Educations -->
<!-- - *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
<!-- - *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # 💬 Invited Talks -->
<!-- - *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
<!-- - *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships -->
<!-- - *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->