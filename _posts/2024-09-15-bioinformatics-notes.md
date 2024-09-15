---
layout: post
title:  "生物信息学笔记"
date:   2024-09-15 12:00:00 +0800
categories: jekyll update
---

# 课堂笔记

>## 课堂笔记1：《Course Logistics》

### 课程介绍
课程名为 **生物信息学实践**，由鲁志教授主讲，侧重分析方法和算法的理论与实践，重视上机实践和编程。

### 预修要求
1. 需要具备基础的编程能力，能够自行安装软件，并熟悉 Linux 操作系统。
2. 学过高等数学等数理基础课程。

### 后续课程推荐
1. Python课程：「基于Python 的科学与数值计算」等。
2. AI 相关课程。

### 学习内容和方法
- 编程技能（如 Linux、Bash、R、Python 等）贯穿课程的不同阶段。
- 每周课程包括课堂讲授和课后实践，要求通过编程和数据分析项目提高实践能力。
- 教学大纲：[《生物信息学实践》教学大纲](https://docs.qq.com/doc/DWXlXc29FclpaTmp2)
- 教学辅导：[Bioinformatics Tutorial](https://book.ncrnalab.org/teaching)
- 课件下载：[清华大学云盘课件](https://cloud.tsinghua.edu.cn/d/dcbb0944631a4291b34c/?p=%2FLectures&mode=list)

### 评分机制
1. 课堂互动占 **20%**。
2. 课后作业和项目占 **80%**，包括经验分享展示和小组作业。

### 其他注意事项
- 课后作业可小组讨论，但需独立完成并提交。
- 助教会在每次课后提供答疑时间。

---

>## 课堂笔记2：《Introduction》

### 生物信息学的四个步骤
1. **提出问题 (Question)**：从生物学或医学中提出研究问题。
2. **数据信息 (Information)**：收集与问题相关的生物或医学数据，如基因组序列。
3. **数据分析 (Data Analysis)**：对数据进行清洗、特征提取，确保数据能够用于后续的模型构建。
4. **建模 (Modeling)**：建立概率模型或计算算法以解决生物学问题。

### 生物学中的核心问题
1. 意识的生物学基础是什么？
2. **为什么人类基因这么少？**
3. **遗传变异与个人健康之间有多大关系？**

### 生物数据分析
- 特定的**生物学问题**对应着特定的**测序方法**和**生物信息学工具**。

### 生物学中的建模
1. **模型**：如机器学习模型、回归模型、神经网络模型（深度学习）。
2. **算法**：如数字排序算法、动态规划算法。

#### 算法与模型的区别：
- 模型需要有**公式和参数**，算法需要的是**逻辑/推理**。
- 模型是对现实世界的**抽象表示**，算法是明确的用于解决问题的**步骤/指令**。
- 在机器学习中，算法是训练模型的手段，模型则是算法运行后的结果。

### 第四范式
1. **数据驱动的科学发现**，通过大规模数据分析来提出和验证科学问题。

---

>## 课堂笔记3：《Getting Started》

### 1. 文档记录工作 - GitHub 和 Markdown

#### 资源链接：
- [Gitee 高校版](https://gitee.com/education)：基于 Git 的代码托管平台。
- [Markdown 语法指南](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- 示例项目：
  - [Pathformer/README.md](https://github.com/lulab/Pathformer/blob/main/README.md)
  - 更多示例请参阅 GitHub 和清华云链接。

#### Markdown 编辑器推荐：
- **Mac**: Typora, MarkText, Bear, MWeb
- **Windows**: Typora, Madoko

### 2. 备份工作

#### 基本备份选项：
- **云存储**：如清华云（校内速度快）或其他商业云存储服务。
- **系统自带备份工具**：
  - **Mac**: 使用 Time Machine 备份。
  - **Windows**: 使用内置的备份工具。
- **GitHub**：通过终端或 GitHub Desktop 应用同步本地项目到 GitHub。

#### 高级备份选项：
- **Linux** 下自动备份文件。

### 3. 使用生物信息学教程
- 除非特别说明，本教程中的命令均应在终端执行。
- 每个章节的操作都在 Docker 中的独立目录下进行（位于 `/home/test`）。

### 4. 生物信息学的环境设置
#### 文本编辑器教程：
- 学习使用文本编辑器如 Vim：[Vim 快速入门](https://cloud.tsinghua.edu.cn/d/ad22768345664924b202/?p=%2FVideo%2FPart%200.%20Getting%20Started&mode=list)

#### Docker 设置：
1. 安装 Docker。
2. 下载 Ubuntu 镜像：`docker pull ubuntu`
3. 运行容器：`docker run -i -t ubuntu`

#### 资源：
- 配套的教学文件与教学视频：[附录 IV](https://book.ncrnalab.org/teaching/appendix/appendix-iv.-teaching)

---

# 本学期生物信息学的学习计划

## 学习目标
1. 掌握 **Linux** 和 **R** 编程技能，用于生物数据处理。
2. 理解 **NGS** 数据分析，熟练应用 **DNA-seq** 和 **RNA-seq**。
3. 了解基本的 **机器学习** 算法，并使用 R 和 Python 实现简单的模型。
4. 掌握 **单细胞测序** 和 **高通量筛选** 数据分析的基本原理。

## 时间安排

| 周次 | 内容 | 作业 |
|---|---|---|
| 第1周 | 课程介绍、入门任务（环境配置） | 入门指南 |
| 第2-4周 | Linux、Bash 脚本、R 基础 | Linux 任务 |
| 第5周 | NGS 基础，Reads Mapping | NGS 数据处理 |
| 第6-9周 | RNA-seq 差异表达分析，GO/KEGG/GSEA | RNA-seq 作业 |
| 第10-16周 | 机器学习与人工智能应用 | 机器学习任务 |
| 第11-16周 | 单细胞测序与高通量筛选数据分析 | 单细胞数据分析任务 |

## 任务管理
1. **每周预习**：提前查看下一周内容，做好准备。
2. **课后作业**：按时完成作业，及时提交。
3. **进度跟踪**：及时追踪学习进度。

---

