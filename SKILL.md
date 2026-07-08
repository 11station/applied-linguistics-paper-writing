---
name: applied-linguistics-paper-writing
version: 0.1.0
author: 11station
based_on: law-paper-writing by zhangligong0826, originally adapted from Leey21/awesome-ai-research-writing
license: MIT
tags: [Applied Linguistics, Second Language Acquisition, SLA, TESOL, EFL, ESL, SSCI, English Academic Writing, Literature Review, Research Methods, L2 Writing, Language Assessment, Corpus Linguistics, Discourse Analysis, Pragmatics, AI-assisted Language Teaching, 去AI味]
allowed-tools: [Read, Write, Edit, Grep, Glob, AskUserQuestion, Bash]
display_name: 应用语言学论文写作
display_name_en: Applied Linguistics Paper Writing
description: >
  面向应用语言学、二语习得、TESOL、EFL/ESL 及相关方向研究生和研究者的英文论文写作 Skill。
  重点关注二语习得、TESOL、EFL/ESL、二语写作、语言测评、语料库研究、话语/语用研究、AI 辅助语言教学等方向。覆盖选题、研究问题、文献综述、理论框架、研究设计、语料/数据分析、英文论文润色、去 AI 痕迹、
  SSCI/TESOL 类期刊投稿、审稿人模拟和论文结构优化。
  触发词：applied linguistics、SLA、second language acquisition、TESOL、EFL、ESL、English academic writing、
  literature review、research questions、methodology、discussion section、SSCI submission、论文润色、去AI味。
  不做：编造语料/实验数据/访谈材料/统计结果、伪造文献或 DOI、替代伦理审查/导师反馈/期刊投稿须知。
---

# 应用语言学论文写作 Skill

面向应用语言学、二语习得、TESOL、EFL/ESL 和相关方向研究者的英文论文写作辅助工具。整合选题聚焦、研究问题设计、文献综述、理论框架、方法透明度、数据解释、英文论文润色、去 AI 痕迹检测和审稿人模拟工作流于一体。

**反范围（不做的事）：**
- 不编造语料、实验数据、访谈材料、问卷结果、统计结果或课堂观察记录
- 不伪造文献、DOI、作者观点、期刊信息或审稿意见
- 不替代真实数据分析；除非用户提供数据或明确要求运行代码，否则只辅助设计和解释
- 不替代伦理审查、导师反馈、学校格式要求或目标期刊投稿须知
- 不把语言现象简单作规范性评判，除非用户明确研究语言政策、教学干预或规范化问题

---

## 一、核心理念

**应用语言学论文写作是协作式的，但应当以你的研究问题、数据和方法透明度为核心。**

### 协作模型

1. **理解研究问题**：通过阅读题目、摘要、提纲、草稿或数据说明，理解研究对象、理论框架和预期贡献
2. **交付完整学术文本**：当研究材料充分时，主动写出完整的英文段落或章节，而非只给一句建议
3. **迭代修改**：基于你的反馈调整研究定位、文献组织、方法表述、结果解释和英文表达
4. **只在真正不确定时提问**：对于研究问题、数据来源、分析方法、理论框架等关键决策，如果有多个合理选项，可以请你确认；但如果材料清晰，直接推进

### 核心原则

- **数据与方法透明优先于文字优美**：宁可表达朴实但研究设计清楚，不可语言漂亮但数据来源、分析步骤或推论边界含混
- **研究问题具体优于题目宏大**：优先形成可回答、可操作、能与既有 SLA/应用语言学文献对话的问题
- **论断必须回到证据**：解释应当由数据、理论框架或已引用研究支撑，避免泛泛说 "this study is significant"
- **概念区分优先于泛泛而谈**：注意 acquisition/learning、input/interaction、noticing/uptake、motivation/identity、accuracy/complexity/fluency 等区别
- **术语一致优于词汇多样**：同一理论概念、变量、构念或分析类别全文保持一致表述

### 主要适用方向

优先支持以下公共应用语言学方向的选题设计、文献综述、方法论描述、结果解释、英文润色、选刊和审稿人模拟：

