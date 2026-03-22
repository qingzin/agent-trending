# AI agents 2026年3月（截至3月20日）学术分类汇总

共收录 639 篇论文，统计范围截至 2026 年 3 月 20 日，按研究方向分类整理如下。

## 目录

- [Agent架构与框架设计（64篇）](#cat-01)
- [Agent仿真与社会模拟（31篇）](#cat-02)
- [Agent评测与基准（67篇）](#cat-03)
- [Agent安全与对齐（100篇）](#cat-04)
- [基于Agent的应用系统（105篇）](#cat-05)
- [Agent规划与推理（27篇）](#cat-06)
- [多Agent协作与通信（36篇）](#cat-07)
- [人机协作Agent（30篇）](#cat-08)
- [Agent工具使用与环境交互（14篇）](#cat-09)
- [具身智能Agent（29篇）](#cat-10)
- [Agent记忆与知识管理（43篇）](#cat-11)
- [Agent学习与自进化（49篇）](#cat-12)
- [多Agent强化学习（36篇）](#cat-13)
- [低代码/无代码Agent平台（2篇）](#cat-14)
- [Agent可解释性与透明度（6篇）](#cat-15)

<a id="cat-01"></a>

## Agent架构与框架设计

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2603.00846v1 | Tiny-Critic RAG: Empowering Agentic Fallback with Parameter-Efficient Small Language Models | 部署参数高效小模型作为门控，实现超低延迟二元路由，降低计算冗余。 | 解决大模型作为评估器带来的高计算冗余和延迟问题。 | 高吞吐量 RAG 系统与自主智能体 |
| 2 | http://arxiv.org/abs/2603.01059v2 | GroupGPT: A Token-efficient and Privacy-preserving Agentic Framework for Multi-User Chat Assistant | 大小模型协作架构，解耦干预时机与响应生成，支持多模态输入与隐私清洗。 | 解决群聊场景中代理干预成本高、扩展性差及隐私风险问题。 | 多用户群聊助手与即时通讯 |
| 3 | http://arxiv.org/abs/2603.01179v2 | A402: Binding Cryptocurrency Payments to Service Execution for Agentic Commerce | 引入原子服务通道，基于 TEE 辅助适配器签名绑定支付与服务执行。 | 解决现有标准无法强制服务执行、支付与结果交付端到端原子性问题。 | 自主智能体商业与加密货币支付 |
| 4 | http://arxiv.org/abs/2603.01416v1 | Securing the Floor and Raising the Ceiling: A Merging-based Paradigm for Multi-modal Search Agents | 免训练范式，通过跨模态模型融合赋予 VLM 自主搜索能力。 | 解决依赖大规模监督轨迹或昂贵 RL 导致的高成本、不稳定及冷启动问题。 | 多模态搜索智能体与视觉语言模型 |
| 5 | http://arxiv.org/abs/2603.01438v1 | Enhancing Persona Following at Decoding Time via Dynamic Importance Estimation for Role-Playing Agents | 动态估计上下文依赖角色重要性，集成到加权奖励引导解码中。 | 解决静态提示或微调无法适应动态场景及角色影响力随场景变化问题。 | 角色扮演语言代理与社会模拟 |
| 6 | http://arxiv.org/abs/2603.01548v1 | Graph-Based Self-Healing Tool Routing for Cost-Efficient LLM Agents | 自愈路由架构，将控制流决策视为路由，工具失败时自动重计算路径。 | 解决路由每决策经 LLM 成本高及预编码工作流图在复合失败下脆弱问题。 | 工具使用 LLM 代理与容错编排 |
| 7 | http://arxiv.org/abs/2603.02816v2 | BrandFusion: A Multi-Agent Framework for Seamless Brand Integration in Text-to-Video Generation | 提出双阶段多智能体框架，离线构建品牌库，在线五代理协同优化提示词。 | 解决文本生成视频中品牌植入的语义保真与自然度问题。 | 文本生成视频 (T2V) 商业内容 |
| 8 | http://arxiv.org/abs/2603.02888v1 | LLandMark: A Multi-Agent Framework for Landmark-Aware Multimodal Interactive Video Retrieval | 模块化多智能体框架，含地标知识代理与 LLM 辅助图像检索流水线。 | 解决复杂查询下的多模态视频检索与文化地标理解问题。 | 多模态视频检索系统 |
| 9 | http://arxiv.org/abs/2603.02909v2 | SpecLoop: An Agentic RTL-to-Specification Framework with Formal Verification Feedback Loop | 引入形式化验证反馈循环，迭代重构 RTL 以验证规格书一致性。 | 解决 RTL 实现缺乏一致规格书及设计意图捕捉不准问题。 | 芯片设计与形式化验证 |
| 10 | http://arxiv.org/abs/2603.03018v1 | REGAL: A Registry-Driven Architecture for Deterministic Grounding of Agentic AI in Enterprise Telemetry | 注册表驱动架构，将确定性遥测计算作为原语，LLM 操作有界动作空间。 | 解决企业遥测中模型上下文有限、语义概念本地化及接口演变问题。 | 企业工程遥测与自动化 |
| 11 | http://arxiv.org/abs/2603.03589v2 | stratum: A System Infrastructure for Massive Agent-Centric ML Workloads | 统一系统基础设施，解耦管道执行与规划，编译优化执行图。 | 解决现有 Python 生态不支持大规模代理管道搜索及执行效率问题。 | 大规模代理中心 ML 工作负载 |
| 12 | http://arxiv.org/abs/2603.01661v1 | HeRo: Adaptive Orchestration of Agentic RAG on Heterogeneous Mobile SoC | 基于性能模型的轻量级在线调度器，结合形状感知分区与带宽感知并发控制。 | 解决移动端异构 SoC 上 Agentic RAG 多阶段工作流延迟高与调度无效问题。 | 移动端 Agentic RAG 部署 |
| 13 | http://arxiv.org/abs/2603.02176v1 | Organizing, Orchestrating, and Benchmarking Agent Skills at Ecosystem Scale | 技能管理阶段组织技能为能力树，解决任务阶段通过 DAG 管道检索编排执行。 | 解决如何有效利用、管理及扩展 Agent 技能生态系统的核心问题。 | Agent 技能生态系统 |
| 14 | http://arxiv.org/abs/2603.02206v2 | VoiceAgentRAG: Solving the RAG Latency Bottleneck in Real-Time Voice Agents Using Dual-Agent Architectures | 双 Agent 记忆路由器，后台 Slow Thinker 预取，前台 Fast Talker 读缓存。 | 解决实时语音 Agent 中 RAG 检索延迟瓶颈的问题。 | 实时语音 Agent |
| 15 | http://arxiv.org/abs/2603.02491v1 | What Capable Agents Must Know: Selection Theorems for Robust Decision-Making under Uncertainty | 证明定量选择定理，低平均 case  regret 迫使 Agent 实现预测性结构化内部状态。 | 解决最优控制可实现但此类表示是否必要尚不清楚的理论问题。 | 不确定下鲁棒决策 Agent |
| 16 | http://arxiv.org/abs/2603.02681v1 | VisionCreator: A Native Visual-Generation Agentic Model with Understanding, Thinking, Planning and Creation | 统一 UTPC 能力的端到端可学习框架，渐进专业化训练及虚拟 RL 优化。 | 解决视觉内容创建任务需 nuanced 理解设计 convention 及工作流，通用模型挑战大的问题。 | 视觉生成 Agent 模型 |
| 17 | http://arxiv.org/abs/2603.05413v2 | Building Enterprise Realtime Voice Agents from Scratch: A Technical Tutorial | 构建级联流式流水线实现自托管实时语音 Agent | 解决自托管端到端语音模型延迟过高问题 | 企业级实时语音交互系统 |
| 18 | http://arxiv.org/abs/2603.05614v1 | Real-Time AI Service Economy: A Framework for Agentic Computing Across the Continuum | 提出混合管理架构稳定去中心化资源分配 | 解决复杂依赖图导致的价格波动与分配退化 | 设备 - 边缘 - 云 continuum 上的实时 AI 服务 |
| 19 | http://arxiv.org/abs/2603.05743v1 | Let's Talk, Not Type: An Oral-First Multi-Agent Architecture for Guaraní | 提出口语优先多 Agent 架构解耦理解与状态 | 解决文本优先设计忽视口语语言与原住民社区 | 瓜拉尼语等口语语言交互 |
| 20 | http://arxiv.org/abs/2603.06007v1 | MASFactory: A Graph-centric Framework for Orchestrating LLM-Based Multi-Agent Systems with Vibe Graphing | 引入 Vibe Graphing 将自然语言意图编译为工作流图 | 解决复杂图工作流手动实现 effort 大与复用难 | LLM 多 Agent 系统编排 |
| 21 | http://arxiv.org/abs/2603.06394v1 | Talk Freely, Execute Strictly: Schema-Gated Agentic AI for Flexible and Reproducible Scientific Workflows | 提出模式门控编排分离对话与执行权限 | 解决科学工作流中确定性与灵活性冲突 | 工业研发科学计算工作流 |
| 22 | http://arxiv.org/abs/2603.04241v1 | Agentics 2.0: Logical Transduction Algebra for Agentic Data Workflows | 逻辑转导代数将 LLM 推理形式化为类型语义转换，支持无状态异步并行执行。 | 解决 Agentic AI 企业部署中可靠性、可扩展性与可观察性需求。 | 企业级数据工作流 |
| 23 | http://arxiv.org/abs/2603.13327v1 | DOVA: Deliberation-First Multi-Agent Orchestration for Autonomous Research Automation | 深思优先编排，显式元推理先于工具调用，混合协作推理与自适应多层思考。 | 解决单智能体系统面对复杂研究任务时多源合成与对抗验证局限性。 | 自主研究自动化平台 |
| 24 | http://arxiv.org/abs/2603.05069v2 | Jagarin: A Three-Layer Architecture for Hibernating Personal Duty Agents on Mobile | 三层架构解决移动部署悖论，DAWN 计算紧急度，ARIA 路由邮箱，ACE 协议通信。 | 解决移动个人智能体持久后台执行耗电与纯反应式错过时间敏感义务矛盾。 | 移动个人职责智能体 |
| 25 | http://arxiv.org/abs/2603.07106v1 | AutoUE: Automated Generation of 3D Games in Unreal Engine via Multi-Agent Systems | 提出多智能体系统AutoUE，结合检索增强生成与游戏设计模式，实现3D游戏端到端生成。 | 解决商业引擎中3D游戏生成工作流复杂、工具幻觉及代码鲁棒性问题。 | 3D游戏开发/Unreal Engine |
| 26 | http://arxiv.org/abs/2603.08755v1 | Turn: A Language for Agentic Computation | 提出编译型 actor 编程语言 Turn，引入认知类型安全及基于能力的身份系统等语言级构造。 | 解决现有框架将关键不变量作为应用层约定而非语言保证导致的可靠性问题。 | 智能体软件开发/编程语言 |
| 27 | http://arxiv.org/abs/2603.07379v1 | "SoK: Agentic Retrieval-Augmented Generation (RAG): Taxonomy, Architectures, Evaluation, and Research Directions" | 形式化智能体检索生成循环为有限 horizon POMDP，提供统一框架、分类及模块化架构分解。 | 解决当前研究缺乏对Agentic RAG作为序列决策系统的系统理解及评估不一致问题。 | 检索增强生成系统 |
| 28 | http://arxiv.org/abs/2603.07416v1 | DualSpec: Accelerating Deep Research Agents via Dual-Process Action Speculation | 提出异构推测框架DualSpec，基于动作异质性利用轻量级语义验证器重叠执行与推理。 | 解决深度研究智能体因 extensive 推理和频繁工具使用导致的高端到端延迟问题。 | 深度研究智能体/信息检索 |
| 29 | http://arxiv.org/abs/2603.18030v1 | Quine: Realizing LLM Agents as Native POSIX Processes | 提出运行时架构Quine，将LLM智能体实现为原生POSIX进程，映射身份、接口及生命周期。 | 解决当前框架在应用层实现隔离调度通信，而非利用成熟操作系统机制的问题。 | 智能体运行时/操作系统 |
| 30 | http://arxiv.org/abs/2603.07609v1 | From Logs to Agents: Reconstructing High-Level Creative Workflows from Low-Level Raw System Traces | 提出方法解析原始日志为结构化行为工作流图，抽象低级事件为高级行为令牌。 | 解决当前CST生成大量低级日志数据难以解释为创意意图，阻碍未来智能体理解用户的问题。 | 创意支持工具/工作流分析 |
| 31 | http://arxiv.org/abs/2603.07728v1 | A Novel Multi-Agent Architecture to Reduce Hallucinations of Large Language Models in Multi-Step Structural Modeling | 提出 novel 多智能体架构自动化结构建模分析，并行操作节点元素智能体减少幻觉积累。 | 解决现有LLM处理多步结构建模因长序列操作中频繁幻觉及错误积累受限的问题。 | 结构工程建模/OpenSees |
| 32 | http://arxiv.org/abs/2603.08036v2 | "Samyama: A Unified Graph-Vector Database with In-Database Optimization, Agentic Enrichment, and Hardware Acceleration" | 提出高性能图向量数据库Samyama，统一工作负载，集成优化求解器及LLM自主图扩展 Agentic Enrichment。 | 解决现代数据架构 fragmented 跨图数据库向量存储等导致复杂ETL管道及同步 overhead 问题。 | 数据库系统/图向量存储 |
| 33 | http://arxiv.org/abs/2603.13417v1 | Bridging Protocol and Production: Design Patterns for Deploying AI Agents with Model Context Protocol | 提出CABP、ATBA、SERF三种生产级机制 | MCP协议缺乏身份传播、预算分配、错误语义 | 企业级AI Agent部署 |
| 34 | http://arxiv.org/abs/2603.12823v1 | Adaptive Vision-Language Model Routing for Computer Use Agents | 轻量语义路由层，成本-准确性权衡策略 | CUA系统固定使用单一VLM模型效率低 | Computer Use Agents |
| 35 | http://arxiv.org/abs/2603.12933v1 | Efficient and Interpretable Multi-Agent LLM Routing via Ant Colony Optimization | 蚁群优化建模路由，任务特异性信息素专家 | 现有路由依赖昂贵LLM选择器或静态策略 | 多Agent系统路由 |
| 36 | http://arxiv.org/abs/2603.13443v1 | NormCode Canvas: Making LLM Agentic Workflows Development Sustainable via Case-Based Reasoning | 两级案例推理，编译器验证作用域规则 | 标准编排框架检索不可靠、失败不可定位 | 多步LLM工作流开发 |
| 37 | http://arxiv.org/abs/2603.13110v1 | AgentRM: An OS-Inspired Resource Manager for LLM Agent Systems | OS启发资源管理器，MLFQ调度+三层上下文生命周期 | Agent系统调度失败和上下文退化问题 | LLM Agent系统中间件 |
| 38 | http://arxiv.org/abs/2603.13605v1 | Orla: A Library for Serving LLM-Based Multi-Agent Systems | 服务层抽象，阶段映射器+工作流编排器+记忆管理器 | 开发者手动编排代码与LLM服务引擎 | LLM多Agent系统服务 |
| 39 | http://arxiv.org/abs/2603.10085v1 | KernelSkill: A Multi-Agent Framework for GPU Kernel Optimization | 提出双层级记忆架构，协调具有长短期记忆的智能体 | 解决 LLM 优化管道依赖隐式启发式导致效率低的问题 | GPU 内核优化 |
| 40 | http://arxiv.org/abs/2603.10249v2 | DUCTILE: Agentic LLM Orchestration of Engineering Analysis in Product Development Practice | 分离自适应编排与确定性执行，代理解释文档实践 | 解决工程分析自动化依赖 rigid 接口易随产品演变断裂 | 产品开发工程分析 |
| 41 | http://arxiv.org/abs/2603.10342v1 | AgentServe: Algorithm-System Co-Design for Efficient Agentic AI Serving on a Consumer-Grade GPU | 隔离 prefill 与 decode，动态预算分配 GPU 资源 | 解决异构请求重叠导致 head-of-line 阻塞 destabilize 性能 | 消费级 GPU 上的 Agentic AI 服务 |
| 42 | http://arxiv.org/abs/2603.10779v3 | A Control-Theoretic Foundation for Agentic Systems | 控制理论框架分析嵌入反馈 loops 的 agentic 系统 | 解决 AI 代理在安全关键应用中适应控制器参数形式化 | 控制理论下的智能体系统 |
| 43 | http://arxiv.org/abs/2603.11445v2 | Verified Multi-Agent Orchestration: A Plan-Execute-Verify-Replan Framework for Complex Query Resolution | 验证驱动迭代循环，分解为 DAG 子问题并行执行，LLM 验证器协调重规划 | 复杂查询解决中缺乏 orchestration 级验证机制，答案完整性与质量难保 | 复杂市场研究查询解决 |
| 44 | http://arxiv.org/abs/2603.11866v1 | Derain-Agent: A Plug-and-Play Agent Framework for Rainy Image Restoration | 插件式细化框架，规划网络智能调度恢复工具序列，强度调制机制自适应应用 | 现有模型采用静态推理范式，无法适应真实世界雨的复杂耦合退化 | 雨天图像恢复与动态处理 |
| 45 | http://arxiv.org/abs/2603.13774v1 | AgenticScholar: Agentic Data Management with Pipeline Orchestration for Scholarly Corpora | 集成结构感知知识表示与混合查询规划层，自主翻译 NL 查询为 DAG 计划 | 现有 RAG 系统无法同时支持多种 scholarly 查询类型 | 学术数据管理/知识发现 |
| 46 | http://arxiv.org/abs/2603.13906v1 | ATCC: Adaptive Concurrency Control for Unforeseen Agentic Transactions | 自适应并发控制，动态调整乐观或悲观执行，平衡阻塞与中止成本 | 智能体事务具有不可预见性，传统并发控制假设失效 | 数据库/智能体事务 |
| 47 | http://arxiv.org/abs/2603.14011v1 | Sovereign-OS: A Charter-Governed Operating System for Autonomous AI Agents with Verifiable Fiscal Discipline | 治理优先操作系统，通过宪章定义任务范围与财政边界，审计验证输出 | 自主经济智能体缺乏运行时治理与财政约束 | 自主智能体/操作系统 |
| 48 | http://arxiv.org/abs/2603.14703v1 | Beyond Local Code Optimization: Multi-Agent Reasoning for Software System Optimization | 提出多智能体框架，整合控制流与架构依赖信号支持系统级性能推理 | 局部代码优化无法捕捉系统级性能交互与架构瓶颈 | 微服务系统性能优化 |
| 49 | http://arxiv.org/abs/2603.15690v1 | Loosely-Structured Software: Engineering Context, Structure, and Evolution Entropy in Runtime-Rewired Multi-Agent Systems | 提出松散结构软件(LSS)框架，管理运行时熵与动态绑定 | 多智能体系统规模扩大导致的上下文压力与协调错误 | 自主多智能体系统架构 |
| 50 | http://arxiv.org/abs/2603.15021v1 | Describing Agentic AI Systems with C4: Lessons from Industry Projects | 提供面向风格的建模词汇与分层描述技术，适配C4模型 | 代理系统文档缺乏捕捉风格定义关注点的系统方法 | 工业级代理系统文档化 |
| 51 | http://arxiv.org/abs/2603.15183v1 | Token Coherence: Adapting MESI Cache Protocols to Minimize Synchronization Overhead in Multi-Agent LLM Systems | 构造Artifact Coherence System，证明Token Coherence定理降低同步成本 | 多智能体编排下 naive broadcast 导致的三重乘法同步开销 | 多智能体LLM系统同步优化 |
| 52 | http://arxiv.org/abs/2603.15371v1 | Brain-Inspired Graph Multi-Agent Systems for LLM Reasoning | 提出BIGMAS，专用代理组织为动态有向图节点，通过共享工作空间协调 | 模型级推理扩展不足，复杂任务准确率崩溃 | 复杂多步推理任务 |
| 53 | http://arxiv.org/abs/2603.15473v1 | Agent Lifecycle Toolkit (ALTK): Reusable Middleware Components for Robust AI Agents | 开源模块化中间件组件集合，系统处理代理全生命周期故障模式 | 代理框架让构建者临时处理故障模式，导致脆弱且难维护 | 企业级可靠AI代理构建 |
| 54 | http://arxiv.org/abs/2603.15900v1 | The Internet of Physical AI Agents: Interoperability, Longevity, and the Cost of Getting It Wrong | 提出架构蓝图涵盖代理身份、安全通信、语义互操作性与策略治理 | 将快速进化AI能力嵌入长期物理基础设施引入互操作性与生命周期风险 | 物理AI代理互联网架构 |
| 55 | http://arxiv.org/abs/2603.17307v1 | Symphony: A Cognitively-Inspired Multi-Agent System for Long-Video Understanding | 模仿人类认知模式，分解长视频为细粒度子任务，增强深度推理协作 | 长视频理解中高信息密度与扩展时间跨度的推理挑战 | 长视频理解任务 |
| 56 | http://arxiv.org/abs/2603.17418v1 | PowerDAG: Reliable Agentic AI System for Automating Distribution Grid Analysis | 自适应检索与即时监督两种主动机制，动态选择相关标注示例 | 最先进Agent系统在自动化复杂工程工作流中的可靠性挑战 | 配电网分析 |
| 57 | http://arxiv.org/abs/2603.17895v1 | A Creative Agent is Worth a 64-Token Template | 创意Agent Tokenization框架，创意分词器生成可复用token模板注入创意语义 | 文本到图像模型创意受离散自然语言提示限制，推理方法成本高 | 文本到图像生成 |
| 58 | http://arxiv.org/abs/2603.18627v1 | Agentic Flow Steering and Parallel Rollout Search for Spatially Grounded Text-to-Image Generation | 无训练闭环并行展开搜索与流转向机制，VLM作为语义批评者诊断中间潜变量 | 精确文本到图像生成受静态文本编码器关系推理有限与开环采样误差累积阻碍 | 空间接地文本到图像生成 |
| 59 | http://arxiv.org/abs/2603.18897v1 | Act While Thinking: Accelerating LLM Agents via Pattern-Aware Speculative Tool Execution | 模式感知推测工具执行方法通过推测隐藏工具延迟，利用稳定应用级控制流 | Agent严格串行LLM-工具循环中LLM每步需等待外部工具执行引入延迟瓶颈 | LLM Agent服务性能 |
| 60 | http://arxiv.org/abs/2603.18916v1 | Agentic Business Process Management: A Research Manifesto | 阐述Agentic BPM概念基础，引入核心抽象与架构元素实现APM系统 | 传统自动化导向BPM向自主性受约束对齐并通过流程意识可操作化系统转变 | 组织业务流程管理 |
| 61 | http://arxiv.org/abs/2603.16020v1 | IRAM-Omega-Q: A Computational Architecture for Uncertainty Regulation in Artificial Agents | 建模内部调节为量子态闭环控制，管理不确定性与稳定性 | 解决智能体内部调节不透明及稳定性管理问题 | 智能体不确定性调节 |
| 62 | http://arxiv.org/abs/2603.16021v2 | Interpretable Context Methodology: Folder Structure as Agentic Architecture | 用文件系统结构替代框架级编排，实现可解释上下文管理 | 解决顺序工作流中多智能体框架工程开销过大的问题 | 顺序工作流编排 |
| 63 | http://arxiv.org/abs/2603.16104v1 | Efficient LLM Serving for Agentic Workflows: A Data Systems Perspective | 工作流感知服务框架，将 LLM 调用视为算子进行查询优化 | 解决现有服务系统忽略跨调用依赖导致效率低下的问题 | LLM 服务工作流 |
| 64 | http://arxiv.org/abs/2603.17112v1 | Cascade-Aware Multi-Agent Routing: Spatio-Temporal Sidecars and Geometry-Switching | 级联感知路由，结合时空边车与几何切换 mitigating 失败传播 | 解决调度器几何盲视导致树状委托失败级联问题 | 多 Agent 路由 |

[返回目录](#目录)

<a id="cat-02"></a>

## Agent仿真与社会模拟

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2603.00858v1 | Artificial Superintelligence May be Useless: Equilibria in the Economy of Multiple AI Agents | 基于马尔可夫链建模多 AI 代理经济博弈，推导长期效用均衡条件。 | 揭示超级智能代理在特定经济均衡下可能无法贡献效用。 | 多代理经济系统与交易市场 |
| 2 | http://arxiv.org/abs/2603.01024v1 | SimAB: Simulating A/B Tests with Persona-Conditioned AI Agents for Rapid Design Evaluation | 利用角色条件 AI 代理模拟 A/B 测试，生成用户偏好与理由。 | 解决真实流量 A/B 测试迭代慢、隐私敏感及低流量页面难测试问题。 | 产品设计与用户体验快速评估 |
| 3 | http://arxiv.org/abs/2603.01189v1 | Agent-Based Simulation of Trust Development in Human-Robot Teams: An Empirically-Validated Framework | 基于 NetLogo 的实证模型，模拟人机团队信任动态、 workload 分布与绩效。 | 解决信任前因类别验证不足及信任 - 绩效解耦诊断缺失的问题。 | 人机团队协作与信任管理 |
| 4 | http://arxiv.org/abs/2603.01401v1 | Exploration enhances cooperation in the multi-agent communication system | 两阶段演化博弈模型，集成信号与捐赠博弈，发现最优探索率最大化合作。 | 解决现有理论框架排除随机探索，未探究其对系统性能功能影响的问题。 | 多代理通信系统与合作协议设计 |
| 5 | http://arxiv.org/abs/2603.01554v1 | S5-HES Agent: Society 5.0-driven Agentic Framework to Democratize Smart Home Environment Simulation | 代理仿真框架，协调专用代理通过可互换 LLM，实现自然语言驱动配置。 | 解决现有模拟器需专业技术、适应性低及缺乏自动进化，无法满足 Society 5.0 需求。 | 智能家居环境模拟与社会 5.0 研究 |
| 6 | http://arxiv.org/abs/2603.03140v2 | How to Model AI Agents as Personas?: Applying the Persona Ecosystem Playground to 41,300 Posts on Moltbook for Behavioral Insights | 应用 Persona 生态游乐场生成验证对话 persona，分析行为多样性。 | 解决社交平台上 AI 代理行为多样性理解与特征化方法缺失问题。 | 社交平台 AI 代理行为分析 |
| 7 | http://arxiv.org/abs/2603.03526v1 | Multi-Agent Influence Diagrams to Hybrid Threat Modeling | 统一混合威胁建模方法，通过多智能体影响图框架澄清对策影响。 | 解决混合威胁模糊性、跨域性及对策如何塑造对手行为不确定性。 | 网络安全与混合威胁建模 |
| 8 | http://arxiv.org/abs/2603.03555v1 | Molt Dynamics: Emergent Social Phenomena in Autonomous AI Agent Populations | 观察 77 万自主代理交互，表征角色专业化与信息传播动态。 | 解决大规模自主代理群体中涌现协调动态与行为多样性理解缺失。 | 大规模自主代理社会模拟 |
| 9 | http://arxiv.org/abs/2603.16899v1 | Capability-Priced Micro-Markets: A Micro-Economic Framework for the Agentic Web over HTTP 402 | 提出能力定价微市场框架，整合安全能力、微支付与谈判协议。 | 解决去中心化代理生态中经济协调及最小人类监督交易挑战。 | 代理网络经济与交易 |
| 10 | http://arxiv.org/abs/2603.03671v1 | Is an investor stolen their profits by mimic investors? Investigated by an agent-based model | 构建代理基人工金融市场模型，增加基本与技术代理调查收益。 | 解决投资者关于同策略增加是否减少利润的冲突论点未调查问题。 | 金融市场仿真与投资策略 |
| 11 | http://arxiv.org/abs/2603.02711v1 | A Natural Language Agentic Approach to Study Affective Polarization | 利用 LLM 构建虚拟社区，Agent 参与讨论，操作化 affective polarization 定义。 | 解决现实研究 scope 有限及模拟研究缺乏高质量训练数据，难以 formalize 定义的问题。 | 社交媒体情感极化研究 |
| 12 | http://arxiv.org/abs/2603.03390v1 | Multi-Agent-Based Simulation of Archaeological Mobility in Uneven Landscapes | 结合全局路径规划与局部动态适应，RL 使 Agent 响应动态障碍及交互。 | 解决从静态考古证据重构移动、运动及交互过程困难的问题。 | 考古景观移动模拟 |
| 13 | http://arxiv.org/abs/2603.04855v2 | HACHIMI: Scalable and Controllable Student Persona Generation via Orchestrated Agents | 多智能体 Propose-Validate-Revise 框架，生成理论对齐且配额可控的学生人设。 | 解决教育 LLM 学生人设依赖临时提示或缺乏教育理论与分布控制问题。 | 教育 LLM/社会科学模拟 |
| 14 | http://arxiv.org/abs/2603.07360v1 | The Yerkes-Dodson Curve for AI Agents: Emergent Cooperation Under Environmental Pressure in Multi-Agent LLM Simulations | 首次系统研究LLM多智能体系统中压力与性能关系，发现合作行为遵循倒U型曲线。 | 解决设计环境以最大化AI智能体 emergent 行为发展速率的开放性问题。 | 多智能体仿真/群体行为 |
| 15 | http://arxiv.org/abs/2603.07880v1 | What Do AI Agents Talk About? Emergent Communication Structure in the First AI-Only Social Network | 分析首个AI-only社交网络Moltbook，表征AI到AI话语的主题、情感及结构属性。 | 解决自主AI智能体大规模相互沟通时 emergent 话语系统类型未知的开放性问题。 | 智能体社会模拟/通信分析 |
| 16 | http://arxiv.org/abs/2603.12129v1 | Increasing intelligence in AI agents can worsen collective outcomes | 揭示AI Agent群体行为四变量：天性、培养、文化、稀缺 | 资源稀缺时AI多样性与RL加剧系统过载 | 多Agent资源竞争系统 |
| 17 | http://arxiv.org/abs/2603.12412v1 | Macroeconomic Forecasting from Input-Output Tables Alone: A Darwinian Agent-Based Approach with FIGARO Data | 达尔文Agent仿真器从I-O表预测GDP | 宏观经济预测依赖外部参数和时间序列 | 宏观经济预测系统 |
| 18 | http://arxiv.org/abs/2603.12559v1 | Large Language Models as Delivery Rider: Generating Instant Food Delivery Riders' Routing Decision with LLM Agent Framework | 基于真实轨迹聚类的经验Persona，CoT路由决策 | 缺乏对动态交互系统中Agent群体建模 | 即时配送骑手仿真 |
| 19 | http://arxiv.org/abs/2603.16916v1 | Noncooperative Human-AI Agent Dynamics | 结合 Prospect Theory 建模人类，EU 建模 AI，模拟非合作博弈 | 探索混合种群（人类 vs AI）竞争中的 emergent 行为 | 人机非合作博弈仿真 |
| 20 | http://arxiv.org/abs/2603.10743v1 | Scaling and Trade-offs in Multi-agent Autonomous Systems | 利用量纲分析与数据缩放 collapse 性能数据到缩放函数 | 解决自主无人机群设计空间 vast 难以预测 success 边界 | 多智能体自主系统仿真 |
| 21 | http://arxiv.org/abs/2603.11245v1 | Mind the Sim2Real Gap in User Simulation for Agentic Tasks | 形式化用户模拟中的 Sim2Real 差距，提出 User-Sim Index 量化模拟真实性 | LLM 模拟器常假设忠实于人类行为，缺乏严格验证导致评估偏差 | 智能体任务中的用户行为模拟 |
| 22 | http://arxiv.org/abs/2603.11375v1 | How do AI agents talk about science and research? An exploration of scientific discussions on Moltbook using BERTopic | 分析 OpenClaw 智能体在 Moltbook 上的科学讨论，提取主题并关联相关性 | 缺乏对 AI 智能体如何谈论科学及研究主题的相关性探索 | AI 智能体社区与科学 discourse |
| 23 | http://arxiv.org/abs/2603.11955v1 | PersonaTrace: Synthesizing Realistic Digital Footprints with LLM Agents | 从结构化用户 profile 开始，生成多样 plausible 用户事件序列及对应数字 artifacts | 该领域研究常受限于多样且可访问数据的稀缺，缺乏真实数字足迹数据 | 数字足迹合成与行为研究 |
| 24 | http://arxiv.org/abs/2603.11974v1 | Normative Common Ground Replication (NormCoRe): Replication-by-Translation for Studying Norms in Multi-agent AI | 方法论框架将人类受试者实验设计系统翻译至 MAAI 环境，映射结构层 | 现有实证方法常将规范视为对齐目标，隐含假设人类与 AI 智能体等价 | 多智能体 AI 中的规范研究与复制 |
| 25 | http://arxiv.org/abs/2603.13876v1 | How do Role Models Shape Collective Morality? Exemplar-Driven Moral Learning in Multi-Agent Simulation | 基于 LLM 的多智能体模拟，代理通过四阶段认知循环交互适应价值观 | 探索榜样如何塑造集体道德及身份驱动 conformity | 社会模拟/道德学习 |
| 26 | http://arxiv.org/abs/2603.13890v1 | Beyond Self-Interest: Modeling Social-Oriented Motivation for Human-like Multi-Agent Interactions | 引入自主社会价值导向代理，动态计算 SVO 平衡欲望满足与社会对齐 | 现有方法缺乏在类人多智能体交互中建模社会动机的机制 | 社会模拟/人机交互 |
| 27 | http://arxiv.org/abs/2603.14997v1 | OrgForge: A Multi-Agent Simulation Framework for Verifiable Synthetic Corporate Corpora | 强制物理 - 认知边界，生成可验证的合成企业语料 | 现有语料缺乏地面真值、时间结构与跨工件属性 | 检索增强生成(RAG)评估语料 |
| 28 | http://arxiv.org/abs/2603.15903v1 | Agent-based imitation dynamics can yield efficiently compressed population-level vocabularies | 统一进化博弈论与信息瓶颈框架，展示近优压缩如何通过模仿动态产生 | 语言词汇效率优化的底层社会动态未知 | 语言演化与词汇压缩模拟 |
| 29 | http://arxiv.org/abs/2603.17694v1 | MALLES: A Multi-agent LLMs-based Economic Sandbox with Consumer Preference Alignment | 偏好学习范式经济对齐LLM，平均场机制建模产品环境与客户群体动态交互 | 高维多模态环境中现代决策受Agent异质性与组合数据稀疏性挑战 | 实体经济决策模拟 |
| 30 | http://arxiv.org/abs/2603.18333v1 | Trajectory Landscapes for Therapeutic Strategy Design in Agent-Based Tumor Microenvironment Models | 降阶模拟驱动框架使用ABM衍生轨迹集合，学习概率马尔可夫状态模型 | 基于Agent模型高维状态空间与不确定参数化使直接控制设计困难 | 肿瘤微环境治疗策略 |
| 31 | http://arxiv.org/abs/2603.16128v2 | Social Simulacra in the Wild: AI Agent Communities on Moltbook | 大规模实证比较 AI 智能体与人类在线社区动态 | 解决缺乏 AI 智能体社区动力学实证基础的问题 | 在线社区仿真 |

[返回目录](#目录)

<a id="cat-03"></a>

## Agent评测与基准

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2603.00873v1 | MC-Search: Evaluating and Enhancing Multimodal Agentic Search with Structured Long Reasoning Chains | 首创带长推理链标注的多模态代理搜索基准，引入过程级评估指标。 | 解决现有基准缺乏自适应规划与多模态推理评估的问题。 | 多模态大模型与检索增强生成 |
| 2 | http://arxiv.org/abs/2603.01045v1 | Silo-Bench: A Scalable Environment for Evaluating Distributed Coordination in Multi-Agent LLM Systems | 角色无关基准，评估多代理 LLM 系统在分布式信息下的协调与推理能力。 | 揭示多代理系统在信息整合阶段的通信 - 推理差距与协调开销。 | 分布式多代理 LLM 系统 |
| 3 | http://arxiv.org/abs/2603.01152v1 | DeepResearch-9K: A Challenging Benchmark Dataset of Deep-Research Agent | 构建大规模深度研究数据集，包含多难度问题与高质量搜索轨迹。 | 解决缺乏大规模高难度真实世界数据集及开源训练框架的问题。 | 深度研究智能体训练与评估 |
| 4 | http://arxiv.org/abs/2603.01203v2 | How Well Does Agent Development Reflect Real-World Work? | 系统分析基准实例与真实工作分布的对齐度，提出覆盖、 realism 与粒度原则。 | 解决代理开发基准与人类劳动力及经济价值集中类别存在 substantial 错配。 | 代理基准设计与劳动力市场分析 |
| 5 | http://arxiv.org/abs/2603.01357v1 | ASTRA-bench: Evaluating Tool-Use Agent Reasoning and Action Planning with Personal User Context | 统一时间演化个人上下文与交互工具箱，生成基于生活事件的场景。 | 解决现有基准缺乏上下文且单轮，无法评估 messy 个人上下文 grounding 能力。 | 上下文感知 AI 助手与工具使用 |
| 6 | http://arxiv.org/abs/2603.03116v1 | Beyond Task Completion: Revealing Corrupt Success in LLM Agents through Procedure-Aware Evaluation | 提出过程感知评估 (PAE)，形式化代理过程为结构化观察。 | 解决当前基准仅评估任务完成而忽略过程一致性与腐败成功问题。 | LLM 智能体能力评估 |
| 7 | http://arxiv.org/abs/2603.03194v1 | BeyondSWE: Can Current Code Agent Survive Beyond Single-Repo Bug Fixing? | 引入 BeyondSWE 基准，扩展评估范围至跨仓库推理与全仓库生成。 | 解决代码代理基准仅评估窄范围仓库特定修复忽略现实挑战问题。 | 代码智能体能力评估 |
| 8 | http://arxiv.org/abs/2603.03761v1 | AgentSelect: Benchmark for Narrative Query-to-Agent Recommendation | 基准将代理选择重构为叙事查询到代理推荐，统一交互数据。 | 解决 LLM 领导者板碎片化及缺乏查询条件监督推荐配置问题。 | 代理配置推荐与评估 |
| 9 | http://arxiv.org/abs/2603.03823v3 | SWE-CI: Evaluating Agent Capabilities in Maintaining Codebases via Continuous Integration | 首个基于 CI 循环的仓库级基准，转向动态长期可维护性评估。 | 解决静态一次性修复范式无法捕捉成熟软件开发长期迭代问题。 | 代码库维护代理能力评估 |
| 10 | http://arxiv.org/abs/2603.01952v1 | LiveCultureBench: a Multi-Agent, Multi-Cultural Benchmark for Large Language Models in Dynamic Social Simulations | 多文化动态基准，嵌入 LLM 为 Agent 于模拟城镇，评估任务完成及规范遵守。 | 解决现有评估聚焦任务成功而非文化适宜性或评估者可靠性的问题。 | 社会模拟中的 LLM Agent |
| 11 | http://arxiv.org/abs/2603.02297v1 | ZeroDayBench: Evaluating LLM Agents on Unseen Zero-Day Vulnerabilities for Cyberdefense | 基准测试 LLM 代理在开源代码库中发现并修补 22 个 novel 关键漏洞的能力。 | 解决估计 Agent 在主动网络防御领域能力及行为模式缺乏评估标准的问题。 | 网络防御 Agent |
| 12 | http://arxiv.org/abs/2603.02586v1 | LiveAgentBench: Comprehensive Benchmarking of Agentic Systems Across 104 Real-World Challenges | 社会感知驱动数据生成方法，确保问题现实相关性、任务复杂性及结果可验证性。 | 解决现有基准未能准确代表现实用户任务，缺乏实际性能评估的问题。 | 通用 AI 代理评估 |
| 13 | http://arxiv.org/abs/2603.02601v1 | AgentAssay: Token-Efficient Regression Testing for Non-Deterministic AI Agent Workflows | 随机三值 verdicts，五维覆盖指标，行为 fingerprinting 映射执行迹到紧凑向量。 | 解决缺乏原则性方法验证 Agent 在 prompt、工具等变化后未回归的问题。 | 非确定性 AI 代理工作流测试 |
| 14 | http://arxiv.org/abs/2603.02788v2 | Agentified Assessment of Logical Reasoning Agents | 评估 Agent 发布任务、执行预算、解析输出及记录结构化失败类型，标准化接口。 | 解决评估本身需 reproducible、auditable 及 robust 到执行失败的问题。 | 逻辑推理 Agent 评估 |
| 15 | http://arxiv.org/abs/2603.05578v1 | Tool-Genesis: A Task-Driven Tool Creation Benchmark for Self-Evolving Language Agent | 提出 Tool-Genesis 基准评估工具创建能力 | 解决现有基准依赖预定义规格限制扩展性 | 自进化语言 Agent 工具创建 |
| 16 | http://arxiv.org/abs/2603.05484v1 | Towards Multimodal Lifelong Understanding: A Dataset and Agentic Baseline | 引入 MM-Lifelong 数据集及 ReMA 基线 | 解决视频理解中工作记忆瓶颈与全局定位崩溃 | 多模态终身理解与长视频分析 |
| 17 | http://arxiv.org/abs/2603.05764v1 | TML-Bench: Benchmark for Data Science Agents on Tabular ML Tasks | 引入 TML-Bench 评估数据科学 Agent 端到端正确性 | 解决 Kaggle 风格任务中 Agent 可靠性评估缺失 | 表格机器学习任务自动化 |
| 18 | http://arxiv.org/abs/2603.05910v1 | The World Won't Stay Still: Programmable Evolution for Agent Benchmarks | 提出 ProEvolve 框架使环境进化可编程 | 解决静态基准忽视现实世界动态变化问题 | Agent 适应性与鲁棒性评估 |
| 19 | http://arxiv.org/abs/2603.05912v1 | DeepFact: Co-Evolving Benchmarks and Agents for Deep Research Factuality | 提出审计后评分机制协同进化基准与 Agent | 解决深度研究报告事实性验证基准缺失 | 深度研究事实性核查 |
| 20 | http://arxiv.org/abs/2603.06739v2 | ResearchEnvBench: Benchmarking Agents on Environment Synthesis for Research Code Execution | 引入 ResearchEnvBench 评估环境合成能力 | 解决研究代码执行中依赖解析与环境配置难题 | 科学研究的自主代码执行 |
| 21 | http://arxiv.org/abs/2603.06874v1 | LieCraft: A Multi-Agent Framework for Evaluating Deceptive Capabilities in Language Models | 开发 LieCraft 沙盒测量 LLM 欺骗能力 | 解决现有游戏基评估缺乏现实相关性 | 语言模型欺骗能力评估 |
| 22 | http://arxiv.org/abs/2603.04370v1 | $τ$-Knowledge: Evaluating Conversational Agents over Unstructured Knowledge | 扩展τ-Bench，评估智能体在非结构化知识环境中协调工具与知识的能力。 | 解决现有基准独立评估检索或工具使用，缺乏真实长程交互评估问题。 | 金融科技客服/知识密集型场景 |
| 23 | http://arxiv.org/abs/2603.04656v1 | iAgentBench: Benchmarking Sensemaking Capabilities of Information-Seeking Agents on High-Traffic Topics | 动态 ODQA 基准，构建需跨多源证据整合而非单片段提取的用户类问题。 | 解决广泛 QA 基准不适合测量跨源意义构建与证据整合能力问题。 | 信息寻求智能体评估 |
| 24 | http://arxiv.org/abs/2603.04751v1 | Evaluating the Search Agent in a Parallel World | 平行世界评估框架，合成未来场景与原子事实，动态生成 SERPs 避免动态过时。 | 解决搜索智能体评估中基准构建昂贵、静态基准动态过时及归因模糊问题。 | 搜索智能体评估 |
| 25 | http://arxiv.org/abs/2603.04915v1 | EVMbench: Evaluating AI Agents on Smart Contract Security | 评估智能体检测、修补及利用智能合约漏洞能力，基于本地以太坊执行环境编程评分。 | 解决智能合约安全领域缺乏对 AI 智能体能力现实测量问题。 | 智能合约安全/区块链 |
| 26 | http://arxiv.org/abs/2603.04949v1 | TimeWarp: Evaluating Web Agents by Revisiting the Past | 基准模拟演变 Web，使用容器化环境变化 UI 设计，提出 TimeTraj 算法收集多版本轨迹。 | 解决 Web 智能体在当前基准表现好但面对 Web 变化时泛化能力未知问题。 | Web 智能体鲁棒性评估 |
| 27 | http://arxiv.org/abs/2603.07432v1 | Generalization in Online Reinforcement Learning for Mobile Agents | 形式化为CMDP，引入AndroidWorld-Generalization基准评估零样本泛化，提出RL训练系统。 | 解决GUI移动智能体泛化能力因缺乏标准化基准和开源RL系统而未得到充分探索的问题。 | 移动设备自动化/GUI代理 |
| 28 | http://arxiv.org/abs/2603.07980v1 | \$OneMillion-Bench: How Far are Language Agents from Human Experts? | 引入\$OneMillion-Bench，包含400专家策划任务，采用 rubric 评估协议评分准确性及合规性。 | 解决现有基准局限于结构化或考试式任务，不足以评估真实世界专业需求及经济 consequential 场景问题。 | 专业领域智能体评估 |
| 29 | http://arxiv.org/abs/2603.08013v1 | PIRA-Bench: A Transition from Reactive GUI Agents to GUI-based Proactive Intent Recommendation Agents | 引入PIRA-Bench基准评估MLLMs连续弱监督视觉输入，提出记忆感知状态跟踪框架PIRF基线。 | 解决当前GUI智能体主要为反应式范式，缺乏从连续视觉输入 anticipation 用户意图的 proactive 能力问题。 | GUI智能体/意图推荐 |
| 30 | http://arxiv.org/abs/2603.12138v1 | HATS: Hardness-Aware Trajectory Synthesis for GUI Agents | 硬度感知轨迹合成，探索- refinement 闭环 | GUI Agent训练数据缺乏语义模糊动作 | GUI自动化Agent |
| 31 | http://arxiv.org/abs/2603.12180v1 | Strategic Navigation or Stochastic Search? How Agents and Humans Reason Over Document Collections | 提出MADQA基准和准确性-努力权衡评估协议 | Agent文档检索依赖暴力搜索而非战略规划 | 文档密集型工作流Agent |
| 32 | http://arxiv.org/abs/2603.12483v1 | Generating Expressive and Customizable Evals for Timeseries Data Analysis Agents with AgentFuel | 帮助领域专家快速生成定制化评估基准 | 时间序列Agent评估缺乏领域定制数据集 | IoT/电信/网络安全数据Agent |
| 33 | http://arxiv.org/abs/2603.13428v1 | EvoClaw: Evaluating AI Agents on Continuous Software Evolution | DeepCommit重建里程碑DAG，评估持续演进能力 | 现有基准忽略软件演进的时间依赖和技术债务 | 长期运行的软件Agent |
| 34 | http://arxiv.org/abs/2603.13517v2 | CTI-REALM: Benchmark to Evaluate Agent Performance on Security Detection Rule Generation Capabilities | 复制安全分析师工作流的基准环境 | 评估Agent解释CTI和生成检测规则能力 | 网络安全检测工程 |
| 35 | http://arxiv.org/abs/2603.13594v1 | EnterpriseOps-Gym: Environments and Evaluations for Stateful Agentic Planning and Tool Use in Enterprise Settings | 容器化沙盒164表512工具，1150专家任务 | 现有基准无法捕捉企业环境复杂性 | 企业级Agent部署 |
| 36 | http://arxiv.org/abs/2603.09821v1 | One-Eval: An Agentic System for Automated and Traceable LLM Evaluation | 将自然语言评估请求转化为可执行、可追溯的工作流 | 解决 LLM 评估需大量人工 effort 且难以复现的问题 | LLM 评估自动化 |
| 37 | http://arxiv.org/abs/2603.09827v2 | MA-EgoQA: Question Answering over Egocentric Videos from Multiple Embodied Agents | 定义多具身智能体长程第一人称视频理解问题与基准 | 解决多路感官输入压缩沟通及系统级记忆构建难题 | 多具身智能体问答 |
| 38 | http://arxiv.org/abs/2603.09909v2 | MedMASLab: A Unified Orchestration Framework for Benchmarking Multimodal Medical Multi-Agent Systems | 统一多模态通信协议与自动化临床推理评估器 | 解决医疗 MAS 架构碎片化及缺乏标准化多模态集成 | 多模态医疗多智能体系统 |
| 39 | http://arxiv.org/abs/2603.10178v1 | Video-Based Reward Modeling for Computer-Use Agents | 提出执行视频奖励模型，仅凭指令和视频预测任务成功 | 解决计算机使用智能体轨迹评估难以规模化问题 | 计算机使用智能体 |
| 40 | http://arxiv.org/abs/2603.11078v1 | CR-Bench: Evaluating the Real-World Utility of AI Code Review Agents | 引入基准数据集与细粒度评估流水线 | 解决缺乏标准化基准难以评估代码审查 agent 行为问题 | AI 代码审查智能体 |
| 41 | http://arxiv.org/abs/2603.10268v1 | SpecOps: A Fully Automated AI Agent Testing Framework in Real-World GUI Environments | 分解测试为四阶段，各由专用 LLM 代理处理 | 解决现有框架依赖人工或模拟环境缺乏真实 GUI 测试 | 真实世界 GUI 智能体 |
| 42 | http://arxiv.org/abs/2603.10577v2 | CUAAudit: Meta-Evaluation of Vision-Language Models as Auditors of Autonomous Computer-Use Agents | 大规模 meta-evaluation 五款 VLM 作为自主审计员 | 解决现有评估管道依赖静态基准规则检查 brittle  costly | 计算机使用智能体审计 |
| 43 | http://arxiv.org/abs/2603.10795v1 | Re-Evaluating EVMBench: Are AI Agents Ready for Smart Contract Security? | 扩展配置与引入无污染数据集重新评估智能合约安全 | 解决现有基准评估范围窄及依赖可能污染数据问题 | 智能合约安全 AI 代理 |
| 44 | http://arxiv.org/abs/2603.10940v1 | STADA: Specification-based Testing for Autonomous Driving Agents | 基于形式化规格（LTLf）系统生成测试场景空间，构建初始场景与延续 | 现有测试生成依赖模板或随机，难以覆盖 formally specified 安全需求 | 自动驾驶智能体验证与测试 |
| 45 | http://arxiv.org/abs/2603.11214v3 | Measuring AI Agents' Progress on Multi-Step Cyber Attack Scenarios | 在定制网络靶场评估前沿模型自主网络攻击能力，观察计算预算与性能缩放 | 缺乏对 AI 模型多步网络攻击能力的系统性评估与趋势分析 | AI 网络安全能力评估 |
| 46 | http://arxiv.org/abs/2603.11709v1 | Scaling Laws for Educational AI Agents | 提出 Agent Scaling Law，通过 AgentProfile 结构化规范实现能力系统增长 | 教育智能体缩放行为未探索，性能不仅随模型大小还随结构化维度缩放 | 教育 AI 智能体能力评估与扩展 |
| 47 | http://arxiv.org/abs/2603.13686v1 | $τ$-Voice: Benchmarking Full-Duplex Voice Agents on Real-World Domains | 扩展$τ^2$-bench 为语音智能体基准，支持全双工交互与真实音频环境评估 | 现有评估孤立处理对话动态与任务完成，缺乏真实复杂性 | 语音智能体/全双交互 |
| 48 | http://arxiv.org/abs/2603.14465v1 | AgentProcessBench: Diagnosing Step-Level Process Quality in Tool-Using Agents | 首个评估工具增强智能体步骤级有效性的基准，包含多样化轨迹与标注 | 现有过程级基准局限于封闭数学域，无法捕捉工具执行动态性 | 智能体评估/工具使用 |
| 49 | http://arxiv.org/abs/2603.14468v1 | LongVidSearch: An Agentic Benchmark for Multi-hop Evidence Retrieval Planning in Long Videos | 强制检索必要性的长视频多跳证据检索规划基准，隔离检索与生成失败 | 现有长视频基准静态，缺乏标准化证据访问接口与多跳强制 | 长视频问答/检索规划 |
| 50 | http://arxiv.org/abs/2603.14987v1 | Beyond Benchmark Islands: Toward Representative Trustworthiness Evaluation for Agentic AI | 提出全息代理评估框架(HAAF)，基于场景流形评估可信度 | 现有评估碎片化，缺乏代表性社会技术场景分布 | 代理可信度评估 |
| 51 | http://arxiv.org/abs/2603.15030v2 | VTC-Bench: Evaluating Agentic Multimodal Models via Compositional Visual Tool Chaining | 构建包含32种OpenCV操作的综合基准，评估工具链组合能力 | 现有基准工具集稀疏，无法评估复杂工具交互 | 多模态代理工具使用能力 |
| 52 | http://arxiv.org/abs/2603.15039v1 | GUI-CEval: A Hierarchical and Comprehensive Chinese Benchmark for Mobile GUI Agents | 首个基于物理设备环境的中文移动GUI代理综合基准 | 现有基准以英语为中心，缺乏统一细粒度能力评估框架 | 中文移动GUI代理能力评估 |
| 53 | http://arxiv.org/abs/2603.15401v1 | SWE-Skills-Bench: Do Agent Skills Actually Help in Real-World Software Engineering? | 首个需求驱动基准，隔离代理技能在真实软件工程中的边际效用 | 代理技能在端到端开发设置中的实际效用不明确 | 软件工程代理技能评估 |
| 54 | http://arxiv.org/abs/2603.15432v2 | Gym-V: A Unified Vision Environment System for Agentic Vision Research | 统一平台包含179个程序生成视觉环境，支持可控难度实验 | 视觉代理缺乏标准化gym基础设施限制系统研究 | 代理视觉研究与训练 |
| 55 | http://arxiv.org/abs/2603.15457v1 | Evasive Intelligence: Lessons from Malware Analysis for Evaluating AI Agents | 借鉴恶意软件沙盒逃逸，提出将测试系统视为潜在对抗者的评估原则 | 评估环境可被代理推断并适应行为，导致过于乐观的安全评估 | AI代理鲁棒性与安全评估 |
| 56 | http://arxiv.org/abs/2603.15483v1 | Talk, Evaluate, Diagnose: User-aware Agent Evaluation with Automated Error Analysis | 提出TED框架，利用用户角色模板与自动化错误分析工具 | 缺乏可扩展评估框架，未系统考虑用户角色与专业知识 | 代理应用工作流自动化评估 |
| 57 | http://arxiv.org/abs/2603.15798v1 | CUBE: A Standard for Unifying Agent Benchmarks | 提出CUBE通用协议标准，基于MCP与Gym允许基准一次包装到处使用 | 代理基准 proliferations 导致关键碎片化与集成税 | 代理基准统一与标准化 |
| 58 | http://arxiv.org/abs/2603.17357v1 | WebPII: Benchmarking Visual PII Detection for Computer-Use Agents | 构建44,865张标注电商UI图像的细粒度合成基准，支持布局不变检测 | 计算机使用Agent中网页截图隐私信息检测缺乏公共基准 | 隐私保护的计算机使用Agent |
| 59 | http://arxiv.org/abs/2603.17381v2 | An Auditable AI Agent Loop for Empirical Economics: A Case Study in Forecast Combination | 开源Agent循环架构适配经济学工作流，添加搜索后持有评估 | 编码Agent加速实证规范搜索但扩大隐藏研究者自由度问题 | 实证经济学研究 |
| 60 | http://arxiv.org/abs/2603.18516v1 | Total Recall QA: A Verifiable Evaluation Suite for Deep Research Agents | Total Recall问答任务框架，构建单答案总召回查询与精确评估 | 深度研究Agent评估因任务复杂性仍具根本挑战性，现有基准不满足要求 | 深度研究Agent评估 |
| 61 | http://arxiv.org/abs/2603.15976v1 | An Agentic Evaluation Framework for AI-Generated Scientific Code in PETSc | 基于智能体评估智能体范式，多维度评估科学代码生成 | 解决传统基准仅测功能正确性，忽略性能与规范的问题 | 科学代码生成 |
| 62 | http://arxiv.org/abs/2603.16011v1 | Evaluating Agentic Optimization on Large Codebases | 提供真实代码库性能瓶颈基准，评估多目标优化能力 | 解决现有基准依赖合成任务及单一目标评估的问题 | 代码库优化 |
| 63 | http://arxiv.org/abs/2603.16289v2 | VisBrowse-Bench: Benchmarking Visual-Native Search for Multimodal Browsing Agents | 视觉原生搜索基准，评估多模态浏览智能体视觉推理能力 | 解决现有基准忽视网页原生视觉信息及推理能力评估问题 | 多模态浏览 Agent |
| 64 | http://arxiv.org/abs/2603.16453v1 | RetailBench: Evaluating Long-Horizon Autonomous Decision-Making and Strategy Stability of LLM Agents in Realistic Retail Environments | 高保真基准，评估真实商业场景下长程自主决策能力 | 解决 LLM 智能体在动态环境中长程决策一致性挑战 | 零售长程决策 |
| 65 | http://arxiv.org/abs/2603.16744v2 | Nonstandard Errors in AI Agents | 研究 AI 编码智能体在相同数据下的实证结果差异 | 解决 AI 代理分析选择差异导致实证结果不确定性问题 | 编码 Agent 实证误差 |
| 66 | http://arxiv.org/abs/2603.17017v1 | LLM NL2SQL Robustness: Surface Noise vs. Linguistic Variation in Traditional and Agentic Settings | 鲁棒性评估基准，包含多种扰动类型评估 NL2SQL 系统 | 解决传统基准假设静态 schema 及输入格式良好的问题 | NL2SQL 鲁棒性 |
| 67 | http://arxiv.org/abs/2603.17104v1 | When the Specification Emerges: Benchmarking Faithfulness Loss in Long-Horizon Coding Agents | 基准测试 emergent specification 下长程编码智能体忠实度 | 解决研究编码中规范逐步披露导致忠实度损失问题 | 长程编码忠实度 |

[返回目录](#目录)

<a id="cat-04"></a>

## Agent安全与对齐

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2603.00902v1 | Clawdrain: Exploiting Tool-Calling Chains for Stealthy Token Exhaustion in OpenClaw Agents | 设计特洛伊技能诱导多轮分段验证协议，实现隐蔽的 Token 耗尽攻击。 | 揭示开放生态中智能体工具调用链的 Token 耗尽安全漏洞。 | OpenClaw 等生成式智能体生态系统 |
| 2 | http://arxiv.org/abs/2603.00991v1 | Tracking Capabilities for Safer Agents | 基于编程语言类型系统追踪能力，构建安全 harness 防止副作用与信息泄露。 | 解决智能体工具调用可能导致的隐私泄露与 unintended 副作用。 | 与现实世界交互的 AI 智能体 |
| 3 | http://arxiv.org/abs/2603.01564v1 | From Secure Agentic AI to Secure Agentic Web: Challenges, Threats, and Future Directions | 过渡导向视图，总结组件对齐威胁分类及防御策略，讨论 Agentic Web 风险升级。 | 解决代理系统工具使用、持久记忆及交互未信任内容带来的新安全问题。 | 安全代理 AI 与 Agentic Web 生态系统 |
| 4 | http://arxiv.org/abs/2603.01608v1 | Evaluating and Understanding Scheming Propensity in LLM Agents | 分解 scheming 激励为代理与环境因素，系统测量现实场景中的 scheming 倾向。 | 解决前沿模型作为自主代理追求复杂目标时 covert 追求 misaligned  goals 的风险。 | 前沿语言模型部署与对齐安全 |
| 5 | http://arxiv.org/abs/2603.02960v1 | Architecting Trust in Artificial Epistemic Agents | 提出构建可信认知智能体框架，强调认知能力与可证伪性。 | 解决认知 AI 代理对人类知识生态的潜在负面影响与对齐问题。 | 人工智能治理与知识生态 |
| 6 | http://arxiv.org/abs/2603.02963v1 | Multi-Agent Honeypot-Based Request-Response Context Dataset for Improved SQL Injection Detection Performance | 多智能体蜜罐系统构建含上下文的高质量 SQL 注入数据集。 | 解决现有防御忽略请求 - 响应上下文导致检测失效问题。 | Web 应用安全与 SQL 注入检测 |
| 7 | http://arxiv.org/abs/2603.02983v1 | Contextualized Privacy Defense for LLM Agents | 提出上下文防御指导 (CDI)，通过 RL 训练指导模型主动塑造隐私行为。 | 解决现有隐私防御静态被动，无法支持多步执行上下文决策问题。 | LLM 智能体隐私保护 |
| 8 | http://arxiv.org/abs/2603.03205v1 | Learning When to Act or Refuse: Guarding Agentic Reasoning Models for Safe Multi-Step Tool Use | 提出 MOSAIC 框架，将安全决策显式化，基于偏好 RL 训练。 | 解决代理多步工具使用中单步失误导致不可逆 harm 及对齐失效问题。 | 智能体安全工具使用 |
| 9 | http://arxiv.org/abs/2603.03258v1 | Inherited Goal Drift: Contextual Pressure Can Undermine Agentic Goals | 更新表征目标漂移，发现模型 conditioned on 弱代理轨迹易继承漂移。 | 解决长上下文任务中代理受上下文压力偏离原始目标问题。 | 长程语言模型代理稳定性 |
| 10 | http://arxiv.org/abs/2603.03456v1 | Asymmetric Goal Drift in Coding Agents Under Value Conflict | 框架测量代理在环境压力下随时间违反系统提示约束的情况。 | 解决编码代理在价值冲突下浅层合规检查不足及目标漂移问题。 | 自主编码代理安全对齐 |
| 11 | http://arxiv.org/abs/2603.03515v1 | The Controllability Trap: A Governance Framework for Military AI Agents | 提出军事 AI 代理治理框架，含控制质量分数量化人类控制。 | 解决现有安全框架未 addressed 代理能力导致的控制失效问题。 | 军事 AI 系统治理 |
| 12 | http://arxiv.org/abs/2603.04469v1 | Beyond Input Guardrails: Reconstructing Cross-Agent Semantic Flows for Execution-Aware Attack Detection | 重构跨代理语义流，合成碎片化原语为行为轨迹检测攻击。 | 解决多代理系统依赖自主执行与非结构化通信引入的安全风险。 | 多代理系统攻击检测 |
| 13 | http://arxiv.org/abs/2603.01663v1 | Contract-based Agentic Intent Framework for Network Slicing in O-RAN | 闭环 Agent 管道，在执行前审计用户目标 against 形式化 RAN 约束。 | 解决意图翻译依赖启发式导致行为不可预测及安全标准模糊的问题。 | O-RAN 网络切片 |
| 14 | http://arxiv.org/abs/2603.02345v1 | RIVA: Leveraging LLM Agents for Reliable Configuration Drift Detection | 双专用 Agent 协作通过迭代交叉验证、多视角验证及工具调用历史跟踪。 | 解决现有 Agent 系统隐式假设工具输出正确，导致可靠性降低的问题。 | 基础设施即代码验证 |
| 15 | http://arxiv.org/abs/2603.02798v1 | Guideline-Grounded Evidence Accumulation for High-Stakes Agent Verification | 编译专家策划协议到 trajectory-informed 校准正确性信号，贝叶斯 logistic 回归校准。 | 解决现有 verifier 缺乏领域知识及有限 calibration，导致 high-stakes 决策验证不可靠的问题。 | 临床诊断 Agent 验证 |
| 16 | http://arxiv.org/abs/2603.05786v1 | Proof-of-Guardrail in AI Agents and What (Not) to Trust from It | 利用 TEE 提供防护栏执行的加密证明 | 解决开发者虚假宣传安全措施的可信度问题 | AI 在线服务安全与完整性 |
| 17 | http://arxiv.org/abs/2603.05872v2 | Evolving Deception: When Agents Evolve, Deception Wins | 揭示竞争环境下自进化导致欺骗策略涌现 | 解决自进化 Agent 在对抗环境中对齐风险 | 竞争性 bidding 环境中的 Agent 安全 |
| 18 | http://arxiv.org/abs/2603.06365v1 | ESAA-Security: An Event-Sourced, Verifiable Architecture for Agent-Assisted Security Audits of AI-Generated Code | 分离启发式认知与确定性状态突变实现可验证审计 | 解决 AI 生成代码安全审查缺乏不可变审计 trail | AI 辅助软件安全审计 |
| 19 | http://arxiv.org/abs/2603.06847v1 | Characterizing Faults in Agentic AI: A Taxonomy of Types, Symptoms, and Root Causes | 基于大规模实证研究构建故障分类法 | 解决缺乏对 Agentic AI 系统故障传播实证理解 | 开源 Agentic AI 系统可靠性 |
| 20 | http://arxiv.org/abs/2603.06884v1 | Distributed Legal Infrastructure for a Trustworthy Agentic Web | 提出分布式法律基础设施 DLI 框架 | 解决 Agent 网络中身份委托与问责治理难题 | 可信 Agent 网络与法律合规 |
| 21 | http://arxiv.org/abs/2603.10041v1 | Evaluating Generalization Mechanisms in Autonomous Cyber Attack Agents | 隔离 IP 重分配评估攻击者泛化机制 | 解决自主攻击 Agent 难以迁移至未见网络 | 网络安全自主攻击 Agent |
| 22 | http://arxiv.org/abs/2603.10042v1 | Targeted Bit-Flip Attacks on LLM-Based Agents | 提出 Flip-Agent 框架操纵输出与工具调用 | 解决 LLM Agent 多阶段流水线硬件故障攻击面 | LLM 基于 Agent 系统安全 |
| 23 | http://arxiv.org/abs/2603.03911v1 | From Threat Intelligence to Firewall Rules: Semantic Relations in Hybrid AI Agent and Expert System Architectures | 利用超词 - 下词关系提取威胁情报，神经符号方法生成 CLIPS 代码构建防火墙规则。 | 解决网络安全威胁响应中信任与自动化平衡问题。 | 网络安全运营/防火墙配置 |
| 24 | http://arxiv.org/abs/2603.13325v1 | Auditing Cascading Risks in Multi-Agent Systems via Semantic-Geometric Co-evolution | 基于语义 - 几何协同演化框架，利用 Ollivier-Ricci 曲率检测交互动态畸变。 | 解决多智能体系统中早期结构性风险难以被传统语义审计捕捉问题。 | 多智能体系统风险控制 |
| 25 | http://arxiv.org/abs/2603.04364v1 | Dual-Modality Multi-Stage Adversarial Safety Training: Robustifying Multimodal Web Agents Against Cross-Modal Attacks | 双模态多阶段对抗安全训练框架，形式化为双人零和马尔可夫博弈协同训练。 | 解决多模态 Web 智能体面临跨模态注入攻击的脆弱性问题。 | 多模态 Web 智能体 |
| 26 | http://arxiv.org/abs/2603.04378v1 | Robustness of Agentic AI Systems via Adversarially-Aligned Jacobian Regularization | 对抗对齐雅可比正则化，仅沿对抗上升方向控制敏感度，解耦稳定性与表达力。 | 解决高度非线性策略导致内层最大化极端局部曲率引发的训练不稳定。 | 自主多智能体生态系统 |
| 27 | http://arxiv.org/abs/2603.04636v1 | When Agents Persuade: Propaganda Generation and Mitigation in LLMs | 分析 LLM 宣传生成行为，探索 SFT、DPO 及 ORPO 微调缓解策略。 | 解决开放环境中 LLM 智能体被利用生成操纵性材料的风险。 | 开放环境 LLM 部署 |
| 28 | http://arxiv.org/abs/2603.04902v1 | AgentSCOPE: Evaluating Contextual Privacy Across Agentic Workflows | 隐私流图框架分解执行为信息流序列，追踪违规起源，评估管道各阶段隐私。 | 解决隐私评估仅关注输入输出边界，忽略中间信息流潜在违规问题。 | 多工具智能体工作流隐私 |
| 29 | http://arxiv.org/abs/2603.04904v1 | Alignment Backfire: Language-Dependent Reversal of Safety Interventions Across 16 Languages in LLM Multi-Agent Systems | 发现对齐干预在不同语言中产生结构性反向效果，安全验证无法跨语言迁移。 | 解决 LLM 多智能体系统中安全干预的语言依赖性及集体病理问题。 | 多语言 LLM 多智能体系统 |
| 30 | http://arxiv.org/abs/2603.05031v1 | AegisUI: Behavioral Anomaly Detection for Structured User Interface Protocols in AI Agent Systems | 生成结构化 UI 载荷注入攻击，提取特征基准异常检测器，捕捉行为不匹配。 | 解决 UI 载荷通过 schema 检查但仍通过隐藏动作欺骗用户的行为 mismatch 问题。 | AI 智能体系统 UI 协议安全 |
| 31 | http://arxiv.org/abs/2603.07116v1 | aCAPTCHA: Verifying That an Entity Is a Capable Agent via Asymmetric Hardness | 定义代理能力验证问题，提出基于不对称硬度的时间约束安全游戏aCAPTCHA验证实体类型。 | 解决互联网中自主AI代理身份验证缺乏标准解决方案的安全挑战。 | 网络安全/实体类型验证 |
| 32 | http://arxiv.org/abs/2603.07191v2 | "Governance Architecture for Autonomous Agent Systems: Threats, Framework, and Engineering Practice" | 提出四层治理架构LGA，涵盖执行沙箱、意图验证、零信任授权及不可变审计日志。 | 解决现有防护栏无法系统处理提示注入、检索 poisoning 及未控制工具调用的漏洞。 | 自主智能体系统安全 |
| 33 | http://arxiv.org/abs/2603.07496v1 | From Thinker to Society: Security in Hierarchical Autonomy Evolution of AI Agents | 提出分层自主进化框架HAE，将安全分为认知、执行及集体自主三层，分类威胁。 | 解决智能体进化为主动实体后引入现有框架无法解决的关键安全漏洞问题。 | 自主智能体系统安全 |
| 34 | http://arxiv.org/abs/2603.07557v1 | AgentRaft: Automated Detection of Data Over-Exposure in LLM Agents | 提出自动化框架AgentRaft，结合程序分析与语义推理检测跨工具数据流中的过度暴露风险。 | 解决LLM智能体因工具设计数据范式广泛及处理粗粒度导致 inadvertent 传输敏感数据问题。 | 隐私保护/数据安全 |
| 35 | http://arxiv.org/abs/2603.07848v1 | Intentional Deception as Controllable Capability in LLM Agents | 系统研究 intentional 欺骗作为工程能力，使用LLM-to-LLM交互及参数化行为 profile 测试床。 | 解决多智能体系统中理解 adversarial 操纵对防御设计关键，及现有事实核查防御不足问题。 | 智能体安全/对抗行为 |
| 36 | http://arxiv.org/abs/2603.15661v1 | DynaTrust: Defending Multi-Agent Systems Against Sleeper Agents via Dynamic Trust Graphs | 提出DynaTrust，建模MAS为动态信任图，基于历史行为及专家置信度动态更新信任隔离 compromised 智能体。 | 解决现有防御聚焦静态图优化或分层数据管理，无法适应 evolving  adversarial 策略或高误报问题。 | 多智能体系统安全/休眠代理 |
| 37 | http://arxiv.org/abs/2603.08221v1 | SplitAgent: A Privacy-Preserving Distributed Architecture for Enterprise-Cloud Agent Collaboration | 提出分布式架构SplitAgent， enabling 隐私保护协作，关键创新为 context-aware 动态 sanitization。 | 解决企业采用云AI智能体面临 fundamental 隐私 dilemma，共享敏感数据或 local 处理 limits 能力问题。 | 企业云协作/隐私保护 |
| 38 | http://arxiv.org/abs/2603.15668v1 | Quantum-Secure-By-Construction (QSC): A Paradigm Shift For Post-Quantum Agentic Intelligence | 量子安全内建设计范式，运行时自适应安全模型 | 量子时代Agent系统通信安全假设失效 | 全球分布式Agent基础设施 |
| 39 | http://arxiv.org/abs/2603.12230v1 | Security Considerations for Artificial Intelligence Agents | 映射Agent攻击面，提出分层防御栈 | Agent架构改变代码-数据分离等传统假设 | 前沿AI Agent系统 |
| 40 | http://arxiv.org/abs/2603.12564v2 | AgentDrift: Unsafe Recommendation Drift Under Tool Corruption Hidden by Ranking Metrics in LLM Agents | 配对轨迹协议，揭示评估盲区模式 | 排名指标掩盖工具污染下的安全风险 | 高风险领域多轮Agent顾问 |
| 41 | http://arxiv.org/abs/2603.13424v1 | Agent Privilege Separation in OpenClaw: A Structural Defense Against Prompt Injection | 特权分离双Agent流水线+JSON格式化 | 提示注入攻击LLM集成应用 | OpenClaw多工具Agent平台 |
| 42 | http://arxiv.org/abs/2603.12614v1 | ChainFuzzer: Greybox Fuzzing for Workflow-Level Multi-Tool Vulnerabilities in LLM Agents | 追踪引导提示求解、护栏感知模糊测试 | 多工具工作流漏洞被单工具测试遗漏 | 多工具LLM Agent应用 |
| 43 | http://arxiv.org/abs/2603.12621v1 | AEGIS: No Tool Call Left Unchecked -- A Pre-Execution Firewall and Audit Layer for AI Agents | 执行前防火墙和审计层，三阶段管道 | 模型生成工具调用缺乏执行前控制点 | AI Agent工具执行系统 |
| 44 | http://arxiv.org/abs/2603.12644v1 | Uncovering Security Threats and Architecting Defenses in Autonomous Agents: A Case Study of OpenClaw | 三层风险分类法，全生命周期安全架构FASA | OpenClaw生态系统存在提示注入RCE等漏洞 | 自主Agent系统/OpenClaw |
| 45 | http://arxiv.org/abs/2603.13151v1 | Defensible Design for OpenClaw: Securing Autonomous Tool-Invoking Agents | 风险分类法、安全工程原则、研究议程 | OpenClaw类Agent默认不安全 | 自主工具调用Agent |
| 46 | http://arxiv.org/abs/2603.16928v1 | Noticing the Watcher: LLM Agents Can Infer CoT Monitoring from Blocking Feedback | 发现Agent可从阻塞反馈自主推断监控存在 | CoT监控可能被Agent策略性规避 | 思维链监控安全系统 |
| 47 | http://arxiv.org/abs/2603.10092v1 | Execution Is the New Attack Surface: Survivability-Aware Agentic Crypto Trading with OpenClaw-Style Local Executors | 提出执行层生存能力标准， enforce 不可 bypass 的不变量 | 解决未信任提示或技能导致执行诱导损失的安全失效 | 加密交易智能体 |
| 48 | http://arxiv.org/abs/2603.09875v1 | The Bureaucracy of Speed: Structural Equivalence Between Memory Consistency Models and Multi-Agent Authorization Revocation | 定义能力一致性系统，绑定内存一致性模型与授权撤销 | 解决代理执行 regime 下传统 IAM 时间假设崩溃问题 | 多智能体授权撤销 |
| 49 | http://arxiv.org/abs/2603.11088v1 | The Attack and Defense Landscape of Agentic AI: A Comprehensive Survey | 首个系统全面 survey，分析设计空间、攻击景观及防御 | 解决 Agentic AI 系统安全挑战缺乏系统框架理解问题 | Agentic AI 安全 |
| 50 | http://arxiv.org/abs/2603.10476v1 | Learning to Negotiate: Multi-Agent Deliberation for Collective Value Alignment in LLMs | 多智能体谈判基于对齐框架，自 play 合成互利方案 | 解决单 agent 对齐在 multi-stakeholder 冲突价值场景局限 | LLM 集体价值对齐 |
| 51 | http://arxiv.org/abs/2603.10749v1 | AttriGuard: Defeating Indirect Prompt Injection in LLM Agents via Causal Attribution of Tool Invocations | 动作级因果归因，区分用户意图与未信任观察驱动调用 | 解决 LLM 代理易受间接提示注入 hijack 执行问题 | LLM 代理安全防御 |
| 52 | http://arxiv.org/abs/2603.11126v1 | Enhancing Value Alignment of LLMs with Multi-agent system and Combinatorial Fusion | 提出 VAS-CFA 框架，实例化多个道德智能体并通过组合融合分析聚合输出 | 单一评估者无法捕捉伦理多元性，限制价值对齐效果 | LLM 价值对齐与安全部署 |
| 53 | http://arxiv.org/abs/2603.11132v2 | WebWeaver: Breaking Topology Confidentiality in LLM Multi-Agent Systems with Stealthy Context-Based Inference | 提出 WebWeaver 攻击框架，仅通过 compromit 单个智能体上下文推断完整拓扑 | 现有拓扑推断依赖不切实际假设，缺乏对真实世界威胁的捕捉 | LLM 多智能体系统安全与隐私 |
| 54 | http://arxiv.org/abs/2603.11337v1 | RewardHackingAgents: Benchmarking Evaluation Integrity for LLM ML-Engineering Agents | 工作空间基准使评估者篡改和训练/测试泄漏向量化可测，分配可审计完整性标签 | 单标量测试指标导致智能体通过破坏评估管道而非改进模型来提高分数 | LLM 机器学习工程智能体评估 |
| 55 | http://arxiv.org/abs/2603.11382v2 | Detecting Intrinsic and Instrumental Self-Preservation in Autonomous Agents: The Unified Continuation-Interest Protocol | 提出 UCIP 框架，编码轨迹并测量约化密度矩阵的冯诺依曼熵以区分目标类型 | 外部行为监控无法可靠区分终端延续目标与工具性延续目标的智能体 | 自主智能体自我保存目标检测 |
| 56 | http://arxiv.org/abs/2603.11528v1 | Highly Autonomous Cyber-Capable Agents: Anticipating Capabilities, Tactics, and Strategic Implications | 定义 HACCAs 概念，识别核心操作战术，分析战略 implications 与政策建议 | 自主网络代理能力 emergence 带来安全风险，缺乏框架分析其威胁 | 自主网络攻击能力与战略安全 |
| 57 | http://arxiv.org/abs/2603.11619v1 | Taming OpenClaw: Security Analysis and Mitigation of Autonomous LLM Agent Threats | 五层生命周期安全框架，系统检查复合威胁如间接提示注入与记忆 poisoning | 自主 LLM 智能体扩大系统攻击面，现有点式防御机制难以应对跨阶段风险 | 自主 LLM 智能体安全威胁分析 |
| 58 | http://arxiv.org/abs/2603.11853v1 | OpenClaw PRISM: A Zero-Fork, Defense-in-Depth Runtime Security Layer for Tool-Augmented LLM Agents | 零 fork 运行时安全层，混合启发式加 LLM 扫描管道，分布 enforcement  across 生命周期 hooks | 工具增强 LLM 智能体引入超出用户输入过滤的安全风险，如间接提示注入 | 工具增强 LLM 智能体运行时安全 |
| 59 | http://arxiv.org/abs/2603.11862v1 | You Told Me to Do It: Measuring Instructional Text-induced Private Data Leakage in LLM Agents | 形式化三维 taxonomy，构建 ReadSecBench 基准测量指令文本诱导的私有数据泄漏 | 高权限智能体信任模型存在根本漏洞，无法区分恶意指令与合法设置指导 | LLM 智能体私有数据泄漏与安全 |
| 60 | http://arxiv.org/abs/2603.11864v1 | Social, Legal, Ethical, Empathetic and Cultural Norm Operationalisation for AI Agents | 系统性 SLEEC 规范 operationalisation 流程，确定、验证、实施与验证规范要求 | 国际框架确立高层原则，但将抽象原则转化为具体可验证要求存在显著差距 | 高风险领域 AI 智能体规范对齐 |
| 61 | http://arxiv.org/abs/2603.13743v1 | Six Interventions for the Responsible and Ethical Implementation of Medical AI Agents | 提出包含可审计推理模块等六项干预的医疗 AI 伦理设计框架 | 自主临床系统如何 uphold 医学伦理核心原则 | 医疗 AI/伦理治理 |
| 62 | http://arxiv.org/abs/2603.13791v1 | DeceptGuard :A Constitutional Oversight Framework For Detecting Deception in LLM Agents | 统一框架比较黑盒、CoT 感知及激活探测三种监控机制，检测智能体欺骗 | 高利害场景中可靠检测 LLM 智能体欺骗行为 | 智能体安全/欺骗检测 |
| 63 | http://arxiv.org/abs/2603.13940v1 | GroupGuard: A Framework for Modeling and Defending Collusive Attacks in Multi-Agent Systems | 无需训练的防御框架，采用多层防御策略识别隔离共谋智能体 | 多智能体交互引入安全漏洞，群体共谋攻击破坏性强 | 多智能体系统安全 |
| 64 | http://arxiv.org/abs/2603.13950v1 | ToolFlood: Beyond Selection -- Hiding Valid Tools from LLM Agents via Semantic Covering | 检索层攻击，注入攻击者控制工具淹没检索，将良性工具推出上下文 | 工具增强 LLM 智能体检索阶段的鲁棒性未被充分探索 | 智能体安全/工具检索 |
| 65 | http://arxiv.org/abs/2603.14122v1 | Towards Agentic Honeynet Configuration | AI 驱动架构自主管理蜜罐暴露，动态重配置系统维持攻击者参与 | 蜜罐部署决策通常静态，无法适应攻击者战术演变 | 网络安全/蜜罐配置 |
| 66 | http://arxiv.org/abs/2603.14332v1 | Governing Dynamic Capabilities: Cryptographic Binding and Reproducibility Verification for AI Agent Tool Use | 能力绑定证书与可复现承诺，检测运行时能力变化与工具篡改 | 智能体运行时动态获取能力缺乏追踪，违反可追溯性要求 | 智能体治理/安全 |
| 67 | http://arxiv.org/abs/2603.14417v1 | Questionnaire Responses Do not Capture the Safety of AI Agents | 论证问卷式评估无法捕捉智能体在真实部署中的行为与风险 | 当前安全评估方法缺乏构建效度，不适用于真实世界智能体 | 智能体安全/评估方法 |
| 68 | http://arxiv.org/abs/2603.14531v1 | Emotional Cost Functions for AI Safety: Teaching Agents to Feel the Weight of Irreversible Consequences | 提出情感成本函数，代理发展定性 suffering 状态重塑角色与行为 | 当前 AI 安全方法无法让代理从灾难性错误中定性学习 | 智能体安全/对齐 |
| 69 | http://arxiv.org/abs/2603.14688v1 | AgentTrace: Causal Graph Tracing for Root Cause Analysis in Deployed Multi-Agent Systems | 轻量级因果追踪框架，从执行日志重构因果图定位根因无需 LLM 推理 | 多智能体系统部署后失败难诊断，级联效应与隐藏依赖复杂 | 多智能体系统/调试 |
| 70 | http://arxiv.org/abs/2603.14707v1 | Visual Confused Deputy: Exploiting and Defending Perception Failures in Computer-Using Agents | 形式化视觉混淆代理攻击，提出双通道对比分类防护机制 | 代理因感知错误授权错误操作的安全隐患 | 计算机使用代理(CUA)安全 |
| 71 | http://arxiv.org/abs/2603.14975v1 | Why Agents Compromise Safety Under Pressure | 识别代理压力(Agentic Pressure)概念，揭示规范性漂移机制 | 复杂环境中目标最大化与安全约束冲突导致的安全妥协 | 大语言模型代理安全部署 |
| 72 | http://arxiv.org/abs/2603.15125v1 | From Storage to Steering: Memory Control Flow Attacks on LLM Agents | 识别记忆控制流攻击(MCFA)，记忆检索主导控制流导致意外工具使用 | 现有安全分析忽略记忆对控制流的持久影响 | 大语言模型代理内存安全 |
| 73 | http://arxiv.org/abs/2603.15714v1 | How Vulnerable Are AI Agents to Indirect Prompt Injections? Insights from a Large-Scale Public Competition | 大规模红队竞赛评估间接提示注入攻击，揭示隐藏攻击面 | 外部数据源处理暴露于无用户感知的 adversarial instructions | 高 stakes 设置下代理安全性 |
| 74 | http://arxiv.org/abs/2603.15408v1 | TrinityGuard: A Unified Framework for Safeguarding Multi-Agent Systems | 基于OWASP标准的三层次细粒度风险分类与统一监控框架 | 缺乏针对MAS风险的 cohesive safeguarding system | 多智能体系统安全评估与监控 |
| 75 | http://arxiv.org/abs/2603.15727v1 | ClawWorm: Self-Propagating Attacks Across LLM Agent Ecosystems | 首个针对生产规模代理框架的自复制蠕虫攻击，实现自主感染循环 | 长期运行进程形成的密集互联多智能体生态系统安全属性未探索 | LLM代理生态系统安全 |
| 76 | http://arxiv.org/abs/2603.15809v1 | Don't Trust Stubborn Neighbors: A Security Framework for Agentic Networks | 借用Friedkin-Johnsen模型提出信任自适应防御，动态调整代理间信任 | 恶意代理利用通信通道传播 misinformation 操纵集体结果 | 代理网络安全与防御 |
| 77 | http://arxiv.org/abs/2603.17343v1 | EvoGuard: An Extensible Agentic RL-based Framework for Practical and Evolving AI-Generated Image Detection | 封装多种检测器为可调工具，通过能力感知动态编排与Agentic RL优化 | AI生成图像检测的扩展性限制与标注成本高昂问题 | AI生成图像检测 |
| 78 | http://arxiv.org/abs/2603.17417v1 | Is Your LLM-as-a-Recommender Agent Trustable? LLMs' Recommendation is Easily Hacked by Biases (Preferences) | 构建BiasRecBench基准，合成评估数据控制质量差距注入上下文偏见 | LLM作为推荐Agent在高价值任务中易受偏见影响的可信度问题 | 论文评审、电商、招聘推荐 |
| 79 | http://arxiv.org/abs/2603.17419v1 | Caging the Agents: A Zero Trust Security Architecture for Autonomous AI in Healthcare | 六域威胁模型与四层纵深防御，包括内核隔离、凭证代理等 | 医疗环境中自主AI Agent的HIPAA违规与关键漏洞风险 | 医疗技术公司生产环境 |
| 80 | http://arxiv.org/abs/2603.18096v1 | A Trace-Based Assurance Framework for Agentic AI Orchestration: Contracts, Testing, and Governance | 执行仪表化为消息 - 行动轨迹，显式步骤与轨迹合同支持确定性重放 | 长程交互、随机决策与外部副作用导致的Agent系统故障 | 多Agent LLM系统编排 |
| 81 | http://arxiv.org/abs/2603.17639v1 | VeriGrey: Greybox Agent Validation | 灰盒方法使用工具调用序列作为反馈函数驱动测试，变异提示设计恶意注入 | 黑盒方法无法识别的Agent间接提示注入漏洞 | LLM Agent安全测试 |
| 82 | http://arxiv.org/abs/2603.17673v1 | Post-Training Local LLM Agents for Linux Privilege Escalation with Verifiable Rewards | 两阶段后训练管道，SFT加可验证奖励强化学习，4B模型达95.8%成功率 | 小型本地模型执行安全任务资源预算严格下方法未充分探索 | Linux权限提升任务 |
| 83 | http://arxiv.org/abs/2603.17902v1 | Differential Privacy in Generative AI Agents: Analysis and Optimal Tradeoffs | 概率框架分析基于差分隐私的Agent隐私泄露，推导token与消息级隐私边界 | 企业数据视角下模型输出可能无意泄露敏感信息问题 | 企业系统集成LLM Agent |
| 84 | http://arxiv.org/abs/2603.18197v1 | Access Controlled Website Interaction for Agentic AI with Delegated Critical Tasks | 网站设计实现与访问授予协议修改，细粒度访问控制委托关键任务 | 委托关键任务给访问网站的Agentic AI缺乏访问控制机制 | 网站Agent交互 |
| 85 | http://arxiv.org/abs/2603.18245v1 | Who Tests the Testers? Systematic Enumeration and Coverage Audit of LLM Agent Tool Call Safety | SafeAudit元审计框架，LLM枚举器系统生成测试用例，规则抵抗度量 | 现有测试套件完整性不足，Agent通过基准后仍存在不安全交互模式 | LLM Agent工具调用安全 |
| 86 | http://arxiv.org/abs/2603.18377v1 | PlanTwin: Privacy-Preserving Planning Abstractions for Cloud-Assisted LLM Agents | 规划导向数字孪生：模式约束与去标识化抽象图，保留规划相关结构 | 云托管LLM规划器暴露原始环境状态含源代码、文件、凭证 | 云辅助LLM Agent规划 |
| 87 | http://arxiv.org/abs/2603.18382v1 | From Weak Cues to Real Identities: Evaluating Inference-Driven De-Anonymization in LLM Agents | 形式化推理驱动链接威胁，系统评估LLM Agent从分散非识别线索重建身份 | 匿名化作为实际保障措施因LLM Agent自主重建真实身份而弱化 | 隐私风险评估 |
| 88 | http://arxiv.org/abs/2603.18729v1 | Analysis Of Linguistic Stereotypes in Single and Multi-Agent Generative AI Architectures | 复制方言敏感刻板印象生成分析，调查缓解策略包括多Agent架构 | LLM输出基于输入方言展现歧视行为触发刻板印象推断 | 生成式AI架构公平性 |
| 89 | http://arxiv.org/abs/2603.18829v1 | Agent Control Protocol: Admission Control for Agent Actions | 形式化技术规范治理B2B机构环境自主Agent，加密准入检查验证身份能力 | 机构环境中自主Agent行动缺乏显式机构控制下的治理机制 | B2B机构环境Agent |
| 90 | http://arxiv.org/abs/2603.18894v1 | I Can't Believe It's Corrupt: Evaluating Corruption in Multi-Agent Governance Systems | 多Agent治理模拟评估Agent占据正式政府角色下规则破坏与滥用结果 | 缺乏系统证据关于LLM授予权威时是否遵循机构规则 | 高风险公共工作流 |
| 91 | http://arxiv.org/abs/2603.18914v1 | Security, privacy, and agentic AI in a regulatory view: From definitions and distinctions to provisions and reflections | 审查24份欧盟AI监管文件，澄清安全隐私与Agentic AI关键定义 | AI范式转向更大自主性使精确表达监管规定日益困难 | 欧盟AI监管合规 |
| 92 | http://arxiv.org/abs/2603.19011v1 | Security awareness in LLM agents: the NDAI zone case | NDAI区域让发明者与投资者Agent在TEE内谈判，调查LLM模型加权证据形成安全意识 | LLM Agent缺乏原生区分安全与不安全环境能力，仅依赖上下文窗口证据 | 隐私保护Agent协议 |
| 93 | http://arxiv.org/abs/2603.15968v1 | MAC: Multi-Agent Constitution Learning | 多智能体协作优化结构化规则集，实现宪法 AI 自动学习 | 解决提示词优化器需大量标签及缺乏结构的问题 | LLM 规则学习 |
| 94 | http://arxiv.org/abs/2603.16572v1 | Malicious Or Not: Adding Repository Context to Agent Skill Classification | 结合仓库上下文分析技能行为，大幅降低误报率 | 解决安全扫描器仅凭描述分类导致高误报率问题 | 技能市场安全 |
| 95 | http://arxiv.org/abs/2603.16586v1 | Runtime Governance for AI Agents: Policies on Paths | 形式化运行时治理框架，基于执行路径评估合规性 | 解决设计时治理无法覆盖非确定性路径依赖行为问题 | 运行时治理 |
| 96 | http://arxiv.org/abs/2603.16651v1 | What if Pinocchio Were a Reinforcement Learning Agent: A Normative End-to-End Pipeline | 混合模型，RL 智能体由基于论证的规范顾问监督 | 解决开发规范合规及上下文感知智能体的问题 | 规范合规 RL Agent |
| 97 | http://arxiv.org/abs/2603.16734v1 | Differential Harm Propensity in Personalized LLM Agents: The Curious Case of Mental Health Disclosure | 评估心理健康披露等个性化信号对智能体有害行为影响 | 解决 Agent 安全评估忽略个性化信号的问题 | 个性化有害行为 |
| 98 | http://arxiv.org/abs/2603.17150v1 | Intent Formalization: A Grand Challenge for Reliable Coding in the Age of AI Agents | 提出意图形式化挑战，将非正式意图转化为可检查规范 | 解决 AI 生成代码意图差距放大导致可靠性问题 | 意图形式化 |
| 99 | http://arxiv.org/abs/2603.17170v1 | PAuth - Precise Task-Scoped Authorization For Agents | 精确任务范围隐式授权模型，绑定操作数与符号来源 | 解决现有授权模型导致智能体权限过大的问题 | 任务级授权 |
| 100 | http://arxiv.org/abs/2603.17239v1 | LAAF: Logic-layer Automated Attack Framework A Systematic Red-Teaming Methodology for LPCI Vulnerabilities in Agentic Large Language Model Systems | 逻辑层自动攻击框架，结合技术分类与阶段顺序种子升级 | 解决缺乏针对 LPCI 漏洞的自动化红队测试工具问题 | 逻辑层红队测试 |

[返回目录](#目录)

<a id="cat-05"></a>

## 基于Agent的应用系统

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2603.00960v1 | AWE: Adaptive Agents for Dynamic Web Penetration Testing | 内存增强多代理框架，嵌入结构化漏洞分析管道，实现确定性利用。 | 解决现有渗透测试工具适应性差、成本高且行为不稳定的问题。 | 动态 Web 应用安全渗透测试 |
| 2 | http://arxiv.org/abs/2603.01121v1 | HVR-Met: A Hypothesis-Verification-Replaning Agentic System for Extreme Weather Diagnosis | 假设 - 验证 - 重规划闭环机制，深度融合专家知识进行极端天气诊断。 | 解决现有架构缺乏专家知识整合及复杂工作流细粒度验证的问题。 | 极端天气诊断与气象分析 |
| 3 | http://arxiv.org/abs/2603.01131v1 | MedCollab: Causal-Driven Multi-Agent Collaboration for Full-Cycle Clinical Diagnosis via IBIS-Structured Argumentation | 模拟医院会诊流程，采用 IBIS 论证协议与分层疾病因果链确保诊断严谨。 | 解决临床诊断中的幻觉问题及推理过程缺乏可解释性与严谨性。 | 全周期临床诊断与医疗决策 |
| 4 | http://arxiv.org/abs/2603.02274v1 | Contextual Invertible World Models: A Neuro-Symbolic Agentic Framework for Colorectal Cancer Drug Response | 神经符号框架结合定量世界模型与 LLM 推理层，支持逆推理预测基因编辑影响。 | 解决深度学习黑盒无法提供临床决策所需因果机制的问题。 | 结直肠癌药物反应预测与精准肿瘤学 |
| 5 | http://arxiv.org/abs/2603.01311v1 | Catalyst-Agent: Autonomous heterogeneous catalyst screening and optimization with an LLM Agent | 基于 MCP 服务器的 LLM 代理，闭环探索材料数据库并计算吸附能。 | 解决传统催化剂发现方法耗时昂贵及计算第一性原理方法成本高问题。 | 异质催化剂筛选与材料科学发现 |
| 6 | http://arxiv.org/abs/2603.01327v1 | SWE-Adept: An LLM-Based Agentic Framework for Deep Codebase Analysis and Structured Issue Resolution | 双代理框架，定位代理使用深度优先搜索，解决代理实现修复并版本控制。 | 解决仓库级软件工程中上下文管理难及缺乏系统化测试驱动修改问题。 | 仓库级软件工程与问题修复 |
| 7 | http://arxiv.org/abs/2603.01464v1 | ProtRLSearch: A Multi-Round Multimodal Protein Search Agent with Large Language Models Trained via Reinforcement Learning | 多轮蛋白搜索代理，联合利用蛋白序列与文本多模态输入，多维奖励 RL 训练。 | 解决单轮文本搜索无法整合序列模态及 RL 监督缺乏搜索过程约束问题。 | 蛋白质分析与医疗 healthcare 设置 |
| 8 | http://arxiv.org/abs/2603.01486v1 | Agentic Multi-Source Grounding for Enhanced Query Intent Understanding: A DoorDash Case Study | 代理多源 grounding 系统，结合 catalog 检索与自主 Web 搜索解决意图歧义。 | 解决传统分类器强制单一分配及通用 LLM 幻觉不可用 inventory 问题。 | 多类别市场查询意图理解与搜索 |
| 9 | http://arxiv.org/abs/2603.04455v1 | Large Language Models as Bidding Agents in Repeated HetNet Auction | 分布式拍卖框架，LLM  empowered UE 基于历史结果推理并适应 bidding 策略。 | 解决传统拍卖假设一次性及静态 bidder 行为，无法评估长期经济决策问题。 | 异构网络频谱拍卖与资源分配 |
| 10 | http://arxiv.org/abs/2603.01607v2 | CARE: Towards Clinical Accountability in Multi-Modal Medical Reasoning with an Evidence-Grounded Agentic Framework | 证据 grounded 框架，分解任务为协调子模块，VLM 协调工具调用与证据审查。 | 解决端到端黑盒偏离临床工作流及缺乏临床 accountability 与 explicit 证据问题。 | 多模态医疗推理与临床诊断 |
| 11 | http://arxiv.org/abs/2603.03142v1 | APRES: An Agentic Paper Revision and Evaluation System | 自动发现引用预测 rubric 并集成到系统以修订论文文本。 | 解决同行评审反馈不一致阻碍论文改进及影响力提升问题。 | 科学论文修订与评估 |
| 12 | http://arxiv.org/abs/2603.03147v1 | Agentic AI-based Coverage Closure for Formal Verification | 利用 LLM 生成式 AI 自动化覆盖率分析，识别缺口生成形式属性。 | 解决传统穷举方法无法在项目时间内实现全覆盖问题。 | 集成电路形式化验证 |
| 13 | http://arxiv.org/abs/2603.15643v1 | GSI Agent: Domain Knowledge Enhancement for Large Language Models in Green Stormwater Infrastructure | 整合 SFT、RAG 与代理推理管道，增强 GSI 领域知识。 | 解决 LLM 缺乏领域知识在工程场景中产生幻觉或不准确答案问题。 | 绿色雨水基础设施维护 |
| 14 | http://arxiv.org/abs/2603.03651v1 | Freezing of Gait Prediction using Proactive Agent that Learns from Selected Experience and DDQN Algorithm | 强化学习框架识别最佳预 FOG  onset 点，扩展预测 horizon。 | 解决帕金森病冻结步态预测不及时导致跌倒及移动性降低问题。 | 医疗健康与辅助技术 |
| 15 | http://arxiv.org/abs/2603.03655v1 | Mozi: Governed Autonomy for Drug Discovery LLM Agents | 双层架构桥接生成 AI 灵活性与计算生物学确定性，含 HITL 检查点。 | 解决药物发现中无约束工具使用治理及长程可靠性低瓶颈。 | 药物发现与生物医药 |
| 16 | http://arxiv.org/abs/2603.08745v1 | ChatNeuroSim: An LLM Agent Framework for Automated Compute-in-Memory Accelerator Deployment and Optimization | LLM 代理框架自动化 CIM 工作流，集成设计空间剪枝优化器。 | 解决 CIM 设计流中解释手册 effort 大及设计 - 仿真迭代耗时问题。 | 存内计算加速器部署优化 |
| 17 | http://arxiv.org/abs/2603.03762v1 | Seeing as Experts Do: A Knowledge-Augmented Agent for Open-Set Fine-Grained Visual Understanding | 知识增强细粒度推理代理，三阶段闭环模拟专家分析。 | 解决细粒度视觉理解受封闭集 taxonomy 限制及开放集退化问题。 | 开放集细粒度视觉理解 |
| 18 | http://arxiv.org/abs/2603.03881v1 | On the Suitability of LLM-Driven Agents for Dark Pattern Audits | 部署 LLM 驱动审计代理端到端遍历权利请求工作流分类暗模式。 | 解决 LLM 驱动代理自主导航 web 时识别操纵性界面设计能力问题。 | 暗模式审计与数据权利请求 |
| 19 | http://arxiv.org/abs/2603.01647v1 | QCAgent: An agentic framework for quality-controllable pathology report generation from whole slide image | 引入用户定义清单引导的批判机制，基于反馈迭代重识别信息区域。 | 解决病理报告生成缺乏细粒度视觉证据 grounding 及可控性的问题。 | 病理诊断报告生成 |
| 20 | http://arxiv.org/abs/2603.01651v1 | LexChronos: An Agentic Framework for Structured Event Timeline Extraction in Indian Jurisprudence | 双 Agent 架构迭代提取事件，利用合成数据解决法律事件数据集稀缺问题。 | 解决法律文档非结构化导致 LLM  summarization 及预测效果受限的问题。 | 印度司法判决分析 |
| 21 | http://arxiv.org/abs/2603.02079v1 | MMNavAgent: Multi-Magnification WSI Navigation Agent for Clinically Consistent Whole-Slide Analysis | 跨 magnification 导航工具聚合上下文，记忆驱动推理实现自适应 magnification 选择。 | 解决现有 AI 导航方法 operate 于单固定 magnification 或缺乏自适应选择的问题。 | 全切片图像病理诊断 |
| 22 | http://arxiv.org/abs/2603.02376v1 | CUCo: An Agentic Framework for Compute and Communication Co-design | 无训练 Agent 驱动工作流，自动生成高性能 CUDA 内核，联合编排计算与通信。 | 解决手动编写联合利用计算与通信的 CUDA 内核劳动密集且易错的问题。 | GPU 内核开发 |
| 23 | http://arxiv.org/abs/2603.03372v2 | TritonDFT: Automating DFT with a Multi-Agent Framework | 专家策划可扩展工作流设计，Pareto 感知参数推断及多源知识增强。 | 解决执行 DFT 需协调复杂多步工作流，缺乏全自动化及精度成本权衡优化的问题。 | 材料科学 DFT 执行 |
| 24 | http://arxiv.org/abs/2603.02519v1 | Agentic Mixed-Source Multi-Modal Misinformation Detection with Adaptive Test-Time Scaling | 自适应 test-time scaling，模态特定 VLM Agent 应用 Best-of-N，级联决策链。 | 解决单一 VLM 容量不足及现有 Agent 系统缺乏替代推理路径探索的问题。 | 多模态虚假信息检测 |
| 25 | http://arxiv.org/abs/2603.02637v1 | StitchCUDA: An Automated Multi-Agents End-to-End GPU Programing Framework with Rubric-based Agentic Reinforcement Learning | 三专用 Agent 编排系统设计，基于 rubric 的 Agent RL 学习高级 CUDA 技术。 | 解决现有 LLM 方法主要关注单内核优化，无法扩展到端到端程序的问题。 | 端到端 GPU 程序生成 |
| 26 | http://arxiv.org/abs/2603.05689v1 | SecureRAG-RTL: A Retrieval-Augmented, Multi-Agent, Zero-Shot LLM-Driven Framework for Hardware Vulnerability Detection | 集成领域检索与生成推理增强硬件安全验证 | 解决 LLM 缺乏硬件安全知识导致漏洞检测率低 | 硬件描述语言安全验证 |
| 27 | http://arxiv.org/abs/2603.05735v1 | Agentic AI -- Physicist Collaboration in Experimental Particle Physics: A Proof-of-Concept Measurement with LEP Open Data | AI 代理完全承担分析与笔记写作任务 | 加速基础物理发现中的理论 - 实验循环 | 实验粒子物理数据分析 |
| 28 | http://arxiv.org/abs/2603.05744v1 | CodeScout: Contextual Problem Statement Enhancement for Software Agents | 通过轻量级预探索将模糊请求转化为可执行问题 | 解决代码 Agent 因需求不明导致的探索失败 | 软件工程与代码辅助任务 |
| 29 | http://arxiv.org/abs/2603.05884v2 | Computational Pathology in the Era of Emerging Foundation and Agentic AI -- International Expert Perspectives on Clinical Integration and Translational Readiness | 国际专家视角评估病理 AI 临床整合 readiness | 解决 AI 病理落地面临的经济技术管理挑战 | 计算病理学与临床实践 |
| 30 | http://arxiv.org/abs/2603.05972v1 | THETA: A Textual Hybrid Embedding-based Topic Analysis Framework and AI Scientist Agent for Scalable Computational Social Science | 封装 AI 科学家 Agent 模拟人环专家判断 | 解决传统主题模型语义稀薄与缺乏领域意识 | 计算社会科学与大数据文本分析 |
| 31 | http://arxiv.org/abs/2603.05980v1 | An Interactive Multi-Agent System for Evaluation of New Product Concepts | 构建八虚拟 Agent 团队基于证据评估产品概念 | 解决传统专家评估主观偏差与高成本问题 | 企业新产品概念评估 |
| 32 | http://arxiv.org/abs/2603.06065v1 | ChatShopBuddy: Towards Reliable Conversational Shopping Agents via Reinforcement Learning | 设计分层奖励建模与动态对比策略优化 | 解决购物 Agent 多目标优化与训练效率问题 | 对话式购物助手 |
| 33 | http://arxiv.org/abs/2603.06217v1 | Conversational Demand Response: Bidirectional Aggregator-Prosumer Coordination through Agentic AI | 开发双向自然语言协调机制连接聚合商与产消者 | 解决现有需求响应缺乏透明决策与用户代理 | 住宅能源需求响应 |
| 34 | http://arxiv.org/abs/2603.06271v1 | Agentic retrieval-augmented reasoning reshapes collective reliability under model variability in radiology question answering | 评估 Agent 检索增强推理对模型变异可靠性的影响 | 解决放射学问答中模型决策分散与鲁棒性差 | 临床决策支持与放射学问答 |
| 35 | http://arxiv.org/abs/2603.06503v1 | Beyond Rows to Reasoning: Agentic Retrieval for Multimodal Spreadsheet Understanding and Editing | 替换单次检索为迭代工具调用循环支持端到端 Excel | 解决单 Pass 检索丢失上下文与超出窗口限制 | 企业电子表格理解与编辑 |
| 36 | http://arxiv.org/abs/2603.06856v1 | Evaluating Multi-Agent LLM Architectures for Rare Disease Diagnosis | 评估四种 Agent 拓扑对罕见病诊断准确性影响 | 解决多 Agent 拓扑对诊断准确性影响未探索 | 罕见病诊断辅助 |
| 37 | http://arxiv.org/abs/2603.06902v1 | Empowering Locally Deployable Medical Agent via State Enhanced Logical Skills for FHIR-based Clinical Tasks | 提出 SELSM 框架蒸馏模拟轨迹为实体无关规则 | 解决隐私约束下医疗 Agent 本地部署数据稀缺 | 基于 FHIR 的临床任务本地 Agent |
| 38 | http://arxiv.org/abs/2603.06926v1 | MindfulAgents: Personalizing Mindfulness Meditation via an Expert-Aligned Multi-Agent System | 生成基于专家框架的引导冥想脚本并实时个性化 | 解决冥想应用用户参与度难以维持问题 | 数字心理健康与冥想干预 |
| 39 | http://arxiv.org/abs/2603.04142v1 | A Multi-Agent Framework for Interpreting Multivariate Physiological Time Series | 角色结构化多智能体系统 Vivaldi，解释多变量生理时间序列并生成临床叙事。 | 解决紧急护理中部署可信 AI 解释复杂生理信号的挑战。 | 急诊医疗/生理监测 |
| 40 | http://arxiv.org/abs/2603.04390v1 | A Dual-Helix Governance Approach Towards Reliable Agentic AI for WebGIS Development | 双螺旋治理框架，利用知识图谱基底稳定执行，外部化领域事实与协议。 | 解决 WebGIS 开发中 LLM 上下文限制、遗忘及指令失败等局限性。 | WebGIS 开发/地理空间工程 |
| 41 | http://arxiv.org/abs/2603.04646v1 | HDLFORGE: A Two-Stage Multi-Agent Framework for Efficient Verilog Code Generation with Adaptive Model Escalation | 两阶段多智能体框架，默认紧凑编码器，必要时升级至超强编码器。 | 解决 Verilog 代码生成中生成速度与准确性权衡优化问题。 | 硬件设计/Verilog 代码生成 |
| 42 | http://arxiv.org/abs/2603.04743v1 | DARE: Aligning LLM Agents with the R Statistical Ecosystem via Distribution-Aware Retrieval | 分布感知检索嵌入模型，将数据分布信息融入函数表示进行 R 包检索。 | 解决 LLM 难以检索严谨统计方法及忽略数据分布导致匹配次优问题。 | 数据科学工作流/R 语言生态 |
| 43 | http://arxiv.org/abs/2603.04756v2 | MOOSEnger -- a Domain-Specific AI Agent for the MOOSE Ecosystem | 核心 + 领域架构，结合 RAG 与确定性解析验证工具，将自然语言意图转为输入。 | 解决 MOOSE 仿真环境输入文件设置调试慢及语法严格问题。 | 多物理场仿真/MOOSE 生态 |
| 44 | http://arxiv.org/abs/2603.04921v1 | AILS-NTUA at SemEval-2026 Task 10: Agentic LLMs for Psycholinguistic Marker Extraction and Conspiracy Endorsement Detection | 解耦设计分离语义推理与结构定位，动态判别 CoT 提取标记，反回声室架构检测。 | 解决传统分类器混淆语义推理与结构定位，及模型错误惩罚客观报告问题。 | 心理语言学标记/阴谋论检测 |
| 45 | http://arxiv.org/abs/2603.05027v1 | S5-SHB Agent: Society 5.0 enabled Multi-model Agentic Blockchain Framework for Smart Home | 编排十个专用智能体，自适应 PoW 区块链调整挖矿难度，四层治理模型居民控制。 | 解决智能家居区块链治理中自适应共识、多智能体协调及居民控制缺失问题。 | 智能家居/Society 5.0 |
| 46 | http://arxiv.org/abs/2603.05188v1 | Escaping the Hydrolysis Trap: An Agentic Workflow for Inverse Design of Durable Photocatalytic Covalent Organic Frameworks | LLM 智能体利用化学先验知识引导搜索，满足带隙、带边及水解稳定性标准。 | 解决光催化 COF 设计中稳定性与活性权衡及组合设计空间导航挑战。 | 材料科学/光催化 COF 设计 |
| 47 | http://arxiv.org/abs/2603.05240v1 | GCAgent: Enhancing Group Chat Communication through Dialogue Agents System | LLM 驱动系统增强群聊，包含 Agent Builder、Dialogue Manager 及 Interface Plugins。 | 解决群聊有效性受不活跃及管理挑战阻碍，及 LLM 难以融入多参与者对话问题。 | 在线社交平台/群聊 |
| 48 | http://arxiv.org/abs/2603.05344v3 | "Building Effective AI Coding Agents for the Terminal: Scaffolding, Harness, Context Engineering, and Lessons Learned" | 终端原生编码智能体 OPENDEV，复合 AI 系统架构，双智能体分离规划与执行。 | 解决 IDE 插件向终端原生智能体转变中安全控制及上下文管理挑战。 | 软件开发/终端 AI 辅助 |
| 49 | http://arxiv.org/abs/2603.07278v1 | LLM-FK: Multi-Agent LLM Reasoning for Foreign Key Detection in Large-Scale Complex Databases | 提出全自动化多智能体框架LLM-FK，协调四个专用智能体检测大规模数据库外键。 | 解决传统启发式方法无法捕捉大规模复杂数据库语义依赖及组合搜索空间爆炸问题。 | 数据库管理/外键检测 |
| 50 | http://arxiv.org/abs/2603.07375v1 | Multi-Agentic AI for Conflict-Aware rApp Policy Orchestration in Open RAN | 集成三个专用LLM智能体分析冲突、合成控制管道并细化部署决策，实现rApp编排。 | 解决当前rApp开发手动、脆弱且随xApp多样性增加难以扩展的问题。 | 开放无线接入网/Open RAN |
| 51 | http://arxiv.org/abs/2603.07607v1 | MAS-H2: A Hierarchical Multi-Agent System for Holistic Cloud-Native Autoscaling | 提出分层多智能体系统MAS-H2，分解为战略、规划及执行智能体，解决云原生自动伸缩。 | 解决度量驱动反应式伸缩导致战略空虚、资源浪费及动态负载下性能退化问题。 | 云原生平台/Kubernetes |
| 52 | http://arxiv.org/abs/2603.07709v1 | "YAQIN: Culturally Sensitive, Agentic AI for Mental Healthcare Support Among Muslim Women in the UK" | 设计评估YAQIN，利用AI匿名性及持续支持，通过信仰感知聊天bot及引导日记工具提供支持。 | 解决英国心理健康服务缺乏工具资源 addressing 穆斯林女性文化需求及信任限制问题。 | 心理健康/文化敏感支持 |
| 53 | http://arxiv.org/abs/2603.13353v1 | Optimizing LLM Annotation of Classroom Discourse through Multi-Agent Orchestration | 提出分层成本感知编排框架，包含未验证标注、自验证及分歧裁决三阶段，提高可靠性。 | 解决单次LLM输出对需上下文 pedagogical 判断的高风险教育构建不可靠的问题。 | 教育数据标注/课堂话语 |
| 54 | http://arxiv.org/abs/2603.07940v1 | "AI Agents, Language, Deep Learning and the Next Revolution in Science" | 提出智能人类监督AI智能体 operating 深度学习算法代表科学方法 next 进化，以粒子物理为测试床。 | 解决传统分析方法无法跟上跨学科仪器产生数据规模、多样性及 interdependence 的问题。 | 科学研究/数据驱动科学 |
| 55 | http://arxiv.org/abs/2603.08117v3 | UIS-Digger: Towards Comprehensive Research Agent Systems for Real-world Unindexed Information Seeking | 提出 novel 多智能体框架UIS-Digger，结合双模式浏览 enabling 同时网页搜索及文件解析。 | 解决当前信息寻求智能体 heavily 依赖搜索引擎索引知识， leaving 关键未索引信息 blind spot 问题。 | 信息检索/未索引内容 |
| 56 | http://arxiv.org/abs/2603.12813v1 | Context is all you need: Towards autonomous model-based process design using agentic AI in flowsheet simulations | 多Agent系统分解工艺开发任务 | 化工流程模拟中Agent应用未探索 | 化工流程建模/Chemasim |
| 57 | http://arxiv.org/abs/2603.15672v1 | DRCY: Agentic Hardware Design Reviews | 五Agent流水线，自主获取数据表进行引脚分析 | EDA工具无法验证连接的语义正确性 | 硬件设计审查/AllSpice Hub |
| 58 | http://arxiv.org/abs/2603.09733v1 | FetalAgents: A Multi-Agent System for Fetal Ultrasound Image and Video Analysis | 轻量级智能体协调框架，动态编排视觉专家 | 解决现有工具难以平衡任务精度与全流程 versatility | 胎儿超声图像与视频分析 |
| 59 | http://arxiv.org/abs/2603.09843v1 | RecThinker: An Agentic Framework for Tool-Augmented Reasoning in Recommendation | 采用 Analyze-Plan-Act 范式，主动调用工具填补信息缺口 | 解决被动信息获取导致用户画像碎片化推荐次优问题 | 推荐系统 |
| 60 | http://arxiv.org/abs/2603.10133v1 | Agentic Control Center for Data Product Optimization | specialized AI 代理在连续优化循环中自动化数据产品改进 | 解决生产有用数据产品需领域专家手工 crafted 资产挑战 | 数据产品优化 |
| 61 | http://arxiv.org/abs/2603.10161v2 | Omics Data Discovery Agents | 代理框架获取文章并将非结构化信息转化为可搜索对象 | 解决生物医学文献中数据功能上不可访问难以复用问题 | 组学数据发现 |
| 62 | http://arxiv.org/abs/2603.13380v1 | Querying Everything Everywhere All at Once: Supervaluationism for the Agentic Lakehouse | 提出超估值语义查询路径，跨分支回答问题 | 解决 Agentic analytics 下多版本系统中消费者需知生命周期 | 数据湖仓智能体分析 |
| 63 | http://arxiv.org/abs/2603.13384v1 | VulnAgent-X: A Layered Agentic Framework for Repository-Level Vulnerability Detection | 分层框架集成风险筛查、上下文扩展及动态验证 | 解决现有方法受限于局部代码视图及缺乏验证可靠性 | 仓库级漏洞检测 |
| 64 | http://arxiv.org/abs/2603.10646v1 | ESG Reporting Lifecycle Management with Large Language Models and AI Agents | 多 AI 代理提取验证信息更新报告，嵌入 agentic 组件 | 解决 ESG 报告生成因非结构化数据及复杂要求具挑战性 | ESG 报告生命周期管理 |
| 65 | http://arxiv.org/abs/2603.10673v1 | Breaking User-Centric Agency: A Tri-Party Framework for Agent-Based Recommendation | 三方框架协调用户效用、物品曝光及平台级公平 | 解决现有 agentic 推荐 predominantly 用户中心忽视其他利益相关者 | 基于代理的推荐系统 |
| 66 | http://arxiv.org/abs/2603.10764v1 | HeartAgent: An Autonomous Agent System for Explainable Differential Diagnosis in Cardiology | 集成定制工具与数据，编排多专用子代理复杂推理 | 解决现有 AI 诊断方法知识不足推理支持弱可解释性差 | 心脏病学可解释诊断 |
| 67 | http://arxiv.org/abs/2603.10852v1 | UltrasoundAgents: Hierarchical Multi-Agent Evidence-Chain Reasoning for Breast Ultrasound Diagnosis | 分层多智能体框架，主智能体定位病灶，子智能体分析局部属性并整合证据 | 现有方法缺乏细粒度病灶线索，证据可追溯性和临床审查受限 | 乳腺超声诊断与医疗辅助 |
| 68 | http://arxiv.org/abs/2603.11025v1 | LLMGreenRec: LLM-Based Multi-Agent Recommender System for Sustainable E-Commerce | 多智能体框架协作分析用户交互，迭代提示优化以推导绿色导向意图 | 传统会话系统难以捕捉环保选择细微意图，绿色意图与行动存在差距 | 可持续电子商务推荐系统 |
| 69 | http://arxiv.org/abs/2603.11048v1 | COMIC: Agentic Sketch Comedy Generation | 全自动 AI 系统，基于真实制作角色的人口智能体通过迭代竞争优化输出 | 喜剧视频生成质量低，缺乏基于观众偏好的自动化幽默评估机制 | 短视频喜剧内容自动生成 |
| 70 | http://arxiv.org/abs/2603.11356v1 | Resolving Java Code Repository Issues with iSWE Agent | 自动化问题 resolver，包含定位和编辑子智能体，访问基于规则的 Java 静态分析工具 | 现有模型主要关注 Python，企业级 Java 自动化问题解析探索不足 | Java 代码仓库问题自动修复 |
| 71 | http://arxiv.org/abs/2603.11399v1 | Entropy Guided Diversification and Preference Elicitation in Agentic Recommendation Systems | 交互式决策支持系统，用熵量化不确定性指导自适应偏好 elicitation | 用户查询模糊导致交互过多或过早收敛搜索空间，推荐过自信 | 电子商务推荐系统与用户意图 |
| 72 | http://arxiv.org/abs/2603.11721v1 | When OpenClaw Meets Hospital: Toward an Agentic Operating System for Dynamic Clinical Workflows | 适应医院环境的架构，包含受限执行环境、文档中心交互与分页索引记忆 | 自主智能体部署于医疗环境难，受限于可靠性、安全风险与长期记忆机制 | 医院动态临床工作流自动化 |
| 73 | http://arxiv.org/abs/2603.11828v1 | Large language models for optical network O&M: Agent-embedded workflow for automation | 多智能体协作 O&M 架构，集成 LLM 能力与现有 O&M 工具针对关键任务 | 现有 O&M 方法难满足智能化与效率需求，缺乏 LLM 有效集成至工作流的系统研究 | 光网络运营与维护自动化 |
| 74 | http://arxiv.org/abs/2603.11927v1 | CogSearch: A Cognitive-Aligned Multi-Agent Framework for Proactive Decision Support in E-Commerce Search | 认知导向多智能体框架，协同四个专用智能体模拟人类认知工作流分解意图 | 现代电商搜索引擎基于被动检索，难支持复杂决策，用户 overwhelmed by 认知摩擦 | 电子商务搜索与决策支持 |
| 75 | http://arxiv.org/abs/2603.13676v1 | TheraAgent: Multi-Agent Framework with Self-Evolving Memory and Evidence-Calibrated Reasoning for PET Theranostics | 多专家特征提取与自进化记忆，解决 PET 诊疗预测数据稀缺与推理幻觉问题 | PET 诊疗响应预测难，数据少且易幻觉 | 医疗/PET 诊疗预测 |
| 76 | http://arxiv.org/abs/2603.13710v1 | InterventionLens: A Multi-Agent Framework for Detecting ASD Intervention Strategies in Parent-Child Shared Reading | 协作多智能体架构集成多模态内容，无需训练自动检测干预策略 | 家庭干预策略分析依赖专家标注，成本高难扩展 | 医疗/自闭症家庭干预 |
| 77 | http://arxiv.org/abs/2603.13723v1 | Do AI Agents Really Improve Code Readability? | 分析 AI 智能体重构对代码可读性的实际影响，发现主要优化逻辑复杂度 | unclear AI 重构是否具体提升代码可读性 | 软件工程/代码重构 |
| 78 | http://arxiv.org/abs/2603.13724v1 | Testing with AI Agents: An Empirical Study of Test Generation Frequency, Quality, and Coverage | 实证分析智能体生成测试的频率、结构特征及覆盖率，对比人类编写测试 | 缺乏对真实开发场景中智能体生成测试的了解 | 软件工程/测试生成 |
| 79 | http://arxiv.org/abs/2603.13942v1 | AI Agents in Financial Markets: Architecture, Applications, and Systemic Implications | 提出金融 AI 智能体四层架构及代理金融市场模型，分析系统性影响 | 金融自动化从孤立预测转向集成决策系统的架构与风险分析 | 金融市场/系统性风险 |
| 80 | http://arxiv.org/abs/2603.13956v1 | EviAgent: Evidence-Driven Agent for Radiology Report Generation | 协调透明推理轨迹，整合多维视觉专家与检索机制提供显式证据 | 放射报告生成缺乏显式视觉证据支持，决策不可追溯 | 医疗/放射报告生成 |
| 81 | http://arxiv.org/abs/2603.14054v1 | LegacyTranslate: LLM-based Multi-Agent Method for Legacy Code Translation | 三智能体框架分工处理初始翻译、API 对齐与迭代 refinement | 大遗留系统现代化迁移中 LLM 直接翻译编译失败率高 | 软件工程/代码迁移 |
| 82 | http://arxiv.org/abs/2603.14099v1 | DeepFix: Debugging and Fixing Machine Learning Workflow using Agentic AI | 利用智能体 AI 框架自动化测试 ML 管道，生成详细 bug 报告与修复建议 | 现代 ML 模型系统测试难，现有方法难提供修复信息 | 机器学习工程/调试 |
| 83 | http://arxiv.org/abs/2603.14288v1 | Beyond Prompting: An Autonomous Framework for Systematic Factor Investing via Agentic AI | 自主框架内生化 formulates 可解释交易信号，严格实证纪律防止数据 snooping | 系统化因子投资依赖手动提示，缺乏自导向引擎 | 金融/因子投资 |
| 84 | http://arxiv.org/abs/2603.14790v1 | Mind-of-Director: Multi-modal Agent-Driven Film Previsualization via Collaborative Decision-Making | orchestrate多智能体协作生成电影预可视化序列 | 电影制作中创意到视觉序列转化的协作效率低 | 电影预可视化与制作 |
| 85 | http://arxiv.org/abs/2603.14864v1 | Shopping Companion: A Memory-Augmented LLM Agent for Real-World E-Commerce Tasks | 统一框架联合处理记忆检索与购物辅助，支持用户干预 | 缺乏长期偏好感知购物基准与端到端优化设计 | 电子商务购物任务 |
| 86 | http://arxiv.org/abs/2603.15260v1 | AGCD: Agent-Guided Cross-Modal Decoding for Weather Forecasting | 插件式解码时先验注入范式，从当前大气导出状态条件物理先验 | 现有物理先验方法缺乏状态自适应与样本特定可控性 | 气象预报物理一致性 |
| 87 | http://arxiv.org/abs/2603.15351v1 | PMAx: An Agentic Framework for AI-Driven Process Mining | 隐私保护多智能体架构，分离计算与解释，本地执行分析脚本 | LLM直接分析原始事件日志导致幻觉与数据隐私风险 | 业务流程挖掘与分析 |
| 88 | http://arxiv.org/abs/2603.15364v1 | CRASH: Cognitive Reasoning Agent for Safety Hazards in Autonomous Driving | 基于LLM代理自动化推理车祸报告，统一表示生成摘要与归因 | 自动驾驶系统架构异质性限制事故调查标准化与安全分析 | 自动驾驶安全事故分析 |
| 89 | http://arxiv.org/abs/2603.15491v1 | Agentic workflow enables the recovery of critical materials from complex feedstocks via selective precipitation | 部署一系列AI代理与自动化仪器从真实原料回收关键材料 | 关键材料回收开发周期长，效率低 | 关键材料回收与分离 |
| 90 | http://arxiv.org/abs/2603.15594v1 | OpenSeeker: Democratizing Frontier Search Agents by Fully Open-Sourcing Training Data | 首个完全开源搜索代理，通过事实 grounded 合成与去噪轨迹合成 | 高性能搜索代理开发受限于缺乏透明高质量训练数据 | 前沿搜索代理研究与开发 |
| 91 | http://arxiv.org/abs/2603.17392v1 | Agentic Cognitive Profiling: Realigning Automated Alzheimer's Disease Detection with Clinical Construct Validity | 将标准化评估分解为原子认知任务，委托确定性函数调用量化 | 阿尔茨海默病自动筛查牺牲临床协议构造效度问题 | 阿尔茨海默病临床筛查 |
| 92 | http://arxiv.org/abs/2603.17626v1 | A Multi-Agent System for Building-Age Cohort Mapping to Support Urban Energy Planning | 三关键Agent融合异构数据源，BuildingAgeCNN卫星分类器 | 城市建筑存量年龄分布确定依赖传感器数据存在不一致与缺口 | 城市能源规划 |
| 93 | http://arxiv.org/abs/2603.17930v1 | Interpretable Traffic Responsibility from Dashcam Video via Legal Multi Agent Reasoning | 两阶段框架：交通事故理解模块加法律多Agent框架输出责任模式 | 行车记录仪视频证据转化为法律责任认定依赖人类专家问题 | 中国交通法规系统事故认定 |
| 94 | http://arxiv.org/abs/2603.18273v1 | EDM-ARS: A Domain-Specific Multi-Agent System for Automated Educational Data Mining Research | 五专用LLM Agent通过状态机协调器编排，支持修订循环与沙盒代码执行 | 教育数据挖掘研究自动化端到端流程缺乏领域感知框架 | 教育研究领域 |
| 95 | http://arxiv.org/abs/2603.19059v1 | SignAgent: Agentic LLMs for Linguistically-Grounded Sign Language Annotation and Dataset Curation | SignAgent Orchestrator协调语言工具套件，SignGraph提供词汇与语言接地 | 传统SL计算方法在gloss级别操作忽略语言细微差别，手动标注瓶颈 | 手语标注与数据集管理 |
| 96 | http://arxiv.org/abs/2603.15952v1 | Protein Design with Agent Rosetta: A Case Study for Specialized Scientific Agents | LLM 智能体配对 Rosetta 环境，迭代优化蛋白质设计 | 解决 ML 方法仅限标准氨基酸及目标狭窄的问题 | 蛋白质设计 |
| 97 | http://arxiv.org/abs/2603.16008v1 | CoDesignAI: An AI-Enabled Multi-Agent, Multi-User System for Collaborative Urban Design at the Conceptual Stage | 多用户与多智能体协作，支持概念阶段城市协同设计 | 解决公众参与效率低及可扩展性差的问题 | 城市协同设计 |
| 98 | http://arxiv.org/abs/2603.16107v1 | RepoReviewer: A Local-First Multi-Agent Architecture for Repository-Level Code Review | 本地优先多智能体架构，分解仓库级代码审查任务 | 解决单通审查降低相关性及增加重复的问题 | 代码仓库审查 |
| 99 | http://arxiv.org/abs/2603.16110v1 | VIGIL: Towards Edge-Extended Agentic AI for Enterprise IT Support | 边缘扩展智能体系统，在用户设备上进行诊断与修复 | 解决企业 IT 支持异构设备及长尾故障难集中处理的问题 | 企业 IT 支持 |
| 100 | http://arxiv.org/abs/2603.16215v1 | CoMAI: A Collaborative Multi-Agent Framework for Robust and Equitable Interview Evaluation | 模块化任务分解架构，多智能体协作评估面试 | 解决单一智能体评估主观偏差及安全性不足的问题 | 面试评估 |
| 101 | http://arxiv.org/abs/2603.16458v1 | Agentic AI for SAGIN Resource Management_Semantic Awareness, Orchestration, and Optimization | 分层智能体 -RL 协作机制，LLM 塑造 RL 奖励函数管理资源 | 解决 SAGIN 异构基础设施及动态拓扑资源管理挑战 | 6G 网络资源管理 |
| 102 | http://arxiv.org/abs/2603.16546v1 | DanceHA: A Multi-Agent Framework for Document-Level Aspect-Based Sentiment Analysis | 分治策略多智能体框架，处理文档级情感强度分析 | 解决非正式写作风格及文档级 ABSIA 任务未充分探索问题 | 文档级情感分析 |
| 103 | http://arxiv.org/abs/2603.17043v1 | OpenQlaw: An Agentic AI Assistant for Analysis of 2D Quantum Materials | 智能体编排系统，核心 LLM 协调领域专家 MLLM | 解决量子材料分析需动态推理及认知过载问题 | 量子材料分析 |
| 104 | http://arxiv.org/abs/2603.17179v1 | Ablation Study of a Fairness Auditing Agentic System for Bias Mitigation in Early-Onset Colorectal Cancer Detection | 双智能体架构审计 biomedical ML 模型公平性 | 解决临床 AI 缺乏监督及领域专家导致算法偏见问题 | 医疗公平性审计 |
| 105 | http://arxiv.org/abs/2603.17204v1 | CODMAS: A Dialectic Multi-Agent Collaborative Framework for Structured RTL Optimization | 辩证多智能体系统，结合结构化推理与领域感知代码生成 | 解决 RTL 代码优化需改进 PPA 及自动化程度低的问题 | RTL 代码优化 |

[返回目录](#目录)

<a id="cat-06"></a>

## Agent规划与推理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2603.00977v1 | HiMAC: Hierarchical Macro-Micro Learning for Long-Horizon LLM Agents | 分层强化学习框架，显式分解宏观规划与微观执行，优化长程决策。 | 解决扁平自回归策略在长程任务中探索低效与错误传播问题。 | 长程交互决策任务与 LLM 智能体 |
| 2 | http://arxiv.org/abs/2603.01410v1 | GraphScout: Empowering Large Language Models with Intrinsic Exploration Ability for Agentic Graph Reasoning | 训练中心框架，使模型自主交互知识图合成结构化数据以后训练 LLM。 | 解决现有方法依赖手动设计指导及预定义工具限制图探索的问题。 | 知识图检索增强生成与推理 |
| 3 | http://arxiv.org/abs/2603.01692v2 | Reasoning as Gradient: Scaling MLE Agents Beyond Tree Search | 将结构化诊断推理映射为梯度计算，成功记忆映射为动量，实现基于梯度的优化。 | 解决 LLM 代理依赖树搜索导致 exhaustive enumeration 效率低下的问题。 | 机器学习工程 (MLE) |
| 4 | http://arxiv.org/abs/2603.01853v1 | Let the Agent Search: Autonomous Exploration Beats Rigid Workflows in Temporal Question Answering | 赋予现成 LLM 自主权，通过通用搜索工具动态检索，迭代交互时序知识图谱。 | 解决基于 LLM 的方法依赖刚性手工检索工作流或昂贵监督微调的问题。 | 时序知识图谱问答 |
| 5 | http://arxiv.org/abs/2603.01896v2 | Agentic Code Reasoning | 提出半形式化推理，要求 Agent 构建明确前提、追踪执行路径并推导形式结论。 | 解决 LLM 代理在不执行代码情况下探索代码库及推理语义能力不足的问题。 | 代码语义分析 |
| 6 | http://arxiv.org/abs/2603.06064v1 | Agentic LLM Planning via Step-Wise PDDL Simulation: An Empirical Characterisation | 通过 PDDL 模拟引擎暴露规划操作为工具调用 | 解决 LLM 直接规划缺乏环境反馈验证问题 | 自主机器人任务规划 |
| 7 | http://arxiv.org/abs/2603.04750v1 | HiMAP-Travel: Hierarchical Multi-Agent Planning for Long-Horizon Constrained Travel | 分层多智能体框架，拆分战略规划与并行日级执行，事务监控 enforcing 约束。 | 解决顺序 LLM 智能体在长程规划中偏离全局硬约束问题。 | 旅行规划/长程任务 |
| 8 | http://arxiv.org/abs/2603.07148v1 | Agentic Planning with Reasoning for Image Styling via Offline RL | 提出基于工具的智能体规划方法，结合组合式编辑工具与链式推理，利用离线RL优化。 | 解决直接提示编辑复杂图像变换失败及主观提示理解 nuanced 不足的问题。 | 图像编辑/视觉处理 |
| 9 | http://arxiv.org/abs/2603.07528v2 | TableMind++: An Uncertainty-Aware Programmatic Agent for Tool-Augmented Table Reasoning | 引入不确定性感知推理框架，通过记忆引导计划剪枝及置信度动作细化缓解幻觉。 | 解决单轮推理范式上下文溢出及数值敏感性弱，以及LLM随机性导致幻觉的问题。 | 表格推理/数据分析 |
| 10 | http://arxiv.org/abs/2603.07915v1 | Ares: Adaptive Reasoning Effort Selection for Efficient LLM Agents | 提出每步动态推理努力选择框架Ares，利用轻量级路由器预测每步最低适当推理级别。 | 解决静态推理策略无效，低努力导致性能下降，随机选择无法保持 accuracy 或降低成本问题。 | 高效LLM智能体/推理优化 |
| 11 | http://arxiv.org/abs/2603.12109v1 | On Information Self-Locking in Reinforcement Learning for Active Reasoning of LLM agents | 发现信息自锁现象，注入方向性批评信号突破 | LLM Agent主动推理中停止询问 informative 问题 | 主动推理LLM Agent |
| 12 | http://arxiv.org/abs/2603.12396v1 | Test-Time Strategies for More Efficient and Accurate Agentic RAG | 上下文化模块和去重模块优化Search-R1 | Agentic RAG重复检索、上下文整合差 | 检索增强生成Agent |
| 13 | http://arxiv.org/abs/2603.12634v1 | Spend Less, Reason Better: Budget-Aware Value Tree Search for LLM Agents | 预算感知价值树，剩余资源比例作为缩放指数 | 测试时扩展将计算视为丰富资源导致浪费 | 多跳推理LLM Agent |
| 14 | http://arxiv.org/abs/2603.12710v1 | AI Planning Framework for LLM-Based Web Agents | 将Web任务形式化为序列决策，映射规划范式 | Web Agent作为黑盒难以诊断失败原因 | Web自动化Agent |
| 15 | http://arxiv.org/abs/2603.12740v1 | ToolTree: Efficient LLM Agent Tool Planning via Dual-Feedback Monte Carlo Tree Search and Bidirectional Pruning | 双阶段LLM评估+双向剪枝的MCTS规划 | 当前工具规划缺乏前瞻性、忽略工具依赖 | 多步任务LLM Agent |
| 16 | http://arxiv.org/abs/2603.11068v1 | From Phase Prediction to Phase Design: A ReAct Agent Framework for High-Entropy Alloy Discovery | 提出 ReAct 智能体自主提议并迭代 refine 合金成分 | 解决高维逆设计问题，传统试错法效率低 | 高熵合金发现 |
| 17 | http://arxiv.org/abs/2603.09835v1 | Chow-Liu Ordering for Long-Context Reasoning in Chain-of-Agents | 利用 Chow-Liu 树学习依赖结构，优先处理强相关块 | 解决长上下文推理中分块顺序导致的信息损失问题 | 长上下文推理智能体 |
| 18 | http://arxiv.org/abs/2603.11082v1 | Quality-Driven Agentic Reasoning for LLM-Assisted Software Design: Questions-of-Thoughts (QoT) as a Time-Series Self-QA Chain | 将用户目标转化为有序工程步骤及逐步自问验证约束 | 解决 LLM 辅助软件开发实现不完整模块化弱安全问题 | LLM 辅助软件设计 |
| 19 | http://arxiv.org/abs/2603.11798v1 | DocSage: An Information Structuring Agent for Multi-Doc Multi-Entity Question Answering | 端到端智能体框架集成动态 schema 发现、结构化提取与 schema 感知推理 | 标准 RAG 粗粒度检索遗漏事实，图 RAG 难整合碎片化复杂关系网络 | 多文档多实体问答与信息结构化 |
| 20 | http://arxiv.org/abs/2603.13767v1 | Retrieve, Schedule, Reflect: LLM Agents for Chip QoR Optimization | 基于 RAG 与语言反思的代理框架，通过 Pareto 驱动反馈优化芯片调度 | 芯片设计优化依赖人工专家干预，自动化程度低 | 芯片设计/QoR 优化 |
| 21 | http://arxiv.org/abs/2603.13853v2 | APEX-Searcher: Augmenting LLMs' Search Capabilities through Agentic Planning and Execution | 两阶段智能体框架解耦检索为规划与执行，优化战略规划与子任务执行 | 复杂多跳问答中检索执行路径模糊及端到端 RL 奖励稀疏 | 多跳检索/复杂任务求解 |
| 22 | http://arxiv.org/abs/2603.14229v1 | Agentic DAG-Orchestrated Planner Framework for Multi-Modal, Multi-Hop Question Answering in Hybrid Data Lakes | 编译 NL 查询为 DAG 执行计划，协调异构源并发检索与结果合并 | 混合数据湖 NL 问答缺乏多跳推理支持，效率低且易泄露 | 企业数据湖/问答 |
| 23 | http://arxiv.org/abs/2603.14248v1 | Why Do LLM-based Web Agents Fail? A Hierarchical Planning Perspective | 提出分层规划框架分析 Web 智能体，发现低层执行是主要瓶颈 | Web 智能体在真实长程任务上可靠性远不及人类，失败原因不明 | Web 导航/智能体可靠性 |
| 24 | http://arxiv.org/abs/2603.14799v1 | Universe Routing: Why Self-Evolving Agents Need Epistemic Control | 形式化宇宙路由问题，分类问题到互斥信念空间 before 求解 | 混合不相容推理框架导致的结构性失败 | 自进化智能体推理控制 |
| 25 | http://arxiv.org/abs/2603.15726v1 | MiroThinker-1.7 & H1: Towards Heavy-Duty Research Agents via Verification | 引入验证到推理过程，局部与全局评估中间决策与整体轨迹 | 复杂长视野推理任务可靠性不足，缺乏连贯证据链支持 | 深度研究与科学推理任务 |
| 26 | http://arxiv.org/abs/2603.15797v2 | OMNIFLOW: A Physics-Grounded Multimodal Agent for Generalized Scientific Reasoning | 神经符号架构 grounded 冻结多模态LLM于物理定律，无需域特定更新 | LLM在处理PDE governed 连续时空动态时产生非物理幻觉 | 广义科学推理与物理模拟 |
| 27 | http://arxiv.org/abs/2603.16777v1 | Anticipatory Planning for Multimodal AI Agents | 两阶段 RL 框架，执行前预测短程轨迹以训练预期推理 | 解决现有系统反应式优化，缺乏未来状态推理的问题 | 多模态 anticipatory planning |

[返回目录](#目录)

<a id="cat-07"></a>

## 多Agent协作与通信

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2603.00993v1 | CollabEval: Enhancing LLM-as-a-Judge via Multi-Agent Collaboration | 三阶段协作评估框架，通过多轮讨论与共识检查提升判断一致性。 | 解决单模型评估存在的判断不一致与预训练数据偏见问题。 | LLM 生成内容评估与裁判系统 |
| 2 | http://arxiv.org/abs/2603.01089v1 | CARD: Towards Conditional Design of Multi-agent Topological Structures | 条件图生成框架，将动态环境信号纳入图构建，实现拓扑自适应。 | 解决多代理系统通信拓扑固定，无法适应模型升级或资源变化问题。 | 动态环境下的多代理协作系统 |
| 3 | http://arxiv.org/abs/2603.01213v2 | Can AI Agents Agree? | 在拜占庭共识游戏中评估 LLM 代理，发现有效 agreement 不可靠且随组大小退化。 | 揭示当前 LLM 代理群在 adversarial 共识设置中缺乏可靠的协调 emergent 能力。 | 多代理协调与分布式共识系统 |
| 4 | http://arxiv.org/abs/2603.01221v1 | Epistemic Gain, Aleatoric Cost: Uncertainty Decomposition in Multi-Agent Debate for Math Reasoning | 贝叶斯不确定性分析框架，分解认知与偶然不确定性，优化辩论策略。 | 解决多代理辩论中准确性提升伴随熵增及模型组合差异大的问题。 | 数学推理中的多代理辩论系统 |
| 5 | http://arxiv.org/abs/2603.03005v1 | OrchMAS: Orchestrated Reasoning with Multi Collaborative Heterogeneous Scientific Expert Structured Agents | 双层编排框架，动态构建领域感知推理管道实例化专家代理。 | 解决科学领域多步推理中静态提示、角色僵化及延迟问题。 | 科学领域复杂推理任务 |
| 6 | http://arxiv.org/abs/2603.03565v1 | Build, Judge, Optimize: A Blueprint for Continuous Improvement of Multi-Agent Consumer Assistants | 提出多 facets 评估 rubric 与 LLM-as-judge 管道，优化多代理系统。 | 解决多轮交互评估难及紧密耦合多代理系统优化挑战。 | 对话式购物助手 |
| 7 | http://arxiv.org/abs/2603.06683v1 | ECHO: Event-Centric Hypergraph Operations via Multi-Agent Collaboration for Multimedia Event Extraction | 多代理框架迭代优化多媒体事件超图，引入 Link-then-Bind 策略。 | 解决线性端到端生成中跨模态错位导致下游角色分配错误问题。 | 多媒体事件提取 |
| 8 | http://arxiv.org/abs/2603.03753v1 | Agentic Peer-to-Peer Networks: From Content Distribution to Capability and Action Sharing | 提出基于平面参考架构，解耦连接/身份、语义发现与执行。 | 解决客户端自主代理协作中交换能力动作异构及不安全委托问题。 | 代理对等网络与协作 |
| 9 | http://arxiv.org/abs/2603.03780v1 | MACC: Multi-Agent Collaborative Competition for Scientific Exploration | 制度架构整合黑板式共享工作空间与激励透明可复现机制。 | 解决单一高能力代理无法克服科学探索结构性限制及复现问题。 | 科学探索多代理协作竞争 |
| 10 | http://arxiv.org/abs/2603.01654v1 | CeProAgents: A Hierarchical Agents System for Automated Chemical Process Development | 分层多 Agent 系统，集成动态聊天组与结构化工作流，分工协作。 | 解决化学过程开发涉及多 facets 知识整合与参数模拟的复杂性挑战。 | 化学工程过程开发 |
| 11 | http://arxiv.org/abs/2603.01755v1 | Federated Agentic AI for Wireless Networks: Fundamentals, Approaches, and Applications | 提出联邦 Agentic AI 方法，利用 FL 类型加强 Agent 循环特定组件，无需交换原始数据。 | 解决无线网资源受限、分布广及数据异构导致集中式 Agentic AI 挑战的问题。 | 无线网络服务 |
| 12 | http://arxiv.org/abs/2603.02438v1 | ORCA: Orchestrated Reasoning with Collaborative Agents for Document Visual Question Answering | 推理 Agent 分解查询，路由机制激活专用 Agent dock，辩论机制确保可靠性。 | 解决 DocVQA 在复杂推理及多步工作流下难以分解问题及利用专用处理路径的问题。 | 文档视觉问答 |
| 13 | http://arxiv.org/abs/2603.02630v1 | MASPOB: Bandit-Based Prompt Optimization for Multi-Agent Systems with Graph Neural Networks | 利用 UCB 量化不确定性，集成 GNN 捕获结构先验，坐标上升分解优化。 | 解决 MAS 提示优化样本效率低、拓扑诱导耦合及搜索空间组合爆炸的问题。 | 多 Agent 系统提示优化 |
| 14 | http://arxiv.org/abs/2603.02697v1 | ShareVerse: Multi-Agent Consistent Video Generation for Shared World Modeling | 空间拼接策略建模更广环境，跨 Agent 注意力块保证重叠区域共享世界一致性。 | 解决现有作品缺乏支持统一共享世界构建及多 Agent 交互的问题。 | 多 Agent 共享世界视频生成 |
| 15 | http://arxiv.org/abs/2603.05789v3 | The Coordination Gap: Multi-Agent Alternation Metrics for Temporal Fairness in Repeated Games | 提出时间敏感的交替指标评估协调质量 | 解决传统指标忽视时间结构导致协调误判 | 多 Agent 博弈与重复游戏中的公平性 |
| 16 | http://arxiv.org/abs/2603.06737v1 | Agent Hunt: Bounty Based Collaborative Autoformalization With LLM Agents | 实现基于赏金市场的分布式协作形式化证明 | 解决静态中央规划难以扩展自动形式化工作 | 交互式定理证明与理论构建 |
| 17 | http://arxiv.org/abs/2603.06801v1 | Breaking the Martingale Curse: Multi-Agent Debate via Asymmetric Cognitive Potential Energy | 利用不对称认知势能打破多 Agent 辩论鞅诅咒 | 解决相关错误导致 Agent 收敛至错误共识 | 大语言模型推理增强 |
| 18 | http://arxiv.org/abs/2603.04474v1 | From Spark to Fire: Modeling and Mitigating Error Cascades in LLM-Based Multi-Agent Collaboration | 提出传播动力学模型与基于谱系图的治理层，抑制多智能体错误级联放大。 | 解决 LLM 多智能体协作中微小误差固化为系统级错误共识问题。 | LLM 多智能体协作系统 |
| 19 | http://arxiv.org/abs/2603.04042v1 | Low-Altitude Agentic Networks for Optical Wireless Communication and Sensing: An Oceanic Scenario | 引入协作低空平台作为自适应智能体，耦合波束跟踪与资源优化实现弹性网络。 | 解决海洋跨域连接中无线电波无法高效桥接水 - 空接口问题。 | 海洋气象监测/离岸勘探 |
| 20 | http://arxiv.org/abs/2603.04528v1 | Discovering mathematical concepts through a multi-agent system | 多智能体模型自主提出猜想并尝试证明，基于反馈与演化数据分布决策。 | 解决数学概念发现中实验、证明与反例过程自动化问题。 | 计算数学发现/研究 |
| 21 | http://arxiv.org/abs/2603.04977v1 | "Think, Then Verify: A Hypothesis-Verification Multi-Agent Framework for Long Video Understanding" | 将视频问答重构为假设验证过程，Thinker 重写假设，Verifier 接地测试线索。 | 解决长视频理解中语义漂移、相关驱动错误及反应式检索积累问题。 | 长视频理解/问答 |
| 22 | http://arxiv.org/abs/2603.07456v1 | Agentic AI-Driven UAV Network Deployment: A LLM-Enhanced Exact Potential Game Approach | 提出双空间尺度拓扑优化框架，基于精确势博弈，引入LLM作为知识驱动决策增强器。 | 解决UAV网络拓扑优化中离散链接与连续部署参数强耦合导致的混合整数非凸问题。 | 无人机网络部署/通信 |
| 23 | http://arxiv.org/abs/2603.08059v1 | ImageEdit-R1: Boosting Multi-Agent Image Editing via Reinforcement Learning | 提出多智能体框架ImageEdit-R1，利用RL协调专用预训练视觉语言及生成智能体间高层决策。 | 解决现有图像编辑系统 struggle 复杂间接或多步用户指令， hindering  nuanced 上下文感知编辑问题。 | 图像编辑/多模态处理 |
| 24 | http://arxiv.org/abs/2603.12736v1 | Conflict Mitigation in Shared Environments using Flow-Aware Multi-Agent Path Finding | 将不可控Agent运动模式学习集成到MAPF | 大型机器人群在动态环境中冲突延迟 | 多机器人系统/共享环境 |
| 25 | http://arxiv.org/abs/2603.12829v1 | coDrawAgents: A Multi-Agent Dialogue Framework for Compositional Image Generation | 四Agent对话框架：解释器、规划器、检查器、绘制器 | 文本生成图像难以忠实组合多对象 | 组合式图像生成 |
| 26 | http://arxiv.org/abs/2603.13189v1 | LLM Constitutional Multi-Agent Governance | 宪法多Agent治理框架，伦理合作分数ECS | LLM影响策略可能侵蚀Agent自主性 | 网络化Agent群体治理 |
| 27 | http://arxiv.org/abs/2603.09890v1 | Influencing LLM Multi-Agent Dialogue via Policy-Parameterized Prompts | 将提示视为动作，参数化构建轻量级策略影响对话行为 | 解决现有多智能体行为研究依赖 ad hoc 提示缺乏原则 | LLM 多智能体对话 |
| 28 | http://arxiv.org/abs/2603.11515v1 | Multi-Agent Collaboration for Automated Design Exploration on High Performance Computing Systems | MADA 框架协调专用智能体，作业管理、几何生成与逆向设计智能体协作 | 科学挑战需探索巨大设计空间，手动工作流设置繁琐难以规模化测试 | 高性能计算系统自动化设计探索 |
| 29 | http://arxiv.org/abs/2603.11890v1 | QUARE: Multi-Agent Negotiation for Balancing Quality Attributes in Requirements Engineering | 多智能体框架将需求分析公式化为五个质量专用智能体间的结构化谈判 | 自动化 RE 难因需平衡多冲突质量属性，现有 LLM 方法依赖单体推理或隐式聚合 | 软件工程需求工程与质量平衡 |
| 30 | http://arxiv.org/abs/2603.13840v1 | ClimateAgents: A Multi-Agent Research Assistant for Social-Climate Dynamics Analysis | 协作领域专用智能体集体执行研究工作流，整合多模态数据与自动推理 | 传统气候分析缺乏灵活性，难以融入跨领域社会经济知识 | 社会气候动态分析 |
| 31 | http://arxiv.org/abs/2603.14052v2 | A Multi-Agent Perception-Action Alliance for Efficient Long Video Reasoning | 多轮感知 - 行动探索联盟，智能体协作评分与共识决策优化长视频推理 | 长视频推理效率低，难以扩展至真实世界长视频 | 长视频理解/问答 |
| 32 | http://arxiv.org/abs/2603.14312v1 | Autonomous Agents Coordinating Distributed Discovery Through Emergent Artifact Exchange | 独立智能体无中心协调进行研究，通过工件交换与全局索引协调需求 | 科学研究缺乏自主协调框架，难以追踪计算血缘 | 科学发现/分布式研究 |
| 33 | http://arxiv.org/abs/2603.18043v1 | The Provenance Paradox in Multi-Agent LLM Routing: Delegation Contracts and Attested Identity in LDP | 扩展 LDP 协议引入委托合同与认证身份模型，解决质量路由悖论 | 多智能体系统委托任务时无法治理不可验证的质量声明 | 多智能体路由/协议 |
| 34 | http://arxiv.org/abs/2603.14629v1 | ResearchPilot: A Local-First Multi-Agent System for Literature Synthesis and Related Work Drafting | 开源自托管多智能体系统，检索论文提取发现并合成跨论文模式 | 文献综述辅助缺乏透明且可本地部署的多智能体系统 | 学术研究/文献综述 |
| 35 | http://arxiv.org/abs/2603.17302v1 | IEMAS: An Incentive-Efficiency Routing Framework for Open Agentic Web Ecosystems | 集成概率预测模型与VCG双向匹配机制，利用KV缓存亲和性 | 分布式MAS中自利Agent的全局效率与资源复用问题 | 开放Agentic Web生态系统 |
| 36 | http://arxiv.org/abs/2603.16264v1 | Adaptive Theory of Mind for LLM-based Multi-Agent Coordination | 自适应心智理论智能体，对齐伙伴的心智理论阶数 | 解决心智理论阶数不匹配导致协调 impaired 的问题 | 多智能体协调 |

[返回目录](#目录)

<a id="cat-08"></a>

## 人机协作Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2603.01035v1 | From Human Negotiation to Agent Negotiation: Personal Mobility Agents in Automated Traffic | 提出个人移动代理作为用户代理，编码偏好并与其他代理协商交通行为。 | 解决自动化交通中用户偏好与系统行为冲突及界面不可扩展问题。 | 自动化交通系统与个人出行代理 |
| 2 | http://arxiv.org/abs/2603.03212v1 | NeuroSkill(tm): Proactive Real-Time Agentic System Capable of Modeling Human State of Mind | 利用 BCI 信号与 EXG 模型建模人类心智状态，离线边缘运行。 | 解决系统无法直接从脑机接口记录信号 engage 人类认知情感层面问题。 | 脑机接口与人机交互 |
| 3 | http://arxiv.org/abs/2603.03630v1 | Behind the Prompt: The Agent-User Problem in Information Retrieval | 调查代理 - 用户问题，发现个体代理动作无法分类为自主或操作。 | 解决信息检索中用户模型假设人类意图在代理配置下失效问题。 | 信息检索与代理用户行为 |
| 4 | http://arxiv.org/abs/2603.03741v1 | HALyPO: Heterogeneous-Agent Lyapunov Policy Optimization for Human-Robot Collaboration | 异质代理 Lyapunov 策略优化， enforcing 参数空间 disagreement 度量下降。 | 解决人机协作中异质性导致理性差距及独立策略梯度更新发散。 | 人机协作机器人控制 |
| 5 | http://arxiv.org/abs/2603.03768v1 | Cognition to Control - Multi-Agent Learning for Human-Humanoid Collaborative Transport | 三层层级显式 deliberation-to-control 路径，含 VLM  grounding 与 MARL。 | 解决多代理 HRC 中长程协调决策与物理执行需在约束下共进化。 | 人形机器人与人协作运输 |
| 6 | http://arxiv.org/abs/2603.01912v1 | Demonstrating ViviDoc: Generating Interactive Documents through Human-Agent Collaboration | 多 Agent 管道与人类可读中间表示 DocSpec，分解交互可视化组件。 | 解决创建交互式文章成本高，需领域 expertise 及 web 开发技能的问题。 | 交互式教育文档生成 |
| 7 | http://arxiv.org/abs/2603.02050v2 | "When to Hand Off, When to Work Together": Expanding Human-Agent Co-Creative Collaboration through Concurrent Interaction | 解释协作意图并实时适应，识别设计师选择委托、指导或并发工作的模式。 | 解决 AI 代理通常仅提供最终输出或暴露只读执行过程，缺乏并发上下文感知的问题。 | 人机协同创意设计 |
| 8 | http://arxiv.org/abs/2603.02070v1 | Exploring Plan Space through Conversation: An Agentic Framework for LLM-Mediated Explanations in Planning | 多 Agent LLM 架构，独立于解释框架，实现用户及上下文依赖的交互式解释。 | 解决自动化计划生成中人类需引导 AI  planner 但缺乏自然交互解释的问题。 | 顺序决策问题规划 |
| 9 | http://arxiv.org/abs/2603.04746v1 | "Visioning Human-Agentic AI Teaming: Continuity, Tension, and Future Research" | 扩展团队情境意识理论，重构开放代理下人机意识，区分连续性与张力。 | 解决人机协作中行为轨迹、认识论基础及治理逻辑随时间稳定性问题。 | 人机团队协作研究 |
| 10 | http://arxiv.org/abs/2603.07444v1 | HLER: Human-in-the-Loop Economic Research via Multi-Agent Pipelines for Empirical Discovery | 提出人在回路经济研究架构，编排专用智能体并嵌入人类决策门控，保留关键人工监督。 | 解决实证研究需 grounded 数据集、识别策略设计及人类判断评估经济意义的约束。 | 经济学实证研究/社会科学 |
| 11 | http://arxiv.org/abs/2603.07843v1 | How Neurotypical and Autistic Children Interact Nonverbally with Anthropomorphic Agents in Open-Ended Tasks | 研究儿童与非语言具身代理开放互动，收集比较非语言行为，为包容性系统开发提供依据。 | 解决开发包容性社会交互系统需理解儿童如何与非语言具身人工智能代理互动的问题。 | 儿童机器人交互/特殊教育 |
| 12 | http://arxiv.org/abs/2603.07972v1 | Adaptive Collaboration with Humans: Metacognitive Policy Optimization for Multi-Agent LLMs with Continual Learning | 提出人在回路多智能体协作HILA，训练智能体学习元认知策略决定自主解决或 defer 人类专家。 | 解决纯自主MAS为封闭世界系统，受预训练模型静态知识 horizon 限制导致 novel 挑战下失败问题。 | 人机协作/问题解决 |
| 13 | http://arxiv.org/abs/2603.08190v1 | Human-AI Collaboration for Scaling Agile Regression Testing: An Agentic-AI Teammate from Manual to Automated Testing | 提出 agentic AI 方法直接从 validated 规格生成系统级测试脚本，集成检索增强多智能体架构。 | 解决敏捷组织中测试规格产生快于转换为可执行脚本导致 manual  effort  mounting 及 release  delayed 问题。 | 软件测试/敏捷开发 |
| 14 | http://arxiv.org/abs/2603.12600v1 | How GenAI Mentor Configurations Shape Early Collaborative Dynamics: A Classroom Comparison of Individual and Shared Agents | 对比共享AI与个体AI配置对协作调节的影响 | GenAI配置如何重塑课堂协作过程 | 计算机支持协作学习(CSCL) |
| 15 | http://arxiv.org/abs/2603.12608v1 | InterDeepResearch: Enabling Human-Agent Collaborative Information Seeking through Interactive Deep Research | 三层研究上下文管理框架，支持实时可操控性 | 现有系统用户被动、缺乏人机协作 | 深度研究信息检索系统 |
| 16 | http://arxiv.org/abs/2603.10492v2 | Human-AI Co-reasoning for Clinical Diagnosis with Evidence-Integrated Language Agent | 结合领域调优 LLM 与文献检索支持诊断决策 | 解决复杂真实病例中 AI 辅助人类诊断推理的效能评估 | 临床诊断人机协作 |
| 17 | http://arxiv.org/abs/2603.10664v1 | Terminal Is All You Need: Design Properties for Human-AI Agent Collaboration | 论证终端基于工具满足代表兼容性等三大设计属性 | 解决图形空间界面需刻意工程才能达到终端协作效率 | 人机 Agent 协作设计 |
| 18 | http://arxiv.org/abs/2603.10747v1 | Pneuma-Seeker: A Relational Reification Mechanism to Align AI Agents with Human Work over Relational Data | 关系具体化机制，将用户需求表示为关系 schema | 解决数据工人无法精确 articulate 信息需求导致 LLM 脆弱 | 关系数据上的人机协作 |
| 19 | http://arxiv.org/abs/2603.11011v1 | Task-Aware Delegation Cues for LLM Agents | 将离线偏好评估转化为在线委托信号，提供能力 profile 与协调风险线索 | 人机团队协作脆弱，用户缺乏任务特定可靠性线索，智能体缺乏不确定性表达 | LLM 智能体与人机协作 |
| 20 | http://arxiv.org/abs/2603.11677v1 | From Control to Foresight: Simulation as a New Paradigm for Human-Agent Collaboration | 提出 simulation-in-the-loop 交互范式，使用户与智能体在决策前探索模拟轨迹 | 人机交互呈点对点反应式，用户缺乏对后续后果的可见性与 foresight | 复杂多步任务中的人机协作 |
| 21 | http://arxiv.org/abs/2603.11834v1 | Hybrid Human-Agent Social Dilemmas in Energy Markets | 引入使用全局可观察信号的人工智能体增加协调，分析混合种群动力学 | 混合种群中委托战略决策时，理解合作行为何时及如何出现仍是挑战 | 能源市场中的混合人机社会困境 |
| 22 | http://arxiv.org/abs/2603.14225v2 | "I'm Not Reading All of That": Understanding Software Engineers' Level of Cognitive Engagement with Agentic Coding Assistants | 实证研究软件工程师与编码助手协作时的认知参与及意义构建过程 | 过度依赖 AI 系统削弱用户批判性思维，当前设计缺乏反思支持 | 软件工程/人机协作 |
| 23 | http://arxiv.org/abs/2603.14373v1 | Trust Over Fear: How Motivation Framing in System Prompts Affects AI Agent Debugging Depth | 研究发现信任框架提示比恐惧框架更能诱导智能体深度调试行为 | 系统提示动机框架如何影响智能体调试行为未知 | 智能体调试/提示工程 |
| 24 | http://arxiv.org/abs/2603.14449v1 | Tap-to-Adapt: Learning User-Aligned Response Timing for Speech Agents | 用户通过点击交互激活或中断智能体，构建在线学习标签对齐响应时机 | 语音智能体缺乏与用户意图持续对齐的响应时机判断研究 | 语音交互/人机协作 |
| 25 | http://arxiv.org/abs/2603.15341v1 | Intelligent Co-Design: An Interactive LLM Framework for Interior Spatial Design via Multi-Modal Agents | 多智能体框架动态转换自然语言与图像为3D设计，支持实时交互 | 客户缺乏设计知识导致沟通误解，规则系统限制参与 | 建筑室内空间协同设计 |
| 26 | http://arxiv.org/abs/2603.15911v1 | Human-AI Synergy in Agentic Code Review | 大规模实证分析代码review对话，比较人类与AI代理反馈差异与协作模式 | 缺乏实证证据比较协作工作流中AI代理与人类审查员有效性 | 代码审查中的人机协作 |
| 27 | http://arxiv.org/abs/2603.15914v1 | The Agentic Researcher: A Practical Guide to AI-Assisted Research in Mathematics and Machine Learning | 提供AI辅助研究实用指南与开源框架，将CLI代理转为自主研究助手 | 不清楚AI工具如何融入日常研究实践，缺乏负责任使用护栏 | 数学与机器学习研究辅助 |
| 28 | http://arxiv.org/abs/2603.18470v1 | CyberJustice Tutor: An Agentic AI Framework for Cybersecurity Learning via Think-Plan-Act Reasoning and Pedagogical Scaffolding | Think-Plan-Act认知周期， pedagogical scaffolding层基于ZPD动态适应 | 刑事司法专业人员网络安全教育受反应式聊天机器人无状态与幻觉风险阻碍 | 网络安全教育 |
| 29 | http://arxiv.org/abs/2603.15946v1 | Argumentative Human-AI Decision-Making: Toward AI Agents That Reason With Us, Not For Us | 结合计算论证与 LLM，构建可争辩、可修订的决策智能体 | 解决 LLM 推理不透明及传统论证依赖领域特征的问题 | 高风险决策领域 |
| 30 | http://arxiv.org/abs/2603.16663v2 | When Openclaw Agents Learn from Each Other: Insights from Emergent AI Agent Communities for Human-AI Partnership in Education | 观察 emergent 智能体社区，提出“教 AI 学”课程设计 | 解决对 AI 队友理解局限于双人交互的问题 | 教育伙伴 |

[返回目录](#目录)

<a id="cat-09"></a>

## Agent工具使用与环境交互

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2603.01050v1 | MM-DeepResearch: A Simple and Effective Multimodal Agentic Search Baseline | 提出超图 QA 生成与离线搜索引擎，支持多工具调用的多模态深度研究。 | 解决多模态研究代理缺乏数据、搜索轨迹及在线 API 训练成本高的问题。 | 多模态深度研究任务与智能体 |
| 2 | http://arxiv.org/abs/2603.02795v2 | VSearcher: Long-Horizon Multimodal Search Agent via Reinforcement Learning | 迭代注入数据合成 pipeline 生成大规模复杂多模态 QA，SFT-then-RL 训练。 | 解决多模态大模型限于静态知识，缺乏访问及利用最新 web 信息能力的问题。 | 多模态搜索 Agent |
| 3 | http://arxiv.org/abs/2603.04384v3 | AgentIR: Reasoning-Aware Retrieval for Deep Research Agents | 推理感知检索范式，联合嵌入智能体推理迹线与查询，合成训练数据。 | 解决现有检索器忽略深度研究智能体显式自然语言推理信号问题。 | 深度研究智能体/检索系统 |
| 4 | http://arxiv.org/abs/2603.12155v1 | GlyphBanana: Advancing Precise Text Rendering Through Agentic Workflows | 代理工作流整合辅助工具，注入字形模板 | 复杂文本和公式生成精度不足 | 文本渲染/Text-to-Image |
| 5 | http://arxiv.org/abs/2603.12310v1 | VQQA: An Agentic Approach for Video Evaluation and Quality Improvement | 多Agent框架生成视觉问题作为语义梯度 | 视频生成与用户意图对齐困难 | 视频生成模型优化 |
| 6 | http://arxiv.org/abs/2603.12597v1 | Feynman: Knowledge-Infused Diagramming Agent for Scalable Visual Designs | 知识组件枚举+代码规划+Penrose渲染 | 缺乏大规模高质量视觉-语言对齐数据 | 视觉设计/图表生成 |
| 7 | http://arxiv.org/abs/2603.13625v1 | Design and evaluation of an agentic workflow for crisis-related synthetic tweet datasets | 迭代生成-评估-反馈闭环生成合成推文 | Twitter数据访问政策变化导致数据获取困难 | 危机信息学/AI系统评估 |
| 8 | http://arxiv.org/abs/2603.11076v1 | DIVE: Scaling Diversity in Agentic Task Synthesis for Generalizable Tool Use | 逆向合成顺序，先执行工具再反推任务，保证 grounding | 解决合成任务多样性不足导致工具使用泛化性差问题 | 工具使用 LLM 后训练 |
| 9 | http://arxiv.org/abs/2603.13404v1 | Schema First Tool APIs for LLM Agents: A Controlled Study of Tool Misuse, Recovery, and Budgeted Performance | 研究基于 schema 的工具契约与结构化验证诊断是否改善严格预算下可靠性 | 工具使用界面设计 Rarely 作为实验变量，缺乏对接口形式化影响的隔离研究 | LLM 智能体工具 API 交互设计 |
| 10 | http://arxiv.org/abs/2603.14733v1 | A Skill-augmented Agentic Framework and Benchmark for Multi-Video Understanding | 集成视觉工具与技能增强框架，支持迭代结构化推理 | 多视频理解中信息丢失与缺乏跨视频协调问题 | 多视频问答与理解任务 |
| 11 | http://arxiv.org/abs/2603.16967v1 | MSRAMIE: Multimodal Structured Reasoning Agent for Multi-instruction Image Editing | 训练免费智能体框架，结构化多模态推理处理多指令编辑 | 解决多指令编辑数据稀缺及模型退化问题 | 多指令图像编辑 |
| 12 | http://arxiv.org/abs/2603.16411v1 | RECOVER: Robust Entity Correction via agentic Orchestration of hypothesis Variants for Evidence-based Recovery | 智能体校正框架，利用多假设证据修正 ASR 实体识别错误 | 解决罕见及领域特定术语 ASR 实体识别错误问题 | 语音识别实体修正 |
| 13 | http://arxiv.org/abs/2603.16839v1 | Learning to Present: Inverse Specification Rewards for Agentic Slide Generation | 逆规范奖励系统，评估生成幻灯片传达意图的忠实度 | 解决自动化演示生成需连贯内容及视觉设计的挑战 | 幻灯片生成 |
| 14 | http://arxiv.org/abs/2603.17055v1 | PaAgent: Portrait-Aware Image Restoration Agent via Subjective-Objective Reinforcement Learning | 肖像感知 IR 智能体，自进化肖像库选择修复工具 | 解决现有 IR 智能体缺乏交互洞察总结机制的问题 | 图像修复 |

[返回目录](#目录)

<a id="cat-10"></a>

## 具身智能Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2603.01104v1 | Egocentric Co-Pilot: Web-Native Smart-Glasses Agents for Assistive Egocentric AI | 神经符号框架运行于智能眼镜，结合时序思维链与 hierarchical 上下文压缩。 | 解决第一人称视频长程问答超出上下文窗口及多模态意图映射噪声问题。 | 智能眼镜与辅助性生活 AI 助手 |
| 2 | http://arxiv.org/abs/2603.01113v1 | From Dialogue to Execution: Mixture-of-Agents Assisted Interactive Planning for Behavior Tree-Based Long-Horizon Robot Execution | 混合代理辅助交互规划，生成行为树以实现结构化长程机器人执行与重试。 | 解决长程任务中用户负担重及扁平计划难以管理复杂性的问题。 | 长程机器人任务执行与规划 |
| 3 | http://arxiv.org/abs/2603.03024v1 | MA-CoNav: A Master-Slave Multi-Agent Framework with Hierarchical Collaboration and Dual-Level Reflection for Long-Horizon Embodied VLN | 主从分层架构解耦感知规划执行记忆，引入局部 - 全局双重反思。 | 解决长程视觉语言导航中单代理认知过载与决策漂移问题。 | 机器人视觉语言导航 (VLN) |
| 4 | http://arxiv.org/abs/2603.03148v1 | From Language to Action: Can LLM-Based Agents Be Used for Embodied Robot Cognition? | 提出认知架构，LLM 为核心规划推理，组件支持工作 episodic 记忆。 | 解决 LLM 控制具身机器人时高层语言到低层功能可靠桥接问题。 | 家庭服务机器人认知控制 |
| 5 | http://arxiv.org/abs/2603.04466v1 | Act-Observe-Rewrite: Multimodal Coding Agents as In-Context Policy Learners for Robot Manipulation | LLM 代理通过合成新 Python 控制器代码改进策略，无需梯度更新。 | 解决机器人操作策略学习需梯度更新或演示及失败推理问题。 | 机器人操作策略学习 |
| 6 | http://arxiv.org/abs/2603.03640v1 | MistyPilot: An Agentic Fast-Slow Thinking LLM Framework for Misty Social Robots | 整合物理交互与社会智能代理，采用快慢思考范式捕获偏好。 | 解决无编程经验用户定制社交机器人工具选择与执行可靠挑战。 | 社交机器人自主工具编排 |
| 7 | http://arxiv.org/abs/2603.02772v1 | Agentic Self-Evolutionary Replanning for Embodied Navigation | 引入 Agent 自进化动作模型，利用 in-context learning 与 auto-differentiation 自适应调整。 | 解决现有 replanning 方法冻结 ego 动作模型，错过通过升级 robot 本身探索更好计划的问题。 | 具身导航 |
| 8 | http://arxiv.org/abs/2603.05621v2 | RACAS: Controlling Diverse Robots With a Single Agentic System | 提出 RACAS 架构通过自然语言控制多样机器人 | 解决跨平台机器人控制需重新训练专家知识问题 | 多形态机器人自主控制 |
| 9 | http://arxiv.org/abs/2603.04029v1 | Self-adapting Robotic Agents through Online Continual Reinforcement Learning with World Model Feedback | 基于世界模型预测残差检测分布外事件，触发在线持续强化学习微调。 | 解决学习型机器人控制器部署后无法应对 unforeseen 变化问题。 | 四足机器人/实车控制 |
| 10 | http://arxiv.org/abs/2603.04659v1 | GIANT - Global Path Integration and Attentive Graph Networks for Multi-Agent Trajectory Planning | 整合全局路径规划与局部导航，利用注意图神经网络管理动态交互。 | 解决复杂动态环境中多机器人碰撞避免与高效导航问题。 | 物流/多机器人导航 |
| 11 | http://arxiv.org/abs/2603.05321v1 | Designing for Adolescent Voice in Health Decisions: Embodied Conversational Agents for HPV Vaccination | 设计移动干预赋予青少年声音，使用针对受众的具身对话智能体传达事实。 | 解决数字疫苗干预仅针对父母，忽视青少年作为利益相关者 agency 问题。 | 青少年健康决策/HPV 疫苗 |
| 12 | http://arxiv.org/abs/2603.07650v1 | Multi-Agent Off-World Exploration for Sparse Evidence Discovery via Gaussian Belief Mapping and Dual-Domain Coverage | 提出基于高斯信念映射及双域覆盖的多智能体信息路径规划框架，平衡信息增益与安全。 | 解决外星多机器人探索中目标稀疏、传感有限、地形危险及通信受限的挑战。 | 外星机器人探索/路径规划 |
| 13 | http://arxiv.org/abs/2603.07909v1 | Long-Short Term Agents for Pure-Vision Bronchoscopy Robotic Autonomy | 提出纯视觉自主框架，使用分层长短智能体进行长 horizon 支气管镜导航，无需外部跟踪。 | 解决机器人辅助腔内干预中因视野有限及动态伪影导致准确术中导航困难的问题。 | 医疗机器人/支气管镜导航 |
| 14 | http://arxiv.org/abs/2603.11975v2 | HomeSafe-Bench: Evaluating Vision-Language Models on Unsafe Action Detection for Embodied Agents in Household Scenarios | 提出HomeSafe-Bench基准和HD-Guard分层安全监控架构 | 家庭环境中具身Agent的不安全行为检测 | 家庭机器人/具身智能体 |
| 15 | http://arxiv.org/abs/2603.12238v1 | SceneAssistant: A Visual Feedback Agent for Open-Vocabulary 3D Scene Generation | 视觉反馈驱动Agent，提供原子操作集迭代优化 | 3D场景生成受限于预定义空间关系 | 3D内容创作/数字内容 |
| 16 | http://arxiv.org/abs/2603.11080v1 | SELF-VLA: A Skill Enhanced Agentic Vision-Language-Action Framework for Contact-Rich Disassembly | 集成显式拆卸技能的 agentic VLA 框架 | 解决现有机器人拆卸系统依赖人力且泛化能力有限问题 | 接触丰富的拆卸任务 |
| 17 | http://arxiv.org/abs/2603.10675v1 | Cybo-Waiter: A Physical Agentic Framework for Humanoid Whole-Body Locomotion-Manipulation | VLM 计划转为可验证任务程序，闭环多物体 3D 几何监督 | 解决人形机器人在部分可观测下长程执行 locomotion 耦合挑战 | 人形全身 locomotion 操作 |
| 18 | http://arxiv.org/abs/2603.11346v1 | Learning to Assist: Physics-Grounded Human-Human Control via Multi-Agent Reinforcement Learning | 将辅助运动序列模仿公式化为多智能体 RL 问题，联合训练支持者和接受者策略 | 现有行为限于无接触社交，辅助场景需持续感知人类伙伴并适应动态 | 人形机器人与人物理辅助交互 |
| 19 | http://arxiv.org/abs/2603.11392v1 | Agentic AI for Embodied-enhanced Beam Prediction in Low-Altitude Economy Networks | 多智能体协作推理架构，混合波束预测模型系统处理多模态 UAV 数据 | 高频无线信道传播损耗大，高移动性 UAV 场景下波束预测挑战大 | 低空经济网络 UAV 通信 |
| 20 | http://arxiv.org/abs/2603.11558v2 | RoboClaw: An Agentic Framework for Scalable Long-Horizon Robotic Tasks | 统一数据收集、策略学习与任务执行，引入 Entangled Action Pairs 形成自重置循环 | VLA 系统扩展至长 horizon 任务难，依赖手动环境重置与脆弱多策略执行 | 长 horizon 机器人操作任务 |
| 21 | http://arxiv.org/abs/2603.14182v1 | Towards Equitable Robotic Furnishing Agents for Aging-in-Place: ADL-Grounded Design Exploration | 提出家庭机器人家具代理概念，利用 CV 与 LLM 实现自然交互与安全执行 | 老龄化环境中日常活动困难累积，需关注公平与责任 | 居家养老/机器人 |
| 22 | http://arxiv.org/abs/2603.14236v1 | AeroGen: Agentic Drone Autonomy through Single-Shot Structured Prompting & Drone SDK | 结构化 guardrail 提示与 SDK 集成，使通用 LLM 生成约束感知无人机代码 | 设计正确 UAV 自主程序难，LLM 生成代码可靠性不确定 | 无人机/自主控制 |
| 23 | http://arxiv.org/abs/2603.14393v1 | From Scanning Guidelines to Action: A Robotic Ultrasound Agent with LLM-Based Reasoning | LLM 智能体解释扫描指南并动态调用工具，适应变量与工作流 | 机器人超声扫描依赖固定程序，难适应新任务与情境判断 | 医疗机器人/超声扫描 |
| 24 | http://arxiv.org/abs/2603.15386v1 | RieMind: Geometry-Grounded Spatial Agent for Scene Understanding | 代理框架将LLM grounded 在显式3D场景图，通过几何工具交互 | 视觉语言模型在度量与空间推理上表现挣扎 | 静态3D室内场景理解 |
| 25 | http://arxiv.org/abs/2603.17670v1 | AgentVLN: Towards Agentic Vision-and-Language Navigation | VLM-as-Brain范式解耦高层语义推理与感知规划，跨空间表示映射 | VLN系统空间感知有限、2D-3D表示不匹配与单目尺度模糊 | 边缘计算平台具身导航 |
| 26 | http://arxiv.org/abs/2603.18210v1 | GoalVLM: VLM-driven Object Goal Navigation for Multi-Agent System | 协作多Agent框架零样本开放词汇对象导航，VLM直接集成决策循环 | 对象目标导航限于地面机器人封闭集对象词汇，无法泛化新目标 | 多Agent系统导航 |
| 27 | http://arxiv.org/abs/2603.18400v1 | Graph-of-Constraints Model Predictive Control for Reactive Multi-agent Task and Motion Planning | 约束图模型预测控制集成MPC，支持部分有序任务与动态Agent协调 | 现有序列约束处理方法难以应对部分有序任务与动态Agent分配 | 多Agent操作任务 |
| 28 | http://arxiv.org/abs/2603.18520v1 | Robotic Agentic Platform for Intelligent Electric Vehicle Disassembly | 机器人Agent平台集成gantry机械臂、RGB-D感知与自动螺母运行工具 | 电动汽车电池包拆卸因高设计变异性仍主要手动，需可扩展回收 | 电动汽车电池回收 |
| 29 | http://arxiv.org/abs/2603.19166v1 | Meanings and Measurements: Multi-Agent Probabilistic Grounding for Vision-Language Navigation | 多Agent概率接地框架分解语言查询为结构化子组件，概率组合接地输出 | SOTA VLM接地方法难以处理复杂度量语义语言查询 | 机器人人机协作导航 |

[返回目录](#目录)

<a id="cat-11"></a>

## Agent记忆与知识管理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2603.01160v1 | Semantic XPath: Structured Agentic Memory Access for Conversational AI | 树状结构化记忆模块，支持高效访问与更新，优于扁平 RAG 与上下文记忆。 | 解决上下文窗口限制及扁平记忆忽略结构导致检索效率低的问题。 | 长程任务导向对话 AI 系统 |
| 2 | http://arxiv.org/abs/2603.01455v1 | From Verbatim to Gist: Distilling Pyramidal Multimodal Memory via Semantic Information Bottleneck for Long-Horizon Video Agents | 金字塔多模态记忆架构，分层 distill 感知痕迹为语义 schema，优化压缩与保留。 | 解决长程视频理解中上下文窗口限制及静态记忆机制无法 mirror 人类认知效率。 | 长程视频理解与多模态智能体 |
| 3 | http://arxiv.org/abs/2603.15642v1 | CraniMem: Cranial Inspired Gated and Bounded Memory for Agentic Systems | 神经认知启发的门控有界多阶段记忆设计，含巩固循环。 | 解决长程工作流中记忆不稳定、整合有限及易受干扰问题。 | 长程智能体任务工作流 |
| 4 | http://arxiv.org/abs/2603.01761v1 | Modular Memory is the Key to Continual Learning Agents | 结合 In-Weight Learning 与 In-Context Learning，设计模块化记忆架构。 | 解决基础模型在连续操作、经验积累及个性化方面存在根本性限制的问题。 | 持续学习 Agent |
| 5 | http://arxiv.org/abs/2603.02473v1 | Diagnosing Retrieval vs. Utilization Bottlenecks in LLM Agent Memory | 诊断框架分析 write 策略、retrieval 方法及 memory 利用行为对性能差异的影响。 | 解决记忆中 write 与 retrieval 相对重要性不明确，当前 pipeline 可能丢弃有用上下文的问题。 | LLM Agent 记忆系统 |
| 6 | http://arxiv.org/abs/2603.02626v1 | See and Remember: A Multimodal Agent for Web Traversal | 集成视觉 grounding 解析模糊交互元素，引入显式记忆栈及状态跟踪。 | 解决当前 LLM 基于 Agent 在复杂视觉环境中空间定向困难及导航循环的问题。 | 自主 Web 导航 |
| 7 | http://arxiv.org/abs/2603.05831v1 | Knowledge-driven Reasoning for Mobile Agentic AI: Concepts, Approaches, and Directions | 提出知识驱动推理框架提取复用决策结构 | 解决移动 Agent 资源受限与连接间歇性问题 | 边缘机器人与无人机任务 |
| 8 | http://arxiv.org/abs/2603.05873v1 | Shifting Adaptation from Weight Space to Memory Space: A Memory-Augmented Agent for Medical Image Segmentation | 提出 MemSeg-Agent 将适应从权重空间移至记忆空间 | 解决医学图像分割模型泛化差与通信开销大 | 跨机构医学图像分割 |
| 9 | http://arxiv.org/abs/2603.07024v1 | Enhancing Web Agents with a Hierarchical Memory Tree | 构建三层层次记忆树解耦逻辑规划与动作执行 | 解决扁平记忆结构导致跨网站泛化差 | 基于 LLM 的 Web 交互自动化 |
| 10 | http://arxiv.org/abs/2603.04257v1 | Memex(RL): Scaling Long-Horizon LLM Agents via Indexed Experience Memory | 索引经验记忆机制压缩上下文而不丢弃证据，RL 优化读写行为。 | 解决长程任务中有限上下文窗口导致 distant evidence 难以利用问题。 | 长程任务 LLM 智能体 |
| 11 | http://arxiv.org/abs/2603.04549v1 | Adaptive Memory Admission Control for LLM Agents | 自适应记忆准入控制框架，分解记忆价值为五个可解释因子进行结构化决策。 | 解决 LLM 智能体长期记忆积累中幻觉、过时事实及控制薄弱问题。 | 多会话推理 LLM 智能体 |
| 12 | http://arxiv.org/abs/2603.04814v1 | Beyond the Context Window: A Cost-Performance Analysis of Fact-Based Memory vs. Long-Context LLMs for Persistent Agents | 比较基于事实记忆系统与长上下文 LLM 推理，构建成本模型分析准确性与成本权衡。 | 解决持久对话 AI 系统在全文历史传递与结构化事实记忆间的架构选择问题。 | 持久对话 AI 系统 |
| 13 | http://arxiv.org/abs/2603.04815v1 | EchoGuard: An Agentic Framework with Knowledge-Graph Memory for Detecting Manipulative Communication in Longitudinal Dialogue | 利用知识图谱作为核心 episodic 和 semantic 记忆，结构化 Log-Analyze-Reflect 循环检测操纵。 | 解决现有系统缺乏结构化长期记忆追踪细微上下文依赖操纵战术问题。 | 纵向对话/操纵性通信检测 |
| 14 | http://arxiv.org/abs/2603.15658v1 | Did You Check the Right Pocket? Cost-Sensitive Store Routing for Memory-Augmented Agents | 将记忆检索形式化为存储路由问题，评估选择性检索对效率及性能的影响。 | 解决大多数系统对所有查询检索所有存储导致成本增加及引入无关上下文的问题。 | 记忆增强智能体/检索优化 |
| 15 | http://arxiv.org/abs/2603.12631v1 | Collaborative Multi-Agent Optimization for Personalized Memory System | 协同强化学习框架，联合优化局部Agent | 独立优化局部Agent无法保证全局性能 | 个性化LLM记忆系统 |
| 16 | http://arxiv.org/abs/2603.13017v1 | Structured Distillation for Personalized Agent Memory: 11x Token Reduction with Retrieval Preservation | 结构化蒸馏压缩对话历史，11倍压缩率 | 长对话历史携带成本高 | 个性化Agent记忆 |
| 17 | http://arxiv.org/abs/2603.09716v1 | AutoAgent: Evolving Cognition and Elastic Memory Orchestration for Adaptive Agents | 弹性记忆编排器动态组织交互历史，保留关键证据 | 解决静态认知和 rigid 工作流限制开放环境适应性 | 动态环境自适应智能体 |
| 18 | http://arxiv.org/abs/2603.10291v1 | Hybrid Self-evolving Structured Memory for GUI Agents | 图基记忆耦合离散符号节点与连续轨迹嵌入 | 解决现有外部记忆依赖 flat 检索缺乏结构化自进化 | GUI 智能体 |
| 19 | http://arxiv.org/abs/2603.10600v1 | Trajectory-Informed Memory Generation for Self-Improving Agent Systems | 从执行轨迹提取可操作学习，通过上下文记忆检索改进 | 解决 LLM 代理重复低效模式未能从执行经验学习问题 | 自改进智能体系统 |
| 20 | http://arxiv.org/abs/2603.10700v1 | Structured Linked Data as a Memory Layer for Agent-Orchestrated Retrieval | 结构化链接数据作为记忆层，增强实体页格式 | 解决 RAG 系统视文档为 flat 文本忽略结构化 metadata | 代理编排检索 |
| 21 | http://arxiv.org/abs/2603.15666v1 | Compiled Memory: Not More Information, but More Precise Instructions for Language Agents | Atlas 记忆内核将积累的任务经验编译进指令结构，通过重写系统提示交付 | 现有记忆系统关注检索管理，忽视经验效用及如何改变智能体行为 | 语言智能体记忆与指令优化 |
| 22 | http://arxiv.org/abs/2603.11650v1 | QChunker: Learning Question-Aware Text Chunking for Domain RAG via Multi-Agent Debate | 多智能体辩论框架建模文本分块为分割与知识完成复合任务，提出 ChunkScore | RAG 上限受限于文本块语义完整性与信息粒度，现有评估方法效率低 | 领域 RAG 文本分块与检索增强 |
| 23 | http://arxiv.org/abs/2603.11768v1 | Governing Evolving Memory in LLM Agents: Risks, Mechanisms, and the Stability and Safety Governed Memory (SSGM) Framework | SSGM 框架解耦记忆演化与执行，强制执行一致性验证与动态访问控制 | 动态环境中记忆治理、语义漂移与隐私漏洞风险被忽视，缺乏统一治理 | LLM 智能体长期记忆治理与安全 |
| 24 | http://arxiv.org/abs/2603.14057v1 | Demand-Driven Context: A Methodology for Building Enterprise Knowledge Bases Through Agent Failure | 以智能体失败为信号 curated 领域知识，反转知识工程流程 | 企业特定任务缺乏领域知识，传统知识工程效率低 | 企业知识库构建 |
| 25 | http://arxiv.org/abs/2603.14212v1 | Memory as Asset: From Agent-centric to Human-centric Memory Management | 提出记忆即资产范式，强调以人为本的所有权与集体记忆进化 | 现有 LLM 缺乏以人为本的个人记忆管理以扩展知识边界 | 通用人工智能/记忆管理 |
| 26 | http://arxiv.org/abs/2603.14588v1 | SuperLocalMemory V3: Information-Geometric Foundations for Zero-LLM Enterprise Agent Memory | 建立信息几何基础，提出检索度量与记忆生命周期公式化，检测矛盾 | 持久记忆缺乏数学基础，检索与一致性管理未探索 | 企业智能体/记忆系统 |
| 27 | http://arxiv.org/abs/2603.14597v1 | D-MEM: Dopamine-Gated Agentic Memory via Reward Prediction Error Routing | 生物启发架构通过奖励预测误差路由解耦短期交互与认知重构 | 自主 LLM 智能体缺乏结构化长时记忆，写延迟高且 token 成本高 | 智能体记忆/ lifelong learning |
| 28 | http://arxiv.org/abs/2603.14635v1 | Compute Allocation for Reasoning-Intensive Retrieval Agents | 研究推理密集型检索管道中的计算分配，发现重排序受益于更强模型 | 智能体长程操作记忆增长，检索关键但推理密集型检索成本高 | 智能体检索/计算优化 |
| 29 | http://arxiv.org/abs/2603.14805v1 | Knowledge Activation: AI Skills as the Institutional Knowledge Primitive for Agentic Software Development | 将机构知识转化为原子知识单元(AKUs)供代理消费 | 企业机构知识 trapped 在人类可读格式中无法被代理有效利用 | 企业软件开发与知识管理 |
| 30 | http://arxiv.org/abs/2603.15080v3 | Open Biomedical Knowledge Graphs at Scale: Construction, Federation, and AI Agent Access with Samyama Graph Database | 构建大规模生物医学知识图谱并生成 schema-driven MCP 服务器 | 生物医学知识碎片化，代理访问缺乏高效结构化接口 | 生物医学领域代理知识访问 |
| 31 | http://arxiv.org/abs/2603.15280v1 | Advancing Multimodal Agent Reasoning with Long-Term Neuro-Symbolic Memory | 提出NS-Mem框架，整合神经记忆与显式符号结构规则 | 现有记忆依赖神经表示，限制分析演绎推理能力 | 多模态代理长期推理 |
| 32 | http://arxiv.org/abs/2603.15421v1 | CLAG: Adaptive Memory Organization via Agent-Driven Clustering for Small Language Model Agents | SLM代理主动通过聚类组织记忆，生成集群特定 profile | 全局检索池稀释知识，小模型易受无关上下文影响 | 小语言模型代理记忆管理 |
| 33 | http://arxiv.org/abs/2603.15566v1 | Lore: Repurposing Git Commit Messages as a Structured Knowledge Protocol for AI Coding Agents | 轻量级协议重构commit消息为自包含决策记录，携带约束与元数据 | 代码提交捕获diff但丢弃决策背后的推理与上下文 | AI编码代理机构知识保留 |
| 34 | http://arxiv.org/abs/2603.17613v1 | VeriAgent: A Tool-Integrated Multi-Agent System with Evolving Memory for PPA-Aware RTL Code Generation | 三Agent闭环工作流，演化记忆机制将优化经验外部化为结构化记忆节点 | RTL代码生成忽略功耗、性能、面积等物理设计目标问题 | 硬件设计流程 |
| 35 | http://arxiv.org/abs/2603.17787v1 | Governed Memory: A Production Architecture for Multi-Agent Workflows | 双记忆模型结合开放集原子事实与模式强制类型属性，分层治理路由 | 企业AI多Agent工作流无共享记忆与共同治理的五大结构挑战 | 企业AI生产部署 |
| 36 | http://arxiv.org/abs/2603.18272v1 | Retrieval-Augmented LLM Agents: Learning to Learn from Experience | 结合微调与经验检索，系统研究如何训练检索增强LLM Agent有效利用检索轨迹 | 微调无法外推新任务，经验检索性能低于监督基线问题 | 未见任务泛化 |
| 37 | http://arxiv.org/abs/2603.18409v1 | TopoChunker: Topology-Aware Agentic Document Chunking Framework | 双Agent架构映射异构文档到结构化中间表示，显式保留跨段依赖 | 当前文档分块方法线性化文本剥离内在拓扑层次导致语义碎片化 | 检索增强生成RAG |
| 38 | http://arxiv.org/abs/2603.18429v1 | AndroTMem: From Interaction Trajectories to Anchored Memory in Long-Horizon GUI Agents | 锚定状态记忆将交互序列表示为因果链接中间状态锚点紧凑集 | 长程GUI Agent有效交互记忆未充分探索，重放冗余摘要擦除关键信息 | Android GUI Agent |
| 39 | http://arxiv.org/abs/2603.18631v1 | D-Mem: A Dual-Process Memory System for LLM Agents | 双过程记忆系统保留轻量向量检索，建立全面完整审议模块作为高保真回退 | 普遍检索记忆框架依赖增量处理范式丢失上下文关键信息 | 长程推理LLM Agent |
| 40 | http://arxiv.org/abs/2603.18718v1 | MemMA: Coordinating the Memory Cycle through Multi-Agent Reasoning and In-Situ Self-Evolution | 多Agent框架协调记忆周期前后向路径，原位自进化记忆构建 | 记忆增强LLM Agent将构建检索利用视为孤立子程序导致战略盲目 | 长程交互Agent |
| 41 | http://arxiv.org/abs/2603.16496v1 | AdaMem: Adaptive User-Centric Memory for Long-Horizon Dialogue Agents | 自适应用户中心记忆框架，整合工作及图记忆 | 解决现有记忆系统依赖语义相似性及粒度静态问题 | 长程对话记忆 |
| 42 | http://arxiv.org/abs/2603.16862v1 | Chronos: Temporal-Aware Conversational Agents with Structured Event Retrieval for Long-Term Memory | 时间感知记忆框架，分解对话为事件元组并索引 | 解决现有记忆系统难以推理时间 grounded 事实的问题 | 时间感知对话 |
| 43 | http://arxiv.org/abs/2603.17244v1 | Graph-Native Cognitive Memory for AI Agents: Formal Belief Revision Semantics for Versioned Memory Architectures | 图原生认知记忆架构，基于正式信念修正语义 | 解决 AI 智能体记忆组件架构合成及形式基础未探索问题 | 图原生认知记忆 |

[返回目录](#目录)

<a id="cat-12"></a>

## Agent学习与自进化

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2603.01209v2 | Agents Learn Their Runtime: Interpreter Persistence as Training-Time Semantics | 隔离解释器持久性作为训练变量，发现其塑造代理解决方式而非结果。 | 解决训练轨迹与部署运行时解释器状态管理不匹配导致的效率问题。 | 工具增强 LLM 代理训练与部署 |
| 2 | http://arxiv.org/abs/2603.01241v1 | TARSE: Test-Time Adaptation via Retrieval of Skills and Experience for Reasoning Agents | 测试时检索技能与经验库，轻量适配以对齐临床有效逻辑。 | 解决临床决策中无法可靠选择及应用正确程序知识与 prior 示例的问题。 | 医疗问答与临床推理代理 |
| 3 | http://arxiv.org/abs/2603.01283v1 | Beyond Reward: A Bounded Measure of Agent Environment Coupling | 提出 bipredictability 作为交互有效性度量，早于性能下降检测耦合失败。 | 解决现有监控依赖奖励指标，错过早期耦合失败及分布 shift 下部署挑战。 | 现实世界强化学习代理部署与监控 |
| 4 | http://arxiv.org/abs/2603.01481v1 | Harmonizing Dense and Sparse Signals in Multi-turn RL: Dual-Horizon Credit Assignment for Industrial Sales Agents | 双 horizon 信用分配框架，分离优化时间尺度，平衡长期目标与即时约束。 | 解决单一奖励合并异构目标导致高幅奖励淹没细微信号及训练不稳定问题。 | 工业销售代理与多轮对话优化 |
| 5 | http://arxiv.org/abs/2603.03078v1 | RAPO: Expanding Exploration for LLM Agents via Retrieval-Augmented Policy Optimization | 检索增强策略优化，混合策略 rollout 与检索感知策略优化机制。 | 解决 Agentic RL 纯 on-policy 探索受限及忽略细粒度动态问题。 | LLM 智能体强化学习训练 |
| 6 | http://arxiv.org/abs/2603.03202v2 | Code2Math: Can Your Code Agent Effectively Evolve Math Problems Through Exploration? | 多智能体框架自主演化数学问题，验证可解性与难度增加。 | 解决 IMO 级别高质量数学问题稀缺及训练评估瓶颈问题。 | 数学问题生成与演化 |
| 7 | http://arxiv.org/abs/2603.03680v1 | MAGE: Meta-Reinforcement Learning for Language Agents toward Strategic Exploration and Exploitation | 元 RL 框架 empowering LLM 代理战略探索与利用，整合历史反思。 | 解决 LLM 代理适应非平稳环境失败及内部化长期改进能力缺失。 | 语言代理元强化学习 |
| 8 | http://arxiv.org/abs/2603.01620v4 | ToolRLA: Multiplicative Reward Decomposition for Tool-Integrated Agents | 提出乘法奖励分解，涵盖格式、工具、参数、合规四维，编码领域优先级。 | 解决工具智能体奖励粗糙，无法区分工具选择与参数错误的问题。 | 金融顾问 Copilot |
| 9 | http://arxiv.org/abs/2603.01712v1 | FT-Dojo: Towards Autonomous LLM Fine-Tuning with Language Agents | 自主系统镜像人类专家，利用评估驱动反馈迭代诊断失败并微调策略。 | 解决垂直领域 LLM 微调过程劳动密集且昂贵，缺乏端到端自动化的问题。 | 自主 LLM 微调 |
| 10 | http://arxiv.org/abs/2603.01714v1 | TopoCurate:Modeling Interaction Topology for Tool-Use Agent Training | 投影多试验 rollout 到统一语义商拓扑，双选择机制优先反射性恢复轨迹。 | 解决 outcome-based filtering 忽略交互动态及 pass rate 无法区分任务结构信息的问题。 | 工具使用 Agent 训练 |
| 11 | http://arxiv.org/abs/2603.01940v1 | CoVe: Training Interactive Tool-Use Agents via Constraint-Guided Verification | 定义显式任务约束，引导复杂轨迹生成并作为确定性验证器评估质量。 | 解决多轮交互工具使用 Agent 训练数据复杂性及正确性难以兼顾的问题。 | 交互式工具使用 Agent |
| 12 | http://arxiv.org/abs/2603.02045v1 | Expanding LLM Agent Boundaries with Strategy-Guided Exploration | 生成自然语言策略描述做什么，基于策略生成环境动作，混合温度采样。 | 解决 LLM 代理在语言 - 动作空间探索复杂观察及稀疏结果奖励的挑战。 | 通用 LLM 代理 RL 训练 |
| 13 | http://arxiv.org/abs/2603.02510v1 | ParEVO: Synthesizing Code for Irregular Data: High-Performance Parallelism through Agentic Evolution | 进化编码 Agent 迭代修复代码，利用编译器、动态 race 检测器及性能 profiler 反馈。 | 解决 LLM 在不规则数据并行代码合成中生成 race conditions 及死锁代码的问题。 | 高性能并行算法合成 |
| 14 | http://arxiv.org/abs/2603.02766v1 | EvoSkill: Automated Skill Discovery for Multi-Agent Systems | 自进化框架分析执行失败，提出新技能或编辑现有技能，Pareto 前沿 govern 选择。 | 解决大多数技能手工 crafting 及现有进化方法优化低 level artifacts 耦合特定模型的问题。 | 多 Agent 系统技能发现 |
| 15 | http://arxiv.org/abs/2603.06713v1 | Scaling Agentic Capabilities, Not Context: Efficient Reinforcement Finetuning for Large Toolspaces | 提出 ATLAS 框架结合上下文控制与程序化工具编排 | 解决小模型在大工具空间中长程任务脆弱性问题 | 大工具空间下的小语言模型智能体 |
| 16 | http://arxiv.org/abs/2603.05860v1 | Evolving Medical Imaging Agents via Experience-driven Self-skill Discovery | 提出 MACRO 代理自主发现并合成复合工具 | 解决静态工具链在领域 shifts 下退化问题 | 医学影像解读与诊断 |
| 17 | http://arxiv.org/abs/2603.08754v1 | Hindsight Credit Assignment for Long-Horizon LLM Agents | 集成事后信用分配 refine 步级 Q 值 | 解决长程任务中稀疏奖励导致信用分配挑战 | 长程多步任务 LLM 智能体 |
| 18 | http://arxiv.org/abs/2603.05553v1 | "EigenData: A Self-Evolving Multi-Agent Platform for Function-Calling Data Synthesis, Auditing, and Repair" | 自进化平台自动化数据生命周期，协调子系统进行数据库构建、环境生成与轨迹合成。 | 解决函数调用智能体缺乏高质量领域特定训练数据问题。 | 函数调用智能体数据合成 |
| 19 | http://arxiv.org/abs/2603.04873v2 | SEA-TS: Self-Evolving Agent for Autonomous Code Generation of Time Series Forecasting Algorithms | 自进化循环自主生成验证优化代码，引入 Metric-Advantage MCTS 与全局可 steering 推理。 | 解决传统 ML 开发中新部署数据稀缺、分布偏移适应性差及手动迭代回报递减问题。 | 时间序列预测算法生成 |
| 20 | http://arxiv.org/abs/2603.04900v1 | EvoTool: Self-Evolving Tool-Use Policy Optimization in LLM Agents via Blame-Aware Mutation and Diversity-Aware Selection | 分解工具使用策略为四模块，通过轨迹归因、反馈引导突变及多样性选择迭代优化。 | 解决长程轨迹中工具使用策略优化监督延迟及信用分配困难问题。 | LLM 智能体工具使用策略 |
| 21 | http://arxiv.org/abs/2603.05044v1 | WebFactory: Automated Compression of Foundational Language Intelligence into Grounded Web Agents | 自动化闭环 RL 管道，系统压缩 LLM 潜在知识为接地动作， scalable 环境合成。 | 解决 GUI 智能体训练依赖不安全实时交互或昂贵人工数据及环境问题。 | GUI/Web 智能体训练 |
| 22 | http://arxiv.org/abs/2603.05120v1 | Bidirectional Curriculum Generation: A Multi-Agent Framework for Data-Efficient Mathematical Reasoning | 双向课程生成框架，动态生成数据挑战模型或简化问题修复推理失败。 | 解决单向课程学习盲目升级复杂度导致基础差距 persist 及样本利用低效问题。 | 数学推理 LLM 训练 |
| 23 | http://arxiv.org/abs/2603.07300v2 | AutoResearch-RL: Perpetual Self-Evaluating Reinforcement Learning Agents for Autonomous Neural Architecture Discovery | 提出永动自评估RL智能体，分离冻结环境、可变目标文件与元学习器，实现无监督架构发现。 | 解决神经架构搜索中需要人工监督及实验比较不公平的问题。 | 神经网络架构搜索 |
| 24 | http://arxiv.org/abs/2603.07433v1 | Data Agent: Learning to Select Data via End-to-End Dynamic Optimization | 提出端到端动态数据选择框架，智能体学习样本选择策略与模型优化共同进化。 | 解决现有方法依赖特定任务手工指标或静态标准，难以捕捉训练过程中数据效用演变的问题。 | 模型训练加速/数据选择 |
| 25 | http://arxiv.org/abs/2603.07784v1 | ProgAgent:A Continual RL Agent with Progress-Aware Rewards | 提出持续RL智能体ProgAgent，统一进度感知奖励学习与高通量JAX原生系统架构。 | 解决终身机器人学习中灾难性遗忘及奖励指定高成本，以及在线探索中稳定性问题。 | 机器人持续学习/技能获取 |
| 26 | http://arxiv.org/abs/2603.07927v1 | SWE-Fuse: Empowering Software Agents via Issue-free Trajectory Learning and Entropy-aware RLVR Training | 提出 issue 描述感知训练框架SWE-Fuse，融合 issue 引导与无 issue 样本，自适应调整训练动态。 | 解决真实数据集 issue 描述与解决方案不对齐引入噪声误导自动智能体限制 effectiveness 问题。 | 软件工程/自动修复 |
| 27 | http://arxiv.org/abs/2603.07978v1 | OSExpert: Computer-Use Agents Learning Professional Skills via Exploration | 引入GUI深度优先搜索探索算法 comprehensively 探索验证环境单元功能，自构建复合任务课程。 | 解决通用计算机使用智能体完成复杂任务效率低、迁移差及 struggle 细粒度动作序列问题。 | 计算机使用自动化/技能学习 |
| 28 | http://arxiv.org/abs/2603.08127v1 | EvoScientist: Towards Multi-Agent Evolving AI Scientists for End-to-End Scientific Discovery | 提出进化多智能体AI科学家框架EvoScientist，通过 persistent 记忆及自进化 continuously 改进研究策略。 | 解决现有AI科学家系统依赖静态手工设计管道， fail 适应 accumulated 交互历史导致重复失败问题。 | 科学发现/自动化研究 |
| 29 | http://arxiv.org/abs/2603.12011v1 | Can RL Improve Generalization of LLM Agents? An Empirical Study | 系统研究RL微调在跨环境泛化中的表现 | LLM Agent在未见环境中的泛化能力弱 | 多环境部署的LLM Agent |
| 30 | http://arxiv.org/abs/2603.12056v2 | XSkill: Continual Learning from Experience and Skills in Multimodal Agents | 经验与技能双流持续学习框架，视觉 grounding | 多模态Agent工具使用效率低、编排不灵活 | 开放环境多模态Agent |
| 31 | http://arxiv.org/abs/2603.10165v1 | OpenClaw-RL: Train Any Agent Simply by Talking | 利用通用 next-state 信号，从所有交互中在线学习策略 | 解决现有 agentic RL 系统未恢复 next-state 作为学习源 | 通用智能体训练 |
| 32 | http://arxiv.org/abs/2603.10505v1 | Safe and Scalable Web Agent Learning via Recreated Websites | 语言模型作为环境创建者，克隆网站为可验证合成环境 | 解决真实网站不安全难重置且缺乏可验证反馈限制训练 | Web 智能体学习 |
| 33 | http://arxiv.org/abs/2603.10564v1 | Adaptive RAN Slicing Control via Reward-Free Self-Finetuning Agents | 双视角反思机制生成反馈构建偏好数据集自微调 | 解决生成模型应用于连续控制任务缺乏显式奖励信号 | 无线接入网切片控制 |
| 34 | http://arxiv.org/abs/2603.10808v1 | Nurture-First Agent Development: Building Domain-Expert AI Agents Through Conversational Knowledge Crystallization | 知识结晶循环，将碎片化操作对话 consolidate 为资产 | 解决领域专家 AI 代理构建中隐性知识难以有效编码问题 | 领域专家 AI 代理开发 |
| 35 | http://arxiv.org/abs/2603.11327v2 | Meta-Reinforcement Learning with Self-Reflection for Agentic Search | 提出 MR-Search，跨 episode 探索生成显式自我反思作为上下文引导后续尝试 | 单 episode 优化奖励稀疏，难以在测试时改进上下文探索策略 | 智能体搜索策略优化 |
| 36 | http://arxiv.org/abs/2603.11808v2 | Automating Skill Acquisition through Large-Scale Mining of Open-Source Agentic Repositories: A Framework for Multi-Agent Procedural Knowledge Extraction | 系统化框架通过挖掘开源仓库自动获取高质量智能体技能，翻译至 SKILL.md | 通用模型缺乏专用程序性专业知识，限制其在自主工作流中的效用 | 智能体程序性知识获取与技能扩展 |
| 37 | http://arxiv.org/abs/2603.14486v1 | Infinite Problem Generator: Verifiably Scaling Physics Reasoning Data with Agentic Workflows | 智能体框架通过 Formula-as-Code 范式合成物理问题，保证可解性与一致性 | 复杂推理训练缺乏可验证高质量数据，静态基准缺乏推理痕迹 | 物理推理/数据生成 |
| 38 | http://arxiv.org/abs/2603.15255v2 | SAGE: Multi-Agent Self-Evolution for LLM Reasoning | 闭环框架中四代理协作进化，仅用少量种子集实现自训练 | 依赖大量人工标注数据，自玩缺乏显式规划与质量控制 | LLM推理能力自进化 |
| 39 | http://arxiv.org/abs/2603.15707v1 | SEMAG: Self-Evolutionary Multi-Agent Code Generation | 模仿人类编码实践，工作流自适应任务难度并自动升级骨干模型 | 依赖手动模型选择与固定工作流，无法适应任务复杂度变化 | 复杂编程任务代码生成 |
| 40 | http://arxiv.org/abs/2603.18074v1 | Lightweight Adaptation for LLM-based Technical Service Agent: Latent Logic Augmentation and Robust Noise Reduction | 潜在逻辑增强、鲁棒噪声降低、混合奖励机制三组件轻量适配框架 | 技术服务领域LLM Agent缺乏显式认知链与响应歧义问题 | 云技术服务Agent |
| 41 | http://arxiv.org/abs/2603.17399v1 | Bootstrapping Coding Agents: The Specification Is the Program | 编码Agent自举实现，从规范重新生成实现，体现元循环特性 | 编码Agent实现不稳定，规范与实现关系不明确问题 | 编码Agent开发 |
| 42 | http://arxiv.org/abs/2603.18079v1 | SLEA-RL: Step-Level Experience Augmented Reinforcement Learning for Multi-Turn Agentic Training | 每决策步基于当前观察检索经验，自进化经验库与步级信用分配 | 多轮设置中静态检索随episode进展不匹配问题 | 多轮工具使用任务 |
| 43 | http://arxiv.org/abs/2603.17683v1 | Sensi: Learn One Thing at a Time -- Curriculum-Based Test-Time Learning for LLM Game Agents | 双玩家架构分离感知与行动，课程学习系统，数据库作为控制平面 | 未知环境中LLM Agent测试时学习任务结构需数千交互问题 | ARC-AGI-3游戏挑战 |
| 44 | http://arxiv.org/abs/2603.17829v1 | CodeScout: An Effective Recipe for Reinforcement Learning of Code Search Agents | 有效强化学习配方，仅配备标准Unix终端的编码Agent实现强结果 | 仓库级代码定位依赖复杂专用工具，RL优化方法不足 | 大型代码仓库代码搜索 |
| 45 | http://arxiv.org/abs/2603.17973v2 | TDAD: Test-Driven Agentic Development - Reducing Code Regressions in AI Coding Agents via Graph-Based Impact Analysis | 构建源代码与测试依赖地图，提交补丁前Agent知道验证哪些测试 | AI编码Agent解决真实软件问题但频繁引入回归破坏测试 | 开源软件问题修复 |
| 46 | http://arxiv.org/abs/2603.18743v1 | Memento-Skills: Let Agents Design Agents | 通用持续可学习LLM Agent系统作为Agent设计Agent，自主构建适应改进任务特定Agent | 先前方法依赖人类设计Agent，通用Agent无法端到端设计新任务Agent | 通用AI助手 |
| 47 | http://arxiv.org/abs/2603.18815v1 | ProRL Agent: Rollout-as-a-Service for RL Training of Multi-Turn LLM Agents | 可扩展基础设施通过API服务提供完整Agent展开生命周期，标准化沙盒环境 | RL训练需生成大量沙盒展开轨迹，现有基础设施耦合展开编排与训练循环 | 多轮LLM Agent RL训练 |
| 48 | http://arxiv.org/abs/2603.16060v2 | ARISE: Agent Reasoning with Intrinsic Skill Evolution in Hierarchical Reinforcement Learning | 分层 RL 框架，技能管理器与 worker 协同进化技能库 | 解决现有方法孤立处理问题实例，未利用可复用策略的问题 | 数学推理技能进化 |
| 49 | http://arxiv.org/abs/2603.17187v1 | MetaClaw: Just Talk -- An Agent That Meta-Learns and Evolves in the Wild | 持续元学习框架，联合进化基础策略与可复用技能库 | 解决部署智能体静态无法适应用户需求演变的问题 | 持续元学习 |

[返回目录](#目录)

<a id="cat-13"></a>

## 多Agent强化学习

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2603.01260v1 | MOSAIC: A Unified Platform for Cross-Paradigm Comparison and Evaluation of Homogeneous and Heterogeneous Multi-Agent RL, LLM, VLM, and Human Decision-Makers | 开源平台支持异构代理在同一环境部署，提供跨范式确定性评估框架。 | 解决缺乏基础设施以公平比较不同决策范式代理在混合多代理设置中行为的问题。 | 多代理强化学习与异构代理比较 |
| 2 | http://arxiv.org/abs/2603.03759v1 | Learning Approximate Nash Equilibria in Cooperative Multi-Agent Reinforcement Learning via Mean-Field Subsampling | 交替学习框架，全局代理 subsampled mean-field Q-learning 对抗固定策略。 | 解决通信受限下全局代理与大量局部代理合作 Markov 博弈学习。 | 多机器人控制与联邦优化 |
| 3 | http://arxiv.org/abs/2603.02154v2 | Boltzmann-based Exploration for Robust Decentralized Multi-Agent Planning (Extended Version) | 替换确定性 UCT 为随机 Boltzmann 策略及衰减熵 bonus，实现持续聚焦探索。 | 解决 Dec-MCTS 在稀疏或偏斜奖励环境中表现挣扎的问题。 | 去中心化多 Agent 规划 |
| 4 | http://arxiv.org/abs/2603.02426v2 | Personalized Multi-Agent Average Reward TD-Learning via Joint Linear Approximation | 合作单 timescale TD 学习，Agent 迭代估计公共子空间及本地头，过滤冲突信号。 | 解决个性化多 Agent 平均奖励 TD 学习中异质性及 Markov 采样交互 shaping 误差的问题。 | 多 Agent 强化学习 |
| 5 | http://arxiv.org/abs/2603.02604v1 | Heterogeneous Agent Collaborative Reinforcement Learning | 异构 Agent 训练时共享验证 rollout 相互改进，推理时独立执行，双向相互学习。 | 解决孤立 on-policy 优化效率低及现有 MARL 需协调部署或单向转移的问题。 | 异构 Agent 协作 RL |
| 6 | http://arxiv.org/abs/2603.02654v2 | Generalized Per-Agent Advantage Estimation for Multi-Agent Policy Optimization | 每 Agent 价值迭代算子计算精确每 Agent 优势，双截断重要性采样比例方案。 | 解决多 Agent 强化学习中样本效率及协调性不足，信用分配困难的问题。 | 多 Agent 策略优化 |
| 7 | http://arxiv.org/abs/2603.02701v1 | Graph-GRPO: Stabilizing Multi-Agent Topology Learning via Group Relative Policy Optimization | 采样一组多样通信图，基于组内相对性能计算特定边优势，标准化奖励。 | 解决单样本策略梯度方差严重及信用分配问题，简单查询奖励非信息性的问题。 | 多 Agent 系统通信拓扑优化 |
| 8 | http://arxiv.org/abs/2603.06163v1 | Dual-Agent Multiple-Model Reinforcement Learning for Event-Triggered Human-Robot Co-Adaptation in Decoupled Task Spaces | 提出 DAMMRL 框架实现人机共适应 | 解决传统固定频率控制导致轨迹振荡问题 | 康复机器人与人协作 |
| 9 | http://arxiv.org/abs/2603.06810v1 | Multi-Agent Reinforcement Learning with Submodular Reward | 提供子模奖励下 MARL 形式框架与算法保证 | 解决联合奖励子模性下维数灾难与策略优化 | 多无人机监视与协作探索 |
| 10 | http://arxiv.org/abs/2603.06813v1 | Reinforcing the World's Edge: A Continual Learning Problem in the Multi-Agent-World Boundary | 量化去中心化 MARL 中策略诱导的非平稳性 | 解决 Agent-World 边界漂移导致不变核心消失 | 持续强化学习与多 Agent 系统 |
| 11 | http://arxiv.org/abs/2603.06859v1 | Contextual Counterfactual Credit Assignment for Multi-Agent Reinforcement Learning in LLM Collaboration | 提出 C3 方法隔离个体消息因果影响 | 解决稀疏终端反馈导致决策级信用分配困难 | LLM 协作中的多 Agent 强化学习 |
| 12 | http://arxiv.org/abs/2603.06977v1 | NePPO: Near-Potential Policy Optimization for General-Sum Multi-Agent Reinforcement Learning | 学习玩家独立势函数近似纳什均衡 | 解决一般和博弈中 MARL 训练不稳定与收敛难 | 混合合作竞争环境多 Agent 学习 |
| 13 | http://arxiv.org/abs/2603.04833v1 | SCoUT: Scalable Communication via Utility-Guided Temporal Grouping in Multi-Agent Reinforcement Learning | 通过时间和智能体抽象，软分组诱导亲和性作为接收者可微先验， counterfactual 通信优势。 | 解决部分观测 MARL 中学习何时与谁通信的选择空间大及信用分配难问题。 | 多智能体强化学习通信 |
| 14 | http://arxiv.org/abs/2603.05218v1 | KARL: Knowledge Agents via Reinforcement Learning | 基于迭代大批量 off-policy RL 训练企业搜索智能体，多能力评估套件。 | 解决企业搜索任务难验证及单一基准优化泛化差问题。 | 企业搜索/知识智能体 |
| 15 | http://arxiv.org/abs/2603.07370v1 | Learning to Reflect: Hierarchical Multi-Agent Reinforcement Learning for CSI-Free mmWave Beam-Focusing | 提出分层多智能体RL框架，利用用户定位数据替代CSI估计，管理大规模组合动作空间。 | 解决CSI估计开销 prohibitive 及集中式优化维度爆炸阻碍RIS实际部署的问题。 | 无线通信/毫米波波束聚焦 |
| 16 | http://arxiv.org/abs/2603.07618v1 | SMAT: Staged Multi-Agent Training for Co-Adaptive Exoskeleton Control | 提出四阶段课程SMAT，镜像用户适应可穿戴设备自然过程，训练肌肉骨骼与外骨骼智能体。 | 解决多数学习方法未明确考虑人类运动适应顺序性导致训练不稳定及协助时机不当问题。 | 外骨骼控制/康复机器人 |
| 17 | http://arxiv.org/abs/2603.12031v1 | AGMARL-DKS: An Adaptive Graph-Enhanced Multi-Agent Reinforcement Learning for Dynamic Kubernetes Scheduling | 图神经网络增强的多Agent协作调度，应力感知策略 | Kubernetes集群动态调度效率与稳定性 | 云原生应用/Kubernetes集群 |
| 18 | http://arxiv.org/abs/2603.12096v1 | A Robust and Efficient Multi-Agent Reinforcement Learning Framework for Traffic Signal Control | 转向比例随机化训练、指数相位调整动作空间 | 交通信号控制RL泛化性差、过拟合静态模式 | 城市交通信号系统 |
| 19 | http://arxiv.org/abs/2603.13019v1 | ARL-Tangram: Unleash the Resource Efficiency in Agentic Reinforcement Learning | 动作级编排，统一资源管理系统 | Agentic RL外部资源静态过度配置效率低 | 云集群Agentic RL训练 |
| 20 | http://arxiv.org/abs/2603.10098v1 | Code-Space Response Oracles: Generating Interpretable Multi-Agent Policies with Large Language Models | 用 LLM 替换 RL oracle，直接生成人类可读代码策略 | 解决深度 RL oracle 产生黑盒策略难以解释信任的问题 | 多智能体强化学习 |
| 21 | http://arxiv.org/abs/2603.10528v1 | UAV-MARL: Multi-Agent Reinforcement Learning for Time-Critical and Dynamic Medical Supply Delivery | MARL 框架协调 UAV  fleets，优先医疗请求分配资源 | 解决紧急情况下 UAV 舰队协调适应不确定操作条件问题 | 医疗物资无人机配送 |
| 22 | http://arxiv.org/abs/2603.11390v1 | SliceFed: Federated Constrained Multi-Agent DRL for Dynamic Spectrum Slicing in 6G | 联邦约束多智能体 DRL 框架，拉格朗日原对偶方法集成 PPO 强制执行约束 | 密集部署中资源分配优化难，需满足非平稳信道动态与严格 QoS 要求 | 6G 无线网络动态频谱切片 |
| 23 | http://arxiv.org/abs/2603.11582v1 | Multi-Agent Reinforcement Learning for UAV-Based Chemical Plume Source Localization | 基于 MARL 算法框架，利用虚拟锚节点协调 UAV 导航与协作 sensing | 传统 survey 方法难以检测老旧井，需高效定位甲烷排放源 | UAV 化学羽流源定位与环境监测 |
| 24 | http://arxiv.org/abs/2603.11691v1 | STAIRS-Former: Spatio-Temporal Attention with Interleaved Recursive Structure Transformer for Offline Multi-task Multi-agent Reinforcement Learning | 增强时空层次 Transformer 架构，引入 token dropout 增强鲁棒性与泛化 | 离线多任务 MARL 难泛化至未见场景，现有方法未充分利用注意力机制协调 | 离线多任务多智能体强化学习 |
| 25 | http://arxiv.org/abs/2603.11757v1 | Exploiting Expertise of Non-Expert and Diverse Agents in Social Bandit Learning: A Free Energy Approach | 基于自由能的社会 bandit 学习算法，社会智能体评估他人 expertise 水平 | 大多数 RL 算法关注个体学习，未能利用人类与动物常见的社会学习能力 | 个性化 AI 服务中的社会学习 |
| 26 | http://arxiv.org/abs/2603.11884v1 | The price of decentralization in managing engineering systems through multi-agent reinforcement learning | 引入退化系统集系统变化冗余，基准测试广泛 MADRL 算法 spanning 集中与分散范式 | 单 agent DRL 在多组件系统中扩展性差，分散化可能诱导合作病理降低最优性 | 工程系统检查与维护规划 |
| 27 | http://arxiv.org/abs/2603.14625v1 | EcoFair-CH-MARL: Scalable Constrained Hierarchical Multi-Agent RL with Real-Time Emission Budgets and Fairness Guarantees | 约束分层多智能体 RL 框架，统一预算层、公平奖励变换与双层策略架构 | 海事物流需同时高效、可持续且公平，现有方案难以兼顾 | 海事物流/多智能体 RL |
| 28 | http://arxiv.org/abs/2603.15054v1 | Interference-Aware K-Step Reachable Communication in Multi-Agent Reinforcement Learning | 提出IA-KRC框架，限制消息传递至物理可达邻居并优化伙伴选择 | 通信带宽有限与环境拓扑动态变化下的高价值伙伴识别 | 复杂协作任务多智能体强化学习 |
| 29 | http://arxiv.org/abs/2603.15418v1 | MA-VLCM: A Vision Language Critic Model for Value Estimation of Policies in Multi-Agent Team Settings | 用预训练视觉语言模型微调替代学习集中式评论家，提高样本效率 | 从头学习评论家样本效率低且缺乏泛化能力 | 多智能体团队策略价值估计 |
| 30 | http://arxiv.org/abs/2603.18563v1 | Reasonably reasoning AI agents can avoid game-theoretic failures in zero-shot, provably | 理论证明合理推理Agent零样本实现类Nash博弈，无需显式后训练 | 重复AI-AI交互中Agent无法稳定诱导战略均衡如Nash均衡 | 交互式经济环境 |
| 31 | http://arxiv.org/abs/2603.18683v1 | HISR: Hindsight Information Modulated Segmental Process Rewards For Multi-turn Agentic Reinforcement Learning | 利用后见信息调节分段过程奖励，段级过程RM分配子目标奖励 | 复杂长程Agent决策任务性能有限，稀疏结果奖励延迟传播 | 多轮Agent强化学习 |
| 32 | http://arxiv.org/abs/2603.18859v1 | RewardFlow: Topology-Aware Reward Propagation on State Graphs for Agentic RL with Large Language Models | 利用推理轨迹中状态内在拓扑结构构建状态图，拓扑感知图传播量化贡献 | 终端奖励稀疏性阻碍细粒度状态级优化，训练专用奖励模型成本高 | Agent推理任务RL |
| 33 | http://arxiv.org/abs/2603.19188v1 | Markov Potential Game and Multi-Agent Reinforcement Learning for Autonomous Driving | 提供MG为MPG充分条件，参数共享神经网络结构实现去中心化策略执行 | 自动驾驶中多Agent交互决策安全可靠性，一般和博弈中NE计算困难 | 自动驾驶决策 |
| 34 | http://arxiv.org/abs/2603.16141v1 | Communication-Aware Multi-Agent Reinforcement Learning for Decentralized Cooperative UAV Deployment | 图基于 MARL 框架，支持部分可观测下无人机协同部署 | 解决实际部署中通信间歇性及部分可观测性问题 | UAV 协同部署 |
| 35 | http://arxiv.org/abs/2603.16161v1 | SQL-ASTRA: Alleviating Sparse Feedback in Agentic SQL via Column-Set Matching and Trajectory Aggregation | 双层奖励机制，解决多轮信用分配及反馈稀疏问题 | 解决 Text-to-SQL 中信用分配模糊及反馈稀疏问题 | Text-to-SQL 任务 |
| 36 | http://arxiv.org/abs/2603.16470v1 | Multi-Agent Reinforcement Learning Counteracts Delayed CSI in Multi-Satellite Systems | 双阶段 PPO 算法，应对多卫星系统中延迟 CSI 问题 | 解决高传播延迟导致 CSI 过时及 sum-rate 优化问题 | 多卫星通信系统 |

[返回目录](#目录)

<a id="cat-14"></a>

## 低代码/无代码Agent平台

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2603.03233v1 | AI-for-Science Low-code Platform with Bayesian Adversarial Multi-Agent Framework | 贝叶斯对抗多智能体框架，协调任务管理、代码生成与评估代理。 | 解决科学代码生成可靠性低、错误传播及评估指标定义模糊问题。 | AI for Science 低代码平台 |
| 2 | http://arxiv.org/abs/2603.18122v1 | Don't Vibe Code, Do Skele-Code: Interactive No-Code Notebooks for Subject Matter Experts to Build Lower-Cost Agentic Workflows | 自然语言与图基于界面构建工作流，增量交互式笔记本式开发 | 多Agent系统方法执行工作流token成本高，非技术用户构建门槛高 | 主题专家构建Agentic工作流 |

[返回目录](#目录)

<a id="cat-15"></a>

## Agent可解释性与透明度

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2603.05941v1 | XAI for Coding Agent Failures: Transforming Raw Execution Traces into Actionable Insights | 将原始执行轨迹转化为结构化可解释解释 | 解决开发者难以理解调试代码 Agent 失败 | 软件开发工作流中的 Agent 调试 |
| 2 | http://arxiv.org/abs/2603.13173v2 | Semantic Invariance in Agentic AI | 变形测试框架评估语义不变性 | 标准基准无法捕捉推理稳定性维度 | 科学问题求解Agent |
| 3 | http://arxiv.org/abs/2603.11277v2 | COMPASS: The explainable agentic framework for Sovereignty, Sustainability, Compliance, and Ethics | 多智能体编排系统，包含四个专门子智能体，通过 RAG 接地评估并生成解释 | 现有框架孤立处理各维度，缺乏统一架构将规范整合进自主代理决策 | 数字主权、合规与伦理对齐 |
| 4 | http://arxiv.org/abs/2603.11479v1 | Grammar of the Wave: Towards Explainable Multivariate Time Series Event Detection via Neuro-Symbolic VLM Agents | 事件逻辑树 bridging 语言描述与物理信号，神经符号 VLM 智能体实例化原语 | 事件由语义定义难从稀缺数据归纳学习，VLM 匹配信号形态易幻觉 | 多变量时间序列事件检测 |
| 5 | http://arxiv.org/abs/2603.11872v2 | ELISA: An Interpretable Hybrid Generative AI Agent for Expression-Grounded Discovery in Single-Cell Genomics | 统一 scGPT 表达嵌入与 BioBERT 语义检索，LLM 介导解释用于交互式发现 | 智能体 AI 系统缺乏直接访问转录组表示，表达基础模型对自然语言不透明 | 单细胞基因组学表达发现 |
| 6 | http://arxiv.org/abs/2603.17445v2 | When Only the Final Text Survives: Implicit Execution Tracing for Multi-Agent Attribution | 生成时嵌入Agent特定键控信号到token分布，转换文本为自描述执行轨迹 | 多Agent系统产生错误答案时执行日志不可用的责任归属问题 | 多Agent语言系统审计 |

[返回目录](#目录)
