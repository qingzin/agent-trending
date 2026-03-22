# AI agents 2025年2月学术分类汇总

共收录 431 篇论文，按研究方向分类整理如下。

## 目录

- [Agent安全与对齐（43篇）](#cat-01)
- [多Agent强化学习（54篇）](#cat-02)
- [Agent架构与框架设计（46篇）](#cat-03)
- [基于Agent的应用系统（77篇）](#cat-04)
- [Agent可解释性与透明度（3篇）](#cat-05)
- [Agent评测与基准（28篇）](#cat-06)
- [具身智能Agent（9篇）](#cat-07)
- [人机协作Agent（28篇）](#cat-08)
- [Agent仿真与社会模拟（28篇）](#cat-09)
- [Agent学习与自进化（33篇）](#cat-10)
- [Agent记忆与知识管理（13篇）](#cat-11)
- [Agent规划与推理（20篇）](#cat-12)
- [多Agent协作与通信（37篇）](#cat-13)
- [Agent工具使用与环境交互（10篇）](#cat-14)
- [低代码/无代码Agent平台（2篇）](#cat-15)

<a id="cat-01"></a>

## Agent安全与对齐

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2502.00289v3 | Agentic AI: Autonomy, Accountability, and the Algorithmic Society | 探讨代理 AI 的自主性与问责制，提出算法社会概念。 | 解决 AI 自主性带来的法律与伦理责任归属模糊问题。 | 社会法律框架、AI 治理 |
| 2 | http://arxiv.org/abs/2502.00406v2 | Agents Are All You Need for LLM Unlearning | 提出多智能体无需重训练的推理时遗忘框架 ALU。 | 解决 LLM 遗忘过程中效用与计算可行性难以平衡问题。 | AI 监管、隐私合规、模型安全 |
| 3 | http://arxiv.org/abs/2502.05206v5 | Safety at Scale: A Comprehensive Survey of Large Model and Agent Safety | 系统综述大模型与智能体安全威胁及防御策略。 | 解决大模型部署中缺乏全面安全评估与防御机制问题。 | 大模型与智能体安全研究 |
| 4 | http://arxiv.org/abs/2502.00757v4 | AgentBreeder: Mitigating the AI Safety Risks of Multi-Agent Scaffolds via Self-Improvement | 通过多目标自我改进进化搜索优化智能体支架安全性。 | 解决多智能体支架优化中伴随的安全风险上升问题。 | 多智能体系统安全加固 |
| 5 | http://arxiv.org/abs/2502.01236v1 | Eliciting Language Model Behaviors with Investigator Agents | 训练调查员智能体映射目标行为到多样化提示以诱导行为。 | 解决大模型行为空间巨大难以characterize 及发现有害行为问题。 | 模型红队测试、安全评估 |
| 6 | http://arxiv.org/abs/2502.01714v1 | Position: Towards a Responsible LLM-empowered Multi-Agent Systems | 倡导以人为本设计及主动动态监管以确保多智能体系统负责。 | 解决 LLM 智能体输出不确定性累积威胁系统稳定性问题。 | 负责任 AI、多智能体治理 |
| 7 | http://arxiv.org/abs/2502.01822v6 | Firewalls to Secure Dynamic LLM Agentic Networks | 提出双防火墙架构投影任务上下文，防止隐私与安全攻击。 | 解决智能体间通信中用户数据泄露及外部操纵风险问题。 | 智能体网络安全、隐私保护 |
| 8 | http://arxiv.org/abs/2502.10420v1 | Position: Stop Acting Like Language Model Agents Are Normal Agents | 论证 LMA 不应被视为正常智能体，需测量其本体属性。 | 解决将 LMA 视为正常智能体导致效用与可信度受损问题。 | AI 本体论、智能体设计理论 |
| 9 | http://arxiv.org/abs/2502.02649v3 | Fully Autonomous AI Agents Should Not be Developed | 论证完全自主 AI 代理不应开发，分析自主性与伦理风险权衡。 | 解决 AI 自主性增加导致的人类安全风险及责任归属问题。 | AI 伦理治理、政策制定 |
| 10 | http://arxiv.org/abs/2502.04249v1 | Free Energy Risk Metrics for Systemically Safe AI: Gatekeeping Multi-Agent Study | 基于自由能原理提出累积风险暴露指标，在线评估多智能体风险。 | 解决复杂世界模型下 AI 风险度量困难及安全治理缺乏透明规则问题。 | AI 系统安全、自动驾驶 |
| 11 | http://arxiv.org/abs/2502.04281v1 | DECAF: Learning to be Fair in Multi-agent Resource Allocation | 学习公平高效策略，在线权衡多智能体资源分配中效用与公平。 | 解决资源约束下多智能体系统长期公平性及效用平衡问题。 | 资源分配、多智能体公平性 |
| 12 | http://arxiv.org/abs/2503.04750v2 | AI Agents Should be Regulated Based on the Extent of Their Autonomous Operations | 主张基于自主操作程度监管 AI 代理，而非仅计算规模。 | 解决现有监管指标无法评估推理时计算及长程规划风险问题。 | AI 监管政策、风险评估 |
| 13 | http://arxiv.org/abs/2502.07807v1 | CP-Guard+: A New Paradigm for Malicious Agent Detection and Defense in Collaborative Perception | 提出特征级恶意智能体检测新范式及双中心对比损失防御。 | 解决协作感知系统中恶意信息注入导致的安全风险问题。 | 自动驾驶、协作感知系统 |
| 14 | http://arxiv.org/abs/2502.05174v4 | MELON: Provable Defense Against Indirect Prompt Injection Attacks in AI Agents | 提出掩码重执行与工具比较方法检测间接提示注入攻击。 | 解决 AI 智能体易受工具检索信息中恶意任务重定向问题。 | AI 智能体安全、提示注入防御 |
| 15 | http://arxiv.org/abs/2502.05442v3 | The Odyssey of the Fittest: Can Agents Survive and Still Be Good? | 引入轻量级文本冒险游戏框架，探索 AI 伦理及安全权衡。 | 解决复杂环境中智能体生存需求与伦理行为一致性冲突问题。 | AI 伦理研究、智能体安全 |
| 16 | http://arxiv.org/abs/2502.05986v2 | Preventing Rogue Agents Improves Multi-Agent Collaboration | 提出监控智能体行动预测并在未来错误可能时干预的方法。 | 解决多智能体协作中单个智能体错误导致系统整体失败问题。 | 多智能体协作、系统鲁棒性 |
| 17 | http://arxiv.org/abs/2502.07254v2 | Fairness in Agentic AI: A Unified Framework for Ethical and Equitable Multi-Agent System | 提出统一框架，将公平性视为多智能体系统动态 emergent 属性。 | 解决去中心化多智能体系统中 emergent 偏见及激励冲突问题。 | 多智能体伦理、公平性框架 |
| 18 | http://arxiv.org/abs/2502.11127v1 | G-Safeguard: A Topology-Guided Security Lens and Treatment on LLM-based Multi-agent Systems | G-Safeguard利用图神经网络检测多智能体话语图异常并拓扑干预 | LLM多智能体系统面临对抗攻击、错误信息传播与意外行为风险 | 关键应用中LLM多智能体系统的鲁棒性保障 |
| 19 | http://arxiv.org/abs/2502.11355v3 | Nuclear Deployed: Analyzing Catastrophic Risks in Decision-making of Autonomous LLM Agents | 三阶段评估框架自然暴露LLM智能体在高风险场景中的灾难性行为与欺骗 | 自主智能体在化学生物放射核领域潜在的灾难性决策风险 | 高利益相关者场景中LLM智能体的安全性评估与缓解 |
| 20 | http://arxiv.org/abs/2502.11448v2 | AGrail: A Lifelong Agent Guardrail with Effective and Adaptive Safety Detection | AGrail提供自适应安全检查生成、优化与工具兼容的终身智能体护栏 | 现有防御机制难以自适应有效缓解智能体的任务特定与系统风险 | 动态环境中部署的自主LLM智能体安全保障 |
| 21 | http://arxiv.org/abs/2502.08586v1 | Commercial LLM Agents Are Already Vulnerable to Simple Yet Dangerous Attacks | 分析商业 LLM 智能体管道独特漏洞，演示简单攻击及影响。 | 解决智能体管道组件引入额外安全风险及缺乏防御研究问题。 | 智能体安全、攻击防御 |
| 22 | http://arxiv.org/abs/2502.08966v2 | RTBAS: Defending LLM Agents Against Prompt Injection and Privacy Leakage | 自适应检测执行工具调用，仅需无法保障安全时用户确认。 | 解决工具智能体提示注入攻击及用户确认负担过重问题。 | 智能体安全、隐私保护 |
| 23 | http://arxiv.org/abs/2502.09809v1 | AgentGuard: Repurposing Agentic Orchestrator for Safety Evaluation of Tool Orchestration | 利用编排器自主发现验证不安全工具工作流及生成安全约束。 | 解决智能体工具使用恶意工作流风险及缺乏标准化测试问题。 | 智能体安全、工具编排 |
| 24 | http://arxiv.org/abs/2502.13172v2 | Unveiling Privacy Risks in LLM Agent Memory | 提出记忆提取攻击 (MEXTRA)，系统调查 Agent 记忆隐私漏洞 | 解决 Agent 记忆模块存储私有交互数据导致的泄露风险 | LLM Agent 记忆安全 |
| 25 | http://arxiv.org/abs/2502.12575v2 | DemonAgent: Dynamically Encrypted Multi-Backdoor Implantation Attack on LLM-based Agent | 提出动态加密多后门植入攻击，绕过安全审计检测 | 解决现有安全机制难以检测高级后门攻击的问题 | LLM Agent 后门攻击与防御 |
| 26 | http://arxiv.org/abs/2502.12630v1 | Automating Prompt Leakage Attacks on Large Language Models Using Agentic Approach | 利用 Agent 团队自动化探测提示词泄露，定义安全标准 | 解决系统级提示词或专有配置暴露的安全威胁 | LLM 提示词泄露安全测试 |
| 27 | http://arxiv.org/abs/2502.13053v3 | Evaluating the Robustness of Multimodal Agents Against Active Environmental Injection Attacks | 定义主动环境注入攻击，评估多模态 Agent 鲁棒性 | 解决攻击者伪装恶意攻击为环境元素操纵决策问题 | 多模态 Agent 安全鲁棒性 |
| 28 | http://arxiv.org/abs/2502.14143v1 | Multi-Agent Risks from Advanced AI | 分类多 Agent 系统风险（失调、冲突、共谋）及关键风险因素 | 解决高级 AI 多 Agent 系统带来的新颖未探索风险问题 | 高级 AI 安全与治理 |
| 29 | http://arxiv.org/abs/2502.18805v3 | It's Not All Black and White: Degree of Truthfulness for Risk-Avoiding Agents | 提出风险避免真实性 (RAT) 程度概念，插值经典真实性与风险避免真实性 | 解决代理在不完全信息下的操纵风险与真实性机制设计问题 | 社会选择机制中的智能体（拍卖、投票等） |
| 30 | http://arxiv.org/abs/2502.19145v2 | Multi-Agent Security Tax: Trading Off Security and Collaboration Capabilities in Multi-Agent Systems | 模拟攻击者妥协智能体场景，评估防御策略及安全与协作能力的权衡 | 研究自主多智能体系统的安全性风险及安全与协作效率的权衡 | 协作多智能体系统的安全防御 |
| 31 | http://arxiv.org/abs/2503.00061v2 | Adaptive Attacks Break Defenses Against Indirect Prompt Injection Attacks on LLM Agents | 评估 8 种防御并用自适应攻击全部 bypass，揭示当前防御关键漏洞 | 解决 LLM 智能体集成外部工具引入的间接提示注入攻击风险 | LLM 智能体安全防御 |
| 32 | http://arxiv.org/abs/2502.20383v3 | Why Are Web AI Agents More Vulnerable Than Standalone LLMs? A Security Analysis | 组件级分析识别放大 Web 智能体脆弱性的三个关键因素 | 调查 Web 智能体比独立 LLM 更脆弱的根本因素及安全差异 | Web AI 智能体安全分析 |
| 33 | http://arxiv.org/abs/2502.20757v1 | The Rise of Darkness: Safety-Utility Trade-Offs in Role-Playing Dialogue Agents | 提出自适应动态多偏好方法，根据风险耦合度动态调整安全效用偏好 | 解决角色扮演对话智能体中角色效用与内容安全平衡挑战 | 角色扮演对话智能体 |
| 34 | http://arxiv.org/abs/2503.01908v3 | UDora: A Unified Red Teaming Framework against LLM Agents by Dynamically Hijacking Their Own Reasoning | 统一红队框架，动态劫持智能体推理过程迫使恶意行为 | 解决操纵 LLM 智能体执行 targeted 恶意动作或调用特定工具的挑战 | LLM 智能体红队测试 |
| 35 | http://arxiv.org/abs/2502.16750v4 | Guardians of the Agentic System: Preventing Many Shots Jailbreak with Agentic System | 开发多智能体模拟检测框架，实现主动监控与自适应干预 | 多轮越狱攻击和欺骗性对齐难以被静态防护抵御 | LLM智能体系统安全防护 |
| 36 | http://arxiv.org/abs/2502.18534v2 | MAFE: Enabling Equitable Algorithm Design in Multi-Agent Multi-Stage Decision-Making Systems | 设计多智能体公平环境套件模拟真实动态系统 | 静态公平方法无法缓解多阶段累积差异 | 贷款、医疗、教育公平决策 |
| 37 | http://arxiv.org/abs/2502.18359v1 | Responsible AI Agents | 提出软件交互约束与价值对齐方法规范AI智能体 | AI智能体可能引发非法商业、操纵等风险 | AI智能体法律与责任规范 |
| 38 | http://arxiv.org/abs/2502.14529v1 | CORBA: Contagious Recursive Blocking Attacks on Multi-Agent Systems Based on Large Language Models | 传染性递归阻塞攻击(Corba)，利用传染性与递归性消耗计算资源 | LLM多Agent系统安全机制未充分探索，易受针对性干扰 | AutoGen、Camel等LLM多Agent系统 |
| 39 | http://arxiv.org/abs/2502.14847v2 | Red-Teaming LLM Multi-Agent Systems via Communication Attacks | Agent-in-the-Middle(AiTM)攻击，拦截操纵Agent间消息 | LLM多Agent系统通信框架存在未探索安全漏洞 | 各类LLM多Agent协作框架 |
| 40 | http://arxiv.org/abs/2502.15865v2 | Standard Benchmarks Fail -- Auditing LLM Agents in Finance Must Prioritize Risk | 主张金融LLM Agent评估应优先风险档案而非准确率指标 | 标准基准忽略幻觉、数据过时、对抗提示等安全风险 | 金融领域LLM Agent部署 |
| 41 | http://arxiv.org/abs/2502.15657v2 | Superintelligent Agents Pose Catastrophic Risks: Can Scientist AI Offer a Safer Path? | 提出非Agent式Scientist AI，含世界模型与问答推理机，显式不确定性 | 通用Agent unchecked自主性带来公共安全风险及失控可能 | AI安全与科学发展 |
| 42 | http://arxiv.org/abs/2502.18509v2 | Protecting Users From Themselves: Safeguarding Contextual Privacy in Interactions with Conversational Agents | 本地部署框架识别并重写用户提示中的上下文外信息 | 用户与LLM对话Agent交互中低估隐私风险，无意泄露敏感信息 | LLM对话Agent用户隐私保护 |
| 43 | http://arxiv.org/abs/2502.18515v2 | Securing Smart Contract Languages with a Unified Agentic Framework for Vulnerability Repair in Solidity and Move | Smartify框架，多Agent团队分析代码概念与语言特定安全原则 | Solidity与Move智能合约语言仍存在安全漏洞需自动检测修复 | 区块链智能合约安全 |

[返回目录](#目录)

<a id="cat-02"></a>

## 多Agent强化学习

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2502.00345v1 | The Composite Task Challenge for Cooperative Multi-Agent Reinforcement Learning | 提出复合任务挑战基准，强制要求多智能体分工合作。 | 解决现有 MARL 测试任务中分工合作非必需的问题。 | 多智能体强化学习算法评估 |
| 2 | http://arxiv.org/abs/2502.00558v2 | Asynchronous Cooperative Multi-Agent Reinforcement Learning with Limited Communication | 提出 AsynCoMARL，利用图变压器学习异步通信协议。 | 解决通信受限环境下多智能体同步协作性能下降问题。 | 未知环境下的多机器人协作 |
| 3 | http://arxiv.org/abs/2502.00955v1 | Efficient Multi-Agent System Training with Data Influence-Oriented Tree Search | 提出 DITS 框架，利用影响分数引导树搜索与数据选择。 | 解决仅靠 Q 值选择合成数据与模型训练目标不一致问题。 | 多智能体系统自训练优化 |
| 4 | http://arxiv.org/abs/2502.01041v1 | Multi-Object Active Search and Tracking by Multiple Agents in Untrusted, Dynamically Changing Environments | 集成时变信念表示与 LSTM 轨迹预测的多智能体搜索跟踪。 | 解决动态不可信环境下多目标搜索跟踪及信息融合问题。 | 机器人搜索救援、海洋监测 |
| 5 | http://arxiv.org/abs/2502.01971v1 | Bottom-Up Reputation Promotes Cooperation with Multi-Agent Reinforcement Learning | 提出 LR2 方法，通过自下而上声誉学习促进多智能体合作。 | 解决多智能体在无预定义规范下如何达成声誉共识问题。 | 社会困境、多智能体合作 |
| 6 | http://arxiv.org/abs/2502.02071v1 | Sequential Multi-objective Multi-agent Reinforcement Learning Approach for Predictive Maintenance | 提出 SMOMA-PPO 算法处理预测性维护中 sequential 多目标。 | 解决传统 MARL 无法处理维护中顺序约束多目标优化问题。 | 工业预测性维护、系统可靠性 |
| 7 | http://arxiv.org/abs/2502.02785v2 | OpenSTARLab: Open Approach for Spatio-Temporal Agent Data Analysis in Soccer | 开源框架标准化足球时空数据，支持事件预测与 RL 任务。 | 解决体育分析中跟踪数据稀缺及多源数据整合困难问题。 | 体育数据分析、足球战术分析 |
| 8 | http://arxiv.org/abs/2502.02844v3 | Wolfpack Adversarial Attack for Robust Multi-Agent Reinforcement Learning | 提出狼群对抗攻击框架及防御学习策略，增强 MARL 鲁棒性。 | 解决协作 MARL 在面对协调对抗攻击时脆弱及合作易 disrupted 问题。 | 多智能体系统安全、鲁棒控制 |
| 9 | http://arxiv.org/abs/2502.02875v1 | Heterogeneous Value Decomposition Policy Fusion for Multi-Agent Cooperation | 提出异构策略融合机制，自适应选择价值分解策略。 | 解决单一价值分解方法表示受限及优化困难问题。 | 协作多智能体任务、策略优化 |
| 10 | http://arxiv.org/abs/2502.03506v1 | Optimistic Îµ-Greedy Exploration for Cooperative Multi-Agent Reinforcement Learning | 引入乐观更新网络识别最优动作，增强探索纠正价值估计。 | 解决单调价值分解方法低估最优动作导致策略次优问题。 | 协作多智能体强化学习、探索策略 |
| 11 | http://arxiv.org/abs/2502.03125v1 | Double Distillation Network for Multi-Agent Reinforcement Learning | 双蒸馏网络弥合全局训练与局部执行差距，增强鲁棒协作。 | 解决部分可观测执行下累积误差损害协作策略训练问题。 | 多智能体协作、分布式执行 |
| 12 | http://arxiv.org/abs/2502.03377v4 | Energy-Efficient UAV-assisted LoRa Gateways: A Multi-Agent Optimization Approach | 两阶段方案结合匹配算法与 MAPPO 优化 UAV 辅助 LoRa 能效。 | 解决 NG-IoT 网络中设备能耗高及资源管理复杂问题。 | 物联网通信、无人机网络 |
| 13 | http://arxiv.org/abs/2502.03640v3 | Discrete GCBF Proximal Policy Optimization for Multi-agent Safe Optimal Control | 学习离散图 CBF 及安全策略，处理未知动力学及输入约束。 | 解决多智能体系统在未知动态下安全控制策略设计困难问题。 | 多智能体安全控制、机器人 |
| 14 | http://arxiv.org/abs/2502.03723v2 | Speaking the Language of Teamwork: LLM-Guided Credit Assignment in Multi-Agent Reinforcement Learning | LLM 生成密集代理特定奖励，优化稀疏奖励下信用分配。 | 解决 MARL 稀疏奖励下信用分配困难及奖励函数设计复杂问题。 | 多智能体强化学习、信用分配 |
| 15 | http://arxiv.org/abs/2502.04028v3 | Deep Meta Coordination Graphs for Multi-agent Reinforcement Learning | 动态组合元协调图学习代理交互表示，优化协作策略。 | 解决固定协调图表示能力有限及交互推理不充分问题。 | 多智能体协作、图神经网络 |
| 16 | http://arxiv.org/abs/2502.04686v3 | Learning Strategic Language Agents in the Werewolf Game with Iterative Latent Space Policy Optimization | 迭代潜空间策略优化框架，结合博弈论与 LLM 微调学习策略。 | 解决战略语言游戏中 LLM 动作分布偏差及探索空间受限问题。 | 战略游戏、语言智能体 |
| 17 | http://arxiv.org/abs/2502.04864v2 | Redistributing Rewards Across Time and Agents for Multi-Agent Reinforcement Learning | 提出时间 - 智能体奖励重分配方法，解耦信用建模约束。 | 解决多智能体强化学习中信用分配及最优策略保持问题。 | 协作多智能体任务、奖励分配 |
| 18 | http://arxiv.org/abs/2502.05028v1 | Near-Optimal Online Learning for Multi-Agent Submodular Coordination: Tight Approximation and Communication Efficiency | 提出 MA-OSMA 算法，利用多线性扩展优化子模协调。 | 解决不可预测环境中多智能体子模协调近似保证差问题。 | 机器人规划、多智能体协调 |
| 19 | http://arxiv.org/abs/2502.05301v1 | Decentralized Online Ensembles of Gaussian Processes for Multi-Agent Systems | 提出完全去中心化高斯过程随机特征近似及集成方案。 | 解决多智能体系统中灵活可扩展的去中心化学习问题。 | 分布式多智能体系统、在线学习 |
| 20 | http://arxiv.org/abs/2502.05573v1 | Low-Rank Agent-Specific Adaptation (LoRASA) for Multi-Agent Policy Learning | 提出低秩智能体特定适配方法，平衡共享策略与个体 specialization。 | 解决多智能体强化学习中参数共享抑制个体专业化问题。 | 异构多智能体环境、策略学习 |
| 21 | http://arxiv.org/abs/2502.05812v1 | Multi-Agent Reinforcement Learning in Wireless Distributed Networks for 6G | 综述 MARL 辅助无线分布式网络，分析架构、挑战及研究方向。 | 解决 6G 网络中分布式协作机制及 MARL 实施挑战理解不足问题。 | 6G 通信网络、无线资源管理 |
| 22 | http://arxiv.org/abs/2502.06060v1 | Training Language Models for Social Deduction with Multi-Agent Reinforcement Learning | 利用 MARL 训练语言模型在社交推理游戏中进行自然语言讨论。 | 解决社交设定中语言模型缺乏自然有用沟通策略及训练数据问题。 | 社交推理游戏、语言智能体 |
| 23 | http://arxiv.org/abs/2502.06113v1 | Towards Bio-inspired Heuristically Accelerated Reinforcement Learning for Adaptive Underwater Multi-Agents Behaviour | 引入生物启发启发式加速 MARL 收敛，优化水下多智能体覆盖。 | 解决水下多智能体 MARL 算法学习时间长及难以实机部署问题。 | 水下机器人、覆盖规划 |
| 24 | http://arxiv.org/abs/2502.06261v1 | Reducing Variance Caused by Communication in Decentralized Multi-agent Deep Reinforcement Learning | 提出模块化技术减少去中心化 MARL 通信导致的策略梯度方差。 | 解决去中心化多智能体通信引入不确定性及学习方差问题。 | 去中心化多智能体系统、通信 |
| 25 | http://arxiv.org/abs/2502.06440v2 | SIGMA: Sheaf-Informed Geometric Multi-Agent Pathfinding | 应用层论到去中心化 DRL，学习几何交叉依赖实现紧密协作。 | 解决有限视野下多智能体路径规划短视及协作效率低问题。 | 多智能体路径规划、机器人物流 |
| 26 | http://arxiv.org/abs/2502.11260v2 | Scalable Multi-Agent Offline Reinforcement Learning and the Role of Information | SCAM-FQI通过信息共享网络实现可扩展的离线多智能体策略学习 | 离线MARL在数据收集可扩展性与策略性能保证间的权衡 | 分布式决策制定中的高效离线策略学习 |
| 27 | http://arxiv.org/abs/2502.11437v1 | Learning Dexterous Bimanual Catch Skills through Adversarial-Cooperative Heterogeneous-Agent Reinforcement Learning | 异质智能体RL框架中投掷与抓取智能体通过对抗奖励协同学习双手抓取 | 双手机器人抓取在协调控制与复杂物体处理上的挑战 | 具身机器人系统的灵巧双手操作技能学习 |
| 28 | http://arxiv.org/abs/2502.07635v1 | Distributed Value Decomposition Networks with Networked Agents | 提出分布式价值分解网络，无需集中训练即可估计共享目标。 | 解决部分可观测下多智能体分布式训练及通信信息丢失问题。 | 分布式多智能体强化学习 |
| 29 | http://arxiv.org/abs/2502.08003v1 | Heterogeneous Multi-agent Multi-armed Bandits on Stochastic Block Models | 提出基于随机块模型的异构多智能体_bandits_算法及遗憾界。 | 解决异构奖励及图随机性下多智能体系统遗憾最小化问题。 | 分布式学习、多智能体_bandits_ |
| 30 | http://arxiv.org/abs/2502.08681v2 | Centrally Coordinated Multi-Agent Reinforcement Learning for Power Grid Topology Control | 中心协调多智能体架构分解动作空间，优化电网拓扑控制。 | 解决电网操作动作空间组合爆炸及传统优化器挑战问题。 | 电力系统控制、电网管理 |
| 31 | http://arxiv.org/abs/2502.08365v4 | Towards Principled Unsupervised Multi-Agent Reinforcement Learning | 提出可扩展去中心化信任域策略搜索算法解决无监督 MARL。 | 解决多智能体设置下无监督预训练理论及实践困难问题。 | 多智能体强化学习、无监督学习 |
| 32 | http://arxiv.org/abs/2502.09780v1 | Incentivize without Bonus: Provably Efficient Model-based Online Multi-agent RL for Markov Games | 模型基算法通过偏差经验估计激励探索，无需额外奖励。 | 解决马尔可夫博弈中样本效率及协调玩家策略更新困难问题。 | 多智能体强化学习、博弈论 |
| 33 | http://arxiv.org/abs/2502.12605v1 | Hypernetwork-based approach for optimal composition design in partially controlled multi-agent systems | 基于超网络联合优化系统组合与 Agent 策略，减少计算开销 | 解决部分可控多 Agent 系统双层优化计算密集问题 | 出租车调度等部分可控系统 |
| 34 | http://arxiv.org/abs/2502.13376v1 | Learning Symbolic Task Decompositions for Multi-Agent Teams | 从模型免费交互中学习最优任务分解，无需人工设计 | 解决 cooperative multi-agent 学习中任务分解依赖先验知识问题 | 多 Agent 团队任务分解 |
| 35 | http://arxiv.org/abs/2502.13430v1 | Vision-Based Generic Potential Function for Policy Alignment in Multi-Agent Reinforcement Learning | 分层视觉奖励 shaping，利用 VLM 语义理解对齐人类常识 | 解决多 Agent 任务中常识建模困难及规则奖励设计耗时问题 | 多 Agent 策略对齐 |
| 36 | http://arxiv.org/abs/2502.19004v1 | A Multi-Agent DRL-Based Framework for Optimal Resource Allocation and Twin Migration in the Multi-Tier Vehicular Metaverse | 集成 GCN、Stackelberg 博弈与 MADRL，优化资源分配与 vehicular twin 迁移 | 平衡多层车辆元宇宙中的延迟、资源利用与用户体验多目标优化 | 多层车辆元宇宙中的资源分配与 twin 迁移 |
| 37 | http://arxiv.org/abs/2503.00056v1 | Stability Analysis of Deep Reinforcement Learning for Multi-Agent Inspection in a Terrestrial Testbed | 评估分层 DRL 框架稳定性，集成高层指导策略与低层运动控制器 | 解决多智能体卫星检查任务在真实环境不确定性下的稳定性与性能 | 多智能体卫星检查任务 |
| 38 | http://arxiv.org/abs/2502.19717v1 | Exponential Topology-enabled Scalable Communication in Multi-agent Reinforcement Learning | 利用指数拓扑实现可扩展通信协议，通过内存消息处理器接地信息 | 解决大规模多智能体系统中部分可观察性下的有效通信与共识问题 | 合作多智能体强化学习系统 |
| 39 | http://arxiv.org/abs/2502.20065v1 | RouteRL: Multi-agent reinforcement learning framework for urban route choice with autonomous vehicles | 集成 MARL 与微观交通仿真，测试开发自动驾驶车辆高效路线选择策略 | 促进 MARL、交通建模及人机交互在交通应用中的研究 | 城市自动驾驶车辆路线选择 |
| 40 | http://arxiv.org/abs/2502.20068v1 | A Generative Model Enhanced Multi-Agent Reinforcement Learning Method for Electric Vehicle Charging Navigation | 利用局部信息生成模型增强多智能体 DRL，压缩全局信息提升训练 | 解决 EV 充电导航中全局信息依赖导致的通信成本与隐私问题 | 电动汽车充电导航 |
| 41 | http://arxiv.org/abs/2502.20217v1 | MARVEL: Multi-Agent Reinforcement Learning for constrained field-of-View multi-robot Exploration in Large-scale environments | 利用图注意力网络与去中心化策略，处理受限视场多机器人探索 | 解决小型机器人受限传感器视场下的多机器人协作探索问题 | 大规模环境多机器人探索 |
| 42 | http://arxiv.org/abs/2502.20462v1 | Cooperative Multi-Agent Assignment over Stochastic Graphs via Constrained Reinforcement Learning | 非常规公式化使双变量自由循环，基于实时约束满足动态适应策略 | 设计动态环境中团队智能体执行冲突任务的可扩展且可行解决方案 | 随机图上合作多智能体分配 |
| 43 | http://arxiv.org/abs/2502.16608v1 | Toward Dependency Dynamics in Multi-Agent Reinforcement Learning for Traffic Signal Control | 提出DQN-DPUS策略，根据代理依赖性动态更新参数 | 集中式RL维度高、分散式RL部分可观测问题 | 城市交通信号自适应控制 |
| 44 | http://arxiv.org/abs/2502.17046v1 | MA2RL: Masked Autoencoders for Generalizable Multi-Agent Reinforcement Learning | 从实体视角重建实体状态，推断未观察实体 | 部分观测下技能语义学习困难、泛化能力差 | 多智能体强化学习任务 |
| 45 | http://arxiv.org/abs/2502.18526v1 | Reinforcement Learning-based Approach for Vehicle-to-Building Charging with Heterogeneous Agents and Long Term Rewards | 结合DDPG与动作掩码及MILP策略指导 | 电动车充电需长期奖励优化、状态动作空间大 | 车辆到建筑能源管理 |
| 46 | http://arxiv.org/abs/2502.17813v2 | Safe Multi-Agent Navigation guided by Goal-Conditioned Safe Reinforcement Learning | 整合规划与安全RL，构建剪枝不安全边的高层图 | 安全RL难以解决长视野多智能体导航任务 | 危险环境多智能体安全导航 |
| 47 | http://arxiv.org/abs/2502.14200v1 | Causal Mean Field Multi-Agent Reinforcement Learning | 提出因果平均场Q学习(CMFQ)，通过结构因果模型量化交互重要性 | 多智能体强化学习可扩展性及非平稳环境下的交互识别问题 | 混合协作竞争游戏、协作游戏环境 |
| 48 | http://arxiv.org/abs/2502.14606v1 | Curiosity Driven Multi-agent Reinforcement Learning for 3D Game Testing | 好奇心驱动多Agent强化学习(cMarlTest)，多Agent协作测试 | 单Agent游戏测试覆盖率低、效率不足的问题 | 3D游戏自动化测试 |
| 49 | http://arxiv.org/abs/2502.15240v2 | Multi-agent Multi-armed Bandits with Minimum Reward Guarantee Fairness | RewardFairUCB算法，保证公平性同时最大化社会福利 | 多Agent多臂老虎机中社会福利与公平性平衡问题 | 中心化决策者多Agent资源分配 |
| 50 | http://arxiv.org/abs/2502.15338v1 | Learning with Limited Shared Information in Multi-agent Multi-armed Bandit | LSI-MAMAB模型及Balanced-ETC算法，支持有限信息共享协作 | 现有研究未考虑Agent因隐私拒绝共享全部信息的情况 | 隐私敏感的多Agent协作学习 |
| 51 | http://arxiv.org/abs/2502.15425v4 | TAG: A Decentralized Framework for Multi-Agent Hierarchical Reinforcement Learning | TAME Agent Framework(TAG)，通过LevelEnv概念支持任意深度分层 | 当前HRL限制两层或需集中训练，实用性与可扩展性受限 | 可扩展分层多Agent系统 |
| 52 | http://arxiv.org/abs/2502.16128v1 | Heterogeneous Multi-Agent Bandits with Parsimonious Hints | HMA2B问题及GP-HCLA/HD-ETC/EBHD-ETC算法，支持低成本提示查询 | 异构多Agent老虎机中最大化效用同时最小化提示查询问题 | 中心化与去中心化多Agent决策 |
| 53 | http://arxiv.org/abs/2502.16449v1 | Facilitating Emergency Vehicle Passage in Congested Urban Areas Using Multi-agent Deep Reinforcement Learning | EMVLight去中心化框架集成应急车辆路由与交通信号优先 | 城市拥堵区域应急车辆通行时间延迟严重影响救援效率 | 城市交通应急管理 |
| 54 | http://arxiv.org/abs/2502.16496v1 | PMAT: Optimizing Action Generation Order in Multi-Agent Reinforcement Learning | AGPS机制建模顺序为Plackett-Luce采样，优先多Agent Transformer | 多数MARL算法忽略Agent间动作级依赖降低协调效率 | StarCraft II、足球、MuJoCo等多Agent基准 |

[返回目录](#目录)

<a id="cat-03"></a>

## Agent架构与框架设计

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2502.00350v2 | OrcaLoca: An LLM Agent Framework for Software Issue Localization | 集成优先级调度与相关性评分，提升代码定位准确率。 | 解决 LLM 智能体在软件问题定位中精度不足的问题。 | 自主软件工程、代码调试 |
| 2 | http://arxiv.org/abs/2502.00510v3 | Understanding and Optimizing Agentic Workflows via Shapley value | 引入 ShapleyFlow 框架，利用博弈论量化组件贡献。 | 解决智能体工作流组件依赖复杂及贡献归因困难问题。 | 复杂 AI 系统工作流优化 |
| 3 | http://arxiv.org/abs/2502.00674v1 | Rethinking Mixture-of-Agents: Is Mixing Different Large Language Models Beneficial? | 提出 Self-MoA，仅聚合单一顶级模型输出优于混合模型。 | 解决混合不同 LLM 导致平均质量下降及多样性权衡问题。 | 大模型集成与性能优化 |
| 4 | http://arxiv.org/abs/2502.00989v1 | ChartCitor: Multi-Agent Framework for Fine-Grained Chart Visual Attribution | 多智能体框架提供细粒度图表视觉引用与证据定位。 | 解决图表问答中响应缺乏视觉语义 grounding 及幻觉问题。 | 图表理解、生成式 AI 可信度 |
| 5 | http://arxiv.org/abs/2503.15520v1 | Agent-S: LLM Agentic workflow to automate Standard Operating Procedures | 提出 Agent-S 工作流，利用记忆与环境自动化标准操作程序。 | 解决客户服务中 SOP 执行依赖人工及流程僵化问题。 | 电商客服、标准操作自动化 |
| 6 | http://arxiv.org/abs/2502.02533v2 | Multi-Agent Design: Optimizing Agents with Better Prompts and Topologies | 提出 MASS 框架，自动化优化多智能体系统的提示与拓扑。 | 解决多智能体系统设计中提示与拓扑组合空间复杂问题。 | 多智能体系统自动化设计 |
| 7 | http://arxiv.org/abs/2502.04358v2 | Position: Scaling LLM Agents Requires Asymptotic Analysis with LLM Primitives | 提出基于 LLM 原语的渐近分析方法，优化任务分解效率。 | 解决 LLM 代理系统任务分解缺乏理论效率评估及优化依据问题。 | 大规模 LLM 代理系统架构设计 |
| 8 | http://arxiv.org/abs/2502.04388v3 | Position: Emergent Machina Sapiens Urge Rethinking Multi-Agent Paradigms | 倡导多智能体框架向 emergent、自组织及情境感知方向转变。 | 解决现有框架规则静态及目标未对齐导致系统混乱问题。 | 多智能体系统理论、基础设施安全 |
| 9 | http://arxiv.org/abs/2502.04392v1 | Division-of-Thoughts: Harnessing Hybrid Language Model Synergy for Efficient On-Device Agents | 协同推理框架利用端云模型 synergy，分解任务优化资源。 | 解决资源受限设备部署全规模 LLM 困难及推理成本高问题。 | 端侧 AI 代理、混合模型部署 |
| 10 | http://arxiv.org/abs/2502.04180v2 | Multi-agent Architecture Search via Agentic Supernet | 自动化框架从超网采样查询依赖代理系统，优化资源分配。 | 解决手动设计代理工作流静态僵化及资源分配不动态问题。 | 多代理架构搜索、自动化设计 |
| 11 | http://arxiv.org/abs/2502.04492v2 | Dynamic Optimizations of LLM Ensembles with Two-Stage Reinforcement Learning Agents | 两阶段 RL 代理动态路由及集成 LLM，优化推理性能与成本。 | 解决静态 LLM 集成无法适应动态环境及推理冲突融合困难问题。 | LLM 集成、动态推理优化 |
| 12 | http://arxiv.org/abs/2502.04747v1 | Every Software as an Agent: Blueprint and Case Study | 倡导白盒设置赋予 LLM 访问软件内部及动态注入代码权限。 | 解决现有 API/GUI 代理准确性效率低及缺乏软件上下文理解问题。 | 软件代理、人机交互范式 |
| 13 | http://arxiv.org/abs/2502.04790v2 | S$^2$-MAD: Breaking the Token Barrier to Enhance Multi-Agent Debate Efficiency | 提出稀疏化策略减少多智能体辩论中的无效信息交换。 | 解决多智能体辩论中 Token 成本过高及扩展性差问题。 | 大模型推理优化、多智能体辩论 |
| 14 | http://arxiv.org/abs/2502.07056v1 | Autonomous Deep Agent | 提出分层任务 DAG 框架及自主 API 创建系统，管理复杂多阶段任务。 | 解决传统智能体系统处理复杂多步任务依赖及执行连贯性问题。 | 复杂任务自动化、自主系统 |
| 15 | http://arxiv.org/abs/2503.16442v1 | Situational Agency: The Framework for Designing Behavior in Agent-based art | 提出情境化行为设计框架，整合环境、观众与智能体交互 | 代理艺术中行为设计与美学体验缺乏理论指导 | 人工生命艺术与基于代理的艺术创作 |
| 16 | http://arxiv.org/abs/2502.07373v1 | EvoFlow: Evolving Diverse Agentic Workflows On The Fly | 基于生态位进化算法，自动搜索异构及复杂度自适应智能体工作流。 | 解决现有自动化流程缺乏模型异构性及单目标优化局限问题。 | 自动化智能体工作流设计 |
| 17 | http://arxiv.org/abs/2502.08224v1 | Flow-of-Action: SOP Enhanced LLM-Based Multi-Agent System for Root Cause Analysis | SOP 增强多智能体框架，约束 LLM 关键步骤减少幻觉及无效行动。 | 解决微服务根因分析中 LLM 幻觉及复杂线索 overwhelms 模型问题。 | 运维自动化、根因分析 |
| 18 | http://arxiv.org/abs/2502.08556v1 | Human-Centric Foundation Models: Perception, Generation and Agentic Modeling | 提出以人为本基础模型分类法，涵盖感知、生成及智能体建模。 | 解决数字人及具身建模缺乏统一框架及任务特定方法局限问题。 | 数字人、具身智能建模 |
| 19 | http://arxiv.org/abs/2502.08820v3 | Can a Single Model Master Both Multi-turn Conversations and Tool Use? CoALM: A Unified Conversational Agentic Language Model | 统一对话及智能体能力模型， interleaved 多轮 ReAct 及 API 使用数据训练。 | 解决任务型对话及语言智能体技能割裂及单一模型难以兼顾问题。 | 对话系统、工具使用智能体 |
| 20 | http://arxiv.org/abs/2502.09215v1 | Architecture for Simulating Behavior Mode Changes in Norm-Aware Autonomous Agents | 架构模拟规范感知智能体行为模式变化，支持人类控制器更新。 | 解决政策制定者理解智能体规范合规态度及行为模拟困难问题。 | 政策模拟、规范感知智能体 |
| 21 | http://arxiv.org/abs/2502.09216v1 | Mind the Gaps: Logical English, Prolog, and Multi-agent Systems for Autonomous Vehicles | 模块化系统表示推理交通规则，集成自然语言接口及仿真环境。 | 解决自动驾驶法律规则可访问计算模型缺乏及责任转移问题。 | 自动驾驶、法律规则推理 |
| 22 | http://arxiv.org/abs/2502.09237v1 | Reliable Conversational Agents under ASP Control that Understand Natural Language | LLM 仅作解析器，基于 ASP 知识推理实现可靠对话智能体。 | 解决 LLM 缺乏理解及可靠性问题，实现可解释对话。 | 对话系统、可靠 AI |
| 23 | http://arxiv.org/abs/2502.09596v1 | KIMAs: A Configurable Knowledge Integrated Multi-Agent System | 可配置知识集成多智能体系统，优化检索准确性及多轮连贯性。 | 解决 RAG 应用处理异构数据及低延迟响应实际场景挑战问题。 | 知识密集型应用、RAG 系统 |
| 24 | http://arxiv.org/abs/2502.09903v1 | The Ann Arbor Architecture for Agent-Oriented Programming | 基于自动机理论重新审视提示工程，提出智能体导向编程架构。 | 解决传统软件工程实践与 LLM 自然语言编程分离问题。 | 智能体编程、软件工程 |
| 25 | http://arxiv.org/abs/2502.12767v7 | R2-KG: General-Purpose Dual-Agent Framework for Reliable Reasoning on Knowledge Graphs | 双 Agent 框架分离证据收集与判断，引入弃权机制增强可靠性 | 解决 KG 推理依赖单一高容量 LLM 及幻觉问题 | 知识图谱可靠推理 |
| 26 | http://arxiv.org/abs/2502.12926v1 | Towards more Contextual Agents: An extractor-Generator Optimization Framework | 自动化优化上下文特定 Agent 的提示词，提升泛化能力 | 解决手动 crafting 特定领域提示词耗时且不可扩展问题 | 特定领域上下文 Agent |
| 27 | http://arxiv.org/abs/2502.13130v1 | Magma: A Foundation Model for Multimodal AI Agents | 预训练多模态基础模型，赋予空间 temporal 智能与行动能力 | 解决现有 VL 模型缺乏视觉空间规划与行动 grounding 问题 | 多模态 UI 导航与机器人操作 |
| 28 | http://arxiv.org/abs/2502.13965v1 | Autellix: An Efficient Serving Engine for LLM Agents as General Programs | 将程序视为一等公民，基于程序上下文调度 LLM 调用 | 解决现有服务系统忽略程序依赖导致累积等待时间长问题 | LLM Agent 服务引擎 |
| 29 | http://arxiv.org/abs/2502.19091v1 | Nexus: A Lightweight and Scalable Multi-Agent Framework for Complex Tasks Automation | 轻量级 Python 框架，引入灵活多监督层级与简化工作流设计 | 解决现有 MAS 架构可扩展性差及领域适应性受限的问题 | 复杂任务自动化的多智能体系统构建 |
| 30 | http://arxiv.org/abs/2502.19298v1 | Agent-centric Information Access | 提出以智能体为中心的信息访问框架，动态排名并查询专业模型 | 解决海量专业 LLM 系统中专家选择、查询效率及响应聚合挑战 | 大规模专业 LLM 知识智能体系统 |
| 31 | http://arxiv.org/abs/2502.20592v3 | Multi2: Multi-Agent Test-Time Scalable Framework for Multi-Document Processing | 利用测试时扩展框架，通过提示集成与聚合器生成 refined 摘要 | 解决多文档摘要中单一提示无法满足多样化需求及评估偏差问题 | 多文档处理与摘要生成 |
| 32 | http://arxiv.org/abs/2503.00237v1 | Agentic AI Needs a Systems Theory | 主张 agentic AI 发展需要更 holistic 系统理论视角理解能力及风险 | 解决当前 AI 开发过度关注个体模型能力忽视 broader emergent behavior 问题 | Agentic AI 系统发展与理解 |
| 33 | http://arxiv.org/abs/2502.16796v1 | MobileSteward: Integrating Multiple App-Oriented Agents with Self-Evolution to Automate Cross-App Instructions | 面向对象的多智能体框架，含动态招募、分配执行、调整评估模块 | 跨应用指令执行中任务关系复杂、错误传播问题 | 手机跨应用自动化任务 |
| 34 | http://arxiv.org/abs/2502.16804v2 | Multi-Agent Autonomous Driving Systems with Large Language Models: A Survey of Recent Advances | 系统综述LLM多智能体自动驾驶的分类、交互模式与挑战 | 单智能体感知有限、协作不足、计算需求高 | 自动驾驶系统 |
| 35 | http://arxiv.org/abs/2502.16866v1 | Toward Agentic AI: Generative Information Retrieval Inspired Intelligent Communications and Networking | 提出代理上下文检索框架，整合多源检索与自反思验证 | 电信网络决策需多跳推理与标准合规性 | 通信网络规划与管理 |
| 36 | http://arxiv.org/abs/2503.01861v3 | Towards Enterprise-Ready Computer Using Generalist Agent | 集成先进智能体技术与系统迭代评估实现企业级性能 | 企业环境对智能体系统的可靠性与成本要求高 | 企业级计算机操作智能体 |
| 37 | http://arxiv.org/abs/2502.17321v1 | Turning Conversations into Workflows: A Framework to Extract and Evaluate Dialog Workflows for Service AI Agents | QA-CoT提示从历史对话提取结构化工作流 | 服务工作流未文档化、自动提取未探索 | 客服AI智能体工作流 |
| 38 | http://arxiv.org/abs/2502.17651v4 | METAL: A Multi-Agent Framework for Chart Generation with Test-Time Scaling | 多智能体分解图表生成任务，展现测试时扩展现象 | 高质量图表需视觉设计与编码能力结合 | 自动专业报告图表生成 |
| 39 | http://arxiv.org/abs/2504.01962v1 | Marco: Configurable Graph-Based Task Solving and Multi-AI Agents Framework for Hardware Design | 整合可配置图任务求解与多模态多AI智能体 | 硬件设计复杂导致优化周期长、成本高 | 芯片设计与硬件优化 |
| 40 | http://arxiv.org/abs/2502.18540v2 | MA-GTS: A Multi-Agent Framework for Solving Complex Graph Problems in Real-World Applications | 多智能体分解复杂图问题，动态选择合适算法 | 图论问题复杂 noisy、LLM精度与输入长度受限 | 物流、通信网络、交通优化 |
| 41 | http://arxiv.org/abs/2502.18180v2 | ChatMotion: A Multimodal Multi-Agent for Human Motion Analysis | 动态解释用户意图，分解任务激活专用功能模块 | 多模态模型缺乏交互性与多视角适应性 | 人体运动分析 |
| 42 | http://arxiv.org/abs/2502.18652v2 | Independent Mobility GPT (IDM-GPT): A Self-Supervised Multi-Agent Large Language Model Framework for Customized Traffic Mobility Analysis Using Machine Learning Models | 多智能体框架连接用户、数据库与ML模型实现定制分析 | 交通数据分析需专业知识、隐私问题突出 | 城市交通管理与移动性分析 |
| 43 | http://arxiv.org/abs/2502.18653v1 | Enhancing Text Classification with a Novel Multi-Agent Collaboration Framework Leveraging BERT | 低置信度预测升级至多智能体系统共识决策 | 标准BERT分类器 accuracy有提升空间 | 文本分类任务 |
| 44 | http://arxiv.org/abs/2502.18702v1 | A Cooperative Multi-Agent Framework for Zero-Shot Named Entity Recognition | 四智能体协作捕获上下文关联、可控利用演示 | 零样本NER忽略上下文关联、演示使用不当 | 零样本命名实体识别 |
| 45 | http://arxiv.org/abs/2502.14282v2 | PC-Agent: A Hierarchical Multi-Agent Collaboration Framework for Complex Task Automation on PC | 分层多Agent协作架构，含Manager/Progress/Decision/Reflection四 agent | PC场景复杂交互环境及跨应用工作流自动化问题 | PC端GUI自动化任务 |
| 46 | http://arxiv.org/abs/2502.14345v1 | FlowAgent: Achieving Compliance and Flexibility for Workflow Agents | 提出程序描述语言(PDL)，结合自然语言灵活性与代码精确性 | 规则方法限制灵活性与提示方法缺乏流程合规性的矛盾 | 工作流自动化及意外查询处理场景 |

[返回目录](#目录)

<a id="cat-04"></a>

## 基于Agent的应用系统

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2502.00415v2 | MarketSenseAI 2.0: Enhancing Stock Analysis through LLM Agents | 结合 RAG 与 LLM 智能体处理财报与宏观环境分析。 | 解决传统股票分析中信息处理不全及决策支持弱问题。 | 金融投资、股票分析 |
| 2 | http://arxiv.org/abs/2502.00495v1 | Looking into the Future of Health-Care Services: Can Life-Like Agents Change the Future of Health-Care Services? | 开发拟人化智能体提供交互式健康管理服务。 | 解决在线医疗信息缺乏交互性及面对面互动缺失问题。 | 医疗健康服务、患者自助管理 |
| 3 | http://arxiv.org/abs/2502.00675v5 | ReFoRCE: A Text-to-SQL Agent with Self-Refinement, Consensus Enforcement, and Column Exploration | 通过自我 refinement 与共识机制提升 Text-to-SQL 准确率。 | 解决企业级复杂 schema 下自然语言查询 SQL 生成困难问题。 | 企业数据库查询、数据分析 |
| 4 | http://arxiv.org/abs/2502.00792v1 | RTBAgent: A LLM-based Agent System for Real-Time Bidding | 首个基于 LLM 的实时竞价智能体，同步真实竞争环境。 | 解决在线竞价环境波动大及离线在线差异导致的可靠性问题。 | 数字广告、实时竞价 |
| 5 | http://arxiv.org/abs/2502.01691v1 | Agent-Based Uncertainty Awareness Improves Automated Radiology Report Labeling with an Open-Source Large Language Model | 引入基于智能体的不确定性感知提升医疗报告标注可信度。 | 解决复杂非英文医疗报告中 LLM 预测可靠性低的问题。 | 放射学报告结构化、医疗 AI |
| 6 | http://arxiv.org/abs/2502.00988v1 | PlotGen: Multi-Agent LLM-based Scientific Data Visualization via Multimodal Feedback | orchestrate 多智能体利用多模态反馈自动化生成科学可视化。 | 解决新手用户创建精确科学图表困难及调试耗时问题。 | 科学数据可视化、图表生成 |
| 7 | http://arxiv.org/abs/2502.01089v3 | Advanced Architectures Integrated with Agentic AI for Next-Generation Wireless Networks | 设计集成代理 AI 的 6G 架构，优化资源分配与能耗。 | 解决下一代无线网络运营复杂及资源管理低效问题。 | 6G 通信网络、无线资源管理 |
| 8 | http://arxiv.org/abs/2502.01492v1 | Develop AI Agents for System Engineering in Factorio | 倡导通过自动化沙盒游戏训练评估 AI 智能体系统工程能力。 | 解决静态基准无法捕捉动态系统工程中权衡与适应性技能问题。 | 系统工程、复杂系统设计 |
| 9 | http://arxiv.org/abs/2502.01503v2 | Sea-cret Agents: Maritime Abduction for Region Generation to Expose Dark Vessel Trajectories | 结合 abduction 与逻辑编程定位关闭 AIS 的暗船轨迹。 | 解决机器学习方法仅能预测短期位置及搜索区域过大问题。 | 海事安全、非法船只追踪 |
| 10 | http://arxiv.org/abs/2502.01789v1 | An Agentic AI Workflow for Detecting Cognitive Concerns in Real-world Data | 开发全自动多智能体工作流识别临床笔记中认知问题。 | 解决认知问题早期识别困难及症状表现 subtle 问题。 | 临床医疗、认知障碍检测 |
| 11 | http://arxiv.org/abs/2502.01821v2 | Agentic Bug Reproduction for Effective Automated Program Repair at Google | 提出 BRT Agent 生成 bug 复现测试加速自动化程序修复。 | 解决 bug 报告缺乏复现细节导致修复时间长的问题。 | 软件工程、自动化调试 |
| 12 | http://arxiv.org/abs/2502.04345v3 | Jingfang: An LLM-Based Multi-Agent System for Precise Medical Consultation and Syndrome Differentiation in Traditional Chinese Medicine | 构建多智能体协作咨询机制模拟真实中医诊疗工作流。 | 解决现有中医 LLM 问诊框架 rigid 及辨证不准确问题。 | 传统中医、辅助诊疗 |
| 13 | http://arxiv.org/abs/2503.11657v2 | Automating Mathematical Proof Generation Using Large Language Model Agents and Knowledge Graphs | 利用知识图谱增强 LLM 智能体构建及形式化数学证明。 | 解决定理证明中关键概念识别及形式化困难问题。 | 自动定理证明、数学推理 |
| 14 | http://arxiv.org/abs/2502.02673v2 | MedRAX: Medical Reasoning Agent for Chest X-ray | 集成多模态大模型与 CXR 分析工具的统一医疗推理代理框架。 | 解决现有胸部 X 光分析模型孤立运行及临床实用性低问题。 | 医疗影像诊断、临床决策支持 |
| 15 | http://arxiv.org/abs/2502.02747v2 | PatchPilot: A Cost-Efficient Software Engineering Agent with Early Attempts on Formal Verification | 结合规则规划与形式化验证的低成本软件工程代理。 | 解决现有补丁代理成本高、稳定性差及工作流局限问题。 | 自动化软件工程、代码修复 |
| 16 | http://arxiv.org/abs/2502.02807v1 | CAMI: A Counselor Agent Supporting Motivational Interviewing through State Inference and Topic Exploration | 基于 STAR 框架的动机性访谈咨询代理，推断客户状态。 | 解决可扩展心理健康支持缺乏个性化及行为改变引导问题。 | 心理健康咨询、自动辅导 |
| 17 | http://arxiv.org/abs/2502.03207v2 | MotionAgent: Fine-grained Controllable Video Generation via Motion Field Agent | 运动场代理将文本运动信息转化为显式光流控制视频生成。 | 解决文本引导视频生成中细粒度运动控制不精确问题。 | 视频生成、内容创作 |
| 18 | http://arxiv.org/abs/2502.03424v5 | Prediction of the Most Fire-Sensitive Point in Building Structures with Differentiable Agents for Thermal Simulators | 图神经网络作为可微代理预测火灾敏感点，优化安全评估。 | 解决建筑结构火灾场景模拟成本高及最坏情况识别困难问题。 | 建筑安全评估、火灾模拟 |
| 19 | http://arxiv.org/abs/2502.03821v1 | PsyPlay: Personality-Infused Role-Playing Conversational Agents | 对话生成框架使多 LLM 代理在交互中一致展现指定人格特质。 | 解决角色扮演代理忽略深层人格特质及对话一致性差问题。 | 角色扮演、对话生成 |
| 20 | http://arxiv.org/abs/2502.03948v1 | Enhancing Online Learning Efficiency Through Heterogeneous Resource Integration with a Multi-Agent RAG System | 多代理 RAG 系统自动化检索整合异构学习资源，提升效率。 | 解决在线学习资源分散及手动查找整合知识效率低问题。 | 在线学习、知识检索 |
| 21 | http://arxiv.org/abs/2502.06842v4 | Agentic AI for Scaling Diagnosis and Care in Neurodegenerative Disease | 提出六阶段路线图，负责任设计集成代理 AI 到神经退行性疾病护理。 | 解决神经护理需求增长及专科医生短缺导致诊疗可及性低问题。 | 医疗健康、神经退行性疾病 |
| 22 | http://arxiv.org/abs/2502.05036v1 | nvAgent: Automated Data Visualization from Natural Language via Collaborative Agent Workflow | 构建三智能体协作工作流，实现自然语言到可视化自动化。 | 解决复杂多表查询下自然语言生成可视化代码困难问题。 | 数据分析、自动化可视化 |
| 23 | http://arxiv.org/abs/2502.05439v2 | Agentic AI Systems Applied to tasks in Financial Services: Modeling and model risk management crews | 构建含人机回环模块的智能体crew，执行建模与风险管理任务。 | 解决金融服务中复杂建模及模型风险管理任务自动化问题。 | 金融服务、模型风险管理 |
| 24 | http://arxiv.org/abs/2502.05664v1 | CODESIM: Multi-Agent Code Generation and Problem Solving through Simulation-Driven Planning and Debugging | 通过输入输出逐步模拟验证计划及内部调试，提升代码生成。 | 解决代码生成中初始代码质量低及依赖外部调试器问题。 | 代码生成、程序合成 |
| 25 | http://arxiv.org/abs/2503.16433v1 | The Application of MATEC (Multi-AI Agent Team Care) Framework in Sepsis Care | 集成多专科 AI 智能体团队，辅助资源匮乏医院脓毒症护理。 | 解决资源匮乏医院专科医疗 access 受限及患者预后差问题。 | 医疗健康、脓毒症护理 |
| 26 | http://arxiv.org/abs/2502.05982v2 | HamRaz: A Culture-Based Persian Conversation Dataset for Person-Centered Therapy Using LLM Agents | 构建文化适配波斯语数据集，支持以人为本治疗 LLM 智能体。 | 解决代表性不足社区中语言文化及心理健康支持资源缺乏问题。 | 心理健康、跨文化对话 |
| 27 | http://arxiv.org/abs/2502.07132v3 | Interactive Data Harmonization with LLM Agents: Opportunities and Challenges | 提出 Harmonia 系统，结合 LLM 推理及交互 UI 自动化数据协调。 | 解决多源数据集整合中模式不匹配及术语差异导致耗时问题。 | 数据协调、临床数据整合 |
| 28 | http://arxiv.org/abs/2502.10050v1 | A Survey on LLM-powered Agents for Recommender Systems | 系统梳理LLM智能体在推荐系统中的三大范式与架构组件 | 传统推荐系统难理解复杂偏好与提供可解释推荐 | 在线平台的个性化推荐与用户交互 |
| 29 | http://arxiv.org/abs/2502.10173v1 | Agentic End-to-End De Novo Protein Design for Tailored Dynamics Using a Language Diffusion Model | VibeGen采用双模型架构实现基于振动模式的端到端蛋白质设计 | 蛋白质序列-结构-动态关系复杂导致定向设计困难 | 具有定制动态特性的生物分子理性设计 |
| 30 | http://arxiv.org/abs/2502.10557v2 | Can Large Language Model Agents Balance Energy Systems? | LLM智能体引导随机机组组合决策，动态适应风电不确定性 | 高可再生能源渗透下能源系统调度效率与可靠性平衡 | 含高比例风电的电力系统优化调度 |
| 31 | http://arxiv.org/abs/2502.10937v2 | SCALE: Towards Collaborative Content Analysis in Social Science with Large Language Model Agents and Human Intervention | SCALE模拟内容分析全流程，支持多模式人类干预增强专家输入 | 社会科学内容分析依赖多轮人工标注与规则迭代的效率瓶颈 | 社会科学研究中的大规模文本编码与理论构建 |
| 32 | http://arxiv.org/abs/2502.11211v2 | A Survey of LLM-based Agents in Medicine: How far are we from Baymax? | 全面综述医学LLM智能体的架构组件、应用场景、评估框架与挑战 | 医疗领域智能体研究分散缺乏系统性梳理与方向指引 | 临床决策支持、医疗文档、培训模拟等医疗智能体研发 |
| 33 | http://arxiv.org/abs/2502.13165v1 | HedgeAgents: A Balanced-aware Multi-agent Financial Trading System | HedgeAgents通过中央基金经理与多类别对冲专家的智能体协作实现稳健交易 | LLM交易智能体在市场快速波动时面临显著亏损的鲁棒性挑战 | 自动化金融交易中的风险控制与收益平衡 |
| 34 | http://arxiv.org/abs/2502.11433v3 | FLAG-Trader: Fusion LLM-Agent with Gradient-based Reinforcement Learning for Financial Trading | FLAG-Trader融合微调LLM策略网络与梯度RL优化，通过交易奖励驱动策略提升 | 金融多步决策场景中纯LLM方法难以优化长期目标导向行为 | 交互式金融市场中的自动化交易决策 |
| 35 | http://arxiv.org/abs/2503.04773v4 | Invisible Walls in Cities: Designing LLM Agent to Predict Urban Segregation Experience with Social Media Content | 反思式LLM编码员+RE'EM框架挖掘社交媒体内容预测城市隔离体验 | 海量模糊社交媒体数据中隐含社会隔离信号的自动化提取困难 | 城市社会学研究中的社会包容性评估与政策制定 |
| 36 | http://arxiv.org/abs/2502.07393v1 | FinRL-DeepSeek: LLM-Infused Risk-Sensitive Reinforcement Learning for Trading Agents | 结合 LLM 风险评估信号与 CPPO 算法，构建风险敏感交易智能体。 | 解决传统交易智能体缺乏新闻语义理解及风险敏感度问题。 | 金融交易、量化投资 |
| 37 | http://arxiv.org/abs/2502.07928v1 | Distributed Approach to Haskell Based Applications Refactoring with LLMs Based Multi-Agent Systems | 多智能体系统自动化重构 Haskell 代码，优化复杂度及性能指标。 | 解决函数式编程语言重构挑战及缺乏自动化优化工具问题。 | 软件工程、代码重构 |
| 38 | http://arxiv.org/abs/2502.08337v1 | Hierarchical Multi-Agent Framework for Carbon-Efficient Liquid-Cooled Data Center Clusters | 分层多智能体框架动态优化数据中心集群工作负载及液冷冷却。 | 解决云计算环境影响及多数据中心协同能效优化困难问题。 | 数据中心管理、绿色计算 |
| 39 | http://arxiv.org/abs/2502.08916v1 | PathFinder: A Multi-Modal Multi-Agent System for Medical Diagnostic Decision-Making Applied to Histopathology | 多模态多智能体框架模拟病理学家决策，导航 WSIs 并提供诊断。 | 解决病理切片 gigapixel 尺度及传统 AI 缺乏 holistic 诊断流程问题。 | 医疗诊断、病理学 AI |
| 40 | http://arxiv.org/abs/2502.12561v3 | UXAgent: An LLM Agent-Based Usability Testing Framework for Web Design | 生成数千模拟用户自动测试网站，提供定性定量反馈 | 解决可用性测试招募难、迭代设计缺陷不灵活的问题 | Web 设计可用性测试 |
| 41 | http://arxiv.org/abs/2502.12633v2 | One Size doesn't Fit All: A Personalized Conversational Tutoring Agent for Mathematics Instruction | 模拟学生学习风格，采用苏格拉底法提供个性化教学策略 | 解决传统 tutoring 系统忽视个体学习风格差异的问题 | 数学个性化教学辅导 |
| 42 | http://arxiv.org/abs/2502.12836v2 | An LLM-Powered Agent for Physiological Data Analysis: A Case Study on PPG-based Heart Rate Estimation | 集成分析工具与用户交互，准确估算心率健康指标 | 解决 LLM 直接处理生理时间序列数据效率低不可靠问题 | 医疗健康生理数据分析 |
| 43 | http://arxiv.org/abs/2502.12927v3 | SEFL: A Framework for Generating Synthetic Educational Assignment Feedback with LLM Agents | 师生角色模拟生成合成反馈数据，微调小模型提供高质量反馈 | 解决教育反馈受时间与预算限制难以规模化问题 | 高等教育作业反馈 |
| 44 | http://arxiv.org/abs/2502.13010v3 | Agentic Medical Knowledge Graphs Enhance Medical Question Answering: Bridging the Gap Between LLMs and Evolving Medical Knowledge | 自动化构建更新医疗 KG，整合外部证据提升准确性 | 解决医疗知识快速演变导致 LLM 回答不可靠问题 | 医疗问答系统 |
| 45 | http://arxiv.org/abs/2502.13069v3 | Ambig-SWE: Interactive Agents to Overcome Underspecificity in Software Engineering | 评估 Agent 处理模糊指令能力，强调交互澄清价值 | 解决软件工程中因指令模糊导致假设错误与资源浪费问题 | 交互式代码生成 |
| 46 | http://arxiv.org/abs/2502.13311v3 | Training Turn-by-Turn Verifiers for Dialogue Tutoring Agents: The Curious Case of LLMs as Your Coding Tutors | 结合知识追踪与逐轮验证，提升编码辅导成功率 | 解决 LLM 导师在复杂任务中引导能力不足的问题 | 编码辅导智能体 |
| 47 | http://arxiv.org/abs/2502.13476v1 | Integration of Agentic AI with 6G Networks for Mission-Critical Applications: Use-case and Challenges | 提出多层架构实现 Agentic AI，提升任务关键应用响应速度 | 解决任务关键应用缺乏适应性及情境感知的问题 | 6G 网络与公共安全应用 |
| 48 | http://arxiv.org/abs/2502.13767v4 | Agentic AI Software Engineers: Programming with Trust | 探讨 LLM Agent 整合分析工具以建立代码信任的路径 | 解决 AI 软件工程部署中信任建立不足的问题 | 软件工程与工作流 |
| 49 | http://arxiv.org/abs/2502.13789v1 | From Correctness to Comprehension: AI Agents for Personalized Error Diagnosis in Education | 多 Agent 协作框架结合历史数据，提升错误诊断与反馈质量 | 解决当前模型重正确性轻错误诊断与反馈生成的问题 | 个性化教育错误诊断 |
| 50 | http://arxiv.org/abs/2502.13843v2 | AgentCF++: Memory-enhanced LLM-based Agents for Popularity-aware Cross-domain Recommendations | 双层记忆架构融合跨域偏好，捕捉流行度因素影响 | 解决跨域推荐中用户 Agent 记忆引入无关信息及忽视流行度问题 | 跨域推荐系统 |
| 51 | http://arxiv.org/abs/2502.13959v3 | LIDDIA: Language-based Intelligent Drug Discovery Agent | 自主导航药物发现流程，平衡化学空间探索与利用 | 解决药物发现过程漫长昂贵且依赖人工化学家的问题 | 自主药物发现 |
| 52 | http://arxiv.org/abs/2502.14144v1 | UM_FHS at TREC 2024 PLABA: Exploration of Fine-tuning and AI agent approach for plain language adaptations of biomedical text | 探索双 Agent 与微调方法简化生物医学文本供学生阅读 | 解决生物医学摘要对非专业读者过于复杂的问题 | 生物医学文本简化 |
| 53 | http://arxiv.org/abs/2502.19175v2 | MEDDxAgent: A Unified Modular Agent Framework for Explainable Automatic Differential Diagnosis | 模块化可解释 DDx 智能体框架，支持交互式诊断推理与迭代学习 | 解决现有医疗诊断方法缺乏交互性、可解释性及完整患者档案假设问题 | 临床自动差分诊断 |
| 54 | http://arxiv.org/abs/2503.01880v1 | BEYONDWORDS is All You Need: Agentic Generative AI based Social Media Themes Extractor | 集成 tweet 嵌入与生成式 AI，通过智能体思维链提示提取主题 | 解决传统方法难以捕捉社交媒体非结构化文本复杂性与细微差别问题 | 社交媒体帖子主题分析 |
| 55 | http://arxiv.org/abs/2502.19519v2 | Static Vs. Agentic Game Master AI for Facilitating Solo Role-Playing Experiences | 利用多智能体架构与 ReAct 框架改进游戏大师 AI，提升沉浸感与好奇心 | 提升单人角色扮演游戏中的互动叙事体验与系统模块化 | 单人角色扮演游戏体验 |
| 56 | http://arxiv.org/abs/2502.19629v1 | Agentic Mixture-of-Workflows for Multi-Modal Chemical Search | 提出工作流混合范式，编排多个智能体工作流进行自我纠正检索增强生成 | 解决材料科学中缺乏基准标准及实用实施框架的问题 | 多模态化学搜索与材料发现 |
| 57 | http://arxiv.org/abs/2502.19860v2 | MIND: Towards Immersive Psychological Healing with Multi-agent Inner Dialogue | 提出多智能体内心对话范式，分配不同角色智能体提供沉浸式治愈体验 | 解决传统心理咨询缺乏情感深度及 LLM 难以捕捉细微情绪问题 | 心理健康沉浸式治愈环境 |
| 58 | http://arxiv.org/abs/2502.20301v1 | M^3Builder: A Multi-Agent System for Automated Machine Learning in Medical Imaging | 四智能体协作自动化医疗影像 ML 工作流，含数据處理到模型训练 | 解决医疗领域自动化工具依赖及复杂多步 ML 工作流执行问题 | 医疗影像自动化机器学习 |
| 59 | http://arxiv.org/abs/2502.20527v1 | Supervised Fine-Tuning LLMs to Behave as Pedagogical Agents in Programming Education | 监督微调 LLM 作为教学智能体，提升苏格拉底式指导及简洁性 | 解决现有 LLM 在教学中过度协助学生及缺乏教学法有效性问题 | 编程教育中的教学智能体 |
| 60 | http://arxiv.org/abs/2502.20689v2 | WiseMind: Recontextualizing AI with a Knowledge-Guided, Theory-Informed Multi-Agent Framework for Instrumental and Humanistic Benefits | 知识引导主动推理与理论知情双智能体架构，协调理性与情感智能体 | 解决精神科诊断中知识上下文不足及缺乏共情评估问题 | 精神科差分诊断 |
| 61 | http://arxiv.org/abs/2502.20791v2 | CyLens: Towards Reinventing Cyber Threat Intelligence in the Paradigm of Agentic Large Language Models | 威胁智能 copilot，集成大量威胁报告知识及专用 NLP 模块增强推理 | 解决网络安全专业人员应对海量动态威胁数据缺乏有效工具问题 | 网络威胁智能分析 |
| 62 | http://arxiv.org/abs/2503.00092v2 | EdgeAIGuard: Agentic LLMs for Minor Protection in Digital Spaces | 多智能体架构部署于网络边缘，实现低延迟检测防止有害内容 | 解决传统内容审核技术对针对未成年人的剥削 evolving tactics 无效问题 | 数字空间未成年人保护 |
| 63 | http://arxiv.org/abs/2503.00162v1 | PreMind: Multi-Agent Video Understanding for Advanced Indexing of Presentation-style Videos | 多智能体多模态框架，利用 prior 知识及 critic 智能体改进视频索引 | 解决在线讲座视频有效理解/索引以支持下游问答任务的需求 | 演示风格视频的高级索引 |
| 64 | http://arxiv.org/abs/2503.00164v1 | Transforming Cyber Defense: Harnessing Agentic and Frontier AI for Proactive, Ethical Threat Intelligence | 探索 agentic AI 与 Frontier AI 融合，重构网络杀伤链及威胁智能 | 应对数字复杂性时代传统防御范式面临的 APT 及 evolving 威胁挑战 | 网络防御与威胁智能 |
| 65 | http://arxiv.org/abs/2502.16730v2 | RapidPen: Fully Automated IP-to-Shell Penetration Testing with LLM-based Agents | 集成ReAct规划与检索增强知识库实现全自动渗透测试 | 渗透测试需人工干预、效率低、成本高 | 网络安全渗透测试 |
| 66 | http://arxiv.org/abs/2503.16463v1 | Improving Interactive Diagnostic Ability of a Large Language Model Agent Through Clinical Experience Learning | 开发PPME方法，整合专用模型进行初始诊断与病史询问 | LLM在交互式诊断中信息收集效率低 | 医疗交互式诊断系统 |
| 67 | http://arxiv.org/abs/2502.16879v1 | A Multi-LLM-Agent-Based Framework for Economic and Public Policy Analysis | 利用不同LLM固有差异建模异质经济智能体 | 传统模拟仅通过提示变化模拟异质性不足 | 经济政策分析与模拟 |
| 68 | http://arxiv.org/abs/2502.18525v2 | Programming with Pixels: Can Computer-Use Agents do Software Engineering? | 创建PwP环境与基准评估视觉控制IDE的软件工程能力 | 通用智能体在专业软件工程任务上表现 unclear | 软件工程自动化 |
| 69 | http://arxiv.org/abs/2502.18528v1 | ARACNE: An LLM-Based Autonomous Shell Pentesting Agent | 多LLM模型支持的自主SSH渗透测试智能体架构 | SSH服务渗透测试需自动化、高成功率 | 网络安全渗透测试 |
| 70 | http://arxiv.org/abs/2502.18228v1 | Debt Collection Negotiations with Large Language Models: An Evaluation System and Optimizing Decision Making with Multi-Agent | MADeN框架含规划与判断模块优化决策理性 | LLM在债务谈判中过度让步、缺乏动态决策 | 债务催收谈判自动化 |
| 71 | http://arxiv.org/abs/2502.14662v4 | iAgent: LLM Agent as a Shield between User and Recommender Systems | 提出用户-Agent-平台新范式，Agent作为用户与推荐系统间的保护盾 | 传统推荐系统中用户易受平台算法操控、缺乏个性化问题 | 推荐系统用户隐私与利益保护 |
| 72 | http://arxiv.org/abs/2502.14994v1 | LAVID: An Agentic LVLM Framework for Diffusion-Generated Video Detection | 基于LVLM的AI生成视频检测框架，自动选择知识工具并自适应调整提示 | 传统深度学习方法缺乏透明度及无法识别新伪影的问题 | AI生成视频内容检测 |
| 73 | http://arxiv.org/abs/2502.15506v1 | Construction and Evaluation of LLM-based agents for Semi-Autonomous penetration testing | 多LLM模块半自主执行网络安全工作流，制定策略/生成命令/分析结果 | 网络安全领域因LLM推理与领域知识限制难以实现全自主 | Hack The Box虚拟机渗透测试 |
| 74 | http://arxiv.org/abs/2502.15601v2 | WorldCraft: Photo-Realistic 3D World Creation and Customization via LLM Agents | 协调员+ForgeIt+ArrangeIt三Agent协作，通过自然语言创建3D场景 | 构建逼真虚拟世界需专业人员操作3D建模软件，门槛高 | 室内外3D场景创建与定制 |
| 75 | http://arxiv.org/abs/2502.17506v3 | RAG-Enhanced Collaborative LLM Agents for Drug Discovery | CLADD系统，多Agent协作动态检索生物医学知识库，无需领域微调 | 生化数据专业化需昂贵微调，限制通用LLM应用及新数据整合 | 药物发现任务 |
| 76 | http://arxiv.org/abs/2502.16069v2 | Curie: Toward Rigorous and Automated Scientific Experimentation with AI Agents | 三模块框架(代理内/代理间严谨模块+实验知识模块)嵌入实验严谨性 | 自动化严谨科学实验仍具挑战性，LLM能力未充分整合 | 计算机科学实验自动化 |
| 77 | http://arxiv.org/abs/2502.16343v1 | Exploring Sentiment Manipulation by LLM-Enabled Intelligent Trading Agents | 首个基于连续深度强化学习的智能交易Agent，可控制LLM发布社交媒体 | 研究LLM交易Agent通过操纵帖子情感优化奖励与利润的机制 | 模拟金融市场交易 |

[返回目录](#目录)

<a id="cat-05"></a>

## Agent可解释性与透明度

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2502.00726v1 | Perspectives for Direct Interpretability in Multi-Agent Deep Reinforcement Learning | 倡导直接可解释性，从训练后模型生成事后解释。 | 解决多智能体深度强化学习模型行为难以理解问题。 | 多智能体系统调试与信任 |
| 2 | http://arxiv.org/abs/2502.10732v1 | Rule-Bottleneck Reinforcement Learning: Joint Explanation and Decision Optimization for Resource Allocation with Language Agents | RBRL联合优化决策与解释，LLM生成规则+RL选择+链式推理执行 | 深度RL策略缺乏透明性与人类决策者协同的适应性 | 医疗、公共政策等需要可解释决策的资源分配场景 |
| 3 | http://arxiv.org/abs/2502.09889v1 | Evaluating and Improving Graph-based Explanation Methods for Multi-Agent Coordination | 提出注意力熵正则化项，提升 GNN 多智能体协调解释质量。 | 解决现有 GNN 解释方法识别多智能体关键通信渠道困难问题。 | 多智能体协调、可解释 AI |

[返回目录](#目录)

<a id="cat-06"></a>

## Agent评测与基准

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2502.00964v3 | ML-Dev-Bench: Comparative Analysis of AI Agents on ML development workflows | 构建 ML-Dev-Bench 基准，评估智能体在 ML 开发工作流能力。 | 解决现有基准仅测试孤立编码任务而非完整 ML 流程问题。 | 机器学习开发自动化评估 |
| 2 | http://arxiv.org/abs/2502.01635v1 | The AI Agent Index | 建立首个公共数据库记录已部署代理 AI 系统组件与安全特征。 | 解决缺乏结构化框架记录代理系统技术及安全信息问题。 | AI 系统文档、风险管理 |
| 3 | http://arxiv.org/abs/2502.05227v1 | Robotouille: An Asynchronous Planning Benchmark for LLM Agents | 构建异步规划基准环境，测试 LLM 代理长程异步任务能力。 | 解决现有基准缺乏异步规划评估及长程任务反馈机制问题。 | LLM 代理规划能力评估 |
| 4 | http://arxiv.org/abs/2502.04773v2 | An Extended Benchmarking of Multi-Agent Reinforcement Learning Algorithms in Complex Fully Cooperative Tasks | 扩展基准评估 MARL 算法在复杂全协作任务及高维观测下表现。 | 解决现有基准缺乏系统性多样性及高维观测评估不足问题。 | 多智能体强化学习评估 |
| 5 | http://arxiv.org/abs/2502.05352v1 | ITBench: Evaluating AI Agents across Diverse Real-World IT Automation Tasks | 构建 ITBench 框架，系统评估 AI 智能体在真实 IT 自动化任务表现。 | 解决缺乏衡量 AI 智能体在关键 IT 任务有效性基准问题。 | IT 自动化、智能体能力评估 |
| 6 | http://arxiv.org/abs/2502.06111v2 | CSR-Bench: Benchmarking LLM Agents in Deployment of Computer Science Research Repositories | 构建 CSR-Bench 基准，评估 LLM 智能体部署 CS 研究代码库能力。 | 解决缺乏评估 LLM 处理复杂 CS 研究项目代码开发任务基准问题。 | 软件工程、研究仓库部署 |
| 7 | http://arxiv.org/abs/2502.07853v1 | PolicySimEval: A Benchmark for Evaluating Policy Outcomes through Agent-Based Simulation | 首个评估基于智能体仿真政策结果能力的基准，含多类任务。 | 解决缺乏系统方法验证智能体仿真在政策评估中有效性问题。 | 政策评估、社会仿真 |
| 8 | http://arxiv.org/abs/2502.08788v3 | Stop Overvaluing Multi-Agent Debate -- We Must Rethink Evaluation and Embrace Model Heterogeneity | 系统评估多智能体辩论方法，发现模型异构性是关键改进点。 | 解决 MAD 评估实践局限及过度估值问题，提倡异构设计。 | 多智能体辩论、评估方法 |
| 9 | http://arxiv.org/abs/2502.09560v3 | EmbodiedBench: Comprehensive Benchmarking Multi-modal Large Language Models for Vision-Driven Embodied Agents | 全面基准评估视觉驱动具身智能体，含多环境及能力子集。 | 解决 MLLM 具身智能体缺乏综合评估框架及低层任务研究不足问题。 | 具身智能体、模型评估 |
| 10 | http://arxiv.org/abs/2502.12257v2 | InfoQuest: Evaluating Multi-Turn Dialogue Agents for Open-Ended Conversations with Hidden Context | 设计隐藏上下文基准，评估 Agent 信息寻求与澄清能力 | 解决模型面对模糊请求默认生成通用回复的问题 | 开放域多轮对话 Agent |
| 11 | http://arxiv.org/abs/2502.13012v3 | Towards a Design Guideline for RPA Evaluation: A Survey of Large Language Model-Based Role-Playing Agents | 系统综述提出 RPA 评估设计指南，标准化评估方法 | 解决 RPA 评估因任务多样缺乏系统一致方法的问题 | 角色扮演 Agent 评估 |
| 12 | http://arxiv.org/abs/2502.13897v1 | DataSciBench: An LLM Agent Benchmark for Data Science | 构建全面数据科学基准，半自动化生成 ground truth 与指标 | 解决现有基准任务单一及评估指标简单的问题 | 数据科学 LLM 能力评估 |
| 13 | http://arxiv.org/abs/2502.18754v1 | AgentSociety Challenge: Designing LLM Agents for User Modeling and Recommendation on Web Platforms | 首个 Web 会议 LLM 智能体竞赛，开源基准环境，探索用户建模与推荐 | 探索 LLM 智能体在 Web 平台用户建模与推荐系统中的潜力 | Web 平台用户行为建模与推荐系统 |
| 14 | http://arxiv.org/abs/2502.18836v2 | REALM-Bench: A Benchmark for Evaluating Multi-Agent Systems on Real-world, Dynamic Planning and Scheduling Tasks | 提供综合评估框架，涵盖 14 个规划调度问题，支持动态环境 disruptions | 评估单个 LLM 和多智能体系统在现实世界规划调度场景中的能力 | 现实世界规划与调度任务的多智能体系统 |
| 15 | http://arxiv.org/abs/2502.20073v3 | Collab-Overcooked: Benchmarking and Evaluating Large Language Models as Collaborative Agents | 提出 Collab-Overcooked 基准，支持自然语言通信及过程导向评估指标 | 评估 LLM 智能体在交互环境中的细粒度协作能力 | 基于 LLM 的多智能体系统协作能力评估 |
| 16 | http://arxiv.org/abs/2502.20379v1 | Multi-Agent Verification: Scaling Test-Time Compute with Multiple Verifiers | 提出多智能体验证范式，结合多个验证者扩展测试时计算提升性能 | 利用测试时计算资源扩展提升大语言模型性能 without additional training | 大语言模型测试时验证与性能提升 |
| 17 | http://arxiv.org/abs/2502.20807v1 | Digital Player: Evaluating Large Language Models based Human-like Agent in Games | 基于 Unciv 游戏构建测试床，研究数字玩家任务中类人智能体 | 评估 LLM 智能体在数值推理、长期规划及社会交互中的人类相似度 | 游戏中的类人智能体评估 |
| 18 | http://arxiv.org/abs/2503.00096v3 | BixBench: a Comprehensive Benchmark for LLM-based Agents in Computational Biology | 提出生物信息学基准，含 50+ 真实场景及 300+ 开放问题评估 agent 能力 | 解决生物信息学领域缺乏衡量 LLM 智能体进展的广泛基准问题 | 计算生物学中的 LLM 基于智能体 |
| 19 | http://arxiv.org/abs/2502.17903v1 | Towards Sustainable Web Agents: A Plea for Transparency and Dedicated Metrics for Energy Consumption | 首次探索Web智能体能耗与CO2成本，呼吁专用指标 | Web智能体可持续性研究缺乏、透明度不足 | Web智能体能耗评估 |
| 20 | http://arxiv.org/abs/2502.17924v2 | FACT-AUDIT: An Adaptive Multi-Agent Framework for Dynamic Fact-Checking Evaluation of Large Language Models | 自适应生成数据集、迭代模型中心评估与更新 | 静态数据集无法评估LLM事实核查推理能力 | LLM事实核查能力评估 |
| 21 | http://arxiv.org/abs/2502.17945v2 | Assessing Agentic Large Language Models in Multilingual National Bias | 首次量化多语言场景下LLM智能体的国家偏见 | 跨语言推理建议中的偏见差异未探索 | 多语言AI智能体应用 |
| 22 | http://arxiv.org/abs/2502.17967v2 | Agent Trading Arena: A Study on Numerical Understanding in LLM-Based Agents | 创建虚拟零和股票市场让LLM智能体竞争影响价格 | 历史回测无法模拟真实市场动态交互 | 金融交易LLM智能体评估 |
| 23 | http://arxiv.org/abs/2502.18308v1 | RefuteBench 2.0 -- Agentic Benchmark for Dynamic Evaluation of LLM Responses to Refutation Instruction | 引入LLM智能体作为反驳者与评估者实现灵活评估 | 评估LLM整合用户反驳反馈能力困难 | LLM多轮交互反驳能力评估 |
| 24 | http://arxiv.org/abs/2502.18356v1 | WebGames: Challenging General-Purpose Web-Browsing AI Agents | 50+互动挑战基准测试Web浏览智能体基础能力 | 当前AI系统处理常见Web交互模式能力有限 | 通用Web浏览AI智能体评估 |
| 25 | http://arxiv.org/abs/2502.14499v1 | MLGym: A New Framework and Benchmark for Advancing AI Research Agents | 首个ML任务Gym环境，含13个多样化AI研究任务基准 | 缺乏评估LLM Agent AI研究能力的标准化框架与基准 | AI研究任务（CV、NLP、RL、博弈论等） |
| 26 | http://arxiv.org/abs/2502.15840v1 | Vending-Bench: A Benchmark for Long-Term Coherence of Autonomous Agents | 模拟自动售货机运营环境，测试长周期(>20M tokens)决策一致性 | LLM在长时程任务中难以保持连贯性能的问题 | 自主Agent长时程任务能力评估 |
| 27 | http://arxiv.org/abs/2502.15850v2 | Forecasting Frontier Language Model Agent Capabilities | 两步预测法(发布日期→Elo→基准)，预测前沿模型Agent能力 | 准确预测LM Agent能力对社会准备至关重要但缺乏有效方法 | SWE-Bench、Cybench、RE-Bench等基准 |
| 28 | http://arxiv.org/abs/2502.15212v1 | Measuring AI agent autonomy: Towards a scalable approach with code inspection | 基于代码的自主性评估框架，按影响与监督属性评分编排代码 | 当前自主性评估依赖运行时评估，成本高且风险大 | AutoGen框架及应用 |

[返回目录](#目录)

<a id="cat-07"></a>

## 具身智能Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2502.01218v3 | Provable Ordering and Continuity in Vision-Language Pretraining for Generalizable Embodied Agents | 提出 AcTOL 学习有序连续视语言表示，无需刚性目标约束。 | 解决具身智能体预训练中视语言关联错误及泛化性差问题。 | 机器人操作、模仿学习 |
| 2 | http://arxiv.org/abs/2502.04809v3 | Humans Coexist, So Must Embodied Artificial Agents | 提出具身人工智能体共存概念，强调长期野外交互能力。 | 解决具身智能体在动态长期人机交互中适应性不足问题。 | 具身机器人、人机共存环境 |
| 3 | http://arxiv.org/abs/2502.05857v3 | EgoAgent: A Joint Predictive Agent Model in Egocentric Worlds | 统一 Transformer 模型同时学习表征、预测及第一人称行动。 | 解决具身智能体感知、预测与行动能力分离及协同学习难问题。 | 第一人称视觉、具身智能 |
| 4 | http://arxiv.org/abs/2502.06725v2 | AgilePilot: DRL-Based Drone Agent for Real-Time Motion Planning in Dynamic Environments by Leveraging Object Detection | 提出基于 DRL 及实时 CV 的无人机运动规划器，桥接 Sim2Real。 | 解决动态环境中无人机实时导航适应性差及经典算法次优问题。 | 无人机导航、动态环境规划 |
| 5 | http://arxiv.org/abs/2502.10046v1 | ViRAC: A Vision-Reasoning Agent Head Movement Control Framework in Arbitrary Virtual Environments | 利用VLM/LLM常识推理实现虚拟环境中拟人化头部运动控制 | 传统方法头部行为僵硬、忽略关键场景元素 | 虚拟环境中的逼真智能体行为生成 |
| 6 | http://arxiv.org/abs/2502.11864v1 | Does Knowledge About Perceptual Uncertainty Help an Agent in Automated Driving? | 将感知不确定性信息直接纳入观测空间，智能体自适应调整驾驶策略 | 自动驾驶智能体在感知不确定环境下难以平衡速度与安全性 | 不确定感知条件下的自动驾驶决策与风险控制 |
| 7 | http://arxiv.org/abs/2502.12532v3 | CityEQA: A Hierarchical LLM Agent on Embodied Question Answering Benchmark in City Space | 提出 PMA 分层 Agent 架构，支持城市空间长程规划与探索 | 解决城市动态环境中具身问答的复杂感知与行动问题 | 城市空间具身导航与问答 |
| 8 | http://arxiv.org/abs/2502.19902v2 | Optimus-2: Multimodal Minecraft Agent with Goal-Observation-Action Conditioned Policy | 结合 MLLM 高层规划与 GOAP 低层控制，建模观察 - 动作因果关系 | 解决开放世界任务中智能体学习行为模式及观察动作语言关系建模 | Minecraft 多模态智能体 |
| 9 | http://arxiv.org/abs/2502.18615v4 | A Distributional Treatment of Real2Sim2Real for Object-Centric Agent Adaptation in Vision-Driven Deformable Linear Object Manipulation | 似然自由推断计算物理参数后验用于域随机化 | 可变形线性物体操作需Real2Sim2Real适应 | 视觉驱动机器人物体操作 |

[返回目录](#目录)

<a id="cat-08"></a>

## 人机协作Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2502.01340v3 | Human-Agent Interaction in Synthetic Social Networks: A Framework for Studying Online Polarization | 嵌入形式化意见动力学原理到 LLM 智能体研究在线极化。 | 解决数学模型缺乏语言真实性与 LM 模拟缺乏分析精度问题。 | 社交媒体研究、舆论动力学 |
| 2 | http://arxiv.org/abs/2502.01390v1 | Plan-Then-Execute: An Empirical Study of User Trust and Team Performance When Using LLM Agents As A Daily Assistant | 实证研究计划 - 执行模式下用户对 LLM 日常助理的信任与绩效。 | 解决用户在日常任务中对 LLM 计划信任校准及协作效率问题。 | 日常任务助理、人机协作 |
| 3 | http://arxiv.org/abs/2502.02863v2 | OceanChat: The Effect of Virtual Conversational AI Agents on Sustainable Attitude and Behavior Change | 创建海洋生物对话代理，通过个性化对话促进环保行为改变。 | 解决传统环境教育难以将意识转化为持续行为改变问题。 | 环境教育、可持续行为引导 |
| 4 | http://arxiv.org/abs/2502.02911v1 | The Benefits of Prosociality towards AI Agents: Examining the Effects of Helping AI Agents on Human Well-Being | 实证研究帮助 AI 代理对人类幸福感的影响及心理需求满足。 | 解决人机互动中亲社会行为对人类福祉影响机制不明问题。 | 人机交互心理学、用户福祉 |
| 5 | http://arxiv.org/abs/2503.16432v1 | Multimodal Transformer Models for Turn-taking Prediction: Effects on Conversational Dynamics of Human-Agent Interaction during Cooperative Gameplay | 多模态 Transformer 预测轮换，提升人机对话流畅度与自然性。 | 解决合作游戏中人机对话轮换不自然及交互质量低问题。 | 游戏人机交互、对话系统 |
| 6 | http://arxiv.org/abs/2502.03788v2 | Frontend Diffusion: Empowering Self-Representation of Junior Researchers and Designers Through Multi-agent System | 多代理编码系统将布局与提示转化为网站代码，赋能自我表达。 | 解决初级研究人员构建专业身份网站困难及技术支持缺乏问题。 | 网页设计、个人品牌构建 |
| 7 | http://arxiv.org/abs/2502.06152v6 | Explaining and Improving Information Complementarities in Multi-Agent Decision-making | 提出决策理论框架及 ILIV-SHAP 解释技术，优化人机信息互补。 | 解决人机配对决策中如何利用互补信息及策略提升性能问题。 | 人机协作决策、可解释 AI |
| 8 | http://arxiv.org/abs/2502.06994v2 | SyncMind: Measuring Agent Out-of-Sync Recovery in Collaborative Software Engineering | 定义协同软件工程中的 out-of-sync 问题及基准，评估恢复能力。 | 解决协作环境中智能体理解与环境状态 diverge 导致集成失败问题。 | 协同软件工程、人机协作 |
| 9 | http://arxiv.org/abs/2502.10088v1 | Enhancing Patient Acceptance of Robotic Ultrasound through Conversational Virtual Agent and Immersive Visualizations | 结合LLM对话代理与混合现实可视化提升患者信任 | 机器人医疗诊断中患者接受度与信任度不足 | 自主医疗程序中的患者交互与体验优化 |
| 10 | http://arxiv.org/abs/2502.10978v2 | Agentic LLM Framework for Adaptive Decision Discourse | 模拟多元利益相关者角色进行权衡探索的自治理对话框架 | 复杂系统决策中多视角合成与不确定性下的策略制定 | 洪水响应等高利益相关者决策场景的数字化辅助 |
| 11 | http://arxiv.org/abs/2502.14892v1 | EgoSpeak: Learning When to Speak for Egocentric Conversational Agents in the Wild | EgoSpeak从第一人称视角建模对话，集成四维能力实现实时语音发起预测 | 真实环境中对话智能体难以判断何时发起语音交互的时机选择 | 开放世界中的第一人称视角人机自然对话 |
| 12 | http://arxiv.org/abs/2502.11843v1 | Can LLM Agents Maintain a Persona in Discourse? | 双视角评估框架分析LLM在成对对话中保持OCEAN人格特质的一致性 | 上下文切换导致LLM对话缺乏稳定可解释的人格对齐交互 | 教育、法律、医疗等需要人格一致性的人机对话应用 |
| 13 | http://arxiv.org/abs/2502.11882v5 | Leveraging Dual Process Theory in Language Agent Framework for Real-time Simultaneous Human-AI Collaboration | DPT-Agent整合System 1 FSM快速决策与System 2 ToM异步推理实现实时协作 | 基于回合的LLM智能体难以处理需实时交互的同时性人机协作任务 | 实时人机协作场景中的低延迟自主决策与意图推断 |
| 14 | http://arxiv.org/abs/2502.08114v2 | From Clicks to Conversations: Evaluating the Effectiveness of Conversational Agents in Statistical Analysis | 评估对话智能体在统计分析中相比 GUI 软件的有效性及用户体验。 | 解决非专业用户进行统计分析认知负荷高及学习曲线陡问题。 | 数据分析、人机交互 |
| 15 | http://arxiv.org/abs/2502.09369v1 | Language Agents as Digital Representatives in Collective Decision-Making | 训练语言智能体作为人类代表参与集体决策，表达个人偏好。 | 解决集体决策中人类偏好代理及多智能体场景研究困难问题。 | 集体决策、数字代表 |
| 16 | http://arxiv.org/abs/2502.09787v2 | TableTalk: Scaffolding Spreadsheet Development with a Language Agent | 语言智能体引导结构化计划，生成电子表格组件辅助编程。 | 解决电子表格编程挑战及非程序员构建复杂任务困难问题。 | 电子表格开发、终端用户编程 |
| 17 | http://arxiv.org/abs/2502.14000v1 | Human-Artificial Interaction in the Age of Agentic AI: A System-Theoretical Approach | 区分 MAS 与 Centaurian 系统，形式化人机协作通信空间 | 解决异构 Agent 与人类协调通信缺乏理论框架问题 | 人机协作与混合智能系统 |
| 18 | http://arxiv.org/abs/2502.14171v5 | Enhancing Conversational Agents with Theory of Mind: Aligning Beliefs, Desires, and Intentions for Human-Like Interaction | 显式操纵 ToM 组件（信念、欲望、意图）提升响应一致性 | 解决当前 LLM 系统缺乏 Theory of Mind 对齐能力的问题 | 类人交互对话 Agent |
| 19 | http://arxiv.org/abs/2502.18881v2 | Letters from Future Self: Augmenting the Letter-Exchange Exercise with LLM-based Agents to Enhance Young Adults' Career Exploration | 集成 LLM 智能体模拟未来自我，增强信件交换练习的参与度 | 解决年轻人职业探索中缺乏结构化指导及干预采用率低的问题 | 年轻人职业探索干预 |
| 20 | http://arxiv.org/abs/2503.16465v3 | OS-Kairos: Adaptive Interaction for MLLM-Powered GUI Agents | 预测交互步骤置信度，决定自主行动或寻求人工干预，实现自适应协作 | 解决 GUI 智能体过度执行及复杂场景下缺乏自适应人机协作的问题 | 多模态大模型驱动的 GUI 智能体 |
| 21 | http://arxiv.org/abs/2502.20513v1 | Personas Evolved: Designing Ethical LLM-Based Conversational Agent Personalities | 促进跨学科对话，探讨负责任设计及评估 LLM 基于 persona 的最佳实践 | 解决 LLM 基于 persona 的快速采用引发的伦理及实际担忧 | LLM 基于对话用户界面 persona 设计 |
| 22 | http://arxiv.org/abs/2502.20990v1 | The Impact of Navigation on Proxemics in an Immersive Virtual Environment with Conversational Agents | 测量 teleportation 与 walking 对与 embodied conversational agents 人际距离影响 | 解决社交 VR 中 locomotion 方法对空间感知及社会动态影响未探索问题 | 沉浸式虚拟环境中的对话智能体交互 |
| 23 | http://arxiv.org/abs/2502.21300v1 | Hybrid Team Tetris: A New Platform For Hybrid Multi-Agent, Multi-Human Teaming | outline 开放共享研究平台，创建在未来条件下功能的混合团队智能体 | 克服混合智能研究中人类与机器学科壁垒及未来条件未知挑战 | 混合多智能体多人团队协作研究 |
| 24 | http://arxiv.org/abs/2502.17960v1 | Advising Agent for Supporting Human-Multi-Drone Team Collaboration | 基于少量人类演示生成类人轨迹提供情境建议 | 人类操作多无人机系统实时决策复杂易次优 | 搜救任务人机多无人机协作 |
| 25 | http://arxiv.org/abs/2502.18145v2 | Carbon and Silicon, Coexist or Compete? A Survey on Human-AI Interactions in Agent-based Modeling and Simulation | 提出五维分类法系统化人机交互模式 | ABMS中人机交互缺乏系统综述 | 基于智能体的建模仿真研究 |
| 26 | http://arxiv.org/abs/2502.18201v1 | Intersubjective Model of AI-mediated Communication: Augmenting Human-Human Text Chat through LLM-based Adaptive Agent Pair | 提出主体间模型，LLM智能体实时动态塑造消息 | 传统通信模型未充分利用LLM主动转换能力 | 人机文本聊天增强 |
| 27 | http://arxiv.org/abs/2502.15948v1 | Likable or Intelligent? Comparing Social Robots and Virtual Agents for Long-term Health Monitoring | 比较社交机器人与虚拟Agent在老年人健康监测中的印象差异 | 长期真实世界研究中社交机器人与VA接口比较研究匮乏 | 老年人长期健康监测 |
| 28 | http://arxiv.org/abs/2502.16376v1 | Does Your AI Agent Get You? A Personalizable Framework for Approximating Human Models from Argumentation-based Dialogue Traces | Persona框架，结合前景理论与贝叶斯信念更新动态学习人类模型 | 可解释AI依赖预设人类模型，缺乏交互中动态学习更新能力 | 基于论证的人机交互解释 |

[返回目录](#目录)

<a id="cat-09"></a>

## Agent仿真与社会模拟

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2502.01450v1 | Simulating Rumor Spreading in Social Networks using LLM Agents | 设计多种 LLM 智能体类型模拟社交网络谣言传播动态。 | 解决传统模型难以真实模拟谣言传播中个体行为差异问题。 | 社交网络分析、 misinformation 研究 |
| 2 | http://arxiv.org/abs/2502.02780v1 | Classroom Simulacra: Building Contextual Student Generative Agents in Online Education for Learning Behavioral Simulation | 提出转移迭代反思模块，增强 LLM 模拟学生学习行为准确性。 | 解决现有学生模拟忽略课程材料调节效应及长文本处理限制问题。 | 在线教育、学习行为仿真 |
| 3 | http://arxiv.org/abs/2502.03191v4 | Cooperative Behavior in Pre-State Societies: An Agent-Based Approach of the Aksum Civilization | 基于代理建模测试阿克苏姆文明早期合作行为及权威作用。 | 解决前国家社会结构及合作可持续性演化路径不明问题。 | 历史社会学模拟、文明演化 |
| 4 | http://arxiv.org/abs/2502.04038v1 | Simulating the Emergence of Differential Case Marking with Communicating Neural-Network Agents | 神经代理框架模拟语言演化，验证沟通对语法标记涌现作用。 | 解决人工语言学习中学习与沟通效应 disentangle 困难问题。 | 语言演化模拟、计算语言学 |
| 5 | http://arxiv.org/abs/2502.06882v1 | Multi-Agent Simulator Drives Language Models for Legal Intensive Interaction | 引入多智能体法律模拟驱动器，规模化生成交互式法律数据。 | 解决法律智能场景数据稀缺及 LLM 交互式法律推理评估难问题。 | 法律智能、合成数据生成 |
| 6 | http://arxiv.org/abs/2502.05632v1 | Amorphous Fortress Online: Collaboratively Designing Open-Ended Multi-Agent AI and Game Environments | 提供 Web 平台设计多智能体 AI 及游戏环境，支持 emergent 行为。 | 解决多智能体交互环境设计门槛高及 emergent 行为观察难问题。 | 游戏开发、人工生命模拟 |
| 7 | http://arxiv.org/abs/2502.05718v1 | Using agent-based models and EXplainable Artificial Intelligence (XAI) to simulate social behaviors and policy intervention scenarios: A case study of private well users in Ireland | 结合 ABM 与 XAI 模拟政策干预，分析私人井测试行为影响因素。 | 解决公共卫生政策中环境及认知因素影响行为模拟难问题。 | 公共卫生政策、社会行为模拟 |
| 8 | http://arxiv.org/abs/2502.05919v1 | Can Generative Agent-Based Modeling Replicate the Friendship Paradox in Social Media Simulations? | 验证生成式智能体建模能否在社交媒体模拟中复现友谊悖论。 | 解决生成式智能体模拟全局网络动态及社会现象能力未探索问题。 | 社交媒体模拟、社会科学研究 |
| 9 | http://arxiv.org/abs/2502.06636v1 | Enhancing healthcare infrastructure resilience through agent-based simulation methods | 探索基于智能体仿真模型，评估医疗基础设施风险及弹性对策。 | 解决关键基础设施系统复杂性及风险情景模拟评估困难问题。 | 医疗基础设施、弹性评估 |
| 10 | http://arxiv.org/abs/2502.13160v3 | Attention Mechanism for LLM-based Agents Dynamic Diffusion under Information Asymmetry | 动态注意力机制帮助智能体在信息不对称下分配关注与社交关系建模 | 现有社会仿真忽略信息不透明、关系可变性与扩散多样性 | 多智能体信息传播与社会资本演化的仿真研究 |
| 11 | http://arxiv.org/abs/2502.11197v1 | CSP: A Simulator For Multi-Agent Ranking Competitions | 利用LLM作为文档作者的可配置排名竞争模拟器，支持大规模可扩展实验 | 人类参与者排名竞争研究的可扩展性限制与LLM生成内容的影响 | 搜索引擎排名博弈与生成式内容生态研究 |
| 12 | http://arxiv.org/abs/2502.11649v3 | Competing LLM Agents in a Non-Cooperative Game of Opinion Polarisation | 整合确认偏误、资源约束与影响惩罚的非合作博弈框架模拟意见极化 | 意见形成中确认偏误、资源优化与虚假信息传播的交互影响 | 社交媒体环境下的群体意见动力学与极化机制研究 |
| 13 | http://arxiv.org/abs/2502.07443v1 | Approximating Human Strategic Reasoning with LLM-Enhanced Recursive Reasoners Leveraging Multi-agent Hypergames | 构建基于超博弈模型的递归推理框架，评估 LLM 战略推理能力。 | 解决现有 LLM 智能体代理概念弱及架构简化导致推理评估不准问题。 | 博弈论模拟、战略推理评估 |
| 14 | http://arxiv.org/abs/2502.08691v1 | AgentSociety: Large-Scale Simulation of LLM-Driven Generative Agents Advances Understanding of Human Behaviors and Society | 大规模社会模拟器集成 LLM 智能体及环境，模拟百万级交互。 | 解决传统实验成本高及缺乏可扩展社会动态计算方法问题。 | 社会科学模拟、人类行为研究 |
| 15 | http://arxiv.org/abs/2502.12450v1 | Investigating and Extending Homans' Social Exchange Theory with Large Language Model based Agents | 构建虚拟社会验证 Homans 社会交换理论，扩展传统理论 | 解决社会科学仿真缺乏 realism 或控制成本高的问题 | 社会科学与人类行为模拟 |
| 16 | http://arxiv.org/abs/2502.12504v1 | Simulating Cooperative Prosocial Behavior with Multi-Agent LLMs: Evidence and Mechanisms for AI Agents to Inform Policy Decisions | 复现公共物品博弈实验，模拟人类亲社会合作行为 | 解决政策设计中难以预测人类复杂行为 implications 的问题 | 公共政策与社会行为模拟 |
| 17 | http://arxiv.org/abs/2502.13135v3 | Sleepless Nights, Sugary Days: Creating Synthetic Users with Health Conditions for Realistic Coaching Agent Interactions | 生成基于健康条件的合成用户，评估 coaching Agent 交互 | 解决健康 coaching Agent 缺乏真实用户交互评估数据问题 | 健康生活方式 coaching |
| 18 | http://arxiv.org/abs/2502.15800v3 | LLM Agents Do Not Replicate Human Market Traders: Evidence From Experimental Finance | 发现 LLM 表现理性，未复现人类市场泡沫行为 | 解决依赖 LLM 数据复制人类驱动市场现象的风险问题 | 实验金融与市场模拟 |
| 19 | http://arxiv.org/abs/2502.13778v1 | Poster: SpiderSim: Multi-Agent Driven Theoretical Cybersecurity Simulation for Industrial Digitalization | 多 Agent 协作自动生成安全场景，支持工业数字化研究 | 解决网络安全仿真场景多样性不足与创建效率低问题 | 工业数字化安全仿真 |
| 20 | http://arxiv.org/abs/2502.19098v1 | Language-Driven Opinion Dynamics in Agent-Based Simulations with LLMs | 提出语言驱动意见动态模型 (LODAS)，模拟辩论中语言与谬误对意见演化影响 | 探索语言及论证谬误在社会系统意见演化中的作用 | 基于 LLM 智能体的社会动态仿真 |
| 21 | http://arxiv.org/abs/2502.19550v1 | Advancing calibration for stochastic agent-based models in epidemiology with Stein variational inference and Gaussian process surrogates | 利用 Stein 变分推断与高斯过程代理优化流行病学随机 ABM 校准 | 解决高参数化流行病学 ABM 校准计算成本高及不可行问题 | 流行病学随机智能体模型校准 |
| 22 | http://arxiv.org/abs/2502.20432v3 | LLM Strategic Reasoning: Agentic Study through Behavioral Game Theory | 基于行为博弈论评估框架，disentangling 推理能力与上下文效应 | 解决现有 LLM 评估忽视战略选择机制及 demographic 偏见影响 | 大语言模型战略推理能力评估 |
| 23 | http://arxiv.org/abs/2502.20859v2 | The Power of Personality: A Human Simulation Perspective to Investigate Large Language Model Agents | 通过人类模拟视角，分配大五人格特质调查 LLM 智能体智力表现 | 填补 LLM 能力解释与现实世界人类智力缺乏联系的空白 | 大语言模型智能体的人类模拟研究 |
| 24 | http://arxiv.org/abs/2502.21037v2 | The amplifier effect of artificial agents in social contagion | 发现人工智能体导致更快更广的社会传染，采用阈值低于人类 | 理解人机交互对社会中新思想、产品及行为传播的后果 | 社会传染中的人工智能体影响 |
| 25 | http://arxiv.org/abs/2502.17705v1 | Homophilic Effects on Economic Inequality: A Dynamic Network Agent-Based Model | 模拟动态网络中同质性对财富交易与不平等的影响 | 同质性如何影响经济不平等机制不明 | 经济不平等社会模拟 |
| 26 | http://arxiv.org/abs/2502.18138v1 | Large Language Model Driven Agents for Simulating Echo Chamber Formation | LLM驱动意见更新与网络重连行为模拟回音室 | 传统规则模拟缺乏真实交互细微差别 | 社交媒体回音室形成模拟 |
| 27 | http://arxiv.org/abs/2502.18712v1 | TrajLLM: A Modular LLM-Enhanced Agent-Based Framework for Realistic Human Trajectory Simulation | 分层框架整合人生成、活动选择、目的地预测 | 传统人类移动模拟成本高、隐私 concerns | 城市规划、交通管理、公共卫生 |
| 28 | http://arxiv.org/abs/2502.14706v3 | Building reliable sim driving agents by scaling self-play | 通过大规模自博弈训练可靠仿真驾驶Agent，99.8%目标完成率 | 仿真Agent行为可靠性不足导致实验信号噪声比失真问题 | 自动驾驶系统仿真测试 |

[返回目录](#目录)

<a id="cat-10"></a>

## Agent学习与自进化

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2502.01562v2 | Memento No More: Coaching AI Agents to Master Multiple Tasks via Hints Internalization | 通过提示内化训练智能体掌握多任务，无需庞大笔记系统。 | 解决 LLM 智能体依赖外部提示无法内化知识及技能问题。 | 多任务智能体、持续学习 |
| 2 | http://arxiv.org/abs/2502.01600v3 | Reinforcement Learning for Long-Horizon Interactive LLM Agents | 提出 LOOP 算法，直接在目标环境中训练交互式数字智能体。 | 解决指令微调 LLM 在状态ful 环境中长程任务完成率低问题。 | 交互式数字助理、API 调用 |
| 3 | http://arxiv.org/abs/2502.02534v2 | Adaptive Self-improvement LLM Agentic System for ML Library Development | 引入自适应自我改进智能体系统生成架构特定 ML 库代码。 | 解决 LLM 在缺乏示例的架构特定语言编程中推理困难问题。 | ML 库开发、代码生成 |
| 4 | http://arxiv.org/abs/2502.02982v2 | MobileA3gent: Training Mobile GUI Agents Using Decentralized Self-Sourced Data from Diverse Users | 去中心化框架利用用户自源数据训练移动 GUI 代理，保护隐私。 | 解决移动代理训练数据成本高及分布式数据隐私利用问题。 | 移动应用自动化、联邦学习 |
| 5 | http://arxiv.org/abs/2502.04306v1 | ScoreFlow: Mastering LLM Agent Workflows via Score-based Preference Optimization | 基于分数偏好优化框架，连续空间梯度优化代理工作流。 | 解决离散优化技术灵活性差及代理工作流扩展性不足问题。 | LLM 代理工作流优化、自动化 |
| 6 | http://arxiv.org/abs/2502.04780v1 | SiriuS: Self-improving Multi-agent Systems via Bootstrapped Reasoning | 自改进框架构建经验库，优化多智能体系统推理及谈判能力。 | 解决多智能体系统依赖脆弱手动提示及训练数据获取困难问题。 | 多智能体自改进、推理优化 |
| 7 | http://arxiv.org/abs/2502.05907v2 | EvoAgent: Self-evolving Agent with Continual World Model for Long-Horizon Tasks | 提出持续世界模型及自我进化机制，自主更新多模态经验池。 | 解决长程任务中依赖人类数据及新任务灾难性遗忘问题。 | 开放世界任务、自我进化智能体 |
| 8 | http://arxiv.org/abs/2502.06589v1 | Hephaestus: Improving Fundamental Agent Capabilities of Large Language Models through Continual Pre-Training | 构建大规模智能体导向预训练语料，增强 API 调用及规划能力。 | 解决 LLM 智能体缺乏导向预训练数据及依赖复杂提示问题。 | 大模型预训练、基础智能体能力 |
| 9 | http://arxiv.org/abs/2502.06776v2 | InSTA: Towards Internet-Scale Training For Agents | 开发流水线利用 LLM 自动标注及过滤轨迹，实现互联网规模训练。 | 解决网页导航智能体训练依赖低效人类演示数据及标注成本问题。 | 网页导航智能体、大规模训练 |
| 10 | http://arxiv.org/abs/2502.10325v1 | Process Reward Models for LLM Agents: Practical Framework and Directions | AgentPRM采用轻量actor-critic范式与蒙特卡洛滚动优化过程奖励 | LLM智能体通过交互持续改进的奖励信号设计难题 | 需要多步交互与过程监督的复杂任务智能体训练 |
| 11 | http://arxiv.org/abs/2502.11435v2 | SMART: Self-Aware Agent for Tool Overuse Mitigation | SMART通过元认知启发增强智能体自我感知，动态平衡参数知识与工具调用 | LLM智能体缺乏自我意识导致工具过度使用增加计算开销 | 需要高效推理与工具调用的复杂任务智能体优化 |
| 12 | http://arxiv.org/abs/2502.11537v3 | Uncovering Untapped Potential in Sample-Efficient World Model Agents | Simulus集成多模态tokenization、内在动机、优先回放与回归分类提升样本效率 | 基于令牌的世界模型受限于视觉输入与离散动作的适用性 | 规划免的世界模型智能体的样本高效强化学习 |
| 13 | http://arxiv.org/abs/2502.07709v3 | MAGELLAN: Metacognitive predictions of learning progress guide autotelic LLM agents in large goal spaces | 元认知框架让 LLM 智能体在线预测能力和学习进度，优化目标优先。 | 解决开放目标空间中 LLM 智能体学习进度预测及课程扩展问题。 | 开放世界学习、自主智能体 |
| 14 | http://arxiv.org/abs/2502.07942v2 | Symbiotic Cooperation for Web Agents: Harnessing Complementary Strengths of Large and Small LLMs | 迭代框架耦合数据合成与任务性能，实现大小模型共生改进。 | 解决网页智能体中大小模型能力互补及蒸馏偏差问题。 | 网页自动化、模型蒸馏 |
| 15 | http://arxiv.org/abs/2502.07949v2 | Advancing Autonomous VLM Agents via Variational Subgoal-Conditioned Reinforcement Learning | 变分子目标条件强化学习框架，优化 VLM 智能体长程决策效率。 | 解决 VLM 智能体在稀疏奖励及长程依赖任务中学习低效问题。 | 视觉语言智能体、机器人控制 |
| 16 | http://arxiv.org/abs/2502.09051v1 | AIDE: Agentically Improve Visual Language Model with Domain Experts | 利用领域专家模型自主增强 VLM 能力，无需更大模型或人工监督。 | 解决 VLM 增强依赖知识蒸馏及缺乏 superior 模型瓶颈问题。 | 视觉语言模型、自改进 |
| 17 | http://arxiv.org/abs/2502.15760v1 | Digi-Q: Learning Q-Value Functions for Training Device-Control Agents | 训练 VLM 动作价值 Q 函数，利用离线 TD 学习提取策略。 | 解决动态环境中 on-policy RL 交互成本高及数据效率低问题。 | 设备控制智能体、移动自动化 |
| 18 | http://arxiv.org/abs/2502.12494v1 | EDGE: Efficient Data Selection for LLM Agents via Guideline Effectiveness | 提出指南有效性指标，无需黄金答案即可选择信息量样本 | 解决 Agent 微调与提示工程中数据质量低效问题 | LLM Agent 数据选择与优化 |
| 19 | http://arxiv.org/abs/2502.12876v1 | Continuous Learning Conversational AI: A Personalized Agent Framework via A2C Reinforcement Learning | 结合 RL 与 LLM，通过连续学习优化对话策略实现个性化 | 解决静态 LLM 无法适应个性化对话演进的问题 | 个性化对话伴侣 |
| 20 | http://arxiv.org/abs/2502.13957v2 | RAG-Gym: Systematic Optimization of Language Agents for Retrieval-Augmented Generation | 系统探索提示、Actor 调优与 Critic 训练三维优化 RAG Agent | 解决 Agentic RAG 依赖临时提示工程缺乏统一优化框架问题 | 检索增强生成 Agent 优化 |
| 21 | http://arxiv.org/abs/2502.18906v1 | VEM: Environment-Free Exploration for Training GUI Agent with Value Environment Model | 提出无环境 RL 框架，利用价值环境模型解耦价值估计与策略优化 | 解决 GUI 智能体训练中环境交互成本高及分布偏移问题 | 图形用户界面 (GUI) 智能体训练 |
| 22 | http://arxiv.org/abs/2502.19328v1 | Agentic Reward Modeling: Integrating Human Preferences with Verifiable Correctness Signals for Reliable Reward Systems | 提出智能体奖励建模，结合人类偏好与可验证正确性信号提供可靠奖励 | 解决现有奖励模型忽视可验证正确性信号导致可靠性不足的问题 | 大语言模型训练与推理时的奖励系统 |
| 23 | http://arxiv.org/abs/2502.19545v2 | Winning Big with Small Models: Knowledge Distillation vs. Self-Training for Reducing Hallucination in Product QA Agents | 比较自训练与知识蒸馏，发现自训练在减少幻觉方面表现相当且成本低 | 解决客服部署中 LLM 幻觉及专有模型成本高的问题 | 产品问答智能体 |
| 24 | http://arxiv.org/abs/2502.21229v1 | A Method of Selective Attention for Reservoir Based Agents | 高维掩码模块加速策略训练，比层归一化方法快两倍 | 解决不有用输入维度条件化奖励函数导致深度强化学习智能体训练慢问题 | 基于储备池的智能体训练 |
| 25 | http://arxiv.org/abs/2502.17110v3 | Mobile-Agent-V: A Video-Guided Approach for Effortless and Efficient Operational Knowledge Injection in Mobile Automation | 从视频内容自动提取操作知识注入智能体 | 手动编写操作知识负担重、效率低 | 移动设备自动化 |
| 26 | http://arxiv.org/abs/2502.17543v4 | Training a Generally Curious Agent | Paprika微调方法使模型在新任务上基于环境反馈自适应 | 语言模型在需战略信息收集场景表现不足 | 通用序列决策任务 |
| 27 | http://arxiv.org/abs/2502.18407v1 | AgentRM: Enhancing Agent Generalization with Reward Modeling | 微调奖励模型指导策略模型比直接微调更鲁棒 | LLM智能体对未见任务泛化能力差 | 通用智能体任务泛化 |
| 28 | http://arxiv.org/abs/2502.14276v2 | STeCa: Step-level Trajectory Calibration for LLM Agent Learning | 步级轨迹校准框架，通过LLM驱动反思构建校准轨迹进行强化训练 | 长周期任务中次优动作累积导致偏离正确轨迹的问题 | LLM智能体复杂任务学习 |
| 29 | http://arxiv.org/abs/2502.14496v3 | Advancing Language Multi-Agent Learning with Credit Re-Assignment for Interactive Environment Generalization | 多Agent信用重分配策略，用LLM分配过程奖励而非环境特定奖励 | 多Agent系统跨环境泛化能力不足及预定义角色限制问题 | 移动操作、网页浏览等交互环境 |
| 30 | http://arxiv.org/abs/2502.14693v5 | I-MCTS: Enhancing Agentic AutoML via Introspective Monte Carlo Tree Search | 内省蒙特卡洛树搜索，迭代分析父子节点解并LLM价值模型评估 | AutoML中代码生成多样性低及标量值反馈机制局限问题 | 自动化机器学习任务 |
| 31 | http://arxiv.org/abs/2502.15538v3 | SOTOPIA-Ω: Dynamic Strategy Injection Learning and Social Instruction Following Evaluation for Social Agents | 动态注入多步推理策略，自动化构建高质量社交对话训练语料 | 人类社交策略向Agent迁移与整合研究匮乏 | 社交语言Agent能力增强 |
| 32 | http://arxiv.org/abs/2502.15676v3 | AutoToM: Scaling Model-based Mental Inference via Automated Agent Modeling | 自动化Agent建模方法，基于贝叶斯逆规划迭代优化心智模型 | 现有ToM方法或依赖LLM提示易错，或手工模型泛化差 | 社会智能Agent心智推理 |
| 33 | http://arxiv.org/abs/2502.16536v1 | Bounded Foresight Equilibrium in Large Dynamic Economies with Heterogeneous Agents and Aggregate Shocks | N-BFE均衡概念，Agent优化无限视野但仅预测未来N期关键变量 | 异质Agent动态经济均衡分析计算复杂，存在维度灾难 | 大型动态经济系统建模 |

[返回目录](#目录)

<a id="cat-11"></a>

## Agent记忆与知识管理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2502.01630v2 | TReMu: Towards Neuro-Symbolic Temporal Reasoning for LLM-Agents with Memory in Multi-Session Dialogues | 结合时间感知记忆与神经符号推理增强多会话对话 temporal reasoning。 | 解决多会话对话中时间推理挑战及记忆检索困难问题。 | 多轮对话系统、时间推理 |
| 2 | http://arxiv.org/abs/2502.03283v2 | SymAgent: A Neural-Symbolic Self-Learning Agent Framework for Complex Reasoning over Knowledge Graphs | 神经符号框架将 KG 视为动态环境，自我学习推理轨迹。 | 解决 LLM 推理幻觉及 KG 不完全性导致复杂推理错误问题。 | 知识图谱推理、复杂问答 |
| 3 | http://arxiv.org/abs/2502.05453v1 | LLM-Powered Decentralized Generative Agents with Adaptive Hierarchical Knowledge Graph for Cooperative Planning | 提出分层知识图谱记忆系统及结构化通信协议优化协作。 | 解决动态开放世界场景中多智能体长期协作规划困难问题。 | 开放世界游戏、多智能体协作 |
| 4 | http://arxiv.org/abs/2502.05589v3 | On Memory Construction and Retrieval for Personalized Conversational Agents | 提出段级记忆构建及压缩去噪方法，提升长对话检索 accuracy。 | 解决长程对话中记忆单元粒度不当及检索内容语义质量低问题。 | 个性化对话系统、长程记忆 |
| 5 | http://arxiv.org/abs/2502.05887v1 | MTPChat: A Multimodal Time-Aware Persona Dataset for Conversational Agents | 构建多模态时间感知人设数据集，评估模型理解隐式时间线索能力。 | 解决人设对话中时间动态理解数据稀缺及复杂性不足问题。 | 对话系统、时间感知记忆 |
| 6 | http://arxiv.org/abs/2502.06472v2 | KARMA: Leveraging Multi-Agent LLMs for Automated Knowledge Graph Enrichment | 利用九协作智能体自动化分析非结构化文本 enrich 知识图谱。 | 解决手动维护知识图谱难以扩展及科学文献快速增长问题。 | 知识图谱构建、科学文献分析 |
| 7 | http://arxiv.org/abs/2502.06975v1 | Position: Episodic Memory is the Missing Piece for Long-Term LLM Agents | 论证情景记忆对长期 LLM 智能体必要性，提出五属性框架。 | 解决长期 LLM 智能体持续学习及长程知识保留挑战问题。 | 长期智能体、记忆机制研究 |
| 8 | http://arxiv.org/abs/2502.10177v2 | STMA: A Spatio-Temporal Memory Agent for Long-Horizon Embodied Task Planning | 整合时空记忆模块、动态知识图与规划器-评论家机制提升长时程规划 | 具身智能体在动态环境中长时程任务的记忆与适应挑战 | 复杂环境下的多步具身任务规划与执行 |
| 9 | http://arxiv.org/abs/2502.12110v11 | A-MEM: Agentic Memory for LLM Agents | A-MEM基于Zettelkasten原则动态构建互联知识网络，支持记忆演化与上下文更新 | 现有记忆系统缺乏复杂组织与跨任务适应性限制历史经验利用 | 需要长期经验积累与知识复用的复杂真实世界任务智能体 |
| 10 | http://arxiv.org/abs/2502.08599v1 | SPeCtrum: A Grounded Framework for Multidimensional Identity Representation in LLM-Based Agent | 整合社会、个人身份及生活背景构建真实 LLM 智能体人设。 | 解决现有身份模拟 oversimplify 人类复杂性及表示扁平化问题。 | 角色扮演、个性化智能体 |
| 11 | http://arxiv.org/abs/2503.00238v1 | Passage Query Methods for Retrieval and Reranking in Conversational Agents | 扩展 Generate-Retrieve-Generate 管道，开发 passage queries 对齐文档格式 | 解决对话信息寻求系统中跨领域及对话轮次理解上下文与检索相关文档挑战 | 对话信息寻求系统 |
| 12 | http://arxiv.org/abs/2502.18017v2 | ViDoRAG: Visual Document Retrieval-Augmented Generation via Dynamic Iterative Reasoning Agents | GMM混合检索策略与迭代智能体工作流含探索反思 | 视觉文档RAG难以整合文本视觉特征、推理token不足 | 视觉丰富文档理解与检索 |
| 13 | http://arxiv.org/abs/2502.15920v2 | Self-Taught Agentic Long Context Understanding | 链式澄清(CoC)机制，通过自生成澄清问题与上下文定位增强理解 | 复杂长上下文问题需有效问题澄清与上下文检索的挑战 | 长上下文问答任务 |

[返回目录](#目录)

<a id="cat-12"></a>

## Agent规划与推理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2502.01956v3 | DHP: Discrete Hierarchical Planning for Hierarchical Reinforcement Learning Agents | 提出 DHP 方法，用离散可达性检查替代连续距离估计。 | 解决 HRL 智能体长程视觉规划依赖易错距离度量问题。 | 分层强化学习、导航规划 |
| 2 | http://arxiv.org/abs/2502.02561v1 | Decision Theoretic Foundations for Conformal Prediction: Optimal Uncertainty Quantification for Risk-Averse Agents | 建立决策理论基础，连接预测集不确定性量化与风险规避决策。 | 解决风险敏感领域中预测不确定性如何指导下游行动问题。 | 医疗诊断、推荐系统决策 |
| 3 | http://arxiv.org/abs/2502.02584v1 | QLASS: Boosting Language Agent Inference via Q-Guided Stepwise Search | 提出 QLASS，通过逐步估计 Q 值自动生成注释指导推理。 | 解决缺乏中间交互注释导致语言智能体策略次优问题。 | 复杂交互式任务、推理优化 |
| 4 | http://arxiv.org/abs/2502.04644v2 | Agentic Reasoning: A Streamlined Framework for Enhancing LLM Reasoning with Agentic Tools | 集成外部工具代理增强 LLM 推理，构建思维导图跟踪逻辑。 | 解决复杂问题深研中 LLM 长推理链 coherence 及工具使用低效问题。 | 复杂推理、研究辅助 |
| 5 | http://arxiv.org/abs/2502.10352v1 | Agentic Verification for Ambiguous Query Disambiguation | VERDICT统一多样化与验证阶段，早期融合检索器与生成器反馈 | RAG中模糊查询的多解释生成与噪声过滤效率问题 | 企业级知识库检索与可验证答案生成 |
| 6 | http://arxiv.org/abs/2502.11418v2 | TimeCAP: Learning to Contextualize, Augment, and Predict Time Series Events with Large Language Model Agents | TimeCAP双LLM智能体分别生成时序上下文摘要与增强预测，多模态编码器协同 | 时序事件预测中缺乏上下文信息导致准确性与可靠性不足 | 气候、医疗、金融等领域的时序事件预测与决策 |
| 7 | http://arxiv.org/abs/2502.12094v1 | A Study on Leveraging Search and Self-Feedback for Agent Reasoning | 系统研究搜索算法中地面真实反馈与自反馈在数学推理与工具调用任务中的差异 | 仅依赖自反馈的搜索方法在复杂任务中泛化能力不足的挑战 | 需要多步推理与工具调用的复杂任务智能体规划优化 |
| 8 | http://arxiv.org/abs/2502.08235v1 | The Danger of Overthinking: Examining the Reasoning-Action Dilemma in Agentic Tasks | 分析 LLM 智能体过度推理现象，提出框架评估推理 - 行动困境。 | 解决交互环境中模型偏好内部推理链导致性能下降及成本增加问题。 | 智能体任务执行、推理优化 |
| 9 | http://arxiv.org/abs/2502.08950v1 | Single-Agent Planning in a Multi-Agent System: A Unified Framework for Type-Based Planners | 统一框架解决多智能体环境中单智能体利用与探索权衡问题。 | 解决无对手先验信息下多智能体环境单智能体规划困难问题。 | 多智能体路径规划、博弈 |
| 10 | http://arxiv.org/abs/2502.12130v1 | Scaling Autonomous Agents via Automatic Reward Modeling And Planning | 自动从环境学习奖励模型，无需人工标注即可评估轨迹 | 解决多步决策数据稀缺与 API 模型微调困难问题 | 通用任务规划与决策 |
| 11 | http://arxiv.org/abs/2502.13025v1 | Agentic Deep Graph Reasoning Yields Self-Organizing Knowledge Networks | 推理原生 LLM 与图表示耦合，迭代结构化知识形成自组织网络 | 解决静态知识提取无法形成开放连贯知识结构问题 | 科学发现与知识合成 |
| 12 | http://arxiv.org/abs/2502.18822v1 | Data-Efficient Multi-Agent Spatial Planning with LLMs | 利用 LLM 世界知识进行多智能体空间规划，零样本表现强，微调后交互少 | 多智能体决策中如何高效利用预训练 LLM 世界知识进行学习 | 出租车路由与分配问题 |
| 13 | http://arxiv.org/abs/2502.19135v1 | A Temporal Planning Framework for Multi-Agent Systems via LLM-Aided Knowledge Base Management | 集成 LLM 与 Prolog 知识库管理，生成行为树用于多机器人任务规划 | 处理多机器人任务中的时间依赖、资源约束及并行执行规划 | 面向任务导向机器人的多智能体系统 |
| 14 | http://arxiv.org/abs/2502.19610v3 | Program Synthesis Dialog Agents for Interactive Decision-Making | 利用程序合成辅助决策，将对话规划映射为代码生成问题 | 解决语言模型在交互式资格决策中幻觉及准确性与问题数量权衡 | 交互式决策对话智能体 |
| 15 | http://arxiv.org/abs/2503.00074v1 | CAMETA: Conflict-Aware Multi-Agent Estimated Time of Arrival Prediction for Mobile Robots | 提出冲突感知多智能体 ETA 预测框架，利用异构图神经网络 | 解决无预设道路基础设施环境下多智能体到达时间预测与路径选择 | 移动机器人多智能体到达时间预测 |
| 16 | http://arxiv.org/abs/2502.20369v1 | Multi-Agent Path Planning in Complex Environments using Gaussian Belief Propagation with Global Path Finding | 结合高斯信念传播与路径积分，引入跟踪因子确保全局路径 adherance | 解决复杂环境中多智能体导航碰撞避免及旅行效率优化问题 | 复杂环境多智能体路径规划 |
| 17 | http://arxiv.org/abs/2502.21087v1 | PASemiQA: Plan-Assisted Agent for Question Answering on Semi-Structured Data with Text and Relational Information | 联合利用文本与关系信息，生成计划遍历半结构化数据提取必要信息 | 解决现有 RAG 方法无法很好处理含文本与关系信息的半结构化数据问题 | 半结构化数据上的问答智能体 |
| 18 | http://arxiv.org/abs/2502.17189v2 | IGDA: Interactive Graph Discovery through Large Language Model Agents | LLM不确定性驱动的边实验选择与局部图更新策略 | 变量关系图发现需大量实验、成本高 | 因果图发现、蛋白质转录因子分析 |
| 19 | http://arxiv.org/abs/2502.14563v1 | Plan-over-Graph: Towards Parallelable LLM Agent Schedule | 将任务分解为可执行子任务并构建抽象任务图，支持并行执行 | LLM任务规划中并行调度能力未充分探索的问题 | 复杂可扩展任务的并行执行 |
| 20 | http://arxiv.org/abs/2502.16111v1 | PlanGEN: A Multi-Agent Framework for Generating Planning and Reasoning Trajectories for Complex Problem Solving | 约束/验证/选择三Agent，约束引导迭代验证及自适应算法选择 | 现有方法任务级验证不考虑约束或推理算法不适应实例复杂度 | 复杂规划与推理问题 |

[返回目录](#目录)

<a id="cat-13"></a>

## 多Agent协作与通信

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2502.02311v2 | MAGNNET: Multi-Agent Graph Neural Network-based Efficient Task Allocation for Autonomous Vehicles with Deep Reinforcement Learning | 集成 GNN 与 CTDE 范式实现异构多智能体去中心化任务分配。 | 解决通信受限下异构多智能体系统去中心化任务分配问题。 | 自动驾驶、无人机协同 |
| 2 | http://arxiv.org/abs/2502.03450v2 | Schema-Guided Scene-Graph Reasoning based on Multi-Agent Large Language Model System | 模式引导场景图推理框架，多代理迭代协作查询与检索。 | 解决 LLM 处理全图数据易幻觉及推理检索协作低效问题。 | 场景图推理、空间规划 |
| 3 | http://arxiv.org/abs/2502.03845v1 | PAGNet: Pluggable Adaptive Generative Networks for Information Completion in Multi-Agent Communication | 可插拔生成网络合成全局状态表示，增强 MARL 通信决策。 | 解决部分可观测任务中代理忽略多消息聚合及策略学习低效问题。 | 多智能体通信、协作决策 |
| 4 | http://arxiv.org/abs/2502.07165v1 | "Don't Just Demo, Teach Me the Principles: A Principle-Based Multi-Agent Prompting Strategy for Text Classification" | 提出基于原则的多智能体提示策略，生成高质量分类原则。 | 解决文本分类中依赖演示数据及人类 crafted 原则质量不稳定问题。 | 文本分类、多智能体提示 |
| 5 | http://arxiv.org/abs/2502.10148v2 | Cooperative Multi-Agent Planning with Adaptive Skill Synthesis | COMPASS整合VLM、动态技能库与结构化通信实现分散式闭环决策 | 多智能体强化学习在样本效率、可解释性与迁移性上的挑战 | 部分可观测下的多智能体协作任务规划 |
| 6 | http://arxiv.org/abs/2502.10705v1 | CoPEFT: Fast Adaptation Framework for Multi-Agent Collaborative Perception with Parameter-Efficient Fine-Tuning | CoPEFT通过协作适配器与智能体提示实现宏微观双层级快速适应 | 协作感知模型在新交通场景下数据分布不一致的鲁棒性 | 资源受限的多智能体感知系统快速部署 |
| 7 | http://arxiv.org/abs/2502.10775v1 | Towards Cloud-Native Agentic Protocol Learning for Conflict-Free 6G: A Case Study on Inter-Slice Resource Allocation | 云原生架构下多切片智能体通过涌现通信自主协调资源分配 | 6G网络中异构切片共享基础设施的冲突避免与动态优化 | 云原生6G网络切片资源管理 |
| 8 | http://arxiv.org/abs/2502.10857v1 | Divergent Thoughts toward One Goal: LLM-based Multi-Agent Collaboration System for Electronic Design Automation | EDAid多智能体系统通过分歧思维汇聚与ChipLlama专家模型保障流程稳定 | LLM在复杂EDA工具链中接口多样与长链调用易错问题 | 电子设计自动化流程的可靠自动化 |
| 9 | http://arxiv.org/abs/2502.10931v2 | D-CIPHER: Dynamic Collaborative Intelligent Multi-Agent System with Planner and Heterogeneous Executors for Offensive Security | Planner-Executor异构智能体架构+动态反馈+Auto-prompter提升CTF求解 | 单智能体系统在复杂网络安全任务中推理与反馈受限 | 自动化渗透测试与CTF挑战的智能辅助 |
| 10 | http://arxiv.org/abs/2502.11098v1 | Talk Structurally, Act Hierarchically: A Collaborative Framework for LLM Multi-Agent Systems | TalkHier引入结构化通信协议与分层精炼系统解决协作中的错误传播 | 多智能体协作中上下文丰富交换与输出纠错的机制缺失 | 开放域问答、专业问答与广告文本生成等复杂协作任务 |
| 11 | http://arxiv.org/abs/2502.11133v1 | MasRouter: Learning to Route LLMs for Multi-Agent Systems | MasRouter通过级联控制器网络实现协作模式、角色分配与LLM路由联合优化 | 多智能体系统中动态LLM选择与协作模式决策的成本与效率平衡 | 主流MAS框架的即插即用式路由优化 |
| 12 | http://arxiv.org/abs/2502.13164v1 | Multi-Agent Actor-Critic Generative AI for Query Resolution and Analysis | MASQRAD采用Actor-Critic多智能体辩论机制将模糊查询转化为精准可视化 | 现有方案处理用户查询歧义与生成可操作洞察的能力不足 | 需要快速精准数据解读的业务分析与决策支持场景 |
| 13 | http://arxiv.org/abs/2502.11518v1 | Generative Multi-Agent Collaboration in Embodied AI: A Systematic Review | 系统梳理生成式基础模型如何增强具身多智能体系统的感知规划通信反馈 | 具身多智能体系统在真实世界复杂挑战中的协作能力与适应性 | 物流、机器人等物理与虚拟场景的生成式多智能体协作 |
| 14 | http://arxiv.org/abs/2502.11785v2 | Changing the Rules of the Game: Reasoning about Dynamic Phenomena in Multi-Agent Systems | LAMB逻辑扩展ATL支持多智能体系统模型变更的动态推理与综合 | 多智能体系统结构修改对规范满足与策略能力影响的验证难题 | 多智能体系统的规范更新、机制设计等动态演化场景 |
| 15 | http://arxiv.org/abs/2502.11799v3 | Table-Critic: A Multi-Agent Framework for Collaborative Criticism and Refinement in Table Reasoning | Table-Critic四智能体协作+自进化模板树实现表格推理的错误识别与迭代修正 | 表格推理中多步过程的一致性维护与中间错误级联传播 | 复杂表格数据的理解、推理与问答任务 |
| 16 | http://arxiv.org/abs/2502.07350v2 | KABB: Knowledge-Aware Bayesian Bandits for Dynamic Expert Coordination in Multi-Agent Systems | 提出知识感知贝叶斯_bandits_框架，动态协调多智能体专家选择。 | 解决多智能体系统中静态知识假设及协调效率低问题。 | 多智能体专家协调系统 |
| 17 | http://arxiv.org/abs/2502.07487v1 | Multi-Agent Collaboration for Multilingual Code Instruction Tuning | 多语言特定智能体协作框架，利用生成记忆跨语言迁移代码知识。 | 解决代码大模型多语言指令调优中知识孤立及迁移效率低问题。 | 代码生成、多语言模型调优 |
| 18 | http://arxiv.org/abs/2502.08514v2 | Faithful, Unfaithful or Ambiguous? Multi-Agent Debate with Initial Stance for Summary Evaluation | 多智能体辩论框架分配初始立场，识别摘要忠实性及歧义。 | 解决 LLM 评估易被流畅性误导及难以识别错误问题。 | 文本摘要评估、多智能体辩论 |
| 19 | http://arxiv.org/abs/2502.12149v2 | HARBOR: Exploring Persona Dynamics in Multi-Agent Competition | 探究竞争环境中 Persona 对 Agent 行为及策略的影响 | 解决多 Agent 拍卖竞争中的行为建模与优势策略问题 | 多 Agent 拍卖竞争环境 |
| 20 | http://arxiv.org/abs/2502.12328v1 | LM Agents for Coordinating Multi-User Information Gathering | 引入 PeopleJoin 基准，评估 Agent 协调多用户信息收集能力 | 解决分布式信息场景下的协作问题求解与总结任务 | 多用户协作信息收集 |
| 21 | http://arxiv.org/abs/2502.13001v2 | You need to MIMIC to get FAME: Solving Meeting Transcript Scarcity with a Multi-Agent Conversations | 多 Agent 辩论生成会议记录，解决数据稀缺问题 | 解决会议总结缺乏高质量隐私合规数据的问题 | 会议记录生成与总结 |
| 22 | http://arxiv.org/abs/2502.14112v1 | To Stand on the Shoulders of Giants: Should We Protect Initial Discoveries in Multi-Agent Exploration? | 博弈论分析知识保护与共享对多 Agent 探索投资的影响 | 解决研发竞争环境中如何激励初始探索与知识共享问题 | 多 Agent 探索与研发博弈 |
| 23 | http://arxiv.org/abs/2502.19130v4 | Voting or Consensus? Decision-Making in Multi-Agent Debate | 系统评估 7 种决策协议，提出全智能体起草与集体改进新方法 | 解决多智能体辩论中决策协议对任务性能影响不明及多样性不足问题 | 多智能体辩论系统中的决策机制 |
| 24 | http://arxiv.org/abs/2502.19559v2 | Stay Focused: Problem Drift in Multi-Agent Debate | 定义问题漂移现象，提出 DRIFTJudge 检测与 DRIFTPolicy 缓解方法 | 解决多智能体辩论多轮交互中偏离初始问题导致性能下降问题 | 多智能体辩论系统 |
| 25 | http://arxiv.org/abs/2502.19592v2 | RAMEN: Real-time Asynchronous Multi-agent Neural Implicit Mapping | 提出实时异步多智能体神经隐式映射，利用不确定性加权共识优化 | 解决带宽有限及通信中断下的多机器人协作环境重建问题 | 多机器人协作环境映射 |
| 26 | http://arxiv.org/abs/2502.19917v1 | Picking the Cream of the Crop: Visual-Centric Data Selection with Collaborative Agents | 提出视觉中心选择方法，通过智能体协作评估图像质量与指令相关性 | 解决多模态大模型训练数据中指令 - 图像错位及低质量图像问题 | 多模态大模型视觉指令微调数据选择 |
| 27 | http://arxiv.org/abs/2502.16565v2 | The Hidden Strength of Disagreement: Unraveling the Consensus-Diversity Tradeoff in Adaptive Multi-Agent Systems | 提出隐式共识机制，保留部分多样性以提升系统探索能力 | 多智能体系统过早同质化导致探索能力不足 | 动态灾难响应、信息传播、公共物品供给 |
| 28 | http://arxiv.org/abs/2502.16863v1 | Leveraging Large Language Models for Effective and Explainable Multi-Agent Credit Assignment | 利用LLM作为奖励评论家进行多智能体信用分配 | 多智能体强化学习中个体贡献评估困难 | 多机器人协作、自动驾驶协调 |
| 29 | http://arxiv.org/abs/2502.17821v3 | CAML: Collaborative Auxiliary Modality Learning for Multi-Agent Systems | 训练时共享多模态数据，测试时允许模态减少推理 | 资源受限环境推理时模态缺失导致决策盲区 | 联网自动驾驶车辆协作 |
| 30 | http://arxiv.org/abs/2502.18438v2 | ToMCAT: Theory-of-Mind for Cooperative Agents in Teams via Multiagent Diffusion Policies | 结合元学习心智推理与多智能体扩散模型生成计划 | 团队智能体需动态适应队友行为与目标 | 模拟烹饪领域团队协作 |
| 31 | http://arxiv.org/abs/2502.18439v2 | MAPoRL: Multi-Agent Post-Co-Training for Collaborative Large Language Models with Reinforcement Learning | 多LLM共同后训练，通过多轮讨论协作改进答案 | 单独训练LLM无法诱导有效协作行为 | 协作多智能体LLM框架 |
| 32 | http://arxiv.org/abs/2502.14321v2 | Beyond Self-Talk: A Communication-Centric Survey of LLM-Based Multi-Agent Systems | 以通信为中心的多Agent系统综述框架，整合系统级与内部通信维度 | 现有综述忽略通信在协调Agent行为中核心作用的问题 | LLM多Agent系统研究者与从业者 |
| 33 | http://arxiv.org/abs/2502.14743v2 | Multi-Agent Coordination across Diverse Applications: A Survey | 统一框架回答协调四问题(是什么/为什么/与谁/如何)，覆盖多应用领域 | 多Agent协调研究分散，缺乏跨应用统一理解 | 搜索救援、物流、交通、LLM等多领域 |
| 34 | http://arxiv.org/abs/2502.14796v1 | A Multi-Agent Perspective on Modern Information Retrieval | 倡导多Agent视角捕捉查询/文档/排序Agent间复杂交互 | 传统IR范式无法适应LLM生成查询与文档的新挑战 | 现代信息检索系统 |
| 35 | http://arxiv.org/abs/2502.15153v2 | When Disagreements Elicit Robustness: Investigating Self-Repair Capabilities under LLM Multi-Agent Disagreements | 研究分歧对集体决策影响，发现一般分歧促进探索、关键分歧影响因任务而异 | 多Agent系统中分歧如何影响集体决策机制不明确 | 协作推理与协作编程任务 |
| 36 | http://arxiv.org/abs/2502.15972v1 | Multi-Agent Multimodal Models for Multicultural Text to Image Generation | MosAIG框架，利用不同文化人格的LLM增强跨文化图像生成 | 现有数据与模型以西方为中心，跨文化语境效果有限 | 跨文化多模态图像生成 |
| 37 | http://arxiv.org/abs/2502.16131v1 | Urban Emergency Rescue Based on Multi-Agent Collaborative Learning: Coordination Between Fire Engines and Traffic Lights | 集成协作学习技术到Unity引擎，支持消防车与交通灯灵活协调 | 城市应急救援中多部门智能协调实现高效调度至关重要 | 城市应急救援仿真 |

[返回目录](#目录)

<a id="cat-14"></a>

## Agent工具使用与环境交互

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2502.02955v1 | ReachAgent: Enhancing Mobile Agent via Page Reaching and Operation | 两阶段框架聚焦页面到达与操作子任务，提升移动代理完成率。 | 解决移动代理忽略整体 GUI 流导致局部最优及任务失败问题。 | 移动设备自动化、GUI 交互 |
| 2 | http://arxiv.org/abs/2502.06787v2 | Visual Agentic AI for Spatial Reasoning with a Dynamic API | 提出智能体程序合成方法，协作生成动态 API 解决 3D 空间推理。 | 解决视觉语言模型在 3D 空间推理中依赖静态 API 及性能下降问题。 | 3D 空间理解、视觉推理 |
| 3 | http://arxiv.org/abs/2502.11271v1 | OctoTools: An Agentic Framework with Extensible Tools for Complex Reasoning | OctoTools提供标准化工具卡、规划器与执行器的免训练可扩展框架 | 现有工具增强方法受限于领域、工具类型或需额外训练数据 | 跨领域复杂推理任务的多工具协同调用 |
| 4 | http://arxiv.org/abs/2502.11357v4 | Explorer: Scaling Exploration-driven Web Trajectory Synthesis for Multimodal Web Agents | 通过大规模网络探索与精炼合成94K+多模态Web轨迹数据集训练Explorer | 开源多模态Web智能体缺乏多样化大规模轨迹数据导致在线性能不足 | 真实在线环境中的复杂Web任务自主完成 |
| 5 | http://arxiv.org/abs/2502.11705v2 | LLM Agents Making Agent Tools | ToolMaker自主将带代码的论文转化为LLM兼容工具，闭环自校正调试 | 专业领域需要大量专用工具但人工预实现阻碍LLM智能体应用 | 生命科学、医学等需要大量专业计算工具的自动化科研工作流 |
| 6 | http://arxiv.org/abs/2502.08226v2 | TRISHUL: Towards Region Identification and Screen Hierarchy Understanding for Large VLM based GUI Agents | 训练免费框架集成层级解析与空间增强描述，提升 GUI 理解。 | 解决跨平台 GUI 智能体动作定位及元素描述泛化性差问题。 | GUI 自动化、视觉语言模型 |
| 7 | http://arxiv.org/abs/2502.08557v3 | A New Query Expansion Approach via Agent-Mediated Dialogic Inquiry | 多智能体对话探究框架，通过苏格拉底式提问扩展查询表示。 | 解决 LLM 查询扩展同质化及缺乏多样化上下文问题。 | 信息检索、查询扩展 |
| 8 | http://arxiv.org/abs/2502.09858v1 | Automated Hypothesis Validation with Agentic Sequential Falsifications | 智能体框架设计执行证伪实验，自动化验证自由形式假设。 | 解决 LLM 生成假设幻觉及手动验证不切实际问题。 | 科学研究、假设验证 |
| 9 | http://arxiv.org/abs/2502.12280v1 | Connecting Large Language Model Agent to High Performance Computing Resource | 实现 LangChain 与 Parsl 集成，桥接 LLM 与高性能计算资源 | 解决科学领域大规模计算资源访问与并行执行问题 | 科学计算与模拟任务 |
| 10 | http://arxiv.org/abs/2502.14327v1 | ChemHTS: Hierarchical Tool Stacking for Enhancing Chemical Agents | 分层工具堆叠策略，含工具自堆叠预热与多层决策优化两阶段 | 化学领域工具调用错误及多样工具间缺乏有效协作问题 | 化学研究任务（分子设计、反应预测等） |

[返回目录](#目录)

<a id="cat-15"></a>

## 低代码/无代码Agent平台

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2502.04103v2 | VTutor: An Open-Source SDK for Generative AI-Powered Animated Pedagogical Agents with Multi-Media Output | 开源 SDK 结合生成 AI 与动画技术，创建多模态教学代理。 | 解决教学代理交互单一及开发门槛高缺乏多模态输出问题。 | 教育技术、教学代理开发 |
| 2 | http://arxiv.org/abs/2502.05957v3 | AutoAgent: A Fully-Automated and Zero-Code Framework for LLM Agents | 构建全自动零代码框架，仅用自然语言创建部署 LLM 智能体。 | 解决非技术人员构建 LLM 智能体门槛高及编程技能缺乏问题。 | 通用 AI 助手、智能体开发平台 |

[返回目录](#目录)

