---
title: 'GHWT: Global Heat Wave Toolbox'
summary: 'Global Heat Wave Toolbox (GHWT) was developed to generate heat wave matrix from 1971 to 2100.'
date: 2022-09-16
url_project: 'https://doi.org/10.6084/m9.figshare.17075660.v6'

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Tool interface'

authors:
  - admin

tags:
  - 热浪
  - 数据
  - 工具
---

全球热浪工具箱（Global Heat Wave Toolbox，GHWT）利用三套历史再分析数据和多情景的CMIP6模拟数据开发而成，可用于生成1971年至2100年的热浪记录。

该长期全球热浪记录数据集是基于三套逐小时历史气候数据（CRU-JRA、ERA5 和 GLDAS）以及GFDL-ESM4模型在三种共享社会经济路径（SSPs）下的未来逐日气候数据构建而成。数据集采用三种热浪判定阈值：固定阈值（如35°C以上）、百分位阈值（如超过90%）和持续时间阈值（如连续3天以上）。提供的Python文件为全球热浪工具箱的源代码，可根据自定义阈值生成相应的热浪记录。