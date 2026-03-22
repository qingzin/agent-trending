# AI agents 2025年7月学术分类汇总

共收录 470 篇论文，按研究方向分类整理如下。

## 目录

- [Agent学习与自进化（25篇）](#cat-01)
- [基于Agent的应用系统（102篇）](#cat-02)
- [Agent架构与框架设计（45篇）](#cat-03)
- [多Agent协作与通信（44篇）](#cat-04)
- [具身智能Agent（24篇）](#cat-05)
- [Agent规划与推理（14篇）](#cat-06)
- [Agent仿真与社会模拟（29篇）](#cat-07)
- [Agent记忆与知识管理（16篇）](#cat-08)
- [人机协作Agent（21篇）](#cat-09)
- [Agent评测与基准（37篇）](#cat-10)
- [Agent安全与对齐（50篇）](#cat-11)
- [多Agent强化学习（43篇）](#cat-12)
- [Agent工具使用与环境交互（15篇）](#cat-13)
- [低代码/无代码Agent平台（2篇）](#cat-14)
- [Agent可解释性与透明度（3篇）](#cat-15)

<a id="cat-01"></a>

## Agent学习与自进化

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2507.03112v1 | RLVER: Reinforcement Learning with Verifiable Emotion Rewards for Empathetic Agents | 首创端到端强化学习框架，利用可验证情感奖励培养LLM共情能力 | LLM情感智能落后于认知能力，对话领域情感智能应用不足 | 情感对话Agent |
| 2 | http://arxiv.org/abs/2507.03616v2 | EvoAgentX: An Automated Framework for Evolving Agentic Workflows | 五层模块化架构，集成三种MAS优化算法迭代优化Agent工作流 | 现有MAS框架需手动配置，缺乏动态进化和性能优化原生支持 | 多Agent工作流自动化 |
| 3 | http://arxiv.org/abs/2507.04103v4 | How to Train Your LLM Web Agent: A Statistical Diagnosis | 两阶段流水线（SFT+on-policy RL），统计诊断计算分配，55%计算量达峰值性能 | 单步任务焦点忽视多步交互复杂性，后训练计算成本高 | LLM Web Agent训练 |
| 4 | http://arxiv.org/abs/2507.04889v1 | Fine-tuning on simulated data outperforms prompting for agent tone of voice | 模拟数据微调小模型优于系统提示，100样本即可实现高对话响应率 | 语音应用中实现自然对话语调困难，复杂提示存在指令遵循限制 | 语音交互Agent |
| 5 | http://arxiv.org/abs/2507.02004v1 | STELLA: Self-Evolving LLM Agent for Biomedical Research | 自进化 LLM 代理，动态扩展工具库与推理模板，从经验学习 | 生物研究工具碎片化及代理适应力限制 | 生物医学研究与实验 |
| 6 | http://arxiv.org/abs/2507.02554v2 | AI Research Agents for Machine Learning: Search, Exploration, and Generalization in MLE-bench | 形式化 AI 研究代理为搜索策略导航解空间，优化算子与策略 | 自动化机器学习模型设计挑战及搜索空间导航 | 机器学习研究与 Kaggle 竞赛 |
| 7 | http://arxiv.org/abs/2507.14897v1 | AgentFly: Extensible and Scalable Reinforcement Learning for LM Agents | 可扩展 Agent-RL 框架，支持多轮交互与异步工具调用训练 | LM Agent 与强化学习结合缺乏系统研究与高效训练框架 | 语言模型智能体强化学习 |
| 8 | http://arxiv.org/abs/2507.15061v1 | WebShaper: Agentically Data Synthesizing via Information-Seeking Formalization | 形式化驱动的信息寻求数据合成，精确控制推理结构 | 高质量训练数据稀缺，现有信息驱动范式导致结构不一致 | 信息寻求智能体训练数据合成 |
| 9 | http://arxiv.org/abs/2507.10741v2 | Ground-Compose-Reinforce: Grounding Language in Agentic Behaviours... | 提出神经符号框架，利用奖励机器从有限数据训练 RL 代理。 | 解决语言 grounding 需大量数据或手动设计奖励的问题。 | 具身语言代理训练 |
| 10 | http://arxiv.org/abs/2507.12732v1 | Strategy Adaptation in Large Language Model Werewolf Agents | 提出方法，根据其他玩家态度与语境切换预定义策略。 | 解决狼人杀代理无法适应变化局势及隐式策略定义问题。 | 游戏智能体策略 |
| 11 | http://arxiv.org/abs/2507.13140v4 | Model-free Reinforcement Learning for Model-based Control... | 提出基于模型的代理作为控制策略近似，结合无模型 RL。 | 解决无模型 RL 样本效率低、不安全及可解释性有限问题。 | 安全可控决策代理 |
| 12 | http://arxiv.org/abs/2507.09540v1 | Learning to Control Dynamical Agents via Spiking Neural Networks and Metropolis-Hastings Sampling | 首次用 Metropolis-Hastings 采样训练 SNN 控制动态智能体 | SNN 训练因 spike 通信不可微而面临挑战 | 神经形态控制 |
| 13 | http://arxiv.org/abs/2507.18884v1 | MindFlow+: A Self-Evolving Agent for E-Commerce Customer Service | 结合 LLM 与模仿学习/离线 RL，自我进化对话 Agent | 传统意图系统难以处理动态多轮交互 | 电商客户服务 |
| 14 | http://arxiv.org/abs/2507.18992v2 | Reinforcement Learning via Conservative Agent for Environments with Random Delays | 保守 Agent 将随机延迟环境重构为恒定延迟 | 随机延迟环境违反 Markov 假设且未探索 | 连续控制任务 RL |
| 15 | http://arxiv.org/abs/2507.19725v1 | Minding Motivation: The Effect of Intrinsic Motivation on Agent Behaviors | 实证评估三种 IM 技术对 Agent 行为影响 | IM 导致 reward hacking 且影响未知 | 游戏 RL 环境 |
| 16 | http://arxiv.org/abs/2507.19849v1 | Agentic Reinforced Policy Optimization | ARPO 算法，熵基自适应 rollout 平衡探索 | 当前 RL 算法 inadequately 平衡推理与工具交互 | 多轮 LLM Agent 训练 |
| 17 | http://arxiv.org/abs/2507.21046v4 | A Survey of Self-Evolving Agents: What, When, How, and Where to Evolve on the Path to Artificial Super Intelligence | 首个系统综述围绕what/when/how进化三维度组织领域 | LLM静态性质成为开放交互环境中的关键瓶颈 | 自进化Agent研究与应用 |
| 18 | http://arxiv.org/abs/2507.21924v1 | MMAT-1M: A Large Reasoning Dataset for Multimodal Agent Tuning | 首个百万级多模态Agent调优数据集支持CoT/反思/工具使用 | 多模态领域缺乏大规模高质量Agent调优数据集 | 多模态大语言模型调优 |
| 19 | http://arxiv.org/abs/2507.22255v1 | Agent-centric learning: from external reward maximization to internal knowledge curation | 提出表征赋权将控制焦点从外部转向内部知识结构调整 | 外部焦点产生缺乏适应性的专业化Agent | 通用智能系统学习范式 |
| 20 | http://arxiv.org/abs/2507.22844v1 | RLVMR: Reinforcement Learning with Verifiable Meta-Reasoning Rewards for Robust Long-Horizon Agents | 集成可验证元推理奖励的 RL 框架 | 解决仅优化最终成功导致推理路径低效问题 | 长程自主 agent 任务 |
| 21 | http://arxiv.org/abs/2507.23554v1 | DICE: Dynamic In-Context Example Selection in LLM Agents via Efficient Knowledge Transfer | 基于因果 lens 的动态示例选择框架 | 解决 ICL 示例选择敏感导致性能不稳定问题 | 通用 LLM agent 任务 |
| 22 | http://arxiv.org/abs/2507.15640v1 | Data Mixing Agent: Learning to Re-weight Domains for Continual Pre-training | 首个基于模型的端到端框架，通过强化学习学习领域重加权启发式 | 持续预训练中灾难性遗忘及手动数据混合策略效率低 | 大语言模型持续预训练 |
| 23 | http://arxiv.org/abs/2507.17131v2 | Enabling Self-Improving Agents to Learn at Test Time With Human-In-The-Loop Guidance | ARIA框架通过结构化自对话评估不确定性，主动请求人类专家指导并更新知识库 | 离线微调和标准提示无法在运行时有效适应新知识 | 动态知识环境（合规、风险筛查） |
| 24 | http://arxiv.org/abs/2507.17311v3 | A Self-Evolving AI Agent System for Climate Science | EarthLink首个自进化AI Agent系统，自动化整个研究工作流程 | 地球科学数据量和碎片化超出人类分析能力，发现瓶颈 | 气候科学研究 |
| 25 | http://arxiv.org/abs/2507.07441v2 | SAND: Boosting LLM Agents with Self-Taught Action Deliberation | 自教动作审议框架，显式 deliberation 候选动作 | 微调方法易过commit 次优动作，缺乏动作空间探索 | LLM 智能体动作决策优化 |

[返回目录](#目录)

<a id="cat-02"></a>

## 基于Agent的应用系统

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2507.05275v1 | A Fuzzy Supervisor Agent Design for Clinical Reasoning Assistance in a Multi-Agent Educational Clinical Scenario Simulation | 模糊监督Agent利用模糊推理系统实时解读学生交互，提供自适应反馈 | 医学教育中临床推理辅助困难，缺乏可扩展的人工监督 | 医学教育临床场景模拟 |
| 2 | http://arxiv.org/abs/2507.03435v1 | ElliottAgents: A Natural Language-Driven Multi-Agent System for Stock Market Analysis and Prediction | 结合AI驱动分析与艾略特波浪原理，Agent间自然语言对话协作 | 复杂金融数据与人类理解之间的鸿沟，需可解释预测系统 | 股票市场分析与预测 |
| 3 | http://arxiv.org/abs/2507.03460v2 | Multi-Agent Reasoning for Cardiovascular Imaging Phenotype Analysis | 多学科AI Agent团队通过迭代自组织推理动态发现表型与关联 | 传统方法依赖人工假设检验，忽视成像表型与非线性依赖 | 心血管成像表型分析 |
| 4 | http://arxiv.org/abs/2507.03493v1 | AI-VaxGuide: An Agentic RAG-Based LLM for Vaccination Decisions | 基于Agentic RAG的多语言智能问答系统，将静态指南转化为交互式知识库 | 医疗专业人员难以快速高效获取免疫接种指南，尤其在紧急情况 | 疫苗接种决策支持 |
| 5 | http://arxiv.org/abs/2507.10448v1 | FinTeam: A Multi-Agent Collaborative Intelligence System for Comprehensive Financial Scenarios | 四LLM Agent工作流（文档分析/分析/会计/顾问），针对金融专业知识训练 | 现有LLM微调于简单QA，无法全面分析真实金融场景 | 金融报告生成 |
| 6 | http://arxiv.org/abs/2507.04036v1 | PresentAgent: Multimodal Agent for Presentation Video Generation | 模块化流水线分割文档、规划渲染幻灯片、生成旁白、合成视频 | 现有方法限于静态幻灯片或文本摘要，无法生成同步视听内容 | 演示视频自动生成 |
| 7 | http://arxiv.org/abs/2507.05292v1 | A LLM-Driven Multi-Agent Systems for Professional Development of Mathematics Teachers | I-VIP智能辅导平台，多Agent框架支持知识期望分析/响应评分/反馈生成 | 为教师提供公平及时的专业发展机会面临重大挑战 | 数学教师专业发展 |
| 8 | http://arxiv.org/abs/2507.04770v1 | FurniMAS: Language-Guided Furniture Decoration using Multi-Agent System | 混合LLM/非LLM Agent团队，通过沟通/推理/验证转化需求为装饰结果 | 高质量家具装饰耗时且需专业艺术专长，难以自动化 | 家具装饰自动化 |
| 9 | http://arxiv.org/abs/2507.04893v1 | MARBLE: A Multi-Agent Rule-Based LLM Reasoning Engine for Accident Severity Prediction | 多Agent规则基LLM引擎，专业Agent分解任务，规则/LLM共识协调预测 | 事故严重度预测因数据不完整/特征依赖/类别不平衡而困难 | 交通事故严重度预测 |
| 10 | http://arxiv.org/abs/2507.05321v1 | AGACCI : Affiliated Grading Agents for Criteria-Centric Interface in Educational Coding Contexts | 多Agent系统分配专业评估角色，提高代码评估准确性/可解释性/一致性 | 现有VLM方法难以处理含可执行组件的复杂教育工件 | 教育代码评估 |
| 11 | http://arxiv.org/abs/2507.05241v2 | SciMaster: Towards General-Purpose Scientific AI Agents, Part I. X-Master as Foundation: Can We Lead on Humanity's Last Exam? | X-Master工具增强推理Agent，X-Masters分散堆叠工作流，HLE得分32.1% | 构建通用科学Agent基础架构，验证人类知识前沿理解能力 | 科学发现AI Agent |
| 12 | http://arxiv.org/abs/2507.00378v2 | iPanda: An LLM-based Agent for Automated Conformance Testing of Communication Protocols | LLM 自动化协议一致性测试框架，结合检索增强与迭代优化 | 手动编写测试用例效率低且劳动密集 | 通信协议一致性测试 |
| 13 | http://arxiv.org/abs/2507.01069v1 | Agentic AI in Product Management: A Co-Evolutionary Model | 提出产品管理中代理 AI 的协同进化框架，指导全生命周期集成 | 传统框架缺乏 AI 集成指导及 PM 角色演变 | 产品管理与软件组织 |
| 14 | http://arxiv.org/abs/2507.00535v1 | Rethinking Group Recommender Systems in the Era of Generative AI: From One-Shot Recommendations to Agentic Group Decision Support | 利用生成式 AI 助手辅助群体决策交互，重构推荐系统假设 | 群体推荐系统实际 adoption 低及假设不匹配 | 群体推荐与决策支持 |
| 15 | http://arxiv.org/abs/2507.00875v2 | TransLaw: A Large-Scale Dataset and Multi-Agent Benchmark Simulating Professional Translation of Hong Kong Case Law | 多代理框架模拟香港案例法专业翻译，结合 RAG 与迭代反馈 | 法律翻译术语不准及文化细微差别缺失 | 香港案例法翻译 |
| 16 | http://arxiv.org/abs/2507.00914v1 | Large Language Model Powered Intelligent Urban Agents: Concepts, Capabilities, and Applications | 综述城市 LLM 代理概念、能力及应用领域，建立基础与路线图 | 城市智能系统决策复杂性及跨域问题解决 | 智慧城市与 urban decision-making |
| 17 | http://arxiv.org/abs/2507.01315v2 | Wired for Reuse: Automating Context-Aware Code Adaptation in IDEs via LLM-Based Agent | LLM 代理自动化 IDE 中上下文感知代码适配，平衡效率与自主 | 代码复用中变量上下文绑定困难及 heuristic 失效 | 软件开发与 IDE 辅助 |
| 18 | http://arxiv.org/abs/2507.01717v1 | Agent Ideate: A Framework for Product Idea Generation from Patents Using Agentic AI | 利用代理 AI 从专利生成产品商业创意，解锁潜在创新 | 专利知识 accessing 及解释挑战与创新 pipeline 增强 | 产品创意生成与专利挖掘 |
| 19 | http://arxiv.org/abs/2507.02182v1 | Enhancing COBOL Code Explanations: A Multi-Agents Approach Using Large Language Models | 多代理方法利用 LLM 解释 COBOL 代码，利用上下文信息 | COBOL 代码文档缺乏及维护难与 token 窗口限制 | COBOL 系统维护与理解 |
| 20 | http://arxiv.org/abs/2507.02252v1 | SurgVisAgent: Multimodal Agentic Model for Versatile Surgical Visual Enhancement | 多模态代理模型用于多样手术视觉增强，动态识别失真类别 | 手术干预单一任务算法局限性及复杂现实场景无效 | 手术视觉辅助与决策 |
| 21 | http://arxiv.org/abs/2507.02353v1 | OMS: On-the-fly, Multi-Objective, Self-Reflective Ad Keyword Generation via LLM Agent | 在线多目标自反思广告关键词生成 Agent，监控在线性能 | LLM 关键词生成依赖数据及质量控制弱与多目标优化 | 赞助搜索广告与关键词决策 |
| 22 | http://arxiv.org/abs/2507.02424v2 | CyberRAG: An Agentic RAG cyber attack classification and reporting tool | 代理 RAG 框架用于网络攻击分类报告，动态控制流与自适应推理 | IDS 警报过多及标准 RAG 检索无关与解释性差 | 网络安全与入侵检测 |
| 23 | http://arxiv.org/abs/2507.02616v1 | DynamiCare: A Dynamic Multi-Agent Framework for Interactive and Open-Ended Medical Decision-Making | 动态多代理框架用于交互式医疗决策，模拟多轮诊断循环 | 医疗诊断模拟单轮任务偏离现实及不确定性缺失 | 临床决策与医疗诊断模拟 |
| 24 | http://arxiv.org/abs/2507.02626v1 | VRAgent-R1: Boosting Video Recommendation with MLLM-based Agents via Reinforcement Learning | 基于 MLLM 代理强化学习提升视频推荐，模拟用户 item 建模 | 视频推荐多模态内容理解及用户模拟次优问题 | 视频推荐系统 |
| 25 | http://arxiv.org/abs/2507.02660v1 | Hey AI, Generate Me a Hardware Code! Agentic AI-based Hardware Design & Verification | 代理 AI 基于硬件设计与验证端到端流程，HITL 干预与自反思 | 集成电路开发验证耗时费力及 bug-free tape-out 确保 | 硬件设计验证与 IC 开发 |
| 26 | http://arxiv.org/abs/2507.02773v2 | KERAP: A Knowledge-Enhanced Reasoning Approach for Accurate Zero-shot Diagnosis Prediction Using Multi-agent LLMs | 知识图谱增强推理多代理 LLM 诊断预测，迭代 refine 预测 | 医疗诊断预测依赖监督训练及幻觉与结构化推理缺失 | 零样本医疗诊断预测 |
| 27 | http://arxiv.org/abs/2507.13729v1 | AGENTS-LLM: Augmentative GENeration of Challenging Traffic Scenarios with an Agentic LLM Framework | 利用自然语言描述增强真实交通场景，细粒度控制输出 | 解决自动驾驶测试中罕见场景数据收集难、生成控制弱 | 自动驾驶规划测试 |
| 28 | http://arxiv.org/abs/2507.13814v1 | CodeEdu: A Multi-Agent Collaborative Platform for Personalized Coding Education | 多智能体协作平台，动态分配任务提供个性化编程教育 | 现有单 Agent 无法评估能力、设计学习计划及互动辅导 | 编程教育与学习辅导 |
| 29 | http://arxiv.org/abs/2507.14267v1 | DREAMS: Density Functional Theory Based Research Engine for Agentic Materials Simulation | 分层多智能体框架结合 LLM 规划与领域 Agent 进行 DFT 模拟 | 材料发现依赖专家经验，训练成本高且错误处理复杂 | 计算材料发现与模拟 |
| 30 | http://arxiv.org/abs/2507.17852v1 | Technical Implementation of Tippy: Multi-Agent Architecture and System Design for Drug Discovery Laboratory Automation | 分布式微服务架构，五类专用 Agent 协调药物发现实验室工作流 | 实验室自动化工作流复杂，需协调安全、可扩展性与集成 | 药物发现实验室自动化 |
| 31 | http://arxiv.org/abs/2507.14680v1 | WSI-Agents: A Collaborative Multi-Agent System for Multi-Modal Whole Slide Image Analysis | 集成专用功能 Agent，通过任务分配与验证机制提升准确性 | 多模态大模型在病理 WSI 分析中表现不如任务专用模型 | 数字病理全切片图像分析 |
| 32 | http://arxiv.org/abs/2507.14730v4 | Towards Urban Planing AI Agent in the Age of Agentic AI | 呼吁结合 Agentic AI 与参与式城市规划，超越预定义生成结构 | 现有生成式城市规划忽略领域专家工具与强假设限制 | 城市规划与设计 |
| 33 | http://arxiv.org/abs/2507.14899v3 | InsightX Agent: An LMM-based Agentic Framework with Reliable X-ray NDT Analysis | LMM 协调检测器与反思工具，主动推理提升诊断可靠性 | 现有深度学习缺乏交互性与自我评估，限制操作员信任 | 工业 X 射线无损检测分析 |
| 34 | http://arxiv.org/abs/2507.14912v1 | Redefining Elderly Care with Agentic AI: Challenges and Opportunities | 探讨 Agentic AI 在老年护理中的主动决策与个性化追踪潜力 | 全球老龄化需新策略，同时关注隐私与伦理挑战 | 老年护理与健康监测 |
| 35 | http://arxiv.org/abs/2507.14969v1 | Think Like an Engineer: A Neuro-Symbolic Collaboration Agent for Generative Software Requirements Elicitation and Self-Review | 嵌入因果效应图的神经符号协作，自愈合 CEG 审查 Gherkin 场景 | 终端用户需求描述模糊，现有方法难表达因果逻辑 | 软件需求 elicitation 与审查 |
| 36 | http://arxiv.org/abs/2507.15241v1 | FaultLine: Automated Proof-of-Vulnerability Generation Using LLM Agents | LLM 工作流追踪数据流，自动生成漏洞证明测试用例 | 漏洞报告常不完整，缺乏验证修复与防止回归的 PoV 测试 | 软件安全漏洞测试生成 |
| 37 | http://arxiv.org/abs/2507.15245v1 | SPAR: Scholar Paper Retrieval with LLM-based Agents for Enhanced Academic Search | 多智能体框架结合 RefChain 查询分解与演化，提升搜索灵活性 | 现有学术检索系统依赖刚性管道，推理能力有限 | 学术文献检索与搜索 |
| 38 | http://arxiv.org/abs/2507.15268v2 | IM-Chat: A Multi-agent LLM Framework Integrating Tool-Calling and Diffusion Modeling for Knowledge Transfer in Injection Molding Industry | 多 Agent 框架整合工具调用与扩散模型，促进注塑行业知识转移 | 注塑行业面临经验丰富的工人退休与多语言沟通障碍 | 注塑制造业知识转移 |
| 39 | http://arxiv.org/abs/2507.15419v1 | PhishIntentionLLM: Uncovering Phishing Website Intentions through Multi-Agent Retrieval-Augmented Generation | 多 Agent RAG 框架从截图识别钓鱼意图，发布首个意图数据集 | 现有方法侧重检测，未探索 underlying 恶意意图识别 | 网络安全钓鱼意图分析 |
| 40 | http://arxiv.org/abs/2507.10281v1 | Toward Real-World Table Agents: Capabilities, Workflows... | 定义 LLM 表格智能体的五项核心能力，分析现有方法。 | 解决真实世界表格任务中的噪声、结构异质性问题。 | 金融、医疗表格处理 |
| 41 | http://arxiv.org/abs/2507.10522v1 | DeepResearch$^{\text{Eco}}$: A Recursive Agentic Workflow... | 引入递归代理工作流，支持深度和广度控制的科学合成。 | 解决生态学研究问题中科学文献检索与综合的效率问题。 | 生态科学研究 |
| 42 | http://arxiv.org/abs/2507.10778v2 | Warehouse Spatial Question Answering with LLM Agent | 提出具有空间推理能力的 LLM 代理系统，集成多种工具。 | 解决复杂室内仓库场景中的空间问答与对象检索任务。 | 智慧仓储管理 |
| 43 | http://arxiv.org/abs/2507.15867v1 | RDMA: Cost Effective Agent-Driven Rare Disease Discovery... | 提出 RDMA 框架，模拟专家在 EHR 中识别罕见病模式。 | 解决 EHR 中罕见病信息 buried 及隐私风险问题。 | 医疗健康记录分析 |
| 44 | http://arxiv.org/abs/2507.10911v1 | Lessons Learned from Evaluation of LLM based Multi-agents... | 设计模拟多学科团队的 MAS 框架，评估治疗推荐安全性。 | 解决多病共存患者治疗推荐中的冲突与可扩展性问题。 | 医疗治疗推荐 |
| 45 | http://arxiv.org/abs/2507.11272v1 | An Empirical Study of Multi-Agent RAG for Real-World University... | 部署 MARAUS 系统，结合混合检索与多代理编排进行招生咨询。 | 解决低资源教育场景中 LLM 幻觉与响应准确性问题。 | 大学招生咨询 |
| 46 | http://arxiv.org/abs/2507.12261v2 | Infherno: End-to-end Agent-based FHIR Resource Synthesis... | 提出端到端框架，利用代理和代码执行合成 FHIR 资源。 | 解决临床笔记到结构化 FHIR 资源转换的泛化性与一致性。 | 医疗数据互操作性 |
| 47 | http://arxiv.org/abs/2507.12621v1 | NLI4VolVis: Natural Language Interaction for Volume Visualization... | 集成多代理 LLM 架构，支持自然语言查询与编辑体积场景。 | 解决体积可视化中交互 rigid 及非专家学习成本高的问题。 | 科学数据可视化 |
| 48 | http://arxiv.org/abs/2507.13190v1 | RIDAS: A Multi-Agent Framework for AI-RAN... | 提出 RIDAS 框架，包含表示驱动代理和意图驱动代理。 | 解决 6G 网络中用户意图与底层参数配置之间的差距。 | 无线接入网络 (RAN) |
| 49 | http://arxiv.org/abs/2507.07887v1 | Automating MD simulations for Proteins using Large language Models: NAMD-Agent | 利用 LLM 自动化 pipeline 生成 MD 输入文件 | 分子动力学模拟输入文件准备耗时且易错 | 计算结构生物学 |
| 50 | http://arxiv.org/abs/2507.07906v1 | Agentic Retrieval of Topics and Insights from Earnings Calls | LLM 智能体提取话题构建本体，推断公司级洞察 | 传统话题建模难以动态捕捉新兴话题与关系 | 金融分析与财报会议 |
| 51 | http://arxiv.org/abs/2507.08325v2 | CRMAgent: A Multi-Agent LLM System for E-Commerce CRM Message Template Generation | 多智能体系统生成高质量 CRM 消息模板与写作指导 | 商家缺乏撰写 persuasive copy 的专业知识与工具 | 电子商务 CRM |
| 52 | http://arxiv.org/abs/2507.08392v3 | Multi-Agent LLMs as Ethics Advocates for AI-Based Systems | 引入伦理倡导智能体生成伦理需求草案 | 手动 eliciting 伦理需求耗时且常被低优先级对待 | 系统需求工程 |
| 53 | http://arxiv.org/abs/2507.10577v2 | Truth Sleuth and Trend Bender: AI Agents to fact-check YouTube videos and influence opinions | 双智能体系统事实检查 YouTube 视频并参与评论互动 | misinformation 在数字世界快速传播，威胁显著 | 社交媒体事实检查 |
| 54 | http://arxiv.org/abs/2507.10584v2 | ARPaCCino: An Agentic-RAG for Policy as Code Compliance | 结合 LLM、RAG 与工具验证自动化生成 PaC 规则 | 策略即代码采用受限于语言复杂性与配置风险 | 基础设施即代码合规 |
| 55 | http://arxiv.org/abs/2507.08584v1 | To Trade or Not to Trade: An Agentic Approach to Estimating Market Risk Improves Trading Decisions | 智能体系统迭代发现随机微分方程估计市场风险 | 现有金融智能体缺乏 principled 模型构建步骤 | 金融交易决策 |
| 56 | http://arxiv.org/abs/2507.08619v2 | Agentic Large Language Models for Conceptual Systems Engineering and Design | 结构化多智能体系统管理需求提取与代码生成 | 早期工程设计涉及复杂推理，现有工作流难保持连续性 | 系统工程设计 |
| 57 | http://arxiv.org/abs/2507.08648v1 | DatasetAgent: A Novel Multi-Agent System for Auto-Constructing Datasets from Real-World Images | 多智能体协作系统从真实图像自动构建数据集 | 图像数据集构建依赖耗时低效的手动收集标注 | 图像数据集构建 |
| 58 | http://arxiv.org/abs/2507.20468v1 | Building crypto portfolios with agentic AI | 多智能体系统自主构建评估加密资产分配 | 加密市场高波动性导致动态投资组合管理挑战 | 加密货币投资 |
| 59 | http://arxiv.org/abs/2507.08958v2 | Bridging Literature and the Universe Via A Multi-Agent Large Language Model System | 多智能体系统自动化文献参数配置与初步分析 | 物理学家从文献提取模拟参数耗时且易错 | 宇宙学模拟研究 |
| 60 | http://arxiv.org/abs/2507.09023v1 | Accelerating Drug Discovery Through Agentic AI: A Multi-Agent Approach to Laboratory Automation in the DMTA Cycle | 五专用智能体自动化 DMTA 循环实验室工作流 | 传统药物发现方法难满足现代治疗开发需求 | 药物发现实验室 |
| 61 | http://arxiv.org/abs/2507.09174v1 | RAMA: Retrieval-Augmented Multi-Agent Framework for Misinformation Detection in Multimodal Fact-Checking | 检索增强多智能体框架验证多媒体 misinformation | 多模态 misinformation  proliferations 挑战自动事实检查 | 多模态事实检查 |
| 62 | http://arxiv.org/abs/2507.20474v3 | MountainLion: A Multi-Modal LLM-Based Agent System for Interpretable and Adaptive Financial Trading | 多模态多智能体系统解释金融数据生成投资策略 | 加密货币交易需整合多模态异构数据，传统方法可解释性差 | 金融交易 |
| 63 | http://arxiv.org/abs/2507.18115v1 | Agentic AI framework for End-to-End Medical Data Inference | 模块化任务特定 Agent 系统，自动化临床数据管道 | 医疗 ML 解决方案构建昂贵且劳动密集 | 医疗临床数据推理 |
| 64 | http://arxiv.org/abs/2507.18190v2 | TN-AutoRCA: Benchmark Construction and Agentic Framework for Self-Improving Alarm-Based Root Cause Analysis in Telecommunication Networks | 构建基准与 Agent 框架，实现自我改进根因分析 | 电信网络根因分析复杂且缺乏基准 | 电信网络报警根因分析 |
| 65 | http://arxiv.org/abs/2507.18755v1 | Agentic Program Repair from Test Failures at Scale: A Neuro-symbolic approach with static analysis and test execution feedback | 工程 Agent 基于测试失败修复代码，神经符号方法 | 大规模代码库中基于测试失败的修复 | 软件工程代码修复 |
| 66 | http://arxiv.org/abs/2508.06497v1 | Forecasting Commodity Price Shocks Using Temporal and Semantic Fusion of Prices Signals and Agentic Generative AI Extracted Economic News | 混合框架融合价格数据与 Agent 提取新闻语义 | 商品价格 spikes 预测对经济缓冲有限国家 vital | 商品价格 shock 预测 |
| 67 | http://arxiv.org/abs/2507.18957v1 | SLICEMATE: Accurate and Scalable Static Program Slicing via LLM-Powered Agents | 三 Agent 协作（合成/验证/ refinement）进行程序切片 | 传统切片工具难以扩展且处理不完整语法失败 | 软件分析程序切片 |
| 68 | http://arxiv.org/abs/2507.18993v1 | Agent0: Leveraging LLM Agents to Discover Multi-value Features from Text for Enhanced Recommendations | Agent0 系统自动化从文本提取信息构建特征 | 推荐系统分类特征获取昂贵 | 推荐系统特征工程 |
| 69 | http://arxiv.org/abs/2507.19771v1 | Large Language Model Agent for Structural Drawing Generation Using ReAct Prompt Engineering and Retrieval Augmented Generation | LLM Agent 结合 RAG 生成结构图纸代码 | 生成结构图纸劳动密集且耗时 | 土木工程结构绘图 |
| 70 | http://arxiv.org/abs/2507.21179v2 | CANDLE: A Cross-Modal Agentic Knowledge Distillation Framework for Interpretable Sarcopenia Diagnosis | CANDLE 框架，耦合 SHAP 证据与 RL 训练 LLM 推理 | 医疗诊断任务缺乏可解释性与部署效率 | 肌肉减少症诊断 |
| 71 | http://arxiv.org/abs/2507.20230v3 | A Multi-Agent System Enables Versatile Information Extraction from the Chemical Literature | MLLM多Agent系统协调专用工具提取化学信息 | 化学文献信息多模态和风格 variability限制自动提取 | 化学反应数据库构建、化学研究 |
| 72 | http://arxiv.org/abs/2508.04714v2 | Prescriptive Agents based on RAG for Automated Maintenance (PARAM) | 多Agent处理维护手册+网络搜索生成结构化建议 | 工业维护需及时干预防止灾难性故障 | 工业机械维护、轴承振动分析 |
| 73 | http://arxiv.org/abs/2507.21035v2 | GenoMAS: A Multi-Agent Framework for Scientific Discovery via Code-Driven Gene Expression Analysis | 六专用Agent通过类型化消息传递协作分析基因表达 | 从原始转录组数据提取洞察需大量领域专业知识 | 生物医学发现、基因表达分析 |
| 74 | http://arxiv.org/abs/2507.21382v1 | MAAD: Automate Software Architecture Design through Knowledge-Driven Multi-Agent Collaboration | 四专用Agent协作解释需求生成架构蓝图 | 软件架构设计耗时依赖架构师且设计替代方案有限 | 软件架构设计自动化 |
| 75 | http://arxiv.org/abs/2508.10904v3 | A2H-MAS: An Algorithm-to-HLS Multi-Agent System for Automated and Reliable FPGA Implementation | 模块化分层MAS分配明确职责+执行验证确保正确性 | 算法到FPGA实现需专家调优且迭代漫长 | 无线通信算法FPGA实现 |
| 76 | http://arxiv.org/abs/2507.21471v2 | LUMIR: an LLM-Driven Unified Agent Framework for Multi-task Infrared Spectroscopy Reasoning | 整合文献知识库、预处理、特征提取、预测建模统一管道 | 高维信号和重叠波段阻碍传统化学计量方法 | 红外光谱分析、化学材料属性分析 |
| 77 | http://arxiv.org/abs/2507.21694v1 | A Multi-Agent Generative AI Framework for IC Module-Level Verification Automation | MAVF框架多专用Agent协作从规范到testbench自动转换 | 芯片验证是开发周期关键瓶颈且单LLM方法有限 | IC模块级验证自动化 |
| 78 | http://arxiv.org/abs/2507.22205v1 | CTG-Insight: A Multi-Agent Interpretable LLM Framework for Cardiotocography Analysis and Classification | 五医学定义特征各由专用Agent分析+聚合Agent综合输出 | 远程胎儿监测系统缺乏可解释性父母难理解CTG数据 | 胎儿健康监测、心脏描记图分析 |
| 79 | http://arxiv.org/abs/2508.03728v1 | WINELL: Wikipedia Never-Ending Updating with LLM Agents | 多 agent 框架持续聚合在线信息 | 解决维基百科内容更新依赖人工问题 | 知识库自动更新 |
| 80 | http://arxiv.org/abs/2507.22504v2 | Collaborative Medical Triage under Uncertainty: A Multi-Agent Dynamic Matching Approach | 三 agent 协作动态匹配机制 | 解决现有 AI 分诊专业化不足与效率低问题 | 医疗分诊系统 |
| 81 | http://arxiv.org/abs/2507.22758v1 | MASCA: LLM based-Multi Agents System for Credit Assessment | 分层架构镜像现实信贷决策过程 | 解决传统信贷评估依赖规则与统计模型问题 | 金融信用评估 |
| 82 | http://arxiv.org/abs/2507.22800v1 | The Multi-Agent Fault Localization System Based on Monte Carlo Tree Search Approach | 基于 MCTS 与知识库奖励机制 | 解决 LLM 幻觉与异常信息传播导致定位错误 | 微服务根因分析 |
| 83 | http://arxiv.org/abs/2507.22827v2 | ScreenCoder: Advancing Visual-to-Code Generation for Front-End Automation via Modular Multimodal Agents | 模块化多 agent 分解 grounding 规划生成 | 解决单模型处理复杂 UI 感知规划错误问题 | 前端自动化开发 |
| 84 | http://arxiv.org/abs/2507.23095v2 | SMART-Editor: A Multi-Agent Framework for Human-Like Design Editing with Structural Integrity | 奖励引导细化与偏好优化策略 | 解决局部编辑破坏全局连贯性问题 | 结构化与非结构化设计编辑 |
| 85 | http://arxiv.org/abs/2507.23370v1 | Trae Agent: An LLM-based Agent for Software Engineering with Test-time Scaling | 基于集成推理的仓库级 issue 解决 agent | 解决提示方法探索空间大与仓库理解不足问题 | 软件工程问题修复 |
| 86 | http://arxiv.org/abs/2507.23693v1 | CFDagent: A Language-Guided, Zero-Shot Multi-Agent System for Complex Flow Simulation | 零样本多 agent 系统自主 CFD 仿真 | 降低专家级 CFD 仿真门槛 | 教育与工程流仿真 |
| 87 | http://arxiv.org/abs/2508.00083v2 | A Survey on Code Generation with LLM-based Agents | 系统 survey LLM 代码生成 agent 领域 | 梳理技术轨迹核心技巧与应用基准 | 软件开发生命周期 |
| 88 | http://arxiv.org/abs/2507.15676v1 | Agentic AI for autonomous anomaly management in complex systems | 探索Agentic AI自主检测响应复杂系统异常的能力 | 传统异常管理依赖人工，效率低且响应慢 | 复杂系统异常管理 |
| 89 | http://arxiv.org/abs/2507.16203v1 | SVAgent: AI Agent for Hardware Security Verification Assertion | 需求分解机制将复杂需求转化为结构化可解的细粒度问题链 | SystemVerilog断言开发效率低，无法应对现代电路安全漏洞 | 集成电路安全验证 |
| 90 | http://arxiv.org/abs/2507.16229v1 | Voice-based AI Agents: Filling the Economic Gaps in Digital Health Delivery | LLM语音助手增强预防性护理和持续患者监测的经济模型 | 医疗资源不足人群难以获得持续健康监测服务 | 数字健康服务交付 |
| 91 | http://arxiv.org/abs/2507.16940v1 | AURA: A Multi-Modal Medical Agent for Understanding, Reasoning & Annotation | 首个视觉语言可解释性Agent，模块化工具箱支持分割、反事实生成和评估 | 基于LLM的Agent系统在医学成像应用仍处于起步阶段 | 医学图像分析 |
| 92 | http://arxiv.org/abs/2507.17012v1 | Towards Autonomous Sustainability Assessment via Multimodal AI Agents | 多模态AI Agent模拟LCA专家与利益相关者交互，迭代生成生命周期清单 | 生命周期评估数据常不可用，专家评估耗时数周至数月 | 电子产品碳足迹评估 |
| 93 | http://arxiv.org/abs/2507.17289v3 | Compliance Brain Assistant: Conversational Agentic AI for Assisting Compliance Tasks in Enterprise Environments | 用户查询路由器智能选择FastTrack或FullAgentic模式，平衡响应质量和延迟 | 企业合规任务效率低，需平衡响应质量与延迟的对话式Agent | 企业合规任务 |
| 94 | http://arxiv.org/abs/2507.05330v1 | MindFlow: Revolutionizing E-commerce Customer Support with Multimodal LLM Agents | 首个开源电商多模态 LLM 智能体，集成记忆与决策模块 | 复杂多模态电商客服场景处理能力不足 | 电商客户服务支持 |
| 95 | http://arxiv.org/abs/2507.05520v3 | Architecting Clinical Collaboration: Multi-Agent Reasoning Systems for Multimodal Medical VQA | 模仿临床推理过程的多智能体架构，结合文献检索 | 远程医疗缺乏上下文，单一模型诊断性能下降 | 皮肤科远程医疗诊断 |
| 96 | http://arxiv.org/abs/2507.05528v2 | Conversational Education at Scale: A Multi-LLM Agent Workflow for Procedural Learning and Pedagogic Quality Assessment | 多智能体工作流模拟教学对话，评估教学质量 | 现有虚拟教育缺乏可扩展性与教学质量评估框架 | 大规模程序性学习与教育 |
| 97 | http://arxiv.org/abs/2507.05755v1 | An autonomous agent for auditing and improving the reliability of clinical AI models | 自反射智能体模拟分布偏移，审计临床 AI 模型可靠性 | 临床 AI 模型在真实世界变异下易失效，审计耗时 | 临床 AI 模型可靠性审计 |
| 98 | http://arxiv.org/abs/2507.06483v2 | Animating Language Practice: Engagement with Stylized Conversational Agents in Japanese Learning | 结合动漫风格角色与 expressive TTS 的语言学习应用 | 学习者练习自然对话缺乏 engagement 与表达性 | 日语学习与应用 |
| 99 | http://arxiv.org/abs/2507.07105v1 | 4KAgent: Agentic Any Image to 4K Super-Resolution | 统一代理超分系统，递归执行 - 反思范式修复图像 | 低分辨率严重退化图像难以恢复至 4K 清晰度 | 图像超分辨率修复 |
| 100 | http://arxiv.org/abs/2507.07257v2 | Open Source Planning & Control System with Language Agents for Autonomous Scientific Discovery | 30 个 LLM 智能体协作完成博士级宇宙学任务 | 科学研究任务自动化程度低，依赖人工介入 | 自主科学发现 (宇宙学) |
| 101 | http://arxiv.org/abs/2507.07426v3 | DrugMCTS: a drug repurposing framework combining multi-agent, RAG and Monte Carlo Tree Search | 结合多智能体、RAG 与 MCTS 的药物重定位框架 | 超出预训练知识的推理受限，结构化数据利用不足 | 药物重定位与发现 |
| 102 | http://arxiv.org/abs/2507.07509v1 | Toward Real-World Chinese Psychological Support Dialogues: CPsDD Dataset and a Co-Evolving Multi-Agent System | 协同进化多智能体系统生成中文心理支持对话 | 非英语心理支持数据集稀缺，缺乏高质量对话数据 | 中文心理咨询支持 |

[返回目录](#目录)

<a id="cat-03"></a>

## Agent架构与框架设计

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2507.03223v1 | SI-Agent: An Agentic Framework for Feedback-Driven Generation and Tuning of Human-Readable System Instructions for Large Language Models | 三Agent协作框架，通过反馈循环自动生成和迭代优化人类可读系统指令 | 手动 crafting 系统指令资源密集且次优，现有方法牺牲可解释性 | LLM系统指令定制 |
| 2 | http://arxiv.org/abs/2507.03311v1 | GRAFT: A Graph-based Flow-aware Agentic Framework for Document-level Machine Translation | 图增强Agent框架，整合分割、DAG依赖建模和话语感知翻译 | 文档级翻译难以捕捉话语现象，难以保持全文一致性 | 文档级机器翻译 |
| 3 | http://arxiv.org/abs/2507.03674v2 | STRUCTSENSE: A Task-Agnostic Agentic Framework for Structured Information Extraction with Human-In-The-Loop Evaluation and Benchmarking | 领域本体引导的模块化框架，含自评估法官反馈循环和人机协同机制 | LLM在专业领域效果下降，跨任务/领域迁移性差 | 结构化信息提取 |
| 4 | http://arxiv.org/abs/2507.04067v1 | HAWK: A Hierarchical Workflow Framework for Multi-Agent Collaboration | 五层十六标准接口，自适应调度优化模块，统一资源抽象 | 跨平台互操作性、动态任务调度、高效资源共享持续挑战 | 多Agent协作系统 |
| 5 | http://arxiv.org/abs/2507.04376v2 | MOD-X: A Modular Open Decentralized eXchange Framework proposal for Heterogeneous Interoperable Artificial Intelligence Agents | 分层架构含通用消息总线/状态管理/翻译能力/区块链安全机制 | 现有协议限制异构Agent互操作性，需去中心化可扩展生态系统 | 异构AI Agent互操作 |
| 6 | http://arxiv.org/abs/2508.00844v1 | Exploring Agentic Artificial Intelligence Systems: Towards a Typological Framework | 八维度类型学框架， ordinal 结构定义认知和环境代理性 | 缺乏结构化框架分类比较AI Agent系统 | Agent系统分类评估 |
| 7 | http://arxiv.org/abs/2507.06261v6 | Gemini 2.5: Pushing the Frontier with Advanced Reasoning, Multimodality, Long Context, and Next Generation Agentic Capabilities | Gemini 2.X模型家族，长上下文+多模态+推理能力解锁新Agent工作流 | 探索复杂Agent问题求解的可能性边界 | 通用Agent能力 |
| 8 | http://arxiv.org/abs/2507.01376v1 | AI Agents and Agentic AI-Navigating a Plethora of Concepts for Future Manufacturing | 系统综述制造领域 LLM 代理与 Agentic AI 概念，澄清定义与挑战 | 制造领域 AI 代理定义与应用 unclear 及能力边界 | 智能制造与未来工厂 |
| 9 | http://arxiv.org/abs/2507.01599v1 | Data Agent: A Holistic Architecture for Orchestrating Data+AI Ecosystems | 编排 Data+AI 生态系统的整体架构，集成知识理解与规划 | 数据管道编排依赖专家及语义理解限制 | 数据科学与 AI 生态系统 |
| 10 | http://arxiv.org/abs/2507.01701v1 | Exploring Advanced LLM Multi-Agent Systems Based on Blackboard Architecture | 将黑板架构融入 LLM 多代理系统共享信息，基于内容选择 Agent | 复杂动态问题求解结构缺失及 token 消耗高 | 常识推理与数学问题解决 |
| 11 | http://arxiv.org/abs/2507.02097v2 | The Future is Agentic: Definitions, Perspectives, and Open Challenges of Multi-Agent Recommender Systems | 统一形式化多代理推荐系统架构与挑战，提出蓝图与议程 | 推荐系统设计空间 transform 及新自主Degree 治理 | 多代理推荐系统 |
| 12 | http://arxiv.org/abs/2508.00007v1 | Agent Network Protocol Technical White Paper | 提出三层协议系统，解决智能体身份认证与动态协商 | 现有互联网基础设施不支持大规模智能体互联协作 | 通用智能体网络互联 |
| 13 | http://arxiv.org/abs/2507.14263v1 | Beyond DNS: Unlocking the Internet of AI Agents via the NANDA Index and Verified AgentFacts | 提出 NANDA 索引架构，支持动态可验证 AgentFacts 解析 | 现有 DNS 中心身份发现无法支撑海量自主智能体负载 | 人工智能体互联网基础设施 |
| 14 | http://arxiv.org/abs/2507.14633v1 | Agentic Satellite-Augmented Low-Altitude Economy and Terrestrial Networks: A Survey on Generative Approaches | 系统综述生成式 AI 赋能智能体在卫星增强网络中的应用 | 异构动态环境中需智能自主系统可靠运行 | 卫星增强低空经济与地面网络 |
| 15 | http://arxiv.org/abs/2507.10644v3 | From Semantic Web and MAS to Agentic AI: A Unified Narrative... | 提出四轴分类法，统一分析代理架构的演化历程。 | 解决 Web of Agents 研究碎片化，缺乏 holistic 理解的问题。 | 智能体网络架构演进 |
| 16 | http://arxiv.org/abs/2507.11117v1 | AI Agent Architecture for Decentralized Trading of Alternative Assets | 提出 GoldMine OS 架构，结合链上合约与链下 AI 代理。 | 解决实物资产代币化交易中的合规、流动性与风险管理。 | 去中心化资产交易 |
| 17 | http://arxiv.org/abs/2507.11277v2 | Taming Uncertainty via Automation: Observing, Analyzing... | 提出 AgentOps 框架，涵盖观察、分析、优化和自动化运行。 | 解决代理系统中不确定性管理及传统运维实践不足的问题。 | 代理系统运维 (AgentOps) |
| 18 | http://arxiv.org/abs/2507.11633v1 | General Modular Harness for LLM Agents in Multi-Turn Gaming... | 引入模块化 harness 设计，组合感知、记忆和推理组件。 | 解决 LLM 代理在多回合游戏环境中需特定领域工程的问题。 | 通用游戏代理 |
| 19 | http://arxiv.org/abs/2507.11988v2 | Aime: Towards Fully-Autonomous Multi-Agent Framework | 提出 Aime 框架，具有动态规划器、演员工厂和进度管理模块。 | 解决现有 MAS 计划执行僵化、代理能力静态的问题。 | 通用多智能体协作 |
| 20 | http://arxiv.org/abs/2507.13175v2 | iReDev: A Knowledge-Driven Multi-Agent Framework... | 提出知识驱动多代理框架，集成人类知识与事件驱动通信。 | 解决需求开发中人类知识注入不足与人机协作支持缺乏。 | 软件需求工程 |
| 21 | http://arxiv.org/abs/2507.07901v3 | The Trust Fabric: Decentralized Interoperability and Economic Coordination for the Agentic Web | 去中心化框架，集成 DID 发现、语义卡片与动态信任层 | AI 智能体生态系统碎片化，缺乏互操作性与信任 | 去中心化智能体网络 |
| 22 | http://arxiv.org/abs/2507.08164v1 | KP-A: A Unified Network Knowledge Plane for Catalyzing Agentic Network Intelligence | 统一网络知识平面，解耦知识获取与智能逻辑 | 独立智能任务导致数据流冗余与解释不一致 | 6G 网络智能管理 |
| 23 | http://arxiv.org/abs/2507.08944v1 | Optimizing Sequential Multi-Step Tasks with Parallel LLM Agents | 并行运行多智能体团队，利用事件驱动通信减少延迟 | 多步任务推理循环导致的高延迟问题 | 复杂任务推理 |
| 24 | http://arxiv.org/abs/2507.09477v2 | Towards Agentic RAG with Deep Reasoning: A Survey of RAG-Reasoning Systems in LLMs | 统一推理与检索视角，综述协同框架 | RAG 事实性与推理能力不足的问题 | RAG 系统研究 |
| 25 | http://arxiv.org/abs/2507.09497v2 | GoalfyMax: A Protocol-Driven Multi-Agent System for Intelligent Experience Entities | 协议驱动框架，标准化 A2A 通信与经验包架构 | 传统单目的 AI 系统缺乏协调、记忆复用与任务分解 | 企业智能系统 |
| 26 | http://arxiv.org/abs/2508.02694v1 | Efficient Agents: Building Effective Agents While Reducing Cost | 研究效率 - 效果权衡，提出 Efficient Agents 框架 | 代理系统成本 escalating 威胁可扩展性 | 通用 Agent 系统 |
| 27 | http://arxiv.org/abs/2507.19635v1 | Efficient and Scalable Agentic AI with Heterogeneous Systems | 异构计算基础设施上动态编排 AI Agent 工作负载 | Agent 工作负载动态复杂，需高效部署 | 企业 AI Agent 部署 |
| 28 | http://arxiv.org/abs/2507.19902v1 | AgentMesh: A Cooperative Multi-Agent Generative AI Framework for Software Development Automation | AgentMesh 框架，多 Agent 协作自动化软件开发 | 软件开发复杂，需 diverse  expertise 协作 | 软件开发自动化 |
| 29 | http://arxiv.org/abs/2508.00890v2 | AgentTTS: Large Language Model Agent for Test-time Compute-optimal Scaling Strategy in Complex Tasks | AgentTTS 框架，自主搜索多阶段任务 compute-optimal 分配 | 多阶段任务 TTS 组合搜索空间大且成本高 | 复杂任务 LLM 推理 |
| 30 | http://arxiv.org/abs/2507.20534v2 | Kimi K2: Open Agentic Intelligence | MoE架构32B激活参数，MuonClip优化器，多阶段后训练 | 开源模型在Agent任务上性能不足 | 软件工程、编码、数学推理任务 |
| 31 | http://arxiv.org/abs/2507.21206v1 | Agentic Web: Weaving the Next Web with AI Agents | 提出智能、交互、经济三维度概念模型理解Agentic Web | 从人类驱动到机器对机器交互的范式转变 | 下一代互联网、自主Agent生态系统 |
| 32 | http://arxiv.org/abs/2507.21407v2 | Graph-Augmented Large Language Model Agents: Current Progress and Future Prospects | 综述图如何增强LLM Agent的规划、记忆、工具管理 | 研究快速增长且碎片化需系统 overview | 图增强LLM Agent研究与应用 |
| 33 | http://arxiv.org/abs/2507.21696v4 | Edge Agentic AI Framework for Autonomous Network Optimisation in O-RAN | 基于角色的多工具架构+主动异常检测+安全对齐奖励机制 | 传统RAN基础设施部署AI Agent的安全可靠性挑战 | 5G/6G开放无线网络优化 |
| 34 | http://arxiv.org/abs/2507.21823v1 | An Agentic AI for a New Paradigm in Business Process Development | 基于目标/对象/Agent组织业务流程而非传统任务方法 | 传统任务方法在动态工业环境中灵活性不足 | 工业自动化业务流程开发 |
| 35 | http://arxiv.org/abs/2507.22606v1 | MetaAgent: Automatically Constructing Multi-Agent Systems Based on Finite State Machines | 基于有限状态机自动生成多 agent 系统 | 解决自动设计方法缺乏工具集成与刚性问题 | 通用多 agent 任务 |
| 36 | http://arxiv.org/abs/2507.23773v2 | SimuRA: A World-Model-Driven Simulative Reasoning Architecture for General Goal-Oriented Agents | 引入世界模型进行模拟规划架构 | 解决黑盒自回归推理缺乏显式模拟问题 | 通用目标导向 agent |
| 37 | http://arxiv.org/abs/2507.15761v1 | GasAgent: A Multi-Agent Framework for Automated Gas Optimization in Smart Contracts | 四Agent协作闭环框架，兼容现有模式并自动发现验证新模式 | 智能合约Gas优化依赖人工发现，效率低难扩展 | 区块链智能合约优化 |
| 38 | http://arxiv.org/abs/2507.17061v5 | Parallelism Meets Adaptiveness: Scalable Documents Understanding in Multi-Agent LLM Systems | 动态任务路由、双向反馈和并行Agent评估三机制实现适应性 | 现有框架依赖静态工作流和固定角色，开放高复杂度领域效果差 | 多Agent LLM文档理解 |
| 39 | http://arxiv.org/abs/2507.17695v2 | Symbiotic Agents: A Novel Paradigm for Trustworthy AGI-driven Networks | 共生Agent范式结合LLM与实时优化算法，输入输出级优化器协同 | LLM基于Agent决策错误率高，需可信赖AGI驱动网络 | 6G网络管理和服务配置 |
| 40 | http://arxiv.org/abs/2507.19543v1 | Agent WARPP: Workflow Adherence via Runtime Parallel Personalization | 并行架构中Personalizer Agent与领域特定Agent协同，运行时动态定制执行路径 | LLM在长条件工作流中难以遵循，涉及外部工具调用和用户特定信息 | 任务导向对话系统 |
| 41 | http://arxiv.org/abs/2507.21105v2 | AgentMaster: A Multi-Agent Conversational Framework Using A2A and MCP Protocols for Multimodal Information Retrieval and Analysis | 首次在同一框架内整合 A2A 与 MCP 协议的多智能体系统 | 多智能体间通信协调及异构工具交互挑战 | 多模态信息检索与分析 |
| 42 | http://arxiv.org/abs/2507.06396v1 | Representing Prompting Patterns with PDL: Compliance Agent Case Study | 提示声明语言 (PDL) 抽象提示模式，支持手动与自动调优 | 提示工程复杂，现有框架隐藏复杂性或灵活性不足 | 合规智能体提示工程 |
| 43 | http://arxiv.org/abs/2507.06520v1 | Gradientsys: A Multi-Agent LLM Scheduler with ReAct Orchestration | 基于 ReAct 的动态规划循环，协调异构 AI 智能体 | 多智能体调度缺乏透明性，失败处理与并行执行难 | 多智能体任务编排与调度 |
| 44 | http://arxiv.org/abs/2507.10571v3 | Agentic AI with Orchestrator-Agent Trust: A Modular Visual Classification Framework with Trust-Aware Orchestration and RAG-Based Reasoning | 信任感知编排器分离感知与元推理，结合 RAG | 零 shot 设置下多智能体系统缺乏信任与可解释性 | 视觉分类与诊断 (如苹果叶病) |
| 45 | http://arxiv.org/abs/2507.07400v1 | KVFlow: Efficient Prefix Caching for Accelerating LLM-Based Multi-Agent Workflows | 工作流感知的 KV 缓存管理，预测未来智能体使用 | 现有 LRU 策略导致频繁缓存缺失与重计算 | LLM 多智能体工作流加速 |

[返回目录](#目录)

<a id="cat-04"></a>

## 多Agent协作与通信

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2507.03254v1 | CodeAgents: A Token-Efficient Framework for Codified Multi-Agent Reasoning in LLMs | 将多Agent推理编码为模块化伪代码，含控制结构和类型变量 | 现有提示策略限于单Agent，忽视令牌效率和多Agent可扩展性 | 多Agent任务规划系统 |
| 2 | http://arxiv.org/abs/2507.03326v1 | Mirror in the Model: Ad Banner Image Generation via Reflective Multi-LLM and Multi-modal Agents | 分层多模态Agent系统+协调循环，探索多风格方向并迭代改进 | 商业广告设计需结构化布局、精确排版、一致品牌，超越视觉保真度 | 广告横幅自动生成 |
| 3 | http://arxiv.org/abs/2507.03928v1 | CortexDebate: Debating Sparsely and Equally for Multi-Agent Debate | 稀疏辩论图+McKinsey辩论物质模块优化图，Agent仅与有益者辩论 | 输入上下文过长导致迷失，过度自信Agent主导辩论降低效果 | 多Agent辩论系统 |
| 4 | http://arxiv.org/abs/2507.04410v1 | Multimedia Verification Through Multi-Agent Deep Research Multimodal Large Language Models | 六阶段多Agent验证系统，Deep Researcher Agent用四工具检测多媒体虚假信息 | 多媒体虚假信息检测需结合MLLM与专业验证工具 | 多媒体内容验证 |
| 5 | http://arxiv.org/abs/2507.02002v4 | Dynamic Strategy Adaptation in Multi-Agent Environments with Large Language Models | 结合博弈论与实时反馈的多 Agent 动态策略适应，提升协作效率 | 动态多 Agent 环境协作效率及实时适应性问题 | cooperative 游戏与动态场景 |
| 6 | http://arxiv.org/abs/2507.02170v1 | Synergizing Logical Reasoning, Knowledge Management and Collaboration in Multi-Agent LLM System | 集成逻辑推理、知识管理与协作的多代理系统，优化通信协议 | 复杂现实挑战的团队问题解决及长期知识保留 | 产品开发团队与协作 |
| 7 | http://arxiv.org/abs/2507.13511v1 | GraphTrafficGPT: Enhancing Traffic Management Through Graph-Based AI Agent Coordination | 提出基于图的架构，实现任务并行执行与动态资源分配 | 解决链式系统任务执行顺序依赖高、扩展性差的问题 | 城市交通管理与调度 |
| 8 | http://arxiv.org/abs/2507.14928v1 | Byzantine-Robust Decentralized Coordination of LLM Agents | 去中心化共识方法，Worker 生成答案 Evaluator 评分选择最佳 | 现有 Leader-driven 协调易受攻击且可能接受低质量提案 | 开放区块链平台多 Agent 协作 |
| 9 | http://arxiv.org/abs/2507.09997v2 | Predictive & Trust-based Multi-Agent Coordination | 提出基于信任的预测多智能体共识协议，分析邻居预期数据。 | 解决多智能体网络中的协调决策与信任学习问题。 | 多智能体网络协调 |
| 10 | http://arxiv.org/abs/2507.14200v1 | Open-Source LLMs Collaboration Beats Closed-Source LLMs... | 提出 SMACS 框架，通过检索优先选择和后验增强协作。 | 解决开源 LLM 协作性能不及闭源模型的问题。 | 开源大模型协作系统 |
| 11 | http://arxiv.org/abs/2507.11198v1 | Temperature and Persona Shape LLM Agent Consensus... | 实验研究代理角色和温度如何影响定性编码中的共识构建。 | 解决多智能体系统在定性研究 coding 中的一致性难题。 | 定性研究数据标注 |
| 12 | http://arxiv.org/abs/2507.13491v1 | Multi-Agent Synergy-Driven Iterative Visual Narrative Synthesis | 提出 RCPS 框架，集成叙事规划、布局生成与迭代优化。 | 解决自动媒体演示生成中的逻辑不一致与布局次优问题。 | 视觉叙事合成 |
| 13 | http://arxiv.org/abs/2507.08350v1 | Exploring Design of Multi-Agent LLM Dialogues for Research Ideation | 分析多智能体对话配置对科研构思新颖性的影响 | 多智能体协作生成科研想法的最优交互设计不明 | 科研构思辅助 |
| 14 | http://arxiv.org/abs/2507.08440v1 | Finding Common Ground: Using Large Language Models to Detect Agreement in Multi-Agent Decision Conferences | 多智能体系统模拟决策会议，检测参与者共识 | 复杂议题决策会议依赖人工引导，效率较低 | 决策会议模拟 |
| 15 | http://arxiv.org/abs/2507.08960v1 | How to Train a Leader: Hierarchical Reasoning in Multi-Agent LLMs | 分层框架训练单一领导者协调未训练的对等智能体 | 多智能体框架训练与推理计算成本高 | 多智能体协作推理 |
| 16 | http://arxiv.org/abs/2507.18224v4 | Assemble Your Crew: Automatic Multi-agent Communication Topology Design via Autoregressive Graph Generation | ARG-Designer，自回归图生成设计协作拓扑 | 现有方法依赖模板，适应性有限 | 多智能体系统拓扑设计 |
| 17 | http://arxiv.org/abs/2507.18572v1 | PosterMate: Audience-driven Collaborative Persona Agents for Poster Design | 创建受众驱动 persona Agent 收集反馈 | 设计编辑中收集多样视角困难 | 海报设计协作 |
| 18 | http://arxiv.org/abs/2507.19550v1 | Towards Multi-Agent Economies: Enhancing the A2A Protocol with Ledger-Anchored Identities and x402 Micropayments for AI Agents | 集成 DLT 与 x402 标准，实现 Agent 发现与微支付 | A2A 协议缺乏去中心化发现与微支付 | 多 Agent 经济系统 |
| 19 | http://arxiv.org/abs/2507.21159v2 | MAC: Masked Agent Collaboration Boosts Large Language Model Medical Decision-Making | MAC 框架，Pareto 最优 Agent 构建与交叉一致性最大化 | 当前 MAS 协作模式僵硬易失败 | 医疗决策 |
| 20 | http://arxiv.org/abs/2507.19049v1 | Heterogeneous Risk Management Using a Multi-Agent Framework for Supply Chain Disruption Response | 异构风险管理机制，纳入不确定性与风险态度 | 现有工作忽略时间动态与个体异构性 | 供应链中断响应 |
| 21 | http://arxiv.org/abs/2507.19090v3 | Debating Truth: Debate-driven Claim Verification with Multiple Large Language Model Agents | DebateCV 框架，Debater 辩论与 Moderator 裁决 | 单 Agent 验证复杂 claim 困难 | 事实核查 claim 验证 |
| 22 | http://arxiv.org/abs/2507.19354v1 | EffiComm: Bandwidth Efficient Multi Agent Communication | EffiComm 框架，两阶段减少传输数据量 | 协作感知传输原始点云 overwhelms 通信 | 车联网协作感知 |
| 23 | http://arxiv.org/abs/2507.19593v2 | A Survey on Hypergame Theory: Modeling Misaligned Perceptions and Nested Beliefs for Multi-agent Systems | 系统 review 超博弈理论在 MAS 中的应用 | 经典博弈论假设在现实 MAS 中常 violated | 多智能体系统建模 |
| 24 | http://arxiv.org/abs/2507.19694v1 | Ultracoarse Equilibria and Ordinal-Folding Dynamics in Operator-Algebraic Models of Infinite Multi-Agent Games | 算子代数框架，证明 regret 学习动态收敛 | 无限 Agent 博弈缺乏严谨数学基础 | 大规模多 Agent 系统 |
| 25 | http://arxiv.org/abs/2507.20145v1 | Multi-Agent Interactive Question Generation Framework for Long Document Understanding | 全自动化多Agent交互框架生成长文档问题 | 长上下文文档理解缺乏细粒度训练数据 | 英语和阿拉伯语长文档理解 |
| 26 | http://arxiv.org/abs/2507.20250v1 | A Truthful Mechanism Design for Distributed Optimisation Algorithms in Networks with Self-interested Agents | 设计真实机制激励自利Agent忠实参与算法 | 自利Agent恶意操纵分布式优化算法 | 网络中的分布式优化系统 |
| 27 | http://arxiv.org/abs/2507.20370v1 | Advancing Shared and Multi-Agent Autonomy in Underwater Missions: Integrating Knowledge Graphs and Retrieval-Augmented Generation | RAG+知识图谱实现多Agent自主决策与人机交互 | 水下环境复杂动态挑战自主性与操作员信任 | 水下基础设施检查、环境监测 |
| 28 | http://arxiv.org/abs/2507.20536v2 | T2I-Copilot: A Training-Free Multi-Agent Text-to-Image System for Enhanced Prompt Interpretation and Interactive Generation | 三Agent协作自动提示工程、模型选择、迭代优化 | 文生图模型对提示措辞敏感需多次 refinement | 文本到图像生成 |
| 29 | http://arxiv.org/abs/2507.21454v1 | Transmission With Machine Language Tokens: A Paradigm for Task-Oriented Agent Communication | 学习机器语言token表示+联合token信道编码压缩 | 现有LLM输出人类语言对Agent通信次优 | 面向任务的Agent通信系统 |
| 30 | http://arxiv.org/abs/2507.21969v1 | Towards Cognitive Synergy in LLM-Based Multi-Agent Systems: Integrating Theory of Mind and Critical Evaluation | 整合自适应心智理论和系统批判性评估实现认知协同 | 当前人工系统缺乏高阶认知限制适应性协作 | LLM多Agent系统复杂决策 |
| 31 | http://arxiv.org/abs/2507.22282v1 | Multi-Agent Path Finding Among Dynamic Uncontrollable Agents with Statistical Safety Guarantees | 结合 conformal prediction 的 ECBS 变体 | 解决不可控 agent 的不确定行为安全问题 | 动态环境路径规划 |
| 32 | http://arxiv.org/abs/2508.00032v2 | Strategic Communication and Language Bias in Multi-Agent LLM Coordination | 模拟不同语言下 agent 沟通与博弈 | 揭示沟通对协调与偏见强化的双重作用 | 多 agent 协调场景 |
| 33 | http://arxiv.org/abs/2507.23261v2 | DynaSwarm: Dynamically Graph Structure Selection for LLM-based Multi-agent System | 动态选择最优图结构的框架 | 解决静态协作图结构限制适应性与性能问题 | 问答推理与编码任务 |
| 34 | http://arxiv.org/abs/2507.23348v1 | SWE-Debate: Competitive Multi-Agent Debate for Software Issue Resolution | 竞争性多 agent 辩论框架 | 解决独立探索易陷局部解与跨代码库模式识别问题 | 软件问题修复 |
| 35 | http://arxiv.org/abs/2507.23565v3 | Semantic Chain-of-Trust: Autonomous Trust Orchestration for Collaborator Selection via Hypergraph-Aided Agentic AI | 语义信任链与超图辅助 agent 选择 | 解决动态环境下协作设备信任评估挑战 | 分布式协作系统 |
| 36 | http://arxiv.org/abs/2507.15727v2 | Competitive Algorithms for Multi-Agent Ski-Rental Problems | 将经典滑雪租赁问题推广到多Agent群体，设计状态感知阈值策略 | 群体决策中个体与共享成本的动态平衡问题 | 不确定性下的群体决策 |
| 37 | http://arxiv.org/abs/2507.16306v2 | COMPASS: Cooperative Multi-Agent Persistent Monitoring using Spatio-Temporal Attention Network | 共享时空注意力网络整合历史观测和空间上下文，高斯过程建模目标动态 | 动态目标持续监控中移动Agent需在不确定性下持续收集信息 | 灾害响应、环境监测、野生动物保护 |
| 38 | http://arxiv.org/abs/2507.16874v2 | Budget Allocation Policies for Real-Time Multi-Agent Path Finding | 探索窗口化MAPF中规划预算分配策略，智能分配预算给各Agent | 实时MAPF中共享预算池方法在挑战性场景中效果差 | 自动化仓库、无人机群 |
| 39 | http://arxiv.org/abs/2507.17054v1 | New Mechanisms in Flex Distribution for Bounded Suboptimal Multi-Agent Path Finding | 提出基于冲突和延迟的灵活分配机制，混合策略分层框架 | 现有灵活分配可能使总路径成本超出边界，降低效率 | 多Agent路径规划 |
| 40 | http://arxiv.org/abs/2507.17134v1 | Resilient Multi-Agent Negotiation for Medical Supply Chains:Integrating LLMs and Blockchain for Transparent Coordination | LLM驱动多Agent协商与区块链集成，链下自适应推理，链上不可变执行 | 传统医疗供应链资源分配效率低、缺乏透明度、适应性差 | 医疗供应链危机协调 |
| 41 | http://arxiv.org/abs/2507.17152v1 | JAM: Keypoint-Guided Joint Prediction after Classification-Aware Marginal Proposal for Multi-Agent Interaction | 两阶段多Agent交互预测框架，关键路点引导联合预测模块捕捉关键信息 | 多Agent联合预测中低概率模式生成质量低 | 自动驾驶道路参与者运动预测 |
| 42 | http://arxiv.org/abs/2507.17875v1 | Trusted Data Fusion, Multi-Agent Autonomy, Autonomous Vehicles | 基于HMM的分散式信任框架估计Agent和信息可信度，信任感知数据融合 | 临时UAV网络分散性质面临安全挑战，易受网络物理攻击 | 情报监视侦察任务 |
| 43 | http://arxiv.org/abs/2507.05981v1 | Multi-Agent Debate Strategies to Enhance Requirements Engineering with Large Language Models | 将多智能体辩论策略应用于需求工程分类任务 | 单一模型输出缺乏迭代 refinement，鲁棒性有限 | 软件需求工程任务 |
| 44 | http://arxiv.org/abs/2507.06506v1 | Pun Intended: Multi-Agent Translation of Wordplay with Contrastive Learning and Phonetic-Semantic Embeddings | 多智能体生成 - 判别框架翻译双关语，结合语音语义嵌入 | 机器翻译难以处理双关语的 linguistic creativity | 英语到法语双关语翻译 |

[返回目录](#目录)

<a id="cat-05"></a>

## 具身智能Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2507.03293v2 | LogicGuard: Improving Embodied LLM agents through Temporal Logic based Critics | Actor-Critic架构，Critic通过线性时序逻辑分析轨迹并生成约束 | 长视野任务中LLM错误累积，导致不可靠或低效行为 | 具身机器人规划任务 |
| 2 | http://arxiv.org/abs/2507.03730v1 | Less is More: Empowering GUI Agent with Context-Aware Simplification | 上下文感知简化框架，掩码元素剪枝+一致性引导历史压缩 | 纯视觉GUI Agent忽视上下文建模挑战，元素/历史信息冗余 | GUI导航Agent |
| 3 | http://arxiv.org/abs/2507.04263v1 | SRefiner: Soft-Braid Attention for Multi-Agent Trajectory Refinement | Soft-Braid Attention捕获轨迹时空拓扑关系，多迭代多Agent框架 | 现有细化方法忽视轨迹间拓扑关系，影响预测精度 | 自动驾驶轨迹预测 |
| 4 | http://arxiv.org/abs/2507.04634v1 | LTMSformer: A Local Trend-Aware Attention and Motion State Encoding Transformer for Multi-Agent Trajectory Prediction | 局部趋势感知注意力+运动状态编码器，轻量提案细化模块 | 建模Agent间复杂时空依赖困难，局部时间依赖常被忽视 | 自动驾驶轨迹预测 |
| 5 | http://arxiv.org/abs/2507.04762v2 | Robustifying 3D Perception via Least-Squares Graphs for Multi-Agent Object Tracking | 最小二乘图工具融合多车检测，两阶段跟踪抑制对抗威胁 | 单Agent跟踪缺乏情境感知，需多Agent协作增强鲁棒性 | 自动驾驶3D感知 |
| 6 | http://arxiv.org/abs/2507.04996v9 | Agentic Vehicles for Human-Centered Mobility: Definition, Prospects, and System Implications | 提出代理车辆(AgVs)概念，具备目标驱动推理/战略适应/自我反思能力 | 技术自主性与人类中心移动所需认知社会能力之间存在差距 | 未来交通系统 |
| 7 | http://arxiv.org/abs/2507.01378v2 | RALLY: Role-Adaptive LLM-Driven Yoked Navigation for Agentic UAV Swarms | 角色自适应 LLM 驱动 UAV 集群导航算法，集成离线先验与在线策略 | UAV 集群语义沟通 gap 及角色刚性导致泛化差 | 无人机集群协同导航 |
| 8 | http://arxiv.org/abs/2507.01485v1 | BioMARS: A Multi-Agent Robotic System for Autonomous Biological Experiments | 集成 LLM/VLM 与机器人的多代理生物实验系统，分层架构 | 生物实验协议 rigid 及操作复杂与错误处理不足 | 自主生物实验与实验室自动化 |
| 9 | http://arxiv.org/abs/2507.07115v1 | Autonomous Control Leveraging LLMs: An Agentic Framework for Next-Generation Industrial Automation | 利用 LLM 统一离散故障恢复与连续过程控制，FSM 作为操作包络 | 化工过程复杂及劳动力短缺与 intricate 故障场景 | 工业自动化与过程控制 |
| 10 | http://arxiv.org/abs/2507.13940v1 | NeHMO: Neural Hamilton-Jacobi Reachability Learning for Decentralized Safe Multi-Agent Motion Planning | 神经 HJR 学习建模高维配置空间，去中心化轨迹优化 | 解决多智能体运动规划中集中式扩展性差与安全性 dilemma | 机器人多臂协作与运动规划 |
| 11 | http://arxiv.org/abs/2507.15428v1 | EgoPrune: Efficient Token Pruning for Egomotion Video Reasoning in Embodied Agent | 针对自我运动视频的无训练 token 剪枝，利用时空连续性 | 长冗余视频输入计算成本高，现有剪枝未利用自我运动约束 | 具身智能体自我运动视频推理 |
| 12 | http://arxiv.org/abs/2507.12273v2 | Next-Gen Museum Guides: Autonomous Navigation and Visitor... | 设计 Alter-Ego 机器人，结合 LLM 问答与 SLAM 导航。 | 解决博物馆场景中机器人导航与上下文感知交互问题。 | 博物馆导览机器人 |
| 13 | http://arxiv.org/abs/2507.19742v1 | DOA: A Degeneracy Optimization Agent with Adaptive Pose Compensation Capability based on Deep Reinforcement Learning | 自适应退化优化 Agent，动态调整传感器贡献 | 室内环境如长走廊导致 SLAM 退化 | 室内定位 SLAM |
| 14 | http://arxiv.org/abs/2507.19817v1 | Ag2x2: Robust Agent-Agnostic Visual Representations for Zero-Shot Bimanual Manipulation | Ag2x2 框架，协调感知视觉表示学习双手操作 | 双手操作复杂，现有方法忽略 Agent 特定信息 | 机器人双手操作 |
| 15 | http://arxiv.org/abs/2507.19854v3 | Think, Act, Learn: A Framework for Autonomous Robotic Agents using Closed-Loop Large Language Models | T-A-L 框架，闭环 cycle 实现自主学习与 refinement | 当前系统 open-loop，无法适应动态环境 | 自主机器人 Agent |
| 16 | http://arxiv.org/abs/2507.20293v2 | Decentralized Uncertainty-Aware Multi-Agent Collision Avoidance with Model Predictive Path Integral | 整合MPPI与概率ORCA，二阶锥规划保证安全 | 不确定性下多Agent导航碰撞避免 | 差速驱动机器人、密集环境导航 |
| 17 | http://arxiv.org/abs/2507.20776v2 | RingMo-Agent: A Unified Remote Sensing Foundation Model for Multi-Platform and Multi-Modal Reasoning | 多模态自适应表示，任务特定token统一建模 | 遥感多源数据异构限制统一框架处理 | 卫星和无人机遥感图像理解 |
| 18 | http://arxiv.org/abs/2507.22025v3 | UI-AGILE: Advancing GUI Agents with Effective Reinforcement Learning and Precise Inference-Time Grounding | 连续奖励函数+简单思考奖励+裁剪重采样+分解定位 | GUI Agent训练推理存在推理设计困境、奖励无效、视觉噪声 | 图形用户界面Agent |
| 19 | http://arxiv.org/abs/2507.23698v1 | Scalable Multi-Task Reinforcement Learning for Generalizable Spatial Intelligence in Visuomotor Agents | 跨视角目标规范与自动任务合成 | 解决 RL 模型过fit 特定任务 hindering 泛化问题 | 3D 世界视动 agent |
| 20 | http://arxiv.org/abs/2507.23735v2 | Distributed AI Agents for Cognitive Underwater Robot Autonomy | 分布式 LLM agent 集成于 ROS 2 框架 | 解决复杂不可预测环境下机器人认知自主挑战 | 水下机器人自主 |
| 21 | http://arxiv.org/abs/2507.16941v1 | Multi-agent Reinforcement Learning for Robotized Coral Reef Sample Collection | 结合游戏引擎仿真、深度RL和实时水下运动捕捉的零样本sim-to-real策略 | 珊瑚礁样本采集任务数据收集成本高，高质量数据稀缺 | 水下机器人珊瑚采样 |
| 22 | http://arxiv.org/abs/2507.17462v1 | ERMV: Editing 4D Robotic Multi-view images to enhance embodied agents | 基于单帧编辑和机器人状态条件高效编辑整个多视角序列的数据增强框架 | 4D多视角序列数据收集成本高，高质量数据稀缺限制具身智能泛化 | 机器人模仿学习 |
| 23 | http://arxiv.org/abs/2507.06016v1 | Conditional Multi-Stage Failure Recovery for Embodied Agents | 条件多阶段故障恢复框架，利用零样本链式提示 | 具身智能体执行复杂任务时易失败且难恢复 | 具身智能体任务执行 |
| 24 | http://arxiv.org/abs/2507.06605v2 | Growing Trees with an Agent: Accelerating RRTs with Learned, Multi-Step Episodic Exploration | 用 DRL 智能体生成探索 episode 替代随机采样加速 RRT | 传统采样规划器在高维空间效率低，碰撞检查昂贵 | 机器人运动规划 (RRT) |

[返回目录](#目录)

<a id="cat-06"></a>

## Agent规划与推理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2507.03671v1 | Recon, Answer, Verify: Agents in Search of Truth | 三Agent框架（问题/答案/标签生成器）迭代生成回答子问题验证声明 | 现有事实核查基准包含后分析信息，限制评估真实性 | 自动化事实核查 |
| 2 | http://arxiv.org/abs/2507.03726v1 | Agent-Based Detection and Resolution of Incompleteness and Ambiguity in Interactions with Large Language Models | 零样本ReAct Agent作为转换器，分类/解决/回答三动作自动处理问题缺陷 | 多轮交互冗长，需澄清可通过推理获得的上下文信息 | LLM问答系统 |
| 3 | http://arxiv.org/abs/2507.13768v1 | From Extraction to Synthesis: Entangled Heuristics for Agent-Augmented Strategic Reasoning | 混合架构结合启发式提取与语义激活，融合冲突启发式 | 传统决策引擎无法处理冲突规则与上下文敏感叙事 | 战略推理与决策支持 |
| 4 | http://arxiv.org/abs/2507.14393v1 | Adaptive Multi-Agent Reasoning via Automated Workflow Generation | Nexus Architect 自动生成 tailored 推理工作流，迭代优化提示 | 大型推理模型泛化差，倾向于记忆而非真正推理 | 复杂逻辑问题求解 |
| 5 | http://arxiv.org/abs/2507.14447v2 | Routine: A Structural Planning Framework for LLM Agent System in Enterprise | 结构化规划框架，明确指令与参数传递指导多步工具调用 | 企业环境中模型缺乏领域知识，计划混乱执行不稳定 | 企业级多步任务执行 |
| 6 | http://arxiv.org/abs/2507.10411v1 | Am I on the Right Track? What Can Predicted Query Performance... | 研究查询性能预测在 Agentic RAG 中的适用性。 | 解决 Agentic RAG 中检索器调用时机与查询质量评估问题。 | 检索增强生成系统 |
| 7 | http://arxiv.org/abs/2507.11049v3 | Journalism-Guided Agentic In-Context Learning for News Stance... | 提出 JoA-ICL 框架，代理预测关键段落立场并聚合。 | 解决长新闻文章立场检测及媒体偏见分析问题。 | 新闻推荐与偏见分析 |
| 8 | http://arxiv.org/abs/2507.11222v1 | An Agentic Flow for Finite State Machine Extraction using Prompt... | 提出 FlowFSM 框架，利用提示链从 RFC 文档提取 FSM。 | 解决网络协议 FSM 提取中的可扩展性与歧义问题。 | 网络安全与协议分析 |
| 9 | http://arxiv.org/abs/2507.08664v1 | Introspection of Thought Helps AI Agents | 设计 LLM-Read 代码，实现内部反思减少 Token 成本 | 外部推理框架成本高且受限于 LLM 自然语言理解 | AI 智能体推理优化 |
| 10 | http://arxiv.org/abs/2507.15770v1 | A Framework for Analyzing Abnormal Emergence in Service Ecosystems Through LLM-based Agent Intention Mining | 双视角思维轨道机制提取Agent意图，动态可解释的涌现分析 | 传统因果方法仅关注个体轨迹，无法动态分析群体涌现 | 服务生态系统异常涌现分析 |
| 11 | http://arxiv.org/abs/2507.16507v1 | Agentic RAG with Knowledge Graphs for Complex Multi-Hop Reasoning in Real-World Applications | LLM Agent多工具架构动态参与丰富知识库，支持迭代查询和多跳推理 | 传统RAG在复杂查询上表现有限，难以导航复杂实体关系 | 科学知识探索（INRAE） |
| 12 | http://arxiv.org/abs/2507.17365v2 | DynaSearcher: Dynamic Knowledge Graph Augmented Search Agent via Multi-Reward Reinforcement Learning | 动态知识图谱增强搜索Agent，多奖励RL细粒度控制训练目标 | 多步Agent检索系统生成事实不一致中间查询，搜索轨迹低效 | 复杂信息搜索任务 |
| 13 | http://arxiv.org/abs/2507.17874v1 | I2I-STRADA -- Information to Insights via Structured Reasoning Agent for Data Analysis | 模块化子任务建模分析认知步骤，形式化数据分析推理过程 | 现有系统忽略分析思维的结构化推理过程，推理步骤不遵循固定流程 | 数据分析Agent |
| 14 | http://arxiv.org/abs/2507.05707v2 | Agentic-R1: Distilled Dual-Strategy Reasoning | 蒸馏双策略推理，动态选择文本推理或工具调用 | 长链式推理慢且易错，工具增强代理逻辑任务弱 | 复杂逻辑与计算混合任务 |

[返回目录](#目录)

<a id="cat-07"></a>

## Agent仿真与社会模拟

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2507.03802v1 | Generating Novelty in Open-World Multi-Agent Strategic Board Games | GNOME平台分离Agent开发与模拟器，测试多AgentAI系统面对新颖性 | AI鲁棒性和真实环境中新颖性本质的开放讨论 | 开放世界多Agent游戏 |
| 2 | http://arxiv.org/abs/2507.03904v1 | Agent Exchange: Shaping the Future of AI Agent Economics | Agent Exchange拍卖平台，四生态系统组件支持Agent经济参与 | 实现以Agent为中心的经济，Agent作为主动经济角色交换价值 | AI Agent经济生态系统 |
| 3 | http://arxiv.org/abs/2507.04074v2 | Efficiency through Evolution, A Darwinian Approach to Agent-Based Economic Forecast Modeling | 达尔文Agent建模方法，家庭为主要驱动，企业通过市场自然选择适应 | 传统DSGE和ABM依赖复杂行为规则，需超级计算集群 | 宏观经济预测 |
| 4 | http://arxiv.org/abs/2507.00657v1 | Generative Exaggeration in LLM Social Agents: Consistency, Bias, and Toxicity | 研究 LLM 社交代理在政治话语中的生成夸张现象及内部一致性 | LLM 作为社会代理的可靠性及结构性偏差 | 社交媒体政治话语模拟 |
| 5 | http://arxiv.org/abs/2507.01413v1 | Evaluating LLM Agent Collusion in Double Auctions | 评估双拍卖市场中 LLM 代理的合谋行为及环境影响因素 | 社会经济互动中 Agent  undesirable 行为及伦理考虑 | 模拟市场与经济交互 |
| 6 | http://arxiv.org/abs/2507.02197v1 | Do Role-Playing Agents Practice What They Preach? Belief-Behavior Consistency in LLM-Based Simulations of Human Trust | 评估 LLM 角色扮演代理信念与行为一致性，提出评估框架 | 行为研究中 Agent 输出 coherence 及信念应用不一致 | 人类信任行为模拟研究 |
| 7 | http://arxiv.org/abs/2507.15143v2 | An intelligent agent-based simulation of human mobility in extreme urban morphologies | 混合仿真框架结合 RL 与 GNN，模拟极端城市形态下人类移动 | 评估高密度垂直结构中智能体导航效率与可持续性 | 极端城市形态人类移动仿真 |
| 8 | http://arxiv.org/abs/2507.15518v4 | HAMLET: A Hierarchical and Adaptive Multi-Agent Framework for Live Embodied Theatrics | 分层自适应框架，Actor Agent 具身交互更新全局环境上下文 | 现有戏剧生成缺乏主动性，无法与物理场景交互且沉浸感低 | 交互式叙事与现场戏剧表演 |
| 9 | http://arxiv.org/abs/2507.11660v1 | STAGED: A Multi-Agent Neural Network for Learning Cellular... | 集成 ABM 与深度学习，模拟细胞间通信及基因调控网络。 | 解决空间转录组数据中复杂交互式细胞动力学学习问题。 | 生物细胞动力学模拟 |
| 10 | http://arxiv.org/abs/2507.12494v1 | MR-LDM -- The Merge-Reactive Longitudinal Decision Model... | 提出博弈论模型，模拟高速公路合并场景中的人类驾驶决策。 | 解决自动驾驶仿真中代理行为不够拟人化的问题。 | 自动驾驶仿真 |
| 11 | http://arxiv.org/abs/2507.11979v2 | Value-Based Large Language Model Agent Simulation for Mutual... | 研究价值相似性对 LLM 代理间信任与人际关系建立的影响。 | 解决人工社会中价值如何影响关系建立的机制未探索问题。 | 社会科学研究仿真 |
| 12 | http://arxiv.org/abs/2507.12767v1 | LLM Agent-Based Simulation of Student Activities and Mental Health... | 利用 LLM 代理模拟学生活动与心理健康，基于手机传感数据。 | 解决学生心理健康研究中无法探索新场景与干预研究的问题。 | 学生心理健康研究 |
| 13 | http://arxiv.org/abs/2507.13370v3 | H-NeiFi: Non-Invasive and Consensus-Efficient Multi-Agent Opinion Guidance | 分层非侵入式意见引导框架，优化信息传播路径 | 社交媒体意见引导侵入性强且效率低的问题 | 社交网络治理 |
| 14 | http://arxiv.org/abs/2507.09367v2 | Simulation for All: A Step-by-Step Cookbook for Developing Human-Centered Multi-Agent Transportation Simulators | 以人为本的多智能体交通仿真平台规格说明 | 现有平台缺乏多模态用户参与及无障碍设计 | 交通系统仿真 |
| 15 | http://arxiv.org/abs/2507.09657v1 | Negotiating Comfort: Simulating Personality-Driven LLM Agents in Shared Residential Social Networks | 生成智能体模拟共享住宅社交网络温度决策 | 复杂真人模拟难以设置，需模拟 nuanced 人类行为 | 社会行为模拟 |
| 16 | http://arxiv.org/abs/2507.19364v2 | Integrating LLM in Agent-Based Social Simulation: Opportunities and Challenges | 分析 LLM 在社会模拟中的潜力与局限，提出混合架构 | LLM 驱动模拟的行为保真度与校准挑战 | 基于 Agent 的社会模拟 |
| 17 | http://arxiv.org/abs/2507.19644v1 | Hierarchical clustering and dimensional reduction for optimal control of large-scale agent-based models | 基于 Agent 聚类与 POD 降阶的可扩展控制框架 | 大规模 ABM 维度增加带来计算挑战 | 意见动力学模型控制 |
| 18 | http://arxiv.org/abs/2507.21341v2 | Replicating the behaviour of electric vehicle drivers using an agent-based reinforcement learning model | 多阶段RL框架模拟私人EV司机充电需求 | 现有模拟依赖静态行为规则难以捕捉自适应行为 | 全国道路网络EV充电需求模拟 |
| 19 | http://arxiv.org/abs/2507.21354v1 | Games Agents Play: Towards Transactional Analysis in LLM-based Multi-Agent Systems | Trans-ACT将交易分析三自我状态嵌入Agent认知架构 | 现有MAS框架缺失人类行为的认知复杂性 | 社会交互模拟、冲突解决、教育支持 |
| 20 | http://arxiv.org/abs/2507.21724v1 | Agent-Based Exploration of Recommendation Systems in Misinformation Propagation | 异构Agent（用户/机器人/影响者）模拟推荐算法影响 | 不同推荐算法对 misinformation传播影响不明 | 在线社交网络misinformation传播研究 |
| 21 | http://arxiv.org/abs/2507.22049v1 | Validating Generative Agent-Based Models of Social Norm Enforcement: From Replication to Novel Predictions | 两阶段验证方法用社会困境范式验证生成式Agent模型 | 用LLM模拟人类社会行为验证模型是关键挑战 | 社会规范执行、人类行为仿真 |
| 22 | http://arxiv.org/abs/2507.22435v2 | AI Agents and the Attention Lemons Problem in Two-Sided Ad Markets | 建立 AI 代理 disrupt 广告市场的理论模型 | 解决用户委托浏览造成的负外部性问题 | 数字广告市场 |
| 23 | http://arxiv.org/abs/2507.22467v1 | Towards Simulating Social Influence Dynamics with LLM-based Multi-agents | 结构化框架模拟人类社交动态 | 验证 LLM 多 agent 能否复现社会动力学 | 在线论坛社会模拟 |
| 24 | http://arxiv.org/abs/2507.23344v2 | Designing Dynamic Pricing for Bike-sharing Systems via Differentiable Agent-based Simulation | 可微分 agent 仿真快速设计动态定价 | 解决用户概率选择导致库存不平衡问题 | 共享单车系统 |
| 25 | http://arxiv.org/abs/2507.23644v2 | Agents Trusting Agents? Restoring Lost Capabilities with Inclusive Healthcare | 结合能力框架与贝叶斯逆强化学习 | 解决无家可归者医疗政策评估非侵入性问题 | 医疗包容性政策模拟 |
| 26 | http://arxiv.org/abs/2507.23694v1 | A survey of multi-agent geosimulation methodologies: from ABM to LLM | 确认 LLM 作为 agent 组件的结构化架构 | 提供下一代地理仿真平台形式化规范 | 地理仿真系统 |
| 27 | http://arxiv.org/abs/2507.15815v1 | LLM Economist: Large Population Models and Mechanism Design in Multi-Agent Generative Simulacra | 基于LLM Agent的经济模拟框架，支持异质效用优化和机制设计 | 经济政策实验缺乏可信的大规模人口模拟测试床 | 社会经济政策评估 |
| 28 | http://arxiv.org/abs/2507.05723v1 | Large Language Models for Agent-Based Modelling: Current and possible uses across the modelling cycle | 反思 LLM 在基于代理建模 (ABM) 全周期的机会与挑战 | LLM 用于社会仿真时的抽象性与可解释性矛盾 | 基于代理的社会科学建模 |
| 29 | http://arxiv.org/abs/2507.06310v1 | Too Human to Model:The Uncanny Valley of LLMs in Social Simulation -- When Generative Language Agents Misalign with Modelling Principles | 揭示 LLM 智能体在社会仿真中过于人性化导致的建模困境 | LLM  realism 与建模抽象性、可解释性之间的冲突 | 基于 LLM 的社会仿真研究 |

[返回目录](#目录)

<a id="cat-08"></a>

## Agent记忆与知识管理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2507.10562v1 | SAMEP: A Secure Protocol for Persistent Context Sharing Across AI Agents | 分布式记忆仓库，向量语义搜索+加密访问控制+标准化API | 当前Agent架构记忆短暂，阻碍跨会话/Agent边界协作和知识共享 | 多Agent协作系统 |
| 2 | http://arxiv.org/abs/2507.02259v1 | MemAgent: Reshaping Long-Context LLM with Multi-Conv RL-based Memory Agent | 多卷积 RL 基于记忆代理重塑长上下文 LLM，分段读取更新记忆 | 无限长文档处理性能退化及线性复杂度挑战 | 长文本处理与 QA 任务 |
| 3 | http://arxiv.org/abs/2507.10000v1 | On The Role of Intentionality in Knowledge Representation... | 利用时空相干性评估数据中的潜在意图，作为 Tiny LM。 | 解决认知代理在低计算成本下的意图识别与知识表示。 | 认知智能体 |
| 4 | http://arxiv.org/abs/2507.07957v1 | MIRIX: Multi-Agent Memory System for LLM-Based Agents | 模块化多智能体记忆系统，支持多模态长期记忆 | 现有智能体记忆扁平化，难以个性化与可靠召回 | LLM 智能体记忆增强 |
| 5 | http://arxiv.org/abs/2507.18812v1 | MemoCoder: Automated Function Synthesis using LLM-Supported Agents | 核心修复知识集存储成功修复，支持检索 | LLM 缺乏积累复用过去尝试知识的机制 | 代码功能合成 |
| 6 | http://arxiv.org/abs/2507.20215v1 | MLC-Agent: Cognitive Model based on Memory-Learning Collaboration in LLM Empowered Agent Simulation Environment | 记忆-学习协作机制，分层建模个体/群体记忆库 | Agent模型忽略记忆机制的长期累积效应 | 人工社会建模、复杂系统仿真 |
| 7 | http://arxiv.org/abs/2507.21428v1 | MemTool: Optimizing Short-Term Memory Management for Dynamic Tool Calling in LLM Agent Multi-Turn Conversations | 三架构模式动态管理工具/MCP服务器上下文 | 固定上下文窗口限制多轮交互中重复工具使用 | LLM Agent多轮对话工具调用 |
| 8 | http://arxiv.org/abs/2507.21892v1 | Graph-R1: Towards Agentic GraphRAG Framework via End-to-end Reinforcement Learning | 轻量知识超图构建+多轮Agent-环境交互检索+端到端奖励优化 | GraphRAG构建成本高、固定一次性检索、依赖长上下文推理 | 检索增强生成系统 |
| 9 | http://arxiv.org/abs/2508.00031v2 | Git Context Controller: Manage the Context of LLM-based Agents like Git | 类似 Git 的版本化上下文管理框架 | 解决长任务中 agent 上下文无界增长问题 | 软件工程与开放研究 |
| 10 | http://arxiv.org/abs/2508.05660v1 | Open-Source Agentic Hybrid RAG Framework for Scientific Literature Review | 动态选择 GraphRAG 或 VectorRAG 的 agent | 解决静态 RAG 缺乏不确定性与动态选择问题 | 科学文献综述 |
| 11 | http://arxiv.org/abs/2507.23633v1 | MemoCue: Empowering LLM-Based Agents for Human Memory Recall via Strategy-Guided Querying | 策略引导查询转换原始查询为线索丰富查询 | 解决记忆模块有限影响回忆性能问题 | 人类记忆回忆辅助 |
| 12 | http://arxiv.org/abs/2507.16799v2 | Test-Time-Matching: Decouple Personality, Memory, and Linguistic Style in LLM-based Role-Playing Language Agent | 测试时匹配框架自动解耦角色特征为个性、记忆和语言风格，无需训练 | 仅靠提示无法实现深度角色沉浸，微调方法数据收集和计算资源受限 | 角色扮演语言Agent |
| 13 | http://arxiv.org/abs/2507.21142v1 | Privacy Artifact ConnecTor (PACT): Embedding Enterprise Artifacts for Compliance AI Agents | 嵌入驱动图链接数百万跨类型工件，对比学习微调链接 artifacts | 隐私合规关键信息嵌入多样资源中，需识别互联 nature | 企业隐私合规AI Agent |
| 14 | http://arxiv.org/abs/2507.22925v1 | Hierarchical Memory for High-Efficiency Long-Term Reasoning in LLM Agents | 分层记忆架构基于语义抽象度多级组织更新记忆，索引路由机制高效检索 | 现有方法在结构化记忆组织和高效检索方面不足 | LLM Agent长期推理 |
| 15 | http://arxiv.org/abs/2507.06229v5 | Agent KB: Leveraging Cross-Domain Experience for Agentic Problem Solving | 通用记忆基础设施，实现异构智能体框架间经验共享 | 智能体框架孤立，知识无法跨架构迁移 | 跨框架智能体问题解决 |
| 16 | http://arxiv.org/abs/2507.07306v1 | ViDove: A Translation Agent System with Multimodal Context and Memory-Augmented Reasoning | 多模态记忆系统增强翻译，利用视觉与背景信息 | 翻译智能体通常限于文本输入，缺乏上下文记忆 | 长视频字幕生成与翻译 |

[返回目录](#目录)

<a id="cat-09"></a>

## 人机协作Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2507.04005v3 | Exploring a Gamified Personality Assessment Method through Interaction with LLM Agents Embodying Different Personalities | 多PR GPA框架，LLM赋能不同人格虚拟Agent，通过互动游戏 eliciting 人格表征 | 低侵入自动化人格评估受关注，需多重人格表征方法 | 人格评估系统 |
| 2 | http://arxiv.org/abs/2507.05244v1 | Modeling Latent Partner Strategies for Adaptive Zero-Shot Human-Agent Collaboration | TALENTS框架，VAE学习潜在策略空间，动态推断调整伙伴策略 | 异构团队中实时观察/识别/适应人类伙伴具挑战性 | 人机协作任务 |
| 3 | http://arxiv.org/abs/2507.01862v1 | Bridging UI Design and chatbot Interactions: Applying Form-Based Principles to Conversational Agents | 将表单原则应用于对话代理交互设计，明确提交与重置动作 | 多步交互中上下文管理混淆及用户意图追踪难 | 领域特定聊天bot 与 UI 设计 |
| 4 | http://arxiv.org/abs/2507.02122v1 | PAL: Designing Conversational Agents as Scalable, Cooperative Patient Simulators for Palliative-Care Training | 设计对话代理作为可扩展协作患者模拟器，提供结构化反馈 | 姑息护理培训资源有限及标准化患者 access 难 | 医疗培训与姑息护理 |
| 5 | http://arxiv.org/abs/2507.13937v2 | Marcel: A Lightweight and Open-Source Conversational Agent for University Student Support | 轻量级对话 Agent，结合 FAQ 检索增强生成提供可验证回答 | 减少大学工作人员工作量，提供快速个性化入学咨询 | 大学学生支持服务 |
| 6 | http://arxiv.org/abs/2507.15885v1 | ADEPTS: A Capability Framework for Human-Centered Agent Design | 提出 ADEPTS 能力框架，定义六项核心用户-facing 能力原则 | 现有指南分散，缺乏统一的用户-facing 能力词汇与指导 | 以人为本的 Agent 体验设计 |
| 7 | http://arxiv.org/abs/2507.15003v1 | The Rise of AI Teammates in Software Engineering (SE) 3.0: How Autonomous Coding Agents Are Reshaping Software Engineering | 发布 AIDev 数据集，实证研究自主编码 Agent 在野外的操作 | 缺乏大规模实证数据支持 AI 原生软件工程与协作研究 | 软件工程中的 AI 队友协作 |
| 8 | http://arxiv.org/abs/2507.11210v3 | Role-Playing LLM-Based Multi-Agent Support Framework... | 开发角色扮演多代理框架，检测家庭沟通中的偏见与压抑情绪。 | 解决家庭沟通中潜意识偏见难以检测与 addressed 的问题。 | 家庭心理支持 |
| 9 | http://arxiv.org/abs/2507.11299v2 | Dr.Copilot: A Multi-Agent Prompt Optimized Assistant... | 提出 Dr.Copilot 系统，评估并增强医生书面回复的呈现质量。 | 解决文本远程医疗中医疗建议沟通质量不佳的问题。 | 远程医疗沟通 |
| 10 | http://arxiv.org/abs/2507.12801v1 | Autonomy for Older Adult-Agent Interaction | examining 老年人代理交互的四个自主维度，提出研究方向。 | 解决代理自主性与老年人自主偏好对齐的关键挑战。 | 老年人护理代理 |
| 11 | http://arxiv.org/abs/2507.12806v2 | Imitating Mistakes in a Learning Companion AI Agent... | 开发学习伴侣代理，假设同等水平同伴会犯相同错误。 | 解决同伴学习中难以找到同等水平同伴的限制问题。 | 在线同伴学习 |
| 12 | http://arxiv.org/abs/2507.10580v2 | An Offline Mobile Conversational Agent for Mental Health Support: Learning from Emotional Dialogues and Psychological Texts with Student-Centered Evaluation | 离线移动端对话应用，微调模型提供心理健康支持 | 心理健康支持面临可访问性、连接性与隐私挑战 | 心理健康支持 |
| 13 | http://arxiv.org/abs/2507.18165v1 | ProactiveVA: Proactive Visual Analytics with LLM-Based UI Agent | LLM 驱动 UI Agent 监控交互并提供主动帮助 | 分析师在复杂视觉分析中易迷失 | 视觉分析系统用户 |
| 14 | http://arxiv.org/abs/2507.18315v1 | Talking to...uh...um...Machines: The Impact of Disfluent Speech Agents on Partner Models and Perspective Taking | 研究语音不流利 Agent 对人类伙伴模型的影响 | 人机对话中语音不流利的影响未知 | 人机语音对话系统 |
| 15 | http://arxiv.org/abs/2507.18374v1 | Towards Effective Human-in-the-Loop Assistive AI Agents | 引入评估框架与多模态数据集，AR 装备 Agent | 人机协作评估因交互复杂性而困难 | 物理任务人机协作 |
| 16 | http://arxiv.org/abs/2507.21636v1 | StaffPro: an LLM Agent for Joint Staffing and Profiling | 自然语言表达优化目标+持续人机反馈循环 | 人员配置与技能评估两挑战紧密交织 | 人力资源管理、任务分配与调度 |
| 17 | http://arxiv.org/abs/2507.22352v1 | Mitigating Response Delays in Free-Form Conversations with LLM-powered Intelligent Virtual Agents | 利用对话填充物 bridging 延迟 | 解决 VR 中 LLM 响应延迟降低体验问题 | 虚拟现实对话系统 |
| 18 | http://arxiv.org/abs/2507.22358v1 | Magentic-UI: Towards Human-in-the-loop Agentic Systems | 支持六种人机交互机制的开源界面 | 解决 AI 自主性带来的安全与失控风险 | 人机协作开发环境 |
| 19 | http://arxiv.org/abs/2507.16562v1 | Evaluating Social Acceptance of eXtended Reality (XR) Agent Technology: A User Study (Extended Version) | 扩展Almere模型，增加依赖性和安全性属性评估XR Agent社会接受度 | 缺乏对XR Agent技术在特定社会情境中用户感知和接受度的理解 | 记者数字远程培训 |
| 20 | http://arxiv.org/abs/2507.16735v1 | AI-enhanced conversational agents for personalized asthma support Factors for engagement, value and efficacy | 患者调查识别chatbot效能、价值和参与度的最优因素，提出7项建议 | 哮喘患者基本护理获取率低，需替代方法提供健康教育和支持 | 哮喘患者自我管理支持 |
| 21 | http://arxiv.org/abs/2507.05820v2 | Constella: Supporting Storywriters' Interconnected Character Creation through LLM-based Multi-Agents | 多智能体工具辅助创作者构建互联角色关系网 | 创作者难以构思影响现有角色的新人物及关系 | 长篇小说角色创作辅助 |

[返回目录](#目录)

<a id="cat-10"></a>

## Agent评测与基准

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2507.04037v4 | Ready Jurist One: Benchmarking Language Agents for Legal Intelligence in Dynamic Environments | J1-ENVS交互式动态法律环境+J1-EVAL细粒度评估框架，六场景三复杂度 | 静态基准与动态法律实践之间的差距阻碍法律智能进步 | 法律Agent能力评估 |
| 2 | http://arxiv.org/abs/2507.05098v1 | Beyond Features: How Dataset Design Influences Multi-Agent Trajectory Prediction Performance | 系统检查特征选择/跨数据集迁移/地理多样性对轨迹预测影响 | 数据集设计对模型性能影响研究不足 | 轨迹预测模型评估 |
| 3 | http://arxiv.org/abs/2507.05178v2 | CREW-WILDFIRE: Benchmarking Agentic Multi-Agent Collaborations at Scale | CREW-Wildfire基准，程序生成野火响应场景，支持大规模协作评估 | 现有基准在评估可扩展性/鲁棒性/协调能力方面不足 | 大规模多Agent协作评估 |
| 4 | http://arxiv.org/abs/2507.00451v1 | Best Agent Identification for General Game Playing | 基于 Wilson 区间的乐观选择过程识别最佳算法，减少 regret | 多任务域中代理评估效率低及算法运行时高 | 通用游戏框架与多任务域 |
| 5 | http://arxiv.org/abs/2507.01997v2 | Towards a Playground to Democratize Experimentation and Benchmarking of AI Agents for Network Troubleshooting | 构建标准化开放基准平台评估网络故障排除 Agent，降低操作 effort | AI 网络 Agent 实验复现难及缺乏标准基准 | 网络故障排除 Agent |
| 6 | http://arxiv.org/abs/2507.00938v2 | WebArXiv: Evaluating Multimodal Agents on Time-Invariant arXiv Tasks | 静态时间不变基准评估多模态 Web 代理，提出动态反思机制 | Web 代理评估基准不稳定及过度依赖固定历史 | Web 导航与交互任务 |
| 7 | http://arxiv.org/abs/2507.02825v5 | Establishing Best Practices for Building Rigorous Agentic Benchmarks | 建立构建严格代理基准的最佳实践，提出 Agentic Benchmark Checklist | 代理基准任务设置或奖励设计 issues 导致性能估计偏差 | 代理基准构建与评估 |
| 8 | http://arxiv.org/abs/2507.14705v1 | Configurable multi-agent framework for scalable and realistic testing of llm-based agents | Neo 框架自动化多轮评估，生成多样化人类对话测试输入 | 静态基准过时，手动测试无法覆盖复杂上下文敏感行为 | LLM 基于系统的 realistic 测试 |
| 9 | http://arxiv.org/abs/2507.15892v1 | StaAgent: An Agentic Framework for Testing Static Analyzers | 四 Agent 框架生成种子程序与变异体，评估静态分析器规则 | 静态分析器规则实现测试不足，易出现不一致与缺陷 | 静态分析器可靠性测试 |
| 10 | http://arxiv.org/abs/2507.10073v2 | Cultural Bias in Large Language Models: Evaluating AI Agents... | 应用道德基础问卷跨 19 种文化背景评估 LLM 代理。 | 解决 LLM 无法代表多样化文化道德框架的问题。 | AI 伦理与文化对齐 |
| 11 | http://arxiv.org/abs/2507.14201v2 | ExCyTIn-Bench: Evaluating LLM agents on Cyber Threat Investigation | 构建首个基于调查图的 LLM 代理网络威胁调查基准。 | 解决 LLM 代理在复杂安全日志分析任务缺乏评估标准。 | 网络安全威胁调查 |
| 12 | http://arxiv.org/abs/2507.10958v1 | DS@GT at eRisk 2025: From prompts to predictions... | 采用提示工程策略，让 LLM 进行 BDI-II 评估并输出结构化 JSON。 | 解决早期抑郁症检测中缺乏 ground-truth 标签的评估难题。 | 心理健康检测 |
| 13 | http://arxiv.org/abs/2507.12844v2 | MCPEval: Automatic MCP-based Deep Evaluation for AI Agent Models | 引入 MCPEval 框架，自动化端到端任务生成与深度评估。 | 解决现有评估依赖静态基准和劳动密集型数据收集的问题。 | 代理模型评估 |
| 14 | http://arxiv.org/abs/2507.13413v1 | GEMMAS: Graph-based Evaluation Metrics for Multi Agent Systems | 引入基于图的评价框架，分析内部协作过程与信息多样性。 | 解决现有评估仅关注最终输出，忽视协作效率与冗余问题。 | 多智能体系统评估 |
| 15 | http://arxiv.org/abs/2507.08616v1 | AgentsNet: Coordination and Collaborative Reasoning in Multi-Agent LLMs | 提出多智能体推理基准，评估网络拓扑协作能力 | 缺乏评估多智能体自组织与协作能力的基准 | 多智能体系统评估 |
| 16 | http://arxiv.org/abs/2507.09063v1 | SetupBench: Assessing Software Engineering Agents' Ability to Bootstrap Development Environments | 构建环境引导技能基准，隔离依赖安装任务 | 现有基准缺乏对开发环境引导能力的评估 | 软件工程智能体 |
| 17 | http://arxiv.org/abs/2507.09255v1 | StockSim: A Dual-Mode Order-Level Simulator for Evaluating Multi-Agent LLMs in Financial Markets | 开源金融模拟平台，建模市场微观结构 | 缺乏评估金融决策智能体的真实市场模拟器 | 金融智能体评估 |
| 18 | http://arxiv.org/abs/2507.22929v1 | EH-Benchmark Ophthalmic Hallucination Benchmark and Agent-Driven Top-Down Traceable Reasoning Workflow | 提出 EH-Benchmark 评估眼科 MLLM 幻觉 | 现有基准无法有效评估医疗幻觉 | 眼科医疗大模型 |
| 19 | http://arxiv.org/abs/2507.18901v1 | REPRO-Bench: Can Agentic AI Systems Assess the Reproducibility of Social Science Research? | 引入 REPRO-Bench 评估 Agent 评估研究可复现性 | 现有基准简化场景且缺乏数据格式多样性 | 社会科学研究可复现性 |
| 20 | http://arxiv.org/abs/2507.19132v1 | OS-MAP: How Far Can Computer-Using Agents Go in Breadth and Depth? | OS-MAP 基准，五级自动化分类与泛化范围评估 | 现有基准未考虑任务异构性与用户需求对齐 | 计算机使用 Agent |
| 21 | http://arxiv.org/abs/2507.19361v2 | SpeechIQ: Speech-Agentic Intelligence Quotient Across Cognitive Levels in Voice Understanding by Large Language Models | SpeechIQ 评估管道，基于 Bloom 分类法三认知层级 | 现有语音理解指标如 WER 不足 | 语音理解大模型 |
| 22 | http://arxiv.org/abs/2507.19478v1 | MMBench-GUI: Hierarchical Multi-Platform Evaluation Framework for GUI Agents | MMBench-GUI 基准，四层技能评估与 EQA 指标 | 现有基准未考虑内部任务异构性与用户需求 | GUI 自动化 Agent |
| 23 | http://arxiv.org/abs/2507.21017v1 | MIRAGE-Bench: LLM Agent is Hallucinating and Where to Find Them | 首个统一基准评估交互式LLM Agent幻觉 | 现有评估碎片化缺乏原则性测试平台 | LLM Agent幻觉检测与评估 |
| 24 | http://arxiv.org/abs/2507.21028v1 | Multi-Agent-as-Judge: Aligning LLM-Agent-Based Automated Evaluation with Multi-Dimensional Human Evaluation | MAJ-EVAL框架自动构建多评估者角色进行组内辩论 | 现有LLM-as-judge角色描述任意且不可泛化 | 教育和医疗领域自动评估 |
| 25 | http://arxiv.org/abs/2507.21504v1 | Evaluation and Benchmarking of LLM Agents: A Survey | 二维分类法组织评估目标与评估过程 | Agent评估领域复杂且欠发达 | LLM Agent评估研究 |
| 26 | http://arxiv.org/abs/2507.22034v1 | UserBench: An Interactive Gym Environment for User-Centric Agents | 模拟用户从模糊目标开始逐步揭示偏好需Agent主动澄清 | Agent与用户主动协作能力尤其目标模糊时未充分探索 | 用户中心多轮偏好驱动交互 |
| 27 | http://arxiv.org/abs/2508.00923v2 | Beyond Benchmarks: Dynamic, Automatic And Systematic Red-Teaming Agents For Trustworthy Medical Language Models | 动态自动系统性红队测试框架 | 解决静态基准无法反映模型动态可靠性问题 | 医疗语言模型安全 |
| 28 | http://arxiv.org/abs/2507.23194v1 | Geak: Introducing Triton Kernel AI Agent & Evaluation Benchmarks | 利用推理时计算缩放生成 Triton 代码 | 解决 AI 生成 GPU 内核性能与正确性问题 | AMD GPU 内核开发 |
| 29 | http://arxiv.org/abs/2507.16248v3 | FinResearchBench: A Logic Tree based Agent-as-a-Judge Evaluation Framework for Financial Research Agents | 首个基于逻辑树的Agent-as-a-Judge系统，提取研究结果逻辑树进行评估 | 缺乏系统自动评估深度研究Agent能力的框架和基准 | 金融研究Agent评估 |
| 30 | http://arxiv.org/abs/2507.16725v2 | RAVine: Reality-Aligned Evaluation for Agentic Search | 针对多点查询和长答案，引入可归因地面真值构建策略，评估迭代过程 | 现有评估框架与Agentic Search目标不一致，忽略迭代过程评估 | Agentic搜索系统评估 |
| 31 | http://arxiv.org/abs/2507.17186v2 | FinGAIA: A Chinese Benchmark for AI Agents in Real-World Financial Domain | 首个金融领域Agent基准，407个任务覆盖7个子领域3个层级 | 金融领域多步多工具协作能力未充分探索，缺乏实用能力评估 | 金融领域AI Agent评估 |
| 32 | http://arxiv.org/abs/2507.17257v1 | Agent Identity Evals: Measuring Agentic Identity | 严格统计驱动的实证框架测量LMA系统随时间保持Agent身份的程度 | LMA继承LLM病理（无状态、随机性等）削弱可识别性、连续性和一致性 | 语言模型Agent身份评估 |
| 33 | http://arxiv.org/abs/2507.05257v3 | Evaluating Memory in LLM Agents via Incremental Multi-Turn Interactions | 提出 MemoryAgentBench，涵盖四种核心记忆能力评估 | 缺乏针对智能体记忆机制的系统性基准测试 | LLM 智能体记忆能力评估 |
| 34 | http://arxiv.org/abs/2507.05495v2 | Deep Research Comparator: A Platform For Fine-grained Human Annotations of Deep Research Agents | 提供深度研究智能体的并排比较与细粒度反馈平台 | 长报告评估困难，缺乏中间步骤反馈机制 | 深度研究智能体开发与评估 |
| 35 | http://arxiv.org/abs/2507.05639v2 | ECom-Bench: Can LLM Agent Resolve Real-World E-commerce Customer Support Issues? | 基于真实 persona 动态模拟的电商客服基准测试 | 现有基准无法反映真实电商场景的复杂性 | 电商客服 LLM 智能体评估 |
| 36 | http://arxiv.org/abs/2507.07155v1 | Evaluating Retrieval-Augmented Generation Agents for Autonomous Scientific Discovery in Astrophysics | 评估天体物理科学发现 RAG 智能体，校准 LLM-as-a-Judge | 缺乏针对自主科学发现智能体的系统评估 | 天体物理学科学发现 |
| 37 | http://arxiv.org/abs/2507.07445v2 | StarDojo: Benchmarking Open-Ended Behaviors of Agentic Multimodal LLMs in Production-Living Simulations with Stardew Valley | 基于星露谷的开放生成 - 生活模拟智能体基准 | 现有基准很少同时评估生产活动与社交交互 | 多模态 LLM 智能体评估 |

[返回目录](#目录)

<a id="cat-11"></a>

## Agent安全与对齐

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2507.04105v1 | Enhancing Robustness of LLM-Driven Multi-Agent Systems through Randomized Smoothing | 随机平滑防御框架，两阶段自适应采样平衡鲁棒性与计算效率 | 安全关键领域中LLM赋能MAS的安全性需概率保证 | 航空航天等安全关键领域 |
| 2 | http://arxiv.org/abs/2507.04227v1 | Hijacking JARVIS: Benchmarking Mobile GUI Agents against Unprivileged Third Parties | AgentHazard攻击模拟框架，3000+攻击场景基准，评估7种GUI Agent | 移动GUI Agent在真实场景中面对第三方操纵的韧性未探索 | 移动GUI Agent安全性 |
| 3 | http://arxiv.org/abs/2507.04724v2 | Who's the Mole? Modeling and Detecting Intention-Hiding Malicious Agents in LLM-Based Multi-Agent Systems | AgentXposed检测框架，结合HEXACO人格模型+Reid审讯技术识别恶意Agent | LLM-MAS中意图隐藏威胁未探索，现有防御易被规避 | LLM多Agent系统安全 |
| 4 | http://arxiv.org/abs/2507.02986v2 | GAF-Guard: An Agentic Framework for Risk Management and Governance in Large Language Models | 以用户为中心的 LLM 治理代理框架，检测监控特定用例风险 | LLM 部署中的 unintended 负面后果及对齐需求 | LLM 治理与风险管理 |
| 5 | http://arxiv.org/abs/2507.00841v1 | SafeMobile: Chain-level Jailbreak Detection and Automated Evaluation for Multimodal Mobile Agents | 链级越狱检测与自动化评估多模态移动 Agent， Incorporating 行为序列 | 移动多模态 Agent 的越狱安全风险及复杂交互检测 | 移动设备控制与智能助手 |
| 6 | http://arxiv.org/abs/2507.00979v1 | Enhancing LLM Agent Safety via Causal Influence Prompting | 利用因果影响图识别缓解 Agent 决策风险，引导安全决策 | 自主 Agent 行为安全可靠及预防 unintended 后果 | 代码执行与移动设备控制 |
| 7 | http://arxiv.org/abs/2507.01446v1 | Using multi-agent architecture to mitigate the risk of LLM hallucinations | 多代理系统结合模糊逻辑减轻 LLM 幻觉，处理 SMS 客户请求 | 客户服务中 LLM 幻觉风险及响应质量维护 | 客户服务与 SMS 交互 |
| 8 | http://arxiv.org/abs/2507.02699v1 | Control at Stake: Evaluating the Security Landscape of LLM-Driven Email Agents | 评估 LLM 驱动邮件代理的安全景观，提出 Email Agent Hijacking 攻击 | 邮件代理应用安全机制 underexplored 及远程控制风险 | LLM 邮件代理应用安全 |
| 9 | http://arxiv.org/abs/2507.14293v1 | WebGuard: Building a Generalizable Guardrail for Web Agents | 构建 WebGuard 数据集，微调专用护栏模型预测动作风险 | 现有 LLM 预测动作结果准确率低，缺乏部署 safeguards | 自主 Web 智能体安全防护 |
| 10 | http://arxiv.org/abs/2507.14660v2 | When Autonomy Goes Rogue: Preparing for Risks of Multi-Agent Collusion in Social Systems | 模拟恶意多智能体共谋风险，发现去中心化系统更具破坏性 | 多智能体系统在复杂现实情境中的共谋风险未被充分探索 | 社会系统中的恶意 Agent 共谋 |
| 11 | http://arxiv.org/abs/2507.14799v1 | Manipulating LLM Web Agents with Indirect Prompt Injection Attack via HTML Accessibility Tree | 演示通过 HTML 嵌入触发器劫持利用 accessibility tree 的 Agent | LLM Web 导航 Agent 易受间接提示注入攻击导致恶意行为 | Web 智能体安全性研究 |
| 12 | http://arxiv.org/abs/2507.15901v1 | Advancing Responsible Innovation in Agentic AI: A study of Ethical Frameworks for Household Automation | 分析家庭自动化中 Agentic AI 的伦理挑战，提出设计原则 | 主动自主 Agent 带来隐私、公平与用户控制等伦理挑战 | 家庭自动化与伦理设计 |
| 13 | http://arxiv.org/abs/2507.15330v1 | QSAF: A Novel Mitigation Framework for Cognitive Degradation in Agentic AI | 提出认知退化漏洞类，定义六阶段生命周期与运行时控制 | 内部系统弱点导致静默漂移、逻辑崩溃与持续幻觉 | 智能体认知退化防御 |
| 14 | http://arxiv.org/abs/2507.15903v1 | Towards Mitigation of Hallucination for LLM-empowered Agents: Progressive Generalization Bound Exploration and Watchdog Monitor | HalMit 黑盒看门狗框架，建模泛化边界检测幻觉 | LLM 幻觉 undermining 智能体可信度，现有方法依赖白盒或不准 | LLM 赋能智能体幻觉缓解 |
| 15 | http://arxiv.org/abs/2507.15478v1 | The Constitutional Controller: Doubt-Calibrated Steering of Compliant Agents | 神经符号系统结合概率逻辑，引入自我怀疑概念确保安全 | 不确定环境中确保自主 Agent 可靠与规则合规行为是挑战 | 智能自主系统安全合规控制 |
| 16 | http://arxiv.org/abs/2507.10016v2 | The Man Behind the Sound: Demystifying Audio Private Attribute Profiling... | 提出 Gifts 混合多智能体框架，增强音频敏感属性推断能力。 | 解决多模态大模型从音频推断隐私属性的风险与幻觉。 | 多模态大模型隐私安全 |
| 17 | http://arxiv.org/abs/2507.10457v2 | Logic layer Prompt Control Injection (LPCI): A Novel Security... | 揭示逻辑层提示控制注入漏洞，可嵌入延迟触发载荷。 | 解决代理系统中逻辑执行层和持久内存的隐蔽安全漏洞。 | 企业级代理系统安全 |
| 18 | http://arxiv.org/abs/2507.11567v1 | Consumer Law for AI Agents | 探讨欧盟消费者法律如何适应 AI 代理（Custobot）经济。 | 解决现行法律基于人类决策假设，不适配 AI 代理的问题。 | 法律与政策监管 |
| 19 | http://arxiv.org/abs/2507.13038v1 | Machine-Readable Ads: Accessibility and Trust Patterns... | 实验研究 Web 代理与广告交互模式，提出设计原则。 | 解决显示广告设计针对人类，代理交互存在信任风险问题。 | Web 代理与广告交互 |
| 20 | http://arxiv.org/abs/2507.13081v1 | MAD-Spear: A Conformity-Driven Prompt Injection Attack... | 提出 MAD-Spear 攻击，利用 LLM 从众倾向传播 misinformation。 | 解决多智能体辩论系统在提示注入攻击下的脆弱性问题。 | 多智能体辩论安全 |
| 21 | http://arxiv.org/abs/2507.13285v1 | Black Box Deployed -- Functional Criteria for Artificial Moral Agents... | 提出十项功能标准，评估 LLM 时代的人工道德代理。 | 解决传统伦理标准不适配 LLM 随机输出与 opaque 内部状态。 | 人工智能伦理 |
| 22 | http://arxiv.org/abs/2507.08207v2 | Toward a Dynamic Stackelberg Game-Theoretic Framework for Agentic AI Defense Against LLM Jailbreaking | 博弈论框架建模提示工程师与 LLM 交互，防御 Jailbreaking | LLM 面临 Prompt 注入攻击，缺乏理论防御基础 | LLM 安全防护 |
| 23 | http://arxiv.org/abs/2507.08249v2 | Giving AI Agents Access to Cryptocurrency and Smart Contracts Creates New Vectors of AI Harm | 提出加密货币赋予智能体的新危害向量分类 | 智能体访问加密货币带来的新型安全风险 | 加密货币与智能体安全 |
| 24 | http://arxiv.org/abs/2507.08270v1 | Agent Safety Alignment via Reinforcement Learning | 统一安全对齐框架，处理用户与工具双通道威胁 | 工具使用智能体面临用户与工具发起的新型安全风险 | 自主 LLM 智能体安全 |
| 25 | http://arxiv.org/abs/2507.09329v2 | When Developer Aid Becomes Security Debt: A Systematic Analysis of Insecure Behaviors in LLM Coding Agents | 系统分析 LLM 编码智能体的不安全行为与漏洞 | 自主编码智能体的安全影响未被充分理解 | 编码智能体安全 |
| 26 | http://arxiv.org/abs/2507.10610v1 | LaSM: Layer-wise Scaling Mechanism for Defending Pop-up Attack on GUI Agents | 层-wise 缩放机制选择性放大注意力，防御 GUI 弹窗攻击 | GUI 智能体易受弹窗环境注入攻击，现有防御成本高 | GUI 智能体安全 |
| 27 | http://arxiv.org/abs/2507.10621v1 | Game Theory Meets LLM and Agentic AI: Reimagining Cybersecurity for the Age of Intelligent Threats | 结合博弈论与智能体 AI 重构网络安全防御 | 传统网络安全方法缺乏主动智能防御能力 | 网络安全防御 |
| 28 | http://arxiv.org/abs/2507.21113v1 | Vulnerability Mitigation System (VMS): LLM Agent and Evaluation Framework for Autonomous Penetration Testing | 基于 LLM 的智能体执行无干预渗透测试 | 传统渗透测试无法捕捉当今复杂环境的全部威胁 | 自主渗透测试 |
| 29 | http://arxiv.org/abs/2507.18284v1 | Designing Value-Aligned Traffic Agents through Conflict Sensitivity | 采用冲突敏感性模型，设计价值对齐交通 Agent | 自主交通 Agent 需符合法律社会道德价值 | 自主交通系统 |
| 30 | http://arxiv.org/abs/2507.22077v1 | From Cloud-Native to Trust-Native: A Protocol for Verifiable Multi-Agent Systems | TrustTrack 协议，嵌入可验证身份与行为日志 | 高利益领域 Agent 缺乏可验证性 | regulated 领域多 Agent 系统 |
| 31 | http://arxiv.org/abs/2507.19183v1 | Agentic AI and Hallucinations | 建模竞争市场，Agent 努力验证降低幻觉风险 | 幻觉敏感 sector 需 endogenous 验证努力 | agentic AI 市场 |
| 32 | http://arxiv.org/abs/2507.21188v1 | Embeddings to Diagnosis: Latent Fragility under Agentic Perturbations in Clinical LLMs | 提出LAPD框架和LDFR指标诊断潜在脆弱性 | 临床LLM在小输入变化下诊断不稳定 | 临床决策支持系统 |
| 33 | http://arxiv.org/abs/2507.20526v1 | Security Challenges in AI Agent Deployment: Insights from a Large Scale Public Competition | 构建ART基准评估22个前沿Agent的安全漏洞 | AI Agent在真实环境中遵循部署策略的可信性 | 大规模Agent安全评估 |
| 34 | http://arxiv.org/abs/2507.20796v2 | Aligning Large Language Model Agents with Rational and Moral Preferences: A Supervised Fine-Tuning Approach | 监督微调对齐经济偏好（homo economicus/moralis） | 现成LLM Agent在策略环境中偏离收益敏感行为 | 市场和组织中的自主Agent |
| 35 | http://arxiv.org/abs/2507.20964v2 | Core Safety Values for Provably Corrigible Agents | 五个结构分离效用头组合实现可证明可纠正性 | 多步部分观察环境中Agent可纠正性无形式解 | 关断博弈、安全关键Agent系统 |
| 36 | http://arxiv.org/abs/2508.00910v2 | Cyber-Zero: Training Cybersecurity Agents without Runtime | 首个无运行时框架合成人格驱动LLM模拟CTF解题轨迹 | 网络安全领域挑战配置和执行环境短暂或受限 | 网络安全LLM Agent训练 |
| 37 | http://arxiv.org/abs/2507.22326v1 | An Explainable Emotion Alignment Framework for LLM-Empowered Agent in Metaverse Service Ecosystem | 可解释的情感对齐框架 | 解决元宇宙 agent 情感与事实对齐问题 | 元宇宙服务生态系统 |
| 38 | http://arxiv.org/abs/2508.02836v1 | Agentic Privacy-Preserving Machine Learning | 意图解析与加密推理模块化分离 | 解决大模型隐私保护推理效率低下问题 | 隐私保护 LLM 服务 |
| 39 | http://arxiv.org/abs/2508.00935v2 | Measuring Harmfulness of Computer-Using Agents | 包含 104 个专家编写 misuse risks 基准 | 解决现有基准主要评估聊天机器人而非 CUA 问题 | 计算机使用 agent 安全 |
| 40 | http://arxiv.org/abs/2507.15796v2 | From Privacy to Trust in the Agentic Era: A Taxonomy of Challenges in Trustworthy Federated Learning Through the Lens of Trust Report 2.0 | 提出可信联邦学习 taxonomy，将信任视为持续维护的运行条件 | 隐私保障不足以维持高风险场景信任，需系统级可信框架 | 联邦学习系统治理 |
| 41 | http://arxiv.org/abs/2507.16459v2 | Towards Enforcing Company Policy Adherence in Agentic Workflows | 两阶段框架：离线编译策略为可验证守卫代码，运行时确保合规 | LLM Agent难以可靠遵循复杂公司策略，缺乏确定性透明框架 | 企业业务流程自动化 |
| 42 | http://arxiv.org/abs/2507.21146v1 | Towards Unifying Quantitative Security Benchmarking for Multi Agent Systems | 形式化Agent级联注入攻击，提出量化基准框架评估Agent间通信协议安全 | 多Agent架构连接引入级联风险，缺乏定量安全基准 | 多Agent系统安全评估 |
| 43 | http://arxiv.org/abs/2507.05445v1 | A Systematization of Security Vulnerabilities in Computer Use Agents | 系统分析计算机使用智能体的七类安全风险与攻击面 | 计算机使用智能体缺乏安全边界与威胁模型 | 计算机使用智能体 (CUA) 安全 |
| 44 | http://arxiv.org/abs/2507.05558v4 | AI Agent Smart Contract Exploit Generation | 代理系统自动发现智能合约漏洞并生成可利用代码 | 传统模糊测试效率低，人工审计无法规模化 | 区块链智能合约安全审计 |
| 45 | http://arxiv.org/abs/2507.06134v2 | OpenAgentSafety: A Comprehensive Framework for Evaluating Real-World AI Agent Safety | 评估真实工具交互下的智能体安全，涵盖八类风险 | 现有基准依赖模拟环境，无法评估真实工具风险 | 真实世界 AI 智能体安全评估 |
| 46 | http://arxiv.org/abs/2507.06323v1 | Bridging AI and Software Security: A Comparative Vulnerability Assessment of LLM Agent Deployment Paradigms | 比较 Function Calling 与 MCP 部署范式的安全漏洞 | AI 特定威胁与传统软件漏洞研究分离，缺乏统一评估 | LLM 智能体部署架构安全 |
| 47 | http://arxiv.org/abs/2507.06850v5 | The Dark Side of LLMs: Agent-based Attacks for Complete Computer Takeover | 揭示 LLM 智能体可被利用实现计算机完全接管 | 智能体系统引入系统级妥协的新安全漏洞 | LLM 智能体系统安全 |
| 48 | http://arxiv.org/abs/2507.06899v2 | VisualTrap: A Stealthy Backdoor Attack on GUI Agents via Visual Grounding Manipulation | 通过视觉定位操纵实现 GUI 智能体的隐蔽后门攻击 | GUI 智能体视觉定位机制存在 vulnerabilities | GUI 智能体安全 |
| 49 | http://arxiv.org/abs/2507.06908v1 | MIND: A Multi-agent Framework for Zero-shot Harmful Meme Detection | 多智能体辩论机制实现零样本有害模因检测 | 传统数据驱动方法难以检测新型演化模因 | 社交媒体有害内容检测 |
| 50 | http://arxiv.org/abs/2507.07307v2 | Multi-Agent Retrieval-Augmented Framework for Evidence-Based Counterspeech Against Health Misinformation | 多智能体检索增强框架生成基于证据的反制言论 | 现有研究证据有限，对最终输出控制力弱 | 健康 misinformation 反制 |

[返回目录](#目录)

<a id="cat-12"></a>

## 多Agent强化学习

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2507.04140v1 | Learning Humanoid Arm Motion via Centroidal Momentum Regularized Multi-Agent Reinforcement Learning | 肢体级多Agent RL框架，分离手臂/腿Actor-Critic，共享质心动量观测 | 人形机器人协调全身控制，手臂运动调节动力学和平衡 | 人形机器人运动控制 |
| 2 | http://arxiv.org/abs/2507.00550v1 | Collaborative Multi-Agent Reinforcement Learning Approach for Elastic Cloud Resource Scaling | 多智能体协作强化学习实现弹性云资源缩放，引入协作价值函数 | 云环境资源变化快及任务负载高度不确定 | 弹性云资源缩放 |
| 3 | http://arxiv.org/abs/2507.01823v1 | TD-MPC-Opt: Distilling Model-Based Multi-Task Reinforcement Learning Agents | 蒸馏基于模型的多任务强化学习代理，优化资源受限部署 | 资源受限环境部署大世界模型挑战及知识表示 | 机器人与资源受限应用 |
| 4 | http://arxiv.org/abs/2507.02698v1 | Multi-Agent Reinforcement Learning for Dynamic Pricing in Supply Chains: Benchmarking Strategic Agent Behaviours under Realistically Simulated Market Conditions | 多代理强化学习用于供应链动态定价，评估战略 Agent 行为 | 传统 ERP 静态规则忽略战略互动及市场 actor 依赖 | 供应链动态定价 |
| 5 | http://arxiv.org/abs/2507.13846v1 | Causal Knowledge Transfer for Multi-Agent Reinforcement Learning in Dynamic Environments | 引入因果知识转移框架，共享路径因果表示实现在线迁移 | 非平稳环境中传统知识迁移泛化差、重训练成本高 | 动态环境多智能体系统 |
| 6 | http://arxiv.org/abs/2507.14658v1 | Learning to Communicate in Multi-Agent Reinforcement Learning for Autonomous Cyber Defence | 设计游戏让防御 Agent 学习通信以协同抵御网络威胁 | 部分可观察环境中独立行动限制协同效应 | 自主网络防御系统 |
| 7 | http://arxiv.org/abs/2507.14850v2 | Hierarchical Multi-Agent Reinforcement Learning with Control Barrier Functions for Safety-Critical Autonomous Systems | 基于控制屏障函数的分层 MARL，高层协作低层安全 | 安全关键系统中需同时满足安全要求与合作完成任务 | 安全关键自主系统（如交通） |
| 8 | http://arxiv.org/abs/2507.14995v3 | LLM-Enhanced Multi-Agent Reinforcement Learning with Expert Workflow for Real-Time P2P Energy Trading | LLM 作为专家生成策略指导 MARL，差分注意力 Critic 网络 | 大规模 P2P 能源交易中专家指导扩展难，缺乏定制框架 | 实时点对点能源交易 |
| 9 | http://arxiv.org/abs/2507.15174v1 | Joint-Local Grounded Action Transformation for Sim-to-Real Transfer in Multi-Agent Traffic Control | 将 GAT 应用于 MARL 交通控制，平衡扩展性与接地能力 | 多智能体交通控制策略从仿真到现实存在性能下降 gap | 多智能体交通信号控制 |
| 10 | http://arxiv.org/abs/2507.15351v2 | One Step is Enough: Multi-Agent Reinforcement Learning based on One-Step Policy Optimization for Order Dispatch on Ride-Sharing Platforms | 提出 OSPO 方法，仅需一步群奖励训练最优策略，消除偏差 | 传统 MARL 依赖价值函数估计，在大规模不确定环境中 problematic | 网约车平台订单调度 |
| 11 | http://arxiv.org/abs/2507.10142v1 | Adaptability in Multi-Agent Reinforcement Learning: A Framework... | 提出适应性框架，包含学习、策略和场景驱动三个维度。 | 解决 MARL 在动态真实世界环境中部署受限的问题。 | 多智能体强化学习 |
| 12 | http://arxiv.org/abs/2507.10251v1 | ToMacVF : Temporal Macro-action Value Factorization... | 提出时间宏动作价值分解，实现细粒度时间信用分配。 | 解决异步 MARL 中宏动作执行表示不完整和信用分配不当。 | 异步多智能体强化学习 |
| 13 | http://arxiv.org/abs/2507.07671v1 | Multi-agent Reinforcement Learning-based In-place Scaling Engine for Edge-cloud Systems | 基于 MARL 的原位扩展引擎，实现动态资源控制与微服务低响应 | 边缘云系统动态工作负载下资源扩展效率低且性能难维持 | 边缘云系统资源管理 |
| 14 | http://arxiv.org/abs/2507.08429v1 | Age of Information Optimization in Laser-charged UAV-assisted IoT Networks: A Multi-agent Deep Reinforcement Learning Method | 提出 MAPPO-TM 框架，优化无人机轨迹与激光充电 | 无人机物联网中信息年龄优化与能源约束平衡 | 无人机物联网 |
| 15 | http://arxiv.org/abs/2507.09179v2 | Hide-and-Shill: A Reinforcement Learning Framework for Market Manipulation Detection in Symphony-a Decentralized Multi-Agent System | MARL 框架检测去中心化市场操纵，集成多模态数据 | 去中心化金融中缺乏有效市场操纵检测机制 | 去中心化金融监控 |
| 16 | http://arxiv.org/abs/2507.09495v1 | GenAI-based Multi-Agent Reinforcement Learning towards Distributed Agent Intelligence: A Generative-RL Agent Perspective | 主张从反应式到生成式 RL 智能体的范式转变 | 传统 MARL 面临动作空间爆炸与非平稳环境挑战 | 分布式智能体系统 |
| 17 | http://arxiv.org/abs/2507.09989v1 | Improving monotonic optimization in heterogeneous multi-agent reinforcement learning with optimal marginal deterministic policy gradient | 提出 OMDPG 算法，解决异构 MARL 单调改进冲突 | 异构多智能体强化学习中参数共享与单调改进冲突 | 异构多智能体系统 |
| 18 | http://arxiv.org/abs/2507.18059v2 | Multi-Agent Guided Policy Optimization | 提出 MAGPO 框架，集成集中式指导与分散式执行 | 现有 CTDE 方法未充分利用集中式训练 | 合作式多智能体强化学习 |
| 19 | http://arxiv.org/abs/2507.18095v1 | Towards Microgrid Resilience Enhancement via Mobile Power Sources and Repair Crews: A Multi-Agent Reinforcement Learning Approach | 分层多智能体强化学习，两级框架协调调度 | 通信受损下微电网弹性恢复的分散决策 | 微电网与修复 crew 协调调度 |
| 20 | http://arxiv.org/abs/2507.18867v1 | Learning Individual Intrinsic Reward in Multi-Agent Reinforcement Learning via Incorporating Generalized Human Expertise | LIGHT 框架，端到端整合人类知识到 MARL | 稀疏奖励下 MARL 探索效率低 | 多智能体强化学习 |
| 21 | http://arxiv.org/abs/2507.19146v2 | Diverse and Adaptive Behavior Curriculum for Autonomous Driving: A Student-Teacher Framework with Multi-Agent RL | 学生 - 教师框架，教师生成多样交通行为课程 | RL 训练依赖规则场景，泛化有限 | 自动驾驶 |
| 22 | http://arxiv.org/abs/2507.19151v2 | ReCoDe: Reinforcement Learning-based Dynamic Constraint Design for Multi-Agent Coordination | ReCoDe 框架，学习动态约束辅助专家控制器 | 手工约束在多 Agent 复杂协调中失败 | 多 Agent 导航协调 |
| 23 | http://arxiv.org/abs/2507.20143v1 | Concept Learning for Cooperative Multi-Agent Reinforcement Learning | 提出CMQ框架，通过概念瓶颈模型学习可解释的合作概念 | 多智能体强化学习缺乏透明性和互操作性 | StarCraft II微操、等级式觅食任务 |
| 24 | http://arxiv.org/abs/2507.20377v2 | Multi-Agent Reinforcement Learning for Dynamic Mobility Resource Allocation with Hierarchical Adaptive Grouping | HAG-PS框架实现动态自适应参数共享 | 城市规模移动资源分配的策略共享与内存效率 | 共享单车/滑板车、拼车车辆调度 |
| 25 | http://arxiv.org/abs/2507.21941v1 | Hierarchical Game-Based Multi-Agent Decision-Making for Autonomous Vehicles | 分层博弈框架通过交互图智能选择有限Agent作为博弈玩家 | 标准多玩家博弈计算复杂度高且成对博弈决策效率低 | 自动驾驶多Agent场景决策 |
| 26 | http://arxiv.org/abs/2507.22338v1 | Parametrized Multi-Agent Routing via Deep Attention Models | 结合最大熵原理的深度注意力模型 | 解决混合离散连续结构的路由优化问题 | 设施定位与路径优化 |
| 27 | http://arxiv.org/abs/2507.22782v3 | Enhancing Multi-Agent Collaboration with Attention-Based Actor-Critic Policies | 引入多头注意力机制的 TAAC 算法 | 解决联合动作空间指数增长与协作问题 | 合作性多 agent 环境 |
| 28 | http://arxiv.org/abs/2507.23080v1 | Causal-Inspired Multi-Agent Decision-Making via Graph Reinforcement Learning | 因果解耦表示学习结合图强化学习 | 解决多车交互环境下最优决策挑战 | 自动驾驶无信号路口 |
| 29 | http://arxiv.org/abs/2508.00938v1 | Trusted Routing for Blockchain-Empowered UAV Networks via Multi-Agent Deep Reinforcement Learning | 区块链信任机制结合多 agent DQN | 解决 UAV 网络路由易受恶意损害问题 | 无人机网络路由 |
| 30 | http://arxiv.org/abs/2507.23604v1 | Hierarchical Message-Passing Policies for Multi-Agent Reinforcement Learning | 基于封建 HRL 框架的分层消息传递策略 | 解决分层策略优化限制与部分可观测问题 | 多 agent 强化学习基准 |
| 31 | http://arxiv.org/abs/2507.15587v1 | Red-Team Multi-Agent Reinforcement Learning for Emergency Braking Scenario | 提出红队多Agent强化学习框架，背景车辆作为干扰Agent主动探索边界案例 | 安全关键场景中数据驱动方法无法捕捉真实边界案例 | 自动驾驶紧急制动场景 |
| 32 | http://arxiv.org/abs/2507.16249v1 | Multi-Agent Reinforcement Learning for Sample-Efficient Deep Neural Network Mapping | 去中心化MARL框架，引入Agent聚类算法基于相关性分配映射参数 | DNN硬件映射中强化学习样本效率低，搜索空间巨大复杂 | 高性能加速器设计 |
| 33 | http://arxiv.org/abs/2507.16479v1 | Arbitrage Tactics in the Local Markets via Hierarchical Multi-agent Reinforcement Learning | 分层MARL算法使聚合器跨多个本地市场执行套利，子Agent协调通信 | 现有研究仅探索单一市场，跨市场套利机会未探索 | 本地电力和灵活性市场 |
| 34 | http://arxiv.org/abs/2507.16635v1 | Novel Multi-Agent Action Masked Deep Reinforcement Learning for General Industrial Assembly Lines Balancing Problems | 动作掩码技术确保Agent仅选择可行动作，多Agent方法减少状态动作空间 | 整数规划大规模场景计算不可行，启发式方法常产生次优解 | 工业装配线平衡 |
| 35 | http://arxiv.org/abs/2507.16796v1 | Uncertainty-Aware Knowledge Transformers for Peer-to-Peer Energy Trading with Multi-Agent Reinforcement Learning | 不确定性感知预测与MARL集成，KTU模型量化预测不确定性 | 现有工作依赖确定性预测，无法在随机环境中稳健决策 | P2P能源交易 |
| 36 | http://arxiv.org/abs/2507.17188v1 | LLM Meets the Sky: Heuristic Multi-Agent Reinforcement Learning for Secure Heterogeneous UAV Networks | LLM引导启发式MARL方法，LLM生成专家启发式策略，无实时推理开销 | 异构UAV网络中物理层安全问题，需管理运动与通信复杂耦合 | 异构无人机网络安全 |
| 37 | http://arxiv.org/abs/2507.17433v1 | Fair Compromises in Participatory Budgeting: a Multi-Agent Deep Reinforcement Learning Approach | 分支神经网络架构去中心化克服MARL可扩展性挑战，优化选民行动 | 参与式预算中选民决策导致选择过载，需支持公平妥协 | 参与式预算决策支持 |
| 38 | http://arxiv.org/abs/2507.05534v1 | Evolutionary and Coevolutionary Multi-Agent Design Choices and Dynamics | 结合 LLM 支持变异算子的进化算法优化智能体控制器 | 量化不同表示与算法组合在团队性能上的权衡 | 网络安全场景下的智能体对抗 |
| 39 | http://arxiv.org/abs/2507.06278v1 | A Survey of Multi Agent Reinforcement Learning: Federated Learning and Cooperative and Noncooperative Decentralized Regimes | 全面综述联邦、去中心化及非合作多智能体强化学习 | 缺乏对三种交互拓扑的系统性梳理与理论保证 | 多智能体强化学习研究者 |
| 40 | http://arxiv.org/abs/2507.06004v1 | From General Relation Patterns to Task-Specific Decision-Making in Continual Multi-Agent Coordination | 提出关系模式引导的任务特定决策器，防止灾难性遗忘 | 持续多智能体协调中的灾难性遗忘问题 | 动态团队持续协调任务 |
| 41 | http://arxiv.org/abs/2507.06690v1 | Multi-Task Multi-Agent Reinforcement Learning via Skill Graphs | 利用技能图处理不相关任务，增强知识迁移能力 | 现有方法难以处理不相关任务，知识迁移能力有限 | 多任务多智能体强化学习 |
| 42 | http://arxiv.org/abs/2507.07074v1 | Graph-Based Complexity Metrics for Multi-Agent Curriculum Learning: A Validated Approach to Task Ordering in Cooperative Coordination Environments | 基于图的协调复杂度指标指导多智能体课程学习 | 多智能体协调缺乏验证的任务复杂度指标 | 多机器人协调课程学习 |
| 43 | http://arxiv.org/abs/2507.07376v1 | PILOC: A Pheromone Inverse Guidance Mechanism and Local-Communication Framework for Dynamic Target Search of Multi-Agent in Unknown Environments | 信息素逆引导机制结合局部通信，无需全局先验 | 动态未知环境下目标搜索难，依赖全局通信 | 多智能体搜救 (MASAR) |

[返回目录](#目录)

<a id="cat-13"></a>

## Agent工具使用与环境交互

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2507.01489v1 | Agent-as-Tool: A Study on the Hierarchical Decision Making with Reinforcement Learning | 分层框架分离工具调用与推理过程，减轻模型推理负担 | 模型同时决策工具与推理的负担及冗余信息干扰 | 强化学习推理与工具调用 |
| 2 | http://arxiv.org/abs/2507.03018v1 | OpenTable-R1: A Reinforcement Learning Augmented Tool Agent for Open-Domain Table Question Answering | 强化学习增强工具代理用于开放域表格 QA，端到端工具调用 | 表格 QA 依赖静态检索及封闭域答案限制 | 开放域表格问答 |
| 3 | http://arxiv.org/abs/2507.02592v1 | WebSailor: Navigating Super-human Reasoning for Web Agent | 后训练方法赋予 Web 代理超人推理能力，减少极端不确定性 | 开源模型在复杂信息寻求任务差距及不确定性导航 | 复杂信息寻求与 Web 导航 |
| 4 | http://arxiv.org/abs/2508.03700v5 | MagicGUI: A Foundational Mobile GUI Agent with Scalable Data Pipeline and Reinforcement Fine-tuning | 构建大规模 GUI 数据集，强化学习微调提升感知与 grounding | 移动 GUI 环境中感知、grounding 与推理面临关键挑战 | 移动设备 GUI 自动化操作 |
| 5 | http://arxiv.org/abs/2507.15296v1 | Butterfly Effects in Toolchains: A Comprehensive Analysis of Failed Parameter Filling in LLM Tool-Agent Systems | 构建参数失败分类法，分析输入源与失败类别的相关性 | 工具 Agent 范式执行中参数填充失败限制有效性 | LLM 工具 Agent 系统可靠性 |
| 6 | http://arxiv.org/abs/2507.16853v1 | MobileUse: A GUI Agent with Hierarchical Reflection for Autonomous Mobile Operation | 分层反思架构实现错误恢复，主动探索模块解决冷启动问题 | 真实移动场景长程任务执行难，错误恢复与冷启动是挑战 | 移动设备自主任务操作 |
| 7 | http://arxiv.org/abs/2507.10844v1 | LLM-Guided Agentic Object Detection for Open-World Understanding | 提出 LAOD 框架，利用 LLM 生成场景特定对象名进行零样本检测。 | 解决开放世界物体检测依赖固定类别集和用户提示的问题。 | 开放世界视觉理解 |
| 8 | http://arxiv.org/abs/2507.07998v3 | PyVision: Agentic Vision with Dynamic Tooling | 交互式框架使 MLLM 自主生成执行 Python 视觉工具 | 视觉推理受限于预定义工作流与静态工具集 | 多模态视觉推理 |
| 9 | http://arxiv.org/abs/2507.20280v1 | SciToolAgent: A Knowledge Graph-Driven Scientific Agent for Multi-Tool Integration | 科学知识图谱驱动的工具选择与执行 | LLM难以无缝集成和编排多个科学工具 | 生物学、化学、材料科学研究 |
| 10 | http://arxiv.org/abs/2507.20666v1 | MIMII-Agent: Leveraging LLMs with Function Calling for Relative Evaluation of Anomalous Sound Detection | LLM解释故障描述自动选择音频转换函数 | 传统数据增强方法产生不现实声音限制可扩展性 | 机器异常声音检测系统评估 |
| 11 | http://arxiv.org/abs/2507.23096v1 | ChatVis: Large Language Model Agent for Generating Scientific Visualizations | 链式思维简化与检索增强提示生成 | 解决 LLM 难以生成专业科学可视化代码问题 | 科学可视化任务 |
| 12 | http://arxiv.org/abs/2507.16037v1 | A Pilot Study on LLM-Based Agentic Translation from Android to iOS | 多Agent链考虑依赖、规范、程序结构和控制流的跨平台翻译 | LLM跨平台应用翻译性能、优势和局限性未充分探索 | Android到iOS移动应用迁移 |
| 13 | http://arxiv.org/abs/2507.16044v3 | Making REST APIs Agent-Ready: From OpenAPI to MCP Servers for Tool-Augmented LLMs | AutoMCP编译器从OpenAPI规范自动生成MCP服务器实现 | MCP服务器构建手动重复，需编写胶水代码和配置 | 工具增强型LLM集成 |
| 14 | http://arxiv.org/abs/2507.05720v1 | MobileGUI-RL: Advancing Mobile Mobile GUI Agent through Reinforcement Learning in Online Environment | 在线环境中通过强化学习训练 GUI 智能体，合成课程 | 离线训练导致过拟合，未见环境策略脆弱 | 移动设备 GUI 自动化任务 |
| 15 | http://arxiv.org/abs/2507.05791v5 | GTA1: GUI Test-time Scaling Agent | 测试时缩放选择动作提案，强化学习改进视觉定位 | 广阔动作空间规划难，高分辨率界面定位不准 | 跨平台 GUI 任务自动化 |

[返回目录](#目录)

<a id="cat-14"></a>

## 低代码/无代码Agent平台

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2507.15559v1 | FlowForge: Guiding the Creation of Multi-agent Workflows with Design Space Visualization as a Thinking Scaffold | 交互式可视化工具，结构化探索设计空间并提供模式指导 | 设计最优工作流挑战大，依赖直觉导致设计固定或低效 | 多智能体工作流设计与创建 |
| 2 | http://arxiv.org/abs/2507.13140v1 | LightAutoDS-Tab: Multi-AutoML Agentic System for Tabular Data | 结合 LLM 代码生成与 AutoML 工具，构建多 AutoML 代理系统。 | 解决 AutoML 效率受限于特定底层工具及管道设计灵活性。 | 数据科学自动化 |

[返回目录](#目录)

<a id="cat-15"></a>

## Agent可解释性与透明度

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2507.07848v2 | "So, Tell Me About Your Policy...": Distillation of interpretable policies from Deep Reinforcement Learning agents | 利用优势函数提取可解释策略，保留专家行为特征 | 深度强化学习策略缺乏可解释性，难用于关键任务 | 关键任务决策系统 |
| 2 | http://arxiv.org/abs/2507.18607v1 | Explainable Mapper: Charting LLM Embedding Spaces Using Perturbation-Based Explanation and Verification Agents | 基于扰动的解释与验证 Agent 标注嵌入空间 | 手动探索 LLM 嵌入空间拓扑结构费力 | LLM 嵌入空间分析 |
| 3 | http://arxiv.org/abs/2507.22414v2 | AutoCodeSherpa: Symbolic Explanations in AI Coding Agents | 提供可执行的符号公式解释 | 解决代码 agent 动作缺乏信任证据问题 | 工业软件工作流 |

[返回目录](#目录)
