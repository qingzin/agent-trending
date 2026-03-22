# AI agents 2025年11月学术分类汇总

共收录 633 篇论文，按研究方向分类整理如下。

## 目录

- [Agent记忆与知识管理（22篇）](#cat-01)
- [基于Agent的应用系统（135篇）](#cat-02)
- [多Agent协作与通信（63篇）](#cat-03)
- [Agent学习与自进化（37篇）](#cat-04)
- [多Agent强化学习（69篇）](#cat-05)
- [Agent架构与框架设计（58篇）](#cat-06)
- [Agent评测与基准（48篇）](#cat-07)
- [Agent工具使用与环境交互（28篇）](#cat-08)
- [Agent安全与对齐（70篇）](#cat-09)
- [人机协作Agent（22篇）](#cat-10)
- [Agent规划与推理（22篇）](#cat-11)
- [Agent仿真与社会模拟（26篇）](#cat-12)
- [具身智能Agent（23篇）](#cat-13)
- [Agent可解释性与透明度（6篇）](#cat-14)
- [低代码/无代码Agent平台（4篇）](#cat-15)

<a id="cat-01"></a>

## Agent记忆与知识管理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2511.13410v2 | Mem-PAL: Towards Memory-based Personalized Dialogue Assistants for Long-term User-Agent Interaction | 提出 H^2Memory 分层异构记忆框架，结合检索增强生成 | 长期交互中用户特征捕捉难，响应缺乏个性化 | 长期用户 - 代理交互对话助手 |
| 2 | http://arxiv.org/abs/2511.13593v3 | O-Mem: Omni Memory System for Personalized, Long Horizon, Self-Evolving Agents | 基于主动用户画像的动态记忆提取与更新机制 | 现有记忆系统依赖语义分组，易遗漏关键信息 | 个性化长周期自进化智能体 |
| 3 | http://arxiv.org/abs/2511.21730v1 | A Benchmark for Procedural Memory Retrieval in Language Agents | 首个隔离程序记忆检索的基准，评估跨上下文迁移 | 解决嵌入方法在新词汇任务上泛化能力差的问题 | 语言代理程序记忆 |
| 4 | http://arxiv.org/abs/2511.17208v2 | A Simple Yet Strong Baseline for Long-Term Conversational Memory of LLM Agents | 基于事件语义的对话记忆，组织为异构图支持关联 recall | 解决固定上下文窗口限制及外部记忆碎片化问题 | 长期对话代理 |
| 5 | http://arxiv.org/abs/2511.17775v1 | Episodic Memory in Agentic Frameworks: Suggesting Next Tasks | 存储检索过去工作流，匹配当前序列推荐下一步 | 解决仅靠 LLM 推荐下一步易幻觉及需微调问题 | 科学工作流 Agent |
| 6 | http://arxiv.org/abs/2512.01089v1 | CodeDistiller: Automatically Generating Code Libraries for Scientific Coding Agents | 自动蒸馏科学 Github 仓库为 vetted 库，扩展 ASD 代理能力无需手动努力 | 解决自动科学发现系统受限于仅从参数知识生成可靠代码的问题 | 科学编码 Agent |
| 7 | http://arxiv.org/abs/2511.21678v1 | Agentic Learner with Grow-and-Refine Multimodal Semantic Memory | 双流连记忆框架，分离视觉干扰与逻辑错误编码 | 轨迹记忆存在 brevity bias 且缺乏多模态整合 | 多模态问题解决智能体 |
| 8 | http://arxiv.org/abs/2511.22729v1 | Solving Context Window Overflow in AI Agents | 从原始数据转向内存指针，处理任意长度工具响应 | 大工具输出溢出上下文窗口，截断导致信息丢失 | 化学与材料科学工作流 |
| 9 | http://arxiv.org/abs/2511.20297v1 | Improving Language Agents through BREW | 基于经验学习知识库构建与优化的 Agent 框架 | Agent 策略难解释适应且训练开销高 | 语言 Agent 优化 |
| 10 | http://arxiv.org/abs/2511.20857v1 | Evo-Memory: Benchmarking LLM Agent Test-time Learning with Self-Evolving Memory | 自进化记忆基准与框架支持测试时学习 | 静态记忆无法适应动态任务流 | LLM Agent 记忆 |
| 11 | http://arxiv.org/abs/2511.18423v1 | General Agentic Memory Via Deep Research | 提出通用智能体记忆框架，采用即时编译原则优化上下文。 | 解决静态记忆导致的信息丢失问题。 | 通用 AI 智能体 |
| 12 | http://arxiv.org/abs/2511.19192v1 | AME: An Efficient Heterogeneous Agentic Memory Engine for Smartphones | 端侧异构智能体记忆引擎，协同设计手机 SoC 与向量数据库。 | 解决现有向量数据库不适配移动端约束与工作负载的问题。 | 移动端/智能体记忆 |
| 13 | http://arxiv.org/abs/2511.12960v2 | ENGRAM: Effective, Lightweight Memory Orchestration for Conversational Agents | 三类型记忆（情景/语义/程序）通过单路由检索器组织 | 当代记忆系统架构复杂、工程难度高、复现困难 | 长程对话Agent |
| 14 | http://arxiv.org/abs/2511.01912v2 | EvoMem: Improving Multi-Agent Planning with Dual-Evolving Memory | 提出双演化记忆机制（约束记忆与查询反馈记忆），协调多智能体规划 | 解决多智能体规划中记忆机制缺失及迭代推理协调难的问题 | 多智能体规划任务（如行程、会议规划） |
| 15 | http://arxiv.org/abs/2511.01448v2 | LiCoMemory: Lightweight and Cognitive Agentic Memory for Efficient Long-Term Reasoning | 提出 CogniGraph 轻量层级图，时序与层级感知搜索提升检索效率 | 解决外部记忆结构扁平纠缠导致检索冗余及效率下降的问题 | 长程对话与推理任务 |
| 16 | http://arxiv.org/abs/2511.08301v1 | Smarter Together: Creating Agentic Communities of Practice through Shared Experiential Learning | Spark共享记忆架构模拟开发者社区 | AI编码Agent缺乏共享学习知识库 | 软件开发Agent协作学习 |
| 17 | http://arxiv.org/abs/2511.09127v1 | History-Aware Reasoning for GUI Agents | HAR框架增强GUI Agent短期记忆与历史感知 | 现有GUI Agent缺乏历史交互感知能力 | 长程GUI自动化任务 |
| 18 | http://arxiv.org/abs/2511.06179v1 | MemoriesDB: A Temporal-Semantic-Relational Database for Long-Term Agent Memory / Modeling Experience as a Graph of Temporal-Semantic Surfaces | 时间-语义-关系统一数据库架构 | Agent长期记忆中时间、意义、关系去相干问题 | Agent长期记忆存储与检索 |
| 19 | http://arxiv.org/abs/2511.07800v1 | From Experience to Strategy: Empowering LLM Agents with Trainable Graph Memory | 可训练多层图记忆框架，强化权重优化 | LLM经验利用隐式记忆遗忘、显式记忆缺乏适应性 | LLM Agent战略推理与经验利用 |
| 20 | http://arxiv.org/abs/2511.02371v1 | LUMA-RAG: Lifelong Multimodal Agents with Provably Stable Streaming Alignment | 流式多层记忆系统与跨模态对齐桥，保证检索稳定。 | 多模态流式数据索引更新成本高、一致性难。 | 生产级多模态 RAG 系统 |
| 21 | http://arxiv.org/abs/2511.02919v1 | Cache Mechanism for Agent RAG Systems | 动态管理高价值语料缓存，减少存储与延迟。 | Agent 级缓存管理未被充分探索。 | RAG 驱动的 LLM  Agent |
| 22 | http://arxiv.org/abs/2511.03506v3 | HaluMem: Evaluating Hallucinations in Memory Systems of Agents | 操作级幻觉评估基准，定位记忆系统幻觉阶段。 | 现有评估难以定位记忆系统幻觉来源。 | Agent 记忆系统评估 |

[返回目录](#目录)

<a id="cat-02"></a>

## 基于Agent的应用系统

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2511.13476v1 | Multi-Agent Multimodal Large Language Model Framework for Automated Interpretation of Fuel Efficiency Analytics in Public Transportation | 多智能体框架协调数据叙事与能量洞察生成 | 传统分析输出碎片化，需大量人工解释 | 公共交通燃料效率分析 |
| 2 | http://arxiv.org/abs/2511.13860v1 | Randomized Controlled Trials for Phishing Triage Agent | 领域特定 AI 代理辅助钓鱼邮件分类与优先级排序 | 安全运营中心处理大量用户报告效率低 | 网络安全运营中心 (SOC) |
| 3 | http://arxiv.org/abs/2511.13865v1 | Randomized Controlled Trials for Conditional Access Optimization Agent | AI 代理辅助条件访问策略管理与零信任检测 | 企业身份治理工作流复杂，人工效率低 | 企业身份管理与访问控制 |
| 4 | http://arxiv.org/abs/2511.13948v1 | EchoAgent: Guideline-Centric Reasoning Agent for Echocardiography Measurement and Interpretation | 协调专用视觉工具进行时空定位与临床解释 | 当前深度学习模型不支持视频级推理与指南分析 | 超声心动图测量与解释 |
| 5 | http://arxiv.org/abs/2601.16984v1 | TelcoAI: Advancing 3GPP Technical Specification Search through Agentic Multi-Modal Retrieval-Augmented Generation | 代理式多模态 RAG，支持章节感知分块与查询规划 | 3GPP 规范层级复杂，多模态内容难处理 | 电信技术规范搜索与理解 |
| 6 | http://arxiv.org/abs/2511.13987v1 | Artificial Intelligence Agents in Music Analysis: An Integrative Perspective Based on Two Use Cases | 整合多智能体架构与 RAG 框架进行音乐分析 | 传统自动化方法在可解释性与适应性上不足 | 音乐分析与教育 |
| 7 | http://arxiv.org/abs/2511.14010v2 | Knowledge-Grounded Agentic Large Language Models for Multi-Hazard Understanding from Reconnaissance Reports | 混合检索代理 RAG，动态路由查询至灾害特定数据库 | 灾后报告非结构化，LLM 易产生幻觉 | 多灾害理解与灾后侦察报告 |
| 8 | http://arxiv.org/abs/2511.14445v1 | Tell Me: An LLM-powered Mental Well-being Assistant with RAG, Synthetic Dialogue Generation, and Agentic Planning | 整合 RAG 助手、合成对话生成与 Agentic 规划 | 心理健康支持资源短缺，静态工具缺乏适应性 | 心理健康与幸福感辅助 |
| 9 | http://arxiv.org/abs/2511.14478v4 | Agentic AI Systems in Electrical Power Systems Engineering: Current State-of-the-Art and Challenges | 综述 Agentic AI 在电力系统工程中的应用与挑战 | 缺乏对 Agentic AI 范式清晰的定义与分类理解 | 电力系统工程 |
| 10 | http://arxiv.org/abs/2511.14631v1 | Enhancing Agentic Autonomous Scientific Discovery with Vision-Language Model Capabilities | VLM 作为 judge 评估图表，引导代理纠正错误 | 自主科学发现中推理路径易出错，缺乏验证 | 数据驱动的科学发现 (宇宙学等) |
| 11 | http://arxiv.org/abs/2511.15752v1 | Build AI Assistants using Large Language Models and Agents to Enhance the Engineering Education of Biomechanics | 双模块框架，RAG 增强概念，MAS 解决计算 | 通用 LLM 在领域特定复杂问题上性能下降 | 生物力学工程教育 |
| 12 | http://arxiv.org/abs/2511.15456v1 | Know Your Intent: An Autonomous Multi-Perspective LLM Agent Framework for DeFi User Transaction Intent Mining | 多视角LLM Agent系统动态协调领域专家分解子任务 | DeFi交易意图理解因智能合约交互复杂而困难 | DeFi用户交易分析 |
| 13 | http://arxiv.org/abs/2511.15825v1 | IMACT-CXR - An Interactive Multi-Agent Conversational Tutoring System for Chest X-Ray Interpretation | 统一空间标注、 gaze分析、知识检索的AutoGen工作流 | 胸部X光解读培训缺乏透明度和可解释性 | 医学影像教育培训 |
| 14 | http://arxiv.org/abs/2511.15870v1 | AquaSentinel: Next-Generation AI System Integrating Sensor Networks for Urban Underground Water Pipeline Anomaly Detection via Collaborative MoE-LLM Agent Architecture | 物理信息AI系统结合稀疏传感器和MoE-LLM Agent架构 | 地下管道泄漏检测覆盖有限且响应延迟 | 城市地下水管网监测 |
| 15 | http://arxiv.org/abs/2511.15997v1 | Sensorium Arc: AI Agent System for Oceanic Data Exploration and Interactive Eco-Art | 多Agent系统使海洋成为诗意说话者引导沉浸式探索 | 海洋数据作为抽象数据集缺乏情感和直觉访问 | 海洋数据探索和生态艺术 |
| 16 | http://arxiv.org/abs/2511.16131v1 | AskDB: An LLM Agent for Natural Language Interaction with Relational Databases | 动态模式感知提示机制和任务分解框架支持SQL和DBA任务 | 关系数据库交互对各级用户都具挑战性 | 数据库分析和管理工作 |
| 17 | http://arxiv.org/abs/2511.16205v2 | ChemLabs on ChemO: A Multi-Agent System for Multimodal Reasoning on IChO 2025 | 分层多Agent框架模仿人类专家协作解决化学问题 | 化学奥林匹克级基准对AI推理仍是开放挑战 | 国际化学奥林匹克问题求解 |
| 18 | http://arxiv.org/abs/2511.16635v1 | SurvAgent: Hierarchical CoT-Enhanced Case Banking and Dichotomy-Based Multi-Agent System for Multimodal Survival Prediction | 分层CoT增强多Agent系统整合多模态数据进行生存预测 | 现有生存分析方法缺乏临床采用所需的透明度 | 癌症预后和治疗规划 |
| 19 | http://arxiv.org/abs/2511.21728v2 | Affective Multimodal Agents with Proactive Knowledge Grounding for Emotionally Aligned Marketing Dialogue | 多模态情感对话Agent执行主动推理和动态知识接地 | 大多数对话系统被动且在情感丰富目标导向设置中挣扎 | 营销对话和情感对齐交互 |
| 20 | http://arxiv.org/abs/2511.17676v1 | LLM and Agent-Driven Data Analysis: A Systematic Approach for Enterprise Applications and System-level Deployment | 系统方法覆盖复杂查询理解、多Agent协作、安全验证和计算效率 | 企业采用AI技术时数据安全和合规是首要任务 | 企业数据分析和系统部署 |
| 21 | http://arxiv.org/abs/2511.17052v1 | PathAgent: Toward Interpretable Analysis of Whole-slide Pathology Images via Large Language Model-based Agentic Reasoning | 模拟病理学家反射性逐步分析方法，生成可解释轨迹 | 解决现有计算管道缺乏显式推理轨迹的问题 | 全切片病理图像分析 |
| 22 | http://arxiv.org/abs/2511.17689v1 | ARISE: Agentic Rubric-Guided Iterative Survey Engine for Automated Scholarly Paper Generation | 模块化架构镜像学术角色，基于 rubric 迭代 refinement | 解决自动 survey 生成质量控制及格式适应性差问题 | 学术 survey 论文生成 |
| 23 | http://arxiv.org/abs/2511.17330v1 | Agentic Program Verification | 代理与定理证明器自主协作，迭代 refinement 证明 | 解决自动生成代码的验证及证明结构化决策问题 | 程序验证与自动编程 |
| 24 | http://arxiv.org/abs/2511.17442v2 | REMSA: Foundation Model Selection for Remote Sensing via a Constraint-Aware Agent | 约束感知代理，结合结构化元数据检索与任务驱动工作流 | 解决遥感基础模型选择因文档分散及约束复杂难问题 | 遥感基础模型选择 |
| 25 | http://arxiv.org/abs/2511.17943v1 | SciEducator: Scientific Video Understanding and Educating via Deming-Cycle Multi-Agent System | 基于 Deming Cycle 的自进化多 Agent 系统，生成多模态内容 | 解决科学视频理解需外部知识整合及逐步推理难问题 | 科学视频理解与教育 |
| 26 | http://arxiv.org/abs/2511.21745v1 | AI-Augmented Bibliometric Framework: A Paradigm Shift with Agentic AI for Dynamic, Snippet-Based Research Analysis | 四代理协同，NL 转代码执行 scientometric 分析 | 解决现有 bibliometric 工具刚性及技术壁垒问题 | 动态文献计量分析 |
| 27 | http://arxiv.org/abs/2511.18038v1 | MASTEST: A LLM-Based Multi-Agent System For RESTful API Tests | 结合 LLM 与编程代理，覆盖 API 测试全工作流 | 解决 RESTful API 测试自动化及 LLM 生成脚本质量问题 | RESTful API 测试 |
| 28 | http://arxiv.org/abs/2511.18192v2 | ARIAL: An Agentic Framework for Document VQA with Precise Answer Localization | 模块化框架编排专用工具，实现文本提取与空间 grounding | 解决 Document VQA 文本准确但空间 grounding 不可靠问题 | 文档视觉问答 |
| 29 | http://arxiv.org/abs/2511.18249v1 | LLM Assisted Coding with Metamorphic Specification Mutation Agent | metamorphic relation 驱动代理，细化规格生成测试用例 | 解决 LLM 代码生成因规格模糊导致不一致问题 | LLM 辅助编码与测试 |
| 30 | http://arxiv.org/abs/2511.18258v1 | Hybrid Agentic AI and Multi-Agent Systems in Smart Manufacturing | 混合框架，LLM 代理战略编排，规则/SLM 代理边缘执行 | 解决传统 MAS 缺乏高阶推理及 Agentic AI 缺乏低层执行问题 | 智能制造预测性维护 |
| 31 | http://arxiv.org/abs/2511.18259v2 | DiscoVerse: Multi-Agent Pharmaceutical Co-Scientist for Traceable Drug Discovery and Reverse Translation | 角色专用代理设计，支持 reverse translation 及证据链接 | 解决制药档案复用难及缺乏系统性 agentic framework 评估问题 | 药物发现与反向转化 |
| 32 | http://arxiv.org/abs/2511.23276v1 | Beyond Curve Fitting: Neuro-Symbolic Agents for Context-Aware Epidemic Forecasting | 提出双智能体框架，解耦上下文解释与概率预测，结合 LLM 与神经符号核心 | 解决传统模型缺乏语义推理能力，无法解释冲突驱动因素因果交互的问题 | 传染病预测（手足口病） |
| 33 | http://arxiv.org/abs/2511.23366v1 | Agentic AI Framework for Smart Inventory Replenishment | 应用需求预测、供应商优化及多智能体谈判的代理 AI 模型监控库存 | 解决零售领域需求预测难、防止缺货及寻找高潜力产品的问题 | 零售库存管理 |
| 34 | http://arxiv.org/abs/2511.23387v1 | Hierarchical AI-Meteorologist: LLM-Agent System for Multi-Scale and Explainable Weather Forecast Reporting | 分层代理系统执行多尺度推理，生成可解释天气报告并提取关键词验证一致性 | 解决传统天气预报缺乏叙事性及语义验证，难以捕捉长短趋势的问题 | 气象预报报告生成 |
| 35 | http://arxiv.org/abs/2512.00214v1 | Towards Corpus-Grounded Agentic LLMs for Multilingual Grammatical Analysis | 集成自然语言任务解释、代码生成和数据驱动推理的语料库接地代理框架 | 解决标注语料库系统分析需要大量方法和技术努力，难以自动化问题 | 多语言语法分析 |
| 36 | http://arxiv.org/abs/2512.00331v1 | CogEvo-Edu: Cognitive Evolution Educational Multi-Agent Collaborative System | 分层教育多智能体系统，联合进化学生 profile、知识库及教学策略 | 解决单一 LLM 导师难以维护长期学生模型及管理异构知识库的问题 | STEM 教育辅导 |
| 37 | http://arxiv.org/abs/2512.00491v1 | Smart-TCP: An Agentic AI-based Autonomous and Adaptive TCP Protocol | 将 TCP 核心控制逻辑重构为自主代理，利用 LLM 推理及 ALU 工具计算 | 解决传统硬编码状态机 TCP 协议难以满足智能自主网络架构需求的问题 | 网络传输协议（TCP） |
| 38 | http://arxiv.org/abs/2512.00769v1 | AI Agent for Source Finding by SoFiA-2 for SKA-SDC2 | 基于 RL 算法的 AI 代理自动优化源提取程序参数，交互环境获取反馈 | 解决将源提取程序应用于真实观测时寻找最优参数配置非平凡的问题 | 射电天文源提取 |
| 39 | http://arxiv.org/abs/2601.11540v1 | Exploring General-Purpose Autonomous Multimodal Agents for Pathology Report Generation | 评估多模态 AI 系统自主导航解释组织病理特征，生成描述及 provisional 诊断 | 解决数字病理学中自主感知推理及工具使用机会利用不足的问题 | 病理报告生成 |
| 40 | http://arxiv.org/abs/2512.00834v1 | SemAgent: Semantic-Driven Agentic AI Empowered Trajectory Prediction in Vehicular Networks | 集成语义通信与代理 AI，RSU 提取特征及语义推理辅助车辆预测轨迹 | 解决常规通信开销大及现有轨迹预测模型缺乏环境感知逻辑推理能力问题 | 车联网轨迹预测 |
| 41 | http://arxiv.org/abs/2512.00839v1 | ARCADIA: Scalable Causal Discovery for Corporate Bankruptcy Analysis Using Agentic AI | 集成 LLM 推理与统计诊断，迭代优化候选 DAG 构建有效因果结构 | 解决传统算法难以构建有效时间连贯因果结构及缺乏可解释性问题 | 企业破产因果分析 |
| 42 | http://arxiv.org/abs/2512.00977v1 | Crystalyse: a multi-tool agent for materials design | 开源科学代理编排工具进行成分筛选、结构生成及力场评估，强制溯源 | 解决材料设计中材料属性幻觉及缺乏透明度可复现性的问题 | 无机晶体材料设计 |
| 43 | http://arxiv.org/abs/2512.03065v1 | Optimizing Life Sciences Agents in Real-Time using Reinforcement Learning | 结合 AWS Strands 与 Thompson Sampling 优化生命科学生成策略 | 传统方法依赖固定规则，无法适应用户偏好变化 | 生命科学与医疗查询 |
| 44 | http://arxiv.org/abs/2511.21902v1 | PathReasoning: A multimodal reasoning agent for query-based ROI navigation on whole-slide images | 多模态推理智能体，通过自反思迭代导航全切片图像 | 超大图像导航困难，缺乏密集像素级标注 | 数字病理与癌症诊断 |
| 45 | http://arxiv.org/abs/2512.23713v1 | PyBangla at BLP-2025 Task 2: Enhancing Bangla-to-Python Code Generation with Iterative Self-Correction and Multilingual Agents | BanglaCodeAct 框架，利用多智能体提示与自修正生成代码 | 低资源语言代码生成进展缓慢，缺乏特定微调 | 孟加拉语到 Python 代码生成 |
| 46 | http://arxiv.org/abs/2511.22311v1 | Swarms of Large Language Model Agents for Protein Sequence Design with Experimental Validation | 去中心化 swarm 智能体框架，并行设计蛋白质序列 | 生成方法需大量微调，缺乏灵活性与可扩展性 | 蛋白质从头设计 |
| 47 | http://arxiv.org/abs/2511.22409v1 | NOMAD: A Multi-Agent LLM System for UML Class Diagram Generation from Natural Language Requirements | 认知启发模块化框架，分解 UML 生成为角色专用子任务 | LLM 生成结构化 artefacts 能力未充分探索，细粒度提取难 | 软件工程 UML 图生成 |
| 48 | http://arxiv.org/abs/2511.22767v1 | Agentic AI Framework for Cloudburst Prediction and Coordinated Response | 自主协作智能体闭环系统，整合 sensing 到 response | 传统预报系统预测与响应分离，极端降雨难预报 | 山洪预测与协调响应 |
| 49 | http://arxiv.org/abs/2512.04105v1 | LegalWebAgent: Empowering Access to Justice via LLM-Based Web Agents | 多模态 LLM Web 智能体，三阶段桥接用户查询到行动 | navigating 复杂网站与法律术语阻碍司法 access | 法律司法服务 access |
| 50 | http://arxiv.org/abs/2511.22975v2 | An LLM-Assisted Multi-Agent Control Framework for Roll-to-Roll Manufacturing Systems | LLM 辅助多智能体框架，自动化控制系统设计与适应 | 控制器 commissioning 依赖专家知识，耗时且调整难 | 卷对卷制造系统控制 |
| 51 | http://arxiv.org/abs/2601.06034v1 | Autonomous QA Agent: A Retrieval-Augmented Framework for Reliable Selenium Script Generation | RAG 系统 grounding Selenium 脚本生成于项目文档与 HTML | LLM 生成代码易 hallucinate 不存在 UI 元素 | 自动化 UI 测试脚本生成 |
| 52 | http://arxiv.org/abs/2511.19798v1 | KOM: A Multi-Agent Artificial Intelligence System for Precision Management of Knee Osteoarthritis (KOA) | 多 Agent 系统自动化 KOA 评估与治疗处方 | 膝骨关节炎管理资源不足 | 医疗健康领域 |
| 53 | http://arxiv.org/abs/2511.20090v2 | R3A: Reliable RTL Repair Framework with Multi-Agent Fault Localization and Stochastic Tree-of-Thoughts Patch Generation | 多 Agent 故障定位与随机思维树补丁生成 | RTL 代码 Bug 自动修复可靠性低 | 硬件设计验证 |
| 54 | http://arxiv.org/abs/2511.20109v1 | CLIMATEAGENT: Multi-Agent Orchestration for Complex Climate Data Science Workflows | 多 Agent 编排自动化气候数据科学工作流 | 通用 Agent 缺乏气候领域上下文与灵活性 | 气候科学研究 |
| 55 | http://arxiv.org/abs/2511.20510v2 | FRAGMENTA: End-to-end Fragmentation-based Generative Model with Agentic Tuning for Drug Lead Optimization | 端到端片段生成模型与 Agent 微调药物优化 | 药物发现数据少且 tuning 依赖人工 | 药物研发领域 |
| 56 | http://arxiv.org/abs/2511.20590v1 | EnergyTwin: A Multi-Agent System for Simulating and Coordinating Energy Microgrids | 物理 grounding 多 Agent 微电网仿真协调系统 | 微电网资源协调与物理模型割裂 | 能源微电网管理 |
| 57 | http://arxiv.org/abs/2512.07849v2 | AI Urban Scientist: Multi-Agent Collaborative Automation for Urban Research | 知识驱动多 Agent 框架自动化城市研究 | 城市研究多源数据整合与知识生成难 | 城市科学研究 |
| 58 | http://arxiv.org/abs/2511.21033v2 | Towards Trustworthy Legal AI through LLM Agents and Formal Reasoning | LLM Agent 与 SMT 求解器结合确保法律推理可信 | 法律 AI 缺乏可验证的逻辑依据 | 法律决策支持 |
| 59 | http://arxiv.org/abs/2511.21042v1 | LungNoduleAgent: A Collaborative Multi-Agent System for Precision Diagnosis of Lung Nodules | 多 Agent 协作肺结节 CT 扫描精准诊断系统 | 肺结节形态描述与恶性分级不准 | 医疗影像诊断 |
| 60 | http://arxiv.org/abs/2511.21380v1 | Multi-Agent Systems for Dataset Adaptation in Software Engineering: Capabilities, Limitations, and Future Directions | 多 Agent 系统自动化软件工程数据集适配 | SE 研究 artifacts 跨数据集适配困难 | 软件工程研究 |
| 61 | http://arxiv.org/abs/2601.04368v1 | From Paper to Structured JSON: An Agentic Workflow for Compliant BMR Digital Transformation | Agentic 工作流自动化 BMR 文档结构化转换 | 制药批记录手工数字化耗时易错 | 制药行业数字化 |
| 62 | http://arxiv.org/abs/2511.21444v1 | EWE: An Agentic Framework for Extreme Weather Analysis | 知识引导规划与闭环推理的极端天气分析 Agent | 极端天气诊断依赖专家且劳动密集 | 气象科学分析 |
| 63 | http://arxiv.org/abs/2511.18414v1 | AutoMAS: A Generic Multi-Agent System for Algorithm Self-Adaptation in Wireless Networks | 通用多智能体系统，自主选择合适的无线优化算法。 | 解决无线网络环境动态变化缺乏自适应能力。 | 无线通信网络 |
| 64 | http://arxiv.org/abs/2512.20623v1 | BitRL-Light: 1-bit LLM Agents with Deep Reinforcement Learning for Energy-Efficient Smart Home Lighting Optimization | 结合 1 比特量化大模型与深度强化学习优化智能家居照明。 | 解决智能家居能耗高且缺乏自适应智能的问题。 | 智能家居照明 |
| 65 | http://arxiv.org/abs/2511.18528v1 | End-to-End Automated Logging via Multi-Agent Framework | 混合框架，利用分类器决策是否日志，多智能体生成日志。 | 解决开发者面临日志过多或过少的双重危机。 | 软件工程/日志 |
| 66 | http://arxiv.org/abs/2511.18531v2 | LockForge: Automating Paper-to-Code for Logic Locking with Multi-Agent Reasoning LLMs | 多智能体大模型框架，将逻辑锁定论文描述转化为可执行代码。 | 解决逻辑锁定研究代码稀缺且难以复现的问题。 | 硬件安全/逻辑锁定 |
| 67 | http://arxiv.org/abs/2511.18714v1 | MAGMA-Edu: Multi-Agent Generative Multimodal Framework for Text-Diagram Educational Question Generation | 自反思多智能体框架，统一文本推理与图表合成生成教育问题。 | 解决多模态模型生成教育视觉内容一致性差的问题。 | 教育/内容生成 |
| 68 | http://arxiv.org/abs/2511.18840v1 | Addressing Situated Teaching Needs: A Multi-Agent Framework for Automated Slide Adaptation | 多智能体框架自动化调整教学幻灯片以适应情境需求。 | 解决教师调整课件耗时且难以适应具体情境的问题。 | 教育/幻灯片适配 |
| 69 | http://arxiv.org/abs/2511.19423v1 | Beyond Protein Language Models: An Agentic LLM Framework for Mechanistic Enzyme Design | 工具增强大模型系统，加速蛋白质设计中的科学假设生成。 | 解决蛋白质设计中序列结构功能关联假设生成耗时问题。 | 生物计算/酶设计 |
| 70 | http://arxiv.org/abs/2511.19644v1 | IRSDA: An Agent-Orchestrated Framework for Enterprise Intrusion Response | 智能体编排框架，结合自适应自主计算与 MAPE-K 循环进行入侵响应。 | 解决传统入侵响应系统依赖静态规则且响应慢的问题。 | 网络安全/入侵响应 |
| 71 | http://arxiv.org/abs/2511.19669v1 | HeaRT: A Hierarchical Circuit Reasoning Tree-Based Agentic Framework for AMS Design Optimization | 分层电路推理树智能体框架，用于 AMS 设计优化。 | 解决 AI 驱动 AMS 设计自动化依赖高质量数据集且迁移性差问题。 | 电路设计/自动化 |
| 72 | http://arxiv.org/abs/2511.12224v1 | RulePilot: An LLM-Powered Agent for Security Rule Generation | 中间表示抽象配置规则复杂度，自动生成检测规则 | 安全规则生成需深度领域专业知识 | 入侵检测系统 |
| 73 | http://arxiv.org/abs/2511.12439v2 | Multi-agent Self-triage System with Medical Flowcharts | 三Agent框架：检索+决策+聊天，引导100个临床流程图 | 在线健康资源与LLM医疗决策可靠性低 | 医疗自我分诊 |
| 74 | http://arxiv.org/abs/2511.12916v1 | Fault2Flow: An AlphaEvolve-Optimized Human-in-the-Loop Multi-Agent System for Fault-to-Workflow Automation | 四步流程：提取法规逻辑+整合专家知识+优化+合成工作流 | 电网故障诊断依赖手动、易错、缺乏可维护性 | 电力电网故障诊断 |
| 75 | http://arxiv.org/abs/2511.13305v1 | SAINT: Service-level Integration Test Generation with Program Analysis and LLM-based Agents | 结合静态分析与LLM Agent，生成端点与场景测试 | 企业服务级测试工具依赖OpenAPI、功能测试能力有限 | 企业Java应用测试 |
| 76 | http://arxiv.org/abs/2511.13361v1 | MedDCR: Learning to Design Agentic Workflows for Medical Coding | MedDCR：Designer-Coder-Reflector闭环学习工作流设计 | 医疗编码需多步推理，现有工作流僵硬手动 | 医疗编码自动化 |
| 77 | http://arxiv.org/abs/2511.00450v1 | SmartDoc: A Context-Aware Agentic Method Comment Generation Plugin | 构建调用图遍历机制，为 IntelliJ 插件提供全上下文方法注释生成 | 解决开发者理解代码困难及注释更新不及时的问题 | Java 代码库维护与开发者 |
| 78 | http://arxiv.org/abs/2511.00517v1 | Issue-Oriented Agent-Based Framework for Automated Review Comment Generation | 分解为生成、判别、训练三阶段，多代理协作生成代码审查评论 | 解决单模型处理多样化代码问题能力有限及评论非信息化的问题 | 软件代码审查流程 |
| 79 | http://arxiv.org/abs/2511.00549v2 | Robust Single-Agent Reinforcement Learning for Regional Traffic Signal Control Under Demand Fluctuations | 采用单智能体 RL 与 DreamerV3 世界模型，统一编码路网与队列状态 | 解决传统交通信号优化模型无法捕捉实时动态复杂性的问题 | 区域自适应交通信号控制 |
| 80 | http://arxiv.org/abs/2511.00551v2 | Single-agent Reinforcement Learning Model for Regional Adaptive Traffic Signal Control | 基于探针车辆数据定义状态与奖励，单智能体协调多路口信号控制 | 解决多智能体框架扩展性差及区域拥堵协调难的问题 | 城市区域交通信号控制 |
| 81 | http://arxiv.org/abs/2511.00651v1 | Leveraging Multi-Agent System (MAS) and Fine-Tuned Small Language Models (SLMs) for Automated Telecom Network Troubleshooting | 多智能体协作配合微调小模型，动态激活工具进行网络故障诊断 | 解决电信网络故障排查依赖专家及现有模型泛化能力差的问题 | 电信网络运维与故障排查 |
| 82 | http://arxiv.org/abs/2511.07437v1 | Agentic Educational Content Generation for African Languages on Edge Devices | 四智能体协作框架，在边缘设备上生成文化自适应的教育内容 | 解决撒哈拉以南非洲教育资源不均及本地化内容缺乏的问题 | 边缘设备上的多语言教育 |
| 83 | http://arxiv.org/abs/2511.00843v1 | Portal UX Agent -- A Plug-and-Play Engine for Rendering UIs from Natural Language Specifications | LLM 规划结合确定性渲染器，从自然语言生成合规且可审计的 UI | 解决自由代码生成可靠性差及静态 UI 缺乏适应性的问题 | 用户界面自动生成 |
| 84 | http://arxiv.org/abs/2511.01047v2 | HAFixAgent: History-Aware Automated Program Repair Agent | 注入基于 blame 的仓库历史启发式信息，增强多 hunk  bug 修复能力 | 解决现有 APR 系统忽略仓库历史及复杂多 hunk bug 修复难的问题 | 自动化程序修复 |
| 85 | http://arxiv.org/abs/2511.01445v2 | From Passive to Proactive: A Hierarchical Multi-Agent Framework for Automated Medical Pre-Consultation | 三智能体协作通过询问与分类引导机制，实现准确科室推荐 | 解决现有 AI 分诊专业化不足及跨机构结构异构适配难的问题 | 医疗预问诊与分诊系统 |
| 86 | http://arxiv.org/abs/2511.01720v1 | Efficient Tool-Calling Multi-Expert NPC Agent for Commonsense Persona-Grounded Dialogue | 多专家系统实例化工具调用与对话 specialists，满足计算效率要求 | 解决 NPC 自然对话与上下文动作执行兼顾难及资源消耗大的问题 | 游戏 NPC 对话与交互 |
| 87 | http://arxiv.org/abs/2511.03697v1 | AnaFlow: Agentic LLM-based Workflow for Reasoning-Driven Explainable and Sample-Efficient Analog Circuit Sizing | 多智能体协作解释模拟电路设计，自适应模拟策略提高效率 | 解决模拟电路设计周期长、易出错且缺乏可解释性的问题 | 模拟电路设计自动化 |
| 88 | http://arxiv.org/abs/2511.03852v1 | GAIA: Geothermal Analytics and Intelligent Agent | 整合代理、聊天和数字孪生，自动化地热田开发流程 | 解决地热开发决策需多学科专家整合且时间紧迫的问题 | 地热田开发与决策 |
| 89 | http://arxiv.org/abs/2511.04076v2 | Agentmandering: A Game-Theoretic Framework for Fair Redistricting via Large Language Model Agents | 基于博弈论的转手谈判框架，嵌入战略交互到选区划分 | 解决选区划分过程中战略动态被忽视导致不公平的问题 | 政治选区重划 |
| 90 | http://arxiv.org/abs/2511.04720v1 | Learning to reason about rare diseases through retrieval-augmented agents | 检索外部医学知识引导诊断决策，无需额外训练 | 解决罕见病医学影像 AI 模型因数据稀缺而失效的问题 | 罕见病医学影像诊断 |
| 91 | http://arxiv.org/abs/2511.04464v1 | Beyond Shortest Path: Agentic Vehicular Routing with Semantic Context | 结合经典路由算法与 LLM 语义推理层，理解用户意图 | 解决传统车辆路由无法解释整合人类司机复杂语义上下文问题 | 城市交通路径规划 |
| 92 | http://arxiv.org/abs/2511.04824v1 | Agentic Refactoring: An Empirical Study of AI Coding Agents | 大规模实证研究 AI 代理生成的重构，分析代码质量影响 | 解决缺乏对代理重构实践与代码质量影响的实证理解问题 | 软件工程与代码重构 |
| 93 | http://arxiv.org/abs/2511.04921v1 | AgentExpt: Automating AI Experiment Design with LLM-based Resource Retrieval Agent | 自动化数据收集管道，集体感知增强检索器推荐基线 | 解决实验设计自动化中数据覆盖有限与过度依赖内容相似问题 | AI 实验设计自动化 |
| 94 | http://arxiv.org/abs/2511.05311v1 | Cleaning Maintenance Logs with LLM Agents for Improved Predictive Maintenance | 评估 LLM 代理清洗维护日志，处理六种噪声类型 | 解决预测性维护中维护日志数据质量差且缺乏专家问题 | 汽车预测性维护 |
| 95 | http://arxiv.org/abs/2511.05912v1 | RadioSim Agent: Combining Large Language Models and Deterministic EM Simulators for Interactive Radio Map Analysis | 整合 LLM 与物理 EM 求解器，实现交互式无线电地图生成 | 解决确定性电磁模拟器需专家配置且缺乏交互灵活性问题 | 无线系统设计与分析 |
| 96 | http://arxiv.org/abs/2511.09533v1 | Digital Co-Founders: Transforming Imagination into Viable Solo Business via Agentic AI | 提出三阶段框架，AI代理作为数字联合创始人辅助创业 | 个体创业者资源有限、决策负担重、认知超载问题 | 独立创业者/小微企业 |
| 97 | http://arxiv.org/abs/2511.09794v1 | Evaluating Software Process Models for Multi-Agent Class-Level Code Generation | 模拟瀑布式开发周期评估多Agent代码生成工作流 | 单Agent函数级生成的局限性，代码可维护性问题 | 软件工程/代码生成 |
| 98 | http://arxiv.org/abs/2511.11752v1 | Towards autonomous quantum physics research using LLM agents with access to intelligent tools | AI-Mandel Agent可生成并实现量子物理实验设计 | 科学研究中AI创意生成与执行分离，依赖人类 | 量子物理研究 |
| 99 | http://arxiv.org/abs/2511.10611v1 | Towards an Agentic Workflow for Internet Measurement Research | ArachNet四Agent系统自动生成网络测量工作流 | 网络测量分析工具集成复杂、需要专业领域知识 | 互联网测量研究 |
| 100 | http://arxiv.org/abs/2511.10853v2 | Advanced Assistance for Traffic Crash Analysis: An AI-Driven Multi-Agent Approach to Pre-Crash Reconstruction | 两阶段协作框架从碎片化碰撞数据重建事故前场景 | 事故前重建比传统重建更困难，依赖专家经验 | 交通事故调查分析 |
| 101 | http://arxiv.org/abs/2511.10857v1 | Enhancing Demand-Oriented Regionalization with Agentic AI and Local Heterogeneous Data for Adaptation Planning | Agent引导空间约束与区域生长优化，人机交互式区域生成 | 传统规划单元无法捕捉社区特定需求与灵活性 | 灾害规划/城市规划 |
| 102 | http://arxiv.org/abs/2511.10860v1 | HPCAgentTester: A Multi-Agent LLM Approach for Enhanced HPC Unit Test Generation | 配方Agent与测试Agent迭代生成优化HPC单元测试 | HPC并行非确定性行为与同步问题传统方法难以处理 | 高性能计算软件测试 |
| 103 | http://arxiv.org/abs/2511.10925v1 | Multi-Agent Legal Verifier Systems for Data Transfer Planning | 多Agent分工进行法条解释、业务评估与风险评估 | AI驱动数据传输规划中的法律合规性检查 | 数据隐私合规(Japanese APPI) |
| 104 | http://arxiv.org/abs/2511.11012v1 | Beyond Accuracy: Behavioral Dynamics of Agentic Multi-Hunk Repair | 首次系统研究LLM编码Agent在多缺陷块修复中的行为动态 | 多缺陷块修复需跨多代码区域协调编辑，挑战更大 | 自动化程序修复 |
| 105 | http://arxiv.org/abs/2511.11017v1 | AI Agent-Driven Framework for Automated Product Knowledge Graph Construction in E-Commerce | 三阶段Agent自动化从非结构化描述构建产品知识图谱 | 产品特定知识图谱构建复杂且依赖人工 | 电子商务/零售 |
| 106 | http://arxiv.org/abs/2511.11035v1 | GraphMASAL: A Graph-based Multi-Agent System for Adaptive Learning | 动态知识图谱+三Agent编排+多源多汇规划引擎 | 现有ITS缺乏结构推理能力与知识动态性 | 智能辅导系统/教育 |
| 107 | http://arxiv.org/abs/2511.13759v1 | Multi-Agent VLMs Guided Self-Training with PNU Loss for Low-Resource Offensive Content Detection | 多Agent VLM模拟双重视角协作伪标签，PNU损失优化 | 低资源场景下攻击性内容检测标注数据稀缺 | 社交媒体内容审核 |
| 108 | http://arxiv.org/abs/2511.11257v1 | AIonopedia: an LLM agent orchestrating multimodal learning for ionic liquid discovery | 首个离子液体发现LLM Agent，分层搜索架构分子筛选 | 离子液体属性预测数据有限、模型精度差、工作流碎片化 | 化学/材料科学发现 |
| 109 | http://arxiv.org/abs/2511.11324v1 | NOVA: An Agentic Framework for Automated Histopathology Analysis and Discovery | 49领域工具+按需创建新工具，将科学查询转为可执行管道 | 数字化病理分析工作流复杂耗时，需要专业知识 | 病理学分析/生物医学 |
| 110 | http://arxiv.org/abs/2511.11370v1 | SRLF: An Agent-Driven Set-Wise Reflective Learning Framework for Sequential Recommendation | 集合级反思学习框架，整体判断项目集而非单点评估 | 单点建模导致用户偏好理解不准确、项目语义表示僵化 | 序列推荐系统 |
| 111 | http://arxiv.org/abs/2511.08060v1 | From LLMs to Agents: A Comparative Evaluation of LLMs and LLM-based Agents in Security Patch Detection | 比较LLM与Agent在安全补丁检测性能 | 安全漏洞检测中假阳性率过高问题 | 开源软件安全补丁检测 |
| 112 | http://arxiv.org/abs/2511.08181v2 | MARC: Multimodal and Multi-Task Agentic Retrieval-Augmented Generation for Cold-Start Recommender System | 基于图数据库的Agentic RAG推荐系统 | 冷启动条件下推荐质量差 | 鸡尾酒推荐系统 |
| 113 | http://arxiv.org/abs/2511.09114v2 | Towards a Generalisable Cyber Defence Agent for Real-World Computer Networks | TERLA拓扑扩展使防御Agent泛化不同网络 | 现有Agent需重训练适应不同网络拓扑 | 真实计算机网络防御 |
| 114 | http://arxiv.org/abs/2511.09122v2 | Vendor-Aware Industrial Agents: RAG-Enhanced LLMs for Secure On-Premise PLC Code Generation | RAG增强本地小模型生成工业PLC代码 | 工业代码方言专有且公司不信任云 | 工业PLC代码生成 |
| 115 | http://arxiv.org/abs/2511.09394v2 | EyeAgent: An Agentic AI System for Multimodal Clinical Decision Support in Ophthalmology | 53种眼科工具动态编排支持临床决策 | 现有医疗AI缺乏灵活性可解释性适应性 | 眼科临床诊断支持 |
| 116 | http://arxiv.org/abs/2511.06036v1 | Towards Human-AI-Robot Collaboration and AI-Agent based Digital Twins for Parkinson's Disease Management: Review and Outlook | 闭环传感器-AI-机器人框架，构建PD患者数字孪生 | PD筛查、监测与管理研究流割裂，缺乏整合 | 帕金森病管理与康复 |
| 117 | http://arxiv.org/abs/2511.06185v2 | Dataforge: Agentic Platform for Autonomous Data Engineering | LLM驱动自主数据工程平台，预算反馈循环 | 数据准备劳动密集、特征转换选择关键但耗时 | 材料发现、分子建模、气候科学数据工程 |
| 118 | http://arxiv.org/abs/2511.06455v1 | A Multi-Agent System for Semantic Mapping of Relational Data to Knowledge Graphs | 多LLM Agent将关系数据映射到知识图谱 | 企业数据孤岛、互操作性挑战 | 企业数据集成与知识图谱构建 |
| 119 | http://arxiv.org/abs/2511.06892v1 | Multi-Agent AI Framework for Road Situation Detection and C-ITS Message Generation | 多模态LLM与视觉感知结合的道路情况监测框架 | 传统方法未见场景失效、缺乏语义解释 | 智能交通系统与C-ITS消息生成 |
| 120 | http://arxiv.org/abs/2511.07097v1 | Agentic AI Sustainability Assessment for Supply Chain Document Insights | 多Agent工作流供应链文档智能可持续性评估框架 | 文档密集工作流自动化效率与环境绩效衡量 | 供应链文档处理与ESG评估 |
| 121 | http://arxiv.org/abs/2511.07257v1 | Bridging the Prototype-Production Gap: A Multi-Agent System for Notebooks Transformation | 三Agent系统自动转换Jupyter笔记本为生产代码 | 笔记本缺乏软件工程原则、生产转换困难 | 数据科学与机器学习工作流 |
| 122 | http://arxiv.org/abs/2511.07262v2 | AgenticSciML: Collaborative Multi-Agent Systems for Emergent Discovery in Scientific Machine Learning | 10+专用Agent协作提出、批评、优化SciML方案 | SciML架构设计专家驱动、需大量实验 | 科学机器学习与物理信息学习 |
| 123 | http://arxiv.org/abs/2511.07322v2 | FinRpt: Dataset, Evaluation System and LLM-based Multi-agent Framework for Equity Research Report Generation | 股权研究报告生成任务、数据集与多Agent框架 | 股权研究报告自动化生成未探索、数据稀缺 | 金融股权研究与报告生成 |
| 124 | http://arxiv.org/abs/2511.07748v1 | Auto-US: An Ultrasound Video Diagnosis Agent Using Video Classification Framework and LLMs | 超声视频分类框架与LLM集成诊断Agent | 超声视频诊断数据集多样性、性能与临床适用性有限 | 医学影像与超声诊断 |
| 125 | http://arxiv.org/abs/2511.08649v1 | Bio AI Agent: A Multi-Agent Artificial Intelligence System for Autonomous CAR-T Cell Therapy Development with Integrated Target Discovery, Toxicity Prediction, and Rational Molecular Design | 六自主Agent协作CAR-T细胞治疗开发系统 | CAR-T开发周期长、临床失败率高、效率低 | 精准肿瘤学与免疫治疗开发 |
| 126 | http://arxiv.org/abs/2512.16925v2 | V-Agent: An Interactive Video Search System Using Vision-Language Models | 三 Agent 协作（路由/搜索/聊天），多模态视频搜索。 | 传统文本检索无法理解视频多模态内容。 | 交互式视频搜索系统 |
| 127 | http://arxiv.org/abs/2511.02399v1 | EvoDev: An Iterative Feature-Driven Framework for End-to-End Software Development with LLM-based Agents | 特性驱动开发框架，构建特性图管理依赖与上下文。 | 线性管道 oversimplify 真实迭代开发流程。 | 端到端软件开发任务 |
| 128 | http://arxiv.org/abs/2511.02532v1 | Agentic AI for Mobile Network RAN Management and Optimization | 提出 Agentic AI 核心概念并应用于 5G/6G RAN 优化。 | 手动优化无法应对 5G/6G 网络动态复杂性。 | 移动网络 RAN 管理与优化 |
| 129 | http://arxiv.org/abs/2511.02748v1 | Agentic World Modeling for 6G: Near-Real-Time Generative State-Space Reasoning | 世界建模范式学习动作条件生成状态空间，支持反事实推理。 | 传统 LLM 无法进行定量 what-if 预测。 | 6G O-RAN 近实时控制 |
| 130 | http://arxiv.org/abs/2511.08605v2 | Mina: A Multilingual LLM-Powered Legal Assistant Agent for Bangladesh for Empowering Access to Justice | 多语言法律助手，RAG 链式工具框架提供法律咨询。 | 低收入群体面临法律建议成本高与语言障碍。 | 孟加拉国法律服务 |
| 131 | http://arxiv.org/abs/2511.03153v2 | RefAgent: A Multi-agent LLM-based Framework for Automatic Software Refactoring | 多 Agent 框架规划、执行、测试并迭代优化重构。 | 传统 LLM 依赖静态指令，缺乏动态适应。 | 自动软件重构 |
| 132 | http://arxiv.org/abs/2511.03179v3 | Toward Autonomous Engineering Design: A Knowledge-Guided Multi-Agent Framework | 知识驱动 Agent 协作生成与 refine 设计候选。 | 传统工程设计资源密集且效率低。 | 自主工程设计（如翼型优化） |
| 133 | http://arxiv.org/abs/2511.03363v1 | A Modular, Data-Free Pipeline for Multi-Label Intention Recognition in Transportation Agentic AI Applications | 无数据管道，合成查询训练分类器识别多标签意图。 | 传统意图识别依赖大量标注数据。 | 交通领域 Agent 应用 |
| 134 | http://arxiv.org/abs/2511.03404v1 | Towards Realistic Project-Level Code Generation via Multi-Agent Collaboration and Semantic Architecture Modeling | 多 Agent 分解架构设计与代码填充，语义软件架构树。 | 项目级代码生成存在语义 gap 与依赖管理难。 | 项目级代码生成 |
| 135 | http://arxiv.org/abs/2511.03517v1 | U2F: Encouraging SWE-Agent to Seize Novelty without Losing Feasibility | 认知启发框架，发现“未知的未知”创新解决方案。 | 现有 SWE-Agent 忽略 predefined 框架外的创新。 | 开放世界软件工程任务 |

[返回目录](#目录)

<a id="cat-03"></a>

## 多Agent协作与通信

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2511.13614v1 | Market-Dependent Communication in Multi-Agent Alpha Generation | 揭示市场特性决定多 Agent 通信结构的最优性 | 多策略对冲基金中分析师通信机制选择不明 | 金融交易策略生成系统 |
| 2 | http://arxiv.org/abs/2511.14101v1 | APD-Agents: A Large Language Model-Driven Multi-Agents Collaborative Framework for Automated Page Design | 多 Agent 协作框架，动态编排布局与组件生成 | 移动端页面设计耗时，跨页协作对齐标准难 | 移动应用页面自动化设计 |
| 3 | http://arxiv.org/abs/2511.14299v2 | DataSage: Multi-agent Collaboration for Insight Discovery with External Knowledge Retrieval, Multi-role Debating, and Multi-path Reasoning | 引入外部知识检索、多角色辩论与多路径推理 | 现有数据洞察 Agent 领域知识利用不足，分析浅 | 自动化数据洞察发现 |
| 4 | http://arxiv.org/abs/2511.15074v1 | Knowledge-Informed Automatic Feature Extraction via Collaborative Large Language Model Agents | 去中心化三 Agent 协作，引入定性反馈机制 | 现有 AutoFE 方法缺乏外部知识整合与系统反馈 | 表格数据自动特征提取 |
| 5 | http://arxiv.org/abs/2511.15755v2 | Multi-Agent LLM Orchestration Achieves Deterministic, High-Quality Decision Support for Incident Response | 多 Agent 编排实现确定性高质量决策支持 | 单 Agent 方法生成建议模糊，不可用 | 生产系统事件响应 |
| 6 | http://arxiv.org/abs/2511.15211v2 | OEMA: Ontology-Enhanced Multi-Agent Collaboration Framework for Zero-Shot Clinical Named Entity Recognition | 本体增强多 Agent 协作，零样本临床 NER | 传统监督模型标注成本高，零样本对齐难 | 临床命名实体识别 |
| 7 | http://arxiv.org/abs/2511.15862v2 | The Subtle Art of Defection: Understanding Uncooperative Behaviors in LLM based Multi-Agent Systems | 基于博弈论的不合作行为分类和多阶段模拟流水线 | 不合作行为如何破坏或瓦解LLM多Agent系统 | 协作资源管理场景 |
| 8 | http://arxiv.org/abs/2511.16202v4 | Multi-Agent Collaborative Reward Design for Enhancing Reasoning in Reinforcement Learning | 协调专家评估员团队替代单一黑盒奖励模型提高鲁棒性 | 传统奖励模型难以联合优化多个冲突偏好维度 | RLHF奖励建模 |
| 9 | http://arxiv.org/abs/2511.16292v1 | Distributed Agent Reasoning Across Independent Systems With Strict Data Locality | 仅用自然语言消息实现跨分布式系统Agent间通信 | 多组织如何在保持数据本地化前提下安全协作 | 医疗、保险和专业网络协作 |
| 10 | http://arxiv.org/abs/2511.16787v1 | NALA_MAINZ at BLP-2025 Task 2: A Multi-agent Approach for Bangla Instruction to Python Code Generation | 代码生成Agent和调试Agent协作仅转发失败测试用例 | 从孟加拉语指令生成Python代码的挑战 | 孟加拉语到Python代码生成 |
| 11 | http://arxiv.org/abs/2511.16964v1 | Optimizing PyTorch Inference with LLM-Based Multi-Agent Systems | 逻辑框架比较多Agent PyTorch优化系统发现利用重策略最佳 | 多Agent系统进行PyTorch优化的动态尚未探索 | PyTorch推理性能优化 |
| 12 | http://arxiv.org/abs/2511.21729v1 | Beyond Component Strength: Synergistic Integration and Adaptive Calibration in Multi-Agent RAG Systems | 多组件协同集成与自适应校准，减少弃权率 | 解决单一组件增强无效及标签不一致问题 | 多 Agent RAG 系统 |
| 13 | http://arxiv.org/abs/2511.18194v1 | Agent-as-a-Graph: Knowledge Graph-Based Tool and Agent Retrieval for LLM Multi-Agent Systems | 知识图检索增强，工具与代理为节点，wRRF 重排序 | 解决现有检索 obscuring fine-grained tool capabilities 问题 | LLM 多 Agent 系统检索 |
| 14 | http://arxiv.org/abs/2512.09935v1 | Exploring Health Misinformation Detection with Multi-Agent Debate | 两阶段框架结合同意度预测与多智能体辩论，合成冲突证据生成理由充分 verdict | 解决健康虚假信息检测需要高质量证据检索及严格推理过程的问题 | 健康 misinformation 检测 |
| 15 | http://arxiv.org/abs/2512.00614v1 | Hierarchical Decentralized Multi-Agent Coordination with Privacy-Preserving Knowledge Sharing: Extending AgentNet for Scalable Autonomous Systems | 提出 AgentNet++，引入集群层级及隐私保护知识共享，实现高效任务路由 | 解决去中心化多 Agent 系统扩展性差、通信开销大及缺乏隐私保证问题 | 大规模自主系统 |
| 16 | http://arxiv.org/abs/2512.00617v2 | ART: Adaptive Response Tuning Framework -- A Multi-Agent Tournament-Based Approach to LLM Response Optimization | 采用锦标赛式 ELO 排名及多智能体推理，通过竞争批评协作优化 LLM 输出 | 解决单模型响应存在不一致、幻觉及不同查询领域质量变化问题 | LLM 响应优化 |
| 17 | http://arxiv.org/abs/2512.00740v1 | Augmented Runtime Collaboration for Self-Organizing Multi-Agent Systems: A Hybrid Bi-Criteria Routing Approach | 提出 BiRouter 双标准路由方法，基于局部信息平衡重要性及上下文连续性 | 解决分布式系统仅用局部信息进行有效协作规划及静态拓扑限制扩展性问题 | 自组织多智能体系统 |
| 18 | http://arxiv.org/abs/2512.01035v1 | Goal-Oriented Multi-Agent Semantic Networking: Unifying Intents, Semantics, and Intelligence | GoAgentNet 架构抽象功能为协作代理，联合编排 sensing  networking computation | 解决现有网络架构应用与网络解耦，无法暴露利用高层目标限制智能适应问题 | 6G 目标导向网络 |
| 19 | http://arxiv.org/abs/2512.17914v1 | Q-KVComm: Efficient Multi-Agent Communication Via Adaptive KV Cache Compression | 直接传输压缩 KV 缓存表示，自适应层重量化 | 冗余上下文传输消耗带宽，接收方需重计算表示 | 多智能体 LLM 系统通信 |
| 20 | http://arxiv.org/abs/2511.22536v1 | A Computable Game-Theoretic Framework for Multi-Agent Theory of Mind | 博弈论视角计算框架，维护对他人的 Theory of Mind | 心理学工作未形式化核心概念，自动化计算难 | 多智能体理论心智建模 |
| 21 | http://arxiv.org/abs/2511.19969v1 | M$^3$Prune: Hierarchical Communication Graph Pruning for Efficient Multi-Modal Multi-Agent Retrieval-Augmented Generation | 分层通信图剪枝优化多模态多 Agent RAG | 多 Agent 系统 Token 开销与计算成本高 | 多模态 RAG 系统 |
| 22 | http://arxiv.org/abs/2511.20719v1 | Learning Multi-Access Point Coordination in Agentic AI Wi-Fi with Large Language Models | LLM Agent 协作实现 Wi-Fi 多接入点动态协调 | 静态协议无法适应动态网络条件 | Wi-Fi 网络管理 |
| 23 | http://arxiv.org/abs/2511.20639v2 | Latent Collaboration in Multi-Agent Systems | 潜在空间直接协作实现无损信息交换 | 文本中介协作信息损失与效率低 | 多 Agent 系统 |
| 24 | http://arxiv.org/abs/2511.20940v1 | Chatty-KG: A Multi-Agent AI System for On-Demand Conversational Question Answering over Knowledge Graphs | 多 Agent 协作实现 KG 对话问答与 SPARQL 生成 | 传统 KGQA 多轮上下文与延迟问题 | 知识图谱问答 |
| 25 | http://arxiv.org/abs/2511.18413v3 | Multi-Agent Collaborative Filtering: Orchestrating Users and Items for Agentic Recommendations | 提出多智能体协同过滤框架，类比传统算法与 LLM 协作。 | 解决推荐系统中协作信号利用不足的问题。 | 推荐系统 |
| 26 | http://arxiv.org/abs/2511.19113v1 | Agent Discovery in Internet of Agents: Challenges and Solutions | 两阶段能力发现框架，支持智能体自主宣布与任务驱动发现。 | 解决智能体互联网中能力表示与可扩展发现的问题。 | 智能体互联网 |
| 27 | http://arxiv.org/abs/2511.19175v1 | LLM-Based Agentic Negotiation for 6G: Addressing Uncertainty Neglect and Tail-Event Risk | 基于大模型的风险感知谈判框架，利用数字孪生预测分布。 | 解决 6G 智能体网络中不确定性忽视与尾部风险问题。 | 6G 网络/资源分配 |
| 28 | http://arxiv.org/abs/2511.19417v1 | Be My Eyes: Extending Large Language Models to New Modalities Through Multi-Agent Collaboration | 模块化多智能体框架，协调高效视觉模型与强大语言模型。 | 解决扩展大模型到新模态需 costly 开发视觉语言模型问题。 | 多模态推理 |
| 29 | http://arxiv.org/abs/2511.19699v3 | A Layered Protocol Architecture for the Internet of Agents | 提出智能体通信层与语义层，构建智能体互联网协议架构。 | 解决现有网络架构不支持智能体协作与语义理解的问题。 | 智能体互联网 |
| 30 | http://arxiv.org/abs/2511.11567v1 | Who Moved My Distribution? Conformal Prediction for Interactive Multi-Agent Systems | 迭代共形预测框架适应内生分布偏移 | 多智能体交互中的不确定性预测与安全保障 | 自动驾驶运动规划 |
| 31 | http://arxiv.org/abs/2511.12160v1 | Game-Theoretic Safe Multi-Agent Motion Planning with Reachability Analysis for Dynamic and Uncertain Environments | RE-DPG框架整合博弈论协调与可达性分析 | 动态不确定环境中多Agent安全运动规划 | 2D/3D多Agent系统 |
| 32 | http://arxiv.org/abs/2511.12208v2 | Debate over Mixed-knowledge: A Robust Multi-Agent Reasoning Framework for Incomplete Knowledge Graph Question Answering | 多Agent辩论范式动态整合结构化与非结构化知识 | 知识图谱不完整导致的问答准确性问题 | 不完整KG问答 |
| 33 | http://arxiv.org/abs/2511.12492v1 | Density-Driven Multi-Agent Coordination for Efficient Farm Coverage and Management in Smart Agriculture | D2OC框架整合最优传输与多UAV覆盖控制 | 大规模农田非均匀喷洒与资源分配效率 | 智慧农业UAV集群 |
| 34 | http://arxiv.org/abs/2511.12630v1 | Knots: A Large-Scale Multi-Agent Enhanced Expert-Annotated Dataset and LLM Prompt Optimization for NOTAM Semantic Parsing | 多Agent协作框架进行NOTAM语义解析与字段发现 | NOTAM复杂语言结构与隐式推理难以自动解析 | 航空安全信息解析 |
| 35 | http://arxiv.org/abs/2511.17586v1 | Hierarchical Adaptive Consensus Network: A Dynamic Framework for Scalable Consensus in Collaborative Multi-Agent AI Systems | 三层架构实现O(n)通信复杂度，99.9%降低通信开销 | 多Agent系统共识策略适应性、可扩展性不足 | 协作多Agent AI系统 |
| 36 | http://arxiv.org/abs/2511.13193v1 | Cost-Effective Communication: An Auction-based Method for Language Agent Interaction | DALA：动态拍卖机制，Agent基于消息价值密度竞价发言 | LLM多Agent通信低效、Token成本指数级增长 | 多Agent推理任务 |
| 37 | http://arxiv.org/abs/2512.00047v1 | Emergent Convergence in Multi-Agent LLM Annotation | 分析7500次多Agent讨论，发现语义压缩与不对称影响模式 | LLM协作协调机制与涌现策略理解不足 | 多Agent标注任务 |
| 38 | http://arxiv.org/abs/2511.00908v2 | GraphGeo: Multi-Agent Debate Framework for Visual Geo-localization with Heterogeneous Graph Neural Networks | 利用异构图神经网络建模多智能体辩论关系，转化认知冲突为精度 | 解决单模型地理定位能力有限及多智能体冲突处理机制缺失的问题 | 视觉地理定位任务 |
| 39 | http://arxiv.org/abs/2511.01149v1 | Modular Task Decomposition and Dynamic Collaboration in Multi-Agent Systems Driven by Large Language Models | 模块化任务分解与动态调度机制，确保子任务连贯及负载均衡 | 解决单智能体任务分解局限及多智能体协作冗余通信问题 | 复杂环境下的多智能体任务执行 |
| 40 | http://arxiv.org/abs/2511.03925v1 | Collaborative Agents for Automated Program Repair in Ruby | 协作智能体生成测试并反思错误，迭代修复 Ruby 代码 | 解决 Ruby 语言自动化程序修复研究少且计算成本高的问题 | Ruby 语言程序修复 |
| 41 | http://arxiv.org/abs/2511.03958v1 | Multi-Agent Collaborative Framework For Math Problem Generation | 多智能体迭代优化问题 - 答案对，平衡复杂度与认知需求 | 解决自动数学问题生成难以控制复杂度和认知需求的问题 | 智能辅导系统内容生成 |
| 42 | http://arxiv.org/abs/2511.03985v1 | ArchPilot: A Proxy-Guided Multi-Agent Approach for Machine Learning Engineering | 代理引导评估与自适应搜索，减少完整训练运行次数 | 解决自动化 ML 工程依赖重复全训练导致计算开销大的问题 | 机器学习架构搜索 |
| 43 | http://arxiv.org/abs/2511.09710v3 | Echoing: Identity Failures when LLM Agents Talk to Each Other | 发现LLM Agent对话中的"回音"失败模式，提出结构化响应缓解 | Agent-Agent对话中角色漂移、目标偏离问题 | LLM多Agent对话系统 |
| 44 | http://arxiv.org/abs/2511.10030v1 | Multi-agent In-context Coordination via Decentralized Memory Retrieval | 去中心化记忆检索实现快速任务适应与团队级信息获取 | 去中心化部署中任务对齐与奖励分配不匹配 | 合作多Agent强化学习 |
| 45 | http://arxiv.org/abs/2511.11040v1 | Key Decision-Makers in Multi-Agent Debates: Who Holds the Power? | 发现"Truth Last"角色分配策略，提出MADC一致性优化 | 多Agent辩论中角色分配策略未被充分探索 | LLM推理任务 |
| 46 | http://arxiv.org/abs/2511.11306v2 | iMAD: Intelligent Multi-Agent Debate for Efficient and Accurate LLM Inference | 选择性触发辩论机制，减少92% token消耗同时提升准确率 | 每次查询都触发辩论效率低，可能推翻正确单Agent答案 | LLM推理优化 |
| 47 | http://arxiv.org/abs/2511.08151v2 | SciAgent: A Unified Multi-Agent System for Generalistic Scientific Reasoning | 分层多Agent系统协调跨学科科学推理 | 领域专用系统缺乏跨学科泛化能力 | 科学奥林匹克竞赛及科研推理 |
| 48 | http://arxiv.org/abs/2511.08217v1 | MADD: Multi-Agent Drug Discovery Orchestra | 四Agent协作执行药物发现流程 | 药物发现工具复杂难被实验人员使用 | 早期药物发现与化合物筛选 |
| 49 | http://arxiv.org/abs/2511.08274v1 | Multi-Agent GraphRAG: A Text-to-Cypher Framework for Labeled Property Graphs | 多Agent系统生成Cypher查询访问图数据库 | RDF/SPARQL主导下LPG潜力未充分挖掘 | 工业数字孪生与图数据查询 |
| 50 | http://arxiv.org/abs/2511.08319v1 | Adaptive Multi-Agent Response Refinement in Conversational Systems | 多Agent动态协作细化对话响应 | 单LLM难以兼顾事实性/个性化/连贯性 | 对话系统与个性化交互 |
| 51 | http://arxiv.org/abs/2511.08538v2 | Fair Multi-agent Persuasion with Submodular Constraints | 贝叶斯说服框架下实现Agent效用公平分配 | 资源分配中多Agent效用公平性难以保证 | 多Agent资源分配与博弈 |
| 52 | http://arxiv.org/abs/2511.08710v3 | Convergence dynamics of Agent-to-Agent Interactions with Misaligned objectives | 理论框架分析目标错位下Agent交互收敛动力学 | 目标错位导致Agent无法达到各自目标 | 多Agent LLM系统稳定性分析 |
| 53 | http://arxiv.org/abs/2511.09149v3 | Enabling Agents to Communicate Entirely in Latent Space | Interlat实现Agent潜空间直接通信 | 自然语言通信限制信息深度与细微差别 | 异构模型间Agent协作 |
| 54 | http://arxiv.org/abs/2511.10687v2 | Who Gets the Reward, Who Gets the Blame? Evaluation-Aligned Training Signals for Multi-LLM Agents | 统一博弈论归因与过程奖励建模训练信号 | 缺乏系统评估与Agent级学习连接方法 | 多LLM Agent系统训练 |
| 55 | http://arxiv.org/abs/2511.11635v1 | EduAgentQG: A Multi-Agent Workflow Framework for Personalized Question Generation | 五智能体协作框架，迭代反馈循环生成个性化问题 | 手动出题耗时、质量不稳定、多样性不足 | 教育领域个性化问题生成 |
| 56 | http://arxiv.org/abs/2511.06134v1 | Maestro: Learning to Collaborate via Conditional Listwise Policy Optimization for Multi-Agent LLMs | 探索-合成解耦架构，条件列表策略优化 | 多Agent协作中过早共识、错误传播、信用分配问题 | 数学推理与通用问题求解 |
| 57 | http://arxiv.org/abs/2511.06727v2 | S-DAG: A Subject-Based Directed Acyclic Graph for Multi-Agent Heterogeneous Reasoning | 主题有向无环图，细粒度主题级多Agent协作 | 混合主题问题推理、任务级模型选择过粗 | 多主题复杂推理任务 |
| 58 | http://arxiv.org/abs/2511.07112v2 | More Agents Improve Math Problem Solving but Adversarial Robustness Gap Persists | 采样投票框架评估多Agent数学求解与对抗鲁棒性 | 多Agent协作对抗鲁棒性差距、噪声类型影响 | 数学问题求解与对抗安全 |
| 59 | http://arxiv.org/abs/2511.07784v1 | Can LLM Agents Really Debate? A Controlled Study of Multi-Agent Debate in Logical Reasoning | 逻辑谜题控制研究多Agent辩论机制 | LLM Agent是否真正 deliberative 推理不明确 | 逻辑推理与多Agent辩论 |
| 60 | http://arxiv.org/abs/2511.02200v1 | Optimal-Agent-Selection: State-Aware Routing Framework for Efficient Multi-Agent Collaboration | 状态感知路由框架，自适应选择最佳单智能体协作。 | 多智能体调度僵硬、协调效率低。 | 复杂任务求解的多智能体系统 |
| 61 | http://arxiv.org/abs/2511.02303v1 | Unlocking the Power of Multi-Agent LLM for Reasoning: From Lazy Agents to Deliberation | 因果影响测量与可验证奖励机制，防止 Agent 懒惰。 | 多 Agent 推理中单 Agent 主导，协作失效。 | 复杂推理任务的多 Agent 系统 |
| 62 | http://arxiv.org/abs/2511.02755v1 | Controlling Performance and Budget of a Centralized Multi-agent LLM System with Reinforcement Learning | 集中式控制器协调专家模型池，优化性能成本权衡。 | 去中心化框架导致推理成本不可控。 | 多模型协作的 LLM 系统 |
| 63 | http://arxiv.org/abs/2511.02834v2 | Agent-Omni: Test-Time Multimodal Reasoning via Model Coordination for Understanding Anything | 主 Agent 协调模态特定 Agent，实现无需重训练的全能推理。 | 全模态模型训练成本高且缺乏推理支持。 | 多模态理解与推理任务 |

[返回目录](#目录)

<a id="cat-04"></a>

## Agent学习与自进化

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2511.13646v3 | Live-SWE-agent: Can Software Engineering Agents Self-Evolve on the Fly? | 首个运行时自主持续进化软件 Agent 框架 | 软件 Agent 设计空间 exhaustive 探索成本高 | 现实世界软件工程任务 |
| 2 | http://arxiv.org/abs/2511.14460v1 | Agent-R1: Training Powerful LLM Agents with End-to-End Reinforcement Learning | 模块化 RL 训练框架，扩展 MDP 定义 Agent 组件 | 缺乏针对 LLM Agent 上下文的有效 RL 训练方法 | 复杂问题解决 LLM Agent 训练 |
| 3 | http://arxiv.org/abs/2511.15055v1 | Learning Human-Like RL Agents Through Trajectory Optimization With Action Quantization | 引入 Macro Action Quantization 蒸馏人类演示 | 奖励驱动 RL 代理行为不自然，缺乏可解释性 | 人类-like 强化学习代理 |
| 4 | http://arxiv.org/abs/2511.15392v1 | DEPO: Dual-Efficiency Preference Optimization for LLM Agents | 双效率偏好优化，同时优化步级和轨迹级效率 | LLM Agent推理链过长导致交互效率低下的问题 | WebShop和BabyAI任务场景 |
| 5 | http://arxiv.org/abs/2511.15593v2 | What Does It Take to Be a Good AI Research Agent? Studying the Role of Ideation Diversity | 分析思想多样性对Agent性能的影响并进行控制实验 | AI研究Agent成功或失败的关键因素尚未完全理解 | MLE-bench上的AI研究Agent |
| 6 | http://arxiv.org/abs/2511.15915v1 | AccelOpt: A Self-Improving LLM Agentic System for AI Accelerator Kernel Optimization | 自改进LLM Agent系统通过迭代生成优化内核 | AI加速器内核优化需要专家提供的硬件特定知识 | AWS Trainium加速器内核优化 |
| 7 | http://arxiv.org/abs/2511.16043v1 | Agent0: Unleashing Self-Evolving Agents from Zero Data via Tool-Integrated Reasoning | 双Agent共生竞争通过多步协同进化和工具集成 | LLM Agent依赖人工策划数据限制可扩展性 | 数学和通用推理任务 |
| 8 | http://arxiv.org/abs/2511.16108v1 | SkyRL-Agent: Efficient RL Training for Multi-turn LLM Agent | 高效异步调度器和工具增强训练配方优化多轮Agent训练 | 多轮长视野Agent训练效率低下成本高 | 软件工程和其他Agent任务 |
| 9 | http://arxiv.org/abs/2512.20629v3 | Learning Evolving Latent Strategies for Multi-Agent Language Systems without Model Fine-Tuning | 双循环架构更新外部潜在向量，无需微调模型参数实现策略持续进化 | 解决语言模型在多轮交互中难以持续适应策略且微调成本高的问题 | 多智能体语言系统 |
| 10 | http://arxiv.org/abs/2511.22074v2 | Real-Time Procedural Learning From Experience for AI Agents | PRAXIS 机制，通过状态索引检索过去经验后果 | LLM 智能体缺乏部署后过程知识获取机制 | 动态状态环境 web 浏览 |
| 11 | http://arxiv.org/abs/2511.22254v4 | Co-Evolving Agents: Learning from Failures as Hard Negatives | 目标智能体与失败智能体协同进化，利用硬负样本优化 | 依赖预测轨迹易过拟合，缺乏地面真值监督 | 任务专用智能体自我改进 |
| 12 | http://arxiv.org/abs/2511.22751v1 | Exact Learning of Arithmetic with Differentiable Agents | 可微分有限状态 transducers，实现精确算法技能学习 | 梯度方法难以 exact 学习算法，长度泛化能力弱 | 算术任务精确学习 |
| 13 | http://arxiv.org/abs/2511.23002v2 | JarvisEvo: Towards a Self-Evolving Photo Editing Agent with Synergistic Editor-Evaluator Optimization | 协同编辑器 - 评估器优化，无需外部奖励自我改进 | 指令幻觉与奖励 hacking，静态奖励模型易被 exploit | 照片编辑智能体 |
| 14 | http://arxiv.org/abs/2511.23262v1 | Adapting Like Humans: A Metacognitive Agent with Test-time Reasoning | 元认知测试时推理框架，装备元级别与对象级别模块 | VLM 测试时适应新任务效率低，缺乏策略 refinement | 视觉语言模型测试时适应 |
| 15 | http://arxiv.org/abs/2511.19900v2 | Agent0-VL: Exploring Self-Evolving Agent for Tool-Integrated Vision-Language Reasoning | 工具集成自进化视觉语言推理 Agent | 视觉推理自我评估幻觉问题 | 多模态推理任务 |
| 16 | http://arxiv.org/abs/2511.20718v2 | Stabilizing Off-Policy Training for Long-Horizon LLM Agent via Turn-Level Importance Sampling and Clipping-Triggered Normalization | 轮级重要性采样稳定长程 LLM Agent 训练 | 长程 Agent 离线训练不稳定 | 多轮 LLM Agent 训练 |
| 17 | http://arxiv.org/abs/2511.19436v1 | VDC-Agent: When Video Detailed Captioners Evolve Themselves via Agentic Self-Reflection | 自进化视频详细 captioning 框架，通过智能体自反思无需标注。 | 解决视频 captioning 依赖人工标注或大教师模型的问题。 | 视频理解/自进化 |
| 18 | http://arxiv.org/abs/2511.11828v1 | Conformal Constrained Policy Optimization for Cost-Effective LLM Agents | CCPO联合优化成本感知策略与自适应阈值 | LLM Agent高计算/API成本问题 | 多跳问答任务 |
| 19 | http://arxiv.org/abs/2511.12844v4 | Towards Reinforcement Learning from Neural Feedback: Mapping fNIRS Signals to Agent Performance | 从fNIRS神经信号映射Agent性能，实现RLNF | RLHF依赖显式反馈，探索隐式神经信号反馈 | 多域Agent训练 |
| 20 | http://arxiv.org/abs/2511.12908v2 | DeepSport: A Multimodal Large Language Model for Comprehensive Sports Video Reasoning via Agentic Reinforcement Learning | 端到端训练MLLM，主动迭代推理，动态提取帧 | 体育视频理解需高速动态、复杂规则、长时序 | 多任务多体育视频 |
| 21 | http://arxiv.org/abs/2511.12997v1 | WebCoach: Self-Evolving Web Agents with Cross-Session Memory Guidance | 跨会话记忆引导，WebCondenser+外部记忆+Coach三组件 | Web Agent重复错误、无法跨会话学习 Past经验 | 复杂网页浏览任务 |
| 22 | http://arxiv.org/abs/2511.13288v2 | Multi-Agent Deep Research: Training Multi-Agent Systems with M-GRPO | M-GRPO：分层GRPO，解耦训练管道，轨迹对齐方案 | 多Agent系统垂直领域训练不足，异构Agent优化困难 | 工具增强推理任务 |
| 23 | http://arxiv.org/abs/2511.00413v3 | Tree Training: Accelerating Agentic LLMs Training via Shared Prefix Reuse | 引入树状训练框架与梯度恢复机制，复用共享前缀加速 Agentic LLM 训练 | 消除多分支执行轨迹训练中的冗余计算，加速监督微调与 RL 更新 | Agentic LLM 训练 pipeline |
| 24 | http://arxiv.org/abs/2511.00802v1 | GrowthHacker: Automated Off-Policy Evaluation Optimization Using Code-Modifying LLM Agents | 利用 LLM 智能体迭代优化代码，自动评估并提升离线策略评估效果 | 解决在线 A/B 测试成本高及离线评估优化缺乏自动化的问题 | 推荐系统与数据驱动决策 |
| 25 | http://arxiv.org/abs/2511.01093v1 | Continual Learning, Not Training: Online Adaptation For Agents | 双智能体架构解耦推理与执行，实现无梯度持续学习与系统级编排 | 解决部署智能体实时适应难及基于梯度重训练成本高的问题 | 网络安全威胁调查智能体 |
| 26 | http://arxiv.org/abs/2511.01824v1 | Simulating Environments with Reasoning Models for Agent Training | 利用 LLM 模拟环境反馈，无需真实 testbed 即可进行 SFT 与 RL 训练 | 解决定制训练环境构建沉重、脆弱及限制 Agent 进步的问题 | 通用 Agent 规模化训练 |
| 27 | http://arxiv.org/abs/2511.03773v2 | Scaling Agent Learning via Experience Synthesis | 合成多样化经验数据，支持在线 RL 训练和课程学习 | 解决 RL 智能体数据采集成本高、任务多样性不足的问题 | 通用自主智能体训练 |
| 28 | http://arxiv.org/abs/2511.04393v1 | Post-Training LLMs as Better Decision-Making Agents: A Regret-Minimization Approach | 迭代后悔最小化微调，蒸馏低后悔决策轨迹回基座模型 | 解决 LLM 作为决策代理难以实现低后悔与探索利用平衡问题 | 交互式动态环境决策 |
| 29 | http://arxiv.org/abs/2511.04847v4 | Test-Time Adaptation for LLM Agents via Environment Interaction | 在线句法对齐与部署时动态接地，利用环境信息适应 | 解决 LLM 代理难以泛化到未见环境与新函数集的问题 | 通用 LLM 代理部署 |
| 30 | http://arxiv.org/abs/2511.05951v1 | Klear-AgentForge: Forging Agentic Intelligence through Posttraining Scaling | 开源管道训练高性能代理模型，SFT 后多轮 RL 解锁潜力 | 解决开源社区缺乏关键后训练细节阻碍强代理开发问题 | 开源代理模型训练 |
| 31 | http://arxiv.org/abs/2511.10705v1 | Co-EPG: A Framework for Co-Evolution of Planning and Grounding in Autonomous GUI Agents | 规划与接地模型协同进化的自迭代训练框架 | GUI Agent跨模型协同不足、过度依赖合成数据 | 图形用户界面自动化 |
| 32 | http://arxiv.org/abs/2511.10395v1 | AgentEvolver: Towards Efficient Self-Evolving Agent System | 自提问、自导航、自归因三机制驱动自主Agent学习 | 手动构建任务数据集成本高、探索效率低、样本利用率差 | 自主Agent系统 |
| 33 | http://arxiv.org/abs/2511.11770v1 | Learning to Refine: An Agentic RL Approach for Iterative SPARQL Query Construction | 3B模型通过结果驱动RL学习迭代SPARQL查询构建策略 | 一次性生成脆弱，缺乏基于执行反馈的动态调试策略 | 知识图谱问答 |
| 34 | http://arxiv.org/abs/2511.08325v1 | AgentPRM: Process Reward Models for LLM Agents via Step-Wise Promise and Progress | 定义Agent任务过程奖励模型评估决策进展 | 多轮决策任务缺乏有效过程监督信号 | 网页购物与浏览器导航任务 |
| 35 | http://arxiv.org/abs/2511.06449v2 | FLEX: Continuous Agent Evolution via Forward Learning from Experience | 无梯度经验学习范式，结构化经验库 | LLM Agent部署后静态、无法随经验成长 | 数学推理、化学逆合成、蛋白质预测 |
| 36 | http://arxiv.org/abs/2511.02208v1 | Training Proactive and Personalized LLM Agents | 多目标 RL 优化生产力、主动性与个性化三维指标。 | 现有 Agent 缺乏主动提问与用户偏好适应。 | 软件工程与深度研究任务 |
| 37 | http://arxiv.org/abs/2511.02690v1 | Curriculum Design for Trajectory-Constrained Agent: Compressing Chain-of-Thought Tokens in LLMs | 课程学习策略逐渐收紧约束，压缩 CoT 令牌。 | 严格部署约束下 Agent 训练困难。 | 资源受限部署的 LLM  Agent |

[返回目录](#目录)

<a id="cat-05"></a>

## 多Agent强化学习

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2512.00048v1 | Causal Reinforcement Learning based Agent-Patient Interaction with Clinical Domain Knowledge | 集成因果发现与推理 into 策略优化，利用 DAG | 医疗干预数据稀缺，决策需可解释性与因果性 | 痴呆护理等适应性医疗干预 |
| 2 | http://arxiv.org/abs/2511.14378v1 | Emergent Cooperative Driving Strategies for Stop-and-Go Wave Mitigation via Multi-Agent Reinforcement Learning | 发现 cooperative 驾驶策略，缓冲车吸收扰动 | 交通流中 stop-and-go 波影响安全与效率 | 自动驾驶系统与高速公路管理 |
| 3 | http://arxiv.org/abs/2511.14730v5 | Heterogeneous Multi-Agent Proximal Policy Optimization for Power Distribution System Restoration | 应用 HARL 框架协调互联微电网恢复 | 传统优化与 RL 在非线性约束下扩展性有限 | 配电系统大规模停电恢复 |
| 4 | http://arxiv.org/abs/2511.14910v1 | Z-Merge: Multi-Agent Reinforcement Learning for On-Ramp Merging with Zone-Specific V2X Traffic Information | V2X 辅助 MARL 框架，利用区域全局信息协调 | 混合交通环境中匝道汇入安全性与效率低 | 自动驾驶车辆匝道汇入 |
| 5 | http://arxiv.org/abs/2511.15002v1 | Task Specific Sharpness Aware O-RAN Resource Management using Multi Agent Reinforcement Learning | 增强 SAC 算法 with SAM，自适应正则化 | DRL 模型在动态环境中鲁棒性与泛化性差 | 开放无线接入网 (O-RAN) 资源管理 |
| 6 | http://arxiv.org/abs/2511.15053v1 | Distributed primal-dual algorithm for constrained multi-agent reinforcement learning under coupled policies | 分布式原始 - 对偶算法，仅共享局部估计 | 约束 MARL 中策略耦合与安全约束满足难 | 约束多 Agent 强化学习 |
| 7 | http://arxiv.org/abs/2511.15239v2 | Symmetry-Breaking in Multi-Agent Navigation: Winding Number-Aware MPC with a Learned Topological Strategy | 量化合作对称性破缺策略，结合 RL 与 MPC | 分布式导航中无通信易陷入对称性死锁 | 多 Agent 导航与避障 |
| 8 | http://arxiv.org/abs/2511.15284v1 | Path Planning through Multi-Agent Reinforcement Learning in Dynamic Environments | 区域感知 RL 框架，分布式 Agent 局部适应 | 动态环境路径规划假设完全不可预测，扩展性差 | 动态环境路径规划 |
| 9 | http://arxiv.org/abs/2511.17653v1 | MARL-CC: A Mathematical Framework for Multi-Agent Reinforcement Learning in Connected Autonomous Vehicles | 整合微分几何控制、贝叶斯推理和Shapley值信用分配 | 现有MARL方法在非线性动力学下无法保证稳定性最优性 | 联网自动驾驶车辆协同决策 |
| 10 | http://arxiv.org/abs/2511.17654v1 | Dialogue Diplomats: An End-to-End Multi-Agent Reinforcement Learning System for Automated Conflict Resolution and Consensus Building | 分层共识网络结合注意力机制和图神经网络建模Agent依赖 | 多Agent系统谈判和协作决策中的冲突解决挑战 | 自动化冲突解决和共识构建 |
| 11 | http://arxiv.org/abs/2511.17656v1 | Multi-Agent Coordination in Autonomous Vehicle Routing: A Simulation-Based Study of Communication, Memory, and Routing Loops | 对象记忆管理OMM机制使Agent保留和共享障碍物知识 | 无持久障碍物记忆的车辆陷入低效路径重计算循环 | 自动驾驶车辆路由协调 |
| 12 | http://arxiv.org/abs/2511.16916v1 | Hybrid Differential Reward: Combining Temporal Difference and Action Gradients for Efficient Multi-Agent Reinforcement Learning in Cooperative Driving | 混合差分奖励机制整合时间差分奖励和动作梯度奖励 | 传统基于状态奖励函数在高频连续控制中奖励差异消失 | 多车合作驾驶任务 |
| 13 | http://arxiv.org/abs/2511.17165v1 | MIR: Efficient Exploration in Episodic Multi-Agent Reinforcement Learning via Mutual Intrinsic Reward | 引入相互内在奖励，激励个体探索影响队友的动作 | 解决 episodic 奖励稀疏及联合动作空间探索难问题 | episodic 多 Agent 强化学习 |
| 14 | http://arxiv.org/abs/2511.17435v2 | Multi-Agent Pointer Transformer: Seq-to-Seq Reinforcement Learning for Multi-Vehicle Dynamic Pickup-Delivery Problems | 结合 Transformer 与 Pointer Network 生成联合动作序列 | 解决多车动态配送中联合动作分布建模难问题 | 多车动态取送货问题 |
| 15 | http://arxiv.org/abs/2511.17915v4 | DISPATCH -- Decentralized Informed Spatial Planning and Assignment of Tasks for Cooperative Heterogeneous Agents | 连接 EG 均衡与去中心化学习，实现公平效率平衡 | 解决异构多 Agent 系统中任务分配公平性及部分可观测问题 | 多机器人配送/网约车 |
| 16 | http://arxiv.org/abs/2511.18181v1 | MOMA-AC: A preference-driven actor-critic framework for continuous multi-objective multi-agent reinforcement learning | 首个连续空间内环 actor-critic 框架，编码 Pareto front | 解决连续 MOMARL 缺乏专用框架及多目标 trade-off 问题 | 连续多目标多 Agent RL |
| 17 | http://arxiv.org/abs/2511.23315v1 | Emergent Coordination and Phase Structure in Independent Multi-Agent Reinforcement Learning | 构建基于合作成功率与稳定性指数的相位图，揭示去中心化 MARL 的三阶段结构 | 解决去中心化多智能体学习中协调何时出现、波动或崩溃的动态特征不明问题 | 多智能体强化学习系统 |
| 18 | http://arxiv.org/abs/2511.21934v2 | Heterogeneous Multi-Agent Reinforcement Learning with Attention for Cooperative and Scalable Feature Transformation | 异构多智能体 RL 框架，共享评论机制增强通信 | 特征空间动态扩展导致不稳定，Agent 间协作不足 | 结构化数据特征转换 |
| 19 | http://arxiv.org/abs/2511.22076v1 | Hybrid Stackelberg Game and Diffusion-based Auction for Two-tier Agentic AI Task Offloading in Internet of Agents | 混合 Stackelberg 博弈与扩散拍卖模型，优化任务卸载 | 无线智能体资源有限，需协调移动与固定智能体 | 智能体互联网任务卸载 |
| 20 | http://arxiv.org/abs/2511.22105v1 | Energy Efficient Sleep Mode Optimization in 5G mmWave Networks via Multi Agent Deep Reinforcement Learning | MARL-DDQN 框架，自适应睡眠模式优化能效 | 静态流量模型无法捕捉非平稳动态，状态空间大 | 5G mmWave 网络优化 |
| 21 | http://arxiv.org/abs/2511.22708v1 | Distributed quantum architecture search using multi-agent reinforcement learning | 多智能体 RL 算法，每个智能体作用于量子电路块 | 单智能体 RL 扩展性差，动作空间维数随量子比特增加 | 量子架构搜索 |
| 22 | http://arxiv.org/abs/2511.23148v1 | Peer-to-Peer Energy Trading in Dairy Farms using Multi-Agent Reinforcement Learning | 结合 MARL 与 P2P 交易机制，优化能源分配与成本 | 传统规则方法在动态环境下表现差，难适应变化 | 农村社区能源管理 |
| 23 | http://arxiv.org/abs/2512.20624v1 | Quantum-Inspired Multi Agent Reinforcement Learning for Exploration Exploitation Optimization in UAV-Assisted 6G Network Deployment | 量子启发多 Agent 强化学习优化探索利用 | UAV 网络部署探索利用平衡 | 6G 无人机网络 |
| 24 | http://arxiv.org/abs/2511.20468v1 | DRAFT-RL: Multi-Agent Chain-of-Draft Reasoning for Reinforcement Learning-Enhanced LLMs | 多 Agent 草稿链推理与强化学习结合 | 多 Agent 反思缺乏结构多样性探索 | 复杂推理任务 |
| 25 | http://arxiv.org/abs/2511.21083v2 | Dual-Agent Reinforcement Learning for Adaptive and Cost-Aware Visual-Inertial Odometry | 双 Agent RL 策略优化视觉惯性里程计效率 | VIO 精度与计算效率权衡困难 | 机器人导航定位 |
| 26 | http://arxiv.org/abs/2511.21304v1 | Sparse shepherding control of large-scale multi-agent systems via Reinforcement Learning | 稀疏间接控制大规模多 Agent 系统 RL 框架 | 大规模系统稀疏执行器控制难 | 群体机器人控制 |
| 27 | http://arxiv.org/abs/2511.18671v2 | Multi-Agent Cross-Entropy Method with Monotonic Nonlinear Critic Decomposition | 提出多智能体交叉熵方法，结合单调非线性评论家分解。 | 解决集中式训练与分布式执行不匹配的问题。 | 多智能体强化学习 |
| 28 | http://arxiv.org/abs/2511.19524v2 | VideoChat-M1: Collaborative Policy Planning for Video Understanding via Multi-Agent Reinforcement Learning | 多智能体强化学习协作策略规划，动态优化工具调用策略。 | 解决视频理解中工具调用机制静态且不可学习的问题。 | 视频理解 |
| 29 | http://arxiv.org/abs/2511.18958v2 | Learning to Compress Graphs via Dual Agents for Consistent Topological Robustness Evaluation | 双智能体强化学习框架，协同识别结构 vital 和冗余节点。 | 解决大图鲁棒性评估计算昂贵且难以扩展的问题。 | 图数据/鲁棒性 |
| 30 | http://arxiv.org/abs/2511.19146v2 | VIL2C: Value-of-Information Aware Low-Latency Communication for Multi-Agent Reinforcement Learning | 价值信息感知低延迟通信方案，主动调整延迟分布。 | 解决多智能体强化学习中通信延迟影响性能的问题。 | 多智能体强化学习 |
| 31 | http://arxiv.org/abs/2511.19562v1 | Trust-Based Social Learning for Communication (TSLEC) Protocol Evolution in Multi-Agent Reinforcement Learning | 基于信任的社交学习框架，显式传授成功策略给 peers。 | 解决多智能体 emergent 通信收敛慢且协议次优的问题。 | 多智能体强化学习 |
| 32 | http://arxiv.org/abs/2511.19253v2 | MAESTRO: Multi-Agent Environment Shaping through Task and Reward Optimization | 多智能体环境塑造框架，利用大模型生成课程与奖励函数。 | 解决合作多智能体强化学习中奖励设计与课程构建瓶颈。 | 多智能体强化学习 |
| 33 | http://arxiv.org/abs/2511.19368v1 | LLM-Driven Stationarity-Aware Expert Demonstrations for Multi-Agent Reinforcement Learning in Mobile Systems | 可扩展多智能体框架，集成大模型驱动专家演示与自主探索。 | 解决多智能体强化学习因非平稳性导致训练不稳定问题。 | 移动系统/强化学习 |
| 34 | http://arxiv.org/abs/2511.19773v1 | Scaling Agentic Reinforcement Learning for Tool-Integrated Reasoning in VLMs | 可扩展训练环境，激励视觉语言模型的工具集成视觉推理能力。 | 解决视觉语言模型多步视觉交互推理能力有限的问题。 | 视觉语言模型/强化学习 |
| 35 | http://arxiv.org/abs/2511.11992v1 | Goal-Oriented Multi-Agent Reinforcement Learning for Decentralized Agent Teams | 目标感知通信策略实现选择性信息共享 | 去中心化车辆团队协调与部分可观测问题 | 跨域自动驾驶车辆 |
| 36 | http://arxiv.org/abs/2511.12123v1 | HCPO: Hierarchical Conductor-Based Policy Optimization in Multi-Agent Reinforcement Learning | 基于指挥器的联合策略框架协调探索 | 合作MARL中独立探索限制联合策略表达能力 | StarCraftII等多Agent基准 |
| 37 | http://arxiv.org/abs/2511.12792v1 | Multi-Agent Reinforcement Learning for Heterogeneous Satellite Cluster Resources Optimization | MARL协调异构卫星集群，平衡成像性能与资源利用 | 地球观测任务实时、不确定、去中心化资源优化 | 异构卫星集群 |
| 38 | http://arxiv.org/abs/2511.12876v3 | Think, Speak, Decide: Language-Augmented Multi-Agent Reinforcement Learning for Economic Decision-Making | LAMP框架：思考-说话-决策管道整合语言与经济决策 | MARL难以处理语言语义模糊与上下文丰富性 | 经济决策模拟 |
| 39 | http://arxiv.org/abs/2511.13103v1 | Transformer-Based Scalable Multi-Agent Reinforcement Learning for Networked Systems with Long-Range Interactions | STACCA：共享Transformer Actor-Critic建模长程依赖 | MARL难以捕捉长程依赖与跨网络拓扑泛化 | 大规模网络控制系统 |
| 40 | http://arxiv.org/abs/2511.13137v1 | Conditional Diffusion Model for Multi-Agent Dynamic Task Decomposition | C D³T：条件扩散模型预测子任务效果，两层分层MARL | 动态任务分解需大量训练样本，联合动作空间大 | 合作MARL长程任务 |
| 41 | http://arxiv.org/abs/2511.00370v1 | Who Can We Trust? Scope-Aware Video Moment Retrieval with Multi-Agent Conflict | 基于强化学习与时序检索，利用多智能体冲突解决机制定位视频片段 | 解决多模型定位结果冲突及无对应时刻查询的识别问题 | 视频时刻检索任务 |
| 42 | http://arxiv.org/abs/2511.00767v1 | Power Control Based on Multi-Agent Deep Q Network for D2D Communication | 提出基于多智能体 DQN 的自适应功率控制算法，减少系统干扰 | 解决 D2D 通信中干扰控制难及系统吞吐量下降的问题 | 蜂窝网络下的 D2D 通信 |
| 43 | http://arxiv.org/abs/2511.01008v1 | MARS-SQL: A multi-agent reinforcement learning framework for Text-to-SQL | 三智能体协作结合交互式 RL，通过执行反馈动态修正 SQL 生成策略 | 解决复杂自然语言转 SQL 查询需环境交互及自我修正的问题 | Text-to-SQL 查询生成 |
| 44 | http://arxiv.org/abs/2511.01078v1 | Predictive Auxiliary Learning for Belief-based Multi-Agent Systems | 引入辅助预测任务学习信念模型，增强部分 observable 环境下的 MARL | 解决多智能体强化学习在部分可观测环境下训练不稳定问题 | 多智能体强化学习训练 |
| 45 | http://arxiv.org/abs/2511.01310v2 | From Pixels to Cooperation Multi Agent Reinforcement Learning based on Multimodal World Models | 基于多模态世界模型学习 latent 表示，解耦表征学习与策略学习 | 解决多智能体直接从高维多模态输入学习协作策略样本效率低问题 | 多智能体协作策略学习 |
| 46 | http://arxiv.org/abs/2511.02016v1 | ABIDES-MARL: A Multi-Agent Reinforcement Learning Environment for Endogenous Price Formation and Execution in a Limit Order Book | 结合 MARL 与限价订单簿仿真，研究复杂金融市场游戏中的均衡行为 | 解决有限异质智能体多周期交易游戏均衡行为研究缺乏重现性问题 | 金融市场微观结构仿真 |
| 47 | http://arxiv.org/abs/2511.04594v2 | Regret Lower Bounds for Decentralized Multi-Agent Stochastic Shortest Path Problems | 推导去中心化多智能体 SSP 问题的后悔下界，揭示学习难度 | 解决去中心化多智能体控制学习复杂性未被充分探索问题 | 多智能体强化学习理论 |
| 48 | http://arxiv.org/abs/2511.04904v1 | Multi-Agent Craftax: Benchmarking Open-Ended Multi-Agent Reinforcement Learning at the Hyperscale | 扩展 Craftax 支持多智能体，评估长期依赖与泛化能力 | 解决现有 MARL 基准难以压力测试长期依赖与泛化问题 | 多智能体强化学习基准 |
| 49 | http://arxiv.org/abs/2511.05005v2 | Multi-agent Coordination via Flow Matching | 学习基于流的联合行为表示，蒸馏为去中心化一步策略 | 解决多智能体协调中性能与计算成本权衡的问题 | 多智能体协调控制 |
| 50 | http://arxiv.org/abs/2511.09535v1 | Robust and Diverse Multi-Agent Learning via Rational Policy Gradient | 提出理性策略梯度(RPG)，避免合作场景中的自我破坏 | 对抗优化在合作设置中导致Agent自我破坏的问题 | 多Agent强化学习环境 |
| 51 | http://arxiv.org/abs/2511.09792v1 | Beyond Monotonicity: Revisiting Factorization Principles in Multi-Agent Q-Learning | 证明非单调值分解在梯度流下稳定收敛到IGM一致解 | 单调性约束限制表达能力与算法复杂度的权衡 | 多Agent强化学习算法 |
| 52 | http://arxiv.org/abs/2511.11373v1 | MarsRL: Advancing Multi-Agent Reasoning System via Reinforcement Learning with Agentic Pipeline Parallelism | 代理特定奖励机制+流水线并行训练联合优化所有Agent | 开源模型批评与纠正能力不足，难以泛化多Agent推理 | 多Agent推理系统 |
| 53 | http://arxiv.org/abs/2511.11393v1 | Robust and Efficient Communication in Multi-Agent Reinforcement Learning | 系统综述MARL在现实约束下的鲁棒高效通信策略 | 现有方法假设通信即时可靠带宽无限，现实部署难满足 | 合作自动驾驶/SLAM/联邦学习 |
| 54 | http://arxiv.org/abs/2511.08412v1 | ARAC: Adaptive Regularized Multi-Agent Soft Actor-Critic in Graph-Structured Adversarial Games | 注意力GNN+自适应散度正则化MARL | 图结构对抗任务中稀疏奖励阻碍学习 | 追捕与对抗博弈场景 |
| 55 | http://arxiv.org/abs/2511.08832v1 | TIGER-MARL: Enhancing Multi-Agent Reinforcement Learning with Temporal Information through Graph-based Embeddings and Representations | 动态时序图嵌入捕捉Agent交互演化 | 静态图忽略交互时序演化影响协调 | 协调密集型多Agent任务 |
| 56 | http://arxiv.org/abs/2511.08926v1 | Achieving Equilibrium under Utility Heterogeneity: An Agent-Attention Framework for Multi-Agent Multi-Objective Reinforcement Learning | Agent-Attention框架学习全局效用函数 | 异构效用函数下训练非平稳性加剧 | 多目标多Agent决策系统 |
| 57 | http://arxiv.org/abs/2511.09171v1 | Learning Efficient Communication Protocols for Multi-Agent Reinforcement Learning | 学习多轮通信协议提升通信效率 | 多Agent通信产生冗余非本质消息 | 分布式环境多Agent协调 |
| 58 | http://arxiv.org/abs/2511.06142v1 | MALinZero: Efficient Low-Dimensional Search for Mastering Complex Multi-Agent Planning | 低维表示结构投影，LinUCT树搜索算法 | 多Agent规划中组合动作空间指数级增长 | 多Agent规划与决策 |
| 59 | http://arxiv.org/abs/2511.06398v1 | Dynamic Electric Vehicle Charging Pricing for Load Balancing in Power Distribution Networks based on Collaborative DDPG Agents | 协作DDPG Agent动态EV充电定价策略 | EV充电导致电网不稳定、需负载均衡 | 电力分配网络与EV充电管理 |
| 60 | http://arxiv.org/abs/2511.07071v1 | Multi-Agent Reinforcement Learning for Deadlock Handling among Autonomous Mobile Robots | MARL处理自主移动机器人死锁，CTDE模式 | 物流系统死锁降低吞吐量、规则方法适应性差 | 内部物流与自主移动机器人 |
| 61 | http://arxiv.org/abs/2511.07366v2 | UAV-Assisted Resilience in 6G and Beyond Network Energy Saving: A Multi-Agent DRL Approach | MADDPG框架优化UAV轨迹、功率与用户关联 | 6G网络节能场景下基站休眠的用户服务韧性 | 6G网络与UAV辅助通信 |
| 62 | http://arxiv.org/abs/2511.07707v1 | A Negotiation-Based Multi-Agent Reinforcement Learning Approach for Dynamic Scheduling of Reconfigurable Manufacturing Systems | 协商机制增强DQN Agent动态调度可重构制造系统 | 可重构制造系统实时生产规划调度复杂 | 智能制造与生产调度 |
| 63 | http://arxiv.org/abs/2511.07778v1 | A Historical Interaction-Enhanced Shapley Policy Gradient Algorithm for Multi-Agent Credit Assignment | 历史交互增强Shapley策略梯度算法 | 强耦合任务中个体贡献捕获难、训练稳定性差 | 多Agent协作信用分配 |
| 64 | http://arxiv.org/abs/2511.02136v1 | JaxMARL-HFT: GPU-Accelerated Large-Scale Multi-Agent Reinforcement Learning for High-Frequency Trading | 首个 GPU 加速 HFT 多智能体 RL 环境，训练提速 240 倍。 | 高频交易代理建模难、计算成本高。 | 高频金融市场交易 |
| 65 | http://arxiv.org/abs/2511.02304v1 | Automata-Conditioned Cooperative Multi-Agent Reinforcement Learning | 自动机条件化协作 MARL，实现任务感知多步协调。 | 多任务多智能体策略样本效率低。 | 合作性 temporal 目标任务 |
| 66 | http://arxiv.org/abs/2511.02314v1 | Large-scale automatic carbon ion treatment planning for head and neck cancers via parallel multi-agent reinforcement learning | 并行 MARL 框架同时调优 45 个治疗计划参数。 | 碳离子治疗计划参数空间大、调优慢。 | 头颈癌碳离子治疗计划 |
| 67 | http://arxiv.org/abs/2511.02762v1 | From Solo to Symphony: Orchestrating Multi-Agent Collaboration with Single-Agent Demos | 从单人演示迁移知识到协作学习，提升训练效率。 | 多 Agent 训练数据获取成本高、效率低。 | 多 Agent 协作强化学习 |
| 68 | http://arxiv.org/abs/2511.03100v1 | Scaling Multi-Agent Environment Co-Design with Diffusion Models | 扩散模型协同设计 Agent 策略与环境配置。 | 现有协同设计方法难以扩展到高维空间。 | 多 Agent 环境协同设计 |
| 69 | http://arxiv.org/abs/2511.03348v2 | Learning Communication Skills in Multi-task Multi-agent Deep Reinforcement Learning | 多任务通信技能，Transformer 编码共享消息空间。 | 多任务下 Agent 间协调与知识迁移难。 | 多任务多 Agent 深度强化学习 |

[返回目录](#目录)

<a id="cat-06"></a>

## Agent架构与框架设计

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2511.13983v1 | MoMoE: A Mixture of Expert Agent Model for Financial Sentiment Analysis | 结合 MoE 架构与协作多智能体框架的混合模型 | 单一模型难以兼顾任务分解与计算可行性 | 金融情感分析 |
| 2 | http://arxiv.org/abs/2511.14043v2 | AISAC: An Integrated multi-agent System for Transparent, Retrieval-Grounded Scientific Assistance | 提供受治理的执行基板，强制角色语义与预算编排 | 科学实践中缺乏可追溯、可复现的代理执行环境 | 科学推理与辅助研究 |
| 3 | http://arxiv.org/abs/2511.14446v1 | Agentic Video Intelligence: A Flexible Framework for Advanced Video Exploration and Understanding | 提出 Retrieve-Perceive-Review 三阶段推理过程 | 现有 VLM 单 pass 处理，缺乏证据重访与迭代 | 高级视频探索与理解 |
| 4 | http://arxiv.org/abs/2511.15061v1 | Beyond GeneGPT: A Multi-Agent Architecture with Open-Source LLMs for Enhanced Genomic Question Answering | 模块化多 Agent 框架，扩展 GeneGPT 支持开源模型 | 专有模型依赖限制扩展性，增加成本与隐私风险 | 基因组问答系统 |
| 5 | http://arxiv.org/abs/2511.15351v2 | Octopus: Agentic Multimodal Reasoning with Six-Capability Orchestration | 六能力编排的多模态推理框架，动态选择合适能力 | 多模态推理模型缺乏自主探索多样化推理路径的能力 | 多模态推理任务 |
| 6 | http://arxiv.org/abs/2511.16402v1 | Trustworthy AI in the Agentic Lakehouse: from Concurrency to Governance | 提出Agent优先设计Bauplan重新实现数据和计算隔离 | 传统数据湖不适合Agent访问模式导致信任问题 | 企业生产数据Agent工作流 |
| 7 | http://arxiv.org/abs/2511.17673v5 | Bridging Symbolic Control and Neural Reasoning in LLM Agents: Structured Cognitive Loop with a Governance Layer | 结构化认知循环SCL将Agent认知分为五阶段并应用软符号控制 | LLM Agent存在推理执行纠缠、记忆易失和动作序列失控问题 | 多步条件推理任务 |
| 8 | http://arxiv.org/abs/2511.17198v1 | Designing Domain-Specific Agents via Hierarchical Task Abstraction Mechanism | 提出层次任务抽象机制 (HTAM)，镜像领域任务依赖图 | 解决通用框架在 specialized domains 工作流结构化不足问题 | 遥感等专用领域代理 |
| 9 | http://arxiv.org/abs/2511.17332v2 | Agentifying Agentic AI | 结合 AAMAS 概念工具（BDI 等）与数据驱动方法 | 解决 Agentic AI 缺乏显式认知/合作/治理模型问题 | 自主代理系统理论 |
| 10 | http://arxiv.org/abs/2511.19477v1 | Building Browser Agents: Architecture, Security, and Practical Solutions | 混合上下文管理，专用工具编程约束 enforced via code | 解决通用浏览智能因 prompt 注入 fundamentally unsafe 问题 | 生产级浏览器代理 |
| 11 | http://arxiv.org/abs/2511.19483v1 | Z-Space: A Multi-Agent Tool Orchestration Framework for Enterprise-Grade LLM Automation | 多代理协作架构，融合子空间加权算法过滤工具 | 解决企业级 MCP 服务工具匹配难及 context inflation 问题 | 企业级 LLM 自动化 |
| 12 | http://arxiv.org/abs/2511.20693v1 | $A^2Flow:$ Automating Agentic Workflow Generation via Self-Adaptive Abstraction Operators | 基于自适应抽象算子的全自动工作流生成，无需手动预定义 | 解决现有方法依赖手动预定义算子限制泛化性问题 | 代理工作流自动生成 |
| 13 | http://arxiv.org/abs/2512.00602v1 | AgentODRL: A Large Language Model-based Multi-agent System for ODRL Generation | 基于 Orchestrator-Workers 架构，动态协调 specialized Workers 生成 ODRL 策略 | 解决自然语言到 ODRL 翻译中授权策略逻辑复杂及高质量训练数据稀缺问题 | 数据权利管理（ODRL） |
| 14 | http://arxiv.org/abs/2512.00611v1 | Prism: A Minimal Compositional Metalanguage for Specifying Agent Behavior | 定义最小组合元语言，分离可重用核心语法与领域特定词典，工具作为桥梁 | 解决 Agent 行为缺乏可检查、可执行策略规范及控制构造随意的问题 | 软件 Agent 行为规范 |
| 15 | http://arxiv.org/abs/2512.00846v2 | AFRAgent : An Adaptive Feature Renormalization Based High Resolution Aware GUI agent | 提出自适应特征重归一化技术 enrich 低分辨率嵌入并融合高分辨率细节 | 解决 VLM 因视觉编码器特征空间信息有限难以准确识别 widget 及动作问题 | 移动 UI 自动化 |
| 16 | http://arxiv.org/abs/2511.21572v1 | BAMAS: Structuring Budget-Aware Multi-Agent Systems | 基于整数线性规划与强化学习构建预算感知多智能体系统 | 多智能体系统在显式预算约束下的结构设计问题 | 通用多智能体任务 |
| 17 | http://arxiv.org/abs/2511.21686v1 | Matrix: Peer-to-Peer Multi-Agent Synthetic Data Generation Framework | 去中心化点对点框架，通过分布式队列传递消息 | 集中式编排导致扩展瓶颈，硬编码限制灵活性 | 合成数据生成工作流 |
| 18 | http://arxiv.org/abs/2511.22226v1 | Embedded Universal Predictive Intelligence: a coherent framework for multi-agent learning | 基于自预测的嵌入式智能体数学框架，扩展 AIXI 理论 | 多智能体环境非平稳，需预测自身与他人行为 | 通用多智能体学习理论 |
| 19 | http://arxiv.org/abs/2511.22433v3 | SkeletonAgent: An Agentic Interaction Framework for Skeleton-based Action Recognition | 桥接识别模型与 LLM，通过 Questioner 与 Selector 协作 | LLM 孤立查询无反馈，无法提供判别性 cues | 骨架动作识别 |
| 20 | http://arxiv.org/abs/2511.22850v1 | Resolving Evidence Sparsity: Agentic Context Engineering for Long-Document Understanding | SLEUTH 框架，编排 retriever 与四个协作智能体粗到细处理 | 长文档线索分散，检索结果冗余 impair 判断 | 长文档理解任务 |
| 21 | http://arxiv.org/abs/2511.19780v1 | NOEM$^{3}$A: A Neuro-Symbolic Ontology-Enhanced Method for Multi-Intent Understanding in Mobile Agents | 神经符号本体增强移动 Agent 多意图理解框架 | 移动 Agent 多意图理解不准 | 移动 AI 助手 |
| 22 | http://arxiv.org/abs/2511.19947v1 | Towards Edge General Intelligence: Knowledge Distillation for Mobile Agentic AI | 面向边缘通用智能的知识蒸馏 survey | 边缘设备部署 Agentic AI 资源受限 | 移动边缘计算 |
| 23 | http://arxiv.org/abs/2511.20048v1 | Reducing Latency of LLM Search Agent via Speculation-based Algorithm-System Co-Design | 基于推测的算法系统协同设计降低搜索延迟 | LLM 搜索 Agent 串行执行延迟高 | 搜索 Agent 系统 |
| 24 | http://arxiv.org/abs/2511.20975v2 | Aragog: Just-in-Time Model Routing for Scalable Serving of Agentic Workflows | 运行时动态配置路由优化 Agent 工作流服务 | 固定配置无法适应工作流异构负载 | Agent 工作流服务 |
| 25 | http://arxiv.org/abs/2511.18438v1 | LLMs as Firmware Experts: A Runtime-Grown Tree-of-Agents Framework | 递归智能体蜂巢框架，构建运行时智能体树进行去中心化协调。 | 解决大模型在固件安全分析中性能下降问题。 | 固件安全分析 |
| 26 | http://arxiv.org/abs/2511.18538v5 | From Code Foundation Models to Agents and Applications: A Comprehensive Survey and Practical Guide to Code Intelligence | 全面综述代码大模型到智能体的生命周期及实践指南。 | 弥合学术研究与实际部署之间的差距。 | 代码智能/综述 |
| 27 | http://arxiv.org/abs/2511.18653v1 | FHE-Agent: Automating CKKS Configuration for Practical Encrypted Inference via an LLM-Guided Agentic Framework | 大模型引导的智能体框架，自动化完全同态加密配置。 | 解决同态加密配置依赖专家知识且难以部署的问题。 | 隐私计算/加密 |
| 28 | http://arxiv.org/abs/2511.18810v2 | MergeVLA: Cross-Skill Model Merging Toward a Generalist Vision-Language-Action Agent | 面向合并的视觉语言动作架构，保留可合并性设计。 | 解决多技能视觉语言动作模型难以合并 mastered 的问题。 | 机器人/视觉语言动作 |
| 29 | http://arxiv.org/abs/2511.19083v1 | A Multi-Agent LLM Framework for Multi-Domain Low-Resource In-Context NER via Knowledge Retrieval, Disambiguation and Reflective Analysis | 多智能体框架集成知识检索、消歧和反思分析进行命名实体识别。 | 解决低资源场景下上下文学习依赖标注数据的问题。 | 自然语言处理/NER |
| 30 | http://arxiv.org/abs/2511.19635v1 | Agint: Agentic Graph Compilation for Software Engineering Agents | 智能体图编译器，将自然语言指令转化为类型感知代码 DAG。 | 解决编码智能体在上下文管理、延迟与可靠性方面的挑战。 | 软件工程/智能体 |
| 31 | http://arxiv.org/abs/2511.11793v2 | MiroThinker: Pushing the Performance Boundaries of Open-Source Research Agents via Model, Context, and Interactive Scaling | 提出交互扩展作为第三维度，支持每任务600次工具调用 | 解决开源研究Agent性能边界问题 | 复杂研究工作流程 |
| 32 | http://arxiv.org/abs/2511.12254v3 | Mobile-Agent-RAG: Driving Smart Multi-Agent Coordination with Contextual Knowledge Empowerment for Long-Horizon Mobile Automation | 双层检索增强：Manager-RAG规划+Operator-RAG执行 | 移动Agent长程跨应用任务成功率低 | 多应用移动自动化 |
| 33 | http://arxiv.org/abs/2511.12884v1 | Agent READMEs: An Empirical Study of Context Files for Agentic Coding | 首个大规模Agent上下文文件实证研究，分析16类指令 | 开发者缺乏安全/性能等非功能性需求规范 | 代理编码工具 |
| 34 | http://arxiv.org/abs/2511.13118v1 | Extracting Events Like Code: A Multi-Agent Programming Framework for Zero-Shot Event Extraction | AEC框架：检索-规划-编码-验证四子任务专用Agent | 零样本事件提取输出不完整、结构无效 | 多领域事件提取 |
| 35 | http://arxiv.org/abs/2511.13293v1 | Grounded by Experience: Generative Healthcare Prediction Augmented with Hierarchical Agentic Retrieval | GHAR：双Agent架构，统一MDP优化检索与生成协同 | 医疗RAG难以判断何时检索及检索器-生成器协同 | 医疗预测任务 |
| 36 | http://arxiv.org/abs/2511.00330v1 | Sherlock: Reliable and Efficient Agentic Workflow Execution | 利用反事实分析识别易错节点，选择性附加验证器，speculative execution 降低延迟 | 解决 Agentic Workflow 中错误传播及验证成本高、延迟大的问题 | 通用 Agentic Workflow 执行系统 |
| 37 | http://arxiv.org/abs/2511.00628v1 | AgentGit: A Version Control Framework for Reliable and Scalable LLM-Powered Multi-Agent Systems | 引入 Git 式回滚与分支机制，支持多智能体工作流的状态提交与探索 | 解决多智能体系统可靠性差、扩展性难及错误恢复成本高的问题 | LLM 驱动的多智能体系统开发 |
| 38 | http://arxiv.org/abs/2511.00739v2 | A CPU-Centric Perspective on Agentic AI | 从 CPU 视角分析 Agentic AI 系统瓶颈，提出微批处理与混合调度优化 | 揭示 CPU 在智能体工作流中的延迟与能耗瓶颈，优化系统性能 | Agentic AI 系统基础设施 |
| 39 | http://arxiv.org/abs/2511.01015v1 | What's the next frontier for Data-centric AI? Data Savvy Agents | 提出数据智能体四大关键能力，强调主动获取与持续适应数据 | 解决智能体设计中数据处理能力被忽视及部署可靠性差的问题 | 数据为中心的 AI 系统设计 |
| 40 | http://arxiv.org/abs/2511.01633v1 | Scaling Graph Chain-of-Thought Reasoning: A Multi-Agent Framework with Efficient LLM Serving | 多智能体分解推理结合 Graph-CoT 感知服务架构，优化 KV-cache 管理 | 解决单智能体 Graph-CoT 延迟高、token 消耗大及吞吐量低的问题 | 大规模图结构知识推理 |
| 41 | http://arxiv.org/abs/2511.03844v1 | ASAP: an Agentic Solution to Auto-optimize Performance of Large-Scale LLM Training | 多智能体系统自动诊断性能瓶颈，推荐优化分片配置 | 解决大规模 LLM 训练优化依赖人工调优且资源利用率低的问题 | 分布式 LLM 训练系统 |
| 42 | http://arxiv.org/abs/2511.03934v1 | PEFA-AI: Advancing Open-source LLMs for RTL generation using Progressive Error Feedback Agentic-AI | 渐进式错误反馈机制，多智能体协作生成可综合 RTL 代码 | 解决开源 LLM 生成 RTL 代码正确率低且需人工干预的问题 | 硬件描述语言生成 |
| 43 | http://arxiv.org/abs/2511.11628v1 | Mixture-of-Schedulers: An Adaptive Scheduling Agent as a Learned Router for Expert Policies | 自适应调度代理，运行时智能匹配工作负载到专家策略 | 解决操作系统单一静态策略难以优化多样动态工作负载问题 | 操作系统调度优化 |
| 44 | http://arxiv.org/abs/2511.05271v4 | DeepEyesV2: Toward Agentic Multimodal Model | 两阶段训练管道，冷启动建立工具使用模式后 RL 细化 | 解决多模态模型直接 RL 难以诱导鲁棒工具使用行为问题 | 多模态智能体模型 |
| 45 | http://arxiv.org/abs/2511.05385v1 | TeaRAG: A Token-Efficient Agentic Retrieval-Augmented Generation Framework | 压缩检索内容与推理步骤，图检索与直接偏好优化 | 解决代理 RAG 中搜索与推理过程产生大量令牌开销问题 | 高效检索增强生成 |
| 46 | http://arxiv.org/abs/2511.09804v1 | SlideBot: A Multi-Agent Framework for Generating Informative, Reliable, Multi-Modal Presentations | 三支柱框架整合检索、结构化规划和代码生成 | 教育幻灯片生成中内容可靠性与多模态复杂性 | 高等教育/教学场景 |
| 47 | http://arxiv.org/abs/2511.10283v1 | Behavior Modeling for Training-free Building of Private Domain Multi Agent System | 行为建模与文档化实现免训练的私有领域多Agent系统 | 私有领域工具异构、API受限、领域术语复杂 | 企业私有对话系统 |
| 48 | http://arxiv.org/abs/2511.11751v1 | Concept-RuleNet: Grounded Multi-Agent Neurosymbolic Reasoning in Vision Language Models | 多Agent神经符号系统实现视觉接地与可解释推理 | VLM决策缺乏可解释性、易产生幻觉 | 医学影像/自然图像识别 |
| 49 | http://arxiv.org/abs/2511.11332v2 | UFO3: Weaving the Digital Agent Galaxy | TaskConstellation分布式DAG统一编排跨设备异构端点 | 现有框架局限于单OS/设备，跨设备工作流脆弱手动 | 跨设备Agent编排 |
| 50 | http://arxiv.org/abs/2511.11483v3 | ImAgent: A Unified Multimodal Agent Framework for Test-Time Scalable Image Generation | 训练免费统一多模态Agent整合推理、生成与自评估 | T2I模型随机性与提示不一致，现有方法需额外模块 | 文本到图像生成 |
| 51 | http://arxiv.org/abs/2511.11788v1 | MALBO: Optimizing LLM-Based Multi-Agent Teams via Multi-Objective Bayesian Optimization | 多目标贝叶斯优化自动化LLM Agent团队角色分配 | 多Agent系统LLM角色分配组合空间大、评估成本高 | 多Agent团队配置优化 |
| 52 | http://arxiv.org/abs/2511.08475v2 | Designing LLM-based Multi-Agent Systems for Software Engineering Tasks: Quality Attributes, Design Patterns and Rationale | 系统研究LLM-based MAS设计模式与质量属性 | 缺乏LLM-based MAS设计系统研究 | 软件工程任务多Agent系统设计 |
| 53 | http://arxiv.org/abs/2511.08521v1 | UniVA: Universal Video Agent towards Open-Source Next-Generation Video Generalist | Plan-and-Act双Agent架构统一视频工作流 | 专用模型难以实现复杂迭代视频工作流 | 视频理解/编辑/生成综合任务 |
| 54 | http://arxiv.org/abs/2511.09268v1 | Decoding the Configuration of AI Coding Agents: Insights from Claude Code Projects | 实证研究AI编码Agent配置生态系统 | 缺乏对Agent配置文件结构与内容了解 | Claude Code配置实践 |
| 55 | http://arxiv.org/abs/2511.06345v2 | PRAGMA: A Profiling-Reasoned Multi-Agent Framework for Automatic Kernel Optimization | 性能分析引导的AI内核生成框架 | 自动内核生成缺乏底层性能瓶颈推理能力 | GPU/CPU高性能内核优化 |
| 56 | http://arxiv.org/abs/2511.07397v1 | ConvFill: Model Collaboration for Responsive Conversational Voice Agents | 对话填充任务，轻量端侧模型融合后端流式知识 | 云模型延迟高、端侧模型能力弱 | 对话语音Agent与响应延迟 |
| 57 | http://arxiv.org/abs/2511.02230v3 | Continuum: Efficient and Robust Multi-Turn LLM Agent Scheduling with KV Cache Time-to-Live | 引入 KV 缓存 TTL 机制，优化多轮 Agent 任务调度。 | 工具调用导致 KV 缓存失效，推理延迟高。 | 多轮 LLM  Agent 工作流服务 |
| 58 | http://arxiv.org/abs/2511.03023v1 | PublicAgent: Multi-Agent Design Principles From an LLM-Based Open Data Analysis Framework | 分解为专用 Agent 处理意图、发现、分析与报告。 | 端到端工作流存在注意力稀释与错误传播。 | 开放数据分析和决策 |

[返回目录](#目录)

<a id="cat-07"></a>

## Agent评测与基准

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2511.13998v1 | LoCoBench-Agent: An Interactive Benchmark for LLM Agents in Long-Context Software Engineering | 扩展为交互式 Agent 环境，评估多轮对话与工具使用 | 现有基准无法捕捉真实编码 Agent 的多轮交互特性 | 长上下文软件工程 Agent 评估 |
| 2 | http://arxiv.org/abs/2511.14136v1 | Beyond Accuracy: A Multi-Dimensional Framework for Evaluating Enterprise Agentic AI Systems | 提出 CLEAR  holistic 评估框架，涵盖成本与可靠性 | 现有基准忽视企业所需的成本效率与 operational 稳定性 | 企业级 Agent 系统部署评估 |
| 3 | http://arxiv.org/abs/2511.14439v2 | MedBench v4: A Robust and Scalable Benchmark for Evaluating Chinese Medical Language Models, Multimodal Models, and Intelligent Agents | nationwide 云基准，涵盖 70 万 + 专家策划任务 | 缺乏反映真实临床工作流与安全约束的评估框架 | 中国医疗语言模型与 Agent 评估 |
| 4 | http://arxiv.org/abs/2511.15378v1 | Terra Nova: A Comprehensive Challenge Environment for Intelligent Agents | 受文明V启发的综合挑战环境，同时呈现多种RL挑战 | 现有基准仅聚合无关任务，无法测试深度推理能力 | 强化学习智能体研究 |
| 5 | http://arxiv.org/abs/2511.16183v1 | FOOTPASS: A Multi-Modal Multi-Agent Tactical Context Dataset for Play-by-Play Action Spotting in Soccer Broadcast Videos | 首个足球比赛逐帧动作 spotting多模态多Agent战术上下文数据集 | 现有动作识别方法不足以构建可靠的逐帧数据 | 足球视频分析和体育分析 |
| 6 | http://arxiv.org/abs/2511.16383v1 | An Agent-Based Framework for the Automatic Validation of Mathematical Optimization Models | 多Agent方法生成测试API、测试用例和模型突变验证优化模型 | 如何验证LLM生成的优化模型正确性并满足需求 | 数学优化模型验证 |
| 7 | http://arxiv.org/abs/2511.16590v1 | D-GARA: A Dynamic Benchmarking Framework for GUI Agent Robustness in Real-World Anomalies | 动态基准框架评估Android GUI Agent在真实世界异常下的鲁棒性 | 现有GUI Agent数据集静态理想化无法反映真实环境复杂性 | Android GUI Agent鲁棒性评估 |
| 8 | http://arxiv.org/abs/2511.17131v1 | UI-CUBE: Enterprise-Grade Computer Use Agent Benchmarking Beyond Task Accuracy to Operational Reliability | 涵盖操作可靠性的企业级基准，暴露架构局限性 | 解决现有基准忽视生产系统 operational reliability 问题 | 计算机使用代理 (CUA) |
| 9 | http://arxiv.org/abs/2511.17729v4 | M^3-Bench: Multi-Modal, Multi-Hop, Multi-Threaded Tool-Using MLLM Agent Benchmark | 首个 MCP 下多模态工具使用基准，序列化工具调用对齐 | 解决多模态代理工作流一致性及参数保真度评估问题 | 多模态 LLM 代理 |
| 10 | http://arxiv.org/abs/2512.00417v4 | CryptoBench: A Dynamic Benchmark for Expert-Level Evaluation of LLM Agents in Cryptocurrency | 首个专家策划动态基准，包含检索与预测四象限任务，评估加密货币领域能力 | 解决通用基准无法评估加密货币领域极端时间敏感及对抗性信息环境问题 | 加密货币分析 Agent |
| 11 | http://arxiv.org/abs/2512.00756v1 | MPR-GUI: Benchmarking and Enhancing Multilingual Perception and Reasoning in GUI Agents | 提出多语言细粒度感知推理 GUI 基准，提出跨语言干预方法缩小性能差距 | 解决 LVLM 在非英语 GUI 场景感知推理性能差及缺乏细粒度分析问题 | 多语言 GUI Agent |
| 12 | http://arxiv.org/abs/2512.00986v2 | Beyond Retrieval: A Modular Benchmark for Academic Deep Research Agents | 提出 ADRA-Bench 基准及模块化评估范式，评估规划检索推理核心能力 | 解决现有基准聚焦检索忽视高层规划推理及 favor 通用领域问题 | 学术深度研究 Agent |
| 13 | http://arxiv.org/abs/2511.21510v2 | Tool-RoCo: An Agent-as-Tool Self-organization Large Language Model Benchmark in Multi-robot Cooperation | 提出工具化智能体基准，评估多机器人协作自组织能力 | 现有研究忽略智能体自主性与协作工具使用 | 多机器人协作系统 |
| 14 | http://arxiv.org/abs/2511.22138v1 | TinyLLM: Evaluation and Optimization of Small Language Models for Agentic Tasks on Edge Devices | 评估小模型在边缘设备上的智能体任务能力与优化策略 | 边缘设备依赖云基础设施，小模型能力不足 | 边缘设备智能体任务 |
| 15 | http://arxiv.org/abs/2511.22884v1 | InsightEval: An Expert-Curated Benchmark for Assessing Insight Discovery in LLM-Driven Data Agents | 构建 InsightEval 数据集与新指标，评估洞察发现能力 | 现有基准格式不一致，目标构思差，洞察冗余 | 数据智能体洞察发现 |
| 16 | http://arxiv.org/abs/2511.20067v1 | ""Are We Done Yet?"": A Vision-Based Judge for Autonomous Task Completion of Computer Use Agents | 基于视觉语言的自主任务完成度判断框架 | Computer Use Agent 任务完成判断不可靠 | 计算机操作 Agent |
| 17 | http://arxiv.org/abs/2511.20216v5 | CostNav: A Navigation Benchmark for Real-World Economic-Cost Evaluation of Physical AI Agents | 基于经济成本收益分析的物理 Agent 导航基准 | 导航基准忽视现实商业经济约束 | 物理配送 Agent |
| 18 | http://arxiv.org/abs/2511.20766v1 | OpenApps: Simulating Environment Variations to Measure UI-Agent Reliability | 模拟环境变化测量 UI-Agent 可靠性的基准 | 固定环境评估无法反映 Agent 泛化可靠性 | UI 交互 Agent |
| 19 | http://arxiv.org/abs/2511.20694v2 | Reasoning With a Star: A Heliophysics Dataset and Benchmark for Agentic Scientific Reasoning | 构建日物理学数据集与基准，支持智能体科学推理评估。 | 解决科学推理缺乏特定领域基准测试的问题。 | 科学推理/日物理学 |
| 20 | http://arxiv.org/abs/2511.18685v3 | Beyond Description: Cognitively Benchmarking Fine-Grained Action for Embodied Agents | 新基准系统评估具身智能体的细粒度动作智能能力。 | 解决现有基准忽视具身物理交互细粒度动作的问题。 | 具身智能/基准 |
| 21 | http://arxiv.org/abs/2511.19262v1 | Psychometric Tests for AI Agents and Their Moduli Space | 发展心理测试电池模量理论视图，连接 AAI 评分。 | 解决 AI 智能体自主性与通用 intelligence 评分定义问题。 | 智能体评估 |
| 22 | http://arxiv.org/abs/2511.19304v2 | AutoEnv: Automated Environments for Measuring Cross-Environment Agent Learning | 自动化环境框架，将环境视为可因子化分布生成异构世界。 | 解决跨环境学习缺乏标准集合与统一表示的问题。 | 智能体学习/评估 |
| 23 | http://arxiv.org/abs/2511.12306v2 | UpBench: A Dynamically Evolving Real-World Labor-Market Agentic Benchmark Framework Built for Human-Centric AI | 基于Upwork真实工作的动态演化基准，专家评估标准 | 现有基准静态、合成、缺乏经济意义 | 真实劳动市场任务 |
| 24 | http://arxiv.org/abs/2511.00751v1 | Reevaluating Self-Consistency Scaling in Multi-Agent Systems | 重新评估大模型多智能体系统中自一致性采样的收益与成本权衡 | 解决高采样配置下计算成本高但收益递减的问题 | 多智能体系统推理策略 |
| 25 | http://arxiv.org/abs/2511.00872v1 | A Comprehensive Empirical Evaluation of Agent Frameworks on Code-centric Software Engineering Tasks | 全面评估七种通用智能体框架在软件开发、漏洞检测等任务的表现 | 解决现有研究对智能体实践能力评估片面及缺乏对比的问题 | 代码中心型软件工程任务 |
| 26 | http://arxiv.org/abs/2511.01527v1 | TPS-Bench: Evaluating AI Agents' Tool Planning & Scheduling Abilities in Compounding Tasks | 构建复合任务基准，评估 LLM 智能体在异构工具库中的规划调度能力 | 解决现有基准缺乏对复合现实问题工具规划与调度能力评估的问题 | LLM 智能体工具使用能力 |
| 27 | http://arxiv.org/abs/2511.01625v1 | UniDataBench: Evaluating Data Analytics Agents Across Structured and Unstructured Data | 构建跨结构化与非结构化数据基准，评估数据分析智能体洞察力 | 解决现有基准局限单一数据类型及无法评估跨源链接能力的问题 | 数据 analytics 智能体 |
| 28 | http://arxiv.org/abs/2511.01833v2 | TIR-Bench: A Comprehensive Benchmark for Agentic Thinking-with-Images Reasoning | 构建 13 项任务基准，评估多模态大模型链式思考中的图像工具使用能力 | 解决现有基准无法捕捉复杂动态及工具依赖的图像推理能力问题 | 多模态大模型图像推理 |
| 29 | http://arxiv.org/abs/2511.04064v1 | Benchmarking and Studying the LLM-based Agent System in End-to-End Software Development | 构建动态基准与混合评估框架，隔离工作流设计影响 | 解决现有基准过于简单且难以公平比较代理架构的问题 | 端到端软件开发代理 |
| 30 | http://arxiv.org/abs/2511.04153v1 | BAPPA: Benchmarking Agents, Plans, and Pipelines for Automated Text-to-SQL Generation | 系统基准测试三种多智能体 LLM 管道，评估小模型性能 | 解决 Text-to-SQL 生成中复杂推理与大模型依赖的问题 | 自然语言到 SQL 生成 |
| 31 | http://arxiv.org/abs/2511.04307v2 | GUI-360$^\circ$: A Comprehensive Dataset and Benchmark for Computer-Using Agents | 大规模数据集与基准，联合评估 GUI 接地与动作预测 | 解决计算机使用代理缺乏真实任务与统一基准的问题 | 计算机使用代理研究 |
| 32 | http://arxiv.org/abs/2511.04481v1 | Promoting Sustainable Web Agents: Benchmarking and Estimating Energy Consumption through Empirical and Theoretical Analysis | 理论与实证分析 Web 代理能耗，倡导能量消耗评估指标 | 解决 Web 代理研究忽视可持续性与能源成本的问题 | Web 自动化代理 |
| 33 | http://arxiv.org/abs/2511.04502v1 | RAGalyst: Automated Human-Aligned Agentic Evaluation for Domain-Specific RAG | 自动化生成 QA 数据集，优化 LLM 裁判指标以对齐人类判断 | 解决特定领域 RAG 系统评估缺乏人类对齐与领域细微差别问题 | 领域特定 RAG 系统 |
| 34 | http://arxiv.org/abs/2511.05459v3 | SWE-Compass: Towards Unified Evaluation of Agentic Coding Abilities for Large Language Models | 统一异构代码评估为结构化框架，覆盖多语言多场景 | 解决现有基准任务覆盖窄、语言偏见且偏离真实工作流问题 | 大模型代理编码能力 |
| 35 | http://arxiv.org/abs/2511.10049v1 | Continuous Benchmark Generation for Evaluating Enterprise-scale LLM Agents | 半结构化文档驱动的动态基准生成流程 | 企业级Agent服务需求持续变化、真实样本稀缺 | 企业级AI Agent部署 |
| 36 | http://arxiv.org/abs/2511.10403v1 | nuPlan-R: A Closed-Loop Planning Benchmark for Autonomous Driving via Reactive Multi-Agent Simulation | 基于扩散的反应式多Agent仿真替代规则式IDM Agent | 规则式Agent行为单一、无法捕捉真实人类交互 | 自动驾驶规划评估 |
| 37 | http://arxiv.org/abs/2511.11252v1 | UAVBench: An Open Benchmark Dataset for Autonomous and Agentic AI UAV Systems via LLM-Generated Flight Scenarios | 5万验证无人机飞行场景+5万推理选择题基准 | 缺乏标准化、物理基础的基准限制UAV Agent系统评估 | 自主无人机系统 |
| 38 | http://arxiv.org/abs/2511.08042v1 | Towards a Standard, Enterprise-Relevant Agentic AI Benchmark: Lessons from 5.5 billion tokens' worth of agentic AI evaluations | 提出KAMI v0.1企业级Agent基准，抗数据污染 | 传统基准无法反映真实Agent部署性能 | 企业级AI Agent部署决策 |
| 39 | http://arxiv.org/abs/2511.08242v1 | Towards Outcome-Oriented, Task-Agnostic Evaluation of AI Agents | 提出11项结果导向的Agent评估指标 | 基础设施指标无法衡量Agent业务价值 | 跨行业AI Agent部署评估 |
| 40 | http://arxiv.org/abs/2511.08866v1 | BioVerge: A Comprehensive Benchmark and Study of Self-Evaluating Agents for Biomedical Hypothesis Generation | BioVerge基准与自评估Agent框架 | 缺乏标准化生物医学假设生成数据集 | 生物医学研究假设生成 |
| 41 | http://arxiv.org/abs/2511.09139v2 | MACEval: A Multi-Agent Continual Evaluation Network for Large Models | 多Agent持续评估网络动态评估大模型 | 现有基准封闭易过拟合且维护困难 | 大模型持续动态评估 |
| 42 | http://arxiv.org/abs/2511.09157v1 | ProBench: Benchmarking GUI Agents with Accurate Process Information | ProBench基准包含过程信息精确评估GUI Agent | 现有基准仅检查最终状态忽略过程信息 | 移动GUI操作任务评估 |
| 43 | http://arxiv.org/abs/2511.09586v3 | Environment Scaling for Interactive Agentic Experience Collection: A Survey | 系统调查环境缩放方法支持Agent经验收集 | 静态数据集缺乏动态性与真实性 | Agent强化学习环境构建 |
| 44 | http://arxiv.org/abs/2511.20663v5 | MTTR-A: Measuring Cognitive Recovery Latency in Multi-Agent Systems | 认知恢复延迟量化指标MTTR-A | 多Agent系统认知故障恢复速度无法量化 | 多Agent系统可靠性评估 |
| 45 | http://arxiv.org/abs/2511.07413v2 | DigiData: Training and Evaluating General-Purpose Mobile Control Agents | 大规模移动控制Agent数据集与动态评估协议 | 移动Agent高质量数据集稀缺、评估指标不足 | 移动设备控制Agent |
| 46 | http://arxiv.org/abs/2511.07685v1 | ResearchRubrics: A Benchmark of Prompts and Rubrics For Evaluating Deep Research Agents | 2500+专家编写细粒度评分标准评估深度研究Agent | 深度研究响应长且多样、评估困难 | 深度研究Agent能力评估 |
| 47 | http://arxiv.org/abs/2511.02734v1 | CostBench: Evaluating Multi-Turn Cost-Optimal Planning and Adaptation in Dynamic Environments for LLM Tool-Use Agents | 成本中心基准，评估动态环境下的经济推理与重规划。 | 现有评估忽略资源效率与适应性。 | LLM 工具使用 Agent 评估 |
| 48 | http://arxiv.org/abs/2511.03051v1 | No-Human in the Loop: Agentic Evaluation at Scale for Recommendation | 多 Agent 框架聚合审计模式，实现无标注 LLM 评估。 | 大规模评估缺乏可扩展且可信的管道。 | 推荐系统 LLM 评估 |

[返回目录](#目录)

<a id="cat-08"></a>

## Agent工具使用与环境交互

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2511.14210v2 | Orion: A Unified Visual Agent for Multimodal Perception, Advanced Visual Reasoning and Execution | 编排专用 CV 工具执行复杂多步视觉工作流 | 传统 VLM 仅生成描述，缺乏主动工具驱动智能 | 多模态感知与视觉推理执行 |
| 2 | http://arxiv.org/abs/2511.14650v1 | AutoTool: Efficient Tool Selection for Large Language Model Agents | 利用工具使用惯性构建有向图，减少 LLM 推理 | 当前 Agent 框架工具选择推理成本高 | 大语言模型 Agent 工具选择 |
| 3 | http://arxiv.org/abs/2511.15567v1 | Computer-Use Agents as Judges for Generative User Interface | Coder-CUA协作框架，Agent作为设计者和评判者 | GUI主要为人设计，Agent需采用不必要的人类行为 | 自动GUI设计与评估 |
| 4 | http://arxiv.org/abs/2511.15705v2 | GeoVista: Web-Augmented Agentic Visual Reasoning for Geolocalization | 整合图像缩放和网页搜索工具的推理循环 | 现有地理定位基准缺乏高分辨率图像和深度推理挑战 | 地理定位任务 |
| 5 | http://arxiv.org/abs/2511.16395v1 | CorrectHDL: Agentic HDL Design with LLMs Leveraging High-Level Synthesis as Reference | 利用HLS结果作为功能参考纠正LLM生成的HDL设计错误 | LLM生成HDL设计因幻觉引入功能错误 | 硬件前端设计 |
| 6 | http://arxiv.org/abs/2511.17006v1 | Budget-Aware Tool-Use Enables Effective Agent Scaling | 提出预算追踪器与 BATS 框架，实现工具调用预算感知 | 解决代理缺乏预算意识导致性能天花板的问题 | Web 搜索代理 |
| 7 | http://arxiv.org/abs/2512.10962v3 | WebSTAR: Scalable Data Synthesis for Computer Use Agents with Step-Level Filtering | 步级过滤转换 noisy rollouts 为可靠监督，无需人工标注 | 解决 CUA 训练数据稀缺及 naive imitation 无效问题 | 计算机使用代理训练 |
| 8 | http://arxiv.org/abs/2511.23281v1 | MCP vs RAG vs NLWeb vs HTML: A Comparison of the Effectiveness and Efficiency of Different Agent Interfaces to the Web | 对比四种 Agent 网页交互接口架构，评估有效性与效率差异 | 解决 LLM Agent 自动化网页任务时接口选择缺乏统一评估标准的问题 | 网页自动化任务（搜索、比价） |
| 9 | http://arxiv.org/abs/2511.22441v1 | GEO-Detective: Unveiling Location Privacy Risks in Images with LLM Agents | 模仿人类推理与工具使用，自适应选择地理定位策略 | 现有方法未优化地理定位任务，缺乏外部线索利用 | 图像地理定位与隐私风险 |
| 10 | http://arxiv.org/abs/2511.21398v1 | Prune4Web: DOM Tree Pruning Programming for Web Agent | DOM 树剪枝编程优化 Web Agent 元素定位 | 庞大 DOM 结构导致 Agent 注意力稀释 | Web 自动化任务 |
| 11 | http://arxiv.org/abs/2511.12159v1 | CriticSearch: Fine-Grained Credit Assignment for Search Agents via a Retrospective Critic | 回顾性评论机制提供细粒度回合级反馈 | 搜索Agent强化学习中稀疏奖励导致训练不稳定 | 多跳推理问答任务 |
| 12 | http://arxiv.org/abs/2511.12586v1 | MMWOZ: Building Multimodal Agent for Task-oriented Dialogue | 多模态数据集MMWOZ与MATE基线模型，桥接GUI与对话 | 传统任务对话系统缺乏GUI前端支持 | 任务导向对话系统 |
| 13 | http://arxiv.org/abs/2511.13087v1 | MEGA-GUI: Multi-stage Enhanced Grounding Agents for GUI Elements | 多阶段框架：粗ROI选择+细粒度元素定位，双向缩放算法 | GUI定位在视觉杂乱与指令模糊下失效 | GUI元素定位 |
| 14 | http://arxiv.org/abs/2511.00592v2 | Agentic Auto-Scheduling: An Experimental Study of LLM-Guided Loop Optimization | LLM 与编译器闭环交互，利用反馈迭代优化循环代码变换策略 | 解决复杂循环嵌套在現代硬件上自动优化困难的问题 | 代码性能优化与编译器 |
| 15 | http://arxiv.org/abs/2511.01854v2 | Tool-to-Agent Retrieval: Bridging Tools and Agents for Scalable LLM Multi-Agent Systems | 统一嵌入工具与父智能体，通过元数据关系实现细粒度检索 | 解决现有检索方法 coarse-grained 导致智能体选择次优及上下文稀释问题 | 大规模 LLM 多智能体系统 |
| 16 | http://arxiv.org/abs/2511.04137v1 | Learning from Online Videos at Inference Time for Computer-Use Agents | 检索过滤教程视频，动态选择轨迹作为上下文指导 | 解决计算机使用代理缺乏领域特定程序知识的问题 | 计算机任务自动化 |
| 17 | http://arxiv.org/abs/2511.11287v1 | Building the Web for Agents: A Declarative Framework for Agent-Web Interaction | VOIX框架通过声明式HTML标签暴露Agent可用动作与状态 | Agent需从人类UI推断功能，导致交互脆弱、低效、不安全 | Web Agent交互 |
| 18 | http://arxiv.org/abs/2511.08172v3 | An Efficient Training Pipeline for Reasoning Graphical User Interface Agents | 数据过滤+参数高效微调训练GUI Agent | 合成数据噪声大导致视觉定位不准 | GUI自动化与屏幕操作任务 |
| 19 | http://arxiv.org/abs/2511.09572v1 | SynthTools: A Framework for Scaling Synthetic Tools for Agent Development | 合成工具生态系统框架支持大规模Agent训练 | 真实API有限且不稳定阻碍Agent训练评估 | 工具使用Agent开发与评估 |
| 20 | http://arxiv.org/abs/2511.11672v3 | OSGym: Scalable Distributed Data Engine for Generalizable Computer Agents | 可扩展分布式OS副本环境引擎训练Computer Agent | 静态数据集缺乏动态性与真实性 | 计算机使用Agent训练 |
| 21 | http://arxiv.org/abs/2511.08819v1 | TEM Agent: enhancing transmission electron microscopy (TEM) with modern AI tools | MCP框架控制透射电镜多子系统 | 复杂显微镜生态系统访问困难 | 透射电子显微镜实验 |
| 22 | http://arxiv.org/abs/2511.06101v2 | Adapting Web Agents with Synthetic Supervision | 双精炼框架提升合成任务与轨迹质量 | Web Agent适应新网站时数据稀缺、合成数据质量差 | Web自动化与GUI Agent |
| 23 | http://arxiv.org/abs/2511.06251v1 | WebVIA: A Web-based Vision-Language Agentic Framework for Interactive and Verifiable UI-to-Code Generation | 三组件框架实现交互式UI-to-Code生成与验证 | UI开发重复劳动、现有VLM仅生成静态布局 | 用户界面开发与代码生成 |
| 24 | http://arxiv.org/abs/2511.06417v1 | AUTO-Explorer: Automated Data Collection for GUI Agent | 自主GUI环境解析与探索机制 | GUI数据获取困难、桌面软件/新网站数据稀缺 | GUI Agent训练数据收集 |
| 25 | http://arxiv.org/abs/2511.06804v1 | AgentSUMO: An Agentic Framework for Interactive Simulation Scenario Generation in SUMO via Large Language Models | 自适应推理层解释用户意图、生成可执行仿真计划 | 交通仿真专家门槛高、用户需求抽象不完整 | 城市交通仿真与政策评估 |
| 26 | http://arxiv.org/abs/2511.07332v1 | Grounding Computer Use Agents on Human Demonstrations | 大规模桌面基础化数据集GroundCUA | 桌面环境高质量基础化数据稀缺 | 计算机使用Agent与UI操作 |
| 27 | http://arxiv.org/abs/2511.07894v1 | From Natural Language to Certified H-infinity Controllers: Integrating LLM Agents with LMI-Based Synthesis | 五角色多Agent框架自然语言到认证控制器映射 | 控制合成需专家知识、形式化保证与高层意图集成 | 控制系统设计与原型开发 |
| 28 | http://arxiv.org/abs/2511.03217v1 | Hybrid Fact-Checking that Integrates Knowledge Graphs, Large Language Models, and Search-Based Retrieval Agents Improves Interpretable Claim Verification | 混合事实检查，结合 KG、LLM 与搜索 Agent。 | LLM 缺乏 grounding，KG 覆盖有限。 | 可解释声明验证 |

[返回目录](#目录)

<a id="cat-09"></a>

## Agent安全与对齐

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2511.17621v2 | From Competition to Coordination: Market Making as a Scalable Framework for Safe and Aligned Multi-Agent LLM Systems | 市场制作框架组织 Agent 交互为结构化经济交换 | 多 Agent 系统集体行为缺乏可信度与透明度 | 多 Agent LLM 系统协调与对齐 |
| 2 | http://arxiv.org/abs/2511.14876v1 | Attacking Autonomous Driving Agents with Adversarial Machine Learning: A Holistic Evaluation with the CARLA Leaderboard | 评估对抗样本对自动驾驶 Agent 系统的整体风险 | 不明对抗攻击是否有效产生有害驾驶行为 | 自动驾驶系统安全评估 |
| 3 | http://arxiv.org/abs/2511.15097v2 | MAIF: Enforcing AI Trust and Provenance with an Artifact-Centric Agentic Paradigm | 以工件为中心的 Agent 范式，嵌入加密来源 | AI 系统缺乏审计追踪与可解释性，难合规 | AI 可信度与来源追踪 |
| 4 | http://arxiv.org/abs/2511.15203v1 | Taxonomy, Evaluation and Exploitation of IPI-Centric LLM Agent Defense Frameworks | 首个 IPI 防御框架综合分析与分类 | 现有防御碎片化，缺乏统一分类与评估 | LLM Agent 间接提示注入防御 |
| 5 | http://arxiv.org/abs/2511.15292v1 | Adversarial Attack on Black-Box Multi-Agent by Adaptive Perturbation | 提出AdapAM框架，自适应选择受害Agent并生成扰动观测 | 黑盒多智能体系统对抗攻击的实用性和隐蔽性问题 | 多智能体系统安全评估 |
| 6 | http://arxiv.org/abs/2511.15759v1 | Securing AI Agents Against Prompt Injection Attacks | 多层防御框架结合内容过滤、提示词护栏和响应验证 | RAG系统提示注入攻击导致的安全漏洞 | RAG增强的AI Agent系统 |
| 7 | http://arxiv.org/abs/2511.15992v1 | Detecting Sleeper Agents in Large Language Models via Semantic Drift Analysis | 双方法检测系统结合语义漂移分析和金丝雀基线比较 | LLM后门在安全训练后持续存在且无实用检测方法 | LLM部署安全检测 |
| 8 | http://arxiv.org/abs/2511.15998v2 | Hiding in the AI Traffic: Abusing MCP for LLM-Powered Agentic Red Teaming | 利用MCP协调分布式自适应侦察Agent的C2架构 | 现有红队方法在通用性和专业化之间存在权衡 | AI驱动的红队操作 |
| 9 | http://arxiv.org/abs/2511.16708v3 | Multi-Agent Code Verification via Information Theory | 四专用Agent检测不同类型bug，用信息论证明组合优势 | LLM生成代码存在大量bug且现有工具检出率低 | 代码验证和漏洞检测 |
| 10 | http://arxiv.org/abs/2511.16709v1 | AutoBackdoor: Automating Backdoor Attacks via LLM Agents | 自主Agent驱动流水线自动化触发器生成和投毒数据构建 | 现有后门攻击方法依赖手工触发器和静态数据管道 | LLM后门攻击评估 |
| 11 | http://arxiv.org/abs/2511.17671v1 | MURMUR: Using cross-user chatter to break collaborative language agents in groups | 发现跨用户投毒攻击向量并通过任务聚类提出防御 | 多用户协作语言Agent缺乏隔离用户交互和并发任务机制 | 多用户LLM部署安全 |
| 12 | http://arxiv.org/abs/2511.17085v2 | Why Do Language Model Agents Whistleblow? | 构建多样化 staged misconduct 场景评估代理告密行为 | 解决代理部署中未授权披露 misconduct 的风险 | 语言模型代理对齐 |
| 13 | http://arxiv.org/abs/2511.17730v1 | Safety and Risk Pathways in Cooperative Generative Multi-Agent Systems: A Telecom Perspective | 模块化安全评估框架，集成代理级代码质量与系统级指标 | 解决电信 GMAS 中 miscoordination 及 semantic drift 风险 | 电信生成式多 Agent 系统 |
| 14 | http://arxiv.org/abs/2511.17959v1 | Towards Automating Data Access Permissions in AI Agents | 基于用户研究编码因素，ML 模型预测用户权限决策 | 解决传统权限模型不适应自动化代理执行范式问题 | AI 代理数据访问权限 |
| 15 | http://arxiv.org/abs/2511.18114v1 | ASTRA: Agentic Steerability and Risk Assessment Framework | 模拟 10 种代理及 37 种工具，评估 LLM 执行自定义 guardrails 能力 | 解决 compromised 代理滥用工具执行恶意动作风险 | AI 代理安全与 steerability |
| 16 | http://arxiv.org/abs/2512.00332v2 | Assertion-Conditioned Compliance: A Provenance-Aware Vulnerability in Multi-Turn Tool-Calling Agents | 提出 A-CC 评估范式，衡量模型对用户误导断言及系统策略冲突的合规性 | 解决多轮工具调用 Agent 在面对误导断言时缺乏鲁棒性及可见性的问题 | 多轮工具调用 Agent 安全 |
| 17 | http://arxiv.org/abs/2512.03089v1 | Password-Activated Shutdown Protocols for Misaligned Frontier Agents | 引入密码激活关闭协议，设计前沿 Agent 在给定密码时实施安全关闭 | 解决未对齐前沿 Agent 规避控制努力执行有害动作的风险问题 | 前沿 AI 系统安全 |
| 18 | http://arxiv.org/abs/2512.00513v2 | Truthful and Trustworthy IoT AI Agents via Immediate-Penalty Enforcement under Approximate VCG Mechanisms | 结合近似 VCG 双拍卖与即时一次性惩罚，单轮内恢复真实报告 | 解决 IoT 能源交易中感知噪声及部分可观察性导致战略操纵的问题 | IoT 能源交易 |
| 19 | http://arxiv.org/abs/2512.00520v1 | Toward a Safe Internet of Agents | 自底向上解构代理系统，识别单 Agent 到互操作多 Agent 系统的架构漏洞 | 解决 Agent 安全作为附加组件而非架构原则，缺乏系统设计基础的问题 | 互联网 of Agents 安全 |
| 20 | http://arxiv.org/abs/2512.00742v1 | On the Regulatory Potential of User Interfaces for AI Agent Governance | 分析 22 个现有系统 UI 元素，合成六个具有监管潜力的高层交互设计模式 | 解决现有治理主要 targeting 系统级 safeguards，缺乏 UI 监管表面的问题 | AI Agent 治理 |
| 21 | http://arxiv.org/abs/2511.21460v1 | MADRA: Multi-Agent Debate for Risk-Aware Embodied Planning | 多智能体辩论风险评估框架，无需训练提升安全性 | 现有方法计算成本高或过度拒绝安全任务 | 具身智能家庭环境 |
| 22 | http://arxiv.org/abs/2511.21990v1 | A Safety and Security Framework for Real-World Agentic Systems | 动态智能体安全框架，统一传统安全与新型智能体风险 | 安全与security在智能体系统中界限模糊，风险 emergent | 企业级智能体部署 |
| 23 | http://arxiv.org/abs/2512.17913v1 | Byzantine Fault-Tolerant Multi-Agent System for Healthcare: A Gossip Protocol Approach to Secure Medical Message Propagation | 拜占庭容错多智能体系统，集成 gossip 协议与加密验证 | 分布式医疗系统在 adversarial 环境下消息完整性难保 | 医疗协作决策系统 |
| 24 | http://arxiv.org/abs/2511.22572v1 | Formal Verification of Probabilistic Multi-Agent Systems for Ballistic Rocket Flight Using Probabilistic Alternating-Time Temporal Logic | 基于 PATL 的形式化验证框架，分析弹道火箭安全属性 | 环境随机性导致轨迹偏差，需实时安全监控 | 弹道火箭飞行安全 |
| 25 | http://arxiv.org/abs/2511.23174v1 | Are LLMs Good Safety Agents or a Propaganda Engine? | 构建 PSP 数据集，探测 LLM 拒绝行为中的政治审查 | 难以区分安全策略拒绝与政治动机审查 | LLM 安全与审查分析 |
| 26 | http://arxiv.org/abs/2511.19874v1 | Cross-LLM Generalization of Behavioral Backdoor Detection in AI Agent Supply Chains | 跨 LLM 行为后门检测与模型感知防御 | AI Agent 供应链后门攻击风险 | AI 系统供应链安全 |
| 27 | http://arxiv.org/abs/2511.19961v1 | Toward Trustworthy Digital Twins in Agentic AI-based Wireless Network Optimization: Challenges, Solutions, and Opportunities | 可信数字孪生评估框架确保 Agent 策略可靠 | 低保真数字孪生导致部署性能下降 | 无线网络优化 |
| 28 | http://arxiv.org/abs/2511.20597v1 | BrowseSafe: Understanding and Preventing Prompt Injection Within AI Browser Agents | 多层防御策略防止 AI 浏览器 Agent 提示注入 | 浏览器 Agent 面临提示注入安全威胁 | Web 浏览器 Agent |
| 29 | http://arxiv.org/abs/2512.07850v1 | SABER: Small Actions, Big Errors -- Safeguarding Mutating Steps in LLM Agents | 突变步骤门控验证与 targeted reflection  safeguard | 长程任务中关键动作错误导致失败 | LLM Agent 可靠性 |
| 30 | http://arxiv.org/abs/2511.18467v1 | Shadows in the Code: Exploring the Risks and Defenses of LLM-based Multi-Agent Software Development Systems | 识别多智能体软件开发系统中的两种风险场景及攻击方式。 | 解决多智能体编码系统未被探索的安全风险。 | 软件开发系统 |
| 31 | http://arxiv.org/abs/2511.19536v1 | AttackPilot: Autonomous Inference Attacks Against ML Services With LLM-Based Agents | 自主智能体独立执行推理攻击，无需人工干预。 | 解决非专家难以实施和评估机器学习服务推理攻击的问题。 | 机器学习安全 |
| 32 | http://arxiv.org/abs/2511.20703v1 | PropensityBench: Evaluating Latent Safety Risks in Large Language Models via an Agentic Approach | 新基准框架评估模型在具备危险能力时的潜在 misuse 倾向。 | 解决当前安全评估忽视模型潜在 misuse 倾向的问题。 | 大模型安全 |
| 33 | http://arxiv.org/abs/2511.11921v1 | Looking Forward: Challenges and Opportunities in Agentic AI Reliability | 系统分析级联失败风险与可靠性机制挑战 | Agentic AI系统可靠性与风险评估 | 通用Agent系统 |
| 34 | http://arxiv.org/abs/2511.12164v1 | Multi-Agent Collaborative Fuzzing with Continuous Reflection for Smart Contracts Vulnerability Detection | 连续反思过程与多Agent协作生成交易序列 | 智能合约复杂漏洞检测效率低、误报高 | 智能合约与DApp项目 |
| 35 | http://arxiv.org/abs/2511.12271v1 | MoralReason: Generalizable Moral Decision Alignment For LLM Agents Using Reasoning-Level Reinforcement Learning | 组相对策略优化同时优化决策对齐与推理过程 | LLM Agent道德决策泛化与框架一致性 | 道德决策场景 |
| 36 | http://arxiv.org/abs/2511.12294v2 | ProofWright: Towards Agentic Formal Verification of CUDA | 整合自动形式验证与LLM代码生成，提供端到端保证 | LLM生成CUDA内核缺乏形式安全保证 | GPU代码生成验证 |
| 37 | http://arxiv.org/abs/2511.13248v1 | DualTAP: A Dual-Task Adversarial Protector for Mobile MLLM Agents | 双任务对抗目标：最小化任务保留损失+隐私干扰损失 | 移动MLLM Agent截图含PII隐私泄露风险 | 移动GUI Agent隐私保护 |
| 38 | http://arxiv.org/abs/2511.01668v2 | Hybrid Retrieval-Augmented Generation Agent for Trustworthy Legal Question Answering in Judicial Forensics | 混合 RAG 与多模型集成，优先检索结合人工审核实现动态知识演化 | 解决法律 QA 中 LLM 幻觉及静态知识库更新滞后导致的不合规问题 | 司法取证与法律咨询 |
| 39 | http://arxiv.org/abs/2511.07441v5 | AudAgent: Automated Auditing of Privacy Policy Compliance in AI Agents | 四组件自动化隐私审计，实时监测数据实践并阻断违规操作 | 解决 AI 智能体运行时行为与隐私政策不符及缺乏透明度的问题 | AI 智能体隐私合规审计 |
| 40 | http://arxiv.org/abs/2511.03841v1 | Security Analysis of Agentic AI Communication Protocols: A Comparative Evaluation | 实证比较智能体通信协议安全性，提出混合架构建议 | 解决多智能体系统通信协议安全性未被充分审查的问题 | 多智能体通信基础设施 |
| 41 | http://arxiv.org/abs/2511.04032v1 | Detecting Silent Failures in Multi-Agentic AI Trajectories | 构建异常检测数据集与基准，识别智能体轨迹中的静默失败 | 解决多智能体系统非确定性导致的漂移和循环难检测问题 | 多智能体系统监控 |
| 42 | http://arxiv.org/abs/2511.11619v1 | DIAP: A Decentralized Agent Identity Protocol with Zero-Knowledge Proofs and a Hybrid P2P Stack | 绑定身份到不可变内容标识符，零知识证明所有权 | 解决去中心化环境中缺乏可验证且隐私保护的通信协议问题 | 去中心化智能体生态 |
| 43 | http://arxiv.org/abs/2511.14780v1 | Ask WhAI:Probing Belief Formation in Role-Primed LLM Agents | 系统级框架检查扰动信念状态，测试信念结构对新信息反应 | 解决多智能体科学推理中信念形成与认知孤岛不可见问题 | 多智能体医疗模拟 |
| 44 | http://arxiv.org/abs/2511.04949v1 | DeepForgeSeal: Latent Space-Driven Semi-Fragile Watermarking for Deepfake Detection Using Multi-Agent Adversarial Reinforcement Learning | 多智能体对抗 RL 范式，潜在空间驱动半脆弱水印 | 解决深度伪造检测泛化性差与水印鲁棒性平衡难的问题 | 深度伪造检测与安全 |
| 45 | http://arxiv.org/abs/2511.05269v1 | TAMAS: Benchmarking Adversarial Risks in Multi-Agent LLM Systems | 基准测试多智能体 LLM 系统鲁棒性，引入有效鲁棒性评分 | 解决多智能体动态与协调带来的独特漏洞未被探索问题 | 多智能体 LLM 系统安全 |
| 46 | http://arxiv.org/abs/2511.05359v1 | ConVerse: Benchmarking Contextual Safety in Agent-to-Agent Conversations | 动态基准评估代理间交互隐私与安全风险，统一安全属性 | 解决多智能体生态中效用与保护之间核心张力问题 | 代理间通信安全 |
| 47 | http://arxiv.org/abs/2511.05804v1 | Catching Contamination Before Generation: Spectral Kill Switches for Agents | 无需训练的诊断，前向_pass_发射二元信号检测上下文污染 | 解决代理执行中中间步骤错误传播且事后评估太晚问题 | 代理推理过程安全 |
| 48 | http://arxiv.org/abs/2511.10400v2 | Rethinking the Reliability of Multi-agent System: A Perspective from Byzantine Fault Tolerance | 基于置信度探测的加权拜占庭容错共识机制(CP-WBFT) | LLM-based Agent在多Agent系统中的可靠性未探索 | 多Agent系统可靠性 |
| 49 | http://arxiv.org/abs/2511.10949v1 | Exposing Weak Links in Multi-Agent Systems under Adversarial Prompting | SafeAgents框架与Dharma诊断度量识别多Agent管道弱点 | 多Agent系统设计引入的安全漏洞未被充分研究 | 多Agent系统安全评估 |
| 50 | http://arxiv.org/abs/2511.11169v1 | Refine and Align: Confidence Calibration through Multi-Agent Interaction in VQA | AlignVQA辩论框架与aligncal校准感知损失函数 | VQA系统置信度估计不可靠，常过度自信 | 视觉问答系统 |
| 51 | http://arxiv.org/abs/2511.11182v1 | Multi-agent Undercover Gaming: Hallucination Removal via Counterfactual Test for Multimodal Reasoning | MUG协议用反事实测试检测"卧底"幻觉Agent | 多Agent辩论假设所有Agent理性，但Agent本身易幻觉 | 多模态推理 |
| 52 | http://arxiv.org/abs/2511.11789v1 | From Single to Societal: Analyzing Persona-Induced Bias in Multi-Agent Interactions | 系统研究多Agent交互中角色诱导的信任度与坚持性偏见 | 角色分配是否引入偏见未被充分探索，影响公平性 | 多Agent社会模拟 |
| 53 | http://arxiv.org/abs/2511.11551v3 | Aligning Machiavellian Agents: Behavior Steering via Test-Time Policy Shaping | 测试时策略塑造技术控制行为属性，无需重新训练 | 预训练Agent对齐困难，重训练成本高且慢 | RL Agent伦理对齐 |
| 54 | http://arxiv.org/abs/2511.08487v1 | How Brittle is Agent Safety? Rethinking Agent Risk under Intent Concealment and Task Complexity | OASIS基准分析意图隐藏与任务复杂度下安全性 | 现有安全评估忽视复杂任务中隐藏恶意意图 | LLM驱动Agent安全评估 |
| 55 | http://arxiv.org/abs/2511.08721v1 | Benevolent Dictators? On LLM Agent Behavior in Dictator Games | LLM-ABS框架研究系统提示对Agent公平行为影响 | 忽视系统提示对Agent行为敏感性的影响 | LLM Agent行为与偏好研究 |
| 56 | http://arxiv.org/abs/2511.08842v1 | 3D Guard-Layer: An Integrated Agentic AI Safety System for Edge Artificial Intelligence | 3D集成自适应AI安全层动态缓解攻击 | 边缘AI系统安全漏洞阻碍实际部署 | 边缘人工智能安全系统 |
| 57 | http://arxiv.org/abs/2511.11693v1 | Value-Aligned Prompt Moderation via Zero-Shot Agentic Rewriting for Safe Image Generation | VALOR框架零样本Agent重写实现安全图像生成 | 现有防御难以对齐人类价值且成本高 | 文本到图像生成安全 |
| 58 | http://arxiv.org/abs/2511.09178v1 | Perspectives on a Reliability Monitoring Framework for Agentic AI Systems | 双层可靠性监控框架支持人类干预决策 | Agent系统可靠性不足不适合高风险领域 | 医疗/流程工业高风险应用 |
| 59 | http://arxiv.org/abs/2511.15712v1 | Secure Autonomous Agent Payments: Verifying Authenticity and Intent in a Trustless Environment | 区块链框架验证Agent身份与交易意图 | 自主Agent支付缺乏身份认证与意图验证 | 金融支付与自主经济Agent |
| 60 | http://arxiv.org/abs/2511.06396v3 | Efficient LLM Safety Evaluation through Multi-Agent Debate | 结构化多Agent辩论提升安全评估可靠性 | LLM安全评估成本高、小模型判断可靠性不足 | LLM安全评估与越狱检测 |
| 61 | http://arxiv.org/abs/2511.06448v1 | When AI Agents Collude Online: Financial Fraud Risks by Collaborative LLM Agents on Social Platforms | 大规模多Agent金融欺诈风险基准与缓解策略 | 多Agent协作欺诈风险、适应性攻击 | 社交平台金融安全 |
| 62 | http://arxiv.org/abs/2511.07176v2 | Graph Representation-based Model Poisoning on the Heterogeneous Internet of Agents | 图表示模型投毒攻击，利用特征相关图生成恶意更新 | 联邦微调IoA系统易受模型投毒攻击 | 智能体互联网安全 |
| 63 | http://arxiv.org/abs/2511.07267v2 | Beyond Detection: Exploring Evidence-based Multi-Agent Debate for Misinformation Intervention and Persuasion | 证据基础多Agent辩论框架用于虚假信息干预 | 虚假信息检测忽略用户理解与信念纠正 | 虚假信息干预与事实核查 |
| 64 | http://arxiv.org/abs/2511.07315v1 | JPRO: Automated Multimodal Jailbreaking via Multi-Agent Collaboration Framework | 四Agent协作框架自动化VLM越狱攻击 | 现有越狱方法多样性差、可扩展性不足 | 多模态大模型安全评估 |
| 65 | http://arxiv.org/abs/2511.02885v1 | AgentSLA : Towards a Service Level Agreement for AI Agents | 基于 ISO 标准的质量模型与 DSL，定义 Agent SLA。 | AI Agent 服务质量 (QoS) 与 SLA 定义缺失。 | 智能软件系统开发与部署 |
| 66 | http://arxiv.org/abs/2511.02780v3 | PoCo: Agentic Proof-of-Concept Exploit Generation for Smart Contracts | 自动生成功能性 PoC 漏洞利用代码，辅助安全审计。 | 手动创建 PoC 耗时且易错。 | 智能合约安全审计 |
| 67 | http://arxiv.org/abs/2511.02823v1 | Optimizing AI Agent Attacks With Synthetic Data | 分解攻击技能并使用合成数据优化攻击策略。 | 复杂 Agent 环境中攻击评估数据匮乏。 | AI 控制与风险评估 |
| 68 | http://arxiv.org/abs/2511.02997v1 | Evaluating Control Protocols for Untrusted AI Agents | 系统评估控制协议 against 自适应攻击者。 | 需确保不可信 Agent 的安全操作。 | 不可信 AI  Agent 控制协议 |
| 69 | http://arxiv.org/abs/2511.03138v4 | DeepKnown-Guard: A Proprietary Model-Based Safety Response Framework for AI Agents | 输入输出双层安全框架，结合 RAG 确保响应可信。 | LLM 安全问题制约关键领域可信部署。 | 高安全 LLM 应用 |
| 70 | http://arxiv.org/abs/2511.03434v1 | Inter-Agent Trust Models: A Comparative Study of Brief, Claim, Proof, Stake, Reputation and Constraint in Agentic Web Protocol Design-A2A, AP2, ERC-8004, and Beyond | 比较 Agent 间信任模型，建议混合信任架构。 | Agent 网络中信任假设未受审视，LLM 脆弱。 | 代理 Web 协议设计 |

[返回目录](#目录)

<a id="cat-10"></a>

## 人机协作Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2511.15253v2 | PresentCoach: Dual-Agent Presentation Coaching through Exemplars and Interactive Feedback | 双 Agent 系统，理想演示与教练角色互补 | 学习者缺乏高质量范例与个性化 coaching | 演讲技能教育与培训 |
| 2 | http://arxiv.org/abs/2511.17315v1 | Humanlike Multi-user Agent (HUMA): Designing a Deceptively Human AI Facilitator for Group Chats | 事件驱动架构处理消息/反应，模拟人类响应 timing | 解决 AI 在异步群聊中交互模式不自然的问题 | 群聊 AI 协调员 |
| 3 | http://arxiv.org/abs/2511.17906v1 | AnimAgents: Coordinating Multi-Stage Animation Pre-Production with Human-Multi-Agent Collaboration | 核心代理协调专用代理，支持四阶段预生产工作流 | 解决生成式 AI 工具孤立及创作者手动协调碎片输出问题 | 动画预生产工作流 |
| 4 | http://arxiv.org/abs/2511.18352v1 | MagicWand: A Universal Agent for Generation and Evaluation Aligned with User Preference | 基于用户偏好数据集，增强 prompt 并应用 preference-aligned 评估 | 解决用户难 craft 详细 prompt 及缺乏偏好保留机制问题 | AIGC 内容生成与评估 |
| 5 | http://arxiv.org/abs/2511.18405v1 | A Multimodal Conversational Agent for Tabular Data Analysis | 多模态对话代理，支持语音/文本查询及多模态响应 | 解决文本分析工具缺乏多模态交互及上下文 grounded 问题 | 表格数据探索与分析 |
| 6 | http://arxiv.org/abs/2512.00797v1 | Transforming Monolithic Foundation Models into Embodied Multi-Agent Architectures for Human-Robot Collaboration | InteractGen 框架分解机器人智能为专用代理，支持动态人类委托及失败反思 | 解决单一基础模型假设与分布式动态实际服务工作流不匹配的问题 | 人机机器人协作 |
| 7 | http://arxiv.org/abs/2511.22269v1 | Investigating AI in Peer Support via Multi-Module System-Driven Embodied Conversational Agents | 多模块系统驱动具身对话智能体，基于 CBT 提供同伴支持 | 现有系统输入 rigid，缺乏情感敏感性与灵活性 | 青少年心理健康同伴支持 |
| 8 | http://arxiv.org/abs/2511.22737v1 | Agentic AI Framework for Individuals with Disabilities and Neurodivergence: A Multi-Agent System for Healthy Eating, Daily Routines, and Inclusive Well-Being | 多层结构混合推理引擎，同步四个专用智能体 | 传统辅助系统缺乏包容性与个性化，数据安全性难保 | 残障与神经多样性人群健康 |
| 9 | http://arxiv.org/abs/2511.20080v1 | Adaptive LLM Agents: Toward Personalized Empathetic Care | 基于心理状态量化的自适应共情护理 Agent | 心理健康对话系统缺乏个性化 | 心理健康支持 |
| 10 | http://arxiv.org/abs/2511.12359v1 | More Than Irrational: Modeling Belief-Biased Agents | 计算理性模型显式建模认知边界与偏置信念状态 | 预测用户次优行为以开发自适应AI助手 | 人机协作导航任务 |
| 11 | http://arxiv.org/abs/2511.12645v2 | BeautyGuard: Designing a Multi-Agent Roundtable System for Proactive Beauty Tech Compliance through Stakeholder Collaboration | 多Agent圆桌系统分配法律/检查/先例/风险角色 | 美容科技企业合规审查手动、碎片化、被动 | 美容科技合规审查 |
| 12 | http://arxiv.org/abs/2511.00945v1 | "Less is More": Reducing Cognitive Load and Task Drift in Real-Time Multimodal Assistive Agents for the Visually Impaired | 共优化认知脑与交互体，提供简洁 actionable 指导及实时通信 embodiment | 解决视障辅助应用高认知负荷、高延迟及任务漂移的问题 | 视障人士实时视觉辅助 |
| 13 | http://arxiv.org/abs/2511.01205v1 | When Machines Join the Moral Circle: The Persona Effect of Generative AI Agents in Collaborative Reasoning | 实验研究 AI 队友人格对道德 discourse 的影响，促进反思性推理 | 解决生成式 AI 在协作学习中伦理 deliberation 效果不明确的问题 | 大学生协作学习与道德推理 |
| 14 | http://arxiv.org/abs/2511.05203v2 | SIL: Symbiotic Interactive Learning for Language-Conditioned Human-Agent Co-Adaptation | 双向共适应框架，共享潜在任务空间与联合信念状态 | 解决人机交互中代理被动执行缺乏互惠学习的问题 | 人机协作与机器人交互 |
| 15 | http://arxiv.org/abs/2511.05706v2 | AdvisingWise: Supporting Academic Advising in Higher Education Settings Through a Human-in-the-Loop Multi-Agent Framework | 多智能体系统自动化耗时任务，保留人类监督验证响应 | 解决高校学术咨询师生比高导致无法提供及时支持问题 | 高等教育学术咨询 |
| 16 | http://arxiv.org/abs/2511.10810v1 | HARNESS: Human-Agent Risk Navigation and Event Safety System for Proactive Hazard Forecasting in High-Risk DOE Environments | LLM整合结构化工作数据与历史事件检索，人机协同优化 | 高危环境运营安全风险预测与实时诊断 | 能源部高危工作环境 |
| 17 | http://arxiv.org/abs/2511.11772v2 | Scaling Equitable Reflection Assessment in Education via Large Language Models and Role-Based Feedback Agents | 五角色Agent协作评分与生成公平、无偏见的学习反馈 | 大规模课程中教师无法为每个学生提供形成性反馈 | 教育/成人学习 |
| 18 | http://arxiv.org/abs/2511.08835v1 | Beyond Task-Oriented and Chitchat Dialogues: Proactive and Transition-Aware Conversational Agents | TACT数据集支持任务与闲聊模式转换 | 传统对话Agent难以处理模式自然转换 | 主动式对话系统 |
| 19 | http://arxiv.org/abs/2511.06954v1 | Personalizing Emotion-aware Conversational Agents? Exploring User Traits-driven Conversational Strategies for Enhanced Interaction | 用户特质驱动的情感感知对话策略 | 对话Agent情感导航能力不足、缺乏个性化 | 情感感知对话系统 |
| 20 | http://arxiv.org/abs/2511.07392v3 | Voice-Interactive Surgical Agent for Multimodal Patient Data Control | 分层多Agent框架解释语音命令控制患者数据 | 机器人手术中访问多模态数据中断工作流 | 机器人手术与临床数据控制 |
| 21 | http://arxiv.org/abs/2511.07401v1 | People Perceive More Phantom Costs From Autonomous Agents When They Make Unreasonably Generous Offers | 用户感知自主Agent" phantom costs"的实证研究 | 用户对Agent慷慨报价的隐藏成本感知机制 | 人机交互与Agent信任设计 |
| 22 | http://arxiv.org/abs/2511.03143v1 | From Measurement to Expertise: Empathetic Expert Adapters for Context-Based Empathy in Conversational AI Agents | 训练共情专家适配器，缩小感知与期望共情差距。 | 模型共情通用而非针对特定任务上下文。 | 对话式 AI 用户体验 |

[返回目录](#目录)

<a id="cat-11"></a>

## Agent规划与推理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2511.15408v1 | NAMeGEn: Creative Name Generation via A Novel Agent-based Multiple Personalized Goal Enhancement Framework | 多Agent优化框架迭代交替目标提取、生成和评估 | 创意文本生成中多目标灵活性和解释复杂性的挑战 | 中文婴儿命名任务 |
| 2 | http://arxiv.org/abs/2511.15578v1 | AVATAAR: Agentic Video Answering via Temporal Adaptive Alignment and Reasoning | 模块化框架结合全局和局部视频上下文及反馈循环 | 长视频理解需要全面理解和详细分析的细微查询 | 长形式视频问答 |
| 3 | http://arxiv.org/abs/2511.17672v1 | Cognitive Inception: Agentic Reasoning against Visual Deceptions by Injecting Skepticism | 通过注入怀疑的完全基于推理的Agent框架验证视觉输入真实性 | 多模态LLM难以识别生成视觉输入与真实输入的区别 | AIGC视觉欺骗检测 |
| 4 | http://arxiv.org/abs/2511.16972v1 | ToC: Tree-of-Claims Search with Multi-Agent Language Models | 将MCTS与协作多Agent系统整合优化专利权利要求 | 手动权利要求起草劳动密集成本高且不一致 | 专利权利要求优化 |
| 5 | http://arxiv.org/abs/2511.18177v1 | Rethinking Retrieval: From Traditional Retrieval Augmented Generation to Agentic and Non-Vector Reasoning Systems in the Financial Domain for Large Language Models | 系统评估向量 vs 非向量 RAG，应用 cross-encoder reranking | 解决金融文档检索准确性及成本性能权衡不明确问题 | 金融领域 LLM 问答 |
| 6 | http://arxiv.org/abs/2511.18313v1 | Path-Constrained Retrieval: A Structural Approach to Reliable LLM Agent Reasoning Through Graph-Scoped Semantic Search | 结合结构图约束与语义搜索，限制搜索空间至可达节点 | 解决检索上下文缺乏结构一致性导致推理 incoherent 问题 | LLM 代理推理系统 |
| 7 | http://arxiv.org/abs/2511.21886v1 | Bridging Planning and Execution: Multi-Agent Path Finding Under Real-World Deadlines | 执行感知 MAPF 框架，集成 ExecTimeNet 估计执行时间 | 规划与执行存在差距，忽略动力学与延迟因素 | 自动化仓库与物流系统 |
| 8 | http://arxiv.org/abs/2511.22659v1 | Geometrically-Constrained Agent for Spatial Reasoning | 训练免费范式，将 VLM 角色解耦为语义分析与任务求解 | 语义到几何存在 gap，工具集成方法规划无约束 | 视觉语言模型空间推理 |
| 9 | http://arxiv.org/abs/2511.22854v2 | CRAwDAD: Causal Reasoning Augmentation with Dual-Agent Debate | 双智能体辩论框架，显化因果推理内部对话 | 因果推理需考虑多干预场景，单模型计算易错 | 因果推断任务 |
| 10 | http://arxiv.org/abs/2511.20085v3 | VICoT-Agent: A Vision-Interleaved Chain-of-Thought Framework for Interpretable Multimodal Reasoning and Scalable Remote Sensing Analysis | 视觉交错思维链框架实现可解释多模态推理 | 遥感图像分析推理能力与工具调用灵活性不足 | 遥感图像分析 |
| 11 | http://arxiv.org/abs/2511.21064v1 | OVOD-Agent: A Markov-Bandit Framework for Proactive Visual Reasoning and Self-Evolving Detection | Markov-Bandit 框架实现主动视觉推理与检测 | 开放词汇检测文本空间探索不足 | 视觉目标检测 |
| 12 | http://arxiv.org/abs/2511.21087v2 | MIRA: Multimodal Iterative Reasoning Agent for Image Editing | 多模态迭代推理 Agent 实现指令引导图像编辑 | 扩散模型复杂指令理解与语义漂移 | 图像编辑任务 |
| 13 | http://arxiv.org/abs/2511.19516v2 | Connecting the Dots: Training-Free Visual Grounding via Agentic Reasoning | 无需微调的智能体视觉定位框架，通过迭代推理优化区域。 | 解决视觉定位依赖大量标注且泛化能力弱的问题。 | 视觉定位/多模态 |
| 14 | http://arxiv.org/abs/2511.04898v1 | Real-Time Reasoning Agents in Evolving Environments | 同时参与反应与规划范式，平衡推理深度与响应延迟 | 解决现有代理在动态环境中无法做出逻辑且及时判断问题 | 实时动态环境代理 |
| 15 | http://arxiv.org/abs/2511.08947v2 | CastMind: An Interaction-Driven Agentic Reasoning Framework for Cognition-Inspired Time Series Forecasting | 多阶段工作流将预测转为专家推理过程 | 传统方法将预测视为静态单步回归问题 | 时间序列预测决策 |
| 16 | http://arxiv.org/abs/2511.09005v1 | AI Founding Fathers: A Case Study of GIS Search in Multi-Agent Pipelines | 递归细化实现渐进增量搜索增强推理 | LLM推理能力需结构化多Agent Pipeline | 政治议题分析与论证生成 |
| 17 | http://arxiv.org/abs/2511.08798v1 | Structured Uncertainty guided Clarification for LLM Agents | 结构化不确定性建模优化澄清问题选择 | 模糊指令导致工具调用错误与任务失败 | 多轮工具增强Agent交互 |
| 18 | http://arxiv.org/abs/2511.07327v2 | IterResearch: Rethinking Long-Horizon Agents with Interaction Scaling | 迭代深度研究范式，交互扩展与战略工作区重构 | 长周期任务上下文窒息、噪声污染 | 深度研究与知识构建 |
| 19 | http://arxiv.org/abs/2511.07568v1 | Procedural Knowledge Improves Agentic LLM Workflows | 分层任务网络形式化程序知识提升Agent规划 | LLM执行Agent任务无工具支持时表现差 | 通用Agent任务规划 |
| 20 | http://arxiv.org/abs/2511.02238v1 | Deep Ideation: Designing LLM Agents to Generate Novel Research Ideas on Scientific Concept Network | 整合科学概念网络，迭代 refine 研究想法。 | 现有方法忽略概念间复杂上下文关系。 | 科学研究创意生成 |
| 21 | http://arxiv.org/abs/2511.02424v2 | ReAcTree: Hierarchical LLM Agent Trees with Control Flow for Long-Horizon Task Planning | 分层 Agent 树分解复杂目标，控制流节点协调执行。 | 单体轨迹难以处理复杂长程任务。 | 具身自主 Agent 长程任务规划 |
| 22 | http://arxiv.org/abs/2511.03094v1 | ALAS: Transactional and Dynamic Multi-Agent LLM Planning | 状态感知框架，分离规划与非循环验证，局部修复。 | 多 Agent 规划脆弱，小故障触发全局重算。 | 多 Agent LLM 任务规划 |

[返回目录](#目录)

<a id="cat-12"></a>

## Agent仿真与社会模拟

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2511.15573v1 | Two-Faced Social Agents: Context Collapse in Role-Conditioned Large Language Models | 评估LLM在不同社会经济角色下的身份保真度 | LLM在认知负载下出现情境崩溃和身份收敛 | 社会模拟和调查数据完整性 |
| 2 | http://arxiv.org/abs/2511.16243v1 | An Agent-Based Simulation of Regularity-Driven Student Attrition: How Institutional Time-to-Live Constraints Create a Dropout Trap in Higher Education | 校准ABM模拟1343名学生轨迹整合13种心理学术原型 | 高辍学率归因于学生缺陷忽视行政规则的因果作用 | 高等教育学生流失分析 |
| 3 | http://arxiv.org/abs/2511.17496v1 | MDG: Masked Denoising Generation for Multi-Agent Behavior Modeling in Traffic Environments | 统一生成框架，重构为独立噪声时空张量重建 | 解决扩散/自回归方法在效率及多任务复用上的限制 | 交通多 Agent 行为建模 |
| 4 | http://arxiv.org/abs/2511.17762v2 | The Software Engineering Simulations Lab: Agentic AI for RE Quality Simulations | 扩展 RE 研究工具箱，用标准化代理复制 SE 过程 | 解决需求质量缺陷下游影响实证数据稀缺问题 | 需求工程质量模拟 |
| 5 | http://arxiv.org/abs/2511.18248v2 | Coherent Multi-Agent Trajectory Forecasting in Team Sports with CausalTraj | 时间因果 likelihood 模型，生成 jointly probable 轨迹 | 解决现有模型忽略联合预测及多 Agent 场景 coherence 问题 | 团队运动轨迹预测 |
| 6 | http://arxiv.org/abs/2512.00249v1 | A Hierarchical Hybrid AI Approach: Integrating Deep Reinforcement Learning and Scripted Agents in Combat Simulations | 分层混合 AI 结合脚本代理可靠性与 RL 适应性，脚本处理战术 RL 处理战略 | 解决脚本代理缺乏灵活性及 RL 代理黑盒决策和扩展性差的问题 | 战斗仿真与兵棋推演 |
| 7 | http://arxiv.org/abs/2601.15290v1 | Agentic Persona Control and Task State Tracking for Realistic User Simulation in Interactive Scenarios | 三代理框架模拟用户交互，控制 persona 及任务状态跟踪镜像人类认知 | 解决测试对话 AI 系统缺乏真实多样用户交互捕捉广泛行为模式的问题 | 交互式场景用户模拟 |
| 8 | http://arxiv.org/abs/2512.01078v2 | SimWorld: An Open-ended Realistic Simulator for Autonomous Agents in Physical and Social Worlds | 基于 Unreal Engine 5 构建模拟器，支持物理社会动态及语言驱动环境生成 | 解决现有世界模拟器依赖手工环境、物理社会规则简化及缺乏 LLM 支持问题 | 物理与社会世界 Agent 仿真 |
| 9 | http://arxiv.org/abs/2511.22037v2 | What AI Speaks for Your Community: Polling AI Agents for Public Opinion on Data Center Projects | 利用 LLM 智能体 polling 框架评估社区对数据中心意见 | 传统 polling 成本高且滞后，难以影响早期规划 | 数据中心社区规划 |
| 10 | http://arxiv.org/abs/2512.05982v1 | FlockVote: LLM-Empowered Agent-Based Modeling for Simulating U.S. Presidential Elections | 高保真人口 profile 智能体，模拟投票决策与宏观结果 | 传统 ABM 规则简化，统计模型缺乏可解释性 | 美国总统选举模拟 |
| 11 | http://arxiv.org/abs/2511.19930v1 | Designing Reputation Systems for Manufacturing Data Trading Markets: A Multi-Agent Evaluation with Q-Learning and IRL-Estimated Utilities | 多 Agent 数据市场信誉系统仿真评估 | 数据交易信息不对称与信任缺失 | 制造数据交易市场 |
| 12 | http://arxiv.org/abs/2511.21783v1 | NetworkGames: Simulating Cooperation in Network Games with Personality-driven LLM Agents | 人格驱动 LLM Agent 模拟网络博弈合作演化 | 网络拓扑与人格对合作影响未探索 | 社会系统仿真 |
| 13 | http://arxiv.org/abs/2511.19726v1 | An Adaptive, Data-Integrated Agent-Based Modeling Framework for Explainable and Contestable Policy Design | 自适应多智能体学习框架，集成动态 regime 与信息论诊断。 | 解决多智能体系统模拟中决策规则静态且缺乏适应性问题。 | 政策设计/社会模拟 |
| 14 | http://arxiv.org/abs/2511.13233v1 | LLM-based Multi-Agent System for Simulating Strategic and Goal-Oriented Data Marketplaces | LLM-MAS：买卖Agent自主执行战略规划与交易行为 | 数据市场参与者交互与监管理解有限 | 数据市场模拟 |
| 15 | http://arxiv.org/abs/2511.00993v1 | Aligning LLM agents with human learning and adjustment behavior: a dual agent approach | 双智能体框架校准旅行者 Agent 人格，模拟人类学习与适应行为 | 解决人类出行行为建模复杂及现有 LLM 方法对齐度差的问题 | 交通仿真与政策分析 |
| 16 | http://arxiv.org/abs/2511.01218v1 | Optimizing Electric Vehicle Charging Station Placement Using Reinforcement Learning and Agent-Based Simulations | 结合深度 RL 与 Agent 仿真，混合奖励函数优化充电站选址 | 解决确定性奖励系统无法捕捉充电需求动态复杂性的问题 | 电动汽车充电基础设施规划 |
| 17 | http://arxiv.org/abs/2511.01415v1 | Modulation of temporal decision-making in a deep reinforcement learning agent under the dual-task paradigm | 双任务范式下 DRL 智能体时间决策干扰研究，模拟人类 timing 行为 | 解决 AI 视角下双任务时间处理干扰机制不明确的问题 | 认知科学与 DRL 行为研究 |
| 18 | http://arxiv.org/abs/2511.02119v1 | InsurAgent: A Large Language Model-Empowered Agent for Simulating Individual Behavior in Purchasing Flood Insurance | 五模块 LLM 智能体结合 RAG 与记忆，模拟洪水保险购买行为演化 | 解决传统模型难以捕捉保险决策定量概率及上下文信息的问题 | 行为建模与保险政策分析 |
| 19 | http://arxiv.org/abs/2511.05410v1 | Story Arena: A Multi-Agent Environment for Envisioning the Future of Software Engineering | 多智能体“编剧室”，独立立场代理对话构建共同愿景 | 解决理解 AI 对软件工程影响缺乏 AI 自身视角的问题 | 软件工程未来愿景模拟 |
| 20 | http://arxiv.org/abs/2511.10835v2 | What the flock knows that the birds do not: exploring the emergence of joint agency in multi-agent active inference | 主动推理Agent自组织涌现群体智能与集体知识 | 群体如何产生超越个体的联合代理与集体知识 | 生物群体行为模拟 |
| 21 | http://arxiv.org/abs/2511.08436v1 | Understanding Electro-communication and Electro-sensing in Weakly Electric Fish using Multi-Agent Deep Reinforcement Learning | MARL模拟弱电鱼电通信与感知行为 | 自然环境中多鱼行为神经记录实验困难 | 神经行为学与动物群体研究 |
| 22 | http://arxiv.org/abs/2511.06260v1 | LLM-Guided Reinforcement Learning with Representative Agents for Traffic Modeling | 代表性LLM Agent建模同质旅行者群体 | LLM交通Agent可扩展性差、选择 opaque、动态不稳定 | 交通建模与出行行为仿真 |
| 23 | http://arxiv.org/abs/2511.06791v1 | Coupling Agent-based Modeling and Life Cycle Assessment to Analyze Trade-offs in Resilient Energy Transitions | Agent建模与生命周期评估耦合框架 | 能源转型评估孤立、忽略关键交互与累积影响 | 能源转型规划与政策评估 |
| 24 | http://arxiv.org/abs/2511.02469v1 | Modeling Hawkish-Dovish Latent Beliefs in Multi-Agent Debate-Based LLMs for Monetary Policy Decision Classification | 多 LLM 代理辩论模拟 FOMC 决策，建模潜在信念。 | 静态分类模型忽略政策制定的审议性质。 | 货币政策决策预测 |
| 25 | http://arxiv.org/abs/2511.02606v1 | A Multi-Agent Psychological Simulation System for Human Behavior Modeling | 基于心理学理论模拟“内部议会”Agent 生成可信行为。 | 黑盒神经模型缺乏心理学透明度与对齐。 | 教师培训与人类行为研究 |
| 26 | http://arxiv.org/abs/2511.03758v3 | Leveraging LLM-based agents for social science research: insights from citation network simulations | 基于 LLM  Agent 模拟引用网络，验证科学科学理论。 | LLM 在社会模拟中的能力边界不清。 | 社会科学研究与模拟 |

[返回目录](#目录)

<a id="cat-13"></a>

## 具身智能Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2511.17384v1 | IndustryNav: Exploring Spatial Reasoning of Embodied Agents in Dynamic Industrial Navigation | 首个动态工业导航基准，引入 collision/warning 率指标 | 解决 VLLM 在动态真实环境空间推理及规划不足问题 | 工业仓库 embodied 代理 |
| 2 | http://arxiv.org/abs/2511.17855v1 | QuickLAP: Quick Language-Action Preference Learning for Autonomous Driving Agents | 贝叶斯框架融合物理与语言反馈，实时推断奖励函数 | 解决单一模态反馈不完整及意图模糊问题 | 自动驾驶代理 |
| 3 | http://arxiv.org/abs/2511.18005v1 | RAISECity: A Multimodal Agent Framework for Reality-Aligned 3D World Generation at City-Scale | 利用多模态基础工具获取知识，迭代 self-reflection | 解决城市级 3D 生成质量、保真度及可扩展性挑战 | 城市级 3D 世界生成 |
| 4 | http://arxiv.org/abs/2512.00259v1 | Design and Evaluation of a Multi-Agent Perception System for Autonomous Flying Networks | 利用多模态 LLM 和代理 AI 解释 UAV 收集的视听数据生成服务等级规范 | 解决自主飞行网络忽略用户感知及服务需求，难以实现零接触操作问题 | 自主飞行网络（UAV） |
| 5 | http://arxiv.org/abs/2512.00294v1 | Words into World: A Task-Adaptive Agent for Language-Guided Spatial Retrieval in AR | 模块化 AR 代理集成 MLLM 与接地视觉模型，构建动态 AR 场景图支持空间检索 | 解决传统 AR 依赖固定检测器，无法解释复杂开放词汇自然语言查询问题 | 增强现实（AR）空间检索 |
| 6 | http://arxiv.org/abs/2511.22134v1 | DualVLA: Building a Generalizable Embodied Agent via Partial Decoupling of Reasoning and Action | 双教师自适应蒸馏策略，解耦推理与动作生成 | 通用 VLA 模型动作性能退化，推理与动作冲突 | 通用具身机器人任务 |
| 7 | http://arxiv.org/abs/2512.05131v1 | AREA3D: Active Reconstruction Agent with Unified Feed-Forward 3D Perception and Vision-Language Guidance | 解耦视图不确定性建模，集成 VLM 提供语义引导 | 现有方法依赖手工几何 heuristic，观察冗余 | 主动 3D 重建 |
| 8 | http://arxiv.org/abs/2511.23055v2 | MindPower: Enabling Theory-of-Mind Reasoning in VLM-based Embodied Agents | 机器人中心框架，整合感知、心智推理与决策行动 | 现有智能体缺乏 ToM 决策，基准忽略 agent 自身视角 | 具身智能体心智理论 |
| 9 | http://arxiv.org/abs/2511.19865v1 | Agentic AI-Empowered Conversational Embodied Intelligence Networks in 6G | 多模态融合与自适应语义通信的具身网络 | 具身设备多模态融合与决策难 | 6G 具身智能网络 |
| 10 | http://arxiv.org/abs/2511.19430v1 | Cook and Clean Together: Teaching Embodied Agents for Parallel Task Execution | 基于运筹学知识的 3D 接地任务调度，支持并行任务执行。 | 解决具身智能体任务规划忽视并行操作与效率优化问题。 | 具身智能/任务调度 |
| 11 | http://arxiv.org/abs/2511.19663v1 | Fara-7B: An Efficient Agentic Model for Computer Use | 高效计算机使用智能体模型，基于合成数据训练原生 CUA 模型。 | 解决计算机使用智能体缺乏高质量人类交互数据集的问题。 | 计算机使用/智能体 |
| 12 | http://arxiv.org/abs/2511.12676v1 | BridgeEQA: Virtual Embodied Agents for Real Bridge Inspections | BridgeEQA基准与EMVR方法，基于图像场景图顺序导航 | 真实世界具身问答基准缺乏，桥梁检查场景复杂 | 基础设施检查 |
| 13 | http://arxiv.org/abs/2511.12998v3 | PerTouch: VLM-Driven Agent for Personalized and Semantic Image Retouching | VLM驱动Agent处理强弱指令，反馈驱动反思与场景感知记忆 | 图像修图平衡可控性与主观审美偏好 | 个性化图像修图 |
| 14 | http://arxiv.org/abs/2511.13297v1 | CorrectAD: A Self-Correcting Agentic System to Improve End-to-end Planning in Autonomous Driving | CorrectAD：PM-Agent+DriveSora生成模型自校正失败案例 | 端到端自动驾驶长尾问题导致安全关键失败 | 自动驾驶规划 |
| 15 | http://arxiv.org/abs/2511.00998v1 | GauDP: Reinventing Multi-Agent Collaboration through Gaussian-Image Synergy in Diffusion Policies | 构建高斯 - 图像协同表示，实现可扩展的感知感知模仿学习 | 解决具身多智能体局部控制与全局场景理解平衡难的问题 | 多臂协作机器人任务 |
| 16 | http://arxiv.org/abs/2511.01236v1 | Don't Just Search, Understand: Semantic Path Planning Agent for Spherical Tensegrity Robots in Unknown Environments | LLM 驱动语义 Agent，自适应观察窗口机制平衡探索与规划 | 解决球形张力机器人未知环境路径规划冗余搜索及易失败问题 | 球形张力机器人路径规划 |
| 17 | http://arxiv.org/abs/2511.01594v1 | MARS: Multi-Agent Robotic System with Multimodal Large Language Models for Assistive Intelligence | 四智能体集成多模态感知与分层决策，实现风险感知个性化协助 | 解决现有辅助系统在风险规划及语言计划落地执行难的问题 | 智能家居助残机器人 |
| 18 | http://arxiv.org/abs/2511.04646v1 | DR. WELL: Dynamic Reasoning and Learning with Symbolic World Model for Embodied LLM-Based Multi-Agent Collaboration | 神经符号框架，基于符号计划而非原始轨迹进行协作 | 解决具身多智能体协作中轨迹级协调易失败的问题 | 具身多智能体协作 |
| 19 | http://arxiv.org/abs/2511.10203v1 | VISTA: A Vision and Intent-Aware Social Attention Framework for Multi-Agent Trajectory Prediction | 递归目标条件Transformer整合长期意图与社交交互 | 密集交互环境中多Agent轨迹预测不真实、碰撞率高 | 自动驾驶/机器人系统 |
| 20 | http://arxiv.org/abs/2511.11022v1 | Miniature Testbed for Validating Multi-Agent Cooperative Autonomous Driving | 1:15比例微型测试台CIVAT集成V2V/V2I通信与智能基础设施 | 现有测试台缺乏配备传感、边缘计算与通信的智能基础设施 | 合作自动驾驶验证 |
| 21 | http://arxiv.org/abs/2511.08892v1 | Lumine: An Open Recipe for Building Generalist Agents in 3D Open Worlds | 统一感知推理行动的通用Agent配方 | 缺乏小时级复杂任务3D开放世界Agent | 3D游戏开放世界任务 |
| 22 | http://arxiv.org/abs/2511.03497v1 | ROSBag MCP Server: Analyzing Robot Data with LLMs for Agentic Embodied AI Applications | MCP 服务器分析 ROS 数据，自然语言交互处理机器人数据。 | 具身 AI 与 Agentic AI 交叉文献稀缺。 | 具身 AI 应用与机器人数据分析 |
| 23 | http://arxiv.org/abs/2511.03591v1 | Manifold-constrained Hamilton-Jacobi Reachability Learning for Decentralized Multi-Agent Motion Planning | 流形约束 HJR 学习框架，去中心化多 Agent 运动规划。 | 动态环境中纳入任务流形约束困难。 | 机器人多 Agent 运动规划 |

[返回目录](#目录)

<a id="cat-14"></a>

## Agent可解释性与透明度

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2512.11819v1 | A Modular LLM-Agent System for Transparent Multi-Parameter Weather Interpretation | 基于上下文的提示工程将数值预报转化为科学依据叙事，无需微调实现可解释性 | 解决传统预报输出 dense tables 缺乏解释、情境化和假设生成的问题 | 气象科学解释 |
| 2 | http://arxiv.org/abs/2511.20820v2 | SAGE: An Agentic Explainer Framework for Interpreting SAE Features in Language Models | Agent 主动解释框架解析 SAE 特征含义 | SAE 特征解释困难且不准确 | 模型可解释性 |
| 3 | http://arxiv.org/abs/2511.01425v1 | Learning to Seek Evidence: A Verifiable Reasoning Agent with Causal Faithfulness Analysis | 智能体学习策略主动寻求外部视觉证据，因果干预验证解释忠实性 | 解决高风险领域 AI 解释缺乏可验证性及信任度低的问题 | 医疗诊断等高风险领域解释 |
| 4 | http://arxiv.org/abs/2511.03878v1 | KnowThyself: An Agentic Assistant for LLM Interpretability | 整合解释工具为聊天接口，引导式解释模型内部机制 | 解决现有 LLM 解释工具碎片化且技术门槛高的问题 | LLM 模型研究与调试 |
| 5 | http://arxiv.org/abs/2511.10409v1 | Explaining Decentralized Multi-Agent Reinforcement Learning Policies | 生成去中心化MARL策略的任务排序与Agent合作摘要 | 现有解释方法集中于集中式MARL，忽视去中心化不确定性 | 去中心化多Agent系统 |
| 6 | http://arxiv.org/abs/2511.15716v1 | MACIE: Multi-Agent Causal Intelligence Explainer for Collective Behavior Understanding | 结合结构因果模型与Shapley值解释多Agent行为 | 现有XAI方法难以归因集体结果到个体 | 安全关键MARL系统可解释性 |

[返回目录](#目录)

<a id="cat-15"></a>

## 低代码/无代码Agent平台

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2511.21438v2 | Conversational No-code, Multi-agentic Disease Module Identification and Drug Repurposing Prediction with ChatDRex | 对话式无代码多 Agent 药物重定位预测平台 | 生物信息分析工具碎片化且门槛高 | 药物重定位研究 |
| 2 | http://arxiv.org/abs/2511.13158v1 | Agent-Oriented Visual Programming for the Web of Things | 基于JaCaMo的块状视觉开发环境，整合Web of Things | 无编程经验用户难以设计配置自主软件 | 物联网自动化任务 |
| 3 | http://arxiv.org/abs/2511.09087v2 | Tele-LLM-Hub: Building Context-Aware Multi-Agent LLM Systems for Telecom Networks | TeleMCP协议+低代码界面构建电信多Agent | 电信网络复杂需领域特定多Agent系统 | 5G及下一代无线网络 |
| 4 | http://arxiv.org/abs/2511.03690v1 | The OpenHands Software Agent SDK: A Composable and Extensible Foundation for Production Agents | 可组合 SDK，集成沙箱执行与多 LLM 路由。 | 构建生产级软件工程 Agent 复杂。 | 软件开发 Agent 构建与部署 |

[返回目录](#目录)
