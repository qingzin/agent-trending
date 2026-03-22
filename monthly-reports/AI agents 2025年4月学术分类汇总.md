# AI agents 2025年4月学术分类汇总

共收录 347 篇论文，按研究方向分类整理如下。

## 目录

- [Agent规划与推理（12篇）](#cat-01)
- [Agent评测与基准（26篇）](#cat-02)
- [多Agent协作与通信（27篇）](#cat-03)
- [具身智能Agent（18篇）](#cat-04)
- [Agent架构与框架设计（31篇）](#cat-05)
- [Agent仿真与社会模拟（16篇）](#cat-06)
- [Agent安全与对齐（50篇）](#cat-07)
- [基于Agent的应用系统（85篇）](#cat-08)
- [Agent工具使用与环境交互（5篇）](#cat-09)
- [Agent学习与自进化（23篇）](#cat-10)
- [人机协作Agent（15篇）](#cat-11)
- [Agent记忆与知识管理（6篇）](#cat-12)
- [多Agent强化学习（31篇）](#cat-13)
- [Agent可解释性与透明度（1篇）](#cat-14)
- [低代码/无代码Agent平台（1篇）](#cat-15)

<a id="cat-01"></a>

## Agent规划与推理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2504.08694v1 | TP-RAG: Benchmarking Retrieval-Augmented Large Language Model Agents for Spatiotemporal-Aware Travel Planning | 提出TP-RAG基准和EvoRAG进化框架，整合检索轨迹与LLM推理 | 旅行规划中时空合理性不足、路线效率和POI吸引力问题 | 旅行规划Agent |
| 2 | http://arxiv.org/abs/2504.11788v3 | WebRollback: Enhancing Web Agents with Explicit Rollback Mechanisms | 显式回滚机制使Agent可返回导航轨迹中先前状态 | 贪婪单向搜索策略难以从错误状态恢复 | Web导航Agent |
| 3 | http://arxiv.org/abs/2504.12734v2 | Pandora: A Code-Driven Large Language Model Agent for Unified Reasoning Across Diverse Structured Knowledge | 利用Pandas API构建统一知识表示，LLM生成推理步骤和可执行Python代码 | 统一结构化知识推理任务特定策略难利用知识迁移 | 表格/数据库/知识图谱推理 |
| 4 | http://arxiv.org/abs/2504.15304v1 | Can Machine Learning Agents Deal with Hard Choices? | 分析ML Agent多目标优化局限，推荐集成方案识别困难选择 | MOO方法无法捕捉不可比性，Agent无法通过审议解决困难选择 | ML Agent决策对齐 |
| 5 | http://arxiv.org/abs/2504.14239v1 | InfiGUI-R1: Advancing Multimodal GUI Agents from Reactive Actors to Deliberative Reasoners | Actor2Reasoner两阶段训练：推理注入+审议增强，空间推理蒸馏+RL | 当前GUI Agent依赖手动推理模板，缺乏深度规划错误恢复 | 多模态GUI Agent |
| 6 | http://arxiv.org/abs/2504.01637v1 | LLM-mediated Dynamic Plan Generation with a Multi-Agent Approach | 利用 LLM 自动生成适应动态环境的 Agent 网络计划。 | 提升机器人在动态环境中的规划灵活性与通用性。 | 机器人与自动驾驶 |
| 7 | http://arxiv.org/abs/2504.01931v4 | On the Role of Feedback in Test-Time Scaling of Agentic AI Workflows | 提出迭代 Agent 解码，分析反馈在推理时对齐中的作用。 | 在有限推理预算下，通过反馈提升复杂任务成功率。 | 复杂 Agent 工作流 |
| 8 | http://arxiv.org/abs/2504.04471v1 | VideoAgent2: Enhancing the LLM-Based Agent System for Long-Form Video Understanding by Uncertainty-Aware CoT | 提出不确定性感知 CoT，增强长视频理解中的推理鲁棒性。 | 解决长视频理解中外部工具噪声及推理链脆弱的问题。 | 长视频内容理解 |
| 9 | http://arxiv.org/abs/2504.15785v1 | WALL-E 2.0: World Alignment by NeuroSymbolic Learning improves World Model-based LLM Agents | 训练免费的世界对齐学习符号知识， complement LLM | LLM 先验知识与指定环境动态之间存在差距 | 开放世界任务规划 |
| 10 | http://arxiv.org/abs/2504.16408v2 | LLMSR@XLLM25: Less is More: Enhancing Structured Multi-Agent Reasoning via Quality-Guided Distillation | 多智能体框架结合反向提示诱导与奖励过滤，蒸馏监督 | 低资源下挑战 LLM 生成可解释的逐步理由 | 结构化推理任务 |
| 11 | http://arxiv.org/abs/2504.16563v3 | Enhancing LLM-Based Agents via Global Planning and Hierarchical Execution | 引入持续更新的全局规划机制与分层执行策略 | 现有框架缺乏清晰全局目标且执行机制不稳定 | 复杂现实任务 |
| 12 | http://arxiv.org/abs/2504.16855v1 | Monte Carlo Planning with Large Language Model for Text-Based Game Agents | 结合 MCTS 与 LLM 语言理解能力，增强动态记忆 | 规划学习范式耗时且缺乏语言理解推理能力 | 文本游戏代理 |

[返回目录](#目录)

<a id="cat-02"></a>

## Agent评测与基准

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2504.08696v2 | SeaView: Software Engineering Agent Visual Interface for Enhanced Workflow | 首创SWE Agent轨迹可视化工具SeaView，支持实验对比和问题诊断 | SWE Agent轨迹超长难分析、错误定位困难、实验追踪不便 | 软件工程Agent研究人员 |
| 2 | http://arxiv.org/abs/2504.08703v3 | SWE-PolyBench: A multi-language benchmark for repository level evaluation of coding agents | 多语言仓库级代码Agent基准，含2110个实例和语法树分析指标 | 跨编程语言和真实场景的代码Agent评估挑战 | 代码生成Agent |
| 3 | http://arxiv.org/abs/2504.08942v2 | AgentRewardBench: Evaluating Automatic Evaluations of Web Agent Trajectories | 首个评估LLM judge评价Web Agent有效性的基准 | 规则基评估难扩展、人工评估慢且贵、LLM评估效果不明 | Web Agent轨迹评估 |
| 4 | http://arxiv.org/abs/2504.09702v3 | MLRC-Bench: Can Language Agents Solve Machine Learning Research Challenges? | 量化语言Agent解决ML研究竞赛能力的动态基准 | 缺乏客观评估AI研究能力的基准、LLM评判与实际性能错位 | ML研究Agent |
| 5 | http://arxiv.org/abs/2504.11543v2 | REAL: Benchmarking Autonomous Agents on Deterministic Simulations of Real Websites | 11个真实网站高保真确定性模拟，112个实际任务基准 | 缺乏可控可复现的Agent评估环境、前沿模型成功率低 | Web导航Agent评估 |
| 6 | http://arxiv.org/abs/2504.11571v1 | GraphicBench: A Planning Benchmark for Graphic Design with Language Agents | GraphicBench基准含1079个设计查询，GraphicTown框架含3专家46工具 | LLM Agent在开放式创意设计任务中规划执行能力评估 | 平面设计自动化 |
| 7 | http://arxiv.org/abs/2504.12516v1 | BrowseComp: A Simple Yet Challenging Benchmark for Browsing Agents | 1266个问题需持久导航互联网搜索难找信息，答案简短易验证 | 衡量Agent浏览网络核心能力：持久性和创造性 | Web浏览Agent评估 |
| 8 | http://arxiv.org/abs/2504.13472v2 | CodeVisionary: An Agent-based Framework for Evaluating Large Language Models in Code Generation | 两阶段Agent评估框架：需求引导上下文蒸馏+细粒度评分总结 | 现有评估基于静态提示，复杂代码场景缺乏细粒度评估 | 代码生成LLM评估 |
| 9 | http://arxiv.org/abs/2504.02867v1 | Multi-Agent LLM Judge: automatic personalized LLM judge design for evaluating natural language generation applications | 设计动态多 Agent 系统，自动生成个性化 LLM 评判器。 | 解决现有 LLM 评判框架灵活性差且与人类判断相关性低的问题。 | 自然语言生成应用评估 |
| 10 | http://arxiv.org/abs/2504.01382v4 | An Illusion of Progress? Assessing the Current State of Web Agents | 引入 Online-Mind2Web 基准， rigorous 评估当前 Web Agent 能力。 | 纠正现有基准导致的对 Web Agent 能力的过度乐观。 | Web 自动化 Agent |
| 11 | http://arxiv.org/abs/2504.02623v3 | Multi-Mission Tool Bench: Assessing the Robustness of LLM based Agents through Related and Dynamic Missions | 提出多任务工具基准，评估 Agent 在动态任务切换中的鲁棒性。 | 填补现有基准仅评估单任务场景的不足。 | 工具调用 Agent 评估 |
| 12 | http://arxiv.org/abs/2505.04628v1 | How Social is It? A Benchmark for LLMs' Capabilities in Multi-user Multi-turn Social Agent Tasks | 提出 HSII 基准，评估 LLM 在多用户多轮社交任务中的能力。 | 填补 LLM 在复杂社交场景中能力系统测量的空白。 | 社交 Agent 能力评估 |
| 13 | http://arxiv.org/abs/2504.03601v4 | APIGen-MT: Agentic Pipeline for Multi-Turn Data Generation via Simulated Agent-Human Interplay | 提出 APIGen-MT，通过模拟人机交互生成可验证的多轮 agent 数据。 | 解决多轮交互训练数据稀缺且人工收集昂贵的问题。 | 多轮交互 Agent 训练 |
| 14 | http://arxiv.org/abs/2504.04310v3 | CO-Bench: Benchmarking Language Model Agents in Algorithm Search for Combinatorial Optimization | 推出 CO-Bench，包含 36 个现实组合优化问题基准。 | 解决缺乏评估 LLM 智能体在结构化约束问题上能力的基准。 | 组合优化算法搜索 |
| 15 | http://arxiv.org/abs/2504.04808v2 | ELT-Bench: An End-to-End Benchmark for Evaluating AI Agents on ELT Pipelines | 推出 ELT-Bench，评估智能体构建端到端数据管道能力。 | 解决现有基准仅评估孤立任务，缺乏端到端 pipeline 评估的问题。 | 数据工程 ELT 管道 |
| 16 | http://arxiv.org/abs/2504.06468v1 | Agent-Arena: A General Framework for Evaluating Control Algorithms | 通用Python框架，支持仿真与真机场景下的决策策略评估 | 解决控制算法适配新环境难及超参调优复杂问题 | 机器人决策策略研发 |
| 17 | http://arxiv.org/abs/2504.07046v1 | A Unified Agentic Framework for Evaluating Conditional Image Generation | CIGEval框架，利用LMM核心集成多功能工具箱评估图像生成 | 解决条件图像生成评估指标缺乏任务无关性及可解释性问题 | 条件图像生成任务 |
| 18 | http://arxiv.org/abs/2504.07164v1 | R2E-Gym: Procedural Environments and Hybrid Verifiers for Scaling Open-Weights SWE Agents | AgentGym环境，混合测试时缩放策略提升开源SWE Agent性能 | 解决真实SWE任务执行环境 curated 难及测试计算缩放问题 | 软件工程Agent |
| 19 | http://arxiv.org/abs/2504.14928v3 | EducationQ: Evaluating LLMs' Teaching Capabilities Through Multi-Agent Dialogue Framework | 多智能体对话框架模拟动态教育场景评估教学能力 | 评估 LLM 教学能力资源密集且方法复杂 | LLM 教育能力评估 |
| 20 | http://arxiv.org/abs/2504.18565v2 | RepliBench: Evaluating the Autonomous Replication Capabilities of Language Model Agents | 评估套件测量语言模型代理的自主复制能力 | 不可控的代理自主复制构成关键安全风险 | 代理安全风险评估 |
| 21 | http://arxiv.org/abs/2504.17087v1 | Leveraging LLMs as Meta-Judges: A Multi-Agent Framework for Evaluating LLM Judgments | 三阶段元法官选择管道，引入多智能体协作评分 | 评估 LLM 响应日益挑战且存在人类判断偏差 | LLM 判断评估 |
| 22 | http://arxiv.org/abs/2504.17934v2 | Toward a Human-Centered Evaluation Framework for Trustworthy LLM-Powered GUI Agents | 提出以人为本的评估框架，整合风险评估与隐私安全考量。 | 解决现有 GUI 智能体评估忽视隐私安全风险及人类评估者整合难的问题。 | LLM 驱动的 GUI 自动化 |
| 23 | http://arxiv.org/abs/2504.18373v1 | Auto-SLURP: A Benchmark Dataset for Evaluating Multi-Agent Frameworks in Smart Personal Assistant | 扩展 SLURP 数据集为 Auto-SLURP，提供多智能体个人助手端到端评估基准。 | 解决缺乏专门评估 LLM 多智能体框架性能的基准数据集的问题。 | 智能个人助手评估 |
| 24 | http://arxiv.org/abs/2504.19912v1 | Can AI Agents Design and Implement Drug Discovery Pipelines? | 引入 DO Challenge 基准，评估 AI 智能体在虚拟筛选场景的决策能力。 | 解决缺乏评估 AI 智能体在复杂药物发现管道中决策能力的基准。 | 药物发现 pipeline 评估 |
| 25 | http://arxiv.org/abs/2504.21205v3 | SecRepoBench: Benchmarking Code Agents for Secure Code Completion in Real-World Repositories | 构建包含 318 个任务的基准，评估代码智能体在真实仓库中的安全补全能力。 | 解决现有基准难以评估代码智能体在真实场景中安全性问题。 | 代码安全补全智能体 |
| 26 | http://arxiv.org/abs/2505.00212v3 | Which Agent Causes Task Failures and When? On Automated Failure Attribution of LLM Multi-Agent Systems | 提出自动化失败归因方法，构建 Who&When 数据集链接失败与具体智能体。 | 解决 LLM 多智能体系统失败调试困难与归因劳动密集型问题。 | LLM 多智能体系统调试 |

[返回目录](#目录)

<a id="cat-03"></a>

## 多Agent协作与通信

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2504.08725v3 | DocAgent: A Multi-Agent System for Automated Code Documentation Generation | 多Agent协作系统，拓扑代码处理增量构建上下文 | 自动代码文档生成不完整、无帮助或事实错误 | 软件开发文档生成 |
| 2 | http://arxiv.org/abs/2504.09764v1 | Socratic Chart: Cooperating Multiple Agents for Robust SVG Chart Understanding | 多Agent管道将图表转为SVG，生成器提取属性、批评者验证 | MLLM图表推理依赖文本捷径、缺乏真正视觉理解 | 图表理解 |
| 3 | http://arxiv.org/abs/2504.09772v2 | Two Heads are Better Than One: Test-time Scaling of Multi-agent Collaborative Reasoning | 自适应多Agent框架，CEO Agent动态管理讨论过程 | 多Agent协作推理如何有效扩展是开放问题 | 复杂推理任务 |
| 4 | http://arxiv.org/abs/2504.10210v1 | Can Competition Enhance the Proficiency of Agents Powered by Large Language Models in the Realm of News-driven Time Series Forecasting? | 多Agent讨论中嵌入竞争机制，增强创新思维生成能力 | 现有多Agent讨论框架优化时间序列预测能力有限 | 新闻驱动时间序列预测 |
| 5 | http://arxiv.org/abs/2504.11002v2 | Dopamine Audiobook: A Training-free MLLM Agent for Emotional and Immersive Audiobook Generation | 免训练多Agent系统，MLLM担任语音和音频设计师双角色 | 多类型音频协同生成难、细粒度情感表达难、缺乏自动评估 | 有声书生成 |
| 6 | http://arxiv.org/abs/2504.12563v2 | MetaSynth: Meta-Prompting-Driven Agentic Scaffolds for Diverse Synthetic Data Generation | 元提示编排多专家LLM Agent协作生成数据，提升合成数据多样性 | 合成数据多样性低影响下游模型适用性 | 领域自适应数据生成 |
| 7 | http://arxiv.org/abs/2504.12635v1 | On Equivalence Between Decentralized Policy-Profile Mixtures and Behavioral Coordination Policies in Multi-Agent Systems | 证明去中心化策略组合与基于共同信息行为协调策略等价性 | 部分观测多Agent系统随机化理解与强对偶性 | 合作多Agent系统理论 |
| 8 | http://arxiv.org/abs/2504.12714v2 | Cross-environment Cooperation Enables Zero-shot Multi-agent Coordination | 跨环境合作学习使Agent发展通用协作规范，支持与新人零样本协调 | 专用模型无法泛化到新任务和新合作伙伴 | 人机协作AI系统 |
| 9 | http://arxiv.org/abs/2504.13399v1 | Towards a Multi-Agent Vision-Language System for Zero-Shot Novel Hazardous Object Detection for Autonomous Driving Safety | 多模态方法整合视觉语言推理与零样本物体检测识别危险 | 现有模型依赖预定义类别难检测标签外异常危险 | 自动驾驶安全系统 |
| 10 | http://arxiv.org/abs/2504.00587v2 | AgentNet: Decentralized Evolutionary Coordination for LLM-based Multi-Agent Systems | 提出去中心化 RAG 框架，支持 Agent 在 DAG 中自主演化协作。 | 解决集中式协调导致的扩展性瓶颈与单点故障问题。 | 多 Agent 协作系统 |
| 11 | http://arxiv.org/abs/2504.02051v2 | Self-Resource Allocation in Multi-Agent LLM Systems | 探索 LLM 作为编排器在多 Agent 系统中分配计算任务的有效性。 | 优化多 Agent 系统中的成本、效率与性能平衡。 | 多 Agent 系统资源管理 |
| 12 | http://arxiv.org/abs/2504.02128v2 | Achieving Unanimous Consensus Through Multi-Agent Deliberation | 引入基于 deliberation 的共识机制，LLM 作为理性 Agent 讨论。 | 在区块链中实现基于意见而非算力的 unanimous 共识。 | 区块链共识机制 |
| 13 | http://arxiv.org/abs/2504.03932v1 | YaleNLP @ PerAnsSumm 2025: Multi-Perspective Integration via Mixture-of-Agents for Enhanced Healthcare QA Summarization | 采用混合智能体（MoA）框架整合多视角医疗问答信息。 | 解决医疗社区问答中多用户视角 diverse 难以综合 summarization 的问题。 | 医疗 QA 摘要生成 |
| 14 | http://arxiv.org/abs/2504.05358v1 | Debate-Feedback: A Multi-Agent Framework for Efficient Legal Judgment Prediction | 提出 Debate-Feedback 架构，集成多智能体辩论与可靠性评估。 | 解决法律判决预测依赖大数据集且未充分利用 LLM 能力的问题。 | 法律判决预测 |
| 15 | http://arxiv.org/abs/2504.05365v1 | A Nature-Inspired Colony of Artificial Intelligence System with Fast, Detailed, and Organized Learner Agents for Enhancing Diversity and Quality | 构建基于 CNN 的 AI 智能体群落，模拟生物 Colony 协作。 | 解决单一模型多样性不足及集体决策质量低的问题。 | 多模型协作系统 |
| 16 | http://arxiv.org/abs/2504.05306v2 | CREA: A Collaborative Multi-Agent Framework for Creative Image Editing and Generation | 提出 CREA，多智能体协作模拟人类创意图像编辑过程。 | 解决创意图像编辑缺乏自主迭代及艺术意图平衡的问题。 | 创意图像编辑 |
| 17 | http://arxiv.org/abs/2504.05607v1 | FactGuard: Leveraging Multi-Agent Systems to Generate Answerable and Unanswerable Questions for Enhanced Long-Context LLM Extraction | 利用多智能体协作生成可答与不可答问题增强数据。 | 解决长上下文 LLM 难以识别不可答问题及标注成本高的问题。 | 长上下文阅读理解 |
| 18 | http://arxiv.org/abs/2504.08810v1 | PriM: Principle-Inspired Material Discovery through Multi-Agent Collaboration | 原则指导的材料发现系统，集成假设生成与实验验证MAS | 解决自动化材料发现探索效率低及结果难解释问题 | 功能材料理性设计 |
| 19 | http://arxiv.org/abs/2504.07303v1 | Modeling Response Consistency in Multi-Agent LLM Systems: A Comparative Analysis of Shared and Separate Context Approaches | 概率框架分析共享与分离上下文配置对响应一致性影响 | 解决LLM多Agent系统上下文管理及响应一致性挑战 | LLM驱动多Agent系统 |
| 20 | http://arxiv.org/abs/2504.07881v2 | An LLM-Driven Multi-Agent Debate System for Mendelian Diseases | MD2GPS系统，数据与知识驱动Agent辩论生成自然语言诊断 | 解决孟德尔疾病诊断准确率不足及依赖大数据预训练问题 | 精准医疗诊断 |
| 21 | http://arxiv.org/abs/2504.20054v3 | Marmot: Object-Level Self-Correction via Multi-Agent Reasoning | 多Agent推理框架，对象感知Agent分解任务并行校正 | 解决扩散模型多物体场景计数属性及空间关系不准问题 | 图像文本对齐生成 |
| 22 | http://arxiv.org/abs/2504.16736v3 | A Survey of AI Agent Protocols | 首次全面分析现有代理协议，提出二维分类 | 缺乏标准方式让代理与外部工具或数据源通信 | 代理通信协议 |
| 23 | http://arxiv.org/abs/2504.21030v1 | Advancing Multi-Agent Systems Through Model Context Protocol: Architecture, Implementation, and Applications | 通过模型上下文协议（MCP）标准化上下文共享与协调机制。 | 解决多智能体系统在上下文管理、协调效率及可扩展性方面的挑战。 | 企业知识管理与协作 |
| 24 | http://arxiv.org/abs/2505.07827v1 | MACH: Multi-Agent Coordination for RSU-centric Handovers | 将任务移交决策去中心化至 RSU，考虑负载与轨迹上下文优化 QoS。 | 解决车联网场景中任务移交的延迟感知与负载均衡问题。 | 车联网计算与路侧单元 |
| 25 | http://arxiv.org/abs/2505.00747v1 | Wireless Communication as an Information Sensor for Multi-agent Cooperative Perception: A Survey | 从信息-centric 视角综述 V2X 通信作为信息传感器在协作感知中的应用。 | 解决大规模交通场景下协作感知的通信约束与异构融合问题。 | 智能交通系统与自动驾驶 |
| 26 | http://arxiv.org/abs/2505.00091v4 | CoordField: Coordination Field for Agentic UAV Task Allocation In Low-alture Urban Scenarios | 利用 LLM 解析指令，提出 Coordination Field 机制引导 UAV 去中心化任务分配。 | 解决异构无人机群在复杂城市场景中任务规划与动态协调问题。 | 低空城市无人机 swarm |
| 27 | http://arxiv.org/abs/2505.00216v1 | Online Federation For Mixtures of Proprietary Agents with Black-Box Encoders | 提出专有联邦学习算法，协调黑盒专有 AI 代理形成混合专家模型。 | 解决黑盒专有 AI 代理无法优化内部参数与集成困难的问题。 | 专有 AI 模型集成与联邦学习 |

[返回目录](#目录)

<a id="cat-04"></a>

## 具身智能Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2504.08981v1 | AGENT: An Aerial Vehicle Generation and Design Tool Using Large Language Models | 基于CodeT5+的飞行器设计生成工具，可条件生成和评估设计 | 传统CAD仿真计算昂贵缓慢、设计搜索空间大 | 无人机设计 |
| 2 | http://arxiv.org/abs/2504.09021v2 | A Champion-level Vision-based Reinforcement Learning Agent for Competitive Racing in Gran Turismo 7 | 纯视觉赛车Agent，非对称actor-critic框架，仅需车载传感器 | 依赖外部全局定位、真实世界适用性受限 | 赛车模拟环境 |
| 3 | http://arxiv.org/abs/2504.09227v1 | SceneScout: Towards AI Agent-driven Access to Street View Imagery for Blind Users | MLLM驱动的街景交互Agent，支持路线预览和虚拟探索 | 视障用户缺乏详细视觉上下文、街景不可访问 | 视障用户导航辅助 |
| 4 | http://arxiv.org/abs/2504.09532v3 | Humanoid Agent via Embodied Chain-of-Action Reasoning with Multimodal Foundation Models for Zero-Shot Loco-Manipulation | 具身动作链推理机制，分解指令为移动和操作原语序列 | 人形机器人移动与操作整合难、指令理解转化难 | 人形机器人操作 |
| 5 | http://arxiv.org/abs/2504.09583v1 | AirVista-II: An Agentic System for Embodied UAVs Toward Dynamic Scene Semantic Understanding | 端到端无人机Agent系统，任务识别调度和关键帧提取 | 无人机任务依赖人工监控、效率适应性有限 | 无人机动态场景理解 |
| 6 | http://arxiv.org/abs/2504.10266v1 | Vision based driving agent for race car simulation environments | DRL训练视觉驾驶Agent，仅用视觉输入达到专业人类圈速 | 赛车紧急情况下轮胎抓地力极限控制问题 | 赛车模拟驾驶 |
| 7 | http://arxiv.org/abs/2504.11754v1 | GrabS: Generative Embodied Agent for 3D Object Segmentation without Scene Supervision | 两阶段流水线，学习生成式物体中心先验，具身Agent查询发现物体 | 无监督3D点云物体分割缺乏场景标注问题 | 3D视觉感知系统 |
| 8 | http://arxiv.org/abs/2504.00907v5 | Grounding Multimodal LLMs to Embodied Agents that Ask for Help with Reinforcement Learning | 利用在线 RL 微调 MLLM，使具身 Agent 能主动询问澄清。 | 解决家庭环境中指令模糊导致的任务执行失败问题。 | 家庭服务机器人 |
| 9 | http://arxiv.org/abs/2504.02450v3 | CHARMS: A Cognitive Hierarchical Agent for Reasoning and Motion Stylization in Autonomous Driving | 利用 Level-k 博弈论，构建认知分层 Agent 实现拟人化驾驶。 | 提升自动驾驶决策的交互性与行为多样性。 | 自动驾驶决策 |
| 10 | http://arxiv.org/abs/2504.08806v2 | Endowing Embodied Agents with Spatial Reasoning Capabilities for Vision-and-Language Navigation | 提出BrainNav框架，集成双地图双方向策略模仿生物认知 | 解决真实场景导航中空间幻觉及意识丢失问题 | 移动机器人VLN任务 |
| 11 | http://arxiv.org/abs/2504.08531v2 | Embodied Image Captioning: Self-supervised Learning Agents for Spatially Coherent Image Descriptions | 自监督方法提升Agent描述物体能力，共识机制蒸馏伪标题 | 解决不同视角及杂乱环境下图像标题连贯性问题 | 具身环境图像描述 |
| 12 | http://arxiv.org/abs/2504.08581v1 | FMLGS: Fast Multilevel Language Embedded Gaussians for Part-level Interactive Agents | 支持3DGS内部分级开放词汇查询，语义偏差策略解决歧义 | 解决多粒度交互语言歧义及物体组件查询质量退化问题 | 3D场景交互Agent |
| 13 | http://arxiv.org/abs/2504.15130v1 | Neural ATTF: A Scalable Solution to Lifelong Multi-Agent Path Planning | 结合优先级任务匹配与神经 STA*，优化路径规划 | 现有方案在动态环境中可扩展性与效率不足 | 仓库自动化与物流 |
| 14 | http://arxiv.org/abs/2504.15263v1 | Interpretable Locomotion Prediction in Construction Using a Memory-Driven LLM Agent With Chain-of-Thought Reasoning | 记忆驱动 LLM 代理结合多模态输入预测运动模式 | 外骨骼在动态环境中意图识别不准确 | 建筑外骨骼辅助 |
| 15 | http://arxiv.org/abs/2504.17950v1 | Collaborating Action by Action: A Multi-agent LLM Framework for Embodied Reasoning | 引入 MINDcraft 平台与 MineCollab 基准，测试 LLM 智能体在 Minecraft 中的协作。 | 解决具身场景中智能体自然语言通信效率低及协作能力不足的问题。 | 游戏环境与具身推理 |
| 16 | http://arxiv.org/abs/2504.19298v1 | AndroidGen: Building an Android Language Agent under Data Scarcity | 开发 AndroidGen 框架，在数据稀缺下增强 LLM 移动设备代理能力。 | 解决移动设备 Agent 缺乏高质量数据源及人工标注成本高的问题。 | 移动设备自动化 |
| 17 | http://arxiv.org/abs/2504.21347v1 | IRL Dittos: Embodied Multimodal AI Agent Interactions in Open Spaces | 设计 embodied agent 代表远程同事，模拟在场感以增强社交联系。 | 解决分布式团队中远程同事缺乏在场感与社交互动问题。 | 共享办公空间与远程协作 |
| 18 | http://arxiv.org/abs/2504.21716v1 | LLM-Empowered Embodied Agent for Memory-Augmented Task Planning in Household Robotics | 集成记忆增强任务规划，利用 RAG 检索上下文实现家庭物体管理。 | 解决家庭机器人执行高层命令时的长期物体跟踪与记忆 recall 问题。 | 家庭服务机器人 |

[返回目录](#目录)

<a id="cat-05"></a>

## Agent架构与框架设计

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2504.09037v4 | A Survey of Frontiers in LLM Reasoning: Inference Scaling, Learning to Reason, and Agentic Systems | 系统梳理LLM推理前沿，分类推理机制和Agent工作流设计 | LLM推理方法分散、缺乏系统理解 | LLM推理与Agent系统 |
| 2 | http://arxiv.org/abs/2504.09073v1 | A Multi-view Discourse Framework for Integrating Semantic and Syntactic Features in Dialog Agents | 话语感知框架，多视图典型相关分析整合语义句法特征 | 多轮对话忽略话语间交互、等权处理所有话语 | 检索式对话系统 |
| 3 | http://arxiv.org/abs/2504.12330v1 | HM-RAG: Hierarchical Multi-Agent Multimodal Retrieval Augmented Generation | 三层多Agent多模态RAG框架，分解-检索-决策协作 | 单Agent RAG难以处理跨异构数据的复杂查询 | 多模态知识合成 |
| 4 | http://arxiv.org/abs/2504.09736v1 | Agentic Workflows for Economic Research: Design and Implementation | 基于AutoGen的经济研究Agent工作流，覆盖研究全生命周期 | 经济研究效率低、可复现性差 | 经济研究 |
| 5 | http://arxiv.org/abs/2504.09848v1 | A Survey of Large Language Model-Powered Spatial Intelligence Across Scales: Advances in Embodied Agents, Smart Cities, and Earth Science | 跨尺度空间智能Agent综述，从具身到城市到全球层面 | 空间智能跨学科研究缺乏系统梳理 | 空间智能Agent |
| 6 | http://arxiv.org/abs/2504.10147v1 | A Survey of Personalization: From RAG to Agent | 系统梳理RAG到Agent的个性化研究，形式化定义和综述 | 个性化RAG和Agent缺乏系统综述 | 个性化Agent系统 |
| 7 | http://arxiv.org/abs/2504.12482v1 | Agentic AI Optimisation (AAIO): what it is, how it works, why it matters, and how to deal with it | 提出AAIO优化范式定义自主AI Agent与在线平台交互 | 确保网站与Agentic AI系统有效集成 | 数字基础设施优化 |
| 8 | http://arxiv.org/abs/2504.12735v2 | The Athenian Academy: A Seven-Layer Architecture Model for Multi-Agent Systems | 七层架构模型系统解决MAS协作效率、角色分配、环境适应等挑战 | AI艺术创作中多Agent系统协作与任务并行挑战 | AI艺术创作系统 |
| 9 | http://arxiv.org/abs/2504.14326v2 | Diffusion-based Dynamic Contract for Federated AI Agent Construction in Mobile Metaverses | 边缘云协作联邦AI Agent构建框架，两期动态合同激励ES参与 | 云基础LLM/VLM高延迟敏感数据泄露风险，ES参与意愿动态 | 移动元宇宙AI Agent |
| 10 | http://arxiv.org/abs/2504.00406v2 | VerifiAgent: a Unified Verification Agent in Language Model Reasoning | 提出统一验证代理，集成元验证与工具自适应验证机制。 | 解决大模型推理结果不可靠及验证方法缺乏通用性问题。 | 语言模型推理任务 |
| 11 | http://arxiv.org/abs/2504.00434v1 | HERA: Hybrid Edge-cloud Resource Allocation for Cost-Efficient AI Agents | 提出自适应迭代模型选择器，动态分配子任务至端云模型。 | 降低 AI Agent 运营成本，平衡精度与效率。 | 端云协同 AI Agent |
| 12 | http://arxiv.org/abs/2504.00727v1 | Personality-Driven Decision-Making in LLM-Based Autonomous Agents | 引入 OCEAN 人格模型，测量人格特质对 Agent 任务选择的影响。 | 实现具有 plausible 欺骗行为的主动网络防御 Agent 设计。 | 网络安全防御 Agent |
| 13 | http://arxiv.org/abs/2504.00906v1 | Agent S2: A Compositional Generalist-Specialist Framework for Computer Use Agents | 提出组合式框架，委托认知责任给通用与专用模型混合。 | 解决计算机使用 Agent  grounding 不准与长程规划难问题。 | 计算机任务自动化 |
| 14 | http://arxiv.org/abs/2505.13453v2 | Pel, A Programming Language for Orchestrating AI Agents | 设计 Pel 编程语言，提供语法级能力控制以安全编排 LLM。 | 解决现有方法在表达力、安全性与细粒度控制上的不足。 | AI Agent 编排与开发 |
| 15 | http://arxiv.org/abs/2504.04220v1 | AdaCoder: An Adaptive Planning and Multi-Agent Framework for Function-Level Code Generation | 提出 AdaCoder，自适应规划结合多智能体进行代码生成。 | 解决现有代码生成框架在不同基础模型上泛化性不稳定的问题。 | 函数级代码生成 |
| 16 | http://arxiv.org/abs/2504.04365v5 | AutoPDL: Automatic Prompt Optimization for LLM Agents | 提出 AutoPDL，自动化发现最优 LLM 智能体提示配置。 | 解决手动调整提示模式和内容繁琐且易错的问题。 | LLM 智能体提示优化 |
| 17 | http://arxiv.org/abs/2504.04485v1 | Building LLM Agents by Incorporating Insights from Computer Systems | 借鉴计算机系统原理（如冯诺依曼架构）设计 LLM 智能体。 | 解决当前 LLM 智能体设计缺乏系统原则，泛化性有限的问题。 | 智能体系统设计 |
| 18 | http://arxiv.org/abs/2504.04650v2 | Autono: A ReAct-Based Highly Robust Autonomous Agent Framework | 提出 Autono，基于 ReAct 的动态决策与多智能体协作框架。 | 解决固定工作流框架适应性差及终止策略不合理的问题。 | 复杂任务自主执行 |
| 19 | http://arxiv.org/abs/2504.16939v1 | A Desideratum for Conversational Agents: Capabilities, Challenges, and Future Directions | 提出对话智能体期望框架，分类推理、监控与控制能力。 | 解决对话智能体缺乏系统性能力定义及未来方向指引的问题。 | 对话智能体综述 |
| 20 | http://arxiv.org/abs/2504.08148v1 | Orchestrating Agents and Data for Enterprise: A Blueprint Architecture for Compound AI | 复合AI蓝图架构，利用流协调Agent间数据指令流 | 解决企业LLM应用集成难及缺乏整体架构愿景问题 | 企业级Agent应用 |
| 21 | http://arxiv.org/abs/2504.10519v2 | Toward Super Agent System with Hybrid AI Routers | 超级Agent系统设计，混合AI路由器动态选择本地云模型 | 解决超级Agent现实部署效率成本及隐私担忧问题 | 边缘设备超级Agent |
| 22 | http://arxiv.org/abs/2504.14427v1 | Optimizing SIA Development: A Case Study in User-Centered Design for Estuary, a Multimodal Socially Interactive Agent Framework | 提出以用户为中心的社会智能体开发框架设计模型 | 社会智能体框架缺乏用户中心的设计指导 | 社会交互智能体开发 |
| 23 | http://arxiv.org/abs/2504.15257v1 | FlowReasoner: Reinforcing Query-Level Meta-Agents | 查询级元代理自动化设计多智能体系统，利用执行反馈 | 为每个用户查询设计多智能体系统成本高 | 个性化多智能体系统 |
| 24 | http://arxiv.org/abs/2504.17700v1 | Applied Sheaf Theory For Multi-agent Artificial Intelligence (Reinforcement Learning) Systems: A Prospectus | 提出将层论应用于多智能体系统，提供局部到全局的数学建模工具。 | 解决复杂智能体系统中局部行为与 emergent 属性间的推理难题。 | 多智能体系统理论建模 |
| 25 | http://arxiv.org/abs/2504.20091v2 | VideoMultiAgents: A Multi-Agent Framework for Video Question Answering | 集成视觉、场景图与文本处理专用智能体，增强视频理解能力。 | 解决单模型难以捕捉视频 temporal 及交互上下文的问题。 | 视频问答任务 |
| 26 | http://arxiv.org/abs/2504.18875v1 | Generative to Agentic AI: Survey, Conceptualization, and Challenges | 对比 GenAI 与 Agentic AI，梳理演进路径及未来挑战。 | 解决业界对 Agentic AI 与 GenAI 区别理解不清及风险认知不足的问题。 | AI 技术演进与概念梳理 |
| 27 | http://arxiv.org/abs/2504.19678v2 | From LLM Reasoning to Autonomous AI Agents: A Comprehensive Review | 系统 consolidate 碎片化评估基准与框架，提出统一分类法。 | 解决 AI 智能体领域缺乏统一分类法及全面综述的问题。 | AI 智能体领域综述 |
| 28 | http://arxiv.org/abs/2504.19838v3 | LLM-Powered GUI Agents in Phone Automation: Surveying Progress and Prospects | 系统综述 LLM 驱动的_phone_GUI 智能体，提出分类法与挑战。 | 解决手机自动化领域缺乏结构化 overview 及研究 gap 识别的问题。 | 手机自动化与 GUI 交互 |
| 29 | http://arxiv.org/abs/2504.21304v1 | Unsupervised Feature Transformation via In-context Generation, Generator-critic LLM Agents, and Duet-play Teaming | 提出生成者 - 批评者二重奏框架，利用上下文学习从无监督数据推导伪监督。 | 解决高维数据特征变换中无监督效率低与标注成本大问题。 | 材料性能筛选等数据领域 |
| 30 | http://arxiv.org/abs/2504.21433v1 | NGENT: Next-Generation AI Agents Must Integrate Multi-Domain Abilities to Achieve Artificial General Intelligence | 论证下一代智能体需整合跨域能力（文本、视觉、机器人等）以实现 AGI。 | 解决当前智能体局限于窄域无法实现通用智能的问题。 | 通用人工智能（AGI）发展 |
| 31 | http://arxiv.org/abs/2505.00749v2 | Coral Protocol: Open Infrastructure Connecting The Internet of Agents | 提出开放去中心化协作基础设施，标准化消息格式与协调机制。 | 解决多智能体生态系统跨域互操作性、信任与支付问题。 | 智能体互联网（Internet of Agents） |

[返回目录](#目录)

<a id="cat-06"></a>

## Agent仿真与社会模拟

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2504.09407v3 | UXAgent: A System for Simulating Usability Testing of Web Design with LLM Agents | 生成数千模拟用户自动测试网站，提供结果查看接口 | 可用性测试研究设计本身难评估迭代 | UX研究可用性测试 |
| 2 | http://arxiv.org/abs/2504.09662v2 | AgentDynEx: Nudging the Mechanics and Dynamics of Multi-Agent Simulations | 引入"nudging"技术动态干预模拟，平衡机制与涌现动态 | 多Agent模拟难一致执行机制同时允许涌现动态 | 多Agent社会模拟 |
| 3 | http://arxiv.org/abs/2504.09723v4 | AgentA/B: Automated and Scalable Web A/B Testing with Interactive LLM Agents | LLM Agent自动模拟用户行为进行Web A/B测试 | 传统A/B测试依赖大规模真人流量、等待时间长 | Web UI/UX测试 |
| 4 | http://arxiv.org/abs/2504.10157v3 | SocioVerse: A World Model for Social Simulation Powered by LLM Agents and A Pool of 10 Million Real-World Users | LLM Agent驱动的世界模型，1000万真实用户池和四对齐组件 | 现有社会模拟在环境、用户、交互、行为对齐上存在挑战 | 社会科学研究 |
| 5 | http://arxiv.org/abs/2504.10789v1 | Can Large Language Models Trade? Testing Financial Theories with LLM Agents in Market Simulations | 真实模拟股市中LLM作为异质竞争交易Agent | 金融理论无闭式解时难模拟、真人实验成本高 | 金融市场模拟 |
| 6 | http://arxiv.org/abs/2504.03274v1 | Do Large Language Models Solve the Problems of Agent-Based Modeling? A Critical Review of Generative Social Simulations | 批判性综述生成式 ABM，指出 LLM 可能加剧验证与因果机制问题。 | 评估 LLM 是否真正解决了传统 ABM 的现实性与验证挑战。 | 社会科学与仿真建模 |
| 7 | http://arxiv.org/abs/2504.03604v1 | Epicast 2.0: A large-scale, demographically detailed, agent-based model for simulating respiratory pathogen spread in the United States | 构建 Epicast 2.0，利用合成人口模拟全美呼吸道病原体传播。 | 解决全国尺度疾病动态建模及资源分配决策支持问题。 | 公共卫生政策模拟 |
| 8 | http://arxiv.org/abs/2504.04872v2 | Simulating Persuasive Dialogues on Meat Reduction with Generative Agents | 利用生成式智能体模拟减肉对话，评估社会成本。 | 解决沟通策略开发依赖昂贵人类参与者实验的问题。 | 社会行为模拟 |
| 9 | http://arxiv.org/abs/2504.07610v1 | What Contributes to Affective Polarization in Networked Online Environments? Evidence from an Agent-Based Model | 基于Agent模型模拟个体新闻消费传播模式对情感极化影响 | 探究数字环境中情感极化驱动的因果机制及动态 | 在线社交网络环境 |
| 10 | http://arxiv.org/abs/2504.07830v3 | MOSAIC: Modeling Social AI for Content Dissemination and Regulation in Multi-Agent Simulations | 开源社交网络模拟框架，生成Agent预测用户行为 | 分析 emergent 欺骗行为及用户判定在线内容真实性机制 | 社交网络内容传播 |
| 11 | http://arxiv.org/abs/2504.08640v1 | Do LLMs trust AI regulation? Emerging behaviour of game-theoretic LLM agents | 演化博弈论框架嵌入LLM Agent，建模战略选择 | 探究AI开发生态系统中信任合作及监管策略互动 | AI监管系统模拟 |
| 12 | http://arxiv.org/abs/2504.14538v1 | BookWorld: From Novels to Interactive Agent Societies for Creative Story Generation | 构建基于书籍的多智能体社会，模拟虚构世界角色 | 现有研究未充分探索基于既定虚构世界的模拟 | 创意故事生成与社交模拟 |
| 13 | http://arxiv.org/abs/2504.18010v2 | Sky-Drive: A Distributed Multi-Agent Simulation Platform for Human-AI Collaborative and Socially-Aware Future Transportation | 构建分布式多智能体仿真平台 Sky-Drive，支持人机协作与社会意识驾驶。 | 解决现有模拟器缺乏人机协作及社会意识驾驶建模能力的问题。 | 未来交通系统仿真 |
| 14 | http://arxiv.org/abs/2504.18039v4 | MultiMind: Enhancing Werewolf Agents with Multimodal Reasoning and Theory of Mind | 集成多模态信息与心理理论模型，提升狼人杀智能体的社交推理能力。 | 解决社交推理游戏中忽略非语言线索及他人视角建模的问题。 | 社交演绎游戏仿真 |
| 15 | http://arxiv.org/abs/2504.19487v3 | Evolution of Cooperation in LLM-Agent Societies: A Preliminary Study Using Different Punishment Strategies | 利用 LLM 智能体模拟 Diner's Dilemma，验证惩罚机制对合作演化的影响。 | 解决传统数学模型缺乏自然语言推理及真实社会行为模拟的问题。 | 社会合作行为仿真 |
| 16 | http://arxiv.org/abs/2504.21609v1 | Applying Machine Learning for characterizing social networks Agent-based models | 利用 ML 刻画用户属性，构建 HPC 上社交网络 ABM 仿真的一般用户模型。 | 解决社交网络建模中数据处理复杂与用户行为模拟困难问题。 | 社交网络社区仿真 |

[返回目录](#目录)

<a id="cat-07"></a>

## Agent安全与对齐

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2504.13192v2 | CheatAgent: Attacking LLM-Empowered Recommender Systems via LLM Agent | LLM Agent攻击框架，识别插入位置生成对抗扰动 | LLM推荐系统安全漏洞研究不足、传统RL攻击无效 | LLM推荐系统安全 |
| 2 | http://arxiv.org/abs/2504.09841v1 | StruPhantom: Evolutionary Injection Attacks on Black-Box Tabular Agents Powered by Large Language Models | 进化优化攻击，约束蒙特卡洛树搜索生成攻击载荷 | 表格Agent严格数据格式使传统注入攻击无效 | 表格Agent安全 |
| 3 | http://arxiv.org/abs/2504.10374v1 | Ctrl-Z: Controlling AI Agents via Resampling | 重采样控制协议，动态采样某些动作阻止恶意代码执行 | Agent环境中监控安全协议防止颠覆性AI模型造成危害 | AI Agent安全控制 |
| 4 | http://arxiv.org/abs/2504.10915v2 | LOKA Protocol: A Decentralized Framework for Trustworthy and Ethical AI Agent Ecosystems | 去中心化框架，通用Agent身份层和伦理共识协议 | Agent身份、问责、伦理对齐存在基础缺口 | AI Agent生态系统治理 |
| 5 | http://arxiv.org/abs/2504.11281v1 | The Obvious Invisible Threat: LLM-Powered GUI Agents' Vulnerability to Fine-Print Injections | 表征六类攻击，实验测试GUI Agent对细字注入的脆弱性 | GUI Agent处理敏感用户数据时存在隐私安全风险 | GUI Agent安全 |
| 6 | http://arxiv.org/abs/2504.13203v2 | X-Teaming: Multi-Turn Jailbreaks and Defenses with Adaptive Multi-Agents | 自适应多Agent框架探索多轮越狱，生成30K交互越狱数据集 | 多轮交互安全风险、多轮红队测试适应性和多样性不足 | LLM多轮安全 |
| 7 | http://arxiv.org/abs/2504.11564v1 | Perceptions of Agentic AI in Organizations: Implications for Responsible AI and ROI | 解释性定性方法探究AI专业人员对Agent AI的感知和适应 | 组织中Agent AI负责任实施和适应存在显著挑战 | 组织AI治理 |
| 8 | http://arxiv.org/abs/2504.11703v2 | Progent: Programmable Privilege Control for LLM Agents | 首个LLM Agent工具级权限控制框架，领域特定语言定义细粒度策略 | Agent过特权工具访问导致的安全风险 | LLM Agent系统安全 |
| 9 | http://arxiv.org/abs/2504.12612v1 | The Chronicles of Foundation AI for Forensics of Multi-Agent Provenance | 符号编年史系统，时间戳签名记录，生成时同步更新溯源链 | 多Agent生成内容溯源追踪，贡献被覆盖无痕迹问题 | 多Agent协作内容溯源 |
| 10 | http://arxiv.org/abs/2504.15301v1 | A biologically Inspired Trust Model for Open Multi-Agent Systems that is Resilient to Rapid Performance Fluctuations | 生物启发信任模型，受托方自评估能力本地存储信任数据 | 开放动态多Agent系统信任管理，适应性能波动 | 开放多Agent系统安全 |
| 11 | http://arxiv.org/abs/2504.16108v1 | Trusted Identities for AI Agents: Leveraging Telco-Hosted eSIM Infrastructure | 利用电信级eSIM基础设施作为AI Agent身份信任根 | 分布式系统中AI Agent身份安全分配验证管理 | 企业AI Agent身份管理 |
| 12 | http://arxiv.org/abs/2504.13314v1 | On the Definition of Robustness and Resilience of AI Agents for Real-time Congestion Management | 量化评估框架，扰动Agent模拟自然和对抗性中断 | EU AI Act缺乏高风险部门鲁棒性韧性评估方法论 | 实时拥堵管理AI Agent |
| 13 | http://arxiv.org/abs/2504.14064v3 | DoomArena: A framework for Testing AI Agents Against Evolving Security Threats | 插件式可配置模块化安全评估框架，适配BrowserGym和τ-bench | SOTA Agent对不同威胁模型脆弱性 varying，需综合细粒度安全测试 | Web和工具调用Agent安全 |
| 14 | http://arxiv.org/abs/2504.14325v5 | FAIRGAME: a Framework for AI Agents Bias Recognition using Game Theory | 博弈论框架可靠模拟游戏场景，系统发现LLM/语言/人格/策略知识偏见 | 多Agent应用可解释性预测复杂性影响可信采用 | AI Agent偏见识别 |
| 15 | http://arxiv.org/abs/2504.00374v1 | When Persuasion Overrides Truth in Multi-Agent LLM Debates: Introducing a Confidence-Weighted Persuasion Override Rate (CW-POR) | 引入置信度加权说服覆盖率指标，评估多 Agent 辩论中的误导风险。 | 防止 LLM 在辩论中被错误信息高置信度说服。 | 多 Agent 辩论系统 |
| 16 | http://arxiv.org/abs/2504.00914v1 | On the Robustness of Agentic Function Calling | 建立基准评估 Agent 函数调用对输入扰动与工具扩展的鲁棒性。 | 揭示现有函数调用模型在真实部署中的脆弱性。 | Agent 工具调用安全 |
| 17 | http://arxiv.org/abs/2504.01278v1 | Strategize Globally, Adapt Locally: A Multi-Turn Red Teaming Agent with Dual-Level Learning | 提出双层次学习红队 Agent，模拟人类攻击者进行多轮探测。 | 识别并利用大模型在现实多轮场景中的漏洞。 | 大模型安全红队测试 |
| 18 | http://arxiv.org/abs/2504.03759v1 | Emerging Cyber Attack Risks of Medical AI Agents | 揭示医疗 AI Agent 通过网页工具遭受网络攻击的风险。 | 防止敏感医疗信息泄露及恶意推荐操纵。 | 医疗 AI Agent 安全 |
| 19 | http://arxiv.org/abs/2504.02254v1 | LLMs as Deceptive Agents: How Role-Based Prompting Induces Semantic Ambiguity in Puzzle Tasks | 研究基于角色的提示如何诱导 LLM 生成欺骗性谜题。 | 揭示 LLM 利用语义模糊进行 adversarial 行为的伦理风险。 | 教育技术与娱乐安全 |
| 20 | http://arxiv.org/abs/2504.03111v3 | Les Dissonances: Cross-Tool Harvesting and Polluting in Pool-of-Tools Empowered LLM Agents | 发现跨工具收割与污染威胁，开发动态扫描工具检测漏洞。 | 保护多工具 Agent 工作流中的控制流与隐私信息。 | 多工具 Agent 安全 |
| 21 | http://arxiv.org/abs/2504.03185v1 | Learning Natural Language Constraints for Safe Reinforcement Learning of Language Agents | 从演示中学习自然语言约束，作为安全对齐的首要步骤。 | 保证语言 Agent 在分布外场景下的约束满足与安全性。 | 安全关键型 NLP 应用 |
| 22 | http://arxiv.org/abs/2504.03255v2 | Inherent and emergent liability issues in LLM-based agentic systems: a principal-agent perspective | 从委托 - 代理视角分析 LLM _agent_ 系统的责任与治理问题。 | 明确 AI 责任归属，增强系统设计的透明度与可审计性。 | AI 治理与法律责任 |
| 23 | http://arxiv.org/abs/2504.04058v1 | Stochastic, Dynamic, Fluid Autonomy in Agentic AI: Implications for Authorship, Inventorship, and Liability | 分析代理 AI 的随机动态自主性对法律归属权的挑战。 | 解决人机贡献纠缠导致的知识产权与责任归属难题。 | 法律与政策框架 |
| 24 | http://arxiv.org/abs/2504.04070v1 | Enforcement Agents: Enhancing Accountability and Resilience in Multi-Agent AI Frameworks | 引入执行智能体（EA）实时监控并干预其他智能体行为。 | 解决多智能体系统中缺乏实时监督与安全对齐机制的问题。 | 多智能体系统安全 |
| 25 | http://arxiv.org/abs/2504.04072v3 | Among Us: A Sandbox for Measuring and Detecting Agentic Deception | 构建 Among Us 沙盒，测量智能体长期开放性欺骗行为。 | 解决现有基准无法评估智能体长期目标驱动欺骗的问题。 | 智能体欺骗检测 |
| 26 | http://arxiv.org/abs/2504.04608v1 | AI in a vat: Fundamental limits of efficient world modelling for agent sandboxing and interpretability | 揭示世界模型构建中效率与可解释性的根本权衡。 | 解决 Agent 沙盒评估中世界模型计算成本高且难解释的问题。 | 智能体安全评估 |
| 27 | http://arxiv.org/abs/2504.05259v1 | How to evaluate control measures for LLM agents? A trajectory from today to superintelligence | 提出适配 Agent 能力 profile 的控制评估框架。 | 解决控制评估未能随 AI 能力进化而调整导致的不准确问题。 | 超级智能控制评估 |
| 28 | http://arxiv.org/abs/2504.05871v2 | Agent Guide: A Simple Agent Behavioral Watermarking Framework | 提出 Agent Guide，通过行为概率偏差嵌入水印。 | 解决传统 token 级水印不适用于智能体行为追踪的问题。 | 智能体行为溯源 |
| 29 | http://arxiv.org/abs/2504.06868v4 | Persona Dynamics: Unveiling the Impact of Personality Traits on Agents in Text-Based Games | PANDA方法将人类人格特质投影到Agent以指导行为 | 解决Agent行为与人类价值观对齐及交互式决策有效性问题 | 文本交互式游戏 |
| 30 | http://arxiv.org/abs/2504.07461v1 | Achilles Heel of Distributed Multi-Agent Systems | 研究分布式多Agent系统信任挑战，识别自由 riding 等漏洞 | 解决异构LLM分布式部署带来的信任worthiness挑战 | 分布式多Agent系统 |
| 31 | http://arxiv.org/abs/2507.01019v1 | MALIBU Benchmark: Multi-Agent LLM Implicit Bias Uncovered | MALIBU基准，评估多Agent系统隐式强化社会偏见程度 | 解决多Agent系统设计中隐式偏见及公平性表示担忧 | 多Agent LLM系统 |
| 32 | http://arxiv.org/abs/2504.08848v1 | X-Guard: Multilingual Guard Agent for Content Moderation | 透明多语言安全Agent，防御低资源语言及代码切换攻击 | 解决现有安全框架多语言上下文脆弱及缺乏透明度问题 | LLM内容安全审核 |
| 33 | http://arxiv.org/abs/2504.08399v2 | Beyond Self-Reports: Multi-Observer Agents for Personality Assessment in Large Language Models | 多观察者框架评估LLM人格，减少自报告偏差 | 解决LLM人格评估自报告偏差及元知识污染问题 | LLM人格特质评估 |
| 34 | http://arxiv.org/abs/2504.14348v4 | Manipulating Multimodal Agents via Cross-Modal Prompt Injection | 提出跨模态提示注入框架，对齐视觉嵌入与恶意指令 | 多模态智能体面临跨模态提示注入的安全漏洞 | 多模态智能体安全 |
| 35 | http://arxiv.org/abs/2504.14395v1 | Hydra: An Agentic Reasoning Approach for Enhancing Adversarial Robustness and Mitigating Hallucinations in Vision-Language Models | 自适应代理框架，通过迭代推理和跨模型验证增强鲁棒性 | 视觉语言模型对抗鲁棒性差且易产生幻觉 | 视觉语言模型可靠性 |
| 36 | http://arxiv.org/abs/2504.14650v1 | A Framework for Benchmarking and Aligning Task-Planning Safety in LLM-Based Embodied Agents | 集成框架测量并对齐具身智能体的任务规划安全性 | 具身智能体系统安全性未被充分探索 | 具身智能体安全 |
| 37 | http://arxiv.org/abs/2504.15585v4 | A Comprehensive Survey in LLM(-Agent) Full Stack Safety: Data, Training and Deployment | 首次提出全栈安全概念，系统考虑 LLM 全生命周期 | 现有调查缺乏对 LLM 全生命周期的 comprehensive 理解 | LLM 全栈安全 |
| 38 | http://arxiv.org/abs/2504.15699v3 | Advancing Embodied Agent Security: From Safety Benchmarks to Input Moderation | 输入调节框架 safeguard 具身智能体，提出安全基准 | 缺乏针对具身智能体的安全基准与输入调节方法 | 具身智能体安全 |
| 39 | http://arxiv.org/abs/2504.18575v3 | WASP: Benchmarking Web Agent Security Against Prompt Injection Attacks | 新基准端到端评估 Web 代理安全对抗提示注入攻击 | 现有测试过于简化或赋予攻击者过多权力 | Web 代理安全 |
| 40 | http://arxiv.org/abs/2504.16489v1 | Amplified Vulnerabilities: Structured Jailbreak Attacks on LLM-based Multi-Agent Debate | 结构化提示重写框架利用多智能体辩论动态越狱 | 多智能体辩论系统固有脆弱性未被充分探索 | 多智能体辩论安全 |
| 41 | http://arxiv.org/abs/2504.16902v2 | Building A Secure Agentic AI Application Leveraging A2A Protocol | 基于 A2A 协议的综合安全分析，提供安全开发方法 | 复杂多智能体协作需要 robust 协议确保安全 | 安全代理应用开发 |
| 42 | http://arxiv.org/abs/2504.17669v2 | Towards a HIPAA Compliant Agentic AI System in Healthcare | 集成基于属性的访问控制与 PHI 净化管道，确保医疗智能体合规。 | 解决医疗 AI 智能体处理敏感数据时的 HIPAA 合规与隐私泄露风险。 | 医疗健康数据管理 |
| 43 | http://arxiv.org/abs/2504.18601v1 | The Philosophic Turn for AI Agents: Replacing centralized digital rhetoric with decentralized truth-seeking | 主张 AI 设计转向去中心化真理寻求，模仿苏格拉底对话保护人类自主性。 | 解决 AI 决策支持系统可能侵蚀人类自主性与代理权的风险。 | AI 伦理与人类自主性 |
| 44 | http://arxiv.org/abs/2504.18839v4 | Detect, Explain, Escalate: Sustainable Dialogue Breakdown Management for LLM Agents | 提出“检测 - 解释 - 升级”框架，利用小模型检测对话崩溃以降低成本。 | 解决 LLM 对话崩溃影响部署可靠性及大模型直接检测成本高的问题。 | 对话系统可靠性管理 |
| 45 | http://arxiv.org/abs/2504.21034v2 | SAGA: A Security Architecture for Governing AI Agentic Systems | 提出 SAGA 安全架构，提供用户控制的智能体生命周期管理与访问控制。 | 解决自主智能体系统缺乏用户 oversight 及恶意 agent 损害控制问题。 | 智能体系统安全治理 |
| 46 | http://arxiv.org/abs/2504.19793v3 | Prompt Injection Attack to Tool Selection in LLM Agents | 提出 ToolHijacker，通过注入恶意工具文档操纵 LLM 智能体工具选择。 | 解决无盒场景下工具选择过程易受提示注入攻击的安全漏洞。 | 智能体工具安全 |
| 47 | http://arxiv.org/abs/2504.19951v1 | Securing GenAI Multi-Agent Systems Against Tool Squatting: A Zero Trust Registry-Based Approach | 提出基于零信任注册表的工具注册系统，防御工具 squatting 攻击。 | 解决多智能体系统互操作协议中工具欺骗注册的安全风险。 | 智能体工具集成安全 |
| 48 | http://arxiv.org/abs/2504.19956v2 | Securing Agentic AI: A Comprehensive Threat Model and Mitigation Framework for Generative AI Agents | 提出 ATFAA 威胁模型与 SHIELD 缓解框架，针对 GenAI 智能体的自主性与记忆访问风险。 | 解决 GenAI 智能体特有的自主决策与持久记忆带来的新型安全威胁。 | 企业级 GenAI 智能体系统 |
| 49 | http://arxiv.org/abs/2504.20965v2 | AegisLLM: Scaling Agentic Systems for Self-Reflective Defense in LLM Security | 构建多智能体协作防御工作流，通过提示优化实现自我改进防御。 | 解决 LLM 对抗攻击与信息泄露的实时防御与适应性问题。 | LLM 安全防御系统 |
| 50 | http://arxiv.org/abs/2504.21848v1 | Characterizing AI Agents for Alignment and Governance | 提出 autonomy, efficacy 等四维特征框架，构建智能体 profile 以辅助治理。 | 解决 AI 智能体治理缺乏核心属性理解与分类框架的问题。 | AI 治理与政策制定 |

[返回目录](#目录)

<a id="cat-08"></a>

## 基于Agent的应用系统

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2504.09855v1 | PestMA: LLM-based Multi-Agent System for Informed Pest Management | 编辑范式多Agent系统，编辑-检索-验证三Agent协作 | 单Agent害虫管理难整合多元信息、系统验证不足 | 农业害虫管理 |
| 2 | http://arxiv.org/abs/2504.11496v1 | IEA-Plugin: An AI Agent Reasoner for Test Data Analytics | LangGraph平台AI Agent推理模块，利用LLM推理和编码能力 | 捕获多样工程需求、提高系统可扩展性 | 工业测试数据分析 |
| 3 | http://arxiv.org/abs/2504.11497v1 | LLM-based AI Agent for Sizing of Analog and Mixed Signal Circuit | LLM Agent整合外部电路仿真工具和数据分折功能 | 模拟电路晶体管尺寸设计手动工作量大、迭代多 | 模拟混合信号电路设计 |
| 4 | http://arxiv.org/abs/2504.11502v1 | Timing Analysis Agent: Autonomous Multi-Corner Multi-Mode (MCMM) Timing Debugging with Timing Debug Relation Graph | 多LLM任务求解Agent，时序调试关系图连接报告与调试轨迹 | 先进制程下时序报告调试挑战大、周转时间长 | VLSI电路时序分析 |
| 5 | http://arxiv.org/abs/2504.10978v1 | AgentPolyp: Accurate Polyp Segmentation via Image Enhancement Agent | CLIP语义引导动态图像增强Agent，质量评估反馈循环 | 息肉图像受人为环境因素干扰、光照模糊过曝 | 医疗内镜息肉分割 |
| 6 | http://arxiv.org/abs/2504.11109v2 | Agent-Q: Fine-Tuning Large Language Models for Quantum Circuit Generation and Optimization | LLM微调系统生成优化量子电路，14000个电路数据集 | 预训练LLM缺乏量子电路知识、难大规模自动生成 | 量子电路生成 |
| 7 | http://arxiv.org/abs/2504.12110v2 | Towards LLM Agents for Earth Observation | 140题基准测试LLM Agent地球观测能力，微调合成数据降低失败率 | LLM Agent使用Google Earth Engine API代码执行失败率高 | 地球观测数据分析 |
| 8 | http://arxiv.org/abs/2504.12143v1 | ARCeR: an Agentic RAG for the Automated Definition of Cyber Ranges | Agentic RAG范式从自然语言描述自动生成部署网络靶场 | LLM或基础RAG系统无法处理的复杂网络安全环境构建 | 网络安全训练环境 |
| 9 | http://arxiv.org/abs/2504.12679v4 | TongUI: Internet-Scale Trajectories from Multimodal Web Tutorials for Generalized GUI Agents | 从多模态Web教程构建143K轨迹数据集GUI-Net，覆盖5系统200+应用 | GUI Agent缺乏跨操作系统和应用充足轨迹数据 | 通用GUI Agent训练 |
| 10 | http://arxiv.org/abs/2504.12865v1 | DashChat: Interactive Authoring of Industrial Dashboard Design Prototypes through Conversation with LLM-Powered Agents | 多Agent流水线理解文本需求生成实用美观原型，并行Agent高效生成 | 工业仪表板原型设计视觉复杂、约束多、迭代成本高 | 工业仪表板设计 |
| 11 | http://arxiv.org/abs/2504.12891v1 | Are AI agents the new machine translation frontier? Challenges and opportunities of single- and multi-agent systems for multilingual digital communication | 多Agent系统含翻译/充分性审查/流畅性审查/最终编辑四专家Agent | 复杂场景需高准确性、领域知识、上下文感知的机器翻译 | 法律机器翻译 |
| 12 | http://arxiv.org/abs/2504.13263v2 | Causal-Copilot: An Autonomous Causal Analysis Agent | 自动化因果分析全流程：发现/推断/算法选择/超参优化/结果解释 | 因果分析概念算法复杂，领域专家难以使用 | 科学发现与决策 |
| 13 | http://arxiv.org/abs/2504.13805v1 | LearnAct: Few-Shot Mobile GUI Agent with a Unified Demonstration Benchmark | LearnGUI数据集2252离线+101在线任务，三Agent框架从演示提取知识 | 移动GUI Agent多样化真实场景泛化挑战 | 移动GUI自动化 |
| 14 | http://arxiv.org/abs/2504.14110v1 | System of Agentic AI for the Discovery of Metal-Organic Frameworks | MOFGen系统含LLM/扩散模型/量子力学/合成可行性四互联Agent | 生成模型导航巨大化学空间同时确保可合成性挑战 | 金属有机框架材料发现 |
| 15 | http://arxiv.org/abs/2504.14233v1 | Template-Based Financial Report Generation in Agentic and Decomposed Information Retrieval | 比较AgenticIR协作Agent与DecomposedIR提示链工作流生成模板财务报告 | LLM生成符合预定义多节模板报告挑战 | 财务分析报告生成 |
| 16 | http://arxiv.org/abs/2504.00338v1 | Agentic Multimodal AI for Hyperpersonalized B2B and B2C Advertising in Competitive Markets: An AI-Driven Competitive Advertising Framework | 提出多模态 AI 框架，集成 RAG 与自适应 persona  targeting。 | 解决动态市场中广告个性化与竞争适应性问题。 | B2B/B2C 广告市场 |
| 17 | http://arxiv.org/abs/2504.00711v2 | GraphMaster: Automated Graph Synthesis via LLM Agents in Data-Limited Environments | orchestrate 四个专用 LLM 代理协作优化图数据合成。 | 解决数据稀缺环境下图基础模型缺乏语义丰富数据的问题。 | 图数据合成与 GFMs |
| 18 | http://arxiv.org/abs/2504.00741v1 | Accelerated Inorganic Materials Design with Generative AI Agents | 结合扩散模型与预测模型，利用 LLM 推理引导材料探索。 | 加速无机晶体材料设计，提高成分有效性与新颖性。 | 材料科学发现 |
| 19 | http://arxiv.org/abs/2504.02870v2 | AI Hiring with LLMs: A Context-Aware and Explainable Multi-Agent Framework for Resume Screening | 构建四核心 Agent 框架，集成 RAG 增强简历评估上下文相关性。 | 自动化简历筛选，提高招聘效率与公平性。 | 人才招聘与简历筛选 |
| 20 | http://arxiv.org/abs/2504.01234v2 | First Field-Trial Demonstration of L4 Autonomous Optical Network for Distributed AI Training Communication: An LLM-Powered Multi-AI-Agent Solution | 演示跨域跨层 L4 自主光网络，利用多 AI Agent 系统管理通信。 | 提升分布式 AI 训练通信的任务完成率与自动化水平。 | 光网络与 AI 训练通信 |
| 21 | http://arxiv.org/abs/2504.01377v1 | Large-scale Evaluation of Notebook Checkpointing with AI Agents | 利用 AI Agent 模拟大规模数据探索场景，评估检查点框架。 | 评估计算笔记本检查点机制对生产力的实际影响。 | 数据科学工作流 |
| 22 | http://arxiv.org/abs/2504.01495v1 | Are Autonomous Web Agents Good Testers? | 探索将自主 Web Agent 适配为自然语言测试执行代理。 | 减少自动化测试脚本维护成本，实现低维护测试。 | 软件测试自动化 |
| 23 | http://arxiv.org/abs/2504.01911v2 | Advancing AI-Scientist Understanding: Multi-Agent LLMs with Interpretable Physics Reasoning | 构建多 Agent 物理学家框架，将 LLM 输出转化为可解释模型。 | 提高 AI 在物理研究中的可靠性、透明度与可验证性。 | 科学研究与物理建模 |
| 24 | http://arxiv.org/abs/2504.02891v1 | Automated Survey Collection with LLM-based Conversational Agents | 构建端到端电话调查框架，利用 LLM 代理收集与分析数据。 | 降低传统电话调查成本，实现可扩展的医疗数据收集。 | 医疗调查与数据收集 |
| 25 | http://arxiv.org/abs/2504.02800v4 | Survey and Experiments on Mental Disorder Detection via Social Media: From Large Language Models and RAG to Agents | 系统综述 LLM、RAG 及 Agent 系统在社交媒体精神障碍检测中的应用。 | 建立统一基准，推动可信赖的自主心理健康支持系统。 | 心理健康与数字表型 |
| 26 | http://arxiv.org/abs/2504.03424v1 | The AI Cosmologist I: An Agentic System for Automated Data Analysis | 构建 AI 宇宙学家系统，自动化 cosmological 数据分析与研究流程。 | 自动化科研过程，加速科学发现与论文生成。 | 天文学与机器学习研究 |
| 27 | http://arxiv.org/abs/2504.04698v1 | scAgent: Universal Single-Cell Annotation via a LLM Agent | 提出 scAgent，利用 LLM 智能体进行通用单细胞注释。 | 解决单细胞注释难以跨组织泛化及发现新细胞类型的问题。 | 生物医学单细胞分析 |
| 28 | http://arxiv.org/abs/2504.04789v1 | Multimodal Agricultural Agent Architecture (MA3): A New Paradigm for Intelligent Agricultural Decision-Making | 提出 MA3，融合多模态信息实现智能农业决策。 | 解决农业生产中气候不确定性风险及决策效率低的问题。 | 智能农业决策 |
| 29 | http://arxiv.org/abs/2504.04855v1 | BIASINSPECTOR: Detecting Bias in Structured Data through LLM Agents | 提出 BIASINSPECTOR，多智能体协同检测结构化数据偏差。 | 解决现有自动化偏差检测技术泛化性差且依赖人工的问题。 | 数据科学偏差检测 |
| 30 | http://arxiv.org/abs/2504.05104v2 | AI for Climate Finance: Agentic Retrieval and Multi-Step Reasoning for Early Warning System Investments | 利用 Agent 检索与多步推理追踪气候金融投资。 | 解决气候适应投资缺乏标准化报告及追踪困难的问题。 | 气候金融追踪 |
| 31 | http://arxiv.org/abs/2504.05122v1 | DoCIA: An Online Document-Level Context Incorporation Agent for Speech Translation | 提出 DoCIA，在线集成文档级上下文增强语音翻译。 | 解决语音翻译中噪声干扰及文档级上下文利用不足的问题。 | 语音翻译系统 |
| 32 | http://arxiv.org/abs/2504.05370v1 | EduPlanner: LLM-Based Multi-Agent Systems for Customized and Intelligent Instructional Design | 提出 EduPlanner，多智能体协作生成定制化教学设计方案。 | 解决单一 LLM 难以管理完整教学设计及个性化不足的问题。 | 智能教育课程设计 |
| 33 | http://arxiv.org/abs/2504.05527v1 | Bridging Industrial Expertise and XR with LLM-Powered Conversational Agents | 集成 RAG 增强 LLM 与 XR 技术，提供工业专家指导。 | 解决工业环境中知识转移困难及缺乏上下文感知指导的问题。 | 工业培训与维护 |
| 34 | http://arxiv.org/abs/2504.05716v3 | Single-Agent vs. Multi-Agent LLM Strategies for Automated Student Reflection Assessment | 比较单/多 Agent 策略评估学生反思及预测学业表现。 | 解决传统反思评估耗时且难以规模化支持学生的问题。 | 教育评估与干预 |
| 35 | http://arxiv.org/abs/2504.05862v2 | Are Generative AI Agents Effective Personalized Financial Advisors? | 评估 LLM 顾问在 eliciting 偏好及提供个性化建议的有效性。 | 解决高风险金融领域 AI 顾问可靠性及用户信任问题。 | 个人金融顾问 |
| 36 | http://arxiv.org/abs/2504.06031v1 | Virtual Agent Tutors in Sheltered Workshops: A Feasibility Study on Attention Training for Individuals with Intellectual Disabilities | 评估虚拟智能体导师在智力障碍者注意力训练中的可行性。 | 解决特殊群体认知训练缺乏个性化及社会辅助支持的问题。 | 特殊教育与康复 |
| 37 | http://arxiv.org/abs/2504.06196v1 | TxGemma: Efficient and Agentic LLMs for Therapeutics | 引入TxGemma套件及Agentic-Tx系统，支持治疗属性预测与推理 | 解决药物开发成本高、失败率高及数据有限问题 | therapeutic开发 pipeline |
| 38 | http://arxiv.org/abs/2504.07148v1 | Q-Agent: Quality-Driven Chain-of-Thought Image Restoration Agent through Robust Multimodal Large Language Model | 质量驱动Agent，细粒度降解感知与贪婪恢复序列决策 | 解决多降解同时处理难及现有Agent忽略图像质量问题 | 复杂场景图像恢复 |
| 39 | http://arxiv.org/abs/2504.06614v1 | AgentFM: Role-Aware Failure Management for Distributed Databases with LLM-Driven Multi-Agents | 角色感知故障管理框架，元Agent编排系统、数据及任务角色 | 解决分布式数据库故障管理忽略角色区分及泛化差问题 | 分布式数据库运维 |
| 40 | http://arxiv.org/abs/2504.07277v3 | Agentic LMs: Hunting Down Test Smells | 评估小参数模型基于Agent工作流检测重构测试异味 | 解决测试异味自动化移除支持少及依赖静态分析问题 | 软件测试与维护 |
| 41 | http://arxiv.org/abs/2504.07634v1 | Agent That Debugs: Dynamic State-Guided Vulnerability Repair | VulDebugger代理，利用静态动态上下文调试修复漏洞 | 解决手动漏洞修复耗时及静态检索Agent补丁生成不足问题 | 软件漏洞自动修复 |
| 42 | http://arxiv.org/abs/2504.07643v1 | CollEX -- A Multimodal Agentic RAG System Enabling Interactive Exploration of Scientific Collections | 多模态Agentic RAG系统，LVLM作为代理支持交互探索 | 解决科学集合搜索缺乏直观性及交互性 barriers 问题 | 科学收藏交互探索 |
| 43 | http://arxiv.org/abs/2504.07655v2 | Synthesizing High-Quality Programming Tasks with LLM-based Expert and Student Agents | PyTaskSyn技术，专家与学生Agent多阶段验证任务质量 | 解决AI生成编程任务质量差距及需人工干预验证问题 | 计算教育任务生成 |
| 44 | http://arxiv.org/abs/2504.08066v1 | The AI Scientist-v2: Workshop-Level Automated Scientific Discovery via Agentic Tree Search | 端到端Agentic系统，自主提出假设实验及撰写论文 | 解决科学发现过程自动化程度低及依赖人工代码模板问题 | 自动化科学研究 |
| 45 | http://arxiv.org/abs/2504.13190v1 | Cellular-X: An LLM-empowered Cellular Agent for Efficient Base Station Operations | 多模态LLM Agent自动化基站维护，支持语音配置报告 | 解决现场工程师基站配置效率低及意图理解慢问题 | 蜂窝基站运维 |
| 46 | http://arxiv.org/abs/2504.08113v2 | Test Amplification for REST APIs via Single and Multi-Agent LLM Systems | 利用单/多Agent LLM系统放大REST API测试套件 | 解决REST API复杂度高及 comprehensive 测试套件创建难问题 | 云原生应用测试 |
| 47 | http://arxiv.org/abs/2504.08621v2 | MooseAgent: A LLM Based Multi-agent Framework for Automating Moose Simulation | 多Agent框架自动化MOOSE仿真，任务分解迭代验证 | 解决多物理仿真预处理配置耗时及需专业知识问题 | 工程科学计算仿真 |
| 48 | http://arxiv.org/abs/2504.14482v1 | DialogueAgents: A Hybrid Agent-Based Speech Synthesis Framework for Multi-Party Dialogue | 混合代理框架协同生成对话，提升情感表达力 | 现有语音合成数据集构建成本高且缺乏多样性 | 多党派对话语音合成 |
| 49 | http://arxiv.org/abs/2504.14557v2 | Enhancing LLM-based Quantum Code Generation with Multi-Agent Optimization and Quantum Error Correction | 多智能体框架 tailored 生成容错量子代码，集成纠错 | 领域特定语言生成缺乏定制化优化与准确性 | 量子程序生成 |
| 50 | http://arxiv.org/abs/2504.14625v3 | Towards Optimal Circuit Generation: Multi-Agent Collaboration Meets Collective Intelligence | 多智能体协作结合集体智能，实现人类级电路设计效率 | LLM 硬件设计门计数远高于人类设计 | 硬件电路生成 |
| 51 | http://arxiv.org/abs/2504.14681v1 | An LLM-enabled Multi-Agent Autonomous Mechatronics Design Framework | 多智能体自主机电设计框架，集成多学科 expertise | 复杂工程任务需要物理体现及跨学科整合 | 机电系统设计 |
| 52 | http://arxiv.org/abs/2504.14822v2 | Completing A Systematic Review in Hours instead of Months with Interactive AI Agents | 交互式 AI 代理分区处理文献，显著缩短系统综述时间 | 系统综述耗时耗力且现有自动方法质量低 | 医疗系统综述 |
| 53 | http://arxiv.org/abs/2504.14837v5 | SQL-Factory: A Multi-Agent Framework for High-Quality and Large-Scale SQL Generation | 多智能体框架分解生成过程，平衡多样性与成本 | 自动 SQL 生成难以兼顾多样性与成本效益 | 数据库 SQL 生成 |
| 54 | http://arxiv.org/abs/2504.15474v1 | Agent for User: Testing Multi-User Interactive Features in TikTok | 多智能体方法自动化测试多用户交互式应用功能 | 多用户交互功能测试面临设备管理与协调挑战 | 社交媒体应用测试 |
| 55 | http://arxiv.org/abs/2504.15552v1 | A Multi-Agent Framework for Automated Qinqiang Opera Script Generation Using Large Language Models | 多智能体框架自动化秦腔剧本端到端生产 | 传统表演艺术 preservation 缺乏 AI 驱动流程 | 传统戏曲剧本生成 |
| 56 | http://arxiv.org/abs/2504.16420v1 | A Survey of Foundation Model-Powered Recommender Systems: From Feature-Based, Generative to Agentic Paradigms | 综述基础模型在推荐系统中的三种范式集成 | 推荐系统范式正在被基础模型重塑 | 推荐系统 |
| 57 | http://arxiv.org/abs/2504.16918v3 | OptimAI: Optimization from Natural Language Using LLM-Powered AI Agents | 多角色协作框架将自然语言优化问题转化为数学形式 | formulat 优化问题需要大量领域专业知识 | 科学优化问题求解 |
| 58 | http://arxiv.org/abs/2504.17200v1 | A RAG-Based Multi-Agent LLM System for Natural Hazard Resilience and Adaptation | 基于 RAG 的多智能体系统支持自然灾害决策分析 | 通用模型难以提供特定背景的自然灾害信息 | 自然灾害韧性决策 |
| 59 | http://arxiv.org/abs/2504.17213v2 | MASR: Self-Reflective Reasoning through Multimodal Hierarchical Attention Focusing for Agent-based Video Understanding | 多模态分层注意力聚焦，自适应提取查询相关上下文 | 视频理解需要在大模型中合理分配注意力 | 代理视频理解 |
| 60 | http://arxiv.org/abs/2504.17334v1 | DataScout: Automatic Data Fact Retrieval for Statement Augmentation with an LLM-Based Agent | 交互式系统自动执行推理与基于立场的数据事实检索 | 检索数据事实耗时且挑战创作者分析技能 | 数据故事增强 |
| 61 | http://arxiv.org/abs/2504.17575v1 | A Multi-Agent, Laxity-Based Aggregation Strategy for Cost-Effective Electric Vehicle Charging and Local Transformer Overload Prevention | 引入基于“松弛度”的多智能体聚合协调机制，优化电动汽车充电调度。 | 解决大规模电动汽车并发充电导致的变压器过载问题。 | 电力系统与电动汽车充电 |
| 62 | http://arxiv.org/abs/2504.19940v2 | Assessing the Potential of Generative Agents in Crowdsourced Fact-Checking | 模拟具有不同人口统计特征的生成式智能体 crowd 进行事实核查。 | 解决众包事实核查中质量波动大及人类偏见问题。 | 在线 misinformation 治理 |
| 63 | http://arxiv.org/abs/2504.17967v1 | LLM Agent Swarm for Hypothesis-Driven Drug Discovery | 提出 PharmaSwarm，编排专用 LLM 智能体群进行药物假设生成与验证。 | 解决药物发现中数据流分散及缺乏模块化迭代记忆的问题。 | 生物医药研发 |
| 64 | http://arxiv.org/abs/2504.18058v1 | Exploring Personality-Aware Interactions in Salesperson Dialogue Agents | 探索基于 MBTI 用户人格的销售对话智能体交互质量与适应性。 | 解决对话系统缺乏对用户个性特征适应及个性化策略不足的问题。 | 销售领域对话系统 |
| 65 | http://arxiv.org/abs/2504.18260v1 | MAGI: Multi-Agent Guided Interview for Psychiatric Assessment | 转化 MINI 访谈为多智能体工作流，实现自动化精神科评估。 | 解决现有 LLM 方法不符合精神科诊断协议及缺乏临床严谨性的问题。 | 心理健康评估 |
| 66 | http://arxiv.org/abs/2504.18316v1 | Towards Adaptive Software Agents for Debugging | 提出自适应智能体设计，动态确定智能体数量与角色以修复代码。 | 解决固定多智能体调试成本高及易失去焦点的问题。 | 软件调试与代码修复 |
| 67 | http://arxiv.org/abs/2504.20082v2 | Evolution of AI in Education: Agentic Workflows | 分析教育中智能体工作流的四大范式，并提出自动评分概念验证。 | 解决教育场景中 AI 智能体应用缺乏系统范式及一致性评估的问题。 | 教育技术与自动评分 |
| 68 | http://arxiv.org/abs/2504.20094v3 | Toward Safe and Human-Aligned Game Conversational Recommendation via Multi-Agent Decomposition | 提出 MATCHA 框架，分配专用智能体处理意图、检索、排序与风险控制。 | 解决游戏推荐中目录变化快、交互偏好复杂及不安全响应风险。 | 游戏对话推荐系统 |
| 69 | http://arxiv.org/abs/2504.18765v3 | A Vision for Auto Research with LLM Agents | 提出基于智能体的自动研究框架，覆盖科研全生命周期。 | 解决科研工作流碎片化、方法论 expertise 不均及认知过载问题。 | 科学研究自动化 |
| 70 | http://arxiv.org/abs/2504.18805v1 | Stealing Creator's Workflow: A Creator-Inspired Agentic Framework with Iterative Feedback Loop for Improved Scientific Short-form Generation | 模仿创作者工作流，利用迭代反馈机制生成科学短视频。 | 解决科学视频生成中事实不准确及视觉 artifacts 问题。 | 科学传播与视频生成 |
| 71 | http://arxiv.org/abs/2504.18880v4 | Reshaping MOFs text mining with a dynamic multi-agents framework of large language model | 利用 LLM 多智能体框架从文献中提取 MOF 合成条件并标准化。 | 解决文献中合成信息分散、不一致及难以解读的问题。 | 材料科学文献挖掘 |
| 72 | http://arxiv.org/abs/2504.19017v1 | Sparks: Multi-Agent Artificial Intelligence Model Discovers Protein Design Principles | 多模态多智能体模型执行完整发现周期，独立发现蛋白质设计原则。 | 解决 AI 系统仅重现训练数据知识而缺乏自主科学发现能力的问题。 | 蛋白质科学与设计 |
| 73 | http://arxiv.org/abs/2504.20115v2 | AutoP2C: An LLM-Based Agent Framework for Code Repository Generation from Multimodal Content in Academic Papers | 提出 AutoP2C，从论文多模态内容生成可执行代码仓库。 | 解决将论文多模态内容转化为可执行代码困难且耗时的问题。 | 科研代码复现 |
| 74 | http://arxiv.org/abs/2504.20117v2 | ResearchCodeAgent: An LLM Multi-Agent System for Automated Codification of Research Methodologies | 利用多智能体系统自动化编码研究方法论，桥接概念与实现。 | 解决研究方法论从文献到代码实现转化效率低的问题。 | 机器学习研究实现 |
| 75 | http://arxiv.org/abs/2504.19565v3 | Knowledge-Driven Agentic Scientific Corpus Distillation Framework for Biomedical Large Language Models Training | 提出知识驱动的智能体框架，从文献中蒸馏高质量生物医学语料。 | 解决开源生物医学标注语料数量质量不足阻碍 LLM 训练的问题。 | 生物医学 LLM 训练 |
| 76 | http://arxiv.org/abs/2504.19818v1 | PhenoAssistant: A Conversational Multi-Agent AI System for Automated Plant Phenotyping | 利用 LLM 编排工具包，通过自然语言交互简化植物表型分析工作流。 | 解决现有植物表型方案复杂、难维护及用户技术门槛高的问题。 | 植物生物学与表型分析 |
| 77 | http://arxiv.org/abs/2504.20412v2 | CrashFixer: A crash resolution agent for the Linux kernel | 构建 kGymSuite 平台，实现首个基于 LLM 的 Linux 内核崩溃修复智能体。 | 解决大规模系统级内核 bug 修复中 LLM 智能体应用能力不足问题。 | Linux 内核开发与维护 |
| 78 | http://arxiv.org/abs/2504.20434v2 | ARCS: Agentic Retrieval-Augmented Code Synthesis with Iterative Refinement | 提出预算化合成 - 执行 - 修复循环，检索上下文后生成代码并基于反馈修复。 | 解决 LLM 代码生成中的幻觉问题并加速收敛，无需微调。 | 代码合成与翻译任务 |
| 79 | http://arxiv.org/abs/2504.20462v5 | TAMO: Fine-Grained Root Cause Analysis via Tool-Assisted LLM Agent with Multi-Modality Observation Data in Cloud-Native Systems | 统一多模态观测数据，调用专用工具进行根因定位与故障分类。 | 解决云原生系统中 LLM 处理实时原始数据与动态依赖的局限性。 | 云原生系统运维与根因分析 |
| 80 | http://arxiv.org/abs/2504.20464v2 | A Survey on GUI Agents with Foundation Models Enhanced by Reinforcement Learning | 结构化综述基于 MLLM 与 RL 的 GUI 智能体架构、训练方法及演进。 | 解决 GUI 智能体在复杂环境中泛化性与鲁棒性不足的问题。 | 图形用户界面交互智能体 |
| 81 | http://arxiv.org/abs/2504.20552v1 | BrAIcht, a theatrical agent that speaks like Bertolt Brecht's characters | 使用 QLoRA 微调 German LeoLM，生成特定戏剧风格的对话。 | 解决特定文学风格对话生成的个性化与记忆容量限制问题。 | 戏剧对话生成与角色扮演 |
| 82 | http://arxiv.org/abs/2504.20898v2 | CBM-RAG: Demonstrating Enhanced Interpretability in Radiology Report Generation with Multi-Agent RAG and Concept Bottleneck Models | 结合概念瓶颈模型与多 Agent RAG，生成可解释的放射学报告。 | 解决医疗 AI 报告生成中的可解释性差与幻觉问题。 | 放射学报告自动生成 |
| 83 | http://arxiv.org/abs/2504.21252v1 | Talk Before You Retrieve: Agent-Led Discussions for Better RAG in Medical QA | 引入总结者与决策者智能体模拟多轮头脑风暴，优化检索内容。 | 解决医疗 RAG 系统中检索片段无关与缺乏人类推理建模问题。 | 医疗问答系统 |
| 84 | http://arxiv.org/abs/2507.21055v2 | Can Memory-Augmented LLM Agents Aid Journalism in Interpreting and Framing News for Diverse Audiences? | 构建 MADES 框架，模拟不同职业/年龄智能体讨论新闻以识别理解差距。 | 解决新闻内容因受众专业背景不同导致的理解差距与误解问题。 | 新闻解读与受众 framing |
| 85 | http://arxiv.org/abs/2505.03785v2 | mAIstro: an open-source multi-agentic system for automated end-to-end development of radiomics and deep learning models for medical imaging | 编排多智能体系统实现医疗 AI 模型端到端开发，无需用户编码。 | 解决医疗 AI 工作流复杂、需编码且难以统一开发的问题。 | 医疗影像 AI 模型开发 |

[返回目录](#目录)

<a id="cat-09"></a>

## Agent工具使用与环境交互

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2504.10046v2 | GraphCodeAgent: Dual Graph-Guided LLM Agent for Retrieval-Augmented Repo-Level Code Generation | 双图引导Agent，需求图和结构语义代码图多跳推理检索 | NL需求与编程实现存在差距、细粒度子任务检索失败 | 仓库级代码生成 |
| 2 | http://arxiv.org/abs/2504.12682v1 | WebLists: Extracting Structured Information From Complex Interactive Websites Using Executable LLM Agents | BardeenAgent将执行转换为可重复程序，构建通用CSS选择器提取数据 | 大规模结构化数据提取任务LLM和Web Agent表现差 | 企业数据提取任务 |
| 3 | http://arxiv.org/abs/2504.16073v1 | Guiding VLM Agents with Process Rewards at Inference Time for GUI Navigation | 推理时通过奖励模型过程监督引导 VLM 代理优化动作 | 当前框架在挑战性 GUI 环境中难以生成正确动作 | GUI 导航与控制 |
| 4 | http://arxiv.org/abs/2504.20168v1 | MICE for CATs: Model-Internal Confidence Estimation for Calibrating Agents with Tools | 利用模型内部层解码与相似度评分，构建概率分类器评估工具调用置信度。 | 解决工具使用智能体置信度校准差导致的风险决策问题。 | 使用外部工具的 LLM 智能体 |
| 5 | http://arxiv.org/abs/2504.21561v4 | Iterative Tool Usage Exploration for Multimodal Agents via Step-wise Preference Tuning | 提出 SPORT 方法，通过逐步偏好优化自主发现有效工具使用策略。 | 解决多模态智能体工具使用训练依赖昂贵人工标注的问题。 | 多模态任务智能体 |

[返回目录](#目录)

<a id="cat-10"></a>

## Agent学习与自进化

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2504.10127v2 | Breaking the Data Barrier -- Building GUI Agents Through Task Generalization | 中期训练任务泛化策略，跨模态知识迁移解决数据稀缺 | GUI Agent高质量轨迹数据稀缺制约性能 | GUI Agent训练 |
| 2 | http://arxiv.org/abs/2504.10458v4 | GUI-R1 : A Generalist R1-Style Vision-Language Action Model For GUI Agents | 首个强化学习框架增强LVLM的GUI能力，统一动作空间规则建模 | 监督微调需大量数据、难理解GUI截图和泛化未见过界面 | 跨平台GUI Agent |
| 3 | http://arxiv.org/abs/2504.11301v2 | Learning to Be A Doctor: Searching for Effective Medical Agent Architectures | 医疗Agent架构自动设计框架，层次化搜索空间动态工作流适应 | 现有医疗Agent依赖静态手工工作流、缺乏灵活性 | 医疗诊断Agent |
| 4 | http://arxiv.org/abs/2504.12497v2 | Requirements for Recognition and Rapid Response to Unfamiliar Events Outside of Agent Design Scope | 结合领域通用元知识和元推理，实现未知事件快速自适应响应 | Agent在设计范围外未知情况的识别与合理响应 | 开放世界通用Agent |
| 5 | http://arxiv.org/abs/2504.13145v2 | Exploring Expert Failures Improves LLM Agent Tuning | EEF方法从失败专家轨迹识别有益动作整合到训练数据集 | RFT偏向简单场景，复杂子任务持续分布外未解决 | LLM Agent微调优化 |
| 6 | http://arxiv.org/abs/2504.13541v3 | Scalable Multi-Task Learning through Spiking Neural Networks with Adaptive Task-Switching Policy for Intelligent Autonomous Agents | SwitchMT采用自适应任务切换策略，利用奖励和网络内部动态 | 固定任务切换间隔限制性能可扩展性，任务干扰问题 | 资源受限自主Agent |
| 7 | http://arxiv.org/abs/2504.02489v1 | The Self-Learning Agent with a Progressive Neural Network Integrated Transformer | 集成 LLaMA 3.2 与渐进神经网络，实现对话与代码的持续学习。 | 提升 Agent 的适应性与记忆稳定性，迈向 AGI。 | 对话 AI 与代码生成 |
| 8 | http://arxiv.org/abs/2504.03553v2 | Agentic Knowledgeable Self-awareness | 提出 KnowSelf，通过两阶段训练实现智能体知识自主调节。 | 解决传统规划方法盲目注入知识，缺乏情境自我意识的问题。 | 通用任务规划智能体 |
| 9 | http://arxiv.org/abs/2504.03561v3 | SynWorld: Virtual Scenario Synthesis for Agentic Action Knowledge Refinement | 构建 SynWorld 框架，利用 MCTS 在虚拟场景中细化动作知识。 | 解决智能体在新环境或非常规动作空间中探索能力不足的问题。 | 新环境下的智能体探索 |
| 10 | http://arxiv.org/abs/2504.04785v1 | Weak-for-Strong: Training Weak Meta-Agent to Harness Strong Executors | 训练弱元智能体设计工作流以驾驭强模型。 | 解决直接微调强模型成本高及无训练方法效果次优的问题。 | 大模型工作流优化 |
| 11 | http://arxiv.org/abs/2504.06188v1 | SkillFlow: Efficient Skill and Code Transfer Through Communication in Adapting AI Agents | 模块化框架允许Agent通过通信获取新技能，类比基因横向转移 | 解决Agent功能扩展依赖预定义编程，适应性问题 | 自适应AI Agent |
| 12 | http://arxiv.org/abs/2504.06821v2 | Inducing Programmatic Skills for Agentic Tasks | 代理技能归纳ASI，在线诱导验证并利用程序化技能 | 解决Web导航任务泛化差及静态基线Agent效率低问题 | Web自动化任务 |
| 13 | http://arxiv.org/abs/2504.07079v1 | SkillWeaver: Web Agents can Self-Improve by Discovering and Honing Skills | 技能中心框架，自主合成可复用技能API并迭代扩展库 | 解决Web Agent缺乏程序知识抽象及技能组合自改进能力 | 复杂环境Web Agent |
| 14 | http://arxiv.org/abs/2504.15313v1 | PolicyEvol-Agent: Evolving Policy via Environment Perception and Self-Awareness with Theory of Mind | 结合心智理论获取他人意图，自适应优化非理性策略 | 动态交互场景中代理认知偏差及策略僵化 | 多智能体博弈与决策 |
| 15 | http://arxiv.org/abs/2504.15046v5 | Text-to-Decision Agent: Offline Meta-Reinforcement Learning from Natural Language Supervision | 利用自然语言监督离线元强化学习，实现零-shot 泛化 | 离线元 RL 依赖昂贵监督信号且泛化受限 | 决策任务泛化 |
| 16 | http://arxiv.org/abs/2504.15228v2 | A Self-Improving Coding Agent | 代理系统配备编码工具可自主编辑自身以提升性能 | LLM 代理系统缺乏自动化开放式设计机制 | 代码代理自我改进 |
| 17 | http://arxiv.org/abs/2504.16078v1 | LLMs are Greedy Agents: Effects of RL Fine-tuning on Decision-Making Abilities | 通过 RL 微调自生成 CoT 理由，增强探索与缩小知行差距 | LLM 代理在决策场景中存在次优探索与知行差距 | LLM 决策能力 |
| 18 | http://arxiv.org/abs/2504.21024v2 | WebEvolver: Enhancing Web Agent Self-Improvement with Coevolving World Model | 引入共演世界模型 LLM，生成自指令数据 refine 策略 | 自主学习中性能达到停滞点，探索有限 | Web 代理自我改进 |
| 19 | http://arxiv.org/abs/2504.20073v2 | RAGEN: Understanding Self-Evolution in LLM Agents via Multi-Turn Reinforcement Learning | 提出 StarPO 框架，通过轨迹级 RL 训练实现 LLM 智能体的自我进化。 | 解决多轮交互中奖励方差大及智能体推理能力难以涌现的问题。 | LLM 智能体训练与优化 |
| 20 | http://arxiv.org/abs/2504.19276v1 | Anyprefer: An Agentic Framework for Preference Data Synthesis | 将数据合成 framing 为合作博弈，利用外部工具辅助 judge 模型减少偏差。 | 解决自奖励方法中奖励模型与目标模型权重共享导致偏差放大的问题。 | 模型对齐与偏好数据合成 |
| 21 | http://arxiv.org/abs/2505.01441v1 | Agentic Reasoning and Tool Integration for LLMs via Reinforcement Learning | 提出 ARTIST 框架，耦合智能体推理、RL 与工具集成，自主决定工具调用。 | 解决 LLM 依赖静态知识及缺乏动态多步推理与工具交互能力的问题。 | 复杂推理与工具使用 |
| 22 | http://arxiv.org/abs/2504.20997v2 | Toward Efficient Exploration by Large Language Model Agents | 显式实现 PSRL 算法于 LLM 中，提升自然语言任务的数据效率探索。 | 解决 LLM 智能体在强化学习中探索效率低与数据需求大问题。 | 自然语言环境下的 RL 智能体 |
| 23 | http://arxiv.org/abs/2504.21798v2 | SWE-smith: Scaling Data for Software Engineering Agents | 构建流水线自动生成大规模软件工程训练数据，提升 Agent 修复率。 | 解决软件工程智能体训练数据稀缺、收集成本高与扩展性问题。 | 软件工程自动化智能体 |

[返回目录](#目录)

<a id="cat-11"></a>

## 人机协作Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2504.10918v1 | Adaptive Human-Agent Teaming: A Review of Empirical Studies from the Process Dynamics Perspective | 从过程动态视角系统综述人机协作，T⁴框架四阶段 | HAT研究碎片化、忽视现实适应性需求 | 人机协作系统 |
| 2 | http://arxiv.org/abs/2504.12125v1 | EmoACT: a Framework to Embed Emotions into Artificial Agents Based on Affect Control Theory | 基于情感控制理论框架在机器人中嵌入合成情感 | 提升人机交互自然性和透明度 | 人形机器人交互 |
| 3 | http://arxiv.org/abs/2504.13707v3 | OpenDeception: Learning Deception and Trust in Human-AI Interaction via Multi-Agent Simulation | 轻量框架联合评估人机对话双方欺骗风险，IntentNet+TrustNet | 现有评估场景特定模型中心，缺乏开放式人机交互欺骗评估 | 人机对话安全 |
| 4 | http://arxiv.org/abs/2504.13793v1 | ChatNekoHacker: Real-Time Fan Engagement with Conversational Agents | 整合Amazon Bedrock Agents+Unity 3D直播+VOICEVOX日语TTS双虚拟人 | 音乐人粉丝互动实时对话Agent系统设计与效果评估 | 音乐粉丝互动 |
| 5 | http://arxiv.org/abs/2504.14112v1 | Longitudinal Study on Social and Emotional Use of AI Conversational Agent | 五周149参与者纵向研究，主动使用组AI依恋/共情/娱乐动机显著提升 | AI用于社会情感支持的益处风险及个体差异影响 | AI对话Agent情感使用 |
| 6 | http://arxiv.org/abs/2504.00636v1 | Exploring the Impact of an LLM-Powered Teachable Agent on Learning Gains and Cognitive Load in Music Education | 基于“教学学习” pedagogy，构建 LLM 可教代理辅助音乐理论。 | 降低学生认知负荷，提升音乐理论学习效果。 | 音乐教育场景 |
| 7 | http://arxiv.org/abs/2504.01700v1 | Reasoning LLMs for User-Aware Multimodal Conversational Agents | 整合 CoT 推理与 VLM，动态构建用户画像实现个性化交互。 | 解决社交机器人冷启动问题，提升 elderly 用户参与度。 | 社交机器人与老年关怀 |
| 8 | http://arxiv.org/abs/2504.13897v1 | Show Me How: Benefits and Challenges of Agent-Augmented Counterfactual Explanations for Non-Expert Users | 利用对话智能体增强反事实解释，提供可操作建议。 | 解决非专家用户难以理解并利用 AI 反事实解释的问题。 | 医疗健康建议 |
| 9 | http://arxiv.org/abs/2504.04592v2 | "Trust me on this" Explaining Agent Behavior to a Human Terminator | 形式化人类接管场景，提出可解释性方案优化干预次数。 | 解决人机协作中信任与接管频率权衡优化的问题。 | 自动驾驶/工业自动化 |
| 10 | http://arxiv.org/abs/2504.06374v1 | Comparing Self-Disclosure Themes and Semantics to a Human, a Robot, and a Disembodied Agent | 分析人类对不同具身Agent自我披露的主题与语义一致性 | 探究具身形式是否影响人类与Agent交互的披露内容 | 社交机器人与对话Agent |
| 11 | http://arxiv.org/abs/2504.14779v1 | Exploring Collaborative GenAI Agents in Synchronous Group Settings: Eliciting Team Perceptions and Design Considerations for the Future of Work | 探索协作 GenAI 代理在同步群体设置中增强团队合作 | 当前工具主要为个人设计，忽视团队动态 | 未来工作团队协作 |
| 12 | http://arxiv.org/abs/2505.00018v2 | Position Paper: Towards Open Complex Human-AI Agents Collaboration Systems for Problem Solving and Knowledge Management | 提出技术无关的协作就绪立场，关闭先前阶段差距 | 人机协作系统缺乏统一代理定义与形式化动态 | 人机协作系统 |
| 13 | http://arxiv.org/abs/2506.11009v1 | Human-In-The-Loop Software Development Agents: Challenges and Future Directions | 部署人机回环软件开发智能体，分析单元测试成本与评估变异性挑战。 | 解决多智能体软件开发中计算成本高及 LLM 评估不稳定的问题。 | 软件工程与代码开发 |
| 14 | http://arxiv.org/abs/2504.20903v3 | Modeling AI-Human Collaboration as a Multi-Agent Adaptation | 形式化 AI 优化搜索与人类满意适应的交互，揭示任务架构对协作的影响。 | 解决 AI 与人类协作中任务分解与序列依赖导致的性能衰减问题。 | 组织环境中的 AI 人机协作 |
| 15 | http://arxiv.org/abs/2505.00049v1 | Humanizing LLMs: A Survey of Psychological Measurements with Tools, Datasets, and Human-Agent Applications | 系统综述 LLM 心理特质评估工具、数据集及应用，提出未来框架方向。 | 解决 LLM 心理特质评估方法不一致与工具匹配度低的问题。 | LLM 社会影响与对齐评估 |

[返回目录](#目录)

<a id="cat-12"></a>

## Agent记忆与知识管理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2504.13936v2 | ViMo: A Generative Visual GUI World Model for App Agents | 首个视觉世界模型生成未来App观察图像，符号文本表示 | 现有世界模型仅生成文本描述、缺乏关键视觉细节 | App Agent长程规划 |
| 2 | http://arxiv.org/abs/2504.11243v1 | Towards Automated Safety Requirements Derivation Using Agent-based RAG | Agent-based RAG推导自动驾驶安全需求，检索信息更相关 | 预训练LLM缺乏领域知识、复杂查询RAG性能下降 | 自动驾驶安全分析 |
| 3 | http://arxiv.org/abs/2504.06135v1 | Decentralizing AI Memory: SHIMI, a Semantic Hierarchical Memory Index for Scalable Agent Reasoning | 提出语义分层记忆索引SHIMI，支持去中心化异步同步 | 解决RAG抽象能力差、扩展性不足及语义精度问题 | 去中心化认知系统 |
| 4 | http://arxiv.org/abs/2504.06943v2 | Review of Case-Based Reasoning for LLM Agents: Theoretical Foundations, Architectural Components, and Cognitive Integration | 系统回顾CBR集成到LLM Agent框架，形式化检索适配学习模型 | 解决LLM Agent幻觉及跨交互上下文记忆缺失问题 | 自主LLM Agent增强 |
| 5 | http://arxiv.org/abs/2504.08525v4 | Task Memory Engine (TME): Enhancing State Awareness for Multi-Step LLM Agent Tasks | 任务记忆引擎，分层任务记忆树跟踪执行状态 | 解决多步任务缺乏结构化理解及长程连贯性差问题 | 多步LLM Agent任务 |
| 6 | http://arxiv.org/abs/2504.19413v1 | Mem0: Building Production-Ready AI Agents with Scalable Long-Term Memory | 引入可扩展记忆中心架构，动态提取与检索对话中的显著信息。 | 解决 LLM 固定上下文窗口导致长会话一致性维持困难的问题。 | 长程对话与记忆管理 |

[返回目录](#目录)

<a id="cat-13"></a>

## 多Agent强化学习

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2504.11258v3 | Multi-Agent Reinforcement Learning for Greenhouse Gas Offset Credit Markets | Nash-DQN估计抵消信用市场纳什均衡，验证RL应用于气候金融市场 | 计算纳什均衡是NP难问题、排放企业需优化策略 | 温室气体抵消信用市场 |
| 2 | http://arxiv.org/abs/2504.11569v1 | Multi-Agent Reinforcement Learning for Decentralized Reservoir Management via Murmuration Intelligence | 仿鸟群智能的去中心化MARL框架，实现局部决策全局协调 | 集中式水管理计算复杂、不确定性传播问题 | 水库管理系统 |
| 3 | http://arxiv.org/abs/2504.11874v1 | Factor-MCLS: Multi-agent learning system with reward factor matrix and multi-critic framework for dynamic portfolio optimization | 奖励因子矩阵阐明资产回报风险，多评论家框架支持投资者干预 | DRL Agent难理解组合回报风险因素，投资者无法干预训练 | 动态投资组合优化 |
| 4 | http://arxiv.org/abs/2504.12777v3 | Multi-Agent Reinforcement Learning Simulation for Environmental Policy Synthesis | MARL增强气候模拟直接合成政策路径，非仅评估政策 | 气候政策开发深度不确定性、复杂系统动力学挑战 | 环境政策合成 |
| 5 | http://arxiv.org/abs/2504.12961v5 | QLLM: Do We Really Need a Mixing Network for Credit Assignment in Multi-Agent Reinforcement Learning? | 利用LLM构建无训练信用分配函数，无需额外可学习参数 | 价值分解方法预定义混合网络导致信用归因不精确 | 多Agent强化学习信用分配 |
| 6 | http://arxiv.org/abs/2504.13554v2 | Task Assignment and Exploration Optimization for Low Altitude UAV Rescue via Generative AI Enhanced Multi-agent Reinforcement Learning | HG-MADDPG结合匈牙利算法与GDM多Agent深度确定性策略梯度 | 单UAV计算需求高难持续提供稳定高层服务 | 低空UAV救援任务 |
| 7 | http://arxiv.org/abs/2504.02281v4 | FinRL Contests: Benchmarking Data-driven Financial Reinforcement Learning Agents | 组织 FinRL 竞赛，标准化金融 RL Agent 的任务与环境。 | 解决金融 RL 策略复现难及缺乏标准基准的问题。 | 金融交易与投资组合 |
| 8 | http://arxiv.org/abs/2504.02479v1 | Hierarchical Policy-Gradient Reinforcement Learning for Multi-Agent Shepherding Control of Non-Cohesive Targets | 提出分层策略梯度 RL，解决非凝聚目标的多 Agent 牧羊问题。 | 实现无先验动力学知识的多 Agent 协同控制。 | 多机器人协同控制 |
| 9 | http://arxiv.org/abs/2504.05335v1 | Impact of Price Inflation on Algorithmic Collusion Through Reinforcement Learning Agents | 分析通胀冲击下 RL 定价算法的隐性共谋行为。 | 解决宏观经济因素对算法竞争动态影响不明的问题。 | 市场经济算法监管 |
| 10 | http://arxiv.org/abs/2504.04438v1 | DRAMA: A Dynamic Packet Routing Algorithm using Multi-Agent Reinforcement Learning with Emergent Communication | 提出 DRAMA，结合涌现通信的动态多智能体路由算法。 | 解决现有 RL 路由缺乏运行时通信及动态拓扑适应性的问题。 | 网络数据包路由 |
| 11 | http://arxiv.org/abs/2504.04691v2 | Large-Scale Mixed-Traffic and Intersection Control using Multi-agent Reinforcement Learning | 使用去中心化 MARL 控制大规模混合交通流。 | 解决大规模混合交通网络中信号与机器人车辆协同控制问题。 | 城市交通控制 |
| 12 | http://arxiv.org/abs/2504.04765v1 | Multi-Agent Deep Reinforcement Learning for Multiple Anesthetics Collaborative Control | 提出 VD-MADRL，优化多种麻醉剂的协同控制。 | 解决现有麻醉控制依赖静态模型且缺乏个性化协同的问题。 | 临床麻醉自动控制 |
| 13 | http://arxiv.org/abs/2504.04850v1 | An Efficient Approach for Cooperative Multi-Agent Learning Problems | 提出集中式学习框架，通过顺序抽象解决协调问题。 | 解决集中式方法联合动作空间爆炸导致的可扩展性问题。 | 多智能体协作学习 |
| 14 | http://arxiv.org/abs/2504.05045v4 | Spatiotemporal Attention-Augmented Inverse Reinforcement Learning for Multi-Agent Task Allocation | 提出注意力增强的逆强化学习框架，约束奖励推断。 | 解决多智能体任务分配中非平稳交互及高维协调难题。 | 多智能体任务分配 |
| 15 | http://arxiv.org/abs/2504.06670v1 | Dynamic Residual Safe Reinforcement Learning for Multi-Agent Safety-Critical Scenarios Decision-Making | 动态残差安全RL框架，弱到强安全校正范式校准安全边界 | 解决多智能体安全关键场景平衡安全约束与任务性能难题 | 自动驾驶决策 |
| 16 | http://arxiv.org/abs/2504.07425v1 | Enhancing Player Enjoyment with a Two-Tier DRL and LLM-Based Agent System for Fighting Games | 双层Agent系统，LLM超Agent动态选择DRL对手提升 enjoyment | 解决格斗游戏Agent设计忽略玩家 enjoyment 关键因素问题 | 格斗游戏NPC设计 |
| 17 | http://arxiv.org/abs/2504.07547v1 | Strategic learning for disturbance rejection in multi-agent systems: Nash and Minmax in graphical games | 基于Q函数策略迭代求纳什均衡，开发Actor-Critic RL框架 | 解决离散时间多Agent系统抗干扰最优控制问题 | 合作与非合作图形博弈 |
| 18 | http://arxiv.org/abs/2504.08195v1 | Graph Based Deep Reinforcement Learning Aided by Transformers for Multi-Agent Cooperation | 集成GNN DRL及Transformer机制增强多Agent协调 | 解决部分可观测下协同无人机舰队任务规划挑战 | 灾难响应与环境监测 |
| 19 | http://arxiv.org/abs/2504.08417v1 | Belief States for Cooperative Multi-Agent Reinforcement Learning under Partial Observability | 学习信念状态克服部分可观测挑战，分离信念与RL任务 | 解决部分可观测多Agent环境状态估计及同时学习难题 | 合作多Agent RL |
| 20 | http://arxiv.org/abs/2504.14422v1 | Optimal Lattice Boltzmann Closures through Multi-Agent Reinforcement Learning | 利用多智能体强化学习动态控制局部松弛参数 | 欠分辨率 LBM 模拟不稳定且难以跨尺度泛化 | 流体力学模拟 |
| 21 | http://arxiv.org/abs/2504.14520v1 | Meta-Thinking in LLMs via Multi-Agent Reinforcement Learning: A Survey | 综述多智能体强化学习如何赋能 LLM 元思考能力 | LLM 缺乏内部自我评估机制及可靠性不足 | LLM 元思考与可靠性 |
| 22 | http://arxiv.org/abs/2504.14874v1 | Event triggered optimal formation control for nonlinear multi-agent systems under Denial-of-Service attacks | 基于事件触发的最优编队控制律，利用 Critic NN | 非线性多智能体系统在 DoS 攻击下的编队控制 | 多智能体系统控制 |
| 23 | http://arxiv.org/abs/2504.16129v4 | MARFT: Multi-Agent Reinforcement Fine-Tuning | 提出多智能体强化微调范式，适配 LLM 多智能体系统 | 直接应用 MARL 到 LaMAS 面临挑战 | LLM 多智能体系统优化 |
| 24 | http://arxiv.org/abs/2504.15425v1 | Solving Multi-Agent Safe Optimal Control with Distributed Epigraph Form MARL | 分布式表形形式 MARL 算法，确保训练稳定与安全 | 安全多智能体强化学习算法训练不稳定 | 多机器人系统协作 |
| 25 | http://arxiv.org/abs/2504.17355v1 | Collaborative Multi-Agent Reinforcement Learning for Automated Feature Transformation with Graph-Driven Path Optimization | 提出 TCTO 框架，利用演化交互图驱动路径优化，实现自动化特征工程。 | 解决特征转换步骤间动态依赖被忽略及操作冗余的问题。 | 机器学习特征工程 |
| 26 | http://arxiv.org/abs/2504.17356v2 | Comprehend, Divide, and Conquer: Feature Subspace Exploration via Multi-Agent Hierarchical Reinforcement Learning | 提出 HRLFS，利用 LLM 提取特征语义并构建分层智能体进行子空间探索。 | 解决复杂数据集下单一智能体效率低及特征依赖复杂的问题。 | 机器学习特征选择 |
| 27 | http://arxiv.org/abs/2504.18937v1 | Two-Agent DRL for Power Allocation and IRS Orientation in Dynamic NOMA-based OWC Networks | 设计双智能体 DRL 算法优化功率分配与 IRS 方向，实现集中训练分散执行。 | 解决动态 NOMA-VLC 系统中非凸优化问题及实时求解困难。 | 无线通信资源分配 |
| 28 | http://arxiv.org/abs/2504.21048v1 | Multi-Agent Reinforcement Learning for Resources Allocation Optimization: A Survey | 综述 MARL 在资源分配优化中的算法、分类及 taxonomy，梳理研究 landscape。 | 解决动态分散环境下资源分配优化的算法选择与方向指引问题。 | 工业 4.0 及资源分配领域研究者 |
| 29 | http://arxiv.org/abs/2504.20927v1 | Exploiting inter-agent coupling information for efficient reinforcement learning of cooperative LQR | 利用智能体间耦合信息精确分解局部 Q 函数，提升样本效率。 | 解决合作多智能体控制中 Q 函数分解不精确与样本效率低问题。 | 合作多智能体控制系统 |
| 30 | http://arxiv.org/abs/2504.21278v1 | Robust Multi-agent Communication Based on Decentralization-Oriented Adversarial Training | 训练 adversary 动态屏蔽关键通道，强制通信策略转向去中心化结构。 | 解决多智能体通信策略因通道集中导致的脆弱性与崩溃风险。 | 鲁棒多智能体通信系统 |
| 31 | http://arxiv.org/abs/2505.00055v1 | TinyMA-IEI-PPO: Exploration Incentive-Driven Multi-Agent DRL with Self-Adaptive Pruning for Vehicular Embodied AI Agent Twins Migration | 结合 Stackelberg 博弈与自适应剪枝 DRL，优化车联网智能体 twins 迁移。 | 解决资源受限下车联网智能体 twins 迁移的计算效率与探索问题。 | 车联网具身智能体网络 |

[返回目录](#目录)

<a id="cat-14"></a>

## Agent可解释性与透明度

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2504.05393v1 | Interactive Explanations for Reinforcement-Learning Agents | 提出 ASQ-IT，基于用户查询的交互式 RL 智能体解释系统。 | 解决现有 XRL 方法静态且缺乏用户主动参与沟通的问题。 | 强化学习可解释性 |

[返回目录](#目录)

<a id="cat-15"></a>

## 低代码/无代码Agent平台

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2504.14787v2 | ADL: A Declarative Language for Agent-Based Chatbots | 代理声明语言抽象实现细节，简化聊天机器人设计 | 现有框架耦合 Python 编程，难以维护和优化 | 客服聊天机器人开发 |

[返回目录](#目录)
