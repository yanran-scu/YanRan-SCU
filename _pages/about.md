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
- *2020.09 - 至今*,  博士（保研、硕博连读），四川大学/计算机数值模拟/导师：赵南蓉教授 （专业：物理化学）
- *2016.09-2020.06*，	学士，四川大学/化学

# 🔥 研究方向
- **介观系统的粗粒化模拟及统计物理分析：**
  
随着纳米材料与生物科学技术的合成及表征手段不断发展，介观尺度（纳米-微米）的动力学因其兼具有宏观与微观的特性受到了越来越多的关注。介观体系具体的例子包括细胞，微米和纳米级别的材料，这类体系往往具有明确的可被宏观观测的物理平均量，而同时，其内部又具有不可忽略的涨落。我们课题组发展介观统计方法（郎之万方程），结合粗粒化模型及计算机模拟（自主开发），探索复杂体系非平衡统计力学行为的新现象和新规律。
- **研究方法：**
  
采用粗粒化模型模拟生物体系中的大分子：对郎之万方程进行离散，把粒子的不断运动归结为其随时刻的位置速度的改变。在 Visual Studio 2012 编译平台，使用 C++ 编程语言，基于 Nvidia 的 CUDA 编写整个模拟程序，实现在GPU上以单指令多数据模式高效并行处理大量粒子的位置速度演化，探索大分子运动规律以及构象变化。




# 🔥 项目经历
- **两项国家自然科学基金面上项目**（参研人）

1. 活性生物体系非均一动力学行为的介观统计理论研究（Grant No.22173063）2022. 12--至今

2. 活性生物体系扩散-反应动力学的介观统计理论研究（Grant No.21873066） 2019.01--2022.12

- **负责内容：**

1. **参与基金的撰写及申请：** 大量阅读国内外关于活性体系的文献，并梳理整合，敏锐发现其中不足，提出初步改进方法，与导师讨论，最终形成切实可行的研究方案。

2. **搭建模拟程序：** 基于 NVIDIA CUDA的 C/C++，运用 GPU 高效数据并行能力，自主开发面向多副本统计的粗粒化分子动力学模拟程序，对大量粒子系统进行位置速度演化，实现相对于传统模拟的 5-10 倍加速。根据课题需要，建立各类复杂模型，如高分子溶液、受限环境、多孔介质、流体环境等等。联动Mathematica软件与C++程序对所记录的粒子信息进行数据处理，分析其结构和动力学性质。同时将程序进行可视化处理（OpenGL）。

3. **结果分析：**(1) 探索亲疏水性、活性、手性等对于生物体系相分离的调控，建立在此环境中大分子异常扩散动力学的理论框架；发展活性相分离环境中高分子链环化速率计算的有效方法。 (2) 探索生物体系中活性、拥挤等不同条件对于生物大分子穿孔、环化、扩散等动力学的影响，发现活性粒子在高分子溶液中的反常扩散动力学规律，分析生物大分子的构象变化。

# 💻 专业技能
- **系统性知识储备：**
  
（1）**分子动力学模拟：** 建立一整套完整的从理论到程序架构再到数据处理的模拟体系，模拟聚合物、金属、纳米颗粒等材料的运动，并设置不同的力场及势能，来分析其构象和动力学行为，进而理解其物理化学特性。

（2）**流体力学的相关计算方法：** 流体被抽象为远小于真实分子个数的一定数量的代表粒子，其碰撞仅在固定的离散时间间隔上进行求算。但流体粒子自身的空间坐标和粒子速度都是连续变量，因此，该算法表现出无条件的数值稳定性，并满足 Boltzmann H 定理（多粒子碰撞动力学）。

（3）**计算机技术：** 熟练掌握C++开发技术及其语言特性在模拟研究中的代码工程化与落地应用；熟悉Python基础语法；掌握强大数学工具软件Mathematica及其与C++等语言的自动化脚本整合；应用Mathematica进行数值运算；掌握CUDA C++ 大规模高性能并行编程以及基于OpenGL的可视化图形应用的底层开发；熟悉Linux操作系统。
- **系统性框架整合能力：**
  
独立完成对课题组多个研究方向相关的程序框架整合，可在数日内实现对新研究方向的快速定制化开发。


# 🎖 所获荣誉
- *2024.09* 获四川大学2025届优秀毕业研究生，校级； 
- *2024.09* 获四川大学2023-2024学年优秀研究生干部，校级；
- *2023.10* 获四川大学2022-2023学年优秀研究生，校级
- *2020.12* 获2019年度“中国大学生自强之星”，获“中国大学生新东方自强奖学金”，国家级；
- *2018.11* 获2018年“四川大学化学学院岛津科技创新”活动一等奖，院级；
- *2017.06* 获四川大学2017年度“自强之星”，校级；


