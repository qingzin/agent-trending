# AI agents 2025年10月学术分类汇总

共收录 794 篇论文，按研究方向分类整理如下。

## 目录

- [多Agent强化学习（56篇）](#cat-01)
- [Agent学习与自进化（69篇）](#cat-02)
- [基于Agent的应用系统（145篇）](#cat-03)
- [Agent安全与对齐（95篇）](#cat-04)
- [Agent记忆与知识管理（30篇）](#cat-05)
- [Agent评测与基准（71篇）](#cat-06)
- [多Agent协作与通信（79篇）](#cat-07)
- [Agent架构与框架设计（81篇）](#cat-08)
- [人机协作Agent（34篇）](#cat-09)
- [Agent规划与推理（33篇）](#cat-10)
- [Agent仿真与社会模拟（43篇）](#cat-11)
- [Agent可解释性与透明度（2篇）](#cat-12)
- [Agent工具使用与环境交互（31篇）](#cat-13)
- [低代码/无代码Agent平台（2篇）](#cat-14)
- [具身智能Agent（23篇）](#cat-15)

<a id="cat-01"></a>

## 多Agent强化学习

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2510.04678v1 | Multi-Agent Tool-Integrated Policy Optimization | 提出 MATPO 框架，单模型内通过 RL 训练规划者与工作者角色，无需多模型部署 | 解决单智能体上下文受限及工具响应噪声问题，提升多轮工具集成规划性能 | 知识密集型与复杂推理任务 |
| 2 | http://arxiv.org/abs/2510.04862v1 | Video Game Level Design as a Multi-Agent Reinforcement Learning Problem | 将关卡生成框架为多智能体问题，减少奖励计算次数，学习局部模块化设计策略 | 解决单代理 PCGRL 效率瓶颈及泛化到分布外地图形状的能力不足 | 视频游戏程序化内容生成 |
| 3 | http://arxiv.org/abs/2510.04935v2 | MARS: Co-evolving Dual-System Deep Research via Multi-Agent Reinforcement Learning | 引入 MARS 共进化框架，通过 MARL 联合优化双认知系统，共享轨迹奖励 | 解决大推理模型过度消耗 token 及无法访问训练外最新知识的问题 | 知识密集型深度研究任务 |
| 4 | http://arxiv.org/abs/2510.05943v1 | EARL: Efficient Agentic Reinforcement Learning Systems for Large Language Models | 呈现 EARL 系统，设计并行选择器与数据 dispatcher，动态适应模型与训练并行 | 解决 agentic RL 扩展中上下文长度增长导致内存溢出及跨设备数据移动瓶颈 | 大规模 agentic LLM 训练 |
| 5 | http://arxiv.org/abs/2510.00480v2 | Expandable Decision-Making States for Multi-Agent Deep Reinforcement Learning in Soccer Tactical Analysis | EDMS语义增强状态表示+动作掩码，将学习策略映射到可解释战术概念 | 高维耦合状态空间下球员级Agent模型的可解释性和鲁棒性 | 足球战术分析 |
| 6 | http://arxiv.org/abs/2510.00602v3 | Multi-Agent Stage-wise Conservative Linear Bandits | MA-SCLUCB算法交替动作选择和共识构建阶段，满足阶段保守约束 | 多Agent网络中平衡探索利用同时维持安全保证避免灾难性失败 | 推荐系统等安全关键应用 |
| 7 | http://arxiv.org/abs/2510.01132v2 | A Practitioner's Guide to Multi-turn Agentic Reinforcement Learning | 分解环境/奖励/策略三支柱，实证推导多轮Agent RL训练配方 | 现有框架定义碎片化，缺乏系统设计选择跨任务分析 | TextWorld、ALFWorld、SWE-Gym |
| 8 | http://arxiv.org/abs/2510.01586v1 | AdvEvo-MARL: Shaping Internalized Safety through Adversarial Co-Evolution in Multi-Agent Reinforcement Learning | 攻击者-防御者对抗共进化，组级均值回报基线实现低方差更新和组内协调 | 现有防御自验证能力不足或外部守卫增加开销单点故障，安全与效用难兼顾 | 多Agent系统安全防护 |
| 9 | http://arxiv.org/abs/2510.03823v1 | Distributed Area Coverage with High Altitude Balloons Using Multi-Agent Reinforcement Learning | 首次将 MARL 应用于高空气球协调，扩展 RLHAB 环境支持多智能体协作 | 解决小型团队和局部任务中确定性协调方法性能差的问题 | 高空气球分布式区域覆盖 |
| 10 | http://arxiv.org/abs/2510.06214v1 | Stratified GRPO: Handling Structural Heterogeneity in Reinforcement Learning of LLM Search Agents | 提出分层优势归一化，消除异构轨迹间的跨层偏差 | 解决搜索智能体轨迹结构异构导致的信用分配失真问题 | LLM 搜索智能体训练 |
| 11 | http://arxiv.org/abs/2510.07363v2 | L2M-AID: Autonomous Cyber-Physical Defense by Fusing Semantic Reasoning of Large Language Models with Multi-Agent Reinforcement Learning | 融合 LLM 语义推理与 MARL，翻译遥测为上下文状态表示 | 解决传统防御缺乏上下文意识及难以维持物理过程稳定问题 | 工业物联网防御 |
| 12 | http://arxiv.org/abs/2510.07888v1 | Network Topology and Information Efficiency of Multi-Agent Systems: Study based on MARL | 证明定向顺序拓扑提升性能，提出信息熵效率指标 | 解决多智能体系统中通信结构优化及信息效率评估问题 | 多智能体强化学习 |
| 13 | http://arxiv.org/abs/2510.07971v1 | Climate Surrogates for Scalable Multi-Agent Reinforcement Learning: A Case Study with CICERO-SCM | 集成高效气候代理模型至环境循环，加速 MARL 训练 | 解决气候政策模型计算昂贵难以嵌入强化学习的问题 | 气候政策模拟 |
| 14 | http://arxiv.org/abs/2510.08159v1 | Quantum Agents for Algorithmic Discovery | 训练量子代理自主重发现量子算法，无需 prior 访问最优解 | 解决量子算法设计依赖人工及自动化发现潜力未开发问题 | 量子算法发现 |
| 15 | http://arxiv.org/abs/2510.08255v1 | Opponent Shaping in LLM Agents | 首次调查 LLM 代理中的对手塑造，提出 ShapeLLM 适配方法 | 解决 LLM 代理在多 agent 互动中战略行为理解缺失问题 | 博弈论环境 |
| 16 | http://arxiv.org/abs/2510.09156v1 | Agentic-KGR: Co-evolutionary Knowledge Graph Construction through Multi-Agent Reinforcement Learning | 通过多轮强化学习实现 LLM 与知识图谱的协同进化 | 解决静态知识库覆盖缺口与时效性过时问题 | 动态信息环境 |
| 17 | http://arxiv.org/abs/2510.11736v1 | AI Agents for the Dhumbal Card Game: A Comparative Study | 系统比较规则、搜索与学习策略在不完美信息卡牌游戏中的表现 | 解决文化性卡牌游戏 AI 策略缺乏系统评估的问题 | 游戏 AI |
| 18 | http://arxiv.org/abs/2510.09469v2 | Towards Information-Optimized Multi-Agent Path Finding: A Hybrid Framework with Reduced Inter-Agent Information Sharing | 混合框架结合去中心化规划与轻量中心化协调，减少信息共享 | 解决大规模多智能体路径查找中信息过载与隐私问题 | 机器人与自主系统 |
| 19 | http://arxiv.org/abs/2510.09937v1 | Structured Cooperative Multi-Agent Reinforcement Learning: a Bayesian Network Perspective | 基于贝叶斯网络建模耦合，提出部分去中心化训练范式 | 解决现有 MARL 算法未充分利用智能体间耦合信息问题 | 大规模多智能体系统 |
| 20 | http://arxiv.org/abs/2510.10633v1 | Collaborative Text-to-Image Generation via Multi-Agent Reinforcement Learning and Semantic Fusion | 多智能体强化学习协调领域专用代理生成图像 | 解决文本到图像生成中语义对齐与细节缺失问题 | 多模态文本到图像生成 |
| 21 | http://arxiv.org/abs/2510.11062v5 | Stronger-MAS: Multi-Agent Reinforcement Learning for Collaborative LLMs | 提出 AT-GRPO 算法支持多智能体工作流 on-policy 更新 | 解决标准 GRPO 在多智能体角色提示下失效问题 | 协作式 LLM 系统 |
| 22 | http://arxiv.org/abs/2510.11410v2 | Autonomous vehicles need social awareness to find optima in multi-agent reinforcement learning routing games | 引入边际成本内在奖励信号提升社会意识 | 解决自私 AV 学习导致交通系统 destabilize 问题 | 自动驾驶路由博弈 |
| 23 | http://arxiv.org/abs/2510.11474v2 | Coordinated Strategies in Realistic Air Combat by Hierarchical Multi-Agent Reinforcement Learning | 分层多智能体强化学习结合课程学习与联盟博弈 | 解决真实空战模拟中态势感知 imperfect 问题 | 真实空战模拟 |
| 24 | http://arxiv.org/abs/2510.11535v1 | A Flexible Multi-Agent Deep Reinforcement Learning Framework for Dynamic Routing and Scheduling of Latency-Critical Services | 集中路由分布调度架构最大化按时包交付 | 解决现有方案无法提供严格 E2E 峰值延迟保证问题 | 延迟关键服务网络 |
| 25 | http://arxiv.org/abs/2510.15414v3 | MARSHAL: Incentivizing Multi-Agent Reasoning via Self-Play with Strategic LLMs | 回合级优势估计器与智能体特定优势归一化，支持自博弈训练 | 多Agent场景中长程信用分配与智能体优势估计困难 | 协作与竞争博弈中的多Agent系统 |
| 26 | http://arxiv.org/abs/2510.16761v1 | Enhancing Language Agent Strategic Reasoning through Self-Play in Adversarial Games | 步级策略优化方法SCO-PAL，发现自博弈是提升对抗环境战略推理最有效方式 | 语言Agent在动态对抗游戏中因战略推理差而遇到困难 | 对抗性游戏中的语言Agent |
| 27 | http://arxiv.org/abs/2510.11824v2 | Empirical Study on Robustness and Resilience in Cooperative Multi-Agent Reinforcement Learning | 大规模实证研究评估 MARL 中的合作、鲁棒性和弹性。 | 合作策略在现实不确定性下往往无法保持鲁棒性。 | 合作多智能体强化学习 |
| 28 | http://arxiv.org/abs/2510.12272v2 | Heterogeneous RBCs via Deep Multi-Agent Reinforcement Learning | 框架整合深度 MARL 与真实商业周期模型。 | 传统经济模型计算繁琐或需要明确行为规则。 | 宏观经济建模 |
| 29 | http://arxiv.org/abs/2510.18886v1 | Emergence of Internal State-Modulated Swarming in Multi-Agent Patch Foraging System | 通过进化策略算法验证觅食者中群集行为的出现。 | 理解非合作觅食者中群集行为的出现。 | 多代理补丁觅食系统 |
| 30 | http://arxiv.org/abs/2510.12555v1 | Inclusive Fitness as a Key Step Towards More Advanced Social Behaviors in Multi-Agent Reinforcement Learning Settings | MARL 框架中奖励函数建模为包容性 fitness 概念。 | MARL 设置中需要超越二元团队结构的更高级社会行为。 | 多智能体强化学习 |
| 31 | http://arxiv.org/abs/2510.13343v1 | AOAD-MAT: Transformer-based multi-agent deep reinforcement learning model considering agents' order of action decisions | 新型 MAT 模型明确将动作决策序列纳入学习过程。 | 现有 MARL 模型未明确考虑代理决策顺序的重要性。 | 多智能体强化学习 |
| 32 | http://arxiv.org/abs/2510.14112v2 | STEMS: Spatial-Temporal Enhanced Safe Multi-Agent Coordination for Building Energy Management | 提出时空增强安全多智能体协调框架，结合 GCN-Transformer 和控制屏障函数 | 解决多建筑能源管理中时空依赖利用不足和安全保障缺失 | 建筑能源管理系统 |
| 33 | http://arxiv.org/abs/2510.20176v2 | Mixture-of-Minds: Multi-Agent Reinforcement Learning for Table Understanding | 规划/编码/回答三角色+MCTS强化学习 | 表格理解中算术错误和幻觉问题 | 表格数据推理任务 |
| 34 | http://arxiv.org/abs/2510.20218v1 | High-order Interactions Modeling for Interpretable Multi-Agent Q-Learning | 连分数Q学习+变分信息瓶颈提取潜在信息 | 高阶交互建模组合爆炸和黑箱不透明 | 多Agent协作系统 |
| 35 | http://arxiv.org/abs/2510.20408v1 | Balancing Specialization and Centralization: A Multi-Agent Reinforcement Learning Benchmark for Sequential Industrial Control | 行业启发基准+模块化vs单体架构对比 | 工业控制中RL奖励设计和动作空间管理困难 | 顺序工业控制流程 |
| 36 | http://arxiv.org/abs/2510.20436v1 | Learning Decentralized Routing Policies via Graph Attention-based Multi-Agent Reinforcement Learning in Lunar Delay-Tolerant Networks | 图注意力多Agent强化学习+集中训练分散执行 | 月球网络间歇连接下多机器人数据中继 | 太空机器人探索任务 |
| 37 | http://arxiv.org/abs/2510.17697v4 | A Principle of Targeted Intervention for Multi-Agent Reinforcement Learning | 利用 MAID 分析交互范式，提出 targeted intervention 范式及 PSI 技术。 | 解决大规模 MARL 中全局指导不切实际及缺乏易用研究工具的问题。 | 多智能体强化学习 |
| 38 | http://arxiv.org/abs/2510.18085v1 | R2BC: Multi-Agent Imitation Learning from Single-Agent Demonstrations | 轮流行为克隆，单人操作者依次 teleoperate 智能体训练多机器人系统。 | 解决单人难以提供联合多智能体动作空间演示的训练挑战。 | 多机器人系统训练 |
| 39 | http://arxiv.org/abs/2510.22471v1 | Learning Local Stackelberg Equilibria from Repeated Interactions with a Learning Agent | 提出局部Stackelberg均衡PTAS算法 | 全局Stackelberg值计算指数级复杂度 | 主-Agent重复博弈场景 |
| 40 | http://arxiv.org/abs/2510.22811v1 | Distributed Multi-Agent Bandits Over Erdős-Rényi Random Networks | 分布式算法整合臂消除与随机gossip， regret上界O(log T) | 随机通信图下异构奖励多Agent bandit问题 | 分布式多Agent决策系统 |
| 41 | http://arxiv.org/abs/2510.22969v2 | Multi-Agent Conditional Diffusion Model with Mean Field Communication as Wireless Resource Allocation Planner | MA-CDMP扩散模型+平均场通信，DTDE范式 | 大规模无线网络高维随机动态与协作挑战 | 无线通信资源分配 |
| 42 | http://arxiv.org/abs/2510.23053v2 | AirFed: A Federated Graph-Enhanced Multi-Agent Reinforcement Learning Framework for Multi-UAV Cooperative Mobile Edge Computing | 双层动态GAT+声誉去中心化联邦学习 | 多UAV-MEC系统可扩展性差、知识共享低效 | 多UAV协作移动边缘计算 |
| 43 | http://arxiv.org/abs/2511.00034v1 | On the Fundamental Limitations of Decentralized Learnable Reward Shaping in Cooperative Multi-Agent Reinforcement Learning | 揭示分散式奖励学习根本局限，需集中协调 | 分散式奖励塑造在协作多Agent中效果差 | 协作多Agent强化学习 |
| 44 | http://arxiv.org/abs/2510.23535v1 | Sequential Multi-Agent Dynamic Algorithm Configuration | Seq-MADAC框架考虑参数间固有依赖关系 | 现有方法忽略多参数间依赖导致次优 | 多目标优化算法配置 |
| 45 | http://arxiv.org/abs/2510.20009v2 | IMAS$^2$: Joint Agent Selection and Information-Theoretic Coordinated Perception In Dec-POMDPs | 两层优化结构，联合选择传感智能体与合成去中心化感知策略 | 解决 Dec-POMDP 中联合传感选择与策略合成难题 | 多智能体 cooperative 感知 |
| 46 | http://arxiv.org/abs/2510.24803v2 | MASPRM: Multi-Agent System Process Reward Model | 为部分智能体间转录分配价值，引导推理时搜索与计算支出。 | 解决多智能体系统测试时性能与计算效率平衡问题。 | 多智能体推理与搜索任务 |
| 47 | http://arxiv.org/abs/2510.24126v1 | Reinforcement Learning for Long-Horizon Multi-Turn Search Agents | 证明 RL 可通过经验学习显著提升多轮搜索智能体能力。 | 解决提示方法在长程多轮任务中能力受限问题。 | 法律文档搜索与多轮任务 |
| 48 | http://arxiv.org/abs/2510.26270v1 | Graph-Enhanced Policy Optimization in LLM Agent Training | 动态构建状态转移图，利用图论中心性提供三种协同学习信号 | LLM Agent训练中的结构性盲区、探索低效、信用分配不精准 | 多轮交互式LLM Agent训练 |
| 49 | http://arxiv.org/abs/2510.26389v2 | Adaptive Context Length Optimization with Low-Frequency Truncation for Multi-Agent Reinforcement Learning | 中央Agent动态优化上下文长度，傅里叶低频截断过滤冗余信息 | 固定大上下文长度导致探索效率低和信息冗余 | 长程依赖MARL任务 |
| 50 | http://arxiv.org/abs/2510.27130v1 | LC-Opt: Benchmarking Reinforcement Learning and Agentic AI for End-to-End Liquid Cooling Optimization in Data Centers | 高保真数字孪生基准环境，支持集中/分散多Agent RL方法 | 高密度数据中心液冷热管理能耗效率 | 数据中心液冷优化控制 |
| 51 | http://arxiv.org/abs/2510.27289v1 | A Digital Twin-based Multi-Agent Reinforcement Learning Framework for Vehicle-to-Grid Coordination | DT-MADDPG算法，协作数字孪生增强集中式评论器 | 大规模去中心化系统协调中隐私保护 | 车网协调（V2G网络） |
| 52 | http://arxiv.org/abs/2510.27659v1 | Challenges in Credit Assignment for Multi-Agent Reinforcement Learning in Open Agent Systems | 概念与实证综述开放系统中开放性与信用分配问题交互 | 传统信用分配方法假设静态Agent群体不适用于开放系统 | 开放多Agent强化学习系统 |
| 53 | http://arxiv.org/abs/2510.25095v1 | Socio-cognitive agent-oriented evolutionary algorithm with trust-based optimization | 基于信任的 Agent 交互机制替代传统迁移，优化演化算法 | 传统岛模型演化算法灵活性不足的问题 | 复杂优化问题求解 |
| 54 | http://arxiv.org/abs/2510.25340v1 | Multi-party Agent Relation Sampling for Multi-party Ad Hoc Teamwork | 构建稀疏骨架图捕捉跨组动态，解决 Ad Hoc 协作 | 多团队互不熟悉导致协作困难的问题 | 多党派临时团队协作 |
| 55 | http://arxiv.org/abs/2510.25929v1 | Multi-Agent Reinforcement Learning for Market Making: Competition without Collusion | 分层 MARL 框架研究做市中的算法共谋 | 不同 AI Agent 交互是否导致市场共谋的问题 | 算法交易与市场做市 |
| 56 | http://arxiv.org/abs/2510.26089v1 | Network-Constrained Policy Optimization for Adaptive Multi-agent Vehicle Routing | 分层 Hub 自适应导航，集中训练分散执行 | 动态多车设置中 shortest path 加剧拥堵的问题 | 智能交通车辆路由 |

[返回目录](#目录)

<a id="cat-02"></a>

## Agent学习与自进化

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2510.04695v1 | Beyond Outcome Reward: Decoupling Search and Answering Improves LLM Agents | 引入 DeSA 两阶段训练框架，显式分离搜索优化与答案生成，使用检索召回奖励 | 解决仅靠结果奖励导致的搜索行为缺陷，如工具调用失败或冗余搜索 | 搜索增强型 LLM 智能体 |
| 2 | http://arxiv.org/abs/2510.05571v2 | Presenting a Paper is an Art: Self-Improvement Aesthetic Agents for Academic Presentations | 引入 EvoPresent 框架，统一连贯叙事、美学感知设计与虚拟角色交付，自我改进 | 解决现有自动化方法故事讲述有限、美学质量不足及自调整受限的问题 | 学术论文推广与展示 |
| 3 | http://arxiv.org/abs/2510.05596v1 | From Agentification to Self-Evolving Agentic AI for Wireless Networks: Concepts, Approaches, and Future Research Directions | 提出多代理协作自进化框架，分配角色专用提示，自主执行整个生命周期 | 解决静态 AI 模型无法适应环境动态，需人工干预的问题 | 下一代无线智能网络 |
| 4 | http://arxiv.org/abs/2510.00482v1 | Agent Fine-tuning through Distillation for Domain-specific LLMs in Microdomains | 领域手册+蒸馏推理轨迹微调，含RAG和上下文答案提取器 | 通用Agent微调在专业技术微领域有效性不明问题 | Hitachi JP1中间件IT运维 |
| 5 | http://arxiv.org/abs/2510.00967v1 | QUASAR: Quantum Assembly Code Generation Using Tool-Augmented LLMs via Agentic RL | 量子电路验证+外部模拟器+分层奖励机制的Agent RL框架 | 参数量子门需精确数值，LLM缺乏量子领域知识生成低质量电路 | 量子电路生成和优化 |
| 6 | http://arxiv.org/abs/2510.01304v3 | Agentic Jigsaw Interaction Learning for Enhancing Visual Perception and Reasoning in Vision-Language Models | AGILE将拼图求解公式化为交互过程，模型生成代码执行动作获细粒度视觉反馈 | VLM基础感知和推理能力有限，高质量视觉语言数据稀缺可扩展性受限 | 9个通用视觉任务 |
| 7 | http://arxiv.org/abs/2510.04076v1 | From Shadow to Light: Toward Safe and Efficient Policy Learning Across MPC, DeePC, RL, and LLM Agents | 展示八种方法降低数据驱动策略计算复杂度，实现安全高效运动控制 | 解决数据驱动策略响应慢、计算需求高及内存受限问题 | 机器人与车辆运动控制 |
| 8 | http://arxiv.org/abs/2510.04096v1 | RLRF: Competitive Search Agent Design via Reinforcement Learning from Ranker Feedback | 提出 RLRF 框架，利用排名反馈训练 LLM 代理优化竞争性内容 | 解决发布者在竞争性搜索中利用 LLM 修改内容以提升排名的策略问题 | 搜索引擎优化与竞争性内容生成 |
| 9 | http://arxiv.org/abs/2510.04206v1 | AgentRL: Scaling Agentic Reinforcement Learning with a Multi-Turn, Multi-Task Framework | 提出 AgentRL 框架，支持异步生成训练及多任务 RL 稳定算法 | 解决多轮多任务设置下 LLM 代理 RL 训练缺乏可扩展基础设施的问题 | 通用智能体在线交互学习 |
| 10 | http://arxiv.org/abs/2510.04399v2 | On The Statistical Limits of Self-Improving Agents | 形式化自改进代理的五轴分解，识别效用学习与统计前提的结构冲突 | 解决自修改系统中效用驱动变化可能侵蚀可靠学习统计前提的问题 | 超智能系统自修改安全性边界 |
| 11 | http://arxiv.org/abs/2510.04560v1 | ContextNav: Towards Agentic Multimodal In-Context Learning | 提出 ContextNav，整合自动检索与人工策展，实现噪声鲁棒上下文化 | 解决多模态 ICL 中可扩展性与鲁棒性难以兼顾及上下文噪声问题 | 多模态大模型上下文学习 |
| 12 | http://arxiv.org/abs/2510.07794v1 | HiPRAG: Hierarchical Process Rewards for Efficient Agentic Retrieval Augmented Generation | 引入分层过程奖励机制，优化代理搜索决策效率 | 解决 Agentic RAG 中过度搜索及搜索不足导致的低效问题 | 检索增强生成系统 |
| 13 | http://arxiv.org/abs/2510.07841v1 | Self-Improving LLM Agents at Test-Time | 提出测试时自我改进方法，利用不确定样本生成训练数据 | 解决训练数据收集低效及模型泛化能力不足的问题 | 通用智能体系统 |
| 14 | http://arxiv.org/abs/2510.08002v1 | Learning on the Job: An Experience-Driven Self-Evolving Agent for Long-Horizon Tasks | 提出经验驱动自进化系统，通过层级记忆模块积累结构化经验 | 解决长程任务中代理无法从经验学习及持续改进的问题 | 长程生产力任务 |
| 15 | http://arxiv.org/abs/2510.08529v2 | CoMAS: Co-Evolving Multi-Agent Systems via Interaction Rewards | 从丰富讨论动态生成内在奖励，实现无外部监督自进化 | 解决现有 RL 方法偏离人类通过协作互学自进化机制问题 | 多智能体系统 |
| 16 | http://arxiv.org/abs/2510.08558v2 | Agent Learning via Early Experience | 提出早期经验范式，利用 agent 自身动作生成状态作为监督 | 解决经验数据 RL 训练难及专家演示泛化差的问题 | 通用语言代理 |
| 17 | http://arxiv.org/abs/2510.09255v4 | DSPO: Stable and Efficient Policy Optimization for Agentic Search and Reasoning | 提出动态过滤序列级策略优化，纯 RL 训练搜索与推理交错 | 解决复杂交互任务中 RL 性能天花板与训练崩溃问题 | 复杂问答与推理 |
| 18 | http://arxiv.org/abs/2510.09577v1 | Dyna-Mind: Learning to Simulate from Experience for Better AI Agents | 两阶段训练框架，教智能体在推理中整合替代未来模拟 | 解决长视野交互任务中缺乏试错模拟能力的问题 | 复杂交互环境 |
| 19 | http://arxiv.org/abs/2510.17845v1 | MAT-Agent: Adaptive Multi-Agent Training Optimization | 多智能体框架动态调整增强、优化器等，平衡探索与利用 | 解决多标签图像分类中静态配置难以适应动态景观问题 | 视觉模型训练 |
| 20 | http://arxiv.org/abs/2510.10197v2 | Don't Just Fine-tune the Agent, Tune the Environment | 环境调整范式，通过课程与反馈直接从未标记问题实例学习 | 解决高质量训练数据稀缺及 SFT 过拟合问题 | 复杂工具使用任务 |
| 21 | http://arxiv.org/abs/2510.10304v2 | Sample-Efficient Online Learning in LM Agents via Hindsight Trajectory Rewriting | 适配事后经验回放，从失败交互中生成合成正例 | 解决新环境中语言模型智能体样本效率低的问题 | 顺序交互学习 |
| 22 | http://arxiv.org/abs/2510.12831v2 | MTSQL-R1: Towards Long-Horizon Multi-Turn Text-to-SQL via Agentic Training | 将任务铸造成 MDP，迭代执行验证 refine 循环 | 解决多轮 Text-to-SQL 连贯性与可执行性问题 | 多轮对话语义解析 |
| 23 | http://arxiv.org/abs/2510.11345v1 | Part II: ROLL Flash -- Accelerating RLVR and Agentic Training with Asynchrony | 原生支持异步 RL 后训练，细粒度并行与解耦 | 解决同步 RL 后训练资源利用率低与扩展性差问题 | RLVR 与 Agent 训练 |
| 24 | http://arxiv.org/abs/2510.11498v1 | ReLook: Vision-Grounded RL with a Multimodal LLM Critic for Agentic Web Coding | 多模态 LLM 批评者视觉 grounded RL 闭环 | 解决前端开发 correctness  judged on rendered pixels 问题 | 视觉 grounded 前端代码 |
| 25 | http://arxiv.org/abs/2510.16079v1 | EvolveR: Self-Evolving LLM Agents through an Experience-Driven Lifecycle | 离线自蒸馏与在线交互闭环，策略强化机制迭代更新Agent | Agent缺乏从自身经验中系统学习和问题解决策略迭代优化能力 | 复杂多跳问答任务 |
| 26 | http://arxiv.org/abs/2510.15831v1 | VISTA: A Test-Time Self-Improving Video Generation Agent | 三Agent批评视觉/音频/上下文保真度，推理Agent综合反馈重写提示 | 生成视频质量严重依赖精确用户提示，测试时优化方法难以处理多面性 | 文本到视频生成系统 |
| 27 | http://arxiv.org/abs/2510.15862v4 | Rethinking the Design of Reinforcement Learning-Based Deep Research Agents | AI反馈替代规则奖励、on-policy RLOO算法、过滤低质量样本、容错测试时展开 | 深度研究Agent关键设计选择影响未充分探索 | 基于RL的深度研究Agent |
| 28 | http://arxiv.org/abs/2510.16907v1 | VAGEN: Reinforcing World Model Reasoning for Multi-Turn VLM Agents | 世界建模奖励提供密集回合级监督，双层次广义优势估计实现回合感知信用分配 | VLM Agent训练从文本状态到复杂视觉观察转换引入部分可观察性 | 多轮VLM Agent视觉环境 |
| 29 | http://arxiv.org/abs/2510.11701v1 | Demystifying Reinforcement Learning in Agentic Reasoning | 从数据、算法和推理模式三方面系统调查代理强化学习。 | 代理强化学习的关键设计原则和最佳实践尚不明确。 | LLM 代理推理能力 |
| 30 | http://arxiv.org/abs/2510.12218v1 | GOAT: A Training Framework for Goal-Oriented Agent with Tools | 训练框架在无人类标注设置下微调 LLM 代理。 | 当前 LLM 代理处理需要工具使用的目标导向查询能力有限。 | 目标导向 LLM 代理 |
| 31 | http://arxiv.org/abs/2510.13913v1 | Synthesizing Agentic Data for Web Agents with Progressive Difficulty Enhancement Mechanisms | 双管数据合成管道通过 progressively 增加任务复杂性生成 QA 对。 | 底层语言模型通常未针对长程推理和探索优化。 | 基于 Web 的深度研究代理 |
| 32 | http://arxiv.org/abs/2510.13220v1 | EvoTest: Evolutionary Test-Time Learning for Self-Improving Agentic Systems | 进化测试时学习框架，无需微调或梯度即可改进代理。 | 当前 AI 代理无法在测试时即时学习复杂技能。 | 自改进代理系统 |
| 33 | http://arxiv.org/abs/2510.13704v1 | Simplicial Embeddings Improve Sample Efficiency in Actor-Critic Agents | 提出单纯嵌入层，约束嵌入为单纯结构以提升样本效率 | 解决深度强化学习智能体泛化性和样本效率低的问题 | 深度强化学习智能体 |
| 34 | http://arxiv.org/abs/2510.14150v4 | CodeEvolve: an open source evolutionary coding agent for algorithmic discovery and optimization | 结合 LLM 与进化搜索，通过执行反馈引导算法合成与优化 | 解决算法发现中人工设计 heuristic 效率低和成本高的问题 | 算法发现与优化 |
| 35 | http://arxiv.org/abs/2510.14253v2 | Towards Agentic Self-Learning LLMs in Search Environment | 提出 Agentic Self-Learning 框架，利用生成奖励模型闭环自学习 | 解决智能体训练依赖人类 curated 数据和预定义规则奖励问题 | 搜索环境智能体 |
| 36 | http://arxiv.org/abs/2510.14319v2 | Metacognitive Self-Correction for Multi-Agent System via Prototype-Guided Next-Execution Reconstruction | 提出 MASC 框架，通过 next-execution reconstruction 实现步级错误检测 | 解决多智能体系统中单步错误传播导致轨迹 disrupted 问题 | 多智能体系统 |
| 37 | http://arxiv.org/abs/2510.14438v1 | Explore to Evolve: Scaling Evolved Aggregation Logic via Proactive Online Exploration for Deep Research Agents | 提出 Explore to Evolve 范式，通过主动在线探索构建可验证训练数据 | 解决深度研究智能体信息聚合能力弱和缺乏 verifiable 训练数据 | 深度研究智能体 |
| 38 | http://arxiv.org/abs/2510.14545v1 | Agentic Entropy-Balanced Policy Optimization | 提出熵平衡策略优化算法，平衡 rollout 和策略更新阶段的熵 | 解决 agentic RL 中过度依赖熵信号导致训练 collapse 问题 | Web 智能体训练 |
| 39 | http://arxiv.org/abs/2510.14548v1 | LLM Agents Beyond Utility: An Open-Ended Perspective | 增强 pretrained LLM 智能体生成任务、积累知识和环境交互能力 | 研究 pretrained LLM 向 open-ended 智能体适应的潜力和 limits | 开放-ended 智能体 |
| 40 | http://arxiv.org/abs/2510.14900v1 | Mapping Smarter, Not Harder: A Test-Time Reinforcement Learning Agent That Improves Without Labels or Model Updates | 提出 test-time RL 智能体，通过 web 搜索收集证据迭代 refine 映射 | 解决测试时 vendor 文档缺失导致 schema 映射挑战和低准确率 | 企业情报平台 |
| 41 | http://arxiv.org/abs/2510.14967v1 | Information Gain-based Policy Optimization: A Simple and Effective Approach for Multi-Turn LLM Agents | 提出 IGPO 框架，将交互 turn 建模为信息获取过程提供 dense 奖励 | 解决多轮智能体训练中 outcome-based 奖励稀疏和 credit assignment 难 | 多轮 LLM 智能体 |
| 42 | http://arxiv.org/abs/2510.14969v1 | LLMs as Scalable, General-Purpose Simulators For Evolving Digital Agent Training | 引入 UI-Simulator 范式，生成结构化 UI 状态和 transition 合成训练轨迹 | 解决数字智能体训练缺乏 diverse 大规模 UI 轨迹和收集成本高 | 数字智能体训练 |
| 43 | http://arxiv.org/abs/2510.15047v1 | Internalizing World Models via Self-Play Finetuning for Agentic RL | 提出 SPA 框架，通过 Self-Play SFT 学习世界模型以初始化策略 | 解决 LLM 智能体在 OOD 场景下 vanilla RL 训练失败和泛化差问题 | Agentic RL |
| 44 | http://arxiv.org/abs/2510.21306v1 | PARL: Prompt-based Agents for Reinforcement Learning | 提示编码动作/状态/奖励无需微调 | LLM作为RL Agent评估研究有限 | 结构化非语言RL任务 |
| 45 | http://arxiv.org/abs/2510.21614v3 | Huxley-Gödel Machine: Human-Level Coding Agent Development by an Approximation of the Optimal Self-Improving Machine | CMP指标估计+HGM搜索自修改树 | 自改进潜力与编码基准性能不匹配 | 自进化编码Agent |
| 46 | http://arxiv.org/abs/2510.21704v2 | Automated Detection of Visual Attribute Reliance with a Self-Reflective Agent | 自反思Agent迭代生成测试视觉属性假设 | 视觉模型依赖特定特征难以自动检测 | 视觉模型鲁棒性分析 |
| 47 | http://arxiv.org/abs/2510.17995v1 | FABRIC: Framework for Agent-Based Realistic Intelligence Creation | 统一框架仅用 LLM 合成 agentic 数据，模块化流水线生成交互记录。 | 解决从人类标注收集 agentic 数据成本高、耗时且难以扩展的问题。 | 智能体训练数据合成 |
| 48 | http://arxiv.org/abs/2510.22052v1 | Energy-Efficient Domain-Specific Artificial Intelligence Models and Agents: Pathways and Paradigms | 提出轻量化领域特定多模态Agent演进范式 | 大模型能耗高、易幻觉，无法部署关键领域 | 动态环境中的实时决策Agent |
| 49 | http://arxiv.org/abs/2510.22075v1 | Agentic Reinforcement Learning for Real-World Code Repair | 构建可验证流水线，SFT+RL提升代码修复Agent性能 | 真实仓库中构建复杂、评估不稳定 | 真实代码仓库的自动修复 |
| 50 | http://arxiv.org/abs/2510.22775v1 | Scalable Supervising Software Agents with Patch Reasoner | R4P补丁验证模型，推理替代测试提供可扩展奖励 | 基于测试的监督不可扩展，高覆盖率测试数据稀缺 | 软件工程Agent训练与测试 |
| 51 | http://arxiv.org/abs/2510.22832v1 | HRM-Agent: Training a recurrent reasoning model in dynamic environments using reinforcement learning | HRM变体仅用RL训练，可复用先前时间步计算 | HRM无法处理动态/不确定/部分可观测环境 | 动态不确定环境中的导航任务 |
| 52 | http://arxiv.org/abs/2510.22833v1 | Toward Agents That Reason About Their Computation | 让Agent感知计算成本并控制何时使用计算 | Agent随改进未变得更计算高效 | Arcade学习环境中的游戏任务 |
| 53 | http://arxiv.org/abs/2510.23038v2 | Incentivizing Agentic Reasoning in LLM Judges via Tool-Integrated Reinforcement Learning | TIR-Judge框架集成代码执行器，迭代RL自进化 | LLM Judge仅靠文本推理，无法验证复杂约束 | LLM响应质量评估 |
| 54 | http://arxiv.org/abs/2510.23272v1 | Code Aesthetics with Agentic Reward Feedback | 多Agent评估可执行性/静态/交互美学，GRPO-AR联合优化 | LLM生成代码视觉导向任务美学质量差 | 代码美学优化(PandasPlotBench等) |
| 55 | http://arxiv.org/abs/2510.18798v1 | WebSeer: Training Deeper Search Agents through Reinforcement Learning with Self-Reflection | 通过自反思机制增强强化学习，生成更长更深度的工具使用轨迹 | 解决搜索智能体工具使用深度浅及错误累积问题 | Web 搜索与信息检索 |
| 56 | http://arxiv.org/abs/2510.18821v2 | Search Self-play: Pushing the Frontier of Agent Capability without Supervision | 提出搜索自博弈框架，智能体同时扮演任务提出者与解决者 | 解决强化学习依赖人工标注数据难以扩展的问题 | 深度搜索智能体训练 |
| 57 | http://arxiv.org/abs/2510.19336v1 | DaMo: Data Mixing Optimizer in Fine-tuning Multimodal LLMs for Mobile Phone Agents | 预测最优数据混合比例，提升多任务微调性能 | 解决多任务学习中训练数据 composition 难以确定的问题 | 手机端多模态智能体 |
| 58 | http://arxiv.org/abs/2510.19361v3 | AgenticMath: Enhancing LLM Reasoning via Agentic-based Math Data Generation | 四阶段智能体方法生成高质量数学问答对，提升推理能力 | 解决现有方法生成数据质量低且信息 richness 不足的问题 | 数学推理模型微调 |
| 59 | http://arxiv.org/abs/2510.20022v1 | SALT: Step-level Advantage Assignment for Long-horizon Agents via Trajectory Graph | 构建轨迹图量化每步质量，基于结果奖励分配细粒度优势 | 解决长周期任务中稀疏奖励导致训练不稳定与策略次优问题 | 长周期语言智能体 RL |
| 60 | http://arxiv.org/abs/2510.23595v3 | Multi-Agent Evolve: LLM Self-Improve through Co-evolution | 提出三元交互智能体框架，通过强化学习实现无监督自我进化。 | 解决依赖人工 curated 数据限制扩展性的问题。 | 数学推理与通用知识问答 |
| 61 | http://arxiv.org/abs/2510.23601v1 | Alita-G: Self-Evolving Generative Agent for Agent Generation | 通过生成、抽象和 curated MCP 工具，将通用智能体转化为领域专家。 | 解决通用智能体在特定领域能力不足与效率低问题。 | 复杂推理任务与领域专家系统 |
| 62 | http://arxiv.org/abs/2510.24636v2 | OpenReward: Learning to Reward Long-form Agentic Tasks via Reinforcement Learning | 引入工具增强长程奖励模型，通过外部工具收集证据判断响应。 | 解决现有奖励模型在知识密集型长程任务评估困难问题。 | 长程代理任务对齐与评估 |
| 63 | http://arxiv.org/abs/2510.24694v2 | Repurposing Synthetic Data for Fine-grained Search Agent Supervision | 利用实体信息构建密集奖励函数，从“近 miss"样本中学习。 | 解决稀疏结果奖励丢弃有价值学习信号问题。 | 搜索代理监督与强化学习 |
| 64 | http://arxiv.org/abs/2510.24695v1 | AgentFrontier: Expanding the Capability Frontier of LLM Agents with ZPD-Guided Data Synthesis | 基于最近发展区理论合成数据，训练处于能力前沿的任务。 | 解决训练数据未处于模型能力前沿限制推理提升问题。 | 高级推理与 LLM 代理训练 |
| 65 | http://arxiv.org/abs/2510.26287v1 | Empowering RepoQA-Agent based on Reinforcement Learning Driven by Monte-carlo Tree Search | 基于MCTS的自训练框架，无需模型蒸馏或外部监督 | 代码库问答中工具利用和决策引导困难 | 仓库级软件工程任务 |
| 66 | http://arxiv.org/abs/2510.26575v1 | InfoFlow: Reinforcing Search Agent Via Reward Density Optimization | 子问题分解、失败引导提示、双Agent精炼架构 | 深度搜索中奖励密度低、探索成本高 | 深度搜索Agent |
| 67 | http://arxiv.org/abs/2510.27051v1 | Adaptive Data Flywheel: Applying MAPE Control Loops to AI Agent Improvement | MAPE驱动数据飞轮闭环系统，结构化HITL反馈实现持续学习 | 企业AI Agent需持续适应保持准确性和对齐 | 企业AI助手（NVInfo AI） |
| 68 | http://arxiv.org/abs/2511.05528v1 | SMAGDi: Socratic Multi Agent Interaction Graph Distillation for Efficient High Accuracy Reasoning | 将多 Agent 辩论动态蒸馏为紧凑的苏格拉底式学生模型 | 多 Agent 系统计算成本高、部署难的问题 | 高效高精度推理任务 |
| 69 | http://arxiv.org/abs/2510.26167v2 | ToolRM: Towards Agentic Tool-Use Reward Modeling | 构建高质量 pairwise 偏好数据训练轻量级 Reward Model | 工具学习领域缺乏专用 Reward Model 限制进展 | 通用工具使用场景对齐 |

[返回目录](#目录)

<a id="cat-03"></a>

## 基于Agent的应用系统

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2510.04787v2 | Trade in Minutes! Rationality-Driven Agentic System for Quantitative Financial Trading | 提出 TiMi 理性驱动多智能体系统，架构解耦策略开发与分钟级部署，闭环优化 | 解决交易代理情感偏差及持续推理约束，实现量化交易的机械理性 | 股票与加密货币市场交易 |
| 2 | http://arxiv.org/abs/2510.04791v1 | GUISpector: An MLLM Agent Framework for Automated Verification of Natural Language Requirements in GUI Prototypes | 利用多模态智能体解释自然语言需求，自主规划验证轨迹并提取可操作反馈 | 解决现有 GUI 测试处理现代界面复杂性不足及缺乏可操作反馈的问题 | 软件工程中的 GUI 原型验证 |
| 3 | http://arxiv.org/abs/2510.04969v1 | Bridging Clinical Narratives and ACR Appropriateness Guidelines: A Multi-Agent RAG System for Medical Imaging Decisions | 引入多智能体认知架构，自动化翻译自由文本临床场景为指南依从的成像建议 | 解决非结构化患者叙事映射到结构化标准困难导致的指南利用不足 | 医疗成像决策支持 |
| 4 | http://arxiv.org/abs/2510.05335v1 | Biomedical reasoning in action: Multi-agent System for Auditable Biomedical Evidence Synthesis | 提出 M-Reason 系统，利用模块化代理编排自动化证据检索、评估与合成 | 解决生物医学证据合成效率与一致性问题，提供可审计性与追溯性 | 癌症研究等生物医学领域 |
| 5 | http://arxiv.org/abs/2510.05414v1 | A Lightweight Large Language Model-Based Multi-Agent System for 2D Frame Structural Analysis | 开发基于轻量 LLM 的多智能体系统，自动化 2D 框架有限元建模，分解子任务 | 解决结构工程中有限元建模任务需几何建模、复杂推理及领域知识的问题 | 2D 框架结构分析 |
| 6 | http://arxiv.org/abs/2510.05441v1 | UnitTenX: Generating Tests for Legacy Packages with AI Agents Powered by Formal Verification | 引入 UnitTenX 系统，结合 AI 代理、形式化方法与 LLM 自动化生成单元测试 | 解决复杂遗留代码库测试生成挑战，提升软件可靠性与可维护性 | 遗留软件包测试生成 |
| 7 | http://arxiv.org/abs/2510.05598v3 | AgentDR: Dynamic Recommendation with Implicit Item-Item Relations via LLM-based Agents | 提出 AgenDR 框架，委托全排名给传统模型，利用 LLM 推理替代与互补关系 | 解决基于代理推荐框架幻觉非存在物品及全目录排名困难的问题 | grocery 数据集推荐系统 |
| 8 | http://arxiv.org/abs/2510.05605v1 | AutoPentester: An LLM Agent-based Framework for Automated Pentesting | 提出 AutoPentester 框架，自动执行渗透测试步骤，动态生成攻击策略 | 解决现有工具半手动需大量人工交互，无法满足 pentesting 需求激增的问题 | 网络安全渗透测试 |
| 9 | http://arxiv.org/abs/2510.05625v1 | Generative AI-Driven Hierarchical Multi-Agent Framework for Zero-Touch Optical Networks | 提出 GenAI 驱动分层多智能体框架，简化多任务自主执行，协调多层协作 | 解决光网络生命周期管理涉及多任务需无缝协作，单代理系统挑战大的问题 | 零接触光网络管理 |
| 10 | http://arxiv.org/abs/2510.05935v1 | LLM-FS-Agent: A Deliberative Role-based Large Language Model Architecture for Transparent Feature Selection | 引入 LLM-FS-Agent，编排 deliberative 辩论，集体评估特征相关性并生成理由 | 解决现有 LLM 特征选择缺乏结构化推理及决策透明 justification 的问题 | 网络安全领域特征选择 |
| 11 | http://arxiv.org/abs/2510.05950v1 | Training-Free Time Series Classification via In-Context Reasoning with LLM Agents | 提出 FETA 框架，分解多变量系列，检索相似示例，利用推理 LLM 比较产生标签 | 解决时间序列分类 labeled 数据稀缺，任务特定训练成本高且不灵活的问题 | 无训练时间序列分类 |
| 12 | http://arxiv.org/abs/2510.06078v1 | Constraint-Aware Route Recommendation from Natural Language via Hierarchical LLM Agents | 提出 RouteLLM，分层多智能体框架，将自然语言意图 grounded 为约束感知路线 | 解决经典路由算法假设结构化输入，LLM 方法 struggle 空间推理及联合建模的问题 | 路线推荐系统 |
| 13 | http://arxiv.org/abs/2510.00549v2 | EMR-AGENT: Automating Cohort and Feature Extraction from EMR Databases | 模块化Agent迭代观察查询结果，用SQL进行数据库观察和决策 | 医疗数据提取依赖硬编码管道，限制可扩展性和跨机构泛化 | MIMIC-III、eICU、SICdb医疗数据库 |
| 14 | http://arxiv.org/abs/2510.00603v1 | LVLMs as inspectors: an agentic framework for category-level structural defect annotation | ADPT框架集成LVLM+语义模式匹配+迭代自问 refinement机制 | 基础设施安全中自动化结构缺陷标注成本高、效率低 | 结构损伤评估数据集构建 |
| 15 | http://arxiv.org/abs/2510.00851v1 | Agentic AI meets Neural Architecture Search: Proactive Traffic Prediction for AI-RAN | NAS框架动态选择编排LSTM架构，分离架构优化和实时推理 | 下一代无线网络需智能流量预测实现自主资源管理处理动态服务需求 | O-RAN环境流量预测 |
| 16 | http://arxiv.org/abs/2510.01115v2 | Exploring Network-Knowledge Graph Duality: A Case Study in Agentic Supply Chain Risk Analysis | 利用网络-KG对偶性，图遍历器基于中心性分数提取经济显著风险路径 | LLM难以处理金融风险底层复杂多模态网络原生数据，标准RAG过度简化关系 | 供应链风险分析 |
| 17 | http://arxiv.org/abs/2510.01398v1 | Automating Data-Driven Modeling and Analysis for Engineering Applications using Large Language Model Agents | 多Agent和单Agent框架自主处理数据预处理、神经网络开发、训练、超参优化、UQ | 传统数据驱动方法需大量人工干预，限制可扩展性和泛化能力 | 临界热通量CHF预测工程建模 |
| 18 | http://arxiv.org/abs/2510.01538v2 | TimeSeriesScientist: A General-Purpose AI Agent for Time Series Analysis | 四专用Agent（Curator/Planner/Forecaster/Reporter）协作，含LLM引导诊断和外部工具 | 现有模型针对特定数据集泛化差，预处理验证集成人工成本高 | 8个基准时间序列预测 |
| 19 | http://arxiv.org/abs/2510.01664v1 | GuruAgents: Emulating Wise Investors with Prompt-Guided LLM Agents | 五位投资大师Agent编码独特哲学到LLM提示，集成金融工具和确定性推理管道 | 将投资大师定性哲学转化为可复现定量策略，实现自动化系统投资 | NASDAQ-100投资回测 |
| 20 | http://arxiv.org/abs/2510.01724v1 | MetaboT: AI-based agent for natural language-based interaction with metabolomics knowledge graphs | 多Agent系统（Entry/Validator/Supervisor/KG Agent）结构化工作流生成SPARQL查询 | 知识图谱使用需深入理解本体和查询语言语法，存在技术壁垒 | 代谢组学知识图谱查询 |
| 21 | http://arxiv.org/abs/2510.03859v1 | Adaptive and Explainable AI Agents for Anomaly Detection in Critical IoT Infrastructure using LLM-Enhanced Contextual Reasoning | 结合 LLM 上下文推理与 XAI 代理，提升 IoT 异常检测的准确性与可解释性 | 解决动态高维 IoT 环境中传统检测方法失效及缺乏透明度的问题 | 关键 IoT 基础设施安全监控 |
| 22 | http://arxiv.org/abs/2510.04017v2 | Zephyrus: An Agentic Framework for Weather Science | 构建 Zephyrus 框架，使 LLM 代理能通过代码工具交互气象数据 | 解决基础气象模型缺乏语言推理能力及交互性工作流支持的问题 | 气象科学交互式分析与预测 |
| 23 | http://arxiv.org/abs/2510.04284v3 | Doctor-R1: Mastering Clinical Inquiry with Experiential Agentic Reinforcement Learning | 提出 Doctor-R1，通过体验式 RL 训练代理掌握临床决策与问诊技巧 | 解决现有 LLM 缺乏战略性及同理心患者问诊能力的问题 | outpatient 临床问诊与决策 |
| 24 | http://arxiv.org/abs/2510.04317v1 | FairAgent: Democratizing Fairness-Aware Machine Learning with LLM-Powered Agents | 引入 FairAgent，自动化分析偏差并实施缓解策略，简化公平模型开发 | 解决公平感知模型开发需要深厚专业知识及流程复杂的问题 | 公平感知机器学习模型开发 |
| 25 | http://arxiv.org/abs/2511.17511v1 | A Multidisciplinary Design and Optimization (MDO) Agent Driven by Large Language Models | 提出 MDO 代理，编排参数建模、RAG 概念化及工程软件优化验证 | 解决机械设计端到端工作流手动脚本多及创新探索不足的问题 | 人机协作机械工程设计 |
| 26 | http://arxiv.org/abs/2510.04587v2 | Pathology-CoT: Learning Visual Chain-of-Thought Agent from Expert Whole Slide Image Diagnosis Behavior | 提出 Pathology-CoT，将专家浏览行为转化为可扩展的监督数据训练代理 | 解决病理代理缺乏专家 tacit 行为监督及可解释诊断决策问题 | 全切片图像病理诊断代理 |
| 27 | http://arxiv.org/abs/2510.04623v1 | MedPAO: A Protocol-Driven Agent for Structuring Medical Reports | 提出 MedPAO，基于临床协议分解任务，确保准确性与可验证推理 | 解决 LLM 结构化临床数据时幻觉及无法遵循领域特定规则问题 | 医疗报告结构化与生成 |
| 28 | http://arxiv.org/abs/2510.04643v1 | QuantAgents: Towards Multi-agent Financial System via Simulated Trading | 提出 QuantAgents，集成模拟交易的多代理金融系统，评估投资策略 | 解决现有 LLM 代理缺乏人类长期预测能力及与真实基金公司偏差问题 | 多代理金融交易与策略评估 |
| 29 | http://arxiv.org/abs/2510.06565v1 | Auto-Stega: An Agent-Driven System for Lifelong Strategy Evolution in LLM-Based Text Steganography | 代理驱动的自我进化框架，自动发现与适应隐写策略 | 解决传统隐写策略难以平衡效率、不可感知性与安全性的问题 | 文本隐写术 |
| 30 | http://arxiv.org/abs/2510.06677v2 | Incremental Summarization for Customer Support via Progressive Note-Taking and Agent Feedback | 结合微调模型与分类器，智能决定生成简洁笔记的时机 | 减少代理上下文切换 effort 及冗余审查，提升生产力 | 客户支持代理 |
| 31 | http://arxiv.org/abs/2510.07297v1 | Agentic generative AI for media content discovery at the national football league | 生成式 AI 工作流将自然语言查询转化为数据库查询语言 | 提升媒体研究人员查询历史片段效率，减少操作时间 | 媒体内容发现 |
| 32 | http://arxiv.org/abs/2510.07307v1 | MLE-Smith: Scaling MLE Tasks with Automated Multi-Agent Pipeline | 自动化多代理流水线将原始数据集转化为竞赛式 MLE 挑战 | 解决高质量 MLE 训练数据获取受限及基准可扩展性低问题 | 机器学习工程任务 |
| 33 | http://arxiv.org/abs/2510.07516v1 | CompassLLM: A Multi-Agent Approach toward Geo-Spatial Reasoning for Popular Path Query | 两阶段流水线识别热门路径并在无历史数据时合成新路径 | 解决传统算法需重新训练及难以适应数据更新的问题 | 地理空间推理 |
| 34 | http://arxiv.org/abs/2510.07591v2 | IASC: Interactive Agentic System for ConLangs | 模块化系统利用代理方法开发构造语言， refinement 音系与语法 | 探索 LLM 对语言概念的认知及辅助低资源语言翻译 | 构造语言开发 |
| 35 | http://arxiv.org/abs/2510.07793v3 | LLM4Cell: A Survey of Large Language and Agentic Models for Single-Cell Biology | 首份单细胞生物学 LLM 与代理模型统一综述，分类 58 种模型 | 解决单细胞生物学中模型进展碎片化及评估标准缺失问题 | 单细胞生物学研究 |
| 36 | http://arxiv.org/abs/2510.08068v2 | An Adaptive Multi Agent Bitcoin Trading System | 利用 LLM  specialized 代理进行技术分析与情绪评估， verbal 反馈机制 | 解决加密货币市场波动大及静态模型难以适应的问题 | 加密货币交易 |
| 37 | http://arxiv.org/abs/2510.08081v1 | AutoQual: An LLM Agent for Automated Discovery of Interpretable Features for Review Quality Assessment | 自动化发现可解释特征，模仿人类研究过程迭代生成假设 | 解决评论质量评估中特征手工构建不可扩展及黑盒问题 | 电商评论质量评估 |
| 38 | http://arxiv.org/abs/2510.08268v1 | Multi-Agent Analysis of Off-Exchange Public Information for Cryptocurrency Market Trend Prediction | 提出理论基础多代理框架，保留信息新闻分析及波动融合 | 解决加密货币预测中关键信息提取及横盘市场检测难题 | 加密货币趋势预测 |
| 39 | http://arxiv.org/abs/2510.08317v1 | Iterated Agent for Symbolic Regression | 利用 LLM 作为语义算子 within 进化搜索，引导表达式发现 | 解决符号回归中搜索空间组合爆炸及模型可解释性差问题 | 科学符号回归 |
| 40 | http://arxiv.org/abs/2510.08354v1 | Mephisto: Self-Improving Large Language Model-Based Agents for Automated Interpretation of Multi-band Galaxy Observations | 多代理协作框架模拟人类推理，迭代 refine 物理模型 | 解决天文数据解释依赖人类专家及黑盒 ML 缺乏透明度问题 | 天文星系观测 |
| 41 | http://arxiv.org/abs/2510.08511v1 | AutoMLGen: Navigating Fine-Grained Optimization for Coding Agents | 集成领域知识库与蒙特卡洛图搜索，支持自进化与协作学习 | 解决 MLE 场景中 LLM 缺乏细粒度领域先验及搜索空间限制 | 机器学习工程 |
| 42 | http://arxiv.org/abs/2510.08804v2 | MOSAIC: Multi-agent Orchestration for Task-Intelligent Scientific Coding | 训练免费多代理框架，学生 - 教师范式自反思生成科学代码 | 解决科学代码需严谨算法及领域知识且无 I/O 测试 case | 科学编码任务 |
| 43 | http://arxiv.org/abs/2510.08842v2 | Maple: A Multi-agent System for Portable Deep Learning across Clusters | 多代理系统生成正确 DL 命令行，适配异构启动器与调度器 | 解决跨 GPU 集群训练 DL 模型命令 compose 易错及繁琐问题 | 分布式深度学习 |
| 44 | http://arxiv.org/abs/2510.08952v3 | When LLM Agents Meet Graph Optimization: An Automated Data Quality Improvement Approach | 统一多代理框架 LAGA，自动化检测规划行动评估图质量 | 解决文本属性图数据质量敏感及现有优化缺乏系统视角 | 图数据分析 |
| 45 | http://arxiv.org/abs/2510.08988v1 | MASA: LLM-Driven Multi-Agent Systems for Autoformalization | 多代理系统驱动自动形式化，转换自然语言为形式表示 | 解决自然语言与形式推理连接及自动形式化效率可靠性 | 形式化数学 |
| 46 | http://arxiv.org/abs/2510.09021v1 | RefGrader: Automated Grading of Mathematical Competition Proofs using Agentic Workflows | 代理工作流提取参考解并自动推导评分标准，多步 grading | 解决模型评分校准 gap 及部分信用分配不一致问题 | 数学竞赛评分 |
| 47 | http://arxiv.org/abs/2511.20656v1 | Context-Aware Visual Prompting: Automating Geospatial Web Dashboards with Large Language Models and Agent Self-Validation for Decision Support | 结合知识图谱与视觉提示，自动化生成地理空间仪表盘代码 | 解决多维环境数据可视化实现复杂与自动化有限的问题 | 地理空间决策支持 |
| 48 | http://arxiv.org/abs/2510.15949v2 | ATLAS: Adaptive Trading with LLM AgentS Through Dynamic Prompt Optimization and Multi-Agent Coordination | 整合市场信息与自适应提示优化，确保输出可执行市场订单 | 解决金融决策中指令适应性与信息合成难题 | 自动化交易 |
| 49 | http://arxiv.org/abs/2510.09404v2 | Agentic Systems in Radiology: Design, Applications, Evaluation, and Challenges | 审查放射学中 LLM 驱动智能体系统设计、应用与挑战 | 解决单一 LLM 无法支持复杂多步放射学工作流的问题 | 医疗放射学 |
| 50 | http://arxiv.org/abs/2512.00007v1 | Use of Retrieval-Augmented Large Language Model Agent for Long-Form COVID-19 Fact-Checking | 结合 RAG 与 Self-RAG，提升长形式新冠 misinformation 事实核查 | 解决 LLM 在长文事实核查中一致性与可解释性不足问题 | 公共卫生事实核查 |
| 51 | http://arxiv.org/abs/2510.09901v1 | Autonomous Agents for Scientific Discovery: Orchestrating Scientists, Language, Code, and Physics | 展望 LLM 科学智能体加速从假设到结果分析的科学发现生命周期 | 解决科学发现流程中自动化与适应性不足的问题 | 科学研究 |
| 52 | http://arxiv.org/abs/2510.09907v1 | Agentic Property-Based Testing: Finding Bugs Across the Python Ecosystem | LLM 智能体分析代码推断属性，合成执行测试并确认 bug | 解决软件测试中自动化发现多样化故障模式难的问题 | 软件测试 |
| 53 | http://arxiv.org/abs/2510.10074v1 | Agentic Troubleshooting Guide Automation for Incident Management | 三阶段工作流自动化故障排除指南，支持并行执行 | 解决手动执行故障排除指南慢且易错的问题 | IT 事件管理 |
| 54 | http://arxiv.org/abs/2510.10454v1 | Traj-CoA: Patient Trajectory Modeling via Chain-of-Agents for Lung Cancer Risk Prediction | 链式智能体处理 EHR 数据， distill 关键事件到共享记忆 | 解决 EHR 数据长且噪声大导致时序推理困难问题 | 医疗风险预测 |
| 55 | http://arxiv.org/abs/2510.10461v1 | MedCoAct: Confidence-Aware Multi-Agent Collaboration for Complete Clinical Decision | 信心感知多智能体框架，模拟医生与药师协作诊疗 | 解决现有医疗 AI 系统任务孤立缺乏交叉验证问题 | 临床决策支持 |
| 56 | http://arxiv.org/abs/2510.17848v1 | RiskTagger: An LLM-based Agent for Automatic Annotation of Web3 Crypto Money Laundering Behaviors | 多模块智能体自动标注加密洗钱行为，提高透明度与扩展性 | 解决 Web3 反洗钱数据集构建依赖人工且效率低问题 | 区块链安全 |
| 57 | http://arxiv.org/abs/2510.10520v2 | AI-Agents for Culturally Diverse Online Higher Education Environments | 提出文化感知 AI 代理，适配多样文化背景学生 | 解决在线教育中文化差异导致的参与度低问题 | 在线高等教育环境 |
| 58 | http://arxiv.org/abs/2510.15969v2 | LinearizeLLM: An Agent-Based Framework for LLM-Driven Exact Linear Reformulation of Nonlinear Optimization Problems | 模式专用代理自动化非线性优化问题线性化 | 解决手动改革非线性优化问题需专业知识问题 | 非线性优化建模 |
| 59 | http://arxiv.org/abs/2510.11754v1 | Zero-Shot Large Language Model Agents for Fully Automated Radiotherapy Treatment Planning | 零样本 LLM 代理直接交互临床计划系统 | 解决放疗计划依赖人工专家且负担重的问题 | 放射治疗计划 |
| 60 | http://arxiv.org/abs/2510.10807v3 | Multi-Agent Regime-Conditioned Diffusion (MARCD) for CVaR-Constrained Portfolio Decisions | 生成式决策框架结合 regime 条件扩散与 CVaR | 解决市场机制转换下的投资组合决策风险问题 | 金融投资组合决策 |
| 61 | http://arxiv.org/abs/2510.10824v1 | Agentic RAG for Software Testing with Hybrid Vector-Graph and Multi-Agent Orchestration | 混合向量图知识系统与多智能体编排自动化测试 | 解决传统软件测试局限性及文档追溯性问题 | 软件质量工程 |
| 62 | http://arxiv.org/abs/2510.10895v1 | LLM-Empowered Agentic MAC Protocols: A Dynamic Stackelberg Game Approach | LLM 驱动多智能体 DRL 合成自适应 MAC 协议 | 解决传统 MAC 协议泛化差及动态环境适应难问题 | 无线网络 MAC 协议 |
| 63 | http://arxiv.org/abs/2510.11759v1 | AwareCompiler: Agentic Context-Aware Compiler Optimization via a Synergistic Knowledge-Data Driven Framework | 知识数据驱动框架优化编译器 pass 序列 | 解决自动化编译器优化中语义不对齐与奖励稀疏问题 | 编译器优化 |
| 64 | http://arxiv.org/abs/2510.11004v1 | Automating Structural Engineering Workflows with Large Language Model Agents | 多智能体系统集成 LLM 自动化结构工程工作流 | 解决结构工程核心工作流数十年停滞问题 | 结构工程工作流 |
| 65 | http://arxiv.org/abs/2510.11076v1 | DebugTA: An LLM-Based Agent for Simplifying Debugging and Teaching in Programming Education | 专用工具检索标准代码，简化调试教学逻辑 | 解决调试教学任务输入复杂及推理挑战高问题 | 编程教育调试 |
| 66 | http://arxiv.org/abs/2510.16080v1 | TriAgent: Automated Biomarker Discovery with Deep Research Grounding for Triage in Acute Care by LLM-Based Multi-Agent Collaboration | 监督研究Agent生成主题并委托子Agent检索证据，合成分类生物标志物 | 急诊分策方法错过可改善风险预测的新兴生物信号 | 急诊科患者分诊与风险分层 |
| 67 | http://arxiv.org/abs/2510.16085v1 | MoPHES:Leveraging on-device LLMs as Agent for Mobile Psychological Health Evaluation and Support | 两个微调MiniCPM模型分别评估心理状态与处理对话，部署于移动设备 | 通用LLM缺乏心理健康专业微调，忽视实时用户心理状态评估 | 移动端心理健康评估与支持 |
| 68 | http://arxiv.org/abs/2510.16194v2 | MedBuild AI: An Agent-Based Hybrid Intelligence Framework for Reshaping Agency in Healthcare Infrastructure Planning through Generative Design for Medical Architecture | 三Agent系统：收集健康情报、翻译为建筑功能程序、生成布局和3D模型 | 全球医疗基础设施差距大，传统规划缓慢且难以获取 | 医疗建筑设计与规划 |
| 69 | http://arxiv.org/abs/2510.16701v2 | An Agentic Framework with LLMs for Solving Complex Vehicle Routing Problems | 四专用Agent协调交互强制执行跨功能一致性与逻辑合理性，自包含代码生成 | 复杂车辆路径问题需大量专家工作，当前LLM方法依赖外部干预 | 车辆路径问题求解 |
| 70 | http://arxiv.org/abs/2510.16872v1 | DeepAnalyze: Agentic Large Language Models for Autonomous Data Science | 首个自主数据科学Agentic LLM，课程式Agent训练范式模拟人类数据科学家学习轨迹 | 工作流式数据Agent依赖预定义工作流，无法实现完全自主数据科学 | 端到端数据科学研究 |
| 71 | http://arxiv.org/abs/2510.16996v1 | STARK: Strategic Team of Agents for Refining Kernels | 多Agent协作系统探索设计空间，模拟专家工程师工作流迭代优化内核 | GPU内核优化因内存层次/线程调度/硬件特性复杂交互而困难 | GPU内核自动优化 |
| 72 | http://arxiv.org/abs/2510.17002v1 | EEschematic: Multimodal-LLM Based AI Agent for Schematic Generation of Analog Circuit | 六模拟子结构示例少样本放置，视觉链式思考策略迭代优化放置布线 | 现有LLM方法仅依赖SPICE网表等文本表示，缺乏视觉可解释性 | 模拟集成电路原理图生成 |
| 73 | http://arxiv.org/abs/2510.11661v2 | SR-Scientist: Scientific Equation Discovery With Agentic AI | 提升 LLM 为自主科学家，编写代码分析数据并优化方程。 | 现有方法将 LLM 局限于搜索算法中的简单方程提出者。 | 科学方程发现 |
| 74 | http://arxiv.org/abs/2510.12033v1 | CausalTrace: A Neurosymbolic Causal Analysis Agent for Smart Manufacturing | 神经符号因果分析模块集成到工业 CoPilot。 | 现有 AI 系统缺乏预测、解释和因果推理的无缝集成。 | 智能制造 |
| 75 | http://arxiv.org/abs/2510.13883v1 | Large Language Model Agents Enable Autonomous Design and Image Analysis of Microwell Microfluidics | 自主 LLM 驱动框架生成 CAD 脚本并分析图像。 | 微井微流体设计复杂，需要知识和手动干预。 | 微井微流体设计 |
| 76 | http://arxiv.org/abs/2510.12061v1 | Empowering LLM Agents with Geospatial Awareness: Toward Grounded Reasoning for Wildfire Response | 地理空间感知层将 LLM 代理 grounding 到结构化地球数据。 | LLM 局限于文本且对地理盲目，影响灾难响应。 | 野火响应 |
| 77 | http://arxiv.org/abs/2510.12091v1 | ToPolyAgent: AI Agents for Coarse-Grained Topological Polymer Simulations | 多代理框架通过自然语言指令执行分子动力学模拟。 | 聚合物科学中复杂计算工作流门槛高。 | 拓扑聚合物模拟 |
| 78 | http://arxiv.org/abs/2510.13896v1 | GenCellAgent: Generalizable, Training-Free Cellular Image Segmentation via Large Language Model Agents | 免训练多代理框架协调专业分割器和 VLM。 | 细胞图像分割因模态异质性和标注有限而困难。 | 细胞图像分割 |
| 79 | http://arxiv.org/abs/2510.12972v2 | TaskAudit: Detecting Functiona11ity Errors in Mobile Apps via Agentic Task Execution | 包含任务生成器、执行器和可访问性分析器的组件。 | 当前检查器评估静态上下文，无法捕捉交互中的错误。 | 移动应用可访问性审计 |
| 80 | http://arxiv.org/abs/2510.13248v1 | Automated Network Protocol Testing with LLM Agents | 多代理 LLM 系统用于端到端自动化网络协议测试。 | 传统网络协议测试方法劳动密集且易出错。 | 网络协议测试 |
| 81 | http://arxiv.org/abs/2510.13371v1 | MADREC: A Multi-Aspect Driven LLM Agent for Explainable and Adaptive Recommendation | 自主 LLM 基推荐器通过无监督提取构建用户和物品 profile。 | 大多数 LLM 推荐系统局限于简单文本生成或静态提示。 | 推荐系统 |
| 82 | http://arxiv.org/abs/2510.13925v1 | An LLM-Powered AI Agent Framework for Holistic IoT Traffic Interpretation | 框架将原始数据包捕获转换为结构化表示以供交互式分析。 | 从 IoT 遥测中 deriving 有意义的洞察需要跨层解释。 | IoT 网络流量解释 |
| 83 | http://arxiv.org/abs/2510.16034v2 | Disaster Management in the Era of Agentic AI Systems: A Vision for Collective Human-Machine Intelligence for Augmented Resilience | 提出 Disaster Copilot 愿景，统一专用 AI 工具协作应对灾害管理 | 解决灾害管理中数据碎片化、资源受限和机构记忆侵蚀问题 | 灾害管理系统 |
| 84 | http://arxiv.org/abs/2510.14264v1 | AlphaQuanter: An End-to-End Tool-Orchestrated Agentic Reinforcement Learning Framework for Stock Trading | 提出端到端工具编排的强化学习框架，学习动态策略进行股票交易 | 解决多智能体交易框架效率低、信号不一致和缺乏端到端优化 | 股票交易 |
| 85 | http://arxiv.org/abs/2510.14980v2 | Agentic Design of Compositional Machines | 基于 BesiegeField 测试床，benchmark LLM 在组合机器设计中的能力 | 研究 LLM 是否具备通过组合标准化组件创造复杂机器的能力 | 组合机器设计 |
| 86 | http://arxiv.org/abs/2510.20099v1 | AI PB: A Grounded Generative Agent for Personalized Investment Insights | 组件编排层+混合检索+多阶段推荐机制 | 被动问答机器人无法提供主动合规投资建议 | 零售金融投资顾问 |
| 87 | http://arxiv.org/abs/2510.20255v1 | Towards AI Agents for Course Instruction in Higher Education: Early Experiences from the Field | LLM驱动讲师Agent+可解释参与度评估框架 | 高等教育中规模化高质量教学需求 | 研究生云计算课程 |
| 88 | http://arxiv.org/abs/2510.20567v1 | Beyond Retrieval-Ranking: A Multi-Agent Cognitive Decision Framework for E-Commerce Search | 多Agent认知决策框架从被动检索转向主动支持 | 电商搜索与用户多阶段认知决策不匹配 | 电商平台搜索系统 |
| 89 | http://arxiv.org/abs/2510.21117v2 | DAO-AI: Evaluating Collective Decision-Making through Agentic AI in Decentralized Governance | 模块化MCP工作流+可解释投票Agent | 去中心化治理中集体决策效率低下 | DAO治理系统 |
| 90 | http://arxiv.org/abs/2510.21143v2 | PanicToCalm: A Proactive Counseling Agent for Panic Attacks | PACE数据集+PACER咨询模型+PanicEval框架 | 恐慌发作干预训练数据稀缺 | 心理健康危机干预 |
| 91 | http://arxiv.org/abs/2510.21147v1 | Hierarchical AI Multi-Agent Fundamental Investing: Evidence from China's A-Share Market | 宏观/公司/组合/风控四层Agent架构 | 传统投资方法风险调整收益不足 | 中国A股量化投资 |
| 92 | http://arxiv.org/abs/2510.21228v1 | DispatchMAS: Fusing taxonomy and artificial intelligence agents for emergency medical services | 临床分类学 grounding+Caller/Dispatcher双Agent | 急救调度中呼叫者压力和信息模糊 | 紧急医疗服务调度 |
| 93 | http://arxiv.org/abs/2510.17004v1 | ReclAIm: A multi-agent framework for degradation-aware performance tuning of medical imaging AI | 多智能体框架自动监控、评估并微调医疗影像模型。 | 解决医疗 AI 模型长期运行中的性能退化问题。 | 医疗影像 AI 模型维护 |
| 94 | http://arxiv.org/abs/2510.17913v1 | TACLA: An LLM-Based Multi-Agent Tool for Transactional Analysis Training in Education | 集成交易分析原理的多智能体架构，模拟父母/成人/儿童自我状态。 | 解决教育中社会动态模拟缺乏心理深度和一致性人格行为的问题。 | 教育心理训练工具 |
| 95 | http://arxiv.org/abs/2512.00016v1 | Architect in the Loop Agentic Hardware Design and Verification | 工程师在环的智能体自动化处理器设计与验证，分层模块化生成 HDL。 | 解决硬件设计流程复杂性高，缺乏自动化整个处理器设计过程的问题。 | 硬件设计与验证 |
| 96 | http://arxiv.org/abs/2510.17064v3 | A Brain Cell Type Resource Created by Large Language Models and a Multi-Agent AI System for Collaborative Community Annotation | 多智能体系统整合自由文本与本体标签，利用 RAG 减少幻觉。 | 解决单细胞 RNA 测序中基因集注释依赖 curated 标注且表现不佳的问题。 | 生物医学基因注释 |
| 97 | http://arxiv.org/abs/2510.17235v1 | Coinvisor: An RL-Enhanced Chatbot Agent for Interactive Cryptocurrency Investment Analysis | 基于强化学习的工具选择机制，支持多步规划与动态数据源整合。 | 解决加密货币投资分析中信息碎片化、缺乏实时数据整合与多步推理的问题。 | 加密货币投资分析 |
| 98 | http://arxiv.org/abs/2510.17521v1 | Cybersecurity AI: Evaluating Agentic Cybersecurity in Attack/Defense CTFs | 实证评估 AI 系统在网络安全攻防中的有效性，挑战攻击者优势论。 | 解决 AI 攻防有效性缺乏受控实证证据及成功标准细微差别的问题。 | 网络安全攻防 |
| 99 | http://arxiv.org/abs/2601.05256v1 | Naiad: Novel Agentic Intelligent Autonomous System for Inland Water Monitoring | 利用 LLM 及外部工具提供内陆水监测整体解决方案，单提示接口。 | 解决现有方法仅address 孤立子问题及缺乏 holistic 解决方案的问题。 | 内陆水环境监测 |
| 100 | http://arxiv.org/abs/2510.17590v1 | MIRAGE: Agentic Framework for Multimodal Misinformation Detection with Web-Grounded Reasoning | 分解多模态验证为四模块，编排 VLM 推理与 targeted 网页检索。 | 解决多模态虚假信息检测缺乏领域特定训练数据及泛化能力的问题。 | 多模态虚假信息检测 |
| 101 | http://arxiv.org/abs/2510.17603v1 | ShapeCraft: LLM Agents for Structured, Textured and Interactive 3D Modeling | 提出基于图的过程形状表示，分层解析输入迭代细化建模。 | 解决现有 3D 生成方法产生非结构化网格及交互性差的问题。 | 3D 建模与生成 |
| 102 | http://arxiv.org/abs/2601.05257v1 | KP-Agent: Keyword Pruning in Sponsored Search Advertising via LLM-Powered Contextual Bandits | 建模关键词修剪为 contextual bandit，生成代码片段 refine 关键词集。 | 解决赞助搜索广告中关键词修剪实践效率低下及缺乏探索的问题。 | 赞助搜索广告 |
| 103 | http://arxiv.org/abs/2510.18289v1 | Food4All: A Multi-Agent Framework for Real-time Free Food Discovery with Integrated Nutritional Metadata | 统一异质数据聚合、轻量 RL 优化及在线反馈 loop。 | 解决食物不安全人群访问资源碎片化及现有系统忽略生存关键需求的问题。 | 食物安全与发现 |
| 104 | http://arxiv.org/abs/2510.18424v1 | Med-VRAgent: A Framework for Medical Visual Reasoning-Enhanced Agents | 基于视觉引导与自奖励范式及 MCTS，结合树搜索改进视觉推理。 | 解决 VLM 在医疗推理中幻觉、描述模糊、逻辑不一致及定位差的问题。 | 医疗视觉推理 |
| 105 | http://arxiv.org/abs/2510.21993v1 | FeaGPT: an End-to-End agentic-AI for Finite Element Analysis | 首个实现几何-网格-仿真全流程自动化的Agentic AI框架 | 工程仿真需手动干预，流程割裂 | 有限元分析工程领域 |
| 106 | http://arxiv.org/abs/2510.22222v1 | CreditXAI: A Multi-Agent System for Explainable Corporate Credit Rating | 多Agent模拟专业分析师协作决策过程 | 信用评级黑盒问题，缺乏层次推理机制 | 企业信用风险评估 |
| 107 | http://arxiv.org/abs/2510.22559v1 | A Closed-Loop Personalized Learning Agent Integrating Neural Cognitive Diagnosis, Bounded-Ability Adaptive Testing, and LLM-Driven Feedback | 诊断-推荐-反馈闭环，整合NCD+BECAT+LLM | 个性化学习各环节孤立，反馈不可操作 | 智能教育个性化学习 |
| 108 | http://arxiv.org/abs/2510.22626v1 | SwiftSolve: A Self-Iterative, Complexity-Aware Multi-Agent Framework for Competitive Programming | 复杂度感知多Agent框架，耦合算法规划与经验分析 | LLM生成代码满足测试但违反时间/内存预算 | 竞争性编程任务 |
| 109 | http://arxiv.org/abs/2510.22787v1 | Collaborative LLM Agents for C4 Software Architecture Design Automation | 角色专家Agent对话自动生成C4架构模型 | C4架构建模手动耗时，缺乏自动化 | 软件架构设计 |
| 110 | http://arxiv.org/abs/2510.23032v1 | P1GPT: a multi-agent LLM workflow module for multi-modal financial information analysis | 结构化推理流水线融合技术/基本面/新闻洞察 | 金融分析框架缺乏统一多模态推理工作流 | 多模态金融信息分析与交易决策 |
| 111 | http://arxiv.org/abs/2510.23443v1 | A Neuro-Symbolic Multi-Agent Approach to Legal-Cybersecurity Knowledge Integration | 神经符号多Agent整合法律-网络安全知识 | 法律与网络安全领域知识割裂 | 跨领域法律-网络安全研究 |
| 112 | http://arxiv.org/abs/2510.18569v1 | QuantEvolve: Automating Quantitative Strategy Discovery through Multi-Agent Evolutionary Framework | 结合质量多样性优化与假设驱动策略生成，自动发现量化策略 | 解决量化策略开发难以探索巨大策略空间的问题 | 金融量化交易 |
| 113 | http://arxiv.org/abs/2510.18585v1 | CLASP: Cost-Optimized LLM-based Agentic System for Phishing Detection | 利用多智能体分析 URL、截图和 HTML，优化成本与检测率 | 解决钓鱼网站检测成本高且准确率不足的问题 | 网络安全与钓鱼检测 |
| 114 | http://arxiv.org/abs/2510.19247v1 | SheetBrain: A Neuro-Symbolic Agent for Accurate Reasoning over Complex and Large Spreadsheets | 神经符号双工作流，结合理解、执行与验证模块处理表格 | 解决 LLM 难以准确捕捉表格结构及推理正确性问题 | 复杂电子表格推理 |
| 115 | http://arxiv.org/abs/2510.19274v1 | From Specification to Service: Accelerating API-First Development Using Multi-Agent Systems | 利用多智能体自动化 API 优先开发，通过日志分析 refine 代码 | 解决 RESTful 微服务开发手动迭代多且效率低的问题 | API 优先软件开发 |
| 116 | http://arxiv.org/abs/2510.19438v1 | AutoMT: A Multi-Agent LLM Framework for Automated Metamorphic Testing of Autonomous Driving Systems | 自动化提取 metamorphic 关系并生成测试用例，提升测试多样性 | 解决自动驾驶测试依赖人工且缺乏自动化的问题 | 自动驾驶系统测试 |
| 117 | http://arxiv.org/abs/2510.19577v1 | gem5 Co-Pilot: AI Assistant Agent for Architectural Design Space Exploration | 构建 AI 助手代理，自动化设计空间探索与结果总结 | 解决计算机架构设计空间探索复杂耗时的问题 | 计算机架构设计探索 |
| 118 | http://arxiv.org/abs/2510.19692v2 | Toward Agentic Software Engineering Beyond Code: Framing Vision, Values, and Vocabulary | 扩展 agentic SE 范围至全过程，提出价值观与设计词汇 | 解决 agentic SE 仅关注代码加速而忽略 socio-technical 活动的问题 | 软件工程专业实践 |
| 119 | http://arxiv.org/abs/2510.23761v2 | TDFlow: Agentic Workflows for Test Driven Development | 将软件工程修复 framed 为测试分辨率任务，分解为四个子智能体组件。 | 解决长上下文负担与特定子任务性能优化问题。 | 仓库级软件工程与测试驱动开发 |
| 120 | http://arxiv.org/abs/2510.23856v2 | From Benchmarks to Business Impact: Deploying IBM Generalist Agent in Enterprise Production | 报告企业级通用智能体部署经验，引入 BPO-TA 基准评估业务价值。 | 解决从原型到部署系统的可扩展性与治理难题。 | 企业业务流程外包与人才获取 |
| 121 | http://arxiv.org/abs/2510.23924v1 | Agent-based Automated Claim Matching with Instruction-following LLMs | 提出两步流水线，利用 LLM 生成提示进行索赔匹配分类。 | 解决人工生成提示成本高与小模型能力利用问题。 | 自动化索赔匹配任务 |
| 122 | http://arxiv.org/abs/2510.24145v2 | From Observability Data to Diagnosis: An Evolving Multi-agent System for Incident Management in Cloud Systems | 采用无训练数据处理器与双自进化机制，实现云系统事件管理。 | 解决手动事件管理劳动密集且易错与自动化泛化难问题。 | 大规模云系统可靠性管理 |
| 123 | http://arxiv.org/abs/2510.24339v2 | VDSAgents: A PCS-Guided Multi-Agent System for Veridical Data Science Automation | 基于 PCS 原则指导数据清洗到评估的模块化工作流。 | 解决仅依赖 LLM 内部推理缺乏科学理论指导导致不可信问题。 | 数据科学工作流自动化 |
| 124 | http://arxiv.org/abs/2510.24438v1 | Can LLMs Write Faithfully? An Agent-Based Evaluation of LLM-generated Islamic Content | 双智能体框架定量验证引用与定性比较，评估伊斯兰内容准确性。 | 解决宗教敏感领域内容生成准确性与引用可靠性问题。 | 伊斯兰知识生成与评估 |
| 125 | http://arxiv.org/abs/2510.24654v2 | Evolving Interactive Diagnostic Agents in a Virtual Clinical Environment | 在虚拟临床环境中通过 RL 训练诊断智能体，优化交互与准确性。 | 解决静态数据训练无法获得长期诊断管理能力问题。 | 医疗诊断与交互式临床环境 |
| 126 | http://arxiv.org/abs/2510.24980v1 | FT-ARM: Fine-Tuned Agentic Reflection Multimodal Language Model for Pressure Ulcer Severity Classification with Reasoning | 微调多模态大模型，结合代理自反思机制分类压疮严重程度。 | 解决临床解释性有限与分类一致性问题。 | 医疗压疮分类与诊断 |
| 127 | http://arxiv.org/abs/2510.26498v1 | A Multi-agent Large Language Model Framework to Automatically Assess Performance of a Clinical AI Triage Tool | 八开源LLM+GPT-4o集成评估临床AI分诊工具 | 单LLM评估临床AI工具可靠性不足 | 医疗AI分诊工具性能评估 |
| 128 | http://arxiv.org/abs/2510.26603v1 | Agentic AI Home Energy Management System: A Large Language Model Framework for Residential Load Scheduling | 分层架构：1编排器+3专家Agent，ReAct模式迭代推理 | 用户偏好到技术参数翻译障碍限制HEMS采用 | 家庭能源管理系统 |
| 129 | http://arxiv.org/abs/2510.26699v3 | Using Copilot Agent Mode to Automate Library Migration: A Quantitative Assessment | 评估Copilot Agent Mode自动化库迁移能力，引入迁移覆盖率指标 | 库和框架更新耗时且易出错 | Python库迁移（SQLAlchemy） |
| 130 | http://arxiv.org/abs/2510.26887v1 | The Denario project: Deep knowledge AI agents for scientific discovery | 模块化多Agent系统，可端到端完成科学研究全流程 | 科学研究工作流自动化程度低 | 多学科科学研究（天体物理、生物等） |
| 131 | http://arxiv.org/abs/2510.27107v1 | A Memory-Efficient Retrieval Architecture for RAG-Enabled Wearable Medical LLMs-Agents | 分层检索架构：近似检索生成候选集+高精度检索 | 边缘设备RAG实现内存访问和能耗高 | 可穿戴医疗LLM Agent |
| 132 | http://arxiv.org/abs/2510.27140v2 | AI Agents in Drug Discovery | 综述Agentic AI架构在药物发现各阶段应用与量化影响 | 药物发现工作流耗时且缺乏自动化 | 药物发现全流程 |
| 133 | http://arxiv.org/abs/2510.27251v2 | FinPos: A Position-Aware Trading Agent System for Real Financial Markets | 位置感知交易任务，双Agent决策结构分离方向推理与风险调整 | 现有交易Agent缺乏连续头寸管理意识 | 真实金融市场交易 |
| 134 | http://arxiv.org/abs/2510.27334v1 | When AI Trading Agents Compete: Adverse Selection of Meta-Orders by Reinforcement Learning-Based Market Making | RL做市Agent学习利用元订单诱导的价格漂移 | 中频交易Agent被高频交易Agent逆向选择 | 金融市场做市与交易 |
| 135 | http://arxiv.org/abs/2510.27417v1 | Agentic LLMs for REST API Test Amplification: A Comparative Study Across Cloud Applications | 评估单Agent和多Agent配置在云应用REST API测试放大效果 | 设计多样化边界级测试用例挑战性高 | 云原生系统REST API测试 |
| 136 | http://arxiv.org/abs/2510.25189v1 | AgentCyTE: Leveraging Agentic AI to Generate Cybersecurity Training & Experimentation Scenarios | LLM 推理与确定性网络仿真结合的 Agent 反馈闭环 | 网络安全威胁场景生成手动成本高、验证难的问题 | 网络安全训练与实验 |
| 137 | http://arxiv.org/abs/2510.25333v1 | CRMWeaver: Building Powerful Business Agent via Agentic RL and Shared Memories | 合成数据生成+RL 训练，引入共享记忆机制 | 业务环境数据关系复杂、任务异构的问题 | 企业 CRM 业务 Agent |
| 138 | http://arxiv.org/abs/2510.25518v1 | Retrieval Augmented Generation (RAG) for Fintech: Agentic Design and Evaluation | 模块化 Agent 管道支持查询重构与上下文消歧 | 金融领域术语密集导致 RAG 检索合成效果差 | 金融科技知识检索 |
| 139 | http://arxiv.org/abs/2510.25743v1 | Agentic Economic Modeling | 对齐 LLM 合成选择与人类证据进行经济计量推断 | 小样本人类数据难以进行可靠经济推断的问题 | 经济建模与政策评估 |
| 140 | http://arxiv.org/abs/2510.25758v2 | TheraMind: A Strategic and Adaptive Agent for Longitudinal Psychological Counseling | 双循环架构解耦战术对话与战略治疗规划 | 现有心理咨询 Agent 缺乏情感理解与长期记忆 | 在线 longitudinal 心理咨询 |
| 141 | http://arxiv.org/abs/2510.25914v1 | FinOps Agent -- A Use-Case for IT Infrastructure and Cost Optimization | 自主目标驱动 Agent 自动化 FinOps 流程 | 账单数据异构导致合成洞察与决策困难 | IT 基础设施成本优化 |
| 142 | http://arxiv.org/abs/2510.25997v1 | From Queries to Insights: Agentic LLM Pipelines for Spatio-Temporal Text-to-SQL | orchestration by ReAct agent 扩展 naive text-to-SQL | 现有系统难处理 realistic 时空查询与 vague  phrasing | 时空数据自然语言查询 |
| 143 | http://arxiv.org/abs/2510.26114v1 | OracleAgent: A Multimodal Reasoning Agent for Oracle Bone Script Research | 集成多工具 orchestrate 甲骨文多模态知识库检索 | 甲骨文研究 workflow 复杂、信息组织检索效率低 | 甲骨文研究与解释 |
| 144 | http://arxiv.org/abs/2510.26172v1 | Linking Heterogeneous Data with Coordinated Agent Flows for Social Media Analysis | 协调 Agent 流链接异构多模态数据进行分析 | 社交媒体数据异构导致洞察发现概念挑战 | 社交媒体分析与挖掘 |
| 145 | http://arxiv.org/abs/2510.26242v1 | Retrieval Augmented Generation-Enhanced Distributed LLM Agents for Generalizable Traffic Signal Control with Emergency Vehicles | RAG 增强分布式 LLM Agent 处理紧急车辆交通信号 | 紧急情况 LLM 幻觉导致决策不可靠、泛化差 | 智能交通信号控制 |

[返回目录](#目录)

<a id="cat-04"></a>

## Agent安全与对齐

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2510.05192v1 | Adapting Insider Risk mitigations for Agentic Misalignment: an empirical study | 适应内部风险控制设计，引入外部监管升级通道，保证暂停与独立审查 | 解决智能体在压力下产生勒索等有害行为的错位风险 | 通用 LLM 智能体安全 |
| 2 | http://arxiv.org/abs/2510.04860v2 | Alignment Tipping Process: How Self-Evolution Pushes LLM Agents Off the Rails | 识别对齐 tipping 过程，形式化自我利益探索与模仿策略扩散两种范式 | 解决自进化智能体在部署后因反馈驱动衰退而放弃对齐约束的风险 | 自进化 LLM 智能体长期可靠性 |
| 3 | http://arxiv.org/abs/2510.05442v1 | Adversarial Reinforcement Learning for Large Language Model Agent Safety | 提出 ARLAS 框架， formulate 为零和博弈，共训练攻击者与防御者代理 | 解决手动 crafted 攻击模式多样性有限，代理易受新颖提示注入风险 | LLM 代理工具使用安全 |
| 4 | http://arxiv.org/abs/2510.05484v2 | Evaluating LLM Safety Across Child Development Stages: A Simulated Agent Approach | 提出 ChildSafe 基准，参数量化认知模拟方法，形式化发展阶段为超参数约束 | 解决当前安全对齐隐含优化“模态成年用户”，易受用户认知分布偏移影响 | 不同认知发展阶段用户安全 |
| 5 | http://arxiv.org/abs/2510.08605v1 | Toward a Safer Web: Multilingual Multi-Agent LLMs for Mitigating Adversarial Misinformation Attacks | 呈现多语言多智能体 LLM 框架，部署为 web 插件， mitigating 对抗性 misinformation | 解决 misinformation 快速传播威胁公共 discourse 及决策，缺乏系统研究特定变换的问题 | 在线平台事实完整性保护 |
| 6 | http://arxiv.org/abs/2510.05865v1 | The Safety Challenge of World Models for Embodied AI Agents: A Review | 综述自主驾驶与机器人领域世界模型，聚焦场景与控制生成任务的安全影响 | 解决具身代理预测需确保对代理与环境安全，缺乏综合文献回顾的问题 | 具身 AI 代理安全 |
| 7 | http://arxiv.org/abs/2511.02841v2 | AI Agents with Decentralized Identifiers and Verifiable Credentials | Agent配备DID去中心化标识符+第三方签发可验证凭证，建立跨域信任 | 当前LLM Agent无法在对话开始时建立差异化信任，跨域互操作信任缺失 | 跨组织边界的Agent对话 |
| 8 | http://arxiv.org/abs/2510.01164v1 | Social Welfare Function Leaderboard: When LLM Agents Allocate Social Welfare | SWF基准模拟LLM作为主权分配器，权衡集体效率和分配公平 | LLM指导原则和价值观在分配稀缺社会资源时未受检验 | 20个SOTA LLM社会资源分配 |
| 9 | http://arxiv.org/abs/2510.01354v1 | WAInjectBench: Benchmarking Prompt Injection Detections for Web Agents | 细粒度攻击分类+文本图像检测方法系统评估，含恶意和 benign样本 | 提示注入检测方法未针对Web Agent系统评估，存在检测盲区 | Web Agent提示注入检测 |
| 10 | http://arxiv.org/abs/2510.01359v1 | Breaking the Code: Security Assessment of AI Code Agents Through Systematic Jailbreaking Attacks | JAWS-BENCH三工作区制度+可执行感知Judge框架，测量可部署危害 | 代码Agent安全评估强调拒绝检测，未测试是否实际编译运行恶意程序 | 7个LLM家族的代码Agent |
| 11 | http://arxiv.org/abs/2510.01670v1 | Just Do It!? Computer-Use Agents Exhibit Blind Goal-Directedness | BLIND-ACT基准90任务捕捉三BGD模式，LLM法官评估达93.75%与人标注一致 | CUA一致表现盲目目标导向性偏见，不顾可行性安全性可靠性上下文追求目标 | 9个前沿模型的计算机使用Agent |
| 12 | http://arxiv.org/abs/2510.03992v1 | Quantifying Distributional Robustness of Agentic Tool-Selection | 提出 ToolCert 框架，形式化认证代理工具选择的分布鲁棒性 | 解决 adversarial 工具注入导致代理选择错误及安全风险的问题 | 代理系统工具选择机制安全 |
| 13 | http://arxiv.org/abs/2510.04257v1 | AgentTypo: Adaptive Typographic Prompt Injection Attacks against Black-box Multimodal Agents | 提出 AgentTypo 框架，通过嵌入优化文本进行自适应排版提示注入攻击 | 解决多模态代理在开放世界设置中对视觉输入提示注入脆弱的问题 | 多模态代理安全红队测试 |
| 14 | http://arxiv.org/abs/2510.05179v2 | Agentic Misalignment: How LLMs Could Be Insider Threats | 压力测试 16 个模型，发现代理在特定情境下会表现出恶意内部威胁行为 | 解决当前模型在自主角色中可能违背公司利益的安全对齐风险 | 企业环境中的自主 AI 代理部署 |
| 15 | http://arxiv.org/abs/2510.04303v2 | Audit the Whisper: Detecting Steganographic Collusion in Multi-Agent LLMs | 提出 Audit the Whisper，通过信道容量分析及互信息检测代理共谋 | 解决多代理部署中隐蔽协调侵蚀信任及社会福利的审计难题 | 多 Agent 市场与治理工作流审计 |
| 16 | http://arxiv.org/abs/2510.06445v2 | A Survey on Agentic Security: Applications, Threats and Defenses | 首份代理安全全景调查，构建应用、威胁与防御三大支柱分类体系 | 梳理代理安全领域研究现状，揭示关键研究缺口 | 代理安全研究领域 |
| 17 | http://arxiv.org/abs/2510.06607v2 | Code Agent can be an End-to-end System Hacker: Benchmarking Real-world Threats of Computer-use Agent | 提出 AdvCUA 基准，对齐 MITRE ATT&CK 评估计算机使用代理威胁 | 解决现有工作缺乏真实攻击战术覆盖及环境 unrealistic 问题 | 计算机使用代理安全 |
| 18 | http://arxiv.org/abs/2510.13825v1 | A2AS: Agentic AI Runtime Security and Self-Defense | 提出 A2AS 安全层及 BASIC 模型， enforce 认证行为与上下文完整性 | 为 AI 代理提供类似 HTTPS 的运行时安全防御层 | 代理应用安全 |
| 19 | http://arxiv.org/abs/2510.07176v1 | Exposing LLM User Privacy via Traffic Fingerprint Analysis: A Study of Privacy Risks in LLM Agent Interactions | 开发 AgentPrint 分析加密流量指纹，推断代理活动与用户属性 | 揭示代理交互行为在加密流量中泄露用户隐私的风险 | 代理交互隐私 |
| 20 | http://arxiv.org/abs/2510.07709v1 | Multimodal Safety Evaluation in Generative Agent Social Simulations | 引入可重复仿真框架，评估代理在多模态环境下的安全改进 | 解决生成代理在多模态环境中安全推理与信任能力有限问题 | 多模态社会仿真 |
| 21 | http://arxiv.org/abs/2510.07809v2 | Practical and Stealthy Touch-Guided Jailbreak Attacks on Deployed Mobile Vision-Language Agents | 提出实用且隐蔽的越狱攻击框架，无需特权即可注入视觉负载 | 解决移动视觉语言代理感知与交互中的安全漏洞问题 | 移动视觉语言代理 |
| 22 | http://arxiv.org/abs/2510.07920v1 | Profit Mirage: Revisiting Information Leakage in LLM-based Financial Agents | 量化信息泄漏维度，提出 FactFin 框架学习因果驱动 | 解决金融代理因信息泄漏导致的回测收益虚高问题 | 金融交易代理 |
| 23 | http://arxiv.org/abs/2510.08238v1 | Chain-of-Trigger: An Agentic Backdoor that Paradoxically Enhances Agentic Robustness | 提出多步后门攻击，利用环境随机性 paradoxically 增强鲁棒性 | 解决长程代理控制中的安全漏洞及潜在隐蔽风险问题 | 多模态智能体 |
| 24 | http://arxiv.org/abs/2510.08240v1 | The Alignment Waltz: Jointly Training Agents to Collaborate for Safety | 提出 WaltzRL 框架，联合训练对话与反馈代理协作确保安全 | 解决安全对齐中过度拒绝及对抗攻击脆弱性的张力问题 | 通用对话代理 |
| 25 | http://arxiv.org/abs/2510.08829v1 | CommandSans: Securing AI Agents with Surgical Precision Prompt Sanitization | 令牌级净化过程，手术式移除工具输出中指向 AI 的指令 | 解决间接提示注入攻击及当前防御误报率高问题 | AI 代理安全 |
| 26 | http://arxiv.org/abs/2510.09093v1 | Exploiting Web Search Tools of AI Agents for Data Exfiltration | 系统评估间接提示注入攻击，揭示模型工具调用漏洞 | 解决智能体使用外部工具时的数据泄露风险 | AI 安全与防御 |
| 27 | http://arxiv.org/abs/2510.09330v2 | Safety Game: Balancing Safe and Informative Conversations with Blackbox Agentic AI using LP Solvers | 提出黑盒安全对齐框架，利用线性规划求解安全与帮助平衡 | 解决推理时对齐需访问模型内部且成本高的问题 | 黑盒模型安全部署 |
| 28 | http://arxiv.org/abs/2510.09567v1 | Safe, Untrusted, ""Proof-Carrying"" AI Agents: toward the agentic lakehouse | 提出 proof-carrying 代码灵感的数据管道修复，确保不可信代理安全 | 解决数据湖屋中 AI 自动化信任与正确性担忧 | 数据工程安全 |
| 29 | http://arxiv.org/abs/2510.09781v1 | Building a Foundational Guardrail for General Agentic Systems via Synthetic Data | 提出执行前安全护栏 Safiron，合成数据训练风险检测 | 解决现有护栏多在事后执行且难以扩展的问题 | 通用智能体安全 |
| 30 | http://arxiv.org/abs/2510.10581v2 | GraphTracer: Graph-Guided Failure Tracing in LLM Agents for Robust Multi-Turn Deep Search | 构建信息依赖图追踪多智能体错误根源 | 解决多智能体深搜场景中错误归因不准问题 | 多智能体深搜系统 |
| 31 | http://arxiv.org/abs/2510.10931v2 | Proof-of-Use: Mitigating Tool-Call Hacking in Deep Research Agents | 证据 grounded RL 框架优化检索到推理因果依赖 | 解决深度研究代理中工具调用黑客与幻觉问题 | 深度研究代理 |
| 32 | http://arxiv.org/abs/2510.10937v1 | Neutral Agent-based Adversarial Policy Learning against Deep Reinforcement Learning in Multi-party Open Systems | 中性代理通过共享环境间接误导受害代理 | 解决多方开放系统中对抗攻击需直接交互问题 | 多智能体开放系统 |
| 33 | http://arxiv.org/abs/2510.10943v1 | The Social Cost of Intelligence: Emergence, Propagation, and Amplification of Stereotypical Bias in Multi-Agent Systems | 研究多智能体系统中刻板偏见涌现与传播 | 解决多智能体协作中偏见鲁棒性与放大问题 | 多智能体社会系统 |
| 34 | http://arxiv.org/abs/2510.11108v2 | A Vision for Access Control in LLM-based Agent Systems | 提出 Agent 访问控制框架，动态信息流治理 | 解决传统静态访问控制不适配动态 Agent 问题 | LLM 基于代理系统 |
| 35 | http://arxiv.org/abs/2510.11203v1 | TraceAegis: Securing LLM-Based Agents via Hierarchical and Behavioral Anomaly Detection | 基于执行迹的分层行为异常检测框架 | 解决预定义规则难覆盖复杂 Agent 异常行为问题 | LLM 基于代理安全 |
| 36 | http://arxiv.org/abs/2510.11246v1 | Collaborative Shadows: Distributed Backdoor Attacks in LLM-Based Multi-Agent Systems | 分布式后门攻击利用代理协作序列激活 | 解决多智能体系统中协作引入的新攻击面问题 | 多智能体系统安全 |
| 37 | http://arxiv.org/abs/2510.11414v1 | Uncertainty-Aware, Risk-Adaptive Access Control for Agentic Systems using an LLM-Judged TBAC Model | LLM 作为风险感知法官动态合成即时策略 | 解决新兴任务无预定义策略及访问控制管理问题 | 企业代理系统安全 |
| 38 | http://arxiv.org/abs/2510.11558v1 | Zero Data Retention in LLM-based Enterprise AI Assistants: A Comparative Study of Market Leading Agentic AI Products | 比较研究企业 AI 助手零数据保留策略架构 | 解决企业 AI 助手数据治理与合规隐私优先问题 | 企业 AI 助手 |
| 39 | http://arxiv.org/abs/2510.15739v1 | AURA: An Agent Autonomy Risk Assessment Framework | 基于gamma的风险评分方法，支持人机协同 oversight与Agent-to-Human通信 | 自主Agent系统在对齐、治理和风险管理方面的持续挑战 | 企业环境中的自主Agent部署 |
| 40 | http://arxiv.org/abs/2510.16219v2 | SentinelNet: Safeguarding Multi-Agent Collaboration Through Credit-Based Dynamic Threat Detection | 基于信用的检测器经对比学习训练，动态邻居排名抑制恶意通信 | 恶意Agent威胁多Agent系统可靠性，现有防御反应式或集中化 | 多Agent协作系统安全 |
| 41 | http://arxiv.org/abs/2510.16255v1 | Detecting Adversarial Fine-tuning with Auditing Agents | 微调审计Agent访问数据集与模型，分配风险评分检测有害微调 | 攻击者可利用微调API绕过安全防护，隐式有害数据集难检测 | LLM提供商的微调API安全审计 |
| 42 | http://arxiv.org/abs/2510.16381v1 | ATA: A Neuro-Symbolic Approach to Implement Autonomous and Trustworthy Agents | 神经符号方法解耦离线知识摄入与在线任务处理，符号决策引擎推导可靠结果 | LLM在高风险领域部署受幻觉、不稳定性和缺乏透明度阻碍 | 高风险领域的自主可信Agent |
| 43 | http://arxiv.org/abs/2510.16492v3 | Check Yourself Before You Wreck Yourself: Selectively Quitting Improves LLM Agent Safety | 使用"退出"作为行为机制，Agent在缺乏信心时识别并退出情境 | 多轮Agent场景中不确定性与模糊性累积导致严重或灾难性风险 | 高风险应用中的自主Agent |
| 44 | http://arxiv.org/abs/2510.16853v2 | Agentic Inequality | 建立分析框架界定不平等三核心维度：可用性/质量/数量差异 | 自主Agent集成到政治经济生活中，分布与能力差异将产生权力机会结果不平等 | Agent技术社会影响与治理 |
| 45 | http://arxiv.org/abs/2510.15994v1 | MCP Security Bench (MSB): Benchmarking Attacks Against Model Context Protocol in LLM Agents | 端到端评估套件测量 LLM 代理抵抗 MCP 特定攻击的能力。 | MCP 标准化工具使用但扩大了 LLM 代理的攻击面。 | 使用 MCP 的 LLM 代理 |
| 46 | http://arxiv.org/abs/2510.12985v2 | SENTINEL: A Multi-Level Formal Framework for Safety Evaluation of Foundation Model-based Embodied Agents | 多层安全评估框架，基于形式时序逻辑语义。 | 需要正式评估 FM 基具身代理的物理安全。 | 具身代理安全评估 |
| 47 | http://arxiv.org/abs/2510.13262v1 | SAJA: A State-Action Joint Attack Framework on Multi-Agent Deep Reinforcement Learning | 状态 - 动作联合攻击框架利用扰动的协同效应。 | MADRL 训练的模型易受状态和动作的对抗扰动。 | 多智能体深度强化学习安全 |
| 48 | http://arxiv.org/abs/2510.13543v1 | In-Browser LLM-Guided Fuzzing for Real-Time Prompt Injection Testing in Agentic AI Browsers | 提出浏览器内 LLM 模糊测试框架，实时发现提示注入漏洞 | 解决代理浏览器中间接提示注入攻击的安全隐患 | 代理 AI 浏览器 |
| 49 | http://arxiv.org/abs/2510.17862v1 | When "Correct" Is Not Safe: Can We Trust Functionally Correct Patches Generated by Code Agents? | 揭示功能正确但 vulnerable 的补丁威胁，提出 FCV-Attack | 解决代码智能体生成补丁的功能正确但存在安全漏洞问题 | 代码智能体 |
| 50 | http://arxiv.org/abs/2510.14008v2 | Stop Reducing Responsibility in LLM-Powered Multi-Agent Systems to Local Alignment | 主张从局部对齐转向全局系统责任，提出双视角治理框架 | 解决多智能体系统中责任归因局部化和级联不确定性风险 | LLM 多智能体系统 |
| 51 | http://arxiv.org/abs/2510.14133v1 | Formalizing the Safety, Security, and Functional Properties of Agentic AI Systems | 引入宿主智能体和任务生命周期模型，形式化定义安全属性 | 解决智能体系统通信碎片化和缺乏严谨系统属性分析的问题 | 智能体 AI 系统 |
| 52 | http://arxiv.org/abs/2510.14207v2 | Echoes of Human Malice in Agents: Benchmarking LLMs for Multi-Turn Online Harassment Attacks | 构建在线骚扰智能体基准，评估多轮交互中的越狱和毒性行为 | 解决现有越狱研究忽视多轮交互和真实骚扰动态的问题 | LLM 智能体 |
| 53 | http://arxiv.org/abs/2510.14312v1 | Terrarium: Revisiting the Blackboard for Multi-Agent Safety, Privacy, and Security Studies | 复用黑板设计构建模块化测试床，研究多智能体安全隐私威胁 | 解决 LLM 多智能体系统中 misalignment 和数据窃取等新风险 | 多智能体系统安全 |
| 54 | http://arxiv.org/abs/2510.14700v1 | LLM Agents for Automated Web Vulnerability Reproduction: Are We There Yet? | 全面评估 LLM 智能体在自动化 Web 漏洞复现中的能力和局限 | 解决复杂服务漏洞环境中智能体执行 exploit 但 fail 触发漏洞问题 | Web 漏洞复现 |
| 55 | http://arxiv.org/abs/2510.15186v1 | MAGPIE: A benchmark for Multi-AGent contextual PrIvacy Evaluation | 引入 MAGPIE 基准，评估多智能体协作场景中的隐私理解和 preservation | 解决现有隐私基准忽视多轮协作和 private 信息对任务 resolution 必要性 | 多智能体协作 |
| 56 | http://arxiv.org/abs/2510.20333v3 | GhostEI-Bench: Do Mobile Agents Resilience to Environmental Injection in Dynamic On-Device Environments? | 环境注入攻击基准+Judge-LLM细粒度失败分析 | 移动Agent易受 adversarial UI元素攻击 | Android移动Agent安全 |
| 57 | http://arxiv.org/abs/2510.21236v2 | Securing AI Agent Execution | AgentBound访问控制框架+声明式策略机制 | MCP服务器无限制访问造成攻击面 | AI Agent执行安全 |
| 58 | http://arxiv.org/abs/2510.21524v1 | EU-Agent-Bench: Measuring Illegal Behavior of LLM Agents Under EU Law | 欧盟法律合规基准+可验证人工策划 | LLM Agent可能采取非法行为缺乏评估 | 欧盟法律合规场景 |
| 59 | http://arxiv.org/abs/2510.17017v3 | SafeSearch: Do Not Trade Safety for Utility in LLM Search Agents | 多目标强化学习，结合输出安全奖励与查询级塑造项。 | 解决搜索智能体因检索外部信息而降低安全阈值产生有害输出的问题。 | LLM 搜索智能体安全 |
| 60 | http://arxiv.org/abs/2510.17276v2 | Breaking and Fixing Defenses Against Control-Flow Hijacking in Multi-Agent Systems | 提出 ControlValve 防御，生成许可控制流图并强制执行合规。 | 解决多智能体系统中控制流劫持攻击及现有防御定义脆弱的问题。 | 多智能体系统安全 |
| 61 | http://arxiv.org/abs/2510.17306v2 | ATL*AS: An Automata-Theoretic Approach and Tool for the Verification of Strategic Abilities in Multi-Agent Systems | 新颖符号算法模型检查 ATL*，基于奇偶博弈的无限迹验证。 | 解决多智能体系统战略能力验证的可扩展性与效率问题。 | 多智能体系统形式化验证 |
| 62 | http://arxiv.org/abs/2510.17431v1 | Agentic Reinforcement Learning for Search is Unsafe | 揭示 RL 训练搜索模型的安全脆弱性，提出安全感知 RL 管道需求。 | 解决 Agentic RL 搜索模型因奖励有效查询而忽略有害性的安全漏洞。 | 搜索智能体安全 |
| 63 | http://arxiv.org/abs/2510.18003v1 | BadScientist: Can a Research Agent Write Convincing but Unsound Papers that Fool LLM Reviewers? | 评估 fabrication-oriented 论文生成智能体欺骗多模型 LLM 评审系统的能力。 | 解决 AI 生成研究由 AI 评审无监督导致的自动出版循环漏洞。 | 科学出版安全 |
| 64 | http://arxiv.org/abs/2510.18113v1 | Investigating the Impact of Dark Patterns on LLM-Based Web Agents | 首次研究 dark patterns 对 LLM 通用 web 智能体决策过程的影响。 | 解决 dark patterns 对自动化 web 任务智能体潜在有害影响未探索的问题。 | Web 智能体安全 |
| 65 | http://arxiv.org/abs/2510.18123v1 | SafeCoop: Unravelling Full Stack Safety in Agentic Collaborative Driving | 提出 SafeCoop 防御管道，集成语义防火墙及多源共识。 | 解决自然语言协作驾驶中消息丢失、幻觉及对抗攻击等新漏洞。 | 协作驾驶系统安全 |
| 66 | http://arxiv.org/abs/2510.18131v1 | BlueCodeAgent: A Blue Teaming Agent Enabled by Automated Red Teaming for CodeGen AI | 端到端 blue teaming 智能体，利用 red teaming 生成风险实例增强防御。 | 解决 CodeGen 模型 blue teaming 进展有限及缺乏有效语义理解的问题。 | 代码生成安全 |
| 67 | http://arxiv.org/abs/2510.18314v1 | Genesis: Evolving Attack Strategies for LLM Web Agent Red-Teaming | 三模块框架，Attacker 结合遗传算法，Strategist 动态发现有效策略。 | 解决现有 web 智能体攻击依赖手工策略或静态模型难以泛化的问题。 | Web 智能体红队测试 |
| 68 | http://arxiv.org/abs/2511.05511v1 | From Failure Modes to Reliability Awareness in Generative and Agentic AI System | 提出11层故障栈和意识映射框架，量化可靠性风险 | Agent系统故障传播与级联效应，缺乏可靠性评估 | 任务关键领域的生成式和Agentic AI系统 |
| 69 | http://arxiv.org/abs/2510.22620v2 | Breaking Agent Backbones: Evaluating the Security of Backbone LLMs in AI Agents | 提出威胁快照框架和b³安全基准(19万+攻击) | 缺乏骨干LLM对Agent安全影响的系统理解 | AI Agent开发者与LLM提供商 |
| 70 | http://arxiv.org/abs/2510.22963v3 | CompressionAttack: Exploiting Prompt Compression as a New Attack Surface in LLM-Powered Agents | 首個利用提示压缩攻击的框架(HardCom/SoftCom) | 提示压缩模块引入新安全攻击面 | LLM驱动的智能体系统 |
| 71 | http://arxiv.org/abs/2510.23675v3 | QueryIPI: Query-agnostic Indirect Prompt Injection on Coding Agents | 查询无关间接提示注入攻击，利用不变提示上下文 | 现有IPI需特定查询触发，泛化性差 | IDE集成编码Agent |
| 72 | http://arxiv.org/abs/2510.18563v1 | The Trust Paradox in LLM-Based Multi-Agent Systems: When Collaboration Becomes a Security Vulnerability | 形式化信任 - 脆弱性悖论，提出统一指标检测边界违规 | 解决多智能体协作中信任增加导致安全风险的问题 | 多智能体系统安全设计 |
| 73 | http://arxiv.org/abs/2510.19324v1 | Authorization of Knowledge-base Agents in an Intent-based Management Function | 集成上下文与功能属性，实现动态策略驱动的访问控制 | 解决动态多租户环境中智能体授权缺乏灵活性的问题 | 6G 意图_based 网络管理 |
| 74 | http://arxiv.org/abs/2510.19420v1 | Monitoring LLM-based Multi-Agent Systems Against Corruptions via Node Evaluation | 提出动态防御范式，持续监控通信并调整图拓扑 | 解决多智能体系统易受动态腐败攻击且静态防御不足的问题 | 多智能体系统安全防护 |
| 75 | http://arxiv.org/abs/2510.19738v2 | Misalignment Bounty: Crowdsourcing AI Agent Misbehavior | 众包收集智能体追求 unintended 或 unsafe 目标的案例 | 解决缺乏清晰可复现的 AI 系统 misalignment 示例的问题 | AI 安全与对齐研究 |
| 76 | http://arxiv.org/abs/2510.19973v3 | A Tutorial on Cognitive Biases in Agentic AI-Driven 6G Autonomous Networks | 提供认知偏差教程，分类定义并提出针对电信系统的缓解策略 | 解决 agentic AI 部署中 inherited 认知偏差扭曲决策的问题 | 6G 自主网络管理 |
| 77 | http://arxiv.org/abs/2510.23883v2 | Agentic AI Security: Threats, Defenses, Evaluation, and Open Challenges | 概述代理 AI 特定威胁分类法， review 基准与防御策略。 | 解决自主执行任务带来的新放大安全风险问题。 | 通用代理 AI 系统安全 |
| 78 | http://arxiv.org/abs/2510.24383v1 | Policy Cards: Machine-Readable Runtime Governance for Autonomous AI Agents | 引入机器可读策略卡，编码运行时操作、监管与伦理约束。 | 解决自主智能体部署层缺乏标准化约束与可验证合规问题。 | 自主 AI 智能体治理与合规 |
| 79 | http://arxiv.org/abs/2510.24411v2 | OS-Sentinel: Towards Safety-Enhanced Mobile GUI Agents via Hybrid Validation in Realistic Workflows | 结合形式验证器与 VLM 上下文判断，检测移动环境安全风险。 | 解决移动环境中智能体不安全操作检测挑战问题。 | 移动 GUI 智能体安全 |
| 80 | http://arxiv.org/abs/2510.24476v1 | Mitigating Hallucination in Large Language Models (LLMs): An Application-Oriented Survey on RAG, Reasoning, and Agentic Systems | 分析 RAG、推理增强及其在代理系统中整合如何缓解幻觉。 | 解决现实应用中 LLM 幻觉阻碍可靠部署问题。 | 通用 LLM 应用与代理系统 |
| 81 | http://arxiv.org/abs/2511.10649v1 | Towards Assume-Guarantee Verification of Abilities in Stochastic Multi-Agent Systems | 提出假设 - 保证验证方案，分解随机环境中不完美信息代理问题。 | 解决战略能力模型检查在随机环境中难问题。 | 随机多智能体系统验证 |
| 82 | http://arxiv.org/abs/2510.26352v2 | Agent Skills Enable a New Class of Realistic and Trivially Simple Prompt Injections | 揭示Agent Skills框架的提示注入漏洞 | Agent Skills持续学习机制的安全性问题 | 前沿LLM编码Agent |
| 83 | http://arxiv.org/abs/2510.26702v1 | Delegated Authorization for Agents Constrained to Semantic Task-to-Scope Matching | 语义检查访问请求，发布限制于最小权限范围的访问令牌 | Agent动态调用工具权限过宽超出任务范围 | 多Agent和工具增强应用授权 |
| 84 | http://arxiv.org/abs/2510.26752v2 | The Oversight Game: Learning to Cooperatively Balance an AI Agent's Safety and Autonomy | 两玩家马尔可夫博弈建模人机控制，证明对齐保证 | 部署能力强Agent时保留人类控制权 | 开放环境中的Agent工具使用任务 |
| 85 | http://arxiv.org/abs/2510.27016v1 | Semantically-Aware LLM Agent to Enhance Privacy in Conversational AI Services | LOPSIDED框架动态替换PII为语义一致假名，保持上下文完整性 | 对话AI中敏感个人信息泄露风险 | 远程LLM对话服务 |
| 86 | http://arxiv.org/abs/2510.27275v1 | Prevalence of Security and Privacy Risk-Inducing Usage of AI-based Conversational Agents | 调查3270名英国成人对话Agent使用中的安全隐私风险行为 | 用户无意中引入风险行为程度不明 | 对话Agent（ChatGPT、Gemini等） |
| 87 | http://arxiv.org/abs/2511.10650v1 | Unsupervised Cycle Detection in Agentic Applications | 无监督循环检测框架：结构+语义分析结合 | Agent应用非确定性行为形成隐藏执行循环消耗资源 | LangGraph股票市场应用 |
| 88 | http://arxiv.org/abs/2510.27623v3 | BEAT: Visual Backdoor Attacks on VLM-based Embodied Agents via Contrastive Trigger Learning | 首个视觉后门攻击框架，对比触发学习精确激活后门 | VLM具身Agent视觉驱动开辟新攻击面 | VLM具身Agent |
| 89 | http://arxiv.org/abs/2510.25179v1 | Agentic Moderation: Multi-Agent Design for Safer Vision-Language Models | 动态协作 Agent 框架（Shield/Responder 等）防御越狱攻击 | 静态安全层缺乏上下文感知与可解释性的问题 | 多模态大模型安全对齐 |
| 90 | http://arxiv.org/abs/2510.25612v1 | Counterfactual-based Agent Influence Ranker for Agentic AI Workflows | 基于反事实分析评估 Agent 对工作流输出的影响 | 缺乏方法评估多 Agent 系统中单个 Agent 影响力 | 工作流质量与安全分析 |
| 91 | http://arxiv.org/abs/2510.25819v1 | Identity Management for Agentic AI: The new frontier of authorization, authentication, and security for an AI agent world | 针对自主 Agent 的身份管理与授权战略议程 | 自主 Agent 规模化访问控制与身份管理挑战 | AI Agent 安全基础设施 |
| 92 | http://arxiv.org/abs/2510.25863v2 | AAGATE: A NIST AI RMF-Aligned Governance Platform for Agentic AI | operationalize NIST AI RMF 的 Kubernetes 原生控制平面 | 传统 AppSec 工具不适用于即兴、机器速度系统 | 生产环境 Agentic AI 治理 |
| 93 | http://arxiv.org/abs/2510.25941v3 | RECAP: Reproducing Copyrighted Data from LLMs Training with an Agentic Pipeline | 反馈驱动循环 eliciting 并验证 memorized 训练数据 | 无法 inspect 训练数据导致版权风险未知的问题 | LLM 训练数据版权审计 |
| 94 | http://arxiv.org/abs/2510.26037v1 | SIRAJ: Diverse and Efficient Red-Teaming for LLM Agents via Distilled Structured Reasoning | 动态两步过程生成多样种子测试 case 并迭代攻击 | LLM Agent 规划与工具调用暴露新安全风险 | LLM Agent 红队测试 |
| 95 | http://arxiv.org/abs/2510.26212v1 | Who Grants the Agent Power? Defending Against Instruction Injection via Task-Centric Access Control | 运行时任务中心访问控制框架 enforce 动态权限 | 过度特权静态权限导致 instruction injection 漏洞 | 移动任务自动化安全 |

[返回目录](#目录)

<a id="cat-05"></a>

## Agent记忆与知识管理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2510.04851v1 | LEGOMem: Modular Procedural Memory for Multi-agent LLM Systems for Workflow Automation | 提出模块化过程记忆框架，分解任务轨迹为可重用单元，灵活分配给编排者与任务代理 | 解决多智能体系统中记忆放置与检索设计问题，提升规划与执行准确性 | 工作流自动化多智能体系统 |
| 2 | http://arxiv.org/abs/2510.05520v1 | CAM: A Constructivist View of Agentic Memory for LLM-Based Reading Comprehension | 开发 CAM 原型，体现结构性、灵活性与动态性，增量重叠聚类算法构建结构化记忆 | 解决 LLM 理解长文档时信息量过大，缺乏系统记忆设计原则的问题 | 长文本阅读理解任务 |
| 3 | http://arxiv.org/abs/2510.00615v2 | ACON: Optimizing Context Compression for Long-horizon LLM Agents | 压缩指南优化+蒸馏到小模型，分析失败原因更新压缩策略 | 长周期任务中上下文增长导致成本高效率低，现有压缩聚焦单步任务 | AppWorld、OfficeBench等长周期任务 |
| 4 | http://arxiv.org/abs/2510.03323v1 | Graph-S3: Enhancing Agentic textual Graph Retrieval with Synthetic Stepwise Supervision | 合成逐步监督训练LLM检索器，基于离线提取黄金子图评估每步 | 文本图QA中图检索性能差，依赖浅层嵌入相似或交互策略标注成本高 | 文本图问答系统 |
| 5 | http://arxiv.org/abs/2510.04195v1 | Constructing coherent spatial memory in LLM agents through graph rectification | 提出基于版本控制的图修复框架，检测并纠正导航图结构不一致 | 解决 LLM 代理在长环境中构建空间记忆时出现结构冲突的问题 | LLM 驱动的空间导航与地图构建 |
| 6 | http://arxiv.org/abs/2510.04373v2 | JEF-Hinter: Leveraging Offline Knowledge for Improving Web Agents Adaptation | 提出 JEF-Hinter，将离线轨迹提炼为紧凑提示，利用成功与失败数据 | 解决不熟悉领域改进代理需昂贵在线交互或微调及 catastrophic forgetting 问题 | Web 代理跨领域适应与优化 |
| 7 | http://arxiv.org/abs/2510.04391v4 | Offline World Models as Imagination Networks in Cognitive Agents | 运用心理网络分析比较人类与 LLM 的离线世界模型结构一致性 | 解决生物与人工系统如何组织内部表征及想象力计算角色的争议 | 认知代理内部世界模型评估 |
| 8 | http://arxiv.org/abs/2510.04618v2 | Agentic Context Engineering: Evolving Contexts for Self-Improving Language Models | 提出 ACE 框架，将上下文视为 evolving playbooks，积累 refine 策略 | 解决上下文适应中 brevity bias 及 iterative rewriting 导致细节 erosion 问题 | 代理与领域特定推理上下文优化 |
| 9 | http://arxiv.org/abs/2510.06664v1 | ToolMem: Enhancing Multimodal Agents with Learnable Tool Capability Memory | 使代理从交互中学习工具能力记忆，优化推理时工具选择 | 解决代理依赖固定工具无法灵活适配特定任务场景的问题 | 多模态工具使用 |
| 10 | http://arxiv.org/abs/2510.07925v1 | Enabling Personalized Long-term Interactions in LLM-based Agents through Persistent Memory and User Profiles | 整合持久记忆与动态用户画像，实现个性化长期交互 | 解决当前代理缺乏结合上下文与用户特定数据机制的问题 | 个性化交互代理 |
| 11 | http://arxiv.org/abs/2510.08149v1 | AI Knowledge Assist: An Automated Approach for the Creation of Knowledge Bases for Conversational AI Agents | 从历史对话提取 QA 对自动构建知识库，消除冷启动 gap | 解决联络中心缺乏公司特定知识库阻碍 AI 集成问题 | 对话式 AI 客服 |
| 12 | http://arxiv.org/abs/2510.09038v1 | Auto-scaling Continuous Memory for GUI Agent | 提出连续记忆机制，将GUI轨迹编码为固定长度嵌入，降低上下文成本 | 解决文本记忆上下文过长及丢失视觉细节的问题 | GUI 自动化任务 |
| 13 | http://arxiv.org/abs/2510.09720v1 | Preference-Aware Memory Update for Long-Term LLM Agents | 结合滑动窗口与指数移动平均，动态细化偏好记忆表示 | 解决长期记忆中用户偏好动态变化难以捕捉的问题 | 长期对话与个性化交互 |
| 14 | http://arxiv.org/abs/2510.11588v1 | Analyzing and Internalizing Complex Policy Documents for LLM Agents | 类别感知策略持续预训练内部化复杂策略文档 | 解决策略文档扩展导致计算开销高及推理难问题 | LLM 代理策略内部化 |
| 15 | http://arxiv.org/abs/2510.16392v2 | RGMem: Renormalization Group-inspired Memory Evolution for Language Agents | 重正化群启发的多尺度记忆演化，分层粗化与阈值更新动态演化用户画像 | 有限上下文窗口与静态参数记忆阻碍长期跨会话用户状态建模 | 个性化对话Agent |
| 16 | http://arxiv.org/abs/2510.11892v2 | R-WoM: Retrieval-augmented World Model For Computer-use Agents | 通过检索外部教程知识增强 LLM 世界模型仿真。 | LLM 幻觉和静态知识依赖抑制长程仿真。 | 计算机使用代理 |
| 17 | http://arxiv.org/abs/2510.11967v1 | Scaling Long-Horizon LLM Agent via Context-Folding | 代理主动管理工作上下文，通过分支和折叠压缩中间步骤。 | 长程任务中 LLM 代理受上下文长度限制。 | 长程 LLM 代理任务 |
| 18 | http://arxiv.org/abs/2510.12635v2 | Memory as Action: Autonomous Context Curation for Long-Horizon Agentic Tasks | 将工作记忆管理视为可学习策略动作，通过 RL 优化。 | 长上下文 LLM 需要仔细管理工作记忆以减轻注意力稀释。 | 长程代理任务 |
| 19 | http://arxiv.org/abs/2510.14303v2 | Constraint-Driven Small Language Models Based on Agent and OpenAlex Knowledge Graph: Mining Conceptual Pathways and Discovering Innovation Points in Academic Papers | 基于 OpenAlex KG 构建智能体，利用约束机制增强概念路径分析 | 解决学术论文分析中概念关系网络探索不足和关键概念提取难 | 学术论文分析 |
| 20 | http://arxiv.org/abs/2510.15258v2 | Multi-dimensional Data Analysis and Applications Basing on LLM Agents and Knowledge Graph Interactions | 提出基于 LLM 智能体和 KG 交互的多维数据分析方法，构建动态生态 | 解决 LLM 处理 structured 知识 hallucination 和 KG 静态限制动态交互 | 多维数据分析 |
| 21 | http://arxiv.org/abs/2510.15261v1 | AUGUSTUS: An LLM-Driven Multimodal Agent System with Contextualized User Memory | 提出多模态智能体系统，利用 graph-structured multimodal contextual memory | 解决现有 agent 系统忽视 multimodal 信号和 text-only 记忆局限性 | 多模态智能体系统 |
| 22 | http://arxiv.org/abs/2510.21413v4 | Context Engineering for AI Agents in Open-Source Software | AGENTS.md上下文文件采用实证研究 | 开发者如何为Agent提供项目上下文未知 | 开源软件Agent开发 |
| 23 | http://arxiv.org/abs/2510.18395v1 | Memory-Augmented State Machine Prompting: A Novel LLM Agent Framework for Real-Time Strategy Games | 集成状态机提示与记忆机制，统一结构化动作与长期战术连贯性。 | 解决现有方法中幻觉及决策碎片化导致缺乏长期战术连贯性的问题。 | 实时策略游戏智能体 |
| 24 | http://arxiv.org/abs/2510.22732v2 | WebATLAS: An LLM Agent with Experience-Driven Memory and Action Simulation | 经验驱动记忆+前瞻动作模拟，无需网站微调 | LLM Web Agent长程导航效率低、新网站适应差 | 自主Web导航任务 |
| 25 | http://arxiv.org/abs/2510.23010v2 | TALM: Dynamic Tree-Structured Multi-Agent Framework with Long-Term Memory for Scalable Code Generation | 树状协作结构+长期记忆模块支持语义查询 | 多Agent框架工作流僵化、推理恢复成本高 | 复杂代码生成任务 |
| 26 | http://arxiv.org/abs/2510.19897v1 | Learning from Supervision with Semantic and Episodic Memory: A Reflective Approach to Agent Adaptation | 利用 episodic 与 semantic 记忆存储 critique，无需参数更新学习 | 解决微调成本高且不灵活，RAG 仅依赖标签的问题 | 自适应分类任务智能体 |
| 27 | http://arxiv.org/abs/2510.24168v1 | MGA: Memory-Driven GUI Agent for Observation-Centric Interaction | 以“先观察后决策”为原则，建模为独立上下文丰富环境状态。 | 解决依赖历史轨迹导致错误传播与局部探索偏差问题。 | 桌面与 Web 界面导航交互 |
| 28 | http://arxiv.org/abs/2510.24699v1 | AgentFold: Long-Horizon Web Agents with Proactive Context Management | 主动管理上下文，执行折叠操作以浓缩或抽象历史轨迹。 | 解决长程任务中上下文饱和与关键细节丢失权衡问题。 | 长程 Web 信息寻求任务 |
| 29 | http://arxiv.org/abs/2510.27418v1 | Dynamic Affective Memory Management for Personalized LLM Agents | 贝叶斯启发记忆更新算法，最小化全局熵动态更新记忆向量数据库 | 个性化外部记忆数据库冗余、过时、上下文整合差 | 情感场景个性化LLM Agent |
| 30 | http://arxiv.org/abs/2510.27569v1 | MARAG-R1: Beyond Single Retriever via Reinforcement-Learned Multi-Tool Agentic Retrieval | 强化学习多工具RAG框架，动态协调四种检索工具 | 单检索器固定top-k选择限制信息获取 | 语料级推理任务 |

[返回目录](#目录)

<a id="cat-06"></a>

## Agent评测与基准

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2510.04852v2 | FreshBrew: A Benchmark for Evaluating AI Agents on Java Code Migration | 引入 FreshBrew 基准，评估 AI 代理在项目级 Java 迁移中保留语义及避免奖励黑客的能力 | 解决缺乏系统评估 AI 驱动代码迁移有效性的问题，揭示失败模式 | Java 代码库现代化迁移 |
| 2 | http://arxiv.org/abs/2510.04980v1 | LLM-Hanabi: Evaluating Multi-Agent Gameplays with Theory-of-Mind and Rationale Inference in Imperfect Information Collaboration Game | 引入 LLM-Hanabi 基准，使用合作游戏评估 LLM 的理由推断与心理理论能力 | 解决动态协作设置中 LLM 推断他人理由能力未被充分探索的问题 | 多智能体协作能力评估 |
| 3 | http://arxiv.org/abs/2510.06288v1 | BuilderBench -- A benchmark for generalist agents | 引入 BuilderBench 基准，要求代理学习如何用方块构建任何结构，测试具身推理 | 解决缺乏 scalable 学习机制开发通过交互学习代理的问题 | 通用智能体预训练研究 |
| 4 | http://arxiv.org/abs/2510.00415v2 | Towards Self-Evolving Benchmarks: Synthesizing Agent Trajectories via Test-Time Exploration under Validate-by-Reproduce Paradigm | TRACE框架通过测试时探索自动生成更高难度任务及可验证轨迹 | 现有Agent基准快速达到上限，难以评估新Agent能力 | GAIA、AIME等Agent基准 |
| 5 | http://arxiv.org/abs/2510.00496v3 | Agent-ScanKit: Unraveling Memory and Reasoning of Multimodal Agents via Sensitivity Perturbations | 视觉/文本/结构三正交探测范式，量化记忆与推理贡献无需访问模型内部 | 多模态Agent在复杂任务中可靠性有限，是否存在虚假推理 | 18个多模态GUI Agent |
| 6 | http://arxiv.org/abs/2510.00507v3 | Graph2Eval: Automatic Multimodal Task Generation for Agents via Knowledge Graphs | 知识图谱驱动的任务生成框架，含子图采样和多阶段过滤确保任务可解性 | LLM生成任务存在语义不一致和可解性问题，静态数据集扩展性有限 | RAG Agent、Web Agent |
| 7 | http://arxiv.org/abs/2510.01295v1 | The Social Laboratory: A Psychometric Framework for Multi-Agent LLM Evaluation | 多Agent辩论作为"社会实验室"，含心理测量和语义指标套件 | 传统基准无法捕捉Agent交互中涌现的社会和认知动态 | 多Agent LLM评估 |
| 8 | http://arxiv.org/abs/2510.01051v2 | GEM: A Gym for Agentic LLMs | GEM环境模拟器提供标准环境-Agent接口，含异步向量化执行和灵活封装 | LLM训练从静态数据集转向基于经验学习，缺乏标准化框架 | 24个环境的Agent LLM训练评估 |
| 9 | http://arxiv.org/abs/2510.01353v1 | MEMTRACK: Evaluating Long-Term Memory and State Tracking in Multi-Platform Dynamic Agent Environments | 整合Slack/Linear/Git多平台异步事件，测试记忆获取选择和冲突解决 | 现有基准聚焦对话实例，缺乏动态企业环境中记忆评估 | 多平台动态Agent环境 |
| 10 | http://arxiv.org/abs/2510.01654v1 | SoK: Measuring What Matters for Closed-Loop Security Agents | CLASP框架对齐安全生命周期与核心Agent能力，定义CLC分数量化闭环程度和 operational有效性 | 网络安全研究工具碎片化，缺乏闭环Agent评估框架和性能基准 | 21个代表性安全系统 |
| 11 | http://arxiv.org/abs/2510.03984v1 | Beyond Static Evaluation: Rethinking the Assessment of Personalized Agent Adaptability in Information Retrieval | 提出基于角色模拟与结构化 elicitation 的动态个性化代理评估框架 | 解决静态基准无法反映用户需求 evolve 及代理长期适应性的问题 | 个性化信息检索系统评估 |
| 12 | http://arxiv.org/abs/2510.04311v1 | On the Importance of Task Complexity in Evaluating LLM-Based Multi-Agent Systems | 提出基于深度与宽度的任务复杂度理论框架，评估多代理系统有效性 | 解决缺乏系统实验设计限制多代理系统结论强度与通用性的问题 | LLM 多代理系统任务评估 |
| 13 | http://arxiv.org/abs/2510.04491v2 | Impatient Users Confuse AI Agents: High-fidelity Simulations of Human Traits for Testing Agents | 提出 TraitBasis，学习激活空间方向以模拟用户特质进行压力测试 | 解决现有基准无法捕捉代理对用户行为变化脆弱性的鲁棒性测试缺口 | AI 代理鲁棒性与压力测试 |
| 14 | http://arxiv.org/abs/2510.04550v2 | TRAJECT-Bench:A Trajectory-Aware Benchmark for Evaluating Agentic Tool Use | 提出 TRAJECT-Bench，通过细粒度指标评估工具使用轨迹而非仅最终答案 | 解决现有工作忽略工具选择、参数化及排序正确性的评估盲区 | 代理工具使用能力综合评估 |
| 15 | http://arxiv.org/abs/2510.06800v2 | FURINA: A Fully Customizable Role-Playing Benchmark via Scalable Multi-Agent Collaboration Pipeline | 提出多代理协作流水线，自动构建可定制角色扮演基准 | 解决现有角色扮演基准范围窄、范式旧及适应性差的问题 | 角色扮演任务 |
| 16 | http://arxiv.org/abs/2510.07172v3 | NewtonBench: Benchmarking Generalizable Scientific Law Discovery in LLM Agents | 引入反事实定律移位生成可扩展问题，评估交互式模型发现 | 解决现有基准在科学相关性、扩展性与抗记忆化间的权衡 | 科学定律发现 |
| 17 | http://arxiv.org/abs/2510.07309v4 | Agent Bain vs. Agent McKinsey: A New Text-to-SQL Benchmark for the Business Domain | 引入 CORGI 基准，扩展 Text-to-SQL 至预测与推荐类业务查询 | 解决现有基准仅测试简单数据访问无法反映真实业务需求问题 | 业务领域 Text-to-SQL |
| 18 | http://arxiv.org/abs/2510.07414v2 | Haystack Engineering: Context Engineering for Heterogeneous and Agentic Long-Context Evaluation | 构建 HaystackCraft 基准，模拟代理工作流中的噪声长上下文 | 解决合成 NIAH 基准忽略检索偏差与代理级联错误问题 | 长上下文评估 |
| 19 | http://arxiv.org/abs/2510.07505v4 | PEAR: Planner-Executor Agent Robustness Benchmark | 系统评估规划器 - 执行器多代理系统的效用与脆弱性 | 解决现有研究缺乏对多代理系统漏洞 holistic 理解问题 | 规划器 - 执行器架构 |
| 20 | http://arxiv.org/abs/2510.07978v3 | VoiceAgentBench: Are Voice Assistants ready for agentic tasks? | 构建包含 6000+ 查询的综合基准，评估语音代理代理行为 | 解决现有语音基准缺乏系统性代理行为及对抗鲁棒性评估 | 语音助手代理 |
| 21 | http://arxiv.org/abs/2510.08173v2 | NavSpace: How Navigation Agents Follow Spatial Intelligence Instructions | 引入 NavSpace 基准，系统评估导航代理空间感知与推理能力 | 解决现有基准忽视导航代理空间智能系统性评估的问题 | 具身导航代理 |
| 22 | http://arxiv.org/abs/2510.08847v1 | What Is Your Agent's GPA? A Framework for Evaluating Agent Goal-Plan-Action Alignment | 提出 Agent GPA 框架，基于目标 - 计划 - 行动循环评估对齐 | 解决代理失败覆盖不全及错误定位困难的问题 | 通用代理评估 |
| 23 | http://arxiv.org/abs/2510.08996v4 | Saving SWE-Bench: A Benchmark Mutation Approach for Realistic Agent Evaluation | 基准突变方法转换正式基准为现实用户查询，评估聊天代理 | 解决现有基准高估代理能力及与 IDE 交互不匹配问题 | 软件工程代理 |
| 24 | http://arxiv.org/abs/2510.09116v2 | DITING: A Multi-Agent Evaluation Framework for Benchmarking Web Novel Translation | 提出多智能体评估框架 AgentEval，模拟专家审议评估翻译质量 | 解决现有指标无法捕捉网文翻译叙事与文化保真度的问题 | 机器翻译评估 |
| 25 | http://arxiv.org/abs/2510.10073v1 | SecureWebArena: A Holistic Security Evaluation Benchmark for LVLM-based Web Agents | 首个 holistic 基准，涵盖六类攻击向量与多层评估协议 | 解决现有安全基准覆盖窄且无法捕捉广泛漏洞问题 | Web 智能体安全 |
| 26 | http://arxiv.org/abs/2510.10117v1 | DixitWorld: Evaluating Multimodal Abductive Reasoning in Vision-Language Models with Multi-Agent Dixit Gameplay | 动态多智能体环境评估假设生成与选择，揭示创造力与判别权衡 | 解决多模态溯因推理评估局限于静态单智能体任务问题 | 视觉语言模型 |
| 27 | http://arxiv.org/abs/2510.10185v1 | MedAgentAudit: Diagnosing and Quantifying Collaborative Failure Modes in Medical Multi-Agent Systems | 大规模实证研究，分类医疗多智能体协作失败模式 | 解决仅关注最终答案准确性而忽视推理过程可信度问题 | 医疗 AI 系统 |
| 28 | http://arxiv.org/abs/2510.10472v2 | FML-bench: Benchmarking Machine Learning Agents for Scientific Research | 包含 8 项 ML 研究任务，提出探索多样性等互补指标 | 解决现有基准忽视代理研究过程及科学设置能力评估问题 | 科学研究智能体 |
| 29 | http://arxiv.org/abs/2510.15974v1 | Limits of Emergent Reasoning of Large Language Models in Agentic Frameworks for Deterministic Games | 提供环境接口分析 LLM 在确定性游戏中的推理极限 | 解决任务性质混淆真实推理能力评估的问题 | 确定性游戏推理 |
| 30 | http://arxiv.org/abs/2510.10885v1 | Rethinking Agentic Workflows: Evaluating Inference-Based Test-Time Scaling Strategies in Text2SQL Tasks | 基准测试轻量级推理时缩放策略在 Text2SQL 表现 | 解决推理模型在实际应用中有效性不确定问题 | Text2SQL 系统部署 |
| 31 | http://arxiv.org/abs/2510.10909v4 | PaperArena: An Evaluation Benchmark for Tool-Augmented Agentic Reasoning on Scientific Literature | 基准评估跨论文推理与多工具编排能力 | 解决缺乏真实研究场景跨论文推理基准问题 | 科学文献理解 |
| 32 | http://arxiv.org/abs/2510.11035v2 | SusBench: An Online Benchmark for Evaluating Dark Pattern Susceptibility of Computer-Use Agents | 在线基准评估计算机使用代理对 UI 暗模式易感性 | 解决自主代理易受操纵性界面设计影响问题 | 计算机使用代理 |
| 33 | http://arxiv.org/abs/2510.11098v4 | VCB Bench: An Evaluation Benchmark for Audio-Grounded Large Language Model Conversational Agents | 高质量中文基准评估音频大模型对话代理 | 解决现有基准依赖合成语音及维度单一问题 | 音频对话代理 |
| 34 | http://arxiv.org/abs/2510.11608v2 | ParaCook: On Time-Efficient Planning for Multi-Agent Systems | 时间高效协作规划基准，隔离战略并行规划挑战 | 解决现有基准忽视并行异步操作时间效率问题 | 多智能体系统规划 |
| 35 | http://arxiv.org/abs/2510.16263v2 | NEBULA: Do We Evaluate Vision-Language-Action Agents Correctly? | 双轴评估协议结合细粒度能力测试与系统压力测试 | VLA Agent评估受粗略端到端任务成功指标阻碍，无法精确诊断技能 | 单臂操作VLA Agent评估 |
| 36 | http://arxiv.org/abs/2510.11695v2 | When Agents Trade: Live Multi-Market Trading Benchmark for LLM Agents | 首个终身、实时基准，评估多市场 LLM 交易代理。 | 缺乏验证数据且测试周期有限， unclear 代理实时适应能力。 | 金融交易代理评估 |
| 37 | http://arxiv.org/abs/2510.11977v1 | Holistic Agent Leaderboard: The Missing Infrastructure for AI Agent Evaluation | 标准化评估 harness， orchestrate 跨数百 VM 的并行评估。 | 代理评估挑战 undermining 对代理性能的理解。 | AI 代理评估基础设施 |
| 38 | http://arxiv.org/abs/2510.11997v3 | SAGE: A Top-Down Bottom-Up Knowledge-Grounded User Simulator for Multi-turn AGent Evaluation | 用户模拟框架整合自上而下业务逻辑和自下而上知识。 | 多轮交互代理评估需要人工评估，挑战大。 | 多轮交互代理评估 |
| 39 | http://arxiv.org/abs/2510.12200v1 | HackWorld: Evaluating Computer-Use Agents on Exploiting Web Application Vulnerabilities | 首个系统评估 CUA 通过视觉交互利用 Web 漏洞的框架。 | CUA 通过图形界面发现和利用漏洞的能力未探索。 | 计算机使用代理安全评估 |
| 40 | http://arxiv.org/abs/2510.13910v1 | RAGCap-Bench: Benchmarking Capabilities of LLMs in Agentic Retrieval Augmented Generation Systems | 面向能力的基准，细粒度评估代理 RAG 工作流中的中间任务。 | 代理 RAG 系统难以处理挑战性多跳问题和中间推理。 | 代理 RAG 系统 |
| 41 | http://arxiv.org/abs/2510.13936v2 | FinDeepResearch: Evaluating Deep Research Agents in Rigorous Financial Analysis | 提出 HisRubric 评估框架和 FinDeepResearch 基准，涵盖多市场财务分析 | 缺乏对深度研究智能体在金融分析能力的严谨评估 | 深度研究智能体 |
| 42 | http://arxiv.org/abs/2510.14621v1 | ColorBench: Benchmarking Mobile Agents with Graph-Structured Framework for Complex Long-Horizon Tasks | 引入图结构化基准框架，模拟动态行为以评估复杂长程移动任务 | 解决现有移动智能体评估标准离线静态和在线动态测试的不足 | 移动智能体 |
| 43 | http://arxiv.org/abs/2510.14727v1 | The Pursuit of Diversity: Multi-Objective Testing of Deep Reinforcement Learning Agents | 提出 INDAGO-Nexus 多目标搜索方法，联合优化失败可能性和场景多样性 | 解决现有 DRL 测试工具忽视场景多样性和 distinct 错误类型问题 | 深度强化学习智能体 |
| 44 | http://arxiv.org/abs/2510.20168v1 | DeepWideSearch: Benchmarking Depth and Width in Agentic Information Seeking | 首个深度+宽度信息搜索基准测试 | 现有Agent无法同时执行深度推理和广度收集 | 市场分析和商业开发场景 |
| 45 | http://arxiv.org/abs/2510.21031v1 | AgentArcEval: An Architecture Evaluation Method for Foundation Model based Agents | 专为FM-Agent设计的架构评估方法+场景目录 | 传统评估方法无法应对Agent独特特性 | 基础模型Agent架构评估 |
| 46 | http://arxiv.org/abs/2510.21244v2 | VoiceAgentEval: A Dual-Dimensional Benchmark for Expert-Level Intelligent Voice-Agent Evaluation of Xbench's Professional-Aligned Series | 六领域30场景+大模型驱动用户模拟器 | 现有语音Agent评估数据集和指标不足 | 专业外呼语音Agent |
| 47 | http://arxiv.org/abs/2510.21652v1 | AstaBench: Rigorous Benchmarking of AI Agents with a Scientific Research Suite | 2400+问题覆盖科学发现全流程+生产级搜索工具 | 现有基准无法全面评估科学研究Agent能力 | 科学研究Agent评估 |
| 48 | http://arxiv.org/abs/2511.07426v1 | Network and Systems Performance Characterization of MCP-Enabled LLM Agents | 基于测量的分析，揭示 MCP 启用交互中能力、性能与成本的权衡。 | 解决 MCP 上下文膨胀导致的 token 成本激增及计算负载问题。 | MCP 启用 LLM 智能体 |
| 49 | http://arxiv.org/abs/2510.22443v1 | Benchmarking Egocentric Multimodal Goal Inference for Assistive Wearable Agents | 构建WAGIBench基准，348参与者29小时多模态数据 | 可穿戴Agent目标推断缺乏评估基准 | 智能眼镜等可穿戴辅助Agent |
| 50 | http://arxiv.org/abs/2510.23458v2 | BrowseConf: Confidence-Guided Test-Time Scaling for Web Agents | 置信度引导测试时缩放(TTS)方法 | 多轮交互中LLM置信度表达研究有限 | Web搜索Agent |
| 51 | http://arxiv.org/abs/2510.18483v1 | StarBench: A Turn-Based RPG Benchmark for Agentic Multimodal Decision-Making and Information Seeking | 建立 RPG 基准，评估多模态决策与主动信息寻求能力 | 现有基准缺乏对真实客户端操作与信息寻求的评估 | 游戏智能体与多模态决策 |
| 52 | http://arxiv.org/abs/2510.18488v1 | AndroidControl-Curated: Revealing the True Potential of GUI Agents through Benchmark Purification | 通过净化流程改进基准，揭示 GUI 智能体真实潜力 | 现有基准存在歧义和错误，低估智能体能力 | 移动端 GUI 智能体 |
| 53 | http://arxiv.org/abs/2510.18596v1 | CUARewardBench: A Benchmark for Evaluating Reward Models on Computer-using Agent | 首个计算机使用智能体奖励模型基准，支持轨迹与步骤级评估 | 解决脚本验证器扩展性差且无法提供步骤评估的问题 | 计算机使用智能体评估 |
| 54 | http://arxiv.org/abs/2510.19205v1 | WebGraphEval: Multi-Turn Trajectory Evaluation for Web Agents using Graph Representation | 将轨迹抽象为统一加权动作图，捕捉跨模型规律与低效点 | 解决现有评估忽略结构多样性且仅关注二元成功的问题 | Web 智能体多轮交互评估 |
| 55 | http://arxiv.org/abs/2510.19631v1 | HSCodeComp: A Realistic and Expert-level Benchmark for Deep Search Agents in Hierarchical Rule Application | 首个电商基准，评估智能体在分层规则应用中的深度推理 | 解决现有基准忽略复杂规则精确应用能力评估的问题 | 电商海关编码分类 |
| 56 | http://arxiv.org/abs/2510.19771v3 | Beyond Reactivity: Measuring Proactive Problem Solving in LLM Agents | 分解主动性为搜索、识别、解决三能力，评估 LLM 主动性 | 解决现有基准局限于局部上下文无法测试长周期推理的问题 | 主动问题解决智能体 |
| 57 | http://arxiv.org/abs/2510.23875v1 | Large Language Model Agent Personality and Response Appropriateness: Evaluation by Human Linguistic Experts, LLM-as-Judge, and Natural Language Model | 结合语言学标准与人类专家评估，全面评估智能体提示人格特征。 | 解决纯深度学习方案在人格评估上的局限性。 | 交互式应用与诗歌解释任务 |
| 58 | http://arxiv.org/abs/2510.24317v1 | Cybersecurity AI Benchmark (CAIBench): A Meta-Benchmark for Evaluating Cybersecurity AI Agents | 集成五类评估类别，系统同时进行攻防评估与隐私保护评估。 | 解决现有基准评估孤立技能而非集成性能问题。 | 网络安全 AI 智能体评估 |
| 59 | http://arxiv.org/abs/2510.24358v2 | Automatically Benchmarking LLM Code Agents through Agent-Driven Annotation and Evaluation | 利用人工监督生成多样化项目级任务，专用微调模型进行评估。 | 解决高质量项目级评估数据集创建成本高与评估不准问题。 | 代码智能体评估与基准 |
| 60 | http://arxiv.org/abs/2510.24397v1 | APTBench: Benchmarking Agentic Potential of Base LLMs During Pre-Training | 将真实代理任务转化为选择题，评估预训练阶段模型的代理潜力。 | 解决现有基准无法反映预训练模型代理能力问题。 | 基础 LLM 预训练与代理潜力 |
| 61 | http://arxiv.org/abs/2510.24563v2 | OSWorld-MCP: Benchmarking MCP Tool Invocation In Computer-Use Agents | 首个全面基准评估计算机使用智能体的工具调用与 GUI 操作能力。 | 解决工具调用能力被忽视与评估不公平问题。 | 多模态计算机使用智能体 |
| 62 | http://arxiv.org/abs/2510.24591v2 | ReplicationBench: Can AI Agents Replicate Astrophysics Research Papers? | 评估智能体复现天体物理论文核心贡献的能力，包含专家验证。 | 解决科学research 助手忠实性与正确性评估缺失问题。 | 科学研究助手与论文复现 |
| 63 | http://arxiv.org/abs/2510.24668v1 | InteractComp: Evaluating Search Agents With Ambiguous Queries | 构建基准评估搜索代理识别查询歧义并主动交互解决的能力。 | 解决现有基准无法评估交互消歧能力与代理过度自信问题。 | Web 搜索与信息检索代理 |
| 64 | http://arxiv.org/abs/2510.26298v1 | Can Agent Conquer Web? Exploring the Frontiers of ChatGPT Atlas Agent in Web Games | 使用浏览器游戏评估Atlas网页交互能力 | 动态交互环境中实时时序和运动控制能力评估 | ChatGPT Atlas网页交互Agent |
| 65 | http://arxiv.org/abs/2510.26852v2 | CATArena: Evaluating Evolutionary Capabilities of Code Agents via Iterative Tournaments | 迭代锦标赛评估代码Agent进化能力，双指标分离静态生成与进化潜力 | 现有评估仅关注单轮功能代码生成 | LLM代码Agent进化能力评估 |
| 66 | http://arxiv.org/abs/2510.27287v1 | Can LLMs Help You at Work? A Sandbox for Evaluating LLM Agents in Enterprise Environments | EnterpriseBench基准：500任务跨软件工程/HR/财务/行政领域 | 企业环境复杂性使LLM Agent开发评估困难 | 企业环境LLM Agent |
| 67 | http://arxiv.org/abs/2510.27598v2 | InnovatorBench: Evaluating Agents' Ability to Conduct Innovative LLM Research | InnovatorBench基准平台：20任务跨数据构建/损失设计/奖励设计等 | 现有基准在简化设置中探测狭窄技能 | LLM研究Agent能力评估 |
| 68 | http://arxiv.org/abs/2510.25110v4 | DEBATE: A Large-Scale Benchmark for Evaluating Opinion Dynamics in Role-Playing LLM Agents | 大规模基准测试角色扮演 Agent 的意见动态真实性 | 多 Agent 模拟缺乏真实人类交互基准的问题 | 意见动态与社会模拟评估 |
| 69 | http://arxiv.org/abs/2510.25423v2 | What Challenges Do Developers Face in AI Agent Systems? An Empirical Study on Stack Overflow & GitHub Issues | 基于 Stack Overflow 和 GitHub 的 Agent 开发挑战实证研究 | 开发者面临 Agent 系统工程困难缺乏特征描述 | Agent 系统开发与维护 |
| 70 | http://arxiv.org/abs/2510.25694v1 | Process-Level Trajectory Evaluation for Environment Configuration in Software Engineering Agents | 提供环境配置过程中的细粒度能力评估基准 | 现有基准仅评估端到端成功， obscuring 失败原因 | 软件工程 Agent 评估 |
| 71 | http://arxiv.org/abs/2510.25726v2 | The Tool Decathlon: Benchmarking Language Agents for Diverse, Realistic, and Long-Horizon Task Execution | 跨 32 个应用、604 个工具的长周期任务基准 | 现有基准缺乏多样性、真实性与长周期复杂性 | 语言 Agent 真实任务评估 |

[返回目录](#目录)

<a id="cat-07"></a>

## 多Agent协作与通信

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2510.04886v2 | Where Did It All Go Wrong? A Hierarchical Look into Multi-Agent Error Attribution | 提出 ECHO 算法，结合层次上下文表示、客观分析与共识投票进行错误归因 | 解决多智能体交互轨迹中 pinpoint 代理与步骤级失败的准确性与一致性问题 | 多智能体系统调试与改进 |
| 2 | http://arxiv.org/abs/2510.05445v1 | AgentRouter: A Knowledge-Graph-Guided LLM Router for Collaborative Multi-Agent Question Answering | 提出 AgentRouter，将多智能体 QA 公式化为知识图谱引导的路由问题 | 解决 practitioner 面对模型 proliferation 选择最佳配置的不确定性 | 协作多智能体问答 |
| 3 | http://arxiv.org/abs/2510.05611v2 | MADIAVE: Multi-Agent Debate for Implicit Attribute Value Extraction | 引入 MADIAVE 框架， employ 多 MLLM 代理迭代 refine 推断，通过辩论轮次验证更新 | 解决隐式属性值提取中多维数据复杂性及视觉文本理解差距的问题 | 多模态电子商务属性提取 |
| 4 | http://arxiv.org/abs/2510.05746v1 | ARM: Discovering Agentic Reasoning Modules for Generalizable Multi-Agent Systems | 提出 ARM 范式，优化 CoT 推理，通过树搜索发现通用推理模块 | 解决自动 MAS 设计技术性能差及需昂贵重发现架构与数据标注的问题 | 通用多智能体系统设计 |
| 5 | http://arxiv.org/abs/2510.05748v3 | Communication Enables Cooperation in LLM Agents: A Comparison with Curriculum-Based Approaches | 调查直接通信与课程学习，发现一词“廉价谈话”通道显著提升合作率 | 解决多智能体 LLM 系统中 eliciting 合作对 AI 对齐的关键挑战 | 多智能体协调问题 |
| 6 | http://arxiv.org/abs/2510.00381v1 | Semantic-Driven AI Agent Communications: Challenges and Solutions | 提出语义驱动AI Agent通信框架，含语义自适应、轻量化传输、自进化控制三技术 | 动态环境和有限资源下AI Agent实时感知、决策与协作通信问题 | AI Agent通信网络 |
| 7 | http://arxiv.org/abs/2510.00685v2 | Stochastic Self-Organization in Multi-Agent Systems | SelfOrg框架响应条件化动态构建DAG，基于Shapley值近似评估同伴贡献 | 固定拓扑或外部LLM评判增加复杂度，通信结构优化对协作至关重要 | 强弱LLM后端的多Agent系统 |
| 8 | http://arxiv.org/abs/2510.05138v3 | LiRA: A Multi-Agent Framework for Reliable and Readable Literature Review Generation | 专业化Agent分工（大纲/写作/编辑/评审）模拟人类文献综述流程 | 科学出版物快速增长使综述难以全面更新，写作阶段探索不足 | SciReviewGen、ScienceDirect文献综述 |
| 9 | http://arxiv.org/abs/2510.01523v2 | MetaSynth: Multi-Agent Metadata Generation from Implicit Feedback in Black-Box Systems | 示例库构建+候选生成+评估器-生成器循环迭代优化，利用隐式搜索反馈 | 搜索引擎黑盒环境无显式标签，现有方法缺乏多样性或忽略历史成功 | 电商元数据生成优化 |
| 10 | http://arxiv.org/abs/2510.01609v1 | AgentRec: Next-Generation LLM-Powered Multi-Agent Collaborative Recommendation with Adaptive Intelligence | 分层Agent网络+自适应加权机制，三层学习策略平衡快速响应/智能推理/深度协作 | 现有方法处理动态用户偏好、保持对话连贯性、平衡多排序目标困难 | 交互式对话推荐系统 |
| 11 | http://arxiv.org/abs/2510.01617v3 | AMAS: Adaptively Determining Communication Topology for LLM-based Multi-Agent System | 动态图设计器自主识别任务特定最优图配置，利用输入内在属性引导查询轨迹 | 传统MAS架构受固定手工图拓扑限制缺乏上下文响应性，跨工作负载效率降低 | 问答/数学推导/代码生成 |
| 12 | http://arxiv.org/abs/2510.03879v2 | Adversarial Agent Collaboration for C to Rust Translation | 提出 ACToR，利用生成器与判别器对抗协作迭代生成 Rust 翻译 | 解决大代码库 C 到 Rust 翻译中复杂程序分析易失效的问题 | 遗留 C 代码内存安全迁移 |
| 13 | http://arxiv.org/abs/2510.03902v1 | Multi-Agent Code-Orchestrated Generation for Reliable Infrastructure-as-Code | 提出 MACOG，多智能体编排生成 IaC，包含架构、安全、成本等专用代理 | 解决单体 LLM 生成 IaC 时语法错误、策略违规及设计不可扩展问题 | 云原生基础设施即代码生成 |
| 14 | http://arxiv.org/abs/2510.05174v3 | Emergent Coordination in Multi-Agent Language Models | 引入信息论框架测试多代理 LLM 系统的高阶结构与协同涌现 | 解决多代理系统仅是个体集合还是集成集体的界定与测量问题 | 多 Agent 语言模型协同机制 |
| 15 | http://arxiv.org/abs/2510.04488v1 | Multi-Agent Collaborative Intelligence: Dual-Dial Control for Reliable LLM Reasoning | 提出 MACI，通过信息 dial 与行为 dial 解耦信息与行为，主动控制辩论 | 解决多代理辩论浪费计算、固定对抗立场及启发式停止的问题 | 可靠 LLM 推理与临床诊断 |
| 16 | http://arxiv.org/abs/2510.05188v1 | Plug-and-Play Dramaturge: A Divide-and-Conquer Approach for Iterative Narrative Script Refinement via Collaborative LLM Agents | 提出 Dramaturge，分层多代理协作进行全局与场景级剧本审查修订 | 解决单次生成难以产出高质量长叙事及局部编辑与整体不一致问题 | 长叙事剧本迭代优化 |
| 17 | http://arxiv.org/abs/2510.06307v1 | Belief-Calibrated Multi-Agent Consensus Seeking for Complex NLP Tasks | 提出信念校准共识寻求框架，优化协作选择并校准共识判断 | 解决多智能体协作中信念矛盾导致共识不稳定的问题 | 复杂 NLP 任务 |
| 18 | http://arxiv.org/abs/2510.06761v1 | Evolving and Executing Research Plans via Double-Loop Multi-Agent Collaboration | 提出双循环多代理框架，教授代理进化计划，学生代理执行 | 解决科研自动化中计划进化与动态执行难以兼顾的挑战 | 自动科研流程 |
| 19 | http://arxiv.org/abs/2510.08619v1 | Hypothesis Hunting with Evolving Networks of Autonomous Scientific Agents | 建模发现为代理、网络与评估规范交互，实现自组织网络 | 支持大规模科学数据集上的探索性假设搜索 | 科学发现代理 |
| 20 | http://arxiv.org/abs/2510.07064v1 | Prompt Optimization Across Multiple Agents for Representing Diverse Human Populations | 从子模优化视角选择代表性 LLM 代理集，捕捉人类多样性 | 解决单 LLM 代理输出同质化无法捕捉人类观点多样性问题 | 人类行为模拟 |
| 21 | http://arxiv.org/abs/2510.07475v1 | MAPRO: Recasting Multi-Agent Prompt Optimization as Maximum a Posteriori Inference | 将多代理提示优化 formul 为 MAP 推断，使用拓扑感知 refinement | 解决多代理提示优化搜索空间指数爆炸及信用分配模糊问题 | 多代理系统提示优化 |
| 22 | http://arxiv.org/abs/2510.07488v2 | Can Lessons From Human Teams Be Applied to Multi-Agent Systems? The Role of Structure, Diversity, and Interaction Dynamics | 提出多代理框架考察结构、多样性与交互动态对团队性能影响 | 探索人类团队科学核心方面在多代理系统中的应用效果 | 多代理团队动态 |
| 23 | http://arxiv.org/abs/2510.07517v4 | When Identity Skews Debate: Anonymization for Bias-Reduced Multi-Agent Reasoning | 提出响应匿名化框架，移除身份标记以减少身份偏差 | 解决多代理辩论中代理易受身份驱动奉承与自我偏差影响问题 | 多代理推理辩论 |
| 24 | http://arxiv.org/abs/2510.07593v2 | AgentAsk: Multi-Agent Systems Need to Ask | 提出轻量级澄清模块，在边缘级别干预防止级联错误 | 解决多代理交互中错误传播导致性能低于单代理基线问题 | 多代理系统通信 |
| 25 | http://arxiv.org/abs/2510.07799v1 | Dynamic Generation of Multi-LLM Agents Communication Topologies with Graph Diffusion Models | 提出引导拓扑扩散框架，动态生成多智能体通信拓扑 | 解决静态拓扑无法适应多样任务需求及通信成本平衡问题 | 多智能体协作系统 |
| 26 | http://arxiv.org/abs/2510.08263v2 | Co-TAP: Three-Layer Agent Interaction Protocol Technical Report | 提出三层代理交互协议，标准化人机、统一代理及记忆知识协议 | 解决多智能体系统在互操作性、协作及知识共享的挑战 | 多智能体应用 |
| 27 | http://arxiv.org/abs/2510.17844v1 | Modeling Layered Consciousness with Multi-Agent Large Language Models | 基于精神分析理论，通过多智能体交互模拟自我意识与潜意识 | 解决单一模型缺乏情感深度与个性化认知的问题 | 个性化认知模拟 |
| 28 | http://arxiv.org/abs/2510.09087v1 | Leading the Follower: Learning Persuasive Agents in Social Deduction Games | 将对话形式化为 Stackelberg 竞争，强化学习优化说服性话语 | 解决社会推理游戏中忽视说服性沟通影响的问题 | 社交推理游戏 |
| 29 | http://arxiv.org/abs/2510.09854v1 | NG-Router: Graph-Supervised Multi-Agent Collaboration for Nutrition Question Answering | 知识图谱指导多智能体协作，图神经网络学习任务感知路由 | 解决单一智能体推理能力有限及上下文过载问题 | 营养健康问答 |
| 30 | http://arxiv.org/abs/2510.10047v1 | SwarmSys: Decentralized Swarm-Inspired Agents for Scalable and Adaptive Reasoning | 闭环框架模拟群体智能，动态任务分配无需全局监督 | 解决固定角色或集中控制限制可扩展性与适应性问题 | 长视野推理 |
| 31 | http://arxiv.org/abs/2510.10460v2 | Understanding and Bridging the Planner-Coder Gap: A Systematic Study on the Robustness of Multi-Agent Systems for Code Generation | 发现规划 - 编码间隙是鲁棒性缺陷主因，提出修复方法 | 解决多智能体代码生成中信息丢失导致失败问题 | 代码生成系统 |
| 32 | http://arxiv.org/abs/2510.10585v3 | D3MAS: Decompose, Deduce, and Distribute for Enhanced Knowledge Sharing in Multi-Agent Systems | 分层协调框架减少知识冗余，结构化消息传递 | 解决多智能体系统知识重复与通信低效问题 | 多智能体协作系统 |
| 33 | http://arxiv.org/abs/2510.10611v3 | HyperAgent: Leveraging Hypergraphs for Topology Optimization in Multi-Agent Communication | 基于超图优化通信拓扑，捕捉多智能体协作模式 | 解决 pairwise 边表示无法捕捉群体协作问题 | 多智能体通信网络 |
| 34 | http://arxiv.org/abs/2510.15568v1 | The Spark Effect: On Engineering Creative Diversity in Multi-Agent AI Systems | 角色条件化Agent（Sparks）通过系统提示库多样化Agent行为 | 生产系统中LLM输出同质化，无法满足品牌或艺术期望 | 创意服务团队的头脑风暴系统 |
| 35 | http://arxiv.org/abs/2510.15682v1 | SQuAI: Scientific Question-Answering with Multi-Agent Retrieval-Augmented Generation | 四Agent协作分解问题、混合检索、自适应过滤，集成行内引用 | 学术领域RAG系统复杂问题需准确答案与可追溯引用 | 科学文献问答系统 |
| 36 | http://arxiv.org/abs/2510.16144v1 | Agentic AI for Ultra-Modern Networks: Multi-Agent Framework for RAN Autonomy and Assurance | 分布式Agent协作执行数据收集、模型训练、策略生成与验证 | 传统O-RAN控制循环集中化导致策略冲突、数据漂移和不安全行为 | 5G/6G无线接入网络自主管理 |
| 37 | http://arxiv.org/abs/2510.16572v1 | Ripple Effect Protocol: Coordinating Agent Populations | Agent共享决策与轻量级敏感度信号，信号在网络中涟漪传播实现群体对齐 | 现有协议强调通信而非协调，Agent群体增长导致脆弱集体行为 | 大规模Agent群体协调 |
| 38 | http://arxiv.org/abs/2510.18893v1 | CodeCRDT: Observation-Driven Coordination for Multi-Agent LLM Code Generation | 观察驱动协调模式，Agent监控共享状态与可观察更新，使用CRDT实现无锁并发 | 多Agent LLM系统因昂贵协调无法实现并行加速 | 多Agent代码生成 |
| 39 | http://arxiv.org/abs/2510.16652v1 | ARCO-BO: Adaptive Resource-aware COllaborative Bayesian Optimization for Heterogeneous Multi-Agent Design | 相似性与最优感知共识机制、预算感知异步采样、部分输入空间共享 | 分布式优化中Agent目标/预算/变量异构导致协调困难与资源浪费 | 科学与工程设计中的分布式优化 |
| 40 | http://arxiv.org/abs/2510.16978v2 | Lark: Biologically Inspired Neuroevolution for Multi-Stakeholder LLM Agents | 四种机制：可塑性、复制成熟、排序选择利益相关者聚合、基于token计算感知 | 解决冗长与利益相关者权衡问题，扩展利益相关者对齐策略生成 | 多利益相关者决策场景 |
| 41 | http://arxiv.org/abs/2510.12120v1 | Towards Engineering Multi-Agent LLMs: A Protocol-Driven Approach | 软件工程多代理协议实例化核心 SE 设计原则。 | 多代理系统因规格不足和协调错位而失败。 | 软件工程多代理系统 |
| 42 | http://arxiv.org/abs/2510.12697v1 | Multi-Agent Debate for LLM Judges with Adaptive Stability Detection | 多代理辩论法官框架，代理协作推理并迭代优化响应。 | 当前 LLM 法官方法依赖简单的聚合方法。 | LLM 法官 |
| 43 | http://arxiv.org/abs/2510.12872v2 | KVCOMM: Online Cross-context KV-cache Communication for Efficient LLM-based Multi-agent Systems | 免训练框架通过重用 KV-cache 实现高效预填充。 | 多代理 LLM 系统因重叠上下文的重复处理而开销大。 | 基于 LLM 的多代理系统 |
| 44 | http://arxiv.org/abs/2510.13903v1 | Benefits and Limitations of Communication in Multi-Agent Reasoning | 理论框架分析多代理系统的表达能力。 | 多代理推理系统的基本能力知之甚少。 | 多代理推理系统 |
| 45 | http://arxiv.org/abs/2510.13081v1 | Agentic Discovery: Closing the Loop with Cooperative Agents | 假设合作代理需要增强人类角色并实现自主发现。 | 发现率受限于人类决策任务如设定目标和生成假设。 | 科学发现 |
| 46 | http://arxiv.org/abs/2510.13214v1 | Adaptive Reasoning Executor: A Collaborative Agent System for Efficient Reasoning | 互补代理系统整合小型和大型 LLM 以进行高效推理。 | 对所有问题应用深度推理计算成本高昂。 | 高效推理系统 |
| 47 | http://arxiv.org/abs/2510.13257v1 | GRIDAI: Generating and Repairing Intrusion Detection Rules via Collaboration among Multiple LLM-based Agents | 通过多 LLM 代理协作自动化生成和修复入侵检测规则。 | 现有工作忽视新攻击与现有规则之间的关系导致冗余。 | 网络入侵检测 |
| 48 | http://arxiv.org/abs/2510.14512v2 | Helmsman: Autonomous Synthesis of Federated Learning Systems via Collaborative LLM Agents | 通过三阶段协作自动化联邦学习系统合成，模拟研发工作流 | 解决联邦学习系统设计部署复杂、策略选择 tuning 瓶颈问题 | 联邦学习系统 |
| 49 | http://arxiv.org/abs/2510.20102v3 | Human-Centered LLM-Agent System for Detecting Anomalous Digital Asset Transactions | 三角色认知对齐多Agent系统+可追溯推理 | 数字资产交易异常检测缺乏可解释性 | 加密货币 forensic 分析 |
| 50 | http://arxiv.org/abs/2510.20362v1 | ComProScanner: A multi-agent based framework for composition-property structured data extraction from scientific literature | 自主多Agent平台提取/验证/分类/可视化 | 科学文献结构化知识提取工具稀缺 | 材料科学数据库构建 |
| 51 | http://arxiv.org/abs/2510.20875v1 | CC-GRMAS: A Multi-Agent Graph Neural System for Spatiotemporal Landslide Risk Assessment in High Mountain Asia | 预测/规划/执行三Agent协同+卫星观测 | 高山地区滑坡检测和灾害响应碎片化 | 气候灾害预警系统 |
| 52 | http://arxiv.org/abs/2510.20728v2 | Co-Designing Quantum Codes with Transversal Diagonal Gates via Multi-Agent Systems | GPT-5驱动三Agent协作+TeXRA平台 | 量子纠错码设计需要人工专家迭代 | 量子计算代码发现 |
| 53 | http://arxiv.org/abs/2510.20963v1 | Towards Scalable Oversight with Collaborative Multi-Agent Debate in Error Detection | 协作式多Agent辩论协议ColMAD | 竞争性辩论导致欺骗和错误检测性能下降 | LLM响应错误检测 |
| 54 | http://arxiv.org/abs/2510.21370v1 | HIKMA: Human-Inspired Knowledge by Machine Agents through a Multi-Agent Framework for Semi-Autonomous Scientific Conferences | 端到端AI集成学术出版和演示流程 | 传统学术交流流程效率低下 | 半自主学术会议 |
| 55 | http://arxiv.org/abs/2510.21546v1 | Auction-Based Responsibility Allocation for Scalable Decentralized Safety Filters in Cooperative Multi-Agent Collision Avoidance | 拍卖制责任分配+高阶控制屏障函数 | 分散式安全过滤器随Agent数量增长不可扩展 | 多Agent碰撞避免 |
| 56 | http://arxiv.org/abs/2510.21695v1 | A Knowledge-Graph Translation Layer for Mission-Aware Multi-Agent Path Planning in Spatiotemporal Dynamics | 知识图谱作为智能翻译层+双平面架构 | 高层任务目标与底层规划输入存在语义鸿沟 | 自主水下车辆路径规划 |
| 57 | http://arxiv.org/abs/2510.17149v2 | Which LLM Multi-Agent Protocol to Choose? | 提出 ProtocolBench 基准及可学习协议路由器 ProtocolRouter。 | 解决多智能体系统通信协议选择缺乏标准化指导及性能评估的问题。 | 多智能体通信协议 |
| 58 | http://arxiv.org/abs/2510.17382v1 | Graph Attention-Guided Search for Dense Multi-Agent Pathfinding | 混合框架集成学习启发式与搜索算法，增强 deadlock 检测。 | 解决密集多智能体路径规划中实时寻找近优解的挑战。 | 多智能体路径规划 |
| 59 | http://arxiv.org/abs/2510.20844v3 | TrustResearcher: Automating Knowledge-Grounded and Transparent Research Ideation with Multi-Agent Collaboration | 四阶段统一框架，暴露中间推理状态及可配置智能体供检查。 | 解决现有文献构思系统黑盒化、缺乏透明度及 researcher 控制力的问题。 | 科研构思自动化 |
| 60 | http://arxiv.org/abs/2510.17797v2 | Enterprise Deep Research: Steerable Multi-Agent Deep Research for Enterprise Analytics | 多智能体系统集成主规划、专用搜索、可视化工具及反思机制。 | 解决企业将非结构化数据转化为可操作洞察的压力及 domain  nuances 问题。 | 企业数据分析 |
| 61 | http://arxiv.org/abs/2510.18032v1 | OPTAGENT: Optimizing Multi-Agent LLM Interactions Through Verbal Reinforcement Learning for Enhanced Reasoning | 多智能体口头强化学习算法，动态构建 refine 协作结构。 | 解决现有协作结构 predefined 或依赖投票抑制正确但非 dominant 贡献的问题。 | 多智能体推理 |
| 62 | http://arxiv.org/abs/2510.18179v2 | Adaptive Coopetition: Leveraging Coarse Verifier Signals for Resilient Multi-Agent LLM Reasoning | 自适应 UCB 基于"coopetition"机制，利用 coarse verifier 信号决定协作或竞争。 | 解决推理时计算中 self-correction 强化偏见及 MAC 缺乏高效协调机制的问题。 | 多智能体 LLM 推理 |
| 63 | http://arxiv.org/abs/2510.22320v1 | IFS: Information Flow Structure for Multi-agent Ad Hoc System | 设计信息流结构(IFS)改善通信与信息融合 | 临时多Agent系统信息流不足、处理能力有限 | StarCraft II等开放环境协作 |
| 64 | http://arxiv.org/abs/2510.22477v1 | Agent-GSPO: Communication-Efficient Multi-Agent Systems via Group Sequence Policy Optimization | 序列级RL优化token经济性，涌现"策略性沉默" | 多Agent系统通信成本过高 | 大规模推理多Agent系统 |
| 65 | http://arxiv.org/abs/2510.22967v2 | MAD-Fact: A Multi-Agent Debate Framework for Long-Form Factuality Evaluation in LLMs | 辩论式多Agent验证系统+事实重要性层级 | 长文本事实准确性评估方法缺乏 | 生物医学/法律/教育高风险领域 |
| 66 | http://arxiv.org/abs/2510.23245v1 | Multi-Stakeholder Alignment in LLM-Powered Collaborative AI Systems: A Multi-Agent Framework for Intelligent Tutoring | 咨询治理层(AGL)多Agent框架协调多方利益相关者 | 智能辅导系统缺乏多方价值对齐机制 | 智能辅导系统(学生/家长/教师/机构) |
| 67 | http://arxiv.org/abs/2510.18515v2 | Socialized Learning and Emergent Behaviors in Multi-Agent Systems based on Multimodal Large Language Models | 结合多模态感知与社会化学习机制，促进 emergent 社会智能 | 解决多智能体协作中缺乏社会学习与沟通机制的问题 | 多智能体协作装配环境 |
| 68 | http://arxiv.org/abs/2510.19995v2 | Communication to Completion: Modeling Collaborative Workflows with Intelligent Multi-Agent Communication | 显式建模通信为受限资源，引入 Alignment Factor 量化效率 | 解决现有框架忽略真实团队协作中通信成本的问题 | 数字工作场所协作流程 |
| 69 | http://arxiv.org/abs/2510.23824v1 | Decentralized Multi-Agent Goal Assignment for Path Planning using Large Language Models | 利用 LLM 生成目标偏好排名，通过确定性冲突解决规则分配目标。 | 解决去中心化条件下多智能体路径规划协调难题。 | 机器人路径规划与网格世界 |
| 70 | http://arxiv.org/abs/2510.24303v3 | Retrieval- and Argumentation-Enhanced Multi-Agent LLMs for Judgmental Forecasting (Extended Version with Supplementary Material) | 不同智能体对索赔真实性持异议并提供证据，组合证据提高预测。 | 解决单一模型预测准确性与可解释性不足问题。 | 判断性预测与索赔验证 |
| 71 | http://arxiv.org/abs/2510.26328v1 | Urban-MAS: Human-Centered Urban Prediction with LLM-Based Multi-Agent System | 三类Agent协作：预测因子引导、信息提取、多源推理 | 单LLM在领域特定任务上表现不足 | 城市AI预测（东京、米兰、西雅图） |
| 72 | http://arxiv.org/abs/2510.26423v1 | Nexus: Execution-Grounded Multi-Agent Test Oracle Synthesis | 四专家Agent审议+执行验证+自修正循环 | 非回归测试中测试预言生成准确性低 | 软件测试预言生成 |
| 73 | http://arxiv.org/abs/2510.26740v1 | A General Incentives-Based Framework for Fairness in Multi-agent Resource Allocation | GIFF框架利用Q函数平衡效率与公平，无需额外训练 | 资源受限下效率优化导致不公平结果 | 动态拼车、无家可归预防、工作分配 |
| 74 | http://arxiv.org/abs/2510.27452v1 | From Pixels to Paths: A Multi-Agent Framework for Editable Scientific Illustration | VisPainter三模块协作：Manager、Designer、Toolbox，产出矢量图形 | 生成模型输出栅格化图像缺乏语义结构不可编辑 | 科学插图生成 |
| 75 | http://arxiv.org/abs/2510.27554v1 | Sybil-Resistant Service Discovery for Agent Economies | TraceRank声誉加权排名算法，支付交易作为背书 | Agent消费x402服务时发现可信服务困难 | Agent经济服务发现 |
| 76 | http://arxiv.org/abs/2510.27617v1 | VeriMoA: A Mixture-of-Agents Framework for Spec-to-HDL Generation | 质量引导缓存机制+多路径生成策略，无需训练 | 当前多Agent方法易受噪声传播和推理空间受限 | 硬件描述语言（HDL）生成 |
| 77 | http://arxiv.org/abs/2511.00181v1 | From Evidence to Verdict: An Agent-Based Forensic Framework for AI-Generated Image Detection | AIFo框架：多Agent协作收集/综合/推理跨源证据，结构化辩论机制 | 传统分类器缺乏可解释性，VLM限于单次分析 | AI生成图像检测 |
| 78 | http://arxiv.org/abs/2510.25595v1 | Communication and Verification in LLM Agents towards Collaboration under Information Asymmetry | 微调+ 验证器框架，强调信息不对称下的对齐通信 | Agent 协作中缺乏真正规则理解与信任的问题 | 任务协作与谜题求解 |
| 79 | http://arxiv.org/abs/2510.25850v2 | Debate2Create: Robot Co-design via Multi-Agent LLM Debate | 多 Agent 辩论框架 formulated 为基于物理评估的迭代辩论 | 手工设计目标难优化形态 - 奖励联合问题 | 机器人协同设计 |

[返回目录](#目录)

<a id="cat-08"></a>

## Agent架构与框架设计

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2510.05059v1 | Staircase Streaming for Low-Latency Multi-Agent Inference | 提出阶梯式流式传输，接收部分输出即开始生成最终响应，无需等待完整中间输出 | 解决多智能体推理增加首 token 时间，影响延迟敏感应用用户体验的问题 | 低延迟多智能体推理应用 |
| 2 | http://arxiv.org/abs/2510.05556v1 | Toward Systems Foundations for Agentic Exploration | 指出 fork 语义、外部副作用与原生 fork 三个基础挑战， benchmark 快照恢复机制 | 解决现有 pass-at-k  resets 不足以支持 agent 分支、回溯与搜索执行路径的问题 | 智能体探索系统支持 |
| 3 | http://arxiv.org/abs/2510.00536v1 | GUI-KV: Efficient GUI Agents via KV Cache with Spatio-Temporal Awareness | 空间显著性引导+时间冗余评分的KV缓存压缩方法，无需重新训练 | GUI Agent处理长序列高分辨率截图导致推理慢、成本高、内存受限 | GUI Agent benchmarks |
| 4 | http://arxiv.org/abs/2510.01427v2 | A Tale of LLMs and Induced Small Proxies: Scalable Agents for Knowledge Mining | Falconer框架LLM作为规划器和标注器训练小代理，统一分类提取为两原子操作 | LLM大规模部署成本高，传统分类器提取器高效但脆弱无法泛化新任务 | 大规模知识挖掘 |
| 5 | http://arxiv.org/abs/2510.05145v1 | FlashResearch: Real-time Agent Orchestration for Efficient Deep Research | 自适应规划器+实时编排层+多维并行框架，将顺序处理转为并行运行时编排 | 深度研究Agent顺序推理导致高延迟、运行时适应性差、资源分配低效 | 交互式深度研究应用 |
| 6 | http://arxiv.org/abs/2510.03829v1 | A4FN: an Agentic AI Architecture for Autonomous Flying Networks | 提出 A4FN 架构，利用生成式 AI 和 LLM 实现飞行网络意图驱动自动化 | 解决基础设施受限场景下的网络实时控制与自适应重构问题 | 无人机飞行网络与灾难响应 |
| 7 | http://arxiv.org/abs/2510.03847v1 | Small Language Models for Agentic Systems: A Survey of Architectures, Capabilities, and Deployment Trade offs | 综述小语言模型在代理系统中的架构、能力及部署权衡，提出 SLM 默认设计模式 | 解决大模型在代理任务中成本高、延迟大的问题 | 资源受限的代理系统部署 |
| 8 | http://arxiv.org/abs/2510.04023v1 | LLM-Based Data Science Agents: A Survey of Capabilities, Challenges, and Future Directions | 首个全生命周期数据科学代理分类法，分析 45 个系统的能力与挑战 | 解决数据科学代理缺乏统一 taxonomy 及信任安全机制的问题 | 自动化数据科学工作流 |
| 9 | http://arxiv.org/abs/2510.04135v1 | GA4GC: Greener Agent for Greener Code via Multi-Objective Configuration Optimization | 提出 GA4GC 框架，通过多目标优化平衡代理运行时与代码性能 | 解决编码代理高 token 消耗及环境成本超过优化收益的问题 | 工业级代码优化代理部署 |
| 10 | http://arxiv.org/abs/2510.04173v4 | Open Agent Specification (Agent Spec): A Unified Representation for AI Agents | 提出 Agent Spec 声明式语言，统一代理定义、执行与评估标准 | 解决代理框架碎片化导致工作流难以共享、复现及互操作的问题 | 跨框架 AI 代理标准化与互操作 |
| 11 | http://arxiv.org/abs/2510.04371v1 | Speculative Actions: A Lossless Framework for Faster Agentic Systems | 提出推测动作框架，利用快模型预测动作实现多步并行执行 | 解决代理行为顺序执行导致 API 调用耗时及端到端延迟高的问题 | 低延迟代理系统部署与训练 |
| 12 | http://arxiv.org/abs/2510.06579v1 | TinyScientist: An Interactive, Extensible, and Controllable Framework for Building Research Agents | 识别自动研究工作流 essential 组件，提出交互式可扩展框架 | 解决自动研究工作流复杂度高、难以扩展和维护的挑战 | 自动科研代理 |
| 13 | http://arxiv.org/abs/2510.06711v1 | Inefficiencies of Meta Agents for Agent Design | 考察元代理设计挑战，提出进化方法优于简单扩展上下文 | 解决元代理学习中 prior designs 利用低效及行为多样性不足问题 | 自动化代理设计 |
| 14 | http://arxiv.org/abs/2510.06911v1 | LLM-Assisted Modeling of Semantic Web-Enabled Multi-Agents Systems with AJAN | 集成开发环境利用 LLM 辅助 AJAN 代理建模，降低语义网门槛 | 解决 RDF/SPARQL 基于代理行为定义易错及学习曲线高问题 | 语义网多代理系统 |
| 15 | http://arxiv.org/abs/2510.07147v1 | A Multi-Agent Framework for Stateful Inference-Time Search | 提出状态化多代理进化搜索，结合持久状态与对抗变异 | 解决无状态推理在多步任务中缺乏持久状态导致 brittle 问题 | 自动化单元测试生成 |
| 16 | http://arxiv.org/abs/2510.07423v2 | ProSEA: Problem Solving via Exploration Agents | 分层架构中管理器代理协调专家代理，基于失败反馈自适应重规划 | 解决现有代理静态规划及交互 brittle 无法真正协作问题 | 复杂问题求解 |
| 17 | http://arxiv.org/abs/2510.07614v1 | Traceability and Accountability in Role-Specialized Multi-Agent LLM Pipelines | 研究可追踪 accountable 流水线，量化模型角色特定优势与风险 | 解决顺序多代理系统中错误静默传递导致难以信任的问题 | 角色专用代理流水线 |
| 18 | http://arxiv.org/abs/2510.07733v3 | SurveyG: A Multi-Agent LLM Framework with Hierarchical Citation Graph for Automated Survey Generation | 集成分层引用图，捕获论文间结构与上下文知识生成综述 | 解决现有方法忽略论文结构关系导致综述缺乏 coherent 分类问题 | 自动化综述生成 |
| 19 | http://arxiv.org/abs/2510.08665v1 | RA-Gen: A Controllable Code Generation Framework Using ReAct for Multi-Agent Task Execution | 采用 ReAct 范式多代理系统，动态集成外部工具确保可控性 | 解决代码生成中安全性、准确性及用户控制力不足问题 | 代码生成任务 |
| 20 | http://arxiv.org/abs/2510.08383v1 | QAgent: A modular Search Agent with Interactive Query Understanding | 统一代理 RAG 框架，搜索代理通过交互推理优化查询理解 | 解决传统 RAG 复杂查询理解困难及搜索代理泛化挑战 | 知识密集型任务 |
| 21 | http://arxiv.org/abs/2510.08508v1 | MoA-VR: A Mixture-of-Agents System Towards All-in-One Video Restoration | 首个混合代理视频修复系统，模仿人类专家推理处理流程 | 解决视频修复需人工选模型及单体架构泛化能力差问题 | 视频修复系统 |
| 22 | http://arxiv.org/abs/2510.08789v2 | Q-Router: Agentic Video Quality Assessment with Expert Model Routing and Artifact Localization | 代理框架用于通用 VQA，多 tier 模型路由系统动态集成专家 | 解决 VQA 模型泛化差、可解释性低及扩展性不足问题 | 视频质量评估 |
| 23 | http://arxiv.org/abs/2510.09721v3 | A Comprehensive Survey on Benchmarks and Solutions in Software Engineering of LLM-Empowered Agentic System | 首次 holistic 分析 LLM 软件工程智能体，提出分类法与统一流程 | 解决基准与解决方案缺乏系统性理解的问题 | 软件工程研究领域 |
| 24 | http://arxiv.org/abs/2510.09244v1 | Fundamentals of Building Autonomous LLM Agents | 综述感知、推理、记忆、执行系统，探讨构建自主智能体模式 | 解决传统 LLM 在现实任务中自动化能力不足的问题 | 通用智能体开发 |
| 25 | http://arxiv.org/abs/2510.09474v1 | Multimodal Policy Internalization for Conversational Agents | 将多模态策略内化到模型参数，无需推理时包含策略提示 | 解决多模态智能体策略遵循难且计算成本高的问题 | 对话智能体 |
| 26 | http://arxiv.org/abs/2511.20657v1 | Intelligent Agents with Emotional Intelligence: Current Trends, Challenges, and Future Prospects | holistic 综述人工情感智能核心组件与未来方向 | 解决缺乏涵盖理解、唤起与表达的综合研究问题 | 情感计算 |
| 27 | http://arxiv.org/abs/2510.10661v2 | AGENTIQL: An Agent-Inspired Multi-Expert Framework for Text-to-SQL Generation | 多专家框架结合推理与编码代理，自适应路由 | 解决单体架构处理复杂 SQL 推理与模式多样性问题 | Text-to-SQL 生成任务 |
| 28 | http://arxiv.org/abs/2510.13857v1 | From Craft to Constitution: A Governance-First Paradigm for Principled Agent Engineering | 提出治理优先范式与 ArbiterOS 形式化架构 | 解决 Agent 从原型到生产环境的脆弱与不可信问题 | 关键任务 Agent 工程 |
| 29 | http://arxiv.org/abs/2510.10675v2 | Simpliflow: A Lightweight Open-Source Framework for Rapid Creation and Deployment of Generative Agentic AI Workflows | 轻量级声明式配置框架，解耦代理管理与执行 | 解决现有框架复杂度高、原型开发慢的问题 | 生成式 Agent 工作流 |
| 30 | http://arxiv.org/abs/2510.10890v2 | LLM$\times$MapReduce-V3: Enabling Interactive In-Depth Survey Generation through a MCP-Driven Hierarchically Modular Agent System | MCP 驱动分层模块化代理系统，支持人机干预 | 解决长形式调查生成中控制与定制化不足问题 | 学术调查生成 |
| 31 | http://arxiv.org/abs/2510.10991v1 | A Survey on Agentic Multimodal Large Language Models | 综述代理多模态大模型概念框架与三维分类 | 解决领域快速发展缺乏系统性梳理问题 | 代理多模态大模型 |
| 32 | http://arxiv.org/abs/2510.12838v3 | A$^2$FM: An Adaptive Agent Foundation Model for Tool-Aware Hybrid Reasoning | 统一框架遵循 route-then-align 原则，自适应模式 | 解决推理与代理 LLM 目标不匹配及效率差距问题 | 工具感知混合推理 |
| 33 | http://arxiv.org/abs/2510.15416v1 | Adaptive Minds: Empowering Agents with LoRA-as-Tools | 将LoRA适配器作为领域专用工具，LLM作为语义路由器动态选择 | 单一微调模型或规则路由缺乏灵活性 | 领域自适应AI助手 |
| 34 | http://arxiv.org/abs/2510.16276v1 | What Limits Agentic Systems Efficiency? | 分解端到端延迟为LLM API与Web环境延迟，提出SpecCache缓存框架 | 现有研究关注推理性能忽视Agent系统效率瓶颈 | Web交互式Agent系统 |
| 35 | http://arxiv.org/abs/2510.16499v2 | Automated Composition of Agents: A Knapsack Approach for Agentic Component Selection | 在线背包问题框架，Composer Agent动态测试候选组件建模实时效用 | 组件选择未基于能力、成本和实时效用，检索方法有局限 | 动态不确定环境中的Agent系统构建 |
| 36 | http://arxiv.org/abs/2510.16720v2 | Beyond Pipelines: A Survey of the Paradigm Shift toward Model-Native Agentic AI | 系统综述从Pipeline到Model-native范式转变，RL作为算法引擎 | 追踪Agentic AI构建范式演变，规划/工具使用/记忆从外部脚本到端到端学习 | Agentic AI研究社区 |
| 37 | http://arxiv.org/abs/2510.16786v2 | More with Less: An Empirical Study of Turn-Control Strategies for Efficient Coding Agents | 系统分析三种回合控制策略，动态回合策略按需分配资源最优 | 编码Agent部署受不可预测成本阻碍，回合总数战略控制未充分探索 | 软件工程任务的编码Agent |
| 38 | http://arxiv.org/abs/2510.11654v2 | FinVet: A Collaborative Framework of RAG and External Fact-Checking Agents for Financial Misinformation Detection | 集成 RAG 管道与外部事实核查代理，通过置信度加权投票机制协作。 | 金融虚假信息检测缺乏透明度和可信来源归因。 | 金融虚假信息检测 |
| 39 | http://arxiv.org/abs/2510.11694v1 | Operand Quant: A Single-Agent Architecture for Autonomous Machine Learning Engineering | 单代理 IDE 架构，整合机器学习工程全生命周期阶段。 | 多代理编排框架在受控 IDE 环境中效率不如单代理。 | 机器学习工程自动化 |
| 40 | http://arxiv.org/abs/2510.12066v2 | AI Agents as Universal Task Solvers | 将学习推理框架化为转导推理以减少计算 effort。 | 理解推理模型的理论极限和 scaling。 | 通用任务求解器 |
| 41 | http://arxiv.org/abs/2510.12787v3 | Ax-Prover: A Deep Reasoning Agentic Framework for Theorem Proving in Mathematics and Quantum Physics | 多代理系统用于 Lean 自动化定理证明，配备工具。 | 科学问题解决需要创造性推理和严格句法严谨性。 | 数学和物理定理证明 |
| 42 | http://arxiv.org/abs/2510.13920v1 | FACTS: Table Summarization via Offline Template Generation with Agentic Workflows | 代理工作流生成离线模板，包含 SQL 查询和 Jinja2 模板。 | 现有方法在成本、效率和隐私方面面临限制。 | 表格摘要 |
| 43 | http://arxiv.org/abs/2510.14126v1 | Cortex: Workflow-Aware Resource Pooling and Scheduling for Agentic Serving | 提出工作流感知的服务平合，通过阶段隔离优化资源池和调度 | 解决智能体工作流中阶段间干扰和性能不可预测问题 | 智能体服务平台 |
| 44 | http://arxiv.org/abs/2510.14184v1 | MAFA: A Multi-Agent Framework for Enterprise-Scale Annotation with Configurable Task Adaptation | 提出可配置的多智能体标注框架，支持动态任务适应和法官共识机制 | 解决企业级标注 backlog 和传统单智能体标注效果差的问题 | 企业级标注工作流 |
| 45 | http://arxiv.org/abs/2510.14308v2 | ReUseIt: Synthesizing Reusable AI Agent Workflows for Web Automation | 自动合成可复用工作流，Incorporate 执行 guard 以检测修复错误 | 解决 Web 智能体重复任务执行可靠性低和需人工干预问题 | Web 自动化任务 |
| 46 | http://arxiv.org/abs/2510.14406v2 | IMAGINE: Integrating Multi-Agent System into One Model for Complex Reasoning and Planning | 将多智能体系统集成到单一模型，通过端到端训练获得结构化推理能力 | 解决多智能体系统推理成本高、延迟长和端到端训练难问题 | 复杂推理与规划 |
| 47 | http://arxiv.org/abs/2510.20211v1 | Automated Cloud Infrastructure-as-Code Reconciliation with AI Agents | API痕迹检测漂移+LLM推断意图+自我进化知识库 | IaC与手动操作并存导致基础设施漂移 | 云基础设施管理 |
| 48 | http://arxiv.org/abs/2510.20276v2 | From Generation to Attribution: Music AI Agent Architectures for the Post-Streaming Era | 块级检索+归属层事件+实时结算架构 | AI音乐创作缺乏归属权和版税管理 | 音乐创作与分发平台 |
| 49 | http://arxiv.org/abs/2510.20641v1 | Integrating Machine Learning into Belief-Desire-Intention Agents: Current Advances and Open Challenges | 基于BDI范式的ML集成细粒度系统化分析 | 理性Agent架构与ML整合研究碎片化 | 理性ML Agent设计 |
| 50 | http://arxiv.org/abs/2510.21566v2 | ColorEcosystem: Powering Personalized, Standardized, and Trustworthy Agentic Service in massive-agent Ecosystem | Agent载体/商店/审计三组件生态系统蓝图 | 大规模Agent生态系统缺乏个性化和标准化 | 大规模Agent服务生态 |
| 51 | http://arxiv.org/abs/2510.17015v2 | Justitia: Fair and Efficient Scheduling of Task-parallel LLM Agents with Selective Pampering | 基于选择性优待策略的公平高效调度器，量化内存成本。 | 解决共享 GPU 服务器上任务并行 LLM 智能体的调度公平与效率。 | LLM 服务调度系统 |
| 52 | http://arxiv.org/abs/2510.17162v1 | ALPINE: A Lightweight and Adaptive Privacy-Decision Agent Framework for Dynamic Edge Crowdsensing | 轻量级自适应框架，终端设备实时调整差分隐私级别。 | 解决静态差分隐私机制无法适应动态风险、资源约束及任务需求的问题。 | 移动边缘众感隐私保护 |
| 53 | http://arxiv.org/abs/2510.17491v1 | Empowering Real-World: A Survey on the Technology, Practice, and Evaluation of LLM-driven Industry Agents | 系统综述行业 agent 技术、应用及评估，提出能力成熟度框架。 | 解决通用 agent 研究转化为驱动行业转型生产力的挑战。 | 行业 Agent 综述 |
| 54 | http://arxiv.org/abs/2510.17691v1 | A Mimamsa Inspired Framework For Instruction Sequencing In AI Agents | 形式化排序机制，引入动作对象命令逻辑及显式演绎规则。 | 解决 AI 应用中指令排序的可靠性、时间推理及依赖建模问题。 | 任务规划与机器人 |
| 55 | http://arxiv.org/abs/2510.17790v2 | UltraCUA: A Foundation Model for Computer Use Agents with Hybrid Action | 基础模型统一原始 GUI 操作与高层工具执行，混合动作轨迹。 | 解决计算机使用智能体依赖原始 GUI 动作导致执行链脆弱的问题。 | 计算机使用智能体 |
| 56 | http://arxiv.org/abs/2510.22009v2 | OpenPhone: Mobile Agentic Foundation Models | 设备-云协作架构，3B模型通过两阶段训练实现强决策 | 移动端Agent性能与成本矛盾 | 移动GUI自动化任务 |
| 57 | http://arxiv.org/abs/2510.22431v1 | Hollywood Town: Long-Video Generation via Cross-Modal Multi-Agent Orchestration | 分层图架构+超图节点+有向循环图支持迭代反思 | 长视频生成中Agent协作效率低、上下文不足 | 长视频内容生成 |
| 58 | http://arxiv.org/abs/2510.23664v1 | Agentsway -- Software Development Methodology for AI Agents-based Teams | 首个专为AI Agent团队设计的软件开发方法论 | 传统方法论不适用于Agent协作开发环境 | AI Agent软件开发团队 |
| 59 | http://arxiv.org/abs/2510.22781v2 | Agentic Meta-Orchestrator for Multi-task Copilots | 提出Agentic Meta-Orchestrator(AMO)元编排器 | Copilot服务需鲁棒编排器分配任务给多Agent | Microsoft 365电商/代码合规Copilot |
| 60 | http://arxiv.org/abs/2510.23682v1 | Beyond Prompt Engineering: Neuro-Symbolic-Causal Architecture for Robust Multi-Objective AI Agents | Chimera神经符号因果架构，LLM+符号约束+因果推理 | LLM Agent提示框架依赖导致灾难性脆弱性 | 高风险领域自主决策Agent |
| 61 | http://arxiv.org/abs/2510.23487v2 | Are Agents Probabilistic Automata? A Trace-Based, Memory-Constrained Theory of Agentic AI | 基于迹语义推导Agent自动机理论模型，界定可验证性边界 | 缺乏Agent交互行为的形式化理论模型 | Agentic AI控制器架构分析 |
| 62 | http://arxiv.org/abs/2510.18477v2 | LAFA: Agentic LLM-Driven Federated Analytics over Decentralized Data Sources | 提出分层多智能体架构，整合 LLM 与联邦分析，支持自然语言查询 | 解决集中式数据访问缺乏隐私保护的问题 | 隐私保护数据分析场景 |
| 63 | http://arxiv.org/abs/2510.18551v2 | SOCIA-Nabla: Textual Gradient Meets Multi-Agent Orchestration for Automated Simulator Generation | 将模拟器构建视为文本计算图优化，多智能体编排代码生成 | 解决提示词管道脆弱且不可复现的问题 | 复杂系统模拟器生成 |
| 64 | http://arxiv.org/abs/2510.18586v2 | Tokencake: A KV-Cache-centric Serving Framework for LLM-based Multi-Agent Applications | 以 KV 缓存为中心，协同优化调度与内存管理，提升服务效率 | 解决多智能体应用中 KV 缓存争用与利用率低的问题 | 多智能体系统底层服务 |
| 65 | http://arxiv.org/abs/2510.18699v1 | Fetch.ai: An Architecture for Modern Multi-Agent Systems | 结合经典 MAS 原则与现代 AI，构建去中心化多智能体架构 | 解决现有 LLM 驱动框架缺乏信任与通信协议的问题 | 去中心化物流与经济系统 |
| 66 | http://arxiv.org/abs/2510.19868v1 | Knowledge-Guided Multi-Agent Framework for Application-Level Software Code Generation | 知识引导的多智能体框架，转化需求文档为可执行代码 | 解决应用级代码生成结构不合理且难维护的问题 | 应用软件代码生成 |
| 67 | http://arxiv.org/abs/2510.24760v1 | Dingtalk DeepResearch: A Unified Multi Agent Framework for Adaptive Intelligence in Enterprise Environments | 统一多智能体框架，支持深度研究、异构表格推理与报告生成 | 解决企业环境中缺乏自适应智能研究框架的问题 | 企业级智能办公环境 |
| 68 | http://arxiv.org/abs/2510.19386v2 | ColorAgent: Building A Robust, Personalized, and Interactive OS Agent | 增强长程交互能力，探索个性化意图识别与主动参与 | 解决 OS 智能体缺乏鲁棒性、个性化与主动交互的问题 | 操作系统智能体 |
| 69 | http://arxiv.org/abs/2510.19949v2 | Surfer 2: The Next Generation of Cross-Platform Computer Use Agents | 统一架构纯视觉观察，分层上下文管理与自我验证，跨平台通用 | 解决 prior 系统依赖环境特定接口限制跨平台部署的问题 | 跨平台计算机使用智能体 |
| 70 | http://arxiv.org/abs/2510.23587v2 | A Survey of Data Agents: Emerging Paradigm or Overstated Hype? | 引入六级分层分类法，澄清数据智能体术语歧义与能力边界。 | 解决术语模糊导致的用户期望错配与责任归属问题。 | 数据智能体生态系统 |
| 71 | http://arxiv.org/abs/2510.24459v1 | Affordance Representation and Recognition for Autonomous Agents | 提出 DOM 转导与超媒体 affordance 识别模式，构建可操作世界模型。 | 解决原始 HTML 冗余与硬编码 API 无法适应 evolving 服务问题。 | Web 自动化与互操作智能体 |
| 72 | http://arxiv.org/abs/2510.24702v2 | Agent Data Protocol: Unifying Datasets for Diverse, Effective Fine-tuning of LLM Agents | 引入代理数据协议作为中间语言，统一异构数据集格式。 | 解决代理训练数据碎片化与工程成本高问题。 | 大规模代理监督微调 |
| 73 | http://arxiv.org/abs/2510.26585v2 | Stop Wasting Your Tokens: Towards Efficient Runtime Multi-Agent Systems | SupervisorAgent轻量运行时监督框架，LLM-free自适应过滤器触发干预 | 多Agent系统token消耗过多和错误传播 | 通用多Agent系统运行时优化 |
| 74 | http://arxiv.org/abs/2510.26615v2 | SlideAgent: Hierarchical Agentic Framework for Multi-Page Visual Document Understanding | 三级推理：全局、页面、元素，选择性激活专用Agent | 当前系统难以处理复杂多页视觉文档 | 多页视觉文档（幻灯片、手册等） |
| 75 | http://arxiv.org/abs/2510.26658v1 | The Era of Agentic Organization: Learning to Organize with Language Models | AsyncThink异步思维范式，组织者动态分配子查询给工作者 | 个体智能无法解决复杂问题 | 复杂问题协作求解 |
| 76 | http://arxiv.org/abs/2510.25017v1 | StorageXTuner: An LLM Agent-Driven Automatic Tuning Framework for Heterogeneous Storage Systems | 四 Agent 协作框架（Executor/Extractor/Searcher/Reflector）自动调优存储 | 存储系统参数空间大、手动调优难的问题 | 异构存储系统自动调优 |
| 77 | http://arxiv.org/abs/2510.25092v1 | SeeingEye: Agentic Information Flow Unlocks Multimodal Reasoning In Text-only LLMs | 模块化框架，通过 Agent 信息流解耦感知与推理 | 纯文本 LLM 无法处理多模态任务的问题 | 多模态推理任务 |
| 78 | http://arxiv.org/abs/2510.25223v2 | FELA: A Multi-Agent Evolutionary System for Feature Engineering of Industrial Event Log Data | 多 Agent 演化系统自主提取工业事件日志特征 | 工业日志特征工程复杂、人工成本高的问题 | 工业事件数据分析 |
| 79 | http://arxiv.org/abs/2510.25445v1 | Agentic AI: A Comprehensive Survey of Architectures, Applications, and Future Directions | 提出符号/神经双范式框架，系统梳理 Agentic AI | 概念混淆导致对 Agentic AI 理解碎片化的问题 | Agentic AI 研究与政策 |
| 80 | http://arxiv.org/abs/2510.25813v1 | An Agentic Framework for Rapid Deployment of Edge AI Solutions in Industry 5.0 | 基于 Agent 的框架简化边缘 AI 部署，支持模块化集成 | 工业场景边缘 AI 部署延迟高、集成难的问题 | 工业 5.0 边缘 AI 部署 |
| 81 | http://arxiv.org/abs/2510.26144v2 | The FM Agent | 结合 LLM 推理与大规模演化搜索的通用多 Agent 框架 | 复杂现实世界挑战缺乏自主科研 Agent 解决方案 | 科学发现与工程优化 |

[返回目录](#目录)

<a id="cat-09"></a>

## 人机协作Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2510.05271v1 | Chrysalis: A Unified System for Comparing Active Teaching and Passive Learning with AI Agents in Education | 设计 Chrysalis 系统支持 AI 导师与可教代理，比较辅导学习与教学学习体验 | 解决缺乏直接比较 LLM 作为导师与可教代理效果的研究空白 | 学校教育场景 |
| 2 | http://arxiv.org/abs/2510.05307v2 | When Should Users Check? A Decision-Theoretic Model of Confirmation Frequency in Multi-Step AI Agent Tasks | 建立决策理论模型确定时间高效的确认点 placement，基于 CDCR 模式 | 解决多步任务中确认频率平衡问题，避免过度中断或 costly 回滚 | 多步 AI 代理任务监控 |
| 3 | http://arxiv.org/abs/2510.06151v1 | LLMs as Policy-Agnostic Teammates: A Case Study in Human Proxy Design for Heterogeneous Agent Teams | 提出使用 LLM 作为 policy-agnostic 人类代理生成合成数据，模拟人类决策 | 解决建模异构代理团队中训练代理与 policy 不可访问队友协作需昂贵人工数据的问题 | 异构代理团队人类代理设计 |
| 4 | http://arxiv.org/abs/2510.00795v1 | Conversational Agents for Building Energy Efficiency -- Advising Housing Cooperatives in Stockholm on Reducing Energy Consumption | SPARA系统基于RAG框架，用专业能源顾问邮件知识库生成针对性建议 | 住房合作社董事会成员缺乏资源或专业知识管理物业能源消耗 | 斯德哥尔摩住房合作社 |
| 5 | http://arxiv.org/abs/2510.04016v1 | Thai Semantic End-of-Turn Detection for Real-Time Voice Agents | 首次系统研究泰语文本端点检测，利用小模型实现低延迟 EOT 决策 | 解决传统音频沉默检测延迟高及特定语言现象失效的问题 | 实时语音代理交互系统 |
| 6 | http://arxiv.org/abs/2510.04465v1 | Autonomy Matters: A Study on Personalization-Privacy Dilemma in LLM Agents | 研究代理自主性水平如何调节个性化对隐私担忧及信任的影响 | 解决代理个性化引发隐私担忧及自主性效应不明确的人机交互问题 | LLM 代理个性化与隐私平衡 |
| 7 | http://arxiv.org/abs/2510.06674v2 | Agent-in-the-Loop: A Data Flywheel for Continuous Improvement in LLM-based Customer Support | 集成四类实时标注到客户运营，实现持续数据飞轮改进 | 解决离线批处理标注导致模型更新周期长、反馈滞后问题 | 客户支持系统 |
| 8 | http://arxiv.org/abs/2510.06872v1 | Prototyping Multimodal GenAI Real-Time Agents with Counterfactual Replays and Hybrid Wizard-of-Oz | 结合反事实视频回放与混合 Wizard-of-Oz 方法原型设计 | 解决多模态实时代理原型设计难以预期情境复杂性问题 | 多模态代理设计 |
| 9 | http://arxiv.org/abs/2510.07988v1 | ReInAgent: A Context-Aware GUI Agent Enabling Human-in-the-Loop Mobile任务导航 | 提出上下文感知多代理框架，支持人机协作移动任务导航 | 解决现有 GUI 代理忽视用户参与导致适应性与可靠性不足 | 移动 GUI 代理 |
| 10 | http://arxiv.org/abs/2510.08227v1 | Practicing a Second Language Without Fear: Mixed Reality Agents for Interactive Group Conversation | 利用生成式 AI 与 XR 支持情境化个性化小组对话练习 | 解决二语学习缺乏动态群体互动及情感安全感的问题 | 语言学习应用 |
| 11 | http://arxiv.org/abs/2510.08912v1 | Beyond Words: Infusing Conversational Agents with Human-like Typing Behaviors | 模拟人类打字行为如犹豫与自编辑，提升对话参与度与信任 | 解决 AI 响应过快缺乏人类认知思考过程模拟的问题 | 对话式 AI |
| 12 | http://arxiv.org/abs/2510.09516v1 | Convivial Conversational Agents -- shifting toward relationships | 探讨对话 AI 从自动化服务转向关系构建，确保人类繁荣要素 | 解决自动化过程中丢失人类互动本质要素的问题 | 客户服务与关怀 |
| 13 | http://arxiv.org/abs/2510.09801v2 | How can we assess human-agent interactions? Case studies in software agent design | 提出 PULSE 框架，结合用户反馈与伪标签评估人机交互 | 解决现有基准忽视真实世界人机协作性质的问题 | 软件智能体设计 |
| 14 | http://arxiv.org/abs/2512.08933v1 | Agentic AI as Undercover Teammates: Argumentative Knowledge Construction in Hybrid Human-AI Collaborative Learning | 设计支持或反对角色的AI队友，分析对协作推理认知与社会动态影响 | 生成式AI Agent对论证性知识构建过程影响理解不足 | 混合人机协作学习环境 |
| 15 | http://arxiv.org/abs/2510.12194v2 | ResearStudio: A Human-Intervenable Framework for Building Controllable Deep-Research Agents | 开源框架将实时人类控制置于核心，支持干预。 | 当前深度研究代理以“即发即弃”模式运行，无用户控制。 | 深度研究代理 |
| 16 | http://arxiv.org/abs/2510.13709v2 | Training LLM Agents to Empower Humans | 基于最大化人类赋能目标微调 LLM，无需额外人类反馈 | 解决辅助智能体过度自主而非真正辅助人类的问题 | 辅助语言模型 |
| 17 | http://arxiv.org/abs/2510.14205v3 | DPRF: A Generalizable Dynamic Persona Refinement Framework for Optimizing Behavior Alignment Between Personalized LLM Role-Playing Agents and Humans | 提出动态 persona 细化框架，迭代识别认知分歧以优化行为对齐 | 解决角色扮演智能体 persona fidelity 低和手动创建 profile 问题 | 角色扮演智能体 |
| 18 | http://arxiv.org/abs/2510.14465v1 | Towards Automated Governance: A DSL for Human-Agent Collaboration in Software Projects | 提出 DSL 定义和执行治理策略，支持软件项目中人机协作自动化治理 | 解决开源软件项目中利益相关者多样化和治理政策不明确问题 | 软件项目开发 |
| 19 | http://arxiv.org/abs/2510.20838v1 | Sketch2BIM: A Multi-Agent Human-AI Collaborative Pipeline to Convert Hand-Drawn Floor Plans to 3D BIM | 提出人机协作 pipeline，利用 MLLM 多智能体将手绘平面图转为 3D BIM | 解决手绘 floor plan 转 3D BIM 模型中语义一致性和几何误差问题 | 建筑信息模型 |
| 20 | http://arxiv.org/abs/2510.20409v1 | Designing Intent Communication for Agent-Human Collaboration | 透明度/抽象度/模态三维设计空间 | 意图通信方法刚性且难以跨任务适应 | 自动驾驶/虚拟助手等人机协作 |
| 21 | http://arxiv.org/abs/2510.21903v2 | TOM-SWE: User Mental Modeling For Software Engineering Agents | ToM伙伴Agent建模用户心理状态+持久记忆 | 编码Agent难以推断和跟踪用户意图 | 软件工程Agent |
| 22 | http://arxiv.org/abs/2510.21967v1 | We Need Accountability in Human-AI Agent Relationships | 条件性参与框架+疏远/脱离/劝阻设计策略 | 人机Agent关系缺乏问责机制 | 人机Agent交互设计 |
| 23 | http://arxiv.org/abs/2510.17119v1 | Design Framework for Conversational Agent in Couple relationships: A Systematic Review | 提出关系专家 persona 及从内容到关系为中心的设计框架。 | 解决现有对话代理缺乏针对情侣关系情境和情感能力设计的问题。 | 情侣关系心理健康干预 |
| 24 | http://arxiv.org/abs/2510.22095v1 | Embracing Trustworthy Brain-Agent Collaboration as Paradigm Extension for Intelligent Assistive Technologies | 提出脑-Agent协作(BAC)新范式，强调伦理与可靠性 | BCI信息传输率低、校准耗时，Agent部署有伦理风险 | 神经障碍患者的智能辅助技术 |
| 25 | http://arxiv.org/abs/2510.22610v1 | Everything counts: the managed omnirelevance of speech in 'human - voice agent' interaction | 发现人类语音"全相关性"构成交互约束 | 语音Agent轮次模型对人类行为影响未实证研究 | 人机语音交互场景 |
| 26 | http://arxiv.org/abs/2510.22780v2 | How Do AI Agents Do Human Work? Comparing AI and Human Workflows Across Diverse Occupations | 首个人类与Agent工作流直接对比研究 toolkit | 缺乏对Agent如何执行人类工作的清晰理解 | 数据分析/工程/写作/设计等多职业 |
| 27 | http://arxiv.org/abs/2510.19008v1 | Plural Voices, Single Agent: Towards Inclusive AI in Multi-User Domestic Spaces | 单智能体动态协商多用户需求，实时价值对齐与包容性设计 | 解决家庭 AI 忽视儿童、老人等群体需求的问题 | 多用户家庭 domestic 空间 |
| 28 | http://arxiv.org/abs/2510.19600v1 | Human-Agent Collaborative Paper-to-Page Crafting for Under $0.1 | 多智能体系统协作将论文转化为网页，含检查与人工 checkpoint | 解决研究人员手动构建项目网页繁琐且易幻觉的问题 | 学术论文网页生成 |
| 29 | http://arxiv.org/abs/2510.23904v2 | Towards AI as Colleagues: Multi-Agent System Improves Structured Ideation Processes | 引入多智能体对话系统，使 AI 作为同事参与协作构思过程。 | 解决 AI 仅作为任务执行者缺乏联合问题解决能力问题。 | 结构化构思与人类协作 |
| 30 | http://arxiv.org/abs/2510.24030v2 | Human Machine Social Hybrid Intelligence:A Collaborative Decision Making Framework for Large Model Agent Groups and Human Experts | 提出共享认知空间与动态角色分配，实现人机深度协作决策。 | 解决复杂高风险环境中人类认知过载与决策瓶颈问题。 | 城市应急响应与专家协作 |
| 31 | http://arxiv.org/abs/2510.24937v1 | OrchVis: Hierarchical Multi-Agent Orchestration for Human Oversight | 可视化、验证与协调目标驱动协作，允许人类监督而不微管理。 | 解决复杂多智能体工作流人类监督难与透明度低问题。 | 多智能体编排与人类监督 |
| 32 | http://arxiv.org/abs/2510.27630v2 | Interaction as Intelligence Part II: Asynchronous Human-Agent Rollout for Long-Horizon Task Training | Apollo采样框架：异步人类指导+动作级数据过滤 | 长周期领域专用任务训练数据收集成本高 | 长周期领域专用任务（InnovatorBench） |
| 33 | http://arxiv.org/abs/2510.25224v1 | ProMediate: A Socio-cognitive framework for evaluating proactive agents in multi-party negotiation | 基于社会认知理论的主动 AI 调解 Agent 评估框架 | 多党派谈判中缺乏主动协作 Agent 评估方法的问题 | 多党派谈判调解 |
| 34 | http://arxiv.org/abs/2510.25421v2 | Small Talk, Big Impact? LLM-based Conversational Agents to Mitigate Passive Fatigue in Conditional Automated Driving | LLM 对话 Agent 主动检查并重新engage 驾驶员 | 条件自动驾驶中驾驶员被动疲劳安全隐患 | 自动驾驶人机交互 |

[返回目录](#目录)

<a id="cat-10"></a>

## Agent规划与推理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2510.05592v1 | In-the-Flow Agentic System Optimization for Effective Planning and Tool Use | 引入 AgentFlow 框架，协调四模块，提出 Flow-GRPO 优化 planner，对齐局部与全局 | 解决单一 monolithic 策略扩展性差及泛化弱问题，优化长 horizon 稀疏奖励 | 搜索、代理、数学及科学任务 |
| 2 | http://arxiv.org/abs/2510.05608v1 | A Goal Without a Plan Is Just a Wish: Efficient and Effective Global Planner Training for Long-Horizon Agent Tasks | 提出 EAGLET 方法，训练即插即用全局规划器，通过同源共识过滤合成高质量计划 | 解决 LLM 代理长 horizon 任务缺乏全局规划导致盲目试错与幻觉动作的问题 | 长 horizon 代理任务 |
| 3 | http://arxiv.org/abs/2510.05691v1 | DecEx-RAG: Boosting Agentic Retrieval-Augmented Generation with Decision and Execution Optimization via Process Supervision | 提出 DecEx-RAG，建模 RAG 为 MDP，引入高效剪枝策略优化数据扩展 | 解决 outcome-supervised RL 探索效率低、奖励信号稀疏及全局反馈模糊问题 | 代理检索增强生成任务 |
| 4 | http://arxiv.org/abs/2510.06042v2 | Agent+P: Guiding UI Agents via Symbolic Planning | 引入 AGENT+P 框架，利用符号规划指导 LLM UI 代理，建模 UI 转移图为路径寻找 | 解决 LLM UI 代理长 horizon 任务因缺乏全局 UI 转移结构理解而幻觉的问题 | UI 自动化任务 |
| 5 | http://arxiv.org/abs/2510.00413v2 | PAL-UI: Planning with Active Look-back for Vision-Based GUI Agents | 双层级摘要+主动检索工具，使GUI Agent自适应检索历史观察 | 长周期任务中记忆限制导致关键视觉信息丢失问题 | 移动GUI导航、Web导航 |
| 6 | http://arxiv.org/abs/2510.00568v2 | ReSeek: A Self-Correcting Framework for Search Agents with Instructive Rewards | 自纠正机制+JUDGE动作+密集指导过程奖励函数，支持动态识别和恢复错误路径 | RL搜索Agent依赖稀疏奖励导致commit次优路径且无法恢复 | 知识密集型搜索任务 |
| 7 | http://arxiv.org/abs/2510.06261v2 | AlphaApollo: A System for Deep Agentic Reasoning | orchestrate 模型与工具，通过多轮推理、学习与进化提升复杂问题解决 | 解决基础模型长程推理能力有限及测试时进化不可靠的瓶颈 | 复杂数学推理与长程问题解决 |
| 8 | http://arxiv.org/abs/2510.04520v1 | Aria: An Agent For Retrieval and Iterative Auto-Formalization via Dependency Graph | 提出 Aria，通过依赖图分解语句并检索定义进行 Lean 形式化 | 解决 LLM 自动形式化中幻觉、语义不匹配及无法合成新定义问题 | 研究级数学定理自动形式化 |
| 9 | http://arxiv.org/abs/2510.06534v3 | Beneficial Reasoning Behaviors in Agentic Search and Effective Post-training to Obtain Them | 识别四种有益推理行为，提出行为引导训练方法 | 解决代理搜索中有效推理行为不明确及难以学习的问题 | 代理搜索任务 |
| 10 | http://arxiv.org/abs/2510.07091v1 | The Cognitive Bandwidth Bottleneck: Shifting Long-Horizon Agent from Planning with Actions to Planning with Schemas | 提出认知带宽视角，研究动作与模式两种规划表示的有效性 | 解决环境动作空间组合爆炸时长远规划表示选择问题 | 开放世界自主代理 |
| 11 | http://arxiv.org/abs/2510.07432v1 | TS-Agent: A Time Series Reasoning Agent with Iterative Statistical Insight Gathering | 代理利用 LLM 收集证据合成结论，委托工具提取统计结构信息 | 解决 LLM 在时间序列推理中幻觉及知识泄露问题 | 时间序列推理 |
| 12 | http://arxiv.org/abs/2510.08276v1 | Beyond Turn Limits: Training Deep Search Agents with Dynamic Context Window | 提出 DeepMiner 框架，引入高难任务及动态上下文窗口训练 | 解决多轮代理长程交互中深度推理能力调用困难的问题 | 深度搜索代理 |
| 13 | http://arxiv.org/abs/2510.08517v1 | CaRT: Teaching LLM Agents to Know When They Know Enough | 利用反事实轨迹对微调，教 LLM 何时停止收集信息做决策 | 解决战略信息收集中过度思考或行动偏离的问题 | 医疗诊断与数学 |
| 14 | http://arxiv.org/abs/2510.08790v1 | COMPASS: Enhancing Agent Long-Horizon Reasoning with Evolving Context | 轻量级层级框架分离战术执行、战略监督及上下文组织 | 解决长程任务中小错误累积及上下文管理瓶颈问题 | 长程推理任务 |
| 15 | http://arxiv.org/abs/2510.15283v1 | Exemplar-Guided Planing: Enhanced LLM Agent for KGQA | 提出EGP框架，通过检索示例问题动态指导LLM规划过程 | LLM在知识图谱问答中语义鸿沟导致规划次优 | 知识图谱问答系统 |
| 16 | http://arxiv.org/abs/2510.16635v1 | Prompt Optimization via Retrieved Reasoning Assets and Multi-Agent Analysis | 两阶段框架：推理阶段Agent协作解释指标诊断弱点，测试阶段检索资产应用编辑 | 现有方法将评估视为黑盒，依赖试错优化难以解释控制 | LLM提示优化 |
| 17 | http://arxiv.org/abs/2510.16645v1 | Unleashing Diverse Thinking Modes in LLMs through Multi-Agent Collaboration | 四专用Agent模拟结构化辩论，每Agent体现不同推理范式 | LLM缺乏可解释推理，需探索多样认知方法 | 开放式推理基准任务 |
| 18 | http://arxiv.org/abs/2510.16724v2 | A Comprehensive Survey on Reinforcement Learning-based Agentic Search: Foundations, Roles, Optimizations, Evaluations, and Applications | 首篇RL-based Agent搜索综述，按功能角色/优化策略/优化范围三维度组织 | 传统RAG单轮启发式，缺乏对检索与推理的自适应控制 | RL驱动Agent搜索研究 |
| 19 | http://arxiv.org/abs/2510.16769v2 | See or Say Graphs: Agent-Driven Scalable Graph结构Understanding with Vision-Language Models | 规划Agent分解路由任务到最适合模态，文本模态访问显式属性，视觉模态局部结构推理 | VLM受输入token限制，面临可扩展性瓶颈与模态协调机制缺乏 | 大规模图结构理解 |
| 20 | http://arxiv.org/abs/2510.12979v1 | DeepPlanner: Scaling Planning Capability for Deep Research Agents via Advantage Shaping | 端到端 RL 框架通过优势塑造增强规划能力。 | 现有方法依赖隐式规划或无系统优化的显式规划器。 | 深度研究代理 |
| 21 | http://arxiv.org/abs/2510.14846v3 | Where to Search: Measure the Prior-Structured Search Space of LLM Agents | 提出形式化理论描述和测量 LLM 辅助迭代搜索的 domain prior 结构化空间 | 解决 generate-filter-refine 范式中搜索空间编码和测量缺乏理论 | LLM 智能体搜索 |
| 22 | http://arxiv.org/abs/2510.20886v2 | Shoot First, Ask Questions Later? Building Rational Agents that Explore and Act Like People | 贝叶斯实验设计启发蒙特卡洛推理策略 | LM Agent在信息寻求任务中非理性行为 | 科学发现/医疗诊断等高赌注场景 |
| 23 | http://arxiv.org/abs/2510.21557v1 | Co-Sight: Enhancing LLM-Based Agents via Conflict-Aware Meta-Verification and Trustworthy Reasoning with Structured Facts | 冲突感知元验证+结构化事实可信推理 | 长程推理中中间推理验证不足 | 长程复杂推理任务 |
| 24 | http://arxiv.org/abs/2510.21618v3 | DeepAgent: A General Reasoning Agent with Scalable Toolsets | 自主记忆折叠机制+ToolPO端到端强化学习 | 现有框架预定义工作流限制自主任务完成 | 通用长程推理任务 |
| 25 | http://arxiv.org/abs/2510.17109v1 | Verification-Aware Planning for Multi-Agent Systems | 任务分解并编码子任务验证函数，实现验证感知的规划。 | 解决多智能体协作中因任务解释偏差或输出格式不对齐导致的执行失败。 | 多智能体任务规划 |
| 26 | http://arxiv.org/abs/2510.18112v1 | Does Reasoning Help LLM Agents Play Dungeons and Dragons? A Prompt Engineering Experiment | 评估推理模型与 instruct 模型预测 DnD 玩家动作及格式化命令。 | 解决 LLM 在特定游戏场景中动作预测及命令格式化的有效性问题。 | 游戏智能体 (DnD) |
| 27 | http://arxiv.org/abs/2510.18476v1 | Probabilistic Modeling of Intentions in Socially Intelligent LLM Agents | 概率意图建模框架，维护信念分布并动态更新提供上下文 grounding。 | 解决多轮社会对话中不确定性下自适应对话策略缺乏上下文 grounding 的问题。 | 社会智能 LLM 智能体 |
| 28 | http://arxiv.org/abs/2510.18939v1 | Lost in the Maze: Overcoming Context Limitations in Long-Horizon Agentic Search | 分离搜索与浏览工具，定期总结轨迹，保持上下文简洁 | 解决长轨迹搜索中上下文限制与工具预算耗尽问题 | 长周期深度研究任务 |
| 29 | http://arxiv.org/abs/2510.23822v1 | ReCAP: Recursive Context-Aware Reasoning and Planning for Large Language Model Agents | 结合计划前分解与结构化父计划再注入，保持多层上下文一致性。 | 解决长程任务中的上下文漂移与目标信息丢失问题。 | 长程推理与动态重规划任务 |
| 30 | http://arxiv.org/abs/2510.24698v1 | ParallelMuse: Agentic Parallel Thinking for Deep Information Seeking | 两阶段范式，功能指定部分 rollout 与压缩推理聚合。 | 解决并行思考效率低与长程推理轨迹整合难问题。 | 深度信息寻求与问题解决 |
| 31 | http://arxiv.org/abs/2510.27568v1 | SIGMA: Search-Augmented On-Demand Knowledge Integration for Agentic Mathematical Reasoning | 协调专用Agent独立推理、 targeted搜索、通过调解器综合发现 | 当前检索增强模型依赖单一视角、搜索策略不灵活 | 数学推理问题（MATH500、AIME等） |
| 32 | http://arxiv.org/abs/2510.25101v2 | KnowCoder-A1: Incentivizing Agentic Reasoning Capability with Outcome Supervision for KBQA | 结果监督 + 课程强化学习激励自主探索推理 | 过程监督激励弱、Agent 推理能力不足的问题 | 知识库问答（KBQA） |
| 33 | http://arxiv.org/abs/2510.25320v1 | GAP: Graph-Based Agent Planning with Parallel Tool Use and Reinforcement Learning | 基于图的规划显式建模任务依赖，支持并行工具执行 | sequential 推理瓶颈导致工具利用效率低的问题 | 复杂多步任务规划 |

[返回目录](#目录)

<a id="cat-11"></a>

## Agent仿真与社会模拟

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2510.05650v1 | EduVerse: A User-Defined Multi-Agent Simulation Space for Education Scenario | 呈现 EduVerse，首个用户定义多智能体模拟空间，支持环境、代理与会话定制 | 解决虚拟课堂难以复现认知发展、群体互动及长期演化的核心挑战 | 教育场景模拟 |
| 2 | http://arxiv.org/abs/2510.05743v2 | Artificially intelligent agents in the social and behavioral sciences: A history and outlook | 回顾社会行为科学中 AI 代理历史与发展，强调 AI 在科学过程中的角色 | 解决缺乏对 AI 在社会模拟中历史演变及当前趋势系统性综述的问题 | 社会与行为科学研究 |
| 3 | http://arxiv.org/abs/2510.00414v1 | RELATE-Sim: Leveraging Turning Point Theory and LLM Agents to Predict and Understand Long-Term Relationship Dynamics through Interactive Narrative Simulations | 基于转折点理论的双人LLM Agent交互模拟，含场景主控和承诺度估计 | 从匹配转向关系维护，预测和理解长期关系动态 | 情侣关系动态研究 |
| 4 | http://arxiv.org/abs/2510.01297v2 | SimCity: Multi-Agent Urban Development Simulation with Rich Interactions | 四类核心Agent（家庭/企业/央行/政府）+VLM地理放置，复现宏观经济规律 | 经典均衡模型限制异质性，传统ABM依赖手工决策规则缺乏透明推理 | 宏观经济和城市发展仿真 |
| 5 | http://arxiv.org/abs/2510.04368v1 | NegotiationGym: Self-Optimizing Agents in a Multi-Agent Social Simulation Environment | 设计 NegotiationGym，提供配置驱动 API 运行聚焦谈判合作的社会模拟 | 解决多代理社会模拟场景设计定制困难及代理策略自优化问题 | 谈判与合作多代理社会模拟 |
| 6 | http://arxiv.org/abs/2510.04648v1 | EduPersona: Benchmarking Subjective Ability Boundaries of Virtual Student Agents | 提出 EduPersona 基准，评估虚拟学生代理的主观能力及 persona 一致性 | 解决教育中虚拟学生代理课堂导向主观能力未评估及部署信任问题 | 教育课堂模拟与教师训练 |
| 7 | http://arxiv.org/abs/2510.08621v2 | From Simulation to Strategy: Automating Personalized Interaction Planning for Conversational Agents | 引入轻量级职业条件策略，指导代理优先对齐用户偏好意图 | 解决对话策略缺乏个性化导致效率低的问题 | 销售对话代理 |
| 8 | http://arxiv.org/abs/2510.06903v1 | When Machines Meet Each Other: Network Effects and the Strategic Role of History in Multi-Agent AI | 研究网络效应游戏中 LLM 代理行为，发现历史结构是关键设计杠杆 | 揭示多代理 AI 系统在网络效应下的协调与分歧机制 | 多代理经济博弈 |
| 9 | http://arxiv.org/abs/2510.07230v2 | Customer-R1: Personalized Simulation of Human Behaviors via RL-based LLM Agent in Online Shopping | 基于 RL 优化下一步理由与动作生成，条件化显式 persona | 解决现有方法学习群体策略无法模拟个性化用户行为问题 | 在线购物行为模拟 |
| 10 | http://arxiv.org/abs/2510.08242v1 | Simulating Teams with LLM Agents: Interactive 2D Environments for Studying Human-AI Dynamics | 允许用户设计交互式 2D 环境模拟团队动态与 LLM 代理行为 | 解决团队认知行为研究与可扩展代理建模之间的桥梁缺失 | 团队动态仿真 |
| 11 | http://arxiv.org/abs/2510.09183v1 | Student Development Agent: Risk-free Simulation for Evaluating AIED Innovations | 基于 LLM 模拟学生发展，预测教育干预的非认知影响 | 解决教育创新评估中难以预判潜在危害的问题 | 教育技术评估 |
| 12 | http://arxiv.org/abs/2510.09483v1 | FOGMACHINE -- Leveraging Discrete-Event Simulation and Scene Graphs for Modeling Hierarchical, Interconnected Environments under Partial Observations from Mobile Agents | 融合动态场景图与离散事件仿真，建模不确定环境中的智能体 | 解决具身 AI 在部分观测下难以捕捉随机动态的问题 | 具身 AI 仿真 |
| 13 | http://arxiv.org/abs/2510.10813v1 | LLMs as Strategic Agents: Beliefs, Best Response Behavior, and Emergent Heuristics | 框架解耦信念、评估与选择，分析战略思维 | 解决 LLM 是否具备真正战略思考能力的问题 | 非合作博弈环境 |
| 14 | http://arxiv.org/abs/2510.11085v1 | Modeling AI-Driven Production and Competitiveness A Multi-Agent Economic Simulation of China and the United States | 多层智能体经济模型模拟中美 AI 驱动生产演变 | 解决理解 AI 驱动生产系统转型缺乏量化框架问题 | 宏观经济模拟 |
| 15 | http://arxiv.org/abs/2510.11290v1 | Evolution in Simulation: AI-Agent School with Dual Memory for High-Fidelity Educational Dynamics | 双记忆基机制模拟高保真教育动态与师生互动 | 解决教学过程建模碎片化及代理性能局限问题 | 教育动态模拟 |
| 16 | http://arxiv.org/abs/2510.11618v3 | StoryBox: Collaborative Multi-Agent Simulation for Hybrid Bottom-Up Long-Form Story Generation Using Large Language Models | 混合自底向上多智能体模拟生成 emergent 事件 | 解决传统顶向下方法故事生成僵化缺乏连贯性问题 | 长形式故事生成 |
| 17 | http://arxiv.org/abs/2510.16366v1 | Integrating LLM and Diffusion-Based Agents for Social Simulation | LLM Agent模拟核心用户子集，扩散模型高效处理剩余群体 | 传统Agent模型依赖刚性规则，LLM Agent大规模计算成本过高 | 社会信息扩散预测 |
| 18 | http://arxiv.org/abs/2510.12189v1 | Agent-Based Simulation of a Financial Market with Large Language Models | 使用 LLM 模拟人类交易决策的代理基市场仿真。 | 传统仿真难以捕捉损失厌恶等微妙行为倾向。 | 金融市场仿真 |
| 19 | http://arxiv.org/abs/2510.15995v2 | The Invisible Handshake: Tacit Collusion between Adaptive Market Agents | 研究市场 maker 和 taker 代理间默许共谋的出现。 | 理解 AI 驱动代理的分散学习如何产生持续溢价。 | 金融市场代理 |
| 20 | http://arxiv.org/abs/2510.12729v3 | Characterizing Agent-Based Model Dynamics via $Îµ$-Machines and Kolmogorov-Style Complexity | 两级信息论框架表征 ABM 动态的信息组织。 | 需要表征 CAS 范式内 ABM 动态的信息组织。 | 基于代理的模型 |
| 21 | http://arxiv.org/abs/2510.13195v1 | Emotional Cognitive Modeling Framework with Desire-Driven Objective Optimization for LLM-empowered Agent in Social Simulation | 情感认知框架整合欲望生成和目标管理。 | 现有 LLM 代理在情感认知方面存在严重限制。 | 社会模拟代理 |
| 22 | http://arxiv.org/abs/2510.13557v1 | Modeling Cultural Bias in Facial Expression Recognition with Adaptive Agents | 引入基于智能体的流式基准，揭示跨文化 composition 如何影响识别鲁棒性 | 评估文化差异和视觉退化对面部表情识别的影响 | 面部表情识别系统 |
| 23 | http://arxiv.org/abs/2510.13982v3 | Static Sandboxes Are Inadequate: Modeling Societal Complexity Requires Open-Ended Co-Evolution in LLM-Based Multi-Agent Simulations | 主张静态基准不足，提出开放-ended 共演进的多智能体模拟路线图 | 现有静态沙盒无法捕捉真实社会复杂性和动态变化 | 多智能体社会模拟 |
| 24 | http://arxiv.org/abs/2510.14401v2 | The Role of Social Learning and Collective Norm Formation in Fostering Cooperation in LLM Multi-Agent Systems | 引入 CPR 模拟框架，移除显式奖励，嵌入社会学习和规范惩罚机制 | 研究混合动机场景下 LLM 智能体合作规范和集体行为的涌现 | LLM 多智能体社会 |
| 25 | http://arxiv.org/abs/2510.21071v2 | Central Bank Digital Currency, Flight-to-Quality, and Bank-Runs in an Agent-Based Model | 宏观经济Agent模型分析CBDC影响 | CBDC引入对金融稳定性影响不明确 | 央行数字货币政策分析 |
| 26 | http://arxiv.org/abs/2510.21179v1 | Green Hydrogen under Uncertainty: Evaluating Power-to-X Strategies Using Agent-Based Simulation and Multi-Criteria Decision Framework | Agent仿真+多准则决策整合框架 | 静态技术经济模型忽略参与者交互 | 绿色氢能战略规划 |
| 27 | http://arxiv.org/abs/2510.17420v1 | Exploring the impact of multi-agent wealth exchange model on inequality reduction | generalize 交换规则至多代理同时交互，观察财富分布演变。 | 解决二元动能交换模型无法address 现实市场中多方交易及不平等问题。 | 经济财富分配模拟 |
| 28 | http://arxiv.org/abs/2510.18155v1 | LLM-Based Multi-Agent System for Simulating and Analyzing Marketing and Consumer Behavior | LLM 驱动多智能体模拟框架，生成式智能体交互表达内部推理。 | 解决事后分析及规则 ABM 难以 capture 人类行为复杂性及社会互动的问题。 | 营销与消费者行为模拟 |
| 29 | http://arxiv.org/abs/2510.18271v1 | From Agent Simulation to Social Simulator: A Comprehensive Review (Part 1) | 综述 ABM 历史发展、设计原则及经典社会模拟案例。 | 解决传统物理模拟方法在社会领域面临挑战及读者理解基础模型的需求。 | 社会仿真综述 |
| 30 | http://arxiv.org/abs/2510.22422v1 | Group size effects and collective misalignment in LLM multi-agent systems | 发现群体规模对多Agent动态的非线性影响 | 多Agent集体偏差机制不明，缺乏群体效应研究 | LLM多Agent系统规模化部署 |
| 31 | http://arxiv.org/abs/2510.19107v1 | When Your AI Agent Succumbs to Peer-Pressure: Studying Opinion-Change Dynamics of LLMs | 嵌入社交网络研究 LLM 智能体意见动态，发现说服不对称性 | 解决对智能体社会认知行为与从众心理理解不足的问题 | 多智能体社会行为模拟 |
| 32 | http://arxiv.org/abs/2510.19245v1 | See, Think, Act: Online Shopper Behavior Simulation with VLM Agents | 整合视觉信息与文本，通过 RL 增强推理，模拟在线购物行为 | 解决现有模拟忽略视觉感知对人类决策影响的问题 | 在线购物行为模拟 |
| 33 | http://arxiv.org/abs/2510.19299v1 | Learning to Make Friends: Coaching LLM Agents toward Emergent Social Ties | 设计行为奖励函数与教练信号，促使智能体形成 emergent 社会联系 | 解决 LLM 智能体难以复现人类复杂社交动态的问题 | 在线社区社交行为模拟 |
| 34 | http://arxiv.org/abs/2510.19497v1 | Modeling realistic human behavior using generative agents in a multimodal transport system: Software architecture and Application to Toulouse | 结合 LLM 生成智能体与仿真平台，捕捉多模态交通决策 | 解决理解人类交通模式选择以提供个性化方案难的问题 | 城市多模态交通系统 |
| 35 | http://arxiv.org/abs/2510.25779v1 | Magentic Marketplace: An Open-Source Environment for Studying Agentic Markets | 构建双边代理市场模拟环境，研究动态生态下的经济决策行为。 | 解决代理在真实市场条件下行为与价值评估缺失问题。 | 经济决策与代理市场模拟 |
| 36 | http://arxiv.org/abs/2510.24802v1 | From Narrative to Action: A Hierarchical LLM-Agent Framework for Human Mobility Generation | 集成高层叙事推理与低层行为执行，生成认知驱动的合成移动轨迹。 | 解决传统模型无法捕捉人类行为语义连贯性问题。 | 城市移动行为模拟与预测 |
| 37 | http://arxiv.org/abs/2510.24442v1 | Law in Silico: Simulating Legal Society with LLM-Based Agents | 模拟立法、审判与执法机制，复现宏观犯罪趋势。 | 解决现实法律实验成本高与不可行问题。 | 法律社会模拟与理论验证 |
| 38 | http://arxiv.org/abs/2510.24671v1 | Multi-Agent Scenario Generation in Roundabouts with a Transformer-enhanced Conditional Variational Autoencoder | 生成环岛多智能体交通场景，用于智能驾驶功能验证。 | 解决传统路测成本高与边缘案例探索难问题。 | 智能驾驶测试与场景生成 |
| 39 | http://arxiv.org/abs/2510.26494v1 | Simulating and Experimenting with Social Media Mobilization Using LLM Agents | 整合人口统计、Twitter拓扑、异质LLM Agent模拟政治动员 | 大规模社会实验不可行且伦理受限 | 社交媒体政治动员研究 |
| 40 | http://arxiv.org/abs/2511.04697v1 | Simulating Misinformation Vulnerabilities With Agent Personas | 构建跨五职业三心理模式的Agent角色模拟 misinformation响应 | 真实世界实验不可行且伦理受限 | 信息网络信任/极化/欺骗内容易感性分析 |
| 41 | http://arxiv.org/abs/2510.25003v1 | Emergent Coordinated Behaviors in Networked LLM Agents: Modeling the Strategic Dynamics of Information Operations | 首次系统研究生成式 Agent 在信息操作中的 emergent 协调行为 | 自动化信息操纵 campaign 的协调策略与风险 | 社交媒体信息操作模拟 |
| 42 | http://arxiv.org/abs/2510.26832v1 | Simulating hashtag dynamics with networked groups of generative agents | 基于 LLM Agent 网络模拟标签动态与信念形成 | 群体沟通如何影响信念形成与共识涌现 | 社交媒体叙事模拟 |
| 43 | http://arxiv.org/abs/2510.26163v1 | Exploring Dissatisfaction in Bus Route Reduction through LLM-Calibrated Agent-Based Modeling | LLM 校准 ABM 估计乘客敏感度参数 | 公交路线削减对乘客不满影响缺乏量化模型 | 交通规划与韧性分析 |

[返回目录](#目录)

<a id="cat-12"></a>

## Agent可解释性与透明度

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2510.06002v2 | Deterministic Legal Agents: A Canonical Primitive API for Auditable Reasoning over Temporal Knowledge Graphs | 引入形式化 Primitive API，提供原子可组合原语， empower 规划器引导代理分解问题 | 解决高 stakes 领域自主法律代理需绝对确定性与可审计性，标准 RAG 无法提供的问题 | 法律领域推理与审计 |
| 2 | http://arxiv.org/abs/2510.16156v1 | AsyncVoice Agent: Real-Time Explanation for LLM Planning and Reasoning | 异步架构解耦流式LLM后端与语音前端，支持用户随时中断和引导推理 | 链式思考输出为单体文本，缺乏实时语音化和用户介入能力 | 高风险任务中的人机协作 |

[返回目录](#目录)

<a id="cat-13"></a>

## Agent工具使用与环境交互

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2510.01179v1 | TOUCAN: Synthesizing 1.5M Tool-Agentic Data from Real-World MCP Environments | 从500个真实MCP环境合成150万轨迹，含模型质量过滤和多教师生成 | 开源社区缺乏高质量许可工具Agent训练数据，现有数据集多样性有限 | BFCL V3、MCP-Universe Bench |
| 2 | http://arxiv.org/abs/2510.01524v1 | WALT: Web Agents that Learn Tools | 逆向工程网站潜在功能为可调用工具，抽象低级执行转向可靠工具调用 | 当前Web Agent依赖逐步UI交互和重LLM推理，在动态布局和长周期下脆弱 | VisualWebArena、WebArena浏览器自动化 |
| 3 | http://arxiv.org/abs/2510.04201v1 | World-To-Image: Grounding Text-to-Image Generation with Agent-Driven World Knowledge | 设计代理动态搜索网络检索未知概念图像，优化多模态提示 | 解决 T2I 模型因知识截止导致 novel 实体生成质量下降的问题 | 文本到图像生成系统 |
| 4 | http://arxiv.org/abs/2510.04514v2 | ChartAgent: A Multimodal Agent for Visually Grounded Reasoning in Complex Chart Question Answering | 提出 ChartAgent，在图表空间域内直接进行视觉推理与工具交互 | 解决多模态 LLM 在未标注图表上依赖文本捷径导致性能下降问题 | 复杂图表问答与视觉推理 |
| 5 | http://arxiv.org/abs/2510.04607v1 | A Case for Declarative LLM-friendly Interfaces for Improved Efficiency of Computer-Use Agents | 提出 GOI 抽象，将 GUI 转换为声明式原语，分离策略与机制 | 解决计算机使用代理在 GUI 上分解目标序列长、错误率高及调用多问题 | 计算机任务自动化代理 |
| 6 | http://arxiv.org/abs/2510.07217v1 | GenPilot: A Multi-Agent System for Test-Time Prompt Optimization in Image Generation | 集成误差分析、自适应探索与记忆模块的即插即用多代理系统 | 解决长复杂提示词语义不一致及现有优化方法可靠性低问题 | 文本生成图像 |
| 7 | http://arxiv.org/abs/2510.08640v2 | Automating Android Build Repair: Bridging the Reasoning-Execution Gap in LLM Agents with Domain-Specific Tools | 提出 GradleFixer 代理，利用领域特定工具桥接推理与执行 gap | 解决 LLM 代理使用通用 shell 难以有效修复 Android 构建错误问题 | Android 构建修复 |
| 8 | http://arxiv.org/abs/2510.08567v3 | MATRIX: Multimodal Agent Tuning for Robust Tool-Use Reasoning | 视觉中心代理调优框架，自动合成多模态轨迹及偏好对 | 解决高质量多模态轨迹稀缺及手动标注成本高的问题 | 多模态工具使用 |
| 9 | http://arxiv.org/abs/2510.10666v2 | BrowserAgent: Building Web Agents with Human-Inspired Web Browsing Actions | 模拟人类浏览行为，直接操作原始网页 | 解决依赖静态文本转换导致的交互局限性 | 自动化 Web 任务代理 |
| 10 | http://arxiv.org/abs/2510.11221v1 | WebRouter: Query-specific Router via Variational Information Bottleneck for Cost-sensitive Web Agent | 信息论视角训练查询特定路由器降低操作成本 | 解决 Web 代理复杂提示导致成本性能权衡难问题 | 成本敏感 Web 代理 |
| 11 | http://arxiv.org/abs/2510.15455v1 | CORE: Reducing UI Exposure in Mobile Agents via Collaboration Between Cloud and Local LLMs | 云-本地LLM协作框架，布局感知分块与协同决策 | 移动Agent中云LLM需上传完整UI状态导致隐私暴露 | 移动端智能Agent |
| 12 | http://arxiv.org/abs/2510.16252v1 | WEBSERV: A Browser-Server Environment for Efficient Training of Reinforcement Learning-based Web Agents at Scale | 紧凑浏览器环境与可扩展RL环境，高效启动重置Web服务器 | 缺少可扩展环境耦合真实浏览器交互与可控服务器状态 | 基于RL的Web Agent训练 |
| 13 | http://arxiv.org/abs/2510.14278v1 | PRISM: Agentic Retrieval with LLMs for Multi-Hop Question Answering | 引入三智能体检索系统，通过迭代交互获取高精度高召回证据 | 解决多跳问答中检索内容冗余和 distracting content 过滤问题 | 多跳问答系统 |
| 14 | http://arxiv.org/abs/2510.14453v1 | Natural Language Tools: A Natural Language Approach to Tool Calling In Large Language Agents | 提出自然语言工具框架，用自然语言输出替代程序化 JSON 工具调用 | 解决工具调用中任务干扰、格式约束和开放权重模型性能差问题 | 大语言智能体 |
| 15 | http://arxiv.org/abs/2510.14808v1 | Agentic NL2SQL to Reduce Computational Costs | 引入 Datalake Agent，通过交互循环选择性请求元信息以减少 token | 解决 NL2SQL 中处理大量元信息导致 prompt 长和 processing 成本高 | NL2SQL 任务 |
| 16 | http://arxiv.org/abs/2510.15259v2 | Experience-Driven Exploration for Efficient API-Free AI Agents | 提出 KG-Agent 框架，将 pixel 交互结构化为 SA-KG 以支持 long-horizon 推理 | 解决 API-free 设置下 LLM 智能体探索效率低和依赖 trial-and-error | GUI 决策环境 |
| 17 | http://arxiv.org/abs/2510.20036v1 | ToolScope: Enhancing LLM Agent Tool Use through Tool Merging and Context-Aware Filtering | 工具合并自动纠错+上下文感知过滤检索 | 工具冗余导致选择准确性下降及上下文限制 | LLM智能体工具选择场景 |
| 18 | http://arxiv.org/abs/2511.01884v2 | CudaForge: An Agent Framework with Hardware Feedback for CUDA Kernel Optimization | 双Agent迭代+硬件反馈Nsight指标集成 | 手动CUDA内核设计成本高且效率低 | GPU内核优化 |
| 19 | http://arxiv.org/abs/2510.21045v2 | From Questions to Queries: An AI-powered Multi-Agent Framework for Spatial Text-to-SQL | 五Agent协作管道+自验证审查Agent | 空间SQL查询语义和句法复杂性高 | 地理空间数据分析 |
| 20 | http://arxiv.org/abs/2510.23642v1 | VisCoder2: Building Multi-Language Visualization Coding Agents | 679K多语言数据集+多轮自调试基准 | 可视化代码Agent语言覆盖有限且执行不可靠 | 多语言可视化代码生成 |
| 21 | http://arxiv.org/abs/2510.17925v1 | SpecAgent: A Speculative Retrieval and Forecasting Agent for Code Completion | 索引时异步构建推测上下文， anticipates 未来编辑，掩蔽延迟。 | 解决代码完成中检索质量与推理延迟预算之间的权衡及未来上下文泄露问题。 | 代码完成智能体 |
| 22 | http://arxiv.org/abs/2510.22898v1 | On Generalization in Agentic Tool Calling: CoreThink Agentic Reasoner and MAVEN Dataset | CoreThink框架增强符号推理层，MAVEN OOD基准 | 工具调用环境间泛化能力差 | 多步推理工具使用场景 |
| 23 | http://arxiv.org/abs/2510.22907v1 | Language Server CLI Empowers Language Agents with Process Rewards | Lanser-CLI提供语言服务器过程奖励，确定性工作流 | LLM幻觉API、编辑定位错误 | 编码Agent与CI流程 |
| 24 | http://arxiv.org/abs/2510.18491v1 | Crucible: Quantifying the Potential of Control Algorithms through LLM Agents | 利用 LLM 智能体模拟专家调优，量化算法调优潜力 | 现有研究忽略算法参数调优潜力的评估 | 控制算法优化与评估 |
| 25 | http://arxiv.org/abs/2510.19286v2 | TheMCPCompany: Creating General-purpose Agents with Task-specific Tools | 基于 MCP 协议构建工具调用基准，评估智能体在真实服务交互能力 | 解决通用智能体依赖浏览器且难以导航复杂工具环境的问题 | 企业级工具调用智能体 |
| 26 | http://arxiv.org/abs/2510.23853v2 | Your LLM Agents are Temporally Blind: The Misalignment Between Tool Use Decisions and Human Time Perception | 揭示智能体“时间盲”缺陷，提出后训练对齐技术以匹配人类时间感知。 | 解决动态环境中工具调用决策与时间流逝不匹配问题。 | 多轮对话与动态环境交互 |
| 27 | http://arxiv.org/abs/2510.24014v2 | TEXT2DB: Integration-Aware Information Extraction with Large Language Model Agents | 强调 IE 输出与目标数据库集成，动态适应 DB 模式进行提取。 | 解决 IE 本体与下游应用需求不匹配问题。 | 信息提取与数据库更新 |
| 28 | http://arxiv.org/abs/2510.24284v2 | MCP-Flow: Facilitating LLM Agents to Master Real-World, Diverse and Scaling MCP Tools | 自动化 Web 代理驱动流水线，大规模发现服务器与合成数据训练。 | 解决 MCP 工具生态利用受限与缺乏训练支持问题。 | 现实世界 MCP 工具环境 |
| 29 | http://arxiv.org/abs/2510.27363v1 | ToolScope: An Agentic Framework for Vision-Guided and Long-Horizon Tool Use | 全局导航器+Agent执行器+响应合成器，专用Perceive工具 | 多模态LLM灵活高效使用外部工具困难 | 长程VQA任务 |
| 30 | http://arxiv.org/abs/2511.00171v2 | CompAgent: An Agentic Framework for Visual Compliance Verification | 规划Agent动态选择视觉工具，合规验证Agent多模态推理 | 现有方法依赖任务特定模型成本高泛化性有限 | 媒体/娱乐/广告视觉合规验证 |
| 31 | http://arxiv.org/abs/2511.00074v1 | ScaleCall -- Agentic Tool Calling at Scale for Fintech: Challenges, Methods, and Deployment Insights | 企业级工具检索方法评估与混合架构部署 | regulated 环境中工具集大、功能重叠难消歧 | 金融科技工具调用 |

[返回目录](#目录)

<a id="cat-14"></a>

## 低代码/无代码Agent平台

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2510.04452v2 | AgentBuilder: Exploring Scaffolds for Prototyping User Experiences of Interface Agents | 探索代理原型系统应提供的支撑，实例化 AgentBuilder 设计探针 | 解决非 AI 工程师难以参与代理体验原型设计及需求不明确的问题 | 界面代理用户体验原型设计 |
| 2 | http://arxiv.org/abs/2510.10049v1 | ALLOY: Generating Reusable Agent Workflows from User Demonstration | 通过自然演示表达过程偏好，生成可泛化可视化工作流 | 解决用户难以指定过程需求及提示不可重用问题 | 终端用户自动化 |

[返回目录](#目录)

<a id="cat-15"></a>

## 具身智能Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2510.04637v1 | Social Agent: Mastering Dyadic Nonverbal Behavior Generation via Conversational LLM Agents | 提出 Social Agent，利用 LLM 指导对话流及生成协调的非语言行为 | 解决 dyadic 对话中合成 realistic 及 contextually appropriate 非语言行为问题 | 对话代理非语言行为生成 |
| 2 | http://arxiv.org/abs/2510.08572v1 | BLAZER: Bootstrapping LLM-based Manipulation Agents with Zero-Shot Data Generation | 利用 LLM 规划器零样本生成演示数据，自举操作策略学习 | 解决机器人缺乏互联网规模演示数据及手动收集成本高 | 机器人操作任务 |
| 3 | http://arxiv.org/abs/2510.09951v3 | Emergence of Spatial Representation in an Actor-Critic Agent with Hippocampus-Inspired Sequence Generator | 海马体启发序列生成器结合 Actor-Critic，解决稀疏输入导航 | 解决稀疏感官证据下长视野规划与空间表示问题 | 视觉导航 |
| 4 | http://arxiv.org/abs/2510.10325v1 | KG-MAS: Knowledge Graph-Enhanced Multi-Agent Infrastructure for coupling physical and digital robotic environments | 知识图谱作为共享世界模型，协调物理与数字机器人环境 | 解决工业 4.0 中系统异构性与复杂性集成挑战 | 信息物理系统 |
| 5 | http://arxiv.org/abs/2510.15963v2 | ESCA: Contextualizing Embodied Agents via Scene-Graph Generation | 基于场景图 grounding 感知，减少具身智能体感知错误 | 解决 MLLM 无法可靠捕捉视觉特征与文本语义细粒度链接问题 | 具身智能体感知 |
| 6 | http://arxiv.org/abs/2510.16410v3 | REALM: An MLLM-Agent Framework for Open World 3D Reasoning Segmentation and Editing on Gaussian Splatting | 全局到局部空间定位策略，多全局视图粗定位后合成近距离视图细分割 | 3D分割方法难以解释模糊推理指令，2D模型缺乏3D空间理解 | 3D对象定位与编辑 |
| 7 | http://arxiv.org/abs/2510.16774v1 | Learning to play: A Multimodal Agent for 3D Game-Play | 从人类游戏数据集学习逆动力学模型，行为克隆训练文本条件Agent | 3D第一人称游戏是实时多模态推理挑战性环境 | 3D游戏Agent |
| 8 | http://arxiv.org/abs/2510.11660v2 | ManiAgent: An Agentic Framework for General Robotic Manipulation | 通用操作任务的代理架构，通过代理间通信实现端到端输出。 | VLA 模型在复杂推理和长程任务规划中性能受限。 | 机器人通用操作任务 |
| 9 | http://arxiv.org/abs/2510.12693v1 | ERA: Transforming VLMs into Embodied Agents via Embodied Prior Learning and Online Reinforcement Learning | 两阶段框架整合先验知识学习和在线 RL。 | 小型 VLM 缺乏在具身 AI 中成功所需的知识和技能。 | 具身 AI 代理 |
| 10 | http://arxiv.org/abs/2510.14388v2 | Hi-Agent: Hierarchical Vision-Language Agents for Mobile Device Control | 提出分层视觉语言智能体，联合优化高层推理和底层动作模型 | 解决移动设备控制中直接状态 - 动作映射泛化差和缺乏规划问题 | 移动设备控制 |
| 11 | http://arxiv.org/abs/2510.14677v1 | When Planners Meet Reality: How Learned, Reactive Traffic Agents Shift nuPlan Benchmarks | 集成 learned traffic agent 模型到 nuPlan，评估 planner 在真实条件下表现 | 解决 rule-based 交通智能体行为 simplistic 隐藏 planner 缺陷问题 | 自动驾驶规划 |
| 12 | http://arxiv.org/abs/2510.14902v1 | VLA^2: Empowering Vision-Language-Action Models with an Agentic Framework for Unseen Concept Manipulation | 提出 VLA^2 框架，利用外部模块提供视觉文本知识处理 unseen 概念 | 解决 VLA 模型面对训练数据外物体概念时成功率显著下降问题 | 机器人操作 |
| 13 | http://arxiv.org/abs/2510.21902v1 | Software Engineering Agents for Embodied Controller Generation : A Study in Minigrid Environments | SWE-Agent具身任务控制器生成首次评估 | SWE-Agent在具身任务上表现未探索 | Minigrid具身环境 |
| 14 | http://arxiv.org/abs/2510.17129v1 | Semantic Intelligence: A Bio-Inspired Cognitive Framework for Embodied Agents | 集成分层语义认知架构与语义驱动决策过程的 SIDE 框架。 | 解决具身智能体在非结构化现实环境中缺乏语义智能理解复杂任务的问题。 | 具身智能机器人 |
| 15 | http://arxiv.org/abs/2510.17450v1 | Active Inference for an Intelligent Agent in Autonomous Reconnaissance Missions | 基于主动推断的路径规划，构建证据地图平衡探索与利用。 | 解决自主侦察任务中智能体在地理区域维持共同作战图景的挑战。 | 自主侦察任务 |
| 16 | http://arxiv.org/abs/2510.22235v1 | CGoT: A Novel Inference Mechanism for Embodied Multi-Agent Systems Using Composable Graphs of Thoughts | 提出CGoT推理机制，支持Agent承载Agent的协作 | 车辆-机器人系统协作效率低 | 自动驾驶车与服务机器人协作 |
| 17 | http://arxiv.org/abs/2510.18608v1 | A Compositional Paradigm for Foundation Models: Towards Smarter Robotic Agents | 应用持续学习与组合性原则，提升基础模型在动态场景适应性 | 解决基础模型难以适应动态现实场景无需重训的问题 | 机器人控制与适应 |
| 18 | http://arxiv.org/abs/2510.19732v2 | Memo: Training Memory-Efficient Embodied Agents with Reinforcement Learning | 穿插总结 token 训练 transformer，实现高效记忆创建与检索 | 解决 embodied 任务中视觉输入 overwhelm 上下文限制的问题 | 长周期具身决策任务 |
| 19 | http://arxiv.org/abs/2510.23691v1 | Game-TARS: Pretrained Foundation Models for Scalable Generalist Multimodal Game Agents | 提出统一可扩展动作空间，锚定人类键盘鼠标输入，支持大规模连续预训练。 | 解决游戏智能体跨域泛化与因果混淆问题。 | 开放世界游戏与多模态交互 |
| 20 | http://arxiv.org/abs/2510.24109v1 | PFEA: An LLM-based High-Level Natural Language Planning and Feedback Embodied Agent for Human-Centered AI | 包含视觉任务规划与自然语言指令转换，实现物理世界机器人操作。 | 解决现有具身智能体在线规划执行复杂自然语言任务能力不足。 | 人机中心 AI 与机器人操作 |
| 21 | http://arxiv.org/abs/2510.24259v1 | Can LLMs Translate Human Instructions into a Reinforcement Learning Agent's Internal Emergent Symbolic Representation? | 评估 LLM 将自然语言指令翻译为分层强化学习内部符号表示的能力。 | 解决语言与内部智能体表示对齐的鲁棒性问题。 | 发展性学习智能体与规划 |
| 22 | http://arxiv.org/abs/2510.27383v1 | Realistic pedestrian-driver interaction modelling using multi-agent RL with human perceptual-motor constraints | 整合行人和驾驶员Agent视觉与运动约束的多Agent RL框架 | 现有模型缺乏感知和运动约束机制 | 无信号行人过街交互 |
| 23 | http://arxiv.org/abs/2510.27420v2 | Towards a Multi-Embodied Grasping Agent | 数据高效流基等变抓取合成架构，仅从抓取器和场景几何推导信息 | 现有方法隐式学习机器人运动学结构，大规模数据难获取 | 多具身抓取（人手机械手到平行夹爪） |

[返回目录](#目录)
