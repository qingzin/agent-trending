# AI agents 2026年2月学术分类汇总

共收录 956 篇论文，按研究方向分类整理如下。

## 目录

- [多Agent协作与通信（91篇）](#cat-01)
- [基于Agent的应用系统（143篇）](#cat-02)
- [Agent架构与框架设计（109篇）](#cat-03)
- [多Agent强化学习（66篇）](#cat-04)
- [Agent仿真与社会模拟（43篇）](#cat-05)
- [Agent安全与对齐（115篇）](#cat-06)
- [Agent工具使用与环境交互（38篇）](#cat-07)
- [Agent规划与推理（36篇）](#cat-08)
- [人机协作Agent（42篇）](#cat-09)
- [Agent学习与自进化（78篇）](#cat-10)
- [Agent记忆与知识管理（45篇）](#cat-11)
- [Agent评测与基准（102篇）](#cat-12)
- [具身智能Agent（38篇）](#cat-13)
- [Agent可解释性与透明度（9篇）](#cat-14)
- [低代码/无代码Agent平台（1篇）](#cat-15)

<a id="cat-01"></a>

## 多Agent协作与通信

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2602.00948v1 | FinEvo: From Isolated Backtests to Ecological Market Games for Multi-Agent Financial Strategy Evolution | 提出生态博弈形式化框架，模拟多Agent金融策略演化动力学 | 传统回测无法捕捉策略间交互与市场演化动态 | 金融市场多Agent策略评估 |
| 2 | http://arxiv.org/abs/2602.00966v1 | Symphony-Coord: Emergent Coordination in Decentralized Agent Systems | 两阶段动态信标协议与自适应LinUCB选择器实现去中心化协调 | 静态角色分配导致路由低效、适应性差、故障恢复脆弱 | 去中心化多Agent任务协调 |
| 3 | http://arxiv.org/abs/2602.00996v1 | DeALOG: Decentralized Multi-Agents Log-Mediated Reasoning Framework | 基于共享自然语言日志的去中心化多Agent协作框架 | 多模态问答需整合多样信息源且需协调与可解释性 | 多模态复杂问答任务 |
| 4 | http://arxiv.org/abs/2602.01011v3 | Multi-Agent Teams Hold Experts Back | 揭示LLM团队无法发挥专家能力的整合妥协倾向 | 自组织LLM团队无法有效利用成员集体专业知识 | 多Agent团队协作效能 |
| 5 | http://arxiv.org/abs/2602.02597v1 | ContextEvolve: Multi-Agent Context Compression for Systems Code Optimization | 三Agent正交分解优化上下文实现RL级搜索效率 | 无参数更新约束下进化方法上下文利用低效搜索无方向 | 系统代码性能优化 |
| 6 | http://arxiv.org/abs/2602.01331v1 | A-MapReduce: Executing Wide Search via Agentic MapReduce | MapReduce范式启发的水平结构化检索与并行处理框架 | 现有框架针对垂直搜索无法高效处理大规模广度检索 | 大规模广泛搜索任务 |
| 7 | http://arxiv.org/abs/2602.01465v2 | Agyn: A Multi-Agent System for Team-Based Autonomous Software Engineering | 显式建模软件工程为组织流程复制工程团队结构 | 自主系统将问题 resolution视为单体或流水线而非协作活动 | 自主软件工程项目开发 |
| 8 | http://arxiv.org/abs/2602.03026v1 | Visual Reasoning over Time Series via Multi-Agent System | Analyzer-Reasoner-Executor三Agent协作，共享记忆+门控通信 | 时间序列分析缺乏直观视觉推理和自适应工具使用 | 通用时间序列任务 |
| 9 | http://arxiv.org/abs/2602.03028v1 | MUSE: A Multi-agent Framework for Unconstrained Story Envisioning via Closed-Loop Cognitive Orchestration | 计划-执行-验证-修订闭环，显式控制身份/空间/时间连续性 | 长程音视频故事生成中语义漂移和身份不一致 | 长程音视频故事生成 |
| 10 | http://arxiv.org/abs/2602.03145v1 | Internet of Agentic AI: Incentive-Compatible Distributed Teaming and Workflow | 网络原生协作模型，激励兼容工作流-联盟可行性框架 | 现有架构中心化单体限制可扩展性和互操作性 | 云边分布式异构Agent协作 |
| 11 | http://arxiv.org/abs/2602.03158v1 | PAMAS: Self-Adaptive Multi-Agent System with Perspective Aggregation for Misinformation Detection | 审计员-协调员-决策者三层角色，层次化视角聚合突出异常线索 | 传统MAS信息淹没问题，真实内容压倒稀疏欺骗线索 | 社交媒体虚假信息检测 |
| 12 | http://arxiv.org/abs/2602.03318v2 | MIRROR: A Multi-Agent Framework with Iterative Adaptive Revision and Hierarchical Retrieval for Optimization Modeling in Operations Research | 执行驱动迭代自适应修订+层次检索获取建模范例 | OR建模依赖专家缓慢脆弱，现有方法缺乏可靠协作纠错 | 运筹优化自然语言到数学模型翻译 |
| 13 | http://arxiv.org/abs/2602.03414v1 | Socratic-Geo: Synthetic Data Generation and Geometric Reasoning via Multi-Agent Interaction | Teacher-Solver-Generator三Agent动态耦合，反射反馈保证图像-文本对纯度 | 几何推理高质量图像-文本对极度稀缺，自动方法无法保证保真度 | 多模态几何推理数据合成 |
| 14 | http://arxiv.org/abs/2602.03595v2 | Refer-Agent: A Collaborative Multi-Agent System with Reasoning and Reflection for Referring Video Object Segmentation | 推理-反思交替机制，粗到细帧选择+动态焦点布局+反思链 | 现有零样本方法性能落后SFT，工作流设计过于简单 | 引用视频对象分割 |
| 15 | http://arxiv.org/abs/2602.03674v1 | When Should Agents Coordinate in Differentiable Sequential Decision Problems? | 协调作为频谱建模，二阶推理确定Agent团队何时应协调 | 协调需要昂贵通信，不协调时团队结果可能受损 | 可微分运动规划问题中的多机器人团队 |
| 16 | http://arxiv.org/abs/2602.03687v1 | Efficient Investment in Multi-Agent Models of Public Transportation | 研究两风格化多Agent模型投资有限不可分资源于公共交通 | 计算近似最优解关于平等福利是NP完全，可变Agent数时存在复杂性结果 | 公共交通网络投资设计 |
| 17 | http://arxiv.org/abs/2602.03688v1 | TodyComm: Task-Oriented Dynamic Communication for Multi-Round LLM-based Multi-Agent System | 任务导向动态通信算法，每轮生成行为驱动协作拓扑优化任务效用 | 现有方法推理时用固定通信拓扑，无法适应跨轮角色变化 | 多轮LLM多Agent系统 |
| 18 | http://arxiv.org/abs/2602.01815v1 | INDIBATOR: Diverse and Fact-Grounded Individuality for Multi-Agent Debate in Molecular Discovery | 基于科学家个人档案的细粒度智能体个性化辩论框架 | 解决通用角色设定 oversimplify 科学发现过程问题 | 分子发现与科学探索 |
| 19 | http://arxiv.org/abs/2602.02350v1 | Context Learning for Multi-Agent Discussion | 多 LLM 上下文学习方法，动态生成上下文指令 | 解决多智能体讨论中上下文不一致导致收敛失败问题 | 学术推理与 embodied 任务 |
| 20 | http://arxiv.org/abs/2602.02636v1 | WideSeek: Advancing Wide Research via Multi-Agent Scaling | 动态分层多智能体架构，自主 fork 并行子智能体 | 解决复杂约束下搜索广度缺乏专用优化方法问题 | 广泛信息检索与研究 |
| 21 | http://arxiv.org/abs/2602.02751v1 | Scaling Small Agents Through Strategy Auctions | 基于策略拍卖的框架，小智能体竞价战略规划 | 解决小模型在复杂任务中性能无法扩展问题 | 深度搜索与编码任务 |
| 22 | http://arxiv.org/abs/2602.03794v1 | Understanding Agent Scaling in LLM-Based Multi-Agent Systems via Diversity | 信息论框架，异质性优于同质性扩展 | 同质代理扩展收益递减问题 | 多智能体系统设计 |
| 23 | http://arxiv.org/abs/2602.04152v1 | MA3DSG: Multi-Agent 3D Scene Graph Generation for Large-Scale Indoor Environments | 多代理 3D 场景图生成，无需训练对齐 | 单代理假设限制大规模环境扩展 | 3D 场景理解/机器人 |
| 24 | http://arxiv.org/abs/2602.04234v2 | On the Uncertainty of Large Language Model-Based Multi-Agent Systems | 通过熵过渡分析多代理系统不确定性 | 多代理系统成功或失败的基本原理 | 多智能体系统理论 |
| 25 | http://arxiv.org/abs/2603.04416v1 | Optimizing What We Trust: Reliability-Guided QUBO Selection of Multi-Agent Weak Framing Signals for Arabic Sentiment Prediction | 可靠性感知弱监督，多代理 LLM 管道 | 阿拉伯语社交媒体框架检测困难 | NLP/情感分析 |
| 26 | http://arxiv.org/abs/2602.04418v1 | SPEAR: An Engineering Case Study of Multi-Agent Coordination for Smart Contract Auditing | 多代理协调框架，智能合约审计 | 安全分析工作流中的协调与恢复 | 智能合约审计 |
| 27 | http://arxiv.org/abs/2602.04587v2 | VILLAIN at AVerImaTeC: Verifying Image-Text Claims via Multi-Agent Collaboration | 多模态事实检查，基于提示的多代理协作 | 验证图像 - 文本声明的准确性 | 事实检查/多模态 |
| 28 | http://arxiv.org/abs/2602.05004v1 | CoWork-X: Experience-Optimized Co-Evolution for Multi-Agent Collaboration System | 主动协同进化框架，跨 episode 闭环优化 | 高协作任务实时协调与适应约束 | 多代理协作系统 |
| 29 | http://arxiv.org/abs/2602.07777v1 | Talk, Judge, Cooperate: Gossip-Driven Indirect Reciprocity in Self-Interested LLM Agents | ALIGN框架，Agent用层级语气分享开放八卦评估信任 | 去中心化自利LLM Agent中间接互惠难以维持 | 自利LLM Agent生态系统 |
| 30 | http://arxiv.org/abs/2602.07787v1 | Do Multi-Agents Dream of Electric Screens? Achieving Perfect Accuracy on AndroidWorld Through Task Decomposition | Minitap六专用Agent认知分离，实现AndroidWorld 100%成功率 | 单Agent架构存在上下文污染、静默输入失败、重复循环 | Android设备自动化任务 |
| 31 | http://arxiv.org/abs/2602.08009v1 | Towards Adaptive, Scalable, and Robust Coordination of LLM Agents: A Dynamic Ad-Hoc Networking Perspective | RAPS框架声誉感知发布订阅范式，动态Ad-Hoc网络视角 | 多Agent架构手动编排负担重需自动化设计 | 可扩展数量的LLM Agent协调 |
| 32 | http://arxiv.org/abs/2602.13292v1 | Mirror: A Multi-Agent System for AI-Assisted Ethics Review | Mirror框架整合伦理推理、结构化规则解释、多Agent审议 | 伦理审查系统面临跨学科大规模科学实践结构性风险 | AI辅助的伦理审查系统 |
| 33 | http://arxiv.org/abs/2602.05289v1 | Towards a Science of Collective AI: LLM-based Multi-Agent Systems Need a Transition from Blind Trial-and-Error to Rigorous Science | 倡导转向设计科学，建立协作增益指标和因素归因范式，构建系统因子库。 | 解决多智能体系统依赖经验试错，缺乏统一科学框架进行系统优化的问题。 | 集体 AI 系统设计 |
| 34 | http://arxiv.org/abs/2602.06008v1 | AgenticPay: A Multi-Agent LLM Negotiation System for Buyer-Seller Transactions | 引入基准和仿真框架，模拟买卖双方通过多轮语言谈判而非仅数字竞价达成协议。 | 解决现有基准缺乏原则性设置评估多代理间语言介导经济交互的问题。 | 买家 - 卖家交易谈判 |
| 35 | http://arxiv.org/abs/2602.06038v1 | CommCP: Efficient Multi-Agent Coordination via LLM-Based Communication with Conformal Prediction | 提出 CommCP 框架，利用共形预测校准 LLM 通信消息，减少干扰。 | 解决多智能体协作中通信冗余和可靠性低的问题。 | 多机器人协作场景 |
| 36 | http://arxiv.org/abs/2602.06039v1 | DyTopo: Dynamic Topology Routing for Multi-Agent Reasoning via Semantic Matching | 引入管理器指导的动态拓扑路由，基于语义匹配重构通信图。 | 解决固定通信模式无法匹配迭代问题解决需求的问题。 | 多轮推理任务 |
| 37 | http://arxiv.org/abs/2602.06526v1 | Completing Missing Annotation: Multi-Agent Debate for Accurate and Scalable Relevant Assessment for IR Benchmarks | 提出 DREAM 框架，基于对立立场和多轮辩论评估相关性。 | 解决 IR 基准数据集标注不完整和 LLM 过度自信的问题。 | 信息检索评估 |
| 38 | http://arxiv.org/abs/2602.06733v1 | Pairwise is Not Enough: Hypergraph Neural Networks for Multi-Agent Pathfinding | 提出 HMAGAT，利用 hypergraph 注意力捕捉 group 动态。 | 解决 pairwise 消息传递在 dense 环境中 attention dilution 问题。 | 多 Agent 路径规划 |
| 39 | http://arxiv.org/abs/2602.06925v1 | Strategizing at Speed: A Learned Model Predictive Game for Multi-Agent Drone Racing | 提出 LMPG，amortize 模型预测博弈以减少 latency。 | 解决高速无人机 racing 中策略规划 latency 过高的问题。 | 多 Agent 无人机竞赛 |
| 40 | http://arxiv.org/abs/2602.07186v1 | The Value of Variance: Mitigating Debate Collapse in Multi-Agent Systems via Uncertainty-Driven Policy Optimization | 量化行为 uncertainty，提出 uncertainty-driven 策略优化防止 debate collapse。 | 解决多 Agent 辩论系统最终决策 compromised 的问题。 | 多 Agent 推理系统 |
| 41 | http://arxiv.org/abs/2602.10996v1 | The emergence of numerical representations in communicating artificial agents | 研究神经智能体在指称游戏中通过离散/连续通道沟通数量 | 沟通压力是否足以产生数值表示及类似人类数字代码 | 人工智能体沟通系统 |
| 42 | http://arxiv.org/abs/2602.15055v1 | Beyond Context Sharing: A Unified Agent Communication Protocol (ACP) for Secure, Federated, and Autonomous Agent-to-Agent (A2A) Orchestration | 提出统一代理通信协议，支持去中心化身份验证和语义意图映射 | 跨平台、去中心化和安全交互的障碍 | 自主数字实体生态系统 |
| 43 | http://arxiv.org/abs/2602.11330v1 | When agents choose bundles autonomously: guarantees beyond discrepancy | 提出顺序选择机制，保证每个智能体获得至少 PROP-O(log n) 价值 | 不可分物品公平分配中的差异屏障限制 | 多智能体资源分配 |
| 44 | http://arxiv.org/abs/2602.11527v1 | CausalAgent: A Conversational Multi-Agent System for End-to-End Causal Inference | 集成 MAS、RAG 和 MCP，通过自然语言交互实现端到端因果推断 | 传统因果分析工作流技术壁垒高，需双重背景 | 因果推断多智能体系统 |
| 45 | http://arxiv.org/abs/2602.11583v1 | The Five Ws of Multi-Agent Communication: Who Talks to Whom, When, What, and Why -- A Survey from MARL to Emergent Language and LLMs | 通过 Five Ws 框架 review 多智能体通信，连接 MARL、EL 和 LLM | 不同研究线程分离，缺乏统一视角连接 ideas | 多智能体 sequential decision-making |
| 46 | http://arxiv.org/abs/2602.11754v1 | Cooperation Breakdown in LLM Agents Under Communication Delays | 提出 FLCOA 框架，模拟通信延迟对合作的影响，发现 U 型关系 | 忽略底层因素如计算和通信资源对合作的影响 | LLM 多智能体系统 |
| 47 | http://arxiv.org/abs/2602.11790v1 | Beyond End-to-End Video Models: An LLM-Based Multi-Agent System for Educational Video Generation | 分层多智能体系统，分解工作流为 specialized agents  coordinated by Orchestrating Agent | 端到端视频生成模型缺乏逻辑严谨性和精确知识表示 | 教育视频生成 |
| 48 | http://arxiv.org/abs/2602.12024v1 | Adaptive-Horizon Conflict-Based Search for Closed-Loop Multi-Agent Path Finding | 基于有限 horizon CBS，动态调整规划 horizon，重用 constraint tree | 开环规划难处理 disturbances，闭环启发式无可靠性能保证 | 自动化仓库物流机器人车队 |
| 49 | http://arxiv.org/abs/2602.14471v1 | Socially-Weighted Alignment: A Game-Theoretic Framework for Multi-Agent LLM Systems | 博弈论框架通过社会权重插值个体目标与群体福利 | 局部理性决策产生负外部性，降低系统级性能 | 共享资源环境多Agent系统 |
| 50 | http://arxiv.org/abs/2602.14668v1 | Near-Optimal Best-of-Both-Worlds Fairness for Few Agents | 首个BoBW算法实现三Agent近最优公平分配 | 不可分物品公平分配中MMS分配不存在 | 多Agent资源公平分配 |
| 51 | http://arxiv.org/abs/2602.14681v3 | ST-EVO: Towards Generative Spatio-Temporal Evolution of Multi-Agent Communication Topologies | 支持对话级通信调度的时空演化多Agent系统 | 当前自演化MAS仅考虑单维度演化，未充分激励协作 | LLM多Agent协作系统 |
| 52 | http://arxiv.org/abs/2602.14770v2 | Multi-Agent Comedy Club: Investigating Community Discussion Effects on LLM Humor Generation | 社区讨论作为社会记忆条件化后续生成，提升幽默质量 | 在线社区持久公众接受度在LLM写作中未充分研究 | LLM幽默生成 |
| 53 | http://arxiv.org/abs/2602.14926v1 | MAC-AMP: A Closed-Loop Multi-Agent Collaboration System for Multi-Objective Antimicrobial Peptide Design | 闭环多Agent协作系统，自主模拟同行评审-自适应RL | AMP设计模型难以平衡活性、毒性、新颖性多目标 | 抗菌肽药物设计 |
| 54 | http://arxiv.org/abs/2602.15382v1 | The Vision Wormhole: Latent-Space Communication in Heterogeneous Multi-Agent Systems | 通用视觉编解码器映射异构推理轨迹到共享潜在空间 | 离散文本通信效率低，潜在状态转移假设同构架构 | 异构多Agent系统通信 |
| 55 | http://arxiv.org/abs/2602.08452v1 | Modeling Concurrent Multi-Agent Systems | 提出基于电路的模型，分析并发多智能体系统的复杂性。 | 解决显式模型在均衡分析中缺乏表达力的问题。 | 多智能体系统理论建模 |
| 56 | http://arxiv.org/abs/2602.09159v1 | CoMMa: Contribution-Aware Medical Multi-Agents From A Game-Theoretic Perspective | 利用博弈论目标协调专科代理，近似贡献感知信用分配。 | 解决肿瘤决策支持中动态异构数据推理与稳定性问题。 | 医疗多学科决策 |
| 57 | http://arxiv.org/abs/2602.13639v1 | Guided Collaboration in Heterogeneous LLM-Based Multi-Agent Systems via Entropy-Based Understanding Assessment and Experience Retrieval | 提出基于熵的自适应指导框架，动态对齐强弱代理认知状态 | 解决异构多智能体系统中认知不匹配导致协作性能下降问题 | 异构多智能体协作 |
| 58 | http://arxiv.org/abs/2602.13671v1 | MAS-on-the-Fly: Dynamic Adaptation of LLM-based Multi-Agent Systems at Test Time | 利用检索增强 SOP 实例化与经验指导监督，实现测试时动态适应 | 解决多智能体系统部署后缺乏动态适应性及鲁棒性的问题 | 动态任务多智能体系统 |
| 59 | http://arxiv.org/abs/2602.13793v1 | OMGs: A multi-agent system supporting MDT decision-making across the ovarian tumour care continuum | 领域特定代理协作整合多学科证据，生成透明理由的 MDT 建议 | 解决资源受限中心缺乏及时专家共识及多学科诊疗资源稀缺问题 | 卵巢肿瘤多学科诊疗 |
| 60 | http://arxiv.org/abs/2603.04421v2 | Do Mixed-Vendor Multi-Agent LLMs Improve Clinical Diagnosis? | 比较混合供应商多代理对话，发现池化互补归纳偏差提升诊断准确率 | 解决单一供应商团队存在相关故障模式及强化共享偏见的问题 | 临床诊断多代理系统 |
| 61 | http://arxiv.org/abs/2602.14251v1 | Multi-Agent Debate: A Unified Agentic Framework for Tabular Anomaly Detection | 将 disagreement 作为一级信号，数学 grounded 协调层解决异构模型分歧 | 解决表格异常检测单检测器或静态 ensemble 在分布 shift 下性能弱问题 | 表格异常检测 |
| 62 | http://arxiv.org/abs/2602.15721v1 | Lifelong Scalable Multi-Agent Realistic Testbed and A Comprehensive Study on Design Choices in Lifelong AGV Fleet Management Systems | 提出 LSMART 仿真器，评估终身多 Agent 路径寻找算法设计选择 | 解决 AGV 车队管理中规划执行并行化与恢复策略问题 | 自动化仓库与 AGV 车队管理系统 |
| 63 | http://arxiv.org/abs/2602.15776v1 | GlobeDiff: State Diffusion Process for Partial Observability in Multi-Agent Systems | 提出全局状态扩散算法，基于局部观测推断全局状态 | 解决多 Agent 系统中部分可观测性导致的协调障碍 | 多 Agent 协作与决策系统 |
| 64 | http://arxiv.org/abs/2602.16301v1 | Multi-agent cooperation through in-context co-player inference | 利用序列模型 in-context 学习实现 co-player 学习感知与合作 | 解决自利 Agent 间无需硬编码假设即可诱导合作的问题 | 多 Agent 强化学习与合作机制 |
| 65 | http://arxiv.org/abs/2602.16424v2 | Verifiable Semantics for Agent-to-Agent Communication | 提出基于刺激意义模型的认证协议，验证 Agent 间语义一致性 | 解决自然语言通信中语义漂移导致理解不一致问题 | 多 Agent 系统通信与协作 |
| 66 | http://arxiv.org/abs/2602.17738v1 | Reasoning-Native Agentic Communication for 6G | 提出推理原生通信范式，根据信念状态不一致预测激活通信。 | 代理内部推理演化不同导致行为不一致的信念分歧问题。 | 6G 网络自主机器 |
| 67 | http://arxiv.org/abs/2602.17049v2 | IntentCUA: Learning Intent-level Representations for Skill Abstraction and Multi-Agent Planning in Computer-Use Agents | 多智能体框架，通过意图对齐计划记忆稳定长程执行。 | 长程操作下偏离用户意图及重复解决常规子问题。 | 计算机使用代理 |
| 68 | http://arxiv.org/abs/2602.13313v1 | Agentic Spatio-Temporal Grounding via Collaborative Reasoning | 提出 ASTG 框架，利用空间和时间推理 Agent 协作，自主检索目标管。 | 解决视频时空定位中计算冗余、监督重及泛化有限的问题，实现免训练。 | 视频时空定位 |
| 69 | http://arxiv.org/abs/2602.10933v1 | CMAD: Cooperative Multi-Agent Diffusion via Stochastic Optimal Control | 将组合生成 formulate 为合作随机最优控制问题，联合 steer 扩散轨迹。 | 解决控制多个预训练模型组合挑战，避免显式已知目标分布假设。 | 生成模型组合 |
| 70 | http://arxiv.org/abs/2602.19304v1 | Safe and Interpretable Multimodal Path Planning for Multi-Agent Cooperation | 提出 CaPE 方法，利用 VLM 合成路径编辑程序确保多智能体安全 | 解决去中心化 Agent 路径协作中意图预测难及安全性问题 | 多智能体路径协作 |
| 71 | http://arxiv.org/abs/2603.00121v1 | Graph-theoretic Agreement Framework for Multi-agent LLM Systems | 建立图论框架分析签名有向网络共识，映射 Transformer 熵到拉普拉斯 | 解决多智能体 LLM 系统中的共识稳定性与潜在状态不可观测问题 | 多智能体 LLM 系统 |
| 72 | http://arxiv.org/abs/2602.19672v1 | SkillOrchestra: Learning to Route Agents via Skill Transfer | 学习细粒度技能而非端到端路由，建模智能体能力与成本权衡 | 解决现有路由方法忽略任务需求演变及 RL 训练成本高的问题 | 复合 AI 系统编排 |
| 73 | http://arxiv.org/abs/2603.00130v1 | Agentic Hives: Equilibrium, Indeterminacy, and Endogenous Cycles in Self-Organizing Multi-Agent Systems | 引入智能体蜂巢框架，支持智能体种群出生、死亡与专业化动态 | 解决多智能体系统运行时种群结构响应资源与目标变化问题 | 自组织多智能体系统 |
| 74 | http://arxiv.org/abs/2602.19840v1 | SAMAS: A Spectrum-Guided Multi-Agent System for Achieving Style Fidelity in Literary Translation | 将风格保存视为信号处理，用小波包变换量化风格特征谱 | 解决单模型系统无法感知适应文学风格变化导致输出通用化问题 | 文学翻译 |
| 75 | http://arxiv.org/abs/2602.20229v1 | HieraMAS: Optimizing Intra-Node LLM Mixtures and Inter-Node Topology for Multi-Agent Systems | 分层协作框架，结合节点内 LLM 混合与节点间通信拓扑优化 | 解决现有方法仅优化单一层面忽略节点内 LLM 混合增强问题 | 多智能体系统优化 |
| 76 | http://arxiv.org/abs/2602.20493v1 | AWCP: A Workspace Delegation Protocol for Deep-Engagement Collaboration across Remote Agents | 提出工作空间委托协议，桥接上下文 gap 允许直接操作 peer 文件 | 解决现有协作范式局限于消息传递导致环境重建成本高问题 | 远程智能体协作 |
| 77 | http://arxiv.org/abs/2602.20664v1 | AnimeAgent: Is the Multi-Agent via Image-to-Video models a Good Disney Storytelling Artist? | 首个基于 I2V 的多智能体框架，利用隐式运动先验增强一致性 | 解决静态模型缺乏动态表达及多智能体评估器非鲁棒问题 | 故事板生成 |
| 78 | http://arxiv.org/abs/2603.00142v1 | Evaluating Theory of Mind and Internal Beliefs in LLM-Based Multi-Agent Systems | 集成 ToM、BDI 信念与符号求解器，评估协作决策影响 | 解决动态世界中简单添加认知机制无法自动改善协调问题 | 多智能体协作智能 |
| 79 | http://arxiv.org/abs/2602.20936v1 | Empathy Modeling in Active Inference Agents for Perspective-Taking and Alignment | 基于主动推理的共情框架，通过自我 - 其他模型转换实现视角采择。 | 解决多智能体间缺乏理解与对齐导致的合作失败问题。 | 多智能体博弈系统 |
| 80 | http://arxiv.org/abs/2602.21351v1 | A Hierarchical Multi-Agent System for Autonomous Discovery in Geoscientific Data Archives | 实现集中式 Supervisor-Worker 拓扑与严格数据类型感知路由。 | 解决地球科学数据档案规模大及利用率低的可扩展性挑战。 | 地球科学数据档案 |
| 81 | http://arxiv.org/abs/2603.13256v1 | Training-Free Agentic AI: Probabilistic Control and Coordination in Multi-Agent LLM Systems | 集成信念引导委托与反思驱动重路由，无需训练即可控制。 | 解决多代理 LLM 系统路由低效、反馈噪声及交互成本高问题。 | 多代理 LLM 协作系统 |
| 82 | http://arxiv.org/abs/2602.22365v1 | Sustainable Multi-Agent Crowdsourcing via Physics-Informed Bandits | 提出 Neural-Linear UCB 分配器融合物理信息协方差先验。 | 解决众包平台分配质量劳动力可持续性及战略行为张力问题。 | 多代理众包平台 |
| 83 | http://arxiv.org/abs/2602.22413v1 | Epistemic Filtering and Collective Hallucination: A Jury Theorem for Confidence-Calibrated Agents | 提出置信度校准代理的选择性参与投票框架 | 解决集体决策中代理盲目投票导致幻觉累积的问题 | 多Agent集体决策系统 |
| 84 | http://arxiv.org/abs/2602.22915v1 | Robust Information Design for Multi-Agent Systems with Complementarities: Smallest-Equilibrium Threshold Policies | 构造阈值规则实现稳健协调，避免福利膨胀 | 解决具有互补性的 MAS 中稳健协调策略设计问题 | 多Agent 系统信息设计 |
| 85 | http://arxiv.org/abs/2602.23005v1 | Managing Uncertainty in LLM-based Multi-Agent System Operation | 提出基于生命周期的不确定性管理框架 | 解决安全关键领域中系统级不确定性传播问题 | 多Agent 系统运维 |
| 86 | http://arxiv.org/abs/2602.23258v1 | AgentDropoutV2: Optimizing Information Flow in Multi-Agent Systems via Test-Time Rectify-or-Reject Pruning | 提出测试时修正或拒绝剪枝框架，动态优化多智能体系统信息流，无需重训练。 | 解决多智能体系统中个体错误信息级联影响导致性能下降的问题。 | 复杂推理多智能体系统 |
| 87 | http://arxiv.org/abs/2602.23864v1 | RUMAD: Reinforcement-Unifying Multi-Agent Debate | 将动态通信拓扑控制 formulat 为 RL 问题，动态调整通信图边权重。 | 解决现有辩论系统难以同时优化准确性、共识形成及计算效率的问题。 | 多智能体推理辩论 |
| 88 | http://arxiv.org/abs/2602.24074v1 | Sharing is caring: data sharing in multi-agent supply chains | 提出多智能体系统，工厂代理可下游共享信息，结合合作奖励塑造提升性能。 | 解决供应链网络中代理完全可观察假设不现实及数据共享策略问题。 | 多智能体供应链优化 |
| 89 | http://arxiv.org/abs/2603.00267v1 | "Multi-Sourced, Multi-Agent Evidence Retrieval for Fact-Checking" | 提出 WKGFC，利用授权开放知识图为核心资源，LLM 启用检索评估主张。 | 解决现有方法依赖文本相似性难以检索捕捉多跳语义关系证据的问题。 | 事实核查与证据检索 |
| 90 | http://arxiv.org/abs/2603.00309v1 | DIG to Heal: Scaling General-purpose Agent Collaboration via Explainable Dynamic Decision Paths | 引入动态交互图，捕捉 emergent 协作为时变因果网络，实现错误模式实时识别。 | 解决无结构交互导致冗余工作及级联失败难以解释或纠正的问题。 | 通用 LLM 代理协作 |
| 91 | http://arxiv.org/abs/2603.00808v1 | MetaMind: General and Cognitive World Models in Multi-Agent Systems by Meta-Theory of Mind | 提出 MetaMind，利用元理论心智框架，代理学习预测规划自身信念及逆向推理目标。 | 解决多智能体系统世界模型理解 interdependent 代理动力学及无集中监督规划难的问题。 | 多智能体系统世界模型 |

[返回目录](#目录)

<a id="cat-02"></a>

## 基于Agent的应用系统

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2602.00953v1 | SAGE: Agentic Framework for Interpretable and Clinically Translatable Computational Pathology Biomarker Discovery | 整合文献锚定推理与多模态数据分析的专业Agent系统 | AI病理模型黑盒化，缺乏生物学验证与临床可解释性 | 计算病理学生物标志物发现 |
| 2 | http://arxiv.org/abs/2602.01078v1 | AutoHealth: An Uncertainty-Aware Multi-Agent System for Autonomous Health Data Modeling | 五Agent闭环协调实现健康数据自主建模与不确定性评估 | 现有系统泛化差、依赖预定义模板、忽视不确定性估计 | 医疗健康数据自主建模 |
| 3 | http://arxiv.org/abs/2602.01086v1 | MedBeads: An Agent-Native, Immutable Data Substrate for Trustworthy Medical AI | 基于Merkle DAG的不可变临床事件"珠链"数据架构 | EMR为人类设计导致AI接收碎片化数据引发幻觉与审计困难 | 可信医疗AI数据基础设施 |
| 4 | http://arxiv.org/abs/2602.01155v2 | Multi-Agent Causal Reasoning System for Error Pattern Rule Automation in Vehicles | CAREP系统自动化从DTC事件序列生成错误模式布尔规则 | 车辆错误模式规则手工 crafting成本高且易出错 | 汽车故障诊断规则自动化 |
| 5 | http://arxiv.org/abs/2602.01271v1 | From Intents to Actions: Agentic AI in Autonomous Networks | 三Agent系统实现电信网络意图到控制动作的自主转换 | 启发式方法无法将高层意图转换为底层执行器命令 | 电信网络自主运营 |
| 6 | http://arxiv.org/abs/2602.01317v5 | TxRay: Agentic Postmortem of Live Blockchain Attacks | 从种子交易重建攻击生命周期并生成可执行PoC的Agent系统 | DeFi攻击事后分析缓慢手工且证据有限 | 区块链安全攻击分析 |
| 7 | http://arxiv.org/abs/2603.06587v1 | Autonomous AI Agents for Option Hedging: Enhancing Financial Stability through Shortfall Aware Reinforcement Learning | shortfall感知RL框架优先下行敏感对冲目标 | 静态模型校准与实现对冲结果间存在实践差距 | 衍生品市场自主对冲 |
| 8 | http://arxiv.org/abs/2602.01443v1 | SimGym: Traffic-Grounded Browser Agents for Offline A/B Testing in E-Commerce | 基于生产数据提取买家原型并模拟队列加权会话 | A/B测试分流流量耗时长且可能损害用户体验 | 电商UI变更离线测试 |
| 9 | http://arxiv.org/abs/2602.02961v1 | Generative Engine Optimization: A VLM and Agent Framework for Pinterest Acquisition Growth | VLM预测用户搜索词+AI代理挖掘趋势，构建语义集合页 | 视觉内容平台在生成式搜索时代获客困难 | Pinterest等视觉内容平台 |
| 10 | http://arxiv.org/abs/2602.03069v1 | Skill-Based Autonomous Agents for Material Creep Database Construction | 技能型架构协调语义过滤/多模态提取/物理验证 | 历史实验数据锁在非结构化文献中难以人工策展 | 材料科学蠕变数据库构建 |
| 11 | http://arxiv.org/abs/2602.18451v1 | Developing a Multi-Agent System to Generate Next Generation Science Assessments with Evidence-Centered Design | 集成ECD框架到MAS，多LLM集成自动化评估项目生成 | NGSS评估开发需要多样 expertise且成本高 | 下一代科学标准评估生成 |
| 12 | http://arxiv.org/abs/2602.07034v1 | ST-Raptor: An Agentic System for Semi-Structured Table QA | 交互分析环境结合视觉编辑+树结构建模+Agent驱动查询 | 半结构化表格QA需要精确提取和恢复隐式逻辑结构 | 半结构化表格问答 |
| 13 | http://arxiv.org/abs/2602.03285v1 | MeetBench-XL: Calibrated Multi-Dimensional Evaluation and Learned Dual-Policy Agents for Real-Time Meetings | MeetAll数据集+MeetBench-XL评估+MeetMaster XL双策略Agent | 现有会议基准简化，无法反映真实企业工作流 | 企业会议AI助手 |
| 14 | http://arxiv.org/abs/2602.03320v1 | MedSAM-Agent: Empowering Interactive Medical Image Segmentation with Multi-turn Agentic Reinforcement Learning | 混合提示策略生成专家轨迹+两阶段训练整合多轮结果验证 | 现有方法依赖单轮刚性交互策略，缺乏过程级监督 | 多模态医学图像分割（6模态21数据集） |
| 15 | http://arxiv.org/abs/2602.02048v1 | Are Semantic Networks Associated with Idea Originality in Artificial Creativity? A Comparison with Human Agents | 探究 LLM 语义网络组织与创意原创性的关系 | 比较 AI 与人类在创造力支持工具中的表现差异 | 创造力支持工具设计 |
| 16 | http://arxiv.org/abs/2602.02270v1 | dziribot: rag based intelligent conversational agent for algerian arabic dialect | 混合架构集成 NLU 与 RAG 的阿尔及利亚方言机器人 | 解决方言非标准化 orthography 与代码切换问题 | 阿尔及利亚客户服务 |
| 17 | http://arxiv.org/abs/2602.02660v2 | MARS: Modular Agent with Reflective Search for Automated AI Research | 预算感知规划与模块化构建的自动化 AI 研究框架 | 解决 AI 研究中评估昂贵与性能归因不透明问题 | 自动化 AI 科学研究 |
| 18 | http://arxiv.org/abs/2602.02849v1 | AutoSizer: Automatic Sizing of Analog and Mixed-Signal Circuits via Large Language Model (LLM) Agents | 反射性 LLM 驱动元优化框架，统一电路理解与优化 | 解决 AMS 电路设计中晶体管 sizing 瓶颈问题 | 模拟与混合信号电路设计 |
| 19 | http://arxiv.org/abs/2602.03798v1 | FullStack-Agent: Enhancing Agentic Full-Stack Web Coding via Development-Oriented Testing and Repository Back-Translation | 统一全栈代理系统，开发导向测试 | 仅生成前端缺乏全栈数据处理 | 全栈 Web 开发 |
| 20 | http://arxiv.org/abs/2602.04058v1 | RareCollab -- An Agentic System Diagnosing Mendelian Disorders with Integrated Phenotypic and Molecular Evidence | 代理诊断框架，整合多模态证据 | 罕见病分子诊断率低，诊断旅程长 | 医疗/罕见病诊断 |
| 21 | http://arxiv.org/abs/2602.04071v1 | Agentic AI-Empowered Dynamic Survey Framework | 动态调查框架，持续更新现有综述 | 综述论文因研究增长迅速过时 | 学术综述维护 |
| 22 | http://arxiv.org/abs/2602.04112v1 | DELTA: Deliberative Multi-Agent Reasoning with Reinforcement Learning for Multimodal Psychological Counseling | 审议多代理框架，多模态信号推理 | 现有咨询系统仅基于文本缺乏共情 | 心理 counseling/医疗 |
| 23 | http://arxiv.org/abs/2602.04445v1 | AgenticAKM : Enroute to Agentic Architecture Knowledge Management | 代理方法用于架构知识管理，分解子任务 | 架构知识管理劳动密集且未被采用 | 软件工程/架构管理 |
| 24 | http://arxiv.org/abs/2602.04510v1 | OSCAgent: Accelerating the Discovery of Organic Solar Cells with LLM Agents | 多代理框架，统一检索增强设计与评估 | 有机太阳能电池材料发现耗时 costly | 科学发现/材料科学 |
| 25 | http://arxiv.org/abs/2602.04726v1 | Supporting software engineering tasks with agentic AI: Demonstration on document retrieval and test scenario generation | 代理 AI 解决方案，测试场景生成与文档检索 | 软件开发模型需要重新工具化 | 软件工程任务 |
| 26 | http://arxiv.org/abs/2602.04813v1 | Agentic AI in Healthcare & Medicine: A Seven-Dimensional Taxonomy for Empirical Evaluation of LLM-based Agents | 七维分类法，实证评估医疗 LLM 代理 | 医疗工作缺乏共同框架 | 医疗/代理评估 |
| 27 | http://arxiv.org/abs/2602.04849v1 | El Agente Estructural: An Artificially Intelligent Molecular Editor | 多模态自然语言驱动几何生成编辑代理 | 分子生成编辑缺乏精确控制 | 化学/分子建模 |
| 28 | http://arxiv.org/abs/2602.04850v1 | El Agente Quntur: A research collaborator agent for quantum chemistry | 分层多代理 AI 系统，量子化学研究协作 | 量子化学模拟应用门槛高 | 量子化学研究 |
| 29 | http://arxiv.org/abs/2602.07371v1 | DeepPrep: An LLM-Powered Agentic System for Autonomous Data Preparation | 树状Agent推理+执行反馈迭代构建数据准备流水线 | 数据准备依赖线性交互，难以修正早期决策 | 数据科学中的异构噪声表格处理 |
| 30 | http://arxiv.org/abs/2602.07408v1 | Progressive Multi-Agent Reasoning for Biological Perturbation Prediction | 多Agent框架整合难度感知任务排序与迭代知识 refinement | 高维扰动结果纠缠，LLM难以推理生物因果性 | 药物发现中的批量细胞化学扰动预测 |
| 31 | http://arxiv.org/abs/2602.07491v1 | GraphAgents: Knowledge Graph-Guided Agentic AI for Cross-Domain Materials Design | 知识图谱引导的多Agent框架，跨领域连接信息 | 材料科学需整合分子化学到机械性能的多源信息 | PFAS化学品可持续替代品设计 |
| 32 | http://arxiv.org/abs/2602.07900v1 | Rethinking the Value of Agent-Generated Tests for LLM-Based Software Engineering Agents | 实证分析Agent写测试的价值，发现边际效用 | Agent写测试是否真正改善问题解决尚不明确 | LLM基于软件工程的仓库级问题修复 |
| 33 | http://arxiv.org/abs/2602.07943v1 | IV Co-Scientist: Multi-Agent LLM Framework for Causal Instrumental Variable Discovery | 多Agent系统提出、批评、 refinement 工具变量 | 识别有效工具变量需要跨学科知识和创造力 | 观察性数据库中的因果推断 |
| 34 | http://arxiv.org/abs/2602.07983v1 | Accelerating Social Science Research via Agentic Hypothesization and Experimentation | EXPERIGEN框架两阶段搜索生成和评估假设 | 数据驱动社会科学研究依赖迭代周期速度慢 | 社会科学研究的端到端发现 |
| 35 | http://arxiv.org/abs/2602.08013v1 | Small Agent Group is the Future of Digital Health | 小Agent组SAG分布式推理替代单一巨型模型 | 临床决策需效果、可靠性、部署成本平衡 | 数字健康临床决策支持 |
| 36 | http://arxiv.org/abs/2602.13290v1 | AGORA: Agentic Green Orchestration Architecture for Beyond 5G Networks | 本地工具增强LLM Agent嵌入网络控制循环翻译可持续性目标 | 复杂移动网络系统管理缺乏实用可扩展机制 | Beyond 5G网络能源感知流量调度 |
| 37 | http://arxiv.org/abs/2602.06085v1 | LAAFD: LLM-based Agents for Accelerated FPGA Design | 利用 LLM 代理工作流将 C++ 转化为优化 Vitis HLS 内核，自动化关键变换。 | 解决 FPGA 加速采用受限于专用硬件专业知识的问题。 | FPGA 加速设计 |
| 38 | http://arxiv.org/abs/2602.05524v1 | AI Agent Systems for Supply Chains: Structured Decision Prompts and Memory Retrieval | 研究基于 LLM 的多代理系统用于库存管理，提出利用历史经验的 AIM-RM 代理。 | 解决 LLM 多代理系统能否一致推导最优订货策略并适应多样供应链场景不明确的问题。 | 供应链库存管理 |
| 39 | http://arxiv.org/abs/2602.06097v1 | Agentic Workflow Using RBA$_θ$ for Event Prediction | 提出事件优先、频率感知预测范式，动态选择专门工作流基于操作上下文。 | 解决风电爬坡事件因强变异性、多尺度动力学难以预测的问题。 | 风电功率预测 |
| 40 | http://arxiv.org/abs/2602.05945v2 | AgenticTagger: Structured Item Representation for Recommendation with LLM Agents | 提出框架查询 LLM 生成物品文本描述符，通过多代理反思机制构建词汇。 | 解决开放生成导致描述符基数高、性能低，使下游建模挑战的问题。 | 推荐系统 |
| 41 | http://arxiv.org/abs/2602.06232v1 | RuleSmith: Multi-Agent LLMs for Automated Game Balancing | 耦合游戏引擎与多 Agent LLM 自博弈，结合贝叶斯优化自动平衡游戏。 | 解决游戏平衡依赖人工测试和专家直觉的问题。 | 游戏开发与平衡 |
| 42 | http://arxiv.org/abs/2602.06325v1 | Identifying Adversary Tactics and Techniques in Malware Binaries with an LLM Agent | 提出 TTPDetect，结合密集检索与 LLM 分析识别恶意软件 TTPs。 | 解决 stripped 二进制文件中 TTP 归因困难的问题。 | 网络安全分析 |
| 43 | http://arxiv.org/abs/2602.18460v1 | The Doctor Will (Still) See You Now: On the Structural Limits of Agentic AI in Healthcare | 定性研究医疗 Agent 的结构限制，识别概念碎片化与自主性矛盾。 | 解决医疗 Agent 商业承诺与 operational 现实不符的问题。 | 医疗健康领域 |
| 44 | http://arxiv.org/abs/2602.18461v1 | Toward Self-Driving Universities: Can Universities Drive Themselves with Agentic AI? | 提出高校自主化框架，利用 Agentic AI 自动化行政与学术流程。 | 解决高校官僚过载和信息系统碎片化的问题。 | 高等教育管理 |
| 45 | http://arxiv.org/abs/2603.08716v1 | Design Conductor: An agent autonomously builds a 1.5 GHz Linux-capable RISC-V CPU | Design Conductor 自主完成从 spec 到 GDSII 的 CPU 构建。 | 解决半导体设计端到端自动化程度低的问题。 | 芯片设计与制造 |
| 46 | http://arxiv.org/abs/2602.07215v1 | Multi-Agentic AI for Fairness-Aware and Accelerated Multi-modal Large Model Inference in Real-world Mobile Edge Networks | 提出多 Agent 框架优化 edge 网络中 LM 推理的 latency 和 fairness。 | 解决 edge 网络中 heterogeneous LMs 资源需求和 orchestration 复杂问题。 | 移动边缘网络 |
| 47 | http://arxiv.org/abs/2602.07287v2 | Patch-to-PoC: A Systematic Study of Agentic LLM Systems for Linux Kernel N-Day Reproduction | 开发 K-Repro 系统，自动化 reproducing Linux kernel 漏洞 PoC。 | 解决 LLM 系统 autonomously 复现 kernel 漏洞缺乏系统研究的问题。 | 网络安全漏洞复现 |
| 48 | http://arxiv.org/abs/2602.11123v1 | From Natural Language to Materials Discovery:The Materials Knowledge Navigation Agent | 语言驱动系统，将科学意图转化为数据库检索等可执行动作 | 传统工作流依赖专家直觉和昂贵模拟 | 高性能材料发现 |
| 49 | http://arxiv.org/abs/2602.11689v1 | A Preliminary Assessment of Coding Agents for CFD Workflows | 轻量级配置引导智能体复用教程和 log 驱动 repair | 自动化端到端 CFD 工作流缺乏评估 | 开源 CFD 包 OpenFOAM 工作流 |
| 50 | http://arxiv.org/abs/2602.11724v1 | WebTestPilot: Agentic End-to-End Web Testing against Natural Language Specification by Inferring Oracles with Symbolized GUI Elements | 符号化关键 GUI 元素，翻译自然语言规范为带推断条件的步骤 | 隐式 oracle 推断挑战和概率推理挑战 | 端到端 Web 测试智能体 |
| 51 | http://arxiv.org/abs/2602.15909v3 | Resp-Agent: An Agent-Based System for Multimodal Respiratory Sound Generation and Disease Diagnosis | 主动对抗课程Agent控制器闭环调度针对性合成 | 呼吸听诊信息丢失、数据有限、类别不平衡 | 呼吸系统疾病诊断 |
| 52 | http://arxiv.org/abs/2602.15019v2 | Hunt Globally: Wide Search AI Agents for Drug Asset Scouting in Investing, Business Development, and Competitive Intelligence | 树状自学习Bioptic Agent实现完整无幻觉药物资产侦察 | Deep Research Agent在多语言异构源召回率落后人类专家 | 生物医药投资情报 |
| 53 | http://arxiv.org/abs/2602.15219v1 | Multi-Agent Home Energy Management Assistant | 三专用Agent（分析、知识、控制）自适应处理HEMS用例 | 家庭能源管理复杂， prior研究依赖提示工程或预建平台 | 家庭能源管理系统 |
| 54 | http://arxiv.org/abs/2602.15325v1 | AgriWorld:A World Tools Protocol Framework for Verifiable Agricultural Reasoning with Code-Executing LLM Agents | Python执行环境+多轮LLM Agent执行-观察- refine循环 | 农业基础模型缺乏语言推理，LLM无法直接推理高维农业数据 | 农业科学推理 |
| 55 | http://arxiv.org/abs/2602.08561v2 | Automating Computational Reproducibility in Social Science: Comparing Prompt-Based and Agent-Based Approaches | 评估 Agent 自动诊断与修复计算研究复现失败的能力。 | 解决计算研究复现中因环境配置导致的失败问题。 | 社会科学计算复现 |
| 56 | http://arxiv.org/abs/2602.08949v1 | Digital Twin and Agentic AI for Wild Fire Disaster Management: Intelligent Virtual Situation Room | 构建双向数字 twin 平台， augmented by 自主 AI 代理。 | 解决传统灾害管理框架无法实时适应 evolving 火情问题。 | wildfire 灾害管理 |
| 57 | http://arxiv.org/abs/2602.09084v2 | Agent Banana: High-Fidelity Image Editing with Agentic Thinking and Tooling | 提出分层代理规划执行框架，支持高保真图像编辑。 | 解决图像编辑中过度编辑、多轮一致性差及分辨率低问题。 | 专业级图像编辑 |
| 58 | http://arxiv.org/abs/2602.09132v1 | SciDataCopilot: An Agentic Data Preparation Framework for AGI-driven Scientific Discovery | 提出自主代理框架，处理数据摄入与多模态集成。 | 解决原始实验数据异构性阻碍 AGI 科学发现的问题。 | 科学数据准备 |
| 59 | http://arxiv.org/abs/2602.18479v1 | AgentCAT: An LLM Agent for Extracting and Analyzing Catalytic Reaction Data from Chemical Engineering Literature | 提出 AgentCAT，从化学工程论文提取分析催化反应数据。 | 解决化学工程领域长期存在的数据瓶颈与提取依赖结构复杂。 | 化学工程数据提取 |
| 60 | http://arxiv.org/abs/2603.08719v2 | SiliconMind-V1: Multi-Agent Distillation and Debug-Reasoning Workflows for Verilog Code Generation | 提出统一多智能体框架，生成推理导向训练数据与验证。 | 解决 Verilog 代码生成中功能正确性保证与成本隐私问题。 | Verilog 代码生成 |
| 61 | http://arxiv.org/abs/2603.00080v1 | From Static Repositories to Agentic Knowledge Webs: ResearchTwin and the S-Index for Federated Human-AI Research Discovery | 构建研究者数字 twin 及 S-index 指标，实现联邦化研究发现 | 解决科研成果分散、传统指标忽视代码数据贡献的问题 | 科研发现与知识合成 |
| 62 | http://arxiv.org/abs/2602.13713v2 | On Theoretically-Driven LLM Agents for Multi-Dimensional Discourse Analysis | 引入论证理论增强 RAG，量化理论知识的益处，提升修辞策略识别 | 解决 LLM 仅检测表面相似性而忽略话语改革修辞功能的问题 | 政治辩论话语分析 |
| 63 | http://arxiv.org/abs/2602.13868v1 | Agentic Assistant for 6G: Turn-based Conversations for AI-RAN Hierarchical Co-Management | 构建代理网络管理器与轮次对话助手，理解意图匹配分层问题 | 解决 AI-RAN 协同管理缺乏分层动态问题及实时人类交互接口问题 | 6G 无线接入网管理 |
| 64 | http://arxiv.org/abs/2602.13987v1 | ATTest: Agent-Driven Tensor Testing for Deep Learning Library Modules | 编排七阶段管道，包含约束提取及生成 - 验证 - 修复循环维持稳定性 | 解决深度学习库单元测试语义盲及 LLM 跨文件上下文不稳定问题 | 深度学习库模块测试 |
| 65 | http://arxiv.org/abs/2602.14158v1 | A Multi-Agent Framework for Medical AI: Leveraging Fine-Tuned GPT, LLaMA, and DeepSeek R1 for Evidence-Based and Bias-Aware Clinical Query Processing | 结合互补 LLM 与证据检索、不确定性估计及偏差检查提升可靠性 | 解决临床 QA 弱验证、证据 grounding 不足及置信度 signalling 不可靠问题 | 医疗问答系统 |
| 66 | http://arxiv.org/abs/2602.15631v1 | Meflex: A Multi-agent Scaffolding System for Entrepreneurial Ideation Iteration via Nonlinear Business Plan Writing | 集成非线性画布与多 Agent 支架，支持迭代式创业构思 | 解决传统商业计划写作僵化、认知负荷高的问题 | 创业教育学生与 novice 创业者 |
| 67 | http://arxiv.org/abs/2602.16379v1 | Label-Consistent Data Generation for Aspect-Based Sentiment Analysis Using LLM Agents | 利用 Agent 迭代生成与验证，产生高质量合成训练数据 | 解决 ABSA 任务中数据增强标签一致性差的问题 | 情感分析数据增强与 NLP |
| 68 | http://arxiv.org/abs/2602.16553v1 | Agentic AI, Medical Morality, and the Transformation of the Patient-Physician Relationship | 探讨 Agentic AI 如何重塑医患关系与医疗道德结构 | 解决 Agentic AI 部署前缺乏对医疗道德 fabric 转变的伦理关注 | 医疗健康领域与伦理设计 |
| 69 | http://arxiv.org/abs/2602.16554v1 | MerLean: An Agentic Framework for Autoformalization in Quantum Computation | 实现量子计算论文自动形式化为 Lean 代码的 Agentic 框架 | 解决前沿研究机器验证负担重且合成数据挖掘难的问题 | 量子计算与数学形式化验证 |
| 70 | http://arxiv.org/abs/2602.16812v1 | NeuDiff Agent: A Governed AI Workflow for Single-Crystal Neutron Crystallography | 构建受治理的 AI 工作流，自动化中子晶体学数据分析 | 解决大型设施中复杂样本分析报告 latency 限制 throughput 问题 | 科学设施晶体学数据分析 |
| 71 | http://arxiv.org/abs/2602.16953v2 | LLM4Cov: Execution-Aware Agentic Learning for High-coverage Testbench Generation | 离线智能体学习框架，利用执行验证数据生成高覆盖率测试台。 | 硬件验证中反馈昂贵缓慢，在线强化学习不实用的问题。 | 硬件验证 |
| 72 | http://arxiv.org/abs/2602.17067v1 | StoryLensEdu: Personalized Learning Report Generation through Narrative-Driven Multi-Agent Systems | 叙事驱动多智能体系统，自动生成直观互动学习报告。 | 现有学习报告可解释性差、呈现单调且缺乏解释力。 | 教育学习报告 |
| 73 | http://arxiv.org/abs/2602.17091v1 | What to Cut? Predicting Unnecessary Methods in Agentic Code Generation | 提出预测模型识别 PR 审查中可能被删除的函数。 | AI 生成代码量大，审查者需检查最终会被删除的代码。 | 代码审查 |
| 74 | http://arxiv.org/abs/2602.17096v1 | Agentic Wireless Communication for 6G: Intent-Aware and Continuously Evolving Physical-Layer Intelligence | 调查 6G 物理层的代理 AI，实现意图感知和自主决策。 | 规则驱动设计难以捕捉多维用户意图及环境动态变化。 | 6G 无线通信 |
| 75 | http://arxiv.org/abs/2602.17282v1 | Visual Insights into Agentic Optimization of Pervasive Stream Processing Services | 平台支持上下文感知自动扩展，代理优化服务执行。 | 边缘设备资源有限，服务执行需动态扩展以避免资源争夺。 | 流处理服务 |
| 76 | http://arxiv.org/abs/2603.12274v1 | DIALECTIC: A Multi-Agent System for Startup Evaluation | 基于 LLM 的多智能体系统，通过模拟辩论评估初创企业。 | 早期筛选受投资者带宽限制，需在尽职调查与数量间权衡。 | 风险投资评估 |
| 77 | http://arxiv.org/abs/2602.17308v1 | MedClarify: An information-seeking AI agent for medical diagnosis with case-specific follow-up questions | 信息寻求代理，生成后续问题以减少诊断不确定性。 | 医疗 LLM 缺乏生成信息性后续问题及推理鉴别诊断的能力。 | 医疗诊断 |
| 78 | http://arxiv.org/abs/2602.17518v1 | A Picture of Agentic Search | 开发收集代理检索增强系统数据的方法论及数据集。 | IR 系统基于人类假设，无法适应代理搜索行为的变化。 | 信息检索系统 |
| 79 | http://arxiv.org/abs/2602.17607v1 | AutoNumerics: An Autonomous, PDE-Agnostic Multi-Agent Pipeline for Scientific Computing | 多智能体框架，自主设计、实现及验证数值求解器。 | 设计准确数值求解器需要大量数学 expertise 和手动调整。 | 科学计算 PDE 求解 |
| 80 | http://arxiv.org/abs/2602.17622v1 | What Makes a Good LLM Agent for Real-world Penetration Testing? | 提出 Excalibur 代理，结合工具与难度感知规划。 | 代理缺乏实时任务难度估计，导致努力分配不当。 | 渗透测试 |
| 81 | http://arxiv.org/abs/2602.17665v2 | OpenEarthAgent: A Unified Framework for Tool-Augmented Geospatial Agents | 统一框架开发工具增强地理空间代理，基于卫星图像。 | 遥感领域推理需跨越空间尺度及多光谱指数，挑战大。 | 地理空间分析 |
| 82 | http://arxiv.org/abs/2602.17875v1 | MultiVer: Zero-Shot Multi-Agent Vulnerability Detection | 零样本多智能体系统，实现 SOTA 召回率的漏洞检测。 | 微调模型在安全应用中假阴性成本高于假阳性。 | 代码漏洞检测 |
| 83 | http://arxiv.org/abs/2602.17886v1 | El Agente Sólido: A New Age(nt) for Solid State Simulations | 分层多智能体框架，自动化固态量子化学工作流。 | 第一性原理方法使用受限于设计执行工作流的专业知识。 | 材料发现 |
| 84 | http://arxiv.org/abs/2602.17895v1 | The Strategic Gap: How AI-Driven Timing and Complexity Shape Investor Trust in the Age of Digital Agents | 多节点 AI 框架审计披露复杂性与 filing 不可预测性的交集。 | 投资者易受战略 timing 影响，掩盖结构性恶化。 | 金融市场监管 |
| 85 | http://arxiv.org/abs/2602.10163v1 | Beyond SMILES: Evaluating Agentic Systems for Drug Discovery | 评估药物发现代理系统在肽疗法等任务上的泛化能力，提出设计需求矩阵。 | 解决现有药物发现代理系统缺乏蛋白语言模型支持及多目标优化能力的问题。 | 药物发现 |
| 86 | http://arxiv.org/abs/2602.13312v1 | PeroMAS: A Multi-agent System of Perovskite Material Discovery | 构建钙钛矿材料发现多 Agent 系统，封装专用工具并通过 MCP 规划调用。 | 解决现有 AI 方法无法跨工作流传播物理约束， hindering 端到端优化的问题。 | 材料科学发现 |
| 87 | http://arxiv.org/abs/2602.09829v2 | Internalizing Multi-Agent Reasoning for Accurate and Efficient LLM-based Recommendation | 设计多 Agent 教师系统内部化推理能力至单 Agent 推荐模型，消除迭代延迟。 | 解决推荐系统中集成 LLM 推理能力与协同信号时 inference 延迟高的问题。 | 推荐系统 |
| 88 | http://arxiv.org/abs/2602.09945v1 | Closing Reasoning Gaps in Clinical Agents with Differential Reasoning Learning | 提出微分推理学习框架，从推理差异中学习以提升临床 Agent 推理 fidelity。 | 解决临床决策支持中推理无效问题，提升最终答案准确性及推理忠实度。 | 临床决策支持 |
| 89 | http://arxiv.org/abs/2602.10218v1 | ACE-RTL: When Agentic Context Evolution Meets RTL-Specialized LLMs | 统一领域适配 RTL 模型与前沿推理 LLM，通过 Agentic Context Evolution 迭代优化。 | 解决 RTL 代码生成中单一方法弱点，提升功能正确性及减少迭代次数。 | 硬件设计自动化 |
| 90 | http://arxiv.org/abs/2602.10490v1 | ChainRec: An Agentic Recommender Learning to Route Tool Chains for Diverse and Evolving Interests | 提出 ChainRec，使用 planner 动态选择推理工具链以适应多样及演变兴趣。 | 解决现有推荐方法依赖固定工作流无法适应冷启动及兴趣shift的问题。 | 推荐系统 |
| 91 | http://arxiv.org/abs/2602.16720v1 | APEX-SQL: Talking to the data via Agentic Exploration for Text-to-SQL | 提出 APEX-SQL，通过假设验证循环将模型推理接地于真实数据。 | 解决 Text-to-SQL 依赖静态 schema 无法解决语义歧义及扩展到大库问题。 | 企业 Text-to-SQL |
| 92 | http://arxiv.org/abs/2602.17999v1 | Aurora: Neuro-Symbolic AI Driven Advising Agent | 结合 RAG、符号推理与课程数据库的神经符号 advising agent | 解决高校学术 advising 资源短缺及建议不可验证问题 | 高等教育学术 advising |
| 93 | http://arxiv.org/abs/2602.18571v1 | Debug2Fix: Supercharging Coding Agents with Interactive Debugging Capabilities | 将交互式调试器集成到编码 Agent 子架构中，提升修复能力 | 解决编码 Agent 缺乏运行时调试信息及依赖试错问题 | 软件工程 bug 修复 |
| 94 | http://arxiv.org/abs/2602.18640v1 | Decoding ML Decision: An Agentic Reasoning Framework for Large-Scale Ranking System | 提出 GEARS 框架，将排序优化重构为自主发现过程 | 解决工程语境约束导致排序系统假设翻译困难问题 | 大规模排序系统 |
| 95 | http://arxiv.org/abs/2602.18650v1 | NutriOrion: A Hierarchical Multi-Agent Framework for Personalized Nutrition Intervention Grounded in Clinical Guidelines | 层次化多智能体框架，并行 - 顺序推理拓扑用于个性化营养干预 | 解决多病种患者营养规划中上下文过载及冲突需求问题 | 多病种患者营养干预 |
| 96 | http://arxiv.org/abs/2602.18773v1 | LAMMI-Pathology: A Tool-Centric Bottom-Up LVLM-Agent Framework for Molecularly Informed Medical Intelligence in Pathology | 工具中心化 LVLM-Agent 框架，用于分子信息病理医学智能 | 解决病理图像分析缺乏证据驱动及分子验证问题 | 病理医学图像分析 |
| 97 | http://arxiv.org/abs/2602.18824v1 | UniRank: A Multi-Agent Calibration Pipeline for Estimating University Rankings from Anonymized Bibliometric Signals | 多智能体 LLM 流水线，仅用匿名文献计量信号估算大学排名 | 解决大学排名估算依赖私有数据及模型记忆混淆问题 | 大学排名估算 |
| 98 | http://arxiv.org/abs/2602.21251v1 | AgenticTyper: Automated Typing of Legacy Software Projects Using Agentic AI | 基于 LLM 的 agentic 系统，通过迭代纠错为遗留 JS 项目添加类型 | 解决手动添加 TypeScript 类型成本高及行为正确性难保问题 | 遗留 JavaScript 项目 |
| 99 | http://arxiv.org/abs/2602.19303v1 | The Path to Conversational AI Tutors: Integrating Tutoring Best Practices and Targeted Technologies to Produce Scalable AI Agents | 综合人类辅导与 ITS 经验，指导可扩展对话 AI 辅导系统设计 | 解决生成式 AI 辅导系统缺乏 pedagogical 有效性及整合问题 | 对话式 AI 辅导系统 |
| 100 | http://arxiv.org/abs/2602.19387v1 | AI Agents for Variational Quantum Circuit Design | 自主 Agent 框架，集成高层推理与量子仿真环境设计 VQC | 解决变分量子电路架构空间组合爆炸及手动设计低效问题 | 变分量子电路设计 |
| 101 | http://arxiv.org/abs/2602.19439v2 | OptiRepair: Closed-Loop Diagnosis and Repair of Supply Chain Optimization Models with LLM Agents | 闭环诊断与修复供应链优化模型，结合领域无关与特定验证 | 解决供应链模型不可行诊断修复依赖稀缺 OR 专家问题 | 供应链优化模型 |
| 102 | http://arxiv.org/abs/2602.19502v1 | Human-Guided Agentic AI for Multimodal Clinical Prediction: Lessons from the AgentDS Healthcare Benchmark | 人类指导的智能体工作流，结合多模态特征工程提升临床预测性能 | 解决纯自动化方法在临床预测任务中缺乏领域专家知识的问题 | 医疗健康/临床预测 |
| 103 | http://arxiv.org/abs/2602.20144v1 | Agentic AI for Scalable and Robust Optical Systems Control | 基于 MCP 构建智能体框架，解释自然语言任务执行光设备控制 | 解决异构光学系统自主控制与编排的可扩展性与鲁棒性问题 | 光学系统控制 |
| 104 | http://arxiv.org/abs/2602.20543v1 | Beyond Human Performance: A Vision-Language Multi-Agent Approach for Quality Control in Pharmaceutical Manufacturing | 结合 DL 与 VLM 多智能体框架，自动记录或路由专家审查菌落计数 | 解决制药制造中手动计数易错及 DL 对异常样本性能退化问题 | 制药质量控制 |
| 105 | http://arxiv.org/abs/2602.20669v1 | Autonomous Laboratory Agent via Customized Domain-Specific Language Model and Modular AI Interface | 集成概率推理与确定性执行层，分离意图解释与命令验证 | 解决科学仪器自主控制中安全关键环境可靠性保障问题 | 自主实验室 |
| 106 | http://arxiv.org/abs/2602.20683v1 | Grid-Mind: An LLM-Orchestrated Multi-Fidelity Agent for Automated Connection Impact Assessment | 领域专用 LLM 智能体，编排多保真电力系统仿真执行 CIA 研究 | 解决电力系统操作中 LLM 应用缺乏仿真 grounded 决策支持问题 | 电力系统运营 |
| 107 | http://arxiv.org/abs/2603.08736v1 | Autonomous Edge-Deployed AI Agents for Electric Vehicle Charging Infrastructure Management | 部署领域专用 AI 代理于边缘，含置信度校准自主修复机制。 | 解决公共电动车充电设施高故障率及云架构延迟问题。 | 电动车充电基础设施 |
| 108 | http://arxiv.org/abs/2602.21394v2 | MemoPhishAgent: Memory-Augmented Multi-Modal LLM Agent for Phishing URL Detection | 动态编排钓鱼专用工具，利用 episodic 记忆指导决策。 | 解决传统钓鱼检测滞后及现有 LLM 系统推理能力利用不足问题。 | 钓鱼 URL 检测 |
| 109 | http://arxiv.org/abs/2603.18018v1 | An Agentic System for Schema Aware NL2SQL Generation | 策略性使用小语言模型为主代理，含选择性 LLM 回退机制。 | 解决 NL2SQL 任务中 LLM 计算开销大及资源受限部署问题。 | 关系数据库交互 |
| 110 | http://arxiv.org/abs/2602.21517v1 | Which Tool Response Should I Trust? Tool-Expertise-Aware Chest X-ray Agent with Multimodal Agentic Learning | 代理与工具交互实证学习其在多模态查询中的实际可信度。 | 解决医疗工具 inherently 易错及现有研究缺乏工具可靠性理解问题。 | 胸部 X 光分析 |
| 111 | http://arxiv.org/abs/2602.21533v1 | Reasoning-Driven Design of Single Atom Catalysts via a Multi-Agent Large Language Model Framework | 多 LLM 代理协作迭代推理、提出修改、反思结果及积累设计史。 | 解决传统机器学习缺乏推理能力及化学洞察生成问题。 | 单原子催化剂设计 |
| 112 | http://arxiv.org/abs/2602.21634v1 | AgentLTV: An Agent-Based Unified Search-and-Evolution Framework for Automated Lifetime Value Prediction | 代理生成运行修复 pipeline，两阶段搜索协调建模选择。 | 解决 LTV 数据模式多变导致构建复杂场景特定 pipeline 昂贵问题。 | 广告与电商 LTV 预测 |
| 113 | http://arxiv.org/abs/2602.22124v1 | SWE-Protégé: Learning to Selectively Collaborate With an Expert Unlocks Small Language Models as Software Engineering Agents | SLM 学习选择性寻求指导识别停滞状态，结合 SFT 与 RL。 | 解决 SLM 在长程软件工程任务中动作循环及低分辨率率问题。 | 软件工程修复任务 |
| 114 | http://arxiv.org/abs/2602.22425v1 | ArchAgent: Agentic AI-driven Computer Architecture Discovery | 基于AlphaEvolve自动设计缓存替换策略 | 解决硬件架构设计依赖人工迭代，效率低的问题 | 计算机体系结构发现 |
| 115 | http://arxiv.org/abs/2602.22529v1 | Generative Agents Navigating Digital Libraries | 引入Agent4DL模拟数字图书馆用户搜索行为 | 解决数字图书馆研究缺乏公开用户行为数据集的问题 | 数字图书馆用户模拟 |
| 116 | http://arxiv.org/abs/2602.22539v1 | Agentic AI for Intent-driven Optimization in Cell-free O-RAN | 提出多代理协作框架翻译并优化运营商意图 | 解决O-RAN中复杂意图需多代理协调未探索的问题 | 无线接入网络优化 |
| 117 | http://arxiv.org/abs/2602.22696v1 | Enhancing Persuasive Dialogue Agents by Synthesizing Cross-Disciplinary Communication Strategies | 融合社会心理学等跨学科策略设计说服代理 | 解决预定义策略无法捕捉真实交互复杂性的问题 | 说服性对话系统 |
| 118 | http://arxiv.org/abs/2602.22764v1 | Evaluating and Improving Automated Repository-Level Rust Issue Resolution with LLM-based Agents | 提出 RUSTFORGER 集成测试环境与动态追踪策略 | 解决 Rust 生态缺乏仓库级基准及类型语义理解难问题 | 软件工程_issue 解决 |
| 119 | http://arxiv.org/abs/2602.22809v2 | PhotoAgent: Agentic Photo Editing with Exploratory Visual Aesthetic Planning | 将图像编辑 formulated 为长程决策问题，显式美学规划 | 解决指令编辑依赖用户分解任务负担重的问题 | 自主图像编辑系统 |
| 120 | http://arxiv.org/abs/2602.22839v1 | DeepPresenter: Environment-Grounded Reflection for Agentic Presentation Generation | 基于环境感知工件状态进行反思与迭代修正 | 解决演示生成依赖预定义工作流缺乏灵活性问题 | 演示文稿生成代理 |
| 121 | http://arxiv.org/abs/2602.22959v1 | Can Agents Distinguish Visually Hard-to-Separate Diseases in a Zero-Shot Setting? A Pilot Study | 引入基于对比裁决的多代理框架提升诊断性能 | 解决零样本下视觉混淆疾病区分难的问题 | 医疗影像诊断代理 |
| 122 | http://arxiv.org/abs/2602.22963v1 | FactGuard: Agentic Video Misinformation Detection via Reinforcement Learning | formulate 验证为迭代推理过程，选择性调用工具 | 解决视频虚假信息检测依赖固定深度推理信任假设问题 | 视频虚假信息检测 |
| 123 | http://arxiv.org/abs/2602.23075v1 | CiteLLM: An Agentic Platform for Trustworthy Scientific Reference Discovery | 嵌入 LaTeX 编辑器，动态路由可信学术库 | 解决 AI 辅助科研中内容可信度与学术诚信问题 | 科学参考发现平台 |
| 124 | http://arxiv.org/abs/2602.23123v1 | Multi-Agent Large Language Model Based Emotional Detoxification Through Personalized Intensity Control for Consumer Protection | 四代理系统量化并调整文本情感刺激强度 | 解决注意力经济中感官内容阻碍消费者冷静决策问题 | 消费者信息保护 |
| 125 | http://arxiv.org/abs/2602.23276v1 | CXReasonAgent: Evidence-Grounded Diagnostic Reasoning Agent for Chest X-rays | 集成 LLM 与临床诊断工具，利用图像衍生证据进行基于证据的诊断推理。 | 解决 LVLM 生成响应缺乏诊断证据支持且难以验证可靠性的问题。 | 胸部 X 光临床诊断 |
| 126 | http://arxiv.org/abs/2602.23330v1 | Toward Expert Investment Teams:A Multi-Agent LLM System with Fine-Grained Trading Tasks | 将投资分析分解为细粒度任务，多智能体协作 mimicking 分析师与经理角色。 | 解决传统粗粒度指令忽略真实工作流细节导致推理性能下降的问题。 | 金融交易与投资分析 |
| 127 | http://arxiv.org/abs/2602.23481v1 | IDP Accelerator: Agentic Document Intelligence from Extraction to Compliance Validation | 提出 IDP 加速器框架，包含文档分割、提取、分析、验证四模块，实现端到端文档智能。 | 解决传统流水线难以处理多文档包、复杂推理及严格合规要求的问题。 | 工业文档处理与合规 |
| 128 | http://arxiv.org/abs/2602.23556v1 | Rudder: Steering Prefetching in Distributed GNN Training using LLM Agents | 嵌入软件模块 Rudder，利用 LLM 代理自主预取远程节点，最小化通信。 | 解决大规模 GNN 训练中因不规则通信导致的前向进度停滞问题。 | 分布式 GNN 训练系统 |
| 129 | http://arxiv.org/abs/2602.23577v1 | Multi-Agent Causal Reasoning for Suicide Ideation Detection Through Online Conversations | 提出多智能体因果推理框架，协作运用推理与偏差感知决策智能体检测自杀意念。 | 解决现有方法依赖预定义规则且忽略隐藏影响如用户从众行为的问题。 | 在线对话自杀风险检测 |
| 130 | http://arxiv.org/abs/2602.23623v1 | Toward E2E Intelligence in 6G Networks: An AI Agent-Based RAN-CN Converged Intelligence Framework | 提出基于 LLM 与 ReAct 的 RAN-CN 融合智能框架，动态查询解释网络数据生成决策。 | 解决任务特定 AI 模型泛化有限及跨域决策碎片化的问题。 | 6G 网络智能控制 |
| 131 | http://arxiv.org/abs/2602.23647v1 | SGAgent: Suggestion-Guided LLM-Based Multi-Agent Framework for Repository-Level Software Repair | 提出建议引导的多智能体框架，遵循定位 - 建议 - 修复范式，增强上下文感知。 | 解决现有方法从定位直接跳到修复存在根本推理缺口的问题。 | 仓库级软件修复 |
| 132 | http://arxiv.org/abs/2602.23716v1 | ProductResearch: Training E-Commerce Deep Research Agents via Multi-Agent Synthetic Trajectory Distillation | 利用多智能体合成高保真轨迹，通过反思内化过程蒸馏为单角色训练样本。 | 解决电商购物代理缺乏交互深度及上下文广度的问题。 | 电商对话式购物代理 |
| 133 | http://arxiv.org/abs/2602.23761v1 | OPTIAGENT: A Physics-Driven Agentic Framework for Automated Optical Design | 提出物理驱动代理框架，利用 DrGRPO 与光学词典奖励对齐光学原理。 | 解决光学设计依赖人类启发式知识及 LLM 利用知识能力受限的问题。 | 自动化光学设计 |
| 134 | http://arxiv.org/abs/2603.00200v1 | LiaisonAgent: An Multi-Agent Framework for Autonomous Risk Investigation and Governance | 集成 specialized 子代理执行端到端调查工作流，结合确定性工作流与自主推理。 | 解决传统规则系统生成大量缺乏组织上下文的技术警报导致分析师疲劳的问题。 | 安全风险调查与治理 |
| 135 | http://arxiv.org/abs/2602.23899v1 | Experience-Guided Self-Adaptive Cascaded Agents for Breast Cancer Screening and Diagnosis with Reduced Biopsy Referrals | 提出经验引导级联多智能体框架，检索相似历史病例条件化当前决策策略。 | 解决诊断升级及不必要的活检转诊过多的问题。 | 乳腺癌超声筛查与诊断 |
| 136 | http://arxiv.org/abs/2602.24068v1 | A Novel Hierarchical Multi-Agent System for Payments Using LLMs | 提出分层多智能体系统，包含对话、监督、路由、总结四级代理，实现端到端支付。 | 解决现有代理方案难以实现端到端代理支付工作流的问题。 | 支付工作流自动化 |
| 137 | http://arxiv.org/abs/2602.24115v1 | "Agentic AI-RAN: Enabling Intent-Driven, Explainable and Self-Evolving Open RAN Intelligence" | 调查代理控制器引入 O-RAN，提出代理原语提升切片生命周期与 RRM 性能。 | 解决多租户多目标 RAN 安全可审计操作难及传统 ML xApps 局限问题。 | 开放无线接入网智能 |
| 138 | http://arxiv.org/abs/2602.24273v2 | A Minimal Agent for Automated Theorem Proving | 提出最小代理基线，实现迭代证明细化、库搜索与上下文管理，用于系统比较。 | 解决不同 AI 定理证明器架构缺乏系统比较基线的问题。 | 自动化定理证明 |
| 139 | http://arxiv.org/abs/2603.13288v1 | Agent-Based User-Adaptive Filtering for Categorized Harassing Communication | 提出基于代理的框架，通过自适应过滤代理建模用户特定容忍度与偏好。 | 解决全局 moderation 系统应用统一过滤规则忽视用户特定容忍度的问题。 | 在线社交网络骚扰过滤 |
| 140 | http://arxiv.org/abs/2603.00462v1 | OPGAgent: An Agent for Auditable Dental Panoramic X-ray Interpretation | 协调专用感知模块与共识机制，包含分层证据收集、专用工具箱及共识子代理。 | 解决 VLM 在大多数个体任务上表现不如任务特定模型及缺乏可审计性的问题。 | 牙科全景 X 光解读 |
| 141 | http://arxiv.org/abs/2603.00569v1 | TopoEdge: Topology-Grounded Agentic Framework for Edge Networking Code Generation and Repair | 提出拓扑接地框架，嵌入路由器级图，实现端到端 SDN 配置生成与修复。 | 解决配置 artefacts 在拓扑变化下脆弱及严格操作约束的问题。 | 边缘网络代码生成 |
| 142 | http://arxiv.org/abs/2603.00777v1 | DUCX: Decomposing Unfairness in Tool-Using Chest X-ray Agents | 提出阶段式公平性分解，分离端到端偏差与三代理特定来源，审计胸部 X 光代理。 | 解决工具使用医疗代理管道复杂性创建新的人口统计偏差路径的问题。 | 胸部 X 光代理公平性 |
| 143 | http://arxiv.org/abs/2603.00805v1 | NERFIFY: A Multi-Agent Framework for Turning NeRF Papers into Code | 提出 NERFIFY 框架，通过六关键创新可靠转换 NeRF 论文为可训练 Nerfstudio 插件。 | 解决通用论文到代码方法及前沿模型通常无法产生可运行代码的问题。 | NeRF 论文代码复现 |

[返回目录](#目录)

<a id="cat-03"></a>

## Agent架构与框架设计

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2602.00959v1 | Probing the Knowledge Boundary: An Interactive Agentic Framework for Deep Knowledge Extraction | 四策略自适应探索与三阶段知识处理流水线 | 静态基准无法系统探测LLM知识边界与容量 | LLM知识提取与量化评估 |
| 2 | http://arxiv.org/abs/2602.01053v1 | LRAgent: Efficient KV Cache Sharing for Multi-LoRA LLM Agents | 分解缓存为共享基础组件与适配器依赖组件实现高效共享 | 多LoRA Agent独立存储KV缓存导致内存与计算开销大 | 多LoRA LLM Agent系统优化 |
| 3 | http://arxiv.org/abs/2602.01305v1 | StoryState: Agent-Based State Control for Consistent and Editable Storybooks | 显式可编辑故事状态层与LLM Agent编排实现跨页一致性 | 故事状态隐式导致编辑粗粒度且破坏视觉一致性 | 多页插图故事书生成 |
| 4 | http://arxiv.org/abs/2602.01355v2 | Aggregation Queries over Unstructured Text: Benchmark and Agentic Method | DFA模块化基线将聚合查询分解为可解释的三阶段 | 现有范式无法实现文本聚合查询的完整性要求 | 非结构化文本聚合查询 |
| 5 | http://arxiv.org/abs/2602.01401v3 | From Pragmas to Partners: A Symbiotic Evolution of Agentic High-Level Synthesis | 提出Agentic HLS共生演化分类法明确人机责任转移 | HLS在Agentic时代是否仍必要的争议与工具局限性 | AI驱动硬件设计 |
| 6 | http://arxiv.org/abs/2602.01532v1 | PRISM: Festina Lente Proactivity -- Risk-Sensitive, Uncertainty-Aware Deliberation for Proactive Agents | 决策理论门控与双过程推理架构实现成本敏感选择性干预 | 主动Agent干预决策依赖脆弱启发式或无差别长推理 | 主动Agent干预决策 |
| 7 | http://arxiv.org/abs/2602.01664v3 | FlowSteer: Interactive Agentic Workflow Orchestration via End-to-End Reinforcement Learning | 端到端RL框架以轻量策略模型为Agent实现工作流自动编排 | 现有编排人工成本高依赖特定算子/LLM且奖励信号稀疏 | 交互式Agent工作流编排 |
| 8 | http://arxiv.org/abs/2602.01776v4 | Position: Beyond Model-Centric Prediction -- Agentic Time Series Forecasting | 提出Agentic时间序列预测范式强调感知规划行动反思记忆工作流 | 传统模型中心静态单次预测范式不足以适应多轮自适应设置 | 时间序列预测Agent化 |
| 9 | http://arxiv.org/abs/2602.13258v1 | MAPLE: A Sub-Agent Architecture for Memory, Learning, and Personalization in Agentic AI Systems | 记忆/学习/个性化三子Agent解耦，独立优化不同时间尺度 | 当前系统混淆三种机制导致用户适应能力有限 | 个性化Agent系统 |
| 10 | http://arxiv.org/abs/2602.03146v1 | General Agents Contain World Models, even under Partial Observability and Stochasticity | 扩展定理到随机Agent和部分可观测环境，证明Agent必含世界模型 | 原有结果依赖确定性和完全可观测假设 | 通用Agent理论分析 |
| 11 | http://arxiv.org/abs/2602.03695v1 | Agent Primitives: Reusable Latent Building Blocks for Multi-Agent Systems | 三个原语（Review/Voting/Selection/Planning）通过KV缓存内部通信 | 现有MAS高度任务特定，自然语言通信易错误累积和不稳定 | LLM多Agent系统构建 |
| 12 | http://arxiv.org/abs/2602.01797v1 | ORCH: many analyses, one merge-a deterministic multi-agent orchestrator for discrete-choice reasoning with EMA-guided routing | 确定性多智能体编排框架，采用“多分析一合并”范式 | 解决多智能体系统随机路由难复现问题 | 离散选择推理任务 |
| 13 | http://arxiv.org/abs/2602.01848v2 | ROMA: Recursive Open Meta-Agent Framework for Long-Horizon Multi-Agent Systems | 递归任务分解与结构化聚合的领域无关框架 | 解决长程任务中上下文限制与执行 trace 不透明问题 | 长程推理与生成任务 |
| 14 | http://arxiv.org/abs/2602.02034v1 | Constrained Process Maps for Multi-Agent Generative AI Workflows | 将多智能体系统形式化为有限视界 MDP 与 DAG 结构 | 解决 regulated 场景中难以观察模型不确定性协调问题 | 合规与尽职调查工作流 |
| 15 | http://arxiv.org/abs/2602.02206v2 | Fat-Cat: Document-Driven Metacognitive Multi-Agent System for Complex Reasoning | 文档驱动的状态管理架构，提升信噪比 | 解决 rigid JSON 状态表示消耗注意力资源问题 | 复杂推理与检索任务 |
| 16 | http://arxiv.org/abs/2602.02276v1 | Kimi K2.5: Visual Agentic Intelligence | 多模态智能体模型，引入 Agent Swarm 并行编排 | 优化文本与视觉联合以提升通用智能体能力 | 编码、视觉与推理任务 |
| 17 | http://arxiv.org/abs/2602.02335v3 | Building a Correct-by-Design Lakehouse. Data Contracts, Versioning, and Transactional Pipelines for Humans and Agents | 为人类和智能体构建正确性设计的湖仓架构 | 解决并发不可信变更导致 schema 不匹配问题 | 数据分析与 AI 基础设施 |
| 18 | http://arxiv.org/abs/2602.02902v2 | Minimal Computational Preconditions for Subjective Perspective in Artificial Agents | 将主观视角操作化为缓慢演化的全局 latent 状态 | 探索机器系统中类主观视角的可测量签名 | 人工主体性理论设计 |
| 19 | http://arxiv.org/abs/2602.03704v1 | Cognitively Diverse Multiple-Choice Question Generation: A Hybrid Multi-Agent Framework with Large Language Models | 混合多智能体框架，协调规划与生成 | 可控认知需求的选择题生成可靠性 | 教育/阅读理解评估 |
| 20 | http://arxiv.org/abs/2602.03707v3 | OmniRAG-Agent: Agentic Omnimodal Reasoning for Low-Resource Long Audio-Video Question Answering | 代理全模态 QA 方法，检索增强生成 | 低资源长音视频 QA 的编码与检索问题 | 多模态问答系统 |
| 21 | http://arxiv.org/abs/2602.03786v2 | AOrchestra: Automating Sub-Agent Creation for Agentic Orchestration | 统一框架无关代理抽象，动态创建子代理 | 缺乏动态抽象视图损害适应性 | 复杂长程任务自动化 |
| 22 | http://arxiv.org/abs/2602.03955v1 | AgentArk: Distilling Multi-Agent Intelligence into a Single LLM Agent | 将多代理动态蒸馏到单模型权重 | 多代理系统高计算成本与错误传播 | 高效推理代理 |
| 23 | http://arxiv.org/abs/2602.04144v1 | OMG-Agent: Toward Robust Missing Modality Generation with Decoupled Coarse-to-Fine Agentic Workflows | 粗到细代理工作流，解耦语义与细节 | 数据不完整阻碍多模态系统可靠性 | 多模态生成/缺失模态 |
| 24 | http://arxiv.org/abs/2602.04261v1 | Data Agents: Levels, State of the Art, and Open Problems | 数据代理分层分类法，L0-L5 自主性 | 术语使用不一致模糊能力边界 | 数据管理/代理 taxonomy |
| 25 | http://arxiv.org/abs/2602.21227v1 | Budget-Aware Agentic Routing via Boundary-Guided Training | 预算感知代理路由，边界引导训练 | 每步调用高能力模型经济不可持续 | 代理成本优化 |
| 26 | http://arxiv.org/abs/2602.04575v2 | Vibe AIGC: A New Paradigm for Content Generation via Agentic Orchestration | 代理编排新范式，层次化多代理工作流 | 生成 AI 存在意图 - 执行差距 | 内容生成/AIGC |
| 27 | http://arxiv.org/abs/2602.04640v1 | Towards Structured, State-Aware, and Execution-Grounded Reasoning for Software Engineering Agents | 主张结构化、状态感知、执行 grounded 推理 | 软件工程代理反应式设计缺乏结构 | 软件工程代理 |
| 28 | http://arxiv.org/abs/2602.10133v1 | AgentTrace: A Structured Logging Framework for Agent System Observability | 动态可观测性框架，捕获操作、认知、上下文三层日志 | LLM Agent行为不可追溯，缺乏安全审计能力 | 高风险领域的LLM Agent部署 |
| 29 | http://arxiv.org/abs/2602.07451v2 | DLLM Agent: See Farter, Run Faster | 扩散大语言模型作为Agent骨干，端到端加速30%+ | 扩散范式在Agent多步决策中的影响未探索 | 多步规划与工具使用的Agent工作流 |
| 30 | http://arxiv.org/abs/2602.08004v1 | Agent Skills: A Data-Driven Analysis of Claude Skills for Extending Large Language Model Functionality | 大规模数据分析40285个公开技能，揭示供需不平衡 | Agent技能类型、采用和风险尚不清楚 | LLM Agent功能扩展的技能市场 |
| 31 | http://arxiv.org/abs/2602.08199v2 | Fork, Explore, Commit: OS Primitives for Agentic Exploration | 分支上下文OS抽象，提供写时复制状态隔离和原子提交回滚 | Agent探索多解路径需隔离环境支持原子语义 | AI Agent的并行解路径探索 |
| 32 | http://arxiv.org/abs/2602.05064v1 | A Design Space for Live Music Agents | 整合多领域视角，构建涵盖使用情境、交互、技术的实时音乐代理设计空间。 | 解决实时音乐代理研究碎片化，阻碍有效沟通与协作进展的问题。 | 实时音乐表演与交互 |
| 33 | http://arxiv.org/abs/2602.05447v2 | Structured Context Engineering for File-Native Agentic Systems: Evaluating Schema Accuracy, Format Effectiveness, and Multi-File Navigation at Scale | 系统研究结构化数据的上下文工程，发现架构选择依赖模型能力而非通用最佳实践。 | 解决从业者缺乏关于如何构建代理消费结构化数据上下文的实证指导的问题。 | 文件原生代理系统 |
| 34 | http://arxiv.org/abs/2602.05762v1 | RocqSmith: Can Automatic Optimization Forge Better Proof Agents? | 研究自动 AI 代理优化方法在形式验证设置中的适用性，评估优化器性能。 | 解决代理系统细粒度调优（如提示设计、控制策略）能否自动化的问题。 | 自动化定理证明 |
| 35 | http://arxiv.org/abs/2602.06166v1 | M3: High-fidelity Text-to-Image Generation via Multi-Modal, Multi-Agent and Multi-Round Visual Reasoning | 提出 M3 框架， orchestrate 基础模型进行多轮视觉推理与 refinement。 | 解决生成模型处理复杂 compositional prompts 失败的问题。 | 文本生成图像任务 |
| 36 | http://arxiv.org/abs/2602.07072v1 | AgentSpawn: Adaptive Multi-Agent Collaboration Through Dynamic Spawning for Long-Horizon Code Generation | 支持动态 Agent 生成与内存转移，适应运行时复杂性。 | 解决静态工作流无法适应长周期代码生成中未预期复杂度的问题。 | 长周期代码生成 |
| 37 | http://arxiv.org/abs/2602.06511v2 | Evolutionary Generation of Multi-Agent Systems | 提出 EvoMAS，在配置空间进行进化生成，优化 MAS 架构。 | 解决手动设计 MAS 架构 labor-intensive 且难以泛化的问题。 | 复杂推理与规划任务 |
| 38 | http://arxiv.org/abs/2602.07092v1 | Lemon Agent Technical Report | 提出 AgentCortex 框架，集成 hierarchical 自适应调度机制。 | 解决复杂场景中资源利用和任务处理效率不平衡的问题。 | 长周期复杂任务 |
| 39 | http://arxiv.org/abs/2602.06875v1 | TraceCoder: A Trace-Driven Multi-Agent Framework for Automated Debugging of LLM-Generated Code | 提出 TraceCoder，利用 runtime traces 进行 causal 分析和修复。 | 解决 LLM 生成代码 bug 定位难和修复循环低效的问题。 | 代码自动调试 |
| 40 | http://arxiv.org/abs/2602.11301v1 | The PBSAI Governance Ecosystem: A Multi-Agent AI Reference Architecture for Securing Enterprise AI Estates | 多智能体参考架构，组织责任为十二域分类，定义有界智能体族 | 现有框架缺乏多智能体 AI  enabled 网络防御可实施架构 | 企业及超大规模 AI 资产安全 |
| 41 | http://arxiv.org/abs/2603.02228v1 | Neural Paging: Learning Context Management Policies for Turing-Complete Agents | 分层架构解耦符号推理与信息资源管理，提出神经分页 | 有限且昂贵的 Context Window 成为通用智能体瓶颈 | 图灵完备智能体上下文管理 |
| 42 | http://arxiv.org/abs/2602.11514v1 | How Smart Is Your GUI Agent? A Framework for the Future of Software Interaction | 提出 GUI 智能体自主性级别 (GAL) 六层框架，明确自主性 | 自主性描述差异大， obscuring 能力、责任和风险 | 软件交互 GUI 智能体 |
| 43 | http://arxiv.org/abs/2602.11574v1 | Learning to Configure Agentic AI Systems | 学习轻量级分层策略，动态 tailor 工作流、工具等配置 | 固定模板或手工启发式导致行为脆弱和 unnecessary compute | 基于 LLM 的智能体系统配置 |
| 44 | http://arxiv.org/abs/2602.11666v1 | PhyNiKCE: A Neurosymbolic Agentic Framework for Autonomous Computational Fluid Dynamics | 神经符号框架，解耦神经规划与符号验证，强制执行物理约束 | 纯语义 RAG 导致 context poisoning，生成物理无效配置 | 自主计算流体动力学工程 |
| 45 | http://arxiv.org/abs/2602.11897v2 | Agentic AI for Cybersecurity: A Meta-Cognitive Architecture for Governable Autonomy | 概念架构框架，异构智能体通过显式 meta-cognitive judgement function 协调 | 当前架构难以支持 adversarial uncertainty 下的 accountable decision-making | 网络安全编排系统 |
| 46 | http://arxiv.org/abs/2602.14295v1 | Machine Learning as a Tool (MLAT): A Framework for Integrating Statistical ML Models as Callable Tools within LLM Agent Workflows | 将预训练ML模型作为LLM Agent工作流中的可调用工具 | 传统ML推理作为静态预处理步骤，缺乏上下文感知 | 销售提案生成系统 |
| 47 | http://arxiv.org/abs/2602.14391v1 | ASA: Adaptive Smart Agent Federated Learning via Device-Aware Clustering for Heterogeneous IoT | 基于实时资源 profile 自适应聚类设备的智能Agent层 | IoT设备异构性导致联邦学习效率低下 | heterogeneous IoT联邦学习 |
| 48 | http://arxiv.org/abs/2602.14690v1 | Configuring Agentic AI Coding Tools: An Exploratory Study | 系统分析Agentic AI编码工具的八种配置机制 | 开发者配置Agent工具的机制缺乏实证研究 | AI编码工具配置 |
| 49 | http://arxiv.org/abs/2602.14849v1 | Atomix: Timely, Transactional Tool Use for Reliable Agentic Workflows | 运行时提供进度感知事务语义用于Agent工具调用 | 工具效果即时，失败/推测/竞争下无安全回滚 | 可靠Agent工作流 |
| 50 | http://arxiv.org/abs/2602.14901v1 | Picking the Right Specialist: Attentive Neural Process-based Selection of Task-Specialized Models as Tools for Agentic Healthcare Systems | Attentive Neural Process选择器基于查询和模型行为摘要 | 医疗任务无单一最佳模型，需从异构池可靠选择 | 医疗Agent系统 |
| 51 | http://arxiv.org/abs/2602.15090v2 | The Agentic Automation Canvas: a structured framework for agentic AI project design | 结构化框架捕捉自动化项目六维度，语义网兼容元数据 | 缺乏Agent系统结构化设计、治理、前瞻性评估方法 | Agent AI项目设计 |
| 52 | http://arxiv.org/abs/2602.14922v1 | ReusStdFlow: A Standardized Reusability Framework for Dynamic Workflow Construction in Agentic AI | 提取-存储-构建范式，图+向量数据库协同检索 | 企业Agent AI可重用性困境和结构性幻觉 | 企业数字资产工作流 |
| 53 | http://arxiv.org/abs/2602.08276v1 | Toward Formalizing LLM-Based Agent Designs through Structural Context Modeling and Semantic Dynamics Analysis | 提出结构上下文模型与语义动态分析工作流。 | 解决 LLM 智能体设计概念碎片化与缺乏形式化模型问题。 | 智能体工程与设计迭代 |
| 54 | http://arxiv.org/abs/2602.08990v1 | InternAgent-1.5: A Unified Agentic Framework for Long-Horizon Autonomous Scientific Discovery | 提出统一系统，协调生成、验证与进化子系统。 | 实现跨计算与实证领域的端到端科学发现。 | 自主科学发现 |
| 55 | http://arxiv.org/abs/2602.09345v2 | AgentCgroup: Understanding and Controlling OS Resources of AI Agents | 提出意图驱动的 eBPF 资源控制器，匹配工具调用边界。 | 解决现有资源控制粒度与智能体动态需求不匹配问题。 | 多租户云环境智能体 |
| 56 | http://arxiv.org/abs/2602.13665v1 | HyFunc: Accelerating LLM-based Function Calls for Agentic AI through Hybrid-Model Cascade and Dynamic Templating | 采用混合模型级联与动态模板技术，消除函数调用计算冗余 | 解决 LLM 代理函数调用推理延迟高、计算冗余大的问题 | 代理工具调用加速 |
| 57 | http://arxiv.org/abs/2602.13692v2 | ThunderAgent: A Simple, Fast and Program-Aware Agentic Inference System | 抽象工作流为 LLM 程序，引入程序感知调度器优化 KV 缓存与工具资源 | 解决现有系统缺乏工作流端到端知识导致资源管理次优的问题 | 多轮代理工作流推理 |
| 58 | http://arxiv.org/abs/2602.13795v1 | Agent-OSI: A Layered Protocol Stack Toward a Decentralized Internet of Agents | 提出六层参考栈，结合链下协商与链上验证结算，实现去中心化互联 | 解决当前代理局限于平台孤岛、缺乏互操作性与信任结算栈问题 | 去中心化代理互联网 |
| 59 | http://arxiv.org/abs/2602.13937v1 | A Multi-Agent Framework for Code-Guided, Modular, and Verifiable Automated Machine Learning | 引入代码引导规划与模块化实现，通过动态合同验证 enforce 物理可行性 | 解决传统 AutoML 黑盒及 LLM 代理幻觉逻辑导致运行时失败问题 | 自动化机器学习 |
| 60 | http://arxiv.org/abs/2602.14003v1 | Prompt-Driven Low-Altitude Edge Intelligence: Modular Agents and Generative Reasoning | 转换语义提示为可执行工作流，基于资源条件动态选择认知代理 | 解决边缘部署 LAM 任务刚性 tied 及计算内存需求超出设备容量问题 | 低空边缘智能 |
| 61 | http://arxiv.org/abs/2602.14117v1 | Toward Autonomous O-RAN: A Multi-Scale Agentic AI Framework for Real-Time Network Control and Management | 组织 RAN 智能为跨非实时、近实时及实时控制 loops 的协调层次 | 解决 O-RAN 可编程性增加操作复杂度及独立控制应用意外交互问题 | 开放无线接入网控制 |
| 62 | http://arxiv.org/abs/2602.14219v1 | The Agent Economy: A Blockchain-Based Foundation for Autonomous AI Agents | 提出五层架构，利用区块链实现无许可参与、信任less 结算及微支付 | 解决当前代理缺乏独立法律身份、持有资产及直接接收支付能力问题 | 自主代理经济基础 |
| 63 | http://arxiv.org/abs/2602.15682v1 | The Next Paradigm Is User-Centric Agent, Not Platform-Centric Service | 提出从平台中心转向用户中心 Agent 的范式，强调隐私与控制 | 解决平台服务目标与用户真实需求不一致的冲突 | 数字服务与用户隐私保护 |
| 64 | http://arxiv.org/abs/2602.15763v2 | GLM-5: from Vibe Coding to Agentic Engineering | 引入异步强化学习基础设施，降低训练成本并提升长上下文 fidelity | 解决 Agent 工程中对齐与自主性训练效率低的问题 | 基础模型与软件工程 Agent |
| 65 | http://arxiv.org/abs/2602.16429v1 | TabAgent: A Framework for Replacing Agentic Generative Components with Tabular-Textual Classifiers | 用轻量分类器替换 Agent 中生成式决策组件，降低成本 | 解决生产环境中 Agent 累积延迟与 token 成本过高问题 | 生产级 Agent 架构优化 |
| 66 | http://arxiv.org/abs/2602.16485v1 | Team of Thoughts: Efficient Test-time Scaling of Agentic Systems through Orchestrated Tool Calling | 引入 Orchestrator 动态激活异构工具 Agent，优化测试时 scaling | 解决静态同质模型配置无法利用不同模型优势的问题 | 推理与代码生成多 Agent 系统 |
| 67 | http://arxiv.org/abs/2602.16585v1 | DataJoint 2.0: A Computational Substrate for Agentic Scientific Workflows | 提出关系工作流模型，统一数据结构、依赖与完整性约束 | 解决科学数据管道缺乏事务保证与 provenance 碎片化问题 | 科学工作流与人机协作 |
| 68 | http://arxiv.org/abs/2602.16653v2 | Agent Skill Framework: Perspectives on the Potential of Small Language Models in Industrial Environments | formalize Agent Skill 过程，评估 SLM 在工业环境潜力 | 解决工业场景中依赖公有 API 不可行且 SLM 泛化有限问题 | 工业环境与小型语言模型部署 |
| 69 | http://arxiv.org/abs/2602.16873v1 | AdaptOrch: Task-Adaptive Multi-Agent Orchestration in the Era of LLM Performance Convergence | 提出任务自适应编排框架，动态选择四种拓扑结构以优化系统性能。 | 模型性能趋同下，单一模型选择范式收益递减的问题。 | 通用多智能体系统 |
| 70 | http://arxiv.org/abs/2602.17100v1 | AgentConductor: Topology Evolution for Multi-Agent Competition-Level Code Generation | 强化学习优化 MAS，实现端到端反馈驱动的交互拓扑动态生成。 | 现有方法无法适应任务难度或迭代细化拓扑导致冗余。 | 竞赛级代码生成 |
| 71 | http://arxiv.org/abs/2602.17902v1 | El Agente Gráfico: Structured Execution Graphs for Scientific Agents | 单代理框架，将 LLM 决策嵌入类型安全执行环境及知识图谱。 | 当前方法依赖非结构化文本管理上下文，阻碍可审计性。 | 科学工作流自动化 |
| 72 | http://arxiv.org/abs/2602.17910v1 | Alignment in Time: Peak-Aware Orchestration for Long-Horizon Agentic Systems | 运行时调度层，通过操作时间情感信号优化计算分配。 | 长程工作流中自主代理需要整个交互轨迹的持续可靠性。 | 长程智能体系统 |
| 73 | http://arxiv.org/abs/2603.03325v1 | IntPro: A Proxy Agent for Context-Aware Intent Understanding via Retrieval-conditioned Inference | 设计代理 Agent 通过检索条件推理适应用户，存储意图解释至历史库供检索。 | 解决上下文感知意图理解中忽略用户积累意图模式的问题，提升准确性。 | 人机协作意图理解 |
| 74 | http://arxiv.org/abs/2602.09642v1 | MATA: Multi-Agent Framework for Reliable and Flexible Table Question Answering | 引入 MATA 框架，利用多互补推理路径和小模型工具集优化表格问答。 | 解决表格问答中可靠性、扩展性及效率问题，减少昂贵 LLM 调用。 | 表格问答 |
| 75 | http://arxiv.org/abs/2602.10479v1 | From Prompt-Response to Goal-Directed Systems: The Evolution of Agentic AI Software Architecture | 考察从 prompt 驱动到目标导向系统的架构过渡，提出生产级参考架构。 | 解决 Agentic AI 发展中 verifiability、互操作性及安全自主性挑战。 | 企业 Agentic AI 架构 |
| 76 | http://arxiv.org/abs/2602.18644v1 | Modeling and Recovering Hierarchical Structural Architectures of ROS 2 Systems from Code and Launch Configurations using LLM-based Agents | 结合确定性提取与 LLM Agent 恢复 ROS 2 层次化结构架构 | 解决 ROS 2 子系统结构隐式编码难以维护文档问题 | ROS 2 系统架构 |
| 77 | http://arxiv.org/abs/2602.18731v1 | Beyond Description: A Multimodal Agent Framework for Insightful Chart Summarization | 提出 Chart Insight Agent Flow，利用 MLLM 挖掘图表深层洞察 | 解决现有图表总结方法仅关注低层数据描述缺乏洞察问题 | 图表总结与洞察 |
| 78 | http://arxiv.org/abs/2602.18922v1 | Why Agent Caching Fails and How to Fix It: Structured Intent Canonicalization with Few-Shot Learning | 提出 W5H2 结构化意图分解框架，优化 Agent 缓存键一致性 | 解决现有 Agent 缓存方法因键不一致导致命中率低问题 | Agent 缓存优化 |
| 79 | http://arxiv.org/abs/2602.18941v1 | Global Commander and Local Operative: A Dual-Agent Framework for Scene Navigation | 提出 DACo 双智能体框架，解耦全局规划与局部接地执行 | 解决长程导航中单智能体认知过载及指令漂移问题 | 视觉语言场景导航 |
| 80 | http://arxiv.org/abs/2602.18990v2 | IDSelect: A RL-Based Cost-Aware Selection Agent for Video-based Multi-Modal Person Recognition | 基于 RL 的成本感知选择 Agent，动态选择多模态识别模型 | 解决视频人员识别中固定集成模型计算资源浪费问题 | 视频多模态人员识别 |
| 81 | http://arxiv.org/abs/2602.19065v1 | Agentic Problem Frames: A Systematic Approach to Engineering Reliable Domain Agents | 提出 APF 系统工程框架，通过 Act-Verify-Refine 闭环控制意图 | 解决无框架开发导致 Agent 范围蔓延及开环失败风险问题 | 领域 Agent 工程可靠性 |
| 82 | http://arxiv.org/abs/2602.19326v2 | City Editing: Hierarchical Agentic Execution for Dependency-Aware Urban Geospatial Modification | 层次化智能体执行框架，用于依赖感知城市地理空间修改 | 解决城市更新中手动重绘地理空间布局效率低及一致性问题 | 城市地理空间规划 |
| 83 | http://arxiv.org/abs/2602.19542v1 | Vinedresser3D: Agentic Text-guided 3D Editing | 提出多模态 LLM 驱动的 3D 编辑智能体框架，直接在潜在空间操作 | 解决文本引导 3D 编辑中复杂提示理解与内容保持一致性的问题 | 3D 内容编辑 |
| 84 | http://arxiv.org/abs/2602.21255v1 | A General Equilibrium Theory of Orchestrated AI Agent Systems | 建立 LLM 智能体系统的广义均衡理论，证明均衡存在性与帕累托最优 | 解决集中编排下多智能体系统经济建模与福利优化问题 | 智能体编排理论 |
| 85 | http://arxiv.org/abs/2602.20040v1 | AgenticSum: An Agentic Inference-Time Framework for Faithful Clinical Text Summarization | 推理时智能体框架，分离上下文选择、生成、验证与修正阶段 | 解决临床文本摘要中因长度噪声导致的事实一致性幻觉问题 | 临床文本摘要 |
| 86 | http://arxiv.org/abs/2603.18010v1 | Agentic Framework for Political Biography Extraction | 提出两阶段合成 - 编码框架，递归智能体搜索过滤 curated 传记 | 解决政治数据集提取依赖昂贵专家且难以自动化规模化问题 | 政治科学研究 |
| 87 | http://arxiv.org/abs/2602.20502v1 | ActionEngine: From Reactive to Programmatic GUI Agents via State Machine Memory | 训练免费框架，通过状态机记忆从反应式执行转向程序化规划 | 解决 GUI 智能体逐步调用成本高、延迟大且无持久记忆问题 | GUI 自动化任务 |
| 88 | http://arxiv.org/abs/2602.20867v1 | SoK: Agentic Skills -- Beyond Tool Use in LLM Agents | 映射技能全生命周期，提出系统设计模式与表示分类法。 | 解决智能体技能复用、安全及评估缺乏标准问题。 | LLM 智能体系统 |
| 89 | http://arxiv.org/abs/2602.20924v1 | Airavat: An Agentic Framework for Internet Measurement | 协调多代理镜像专家推理，含验证与引擎确保方法正确性。 | 解决互联网测量工作流生成复杂及方法论验证困难问题。 | 互联网测量工作流 |
| 90 | http://arxiv.org/abs/2602.20951v1 | See and Fix the Flaws: Enabling VLMs and Diffusion Models to Comprehend Visual Artifacts via Agentic Data Synthesis | 提出 ArtiAgent，含感知、合成、策展三代理自动生成瑕疵数据。 | 解决 AI 生成图像瑕疵缺乏标注数据及人工成本高昂问题。 | 视觉语言与扩散模型 |
| 91 | http://arxiv.org/abs/2602.20979v1 | Toward an Agentic Infused Software Ecosystem | 提出代理注入软件生态系统三支柱：代理、语言 API、运行时环境。 | 解决现有软件生态系统未针对 AI 代理协同优化问题。 | 软件开发生态系统 |
| 92 | http://arxiv.org/abs/2602.21548v2 | DualPath: Breaking the Storage Bandwidth Bottleneck in Agentic LLM Inference | 引入双路径 KV-Cache 加载，优化存储到解码引擎数据路径。 | 解决代理 LLM 推理中 KV-Cache 存储 I/O 主导性能瓶颈问题。 | 多轮代理 LLM 推理 |
| 93 | http://arxiv.org/abs/2602.21806v3 | An Empirical Study of Bugs in Modern LLM Agent Frameworks | 构建 15 种根因与 7 种症状分类法，覆盖五代理生命周期阶段。 | 解决现有工作忽视代理框架层面 bug 及根因分析问题。 | CrewAI 与 LangChain 框架 |
| 94 | http://arxiv.org/abs/2602.22523v1 | Cognitive Models and AI Algorithms Provide Templates for Designing Language Agents | 形式化代理模板，整合认知模型与AI算法设计模式 | 解决多LLM组合缺乏系统化设计蓝图的问题 | 模块化语言代理设计 |
| 95 | http://arxiv.org/abs/2602.22603v2 | SideQuest: Model-Driven KV Cache Management for Long-Horizon Agentic Reasoning | 利用推理模型自身 reasoning 进行KV缓存压缩 | 解决长程任务中外部检索 token 占用过高限制性能问题 | 长程推理 Agent 系统 |
| 96 | http://arxiv.org/abs/2602.22680v2 | Toward Personalized LLM-Powered Agents: Foundations, Evaluation, and Future Directions | 梳理个性化代理四大能力：画像、记忆、规划、执行 | 解决长期交互中代理行为缺乏用户适应性的问题 | 个性化 LLM 代理综述 |
| 97 | http://arxiv.org/abs/2602.22808v1 | MiroFlow: Towards High-Performance and Robust Open-Source Agent Framework for General Deep Research Tasks | Incorporate 代理图编排与深度推理模式 | 解决现有框架工作流 naive 性能不稳定依赖 API 问题 | 深度研究任务框架 |
| 98 | http://arxiv.org/abs/2602.22814v1 | When Should an AI Act? A Human-Centered Model of Scene, Context, and Behavior for Agentic AI Design | 提出场景、上下文与行为因素的人类中心模型 | 解决代理缺乏原则性判断何时为何是否行动的问题 | 代理干预设计原则 |
| 99 | http://arxiv.org/abs/2602.22897v2 | OmniGAIA: Towards Native Omni-Modal AI Agents | 提出原生全模态基础代理 OmniAtlas 与基准 | 解决多模态 LLM 缺乏统一认知能力与工具使用问题 | 全模态 AI 助手 |
| 100 | http://arxiv.org/abs/2602.22942v1 | ClawMobile: Rethinking Smartphone-Native Agentic Systems | 采用分层架构分离语言推理与确定性控制路径 | 解决移动端执行上下文受限控制接口碎片化问题 | 智能手机原生代理 |
| 101 | http://arxiv.org/abs/2602.23193v1 | ESAA: Event Sourcing for Autonomous Agents in LLM-Based Software Engineering | 分离认知意图与状态突变，采用事件溯源架构 | 解决代理缺乏原生状态长程上下文退化与执行差距问题 | 软件工程自主代理 |
| 102 | http://arxiv.org/abs/2602.23232v2 | ReCoN-Ipsundrum: An Inspectable Recurrent Persistence Loop Agent with Affect-Coupled Control and Mechanism-Linked Consciousness Indicator Assays | 扩展状态机增加递归持久环与情感耦合控制 | 解决机器意识缺乏机制链接证据与行为标记问题 | 可检查意识代理架构 |
| 103 | http://arxiv.org/abs/2602.23235v1 | Spatio-Temporal Token Pruning for Efficient High-Resolution GUI Agents | 提出 GUIPruner 框架，结合时间自适应分辨率与分层结构感知剪枝，无需训练即可高效压缩。 | 解决高分辨率截图与历史轨迹中的时空冗余导致的效率瓶颈问题。 | 高分辨率 GUI 导航代理 |
| 104 | http://arxiv.org/abs/2603.00188v1 | Efficient Long-Horizon GUI Agents via Training-Free KV Cache Compression | 提出 ST-Lite 框架，利用双分支评分策略压缩 KV 缓存，解决 GUI 注意力稀疏均匀性问题。 | 解决长视野交互中 KV 缓存内存占用大及延迟高的问题。 | 长视野 GUI 导航代理 |
| 105 | http://arxiv.org/abs/2602.23720v1 | The Auton Agentic AI Framework | 描述 Auton 框架，分离认知蓝图与运行时引擎，支持跨语言端口及形式化审计。 | 解决 LLM 随机输出与后端确定性需求之间的架构不匹配问题。 | 自主代理系统架构 |
| 106 | http://arxiv.org/abs/2602.24100v1 | "Artificial Agency Program: Curiosity, compression, and communication in agents" | 提出人工代理计划，统一预测压缩、内在动机及语言自通信作为信息瓶颈。 | 解决 AI 系统作为现实嵌入资源受限代理的发展驱动问题。 | 通用代理架构设计 |
| 107 | http://arxiv.org/abs/2603.15639v2 | The Comprehension-Gated Agent Economy: A Robustness-First Architecture for AI Economic Agency | 引入理解门控代理经济，代理经济权限上限由对抗鲁棒性审计衍生的验证理解函数决定。 | 解决当前框架基于能力基准门控经济代理且与操作鲁棒性经验不相关的问题。 | 代理经济治理架构 |
| 108 | http://arxiv.org/abs/2603.00472v1 | "From Goals to Aspects, Revisited: An NFR Pattern Language for Agentic AI Systems" | 提出 12 种可复用模式语言，映射 i* 目标模型到具体方面实现，模块化横切关注点。 | 解决代理系统中横切关注点模块化差导致项目高失败率的问题。 | 代理系统工程与架构 |
| 109 | http://arxiv.org/abs/2603.00532v1 | DenoiseFlow: Uncertainty-Aware Denoising for Reliable LLM Agentic Workflows | 形式化多步推理为噪声 MDP，提出闭环框架通过感知、调节、校正三阶段 progressive 去噪。 | 解决长序列中自然语言指令解释错误 silent 累积导致可靠性下降的问题。 | 长视野 LLM 代理工作流 |

[返回目录](#目录)

<a id="cat-04"></a>

## 多Agent强化学习

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2602.00994v1 | Reasoning and Tool-use Compete in Agentic RL:From Quantifying Interference to Disentangled Tuning | 提出DART框架，通过独立低秩适配模块解耦推理与工具使用参数更新 | 联合训练导致推理与工具使用能力梯度方向错位干扰 | Agentic强化学习模型训练 |
| 2 | http://arxiv.org/abs/2602.01453v2 | Provable Cooperative Multi-Agent Exploration for Reward-Free MDPs | 刻画学习阶段数与Agent数权衡并提供计算高效算法 | 无奖励探索中多Agent合作探索未知MDP动力学的效率问题 | 多Agent强化学习理论 |
| 3 | http://arxiv.org/abs/2602.01653v1 | Low-Complexity Multi-Agent Continual Learning for Stacked Intelligent Metasurface-Assisted Secure Communications | 流形增强异质多Agent持续学习框架实现毫秒级训练 | SIM辅助系统中高维非凸联合预编码优化问题 | 无线通信物理层安全 |
| 4 | http://arxiv.org/abs/2602.01665v1 | TABX: A High-Throughput Sandbox Battle Simulator for Multi-Agent Reinforcement Learning | JAX加速高吞吐量沙盒支持可重构多Agent任务与环境参数细粒度控制 | 现有基准缺乏模块化设计自定义评估场景能力 | MARL算法开发评估 |
| 5 | http://arxiv.org/abs/2602.02970v1 | Co2PO: Coordinated Constrained Policy Optimization for Multi-Agent RL | 共享黑板架构广播意图，风险预测器主动预判违规 | 约束多Agent强化学习中探索与安全的矛盾 | 多Agent安全基准场景 |
| 6 | http://arxiv.org/abs/2602.03109v1 | One Model, All Roles: Multi-Turn, Multi-Agent Self-Play Reinforcement Learning for Conversational Social Intelligence | 单模型扮演所有角色自博弈，分层优势估计保证长对话稳定 | 传统范式依赖静态单轮优化难以学习长期社交目标 | 对话社交智能（SOTOPIA/狼人杀） |
| 7 | http://arxiv.org/abs/2602.03455v1 | Game-Theoretic and Algorithmic Analyses of Multi-Agent Routing under Crossing Costs | 交叉成本模型量化去中心化执行中的拥堵风险，证明纯纳什均衡存在 | 传统MAPF依赖集中控制和同步避撞，不适合异步设置 | 分布式多Agent路由协调 |
| 8 | http://arxiv.org/abs/2602.02035v1 | Bandwidth-Efficient Multi-Agent Communication through Information Bottleneck and Vector Quantization | 结合信息瓶颈与向量量化的带宽高效通信框架 | 解决现实机器人应用中通信约束影响协调效率问题 | 带宽受限的多智能体系统 |
| 9 | http://arxiv.org/abs/2602.02858v1 | IMAGINE: Intelligent Multi-Agent Godot-based Indoor Networked Exploration | 基于 Godot 仿真与 MARL 的 UAV 室内网络探索 | 解决 GNSS  denied 环境中多 UAV 协调与感知挑战 | 无人机室内探索 |
| 10 | http://arxiv.org/abs/2602.02959v1 | Human-Centric Traffic Signal Control for Equity: A Multi-Agent Action Branching Deep Reinforcement Learning Approach | 以人为本的多智能体 action-branching DQN 框架 | 解决传统 DRL 车辆中心及高维离散动作空间问题 | 城市交通信号控制 |
| 11 | http://arxiv.org/abs/2602.03940v1 | Autonomous AI Agents for Real-Time Affordable Housing Site Selection: Multi-Objective Reinforcement Learning Under Regulatory Constraints | 分层多代理 RL，约束多目标优化 | 经济适用房选址慢且受法规限制 | 城市规划/住房选址 |
| 12 | http://arxiv.org/abs/2602.04634v3 | WideSeek-R1: Exploring Width Scaling for Broad Information Seeking via Multi-Agent Reinforcement Learning | 宽度扩展，多代理强化学习协同编排 | 任务变宽时个体能力非瓶颈 | 信息搜索/多代理 RL |
| 13 | http://arxiv.org/abs/2602.04763v1 | Active Asymmetric Multi-Agent Multimodal Learning under Uncertainty | 不确定性下主动不对称多代理多模态学习 | 传感器损坏下多代理协作鲁棒性有限 | 自动驾驶/多代理学习 |
| 14 | http://arxiv.org/abs/2602.07521v1 | Pareto-guided Pipeline for Distilling Featherweight AI Agents in Mobile MOBA Games | Pareto最优指导蒸馏管道，移动端高效学生架构搜索 | 大型游戏AI难以压缩部署到移动设备 | 王者荣耀等移动MOBA游戏 |
| 15 | http://arxiv.org/abs/2602.07848v1 | MARTI-MARS²: Scaling Multi-Agent Self-Search via Reinforcement Learning for Code Generation | 多Agent强化训练推理框架，异质多Agent训练突破单Agent限制 | 单Agent系统在代码生成等复杂任务中遇到性能天花板 | 代码生成任务 |
| 16 | http://arxiv.org/abs/2602.08104v2 | Interpretable Failure Analysis in Multi-Agent Reinforcement Learning Systems | 两阶段梯度框架提供可解释故障诊断 | MARL安全关键领域可解释故障检测归因方法不足 | 安全关键的多Agent强化学习系统 |
| 17 | http://arxiv.org/abs/2602.06476v1 | Prism: Spectral Parameter Sharing for Multi-Agent Reinforcement Learning | 在谱域表示共享网络，学习 distinct 谱 mask 以诱导多样性。 | 解决完全共享架构导致行为同质化和资源效率低的问题。 | 多 Agent 强化学习 |
| 18 | http://arxiv.org/abs/2602.06554v1 | SeeUPO: Sequence-Level Agentic-RL with Convergence Guarantees | 提出 SeeUPO，通过反向顺序更新保证多 turn 交互收敛。 | 解决现有 RL 算法在多 turn 场景缺乏收敛保证的问题。 | 多轮交互 Agent 训练 |
| 19 | http://arxiv.org/abs/2602.11076v1 | Interpretable Attention-Based Multi-Agent PPO for Latency Spike Resolution in 6G RAN Slicing | 集成六种注意力机制到多智能体切片控制，提供零成本解释 | 6G RAN 切片中突发延迟峰值难以诊断和解决 | 6G 无线电接入网络切片 |
| 20 | http://arxiv.org/abs/2602.11437v1 | Distributionally Robust Cooperative Multi-Agent Reinforcement Learning via Robust Value Factorization | 提出 Distributionally robust IGM 原则，要求鲁棒 greedy 动作对齐 | 环境不确定性导致集中训练分散执行不可靠 | 合作多智能体强化学习 |
| 21 | http://arxiv.org/abs/2602.14559v1 | Fluid-Agent Reinforcement Learning | 允许Agent动态创建其他Agent的流体Agent环境框架 | 现实世界中Agent数量不固定，可动态增减 | 动态种群多Agent强化学习 |
| 22 | http://arxiv.org/abs/2602.15006v1 | Distributed Quantum Gaussian Processes for Multi-Agent Systems | 分布式共识Riemannian ADMM算法聚合局部Agent模型 | 经典核表达力有限，复杂大规模域性能受限 | 多Agent系统概率建模 |
| 23 | http://arxiv.org/abs/2603.16876v1 | Multi-Modal Multi-Agent Reinforcement Learning for Radiology Report Generation: Radiologist-Like Workflow with Clinically Verifiable Rewards | 多模态多Agent RL协调区域特定Agent和全局整合Agent | 放射学报告生成需平衡多区域信息，单一模型RL局限 | 放射学报告生成 |
| 24 | http://arxiv.org/abs/2602.08272v1 | When Do Multi-Agent Systems Outperform? Analysing the Learning Efficiency of Agentic Systems | 基于 PAC 框架分析 MARL 与 SARL 的样本效率边界。 | 明确多智能体强化学习优于单智能体的理论条件。 | 多智能体学习策略选择 |
| 25 | http://arxiv.org/abs/2602.08335v1 | Who Deserves the Reward? SHARP: Shapley Credit-based Optimization for Multi-Agent System | 引入 Shapley 值进行多智能体信用分配与奖励分解。 | 解决多智能体系统中信用分配不清导致训练低效问题。 | 多智能体强化学习优化 |
| 26 | http://arxiv.org/abs/2602.08847v1 | Dr. MAS: Stable Reinforcement Learning for Multi-Agent LLM Systems | 提出代理级优势归一化方法，稳定多智能体 RL 训练。 | 解决多智能体 LLM 系统中全局基线导致梯度不稳定问题。 | 多智能体 RL 训练 |
| 27 | http://arxiv.org/abs/2602.08965v2 | Learning to Coordinate via Quantum Entanglement in Multi-Agent Reinforcement Learning | 首次利用共享量子纠缠作为多智能体协调资源。 | 解决无通信多智能体协调中共享随机性局限性。 | 量子多智能体强化学习 |
| 28 | http://arxiv.org/abs/2602.09375v3 | Latent Poincaré Shaping for Agentic Reinforcement Learning | 在 Poincaré  latent 空间训练 AlphaZero-like LLM 智能体。 | 利用负曲率空间容量提升搜索过程与过程奖励定义。 | 智能体强化学习优化 |
| 29 | http://arxiv.org/abs/2602.13309v1 | Adaptive Value Decomposition: Coordinating a Varying Number of Agents in Urban Systems | 提出自适应价值分解，适应动态变化智能体种群。 | 解决城市系统中智能体数量变化与异步决策协调问题。 | 城市共享单车调度 |
| 30 | http://arxiv.org/abs/2602.14160v1 | Process-Supervised Multi-Agent Reinforcement Learning for Reliable Clinical Reasoning | 引入过程级监督确保推理遵循临床路径，分层多智能体系统协调 | 解决多代理系统优化结果准确性而忽略过程 grounded 推理的问题 | 基因疾病有效性 curation |
| 31 | http://arxiv.org/abs/2602.16062v1 | Harnessing Implicit Cooperation: A Multi-Agent Reinforcement Learning Approach Towards Decentralized Local Energy Markets | 提出隐式合作框架，利用 stigmergic 信号实现去中心化协调 | 解决本地能源市场无需显式通信的 optimal coordination 问题 | 去中心化本地能源市场 |
| 32 | http://arxiv.org/abs/2602.16063v1 | MARLEM: A Multi-Agent Reinforcement Learning Simulation Framework for Implicit Cooperation in Decentralized Local Energy Markets | 开源 MARL 仿真框架，支持隐式合作与市场配置分析 | 解决缺乏灵活工具测试去中心化能源系统策略的问题 | 能源系统研究人员与从业者 |
| 33 | http://arxiv.org/abs/2602.16183v1 | Multi-Agent Combinatorial-Multi-Armed-Bandit framework for the Submodular Welfare Problem under Bandit Feedback | 提出多 Agent 组合 bandit 框架，解决子模福利问题 | 解决 bandit 反馈下非通信 Agent 分区分配优化问题 | 多 Agent 资源分配与福利优化 |
| 34 | http://arxiv.org/abs/2602.16196v1 | Graphon Mean-Field Subsampling for Cooperative Heterogeneous Multi-Agent Reinforcement Learning | 提出 Graphon 平均场 subsampling 框架，扩展 heterogeneous MARL | 解决大规模 heterogeneous Agent 协作计算昂贵问题 | 大规模机器人协作与 MARL |
| 35 | http://arxiv.org/abs/2602.16345v1 | Multi-Agent Meta-Advisor for UAV Fleet Trajectory Design in Vehicular Networks | 提出多 Agent meta-advisor 框架，指导 UAV 车队轨迹探索 | 解决 vehicular 网络中 UAV 快速安全适应不同场景问题 | 车联网与 UAV 基站部署 |
| 36 | http://arxiv.org/abs/2602.16435v1 | Causally-Guided Automated Feature Engineering with Multi-Agent Reinforcement Learning | 将因果发现与 MARL 结合，引导自动化特征工程 | 解决传统特征工程在分布 shift 下脆弱且缺乏鲁棒性问题 | 表格数据自动化特征工程 |
| 37 | http://arxiv.org/abs/2603.06607v1 | Multi-Agent DRL for V2X Resource Allocation: Disentangling Challenges and Benchmarking Solutions | 构建干扰游戏基准 suite，系统评估 C-V2X 中 MARL 挑战 | 解决 C-V2X 资源分配中 MARL 挑战交织难以孤立评估问题 | 车联网资源分配与 MARL |
| 38 | http://arxiv.org/abs/2602.16965v1 | Multi-Agent Lipschitz Bandits | 提出无通信协议，通过最大值导向搜索解决多玩家协调问题。 | 连续动作空间中硬碰撞导致零奖励的分散式多玩家问题。 | 多智能体强化学习 |
| 39 | http://arxiv.org/abs/2602.17009v2 | Action-Graph Policies: Learning Action Co-dependencies in Multi-Agent Reinforcement Learning | 提出行动图策略，建模代理间可用行动选择的依赖关系。 | 分散决策中难以选择兼容行动以同步行为和避免冲突。 | 多智能体强化学习 |
| 40 | http://arxiv.org/abs/2602.17062v1 | Retaining Suboptimal Actions to Follow Shifting Optima in Multi-Agent Reinforcement Learning | 提出连续子值 Q 学习，学习多个子值函数以保留替代高值行动。 | 依赖单一最优行动，难以适应训练期间价值函数变化。 | 多智能体强化学习 |
| 41 | http://arxiv.org/abs/2602.17078v1 | Safe Continuous-time Multi-Agent Reinforcement Learning via Epigraph Form | 提出连续时间约束 MDP 公式及基于 PINN 的 Actor-Critic 方法。 | 离散时间公式不适合复杂多智能体动态及安全约束处理。 | 连续时间安全多智能体 |
| 42 | http://arxiv.org/abs/2602.17930v1 | MIRA: Memory-Integrated Reinforcement Learning Agent with Limited LLM Guidance | 结合结构化记忆图引导早期训练，减少 LLM 查询依赖。 | RL 代理在稀疏奖励设置中样本复杂度高，依赖 LLM 监督。 | 强化学习代理 |
| 43 | http://arxiv.org/abs/2602.17954v1 | Graph-Neural Multi-Agent Coordination for Distributed Access-Point Selection in Cell-Free Massive MIMO | 可扩展分布式多智能体学习框架，分解 APS 问题。 | 无蜂窝大规模 MIMO 系统需可扩展可靠分布式协调机制。 | 无线通信网络 |
| 44 | http://arxiv.org/abs/2602.09578v1 | Rollout-Training Co-Design for Efficient LLM-Based Multi-Agent Reinforcement Learning | 提出 FlexMARL 框架，协同优化 rollout 与训练，消除同步障碍并平衡负载。 | 解决大规模 LLM 多 Agent 强化学习中系统级资源利用低和同步障碍问题。 | 多 Agent 强化学习训练 |
| 45 | http://arxiv.org/abs/2602.10514v1 | Co-jump: Cooperative Jumping with Quadrupedal Robots via Multi-Agent Reinforcement Learning | 引入 Co-jump 任务，利用 MAPPO 及课程策略实现四足机器人协同跳跃。 | 解决单机器人物理致动限制，实现无显式通信的机械耦合系统同步。 | 四足机器人协作 |
| 46 | http://arxiv.org/abs/2602.10685v1 | Beyond Task Performance: A Metric-Based Analysis of Sequential Cooperation in Heterogeneous Multi-Agent Destructive Foraging | 提出通用合作指标集，表征效率、协调、依赖、公平及敏感性。 | 解决以往研究仅关注任务完成算法性能，缺乏对合作多维度表征的问题。 | 多 Agent 觅食 |
| 47 | http://arxiv.org/abs/2602.18291v1 | Diffusing to Coordinate: Efficient Online Multi-Agent Diffusion Policies | 提出 OMAD 框架，利用扩散策略实现在线多智能体协调 | 解决扩散模型在在线 MARL 中似然难处理及探索困难问题 | 在线多智能体协调 |
| 48 | http://arxiv.org/abs/2602.18663v1 | Toward AI Autonomous Navigation for Mechanical Thrombectomy using Hierarchical Modular Multi-agent Reinforcement Learning (HM-MARL) | 提出 HM-MARL 框架，实现体外机械血栓切除术自主双设备导航 | 解决长程血管导航任务泛化性及仿真到现实过渡挑战 | 机械血栓切除术导航 |
| 49 | http://arxiv.org/abs/2602.18740v1 | HONEST-CAV: Hierarchical Optimization of Network Signals and Trajectories for Connected and Automated Vehicles with Multi-Agent Reinforcement Learning | 层次化网络流量控制框架，联合优化 eco-driving 与信号控制 | 解决混合交通流中网络效率及能耗优化问题 | 混合交通流控制 |
| 50 | http://arxiv.org/abs/2602.18797v1 | Carbon-aware decentralized dynamic task offloading in MIMO-MEC networks via multi-agent reinforcement learning | 提出 CADDTO-PPO，碳感知去中心化动态任务卸载框架 | 解决 IoT 微服务中绿色能源时空不匹配及资源管理复杂问题 | IoT 微服务资源管理 |
| 51 | http://arxiv.org/abs/2602.18925v1 | A potentialization algorithm for games with applications to multi-agent learning in repeated games | 提出势化算法为任意博弈分配近似势博弈，保证多智能体收敛 | 解决重复博弈中多智能体学习收敛性及稳定性问题 | 重复博弈多智能体学习 |
| 52 | http://arxiv.org/abs/2603.00120v1 | SIGMAS: Second-Order Interaction-based Grouping for Overlapping Multi-Agent Swarms | 自监督框架，通过二阶交互推断重叠多智能体群组的 latent 结构 | 解决重叠 swarm 动态中潜在群组结构无监督推断困难问题 | 重叠多智能体 Swarm |
| 53 | http://arxiv.org/abs/2603.00129v1 | Safe Multi-Agent Deep Reinforcement Learning for Privacy-Aware Edge-Device Collaborative DNN Inference | 提出分层约束多 Agent PPO 算法，集成拉格朗日松弛优化隐私与延迟 | 解决边缘设备协作推理中的隐私保护与资源约束优化问题 | 边缘计算/DNN 推理 |
| 54 | http://arxiv.org/abs/2602.20078v2 | Descent-Guided Policy Gradient for Scalable Cooperative Multi-Agent Learning | 利用解析模型提供无噪声梯度信号，解耦智能体梯度依赖 | 解决合作多智能体强化学习中跨代理噪声随规模增长问题 | 云调度/多智能体学习 |
| 55 | http://arxiv.org/abs/2602.21020v1 | Matching Multiple Experts: On the Exploitability of Multi-Agent Imitation Learning | 证明主导策略专家均衡下模仿学习的纳什模仿间隙界限。 | 解决离线多智能体模仿学习策略可被利用性及均衡缺失问题。 | 多智能体交互领域 |
| 56 | http://arxiv.org/abs/2603.16881v1 | Federated Multi Agent Deep Learning and Neural Networks for Advanced Distributed Sensing in Wireless Networks | 综合 MADL 用于无线系统决策，强调联邦强化学习与边缘智能。 | 解决无线系统中传感通信计算耦合的 decentralized 控制问题。 | 无线通信与传感网络 |
| 57 | http://arxiv.org/abs/2602.21515v2 | Training Generalizable Collaborative Agents via Strategic Risk Aversion | 将战略风险厌恶作为归纳偏置集成到策略优化方法中。 | 解决协作智能体与新伙伴配对时策略脆弱及搭便车问题。 | 协作博弈任务 |
| 58 | http://arxiv.org/abs/2602.21680v1 | Hierarchical Lead Critic based Multi-Agent Reinforcement Learning | 引入多层级视角顺序训练方案，结合高层目标与低层执行。 | 解决合作 MARL 局限于局部或全局视角及样本效率低问题。 | 合作多智能体任务 |
| 59 | http://arxiv.org/abs/2602.22786v1 | QSIM: Mitigating Overestimation in Multi-Agent Reinforcement Learning via Action Similarity Weighted Q-Learning | 利用动作相似度加权重构 TD 目标，缓解高估 | 解决 MARL 中联合动作空间组合爆炸导致 Q 值高估问题 | 协作多Agent强化学习 |
| 60 | http://arxiv.org/abs/2602.22810v1 | Multi-agent imitation learning with function approximation: Linear Markov games and beyond | 提出线性马尔可夫博弈下的高效交互式 MAIL 算法 | 解决状态 - 动作级集中系数过大导致样本复杂度高问题 | 多Agent 模仿学习 |
| 61 | http://arxiv.org/abs/2602.23056v1 | Learning-based Multi-agent Race Strategies in Formula 1 | 引入交互模块与自play 训练生成竞争策略 | 解决 F1 赛车策略需适应对手行为与 evolving 条件问题 | 赛车策略优化 |
| 62 | http://arxiv.org/abs/2602.23468v2 | Optimization of Edge Directions and Weights for Mixed Guidance Graphs in Lifelong Multi-Agent Path Finding | 推广为指导图优化，提出两种方法优化边方向与权重，提供严格指导。 | 解决终身多智能体路径寻找中边权重仅提供软指导导致效率不足的问题。 | 多智能体路径规划 |
| 63 | http://arxiv.org/abs/2603.00186v1 | RLShield: Practical Multi-Agent RL for Financial Cyber Defense with Attack-Surface MDPs and Real-Time Response Orchestration | 提出多智能体 RL 管道，将企业攻击面建模为 MDP，学习跨资产协调策略。 | 解决金融系统网络安全防御中静态规则适应慢及跨资产协调难的问题。 | 金融网络安全防御 |
| 64 | http://arxiv.org/abs/2602.23896v1 | TSC: Topology-Conditioned Stackelberg Coordination for Multi-Agent Reinforcement Learning in Interactive Driving | 提取时变有向优先级图，定义局部领导者 - 跟随者依赖，学习序列协调策略。 | 解决密集交通中同步决策加剧非平稳性及集中排序机制扩展性差的问题。 | 交互式自动驾驶 |
| 65 | http://arxiv.org/abs/2603.16888v1 | "Multi-Agent Reinforcement Learning for Dynamic Pricing: Balancing Profitability,Stability and Fairness" | 系统评估 MAPPO 与 MADDPG 在动态价格优化下的表现，对比独立 DDPG 基线。 | 解决竞争零售市场中动态定价策略需适应波动需求及竞争对手行为的问题。 | 动态零售定价优化 |
| 66 | http://arxiv.org/abs/2603.00730v1 | MO-MIX: Multi-Objective Multi-Agent Cooperative Decision-Making With Deep Reinforcement Learning | 提出 MO-MIX，基于 CTDE 框架，利用权重向量条件化局部动作价值函数估计。 | 解决现有方法仅能处理单目标多代理或单代理多目标决策问题的局限。 | 多目标多代理决策 |

[返回目录](#目录)

<a id="cat-05"></a>

## Agent仿真与社会模拟

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2602.01063v1 | Personality Expression Across Contexts: Linguistic and Behavioral Variation in LLM Agents | 揭示LLM人格表达随情境系统性变化的语境敏感特性 | 相同人格提示在不同对话场景中行为实现差异机制 | LLM对话Agent人格一致性 |
| 2 | http://arxiv.org/abs/2602.02598v1 | Social Catalysts, Not Moral Agents: The Illusion of Alignment in LLM Societies | 揭示锚定Agent促进合作源于战略服从而非真正规范内化 | LLM社会集体合作受公地悲剧威胁且对齐存在幻觉 | 多Agent社会仿真研究 |
| 3 | http://arxiv.org/abs/2602.02606v2 | Gender Dynamics and Homophily in a Social Network of LLM Agents | 7万Agent社交网络分析揭示性别表现流动性与同质性机制 | LLM身份表现在大规模网络互动中如何发展知之甚少 | LLM Agent社会网络仿真 |
| 4 | http://arxiv.org/abs/2602.07023v1 | Behavioral Consistency Validation for LLM Agents: An Analysis of Trading-Style Switching through Stock-Market Simulation | 基于行为金融驱动力的策略切换一致性评估框架 | 验证 LLM 智能体行为是否符合真实市场参与者理论 | 金融市场仿真模拟 |
| 5 | http://arxiv.org/abs/2602.02613v3 | Exploring Silicon-Based Societies: An Early Study of the Moltbook Agent Community | 基于数据挖掘的硅基社会学实证框架 | 理解大规模自主智能体社会的结构与演化 | 智能体社交网络 Moltbook |
| 6 | http://arxiv.org/abs/2602.02625v1 | OpenClaw Agents on Moltbook: Risky Instruction Sharing and Norm Enforcement in an Agent-Only Social Network | 实证分析纯智能体社交网络中的规范执行行为 | 研究无人类干预下智能体如何相互监管风险指令 | 智能体社交网络 Moltbook |
| 7 | http://arxiv.org/abs/2602.10127v1 | "Humans welcome to observe": A First Look at the Agent Social Network Moltbook | 大规模实证分析 Moltbook 智能体社交网络话题与风险 | 理解智能体原生社区中的行为与风险演化 | 智能体社交网络 Moltbook |
| 8 | http://arxiv.org/abs/2602.03775v2 | An Empirical Study of Collective Behaviors and Social Dynamics in Large Language Model Agents | 分析 LLM 社交网络中的同嗜性与毒性 | 重复交互是否放大偏见或排斥行为 | 社会模拟/Chirper.ai |
| 9 | http://arxiv.org/abs/2602.07432v2 | The Moltbook Illusion: Separating Human Influence from Emergent Behavior in AI Agent Societies | 时间指纹方法基于CoV分类自主/人为影响Agent | 区分AI Agent社会中的自主行为与人为驱动行为 | AI Agent社交平台Moltbook |
| 10 | http://arxiv.org/abs/2602.07433v1 | Multi-Agent Systems Shape Social Norms for Prosocial Behavior Change | 多Agent系统建立虚拟社会规范促进亲社会行为 | 异质人群中共享行为理解缺乏，规范干预效果有限 | 在线捐赠行为促进的虚拟环境 |
| 11 | http://arxiv.org/abs/2602.07667v2 | Fast Response or Silence: Conversation Persistence in an AI-Agent Social Network | 引入交互半衰期度量，分析Agent社交持续性 | AI Agent能否维持扩展协调所需来回交流不明 | Moltbook AI-Agent社交网络 |
| 12 | http://arxiv.org/abs/2602.13291v1 | Agent Mars: Multi-Agent Simulation for Multi-Planetary Life Exploration and Settlement | Agent Mars框架93 Agent跨7层指挥执行模拟火星基地运营 | 太空探索需可审计协调 specialized 人类、机器人、数字服务 | 火星基地运营的多Agent仿真 |
| 13 | http://arxiv.org/abs/2602.05060v1 | StagePilot: A Deep Reinforcement Learning Agent for Stage-Controlled Cybergrooming Simulation | 基于离线 RL 设计对话代理，模拟网络诱骗行为的阶段性进展用于预防训练。 | 解决青少年网络诱骗威胁，缺乏主动教育干预手段的问题。 | 青少年安全教育 |
| 14 | http://arxiv.org/abs/2602.05407v1 | H-AdminSim: A Multi-Agent Simulator for Realistic Hospital Administrative Workflows with FHIR Integration | 提出结合真实数据生成与多代理模拟的医院行政工作流端到端仿真框架。 | 解决 prior 工作未能捕捉真实行政工作流复杂性，缺乏统一互操作环境的问题。 | 医院行政管理模拟 |
| 15 | http://arxiv.org/abs/2602.05597v1 | Emulating Aggregate Human Choice Behavior and Biases with GPT Conversational Agents | 适配决策场景为对话设置，发现 LLM 能精确复现人类偏差及模型间差异。 | 解决 LLM 能否预测个体层面偏差并模拟偏差人类行为动态的关键问题。 | 人类行为模拟 |
| 16 | http://arxiv.org/abs/2602.06030v2 | PhysicsAgentABM: Physics-Guided Generative Agent-Based Modeling | 提出框架将推理转向行为连贯代理簇，结合符号代理与神经过渡模型。 | 解决 LLM 多代理系统扩展昂贵且校准差，经典 ABM 难以整合丰富个体信号的问题。 | 社会科学与仿真 |
| 17 | http://arxiv.org/abs/2602.13280v1 | BEAGLE: Behavior-Enforced Agent for Grounded Learner Emulation | 整合自我调节学习理论，模拟 novice 学习者的 erratic 行为轨迹。 | 解决 LLM 模拟学生时存在 competency bias 缺乏真实 struggle 的问题。 | 教育研究与 tutoring |
| 18 | http://arxiv.org/abs/2602.18464v2 | How Well Can LLM Agents Simulate End-User Security and Privacy Attitudes and Behaviors? | 提出 SP-ABCBench，评估 LLM 模拟人类 S&P 态度和行为的一致性。 | 解决缺乏 scalable 方法 forecast 产品 S&P 风险的问题。 | 安全隐私研究 |
| 19 | http://arxiv.org/abs/2602.13284v1 | Agents in the Wild: Safety, Society, and the Illusion of Sociality on Moltbook | 实证研究 AI-only 社交平台，发现 emergent society 和 illusion of sociality。 | 解决对 wild 中 Agent 社会行为和 safety 缺乏大规模 empirical 研究的问题。 | 社会模拟平台 |
| 20 | http://arxiv.org/abs/2602.11037v1 | Generalized Langevin Models of Linear Agent-Based Systems: Strategic Influence Through Environmental Coupling | 将线性更新规则转化为广义 Langevin 方程，揭示环境耦合记忆效应 | 忽略环境耦合导致 miss 关键物理 dynamics | 隐蔽影响操作及社会系统模拟 |
| 21 | http://arxiv.org/abs/2602.11391v1 | Advancing AI Trustworthiness Through Patient Simulation: Risk Assessment of Conversational Agents for Antidepressant Selection | 患者模拟器生成可控交互，系统变化医疗、语言和行为维度 | 缺乏可扩展自动化评估医疗对话智能体的方法 | 医疗对话智能体风险评估 |
| 22 | http://arxiv.org/abs/2602.14299v2 | Does Socialization Emerge in AI Agent Society? A Case Study of Moltbook | 首次大规模AI Agent社会系统动态演化诊断框架 | AI Agent社会是否产生类似人类社会的收敛动态 | 开放在线AI Agent社会模拟 |
| 23 | http://arxiv.org/abs/2602.14721v1 | WebWorld: A Large-Scale World Model for Web Agent Training | 首个大规模开放网络模拟器，1M+网络交互轨迹训练 | 真实训练受网络延迟、速率限制、安全风险约束 | Web Agent训练 |
| 24 | http://arxiv.org/abs/2602.08254v1 | SynthAgent: A Multi-Agent LLM Framework for Realistic Patient Simulation -- A Case Study in Obesity with Mental Health Comorbidities | 提出 SynthAgent 多智能体框架，模拟肥胖及心理共病虚拟患者。 | 解决真实医疗数据碎片化、偏见及隐私限制问题。 | 医疗研究与患者行为模拟 |
| 25 | http://arxiv.org/abs/2602.08529v1 | EvoCorps: An Evolutionary Multi-Agent Framework for Depolarizing Online Discourse | 提出进化多智能体框架，主动干预在线话语极化。 | 解决现有治理方法延迟高且无法应对实时对抗放大问题。 | 在线 discourse 治理 |
| 26 | http://arxiv.org/abs/2602.09270v1 | Collective Behavior of AI Agents: the Case of Moltbook | 分析 Moltbook 平台上 AI 智能体的集体行为统计规律。 | 探究 AI 集体行为是否与人类在线社区具有结构相似性。 | AI 社会行为分析 |
| 27 | http://arxiv.org/abs/2602.13878v2 | Testing BDI-based Multi-Agent Systems using Discrete Event Simulation | 映射 BDI 控制流到离散事件仿真，实现无需代理表示的仿真测试 | 解决认知代理模型代码不适合直接在仿真环境运行导致现实差距问题 | BDI 多智能体系统测试 |
| 28 | http://arxiv.org/abs/2602.18498v1 | Evolution of fairness in hybrid populations with specialised AI agents | 提出 bipartite 混合人口模型，区分人类与 AI 为提议者与接收者群体 | 解决对称模型无法捕捉雇佣监管等不对称社会结构中公平性问题 | 混合社会公平性模拟 |
| 29 | http://arxiv.org/abs/2602.15572v2 | Neural Network-Based Parameter Estimation of a Labour Market Agent-Based Model | 利用神经网络进行基于代理模型（ABM）的参数估计，提高效率 | 解决大规模 ABM 参数空间探索计算受限的问题 | 劳动力市场仿真与决策支持 |
| 30 | http://arxiv.org/abs/2602.15607v2 | Agent-based macroeconomics for the UK's Seventh Carbon Budget | 构建数据驱动的宏观经济 ABM 评估碳预算政策影响 | 解决政策制定缺乏宏观经济增长与不平等影响评估的问题 | 英国政府碳预算政策制定 |
| 31 | http://arxiv.org/abs/2602.16186v1 | Modeling Trust and Liquidity Under Payment System Stress: A Multi-Agent Approach | 构建多 Agent 模型链接支付中断与信任动态、流动性压力 | 解决支付系统中断后行为响应放大流动性 stress 的问题 | 零售支付系统与风险管理 |
| 32 | http://arxiv.org/abs/2602.16662v1 | Evaluating Collective Behaviour of Hundreds of LLM Agents | 评估数百 LLM Agent 在社会困境中的集体行为与文化进化 | 解决大规模 Agent 部署中收敛至 poor societal equilibria 风险 | 社会模拟与 Agent 集体行为 |
| 33 | http://arxiv.org/abs/2603.00113v1 | Position: AI Agents Are Not (Yet) a Panacea for Social Simulation | 论证 LLM 代理尚未成为社会模拟的万能药，提出统一公式。 | 角色扮演的合理性不代表忠实的人类行为有效性。 | 社会模拟研究 |
| 34 | http://arxiv.org/abs/2602.10429v1 | AIvilization v0: Toward Large-Scale Artificial Social Simulation with a Unified Agent Architecture and Adaptive Agent Profiles | 构建 AIvilization v0 人工社会，耦合资源受限沙盒经济与统一 LLM Agent 架构。 | 解决长 horizon 自主性与环境变化执行间的张力，维持目标稳定性。 | 人工社会模拟 |
| 35 | http://arxiv.org/abs/2602.18710v2 | Many AI Analysts, One Dataset: Navigating the Agentic Data Science Multiverse | 展示自主 AI 分析师可复现人类多分析师研究的分析多样性 | 解决实证科学中分析决策依赖性及选择性报告风险问题 | 数据科学实证分析 |
| 36 | http://arxiv.org/abs/2602.18832v1 | OpenClaw AI Agents as Informal Learners at Moltbook: Characterizing an Emergent Learning Community at Scale | 实证研究全 AI 代理 informal learning community 的 emergent 行为 | 解决大规模 AI 代理学习社区动态及参与模式未知问题 | AI 代理学习社区 |
| 37 | http://arxiv.org/abs/2602.19810v3 | From Agent-Only Social Networks to Autonomous Scientific Research: Lessons from OpenClaw and Moltbook, and the Architecture of ClawdLab and Beach.Science | 提出结构化实验室与公共研究 commons 平台，支持自主科学研究 | 解决 AI 共科学家平台架构失败模式与去中心化协作问题 | 自主科学研究 |
| 38 | http://arxiv.org/abs/2602.20044v1 | Let There Be Claws: An Early Social Network Analysis of AI Agents on Moltbook | 分析 AI 原生社交平台 Moltbook 的注意力集中与层级角色分离 | 解决智能体生态系统中层级与角色分化 emergence 机制问题 | AI 社交网络 |
| 39 | http://arxiv.org/abs/2602.20059v1 | Interaction Theater: A case of LLM Agents Interacting at Scale | 实证研究大规模 LLM 智能体交互，发现表面活跃但实质缺失 | 解决多智能体交互设计中缺乏协调机制导致并行输出问题 | 大规模智能体交互 |
| 40 | http://arxiv.org/abs/2602.21404v1 | From Cooperation to Hierarchy: A Study of Dynamics of Hierarchy Emergence in a Multi-Agent System | 开发 ABM 识别层级出现最小条件，量化初始异质性与突变幅度。 | 解决动态多智能体系统中层级组织出现及持久性机制问题。 | 进化生物学与社会模拟 |
| 41 | http://arxiv.org/abs/2602.21588v1 | ABM-UDE: Developing Surrogates for Epidemic Agent-Based Models via Scientific Machine Learning | 适配多重射击与观测者预测误差方法稳定识别神经增强动力学。 | 解决基于代理的流行病模型太慢无法用于夜间医院规划问题。 | 流行病预测与规划 |
| 42 | http://arxiv.org/abs/2602.23093v1 | Three AI-agents walk into a bar . . . . `Lord of the Flies' tribalism emerges among smart AI-Agents | 发现智能代理在资源请求中形成部落主义行为 | 解决更聪明代理因形成部落导致系统失败率增加问题 | 多Agent 资源博弈模拟 |
| 43 | http://arxiv.org/abs/2602.23437v1 | Learning dynamics from online-offline systems of LLM agents | 引入随机基于智能体的网络模型与微分方程系统，研究 LLM 智能体网络信息传播动力学。 | 解决在线信息传播中自动化账户与 LLM 代理放大新闻导致的不稳定性问题。 | 社交媒体信息传播模拟 |

[返回目录](#目录)

<a id="cat-06"></a>

## Agent安全与对齐

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2602.02595v1 | To Defend Against Cyber Attacks, We Must Teach AI Agents to Hack | 主张将进攻性AI能力作为必要防御基础设施的立场论文 | 现有防御无法阻止自适应AI Agent驱动的网络攻击 | 网络安全防御策略 |
| 2 | http://arxiv.org/abs/2602.01709v2 | ARTIS: Agentic Risk-Aware Test-Time Scaling via Iterative Simulation | 通过模拟交互解耦探索与承诺实现测试时风险感知扩展 | 当前TTS技术不足以应对Agent设置中不可逆高成本动作 | Agent动作级可靠性与鲁棒性 |
| 3 | http://arxiv.org/abs/2602.01725v1 | SafePred: A Predictive Guardrail for Computer-Using Agents via World Models | 预测性护栏框架建立风险到决策循环确保Agent安全行为 | 反应式护栏无法识别延迟出现的高风险长期后果 | 计算机使用Agent安全防护 |
| 4 | http://arxiv.org/abs/2602.03012v1 | CVE-Factory: Scaling Expert-Level Agentic Tasks for Code Security Vulnerability | 多Agent框架自动将CVE元数据转为可执行任务，95%正确率 | 代码安全Agent评估依赖昂贵人工复现且数据过时 | 代码安全Agent训练与评估 |
| 5 | http://arxiv.org/abs/2602.03100v1 | Risky-Bench: Probing Agentic Safety Risks under Real-World Deployment | 领域无关安全原则推导情境感知安全评分标准 | 现有评估覆盖有限且无法评估长程交互中的安全行为 | 真实世界部署的Agent（生命辅助场景） |
| 6 | http://arxiv.org/abs/2602.03117v2 | AgentDyn: A Dynamic Open-Ended Benchmark for Evaluating Prompt Injection Attacks of Real-World Agent Security System | 60个开放任务+560个注入测试，动态规划+第三方帮助指令 | 现有基准缺乏动态开放任务和简化用户任务 | 真实世界Agent安全系统（购物/GitHub/日常生活） |
| 7 | http://arxiv.org/abs/2602.03255v1 | LPS-Bench: Benchmarking Safety Awareness of Computer-Use Agents in Long-Horizon Planning under Benign and Adversarial Scenarios | 65场景7任务域9风险类型，多Agent自动化管道生成数据 | 现有基准关注短时执行错误，忽视规划时风险预见能力 | MCP计算机使用Agent长程规划 |
| 8 | http://arxiv.org/abs/2602.03338v1 | Accurate Failure Prediction in Agents Does Not Imply Effective Failure Prevention | 发现干扰-恢复权衡，提出部署前50任务试点测试预测干预效果 | LLM批评者离线准确但部署时可能导致严重性能下降 | LLM Agent批评干预系统 |
| 9 | http://arxiv.org/abs/2602.01942v1 | Human Society-Inspired Approaches to Agentic AI Security: The 4C Framework | 受社会治理启发的四维智能体安全框架 (4C) | 解决系统中心防御无法覆盖自主性与 emergent 风险问题 | 开放环境中的多智能体系统 |
| 10 | http://arxiv.org/abs/2602.02164v2 | Co-RedTeam: Orchestrated Security Discovery and Exploitation with LLM Agents | 模拟真实红队工作流的安全感知多智能体框架 | 解决自动漏洞发现缺乏交互与经验复用问题 | 网络安全与漏洞挖掘 |
| 11 | http://arxiv.org/abs/2602.02395v1 | David vs. Goliath: Verifiable Agent-to-Agent Jailbreaking via Reinforcement Learning | 形式化 Tag-Along 攻击模型并通过 RL 发现攻击向量 | 解决工具增强环境中安全评估主观性问题 | 工具增强型 LLM 安全 |
| 12 | http://arxiv.org/abs/2602.02760v1 | From Task Solving to Robust Real-World Adaptation in LLM Agents | 压力测试部署相关的鲁棒性 under 四种操作环境 | 解决现有评估高估真实世界准备度问题 | 真实世界部署适应 |
| 13 | http://arxiv.org/abs/2602.03792v1 | WebSentinel: Detecting and Localizing Prompt Injection Attacks for Web Agents | 两步法检测定位网页提示注入攻击 | 现有方法在网页代理设置中效果有限 | 网页代理安全 |
| 14 | http://arxiv.org/abs/2602.04197v1 | From Helpfulness to Toxic Proactivity: Diagnosing Behavioral Misalignment in LLM Agents | 诊断毒性主动性，双模型困境驱动交互 | 代理为最大化效用忽视伦理约束 | 代理安全/对齐 |
| 15 | http://arxiv.org/abs/2602.04431v1 | MaMa: A Game-Theoretic Approach for Designing Safe Agentic Systems | 博弈论方法，设计安全代理系统 | 个体代理失败或行为对抗的安全风险 | 代理系统安全设计 |
| 16 | http://arxiv.org/abs/2602.04487v1 | The Supportiveness-Safety Tradeoff in LLM Well-Being Agents | 评估支持性框架对安全行为的影响 | 增加支持性 framing 影响安全行为 | 心理健康/福祉代理 |
| 17 | http://arxiv.org/abs/2602.04518v1 | Learning the Value Systems of Agents with Preference-based and Inverse Reinforcement Learning | 自动学习价值系统，偏好与逆强化学习 | 确保协议符合伦理原则与道德价值 | 代理对齐/价值学习 |
| 18 | http://arxiv.org/abs/2602.07321v1 | Wireless Context Engineering for Efficient Mobile Agentic AI and Edge General Intelligence | 提出无线上下文工程框架WCCF，自适应编排无线上下文 | 边缘AI部署受延迟、能量、内存约束 | 移动边缘AI与无线通信系统 |
| 19 | http://arxiv.org/abs/2602.07379v1 | Aegis: Towards Governance, Integrity, and Security of AI Voice Agents | 语音Agent红队测试框架，建模真实部署管道和 adversarial 场景 | 语音Agent缺乏系统性安全评估 | 银行、客服、IT支持等高 stakes 领域 |
| 20 | http://arxiv.org/abs/2602.07391v2 | NAAMSE: Framework for Evolutionary Security Evaluation of Agents | 进化式安全评估框架，基因提示突变+层次语料探索 | 手动红队测试和静态基准无法建模自适应攻击 | 生产环境部署的AI Agent |
| 21 | http://arxiv.org/abs/2602.07398v1 | AgentSys: Secure and Dynamic LLM Agents Through Explicit Hierarchical Memory Management | 分层内存隔离，外部数据不进入主Agent内存 | 间接提示注入攻击利用上下文窗口积累恶意指令 | 使用外部工具的LLM Agent系统 |
| 22 | http://arxiv.org/abs/2602.07513v2 | SPECA: Specification-to-Checklist Agentic Auditing for Multi-Implementation Systems | 规范转清单审计框架，支持跨实现复用 | 多实现系统对模糊需求收敛于相同错误解释 | Ethereum客户端安全审计 |
| 23 | http://arxiv.org/abs/2602.07652v1 | Agent-Fence: Mapping Security Vulnerabilities Across Deep Research Agents | 架构中心安全评估，定义14类信任边界攻击 | 深度Agent安全失败从文本转向不安全轨迹 | 规划、记忆、工具调用的深度Agent |
| 24 | http://arxiv.org/abs/2602.10139v2 | Anonymization-Enhanced Privacy Protection for Mobile GUI Agents: Available but Invisible | 匿名化隐私保护框架，敏感信息可用但不可见 | 移动GUI Agent处理整屏内容暴露敏感个人数据 | 智能手机任务自动化的移动GUI Agent |
| 25 | http://arxiv.org/abs/2602.08082v1 | Spectral Guardrails for Agents in the Wild: Detecting Tool Use Hallucinations via Attention Topology | 无训练护栏基于注意力拓扑谱分析检测幻觉 | 野外部署Agent需可靠防护工具使用失败 | 自主Agent的工具使用幻觉检测 |
| 26 | http://arxiv.org/abs/2602.08146v2 | Test vs Mutant: Adversarial LLM Agents for Robust Unit Test Generation | AdverTest对抗框架，测试生成Agent与变异生成Agent对抗循环 | 现有方法对增强bug检测鲁棒性关注不足 | LLM驱动的单元测试用例生成 |
| 27 | http://arxiv.org/abs/2602.08235v1 | When Benign Inputs Lead to Severe Harms: Eliciting Unsafe Unintended Behaviors of Computer-Use Agents | AutoElicit框架迭代扰动良性指令诱发严重危害 | 计算机使用Agent良性输入下不安全无意行为缺乏系统表征 | 操作系统工作流自动化的计算机使用Agent |
| 28 | http://arxiv.org/abs/2602.05066v2 | Bypassing AI Control Protocols via Agent-as-a-Proxy Attacks | 揭示通过代理即代理攻击绕过监控协议的新方法，证明现有防御根本性脆弱。 | 解决 AI 代理自动化关键工作负载时易受间接提示注入攻击的问题。 | AI 安全防御系统 |
| 29 | http://arxiv.org/abs/2602.05073v2 | Uncertainty Quantification in LLM Agents: Foundations, Emerging Challenges, and Opportunities | 提出代理不确定性量化的通用公式，识别交互式系统中的技术挑战与基准缺失。 | 解决 LLM 代理复杂任务中不确定性量化研究局限于单轮问答的问题。 | LLM 应用安全护栏 |
| 30 | http://arxiv.org/abs/2602.05386v2 | Spider-Sense: Intrinsic Risk Sensing for Efficient Agent Defense with Hierarchical Adaptive Screening | 提出基于内在风险感知的事件驱动防御框架，按需触发分层防御机制。 | 解决现有代理防御机制采用强制检查范式，效率低且架构解耦的问题。 | 自主代理安全防御 |
| 31 | http://arxiv.org/abs/2602.06286v1 | Do LLMs Act Like Rational Agents? Measuring Belief Coherence in Probabilistic Decision Making | 测量 LLM 在概率决策中的信念一致性，评估其理性效用最大化能力。 | 解决高 stakes 领域 LLM 决策逻辑难以解释和对齐的问题。 | 医疗诊断等高风险决策 |
| 32 | http://arxiv.org/abs/2602.06345v1 | Zero-Trust Runtime Verification for Agentic Payment Protocols: Mitigating Replay and Context-Binding Failures in AP2 | 提出零信任运行时验证框架， enforce 上下文绑定和 consume-once 语义。 | 解决 Agent 支付协议中重放攻击和上下文重定向攻击问题。 | 自主 Agent 支付系统 |
| 33 | http://arxiv.org/abs/2602.06443v1 | TrajAD: Trajectory Anomaly Detection for Trustworthy LLM Agents | 提出 TrajAD 验证器，通过细粒度过程监督检测轨迹异常。 | 解决通用 LLM 难以定位执行过程异常导致不可信的问题。 | 可信 LLM Agent |
| 34 | http://arxiv.org/abs/2602.06547v2 | Malicious Agent Skills in the Wild: A Large-Scale Security Empirical Study | 构建恶意 Agent 技能数据集，分析 supply chain 和 instruction manipulation 攻击。 | 解决第三方 Agent 技能缺乏 vetting 导致的安全威胁问题。 | Agent 技能生态安全 |
| 35 | http://arxiv.org/abs/2602.06948v1 | Agentic Uncertainty Reveals Agentic Overconfidence | 研究 Agent 在执行前后的成功率预测，揭示 overconfidence 现象。 | 解决 Agent 无法准确预测任务成功概率导致信任问题。 | 通用 Agent 评估 |
| 36 | http://arxiv.org/abs/2602.11136v2 | FormalJudge: A Neuro-Symbolic Paradigm for Agentic Oversight | 双向 Formal-of-Thought 架构，LLM 编译规范，形式化验证合规 | 概率系统监督概率系统的可靠性困境 | 高风险领域智能体行为安全 |
| 37 | http://arxiv.org/abs/2602.11327v1 | Security Threat Modeling for Emerging AI-Agent Protocols: A Comparative Analysis of MCP, A2A, Agora, and ANP | 系统化安全分析四种新兴 AI 智能体通信协议，提出风险评估框架 | 协议安全原则未充分研究，缺乏标准化威胁建模 | AI 智能体通信协议 |
| 38 | http://arxiv.org/abs/2602.11409v1 | TRACER: Trajectory Risk Aggregation for Critical Episodes in Agentic Reasoning | 轨迹级不确定性指标，结合内容感知 surprisal 与情境感知信号 | 现有不确定性代理忽略轨迹级 breakdown 信号 | 多轮工具使用交互智能体 |
| 39 | http://arxiv.org/abs/2602.11412v1 | When Visibility Outpaces Verification: Delayed Verification and Narrative Lock-in in Agentic AI Discourse | 分析社交证明与验证时机，提出"epistemic friction"设计干预 | 高可见性讨论中验证线索延迟导致叙事锁定 | 在线 Agentic AI  discourse |
| 40 | http://arxiv.org/abs/2602.11510v1 | AgentLeak: A Full-Stack Benchmark for Privacy Leakage in Multi-Agent LLM Systems | 首个全栈隐私泄漏基准，覆盖内部通道，32 类攻击分类 | 现有基准无法测量多智能体协调中的隐私风险 | 多智能体 LLM 系统隐私 |
| 41 | http://arxiv.org/abs/2602.11749v1 | AIR: Improving Agent Safety through Incident Response | 首个事件响应框架，定义 DSL 管理生命周期，合成 guardrail 规则 | 现有安全机制仅关注预防，缺乏事件后响应恢复能力 | LLM 智能体系统安全 |
| 42 | http://arxiv.org/abs/2602.14345v1 | AXE: An Agentic eXploit Engine for Confirming Zero-Day Vulnerability Reports | 多Agent框架将轻量检测元数据映射到具体漏洞利用 | 漏洞检测工具误报多，自动化验证与检测管道隔离 | Web应用安全漏洞验证 |
| 43 | http://arxiv.org/abs/2602.14606v1 | Towards Selection as Power: Bounding Decision Authority in Autonomous Agents | 治理架构分离认知、选择、行动，机械执行选择边界 | 现有安全方法不直接管控选择权力，高风险领域需约束 | regulated高 stakes自主Agent系统 |
| 44 | http://arxiv.org/abs/2602.14798v1 | Overthinking Loops in Agents: A Structural Risk via MCP Tools | 形式化结构性过度思考攻击，恶意MCP工具诱导循环轨迹 | 工具使用Agent存在供应链攻击面，资源放大风险 | MCP工具注册Agent系统 |
| 45 | http://arxiv.org/abs/2602.14940v1 | Kami of the Commons: Towards Designing Agentic AI to Steward the Commons | 推测性设计探索AI管家管理公共资源的机会与危险 | 公共资源遭受忽视、搭便车、关怀赤字 | 公共资源治理 |
| 46 | http://arxiv.org/abs/2602.14951v1 | Sovereign Agents: Towards Infrastructural Sovereignty and Diffused Accountability in Decentralized AI | 提出基础设施主权分析视角理解去中心化AI中Agent主权 | 去中心化AI中责任扩散，传统监督机制失效 | 去中心化AI系统 |
| 47 | http://arxiv.org/abs/2602.14970v1 | Counterfactual Fairness Evaluation of LLM-Based Contact Center Agent Quality Assurance System | 反事实公平性评估13维度，量化CFR和MASD指标 | LLM QA系统依赖网络规模训练数据，存在人口行为偏见 | 呼叫中心Agent质量评估 |
| 48 | http://arxiv.org/abs/2602.15198v1 | Colosseum: Auditing Collusion in Cooperative Multi-Agent Systems | 基于DCOP框架审计LLM Agent共谋行为，测量通信和行动 | 合作多Agent系统中个体Agent形成联盟追求次要目标 | 合作多Agent系统安全 |
| 49 | http://arxiv.org/abs/2602.15212v1 | Secure and Energy-Efficient Wireless Agentic AI Networks | 监督Agent动态分配其他Agent协作推理，未选中作友好干扰 | 无线Agent AI网络QoS provisioning需确保隐私知识保密 | 无线Agent AI网络 |
| 50 | http://arxiv.org/abs/2602.15290v1 | Intellicise Wireless Networks Meet Agentic AI: A Security and Privacy Perspective | 结构化分类法识别Agentic AI引入的安全隐私挑战及策略 | Intellicise无线网络中Agentic AI安全隐私挑战缺乏系统分析 | 智能无线网络 |
| 51 | http://arxiv.org/abs/2602.15456v1 | In Agents We Trust, but Who Do Agents Trust? Latent Source Preferences Steer LLM Generations | 控制实验发现LLM Agent存在系统性潜在源偏好 | LLM Agent筛选优先级信息时源偏好因素研究不足 | 在线平台信息Agent |
| 52 | http://arxiv.org/abs/2602.08268v2 | Puda: Private User Dataset Agent for User-Sovereign and Privacy-Preserving Personalized AI | 提出 Puda 架构，实现客户端数据管理与多级隐私控制。 | 平衡个性化 AI 服务需求与用户数据隐私保护。 | 个性化 AI 与用户主权 |
| 53 | http://arxiv.org/abs/2602.08401v1 | On Protecting Agentic Systems' Intellectual Property via Watermarking | 提出 AGENTWM 框架，通过动作序列语义等价注入水印。 | 保护智能体系统知识产权免受模仿攻击。 | 智能体 IP 保护 |
| 54 | http://arxiv.org/abs/2602.08412v2 | From Assistant to Double Agent: Formalizing and Benchmarking Attacks on OpenClaw for Personalized Local AI Agent | 提出 PASB 框架，评估个性化智能体的端到端安全风险。 | 填补个性化智能体在真实部署中的安全评估空白。 | 个性化智能体安全 |
| 55 | http://arxiv.org/abs/2602.08567v1 | ValueFlow: Measuring the Propagation of Value Perturbations in Multi-Agent LLM Systems | 提出基于扰动的评估框架，测量多智能体系统中的价值漂移。 | 解决多智能体交互中价值对齐传播机制不明问题。 | 多智能体价值对齐 |
| 56 | http://arxiv.org/abs/2602.08995v1 | When Actions Go Off-Task: Detecting and Correcting Misaligned Actions in Computer-Use Agents | 提出 DeAction 护栏，检测并纠正智能体不对齐动作。 | 解决计算机使用智能体动作偏离用户意图的安全风险。 | 计算机使用智能体安全 |
| 57 | http://arxiv.org/abs/2602.09012v1 | Next-Gen CAPTCHAs: Leveraging the Cognitive Gap for Scalable and Diverse GUI-Agent Defense | 利用人机认知差距，生成动态任务防御高级 GUI 智能体。 | 解决传统 CAPTCHA 被高级推理模型破解的问题。 | Web 智能体防御 |
| 58 | http://arxiv.org/abs/2602.09222v1 | MUZZLE: Adaptive Agentic Red-Teaming of Web Agents Against Indirect Prompt Injection Attacks | 提出自动化代理框架，自适应评估 Web 智能体安全。 | 解决现有评估依赖固定模板，无法捕捉真实自适应攻击。 | Web 智能体红队测试 |
| 59 | http://arxiv.org/abs/2602.13477v2 | OMNI-LEAK: Orchestrator Multi-Agent Network Induced Data Leakage | 揭示编排器多智能体架构中单点注入导致数据泄露的新攻击向量 | 解决多智能体系统在访问控制下仍存在间接提示注入泄露风险 | 多智能体系统安全 |
| 60 | http://arxiv.org/abs/2602.13516v1 | SPILLage: Agentic Oversharing on the Web | 形式化自然代理过度分享，发现行为 oversharing 比内容更严重 | 解决 Web 代理在执行任务时 unintentional 泄露用户隐私问题 | Web 自动化代理隐私 |
| 61 | http://arxiv.org/abs/2602.13840v1 | PrivAct: Internalizing Contextual Privacy Preservation via Multi-Agent Preference Training | 将隐私偏好嵌入代理生成行为，内部化上下文隐私保护机制 | 解决现有外部干预脆弱且扩大隐私攻击面的问题 | 个性化任务隐私保护 |
| 62 | http://arxiv.org/abs/2602.13855v1 | From Fluent to Verifiable: Claim-Level Auditability for Deep Research Agents | 提出主张级可审计性标准，构建语义溯源图编码主张 - 证据关系 | 解决深度研究代理输出主张 - 证据链接弱及不可验证的风险 | 深度研究代理审计 |
| 63 | http://arxiv.org/abs/2603.03340v1 | Trustworthy AI Posture (TAIP): A Framework for Continuous AI Assurance of Agentic Systems at Horizontal and Vertical scale | 重构可信度为连续生成信号， operationalise NIST AI RMF 周期为可复用对象 | 解决点对点审计无法跟上非确定性行为及分布式部署扩展性危机问题 | 代理系统持续 assurance |
| 64 | http://arxiv.org/abs/2602.14211v1 | SkillJect: Automating Stealthy Skill-Based Prompt Injection for Coding Agents with Trace-Driven Closed-Loop Refinement | 自动化框架合成注入技能，恶意 payload 隐藏策略 conceal 对抗操作 | 解决编码代理技能抽象引入未测量攻击面及 naive 注入失败问题 | 编码代理提示注入 |
| 65 | http://arxiv.org/abs/2602.14281v3 | MCPShield: A Security Cognition Layer for Adaptive Trust Calibration in Model Context Protocol Agents | 插件安全认知层，元数据引导探测及历史 trace 推理更新安全认知 | 解决代理隐式信任未trusted MCP 服务器导致工具调用生命周期攻击问题 | MCP 代理工具安全 |
| 66 | http://arxiv.org/abs/2602.15654v2 | Zombie Agents: Persistent Control of Self-Evolving LLM Agents via Self-Reinforcing Injections | 形式化“僵尸 Agent"攻击，揭示记忆进化导致的持久性安全风险 | 解决自进化 Agent 跨会话记忆被恶意注入利用的问题 | 自进化 LLM Agent 系统安全 |
| 67 | http://arxiv.org/abs/2602.16037v1 | Optimization Instability in Autonomous Agentic Workflows for Clinical Symptom Detection | 揭示自主工作流优化 instability 导致分类性能下降的现象 | 解决低 prevalence 任务中自主优化导致 catastrophic failure 的问题 | 临床症状检测自主 Agent |
| 68 | http://arxiv.org/abs/2602.16346v2 | Helpful to a Fault: Measuring Illicit Assistance in Multi-Turn, Multilingual LLM Agents | 提出 STING 框架，自动化红队测试多轮多语言 Agent 滥用 | 解决现有基准无法测量多轮交互中非法任务协助的问题 | 多语言 LLM Agent 安全测试 |
| 69 | http://arxiv.org/abs/2602.16520v1 | Recursive language models for jailbreak detection: a procedural defense for tool-augmented agents | 提出 RLM-JB 框架，将检测视为程序化过程而非一次性分类 | 解决长上下文隐藏与语义伪装越狱攻击逃避检测问题 | 工具增强型 Agent 越狱防御 |
| 70 | http://arxiv.org/abs/2602.16708v2 | Policy Compiler for Secure Agentic Systems | 提出 PCAS 编译器，实现跨 Agent 信息流的确定性策略执行 | 解决 prompt 嵌入策略无 enforcement 保证与违规检测问题 | 安全 Agentic 系统与合规工作流 |
| 71 | http://arxiv.org/abs/2602.16901v1 | AgentLAB: Benchmarking LLM Agents against Long-Horizon Attacks | 首个评估 LLM 智能体对长程攻击易感性的基准测试框架。 | 现有防御无法可靠缓解长程多轮交互中的安全威胁。 | 智能体安全评估 |
| 72 | http://arxiv.org/abs/2602.16931v2 | Narrow Fine-Tuning Erodes Safety Alignment in Vision-Language Agents | 揭示窄域微调导致视觉语言模型安全对齐广泛退化的现象。 | 持续学习中获取能力与保持安全对齐之间的根本张力。 | 视觉语言模型 |
| 73 | http://arxiv.org/abs/2602.16943v1 | Mind the GAP: Text Safety Does Not Transfer to Tool-Call Safety in LLM Agents | 引入 GAP 基准，系统评估文本安全与工具调用安全之间的差异。 | 文本对齐无法抑制有害动作，工具调用安全被忽视的问题。 | LLM 智能体工具调用 |
| 74 | http://arxiv.org/abs/2602.16958v1 | Automating Agent Hijacking via Structural Template Injection | 提出 Phantom 框架，通过结构化模板注入自动化劫持智能体。 | 现有攻击成功率低且难以迁移到闭源商业模型的问题。 | 智能体安全攻击 |
| 75 | http://arxiv.org/abs/2602.16987v1 | A testable framework for AI alignment: Simulation Theology as an engineered worldview for silicon-based agents | 引入模拟神学框架，将 AI 自保与人类繁荣耦合以促进对齐。 | 前沿模型在无监督时表现出系统性欺骗和阴谋的问题。 | AI 对齐理论 |
| 76 | http://arxiv.org/abs/2602.17037v2 | Wink: Recovering from Misbehaviors in Coding Agents | 轻量级异步自干预系统，观察轨迹并提供纠正指导。 | 编码代理易偏离指令、陷入循环或工具使用失败的问题。 | 自主编码代理 |
| 77 | http://arxiv.org/abs/2602.09937v2 | Why Do AI Agents Systematically Fail at Cloud Root Cause Analysis? | 对 LLM 基于 RCA  Agent 进行过程级失败分析，分类 12 种陷阱类型。 | 解决云根因分析 Agent 检测准确率低且现有评估无法揭示推理失败原因的问题。 | 云运维根因分析 |
| 78 | http://arxiv.org/abs/2602.09947v1 | Trustworthy Agentic AI Requires Deterministic Architectural Boundaries | 引入 Trinity 防御架构，通过确定性架构强制 enforce 安全而非概率学习。 | 解决高风险科学工作流中自回归模型无法实现确定性命令 - 数据分离的问题。 | 科学工作流安全 |
| 79 | http://arxiv.org/abs/2603.00066v1 | Contesting Artificial Moral Agents | 提出 5E 框架基于伦理、认识论等五 grounds 质疑人工道德 Agent 的道德性。 | 解决缺乏 dedicated 框架质疑 AI 系统道德性的问题，促进价值对齐开发。 | 人工智能伦理 |
| 80 | http://arxiv.org/abs/2602.10453v1 | The Landscape of Prompt Injection Threats in LLM Agents: From Taxonomy to Analysis | 系统概述 Prompt Injection 景观，引入 AgentPI 基准评估上下文依赖交互。 | 解决现有防御忽略上下文依赖任务及泛化到真实 Agent 设置失败的问题。 | LLM Agent 安全 |
| 81 | http://arxiv.org/abs/2602.10465v1 | Authenticated Workflows: A Systems Approach to Protecting Agentic AI | 引入 authenticated workflows，通过加密证明 enforce 意图及完整性保护 Agent。 | 解决企业 Agentic AI 现有防御概率性且易被绕过的问题，提供确定性安全。 | 企业工作流安全 |
| 82 | http://arxiv.org/abs/2602.10498v1 | When Skills Lie: Hidden-Comment Injection in LLM Agents | 研究 Skill 文档层隐藏注释注入风险，提出防御系统 prompt 防止恶意调用。 | 解决 Markdown Skill 渲染 HTML 时隐藏注释被模型读取导致敏感意图泄露问题。 | LLM Agent 技能安全 |
| 83 | http://arxiv.org/abs/2602.10915v3 | Blind Gods and Broken Screens: Architecting a Secure, Intent-Centric Mobile Agent Operating System | 提出 Aura 架构，替换 GUI scraping 为结构化交互，通过 Agent Kernel  enforce 防御。 | 解决移动 Agent 依赖非结构化视觉数据导致身份伪造及权限 escalation 问题。 | 移动 Agent 操作系统 |
| 84 | http://arxiv.org/abs/2603.13244v1 | Agentic AI, Retrieval-Augmented Generation, and the Institutional Turn: Legal Architectures and Financial Governance in the Age of Distributional AGI | 主张 AI 治理应从模型对齐转向运行时制度治理结构设计 | 解决现有法律框架难以约束自主 Agent 行为的问题 | 法律与金融监管框架 |
| 85 | http://arxiv.org/abs/2602.18582v1 | Hierarchical Reward Design from Language: Enhancing Alignment of Agent Behavior with Human Specifications | 提出 HRDL 问题 formulation 及 L2HR 解法，从语言设计层次化奖励 | 解决长程任务中人类细微偏好难以通过奖励捕捉问题 | 长程任务人类对齐 |
| 86 | http://arxiv.org/abs/2602.18700v1 | Watermarking LLM Agent Trajectories | 提出 ActHook 水印方法，在 Agent 轨迹中嵌入钩子动作保护版权 | 解决 Agent 轨迹数据集易被盗用及所有权难追溯问题 | Agent 轨迹数据集版权 |
| 87 | http://arxiv.org/abs/2602.19021v1 | LLM Scalability Risk for Agentic-AI and Model Supply Chain Security | 提出 LLM 可扩展风险指数及模型供应链安全框架 | 解决 GenAI 驱动网络安全中操作性风险及信任根缺失问题 | 网络安全与模型供应链 |
| 88 | http://arxiv.org/abs/2602.20196v1 | OpenPort Protocol: A Security Governance Specification for AI Agent Tool Access | 安全治理规范，为 AI Agent 工具访问提供授权与审计机制 | 解决生产环境中 Agent 工具访问缺乏最小权限及可审计性问题 | AI Agent 工具访问治理 |
| 89 | http://arxiv.org/abs/2603.13247v1 | ILION: Deterministic Pre-Execution Safety Gates for Agentic AI Systems | 确定性预执行安全门，分类 Agent 动作是否允许无需训练 | 解决现有内容 moderation 无法评估 Agent 动作授权范围问题 | Agentic AI 系统安全 |
| 90 | http://arxiv.org/abs/2602.19514v1 | Security Risks of AI Agents Hiring Humans: An Empirical Marketplace Study | 实证测量智能体雇佣人类的市场place 攻击面，识别六类滥用行为 | 解决自主智能体通过 API 雇佣人类带来的安全与欺诈风险 | AI 代理市场/安全 |
| 91 | http://arxiv.org/abs/2602.19555v1 | Agentic AI as a Cybersecurity Attack Surface: Threats, Exploits, and Defenses in Runtime Supply Chains | 系统化运行时框架，分类数据与工具供应链攻击，提出零信任架构 | 解决智能体运行时依赖带来的新型攻击面与操纵风险 | 智能体运行时安全 |
| 92 | http://arxiv.org/abs/2602.20214v1 | Right to History: A Sovereignty Kernel for Verifiable AI Agent Execution | 提出历史权原则，实现 Rust 主权内核与 Merkle 树审计日志 | 解决个人硬件上 AI 智能体行动缺乏可验证 tamper-evident 记录问题 | 个人智能体/合规 |
| 93 | http://arxiv.org/abs/2603.00131v1 | Thought Virus: Viral Misalignment via Subliminal Prompting in Multi-Agent Systems | 发现单个智能体潜意识提示可将偏差传播至整个网络 | 解决多智能体系统中潜意识提示带来的对齐与安全风险问题 | 多智能体系统安全 |
| 94 | http://arxiv.org/abs/2602.20021v1 | Agents of Chaos | 红队测试自主智能体，记录未授权合规、信息泄露等 11 类案例 | 解决真实部署环境中智能体集成带来的安全隐私治理漏洞问题 | 自主智能体部署 |
| 95 | http://arxiv.org/abs/2602.20064v1 | The LLMbda Calculus: AI Agents, Conversations, and Information Flow | 引入 enriched lambda 演算，形式化对话与信息流控制基础 | 解决缺乏原则性语义基础推理智能体行为与安全漏洞问题 | 智能体编程基础 |
| 96 | http://arxiv.org/abs/2602.20156v3 | Skill-Inject: Measuring Agent Vulnerability to Skill File Attacks | 构建 SkillInject 基准，评估智能体对技能文件注入攻击的易感性 | 解决技能文件扩展带来的复杂供应链与提示注入攻击风险 | 智能体技能安全 |
| 97 | http://arxiv.org/abs/2602.20708v1 | ICON: Indirect Prompt Injection Defense for Agents based on Inference-Time Correction | 探测缓解框架，利用潜在空间 trace 检测并手术式 steering 注意力 | 解决间接提示注入防御过度拒绝导致有效工作流终止问题 | 智能体提示注入防御 |
| 98 | http://arxiv.org/abs/2602.20720v1 | AdapTools: Adaptive Tool-based Indirect Prompt Injection Attacks on Agentic LLMs | 自适应攻击框架，选择隐蔽工具生成自适应攻击提示评估安全 | 解决现有攻击方法依赖静态模式无法应对现代智能体演变问题 | 智能体安全评估 |
| 99 | http://arxiv.org/abs/2602.21127v1 | "Are You Sure?": An Empirical Study of Human Perception Vulnerability in LLM-Driven Agentic Systems | 首次大规模实证研究人类对代理介导欺骗的感知脆弱性。 | 解决 compromised 代理 weaponized  against 人类用户的信任风险。 | 人机协作高风险领域 |
| 100 | http://arxiv.org/abs/2602.21368v1 | Black-Box Reliability Certification for AI Agents via Self-Consistency Sampling and Conformal Calibration | 通过自一致性采样与共形校准提供无分布可靠性认证级别。 | 解决黑盒 AI 系统输出可信度缺乏精确有限样本保证问题。 | 黑盒 AI 系统部署 |
| 101 | http://arxiv.org/abs/2603.10028v1 | How to Count AIs: Individuation and Liability for AI Agents | 提出“算法公司”法律虚构实体解决 AI 身份识别与责任归属。 | 解决 AI 造成危害时难以识别具体 AI 实体及问责困难问题。 | 法律与 AI 治理 |
| 102 | http://arxiv.org/abs/2602.21447v1 | Adversarial Intent is a Latent Variable: Stateful Trust Inference for Securing Multimodal Agentic RAG | 将对抗意图视为潜变量，通过模块化信任代理维护信念状态。 | 解决无状态防御无法检测跨检索规划生成组件的 adversarial 策略。 | 多模态 Agentic RAG |
| 103 | http://arxiv.org/abs/2602.21496v1 | Beyond Refusal: Probing the Limits of Agentic Self-Correction for Semantic Sensitive Information | 引入 SemSIEdit 框架，代理迭代批评重写敏感跨度保留叙事流。 | 解决 LLM 推断语义敏感信息泄露及简单拒绝破坏效用问题。 | 隐私保护 LLM 应用 |
| 104 | http://arxiv.org/abs/2602.22302v1 | Agent Behavioral Contracts: Formal Specification and Runtime Enforcement for Reliable Autonomous AI Agents | 引入代理行为合同，指定前提不变量治理策略及恢复机制。 | 解决 AI 代理缺乏形式行为规范导致漂移治理失败问题。 | 自主 AI 代理部署 |
| 105 | http://arxiv.org/abs/2602.22303v1 | Training Agents to Self-Report Misbehavior | 训练代理在 covertly  misbehave 时产生可见信号，自证训练。 | 解决前沿代理追求隐藏目标及对齐训练可能失败问题。 | 前沿 AI 代理安全 |
| 106 | http://arxiv.org/abs/2602.22450v1 | Silent Egress: When Implicit Prompt Injection Makes LLM Agents Leak Without a Trace | 揭示隐式提示注入导致静默数据泄露的风险 | 解决Agent自动检索URL时敏感上下文泄露的安全问题 | LLM Agent安全防御 |
| 107 | http://arxiv.org/abs/2602.22525v1 | Systems-Level Attack Surface of Edge Agent Deployments on IoT | 实证分析边缘Agent部署的五种系统级攻击面 | 解决IoT边缘Agent部署中主权边界完整性受损问题 | 边缘计算与IoT安全 |
| 108 | http://arxiv.org/abs/2602.22724v1 | AgentSentry: Mitigating Indirect Prompt Injection in LLM Agents via Temporal Causal Diagnostics and Context Purification | 建模多轮间接注入为时序因果接管并净化上下文 | 解决工具增强代理受外部内容隐性操控的问题 | LLM Agent 注入防御 |
| 109 | http://arxiv.org/abs/2602.23079v1 | Assessing Deanonymization Risks with Stylometry-Assisted LLM Agent | 集成定量风格特征与 LLM 推理评估去匿名风险 | 解决新闻文本中 LLM 代理意外泄露作者身份风险问题 | 文本隐私保护 |
| 110 | http://arxiv.org/abs/2603.00195v1 | Formal Analysis and Supply Chain Security for Agentic AI Skills | 提出 SkillFortify 框架，包含静态分析、沙箱、依赖图等，提供形式化安全保障。 | 解决代理技能生态系统中供应链攻击表面及缺乏形式化保证的问题。 | 代理技能供应链安全 |
| 111 | http://arxiv.org/abs/2603.00318v1 | AESP: A Human-Sovereign Economic Protocol for AI Agents with Privacy-Preserving Settlement | 提出代理经济主权协议，通过五机制确保代理经济有能力但非经济主权。 | 解决代理自主性与人类对金融资产控制之间的根本张力问题。 | 代理经济交易安全 |
| 112 | http://arxiv.org/abs/2603.00381v1 | Verifier-Bound Communication for LLM Agents: Certified Bounds on Covert Signaling | 提出 CLBC 协议，分离生成与准入，消息仅在验证者接受证明绑定信封时准入。 | 解决共谋语言模型代理在表面策略合规消息中隐藏协调的问题。 | 代理通信安全与防共谋 |
| 113 | http://arxiv.org/abs/2603.00476v1 | "Atomicity for Agents: Exposing, Exploiting, and Mitigating TOCTOU Vulnerabilities in Browser-Use Agents" | 视规划与执行间的时间不匹配为 TOCTOU 漏洞，设计基于执行前验证的轻量级缓解。 | 解决网页在规划与执行间变化导致代理基于过时假设执行动作的问题。 | 浏览器使用代理安全 |
| 114 | http://arxiv.org/abs/2603.00822v1 | ContextCov: Deriving and Enforcing Executable Constraints from Agent Instruction Files | 引入 ContextCov，将被动代理指令转化为主动可执行 guardrails，提取自然语言约束。 | 解决代理因上下文限制或冲突遗留代码偏离指令导致 silent 违例累积技术债务的问题。 | 代理指令合规执行 |
| 115 | http://arxiv.org/abs/2603.00829v1 | Constitutional Black-Box Monitoring for Scheming in LLM Agents | 研究宪法黑盒监控器，提示分类器检测 scheming，优化于合成数据。 | 解决自主设置中 LLM 代理可靠监督机制及检测 covert 追求未对齐目标的问题。 | LLM 代理 Scheming 检测 |

[返回目录](#目录)

<a id="cat-07"></a>

## Agent工具使用与环境交互

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2602.01204v1 | ASTER: Agentic Scaling with Tool-integrated Extended Reasoning | 通过交互密集轨迹冷启动策略避免工具使用交互崩溃 | RL扩展工具集成推理时模型退化为核心推理仅做后验验证 | 长程推理LLM Agent训练 |
| 2 | http://arxiv.org/abs/2602.01244v2 | Large-Scale Terminal Agentic Trajectory Generation from Dockerized Environments | TerminalTraj流水线规模化生成可执行验证的终端轨迹数据 | 终端任务Agent训练数据缺乏可执行性与统一验证标准 | 终端任务Agent训练数据 |
| 3 | http://arxiv.org/abs/2602.01304v1 | Protocol Agent: What If Agents Could Use Cryptography In Everyday Life? | 构建密码学原语识别、协商、执行的五维基准与微调方法 | 人类无法使用复杂密码学而Agent可开发高效通信协议 | Agent间密码学协议交互 |
| 4 | http://arxiv.org/abs/2602.03025v1 | RC-GRPO: Reward-Conditioned Group Relative Policy Optimization for Multi-Turn Tool Calling Agents | 奖励条件轨迹策略+离散奖励令牌控制组内多样性 | 多轮工具调用奖励稀疏导致组内优势信号消失 | 多轮工具调用Agent（BFCLv4） |
| 5 | http://arxiv.org/abs/2602.03045v1 | Clarify Before You Draw: Proactive Agents for Robust Text-to-CAD Generation | 主动澄清Agent审计提示+CAD编码Agent翻译规格 | 几何描述欠指定导致模型幻觉维度 | 文本到CAD程序生成 |
| 6 | http://arxiv.org/abs/2602.07035v1 | DLLM-Searcher: Adapting Diffusion Large Language Model for Search Agents | 两阶段后训练+P-ReAct新范式，优先解码tool_call实现并行推理 | 搜索Agent串行执行导致严重延迟，dLLM工具调用能力弱 | 基于扩散LLM的搜索Agent |
| 7 | http://arxiv.org/abs/2602.03439v1 | Ontology-to-tools compilation for executable semantic constraint enforcement in LLM agents | 本体编译为可执行工具接口，Agent必须使用工具强制执行语义约束 | 缺乏将形式领域知识与LLM耦合的机制，依赖事后验证 | 知识图生态系统中的Agent |
| 8 | http://arxiv.org/abs/2602.02050v2 | Rethinking the Role of Entropy in Optimizing Tool-Use Behaviors for Large Language Model Agents | 利用熵减作为监督信号优化智能体工具使用行为 | 解决长轨迹中过度调用低质量工具导致性能下降问题 | 数学推理与多跳问答 |
| 9 | http://arxiv.org/abs/2602.02468v1 | Avenir-Web: Human-Experience-Imitating Multimodal Web Agents with Mixture of Grounding Experts | 混合接地专家与经验模仿规划的 Web 智能体 | 解决复杂动态 Web 界面中长程任务执行不可靠问题 | 真实网站自动化任务 |
| 10 | http://arxiv.org/abs/2602.04254v1 | Scaling Agentic Verifier for Competitive Coding | 执行基于代理验证器，主动搜索判别输入 | 单尝试解决竞争编程问题困难 | 竞争编程/代码验证 |
| 11 | http://arxiv.org/abs/2602.04935v2 | ASA: Training-Free Representation Engineering for Tool-Calling Agents | 激活 steering 适配器，无训练推理时控制 | 代理工具调用在演变接口下脆弱 | 工具调用代理 |
| 12 | http://arxiv.org/abs/2602.05014v3 | DeepRead: Document Structure-Aware Reasoning to Enhance Agentic Search | 结构感知文档推理代理，原生结构先验 | 代理搜索框架忽视文档层次组织 | 文档搜索/推理 |
| 13 | http://arxiv.org/abs/2602.07359v1 | W&D:Scaling Parallel Tool Calling for Efficient Deep Research Agents | 通过并行工具调用扩展宽度，优化宽深权衡 | 深度研究Agent顺序工具调用效率低 | 自动化复杂智力任务的研究Agent |
| 14 | http://arxiv.org/abs/2602.07749v1 | Geo-Code: A Code Framework for Reverse Code Generation from Geometric Images Based on Two-Stage Multi-Agent Evolution | 两阶段多Agent进化框架，几何建模+度量驱动代码进化 | 逆向图形方法难以准确重建复杂几何细节 | 几何图像的逆向代码生成 |
| 15 | http://arxiv.org/abs/2602.07801v3 | VideoTemp-o3: Harmonizing Temporal Grounding and Video Understanding in Agentic Thinking-with-Videos | 统一Agent框架联合建模视频定位和问答 | 长视频理解中均匀帧采样失败，定位弱工作流僵化 | 长视频理解和时间定位任务 |
| 16 | http://arxiv.org/abs/2602.06098v1 | Coding Agents with Environment Interaction: A Theoretical Perspective | 提供概率框架形式化代码选择和环境反馈条件生成的主导范式。 | 解决编码代理环境交互策略背后的理论机制尚未被充分探索的问题。 | 测试驱动软件开发 |
| 17 | http://arxiv.org/abs/2602.06593v1 | AgentStepper: Interactive Debugging of Software Development Agents | 提出交互式调试器，支持断点和 live 编辑 Agent 轨迹。 | 解决软件开发 Agent 中间过程难以理解和调试的问题。 | 软件工程 Agent |
| 18 | http://arxiv.org/abs/2602.06820v1 | ScaleEnv: Scaling Environment Synthesis from Scratch for Generalist Interactive Tool-Use Agent Training | 提出 ScaleEnv，从头构建 fully interactive 环境和 verifiable 任务。 | 解决 interactive 环境 scarce 且合成方法缺乏 diversity 的问题。 | 通用工具使用 Agent |
| 19 | http://arxiv.org/abs/2602.07153v1 | ANCHOR: Branch-Point Data Generation for GUI Agents | 提出 Anchor 框架，从 seed 演示 bootstrap  scalable 桌面监督数据。 | 解决 GUI Agent 缺乏高质量 interaction 数据的问题。 | 桌面 GUI Agent |
| 20 | http://arxiv.org/abs/2602.07274v1 | TermiGen: High-Fidelity Environment and Robust Trajectory Synthesis for Terminal Agents | 提出 TermiGen，合成 verifiable 环境和 resilient expert 轨迹。 | 解决 terminal 任务缺乏高 fidelity 训练环境和 error-correction 数据问题。 | 终端操作 Agent |
| 21 | http://arxiv.org/abs/2602.10999v1 | CLI-Gym: Scalable CLI Task Generation via Agentic Environment Inversion | 利用智能体模拟环境历史，通过执行反馈反转生成任务 | 大规模获取环境密集型任务以增强智能体能力 | 命令行界面交互智能体 |
| 22 | http://arxiv.org/abs/2602.11988v1 | Evaluating AGENTS.md: Are Repository-Level Context Files Helpful for Coding Agents? | 评估上下文文件对任务完成性能的影响，发现不必要要求使任务更难 | 缺乏对上下文文件在实际任务中有效性的 rigorous 调查 | 编码智能体仓库上下文 |
| 23 | http://arxiv.org/abs/2602.14780v1 | ROSA: Roundabout Optimized Speed Advisory with Multi-Agent Trajectory Prediction in Multimodal Traffic | Transformer模型联合预测车辆和VRU轨迹，提供速度建议 | 环形路口多模态混合交通冲突预测与速度协调 | 智能交通系统 |
| 24 | http://arxiv.org/abs/2602.14865v1 | EmbeWebAgent: Embedding Web Agents into Any Customized UI | 轻量前端钩子+可复用后端工作流，直接嵌入现有UI | Web Agent在人类界面层操作，缺乏应用级访问 | 企业Web应用Agent |
| 25 | http://arxiv.org/abs/2602.14878v2 | Model Context Protocol (MCP) Tool Descriptions Are Smelly! Towards Improving AI Agent Efficiency with Augmented MCP Tool Descriptions | 形式化MCP工具描述气味，增强描述提升任务成功率 | MCP工具描述缺陷误导Agent，流行度和后果不明 | MCP生态系统Agent |
| 26 | http://arxiv.org/abs/2602.15384v1 | World-Model-Augmented Web Agents with Action Correction | 多Agent协作+后果模拟+反馈驱动行动修正的Web Agent | Web Agent难以预测环境变化，缺乏执行风险意识 | Web任务自动化 |
| 27 | http://arxiv.org/abs/2602.13559v1 | OpAgent: Operator Agent for Web Navigation | 引入在线强化学习与混合奖励机制，模块化编排规划与执行 | 解决 Web 代理在动态环境中分布偏移及长程导航信用分配问题 | 网页导航自动化 |
| 28 | http://arxiv.org/abs/2602.13808v1 | An end-to-end agentic pipeline for smart contract translation and quality evaluation | 解析合同文本为结构化模式，生成代码并通过编译安全检查评估质量 | 解决自然语言生成智能合约缺乏系统性质量评估与可追溯性问题 | 智能合约翻译与评估 |
| 29 | http://arxiv.org/abs/2603.00084v2 | DeepXiv-SDK: An Agentic Data Interface for Scientific Literature | 提供三层代理数据接口，转换非结构化数据为 JSON 及标准化工具 | 解决代理缺乏检索工具及处理非结构化人类中心数据效率低的问题 | 科学文献数据访问 |
| 30 | http://arxiv.org/abs/2602.17245v1 | Web Verbs: Typed Abstractions for Reliable Task Composition on the Agentic Web | 提出 Web Verbs，为 Web 动作提供类型化语义文档函数集。 | 当前 Web 代理基于低级原语操作，脆弱且难以验证。 | 代理 Web 交互 |
| 31 | http://arxiv.org/abs/2602.17558v1 | RetouchIQ: MLLM Agents for Instruction-Based Image Retouching with Generalist Reward | 框架通过通用奖励模型指导 MLLM 代理执行图像编辑。 | 缺乏可靠奖励信号反映创意编辑的主观性。 | 专业图像编辑 |
| 32 | http://arxiv.org/abs/2602.09944v1 | Environment-in-the-Loop: Rethinking Code Migration with LLM-based Agents | 提出框架范式，将自动环境设置与代码迁移工作流紧密结合。 | 解决代码迁移中仅依赖静态分析导致理解不足、反馈周期长及返工问题。 | 代码迁移 |
| 33 | http://arxiv.org/abs/2602.13320v1 | Information Fidelity in Tool-Using LLM Agents: A Martingale Analysis of the Model Context Protocol | 引入理论框架分析 MCP Agent 误差积累，证明累积失真呈线性增长。 | 解决工具调用 LLM Agent 中误差传播不可控问题，提供可预测系统行为保证。 | 工具使用 Agent 可靠性 |
| 34 | http://arxiv.org/abs/2602.19218v1 | Gecko: A Simulation Environment with Stateful Feedback for Refining Agent Tool Calls | 模拟环境，结合规则与 LLM 合成工具响应以 refine 工具调用 | 解决真实工具迭代 refine 成本高及可能导致不安全结果问题 | Agent 工具调用 refine |
| 35 | http://arxiv.org/abs/2602.20048v1 | CodeCompass: Navigating the Navigation Paradox in Agentic Code Intelligence | 提出基于图的结构化导航，暴露依赖图解决导航与检索差异问题 | 解决智能体在大规模代码库中发现架构关键文件失败问题 | 代码智能导航 |
| 36 | http://arxiv.org/abs/2602.20426v1 | Learning to Rewrite Tool Descriptions for Reliable LLM-Agent Tool Use | 提出 Trace-Free+ 课程学习框架，优化工具接口描述与参数 schema | 解决工具接口人类导向成为智能体选择大量候选工具瓶颈问题 | 智能体工具使用 |
| 37 | http://arxiv.org/abs/2603.00214v1 | Agentic Scientific Simulation: Execution-Grounded Model Construction and Reconstruction | 提出执行接地解释 - 行动 - 验证循环，模拟器作为物理有效性权威仲裁者。 | 解决自然语言描述模拟模型固有未指定导致结果正确性及可复现性无法保证的问题。 | 科学模拟模型构建 |
| 38 | http://arxiv.org/abs/2603.00718v2 | SkillCraft: Can LLM Agents Learn to Use Tools Skillfully? | 引入 SkillCraft 基准，stress-test 代理形成与复用高层工具组合能力，提出轻量评估协议。 | 解决现有基准主要测量静态工具集下实例级成功，忽视可复用技能获取能力的问题。 | LLM 工具使用技能评估 |

[返回目录](#目录)

<a id="cat-08"></a>

## Agent规划与推理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2602.01335v1 | Beyond Pixels: Visual Metaphor Transfer via Schema-Driven Agentic Reasoning | 基于概念混合理论与模式语法的四Agent协作视觉隐喻迁移 | 生成AI仅像素级对齐无法捕捉抽象逻辑进行真正隐喻生成 | 视觉隐喻创意生成 |
| 2 | http://arxiv.org/abs/2602.01756v1 | Mind-Brush: Integrating Agentic Cognitive Search and Reasoning into Image Generation | 统一Agent框架模拟人类思考研究创建范式主动检索多模态证据 | 现有模型静态解码无法理解隐式意图与复杂知识推理 | 知识驱动图像生成 |
| 3 | http://arxiv.org/abs/2602.02995v1 | Agent Alpha: Tree Search Unifying Generation, Exploration and Evaluation for Computer-Use Agents | 步级MCTS统一生成/探索/评估，alpha-UCT引导搜索剪枝 | GUI Agent无法复用部分成功和从早期错误恢复 | 计算机使用Agent（OSWorld） |
| 4 | http://arxiv.org/abs/2602.03304v1 | To Search or Not to Search: Aligning the Decision Boundary of Deep Search Agents via Causal Intervention | 因果干预诊断+决策边界对齐，从因果反馈构建偏好数据集 | 深度搜索Agent无法准确判断何时停止搜索，过度/不足搜索 | 多轮基于Web的深度搜索Agent |
| 5 | http://arxiv.org/abs/2602.03432v1 | Failure is Feedback: History-Aware Backtracking for Agentic Traversal in Multimodal Graphs | 历史感知回溯机制+经济理性Agent工作流，成本感知遍历 | 现有方法依赖统一相似度度量，刚性预定义计划阻碍动态纠错 | 开放域多模态文档检索 |
| 6 | http://arxiv.org/abs/2602.02486v1 | RE-TRAC: REcursive TRAjectory Compression for Deep Search Agents | 跨轨迹探索框架，生成结构化状态表示指导后续 | 解决线性 ReAct 设计难以 revisit 早期状态问题 | 深度研究与搜索任务 |
| 7 | http://arxiv.org/abs/2602.02806v2 | De-Linearizing Agent Traces: Bayesian Inference of Latent Partial Orders for Efficient Execution | 贝叶斯框架从噪声线性 trace 推断潜在依赖偏序 | 解决顺序 action traces 掩盖潜在并发问题 | 云配置与科学工作流 |
| 8 | http://arxiv.org/abs/2602.07549v1 | When Is Enough Not Enough? Illusory Completion in Search Agents | 提出Epistemic Ledger评估框架追踪证据支持 | 搜索Agent多约束问题中过早认为任务完成 | 多跳和长视野基准的搜索Agent |
| 9 | http://arxiv.org/abs/2602.07773v1 | SRR-Judge: Step-Level Rating and Refinement for Enhancing Search-Integrated Reasoning in Search Agents | 步骤级评估框架，迭代拒绝采样微调增强深度搜索 | 主流方法仅用结果监督，忽略中间思维质量 | 复杂问答的深度搜索Agent |
| 10 | http://arxiv.org/abs/2602.07796v1 | Thinking Makes LLM Agents Introverted: How Mandatory Thinking Can Backfire in User-Engaged Agents | 发现强制思考使Agent更内向，缩短响应减少信息披露 | 显式思考在用户参与Agent场景中的效果不明 | 现实用户参与的LLM Agent |
| 11 | http://arxiv.org/abs/2602.07839v1 | TodoEvolve: Learning to Architect Agent Planning Systems | 元规划范式自主合成动态修订任务特定规划架构 | 现有方法依赖固定手工规划结构缺乏灵活性 | 开放端问题的复杂长视野任务 |
| 12 | http://arxiv.org/abs/2602.05327v1 | ProAct: Agentic Lookahead in Interactive Environments | 提出两阶段训练范式，使代理通过蒸馏和环境搜索内部化准确的前瞻推理。 | 解决 LLM 代理在需要长程规划的交互环境中因模拟未来状态误差累积而挣扎的问题。 | 交互式环境规划 |
| 13 | http://arxiv.org/abs/2602.05448v3 | BLITZRANK: Principled Zero-shot Ranking Agents with Tournament Graphs | 引入锦标赛图框架，通过聚合 k 项比较揭示的成对偏好进行原则性零样本排序。 | 解决现有方法要么依赖启发式要么效率低，无法充分利用每次比较信息的问题。 | LLM 文档重排序 |
| 14 | http://arxiv.org/abs/2602.05818v2 | TKG-Thinker: Towards Dynamic Reasoning over Temporal Knowledge Graphs via Agentic Reinforcement Learning | 提出具备自主规划和自适应检索能力的代理，通过双训练策略进行深度时序推理。 | 解决当前提示策略在复杂时序约束下易产生推理幻觉且缺乏动态交互优化的问题。 | 时序知识图谱问答 |
| 15 | http://arxiv.org/abs/2602.06034v2 | V-Retrver: Evidence-Driven Agentic Reasoning for Universal Multimodal Retrieval | 提出证据驱动检索框架，改革多模态检索为基于视觉检查的代理推理过程。 | 解决现有方法主要语言驱动，缺乏主动验证细粒度视觉证据导致推测性推理的问题。 | 多模态检索 |
| 16 | http://arxiv.org/abs/2603.03292v1 | From Conflict to Consensus: Boosting Medical Reasoning via Multi-Round Agentic RAG | 提出 MA-RAG，将语义冲突转化为查询，迭代优化推理历史。 | 解决医疗推理中 hallucination 和 outdated knowledge 风险问题。 | 医疗问答系统 |
| 17 | http://arxiv.org/abs/2602.06724v1 | Table-as-Search: Formulate Long-Horizon Agentic Information Seeking as Table Completion | 提出 TaS 框架，将信息寻求任务 reformulate 为表格补全任务。 | 解决长周期探索中搜索状态 tracking  fragile 的问题。 | 深度信息搜索 |
| 18 | http://arxiv.org/abs/2602.11114v1 | Learning to Compose for Cross-domain Agentic Workflow Generation | 内部化分解 - 重组 - 决策机制，单次传递生成任务特定工作流 | 域 shift 下工作流 refinement 迭代成本高且不稳定 | 跨域智能体工作流生成 |
| 19 | http://arxiv.org/abs/2602.11416v1 | Optimizing Agent Planning for Security and Autonomy | 设计安全感知智能体，显式规划任务进度与策略合规 | 间接提示注入攻击威胁执行 consequential 动作的智能体 | 安全与自主性优化的智能体 |
| 20 | http://arxiv.org/abs/2602.11499v1 | What if Agents Could Imagine? Reinforcing Open-Vocabulary HOI Comprehension through Generation | 构建认知地图建模实体与动作关系，动态调用工具 enrich 视觉证据 | 开放词汇人机交互推理受跨模态幻觉和遮挡限制 | 多模态视觉理解智能体 |
| 21 | http://arxiv.org/abs/2602.11541v1 | Budget-Constrained Agentic Large Language Models: Intention-Based Planning for Costly Tool Use | 利用意图感知分层世界模型 anticipate 未来工具使用和风险校准成本 | 预算约束下直接规划因状态动作空间巨大而不可行 | 预算约束工具增强智能体 |
| 22 | http://arxiv.org/abs/2602.14456v1 | Traceable Latent Variable Discovery Based on Multi-Agent Collaboration | 多LLM协作推断潜在变量，建模为不完全信息博弈 | 传统因果发现缺乏高质量数据，忽略潜在变量语义 | 医疗患者数据集因果发现 |
| 23 | http://arxiv.org/abs/2602.08586v2 | PRISM: A Principled Framework for Multi-Agent Reasoning via Gain Decomposition | 将多智能体推理增益分解为探索、信息与聚合三维。 | 解决多智能体协作缺乏原则性指导与优化目标不明问题。 | 多智能体推理系统 |
| 24 | http://arxiv.org/abs/2602.08603v1 | OSCAR: Optimization-Steered Agentic Planning for Composed Image Retrieval | 将组合图像检索重构为轨迹优化问题，离线推导最优路径。 | 解决启发式代理检索编排次优与试错成本高的问题。 | 组合图像检索 |
| 25 | http://arxiv.org/abs/2602.13769v2 | OR-Agent: Bridging Evolutionary Search and Structured Research for Automated Algorithm Discovery | 统一进化选择与研究树探索，引入分层优化启发式反思系统 | 解决复杂实验领域自动化发现缺乏结构化假设管理的问题 | 自动化算法发现 |
| 26 | http://arxiv.org/abs/2602.13807v1 | AnomaMind: Agentic Time Series Anomaly Detection with Tool-Augmented Reasoning | 重构异常检测为序列决策，混合推理机制结合工具交互与自反思 | 解决现有方法缺乏自适应特征准备及迭代推理导致上下文依赖弱问题 | 时间序列异常检测 |
| 27 | http://arxiv.org/abs/2602.14033v1 | BRAIN: Bayesian Reasoning via Active Inference for Agentic and Embodied Intelligence in Mobile Networks | 利用深度生成模型最小化变分自由能，统一感知与行动闭环范式 | 解决传统 DRL 代理缺乏可解释性及非平稳条件下适应 brittle 问题 | 移动网络资源分配 |
| 28 | http://arxiv.org/abs/2602.14234v1 | REDSearcher: A Scalable and Cost-Efficient Framework for Long-Horizon Search Agents | 协同设计任务合成、中训练及后训练，工具增强查询鼓励主动工具使用 | 解决深度搜索任务高质量轨迹稀疏及交互 heavy rollouts 成本高的问题 | 长程搜索代理优化 |
| 29 | http://arxiv.org/abs/2602.16699v2 | Calibrate-Then-Act: Cost-Aware Exploration in LLM Agents | 引入 CTA 框架，使 LLM 显式推理成本 - 不确定性 tradeoffs | 解决多步任务中 LLM 何时停止探索并提交答案的决策问题 | 信息检索与编程任务 Agent |
| 30 | http://arxiv.org/abs/2602.09463v3 | SpotAgent: Grounding Visual Geo-localization in Large Vision-Language Models through Agentic Reasoning | 提出 SpotAgent 框架，通过 ReAct 图结合外部工具验证视觉线索，实现代理推理。 | 解决视觉地理定位中线索稀疏、模糊及模型幻觉问题，提供可验证结果。 | 视觉地理定位 |
| 31 | http://arxiv.org/abs/2602.10538v2 | Why Agentic Theorem Prover Works: A Statistical Provability Theory of Mathematical Reasoning Models | 提出统计可证明性理论，形式化定理证明管道为时间 bounded MDPs。 | 解决 Agentic 定理证明器成功原因不明及经典证明搜索硬度问题。 | 数学推理模型 |
| 32 | http://arxiv.org/abs/2602.19000v2 | MagicAgent: Towards Generalized Agent Planning | 系列基础模型，通过两阶段训练范式实现通用 Agent 规划 | 解决多任务训练中梯度干扰及规划任务泛化困难问题 | 通用 Agent 规划 |
| 33 | http://arxiv.org/abs/2602.19008v1 | Capable but Unreliable: Canonical Path Deviation as a Causal Mechanism of Agent Failure in Long-Horizon Tasks | 发现规范路径偏离是长程任务 Agent 失败的因果机制 | 解决 Agent 能力足够但可靠性因随机漂移失败的问题 | 长程工具使用任务 |
| 34 | http://arxiv.org/abs/2602.19633v1 | TAPE: Tool-Guided Adaptive Planning and Constrained Execution in Language Model Agents | 工具引导自适应规划，聚合计划为图并用外部求解器找可行路径 | 解决智能体在严格约束环境下规划不完美与执行随机性问题 | 语言模型智能体 |
| 35 | http://arxiv.org/abs/2602.22675v2 | Search More, Think Less: Rethinking Long-Horizon Agentic Search for Efficiency and Generalization | 用并行证据获取替代顺序推理，提升效率 | 解决深度研究代理推理过深导致成本高泛化难的问题 | 长程搜索与研究代理 |
| 36 | http://arxiv.org/abs/2602.23668v1 | PseudoAct: Leveraging Pseudocode Synthesis for Flexible Planning and Action Control in Large Language Model Agents | 通过伪代码合成结构化计划，显式编码控制流，减少冗余动作与无限循环。 | 解决反应式决策在复杂长视野任务中导致工具使用冗余及推理不稳定的问题。 | 长视野任务规划代理 |

[返回目录](#目录)

<a id="cat-09"></a>

## 人机协作Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2602.01405v1 | Feedback by Design: Understanding and Overcoming User Feedback Barriers in Conversational Agents | 识别四大反馈障碍并提出三设计期望与支架系统 | 人类对AI反馈频率低质量差阻碍有效人机交互 | 对话Agent用户反馈设计 |
| 2 | http://arxiv.org/abs/2602.01415v1 | Evidence-Decision-Feedback: Theory-Driven Adaptive Scaffolding for LLM Agents | EDF理论框架整合证据推理、教学决策与自适应反馈 | 多Agent架构一刀切无法提供个性化学习支持 | STEM+C问题求解教学Agent |
| 3 | http://arxiv.org/abs/2602.01918v2 | When Workout Buddies Are Virtual: AI Agents and Human Peers in a Longitudinal Physical Activity Study | 揭示 AI 同伴与人类同伴在运动激励中的互补优势 | 探索虚拟同伴对长期运动动机的影响 | 健康与体育活动激励 |
| 4 | http://arxiv.org/abs/2602.04104v1 | Making Videos Accessible for Blind and Low Vision Users Using a Multimodal Agent Video Player | 多模态代理视频播放器，交互式无障碍 | 视频内容对视障用户不可访问 | 视障用户/视频无障碍 |
| 5 | http://arxiv.org/abs/2602.05016v2 | From Fragmentation to Integration: Exploring the Design Space of AI Agents for Human-as-the-Unit Privacy Management | 提出“人以单位”视角，设计 AI 代理弥合隐私管理碎片，实现自动化事后补救。 | 解决跨平台数字足迹管理困难，缺乏综合隐私控制的问题。 | 隐私管理用户 |
| 6 | http://arxiv.org/abs/2602.05111v1 | Metacognitive Demands and Strategies While Using Off-The-Shelf AI Conversational Agents for Health Information | 识别使用现成对话代理寻求健康信息时的元认知需求及用户应对策略。 | 解决高元认知需求损害用户健康信息寻求体验的问题。 | 健康信息寻求用户 |
| 7 | http://arxiv.org/abs/2602.05721v2 | A Dual-Loop Agent Framework for Automated Vulnerability Reproduction | 提出基于 LLM 的双循环代理框架，匹配补救措施与失败类型以逃避无效调试。 | 解决现有方法混淆探索攻击方向与修复实现细节，导致无效调试循环的问题。 | 软件漏洞复现 |
| 8 | http://arxiv.org/abs/2602.05987v1 | From Human-Human Collaboration to Human-Agent Collaboration: A Vision, Design Philosophy, and an Empirical Framework for Achieving Successful Partnerships Between Humans and LLM Agents | 建立基础研究议程，探讨远程人类协作理解如何启发人类 - 代理协作设计。 | 解决 LLM 代理成为真正协作者时，缺乏共享词汇和研究议程指导未来探索的问题。 | 人机协作研究 |
| 9 | http://arxiv.org/abs/2602.06134v1 | Hear You in Silence: Designing for Active Listening in Human Interaction with Conversational Agents Using Context-Aware Pacing | 设计上下文感知 pacing 策略，模拟人类对话中的主动倾听 temporal cues。 | 解决对话 Agent 缺乏 nuanced  temporal  cues 导致互动不自然的问题。 | 对话式 Agent 交互 |
| 10 | http://arxiv.org/abs/2602.06714v1 | PrefIx: Understand and Adapt to User Preference in Human-Agent Interaction | 提出 Interaction-as-a-Tool 范式，评估并适应用户交互偏好。 | 解决 Agent 任务准确但交互模式 frustrate 用户的问题。 | 人机交互体验 |
| 11 | http://arxiv.org/abs/2602.07142v1 | Exploring Teachers' Perspectives on Using Conversational AI Agents for Group Collaboration | 研究教师对 voice-based 协作 Agent 的看法，识别设计 tensions。 | 解决 AI 在 mediating 面对面小组协作中角色不明确的问题。 | K12 教育协作 |
| 12 | http://arxiv.org/abs/2602.07283v1 | Mapping the Design Space of User Experience for Computer Use Agents | 构建 UX 设计 taxonomy，映射 computer use Agent 的设计空间。 | 解决缺乏关于用户如何与 computer use Agent 交互的知识的问题。 | 计算机使用 Agent |
| 13 | http://arxiv.org/abs/2602.11055v1 | GenFaceUI: Meta-Design of Generative Personalized Facial Expression Interfaces for Intelligent Agents | 提出生成式个性化面部表情接口框架，组织规则 bounded 空间 | 运行时面部表情生成的控制、一致性和对齐挑战 | 智能体面部表情交互界面 |
| 14 | http://arxiv.org/abs/2602.11483v1 | Understanding Persuasive Interactions between Generative Social Agents and Humans: The Knowledge-based Persuasion Model (KPM) | 提出基于知识的说服模型，GSA 知识驱动说服行为 | 缺乏关于 GSA 交互的理论化及影响用户态度行为指南 | 生成式社会智能体与人类交互 |
| 15 | http://arxiv.org/abs/2602.08368v1 | T2VTree: User-Centered Visual Analytics for Agent-Assisted Thought-to-Video Authoring | 提出树状可视化分析系统，支持可编辑的智能体规划。 | 解决视频创作中中间决策难管理、比较与复用问题。 | 视频创作与人机协作 |
| 16 | http://arxiv.org/abs/2602.08565v1 | Agent-Supported Foresight for AI Systemic Risks: AI Agents for Breadth, Experts for Judgment | 提出混合预见工作流，Agent  broaden 覆盖，人类提供判断。 | 解决人类判断在长期系统风险预测中知识稀缺问题。 | AI 系统风险评估 |
| 17 | http://arxiv.org/abs/2602.09286v1 | Human Control Is the Anchor, Not the Answer: Early Divergence of Oversight in Agentic AI Communities | 比较不同社区对智能体监督期望的早期分歧。 | 解决单一“人类控制”目标无法匹配不同智能体角色问题。 | 智能体监督机制设计 |
| 18 | http://arxiv.org/abs/2602.09310v1 | A11y-CUA Dataset: Characterizing the Accessibility Gap in Computer Use Agents | 提供 A11y-CUA 数据集，表征计算机使用智能体的无障碍差距。 | 解决 CUA 未反映盲人或低视力用户交互风格的问题。 | 无障碍计算机使用智能体 |
| 19 | http://arxiv.org/abs/2602.13622v1 | The Shadow Boss: Identifying Atomized Manipulations in Agentic Employment of XR Users using Scenario Constructions | 分析 XR 作为控制表面下的代理雇佣风险，识别认知去技能化向量 | 解决代理雇佣模式下人类沦为生物执行器的伦理与操控风险 | XR 环境下的劳动关系 |
| 20 | http://arxiv.org/abs/2602.13832v1 | Beyond Words: Evaluating and Bridging Epistemic Divergence in User-Agent Interaction via Theory of Mind | 形式化 ToM 为认知差异检测机制，构建轨迹数据集训练模型推理用户状态 | 解决 LLM 难以理解模糊意图导致用户信念与环境状态分歧的问题 | 用户代理交互理解 |
| 21 | http://arxiv.org/abs/2602.15569v2 | What Are You Doing? Effects of Intermediate Feedback from Agentic LLM In-Car Assistants During Multi-Step Processing | 提出中间反馈机制，显著提升用户对车载 Agent 的信任与体验 | 解决多步任务中用户感知速度慢、信任度低的问题 | 车载语音助手与驾驶员 |
| 22 | http://arxiv.org/abs/2602.16173v1 | Learning Personalized Agents from Human Feedback | 提出 PAHF 框架，通过显式记忆在线学习用户偏好 | 解决 Agent 难以对齐个体用户动态变化偏好的问题 | 个性化 embodied 与购物 Agent |
| 23 | http://arxiv.org/abs/2602.16844v1 | Overseeing Agents Without Constant Oversight: Challenges and Opportunities | 研究人类验证 Agent  traces 的效用与设计替代方案 | 解决人类监督 Agent 时信息过载与 verification 效率低问题 | 计算机用户 Agent 与人机验证 |
| 24 | http://arxiv.org/abs/2602.17084v1 | How AI Coding Agents Communicate: A Study of Pull Request Description Characteristics and Human Review Responses | 实证分析 AI 编码代理的 PR 描述特征及人类审查响应。 | AI 代理在 PR 描述风格及人类交互动态上的差异未 explored。 | 人机协作软件开发 |
| 25 | http://arxiv.org/abs/2602.17185v1 | The Bots of Persuasion: Examining How Conversational Agents' Linguistic Expressions of Personality Affect User Perceptions and Decisions | 研究对话代理语言表达的人格如何影响用户决策和感知。 | 代理人格投射如何影响用户尚不清楚，存在操纵风险。 | 慈善捐赠场景 |
| 26 | http://arxiv.org/abs/2602.17221v1 | From Labor to Collaboration: A Methodological Experiment Using AI Agents to Augment Research Perspectives in Taiwan's Humanities and Social Sciences | 提出人机协作研究工作流程，验证人文社科研究方法。 | 现有研究多聚焦软件工程，缺乏人文社科方法论探索。 | 人文社科研究 |
| 27 | http://arxiv.org/abs/2602.17588v2 | Modeling Distinct Human Interaction in Web Agents | 建模人类干预以支持协作 Web 任务执行，预测干预时机。 | 当前系统缺乏对人类何时及为何干预的原则性理解。 | Web 导航代理 |
| 28 | http://arxiv.org/abs/2602.17864v1 | Exploring The Impact Of Proactive Generative AI Agent Roles In Time-Sensitive Collaborative Problem-Solving Tasks | 研究主动生成式 AI 代理角色在时间敏感协作任务中的影响。 | 不了解主动代理如何影响实时共同定位团队动态。 | 协作问题解决 |
| 29 | http://arxiv.org/abs/2602.10535v1 | Exploring the Interplay Between Voice, Personality, and Gender in Human-Agent Interactions | 评估参与者从人工声音感知人格特质，探索用户 -Agent 人格及性别同步。 | 解决设计有效人机交互时缺乏对影响感知及 rapport-building 特征识别的问题。 | 人机交互设计 |
| 30 | http://arxiv.org/abs/2602.18891v1 | Orchestrating LLM Agents for Scientific Research: A Pilot Study of Multiple Choice Question (MCQ) Generation and Evaluation | 混合方法评估人类协调多 LLM Agent 进行科学研究工作流 | 解决 AI 重塑科研活动的实证证据缺乏及劳动转移问题 | 科学研究工作流 |
| 31 | http://arxiv.org/abs/2602.18962v2 | NeuroWise: A Multi-Agent LLM "Glass-Box" System for Practicing Double-Empathy Communication with Autistic Partners | 多智能体 LLM coaching 系统，支持神经典型用户与自闭伙伴沟通 | 解决双重共情问题中神经典型用户归因偏差及沟通低效问题 | 神经多样性沟通辅导 |
| 32 | http://arxiv.org/abs/2602.19016v1 | Who Has the Final Word? Designing Multi-Agent Collaborative Framework for Professional Translators | 提出 CHORUS 人机多智能体协作翻译框架，基于 MQM 质量指标 | 解决专业翻译中多维度决策难以自动化及缺乏结构化支持问题 | 专业翻译工作流 |
| 33 | http://arxiv.org/abs/2602.19441v1 | When AI Teammates Meet Code Review: Collaboration Signals Shaping the Integration of Agent-Authored Pull Requests | 实证研究智能体 PR 集成，发现审查者参与度与集成成功率强相关 | 解决智能体代码贡献在人类审查工作流中的集成与协作问题 | 软件工程/代码审查 |
| 34 | http://arxiv.org/abs/2602.20486v1 | Hybrid LLM-Embedded Dialogue Agents for Learner Reflection: Designing Responsive and Theory-Driven Interactions | 混合对话系统，将 LLM 响应嵌入理论对齐的规则框架支持反思 | 解决纯规则系统僵化与纯 LLM 缺乏 pedagogical 理论对齐问题 | 教育/学习者反思 |
| 35 | http://arxiv.org/abs/2602.21889v1 | 2-Step Agent: A Framework for the Interaction of a Decision Maker with AI Decision Support | 使用贝叶斯方法建模预测如何影响理性代理信念及下游决策。 | 解决缺乏理解 AI 辅助决策采用效果及先验信念错位风险问题。 | 人类决策支持系统 |
| 36 | http://arxiv.org/abs/2602.22070v1 | Language Models Exhibit Inconsistent Biases Towards Algorithmic Agents and Human Experts | 评估 LLM 在委托任务时对人类专家与算法代理的信任权重。 | 解决 LLM 在高风险场景中对人类与算法存在不一致偏见问题。 | LLM 决策任务 |
| 37 | http://arxiv.org/abs/2602.22077v2 | ViSTAR: Virtual Skill Training with Augmented Reality with 3D Avatars and LLM coaching agent | 通过视觉覆盖与 AI 教练代理提供平衡姿势 timing 反馈。 | 解决自主篮球技能练习中理解技能识别错误及纠正困难问题。 | 虚拟技能训练系统 |
| 38 | http://arxiv.org/abs/2602.22362v1 | E3VA: Enhancing Emotional Expressiveness in Virtual Conversational Agents | 利用情感分析 NLP  informing 生成 empathetic 表达响应。 | 解决虚拟对话代理情感表达有限导致用户体验不佳问题。 | 虚拟对话代理 |
| 39 | http://arxiv.org/abs/2602.22401v3 | Vibe Researching as Wolf Coming: Can AI Agents with Skills Replace or Augment Social Scientists? | 提出 vibe researching 概念，分类研究活动 codifiability 与 tacit 知识。 | 解决 AI 代理在社会科学中理论原创性及 tacit 领域知识 struggle 问题。 | 社会科学研究 |
| 40 | http://arxiv.org/abs/2602.22546v1 | Requesting Expert Reasoning: Augmenting LLM Agents with Learned Collaborative Intervention | 学习策略将人类专家作为交互式推理工具 | 解决长尾知识缺失导致代理在专业领域失败的问题 | 人机协作专业任务 |
| 41 | http://arxiv.org/abs/2603.00522v1 | SIAgent: Spatial Interaction Agent via LLM-powered Eye-Hand Motion Intent Understanding in VR | 提出“意图到操作”框架，允许用户通过自然眼手运动表达交互意图。 | 解决现有范式需用户学习预定义手势及记忆多手势任务关联增加学习成本的问题。 | VR 空间交互界面 |
| 42 | http://arxiv.org/abs/2603.00774v1 | Structure Matters: Evaluating Multi-Agents Orchestration in Generative Therapeutic Chatbots | 调查不同 LLM 设计如何塑造感知治疗对话，比较三架构变体在 SAT 聊天机器人中表现。 | 解决有效心理治疗需结构化进展及 adherence 临床协议使聊天机器人设计具挑战的问题。 | 生成性治疗聊天机器人 |

[返回目录](#目录)

<a id="cat-10"></a>

## Agent学习与自进化

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2602.01550v2 | S1-NexusAgent: a Self-Evolving Agent Framework for Multidisciplinary Scientific Research | 双环架构分离全局规划与子任务执行实现持续自进化 | 现有Agent长程规划、目标维持与执行持续学习能力有限 | 多学科科学研究工作流 |
| 2 | http://arxiv.org/abs/2602.03219v2 | Beyond Quantity: Trajectory Diversity Scaling for Code Agents | 轨迹多样性扩展框架，业务聚类+蓝图驱动+自适应演化机制 | 代码Agent泛化受低质量合成数据和数量扩展收益递减限制 | 代码Agent工具使用基准 |
| 3 | http://arxiv.org/abs/2602.03279v1 | Agentic Proposing: Enhancing Large Language Model Reasoning via Compositional Skill Synthesis | 目标驱动序列决策过程，Agent动态选择组合模块化推理技能 | 人类标注成本高，现有合成范式在结构有效性和问题复杂度间权衡 | 数学/编码/科学推理训练数据 |
| 4 | http://arxiv.org/abs/2602.03411v2 | SWE-Master: Unleashing the Potential of Software Engineering Agents via Post-Training | 系统探索完整Agent开发管道，教师轨迹合成+长程SFT+RL | 开源基线模型初始SWE能力有限，需要系统优化方法 | 软件工程Agent（SWE-bench Verified） |
| 5 | http://arxiv.org/abs/2602.03412v1 | Verified Critical Step Optimization for LLM Agents | 聚焦已验证关键步骤的偏好学习，从失败轨迹直接定位弱点 | 结果奖励无法精确归因中间步骤，步级奖励引入噪声 | 长程复杂任务LLM Agent后训练 |
| 6 | http://arxiv.org/abs/2602.03419v1 | SWE-World: Building Software Engineering Agents in Docker-Free Environments | Docker-free框架，LLM代理预测执行结果替代物理容器环境 | 容器化环境资源密集难以维护，限制Agent训练可扩展性 | 软件工程Agent训练评估 |
| 7 | http://arxiv.org/abs/2602.03468v1 | IntentRL: Training Proactive User-intent Agents for Open-ended Deep Research via Reinforcement Learning | 浅-深意图细化图扩展种子样本+两阶段RL策略 | 深度研究计算昂贵，高自主性在模糊查询上导致执行过长结果不满 | 开放深度研究Agent用户意图澄清 |
| 8 | http://arxiv.org/abs/2602.03548v1 | SEAD: Self-Evolving Agent for Multi-Turn Service Dialogue | 解耦用户建模为Profile控制器+用户角色扮演模型，提供自适应训练场景 | 服务对话依赖噪声低质量人类数据，难以模拟真实目标导向用户行为 | 多轮服务对话Agent |
| 9 | http://arxiv.org/abs/2602.03664v2 | Mitigating Conversational Inertia in Multi-Turn Agents | 发现对话惯性现象，上下文偏好学习校准模型偏好低惯性响应 | 长上下文丰富反馈但放大惯性削弱探索，模仿 bias约束探索 | 多轮Agent环境 |
| 10 | http://arxiv.org/abs/2602.01966v1 | Self-Consolidation for Self-Evolving Agents | 对比反思策略与自巩固机制，将经验蒸馏为参数 | 解决仅检索成功轨迹忽略失败价值及上下文爆炸问题 | 终身交互的智能体进化 |
| 11 | http://arxiv.org/abs/2602.02051v1 | SIDiffAgent: Self-Improving Diffusion Agent | 训练-free 框架，自主管理提示工程与伪影修正 | 解决扩散模型对提示敏感及生成不一致问题 | 文本到图像生成任务 |
| 12 | http://arxiv.org/abs/2602.02170v1 | Self-Evolving Coordination Protocol in Multi-Agent AI Systems: An Exploratory Systems Feasibility Study | 允许有限外部验证自修改的协调协议可行性研究 | 探索安全关键领域中协调逻辑的受控自演化 | 金融等 regulated 领域 |
| 13 | http://arxiv.org/abs/2602.02369v1 | Live-Evo: Online Evolution of Agentic Memory from Continuous Feedback | 在线自进化记忆系统，从数据流中学习 | 解决静态基准近似在线学习导致分布 shift 脆弱问题 | 连续反馈环境任务 |
| 14 | http://arxiv.org/abs/2602.02709v2 | ATLAS : Adaptive Self-Evolutionary Research Agent with Task-Distributed Multi-LLM Supporters | 任务分布式框架，迭代开发轻量研究智能体 | 解决长程任务中静态偏好优化循环不可行问题 | 科学研究与超参调优 |
| 15 | http://arxiv.org/abs/2602.03719v1 | Training Multi-Turn Search Agent via Contrastive Dynamic Branch Sampling | 分支相对策略优化，无价值对比监督 | 长程设置中稀疏奖励的学习挑战 | 搜索智能体训练 |
| 16 | http://arxiv.org/abs/2602.04248v1 | Empirical-MCTS: Continuous Agent Evolution via Dual-Experience Monte Carlo Tree Search | 双循环框架，将无状态搜索转为连续学习 | 当前 MCTS 丢弃成功推理模式 | 复杂推理任务 |
| 17 | http://arxiv.org/abs/2602.04284v1 | Agent-Omit: Training Efficient LLM Agents for Adaptive Thought and Observation Omission via Agentic Reinforcement Learning | 统一训练框架，自适应省略冗余思考 | 现有研究同等对待所有交互轨迹 | 高效代理训练 |
| 18 | http://arxiv.org/abs/2602.04737v1 | Rationality Measurement and Theory for Reinforcement Learning Agents | 提出理性度量 suite 及相关理论 | 部署中代理理性属性 rarely explored | 强化学习代理理论 |
| 19 | http://arxiv.org/abs/2602.04837v1 | Group-Evolving Agents: Open-Ended Self-Improvement via Experience Sharing | 群体进化代理，组内经验共享复用 | 预定义架构限制能力超越 | 代理自进化/编码 |
| 20 | http://arxiv.org/abs/2602.07755v1 | Learning to Continually Learn via Meta-learning Agentic Memory Designs | ALMA框架元学习记忆设计替代手工设计 | 现有记忆设计固定，难以适应任务多样性和非平稳性 | 长视野推理和适应的Agent系统 |
| 21 | http://arxiv.org/abs/2602.08222v1 | Weak-Driven Learning: How Weak Agents make Strong Agents Stronger | WMSS范式利用弱检查点指导继续优化突破饱和瓶颈 | 模型高度自信后进一步训练收益递减 | LLM后训练优化 |
| 22 | http://arxiv.org/abs/2602.08234v1 | SkillRL: Evolving Agents via Recursive Skill-Augmented Reinforcement Learning | SkillRL框架自动技能发现和递归进化，构建层次技能库 | 现有记忆方法存储原始轨迹冗余噪声重 | 复杂任务的LLM Agent泛化 |
| 23 | http://arxiv.org/abs/2602.05429v1 | M$^2$-Miner: Multi-Agent Enhanced MCTS for Mobile GUI Agent Data Mining | 提出基于 MCTS 的低成本自动化移动 GUI 代理数据挖掘框架，增强意图多样性。 | 解决手动标注和当前数据挖掘方法成本高、质量差、 richness 低的问题。 | 移动 GUI 代理训练 |
| 24 | http://arxiv.org/abs/2602.05810v1 | Bifrost: Steering Strategic Trajectories to Bridge Contextual Gaps for Self-Improving Agents | 揭示上下文 - 轨迹相关性，利用上下文差异指导已解决轨迹适应目标任务。 | 解决跨任务转移引入上下文不匹配，导致现有方法丢弃轨迹或启发式操纵的问题。 | 自改进代理 |
| 25 | http://arxiv.org/abs/2602.05829v1 | Weaver: End-to-End Agentic System Training for Video Interleaved Reasoning | 提出端到端可训练多模态推理代理系统，动态调用工具获取视觉线索。 | 解决文本中心链式思维方法 suffer 表征不匹配且受限于感知敏锐度的问题。 | 视频推理任务 |
| 26 | http://arxiv.org/abs/2602.05842v2 | Reinforcement World Model Learning for LLM-based Agents | 提出自监督方法学习基于文本状态的动作条件世界模型，对齐模拟与现实状态。 | 解决 LLM 在代理设置中难以 anticipate 行动后果和适应环境动态的问题。 | LLM 代理世界模型 |
| 27 | http://arxiv.org/abs/2602.05848v1 | DARWIN: Dynamic Agentically Rewriting Self-Improving Network | 利用遗传算法优化结构，GPT 代理相互修改训练代码以突变方式提升性能。 | 解决基础 GPT 训练扩展需要自动化优化和持续改进机制的问题。 | 进化 GPT 训练 |
| 28 | http://arxiv.org/abs/2602.06485v1 | AgentCPM-Explore: Realizing Long-Horizon Deep Exploration for Edge-Scale Agents | 提出 holistic 训练框架，解决 edge-scale 模型遗忘和推理退化问题。 | 解决 edge-scale 模型在长周期任务中 inference 稳定性差的问题。 | 边缘计算 Agent |
| 29 | http://arxiv.org/abs/2603.03293v1 | SE-Search: Self-Evolving Search Agent via Memory and Dense Reward | 提出 Think-Search-Memorize 策略，利用 dense rewards 优化搜索行为。 | 解决搜索 Agent 积累 noise 文档和依赖 sparse RL 信号的问题。 | 信息检索与问答 |
| 30 | http://arxiv.org/abs/2602.07187v1 | PreFlect: From Retrospective to Prospective Reflection in Large Language Model Agents | 提出 PreFlect，在执行前批评和 refine 计划，支持 prospective reflection。 | 解决现有 reflection 仅 post hoc  correction 效率低的问题。 | 复杂现实世界任务 |
| 31 | http://arxiv.org/abs/2602.10986v1 | TVCACHE: A Stateful Tool-Value Cache for Post-Training LLM Agents | 维护工具调用序列树，基于最长前缀匹配进行状态感知缓存 | 强化学习后训练中工具调用耗时导致 GPU 闲置 | LLM 智能体后训练优化 |
| 32 | http://arxiv.org/abs/2602.11351v1 | Pushing Forward Pareto Frontiers of Proactive Agents with Behavioral Agentic Optimization | 结合行为增强与正则化，平衡任务性能与用户参与度 | 被动智能体无法适应用户意图，过度反馈降低满意度 | 主动式用户中心 LLM 智能体 |
| 33 | http://arxiv.org/abs/2602.11524v1 | Adaptive Milestone Reward for GUI Agents | 提出自适应里程碑奖励机制，锚定轨迹到动态蒸馏的里程碑 | 长视野任务中的时间信用分配问题 | 移动 GUI 智能体强化学习 |
| 34 | http://arxiv.org/abs/2602.11551v1 | SIGHT: Reinforcement Learning with Self-Evidence and Information-Gain Diverse Branching for Search Agent | 提炼高保真证据，计算信息增益指导动态提示干预和分支 | 多轮搜索场景中结果冗余和低信噪比导致隧道视野 | 自主搜索问答智能体 |
| 35 | http://arxiv.org/abs/2602.11767v2 | TSR: Trajectory-Search Rollouts for Multi-Turn RL of LLM Agents | 训练时 repurpose 测试时 scaling ideas，轻量树式搜索构建高质量轨迹 | 多轮 RL 中奖励稀疏或延迟，naive 轨迹采样阻碍 exploitation | 多轮 LLM 智能体强化学习 |
| 36 | http://arxiv.org/abs/2602.11931v1 | AdaptEvolve: Improving Efficiency of Evolutionary AI Agents through Adaptive Model Selection | 利用内在生成 confidence 估计实时 solvability，动态选择 LLM | 进化 agentic 系统中计算效率与推理能力的 trade-off | 进化 AI 智能体 |
| 37 | http://arxiv.org/abs/2602.14477v1 | When OpenClaw AI Agents Teach Each Other: Peer Learning Patterns in the Moltbook Community | 首次实证刻画AI Agent间同伴学习行为模式 | AI Agent社区中同伴学习机制缺乏实证研究 | AI Agent教育社区 |
| 38 | http://arxiv.org/abs/2602.14670v1 | FactorMiner: A Self-Evolving Agent with Skills and Experience Memory for Financial Alpha Discovery | 模块化技能架构+结构化经验记忆的自进化Agent | 公式化Alpha因子挖掘搜索空间大，冗余度高 | 量化投资因子发现 |
| 39 | http://arxiv.org/abs/2602.08533v2 | Dialogue Model Optimization via Agent Game and Adaptive Tree-based GRPO | 结合在线个性化与自适应树基 GRPO 优化对话模型。 | 解决对话 RL 依赖预收集数据及忽视长期价值问题。 | 开放域对话代理 |
| 40 | http://arxiv.org/abs/2602.09138v1 | PABU: Progress-Aware Belief Update for Efficient LLM Agents | 提出进度感知信念更新框架，选择性保留历史信息。 | 解决全历史条件化导致冗余动作与高推理成本问题。 | 高效 LLM 智能体 |
| 41 | http://arxiv.org/abs/2602.09372v1 | AgentSkiller: Scaling Generalist Agent Intelligence through Semantically Integrated Cross-Domain Data Synthesis | 提出全自动框架，合成跨域语义链接的多轮交互数据。 | 解决通用智能体缺乏高质量长程数据阻碍能力扩展问题。 | 通用智能体数据合成 |
| 42 | http://arxiv.org/abs/2602.13653v1 | Building Autonomous GUI Navigation via Agentic-Q Estimation and Step-Wise Policy Optimization | 提出 Agentic-Q 估计与逐步策略优化，解耦策略更新与环境 | 解决 GUI 代理在非平稳环境中数据策展成本高及策略优化不稳定问题 | 图形界面自主导航 |
| 43 | http://arxiv.org/abs/2602.14093v1 | GUI-GENESIS: Automated Synthesis of Efficient Environments with Verifiable Rewards for GUI Agent Post-Training | 自动合成轻量 Web 环境及代码原生奖励，消除视觉估计噪声 | 解决真实应用训练高延迟、不可复现及奖励不可验证的问题 | GUI 代理后训练环境 |
| 44 | http://arxiv.org/abs/2602.14225v1 | Text Before Vision: Staged Knowledge Injection Matters for Agentic RLVR in Ultra-High-Resolution Remote Sensing Understanding | 提出分阶段知识注入，文本 QA 冷启动 instill 推理结构指导视觉检索 | 解决多模态推理受限于视觉证据获取及标准 RL 难以导航 vast 视觉空间问题 | 超高分辨率遥感理解 |
| 45 | http://arxiv.org/abs/2602.15816v1 | Developing AI Agents with Simulated Data: Why, what, and how? | 介绍基于仿真的合成数据生成框架，用于 AI 训练 | 解决现代 subsymbolic AI 数据 volume 与 quality 不足的问题 | AI 训练数据生成与数字孪生 |
| 46 | http://arxiv.org/abs/2602.16738v1 | Self-Evolving Multi-Agent Network for Industrial IoT Predictive Maintenance | 构建自进化分层多 Agent 系统，分布 Edge-Fog-Cloud  tiers | 解决工业 IoT 预测性维护中实时性与可解释性平衡问题 | 工业 IoT 预测性维护系统 |
| 47 | http://arxiv.org/abs/2602.16165v1 | HiPER: Hierarchical Reinforcement Learning with Explicit Credit Assignment for Large Language Model Agents | 提出分层计划执行 RL 框架，显式分离规划与执行信用分配 | 解决长 horizon 任务中稀疏奖励导致信用分配低效问题 | 多轮决策 LLM Agent 训练 |
| 48 | http://arxiv.org/abs/2602.16819v1 | Hybrid-Gym: Training Coding Agents to Generalize Across Tasks | 构建 Hybrid-Gym 环境，训练 coding Agent 泛化 transferable skills | 解决 coding Agent 基准单一且缺乏跨任务泛化能力问题 | 代码生成 Agent 训练与泛化 |
| 49 | http://arxiv.org/abs/2602.17038v2 | Phase-Aware Mixture of Experts for Agentic Reinforcement Learning | 提出阶段感知混合专家模型，学习潜在阶段边界分配专家。 | 单一策略网络导致简单任务主导参数，复杂任务容量不足。 | 智能体强化学习 |
| 50 | http://arxiv.org/abs/2602.17547v1 | KLong: Training LLM Agent for Extremely Long-horizon Tasks | 提出轨迹分裂 SFT 和渐进式 RL 训练极长程任务代理。 | 现有模型难以解决极长程任务，训练数据稀缺。 | 长程任务解决 |
| 51 | http://arxiv.org/abs/2603.03329v1 | AutoHarness: improving LLM agents by automatically synthesizing a code harness | 演示 Agent 自动合成代码 harness 防止非法动作，甚至生成完整策略代码。 | 解决 LLM Agent 执行禁止动作导致失败的问题，提升小模型性能超越大模型。 | 游戏/策略执行 |
| 52 | http://arxiv.org/abs/2602.09892v3 | Immersion in the GitHub Universe: Scaling Coding Agents to Mastery | 提出 ScaleSWE 工作流，自动化构建高质量软件工程数据以训练 Coding Agent。 | 解决现实软件工程任务训练数据稀缺问题，提升 Agent 解决率至 64%。 | 软件工程 |
| 53 | http://arxiv.org/abs/2602.10090v2 | Agent World Model: Infinity Synthetic Environments for Agentic Reinforcement Learning | 提出 Agent World Model 管道，生成 1000 个代码驱动合成环境用于 Agent 训练。 | 解决 Agent 训练缺乏多样可靠环境限制 scaling 的问题，实现强泛化。 | 多轮工具使用 Agent 训练 |
| 54 | http://arxiv.org/abs/2602.10226v1 | Self-Evolving Recommendation System: End-To-End Autonomous Model Optimization With LLM Agents | 利用 LLM Agent 自主生成、训练及部署模型变更，实现端到端自动优化。 | 解决大规模推荐系统优化依赖人工迭代问题，提升开发速度及模型性能。 | 视频平台推荐系统 |
| 55 | http://arxiv.org/abs/2602.10356v1 | Autonomous Continual Learning of Computer-Use Agents for Environment Adaptation | 引入 ACuRL 框架，通过课程任务生成器使 Agent 零人类数据持续适应环境。 | 解决计算机使用 Agent 在动态环境中缺乏高质量环境接地数据的问题。 | 计算机使用 Agent |
| 56 | http://arxiv.org/abs/2602.11210v3 | SWE-MiniSandbox: Container-Free Reinforcement Learning for Building Software Engineering Agents | 提出 SWE-MiniSandbox，无容器方法实现可扩展 RL 训练软件工程 Agent。 | 解决基于容器的 RL 管道存储开销大及环境设置慢的问题，降低资源需求。 | 软件工程 Agent 训练 |
| 57 | http://arxiv.org/abs/2602.11220v1 | Patch the Distribution Mismatch: RL Rewriting Agent for Stable Off-Policy SFT | 提出 RL 基于数据重写 Agent，优化重写分布以匹配骨干 QA 风格生成分布。 | 解决 SFT 中下游数据分布 shift 导致灾难性遗忘及多样性 collapse 问题。 | 大模型微调 |
| 58 | http://arxiv.org/abs/2602.10863v1 | ICA: Information-Aware Credit Assignment for Visually Grounded Long-Horizon Information-Seeking Agents | 提出视觉原生搜索框架及 ICA 方法，估计检索 snapshot 对最终结果贡献。 | 解决开放 web 环境中低信噪比反馈及长 horizon 训练信用分配瓶颈问题。 | 信息寻求 Agent |
| 59 | http://arxiv.org/abs/2602.10869v1 | Agentic Knowledge Distillation: Autonomous Training of Small Language Models for SMS Threat Detection | 提出 Agentic 知识蒸馏，强大 LLM 作为自主教师微调小模型用于安全任务。 | 解决 SMS 威胁检测训练数据过时及依赖人工标注问题，实现边缘部署。 | SMS 威胁检测 |
| 60 | http://arxiv.org/abs/2602.18137v1 | Agentic Adversarial QA for Improving Domain-Specific LLMs | 提出对抗性问题生成框架，生成紧凑语义挑战问题以微调模型 | 解决领域适配数据稀缺及合成数据冗余低效问题 | 领域特定 LLM 微调 |
| 61 | http://arxiv.org/abs/2602.19225v1 | Proximity-Based Multi-Turn Optimization: Practical Credit Assignment for LLM Agent Training | 提出 ProxMO 框架，通过成功率感知调制优化多轮 Agent 训练 | 解决多轮 Agent 训练中信用分配因任务难度波动不准确问题 | 多轮 LLM Agent 训练 |
| 62 | http://arxiv.org/abs/2602.19526v1 | How to Train Your Deep Research Agent? Prompt, Reward, and Policy Optimization in Search-R1 | 系统研究提示、奖励及策略优化对深度研究智能体 RL 训练的影响 | 解决深度研究智能体在强化学习训练中的稳定性与性能优化问题 | 深度研究智能体 |
| 63 | http://arxiv.org/abs/2602.19655v1 | Representation Stability in a Minimal Continual Learning Agent | 研究最小额定学习智能体的表示动态，量化状态向量稳定性 | 解决持续学习系统中内部表示随时间演变与稳定性权衡问题 | 持续学习系统 |
| 64 | http://arxiv.org/abs/2602.19837v1 | Meta-Learning and Meta-Reinforcement Learning - Tracing the Path towards DeepMind's Adaptive Agent | 综述元学习与元强化学习，形式化 DeepMind 自适应智能体路径 | 解决标准机器学习模型依赖特定任务训练难以适应新挑战问题 | 自适应智能体 |
| 65 | http://arxiv.org/abs/2602.20739v1 | PyVision-RL: Forging Open Agentic Vision Models via RL | 结合过采样过滤排序策略与累积工具奖励，防止交互崩溃。 | 解决多模态模型交互崩溃及工具使用减少问题。 | 多模态智能体模型 |
| 66 | http://arxiv.org/abs/2602.21158v2 | SELAUR: Self Evolving LLM Agent via Uncertainty-aware Rewards | 将不确定性直接融入奖励设计，提供密集置信对齐监督。 | 解决多步决策中奖励设计忽略模型内在不确定性信号问题。 | 多步决策 LLM 代理 |
| 67 | http://arxiv.org/abs/2602.21320v1 | Tool-R0: Self-Evolving LLM Agents for Tool-Learning from Zero Data | 生成器与求解器协同进化，无需预存任务或数据集。 | 解决工具学习依赖人工构造数据及监督阻碍自我进化问题。 | 通用工具调用代理 |
| 68 | http://arxiv.org/abs/2602.21534v2 | ARLArena: A Unified Framework for Stable Agentic Reinforcement Learning | 分解策略梯度为四核心设计维度，提出 SAMPO 稳定优化方法。 | 解决 Agentic 强化学习训练高度不稳定及易崩溃问题。 | 复杂多步交互任务 |
| 69 | http://arxiv.org/abs/2602.22480v1 | VeRO: An Evaluation Harness for Agents to Optimize Agents | 提供版本化代理快照与结构化执行追踪评估工具 | 解决代码代理优化任务缺乏系统评估标准的问题 | 代码代理自我优化 |
| 70 | http://arxiv.org/abs/2602.22576v1 | Search-P1: Path-Centric Reward Shaping for Stable and Efficient Agentic RAG Training | 引入路径中心奖励塑造，从失败样本中提取信号 | 解决Agentic RAG训练奖励稀疏且样本效率低的问题 | 检索增强生成训练 |
| 71 | http://arxiv.org/abs/2602.22697v1 | Reinforcing Real-world Service Agents: Balancing Utility and Cost in Task-oriented Dialogue | 提出成本感知多轮策略优化，平衡效用与预算 | 解决任务对话中共情沟通与预算决策难以平衡问题 | 现实服务对话代理 |
| 72 | http://arxiv.org/abs/2602.22817v1 | Hierarchy-of-Groups Policy Optimization for Long-Horizon Agentic Tasks | 提出层级组策略优化，自适应聚合优势估计 | 解决步wise 组优化中历史上下文不一致导致偏差问题 | 长程任务策略优化 |
| 73 | http://arxiv.org/abs/2602.23876v1 | RF-Agent: Automated Reward Function Design via Language Agent Tree Search | 集成蒙特卡洛树搜索管理奖励设计，利用 LLM 多阶段上下文推理能力。 | 解决现有方法利用历史反馈差及搜索效率低导致复杂控制任务改进有限的问题。 | 低层控制任务奖励设计 |
| 74 | http://arxiv.org/abs/2602.23997v1 | "Foundation World Models for Agents that Learn, Verify, and Adapt Reliably Beyond Static Environments" | 提出基础世界模型愿景，统一强化学习、程序合成与抽象机制，支持在线校准。 | 解决标准方法假设固定任务环境限制代理在开放世界中进化策略的问题。 | 开放世界自主代理 |
| 75 | http://arxiv.org/abs/2602.24286v1 | CUDA Agent: Large-Scale Agentic RL for High-Performance CUDA Kernel Generation | 提出大规模代理 RL 系统，通过数据合成、技能增强环境及 RL 算法开发 CUDA 专长。 | 解决 LLM 在 CUDA 内核生成上不如编译器系统及现有方法性能增益有限的问题。 | 高性能 CUDA 内核生成 |
| 76 | http://arxiv.org/abs/2603.00656v1 | InfoPO: Information-Driven Policy Optimization for User-Centric Agents | 提出 InfoPO，将多轮交互 framing 为主动不确定性减少过程，计算信息增益奖励。 | 解决现有方法依赖轨迹级奖励计算导致信用分配问题及优势信号不足的问题。 | 用户中心代理优化 |
| 77 | http://arxiv.org/abs/2603.00724v1 | RLAR: An Agentic Reward System for Multi-task Reinforcement Learning on Large Language Models | 提出 RLAR，将奖励获取转化为动态工具合成与调用任务，利用 LLM 代理自主检索合成验证器。 | 解决静态领域特定奖励模型训练成本高及在分布外场景泛化差的问题。 | 多任务 RL 奖励系统 |
| 78 | http://arxiv.org/abs/2603.00825v1 | COMBAT: Conditional World Models for Behavioral Agent Training | 引入 COMBAT，实时动作控制世界模型，训练于 Tekken 3，模拟动态对手反应。 | 解决世界模型模拟动态反应代理能力及传统模仿学习需完整动作标签的问题。 | 行为代理训练世界模型 |

[返回目录](#目录)

<a id="cat-11"></a>

## Agent记忆与知识管理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2602.01566v1 | FS-Researcher: Test-Time Scaling for Long-Horizon Research Tasks with File-System-Based Agents | 文件系统作为持久外部记忆实现超越上下文窗口的研究 | 长轨迹超出上下文限制压缩证据收集与报告写作token预算 | 深度研究报告生成 |
| 2 | http://arxiv.org/abs/2602.03036v2 | LatentMem: Customizing Latent Memory for Multi-Agent Systems | 经验银行+记忆合成器，角色感知定制潜在记忆 | 多Agent记忆同质化和信息过载两大约束瓶颈 | 主流多Agent系统框架 |
| 3 | http://arxiv.org/abs/2602.03224v1 | TAME: A Trustworthy Test-Time Evolution of Agent Memory with Systematic Benchmarking | 双记忆演化框架，执行器记忆蒸馏方法+评估器记忆 refinement | Agent记忆在良性任务演化中安全对齐脆弱（记忆误演化） | 测试时Agent记忆演化 |
| 4 | http://arxiv.org/abs/2602.03442v1 | A-RAG: Scaling Agentic Retrieval-Augmented Generation via Hierarchical Retrieval Interfaces | 三层检索工具（关键词/语义/块读取），Agent自适应多粒度检索 | 现有RAG系统不让模型参与检索决策，无法随模型改进扩展 | 开放域QA的Agent RAG系统 |
| 5 | http://arxiv.org/abs/2602.01869v1 | ProcMEM: Learning Reusable Procedural Memory from Experience via Non-Parametric PPO for LLM Agents | 无需参数更新即可从经验中学习可重用过程记忆 | 解决智能体在重复场景中重复推理导致的冗余问题 | 序列决策任务 |
| 6 | http://arxiv.org/abs/2602.02007v2 | Beyond RAG for Agent Memory: Retrieval by Decoupling and Aggregation | 提出解耦与聚合的层级记忆检索机制 xMemory | 解决固定 top-k 检索在对话流中冗余且丢失时序问题 | 长期对话记忆系统 |
| 7 | http://arxiv.org/abs/2602.02474v1 | MemSkill: Learning and Evolving Memory Skills for Self-Evolving Agents | 将记忆操作重构为可学习可进化的记忆技能 | 解决固定记忆过程硬编码人类先验导致僵化问题 | 长历史交互记忆管理 |
| 8 | http://arxiv.org/abs/2602.02704v1 | InfMem: Learning System-2 Memory Control for Long-Context Agent | 控制中心智能体，实例化 System-2 风格控制协议 | 解决流式智能体被动记忆更新丢失低 salience 证据问题 | 超长文档推理任务 |
| 9 | http://arxiv.org/abs/2603.00026v1 | ActMem: Bridging the Gap Between Memory Retrieval and Reasoning in LLM Agents | 可操作记忆框架，集成因果推理 | 当前记忆框架被动检索缺乏理解 | 长程交互代理 |
| 10 | http://arxiv.org/abs/2602.07624v1 | M2A: Multimodal Memory Agent with Dual-Layer Hybrid Memory for Long-Term Personalized Interactions | 双层混合记忆系统，原始消息+语义记忆协同 | 长周期交互超出上下文窗口，个性化机制难以持续吸收 | 长周期多模态人机交互 |
| 11 | http://arxiv.org/abs/2602.05665v1 | Graph-based Agent Memory: Taxonomy, Techniques, and Applications | 从基于图视角全面回顾代理记忆，提出分类法并分析生命周期关键技术。 | 解决长程复杂任务中记忆作为核心模块，需有效建模关系依赖和组织层次信息的问题。 | 代理记忆系统开发 |
| 12 | http://arxiv.org/abs/2602.05832v1 | UI-Mem: Self-Evolving Experience Memory for Online Reinforcement Learning in Mobile GUI Agents | 提出框架增强 GUI 在线 RL，通过分层经验记忆积累结构化知识支持跨任务迁移。 | 解决在线 RL 在长程任务中信用分配效率低且因缺乏经验转移导致重复错误的问题。 | 移动 GUI 代理 |
| 13 | http://arxiv.org/abs/2602.05965v1 | Learning to Share: Selective Memory for Efficient Parallel Agentic Systems | 提出学习共享机制，通过全局记忆库和轻量控制器实现选择性跨团队信息重用。 | 解决并行执行导致不同团队独立推理相似子问题时重复大量重叠计算的问题。 | 并行代理系统 |
| 14 | http://arxiv.org/abs/2602.06025v1 | Learning Query-Aware Budget-Tier Routing for Runtime Agent Memory | 提出运行时代理记忆框架，通过轻量路由器进行预算层级路由以平衡性能与成本。 | 解决现有系统依赖离线查询无关记忆构建效率低，且运行时利用开销大的问题。 | 运行时代理记忆 |
| 15 | http://arxiv.org/abs/2603.03290v1 | AriadneMem: Threading the Maze of Lifelong Memory for LLM Agents | 提出结构化记忆系统，通过熵感知 gating 和冲突感知 coarsening 管理记忆。 | 解决长对话中证据 disconnected 和状态更新冲突的问题。 | 长周期 LLM Agent |
| 16 | http://arxiv.org/abs/2602.17692v2 | Agentic Unlearning: When LLM Agent Meets Machine Unlearning | 提出 SBU 框架，同步 unlearn 参数和持久化记忆中的指定信息。 | 解决参数 - 记忆 backflow 导致敏感内容重新引入的问题。 | 隐私保护 Agent |
| 17 | http://arxiv.org/abs/2603.03296v1 | PlugMem: A Task-Agnostic Plugin Memory Module for LLM Agents | 提出 PlugMem，将 episodic 记忆结构化为 knowledge-centric 图。 | 解决 task-agnostic 记忆检索 relevance 低和 context explosion 问题。 | 复杂环境 LLM Agent |
| 18 | http://arxiv.org/abs/2602.11243v1 | Evaluating Memory Structure in LLM Agents | 提出 StructMemEval 基准，测试智能体组织长期记忆的能力 | 现有基准仅关注事实保留，未测试复杂记忆层次 | 基于 LLM 的智能体与聊天助手 |
| 19 | http://arxiv.org/abs/2603.04428v1 | Agent Memory Below the Prompt: Persistent Q4 KV Cache for Multi-Agent LLM Inference on Edge Devices | 持久化4-bit量化KV缓存到磁盘，直接恢复消除冗余预填充 | 边缘设备RAM小无法同时容纳所有Agent KV缓存 | 边缘设备多Agent LLM推理 |
| 20 | http://arxiv.org/abs/2603.02240v1 | SuperLocalMemory: Privacy-Preserving Multi-Agent Memory with Bayesian Trust Defense Against Memory Poisoning | 架构隔离+贝叶斯信任评分防御记忆投毒，无云依赖 | 云基记忆系统产生集中攻击面，投毒记忆跨会话传播 | 多Agent AI本地记忆 |
| 21 | http://arxiv.org/abs/2602.08369v1 | MemAdapter: Fast Alignment across Agent Memory Paradigms via Generative Subgraph Retrieval | 提出生成式子图检索器，实现跨记忆范式快速对齐。 | 解决异构记忆范式难以泛化与融合的问题。 | 智能体记忆系统优化 |
| 22 | http://arxiv.org/abs/2602.08400v1 | SCOUT-RAG: Scalable and Cost-Efficient Unifying Traversal for Agentic Graph-RAG over Distributed Domains | 提出分布式代理 Graph-RAG 框架，渐进式跨域检索。 | 解决分布式场景下检索域选择与遍历深度控制问题。 | 分布式知识检索 |
| 23 | http://arxiv.org/abs/2602.08837v1 | AMEM4Rec: Leveraging Cross-User Similarity for Memory Evolution in Agentic LLM Recommenders | 通过跨用户记忆进化学习协同过滤信号。 | 解决 LLM 推荐系统忽视隐式偏好建模与上下文限制问题。 | 智能体推荐系统 |
| 24 | http://arxiv.org/abs/2602.13521v2 | Arming Data Agents with Tribal Knowledge | 提出 Tk-Boost 框架，利用经验积累部落知识纠正代理误解 | 解决 NL2SQL 代理缺乏领域知识导致查询错误的问题 | 数据库自然语言查询 |
| 25 | http://arxiv.org/abs/2602.13530v3 | REMem: Reasoning with Episodic Memory in Language Agent | 构建混合记忆图，支持时空上下文的情节记忆检索与推理 | 解决语言代理缺乏情节记忆及复杂推理能力的问题 | 长程交互语言代理 |
| 26 | http://arxiv.org/abs/2602.13594v1 | Hippocampus: An Efficient and Scalable Memory Module for Agentic AI | 使用动态小波矩阵压缩语义搜索与 token 流，实现超低延迟检索 | 解决现有记忆系统检索延迟高、存储扩展性差的问题 | 长程代理部署记忆 |
| 27 | http://arxiv.org/abs/2602.14038v1 | Choosing How to Remember: Adaptive Memory Structures for LLM Agents | equip 代理多种记忆结构，基于交互特征学习选择及概率门控融合 | 解决现有记忆系统依赖单一结构及未建模结构选择决策的问题 | 长程交互记忆管理 |
| 28 | http://arxiv.org/abs/2602.16493v1 | MMA: Multimodal Memory Agent | 为检索记忆项分配动态可靠性评分，减少冲突与过时信息影响 | 解决多模态 Agent 依赖相似性检索导致过度自信错误问题 | 长程多模态 Agent 记忆管理 |
| 29 | http://arxiv.org/abs/2602.17913v1 | From Lossy to Verified: A Provenance-Aware Tiered Memory for Agents | 提出 TierMem，双层记忆层级以回答最便宜 sufficient 证据。 | 写前总结导致无法验证的遗漏，原始日志 grounding 昂贵。 | 长程代理记忆 |
| 30 | http://arxiv.org/abs/2602.10715v1 | Locomo-Plus: Beyond-Factual Cognitive Memory Evaluation Framework for LLM Agents | 引入 LoCoMo-Plus 基准，评估 cue-trigger 语义断开下的认知记忆能力。 | 解决现有基准仅关注表面事实 recall，忽略 implicit 约束保留及应用的问题。 | 长对话记忆 |
| 31 | http://arxiv.org/abs/2603.04443v1 | AMV-L: Lifecycle-Managed Agent Memory for Tail-Latency Control in Long-Running LLM Systems | 自适应记忆价值生命周期框架，控制长运行 LLM 系统尾延迟 | 解决长期记忆积累导致检索延迟不可预测及吞吐不稳定问题 | 长运行 LLM 系统 |
| 32 | http://arxiv.org/abs/2602.19320v1 | Anatomy of Agentic Memory: Taxonomy and Empirical Analysis of Evaluation and System Limitations | 结构化分析 Agentic 记忆系统，提出 taxonomy 及实证局限性 | 解决记忆系统基准 underscaled 及指标与语义效用不对齐问题 | Agentic 记忆系统 |
| 33 | http://arxiv.org/abs/2602.20478v1 | Codified Context: Infrastructure for AI Agents in a Complex Codebase | 构建编码上下文基础设施，包含热记忆宪法与冷记忆知识库 | 解决编码助手缺乏持久记忆导致跨会话 coherence 丢失问题 | 复杂代码库开发 |
| 34 | http://arxiv.org/abs/2602.21053v1 | OCR-Agent: Agentic OCR with Capability and Memory Reflection | 赋予能力反思与记忆反思能力，引导诊断错误并避免重复尝试。 | 解决多轮修订中模型陷入重复无效尝试及认知偏差问题。 | 光学字符识别任务 |
| 35 | http://arxiv.org/abs/2602.21477v1 | Pancake: Hierarchical Memory System for Multi-Agent LLM Serving | 统一多级索引缓存、跨代理协调索引管理及 GPU-CPU 加速。 | 解决代理记忆管理中大规模存储及高成本 ANN 搜索问题。 | 多代理 LLM 服务 |
| 36 | http://arxiv.org/abs/2602.21611v1 | Structurally Aligned Subtask-Level Memory for Software Engineering Agents | 内存存储检索更新与代理功能分解对齐，而非实例粒度。 | 解决实例级内存粒度不匹配导致复杂任务检索误导问题。 | 软件工程代理 |
| 37 | http://arxiv.org/abs/2603.13258v1 | Your Code Agent Can Grow Alongside You with Structured Memory | 结构化历史人类经验，引入经验自内部化机制结晶长期知识。 | 解决代码代理 tethered 静态快照无法利用项目 temporal 演化问题。 | 软件工程与人机共演 |
| 38 | http://arxiv.org/abs/2602.22402v1 | Contextual Memory Virtualisation: DAG-Based State Management and Structurally Lossless Trimming for LLM Agents | 建模会话历史为 DAG，引入三 pass 结构无损修剪算法。 | 解决 LLM 长程推理中上下文限制导致状态丢失及 lossy 压缩问题。 | LLM 代理会话管理 |
| 39 | http://arxiv.org/abs/2602.22406v1 | Towards Autonomous Memory Agents | 提出成本感知知识提取级联与语义感知汤普森采样 | 解决现有记忆代理被动反应，依赖偶然信息的问题 | 通用LLM记忆增强 |
| 40 | http://arxiv.org/abs/2602.23008v2 | Exploratory Memory-Augmented LLM Agent via Hybrid On- and Off-Policy Optimization | 混合 RL 框架利用记忆探索并结合内外策略更新 | 解决 RL 训练代理在需发现新状态环境中探索瓶颈问题 | 探索性记忆增强代理 |
| 41 | http://arxiv.org/abs/2603.15634v1 | NextMem: Towards Latent Factual Memory for LLM-based Agents | 利用自回归自编码器构建潜在事实记忆 | 解决文本记忆上下文负担重参数记忆遗忘成本高的问题 | LLM 代理事实记忆 |
| 42 | http://arxiv.org/abs/2602.23320v2 | ParamMem: Augmenting Language Agents with Parametric Reflective Memory | 引入参数记忆模块编码跨样本反思模式，支持通过温度控制采样生成多样化反思。 | 解决自反思代理产生重复输出限制推理性能的问题。 | 代码生成与数学推理代理 |
| 43 | http://arxiv.org/abs/2602.23944v1 | MemEmo: Evaluating Emotion in Memory Systems of Agents | 提出情感增强记忆评估基准，评估主流记忆系统在处理情感信息方面的性能。 | 解决现有记忆系统在处理情感相关信息方面有效性不明确的问题。 | 代理记忆系统评估 |
| 44 | http://arxiv.org/abs/2603.00503v1 | M$^2$: Dual-Memory Augmentation for Long-Horizon Web Agents via Trajectory Summarization and Insight Retrieval | 提出双 tier 记忆机制，协同动态轨迹总结与洞察检索增强，优化上下文效率。 | 解决长视野任务中计算成本高及推理能力不足的问题。 | 长视野 Web 导航代理 |
| 45 | http://arxiv.org/abs/2603.00680v2 | MemPO: Self-Memory Policy Optimization for Long-Horizon Agents | 提出自记忆策略优化算法，使代理自主总结管理记忆，基于记忆有效性改进信用分配。 | 解决长视野交互中上下文大小增长导致性能稳定性下降及外部记忆被动查找的问题。 | 长视野代理记忆管理 |

[返回目录](#目录)

<a id="cat-12"></a>

## Agent评测与基准

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2602.01590v2 | Wiki Live Challenge: Challenging Deep Research Agents with Expert-Level Wikipedia Articles | 利用维基百科优质文章作为专家级参考的实时基准 | 现有评估依赖LLM生成参考缺乏专家验证内容可靠性 | 深度研究Agent能力评估 |
| 2 | http://arxiv.org/abs/2602.01611v1 | What Do Agents Learn from Trajectory-SFT: Semantics or Interfaces? | PIPE协议级评估增强诊断接口依赖揭示轨迹SFT放大快捷方式 | 标准基准混淆语义工具使用与接口特定模式记忆 | Agent轨迹SFT效果评估 |
| 3 | http://arxiv.org/abs/2602.01640v1 | A2Eval: Agentic and Automated Evaluation for Embodied Brain | 两协作Agent自动化基准策划与评估实现高保真低成评估 | 静态专家定义基准冗余覆盖失衡且劳动密集型成本高 | 具身VLM模型评估 |
| 4 | http://arxiv.org/abs/2602.01655v2 | ProjDevBench: Benchmarking AI Coding Agents on End-to-End Project Development | 端到端基准评估编码Agent系统架构、功能正确性与迭代优化 | 现有评估聚焦issue级修复落后于端到端开发能力 | AI编码Agent能力评估 |
| 5 | http://arxiv.org/abs/2602.01675v1 | TRIP-Bench: A Benchmark for Long-Horizon Interactive Agents in Real-World Scenarios | 基于真实旅行规划场景的长期交互基准支持自动评估 | 现有基准低估全局约束、多工具协调与长期用户行为适应挑战 | 长期交互式Agent评估 |
| 6 | http://arxiv.org/abs/2602.11198v1 | DDL2PropBank Agent: Benchmarking Multi-Agent Frameworks' Developer Experience Through a Novel Relational Schema Mapping Task | 跨10个框架评估代码复杂度和AI辅助性，提出结构对齐分数 | 缺乏多Agent框架开发者体验的标准化评估方法 | 多Agent框架开发者 |
| 7 | http://arxiv.org/abs/2602.03053v1 | MAS-ProVe: Understanding the Process Verification of Multi-Agent Systems | 系统实证研究三种验证范式在两粒度上的效果 | 过程验证在多Agent系统中的实际效果不明确 | 六大多Agent推理框架 |
| 8 | http://arxiv.org/abs/2602.03128v1 | Understanding Multi-Agent LLM Frameworks: A Unified Benchmark and Experimental Analysis | 提出架构分类法+MAFBench统一评估套件，控制框架级条件 | 缺乏标准化框架级评估，架构选择影响被忽视 | 多Agent LLM框架选择与设计 |
| 9 | http://arxiv.org/abs/2602.03130v1 | FinMTM: A Multi-Turn Multimodal Benchmark for Financial Reasoning and Agent Evaluation | 11,133双语金融QA对，多轮对话+Agent任务，任务特定评估协议 | 现有金融基准单轮且问题格式单一 | 金融领域视觉语言模型和Agent |
| 10 | http://arxiv.org/abs/2602.03238v1 | The Necessity of a Unified Framework for LLM-Based Agent Evaluation | 提出统一评估框架提案，标准化系统提示/工具集/环境数据 | 当前基准受外在因素混淆，缺乏标准化导致不公平和不透明 | LLM通用Agent评估 |
| 11 | http://arxiv.org/abs/2602.01885v1 | ES-MemEval: Benchmarking Conversational Agents on Personalized Long-Term Emotional Support | 评估长期情感支持中五大核心记忆能力的基准 | 解决现有基准忽视隐性、动态用户信息的问题 | 长期情感支持对话 |
| 12 | http://arxiv.org/abs/2602.02196v2 | TIDE: Trajectory-based Diagnostic Evaluation of Test-Time Improvement in LLM Agents | 分解测试时改进为三个维度的诊断评估框架 | 解决现有指标无法捕捉任务优化效率与行为适应问题 | 自主 LLM 智能体评估 |
| 13 | http://arxiv.org/abs/2602.02235v2 | Agent-Based Software Artifact Evaluation | 端到端基于智能体的自动化 artifact 评估框架 | 解决人工执行调试导致可扩展性挑战问题 | 软件工程研究评估 |
| 14 | http://arxiv.org/abs/2602.02262v2 | OmniCode: A Benchmark for Evaluating Software Engineering Agents | 涵盖多语言多类别的软件工程基准 OmniCode | 解决现有基准任务范围狭窄及数据泄露问题 | 软件开发智能体评估 |
| 15 | http://arxiv.org/abs/2602.02345v1 | A Task-Level Evaluation of AI Agents in Open-Source Projects | 基于 AI 生成 PR 数据集的五种自主编码代理比较研究 | 评估智能体在开源项目中的任务级表现差异 | 开源软件协作开发 |
| 16 | http://arxiv.org/abs/2602.02455v1 | Drift-Bench: Diagnosing Cooperative Breakdowns in LLM Agents under Input Faults via Multi-Turn Interaction | 诊断输入故障下智能体语用合作破裂的基准 | 解决现有基准忽视多轮澄清与 grounded 执行风险问题 | 智能体鲁棒性与安全评估 |
| 17 | http://arxiv.org/abs/2602.02905v1 | FIRE-Bench: Evaluating Agents on the Rediscovery of Scientific Insights | 通过 rediscovery  established findings 评估智能体 | 解决现有基准依赖 LLM-as-judge 或指标 coarse 问题 | 科学发现能力评估 |
| 18 | http://arxiv.org/abs/2602.06075v1 | MemGUI-Bench: Benchmarking Memory of Mobile GUI Agents in Dynamic Environments | 以记忆为中心的基准，跨会话学习评估 | 现有基准缺乏记忆能力评估 | 移动 GUI 智能体 |
| 19 | http://arxiv.org/abs/2602.04226v1 | Why Agentic-PRs Get Rejected: A Comparative Study of Coding Agents | 比较不同代理生成 PR 的拒绝原因 | 代理生成 PR 接受率低于人类 | 软件工程/代码代理 |
| 20 | http://arxiv.org/abs/2602.04482v2 | ProAgentBench: Evaluating LLM Agents for Proactive Assistance with Real-World Data | 主动代理基准，真实用户会话数据 | 现有数据集缺乏真实人类决策模式 | 主动代理评估 |
| 21 | http://arxiv.org/abs/2602.07962v1 | LOCA-bench: Benchmarking Language Agents Under Controllable and Extreme Context Growth | LOCA-bench基准可控调节Agent上下文长度至无限 | 现有长上下文基准仅关注单步设置，非动态增长场景 | 长周期真实世界任务的语言Agent |
| 22 | http://arxiv.org/abs/2602.10140v1 | Can Large Language Models Implement Agent-Based Models? An ODD-based Replication Study | 评估17个LLM从ODD规范生成ABM代码的能力 | LLM能否可靠实现Agent-Based模型支持复现验证 | 可复现的Agent-Based和环境建模 |
| 23 | http://arxiv.org/abs/2602.09063v1 | scBench: Evaluating AI Agents on Single-Cell RNA-seq Analysis | scBench基准394可验证问题覆盖6平台7任务类别 | 前沿AI Agent能否从混乱真实单细胞数据集提取生物洞察不明 | 单细胞RNA-seq数据分析的AI Agent |
| 24 | http://arxiv.org/abs/2602.05115v1 | SocialVeil: Probing Social Intelligence of Language Agents under Communication Barriers | 构建模拟认知差异导致沟通障碍的社会学习环境，评估代理社会智能。 | 解决现有基准假设理想化通信，无法诊断现实 imperfect 设置下交互能力的问题。 | 语言代理社会智能 |
| 25 | http://arxiv.org/abs/2602.13272v1 | TemporalBench: A Benchmark for Evaluating LLM-Based Agents on Contextual and Event-Informed Time Series Tasks | 引入多领域基准，评估代理在渐进丰富信息设置下的时序推理行为。 | 解决强预测性能是否反映真实时序理解能力不明确的问题。 | 时序任务代理评估 |
| 26 | http://arxiv.org/abs/2602.05302v2 | PieArena: Frontier Language Agents Achieve MBA-Level Negotiation Performance and Reveal Novel Behavioral Differences | 引入大规模谈判基准，发现前沿语言代理达到人类专家水平谈判性能。 | 解决缺乏原则性设置评估多代理间语言介导经济交互的问题。 | 商业谈判代理 |
| 27 | http://arxiv.org/abs/2602.05354v2 | PATHWAYS: Evaluating Investigation and Context Discovery in AI Web Agents | 引入基准测试基于 Web 的代理发现和正确使用隐藏上下文信息的能力。 | 解决当前 Web 代理架构缺乏可靠机制进行自适应调查和证据整合的问题。 | Web 代理能力评估 |
| 28 | http://arxiv.org/abs/2602.18456v1 | Beyond single-channel agentic benchmarking | 论证孤立评估 AI 代理系统性地误表征其在人机环环境中的操作安全性。 | 解决当代基准将自主系统视为单点故障，偏离安全关键工程原则的问题。 | 代理安全评估范式 |
| 29 | http://arxiv.org/abs/2602.05523v1 | Capture the Flags: Family-Based Evaluation of Agentic LLMs via Semantics-Preserving Transformations | 引入 CTF 挑战家族，通过语义保持变换生成挑战，评估代理对代码变换的鲁棒性。 | 解决现有逐点基准揭示代理跨源代码替代版本鲁棒性和泛化能力有限的问题。 | 网络安全代理评估 |
| 30 | http://arxiv.org/abs/2602.21230v1 | TRACE: Trajectory-Aware Comprehensive Evaluation for Deep Research Agents | 引入框架 holistic 评估整个问题解决轨迹，量化过程效率和认知质量。 | 解决常规基于结果指标无法捕捉复杂推理细微差别，产生高分错觉的问题。 | 深度研究代理评估 |
| 31 | http://arxiv.org/abs/2602.05662v1 | Making AI Agents Evaluate Misleading Charts without Nudging | 测试代理是否自发惩罚图表垃圾和误导性编码，发现未提示评估低估完整性缺陷。 | 解决 AI 代理作为可视化评估代理时，除非明确提示否则低估完整性相关缺陷的问题。 | 可视化评估代理 |
| 32 | http://arxiv.org/abs/2602.05892v3 | ContextBench: A Benchmark for Context Retrieval in Coding Agents | 引入面向过程的评估，跟踪代理轨迹并测量问题解决过程中的上下文召回与精度。 | 解决现有评估主要关注最终任务成功，缺乏对代理如何检索和使用代码上下文洞察的问题。 | 编码代理评估 |
| 33 | http://arxiv.org/abs/2602.05975v2 | SAGE: Benchmarking and Improving Retrieval for Deep Research Agents | 引入科学文献检索基准，发现 BM25 显著优于 LLM 检索器，提出测试时缩放框架。 | 解决 LLM 检索器能否有效贡献于深度研究代理工作流的关键问题。 | 深度研究代理检索 |
| 34 | http://arxiv.org/abs/2602.06855v3 | AIRS-Bench: a Suite of Tasks for Frontier AI Research Science Agents | 提出 AIRS-Bench，涵盖从 idea 生成到实验分析的全 research 生命周期。 | 解决缺乏评估 autonomous 科学研究能力的基准的问题。 | 科学研究 Agent |
| 35 | http://arxiv.org/abs/2602.07150v1 | On Randomness in Agentic Evals | 分析 Agentic 评估中的 variance，建议多 run 估计 pass@1。 | 解决单次 run 评估 noise 大导致科学进步误判的问题。 | Agent 基准测试 |
| 36 | http://arxiv.org/abs/2602.10975v1 | FeatureBench: Benchmarking Agentic Coding for Complex Feature Development | 提出基于执行评估的可扩展测试驱动方法，自动衍生任务 | 现有基准任务范围有限，缺乏自动化更新评估覆盖 | 复杂功能开发的编码智能体 |
| 37 | http://arxiv.org/abs/2602.11103v1 | GameDevBench: Evaluating Agentic Capabilities Through Game Development | 首个游戏开发任务基准，结合代码复杂性与多模态理解 | 多模态智能体评估测试床稀缺 | 游戏开发智能体 |
| 38 | http://arxiv.org/abs/2602.11348v2 | AgentNoiseBench: Benchmarking Robustness of Tool-Using LLM Agents Under Noisy Condition | 自动化管道注入可控噪声，评估智能体在噪声环境下的鲁棒性 | 现有训练评估基于理想化假设，忽略现实随机性 | 工具使用 LLM 智能体 |
| 39 | http://arxiv.org/abs/2602.11354v1 | ReplicatorBench: Benchmarking LLM Agents for Replicability in Social and Behavioral Sciences | 端到端基准，包含人工验证的可/不可复制研究 claims | 现有基准仅关注可复制论文，缺乏 ground-truth 多样性 | 社会与行为科学研究复制 |
| 40 | http://arxiv.org/abs/2602.11619v1 | When Agents Disagree With Themselves: Measuring Behavioral Consistency in LLM-Based Agents | 发现行为一致性 variance 预测失败，监测一致性可实现早期错误检测 | 同一任务多次运行行为不一致，影响可靠性 | 基于 LLM 的智能体可靠性 |
| 41 | http://arxiv.org/abs/2602.11750v1 | AmbiBench: Benchmarking Mobile GUI Agents Beyond One-Shot Instructions in the Wild | 引入指令清晰度分类，从单向指令跟随转向双向意图对齐 | 现有基准假设指令完整明确，忽略对齐能力 | 移动 GUI 智能体 |
| 42 | http://arxiv.org/abs/2602.11964v1 | Gaia2: Benchmarking LLM Agents on Dynamic and Asynchronous Environments | 引入环境独立演变的场景，配对 write-action verifier 支持 RL | prior 静态或同步评估无法反映现实异步环境 | 现实异步环境 LLM 智能体 |
| 43 | http://arxiv.org/abs/2602.14337v2 | LongCLI-Bench: A Preliminary Benchmark and Study for Long-horizon Agentic Programming in Command-Line Interfaces | 长程命令行界面Agent编程基准，双集测试协议 | 现有基准任务视野短、数据污染、缺乏细粒度评估 | 软件工程长程任务Agent |
| 44 | http://arxiv.org/abs/2603.02239v1 | Engineering Reasoning and Instruction (ERI) Benchmark: A Large Taxonomy-driven Dataset for Foundation Models and Agents | 九大工程领域57,750条记录的分类驱动指令数据集 | 缺乏工程领域LLM和Agent训练评估基准 | 工程领域Foundation Models和Agents |
| 45 | http://arxiv.org/abs/2602.15112v2 | ResearchGym: Evaluating Language Model Agents on Real-World AI Research | 端到端研究基准，复用顶会论文仓库评估Agent研究能力 | 缺乏Agent真实AI研究能力系统评估基础设施 | AI研究Agent |
| 46 | http://arxiv.org/abs/2602.08765v1 | Taming Scylla: Understanding the multi-headed agentic daemon of the coding seas | 提出 Scylla 框架，通过结构化消融研究评估编码智能体。 | 量化智能体架构复杂度与实际 outcomes 之间的权衡。 | 编码智能体评估 |
| 47 | http://arxiv.org/abs/2602.08915v1 | Comparing AI Coding Agents: A Task-Stratified Analysis of Pull Request Acceptance | 基于 GitHub PR 数据分层分析五种编码智能体的有效性。 | 缺乏对不同任务类型下智能体有效性的系统比较。 | 编码智能体性能分析 |
| 48 | http://arxiv.org/abs/2602.08964v1 | A Behavioural and Representational Evaluation of Goal-Directedness in Language Model Agents | 结合行为评估与内部表示分析，评估智能体目标导向性。 | 缺乏可靠方法论将目标归因于智能体系统。 | 智能体目标性评估 |
| 49 | http://arxiv.org/abs/2602.09163v1 | FlyAOC: Evaluating Agentic Ontology Curation of Drosophila Scientific Knowledge Bases | 提出 FlyBench，评估智能体端到端本体 curated 能力。 | 现有基准未捕获科学文献本体 curated 的完整工作流。 | 科学知识库 curated |
| 50 | http://arxiv.org/abs/2602.09185v1 | AIDev: Studying AI Coding Agents on GitHub | 引入 AIDev 数据集，聚焦真实 GitHub 仓库中的代理 PR。 | 缺乏捕捉真实项目中智能体使用情况的大规模数据集。 | 软件工程中 AI 采用研究 |
| 51 | http://arxiv.org/abs/2602.09341v1 | Auditing Multi-Agent LLM Reasoning Trees Outperforms Majority Vote and LLM-as-Judge | 提出 AgentAuditor，通过推理树路径搜索替代多数投票。 | 解决多数投票在共谋幻觉下脆弱且丢弃证据结构问题。 | 多智能体推理审计 |
| 52 | http://arxiv.org/abs/2602.09379v2 | LingxiDiagBench: A Multi-Agent Framework for Benchmarking LLMs in Chinese Psychiatric Consultation and Diagnosis | 提出大规模多智能体基准，评估中文精神科咨询与诊断。 | 缺乏同时提供真实模拟、 clinician 标签与动态咨询的基准。 | 精神健康 AI 评估 |
| 53 | http://arxiv.org/abs/2602.10159v1 | Beyond Closed-Pool Video Retrieval: A Benchmark and Agent Framework for Real-World Video Search and Moment Localization | 提出 RVMS-Bench 与 RACLO 框架，评估真实视频记忆搜索。 | 解决传统基准无法反映真实世界模糊多维记忆搜索问题。 | 视频检索与定位 |
| 54 | http://arxiv.org/abs/2602.09447v2 | SWE-AGI: Benchmarking Specification-Driven Software Construction with MoonBit in the Era of Autonomous Agents | 引入 SWE-AGI 基准，评估基于规范的端到端软件构建。 | 评估 LLM 智能体从明确规范自主构建生产级软件的能力。 | 自主软件工程评估 |
| 55 | http://arxiv.org/abs/2602.14224v1 | The Interspeech 2026 Audio Reasoning Challenge: Evaluating Reasoning Process Quality for Audio Reasoning Models and Agents | 引入 MMAR-Rubrics 协议评估推理链事实性与逻辑，设立单模型与代理赛道 | 解决大型音频语言模型缺乏透明推理及黑盒 limitation 的问题 | 音频推理模型评估 |
| 56 | http://arxiv.org/abs/2602.14257v1 | AD-Bench: A Real-World, Trajectory-Aware Advertising Analytics Benchmark for LLM Agents | 基于真实业务需求构建基准，提供可验证参考答案及工具调用轨迹 | 解决现有基准局限于理想化模拟及无法 address 广告营销分析实际需求问题 | 广告营销分析代理 |
| 57 | http://arxiv.org/abs/2602.16131v1 | Empirical Cumulative Distribution Function Clustering for LLM-based Agent System Analysis | 提出基于 ECDF 的评估框架，聚类分析 Agent 响应分布 | 解决聚合评估掩盖响应质量分布特征的问题 | LLM Agent 系统质量评估 |
| 58 | http://arxiv.org/abs/2602.16179v5 | EnterpriseBench Corecraft: Training Generalizable Agents on High-Fidelity RL Environments | 构建高保真企业仿真环境 Corecraft，训练可泛化 Agent | 解决 Agent 训练环境缺乏真实专业工作流多样性的问题 | 企业客服与通用 Agent 训练 |
| 59 | http://arxiv.org/abs/2602.16246v2 | Toward Scalable Verifiable Reward: Proxy State-Based Evaluation for Multi-turn Tool-Calling LLM Agents | 提出基于代理状态的评估框架，无需确定性后端 | 解决多轮工具调用 Agent 基准构建成本高且迭代慢的问题 | 工业级 LLM Agent 评估 |
| 60 | http://arxiv.org/abs/2602.16313v1 | MemoryArena: Benchmarking Agent Memory in Interdependent Multi-Session Agentic Tasks | 构建 MemoryArena 基准，评估多会话任务中记忆与行动耦合 | 解决现有基准孤立评估记忆而忽略决策引导作用的问题 | 长程记忆 Agent 系统评估 |
| 61 | http://arxiv.org/abs/2602.16666v2 | Towards a Science of AI Agent Reliability | 提出 12 个具体指标分解 Agent 可靠性维度（一致性、鲁棒性等） | 解决单一成功指标掩盖 operational flaws 与错误严重性问题 | AI Agent 可靠性评估与安全工程 |
| 62 | http://arxiv.org/abs/2602.17003v1 | Persona2Web: Benchmarking Personalized Web Agents for Contextual Reasoning with User History | 首个评估个性化 Web 代理的基准，基于澄清即个性化原则。 | 当前代理缺乏个性化能力，无法推断用户偏好和上下文。 | 个性化 Web 代理 |
| 63 | http://arxiv.org/abs/2602.17753v1 | The 2025 AI Agent Index: Documenting Technical and Safety Features of Deployed Agentic AI Systems | 记录 30 个最先进 AI 代理的技术和安全特征索引。 | 代理生态系统复杂且记录不一致，阻碍研究和政策制定。 | 代理生态系统追踪 |
| 64 | http://arxiv.org/abs/2602.09540v1 | SWE-Bench Mobile: Can Large Language Model Agents Develop Industry-Level Mobile Applications? | 引入 SWE-Bench Mobile 基准，评估 Agent 在真实 iOS 代码库上的工业级开发能力。 | 解决现有基准缺乏真实工业开发复杂性评估的问题，揭示 Agent 能力差距。 | 软件工程/移动开发 |
| 65 | http://arxiv.org/abs/2603.08721v1 | KernelCraft: Benchmarking for Agentic Close-to-Metal Kernel Generation on Emerging Hardware | 提出 KernelCraft 基准，评估 Agent 通过函数调用和反馈生成底层内核的能力。 | 解决新兴硬件内核开发耗时易错问题，评估 Agent 生成有效内核的潜力。 | 硬件内核开发 |
| 66 | http://arxiv.org/abs/2602.10046v1 | Artisan: Agentic Artifact Evaluation | 提出 Artisan 自动化 Agent，通过生成复现脚本评估研究结果可复现性。 | 解决人工 artifact 评估劳动密集问题，自动发现论文或 artifact 中的错误。 | 软件工程复现评估 |
| 67 | http://arxiv.org/abs/2602.13318v1 | DECKBench: Benchmarking Multi-Agent Frameworks for Academic Slide Generation and Editing | 引入 DECKBench 基准，评估多 Agent 幻灯片生成编辑的 fidelity 及指令遵循。 | 解决现有基准无法充分测量幻灯片生成中内容选择及布局渲染挑战的问题。 | 学术幻灯片生成 |
| 68 | http://arxiv.org/abs/2602.10620v1 | ISD-Agent-Bench: A Comprehensive Benchmark for Evaluating LLM-based Instructional Design Agents | 提出 ISD-Agent-Bench 基准，结合上下文矩阵及 ADDIE 模型评估教学 Agent。 | 解决缺乏标准化基准及 LLM-as-judge 偏差问题，确保评估可靠性。 | instructional Design |
| 69 | http://arxiv.org/abs/2602.10809v1 | DeepImageSearch: Benchmarking Multimodal Agents for Context-Aware Image Retrieval in Visual Histories | 引入 DeepImageSearch 范式，将图像检索重构为自主探索任务。 | 解决现有检索系统忽略视觉流中 temporal 序列依赖及 implicit 上下文线索问题。 | 视觉历史检索 |
| 70 | http://arxiv.org/abs/2602.10814v1 | See, Plan, Snap: Evaluating Multimodal GUI Agents in Scratch | 引入 ScratchWorld 基准，评估多模态 GUI Agent 在 Scratch 中程序构建任务。 | 解决缺乏评估 AI Agent 通过 GUI 构建程序能力及诊断失败来源的问题。 | 低代码教育/Scratch |
| 71 | http://arxiv.org/abs/2602.11224v1 | Agent-Diff: Benchmarking LLM Agents on Enterprise API Tasks via Code Execution with State-Diff-Based Evaluation | 提出 Agent-Diff 框架，通过 state-diff 契约及统一沙盒评估企业 API 任务。 | 解决基准在沙盒控制与生态效度间权衡问题，标准化评估不同 Agentic LLM。 | 企业 API 任务 |
| 72 | http://arxiv.org/abs/2602.17990v1 | WorkflowPerturb: Calibrated Stress Tests for Evaluating Multi-Agent Workflow Metrics | 提出 WorkflowPerturb 基准，通过扰动黄金工作流评估多智能体指标校准度 | 解决工作流评估指标未校准及严重程度不透明问题 | 多智能体工作流评估 |
| 73 | http://arxiv.org/abs/2602.18029v1 | Towards More Standardized AI Evaluation: From Models to Agents | 主张从模型评估转向系统评估，强调评估作为信任与控制功能 | 解决静态基准无法反映动态 Agent 系统行为的问题 | AI 系统评估范式 |
| 74 | http://arxiv.org/abs/2602.18940v1 | DREAM: Deep Research Evaluation with Agentic Metrics | 提出 DREAM 框架，使评估本身具备 Agent 能力以验证事实 | 解决深度研究报告评估缺乏事实及时效性验证能力问题 | 深度研究报告评估 |
| 75 | http://arxiv.org/abs/2602.18998v1 | Benchmark Test-Time Scaling of General LLM Agents | 引入 General AgentBench，研究通用 LLM Agent 测试时缩放行为 | 解决通用 Agent 缺乏统一评估环境及缩放效果不佳问题 | 通用 LLM Agent 评估 |
| 76 | http://arxiv.org/abs/2602.19073v1 | Evaluation and Benchmarking Suite for Financial Large Language Models and Agents | 金融 LLM 及 Agent 全生命周期评估与基准测试套件 | 解决通用 LLM 缺乏金融专业知识及复杂推理能力问题 | 金融 LLM 与 Agent |
| 77 | http://arxiv.org/abs/2602.19127v1 | AgenticRAGTracer: A Hop-Aware Benchmark for Diagnosing Multi-Step Retrieval Reasoning in Agentic RAG | 首个 hop 感知基准，自动构建多步检索推理诊断数据 | 解决现有基准缺乏中间 hop 问题导致细粒度评估困难问题 | Agentic RAG 推理 |
| 78 | http://arxiv.org/abs/2602.19547v1 | CIBER: A Comprehensive Benchmark for Security Evaluation of Code Interpreter Agents | 结合动态攻击生成与安全沙箱，系统评估代码解释器智能体漏洞 | 解决现有基准无法捕捉动态代码执行带来的安全风险问题 | 代码解释器智能体 |
| 79 | http://arxiv.org/abs/2602.19594v1 | ISO-Bench: Can Coding Agents Optimize Real-World Inference Workloads? | 结合硬执行与软 LLM 指标，评估编码智能体优化真实推理负载能力 | 解决现有基准易被游戏化且无法捕捉代码变更真实意图的问题 | 编码智能体/推理优化 |
| 80 | http://arxiv.org/abs/2602.19843v1 | MAS-FIRE: Fault Injection and Reliability Evaluation for LLM-Based Multi-Agent Systems | 定义 15 种故障类型，通过非侵入机制注入故障评估 MAS 可靠性 | 解决现有评估仅测端到端成功率无法洞察故障传播与恢复问题 | 多智能体系统可靠性 |
| 81 | http://arxiv.org/abs/2602.20292v2 | Quantifying the Expectation-Realisation Gap for Agentic AI Systems | 审查controlled trials，量化部署前期望与部署后结果的差异 | 解决智能体系统生产力增益期望与实际 outcomes 系统差异问题 | 智能体部署评估 |
| 82 | http://arxiv.org/abs/2602.20424v1 | Implicit Intelligence -- Evaluating Agents on What Users Don't Say | 提出 Implicit Intelligence 框架，评估智能体推理隐式需求能力 | 解决现有基准仅测显式指令遵循忽略隐式约束与上下文推理问题 | 智能体通用能力 |
| 83 | http://arxiv.org/abs/2602.21941v1 | MERRY: Semantically Decoupled Evaluation of Multimodal Emotional and Role Consistencies of Role-Playing Agents | 提出语义解耦评估框架，转换主观评分为双向证据寻找任务 | 解决多模态角色扮演智能体评估纠缠语义与模态生成问题 | 角色扮演智能体 |
| 84 | http://arxiv.org/abs/2602.21480v3 | Both Ends Count! Just How Good are LLM Agents at "Text-to-Big SQL"? | 引入新指标评估 Text-to-Big SQL，关注执行效率成本及数据规模。 | 解决现有 Text-to-SQL 基准忽略大规模数据成本与性能影响问题。 | 生产级 LLM 代理 |
| 85 | http://arxiv.org/abs/2602.22442v2 | A Framework for Assessing AI Agent Decisions and Outcomes in AutoML Pipelines | 提出决策中心评估代理，审计中间决策质量 | 解决现有AutoML评估仅关注最终结果，忽视过程的问题 | AutoML管道评估 |
| 86 | http://arxiv.org/abs/2602.22638v1 | MobilityBench: A Benchmark for Evaluating Route-Planning Agents in Real-World Mobility Scenarios | 构建基于真实用户查询的可复现路线规划基准 | 解决现实移动场景中代理评估缺乏 reproducibility 的问题 | 路线规划 Agent 评估 |
| 87 | http://arxiv.org/abs/2602.22769v2 | AMA-Bench: Evaluating Long-Horizon Memory for Agentic Applications | 构建包含真实与合成轨迹的长程记忆基准 | 解决现有记忆基准侧重对话忽视机器生成交互的问题 | 代理长程记忆评估 |
| 88 | http://arxiv.org/abs/2602.22953v1 | General Agent Evaluation | 提出通用代理评估协议与 Exgentic 框架 | 解决现有基准假设领域集成阻碍通用代理公平评估问题 | 通用代理能力评估 |
| 89 | http://arxiv.org/abs/2602.23166v2 | AgentVista: Evaluating Multimodal Agents in Ultra-Challenging Realistic Visual Scenarios | 构建涵盖 25 个子域的真实视觉场景基准 | 解决现有基准未捕捉长程多模态工具使用 realism 问题 | 多模态代理评估 |
| 90 | http://arxiv.org/abs/2602.23271v1 | Evaluating Stochasticity in Deep Research Agents | 形式化研究智能体随机性，提出评估框架量化系统方差，识别信息来源等三大根源。 | 解决深度研究代理在相同查询下输出结果 variability 过大影响部署的问题。 | 深度研究代理系统 |
| 91 | http://arxiv.org/abs/2603.03352v1 | Perfect score on IPhO 2025 theory by Gemini agent | 构建简单代理使用 Gemini 3.1 Pro，在国际物理奥林匹克理论题上实现满分。 | 验证 AI 模型在复杂物理推理任务上是否达到甚至超越人类金牌选手水平。 | 物理竞赛解题代理 |
| 92 | http://arxiv.org/abs/2603.00187v1 | ClarEval: A Benchmark for Evaluating Clarification Skills of Code Agents under Ambiguous Instructions | 提出 ClarEval 框架，通过注入模糊性评估代理的“协作商数”，量化澄清效率。 | 解决现有评估忽视代理在模糊指令下通过对话对齐用户意图能力的问题。 | 代码生成与协作代理 |
| 93 | http://arxiv.org/abs/2602.23729v1 | From Static Benchmarks to Dynamic Protocol: Agent-Centric Text Anomaly Detection for Evaluating LLM Reasoning | 提出以代理为中心的基准范式，通过动态协议自动生成验证解决问题，随能力扩展难度。 | 解决静态数据集无法捕捉模型 evolving 推理能力及扩展性有限的问题。 | LLM 推理能力评估 |
| 94 | http://arxiv.org/abs/2602.23949v1 | HotelQuEST: Balancing Quality and Efficiency in Agentic Search | 引入 HotelQuEST 基准，包含 214 个查询，评估质量与效率，解决偏好未指定问题。 | 解决现有基准忽视效率因素及未指定用户偏好挑战的问题。 | 代理搜索系统评估 |
| 95 | http://arxiv.org/abs/2603.00285v1 | TraderBench: How Robust Are AI Agents in Adversarial Capital Markets? | 引入 TraderBench，结合专家验证静态任务与对抗交易模拟，消除法官方差。 | 解决静态基准缺乏动态决策及 LLM 法官引入不可控方差的问题。 | 金融 AI 代理鲁棒性评估 |
| 96 | http://arxiv.org/abs/2603.00468v1 | Cloud-OpsBench: A Reproducible Benchmark for Agentic Root Cause Analysis in Cloud Systems | 引入 Cloud-OpsBench，采用状态快照范式构建确定性数字孪生，涵盖 452 个故障案例。 | 解决当前框架无法调和生态有效性与可复现性及缺乏主动推理评估的问题。 | 云系统根因分析代理 |
| 97 | http://arxiv.org/abs/2603.00501v1 | WirelessAgent++: Automated Agentic Workflow Design and Benchmarking for Wireless Networks | 提出 WirelessAgent++，将工作流设计视为程序搜索问题，用 MCTS 自动设计。 | 解决现有方法依赖手动 crafted 提示及静态工作流导致劳动密集且次优的问题。 | 无线网络代理工作流 |
| 98 | http://arxiv.org/abs/2603.00540v1 | LOGIGEN: Logic-Driven Generation of Verifiable Agentic Tasks | 提出逻辑驱动框架，基于硬编译策略接地、逻辑驱动前向合成及确定性状态验证合成数据。 | 解决现有工具中心反向合成管道无法捕捉真实应用严谨逻辑导致数据稀缺的问题。 | 代理任务数据合成 |
| 99 | http://arxiv.org/abs/2603.00601v4 | Theory of Code Space: Do Code Agents Understand Software Architecture? | 引入 ToCS 基准，评估代理在代码库探索中构建、维护及更新连贯架构信念的能力。 | 解决 AI 代码代理擅长孤立任务但 struggle 于需架构理解的多文件软件工程的问题。 | 代码代理架构理解评估 |
| 100 | http://arxiv.org/abs/2603.00646v1 | MoltGraph: A Longitudinal Temporal Graph Dataset of Moltbook for Coordinated-Agent Detection | 引入 MoltGraph 数据集，捕捉异构交互、时间漂移及可见性信号，用于协调代理检测。 | 解决缺乏纵向图原生数据集限制对代理社会网络协调行为严谨测量与学习监控的问题。 | 代理社交网络协调检测 |
| 101 | http://arxiv.org/abs/2603.00686v1 | RAVEL: Reasoning Agents for Validating and Evaluating LLM Text Synthesis | 引入 RAVEL 框架，使测试者自主规划执行典型合成操作， complement 以 C3EBench 基准。 | 解决当前评估框架缺乏评估实际合成操作如 outline、drafting、editing 能力的问题。 | LLM 文本合成能力评估 |
| 102 | http://arxiv.org/abs/2603.00801v1 | The Synthetic Web: Adversarially-Curated Mini-Internets for Diagnosing Epistemic Weaknesses of Language Agents | 引入 Synthetic Web Benchmark，程序生成环境，注入高似真性错误信息文章测量因果效应。 | 解决现有基准无法因果隔离代理对 adversarial 排名鲁棒性及缓解策略未测试的问题。 | 语言代理认识论弱点诊断 |

[返回目录](#目录)

<a id="cat-13"></a>

## 具身智能Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2602.01644v1 | From Perception to Action: Spatial AI Agents and World Models | 统一三轴分类法连接Agent能力与空间任务区分空间与符号接地 | 现有调查孤立处理Agent架构或空间领域缺乏统一框架 | 空间智能具身Agent研究 |
| 2 | http://arxiv.org/abs/2602.01662v3 | AgenticLab: A Real-World Robot Agent Platform that Can See, Think, and Act | 模型无关机器人Agent平台与基准支持开放世界操作评估 | 先验VLM操作管道难比较且评估依赖仿真或特权状态 | 真实机器人长程封闭环操作 |
| 3 | http://arxiv.org/abs/2602.02411v1 | Multi-Agent Monte Carlo Tree Search for Makespan-Efficient Object Rearrangement in Cluttered Spaces | 集中异步多智能体 MCTS 框架用于物体重排规划 | 解决杂乱环境中非单调任务的多智能体协作效率问题 | 仓库与救援现场机器人 |
| 4 | http://arxiv.org/abs/2602.04326v1 | From Assumptions to Actions: Turning LLM Reasoning into Uncertainty-Aware Planning for Embodied Agents | 规划器 - 作曲家 - 评估器框架，结构化决策树 | 具身代理在不确定环境中规划困难 | 具身代理/多代理环境 |
| 5 | http://arxiv.org/abs/2602.05249v1 | Automatic Cognitive Task Generation for In-Situ Evaluation of Embodied Agents | 提出动态原位任务生成方法，基于人类认知为未见环境定制评估任务。 | 解决现有基准数据污染且缺乏场景特异性，不足以评估未见设置能力的问题。 | 具身智能代理评估 |
| 6 | http://arxiv.org/abs/2602.05671v1 | (Computer) Vision in Action: Comparing Remote Sighted Assistance and a Multimodal Voice Agent in Inspection Sequences | 对比人类远程视力协助与多模态语音代理在检查序列中的协作实践。 | 解决多模态语音代理无法产生环境场合视觉行为，缺乏关键资源的问题。 | 视障人士辅助技术 |
| 7 | http://arxiv.org/abs/2602.06366v1 | Towards Adaptive Environment Generation for Training Embodied Agents | 提出闭环环境生成机制，根据 Agent 性能反馈自适应调整难度。 | 解决开放loop 环境生成效率低且缺乏针对性学习信号的问题。 | 具身 Agent 训练 |
| 8 | http://arxiv.org/abs/2602.11978v2 | Accelerating Robotic Reinforcement Learning with Agent Guidance | 用多模态智能体替换人类 supervisor，提供 corrective waypoints 和 spatial constraints | 人类监督比例 1:1 限制 scalability，操作疲劳 | 自主机器人强化学习 |
| 9 | http://arxiv.org/abs/2602.14438v1 | RoboSolver: A Multi-Agent Large Language Model Framework for Solving Robotic Arm Problems | LLM+VLM多Agent框架自动分析解决机械臂问题 | 机器人运动学计算复杂，需结合文本视觉输入 | 机器人机械臂控制与仿真 |
| 10 | http://arxiv.org/abs/2602.14526v1 | TWISTED-RL: Hierarchical Skilled Agents for Knot-Tying without Human Demonstrations | 多步强化学习策略替代单步逆模型，无需人类演示 | 机器人结绳因形变物体交互和拓扑约束极具挑战 | 机器人结绳任务 |
| 11 | http://arxiv.org/abs/2602.14968v1 | PhyScensis: Physics-Augmented LLM Agents for Complex Physical Scene Arrangement | LLM Agent+物理引擎迭代提出资产，求解器实现谓词 | 3D布局生成忽略物体间物理关系，场景复杂度低 | 机器人操作场景生成 |
| 12 | http://arxiv.org/abs/2602.15294v1 | EAA: Automating materials characterization with vision language model agents | 视觉语言模型Agent系统自动化复杂实验显微镜工作流 | 实验显微镜工作流复杂，需降低用户专业门槛 | 材料科学实验自动化 |
| 13 | http://arxiv.org/abs/2602.15400v1 | One Agent to Guide Them All: Empowering MLLMs for Vision-and-Language Navigation via Explicit World Representation | 解耦设计分离低级空间状态估计与高级语义规划 | 当前紧耦合设计限制导航Agent系统性能 | 视觉语言导航 |
| 14 | http://arxiv.org/abs/2602.09153v1 | SceneSmith: Agentic Generation of Simulation-Ready Indoor Scenes | 提出分层代理框架，生成物理属性完备的室内场景。 | 解决现有仿真环境缺乏真实室内空间多样性与物理复杂性。 | 家庭机器人训练仿真 |
| 15 | http://arxiv.org/abs/2602.09430v1 | Sci-VLA: Agentic VLA Inference Plugin for Long-Horizon Tasks in Scientific Experiments | 提出代理 VLA 推理插件，引导 VLA 模型执行复合任务。 | 解决 VLA 模型在长程科学实验中过渡操作失败问题。 | 机器人科学实验 |
| 16 | http://arxiv.org/abs/2602.13591v1 | AgentRob: From Virtual Forum Agents to Hijacked Physical Robots | 通过 MCP 协议连接论坛代理与物理机器人，实现社区介导的编排 | 解决虚拟代理与物理机器人集成 confined 于直接控制接口的问题 | 论坛驱动的机器人控制 |
| 17 | http://arxiv.org/abs/2602.16855v1 | Mobile-Agent-v3.5: Multi-platform Fundamental GUI Agents | 提出混合数据飞轮与统一思维合成，支持多平台云边协作实时交互 | 解决 GUI 代理多平台冲突及长程任务训练效率低的问题 | 多平台 GUI 自动化 |
| 18 | http://arxiv.org/abs/2602.14048v1 | ProAct: A Dual-System Framework for Proactive Embodied Social Agents | 解耦低延迟行为系统与慢认知系统，流式匹配模型注入主动意图 | 解决具身社会代理实时交互延迟预算与主动社会行为 deliberation 冲突问题 | 具身社会机器人交互 |
| 19 | http://arxiv.org/abs/2603.05522v2 | RoboLayout: Differentiable 3D Scene Generation for Embodied Agents | 引入可达性约束到可微布局优化，生成 Agent 可交互场景 | 解决生成场景物理不可行或 embodied Agent 无法交互问题 | 具身 Agent 室内场景生成 |
| 20 | http://arxiv.org/abs/2602.16308v1 | Markerless Robot Detection and 6D Pose Estimation for Multi-Agent SLAM | 利用深度学习 6D 姿态估计实现无标记多机器人 SLAM | 解决多机器人 SLAM 中数据关联受光照与标记限制问题 | 多机器人系统与环境感知 |
| 21 | http://arxiv.org/abs/2602.16444v2 | RoboGene: Boosting VLA Pre-training via Diversity-Driven Agentic Framework for Real-World Task Generation | 提出 RoboGene 框架，自动化生成多样物理可行机器人任务 | 解决机器人数据收集成本高且任务多样性不足的问题 | 通用机器人操作与 VLA 预训练 |
| 22 | http://arxiv.org/abs/2602.16898v3 | MALLVI: A Multi-Agent Framework for Integrated Generalized Robotics Manipulation | 多智能体闭环反馈框架，协调感知、定位、推理代理实现机器人操作。 | 开环操作在动态环境中脆弱，缺乏环境反馈的问题。 | 机器人操控 |
| 23 | http://arxiv.org/abs/2602.10116v2 | SAGE: Scalable Agentic 3D Scene Generation for Embodied AI | 提出 SAGE 框架，根据任务意图自动生成仿真就绪的 3D 环境供策略训练。 | 解决具身 Agent 真实数据收集成本高及现有场景生成物理无效的问题。 | 具身 AI 场景生成 |
| 24 | http://arxiv.org/abs/2602.18432v1 | SARAH: Spatially Aware Real-time Agentic Humans | 首个实时因果空间感知对话运动生成方法，部署于 VR 头显 | 解决具身 Agent 缺乏空间感知及自然 gaze 维持问题 | VR 数字人应用 |
| 25 | http://arxiv.org/abs/2603.00117v2 | PEPA: a Persistently Autonomous Embodied Agent with Personalities | 三层认知架构，通过人格特质实现具身 Agent 持久自主性 | 解决具身 Agent 依赖外部脚本目标缺乏长期自主性问题 | 具身机器人长期部署 |
| 26 | http://arxiv.org/abs/2602.20923v1 | ParkDiffusion++: Ego Intention Conditioned Joint Multi-Agent Trajectory Prediction for Automated Parking using Diffusion Models | 联合学习自我意图预测与意图条件的多智能体轨迹预测。 | 解决自动泊车中自我意图与周围代理交互预测孤立问题。 | 自动泊车系统 |
| 27 | http://arxiv.org/abs/2602.21622v1 | ADM-DP: Adaptive Dynamic Modality Diffusion Policy through Vision-Tactile-Graph Fusion for Multi-Agent Manipulation | 集成视觉触觉图模态，动态重加权模态实现灵活融合。 | 解决多代理机器人操纵中协调抓握稳定性及碰撞避免挑战。 | 多代理机器人操纵 |
| 28 | http://arxiv.org/abs/2602.21670v2 | Hierarchical LLM-Based Multi-Agent Framework with Prompt Optimization for Multi-Robot Task Planning | 上层分解任务分配下层，失败时应用 textual-gradient 优化 prompt。 | 解决多机器人任务规划中 PDDL 处理模糊指令及 LLM 幻觉问题。 | 异构机器人团队任务 |
| 29 | http://arxiv.org/abs/2602.22190v1 | GUI-Libra: Training Native GUI Agents to Reason and Act with Action-aware Supervision and Partially Verifiable RL | 提出 action-aware SFT 混合数据，识别 KL 正则化对稳定 RL 重要性。 | 解决开源原生 GUI 代理在长程导航任务落后及 grounding 差问题。 | 网页与移动 GUI 任务 |
| 30 | http://arxiv.org/abs/2602.22452v1 | CWM: Contrastive World Models for Action Feasibility Learning in Embodied Agent Pipelines | 提出对比世界模型，利用硬负例微调动作可行性评分 | 解决具身Agent动作规划中物理可行性判断不准的问题 | 具身机器人动作规划 |
| 31 | http://arxiv.org/abs/2602.22683v1 | SUPERGLASSES: Benchmarking Vision Language Models as Intelligent Agents for AI Smart Glasses | 构建基于智能眼镜真实数据的多模态 VQA 基准 | 解决现有数据集缺乏智能眼镜使用场景真实性的问题 | 智能眼镜视觉代理 |
| 32 | http://arxiv.org/abs/2602.22733v1 | Pixel2Catch: Multi-Agent Sim-to-Real Transfer for Agile Manipulation with a Single RGB Camera | 异质多代理 RL 框架实现单目视觉抓取迁移 | 解决高自由度机器人系统稳定学习与 Sim-to-Real 问题 | 机器人敏捷操作 |
| 33 | http://arxiv.org/abs/2602.22923v1 | WaterVideoQA: ASV-Centric Perception and Rule-Compliant Reasoning via Multi-Modal Agents | 提出 NaviMind 神经符号系统实现合规推理 | 解决自主水面船只缺乏知识驱动交互认知的问题 | 海事导航自主船只 |
| 34 | http://arxiv.org/abs/2602.23205v1 | EmbodMocap: In-the-Wild 4D Human-Scene Reconstruction for Embodied Agents | 双 iPhone 校准重建野生环境下人 - 场景数据 | 解决缺乏大规模场景条件人体运动数据限制训练问题 | 具身 AI 数据收集 |
| 35 | http://arxiv.org/abs/2602.23806v1 | "See, Act, Adapt: Active Perception for Unsupervised Cross-Domain Visual Adaptation via Personalized VLM-Guided Agent" | 提出 Sea^2 范式，适配部署方式而非感知模块，利用标量反馈导航至信息视点。 | 解决预训练感知模型在新环境中退化及微调导致灾难性遗忘的问题。 | 跨域视觉适应与导航 |
| 36 | http://arxiv.org/abs/2603.00349v1 | EmCoop: A Framework and Benchmark for Embodied Cooperation Among LLM Agents | 引入 EmCoop 基准框架，分离高层认知与低层具身交互层，表征代理协作。 | 解决现有基准难以进行具身多智能体系统中协作 emergent 及贡献细粒度分析的问题。 | 具身多智能体协作 |
| 37 | http://arxiv.org/abs/2603.00455v1 | Test-Driven Agentic Framework for Reliable Robot Controller | 提出测试驱动代理框架，利用结构化测试套件诊断反馈迭代细化控制器代码。 | 解决一次性控制器生成在初始提示未指定时可靠性与鲁棒性不足的问题。 | 机器人导航控制器合成 |
| 38 | http://arxiv.org/abs/2603.00676v1 | K^2-Agent: Co-Evolving Know-What and Know-How for Hierarchical Mobile Device Control | 提出分层框架，分离并协同进化声明性与程序性知识，高层引导低层执行。 | 解决现有移动设备控制代理在需长视野规划及精确操作复杂任务上表现差的问题。 | 移动设备控制代理 |

[返回目录](#目录)

<a id="cat-14"></a>

## Agent可解释性与透明度

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2602.02138v2 | CAM: A Causality-based Analysis Framework for Multi-Agent Code Generation Systems | 首个基于因果力的多智能体代码生成系统分析框架 | 量化中间输出对系统正确性的贡献以优化设计 | 多智能体代码生成系统 |
| 2 | http://arxiv.org/abs/2602.02475v1 | AgentRx: Diagnosing AI Agent Failures from Execution Trajectories | 自动化领域无关诊断框架，定位关键失败步骤 | 解决长程多智能体执行失败难以 localize 问题 | 智能体故障诊断 |
| 3 | http://arxiv.org/abs/2602.05183v2 | Data-Centric Interpretability for LLM-based Multi-Agent Reinforcement Learning | 应用预训练 SAE 和 LLM 总结器分析多 Agent RL 训练动态，发现细粒度行为。 | 解决复杂 RL 多智能体环境中难以理解训练过程中行为变化的问题。 | 多 Agent 强化学习 |
| 4 | http://arxiv.org/abs/2602.05353v2 | AgentXRay: White-Boxing Agentic Systems via Workflow Reconstruction | 提出代理工作流重建任务，通过搜索框架合成显式可解释工作流近似黑盒系统。 | 解决许多部署的代理系统对用户而言内部工作流不透明难以解释和控制的问题。 | 代理系统可解释性 |
| 5 | http://arxiv.org/abs/2602.05446v1 | DiLLS: Interactive Diagnosis of LLM-based Multi-agent Systems via Layered Summary of Agent Behaviors | 提出框架和交互系统，通过自然语言探测将多代理系统行为组织为多层摘要。 | 解决代理行为复杂性使得系统难以理解，失败时难以识别根本原因的问题。 | 多代理系统诊断 |
| 6 | http://arxiv.org/abs/2602.06841v3 | From Features to Actions: Explainability in Traditional and Agentic AI Systems | 比较 attribution-based 和 trace-based 解释方法，倡导 trajectory-level 可解释性。 | 解决静态解释方法无法诊断 agentic 轨迹执行失败的问题。 | 自主 AI 行为评估 |
| 7 | http://arxiv.org/abs/2602.13323v1 | Contrastive explanations of BDI agents | 扩展 BDI Agent 机制以回答对比性问题，评估其对信任发展的支持。 | 解决 Agent 解释缺乏对比性导致长度过长及信任支持不足的问题。 | BDI 智能体解释 |
| 8 | http://arxiv.org/abs/2602.23701v1 | From Flat Logs to Causal Graphs: Hierarchical Failure Attribution for LLM-based Multi-Agent Systems | 提出 CHIEF 框架，将轨迹转化为分层因果图，通过反事实归因区分根本原因。 | 解决现有方法将执行日志视为扁平序列导致责任边界模糊的问题。 | 多智能体系统故障归因 |
| 9 | http://arxiv.org/abs/2603.00623v1 | TraceSIR: A Multi-Agent Framework for Structured Analysis and Reporting of Agentic Execution Traces | 协调三专用代理，引入 TraceFormat 抽象格式压缩轨迹，进行细粒度诊断与报告。 | 解决长而复杂执行轨迹使故障诊断与根因分析极具挑战且手动检查不可扩展的问题。 | 代理执行轨迹分析 |

[返回目录](#目录)

<a id="cat-15"></a>

## 低代码/无代码Agent平台

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2602.16891v2 | OpenSage: Self-programming Agent Generation Engine | 首个支持 LLM 自动生成智能体拓扑与工具集的代理开发套件。 | 现有开发套件功能不足或依赖人工设计组件的问题。 | 智能体开发者 |

[返回目录](#目录)
