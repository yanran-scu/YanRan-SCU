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

# 📖 教育经历
- *2020.09 - 至今*,  博士（保研、硕博连读），四川大学/物理化学/导师：赵南蓉教授
- *2016.09-2020.06*，	学士，四川大学/化学

- 
# 🔥 研究方向
- **介观系统的粗理化模拟及统计物理分析：**
随着纳米材料与生物科学技术的合成及表征手段不断发展，介观尺度（纳米-微米）的动力学因其兼具有宏观与微观的特性受到了越来越多的关注。介观体系具体的例子包括细胞，微米和纳米级别的材料，这类体系往往具有明确的可被宏观观测的物理平均量，而同时，其内部又具有不可忽略的涨落。我们课题组发展介观统计方法（郎之万方程），结合粗粒化模型及计算机模拟（自主开发），探索复杂体系非平衡统计力学行为的新现象和新规律。
- **研究方法：**
采用粗粒化模型模拟生物体系中的大分子：对郎之万方程进行离散，把粒子的不断运动归结为其随时刻的位置速度的改变。在 Visual Studio 2012 编译平台，使用 C++ 编程语言，基于 Nvidia 的 CUDA 编写整个模拟程序，实现在GPU上以单指令多数据模式高效并行处理大量粒子的位置速度演化，探索大分子运动规律以及构象变化。




# 🔥 项目经历
- **两项国家自然科学基金面上项目**
（1）活性生物体系非均一动力学行为的介观统计理论研究（Grant No.22173063）2022. 12--至今
（2）活性生物体系扩散-反应动力学的介观统计理论研究（Grant No.21873066） 2019.01--2022.12

- **负责内容：**
&参与基金的撰写及申请：大量阅读国内外关于活性体系的文献，并梳理整合，敏锐发现其中不足，提出初步改进方法，与导师讨论，最终形成切实可行的研究方案。
&	搭建模拟程序：基于 NVIDIA CUDA的 C/C++，运用 GPU 高效数据并行能力，自主开发面向多副本统计的粗粒化分子动力学模拟程序，对大量粒子系统进行位置速度演化，实现相对于传统模拟的 5-10 倍加速。根据课题需要，建立各类复杂模型，如高分子溶液、受限环境、多孔介质、流体环境等等。联动Mathematica软件与C++程序对所记录的粒子信息进行数据处理，分析其结构和动力学性质。同时将程序进行可视化处理（OpenGL）。
&结果分析：(1) 探索亲疏水性、活性、手性等对于生物体系相分离的调控，建立在此环境中大分子异常扩散动力学的理论框架；发展活性相分离环境中高分子链环化速率计算的有效方法。 (2) 探索生物体系中活性、拥挤等不同条件对于生物大分子穿孔、环化、扩散等动力学的影响，发现活性粒子在高分子溶液中的反常扩散动力学规律，分析生物大分子的构象变化。


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>
- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**




# 🎖 Honors and Awards
- *2024.09* 获四川大学2025届优秀毕业研究生，校级； 
- *2024.09* 获四川大学2023-2024学年优秀研究生干部，校级；



# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