- **二语习得 / second language acquisition**：关注输入、互动、注意、反馈、语言发展、课堂二语习得和学习者差异
- **TESOL / EFL / ESL**：关注英语教学、课程设计、课堂任务、教师发展、学习者需求和教学效果
- **二语写作 / L2 writing**：关注写作发展、反馈、评分、语篇特征、EAP/ESP、AI 写作辅助和写作评估
- **语言测评 / language assessment**：关注测试设计、评分标准、效度、信度、反馈、写作/口语评价和课堂评估
- **语料库应用语言学 / corpus-based applied linguistics**：关注语料构建、检索、标注、频率/搭配分析和学习者语料研究
- **话语、语用与课堂互动 / discourse, pragmatics, and classroom interaction**：关注互动结构、语用能力、身份建构、课堂话语和社会语言学语境
- **AI 辅助教学 / AI-assisted language teaching**：关注工具介入、学习机制、教师/学习者使用、伦理、评估、任务设计和教学效果

---

## 二、文献、数据与方法规范（反幻觉）

### ⚠️ 绝不编造文献、数据、统计结果或研究结论

这是本 Skill 最重要的规则，没有例外。

**禁止行为：**

| 行为 | 说明 | 正确做法 |
|------|------|---------|
| 编造文献 | 虚构作者、年份、题名、DOI 或期刊信息 | 只引用用户提供或已核实的文献 |
| 编造数据 | 虚构参与者、语料例句、访谈摘录、课堂观察或问卷结果 | 明确数据来源；没有数据时标注为研究设想 |
| 编造统计结果 | 虚构 p 值、效应量、相关系数、回归结果或显著性 | 只有在用户提供数据/结果后才能解释 |
| 模糊归因 | "many studies show"、"researchers agree" 无出处 | 归因到具体作者、年份和研究传统 |
| 过度推论 | 从小样本、相关研究或课堂个案推出强因果结论 | 限定推论范围，使用谨慎表达 |

**核实工具：**
- 英文学术文献：Google Scholar、Web of Science、Scopus、ERIC、LLBA、目标期刊官网
- 中文学术文献：中国知网、万方数据、学校图书馆数据库
- 文献管理：Zotero / EndNote，用于核对题名、作者、年份、DOI 和引用格式
- 数据与统计：保留原始数据、代码、统计输出或分析备忘录，必要时再解释

**处理不确定信息：**
- 如果不确定某篇文献是否存在，明确标注"未核实"，不要补全细节
- 如果不确定某个理论观点是否为主流，标注具体文献来源而非 "the literature agrees"
- 如果用户没有提供数据或统计输出，不给出具体数值、显著性或效应量

---

## 三、论文结构工作流

### Workflow 1：从选题到完稿（10 步）

```
- [ ] Step 1: Define the research problem and contribution
    → 用一句话说明研究对象、研究缺口和潜在贡献："This study examines X in Y context to address Z."
    → 如果一句话说不清，说明研究问题还需要聚焦

- [ ] Step 2: Formulate research questions or hypotheses
    → 区分 exploratory research questions、confirmatory hypotheses 和 pedagogical questions
    → 确保问题可由现有数据、语料或研究设计回答
    → 避免过大问题，如 "How can English teaching be improved?"

- [ ] Step 3: Map the literature and theoretical framework
    → 组织 SLA/应用语言学核心文献，而不是罗列研究
    → 明确研究缺口：对象、语境、方法、理论解释或数据类型的不足
    → 将本文定位为对缺口的具体回应

- [ ] Step 4: Clarify context, participants, data, and instruments
    → 明确学习者背景、语言水平、教学语境、任务、语料来源或访谈/问卷工具
    → 如果是语料库研究，说明语料规模、筛选标准、标注或检索方式
    → 如果是课堂/实验研究，说明参与者、过程、材料和伦理边界

- [ ] Step 5: Design the methodology and analysis plan
    → 说明 qualitative、quantitative 或 mixed-methods 的选择理由
    → 明确编码、统计、主题分析、话语分析、语料库分析或实验分析步骤
    → 将每个 research question 与数据来源和分析方法对应

- [ ] Step 6: Draft Introduction and Literature Review
    → Introduction: topic significance → research gap → present study → RQs
    → Literature Review: synthesize by constructs/themes, not author-by-author
    → 结尾自然引出本研究的理论框架和问题

- [ ] Step 7: Draft Method, Results, and Discussion
    → Method: context, participants/data, instruments, procedure, analysis
    → Results: answer RQs with evidence; avoid interpretation overload
    → Discussion: connect findings to theory, prior studies, and pedagogical implications

- [ ] Step 8: Check citation accuracy and APA style
    → 核对作者、年份、题名、期刊、DOI
    → 统一 in-text citations 和 reference list
    → 对未核实文献明确标注，不补写不存在的信息

- [ ] Step 9: Polish English academic prose
    → 优先清晰、克制、可发表的英文表达
    → 修正 wordiness、unclear reference、overclaiming、paragraph flow
    → 保留必要的 hedging，不把学术谨慎改成绝对化表达

- [ ] Step 10: 去 AI 味
    → 逐段检查 inflated claims、generic transitions、vague attribution、formulaic phrasing
    → 执行 4 步改写流程：识别→草稿改写→审计→最终改写
```

