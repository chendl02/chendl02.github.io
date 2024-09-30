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

I am currently a first-year ms student in computer science at the University of Massachusetts Amherst, working with Prof. Chuang Gan. Previously, I was an undergraduate at Wuhan University.

My research interest lies in multimodal foundation model and (embodied) agent.

<br/>

# 🔥 News


<div style="max-height: 200px; overflow-y: auto;">
<ul>
  <li><em>2024.09:</em> I serve as a reviewer for <strong>ICLR 2025</strong>.</li>
  <li><em>2024.08:</em> <a href="https://arxiv.org/abs/2407.20228">FlexAttention</a> is accepted by <strong>ECCV 2024</strong>. Check our <a href="https://vis-www.cs.umass.edu/flexattention/">Project Page</a> and also <a href="https://github.com/UMass-Foundation-Model/FlexAttention">GitHub</a></li>
  <li><em>2024.07:</em> I serve as a reviewer for <strong>WACV 2025</strong>.</li>
  <li><em>2024.01:</em> <a href="https://arxiv.org/abs/2311.03354">CoVLM</a> is accepted by <strong>ICLR 2024</strong>. Check our <a href="https://vis-www.cs.umass.edu/CoVLM/">Project Page</a> and also <a href="https://github.com/UMass-Foundation-Model/CoVLM">GitHub</a>.</li>
  <li><em>2024.02:</em> I serve as a reviewer for <strong>ACM MM 2024</strong>.</li>
  <li><em>2023.10:</em> One paper is accepted at <strong>MMMI@MICCAI 2023</strong> and one paper is accepted by <strong>ACM MM 2023</strong>.</li>
  <li><em>2023.10:</em> I attended China National Computer Congress (CNCC) and was awarded the honor of CCF (China Computer Federation) Elite Collegiate Award (102 Students nation-wide).</li>
  <li><em>2023.08:</em> <a href="https://openaccess.thecvf.com/content/ICCV2023/papers/Qiu_Scratch_Each_Others_Back_Incomplete_Multi-Modal_Brain_Tumor_Segmentation_via_ICCV_2023_paper.pdf">GSS</a> is accepted by <strong>ICCV 2023</strong>, a novel self-distillation algorithm for multimodal data. </li>
  <li><em>2023.06:</em> Introduce <a href="http://arxiv.org/abs/2306.11528">TransRef</a>, first transformer-based model for Reference-Guided Image Inpainting. Check our <a href="https://github.com/Cameltr/TransRef"> Github</a>.</li>
</ul>
</div>

<br/>


# 📝 Publications 
**&dagger; Equal Contribution**   


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV2024</div><img src='images/flexattention/intro.jpg' alt="covlm_poster" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

FlexAttention for Efficient High-Resolution Vision-Language Models


Junyan Li, **Delin Chen**, Tianle Cai, Peihao Chen, Yining Hong, Zhenfang Chen, Yikang Shen, Chuang Gan

[**Paper**](https://arxiv.org/pdf/2407.20228)  |  [**GitHub** ](https://github.com/UMass-Foundation-Model/FlexAttention) | [**Project Page**](https://vis-www.cs.umass.edu/flexattention/) |
![](https://img.shields.io/github/stars/UMass-Foundation-Model/FlexAttention?style=social)
- FlexAttention is a plug-and-play attention module that can enhance VLMs' ability to perceive details in high resolution image in an efficient way.

</div>
</div>





<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR2024</div><img src='images/covlm/intro.png' alt="covlm_poster" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

CoVLM: Composing Visual Entities and Relationships in Large Language Models Via Communicative Decoding

Junyan Li, **Delin Chen**, Yining Hong, Zhenfang Chen, Peihao Chen, Yikang Shen, Chuang Gan

[**Paper** ](https://arxiv.org/pdf/2311.03354.pdf)  |  [**GitHub** ](https://github.com/UMass-Foundation-Model/CoVLM) | [**Project Page**](https://vis-www.cs.umass.edu/CoVLM/)|
![](https://img.shields.io/github/stars/UMass-Foundation-Model/CoVLM?style=social)
- CoVLM is specifically designed to guide the VLM to explicitly compose visual entities and relationships among the text and dynamically communicate with the vision encoder and detection network to achieve vision-language communicative decoding. It boosts the compositional reasoning ability of VLMs and achieve SoTA performance on various tasks involving compositional analysis.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV2023</div><img src='images/GSS/intro.png' alt="gss_poster" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Scratch Each Other's Back: Incomplete Multi-Modal Brain Tumor Segmentation via Category Aware Group Self-Support Learning

Yansheng Qiu&dagger;, **Delin Chen&dagger;**, Hongdou Yao, Yongchao Xu, Zheng Wang

[**Paper**](https://openaccess.thecvf.com/content/ICCV2023/papers/Qiu_Scratch_Each_Others_Back_Incomplete_Multi-Modal_Brain_Tumor_Segmentation_via_ICCV_2023_paper.pdf)


- We proposed Group Self-Support Learning framework to utilize the dominating characteristics of modalities to direct the distillation of mutual knowledge between modalities without expanding the complexity of the baseline network. The result obtained SOTA on BraTs 2015, 2018 and 2020 datasets.

</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'>
<div><div class="badge">ArXiv</div><img src='images\Transref\intro.png' alt="transref_poster" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

TransRef: Multi-Scale Reference Embedding <b>Trans</b>former for <b>Ref</b>erence-Guided Image Inpainting 

 Liang Liao&dagger;, Taorong Liu&dagger;, <b>Delin Chen</b>, Jing Xiao, Zheng Wang, Chia-Wen Lin, and Shin'ichi Satoh

[**Paper**](http://arxiv.org/abs/2306.11528) | [**GitHub** ![](https://img.shields.io/github/stars/Cameltr/TransRef?style=social)](https://github.com/Cameltr/TransRef) 
- Transref utilizes a reference image that depicts a scene similar to the corrupted image to facilitate image inpainting.
</div>
</div>

# 🎡 Service
<!-- ## Conference Committee Member -->
- Reviewer for ICLR'2025
- Reviewer for WACV'2025
- Reviewer for ACM MM'2024




# 🎖 Honors and Awards
- *2024.04* Outstanding Graduate of Wuhan University.
- *2023.11* Leijun Undergraduate Computer Science Scholarship *Wuhan University*
- *2023.10* **CCF (China Computer Federation) Elite Collegiate Award** (CCF优秀大学生) (102 Students nation-wide) *China Computer Federation*
- *2023.09* **First Class Scholarship** (Award Rate: 5% school-wide) *Wuhan University* 
- *2021, 2022, 2023* Excellent Student Award *Wuhan University*


# 📖 Educations
- University of Massachusetts Amherst<img src="images/insignia/umass.png" alt="UMass Insignia" style="float: right; width: 100px;"/>

  MS, Computer Science, 2024.09 - (now), 
  

<br/>

- Wuhan University<img src="images/insignia/whu.png" alt="WHU Insignia" style="float: right; width: 100px;"/>
  
  Undergraduate, Computer Science, 2020.09 - 2024.06, 
  
  Advisor: Prof. [Zheng Wang](https://wangzwhu.github.io/home/)

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->

<dl style="text-align: center;"><a href='https://clustrmaps.com/site/1bw3j'  title='Visit tracker'><img src='//clustrmaps.com/map_v2.png?cl=ffffff&w=400&t=tt&d=kX2KOIZec5lK22VitFidFZG9_RIYd8zSoWPTZZp1KA4'/></a></dl>

