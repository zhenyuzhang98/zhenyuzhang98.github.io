---
permalink: /zh/cv/
title: "简历"
lang: zh-CN
author_profile: true
author_bio: '目前为宁波大学博士后研究人员'
---

## 当前职位

宁波大学博士后研究人员。

## 教育经历

- 2025 年 6 月：北京大学理论物理博士。
- 2020 年 6 月：中山大学物理学学士。

## 研究经历

### 2021 年 9 月至今：黑洞成像

指导教师：[陈斌教授](https://inspirehep.net/authors/1013901?ui-citation-summary=true)。

- 使用广义相对论光线追踪方法，计算不同天体环境和光源（包括吸积盘、热点和喷流）下的黑洞图像。
- 研究黑洞阴影和偏振图样。
- 研究磁化黑洞附近的带电粒子动力学。
- 建立吸积盘和漏斗壁的解析形态模型。
- 研究动态光源产生的黑洞电影自相关，以提取黑洞及其吸积盘的物理信息。

### 2023 年 8 月至今：原初黑洞与早期宇宙

指导教师：[皮石教授](https://stonepi.github.io)。

- 使用扩展 Press–Schechter 方法和峰值理论计算原初黑洞丰度，并研究未来引力波探测器对其的约束。

### 2018 年 10 月—2020 年 8 月：宇宙大尺度结构

指导教师：[李潇东教授](https://inspirehep.net/authors/1024776?ui-citation-summary=true)。

- 结合层析 Alcock–Paczynski 检验与非参数统计方法，重构暗能量状态方程参数。
- 开发深度学习方法，从暗物质密度场推断非线性速度场。

## 教学经历

{% include zh-teaching.md %}

## 荣誉与奖励

- 2024 年 6 月：北京大学校长奖学金。
- 2023 年 6 月：北京大学校长奖学金。
- 2022 年 7 月：中国物理学会引力与相对论天体物理分会年会优秀学生报告奖。
- 2018 年 9 月：中山大学本科生一等奖学金。
- 2017 年 9 月：本科生国家奖学金。

## 编程技能

- 熟练使用：Wolfram Mathematica、Python、Linux。
- 熟悉：C/C++。
- 具备基础知识：Julia、Fortran。

## 学术报告

{% include zh-talks.md %}

## 代表论文

完整论文列表见 [INSPIRE](https://inspirehep.net/authors/1744398?ui-citation-summary=true)。以下保留论文原始英文题名。

{% for post in site.publications reversed %}
- [{{ post.title }}]({{ post.url }})。{{ post.citation }}。
{% endfor %}