# 📝 论文发表 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2024</div><img src='images/1.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Attractive crowding effect on passive and active polymer looping kinetics](https://pubs.aip.org/aip/jcp/article/160/13/134902/3280571/Attractive-crowding-effect-on-passive-and-active)

***R. Yan***, C. N. Zhao, and N. R. Zhao*, J. Chem. Phys. (Sci) 160, 134902 (2024). [\[Video](https://pan.baidu.com/s/1Q4MRHxdzDN_j6ghcjvdARA?pwd=pn0h)]

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023</div><img src='images/2.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

 [Conformation and dynamics of an active filament in crowded media](https://pubs.aip.org/aip/jcp/article/158/11/114905/2881794/Conformation-and-dynamics-of-an-active-filament-in)
 
***R. Yan***, F. Tan, J. L. Wang and N. R. Zhao*, J. Chem. Phys. (Sci)  158, 114905 (2023). [\[Video](https://pan.baidu.com/s/1dUxqL0oo0aKFE8zhPVz4Yg?pwd=5u26)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023</div><img src='images/3.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Translocation dynamics of an active filament through a long-length scale channel](https://pubs.acs.org/doi/10.1021/acs.jpcb.3c04250)

F. Tan, ***R. Yan***, C. N. Zhao and N. R. Zhao*, J. Phys. Chem. B (Sci)  127, 8603 (2023). [\[Video](https://pan.baidu.com/s/1wBj44RWz5YbMrxDMVdxZKQ?pwd=f7cv)]
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022</div><img src='images/9.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Biased-angle effect on diffusion dynamics and phase separation in anisotropic active particle system](https://pubs.aip.org/aip/jcp/article/156/20/204901/2841498/Biased-angle-effect-on-diffusion-dynamics-and)  

T. Lei, ***R. Yan*** and N. R. Zhao*,  J. Chem. Phys. (Sci)  156, 204901 (2022). [[Video](https://pan.baidu.com/s/1VRZYwTda2oAwh1D327uARw?pwd=qiqo)]
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2022</div><img src='images/4.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Passive and active tracer dynamics in polymer solutions with isotropic-to-nematic phase transition](https://pubs.rsc.org/en/content/articlelanding/2022/cp/d2cp00323f)

Y. Chen, ***R. Yan*** and N. R. Zhao*,  Phys. Chem. Chem. Phys. (Sci)  24, 7415 (2022).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2020</div><img src='images/5.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dynamics and glass transition temperature of polystyrene films supported on hydroxyl terminated substrates](https://pubs.aip.org/aip/adv/article/10/4/045322/1037727/Dynamics-and-glass-transition-temperature-of)
 
B. J. Zhang, ***R. Yan*** and N. R. Zhao*,AIP Advances (Sci)  10, 045322 (2020).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2019</div><img src='images/6.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Unusual crowding-induced chain looping kinetics in hard-sphere fluids: a contrastive study with polymer solutions](https://pubs.rsc.org/en/content/articlelanding/2019/sm/c9sm00400a)

Y. K. Bian, ***R. Yan***, P. Li and N. R. Zhao*,  Soft Matter (Sci)  15, 4976 (2019).
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2024</div><img src='images/10.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Forced and spontaneous translocation dynamics of a semiflexible active polymer in two dimensions](https://pubs.rsc.org/en/content/articlelanding/2024/sm/d3sm01409f)

F. Tan, J. L. Wang, ***R. Yan*** and N. R. Zhao*,  Soft Matter (Sci)  20, 1120 (2024). [\[Video](https://pan.baidu.com/s/1tINi6Vzpj5mZf2Bb1_cFig?pwd=x79z)]
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023</div><img src='images/8.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Collective behavior of chiral active particles with anisotropic interactions in a confined space](https://pubs.rsc.org/en/content/articlelanding/2023/sm/d2sm01402e)

T. Lei, C. N. Zhao, ***R. Yan*** and N. R. Zhao*,  Soft Matter (Sci)  19, 1312 (2023). [\[Video](https://pan.baidu.com/s/1NX7AwBJ67CKJSPANr0AJhg?pwd=kb6u)]
</div>
</div>


- **所参加学术会议：**
  
1.   中国化学会第十四届全国量子化学会，上海，2021 年 10 月
   
2.   中国化学会第三十三届学术年会，青岛，2023 年 6 月
   
***R. Yan***, F. Tan, J. L. Wang and N. R. Zhao*, Conformation and dynamics of an active filament in crowded media. (优秀墙报奖)



# 💬 在校经历
1.	*2023. 09*--至今，任四川大学化学学院2022级研究生一班班长兼副团支书
   
2.	*2020. 09--2021.06*，任四川大学化学学院物理化学课程助教
   
3.	*2017. 06--2019. 05*，任四川大学化学学院学生会学习部副部长


# 💻 专业技术

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/zy0.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"></div><img src='images/zy1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

</div>
</div>

