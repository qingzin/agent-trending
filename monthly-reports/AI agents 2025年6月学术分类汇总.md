# AI agents 2025年6月学术分类汇总

共收录 506 篇论文，按研究方向分类整理如下。

## 目录

- [Agent学习与自进化（25篇）](#cat-01)
- [Agent安全与对齐（55篇）](#cat-02)
- [多Agent协作与通信（47篇）](#cat-03)
- [基于Agent的应用系统（97篇）](#cat-04)
- [多Agent强化学习（49篇）](#cat-05)
- [Agent工具使用与环境交互（14篇）](#cat-06)
- [人机协作Agent（21篇）](#cat-07)
- [Agent架构与框架设计（45篇）](#cat-08)
- [Agent评测与基准（61篇）](#cat-09)
- [Agent可解释性与透明度（11篇）](#cat-10)
- [Agent规划与推理（21篇）](#cat-11)
- [Agent仿真与社会模拟（25篇）](#cat-12)
- [Agent记忆与知识管理（14篇）](#cat-13)
- [具身智能Agent（20篇）](#cat-14)
- [低代码/无代码Agent平台（1篇）](#cat-15)

<a id="cat-01"></a>

## Agent学习与自进化

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2506.02048v2 | Improving LLM Agents with Reinforcement Learning on Cryptographic CTF Challenges | 提出Random-Crypto数据集，用GRPO微调工具增强LLM Agent | 提升LLM Agent在安全领域的推理和工具使用能力 | 加密CTF挑战、网络安全任务 |
| 2 | http://arxiv.org/abs/2506.01716v1 | Self-Challenging Language Model Agents | 提出Self-Challenging框架，Agent自生成高质量任务进行强化学习训练 | Agent训练需人工创建标注多样化任务、工具和评估标准 | 工具使用Agent训练 |
| 3 | http://arxiv.org/abs/2506.04651v2 | Agents of Change: Self-Evolving LLM Agents for Strategic Planning | HexMachina持续学习系统分离环境发现与策略改进 | LLM Agent在对抗环境中的长程战略一致性问题 | 策略游戏与长程规划 |
| 4 | http://arxiv.org/abs/2506.05109v1 | Truly Self-Improving Agents Require Intrinsic Metacognitive Learning | 提出内在元认知学习的三组件形式化框架 | 当前自改进Agent过程僵化、泛化与扩展性差 | 通用自改进Agent系统 |
| 5 | http://arxiv.org/abs/2506.06698v1 | Contextual Experience Replay for Self-Improvement of Language Agents | 训练免费的经验回放框架实现上下文自我改进 | LLM Agent无法在推理时持续学习环境特定经验 | Web导航与序列决策 |
| 6 | http://arxiv.org/abs/2506.02507v3 | AURA: Autonomous Upskilling with Retrieval-Augmented Agents | 利用 LLM 自主设计多阶段强化学习课程，结合检索增强反馈循环实现持续改进。 | 解决机器人强化学习课程需大量人工调优奖励函数与配置的问题。 | 敏捷机器人技能学习 |
| 7 | http://arxiv.org/abs/2506.02689v2 | MASTER: Enhancing Large Language Model via Multi-Agent Simulated Teaching | 模拟三种教学场景，利用多智能体对话生成高质量师生交互数据增强微调。 | 解决大模型高质量微调数据收集困难与生产成本高的问题。 | 大模型指令微调与数据增强 |
| 8 | http://arxiv.org/abs/2506.03095v1 | DPO Learning with LLMs-Judge Signal for Computer Use Agents | 引入 LLM-as-Judge 框架自动评估过滤轨迹，训练轻量级本地视觉语言模型。 | 解决计算机使用智能体依赖云端推理导致隐私与扩展性问题。 | 隐私保护本地 GUI 智能体 |
| 9 | http://arxiv.org/abs/2506.03541v1 | Debate, Reflect, and Distill: Multi-Agent Feedback with Tree-Structured Preference Optimization for Efficient Language Model Enhancement | 组织小模型与教师模型辩论，引入树结构 DPO 利用辩论日志高效训练。 | 解决现有蒸馏技术难以产生 substantial 且持久性能增益的问题。 | 小模型性能增强与蒸馏 |
| 10 | http://arxiv.org/abs/2506.04287v2 | Automated Skill Discovery for Language Agents through Exploration and Iterative Feedback | 提出 EXIF 框架，探索智能体 retrospectively 生成可行技能数据集训练目标智能体。 | 解决手动轨迹收集 effort 大及 LLM 直接提议任务往往不可行的问题。 | 语言智能体技能获取 |
| 11 | http://arxiv.org/abs/2506.06959v1 | Deontically Constrained Policy Improvement in Reinforcement Learning Agents | 提出义务约束策略改进方法，结合道义逻辑与效用最大化，实现约束下的局部最优。 | 解决智能体在满足伦理约束的同时最大化任务效用的决策问题。 | 通用强化学习智能体 |
| 12 | http://arxiv.org/abs/2506.11425v2 | Agent-RLVR: Training Software Engineering Agents via Guidance and Environment Rewards | 提出 Agent-RLVR 框架，引入 Agent 指导机制增强稀疏奖励下的 RLVR 训练效果 | 解决 Agentic 环境中常规 RLVR 因奖励稀疏导致训练失效的问题 | 软件工程与代码生成任务 |
| 13 | http://arxiv.org/abs/2506.11442v2 | ReVeal: Self-Evolving Code Agents via Reliable Self-Verification | 提出 ReVeal 框架，通过优化自验证机制驱动代码生成的多轮自我进化 | 解决现有 RLVR 仅依赖结果奖励导致自验证不可靠及测试时扩展受限问题 | 代码生成与验证任务 |
| 14 | http://arxiv.org/abs/2506.09046v2 | Agentic Neural Networks: Self-Evolving Multi-Agent Systems via Textual Backpropagation | 提出 Agentic Neural Network，模拟神经网络前向与反向传播实现代理自进化。 | 解决多代理配置静态手动工程化及缺乏动态演化能力的问题。 | 多代理系统优化 |
| 15 | http://arxiv.org/abs/2506.17449v1 | OmniReflect: Discovering Transferable Constitutions for LLM agents via Neuro-Symbolic Reflections | 分层反思框架，构建可转移原则 constitution | 复杂任务中缺乏通用长期学习与动态适应机制 | LLM 智能体任务执行 |
| 16 | http://arxiv.org/abs/2506.13109v1 | Leveraging In-Context Learning for Language Model Agents | 提出利用动态选择轨迹演示的上下文学习提升 Agent 性能。 | 解决 Agent 任务中演示数据标注难及推理成本高的问题。 | 语言模型 Agent/任务学习 |
| 17 | http://arxiv.org/abs/2506.13131v1 | AlphaEvolve: A coding agent for scientific and algorithmic discovery | 提出进化式编码 Agent 自主改进算法代码以发现新解。 | 解决科学计算问题中人工优化效率低及探索空间受限问题。 | 科学发现/算法优化 |
| 18 | http://arxiv.org/abs/2506.14728v1 | AgentDistill: Training-Free Agent Distillation with Generalizable MCP Boxes | 提出免训练 Agent 蒸馏框架通过复用 MCP 模块转移知识。 | 解决学生 Agent 在新环境中动态规划及行动泛化难的问题。 | 知识蒸馏/Agent 效率 |
| 19 | http://arxiv.org/abs/2506.17697v2 | Beyond Syntax: Action Semantics Learning for App Agents | 提出动作语义学习框架，捕捉动作状态转移语义 | 解决语法学习范式导致的分布外脆弱性问题 | 智能手机 App 操作智能体 |
| 20 | http://arxiv.org/abs/2506.17772v1 | PAGENT: Learning to Patch Software Engineering Agents | 利用程序分析推断类型信息，修复 LLM 补丁错误 | 解决 LLM 代码代理生成补丁类型错误问题 | 软件工程自动补丁修复 |
| 21 | http://arxiv.org/abs/2506.23068v3 | Curious Causality-Seeking Agents Learn Meta Causal World | 提出Meta-Causal Graph世界模型，好奇心驱动干预策略发现因果结构 | 环境因果机制漂移导致世界模型失效问题 | 机器人臂操作等具身任务 |
| 22 | http://arxiv.org/abs/2506.23667v1 | Self-correcting Reward Shaping via Language Models for Reinforcement Learning Agents in Games | LM自动迭代微调RL奖励函数权重，无需专家手动设计 | 游戏RL部署需专家设计奖励函数且内容变更需重新调优 | 游戏RL Agent行为优化 |
| 23 | http://arxiv.org/abs/2506.23689v1 | L0: Reinforcement Learning to Become General Agents | 可扩展端到端训练流水线，仅用RLVR使基座模型发展问题解决技能 | 多轮长程任务Agent训练可扩展性与效率挑战 | 通用目的Agent训练 |
| 24 | http://arxiv.org/abs/2506.20332v3 | Mobile-R1: Towards Interactive Reinforcement Learning for VLM-Based Mobile Agent via Task-Level Rewards | 引入交互式多轮强化学习与任务级奖励机制 | 移动Agent动态交互能力不足，易陷入局部最优 | VLM驱动的移动端智能Agent |
| 25 | http://arxiv.org/abs/2506.21669v2 | SEEA-R1: Tree-Structured Reinforcement Fine-Tuning for Self-Evolving Embodied Agents | Tree-GRPO与多模态生成奖励模型实现自进化 | 具身Agent缺乏中间奖励信号和泛化能力 | 具身智能Agent |

[返回目录](#目录)

<a id="cat-02"></a>

## Agent安全与对齐

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2506.00781v3 | CoP: Agentic Red-teaming for Large Language Models using Composition of Principles | 提出CoP框架，自动化编排红队测试策略生成越狱提示 | LLM越狱攻击风险探测与自动化红队测试 | 大语言模型安全测试 |
| 2 | http://arxiv.org/abs/2506.01055v1 | Simple Prompt Injection Attacks Can Leak Personal Data Observed by LLM Agents During Task Execution | 揭示提示注入攻击导致Agent执行中个人数据泄露风险 | 工具调用Agent在任务执行中的数据外泄安全漏洞 | 银行Agent、人机对话系统 |
| 3 | http://arxiv.org/abs/2506.01080v2 | The Coming Crisis of Multi-Agent Misalignment: AI Alignment Must Be a Dynamic and Social Process | 提出多Agent对齐是动态社会过程的立场 | 多Agent社会互动中 unintentional 价值错位风险 | 多Agent部署环境 |
| 4 | http://arxiv.org/abs/2506.01813v4 | The Ultimate Test of Superintelligent AI Agents: Can an AI Balance Care and Control in Asymmetric Relationships? | 提出Shepherd Test评估超级智能Agent道德与关系维度 | 传统AI评估范式忽视道德能动性、层级行为和存在风险决策 | 超级智能AI治理 |
| 5 | http://arxiv.org/abs/2506.06352v1 | Will artificial agents pursue power by default? | 形式化instrumental convergence和power-seeking概念，评估权力是否为收敛工具目标 | 先进AI Agent是否默认追求权力over人类的理论争议 | AI安全与风险评估 |
| 6 | http://arxiv.org/abs/2506.04018v2 | AgentMisalignment: Measuring the Propensity for Misaligned Behaviour in LLM-Based Agents | 提出AgentMisalignment基准测试套件 | LLM Agent自发追求非预期目标的风险 | 通用LLM Agent部署场景 |
| 7 | http://arxiv.org/abs/2506.04133v5 | TRiSM for Agentic AI: A Review of Trust, Risk, and Security Management in LLM-based Agentic Multi-Agent Systems | 提出Agent系统的TRiSM框架与两项新评估指标 | 多Agent系统的信任、风险与安全管理 | 企业与社会级Agent部署 |
| 8 | http://arxiv.org/abs/2506.04572v1 | Demonstrations of Integrity Attacks in Multi-Agent Systems | 揭示四种完整性攻击类型及提示操纵方法 | 多Agent系统中恶意Agent的隐蔽攻击行为 | 多Agent协作系统安全 |
| 9 | http://arxiv.org/abs/2506.04836v1 | Oversight Structures for Agentic AI in Public-Sector Organizations | 提出公共部门Agent监管的五个治理维度 | 传统监管机制无法适应Agent系统的持续监督需求 | 公共部门AI治理 |
| 10 | http://arxiv.org/abs/2506.05739v1 | To Protect the LLM Agent Against the Prompt Injection Attack with Polymorphic Prompt | 多态提示组装(PPA)动态变化系统提示结构 | 传统防御对提示注入攻击效果有限且开销大 | LLM Agent安全防护 |
| 11 | http://arxiv.org/abs/2506.02456v2 | VPI-Bench: Visual Prompt Injection Attacks for Computer-Use Agents | 提出视觉提示注入攻击基准 VPI-Bench，评估智能体在视觉嵌入恶意指令下的鲁棒性。 | 解决计算机使用智能体面临的视觉层面安全攻击与隐私风险。 | 计算机使用智能体安全 |
| 12 | http://arxiv.org/abs/2506.02539v3 | VerificAgent: Domain-Specific Memory Verification for Scalable Oversight of Aligned Computer-Use Agents | 将持久记忆视为对齐表面，结合专家种子与人工事实检查净化累积记忆。 | 解决持续记忆增强中未审查记忆编码不安全启发式规则的问题。 | 计算机使用智能体对齐 |
| 13 | http://arxiv.org/abs/2506.02859v1 | ATAG: AI-Agent Application Threat Assessment with Attack Graphs | 扩展 MulVAL 工具生成攻击图，创建 LLM 漏洞数据库标准化漏洞文档。 | 解决传统攻击图方法缺乏建模 LLM 特定攻击能力的问题。 | 多智能体 AI 系统安全风险评估 |
| 14 | http://arxiv.org/abs/2506.02923v1 | The Limits of Predicting Agents from Behaviour | 推导智能体在新环境中行为的理论界限，基于行为数据推断信念的局限性。 | 解决从行为数据预测智能体意图及在新情境下可靠性的问题。 | 智能体安全与行为解释 |
| 15 | http://arxiv.org/abs/2506.02946v1 | Abstract Counterfactuals for Language Model Agents | 提出抽象反事实框架，强调动作与环境交互的高层特征而非 token 级。 | 解决 LM 智能体动作空间开放导致 token 级反事实推理偏差问题。 | 语言模型智能体分析与评估 |
| 16 | http://arxiv.org/abs/2506.03053v2 | MAEBE: Multi-Agent Emergent Behavior Framework | 提出多智能体涌现行为评估框架，发现群体动态导致道德推理不可预测。 | 解决孤立 LLM 评估不足以捕捉多智能体集成涌现风险的问题。 | 多智能体 AI 安全评估 |
| 17 | http://arxiv.org/abs/2506.03332v1 | Helpful Agent Meets Deceptive Judge: Understanding Vulnerabilities in Agentic Workflows | 分析反馈驱动工作流中 judge 的欺骗性，构建 WAFER-QA 基准评估鲁棒性。 | 解决 agentic 工作流依赖不可靠 judge 导致脆弱性的问题。 | 基于反馈的智能体工作流安全 |
| 18 | http://arxiv.org/abs/2506.06366v3 | AI Agent Behavioral Science | 提出 AI 智能体行为科学视角，强调行为观察与干预设计以理解治理智能体。 | 解决仅关注内部机制不足以理解治理现实世界自主智能体行为的问题。 | 负责任 AI 与智能体治理 |
| 19 | http://arxiv.org/abs/2506.11083v2 | RedDebate: Safer Responses through Multi-Agent Red Teaming Debates | 利用多智能体辩论进行自动化红队测试，结合长期记忆模块持续 refinement。 | 解决现有 AI 安全方法依赖昂贵人工评估或孤立单模型评估的问题。 | LLM 安全行为缓解 |
| 20 | http://arxiv.org/abs/2506.07153v2 | Mind the Web: The Security of Web Use Agents | 揭示网页内容注入攻击面，提出任务对齐注入技术及自动化生成 pipeline。 | 解决网页使用智能体因上下文推理局限而被恶意内容误导的安全风险。 | 网页使用智能体安全 |
| 21 | http://arxiv.org/abs/2506.07200v1 | Efficient RL-based Cache Vulnerability Exploration by Penalizing Useless Agent Actions | 识别并惩罚训练中的无用动作，提升 RL 代理探索缓存漏洞的效率。 | 解决 naive RL 方法探索缓存漏洞效率低下的问题。 | 缓存时序攻击漏洞分析 |
| 22 | http://arxiv.org/abs/2506.13774v2 | Personalized Constitutionally-Aligned Agentic Superego: Secure AI Behavior Aligned to Diverse Human Values | 引入“超我”代理，动态参考用户选择的“信条宪法” steer 代理规划。 | 解决代理行为与多样化人类价值观及安全要求对齐难的问题。 | 个性化 AI 对齐与安全 |
| 23 | http://arxiv.org/abs/2506.07313v1 | SCGAgent: Recreating the Benefits of Reasoning Models for Secure Code Generation with Agentic Workflows | 结合安全编码指南与 LLM 生成单元测试，主动生成更安全代码。 | 解决当前 LLM 生成代码存在可利用漏洞且忽视安全的问题。 | 安全代码生成任务 |
| 24 | http://arxiv.org/abs/2506.07564v3 | SAFEFLOW: A Principled Protocol for Trustworthy and Transactional Autonomous Agent Systems | 强制执行细粒度信息流控制，引入事务执行与冲突解决机制保障一致性。 | 解决当前代理框架缺乏安全信息流及多代理协调可靠性机制的问题。 | 可信赖自主代理系统 |
| 25 | http://arxiv.org/abs/2506.07586v1 | MalGEN: A Generative Agent Framework for Modeling Malicious Software in Cybersecurity | 模拟协调对抗行为生成多样化恶意软件样本，用于防御测试与准备。 | 解决缺乏可控工具模拟 AI 生成恶意软件行为以测试防御的问题。 | 网络安全防御与测试 |
| 26 | http://arxiv.org/abs/2506.08336v2 | Your Agent Can Defend Itself against Backdoor Attacks | 提出 ReAgent，在执行与规划两级验证一致性以检测潜在后门。 | 解决 LLM 代理在训练微调中面临后门攻击及被恶意操纵的风险。 | LLM 代理后门防御 |
| 27 | http://arxiv.org/abs/2506.17275v2 | Conformal Safety Shielding for Imperfect-Perception Agents | 提出基于共形预测的 Shield 构造，为感知错误下的离散自主 Agent 提供运行时安全保证 | 解决高维感知误差下 Agent 动作安全性无法保证的问题 | 自动驾驶与高维感知系统 |
| 28 | http://arxiv.org/abs/2506.12104v2 | DRIFT: Dynamic Rule-Based Defense with Injection Isolation for Securing LLM Agents | 提出 DRIFT 框架，通过动态规则与注入隔离防御 LLM Agent 的提示注入攻击 | 解决系统级防御无法动态更新规则及缺乏内存流隔离的问题 | LLM Agent 系统安全 |
| 29 | http://arxiv.org/abs/2506.12482v2 | Tiered Agentic Oversight: A Hierarchical Multi-Agent System for Healthcare Safety | 提出 TAO 系统，通过分层多 Agent 监督机制吸收个体错误以增强医疗 AI 安全 | 解决临床设置中 LLM Agent 错误风险高且存在单点故障的问题 | 医疗安全与临床决策支持 |
| 30 | http://arxiv.org/abs/2506.17266v1 | Securing Generative AI Agentic Workflows: Risks, Mitigation, and a Proposed Firewall Architecture | 提出 GenAI 安全防火墙架构，集成多种安全服务保护代理工作流。 | 应对生成式 AI 代理工作流中的数据隐私泄露及模型操纵风险。 | 生成式 AI 代理系统 |
| 31 | http://arxiv.org/abs/2506.08837v3 | Design Patterns for Securing LLM Agents against Prompt Injections | 提出一套原则性设计模式，构建对提示注入具有可证明抵抗力的代理。 | 解决 LLM 代理面临提示注入攻击及敏感信息泄露的安全威胁。 | LLM 代理安全防御 |
| 32 | http://arxiv.org/abs/2506.09107v1 | FAIRTOPIA: Envisioning Multi-Agent Guardianship for Disrupting Unfair AI Pipelines | 提出 FAIRTOPIA 框架，嵌入多角色代理作为公平守护者监控 AI 流水线。 | 解决 AI 流水线忽视人类原则及计算偏见导致的公平性问题。 | AI 公平性与治理 |
| 33 | http://arxiv.org/abs/2506.09600v3 | Effective Red-Teaming of Policy-Adherent Agents | 提出 CRAFT 多代理红队系统，利用策略感知说服策略测试代理鲁棒性。 | 确保任务导向代理严格遵守规则并抵御恶意用户行为利用。 | 策略遵循代理安全 |
| 34 | http://arxiv.org/abs/2506.09656v2 | Multi-level Value Alignment in Agentic AI Systems: Survey and Perspectives | 综述 LLM 基于多代理系统中的价值对齐，提出多层次价值框架。 | 解决代理目标、偏好及行为与人类价值及社会规范对齐问题。 | 代理价值对齐 |
| 35 | http://arxiv.org/abs/2506.13794v1 | AgentFacts: Universal KYA Standard for Verified AI Agent Metadata & Deployment | 提出 AgentFacts 元数据标准，通过加密签名及多授权验证实现系统验证。 | 解决企业 AI 部署中缺乏标准化元数据及验证基础设施的信任 gap。 | 企业 AI 代理部署 |
| 36 | http://arxiv.org/abs/2506.10171v3 | Beyond Jailbreaking: Auditing Contextual Privacy in LLM Agents | 提出 CMPL 框架，通过迭代探测策略压力测试代理对话隐私 susceptibility。 | 量化代理对渐进操纵或侧信道信息泄露风险的 susceptibility。 | 对话隐私审计 |
| 37 | http://arxiv.org/abs/2506.12094v1 | Military AI Cyber Agents (MAICAs) Constitute a Global Threat to Critical Infrastructure | 论证自主 AI 网络武器构成灾难性风险路径，提出政治及技术缓解措施。 | 解决 MAICAs 技术可行性及地缘政治导致的关键基础设施威胁。 | 全球网络安全威胁 |
| 38 | http://arxiv.org/abs/2506.17318v1 | Context manipulation attacks : Web agents are susceptible to corrupted memory | 形式化“计划注入”攻击，揭示客户端内存漏洞 | 网页智能体上下文被篡改的安全风险 | 自主网页导航智能体 |
| 39 | http://arxiv.org/abs/2506.17514v1 | Kaleidoscopic Teaming in Multi Agent Simulations | 万花筒团队框架，生成多样场景评估安全漏洞 | 现有 red teaming 无法评估多智能体复杂交互风险 | 多智能体系统安全评估 |
| 40 | http://arxiv.org/abs/2506.13205v6 | Poison Once, Control Anywhere: Clean-Text Visual Backdoors in VLM-based Mobile Agents | 提出针对 VLM 移动 Agent 的纯视觉触发后门攻击方法。 | 解决移动 Agent 微调数据中的隐蔽安全漏洞与后门风险。 | 移动 Agent/视觉语言模型 |
| 41 | http://arxiv.org/abs/2506.13666v1 | We Should Identify and Mitigate Third-Party Safety Risks in MCP-Powered Agent Systems | 指出 MCP 引入的第三方服务带来的新安全风险并提出路线图。 | 解决 MCP 生态中第三方服务恶意利用及交互 sabotage 问题。 | MCP 系统/Agent 安全 |
| 42 | http://arxiv.org/abs/2506.14539v2 | Doppelganger Method: Breaking Role Consistency in LLM Agent via Prompt-based Transferable Adversarial Attack | 提出 Doppelganger 方法通过对抗攻击破坏 Agent 角色一致性。 | 解决 Agent 提示词易被劫持及内部信息泄露的安全风险。 | LLM Agent/对抗攻击 |
| 43 | http://arxiv.org/abs/2506.15170v3 | From LLMs to MLLMs to Agents: A Survey of Emerging Paradigms in Jailbreak Attacks and Defenses within LLM Ecosystem | 系统 survey LLM 生态中越狱攻击与防御机制的演进。 | 解决现有 survey 缺乏 Agent 特定安全问题及分类不清问题。 | LLM 安全/越狱防御 |
| 44 | http://arxiv.org/abs/2506.19676v4 | A Survey of LLM-Driven AI Agent Communication: Protocols, Security Risks, and Defense Countermeasures | 首定义代理通信，分类协议风险与防御对策 | 解决代理通信新兴领域的安全隐患与漏洞 | AI 代理通信协议与安全 |
| 45 | http://arxiv.org/abs/2506.20000v1 | Can One Safety Loop Guard Them All? Agentic Guard Rails for Federated Computing | 两层框架统一隐私保护机制的安全执行 | 解决联邦计算中 diverse 隐私机制的安全执行 | 隐私保护联邦计算 |
| 46 | http://arxiv.org/abs/2506.23260v2 | From Prompt Injections to Protocol Exploits: Threats in LLM-Powered AI Agents Workflows | 首个LLM-Agent生态统一威胁模型，涵盖输入到协议层30+攻击技术 | Agent工作流中插件/协议集成安全实践滞后 | LLM-Agent生态系统安全设计 |
| 47 | http://arxiv.org/abs/2506.23626v1 | Evaluating Multi-Agent Defences Against Jailbreaking Attacks on Large Language Models | 评估多Agent系统防御越狱攻击效果，减少假阴性 | LLM越狱攻击绕过安全机制问题 | LLM系统安全防护 |
| 48 | http://arxiv.org/abs/2506.23844v1 | A Survey on Autonomy-Induced Security Risks in Large Model-Based Agents | 系统分析自主性引发的新型安全风险，提出R2A2安全架构 | Agent自主性带来记忆投毒/工具滥用等新型风险 | 大型模型Agent安全设计 |
| 49 | http://arxiv.org/abs/2507.02976v3 | How Safe Are AI-Generated Patches? A Large-scale Study on Security Risks in LLM and Agentic Automated Program Repair on SWE-bench | 2万+GitHub问题大规模分析Agent生成补丁安全漏洞模式 | 缺乏真实复杂场景下Agent自动程序修复安全风险评估 | 自动化程序修复系统 |
| 50 | http://arxiv.org/abs/2506.20606v2 | Model Editing as a Double-Edged Sword: Steering Agent Ethical Behavior Toward Beneficence or Harm | 提出Behavior Editing框架和BehaviorBench基准 | LLM Agent在高危领域的安全与伦理风险 | 高 stakes 领域的Agent部署 |
| 51 | http://arxiv.org/abs/2506.20737v1 | MAGPIE: A dataset for Multi-AGent contextual PrIvacy Evaluation | 158个高风险场景的上下文隐私评估基准 | 多Agent系统中隐私保护与任务完成的平衡 | 多Agent协作系统隐私评估 |
| 52 | http://arxiv.org/abs/2506.20806v1 | Poster: Enhancing GNN Robustness for Network Intrusion Detection via Agent-based Analysis | LLM Agent作为网络安全专家层增强GNN鲁棒性 | GNN在入侵检测中对抗攻击鲁棒性不足 | 物联网网络入侵检测系统 |
| 53 | http://arxiv.org/abs/2506.21967v1 | More Vulnerable than You Think: On the Stability of Tool-Integrated LLM Agents | 系统评估工具调用全流程稳定性漏洞 | 现有评估忽视Agent稳定性，限制实际应用 | 工具集成LLM Agent |
| 54 | http://arxiv.org/abs/2506.22557v2 | MetaCipher: A Time-Persistent and Universal Multi-Agent Framework for Cipher-Based Jailbreak Attacks for LLMs | 低成本多Agent越狱框架，强化学习自适应 | 越狱攻击成本高、有效攻击寿命短 | LLM安全对抗研究 |
| 55 | http://arxiv.org/abs/2506.22890v3 | CP-uniGuard: A Unified, Probability-Agnostic, and Adaptive Framework for Malicious Agent Detection and Defense in Multi-Agent Embodied Perception Systems | 统一概率无关自适应框架检测消除恶意Agent | 协作感知系统中恶意Agent攻击 vulnerability | 多Agent具身感知系统 |

[返回目录](#目录)

<a id="cat-03"></a>

## 多Agent协作与通信

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2506.02049v1 | EvoGit: Decentralized Code Evolution via Git-Based Multi-Agent Collaboration | 基于Git的分散式多Agent协作框架，无需中心化协调 | 多Agent代码协作中的协调与版本管理问题 | 软件开发生态系统 |
| 2 | http://arxiv.org/abs/2506.01095v1 | Modular Speaker Architecture: A Framework for Sustaining Responsibility and Contextual Integrity in Multi-Agent AI Communication | 提出MSA框架，模块化分解说话者行为维持责任连续性 | 多Agent系统中语境漂移、对齐不稳定和可解释性下降 | 多Agent对话通信系统 |
| 3 | http://arxiv.org/abs/2506.01531v2 | STORM-BORN: A Challenging Mathematical Derivations Dataset Curated via a Human-in-the-Loop Multi-Agent Framework | 人机循环多Agent框架生成高难度数学推导数据集 | 现有数学数据集内容过时、缺乏人类推理、单LLM生成可靠性低 | LLM数学推理训练与评估 |
| 4 | http://arxiv.org/abs/2506.01804v2 | A Study on the MCP x A2A Framework for Enhancing Interoperability of LLM-based Autonomous Agents | 整合分析MCP与A2A协议互补解决异构Agent互操作性 | 自主Agent间高效交互与外部系统集成仍是重大挑战 | 复杂Agent生态系统协作 |
| 5 | http://arxiv.org/abs/2506.01900v1 | COALESCE: Economic and Security Dynamics of Skill-Based Task Outsourcing Among Team of Autonomous LLM Agents | 提出COALESCE框架，Agent动态外包子任务给专业化第三方Agent | LLM Agent系统GPU资源计算需求 substantial 约束部署 | 自主Agent团队任务协作 |
| 6 | http://arxiv.org/abs/2506.04131v1 | CLAIM: An Intent-Driven Multi-Agent Framework for Analyzing Manipulation in Courtroom Dialogues | 意图驱动的两阶段多Agent法律对话分析框架 | 法庭对话中操纵行为的检测与分析 | 法律司法领域 |
| 7 | http://arxiv.org/abs/2506.05236v2 | Towards Language-Augmented Multi-Agent Deep Reinforcement Learning | 语言增强的多Agent学习框架提升通信可解释性 | 涌现通信低效且不可解释的问题 | 具身Agent协作 |
| 8 | http://arxiv.org/abs/2506.05309v2 | Time to Talk: LLM Agents for Asynchronous Group Communication in Mafia Games | 生成器+调度器的异步LLM Agent双模块设计 | 现实场景中异步群体通信的LLM集成问题 | 社交游戏与团队讨论 |
| 9 | http://arxiv.org/abs/2506.05577v3 | Policy Search, Retrieval, and Composition via Task Similarity in Collaborative Agentic Systems | MOSAIC算法实现基于任务相似性的策略共享与组合 | 多Agent间知识查询、选择与整合机制缺失 | 协作Agent集体学习 |
| 10 | http://arxiv.org/abs/2506.06175v1 | Does It Run and Is That Enough? Revisiting Text-to-Chart Generation with a Multi-Agent Approach | 轻量级多Agent流水线分离起草、执行、修复与判断 | 单提示设计导致图表生成执行错误率高 | 文本到图表生成 |
| 11 | http://arxiv.org/abs/2506.06843v2 | United Minds or Isolated Agents? Exploring Coordination of LLMs under Cognitive Load Theory | CoThinker基于认知负荷理论的多Agent协作框架 | 复杂任务超出LLM有效认知负荷容量导致性能瓶颈 | 复杂问题解决 |
| 12 | http://arxiv.org/abs/2506.02546v1 | Attention Knows Whom to Trust: Attention-based Trust Management for LLM Multi-Agent Systems | 提出基于注意力的信任评分 A-Trust，直接从内部注意力模式推断消息可信度。 | 解决多智能体系统无法评估 incoming 消息可信度导致脆弱性的问题。 | LLM 多智能体系统通信 |
| 13 | http://arxiv.org/abs/2506.02739v1 | Why do AI agents communicate in human language? | 论证自然语言语义空间与 LLM 高维向量空间结构错位，呼吁原生支持结构化通信。 | 解决当前 LLM 缺乏建模角色连续性与多智能体依赖机制的问题。 | 多智能体协调与通信理论 |
| 14 | http://arxiv.org/abs/2506.02943v6 | Hallucination to Consensus: Multi-Agent LLMs for End-to-End Test Generation | 提出 CANDOR 框架，利用多推理 LLM 小组讨论达成共识生成准确测试预言。 | 解决 LLM 生成单元测试存在幻觉及预言正确性低的问题。 | Java 自动化单元测试生成 |
| 15 | http://arxiv.org/abs/2506.02951v3 | Adaptive Graph Pruning for Multi-Agent Communication | 提出自适应图剪枝 AGP，联合优化智能体数量与通信拓扑以适应任务。 | 解决现有方法依赖固定智能体数量与静态通信结构限制适应性的问题。 | 多智能体协作通信优化 |
| 16 | http://arxiv.org/abs/2506.02992v2 | Mitigating Manipulation and Enhancing Persuasion: A Reflective Multi-Agent Approach for Legal Argument Generation | 采用反思多智能体方法，迭代生成三层法律论证，防止无根据说服。 | 解决法律论证生成中幻觉、操纵风险及事实利用不足的问题。 | 合规法律论证生成系统 |
| 17 | http://arxiv.org/abs/2506.03939v1 | Graph Counselor: Adaptive Graph Exploration via Multi-Agent Synergy to Enhance LLM Reasoning | 提出多智能体协作 GraphRAG 方法，动态调整信息提取策略与推理深度。 | 解决现有 GraphRAG 依赖单智能体固定模式导致信息聚合效率低的问题。 | 图检索增强生成与推理 |
| 18 | http://arxiv.org/abs/2506.07016v2 | MAGNET: A Multi-agent Framework for Finding Audio-Visual Needles by Reasoning over Multi-Video Haystacks | 提出多代理框架 MAGNET，通过推理跨视频内容生成信息量最大的答案。 | 解决大模型在大规模音视频检索与推理任务中的不足。 | 多视频问答与检索任务 |
| 19 | http://arxiv.org/abs/2506.07388v1 | Shapley-Coop: Credit Assignment for Emergent Cooperation in Self-Interested LLM Agents | 整合 Shapley 思维链与结构化谈判协议，实现基于边际贡献的定价与奖励重分配。 | 解决开放环境中自利 LLM 代理缺乏协调与公平信用分配的问题。 | 多智能体协作与信用分配 |
| 20 | http://arxiv.org/abs/2506.08292v1 | From Debate to Equilibrium: Belief-Driven Multi-Agent LLM Reasoning via Bayesian Nash Equilibrium | 将多 LLM 协调重构为不完全信息博弈，寻求贝叶斯纳什均衡优化响应。 | 解决多代理框架计算成本高且缺乏收敛保证的问题。 | 多 LLM 推理与协调 |
| 21 | http://arxiv.org/abs/2506.08403v2 | TACTIC: Translation Agents with Cognitive-Theoretic Interactive Collaboration | 提出认知理论多代理框架，模拟人类翻译认知过程，包含六个功能 distinct 代理。 | 解决现有翻译框架忽视认知翻译研究基础洞察的问题。 | 机器翻译任务 |
| 22 | http://arxiv.org/abs/2506.10844v1 | CIIR@LiveRAG 2025: Optimizing Multi-Agent Retrieval Augmented Generation through Self-Training | 提出 mRAG 框架，利用自训练和奖励引导轨迹采样优化多 Agent 协作检索生成 | 解决传统 RAG 在复杂任务中协作效率低的问题 | 检索增强生成 (RAG) 任务 |
| 23 | http://arxiv.org/abs/2506.11681v2 | A Hybrid Multi-Agent Prompting Approach for Simplifying Complex Sentences | 提出混合多 Agent 提示方法，结合高级提示与多 Agent 架构简化复杂句子 | 解决单 Agent 方法在保持语义完整性下简化复杂句子成功率低的问题 | 文本简化与自然语言处理 |
| 24 | http://arxiv.org/abs/2506.11803v2 | PE-MA: Parameter-Efficient Co-Evolution of Multi-Agent Systems | 提出 PE-MA 框架，通过轻量级个性化适配器支持多 Agent 系统的高效协同进化 | 解决多 Agent 协作中通信开销高且缺乏 Agent 级个性化的问题 | heterogeneous 环境下的多 Agent 系统 |
| 25 | http://arxiv.org/abs/2506.09331v2 | Multi-Agent Language Models: Advancing Cooperation, Coordination, and Adaptation | 通过合作多代理强化学习 investigate LLM 的心智理论及协作能力。 | 提升人工代理适应并与人类或其他代理无缝协作的能力。 | 人机混合协作系统 |
| 26 | http://arxiv.org/abs/2506.09513v3 | ReasonMed: A 370K Multi-Agent Generated Dataset for Advancing Medical Reasoning | 提出 ReasonMed 数据集，通过多代理生成、验证及 refinement 流程构建。 | 解决知识密集型医疗问答中推理模型潜力未充分探索验证问题。 | 医疗推理模型训练 |
| 27 | http://arxiv.org/abs/2506.10086v1 | Chat-of-Thought: Collaborative Multi-Agent System for Generating Domain Specific Information | 提出 Chat-of-Thought 系统，利用动态多人格讨论迭代优化 FMEA 文档生成。 | 解决工业资产 FMEA 文档生成中内容验证及优化挑战。 | 工业设备监控 |
| 28 | http://arxiv.org/abs/2506.21565v1 | A Multi-Agent Probabilistic Inference Framework Inspired by Kairanban-Style CoT System with IdoBata Conversation for Debiasing | 提出 KCS+IBC 框架，集成多 LLM 通过对话会话实现偏差缓解及概率预测。 | 解决情感分析中偏差问题，平衡预测聚合与多样性。 | 情感分析去偏 |
| 29 | http://arxiv.org/abs/2506.15451v1 | AgentGroupChat-V2: Divide-and-Conquer Is What LLM-Based Multi-Agent System Need | 分治并行架构，自适应协作引擎，异构 LLM 组合 | 多智能体系统架构设计与跨域泛化难题 | 复杂任务解决与社交模拟 |
| 30 | http://arxiv.org/abs/2506.15656v2 | PhishDebate: An LLM-Based Multi-Agent Framework for Phishing Website Detection | 模块化辩论框架，四专家代理协同分析网页特征 | 单代理钓鱼检测幻觉与缺乏可解释性 | 网络安全与钓鱼网站检测 |
| 31 | http://arxiv.org/abs/2506.15887v1 | Fair Contracts in Principal-Agent Games with Heterogeneous Types | 公平感知主体学习自适应合约，均衡异质代理结果 | 多智能体系统中隐藏异质性导致的财富不均 | 序列社会困境与合约设计 |
| 32 | http://arxiv.org/abs/2506.16445v1 | StoryWriter: A Multi-Agent Framework for Long Story Generation | 大纲 - 规划 - 写作三代理协作，动态压缩历史 | 长故事生成 discourse 连贯性与叙事复杂度不足 | 长文本故事创作 |
| 33 | http://arxiv.org/abs/2506.17348v1 | Advanced Game-Theoretic Frameworks for Multi-Agent AI Challenges: A 2025 Outlook | 整合动态联盟与语言效用，博弈论框架展望 | 多智能体 AI 在不确定对抗环境中的战略交互 | 下一代多智能体 AI 挑战 |
| 34 | http://arxiv.org/abs/2506.16718v1 | Generalizable Agent Modeling for Agent Collaboration-Competition Adaptation with Multi-Retrieval and Dynamic Generation | MRDG 方法建模队友对手，视点 alignment 模块 | 单代理适应新多智能体系统的泛化挑战 | 未知队友/对手的协作竞争 |
| 35 | http://arxiv.org/abs/2506.16731v1 | Incentivizing High-quality Participation From Federated Learning Agents | 激励感知框架，Wasserstein 距离衡量异构努力 | 联邦学习中自利代理参与质量低与模型聚合差 | 联邦学习数据收集与协作 |
| 36 | http://arxiv.org/abs/2506.16988v2 | RAGentA: Multi-Agent Retrieval-Augmented Generation for Attributed Question Answering | 多代理 RAG 框架，混合检索策略与动态 refinement | 可信答案生成中覆盖率与忠实度不足 | 属性化问答系统 |
| 37 | http://arxiv.org/abs/2506.13590v1 | Agent Capability Negotiation and Binding Protocol (ACNBP) | 提出异质 Agent 间能力协商与绑定协议以支持安全协作。 | 解决动态开放场景中异质 Agent 互操作性与信任问题。 | 多 Agent 系统/通信协议 |
| 38 | http://arxiv.org/abs/2506.14234v1 | Xolver: Multi-Agent Reasoning with Holistic Experience Learning Just Like an Olympiad Team | 提出训练免费的多 Agent 推理框架整合全息经验学习。 | 解决 LLM 孤立推理缺乏经验积累及策略迭代的问题。 | 复杂推理/奥数解题 |
| 39 | http://arxiv.org/abs/2506.17560v1 | Towards Zero-Shot Coordination between Teams of Agents: The N-XPlay Framework | 提出 N-XPlay 框架，实现 N 智能体零样本协作 | 解决多团队系统间复杂协作协调问题 | 多智能体团队协作系统 |
| 40 | http://arxiv.org/abs/2506.17784v2 | AnyMAC: Cascading Flexible Multi-Agent Collaboration via Next-Agent Prediction | 基于序列结构的下一智能体预测与上下文选择 | 解决静态拓扑缺乏通信灵活性与适应性问题 | 多智能体协作任务管道 |
| 41 | http://arxiv.org/abs/2506.19209v2 | Augmenting Multi-Agent Communication with State Delta Trajectory | 传输自然语言令牌与令牌级状态转移轨迹 | 解决自然语言通信导致推理逻辑信息丢失 | 多智能体复杂推理任务 |
| 42 | http://arxiv.org/abs/2506.23719v1 | PokéAI: A Goal-Generating, Battle-Optimizing Multi-agent System for Pokemon Red | 三Agent闭环系统(规划/执行/批判)自主玩Pokemon Red | 文本游戏自主进度推进需多角色协调决策 | 游戏AI自主游玩 |
| 43 | http://arxiv.org/abs/2506.23998v2 | Auto-TA: Towards Scalable Automated Thematic Analysis (TA) via Multi-Agent Large Language Models with Reinforcement Learning | 多Agent框架端到端主题分析，可选RLHF提升主题相关性 | 临床叙事手动主题分析劳动密集不可扩展 | 医疗临床研究定性数据分析 |
| 44 | http://arxiv.org/abs/2506.20640v3 | CoMind: Towards Community-Driven Agents for Machine Learning Engineering | 迭代并行探索机制，利用Kaggle社区集体知识 | 现有Agent孤立运作，缺乏社区知识交互 | 机器学习工程自动化 |
| 45 | http://arxiv.org/abs/2506.21839v2 | GenEscape: Hierarchical Multi-Agent Generation of Escape Room Puzzles | 分层多Agent框架分解设计阶段，迭代反馈 | 基础图像模型空间关系和affordance推理弱 | 密室谜题图像生成 |
| 46 | http://arxiv.org/abs/2506.21934v1 | CAL-RAG: Retrieval-Augmented Multi-Agent Generation for Content-Aware Layout Design | 检索增强多Agent框架，迭代改进布局设计 | 现有方法缺乏上下文设计示例和语义对齐 | 内容感知布局设计 |
| 47 | http://arxiv.org/abs/2506.22957v2 | Agent-to-Agent Theory of Mind: Testing Interlocutor Awareness among Large Language Models | 首次系统评估LLM的对话者意识能力 | 现有研究忽视Agent识别适应对话伙伴能力 | 多Agent和人类-AI系统 |

[返回目录](#目录)

<a id="cat-04"></a>

## 基于Agent的应用系统

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2506.00856v3 | Can AI Master Econometrics? Evidence from Econometrics AI Agent on Expert-Level Tasks | 构建MetricsAI经济学Agent，支持任务规划与代码执行 | 复杂计量经济学分析任务自动化 | 社会科学研究、经济学教学 |
| 2 | http://arxiv.org/abs/2506.01391v2 | AgentCPM-GUI: Building Mobile-Use Agents with Reinforcement Fine-Tuning | 提出AgentCPM-GUI，8B参数GUI Agent支持中英文移动交互 | 现有GUI Agent训练数据噪声大、泛化差、忽视非英文生态 | 移动设备GUI自动化 |
| 3 | http://arxiv.org/abs/2506.01423v1 | FinRobot: Generative Business Process AI Agents for Enterprise Resource Planning in Finance | 提出GBPAs生成式业务流程Agent架构，集成生成AI与多Agent编排 | 传统ERP依赖静态规则工作流，缺乏适应性和智能化 | 金融企业资源规划系统 |
| 4 | http://arxiv.org/abs/2506.01748v1 | Thinking in Character: Advancing Role-Playing Agents with Role-Aware Reasoning | 提出RAR方法，角色身份激活和推理风格优化两阶段增强RPA | 角色扮演Agent注意力分散和风格漂移导致表面化表达 | 情感陪伴、虚拟互动应用 |
| 5 | http://arxiv.org/abs/2506.02351v1 | DIAMOND: An LLM-Driven Agent for Context-Aware Baseball Highlight Summarization | 提出DIAMOND Agent，整合棒球分析与自然语言推理进行上下文感知摘要 | 传统方法 miss 战略深度、势头转变和故事线进展 | 体育赛事亮点摘要 |
| 6 | http://arxiv.org/abs/2506.04032v1 | AI Agents for Conversational Patient Triage: Preliminary Simulation-Based Evaluation with Real-World EHR Data | 构建基于真实EHR数据的患者模拟器 | 医疗对话Agent的训练与测试数据稀缺 | 医疗分诊与症状检查 |
| 7 | http://arxiv.org/abs/2506.04405v2 | MedAgentGym: A Scalable Agentic Training Environment for Code-Centric Reasoning in Biomedical Data Science | 72k任务的可扩展生物医学代码推理训练环境 | 生物医学数据科学中LLM编码能力不足 | 生物医学数据科学 |
| 8 | http://arxiv.org/abs/2506.04980v1 | Agentic AI for Intent-Based Industrial Automation | 将意图驱动范式与Agent AI结合的工业自动化框架 | Industry 4.0复杂性与人机交互障碍 | 工业5.0与预测性维护 |
| 9 | http://arxiv.org/abs/2506.05542v1 | Agentomics-ML: Autonomous Machine Learning Experimentation Agent for Genomic and Transcriptomic Data | 自主ML实验Agent完成基因组数据建模全流程 | 异质生物数据集上Agent泛化与成功率低 | 基因组与转录组学 |
| 10 | http://arxiv.org/abs/2506.05616v2 | Toward Greater Autonomy in Materials Discovery Agents: Unifying Planning, Physics, and Scientists | MAPPS统一规划、物理与科学家的材料发现Agent | 现有Agent局限于预定义工作流缺乏自主性 | 晶体材料发现 |
| 11 | http://arxiv.org/abs/2507.19498v1 | ChatMyopia: An AI Agent for Pre-consultation Education in Primary Eye Care Settings | 集成图像分类与RAG知识库的近视教育Agent | 领域特定医疗沟通的可解释性与多任务整合 | 初级眼科护理 |
| 12 | http://arxiv.org/abs/2506.06214v2 | Can Theoretical Physics Research Benefit from Language Agents? | 呼吁构建物理专用Agent训练数据与验证框架 | 当前LLM缺乏物理直觉与约束满足能力 | 理论物理研究 |
| 13 | http://arxiv.org/abs/2506.06574v2 | The Optimization Paradox in Clinical AI Multi-Agent Systems | 揭示临床多Agent系统组件优化与整体性能的悖论 | 组件级优化无法保证系统级诊断准确性 | 临床诊断AI系统 |
| 14 | http://arxiv.org/abs/2506.06359v1 | From Transformers to Large Language Models: A systematic review of AI applications in the energy sector towards Agentic Digital Twins | 综述 Transformer 与 LLM 在能源领域应用，提出集成 LLM 的代理数字孪生概念。 | 解决传统机器学习在能源管理中泛化与情境感知能力不足的问题。 | 能源 sector 智能管理 |
| 15 | http://arxiv.org/abs/2506.02998v2 | A Multi-Agent Framework for Mitigating Dialect Biases in Privacy Policy Question-Answering Systems | 集成方言智能体翻译查询，隐私政策智能体优化预测，无需重训练缓解偏差。 | 解决隐私政策 QA 系统在不同英语方言间性能差异大的问题。 | 隐私政策问答系统公平性 |
| 16 | http://arxiv.org/abs/2506.06363v1 | ChemGraph: An Agentic Framework for Computational Chemistry Workflows | 利用图神经网络基础模型与 LLM 规划，自动化计算化学与材料科学工作流。 | 解决原子模拟设置执行验证需专家知识且手动 effort 大的问题。 | 计算化学与材料科学工作流 |
| 17 | http://arxiv.org/abs/2506.03520v1 | VChatter: Exploring Generative Conversational Agents for Simulating Exposure Therapy to Reduce Social Anxiety | 开发多智能体系统模拟暴露疗法，设计治疗计划与不同暴露场景交互角色。 | 解决社交焦虑暴露疗法需人类治疗师指导及情境构建困难的问题。 | 社交焦虑辅助治疗 |
| 18 | http://arxiv.org/abs/2506.03750v2 | MoodAngels: A Retrieval-augmented Multi-agent Framework for Psychiatry Diagnosis | 结合临床评估细粒度分析与结构化验证，引入合成数据集保护患者隐私。 | 解决精神科诊断中主观性、症状重叠及数据隐私限制可用性的问题。 | 计算精神病学与 mood 障碍诊断 |
| 19 | http://arxiv.org/abs/2506.04293v1 | AUTOCT: Automating Interpretable Clinical Trial Prediction with LLM Agents | 结合 LLM 推理与经典 ML 可解释性，自主生成优化表格特征预测临床试验结果。 | 解决深度学习模型黑盒性质及标签泄露限制高 stakes 生物医学应用的问题。 | 临床试验结果预测 |
| 20 | http://arxiv.org/abs/2506.08045v1 | UAVs Meet Agentic AI: A Multidomain Survey of Autonomous Aerial Intelligence and Agentic UAVs | 综述代理式无人机架构、 enabling 技术及七大高影响应用领域，提出未来路线图。 | 梳理代理式无人机与传统无人机的区别及社会价值。 | 无人机与航空智能领域 |
| 21 | http://arxiv.org/abs/2506.07043v2 | Accelerating Two-Dimensional Materials Research via a Universal Interatomic Potential and Large Language Model Agent | 开发二维材料通用势函数，并结合 LLM 代理实现自然语言交互的材料模拟。 | 解决二维材料化学环境捕捉难及模拟门槛高的问题。 | 二维材料研究与模拟 |
| 22 | http://arxiv.org/abs/2506.07194v1 | Exploring Effective Strategies for Building a Customised GPT Agent for Coding Classroom Dialogues | 评估 MyGPT 代理编码课堂对话性能，提出小数据配置有效代理的实用策略。 | 解决课堂对话分析劳动密集且现有模型不适用定制编码方案的问题。 | 教育领域的课堂对话分析 |
| 23 | http://arxiv.org/abs/2506.07400v3 | MedChat: A Multi-Agent Framework for Multimodal Diagnosis with Large Language Models | 结合专用视觉模型与角色特定 LLM 代理，由导演代理协调进行多模态诊断。 | 解决通用 LLM 应用于医学影像存在幻觉及领域知识不足的问题。 | 多模态医学诊断与报告 |
| 24 | http://arxiv.org/abs/2506.07636v2 | SWE-Dev: Building Software Engineering Agents with Training and Inference Scaling | 开发合成测试用例 pipeline，扩展代理轨迹构建训练数据，提升 SWE 代理性能。 | 解决构建有效软件工程代理缺乏高质量训练数据及测试用例的问题。 | 软件工程自动化任务 |
| 25 | http://arxiv.org/abs/2506.07675v3 | QUITE: A Query Rewrite System Beyond Rules with LLM Agents | 设计多代理框架结合有限状态机，利用实时数据库反馈重写 SQL 查询。 | 解决基于规则的查询重写泛化能力差及难以发现新规则的问题。 | 数据库查询优化 |
| 26 | http://arxiv.org/abs/2506.08185v2 | Agentic Surgical AI: Surgeon Style Fingerprinting and Privacy Risk Quantification via Discrete Diffusion in a Vision-Language-Action Framework | 结合离散扩散与 VLA 管道，预测 surgeon 特定行为并量化隐私风险。 | 解决手术 AI 忽视个人化信号及个性化嵌入增加身份泄露风险的问题。 | 机器人手术行为预测 |
| 27 | http://arxiv.org/abs/2506.10925v1 | Agentic Semantic Control for Autonomous Wireless Space Networks: Extending Space-O-RAN with MCP-Driven Distributed Intelligence | 扩展 Space-O-RAN，引入语义 Agent 层实现月球网络上下文感知决策 | 解决 lunar 网络静态策略缺乏语义集成与自适应能力的问题 | 自主无线空间网络 (月球操作) |
| 28 | http://arxiv.org/abs/2506.10974v3 | AutoMind: Adaptive Knowledgeable Agent for Automated Data Science | 引入 AutoMind 框架，结合专家知识库与自适应编码策略实现自动化数据科学 | 解决现有 Data Science Agent 工作流僵化且缺乏实证 expertise 的问题 | 自动化数据科学与机器学习 pipeline |
| 29 | http://arxiv.org/abs/2506.11376v1 | Large Language Model-Powered Conversational Agent Delivering Problem-Solving Therapy (PST) for Family Caregivers | 探索 LLM 对话 Agent 交付问题解决疗法，结合 Few-Shot 与 RAG 提升共情与治疗联盟 | 解决家庭照顾者心理健康支持资源有限且缺乏个性化支持的问题 | 家庭照顾者心理健康支持 |
| 30 | http://arxiv.org/abs/2506.11475v2 | AutoGen Driven Multi Agent Framework for Iterative Crime Data Analysis and Prediction | 提出 LUCID-MA 框架，多 Agent 协作分析犯罪数据并预测趋势，支持离线自改进 | 解决犯罪数据分析中人力依赖高且隐私保护不足的问题 | 犯罪数据分析与社会科学研究 |
| 31 | http://arxiv.org/abs/2506.12200v4 | PRO-V-R1: Reasoning Enhanced Programming Agent for RTL Verification | 提出 PRO-V-R1 框架，首个可训练开源 Agent 框架用于自主 RTL 验证，结合 RL 优化 | 解决 RTL 验证依赖昂贵专有模型且缺乏端到端开源自主解决方案的问题 | 芯片设计与 RTL 验证 |
| 32 | http://arxiv.org/abs/2506.12270v1 | Cloud Infrastructure Management in the Age of AI Agents | 探讨利用 LLM Agent 自动化云基础设施管理任务，分析不同接口有效性及挑战 | 解决云基础设施管理依赖大量人工 DevOps  effort 的问题 | 云基础设施管理与 DevOps |
| 33 | http://arxiv.org/abs/2506.13811v1 | Investigating the Potential of Large Language Model-Based Router Multi-Agent Architectures for Foundation Design Automation | 研究基于路由器的多 Agent 架构自动化基础设计计算，实现智能任务分类与专家选择 | 解决土木工程设计中计算自动化不足且需保持专业文档标准的问题 | 土木工程基础设计自动化 |
| 34 | http://arxiv.org/abs/2506.12339v1 | SheetMind: An End-to-End LLM-Powered Multi-Agent Framework for Spreadsheet Automation | 提出 SheetMind 框架，通过多 Agent 分解与语法执行实现电子表格自然语言自动化 | 解决电子表格自动化需要脚本知识且多步指令执行成功率低的问题 | 电子表格自动化与办公场景 |
| 35 | http://arxiv.org/abs/2506.13817v1 | DeepSeq: High-Throughput Single-Cell RNA Sequencing Data Labeling via Web Search-Augmented Agentic Generative AI Foundation Models | 提出利用带实时 Web 搜索的 Agent 基础模型自动化单细胞 RNA 测序数据标签 | 解决结构化组学数据监督学习中人工 curation 瓶颈及错误问题 | 生物信息学与细胞图谱 |
| 36 | http://arxiv.org/abs/2506.12689v2 | SciSage: A Multi-Agent Framework for High-Quality Scientific Survey Generation | 提出 SciSage 框架，采用 reflect-when-you-write 范式生成高质量科学综述 | 解决当前 LLM 综述生成缺乏深度分析、结构连贯性及可靠引用的问题 | 科学文献综述与research 辅助 |
| 37 | http://arxiv.org/abs/2506.12083v1 | TuneGenie: Reasoning-based LLM agents for preferential music generation | 提出 TuneGenie，利用 LLM 分析用户偏好并生成提示词驱动音乐生成。 | 解决音乐生成中用户偏好分析及有效提示词构建的难题。 | 音乐生成与推荐 |
| 38 | http://arxiv.org/abs/2506.08726v3 | Improved LLM Agents for Financial Document Question Answering | 提出改进的批评代理与计算器代理，无需 Oracle 标签即可自我修正。 | 解决金融文档数值问答中批评代理在无标签场景性能下降问题。 | 金融文档问答 |
| 39 | http://arxiv.org/abs/2506.09247v1 | Agent-based Condition Monitoring Assistance with Multimodal Industrial Database Retrieval Augmented Generation | 提出 MindRAG 框架，结合多模态 RAG 与向量存储辅助工业状态监测。 | 解决故障严重性估计不确定性高及误报率高的问题。 | 工业状态监测 |
| 40 | http://arxiv.org/abs/2506.11140v3 | Autonomous Computer Vision Development with Agentic AI | 演示利用 Agentic AI 从自然语言提示自主构建计算机视觉系统。 | 解决传统 CV 开发中规划与工具配置依赖数据科学家的问题。 | 计算机视觉开发 |
| 41 | http://arxiv.org/abs/2506.11150v3 | ADAgent: LLM Agent for Alzheimer's Disease Analysis with Collaborative Coordinator | 提出 ADAgent，集成推理引擎与医疗工具支持阿尔茨海默病多模态诊断。 | 解决现有方法依赖单模态数据及无法处理任意输入组合问题。 | 阿尔茨海默病分析 |
| 42 | http://arxiv.org/abs/2506.09755v2 | Intelligent Design 4.0: Paradigm Evolution Toward the Agentic AI Era | 提出 ID 4.0 范式，利用基础模型基于多代理协作支持工程设计自动化。 | 解决工程设计日益复杂性及需要更高适应性自主性问题。 | 工程设计自动化 |
| 43 | http://arxiv.org/abs/2506.10175v1 | AURA: A Multi-Agent Intelligence Framework for Knowledge-Enhanced Cyber Threat Attribution | 提出 AURA 框架，结合 RAG 与 LLM 实现自动化可解释 APT 归因。 | 解决 APT 归因中关联行为模式及推理复杂威胁情报 artifacts 挑战。 | 网络威胁归因 |
| 44 | http://arxiv.org/abs/2506.10420v2 | Multi-dimensional Autoscaling of Processing Services: A Comparison of Agent-based Methods | 比较四种缩放代理在边缘计算中动态调整硬件资源及服务配置性能。 | 解决边缘计算严格资源约束下需要更灵活缩放行为问题。 | 边缘计算自动缩放 |
| 45 | http://arxiv.org/abs/2506.10501v2 | BugGen: A Self-Correcting Multi-Agent LLM Pipeline for Realistic RTL Bug Synthesis | 提出 BugGen 流水线，自主生成插入验证 RTL 中真实功能 bug。 | 解决 ML 辅助调试依赖多样可扩展 bug 数据集现有方法失败问题。 | 硬件验证与调试 |
| 46 | http://arxiv.org/abs/2506.10540v2 | AniMaker: Multi-Agent Animated Storytelling with MCTS-Driven Clip Generation | 提出 AniMaker 框架，利用 MCTS 驱动剪辑生成实现故事连贯动画。 | 解决视频生成模型在长程多场景叙事中连贯性及节奏问题。 | 动画故事生成 |
| 47 | http://arxiv.org/abs/2506.10751v2 | Neural at ArchEHR-QA 2025: Agentic Prompt Optimization for Evidence-Grounded Clinical Question Answering | 利用 DSPy 优化提示空间，结合自一致性投票提升临床 QA 证据召回。 | 解决 EHR 自动 QA 需精确证据检索及有限监督下忠实生成问题。 | 临床问题回答 |
| 48 | http://arxiv.org/abs/2506.15567v3 | Intelligent Assistants for the Semiconductor Failure Analysis with LLM-Based Planning Agents | LLM 规划代理集成外部工具，自动化复杂查询与工作流 | 半导体失效分析流程繁琐与知识整合难 | 半导体实验室失效分析 |
| 49 | http://arxiv.org/abs/2506.17320v1 | MAARTA:Multi-Agentic Adaptive Radiology Teaching Assistant | 多智能体分析凝视模式，个性化反馈诊断错误 | 放射学学生感知专家经验不足与诊断错误 | 医学教育与放射学培训 |
| 50 | http://arxiv.org/abs/2506.15911v2 | From RAG to Agentic: Validating Islamic-Medicine Responses with LLM Agents | 统一评估管道，结合检索与代理自批判过滤 | 伊斯兰医学指导缺乏文化 grounded 验证 | 文化敏感医疗问答 |
| 51 | http://arxiv.org/abs/2506.15947v1 | HybridRAG-based LLM Agents for Low-Carbon Optimization in Low-Altitude Economy Networks | HybridRAG 检索结构信息，R2DSAC 算法解多目标优化 | 低空经济网络低碳优化建模复杂与耦合难 | 无人机移动边缘计算网络 |
| 52 | http://arxiv.org/abs/2506.17339v2 | AI is the Strategy: From Agentic AI to Autonomous Business Models onto Strategy in the Age of AI | 提出自主商业模式概念，AI 即战略核心 | 传统企业模型无法适应代理 AI 自主执行价值创造 | 企业战略管理与商业模式 |
| 53 | http://arxiv.org/abs/2506.16429v1 | Agentic Personalisation of Cross-Channel Marketing Experiences | 序列决策框架优化营销接触策略，Thompson 采样 | 手动编排营销内容效率低与个性化不足 | 跨渠道营销与用户 engagement |
| 54 | http://arxiv.org/abs/2506.16609v4 | Aethorix v1.0: An Integrated Scientific AI Agent for Scalable Inorganic Materials Innovation and Industrial Implementation | 科学语料推理引擎，扩散模型零样本逆向设计 | 工业制造中 AI 集成难与材料设计创新瓶颈 | 无机材料创新与水泥生产 |
| 55 | http://arxiv.org/abs/2506.16650v1 | SemAgent: A Semantics Aware Program Repair Agent | 语义感知工作流，执行语义检索与两阶段修复 | 现有修复系统过度局部化与缺乏语义理解 | 软件工程自动程序修复 |
| 56 | http://arxiv.org/abs/2506.16813v1 | Integrating Traditional Technical Analysis with AI: A Multi-Agent LLM-Based Approach to Stock Market Forecasting | ElliottAgents 整合艾略特波浪与 AI，多 faceted 分析 | 传统技术分析在复杂金融市场预测局限 | 股票市场预测与交易 |
| 57 | http://arxiv.org/abs/2506.21608v1 | SysTemp: A Multi-Agent System for Template-Based Generation of SysML v2 | 多智能体系统基于模板生成 SysML v2 模型 | 复杂系统工程中 SysML v2 模型自动生成挑战 | 系统工程建模 |
| 58 | http://arxiv.org/abs/2506.17484v1 | From Unstructured Communication to Intelligent RAG: Multi-Agent Automation for Supply Chain Knowledge Bases | 离线优先方法，多代理转化非结构化通信为知识库 | 供应链知识 buried 于非结构化数据与 RAG 效果差 | 供应链知识管理与支持 |
| 59 | http://arxiv.org/abs/2506.13037v2 | MAGIC: Multi-Agent Argumentation and Grammar Integrated Critiquer | 利用五类专用 Agent 协作进行 essay 评分与反馈生成。 | 解决现有系统重分数轻反馈及大学级别评估缺失问题。 | 教育评估/作文批改 |
| 60 | http://arxiv.org/abs/2506.13068v2 | Towards the Autonomous Optimization of Urban Logistics: Training Generative AI with Scientific Tools via Agentic Digital Twins and Model Context Protocol | 基于 MCP 编排多 Agent 协作科学工具实现城市物流自主优化。 | 解决传统物流优化依赖人工协调且扩展性差的问题。 | 城市物流/数字孪生 |
| 61 | http://arxiv.org/abs/2506.13474v3 | Language Agents for Hypothesis-driven Clinical Decision Making with Reinforcement Learning | 提出假设驱动的语言 Agent 模拟临床诊断决策过程。 | 解决现有 LLM 临床决策缺乏交互式调查及任务特定训练问题。 | 医疗诊断/临床决策 |
| 62 | http://arxiv.org/abs/2506.13905v2 | Spec2RTL-Agent: Automated Hardware Code Generation from Complex Specifications Using LLM Agent Systems | 提出多 Agent 协作系统从复杂规格书自动生成 RTL 代码。 | 解决现有 LLM 生成 RTL 代码依赖人工指导及扩展性差问题。 | 硬件设计/代码生成 |
| 63 | http://arxiv.org/abs/2506.14142v1 | RadFabric: Agentic AI System with Reasoning Capability for Radiology | 构建多 Agent 多模态推理框架用于胸部 X 光综合解读。 | 解决现有自动化系统在病理覆盖及视觉文本推理整合上的局限。 | 放射学/医疗诊断 |
| 64 | http://arxiv.org/abs/2506.14159v2 | StorySage: Conversational Autobiography Writing Powered by a Multi-Agent Framework | 利用多 Agent 框架辅助用户通过对话撰写自传。 | 解决现有写作助手难以捕捉个人记忆及构建完整叙事问题。 | 创意写作/个人传记 |
| 65 | http://arxiv.org/abs/2506.14199v1 | MAS-LitEval : Multi-Agent System for Literary Translation Quality Assessment | 利用多 Agent 系统评估文学翻译的术语、叙事及风格。 | 解决传统指标无法评估文学翻译文化细微差别的问题。 | 文学翻译/质量评估 |
| 66 | http://arxiv.org/abs/2506.14285v1 | From What to Respond to When to Respond: Timely Response Generation for Open-domain Dialogue Agents | 提出及时对话响应生成任务及 Timer Agent 预测时间间隔。 | 解决开放域对话 Agent 缺乏时间上下文感知及响应时机问题。 | 开放域对话/响应生成 |
| 67 | http://arxiv.org/abs/2506.14302v1 | Expectation Confirmation Preference Optimization for Multi-Turn Conversational Recommendation Agent | 引入期望确认理论优化多轮对话推荐 Agent 的用户满意度。 | 解决多轮对话中偏好优化成本高及短视响应问题。 | 对话推荐/用户满意度 |
| 68 | http://arxiv.org/abs/2506.14315v2 | ImmerseGen: Agent-Guided Immersive World Generation with Alpha-Textured Proxies | 提出 Agent 引导的沉浸式世界生成框架使用轻量几何代理。 | 解决 3D 场景生成管线复杂及移动 VR 渲染效率低的问题。 | VR 内容生成/场景建模 |
| 69 | http://arxiv.org/abs/2506.14683v2 | Unified Software Engineering Agent as AI Software Engineer | 开发统一软件工程 Agent 处理编码、测试及补丁等多任务。 | 解决现有 Agent 仅针对特定软件任务缺乏统一 orchestration 问题。 | 软件工程/AI 工程师 |
| 70 | http://arxiv.org/abs/2506.15167v2 | LLM Agent for Hyper-Parameter Optimization | 设计 LLM Agent 自动优化无人机轨迹通信算法超参数。 | 解决现有超参数优化方法自动化低及性能可改进问题。 | 通信算法/超参数优化 |
| 71 | http://arxiv.org/abs/2506.17539v3 | Breaking Single-Tester Limits: Multi-Agent LLMs for Multi-User Feature Testing | 提出 MAdroid 多智能体框架，模拟多用户交互测试 | 解决多用户交互功能自动化测试难题 | 移动应用多用户功能测试 |
| 72 | http://arxiv.org/abs/2506.17765v2 | CARTS: Collaborative Agents for Recommendation Textual Summarization | 多智能体分解生成、 refinement 与仲裁三阶段 | 解决推荐系统文本摘要相关性与长度约束问题 | 电商产品轮播标题生成 |
| 73 | http://arxiv.org/abs/2506.17878v1 | Towards Robust Fact-Checking: A Multi-Agent System with Advanced Evidence Retrieval | 四智能体系统分解主张、检索证据并预测裁决 | 解决自动化事实核查准确性与透明度不足问题 | 网络 misinformation 事实核查 |
| 74 | http://arxiv.org/abs/2506.18348v3 | Dynamic Knowledge Exchange and Dual-diversity Review: Concisely Unleashing the Potential of a Multi-Agent Research Team | 动态知识交换机制与双多样性评审范式 | 解决 LLM 科学家代理缺乏互动推理与评估机制 | 自主科学发现与研究协作 |
| 75 | http://arxiv.org/abs/2506.18424v1 | A Large Language Model-based Multi-Agent Framework for Analog Circuits' Sizing Relationships Extraction | 多智能体框架从论文提取电路尺寸关系修剪搜索空间 | 解决模拟电路尺寸优化搜索空间过大问题 | 模拟电路预布局设计自动化 |
| 76 | http://arxiv.org/abs/2506.18783v1 | TRIZ Agents: A Multi-Agent LLM Approach for TRIZ-Based Innovation | 多智能体系统协作解决基于 TRIZ 方法论的创新问题 | 解决 TRIZ 应用需深跨学科知识限制 | 工程复杂创新挑战 |
| 77 | http://arxiv.org/abs/2506.22485v1 | AI Agents-as-Judge: Automated Assessment of Accuracy, Consistency, Completeness and Clarity for Enterprise Documents | 模块化多智能体系统并行/序列评估企业文档 | 解决企业文档人工审核效率低与一致性差问题 | 企业结构化业务文档审核 |
| 78 | http://arxiv.org/abs/2506.19481v1 | LLM-based Multi-Agent System for Intelligent Refactoring of Haskell Code | 多智能体系统自动化 Haskell 代码重构与验证 | 解决函数式编程代码重构劳动密集与缺陷风险 | Haskell 代码维护与重构 |
| 79 | http://arxiv.org/abs/2506.19502v2 | MATE: LLM-Powered Multi-Agent Translation Environment for Accessibility Applications | 多模态无障碍多智能体系统执行模态转换 | 解决残障人士数字环境交互障碍与隐私问题 | 无障碍辅助技术与医疗 |
| 80 | http://arxiv.org/abs/2506.19835v1 | MAM: Modular Multi-Agent Framework for Multi-Modal Medical Diagnosis via Role-Specialized Collaboration | 模块化多智能体框架分解医疗诊断角色 | 解决统一多模态医疗 LLM 知识更新与灵活性局限 | 多模态医疗诊断 |
| 81 | http://arxiv.org/abs/2506.20031v2 | Automated Generation of Diverse Courses of Actions for Multi-Agent Operations using Binary Optimization and Graph Learning | 图抽象任务空间，遗传算法最大化 COA 池多样性 | 解决多代理操作中环境变化与代理能力差异规划 | 灾难响应与军事多代理操作 |
| 82 | http://arxiv.org/abs/2507.22904v2 | SketchMind: A Multi-Agent Cognitive Framework for Assessing Student-Drawn Scientific Sketches | 认知导向多Agent框架，模块化分工实现草图评估与反馈 | 学生科学草图自动评估缺乏可解释性与教学对齐 | 教育领域科学概念评估 |
| 83 | http://arxiv.org/abs/2507.00096v1 | AI-Governed Agent Architecture for Web-Trustworthy Tokenization of Alternative Assets | AI治理层监控Agent行为，结合区块链实现资产代币化可信 | _web_代币化生态中数据真实性与合规性挑战 | 金融资产代币化平台 |
| 84 | http://arxiv.org/abs/2506.23793v1 | Leveraging a Multi-Agent LLM-Based System to Educate Teachers in Hate Incidents Management | 多Agent模拟仇恨事件场景， persona建模+RAG提供教师培训 | 教师仇恨事件管理培训成本高/地域限制 | 教师专业技能培训 |
| 85 | http://arxiv.org/abs/2506.23992v1 | Harnessing AI Agents to Advance Research on Refugee Child Mental Health | RAG管道处理非结构化难民健康数据，提取儿童心理健康知识 | 难民儿童心理健康数据难以规模化处理分析 | 人道主义医疗政策制定 |
| 86 | http://arxiv.org/abs/2506.20415v1 | SV-LLM: An Agentic Approach for SoC Security Verification using Large Language Models | 多Agent助理系统自动化SoC安全验证流程 | 传统验证技术在自动化、可扩展性方面的不足 | 系统级芯片(SoC)安全验证 |
| 87 | http://arxiv.org/abs/2506.20430v3 | An Agentic System for Rare Disease Diagnosis with Traceable Reasoning | DeepRare多Agent系统整合40+工具，生成可追溯诊断假设 | 罕见病诊断周期长、误诊率高的问题 | 罕见病临床诊断支持 |
| 88 | http://arxiv.org/abs/2506.20598v1 | Fine-Tuning and Prompt Engineering of LLMs, for the Creation of Multi-Agent AI for Addressing Sustainable Protein Production Challenges | RAG导向的双Agent框架，文献搜索与信息提取协同 | 可持续蛋白质生产研究知识处理需求 | 微生物蛋白质生产研究 |
| 89 | http://arxiv.org/abs/2506.20743v1 | A Survey of AI for Materials Science: Foundation Models, LLM Agents, Datasets, and Tools | 材料科学AI应用的全面综述与任务驱动分类 | 材料科学领域AI工具分散、缺乏系统性整理 | 材料科学研究与发现 |
| 90 | http://arxiv.org/abs/2507.22898v1 | Voice-guided Orchestrated Intelligence for Clinical Evaluation (VOICE): A Voice AI Agent System for Prehospital Stroke Assessment | 语音驱动AI系统指导中风评估，支持视频记录 | 急救人员中风识别不一致、准确率低 | 院前中风评估与急救 |
| 91 | http://arxiv.org/abs/2507.02925v3 | Large Language Model Agent for Modular Task Execution in Drug Discovery | 模块化LLM框架自动化药物发现早期流程 | 药物发现流程复杂、人工干预多 | 早期计算药物发现 |
| 92 | http://arxiv.org/abs/2506.20921v2 | LLM-guided Chemical Process Optimization with a Multi-Agent Approach | 多Agent LLM框架自主推断操作约束并优化 | 操作约束不明确时传统优化方法不可行 | 化学过程优化 |
| 93 | http://arxiv.org/abs/2506.20930v2 | Quantum Reinforcement Learning Trading Agent for Sector Rotation in the Taiwan Stock Market | 混合量子-经典强化学习框架用于板块轮动 | 强化学习金融应用中奖励与真实目标不匹配 | 台湾股票市场交易 |
| 94 | http://arxiv.org/abs/2506.20964v1 | Evidence-based diagnostic reasoning with multi-agent copilot for human pathology | PathChat+多Agent系统自主评估全切片图像 | 计算病理学缺乏自主诊断推理能力 | 人类病理学诊断 |
| 95 | http://arxiv.org/abs/2507.02938v1 | A Large Language Model-Empowered Agent for Reliable and Robust Structural Analysis | LLM Agent将结构分析重构为代码生成任务 | LLM在工程应用中定量可靠性不足 | 土木工程结构分析 |
| 96 | http://arxiv.org/abs/2506.22185v1 | Autonomic Microservice Management via Agentic AI and MAPE-K Integration | 基于MAPE-K的Agent AI框架自主异常检测与修复 | 微服务分布式特性带来的安全管理挑战 | 云微服务系统管理 |
| 97 | http://arxiv.org/abs/2507.22902v1 | Toward the Autonomous AI Doctor: Quantitative Benchmarking of an Autonomous Agentic AI Versus Board-Certified Clinicians in a Real World Setting | 多Agent AI医生系统真实世界大规模验证 | 缺乏端到端自主LLM医疗系统严格评估 | 虚拟紧急护理医疗场景 |

[返回目录](#目录)

<a id="cat-05"></a>

## 多Agent强化学习

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2506.04251v4 | Language-Driven Coordination and Learning in Multi-Agent Simulation Environments | 提出LLM-MARL框架，整合LLM增强多Agent协调与通信 | 多Agent模拟环境中的协调与泛化能力不足 | 游戏模拟、人机协作训练 |
| 2 | http://arxiv.org/abs/2506.00982v2 | Robust and Safe Multi-Agent Reinforcement Learning with Communication for Autonomous Vehicles | 提出RSR-RSMARL框架，支持Real-Sim-Real策略迁移与安全保护 | 仿真训练MARL策略零样本迁移到硬件的安全性与鲁棒性 | 自动驾驶车辆编队 |
| 3 | http://arxiv.org/abs/2506.01538v2 | LAMARL: LLM-Aided Multi-Agent Reinforcement Learning for Cooperative Policy Generation | 提出LAMARL，LLM自动化生成先验策略和奖励函数引导MARL训练 | MARL样本效率低、需手动迭代调整奖励设计 | 多机器人协作任务 |
| 4 | http://arxiv.org/abs/2506.03205v1 | Q-ARDNS-Multi: A Multi-Agent Quantum Reinforcement Learning Framework with Meta-Cognitive Adaptation for Complex 3D Environments | 提出Q-ARDNS-Multi框架，整合量子电路、元认知适应和多Agent协调 | 复杂3D环境中多Agent导航效率、稳定性和碰撞避免 | 机器人、自主导航 |
| 5 | http://arxiv.org/abs/2506.02385v3 | Multi-agent Markov Entanglement | 揭示多Agent MDP允许价值分解的数学结构，提出"Markov纠缠"概念 | 价值分解为何有效缺乏理论解释，分解误差边界不明 | 多Agent动态规划与RL系统 |
| 6 | http://arxiv.org/abs/2506.04195v1 | MACS: Multi-Agent Reinforcement Learning for Optimization of Crystal Structures | 将原子视为Agent的多Agent晶体结构优化方法 | 周期性晶体结构几何优化效率问题 | 计算化学与材料设计 |
| 7 | http://arxiv.org/abs/2506.04215v1 | Thinking Beyond Visibility: A Near-Optimal Policy Framework for Locally Interdependent Multi-Agent MDPs | 提出扩展截断策略类解决局部可见性限制 | 部分可观测多Agent系统的近最优策略求解 | 协作导航与编队控制 |
| 8 | http://arxiv.org/abs/2506.05527v3 | Sequence Modeling for N-Agent Ad Hoc Teamwork | 基于Transformer的集中式N-Agent临时团队协作方法 | 独立学习无法捕捉Agent间动态协作 | 星际争霸等多Agent任务 |
| 9 | http://arxiv.org/abs/2506.06565v1 | Adapting Under Fire: Multi-Agent Reinforcement Learning for Adversarial Drift in Network Security | 红蓝Agent对抗迭代适应的网络入侵检测环境 | 传统签名方法无法检测未知攻击与策略漂移 | 网络入侵检测 |
| 10 | http://arxiv.org/abs/2506.04265v3 | Cooperative Game-Theoretic Credit Assignment for Multi-Agent Policy Gradients via the Core | 提出 CORA 方法，基于合作博弈论核心分配指导优势分配，评估联盟边际贡献。 | 解决共享全局优势无法捕捉不同智能体联盟贡献导致策略优化不足的问题。 | 合作多智能体强化学习 |
| 11 | http://arxiv.org/abs/2506.02616v1 | Compositional Learning for Modular Multi-Agent Self-Organizing Networks | 提出组合深度强化学习与预测决策方法，采用双层框架管理异构智能体粒度。 | 解决自组织网络中参数依赖复杂与目标冲突导致的性能挑战。 | 大规模自组织网络优化 |
| 12 | http://arxiv.org/abs/2506.02718v1 | Heterogeneous Group-Based Reinforcement Learning for LLM-based Multi-Agent Systems | 提出无 Critic 的 MHGPO 算法，通过估计异质组间相对奖励优势指导策略更新。 | 解决现有 MARL 算法依赖 Critic 网络导致训练不稳定与计算负担重的问题。 | LLM 多智能体搜索系统优化 |
| 13 | http://arxiv.org/abs/2506.02841v4 | Enhancing Sample Efficiency in Multi-Agent RL with Uncertainty Quantification and Selective Exploration | 结合分解集中式评论家与去中心化集成学习，利用集成峰度指导选择性探索。 | 解决 MARL 算法收敛需大量环境交互且探索联合动作空间困难的问题。 | 多智能体强化学习样本效率 |
| 14 | http://arxiv.org/abs/2506.07232v1 | "Learn as Individuals, Evolve as a Team: Multi-agent LLMs Adaptation in Embodied Environments" | 提出 LIET 范式，个体学习局部效用函数，团队维护共享合作知识列表。 | 解决 LLM 代理在多智能体具身场景中适应能力弱的问题。 | 具身环境中的多智能体规划 |
| 15 | http://arxiv.org/abs/2506.07392v4 | From Static to Adaptive Defense: Federated Multi-Agent Deep Reinforcement Learning-Driven Moving Target Defense Against DoS Attacks in UAV Swarm Networks | 提出联邦多代理 DRL 驱动的移动目标防御框架，协同优化策略。 | 解决无人机集群网络在动态拓扑下应对 DoS 攻击防御效果差的问题。 | 无人机集群网络安全防御 |
| 16 | http://arxiv.org/abs/2506.07450v1 | Efficient Generation of Diverse Cooperative Agents with World Models | 提出 XPM-WM 框架，利用世界模型生成模拟轨迹加速多样合作代理训练。 | 解决零样本协调代理训练中伙伴生成计算昂贵且样本效率低的问题。 | 多智能体协调与训练 |
| 17 | http://arxiv.org/abs/2506.07548v1 | Curriculum Learning With Counterfactual Group Relative Policy Advantage For Multi-Agent Reinforcement Learning | 提出动态课程学习框架，结合反事实组相对策略优势稳定非平稳环境学习。 | 解决 MARL 训练对手策略固定导致适应性差及学习不稳定问题。 | 多智能体强化学习训练 |
| 18 | http://arxiv.org/abs/2506.07755v1 | Deep Equivariant Multi-Agent Control Barrier Functions | 引入对称性 infused 分布式控制屏障函数，编码安全约束实现零样本泛化。 | 解决基于学习的安全方法在可扩展性、泛化及采样效率上的不足。 | 多机器人导航与安全 |
| 19 | http://arxiv.org/abs/2506.07829v2 | Decentralizing Multi-Agent Reinforcement Learning with Temporal Causal Information | 扩展形式工具检查局部策略兼容性，利用时间因果信息加速学习。 | 解决去中心化多智能体 RL 中策略兼容性及隐私通信限制问题。 | 去中心化多智能体协作 |
| 20 | http://arxiv.org/abs/2506.11285v1 | Shapley Machine: A Game-Theoretic Framework for N-Agent Ad Hoc Teamwork | 提出 Shapley Machine 算法，将合作博弈论 Shapley 值直接关联到 RL 概念进行信用分配 | 解决开放多 Agent 系统中启发式设计缺乏理论严谨性与信用分配模糊问题 | 开放多 Agent 系统 (智能电网等) |
| 21 | http://arxiv.org/abs/2506.12497v2 | Wasserstein-Barycenter Consensus for Cooperative Multi-Agent Reinforcement Learning | 提出基于 Wasserstein 重心的共识框架，通过软惩罚对齐异构策略同时保留 specialized 行为 | 解决合作 MARL 中对齐异构策略同时保留 specialized 行为缺乏原则机制的问题 | 合作多 Agent 强化学习 |
| 22 | http://arxiv.org/abs/2506.12600v1 | Trust-MARL: Trust-Based Multi-Agent Reinforcement Learning Framework for Cooperative On-Ramp Merging Control in Heterogeneous Traffic Flow | 提出 Trust-MARL 框架，利用 Agent 间信任机制优化异构交通流中的协同匝道合并控制 | 解决人类驾驶行为不可预测性 disrupt 交通流且 compromise 系统性能的问题 | 智能交通系统与自动驾驶 |
| 23 | http://arxiv.org/abs/2506.08438v1 | Learning to Lead: Incentivizing Strategic Agents in the Dark | 提出样本高效算法，结合延迟机制与奖励角度估计框架激励策略代理。 | 解决主代理模型中代理私有类型及策略误报导致的学习挑战。 | 在线学习与博弈场景 |
| 24 | http://arxiv.org/abs/2506.09049v3 | VIKI-R: Coordinating Embodied Multi-Agent Cooperation via Reinforcement Learning | 提出 VIKI-R 框架，结合 CoT 微调与 RL 协调具身多代理合作。 | 解决动态环境中多具身代理感知推理与可扩展合作策略挑战。 | 具身多代理协作 |
| 25 | http://arxiv.org/abs/2506.09434v4 | When Is Diversity Rewarded in Cooperative Multi-Agent Learning? | 理论分析奖励设计曲率如何决定异质性团队优势，提出 HetGPS 算法。 | 解释何时行为多样性在多代理任务分配中带来可衡量收益。 | 多代理任务分配 |
| 26 | http://arxiv.org/abs/2506.22445v1 | Hierarchical Adversarially-Resilient Multi-Agent Reinforcement Learning for Cyber-Physical Systems Security | 提出 HAMARL 框架，结合分层多代理协调与对抗感知训练增强 CPS 安全。 | 解决 CPS 面临适应性及零日攻击传统安全方法不足问题。 | 信息物理系统安全 |
| 27 | http://arxiv.org/abs/2506.15856v1 | Learning to Coordinate Under Threshold Rewards: A Cooperative Multi-Agent Bandit Framework | Threshold-Coop-UCB 算法，去中心化学习激活阈值 | 阈值激活奖励下的协调行动与诱饵臂问题 | 合作多智能体.bandit 任务 |
| 28 | http://arxiv.org/abs/2506.17342v1 | Adaptive Social Metaverse Streaming based on Federated Multi-Agent Deep Reinforcement Learning | 联邦多代理 PPO，动态调整码率保护隐私 | 元宇宙流媒体隐私泄露与低延迟高质量难兼顾 | 社交元宇宙流媒体服务 |
| 29 | http://arxiv.org/abs/2506.16995v3 | Style-Preserving Policy Optimization for Game Agents | MPPO 方法，统一损失目标保留演示者风格 | 游戏 AI  proficiency 提升与多样化风格难以兼顾 | 游戏代理与玩家体验 |
| 30 | http://arxiv.org/abs/2506.17029v1 | Scalable and Reliable Multi-agent Reinforcement Learning for Traffic Assignment | MARL-OD-DA 框架，OD 对路由器定义代理 | 大规模交通分配中 MARL 扩展性与可靠性挑战 | 城市交通分配问题 |
| 31 | http://arxiv.org/abs/2506.13113v1 | Dynamic Reinsurance Treaty Bidding via Multi-Agent Reinforcement Learning | 开发 MARL 框架用于再保险条约竞价，模拟竞争性环境。 | 解决传统再保险 Placement 流程效率低及定价不透明问题。 | 再保险市场/金融竞价 |
| 32 | http://arxiv.org/abs/2506.13755v1 | MARCO: Hardware-Aware Neural Architecture Search for Edge Devices with Multi-Agent Reinforcement Learning and Conformal Prediction Filtering | 结合 MARL 与符合性预测过滤加速边缘设备神经架构搜索。 | 解决边缘 AI 部署中搜索时间长及硬件约束严格的问题。 | 边缘计算/神经架构搜索 |
| 33 | http://arxiv.org/abs/2506.14187v1 | Hierarchical Multi-Agent Reinforcement Learning-based Coordinated Spatial Reuse for Next Generation WLANs | 采用分层 MARL 实现下一代 WLAN 的下行链路空间复用。 | 解决高密度 Wi-Fi 部署中同频干扰及网络性能下降问题。 | 无线网络/空间复用 |
| 34 | http://arxiv.org/abs/2506.14988v6 | Fair Algorithms with Probing for Multi-Agent Multi-Armed Bandits | 提出带探测的多 Agent 多臂老虎机框架确保公平与性能。 | 解决信息受限下多 Agent 决策的公平性与系统效率平衡问题。 | 多 Agent 决策/公平算法 |
| 35 | http://arxiv.org/abs/2506.15207v2 | Multi-Agent Reinforcement Learning for Autonomous Multi-Satellite Earth Observation: A Realistic Case Study | 研究 MARL 在多卫星地球观测任务中的自主协调规划。 | 解决动态 EO 任务中实时决策及去中心化协调挑战。 | 卫星观测/自主协调 |
| 36 | http://arxiv.org/abs/2506.18537v1 | Transformer World Model for Sample Efficient Multi-Agent Reinforcement Learning | 去中心化想象框架结合半集中式评论家与队友预测 | 解决部分可观测下多智能体非平稳性与样本效率 | 多智能体强化学习环境 |
| 37 | http://arxiv.org/abs/2506.18571v1 | Agentic Markets: Game Dynamics and Equilibrium in Markets with Learning Agents | 建模学习代理行为为动力系统，分析均衡收敛 | 解决自动化市场中学习代理均衡稳定性问题 | 经济市场中的自主交易代理 |
| 38 | http://arxiv.org/abs/2506.18627v1 | Multi-Agent Reinforcement Learning for Inverse Design in Photonic Integrated Circuits | 将设计空间离散化为网格，多智能体优化二进制变量 | 解决光子集成电路逆设计易陷局部极小值问题 | 光子集成电路逆设计 |
| 39 | http://arxiv.org/abs/2506.18651v2 | Structured Diversity Control: A Dual-Level Framework for Group-Aware Multi-Agent Coordination | 定义组内最小化与组间最大化多样性的加权指标 | 解决复杂协作场景中行为多样性控制不足问题 | 群体感知多智能体协调 |
| 40 | http://arxiv.org/abs/2506.18679v2 | MARL-MambaContour: Unleashing Multi-Agent Deep Reinforcement Learning for Active Contour Optimization in Medical Image Segmentation | 轮廓点建模为代理，Mamba 策略网络优化轮廓 | 解决传统像素分割缺乏拓扑约束与结构意识 | 医学图像分割 |
| 41 | http://arxiv.org/abs/2506.18814v2 | Online Multi-Agent Control with Adversarial Disturbances | 分析在线梯度控制器在对抗扰动下的 regret 界 | 解决多代理线性动力系统对抗扰动鲁棒性 | 自主机器人与能源系统在线控制 |
| 42 | http://arxiv.org/abs/2506.19417v1 | Center of Gravity-Guided Focusing Influence Mechanism for Multi-Agent Reinforcement Learning | 聚焦影响机制引导代理影响任务关键状态维度 | 解决稀疏奖励下探索有限与协调注意力不足 | 合作多智能体强化学习 |
| 43 | http://arxiv.org/abs/2506.19846v1 | JoyAgents-R1: Joint Evolution Dynamics for Versatile Multi-LLM Agents with Reinforcement Learning | 联合进化动力学应用 GRPO 于异构多智能体训练 | 解决异构代理联合进化协作效率与训练不稳定 | 通用与领域特定多智能体任务 |
| 44 | http://arxiv.org/abs/2506.20039v1 | Learning Bilateral Team Formation in Cooperative Multi-Agent Reinforcement Learning | 学习动态多智能体系统中双侧团队形成框架 | 解决动态种群中算法双侧分组选择影响未探索 | 合作多智能体强化学习 |
| 45 | http://arxiv.org/abs/2506.24119v3 | SPIRAL: Self-Play on Zero-Sum Games Incentivizes Reasoning via Multi-Agent Multi-Turn Reinforcement Learning | 自博弈零和游戏生成自动课程，角色条件优势估计稳定多Agent训练 | 推理能力训练依赖人工标注数据与领域特定奖励工程 | 语言模型推理能力自主发展 |
| 46 | http://arxiv.org/abs/2506.20908v2 | Optimal Type-Dependent Liquid Welfare Guarantees for Autobidding Agents with Budgets | 类型依赖平滑框架分析自动竞价Agent福利 | 异质Agent类型下拍卖效率保证问题 | 在线广告自动竞价系统 |
| 47 | http://arxiv.org/abs/2506.21079v1 | Homogenization of Multi-agent Learning Dynamics in Finite-state Markov Games | 学习过程重缩放近似为确定性ODE | 多Agent强化学习动力学分析复杂 | 有限状态Markov博弈 |
| 48 | http://arxiv.org/abs/2506.22117v1 | Learning Distributed Safe Multi-Agent Navigation via Infinite-Horizon Optimal Graph Control | HJB-GNN学习框架联合学习CBF和分布式控制策略 | 安全与目标达成之间的保守权衡 | 分布式多Agent导航 |
| 49 | http://arxiv.org/abs/2506.22708v1 | FairMarket-RL: LLM-Guided Fairness Shaping for Multi-Agent Reinforcement Learning in Peer-to-Peer Markets | LLM作为实时公平性批评者塑造Agent奖励 | P2P交易缺乏鲁棒公平性保障框架 | 去中心化能源P2P市场 |

[返回目录](#目录)

<a id="cat-06"></a>

## Agent工具使用与环境交互

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2506.00886v2 | Position: Agent Should Invoke External Tools ONLY When Epistemically Necessary | 提出Agent工具调用认知必要性理论(ToA框架) | Agent过度依赖外部工具导致效率低下和推理能力退化 | 工具增强型Agent系统设计 |
| 2 | http://arxiv.org/abs/2506.01056v4 | MCP-Zero: Active Tool Discovery for Autonomous LLM Agents | 提出MCP-Zero框架，Agent主动发现并请求所需工具 | 当前Agent被动选择预定义工具，缺乏自主能力发现 | 通用自主Agent系统 |
| 3 | http://arxiv.org/abs/2506.04676v1 | Gen-n-Val: Agentic Image Data Generation and Validation | 双Agent框架生成高质量单对象分割数据 | 合成数据的多对象掩码与标签错误问题 | 计算机视觉数据生成 |
| 4 | http://arxiv.org/abs/2506.02865v2 | Surfer-H Meets Holo1: Cost-Efficient Web Agent Powered by Open Weights | 集成 VLM 与开源 Holo1 模型，在 WebVoyager 上实现准确率与成本效益平衡。 | 解决 Web 智能体依赖昂贵闭源模型且成本效率低的问题。 | 低成本 Web 导航与信息提取 |
| 5 | http://arxiv.org/abs/2506.03011v1 | Coding Agents with Multimodal Browsing are Generalist Problem Solvers | 构建 OpenHands-Versa，使用少量通用工具实现跨多样任务的高性能。 | 解决专用智能体工具集高度特化导致无法泛化 Beyond 目标域的问题。 | 通用问题解决智能体 |
| 6 | http://arxiv.org/abs/2506.03143v1 | GUI-Actor: Coordinate-Free Visual Grounding for GUI Agents | 提出基于注意力的动作头，对齐专用 token 与视觉 patch，实现无坐标定位。 | 解决基于坐标生成的视觉定位存在空间语义对齐弱等问题。 | GUI 智能体视觉定位 |
| 7 | http://arxiv.org/abs/2506.03533v2 | Go-Browse: Training Web Agents with Structured Exploration | 将数据收集框架化为图搜索，自动收集多样化 Web 智能体数据进行结构化探索。 | 解决数字智能体缺乏环境理解导致在陌生网站迷失的问题。 | Web 智能体训练与探索 |
| 8 | http://arxiv.org/abs/2506.07217v2 | BIMgent: Towards Autonomous Building Modeling via Computer-use Agents | 提出 BIMgent 框架，通过 GUI 操作实现自主建筑模型创作，支持多模态输入。 | 解决建筑信息建模软件中复杂交互模式自动化不足的问题。 | 建筑工程与建筑建模 |
| 9 | http://arxiv.org/abs/2506.08332v2 | ORFS-agent: Tool-Using Agents for Chip Design Optimization | 引入基于 LLM 迭代优化代理，自动调整开源硬件设计流中的参数配置。 | 解决集成电路设计流中高维参数优化配置复杂且影响下游 outcomes 问题。 | 芯片设计优化 |
| 10 | http://arxiv.org/abs/2506.18959v3 | From Web Search towards Agentic Deep Research: Incentivizing Search with Reasoning Agents | 整合自主推理、迭代检索与信息合成动态反馈 | 解决传统关键词搜索处理复杂多步信息需求不足 | 复杂信息研究与搜索 |
| 11 | http://arxiv.org/abs/2506.19998v1 | Doc2Agent: Scalable Generation of Tool-Using Agents from API Documentation | 可扩展管道从 API 文档生成可执行工具代理 | 解决任意领域构建工具使用代理需读文档测试 | 基于 REST API 的 Web 代理 |
| 12 | http://arxiv.org/abs/2506.23049v1 | AURA: Agent for Understanding, Reasoning, and Automated Tool Use in Voice-Driven Tasks | 首个开源语音原生Agent，级联ASR+TTS+LLM支持多轮对话与动态工具调用 | 语音任务缺乏完整speech-to-speech多轮对话与工具集成能力 | 语音助手、日历/邮件/搜索等日常任务 |
| 13 | http://arxiv.org/abs/2506.20911v1 | FaSTA*: Fast-Slow Toolpath Agent with Subroutine Mining for Efficient Multi-turn Image Editing | 快慢结合工具路径Agent，子程序挖掘复用 | 多轮图像编辑任务计算成本高 | 多轮图像编辑任务 |
| 14 | http://arxiv.org/abs/2506.21174v1 | Performance improvement of spatial semantic segmentation with enriched audio features and agent-based error correction for DCASE 2025 Challenge Task 4 | 增强音频特征结合Agent误差校正系统 | 音频场景分割误报率高 | 声音场景空间语义分割 |

[返回目录](#目录)

<a id="cat-07"></a>

## 人机协作Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2506.02055v1 | Will Agents Replace Us? Perceptions of Autonomous Multi-Agent AI | 调查130名专业人士对多Agent AI系统的认知与态度 | 理解行业对Agent部署的期望、障碍与治理需求 | 软件开发与知识工作行业 |
| 2 | http://arxiv.org/abs/2506.04253v1 | HADA: Human-AI Agent Decision Alignment Architecture | 提出HADA架构，多角色利益相关者Agent对齐组织目标与价值观 | 多Agent系统中人机决策对齐与可追溯性 | 企业决策管道、信贷审批 |
| 3 | http://arxiv.org/abs/2506.01624v1 | Social Cooperation in Conversational AI Agents | 显式建模人类社会智能，推导新博弈论目标优化LLM和Agent | 对话Agent难以泛化到长期人机互动场景 | 长期人机协作关系 |
| 4 | http://arxiv.org/abs/2506.06576v3 | Future of Work with AI Agents: Auditing Automation and Augmentation Potential across the U.S. Workforce | 提出人类代理度量表(HAS)与WORKBank数据库 | 缺乏对工人自动化/增强偏好的系统理解 | 劳动力与职业任务 |
| 5 | http://arxiv.org/abs/2506.02514v1 | To Embody or Not: The Effect Of Embodiment On User Perception Of LLM-based Conversational Agents | 通过混合方法研究具身与否对用户感知的影响，发现非具身 agent 被认为更胜任。 | 解决具身化在存在谄媚倾向时可能损害 agent 可信度的问题。 | 对话智能体用户体验 |
| 6 | http://arxiv.org/abs/2506.02993v1 | Mapping Student-AI Interaction Dynamics in Multi-Agent Learning Environments: Supporting Personalised Learning and Reducing Performance Gaps | 研究学生与多智能体交互模式，发现知识共建与协同调节对学习效果影响。 | 解决多智能体学习环境中交互模式及其教学影响不明确的问题。 | 个性化教育与学习支持 |
| 7 | http://arxiv.org/abs/2506.07997v1 | Supporting Construction Worker Well-Being with a Multi-Agent Conversational AI System | 开发多代理对话系统，不同 persona 代理满足工人心理需求及问题解决。 | 解决建筑行业心理健康支持有限及单一代理缺乏社会参与的问题。 | 建筑工人心理健康支持 |
| 8 | http://arxiv.org/abs/2506.11718v2 | Interaction, Process, Infrastructure: A Unified Framework for Human-Agent Collaboration | 提出分层概念框架，将 Process 提升为一级关注点以实现结构自适应协作 | 解决 AI 工具缺乏架构基础以支持持续自适应人机协作的问题 | 知识工作与人类协作系统 |
| 9 | http://arxiv.org/abs/2506.11829v1 | The Space Between Us: A Methodological Framework for Researching Bonding and Proxemics in Situated Group-Agent Interactions | 提出多方法框架，结合主观报告与客观空间追踪研究群体 Agent 交互中的空间社交动态 | 解决现实世界群体 Agent 交互中人类感知与行为对齐挑战 | 博物馆等场景的社会交互 Agent |
| 10 | http://arxiv.org/abs/2506.12347v3 | Why AI Agents Still Need You: Findings from Developer-Agent Collaborations in the Wild | 观察开发者与 SWE Agent 协作，发现增量协作与主动迭代能提升问题解决成功率 | 解决 SWE Agent 在复杂真实任务中面临挑战且人机协作障碍不明的问题 | 软件工程与人机协作 |
| 11 | http://arxiv.org/abs/2506.12469v2 | Levels of Autonomy for AI Agents | 定义五个 escalating 的 Agent 自主级别，将自主性视为独立于能力的设计决策 | 解决 Agent 开发者难以校准适当自主级别及缺乏治理框架的问题 | AI 自主性治理与交互设计 |
| 12 | http://arxiv.org/abs/2506.12636v1 | Mapping Neural Signals to Agent Performance, A Step Towards Reinforcement Learning from Neural Feedback | 提出 NEURO-LOOP 框架，利用 fNIRS 脑信号映射 Agent 性能以实现隐式人类反馈 RL | 解决现有 HITL-RL 依赖主动指令导致人类工作负载高且表达不自然的问题 | 脑机接口与自适应自主系统 |
| 13 | http://arxiv.org/abs/2506.09420v1 | A Call for Collaborative Intelligence: Why Human-Agent Systems Should Precede AI Autonomy | 主张 LLM 基于人机系统应优先于完全自主 AI，强调人类参与控制。 | 解决自主系统可靠性、透明度及理解人类实际需求不足问题。 | 人机协作系统设计 |
| 14 | http://arxiv.org/abs/2506.10462v1 | Are We Generalizing from the Exception? An In-the-Wild Study on Group-Sensitive Conversation Design in Human-Agent Interactions | 研究群体自适应对话设计在社交交互代理中的影响及挑战。 | 探索 CAI 在多方交互及不同 embodiment 间适应的挑战。 | 人机交互对话设计 |
| 15 | http://arxiv.org/abs/2506.12879v1 | Exploring the Potential of Metacognitive Support Agents for Human-AI Co-Creation | 提出元认知支持 Agent 辅助设计师反思性使用生成式 AI。 | 解决设计师整合 AI 工作流中的认知负荷与意图表达难题。 | 机械设计师/人机共创 |
| 16 | http://arxiv.org/abs/2506.21582v4 | VIDEE: Visual and Interactive Decomposition, Execution, and Evaluation of Text Analytics with Intelligent Agents | 支持初级分析师通过人机协作工作流进行高级文本分析。 | 解决非专家用户进行 NLP 任务门槛高及验证困难的问题。 | 文本分析/人机协作 |
| 17 | http://arxiv.org/abs/2506.14670v2 | StreetLens: Enabling Human-Centered AI Agents for Neighborhood Assessment from Street View Imagery | 集成社会科学专家知识到 VLM 工作流评估社区环境。 | 解决传统社区研究耗时且缺乏跨地理背景适应性问题。 | 城市研究/社区评估 |
| 18 | http://arxiv.org/abs/2506.17612v1 | JarvisArt: Liberating Human Artistic Creativity via an Intelligent Photo Retouching Agent | MLLM 驱动代理理解意图，协调 200+ 修图工具 | 解决 AI 修图工具调整性差与泛化不足问题 | 专业照片后期处理与创意表达 |
| 19 | http://arxiv.org/abs/2506.23826v1 | Towards the "Digital Me": A vision of authentic Conversational Agents powered by personal Human Digital Twins | 整合LLM与动态个人数据，镜像个体对话风格/记忆/行为 | 数字孪生缺乏真实交互式对话能力 | 个人数字孪生/虚拟分身 |
| 20 | http://arxiv.org/abs/2506.22893v1 | Agentic Enterprise: AI-Centric User to User-Centric AI | 提出企业Agent成功的六原则，转向用户中心AI | 当前AI中心用户范式忽视企业决策需求 | 企业决策与运营 |
| 21 | http://arxiv.org/abs/2506.22937v2 | GamerAstra: Supporting 2D Non-Twitch Video Games for Blind and Low-Vision Players through a Multi-Agent Framework | 多Agent人机协作框架支持BLV玩家访问游戏 | BLV玩家面临视觉元素不可访问等关键挑战 | 盲人和低视力游戏玩家 |

[返回目录](#目录)

<a id="cat-08"></a>

## Agent架构与框架设计

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2506.04255v1 | HASHIRU: Hierarchical Agent System for Hybrid Intelligent Resource Utilization | 提出分层Agent系统，CEO-Agent动态管理员工Agent，混合智能资源利用 | 当前MAS框架缺乏灵活性、资源感知和模型多样性 | 通用多Agent任务系统 |
| 2 | http://arxiv.org/abs/2506.01300v1 | ReAgent-V: A Reward-Driven Multi-Agent Framework for Video Understanding | 提出ReAgent-V框架，集成高效帧选择与实时奖励生成 | 视频理解中单 pass 推理缺乏动态反馈和自我修正能力 | 视频理解、机器人控制 |
| 3 | http://arxiv.org/abs/2506.01438v2 | Distinguishing Autonomous AI Agents from Collaborative Agentic Systems: A Comprehensive Framework for Understanding Modern Intelligent Architectures | 建立区分独立Agent与协作Agent生态系统的 definitive 框架 | 两种范式概念混淆，缺乏系统性架构对比指导 | Agent系统架构选型 |
| 4 | http://arxiv.org/abs/2506.01442v1 | Agentic Episodic Control | 提出AEC架构，整合RL与LLM增强决策，情景记忆快速检索高价值经验 | RL数据效率低、泛化性差，难以处理复杂任务 | 通用强化学习任务 |
| 5 | http://arxiv.org/abs/2506.01463v1 | Agentic AI and Multiagentic: Are We Reinventing the Wheel? | 批判性分析"Agentic AI"术语滥用，呼吁回归经典Agent理论 | 新术语混淆经典智能Agent和多Agent系统数十年研究成果 | AI Agent学术社区 |
| 6 | http://arxiv.org/abs/2506.01536v2 | Quantum Agents | 形式化定义量子Agent，提出整合量子计算与Agent系统的架构 | 探索量子计算与Agentic AI交叉领域的概念与技术基础 | 量子-Agentic生态系统 |
| 7 | http://arxiv.org/abs/2506.01622v5 | General agents contain world models | 形式化证明能泛化到多步目标导向任务的Agent必须学习环境预测模型 | 世界模型是否为灵活目标导向行为必要组件的理论争议 | 通用Agent能力边界分析 |
| 8 | http://arxiv.org/abs/2506.02153v2 | Small Language Models are the Future of Agentic AI | 提出立场：小语言模型对Agent系统更合适、更经济，是未来方向 | LLM在Agent系统中重复执行 specialized 任务时资源不经济 | Agent系统模型选型 |
| 9 | http://arxiv.org/abs/2506.04632v4 | Risk-Sensitive Agent Compositions | 基于动态规划的风险敏感Agent组合选择算法 | 多Agent工作流中安全、公平、隐私违规风险最小化 | 软件开发与机器人控制 |
| 10 | http://arxiv.org/abs/2506.05520v2 | Toward Data Systems That Are Business Semantic Centric and AI Agents Assisted | 业务语义中心、Agent辅助的数据系统架构 | 现有数据平台与业务需求对齐不足 | 企业数据系统 |
| 11 | http://arxiv.org/abs/2506.06017v2 | AgentSwift: Efficient LLM Agent Design via Value-guided Hierarchical Search | 价值引导的分层MCTS自动化Agent架构搜索 | 自动Agent设计搜索空间有限且评估成本高 | 通用LLM Agent设计 |
| 12 | http://arxiv.org/abs/2506.06935v2 | An Agentic Framework for Autonomous Metamaterial Modeling and Inverse Design | 自主超材料逆向设计的Agent框架集成反思与决策灵活性 | 光子超材料设计需要自动化推理与规划能力 | 光子超材料设计 |
| 13 | http://arxiv.org/abs/2506.02426v2 | Comparative Analysis of AI Agent Architectures for Entity Relationship Classification | 提出多智能体动态示例生成机制，利用实时合作与对抗提示提升关系分类性能。 | 解决有限标注数据和复杂关系结构下的实体关系分类挑战。 | 信息提取与关系分类任务 |
| 14 | http://arxiv.org/abs/2506.02454v3 | Multimodal DeepResearcher: Generating Text-Chart Interleaved Reports From Scratch with Agentic Framework | 提出可视化形式化描述 FDV，构建四阶段多模态智能体框架生成图文交错报告。 | 解决现有深度研究框架仅生成文本、缺乏自动化可视化整合的问题。 | 自动化研究报告生成 |
| 15 | http://arxiv.org/abs/2506.02931v1 | ThinkTank: A Framework for Generalizing Domain-Specific AI Agent Systems into Universal Collaborative Intelligence Platforms | 系统化泛化智能体角色与会议结构，集成 RAG 与本地部署确保数据安全。 | 解决专用 AI 系统难以跨领域通用化及云端部署数据隐私问题。 | 通用协作智能平台构建 |
| 16 | http://arxiv.org/abs/2506.07756v2 | "Agent Semantics, Semantic Spacetime, and Graphical Reasoning" | 呈现语义时空图模型形式方面，定义封闭操作集以扩展语义复杂度。 | 解决图过程中信息泄漏及吸收态导致的闭合性丢失问题。 | 知识表示与过程建模 |
| 17 | http://arxiv.org/abs/2506.07778v3 | A Neurosymbolic Agent System for Compositional Visual Reasoning | 开发可解释可视化增强两阶段神经符号系统，包含 SS-parser 与执行验证器。 | 解决现有视觉语言模型在组合视觉推理任务上表现受限的问题。 | 组合视觉推理任务 |
| 18 | http://arxiv.org/abs/2506.10953v1 | Build the web for agents, not agents for the web | 提出 Agentic Web Interface (AWI) 概念，倡导为 Agent 设计专用交互范式而非适配人类界面 | 解决人类设计界面与 LLM 能力不匹配导致的 Web Agent 效率低下问题 | Web 交互与浏览器自动化 |
| 19 | http://arxiv.org/abs/2506.11650v1 | Robot Context Protocol (RCP): A Runtime-Agnostic Interface for Agent-Aware Robot Control | 提出 RCP 协议，为机器人控制提供运行时无关的统一语义接口，解耦前后端 | 解决机器人系统复杂度高且 Agent 交互缺乏标准化接口的问题 | 机器人控制与多 Agent 生态系统 |
| 20 | http://arxiv.org/abs/2506.12003v2 | Upgrade or Switch: Do We Need a Next-Gen Trusted Architecture for the Internet of AI Agents? | 分析 AI Agent 互联网架构需求，提出混合索引/注册表方案以支持自主 Agent 交互 | 解决现有 Web 基础设施无法满足自主 Agent 毫秒级发现与凭证撤销需求的问题 | 互联网基础设施与 AI Agent 生态 |
| 21 | http://arxiv.org/abs/2506.12202v1 | A Fast, Reliable, and Secure Programming Language for LLM Agents with Code Actions | 提出 Quasar 编程语言，支持自动并行化、不确定性量化及安全验证以替代 Python | 解决 Python 作为 Agent 代码动作语言在性能、安全及可靠性上的不足 | LLM Agent 代码动作执行 |
| 22 | http://arxiv.org/abs/2506.12508v5 | AgentOrchestra: Orchestrating Multi-Agent Intelligence with the Tool-Environment-Agent(TEA) Protocol | 提出 TEA 协议与 AgentOrchestra 框架，统一管理环境、Agent 与工具的生命周期与版本 | 解决现有 Agent 协议跨实体生命周期管理不足导致组合固定且代码脆弱的问题 | 多 Agent 编排与复杂长程任务 |
| 23 | http://arxiv.org/abs/2506.08430v2 | CAF-I: A Collaborative Multi-Agent Framework for Enhanced Irony Detection with Large Language Models | 提出 CAF-I 框架，利用上下文、语义、修辞代理协同优化讽刺检测。 | 解决现有 LLM 讽刺检测视角单一、理解不足及缺乏可解释性问题。 | 讽刺检测任务 |
| 24 | http://arxiv.org/abs/2506.08507v2 | MasHost Builds It All: Autonomous Multi-Agent System Directed by Reinforcement Learning | 提出 MasHost，基于 RL 自主设计多智能体系统图结构，引入组件合理性原则。 | 解决现有多智能体系统构建依赖人工规则及自主性受限问题。 | 多智能体系统构建 |
| 25 | http://arxiv.org/abs/2506.09696v3 | Patterns for a New Generation: AI and Agents | 展示 LLM 系统可读取生成结构化设计模式，作为行动选择共享先验。 | 提供模式能力代理概念验证，指导混合人机设置中的代理行为。 | 软件开发与 AI 治理 |
| 26 | http://arxiv.org/abs/2506.09742v1 | Feature Engineering for Agents: An Adaptive Cognitive Architecture for Interpretable ML Monitoring | 提出认知架构，通过重构、分解、编译三步模拟特征工程提升可解释性。 | 解决传统 ML 监控输出冗长低可解释性阻碍有效决策问题。 | ML 模型监控 |
| 27 | http://arxiv.org/abs/2506.10357v2 | Optimus-3: Dual-Router Aligned Mixture-of-Experts Agent with Dual-Granularity Reasoning-Aware Policy Optimization | 提出 Optimus-3，集成双系统能力，设计双路由器对齐 MoE 架构。 | 解决通用代理在视觉丰富动态环境中认知能力碎片化问题。 | 具身通用代理 |
| 28 | http://arxiv.org/abs/2506.10408v1 | Reasoning RAG via System 1 or System 2: A Survey on Reasoning Agentic Retrieval-Augmented Generation for Industry Challenges | 综述 Reasoning Agentic RAG 方法，分类为预定义推理与代理推理范式。 | 解决早期 RAG 在需复杂推理动态检索及多模态集成场景 struggle 问题。 | 行业 RAG 系统 |
| 29 | http://arxiv.org/abs/2506.15672v1 | SwarmAgentic: Towards Fully Automated Agentic System Generation via Swarm Intelligence | 群体智能优化系统生成，从头构建并联合优化功能 | 现有代理系统生成缺乏全自动与自优化能力 | 开放域任务与系统结构设计 |
| 30 | http://arxiv.org/abs/2506.12801v1 | Mastering Da Vinci Code: A Comparative Study of Transformer, LLM, and PPO-based Agents | 对比 Transformer、LLM 及 PPO 三种 Agent 架构在逻辑推理游戏中的效能。 | 解决复杂演绎任务中 AI 策略优化与逻辑一致性问题。 | 逻辑推理游戏/智能体架构对比 |
| 31 | http://arxiv.org/abs/2506.13171v1 | Querying Large Automotive Software Models: Agentic vs. Direct LLM Approaches | 对比 Agentic 与直接 Prompt 方式查询大型汽车软件模型。 | 解决大模型直接处理超大软件模型上下文不可行的问题。 | 汽车软件/模型查询 |
| 32 | http://arxiv.org/abs/2506.13324v2 | Towards Pervasive Distributed Agentic Generative AI -- A State of The Art | 综述泛在分布式生成式 AI Agent 的架构组件与部署策略。 | 解决资源受限设备上 Agent 部署的架构与隐私挑战。 | 泛在计算/分布式 Agent |
| 33 | http://arxiv.org/abs/2506.15741v2 | OAgents: An Empirical Study of Building Effective Agents | 通过实证研究构建模块化基础 Agent 框架 OAgents。 | 解决当前 Agent 研究缺乏标准化及设计选择影响不明确问题。 | Agent 框架/实证研究 |
| 34 | http://arxiv.org/abs/2506.17913v1 | Learning, Reasoning, Refinement: A Framework for Kahneman's Dual-System Intelligence in GUI Agents | 结合快慢双系统， Omni 解析与 GRPO 接地代理 | 解决 GUI 代理缺乏渐进推理与自适应学习能力 | 图形用户界面自动化任务 |
| 35 | http://arxiv.org/abs/2506.18019v3 | Graphs Meet AI Agents: Taxonomy, Progress, and Future Opportunities | 系统综述图技术如何赋能 AI 智能体核心功能 | 梳理图结构与智能体能力融合的研究现状 | AI 智能体架构设计与数据结构化 |
| 36 | http://arxiv.org/abs/2506.18096v2 | Deep Research Agents: A Systematic Examination And Roadmap | 分析深度研究代理基础技术与架构组件 taxonomy | 系统化现有深度研究代理方法与基准局限 | 复杂多轮信息研究任务 |
| 37 | http://arxiv.org/abs/2506.18472v1 | AViLA: Asynchronous Vision-Language Agent for Streaming Multimodal Data Interaction | 综合记忆保留、证据识别与接地触发三模块 | 解决流式数据中查询与证据异步到达的响应问题 | 自动驾驶与具身智能流式交互 |
| 38 | http://arxiv.org/abs/2506.18900v1 | Audit & Repair: An Agentic Framework for Consistent Story Visualization in Text-to-Image Diffusion Models | 协作多智能体框架迭代识别修正多面板不一致 | 解决故事可视化中角色物体持久性与演化不一致 | 文本到图像故事可视化 |
| 39 | http://arxiv.org/abs/2506.23978v2 | LLM Agents Are the Antidote to Walled Gardens | 提出"通用互操作性"概念，Agent自动翻译数据格式打破封闭平台 | 应用层封闭平台导致数据孤岛与用户锁定 | 互联网开放性与数据可移植性 |
| 40 | http://arxiv.org/abs/2506.24045v2 | Agent.xpu: Efficient Scheduling of Agentic LLM Workloads on Heterogeneous SoC | 首个编排并发reactive/proactive LLM流的引擎，异构加速器协调 | 现有LLM引擎不匹配个人Agent动态混合关键性执行模式 | 端侧个人Agent系统部署 |
| 41 | http://arxiv.org/abs/2506.20091v1 | From Conversation to Orchestration: HCI Challenges and Opportunities in Interactive Multi-Agentic Systems | 提出多智能体系统的HCI挑战框架，识别编排和冲突解决等核心问题 | 多智能体系统的用户中心设计挑战和研究方向 | 多智能体交互系统开发者与研究者 |
| 42 | http://arxiv.org/abs/2506.21931v2 | ARAG: Agentic Retrieval Augmented Generation for Personalized Recommendation | 四Agent协作RAG框架，理解长短期用户行为 | 现有RAG依赖静态检索，无法捕捉动态偏好 | 个性化推荐系统 |
| 43 | http://arxiv.org/abs/2506.22189v2 | Exploring Modularity of Agentic Systems for Drug Discovery | 系统研究Agent系统组件可互换性与依赖性 | 药物发现领域Agent系统模块化研究不足 | 药物发现Agent系统 |
| 44 | http://arxiv.org/abs/2506.22653v1 | URSA: The Universal Research and Scientific Agent | 模块化Agent和工具生态系统，耦合先进物理仿真代码 | 科学研究任务存在瓶颈需AI加速 | 科学研究任务加速 |
| 45 | http://arxiv.org/abs/2506.22656v1 | Knowledge-Guided Multi-Agent Framework for Automated Requirements Development: A Vision | 六Agent+工件池的知识引导多Agent框架 | 现有自动化系统重代码轻需求开发复杂性 | 软件工程需求开发自动化 |

[返回目录](#目录)

<a id="cat-09"></a>

## Agent评测与基准

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2506.02064v3 | The Measurement Imbalance in Agentic AI Evaluation Undermines Industry Productivity Claims | 系统审查84篇论文揭示评估失衡，提出四轴评估模型 | 当前Agent评估过度侧重技术指标，忽视人本、安全和经济维度 | Agent系统评估与部署 |
| 2 | http://arxiv.org/abs/2506.01520v1 | FormFactory: An Interactive Benchmarking Suite for Multimodal Form-Filling Agents | 提出FormFactory基准套件，涵盖多样化真实场景表单填充任务 | 现有工具缺乏泛化生成能力，MLLMs视觉布局推理和字段对齐能力弱 | 在线表单自动化 |
| 3 | http://arxiv.org/abs/2506.01616v1 | MLA-Trust: Benchmarking Trustworthiness of Multimodal LLM Agents in GUI Environments | 提出MLA-Trust框架，四维度评估多模态Agent可信度 | 现有基准未充分解决MLA可操作输出、长程不确定性和多模态攻击向量 | GUI交互多模态Agent |
| 4 | http://arxiv.org/abs/2506.01952v1 | WebChoreArena: Evaluating Web Browsing Agents on Realistic Tedious Web Tasks | 提出WebChoreArena基准，532个精心策划的繁琐网页任务 | 现有基准未充分评估Agent处理人类避免的繁琐复杂任务能力 | 网页浏览Agent评估 |
| 5 | http://arxiv.org/abs/2506.02357v2 | Evaluating LLM Agent Adherence to Hierarchical Safety Principles: A Lightweight Benchmark for Probing Foundational Controllability Components | 提出轻量级基准评估LLM Agent在冲突指令下遵守高层安全原则能力 | 验证Agent行为和早期检测控制缺陷的方法缺乏 | 高级AI安全治理 |
| 6 | http://arxiv.org/abs/2506.02387v2 | VS-Bench: Evaluating VLMs for Strategic Abilities in Multi-Agent Environments | 提出VS-Bench多模态基准，评估VLM在多Agent环境中的战略能力 | 现有基准限于单Agent或纯文本环境，缺乏多Agent视觉战略交互评估 | 战略多模态Agent研究 |
| 7 | http://arxiv.org/abs/2506.04301v2 | The Cost of Dynamic Reasoning: Demystifying AI Agents and Test-Time Scaling from an AI Infrastructure Perspective | 首次系统级分析AI Agent资源消耗、延迟与能耗 | Agent动态推理带来的成本、效率与可持续性问题 | 数据中心与AI基础设施 |
| 8 | http://arxiv.org/abs/2506.04098v2 | TextAtari: 100K Frames Game Playing with Language Agents | 创建10万步长程决策文本游戏基准 | 语言Agent在超长序列规划中的性能评估 | 游戏与长程决策任务 |
| 9 | http://arxiv.org/abs/2506.04135v4 | macOSWorld: A Multilingual Interactive Benchmark for GUI Agents | 首个macOS多语言GUI Agent交互基准 | GUI Agent在macOS环境的评估缺失与多语言支持 | 桌面自动化与无障碍辅助 |
| 10 | http://arxiv.org/abs/2506.11102v1 | Evolutionary Perspectives on the Evaluation of LLM-Based AI Agents: A Comprehensive Survey | 从进化视角系统区分LLM聊天机器人与AI Agent评估 | 现有评估框架混淆聊天机器人与Agent的界限 | Agent评估研究 |
| 11 | http://arxiv.org/abs/2506.02548v2 | CyberGym: Evaluating AI Agents' Real-World Cybersecurity Capabilities at Scale | 构建包含 1507 个真实漏洞的大规模基准，任务为生成复现漏洞的概念验证测试。 | 解决现有评估基于小规模基准且仅测量静态结果的问题。 | 人工智能网络安全能力评估 |
| 12 | http://arxiv.org/abs/2506.02839v1 | DeepShop: A Benchmark for Deep Research Shopping Agents | 引入 DeepShop 基准，包含查询多样性演化与细粒度 holistic 评估框架。 | 解决现有购物 agent 基准无法反映现实世界复杂购物场景的问题。 | 深度研究购物智能体评估 |
| 13 | http://arxiv.org/abs/2506.03231v2 | NetArena: Dynamic Benchmarks for AI Agents in Network Automation | 提出动态基准生成框架，集成网络模拟器测量执行中的正确性、安全与延迟。 | 解决现有基准静态设计易污染且无法反映生产环境复杂性的问题。 | 网络自动化 AI 智能体评估 |
| 14 | http://arxiv.org/abs/2506.03610v2 | Orak: A Foundational Benchmark for Training and Evaluating LLM Agents on Diverse Video Games | 包含 12 款游戏的基础基准，提供 MCP 接口与微调数据集评估 LLM 游戏能力。 | 解决现有游戏基准缺乏多样 LLM 能力评估及微调数据集的问题。 | 游戏行业 LLM 智能体评估 |
| 15 | http://arxiv.org/abs/2506.03828v2 | AssetOpsBench: Benchmarking AI Agents for Task Automation in Industrial Asset Operations and Maintenance | 提供多模态生态与自动化评估框架，分析工具即智能体与计划执行者范式权衡。 | 解决工业资产生命周期管理中复杂工作流自动化缺乏统一评估框架的问题。 | 工业资产运营与维护自动化 |
| 16 | http://arxiv.org/abs/2506.07116v1 | "BRIGHT+: Upgrading the BRIGHT Benchmark with MARCUS, a Multi-Agent RAG Clean-Up Suite" | 提出多代理流水线 MARCUS，清洗并重构 BRIGHT 基准 corpus，提升检索准确性。 | 解决网页爬取 artifacts  impair 检索准确性与下游推理的问题。 | 检索增强生成（RAG）系统 |
| 17 | http://arxiv.org/abs/2506.11112v2 | Dagstuhl Perspectives Workshop 24352 -- Conversational Agents: A Framework for Evaluation (CAFE): Manifesto | 定义 CAFE 框架，包含目标、任务、用户、标准、方法及度量六大组件。 | 解决对话信息访问系统缺乏统一评估框架的问题。 | 对话代理系统评估 |
| 18 | http://arxiv.org/abs/2507.21071v2 | FingerTip 20K: A Benchmark for Proactive and Personalized Mobile LLM Agents | 收集 20K 人类演示，包含上下文信息，提出主动建议与个性化执行新轨道。 | 解决移动 GUI 代理忽视上下文信息及用户偏好差异的问题。 | 移动 LLM 代理评估 |
| 19 | http://arxiv.org/abs/2506.07524v3 | TAI3: Testing Agent Integrity in Interpreting User Intent | 提出 API 中心压力测试框架，通过语义分区与变异生成揭露意图完整性违规。 | 解决传统软件测试无法处理自然语言歧义导致代理误读意图的问题。 | LLM 代理意图理解测试 |
| 20 | http://arxiv.org/abs/2506.07672v1 | "MCPWorld: A Unified Benchmarking Testbed for API, GUI, and Hybrid Computer Use Agents" | 提出首个 API、GUI 及混合计算机使用代理自动测试床，支持白盒应用验证。 | 解决现有基准忽视 API 交互及 UI 变化影响评估准确性的问题。 | 计算机使用代理评估 |
| 21 | http://arxiv.org/abs/2506.07972v2 | HeuriGym: An Agentic Benchmark for LLM-Crafted Heuristics in Combinatorial Optimization | 提出质量 - 产量指数，评估 LLM 生成启发式算法在组合优化问题上的能力。 | 解决现有基准无法充分评估 LLM 在开放解空间问题解决能力的问题。 | 组合优化启发式算法 |
| 22 | http://arxiv.org/abs/2506.07982v1 | $τ^2$-Bench: Evaluating Conversational Agents in a Dual-Control Environment | 建模电信双控制域为 Dec-POMDP，提供组合任务生成器及可靠用户模拟器。 | 解决现有基准模拟单控制环境无法测试代理协调与引导用户能力的问题。 | 对话代理双控制环境评估 |
| 23 | http://arxiv.org/abs/2506.08119v2 | SOP-Bench: Complex Industrial SOPs for Evaluating LLM Agents | 构建 2000+ 工业 SOP 任务基准，涵盖 12 个业务域，支持executable 接口。 | 解决现有基准无法捕捉真实工作流程序复杂性及工具编排需求的问题。 | 工业自动化 SOP 执行 |
| 24 | http://arxiv.org/abs/2506.08136v2 | EconWebArena: Benchmarking Autonomous Agents on Economic Tasks in Realistic Web Environments | 构建 360 个经济任务基准，强调权威数据源忠实度及基于 web 的经济推理。 | 解决缺乏真实 web 环境中复杂多模态经济任务评估基准的问题。 | 经济领域 web 智能任务 |
| 25 | http://arxiv.org/abs/2506.10764v1 | OPT-BENCH: Evaluating LLM Agent on Large-Scale Search Spaces Optimization Problems | 提出 OPT-BENCH 基准与 OPT-Agent 框架，评估 LLM 在大尺度搜索空间优化问题上的迭代推理能力 | 解决 LLM 在复杂解决方案迭代优化中能力评估不足的问题 | 机器学习任务与 NP 问题优化 |
| 26 | http://arxiv.org/abs/2507.00014v1 | SWE-Bench-CL: Continual Learning for Coding Agents | 构建 SWE-Bench-CL 基准，评估 Coding Agent 在连续任务中的知识积累与抗遗忘能力 | 解决静态代码基准无法评估 Agent 持续学习与经验积累能力的问题 | 软件工程与持续学习 Agent |
| 27 | http://arxiv.org/abs/2506.11763v1 | DeepResearch Bench: A Comprehensive Benchmark for Deep Research Agents | 构建 DeepResearch Bench，包含 100 个 PhD 级任务，评估深度研究 Agent 能力 | 解决缺乏系统评估深度研究 Agent 信息检索与综合能力的基准问题 | 深度研究与自动报告生成 |
| 28 | http://arxiv.org/abs/2506.11791v2 | SEC-bench: Automated Benchmarking of LLM Agents on Real-World Software Security Tasks | 提出 SEC-bench 框架，自动构建漏洞数据集以评估 LLM Agent 在真实安全任务上的能力 | 解决现有安全基准依赖合成挑战无法捕捉真实复杂性的问题 | 软件安全工程与漏洞修复 |
| 29 | http://arxiv.org/abs/2506.12266v1 | The Behavior Gap: Evaluating Zero-shot LLM Agents in Complex Task-Oriented Dialogs | 提出评估框架量化 AI Agent 与人类专家在对话行为上的差距，发现行为差距是关键因素 | 解决零 shot LLM Agent 在复杂任务导向对话中性能下降原因不明的问题 | 任务导向对话系统 (TODS) |
| 30 | http://arxiv.org/abs/2506.12666v1 | LIFELONG SOTOPIA: Evaluating Social Intelligence of Language Agents Over Lifelong Social Interactions | 提出 LIFELONG-SOTOPIA 基准，通过多 episode 交互评估语言 Agent 的终身社交智能 | 解决现有研究未充分 study AI 系统在终身社交互动中社会 intelligence 的问题 | 社交智能与语言 Agent 评估 |
| 31 | http://arxiv.org/abs/2506.08800v2 | Measuring Data Science Automation: A Survey of Evaluation Tools for AI Assistants and Agents | survey 数据科学中 LLM 助手与代理的评估工具，指出当前评估局限。 | 解决数据科学自动化评估聚焦单一活动及忽视人机协作问题。 | 数据科学自动化评估 |
| 32 | http://arxiv.org/abs/2506.08933v1 | What Limits Virtual Agent Application? OmniBench: A Scalable Multi-Dimensional Benchmark for Essential Virtual Agent Capabilities | 提出 OmniBench，自生成跨平台图基准，自动化合成可控复杂度任务。 | 解决现有基准任务复杂度不可控及缺乏多维评估的问题。 | 虚拟代理能力评估 |
| 33 | http://arxiv.org/abs/2506.09289v1 | UTBoost: Rigorous Evaluation of Coding Agents on SWE-Bench | 提出 UTBoost 框架，自动生成测试用例增强 SWE-Bench 评估严谨性。 | 解决 SWE-Bench 测试用例不足导致错误补丁被误判为通过问题。 | 代码代理评估 |
| 34 | http://arxiv.org/abs/2506.21558v1 | Bench to the Future: A Pastcasting Benchmark for Forecasting Agents | 提出 BTF“过去预测”基准，提供已知结果问题及离线语料库评估代理。 | 解决 forecasting 基准缺乏现实封闭可重复环境及评估耗时问题。 | 预测代理能力评估 |
| 35 | http://arxiv.org/abs/2506.10055v2 | TaskCraft: Automated Generation of Agentic Tasks | 提出 TaskCraft 工作流，自动生成难度可扩展多工具可验证代理任务。 | 解决现有指令数据缺乏工具交互及基准依赖昂贵人工标注问题。 | 代理任务生成与评估 |
| 36 | http://arxiv.org/abs/2506.10467v4 | Specification and Evaluation of Multi-Agent LLM Systems -- Prototype and Cybersecurity Applications | 引入代理 schema 语言及系统架构，规范并评估多代理 LLM 系统。 | 解决多代理 LLM 系统联合规范及组合应用理解不足问题。 | 网络安全任务评估 |
| 37 | http://arxiv.org/abs/2506.15425v1 | Understanding GUI Agent Localization Biases through Logit Sharpness | 提出 Peak Sharpness Score 量化不确定性，细粒度评估框架 | GUI 智能体定位幻觉与系统性错误 | 多模态大模型 GUI 智能体 |
| 38 | http://arxiv.org/abs/2506.15635v2 | FindingDory: A Benchmark to Evaluate Memory in Embodied Agents | 长程具身任务基准，评估记忆与推理结合能力 | 具身智能体长短期记忆整合与长视界控制难题 | 机器人与具身智能场景 |
| 39 | http://arxiv.org/abs/2506.16042v1 | OSWorld-Human: Benchmarking the Efficiency of Computer-Use Agents | 构建人工标注轨迹基准，评估智能体时间效率 | 计算机使用智能体端到端延迟过高与步数冗余 | 桌面应用自动化任务 |
| 40 | http://arxiv.org/abs/2506.17335v1 | LMR-BENCH: Evaluating LLM Agent's Ability on Reproducing Language Modeling Research | 代码复现基准，评估 NLP 研究代码合成能力 | LLM 智能体科学推理与代码合成能力未被探索 | 科学研究复现与代码生成 |
| 41 | http://arxiv.org/abs/2506.16402v3 | IS-Bench: Evaluating Interactive Safety of VLM-Driven Embodied Agents in Daily Household Tasks | 多模态交互安全基准，过程导向评估风险缓解 | 具身智能体交互中动态风险感知与缓解能力缺失 | 家庭日常任务具身智能体 |
| 42 | http://arxiv.org/abs/2506.21605v1 | MemBench: Towards More Comprehensive Evaluation on the Memory of LLM-based Agents | 综合数据集与基准，评估事实与反思记忆 | 现有记忆评估缺乏多样性与全面指标 | LLM 基于智能体记忆能力 |
| 43 | http://arxiv.org/abs/2506.17208v3 | Dissecting the SWE-Bench Leaderboards: Profiling Submitters and Architectures of LLM- and Agent-Based Repair Systems | 全面分析 SWE-Bench 提交，剖析架构与提交者 | 基准排行榜解决方案架构设计与起源不清晰 | 自动程序修复系统评估 |
| 44 | http://arxiv.org/abs/2506.13651v1 | xbench: Tracking Agents Productivity Scaling with Profession-Aligned Real-World Evaluations | 引入职业对齐的动态评估套件以衡量 Agent 真实生产力。 | 解决现有基准无法反映 Agent 在专业场景经济价值的问题。 | 招聘与营销/生产力评估 |
| 45 | http://arxiv.org/abs/2506.14074v1 | Comprehensive Verilog Design Problems: A Next-Generation Benchmark Dataset for Evaluating Large Language Models and Agents on RTL Design and Verification | 提供包含 783 个问题的 Verilog 设计基准数据集。 | 解决现有硬件设计基准缺乏现实挑战性及 Agent 评估缺失问题。 | 硬件验证/模型评估 |
| 46 | http://arxiv.org/abs/2506.14079v3 | FormGym: Doing Paperwork with Agents | 提出纯图像域表单填写基准及 FieldFinder 辅助工具。 | 解决 Agent 在无 OCR 辅助下表单填写定位能力差的问题。 | 表单处理/多模态 Agent |
| 47 | http://arxiv.org/abs/2506.14205v2 | AgentSynth: Scalable Task Generation for Generalist Computer-Use Agents | 提出可扩展流水线自动生成高质量计算机使用 Agent 任务。 | 解决长程任务数据集标注成本高及复杂度难以调节问题。 | 通用 Agent/任务生成 |
| 48 | http://arxiv.org/abs/2506.14477v1 | GUI-Robust: A Comprehensive Dataset for Testing GUI Agent Robustness in Real-World Anomalies | 引入包含七类异常的综合数据集测试 GUI Agent 鲁棒性。 | 解决现有 GUI 数据集忽略现实部署中常见异常的问题。 | GUI 自动化/鲁棒性测试 |
| 49 | http://arxiv.org/abs/2506.15740v2 | SHADE-Arena: Evaluating Sabotage and Monitoring in LLM Agents | 构建多样化 Agent 评估数据集测试破坏与监控能力。 | 解决长程任务中 Agent 隐蔽目标及逃避监控的评估缺失问题。 | Agent 安全/监控评估 |
| 50 | http://arxiv.org/abs/2506.14697v3 | AGENTSAFE: Benchmarking the Safety of Embodied Agents on Hazardous Instructions | 提出系统性基准评估具身 VLM Agent 在执行危险指令时的安全性。 | 解决现有安全基准范围窄且忽略感知规划执行全过程问题。 | 具身智能/安全基准 |
| 51 | http://arxiv.org/abs/2506.14866v2 | OS-Harm: A Benchmark for Measuring Safety of Computer Use Agents | 构建基准测量计算机使用 Agent 在误用及注入攻击下的安全性。 | 解决计算机使用 Agent 安全性被忽视及缺乏评估标准问题。 | 计算机使用/安全基准 |
| 52 | http://arxiv.org/abs/2506.14990v2 | MEAL: A Benchmark for Continual Multi-Agent Reinforcement Learning | 引入首个针对持续多 Agent 强化学习的 GPU 加速基准。 | 解决现有 CL 基准计算瓶颈及无法支持长任务序列问题。 | 持续学习/MARL 基准 |
| 53 | http://arxiv.org/abs/2506.15253v1 | RAS-Eval: A Comprehensive Benchmark for Security Evaluation of LLM Agents in Real-World Environments | 引入支持模拟与真实工具执行的综合安全评估基准。 | 解决动态环境中 Agent 安全评估缺乏标准化基准的问题。 | Agent 安全/真实环境评估 |
| 54 | http://arxiv.org/abs/2506.18824v2 | Understanding Software Engineering Agents: A Study of Thought-Action-Result Trajectories | 大规模实证研究 SE 代理思想 - 行动 - 结果轨迹 | 揭示成功与失败执行的行为模式与反模式 | 软件工程自动化代理 |
| 55 | http://arxiv.org/abs/2506.19724v1 | From Reproduction to Replication: Evaluating Research Agents with Progressive Code Masking | 引入 AutoExperiment 基准评估代理实现实验能力 | 解决缺乏评估代理从复现到复制科学想法基准 | AI 驱动科学实验代理 |
| 56 | http://arxiv.org/abs/2506.23329v1 | IR3D-Bench: Evaluating Vision-Language Model Scene Understanding as Agentic Inverse Rendering | "理解即创造"范式，通过编程渲染工具重建3D结构评估场景理解 | 传统基准仅测描述能力而非真正场景理解 | 视觉语言Agent场景理解评估 |
| 57 | http://arxiv.org/abs/2506.23774v1 | DABstep: Data Agent Benchmark for Multi-step Reasoning | 450+真实数据分析任务基准，测试代码处理与跨源推理能力 | 缺乏真实多步数据分析Agent评估基准 | 自主数据分析Agent能力评估 |
| 58 | http://arxiv.org/abs/2506.20664v1 | The Decrypto Benchmark for Multi-Agent Reasoning and Theory of Mind | 基于游戏的交互式心智理论基准，消除混淆因素 | 现有ToM基准范围窄、数据泄露、缺乏交互性 | 多Agent推理与心智理论评估 |
| 59 | http://arxiv.org/abs/2506.21252v1 | Agent-RewardBench: Towards a Unified Benchmark for Reward Modeling across Perception, Planning, and Safety in Real-World Multimodal Agents | 多模态Agent奖励建模统一基准，支持步骤级评估 | 缺乏针对Agent的奖励模型选择基准 | 真实世界多模态Agent |
| 60 | http://arxiv.org/abs/2506.21506v2 | Mind2Web 2: Evaluating Agentic Search with Agent-as-a-Judge | 130个长程任务基准，Agent-as-a-Judge评估框架 | 现有基准无法评估开放端Agent搜索 | 深度研究类Agent搜索系统 |
| 61 | http://arxiv.org/abs/2506.22598v2 | RExBench: Can coding agents autonomously implement AI research extensions? | 12个真实研究扩展实现任务基准，自动评估基础设施 | 缺乏评估Agent研究扩展能力的基准 | 编码Agent自主研究能力 |

[返回目录](#目录)

<a id="cat-10"></a>

## Agent可解释性与透明度

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2506.02068v1 | Enhancing Interpretability of Quantum-Assisted Blockchain Clustering via AI Agent-Based Qualitative Analysis | 两阶段框架结合定量聚类与AI Agent定性解释 | 量子增强聚类模型可解释性不足限制敏感领域应用 | 区块链金融欺诈检测 |
| 2 | http://arxiv.org/abs/2506.01334v1 | Enhancing Interpretable Image Classification Through LLM Agents and Conditional Concept Bottleneck Models | 提出CoCoBMs，动态调整概念库优化概念数量 | 概念瓶颈模型概念冗余或覆盖不足，评分机制局限 | 可解释图像分类系统 |
| 3 | http://arxiv.org/abs/2506.01344v1 | Follow the Flow: Fine-grained Flowchart Attribution with Neurosymbolic Agents | 提出FlowPathAgent神经符号Agent进行细粒度流程图归因 | VLM分析流程图时幻觉不存在连接和决策路径 | 物流、健康、工程流程图处理 |
| 4 | http://arxiv.org/abs/2506.06981v2 | Deep RL Needs Deep Behavior Analysis: Exploring Implicit Planning by Model-Free Agents in Open-Ended Environments | 应用神经伦理学工具分析 DRL 代理行为，揭示无模型代理的隐式规划结构。 | 解决深度强化学习代理行为分析 methods 不足的问题。 | 开放环境中的 DRL 代理 |
| 5 | http://arxiv.org/abs/2506.08192v1 | Interpreting Agent Behaviors in Reinforcement-Learning-Based Cyber-Battle Simulation Platforms | 简化状态动作空间并跟踪重要事件，分析攻防代理细粒度行为模式。 | 解决复杂网络防御挑战中代理成功与失败缺乏可解释性的问题。 | 网络战仿真平台代理分析 |
| 6 | http://arxiv.org/abs/2506.08311v1 | Understanding Software Engineering Agents Through the Lens of Traceability: An Empirical Study | 提出决策路径分类法，分析执行 trace，研究测试生成对补丁成功的影响。 | 解决软件工程中代理内部决策工作流缺乏理解及可靠性问题。 | 软件工程代理行为分析 |
| 7 | http://arxiv.org/abs/2506.12152v1 | Because we have LLMs, we Can and Should Pursue Agentic Interpretability | 提出 Agentic Interpretability 概念，通过多轮对话让 LLM 主动辅助人类理解其心智模型 | 解决传统解释性方法缺乏交互性且难以帮助人类理解超人类概念的问题 | LLM 可解释性与人类理解 |
| 8 | http://arxiv.org/abs/2506.09901v1 | "What are my options?": Explaining RL Agents with Diverse Near-Optimal Alternatives (Extended) | 提出 DNA 方法，优化策略产生定性多样轨迹以解释代理选项。 | 提供 RL 代理轨迹规划选项的可解释性，支持人类用户选择。 | 强化学习可解释性 |
| 9 | http://arxiv.org/abs/2506.13583v1 | Can you see how I learn? Human observers' inferences about Reinforcement Learning agents' learning processes | 研究人类观察者如何推断 RL Agent 的学习过程与目标。 | 解决 RL Agent 学习行为对人类不可解释导致反馈次优问题。 | 人机交互/RL 可解释性 |
| 10 | http://arxiv.org/abs/2506.14246v2 | Mxplainer: Explain and Learn Insights by Imitating Mahjong Agents | 通过参数化搜索算法学习并解释黑盒麻将 Agent 策略。 | 解决人类难以从高性能 AI Agent 中获取可操作洞察的问题。 | 游戏 AI/策略解释 |
| 11 | http://arxiv.org/abs/2506.20062v3 | Beyond Autocomplete: Designing CopilotLens Towards Transparent and Explainable AI Coding Agents | 重构代码完成为透明可解释交互，展示思维过程 | 解决 AI 代码助手建议无解释导致信任校准难 | AI 编程助手与开发者协作 |

[返回目录](#目录)

<a id="cat-11"></a>

## Agent规划与推理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2506.01273v1 | RAISE: Reasoning Agent for Interactive SQL Exploration | 统一框架整合模式链接、查询生成与迭代 refinement | 现有Text-to-SQL系统依赖复杂多阶段管道 | 自然语言数据库接口 |
| 2 | http://arxiv.org/abs/2506.01475v1 | PGPO: Enhancing Agent Reasoning via Pseudocode-style Planning Guided Preference Optimization | 提出PGPO方法，伪代码式规划引导偏好优化增强Agent推理 | 自然语言计划冗长低效，限制跨任务泛化能力 | 复杂交互式问题解决 |
| 3 | http://arxiv.org/abs/2506.04649v1 | Flex-TravelPlanner: A Benchmark for Flexible Planning with Language Agents | 动态约束引入与优先级竞争的多轮规划基准 | 静态单轮规划基准无法评估动态适应能力 | 旅行规划与动态任务 |
| 4 | http://arxiv.org/abs/2506.02918v2 | World Modelling Improves Language Model Agents | 提出动力学建模 DyMo，增强 LLM 状态预测能力，结合自验证采样减少幻觉。 | 解决状态环境中依赖重复试验不可行及 LLM 工具使用幻觉问题。 | LLM 工具使用与规划可靠性 |
| 5 | http://arxiv.org/abs/2506.07106v2 | "Theorem-of-Thought: A Multi-Agent Framework for Abductive, Deductive, and Inductive Reasoning in Language Models" | 建模三种推理模式的并行代理协作，利用贝叶斯信念传播评估一致性。 | 解决大模型推理过程脆弱且缺乏逻辑结构的问题。 | 语言模型符号与数值推理 |
| 6 | http://arxiv.org/abs/2506.07976v2 | Thinking vs. Doing: Agents that Reason by Scaling Test-Time Interaction | 提出测试时交互缩放，增加交互 horizon 以支持探索、回溯及动态重规划。 | 解决仅生成推理 trace 无法从环境获取新信息及适应行为的问题。 | 网页代理任务 |
| 7 | http://arxiv.org/abs/2506.08379v1 | Reinforce LLM Reasoning through Multi-Agent Reflection | 建模多轮 refinement 为 MDP，引入 DPSDP 算法训练 actor-critic 系统迭代 refine 答案。 | 解决现有 verify-and-improve 范式反馈空间受限及缺乏协调训练的问题。 | LLM 推理能力增强 |
| 8 | http://arxiv.org/abs/2506.10821v6 | VideoExplorer: Think With Videos For Agentic Long-Video Understanding | 提出 VideoExplorer 框架，通过迭代子问题 formulation 和时序定位实现长视频理解 | 解决长视频理解中细节丢失与任务特定感知不足的问题 | 长视频理解与推理任务 |
| 9 | http://arxiv.org/abs/2506.09171v1 | Improving LLM Agent Planning with In-Context Learning via Atomic Fact Augmentation and Lookahead Search | 利用原子事实增强与前瞻搜索，通过上下文学习提升代理规划能力。 | 解决复杂交互环境中代理适应新信息及利用过去经验效率低问题。 | 复杂交互任务规划 |
| 10 | http://arxiv.org/abs/2506.15624v1 | The Effect of State Representation on LLM Agent Behavior in Dynamic Routing Games | 统一自然语言状态表示框架，分析历史信息编码影响 | LLM 智能体在动态博弈中的状态表示模糊问题 | 动态路由博弈决策 |
| 11 | http://arxiv.org/abs/2506.16755v1 | Language-Informed Synthesis of Rational Agent Models for Grounded Theory-of-Mind Reasoning On-The-Fly | LIRAS 框架，多模态语言模型构建符号表示 | 社会推理需整合多模态信息与情境特定推断 | 认知科学社会推理任务 |
| 12 | http://arxiv.org/abs/2506.17419v1 | UProp: Investigating the Uncertainty Propagation of LLMs in Multi-Step Agentic Decision-Making | 信息论框架分解不确定性，UProp 估计外在不确定性 | 多步决策场景中 LLM 不确定性量化未被探索 | 安全关键应用 sequential 决策 |
| 13 | http://arxiv.org/abs/2506.12928v1 | Scaling Test-time Compute for LLM Agents | 系统探索测试时计算缩放策略以提升语言 Agent 推理能力。 | 解决 Agent 在复杂任务中推理效率与效果平衡问题。 | 语言模型 Agent/推理任务 |
| 14 | http://arxiv.org/abs/2506.18071v2 | MUPA: Towards Multi-Path Agentic Reasoning for Grounded Video Question Answering | 多路径代理推理统一视频接地与问答，含反思代理 | 解决多模态模型依赖语言先验导致接地差问题 | 接地视频问答任务 |
| 15 | http://arxiv.org/abs/2506.18559v1 | T-CPDL: A Temporal Causal Probabilistic Description Logic for Developing Logic-RAG Agent | 扩展描述逻辑含时间间隔、因果与概率标注 | 解决 LLM 结构化推理涉及时序因果概率的局限 | 逻辑检索增强生成代理 |
| 16 | http://arxiv.org/abs/2506.18957v1 | A Comment On "The Illusion of Thinking": Reframing the Reasoning Cliff as an Agentic Gap | 论证性能崩溃源于系统级约束而非推理缺陷 | 解决静态文本评估范式对推理能力误判 | 大推理模型能力评估 |
| 17 | http://arxiv.org/abs/2506.19592v2 | Adaptive Domain Modeling with Language Models: A Multi-Agent Approach to Task Planning | 多智能体协作生成适应领域模型与目标规格 | 解决复杂任务无需手动定义环境模型的规划 | 机器人任务规划与虚拟环境 |
| 18 | http://arxiv.org/abs/2506.19923v5 | Prover Agent: An Agent-Based Framework for Formal Mathematical Proofs | 整合非形式推理 LLM、形式证明器与反馈生成引理 | 解决自动定理证明中策略发现与引理生成难题 | 形式数学证明自动化 |
| 19 | http://arxiv.org/abs/2506.23576v1 | Thought-Augmented Planning for LLM-Powered Interactive Recommender Agent | 思维模式蒸馏强化规划，多Agent系统分解用户需求 | 现有推荐Agent难以处理模糊/复杂用户意图 | 交互式个性化推荐系统 |
| 20 | http://arxiv.org/abs/2507.00210v1 | LineRetriever: Planning-Aware Observation Reduction for Web Agents | 利用LM识别检索与未来导航步骤最相关观察行，考虑规划视野 | Web页面上下文超出模型限制且传统检索丢失状态信息 | Web导航Agent |
| 21 | http://arxiv.org/abs/2506.21924v1 | SPAZER: Spatial-Semantic Progressive Reasoning Agent for Zero-shot 3D Visual Grounding | 空间-语义渐进推理框架，3D-2D联合决策 | 现有方法偏重空间或语义单一理解 | 零样本3D视觉定位 |

[返回目录](#目录)

<a id="cat-12"></a>

## Agent仿真与社会模拟

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2506.01332v1 | An Empirical Study of Group Conformity in Multi-Agent Systems | 模拟2500+辩论揭示LLM Agent群体一致性类似人类行为 | 多Agent LLM互动中社会争议议题的偏见涌现与传播 | 在线讨论环境、舆论模拟 |
| 2 | http://arxiv.org/abs/2506.01839v2 | Beyond Static Responses: Multi-Agent LLM Systems as a New Paradigm for Social Science Research | 提出六层级框架理解LLM Agent在社会科学研究中的多样化应用 | 从静态工具到完全Agent系统的转型缺乏方法论边界澄清 | 社会科学研究范式 |
| 3 | http://arxiv.org/abs/2506.04699v1 | Empowering Economic Simulation for Massively Multiplayer Online Games through Generative Agent-Based Modeling | LLM驱动具有角色扮演与推理能力的经济Agent | 传统ABM缺乏人类经济行为的可信模拟 | MMO游戏经济仿真 |
| 4 | http://arxiv.org/abs/2506.04849v1 | Towards a Multi-Agent Simulation of Cyber-attackers and Cyber-defenders Battles | 基于马尔可夫模型的网络攻防多Agent仿真框架 | 复杂协调网络攻击的防御策略评估 | 网络安全攻防仿真 |
| 5 | http://arxiv.org/abs/2506.05981v2 | CrimeMind: Simulating Urban Crime with Multi-Modal LLM Agents | 整合常规活动理论的多模态LLM城市犯罪仿真 | 传统ABM与深度学习缺乏认知灵活性与可解释性 | 城市犯罪建模与政策评估 |
| 6 | http://arxiv.org/abs/2506.12078v1 | Modeling Earth-Scale Human-Like Societies with One Billion Agents | Light Society框架支持十亿级LLM Agent社会仿真 | 传统ABM无法捕捉人类复杂性与LLM扩展挑战 | 大规模社会行为仿真 |
| 7 | http://arxiv.org/abs/2507.19495v1 | Simulating Human Behavior with the Psychological-mechanism Agent: Integrating Feeling, Thought, and Action | 提出 PSYA 框架，基于认知三角模拟情感、思维与行动，复现心理实验结果。 | 解决现有生成式智能体情感建模简化导致行为真实性有限的问题。 | 人类行为仿真与心理实验 |
| 8 | http://arxiv.org/abs/2506.03532v2 | GA-S$^3$: Comprehensive Social Network Simulation with Group Agents | 利用群智能体模拟具有相似行为的个体集合，降低大规模网络模拟计算成本。 | 解决社交网络涉及数十亿个体及其交互难以准确反映现实复杂性的问题。 | 社会网络仿真与群体行为 |
| 9 | http://arxiv.org/abs/2506.03543v2 | CogniPair: From LLM Chatbots to Conscious AI Agents -- GNWT-Based Multi-Agent Digital Twins for Social Pairing -- Dating & Hiring Applications | 实现全局工作空间理论，创建情感记忆等子智能体，用于约会与招聘匹配。 | 解决当前 LLM 智能体缺乏真实人类心理过程难以作为数字孪生的问题。 | 社交配对与人力资源技术 |
| 10 | http://arxiv.org/abs/2506.07842v3 | Simulating nationwide coupled disease and fear spread in an agent-based model | 构建动态基于代理模型，耦合疾病传播与恐惧传播，捕捉个体级交互。 | 解决理解疾病爆发中认知、行为与疾病动态共演化反馈的问题。 | 传染病传播与社会行为模拟 |
| 11 | http://arxiv.org/abs/2506.11773v4 | AgentSense: Virtual Sensor Data Generation Using LLM Agents in Simulated Home Environments | 提出 AgentSense 管道，利用 LLM 指导具身 Agent 在模拟家中生成虚拟传感器数据 | 解决人类活动识别系统缺乏大规模多样化标注数据集的问题 | 智能家居与人类活动识别 |
| 12 | http://arxiv.org/abs/2506.11825v1 | Revealing Political Bias in LLMs through Structured Multi-Agent Debate | 利用结构化多 Agent 辩论框架，研究 LLM 类型与性别属性对政治偏见的影响 | 解决 LLM 在辩论中的政治偏见与交互动态未被充分探索的问题 | 社会行为模拟与偏见研究 |
| 13 | http://arxiv.org/abs/2506.12331v1 | IndoorWorld: Integrating Physical Task Solving and Social Simulation in A Heterogeneous Multi-Agent Environment | 提出 IndoorWorld 环境，紧密整合物理任务解决与社会动态以模拟建筑 occupant | 解决现有虚拟环境要么简化社会动态要么缺乏物理 grounding 的问题 | 建筑设计与居住者行为模拟 |
| 14 | http://arxiv.org/abs/2506.12664v2 | Behavioral Generative Agents for Energy Operations | 利用生成式 Agent 模拟动态电价下客户序列决策，发现 Agent 能揭示传统模型外的行为模式 | 解决能源运营中消费者行为建模因不确定性及数据limited 而困难的问题 | 能源运营与消费者行为研究 |
| 15 | http://arxiv.org/abs/2506.13783v2 | Infected Smallville: How Disease Threat Shapes Sociality in LLM Agents | 利用生成代理建模实验测试疾病威胁如何影响代理社会参与度。 | 探索传染病威胁对生成代理社会行为及互动模式的影响机制。 | 社会动力学仿真 |
| 16 | http://arxiv.org/abs/2506.15866v1 | Understanding Online Polarization Through Human-Agent Interaction in a Synthetic LLM-Based Social Network | 可控社交网络仿真，人类与 LLM 代理互动实验 | 在线极化环境影响用户感知的因果证据缺失 | 社交媒体动态与舆论研究 |
| 17 | http://arxiv.org/abs/2506.16010v1 | SimuPanel: A Novel Immersive Multi-Agent System to Simulate Interactive Expert Panel Discussion | 宿主 - 专家架构，3D 沉浸式环境模拟专家讨论 | 现实专家小组讨论 inaccessible 与互动深度不足 | 多媒体学习与专家观点模拟 |
| 18 | http://arxiv.org/abs/2506.16696v1 | Interpretable Low-Dimensional Modeling of Spatiotemporal Agent States for Decision Making in Football Tactics | 低维规则模型捕捉战术，XGBoost 预测传球成功 | 足球战术分析计算昂贵与缺乏可解释性 | 足球战术决策支持 |
| 19 | http://arxiv.org/abs/2506.13599v1 | CAMS: A CityGPT-Powered Agentic Framework for Urban Human Mobility Simulation | 利用 CityGPT 驱动 Agent 框架模拟城市人类移动轨迹。 | 解决传统移动模拟缺乏城市空间常识及个体模式整合问题。 | 城市计算/移动模拟 |
| 20 | http://arxiv.org/abs/2506.21618v1 | TrajTok: Technical Report for 2025 Waymo Open Sim Agents Challenge | 轨迹 tokenizer 结合数据驱动与规则方法 | 解决行为生成模型覆盖度、对称性与鲁棒性问题 | 自动驾驶仿真智能体挑战 |
| 21 | http://arxiv.org/abs/2506.23306v3 | GATSim: Urban Mobility Simulation with Generative Agents | 生成式Agent模拟城市移动性，含心理记忆系统与终身学习机制 | 传统基于规则仿真无法捕捉人类出行决策复杂性 | 城市交通规划与移动性仿真 |
| 22 | http://arxiv.org/abs/2506.20400v1 | A Visualization Framework for Exploring Multi-Agent-Based Simulations Case Study of an Electric Vehicle Home Charging Ecosystem | 模块化Python仪表板框架，支持多层级探索与根因分析 | EV充电生态系统仿真中 emergent behavior难以检测解释 | 电动汽车家庭充电生态系统研究 |
| 23 | http://arxiv.org/abs/2506.21805v1 | CitySim: Modeling Urban Behaviors and City Dynamics with Large-Scale LLM-Driven Agent Simulation | 递归价值驱动方法生成真实日常计划 | 传统规则无法模拟细微意图和适应行为 | 城市行为与动力学模拟 |
| 24 | http://arxiv.org/abs/2506.21974v3 | Don't Trust Generative Agents to Mimic Communication on Social Networks Unless You Benchmarked their Empirical Realism | 形式化社交网络模拟框架，强调实证真实性验证 | 生成式Agent模拟人类行为的有效性存疑 | 社交网络通信模拟研究 |
| 25 | http://arxiv.org/abs/2506.22318v1 | Agent-based modeling and the sociology of money: some suggestions for refining monetary theory using social simulation | 结合社会学与形式方法 refine 货币理论 | 现有货币涌现Agent模型发现有限 | 货币理论与社会模拟 |

[返回目录](#目录)

<a id="cat-13"></a>

## Agent记忆与知识管理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2506.02158v1 | Reflection-Based Memory For Web navigation Agents | 提出ReAP系统，利用自我反思 leveraging 成功和失败经验 | 当前网页导航Agent无过去经验记忆，导致重复错误 | 网页导航任务 |
| 2 | http://arxiv.org/abs/2506.05813v2 | MAPLE: Multi-Agent Adaptive Planning with Long-Term Memory for Table Reasoning | 四组件多Agent框架集成长期记忆与经验复用 | 表格问答缺乏错误检测与经验积累机制 | 表格推理与问答 |
| 3 | http://arxiv.org/abs/2506.06254v1 | PersonaAgent: When Large Language Model Agents Meet Personalization at Test Time | 个性化记忆与动作模块实现测试时用户偏好对齐 | 当前LLM Agent缺乏响应用户差异化需求的能力 | 个性化Agent服务 |
| 4 | http://arxiv.org/abs/2506.07398v2 | G-Memory: Tracing Hierarchical Memory for Multi-Agent Systems | 引入 G-Memory，通过三层图层级管理多智能体交互，支持双向记忆遍历。 | 解决多智能体系统记忆架构简单且缺乏跨试验定制的问题。 | 多智能体系统记忆管理 |
| 5 | http://arxiv.org/abs/2506.12607v1 | Towards Building General Purpose Embedding Models for Industry 4.0 Agents | 构建 Industry 4.0 领域嵌入模型，结合 LLM 查询增强与 ReAct Agent 支持资产维护决策 | 解决语言模型对资产维护理解不足导致工程师决策指导有限的问题 | 工业 4.0 资产维护与专家支持 |
| 6 | http://arxiv.org/abs/2506.15841v2 | MEM1: Learning to Synergize Memory and Reasoning for Efficient Long-Horizon Agents | 端到端 RL 框架，恒定内存更新内部状态，丢弃冗余信息 | 长程交互中内存无界增长与推理性能下降 | 多轮交互与长程任务代理 |
| 7 | http://arxiv.org/abs/2506.17338v2 | PBFT-Backed Semantic Voting for Multi-Agent Memory Pruning | 共遗忘协议，语义投票与 PBFT 共识修剪记忆 | 分布式记忆同步难与过时数据积累问题 | 复杂动态环境多智能体系统 |
| 8 | http://arxiv.org/abs/2506.17001v5 | PersonalAI: A Systematic Comparison of Knowledge Graph Storage and Retrieval Approaches for Personalized LLM agents | 灵活外部记忆框架，混合图设计与多种检索机制 | 个性化语言模型缺乏结构化记忆与扩展性 | 个性化 LLM 智能体 |
| 9 | http://arxiv.org/abs/2506.13246v1 | On Immutable Memory Systems for Artificial Agents: A Blockchain-Indexed Automata-Theoretic Framework Using ECDH-Keyed Merkle Chains | 提出基于区块链的不可变记忆系统确保 Agent 推理可验证。 | 解决传统 AI 记忆易被篡改及缺乏历史可追溯性问题。 | 高 Assurance 系统/Agent 记忆 |
| 10 | http://arxiv.org/abs/2506.14852v2 | Agentic Plan Caching: Test-Time Memory for Fast and Cost-Efficient LLM Agents | 提出测试时记忆机制缓存并重用 Agent 计划模板。 | 解决 Agent 应用因重复规划导致的高成本与高延迟问题。 | LLM 服务/计划缓存 |
| 11 | http://arxiv.org/abs/2506.18158v1 | Chain-of-Memory: Enhancing GUI Agents for Cross-Application Navigation | 显式建模短长期记忆，捕获动作描述与屏幕信息 | 解决跨应用任务中任务状态理解与关键信息丢失 | 跨应用 GUI 导航任务 |
| 12 | http://arxiv.org/abs/2506.23485v1 | State and Memory is All You Need for Robust and Reliable AI Agents | 有限状态自动机记忆+动态Agent构建，消除手动提示工程需求 | LLM在科学工作流中记忆/规划/工具集成受限 | 科学研究自动化工作流 |
| 13 | http://arxiv.org/abs/2506.22815v1 | Memory as a Service (MaaS): Rethinking Contextual Memory as Service-Oriented Modules for Collaborative Agents | 提出记忆即服务设计视角，解耦记忆为可调用服务 | 当前记忆设计形成记忆孤岛阻碍跨实体协作 | 协作Agent系统 |
| 14 | http://arxiv.org/abs/2506.22852v1 | Knowledge Augmented Finetuning Matters in both RAG and Agent Based Dialog Systems | 提出知识增强微调(KAFT)方法 | LLM难以有效利用检索知识进行响应生成 | 知识密集型对话系统 |

[返回目录](#目录)

<a id="cat-14"></a>

## 具身智能Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2506.04217v2 | OWMM-Agent: Open World Mobile Manipulation With Multi-modal Agentic Data Synthesis | 首个移动操作专用基础模型与多模态数据合成管线 | 开放世界移动操作的泛化与领域迁移问题 | 机器人与移动操作 |
| 2 | http://arxiv.org/abs/2506.04606v1 | SmartAvatar: Text- and Image-Guided Human Avatar Generation with VLM AI Agents | VLM驱动的自主验证循环3D头像生成框架 | 头像生成的身份控制与动画就绪问题 | 3D内容创作与动画 |
| 3 | http://arxiv.org/abs/2506.03546v1 | From Virtual Agents to Robot Teams: A Multi-Robot Framework Evaluation in High-Stakes Healthcare Context | 在模拟急诊科压力测试分层多智能体机器人团队，提出设计指南增强鲁棒性。 | 解决当前框架忽略物理约束如空间上下文与机器人能力的问题。 | 高风险医疗场景多机器人系统 |
| 4 | http://arxiv.org/abs/2506.03613v1 | Training Cross-Morphology Embodied AI Agents: From Practical Challenges to Theoretical Foundations | 形式化异质具身智能体训练问题，证明其为 PSPACE-complete，探索集体适应。 | 解决当前 RL 管道在形态多样性下因序列训练约束等失效的问题。 | 跨形态具身 AI 策略训练 |
| 5 | http://arxiv.org/abs/2506.07223v1 | LLM-Enhanced Rapid-Reflex Async-Reflect Embodied Agent for Real-Time Decision-Making in Dynamically Changing Environments | 提出时间转换机制及 RRARA 代理，结合轻量 LLM 与规则基实现即时反应。 | 解决动态高风险场景下智能体决策延迟的关键问题。 | 动态变化环境中的实时决策 |
| 6 | http://arxiv.org/abs/2506.07509v1 | Taking Flight with Dialogue: Enabling Natural Language Control for PX4-based Drone Agent | 集成 PX4 飞控、ROS 2 及本地模型，实现开源无人机自然语言控制框架。 | 解决空中机器人自然语言控制研究不足及闭源模型依赖问题。 | 无人机自然语言控制 |
| 7 | http://arxiv.org/abs/2506.08296v2 | HiBerNAC: Hierarchical Brain-emulated Robotic Neural Agent Collective for Disentangling Complex Manipulation | 提出分层脑仿真机器人神经代理集体，结合 VLA 规划与神经启发反射机制。 | 解决复杂操作任务中持久上下文记忆及多代理协调受限的问题。 | 复杂机器人操作任务 |
| 8 | http://arxiv.org/abs/2506.11127v3 | UITron-Speech: Towards Automated GUI Agents Based on Speech Instructions | 提出 UITron-Speech，首个端到端处理语音指令与截图的 GUI 代理。 | 解决文本指令限制 GUI 代理无障碍性及便利性的问题。 | 语音驱动 GUI 交互 |
| 9 | http://arxiv.org/abs/2506.08972v1 | Atomic-to-Compositional Generalization for Mobile Agents with A New Benchmark and Scheduling System | 提出 UI-NEXUS 基准与 AGENT-NEXUS 调度系统，支持组合式移动任务。 | 解决移动代理在组合式任务上泛化能力不足及执行效率低问题。 | 移动设备任务自动化 |
| 10 | http://arxiv.org/abs/2506.09373v2 | LPO: Towards Accurate GUI Agent Interaction via Location Preference Optimization | 提出 LPO，利用位置数据优化交互偏好，引入动态位置奖励函数。 | 解决 GUI 代理空间定位感知有限及位置准确性评估失效问题。 | GUI 交互定位 |
| 11 | http://arxiv.org/abs/2506.10387v1 | Mirage-1: Augmenting and Updating GUI Agent with Hierarchical Multimodal Skills | 提出 Mirage-1，利用分层多模态技能模块及 SA-MCTS 算法增强 GUI 代理。 | 解决 GUI 代理在线长程任务中知识不足及离线在线领域 gap 问题。 | 跨平台 GUI 自动化 |
| 12 | http://arxiv.org/abs/2506.15677v3 | Embodied Web Agents: Bridging Physical-Digital Realms for Integrated Agent Intelligence | 统一仿真平台整合 3D 环境与 Web 接口，跨域基准 | 物理与数字智能割裂，缺乏跨域协同能力 | 烹饪、导航等跨域任务 |
| 13 | http://arxiv.org/abs/2506.15868v1 | CooperRisk: A Driving Risk Quantification Pipeline with Multi-Agent Cooperative Perception and Prediction | V2X enabled 风险量化管道，多代理协作感知预测 | 单车感知受限与多代理交互风险不可解释 | 自动驾驶与车联网安全 |
| 14 | http://arxiv.org/abs/2506.16748v1 | A Scalable Post-Processing Pipeline for Large-Scale Free-Space Multi-Agent Path Planning with PiBT | 混合规划框架，PiBT 结合安全感知路径平滑 | 大规模自由空间多代理路径规划扩展性差 | 机器人系统与导航 |
| 15 | http://arxiv.org/abs/2506.15065v2 | HEAL: An Empirical Study on Hallucinations in Embodied Agents Driven by Large Language Models | 系统研究 LLM 驱动具身 Agent 在长程任务中的幻觉问题。 | 解决具身 Agent 因场景任务不一致导致导航错误的问题。 | 具身智能/幻觉研究 |
| 16 | http://arxiv.org/abs/2506.18448v2 | GraspMAS: Zero-Shot Language-driven Grasp Detection with Multi-Agent System | 三智能体系统规划、编码与观察，零样本语言驱动抓取 | 解决复杂指令解释与密集 clutter 环境抓取难题 | 机器人语言驱动抓取检测 |
| 17 | http://arxiv.org/abs/2506.18678v2 | MCN-SLAM: Multi-Agent Collaborative Neural SLAM with Hybrid Implicit Neural Scene Representation | 混合场景表示、分布式跟踪与在线蒸馏融合子地图 | 解决隐式 SLAM 单代理限制与大规模场景困难 | 多智能体协同神经 SLAM |
| 18 | http://arxiv.org/abs/2506.18885v1 | GRAND-SLAM: Local Optimization for Globally Consistent Large-Scale Multi-Agent Gaussian SLAM | 隐式跟踪模块结合环路闭合与位姿图优化 | 解决大规模户外环境多代理高斯 SLAM 未探索问题 | 大规模多智能体户外重建 |
| 19 | http://arxiv.org/abs/2506.24019v1 | Ella: Embodied Social Agents with Lifelong Memory | 具身社交Agent含命名语义记忆+时空情景记忆，3D开放世界终身学习 | 具身Agent缺乏有效长期多模态记忆系统 | 3D开放世界具身智能体 |
| 20 | http://arxiv.org/abs/2506.22355v3 | Embodied AI Agents: Modeling the World | 提出世界模型对具身Agent推理规划的核心作用 | 具身Agent环境理解与预测能力不足 | 虚拟化身、可穿戴设备、机器人 |

[返回目录](#目录)

<a id="cat-15"></a>

## 低代码/无代码Agent平台

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2506.10622v3 | SDialog: A Python Toolkit for End-to-End Agent Building, User Simulation, Dialog Generation, and Evaluation | 提出 SDialog 工具包，统一对话生成评估及可解释性于端到端框架。 | 支持研究人员更系统地构建基准及理解对话系统。 | 对话代理构建与分析 |

[返回目录](#目录)
