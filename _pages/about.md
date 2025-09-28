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

I am currently a first-year PhD student in computer science at the University of Hong Kong, advised by Prof. <a href="https://taoyds.github.io/">Tao Yu</a> in <a href="https://xlang.ai/">XLANG Lab</a>. Previously, I was a master's student at the University of Massachusetts, working with Prof. <a href="https://people.csail.mit.edu/ganchuang/">Chuang Gan</a>, and completed my undergraduate studies at Wuhan University under the supervision of Prof. <a href="https://wangzwhu.github.io/home/">Zheng Wang</a>.

My research interest lies in building multimodal (embodied) agents in physical world.

Feel free to reach out to me if you are interested in my work, have any questions or ideas to discuss with!
<br/>

# 🔥 News


<div style="max-height: 200px; overflow-y: auto;">
<ul>
  <li><em>2025.05:</em> We release <a href="https://arxiv.org/abs/2505.23604">Satori-SWE</a>. Check our <a href="https://satori-reasoning.github.io/blog/satori-swe/">Project Page</a> and also <a href="https://github.com/satori-reasoning/Satori-SWE">GitHub</a></li>
  <li><em>2025.01:</em> <a href="https://openreview.net/forum?id=womU9cEwcO">ARMAP</a> is accepted by <strong>ICLR 2025</strong>. Check our <a href="https://armap-agent.github.io/">Project Page</a> and also <a href="https://github.com/heaplax/ARMAP">GitHub</a></li>
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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/swesatori/SWE-Satori.png' alt="swesatori" width="100%" style="display: block;"></div></div>
<div class='paper-box-text' markdown="1">

Satori-SWE: Evolutionary Test-Time Scaling for Sample-Efficient Software Engineering


Guangtao Zeng&dagger;, Maohao Shen&dagger;, **Delin Chen**, Zhenting Qi, Subhro Das, Dan Gutfreund, David Cox, Gregory Wornell, Wei Lu, Zhang-Wei Hong&dagger;, Chuang Gan

