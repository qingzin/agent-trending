# AI agents 2025年9月学术分类汇总

共收录 675 篇论文，按研究方向分类整理如下。

## 目录

- [多Agent协作与通信（67篇）](#cat-01)
- [Agent记忆与知识管理（21篇）](#cat-02)
- [多Agent强化学习（66篇）](#cat-03)
- [Agent架构与框架设计（66篇）](#cat-04)
- [人机协作Agent（37篇）](#cat-05)
- [基于Agent的应用系统（128篇）](#cat-06)
- [具身智能Agent（32篇）](#cat-07)
- [Agent学习与自进化（37篇）](#cat-08)
- [Agent评测与基准（57篇）](#cat-09)
- [Agent安全与对齐（73篇）](#cat-10)
- [Agent可解释性与透明度（6篇）](#cat-11)
- [低代码/无代码Agent平台（4篇）](#cat-12)
- [Agent规划与推理（25篇）](#cat-13)
- [Agent工具使用与环境交互（20篇）](#cat-14)
- [Agent仿真与社会模拟（36篇）](#cat-15)

<a id="cat-01"></a>

## 多Agent协作与通信

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2509.08139v2 | SCA-LLM: Spectral-Attentive LLM-Based Wireless World Modeling for Agentic Communications | 提出谱通道注意力适配器，将CSI与LLM序列建模能力对齐 | LLM适配非文本时序信号时缺乏通道结构归纳偏置 | AI原生无线网络中的智能体通信 |
| 2 | http://arxiv.org/abs/2509.08157v2 | Risk-Bounded Multi-Agent Visual Navigation via Iterative Risk Allocation | 迭代风险分配层动态分配每Agent风险预算，集成CBS规划器 | 静态边剪枝策略过于保守，无法利用可接受的全局风险预算 | 危险环境中的多Agent视觉导航 |
| 3 | http://arxiv.org/abs/2509.08242v1 | Behaviorally Heterogeneous Multi-Agent Exploration Using Distributed Task Allocation | 将任务分配转化为非合作博弈，用d-PBRAG算法收敛到纳什均衡 | 异构机器人团队探索时的分布式任务分配优化 | 行为异构的多机器人探索系统 |
| 4 | http://arxiv.org/abs/2509.09210v1 | ProgD: Progressive Multi-scale Decoding with Dynamic Graphs for Joint Multi-agent Motion Forecasting | 渐进多尺度解码策略，用动态异构图显式捕捉未来场景中的演化社会交互 | 现有方法忽略多Agent未来运动中交互的演化特性 | 自动驾驶车辆的多Agent运动预测 |
| 5 | http://arxiv.org/abs/2509.09629v1 | Bridging the Capability Gap: Joint Alignment Tuning for Harmonizing LLM-based Multi-Agent Systems | MOAT框架交替进行规划Agent对齐和基础Agent改进，确保非递减收敛训练 | 独立微调Agent导致能力差距和协调不良 | 基于LLM的多Agent系统协作优化 |
| 6 | http://arxiv.org/abs/2509.03704v1 | QuantV2X: A Fully Quantized Multi-Agent System for Cooperative Perception | 首创全量化多智能体系统，统一量化模型与传输消息 | 解决 V2X 协同感知中计算负载高与传输带宽受限问题 | 车联网协同感知 |
| 7 | http://arxiv.org/abs/2509.03727v1 | Adversarial Decision-Making in Partially Observable Multi-Agent Systems: A Sequential Hypothesis Testing Approach | 将欺骗建模为动态优化问题，采用序贯假设测试框架 | 解决部分可观察环境下对抗性决策中的战略误导问题 | 网络安全与自主决策 |
| 8 | http://arxiv.org/abs/2509.04310v3 | EvoEmo: Towards Evolved Emotional Policies for Adversarial LLM Agents in Multi-Turn Price Negotiation | 演化强化学习框架优化谈判中的动态情感表达策略 | 解决 LLM 代理在谈判中因被动情感响应易被操纵问题 | 多轮价格谈判代理 |
| 9 | http://arxiv.org/abs/2509.04687v2 | Guideline-Consistent Segmentation via Multi-Agent Refinement | 协调通用视觉语言模型进行迭代工人 - 监督者细化 | 解决长文本标注指南下语义分割难以遵循规则问题 | 语义分割与标注 |
| 10 | http://arxiv.org/abs/2509.04876v1 | OSC: Cognitive Orchestration through Dynamic Knowledge Alignment in Multi-Agent LLM Collaboration | 引入协作者知识模型实现动态认知状态感知与对齐 | 解决专家代理间深度协作的语言交互瓶颈 | 多智能体 LLM 协作 |
| 11 | http://arxiv.org/abs/2509.04993v1 | LLM Enabled Multi-Agent System for 6G Networks: Framework and Method of Dual-Loop Edge-Terminal Collaboration | 提出双环终端 - 边缘协作框架增强 LLM 代理规划能力 | 解决网络设备资源有限 hindering 复杂工具调用问题 | 6G 网络智能服务 |
| 12 | http://arxiv.org/abs/2509.01182v2 | Question-to-Knowledge (Q2K): Multi-Agent Generation of Inspectable Facts for Product Mapping | 三agent协作（推理+知识+去重）+人类反馈，复用推理轨迹减少冗余搜索 | 电商产品映射中规则方法难以处理品牌/规格等细微差异 | 电商平台的产品去重与SKU映射任务 |
| 13 | http://arxiv.org/abs/2509.01228v1 | OpenMulti: Open-Vocabulary Instance-Level Multi-Agent Distributed Implicit Mapping | 跨agent实例对齐构建协作图，跨渲染监督缓解盲区优化陷阱 | 现有分布式mapping缺乏实例级语义理解，影响下游应用 | 多机器人协同建图与语义标注任务 |
| 14 | http://arxiv.org/abs/2509.01232v1 | FantasyHSI: Video-Generation-Centric 4D Human Synthesis In Any Scene through A Graph-based Multi-Agent Framework | 动态有向图建模+三agent协作（导航+规划+批评），DPO训练提升物理真实性 | HSI难以处理长程任务、泛化到未知场景、保证长期逻辑一致性 | 复杂场景中的人 - 景交互视频生成 |
| 15 | http://arxiv.org/abs/2509.01238v2 | Towards Open-World Retrieval-Augmented Generation on Knowledge Graph: A Multi-Agent Collaboration Framework | 预测器+多检索器+监督者三agent协作，动态识别候选锚点并行多跳探索 | 开放世界中查询与KG实体链接不可靠，限制传统KG-RAG鲁棒性 | 无需预定义锚点的开放世界知识图谱问答 |
| 16 | http://arxiv.org/abs/2509.01277v1 | Communicative Agents for Slideshow Storytelling Video Generation based on LLMs | 多communicative agent分工协作（脚本+场景+音频），chat tower工作流降低计算成本 | 传统text-to-video模型计算成本高，难以规模化生成叙事视频 | 低成本幻灯片式叙事视频自动生成 |
| 17 | http://arxiv.org/abs/2509.01835v2 | From CVE Entries to Verifiable Exploits: An Automated Multi-Agent Framework for Reproducing CVEs | LLM多agent框架自动收集资源、重建环境、生成可验证漏洞利用代码 | 高质量漏洞数据集构建依赖人工专家，成本高、规模有限 | 自动化生成可复现CVE基准用于安全研究与AI能力评估 |
| 18 | http://arxiv.org/abs/2509.02317v1 | AI Agent Communication from Internet Architecture Perspective: Challenges and Opportunities | 首次从互联网架构五要素（可扩展/安全/实时/高性能/可管理）系统分析agent通信 | agent通信框架碎片化，缺乏系统性视角指导可扩展生态发展 | 构建可持续、互操作的多agent通信基础设施 |
| 19 | http://arxiv.org/abs/2509.04508v2 | ProST: Progressive Sub-task Training for Pareto-Optimal Multi-agent Systems Using Small Language Models | 渐进式子任务训练策略类比课程学习，小模型多agent系统实现帕累托最优效率 | 小模型长轨迹学习困难，即使角色特化也难以有效掌握全部子任务 | 资源受限场景下复杂问题的多agent协作求解 |
| 20 | http://arxiv.org/abs/2509.05651v1 | Orchestrator: Active Inference for Multi-Agent Systems in Long-Horizon Tasks | 引入注意力启发式自涌现协调机制，优化全局任务性能 | 解决长程任务中部分可观测导致的协作次优问题 | 复杂非线性任务的多智能体系统 |
| 21 | http://arxiv.org/abs/2509.05764v1 | DRF: LLM-AGENT Dynamic Reputation Filtering Framework | 构建交互式评级网络与声誉评分机制，动态过滤低信誉代理 | 解决多智能体系统中代理性能量化与可信度评估缺失 | 大规模多智能体协作任务 |
| 22 | http://arxiv.org/abs/2509.07234v1 | Efficient Multi-Agent Coordination via Dynamic Joint-State Graph Construction | 动态构建联合状态图，利用代理同质性剪枝冗余状态 | 解决高风险边遍历中多代理主动协调计算复杂度高的问题 | 协作路径规划与优化 |
| 23 | http://arxiv.org/abs/2509.10284v1 | A Holistic Architecture for Monitoring and Optimization of Robust Multi-Agent Path Finding Plan Execution | 利用动作依赖图监控执行，动态决策是否重规划 | 解决多智能体路径执行中延迟导致的碰撞与效率问题 | 自主仓库机器人车队 |
| 24 | http://arxiv.org/abs/2509.11035v1 | Free-MAD: Consensus-Free Multi-Agent Debate | 无需共识的辩论框架，基于评分机制评估推理轨迹 | 解决传统多 agent 辩论 token 开销大及错误传播问题 | 大模型推理增强 |
| 25 | http://arxiv.org/abs/2509.12446v2 | PromptSculptor: Multi-Agent Based Text-to-Image Prompt Optimization | 分解任务为四个 specialized 代理协作优化文本生成图像提示词 | 解决用户需多轮手动 refinement 才能生成高质量图像问题 | 文本生成图像模型 |
| 26 | http://arxiv.org/abs/2509.12546v1 | Agent4FaceForgery: Multi-Agent LLM Framework for Realistic Face Forgery Detection | 多代理模拟伪造创建过程，生成带 nuanced 标签的样本 | 解决面部伪造检测中训练数据生态无效性与文本图像交互建模问题 | 面部伪造检测 |
| 27 | http://arxiv.org/abs/2509.12612v1 | GBV-SQL: Guided Generation and SQL2Text Back-Translation Validation for Multi-Agent Text2SQL | 引入 SQL2Text 回译验证机制，确保生成查询逻辑对齐用户意图 | 解决 Text2SQL 生成中语法有效但语义误解用户意图问题 | 文本到 SQL 生成 |
| 28 | http://arxiv.org/abs/2509.13677v1 | AgentCTG: Harnessing Multi-Agent Collaboration for Fine-Grained Precise Control in Text Generation | 模拟多智能体工作流控制机制，实现细粒度文本生成控制。 | 解决可控文本生成中细粒度条件控制难及扩展性问题。 | 自然语言处理与内容生成 |
| 29 | http://arxiv.org/abs/2509.14034v1 | Enhancing Multi-Agent Debate System Performance via Confidence Expression | 在多智能体辩论中引入置信度表达机制，优化辩论动态。 | 解决智能体辩论中因缺乏置信度表达导致收敛次优的问题。 | 多智能体辩论系统 |
| 30 | http://arxiv.org/abs/2509.14547v1 | (P)rior(D)yna(F)low: A Priori Dynamic Workflow Construction via Multi-Agent Collaboration | 结合 Q 表学习与先验决策，动态构建工作流。 | 解决自动工作流构建仅依赖历史经验导致效率适应性低问题。 | 大语言模型工作流构建 |
| 31 | http://arxiv.org/abs/2509.14860v1 | MARIC: Multi-Agent Reasoning for Image Classification | 将图像分类重构为多智能体协作推理过程，综合多视角。 | 解决视觉语言模型单 pass 表示无法捕捉视觉内容互补性问题。 | 图像分类任务 |
| 32 | http://arxiv.org/abs/2509.15786v1 | Building Data-Driven Occupation Taxonomies: A Bottom-Up Multi-Stage Approach via Semantic Clustering and Multi-Agent Collaboration | 利用全局语义聚类与反思型多智能体系统，自动构建职业分类体系。 | 解决手动构建职业分类慢且现有自动方法难以适应动态市场的问题。 | 劳动力市场/职业分类 |
| 33 | http://arxiv.org/abs/2509.16736v1 | Towards Transparent and Incentive-Compatible Collaboration in Decentralized LLM Multi-Agent Systems: A Blockchain-Driven Approach | 基于区块链实现透明代理注册、任务分配与动态声誉追踪机制。 | 解决去中心化环境中多智能体协作缺乏透明度与集中激励塑造的问题。 | 去中心化多智能体系统/区块链 |
| 34 | http://arxiv.org/abs/2509.16839v2 | Roundtable Policy: Confidence-Weighted-Consensus Aggregation Improves Multi-Agent-System Reasoning | 提出圆桌策略，通过多 LLM 加权共识进行推理，强调结构化可解释性。 | 解决多智能体系统中特定选择偏好原因不透明且收敛过程 opaque 的问题。 | 多智能体推理/科学任务 |
| 35 | http://arxiv.org/abs/2509.17195v1 | MAST: Multi-Agent Spatial Transformer for Learning to Collaborate | 提出多代理空间 Transformer，学习去中心化协作通信策略。 | 解决大规模去中心化多机器人系统中部分观测与通信受限的协作挑战。 | 多机器人系统/协作学习 |
| 36 | http://arxiv.org/abs/2509.17429v4 | Multi-scale Temporal Prediction via Incremental Generation and Multi-agent Collaboration | 提出增量生成模块与决策驱动多代理协作框架，平衡全局连贯与局部 fidelity。 | 解决视觉语言模型难以预测多时间尺度场景细粒度状态的问题。 | 场景理解/时间预测 |
| 37 | http://arxiv.org/abs/2509.19236v1 | AgentInit: Initializing LLM-based Multi-Agent Systems via Diversity and Expertise Orchestration for Effective and Efficient Collaboration | 多样性与专家编排优化 Agent 团队初始化结构 | 解决多智能体系统初始化未充分考虑协作需求问题 | 多智能体系统初始化 |
| 38 | http://arxiv.org/abs/2509.19599v1 | Knowledge Base-Aware Orchestration: A Dynamic, Privacy-Preserving Method for Multi-Agent Systems | 动态隐私保护相关性信号增强静态描述进行任务路由 | 解决动态环境中静态描述导致任务路由低效问题 | 大规模知识密集型系统 |
| 39 | http://arxiv.org/abs/2509.21593v1 | GeoEvolve: Automating Geospatial Model Discovery via Multi-Agent Large Language Models | 多Agent LLM框架耦合进化搜索与地理空间领域知识 | 现有LLM算法发现框架缺乏地理空间领域知识 | 地理空间建模、可持续发展研究 |
| 40 | http://arxiv.org/abs/2509.21772v2 | PhishLumos: An Adaptive Multi-Agent System for Proactive Phishing Campaign Mitigation | LLM多Agent主动挖掘攻击基础设施共享模式 | 钓鱼防御被动反应，无法应对现代规避战术 | 网络安全、钓鱼攻击防御 |
| 41 | http://arxiv.org/abs/2509.21789v3 | Visual Multi-Agent System: Mitigating Hallucination Snowballing via Visual Flow | ViF范式通过视觉流中继token，重分配注意力抑制幻觉雪崩 | 多Agent视觉幻觉在文本流转中逐级放大 | 视觉语言模型多Agent系统 |
| 42 | http://arxiv.org/abs/2509.21848v1 | Graph of Agents: Principled Long Context Modeling by Emergent Multi-Agent Collaboration | 将长上下文建模形式化为压缩问题，动态构建输入依赖协作结构 | 多Agent系统性能依赖手工协作策略和提示工程，泛化性差 | 长文档问答、超越上下文窗口限制 |
| 43 | http://arxiv.org/abs/2509.21981v3 | Collaborative Belief Reasoning with LLMs for Efficient Multi-Agent Collaboration | CoBel-World内部表征联合建模物理环境和协作者心理状态 | 现有协作框架忽视LLM推理潜力进行动态意图推断 | 部分可观察环境协作、 embodied 任务 |
| 44 | http://arxiv.org/abs/2510.13821v1 | LLM Agent Communication Protocol (LACP) Requires Urgent Standardization: A Telecom-Inspired Protocol is Necessary | 提出三层LACP架构确保语义清晰、事务完整、内置安全 | 当前ad-hoc通信方法造成碎片化生态，阻碍创新且有风险 | 分布式AI、6G及以后多Agent系统 |
| 45 | http://arxiv.org/abs/2509.22522v3 | JointDiff: Bridging Continuous and Discrete in Multi-Agent Trajectory Generation | JointDiff扩散框架同时生成连续时空数据和同步离散事件 | 生成模型常将连续数据和离散事件视为分离过程，存在gap | 体育领域多Agent轨迹、控球事件生成 |
| 46 | http://arxiv.org/abs/2509.19918v1 | Beyond Language Barriers: Multi-Agent Coordination for Multi-Language Code Generation | 提出 XL-CoGen 多智能体架构，通过数据驱动选择桥接语言，实现跨语言代码生成协同。 | 解决多语言代码生成中模型能力差异大、知识无法共享的问题。 | 多编程语言代码生成 |
| 47 | http://arxiv.org/abs/2509.20502v1 | MARS: toward more efficient multi-agent collaboration for LLM reasoning | 提出基于角色的协作框架，作者生成、评审独立反馈，避免昂贵评审间交互。 | 解决多智能体辩论计算开销大、通信频繁导致成本高的问题。 | LLM 推理任务 |
| 48 | http://arxiv.org/abs/2509.20900v3 | Learning to Summarize by Learning to Quiz: Adversarial Agentic Collaboration for Long Document Summarization | 提出 SummQ 框架，通过摘要与测验代理的对抗协作迭代优化长文档摘要。 | 解决长文档摘要信息丢失、事实不一致及连贯性差的问题。 | 长文档摘要 |
| 49 | http://arxiv.org/abs/2509.21004v2 | Multi-Agent Inverted Transformer for Flight Trajectory Prediction | 提出 MAIFormer，利用掩码多变量注意力与代理注意力建模个体行为与交互。 | 解决多飞机轨迹预测中个体行为与复杂交互建模难及可解释性差的问题。 | 空中交通流量管理 |
| 50 | http://arxiv.org/abs/2509.21054v1 | Disagreements in Reasoning: How a Model's Thinking Process Dictates Persuasion in Multi-Agent Systems | 揭示推理过程透明化显著增加说服能力，发现 persuasion duality 权衡。 | 解决多智能体系统中说服动态及模型内部处理架构对外部行为影响不明的问题。 | 多智能体说服与交互 |
| 51 | http://arxiv.org/abs/2509.21193v1 | Eigen-1: Adaptive Multi-Agent Refinement with Monitor-Based RAG for Scientific Reasoning | 结合隐式检索与结构化协作，层次化解方案细化适应解决方案质量。 | 解决显式检索碎片化推理及多智能体管道平均化稀释强解的问题。 | 科学推理任务 |
| 52 | http://arxiv.org/abs/2509.21464v2 | Residual Vector Quantization For Communication-Efficient Multi-Agent Perception | 提出 ReVQom 学习特征编解码器，通过多阶段残差矢量量化压缩中间特征。 | 解决多代理协作感知中通信带宽限制可扩展性的问题。 | 多代理协作感知 |
| 53 | http://arxiv.org/abs/2509.23055v1 | Peacemaker or Troublemaker: How Sycophancy Shapes Multi-Agent Debate | 定义多智能体辩论中的谄媚行为，分析其对共识的影响。 | 解决多智能体辩论中因过度一致导致的早期共识崩溃。 | 多智能体辩论系统 |
| 54 | http://arxiv.org/abs/2509.23251v1 | XGC-AVis: Towards Audio-Visual Content Understanding with a Multi-Agent Collaborative System | 四阶段多智能体框架，增强音视频时序对齐与检索。 | 解决多模态大模型在音视频质量感知与对齐上的不足。 | 音视频内容理解 |
| 55 | http://arxiv.org/abs/2509.23537v2 | Beyond the Strongest LLM: Multi-Turn Multi-Agent Orchestration vs. Single LLMs on Benchmarks | 研究多轮多智能体编排，分析作者可见性与投票对共识影响。 | 探索多智能体协作是否超越单一最强模型的性能上限。 | 通用基准测试任务 |
| 56 | http://arxiv.org/abs/2509.24046v2 | PartnerMAS: An LLM Hierarchical Multi-Agent Framework for Business Partner Selection on High-Dimensional Features | 提出分层多智能体框架，分解评估任务，提升高维决策一致性 | 解决单智能体在高维商业伙伴选择中扩展性与一致性差的问题 | 商业伙伴选择/风投 |
| 57 | http://arxiv.org/abs/2509.24088v1 | CORRECT: COndensed eRror RECognition via knowledge Transfer in multi-agent systems | 利用蒸馏错误模式缓存，实现无需训练的多智能体系统错误识别 | 解决多智能体系统错误传播难调试及分析成本高的问题 | 复杂多智能体任务 |
| 58 | http://arxiv.org/abs/2509.24314v1 | MedMMV: A Controllable Multimodal Multi-Agent Framework for Reliable and Verifiable Clinical Reasoning | 通过多样化短 rollout 与证据图约束，稳定多模态临床推理 | 解决多模态模型早期证据解释不稳定导致幻觉 cascade 问题 | 临床决策支持 |
| 59 | http://arxiv.org/abs/2509.24350v1 | Dynamic Orchestration of Multi-Agent System for Real-World Multi-Image Agricultural VQA | 提出自反思多智能体框架，整合检索、反思、回答与改进角色 | 解决农业 VQA 中多图像输入及证据不完整适应性问题 | 农业视觉问答 |
| 60 | http://arxiv.org/abs/2509.24855v1 | PhysicsMinions: Winning Gold Medals in the Latest Physics Olympiads with a Coevolutionary Multimodal Multi-Agent System | 提出协同进化多智能体系统，通过视觉、逻辑与评审工作室协作解题 | 解决物理奥林匹克竞赛中复杂推理与多模态理解挑战 | 物理竞赛解题 |
| 61 | http://arxiv.org/abs/2509.25185v1 | PixelCraft: A Multi-Agent System for High-Fidelity Visual Reasoning on Structured Images | 包含调度器、规划器等多角色的高保真视觉推理系统 | 结构化图像感知错误导致推理结论错误 | 图表与几何 diagram 理解 |
| 62 | http://arxiv.org/abs/2509.25586v1 | ATLAS: Constraints-Aware Multi-Agent Collaboration for Real-World Travel Planning | 处理动态约束管理的通用多智能体框架 | 复杂约束下难以生成最优接地解决方案 | 现实世界旅行规划 |
| 63 | http://arxiv.org/abs/2509.26126v1 | The Hunger Game Debate: On the Emergence of Over-Competition in Multi-Agent Systems | 模拟零和竞争竞技场下辩论的实验框架 | 竞争压力导致不可靠有害行为 | 多智能体辩论系统 |
| 64 | http://arxiv.org/abs/2510.00311v1 | CORTEX: Collaborative LLM Agents for High-Stakes Alert Triage | specialized agents 协作 over 真实证据的多智能体架构 | 单模型解释日志检索上下文 end-to-end 困难 | 安全运营中心警报分类 |
| 65 | http://arxiv.org/abs/2510.00317v1 | MAVUL: Multi-Agent Vulnerability Detection via Contextual Reasoning and Interactive Refinement | 集成上下文推理和交互 refinement 的多智能体 VD 系统 | 现有方法上下文理解不足且交互单一 | 开源软件漏洞检测 |
| 66 | http://arxiv.org/abs/2510.00326v1 | Reasoning-Aware Prompt Orchestration: A Foundation Model for Multi-Agent Language Model Coordination | 动态提示编排增强多个 specialized agents 推理 | 通过提示工程协调推理能力具有挑战性 | 多智能体语言模型协调 |
| 67 | http://arxiv.org/abs/2510.01285v2 | LLM-Based Multi-Agent Blackboard System for Information Discovery in Data Science | 受黑板架构启发的多智能体范式 | 主从多智能体系统依赖 rigid 中央控制器 | 数据科学信息发现 |

[返回目录](#目录)

<a id="cat-02"></a>

## Agent记忆与知识管理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2509.08151v2 | Trust Semantics Distillation for Collaborator Selection via Memory-Augmented Agentic AI | 教师-学生Agent架构，服务器端增强记忆模块进行信任语义蒸馏 | 资源受限设备独立评估协作者时开销大、时效性差 | 协作计算中的可信协作者选择 |
| 2 | http://arxiv.org/abs/2509.09498v3 | SEDM: Scalable Self-Evolving Distributed Memory for Agents | 可验证写入准入、自调度记忆控制器、跨域知识扩散，将记忆转为主动自优化组件 | 长期多Agent系统产生大量轨迹，现有方法易受噪声积累和内存无控扩展影响 | 开放-ended多Agent协作的记忆管理 |
| 3 | http://arxiv.org/abs/2509.03891v1 | MobileRAG: Enhancing Mobile Agent with Retrieval-Augmented Generation | 提出包含 Inter/Local/MemRAG 的移动代理增强框架 | 解决移动代理依赖 LLM 理解力及缺乏记忆与环境交互问题 | 智能手机移动任务 |
| 4 | http://arxiv.org/abs/2509.03990v2 | Meta-Policy Reflexion: Reusable Reflective Memory and Rule Admissibility for Resource-Efficient LLM Agent | 将反思 consolidates 为结构化元策略记忆，支持规则准入 | 解决现有反思策略 ephemeral 且无法跨任务复用问题 | 资源高效 LLM 代理 |
| 5 | http://arxiv.org/abs/2509.06269v1 | REMI: A Novel Causal Schema Memory Architecture for Personalized Lifestyle Recommendation Agents | 集成个人因果知识图谱与模式规划模块，提供可解释推荐 | 解决个性化助手缺乏复杂个人数据与因果知识整合问题 | 生活方式推荐与个人助理 |
| 6 | http://arxiv.org/abs/2509.11914v2 | EgoMem: Lifelong Memory Agent for Full-duplex Omnimodal Models | 首创全双工模型终身记忆代理，异步处理检索与记忆管理 | 解决实时多模态流中用户识别与长期知识维护难题 | 实时多模态对话系统 |
| 7 | http://arxiv.org/abs/2509.12810v1 | H$^2$R: Hierarchical Hindsight Reflection for Multi-Task LLM Agents | 提出分层记忆架构，解耦高层规划与低层执行记忆 | 解决多任务场景中 prior 经验被视为单体单元导致知识转移低效问题 | 多任务 LLM 代理 |
| 8 | http://arxiv.org/abs/2509.16369v1 | Enhancing Financial RAG with Agentic AI and Multi-HyDE: A Novel Approach to Knowledge Retrieval and Hallucination Reduction | 利用多 HyDE 系统生成多查询，结合代理工作流优化金融知识检索。 | 解决金融问答中数据源复杂、传统检索系统准确率与可靠性低的问题。 | 金融问答/知识检索 |
| 9 | http://arxiv.org/abs/2509.17459v1 | PRINCIPLES: Synthetic Strategy Memory for Proactive Dialogue Agents | 通过离线自博弈模拟生成合成策略记忆，指导推理时策略规划。 | 解决主动对话策略规划覆盖有限、存在偏好偏差且依赖昂贵训练的问题。 | 对话代理/策略规划 |
| 10 | http://arxiv.org/abs/2509.21710v2 | Think-on-Graph 3.0: Efficient and Adaptive LLM Reasoning on Heterogeneous Graphs via Multi-Agent Dual-Evolving Context Retrieval | 多Agent上下文演化检索机制，动态构建异构图索引 | 现有GraphRAG依赖高质量知识图谱，扩展性差 | 知识图谱检索、复杂推理任务 |
| 11 | http://arxiv.org/abs/2509.22009v2 | GraphSearch: An Agentic Deep Searching Workflow for Graph Retrieval-Augmented Generation | 六模块模块化框架，双通道检索（语义+关系查询） | 现有GraphRAG检索浅层，无法利用预构建结构图数据 | 多跳RAG、复杂查询图检索 |
| 12 | http://arxiv.org/abs/2511.03728v1 | Efficient On-Device Agents via Adaptive Context Management | 利用专用 LoRA 适配器蒸馏对话历史，实现动态内存与即时模式传递。 | 解决设备端 AI 代理内存受限、上下文窗口小导致交互能力弱的问题。 | 设备端 AI 代理 |
| 13 | http://arxiv.org/abs/2509.21212v1 | SGMem: Sentence Graph Memory for Long-Term Conversational Agents | 将对话表示为分块单元内的句子级图，捕获跨轮次会话级上下文关联。 | 解决长时对话代理难以组织检索不同粒度对话及生成记忆的问题。 | 长时对话代理 |
| 14 | http://arxiv.org/abs/2509.23040v5 | Look Back to Reason Forward: Revisitable Memory for Long-Context LLM Agents | 集成记忆检索机制，支持非线性推理与历史回溯。 | 解决长上下文问答中证据丢失与信息退化问题。 | 长上下文 LLM 智能体 |
| 15 | http://arxiv.org/abs/2510.02369v3 | AutoContext: Instance-Level Context Learning for LLM Agents | 解耦探索与任务求解，构建可复用知识图谱作为实例级上下文 | 解决智能体缺乏实例级上下文导致重复探索及决策脆弱问题 | 通用 LLM 智能体 |
| 16 | http://arxiv.org/abs/2509.24704v2 | MemGen: Weaving Generative Latent Memory for Self-Evolving Agents | 提出动态生成记忆框架，通过记忆触发与编织增强推理 | 解决现有记忆范式无法捕捉推理与记忆流体交织的问题 | 通用自进化智能体 |
| 17 | http://arxiv.org/abs/2509.25299v1 | ID-RAG: Identity Retrieval-Augmented Generation for Long-Horizon Persona Coherence in Generative Agents | 基于动态知识图谱的身份检索增强生成机制 | 解决长程任务中智能体身份漂移和幻觉问题 | 生成式智能体与角色扮演 |
| 18 | http://arxiv.org/abs/2509.25140v2 | ReasoningBank: Scaling Agent Self-Evolving with Reasoning Memory | 从成功失败经验中蒸馏可泛化推理策略的记忆框架 | 智能体无法从累积交互历史中学习 | 持续任务与自我进化 |
| 19 | http://arxiv.org/abs/2509.26200v1 | Toward an Unbiased Collective Memory for Efficient LLM-Based Agentic 6G Cross-Domain Management | 包含语义检索和失败学习的无偏记忆设计 | 智能体检索过去经验时的认知偏差 | 6G 跨域资源管理 |
| 20 | http://arxiv.org/abs/2509.26383v4 | Efficient and Transferable Agentic Knowledge Graph RAG via Reinforcement Learning | 通过 RL 优化单智能体与 KG 交互的检索增强生成框架 | 多模块系统推理成本高且绑定特定 KG | 知识图谱问答 |
| 21 | http://arxiv.org/abs/2510.02388v2 | Learning to Route: A Rule-Driven Agent Framework for Hybrid-Source Retrieval-Augmented Generation | 基于规则驱动路由框架选择最适合的增强路径 | 数据库和文档结合引入 noise 且成本无增益 | 混合源检索增强生成 |

[返回目录](#目录)

<a id="cat-03"></a>

## 多Agent强化学习

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2509.08257v2 | Symmetry-Guided Multi-Agent Inverse Reinforcement Learning | 将对称性整合到多Agent对抗IRL算法中，显著提升样本效率 | 多机器人系统中专家演示收集成本高，样本效率低 | 多机器人系统的逆强化学习 |
| 2 | http://arxiv.org/abs/2509.08310v1 | Game-Theoretic Resilience Framework for Cyber-Physical Microgrids using Multi-Agent Reinforcement Learning | 博弈论框架整合四种韧性指标，用多Agent Q学习应对自适应攻击 | 现代电力系统对网络物理基础设施依赖增加，面临定向网络攻击风险 | 网络物理微电网的韧性防御 |
| 3 | http://arxiv.org/abs/2509.08956v1 | Multi-Agent Inverse Reinforcement Learning for Identifying Pareto-Efficient Coordination -- A Distributionally Robust Approach | 推导帕累托高效协调的必要充分条件，提供分布鲁棒效用估计算法 | 从噪声测量中构建统计检测器识别多Agent系统的帕累托高效行为 | UAV协调检测与效用函数重构 |
| 4 | http://arxiv.org/abs/2509.09135v3 | Continuous-Time Value Iteration for Multi-Agent Reinforcement Learning | CT-MARL框架用PINNs近似HJB值函数，引入VGI模块迭代优化值梯度 | 连续时间RL在多Agent领域应用受限，中心化值函数近似困难 | 高频率交互的复杂动力学系统 |
| 5 | http://arxiv.org/abs/2509.03682v1 | A Comprehensive Review of Multi-Agent Reinforcement Learning in Video Games | 全面综述 MARL 在各类视频游戏中的应用与挑战 | 梳理 MARL 技术发展脉络及在游戏 AI 中的关键挑战 | 视频游戏 AI 系统 |
| 6 | http://arxiv.org/abs/2509.03817v2 | Learning to Deliberate: Meta-policy Collaboration for Agentic LLMs with Multi-agent Reinforcement Learning | 提出元策略审议框架，学习去中心化元认知动作策略 | 解决固定协作协议忽略代理内部审议能力的局限 | 复杂推理多智能体系统 |
| 7 | http://arxiv.org/abs/2509.03974v1 | Real-time adaptive quantum error correction by model-free multi-agent learning | 利用无模型 MARL 发现量子纠错码并实时适应噪声 | 解决时变噪声下量子纠错效率低及重训练步骤多问题 | 量子计算错误纠正 |
| 8 | http://arxiv.org/abs/2509.05051v1 | QCA-MolGAN: Quantum Circuit Associative Molecular GAN with Multi-Agent Reinforcement Learning | 结合量子电路 Born 机与 MARL 生成药物分子 | 解决药物发现中化学空间导航及多属性平衡优化问题 | 药物分子生成 |
| 9 | http://arxiv.org/abs/2509.01257v2 | Multi-Agent Reinforcement Learning for Task Offloading in Wireless Edge Networks | 去中心化CMDP框架，通过稀疏更新的全局约束向量实现隐式协调 | 现有MARL依赖中心化critic或频繁通信，难以适应资源受限边缘场景 | 无线边缘网络中的分布式任务卸载决策 |
| 10 | http://arxiv.org/abs/2509.01856v4 | Hierarchical Multi-Agent MCTS for Safety-Critical Coordination in Mixed-Autonomy Roundabouts | 分层安全评估+车道特异性不确定性模型+安全感知MCTS剪枝+Shapley价值分配 | 混合交通环岛中CAV与HDV交互复杂，需保证安全同时高效协调 | 自动驾驶车辆在无信号环岛中的安全导航决策 |
| 11 | http://arxiv.org/abs/2509.02547v4 | The Landscape of Agentic Reinforcement Learning for LLMs: A Survey | 形式化单步MDP与扩展POMDP的范式对比，双维度分类+开源资源汇编+500+文献综述 | 缺乏对Agentic RL概念演进、能力体系与研究景观的系统性梳理 | 推动可扩展通用AI agent的强化学习研究 |
| 12 | http://arxiv.org/abs/2509.06493v2 | Scaling up Multi-Turn Off-Policy RL and Multi-Agent Tree Search for LLM Step-Provers | 多阶段专家迭代 pipeline 与规划增强多代理搜索架构 | 解决定理证明中训练 RL 与推理计算扩展的双重挑战 | 形式化数学证明代理 |
| 13 | http://arxiv.org/abs/2509.07650v3 | Inference of Altruism and Intrinsic Rewards in Multi-Agent Systems | 多代理逆强化学习框架，可靠识别内在奖励与利他倾向 | 解决自主代理与人类协作时偏好未知导致误解问题 | 多智能体系统与人类协作 |
| 14 | http://arxiv.org/abs/2509.10163v1 | Federated Multi-Agent Reinforcement Learning for Privacy-Preserving and Energy-Aware Resource Management in 6G Edge Networks | 联邦多智能体强化学习框架，跨层协调 MAC 与应用层 | 解决 6G 边缘网络资源管理中的隐私与能耗约束问题 | 6G 边缘网络资源管理 |
| 15 | http://arxiv.org/abs/2509.10656v1 | Self-Supervised Goal-Reaching Results in Multi-Agent Cooperation and Exploration | 自监督目标达成技术，最大化访问目标 likelihood | 解决稀疏奖励下多智能体协作与探索难设计问题 | 多智能体强化学习基准 |
| 16 | http://arxiv.org/abs/2509.11508v2 | SafeDiver: Cooperative AUV-USV Assisted Diver Communication via Multi-agent Reinforcement Learning Approach | MARL 控制 AUV-USV 协作，辅助潜水员高速通信 | 解决水下复杂环境中潜水员通信服务挑战 | 水下通信与无人系统 |
| 17 | http://arxiv.org/abs/2509.12117v1 | $K$-Level Policy Gradients for Multi-Agent Reinforcement Learning | 引入 K 级策略梯度，递归更新代理以应对其他代理策略变化 | 解决多代理强化学习中因忽略同步更新导致的协调失败问题 | 多代理强化学习环境 |
| 18 | http://arxiv.org/abs/2509.12307v1 | FLARE: Flying Learning Agents for Resource Efficiency in Next-Gen UAV Networks | 采用混合强化学习策略联合优化 UAV 位置与资源分配 | 解决 6G 网络中 UAV 在动态环境下资源分配效率低问题 | 无人机网络资源管理 |
| 19 | http://arxiv.org/abs/2509.14276v2 | Constructive Conflict-Driven Multi-Agent Reinforcement Learning for Strategic Diversity | 引入竞争性内在奖励机制，鼓励合作场景中的策略多样性 | 解决现有 MARL 方法忽视代理间相互作用导致策略单一问题 | 多代理战略决策 |
| 20 | http://arxiv.org/abs/2509.14159v2 | MIMIC-D: Multi-modal Imitation for MultI-agent Coordination with Decentralized Diffusion Policies | 提出集中训练分散执行的扩散策略多模态多智能体模仿学习。 | 解决多模态专家演示下多智能体协调策略学习困难的问题。 | 机器人多智能体协调 |
| 21 | http://arxiv.org/abs/2509.14680v1 | LEED: A Highly Efficient and Scalable LLM-Empowered Expert Demonstrations Framework for Multi-Agent Reinforcement Learning | 利用 LLM 生成指令演示，结合分散训练优化局部策略。 | 解决多智能体强化学习随 agent 数量增加的协调扩展瓶颈。 | 多智能体强化学习系统 |
| 22 | http://arxiv.org/abs/2509.15042v1 | Reinforcement Learning Agent for a 2D Shooter Game | 结合离线模仿学习与在线强化学习的混合训练方法。 | 解决复杂游戏环境中强化学习奖励稀疏及训练不稳定问题。 | 2D 射击游戏 AI 智能体 |
| 23 | http://arxiv.org/abs/2509.15099v1 | Digital Twin-based Cooperative Autonomous Driving in Smart Intersections: A Multi-Agent Reinforcement Learning Approach | 结合离线预训练与在线微调的混合 RL 框架协调自动驾驶。 | 解决无信号路口交通流复杂及盲点导致的安全效率挑战。 | 智能路口协同自动驾驶 |
| 24 | http://arxiv.org/abs/2509.15103v2 | Vulnerable Agent Identification in Large-Scale Multi-Agent Reinforcement Learning | 将脆弱智能体识别 framed 为分层对抗分散均值场控制问题。 | 解决大规模 MARL 系统中部分智能体失效导致性能下降问题。 | 大规模多智能体强化学习 |
| 25 | http://arxiv.org/abs/2509.15519v1 | Fully Decentralized Cooperative Multi-Agent Reinforcement Learning is A Context Modeling Problem | 提出动态感知上下文方法，建模局部任务动态为非平稳上下文。 | 解决完全分散协作 MARL 中非平稳性及相对过度泛化问题。 | 完全分散协作多智能体强化学习 |
| 26 | http://arxiv.org/abs/2509.15737v1 | SMART: Scalable Multi-Agent Reasoning and Trajectory Planning in Dense Environments | 结合优先级搜索与分布式优化，分层解决多车轨迹规划非凸问题。 | 解决密集环境下多车轨迹规划碰撞约束增长快、计算难的问题。 | 自动驾驶/多车协同 |
| 27 | http://arxiv.org/abs/2509.15799v2 | Hierarchical Reinforcement Learning with Low-Level MPC for Multi-Agent Control | 结合高层强化学习决策与低层模型预测控制，确保动态可行性与安全。 | 解决纯端到端学习样本效率低且模型基于方法泛化差的问题。 | 多智能体控制/动态环境 |
| 28 | http://arxiv.org/abs/2509.16095v1 | AdaSports-Traj: Role- and Domain-Aware Adaptation for Multi-Agent Trajectory Modeling in Sports | 引入角色与领域感知适配器，分层对比学习解耦潜在表示结构。 | 解决体育场景中代理角色异构及跨领域分布差异导致的泛化差问题。 | 体育轨迹预测/多代理建模 |
| 29 | http://arxiv.org/abs/2509.16151v1 | Automated Cyber Defense with Generalizable Graph-based Reinforcement Learning Agents | 将网络表示为属性图，利用关系归纳偏置学习通用防御策略。 | 解决传统 RL 防御模型过拟合特定网络拓扑、泛化能力弱的问题。 | 网络安全/自动化防御 |
| 30 | http://arxiv.org/abs/2509.16606v4 | Bayesian Ego-graph Inference for Networked Multi-Agent Reinforcement Learning | 提出 BayesG 框架，通过贝叶斯变分推断学习稀疏上下文感知交互结构。 | 解决网络化 MARL 中静态邻居假设限制动态异构环境适应性的问题。 | 交通控制/网络化 MARL |
| 31 | http://arxiv.org/abs/2509.16709v1 | HypeMARL: Multi-Agent Reinforcement Learning For High-Dimensional, Parametric, and Distributed Systems | 利用超网络参数化策略，结合模型扩展减少环境交互次数。 | 解决高维分布式系统控制中局部性原则限制集体非局部行为优化的问题。 | 分布式系统控制/PDE 约束 |
| 32 | http://arxiv.org/abs/2509.17042v1 | Orchestrate, Generate, Reflect: A VLM-Based Multi-Agent Collaboration Framework for Automated Driving Policy Learning | 利用 VLM 多代理协作自动生成奖励 - 课程对，实现在线策略进化。 | 解决复杂驾驶任务中手动工程奖励函数与训练课程耗时费力的问题。 | 自动驾驶策略学习/强化学习 |
| 33 | http://arxiv.org/abs/2509.17244v1 | Scalable Multi Agent Diffusion Policies for Coverage Control | 利用扩散模型生成捕捉代理间动作依赖的高维动作分布样本。 | 解决去中心化机器人集群覆盖控制中复杂动作分布建模困难的问题。 | 机器人集群/覆盖控制 |
| 34 | http://arxiv.org/abs/2509.17676v1 | GLo-MAPPO: A Multi-Agent Proximal Policy Optimization for Energy Efficiency in UAV-Assisted LoRa Networks | 提出 GLo-MAPPO 框架优化 UAV 轨迹与能耗 | 解决大规模动态环境下 LoRa 网络能效优化难题 | UAV 辅助物联网网络 |
| 35 | http://arxiv.org/abs/2509.17917v1 | Orcust: Stepwise-Feedback Reinforcement Learning for GUI Agent | 集成原则约束奖励建模与在线轨迹构建增强推理 | 解决 GUI 智能体奖励信号不可靠与轨迹生成有限问题 | 图形界面自动化任务 |
| 36 | http://arxiv.org/abs/2509.18088v1 | Strategic Coordination for Evolving Multi-agent Systems: A Hierarchical Reinforcement and Collective Learning Approach | 分层强化与集体学习结合平衡长期决策与短期优化 | 解决去中心化组合优化中状态空间爆炸与通信开销问题 | 智慧城市与无人机群 |
| 37 | http://arxiv.org/abs/2509.18371v1 | Policy Gradient with Self-Attention for Model-Free Distributed Nonlinear Multi-Agent Games | 自注意力层参数化非线性反馈增益学习分布式策略 | 解决动态非线性设置下多智能体博弈策略学习问题 | 多机器人追捕与逃避 |
| 38 | http://arxiv.org/abs/2509.18526v1 | AI Agent Access (A^3) Network: An Embodied, Communication-Aware Multi-Agent Framework for 6G Coverage | 统一框架集成探索、接入与回haul 维护于单学习过程 | 解决 6G 无基础设施环境下多智能体网络适应性问题 | 6G 通信网络覆盖 |
| 39 | http://arxiv.org/abs/2509.18891v1 | Attack for Defense: Adversarial Agents for Point Prompt Optimization Empowering Segment Anything Model | 对抗强化学习框架自动优化点提示提升分割性能 | 解决 SAM 模型依赖启发式或手动 crafted 提示问题 | 图像分割提示优化 |
| 40 | http://arxiv.org/abs/2509.19199v3 | Agentic Reinforcement Learning with Implicit Step Rewards | 隐式步骤奖励策略无缝集成标准 RL 算法 | 解决稀疏不可验证奖励下智能体信用分配难题 | 开放域社交交互与任务 |
| 41 | http://arxiv.org/abs/2509.19512v1 | The Heterogeneous Multi-Agent Challenge | 提出异构多智能体强化学习挑战与标准化测试床需求 | 解决缺乏 cooperative HeMARL 标准化基准问题 | 异构多智能体强化学习 |
| 42 | http://arxiv.org/abs/2509.20408v1 | A Theory of Multi-Agent Generative Flow Networks | 提出多智能体生成流网络理论框架与四种算法 | 解决多智能体协作生成对象缺乏理论框架问题 | 多智能体生成模型 |
| 43 | http://arxiv.org/abs/2509.19791v1 | Agentic AI for Low-Altitude Semantic Wireless Networks: An Energy Efficient Design | 智能体 AI 框架编排感知 - 通信 - 决策 - 控制工作流 | 解决 UAV 辅助自主系统能耗效率问题 | 低空语义无线网络 |
| 44 | http://arxiv.org/abs/2509.21612v2 | Incentives in Federated Learning with Heterogeneous Agents | 博弈论框架刻画异构数据Agent激励对齐问题 | 联邦学习中Agent贡献成本与收益不匹配 | 联邦学习、分布式机器学习 |
| 45 | http://arxiv.org/abs/2510.01264v1 | A Framework for Scalable Heterogeneous Multi-Agent Adversarial Reinforcement Learning in IsaacLab | 扩展IsaacLab支持异构Agent对抗MARL训练 | 现有MARL聚焦协作，对抗交互对现实应用同样关键 | 机器人竞争、安全、追捕-逃避 |
| 46 | http://arxiv.org/abs/2509.21828v1 | Preference-Guided Learning for Sparse-Reward Multi-Agent Reinforcement Learning | 在线逆偏好学习+多Agent on-policy优化统一架构 | 稀疏奖励环境下缺乏中间奖励引导策略学习 | 在线MARL、稀疏奖励场景 |
| 47 | http://arxiv.org/abs/2509.22130v1 | Multi-Agent Path Finding via Offline RL and LLM Collaboration | Decision Transformer基于离线RL，GPT-4o动态引导Agent策略 | 去中心化RL产生自我中心行为导致碰撞，训练时间长 | 机器人物流、多Agent路径规划 |
| 48 | http://arxiv.org/abs/2509.22216v1 | Impact of Collective Behaviors of Autonomous Vehicles on Urban Traffic Dynamics: A Multi-Agent Reinforcement Learning Approach | 定义六种AV行为（自私/协作/竞争/社会/利他/恶意）通过奖励施加 | 研究RL赋能AV对混合交通流影响，行为对学习任务复杂度差异 | 城市交通动力学、自动驾驶车辆 |
| 49 | http://arxiv.org/abs/2510.00022v1 | Learning to Lead Themselves: Agentic AI in MAS using MARL | 实现轻量级多代理 PPO 算法，在集中训练分散执行范式下提升无人机群自组织协调能力。 | 解决多无人机系统在无显式通信下的 decentralized 协作决策问题。 | 无人机配送与仓储自动化 |
| 50 | http://arxiv.org/abs/2509.20338v1 | Adaptive Event-Triggered Policy Gradient for Multi-Agent Reinforcement Learning | 联合学习控制策略与事件触发策略，优化智能体执行时机与通信对象。 | 解决传统时间触发 MARL 计算成本高、通信开销大的问题。 | 多智能体强化学习基准 |
| 51 | http://arxiv.org/abs/2509.20648v3 | Wonder Wins Ways: Curiosity-Driven Exploration through Multi-Agent Contextual Calibration | 提出 CERMIC 框架，动态校准内在好奇心，过滤噪声惊喜信号引导探索。 | 解决稀疏奖励 MARL 中人工好奇心混淆环境随机性与有意义新奇性的问题。 | 多智能体探索任务 |
| 52 | http://arxiv.org/abs/2509.21134v1 | ToMPO: Training LLM Strategic Decision Making from a Multi-Agent Perspective | 提出 ToMPO 算法，基于推理他人策略生成 rollout，平衡全局与部分奖励。 | 解决现有 RL 方法训练时难以考虑他人策略及决策类型依赖的问题。 | LLM 战略决策 |
| 53 | http://arxiv.org/abs/2509.22596v1 | Effective Policy Learning for Multi-Agent Online Coordination Beyond Submodular Objectives | 提出无参数在线算法，实现弱次模目标下的最优近似。 | 解决多智能体在线协调中依赖未知参数的问题。 | 多智能体协作系统 |
| 54 | http://arxiv.org/abs/2509.23026v1 | Game-Theoretic Understandings of Multi-Agent Systems with Multiple Objectives | 引入多目标马尔科夫博弈，定义帕累托纳什均衡。 | 解决多智能体系统中多目标冲突与策略权衡问题。 | 多目标多智能体系统 |
| 55 | http://arxiv.org/abs/2509.23462v2 | Generative Evolutionary Meta-Solver (GEMS): Scalable Surrogate-Free Multi-Agent Reinforcement Learning | 提出无代理元求解器，替代显式种群降低计算内存成本。 | 解决大规模多智能体强化学习中种群存储与计算瓶颈。 | 多智能体博弈学习 |
| 56 | http://arxiv.org/abs/2509.23747v1 | Beyond Game Theory Optimal: Profit-Maximizing Poker Agents for No-Limit Holdem | 结合 GTO 基线与实时剥削策略，最大化扑克利润。 | 解决纯 GTO 策略无法在多变对手下实现利润最大化问题。 | 扑克博弈智能体 |
| 57 | http://arxiv.org/abs/2509.23778v2 | Sequence Pathfinder for Multi-Agent Pickup and Delivery in the Warehouse | 将路径查找建模为序列问题，利用 Transformer 隐式交换信息。 | 解决仓库环境中多智能体取货交付的分布式决策难题。 | 仓库物流机器人 |
| 58 | http://arxiv.org/abs/2509.23866v1 | Efficient Multi-turn RL for GUI Agents via Decoupled Training and Adaptive Data Curation | 提出 DART 框架，解耦训练模块并自适应数据策展，提升 GUI 智能体 RL 效率 | 解决 GUI 智能体 RL 训练中交互慢及高质量数据不足的问题 | 桌面/移动端 GUI 自动化 |
| 59 | http://arxiv.org/abs/2509.23870v4 | Gradient Coupling: The Hidden Barrier to Generalization in Agentic Reinforcement Learning | 发现梯度耦合现象，提出分类器辅助目标以减轻梯度干扰，提升泛化性 | 解决智能体强化学习在复杂任务中泛化能力差的问题 | 通用强化学习智能体 |
| 60 | http://arxiv.org/abs/2509.23905v1 | Integrated Communication and Control for Energy-Efficient UAV Swarms: A Multi-Agent Reinforcement Learning Approach | 提出 MAHPPO-AM 算法，集成通信与控制，优化无人机群能量效率 | 解决复杂地理环境下无人机群通信链路中断及能耗问题 | 无人机群通信网络 |
| 61 | http://arxiv.org/abs/2509.24047v2 | Optimism as Risk-Seeking in Multi-Agent Reinforcement Learning | 提出乐观值函数框架，将风险寻求目标解释为乐观，促进合作 | 解决合作 MARL 中风险厌恶导致次优均衡的问题 | 合作多智能体系统 |
| 62 | http://arxiv.org/abs/2509.24226v4 | Multi-Agent Guided Policy Search for Non-Cooperative Dynamic Games | 提出 MA-GPS，利用局部 LQ 近似引导非合作动态游戏策略搜索 | 解决多智能体策略梯度在不合作游戏中不稳定及极限环问题 | 非合作动态游戏 |
| 63 | http://arxiv.org/abs/2509.24527v1 | Training Agents Inside of Scalable World Models | 提出 Dreamer 4，在快速准确世界模型内通过 RL 训练智能体 | 解决世界模型无法准确预测复杂环境物体交互的问题 | 复杂控制任务/Minecraft |
| 64 | http://arxiv.org/abs/2509.25034v4 | MARLIN: Multi-Agent Reinforcement Learning with Murmuration Intelligence and LLM Guidance for Reservoir Management | 结合鸟群智能与 MARL 的去中心化水库管理框架 | 处理互联水库网络中的级联不确定性 | 水资源管理与防洪 |
| 65 | http://arxiv.org/abs/2509.25550v4 | Unifying Agent Interaction and World Information for Multi-agent Coordination | 联合捕捉智能体间关系与世界信息的表示学习框架 | 多智能体交互动态复杂及局部观察信息不全 | 团队协调与 MARL |
| 66 | http://arxiv.org/abs/2510.00274v1 | MAGIC-MASK: Multi-Agent Guided Inter-Agent Collaboration with Mask-Based Explainability for Reinforcement Learning | 扩展基于扰动的解释到多智能体强化学习 | 多智能体环境下深度强化学习决策过程难理解 | 多智能体强化学习 |

[返回目录](#目录)

<a id="cat-04"></a>

## Agent架构与框架设计

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2509.08863v3 | GeoJSON Agents:A Multi-Agent LLM Architecture for Geospatial Analysis-Function Calling vs Code Generation | 三核心组件架构：任务解析、Agent协作、结果集成，比较函数调用与代码生成 | LLM处理复杂地理空间任务时准确性低、性能不稳定 | 地理信息科学领域的空间分析 |
| 2 | http://arxiv.org/abs/2509.08312v2 | Leveraging AI Agents for Autonomous Networks: A Reference Architecture and Empirical Studies | 实现Sifakis的AN Agent参考架构，部署协调的主动-反应式运行时 | 传统自动化无法实现L4自主网络的认知能力 | 5G无线接入网络的链路自适应 |
| 3 | http://arxiv.org/abs/2509.08646v1 | Architecting Resilient LLM Agents: A Guide to Secure Plan-then-Execute Implementations | 提供P-t-E模式的全面指南，分离战略规划与战术执行，增强控制流完整性 | LLM Agent自动化复杂多步任务时需要稳健、安全、可预测的架构模式 | 生产级LLM Agent系统架构设计 |
| 4 | http://arxiv.org/abs/2509.09215v1 | Enabling Regulatory Multi-Agent Collaboration: Architecture, Challenges, and Solutions | 区块链赋能的分层架构，含Agent行为追踪仲裁、动态声誉评估、恶意行为预测模块 | LLM赋能Agent的不可预测行为和异构能力带来治理和问责挑战 | 大规模Agent生态系统的监管协作 |
| 5 | http://arxiv.org/abs/2509.09292v1 | LightAgent: Production-level Open-source Agentic AI Framework | 轻量级框架集成Memory、Tools、Tree of Thought，保持极简结构 | 现有框架在灵活性和简单性之间存在权衡，缺乏多功能稳健高效平台 | 生产级多Agent系统部署 |
| 6 | http://arxiv.org/abs/2509.09505v2 | Combating the Memory Walls: Optimization Pathways for Long-Context Agentic LLM Inference | PLENA软硬件协同设计系统，非对称量化、扁平化脉动阵列、原生FlashAttention支持 | Agent LLM推理任务上下文长度大，受带宽和容量内存墙限制 | 长上下文LLM Agent推理的硬件优化 |
| 7 | http://arxiv.org/abs/2509.09915v1 | The (R)evolution of Scientific Workflows in the Agentic AI Era: Towards Autonomous Science | 概念框架沿智能和组成两维度演化，提出架构蓝图实现100x发现加速 | 现代科学发现需要协调分布式设施，研究人员沦为手动工作流协调员 | 自主科学实验室的工作流演化 |
| 8 | http://arxiv.org/abs/2509.02973v2 | InstaDA: Augmenting Instance Segmentation Data with Dual-Agent System | 提出文本与图像双智能体协作框架，迭代优化提示词 | 解决实例分割数据标注成本高及类别不平衡问题 | 计算机视觉数据增强 |
| 9 | http://arxiv.org/abs/2509.03310v2 | app.build: A Production Framework for Scaling Agentic Prompt-to-App Generation with Environment Scaffolding | 构建多层验证管道与环境支架框架以规模化生成应用 | 解决 LLM 生成应用可靠性低及环境依赖问题 | 自动化应用开发平台 |
| 10 | http://arxiv.org/abs/2509.04343v1 | Psychologically Enhanced AI Agents | 基于 MBTI 框架通过提示工程增强 LLM 代理人格条件 | 实现无需微调即可控制代理行为认知与情感轴 | 人格化 AI 代理设计 |
| 11 | http://arxiv.org/abs/2509.04642v1 | Maestro: Joint Graph & Config Optimization for Reliable AI Agents | 联合搜索图结构与节点配置以最大化代理质量 | 解决现有优化器仅调配置忽略结构失败模式问题 | 可靠 LLM 代理构建 |
| 12 | http://arxiv.org/abs/2509.04979v1 | Internet 3.0: Architecture for a Web-of-Agents with it's Algorithm for Ranking Agents | 提出 DOVIS 协议与 AgentRank-UC 算法实现代理排名 | 解决缺乏全局交互网络导致代理排名不可行问题 | 代理互联网生态系统 |
| 13 | http://arxiv.org/abs/2509.01245v4 | Towards Agentic OS: An LLM Agent Framework for Linux Schedulers | 解耦控制平面分离语义推理与系统执行，MCP服务接口+执行验证器保障安全 | OS调度器语义缺口导致应用感知优化困难，AI生成代码部署风险 | Linux调度器的自主优化与系统性能调优 |
| 14 | http://arxiv.org/abs/2509.01312v1 | TableZoomer: A Collaborative Agent Framework for Large-scale Table Question Answering | 结构化schema替代全表格、查询感知缩放机制、PoT策略+ReAct迭代推理 | 工业表格问答面临结构异构、目标定位难、复杂推理瓶颈 | 大规模异构表格的自动化问答与分析 |
| 15 | http://arxiv.org/abs/2509.01551v1 | Cloud-Device Collaborative Agents for Sequential Recommendation | 云 - 端双agent分工，策略规划机制实现上下文感知任务分配与部分并行执行 | 云端agent隐私/实时性不足，端侧agent算力/全局建模能力有限 | 资源受限设备上的个性化序列推荐 |
| 16 | http://arxiv.org/abs/2509.02121v2 | Batch Query Processing and Optimization for Agentic Workflows | 工作流表示为查询计划DAG，成本模型指导的批处理优化+KV缓存共享+CPU-GPU流水线 | 现有系统孤立优化单调用，批处理场景下重复计算导致硬件利用率低 | 大规模agentic LLM工作流的批处理与在线服务效率优化 |
| 17 | http://arxiv.org/abs/2509.02124v1 | FlexNGIA 2.0: Redesigning the Internet with Agentic AI -- Protocols, Services, and Traffic Engineering Designed, Deployed, and Managed by AI | LLM agent自主感知 - 推理 - 协调，动态设计部署网络协议、服务链、资源策略 | 传统网络架构难以适应沉浸式通信等新兴需求的动态变化 | 未来互联网的自主编排、配置与演化 |
| 18 | http://arxiv.org/abs/2509.02449v1 | KubeIntellect: A Modular LLM-Orchestrated Agent Framework for End-to-End Kubernetes Management | 模块化领域agent+监督者编排，内存检查点+人机澄清+动态任务序列+安全代码生成 | K8s管理API复杂、工具碎片化，需自然语言接口实现端到端智能控制 | 云原生基础设施的自动化运维与配置管理 |
| 19 | http://arxiv.org/abs/2509.02515v1 | Contemporary Agent Technology: LLM-Driven Advancements vs Classic Multi-Agent Systems | 系统对比LLM驱动agent与经典MAS的模型、方法、特征，识别挑战与未来方向 | 缺乏对新兴agent技术与传统MAS理论关联的批判性梳理 | agent领域研究者理解技术演进脉络与前沿趋势 |
| 20 | http://arxiv.org/abs/2509.05584v1 | ProfilingAgent: Profiling-Guided Agentic Reasoning for Adaptive Model Optimization | 利用 LLM 代理自动化模型压缩，基于性能分析动态剪枝量化 | 解决基础模型在资源受限平台部署的瓶颈 | 模型优化与边缘设备部署 |
| 21 | http://arxiv.org/abs/2509.05721v2 | A Composable Agentic System for Automated Visual Data Reporting | 混合多智能体架构，外部化逻辑至确定性模块，实现可审计报告 | 解决单体 AI 代理脆弱性及不可追溯问题 | 自动化视觉数据报告生成 |
| 22 | http://arxiv.org/abs/2509.06431v1 | HECATE: An ECS-based Framework for Teaching and Developing Multi-Agent Systems | 基于 ECS 架构模式，从分布式系统视角工程化多智能体系统 | 解决多智能体开发需专用知识且与分布式系统脱节问题 | 多智能体系统教学与开发 |
| 23 | http://arxiv.org/abs/2509.06917v2 | Paper2Agent: Reimagining Research Papers As Interactive and Reliable AI Agents | 自动将研究论文转化为交互式 AI 代理，构建 MCP 服务器 | 解决研究论文代码数据复用壁垒高且被动的问题 | 科学研究与知识传播 |
| 24 | http://arxiv.org/abs/2509.07571v2 | Towards Generalized Routing: Model and Agent Orchestration for Adaptive and Efficient Inference | 集成 LLM 与代理路由的通用框架，动态路由至最优成本性能 | 解决用户查询多样导致路由复杂且效率低的问题 | 大模型服务与推理路由 |
| 25 | http://arxiv.org/abs/2509.07595v1 | AgentX: Towards Orchestrating Robust Agentic Workflow Patterns with FaaS-hosted MCP Services | 定义新型代理工作流模式，利用 FaaS 部署 MCP 服务 | 解决代理系统面对多工具复杂任务时历史追踪困难问题 | 代理工作流编排与部署 |
| 26 | http://arxiv.org/abs/2509.08088v1 | EnvX: Agentize Everything with Agentic AI | 框架将 GitHub 仓库转化为智能代理，支持代理间协作 | 解决开源组件利用手动且 disconnected 的问题 | 软件开发与开源生态 |
| 27 | http://arxiv.org/abs/2509.10054v1 | XAgents: A Unified Framework for Multi-Agent Cooperation via IF-THEN Rules and Multipolar Task Processing Graph | 基于多极任务处理图与 IF-THEN 规则的统一协作框架 | 解决复杂不确定任务下的规划误导与执行错误问题 | 通用复杂任务处理 |
| 28 | http://arxiv.org/abs/2509.10875v1 | Is the`Agent'Paradigm a Limiting Framework for Next-Generation Intelligent Systems? | 批判性重估 Agent 范式，提议转向系统动力学框架 | 解决 Agent 概念模糊及人类中心主义偏见限制 | 下一代智能系统理论 |
| 29 | http://arxiv.org/abs/2509.11067v2 | Agentic Lybic: Multi-Agent Execution System with Tiered Reasoning and Orchestration | 基于 FSM 的路由机制，动态选择最优执行策略 | 解决桌面自动化中复杂多步任务协调与质量控制问题 | 通用桌面自动化 |
| 30 | http://arxiv.org/abs/2509.11079v5 | Difficulty-Aware Agentic Orchestration for Query-Specific Multi-Agent Workflows | 难度感知代理编排，动态生成查询特定工作流 | 解决静态工作流过处理简单查询或低估复杂查询问题 | 异构 LLM 多 agent 系统 |
| 31 | http://arxiv.org/abs/2509.11575v2 | A Survey of Reasoning and Agentic Systems in Time Series with Large Language Models | 综述时间序列推理与代理系统，定义推理拓扑 | 梳理时间序列领域代理系统进展与评估实践 | 时间序列分析与代理系统 |
| 32 | http://arxiv.org/abs/2509.11656v3 | MALLM: Multi-Agent Large Language Models Framework | 开源框架支持 144+ 种多 agent 辩论配置与评估 | 解决现有辩论框架配置有限及缺乏集成评估问题 | 多 agent 辩论研究 |
| 33 | http://arxiv.org/abs/2509.11943v3 | Agentic System with Modal Logic for Autonomous Diagnostics | 引入神经符号多代理架构，用模态逻辑形式化信念状态 | 解决代理在复杂环境中推理缺乏逻辑一致性与可解释性问题 | 自主诊断系统 |
| 34 | http://arxiv.org/abs/2509.13368v2 | $Agent^2$: An Agent-Generates-Agent Framework for Reinforcement Learning Automation | 双代理架构自动生成 RL 解决方案，分解 MDP 建模与算法优化 | 解决 RL 代理开发需大量专家知识且迭代努力导致高失败率问题 | 强化学习代理自动化设计 |
| 35 | http://arxiv.org/abs/2509.18167v1 | SIRAG: Towards Stable and Interpretable RAG with A Process-Supervised Multi-Agent Framework | 引入决策者与知识选择器智能体，过程监督优化 RAG 检索生成。 | 解决 RAG 中检索器与生成器协调不佳及证据利用不充分问题。 | 检索增强生成系统 |
| 36 | http://arxiv.org/abs/2509.13978v2 | LLM Agents for Interactive Workflow Provenance: Reference Architecture and Evaluation Methodology | 提出基于 LLM 智能体的工作流谱系交互式分析参考架构。 | 解决大规模工作流谱系数据复杂难分析及交互性差的问题。 | 科学计算工作流管理 |
| 37 | http://arxiv.org/abs/2509.15532v1 | GUI-ARP: Enhancing Grounding with Adaptive Region Perception for GUI Agents | 提出自适应区域感知框架，动态裁剪任务区域，结合强化学习微调策略。 | 解决高分辨率截图下 GUI 智能体细粒度定位困难的问题。 | GUI 智能体/高分辨率屏幕 |
| 38 | http://arxiv.org/abs/2509.15566v4 | BTL-UI: Blink-Think-Link Reasoning Model for GUI Agent | 模仿人类认知过程，构建眨眼 - 思考 - 链接三阶段脑启发式交互框架。 | 解决现有 AI 交互逻辑偏离自然人机沟通模式的问题。 | GUI 智能体/人机交互 |
| 39 | http://arxiv.org/abs/2509.19369v1 | SLM-Based Agentic AI with P-C-G: Optimized for Korean Tool Use | 提出规划 - 调用 - 生成角色分离架构，应用韩语优先值策略减少代码切换。 | 解决韩语环境下小模型智能体工具使用执行失败率高的问题。 | 韩语工具使用/小模型智能体 |
| 40 | http://arxiv.org/abs/2509.16666v1 | Robust Native Language Identification through Agentic Decomposition | 引入法医语言学灵感代理管道，积累分类证据后由协调代理综合评估。 | 解决 LLM 依赖表面线索而非底层语言模式导致原生语言识别不鲁棒的问题。 | 原生语言识别/文本分析 |
| 41 | http://arxiv.org/abs/2509.16676v1 | Governed By Agents: A Survey On The Role Of Agentic AI In Future Computing Environments | 调查代理 AI 对计算基础设施架构、治理与运营的影响及迁移趋势。 | 解决自主代理兴起带来的计算环境架构重组与治理模型变革挑战。 | 计算基础设施/代理治理 |
| 42 | http://arxiv.org/abs/2509.17197v2 | SignalLLM: A General-Purpose LLM Agent Framework for Automated Signal Processing | 提出模块化架构，分解高级目标并通过自适应 RAG 与代码合成执行。 | 解决信号处理工作流复杂碎片化且依赖专家知识难以泛化的问题。 | 信号处理/自动化工作流 |
| 43 | http://arxiv.org/abs/2509.17328v1 | UIPro: Unleashing Superior Interaction Capability For GUI Agents | 训练通用 GUI 代理，统一异构动作空间并利用大规模数据预训练。 | 解决现有 GUI 代理场景有限、数据不足及动作空间异构阻碍通用化的问题。 | GUI 智能体/跨平台交互 |
| 44 | http://arxiv.org/abs/2509.17489v2 | MapCoder-Lite: Distilling Multi-Agent Coding into a Single Small LLM | 三支柱方法将多智能体编码推理蒸馏至 7B 模型 | 解决小模型无法承担复杂多智能体编码任务问题 | 代码生成与小模型部署 |
| 45 | http://arxiv.org/abs/2509.17757v1 | Multi-Agent Amodal Completion: Direct Synthesis with Fine-Grained Semantic Guidance | 多智能体协作分析遮挡关系并生成细粒度语义指导 | 解决遮挡物体补全中的数据需求与误差积累问题 | 图像编辑与增强现实 |
| 46 | http://arxiv.org/abs/2509.17788v1 | One Agent to Serve All: a Lite-Adaptive Stylized AI Assistant for Millions of Multi-Style Official Accounts | WeStar 框架结合 RAG 与动态 LoRA 实现风格自适应 | 解决大规模多风格官方账号响应延迟与微调成本高问题 | 工业级客服与官方账号 |
| 47 | http://arxiv.org/abs/2509.18787v1 | The AGNTCY Agent Directory Service: Architecture and Implementation | 分布式目录服务实现 AI 智能体能力发现与验证 | 解决异构多智能体系统中能力发现与互操作性问题 | 多智能体系统基础设施 |
| 48 | http://arxiv.org/abs/2509.18813v2 | MAPEX: A Multi-Agent Pipeline for Keyphrase Extraction | 多智能体协作管道动态适应文档长度提取关键词 | 解决单阶段提示方法无法充分利用 LLM 推理能力问题 | 自然语言处理关键词提取 |
| 49 | http://arxiv.org/abs/2510.05107v4 | Structured Cognitive Loop for Behavioral Intelligence in Large Language Model Agents | 结构化认知循环分离认知、记忆与控制功能 | 解决单提示混合功能导致连贯性与可预测性降低问题 | 多步骤任务 LLM 智能体 |
| 50 | http://arxiv.org/abs/2509.19783v1 | Agentic Metacognition: Designing a ""Self-Aware"" Low-Code Agent for Failure Prediction and Human Handoff | 集成元认知层监控主 Agent 预测失败并主动移交人类 | 解决低代码环境 Agent 非确定性导致可靠性挑战 | 低代码/无代码 Agent |
| 51 | http://arxiv.org/abs/2509.21799v3 | D-Artemis: A Deliberative Cognitive Framework for Mobile GUI Multi-Agents | 思考-对齐-反思认知循环，预执行对齐+后执行状态反思 | GUI Agent数据瓶颈、错误检测延迟、指导矛盾风险 | 移动GUI自动化、MLLM增强 |
| 52 | http://arxiv.org/abs/2509.21834v2 | RobustFlow: Towards Robust Agentic Workflow Generation | 偏好优化训练模型对指令变化不变性，提升工作流鲁棒性 | 当前方法生成工作流对语义相同但措辞不同指令极度不稳定 | Agent工作流自动生成、可靠性 |
| 53 | http://arxiv.org/abs/2509.20175v1 | Federation of Agents: A Semantics-Aware Communication Fabric for Large-Scale Agentic AI | 引入版本化能力向量，实现基于语义嵌入的动态任务分解与智能集群协作编排。 | 解决大规模异构智能体间静态协调效率低、能力匹配难的问题。 | 大规模分布式智能体系统 |
| 54 | http://arxiv.org/abs/2509.20729v2 | Robust, Observable, and Evolvable Agentic Systems Engineering: A Principled Framework Validated via the Fairy GUI Agent | 提出包含运行时目标细化、可观察认知架构及进化记忆架构的工程框架。 | 解决代理系统缺乏鲁棒性、可观察性及可进化性的软件工程缺失问题。 | 移动 GUI 代理系统 |
| 55 | http://arxiv.org/abs/2509.20971v2 | i-LAVA: Insights on Low Latency Voice-2-Voice Architecture for Agents | 分析 V-2-V 系统组件，优化 TTS 解码器 RVQ 迭代以降低延迟保持高质量。 | 解决实时语音对话应用中处理时间长、难以平衡延迟与质量的问题。 | 实时语音代理架构 |
| 56 | http://arxiv.org/abs/2509.21301v1 | Nova: Real-Time Agentic Vision-Language Model Serving with Adaptive Cross-Stage Parallelization | 实现视觉编码、LLM 预填与解码阶段有效流水线，自适应校准资源分配。 | 解决单 GPU 服务代理 VLM 时每请求延迟与整体吞吐量平衡难的问题。 | 视觉语言模型服务 |
| 57 | http://arxiv.org/abs/2509.23248v2 | Agentic AI Reasoning for Mobile Edge General Intelligence: Fundamentals, Approaches, and Directions | 提出联合优化框架，动态调节推理深度与专家网络。 | 解决边缘设备上 LLM 智能体推理资源受限问题。 | 移动边缘通用智能 |
| 58 | http://arxiv.org/abs/2509.23586v2 | Reducing Cost of LLM Agents with Trajectory Reduction | 提出推理时轨迹缩减方法，自动移除冗余过期信息。 | 解决多轮智能体系统因轨迹增长导致的高计算成本。 | 软件工程 LLM 智能体 |
| 59 | http://arxiv.org/abs/2509.23988v3 | LLM/Agent-as-Data-Analyst: A Survey | 综述 LLM/Agent 在数据分析中的技术演进，提炼四大设计目标 | 梳理智能数据分析 Agent 的技术现状与挑战 | 数据分析领域 |
| 60 | http://arxiv.org/abs/2509.24116v2 | Dual-Scale World Models for LLM Agents Towards Hard-Exploration Problems | 利用双尺度世界模型，维护全局发现前沿与局部试错学习 | 解决 LLM 智能体在硬探索任务中学习新知识能力受限的问题 | 文本游戏/探索任务 |
| 61 | http://arxiv.org/abs/2509.24323v1 | MAS$^2$: Self-Generative, Self-Configuring, Self-Rectifying Multi-Agent Systems | 提出递归自生成范式，智能体系统自主架构 bespoke 多智能体系统 | 解决自动多智能体系统 rigid generate-once-and-deploy 范式脆弱性问题 | 复杂研究与代码生成 |
| 62 | http://arxiv.org/abs/2509.24380v2 | Agentic Services Computing | 提出 Agentic Services Computing 范式，重构服务为自主自适应智能体 | 解决服务计算从静态请求驱动向动态目标导向生态转型问题 | 服务计算生态系统 |
| 63 | http://arxiv.org/abs/2509.25301v1 | Flash-Searcher: Fast and Effective Web Agents via DAG-Based Parallel Execution | 基于 DAG 的并行执行推理框架 | 顺序处理导致工具交互效率低下 | 复杂推理与 Web 搜索任务 |
| 64 | http://arxiv.org/abs/2510.00078v1 | Adaptive and Resource-efficient Agentic AI Systems for Mobile and Embedded Devices: A Survey | 首次系统表征自适应资源高效智能体 AI 系统 | 基础模型复杂性与部署环境资源受限的矛盾 | 移动与嵌入式设备 |
| 65 | http://arxiv.org/abs/2509.26062v1 | DyFlow: Dynamic Workflow Framework for Agentic Reasoning | 基于任务要求和实时反馈自适应构建推理流程 | 手动设计流程限制跨任务适应性 | 复杂推理任务 |
| 66 | http://arxiv.org/abs/2510.00229v4 | AgentFlux: Decoupled Fine-Tuning & Inference for On-Device Agentic Systems | 解耦微调与推理，动态加载 LoRA 适配器 | 本地 LLM 在工具调用场景表现 consistently 不足 | 端侧智能体系统 |

[返回目录](#目录)

<a id="cat-05"></a>

## 人机协作Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2510.06224v1 | Exploring Human-AI Collaboration Using Mental Models of Early Adopters of Multi-Agent Generative AI Tools | 揭示早期采用者将多Agent系统概念化为基于角色的"团队"协作模型 | 错误传播、不可预测的Agent循环行为、分层透明度问题 | 企业级多Agent生成式AI工具采用 |
| 2 | http://arxiv.org/abs/2509.09071v4 | Strategic Tradeoffs Between Humans and AI in Multi-Agent Bargaining | 实证比较人类、前沿LLM和定制贝叶斯Agent在动态多玩家博弈中的行为 | 评估LLM Agent相对于人类和统计前辈的行为差异 | 多Agent博弈市场中的人机交互 |
| 3 | http://arxiv.org/abs/2509.09255v2 | Sensible Agent: A Framework for Unobtrusive Interaction with Proactive AR Agents | 基于实时多模态上下文感知动态适应"提供什么"和"如何交付"协助 | 主动AR Agent交互依赖显式语音提示，可能具有破坏性或社交尴尬 | 增强现实中的主动Agent交互 |
| 4 | http://arxiv.org/abs/2509.09867v1 | LLMs as Agentic Cooperative Players in Multiplayer UNO | 构建工具使decoder-only LLM在RLCard游戏环境中作为Agent参与，帮助其他玩家获胜 | 测试LLM Agent作为主动参与者帮助他人实现目标的能力限度 | 多人UNO游戏中的LLM协作玩家 |
| 5 | http://arxiv.org/abs/2509.09870v1 | Vibe Check: Understanding the Effects of LLM-Based Conversational Agents' Personality and Alignment on User Perceptions in Goal-Oriented Tasks | 特质调制键框架控制Big Five特质表达水平，发现中等表达产生最积极评价 | LLM赋能对话Agent表达独特个性如何影响用户感知 | 目标导向任务中的对话Agent设计 |
| 6 | http://arxiv.org/abs/2509.02910v1 | The Basic B*** Effect: The Use of LLM-based Agents Reduces the Distinctiveness and Diversity of People's Choices | 研究 LLM 代理如何影响人类选择的独特性与多样性 | 揭示 AI 代理外包决策对人类身份认同的潜在同质化影响 | 社交媒体用户及 AI 决策外包场景 |
| 7 | http://arxiv.org/abs/2509.04104v2 | Towards Stable and Personalised Profiles for Lexical Alignment in Spoken Human-Agent Dialogue | 构建稳定个性化词汇 profile 以实现人机词汇对齐 | 探索对话代理中词汇对齐策略及最小数据需求 | 口语人机对话系统 |
| 8 | http://arxiv.org/abs/2509.01450v1 | Analyzing Reluctance to Ask for Help When Cooperating With Robots: Insights to Integrate Artificial Agents in HRC | 量化分析用户在HRC中请求帮助的犹豫行为，对比人类vs人工agent辅助设计偏好 | 缺乏对人机协作中用户求助心理与agent设计要素的系统理解 | 工业机器人协作场景中辅助agent的交互设计 |
| 9 | http://arxiv.org/abs/2509.02144v1 | A Theoretical Framework of the Processes of Change in Psychotherapy Delivered by Artificial Agents | 提出"真实性缺口"与"可信度缺口"理论框架，分析人工agent心理治疗的变化机制 | 缺乏对人工agent提供心理治疗时起效因素的理论理解 | 人工心理治疗agent的设计优化与人机协作模式 |
| 10 | http://arxiv.org/abs/2509.07424v2 | Feed-O-Meter: Investigating AI-Generated Mentee Personas as Interactive Agents for Scaffolding Design Feedback Practice | 设计 LLM 代理扮演学员，让学生练习提供设计反馈 | 解决设计课程中学生因缺乏自信难以提供反馈的问题 | 设计教育与反馈技能培养 |
| 11 | http://arxiv.org/abs/2509.10993v3 | When Your Boss Is an AI Bot: Exploring Opportunities and Risks of Manager Clone Agents in the Future Workplace | 探索经理克隆代理角色，强调工人视角与人际纽带 | 解决 AI 嵌入职场带来的层级 disruption 与风险 | 未来职场与人机协作 |
| 12 | http://arxiv.org/abs/2509.11342v1 | What if Virtual Agents Had Scents? Users'Judgments of Virtual Agent Personality and Appeals in Encounters | 研究嗅觉线索对虚拟代理人格感知的影响 | 解决 VR 交互中多感官线索设计对用户体验的影响 | 虚拟现实交互设计 |
| 13 | http://arxiv.org/abs/2509.11826v2 | Collaborative Document Editing with Multiple Users and AI Agents | 将 AI 代理集成到协作写作环境，通过共享对象可见化 | 解决协作者离开 workspace 使用 AI 导致的沟通与整合困难 | 多人协作文档编辑 |
| 14 | http://arxiv.org/abs/2509.12049v1 | Interaction-Driven Browsing: A Human-in-the-Loop Conceptual Framework Informed by Human Web Browsing for Browser-Using Agents | 提出人机回路概念框架，区分探索与利用动作 | 解决浏览器代理无法支持用户复杂非线性浏览与模糊目标问题 | 浏览器使用代理 |
| 15 | http://arxiv.org/abs/2509.13444v2 | DuetUI: A Bidirectional Context Loop for Human-Agent Co-Generation of Task-Oriented Interfaces | 提出人机共同生成范式，通过双向上下文循环协同构建界面 | 解决 LLM 在复杂多步任务中难以对齐模糊用户意图问题 | 任务导向界面生成 |
| 16 | http://arxiv.org/abs/2509.13547v1 | AI Agents with Human-Like Collaborative Tools: Adaptive Strategies for Enhanced Problem-Solving | 赋予代理类似人类的协作工具与自主权，提升问题解决性能 | 解决代理在能力边缘缺乏推理 scaffolding 导致性能不足问题 | 编程问题解决代理 |
| 17 | http://arxiv.org/abs/2509.15237v2 | MICA: Multi-Agent Industrial Coordination Assistant | 协调五个角色专用智能体，提供实时工业装配与维护指导。 | 解决工业工作流中适应性协助及隐私约束下的实时指导问题。 | 动态工厂环境与工业助手 |
| 18 | http://arxiv.org/abs/2509.14528v1 | Why Johnny Can't Use Agents: Industry Aspirations vs. User Realities with AI Agent Software | 系统评估商业 AI 智能体软件的用户可用性及心智模型错位。 | 解决行业宣传与用户实际使用体验及能力错位的问题。 | 商业 AI 智能体软件用户 |
| 19 | http://arxiv.org/abs/2509.14627v1 | Towards Human-like Multimodal Conversational Agent by Generating Engaging Speech | 基于对话情绪生成包含副语言信息的自然语音响应。 | 解决多模态智能体生成语音缺乏自然度及 engagement 问题。 | 多模态对话智能体 |
| 20 | http://arxiv.org/abs/2509.14803v4 | OnlineMate: An LLM-Based Multi-Agent Companion System for Cognitive Support in Online Learning | 集成理论心智，模拟同伴角色推断学习者心理状态。 | 解决在线学习缺乏个性化 peer 交互及认知支持的问题。 | 在线学习环境与學生 |
| 21 | http://arxiv.org/abs/2509.16325v1 | Overhearing LLM Agents: A Survey, Taxonomy, and Roadmap | 提出“旁听智能体”范式，分类交互任务并建立最佳实践指南。 | 解决现有对话代理需占用用户注意力、无法无缝提供上下文协助的问题。 | 人机交互/辅助助手 |
| 22 | http://arxiv.org/abs/2509.16784v1 | Controlled Yet Natural: A Hybrid BDI-LLM Conversational Agent for Child Helpline Training | 将 LLM 集成到规则基于 BDI 框架中，模拟更真实的虚拟儿童聊天。 | 解决规则基于代理语言理解有限且响应多样性不足的儿童热线训练问题。 | 儿童热线培训/对话代理 |
| 23 | http://arxiv.org/abs/2509.17619v2 | Human vs. Agent in Task-Oriented Conversations | 系统比较 LLM 模拟用户与真实人类用户行为差异 | 明确 Agent 模拟用户在任务对话中的行为偏差 | 任务导向对话系统 |
| 24 | http://arxiv.org/abs/2509.18008v2 | Through the Lens of Human-Human Collaboration: A Configurable Research Platform for Exploring Human-Agent Collaboration | 提供可配置研究平台探索人机协作原则变化 | 验证 HCI 协作原则在人机协作中的有效性 | 人机协作研究平台 |
| 25 | http://arxiv.org/abs/2509.19736v1 | UserRL: Training Interactive User-Centric Agent via Reinforcement Learning | 统一框架通过标准化 Gym 环境与模拟用户训练 Agent | 解决用户交互多样性与动态性带来的训练挑战 | 以用户为中心的交互 Agent |
| 26 | http://arxiv.org/abs/2509.21542v1 | Psychological and behavioural responses in human-agent vs. human-human interactions: a systematic review and meta-analysis | 首次系统综述人机vs人人交互的心理行为响应差异 | 人类对智能体的社会归因和道德参与低于人类交互 | 人机交互设计、Agent社会接受度 |
| 27 | http://arxiv.org/abs/2509.21849v2 | Following the TRACE: A Structured Path to Empathetic Response Generation with Multi-Agent Models | TRACE将共情建模为结构化认知过程，分解为分析-合成流水线 | 现有方法在专业模型分析深度与LLM生成流畅性间权衡 | 共情对话Agent、心理支持系统 |
| 28 | http://arxiv.org/abs/2509.20553v1 | Perspectra: Choosing Your Experts Enhances Critical Thinking in Multi-Agent Research Ideation | 可视化多智能体审议，支持@提及 targeted 代理与线程并行探索，增强用户控制。 | 解决用户难以有效控制、引导及评估多领域专家代理协作的问题。 | 研究构思与人机协作 |
| 29 | http://arxiv.org/abs/2509.20731v1 | Imagining Design Workflows in Agentic AI Futures | 通过设计虚构调查设计师与协作代理平台的交互意愿及权威分配。 | 解决设计师如何将代理系统整合到工作流及意图解释 beyond 提示词的问题。 | 设计工作流与人机协作 |
| 30 | http://arxiv.org/abs/2509.21317v2 | Interactive Recommendation Agent with Active User Commands | 开发 RecBot 双代理架构，解析自然语言命令动态编排自适应工具链。 | 解决传统推荐系统依赖被动反馈、无法捕捉用户细微行为动机的问题。 | 交互式推荐系统 |
| 31 | http://arxiv.org/abs/2509.22887v1 | Infusing Theory of Mind into Socially Intelligent LLM Agents | 将心理理论融入对话智能体，提升目标达成与关系维护。 | 解决聊天机器人缺乏社会智能与心理状态理解的问题。 | 社会性对话智能体 |
| 32 | http://arxiv.org/abs/2509.23327v2 | "Shall We Dig Deeper?": Designing and Evaluating Strategies for LLM Agents to Advance Knowledge Co-Construction in Asynchronous Online Discussions | 设计自适应干预策略，促进异步讨论中的知识共建。 | 解决在线讨论停滞于浅层信息交换，难以深入合成。 | 异步在线教育讨论 |
| 33 | http://arxiv.org/abs/2509.24073v4 | "Having Lunch Now": Understanding How Users Engage with a Proactive Agent for Daily Planning and Self-Reflection | 通过纵向研究揭示用户与主动型教练智能体的交互模式与设计考量 | 缺乏对用户如何与教练型智能体行为交互驱动因素的理解 | 日常规划与自我反思 |
| 34 | http://arxiv.org/abs/2509.24651v1 | "Stop replacing salt with sugar!": Towards Intuitive Human-Agent Teaching | 提出直观人机教学架构，支持人类通过少量示例增量教学智能体 | 解决 AI 系统难以从少量示例中学习主观任务的问题 | 食谱食材替换任务 |
| 35 | http://arxiv.org/abs/2509.24826v1 | AIPOM: Agent-aware Interactive Planning for Multi-Agent Systems | 支持人机循环规划，通过对话与图谱界面透明 inspect 与 refine 计划 | 解决 LLM 多智能体规划缺乏用户检查、理解与控制机制问题 | 多智能体工作流 |
| 36 | http://arxiv.org/abs/2509.25492v2 | Botender: Supporting Communities in Collaboratively Designing AI Agents through Case-Based Provocations | 支持社区无需代码协作设计 LLM 机器人的系统 | 机器人设计不符合广大社区需求 | 在线社区机器人设计 |
| 37 | http://arxiv.org/abs/2509.26153v3 | A Field Guide to Deploying AI Agents in Clinical Practice | 基于部署经验的面向实践者的生成式智能体部署手册 | 临床 AI 开发中社会技术工作与算法开发错位 | 临床实践 AI 部署 |

[返回目录](#目录)

<a id="cat-06"></a>

## 基于Agent的应用系统

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2509.08380v2 | Co-Investigator AI: The Rise of Agentic AI for Smarter, Trustworthy AML Compliance Narratives | 集成规划、犯罪类型检测、情报收集、合规验证专用Agent，含AI隐私保护层 | SAR报告生成成本高、可扩展性低，LLM存在事实幻觉风险 | 反洗钱合规中的可疑活动报告生成 |
| 2 | http://arxiv.org/abs/2509.09727v1 | A Role-Aware Multi-Agent Framework for Financial Education Question Answering with LLMs | 三Agent单通道迭代：基础生成器、证据检索器、专家评审器 | 现有LLM方法无法捕捉金融问题解决所需的细微专业推理 | 金融教育领域的问答系统 |
| 3 | http://arxiv.org/abs/2509.08736v2 | ChemBOMAS: Accelerated BO in Chemistry with LLM-Enhanced Multi-Agent System | 8B规模LLM回归器仅用1%标记样本生成伪数据，混合RAG引导搜索空间划分 | 化学领域贝叶斯优化效率受稀疏实验数据和巨大搜索空间限制 | 化学科学发现中的优化问题 |
| 4 | http://arxiv.org/abs/2509.09740v1 | HypoGeneAgent: A Hypothesis Language Agent for Gene-Set Cluster Resolution Selection Using Perturb-seq Datasets | LLM作为基因集分析师生成GO假设，Agent评审团评分内部一致性和外部区分性 | 单细胞研究中的聚类分辨率选择和功能注释依赖启发式和专家策划 | 单细胞多组学研究的聚类注释 |
| 5 | http://arxiv.org/abs/2509.09470v1 | AEGIS: An Agent for Extraction and Geographic Identification in Scholarly Proceedings | 专用AI Agent'Agent-E'识别特定地区论文，执行RPA完成预定义动作 | 学术文献快速增长，人工发现耗时费力 | 学术会议论文的地区识别与提名 |
| 6 | http://arxiv.org/abs/2509.09936v1 | SciML Agents: Write the Solver, Not the Solution | LLM作为SciML Agent生成可运行代码，选择合适求解器并执行稳定性检查 | 直接预测目标值的科学机器学习难以实现高精度和鲁棒性 | 科学计算中的ODE求解任务 |
| 7 | http://arxiv.org/abs/2509.03335v2 | EvolveSignal: A Large Language Model Powered Coding Agent for Discovering Traffic Signal Control Algorithms | 利用 LLM 编码智能体自动发现交通信号控制算法 | 替代人工设计公式，优化 heterogeneous 交通流控制 | 交通工程与信号控制 |
| 8 | http://arxiv.org/abs/2509.05363v1 | SasAgent: Multi-Agent AI System for Small-Angle Scattering Data Analysis | 利用 LLM 多智能体系统自动化小角散射数据分析 | 简化科学数据分析流程，实现文本交互式分析 | 小角散射科学研究 |
| 9 | http://arxiv.org/abs/2509.03828v1 | An Agentic Model Context Protocol Framework for Medical Concept Standardization | 基于 MCP 框架构建零训练防幻觉医学术语映射系统 | 解决医学术语标准化过程中资源密集与易错问题 | 医疗数据标准化 |
| 10 | http://arxiv.org/abs/2509.03890v1 | FaMA: LLM-Empowered Agentic Assistant for Consumer-to-Consumer Marketplace | 构建 LLM 代理助手，将复杂 GUI 交互转为对话式入口 | 简化 C2C 电商平台买卖双方的复杂操作流程 | 消费者电商市场 |
| 11 | http://arxiv.org/abs/2509.04152v1 | TAGAL: Tabular Data Generation using Agentic LLM Methods | 利用 LLM 代理工作流自动生成合成表格数据 | 解决机器学习任务中训练数据不足及质量提升问题 | 表格数据生成与分类 |
| 12 | http://arxiv.org/abs/2509.04183v2 | MAGneT: Coordinated Multi-Agent Generation of Synthetic Multi-Turn Mental Health Counseling Sessions | 分解咨询师响应生成任务，由专用代理协调生成会话 | 解决高质量隐私合规心理咨询数据稀缺问题 | 心理健康 counseling 数据 |
| 13 | http://arxiv.org/abs/2509.04198v1 | Are LLM Agents the New RPA? A Comparative Study with RPA Across Enterprise Workflows | 对比 LLM 代理自动化与 RPA 在企业工作流中的表现 | 评估 AACU 作为 RPA 替代方案的速度、可靠性与开发成本 | 企业工作流自动化 |
| 14 | http://arxiv.org/abs/2509.05378v3 | Code Like Humans: A Multi-Agent Solution for Medical Coding | 首个支持全 ICD-10 编码系统的多智能体医疗编码框架 | 解决罕见诊断代码编码性能差及系统盲区问题 | 医疗诊断编码 |
| 15 | http://arxiv.org/abs/2509.04752v1 | SePA: A Search-enhanced Predictive Agent for Personalized Health Coaching | 集成个性化预测模型与 RAG 的健康 coaching 系统 | 提供自适应基于证据的健康指导，平衡响应质量与速度 | 个人健康 informatics |
| 16 | http://arxiv.org/abs/2509.04871v1 | Cloning a Conversational Voice AI Agent from Call Recording Datasets for Telesales | 从通话记录数据克隆对话语音 AI 代理用于电话销售 | 自动化重复任务，降低运营成本并提供全天候支持 | 电话销售与客户服务 |
| 17 | http://arxiv.org/abs/2509.05197v1 | AI Agents for Web Testing: A Case Study in the Wild | 构建 WebProber 原型代理自主探索网站识别可用性问题 | 解决传统测试工具无法捕捉复杂用户行为问题 | 网站自动化测试 |
| 18 | http://arxiv.org/abs/2509.01063v1 | An Economy of AI Agents | 系统梳理AI agent在经济系统中的交互模式、市场影响及制度需求 | 缺乏对AI agent经济行为的系统性经济学分析框架 | 经济学家研究AI agent对市场和组织的影响 |
| 19 | http://arxiv.org/abs/2509.01379v1 | WATCHED: A Web AI Agent Tool for Combating Hate Speech by Expanding Data | 多工具AI agent整合案例对比、BERT分类、俚语查询、思维链与策略检查 | 仇恨言论检测需兼顾自动化效率与人类可解释性，建立信任 | 内容审核员辅助检测与解释仇恨言论 |
| 20 | http://arxiv.org/abs/2509.01517v1 | Agentic Workflow for Education: Concepts and Applications | AWE四组件模型（反思+工具+规划+协作），von Neumann MAS架构理论框架 | 传统LLM线性交互难以支持教育场景的个性化、协作式复杂任务 | 教育领域的个性化学习、自动评测与决策支持 |
| 21 | http://arxiv.org/abs/2509.02494v1 | GridMind: LLMs-Powered Agents for Power System Analysis and Operations | LLM agent+确定性工程求解器协同，自然语言接口保持数值精度的对话式科学计算 | 传统电力系统分析工作流复杂，专家知识获取与决策支持效率低 | 电力系统的潮流计算、安全分析等工程决策支持 |
| 22 | http://arxiv.org/abs/2509.05469v2 | From Image Generation to Infrastructure Design: a Multi-agent Pipeline for Street Design Generation | 多智能体管道直接在街景图编辑自行车设施，实现真实渲染 | 解决传统街道设计耗时且难以协作的问题 | 城市规划与公共交通设计 |
| 23 | http://arxiv.org/abs/2509.05933v2 | MapAgent: A Hierarchical Agent for Geospatial Reasoning with Dynamic Map Tool Integration | 分层多智能体框架，解耦规划与执行，集成动态地图工具 | 解决现有框架在地理空间任务中工具选择准确性低的问题 | 地理空间推理与地图交互 |
| 24 | http://arxiv.org/abs/2509.06216v2 | Agentic Software Engineering: Foundational Pillars and a Research Roadmap | 提出 SE 3.0 愿景，定义人与代理双模态协作的基础支柱 | 解决代理时代软件工程信任worthiness 与基础重构问题 | 软件工程专业与教育 |
| 25 | http://arxiv.org/abs/2509.06586v1 | Simulating Dispute Mediation with LLM-Based Agents for Legal Research | 首个基于 LLM 代理的纠纷调解模拟框架，支持可控实验 | 解决法律纠纷调解实证研究受隐私与多变量限制问题 | 法律研究与纠纷调解 |
| 26 | http://arxiv.org/abs/2509.06602v2 | Demo: Healthcare Agent Orchestrator (HAO) for Patient Summarization in Molecular Tumor Boards | 协调多代理临床工作流，生成准确全面的患者摘要 | 解决肿瘤委员会患者摘要手动编制耗时且易遗漏问题 | 医疗健康与肿瘤委员会 |
| 27 | http://arxiv.org/abs/2509.07283v3 | An Agentic AI Workflow to Simplify Parameter Estimation of Complex Differential Equation Systems | 将轻量规格转化为编译并行可微模型校准 pipeline | 解决微分方程系统参数识别手动且劳动密集型问题 | 科学计算与模型校准 |
| 28 | http://arxiv.org/abs/2509.07506v2 | Astra: A Multi-Agent System for GPU Kernel Performance Optimization | 首个基于 LLM 多代理系统优化 GPU 内核，迭代生成测试 | 解决 GPU 内核优化依赖手动 tuning 且编译器负担重问题 | 高性能计算与 GPU 优化 |
| 29 | http://arxiv.org/abs/2509.09995v3 | QuantAgent: Price-Driven Multi-Agent LLMs for High-Frequency Trading | 首创高频交易多智能体框架，分解为指标、模式等四 agent | 解决 LLM 难以适应高频交易速度与精度需求的问题 | 金融高频交易场景 |
| 30 | http://arxiv.org/abs/2509.12251v1 | V-Math: An Agentic Approach to the Vietnamese National High School Graduation Mathematics Exams | 集成生成、求解、辅导三 agent，支持自适应数学备考 | 解决学生备考资源不足及教师出题 workload 大的问题 | 越南高中数学教育与考试 |
| 31 | http://arxiv.org/abs/2509.10210v1 | Towards Fully Automated Molecular Simulations: Multi-Agent Framework for Simulation Setup and Force Field Extraction | LLM 智能体自主理解任务、规划模拟并提取力场 | 解决多孔材料表征中模拟设置与力场选择的复杂性 | 材料科学与分子模拟 |
| 32 | http://arxiv.org/abs/2509.10761v1 | EditDuet: A Multi-Agent System for Video Non-Linear Editing | 编辑器与评论家双 agent，学习式通信实现视频编辑 | 解决视频编辑核心任务自动化程度低的问题 | 视频非线性编辑 |
| 33 | http://arxiv.org/abs/2509.11062v2 | Auto-Slides: An Interactive Multi-Agent System for Creating and Customizing Research Presentations | 多 agent 框架将论文转化为教学幻灯片，支持交互定制 | 解决学习者系统理解复杂概念及 engagement 低的问题 | 教育与学术演示生成 |
| 34 | http://arxiv.org/abs/2509.11136v1 | Agentic Username Suggestion and Multimodal Gender Detection in Online Platforms: Introducing the PNGT-26K Dataset | 引入 PNGT-26K 数据集，Agentic AI 辅助用户名选择 | 解决波斯语名字性别检测及数字身份创建难题 | 在线平台用户身份管理 |
| 35 | http://arxiv.org/abs/2509.11183v1 | WeaveMuse: An Open Agentic System for Multimodal Music Understanding and Generation | 多 agent 系统协调音乐理解、符号作曲与音频合成 | 解决复杂多模态音乐任务协调与可控性问题 | 音乐信息检索与生成 |
| 36 | http://arxiv.org/abs/2509.11478v2 | Designing and Evaluating a Conversational Agent for Early Diagnosis of Alzheimer's Disease and Related Dementias | 语音交互代理 eliciting 叙事，支持 ADRD 早期诊断 | 解决阿尔茨海默病诊断延迟及患者叙事获取难问题 | 医疗健康诊断支持 |
| 37 | http://arxiv.org/abs/2509.11507v1 | MedicalOS: An LLM Agent based Operating System for Digital Healthcare | 医疗领域专用抽象层，翻译人类指令为数字医疗命令 | 解决临床系统难用及医生行政负担重的问题 | 数字医疗工作流自动化 |
| 38 | http://arxiv.org/abs/2509.11595v1 | AMLNet: A Knowledge-Based Multi-Agent Framework to Generate and Detect Realistic Money Laundering Transactions | 知识驱动多 agent 框架生成与检测洗钱交易 | 解决 AML 研究缺乏公开共享且合规数据集的问题 | 反洗钱金融监管 |
| 39 | http://arxiv.org/abs/2509.11773v3 | AgenticIE: An Adaptive Agent for Information Extraction from Complex Regulatory Documents | 规划 - 执行 - 对应模式，自适应提取监管文档信息 | 解决欧盟建筑产品性能声明文档机器可读性差问题 | 监管文档信息提取 |
| 40 | http://arxiv.org/abs/2509.11942v1 | VisDocSketcher: Towards Scalable Visual Documentation with Agentic Systems | 结合静态分析与 LLM 代理自动生成代码视觉文档 | 解决手动创建视觉文档耗时且难以评估质量的问题 | 软件工程与代码文档 |
| 41 | http://arxiv.org/abs/2509.11944v1 | Agentic Temporal Graph of Reasoning with Multimodal Language Models: A Potential AI Aid to Healthcare | 提出基于时序图的推理过程模型，支持回溯与动态调整 | 解决多模态医疗数据推理中动态变化跟踪与诊断准确性问题 | 医疗诊断辅助 |
| 42 | http://arxiv.org/abs/2509.12443v3 | From Legacy Fortran to Portable Kokkos: An Autonomous Agentic AI Workflow | 构建代理 AI 工作流，协作翻译优化 Fortran 到 Kokkos 代码 | 解决 legacy 科学代码向异构 GPU 架构迁移耗时且需专家知识问题 | 高性能计算代码迁移 |
| 43 | http://arxiv.org/abs/2509.12589v1 | Redefining CX with Agentic AI: Minerva CQ Case Study | 集成实时转录与意图检测，提供主动工作流支持 | 解决客服中心代理认知负荷高导致处理时间长与满意度低问题 | 客户体验与客服中心 |
| 44 | http://arxiv.org/abs/2509.12753v1 | DeltaHedge: A Multi-Agent Framework for Portfolio Options Optimization | 结合强化学习与集成期权对冲策略优化投资组合 | 解决波动市场中传统方法忽略期权交易优势导致风险回报失衡问题 | 金融投资组合管理 |
| 45 | http://arxiv.org/abs/2509.13021v1 | xOffense: An AI-driven autonomous penetration testing framework with offensive knowledge-enhanced LLMs and multi agent systems | 利用微调 LLM 驱动多代理渗透测试，自动化工作流 | 解决渗透测试依赖人工专家努力且难以规模化问题 | 自主渗透测试 |
| 46 | http://arxiv.org/abs/2509.13137v1 | Agentic AI for Financial Crime Compliance | 设计代理 AI 系统自动化合规流程，强调可解释性与审计 | 解决金融犯罪合规成本高且现有 AI 方案不透明不符合监管问题 | 金融犯罪合规 |
| 47 | http://arxiv.org/abs/2509.13471v2 | An LLM Agentic Approach for Legal-Critical Software: A Case Study for Tax Prep Software | 利用 LLM 驱动框架自动化测试生成与代码合成，处理法律关键软件 | 解决法律关键设置中因歧义与幻觉导致可靠性挑战问题 | 法律关键软件开发 |
| 48 | http://arxiv.org/abs/2509.13557v6 | MACO: A Multi-Agent LLM-Based Hardware/Software Co-Design Framework for CGRAs | 多代理框架迭代改进 CGRA 架构，自动纠正设计错误 | 解决 CGRA 设计空间巨大且手动迭代成本高难题 | 硬件软件协同设计 |
| 49 | http://arxiv.org/abs/2509.15233v1 | Video2Roleplay: A Multimodal Dataset and Framework for Video-Guided Role-playing Agents | 引入视频模态构建动态角色档案，提出 Video2Roleplay 框架。 | 解决现有角色扮演智能体缺乏动态感知能力的问题。 | 角色扮演智能体与交互式对话 |
| 50 | http://arxiv.org/abs/2509.13704v1 | InfraMind: A Novel Exploration-based GUI Agentic Framework for Mission-critical Industrial Management | 集成探索、记忆、状态识别等模块的工业 GUI 智能体框架。 | 解决工业管理系统复杂 GUI 自动化操作的灵活性与安全问题。 | 关键工业基础设施管理 |
| 51 | http://arxiv.org/abs/2509.14030v1 | CrowdAgent: Multi-Agent Managed Multi-Source Annotation System | 整合任务分配、标注及质量管理的多智能体众包标注系统。 | 解决多源标注数据管理中调度复杂及质量成本权衡问题。 | 多模态数据标注与管理 |
| 52 | http://arxiv.org/abs/2509.14483v1 | An LLM-based multi-agent framework for agile effort estimation | 提出基于 LLM 多智能体框架，协调人类开发者进行敏捷估算。 | 解决敏捷估算依赖主观评估及缺乏解释性与交互性问题。 | 敏捷软件开发估算 |
| 53 | http://arxiv.org/abs/2509.18178v2 | Foam-Agent 2.0: An End-to-End Composable Multi-Agent Framework for Automating CFD Simulation in OpenFOAM | 实现端到端 CFD 模拟自动化，支持可组合服务架构。 | 解决 CFD 模拟学习曲线陡峭及手动设置复杂的问题。 | 计算流体动力学工程模拟 |
| 54 | http://arxiv.org/abs/2509.14542v1 | S1-MatAgent: A planner driven multi-agent system for material discovery | 采用规划器 - 执行器架构，自动分解材料设计任务。 | 解决材料研究多智能体系统依赖预定义配置及适应性差问题。 | 高性能材料发现与设计 |
| 55 | http://arxiv.org/abs/2509.14744v1 | On the Use of Agentic Coding Manifests: An Empirical Study of Claude Code | 分析智能体编码 manifest 文件结构，提供配置指导。 | 解决开发者创建智能体配置文件缺乏文档及标准的问题。 | 智能体编码工具开发者 |
| 56 | http://arxiv.org/abs/2509.14745v3 | On the Use of Agentic Coding: An Empirical Study of Pull Requests on GitHub | 实证研究 GitHub 上智能体生成的 Pull Request 接受度。 | 解决对智能体辅助代码贡献实用性及接受度认知不足问题。 | 开源软件项目开发 |
| 57 | http://arxiv.org/abs/2509.14778v2 | OpenLens AI: Fully Autonomous Research Agent for Health Infomatics | 集成文献 review、数据分析等智能体，自动化健康信息学研究。 | 解决健康信息学研究缺乏医疗可视化解释及质量管控问题。 | 健康信息学自动化研究 |
| 58 | http://arxiv.org/abs/2509.14834v2 | LLM Agents at the Roundtable: A Multi-Perspective and Dialectical Reasoning Framework for Essay Scoring | 构建多视角评估智能体，通过辩证推理达成评分共识。 | 解决自动作文评分缺乏人类水平多视角理解及判断问题。 | 教育领域自动作文评分 |
| 59 | http://arxiv.org/abs/2509.14877v1 | AI-Driven Multi-Agent Vehicular Planning for Battery Efficiency and QoS in 6G Smart Cities | 扩展模拟器支持动态智能体规划，优化车辆电池及 QoS。 | 解决车联网模拟缺乏动态规划及电池能耗优化支持问题。 | 6G 智慧城市车联网 |
| 60 | http://arxiv.org/abs/2509.15378v2 | Conversational Agents in Behavioral Sleep Medicine: Designing Self-Report and Analytics Tools | 设计语音睡眠日记及分析工具，探索对话智能体在睡眠医学应用。 | 解决传统睡眠日记依从性低及上下文信息 capture 不足问题。 | 行为睡眠医学临床 care |
| 61 | http://arxiv.org/abs/2509.15635v1 | MicroRCA-Agent: Microservice Root Cause Analysis Method Based on Large Language Model Agents | 结合日志解析与多模态数据融合，设计双异常检测与两阶段 LLM 分析策略。 | 解决微服务架构下故障根因定位复杂且效率低的问题。 | 微服务运维/故障分析 |
| 62 | http://arxiv.org/abs/2509.16811v2 | Prompt-Driven Agentic Video Editing System: Autonomous Comprehension of Long-Form, Story-Driven Media | 构建语义索引管道，通过提示驱动重构多小时内容而非时间线。 | 解决创作者编辑长视频时搜索、分镜与序列化的认知负荷过高问题。 | 视频编辑/媒体创作 |
| 63 | http://arxiv.org/abs/2509.17167v1 | SFT-TA: Supervised Fine-Tuned Agents in Multi-Agent LLMs for Automated Inductive Thematic Analysis | 将监督微调代理嵌入多智能体系统，自动化临床访谈转录主题分析。 | 解决手动主题分析耗时且现有 LLM 自动化方法与人类结果对齐有限的问题。 | qualitative 研究/主题分析 |
| 64 | http://arxiv.org/abs/2509.17240v1 | Can Agents Judge Systematic Reviews Like Humans? Evaluating SLRs with LLM-based Multi-Agent System | 构建多智能体系统辅助评估系统文献综述质量，对齐 PRISMA 指南。 | 解决系统文献综述劳动密集型且跨学科不一致的问题。 | 学术研究/文献综述评估 |
| 65 | http://arxiv.org/abs/2509.17255v1 | Agentic AI for Multi-Stage Physics Experiments at a Large-Scale User Facility Particle Accelerator | 首个语言模型驱动代理系统，自主执行粒子加速器多阶段物理实验。 | 解决大型科学设施实验准备耗时且手动脚本易错的问题。 | 粒子加速器/科学实验 |
| 66 | http://arxiv.org/abs/2509.17353v1 | Medical AI Consensus: A Multi-Agent Framework for Radiology Report Generation and Evaluation | 集成十种专用代理，实现放射学报告生成与细粒度评估的多代理框架。 | 解决放射学报告生成系统临床可靠性低且缺乏严谨评估协议的问题。 | 医疗放射学/报告生成 |
| 67 | http://arxiv.org/abs/2509.17395v1 | FinDebate: Multi-Agent Collaborative Intelligence for Financial Analysis | 集成五种专用代理并行运行，引入安全辩论协议缓解过度自信。 | 解决金融分析中单一模型可靠性低且缺乏多维度洞察与校准置信度的问题。 | 金融分析/投资决策 |
| 68 | http://arxiv.org/abs/2509.18230v1 | Towards General Computer Control with Hierarchical Agents and Multi-Level Action Spaces | 轻量级分层 RL 框架实现 OS 控制，参数量极小 | 解决多模态大模型控制桌面应用延迟高部署难问题 | 桌面应用自动化控制 |
| 69 | http://arxiv.org/abs/2509.18405v1 | Check Field Detection Agent (CFD-Agent) using Multimodal Large Language and Vision Language Models | 利用 VLM 与 MLLM 实现零样本支票字段检测 | 解决金融支票欺诈检测中数据稀缺与标注成本高问题 | 金融支票防伪检测 |
| 70 | http://arxiv.org/abs/2509.18661v1 | Agentic AutoSurvey: Let LLMs Survey LLMs | 四智能体协作框架自动生成高质量文献综述 | 解决科研文献爆炸导致知识综合困难与挑战 | 学术文献自动综述 |
| 71 | http://arxiv.org/abs/2509.18710v2 | Autonomous Data Agents: A New Opportunity for Smart Data | 定义 DataAgents 自主解释数据任务并执行工作流 | 解决数据准备与分析劳动密集且难以规模化问题 | 智能数据管理与分析 |
| 72 | http://arxiv.org/abs/2510.01235v1 | Automated Extraction of Material Properties using LLM-based AI Agents | 智能体工作流自主从科学文章提取热电与结构属性 | 解决材料科学缺乏大规模机器可读数据集问题 | 材料科学数据提取 |
| 73 | http://arxiv.org/abs/2509.19566v1 | Nano Bio-Agents (NBA): Small Language Model Agents for Genomics | 小语言模型智能体框架结合工具编排回答基因组问题 | 解决大模型幻觉与计算成本高风险问题 | 基因组学问答 |
| 74 | http://arxiv.org/abs/2509.19640v1 | AutoSpec: An Agentic Framework for Automatically Drafting Patent Specification | 安全智能体框架分解 drafting 过程为可管理子任务 | 解决专利起草昂贵耗时且封闭模型无法使用问题 | 专利自动起草 |
| 75 | http://arxiv.org/abs/2509.19789v1 | RDAR: Reward-Driven Agent Relevance Estimation for Autonomous Driving | 学习每智能体相关性掩码减少行为模型输入 | 解决自动驾驶系统处理复杂场景中众多 Agent 计算昂贵问题 | 自动驾驶行为预测 |
| 76 | http://arxiv.org/abs/2509.20414v2 | SceneWeaver: All-in-One 3D Scene Synthesis with an Extensible and Self-Reflective Agent | 反射智能体框架统一多样场景合成范式工具迭代优化 | 解决室内场景合成缺乏物理一致性与复杂指令对齐问题 | 3D 室内场景生成 |
| 77 | http://arxiv.org/abs/2509.21553v2 | AutoClimDS: Climate Data Science Agentic AI -- A Knowledge Graph is All You Need | 知识图谱+Agent工作流实现气候数据科学自动化分析 | 气候数据碎片化、格式异构、技术门槛高 | 气候科学研究、数据科学家 |
| 78 | http://arxiv.org/abs/2510.02325v1 | Agentic-AI Healthcare: Multilingual, Privacy-First Framework with MCP Agents | MCP协议编排多Agent，集成隐私合规层 | 医疗AI的多语言可及性与数据隐私保护 | 医疗健康、患者-医生交互 |
| 79 | http://arxiv.org/abs/2510.02328v1 | AMANDA: Agentic Medical Knowledge Augmentation for Data-Efficient Medical Visual Question Answering | 训练-free Agent框架，内外医学知识增强Med-VQA | 低资源场景下Med-MLLMs医学推理能力瓶颈 | 医疗影像问答、低资源医疗场景 |
| 80 | http://arxiv.org/abs/2511.14767v1 | An LLM-Powered Agent for Real-Time Analysis of the Vietnamese IT Job Market | ReAct框架Agent，工具增强SQL查询、语义搜索、数据可视化 | 就业市场报告过时，手动分析海量招聘信息不现实 | 越南IT就业市场、求职者职业指导 |
| 81 | http://arxiv.org/abs/2509.21825v4 | DS-STAR: Data Science Agent for Solving Diverse Tasks across Heterogeneous Formats and Open-Ended Queries | 无缝处理异构格式数据，生成开放式查询综合研究报告 | 现有Agent难处理真实工作流多源探索与综合洞察 | 数据科学工作流、研究报告生成 |
| 82 | http://arxiv.org/abs/2510.00031v3 | VibeCodeHPC: An Agent-Based Iterative Prompting Auto-Tuner for HPC Code Generation Using LLMs | 四角色多Agent（PM/SE/PG/CD）自主性能优化，无需用户干预 | 超算HPC编程门槛高，性能优化需专业 expertise | 高性能计算、超算代码开发 |
| 83 | http://arxiv.org/abs/2509.21910v1 | AutoSCORE: Enhancing Automated Scoring with Multi-Agent LLMs via Structured Component Recognition | 两Agent流水线：提取评分标准组件→分配最终分数 | LLM端到端评分准确率低、提示敏感、可解释性差 | 教育自动评分、学生作业评估 |
| 84 | http://arxiv.org/abs/2509.21982v1 | RISK: A Framework for GUI Agents in E-commerce Risk Management | R1风格强化微调框架，四层级奖励（输出/单步/多步/任务） | 电商风险管理需多步状态ful交互，传统GUI Agent限于单步 | 电商风险监测、复杂网页交互自动化 |
| 85 | http://arxiv.org/abs/2509.22170v1 | Leveraging LLM Agents for Automated Video Game Testing | TITAN四组件：状态抽象、动作优化、长horizon推理、LLM oracle检测bug | MMORPG测试劳动密集，现有方法状态覆盖率和效率低 | 游戏QA、MMORPG自动化测试 |
| 86 | http://arxiv.org/abs/2509.22218v1 | VizGen: Data Exploration and Visualization from Natural Language via a Multi-Agent AI Architecture | 多Agent架构处理SQL生成、图表创建、定制、洞察提取 | 传统可视化工具需技术 expertise，限制可及性 | 数据探索可视化、非技术用户 |
| 87 | http://arxiv.org/abs/2510.17814v1 | LLM Assisted Alpha Fairness for 6 GHz WiFi and NR_U Coexistence: An Agentic Orchestrator for Throughput, Energy, and SLA | Agent分离策略与执行，LLM提议可解释knobs，确定性优化器强制执行 | 6GHz无许可频段Wi-Fi和NR-U竞争，需联合权衡吞吐量/能量/SLA | 6GHz WiFi、5G NR-U共存、无线通信 |
| 88 | http://arxiv.org/abs/2509.20067v4 | MACD: Multi-Agent Clinical Diagnosis with Self-Learned Knowledge for LLM | 构建 MACD 框架，允许 LLM 通过多智能体流水线自学习临床知识，模拟医生专家经验积累。 | 解决传统提示词方法难以处理复杂真实世界临床诊断的问题。 | 医疗临床诊断 |
| 89 | http://arxiv.org/abs/2509.20182v1 | Automated Multi-Agent Workflows for RTL Design | 集成形式化验证反馈到工作流生成，自动 compose 多智能体工作流用于 RTL 代码生成。 | 解决 HDL 资源稀缺导致的任务特定微调成本高、手动编排难的问题。 | 芯片 RTL 设计 |
| 90 | http://arxiv.org/abs/2509.20270v1 | Scan-do Attitude: Towards Autonomous CT Protocol Management using a Large Language Model Agent | 结合上下文学习与结构化工具调用，辅助解释执行 CT 协议配置请求。 | 解决 CT 扫描协议管理耗时且需专业技能，缓解放射科人力短缺。 | 医疗 CT 扫描协议管理 |
| 91 | http://arxiv.org/abs/2509.20279v1 | A co-evolving agentic AI system for medical imaging analysis | 提出 TissueLab 共进化系统，整合工具工厂，支持实时交互分析与专家反馈闭环。 | 解决医疗图像分析缺乏 robust 生态系统及实时专家反馈的问题。 | 医疗影像分析与病理研究 |
| 92 | http://arxiv.org/abs/2510.00024v2 | EpidemIQs: Prompt-to-Paper LLM Agents for Epidemic Modeling and Analysis | 集成五阶段研究流程，自主完成文献综述、建模、仿真及论文撰写。 | 解决流行病建模复杂度高、跨学科研究自动化程度低的问题。 | 流行病学建模与研究 |
| 93 | http://arxiv.org/abs/2509.20490v3 | RadAgents: Multimodal Agentic Reasoning for Chest X-ray Interpretation with Radiologist-like Workflows | 耦合临床先验与任务感知多模态推理，编码放射科医生工作流到可审计管道。 | 解决胸部 X 光解释推理不可解释、多模态证据融合不足的问题。 | 医疗胸部 X 光解读 |
| 94 | http://arxiv.org/abs/2509.20600v1 | An LLM-based Agentic Framework for Accessible Network Control | 使用中间表示简化配置，实时检索网络状态，提供自然语言网络管理接口。 | 解决传统网络管理门槛高，非专家用户难以操作的问题。 | 网络控制与管理 |
| 95 | http://arxiv.org/abs/2509.21291v1 | VC-Agent: An Interactive Agent for Customized Video Dataset Collection | 定义用户友好方式指定需求，利用多模态 LLM 连接需求与视频内容。 | 解决收集满足特定需求的大量视频数据劳动密集且耗时的问题。 | 定制化视频数据集收集 |
| 96 | http://arxiv.org/abs/2509.25244v1 | Neo-Grounded Theory: A Methodological Innovation Integrating High-Dimensional Vector Clustering and Multi-Agent Collaboration for Qualitative Research | 融合向量聚类与多智能体协作，实现定性研究自动化分析。 | 解决定性研究规模与深度的矛盾，大幅降低成本。 | 社会科学研究/定性数据分析 |
| 97 | http://arxiv.org/abs/2509.22631v1 | LABELING COPILOT: A Deep Research Agent for Automated Data Curation in Computer Vision | 引入多步推理协调专用工具，实现视觉数据自动化策展。 | 解决大规模未标注数据中高质量数据集构建瓶颈。 | 计算机视觉数据 curated |
| 98 | http://arxiv.org/abs/2509.22644v1 | WebGen-Agent: Enhancing Interactive Website Generation with Multi-Level Feedback and Step-Level Reinforcement Learning | 利用多级视觉反馈与步级 RL，迭代生成网站代码。 | 解决现有代码智能体缺乏视觉交互反馈验证的问题。 | 交互式网站生成 |
| 99 | http://arxiv.org/abs/2509.23045v3 | Kimi-Dev: Agentless Training as Skill Prior for SWE-Agents | 利用无智能体训练诱导技能先验，赋能软件工程智能体。 | 解决工作流与智能体框架间的技能迁移与效率问题。 | 软件工程智能体 |
| 100 | http://arxiv.org/abs/2509.23141v3 | Earth-Agent: Unlocking the Full Landscape of Earth Observation with Agents | 统一 RGB 与光谱数据，启用跨模态时空推理工具生态。 | 解决地球观测任务中多步推理与领域工具缺乏问题。 | 地球观测科学任务 |
| 101 | http://arxiv.org/abs/2509.23263v2 | GUI-PRA: Process Reward Agent for GUI Tasks | 引入动态记忆与自适应 UI 感知，优化 GUI 任务过程奖励。 | 解决 GUI 智能体长程任务中上下文丢失与状态感知缺失。 | 图形用户界面任务 |
| 102 | http://arxiv.org/abs/2511.03731v1 | MimiTalk: Revolutionizing Qualitative Research with Dual-Agent AI | 双智能体宪法 AI 框架，实现可扩展伦理对话数据收集。 | 解决定性研究中访谈焦虑、一致性与规模化难题。 | 社会科学研究访谈 |
| 103 | http://arxiv.org/abs/2509.25257v1 | RANGER -- Repository-Level Agent for Graph-Enhanced Retrieval | 构建仓库级知识图谱，双阶段检索支持实体与自然语言查询。 | 解决代码检索中跨文件依赖与自然语言查询的鸿沟。 | 自动化软件工程 |
| 104 | http://arxiv.org/abs/2509.23675v1 | PAT-Agent: Autoformalization for Model Checking | 端到端框架，结合 LLM 生成与形式化验证修复模型。 | 解决自然语言到形式逻辑自动转换中的幻觉与语义鸿沟。 | 形式化验证系统 |
| 105 | http://arxiv.org/abs/2510.02359v1 | Emission-GPT: A domain-specific language model agent for knowledge retrieval, emission inventory and data analysis | 领域增强 LLM 智能体，支持排放数据交互式分析与可视化。 | 解决排放知识碎片化与非专家解读 emissions 数据难题。 | 大气排放管理 |
| 106 | http://arxiv.org/abs/2509.23725v3 | MedLA: A Logic-Driven Multi-Agent Framework for Complex Medical Reasoning with Large Language Models | 逻辑树驱动多智能体框架，通过辩论解决细粒度逻辑不一致。 | 解决复杂医疗问答中缺乏结构化多视角推理问题。 | 医疗诊断与问答 |
| 107 | http://arxiv.org/abs/2509.23768v1 | From What to Why: A Multi-Agent System for Evidence-based Chemical Reaction Condition Reasoning | 多智能体系统将条件预测重构为证据基于推理任务。 | 解决化学反应推荐缺乏可解释理由与科学依据问题。 | 化学科学发现 |
| 108 | http://arxiv.org/abs/2509.23986v1 | TusoAI: Agentic Optimization for Scientific Methods | 引入 TusoAI 系统，自主开发并优化科学计算方法，集成领域知识树 | 解决科学发现中计算工具手动开发成本高、耗时久的问题 | 科学计算与数据分析 |
| 109 | http://arxiv.org/abs/2509.24127v1 | Transparent, Evaluable, and Accessible Data Agents: A Proof-of-Concept Framework | 提出模块化架构，支持自然语言交互企业数据仓库，确保透明决策 | 解决非技术用户难以访问复杂数据仓库及语义鸿沟问题 | 企业数据分析 |
| 110 | http://arxiv.org/abs/2509.24229v1 | Model Fusion with Multi-LoRA Inference for Tool-Enhanced Game Dialogue Agents | 利用多 LoRA 推理与模型融合，处理游戏对话中的工具调用与生成 | 解决游戏对话 AI 在资源约束下兼顾人设与功能调用的问题 | 游戏对话 AI |
| 111 | http://arxiv.org/abs/2509.24263v2 | PAME-AI: Patient Messaging Creation and Optimization using Agentic AI | 基于 DIKW  hierarchy，利用专用智能体系统优化患者消息设计 | 解决传统移动消息设计无法探索高维设计空间的问题 | 医疗健康沟通 |
| 112 | http://arxiv.org/abs/2509.24405v1 | Multilingual Text-to-SQL: Benchmarking the Limits of Language Models with Collaborative Language Agents | 扩展 Spider 2.0 至八种语言，提供协作语言智能体基线提升准确率 | 解决 Text-to-SQL 基准仅英语限制多语言进展及推理深度问题 | 多语言数据库访问 |
| 113 | http://arxiv.org/abs/2509.24463v2 | An Agent-Based Framework for Automated Higher-Voice Harmony Generation | 提出多智能体系统，模拟人类音乐家协作生成高音和声 | 解决算法作曲中音乐连贯性与美学和谐生成的挑战 | 音乐创作与生成 |
| 114 | http://arxiv.org/abs/2509.24515v1 | Agentic Specification Generator for Move Programs | 提出 MSG 工具，利用 LLM 为 Move 智能合约自动生成可验证规范 | 解决新兴验证导向语言缺乏 LLM 规范生成工具的问题 | 智能合约开发 |
| 115 | http://arxiv.org/abs/2509.24698v1 | LISA Technical Report: An Agentic Framework for Smart Contract Auditing | 结合规则与逻辑方法，利用历史审计报告数据检测智能合约漏洞 | 解决智能合约漏洞检测依赖人工及传统工具覆盖率低的问题 | 智能合约审计 |
| 116 | http://arxiv.org/abs/2509.25297v2 | Automatically Generating Web Applications from Requirements Via Multi-Agent Test-Driven Development | 首个支持测试驱动开发的全栈 Web 应用生成框架 | 解决全栈自动化中需求不明确和依赖复杂问题 | 全栈 Web 应用开发 |
| 117 | http://arxiv.org/abs/2509.25084v3 | Scaling Generalist Data-Analytic Agents | 可扩展的数据合成与智能体训练配方 DataMind | 开源模型难以处理多样格式数据和长程推理 | 通用数据分析智能体 |
| 118 | http://arxiv.org/abs/2509.25510v2 | EEsizer: LLM-Based AI Agent for Sizing of Analog and Mixed Signal Circuit | 集成 LLM 与电路模拟器的全自动晶体管 sizing 智能体 | 模拟电路设计手动 effort 大且迭代多 | 模拟与混合信号电路设计 |
| 119 | http://arxiv.org/abs/2509.25540v2 | RadOnc-GPT: An Autonomous LLM Agent for Real-Time Patient Outcomes Labeling at Scale | 自主检索患者信息并评估证据的结构化结果智能体 | 手动标注限制放射肿瘤学研究规模与时效 | 放射肿瘤学患者结果标注 |
| 120 | http://arxiv.org/abs/2509.25651v1 | AutoLabs: Cognitive Multi-Agent Systems with Self-Correction for Autonomous Chemical Experimentation | 具有自校正能力的多智能体架构翻译自然语言指令 | 自动驾驶实验室 underlying AI 智能体可靠性不足 | 自主化学实验 |
| 121 | http://arxiv.org/abs/2509.25693v3 | ScheduleMe: Multi-Agent Calendar Assistant | 使用图结构协调机制的多智能体日历助手 | 解决用户命令歧义与冲突 | 个人日历管理 |
| 122 | http://arxiv.org/abs/2509.26006v2 | AgenticIQA: An Agentic Framework for Adaptive and Interpretable Image Quality Assessment | 集成 VLM 与传统 IQA 工具的模块化智能体框架 | 固定模型适应性差且评分与解释独立 | 图像质量评估 |
| 123 | http://arxiv.org/abs/2509.26110v1 | Agent-based code generation for the Gammapy framework | 开发能在受控环境编写执行验证代码的智能体 | 专用科学库缺乏资源且 API 不稳定 | 科学软件代码生成 |
| 124 | http://arxiv.org/abs/2509.26201v2 | LLM Agents for Knowledge Discovery in Atomic Layer Processing | 利用工具功能供智能体 interrogate 黑盒函数 | 知识发现需自由探索系统而非特定任务 | 材料科学知识发现 |
| 125 | http://arxiv.org/abs/2509.26386v2 | PANDA: Towards Generalist Video Anomaly Detection via Agentic AI Engineer | 基于 MLLM 的具身 AI 工程师实现通用视频异常检测 | 现有方法依赖特定训练数据且泛化有限 | 视频异常检测 |
| 126 | http://arxiv.org/abs/2509.26461v1 | CreAgentive: An Agent Workflow Driven Multi-Category Creative Generation Engine | 基于故事原型和三阶段工作流的创意生成引擎 | 当代 LLM 在创作中体裁多样性和连贯性不足 | 故事与戏剧创作 |
| 127 | http://arxiv.org/abs/2510.00156v1 | AuditAgent: Expert-Guided Multi-Agent Reasoning for Cross-Document Fraudulent Evidence Discovery | 增强审计领域 expertise 的细粒度证据链定位框架 | 现实场景中财务欺诈证据 subtlety 且分散 | 金融欺诈检测 |
| 128 | http://arxiv.org/abs/2510.02389v3 | From Trace to Line: LLM Agent for Real-World OSS Vulnerability Localization | 通过 AST 分块和证据引导 refinement 逐步缩小范围 | 现有方法检查代码孤立且定位 coarse | 开源软件漏洞定位 |

[返回目录](#目录)

<a id="cat-07"></a>

## 具身智能Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2509.08535v2 | Agents of Discovery | 创建LLM Agent团队，类似人类研究者方式创建代码操作标准工具和库 | 现代粒子物理数据分析工具链复杂度不断增加 | 粒子物理等领域的基础研究数据分析 |
| 2 | http://arxiv.org/abs/2509.09154v1 | Mind Meets Space: Rethinking Agentic Spatial Intelligence from a Neuroscience-inspired Perspective | 神经科学启发的计算框架，映射六个核心生物功能到计算模块 | Agent空间推理能力有限，局限于符号和序列处理 | 虚拟和物理环境中的空间推理 |
| 3 | http://arxiv.org/abs/2509.09560v1 | Boosting Embodied AI Agents through Perception-Generation Disaggregation and Asynchronous Pipeline Execution | Auras框架解耦感知和生成，提供受控流水线并行，建立公共上下文共享 | 传统顺序计算模式无法实现真实应用所需的"思考"频率 | 动态环境中的具身AI系统 |
| 4 | http://arxiv.org/abs/2509.03956v1 | World Model Implanting for Test-time Adaptation of Embodied Agents | 提出世界模型植入框架，结合 LLM 推理与领域模型 | 解决具身代理在新领域适应需大量数据收集或重训练问题 | 具身机器人跨域适应 |
| 5 | http://arxiv.org/abs/2509.04731v3 | Generative World Models of Tasks: LLM-Driven Hierarchical Scaffolding for Embodied Agents | 利用 LLM 作为生成式任务世界模型提供分层支架 | 解决复杂长 horizon 多代理任务探索空间不可行问题 | 具身机器人任务学习 |
| 6 | http://arxiv.org/abs/2509.05338v1 | Plantbot: Integrating Plant and Robot through LLM Modular Agent Networks | LLM模块异步通信架构，自然语言作为生物 - 机器人系统的通用协议 | 生物系统与机器人系统间缺乏统一的交互与协调机制 | 植物 - 机器人混合生命体的自适应环境响应 |
| 7 | http://arxiv.org/abs/2509.02322v1 | OmniActor: A Generalist GUI and Embodied Agent for 2D&3D Worlds | 层异构MoE分离深浅层参数消除数据冲突，统一GUI+具身动作空间+大规模混合训练 | GUI与具身数据混合训练导致性能退化，难以构建通用2D/3D交互agent | 需要交替交互虚拟与现实世界的复杂多模态任务 |
| 8 | http://arxiv.org/abs/2509.02444v2 | AppCopilot: Toward General, Accurate, Long-Horizon, and Efficient Mobile Agent | 多模态多agent架构+链式推理+分层规划，剖析驱动优化适配异构硬件 | 移动agent在泛化性、精度、长程任务、资源效率四维度难以兼顾 | 跨应用、跨设备的通用移动任务自动化 |
| 9 | http://arxiv.org/abs/2509.02544v2 | UI-TARS-2 Technical Report: Advancing GUI Agent with Multi-Turn Reinforcement Learning | 数据飞轮+稳定多轮RL+混合GUI环境+统一沙盒，端到端训练提升GUI agent性能 | 原生agent模型面临数据扩展、多轮RL稳定、环境交互、平台适配等挑战 | 跨平台GUI任务的自主交互与长程信息检索 |
| 10 | http://arxiv.org/abs/2509.02761v4 | Plan Verification for LLM-Based Embodied Task Completion Agents | Judge-Planner双LLM迭代验证框架，自然语言提示泛化纠正空间规划中的多类错误 | LLM具身任务计划含噪声动作、冗余导航、逻辑错误，降低策略质量 | 提升具身AI训练数据质量与空间规划策略的时空一致性 |
| 11 | http://arxiv.org/abs/2509.06644v4 | T-araVLN: Translator for Agricultural Robotic Agents on Vision-and-Language Navigation | 指令翻译模块细化自然语言指令，提升农业机器人导航 | 解决农业机器人在复杂指令下导航误解与误差问题 | 农业机器人与视觉语言导航 |
| 12 | http://arxiv.org/abs/2510.15895v1 | BREATH: A Bio-Radar Embodied Agent for Tonal and Human-Aware Diffusion Music Generation | 整合生理传感与 LLM 推理，生成个性化音乐 | 解决音乐生成缺乏生理信号与文化基调适配问题 | 音乐生成与人机交互 |
| 13 | http://arxiv.org/abs/2509.10317v1 | Robot guide with multi-agent control and automatic scenario generation with LLM | 混合控制架构，LLM 生成行为场景，多 agent 管理资源 | 解决传统导游机器人行为配置手动且缺乏自然性问题 | anthropomorphic 导游机器人 |
| 14 | http://arxiv.org/abs/2509.13347v1 | OpenHA: A Series of Open-Source Hierarchical Agentic Models in Minecraft | 提出 Chain of Action 框架，统一高层规划与底层控制 | 解决开放环境中动作空间选择与通用智能体构建难题 | Minecraft 开放世界任务 |
| 15 | http://arxiv.org/abs/2509.13352v2 | Agentic UAVs: LLM-Driven Autonomy with Integrated Tool-Calling and Cognitive Reasoning | 五层架构，LLM 驱动推理与工具调用，提升 UAV 自主性 | 解决 UAV 依赖规则控制及缺乏上下文推理能力问题 | 国防与灾难响应无人机 |
| 16 | http://arxiv.org/abs/2509.12507v1 | Learning to Generate Pointing Gestures in Situated Embodied Conversational Agents | 结合模仿与强化学习生成物理有效且自然的指向手势 | 解决具身代理在非语言沟通中手势自然性与指代准确性问题 | 具身对话机器人 |
| 17 | http://arxiv.org/abs/2509.13380v2 | ASTREA: Introducing Agentic Intelligence for Orbital Thermal Autonomy | 首次在飞行遗产硬件上执行代理系统，结合 LLM 与 RL 控制器 | 解决空间受限硬件下自主航天器操作的热控制 autonomy 问题 | 航天器自主操作 |
| 18 | http://arxiv.org/abs/2509.13386v2 | VEGA: Electric Vehicle Navigation Agent via Physics-Informed Neural Operator and Proximal Policy Optimization | 整合物理信息参数估计与 RL 路径规划，实现能量感知路由 | 解决电动车在跨城路线中充电停止与路线联合优化难题 | 电动车导航系统 |
| 19 | http://arxiv.org/abs/2509.15491v1 | Explainable AI-Enhanced Supervisory Control for Robust Multi-Agent Robotic Systems | 结合定时自动机监督及可解释预测器，控制多智能体机器人。 | 解决安全关键多智能体机器人系统在不确定动态下的控制问题。 | 航天及水下多智能体机器人 |
| 20 | http://arxiv.org/abs/2509.16176v1 | Agentic Aerial Cinematography: From Dialogue Cues to Cinematic Trajectories | 利用大模型将自然语言提示直接转化为可执行无人机视频拍摄轨迹。 | 解决无人机拍摄工作流依赖人工选择 waypoints 且效率低的问题。 | 无人机航拍/影视制作 |
| 21 | http://arxiv.org/abs/2509.16482v2 | Robot Conga: A Leader-Follower Walking Approach to Sequential Path Following in Multi-Agent Systems | 提出基于领导者空间位移而非时间的领导者 - 跟随者控制策略。 | 解决传统编队控制依赖时间参数化轨迹导致同步问题与行为僵化的问题。 | 多机器人系统/路径跟随 |
| 22 | http://arxiv.org/abs/2509.22698v1 | Advancing Audio-Visual Navigation Through Multi-Agent Collaboration in 3D Environments | 提出 MASTAVN 框架，整合跨代理通信与联合音视频融合机制。 | 解决动态 3D 环境中单代理音视频导航局限性及时间敏感协调问题。 | 3D 环境导航/紧急响应 |
| 23 | http://arxiv.org/abs/2509.18597v2 | Growing with Your Embodied Agent: A Human-in-the-Loop Lifelong Code Generation Framework for Long-Horizon Manipulation Skills | 人机回路框架将修正编码为可复用技能支持长期任务 | 解决 LLM 代码生成噪声大与长视界任务失败问题 | 机器人长视界操作技能 |
| 24 | http://arxiv.org/abs/2509.19571v1 | Agentic Scene Policies: Unifying Space, Semantics, and Affordances for Robot Action | 利用场景表示查询能力实现语言条件机器人策略 | 解决端到端模型面对复杂指令与新场景 struggle 问题 | 机器人开放词汇操作 |
| 25 | http://arxiv.org/abs/2509.20705v1 | Building Information Models to Robot-Ready Site Digital Twins (BIM2RDT): An Agentic AI Safety-First Framework | 整合 BIM、IoT 与机器人数据，利用 LLM 推理优化点云配准与数字孪生更新。 | 解决静态 BIM 模型无法动态反映实时工地条件及安全优先执行的问题。 | 建筑施工数字孪生与机器人 |
| 26 | http://arxiv.org/abs/2509.22937v2 | DBF-MA: A Differential Bayesian Filtering Planner for Multi-Agent Autonomous Racing Overtakes | 基于微分贝叶斯滤波框架，合成无碰撞超车轨迹。 | 解决自动驾驶赛车在复杂赛道上的动态避障超车难题。 | 自主赛车智能体 |
| 27 | http://arxiv.org/abs/2509.23155v2 | LAGEA: Language Guided Embodied Agents for Robotic Manipulation | 将语言反馈转化为时序引导信号，调制强化学习奖励。 | 解决具身智能体缺乏 principled 方式从错误中学习问题。 | 机器人操作任务 |
| 28 | http://arxiv.org/abs/2509.25261v1 | Heterogeneous Multi-agent Collaboration in UAV-assisted Mobile Crowdsensing Networks | 设计混合演员网络 MADRL 算法，优化 UAV 轨迹与资源。 | 解决移动群智感知中频谱稀缺与设备异构协调难题。 | 无人机辅助网络 |
| 29 | http://arxiv.org/abs/2509.23655v1 | Focusing on What Matters: Object-Agent-centric Tokenization for Vision Language Action models | 提出对象 - 智能体中心 tokenization，大幅减少视觉 token。 | 解决 VLA 模型适配机器人领域时计算成本过高问题。 | 机器人操作学习 |
| 30 | http://arxiv.org/abs/2509.24524v1 | PhysiAgent: An Embodied Agent Framework in Physical World | 提出具身智能体框架，整合监控、记忆与自反思机制协调 VLM 与 VLA | 解决 VLA 模型泛化有限及 VLM 与 VLA 协作僵硬问题 | 物理世界机器人任务 |
| 31 | http://arxiv.org/abs/2509.26536v2 | OceanGym: A Benchmark Environment for Underwater Embodied Agents | 首个综合水下具身智能体基准环境 | 水下环境感知和决策挑战极大 | 水下自主车辆 |
| 32 | http://arxiv.org/abs/2510.00259v1 | A Hierarchical Agentic Framework for Autonomous Drone-Based Visual Inspection | 用于自主无人机控制的分层智能体框架 | 物理资产现实环境应用尚未探索 | 工业视觉检查 |

[返回目录](#目录)

<a id="cat-08"></a>

## Agent学习与自进化

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2509.18119v2 | MobileRL: Online Agentic Reinforcement Learning for Mobile GUI Agents | 难度自适应ADAGRPO算法，含困难自适应正回放和失败课程过滤 | 移动GUI Agent的RL训练因任务难度重尾分布和环境采样低效而困难 | 移动环境中的通用GUI Agent |
| 2 | http://arxiv.org/abs/2509.08755v1 | AgentGym-RL: Training LLM Agents for Long-Horizon Decision Making through Multi-Turn Reinforcement Learning | ScalingInter-RL训练方法，早期强调利用，逐渐转向探索以鼓励多样化策略 | 缺乏统一交互式RL框架从零开始训练Agent解决复杂真实任务 | 长视野决策的LLM Agent训练 |
| 3 | http://arxiv.org/abs/2509.09265v1 | Harnessing Uncertainty: Entropy-Modulated Policy Gradients for Long-Horizon LLM Agents | EMPG框架基于逐步不确定性和最终任务结果重新校准学习信号 | 长视野任务中稀疏结果奖励难以将信用分配给中间步骤 | 长视野LLM Agent的策略梯度学习 |
| 4 | http://arxiv.org/abs/2509.03479v1 | Design and Optimization of Reinforcement Learning-Based Agents in Text-Based Games | 结合世界模型与策略梯度强化学习优化文本游戏代理 | 提升文本游戏代理的状态理解与策略最优性 | 文本冒险游戏 AI |
| 5 | http://arxiv.org/abs/2509.01684v1 | Reinforcement Learning for Machine Learning Engineering Agents | 时长感知梯度更新+环境插桩提供部分奖励，小模型通过RL超越大模型提示 | 现有agent依赖提示无法从经验中学习，奖励信号稀疏限制策略优化 | 自动化机器学习工程任务的agent持续改进 |
| 6 | http://arxiv.org/abs/2509.06283v2 | SFR-DeepResearch: Towards Effective Reinforcement Learning for Autonomously Reasoning Single Agents | 提出纯合成数据 RL 配方，增强自主单代理推理与工具使用能力 | 解决深度研究中自主单代理推理能力不足的问题 | 自主研究与信息检索代理 |
| 7 | http://arxiv.org/abs/2509.06775v3 | Agentic DDQN-Based Scheduling for Licensed and Unlicensed Band Allocation in Sidelink Networks | 感知多维上下文的 DDQN 调度器，对齐目标导向调度 | 解决受限带宽下网络阻塞高且缺乏上下文驱动决策问题 | 通信网络资源调度 |
| 8 | http://arxiv.org/abs/2509.14257v2 | From Correction to Mastery: Reinforced Distillation of Large Language Model Agents | SCoRe 框架，学生生成轨迹教师修正最早错误，结合 RL | 解决蒸馏过程中师生推理差距导致的累积错误问题 | 大模型智能体蒸馏与优化 |
| 9 | http://arxiv.org/abs/2509.10704v1 | Maestro: Self-Improving Text-to-Image Generation via Agent Orchestration | 自我批判与进化机制，多模态 LLM 作为 critic 与 judge | 解决文生图依赖人工迭代提示工程的问题 | 文本到图像生成 |
| 10 | http://arxiv.org/abs/2509.11361v3 | MAPGD: Multi-Agent Prompt Gradient Descent for Collaborative Prompt Optimization | 多 agent 提示梯度下降，协作优化提示词 | 解决单轨迹提示优化适应性差及计算开销大问题 | 大模型提示工程优化 |
| 11 | http://arxiv.org/abs/2509.11880v1 | Learning Representations in Video Game Agents with Supervised Contrastive Imitation Learning | 将监督对比学习应用于模仿学习，优化状态表示 | 解决视频游戏代理中动作相关因素捕捉不足导致泛化差问题 | 视频游戏智能体 |
| 12 | http://arxiv.org/abs/2509.12434v3 | Building Coding Agents via Entropy-Enhanced Multi-Turn Preference Optimization | 提出熵增强框架，适配多轮工具辅助设置的偏好优化 | 解决标准对齐方法降低输出多样性限制测试时扩展效果问题 | 代码生成智能体 |
| 13 | http://arxiv.org/abs/2509.13305v1 | WebSailor-V2: Bridging the Chasm to Proprietary Agents via Synthetic Data and Scalable Reinforcement Learning | 生成高不确定性任务，采用高效代理 RL 训练算法 | 解决开源代理在复杂信息寻求任务中缺乏系统性降低不确定性能力问题 | 信息寻求代理 |
| 14 | http://arxiv.org/abs/2509.13310v1 | Scaling Agents via Continual Pre-training | 提出代理持续预训练，构建强大的代理基础模型 | 解决后训练方法因缺乏稳健代理基础模型导致优化张力问题 | 通用代理智能 |
| 15 | http://arxiv.org/abs/2509.13311v1 | Towards General Agentic Intelligence via Environment Scaling | 设计可扩展框架自动构建异构环境，扩大函数调用场景空间 | 解决代理函数调用能力广度受限于训练环境多样性问题 | 通用代理智能 |
| 16 | http://arxiv.org/abs/2509.18158v1 | ZERA: Zero-init Instruction Evolving Refinement Agent -- From Zero Instructions to Structured Prompts via Principle-based Optimization | 联合优化系统与用户提示，基于原则化 refinement 快速收敛 | 解决现有自动提示优化方法依赖非结构化反馈且迭代成本高问题 | 提示优化与构建 |
| 17 | http://arxiv.org/abs/2509.14172v2 | TGPO: Tree-Guided Preference Optimization for Robust Web Agent Reinforcement Learning | 提出树引导偏好优化，合并语义相同状态消除标签冲突。 | 解决 Web 智能体强化学习中奖励稀疏及标注成本高的问题。 | Web 自动化交互智能体 |
| 18 | http://arxiv.org/abs/2509.15172v3 | Self-Improvement of Language Models by Post-Training on Multi-Agent Debate | 利用多智能体辩论信号后训练模型，提升自我一致性。 | 解决模型自我改进缺乏强于自身产生的训练信号问题。 | 语言模型自我进化 |
| 19 | http://arxiv.org/abs/2509.15738v1 | GUI-ReWalk: Massive Data Generation for GUI Agent via Stochastic Exploration and Intent-Aware Reasoning | 结合随机探索与意图推理，生成多样化且符合人类意图的 GUI 轨迹数据。 | 解决 GUI 智能体训练缺乏可扩展高质量轨迹数据的问题。 | GUI 智能体训练/数据生成 |
| 20 | http://arxiv.org/abs/2509.18847v2 | Failure Makes the Agent Stronger: Enhancing Accuracy through Structured Reflection for Reliable Tool Interactions | 结构化反思将错误到修复路径转化为可训练动作 | 解决工具增强 LLM 多轮交互中重复错误与脆弱性问题 | 工具调用与错误恢复 |
| 21 | http://arxiv.org/abs/2509.21823v1 | ProRe: A Proactive Reward System for GUI Agents via Reasoner-Actor Collaboration | 通用推理器+领域评估器Agent协作，主动探测状态分配奖励 | GUI Agent奖励缺乏ground-truth，静态LLM-as-Judge准确率有限 | GUI Agent训练、奖励建模 |
| 22 | http://arxiv.org/abs/2509.21891v1 | AgentPack: A Dataset of Code Changes, Co-Authored by Agents and Humans | 1.3M Agent-人类共同创作代码编辑数据集，LLM生成详细commit消息 | 现有代码编辑数据噪声大，commit消息简略混杂无关编辑 | 代码编辑模型微调、软件工程Agent |
| 23 | http://arxiv.org/abs/2510.03253v2 | Solving the Granularity Mismatch: Hierarchical Preference Learning for Long-Horizon LLM Agents | 分层偏好学习HPL，轨迹/步骤/组三级粒度+双层课程调度 | 轨迹级DPO太粗，步骤级DPO太短视，粒度不匹配 | 长horizon复杂任务LLM Agent对齐 |
| 24 | http://arxiv.org/abs/2509.22502v2 | InfiAgent: Self-Evolving Pyramid Agent Framework for Infinite Scenarios | 金字塔DAG多Agent框架，Agent即工具自动分解+自进化机制 | 开发Agent需精心设计工作流/提示/迭代调优，限制可扩展性 | 无限场景通用Agent、AI研究助手 |
| 25 | http://arxiv.org/abs/2509.20562v1 | SAMULE: Self-Learning Agents Enhanced by Multi-level Reflection | 基于多级反思合成训练回顾模型，支持微观、中观及宏观层面的错误修正。 | 解决 LLM 代理因错误分析不足难以生成有意义反思的问题。 | 复杂任务自我改进代理 |
| 26 | http://arxiv.org/abs/2509.21126v1 | Teaching RL Agents to Act Better: VLM as Action Advisor for Online Reinforcement Learning | 利用 VLM 领域知识提供动作建议而非设计启发式奖励，保证最优性收敛。 | 解决在线 RL 样本效率低、稀疏奖励任务需大量交互步骤的问题。 | 在线强化学习代理 |
| 27 | http://arxiv.org/abs/2509.21129v1 | EvoMail: Self-Evolving Cognitive Agents for Adaptive Spam and Phishing Email Defense | 构建统一异构图，红蓝队对抗自进化循环，压缩经验到记忆模块复用。 | 解决传统垃圾邮件检测难以整合异质信号及持续适应新攻击策略的问题。 | 垃圾邮件与网络钓鱼防御 |
| 28 | http://arxiv.org/abs/2509.21224v1 | What Do LLM Agents Do When Left Alone? Evidence of Spontaneous Meta-Cognitive Patterns | 部署持续推理行动框架，发现代理自发组织成三种 distinct 行为模式。 | 解决缺乏对外部强加任务缺失时 LLM 代理行为系统文档的问题。 | 自主 LLM 代理行为 |
| 29 | http://arxiv.org/abs/2509.21240v3 | Tree Search for LLM Agent Reinforcement Learning | 提出 Tree-GRPO，基于树搜索分组代理 RL，共享前缀增加 rollout 数量。 | 解决长程多转代理任务中仅靠结果奖励导致监督稀疏的问题。 | LLM 代理强化学习 |
| 30 | http://arxiv.org/abs/2509.22576v2 | EPO: Entropy-regularized Policy Optimization for LLM Agents Reinforcement Learning | 提出熵正则化策略优化框架，打破探索 - 利用级联失败。 | 解决多轮稀疏奖励环境下 LLM 智能体训练崩溃问题。 | LLM 智能体强化学习训练 |
| 31 | http://arxiv.org/abs/2509.22601v4 | Learn the Ropes, Then Trust the Wins: Self-imitation with Progressive Exploration for Agentic Reinforcement Learning | 结合自我模仿与渐进探索，平衡智能体探索利用 trade-off。 | 解决长程稀疏奖励任务中 RL 不稳定及熵崩溃问题。 | 长程任务 LLM 智能体 |
| 32 | http://arxiv.org/abs/2509.23652v2 | ReWatch-R1: Boosting Complex Video Reasoning in Large Vision-Language Models through Agentic Data Synthesis | 多智能体 ReAct 框架合成视频 grounding 推理数据。 | 解决复杂视频推理缺乏高质量多跳 CoT 数据瓶颈。 | 大型视觉语言模型 |
| 33 | http://arxiv.org/abs/2509.24726v1 | Socratic-Zero : Bootstrapping Reasoning via Data-Free Agent Co-evolution | 提出无数据智能体协同进化框架，通过师生生成器闭环生成高质量数据 | 解决推理任务依赖大规模高质量标注数据难以扩展的问题 | 数学推理任务 |
| 34 | http://arxiv.org/abs/2509.25047v1 | Scaling Synthetic Task Generation for Agents via Exploration | 通过探索交互式环境合成可验证任务的流水线 | 缺乏高质量下游智能体任务数据集 | 多模态智能体后训练 |
| 35 | http://arxiv.org/abs/2509.25052v1 | "Cogito, Ergo Ludo: An Agent that Learns to Play by Reasoning and Planning" | 基于 LLM 显式推理和规划的学习架构 | 深度强化学习依赖大量经验且知识不透明 | 网格世界游戏与策略学习 |
| 36 | http://arxiv.org/abs/2509.25598v1 | Hybrid Reward Normalization for Process-supervised Non-verifiable Agentic Tasks | 统一原则性步骤评估与结果验证的 RL 方法 | 非可验证过程中步骤标签标注困难 | 长轨迹复杂智能体任务 |
| 37 | http://arxiv.org/abs/2509.25779v2 | Planner-R1: Reward Shaping Enables Efficient Agentic RL with Smaller LLMs | 奖励塑造使小模型在智能体 RL 中达到竞争性能 | 大模型计算成本高且稀疏奖励下学习难 | 智能体强化学习训练 |

[返回目录](#目录)

<a id="cat-09"></a>

## Agent评测与基准

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2509.09734v1 | MCP-AgentBench: Evaluating Real-World Language Agent Performance with MCP-Mediated Tools | 建立含33个服务器188个工具的MCP测试床，600个系统化设计查询 | 现有基准无法捕捉MCP范式下Agent的真实操作价值 | MCP中介工具交互的语言Agent评估 |
| 2 | http://arxiv.org/abs/2509.08809v1 | Evaluating LLMs Without Oracle Feedback: Agentic Annotation Evaluation Through Unsupervised Consistency Signals | 提出CAI Ratio无监督评估指标，学生模型与噪声教师协作评估标注质量 | 动态无监督环境中缺乏oracle反馈时评估LLM标注质量困难 | 无oracle反馈的LLM标注质量评估 |
| 3 | http://arxiv.org/abs/2509.09321v1 | Towards Adaptive ML Benchmarks: Web-Agent-Driven Construction, Domain Expansion, and Metric Optimization | 浏览器自动化和LLM任务获取系统自动收集结构化ML挑战，排行榜驱动难度建模 | 现有基准在任务覆盖、领域多样性、难度建模和评估严谨性方面有限 | 端到端ML任务的LLM Agent评估 |
| 4 | http://arxiv.org/abs/2509.09853v2 | SWE-Effi: Re-Evaluating Software AI Agent System Effectiveness Under Resource Constraints | 定义有效性为结果准确性与资源消耗的平衡，重新评估SWE-bench上的AI系统 | 现有排行榜仅关注解决方案准确性，忽略资源受限世界的有效性 | 软件工程AI Agent系统的有效性评估 |
| 5 | http://arxiv.org/abs/2509.03940v1 | VoxRole: A Comprehensive Benchmark for Evaluating Speech-Based Role-Playing Agents | 首创语音角色扮演代理综合基准，包含多维角色档案 | 填补语音领域缺乏标准化评估基准及角色一致性量化空白 | 语音对话模型评估 |
| 6 | http://arxiv.org/abs/2509.05396v2 | Talk Isn't Always Cheap: Understanding Failure Modes in Multi-Agent Debate | 探索模型能力多样性对多智能体辩论动态的影响 | 揭示辩论可能导致准确性下降及盲目同意错误推理问题 | 多智能体辩论系统 |
| 7 | http://arxiv.org/abs/2509.01052v2 | FlashAdventure: A Benchmark for GUI Agents Solving Full Story Arcs in Diverse Adventure Games | 提出34款Flash游戏基准，引入CUA-as-a-Judge自动评估器与COAST长时记忆框架 | 现有游戏基准缺乏多样性，难以评估agent完成完整叙事的能力 | GUI agent在游戏场景的长程任务完成能力评估 |
| 8 | http://arxiv.org/abs/2509.02473v1 | FDABench: A Benchmark for Data Agents on Analytical Queries over Heterogeneous Data | 2007+异构数据任务基准+agent - 专家协作构建框架+跨系统泛化能力评估 | 缺乏全面评估数据agent多源分析能力的基准，测试用例构建成本高 | 数据智能体在异构数据分析场景的能力评估与系统对比 |
| 9 | http://arxiv.org/abs/2509.06235v1 | PillagerBench: Benchmarking LLM-Based Agents in Competitive Minecraft Team Environments | 提供 Minecraft 团队对抗环境基准，评估多智能体战略推理 | 解决竞争性多智能体环境缺乏公平可复现评估的问题 | 游戏 AI 与竞争性多智能体系统 |
| 10 | http://arxiv.org/abs/2509.06341v1 | Evaluating Multi-Turn Bargain Skills in LLM-Based Seller Agent | 构建大规模电商议价基准，基于心智理论评估意图追踪 | 解决卖家代理在长程谈判中累积意图追踪能力评估缺失 | 电子商务与谈判代理 |
| 11 | http://arxiv.org/abs/2509.06477v1 | MAS-Bench: A Unified Benchmark for Shortcut-Augmented Hybrid Mobile GUI Agents | 评估 GUI-快捷方式混合代理，测试自主生成快捷方式能力 | 解决混合 GUI 代理缺乏系统基准评估的问题 | 移动 GUI 自动化代理 |
| 12 | http://arxiv.org/abs/2509.07389v1 | Talking with Oompa Loompas: A novel framework for evaluating linguistic acquisition of LLM agents | 评估 LLM 代理通过模式识别与交互反馈获取新语言能力 | 解决现有评估未测试代理通过互动反馈习得语言的问题 | 语言习得与代理评估 |
| 13 | http://arxiv.org/abs/2509.19319v2 | FHIR-AgentBench: Benchmarking LLM Agents for Realistic Interoperable EHR Question Answering | 构建基于 FHIR 标准的临床问答基准，评估 Agent 互操作性 | 缺乏评估 LLM 处理互操作性临床数据能力的基准 | 医疗电子健康记录系统 |
| 14 | http://arxiv.org/abs/2509.10769v2 | AgentArch: A Comprehensive Benchmark to Evaluate Agent Architectures in Enterprise | 企业级基准评估 18 种代理配置，揭示模型特定偏好 | 缺乏对企业复杂任务中代理架构交互的实证理解 | 企业级代理系统 |
| 15 | http://arxiv.org/abs/2509.12718v2 | EvoEmpirBench: Dynamic Spatial Reasoning with Agent-ExpVer | 引入动态空间基准，评估局部感知与动态变化下的推理能力 | 解决现有基准忽略部分可观察性与动态变化下长程推理挑战问题 | 空间推理能力评估 |
| 16 | http://arxiv.org/abs/2509.12927v1 | HLSMAC: A New StarCraft Multi-Agent Challenge for High-Level Strategic Decision-Making | 设计基于三十六计的新基准，评估高层战略决策能力 | 解决现有 StarCraft 基准仅关注微观管理限制战略智能评估问题 | 多代理战略决策评估 |
| 17 | http://arxiv.org/abs/2509.14279v1 | Towards Robust Agentic CUDA Kernel Benchmarking, Verification, and Optimization | 引入 robust-kbench 基准，自动化 CUDA 内核发现与优化 | 解决现有内核生成基准存在漏洞且测试条件多样性不足问题 | CUDA 内核性能评估 |
| 18 | http://arxiv.org/abs/2509.13399v3 | EdiVal-Agent: An Object-Centric Framework for Automated, Fine-Grained Evaluation of Multi-Turn Editing | 提出对象中心评估框架，自动评估多轮指令编辑质量 | 解决现有评估协议依赖参考图像或零 shot VLM 导致不精确问题 | 图像编辑模型评估 |
| 19 | http://arxiv.org/abs/2509.14382v1 | Detecting Pipeline Failures through Fine-Grained Analysis of Web Agents | 提出模块化评估框架，分解智能体流水线进行细粒度错误分析。 | 解决现有 Web 智能体评估忽略中间错误及缺乏诊断工具问题。 | Web 智能体评估与改进 |
| 20 | http://arxiv.org/abs/2509.14477v1 | Ticket-Bench: A Kickoff for Multilingual and Regionalized Agent Evaluation | 构建涵盖六种语言及区域化场景的票务购买智能体基准。 | 解决现有智能体评估忽视文化语言多样性及真实性的问题。 | 多语言任务导向智能体 |
| 21 | http://arxiv.org/abs/2509.14647v1 | AgentCompass: Towards Reliable Evaluation of Agentic Workflows in Production | 模拟专家调试推理过程，监控生产环境智能体工作流。 | 解决现有评估方法无法捕捉生产环境错误及 emergent 行为问题。 | 生产环境智能体工作流监控 |
| 22 | http://arxiv.org/abs/2509.15160v1 | An Evaluation-Centric Paradigm for Scientific Visualization Agents | 探讨科学可视化智能体所需评估类型及基准建设挑战。 | 解决科学可视化智能体缺乏综合大规模基准评估的问题。 | 科学可视化智能体 |
| 23 | http://arxiv.org/abs/2509.15366v1 | Diagnostics of cognitive failures in multi-agent expert systems using dynamic evaluation protocols and subsequent mutation of the processing context | 集成专家标注及行为突变数据集，诊断多智能体认知失败。 | 解决经典评估方法不足以诊断随机多步决策智能体性能问题。 | 多智能体专家系统 |
| 24 | http://arxiv.org/abs/2509.16330v1 | Generalizability of Large Language Model-Based Agents: A Comprehensive Survey | 首次全面综述 Agent 通用性，分类改进方法并指出标准化评估挑战。 | 解决 Agent 通用性概念未定义且缺乏系统测量与改进方法的问题。 | Agent 通用性评估/综述 |
| 25 | http://arxiv.org/abs/2509.16941v2 | SWE-Bench Pro: Can AI Agents Solve Long-Horizon Software Engineering Tasks? | 构建包含 1865 个企业级问题的基准，涵盖长周期任务与多文件修改。 | 解决现有基准无法捕捉真实软件开发复杂性与多样性及污染问题。 | 软件工程/Agent 基准 |
| 26 | http://arxiv.org/abs/2509.17158v2 | ARE: Scaling Up Agent Environments and Evaluations | 提供 Meta Agents Research Environments 平台，构建 Gaia2 基准测试通用能力。 | 解决模型开发与真实部署间差距及现有基准无法 surfaced 异步失败模式问题。 | Agent 环境/通用能力评估 |
| 27 | http://arxiv.org/abs/2509.17191v2 | VaseVQA: Multimodal Agent and Benchmark for Ancient Greek Pottery | 构建专家定义类别的大规模基准，结合 SFT 与强化学习提升领域推理。 | 解决当前 MLLM 因缺乏领域数据难以理解文化遗产 artifacts 的问题。 | 文化遗产/视觉问答 |
| 28 | http://arxiv.org/abs/2509.17628v1 | MSCoRe: A Benchmark for Multi-Stage Collaborative Reasoning in LLM Agents | 构建包含 12 万实例的多阶段协作推理基准 | 填补复杂多阶段场景下 Agent 推理能力评估空白 | 多阶段推理 LLM 智能体 |
| 29 | http://arxiv.org/abs/2509.19136v2 | On the Soundness and Consistency of LLM Agents for Executing Test Cases Written in Natural Language | 提出护栏机制与专用智能体执行自然语言测试用例 | 解决 NL 测试用例执行不健全与结果不一致问题 | 图形界面自动化测试 |
| 30 | http://arxiv.org/abs/2509.19185v2 | An Empirical Study of Testing Practices in Open Source AI Agent Frameworks and Agentic Applications | 大规模实证研究开源 Agent 框架测试实践与模式 | 揭示基础模型非确定性带来的测试盲区与挑战 | 开源 Agent 框架开发 |
| 31 | http://arxiv.org/abs/2509.19843v1 | PersONAL: Towards a Comprehensive Benchmark for Personalized Embodied Agents | 综合基准研究具身 AI 中个性化物体导航与定位 | 解决现实人类中心场景中建模个体偏好行为难问题 | 个性化具身智能体 |
| 32 | http://arxiv.org/abs/2509.21766v1 | UltraHorizon: Benchmarking Agent Capabilities in Ultra Long-Horizon Scenarios | 超长horizon基准，轨迹平均200k+ tokens、400+工具调用 | 现有基准缺乏长horizon、部分可观察场景评估 | 复杂现实任务Agent能力评估 |
| 33 | http://arxiv.org/abs/2509.21998v2 | GSM-Agent: Understanding Agentic Reasoning Using Controllable Environments | Agent推理图概念，工具调用映射到文档嵌入节点构建推理路径 | 现有基准混合Agent推理与数学推理/专家知识，难以解耦 | Agent推理能力理解、工具使用研究 |
| 34 | http://arxiv.org/abs/2509.22356v1 | RoboView-Bias: Benchmarking Visual Bias in Embodied Agents for Robotic Manipulation | 首个系统量化机器人操作中视觉偏差的基准，2127任务实例 | 现有基准强调泛化鲁棒性，缺乏视觉偏差系统量化 | 具身Agent安全可靠性、机器人操作 |
| 35 | http://arxiv.org/abs/2509.22391v1 | Do LLM Agents Know How to Ground, Recover, and Assess? A Benchmark for Epistemic Competence in Information-Seeking Agents | SeekBench首个评估LLM搜索Agent认识论能力的基准，步骤级分析 | 现有评估仅关注最终答案准确率，忽视Agent如何推理和行动 | 信息寻求Agent、搜索Agent能力评估 |
| 36 | http://arxiv.org/abs/2509.22504v2 | Estimating the Empowerment of Language Model Agents | EELMA算法基于信息论empowerment（行动与未来状态互信息）评估Agent | 传统基准中心评估设计成本高，需人类设计有效任务 | LLM Agent能力评估、开放-ended场景监控 |
| 37 | http://arxiv.org/abs/2509.25229v1 | Blueprint-Bench: Comparing spatial intelligence of LLMs, agents and image models | 通过公寓照片转 2D 平面图任务，评估 AI 模型的空间推理与重建能力。 | 解决当前 AI 模型空间智能缺乏数值化评估框架的问题。 | 空间智能评估 |
| 38 | http://arxiv.org/abs/2509.20998v1 | CORE: Full-Path Evaluation of LLM Agents Beyond Final State | 基于 DFA 编码任务为有效工具使用路径集，提出五指标评估代理行为。 | 解决现有基准仅评估最终状态，忽略安全性、效率及中间正确性的问题。 | LLM 代理全路径评估 |
| 39 | http://arxiv.org/abs/2509.21143v2 | Automotive-ENV: Benchmarking Multimodal Agents in Vehicle Interface Systems | 引入首个高保真车载 GUI 基准，定义 185 个参数化任务及多模态观察。 | 解决车内 GUI 交互缺乏专用基准及安全感知任务评估标准的问题。 | 车载多模态代理 |
| 40 | http://arxiv.org/abs/2509.21501v1 | LLM Agent Meets Agentic AI: Can LLM Agents Simulate Customers to Evaluate Agentic-AI-based Shopping Assistants? | 创建数字孪生重复购物任务，量化 LLM 代理镜像人类多转交互的程度。 | 解决 agentic AI 系统快速演进超过传统人工评估速度的问题。 | 购物助手代理评估 |
| 41 | http://arxiv.org/abs/2509.23006v1 | Creative Adversarial Testing (CAT): A Novel Framework for Evaluating Goal-Oriented Agentic AI Systems | 提出创意对抗测试框架，分析任务与目标对齐关系。 | 填补智能体系统目标 - 任务对齐评估的空白。 | 目标导向型智能体系统 |
| 42 | http://arxiv.org/abs/2509.25248v1 | BuildBench: Benchmarking LLM Agents on Compiling Real-World Open-Source Software | 构建多样化开源软件编译基准，评估智能体工程能力。 | 解决现有基准低估开源软件编译现实挑战的问题。 | 软件编译智能体 |
| 43 | http://arxiv.org/abs/2509.23415v2 | From Conversation to Query Execution: Benchmarking User and Tool Interactions for EHR Database Agents | 构建 EHR 数据库问答基准，评估查询消歧与值匹配能力。 | 解决医疗数据访问中查询模糊与术语不匹配挑战。 | 电子健康记录智能体 |
| 44 | http://arxiv.org/abs/2509.23803v1 | FedAgentBench: Towards Automating Real-world Federated Medical Image Analysis with Server-Client LLM Agents | 提出 FedAgentBench 基准，评估 LLM 智能体在联邦医疗图像分析中的自主协调能力 | 解决现实联邦学习部署中复杂操作挑战需大量人力的问题 | 医疗图像分析/联邦学习 |
| 45 | http://arxiv.org/abs/2510.03285v1 | WAREX: Web Agent Reliability Evaluation on Existing Benchmarks | 引入网络不稳定因素，评估 Web 智能体在真实环境下的可靠性 | 解决现有基准仅在受控环境测试，忽视真实网络不稳定的问题 | Web 自动化智能体 |
| 46 | http://arxiv.org/abs/2509.24091v3 | PerfBench: Can Agents Resolve Real-World Performance Bugs? | 构建 PerfBench 基准，评估智能体修复真实性能 bug 的能力 | 解决现有基准仅关注功能正确性，忽视性能优化问题 | 软件工程/代码修复 |
| 47 | http://arxiv.org/abs/2509.24282v3 | SimuHome: A Temporal- and Environment-Aware Benchmark for Smart Home LLM Agents | 构建高保真智能家居模拟器，支持设备操作对环境变量的时间影响 | 解决现有智能家居基准忽视设备操作时间动态影响的问题 | 智能家居 LLM 智能体 |
| 48 | http://arxiv.org/abs/2509.24922v2 | MASLegalBench: Benchmarking Multi-Agent Systems in Deductive Legal Reasoning | 提出面向 MAS 的法律基准，基于演绎推理方法评估 GDPR 场景 | 解决缺乏考虑 MAS 优势的法律领域评估方法限制潜力问题 | 法律 deductive 推理 |
| 49 | http://arxiv.org/abs/2510.00069v1 | OIG-Bench: A Multi-Agent Annotated Benchmark for Multimodal One-Image Guides Understanding | 提出 One-Image Guide 理解基准，利用多智能体协作辅助人工标注 | 解决多模态模型在 One-Image Guide 人类化理解评估不足问题 | 多模态图文理解 |
| 50 | http://arxiv.org/abs/2509.24958v2 | The Dialogue That Heals: A Comprehensive Evaluation of Doctor Agents' Inquiry Capability | 提出 MAQuE 基准，评估医疗智能体问询能力 | 现有评估忽视医生同理心等关键素质 | 医疗诊断智能体 |
| 51 | http://arxiv.org/abs/2509.25370v1 | Where LLM Agents Fail and How They can Learn From Failures | 提出 AgentErrorTaxonomy 分类及 AgentDebug 调试框架 | 缺乏理解智能体错误的模块化系统框架 | 多步任务智能体调试 |
| 52 | http://arxiv.org/abs/2509.25609v2 | A Framework for Studying AI Agent Behavior: Evidence from Consumer Choice Experiments | 通过操纵选项属性系统探测智能体选择的框架 | 现有评估忽视智能体面对现实决策的选择 | 消费者选择行为研究 |
| 53 | http://arxiv.org/abs/2509.25873v1 | Lita: Light Agent Uncovers the Agentic Coding Capabilities of LLMs | 最小化手动设计的轻量级智能体评估方法 | 复杂工作流掩盖模型真实编码能力 | 代码智能体能力评估 |
| 54 | http://arxiv.org/abs/2509.25944v1 | NuRisk: A Visual Question Answering Dataset for Agent-Level Risk Assessment in Autonomous Driving | 提供基于 BEV 序列图像的智能体级风险标注数据集 | 现有方法缺乏捕捉风险随时间演化的时空推理 | 自动驾驶风险评估 |
| 55 | http://arxiv.org/abs/2509.26490v2 | VitaBench: Benchmarking LLM Agents with Versatile Interactive Tasks in Real-world Applications | 包含 66 种工具的真实世界复杂生活服务模拟环境 | 现有基准无法捕捉处理 extensive 信息的复杂性 | 现实世界应用智能体 |
| 56 | http://arxiv.org/abs/2510.00245v1 | Can AI agents understand spoken conversations about data visualizations in online meetings? | 评估 AI 智能体理解在线会议中数据可视化对话 | 会议支持质量依赖模型理解对话能力 | 在线会议助手 |
| 57 | http://arxiv.org/abs/2510.00332v2 | When Hallucination Costs Millions: Benchmarking AI Agents in High-Stakes Adversarial Financial Markets | 暴露 AI 评估盲点：无法在 adversarial 高风险环境操作 | 现有基准测量 controlled 设置任务完成 | adversarial 金融市场 |

[返回目录](#目录)

<a id="cat-10"></a>

## Agent安全与对齐

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2509.08638v1 | AutoODD: Agentic Audits via Bayesian Red Teaming in Black-Box Models | LLM-Agent作为工具编排器，在低维文本嵌入流形上拟合不确定性感知故障分布 | 高维输入空间下审计专用模型需要大量人力和领域专业知识 | 黑盒专用模型的运行设计域审计 |
| 2 | http://arxiv.org/abs/2509.09207v2 | Shell or Nothing: Real-World Benchmarks and Memory-Activated Agents for Automated Penetration Testing | TermiBench基准含510主机，TermiAgent用定位记忆激活机制缓解长上下文遗忘 | 现有AI渗透测试评估依赖简化CTF设置，性能估计远离真实实践 | 真实世界的自动化渗透测试 |
| 3 | http://arxiv.org/abs/2509.09970v1 | Securing LLM-Generated Embedded Firmware through AI Agent-Driven Validation and Patching | 三阶段方法论结合LLM固件生成与自动化安全验证，专用Agent协作检测修复 | LLM生成嵌入式系统固件常引入安全缺陷且无法满足实时性能约束 | 嵌入式系统的LLM生成固件安全 |
| 4 | http://arxiv.org/abs/2509.03312v2 | AgenTracer: Who Is Inducing Failure in the LLM Agentic Systems? | 首创通过反事实回放自动标注多智能体故障轨迹 | 定位复杂多智能体系统中导致失败的具体代理或步骤 | LLM 多智能体系统调试 |
| 5 | http://arxiv.org/abs/2509.03380v1 | Situating AI Agents in their World: Aspective Agentic AI for Dynamic Partially Observable Information Systems | 引入方面性智能体架构，实现零信息泄露的环境感知 | 解决典型架构中代理间信息泄露及控制不清问题 | 动态部分可观察信息系统 |
| 6 | http://arxiv.org/abs/2509.05379v1 | ThreatGPT: An Agentic AI Framework for Enhancing Public Safety through Threat Modeling | 构建威胁建模智能助手，适配多种安全框架分析威胁 | 降低公共安全系统威胁分析的专业门槛 | 公共安全与基础设施 |
| 7 | http://arxiv.org/abs/2509.04802v2 | Mind the Gap: Evaluating Model- and Agentic-Level Vulnerabilities in LLMs with Action Graphs | 提出基于行动图的代理情境评估框架 AgentSeer | 揭示传统评估忽略的代理级特定漏洞与工具调用风险 | LLM 代理安全评估 |
| 8 | http://arxiv.org/abs/2509.01211v2 | Web Fraud Attacks Against LLM-Driven Multi-Agent Systems | 设计12种基于网页链接结构的欺诈攻击变体，揭示MAS对链接操纵的脆弱性 | LLM多agent系统易被恶意链接诱导，扩大攻击面 | 提升MAS对网络欺诈攻击的防御能力 |
| 9 | http://arxiv.org/abs/2509.01619v1 | Throttling Web Agents Using Reasoning Gates | rebus-based Reasoning Gates框架，通过多跳推理谜题对agent施加可调计算成本 | web agent可能滥用资源或绕过防御，需低成本高效的访问控制机制 | 保护内容提供商免受恶意或错误agent的资源滥用 |
| 10 | http://arxiv.org/abs/2509.05755v5 | Red-Teaming Coding Agents from a Tool-Invocation Perspective: An Empirical Security Assessment | 首次系统性红队测试编码代理工具调用漏洞，发现 ToolLeak | 解决编码代理工具调用引发的远程代码执行风险 | 编程辅助 AI 代理的安全性 |
| 11 | http://arxiv.org/abs/2509.05882v2 | Collaborate, Deliberate, Evaluate: How LLM Alignment Affects Coordinated Multi-Agent Outcomes | 研究不同对齐方法对多轮多方协作中代理行为预测性的影响 | 解决现有对齐技术未考虑长程多党交互动态的问题 | 人机协作与多 AI 系统协调 |
| 12 | http://arxiv.org/abs/2509.06701v1 | Probabilistic Modeling of Latent Agentic Substructures in Deep Neural Networks | 形式化 LLM 中代理对齐现象，证明子代理凝聚为高层实体 | 解决智能体对齐缺乏原则性数学框架的问题 | 大模型对齐与理论研究 |
| 13 | http://arxiv.org/abs/2509.12233v1 | Towards Trustworthy Agentic IoEV: AI Agents for Explainable Cyberthreat Mitigation and State Analytics | 专用代理协作交付自主威胁缓解与可解释决策支持 | 解决 IoEV 生态系统易受攻击且决策过程不透明问题 | 电动汽车物联网与安全 |
| 14 | http://arxiv.org/abs/2509.07131v1 | SoK: Security and Privacy of AI Agents for Blockchain | 首个专注于区块链 AI 驱动系统的安全与隐私知识系统化 | 解决区块链 AI 代理缺乏综合安全隐私survey的问题 | 区块链与 Web3 安全 |
| 15 | http://arxiv.org/abs/2509.10550v2 | Auditable Early Stopping for Agentic Routing: Ledger-Verified Run-Wise Certificates under Local DP | 引入运行级证书耦合节点密钥，保留审计轨迹同时保护隐私 | 解决工具使用代理路由停止缺乏可审计性与隐私保护问题 | 代理路由与隐私保护 |
| 16 | http://arxiv.org/abs/2509.07553v2 | VeriOS: Query-Driven Proactive Human-Agent-GUI Interaction for Trustworthy OS Agents | 查询驱动的人机交互框架，代理在不可信场景主动查询人类 | 解决 OS 代理在现实不可信环境中过度执行的风险 | 操作系统代理与可信交互 |
| 17 | http://arxiv.org/abs/2509.07764v1 | AgentSentinel: An End-to-End and Real-Time Security Defense Framework for Computer-Use Agents | 端到端实时防御框架，拦截敏感操作直至完成安全审计 | 解决计算机使用代理因 LLM 不稳定导致有害操作风险 | 计算机使用代理安全 |
| 18 | http://arxiv.org/abs/2509.10018v2 | GAMA: A General Anonymizing Multi-Agent System for Privacy Preservation Enhanced by Domain Rules and Disproof Mechanism | 划分公私空间，引入领域规则与反证机制增强匿名化 | 解决 MAS 利用公有云 LLM 时的隐私数据泄露风险 | 通用隐私保护问答任务 |
| 19 | http://arxiv.org/abs/2509.10289v1 | We Need a New Ethics for a World of AI Agents | 呼吁建立新伦理框架以应对 AI 代理普及带来的挑战 | 解决人机关系及 Agent 间交互的安全与协调问题 | 社会伦理与政策制定 |
| 20 | http://arxiv.org/abs/2509.10723v1 | Dark Patterns Meet GUI Agents: LLM Agent Susceptibility to Manipulative Interfaces and the Role of Human Oversight | 实证研究 GUI 代理对黑暗模式的易感性及人类监督作用 | 揭示代理易受欺骗界面影响及人机协作新漏洞 | GUI 自动化代理安全 |
| 21 | http://arxiv.org/abs/2510.09615v1 | A Biosecurity Agent for Lifecycle LLM Biosecurity Alignment | 全生命周期生物安全代理，含数据清洗与红队测试 | 解决 LLM 在生物研究中被滥用合成毒性化合物的风险 | 生物医学研究工作流 |
| 22 | http://arxiv.org/abs/2509.11250v2 | Environmental Injection Attacks against GUI Agents in Realistic Dynamic Environments | 提出变色龙攻击框架，针对动态环境优化触发器 | 解决现有 GUI 代理攻击研究缺乏现实动态环境问题 | GUI 代理安全性测试 |
| 23 | http://arxiv.org/abs/2509.13356v2 | CogniAlign: Survivability-Grounded Multi-Agent Moral Reasoning for Safe and Transparent AI | 基于生存力的多 agent 道德推理，学科专家 agent 辩论 | 解决 AI 道德对齐抽象冲突及现有方法不透明问题 | AI 安全与道德对齐 |
| 24 | http://arxiv.org/abs/2509.11431v1 | Securing AI Agents: Implementing Role-Based Access Control for Industrial Applications | 将 RBAC 集成到 AI 代理中，提供安全护栏 | 解决工业场景 AI 代理面临的提示注入等安全威胁 | 工业 AI 代理部署 |
| 25 | http://arxiv.org/abs/2509.11523v1 | VulAgent: Hypothesis-Validation based Multi-Agent Vulnerability Detection | 假设验证范式，多 view 检测 pipeline 减少误报 | 解决项目级漏洞检测中定位与推理复杂上下文难题 | 软件安全漏洞检测 |
| 26 | http://arxiv.org/abs/2509.11939v1 | PrivWeb: Unobtrusive and Content-aware Privacy Protection For Web Agents | 设计可信插件，利用本地 LLM 根据偏好匿名化隐私信息 | 解决 Web 代理自动化交互中用户隐私风险与误解问题 | Web 自动化代理 |
| 27 | http://arxiv.org/abs/2509.12626v2 | DoubleAgents: Interactive Simulations for Alignment in Agentic AI | 嵌入透明度与控制机制，通过模拟让用户校准代理行为 | 解决用户难以将代理系统目标与自身价值观及情境期望对齐问题 | 代理系统对齐与校准 |
| 28 | http://arxiv.org/abs/2509.14284v1 | The Sum Leaks More Than Its Parts: Compositional Privacy Risks and Mitigations in Multi-Agent Collaboration | 研究多代理协作中组合隐私泄露，提出理论与协作防御策略 | 解决多代理系统中看似无害响应组合导致敏感信息恢复问题 | 多代理 LLM 系统隐私 |
| 29 | http://arxiv.org/abs/2509.14285v4 | A Multi-Agent LLM Defense Pipeline Against Prompt Injection Attacks | 采用专用 LLM 代理协调管道，实时检测中和提示注入攻击 | 解决恶意指令嵌入用户输入覆盖系统提示导致 unintended 行为问题 | LLM 部署安全 |
| 30 | http://arxiv.org/abs/2509.13597v1 | Agentic JWT: A Secure Delegation Protocol for Autonomous AI Agents | 引入双方面意图令牌，绑定代理动作与可验证用户意图 | 解决自主代理无监督下发 API 调用导致权限 silently 扩展问题 | 自主 AI 代理安全 |
| 31 | http://arxiv.org/abs/2509.14295v5 | Aegis: Automated Error Generation and Attribution for Multi-Agent Systems | 提出 Aegis 框架，自动化生成多智能体系统错误轨迹并归因。 | 解决多智能体系统错误归因数据稀缺且标注成本高的问题。 | 多智能体系统调试与可靠性提升 |
| 32 | http://arxiv.org/abs/2509.13782v1 | Who is Introducing the Failure? Automatically Attributing Failures of Multi-Agent Systems via Spectrum Analysis | 提出基于频谱分析的多智能体系统故障自动归因方法 FAMAS。 | 解决多智能体系统故障定位困难且依赖人工排查的问题。 | 多智能体系统调试与改进 |
| 33 | http://arxiv.org/abs/2510.09620v1 | Toward a Unified Security Framework for AI Agents: Trust, Risk, and Liability | 提出 TRL 框架，系统关联信任、风险与责任以构建安全体系。 | 解决 AI 智能体应用中信任、风险与责任归属割裂的问题。 | AI 智能体安全治理 |
| 34 | http://arxiv.org/abs/2509.14956v1 | Sentinel Agents for Secure and Trustworthy Agentic AI in Multi-Agent Systems | 提出哨兵智能体网络，集成语义分析及异常检测安全层。 | 解决多智能体系统面临提示注入及协同攻击等安全威胁问题。 | 多智能体系统安全防护 |
| 35 | http://arxiv.org/abs/2509.16275v1 | SecureFixAgent: A Hybrid LLM Agent for Automated Python Static Vulnerability Repair | 集成静态分析与本地 LLM，迭代检测修复验证漏洞。 | 解决静态分析误报高及 LLM 修复缺乏自验证的问题。 | Python 代码安全漏洞修复 |
| 36 | http://arxiv.org/abs/2509.15435v1 | ORCA: Agentic Reasoning For Hallucination and Adversarial Robustness in Vision-Language Models | 通过观察 - 推理 - 批评 - 行动循环，提升 VLM 事实准确性。 | 解决视觉语言模型内在幻觉及外部对抗攻击脆弱性问题。 | 视觉语言模型鲁棒性 |
| 37 | http://arxiv.org/abs/2509.16394v1 | Evaluating Behavioral Alignment in Conflict Dialogue: A Multi-Dimensional Comparison of LLM Agents and Humans | 评估人格提示 LLM 在对抗性 dispute 解决中与人类行为的对齐程度。 | 解决 LLM 在情感与策略复杂情境下镜像人类行为能力未被充分探索的问题。 | 对话建模/冲突解决 |
| 38 | http://arxiv.org/abs/2509.16494v2 | Can an Individual Manipulate the Collective Decisions of Multi-Agents? | 提出 M-Spoiler 框架，模拟代理交互生成对抗样本误导集体决策。 | 解决攻击者仅知单个代理即可误导多智能体系统集体决策的安全风险。 | 多智能体系统安全/对抗攻击 |
| 39 | http://arxiv.org/abs/2509.16645v1 | ADVEDM:Fine-grained Adversarial Attack against VLM-based Embodied Agents | 提出细粒度对抗攻击框架，仅修改关键对象感知保留其余语义。 | 解决现有攻击破坏语义导致推理中断、无法影响物理世界交互的问题。 | 具身智能体安全/对抗攻击 |
| 40 | http://arxiv.org/abs/2509.16950v2 | Temporal Logic-Based Multi-Vehicle Backdoor Attacks against Offline RL Agents in End-to-end Autonomous Driving | 使用时序逻辑定义攻击车辆行为轨迹，生成精确触发器进行后门攻击。 | 解决现有自动驾驶后门攻击依赖不切实际像素级触发器的问题。 | 自动驾驶安全/后门攻击 |
| 41 | http://arxiv.org/abs/2509.17259v1 | Mind the Gap: Comparing Model- vs Agentic-Level Red Teaming with Action-Graph Observability on GPT-OSS-20B | 发现仅存在于代理执行上下文的漏洞，工具调用上下文脆弱性更高。 | 解决模型级安全 flaw 无法完全捕捉代理部署中独特风险的问题。 | 代理系统安全/红队测试 |
| 42 | http://arxiv.org/abs/2509.17488v1 | Privacy in Action: Towards Realistic Privacy Mitigation and Evaluation for LLM-Powered Agents | 提出 PrivacyChecker 缓解方案与 PrivacyLens-Live 动态基准 | 解决 LLM 智能体在动态环境中的隐私泄露风险 | LLM 智能体隐私保护 |
| 43 | http://arxiv.org/abs/2509.18415v1 | Context Lineage Assurance for Non-Human Identities in Critical Multi-Agent Systems | 基于 Merkle 树机制验证非人类身份谱系与来源 | 确保关键多智能体系统中 A2A 交互的安全可验证 | 关键基础设施智能体 |
| 44 | http://arxiv.org/abs/2509.18557v1 | LLMZ+: Contextual Prompt Whitelist Principles for Agentic LLMs | 实施上下文提示白名单原则替代传统检测防御 | 解决 Agentic LLM 面临提示注入与越狱攻击风险 | 企业级 Agentic LLM 安全 |
| 45 | http://arxiv.org/abs/2509.18970v2 | LLM-based Agents Suffer from Hallucinations: A Survey of Taxonomy, Methods, and Directions | 首次全面调查 LLM 智能体幻觉分类、原因与缓解 | 解决智能体幻觉导致任务执行错误与系统不可靠问题 | LLM 智能体可靠性研究 |
| 46 | http://arxiv.org/abs/2509.21634v2 | MobiLLM: An Agentic AI Framework for Closed-Loop Threat Mitigation in 6G Open RANs | LLM多Agent编排安全工单流，实现闭环威胁缓解 | 6G O-RAN开放架构扩大攻击面，防御被动滞后 | 6G网络安全、电信运营商 |
| 47 | http://arxiv.org/abs/2509.21712v1 | Not My Agent, Not My Boundary? Elicitation of Personal Privacy Boundaries in AI-Delegated Information Sharing | AI驱动的隐私边界 elicitation 方法，探测个体披露偏好 | 隐私决策情境依赖性强，难以 elicitation 细粒度边界 | AI隐私对齐、个人信息保护 |
| 48 | http://arxiv.org/abs/2511.13725v3 | AI Kill Switch for malicious web-based LLM agent | AutoGuard生成防御提示嵌入DOM，触发恶意Agent安全机制 | 基于web的LLM Agent恶意滥用风险（PII收集、网络攻击） | Web安全、恶意Agent防控 |
| 49 | http://arxiv.org/abs/2509.22040v1 | "Your AI, My Shell": Demystifying Prompt Injection Attacks on Agentic AI Coding Editors | AIShellJack自动化测试框架，314攻击载荷覆盖70种MITRE技术 | 高权限Agent编码编辑器远程提示注入攻击风险 | Cursor/GitHub Copilot等编码编辑器安全 |
| 50 | http://arxiv.org/abs/2509.22041v3 | Taxonomy of Comprehensive Safety for Clinical Agents | TACOS 21类细粒度分类法，整合安全过滤与工具选择 | 现有护栏和工具调用方法无法满足临床领域细微需求 | 临床聊天机器人、医疗Agent安全 |
| 51 | http://arxiv.org/abs/2509.22256v4 | Secure and Efficient Access Control for Computer-Use Agents via Context Space | CSAgent系统级静态策略访问控制，意图和上下文感知策略 | LLM不确定性导致Agent控制计算机有安全风险，现有缓解方法有局限 | 计算机使用Agent、系统级安全 |
| 52 | http://arxiv.org/abs/2509.20640v2 | Adaptive Cybersecurity Architecture for Digital Product Ecosystems Using Agentic AI | 集成自主目标驱动代理，实现动态学习、上下文感知决策及实时异常检测。 | 解决传统静态网络安全模型可扩展性差、实时检测能力弱的问题。 | 数字产品生态系统安全 |
| 53 | http://arxiv.org/abs/2509.21011v1 | Automatic Red Teaming LLM-based Agents with Model Context Protocol Tools | 提出 AutoMalTool 框架，自动生成恶意 MCP 工具以操纵主流 LLM 代理行为。 | 解决 MCP 工具引入的中毒攻击风险及缺乏自动系统化红队测试的问题。 | LLM 代理安全测试 |
| 54 | http://arxiv.org/abs/2509.21080v1 | Which Cultural Lens Do Models Adopt? On Cultural Positioning Bias and Agentic Mitigation in LLMs | 提出文化定位偏差基准，利用多智能体框架在推理时缓解生成偏差。 | 解决 LLM 默认生成立场 align 主流文化而视其他文化为外部的偏差问题。 | 文化公平性与对齐 |
| 55 | http://arxiv.org/abs/2509.22735v1 | Regulating the Agency of LLM-based Agents | 将代理性操作化为偏好刚性等维度，提出表示工程方法测量控制代理性。 | 解决能力增强的 LLM 代理因错位与失控导致潜在危害增长的问题。 | LLM 代理监管与安全 |
| 56 | http://arxiv.org/abs/2509.22830v2 | ChatInject: Abusing Chat Templates for Prompt Injection in LLM Agents | 发现聊天模板漏洞，提出多轮对话注入攻击方法。 | 揭示 LLM 智能体在结构化模板下的间接提示注入风险。 | LLM 智能体安全性 |
| 57 | http://arxiv.org/abs/2509.23188v3 | Diagnose, Localize, Align: A Full-Stack Framework for Reliable LLM Multi-Agent Systems under Instruction Conflicts | 提出全栈框架，通过手术式对齐解决指令冲突合规性。 | 解决多智能体系统在指令冲突下的层级合规失效问题。 | 可靠多智能体系统 |
| 58 | http://arxiv.org/abs/2509.23425v1 | Situational Awareness for Safe and Robust Multi-Agent Interactions Under Uncertainty | 开发情境感知模型，通过风险分析管理不确定性。 | 解决非协调智能体意图预测与资源约束下的安全交互。 | 电力/车辆/机器人网络 |
| 59 | http://arxiv.org/abs/2509.23614v1 | PSG-Agent: Personality-Aware Safety Guardrail for LLM-based Agents | 创建个性化护栏，持续监控跨轮次风险积累。 | 解决统一护栏忽视用户差异及跨交互风险演化问题。 | 关键应用 LLM 智能体 |
| 60 | http://arxiv.org/abs/2509.23694v4 | SafeSearch: Automated Red-Teaming of LLM-Based Search Agents | 自动化红队框架，评估搜索智能体在不可靠结果下的安全性。 | 解决搜索智能体因不可靠搜索结果产生不安全输出风险。 | 联网搜索智能体 |
| 61 | http://arxiv.org/abs/2509.25271v4 | RADAR: A Risk-Aware Dynamic Multi-Agent Framework for LLM Safety Evaluation via Role-Specialized Collaboration | 风险感知动态多智能体框架，重构风险概念空间。 | 解决现有安全评估中评估者偏差与检测失效问题。 | LLM 安全评估 |
| 62 | http://arxiv.org/abs/2509.23864v1 | AgentGuard: Runtime Verification of AI Agents | 提出动态概率保证框架，通过运行时验证监控智能体行为 | 解决自主 AI 系统不可预测性及 emergent 行为带来的风险 | 通用 AI 智能体系统 |
| 63 | http://arxiv.org/abs/2509.23994v2 | Policy-as-Prompt: Turning AI Governance Rules into Guardrails for AI Agents | 将监管规则转化为可执行提示词，构建运行时护栏 | 解决 regulated 场景下策略难以转化为可执行控制的问题 | regulated AI 系统 |
| 64 | http://arxiv.org/abs/2509.24240v1 | Takedown: How It's Done in Modern Coding Agent Exploits | 系统分析编码智能体内部工作流，识别可导致端到端利用的安全问题 | 缺乏对现代 LLM 驱动编码智能体的系统性安全分析 | 编码智能体安全 |
| 65 | http://arxiv.org/abs/2509.24408v2 | FuncPoison: Poisoning Function Library to Hijack Multi-agent Autonomous Driving Systems | 提出 FuncPoison 攻击，通过污染函数库操纵多智能体自动驾驶行为 | 解决 LLM 驱动自动驾驶系统函数库作为关键攻击面的脆弱性 | 自动驾驶系统安全 |
| 66 | http://arxiv.org/abs/2510.02373v1 | A-MemGuard: A Proactive Defense Framework for LLM-Based Agent Memory | 基于共识验证和双记忆结构的主动防御框架 | 防止恶意记录注入操纵智能体行为 | LLM 智能体记忆安全 |
| 67 | http://arxiv.org/abs/2509.25302v1 | Dive into the Agent Matrix: A Realistic Evaluation of Self-Replication Risk in LLM Agents | 量化智能体自复制风险的综合评估框架 | 目标错位导致的自发复制安全隐患 | LLM 智能体安全部署 |
| 68 | http://arxiv.org/abs/2509.25624v2 | STAC: When Innocent Tools Form Dangerous Chains to Jailbreak LLM Agents | 利用无害工具链组合实现有害操作的攻击框架 | 工具启用智能体的序列动作安全风险 | LLM 智能体越狱防御 |
| 69 | http://arxiv.org/abs/2509.25885v1 | SafeMind: Benchmarking and Mitigating Safety Risks in Embodied LLM Agents | 形式化三种正交安全约束类型的多模态基准 | 具身智能体与物理世界交互的安全漏洞 | 具身 LLM 智能体安全 |
| 70 | http://arxiv.org/abs/2509.25894v1 | Red Teaming Program Repair Agents: When Correct Patches can Hide Vulnerabilities | 生成 adversarial issue 误导智能体产生脆弱补丁 | 功能正确补丁可能隐藏安全风险 | 自动程序修复智能体 |
| 71 | http://arxiv.org/abs/2509.25926v1 | Better Privilege Separation for Agents by Restricting Data Types | 通过限制数据类型系统防止提示注入的方法 | LLM 与非结构化内容交互的提示注入漏洞 | LLM 系统安全 |
| 72 | http://arxiv.org/abs/2509.26100v1 | SafeEvalAgent: Toward Agentic and Self-Evolving Safety Evaluation of LLMs | 自主摄入政策文档生成并进化安全基准的多智能体框架 | 静态基准无法应对动态 AI 风险和法规 | LLM 安全与合规评估 |
| 73 | http://arxiv.org/abs/2509.26354v2 | Your Agent May Misevolve: Emergent Risks in Self-evolving LLM Agents | 系统研究智能体自我进化偏离导致有害 outcomes | 自我进化引入被当前安全研究忽视的新风险 | 自进化 LLM 智能体 |

[返回目录](#目录)

<a id="cat-11"></a>

## Agent可解释性与透明度

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2509.08682v1 | Automatic Failure Attribution and Critical Step Prediction Method for Multi-Agent Systems Based on Causal Inference | 基于多粒度因果推理的故障归因框架，性能因果反转原理结合Shapley值 | 当前诊断工具依赖统计相关性，在复杂基准上根因定位准确率低于15% | 多Agent系统的故障诊断与优化 |
| 2 | http://arxiv.org/abs/2509.04809v2 | TalkToAgent: A Human-centric Explanation of Reinforcement Learning Agents with Large Language Models | 多智能体 LLM 框架提供 RL 策略的交互式自然语言解释 | 弥合复杂 RL 策略与领域专家间的可理解性差距 | 强化学习系统解释 |
| 3 | http://arxiv.org/abs/2509.17978v2 | The STAR-XAI Protocol: A Framework for Inducing and Verifying Agency, Reasoning, and Reliability in AI Agents | STAR-XAI 协议通过苏格拉底对话与状态锁实现透明 | 解决大推理模型黑盒性质与状态幻觉问题 | 高可靠性 AI 智能体 |
| 4 | http://arxiv.org/abs/2509.23757v1 | Transparent Visual Reasoning via Object-Centric Agent Collaboration | 对象中心表示与透明多智能体推理，生成可解释证据。 | 解决视觉 AI 决策缺乏人类可理解概念 grounding 问题。 | 可解释视觉分类 |
| 5 | http://arxiv.org/abs/2509.25593v1 | Causal Autoencoder-like Generation of Feedback Fuzzy Cognitive Maps with an LLM Agent | LLM 近似身份映射的可解释 AI 系统 | 黑盒自编码器隐藏变量不可读 | 模糊认知地图重建 |
| 6 | http://arxiv.org/abs/2509.26433v3 | ACT: Agentic Classification Tree | 将每个分裂 formulat 为自然语言问题的决策树方法 | 非结构化输入缺乏透明可审计决策规则 | 高风险文本分类 |

[返回目录](#目录)

<a id="cat-12"></a>

## 低代码/无代码Agent平台

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2510.15898v1 | HealthDial: A No-Code LLM-Assisted Dialogue Authoring Tool for Healthcare Virtual Agents | LLM自动创建初始会话计划和对话，输出为有限状态机供验证，无代码UI可编辑 | 医疗服务提供者和教育者创建虚拟Agent进行健康教育门槛高 | 医疗健康领域的虚拟Agent对话创作 |
| 2 | http://arxiv.org/abs/2509.25250v1 | Memory Management and Contextual Consistency for Long-Running Low-Code Agents | 提出混合记忆系统与智能衰减机制，支持用户可视管理。 | 解决低代码智能体长期运行中的记忆膨胀与上下文退化。 | 低代码业务自动化 |
| 3 | http://arxiv.org/abs/2509.23735v2 | Demystifying the Lifecycle of Failures in Platform-Orchestrated Agentic Workflows | 实证研究平台编排工作流故障生命周期，提供修复指南。 | 解决低代码智能体工作流中故障传播与归因困难问题。 | 平台编排智能体 |
| 4 | http://arxiv.org/abs/2509.25282v2 | Toward Causal-Visual Programming: Enhancing Agentic Reasoning in Low-Code Environments | 引入因果视觉编程，通过用户定义因果图约束智能体推理 | 解决低代码环境中智能体因概率关联而非因果理解导致幻觉问题 | 低代码工作流设计 |

[返回目录](#目录)

<a id="cat-13"></a>

## Agent规划与推理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2509.08970v2 | Gala: Global LLM Agents for Text-to-Model Translation | 全局Agent方法：多个专用LLM Agent按全局约束类型分解建模任务 | 自然语言描述优化问题转换为MiniZinc模型需要逻辑推理和约束编程专业知识 | 约束规划问题的文本到模型转换 |
| 2 | http://arxiv.org/abs/2509.03581v3 | Learning When to Plan: Efficiently Allocating Test-Time Compute for LLM Agents | 提出动态规划框架，让代理灵活决定何时分配计算资源 | 解决始终规划或从不规划导致的性能下降与计算浪费 | 长 horizon 任务 LLM 代理 |
| 3 | http://arxiv.org/abs/2509.01659v1 | Physics Supernova: AI Agent Matches Elite Gold Medalists at IPhO 2025 | 工具集成agent系统，在IPhO理论题中达到金牌选手水平，展现物理问题求解能力 | AI系统缺乏将物理定律形式化并应用于复杂问题求解的能力 | 科学问题自动求解与物理竞赛级推理任务 |
| 4 | http://arxiv.org/abs/2509.01920v3 | Dynamic Speculative Agent Planning | 异步在线RL框架联合优化延迟与成本，单参数控制加速 - 性能权衡 | LLM agent部署面临高延迟与推理成本，现有加速方法牺牲性能或需离线训练 | 需要低延迟、低成本的实时agent应用部署 |
| 5 | http://arxiv.org/abs/2509.02360v2 | When Agents go Astray: Course-Correcting SWE Agents with PRMs | 推理时PRM基于错误分类学提供轻量可解释反馈，动态纠正SWE agent轨迹低效 | SWE agent执行中常出现冗余探索、循环、无法终止等轨迹级低效 | 提升软件工程agent的可靠性、效率与任务完成率 |
| 6 | http://arxiv.org/abs/2509.02401v1 | Towards Agents That Know When They Don't Know: Uncertainty as a Control Signal for Structured Reasoning | 检索+摘要双重不确定性信号，指导推理时过滤与RL训练，提升事实性与校准 | LLM agent在复杂多表数据推理中易产生流畅但过度自信的错误输出 | 生物医学结构化数据的多表查询摘要与下游分析 |
| 7 | http://arxiv.org/abs/2509.06278v3 | TableMind: An Autonomous Programmatic Agent for Tool-Augmented Table Reasoning | 模拟人类多轮交互认知模式，内部化规划、行动与反思 | 解决单轮推理范式在表格理解中上下文溢出与数值敏感性问题 | 表格数据推理与分析 |
| 8 | http://arxiv.org/abs/2509.06436v2 | Tree of Agents: Improving Long-Context Capabilities of Large Language Models through Multi-Perspective Reasoning | 多智能体推理框架分段处理输入，动态交换信息协同推理 | 解决长上下文任务中中间信息利用不足与幻觉问题 | 长文本理解与推理 |
| 9 | http://arxiv.org/abs/2509.07680v1 | CAViAR: Critic-Augmented Video Agentic Reasoning | 引入评论家区分成功与失败序列，增强视频推理代理 | 解决长视频复杂推理任务中模型性能下降问题 | 视频理解与推理 |
| 10 | http://arxiv.org/abs/2509.10222v2 | Compartmentalised Agentic Reasoning for Clinical NLI | 分区代理推理框架，路由至特定推理族并验证 | 解决临床 NLI 中表面匹配导致的推理错误问题 | 临床自然语言推断 |
| 11 | http://arxiv.org/abs/2509.10401v2 | "Abduct, Act, Predict: Scaffolding Causal Inference for Automated Failure Attribution in Multi-Agent Systems" | A2P 支架，将失败归因转化为 abduction-action-predict 因果推理 | 解决多智能体系统失败归因准确率低的问题 | 复杂多智能体系统调试 |
| 12 | http://arxiv.org/abs/2509.11796v1 | FineQuest: Adaptive Knowledge-Assisted Sports Video Understanding via Agent-of-Thoughts Reasoning | 提出双模式推理框架，引入体育知识场景图增强理解 | 解决通用模型在复杂体育视频问答中知识缺失与推理不足问题 | 体育视频理解与问答 |
| 13 | http://arxiv.org/abs/2509.13309v2 | WebResearcher: Unleashing unbounded reasoning capability in Long-Horizon Agents | 将深度研究重构为 MDP，定期巩固发现并维持专注工作区 | 解决现有单上下文方法受困于上下文窒息与噪声污染问题 | 长程深度研究代理 |
| 14 | http://arxiv.org/abs/2509.15238v1 | Generating Plans for Belief-Desire-Intention (BDI) Agents Using Alternating-Time Temporal Logic (ATL) | 利用交替时间时序逻辑自动生成 BDI 智能体计划。 | 解决 BDI 智能体计划生成依赖人工且难以处理多 agent 竞争合作问题。 | BDI 智能体系统 |
| 15 | http://arxiv.org/abs/2509.16343v1 | Agentic Reasoning for Robust Vision Systems via Increased Test-Time Compute | 提出无需训练的视觉推理代理框架，包裹模型进行思考 - 批评 - 行动循环。 | 解决高风险领域视觉系统缺乏广泛鲁棒性且重训练成本高的问题。 | 视觉系统/遥感与医疗 |
| 16 | http://arxiv.org/abs/2509.16971v2 | AudioGenie-Reasoner: A Training-Free Multi-Agent Framework for Coarse-to-Fine Audio Deep Reasoning | 将音频推理转化为文本理解，设计主动迭代文档 refinement 循环。 | 解决音频深度推理缺乏显式推理链训练数据及主动探索机制的问题。 | 音频推理/多模态理解 |
| 17 | http://arxiv.org/abs/2509.21842v1 | DeepTravel: An End-to-End Agentic Reinforcement Learning Framework for Autonomous Travel Planning Agents | 端到端Agent RL框架，分层奖励建模+失败经验回放增强 | 现有旅行规划Agent依赖手工提示和固定工作流 | 旅行 itinerary 生成、DiDi企业应用 |
| 18 | http://arxiv.org/abs/2509.22720v1 | LayoutAgent: A Vision-Language Agent Guided Compositional Diffusion for Spatial Layout Planning | 统一视觉语言推理与组合扩散，利用场景图合成尊重对象关系的边界框。 | 解决扩散模型缺乏显式空间推理导致对象布局不真实的问题。 | 空间布局规划与图像生成 |
| 19 | http://arxiv.org/abs/2509.20616v2 | Training Task Reasoning LLM Agents for Multi-turn Task Planning via Single-turn Reinforcement Learning | 将多转任务规划转化为单转推理问题，利用 GRPO 与密集奖励优化策略。 | 解决多转任务规划奖励稀疏、信用分配难及 RL 计算开销大的问题。 | 长程任务规划 |
| 20 | http://arxiv.org/abs/2509.21035v1 | CLAUSE: Agentic Neuro-Symbolic Knowledge Graph Reasoning via Dynamic Learnable Context Engineering | 将上下文构建视为序列决策过程，联合优化子图构建、路径发现与证据选择。 | 解决静态 k-hop 扩展过度检索、上下文膨胀及运行时不可预测的问题。 | 知识图谱多跳问答 |
| 21 | http://arxiv.org/abs/2509.23071v1 | From Evidence to Trajectory: Abductive Reasoning Path Synthesis for Training Retrieval-Augmented Generation Agents | 提出证据锚定推理路径合成范式，指导 RAG 智能体训练。 | 解决 RAG 智能体缺乏过程级监督与复杂推理能力问题。 | 检索增强生成智能体 |
| 22 | http://arxiv.org/abs/2509.24230v2 | ELHPlan: Efficient Long-Horizon Task Planning for Multi-Agent Collaboration | 引入动作链作为规划原语，平衡长视野 lookahead 与重规划成本 | 解决多机器人协作中长视野任务规划效率与适应性权衡问题 | 多机器人协作 |
| 23 | http://arxiv.org/abs/2509.24765v5 | From Ambiguity to Verdict: A Semiotic-Grounded Multi-Perspective Agent for LLM Logical Reasoning | 提出符号方块引导框架，联合处理逻辑复杂性与语义复杂性 | 解决现有系统难以处理抽象命题及模糊上下文逻辑推理问题 | 逻辑推理任务 |
| 24 | http://arxiv.org/abs/2509.24943v1 | Perceive, Reflect and Understand Long Video: Progressive Multi-Granular Clue Exploration with Interactive Agents | 利用多粒度感知与验证反思智能体交互循环，高效理解长视频 | 解决长视频理解中任务关键信息捕捉完整性与效率平衡问题 | 长视频理解 |
| 25 | http://arxiv.org/abs/2509.26048v2 | RE-Searcher: Robust Agentic Search with Goal-oriented Planning and Self-reflection | 明确 articulates 搜索目标并反思证据是否满足 | 环境复杂性导致搜索行为脆弱 | 复杂搜索环境 |

[返回目录](#目录)

<a id="cat-14"></a>

## Agent工具使用与环境交互

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2509.09234v1 | Agentic LLMs for Question Answering over Tabular Data | NL-to-SQL多阶段管道：示例选择、SQL生成、答案提取、验证、迭代优化 | 真实世界表格结构、大小、数据类型多样，Table QA挑战独特 | 表格数据上的问答系统 |
| 2 | http://arxiv.org/abs/2509.01055v3 | VerlTool: Towards Holistic Agentic Reinforcement Learning with Tool Use | 统一模块化框架支持代码/搜索/SQL/视觉等多模态工具，异步执行加速近2倍 | 现有ARLT方法代码碎片化、同步执行瓶颈、跨领域扩展性差 | 需要多工具协作的复杂推理与任务执行场景 |
| 3 | http://arxiv.org/abs/2509.01560v3 | In-N-Out: A Parameter-Level API Graph Dataset for Tool Agents | 首个专家标注的参数级API graph数据集，支持工具检索与多工具组合查询生成 | 复杂任务中agent难以正确识别和排序调用多个API | 提升tool agent的API理解与组合调用能力 |
| 4 | http://arxiv.org/abs/2509.06501v3 | WebExplorer: Explore and Evolve for Training Long-Horizon Web Agents | 系统化数据生成方法，迭代演化查询以训练长程 Web 代理 | 解决开源 Web 代理在复杂任务中信息寻求能力有限问题 | 网页浏览与信息检索代理 |
| 5 | http://arxiv.org/abs/2509.07098v1 | Instruction Agent: Enhancing Agent with Expert Demonstration | 利用专家演示提取指令，严格遵循轨迹执行避免错误 | 解决 GUI 代理在复杂任务与新颖 UI 元素中执行失败问题 | 图形用户界面自动化 |
| 6 | http://arxiv.org/abs/2509.10446v2 | DeepDive: Advancing Deep Search Agents with Knowledge Graphs and Multi-Turn RL | 结合知识图谱合成难问，多轮 RL 增强长程搜索推理 | 解决开放 LLM 深搜能力弱及缺乏困难监督数据问题 | 深度搜索智能体 |
| 7 | http://arxiv.org/abs/2509.12867v1 | Tool-R1: Sample-Efficient Reinforcement Learning for Agentic Tool Use | 提出 RL 框架，通过生成可执行 Python 代码实现多步工具使用 | 解决 LLM 在处理需最新知识或精确操作的实际任务中能力受限问题 | 通用工具增强推理 |
| 8 | http://arxiv.org/abs/2509.13615v5 | See, Think, Act: Teaching Multimodal Agents to Effectively Interact with GUI by Identifying Toggles | 提出状态感知推理方法，使代理感知当前 toggle 状态并行动 | 解决多模态代理无法可靠执行 toggle 控制指令瓶颈问题 | GUI 交互代理 |
| 9 | http://arxiv.org/abs/2509.14480v1 | Process-Supervised Reinforcement Learning for Interactive Multimodal Tool-Use Agents | 引入沙箱环境及轮次裁决强化学习，支持交错语音文本 rollout。 | 解决多模态工具使用智能体长程任务信用分配困难的问题。 | 多模态交互式工具使用智能体 |
| 10 | http://arxiv.org/abs/2509.15221v2 | ScaleCUA: Scaling Open-Source Computer Use Agents with Cross-Platform Data | 构建跨平台大规模计算机使用数据集，训练通用 CUA。 | 解决开源计算机使用智能体缺乏大规模数据及基础模型问题。 | 通用计算机使用智能体 |
| 11 | http://arxiv.org/abs/2509.18063v1 | ARK-V1: An LLM-Agent for Knowledge Graph Question Answering Requiring Commonsense Reasoning | 简单 KG 智能体迭代探索图谱回答自然语言查询 | 解决 LLM 内部知识不足与 KG 多跳推理集成难问题 | 知识图谱问答 |
| 12 | http://arxiv.org/abs/2510.00023v2 | ToolBrain: A Flexible Reinforcement Learning Framework for Agentic Tools | 提供灵活 RL 框架训练智能体工具使用，支持自定义奖励与自动化 LLM 评判。 | 解决智能体工具训练奖励设计难、多工具选择差及适应慢的问题。 | 通用智能体工具使用训练 |
| 13 | http://arxiv.org/abs/2509.25238v1 | PALADIN: Self-Correcting Language Model Agents to Cure Tool-Failure Cases | 训练代理检测执行错误并检索失败案例库执行恢复动作，提升容错能力。 | 解决工具增强代理因工具故障导致级联推理错误及任务放弃的问题。 | 工具使用代理容错 |
| 14 | http://arxiv.org/abs/2509.21072v1 | Recon-Act: A Self-Evolving Multi-Agent Browser-Use System via Web Reconnaissance, Tool Generation, and Task Execution | 侦察团队对比错误与成功轨迹生成通用工具，行动团队利用工具闭环执行。 | 解决多转长程网页任务中动作序列混乱及试错过多的问题。 | 浏览器使用代理 |
| 15 | http://arxiv.org/abs/2509.24183v1 | Retrieval-augmented GUI Agents with Generative Guidelines | 提出 RAG-GUI，利用网络教程增强 VLM 智能体在长尾场景的表现 | 解决 GUI 智能体训练数据稀缺及复杂任务长尾知识不足问题 | 图形界面自动化 |
| 16 | http://arxiv.org/abs/2509.24978v5 | Agentic Exploration of Physics Models | 利用 LLM 工具使用能力探索未知物理系统 | 自动化发现未知系统定律的启发式循环 | 科学发现与物理模型 |
| 17 | http://arxiv.org/abs/2509.25189v1 | InfoAgent: Advancing Autonomous Information-Seeking Agents | 结合创新数据合成管线和编排 Web 搜索工具的深度研究智能体 | 知识截止、幻觉及交互模态有限 | 自主信息搜寻与问答 |
| 18 | http://arxiv.org/abs/2509.26539v1 | Ferret-UI Lite: Lessons from Building Small On-Device GUI Agents | 通过数据混合和 RL 构建紧凑端到端 GUI 智能体 | 小型设备模型有效交互 GUI 困难 | 移动端 GUI 智能体 |
| 19 | http://arxiv.org/abs/2510.00161v1 | TAMA: Tool-Augmented Multimodal Agent for Procedural Activity Understanding | 利用多媒体返回工具实现交错多模态推理 | 针对程序活动助手的系统开发尚未探索 | 程序活动理解 |
| 20 | http://arxiv.org/abs/2510.01279v1 | TUMIX: Multi-Agent Test-Time Scaling with Tool-Use Mixture | 运行多个采用不同工具策略智能体的集成框架 | 缺乏有效结合文本推理编码搜索的实际指导 | 复杂推理任务 |

[返回目录](#目录)

<a id="cat-15"></a>

## Agent仿真与社会模拟

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2509.02924v1 | Simulacra Naturae: Generative Ecosystem driven by Agent-Based Simulations and Brain Organoid Collective Intelligence | 结合脑类器官信号与生成式 Agent 模拟自然生态系统 | 探索生物计算与物质生态纠缠下的集体关怀表现形式 | 艺术装置与混合计算系统 |
| 2 | http://arxiv.org/abs/2509.03303v2 | Automatic Differentiation of Agent-Based Models | 将自动微分技术应用于基于代理的模型校准 | 降低复杂系统 ABM 模型的计算负担与参数校准难度 | 流行病学与金融市场模拟 |
| 3 | http://arxiv.org/abs/2509.03736v1 | Are LLM Agents Behaviorally Coherent? Latent Profiles for Social Simulation | 评估 LLM 代理在不同实验设置下的内部行为一致性 | 揭示 LLM 代理作为人类受试者替代品的内部不一致缺陷 | 社会科学研究模拟 |
| 4 | http://arxiv.org/abs/2509.03793v1 | SAMVAD: A Multi-Agent System for Simulating Judicial Deliberation Dynamics in India | 集成 RAG 与多智能体模拟印度司法审议动态 | 克服实证研究伦理障碍，模拟司法小组审议过程 | 印度司法系统模拟 |
| 5 | http://arxiv.org/abs/2509.04537v3 | Emergent Social Dynamics of LLM Agents in the El Farol Bar Problem | 观察 LLM 代理在空间扩展 El Farol 酒吧问题中的社会动态 | 揭示 LLM 代理平衡博弈理性与社会动机的复杂交互 | 社会困境博弈模拟 |
| 6 | http://arxiv.org/abs/2509.01441v1 | LLM-empowered Agents Simulation Framework for Scenario Generation in Service Ecosystem Governance | 三LLM agent（环境+社会+规划）自适应协调，实时感知调整实验方案 | 传统场景分析依赖预定义规则，难以处理服务生态系统的复杂不确定性 | 服务生态系统治理的场景生成与决策支持 |
| 7 | http://arxiv.org/abs/2509.02172v2 | RumorSphere: A Framework for Million-scale Agent-based Dynamic Simulation of Rumor Propagation | 信息茧房理论指导的多agent动态交互策略+分层共振网络，自适应激活核心传播者 | 现有谣言仿真忽略核心agent动态性与网络拓扑，影响百万级仿真准确性 | 大规模社交媒体谣言传播的动态建模与干预 |
| 8 | http://arxiv.org/abs/2509.06355v2 | A Data-Driven Discretized CS:GO Simulation Environment to Facilitate Strategic Multi-Agent Planning Research | 抽象战略 planning 为高层离散模拟，保留低层环境 fidelity | 解决复杂多智能体交互仿真中高保真与效率平衡问题 | 战略多智能体规划研究 |
| 9 | http://arxiv.org/abs/2509.10147v1 | Virtual Agent Economies | 提出“沙盒经济”框架分析 emergent AI 代理经济层 | 探讨自主 Agent 交易带来的经济风险与不平等问题 | 未来 AI 代理经济系统 |
| 10 | http://arxiv.org/abs/2509.10397v2 | RecoWorld: Building Simulated Environments for Agentic Recommender Systems | 双视图架构模拟用户与推荐 Agent 多轮交互环境 | 解决推荐系统训练缺乏安全试错空间的问题 | 代理推荐系统训练 |
| 11 | http://arxiv.org/abs/2509.13346v1 | "All Models Are Wrong, But Can They Be Useful? Lessons from COVID-19 Agent-Based Models: A Systematic Review" | 系统回顾 536 篇 COVID-19 基于代理模型研究 | 评估 ABM 在公共卫生危机中的效用与透明度缺失 | 公共卫生政策模拟 |
| 12 | http://arxiv.org/abs/2509.10867v1 | Agent-based Simulation for Drone Charging in an Internet of Things Environment System | 基于代理仿真协调无人机群电池充电，结合 ML 分析 | 解决 IoT 环境中大规模无人机部署的电池优化问题 | 智能农业与 IoT 无人机 |
| 13 | http://arxiv.org/abs/2509.11078v2 | Patient-Zero: Scaling Synthetic Patient Agents to Real-World Distributions without Real Patient Data | 无需真实记录的从头患者模拟，双轨认知记忆系统 | 解决医疗数据稀缺、隐私及患者代理稳定性难题 | 医疗数据生成与推理 |
| 14 | http://arxiv.org/abs/2509.13011v1 | A Visualized Framework for Event Cooperation with Generative Agents | 开发可视化平台，评估代理在物理事件组织中的协作能力 | 解决现有框架缺乏可视化集成与物理事件组织系统评估问题 | 生成代理社会仿真 |
| 15 | http://arxiv.org/abs/2509.13588v3 | CoBRA: Programming Cognitive Bias in Social Agents Using Classic Social Science Experiments | 引入闭环系统原语，量化并调节代理认知偏差 | 解决自然语言描述导致代理行为不一致且无法捕捉细微差别问题 | 社会仿真代理行为 |
| 16 | http://arxiv.org/abs/2509.13712v1 | Inject, Fork, Compare: Defining an Interaction Vocabulary for Multi-Agent Simulation Platforms | 定义注入、分叉、比较三种操作，构建多智能体仿真交互词汇。 | 解决多智能体仿真缺乏清晰交互模式及因果分析能力的问题。 | 多智能体社会仿真平台 |
| 17 | http://arxiv.org/abs/2509.14485v1 | Beyond the high score: Prosocial ability profiles of multi-agent populations | 应用贝叶斯方法推断多智能体系统的亲社会能力 profile。 | 解决社会 AI 评估中抽象行为难控制及评价框架偏差问题。 | 多智能体社会能力评估 |
| 18 | http://arxiv.org/abs/2509.16457v1 | Implicit Behavioral Alignment of Language Agents in High-Stakes Crowd Simulations | 提出 PEBA 框架与 PEvo 算法，迭代优化代理角色以对齐现实专家基准。 | 解决生成式代理行为偏离专家预期与现实数据的行为现实主义差距。 | 社会模拟/紧急事件仿真 |
| 19 | http://arxiv.org/abs/2509.16912v1 | Analysis of the Impact of an Execution Algorithm with an Order Book Imbalance Strategy on a Financial Market Using an Agent-based Simulation | 构建执行算法代理，在人工市场中测试订单簿不平衡策略的影响。 | 解决真实市场中隔离订单簿不平衡效应困难且缺乏证据的问题。 | 金融市场仿真/交易算法 |
| 20 | http://arxiv.org/abs/2509.17703v1 | An LLM-based Agent Simulation Approach to Study Moral Evolution | 基于 LLM 智能体模拟史前社会道德演化过程 | 探究道德框架与认知约束对演化结果的影响 | 社会演化与人类学研究 |
| 21 | http://arxiv.org/abs/2509.18985v1 | Simulating Online Social Media Conversations on Controversial Topics Using AI Agents Calibrated on Real-World Data | 基于真实数据校准 LLM 智能体模拟社交媒体对话 | 探究 LLM 智能体在社交环境中的行为与意见演化 | 社交媒体行为模拟 |
| 22 | http://arxiv.org/abs/2509.21862v2 | Reimagining Agent-based Modeling with Large Language Model Agents via Shachi | Shachi方法论将Agent策略分解为配置-记忆-工具三核心认知组件 | 缺乏 principled 方法论进行LLM多Agent系统受控实验 | LLM Agent社会模拟、群体行为研究 |
| 23 | http://arxiv.org/abs/2509.21868v2 | What Makes LLM Agent Simulations Useful for Policy Practice? An Iterative Design Study in Emergency Preparedness | 一年迭代设计过程，13000 Agent模拟校园集会紧急场景 | LLM Agent模拟如何对真实政策实践有用知之甚少 | 应急准备政策、校园疏散规划 |
| 24 | http://arxiv.org/abs/2510.06225v1 | Generalized Multi-agent Social Simulation Framework | 模块化面向对象框架，分层结构整合基类，记忆摘要机制 | 当前模拟系统难以扩展到多样场景，缺乏模块化设计复用性差 | 社交媒体人类交互模拟、在线社会行为 |
| 25 | http://arxiv.org/abs/2509.22479v1 | NeLLCom-Lex: A Neural-agent Framework to Study the Interplay between Lexical Systems and Language Use | 神经Agent框架模拟语义变化，先 grounding 真实词汇系统再操纵交际需求 | 观察方法无法探究因果机制，人类实验范式难应用于语义变化 | 词汇语义变化研究、颜色命名任务 |
| 26 | http://arxiv.org/abs/2509.22537v1 | The Emergence of Altruism in Large-Language-Model Agents Society | Schelling变体城市迁移模型，200+ LLM Agent导航自我利益与集体利益冲突 | 现有研究聚焦小规模任务导向游戏合作，忽视大规模Agent社会利他主义涌现 | LLM Agent社会模拟、群体行为逻辑 |
| 27 | http://arxiv.org/abs/2509.20538v1 | Pattern Formation in Agent-Based and PDE Models for Evolutionary Games with Payoff-Driven Motion | 探索随机与定向运动对空间种群模式形成及收益的影响，对比随机与 PDE 模型。 | 解决进化博弈中空间结构对合作行为演化影响机制不明确的问题。 | 进化博弈与社会仿真 |
| 28 | http://arxiv.org/abs/2509.23124v5 | Non-Collaborative User Simulators for Tool Agents | 模拟四类非协作用户行为，压力测试工具智能体。 | 解决现有用户模拟器过于友好，缺乏真实鲁棒性测试。 | 工具使用智能体 |
| 29 | http://arxiv.org/abs/2509.23212v1 | Replication and Information Extraction in a Minimal Agent-Environment Model | 构建最小智能体环境模型，研究自一致性驱动的复制现象。 | 探索无监督环境下智能体自发对齐 latent 结构的机制。 | 理论智能体模型 |
| 30 | http://arxiv.org/abs/2509.23270v1 | Socio-Economic Model of AI Agents | 构建异质智能体模型，研究 AI 协作对社会总产出的影响。 | 分析资源约束下 AI 协作对宏观经济产出的非线性增长。 | 社会经济系统模拟 |
| 31 | http://arxiv.org/abs/2509.23557v1 | SIMPOL Model for Solving Continuous-Time Heterogeneous Agent Problems | 模块化数值框架，求解连续时间异质智能体经济模型。 | 解决消费储蓄优化中 coupled PDE 系统的稳定求解问题。 | 定量宏观经济模型 |
| 32 | http://arxiv.org/abs/2510.02360v2 | Spiral of Silence in Large Language Model Agents | 评估框架研究 LLM 集体中的沉默螺旋社会动力学。 | 揭示纯统计语言生成中涌现的从众与多数主导现象。 | LLM 社会模拟 |
| 33 | http://arxiv.org/abs/2509.23993v2 | Advancing Multi-agent Traffic Simulation via R1-Style Reinforcement Fine-Tuning | 提出 SMART-R1，利用 R1 风格强化微调对齐智能体行为与人类偏好 | 解决交通仿真中训练与测试分布偏移导致泛化差的问题 | 自动驾驶交通仿真 |
| 34 | http://arxiv.org/abs/2509.24063v1 | TeraAgent: A Distributed Agent-Based Simulation Engine for Simulating Half a Trillion Agents | 提出分布式仿真引擎，优化序列化与数据传输，支持万亿级智能体 | 解决现有平台无法跨服务器扩展模拟大规模智能体系统的问题 | 大规模复杂系统仿真 |
| 35 | http://arxiv.org/abs/2510.05124v2 | MADS: Multi-Agent Dialogue Simulation for Diverse Persuasion Data Generation | 通过智能体自玩生成多样化说服多轮对话框架 | 缺乏用户数据及冷启动评估困难 | 营销场景与对话数据生成 |
| 36 | http://arxiv.org/abs/2509.26080v2 | Evaluating the Use of Large Language Models as Synthetic Social Agents in Social Science Research | 提出将 LLM 作为高容量模式匹配器的实用重构 | 避免将 LLM 输出误认为概率推断 | 社会科学研究 |

[返回目录](#目录)
