# AI-For-Science-Daily
AI for Science（AI+科研）日常学习笔记+实操代码

[![Zhihu](https://img.shields.io/badge/知乎专栏-AI科研加速器-0084FF?logo=zhihu)](https://www.zhihu.com/people/你的知乎ID)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)
> **Linking AI Theory to Academic Practice.**
>
> 这是一个面向科研人员（Researcher/Student）的 AI 知识库与工具箱。本项目是[**知乎专栏《AI 科研加速器》**](你的知乎专栏链接)的配套代码仓库。

---

## 📖 项目简介 (Introduction)

在 AI 爆发的时代，科研范式正在发生改变。本项目旨在探索AI与科研的结合点：

1.  **操作方式：** 用通俗的语言+代码演示，拆解 Transformer、RAG、Fine-tuning 等核心概念。
2.  **科研提效：** 提供经过验证的 **Academic Prompts**（润色、降重、审稿回复）。
3.  **代码实战：** 提供python代码实现。

---

## 🗂️ 学习路线与目录 (Roadmap & Contents)

### Phase 1: 理论基石与直觉构建

| Day | 📝 主题 (Topic) | 🔗 知乎文章 | 💻 代码/演示 (Code) | 🏷️ 标签 |
| :--- | :--- | :--- | :--- | :--- |
| **01** | **Transformer** 核心架构拆解 | [知乎链接](...) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](notebooks/day01_transformer.ipynb) | `DeepLearning` |
| **02** | **Tokenization** 分词机制与陷阱 | [知乎链接](...) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](notebooks/day02_tokenization.ipynb) | `NLP` `Preprocessing` |
| **03** | **Embedding** 向量化与语义搜索 | [知乎链接](...) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](notebooks/day03_embedding.ipynb) | `RAG` |

### Phase 2: 科研生产力工具 (Prompt Engineering)

| Day | 📝 主题 (Topic) | 🔗 知乎文章 | 🛠️ 提示词模版 (Prompt) | 🏷️ 标签 |
| :--- | :--- | :--- | :--- | :--- |
| **08** | **Academic Polishing** 论文润色 | [知乎链接](...) | [Prompt Template](prompts/polishing.md) | `Writing` |
| **09** | **Rebuttal** 审稿意见回复 | [知乎链接](...) | [Prompt Template](prompts/rebuttal.md) | `Review` |
| **10** | **Literature Review** 文献综述 | [知乎链接](...) | [Agent Demo](notebooks/day10_lit_review_agent.ipynb) | `Reading` |

*(持续更新中，欢迎 Star ⭐ 关注)*

---

## 🛠️ 安装与使用 (Installation)

如果你想在本地运行本项目的代码：

1.  **Clone 仓库**
    ```bash
    git clone [https://github.com/YourUsername/AI-For-Science-Notes.git](https://github.com/YourUsername/AI-For-Science-Notes.git)
    cd AI-For-Science-Notes
    ```

2.  **安装依赖**
    ```bash
    pip install -r requirements.txt
    ```

3.  **启动 Jupyter Notebook**
    ```bash
    jupyter notebook
    ```

---

## 🗺️ 学习大纲 (Syllabus: From Zero to AI-Powered Researcher)

本项目分为五个阶段，建议按顺序阅读，或根据需求跳转到对应模块。

### 🟢 Phase 1: 核心直觉与底层逻辑 (The Foundations)
*目标：理解大模型“思考”的本质，不再把 AI 当成黑盒。*

| 序号 | 知识点 | 核心内容 | 实战资源 | 进度 |
| :--- | :--- | :--- | :--- | :--- |
| 01 | **Transformer** | 彻底理解 Attention 机制与并行计算 | [原理图解] | 🟢 |
| 02 | **Tokenization** | 为什么 AI 算不对 9.11 > 9.9？理解分词陷阱 | [BPE 演示] | 🟢 |
| 03 | **Embeddings** | 语义的几何表示：如何让文献变成向量 | [向量搜索脚本]| 🟢 |
| 04 | **Temperature** | 概率采样：如何控制回复的“创造性”与“严谨性” | [参数对比实验]| 🟡 |
| 05 | **Context Window** | 上下文衰减与长文本处理的局限性 | [长文本压缩技巧]| ⚪ |