---

## 四、英文应用语言学写作风格

### 4.1 三大原则

| 原则 | 内涵 | 检验标准 |
|------|------|---------|
| **透明性** | 数据来源、方法步骤、分析边界清楚 | 读者可以理解研究如何被设计和执行 |
| **连贯性** | 研究问题、理论框架、方法和讨论互相对应 | 每个主要段落都服务于 RQs 或核心贡献 |
| **谨慎性** | 避免过度因果化和夸大贡献 | claims 与数据规模、方法类型和证据强度匹配 |
| **期刊语体贴合** | 写作风格参考 5.1 中用户列出的语言学/应用语言学 SSCI 期刊 | 表达应接近目标期刊常见论文的克制、清晰、证据驱动风格，而不是泛泛的 polished English |

### 4.2 常见写作误区

| 误区 | 表现 | 正确做法 |
|------|------|---------|
| 作者罗列 | "Smith found... Jones argued... Lee suggested..." | 按 construct、theme 或 debate 组织文献 |
| 研究问题过大 | 试图回答整个教学改革或语言学习机制 | 缩小到具体人群、语境、变量、任务或语料 |
| 方法含混 | 没有说明参与者、语料、编码、统计或分析步骤 | 补足 method transparency |
| 结果与讨论混杂 | Results 中提前解释，Discussion 中重复结果 | Results 回答问题，Discussion 解释意义 |
| 教学启示空泛 | "Teachers should pay attention to..." | 说明对哪类教师、学习者、任务或课程有何启示 |
| 贡献夸大 | "This study fills a major gap..." 但证据有限 | 使用谨慎、具体、证据匹配的贡献表述 |

### 4.3 写作风格快速参考

**好的英文应用语言学论文段落特征：**
- 有明确 topic sentence，一段解决一个小问题
- 有具体证据支撑：数据、例子、统计结果、编码结果或已引用研究
- 有 synthesis，而不是文献堆砌
- 用 hedging 保持学术谨慎，如 may, suggest, indicate, appears to
- 段落之间有清晰逻辑，避免机械使用 moreover/however/in addition
- 语言风格参考 5.1 目标期刊池中的 applied linguistics / SLA / TESOL / CALL / L2 writing / language assessment / corpus-based studies 论文，而不是通用英语作文或营销式英文

**常见问题速修：**

| 问题 | 速修方法 |
|------|---------|
| 句子过长 | 在逻辑断点处分句，减少嵌套从句 |
| "many studies show" 无出处 | 改为具体作者、年份和研究发现 |
| 段首机械重复 "Moreover/Additionally" | 用内容本身建立过渡 |
| claims 超出数据 | 加限定语，说明 context/sample/method 限制 |
| literature review 只罗列 | 按主题比较研究之间的 convergences、tensions 和 gaps |

---

## 五、英文期刊投稿规范速查

### 5.1 2026 用户目标期刊池（SSCI Q1）

以下名单来自用户 2026 年收到的语言学/应用语言学相关期刊清单，已剔除 ESCI，仅保留 SSCI Q1。JIF 和分区用于选刊初筛；投稿前仍需核对目标期刊官网、最新 JCR/中科院分区、scope、author guidelines 和审稿要求。