[**Paper**](https://arxiv.org/abs/2505.23604)  |  [**GitHub** ](https://github.com/satori-reasoning/Satori-SWE) | [**Project Page**](https://satori-reasoning.github.io/blog/satori-swe/)
![](https://img.shields.io/github/stars/satori-reasoning/Satori-SWE?style=social)
- A new perspective of formulating test-time scaling as an evolutionary process, improving sample efficiency for software engineering tasks.
- A novel RL training approach that enables self-evolution, eliminating the need for external reward models or verifiers at inference time.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR2025</div><img src='images/armap/armap.gif' alt="armap_poster" width="100%" style="display: block;"></div></div>
<div class='paper-box-text' markdown="1">

Scaling Autonomous Agents via Automatic Reward Modeling And Planning


Zhenfang Chen&dagger;, **Delin Chen&dagger;**, Rui Sun&dagger;, Wenjun Liu&dagger;, Chuang Gan

[**Paper**](https://openreview.net/forum?id=womU9cEwcO)  |  [**GitHub** ](https://github.com/heaplax/ARMAP) | [**Project Page**](https://armap-agent.github.io/)
![](https://img.shields.io/github/stars/heaplax/ARMAP?style=social) | [**Awesome-Inference-Time-Scaling** ](https://github.com/ThreeSR/Awesome-Inference-Time-Scaling)![](https://img.shields.io/github/stars/ThreeSR/Awesome-Inference-Time-Scaling?style=social) 
- A new framework for LLM-based agents using **automatic** reward models.
- We build  effective, scalable, and controllable reward models to integrate Reflexion and MCTS.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV2024</div><img src='images/flexattention/intro.jpg' alt="covlm_poster" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

FlexAttention for Efficient High-Resolution Vision-Language Models


Junyan Li, **Delin Chen**, Tianle Cai, Peihao Chen, Yining Hong, Zhenfang Chen, Yikang Shen, Chuang Gan

[**Paper**](https://arxiv.org/pdf/2407.20228)  |  [**GitHub** ](https://github.com/UMass-Foundation-Model/FlexAttention) | [**Project Page**](https://vis-www.cs.umass.edu/flexattention/) 
![](https://img.shields.io/github/stars/UMass-Foundation-Model/FlexAttention?style=social)
- FlexAttention is a plug-and-play attention module that can enhance VLMs' ability to perceive details in high resolution image in an efficient way.

</div>
</div>





<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR2024</div><img src='images/covlm/intro.png' alt="covlm_poster" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

CoVLM: Composing Visual Entities and Relationships in Large Language Models Via Communicative Decoding

Junyan Li, **Delin Chen**, Yining Hong, Zhenfang Chen, Peihao Chen, Yikang Shen, Chuang Gan

[**Paper** ](https://arxiv.org/pdf/2311.03354.pdf)  |  [**GitHub** ](https://github.com/UMass-Foundation-Model/CoVLM) | [**Project Page**](https://vis-www.cs.umass.edu/CoVLM/)
![](https://img.shields.io/github/stars/UMass-Foundation-Model/CoVLM?style=social)
- CoVLM is specifically designed to guide the VLM to explicitly compose visual entities and relationships among the text and dynamically communicate with the vision encoder and detection network to achieve vision-language communicative decoding. It boosts the compositional reasoning ability of VLMs and achieve SoTA performance on various tasks involving compositional analysis.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV2023</div><img src='images/GSS/intro.png' alt="gss_poster" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Scratch Each Other's Back: Incomplete Multi-Modal Brain Tumor Segmentation via Category Aware Group Self-Support Learning

Yansheng Qiu&dagger;, **Delin Chen&dagger;**, Hongdou Yao, Yongchao Xu, Zheng Wang

[**Paper**](https://openaccess.thecvf.com/content/ICCV2023/papers/Qiu_Scratch_Each_Others_Back_Incomplete_Multi-Modal_Brain_Tumor_Segmentation_via_ICCV_2023_paper.pdf) |  [**GitHub** ](https://github.com/yansheng-qiu/GSS)
![](https://img.shields.io/github/stars/yansheng-qiu/GSS?style=social)

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
- Reviewer for ACM MM'2024, 2025




# 🎖 Honors and Awards
- *2024.04* Outstanding Graduate of Wuhan University.
- *2023.11* Leijun Undergraduate Computer Science Scholarship *Wuhan University*
- *2023.10* **CCF (China Computer Federation) Elite Collegiate Award** (CCF优秀大学生) (102 Students nation-wide) *China Computer Federation*
- *2023.09* **First Class Scholarship** (Award Rate: 5% school-wide) *Wuhan University* 
- *2021, 2022, 2023* Excellent Student Award *Wuhan University*


# 📖 Educations
- University of Hong Kong<img src="images/insignia/hku.jpg" alt="HKU Insignia" style="float: right; width: 100px;"/>

  PhD, Computer Science, 2025.12 - (now), 

  Advisor: Prof. [Tao Yu](https://taoyds.github.io/)
<br>
<br>

- University of Massachusetts Amherst<img src="images/insignia/umass.png" alt="UMass Insignia" style="float: right; width: 100px;"/>

  MS, Computer Science, 2024.09 - (now), 

  Advisor: Prof. [Chuang Gan](https://people.csail.mit.edu/ganchuang/)
<br>
<br>



- Wuhan University<img src="images/insignia/whu.png" alt="WHU Insignia" style="float: right; width: 100px;"/>
  
  Undergraduate, Computer Science, 2020.09 - 2024.06, 
  
  Advisor: Prof. [Zheng Wang](https://wangzwhu.github.io/home/)

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->

# 👾 Misc

<dl style="text-align: center;"><a href='https://clustrmaps.com/site/1bw3j'  title='Visit tracker'><img src='//clustrmaps.com/map_v2.png?cl=080808&w=300&t=tt&d=kX2KOIZec5lK22VitFidFZG9_RIYd8zSoWPTZZp1KA4&co=ffffff&ct=808080'/></a></dl>