### 🔵 Phase 2: 提示词工程学术实战 (Prompt Engineering for Science)
*目标：掌握与 AI 深度对话的语言，精确控制输出质量。*

| 序号 | 知识点 | 核心内容 | 模版资源 | 进度 |
| :--- | :--- | :--- | :--- | :--- |
| 06 | **Few-shot** | 给 AI 给几个例子，它能完成更复杂的科研分类 | [小样本模版] | ⚪ |
| 07 | **CoT (思维链)** | 如何诱导 AI 进行逻辑推理而非直接给答案 | [推理链 Prompt] | ⚪ |
| 08 | **Role-play** | 将 AI 设定为审稿人、数学家或 Native Speaker | [身份预设库] | ⚪ |
| 09 | **Structured Prompt** | 使用 Markdown/JSON 编写高成功率的指令 | [结构化模版] | ⚪ |
| 10 | **Negative Prompt** | 逆向约束：如何防止 AI 使用陈词滥调 | [学术禁术表] | ⚪ |

### 🟡 Phase 3: 科研全流程提效 (Academic Workflow)
*目标：将 AI 嵌入文献、写作、投稿的每一个环节。*

| 序号 | 场景 | 核心内容 | 工具/脚本 | 进度 |
| :--- | :--- | :--- | :--- | :--- |
| 11 | **文献极速读** | 5分钟拆解一篇 CVPR/Nature 论文的核心贡献 | [阅读流脚本] | ⚪ |
| 12 | **论文深度润色** | 告别 ChatGPT 风格，写出地道的学术英语 | [润色指令集] | ⚪ |
| 13 | **Rebuttal 助手** | 逻辑化拆解审稿意见并自动生成回复初稿 | [回复模版] | ⚪ |
| 14 | **Abstract 逆向生成** | 根据正文核心数据反推高质量摘要 | [生成器] | ⚪ |
| 15 | **LaTeX/Markdown** | 公式排版、表格转换与参考文献格式自动化 | [转换工具] | ⚪ |

### 🔴 Phase 4: 代码、数据与可视化 (Coding & Visualization)
*目标：利用 AI 辅助数据处理、算法复现与论文绘图。*

| 序号 | 场景 | 核心内容 | 演示代码 | 进度 |
| :--- | :--- | :--- | :--- | :--- |
| 16 | **Python 绘图** | 用 AI 辅助绘制 Matplotlib/Seaborn 高级图表 | [绘图 Notebook]| ⚪ |
| 17 | **代码 Debug** | 报错信息一键修复与代码重构建议 | [Debug 案例] | ⚪ |
| 18 | **数据合成** | 实验样本不足？利用生成模型进行数据增强 | [增强算法] | ⚪ |
| 19 | **爬虫与清洗** | 自动化抓取 ArXiv 文献并整理至 Excel/Notion | [自动化脚本] | ⚪ |

### 🟣 Phase 5: 高阶 AI 应用 (Advanced AI for Science)
*目标：构建自己的科研知识库与自主智能体。*

| 序号 | 知识点 | 核心内容 | 项目展示 | 进度 |
| :--- | :--- | :--- | :--- | :--- |
| 20 | **RAG 基础** | 检索增强生成：基于你的 PDF 库搭建私有问答 AI | [RAG Demo] | ⚪ |
| 21 | **Graph RAG** | 复杂文献关系链挖掘：从知识图谱看领域演化 | [知识图谱] | ⚪ |
| 22 | **AI Agents** | 让 AI 自主搜索网页、总结前沿并生成周报 | [Agent 实战] | ⚪ |
| 23 | **模型微调预热** | 什么情况下科研人员需要 Fine-tune 自己的模型？| [微调指南] | ⚪ |


---

## 📂 仓库结构 (Structure)

```text
AI-For-Science-Notes/
├── notebooks/          # 核心代码演示 (.ipynb)
│   ├── day01_transformer.ipynb
│   └── ...
├── prompts/            # 科研专用提示词库 (.md)
│   ├── academic_polishing.md
│   └── data_analysis.md
├── references/         # 补充阅读材料与论文
├── requirements.txt    # 依赖包列表
└── README.md           # 你现在看到的这个文件