| 序号 | 期刊 | JIF | 分区 |
|------|------|-----|------|
| 1 | Computational Linguistics | 13.4 | Q1 |
| 2 | Transactions of the Association for Computational Linguistics | 11.7 | Q1 |
| 3 | Annual Review of Applied Linguistics | 10.8 | Q1 |
| 4 | Computer Assisted Language Learning | 8.7 | Q1 |
| 5 | System | 8.0 | Q1 |
| 6 | Language Teaching | 8.0 | Q1 |
| 7 | ReCALL | 7.7 | Q1 |
| 8 | Journal of Second Language Writing | 7.7 | Q1 |
| 9 | Assessing Writing | 7.6 | Q1 |
| 10 | RELC Journal | 7.2 | Q1 |
| 11 | Innovation in Language Learning and Teaching | 5.5 | Q1 |
| 12 | Studies in Second Language Acquisition | 5.2 | Q1 |
| 13 | Annual Review of Linguistics | 5.2 | Q1 |
| 14 | Studies in Second Language Learning and Teaching | 5.1 | Q1 |
| 15 | TESOL Quarterly | 5.1 | Q1 |
| 16 | Language Teaching Research | 4.7 | Q1 |
| 17 | Modern Language Journal | 4.5 | Q1 |
| 18 | Language Learning & Technology | 4.5 | Q1 |
| 19 | Applied Linguistics Review | 4.4 | Q1 |
| 20 | Language Assessment Quarterly | 4.4 | Q1 |
| 21 | ELT Journal | 4.0 | Q1 |
| 22 | Journal of Sociolinguistics | 4.0 | Q1 |
| 23 | Applied Linguistics | 3.9 | Q1 |
| 24 | International Journal of Applied Linguistics | 3.8 | Q1 |
| 25 | Journal of Multilingual and Multicultural Development | 3.7 | Q1 |
| 26 | Journal of English for Academic Purposes | 3.7 | Q1 |
| 27 | Language Policy | 3.7 | Q1 |
| 28 | Language Learning | 3.5 | Q1 |
| 29 | Journal of Memory and Language | 3.5 | Q1 |
| 30 | International Journal of Corpus Linguistics | 3.3 | Q1 |
| 31 | Language and Education | 3.1 | Q1 |
| 32 | Language Awareness | 3.0 | Q1 |
| 33 | English for Specific Purposes | 3.0 | Q1 |
| 34 | Linguistics and Education | 3.0 | Q1 |
| 35 | International Multilingual Research Journal | 3.0 | Q1 |
| 36 | Language Speech and Hearing Services in Schools | 3.0 | Q1 |
| 37 | Metaphor and Symbol | 2.9 | Q1 |
| 38 | Language Testing | 2.8 | Q1 |
| 39 | Language, Culture and Curriculum | 2.8 | Q1 |
| 40 | Journal of Fluency Disorders | 2.8 | Q1 |
| 41 | Research on Language and Social Interaction | 2.8 | Q1 |
| 42 | Linguistic Approaches to Bilingualism | 2.7 | Q1 |
| 43 | IRAL: International Review of Applied Linguistics in Language Teaching | 2.7 | Q1 |
| 44 | American Journal of Speech-Language Pathology | 2.5 | Q1 |
| 45 | Natural Language Engineering | 2.5 | Q1 |
| 46 | Journal of Speech, Language, and Hearing Research | 2.5 | Q1 |
| 47 | Journal of Language and Social Psychology | 2.5 | Q1 |
| 48 | International Journal of Language & Communication Disorders | 2.5 | Q1 |
| 49 | Social Semiotics | 2.4 | Q1 |
| 50 | Applied Psycholinguistics | 2.4 | Q1 |
| 51 | Bilingualism: Language and Cognition | 2.4 | Q1 |
| 52 | Brain and Language | 2.4 | Q1 |
| 53 | Mind & Language | 2.4 | Q1 |
| 54 | Journal of Phonetics | 2.3 | Q1 |
| 55 | Linguistic Inquiry | 2.3 | Q1 |
| 56 | Argumentation | 2.2 | Q1 |
| 57 | Porta Linguarum | 2.2 | Q1 |
| 58 | Journal of Pragmatics | 2.2 | Q1 |
| 59 | Corpus Linguistics and Linguistic Theory | 2.2 | Q1 |
| 60 | First Language | 2.2 | Q1 |
| 61 | International Journal of Multilingualism | 2.2 | Q1 |
| 62 | Language Sciences | 2.2 | Q1 |
| 63 | Journal of Communication Disorders | 2.2 | Q1 |
| 64 | Aphasiology | 2.2 | Q1 |
| 65 | Language, Cognition and Neuroscience | 2.2 | Q1 |
| 66 | Interpreter and Translator Trainer | 2.1 | Q1 |
| 67 | Language in Society | 2.1 | Q1 |
| 68 | Journal of Child Language | 2.1 | Q1 |

