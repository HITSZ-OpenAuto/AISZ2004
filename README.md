# AISZ2004 - 信息论
<!-- TOML-META: repo_type="normal" -->
<!-- TOML-BADGES: source="basic_info" -->

![学分](https://img.shields.io/badge/学分-2-moccasin)

![学时构成](https://img.shields.io/badge/学时构成-gold)
![理论学时32](https://img.shields.io/badge/理论学时-32-wheat)

![成绩构成](https://img.shields.io/badge/成绩构成-gold)
![平时30%](https://img.shields.io/badge/平时-30%25-wheat)
![期末考试70%](https://img.shields.io/badge/期末考试-70%25-wheat)

信息论（Information Theory），2 学分，理论课，总学时 32。开课单位：信息科学与技术学院。面向人工智能院士班。讲授信息度量、信源编码、信道编码与率失真等经典内容。

## 授课教师

<!-- TOML-LECTURERS: part="intro" -->

<!-- TOML-ITEM: id="lecturers-intro-1" -->

白方，哈尔滨工业大学（深圳）教授、博士生导师。研究方向包括几何优化、3D 感知、医疗影像导航与空间计算等。

> 文 / [aqua](https://github.com/marine-aqua)，2026-07

<!-- TOML-LECTURERS: part="items" -->
- 白方
  <!-- TOML-ITEM: id="review-白方-1" -->
  - 2025 年底入职哈工深后首开本课，课业与科研任务都重，状态上能感觉到比较辛苦。
  - 老师学习与消化新课的能力很强：此前主要方向并非通信 / 压缩，备课周期据了解也很短，但仍能很快把内容吃透，课堂主线清楚、insight 突出。语速偏快。课堂上常提醒更应抓住思路与直觉，而不必过度纠结数学形式的绝对严谨。
    > 文 / [aqua](https://github.com/marine-aqua)，2026-07

## 考核方式
<!-- TOML-SECTION: title="考核方式" -->

<!-- TOML-ITEM: id="item-考核方式-1" -->

本课程与其他集群开设的「信息论导论」不同。

- 平时成绩：30%（点名 + 作业）
- 期末考试：70%（闭卷）
- 期末侧重概念关系与思路；课堂曾强调噪声信道编码定理、Kraft / Huffman / Hamming、马尔可夫熵率、信道容量与高斯信道等

> 文 / [aqua](https://github.com/marine-aqua)，2026-07

## 教材与参考书
<!-- TOML-SECTION: title="教材与参考书" -->

<!-- TOML-ITEM: id="item-教材与参考书-1" -->

本课内容脉络与常见信息论教材相近，但更重要的学习材料是**教师课件**——作业与期末题均出自课件，老师在课件上投入很大；也没有另行发放纸质讲义。课件因版权原因不上传本仓库。

公开参考材料（据课堂整理，供拓展阅读）：

- 课程要点脉络：Duke 信息论相关 PPT
- 前期（至噪声信道编码定理）：David MacKay, *Information Theory, Inference, and Learning Algorithms*
- 后期：Stanford 信息论课程讲义

> 文 / [aqua](https://github.com/marine-aqua)，2026-07

## 学习资料
<!-- TOML-SECTION: title="学习资料" -->

<!-- TOML-ITEM: id="item-学习资料-1" -->

- 本仓库：考试笔记、分章节习题集（`notes/`）；期末回忆卷（`exams/`）

> 文 / [aqua](https://github.com/marine-aqua)，2026-07

<!-- TOML-ITEM: id="item-学习资料-2" -->

- [2026 年 AISZ-23 复习资料总览](notes/2026_AISZ-23-CS-Reviews/信息论复习.html)：知识图谱、考试重点、三个讲解模块与疑问解答
- `notes/2026_AISZ-23-CS-Reviews/知识清单/` 与 `章节测试/`：覆盖 Lecture 2–16 的知识清单和交互式章节测试
- HTML 可直接用浏览器打开；公式由 MathJax 渲染，首次加载需要联网
- 资料来源：[MukioXun/AISZ-23-CS-Review-Materials](https://github.com/MukioXun/AISZ-23-CS-Review-Materials)

## 课程内容
<!-- TOML-SECTION: title="课程内容" -->

<!-- TOML-ITEM: id="item-课程内容-1" -->

大致覆盖（按照 2026 春实际授课情况总结，供参考）：

- 信息度量：熵、条件熵、互信息、KL 散度、交叉熵
- 不等式与凹凸性：Jensen、log-sum、Gibbs；熵与互信息的凹凸性
- 信源编码：AEP（IID / 平稳遍历）、熵率与马尔可夫、Kraft、变长编码、Huffman
- 信道编码：数据处理不等式与 Fano、信道容量与联合典型性、噪声信道编码定理、高斯信道与水填充、Hamming 码
- 有损压缩与综合：率失真、信源–信道分离；略及 VAE 与信息论的联系

> 文 / [aqua](https://github.com/marine-aqua)，2026-07

## 课程建议
<!-- TOML-SECTION: title="课程建议" -->

<!-- TOML-ITEM: id="item-课程建议-1" -->

- 更重要的是概念和思路要清楚，而不是死记公式；按往年题型，证明比重并不大
- 复习以课件与作业为主；本仓库笔记、分章节习题集与期末回忆卷可作补充
- 教师课件因版权问题，不上传至仓库

> 文 / [aqua](https://github.com/marine-aqua)，2026-07
