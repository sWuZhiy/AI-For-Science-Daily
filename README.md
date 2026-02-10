# 🔬 AI for Science Daily (科研AI每日一练)

AI for Science（AI+科研）日常学习笔记+实操代码

[![Python](https://img.shields.io/badge/python-3.8+-green.svg)](https://www.python.org/)
[![Zhihu](https://img.shields.io/badge/知乎-专栏链接-0084FF)](你的知乎专栏链接)（可替换）

## 📖 项目介绍
这是一个面向科研人员（Researcher/Student）的AI知识库，配套知乎专栏《[知乎专栏《AI 科研加速器》]》，旨在通过 **"每日一个知识点 + 代码实战"** 的形式，帮助大家理解大模型原理，并将其高效应用到论文写作、文献分析、数据处理和实验复现中。

**核心目标：** 让AI成为科研加速器，节省时间、提升效率、规避风险，适配科研人员无访问障碍使用需求。

**更新频率：** 每日/每周更新（可替换）
**配套专栏：** [点击跳转知乎专栏](你的知乎专栏链接)（可替换，核心引流入口）

## 🗂️ 内容导航 (Table of Contents)
| Day | Topic (主题) | 知乎文章 | Code (代码) | Tags |
| :--- | :--- | :--- | :--- | :--- |
| **01** | Transformer 原理详解 | [点击阅读](Day01知乎文章链接)（可替换） | [Notebook](./Day01_Transformer/) | `NLP` `Architecture` |
| **02** | Tokenization 分词机制 | [点击阅读](Day02知乎文章链接)（可替换） | [Script](./Day02_Tokenization/) | `Preprocessing` |
| **03** | RAG 检索增强生成 | [点击阅读](Day03知乎文章链接)（可替换） | [Demo](./Day03_RAG/) | `Application` |
| ... | ... | ... | ... | ... |（后续Day逐步补充，可替换）

## 🛠️ 如何使用
### 方法一：本地运行（适合有Python环境的用户）
1. Clone 本仓库：
   ```bash
   git clone https://github.com/你的用户名/AI-For-Science-Daily.git（可替换）
   ```
2. 进入仓库目录：
   ```bash
   cd AI-For-Science-Daily
   ```
3. 安装依赖：
   ```bash
   pip install -r requirements.txt
   ```
4. 运行对应文件夹下的Jupyter Notebook或Python脚本。

### 方法二：云端运行（无需配置环境，中国大陆直接访问）
选用2款适配科研场景的中国大陆云端平替（二选一即可，均支持Jupyter Notebook、免费可用）：
1.  豆包编程（优先推荐）：打开豆包编程（https://dbcoding.ai-kit.cn/），点击「导入GitHub仓库」，粘贴本仓库地址，即可一键加载所有Notebook并运行，支持AI代码解释、调试，贴合科研编程需求。
2.  百度飞桨AI Studio：打开AI Studio（https://aistudio.baidu.com/），注册登录后，点击「导入项目」→「GitHub导入」，粘贴对应Day的Notebook链接，即可免费运行，支持GPU加速（适合深度学习相关代码）。
👉 所有Day的云端运行链接汇总：[Cloud_Links.md](./Cloud_Links.md)（可直接点击跳转，无需手动粘贴）

## 🤝 参与贡献
如果你发现代码有Bug、有更好的Prompt技巧，或想补充某一学科的AI应用案例，欢迎提交 **Pull Request** 或 **Issue**。让我们一起构建最实用的科研AI社区！

## 📌 加分技巧
1. 所有代码均经过测试，可直接运行，若遇到版本兼容问题，可参考requirements.txt中的版本说明。
2. Notebook中包含详细的代码注释和原理说明，适合边看边学。
3. 定期更新依赖包，确保代码适配最新版本的AI库（如Transformers、Torch等）及云端平台（豆包编程/AI Studio）。
4. 豆包编程支持圈选代码AI解释、优化，科研中遇到代码调试难题可直接使用该功能提升效率。

## 👤 关于作者
* **知乎：** [你的知乎名称](你的知乎个人主页链接)（可替换）
* **研究方向：** [你的研究领域]（可替换，增强科研可信度）
* **GitHub：** [你的GitHub主页链接]（可替换）

## ⚠️ 注意事项
1. 本项目仅用于科研学习，请勿用于商业用途。
2. 科研过程中，需坚持「Human-in-the-loop」（人在回路），仔细核实AI生成的代码、文本和数据，避免学术不端。
3. 请勿上传未发表的实验数据、核心代码到公有平台，保护科研成果。
4. 使用云端平台时，建议优先选择私有项目模式，保护个人科研代码隐私。

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