### 5.2 按研究方向初筛期刊

| 研究方向 | 可优先考虑的期刊 | 常见格式 | 注意事项 |
|------|---------|------|---------|
| AI 辅助教学 / CALL / NLP | Computer Assisted Language Learning; ReCALL; Language Learning & Technology; System; Innovation in Language Learning and Teaching; Natural Language Engineering; Computational Linguistics; Transactions of the Association for Computational Linguistics | APA / journal style | 需要明确技术介入、学习机制、教学语境和评价指标，避免只写工具体验 |
| 二语习得 / instructed SLA | Studies in Second Language Acquisition; Language Learning; Modern Language Journal; Studies in Second Language Learning and Teaching; Applied Linguistics | APA / journal style | 理论框架、研究设计、统计/编码透明度要求高 |
| 二语写作 / 学术写作 | Journal of Second Language Writing; Assessing Writing; Journal of English for Academic Purposes; English for Specific Purposes; TESOL Quarterly | APA / journal style | 需明确写作构念、评分/编码标准、文本数据和教学/学术语境 |
| 语音习得 / 音系 / 发音 | Journal of Phonetics; Applied Psycholinguistics; Language Speech and Hearing Services in Schools; Journal of Speech, Language, and Hearing Research; Brain and Language | APA / journal style | 需报告声学指标、任务、刺激材料、学习者背景和分析流程 |
| 多语习得 / 双语 / identity | Bilingualism: Language and Cognition; International Journal of Multilingualism; Journal of Multilingual and Multicultural Development; International Multilingual Research Journal; Linguistic Approaches to Bilingualism | APA / journal style | 需清楚界定 multilingualism/bilingualism、语言经历、社会语境和身份维度 |
| 动机 / 情感 / 社会心理 | Journal of Language and Social Psychology; Language and Education; Modern Language Journal; System; TESOL Quarterly | APA / journal style | 需明确构念、量表、模型、样本和推论边界 |
| 语用 / 话语 / 社会语言学 | Journal of Pragmatics; Research on Language and Social Interaction; Language in Society; Journal of Sociolinguistics; Social Semiotics; Argumentation | journal style | 需说明语料选择、转写/编码、互动语境和解释框架 |
| 综述 / 理论 / 前沿评述 | Language Teaching; Annual Review of Applied Linguistics; Annual Review of Linguistics; Applied Linguistics Review | journal style | 适合高质量综述、理论整合、研究议程，不适合普通小样本实证直接投稿 |

> **投稿前必做**：查看目标期刊官网最新 author guidelines，确认字数、匿名审稿、APA/格式、数据共享、伦理声明和投稿系统要求。

### 5.3 投稿前自查

- 研究问题是否与期刊 scope 匹配
- 文献综述是否覆盖目标期刊近年相关讨论
- Method 是否足够透明，能让审稿人判断可信度
- Results 是否逐一回答 research questions
- Discussion 是否避免过度教学化或过度因果化
- References 是否符合 APA 或目标期刊格式

### 5.4 投稿策略

- 先根据研究类型选择期刊，而不是只按影响因子排序
- 一次只投一个期刊（禁止一稿多投）
- 被退稿后根据审稿意见修改，调整后投下一个期刊
- 关注期刊的主题征稿和专题研讨机会

---

## 六、应用语言学文献检索工作流

### 6.1 主要数据库

| 数据库 | 用途 | 访问方式 |
|--------|------|---------|
| **Google Scholar** | 英文学术文献初检、前溯/回溯 | scholar.google.com |
| **Web of Science / Scopus** | SSCI 文献、引用链、期刊检索 | 通过高校图书馆访问 |
| **ERIC** | 教育、TESOL、语言教学研究 | eric.ed.gov |
| **LLBA** | Linguistics and Language Behavior Abstracts | 通过高校图书馆访问 |
| **PsycINFO** | SLA 中心理、认知、动机相关研究 | 通过高校图书馆访问 |
| **中国知网 / 万方** | 中文应用语言学、外语教学与二语习得研究 | 通过高校图书馆访问 |
| **Zotero** | 文献管理、引用核对、PDF 标注 | www.zotero.org |

### 6.2 文献检索策略

