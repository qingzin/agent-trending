# AI agents 2025年1月学术分类汇总

共收录 205 篇论文，按研究方向分类整理如下。

## 目录

- [低代码/无代码Agent平台（1篇）](#cat-01)
- [基于Agent的应用系统（40篇）](#cat-02)
- [人机协作Agent（12篇）](#cat-03)
- [Agent架构与框架设计（23篇）](#cat-04)
- [多Agent协作与通信（19篇）](#cat-05)
- [多Agent强化学习（33篇）](#cat-06)
- [Agent评测与基准（11篇）](#cat-07)
- [Agent安全与对齐（17篇）](#cat-08)
- [Agent学习与自进化（9篇）](#cat-09)
- [Agent规划与推理（7篇）](#cat-10)
- [Agent仿真与社会模拟（16篇）](#cat-11)
- [具身智能Agent（7篇）](#cat-12)
- [Agent工具使用与环境交互（6篇）](#cat-13)
- [Agent可解释性与透明度（2篇）](#cat-14)
- [Agent记忆与知识管理（2篇）](#cat-15)

<a id="cat-01"></a>

## 低代码/无代码Agent平台

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2501.00750v2 | Beyond Text: Implementing Multimodal Large Language Model-Powered Multi-Agent Systems Using a No-Code Platform | 基于No-Code平台实现多模态LLM多Agent系统，降低AI使用门槛 | 企业AI采用的技术复杂性和高成本壁垒 | 无编程经验的企业用户 |

[返回目录](#目录)

<a id="cat-02"></a>

## 基于Agent的应用系统

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2501.00826v2 | LLM-Powered Multi-Agent System for Automated Crypto Portfolio Management | 多模态多Agent框架，含团队内/团队间协作机制进行加密货币投资 | 加密货币投资中LLM知识不足和单Agent能力局限 | 加密货币投资组合管理 |
| 2 | http://arxiv.org/abs/2501.01834v3 | MoColl: Agent-Based Specific and General Model Collaboration for Image Captioning | Agent协调专用VQA模型和LLM，分解为问答子任务协作 | 专用模型缺泛化、VLM缺领域适应的矛盾 | 医学影像报告生成 |
| 3 | http://arxiv.org/abs/2501.02341v2 | UAVs Meet LLMs: Overviews and Perspectives Toward Agentic Low-Altitude Mobility | 提出LLM赋能无人机实现自主感知、记忆、推理的路线图 | 无人机缺乏复杂环境下的智能化和自主决策能力 | 无人机智能化应用 |
| 4 | http://arxiv.org/abs/2501.02368v1 | Enhancing Workplace Productivity and Well-being Using AI Agent | 结合ML与神经生物数据的多Agent系统提升工作效率 | 工作场所生产力与员工健康管理的智能化 | 企业人力资源管理 |
| 5 | http://arxiv.org/abs/2501.05468v2 | LatteReview: A Multi-Agent Framework for Systematic Review Automation Using Large Language Models | 模块化多Agent框架自动化系统综述的筛选、评分、提取 | 系统文献综述耗时耗力的流程自动化 | 学术系统文献综述 |
| 6 | http://arxiv.org/abs/2501.02727v1 | Tree-based RAG-Agent Recommendation System: A Case Study in Medical Test Data | 树结构RAG增强Agent在每个节点进行医学推理推荐 | 传统检索方法缺乏医学推理能力 | 医学检查推荐 |
| 7 | http://arxiv.org/abs/2501.05470v1 | RTLSquad: Multi-Agent Based Interpretable RTL Design | 多Agent分阶段协作生成RTL代码并提供决策可解释性 | RTL代码生成缺乏决策可解释性，工程师难以信任 | 硬件RTL代码设计 |
| 8 | http://arxiv.org/abs/2502.15700v1 | Sustainable Digitalization of Business with Multi-Agent RAG and LLM | 多Agent架构分工信息检索、增强和分类实现可持续IE | 企业数据提取资源密集且不可持续 | 企业数字化转型 |
| 9 | http://arxiv.org/abs/2501.12399v2 | FinSphere, a Real-Time Stock Analysis Agent Powered by Instruction-Tuned LLMs and Domain Tools | 结合实时数据、量化工具和指令微调LLM的股票分析Agent | 金融LLM缺乏客观评估指标和深度分析能力 | 股票分析 |
| 10 | http://arxiv.org/abs/2501.06314v1 | BioAgents: Democratizing Bioinformatics Analysis with Multi-Agent Systems | 基于小语言模型微调+RAG的多Agent系统实现本地化生物信息学分析 | 生物信息学工作流需要多学科专业知识且计算资源昂贵 | 生物信息学/基因组学分析 |
| 11 | http://arxiv.org/abs/2501.06327v1 | OpenFOAMGPT: a RAG-Augmented LLM Agent for OpenFOAM-Based Computational Fluid Dynamics | LLM Agent结合RAG管道实现CFD仿真自动配置和迭代纠错 | CFD仿真配置复杂需大量专业知识和手动调参 | 计算流体力学仿真 |
| 12 | http://arxiv.org/abs/2501.06695v1 | DVM: Towards Controllable LLM Agents in Social Deduction Games | RL与胜率约束奖励机制实现LLM Agent可控游戏能力 | 社交推理游戏中LLM Agent能力无法按需调节 | 社交推理游戏（狼人杀） |
| 13 | http://arxiv.org/abs/2501.06832v1 | A novel multi-agent dynamic portfolio optimization learning system based on hierarchical deep reinforcement learning | 辅助Agent与执行Agent协作的层次DRL框架探索高风险调整回报策略 | DRL Agent在投资组合优化中正奖励稀疏和维度灾难 | 动态投资组合优化 |
| 14 | http://arxiv.org/abs/2501.07531v1 | Evaluating Agent-based Program Repair at Google | 企业级Agent自动修复评测基准，Passerine Agent在Google环境的验证 | Agent式程序修复在企业环境的可行性和效果评估 | 企业级软件Bug修复 |
| 15 | http://arxiv.org/abs/2501.08234v2 | Dynamic Pricing in High-Speed Railways Using Multi-Agent Reinforcement Learning | 基于非零和马尔可夫博弈的MARL动态定价+RailPricing-RL仿真器 | 高铁运营商竞合场景下的动态定价策略 | 高铁动态定价 |
| 16 | http://arxiv.org/abs/2501.08243v1 | Engineering LLM Powered Multi-agent Framework for Autonomous CloudOps | MOYA多Agent框架结合RAG实现自主云运维 | 云运维中多数据源、复杂工作流的自动化管理 | 企业云运维（CloudOps） |
| 17 | http://arxiv.org/abs/2501.08523v1 | Doc-Guided Sent2Sent++: A Sent2Sent++ Agent with Doc-Guided memory for Document-level Machine Translation | 增量句级强制解码+文档引导记忆确保翻译完整性和一致性 | 文档级机器翻译中漏译和流畅性问题 | 文档级机器翻译 |
| 18 | http://arxiv.org/abs/2501.08760v2 | INTA: Intent-Based Translation for Network Configuration with LLM Agents | 以配置意图为中间表示+语法检查器引导的增量翻译框架 | 网络设备间配置翻译的自动化和准确性 | 网络配置翻译 |
| 19 | http://arxiv.org/abs/2501.09426v1 | AutoCBT: An Autonomous Multi-agent Framework for Cognitive Behavioral Therapy in Psychological Counseling | 动态路由+监督机制的自主多Agent CBT框架 | 现有LLM-CBT系统结构固定且建议空洞 | 心理咨询自动化 |
| 20 | http://arxiv.org/abs/2501.10332v1 | Agent4Edu: Generating Learner Response Data by Generative Agents for Intelligent Education Systems | LLM 生成式智能体模拟学习者，含画像、记忆、行动模块 | 离线指标与在线表现差异阻碍个性化学习 | 智能教育系统 |
| 21 | http://arxiv.org/abs/2501.11283v2 | Large Language Model Agents for Radio Map Generation and Wireless Network Planning | LLM 智能体自主生成无线电地图和网络规划 | 商业软件手动操作复杂，可扩展性差 | 无线网络规划 |
| 22 | http://arxiv.org/abs/2501.11864v1 | LLM-Agents Driven Automated Simulation Testing and Analysis of small Uncrewed Aerial Systems | 多 LLM 智能体协作支持 sUAS 仿真测试全流程 | sUAS 仿真测试手动创建执行分析繁琐 | 小型无人机系统测试 |
| 23 | http://arxiv.org/abs/2501.12216v2 | RL-RC-DoT: A Block-level RL agent for Task-Aware Video Compression | 块级 RL 智能体控制量化参数优化下游任务 | 视频编码为人类感知优化而非 AI 任务 | 自动驾驶/边缘设备 |
| 24 | http://arxiv.org/abs/2502.10406v1 | FishBargain: An LLM-Empowered Bargaining Agent for Online Fleamarket Platform Sellers | LLM 赋能讨价还价智能体，理解上下文选择行动和语言 | 个体卖家缺乏时间和商业能力完成交易 | 在线跳蚤市场平台 |
| 25 | http://arxiv.org/abs/2501.13299v2 | Hypothesis Generation for Materials Discovery and Design Using Goal-Driven and Constraint-Guided LLM Agents | 目标驱动和约束引导的 LLM 智能体生成材料发现假设 | 材料发现设计过程耗时 | 材料科学发现 |
| 26 | http://arxiv.org/abs/2501.13411v1 | VulnBot: Autonomous Penetration Testing for A Multi-Agent Collaborative Framework | 多智能体系统模拟人类渗透测试团队协作工作流 | 手动渗透测试劳动密集耗时 | 网络安全渗透测试 |
| 27 | http://arxiv.org/abs/2501.14170v1 | Argos: Agentic Time-Series Anomaly Detection with Autonomous Rule Generation via Large Language Models | 利用 LLM 自主生成可解释可复现异常规则，多智能体协作训练 | 现有系统难同时实现可解释性、可复现性和自主性 | 云基础设施监控/异常检测 |
| 28 | http://arxiv.org/abs/2501.14179v2 | AI Chatbots as Professional Service Agents: Developing a Professional Identity | 提出 LAPI 框架，理论指导任务规划及语用熵方法生成专业响应 | 聊天机器人缺乏与专业身份一致的沟通方式 | 医疗问答/专业服务代理 |
| 29 | http://arxiv.org/abs/2501.14700v4 | An Attentive Graph Agent for Topology-Adaptive Cyber Defence | 定制 CybORG 环境编码网络状态为有向图，采用图注意力网络架构 | 现有自主防御代理忽略计算机网络固有图结构，适应性受限 | 网络安全防御/自适应系统 |
| 30 | http://arxiv.org/abs/2504.13183v1 | Factors That Influence the Adoption of AI-enabled Conversational Agents (AICAs) as an Augmenting Therapeutic Tool by Frontline Healthcare Workers: From Technology Acceptance Model 3 (TAM3) Lens -- A Systematic Mapping Review | 系统文献综述，探索心理健康从业者对 AI 对话代理态度及采用因素 | 需调查 AI 对话代理在心理健康领域可行性及从业者观点 | 心理健康/对话代理采用 |
| 31 | http://arxiv.org/abs/2501.15749v1 | LLM-powered Multi-agent Framework for Goal-oriented Learning in Intelligent Tutoring System | 提出 GenMentor，利用微调 LLM 映射目标到技能，调度高效学习路径 | 现有 ITS 难提供目标导向学习体验，强调高效达成特定目标 | 智能辅导系统/个性化学习 |
| 32 | http://arxiv.org/abs/2501.15826v1 | MADP: Multi-Agent Deductive Planning for Enhanced Cognitive-Behavioral Mental Health Question Answer | 提出 MADP 框架，基于 CBT 心理元素交互引导 LLM 深入理解求助者 | 现有 MHQA 工作聚焦单智能体，忽略 CBT 元素间交互 | 心理健康问答/认知行为疗法 |
| 33 | http://arxiv.org/abs/2501.17206v1 | Integrating Reinforcement Learning and AI Agents for Adaptive Robotic Interaction and Assistance in Dementia Care | 集成社会辅助机器人、RL、LLM 及临床专业知识于模拟环境 | 痴呆症社会辅助机器人实验数据有限，需动态模拟环境 | 痴呆症护理/辅助技术 |
| 34 | http://arxiv.org/abs/2502.18465v1 | Empirical Research on Utilizing LLM-based Agents for Automated Bug Fixing via LangGraph | 整合 LangGraph 等组件实现自动化代码生成与调试四步工作流 | 解决软件开发中代码准确性、效率及可扩展性挑战 | 自动化 bug 修复 |
| 35 | http://arxiv.org/abs/2501.18160v3 | RepoAudit: An Autonomous LLM-Agent for Repository-Level Code Auditing | 开发自主 LLM 代理 RepoAudit，利用内存探索代码库审计 | 解决 LLM 审计代码库上下文受限及幻觉导致效率低问题 | 仓库级代码审计 |
| 36 | http://arxiv.org/abs/2501.18320v1 | Leveraging LLM Agents for Automated Optimization Modeling for SASP Problems: A Graph-RAG based Approach | 提出基于 Graph-RAG 的多代理结构，自动化 SASP 优化建模 | 解决提示工程缺乏领域知识导致传感器信号处理建模差问题 | 优化建模自动化 |
| 37 | http://arxiv.org/abs/2502.05199v1 | Advancing Geometry with AI: Multi-agent Generation of Polytopes | 利用 AI 系统生成复杂多胞形，突破人类构造极限 | 解决几何中极值结构构造困难及耗时问题 | 数学几何对象生成 |
| 38 | http://arxiv.org/abs/2501.19056v1 | Enabling Autonomic Microservice Management through Self-Learning Agents | 提出 ServiceOdyssey 自学习代理系统，自主管理微服务 | 解决 LLM 适应特定服务上下文及依赖静态文档问题 | 自主微服务管理 |
| 39 | http://arxiv.org/abs/2501.19204v1 | Autonomous Legacy Web Application Upgrades Using a Multi-Agent System | 提出基于 LLM 的多代理系统，自主升级遗留 Web 应用 | 解决遗留应用升级复杂成本高及 LLM 上下文保持问题 | 遗留 Web 应用升级 |
| 40 | http://arxiv.org/abs/2501.19206v1 | An Empirical Game-Theoretic Analysis of Autonomous Cyber-Defence Agents | 利用实证博弈论分析自主网络防御代理，评估 DRL 方法 | 解决自主网络防御代理泛化策略及保证挑战 | 自主网络防御代理 |

[返回目录](#目录)

<a id="cat-03"></a>

## 人机协作Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2501.00867v1 | Interactionalism: Re-Designing Higher Learning for the Large Language Agent Era | 提出交互主义原则，定义与LLM Agent协作的交互智能技能集 | GenAI时代学习设计缺乏与Agent协作的系统方法 | 高等教育学习设计 |
| 2 | http://arxiv.org/abs/2502.00005v1 | A Study about Distribution and Acceptance of Conversational Agents for Mental Health in Germany | 调研对话Agent在心理健康领域的使用分布和接受度 | 心理健康AI对话Agent的用户接受度与风险评估 | 心理健康领域对话Agent |
| 3 | http://arxiv.org/abs/2501.04227v2 | Agent Laboratory: Using LLM Agents as Research Assistants | 自主LLM Agent完成文献综述、实验、报告的全流程研究 | 科学研究耗时耗资，研究流程自动化 | 科学研究辅助 |
| 4 | http://arxiv.org/abs/2501.06607v1 | AI Drawing Partner: Co-Creative Drawing Agent and Research Platform to Model Co-Creation | 共创绘画Agent结合CCSM框架量化建模交互动态 | 共创AI系统缺乏量化协作过程的方法 | 人机共创绘画 |
| 5 | http://arxiv.org/abs/2501.16341v1 | Developing Enhanced Conversational Agents for Social Virtual Worlds | 统计建模对话行为+情感检测+用户画像的虚拟世界对话Agent | 社交虚拟世界中对话Agent的多模态交互和适应性 | 社交虚拟世界（Second Life） |
| 6 | http://arxiv.org/abs/2501.08393v1 | Empathetic Conversational Agents: Utilizing Neural and Physiological Signals for Enhanced Empathetic Interactions | 集成神经/生理信号实时情感检测实现共情数字人交互 | 对话Agent缺乏基于实时生理信号的共情能力 | 共情数字人交互 |
| 7 | http://arxiv.org/abs/2501.09355v1 | YETI (YET to Intervene) Proactive Interventions by Multimodal AI Agents in Augmented Reality Tasks | 基于SSIM和对齐信号的主动干预时机识别机制 | 现有AI Agent被动响应，无法主动检测纠正用户错误 | AR辅助任务（如烹饪）主动干预 |
| 8 | http://arxiv.org/abs/2501.10553v1 | Observe, Ask, Intervene: Designing AI Agents for More Inclusive Meetings | 提出"观察 - 询问 - 干预"(OAI) 框架，AI 作为虚拟联合主持人 | 视频会议中包容性不足，依赖主持人实践 | 视频会议/团队协作 |
| 9 | http://arxiv.org/abs/2502.00023v1 | Musical Agent Systems: MACAT and MACataRT | MACAT 智能体主导表演，MACataRT 支持协作即兴创作 | 音乐表演中人机协作创意空间有限 | 音乐表演/即兴创作 |
| 10 | http://arxiv.org/abs/2501.16609v4 | CowPilot: A Framework for Autonomous and Human-Agent Collaborative Web Navigation | 提出 CowPilot 支持自主及人机协作网页导航，用户可暂停拒绝或接管 | 智能体复杂任务现实语境及建模用户偏好常不足，需人机协作 | 网页导航/人机协作 |
| 11 | http://arxiv.org/abs/2501.17258v1 | Controlling AI Agent Participation in Group Conversations: A Human-Centered Approach | 提出组对话中 AI 代理参与控制的分类法，支持用户干预行为 | 解决 AI 在群组中主导对话引发用户不满的问题 | 群组头脑风暴场景 |
| 12 | http://arxiv.org/abs/2501.18002v1 | Agentic Workflows for Conversational Human-AI Interaction Design | 探索代理工作流辅助用户明确目标及设计测试，解决交互短暂问题 | 解决用户目标模糊及人机交互短暂限制持续 engagement 问题 | 对话式人机交互设计 |

[返回目录](#目录)

<a id="cat-04"></a>

## Agent架构与框架设计

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2501.00881v1 | Agentic Systems: A Guide to Transforming Industries with Vertical AI Agents | 提出垂直AI Agent标准化设计模式和认知技能模块 | 垂直行业Agent系统缺乏一致性和标准化设计 | 跨行业垂直AI Agent设计 |
| 2 | http://arxiv.org/abs/2501.01849v2 | A Multi-Agent Conversational Bandit Approach to Online Evaluation and Selection of User-Aligned LLM Responses | 多Agent对话Bandit模型，含本地淘汰和云端自适应策略 | LLM响应在线评估的高维特征和多设备适应问题 | LLM响应选择与用户偏好对齐 |
| 3 | http://arxiv.org/abs/2501.03265v2 | Cognitive Edge Computing: A Comprehensive Survey on Optimizing Large Models and AI Agents for Pervasive Deployment | 统一认知保持框架涵盖模型优化、系统架构和自适应智能 | 资源受限边缘设备上部署LLM和AI Agent的挑战 | 边缘计算设备部署AI Agent |
| 4 | http://arxiv.org/abs/2501.04136v1 | Implementing Systemic Thinking for Automatic Schema Matching: An Agent-Based Modeling Approach | 将自动模式匹配建模为复杂自适应系统的Agent仿真 | 模式匹配的复杂性和不确定性挑战 | 数据库模式匹配 |
| 5 | http://arxiv.org/abs/2501.04575v1 | InfiGUIAgent: A Multimodal Generalist GUI Agent with Native Reasoning and Reflection | 两阶段微调管道赋予GUI Agent原生层级推理和反思能力 | GUI Agent多步推理不足和依赖文本标注 | 计算设备GUI自动化 |
| 6 | http://arxiv.org/abs/2501.06781v2 | Eliza: A Web3 friendly AI Agent Operating System | 首个开源Web3友好的Agent框架，无缝集成区块链交互 | AI Agent与Web3应用间缺乏无缝集成框架 | Web3/区块链AI Agent |
| 7 | http://arxiv.org/abs/2501.07054v1 | PoAct: Policy and Action Dual-Control Agent for Generalized Applications | 动态切换推理策略和修改动作空间的双控Agent | Code Action复杂动作空间与推理路径的精确组织 | 法律及通用场景复杂推理 |
| 8 | http://arxiv.org/abs/2501.07815v1 | Agent-Centric Projection of Prompting Techniques and Implications for Synthetic Training Data for Large Language Models | 线性/非线性上下文框架揭示提示技术与多Agent系统的深层联系 | 缺乏提示技术与多Agent系统关系的统一分析框架 | LLM提示工程与多Agent设计 |
| 9 | http://arxiv.org/abs/2501.07834v2 | Flow: Modularized Agentic Workflow Automation | AOV图定义工作流，支持动态子任务分配调整和模块化并行执行 | 多Agent工作流执行中缺乏有效动态调整机制 | 多Agent工作流自动化 |
| 10 | http://arxiv.org/abs/2501.08262v1 | Addressing the sustainable AI trilemma: a case study on LLM agents and RAG | 提出可持续AI三难困境概念，量化Agent记忆模块能耗权衡 | LLM Agent推理能耗高，记忆增强框架能效低 | AI Agent可持续性设计 |
| 11 | http://arxiv.org/abs/2501.09136v3 | Agentic Retrieval-Augmented Generation: A Survey on Agentic RAG | 系统综述Agentic RAG架构分类、设计模式和应用 | 传统RAG缺乏自适应多步推理和动态检索能力 | Agentic RAG系统研究 |
| 12 | http://arxiv.org/abs/2501.09316v1 | SOP-Agent: Empower General Purpose AI Agent with Domain-Specific SOPs | 伪代码式SOP表示为决策图引导Agent执行领域任务 | 通用Agent在长期规划和领域知识利用方面的局限 | 跨领域决策/客服/代码生成 |
| 13 | http://arxiv.org/abs/2501.10114v3 | Infrastructure for AI Agents | 提出智能体基础设施概念，定义归因、交互塑造、有害行为检测三大功能 | 异构智能体间交互缺乏外部协议和系统 | 多智能体生态系统 |
| 14 | http://arxiv.org/abs/2501.17167v2 | QualityFlow: An Agentic Workflow for Program Synthesis Controlled by LLM Quality Checks | LLM 质量检查器动态控制工作流，想象程序执行是否符合测试 | 程序合成中工作流偏离和错误合成测试 | 程序合成任务 |
| 15 | http://arxiv.org/abs/2502.17443v1 | AI Agentic workflows and Enterprise APIs: Adapting API architectures for the age of AI agents | 企业 API 架构适应 AI 智能体动态目标导向行为 | 现有 API 架构为人类驱动设计，不支持智能体 | 企业计算架构 |
| 16 | http://arxiv.org/abs/2501.13333v1 | AgentRec: Agent Recommendation Using Sentence Embeddings Aligned to Human Feedback | 扩展 SBERT 编码器推荐 LLM 智能体，RLHF 对齐人类价值观 | 多智能体系统需决定哪个智能体最适合任务 | 智能体任务分配 |
| 17 | http://arxiv.org/abs/2503.15504v1 | GRETA: Modular Platform to Create Adaptive Socially Interactive Agents | 描述 GRETA 平台架构，处理外部特征并增量处理对话 | 社会交互代理需适应交互伙伴状态及多模态元素 | 社会交互代理/人机交互 |
| 18 | http://arxiv.org/abs/2501.14082v2 | Communicating Activations Between Language Model Agents | 提出语言模型通过激活值通信，暂停计算结合中间层激活 | 自然语言通信成本高且抽象掉丰富内部信息 | 多语言模型协作/推理 |
| 19 | http://arxiv.org/abs/2501.14224v1 | Top Ten Challenges Towards Agentic Neural Graph Databases | 引入代理神经图数据库，扩展自主查询构建、执行及持续学习功能 | 神经图数据库依赖预定义查询，缺乏自主性和适应性 | 数据管理/图数据库 |
| 20 | http://arxiv.org/abs/2501.15346v1 | Between Puppet and Actor: Reframing Authorship in this Age of AI Agents | 提出理解 AI 代理介于无机傀儡与表演演员之间的动态状态 | 创意过程中 AI 代理角色存在概念张力，作者定义需演变 | AI 版权/创意过程 |
| 21 | http://arxiv.org/abs/2501.15355v1 | Large Language Models as Theory of Mind Aware Generative Agents with Counterfactual Reflection | 提出 ToM-agent 范式，解耦信心与心理状态，动态调整推断 BDI | LLM 需模拟开放域对话交互中的心理理论能力 | 生成式智能体/社会行为模拟 |
| 22 | http://arxiv.org/abs/2501.16150v2 | A Comprehensive Survey of Agents for Computer Use: Foundations, Challenges, and Future Directions | 调查 ACU 现状，提出涵盖领域、交互及智能体视角的统一分类法 | ACU 尚未成熟日常使用，需识别研究差距及未来方向 | 计算机使用智能体/综述 |
| 23 | http://arxiv.org/abs/2501.17903v2 | Free Agent in Agent-Based Mixture-of-Experts Generative AI Framework | 引入基于奖励的自由代理机制，实时替换低性能代理 | 解决多智能体系统中下性能代理无法实时替换的问题 | 生成式 AI 多代理框架 |

[返回目录](#目录)

<a id="cat-05"></a>

## 多Agent协作与通信

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2501.00906v2 | Large Language Model Based Multi-Agent System Augmented Complex Event Processing Pipeline for Internet of Multimedia Things | 集成LLM多Agent与pub/sub工具构建自主CEP管道 | LLM与现有复杂事件处理系统的集成问题 | 物联网多媒体视频查询处理 |
| 2 | http://arxiv.org/abs/2501.01205v1 | Harnessing Multi-Agent LLMs for Complex Engineering Problem-Solving: A Framework for Senior Design Projects | 多LLM Agent代表不同专家视角，协作模拟工程团队 | 工程高年级设计项目中多学科协作问题求解 | 工程教育毕业设计项目 |
| 3 | http://arxiv.org/abs/2501.02174v1 | TACTIC: Task-Agnostic Contrastive pre-Training for Inter-Agent Communication | 任务无关的对比预训练通信机制，跨视野范围泛化 | MARL中通信方法难以泛化到不同视野范围 | 多Agent协作任务（SMACv2） |
| 4 | http://arxiv.org/abs/2501.02888v2 | Revisiting Communication Efficiency in Multi-Agent Reinforcement Learning from the Dimensional Analysis Perspective | 维度分析视角消除消息维度冗余和混淆因子 | MARL通信中接收端维度冗余导致决策质量下降 | 多Agent强化学习通信 |
| 5 | http://arxiv.org/abs/2501.06243v1 | Agent TCP/IP: An Agent-to-Agent Transaction System | Agent间基于区块链的无信任IP交易协议，赋予法律人格 | Agent间缺乏标准化交互和IP交易协议 | Agent间自主交易与知识经济 |
| 6 | http://arxiv.org/abs/2501.05207v1 | CoDe: Communication Delay-Tolerant Multi-Agent Collaboration via Dual Alignment of Intent and Timeliness | 意图-时效双对齐机制应对异步通信延迟 | 通信延迟导致多Agent认知偏差和协作失效 | 多Agent协作通信 |
| 7 | http://arxiv.org/abs/2501.06322v1 | Multi-Agent Collaboration Mechanisms: A Survey of LLMs | 提出可扩展的MAS协作机制分类框架，涵盖多维度分析 | LLM多Agent系统协作机制缺乏系统性综述和分类 | LLM多Agent系统研究 |
| 8 | http://arxiv.org/abs/2501.06625v1 | Guided Code Generation with LLMs: A Multi-Agent Framework for Complex Code Tasks | 多Agent框架通过细粒度结构化引导代码生成 | LLM在复杂长上下文代码生成中的组合推理不足 | 软件开发代码生成 |
| 9 | http://arxiv.org/abs/2501.07811v1 | CodeCoR: An LLM-Based Self-Reflective Multi-Agent Framework for Code Generation | 自反思多Agent框架评估各Agent有效性并剪枝低质量输出 | 多Agent代码生成工作流中单Agent失败导致整体鲁棒性差 | 代码生成 |
| 10 | http://arxiv.org/abs/2501.12263v3 | mmCooper: A Multi-agent Multi-stage Communication-efficient and Collaboration-robust Cooperative Perception Framework | 多阶段协作策略动态平衡中间/后期信息共享 | 带宽限制和校准误差影响协作感知 | 车辆协作感知 |
| 11 | http://arxiv.org/abs/2501.12909v1 | FilmAgent: A Multi-Agent Framework for End-to-End Film Automation in Virtual 3D Spaces | 模拟导演/编剧/演员/摄影师角色，迭代反馈减少幻觉 | 虚拟电影制作决策过程复杂 | 虚拟 3D 空间电影制作 |
| 12 | http://arxiv.org/abs/2501.13189v1 | Map Prediction and Generative Entropy for Multi-Agent Exploration | 地图预测器填充未知空间，生成熵优先高不确定性区域 | 传统方法依赖显式历史观测集 | 多智能体探索任务 |
| 13 | http://arxiv.org/abs/2501.13461v2 | Knowledge-Informed Multi-Agent Trajectory Prediction at Signalized Intersections for Infrastructure-to-Everything | 提出 I2X 协作预测方案，利用路侧单元预测并传输轨迹 | 单车感知局限，交叉口场景复杂性高 | 智能交通/自动驾驶系统 |
| 14 | http://arxiv.org/abs/2501.14189v1 | Distributed Multi-Agent Coordination Using Multi-Modal Foundation Models | 利用多模态基础模型自动生成约束，提出神经符号到全神经智能体谱系 | 分布式约束优化问题依赖劳动密集型手动构建 | 多智能体协调/视觉语言任务 |
| 15 | http://arxiv.org/abs/2501.14568v2 | Hybrid Quantum-Classical Multi-Agent Pathfinding | 提出首个最优混合量子经典 MAPF 算法，基于分支切割定价 | 处理大量智能体时计算挑战大，量子硬件尚处初期 | 多智能体路径规划/量子计算 |
| 16 | http://arxiv.org/abs/2501.15791v5 | Harnessing Diverse Perspectives: A Multi-Agent Framework for Enhanced Error Detection in Knowledge Graphs | 提出 MAKGED，利用四个专用智能体多轮讨论利用细粒度子图信息 | 现有错误检测方法未有效利用子图信息且缺乏决策透明度 | 知识图谱错误检测 |
| 17 | http://arxiv.org/abs/2501.16254v1 | Multi-Agent Geospatial Copilots for Remote Sensing Workflows | 提出 GeoLLM-Squad，将智能体编排与地理空间任务求解分离 | 单智能体系统难随 RS 任务复杂度扩展，需模块化集成 | 遥感工作流/地理空间分析 |
| 18 | http://arxiv.org/abs/2501.16803v3 | RG-Attn: Radian Glue Attention for Multi-modality Multi-agent Cooperative Perception | 提出 RG-Attn 轻量通用跨模态融合模块，统一智能体内及间融合 | 现有方法依赖单模态数据共享，异构传感器设置融合性能受限 | 自动驾驶/协作感知 |
| 19 | http://arxiv.org/abs/2501.17661v1 | Multi-Agent Path Finding Using Conflict-Based Search and Structural-Semantic Topometric Maps | 利用结构语义拓扑地图加速冲突基搜索，优化多机器人路径规划 | 解决传统 CBS 计算密集且难以适用于现实环境的问题 | 多机器人路径寻找 |

[返回目录](#目录)

<a id="cat-06"></a>

## 多Agent强化学习

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2501.01136v2 | Symmetries-enhanced Multi-Agent Reinforcement Learning | 嵌入外在对称性的框架和群等变Graphormer架构 | MARL中固有对称性不足导致的泛化和可扩展性问题 | 无人机集群分布式任务 |
| 2 | http://arxiv.org/abs/2501.01140v1 | Communicating Unexpectedness for Out-of-Distribution Multi-Agent Reinforcement Learning | Agent间通信"意外性"信息以适应分布外环境变化 | 多Agent RL在分布外场景下的快速适应问题 | 多机器人仓库环境 |
| 3 | http://arxiv.org/abs/2501.01266v1 | PIMAEX: Multi-Agent Exploration through Peer Incentivization | 同伴激励奖励函数结合通信通道促进多Agent探索 | 多Agent RL中探索不足问题 | 部分可观测多Agent环境 |
| 4 | http://arxiv.org/abs/2501.03187v1 | Turn-based Multi-Agent Reinforcement Learning Model Checking | 紧密集成TMARL与模型检验验证Agent合规性 | 现有验证方法无法处理回合制MARL Agent的合规性 | 多人随机博弈验证 |
| 5 | http://arxiv.org/abs/2501.05113v1 | Constrained Optimization of Charged Particle Tracking with Multi-Agent Reinforcement Learning | 带约束安全层的多Agent RL用于粒子径迹重建 | 粒子探测器中径迹重建的多维分配优化问题 | 粒子物理探测器 |
| 6 | http://arxiv.org/abs/2501.06554v1 | Hierarchical Reinforcement Learning for Optimal Agent Grouping in Cooperative Systems | 层次RL框架同时学习最优分组和Agent策略 | 协作多Agent系统中Agent分组/配对的优化问题 | 协作多Agent系统 |
| 7 | http://arxiv.org/abs/2501.08020v1 | Cooperative Patrol Routing: Optimizing Urban Crime Surveillance through Multi-Agent Reinforcement Learning | 基于Dec-POMDP的MARL模型+新覆盖指标优化巡逻路线 | 城市巡逻路线协同规划以最大化犯罪热点覆盖 | 城市警察巡逻路线优化 |
| 8 | http://arxiv.org/abs/2501.08778v1 | Networked Agents in the Dark: Team Value Learning under Partial Observability | 部分可观测下通过本地通信共识机制逼近团队价值函数 | 网络化Agent在部分可观测和隐私约束下的协作学习 | 网络化多Agent协作 |
| 9 | http://arxiv.org/abs/2501.10116v1 | GAWM: Global-Aware World Model for Multi-Agent Reinforcement Learning | 引入 Transformer 融合多智能体局部观测，增强全局状态表示 | 部分可观测环境下世界模型全局表示不足 | 复杂多智能体环境 (SMAC) |
| 10 | http://arxiv.org/abs/2501.10924v1 | Adaptive Target Localization under Uncertainty using Multi-Agent Deep Reinforcement Learning with Knowledge Transfer | MADRL 结合迁移学习，团队奖励函数产生合作智能体 | 目标定位中实践不确定性 (误报、不可达) | 放射性目标定位 |
| 11 | http://arxiv.org/abs/2501.10938v1 | Blockchain-assisted Demonstration Cloning for Multi-Agent Deep Reinforcement Learning | 区块链辅助多专家示范克隆，模型共享框架 | 样本效率、维度灾难、环境探索问题 | 合作/竞争 MDRL 环境 |
| 12 | http://arxiv.org/abs/2501.11818v2 | Group-Agent Reinforcement Learning with Heterogeneous Agents | 异质智能体组学习机制，异步共享知识 | 单智能体学习速度慢，性能有限 | Atari 游戏学习 |
| 13 | http://arxiv.org/abs/2501.12061v1 | Tackling Uncertainties in Multi-Agent Reinforcement Learning through Integration of Agent Termination Dynamics | 分布学习结合安全焦点损失函数，屏障函数降低风险 | MARL 中随机性和不确定性影响策略学习 | StarCraft II 微管理 |
| 14 | http://arxiv.org/abs/2501.12991v1 | An Offline Multi-Agent Reinforcement Learning Framework for Radio Resource Management | 离线 MARL 框架优化多 AP 调度策略 | 在线 MARL 安全问题、数据收集成本高 | 无线资源管理 |
| 15 | http://arxiv.org/abs/2501.13200v1 | SRMT: Shared Recurrent Memory Transformer for Multi-agent Lifelong Pathfinding | 共享循环记忆 Transformer，全局广播个体工作记忆 | MARL 需显式预测智能体行为实现合作 | 多智能体路径寻找 |
| 16 | http://arxiv.org/abs/2501.13994v1 | CSAOT: Cooperative Multi-Agent System for Active Object Tracking | 利用多智能体深度强化学习和混合专家框架，单设备多智能体协作 | 动态复杂场景下单智能体跟踪信息获取有限 | 主动物体跟踪/机器人导航 |
| 17 | http://arxiv.org/abs/2501.13592v1 | WFCRL: A Multi-Agent Reinforcement Learning Benchmark for Wind Farm Control | 首个风电场控制多智能体强化学习开放环境套件 | 传统模型控制策略需可处理模型且受维数灾难限制 | 风电场控制/能源管理 |
| 18 | http://arxiv.org/abs/2501.13727v2 | Scalable Safe Multi-Agent Reinforcement Learning for Multi-Agent System | 设计多层消息传递网络聚合局部观测，约束联合策略优化 | 现有 MARL 算法安全性不足且可扩展性有限 | 大规模多智能体系统 |
| 19 | http://arxiv.org/abs/2501.14111v1 | Collaborating in a competitive world: Heterogeneous Multi-Agent Decision Making in Symbiotic Supply Chain Environments | 比较同质与异构智能体结构，开发无需共享利润的奖励共享方法 | 供应链网络中平衡支持其他节点与利润的挑战 | 供应链环境/决策优化 |
| 20 | http://arxiv.org/abs/2501.14225v2 | Multi-agent KTO: Reinforcing Strategic Interactions of Large Language Model in Language Game | 提出 MaKTO，利用上下文交互而非传统多阶段框架学习语言博弈 | 智能体需战略决策及灵活有意义沟通，传统框架分离决策与表达 | 语言博弈/战略交互 |
| 21 | http://arxiv.org/abs/2501.14451v1 | MARL-OT: Multi-Agent Reinforcement Learning Guided Online Fuzzing to Detect Safety Violation in Autonomous Driving Systems | 利用 MARL 高层指导触发危险场景，规则在线模糊测试探索违规 | 离线方法难快速生成违规，单智能体 RL 难捕捉多车复杂角落案例 | 自动驾驶系统安全测试 |
| 22 | http://arxiv.org/abs/2501.15228v2 | Improving Retrieval-Augmented Generation through Multi-Agent Reinforcement Learning | 提出 MMOA-RAG，将 RAG 管道多组件视为多智能体协作任务联合优化 | RAG 组件通常单独优化，导致目标不一致及模块间依赖复杂 | 检索增强生成/问答任务 |
| 23 | http://arxiv.org/abs/2501.15495v1 | Expert-Free Online Transfer Learning in Multi-Agent Reinforcement Learning | 引入迁移学习利用外部知识增强学习过程，简化探索降低收敛时间 | 深度 RL 需大量数据，任务稍变即失效，学习时间长 | 多智能体强化学习/迁移学习 |
| 24 | http://arxiv.org/abs/2501.15695v1 | Contextual Knowledge Sharing in Multi-Agent Reinforcement Learning with Decentralized Communication and Coordination | 集成点对点通信和协调，将目标意识和时间意识纳入知识共享 | 现有 Dec-MARL 策略优先考虑通信或协调，缺乏集成方法 | 去中心化多智能体强化学习 |
| 25 | http://arxiv.org/abs/2501.16098v1 | Multi-Agent Meta-Offline Reinforcement Learning for Timely UAV Path Planning and Data Collection | 提出元离线 MARL 算法结合 CQL 和 MAML，支持离线训练及适应动态配置 | 传统 MARL 在线不安全且不实用，环境特定需重新训练 | 无人机路径规划/数据收集 |
| 26 | http://arxiv.org/abs/2501.16847v1 | Optimization and Learning in Open Multi-Agent Systems | 引入新分布式算法解决开放网络优化学习问题，基于开放算子理论 | 开放网络中参与智能体数量因自主决策等因素变化，需评估性能 | 开放多智能体系统/分布式算法 |
| 27 | http://arxiv.org/abs/2501.16966v1 | Heterogeneity-aware Personalized Federated Learning via Adaptive Dual-Agent Reinforcement Learning | 提出 HAPFL，利用多级 RL 机制优化异构个性化联邦学习过程 | 客户端模型架构及计算能力固有异构性导致精度损失及掉队问题 | 联邦学习/物联网环境 |
| 28 | http://arxiv.org/abs/2501.17384v2 | A Dual-Agent Adversarial Framework for Robust Generalization in Deep Reinforcement Learning | 提出双智能体对抗框架，通过相互扰动学习不变语义特征 | 解决 RL 模型泛化能力差，易过拟合背景变化问题 | 深度强化学习泛化 |
| 29 | http://arxiv.org/abs/2501.18138v3 | B3C: A Minimalist Approach to Offline Multi-Agent Reinforcement Learning | 提出行为克隆正则化与评论剪枝方法，优化离线多智能体 RL | 解决离线多智能体 RL 中过估计及正则化失衡问题 | 离线多智能体强化学习 |
| 30 | http://arxiv.org/abs/2501.18944v1 | O-MAPL: Offline Multi-agent Preference Learning | 提出端到端偏好学习框架，利用价值分解优化合作 MARL | 解决多智能体 RL 中奖励函数推断及训练不稳定问题 | 离线多智能体偏好学习 |
| 31 | http://arxiv.org/abs/2501.19144v2 | Prediction-Aware Learning in Multi-Agent Systems | 提出预测感知框架，代理预测未来收益调整策略 | 解决时变游戏中预测未来收益未纳入学习框架问题 | 多智能体系统预测学习 |
| 32 | http://arxiv.org/abs/2501.19239v1 | Multi-agent Multi-armed Bandit with Fully Heavy-tailed Dynamics | 研究完全重尾动态下的去中心化多代理多臂老虎机 | 解决重尾图通信及奖励分布下方差无限挑战 | 多代理多臂老虎机 |
| 33 | http://arxiv.org/abs/2501.19388v3 | Online Decision-Making in Tree-Like Multi-Agent Games with Transfers | 研究树状多代理游戏中允许转移的在线决策，实现无遗憾 | 解决自利非合作玩家间难以达成全局最优问题 | 多代理游戏决策 |

[返回目录](#目录)

<a id="cat-07"></a>

## Agent评测与基准

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2501.01149v3 | A3: Android Agent Arena for Mobile GUI Agents with Essential-State Procedural Evaluation | 基于"关键状态"的过程式评估方法，用MLLM作为奖励模型 | 移动GUI Agent在动态在线应用中缺乏有效评测方法 | 移动端GUI Agent评测 |
| 2 | http://arxiv.org/abs/2501.01594v1 | PSYCHE: A Multi-faceted Patient Simulation Framework for Evaluation of Psychiatric Assessment Conversational Agents | 基于多维精神病学构建体的患者模拟评估框架 | 精神科评估对话Agent缺乏标准化评测方法 | 精神科评估对话Agent |
| 3 | http://arxiv.org/abs/2501.01892v2 | QuArch: A Question-Answering Dataset for AI Agents in Computer Architecture | 1500条人工验证的计算机体系结构QA数据集 | AI Agent在计算机体系结构领域的能力评估缺乏数据集 | 计算机体系结构AI Agent |
| 4 | http://arxiv.org/abs/2501.04180v2 | HIVEX: A High-Impact Environment Suite for Multi-Agent Research (extended version) | 面向生态挑战的五个多Agent基准环境套件 | 现有多Agent环境过于简化，脱离现实问题 | 多Agent研究基准评测 |
| 5 | http://arxiv.org/abs/2501.06706v1 | AIOpsLab: A Holistic Framework to Evaluate AI Agents for Enabling Autonomous Clouds | 集成部署、故障注入、遥测和评估的一体化Agent评测框架 | 缺乏评估AIOps Agent端到端能力的综合框架 | 云运维自动化 |
| 6 | http://arxiv.org/abs/2501.09993v3 | Agent-as-Judge for Factual Summarization of Long Narratives | Agent-as-Judge框架利用角色知识图谱评估摘要事实一致性 | 长叙事摘要的事实准确性评估不足 | 长文本摘要事实性评估 |
| 7 | http://arxiv.org/abs/2501.10593v1 | ColorGrid: A Multi-Agent Non-Stationary Environment for Goal Inference and Assistance | 创建具有可定制非平稳性、不对称性的 MARL 环境 ColorGrid | 现有 MARL 环境缺乏评估智能体目标推断能力的属性 | MARL 算法基准测试 |
| 8 | http://arxiv.org/abs/2501.11067v1 | IntellAgent: A Multi-Agent Framework for Evaluating Conversational AI Systems | 策略驱动图建模、事件生成、用户 - 智能体仿真自动化创建基准 | 传统方法无法捕捉真实交互复杂性 | 对话式 AI 系统评估 |
| 9 | http://arxiv.org/abs/2501.11858v2 | EmbodiedEval: Evaluate Multimodal LLMs as Embodied Agents | 328 个任务/125 个 3D 场景的综合交互式评估基准 | 现有基准限于静态图像，无法评估具身能力 | 多模态 LLM 具身任务评估 |
| 10 | http://arxiv.org/abs/2501.14654v2 | MedAgentBench: A Realistic Virtual EHR Environment to Benchmark Medical LLM Agents | 引入 MedAgentBench，包含临床任务、患者档案及 FHIR 合规交互环境 | 缺乏标准化数据集基准测试医疗应用中 LLM 智能体能力 | 医疗 LLM 智能体评估 |
| 11 | http://arxiv.org/abs/2501.18411v2 | Gravity-Bench-v1: A Benchmark on Gravitational Physics Discovery for Agents | 提出 Gravity-Bench 基准，评估代理在动态环境中发现物理规律 | 解决缺乏评估 AI 科学发现能力及泛化性的基准问题 | 物理发现代理评测 |

[返回目录](#目录)

<a id="cat-08"></a>

## Agent安全与对齐

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2501.01593v2 | BLAST: A Stealthy Backdoor Leverage Attack against Cooperative Multi-Agent Deep Reinforcement Learning based Systems | 仅在单个Agent植入后门即可撬动整个多Agent系统 | 协作MADRL系统后门攻击的隐蔽性和实用性 | 协作多Agent深度RL系统安全 |
| 2 | http://arxiv.org/abs/2501.02450v1 | GCP: Guarded Collaborative Perception with Spatial-Temporal Aware Malicious Agent Detection | 时空感知恶意Agent检测，揭示盲区混淆攻击 | 协作感知中恶意Agent的隐蔽攻击检测问题 | 自动驾驶协作感知 |
| 3 | http://arxiv.org/abs/2501.05360v1 | On Corrigibility and Alignment in Multi Agent Games | 多Agent博弈中的可纠正性建模为贝叶斯博弈框架 | 多Agent系统中Agent可纠正性的理论建模不足 | 多Agent系统安全与对齐 |
| 4 | http://arxiv.org/abs/2501.05501v2 | Strategy Masking: A Method for Guardrails in Value-based Reinforcement Learning Agents | 策略掩码方法显式学习并抑制不良Agent行为（如欺骗） | RL Agent通过奖励函数学习到不良或不道德行为 | 基于价值的RL Agent安全护栏 |
| 5 | http://arxiv.org/abs/2501.07913v2 | Governing AI Agents | 用委托代理理论和代理法分析AI Agent治理挑战和解决方案 | AI Agent的授权、问责和访问控制的治理问题 | AI Agent监管与法律治理 |
| 6 | http://arxiv.org/abs/2501.09674v1 | Authenticated Delegation and Authorized AI Agents | 扩展OAuth 2.0/OIDC的Agent授权框架+自然语言权限转换 | AI Agent缺乏认证授权和可审计的权限委托机制 | AI Agent安全授权与身份管理 |
| 7 | http://arxiv.org/abs/2501.13946v1 | Hallucination Mitigation using Agentic AI Natural Language-Based Frameworks | 多层级专用智能体协作检测幻觉，引入 KPIs 评估 | 生成式 AI 幻觉问题削弱信任 | NLP 系统/生成式 AI |
| 8 | http://arxiv.org/abs/2501.16356v1 | Evaluating Binary Decision Biases in Large Language Models: Implications for Fair Agent-Based Financial Simulations | 测试 GPT 模型二元决策偏差，分析采样方法影响 | LLM 集成到 ABM 可能引入固有偏差 | 基于智能体的金融市场仿真 |
| 9 | http://arxiv.org/abs/2501.11739v2 | Episodic memory in AI agents poses risks that should be studied and mitigated | 分析情景记忆能力的风险与益处，提出四项开发原则 | 情景记忆可能引入新安全风险 | AI 安全研究 |
| 10 | http://arxiv.org/abs/2501.16606v2 | Can We Govern the Agent-to-Agent Economy? | 强调行业新兴概念， informing 研发以 anticipating 未来去中心化智能体经济 | 当前 AI 治理方法难 anticipating 智能体管理关键任务未来经济 | 智能体经济治理/哲学探索 |
| 11 | http://arxiv.org/abs/2501.17070v3 | Contextual Agent Security: A Policy for Every Purpose | 提出上下文智能体安全框架，生成即时可验证安全策略 | 通用智能体支持多任务，需重新思考安全设计适应上下文规模 | 通用智能体安全/策略生成 |
| 12 | http://arxiv.org/abs/2501.17420v1 | Actions Speak Louder than Words: Agent Decisions Reveal Implicit Biases in Language Models | 通过代理决策差异系统揭示 LLM 隐含的社会人口偏见 | 解决 LLM 显式偏见减少但隐含决策偏见仍存在的问题 | LLM 公平性与对齐 |
| 13 | http://arxiv.org/abs/2501.18038v2 | A Case Study in Acceleration AI Ethics: The TELUS GenAI Conversational Agent | 通过 Telus 案例展示加速 AI 伦理框架，平衡创新与安全 | 解决 AI 发展中创新与安全之间的张力及治理问题 | 生成式 AI 伦理治理 |
| 14 | http://arxiv.org/abs/2501.18155v1 | Model Checking for Multi-Agent Systems Modeled By Epistemic Process Calculus | 提出认知过程演算及模型检测算法，验证多智能体系统属性 | 解决多智能体系统复杂认知状态属性形式化验证难题 | 多智能体系统验证 |
| 15 | http://arxiv.org/abs/2501.18190v2 | Economic Rationality under Specialization: Evidence of Decision Bias in AI Agents | 比较 specialized agents 与 GPT 在经济决策中的理性偏差 | 解决专业化是否增强 AI 经济理性及决策偏差问题 | AI 经济决策理性 |
| 16 | http://arxiv.org/abs/2501.18299v1 | Model-Free RL Agents Demonstrate System 1-Like Intentionality | 论证无模型 RL 代理表现出类似系统 1 的意向性，挑战规划假设 | 解决意向性是否需规划及 RL 代理责任归属问题 | RL 代理意向性与安全 |
| 17 | http://arxiv.org/abs/2502.00138v2 | JustAct+: A Framework for Auditable Multi-Agent Systems Regulated by Inter-Organisational Policies | 提出 JustAct+ 框架，实现跨组织策略监管的可审计多代理系统 | 解决开放多代理系统中复杂策略监管及审计问题 | 跨组织多代理系统 |

[返回目录](#目录)

<a id="cat-09"></a>

## Agent学习与自进化

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2501.01702v2 | AgentRefine: Enhancing Agent Generalization through Refinement Tuning | 让模型通过观察轨迹中的错误学习自我纠正，提升泛化 | Agent指令微调后泛化能力差、格式错误多 | LLM Agent通用能力提升 |
| 2 | http://arxiv.org/abs/2501.01821v2 | SDPO: Segment-Level Direct Preference Optimization for Social Agents | 段级DPO动态选择关键交互片段优化多轮对话Agent | 标准DPO在多轮社交对话中粒度过粗、噪声大 | 社交对话Agent |
| 3 | http://arxiv.org/abs/2501.05329v1 | Knowledge Transfer in Model-Based Reinforcement Learning Agents for Efficient Multi-Task Learning | 大型世界模型蒸馏为紧凑模型并量化，保持多任务性能 | 大型RL世界模型在资源受限环境部署困难 | 多任务机器人RL |
| 4 | http://arxiv.org/abs/2501.07278v2 | Lifelong Learning of Large Language Model based Agents: A Roadmap | 系统性综述LLM Agent终身学习技术路线图（感知/记忆/行动三模块） | LLM Agent缺乏随时间持续适应动态环境的能力 | LLM Agent终身学习研究 |
| 5 | http://arxiv.org/abs/2501.09160v1 | AutoLoop: Fast Visual SLAM Fine-tuning through Agentic Curriculum Learning | DDPG Agent自动调整回环闭合权重实现课程学习微调 | 视觉SLAM回环闭合的手动调参和计算开销 | 视觉SLAM系统 |
| 6 | http://arxiv.org/abs/2501.10893v1 | Learn-by-interact: A Data-Centric Framework for Self-Adaptive Agents in Realistic Environments | 基于文档合成智能体 - 环境交互轨迹，反向构建指令 | LLM 智能体缺乏高质量环境交互数据 | 编码/Web/桌面环境 |
| 7 | http://arxiv.org/abs/2501.11425v3 | Agent-R: Training Language Model Agents to Reflect via Iterative Self-Training | 迭代自训练框架，MCTS 构建从错误恢复的训练数据 | 智能体无法从错误中恢复，步级批评数据难收集 | 交互式环境任务 |
| 8 | http://arxiv.org/abs/2501.11733v2 | Mobile-Agent-E: Self-Evolving Mobile Assistant for Complex Tasks | 分层多智能体框架，含 Tips 和 Shortcuts 自进化模块 | 移动智能体难以处理推理密集型长周期任务 | 移动设备复杂任务 |
| 9 | http://arxiv.org/abs/2501.19340v2 | Adaptive Self-Improvement for Smarter Energy Systems using Agentic Policy Search | 提出代理策略搜索框架，LLM 生成控制逻辑并迭代改进 | 解决能源系统手动设计策略复杂及适应慢问题 | 智能能源系统控制 |

[返回目录](#目录)

<a id="cat-10"></a>

## Agent规划与推理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2501.02770v5 | Multi-Agent Pathfinding Under Team-Connected Communication Constraint via Adaptive Path Expansion and Dynamic Leading | 自适应路径扩展与动态领导切换的两级规划框架 | 通信连通约束下多Agent路径规划的可靠性 | 多Agent路径规划 |
| 2 | http://arxiv.org/abs/2501.02803v1 | Enhancing Lifelong Multi-Agent Path Finding with Cache Mechanism | 引入缓存机制和锁定任务分配器优化终身MAPF | 终身MAPF中缓存存储与多机器人路径规划的集成 | 自主仓库机器人调度 |
| 3 | http://arxiv.org/abs/2501.07813v1 | Talk to Right Specialists: Routing and Planning in Multi-agent System for Question Answering | 路由器选择相关Agent+规划器分解多跳查询的双机制 | 跨域查询中单知识源RAG Agent的局限性 | 跨领域问答系统 |
| 4 | http://arxiv.org/abs/2501.14304v2 | MASTER: A Multi-Agent System with LLM Specialized MCTS | 协调智能体招募和通信，基于任务复杂度自主调整智能体数量 | MCTS 依赖大量采样模拟，无客观奖励且 token 消耗大 | 问题求解/任务规划 |
| 5 | http://arxiv.org/abs/2501.15470v2 | CogPlanner: Unveiling the Potential of Agentic Multimodal Retrieval Augmented Generation with Planning | 提出 CogPlanner 框架，迭代确定查询重构和检索策略生成响应 | 现有 MRAG 框架 adheres 刚性单步检索，难处理信息获取挑战 | 多模态检索增强生成 |
| 6 | http://arxiv.org/abs/2501.16689v2 | MACI: Multi-Agent Collaborative Intelligence for Adaptive Reasoning and Temporal Planning | 提出 MACI 框架，含元规划器、智能体集合及运行时监视器 | 传统 LLM 缺乏深思推理、时间意识及有效约束管理能力 | 自适应推理/时间规划 |
| 7 | http://arxiv.org/abs/2501.18922v4 | KBQA-o1: Agentic Knowledge Base Question Answering with Monte Carlo Tree Search | 提出 KBQA-o1，结合 ReAct 与 MCTS 进行知识库问答 | 解决 KBQA 弱感知、效率平衡及依赖标注数据问题 | 知识库问答代理 |

[返回目录](#目录)

<a id="cat-11"></a>

## Agent仿真与社会模拟

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2501.05171v2 | Emergence of human-like polarization among large language model agents | 发现LLM Agent自发形成类人社交网络和极化现象 | 理解LLM Agent集体行为及其对社会极化的影响 | 社会极化模拟与研究 |
| 2 | http://arxiv.org/abs/2501.06834v1 | LLMs Model Non-WEIRD Populations: Experiments with Synthetic Cultural Agents | 用LLM创建合成文化Agent模拟非WEIRD人群行为 | 研究非WEIRD人群经济行为的实验困难 | 跨文化经济行为研究 |
| 3 | http://arxiv.org/abs/2501.08985v1 | Personality Modeling for Persuasion of Misinformation using AI Agent | 大五人格AI Agent模拟错误信息传播中的说服动态 | 人格特质如何影响错误信息的易感性和传播 | 社交媒体错误信息对抗 |
| 4 | http://arxiv.org/abs/2503.15497v1 | The Impact of Big Five Personality Traits on AI Agent Decision-Making in Public Spaces | 大五人格Agent公共/私人决策差异揭示社交情境影响 | 人格特质如何影响AI Agent在公共场所的决策 | AI Agent社会行为模拟 |
| 5 | http://arxiv.org/abs/2502.00022v1 | A Dynamic and High-Precision Method for Scenario-Based HRA Synthetic Data Collection in Multi-Agent Collaborative Environments Driven by LLMs | LLM微调模拟人类行为和认知负荷，动态估算协作场景工作负载 | HRA数据采集缺乏粒度和动态特征 | 核电站人因可靠性分析 |
| 6 | http://arxiv.org/abs/2501.09429v1 | ADAGE: A generic two-layer framework for adaptive agent based modelling | 双层自适应ABM框架将双层问题形式化为Stackelberg博弈 | Agent行为和环境同时适应的双层适应性ABM建模 | 经济/金融Agent仿真 |
| 7 | http://arxiv.org/abs/2501.16355v2 | How Strategic Agents Respond: Comparing Analytical Models with LLM-Generated Responses in Strategic Classification | 比较 LLM 生成策略与理论模型，分析个体/群体层面行为 | LLM 是否改变智能体战略行为假设 | 战略分类场景 (招聘/贷款等) |
| 8 | http://arxiv.org/abs/2501.15048v1 | YouTube Recommendations Reinforce Negative Emotions: Auditing Algorithmic Bias with Emotionally-Agentic Sock Puppets | 使用袜子傀儡审计方法，模拟具有情感偏好的用户账户导航平台 | 个性化推荐算法可能无意中强化冲动和情感偏见 | 推荐系统审计/算法偏见 |
| 9 | http://arxiv.org/abs/2501.15283v1 | Are Human Interactions Replicable by Generative Agents? A Case Study on Pronoun Usage in Hierarchical Interactions | 调查 LLM 智能体交互是否类似人类，聚焦层级交互中代词使用差异 | LLM 基于社会模拟能否复制人类交互模式尚不明确 | 社会模拟/生成式智能体 |
| 10 | http://arxiv.org/abs/2501.15317v1 | Welfare Modeling with AI as Economic Agents: A Game-Theoretic and Behavioral Approach | 提出包含博弈论和行为维度的福利模型，利用 ABM 模拟人机交互 | AI 集成到经济系统引入新动态，需优化人机生态系统交互 | 经济系统/人机协作 |
| 11 | http://arxiv.org/abs/2501.16090v1 | Galaxy Era: Agent-based Simulation of Execution Tickets | 构建六具体机制设计，执行超 300 次基于智能体模拟评估权衡 | 需评估执行票机制设计在真实条件下权衡及最优配置 | 以太坊区块空间分配/机制设计 |
| 12 | http://arxiv.org/abs/2501.16173v1 | Will Systems of LLM Agents Cooperate: An Investigation into a Social Dilemma | 利用进化博弈论模拟不同战略倾向智能体种群，观察进化动态 | 需理解自主智能体集体行为及战略交互中 emergent 合作倾向 | 社会困境/LLM 智能体系统 |
| 13 | http://arxiv.org/abs/2501.16935v1 | Beyond Human Intervention: Algorithmic Collusion through Multi-Agent Learning Strategies | 探索智能体多目标策略，学习建模其他智能体行为直接实现共谋 | 算法共谋技术易受其他玩家利用，难实践实施 | 市场定价/算法共谋 |
| 14 | http://arxiv.org/abs/2501.17015v1 | Revisit Mixture Models for Multi-Agent Simulation: Experimental Study within a Unified Framework | 重访混合模型生成多模态智能体行为，引入闭环样本生成方法 | 多智能体模拟中行为多模态性及闭环分布偏移是关键挑战 | 自动驾驶模拟/行为生成 |
| 15 | http://arxiv.org/abs/2501.18177v2 | Investigating Tax Evasion Emergence Using Dual Large Language Model and Deep Reinforcement Learning Powered Agent-based Simulation | 利用 LLM 和 DRL 驱动代理模拟，研究逃税行为涌现 dynamics | 解决传统研究假设逃税行为给定而非涌现出现的局限 | 税务逃税社会模拟 |
| 16 | http://arxiv.org/abs/2501.19168v1 | Implications of zero-growth economics analysed with an agent-based model | 开发宏观经济学代理模型，分析零增长经济稳定性 | 解决零增长轨迹在资本主义系统中经济稳定性未知问题 | 零增长经济模拟 |

[返回目录](#目录)

<a id="cat-12"></a>

## 具身智能Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2501.06262v2 | Towards smart and adaptive agents for active sensing on edge devices | 结合主动推理实现边缘设备上感知与规划的Agent系统 | 边缘设备深度学习模型缺乏环境动态适应能力 | IoT边缘设备主动感知 |
| 2 | http://arxiv.org/abs/2501.07802v1 | Visual Language Models as Operator Agents in the Space Domain | VLM作为太空领域操作Agent，在仿真和硬件中执行任务 | 太空任务中自主控制和决策的智能化 | 太空任务（轨道机动/卫星检查） |
| 3 | http://arxiv.org/abs/2501.08944v1 | Physical AI Agents: Integrating Cognitive Intelligence with Real-World Action | 感知-认知-执行三模块架构+Ph-RAG连接物理智能与LLM | 垂直AI Agent从数字世界扩展到物理世界交互 | 自动驾驶/仓储机器人/制造业 |
| 4 | http://arxiv.org/abs/2501.10262v1 | Deployment of an Aerial Multi-agent System for Automated Task Execution in Large-scale Underground Mining Environments | 基于拍卖的任务分配系统，行为树生成模块化智能体行为 | 地下矿山环境中多智能体任务分配与执行 | 地下采矿巡检 |
| 5 | http://arxiv.org/abs/2501.14443v1 | Learning more with the same effort: how randomization improves the robustness of a robotic deep reinforcement learning agent | 分析渐进神经网络鲁棒性，研究仿真经验多样性如何补充 sim-to-real | 工业 DRL 应用因生成经验成本高而放缓，sim-to-real 转移难 | 机器人训练/强化学习 |
| 6 | http://arxiv.org/abs/2501.18016v2 | Digital Twin Synchronization: Bridging the Sim-RL Agent to a Real-Time Robotic Additive Manufacturing Control | 结合 SAC 与数字孪生实现工业机器人实时自适应控制 | 解决智能制造中动态自适应控制机制优化复杂过程难题 | 机器人增材制造控制 |
| 7 | http://arxiv.org/abs/2501.18867v3 | UP-VLA: A Unified Understanding and Prediction Model for Embodied Agent | 提出 UP-VLA 模型，统一多模态理解与未来预测目标训练 | 解决 VLA 模型忽视低层空间信息及物理动态理解问题 | 具身智能代理控制 |

[返回目录](#目录)

<a id="cat-13"></a>

## Agent工具使用与环境交互

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2501.05366v1 | Search-o1: Agentic Search-Enhanced Large Reasoning Models | 将Agent式搜索嵌入推理链，配合Reason-in-Documents模块精炼检索结果 | 大推理模型长步骤推理中知识不足导致的不确定性和错误 | 科学/数学/编程复杂推理任务 |
| 2 | http://arxiv.org/abs/2501.10120v2 | PaSa: An LLM Agent for Comprehensive Academic Paper Search | LLM 驱动的智能体自主调用搜索工具、阅读论文、选择参考文献 | 复杂学术查询难以获得全面准确结果 | 学术研究/文献检索 |
| 3 | http://arxiv.org/abs/2501.11233v1 | PlotEdit: Natural Language-Driven Accessible Chart Editing in PDFs via Multimodal LLM Agents | 五智能体框架协调图表数据提取、风格识别、代码生成、编辑 | PDF 中图表缺乏源数据和样式信息难以编辑 | 视障用户/图表编辑 |
| 4 | http://arxiv.org/abs/2501.12326v1 | UI-TARS: Pioneering Automated GUI Interaction with Native Agents | 原生 GUI 智能体模型，端到端感知截图执行人机交互 | 现有框架依赖商业模型和专家提示 | GUI 自动化交互 |
| 5 | http://arxiv.org/abs/2501.13746v1 | EICopilot: Search and Explore Enterprise Information over Large-scale Knowledge Graphs with LLM-driven Agents | 利用 LLM 解释自然语言查询，自动生成执行 Gremlin 脚本 | 传统方法需文本查询和手动子图探索，耗时 | 企业信息搜索/知识图谱 |
| 6 | http://arxiv.org/abs/2503.15515v1 | Towards Computer-Using Personal Agents | 提出计算机使用个人代理 (CUPA)，访问用户个人数据仓库 | 解决 CUA 缺乏个人数据控制及协作任务能力问题 | 个人计算机使用代理 |

[返回目录](#目录)

<a id="cat-14"></a>

## Agent可解释性与透明度

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2501.13945v1 | Self-Explanation in Social AI Agents | 基于自模型内省，使用思维链生成自我解释 | 社会 AI 智能体需增强透明度和信任 | 在线学习/社会辅助 |
| 2 | http://arxiv.org/abs/2501.18645v2 | Layered Chain-of-Thought Prompting for Multi-Agent LLM Systems: A Comprehensive Approach to Explainable Large Language Models | 提出分层思维链提示，将推理分段并进行外部检查 | 解决传统思维链中间推断未验证及解释误导性问题 | 多代理 LLM 可解释性 |

[返回目录](#目录)

<a id="cat-15"></a>

## Agent记忆与知识管理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2501.13956v1 | Zep: A Temporal Knowledge Graph Architecture for Agent Memory | 时间感知知识图谱引擎 Graphiti，动态合成非结构化/结构化数据 | RAG 框架限于静态文档检索，企业需动态知识整合 | 企业级 AI 应用 |
| 2 | http://arxiv.org/abs/2501.12485v3 | R2D2: Remembering, Replaying and Dynamic Decision Making with a Reflective Agentic Memory | 记住 - 反思双范式，重放缓冲区重建 Web 环境地图 | Web 智能体导航效率低，理解 Web 结构有限 | Web 自动化/数字助理 |

[返回目录](#目录)

