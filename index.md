---
marp: true
theme: gaia
_class: lead
paginate: true
backgroundColor: #fff
backgroundImage: url('https://marp.app/assets/hero-background.svg')
---



# 无人机三维重建与遥感迁移学习

关键词：减灾科技、点云、迁移学习

2021.10.20

苏锦华

Available at https://github.com/SmartDataLab/DRT-SHARE

Written by Marp and Mermaid in Markdown

---

# 巨灾保险现有问题

- 政府购买、没有面向个人的产品
- 赔付与具体个人受损解耦
- 定损、救援减灾、重建息息相关

![drop-shadow w:400](https://www.chinare.com.cn/zhzjt/template/common/index_nav/zhongzai02_03.png)

![drop-shadow w:100](http://www.ndrcc.org.cn/r/cms/www/official/image/2020/new_logo@4x.png)

![bg right:45% drop-shadow w:600](company2.png)

---

# 自动定损技术

![drop-shadow w:900](company.png)

---

# 自动定损技术 cont.

![bg drop-shadow 60%](https://www.mdpi.com/remotesensing/remotesensing-12-04055/article_deploy/html/images/remotesensing-12-04055-g001-550.jpg)
![bg drop-shadow 90%](https://www.mdpi.com/remotesensing/remotesensing-12-04055/article_deploy/html/images/remotesensing-12-04055-g010-550.jpg)



---

# 当前主要的问题

- 灾前灾后遥感不够实时
- 以屋顶损失代替了建筑物损失
- 物理损失不代表经济损失(asset exposure)

$DLI=\sum w_i \times f_i$

![bg right:40% 100% drop-shadow](DI_series.png)

---

# 现有的数据

- google earth 遥感
- 8月1日-3日 河南鹤壁 大疆Pro和RTX 路径斜拍(合成正投影和点云)

![drop-shadow](https://img2.baidu.com/it/u=1764666523,3295480903&fm=26&fmt=auto)

---

# 研究目标

PICC&减灾防控中心课题项目

![drop-shadow h:400](task.png)


---


# 参考方案

Transfer Component Analysis