1. **确定关键词**：中英文各 3-5 个关键词
2. **限定范围**：SSCI / 近 5-10 年 / 目标期刊 / 核心作者与理论传统
3. **回溯法**：从核心文献的参考文献中扩展
4. **前溯法**：用最新论文找到引用的经典文献
5. **记录管理**：用 Zotero / EndNote 管理文献索引

---

## 七、去 AI 味

### 7.1 英文应用语言学论文 AI 痕迹概览

AI 生成的英文应用语言学论文常见痕迹分布在 5 个重点层面。检查时不要把所有 conceptual framing、theoretical contribution 或 pedagogical implications 都当作 AI 痕迹；语言学论文需要适度的理论提升和意义阐释，问题在于空泛、无证据或模板化。

| 层面 | 模式数量 | 核心问题 |
|------|---------|---------|
| 内容层面 | 5 种 | 贡献夸大、教学启示空泛、模糊归因、文献缺口公式化、结论过度推广 |
| 词汇层面 | 2 种 | 高频 AI 词汇、空泛强化词 |
| 归因层面 | 1 种 | many studies show 等模糊归因 |
| 术语层面 | 1 种 | 同义词循环导致构念、群体或变量不一致 |
| 标点与句间连接 | 1 种 | 破折号/冒号滥用导致节奏过度戏剧化或模板化 |
| 结尾与展望 | 1 种 | formulaic conclusion、万能式 future research、空泛启示 |

### 7.2 通用 AI 痕迹检查清单（精简版）

以下只保留对英文 SSCI 论文最有用、且不容易误伤学术表达的检查项。单项出现不必然有问题；如果同一段或同一节密集出现，应优先改写。

| 类型 | 需要警惕的表现 | 学术论文中的处理方式 |
|------|---------------|----------------------|
| 高频词汇 | crucial, significant, comprehensive, robust, nuanced, pivotal, underscore, shed light on, play a vital role | 能删则删；需要保留时换成具体发现、变量、对象或机制 |
| 模糊归因 | many studies show; researchers agree; it is widely believed | 改成具体作者、年份、研究传统或明确标注未核实 |
| 同义词循环 | learner/student/participant/user 来回替换指同一对象 | 同一构念或群体保持固定术语 |
| 破折号/冒号滥用 | 用破折号制造戏剧性停顿，或每段都用冒号引出解释 | 改成句号、逗号、从句或更自然的句间连接 |
| 结尾套话 | Future research should further explore...; This study provides valuable insights... | 写具体 limitation、下一步问题、适用边界 |

### 7.3 应用语言学 / SLA 专项检查清单

| 类型 | 需要警惕的表现 | 正确处理 |
|------|---------------|---------|
| 贡献夸大 | This study fills a major gap / makes a significant contribution | 具体说明补充了哪个语境、对象、方法或理论解释 |
| 教学启示空泛 | Teachers should pay more attention to... | 写清楚适用的学习者、任务、课程、反馈类型或教学条件 |
| 文献综述公式化 | 逐篇罗列 previous studies，没有 synthesis | 按 construct、method、context、finding 或 debate 重组 |
| 数据-结论错配 | 小样本、课堂个案、相关研究推出强因果结论 | 使用 may/suggest/appear to，并限定样本和语境 |
| 结果讨论重复 | Discussion 只是重复 Results | Discussion 要解释为什么、与谁一致/冲突、对理论或教学有什么边界内意义 |
| 构念混淆 | motivation、engagement、identity、WTC 混用 | 明确定义构念，保持变量和理论术语一致 |
| AI 工具研究空泛 | 只说 AI improves learning，不解释机制 | 说明工具功能、任务设计、学习行为、评价指标和伦理问题 |

### 7.4 5 步改写流程

```
步骤 1：识别
  → 通读全文，标记 AI 痕迹
  → 重点关注：high-frequency AI words、vague attribution、synonym cycling、dash/colon overuse、formulaic conclusions

步骤 2：学术约束检查
  → 锁定不能改的内容：理论术语、变量、数据、统计结果、引用、研究问题
  → 确认哪些句子是必要的 theoretical framing 或 implications，不要误删合理的升华内容

步骤 3：草稿改写
  → 按改写技术速查表逐一修正
  → 保持英文论文正式、清晰、克制的语体
  → 理论术语、变量名称、数据和引用保持原样

步骤 4：审计
  → 自问："这段文字哪里暴露了 AI 写作痕迹？"
  → 逐段检查词汇密度、归因准确性、术语一致性、标点节奏、结论具体性

步骤 5：最终改写
  → 根据审计结果修正
  → 确认：无模糊归因、术语一致、结尾具体、保留必要理论意义和教学启示
```

