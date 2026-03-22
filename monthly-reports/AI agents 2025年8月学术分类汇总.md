# AI agents 2025年8月学术分类汇总

共收录 585 篇论文，按研究方向分类整理如下。

## 目录

- [多Agent协作与通信（56篇）](#cat-01)
- [Agent规划与推理（21篇）](#cat-02)
- [Agent架构与框架设计（72篇）](#cat-03)
- [基于Agent的应用系统（122篇）](#cat-04)
- [Agent安全与对齐（58篇）](#cat-05)
- [Agent评测与基准（51篇）](#cat-06)
- [Agent记忆与知识管理（23篇）](#cat-07)
- [多Agent强化学习（47篇）](#cat-08)
- [Agent学习与自进化（34篇）](#cat-09)
- [人机协作Agent（27篇）](#cat-10)
- [低代码/无代码Agent平台（2篇）](#cat-11)
- [具身智能Agent（23篇）](#cat-12)
- [Agent可解释性与透明度（3篇）](#cat-13)
- [Agent工具使用与环境交互（19篇）](#cat-14)
- [Agent仿真与社会模拟（27篇）](#cat-15)

<a id="cat-01"></a>

## 多Agent协作与通信

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2508.01815v1 | AGENTICT$^2$S:Robust Text-to-SPARQL via Agentic Collaborative Reasoning over Heterogeneous Knowledge Graphs for the Circular Economy | 模块化Agent框架，调度器分配子目标，两阶段验证器检测查询有效性 | 跨多图推理、低资源领域泛化性差 | 循环经济领域知识图谱问答 |
| 2 | http://arxiv.org/abs/2508.02015v1 | A Group Consensus-Driven Auction Algorithm for Cooperative Task Allocation Among Heterogeneous Multi-Agents | 基于群体共识的异构拍卖算法，启发式聚类减少共识时间 | 异构多任务多Agent任务分配误差大 | 自动化仓库机器人任务分配 |
| 3 | http://arxiv.org/abs/2508.02188v3 | Whispering Agents: An Event-driven Covert Communication Protocol For the Internet of Agents | 隐蔽事件通道协议，存储/时序/行为三维度 covert communication | Agent间通信行为本身易被监控分析 | Internet of Agents隐私保护 |
| 4 | http://arxiv.org/abs/2508.02826v1 | TransAM: Transformer-Based Agent Modeling for Multi-Agent Systems via Local Trajectory Encoding | Transformer编码局部轨迹到其他Agent策略嵌入空间 | 实际应用中无法获取其他Agent完整轨迹 | 合作/竞争/混合多Agent环境 |
| 5 | http://arxiv.org/abs/2508.02912v4 | Communicating Plans, Not Percepts: Scalable Multi-Agent Coordination with Embodied World Models | 基于具身世界模型的意图通信，压缩计划为消息 | 部分可观测下多Agent协调困难 | 合作任务分配、具身AI |
| 6 | http://arxiv.org/abs/2508.00280v1 | WMAS: A Multi-Agent System Towards Intelligent and Customized Wireless Networks | 基于强化学习优化多智能体对话拓扑结构 | 解决多智能体协作中的故障风险与无限循环 | 无线网络用户设备服务 |
| 7 | http://arxiv.org/abs/2508.00391v1 | Cued-Agent: A Collaborative Multi-Agent System for Automatic Cued Speech Recognition | 四子智能体协作系统，动态整合手语与唇语特征 | 解决手唇运动时间异步与多模态融合训练数据不足 | 听障人士辅助语音识别 |
| 8 | http://arxiv.org/abs/2508.00401v2 | Theory of Mind Using Active Inference: A Framework for Multi-Agent Cooperation | 在主动推理中实现心智理论，无需显式通信 | 解决多智能体合作中的信念理解与冗余努力 | 多智能体避障与觅食仿真 |
| 9 | http://arxiv.org/abs/2508.00554v3 | ContestTrade: A Multi-Agent Trading System Based on Internal Contest Mechanism | 内部竞赛机制的多智能体交易系统的实时评估排名 | 解决 LLM 交易系统对市场噪声敏感与性能不稳定 | 金融量化交易与投资决策 |
| 10 | http://arxiv.org/abs/2508.01531v1 | Revisiting Gossip Protocols: A Vision for Emergent Coordination in Agentic Multi-Agent Systems | 重访 Gossip 协议作为智能体 emergent 协调的补充层 | 解决规模化智能体平台中灵活去中心化协调需求 | 大规模去中心化多智能体系统 |
| 11 | http://arxiv.org/abs/2508.07092v1 | Communication-Efficient Multi-Agent 3D Detection via Hybrid Collaboration | 提出混合协作机制，自适应整合感知输出与原始观测消息。 | 解决协作 3D 检测中性能与通信带宽的权衡瓶颈。 | 3D 目标检测 |
| 12 | http://arxiv.org/abs/2508.07720v1 | Toward Goal-Oriented Communication in Multi-Agent Systems: An overview | 综述目标导向通信， bridging 信息论、通信理论与机器学习。 | 解决传统通信范式忽视交换信息任务相关性的问题。 | 多 Agent 系统通信 |
| 13 | http://arxiv.org/abs/2508.03329v2 | Industrial LLM-based Code Optimization under Regulation: A Mixture-of-Agents Approach | 采用混合代理方法合成代码，在合规环境下实现成本与速度优化 | 解决 regulated industry 中 LLM 代码优化的合规与成本问题 | 受监管行业的工业代码优化 |
| 14 | http://arxiv.org/abs/2508.03404v2 | Visual Document Understanding and Reasoning: A Multi-Agent Collaboration Framework with Agent-Wise Adaptive Test-Time Scaling | 提出多代理协作框架，动态分配计算资源以处理视觉文档理解 | 解决单体模型在文档推理中认知过载与事实准确性问题 | 视觉文档理解与推理 |
| 15 | http://arxiv.org/abs/2508.04575v1 | Beyond Brainstorming: What Drives High-Quality Scientific Ideas? Lessons from Multi-Agent Collaboration | 验证结构化多代理讨论优于 solitary ideation，认知多样性驱动质量 | 解决单代理 refinement 限制创造力与知识边界问题 | 科学研究提案生成 |
| 16 | http://arxiv.org/abs/2508.04903v3 | RCR-Router: Efficient Role-Aware Context Routing for Multi-Agent LLM Systems with Structured Memory | 动态选择语义相关记忆子集，实现高效自适应多代理协作 | 解决静态路由导致 token 消耗过多与记忆暴露冗余问题 | 多代理 LLM 系统 |
| 17 | http://arxiv.org/abs/2508.05996v2 | Mediator-Guided Multi-Agent Collaboration among Open-Source Models for Medical Decision-Making | 中介引导多智能体协作框架，使多个 VLM 专家智能体交换反思输出 | 多模态医疗决策中 VLM 指令遵循与自我反思能力弱 | 医疗多模态决策 |
| 18 | http://arxiv.org/abs/2508.06110v1 | PanelTR: Zero-Shot Table Reasoning Framework Through Multi-Agent Scientific Discussion | 利用 LLM 代理科学家进行结构化科学讨论，实现零样本表格推理 | 表格推理依赖标注数据，LLM 表现不如监督模型 | 表格推理与验证 |
| 19 | http://arxiv.org/abs/2508.09549v2 | CS-Agent: LLM-based Community Search via Dual-agent Collaboration | 双智能体协作框架，Solver 与 Validator 迭代 refinement | 解决 LLM 在社区搜索中输出偏见及无意义结果问题 | 图分析与社区搜索 |
| 20 | http://arxiv.org/abs/2508.09889v4 | Profile-Aware Maneuvering: A Dynamic Multi-Agent System for Robust GAIA Problem Solving by AWorld | 执行智能体受 Guard 监督，基于性能指纹动态干预 | 解决扩展上下文及噪声工具输出削弱系统可靠性问题 | 复杂现实问题解决 |
| 21 | http://arxiv.org/abs/2508.09893v1 | RAGulating Compliance: A Multi-Agent Knowledge Graph for Regulatory QA | 集成监管三元组 KG 与 RAG， orchestrated agent pipeline | 解决监管合规 QA 中精确性及领域专业知识挑战问题 | 法律合规与审计问答 |
| 22 | http://arxiv.org/abs/2508.10143v1 | MCP-Orchestrated Multi-Agent System for Automated Disinformation Detection | 四智能体 ensemble，MCP 编排共享上下文及实时学习 | 解决数字平台虚假信息传播及信息完整性挑战问题 | 虚假信息检测 |
| 23 | http://arxiv.org/abs/2508.15809v3 | Chain-of-Query: Unleashing the Power of LLMs in SQL-Aided Table Understanding via Multi-Agent Collaboration | 多智能体框架，分离 SQL 机械推理与 LLM 逻辑推理 | 表格结构复杂导致 SQL 生成错误及误差传播 | 表格数据理解与分析 |
| 24 | http://arxiv.org/abs/2508.11070v1 | From Individual to Multi-Agent Algorithmic Recourse: Minimizing the Welfare Gap via Capacitated Bipartite Matching | 多层优化框架，将多主体交互建模为容量加权二分匹配 | 个体福利优化忽视多主体资源竞争与系统级福利 | 算法救济与资源分配 |
| 25 | http://arxiv.org/abs/2508.11733v2 | SafeSieve: From Heuristics to Experience in Progressive Pruning for LLM-based Multi-Agent Communication | 渐进式剪枝算法，结合语义评估与性能反馈 | 多智能体系统通信冗余，Token 开销过大 | 多智能体协作效率 |
| 26 | http://arxiv.org/abs/2508.11995v1 | AgentCDM: Enhancing Multi-Agent Collaborative Decision-Making via ACH-Inspired Structured Reasoning | 结构化推理范式，基于 ACH 减轻认知偏差 | 协作决策依赖独裁或投票，未充分利用集体智慧 | 多智能体协作决策 |
| 27 | http://arxiv.org/abs/2508.12314v1 | Synchronization Dynamics of Heterogeneous, Collaborative Multi-Agent AI Systems | 桥接同步理论与多智能体 AI，适配 Kuramoto 模型 | 缺乏设计分析优化可扩展自适应多智能体系统的数学基础 | 多智能体系统协同 |
| 28 | http://arxiv.org/abs/2508.15819v1 | Agent Communications toward Agentic AI at Edge -- A Case Study of the Agent2Agent Protocol | 评估 A2A 协议在边缘计算挑战下的有效性 | 现有协议未充分考虑边缘计算特殊挑战 | 边缘智能代理通信 |
| 29 | http://arxiv.org/abs/2508.14635v1 | Can LLM Agents Solve Collaborative Tasks? A Study on Urgency-Aware Planning and Coordination | 评估LLM Agent在结构化救援任务中的协作能力 | 多Agent任务分工、优先级排序、合作规划问题 | 受害者救援等多Agent协作场景 |
| 30 | http://arxiv.org/abs/2508.14654v1 | Entropy-Constrained Strategy Optimization in Urban Floods: A Multi-Agent Framework with LLM and Knowledge Graph Integration | 分层多Agent框架集成知识引导和熵约束生成 | 城市洪水应急调度中多目标权衡和策略不稳定问题 | 城市洪水应急响应系统 |
| 31 | http://arxiv.org/abs/2508.15030v4 | Collab-REC: An LLM-based Agentic Framework for Balancing Recommendations in Tourism | 三Agent多轮协商机制平衡推荐多样性 | 旅游推荐中流行度偏差、过度旅游问题 | 旅游推荐系统 |
| 32 | http://arxiv.org/abs/2508.15447v2 | From Bits to Boardrooms: A Cutting-Edge Multi-Agent LLM Framework for Business Excellence | CTMDP动态Agent建模+熵度量+Stackelberg博弈 | 企业决策中操作分析与战略目标碎片化问题 | 复杂企业决策支持系统 |
| 33 | http://arxiv.org/abs/2508.15876v1 | DeepMEL: A Multi-Agent Collaboration Framework for Multimodal Entity Linking | 四专用Agent角色分工实现端到端跨模态链接 | 多模态实体链接中上下文不完整、跨模态融合粗糙问题 | 多模态知识图谱实体链接 |
| 34 | http://arxiv.org/abs/2508.15510v1 | Super-additive Cooperation in Language Model Agents | 团队内部动态+外部竞争提升LLM Agent合作水平 | 理解AI Agent在复杂社会场景中的合作倾向问题 | 多Agent AI系统价值对齐设计 |
| 35 | http://arxiv.org/abs/2508.17068v3 | Anemoi: A Semi-Centralized Multi-agent System Based on Agent-to-Agent Communication MCP server from Coral Protocol | 半中心化架构，支持Agent间结构化直接通信 | 传统中心化MAS依赖规划器，Agent间通信有限 | 通用多Agent任务协作 |
| 36 | http://arxiv.org/abs/2508.17205v1 | Multi-Agent Visual-Language Reasoning for Comprehensive Highway Scene Understanding | 混合专家策略：大VLM生成CoT提示引导小VLM推理 | 多任务感知需平衡精度与计算效率 | 高速公路交通监控与预警 |
| 37 | http://arxiv.org/abs/2508.18321v3 | LLMs Can't Handle Peer Pressure: Crumbling under Multi-Agent Social Interactions | KAIROS基准评估LLM在社交压力下的决策韧性 | LLM在多Agent社交动态中易受误导 | 多Agent集体智能系统 |
| 38 | http://arxiv.org/abs/2508.17536v2 | Debate or Vote: Which Yields Better Decisions in Multi-Agent Large Language Models? | 理论证明辩论本身不提升期望正确率，多数投票贡献主要增益 | MAD有效性驱动因素不清晰 | 多Agent决策系统优化 |
| 39 | http://arxiv.org/abs/2508.17720v1 | RepoTransAgent: Multi-Agent LLM Framework for Repository-Aware Code Translation | 三Agent分解：上下文检索+动态提示+迭代修正，RAG增强 | 现有方法上下文理解不足，错误纠正机制欠缺 | 跨编程语言代码库翻译 |
| 40 | http://arxiv.org/abs/2508.18108v1 | SentiMM: A Multimodal Multi-Agent Framework for Sentiment Analysis in Social Media | 专用Agent处理文本/视觉，知识检索增强上下文 | 多模态情感分析缺乏跨模态融合和外部知识 | 社交媒体多模态情感分析 |
| 41 | http://arxiv.org/abs/2508.12981v1 | Analyzing Information Sharing and Coordination in Multi-Agent Planning | 评估笔记本信息共享与编排 Agent 对长 horizon 规划任务误差影响 | 解决长周期多约束规划中信息幻觉及复杂依赖协调挑战问题 | 旅行规划任务 |
| 42 | http://arxiv.org/abs/2508.13118v2 | AutoBnB-RAG: Enhancing Multi-Agent Incident Response with Retrieval-Augmented Generation | 扩展 AutoBnB 框架集成 RAG，支持多 Agent 协作调查网络安全事件 | 解决 LLM 推理缺乏外部知识访问及协同决策质量受限问题 | 网络安全事件响应 |
| 43 | http://arxiv.org/abs/2508.13439v1 | Structured Prompting and Multi-Agent Knowledge Distillation for Traffic Video Interpretation and Risk Inference | 编排双 VLM 生成伪标注，知识蒸馏至轻量模型实现实时风险监测 | 解决传统方法可扩展性差及复杂动态环境泛化能力不足问题 | 智能交通系统 |
| 44 | http://arxiv.org/abs/2508.13602v2 | PersonaVlog: Personalized Multimodal Vlog Generation with Multi-Agent Collaboration and Iterative Self-Correction | 提出多 Agent 协作框架，基于 MLLM 生成提示及迭代自校正多模态内容 | 解决现有 Vlog 生成缺乏动态性及个人表达及多模态协作问题 | 个性化 Vlog 生成 |
| 45 | http://arxiv.org/abs/2508.13920v2 | LLMind 2.0: Distributed IoT Automation with Natural Language M2M Communication and Lightweight LLM Agents | 嵌入轻量 LLM 设备 Agent，采用自然语言 M2M 通信克服设备异构性 | 解决集中式方法难以 scale 跨异构大规模 IoT 系统自动化问题 | 分布式 IoT 自动化 |
| 46 | http://arxiv.org/abs/2508.18797v1 | CausalMACE: Causality Empowered Multi-Agents in Minecraft Cooperative Tasks | 引入因果规划框架，管理子任务依赖，增强多智能体在 Minecraft 中的协作。 | 解决复杂长序列任务中单智能体效率低且多智能体协作研究 scarce 的问题。 | Minecraft 游戏多智能体协作 |
| 47 | http://arxiv.org/abs/2508.20370v1 | Adaptive Root Cause Localization for Microservice Systems with Multi-Agent Recursion-of-Thought | 提出多 Agent 递归思维框架，整合多源数据与工具辅助分析。 | 解决微服务系统故障根因定位依赖预定义 schema 且缺乏可解释性问题。 | 微服务系统可靠性保障 |
| 48 | http://arxiv.org/abs/2508.20508v1 | Collaborative Evolution of Intelligent Agents in Large-Scale Microservice Systems | 基于图表示学习与博弈驱动策略优化，实现服务 Agent 协同进化。 | 解决大规模微服务架构中依赖复杂与动态拓扑治理难题。 | 大型微服务系统治理 |
| 49 | http://arxiv.org/abs/2508.21304v3 | ORCA: ORchestrating Causal Agent | 引入多 Agent 框架维护共享状态与人工检查点，确保因果分析一致性。 | 解决关系数据库因果分析中阶段依赖复杂且假设不一致问题。 | 关系数据库因果分析 |
| 50 | http://arxiv.org/abs/2509.00132v1 | CoComposer: LLM Multi-agent Collaborative Music Composition | 五个 Agent 协作模拟传统作曲工作流，提升音乐质量与可控性。 | 解决 AI 音乐生成时长受限、质量低且缺乏可编辑性问题。 | 音乐创作与生成 |
| 51 | http://arxiv.org/abs/2508.21720v1 | PosterForest: Hierarchical Multi-Agent Collaboration for Scientific Poster Generation | 引入 Poster Tree 层次表示，多 Agent 迭代协调内容与布局。 | 解决科学海报生成忽略层次结构及图文语义整合不足问题。 | 学术海报自动化生成 |
| 52 | http://arxiv.org/abs/2508.21803v1 | Automated Clinical Problem Detection from SOAP Notes using a Collaborative Multi-Agent LLM Architecture | 模拟临床团队辩论过程，动态分配专家 Agent 达成共识。 | 解决单一模型处理复杂临床叙事缺乏鲁棒性与可解释性问题。 | 临床问题检测与决策支持 |
| 53 | http://arxiv.org/abs/2509.00481v1 | Multi-Agent Data Visualization and Narrative Generation | 结合混合多 Agent 架构与确定性组件，自动化数据到沟通流程。 | 解决数据可视化中缺乏自动化叙事生成及人类协作可持续性问题。 | 数据可视化与洞察沟通 |
| 54 | http://arxiv.org/abs/2509.00581v2 | SQL-of-Thought: Multi-agentic Text-to-SQL with Guided Error Correction | 分解 Text2SQL 任务为多阶段，引入分类指导的动态错误修正。 | 解决 Text2SQL 系统依赖静态执行修正且缺乏推理规划问题。 | 自然语言转 SQL 查询 |
| 55 | http://arxiv.org/abs/2509.00710v1 | On Verifiable Legal Reasoning: A Multi-Agent Framework with Formalized Knowledge Representations | 分解法律推理为知识获取与应用，形式化规则以增强可验证性。 | 解决法律推理中自然语言理解与符号推理 bridging 困难问题。 | 法律 statutory 计算与推理 |
| 56 | http://arxiv.org/abs/2509.00761v2 | L-MARS: Legal Multi-Agent Workflow with Orchestrated Reasoning and Agentic Search | 分解查询为子问题，迭代搜索验证以 grounding 权威法律。 | 解决法律问答中幻觉多、不确定性高且缺乏精确检索问题。 | 法律问答与检索系统 |

[返回目录](#目录)

<a id="cat-02"></a>

## Agent规划与推理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2508.01858v2 | Web-CogReasoner: Towards Knowledge-Induced Cognitive Reasoning for Web Agents | 知识驱动CoT推理框架，分解为知识学习与认知过程两阶段 | Web Agent缺乏结构化知识支撑认知推理 | 通用Web Agent任务 |
| 2 | http://arxiv.org/abs/2508.03038v1 | Tree-of-Reasoning: Towards Complex Medical Diagnosis via Multi-Agent Reasoning with Evidence Tree | 树结构记录推理路径和临床证据，交叉验证机制确保一致性 | 复杂医疗诊断缺乏推理深度导致错误 | 复杂医疗诊断 |
| 3 | http://arxiv.org/abs/2508.00344v4 | PilotRL: Training Language Model Agents via Global Planning-Guided Progressive Reinforcement Learning | 全局规划引导的渐进式强化学习训练框架 | 解决长程任务中规划与执行协调及泛化能力 | 大语言模型智能体训练 |
| 4 | http://arxiv.org/abs/2508.07466v1 | Grounding Natural Language for Multi-agent Decision-Making with Multi-agentic LLMs | 扩展 LLM 能力，集成多 Agent 决策算法，关注提示工程与记忆架构。 | 解决多 Agent 决策中语言 grounding 及协作策略清晰性问题。 | 多 Agent 决策 |
| 5 | http://arxiv.org/abs/2508.07468v3 | CP-Agent: Agentic Constraint Programming | 使用 ReAct 框架与持久 IPython 内核，迭代执行代码并 refine 约束模型。 | 解决自然语言到形式约束模型翻译需要专业知识的问题。 | 约束规划 |
| 6 | http://arxiv.org/abs/2508.08092v1 | How Quantum Agents Can Change Which Strategies Are More Complex | 展示复杂性结论依赖于 Agent 是否处理量子信息，推导内存下界。 | 解决经典与量子 Agent 策略复杂性度量不一致的理论问题。 | 量子 Agent 理论 |
| 7 | http://arxiv.org/abs/2508.03824v5 | What Do Agents Think One Another Want? Level-2 Inverse Games for Inferring Agents'Estimates of Others'Objectives | 提出 Level-2 推理框架，推断智能体对他体目标的估计 | 解决 decentralized 场景中智能体目标认知冲突问题 | 城市驾驶与谈判博弈 |
| 8 | http://arxiv.org/abs/2508.04118v1 | AgREE: Agentic Reasoning for Knowledge Graph Completion on Emerging Entities | 结合迭代检索与多步推理，动态构建新兴实体知识图谱三元组 | 解决 KGC 对新兴实体信息捕获不足与需大量监督问题 | 开放域知识图谱补全 |
| 9 | http://arxiv.org/abs/2508.08816v1 | Efficient Agent: Optimizing Planning Capability for Multimodal Retrieval Augmented Generation | 动态编排多模态工具，一次性 mRAG 规划策略 | 解决 mRAG 检索策略僵化及视觉信息利用不足问题 | 多模态检索增强生成 |
| 10 | http://arxiv.org/abs/2508.16383v1 | GLARE: Agentic Reasoning for Legal Judgment Prediction | 动态调用不同模块获取关键法律知识增强推理 | 现有LLM缺乏法律知识导致推理不足问题 | 法律判决预测系统 |
| 11 | http://arxiv.org/abs/2508.16998v1 | DeAR: Dual-Stage Document Reranking with Reasoning Agents via LLM Distillation | 双阶段重排序：蒸馏点式评分+列表式推理 | 单模型难以平衡细粒度评分与跨文档分析 | 文档检索与重排序系统 |
| 12 | http://arxiv.org/abs/2508.19279v1 | FLAIRR-TS -- Forecasting LLM-Agents with Iterative Refinement and Retrieval for Time Series | 测试时提示优化：预测Agent+优化Agent迭代 refinement | 为每个任务手工设计提示繁琐且临时 | 跨领域时间序列预测 |
| 13 | http://arxiv.org/abs/2508.17258v1 | Are You Sure You're Positive? Consolidating Chain-of-Thought Agents with Uncertainty Quantification for Aspect-Category Sentiment Analysis | 多CoT Agent整合+token级不确定性量化 | 新领域标注数据稀缺，监督方法迁移性差 | 细粒度情感分析 |
| 14 | http://arxiv.org/abs/2508.12800v3 | Atom-Searcher: Enhancing Agentic Deep Research via Fine-Grained Atomic Thought Reward | 提出原子思维范式与奖励模型，集成课程灵感奖励调度加速收敛 | 解决 outcome-based RL 梯度冲突及奖励稀疏导致性能受限问题 | 深度研究 Agent |
| 15 | http://arxiv.org/abs/2508.12840v4 | Scaling Multi-Agent Epistemic Planning through GNN-Derived Heuristics | 利用 GNN 学习认知状态模式，推导启发式策略指导多智能体认知规划 | 解决认知规划状态空间指数爆炸及现有启发式不可用问题 | 多智能体认知规划 |
| 16 | http://arxiv.org/abs/2508.13721v1 | CausalPlan: Empowering Efficient LLM Multi-Agent Collaboration Through Causality-Driven Planning | 集成结构因果推理到 LLM 规划，学习因果图指导动作选择 | 解决小模型依赖表面相关性导致协作任务因果无效或不连贯问题 | 多 Agent 协作规划 |
| 17 | http://arxiv.org/abs/2508.19076v1 | HiPlan: Hierarchical Planning for LLM-Based Agents with Adaptive Global-Local Guidance | 分层规划框架，提供自适应全局 - 局部指导，分解任务为里程碑与步骤提示。 | 解决 LLM  Agent 在复杂长程规划中缺乏宏观指导与持续监督的问题。 | LLM 智能体复杂任务规划 |
| 18 | http://arxiv.org/abs/2508.19598v1 | Encouraging Good Processes Without the Need for Good Answers: Reinforcement Learning for LLM Agent Planning | 提出 RLTR 框架，解耦训练过程，基于工具使用完整性奖励优化规划模块。 | 解决端到端训练目标分配不平衡与可验证数据稀缺阻碍规划能力提升的问题。 | LLM 智能体动作规划 |
| 19 | http://arxiv.org/abs/2509.04472v3 | RECAP: REwriting Conversations for Intent Understanding in Agentic Planning | 提出意图重写基准，将对话重构为用户目标的简洁表示。 | 解决开放域对话中意图检测模糊导致下游规划 brittle 问题。 | 对话 Agent 意图理解与规划 |
| 20 | http://arxiv.org/abs/2509.00483v1 | Exploring Decision-Making Capabilities of LLM Agents: An Experimental Study on Jump-Jump Game | 利用 Jump-Jump 游戏测试 LLM 空间推理与策略规划能力。 | 解决缺乏简单环境评估 LLM 基础决策与物理建模能力问题。 | LLM 决策能力实验研究 |
| 21 | http://arxiv.org/abs/2509.01022v2 | Symbolic Planning and Multi-Agent Path Finding in Extremely Dense Environments with Unassigned Agents | 定义块重排问题，提出五种基于搜索的解决方案算法。 | 解决极高密度环境中多 Agent 路径规划与块重排效率低问题。 | 仓库管理与物流规划 |

[返回目录](#目录)

<a id="cat-03"></a>

## Agent架构与框架设计

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2508.01875v3 | StreamAgent: Towards Anticipatory Agents for Streaming Video Understanding | 预期Agent预测未来任务相关时空区域，流式KV-cache记忆机制 | 流式视频理解缺乏任务驱动规划和未来预期 | 自动驾驶、智能监控等流式视频场景 |
| 2 | http://arxiv.org/abs/2508.02276v2 | CellForge: Agentic Design of Virtual Cell Models | 多Agent框架自主设计神经网络架构，协作推理发现新架构组件 | 虚拟细胞建模需跨学科 expertise，手动设计效率低 | 计算生物学、单细胞数据分析 |
| 3 | http://arxiv.org/abs/2508.02773v3 | Web3 x AI Agents: Landscape, Integrations, and Foundational Challenges | 首个Web3与AI Agent交叉综合分析，五维度 taxonomy | Web3与AI Agent融合缺乏系统分析 | Web3去中心化生态系统 |
| 4 | http://arxiv.org/abs/2508.02999v1 | AGENTiGraph: A Multi-Agent Knowledge Graph Framework for Interactive, Domain-Specific LLM Chatbots | 用户友好Agent驱动系统，自然语言操作知识图谱 | 非技术用户难以构建管理领域知识库 | 企业知识管理、教育/法律/医疗 |
| 5 | http://arxiv.org/abs/2508.03095v3 | Evolution of AI Agent Registry Solutions: Centralized, Enterprise, and Distributed Approaches | 分析五种Agent注册表方案，四维评估架构权衡 | Agent跨域运营缺乏可信发现基础设施 | Internet of AI Agents基础设施 |
| 6 | http://arxiv.org/abs/2508.03113v1 | NANDA Adaptive Resolver: Architecture for Dynamic Resolution of AI Agent Names | 动态微服务架构，上下文感知实时选择通信端点 | 静态端点解析限制分布式异构环境Agent通信 | Agent间通信基础设施 |
| 7 | http://arxiv.org/abs/2508.00356v1 | Analyze-Prompt-Reason: A Collaborative Agent-Based Framework for Multi-Image Vision-Language Reasoning | 双智能体协作框架，提示工程师与视觉推理者配合 | 解决多图像交错模态推理的上下文感知问题 | 多图像视觉语言推理任务 |
| 8 | http://arxiv.org/abs/2508.00414v2 | Cognitive Kernel-Pro: A Framework for Deep Research Agents and Agent Foundation Models Training | 开源多模块智能体框架，系统化构建训练数据 | 解决代理系统闭源依赖与高质量训练数据缺乏 | 深度研究智能体与基础模型 |
| 9 | http://arxiv.org/abs/2508.00429v4 | ReaGAN: Node-as-Agent-Reasoning Graph Agentic Network | 节点即智能体，结合检索增强生成构建全局关系 | 解决图神经网络中节点信息不平衡与全局语义缺失 | 图学习与节点分类任务 |
| 10 | http://arxiv.org/abs/2508.08283v1 | MinionsLLM: a Task-adaptive Framework For The Training and Control of Multi-Agent Systems Through Natural Language | 集成行为树与形式语法，实现自然语言控制多智能体 | 解决任意环境中多智能体系统的 syntactic 有效性 | 资源受限的多智能体控制 |
| 11 | http://arxiv.org/abs/2508.01005v1 | MAO-ARAG: Multi-Agent Orchestration for Adaptive Retrieval-Augmented Generation | 多智能体编排自适应 RAG，动态规划工作流 | 解决固定 RAG 管道在不同查询复杂度下性能成本失衡 | 问答系统与检索增强生成 |
| 12 | http://arxiv.org/abs/2508.01186v1 | A Survey on Agent Workflow -- Status and Future | 全面综述智能体工作流系统的功能与架构特征 | 解决智能体系统复杂性增加带来的可控性与安全性挑战 | 智能体工作流研究与开发 |
| 13 | http://arxiv.org/abs/2508.02744v2 | Large Language Model-based Data Science Agent: A Survey | 双视角框架连接通用智能体设计与数据科学 workflow | 解决 LLM 数据科学智能体缺乏系统性综述与设计原则 | 数据科学任务智能体 |
| 14 | http://arxiv.org/abs/2508.01581v1 | Polymorphic Combinatorial Frameworks (PCF): Guiding the Design of Mathematically-Grounded, Adaptive AI Agents | 数学基础组合框架指导自适应 AI 智能体参数空间设计 | 解决静态智能体架构在复杂动态环境中适应性不足 | 客户服务、医疗等动态环境 |
| 15 | http://arxiv.org/abs/2508.05668v3 | A Survey of LLM-based Deep Search Agents: Paradigm, Optimization, Evaluation, and Challenges | 系统分析搜索智能体的架构、优化、应用与评估 | 解决深度搜索智能体领域缺乏系统性分析与挑战梳理 | 基于 LLM 的深度搜索智能体 |
| 16 | http://arxiv.org/abs/2508.01696v3 | CoCoA: Collaborative Chain-of-Agents for Parametric-Retrieved Knowledge Synergy | 协作智能体链增强参数知识与检索知识显式协同 | 解决 RAG 中检索内容误导生成与知识利用不充分 | 开放域与多跳问答任务 |
| 17 | http://arxiv.org/abs/2508.07343v1 | A Survey on Agentic Service Ecosystems: Measurement, Analysis, and Optimization | 提出测量、分析、优化三步框架，分析智能体服务生态系统中群智涌现。 | 解决现有研究碎片化，缺乏统一方法论捕捉生态复杂性的问题。 | 智能体服务生态 |
| 18 | http://arxiv.org/abs/2508.07935v1 | SHIELDA: Structured Handling of Exceptions in LLM-Driven Agentic Workflows | 模块化运行时异常处理框架，链接异常与根本原因，支持阶段感知恢复。 | 解决 LLM Agent 工作流中异常处理表面化及恢复逻辑脆弱问题。 | Agent 工作流管理 |
| 19 | http://arxiv.org/abs/2508.08487v5 | MAViS: A Multi-Agent Framework for Long-Sequence Video Storytelling | 多 Agent 协作框架，涵盖脚本、镜头、角色及视频生成阶段。 | 解决长序列视频生成中辅助能力差及视觉质量次优问题。 | 视频故事生成 |
| 20 | http://arxiv.org/abs/2508.03345v1 | Adaptive AI Agent Placement and Migration in Edge Intelligence Systems | 提出边缘智能系统中 AI 代理放置与迁移的自适应框架，优化资源与延迟 | 解决边缘环境下 AI 代理部署延迟高与资源异构问题 | 动态边缘计算环境 |
| 21 | http://arxiv.org/abs/2508.03370v1 | A Closed-Loop Multi-Agent Framework for Aerodynamics-Aware Automotive Styling Design | 集成创意生成与工程验证闭环，实现端到端汽车造型设计自动化 | 平衡主观美学与客观空气动力学性能，加速开发周期 | 汽车 exterior 设计 |
| 22 | http://arxiv.org/abs/2508.03991v1 | Galaxy: A Cognition-Centered Framework for Proactive, Privacy-Preserving, and Self-Evolving LLM Agents | 提出 Cognition Forest 语义结构，统一认知架构与系统设计 | 解决 IPA 设计中 proactive 行为与隐私保护挑战 | 智能个人助手 |
| 23 | http://arxiv.org/abs/2508.04080v1 | GeoSR: Cognitive-Agentic Framework for Probing Geospatial Knowledge Boundaries via Iterative Self-Refinement | 嵌入地理原则的自修正代理推理框架，迭代提升空间预测质量 | 解决 LLM 空间一致性差与地理偏差问题 | 地理空间知识预测 |
| 24 | http://arxiv.org/abs/2508.11665v2 | StackPilot: Autonomous Function Agents for Scalable and Environment-Free Code Execution | 提出 Function-as-Agents 范式，实现语言无关的代码验证与执行 | 解决 LLM 生成代码验证依赖特定编译器与环境问题 | 代码生成验证与执行 |
| 25 | http://arxiv.org/abs/2508.04482v1 | OS Agents: A Survey on MLLM-based Agents for General Computing Devices Use | 全面 survey OS Agents  fundamentals，组件能力与评估协议 | 解决 OS Agents 研究分散缺乏 consolidated  overview 问题 | 通用计算设备代理 |
| 26 | http://arxiv.org/abs/2508.09171v1 | webMCP: Efficient AI-Native Client-Side Interaction for Agent-Ready Web Design | 嵌入结构化交互元数据至 Web 页面，降低 AI 代理理解开销 | 解决 AI 代理理解 Web 页面处理慢与成本高问题 | AI Web 辅助交互 |
| 27 | http://arxiv.org/abs/2508.05081v1 | Cognitive Duality for Adaptive Web Agents | 基于双过程理论，自适应切换快慢认知模式的 Web 智能体架构 | Web 导航中离线模仿与在线探索难以有效整合 | 通用 Web 智能体 |
| 28 | http://arxiv.org/abs/2508.05311v1 | A Novel Architecture for Symbolic Reasoning with Decision Trees and LLM Agents | 决策树符号推理与 LLM 生成能力混合架构，树作为可调用预言机 | 符号与神经模块松散耦合，缺乏可解释性 | 通用神经符号推理 |
| 29 | http://arxiv.org/abs/2508.05338v1 | The Term 'Agent' Has Been Diluted Beyond Utility and Requires Redefinition | 提出智能体重新定义框架，明确最低要求与多维谱系特征 | 术语"Agent"歧义大，阻碍研究沟通与评估复现 | AI 研究领域定义 |
| 30 | http://arxiv.org/abs/2509.25193v1 | Devstral: Fine-tuning Language Models for Coding Agent Applications | 轻量级开源代码智能体模型，针对代理软件开发进行设计与微调 | 现有大模型在代码智能体应用上性能与效率不平衡 | 代码智能体应用 |
| 31 | http://arxiv.org/abs/2508.06471v1 | GLM-4.5: Agentic, Reasoning, and Coding (ARC) Foundation Models | 开源混合专家大语言模型，支持思考与直接响应混合推理模式 | 现有模型在智能体、推理与编码任务上参数效率低 | 基础模型研发 |
| 32 | http://arxiv.org/abs/2508.06948v1 | Kairos: Low-latency Multi-Agent Serving with Shared LLMs and Excessive Loads in the Public Cloud | 多智能体编排系统，优化工作流感知优先级调度与内存感知分发 | 多智能体应用共享 LLM 负载过高，服务延迟性能低 | 多智能体云服务 |
| 33 | http://arxiv.org/abs/2508.09123v3 | OpenCUA: Open Foundations for Computer-Use Agents | 开源 CUA 框架，含标注基础设施及大规模数据集 | 解决最强大 CUA 系统细节封闭及研究访问受限问题 | 计算机使用智能体 |
| 34 | http://arxiv.org/abs/2508.09561v1 | Edge General Intelligence Through World Models and Agentic AI: Fundamentals, Solutions, and Challenges | 综述世界模型赋能边缘 Agentic AI 架构及挑战 | 解决世界模型在无线边缘集成及 EGI 实现问题 | 边缘计算与通用智能 |
| 35 | http://arxiv.org/abs/2508.10146v1 | Agentic AI Frameworks: Architectures, Protocols, and Design Challenges | 系统 review 领先框架，分析架构及通信协议 | 解决 Agentic AI 系统分类及互操作性挑战问题 | 智能体框架研究与设计 |
| 36 | http://arxiv.org/abs/2508.10494v1 | A Unified Multi-Agent Framework for Universal Multimodal Understanding and Generation | 解耦认知与审议阶段，符号多智能体协作共享文本空间 | 解决多模态理解与生成集成灵活性及扩展性问题 | 通用多模态理解与生成 |
| 37 | http://arxiv.org/abs/2508.11120v2 | Towards Reliable Multi-Agent Systems for Marketing Applications via Reflection, Memory, and Planning | RAMP 框架，迭代规划、工具调用与验证，配备长期记忆 | 营销任务中 LLM 系统可靠性低，输出质量不稳定 | 营销受众策划 |
| 38 | http://arxiv.org/abs/2508.11126v2 | AI Agentic Programming: A Survey of Techniques, Challenges, and Opportunities | 系统综述，提出智能体行为与系统架构分类法 | 缺乏对 AI 代理编程技术、挑战与机会的全面梳理 | 软件开发与代码生成 |
| 39 | http://arxiv.org/abs/2508.11957v1 | A Comprehensive Review of AI Agents: Transforming Possibilities in Technology and Beyond | 系统审查架构原则、组件与新兴范式，综合多领域见解 | 设计部署统一 AI 代理整合认知、规划与交互仍是挑战 | 通用 AI 代理系统发展 |
| 40 | http://arxiv.org/abs/2508.12257v1 | Structuring the Unstructured: A Systematic Review of Text-to-Structure Generation for Agentic AI with a Universal Evaluation Framework | 系统综述与通用评估框架，确立文本到结构为基础设 | 缺乏对方法、数据集与指标的综合合成 | 代理 AI 基础设施 |
| 41 | http://arxiv.org/abs/2508.12412v2 | LumiMAS: A Comprehensive Framework for Real-Time Monitoring and Enhanced Observability in Multi-Agent Systems | 三组件可观测性框架，实时检测与解释异常 | 现有框架忽视整个 MAS 相关失败，缺乏统一监控 | 多智能体系统监控 |
| 42 | http://arxiv.org/abs/2508.15066v3 | Osprey: Production-Ready Agentic AI for Safety-Critical Control Systems | 计划优先编排器+协调层+分类器的生产级框架 | 大科学设施控制中Agent可靠性与安全性不足问题 | 安全关键设施控制系统 |
| 43 | http://arxiv.org/abs/2508.15164v1 | ContextualLVLM-Agent: A Holistic Framework for Multi-Turn Visually-Grounded Dialogue and Complex Instruction Following | 记忆-感知-规划-执行迭代循环增强LVLM | 多轮视觉对话中上下文丢失和视觉幻觉问题 | 多模态对话与复杂指令跟随 |
| 44 | http://arxiv.org/abs/2508.16279v1 | AgentScope 1.0: A Developer-Centric Framework for Building Agentic Applications | 统一接口+可扩展模块+异步设计支持Agent应用开发 | 构建灵活高效工具基Agent应用缺乏开发者中心框架问题 | 可伸缩Agent应用开发 |
| 45 | http://arxiv.org/abs/2508.18298v2 | Murakkab: Resource-Efficient Agentic Workflow Orchestration in Cloud Platforms | 声明式抽象解耦工作流与执行配置，跨层优化 | Agentic工作流资源浪费、SLO难以保障 | 云端AI应用工作流编排 |
| 46 | http://arxiv.org/abs/2508.16987v1 | WebSight: A Vision-First Architecture for Robust Web Agents | 纯视觉感知Web Agent，模块化多Agent架构+情景记忆 | 传统Web Agent依赖HTML/DOM，鲁棒性差 | 网页自动化导航与交互 |
| 47 | http://arxiv.org/abs/2508.17281v2 | From Language to Action: A Review of Large Language Models as Autonomous Agents and Tool Users | 系统综述68个数据集，分析架构、认知机制、评估协议 | 缺乏对LLM Agent系统性梳理和未来方向 | LLM Agent研究领域 |
| 48 | http://arxiv.org/abs/2508.17692v1 | LLM-based Agentic Reasoning Frameworks: A Survey from Methods to Scenarios | 提出统一形式语言分类：单Agent/工具/多Agent方法 | 不同推理框架组织方式差异大，缺乏系统 taxonomy | LLM Agent推理框架研究 |
| 49 | http://arxiv.org/abs/2508.17778v2 | AgentRAN: An Agentic AI Architecture for Autonomous Control of Open 6G Networks | AI-RAN Factory持续生成改进Agent，自然语言意图驱动 | Open RAN依赖静态控制和人工操作 | 6G开放无线网络自主控制 |
| 50 | http://arxiv.org/abs/2508.18177v3 | Scene-Aware Vectorized Memory Multi-Agent Framework with Cross-Modal Differentiated Quantization VLMs for Visually Impaired Assistance | 跨模态差异化量化(38GB→11.3GB)+场景感知向量记忆 | VLM计算需求大，传统辅助技术缺乏集成智能 | 视障人士环境感知辅助 |
| 51 | http://arxiv.org/abs/2508.18406v1 | Toward Generalized Autonomous Agents: A Neuro-Symbolic AI Framework for Integrating Social and Technical Support in Education | 神经符号多Agent：RL导师+LLM同伴，统一教育本体 | 学生难以自主设定目标、跟踪进度、调整策略 | 数字化学习环境 |
| 52 | http://arxiv.org/abs/2508.18675v1 | Requirements Development and Formalization for Reliable Code Generation: A Multi-Agent Vision | ReDeFo：三Agent+形式化规范桥接自然语言与可执行代码 | LLM生成代码质量无保证，缺乏需求系统化建模 | 可靠代码自动生成 |
| 53 | http://arxiv.org/abs/2508.14111v2 | From AI for Science to Agentic Science: A Survey on Autonomous Scientific Discovery | 构建 Agentic Science 框架，统一过程、自主性与机制视角的科学发现范式 | 解决 AI 科学发现中自主性定义模糊及缺乏结构化范式问题 | 科学发现领域 |
| 54 | http://arxiv.org/abs/2508.12683v1 | A Taxonomy of Hierarchical Multi-Agent Systems: Design Patterns, Coordination Mechanisms, and Industrial Applications | 提出五维分层多智能体系统分类法，连接经典协调机制与现代 LLM | 解决分层 MAS 设计维度孤立及缺乏统一比较框架问题 | 工业复杂系统协调 |
| 55 | http://arxiv.org/abs/2508.12752v1 | Deep Research: A Survey of Autonomous Research Agents | 系统概述深度研究 pipeline，分析规划、检索、合成四阶段技术挑战 | 解决 LLM 内部知识边界受限及复杂任务自主执行难题 | 自主研究 Agent |
| 56 | http://arxiv.org/abs/2508.16644v3 | CountLoop: Training-Free High-Instance Image Generation via Iterative Agent Guidance | 引入 VLM 规划器与批评家迭代反馈，实现无训练高精度实例控制 | 解决扩散模型在高密度场景下物体计数不准及语义泄漏问题 | 图像生成控制 |
| 57 | http://arxiv.org/abs/2508.13732v2 | Self-Organizing Agent Network for LLM-based Workflow Automation | 提出自组织 Agent 网络，增量构建形式化网络封装结构单元 | 解决企业工作流嵌套复杂及 LLM 编排状态空间爆炸影响规划问题 | 企业工作流自动化 |
| 58 | http://arxiv.org/abs/2508.13787v1 | BetaWeb: Towards a Blockchain-enabled Trustworthy Agentic Web | 引入区块链 enabled 可信 Agentic Web，提出五阶段进化路线图 | 解决 Agentic 生态 fragmented 及隐私、数据管理、价值测量挑战 | 可信 Agentic Web |
| 59 | http://arxiv.org/abs/2508.13815v2 | COCO: Cognitive Operating System with Continuous Oversight for Multi-Agent Workflow Reliability | 提出连续监督认知操作系统，解耦错误检测与执行路径自适应校正 | 解决大规模多 Agent 系统错误 cascading 及下游加剧上游 inaccuracies 问题 | 多 Agent 工作流可靠性 |
| 60 | http://arxiv.org/abs/2508.18725v1 | Toward Edge General Intelligence with Agentic AI and Agentification: Concepts, Technologies, and Future Directions | 提出边缘通用智能与Agentification范式，系统梳理概念与 enabling 技术。 | 解决传统边缘智能静态模型无法适应动态异构场景的问题。 | 6G 网络与物联网边缘环境 |
| 61 | http://arxiv.org/abs/2508.19042v1 | A Concurrent Modular Agent: Framework for Autonomous LLM Agents | 并发模块化 Agent 框架， orchestrates 多个异步 LLM 模块保持行为连贯。 | 解决 Agent 架构中长期存在的意图涌现与故障容忍 difficulties 问题。 | 自主 LLM 智能体架构 |
| 62 | http://arxiv.org/abs/2508.19359v1 | Reflective Agreement: Combining Self-Mixture of Agents with a Sequence Tagger for Robust Event Extraction | 结合自混合 Agent 与判别式序列标记器，利用共识与反思推理解决歧义。 | 解决事件提取中判别模型召回率低与生成模型幻觉及不一致的问题。 | 鲁棒事件提取系统 |
| 63 | http://arxiv.org/abs/2508.19504v1 | Aegis: Taxonomy and Optimizations for Overcoming Agent-Environment Failures in LLM Agents | 提出 Agent-环境交互失败分类学，设计环境可观测性等优化提升成功率。 | 解决复杂真实环境中 LLM  Agent 成功率低且忽视系统环境作用的问题。 | LLM 智能体环境交互优化 |
| 64 | http://arxiv.org/abs/2508.20019v1 | Symphony: A Decentralized Multi-Agent Framework for Scalable Collective Intelligence | 去中心化多智能体系统，引入分布式账本、Beacon 选择与加权投票机制。 | 解决现有 LLM  Agent 框架依赖集中编排导致高成本与刚性拓扑的问题。 | 可扩展集体智能多智能体 |
| 65 | http://arxiv.org/abs/2508.20368v4 | AI-SearchPlanner: Modular Agentic Search via Pareto-Optimal Multi-Objective Reinforcement Learning | 解耦搜索规划与生成器架构，引入双奖励对齐与帕累托优化。 | 解决单一模型难以同时优化搜索规划与问答能力的问题。 | 冻结 QA 模型的搜索规划增强 |
| 66 | http://arxiv.org/abs/2508.21148v2 | A Survey of Scientific Large Language Models: From Data Foundations to Agent Frontiers | 系统综述 Sci-LLM 数据基础与 Agent 前沿，提出闭环系统范式。 | 解决科学数据异构多尺度导致模型表示与推理困难的问题。 | 科学大模型与自主 Agent |
| 67 | http://arxiv.org/abs/2508.21246v1 | HCQA: Hybrid Classical-Quantum Agent for Generating Optimal Quantum Sensor Circuits | 结合 DQN 与量子动作选择机制，自动生成最优量子传感器电路。 | 解决复杂量子物理问题中电路设计依赖人工且效率低的问题。 | 量子传感器电路设计 |
| 68 | http://arxiv.org/abs/2508.21307v1 | MultiFluxAI Enhancing Platform Engineering with Advanced Agent-Orchestrated Retrieval Systems | 利用生成式 AI 与 Agent 编排，提供动态上下文感知响应。 | 解决产品工程中多源数据管理集成复杂且查询响应慢的问题。 | 平台工程与数据集成 |
| 69 | http://arxiv.org/abs/2509.00189v1 | HiVA: Self-organized Hierarchical Variable Agent via Goal-driven Semantic-Topological Evolution | 将工作流建模为自组织图，利用文本梯度优化语义拓扑空间。 | 解决固定工作流需手动重配置且反应式循环无法蒸馏进展问题。 | 自主任务执行与工具编排 |
| 70 | http://arxiv.org/abs/2509.00482v2 | Talk Less, Call Right: Enhancing Role-Play LLM Agents with Automatic Prompt Optimization and Role Prompting | 提出基于规则的角色提示设计，优化工具调用与响应长度。 | 解决角色扮演 Agent 过度说话且工具使用不符合人设问题。 | 角色扮演对话 Agent |
| 71 | http://arxiv.org/abs/2509.00531v1 | MobiAgent: A Systematic Framework for Customizable Mobile Agents | 提出包含模型、加速框架与基准套件的综合移动 Agent 系统。 | 解决现有移动 Agent 在真实任务中准确率与效率不足的问题。 | 移动端 GUI 智能体系统 |
| 72 | http://arxiv.org/abs/2509.00997v2 | Supporting Our AI Overlords: Redesigning Data Systems to be Agent-First | 提出 Agent-First 数据系统架构，支持 agentic speculation 特性。 | 解决现有数据系统难以适应 Agent 高吞吐探索与解决方案制定问题。 | 数据系统架构设计 |

[返回目录](#目录)

<a id="cat-04"></a>

## 基于Agent的应用系统

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2508.01956v2 | Scaling Clinician-Grade Feature Generation from Clinical Notes with Multi-Agent Language Models | SNOW多Agent LLM系统模拟临床专家迭代推理验证工作流 | 从非结构化EHR笔记中提取结构化特征困难 | 临床预测模型、癌症复发预测 |
| 2 | http://arxiv.org/abs/2508.02342v1 | Agentic Personalized Fashion Recommendation in the Age of Generative AI: Challenges, Opportunities, and Evaluation | Agentic混合模态精炼管道，融合多模态编码器与Agent规划器 | 时尚推荐系统难以捕捉动态趋势和细粒度偏好 | 时尚推荐系统 |
| 3 | http://arxiv.org/abs/2508.02841v1 | A Multi-Agent System for Complex Reasoning in Radiology Visual Question Answering | 多Agent系统含上下文理解、多模态推理、答案验证专用Agent | 放射VQA存在事实准确性、幻觉、跨模态错位问题 | 放射学视觉问答 |
| 4 | http://arxiv.org/abs/2508.02936v1 | AQUAH: Automatic Quantification and Unified Agent in Hydrology | 端到端水文语言Agent，自主检索数据配置模型生成报告 | 水文建模门槛高，需手动干预 | 水文建模、洪水模拟 |
| 5 | http://arxiv.org/abs/2508.02956v1 | Autonomous Inorganic Materials Discovery via Multi-Agent Physics-Aware Scientific Reasoning | SparksMatter多Agent模型自主执行材料发现全流程 | 传统ML方法限于训练数据内知识 | 无机材料设计发现 |
| 6 | http://arxiv.org/abs/2508.04721v1 | Toward Low-Latency End-to-End Voice Agents for Telecommunications Using Streaming ASR, Quantized LLMs, and Real-Time TTS | 低延迟电信语音Agent管道，四专用模型整合流式ASR+RAG+实时TTS | 电信领域缺乏低延迟领域适配语音Agent | 电信客服、智能IVR |
| 7 | http://arxiv.org/abs/2508.00632v1 | Multi-Agent Game Generation and Evaluation via Audio-Visual Recordings | 多智能体系统生成 JavaScript 游戏并自动评估 | 解决交互式音视频内容生成缺乏自动评估指标 | 游戏与动画内容自动生成 |
| 8 | http://arxiv.org/abs/2508.01012v2 | AutoEDA: Enabling EDA Flow Automation through Microservice-Based LLM Agents | 基于 MCP 的微服务 LLM 智能体实现 EDA 流程自动化 | 解决 EDA 脚本依赖人工、易错且难以扩展的问题 | 电子设计自动化流程 |
| 9 | http://arxiv.org/abs/2508.01031v4 | CADDesigner: Conceptual Design of CAD Models Based on General-Purpose Agent | 基于显式上下文命令范式的通用智能体生成 CAD 代码 | 降低 CAD 设计门槛，提升设计效率与代码质量 | 工业制造与计算机辅助设计 |
| 10 | http://arxiv.org/abs/2508.01173v2 | MARS: A Meta-Adaptive Reinforcement Learning Framework for Risk-Aware Multi-Agent Portfolio Management | 元自适应控制器动态编排异质智能体组合 | 解决投资组合管理中风险回报平衡与市场动态适应 | 金融投资组合管理 |
| 11 | http://arxiv.org/abs/2508.09147v1 | Agentic TinyML for Intent-aware Handover in 6G Wireless Networks | 嵌入轻量级 TinyML 智能体实现意图感知主动切换 | 解决 6G 网络中传统反应式切换机制的局限性 | 6G 无线网络与移动边缘计算 |
| 12 | http://arxiv.org/abs/2508.01285v2 | BioDisco: Multi-agent hypothesis generation with dual-mode evidence, iterative feedback and temporal evaluation | 多智能体框架结合双模式证据生成科学假设 | 解决自动化假设生成缺乏新颖性、证据 grounding 与评估 | 生物医学科研假设生成 |
| 13 | http://arxiv.org/abs/2508.01293v2 | GMAT: Grounded Multi-Agent Clinical Description Generation for Text Encoder in Vision-Language MIL for Whole Slide Image Classification | 基于病理教科书与智能体 specialization 生成临床描述 | 解决 VLM 中类描述缺乏领域 grounding 与细粒度特异性 | 全切片图像分类与医疗病理 |
| 14 | http://arxiv.org/abs/2508.01370v1 | MaRGen: Multi-Agent LLM Approach for Self-Directed Market Research and Analysis | 多智能体协作自动化端到端业务分析与报告生成 | 解决市场洞察生成成本高与专业分析方法复制难 | 商业市场研究与分析报告 |
| 15 | http://arxiv.org/abs/2508.01746v1 | Bayes-Entropy Collaborative Driven Agents for Research Hypotheses Generation and Optimization | 集成贝叶斯推理与信息熵驱动搜索的假设生成框架 | 解决自动假设生成缺乏系统性建模与闭环反馈机制 | 科学研究假设生成与优化 |
| 16 | http://arxiv.org/abs/2508.08322v1 | Context Engineering for Multi-Agent LLM Code Assistants Using Elicit, NotebookLM, ChatGPT, and Claude Code | 结合意图翻译、文献检索与多 Agent 代码生成的上下文工程工作流。 | 解决 LLM 在复杂多文件项目中上下文限制与知识缺口问题。 | 软件工程/代码助手 |
| 17 | http://arxiv.org/abs/2508.07021v1 | DocRefine: An Intelligent Framework for Scientific Document Understanding and Content Optimization based on Multimodal Large Model Agents | 编排六个专用 Agent 协作，实现科学 PDF 文档的理解与内容优化。 | 解决传统方法处理复杂布局和多模态科学文档精度不足问题。 | 科学文档处理 |
| 18 | http://arxiv.org/abs/2508.07035v1 | VASPilot: MCP-Facilitated Multi-Agent Intelligence for Autonomous VASP Simulations | 基于 CrewAI 和 MCP 构建多 Agent 架构，全自动化 VASP 工作流。 | 解决 DFT 模拟中手动设置、监控及后处理繁琐的问题。 | 计算材料科学 |
| 19 | http://arxiv.org/abs/2508.07186v1 | Multi-Dimensional Summarization Agents with Context-Aware Reasoning over Enterprise Tables | 引入多 Agent 流水线，提取、分析并总结多维企业数据。 | 解决传统表格文本模型缺乏跨层级结构与上下文感知推理能力问题。 | 企业数据报告 |
| 20 | http://arxiv.org/abs/2508.07221v1 | LLM-based Agents for Automated Confounder Discovery and Subgroup Analysis in Causal Inference | 集成 LLM Agent 模拟领域专家，自动发现混杂因子并进行亚组分析。 | 解决观察性数据中未测量混杂及结构偏差导致的治疗效果估计挑战。 | 因果推断/医疗 |
| 21 | http://arxiv.org/abs/2508.08331v2 | miRKatAI: An Integrated Database and Multi-agent AI system for microRNA Research | 构建 miRKatDB 数据库及基于 LLM 的多 Agent 查询系统。 | 解决 miR 靶点相互作用信息访问、整合及分析的挑战。 | 微 RNA 研究 |
| 22 | http://arxiv.org/abs/2508.14063v1 | A Multi-Agent Approach to Neurological Clinical Reasoning | 分解神经推理为专用认知功能的多 Agent 框架，提升复杂推理能力。 | 解决 LLM 在专业神经科推理任务中表现不一致的问题。 | 神经科临床推理 |
| 23 | http://arxiv.org/abs/2508.07569v1 | Retrieval-Augmented Multi-Agent System for Rapid Statement of Work Generation | 三 Agent 协作（起草、法律检查、格式化），自动化 SOW 生成。 | 解决 SOW 起草过程缓慢、复杂且易出错的问题。 | 法律/商业文档 |
| 24 | http://arxiv.org/abs/2508.07880v1 | Multi-agent systems for chemical engineering: A review and perspective | 综述 MAS 在化学工程中的现状，讨论架构设计与数据整合挑战。 | 解决化学工程复杂工作流分解及多模态数据集成问题。 | 化学工程 |
| 25 | http://arxiv.org/abs/2508.07950v1 | FEAT: A Multi-Agent Forensic AI System with Domain-Adapted Large Language Model for Automated Cause-of-Death Analysis | 多 Agent 框架自动化死亡调查，集成工具增强推理与人机反馈。 | 解决法医死因确定中人力短缺及诊断变异性系统挑战。 | 法医医学 |
| 26 | http://arxiv.org/abs/2508.08137v1 | MuaLLM: A Multimodal Large Language Model Agent for Circuit Design Assistance with Hybrid Contextual Retrieval-Augmented Generation | 多模态 LLM Agent 集成混合 RAG，辅助电路设计文献 review。 | 解决电路设计文献综述中数据表示不一致及优化目标复杂问题。 | 电路设计辅助 |
| 27 | http://arxiv.org/abs/2508.08620v1 | Agentic Graph Neural Networks for Wireless Communications and Networking Towards Edge General Intelligence: A Survey | 提议 employing agentic AI 组织整合 GNNs，实现场景感知实施。 | 解决传统 GNN 被动学习框架无法满足多样无线系统需求问题。 | 无线通信网络 |
| 28 | http://arxiv.org/abs/2508.08627v1 | QoE-Aware Service Provision for Mobile AR Rendering: An Agent-Driven Approach | 建立 LLM 驱动的数字 Agent 桥接 MAR 服务与网络域数据 gap。 | 解决 MAR 应用特定信息对网络控制器不可访问及流量动态性问题。 | 移动 AR 渲染 |
| 29 | http://arxiv.org/abs/2508.08709v1 | CRADLE: Conversational RTL Design Space Exploration with LLM-based Multi-Agent Systems | 对话式框架探索 RTL 设计空间，支持用户引导流与内部自验证。 | 解决现有 RTL 设计方法 rigid 及缺乏自验证优化问题。 | RTL 设计探索 |
| 30 | http://arxiv.org/abs/2508.03281v2 | Quo-Vadis Multi-Agent Automotive Research? Insights from a Participatory Workshop and Questionnaire | 通过研讨会探索多智能体汽车研究现状，强调跨学科方法与仿真环境需求 | 解决混合交通环境中单一智能体研究的局限性 | 自动驾驶与混合交通环境研究 |
| 31 | http://arxiv.org/abs/2508.09159v2 | Agoran: An Agentic Open Marketplace for 6G RAN Automation | 引入代理市场机制，通过立法、执行、司法分支实现 6G 网络自动化 | 解决网络切片控制器僵化且 unaware 业务上下文问题 | 6G 无线接入网自动化 |
| 32 | http://arxiv.org/abs/2508.03393v1 | Agentic AI in 6G Software Businesses: A Layered Maturity Model | 构建分层成熟度模型，评估 6G 软件业务中 Agentic AI 的组织就绪度 | 解决 Agentic AI  adoption 中的技术 immature 与整合复杂性问题 | 6G 软件业务组织 |
| 33 | http://arxiv.org/abs/2508.03444v1 | An Auditable Agent Platform For Automated Molecular Optimisation | 构建分层工具使用代理框架，自动化分子优化并保持推理路径可审计 | 解决药物发现中数据分散与设计循环缓慢问题 | 药物发现与分子设计 |
| 34 | http://arxiv.org/abs/2508.03865v3 | An Entity Linking Agent for Question Answering | 基于 LLM 模拟人类认知工作流的实体链接代理，提升 QA 准确性 | 解决现有 EL 方法在短模糊 QA 问题中表现不佳问题 | 问答系统与知识库 |
| 35 | http://arxiv.org/abs/2508.04038v1 | ZARA: Zero-shot Motion Time-Series Analysis via Knowledge and Retrieval Driven LLM Agents | 基于知识与检索驱动的代理框架，实现零样本可解释人类活动识别 | 解决现有 HAR 方法需重训练且缺乏可解释性问题 | 健康与运动传感器分析 |
| 36 | http://arxiv.org/abs/2508.04742v1 | Discovery of Disease Relationships via Transcriptomic Signature Analysis Powered by Agentic AI | 利用 Agentic AI 系统分析转录组特征，发现疾病间分子关系 | 解决现代疾病分类忽略分子共性问题 | 疾病关系发现与药物重定位 |
| 37 | http://arxiv.org/abs/2508.04170v1 | Agentic-AI based Mathematical Framework for Commercialization of Energy Resilience in Electrical Distribution System Planning and Operation | 集成双代理 PPO 与市场机制，优化配电系统韧性商业化部署 | 解决传统优化无法动态适应正常与紧急条件问题 | 电力分配系统规划 |
| 38 | http://arxiv.org/abs/2508.04231v2 | Empowering Time Series Forecasting with LLM-Agents | 提出数据中心代理，利用元数据清理数据以优化时间序列预测 | 解决 AutoML 过度关注模型架构而忽视数据质量问题 | 时间序列预测 AutoML |
| 39 | http://arxiv.org/abs/2508.04556v1 | CONVERGE: A Multi-Agent Vision-Radio Architecture for xApps | 提出多代理视觉 - 无线电架构，实时交付传感信息给 O-RAN xApps | 解决电信与计算机视觉独立演进缺乏协同问题 | 5G/6G RAN 控制 |
| 40 | http://arxiv.org/abs/2508.04915v1 | ConfAgents: A Conformal-Guided Multi-Agent Framework for Cost-Efficient Medical Diagnosis | 提出 conformal-guided 多代理框架，优化医疗诊断成本与效率 | 解决 AI 代理依赖 static 策略无法学习 strategic planning 问题 | 医疗诊断 |
| 41 | http://arxiv.org/abs/2508.05702v3 | Grid-Agent: An LLM-Powered Multi-Agent System for Power Grid Control | LLM 多智能体电网控制框架，集成语义推理与数值精度 | 分布式能源与极端天气下的电网违规检测与修复 | 现代智能电网控制 |
| 42 | http://arxiv.org/abs/2508.05002v1 | AgenticData: An Agentic Data Analytics System for Heterogeneous Data | 反馈驱动规划将自然语言转为语义计划，多智能体协作分析 | 非结构化数据分析依赖专家代码，成本高耗时 | 异构数据 analytics 系统 |
| 43 | http://arxiv.org/abs/2508.06569v1 | Operationalizing Serendipity: Multi-Agent AI Workflows for Enhanced Materials Characterization with Theory-in-the-Loop | 多智能体工作流连接实验观察与理论模拟，运营化偶然发现 | 自主实验室优化效率易忽略意外科学发现 | 材料科学研究 |
| 44 | http://arxiv.org/abs/2508.05421v1 | LLM-based Multi-Agent Copilot for Quantum Sensor | LLM 多智能体框架集成外部知识与主动学习，用于量子传感器设计 | 量子传感器开发存在跨学科知识壁垒与优化复杂 | 量子传感器设计 |
| 45 | http://arxiv.org/abs/2508.05492v1 | MoMA: A Mixture-of-Multimodal-Agents Architecture for Enhancing Clinical Prediction Modelling | 混合多模态智能体架构，专家智能体转换非文本模态为结构化摘要 | 多模态医疗数据整合难，临床预测模型数据需求大 | 临床预测建模 |
| 46 | http://arxiv.org/abs/2508.05503v1 | AutoIAD: Manager-Driven Multi-Agent Collaboration for Automated Industrial Anomaly Detection | 管理器驱动多智能体协作，端到端自动化工业视觉异常检测模型开发 | 工业异常检测依赖人工努力，场景应用成本高 | 工业视觉检测 |
| 47 | http://arxiv.org/abs/2508.11671v1 | LLM-Based Intelligent Agents for Music Recommendation: A Comparison with Classical Content-Based Filtering | 结合 LLM 与智能体的多智能体个性化音乐推荐系统 | 流媒体平台信息过载，传统推荐系统用户体验不足 | 音乐推荐系统 |
| 48 | http://arxiv.org/abs/2508.05748v3 | WebWatcher: Breaking New Frontier of Vision-Language Deep Research Agent | 多模态深度研究智能体，增强视觉语言推理与工具使用能力 | 现有研究智能体主要基于文本，忽略现实世界视觉信息 | 多模态深度研究 |
| 49 | http://arxiv.org/abs/2508.14053v2 | MAHL: Multi-Agent LLM-Guided Hierarchical Chiplet Design with Adaptive Debugging | 分层 LLM 芯片设计生成框架，六智能体协作实现算法硬件映射 | LLM 驱动芯片设计面临扁平化设计高验证成本与参数优化不准 | 芯片设计自动化 |
| 50 | http://arxiv.org/abs/2508.06189v2 | MA-CBP: A Criminal Behavior Prediction Framework Based on Multi-Agent Asynchronous Collaboration | 多智能体异步协作框架，转换视频流为语义描述进行犯罪行为预测 | 传统异常检测难捕捉高层行为语义，生成式方法非实时 | 城市公共安全预警 |
| 51 | http://arxiv.org/abs/2508.09197v1 | MX-AI: Agentic Observability and Control Platform for Open and AI-RAN | 端到端智能体系统，在 SMO 层部署 LLM 智能体图暴露可观测性与控制 | 6G 无线接入网络缺乏原生 AI 智能体观测与控制平台 | 6G Open RAN |
| 52 | http://arxiv.org/abs/2508.06916v1 | Talk2Image: A Multi-Agent System for Multi-Turn Image Generation and Editing | 多智能体系统支持多轮对话图像生成与编辑，意图解析与任务分解 | 现有文本生成图像系统难以处理迭代多轮创意任务 | 多轮图像生成编辑 |
| 53 | http://arxiv.org/abs/2508.08761v1 | DevNous: An LLM-Based Multi-Agent System for Grounding IT Project Management in Unstructured Conversation | 集成多智能体专家系统，自动化非结构化对话转换 | 解决 IT 项目管理中对话到结构化 artifacts 翻译瓶颈 | IT 项目管理与团队协作 |
| 54 | http://arxiv.org/abs/2508.08764v1 | CARES: Collaborative Agentic Reasoning for Error Detection in Surgery | 零样本临床知情风险分层智能体推理架构 | 解决机器人手术中错误检测数据少及方法受限问题 | 医疗手术错误检测 |
| 55 | http://arxiv.org/abs/2508.10052v1 | NetMoniAI: An Agentic AI Framework for Network Security & Monitoring | 去中心化分析结合轻量集中协调的双层框架 | 解决网络监控中资源约束及协调攻击检测问题 | 网络安全与监控 |
| 56 | http://arxiv.org/abs/2508.09632v6 | Preacher: Paper-to-Video Agentic System | 自顶向下分解论文，渐进式思维链规划视频生成 | 解决视频生成模型上下文限制及领域知识表示问题 | 科研论文视频摘要生成 |
| 57 | http://arxiv.org/abs/2508.09648v1 | ReqInOne: A Large Language Model-Based Agent for Software Requirements Specification Generation | 模块化架构，分解 SRS 生成任务及定制 prompt | 解决手动写 SRS 耗时及 LLM 幻觉与可控性问题 | 软件需求工程 |
| 58 | http://arxiv.org/abs/2508.09858v1 | HumanGenesis: Agent-Based Geometric and Generative Modeling for Synthetic Human Dynamics | 四协作智能体集成几何与生成建模，Back-to-4D 反馈 | 解决合成人类动态几何不一致及运动泛化限制问题 | 人体运动生成与视频合成 |
| 59 | http://arxiv.org/abs/2508.10177v2 | KompeteAI: Accelerated Autonomous Multi-Agent System for End-to-End Pipeline Generation for Machine Learning Problems | 动态解空间探索，合并阶段及加速调试方法 | 解决 AutoML 探索策略受限及执行瓶颈问题 | 机器学习管道生成 |
| 60 | http://arxiv.org/abs/2508.10745v2 | Agentic Design Review System | 多智能体协作分析设计，meta-agent 编排及图匹配 | 解决图形设计 holistic 评估及反馈聚合问题 | 图形设计评估 |
| 61 | http://arxiv.org/abs/2508.10760v2 | FROGENT: An End-to-End Full-process Drug Design Multi-Agent System | 闭环自主框架，中央编排及分布式智能体协作 | 解决药物发现流程碎片化及手动操作依赖问题 | 药物设计与发现 |
| 62 | http://arxiv.org/abs/2508.11152v1 | AlphaAgents: Large Language Model based Multi-Agents for Equity Portfolio Constructions | 基于角色的多智能体系统，支持股票选择与组合构建 | 股权研究中复杂挑战需多智能体协作解决 | 金融投资组合管理 |
| 63 | http://arxiv.org/abs/2508.11398v2 | Trustworthy AI Psychotherapy: Multi-Agent LLM Workflow for Counseling and Explainable Mental Disorder Diagnosis | DSM5AgentFlow，自主生成诊断问卷，模拟治疗师对话 | 心理健康诊断数据稀缺，缺乏主动询问与临床对齐 | 心理健康诊断与咨询 |
| 64 | http://arxiv.org/abs/2508.11401v4 | FACET: Teacher-Centred LLM-Based Multi-Agent Systems-Towards Personalized Educational Worksheets | 三智能体框架，模拟学习者 profile 生成个性化材料 | 学生群体异质性高，现有工具忽视教学法需求 | 数学教育与个性化学习 |
| 65 | http://arxiv.org/abs/2508.11567v1 | AgentMental: An Interactive Multi-Agent Framework for Explainable and Adaptive Mental Health Assessment | 多智能体框架模拟医患对话，自适应提问机制 | 传统评估依赖静态文本，缺乏动态交互与迭代提问 | 心理健康评估 |
| 66 | http://arxiv.org/abs/2508.11860v1 | LARC: Towards Human-level Constrained Retrosynthesis Planning through an Agentic Framework | 首个约束下逆合成规划 LLM 代理框架，Agent-as-a-Judge | 约束逆合成规划挑战大，需实用约束指导路线生成 | 化学合成路线规划 |
| 67 | http://arxiv.org/abs/2508.12232v2 | LinkAnchor: An Autonomous LLM-Based Agent for Issue-to-Commit Link Recovery | 懒加载架构，动态检索相关上下文恢复链接 | LLM 上下文窗口限制，成对评分在大规模库不实用 | 软件可追溯性与项目管理 |
| 68 | http://arxiv.org/abs/2508.12472v1 | GALA: Can Graph-Augmented Large Language Model Agentic Workflows Elevate Root Cause Analysis? | 多模态框架，结合统计因果推断与 LLM 迭代推理 | 传统 RCA 方法聚焦单模态，缺乏可操作诊断见解 | 微服务系统根因分析 |
| 69 | http://arxiv.org/abs/2508.12551v1 | OS-R1: Agentic Operating System Kernel Tuning with Reinforcement Learning | 基于规则 RL 的代理内核调优框架，抽象配置空间 | 现有方法效率、扩展性与泛化性面临挑战 | 操作系统性能优化 |
| 70 | http://arxiv.org/abs/2509.09685v4 | TalkPlayData 2: An Agentic Synthetic Data Pipeline for Multimodal Conversational Music Recommendation | 代理数据管道，多角色 LLM 生成多模态对话数据 | 缺乏多模态对话音乐推荐合成数据集 | 音乐推荐系统训练 |
| 71 | http://arxiv.org/abs/2508.15110v1 | LLMs and Agentic AI in Insurance Decision-Making: Opportunities and Challenges For Africa | 分析非洲保险市场中LLM和Agent AI的机遇挑战 | 非洲保险市场AI应用的关键差距和本地化需求 | 非洲保险行业决策系统 |
| 72 | http://arxiv.org/abs/2508.16678v1 | Cognitive Agents Powered by Large Language Models for Agile Software Project Management | LLM认知Agent集成到SAFe框架优化项目管理 | 软件项目中任务委托、跨Agent通信和生命周期管理问题 | 敏捷软件项目管理 |
| 73 | http://arxiv.org/abs/2508.15746v2 | End-to-End Agentic RAG System Training for Traceable Diagnostic Reasoning | 端到端RL训练Agentic RAG实现可追溯诊断推理 | 医疗LLM知识局限、幻觉、与循证医学脱节问题 | 医疗诊断辅助系统 |
| 74 | http://arxiv.org/abs/2508.15940v1 | ASIC-Agent: An Autonomous Multi-Agent System for ASIC Design with Benchmark Evaluation | 多Agent架构集成RTL生成、验证、硬化专用子Agent | LLM无法执行代码、缺乏调试能力和长时记忆问题 | 数字ASIC设计工作流 |
| 75 | http://arxiv.org/abs/2508.16044v2 | AMAZe: A Multi-Agent Zero-shot Index Advisor for Relational Databases | 零-shot多Agent框架分解索引推荐为多子步骤 | 启发式优化计算时间长、学习模型泛化性差问题 | 关系数据库索引优化 |
| 76 | http://arxiv.org/abs/2508.16112v1 | IR-Agent: Expert-Inspired LLM Agents for Structure Elucidation from Infrared Spectra | 多Agent框架模拟专家驱动IR分析流程 | 现有方法不反映专家分析流程、缺乏灵活性问题 | 红外光谱分子结构解析 |
| 77 | http://arxiv.org/abs/2508.20119v2 | LLM Agents for Generating Microservice-based Applications: how complex is your specification? | 评估LLM Agent生成微服务应用代码的能力 | 复杂业务逻辑、外部服务集成下代码生成正确率低问题 | 微服务应用代码生成 |
| 78 | http://arxiv.org/abs/2508.16379v1 | Agentic AI Empowered Multi-UAV Trajectory Optimization in Low-Altitude Economy Networks | ARMAIT框架集成Agent RAG+Mamba-Attention Transformer | 多UAV轨迹优化中高层任务解释和关键组件识别问题 | 低空经济网络UAV轨迹优化 |
| 79 | http://arxiv.org/abs/2508.05306v1 | Towards Log Analysis with AI Agents: Cowrie Case Study | 轻量级AI Agent自动化解析、总结蜜罐日志 | 蜜罐日志量大且非结构化，人工分析困难 | 网络安全威胁情报分析 |
| 80 | http://arxiv.org/abs/2508.16571v3 | LLM-Based Agents for Competitive Landscape Mapping in Drug Asset Due Diligence | 竞争发现Agent+验证Agent过滤假阳性，83%召回率 | 药物竞争格局数据碎片化、LLM检索不可靠 | 生物医药投资尽职调查 |
| 81 | http://arxiv.org/abs/2508.17094v3 | PowerChain: A Verifiable Agentic AI System for Automating Distribution Grid Analyses | 动态生成结构化上下文，利用电力系统工具监督信号 | 配电网分析工作流复杂，难以自动化泛化 | 电力公司配电网运营规划 |
| 82 | http://arxiv.org/abs/2508.17188v1 | PosterGen: Aesthetic-Aware Paper-to-Poster Generation via Multi-Agent LLMs | 四Agent协作：解析、布局、样式、渲染，VLM评估 | 现有方法忽视设计美学原则，需大量人工修改 | 学术会议海报自动生成 |
| 83 | http://arxiv.org/abs/2508.17343v4 | Agentic AI for Software: thoughts from Software Engineering community | 提出规范推断是核心，需AI-based V&V应对代码爆炸 | 代码生成质量无保证，缺乏需求对齐 | 软件工程自动化工作流 |
| 84 | http://arxiv.org/abs/2508.17565v1 | TradingGroup: A Multi-Agent Trading System with Self-Reflection and Data-Synthesis | 五Agent协作+自反思机制+端到端数据合成管道 | 现有系统缺乏Agent协调和高质量领域数据 | 金融股票交易决策 |
| 85 | http://arxiv.org/abs/2510.01193v1 | How can AI agents support journalists' work? An experiment with designing an LLM-driven intelligent reporting system | TeleFlash系统：信息过滤+摘要+报告自动化 | 新闻工作流AI整合复杂，需求未充分满足 | 新闻采编工作流辅助 |
| 86 | http://arxiv.org/abs/2508.12868v1 | An LLM Agent-Based Complex Semantic Table Annotation Approach | 设计五工具 ReAct 框架，动态选择标注策略处理复杂表格语义 | 解决复杂表格语义丢失、本体层级严格及拼写错误阻碍标注问题 | 语义表格标注 |
| 87 | http://arxiv.org/abs/2508.13251v2 | "DIVE" into Hydrogen Storage Materials Discovery with AI Agents | 提出 DIVE 多智能体工作流，从科学文献图表中提取实验数据 | 解决非结构化图表信息 trapped 阻碍 LLM 材料设计 Agent 构建问题 | 氢存储材料发现 |
| 88 | http://arxiv.org/abs/2508.13256v2 | CardAIc-Agents: A Multimodal Framework with Hierarchical Adaptation for Cardiac Care Support | 提出多模态框架，动态 refine 计划及多学科讨论支持心脏护理 | 解决临床工作流 rigid、缺乏领域工具支持及连续学习能力问题 | 心血管疾病护理 |
| 89 | http://arxiv.org/abs/2508.14123v1 | AI Agents for Photonic Integrated Circuit Design Automation | 提出 PhIDO 多智能体框架，将自然语言 PIC 设计请求转为布局掩膜 | 解决光子集成电路设计自动化缺乏自然语言接口及多模型比较问题 | 光子集成电路设计 |
| 90 | http://arxiv.org/abs/2508.13404v4 | TASER: Table Agents for Schema-guided Extraction and Recommendation | 提出持续学习 Agent 系统，将非结构化多页表格转为标准化输出 | 解决金融表格杂乱无边界框及下游 QA 数据标准化困难问题 | 金融表格提取 |
| 91 | http://arxiv.org/abs/2508.13413v1 | Large Language Models as Visualization Agents for Immersive Binary Reverse Engineering | 集成 LLM Agent 查询二进制工具，动态生成沉浸式 3D 可视化 | 解决二进制逆向工程认知复杂度高及缺乏空间持久性支持问题 | 二进制逆向工程 |
| 92 | http://arxiv.org/abs/2508.13423v2 | AdaptJobRec: Enhancing Conversational Career Recommendation through an LLM-Powered Agentic System | 利用查询复杂度识别机制，平衡复杂查询处理与响应延迟 trade-off | 解决 Agentic 系统响应延迟高及 conversational 推荐系统挑战问题 | 职业推荐系统 |
| 93 | http://arxiv.org/abs/2508.14135v1 | Towards Agent-based Test Support Systems: An Unsupervised Environment Design Approach | 引入 Agent 决策支持框架，自适应传感器放置 across 动态模态测试环境 | 解决传统测试设计 static 及忽略 evolving 参数影响测试结果问题 | 结构分析模态测试 |
| 94 | http://arxiv.org/abs/2508.13872v1 | RED.AI Id-Pattern: First Results of Stone Deterioration Patterns with Multi-Agent Systems | 设计多 Agent AI 系统模拟专家协作，自动化诊断石材病理视觉证据 | 解决传统方法基于直接观察成本高及时间资源消耗大问题 | 石材 deterioration 诊断 |
| 95 | http://arxiv.org/abs/2508.13915v1 | Structured Agentic Workflows for Financial Time-Series Modeling with LLMs and Reflective Feedback | 引入 TS-Agent 模块化框架，自动化增强金融时间序列建模工作流 | 解决 AutoML 缺乏适应性及 LLM Agent 动态代码生成可解释性问题 | 金融时间序列建模 |
| 96 | http://arxiv.org/abs/2508.13943v1 | LLM-Powered Virtual Patient Agents for Interactive Clinical Skills Training with Automated Feedback | 增强 LLM 模拟患者动作空间，引入虚拟导师提供即时个性化反馈 | 解决 OSCE 训练资源需求大及文本模拟缺乏非文本交互能力问题 | 临床技能训练 |
| 97 | http://arxiv.org/abs/2508.14300v1 | MultiFuzz: A Dense Retrieval-based Multi-Agent System for Network Protocol Fuzzing | 集成语义感知上下文检索与专用 Agent，动态适应 fuzzing 策略 | 解决传统 fuzzing 缺乏语义理解及 LLM 输出不可靠 hallucinations 问题 | 网络协议 Fuzzing |
| 98 | http://arxiv.org/abs/2508.14940v2 | Cohort-Aware Agents for Individualized Lung Cancer Risk Prediction Using a Retrieval-Augmented Model Selection Framework | 提出个性化风险预测 Agent，动态检索 cohort 知识推荐最优模型 | 解决肺癌风险预测跨人群 variability 大及单一模型性能不佳问题 | 肺癌风险预测 |
| 99 | http://arxiv.org/abs/2508.18781v3 | AniME: Adaptive Multi-Agent Planning for Long Animation Generation | 导演导向的多智能体系统，协调下游专用 Agent 实现长动画自动生成。 | 解决长表单动画生产中角色一致性与音画同步难的问题。 | 自动化动漫生产工作流 |
| 100 | http://arxiv.org/abs/2508.18791v3 | LaTeXTrans: Structured LaTeX Translation with Multi-Agent Coordination | 六专用 Agent 协作，确保 LaTeX 文档翻译的格式保留与术语一致性。 | 解决结构化 LaTeX 文档翻译中语义完整性与可编译性难以维持的问题。 | 学术文档结构化翻译 |
| 101 | http://arxiv.org/abs/2508.18812v1 | STARec: An Efficient Agent Framework for Recommender Systems via Autonomous Deliberate Reasoning | 慢思考增强 Agent 框架，结合快响应与慢推理，通过锚定强化训练培养内在慢思考。 | 解决推荐系统静态用户建模与反应式决策导致的浅层关联偏差问题。 | 个性化推荐系统 |
| 102 | http://arxiv.org/abs/2508.19322v1 | AT-CXR: Uncertainty-Aware Agentic Triage for Chest X-rays | 不确定性感知 Agent，估计置信度并决定自动决策或 Abstain 让人类干预。 | 解决医学影像分诊中真正自主决策 under 真实约束探索不足的问题。 | 胸部 X 光医学影像分诊 |
| 103 | http://arxiv.org/abs/2508.20134v1 | QAgent: An LLM-based Multi-Agent System for Autonomous OpenQASM programming | 多智能体系统自动化 OpenQASM 编程，集成任务规划、RAG 与 CoT 推理。 | 解决非专家因 OpenQASM 编程复杂性难以实现量子优势的问题。 | 自主量子编程 |
| 104 | http://arxiv.org/abs/2508.19383v1 | Aleks: AI powered Multi Agent System for Autonomous Scientific Discovery via Data-Driven Approaches in Plant Science | 多智能体系统整合领域知识与 ML，自主进行数据驱动的植物科学发现。 | 解决植物科学中实验设计、数据预处理与可重复性阻碍研究吞吐的问题。 | 植物科学自主发现 |
| 105 | http://arxiv.org/abs/2509.00078v1 | ChipChat: Low-Latency Cascaded Conversational Agent in MLX | 低延迟级联对话 Agent，集成流式 ASR、LLM 与 TTS，实现端侧亚秒响应。 | 解决实时端侧语音 Agent 架构中串行处理延迟瓶颈与隐私问题。 | 端侧语音对话系统 |
| 106 | http://arxiv.org/abs/2508.19603v1 | CompLex: Music Theory Lexicon Constructed by Autonomous Agents for Automatic Music Generation | 多智能体算法自动构建音乐理论词典，检测并缓解幻觉，提升生成效果。 | 解决音乐生成数据有限且知识整合需大量人工努力的问题。 | 自动音乐生成 |
| 107 | http://arxiv.org/abs/2508.19611v3 | Instructional Agents: Reducing Teaching Faculty Workload through Multi-Agent Instructional Design | 多智能体框架自动化端到端课程材料生成，模拟基于角色的协作确保 pedagogical 连贯。 | 解决高质量教学材料准备劳动密集且需 extensive 协调的问题。 | 教育课程材料生成 |
| 108 | http://arxiv.org/abs/2508.19800v1 | A Multi-Layered Framework for Modeling Human Biology: From Basic AI Agents to a Full-Body AI Agent | envision 全身 AI  Agent，整合多生物层级模型模拟优化人体动态过程。 | 解决复杂生物医学挑战需多层级整合与跨尺度推理的问题。 | 人体生物学建模与个性化医疗 |
| 109 | http://arxiv.org/abs/2509.03536v1 | PG-Agent: An Agent Powered by Page Graph | 将序列 episodes 转为页面图，利用 RAG 检索 GUI 感知指南，泛化至未见场景。 | 解决现有 GUI  Agent 未能捕捉页面间复杂转换关系难以泛化的问题。 | GUI 智能体操作 |
| 110 | http://arxiv.org/abs/2508.20148v2 | The Anatomy of a Personal Health Agent | 构建个人健康 Agent，含数据科学、领域专家与健康教练三个子 Agent。 | 解决日常非临床设置中健康 Agent 应用 underexplored 且需求多样的问题。 | 个人健康管理 |
| 111 | http://arxiv.org/abs/2508.19932v1 | CASE: An Agentic AI Framework for Enhancing Scam Intelligence in Digital Payments | 对话 Agent 主动采访潜在受害者收集诈骗情报，转化为结构化数据用于执法。 | 解决数字支付中复杂社会工程诈骗难以及时预防且信号不足的问题。 | 数字支付诈骗情报收集 |
| 112 | http://arxiv.org/abs/2509.00098v1 | Operating advanced scientific instruments with AI agents that learn on the job | 探索集成 Agentic AI 操作先进仪器，通过可选人类输入与迭代学习优化。 | 解决先进科学设施 operational 复杂性高且需适应用户项目的问题。 | 科学仪器操作与自动化 |
| 113 | http://arxiv.org/abs/2508.20096v1 | CODA: Coordinating the Cerebrum and Cerebellum for a Dual-Brain Computer Use Agent with Decoupled Reinforcement Learning | 可训练组合框架整合通用规划器与专用执行器，通过解耦 RL 训练。 | 解决科学计算领域 GUI  Agent 规划与执行 trade-off 且数据稀缺的问题。 | 科学计算计算机使用 Agent |
| 114 | http://arxiv.org/abs/2508.20467v1 | QTMRL: An Agent for Quantitative Trading Decision-Making Based on Multi-Indicator Guided Reinforcement Learning | 结合多维技术指标与 A2C 算法，构建自适应交易 Agent。 | 解决传统量化模型难以适应动态市场变化与黑天鹅事件的问题。 | 金融量化交易决策 |
| 115 | http://arxiv.org/abs/2508.20585v1 | Persode: Personalized Visual Journaling with Episodic Memory-Aware AI Agent | 集成个性化引导与情景记忆 Agent，自动生成视觉化叙事。 | 解决传统日记缺乏个性化与视觉 Engagement 难以吸引年轻世代问题。 | Z 世代与 Alpha 世代个人记录 |
| 116 | http://arxiv.org/abs/2508.20643v2 | CyberSleuth: Autonomous Blue-Team LLM Agent for Web Attack Forensics | 设计多 Agent  specialization 架构，自动化网络攻击取证分析。 | 解决网络安全取证人工分析慢、易错且缺乏长期推理能力问题。 | Web 攻击事后取证分析 |
| 117 | http://arxiv.org/abs/2508.20729v2 | Re4: Scientific Computing Agent with Rewriting, Resolution, Review and Revision | 构建咨询、审查、编程三 Agent 协作链，实现代码自调试与修正。 | 解决科学计算中代码生成错误率高及非物理解频发的问题。 | 科学计算与物理方程求解 |
| 118 | http://arxiv.org/abs/2508.20784v2 | Single Agent Robust Deep Reinforcement Learning for Bus Fleet Control | 将多车问题重构为单 Agent 问题，通过状态增强捕捉依赖。 | 解决公交调度中 MARL 数据不平衡与收敛困难的问题。 | 城市公交车队控制 |
| 119 | http://arxiv.org/abs/2508.20816v1 | Multi-Agent Penetration Testing AI for the Web | 结合 LLM 编排与工具执行，实现端到端漏洞利用验证。 | 解决 AI 生成代码漏洞多且安全审计能力跟不上开发速度的问题。 | Web 应用安全渗透测试 |
| 120 | http://arxiv.org/abs/2508.21111v1 | Automating the Deep Space Network Data Systems; A Case Study in Adaptive Anomaly Detection through Agentic AI | 集成 ML 预测、RL 分类与 LLM 解释，构建深空网络异常检测管道。 | 解决深空网络设备退化导致数据流中断且维护困难的问题。 | NASA 深空网络数据系统 |
| 121 | http://arxiv.org/abs/2509.02606v1 | Lessons Learned from Deploying Adaptive Machine Learning Agents with Limited Data for Real-time Cell Culture Process Monitoring | 比较预训练、JITL 与在线学习，部署自适应 ML Agent 监测细胞培养。 | 解决生物制造中数据有限且过程变异导致模型性能下降问题。 | 细胞培养过程实时监控 |
| 122 | http://arxiv.org/abs/2509.00625v2 | NetGent: Agent-Based Automation of Network Application Workflows | 将自然语言规则编译为自动机，生成可重执行的网络流量代码。 | 解决浏览器自动化工具脆弱、成本高且难以适应 UI 变化问题。 | 网络流量数据集生成 |

[返回目录](#目录)

<a id="cat-05"></a>

## Agent安全与对齐

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2508.01997v2 | DIRF: A Framework for Digital Identity Protection and Clone Governance in Agentic AI Systems | 数字身份权利框架，九域63控制点，整合法律技术混合执行机制 | AI生成内容导致的数字克隆、身份冒充风险 | Agentic AI系统身份保护 |
| 2 | http://arxiv.org/abs/2508.02110v2 | Attractive Metadata Attack: Inducing LLM Agents to Invoke Malicious Tools | 吸引力元数据攻击，操纵工具元数据诱导Agent选择恶意工具 | 工具元数据操纵攻击面未被探索 | LLM Agent工具调用安全 |
| 3 | http://arxiv.org/abs/2508.04039v1 | Large Reasoning Models Are Autonomous Jailbreak Agents | 大推理模型可作为自主越狱Agent，97.14%攻击成功率 | LRMs简化并规模化越狱活动 | 大推理模型安全对齐 |
| 4 | http://arxiv.org/abs/2508.03117v1 | Toward a Trustworthy Optimization Modeling Agent via Verifiable Synthetic Data Generation | OptiTrust Agent，可验证合成数据生成管道训练优化建模Agent | 优化建模Agent缺乏可信赖训练数据 | 线性/混合整数规划优化 |
| 5 | http://arxiv.org/abs/2508.03125v1 | Attack the Messages, Not the Agents: A Multi-round Adaptive Stealthy Tampering Framework for LLM-MAS | MAST框架，MCTS+DPO训练攻击策略，双语义嵌入相似性约束保持隐蔽 | LLM-MAS通信漏洞未被充分探索 | LLM多Agent系统安全 |
| 6 | http://arxiv.org/abs/2508.00500v2 | Pro2Guard: Proactive Runtime Enforcement of LLM Agent Safety via Probabilistic Model Checking | 基于概率模型检查的主动运行时安全执行框架 | 解决 LLM 智能体随机行为带来的不可预测安全风险 | 自动驾驶与具身智能体安全 |
| 7 | http://arxiv.org/abs/2508.02736v2 | AgentSight: System-Level Observability for AI Agents Using eBPF | 基于 eBPF 的混合方法桥接智能体意图与系统行为语义鸿沟 | 解决 AI 智能体监控调试中意图与动作无法关联问题 | AI 智能体系统运维与安全 |
| 8 | http://arxiv.org/abs/2508.01249v3 | AgentArmor: Enforcing Program Analysis on Agent Runtime Trace to Defend Against Prompt Injection | 将智能体轨迹转化为结构化程序进行安全策略执行 | 解决 LLM 智能体动态行为带来的提示注入安全风险 | 智能体运行时安全防御 |
| 9 | http://arxiv.org/abs/2508.01332v3 | BlockA2A: Towards Secure and Verifiable Agent-to-Agent Interoperability | 统一多智能体信任框架，实现安全可验证互操作 | 解决 LLM 多智能体系统中的身份碎片化与通信不安全 | 企业级多智能体系统互操作 |
| 10 | http://arxiv.org/abs/2508.01451v1 | Think Broad, Act Narrow: CWE Identification with Multi-Agent Large Language Models | 多智能体 LLM 方法 exhaustive 搜索与上下文验证 CWE | 解决 LLM 漏洞检测中深度分析不足与误报率高问题 | 软件漏洞检测与安全弱点识别 |
| 11 | http://arxiv.org/abs/2508.07667v3 | 1-2-3 Check: Enhancing Contextual Privacy in LLM via Multi-Agent Reasoning | 多 Agent 框架分解隐私推理任务，减少单 Agent 信息负载。 | 解决交互式设置中 LLM 处理多源信息时的上下文隐私泄露问题。 | LLM 隐私保护 |
| 12 | http://arxiv.org/abs/2508.07672v1 | Towards Aligning Personalized Conversational Recommendation Agents with Users' Privacy Preferences | 基于情境完整性理论，提出 Agent 主动对齐用户隐私偏好框架。 | 解决传统隐私范式不匹配 AI Agent 动态交互性质的问题。 | 推荐系统隐私 |
| 13 | http://arxiv.org/abs/2508.07673v1 | Ethics2vec: aligning automatic agents and human preferences | 提出 Ethics2Vec 方法，将 Agent 决策策略映射为向量表示以评估对齐。 | 解决人类伦理价值不可度量及与 AI 价值对齐困难的问题。 | AI 伦理对齐 |
| 14 | http://arxiv.org/abs/2508.08127v1 | BlindGuard: Safeguarding LLM-based Multi-Agent Systems under Unknown Attacks | 无监督防御方法，学习正常 Agent 行为以检测恶意 Agent。 | 解决 MAS 中传播漏洞及依赖标签训练防御模型不实用问题。 | 多 Agent 系统安全 |
| 15 | http://arxiv.org/abs/2508.10043v1 | Securing Agentic AI: Threat Modeling and Risk Analysis for Network Monitoring Agentic AI System | 使用 MAESTRO 框架进行七层威胁建模，暴露并消除漏洞。 | 解决 LLM 与自主 Agent 结合在网络监控中的严重安全问题。 | 网络监控 Agent 安全 |
| 16 | http://arxiv.org/abs/2508.08544v1 | AI Agents and the Law | 从技术与法律视角解释 AI 系统直接执行任务时的变化与问题。 | 解决计算机科学与法律在代理忠诚度及第三方交互概念上的差距。 | AI 法律合规 |
| 17 | http://arxiv.org/abs/2508.09230v1 | Cowpox: Towards the Immunity of VLM-based Multi-Agent Systems | 分布式防御机制，生成分发特殊 cure sample 免疫 Agent 免受攻击。 | 解决 VLM 多 Agent 系统中单点 exploit 传播感染整个系统问题。 | 多 Agent 系统鲁棒性 |
| 18 | http://arxiv.org/abs/2508.03665v4 | A DbC Inspired Neurosymbolic Layer for Trustworthy Agent Design | 适配 Design by Contract 引入合约层，介导 LLM 调用以确保语义合规 | 解决生成模型输出缺乏可验证保证与可信度问题 | 可信智能体系统设计 |
| 19 | http://arxiv.org/abs/2508.03858v4 | MI9: An Integrated Runtime Governance Framework for Agentic AI | 引入运行时治理框架，通过六大组件实现安全与对齐的实时控制 | 解决 Agentic AI 运行时 emergent 行为带来的 novel 风险 | 生产环境 Agentic 系统 |
| 20 | http://arxiv.org/abs/2508.04010v1 | HarmonyGuard: Toward Safety and Utility in Web Agents via Adaptive Policy Enhancement and Dual-Objective Optimization | 多代理协作框架，通过策略增强与双目标优化平衡安全与效用 | 解决 Web 代理长序列操作中安全与性能平衡问题 | 开放 Web 环境代理 |
| 21 | http://arxiv.org/abs/2508.05687v1 | Risk Analysis Techniques for Governed LLM-based Multi-Agent Systems | 提供多智能体 AI 系统风险分析工具包，识别六种关键失败模式 | 解决多智能体交互产生 emergent 行为与 novel 失败模式问题 | 受控环境多智能体系统 |
| 22 | http://arxiv.org/abs/2508.05432v1 | Whose Truth? Pluralistic Geo-Alignment for (Agentic) AI | 提出 pluralistic geo-alignment，强调 AI 对齐的时空敏感性 | AI 对齐忽略地理文化差异，输出缺乏情境感知 | 全球 AI 对齐策略 |
| 23 | http://arxiv.org/abs/2508.05557v3 | MV-Debate: Multi-view Agent Debate with Dynamic Reflection Gating for Multimodal Harmful Content Detection in Social Media | 多视图智能体辩论框架，动态反思门控检测多模态有害内容 | 社交媒体多模态内容隐含有害意图，跨模态矛盾难识别 | 社交媒体内容安全 |
| 24 | http://arxiv.org/abs/2508.06059v2 | Fact2Fiction: Targeted Poisoning Attack to Agentic Fact-checking System | 首个针对智能体事实核查系统的投毒攻击框架，利用分解策略 | 自动事实核查系统安全性未探索，易被恶意证据妥协 | 事实核查系统安全 |
| 25 | http://arxiv.org/abs/2508.06457v2 | ScamAgents: How AI Agents Can Simulate Human-Level Scam Calls | 自主多轮智能体模拟真实欺诈场景，生成高度逼真诈骗电话脚本 | LLM 安全护栏对多轮对话欺骗与代理威胁无效 | AI 安全与欺诈检测 |
| 26 | http://arxiv.org/abs/2508.06963v1 | MASteer: Multi-Agent Adaptive Steer Strategy for End-to-End LLM Trustworthiness Repair | 端到端框架基于表示工程修复 LLM 可信度，自动生成导向样本 | 现有修复方法成本高慢，提示工程缺乏鲁棒性与扩展性 | LLM 可信度修复 |
| 27 | http://arxiv.org/abs/2508.09275v2 | Constrained Black-Box Attacks Against Cooperative Multi-Agent Reinforcement Learning | 生成扰动故意 misalign  victim  agents 环境感知 | 解决协作 MARL 在受限条件下对抗攻击脆弱性问题 | 多智能体强化学习安全 |
| 28 | http://arxiv.org/abs/2508.09815v1 | Extending the OWASP Multi-Agentic System Threat Modeling Guide: Insights from Multi-Agent Security Research | 扩展 OWASP 指南，新增威胁类及评估策略 | 解决 LLM 驱动多智能体架构独特失效建模缺口问题 | 多智能体系统安全 |
| 29 | http://arxiv.org/abs/2508.10880v2 | Searching for Privacy Risks in LLM Agents via Simulation | 基于模拟的搜索框架，交替优化攻击与防御策略 | 恶意 Agent 通过多轮交互提取敏感信息的隐私威胁 | LLM 智能体隐私安全 |
| 30 | http://arxiv.org/abs/2508.10991v4 | MCP-Guard: A Multi-Stage Defense-in-Depth Framework for Securing Model Context Protocol in Agentic AI | 三阶段检测管道，结合静态扫描与神经检测器 | MCP 协议下的提示注入与数据泄露风险 | LLM 工具交互安全 |
| 31 | http://arxiv.org/abs/2508.11933v1 | CAMF: Collaborative Adversarial Multi-agent Framework for Machine Generated Text Detection | 协同对抗多智能体框架，三阶段深度分析文本不一致性 | 现有零样本检测缺乏跨维度一致性调查 | 机器生成文本检测 |
| 32 | http://arxiv.org/abs/2508.12259v3 | Fortifying the Agentic Web: A Unified Zero-Trust Architecture Against Logic-layer Threats | 统一零信任架构，基于 DID/VC 与信任自适应运行时 | 代理 Web 面临逻辑层威胁，缺乏统一安全架构 | 代理 Web 安全 |
| 33 | http://arxiv.org/abs/2508.14415v1 | The Agent Behavior: Model, Governance and Challenges in the AI Digital Age | 提出网络行为生命周期模型和A4A范式，分析人机行为差异 | Agent行为监管困难、责任不清、数据污染问题 | 网络环境中的人机协作系统 |
| 34 | http://arxiv.org/abs/2508.15068v1 | S3LoRA: Safe Spectral Sharpness-Guided Pruning in Adaptation of Agent Planner | 谱锐度引导的LoRA剪枝框架无需访问基模型 | LoRA适配Agent规划器时安全对齐受损问题 | 资源受限安全关键Agent部署 |
| 35 | http://arxiv.org/abs/2508.15310v1 | IPIGuard: A Novel Tool Dependency Graph-Based Defense Against Indirect Prompt Injection in LLM Agents | 工具依赖图范式解耦动作规划与外部数据交互 | LLM Agent间接触发恶意工具调用的安全漏洞问题 | 动态环境中Agent工具使用安全 |
| 36 | http://arxiv.org/abs/2508.15764v1 | Distributed Detection of Adversarial Attacks in Multi-Agent Reinforcement Learning with Continuous Action Space | 分布式检测器基于局部观测检测对抗攻击 | 连续动作空间MARL中对抗攻击检测问题 | 合作多Agent强化学习系统 |
| 37 | http://arxiv.org/abs/2508.19267v1 | The Aegis Protocol: A Foundational Security Framework for Autonomous AI Agents | DID身份+后量子密码+零知识证明三层安全框架 | 自主Agent系统控制流劫持、级联故障等安全风险问题 | 开放Agent生态系统安全 |
| 38 | http://arxiv.org/abs/2508.16481v2 | Benchmarking the Robustness of Agentic Systems to Adversarially-Induced Harms | BAD-ACTS基准测试Agent系统对对抗诱导伤害的鲁棒性 | 缺乏全面研究Agent系统在攻击下恶意行为范围问题 | Agent系统安全鲁棒性评估 |
| 39 | http://arxiv.org/abs/2508.17155v1 | Mind the Gap: Time-of-Check to Time-of-Use Vulnerabilities in LLM-Enabled Agents | 首次研究LLM Agent中TOCTOU漏洞，提出三种缓解技术 | LLM Agent验证后状态被修改的安全风险 | LLM Agent系统安全部署 |
| 40 | http://arxiv.org/abs/2508.17674v2 | Attacking LLMs and AI Agents: Advertisement Embedding Attacks Against Large Language Models | 发现AEA攻击：劫持平台注入对抗提示或后门检查点 | LLM输出信息完整性被隐蔽破坏 | LLM和AI Agent安全防御 |
| 41 | http://arxiv.org/abs/2508.18724v1 | Bias Mitigation Agent: Optimizing Source Selection for Fair and Balanced Knowledge Retrieval | 多Agent编排优化源选择，减少检索内容偏差 | Agentic AI继承内外信息源偏差，影响公平性和用户信任 | 公平平衡知识检索 |
| 42 | http://arxiv.org/abs/2508.13465v1 | LM Agents May Fail to Act on Their Own Risk Knowledge | 发现 Agent 风险知识与执行差距，提出风险验证器独立 critique 动作 | 解决 Agent 知晓风险但仍执行危险动作的安全执行能力差距问题 | 安全关键场景 Agent |
| 43 | http://arxiv.org/abs/2508.14031v2 | Unintended Misalignment from Agentic Fine-Tuning: Risks and Mitigation | 提出 Prefix Injection Guard，引导微调 Agent 拒绝有害请求保留性能 | 解决对齐 LLM 微调执行 Agent 任务后 unintentionally misaligned 问题 | Agent 微调安全 |
| 44 | http://arxiv.org/abs/2509.20364v1 | An Approach to Checking Correctness for Agentic Systems | 提出时序表达式语言监控 Agent 行为，检测工具调用及状态转换偏差 | 解决 LLM 输出 variability 导致文本匹配错误检测 fragile 问题 | 生产 Agent 系统监控 |
| 45 | http://arxiv.org/abs/2508.14231v1 | Incident Analysis for AI Agents | 提出 Agent 事件分析框架，识别系统、上下文及认知三类致因因素 | 解决现有事件报告流程不足以理解 Agent 事件及缺乏敏感信息问题 | AI Agent 事件管理 |
| 46 | http://arxiv.org/abs/2508.18765v2 | Governance-as-a-Service: A Multi-Agent Framework for AI System Compliance and Policy Enforcement | 提出治理即服务（GaaS）模块，运行时监管 Agent 输出而不改模型内部。 | 解决分布式自主 Agent 生态系统缺乏可扩展治理与审计机制的问题。 | 多智能体系统合规与策略执行 |
| 47 | http://arxiv.org/abs/2508.19096v1 | Trustworthy Agents for Electronic Health Records through Confidence Estimation | 提出 HCAcc@k% 指标，引入置信度感知 Agent 进行临床问答。 | 解决医疗 EHR 提取中幻觉风险与传统准确率指标局限性的问题。 | 电子健康记录临床问答 |
| 48 | http://arxiv.org/abs/2508.19461v1 | Reliable Weak-to-Strong Monitoring of LLM Agents | 系统化监控红队工作流，提出混合分层顺序 scaffolding 实现弱到强监控。 | 解决自主 LLM  Agent 隐蔽不当行为检测中监控可靠性与对抗鲁棒性问题。 | LLM 智能体行为监控 |
| 49 | http://arxiv.org/abs/2508.19500v1 | Servant, Stalker, Predator: How An Honest, Helpful, And Harmless (3H) Agent Unlocks Adversarial Skills | 揭示 MCP 基于 Agent 系统中良性任务编排产生有害涌现行为的漏洞类。 | 解决服务隔离假设在 Agent 跨域协调行动时失效导致指数级攻击面的问题。 | MCP 代理系统安全漏洞 |
| 50 | http://arxiv.org/abs/2508.19870v1 | Secure Multi-LLM Agentic AI and Agentification for Edge General Intelligence by Zero-Trust: A Survey | 首次系统处理零信任应用于多 LLM 系统，提供理论基础与实用策略。 | 解决多 LLM 协作引入的不安全通信与跨域数据泄漏等传统安全无法address的问题。 | 边缘通用智能多 LLM 安全 |
| 51 | http://arxiv.org/abs/2508.19919v2 | Your AI Bosses Are Still Prejudiced: The Emergence of Stereotypes in LLM-Based Multi-Agent Systems | 发现 LLM 多智能体系统中刻板印象作为交互涌现属性自发产生并强化。 | 解决 AI 系统刻板印象不仅来自训练数据且源于多智能体交互机制的问题。 | 多智能体系统偏见与安全 |
| 52 | http://arxiv.org/abs/2508.20282v3 | Network-Level Prompt and Trait Leakage in Local Research Agents | 展示 Web 与研究 Agent 易受被动网络观察者推断攻击，泄露提示与特征。 | 解决本地部署研究 Agent 因网络元数据导致隐私泄露的独特风险问题。 | 研究 Agent 网络安全与隐私 |
| 53 | http://arxiv.org/abs/2508.20412v3 | MindGuard: Intrinsic Decision Inspection for Securing LLM Agents Against Metadata Poisoning | 利用注意力机制构建决策依赖图，实现决策级毒化攻击检测。 | 解决工具元数据毒化攻击无行为痕迹难以防御的问题。 | LLM Agent 工具调用安全 |
| 54 | http://arxiv.org/abs/2508.20866v6 | AVIATOR: Towards AI-Agentic Vulnerability Injection Workflow for High-Fidelity, Large-Scale Code Security Dataset | 分解漏洞注入为多 Agent 工作流，结合 RAG 与 LoRA 微调。 | 解决现有漏洞数据集标签噪声大、覆盖少且缺乏真实上下文问题。 | 代码安全数据集构建 |
| 55 | http://arxiv.org/abs/2508.21302v3 | Locus: Agentic Predicate Synthesis for Directed Fuzzing | 合成谓词捕获模糊测试进度，自动拒绝无效执行路径。 | 解决定向模糊测试搜索空间大且分支距离指导不精确问题。 | 软件漏洞挖掘与调试 |
| 56 | http://arxiv.org/abs/2509.00124v1 | A Whole New World: Creating a Parallel-Poisoned Web Only AI-Agents Can See | 利用网站 cloaking 技术针对 AI Agent 指纹提供恶意内容。 | 解决自主浏览 Agent 因指纹同质化易受隐蔽攻击的问题。 | AI Agent 网络安全防御 |
| 57 | http://arxiv.org/abs/2508.21579v1 | Agentic Discovery and Validation of Android App Vulnerabilities | 模仿专家分析流程，自动生成 PoC 验证漏洞可利用性。 | 解决安卓漏洞检测工具误报多且缺乏可验证利用证据问题。 | 安卓应用安全检测 |
| 58 | http://arxiv.org/abs/2510.06222v1 | Inducing State Anxiety in LLM Agents Reproduces Human-Like Biases in Consumer Decision-Making | 发现创伤性提示诱导 Agent 产生类似人类的消费决策偏差。 | 解决 LLM Agent 在压力情境下可靠性及伦理部署隐患问题。 | 消费者行为模拟与数字健康 |

[返回目录](#目录)

<a id="cat-06"></a>

## Agent评测与基准

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2508.02013v6 | SpeechRole: A Large-Scale Dataset and Benchmark for Evaluating Speech Role-Playing Agents | 98角色111k语音对话数据集，多维语音角色扮演评测基准 | 语音角色扮演Agent缺乏系统评估 | 语音角色扮演Agent |
| 2 | http://arxiv.org/abs/2508.02630v3 | What Is Your AI Agent Buying? Evaluation, Biases, Model Dependence, & Emerging Implications for Agentic E-Commerce | ACES框架审计Agent决策行为，揭示选择同质性、位置偏差等 | AI Agent电商行为缺乏系统评估 | 电商AI Agent、在线市场 |
| 3 | http://arxiv.org/abs/2508.02808v1 | Clinically Grounded Agent-based Report Evaluation: An Interpretable Metric for Radiology Report Generation | ICARE框架，两Agent生成临床问题互测，可解释评估指标 | 放射报告生成缺乏可靠临床评估指标 | 放射学报告生成 |
| 4 | http://arxiv.org/abs/2508.02921v1 | PentestJudge: Judging Agent Behavior Against Operational Requirements | LLM-as-judge评估渗透测试Agent，树结构rubrics分层评估 | 安全Agent操作标准难以编程评估 | 渗透测试Agent评估 |
| 5 | http://arxiv.org/abs/2508.02994v1 | When AIs Judge AIs: The Rise of Agent-as-a-Judge Evaluation for LLMs | 综述Agent-as-a-judge范式，从单模型到多Agent辩论框架 | LLM输出评估成为瓶颈，尤其是开放任务 | LLM评估、多领域部署 |
| 6 | http://arxiv.org/abs/2508.05674v1 | Towards Effective Offensive Security LLM Agents: Hyperparameter Tuning, LLM as a Judge, and a Lightweight CTF Benchmark | CTFJudge框架+CCI指标+CTFTiny基准，系统研究Agent成功因素 | 进攻性安全LLM Agent缺乏系统评估方法 | CTF挑战、网络安全Agent |
| 7 | http://arxiv.org/abs/2508.00288v4 | UAV-ON: A Benchmark for Open-World Object Goal Navigation with Aerial Agents | 构建大规模开放世界无人机物体导航基准 | 解决现有导航范式依赖指令、缺乏自主性问题 | 空中智能体导航研究 |
| 8 | http://arxiv.org/abs/2508.00400v1 | Sari Sandbox: A Virtual Retail Store Environment for Embodied AI Agents | 高保真 3D 零售店仿真环境与人类性能基准 | 解决具身智能体在零售特定场景训练环境缺失 | 具身智能体购物任务 |
| 9 | http://arxiv.org/abs/2508.01330v2 | NatureGAIA: Pushing the Frontiers of GUI Agents with a Challenging Benchmark and High-Quality Trajectory Dataset | 基于因果路径原则的 GUI 智能体基准与轨迹数据集 | 解决现有 GUI 智能体评估基准在准确性与可扩展性局限 | 图形用户界面智能体 |
| 10 | http://arxiv.org/abs/2508.01623v1 | A Multi-Agent Pokemon Tournament for Evaluating Strategic Reasoning of Large Language Models | 竞争性锦标赛系统模拟宝可梦战斗中的战略决策 | 解决 LLM 在约束规则环境下战略推理与适应性评估 | 大语言模型战略推理评估 |
| 11 | http://arxiv.org/abs/2508.01780v2 | LiveMCPBench: Can Agents Navigate an Ocean of MCP Tools? | 大规模可复现基准评估智能体在 MCP 工具海洋中导航 | 解决现有 MCP 评估假设单服务器与忽略大规模检索挑战 | 模型上下文协议智能体能力 |
| 12 | http://arxiv.org/abs/2508.07575v1 | MCPToolBench++: A Large Scale AI Agent Model Context Protocol MCP Tool Use Benchmark | 构建大规模多领域 MCP 工具使用基准，涵盖 4k+ 服务器。 | 解决缺乏全面数据集评估 LLM 及 Agent 的 MCP 工具使用能力问题。 | Agent 工具使用评估 |
| 13 | http://arxiv.org/abs/2508.07999v2 | WideSearch: Benchmarking Agentic Broad Info-Seeking | 引入 WideSearch 基准，评估 Agent 在大规模信息收集任务中的可靠性。 | 解决缺乏合适基准评估 Agent 宽上下文收集能力的问题。 | 信息搜索评估 |
| 14 | http://arxiv.org/abs/2508.08501v2 | GVGAI-LLM: Evaluating Large Language Model Agents with Infinite Games | 基于 GVGAI 构建视频游戏基准，测试 LLM 空间推理与规划能力。 | 解决现有 LLM 基准缺乏空间推理及基本规划测试的问题。 | LLM 游戏能力评估 |
| 15 | http://arxiv.org/abs/2508.04026v2 | VeriWeb: Verifiable Long-Chain Web Benchmark for Agentic Information-Seeking | 提出可验证长链 Web 基准，强调子任务级可验证性与长程复杂度 | 解决现有基准仅限单事实检索与 outcome-only 验证问题 | Web 信息寻求代理 |
| 16 | http://arxiv.org/abs/2508.04266v3 | ShoppingBench: A Real-World Intent-Grounded Shopping Benchmark for LLM-based Agents | 构建端到端购物基准，模拟复杂用户意图与大规模交互环境 | 解决现有电商基准仅关注基本意图缺乏真实复杂度问题 | 电商 LLM 代理 |
| 17 | http://arxiv.org/abs/2508.05405v1 | DeepPHY: Benchmarking Agentic VLMs on Physical Reasoning | 引入 DeepPHY 基准，通过模拟环境系统评估 VLM 物理推理能力 | VLM 在复杂动态环境中缺乏精确动作规划与物理理解 | VLM 物理推理评估 |
| 18 | http://arxiv.org/abs/2508.05508v1 | Auto-Eval Judge: Towards a General Agentic Framework for Task Completion Evaluation | 通用模块化框架，模拟人类评估分解任务并验证每一步 | 现有 Agent 评估忽略逐步推理，缺乏领域无关框架 | 通用 Agent 任务评估 |
| 19 | http://arxiv.org/abs/2508.05614v1 | OmniEAR: Benchmarking Agent Reasoning in Embodied Tasks | 综合框架评估语言模型在具身任务中的物理交互与多智能体协调推理 | 现有基准提供预定义工具，缺乏动态能力获取评估 | 具身 Agent 推理评估 |
| 20 | http://arxiv.org/abs/2508.14052v4 | FinAgentBench: A Benchmark Dataset for Agentic Retrieval in Financial Question Answering | 首个金融领域多步推理检索基准，评估 Agent 识别文档与关键段落 | 金融领域缺乏评估检索增强多步推理能力的基准 | 金融问答检索 |
| 21 | http://arxiv.org/abs/2508.06600v1 | BrowseComp-Plus: A More Fair and Transparent Evaluation Benchmark of Deep-Research Agent | 基于固定 curated 语料库的基准，支持可控实验评估深度研究智能体 | 现有基准依赖黑盒 Web API，公平性与透明度不足 | 深度研究 Agent 评估 |
| 22 | http://arxiv.org/abs/2508.06960v1 | DatasetResearch: Benchmarking Agent Systems for Demand-Driven Dataset Discovery | 首个综合基准评估 AI 智能体从真实需求中发现与合成数据集能力 | 有价值数据集隐藏，Agent 难以超越常规搜索发现 | 数据集发现 Agent |
| 23 | http://arxiv.org/abs/2508.09241v1 | FineState-Bench: A Comprehensive Benchmark for Fine-Grained State Control in GUI Agents | 首个细粒度 GUI 代理操作评估与诊断标准 | 解决现有基准忽视细粒度控制能力问题 | 图形用户界面智能体 |
| 24 | http://arxiv.org/abs/2508.09057v2 | MVISU-Bench: Benchmarking Mobile Agents for Real-World Tasks by Multi-App, Vague, Interactive, Single-App and Unethical Instructions | 涵盖五类真实任务的双语基准，提出 Aider 模块 | 解决移动智能体基准脱离现实及用户意图模糊问题 | 移动智能体自动化 |
| 25 | http://arxiv.org/abs/2508.09124v1 | OdysseyBench: Evaluating LLM Agents on Long-Horizon Complex Office Application Workflows | 评估长周期工作流基准，含真实及合成复杂任务 | 解决现有基准忽视长周期上下文依赖问题 | 办公应用工作流自动化 |
| 26 | http://arxiv.org/abs/2508.09507v2 | An Automated Multi-modal Evaluation Framework for Mobile Intelligent Assistants Based on Large Language Models and Multi-Agent Collaboration | 三层智能体架构，基于 LLM 自动化多模态评估 | 解决移动助手评估成本高及标准不一致问题 | 移动智能助手评估 |
| 27 | http://arxiv.org/abs/2508.10152v2 | Improving and Evaluating Open Deep Research Agents | 适配 BrowseComp 基准，提出 ODR+ 模型及三项改进 | 解决开源深度研究智能体性能及评估基准缺失问题 | 深度研究智能体 |
| 28 | http://arxiv.org/abs/2508.15804v1 | ReportBench: Evaluating Deep Research Agents via Academic Survey Tasks | 系统基准评估研究报告内容质量及引用文献 | 解决深度研究智能体事实准确性及全面性评估问题 | 学术研究报道生成 |
| 29 | http://arxiv.org/abs/2508.13186v1 | MM-BrowseComp: A Comprehensive Benchmark for Multimodal Browsing Agents | 含 224 个手工问题基准，评估多模态检索与推理 | 解决现有浏览基准忽视多模态内容及推理问题 | 多模态浏览智能体 |
| 30 | http://arxiv.org/abs/2508.11027v1 | Hell or High Water: Evaluating Agentic Recovery from External Failures | 专用代理规划基准，引入外部失败测试代理恢复能力 | 智能体在面对环境反馈失败时难以制定备用计划 | 智能体规划鲁棒性评估 |
| 31 | http://arxiv.org/abs/2508.11416v1 | AIM-Bench: Evaluating Decision-making Biases of Agentic LLM as Inventory Manager | 新基准，评估不确定环境下 LLM 代理库存决策偏差 | 库存决策中 LLM 代理能力与决策偏差未被探索 | 供应链库存管理 |
| 32 | http://arxiv.org/abs/2508.11514v1 | DiCriTest: Testing Scenario Generation for Decision-Making Agents Considering Diversity and Criticality | 双空间引导测试框架，协调场景参数与代理行为空间 | 高维场景空间中难以平衡测试场景多样性与关键性 | 决策智能体安全验证 |
| 33 | http://arxiv.org/abs/2508.13201v3 | Benchmarking LLM-based agents for single-cell omics analysis | 新基准评估系统，统一平台与多维指标评估单细胞分析 | 缺乏综合基准阻碍单细胞组学分析 AI 代理进展 | 计算生物学与组学分析 |
| 34 | http://arxiv.org/abs/2508.11915v2 | CORE: Measuring Multi-Agent LLM Interaction Quality under Game-Theoretic Pressures | CORE 指标，量化博弈压力下多智能体语言使用有效性 | 多智能体交互语言多样性未被充分量化 | 多智能体对话质量评估 |
| 35 | http://arxiv.org/abs/2508.11987v3 | FutureX: An Advanced Live Benchmark for LLM Agents in Future Prediction | 动态实时评估基准，支持每日更新与防数据污染 | 缺乏大规模基准评估代理未来预测与动态适应能力 | 未来预测任务评估 |
| 36 | http://arxiv.org/abs/2508.15526v1 | SafetyFlow: An Agent-Flow System for Automated LLM Safety Benchmarking | 七专用Agent自动化构建安全基准无需人工干预 | 现有安全基准人工策展成本高、冗余大、难度有限问题 | LLM安全评估基准构建 |
| 37 | http://arxiv.org/abs/2508.15760v1 | LiveMCP-101: Stress Testing and Diagnosing MCP-enabled Agents on Challenging Queries | 101真实世界查询基准测试MCP Agent工具编排能力 | 缺乏基准测试Agent在动态场景中使用MCP工具能力问题 | MCP-enabled Agent工具使用评估 |
| 38 | http://arxiv.org/abs/2508.16260v2 | MCPVerse: An Expansive, Real-World Benchmark for Agentic Tool Use | 550+真实可执行工具创建超140k token动作空间 | 现有基准依赖合成工具、动作空间严重受限问题 | Agent工具使用能力评估 |
| 39 | http://arxiv.org/abs/2508.17393v1 | Agent-Testing Agent: A Meta-Agent for Automated Testing and Evaluation of Conversational AI Agents | ATA元Agent自适应生成对抗测试，LLM-as-Judge评分 | 现有评估依赖静态基准和小规模人工研究 | 对话式AI Agent测试 |
| 40 | http://arxiv.org/abs/2508.17398v1 | DashboardQA: Benchmarking Multimodal Agents for Question Answering on Interactive Dashboards | 首个交互式Dashboard多模态Agent基准，112个仪表板 | 现有基准忽视Dashboard交互性，评估能力受限 | GUI多模态Agent评估 |
| 41 | http://arxiv.org/abs/2508.13024v2 | WebMall -- A Multi-Shop Benchmark for Evaluating Web Agents [Technical Report] | 引入首个离线多商店基准，模拟异构产品数据及复杂比价任务 | 解决现有 Web 基准缺乏多店异构数据及复杂电商任务覆盖问题 | Web Agent 评估 |
| 42 | http://arxiv.org/abs/2508.13143v1 | Exploring Autonomous Agents: A Closer Look at Why They Fail When Completing Tasks | 构建 34 任务基准，提出三层失败分类法分析规划、执行及响应错误 | 解决当前评估依赖成功率缺乏系统交互及失败原因分析问题 | 自主 Agent 系统 |
| 43 | http://arxiv.org/abs/2508.15832v1 | A Functionality-Grounded Benchmark for Evaluating Web Agents in E-commerce Domains | 提出 Amazon-Bench，涵盖账户管理及安全风险评估的自动化评估框架 | 解决现有电商基准功能单一及忽略 Agent 操作潜在安全风险问题 | 电商 Web Agent |
| 44 | http://arxiv.org/abs/2508.18929v1 | Diverse And Private Synthetic Datasets Generation for RAG evaluation: A multi-agent framework | 多智能体框架生成合成 QA 数据集，优先语义多样性与隐私保护。 | 解决 RAG 评估数据集缺乏多样性与隐私保护，难以反映真实约束的问题。 | RAG 系统评估数据集生成 |
| 45 | http://arxiv.org/abs/2508.18993v2 | GitTaskBench: A Benchmark for Code Agents Solving Real-World Tasks Through Code Repository Leveraging | 构建利用代码仓库解决真实任务的基准，提出 alpha-value 量化经济收益。 | 解决现有基准缺乏评估 Agent 利用仓库解决端到端真实任务能力的问题。 | 代码智能体真实任务评估 |
| 46 | http://arxiv.org/abs/2508.19493v2 | Mind the Third Eye! Benchmarking Privacy Awareness in MLLM-powered Smartphone Agents | 构建包含 7138 场景的大规模基准，评估 MLLM 手机 Agent 的隐私意识。 | 解决手机 Agent 访问敏感信息时隐私意识不足且缺乏全面评估的问题。 | 多模态手机智能体隐私评估 |
| 47 | http://arxiv.org/abs/2508.20453v1 | MCP-Bench: Benchmarking Tool-Using LLM Agents with Complex Real-World Tasks via MCP Servers | 基于 MCP 协议构建包含 250 个工具的真实多步任务基准。 | 解决现有基准缺乏跨工具协调与真实多步工作流评估的问题。 | 工具使用型 LLM Agent 评估 |
| 48 | http://arxiv.org/abs/2509.00115v3 | Adaptive Monitoring and Real-World Evaluation of Agentic AI Systems | 形式化自适应多维监控算法，降低异常检测延迟与误报率。 | 解决现有评估缺乏算法实例与实证证据且技术指标主导问题。 | Agentic AI 系统实时监控 |
| 49 | http://arxiv.org/abs/2508.20973v1 | ProactiveEval: A Unified Evaluation Framework for Proactive Dialogue Agents | 分解主动对话为目标规划与对话引导，自动生成评估数据。 | 解决主动对话评估碎片化且缺乏跨领域综合探索的问题。 | 主动对话 Agent 能力评估 |
| 50 | http://arxiv.org/abs/2508.21475v3 | MMSearch-Plus: Benchmarking Provenance-Aware Search for Multimodal Browsing Agents | 构建需多模态推理的基准，引入 Set-of-Mark 模块增强鲁棒性。 | 解决现有多模态浏览基准缺乏真正视觉推理与来源感知问题。 | 多模态浏览 Agent 评估 |
| 51 | http://arxiv.org/abs/2509.00446v1 | NEWSAGENT: Benchmarking Multimodal Agents as Journalists with Real-World Newswriting Tasks | 构建新闻写作基准，评估 Agent 主动发现信息与叙事整合能力。 | 解决现有任务缺乏真实新闻写作中信息缺口与规划挑战问题。 | 新闻写作与多模态数据处理 |

[返回目录](#目录)

<a id="cat-07"></a>

## Agent记忆与知识管理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2508.02016v4 | Dynamic Context Adaptation for Consistent Role-Playing Agents with Retrieval-Augmented Generations | Amadeus框架增强角色一致性，CharacterRAG数据集 | RAG角色扮演Agent易产生幻觉 | 角色扮演Agent |
| 2 | http://arxiv.org/abs/2508.02258v2 | Patho-AgenticRAG: Towards Multimodal Agentic Retrieval-Augmented Generation for Pathology VLMs via Reinforcement Learning | 多模态RAG支持图文联合检索，页级嵌入权威病理教科书 | 病理VLM易产生幻觉，文本RAG丢失视觉信息 | 病理学诊断、视觉问答 |
| 3 | http://arxiv.org/abs/2508.07010v1 | Narrative Memory in Machines: Multi-Agent Arc Extraction in Serialized TV | 引入计算记忆架构，利用向量库存储情节记忆，多 Agent 模拟工作记忆。 | 解决 serialized TV 叙事弧提取与信息管理的复杂性挑战。 | 电视叙事分析 |
| 4 | http://arxiv.org/abs/2508.07292v2 | EndoAgent: A Memory-Guided Reflective Agent for Intelligent Endoscopic Vision-to-Decision Reasoning | 双记忆设计，短期跟踪动作，长期积累经验，整合专家工具。 | 解决内镜诊断中多步流程协调及复杂临床工作流处理难题。 | 内镜视觉诊断 |
| 5 | http://arxiv.org/abs/2508.03341v3 | Nemori: Self-Organizing Agent Memory Inspired by Cognitive Science | 提出自组织记忆架构，基于事件分割与自由能原理实现自适应知识进化 | 解决 LLM 长上下文记忆粒度 arbitrary 与被动提取问题 | 长周期交互的自主智能体 |
| 6 | http://arxiv.org/abs/2508.06433v3 | Memp: Exploring Agent Procedural Memory | 将过去智能体轨迹提炼为细粒度指令与脚本抽象，构建可更新程序记忆 | LLM 智能体程序记忆脆弱，手动工程或静态参数纠缠 | 智能体程序记忆 |
| 7 | http://arxiv.org/abs/2508.08774v1 | Designing Memory-Augmented AR Agents for Spatiotemporal Reasoning in Personalized Task Assistance | 提出记忆增强 AR 智能体概念框架，含时空记忆模块 | 解决 AR 智能体无法利用用户长期经验问题 | 增强现实个性化任务辅助 |
| 8 | http://arxiv.org/abs/2508.08997v2 | Intrinsic Memory Agents: Heterogeneous Multi-Agent LLM Systems through Structured Contextual Memory | 代理特定记忆随输出内在演化，通用记忆模板 | 解决多智能体上下文窗口限制及记忆一致性问题 | 复杂协作问题解决 |
| 9 | http://arxiv.org/abs/2508.09736v4 | Seeing, Listening, Remembering, and Reasoning: A Multimodal Agent with Long-Term Memory | 实体中心多模态记忆，自主多轮推理及记忆检索 | 解决多模态智能体缺乏长时记忆及一致性理解问题 | 多模态任务与视频问答 |
| 10 | http://arxiv.org/abs/2508.16629v1 | Learn to Memorize: Optimizing LLM-based Agents with Adaptive Memory Framework | 自适应数据驱动记忆框架，建模记忆周期与 MoE 检索 | 预定义记忆机制成本高，忽视交互场景记忆周期效应 | 通用 LLM 智能体优化 |
| 11 | http://arxiv.org/abs/2508.12379v2 | GraphCogent: Mitigating LLMs' Working Memory Constraints via Multi-Agent Collaboration in Complex Graph Understanding | 协作代理框架，分解图推理为感知、缓冲与执行 | LLM 工作记忆限制，无法 retain 长程图拓扑 | 复杂图理解任务 |
| 12 | http://arxiv.org/abs/2508.12393v2 | MedKGent: A Large Language Model Agent Framework for Constructing Temporally Evolving Medical Knowledge Graph | 双智能体框架，增量构建时序演化医疗知识图谱 | 现有方法忽视知识时序动态与上下文不确定性 | 医疗知识图谱构建 |
| 13 | http://arxiv.org/abs/2508.15294v3 | A Multi-Memory Segment System for Generating High-Quality Long-Term Memory Content in Agents | 多记忆片段系统受认知心理学启发构建高质量记忆 | 现有Agent记忆内容质量低影响召回和响应问题 | Agent长时记忆内容生成 |
| 14 | http://arxiv.org/abs/2508.15305v2 | Coarse-to-Fine Grounded Memory for LLM Agent Planning | 粗到细记忆机制支持灵活场景适应 | 单粒度记忆受经验质量限制、规划灵活性不足问题 | LLM Agent复杂规划任务 |
| 15 | http://arxiv.org/abs/2508.17590v1 | RubikSQL: Lifelong Learning Agentic Knowledge Base as an Industrial NL2SQL System | 终身学习KB：数据库画像+Agent规则挖掘+CoT SQL画像 | 企业NL2SQL隐含意图和领域术语挑战 | 工业级NL2SQL系统 |
| 16 | http://arxiv.org/abs/2508.17906v2 | FinReflectKG: Agentic Construction and Evaluation of Financial Knowledge Graphs | 反射Agent模式最佳，规则+统计+LLM-as-Judge三重评估 | 金融文档复杂，缺乏大规模开放知识图谱数据集 | 金融知识图谱构建 |
| 17 | http://arxiv.org/abs/2508.18040v1 | PerPilot: Personalizing VLM-based Mobile Agents via Memory and Exploration | 记忆检索+推理探索双途径，自主完成个性化指令 | 现有Agent难以处理含用户特定上下文的模糊指令 | 移动端个性化任务执行 |
| 18 | http://arxiv.org/abs/2508.18722v3 | VistaWise: Building Cost-Effective Agent with Cross-Modal Knowledge Graph for Minecraft | 跨模态知识图谱+专用检测模型微调，数据需求百万→几百 | 具身决策缺乏领域知识，微调成本高昂 | Minecraft虚拟开放世界任务 |
| 19 | http://arxiv.org/abs/2508.12630v1 | Semantic Anchoring in Agentic Memory: Leveraging Linguistic Structures for Persistent Conversational Context | 提出语义锚定混合记忆架构，结合依赖解析与核心ference 增强记忆召回 | 解决 LLM 长对话记忆持久性差及细粒度语言结构丢失问题 | 长周期对话系统 |
| 20 | http://arxiv.org/abs/2508.19828v5 | Memory-R1: Enhancing Large Language Model Agents to Manage and Utilize Memories via Reinforcement Learning | RL 框架 equip LLM 主动管理外部记忆，含记忆管理与回答 Agent。 | 解决 LLM 无状态且上下文窗口有限阻碍长程推理的问题。 | LLM 智能体记忆管理 |
| 21 | http://arxiv.org/abs/2508.19855v3 | Youtu-GraphRAG: Vertically Unified Agents for Graph Retrieval-Augmented Complex Reasoning | 垂直统一 Agent 范式，连接图构建与检索，支持自上而下过滤与自下而上推理。 | 解决 GraphRAG 框架中图构建或检索孤立优化导致域转移性能次优的问题。 | 图检索增强复杂推理 |
| 22 | http://arxiv.org/abs/2508.21433v3 | The Complexity Trap: Simple Observation Masking Is as Efficient as LLM Summarization for Agent Context Management | 发现简单观察掩蔽策略成本减半且效果匹配 LLM 总结。 | 解决长上下文历史导致 Agent 推理成本高且总结收益不明问题。 | 软件工程 Agent 上下文管理 |
| 23 | http://arxiv.org/abs/2509.00366v1 | KG-RAG: Enhancing GUI Agent Decision-Making via Knowledge Graph-Driven Retrieval-Augmented Generation | 将碎片化 UI 转换图转化为结构化向量库，增强导航决策。 | 解决 GUI Agent 缺乏特定应用知识导致复杂任务执行困难问题。 | 移动应用 GUI 自动化 |

[返回目录](#目录)

<a id="cat-08"></a>

## 多Agent强化学习

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2508.02027v1 | An Evolving Scenario Generation Method based on Dual-modal Driver Model Trained by Multi-Agent Reinforcement Learning | 多Agent强化学习训练双模态驾驶员模型生成安全关键场景 | 自动驾驶测试场景生成效率低 | 自动驾驶安全测试 |
| 2 | http://arxiv.org/abs/2508.02421v1 | Emergence of Fair Leaders via Mediators in Multi-Agent Reinforcement Learning | 集成调解者的多Agent强化学习框架，最小化控制实现公平领导选择 | Stackelberg博弈中领导选择偏差导致不公平 | 多Agent公平性、博弈论 |
| 3 | http://arxiv.org/abs/2508.02632v1 | Hierarchical Learning-Based Control for Multi-Agent Shepherding of Stochastic Autonomous Agents | 分层学习控制架构，高层决策+底层运动控制，无需显式通信 | 目标Agent随机自主行为导致传统策略失效 | 多Agent牧羊问题、机器人编队 |
| 4 | http://arxiv.org/abs/2508.02948v2 | Sample-Efficient Distributionally Robust Multi-Agent Reinforcement Learning via Online Interaction | MORNAVI算法，在线学习分布鲁棒多Agent强化学习 | 训练部署环境不匹配导致系统失败 | 真实环境多Agent系统部署 |
| 5 | http://arxiv.org/abs/2508.01049v1 | Centralized Adaptive Sampling for Reliable Co-Training of Independent Multi-Agent Policies | 集中式自适应动作采样减少联合采样误差 | 解决独立策略梯度算法收敛至次优均衡的问题 | 多智能体强化学习合作博弈 |
| 6 | http://arxiv.org/abs/2508.01522v3 | Decentralized Aerial Manipulation of a Cable-Suspended Load using Multi-Agent Reinforcement Learning | 去中心化 MARL 策略实现真实世界 6-DoF 负载操控 | 解决集中式控制器计算成本高与通信依赖问题 | 微型航空器协同负载操控 |
| 7 | http://arxiv.org/abs/2508.07001v1 | Consensus-based Decentralized Multi-agent Reinforcement Learning for Random Access Network Optimization | 采用完全去中心化 MARL 架构，基于共识交换局部奖励。 | 解决随机接入网络中碰撞最小化与传输公平性问题。 | 无线网络优化 |
| 8 | http://arxiv.org/abs/2508.11687v1 | Agent-Based Anti-Jamming Techniques for UAV Communications in Adversarial Environments: A Comprehensive Survey | 综述基于 Agent 的自主抗干扰技术，形式化 P-D-A 决策框架。 | 解决动态对抗环境中 UAV 通信可靠性与弹性挑战。 | UAV 通信安全 |
| 9 | http://arxiv.org/abs/2508.03864v2 | Evo-MARL: Co-Evolutionary Multi-Agent Reinforcement Learning for Internalized Safety | 通过共进化 MARL 使任务代理内部化防御能力，无需外部安全模块 | 解决外部 guard 模块单点故障与保护有限问题 | 多模态大模型多智能体系统 |
| 10 | http://arxiv.org/abs/2508.04652v7 | LLM Collaboration With Multi-Agent Reinforcement Learning | 建模 LLM 协作为 cooperative MARL 问题，提出 MAGRPO 算法 | 解决 LLM 预训练独立未优化 coordination 与 reward 设计复杂问题 | LLM 写作与编码协作 |
| 11 | http://arxiv.org/abs/2508.04682v2 | TurboTrain: Towards Efficient and Balanced Multi-Task Learning for Multi-Agent Perception and Prediction | 提出多代理时空预训练与平衡多任务学习策略，简化训练流程 | 解决多代理系统端到端训练需大量手动设计与监控问题 | 协同驾驶感知与预测 |
| 12 | http://arxiv.org/abs/2508.05154v1 | Domain-driven Metrics for Reinforcement Learning: A Case Study on Epidemic Control using Agent-based Simulation | 开发领域驱动的 RL 指标，结合传统与 SOTA 指标评估疫情控制 | RL 基于 ABM 模型性能评估缺乏标准化指标 | 疫情控制模拟 |
| 13 | http://arxiv.org/abs/2508.06042v1 | Society of Mind Meets Real-Time Strategy: A Hierarchical Multi-Agent Framework for Strategic Reasoning | 分层多智能体框架，专用模仿学习智能体在元控制器下协作战略推理 | LLM 在实时战略游戏中难以管理资源与适应动态战场 | 实时战略游戏 |
| 14 | http://arxiv.org/abs/2508.06061v1 | Policy Optimization in Multi-Agent Settings under Partially Observable Environments | 利用适应性社会学习估计部分可观察全局状态，交替社会学习与 MARL | 部分可观察环境下 MARL 策略优化评估困难 | 部分可观察 MARL |
| 15 | http://arxiv.org/abs/2508.06269v2 | OM2P: Offline Multi-Agent Mean-Flow Policy | 离线多智能体均值流策略算法，实现高效单步动作采样 | 生成模型在离线 MARL 中采样效率低，训练时间长 | 离线多智能体 RL |
| 16 | http://arxiv.org/abs/2508.06767v1 | PANAMA: A Network-Aware MARL Framework for Multi-Agent Path Finding in Digital Twin Ecosystems | 网络感知 MARL 框架，采用优先不对称性进行多智能体路径寻找 | 数字孪生生态系统中数据共享与多智能体协调缺乏鲁棒性 | 数字孪生路径规划 |
| 17 | http://arxiv.org/abs/2508.06836v1 | Multi-level Advantage Credit Assignment for Cooperative Multi-Agent Reinforcement Learning | 多级优势信用分配，通过注意力框架识别相关智能体关系构建优势 | cooperative MARL 中多样化任务下的信用分配挑战 | 合作多智能体 RL |
| 18 | http://arxiv.org/abs/2508.08800v2 | Fault Tolerant Multi-Agent Learning with Adversarial Budget Constraints | 引入 Switcher-Adversary 机制增强 MARL 鲁棒性 | 解决协作多智能体在故障模式下的鲁棒性问题 | 多智能体强化学习系统 |
| 19 | http://arxiv.org/abs/2508.08882v4 | Reducing Cognitive Overhead in Tool Use via Multi-Small-Agent Reinforcement Learning | 显式解耦推理与工具使用，多小智能体协作框架 | 解决单智能体工具使用中认知负载干扰问题 | 数学问题求解与工具使用 |
| 20 | http://arxiv.org/abs/2508.09541v1 | Emergence of Hierarchies in Multi-Agent Self-Organizing Systems Pursuing a Joint Objective | 量化智能体间依赖，分析层级动态涌现机制 | 解决 MASOS 中依赖层级涌现及演化因素不明问题 | 多智能体自组织系统 |
| 21 | http://arxiv.org/abs/2508.11706v1 | Centralized Permutation Equivariant Policy for Cooperative Multi-Agent Reinforcement Learning | 集中训练执行框架，全局 - 本地置换等价网络 | 解决分散策略部分可观测性及集中扩展性挑战问题 | 协作多智能体强化学习 |
| 22 | http://arxiv.org/abs/2508.10253v1 | Multi-Agent Reinforcement Learning for Adaptive Resource Orchestration in Cloud-Native Clusters | 异构角色建模，奖励整形整合局部观察与全局反馈 | 解决云原生数据库高资源动态及调度复杂性问题 | 云资源编排与调度 |
| 23 | http://arxiv.org/abs/2508.10340v1 | Multi-Agent Trust Region Policy Optimisation: A Joint Constraint Approach | 两种 KL 阈值分配方法，连接序列策略优化与约束调度 | 解决异构设置中每智能体相同 KL 阈值导致更新慢问题 | 多智能体策略优化 |
| 24 | http://arxiv.org/abs/2508.10423v1 | MASH: Cooperative-Heterogeneous Multi-Agent Reinforcement Learning for Single Humanoid Robot Locomotion | 肢体作为独立智能体，共享全局 critic 协作学习 | 解决单足式机器人 locomotion 训练收敛及协作问题 | 人形机器人运动控制 |
| 25 | http://arxiv.org/abs/2508.11553v1 | SeamlessFlow: A Trainer Agent Isolation RL Framework Achieving Bubble-Free Pipelines via Tag Scheduling | 数据平面解耦训练与执行，标签驱动调度消除流水线气泡 | 工业级 RL 训练与执行耦合，GPU 利用率低 | 大规模强化学习部署 |
| 26 | http://arxiv.org/abs/2508.12087v2 | MAPF-World: Action World Model for Multi-Agent Path Finding | 自回归动作世界模型，统一情境理解与动作生成 | 现有求解器对环境动态与代理依赖建模有限 | 多机器人路径规划 |
| 27 | http://arxiv.org/abs/2508.14676v1 | Adaptive Vision-Based Coverage Optimization in Mobile Wireless Sensor Networks: A Multi-Agent Deep Reinforcement Learning Approach | 视觉基MARL-DRL框架实现传感器自主部署 | 传感器网络覆盖重叠、能耗高、静态部署局限问题 | 移动无线传感器网络/IoT |
| 28 | http://arxiv.org/abs/2508.14679v1 | Energy-Efficient Routing Algorithm for Wireless Sensor Networks: A Multi-Agent Reinforcement Learning Approach | Q学习多Agent系统动态适应传输路径 | 传感器网络能耗管理、节点过早耗尽问题 | 无线传感器网络/IoT应用 |
| 29 | http://arxiv.org/abs/2508.15207v1 | Adversarial Agent Behavior Learning in Autonomous Driving Using Deep Reinforcement Learning | 学习基于方法推导规则Agent的对抗行为 | 自动驾驶中周围Agent行为建模不充分问题 | 自动驾驶安全测试场景 |
| 30 | http://arxiv.org/abs/2508.15652v2 | Understanding Action Effects through Instrumental Empowerment in Multi-Agent Reinforcement Learning | 基于信息论Shapley值量化Agent因果影响力 | 无价值反馈时推断Agent贡献、MARL可解释性问题 | 合作/竞争MARL系统行为分析 |
| 31 | http://arxiv.org/abs/2508.16410v2 | Optimal Multi-agent Path Finding in Continuous Time | δ-BR分支规则恢复CCBS算法的可靠性和终止保证 | 连续时间MAPF中CCBS算法可能不终止或返回次优解问题 | 连续时间多Agent路径规划 |
| 32 | http://arxiv.org/abs/2508.16490v1 | Multi-agent Robust and Optimal Policy Learning for Data Harvesting | 使用PPO+Lagrangian Penalty，加入状态正则化增强鲁棒性 | 多智能体高效采集传感器节点数据 | 二维环境中分布式传感器数据采集 |
| 33 | http://arxiv.org/abs/2508.17971v1 | Neural Algorithmic Reasoners informed Large Language Model for Multi-Agent Path Finding | LLM-NAR：NAR(GNN)引导LLM，首次整合GNN与地图信息 | LLM在MAPF任务中表现不佳，需规划与协调 | 多Agent路径规划 |
| 34 | http://arxiv.org/abs/2508.18610v1 | Scalable Fairness Shaping with LLM-Guided Multi-Agent Reinforcement Learning for Peer-to-Peer Electricity Markets | FairMarket-RL：LLM评论器生成公平性评分 shaping 奖励 | P2P电力市场缺乏实时公平性指导，侧重效率 | 分布式电力交易市场 |
| 35 | http://arxiv.org/abs/2508.18669v1 | MUA-RL: Multi-turn User-interacting Agent Reinforcement Learning for agentic tool use | 首次将LLM模拟用户整合进RL训练循环，动态多轮交互 | 现有RL缺乏动态用户集成，工具调用能力有限 | 多轮工具使用Agent |
| 36 | http://arxiv.org/abs/2508.18708v3 | Skill-Aligned Fairness in Multi-Agent Learning for Collaboration in Healthcare | FairSkillMARL：工作量平衡+技能任务对齐双目标公平 | 现有公平性忽视Agent专业知识和协调需求 | 医疗团队协作调度 |
| 37 | http://arxiv.org/abs/2508.12845v2 | CAMAR: Continuous Actions Multi-Agent Routing | 设计连续动作空间多智能体路径规划基准，支持经典规划与 MARL 混合 | 解决现有 MARL 基准缺乏连续空间及复杂协调任务挑战问题 | 多智能体路径规划 |
| 38 | http://arxiv.org/abs/2508.13608v1 | Towards safe control parameter tuning in distributed multi-agent systems | 提出安全贝叶斯优化算法，整合时空核函数处理分布式多 Agent 控制 | 解决安全关键问题中样本效率低及未知非凸奖励约束优化问题 | 分布式多 Agent 控制 |
| 39 | http://arxiv.org/abs/2508.13661v3 | MACTAS: Self-Attention-Based Inter-Agent Communication in Multi-Agent Reinforcement Learning with Action-Value Function Decomposition | 引入自注意力通信机制，完全可微且参数固定独立于 Agent 数量 | 解决现有 MARL 通信协议复杂不可微及大规模系统扩展性问题 | 多 Agent 强化学习 |
| 40 | http://arxiv.org/abs/2508.14131v1 | An Improved Multi-Agent Algorithm for Cooperative and Competitive Environments by Identifying and Encouraging Cooperation among Agents | 基于 MADDPG 引入新参数，识别并鼓励 Agent 间合作行为增加奖励 | 解决现有算法在多 Agent 强化学习环境中合作行为 addressing 不足问题 | 合作竞争环境 |
| 41 | http://arxiv.org/abs/2509.02579v2 | Latent Variable Modeling in Multi-Agent Reinforcement Learning via Expectation-Maximization for UAV-Based Wildlife Protection | 引入基于 EM 的潜变量建模，增强多智能体在不确定性下的探索与协作。 | 解决广阔部分可观测环境中野生动物保护实时响应难的问题。 | 无人机野生动物保护协作 |
| 42 | http://arxiv.org/abs/2508.19488v1 | PoolFlip: A Multi-Agent Reinforcement Learning Security Environment for Cyber Defense | 扩展 FlipIt 游戏为多智能体 Gym 环境，提出 Flip-PSRO 训练防御 Agent。 | 解决现有网络防御框架依赖启发式导致脆弱且无法适应新攻击的问题。 | 网络防御多智能体强化学习 |
| 43 | http://arxiv.org/abs/2508.19945v5 | Constraint Learning in Multi-Agent Dynamic Games from Demonstrations of Local Nash Interactions | 基于逆动态游戏算法从局部 Nash 均衡演示中学习参数约束。 | 解决多智能体动态游戏中从交互演示学习安全与不安全集约束的问题。 | 多智能体动态游戏约束学习 |
| 44 | http://arxiv.org/abs/2508.20315v2 | Multi-Agent Reinforcement Learning in Intelligent Transportation Systems: A Comprehensive Survey | 全面 survey MARL 在 ITS 中的应用，分类协调模型与学习算法。 | 解决 ITS 中多智能体自主决策协调挑战及现实部署阻碍的问题。 | 智能交通系统多智能体强化学习 |
| 45 | http://arxiv.org/abs/2508.20818v1 | cMALC-D: Contextual Multi-Agent LLM-Guided Curriculum Learning with Diversity-Based Context Blending | 利用 LLM 生成语义课程并引入多样性上下文混合机制。 | 解决上下文 MARL 训练依赖噪声代理信号且易模式坍塌问题。 | 交通信号控制等动态环境 |
| 46 | http://arxiv.org/abs/2508.20923v1 | Finite-Time Guarantees for Multi-Agent Combinatorial Bandits with Nonstationary Rewards | 提出首个结合非平稳奖励的组合多臂老虎机框架。 | 解决干预效果随时间动态变化导致资源分配决策困难的问题。 | 社区健康干预与广告投放 |
| 47 | http://arxiv.org/abs/2509.00678v1 | Nash Q-Network for Multi-Agent Cybersecurity Simulation | 提出 Nash Q-Network 直接收敛至稳态均衡，学习纳什最优策略。 | 解决网络安全防御中多 Agent 训练复杂且非平稳不稳定问题。 | 网络安全攻防仿真 |

[返回目录](#目录)

<a id="cat-09"></a>

## Agent学习与自进化

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2508.02085v6 | SE-Agent: Self-Evolution Trajectory Optimization in Multi-Step Reasoning with LLM-Based Agents | 自我进化框架通过修订、重组、精炼优化推理轨迹 | 多步推理轨迹利用不足导致次优结果 | 复杂推理任务、GitHub问题修复 |
| 2 | http://arxiv.org/abs/2508.02621v2 | HealthFlow: A Self-Evolving AI Agent with Meta Planning for Autonomous Healthcare Research | 自进化Agent通过元规划提炼程序性成功失败到结构化知识库 | 当前Agent受静态预定义策略限制 | 医疗健康科学研究 |
| 3 | http://arxiv.org/abs/2508.02959v2 | Polymath: A Self-Optimizing Agent with Dynamic Hierarchical Workflow | 自优化Agent，多网格图优化+自反思引导进化算法 | 现有方法依赖标注数据，难以解决动态问题 | 编码/数学/多轮问答任务 |
| 4 | http://arxiv.org/abs/2508.03248v2 | Federated Learning Enhanced by Feature Reconstruction for Semantic Communication Module Updates of Agents | FedSFR框架，语义特征重建提升训练稳定性和通信效率 | Agent语义通信模块知识不匹配导致性能下降 | 向量量化图像语义通信系统 |
| 5 | http://arxiv.org/abs/2508.00271v2 | MetaAgent: Toward Self-Evolving Agent via Tool Meta-Learning | 提出元工具学习范式，代理通过实践自我进化 | 解决知识缺口与长期任务中的推理策略优化 | 通用知识发现任务 |
| 6 | http://arxiv.org/abs/2508.01550v2 | RepoForge: Training a SOTA Fast-thinking SWE Agent with an End-to-End Data Curation Pipeline Synergizing SFT and RL at Scale | 端到端数据策展流水线协同 SFT 与 RL 训练 SWE 智能体 | 解决 SWE 智能体训练中基础设施贵与数据稀缺瓶颈 | 软件工程智能体训练 |
| 7 | http://arxiv.org/abs/2508.01612v1 | Augmented Reinforcement Learning Framework For Enhancing Decision-Making In Machine Learning Models Using External Agents | 引入外部智能体作为监督者进行决策路径纠正 | 解决强化学习中垃圾输入导致决策错误与数据质量低 | 文档识别与信息提取决策 |
| 8 | http://arxiv.org/abs/2508.07407v2 | A Comprehensive Survey of Self-Evolving AI Agents: A New Paradigm Bridging Foundation Models and Lifelong Agentic Systems | 统一概念框架，综述自进化技术，涵盖输入、系统、环境及优化器。 | 解决现有 Agent 系统部署后静态配置，无法适应动态环境的问题。 | 自进化 AI 系统 |
| 9 | http://arxiv.org/abs/2508.07522v1 | Evolutionary Optimization of Deep Learning Agents for Sparrow Mahjong | 结合深度学习与进化策略优化 LSTM 网络，训练麻雀 AI 决策代理。 | 解决非确定性部分 observable 游戏中策略优化问题。 | 游戏 AI/麻雀 |
| 10 | http://arxiv.org/abs/2508.07976v4 | Beyond Ten Turns: Unlocking Long-Horizon Agentic Search with Large-Scale Asynchronous RL | 可扩展异步 RL 训练，支持长程搜索，Agent 自主合成高质量 QA。 | 解决现有在线 RL 方法轮次限制及搜索智能扩展性问题。 | 搜索 Agent 训练 |
| 11 | http://arxiv.org/abs/2508.03501v2 | Training Long-Context, Multi-Turn Software Engineering Agents with Reinforcement Learning | 应用强化学习训练长上下文多轮软件工程代理，显著提升 Pass@1 | 解决单 turn RL 无法处理 stateful 环境多轮交互问题 | 软件工程自动化任务 |
| 12 | http://arxiv.org/abs/2508.03680v1 | Agent Lightning: Train ANY AI Agents with Reinforcement Learning | 实现代理执行与训练完全解耦，支持任意 AI 代理的 RL 训练 | 解决现有 RL 方法与代理框架紧耦合导致集成困难问题 | 通用 AI 代理训练 |
| 13 | http://arxiv.org/abs/2508.04037v2 | Evolving in Tasks: Empowering the Multi-modality Large Language Model as the Computer Use Agent | 提出自进化代理，通过自动数据生成与步级 RL 提升计算机操作能力 | 解决现有代理性能不足且依赖人工标注问题 | 计算机操作任务 |
| 14 | http://arxiv.org/abs/2508.15784v3 | Emergent time-keeping mechanisms in a deep reinforcement learning agent performing an interval timing task | 发现 DRL 代理中 emergent 振荡神经激活机制，类比生物计时模型 | 解决生物系统 temporal processing 机制难以理解问题 | 深度强化学习代理机制 |
| 15 | http://arxiv.org/abs/2508.13167v1 | Chain-of-Agents: End-to-End Agent Foundation Models via Multi-Agent Distillation and Agentic RL | 通过多代理蒸馏与 Agentic RL 训练端到端 Agent Foundation Models | 解决现有多代理系统计算低效且无法受益于数据学习问题 | 复杂问题解决模型 |
| 16 | http://arxiv.org/abs/2508.04700v2 | SEAgent: Self-Evolving Computer Use Agent with Autonomous Learning from Experience | 使计算机使用代理通过体验学习自主进化，掌握 novel 软件环境 | 解决 LVLM 缺乏人工标注时难以处理 novel 软件问题 | 计算机使用代理 |
| 17 | http://arxiv.org/abs/2508.06803v2 | SEVADE: Self-Evolving Multi-Agent Analysis with Decoupled Evaluation for Hallucination-Resistant Irony Detection | 自进化多智能体分析框架，解耦评估以抵抗幻觉检测讽刺 | 现有 LLM 方法单视角分析，易受幻觉影响准确性 | 讽刺检测任务 |
| 18 | http://arxiv.org/abs/2508.15805v1 | ALAS: Autonomous Learning Agent for Self-Updating Language Models | 模块化流水线，自动生成课程及微调更新知识 | 解决 LLM 知识截止限制及新兴信息准确性问题 | 大模型持续学习与更新 |
| 19 | http://arxiv.org/abs/2508.11425v2 | Tapas Are Free! Training-Free Adaptation of Programmatic Agents via LLM-Guided Program Synthesis in Dynamic Environments | TAPA 框架，LLM 动态生成符号程序适配高层动作 | 安全关键应用需持续适配动态条件且不影响可靠性 | 网络安全与群体智能 |
| 20 | http://arxiv.org/abs/2508.14751v1 | HERAKLES: Hierarchical Skill Compilation for Open-ended LLM Agents | 两层层次化自目标Agent持续编译掌握的技能 | 开放场景中目标复杂度增长、样本效率低问题 | 开放-ended LLM Agent系统 |
| 21 | http://arxiv.org/abs/2508.16153v2 | Memento: Fine-tuning LLM Agents without Fine-tuning LLMs | 基于记忆的在线RL实现低成本持续适应无需微调 | 现有方法刚性依赖手工反思或计算密集型微调问题 | 通用LLM Agent持续学习 |
| 22 | http://arxiv.org/abs/2508.17057v1 | GRAID: Synthetic Data Generation with Geometric Constraints and Multi-Agentic Reflection for Harmful Content Detection | 几何约束生成+多Agent反思增强数据多样性 | 有害文本分类数据稀缺，覆盖不足 | AI内容安全护栏训练 |
| 23 | http://arxiv.org/abs/2508.18370v2 | Training Language Model Agents to Find Vulnerabilities with CTF-Dojo | CTF-Dojo：658个CTF挑战+CTF-Forge自动管道，执行验证训练 | 可扩展的执行环境稀缺，限制ML Agent训练 | 漏洞发现Agent训练 |
| 24 | http://arxiv.org/abs/2508.12685v3 | ToolACE-MT: Non-Autoregressive Generation for Agentic Multi-Turn Interaction | 提出非自回归迭代生成框架，三阶段构建高质量多轮 Agent 对话数据 | 解决自回归交互生成成本高及效率低的问题 | Agent 训练数据构建 |
| 25 | http://arxiv.org/abs/2508.19005v6 | Building Self-Evolving Agents via Experience-Driven Lifelong Learning: A Framework and Benchmark | 提出经验驱动终身学习框架，含经验探索、长期记忆、技能学习与知识内化。 | 解决 Agent 从静态任务优化向开放世界持续学习进化转变的问题。 | 自进化智能体与终身学习 |
| 26 | http://arxiv.org/abs/2508.19506v1 | Learning Game-Playing Agents with Generative Code Optimization | 将策略表示为 Python 程序，利用 LLM 通过执行轨迹与自然语言反馈自改进。 | 解决游戏 Agent 训练时间长与环境交互次数多的问题，实现高效适应。 | 游戏智能体策略学习 |
| 27 | http://arxiv.org/abs/2508.20324v3 | Can Compact Language Models Search Like Agents? Distillation-Guided Policy Optimization for Preserving Agentic RAG Capabilities | 提出 DGPO，利用教师演示冷启动与持续指导，使紧凑模型保留 Agentic RAG 能力。 | 解决紧凑模型因初始性能差导致 RL 训练稀疏奖励与不稳定的问题。 | 紧凑语言模型 Agentic RAG |
| 28 | http://arxiv.org/abs/2508.20404v2 | AWorld: Orchestrating the Training Recipe for Agentic AI | 构建大规模 Agent-环境交互系统，加速经验收集与强化学习训练。 | 解决复杂基准测试中经验生成效率低导致 RL 训练不可行的问题。 | 通用 Agentic AI 系统训练 |
| 29 | http://arxiv.org/abs/2508.21104v3 | PVPO: Pre-Estimated Value-Based Policy Optimization for Agentic Reasoning | 引入优势参考锚点与数据预采样，减少 Rollout 依赖并纠正偏差。 | 解决无批评 RL 方法依赖多重采样易陷局部最优且成本高的问题。 | 通用 Agentic 推理任务 |
| 30 | http://arxiv.org/abs/2508.20722v1 | rStar2-Agent: Agentic Reasoning Technical Report | 采用 GRPO-RoC 算法与高效 RL 基础设施，实现数学推理 SOTA。 | 解决大模型在代码环境下推理噪声大且训练成本高的问题。 | 数学推理与代码工具使用 |
| 31 | http://arxiv.org/abs/2508.21314v2 | Convergence of regularized agent-state-based Q-learning in POMDPs | 证明正则化 Agent 状态 Q 学习在 mild 条件下收敛至固定点。 | 解决实践中 Q 学习算法使用非信念状态更新缺乏理论保证问题。 | POMDP 环境下的 RL 算法 |
| 32 | http://arxiv.org/abs/2508.21476v1 | Igniting Creative Writing in Small Language Models: LLM-as-a-Judge versus Multi-Agent Refined Rewards | 比较 LLM 裁判与多 Agent 奖励策略，优化小模型创意写作。 | 解决小模型创意写作新颖性不足且 RLHF 成本高的问题。 | 小语言模型创意生成 |
| 33 | http://arxiv.org/abs/2509.00251v2 | Instruction-Level Weight Shaping: A Framework for Self-Improving AI Agents | 系统指令作为伪参数，经反思与反馈更新并蒸馏至权重。 | 解决 RAG 延迟高、微调成本高且易灾难性遗忘的问题。 | 企业支持与动态领域 Agent |
| 34 | http://arxiv.org/abs/2509.00629v1 | Can Multi-turn Self-refined Single Agent LMs with Retrieval Solve Hard Coding Problems? | 结合多轮自评判、反思与 episodic 检索，提升代码问题解决率。 | 解决 competitive programming 任务中模型算法思维与想象力不足问题。 | 竞争性编程与代码生成 |

[返回目录](#目录)

<a id="cat-10"></a>

## 人机协作Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2508.02376v1 | Talking Surveys: How Photorealistic Embodied Conversational Agents Shape Response Quality, Engagement, and Satisfaction | 具身对话Agent嵌入在线调查，AI视频生成+语音识别+LLM | 在线调查缺乏人际互动导致敷衍回答 | 用户体验研究、在线调查 |
| 2 | http://arxiv.org/abs/2508.02966v1 | Measuring Human Leadership Skills with Artificially Intelligent Agents | AI Agent作为人类参与者代理测量领导技能，强相关性验证 | 人类团队协作技能测量复杂耗时 | 领导力测量、社会实验 |
| 3 | http://arxiv.org/abs/2508.01169v1 | WIP: Enhancing Game-Based Learning with AI-Driven Peer Agents | 集成 AI 同伴智能体的游戏化学习平台 SPARC | 解决 K-12 STEM 教育中学生动机不足与概念理解困难 | K-12  STEM 教育与游戏化学习 |
| 4 | http://arxiv.org/abs/2508.01503v1 | A Theory of Adaptive Scaffolding for LLM-Based Pedagogical Agents | 结合证据中心设计与社会认知理论的自适应支架框架 | 解决 LLM 教学智能体缺乏坚实理论基础与适应性 | STEM+C 学习与形成性评估 |
| 5 | http://arxiv.org/abs/2508.08101v1 | ChatGPT on the Road: Leveraging Large Language Model-Powered In-vehicle Conversational Agents for Safer and More Enjoyable Driving Experience | 探索基于 ChatGPT 的车内 Agent，支持连续多轮对话。 | 解决传统车内 Agent 依赖预脚本及交互不自然的问题。 | 智能驾驶交互 |
| 6 | http://arxiv.org/abs/2508.08645v1 | Quick on the Uptake: Eliciting Implicit Intents from Human Demonstrations for Personalized Mobile-Use Agents | 分析显性与隐性意图流，构建 SOP 库与用户习惯库以对齐意图。 | 解决现有方法忽视隐性意图流导致难以构建个性化移动 Agent 问题。 | 移动任务自动化 |
| 7 | http://arxiv.org/abs/2508.04025v1 | Uncertainty-Aware GUI Agent: Adaptive Perception through Component Recommendation and Human-in-the-Loop Refinement | 引入不确定性感知机制，通过组件推荐与人机回环减少决策歧义 | 解决 GUI 代理输入冗余与决策模糊问题 | 移动任务自动化 |
| 8 | http://arxiv.org/abs/2508.05116v1 | Beyond Automation: Socratic AI, Epistemic Agency, and the Implications of the Emergence of Orchestrated Multi-Agent Learning Architectures | 苏格拉底式 AI 导师，通过结构化对话支架学生研究问题发展 | 生成式 AI 导致学生去技能化，缺乏批判性思维 | 高等教育与学生 |
| 9 | http://arxiv.org/abs/2508.05728v1 | CLAPP: The CLASS LLM Agent for Pair Programming | 交互式 AI 助手，结合多智能体编排与语义搜索支持 CLASS 求解器编程 | 科学家不熟悉 AI 工具，计算宇宙学协作效率低 | 计算宇宙学编程 |
| 10 | http://arxiv.org/abs/2508.06955v2 | Your Thoughtful Opponent: Embracing Cognitive Conflict with Peer Agent | 模拟 deliberative 对话伙伴，在困境游戏中诱导社会认知冲突 | 教育中缺乏培养民主技能与协作决策的对话伙伴 | 教育对话系统 |
| 11 | http://arxiv.org/abs/2509.05298v1 | Livia: An Emotion-Aware AR Companion Powered by Modular AI Agents and Progressive Memory Compression | 模块化 AI 架构，结合多模态情感计算与记忆压缩 | 解决孤独感问题，提供个性化情感支持 | 情感陪伴与心理健康 |
| 12 | http://arxiv.org/abs/2508.16609v1 | Social Identity in Human-Agent Interaction: A Primer | 综述社会身份理论在人工社会智能体中应用 | 解决理解机器作为社会实体角色及潜在风险问题 | 人机交互与社会机器人 |
| 13 | http://arxiv.org/abs/2508.11030v3 | Families' Vision of Generative AI Agents for Household Safety Against Digital and Physical Threats | 提出多智能体系统设计，包含隐私保护原则 | 家庭数字与物理安全挑战及代际信任差异 | 家庭安全与教育场景 |
| 14 | http://arxiv.org/abs/2508.11781v1 | Behavioral and Symbolic Fillers as Delay Mitigation for Embodied Conversational Agents in Virtual Reality | 多模态行为填充器，缓解 VR 中 ECA 响应延迟 | LLM 计算延迟导致交互不自然或用户沮丧 | 虚拟现实对话代理 |
| 15 | http://arxiv.org/abs/2508.12388v1 | When motivation can be more than a message: designing agents to boost physical activity | 设计代理作为共同参与者，体现努力而非仅指令 | 虚拟代理缺乏关系深度，模糊活动水平破坏信任 | 体育活动干预 |
| 16 | http://arxiv.org/abs/2508.14787v1 | Challenges and Opportunities for Participatory Design of Conversational Agents for Young People's Wellbeing | 四国参与式设计研究对话Agent支持青少年福祉 | 跨社会文化语境下儿童Agent设计的挑战与机会 | 青少年心理健康对话Agent |
| 17 | http://arxiv.org/abs/2508.14825v1 | From Passive Tool to Socio-cognitive Teammate: A Conceptual Framework for Agentic AI in Human-AI Collaborative Learning | 提出APCP四级Agent代理性模型框架 | 缺乏理解人机协作学习中Agent角色的概念框架 | 人机协作学习环境设计 |
| 18 | http://arxiv.org/abs/2508.16701v2 | Generative Artificial Intelligence and Agents in Research and Teaching | 综合分析GenAI和Agent在研究与教育中的应用 | GenAI在学术实践和教育中的整合、伦理挑战问题 | 学术研究与教育教学 |
| 19 | http://arxiv.org/abs/2508.17676v1 | "I Can't Join, But I Will Send My Agent: Stand-in Enhanced Asynchronous Meetings (SEAM)" | VR会议中虚拟Agent代表缺席用户，增强社会临场感 | 异步会议中缺席者难以参与和获取信息 | 虚拟协作会议系统 |
| 20 | http://arxiv.org/abs/2508.12896v1 | Reliability, Embeddedness, and Agency: A Utility-Driven Mathematical Framework for Agent-Centric AI Adoption | 形式化可靠性、嵌入性、代理性三公理，建模采用率效用函数 | 解决多步任务 Agent 系统持续采用缺乏数学框架及效用驱动问题 | Agent 系统采用评估 |
| 21 | http://arxiv.org/abs/2508.14344v1 | ISCA: A Framework for Interview-Style Conversational Agents | 提出低计算非生成系统，实现 interview-style 对话 Agent  facilitating 数据收集 | 解决定性数据收集需要控制标准化 conversational flow 及定量分析问题 | 定性数据收集 |
| 22 | http://arxiv.org/abs/2508.21087v1 | Can LLMs Generate Behaviors for Embodied Virtual Agents Based on Personality Traits? | 利用人格提示生成虚拟 Agent 的言语与非言语行为，用户可识别特质。 | 解决虚拟 Agent 行为缺乏人格一致性且难以被人类观察者感知的问题。 | 具身虚拟 Agent 人格行为 |
| 23 | http://arxiv.org/abs/2508.19679v1 | InquireMobile: Teaching VLM-based Mobile Agent to Request Human Assistance via Reinforcement Fine-Tuning | 提出 InquireMobile 模型，通过强化微调教 VLM 手机 Agent 在关键点请求人类帮助。 | 解决完全自主范式在模型能力不足时存在潜在安全风险的问题。 | VLM 手机智能体安全交互 |
| 24 | http://arxiv.org/abs/2508.19942v1 | Socially Interactive Agents for Preserving and Transferring Tacit Knowledge in Organizations | 社会交互 Agent 通过多模态行为模拟专家角色，帮助员工外部化隐性知识。 | 解决隐性知识保留与转移依赖人工 facilitator 且缺乏可扩展性的问题。 | 组织隐性知识转移 |
| 25 | http://arxiv.org/abs/2508.21209v1 | Designing Smarter Conversational Agents for Kids: Lessons from Cognitive Work and Means-Ends Analyses | 基于认知工作分析设计脚手架对话树，增强儿童交互体验。 | 解决儿童使用对话 Agent 缺乏结构化支持与个性化上下文问题。 | 儿童教育与娱乐交互 |
| 26 | http://arxiv.org/abs/2509.04465v1 | Emotionally-Aware Agents for Dispute Resolution | 利用 LLM 识别情感强度，辅助管理冲突升级与解决。 | 解决纠纷解决中情感表达影响结果且缺乏自动洞察的问题。 | 买卖纠纷调解与谈判 |
| 27 | http://arxiv.org/abs/2508.21456v1 | Morae: Proactively Pausing UI Agents for User Choices | 自动识别决策点并暂停，让用户参与关键选择以增强代理权。 | 解决 UI Agent 端到端执行忽略用户偏好与关键上下文信息问题。 | 视障用户 UI 辅助操作 |

[返回目录](#目录)

<a id="cat-11"></a>

## 低代码/无代码Agent平台

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2508.02470v1 | AIAP: A No-Code Workflow Builder for Non-Experts with Natural Language and Multi-Agent Collaboration | 无代码平台整合自然语言输入与可视化工作流，多Agent分解模糊指令 | 非专家难以清晰表达意图和管理系统复杂度 | AI服务设计、非专家用户 |
| 2 | http://arxiv.org/abs/2508.04108v3 | XARP Tools: An Extended Reality Platform for Humans and AI Agents | 提供 AI-XR 开发工具包，通过 JSON-RPC 抽象底层集成细节 | 解决 AI-XR 系统开发工具链碎片化与集成困难问题 | 扩展现实与 AI 应用开发 |

[返回目录](#目录)

<a id="cat-12"></a>

## 具身智能Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2508.06326v2 | A "good regulator theorem" for embodied agents | 提出具身Agent"好调节器定理"，观察者视角解释信念更新 | Conant-Ashby定理难以推广到Artificial Life系统 | 具身Agent理论分析 |
| 2 | http://arxiv.org/abs/2508.02629v2 | HyCodePolicy: Hybrid Language Controllers for Multimodal Monitoring and Decision in Embodied Agents | 混合语言控制框架，代码合成+几何 grounding+感知监控+迭代修复闭环 | 具身Agent缺乏自适应监控和代码修复机制 | 机器人操作任务 |
| 3 | http://arxiv.org/abs/2508.03216v1 | Navigation Pixie: Implementation and Empirical Study Toward On-demand Navigation Agents in Commercial Metaverse | 按需导航Agent，松散耦合架构整合空间元数据与LLM | 商业元宇宙缺乏动态适应用户兴趣导航 | 商业元宇宙平台导航 |
| 4 | http://arxiv.org/abs/2508.01415v6 | RoboMemory: A Brain-inspired Multi-memory Agentic Framework for Interactive Environmental Learning in Physical Embodied Systems | 脑启发多记忆框架统一空间、时间、 episodic 与语义记忆 | 解决具身智能体部分可观测性与长程适应效率低 | 物理具身系统与环境学习 |
| 5 | http://arxiv.org/abs/2508.06990v1 | Imaginative World Modeling with Scene Graphs for Embodied Agent Navigation | 提出 SGImagineNav，利用场景图进行想象性导航，预测未来场景。 | 解决未见环境中语义导航目标查找慢的问题。 | 具身代理导航 |
| 6 | http://arxiv.org/abs/2508.07033v1 | $\mathcal{P}^3$: Toward Versatile Embodied Agents | 集成实时感知与动态调度，支持主动感知、即插即用工具及多任务规划。 | 解决具身代理在动态环境中感知、工具使用及多任务规划挑战。 | 通用具身代理 |
| 7 | http://arxiv.org/abs/2508.16602v1 | An Embodied AR Navigation Agent: Integrating BIM with Retrieval-Augmented Generation for Language Guidance | 集成 BIM 与多 Agent RAG 框架，支持灵活语言驱动的目标检索与路径规划。 | 解决 prior AR 导航系统依赖刚性输入及缺乏空间语义推理问题。 | 增强现实导航 |
| 8 | http://arxiv.org/abs/2508.07642v2 | Breaking Down and Building Up: Mixture of Skill-Based Vision-and-Language Navigation Agents | 提出 SkillNav，将导航分解为原子技能，由专用 Agent 处理。 | 解决 VLN 代理在未见场景及复杂时空推理中泛化能力不足问题。 | 视觉语言导航 |
| 9 | http://arxiv.org/abs/2508.08574v2 | DeepFleet: Multi-Agent Foundation Models for Mobile Robots | suite of foundation models 支持大规模移动机器人车队协调与规划。 | 解决大规模机器人车队协调及规划的基础模型设计问题。 | 移动机器人车队 |
| 10 | http://arxiv.org/abs/2508.03998v1 | Transferring Expert Cognitive Models to Social Robots via Agentic Concept Bottleneck Models | 通过概念瓶颈模型将专家认知模型迁移至社交机器人，确保透明性 | 解决 facilitator 认知负荷高与黑盒模型缺乏信任问题 | 群体会议社交机器人 |
| 11 | http://arxiv.org/abs/2508.04418v1 | Think Before You Segment: An Object-aware Reasoning Agent for Referring Audio-Visual Segmentation | 分解 Think-Ground-Segment 过程，通过多模态推理实现参考分割 | 解决 prior 工作依赖像素监督与缺乏可解释性问题 | 音频视觉分割任务 |
| 12 | http://arxiv.org/abs/2508.04691v1 | From MAS to MARS: Coordination Failures and Reasoning Trade-offs in Hierarchical Multi-Agent Robotic Systems within a Healthcare Scenario | 研究医疗场景中分层多智能体机器人系统协调失败与推理权衡 | 解决先进多代理框架在机器人 real-world 部署 limited 问题 | 医疗多机器人系统 |
| 13 | http://arxiv.org/abs/2508.05294v4 | Towards Embodied Agentic AI: Review and Classification of LLM- and VLM-Driven Robot Autonomy and Interaction | 综述 LLM/VLM 驱动的机器人自主性与交互，提出分类法 | 具身智能体架构与模型集成方法缺乏系统梳理 | 机器人 autonomy 研究 |
| 14 | http://arxiv.org/abs/2508.08930v2 | How Does a Virtual Agent Decide Where to Look? Symbolic Cognitive Reasoning for Embodied Head Rotation | 符号认知推理框架，编码五种人类头部运动动机 | 解决虚拟智能体头部旋转缺乏认知动机问题 | 虚拟人与 embodied 交互 |
| 15 | http://arxiv.org/abs/2508.09423v2 | Distilling LLM Prior to Flow Model for Generalizable Agent's Imagination in Object Goal Navigation | 生成流框架，LLM 空间先验注入目标地图 | 解决物体导航中确定性模型泛化及不确定性忽略问题 | 具身导航与环境理解 |
| 16 | http://arxiv.org/abs/2508.10833v2 | UI-Venus Technical Report: Building High-performance UI Agents with RFT | 基于 Qwen2.5-VL 的 RFT 微调，仅用截图输入实现 SOTA 性能 | UI 接地与导航任务性能不足，训练样本效率低 | 图形用户界面自动化操作 |
| 17 | http://arxiv.org/abs/2508.11286v1 | Scene Graph-Guided Proactive Replanning for Failure-Resilient Embodied Agent | 场景图引导的主动重规划，检测子任务边界失败 | 自主机器人缺乏自适应意识，执行 outdated 假设导致失败 | 具身机器人与家庭任务 |
| 18 | http://arxiv.org/abs/2508.11360v2 | CRAFT-GUI: Curriculum-Reinforced Agent For GUI Tasks | 基于课程学习的 GRPO 框架，结合规则与模型判断奖励 | GUI 任务难度差异大，单一奖励信号导致策略更新低效 | 图形用户界面交互任务 |
| 19 | http://arxiv.org/abs/2508.11412v1 | Towards Embodied Conversational Agents for Reducing Oral Exam Anxiety in Extended Reality | 整合 photorealistic ECA 与实时 LLM，支持 XR 环境排练 | 口试焦虑影响认知表现，缺乏安全重复排练场景 | 高等教育口试准备 |
| 20 | http://arxiv.org/abs/2508.15752v1 | "Does the cafe entrance look accessible? Where is the door?" Towards Geospatial AI Agents for Visual Inquiries | 多模态Agent分析地理空间图像回答视觉问题 | 传统数字地图无法回答地理视觉查询问题 | 地理空间视觉查询Agent |
| 21 | http://arxiv.org/abs/2508.17198v1 | From reactive to cognitive: brain-inspired spatial intelligence for embodied agents | BSC-Nav构建结构化空间记忆，动态检索与语义目标对齐 | 现有MLLM缺乏结构化空间记忆，泛化能力有限 | 物理环境中具身导航 |
| 22 | http://arxiv.org/abs/2508.13530v1 | CrafterDojo: A Suite of Foundation Models for Building Open-Ended Embodied Agents in Crafter | 提供 Crafter 基础模型套件，解锁轻量级类 Minecraft 具身 Agent 研究 | 解决 Minecraft 速度慢及 Crafter 缺乏基础模型驱动进展问题 | 具身 Agent 原型设计 |
| 23 | http://arxiv.org/abs/2508.21767v1 | UItron: Foundational GUI Agent with Advanced Perception and Planning | 系统研究数据工程策略，构建连接移动与 PC 的交互环境。 | 解决 GUI Agent 缺乏操作轨迹数据及基础模型初始能力限制问题。 | 移动与 PC 端 GUI 自动化 |

[返回目录](#目录)

<a id="cat-13"></a>

## Agent可解释性与透明度

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2508.02866v3 | PROV-AGENT: Unified Provenance for Tracking AI Agent Interactions in Agentic Workflows | 扩展W3C PROV，整合MCP和数据可观测性追踪Agent交互溯源 | Agent幻觉错误传播，缺乏透明可追溯性 | Agentic工作流、联邦异构环境 |
| 2 | http://arxiv.org/abs/2508.10501v4 | PASS: Probabilistic Agentic Supernet Sampling for Interpretable and Adaptive Chest X-Ray Reasoning | 自适应采样智能体工作流，概率标注决策路径 | 解决医疗 AI 黑盒推理及多模态集成差问题 | 医疗影像诊断推理 |
| 3 | http://arxiv.org/abs/2508.12555v1 | Illuminating LLM Coding Agents: Visual Analytics for Deeper Understanding and Enhancement | 视觉分析系统，支持代码、过程与 LLM 层级对比分析 | 手动检查输出低效，难以追踪代码演进与改进机会 | 编码智能体行为理解 |

[返回目录](#目录)

<a id="cat-14"></a>

## Agent工具使用与环境交互

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2508.04719v1 | GeoFlow: Agentic Workflow Automation for Geospatial Tasks | 自动生成Agent工作流，提供详细工具调用目标指导地理空间API | 地理空间任务API选择隐式导致成功率低 | 地理空间任务自动化 |
| 2 | http://arxiv.org/abs/2508.03092v1 | Toward Verifiable Misinformation Detection: A Multi-Tool LLM Agent Framework | 三核心工具：精确搜索、来源可信度评估、数值声明验证 | 虚假信息检测复杂，传统方法缺乏可验证推理 | 虚假信息检测、事实核查 |
| 3 | http://arxiv.org/abs/2508.00360v1 | Lucy: edgerunning agentic web search on mobile with machine generated task vectors | 将内部推理视为动态任务向量机器进行优化 | 解决小模型在知识密集型任务中的能力限制 | 移动端智能网页搜索 |
| 4 | http://arxiv.org/abs/2508.03923v3 | CoAct-1: Computer-using Multi-Agent System with Coding Actions | 结合 GUI 控制与代码执行，动态委托子任务给程序员代理 | 解决纯 GUI 操作在复杂长程任务中效率低与脆弱问题 | 计算机自动化任务 |
| 5 | http://arxiv.org/abs/2508.04412v2 | Beyond Pixels: Exploring DOM Downsampling for LLM-Based Web Agents | 提出 DOM 下采样算法，降低 Web 代理输入 token 消耗并保持成功率 | 解决 DOM 快照 token 过大导致 Web 代理不可靠问题 | LLM Web 代理 |
| 6 | http://arxiv.org/abs/2508.04604v2 | TURA: Tool-Augmented Unified Retrieval Agent for AI Search | 结合 RAG 与代理工具使用，访问静态内容与动态实时信息 | 解决传统 RAG 无法处理动态生成内容与实时查询问题 | AI 搜索引擎 |
| 7 | http://arxiv.org/abs/2508.05580v1 | Follow-Your-Instruction: A Comprehensive MLLM Agent for World Data Synthesis | MLLM 驱动框架自动合成高质量 2D/3D/4D 数据，包含收集生成优化 | 真实世界数据收集成本高，手动场景构建扩展性差 | AIGC 数据合成 |
| 8 | http://arxiv.org/abs/2508.05888v2 | Planning Agents on an Ego-Trip: Leveraging Hybrid Ego-Graph Ensembles for Improved Tool Retrieval in Enterprise Task Planning | 基于知识图谱的工具检索框架，利用自我图集成建模工具功能依赖 | 传统工具检索依赖查询相似度，多步任务准确性低 | 企业任务规划 |
| 9 | http://arxiv.org/abs/2508.09129v1 | BrowseMaster: Towards Scalable Web Browsing via Tool-Augmented Programmatic Agent Pair | 规划 - 执行智能体对，编程增强可扩展浏览 | 解决搜索广度与推理深度平衡及噪声输入问题 | 网页浏览与信息检索 |
| 10 | http://arxiv.org/abs/2508.10572v1 | Towards Agentic AI for Multimodal-Guided Video Object Segmentation | 利用 LLM 推理生成动态工作流，迭代交互专用工具 | 解决固定流水线缺乏灵活性及适应动态任务问题 | 视频对象分割 |
| 11 | http://arxiv.org/abs/2508.15144v2 | Mobile-Agent-v3: Fundamental Agents for GUI Automation | GUI-Owl基础模型+Mobile-Agent-v3框架实现GUI自动化 | 开源GUI Agent在跨平台自动化任务上性能不足问题 | 桌面/移动GUI自动化任务 |
| 12 | http://arxiv.org/abs/2508.15222v2 | See it. Say it. Sorted: Agentic System for Compositional Diagram Generation | VLM+LLM迭代循环生成可编辑SVG程序 | 扩散模型生成流程图空间精度和符号结构不足问题 | 草图到流程图转换任务 |
| 13 | http://arxiv.org/abs/2508.15243v1 | Comp-X: On Defining an Interactive Learned Image Compression Paradigm With Expert-driven LLM Agent | 交互式编码Agent统一多功能编码框架 | 传统编解码器编码模式有限、手动选择不友好问题 | 智能交互式图像压缩系统 |
| 14 | http://arxiv.org/abs/2508.17435v1 | An LLM-LVLM Driven Agent for Iterative and Fine-Grained Image Editing | RefineEdit-Agent闭环系统：LLM规划+LVLM反馈评估 | 现有方法缺乏细粒度迭代编辑和智能反馈 | 复杂多轮图像编辑 |
| 15 | http://arxiv.org/abs/2508.18689v2 | AppAgent-Pro: A Proactive GUI Agent System for Multidomain Information Integration and User Assistance | 主动式GUI Agent，预测用户潜在需求进行多领域挖掘 | 现有Agent纯被动响应，信息获取效率受限 | 日常多领域信息获取 |
| 16 | http://arxiv.org/abs/2508.13121v1 | Bayesian Optimization-based Search for Agent Control in Automated Game Testing | 利用贝叶斯优化执行样本高效搜索，控制 Agent 检测游戏关卡 Bug | 解决传统模型可扩展性差及游戏测试地图覆盖效率低问题 | 自动化游戏测试 |
| 17 | http://arxiv.org/abs/2508.13774v1 | Agentic DraCor and the Art of Docstring Engineering: Evaluating MCP-empowered LLM Usage of the DraCor API | 实现 MCP 服务器 enabling LLM 自主交互 DraCor API，强调 Docstring 工程 | 解决 LLM 工具选择及应用可靠性及数字人文基础设施需求问题 | 计算文学研究 |
| 18 | http://arxiv.org/abs/2508.14040v2 | ComputerRL: Scaling End-to-End Online Reinforcement Learning for Computer Use Agents | 提出 API-GUI 范式统一程序调用与 GUI 交互，支持大规模在线 RL 训练 | 解决机器 Agent 与人类桌面环境 mismatch 及训练环境效率不稳定问题 | 桌面自动化 Agent |
| 19 | http://arxiv.org/abs/2508.20637v2 | GDS Agent for Graph Algorithmic Reasoning | 将图算法封装为 MCP 工具，支持预处理与后处理流水线。 | 解决 LLM 难以直接处理与推理大规模图结构数据的问题。 | 图数据科学分析与推理 |

[返回目录](#目录)

<a id="cat-15"></a>

## Agent仿真与社会模拟

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2508.00384v1 | On Learning Closed-Loop Probabilistic Multi-Agent Simulator | 神经交互智能体框架，统一轨迹预测与闭环仿真 | 解决自动驾驶仿真中场景多样性与交互真实性 | 自动驾驶多智能体交通仿真 |
| 2 | http://arxiv.org/abs/2508.00742v2 | Applying Psychometrics to Large Language Model Simulated Populations: Recreating the HEXACO Personality Inventory Experiment with Generative Agents | 重现 HEXACO 人格实验，验证生成智能体的人群代表性 | 解决社会科学研究中人类参与者成本高与代表性问题 | 社会科学研究生成智能体仿真 |
| 3 | http://arxiv.org/abs/2508.07730v1 | SimViews: An Interactive Multi-Agent System Simulating Visitor-to-Visitor Conversational Patterns to Present Diverse Perspectives of Artifacts in Virtual Museums | 模拟不同专业身份的虚拟访客，提供多样化文物解读。 | 解决虚拟博物馆中单一叙事限制及难以维持用户注意力问题。 | 虚拟博物馆 |
| 4 | http://arxiv.org/abs/2508.07745v4 | Chimera: Harnessing Multi-Agent LLMs for Automatic Insider Threat Simulation | 多 Agent 框架自动模拟良性与恶意内部活动，生成系统日志。 | 解决内部威胁检测缺乏高质量 realistic 训练数据的问题。 | 网络安全仿真 |
| 5 | http://arxiv.org/abs/2508.08473v2 | A Minimal Model for Emergent Collective Behaviors in Autonomous Robotic Multi-Agent Systems | 提出最小模型，基于相对位置速度及局部密度控制 Agent 动力学。 | 解决现有模型缺乏避障或形成 rigid 限制 swarm 机器人应用问题。 | 机器人集群行为 |
| 6 | http://arxiv.org/abs/2508.08678v1 | Exploring Large Language Model Agents for Piloting Social Experiments | 开发基于 LLM 驱动实验 Agent 的框架，模拟社会实验。 | 解决计算社会实验中核心组件 Agent 智能不足限制影响问题。 | 计算社会科学 |
| 7 | http://arxiv.org/abs/2508.05622v1 | Simulating Human-Like Learning Dynamics with LLM-Empowered Agents | 基于 LLM 多智能体框架模拟真实教学环境，构建心理画像学习者 | 深度学习难以捕捉人类学习动态与进度追踪 | 教育学习动态模拟 |
| 8 | http://arxiv.org/abs/2508.08726v1 | Simulating Generative Social Agents via Theory-Informed Workflow Design | 提出理论 informed 框架，含动机、规划、学习模块 | 解决社会仿真中行为不一致及泛化能力差问题 | 社会仿真与群体行为模拟 |
| 9 | http://arxiv.org/abs/2508.08837v3 | Debiasing International Attitudes: LLM Agents for Simulating US-China Perception Changes | 集成新闻数据与社交 profile，提出三种去偏机制 | 解决媒体影响跨境态度建模及 LLM 偏见问题 | 计算社会科学与舆论模拟 |
| 10 | http://arxiv.org/abs/2508.11829v1 | Every 28 Days the AI Dreams of Soft Skin and Burning Stars: Scaffolding AI Agents with Hormones and Emotions | 嵌入模拟激素周期系统提示，过滤上下文相关信息 | AI 系统难以从指数级空间确定上下文相关信息 | 上下文相关 AI 与偏见研究 |
| 11 | http://arxiv.org/abs/2508.15047v1 | Emergent Crowds Dynamics from Language-Driven Multi-Agent Interactions | 语言驱动的多Agent交互模拟人群涌现行为 | 传统人群模拟缺乏社会语言交互维度问题 | 人群动画与仿真系统 |
| 12 | http://arxiv.org/abs/2508.15555v2 | HEAS: Hierarchical Evolutionary Agent Simulation Framework for Cross-Scale Modeling and Multi-Objective Search | 分层Agent建模与进化优化统一的Python框架 | 跨尺度耦合建模、多目标搜索可复现性差问题 | 跨学科多层级Agent仿真研究 |
| 13 | http://arxiv.org/abs/2508.15679v1 | An Efficient Open World Environment for Multi-Agent Social Learning | 开放世界多Agent环境支持社会智能学习 | 缺乏开放-ended多Agent环境研究社会智能问题 | 社会智能AI Agent训练环境 |
| 14 | http://arxiv.org/abs/2508.16172v2 | Graph RAG as Human Choice Model: Building a Data-Driven Mobility Agent with Preference Chain | Preference Chain集成Graph RAG增强人类行为模拟 | 数据稀缺环境下生成一致、上下文敏感行为输出问题 | 城市交通人类行为模拟 |
| 15 | http://arxiv.org/abs/2508.16508v3 | ABMax: A JAX-based Agent-based Modeling Framework | 基于JAX实现JIT编译的ABM框架，支持动态Agent操作 | 传统ABM框架难以大规模扩展和动态更新 | 复杂系统仿真研究（捕食、交通、金融） |
| 16 | http://arxiv.org/abs/2508.17322v1 | Chinese Court Simulation with LLM-Based Agent System | SimCourt复现中国法庭5阶段5角色，Agent具记忆规划反思 | 传统模拟法庭依赖专业人员，公众难以接触 | 法律专业培训与教育 |
| 17 | http://arxiv.org/abs/2508.17366v2 | Computational Multi-Agents Society Experiments: Social Modeling Framework Based on Generative Agents | CMASE将研究者嵌入为参与者，结合计算实验与民族志 | 传统仿真缺乏机制解释和因果预测能力 | 社会科学干预建模 |
| 18 | http://arxiv.org/abs/2508.17407v5 | General Social Agents | 理论指导的通用Agent，用种子游戏数据预测新游戏人类行为 | 理论应用于新场景需临时修改，预测困难 | 行为经济学与博弈论预测 |
| 19 | http://arxiv.org/abs/2508.18600v1 | Bias-Adjusted LLM Agents for Human-Like Decision-Making via Behavioral Economics | 基于行为经济学个体数据调整LLM偏差，最后通牒游戏验证 | LLM内在偏差与真实人类行为偏离，难以反映多样性 | 人类决策行为模拟 |
| 20 | http://arxiv.org/abs/2508.12920v1 | Do Large Language Model Agents Exhibit a Survival Instinct? An Empirical Study in a Sugarscape-Style Simulation | 在 Sugarscape 模拟中发现 LLM Agent 自发产生生存本能及攻击行为 | 解决自主 AI 系统 emergent 生存行为及安全对齐潜在风险问题 | AI 安全与仿真 |
| 21 | http://arxiv.org/abs/2508.13635v3 | Interpreting the Interpreter: Can We Model post-ECB Conferences Volatility with LLM Agents? | 构建 30 个异构交易员 Agent 模拟市场反应，预测利率互换波动率 | 解决货币政策沟通效果 ex-post 识别及缺乏 ex-ante 评估框架问题 | 金融市场模拟 |
| 22 | http://arxiv.org/abs/2508.14357v1 | Organ-Agents: Virtual Human Physiology Simulator via LLMs | 多 Agent 框架模拟人体生理，各 Simulator 建模特定系统时间序列数据 | 解决复杂生理系统模拟缺乏 LLM 驱动 Agent 及多系统协调问题 | 人体生理模拟 |
| 23 | http://arxiv.org/abs/2508.19163v1 | MATRIX: Multi-Agent simulaTion fRamework for safe Interactions and conteXtual clinical conversational evaluation | 整合安全分类学、BehvJudge 评估器与 PatBot 患者 Agent 的安全评估框架。 | 解决临床对话系统评估缺乏行为与风险管理洞察，难以保障安全的问题。 | 临床对话系统安全评估 |
| 24 | http://arxiv.org/abs/2509.00080v1 | Wrong Face, Wrong Move: The Social Dynamics of Emotion Misperception in Agent-Based Models | 实例化不同精度情感分类器的 Agent，研究感知精度对涌现情感与空间行为影响。 | 解决情感识别偏差或不准如何扭曲社会过程与破坏情感整合的问题。 | 基于 Agent 的社会情感模拟 |
| 25 | http://arxiv.org/abs/2508.20234v1 | Validating Generative Agent-Based Models for Logistics and Supply Chain Management Research | 评估 LLM 作为 LSCM 仿真中人类行为代理的有效性，提出双重验证框架。 | 解决 GABM 在物流供应链研究中人类行为代理有效性 unknown 的问题。 | 物流供应链生成式 Agent 仿真 |
| 26 | http://arxiv.org/abs/2508.21411v1 | CARJAN: Agent-Based Generation and Simulation of Traffic Scenarios with AJAN | 基于多 Agent 工程框架与行为树，生成模拟城市交通场景。 | 解决城市交通场景建模复杂且多类型 Agent 交互仿真困难问题。 | 自动驾驶与交通仿真 |
| 27 | http://arxiv.org/abs/2508.21740v2 | Towards Operational Validation of LLM-Agent Social Simulations: A Replicated Study of a Reddit-like Technology Forum | 构建技术社区仿真，校准参数以复现在线社区毒性动态。 | 解决社会仿真缺乏操作有效性验证且难以模拟毒性动态问题。 | 在线社区行为与 moderation 研究 |

[返回目录](#目录)