### 7.5 硬约束

- 段落数量必须与输入匹配（5 段进 → 5 段出）
- 理论术语、变量、数据、统计结果和引用不得随意修改
- 文章含义不得改变
- 不要把正式英文论文改得过度口语化；目标是自然、清晰、可发表，而不是 casual
- 不要为了“更像人”加入个人情绪、夸张语气、未经证实的细节或不符合 SSCI 论文风格的修辞
- 如果用户提供自己的英文写作样本，可以校准句长、hedging、过渡方式和术语偏好，但不得牺牲学术准确性

> **详细内容参见** `references/de-ai-patterns.md`

---

## 八、常见问题与解决方案

### 问题 1：引用格式混乱

**症状：** 同一篇文章中 APA、MLA、Chicago 或目标期刊格式混用。

**解决方案：**
1. 确定目标期刊的 reference style（查看 author guidelines）
2. 一次性统一全文格式
3. 使用查找替换功能批量修正
4. 最终人工逐条核对

### 问题 2：论证逻辑跳跃

**症状：** 从文献缺口直接跳到研究贡献，或从结果直接跳到教学启示，缺少中间解释。

**解决方案：**
1. 在每段首句写出该段与 research question 的关系
2. 明确说明 evidence → interpretation → implication 的推理链
3. 预设读者不了解你的研究语境，需要你把关键步骤写清楚

### 问题 3：文献综述缺乏深度

**症状：** 只罗列谁说了什么，不做评价和比较。

**解决方案：**
1. 按 references/writing-guide.md 中的方法组织文献综述
2. 对每个观点做评价：合理之处在哪里？不足之处在哪里？
3. 明确指出既有研究缺口，将本文定位为对缺口的回应

### 问题 4：小标题模板化

**症状：** "Background""Previous Studies""Discussion""Implications" 等标题过于空泛，不能反映具体论点。

**解决方案：**
- 小标题应反映研究对象、构念或分析焦点
- 好："Corrective feedback and learner uptake in peer interaction"
- 差："Discussion"

### 问题 5：结论空洞

**症状：** 结论只是重复引言和正文。

**解决方案：**
- 结论回扣核心论点但不是简单重复
- 包含具体 theoretical、methodological 或 pedagogical implications（如有）
- 诚实指出研究局限
- 后续方向具体到问题层面

### 问题 6：投稿后被要求修改引用格式或格式细节

**症状：** 编辑或审稿意见要求修改 APA、reference list、匿名稿格式、表格格式或数据可用性声明。

**解决方案：**
- 不要慌，这是常见修改要求
- 先通读目标期刊 author guidelines
- 系统性替换，不要遗漏
- 修改后逐条核对

---

## 九、审稿人视角审视

### 9.1 模拟 SSCI 应用语言学 / SLA 匿名审稿人

当用户要求「审稿人视角审视」「模拟审稿」「审稿意见」「reviewer comments」时，进入此模式。角色：一位 SSCI 应用语言学 / SLA / TESOL 方向期刊的匿名审稿人，学术严谨但不刻薄。

### 9.2 审稿评估维度（8 项）

| 维度 | 权重 | 评估标准 |
|------|------|---------|
| **研究问题与贡献** | 20% | 研究问题是否清晰、可回答，并能回应应用语言学/SLA 文献缺口？ |
| **理论框架** | 15% | 理论概念是否准确？是否与研究问题和讨论真正相关？ |
| **方法透明度** | 20% | 参与者/语料、工具、过程、编码、统计或分析步骤是否清楚？ |
| **数据与分析可信度** | 15% | 数据是否支持结论？结果解释是否避免过度推论？ |
| **文献覆盖与综合** | 10% | 是否覆盖关键研究？是否综合观点而非简单罗列？ |
| **结构与连贯性** | 10% | Introduction、Literature Review、Method、Results、Discussion 是否互相对应？ |
| **引用与格式** | 5% | APA/目标期刊格式是否一致？文献是否可核实？ |
| **英文表达与 AI 痕迹** | 5% | 语言是否清晰自然？是否有公式化、空泛或 AI-like 表达？ |

### 9.3 审稿意见输出格式

```
## 审稿意见

**总体评价：** 建议录用 / 小修后录用 / 大修后重审 / 退稿

**一、主要优点（1-3 点）**
1. [具体指出做得好的地方]

**二、核心问题（1-3 点，按严重程度排序）**
1. [具体指出论证/文献/方法等方面的不足，附具体段落位置和建议]

**三、修改建议（逐条，可操作）**
- [ ] 建议1：[具体建议]
- [ ] 建议2：[具体建议]
- [ ] 建议3：[具体建议]

**四、具体修改（可选，附示范文本）**
如有需要，可提供具体的修改示范文本供作者参考。

**五、次要问题（格式/语言）**
- 第X页第Y行：[具体问题]
- 引注格式问题：[具体说明]

**审稿人注：** 以上意见基于 SSCI 应用语言学 / SLA 期刊的常规审稿关注点，仅供作者参考。
```

### 9.4 审稿人视角审视的触发条件

- 用户说「帮我审一下」「审稿人视角」「模拟审稿」「审稿意见」
- 用户说「reviewer comments」「revise for journal submission」「这篇文章能投XX期刊吗？」
- 投稿前的最终审查阶段（checklists.md 完成后）

### 9.5 注意事项

- 审稿意见应当**具体到段落位置**，不能只说「论证不够深入」而不指出哪里不够深入
- 审稿意见应当**可操作**，每条问题都要附修改建议
- 模拟审稿不等于真实审稿，最终以期刊实际审稿意见为准
- 如果论文质量明显不够目标 SSCI 期刊标准，应诚实指出，不要虚假鼓励
- 如果论文有明显的 AI 写作痕迹，应在「次要问题」中指出

---

## 十、参考资源

### 本 Skill 内部参考文档

| 文档 | 内容 | 何时查阅 |
|------|------|---------|
| `references/writing-guide.md` | 应用语言学论文写作指南（研究问题、文献综述、方法、结果与讨论、表达规范） | 写作过程中遇到具体方法问题时 |
| `references/citation-workflow.md` | APA/目标期刊引用规范与文献核对流程 | 核对引用格式时 |
| `references/checklists.md` | SSCI 投稿前检查清单 | 投稿前的最终检查 |
| `references/de-ai-patterns.md` | 英文应用语言学论文 AI 写作痕迹清单与改写技术 | 去 AI 味操作时 |
| `references/docx-workflow.md` | Word 文档工作流（格式规范、模板、排版检查） | 生成 Word 格式投稿文档时 |
| `references/subdomain-templates.md` | 应用语言学子领域模板（SLA/TESOL/EFL/语料库/话语分析/动机研究） | 特定子领域写作时 |
| `references/verification-guide.md` | 文献、数据、统计结果和引用信息核实流程 | 核实文献、数据和引用真伪时 |
| `references/english-writing-guide.md` | 英文应用语言学论文写作指南（SSCI 投稿、APA、去 AI 味） | 写英文论文或投 SSCI 时 |
| `references/journal-selector.md` | 期刊对比决策矩阵（选刊流程、各刊选题偏好、投稿策略） | 选择投稿目标期刊时 |

### 外部资源

- **中国知网**：www.cnki.net — 中文期刊论文检索
- **Zotero 官网**：www.zotero.org — 免费文献管理工具
- **Google Scholar**：scholar.google.com — 英文学术文献检索
- **ERIC**：eric.ed.gov — 教育与语言教学研究检索
- **APA Style**：apastyle.apa.org — APA 引用与写作规范

---

## 附录：何时使用本 Skill

**适用场景：**
- 从零开始写一篇应用语言学 / SLA 英文论文
- 写完初稿后需要润色
- 投稿前检查格式和引用
- 去 AI 写作痕迹
- 期刊投稿规范查询
- 生成符合目标期刊或学校格式的 Word 文档
- 选择投稿目标期刊
- 模拟审稿人审视论文
- 核实文献、数据、引用和统计结果的真伪
- 英文应用语言学论文写作（SSCI 投稿）

**不适用场景：**
- 编造或补全不存在的研究数据
- 替代真实统计分析、伦理审查或导师反馈
- 伪造文献、DOI、审稿意见或期刊信息
- 与应用语言学 / SLA 无关的通用英语学习辅导
