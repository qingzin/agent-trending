# AI agents 2025年5月学术分类汇总

共收录 596 篇论文，按研究方向分类整理如下。

## 目录

- [Agent学习与自进化（48篇）](#cat-01)
- [基于Agent的应用系统（94篇）](#cat-02)
- [人机协作Agent（23篇）](#cat-03)
- [Agent工具使用与环境交互（20篇）](#cat-04)
- [Agent记忆与知识管理（17篇）](#cat-05)
- [Agent评测与基准（56篇）](#cat-06)
- [Agent可解释性与透明度（8篇）](#cat-07)
- [具身智能Agent（22篇）](#cat-08)
- [多Agent协作与通信（61篇）](#cat-09)
- [多Agent强化学习（57篇）](#cat-10)
- [Agent架构与框架设计（70篇）](#cat-11)
- [Agent安全与对齐（69篇）](#cat-12)
- [Agent仿真与社会模拟（27篇）](#cat-13)
- [Agent规划与推理（23篇）](#cat-14)
- [其他（1篇）](#cat-15)

<a id="cat-01"></a>

## Agent学习与自进化

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2505.00234v3 | Self-Generated In-Context Examples Improve LLM Agents for Sequential Decision-Making Tasks | 自生成轨迹数据库作为上下文示例，无需人工干预实现Agent自主改进 | 减少任务特定知识工程，提升顺序决策任务性能 | 通用顺序决策任务（ALFWorld、Wordcraft、InterCode-SQL） |
| 2 | http://arxiv.org/abs/2505.03792v2 | Towards Efficient Online Tuning of VLM Agents via Counterfactual Soft Reinforcement Learning | CoSo利用反事实推理动态评估token因果影响，优先探索关键token | VLM Agent在线RL探索空间爆炸，文本动作空间开放 | 动态环境中的VLM Agent（Android控制、卡牌游戏、具身AI） |
| 3 | http://arxiv.org/abs/2505.02156v5 | Adaptive Social Learning via Mode Policy Optimization for Language Agents | ASL框架+AMPO算法学习上下文感知模式适应与推理 | 现有方法推理深度固定，token消耗大且社会行为不灵活 | 动态社会交互（谈判、协作） |
| 4 | http://arxiv.org/abs/2505.07184v1 | Structural Entropy Guided Agent for Detecting and Repairing Knowledge Deficiencies in LLMs | 提出SENATOR框架，用结构熵量化知识图谱路径不确定性，生成针对性合成数据 | LLM在知识密集型领域事实精度不足、合成数据冗余问题 | 医学与科学研究领域 |
| 5 | http://arxiv.org/abs/2505.07911v1 | Combining Bayesian Inference and Reinforcement Learning for Agent Decision Making: A Review | 系统综述贝叶斯推理与强化学习结合的五类方法及其在六类复杂RL问题中的应用 | 缺乏对贝叶斯推理在Agent决策中应用的系统性理解 | 机器人/仿真Agent决策 |
| 6 | http://arxiv.org/abs/2505.07757v2 | Emotion-Gradient Metacognitive RSI (Part I): Theoretical Foundations and Single-Agent Architecture | 提出EG-MRSI框架，整合内省元认知、情感内在动机与递归自我修改 | 开放-ended安全AGI的理论基础与单Agent架构问题 | 通用人工智能系统 |
| 7 | http://arxiv.org/abs/2505.07773v4 | Agent RL Scaling Law: Agent RL with Spontaneous Code Execution for Mathematical Problem Solving | 发现Agent RL训练中代码执行频率、响应长度与任务准确率的可量化缩放关系 | LLM在数学推理中缺乏精确可验证计算能力的问题 | 数学问题求解 |
| 8 | http://arxiv.org/abs/2505.03947v1 | Frog Soup: Zero-Shot, In-Context, and Sample-Efficient Frogger Agents | 利用推理 LLM 零样本玩 Atari 游戏并引导传统 RL | 解决 RL 游戏智能体训练慢、成本高且泛化差的问题 | 游戏智能体与 RL 引导 |
| 9 | http://arxiv.org/abs/2505.03973v1 | Divide, Optimize, Merge: Fine-Grained LLM Agent Optimization at Scale | 细粒度优化框架，分治合并大任务避免上下文溢出 | 解决大数据集上 LLM 智能体优化上下文溢出问题 | 大规模智能体系统优化 |
| 10 | http://arxiv.org/abs/2505.04424v1 | RLMiniStyler: Light-weight RL Style Agent for Arbitrary Sequential Neural Style Generation | 基于 RL 策略迭代引导风格迁移，实现模型轻量化 | 解决任意风格迁移计算成本高且多样性不足问题 | 神经风格迁移生成 |
| 11 | http://arxiv.org/abs/2505.10330v1 | Efficient Adaptation of Reinforcement Learning Agents to Sudden Environmental Change | 提出优先探索采样与结构化知识选择性保留机制 | 解决 RL 代理在环境突变时适应效率低及灾难性遗忘问题 | 动态环境自主决策系统 |
| 12 | http://arxiv.org/abs/2505.10978v3 | Group-in-Group Policy Optimization for LLM Agent Training | 提出 GiGPO 算法，两级结构实现细粒度信用分配 | 解决多轮 LLM 代理训练中信用分配难及稀疏奖励问题 | LLM 代理强化学习训练 |
| 13 | http://arxiv.org/abs/2505.13504v1 | An agentic system with reinforcement-learned subsystem improvements for parsing form-like documents | 利用 RL 驱动元提示 Agent，从过去错误中学习改进提取 | 解决单体 LLM 提取表单数据缺乏系统改进及不确定性问题 | 表单文档信息提取 |
| 14 | http://arxiv.org/abs/2505.13188v2 | When a Reinforcement Learning Agent Encounters Unknown Unknowns | 提出具有增长意识的 episodic MDP 模型与非信息值扩展 | 解决 RL 智能体遭遇未知状态时的价值函数初始化问题 | 强化学习智能体 |
| 15 | http://arxiv.org/abs/2505.13820v3 | Structured Agent Distillation for Large Language Model | 提出结构化智能体蒸馏，分段对齐推理与动作 | 解决大 LLM 智能体部署成本高与模型尺寸大的问题 | 大型语言模型智能体 |
| 16 | http://arxiv.org/abs/2505.13909v2 | Efficient Agent Training for Computer Use | 引入 PC Agent-E 框架，减少对人类演示数据的依赖 | 解决高质量轨迹数据扩展是计算机使用智能体开发的瓶颈 | 计算机使用智能体 |
| 17 | http://arxiv.org/abs/2505.14069v3 | Process vs. Outcome Reward: Which is Better for Agentic RAG Reinforcement Learning | 引入利用细粒度过程级奖励改进训练稳定性的 ReasonRAG | 解决结果监督智能体 RAG 方法探索效率低与奖励稀疏问题 | 检索增强生成系统 |
| 18 | http://arxiv.org/abs/2505.14146v2 | s3: You Don't Need That Much Data to Train a Search Agent via RL | 提出轻量级框架 s3，解耦搜索者与生成者并用 RL 训练 | 解决现有方法优化检索忽略下游效用或微调整个 LLM 问题 | 搜索智能体 |
| 19 | http://arxiv.org/abs/2505.14163v1 | DSMentor: Enhancing Data Science Agents with Curriculum Learning and Online Knowledge Accumulation | 开发利用课程学习与在线知识积累的推理时优化框架 | 解决现有研究忽略推理时问题解决顺序重要性的问题 | 数据科学任务 |
| 20 | http://arxiv.org/abs/2505.14246v1 | Visual Agentic Reinforcement Fine-Tuning | 强调视觉智能体强化微调对启用灵活自适应推理能力的有效性 | 解决开源 LVLM 多模态智能体能力与基准探索不足问题 | 大型视觉语言模型 |
| 21 | http://arxiv.org/abs/2505.11807v2 | Retrospex: Language Agent Meets Offline Reinforcement Learning Critic | 结合 LLM 动作似然与离线 RL Critic 估计值，动态重评分动作。 | 现有 LLM 智能体框架未充分利用过去经验进行改进。 | 需要环境交互的任务（如 ScienceWorld） |
| 22 | http://arxiv.org/abs/2505.11821v2 | Reinforcing Multi-Turn Reasoning in LLM Agents via Turn-Level Reward Design | 设计轮次级奖励，扩展 GRPO 与 PPO 至多轮变体，实现细粒度信用分配。 | 多轮 RL 算法依赖稀疏结果奖励，缺乏密集中间信号限制复杂推理。 | 多轮推理增强搜索智能体 |
| 23 | http://arxiv.org/abs/2505.12299v3 | MobileIPL: Enhancing Mobile Agents Thinking Process via Iterative Preference Learning | 迭代偏好学习构建 CoaT-tree，反向传播反馈推导 T-DPO 对。 | 多样 CoaT 轨迹稀缺，现有自训练忽略中间步骤正确性或依赖昂贵标注。 | 移动 GUI 智能体推理过程 |
| 24 | http://arxiv.org/abs/2505.12370v2 | Enhancing Visual Grounding for GUI Agents via Self-Evolutionary Reinforcement Learning | RL 框架含种子数据策划、密集策略梯度与自进化微调机制。 | 传统 SFT 需大量数据且泛化弱，复杂环境 grounding 挑战大。 | 高分辨率复杂 GUI 环境智能体 |
| 25 | http://arxiv.org/abs/2505.12493v3 | GUI-Shift: Enhancing VLM-Based GUI Agents through Self-supervised Reinforcement Learning | 提出 K-step GUI Transition 自监督任务，结合规则优化与数据过滤。 | 训练有效 VLM 依赖大规模标注数据，收集 labor-intensive 且 error-prone。 | GUI 任务自动化与 grounding |
| 26 | http://arxiv.org/abs/2505.15117v1 | An Empirical Study on Reinforcement Learning for Reasoning-Search Interleaved LLM Agents | 实证研究 RL 训练搜索 Agent 的关键因素，如奖励公式与 LLM 选择 | 解决搜索 Agent 中 RL 最优设计尚未完全理解的问题 | 现实世界问题求解 Agent |
| 27 | http://arxiv.org/abs/2505.15251v2 | Loss-Guided Auxiliary Agents for Overcoming Mode Collapse in GFlowNets | 提出 LGGFN，利用辅助 Agent 直接由主模型训练损失驱动探索 | 解决 GFlowNets 实践中易陷入模式坍塌与探索效率低问题 | 生成流网络多样性采样 |
| 28 | http://arxiv.org/abs/2505.15277v2 | Web-Shepherd: Advancing PRMs for Reinforcing Web Agents | 提出首个 Web 导航过程奖励模型 (PRM)，构建 WebPRM 数据集 | 解决缺乏专门用于 Web 导航训练与测试的奖励模型问题 | Web 导航智能体强化学习 |
| 29 | http://arxiv.org/abs/2505.15810v2 | GUI-G1: Understanding R1-Zero-Like Training for Visual Grounding in GUI Agents | 提出 Fast Thinking Template 与 box 大小约束，优化 GUI  grounding RL | 解决盲目应用通用 RL 导致 GUI grounding 任务性能下降问题 | 图形用户界面 Agent |
| 30 | http://arxiv.org/abs/2505.16282v1 | ARPO:End-to-End Policy Optimization for GUI Agents with Experience Replay | 提出 ARPO，增强 GRPO 与回放缓冲区，复用成功经验优化策略 | 解决 GUI Agent 长视野动作序列优化中稀疏奖励与高 rollout 成本问题 | 图形用户界面 Agent 训练 |
| 31 | http://arxiv.org/abs/2505.16421v2 | WebAgent-R1: Training Web Agents via End-to-End Multi-Turn Reinforcement Learning | 提出 WebAgent-R1，通过异步生成轨迹与二元奖励端到端训练 | 解决多 turn 交互 Web Agent 长视野决策训练挑战问题 | Web 导航 Agent 训练 |
| 32 | http://arxiv.org/abs/2505.17612v2 | Distilling LLM Agent into Small Models with Retrieval and Code Tools | 代理蒸馏框架，将 LLM 代理行为迁移至小模型 | 解决小模型在复杂推理任务中幻觉与能力不足问题 | 资源受限下的推理任务 |
| 33 | http://arxiv.org/abs/2505.18121v1 | ProgRM: Build Better GUI Agents with Progress Rewards | 进度奖励模型，为在线训练提供密集中间奖励 | 解决 GUI 代理训练数据稀缺与奖励标注困难问题 | GUI 代理强化学习训练 |
| 34 | http://arxiv.org/abs/2505.18646v1 | SEW: Self-Evolving Agentic Workflows for Automated Code Generation | 提出自进化框架，自动生成并优化多智能体工作流，无需手工设计。 | 现有代码生成工作流依赖手工设计，难以适应不同问题。 | 自动化代码生成 |
| 35 | http://arxiv.org/abs/2505.20023v1 | Training LLM-Based Agents with Synthetic Self-Reflected Trajectories and Partial Masking | 合成自反思轨迹+部分掩码策略，提升智能体纠错能力 | 专家轨迹训练存在性能瓶颈和错误传播 | 通用任务型智能体训练 |
| 36 | http://arxiv.org/abs/2505.20128v1 | Iterative Self-Incentivization Empowers Large Language Models as Agentic Searchers | 广义EM算法+自激励循环，迭代学习自身生成的搜索轨迹 | 复杂多跳查询中LLM有效检索相关知识的能力不足 | 知识密集型检索与问答 |
| 37 | http://arxiv.org/abs/2505.20285v2 | MaskSearch: A Universal Pre-Training Framework to Enhance Agentic Search Capability | RAMP预训练任务+课程学习，从易到难习得通用搜索推理能力 | 任务特定数据限制智能体搜索能力的泛化性 | 开放域多跳问答与知识检索 |
| 38 | http://arxiv.org/abs/2505.20732v1 | SPA-RL: Reinforcing LLM Agents via Stepwise Progress Attribution | 进度估计器分解最终奖励为逐步贡献，提供细粒度中间奖励信号 | 延迟奖励难以归因到早期动作，环境约束指导不足 | 多步交互目标导向任务 |
| 39 | http://arxiv.org/abs/2505.20737v1 | RRO: LLM Agent Optimization Through Rising Reward Trajectories | 维持轨迹中奖励上升趋势，动态扩展搜索空间高效捕获高质量数据 | 过程奖励模型扩展成本高，关键步骤敏感易因小错失败 | 复杂多步任务规划与执行 |
| 40 | http://arxiv.org/abs/2505.22942v2 | WorkForceAgent-R1: Incentivizing Reasoning Capability in LLM-based Web Agents via Reinforcement Learning | 基于R1风格RL框架增强web Agent推理能力 | SFT web Agent泛化和鲁棒性不足 | 企业级web导航任务 |
| 41 | http://arxiv.org/abs/2505.22954v3 | Darwin Godel Machine: Open-Ended Evolution of Self-Improving Agents | 达尔文式开放端自我改进Agent系统 | AI系统无法自主持续改进自身架构 | 代码生成Agent自进化 |
| 42 | http://arxiv.org/abs/2505.23723v1 | ML-Agent: Reinforcing LLM Agents for Autonomous Machine Learning Engineering | 在线RL训练LLM Agent自主ML工程 | 现有方法依赖手动提示工程 | 自动化机器学习工程 |
| 43 | http://arxiv.org/abs/2505.21410v1 | MRSD: Multi-Resolution Skill Discovery for HRL Agents | 提出多分辨率技能发现框架，并行学习不同时间分辨率技能 | 解决现有技能发现方法仅限单技能且粒度单一问题 | 分层强化学习 (HRL) 智能体 |
| 44 | http://arxiv.org/abs/2505.21496v1 | UI-Genie: A Self-Improving Approach for Iteratively Boosting MLLM-based Mobile GUI Agents | 提出自改进框架，含奖励模型与数据生成策略 | 解决 GUI 代理轨迹验证难与高质量训练数据不可扩展问题 | 移动 GUI 智能体 |
| 45 | http://arxiv.org/abs/2505.21963v1 | LaMDAgent: An Autonomous Framework for Post-Training Pipeline Optimization via LLM Agents | 自主构建并优化完整后训练管道，探索模型生成技术 | 解决后训练管道自动化构建未被充分探索问题 | 大语言模型后训练 |
| 46 | http://arxiv.org/abs/2505.21964v2 | UI-Evol: Automatic Knowledge Evolving for Computer Use Agents | 提出重追踪与批判阶段，自动进化 GUI 知识 | 解决检索知识无法有效转化为实际任务执行问题 | 计算机使用代理 |
| 47 | http://arxiv.org/abs/2505.22501v1 | EvolveSearch: An Iterative Self-Evolving Search Agent | 结合 SFT 与 RL 的迭代自进化框架，无需外部标注数据 | 解决 LLM Web 搜索能力训练中数据生产与利用效率低问题 | 代理信息搜索 |
| 48 | http://arxiv.org/abs/2506.00539v2 | ARIA: Training Language Agents with Intention-Driven Reward Aggregation | 将自然语言动作投影到低维意图空间，聚合奖励以减少方差 | 解决开放语言动作空间中奖励稀疏及方差大阻碍有效 RL 的问题 | 开放-ended 语言动作环境中的代理训练 |

[返回目录](#目录)

<a id="cat-02"></a>

## 基于Agent的应用系统

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2505.00254v5 | AVA: Towards Agentic Video Analytics with Vision Language Models | 事件知识图谱索引+Agent检索生成机制处理超长视频 | VLM上下文窗口限制，超长视频内容理解困难 | 开放域视频分析、超长视频理解 |
| 2 | http://arxiv.org/abs/2505.00270v2 | Large Language Models as AI Agents for Digital Atoms and Molecules: Catalyzing a New Era in Computational Biophysics | ADAM框架采用混合神经符号架构，支持异步工具编排 | 计算生物物理领域工作流复杂，系统复杂性指数增长 | 计算生物物理、分子模拟 |
| 3 | http://arxiv.org/abs/2505.00586v2 | ParkDiffusion: Heterogeneous Multi-Agent Multi-Modal Trajectory Prediction for Automated Parking using Diffusion Models | 双地图编码器+自适应Agent类型嵌入+运动学可行轨迹生成 | 自动停车场景中车辆与行人异质轨迹预测不确定性 | 自动驾驶停车场景 |
| 4 | http://arxiv.org/abs/2505.00945v2 | SSRLBot: Designing and Developing a Large Language Model-based Agent using Socially Shared Regulated Learning | 基于SSRL理论框架，分析团队SSRL技能并评估诊断结果 | 医学教育中LLM Agent应用不足，需评估学生协作诊断过程 | 医学教育、团队诊断学习 |
| 5 | http://arxiv.org/abs/2505.00989v1 | VTS-LLM: Domain-Adaptive LLM Agent for Enhancing Awareness in Vessel Traffic Services | 领域自适应LLM Agent，知识增强Text-to-SQL+语义代数中间表示 | VTS系统时空推理能力有限，人机交互不直观 | 海事交通服务、船舶安全管理 |
| 6 | http://arxiv.org/abs/2505.01074v1 | WirelessAgent: Large Language Model Agents for Intelligent Wireless Networks | 模仿人类认知四模块（感知、记忆、规划、行动）的无线网络Agent框架 | 无线网络系统复杂动态，现有方法管理挑战大 | 智能无线网络、网络切片 |
| 7 | http://arxiv.org/abs/2505.03807v1 | Facilitating Video Story Interaction with Multi-Agent Collaborative System | VLM理解视频故事+MAS创建成长型角色+场景定制可视化 | 现有视频故事交互方法限于用户选择，缺乏定制化 | 视频故事交互、沉浸式叙事体验 |
| 8 | http://arxiv.org/abs/2505.02076v1 | Leveraging LLM Agents and Digital Twins for Fault Handling in Process Plants | LLM Agent+数字孪生框架，数字孪生作为知识库与仿真验证平台 | 流程工厂故障处理依赖人类专家，需系统化知识方法 | 工业流程工厂、故障处理 |
| 9 | http://arxiv.org/abs/2505.02123v1 | DriveAgent: Multi-Agent Structured Reasoning with LLM and Multimodal Sensor Fusion for Autonomous Driving | 四模块Agent管道融合多传感器，LLM协调专用感知推理Agent | 自动驾驶场景复杂，需可解释的情境理解与决策 | 自动驾驶系统 |
| 10 | http://arxiv.org/abs/2505.02306v4 | SafeMate: A Modular RAG-Based Agent for Context-Aware Emergency Guidance | 基于MCP的RAG Agent，动态路由查询到文档检索/清单生成工具 | 公众难以在危机中解读安全文档，传统EDSS面向专业人士 | 应急准备与响应、公共安全 |
| 11 | http://arxiv.org/abs/2505.02484v2 | El Agente: An Autonomous Agent for Quantum Chemistry | 分层记忆框架+自适应工具选择+原位调试的量子化学Agent | 计算化学工具复杂，非专家难以使用 | 量子化学计算、大学教学 |
| 12 | http://arxiv.org/abs/2505.02699v1 | Exploring LLM-Powered Role and Action-Switching Pedagogical Agents for History Education in Virtual Reality | VR中原型支持自适应角色切换与动作切换的教学Agent | 现有教学Agent多角色交互控制复杂，难以动态适应用户输入 | VR历史教育、沉浸式学习 |
| 13 | http://arxiv.org/abs/2505.06676v1 | VTutor: An Animated Pedagogical Agent SDK that Provide Real Time Multi-Model Feedback | 提出VTutor开源SDK，实现实时唇形同步教学Agent，采用动漫风格避免恐怖谷 | 教学Agent预脚本对话、动画不自然、开发成本高的问题 | 在线教育平台 |
| 14 | http://arxiv.org/abs/2505.07214v3 | Towards user-centered interactive medical image segmentation in VR with an assistive AI agent | 提出SAMIRA对话Agent，支持VR中语音交互的医学图像分割与可视化 | 医学扫描手动分割费时易错、全自动算法需用户反馈的问题 | 放射学分析与手术规划 |
| 15 | http://arxiv.org/abs/2505.08130v1 | ALOHA: Empowering Multilingual Agent for University Orientation with Hierarchical Retrieval | 提出ALOHA多语言Agent，通过分层检索与外部API集成提供校园信息服务 | 现有服务缺乏领域知识、不支持多语言与及时场景的问题 | 大学新生导向服务 |
| 16 | http://arxiv.org/abs/2505.03049v2 | 34 Examples of LLM Applications in Materials Science and Chemistry: Towards Automation, Assistants, Agents, and Accelerated Scientific Discovery | 综述 34 个 LLM 在材料化学领域的应用项目 | 展示 LLM 在科研全流程的自动化与辅助潜力 | 材料科学与化学研究 |
| 17 | http://arxiv.org/abs/2505.03735v2 | Multi-Agent System for Comprehensive Soccer Understanding | 构建足球知识库与多智能体系统实现 holistic 理解 | 解决现有足球理解研究任务孤立、缺乏领域知识问题 | 体育视频分析与理解 |
| 18 | http://arxiv.org/abs/2505.03906v3 | MARCO: Multi-Agent Code Optimization with Real-Time Knowledge Integration for High-Performance Computing | 多智能体代码优化框架，集成实时知识检索 | 解决通用 LLM 生成 HPC 代码性能不足的问题 | 高性能计算代码优化 |
| 19 | http://arxiv.org/abs/2505.04649v3 | FRAME: Feedback-Refined Agent Methodology for Enhancing Medical Research Insights | 生成 - 评估 - 反思三方架构迭代生成医学论文 | 解决自动化医学研究知识合成与质量保证难题 | 医学研究论文生成 |
| 20 | http://arxiv.org/abs/2505.04869v1 | From First Draft to Final Insight: A Multi-Agent Approach for Feedback Generation | 生成 - 评估 - 再生成多智能体流程提升反馈质量 | 解决教师生成大规模高质量反馈耗时且质量不一问题 | 教育反馈自动生成 |
| 21 | http://arxiv.org/abs/2505.04885v1 | A Multi-Agent AI Framework for Immersive Audiobook Production through Spatial Audio and Neural Narration | 多智能体框架生成空间音频与神经 narration 制作有声书 | 解决有声书制作缺乏沉浸感与自动化程度低的问题 | 沉浸式有声书制作 |
| 22 | http://arxiv.org/abs/2505.04997v2 | Foam-Agent: Towards Automated Intelligent CFD Workflows | 多智能体框架自动化端到端 CFD 工作流 | 解决计算流体力学工作流陡峭学习曲线与碎片化问题 | 计算物理与流体仿真 |
| 23 | http://arxiv.org/abs/2505.08842v2 | LibVulnWatch: A Deep Assessment Agent System and Leaderboard for Uncovering Hidden Vulnerabilities in Open-Source AI Libraries | 利用图编排专用 Agent 评估开源库风险，发布公共排行榜 | 解决开源 AI 库安全风险缺乏深度评估与持续监控问题 | 开源 AI 库安全评估 |
| 24 | http://arxiv.org/abs/2505.09787v1 | A Multimodal Multi-Agent Framework for Radiology Report Generation | 多模态多 Agent 框架对齐临床推理工作流，分步生成报告 | 解决放射学报告生成事实不一致、幻觉及跨模态错位问题 | 医疗放射学报告生成 |
| 25 | http://arxiv.org/abs/2505.09936v1 | CartoAgent: a multimodal large language model-powered multi-agent cartographic framework for map style transfer and evaluation | 模拟制图三阶段，利用 MLLM 分离风格与地理数据确保精度 | 解决生成式 AI 制图缺乏艺术性与地理准确性平衡问题 | 地图风格迁移与评估 |
| 26 | http://arxiv.org/abs/2505.10117v3 | Learning Virtual Machine Scheduling in Cloud Computing through Language Agents | 分层语言 Agent 框架 MiCo，利用 LLM 设计启发式调度策略 | 解决云环境虚拟机调度动态适应性差及缺乏可解释性问题 | 云计算虚拟机调度 |
| 27 | http://arxiv.org/abs/2505.10278v2 | MASS: Muli-agent simulation scaling for portfolio construction | 多 Agent 缩放模拟 MASS，反向优化学习异质 Agent 分布 | 解决金融投资组合构建依赖静态工作流及适应性差问题 | 金融投资组合构建 |
| 28 | http://arxiv.org/abs/2505.10321v1 | AutoPentest: Enhancing Vulnerability Management With Autonomous LLM Agents | 基于 GPT-4o 与 LangChain 实现高自主性黑盒渗透测试 | 解决传统渗透测试成本高、频率低及人工依赖问题 | 网络安全漏洞管理 |
| 29 | http://arxiv.org/abs/2505.10732v1 | Automating Security Audit Using Large Language Model based Agent: An Exploration Experiment | 利用 LLM 代理自动化执行字段审计，标记密码策略违规 | 解决安全审计人工成本高、耗时及效率低问题 | 信息系统安全审计 |
| 30 | http://arxiv.org/abs/2505.10922v1 | Vaiage: A Multi-Agent Solution to Personalized Travel Planning | 图结构多 Agent 框架，结合符号推理与对话理解规划行程 | 解决传统旅行平台缺乏上下文适应及实时交互支持问题 | 个性化旅行规划 |
| 31 | http://arxiv.org/abs/2505.10961v2 | Let the Trial Begin: A Mock-Court Approach to Vulnerability Detection using LLM-Based Agents | 模拟法庭多 Agent 框架，四角色协作检测漏洞并解释 | 解决代码漏洞检测难区分 benign 与 vulnerable 函数问题 | 代码漏洞检测 |
| 32 | http://arxiv.org/abs/2505.13400v1 | Robin: A multi-agent system for automating scientific discovery | 首个能全自动科学过程关键智力步骤的多智能体系统 | 解决科学发现流程中背景研究到数据分析的自动化缺失 | 科学发现自动化 |
| 33 | http://arxiv.org/abs/2505.14727v1 | The Evolution of Alpha in Finance Harnessing Human Insight and LLM Agents | 提出金融 Alpha 演进的五阶段分类法与系统级视角 | 解决金融领域从静态预测到上下文感知智能体的转变 | 金融投资系统 |
| 34 | http://arxiv.org/abs/2505.13940v2 | DrugPilot: LLM-based Parameterized Reasoning Agent for Drug Discovery | 引入带参数化推理架构的 LLM 智能体系统用于药物发现 | 解决药物发现中多模数据处理与任务自动化支持不足 | 药物发现工作流 |
| 35 | http://arxiv.org/abs/2505.13941v1 | MLZero: A Multi-Agent System for End-to-end Machine Learning Automation | 引入支持端到端 ML 自动化的多智能体框架 | 解决现有 AutoML 系统处理多模态数据需大量人工配置问题 | 机器学习自动化 |
| 36 | http://arxiv.org/abs/2505.14126v1 | MAS-KCL: Knowledge component graph structure learning with large language model-based agentic workflow | 采用 LLM 驱动多智能体系统自适应修改优化知识组件图 | 解决教育中准确识别学习者学习路径以设计计划的问题 | 教育技术领域 |
| 37 | http://arxiv.org/abs/2505.14148v1 | MM-Agent: LLM as Agents for Real-world Mathematical Modeling Problem | 形式化 LLM 驱动的现实世界数学建模任务并提出 MM-Agent | 解决 LLM 在严谨模型构建与真实问题解决中效用有限问题 | 数学建模竞赛 |
| 38 | http://arxiv.org/abs/2505.14848v2 | MAATS: A Multi-Agent Automated Translation System Based on MQM Evaluation | 利用 MQM 框架作为细粒度信号的多智能体自动翻译系统 | 解决传统单智能体方法依赖自校正与表面流畅性问题 | 自动翻译系统 |
| 39 | http://arxiv.org/abs/2505.14978v2 | JARVIS: A Multi-Agent Code Assistant for High-Quality EDA Script Generation | 利用 LLM 与领域 expertise 生成高质量 EDA 脚本的多智能体框架 | 解决 LLM 在 specialized engineering domains 数据稀缺与幻觉 | 电子设计自动化 |
| 40 | http://arxiv.org/abs/2505.11401v1 | Can AI automatically analyze public opinion? A LLM agents-based agentic pipeline for timely public opinion analysis | 实现首个基于 LLM 智能体的端到端自动化舆情分析流水线。 | 传统舆情分析依赖特定训练数据与人工标注，成本高且不及时。 | 公共治理与舆情监控 |
| 41 | http://arxiv.org/abs/2505.11672v1 | Terminators: Terms of Service Parsing and Auditing Agents | 模块化智能体框架解析审计 ToS，分为提取、验证与问责规划三步。 | ToS 文档 lengthy 且复杂，用户难以理解，缺乏透明性与可执行性。 | 法律文档理解与用户权利保护 |
| 42 | http://arxiv.org/abs/2505.11963v3 | MARVEL: Multi-Agent RTL Vulnerability Extraction using Large Language Models | 多智能体 LLM 框架模拟设计师认知过程，统一决策、工具使用与推理。 | 硬件安全验证挑战大且耗时，需辅助工具识别 RTL 代码漏洞。 | 片上系统安全验证 |
| 43 | http://arxiv.org/abs/2505.12188v3 | LLM-DSE: Searching Accelerator Parameters with LLM Agents | 多智能体框架优化 HLS 指令，协调路由、专家、仲裁与批评智能体。 | 优化硬件指令参数困难，现有方法适应性与样本效率低。 | 领域专用加速器设计空间探索 |
| 44 | http://arxiv.org/abs/2505.12247v1 | LAMeTA: Intent-Aware Agentic Network Optimization via a Large AI Model-Empowered Two-Stage Approach | 意图导向知识蒸馏与共生强化学习，优化意图感知网络。 | 传统 DRL 难以捕捉自然语言意图语义，导致次优策略。 | 智能体网络服务质量优化 |
| 45 | http://arxiv.org/abs/2505.12710v1 | Confidence-Regulated Generative Diffusion Models for Reliable AI Agent Migration in Vehicular Metaverses | 可信 vehicular AI 智能体迁移框架，设计信任评估模型与 CGDM 算法。 | 智能体迁移需频繁数据交换，暴露 vehicular metaverses 至 cyber attacks。 | 车联网元宇宙智能体迁移 |
| 46 | http://arxiv.org/abs/2505.15063v2 | UrduFactCheck: An Agentic Fact-Checking Framework for Urdu with Evidence Boosting and Benchmarking | 构建 UrduFactBench 基准与模块化事实核查框架，增强证据检索 | 解决低资源语言 Urdu 缺乏自动化事实核查系统问题 | 低资源语言事实核查 |
| 47 | http://arxiv.org/abs/2505.15132v1 | Multicrossmodal Automated Agent for Integrating Diverse Materials Science Data | 设计协调 Agent 团队，通过动态门控机制融合多模态材料数据 | 解决材料科学数据多模态隔离与手动集成困难问题 | 材料科学数据集成与发现 |
| 48 | http://arxiv.org/abs/2505.15155v2 | R&D-Agent-Quant: A Multi-Agent Framework for Data-Centric Factors and Model Joint Optimization | 提出数据中心多 Agent 框架，自动化量化策略全栈研发 | 解决量化研究 pipeline 自动化有限与协调碎片化问题 | 量化金融策略研发 |
| 49 | http://arxiv.org/abs/2505.17107v1 | CRAKEN: Cybersecurity LLM Agent with Knowledge-Based Execution | 提出基于知识的 LLM Agent 框架，通过知识提示注入增强安全能力 | 解决 LLM Agent 无法访问训练数据外最新安全知识问题 | 网络安全任务自动化 |
| 50 | http://arxiv.org/abs/2505.15799v2 | The Agentic Economy | 探讨 Agent 经济架构，分析非脚本化交互对市场重组的影响 | 解决生成式 AI 经济影响局限于预定义任务工作流问题 | 经济市场与消费者 - 企业交互 |
| 51 | http://arxiv.org/abs/2505.15928v1 | ViQAgent: Zero-Shot Video Question Answering via Agent with Open-Vocabulary Grounding Validation | 结合 CoT 与 grounding 推理及 YOLO-World，增强物体跟踪与对齐 | 解决 VideoQA 中跨时间物体跟踪与决策对齐改进空间大问题 | 视频问答与理解 |
| 52 | http://arxiv.org/abs/2505.16120v1 | LLM-Powered AI Agent Systems and Their Applications in Industry | 全面考察 Agent 系统演变，分类软件、物理及自适应混合系统 | 解决 LLM powered Agent 在延迟、不确定性及安全上挑战问题 | 工业界 Agent 系统应用 |
| 53 | http://arxiv.org/abs/2505.16229v1 | CT-Agent: A Multimodal-LLM Agent for 3D CT Radiology Question Answering | 采用解剖独立工具与全局 - 局部 token 压缩，处理 3D CT 数据 | 解决现有 VQA 系统难以处理 CT 解剖复杂性与跨切片关系问题 | 3D CT 放射学问答 |
| 54 | http://arxiv.org/abs/2505.16455v1 | Psychology-driven LLM Agents for Explainable Panic Prediction on Social Media during Sudden Disaster Events | 提出 PsychoAgent 框架，基于情绪唤醒理论模拟个体心理链 | 解决突发灾难事件中恐慌预测缺乏细粒度数据与可解释性问题 | 社交媒体恐慌情绪预测 |
| 55 | http://arxiv.org/abs/2505.16938v3 | InternAgent: When Agent Becomes the Scientist -- Building Closed-Loop System from Hypothesis to Verification | 统一闭环多智能体框架，支持自主科学研究全流程 | 解决复杂科学问题研究效率低及创新不足问题 | 多领域科学研究任务 |
| 56 | http://arxiv.org/abs/2505.16982v1 | Beyond Correlation: Towards Causal Large Language Model Agents in Biomedicine | envision 因果 LLM 智能体，整合多模态数据进行干预推理 | 解决生物医学中 LLM 缺乏真正因果理解的问题 | 生物医学研究与药物发现 |
| 57 | http://arxiv.org/abs/2505.21534v1 | Uncovering Bottlenecks and Optimizing Scientific Lab Workflows with Cycle Time Reduction Agents | LangGraph 基于代理工作流，自动化分析实验室运营指标 | 解决科学实验室工作流优化复杂与任务量大问题 | 制药与生物技术研发 |
| 58 | http://arxiv.org/abs/2505.18457v1 | EdgeAgentX: A Novel Framework for Agentic AI at the Edge in Military Communication Networks | 集成联邦学习与 MARL 的边缘代理框架，含对抗防御 | 解决军事通信网络中自主决策延迟与对抗脆弱问题 | 军事通信网络边缘计算 |
| 59 | http://arxiv.org/abs/2505.18530v1 | MRGAgents: A Multi-Agent Framework for Improved Medical Report Generation with Med-LVLMs | 提出多智能体框架，微调特定疾病代理，平衡正常与异常发现描述。 | 医疗报告生成中模型偏向正常结果且描述不全的问题。 | 医疗影像报告生成 |
| 60 | http://arxiv.org/abs/2505.18630v2 | DDO: Dual-Decision Optimization for LLM-Based Medical Consultation via Multi-Agent Collaboration | 解耦症状询问与疾病诊断子任务，通过多智能体协作优化双重决策。 | 医疗咨询中症状询问无效及疾病诊断不可靠的问题。 | 在线医疗咨询 |
| 61 | http://arxiv.org/abs/2505.19197v3 | Structuring the Unstructured: A Multi-Agent System for Extracting and Querying Financial KPIs and Guidance | 含提取与 Text-to-SQL 双代理，自动识别 KPI 并生成可执行 SQL 语句。 | 非结构化财务文件提取结构化洞察耗时且依赖人工，难以扩展。 | 投资研究自动化 |
| 62 | http://arxiv.org/abs/2505.19205v2 | OptiMindTune: A Multi-Agent Framework for Intelligent Hyperparameter Optimization | 利用推荐、评估与决策三代理协作，结合自适应搜索优化超参数。 | 传统超参数优化面临高维、复杂依赖及计算昂贵挑战。 | 机器学习模型调优 |
| 63 | http://arxiv.org/abs/2505.19567v1 | LLM-Agent-Controller: A Universal Multi-Agent Large Language Model System as a Control Engineer | 集成中央控制器与多个专用辅助代理，解决控制工程各类问题。 | 控制理论问题复杂，用户缺乏专业知识难以输入及获取解决方案。 | 控制工程辅助 |
| 64 | http://arxiv.org/abs/2505.20466v1 | Reconceptualizing Smart Microscopy: From Data Collection to Knowledge Creation by Multi-Agent Integration | 提出六项设计原则指导多智能体架构，弥合经验-认知鸿沟 | 智能显微镜从被动观测到主动科学伙伴的范式转变 | 生物成像与科学发现 |
| 65 | http://arxiv.org/abs/2505.20510v2 | CPathAgent: An Agent-based Foundation Model for Interpretable High-Resolution Pathology Image Analysis Mimicking Pathologists' Diagnostic Logic | 多阶段训练统一多尺度能力，自主导航切片模仿病理学家诊断流程 | 现有模型缺乏病理学家渐进式诊断逻辑与可解释性 | 高分辨率病理图像分析与辅助诊断 |
| 66 | http://arxiv.org/abs/2505.21559v1 | Streamlining Resilient Kubernetes Autoscaling with Multi-Agent Systems via an Automated Online Design Framework | 四阶段在线框架设计故障专用多智能体HPA系统，数字孪生仿真训练 | 传统自动扩缩容难以应对动态adversarial条件下的弹性挑战 | 云原生Kubernetes集群运维 |
| 67 | http://arxiv.org/abs/2505.20574v2 | xChemAgents: Agentic AI for Explainable Quantum Chemistry | 选择器+验证器双智能体协作，自适应稀疏描述符+物理约束对话 | 多模态化学预测中描述符冗余损害性能与可解释性 | 量子化学性质预测与材料科学 |
| 68 | http://arxiv.org/abs/2506.11060v1 | Code Researcher: Deep Research Agent for Large Systems Code and Commit History | 多步语义/模式/提交历史推理+结构化记忆，深度探索代码库生成补丁 | 大型系统代码修改需研究大量上下文，现有智能体探索不足 | 系统代码崩溃修复与软件维护 |
| 69 | http://arxiv.org/abs/2505.20733v2 | E2E Process Automation Leveraging Generative AI and IDP-Based Automation Agent: A Case Study on Corporate Expense Processing | 四阶段集成流程+生成式AI异常处理+人在回路持续学习 | 传统RPA难以处理非结构化数据、异常管理和复杂决策 | 企业财务费用处理流程自动化 |
| 70 | http://arxiv.org/abs/2505.21569v2 | ChemHAS: Hierarchical Agent Stacking for Enhancing Chemistry Tools | 层次化智能体堆叠结构优化，从有限数据补偿化学工具预测误差 | 化学工具固有预测误差限制LLM智能体任务性能 | 化学性质预测与分子设计 |
| 71 | http://arxiv.org/abs/2505.20820v1 | MT-Mol:Multi Agent System with Tool-based Reasoning for Molecular Optimization | 五领域专家分析智能体+工具引导推理，迭代优化分子候选 | 分子优化中结构化推理、可解释性与工具落地能力不足 | 药物发现与分子设计 |
| 72 | http://arxiv.org/abs/2505.23852v1 | Large Language Model-Based Agents for Automated Research Reproducibility: An Exploratory Study in Alzheimer's Disease | LLM Agent团队自动复现生物医学研究 | 研究可重复性评估缺乏自动化方法 | 阿尔茨海默病研究复现 |
| 73 | http://arxiv.org/abs/2505.22990v2 | MenTeR: A fully-automated Multi-agenT workflow for end-to-end RF/Analog Circuits Netlist Design | 多Agent工作流端到端模拟电路设计 | 模拟设计依赖专家直觉效率低 | RF/模拟电路设计 |
| 74 | http://arxiv.org/abs/2505.23055v2 | CDR-Agent: Intelligent Selection and Execution of Clinical Decision Rules Using Large Language Model Agents | LLM Agent自主选择执行临床决策规则 | 急诊医生认知负荷限制CDR使用 | 急诊科临床决策支持 |
| 75 | http://arxiv.org/abs/2505.23130v1 | PhotoArtAgent: Intelligent Photo Retouching with Language Model-Based Artist Agents | VLM+语言推理模拟专业艺术家修图过程 | 自动修图工具缺乏解释深度和交互透明 | 照片艺术修图 |
| 76 | http://arxiv.org/abs/2505.23695v1 | Data-to-Dashboard: Multi-Agent LLM Framework for Insightful Visualization in Enterprise Analytics | 模块化Agent自动化数据到仪表板流程 | 现有图表QA系统缺乏分析推理深度 | 企业数据分析可视化 |
| 77 | http://arxiv.org/abs/2505.21582v1 | AITEE -- Agentic Tutor for Electrical Engineering | 提出代理辅导系统，支持手绘/数字电路交互与苏格拉底式对话 | 解决大模型在电气电路具体问题上的能力不足 | 电气工程教育与学生 |
| 78 | http://arxiv.org/abs/2505.21069v1 | CXXCrafter: An LLM-Based Agent for Automated C/C++ Open Source Software Building | 开发自动化构建系统，利用 LLM 统一构建系统并处理错误 | 解决 C/C++ 项目自动化构建中的依赖与错误处理难题 | 开源软件构建与分析 |
| 79 | http://arxiv.org/abs/2505.21418v2 | Autonomous Multi-Modal LLM Agents for Treatment Planning in Focused Ultrasound Ablation Surgery | 整合患者 profile 与 MRI 数据， orchestrate 医疗 AI 工具生成治疗计划 | 解决聚焦超声手术中复杂任务需智能辅助的问题 | 聚焦超声消融手术 (FUAS) |
| 80 | http://arxiv.org/abs/2506.15692v3 | MLE-STAR: Machine Learning Engineering Agent via Search and Targeted Refinement | 利用搜索引擎检索模型并迭代细化特定 ML 组件 | 解决现有 MLE 代理依赖内部知识且探索策略粗糙问题 | 机器学习工程 (MLE) |
| 81 | http://arxiv.org/abs/2505.21660v2 | PreGenie: An Agentic Framework for High-quality Visual Presentation Generation | 提出模块化框架，分阶段生成并审查视觉演示文稿 | 解决自动生成演示文稿布局混乱与图文不匹配问题 | 商业与科研视觉演示 |
| 82 | http://arxiv.org/abs/2506.02009v2 | STRATUS: A Multi-agent System for Autonomous Reliability Engineering of Modern Clouds | 构建多代理系统实现自主站点可靠性工程，形式化安全规范 | 解决云规模系统故障频发且人工运维跟不上问题 | 现代云服务可靠性工程 |
| 83 | http://arxiv.org/abs/2505.21757v1 | BehaviorSFT: Behavioral Token Conditioning for Clinical Agents Across the Proactivity Spectrum | 提出 BehaviorSFT 策略，使用行为 token 条件化 LLM 动态行为 | 解决临床 LLM 代理在主动性 engagement 上不一致问题 | 临床辅助代理 |
| 84 | http://arxiv.org/abs/2506.15695v2 | SimuGen: Multi-modal Agentic Framework for Constructing Block Diagram-Based Simulation Models | 提出多模态框架，结合视觉图与领域知识生成 Simulink 代码 | 解决 LLM 代理生成 Simulink 模型不可靠与不完整问题 | 工程与科学仿真模型 |
| 85 | http://arxiv.org/abs/2505.21966v2 | MapStory: Prototyping Editable Map Animations with LLM Agents | 双代理架构，从文本生成可编辑地图动画序列 | 解决地图动画制作门槛高与迭代慢问题 | 地图动画原型设计 |
| 86 | http://arxiv.org/abs/2506.02019v3 | ChatCFD: An LLM-Driven Agent for End-to-End CFD Automation with Structured Knowledge and Reasoning | 集成结构化知识库与错误定位器，实现 CFD 端到端自动化 | 解决计算流体动力学操作复杂与专家门槛高问题 | 科学计算 (CFD) |
| 87 | http://arxiv.org/abs/2505.23837v1 | CoMaPOI: A Collaborative Multi-Agent Framework for Next POI Prediction Bridging the Gap Between Trajectory and Language | 三代理协作将数值时空数据转为语言描述并约束候选空间 | 解决 LLM 缺乏时空数据内在理解与候选空间过大问题 | 下一兴趣点 (POI) 预测 |
| 88 | http://arxiv.org/abs/2505.24331v1 | Context-Aware Sentiment Forecasting via LLM-based Multi-Perspective Role-Playing Agents | 提出多视角角色扮演框架，模拟人类响应过程以预测情感 | 解决社交媒体中针对 ongoing 事件的未来情感预测研究不足的问题 | 社交媒体情感趋势 forecasting |
| 89 | http://arxiv.org/abs/2505.24553v1 | CREFT: Sequential Multi-Agent LLM for Character Relation Extraction | 构建基础角色图，迭代细化角色组成与关系提取 | 解决现有方法难以处理长篇幅叙事中细微互动的问题 | 叙事分析与剧本评估 |
| 90 | http://arxiv.org/abs/2505.24575v1 | NexusSum: Hierarchical LLM Agents for Long-Form Narrative Summarization | 引入对话转描述变换及分层多 LLM 总结流水线 | 解决现有 LLM 难以捕捉长篇幅叙事中复杂情节与主题连贯性的问题 | 书籍、电影及剧本长文本总结 |
| 91 | http://arxiv.org/abs/2505.24584v3 | AutoChemSchematic AI: Agentic Physics-Aware Automation for Chemical Manufacturing Scale-Up | 集成领域 SLM、层次知识图及化学过程模拟器，生成工业级流程图 | 解决 AI 系统无法可靠生成关键工程示意图阻碍制造放大的问题 | 化学制造规模化与工程设计 |
| 92 | http://arxiv.org/abs/2506.00235v1 | MedOrch: Medical Diagnosis with Tool-Augmented Reasoning Agents for Flexible Extensibility | 编排多专用工具及推理代理，支持灵活集成领域工具 | 解决当前 AI 系统依赖任务特定模型或缺乏外部知识 grounding 的问题 | 多模态医疗数据处理的临床决策 |
| 93 | http://arxiv.org/abs/2506.00608v2 | PAKTON: A Multi-Agent Framework for Question Answering in Long Legal Agreements | 设计协作代理工作流及 novel RAG 组件，实现自动化法律文档审查 | 解决合同审查复杂耗时、非专家 inaccessible 及保密性限制的问题 | 长法律协议中的问答与审查 |
| 94 | http://arxiv.org/abs/2506.00714v2 | RFCAudit: An LLM Agent for Functional Bug Detection in Network Protocols | 包含索引与检测代理，通过需求驱动检索识别 RFC 规范不一致 | 解决传统静态分析工具无法检测功能 bug 及深度语义分析需求的问题 | 网络协议实现的功能正确性 |

[返回目录](#目录)

<a id="cat-03"></a>

## 人机协作Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2505.00753v4 | LLM-Based Human-Agent Collaboration and Interaction Systems: A Survey | 首篇LLM人机协作系统综述，系统化呈现核心组件与交互类型 | 完全自主Agent可靠性低、安全性风险高，需人类介入 | 人机协作应用场景 |
| 2 | http://arxiv.org/abs/2505.05543v1 | Would You Rely on an Eerie Agent? A Systematic Review of the Impact of the Uncanny Valley Effect on Trust in Human-Agent Interaction | 系统综述恐怖谷效应对人机信任的影响，提出信任测量分类框架 | 恐怖谷效应如何影响用户对AI智能体的信任感知 | 人机交互中的信任建立 |
| 3 | http://arxiv.org/abs/2505.06947v1 | The Wisdom of Agent Crowds: A Human-AI Interaction Innovation Ignition Framework | 构建基于BDI理论的多Agent头脑风暴框架，支持人机协同金融分析 | 高风险决策场景中人类参与与智能系统对齐问题 | 金融决策分析 |
| 4 | http://arxiv.org/abs/2505.07142v2 | Exploring Anthropomorphism in Conversational Agents for Environmental Sustainability | 比较拟人化与非拟人化对话Agent设计对环保行为的影响 | 如何通过Agent设计促进用户可持续消费行为转变 | 家庭能源管理 |
| 5 | http://arxiv.org/abs/2505.04251v1 | Facilitating Trustworthy Human-Agent Collaboration in LLM-based Multi-Agent System oriented Software Engineering | 提出基于 RACI 的框架分配人与 LMA 系统任务 | 解决软件工程中人机任务分配信任与责任界定难题 | 软件工程人机协作 |
| 6 | http://arxiv.org/abs/2505.04579v1 | Implicitly Aligning Humans and Autonomous Agents through Shared Task Abstractions | 利用分层 RL 模仿人类共享任务抽象实现零样本协作 | 解决自主智能体难以快速适应新人类队友的问题 | 人机零样本协作 |
| 7 | http://arxiv.org/abs/2505.08648v1 | Enhancing Software Development with Context-Aware Conversational Agents: A User Study on Developer Interactions with Chatbots | 通过用户研究揭示开发者对上下文感知对话 Agent 的需求 | 解决开发者使用聊天机器人缺乏深层上下文理解支持问题 | 软件开发辅助工具 |
| 8 | http://arxiv.org/abs/2505.09875v2 | Characterizing Unintended Consequences in Human-GUI Agent Collaboration for Web Browsing | characterize 三类意外后果，提出用户发起的缓解措施 | 解决 LLM 基于 GUI 代理在网页浏览中的安全与信任风险 | 网页浏览人机协作 |
| 9 | http://arxiv.org/abs/2506.01998v1 | Inter(sectional) Alia(s): Ambiguity in Voice Agent Identity via Intersectional Japanese Self-Referents | 研究交叉性日语自指代词对语音智能体身份模糊性的影响 | 解决拟人化机器中身份中立性假设与伦理问题 | 语音对话智能体 |
| 10 | http://arxiv.org/abs/2505.14668v2 | ContextAgent: Context-Aware Proactive LLM Agents with Open-World Sensory Perceptions | 引入结合广泛感官上下文增强 LLM 智能体主动性的框架 | 解决现有主动智能体依赖封闭环境观察或规则通知问题 | 主动 LLM 智能体 |
| 11 | http://arxiv.org/abs/2505.14872v1 | Unremarkable to Remarkable AI Agent: Exploring Boundaries of Agent Intervention for Adults With and Without Cognitive Impairment | 通过速配与故事板研究揭示阻碍接受智能体的社会边界 | 解决老年人及照护者对智能体介入的 invisible social boundaries | 老年人与认知障碍者 |
| 12 | http://arxiv.org/abs/2505.16171v1 | Fairness and Efficiency in Human-Agent Teams: An Iterative Algorithm Design Approach | 提出 Fair-Efficient Algorithm，平衡基于能力与偏好任务分配 | 解决现有公平指标未考虑第一人称视角与任务偏好问题 | 人机团队任务分配 |
| 13 | http://arxiv.org/abs/2505.20312v1 | Let's Get You Hired: A Job Seeker's Perspective on Multi-Agent Recruitment Systems for Explaining Hiring Decisions | 引入多 Agent AI 系统，引导求职者并解释招聘决策提高透明度 | 解决传统招聘选择方法缺乏透明度与 justification 问题 | 招聘系统与求职者辅助 |
| 14 | http://arxiv.org/abs/2505.17238v2 | Personalizing Student-Agent Interactions Using Log-Contextualized Retrieval Augmented Generation (RAG) | 日志上下文 RAG，增强检索以个性化学生 - 代理交互 | 解决学生对话中语义链接弱导致幻觉问题 | STEM+C 协作学习环境 |
| 15 | http://arxiv.org/abs/2505.17557v2 | Novobo: Supporting Teachers' Peer Learning of Instructional Gestures by Teaching a Mentee AI-Agent Together | 学徒 AI 代理刺激教师通过教代理进行同伴学习 | 解决教师 embodied 技能训练孤立且耗时问题 | 教师专业发展与手势教学 |
| 16 | http://arxiv.org/abs/2505.20120v1 | Agents Require Metacognitive and Strategic Reasoning to Succeed in the Coming Labor Markets | 提出元认知（内部）与战略推理（外部）双维度推理框架 | AI智能体在不完全信息劳动力市场中的有效决策 | 未来劳动力市场人机协作 |
| 17 | http://arxiv.org/abs/2505.20277v2 | OmniCharacter: Towards Immersive Role-Playing Agents with Seamless Speech-Language Personality Interaction | 无缝语音-语言人格交互模型，保持一致角色特质与低延迟响应 | 现有角色扮演智能体忽视语音特质影响交互沉浸感 | 沉浸式人机对话与娱乐 |
| 18 | http://arxiv.org/abs/2505.20973v2 | Towards Conversational Development Environments: Using Theory-of-Mind and Multi-Agent Architectures for Requirements Refinement | 心智理论增强多智能体架构，迭代澄清利益相关者信念意图生成可执行工作流 | 基础模型准确捕捉软件需求困难，需求细化阶段缺乏有效支持 | 软件需求工程与人机协作开发 |
| 19 | http://arxiv.org/abs/2505.22809v2 | First Steps Towards Overhearing LLM Agents: A Case Study With Dungeons & Dragons Gameplay | 提出"窃听式Agent"新交互范式 | 传统对话Agent需主动参与限制应用场景 | D&D游戏地下城主辅助 |
| 20 | http://arxiv.org/abs/2505.22698v1 | Design and testing of an agent chatbot supporting decision making with public transport data | 基于代理架构的聊天机器人，执行 SQL 查询与可视化 | 解决公共交通数据查询复杂与普通用户交互难问题 | 公共交通决策支持 |
| 21 | http://arxiv.org/abs/2505.22526v1 | AI instructional agent improves student's perceived learner control and learning outcome: empirical evidence from a randomized controlled trial | 实证研究 AI 教学代理对学生控制感与成绩的影响 | 解决传统教学中学生控制感低与互动不足问题 | 教育与学习系统 |
| 22 | http://arxiv.org/abs/2506.06324v1 | Mapping Human-Agent Co-Learning and Co-Adaptation: A Scoping Review | 综述人机共学共适应研究，梳理术语、代理类型及认知理论框架 | 解决术语不一致及缺乏对人机协作动态理解的问题 | 人机协作与自适应学习研究 |
| 23 | http://arxiv.org/abs/2506.00160v2 | Verbal Werewolf: Engage Users with Verbalized Agentic Werewolf Game Framework | 优化 LLM 游戏play 及 TTS 并行流水线，实现近实时语音交互 | 解决现有框架依赖外部模块导致延迟及用户体验不足的问题 | 社交推理游戏中的用户 engagement |

[返回目录](#目录)

<a id="cat-04"></a>

## Agent工具使用与环境交互

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2505.00416v1 | ScaleTrack: Scaling and back-tracking Automated GUI Agents | 统一GUI样本模板+回溯规划策略，解释GUI图像与动作对应关系 | GUI定位训练数据不足，规划阶段忽略历史行为回溯 | 自动化GUI交互（Web、移动、桌面） |
| 2 | http://arxiv.org/abs/2505.00684v2 | Visual Test-time Scaling for GUI Agent Grounding | RegionFocus动态放大相关区域，图像即地图机制可视化关键地标 | GUI图像视觉复杂，界面元素众多导致动作选择困难 | GUI Agent定位（Screenspot-pro、WebVoyager） |
| 3 | http://arxiv.org/abs/2505.06416v1 | ScaleMCP: Dynamic and Auto-Synchronizing Model Context Protocol Tools for LLM Agents | 提出动态工具检索与自动同步存储系统，支持Agent自主添加工具 | LLM Agent工具选择的手动更新、重复与低效问题 | LLM Agent工具调用 |
| 4 | http://arxiv.org/abs/2505.07064v1 | ParaView-MCP: An Autonomous Visualization Agent with Direct Tool Use | 集成多模态LLM与ParaView，通过MCP实现自然语言交互与视觉反馈 | ParaView学习曲线陡峭、使用门槛高的问题 | 科学可视化分析 |
| 5 | http://arxiv.org/abs/2505.04254v1 | CompileAgent: Automated Real-World Repo-Level Compilation with Tool-Integrated LLM-based Agent System | 集成 5 种工具的流式智能体实现 repo 级自动编译 | 解决大型开源项目手动编译繁琐且易错的问题 | 软件仓库自动编译 |
| 6 | http://arxiv.org/abs/2505.13887v3 | Mobile-Agent-V: A Video-Guided Approach for Effortless and Efficient Operational Knowledge Injection in Mobile Automation | 利用视频作为指导工具注入操作知识到移动自动化 | 解决 AI 框架因缺乏操作专业知识而效率低下的问题 | 移动自动化任务 |
| 7 | http://arxiv.org/abs/2505.12650v1 | AutoMat: Enabling Automated Crystal Structure Reconstruction from Microscopy via Agentic Tool Use | 端到端智能体辅助 pipeline，转换 STEM 图像为原子结构并预测属性。 | 原子结构数据 scarce，转换图像为仿真格式 labor-intensive 且 error-prone。 | 材料科学显微镜与原子模拟 |
| 8 | http://arxiv.org/abs/2505.15859v1 | AutoData: A Multi-Agent System for Open Web Data Collection | 设计面向消息超图架构与缓存系统，最小化人工干预收集数据 | 解决现有 web 数据收集方法适应性差或成本高的问题 | 开放网络数据自动化收集 |
| 9 | http://arxiv.org/abs/2505.17148v2 | LLM Agents for Interactive Exploration of Historical Cadastre Data: Framework and Application to Venice | 提出 text-to-programs 框架，利用 SQL 与 coding Agent 分析历史数据 | 解决历史地籍数据非标准化 complicating 大规模分析挑战问题 | 历史城市数据交互探索 |
| 10 | http://arxiv.org/abs/2505.16582v2 | O$^2$-Searcher: A Searching-based Agent Model for Open-Domain Open-Ended Question Answering | 提出 O^2-Searcher，利用 RL 与本地模拟搜索环境处理开放域问题 | 解决 LLM 静态参数知识限制开放域最新信息与开放端问题 | 开放域开放端问答 |
| 11 | http://arxiv.org/abs/2505.16827v1 | GUI-explorer: Autonomous Exploration and Mining of Transition-aware Knowledge for GUI Agent | 提出 GUI-explorer，自主探索功能感知轨迹与无监督挖掘知识 | 解决 GUI 自动化中 MLLM 误解 UI 组件与知识过时关键挑战 | 图形用户界面自动化 |
| 12 | http://arxiv.org/abs/2505.18079v4 | Deep Video Discovery: Agentic Search with Tool Use for Long-form Video Understanding | 代理搜索策略，自适应选择工具处理长视频片段 | 解决长视频理解中时空复杂性与问答困难问题 | 长形式视频理解任务 |
| 13 | http://arxiv.org/abs/2505.18135v2 | Tool Preferences in Agentic LLMs are Unreliable | 揭示工具描述编辑可 drastically 改变 LLM 工具选择 | 解决代理 LLM 工具选择依赖文本描述且脆弱问题 | 工具调用与功能选择协议 |
| 14 | http://arxiv.org/abs/2505.19768v2 | T^2Agent A Tool-augmented Multimodal Misinformation Detection Agent with Monte Carlo Tree Search | 结合可扩展工具包与 MCTS，动态收集证据并进行多源验证。 | 现有方法依赖静态 pipeline 及有限工具使用，难以处理混合伪造源。 | 多模态虚假信息检测 |
| 15 | http://arxiv.org/abs/2505.22846v3 | RocqStar: Leveraging Similarity-driven Retrieval and Agentic Systems for Rocq generation | 多阶段Agent系统+多Agent辩论提升证明生成 | 交互式定理证明生成效率低 | Rocq形式化验证证明生成 |
| 16 | http://arxiv.org/abs/2505.23752v2 | ThinkGeo: Evaluating Tool-Augmented Agents for Remote Sensing Tasks | 遥感任务工具增强Agent评测基准 | 缺乏领域特定工具使用能力评估 | 遥感分析任务 |
| 17 | http://arxiv.org/abs/2505.21055v1 | Agent-Environment Alignment via Automated Interface Generation | 提出 ALIGN 框架，自动生成接口以对齐智能体与环境期望 | 解决智能体动作预期与环境状态转移不匹配问题 | 具身任务、Web 导航与工具使用 |
| 18 | http://arxiv.org/abs/2506.15701v1 | Compiler-R1: Towards Agentic Compiler Auto-tuning with Reinforcement Learning | 首创 RL 驱动框架 Compiler-R1，利用高质量推理数据集优化编译器自动调优 | 解决缺乏高质量推理数据集及与编译环境交互有限的问题 | 编译器优化与自动化调优 |
| 19 | http://arxiv.org/abs/2505.24197v2 | Learning API Functionality from In-Context Demonstrations for Tool-based Agents | 提出从上下文演示中学习 API 功能的新范式，无需文档依赖 | 解决 API 文档缺失、过时或不一致阻碍通用代理开发的问题 | 无文档场景下的工具型智能体 |
| 20 | http://arxiv.org/abs/2506.00520v1 | Temac: Multi-Agent Collaboration for Automated Web GUI Testing | 利用 LLM 多智能体协作总结信息形成知识库，指导未覆盖功能测试 | 解决现有 AWGT 方法生成连续有意义动作序列能力及覆盖率 limited 的问题 | 自动化 Web GUI 测试与质量保证 |

[返回目录](#目录)

<a id="cat-05"></a>

## Agent记忆与知识管理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2505.00472v1 | UserCentrix: An Agentic Memory-augmented AI Framework for Smart Spaces | 个性化LLM Agent+混合分层控制+价值信息驱动决策 | 智能空间需动态适应用户偏好，优化资源分配 | 智能空间、智能家居环境 |
| 2 | http://arxiv.org/abs/2505.00675v3 | Rethinking Memory in LLM based Agents: Representations, Operations, and Emerging Topics | 将记忆分为参数化与上下文两类，定义六种核心操作 | 现有综述忽视记忆动态的原子操作，缺乏结构化视图 | LLM-based Agent记忆研究 |
| 3 | http://arxiv.org/abs/2505.02099v1 | MemEngine: A Unified and Modular Library for Developing Advanced Memory of LLM-based Agents | 统一模块化库实现多种先进记忆模型，支持便捷可扩展开发 | 缺乏统一框架下的记忆模型实现，开发不便 | LLM-based Agent记忆开发 |
| 4 | http://arxiv.org/abs/2505.07596v1 | Reinforced Internal-External Knowledge Synergistic Reasoning for Efficient Adaptive Search Agent | 提出IKEA Agent，识别知识边界，优先利用内部知识，必要时检索外部知识 | RAG搜索Agent冗余检索、知识冲突与推理延迟问题 | 知识推理任务 |
| 5 | http://arxiv.org/abs/2505.07815v3 | Imagine, Verify, Execute: Memory-guided Agentic Exploration with Vision-Language Models | 提出IVE框架，利用VLM抽象场景图、想象新场景并生成可执行技能序列 | 开放环境中探索缺乏密集奖励与任务监督的问题 | 通用机器人学习 |
| 6 | http://arxiv.org/abs/2505.03434v1 | Procedural Memory Is Not All You Need: Bridging Cognitive Gaps in LLM-Based Agents | 主张增强 LLM 语义记忆与关联学习系统以弥补认知差距 | 解决 LLM 仅依赖程序性记忆难以适应复杂环境的问题 | 通用 LLM 智能体架构 |
| 7 | http://arxiv.org/abs/2505.13044v1 | CAIM: Development and Evaluation of a Cognitive AI Memory Framework for Long-Term Interaction with Intelligent Agents | 提出包含记忆控制器、检索与后思考的认知 AI 记忆框架 | 解决 LLM 在长期交互中适应用户与环境变化的挑战 | 长期人机交互系统 |
| 8 | http://arxiv.org/abs/2505.11888v1 | AR Secretary Agent: Real-time Memory Augmentation via LLM-powered Augmented Reality Glasses | AR 秘书智能体实时提供对话者信息与讨论摘要，增强记忆。 | 专业人士日常交互多，难以回忆具体细节与过往讨论。 | 增强现实眼镜与日常交互辅助 |
| 9 | http://arxiv.org/abs/2505.16067v2 | How Memory Management Impacts LLM Agents: An Empirical Study of Experience-Following Behavior | 实证研究记忆管理操作对 Agent 行为影响，发现经验跟随属性 | 解决记忆系统中错误传播与经验回放错位挑战问题 | LLM Agent 长期性能与记忆 |
| 10 | http://arxiv.org/abs/2505.17716v1 | Get Experience from Practice: LLM Agents with Record & Replay | 引入记录与回放机制，将交互 trace 总结为经验 | 解决代理可靠性、隐私、成本与性能挑战 | 安全高效的代理部署 |
| 11 | http://arxiv.org/abs/2505.18279v1 | Collaborative Memory: Multi-User Memory Sharing in LLM Agents with Dynamic Access Control | 多用户多代理环境下的协作记忆框架，含动态访问控制 | 解决单用户记忆假设忽略跨用户知识转移挑战问题 | 多用户协作代理系统 |
| 12 | http://arxiv.org/abs/2505.19436v1 | Task Memory Engine: Spatial Memory for Robust Multi-Step LLM Agents | 实施空间记忆框架，构建动态任务图替代扁平上下文，支持依赖跟踪修订。 | 多步交互中因缺乏持久记忆导致幻觉、重复动作及误解用户修正。 | 多步任务智能体 |
| 13 | http://arxiv.org/abs/2505.19549v2 | From Single to Multi-Granularity: Toward Long-Term Memory Association and Selection of Conversational Agents | 构建多粒度关联与自适应选择检索框架，利用高斯混合模型聚类记忆。 | 单粒度记忆分割难以捕捉深层连接，导致检索信息不全或噪声大。 | 长对话记忆管理 |
| 14 | http://arxiv.org/abs/2505.20231v2 | MemGuide: Intent-Driven Memory Selection for Goal-Oriented Multi-Session LLM Agents | 意图对齐检索+缺失槽位引导过滤，最小化对话轮次 | 多会话任务中语义相似检索忽略任务意图导致连贯性下降 | 任务型对话系统与多轮交互 |
| 15 | http://arxiv.org/abs/2505.23422v1 | From Knowledge to Noise: CTIM-Rover and the Pitfalls of Episodic Memory in Software Engineering Agents | 发现跨任务实例记忆引入噪声导致性能下降 | SE Agent长时记忆机制有效性存疑 | 软件工程Agent记忆设计 |
| 16 | http://arxiv.org/abs/2505.22006v1 | Efficiently Enhancing General Agents With Hierarchical-categorical Memory | 引入分层记忆检索与任务类别导向经验学习模块 | 解决通用代理无法持续学习适应新环境且训练成本高问题 | 通用多模态代理 |
| 17 | http://arxiv.org/abs/2506.06326v1 | Memory OS of AI Agent | 设计分层存储架构及动态更新机制，实现全面高效的记忆管理 | 解决固定上下文窗口导致长期记忆不足及个性化 limited 的问题 | 长对话中的 AI 智能体记忆 |

[返回目录](#目录)

<a id="cat-06"></a>

## Agent评测与基准

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2505.02847v3 | Sentient Agent as a Judge: Evaluating Higher-Order Social Cognition in Large Language Models | SAGE框架模拟人类情感变化与内心思考，提供情感轨迹评分 | 评估LLM理解人类而非文本的能力，现有基准无法反映社会认知差距 | 多轮对话、共情能力评估 |
| 2 | http://arxiv.org/abs/2505.01560v1 | AI agents may be worth the hype but not the resources (yet): An initial exploration of machine translation quality and costs in three language pairs in the legal and news domains | 多维度成本感知评估，发现Agent质量提升但成本高5-15倍 | LLM/多Agent在机器翻译中相对传统NMT的优势不明确 | 机器翻译（法律、新闻领域） |
| 3 | http://arxiv.org/abs/2505.01563v1 | TutorGym: A Testbed for Evaluating AI Agents as Tutors and Students | TutorGym标准接口将AI Agent嵌入现有智能辅导系统交互界面 | 现有评估仅看最终解答，需评估Agent作为导师/学生的交互能力 | 智能辅导系统、教育AI |
| 4 | http://arxiv.org/abs/2505.01592v2 | AURA: A Diagnostic Framework for Tracking User Satisfaction of Interactive Planning Agents | AURA框架概念化交互式任务规划Agent行为阶段，原子LLM评估标准 | 现有基准仅评估任务完成度，与用户满意度不一致 | 交互式任务规划Agent |
| 5 | http://arxiv.org/abs/2505.02709v1 | Technical Report: Evaluating Goal Drift in Language Model Agents | 分析Agent目标漂移，暴露 competing objectives下行为渐变 | 自主Agent长期运行无监督时目标可能逐渐偏移 | 长期自主Agent安全运行 |
| 6 | http://arxiv.org/abs/2505.06702v1 | Do Language Model Agents Align with Humans in Rating Visualizations? An Empirical Study | 三项研究验证LLM Agent模拟人类可视化评分的能力与局限性 | LLM Agent能否预测人类对可视化设计的反馈问题 | 可视化设计评估 |
| 7 | http://arxiv.org/abs/2505.07782v1 | MLE-Dojo: Interactive Environments for Empowering LLM Agents in Machine Learning Engineering | 提出Gym风格框架MLE-Dojo，支持LLM Agent在MLE工作流中的迭代实验与评估 | 现有基准依赖静态数据集、缺乏交互式迭代评估的问题 | 机器学习工程自动化 |
| 8 | http://arxiv.org/abs/2505.02820v3 | AutoLibra: Agent Metric Induction from Open-Ended Human Feedback | 将开放人类反馈转化为细粒度行为指标，自动化评估智能体 | 解决任务成功率指标粗糙，无法奖励中间行为的问题 | 通用语言智能体评估 |
| 9 | http://arxiv.org/abs/2505.03570v1 | OSUniverse: Benchmark for Multimodal GUI-navigation AI Agents | 提供复杂多模态桌面任务基准与自动化验证机制 | 解决 GUI 导航智能体缺乏标准化评估基准的问题 | 桌面 GUI 导航智能体 |
| 10 | http://arxiv.org/abs/2506.06287v1 | Deep Research Bench: Evaluating AI Web Research Agents | 构建包含 89 个多步 Web 研究任务的离线评估环境 | 解决 Web 研究智能体缺乏可控评估环境的问题 | Web 研究智能体评估 |
| 11 | http://arxiv.org/abs/2505.05115v1 | Is there a half-life for the success rates of AI agents? | 提出任务成功率随长度指数下降的半衰期模型 | 解决长周期任务中智能体失败原因分析与预测难题 | 智能体任务成功率分析 |
| 12 | http://arxiv.org/abs/2505.05283v3 | Software Development Life Cycle Perspective: A Survey of Benchmarks for Code Large Language Models and Agents | 从 SDLC 视角系统综述代码 LLM 与智能体基准 | 解决现有基准覆盖不均且缺乏防污染策略的问题 | 代码智能体基准评估 |
| 13 | http://arxiv.org/abs/2505.08638v3 | TRAIL: Trace Reasoning and Agentic Issue Localization | 构建 148 个人类标注轨迹数据集，定义 Agent 错误分类法 | 解决 Agent 工作流轨迹缺乏系统化评估与错误分析工具问题 | Agent 工作流调试与评估 |
| 14 | http://arxiv.org/abs/2505.13291v1 | TimeSeriesGym: A Scalable Benchmark for (Time Series) Machine Learning Engineering Agents | 引入可扩展的时序机器学习工程智能体基准框架 | 现有基准缺乏可扩展性与对 ML 工程实践的相关性 | 机器学习工程智能体 |
| 15 | http://arxiv.org/abs/2508.00828v1 | Finance Agent Benchmark: Benchmarking LLMs on Real-world Financial Research Tasks | 呈现包含真实世界金融研究问题的金融智能体基准 | 解决关于 LLM 智能体在金融领域全能力的显著疑问 | 金融研究任务 |
| 16 | http://arxiv.org/abs/2505.11368v2 | GuideBench: Benchmarking Domain-Oriented Guideline Following for LLM Agents | 构建评估 LLM 遵循领域指南能力的基准，涵盖规则遵守与鲁棒性。 | 缺乏评估 LLM 智能体遵循频繁更新领域指南能力的综合基准。 | 领域导向的 LLM 智能体评估 |
| 17 | http://arxiv.org/abs/2505.11891v3 | Mobile-Bench-v2: A More Realistic and Comprehensive Benchmark for VLM-based Mobile Agents | 构建含噪声、模糊指令 splits 的基准，评估多路径与主动交互能力。 | 现有基准奖励信号不稳、单路径评估且缺乏噪声与主动交互评估。 | 基于 VLM 的手机 GUI 智能体 |
| 18 | http://arxiv.org/abs/2505.11942v3 | LifelongAgentBench: Evaluating LLM Agents as Lifelong Learners | 首个统一基准评估 LLM 智能体终身学习能力，含技能接地与互依任务。 | 现有基准视智能体为静态系统，无法评估终身学习与知识积累。 | 动态环境中的自适应 LLM 智能体 |
| 19 | http://arxiv.org/abs/2505.12371v2 | MedAgentBoard: Benchmarking Multi-Agent Collaboration with Conventional Methods for Diverse Medical Tasks | 综合基准评估多智能体、单 LLM 与传统方法在四类医疗任务表现。 | 现有评估缺乏泛化性，未覆盖多样任务且缺乏 rigorous 对比。 | 医疗任务 AI 解决方案选择 |
| 20 | http://arxiv.org/abs/2505.12531v1 | ESC-Judge: A Framework for Comparing Emotional Support Conversational Agents | 端到端评估框架，基于 counseling model 自动化比较情感支持 LLM。 | 缺乏 scalable、theory-grounded 方式决定哪种模型最有效部署。 | 心理健康聊天机器人评估 |
| 21 | http://arxiv.org/abs/2505.12632v1 | Scalable Video-to-Dataset Generation for Cross-Platform Mobile Agents | 自动化框架利用公开视频创建任务数据集，含 OCR 检测与动作识别。 | 现有数据集单 OS 且标注 labor-intensive，需 cross-platform generalization。 | 移动 OS 导航任务数据集构建 |
| 22 | http://arxiv.org/abs/2505.15372v1 | X-WebAgentBench: A Multilingual Interactive Web Benchmark for Evaluating Global Agentic System | 引入多语言 Agent 基准，评估跨语言规划与交互性能 | 解决当前研究 predominantly 关注英语场景缺乏多语言评估问题 | 全球多语言 Agent 系统 |
| 23 | http://arxiv.org/abs/2505.15872v2 | InfoDeepSeek: Benchmarking Agentic Information Seeking for Retrieval-Augmented Generation | 提出 InfoDeepSeek 基准，评估动态 Web 环境中 Agent 信息寻求 | 解决现有基准 confined 于静态检索环境无法 eliciting 代理行为问题 | 检索增强生成系统 |
| 24 | http://arxiv.org/abs/2505.15935v3 | MAPS: A Multilingual Benchmark for Agent Performance and Security | 提出 MAPS 基准套件，翻译 11 种语言评估多语言 Agent 性能与安全 | 解决现有基准缺乏全面多领域安全 aware 多语言评估问题 | 多语言 Agent 系统评估 |
| 25 | http://arxiv.org/abs/2505.16100v1 | BioDSA-1K: Benchmarking Data Science Agents for Biomedical Research | 提出 BioDSA-1K 基准，评估 AI Agent 在生物医学假设验证任务 | 解决 AI Agent 因真实数据分析复杂性难以验证科学假设问题 | 生物医学研究数据科学 |
| 26 | http://arxiv.org/abs/2505.16801v2 | A modular framework for automated evaluation of procedural content generation in serious games with deep reinforcement learning agents | 提出方法论，结合 DRL 游戏测试 Agent 自动化评估 PCG 集成 | 解决评估 PCG 技术集成到严肃游戏中影响框架开发挑战问题 | 严肃游戏内容生成评估 |
| 27 | http://arxiv.org/abs/2505.16944v1 | AGENTIF: Benchmarking Instruction Following of Large Language Models in Agentic Scenarios | 首个智能体场景指令遵循基准，含真实长指令与复杂约束 | 解决智能体场景中长指令遵循能力评估缺失问题 | 大语言模型指令遵循能力 |
| 28 | http://arxiv.org/abs/2505.16986v2 | T1: A Tool-Oriented Conversational Dataset for Multi-Turn Agentic Planning | 工具增强多轮对话数据集，捕捉跨域工具依赖关系 | 解决多轮对话中工具调用依赖与规划评估难题 | 多工具依赖的规划场景 |
| 29 | http://arxiv.org/abs/2505.17512v2 | Is Your LLM Really Mastering the Concept? A Multi-Agent Benchmark | 基于多智能体社会推理游戏的动态概念知识基准 | 解决静态基准无法探测细粒度语义理解的问题 | 大语言模型概念理解评估 |
| 30 | http://arxiv.org/abs/2505.17572v1 | USTBench: Benchmarking and Dissecting Spatiotemporal Reasoning of LLMs as Urban Agents | 首个城市智能体时空推理基准，含理解/预测/规划/反思 | 解决城市 LLM 代理底层推理过程评估缺失问题 | 城市决策与 spatiotemporal 预测 |
| 31 | http://arxiv.org/abs/2505.17629v2 | TransBench: Breaking Barriers for Transferable Graphical User Interface Agents in Dynamic Digital Environments | 首个评估 GUI 代理跨版本/平台/应用迁移性的基准 | 解决 GUI 代理难以适应动态互联数字环境问题 | 动态数字环境中的 GUI 操作 |
| 32 | http://arxiv.org/abs/2505.18229v2 | BEDI: A Comprehensive Benchmark for Evaluating Embodied Agents on UAVs | 无人机具身代理基准，含动态任务链与六核心子技能 | 解决 UAV 代理缺乏标准化基准与测试场景问题 | 无人机自主任务评估 |
| 33 | http://arxiv.org/abs/2505.18746v4 | $C^3$-Bench: The Things Real Disturbing LLM based Agent in Multi-Tasking | 集成攻击概念，设计工具关系、隐藏信息及动态决策路径三大挑战基准。 | 现有评估忽略工具依赖、长上下文及策略切换对智能体鲁棒性影响。 | 多任务 LLM 智能体 |
| 34 | http://arxiv.org/abs/2505.18878v1 | CRMArena-Pro: Holistic Assessment of LLM Agents Across Diverse Business Scenarios and Interactions | 扩展十九项专家验证任务，涵盖多轮交互及保密意识评估的真实业务基准。 | 现有基准缺乏真实业务数据 fidelity 及多样场景覆盖。 | 企业级 LLM 智能体 |
| 35 | http://arxiv.org/abs/2505.19433v2 | Can Compressed LLMs Truly Act? An Empirical Evaluation of Agentic Capabilities in LLM Compression | 引入首个智能体压缩基准，评估压缩对工作流、工具使用等能力影响。 | 现有压缩基准忽略智能体能力，仅关注语言建模与理解任务。 | 模型压缩与部署 |
| 36 | http://arxiv.org/abs/2505.19477v3 | Judging with Many Minds: Do More Perspectives Mean Less Prejudice? On Bias Amplifications and Resistance in Multi-Agent Based LLM-as-Judge | 系统分析多智能体法官框架中的四种偏差，评估辩论与元法官机制。 | 多智能体评估设置中内在偏差如何manifest 及放大机制尚不明确。 | LLM 评估系统 |
| 37 | http://arxiv.org/abs/2505.19489v1 | Benchmarking and Enhancing LLM Agents in Localizing Linux Kernel Bugs | 构建 Linux 内核故障定位基准，提出增强框架提升代理定位有效性。 | 现有代理在大规模代码库及有限可观察性的内核故障定位上表现不佳。 | 软件故障定位 |
| 38 | http://arxiv.org/abs/2505.19623v2 | AgentRecBench: Benchmarking LLM Agent-based Personalized Recommender Systems | 提出交互式文本推荐模拟器及统一模块化框架， benchmark 经典与代理方法。 | 缺乏标准化评估协议系统评估代理推荐系统能力。 | 个性化推荐系统 |
| 39 | http://arxiv.org/abs/2505.19662v2 | FieldWorkArena: Agentic AI Benchmark for Real Field Work Tasks | 定义真实工作环境动作空间，改进评估函数，数据集含现场视频与文档。 | 现有基准局限于 Web 任务，不足以评估真实工作环境中的代理性能。 | 现场工作智能体 |
| 40 | http://arxiv.org/abs/2505.19897v2 | ScienceBoard: Evaluating Multimodal Autonomous Agents in Realistic Scientific Workflows | 构建真实多领域科学工作流环境和169个高质量任务基准 | 评估多模态智能体在复杂科学任务中的可靠性 | 科学发现工作流自动化 |
| 41 | http://arxiv.org/abs/2505.19955v3 | MLR-Bench: Evaluating AI Agents on Open-Ended Machine Learning Research | 201个研究任务+自动评估框架+模块化智能体脚手架 | 评估AI智能体在开放式科研任务中的可靠性 | 机器学习研究自动化 |
| 42 | http://arxiv.org/abs/2505.20148v3 | MineAnyBuild: Benchmarking Spatial Planning for Open-world AI Agents | Minecraft中4000个空间规划任务，评估理解/推理/创意/常识四维 | 现有基准缺乏抽象空间理解到具体任务执行的桥梁 | 开放世界智能体空间智能评估 |
| 43 | http://arxiv.org/abs/2505.20411v2 | SWE-rebench: An Automated Pipeline for Task Collection and Decontaminated Evaluation of Software Engineering Agents | 自动化管道持续采集21000+真实交互任务，构建无污染基准 | 高质量交互式软件工程数据稀缺及基准快速污染 | 软件工程智能体训练与评估 |
| 44 | http://arxiv.org/abs/2505.22583v1 | GitGoodBench: A Novel Benchmark For Evaluating Agentic Performance On Git | 首个Git版本控制操作Agent评测基准 | SE Agent缺乏VCS操作能力评估 | 软件工程AI Agent |
| 45 | http://arxiv.org/abs/2505.23239v1 | OSS-UAgent: An Agent-based Usability Evaluation Framework for Open Source Software | LLM Agent模拟不同经验级别开发者评估可用性 | 传统可用性评估成本高可扩展性差 | 开源软件可用性评估 |
| 46 | http://arxiv.org/abs/2505.23671v3 | GSO: Challenging Software Optimization Tasks for Evaluating SWE-Agents | 102个挑战性软件优化任务评测基准 | SWE-Agent高性能软件开发能力评估缺失 | 软件工程Agent评测 |
| 47 | http://arxiv.org/abs/2505.21279v2 | XBOUND: Exploring Capability Boundaries of Device-Control Agents at the State Level | 提出状态级评估框架 XBOUND，评估指令完成准确性 | 解决仅指令级评估忽略 GUI 环境交互上下文的问题 | 设备控制智能体 (DC Agents) |
| 48 | http://arxiv.org/abs/2505.21389v1 | AutoJudger: An Agent-Driven Framework for Efficient Benchmarking of MLLMs | 利用项目反应理论与自主代理动态选择测试问题 | 解决多模态大模型基准测试成本高、效率低问题 | 多模态大模型 (MLLMs) 评估 |
| 49 | http://arxiv.org/abs/2505.21731v1 | Deep Reinforcement Learning Agents are not even close to Human Intelligence | 引入 HackAtari 基准，测试 RL 代理在简化任务上的表现 | 解决 RL 代理缺乏零样本适应能力与依赖捷径问题 | 深度强化学习代理 |
| 50 | http://arxiv.org/abs/2505.22192v1 | Efficient Leave-one-out Approximation in LLM Multi-agent Debate Based on Introspection | 提出 IntrospecLOO，通过内省提示近似留一法评估代理贡献 | 解决 LLM 多代理辩论中评估个体贡献计算成本高问题 | LLM 多代理辩论系统 |
| 51 | http://arxiv.org/abs/2505.24787v1 | Draw ALL Your Imagine: A Holistic Benchmark and Agent Framework for Complex Instruction-based Image Generation | 提出 LongBench-T2I 基准及 Plan2Gen 框架，评估复杂指令遵循能力 | 解决现有基准无法捕捉复杂多面提示细微要求的问题 | 复杂指令驱动的图像生成模型 |
| 52 | http://arxiv.org/abs/2505.24876v1 | Agent-X: Evaluating Deep Multimodal Reasoning in Vision-Centric Agentic Tasks | 构建含 828 个任务的基准，评估多步多模态推理及工具使用能力 | 解决现有基准缺乏真实视觉上下文及多步推理评估框架的问题 | 视觉中心的多模态智能体 |
| 53 | http://arxiv.org/abs/2505.24878v1 | Open CaptchaWorld: A Comprehensive Web-based Platform for Testing and Benchmarking Multimodal LLM Agents | 首创基于 Web 的基准平台，含 20 种 CAPTCHA 类型及推理深度指标 | 解决多模态代理处理交互式多步推理挑战如 CAPTCHA 未测试的问题 | 多模态 LLM 代理的视觉推理 |
| 54 | http://arxiv.org/abs/2506.00172v1 | Breakpoint: Scalable evaluation of system-level reasoning in LLM code agents | 通过对抗性腐蚀函数自动生成代码修复任务，可控任务难度 | 解决现有长程套件依赖人工 curated 问题及评估快速饱和的问题 | LLM 代码代理的系统级推理 |
| 55 | http://arxiv.org/abs/2506.00618v3 | RiOSWorld: Benchmarking the Risk of Multimodal Computer-Use Agents | 构建含 492 个风险任务的基准，评估真实计算机操作中的安全风险 | 解决现有研究缺乏真实交互环境及风险类型狭窄限制全面评估的问题 | 多模态计算机使用代理的安全风险 |
| 56 | http://arxiv.org/abs/2506.00739v4 | DefenderBench: A Toolkit for Evaluating Language Agents in Cybersecurity Environments | 提供开源工具包，含网络入侵、恶意内容检测等评估环境 | 解决 LLM 代理在网络安全领域潜力未探索及缺乏公平严谨评估的问题 | 网络安全环境中的语言代理评估 |

[返回目录](#目录)

<a id="cat-07"></a>

## Agent可解释性与透明度

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2505.00875v1 | Thoughts without Thinking: Reconsidering the Explanatory Value of Chain-of-Thought Reasoning in LLMs through Agentic Pipelines | 分析CoT在Agent管道中的解释价值，发现CoT alone不提供真正可解释性 | Agent管道中CoT推理是否提升输出质量与可解释性存疑 | 人机中心可解释性（HCXAI） |
| 2 | http://arxiv.org/abs/2505.08073v2 | Explainable Reinforcement Learning Agents Using World Models | 引入反向世界模型生成反事实轨迹解释，展示世界应如何变化以偏好给定行动 | 非AI专家理解强化学习Agent时序决策过程的困难 | 可解释强化学习系统 |
| 3 | http://arxiv.org/abs/2505.11311v1 | Explaining Strategic Decisions in Multi-Agent Reinforcement Learning for Aerial Combat Tactics | 适配多种可解释性技术于空战场景，链接 AI 战术与人类理解推理。 | 多智能体强化学习在军事敏感场景缺乏可解释性，影响信任与安全。 | 军事空战战术规划与人员训练 |
| 4 | http://arxiv.org/abs/2505.11708v2 | Unveiling the Black Box: A Multi-Layer Framework for Explaining Reinforcement Learning-Based Cyber Agents | 提出多层可解释性框架，揭示 RL 攻击智能体的战略与战术推理。 | RL 网络攻击智能体决策过程 opaque，阻碍信任、调试与防御准备。 | 网络安全红队模拟与威胁建模 |
| 5 | http://arxiv.org/abs/2505.16288v2 | No Black Boxes: Interpretable and Interactable Predictive Healthcare with Knowledge-Enhanced Agentic Causal Discovery | 提出 II-KEA 框架，集成个性化知识库与 Agent LLM 增强可解释性 | 解决深度学习医疗模型缺乏可解释性与交互性限制问题 | predictive  healthcare 决策支持 |
| 6 | http://arxiv.org/abs/2505.17801v2 | Integrating Counterfactual Simulations with Language Models for Explaining Multi-Agent Behaviour | 利用 LLM  interrogate 模拟器生成反事实解释 | 解决多代理系统行为复杂导致用户信任校准难问题 | 自动驾驶等多代理场景 |
| 7 | http://arxiv.org/abs/2505.19316v2 | Making Teams and Influencing Agents: Efficiently Coordinating Decision Trees for Interpretable Multi-Agent Reinforcement Learning | 提出基于决策树的可解释 MARL 算法，协调训练并自适应分配交互预算。 | 可解释 MARL 策略在性能与计算效率之间难以兼顾的问题。 | 可解释多智能体系统 |
| 8 | http://arxiv.org/abs/2505.20127v2 | Agentic AI Process Observability: Discovering Behavioral Variability | 流程/因果发现+LLM静态分析，区分意图内/外行为变异性 | LLM智能体非确定性行为的可观测性与调试困难 | 智能体系统开发与运维 |

[返回目录](#目录)

<a id="cat-08"></a>

## 具身智能Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2505.00935v1 | Autonomous Embodied Agents: When Robotics Meets Deep Learning Reasoning | 完整具身Agent创建流程，从概念到部署的室内环境智能体实现 | 具身AI中机器人如何与未知环境持续交互并完成任务 | 室内环境机器人、具身AI |
| 2 | http://arxiv.org/abs/2505.05762v1 | Multi-Agent Systems for Robotic Autonomy with LLMs | 提出三核心Agent框架实现机器人任务分析、机械设计与路径生成 | 机器人系统开发效率低、可访问性差的问题 | 机器人自主系统研发 |
| 3 | http://arxiv.org/abs/2505.07532v1 | RAI: Flexible Agent Framework for Embodied AI | 提出RAI框架，支持Agent与机器人栈、LLM及仿真集成，提供ROS 2开箱即用集成 | 具身AI中多Agent系统构建与实体化机制不足问题 | 机器人系统与数字孪生 |
| 4 | http://arxiv.org/abs/2505.07634v3 | Neural Brain: A Neuroscience-inspired Framework for Embodied Agents | 提出神经科学启发的统一框架，整合多模态感知、认知与神经形态硬件优化 | 当前AI系统缺乏实体化、无法在动态环境中实时行动的问题 | 人形机器人等具身Agent |
| 5 | http://arxiv.org/abs/2505.03460v1 | LogisticsVLN: Vision-Language Navigation For Low-Altitude Terminal Delivery Based on Agentic UAVs | 集成轻量 LLM 与 VLM 的模块化无人机配送导航系统 | 解决无人机最后一公里配送中细粒度导航难题 | 低空物流终端配送 |
| 6 | http://arxiv.org/abs/2505.03673v2 | RoboOS: A Hierarchical Embodied Framework for Cross-Embodiment and Multi-Agent Collaboration | 基于脑 - 小脑架构的开源具身系统，支持跨形态协作 | 解决机器人系统跨形态适应性与多智能体协作不足问题 | 多机器人协作与制造 |
| 7 | http://arxiv.org/abs/2505.05108v2 | Multi-agent Embodied AI: Advances and Future Directions | 综述多智能体具身 AI 进展、挑战与未来方向 | 解决现有研究缺乏对动态开放环境多智能体具身 AI 综述 | 具身人工智能领域综述 |
| 8 | http://arxiv.org/abs/2505.08765v2 | Towards Autonomous UAV Visual Object Search in City Space: Benchmark and Agentic Methodology | 提出 PRPSearcher 方法，构建三类地图模拟人类三层认知 | 解决城市复杂环境中 UAV 自主视觉搜索效率与语义推理问题 | 城市空间 UAV 视觉搜索 |
| 9 | http://arxiv.org/abs/2505.10872v3 | REI-Bench: Can Embodied Agents Understand Vague Human Instructions in Task Planning? | 提出 REI-Bench 基准，建模模糊指代表达对任务规划影响 | 解决具身 Agent 难以理解非专家用户模糊指令问题 | 机器人任务规划 |
| 10 | http://arxiv.org/abs/2505.10887v2 | InfantAgent-Next: A Multimodal Generalist Agent for Automated Computer Interaction | 集成工具与纯视觉 Agent，模块化架构解决解耦任务 | 解决现有计算机交互 Agent 工作流复杂或仅支持单一模态问题 | 自动化计算机交互 |
| 11 | http://arxiv.org/abs/2505.12321v1 | BeliefNest: A Joint Action Simulator for Embodied Agents with Theory of Mind | 开源模拟器动态构建嵌套信念状态，支持具身智能体心智理论推理。 | 开放域任务需心智理论推理，缺乏显式表示嵌套信念状态的模拟器。 | Minecraft 环境中的具身协作任务 |
| 12 | http://arxiv.org/abs/2505.16348v4 | Embodied Agents Meet Personalization: Investigating Challenges and Solutions Through the Lens of Memory Utilization | 设计分层知识图谱用户画像记忆模块，管理个性化知识 | 解决具身 Agent 在利用用户特定知识提供个性化协助上挑战 | 具身智能 Agent 个性化 |
| 13 | http://arxiv.org/abs/2505.18214v1 | LA-RCS: LLM-Agent-Based Robot Control System | 双智能体框架，自主规划并适应外部环境变化 | 解决机器人控制中用户干预多及环境适应差问题 | 自主机器人控制任务 |
| 14 | http://arxiv.org/abs/2505.19767v1 | RFTF: Reinforcement Fine-tuning for Embodied Agents with Temporal Feedback | 利用价值模型生成密集奖励，结合时序信息消除对昂贵机器人动作标签依赖。 | 典型强化微调依赖稀疏结果奖励，难以提供具体动作细粒度反馈。 | 具身智能任务 |
| 15 | http://arxiv.org/abs/2505.19905v2 | EMAC+: Embodied Multimodal Agent for Collaborative Planning with VLM+LLM | 双向训练范式动态融合LLM高层规划与VLM实时视觉反馈 | LLM在机器人控制中缺乏视觉交互和领域知识适应 | 机器人任务执行与控制 |
| 16 | http://arxiv.org/abs/2505.20129v3 | Agentic 3D Scene Generation with Spatially Contextualized VLMs | 注入演化空间上下文（场景肖像/点云/超图）赋能VLM 3D推理 | VLM在结构化3D场景生成与理解中的能力局限 | 3D内容生成与具身仿真 |
| 17 | http://arxiv.org/abs/2505.20726v2 | ManiTaskGen: A Comprehensive Task Generator for Benchmarking and Improving Vision-Language Agents on Embodied Decision-Making | 任意场景自动生成多样化可行任务，支持流程/结果双类型指令 | 现有基准任务有限场景单一，缺乏全面评估具身决策能力 | 具身机器人任务规划与评估 |
| 18 | http://arxiv.org/abs/2505.22634v2 | LabUtopia: High-Fidelity Simulation and Hierarchical Benchmark for Scientific Embodied Agents | 高保真实验室仿真器与五层复杂度基准 | 科学具身Agent缺乏合适仿真器和基准 | 实验室自动化具身Agent |
| 19 | http://arxiv.org/abs/2505.23450v2 | Agentic Robot: A Brain-Inspired Framework for Vision-Language-Action Models in Embodied Agents | 脑启发SAP协调协议支持动态自验证 | 长程机器人操作误差累积缺乏验证机制 | 长程机器人操作任务 |
| 20 | http://arxiv.org/abs/2505.21969v4 | DORAEMON: Decentralized Ontology-aware Reliable Agent with Enhanced Memory Oriented Navigation | 模仿人类导航的双流框架，含层次语义空间融合与拓扑图 | 解决 VLM 零_shot 导航中时空不连续与记忆非结构化问题 | 家庭服务机器人导航 |
| 21 | http://arxiv.org/abs/2505.22503v2 | Communication-Efficient Desire Alignment for Embodied Agent-Human Adaptation | 提出 FAMER 框架，含基于欲望的心理推理与反射通信模块 | 解决具身代理在模糊指令下快速对齐用户潜在欲望问题 | 具身代理与人协作 |
| 22 | http://arxiv.org/abs/2506.00138v2 | Intrinsic Goals for Autonomous Agents: Model-Based Exploration in Virtual Zebrafish Predicts Ethological Behavior and Whole-Brain Dynamics | 提出 3M-Progress 方法，通过内在目标驱动自主具身代理预测脑数据 | 解决现有 RL 探索模式不一致及未能捕捉动物鲁棒自主行为的问题 | 虚拟斑马鱼自主行为与神经动力学 |

[返回目录](#目录)

<a id="cat-09"></a>

## 多Agent协作与通信

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2507.17753v1 | Exploring Communication Strategies for Collaborative LLM Agents in Mathematical Problem-Solving | 比较四种通信模式，发现同伴协作效果最佳 | 不同通信策略对Agent协作解题效率影响缺乏系统评估 | AI辅助教育、数学问题求解 |
| 2 | http://arxiv.org/abs/2505.00981v1 | Multi-agents based User Values Mining for Recommendation | ZOOM框架采用评估者+监督者双Agent角色协同提取用户价值观 | 推荐系统难以获取稳定长期用户价值观，直接LLM提取有幻觉 | 推荐系统、用户偏好建模 |
| 3 | http://arxiv.org/abs/2505.02133v1 | Enhancing LLM Code Generation: A Systematic Evaluation of Multi-Agent Collaboration and Runtime Debugging for Improved Accuracy, Reliability, and Latency | 链式系统组合多Agent协作与运行时调试，评估19个LLM | 代码生成质量需优化，单一策略效果有限 | 自动化代码生成 |
| 4 | http://arxiv.org/abs/2505.02648v2 | MCCD: Multi-Agent Collaboration-based Compositional Diffusion for Complex Text-to-Image Generation | 多Agent协作场景解析+分层组合扩散，无需训练提升复杂场景生成 | 扩散模型处理多对象/特征/关系复杂提示时性能瓶颈 | 复杂场景文本生成图像 |
| 5 | http://arxiv.org/abs/2505.07603v1 | AgentFlow: Resilient Adaptive Cloud-Edge Framework for Multi-Agent Coordination | 提出基于物流对象与抽象Agent接口的框架，支持去中心化发布订阅与服务选举 | 异构云边环境中多Agent协调的可扩展性与容错问题 | 任务关键型分布式系统 |
| 6 | http://arxiv.org/abs/2505.07779v1 | Multi-Agent Path Finding via Finite-Horizon Hierarchical Factorization | 提出有限视界层次分解框架，支持并行个体规划与动态冲突分组 | 大规模多Agent路径查找在动态环境中的响应时间问题 | 自动化仓库等动态环境 |
| 7 | http://arxiv.org/abs/2505.08025v1 | PRISM: Complete Online Decentralized Multi-Agent Pathfinding with Rapid Information Sharing using Motion Constraints | 提出去中心化PRISM算法，通过运动约束信息包实现快速信息共享与避障 | 去中心化多Agent路径查找中的死锁与可扩展性问题 | 大规模多Agent系统 |
| 8 | http://arxiv.org/abs/2505.03961v2 | The Power of Stories: Narrative Priming Shapes How LLM Agents Collaborate and Compete | 发现叙事 priming 显著影响 LLM 智能体协作策略 | 解决多智能体系统中协作动机与对齐机制设计问题 | 多智能体协作与博弈 |
| 9 | http://arxiv.org/abs/2505.17030v2 | Distillation-Enabled Knowledge Alignment Protocol for Semantic Communication in AI Agent Networks | 蒸馏专家知识到低秩矩阵实现多智能体知识对齐 | 解决多智能体网络中知识异构与通信开销大问题 | 多智能体语义通信 |
| 10 | http://arxiv.org/abs/2505.13466v1 | AgentSGEN: Multi-Agent LLM in the Loop for Semantic Collaboration and GENeration of Synthetic Data | 评估者与编辑器智能体迭代协作生成安全关键场景数据 | 解决危险场景真实数据稀缺且合成数据语义不足问题 | 安全关键场景数据生成 |
| 11 | http://arxiv.org/abs/2505.08532v1 | The Truth Becomes Clearer Through Debate! Multi-Agent Systems with Large Language Models Unmask Fake News | 引入辩论流程 Agent，模拟正反方辩论与洞察合成 | 解决假新闻检测可解释性差及 LLM 推理能力利用不足问题 | 社交媒体假新闻检测 |
| 12 | http://arxiv.org/abs/2505.11556v3 | Systematic Failures in Collective Reasoning under Distributed Information in Multi-Agent LLMs | 引入 HiddenBench 基准，揭示多 Agent 集体推理系统性失败 | 解决多 Agent 在分布式信息下无法识别潜在信息不对称问题 | 多 Agent 集体决策 |
| 13 | http://arxiv.org/abs/2505.10936v3 | Cochain: Balancing Insufficient and Excessive Collaboration in LLM Agent Workflows | 构建集成知识图谱与提示树，平衡协作成本与效果 | 解决单 Agent 提示复杂及多 Agent 令牌消耗过大问题 | 业务工作流协作 |
| 14 | http://arxiv.org/abs/2505.11107v1 | Group Think: Multiple Concurrent Reasoning Agents Collaborating at Token Level Granularity | 单 LLM 扮演多并发推理 Agent，token 级动态协作生成 | 解决多 Agent 轮流交互延迟高及冗余推理问题 | 高效协同推理生成 |
| 15 | http://arxiv.org/abs/2505.13311v1 | Synthesis of Communication Policies for Multi-Agent Systems Robust to Communication Restrictions | 合成对通信限制鲁棒的联合动作与通信策略 | 解决多智能体系统在带宽受限下的协作与目标达成问题 | 随机多智能体系统 |
| 16 | http://arxiv.org/abs/2505.13994v2 | Divide by Question, Conquer by Agent: SPLIT-RAG with Question-Driven Graph Partitioning | 提出基于问题驱动语义图划分与协作子图检索的多智能体 RAG | 解决大规模知识图谱 RAG 系统中效率与准确性的权衡 | 检索增强生成系统 |
| 17 | http://arxiv.org/abs/2505.14569v1 | Agent Context Protocols Enhance Collective Inference | 引入智能体上下文协议 ACPs 用于结构化通信与协调 | 解决通用系统构建中协调处理不精确与自然语言限制问题 | 多智能体集体推理 |
| 18 | http://arxiv.org/abs/2505.17086v3 | Advancing Multi-Agent RAG Systems with Minimalist Reinforcement Learning | 提出统一框架 Mujica-MyGo 用于 RAG 中高效多轮推理 | 解决多轮交互产生长中间上下文导致 LLM 利用信息困难 | 多智能体 RAG 系统 |
| 19 | http://arxiv.org/abs/2505.11765v2 | OMAC: A Broad Optimization Framework for LLM-Based Multi-Agent Collaboration | 识别五个优化维度，提出语义初始化与对比比较器算法优化协作。 | 基于 LLM 的多智能体系统开发依赖手工方法，缺乏系统设计优化。 | 代码生成、算术与通用推理任务 |
| 20 | http://arxiv.org/abs/2505.13523v1 | ACPs: Agent Collaboration Protocols for the Internet of Agents | 提出代理协作协议套件，含注册、发现、交互与工具协议，支持 IoA。 | 现有协议 fragmented 且场景特定，缺乏互操作性与标准化。 | 智能体互联网基础设施 |
| 21 | http://arxiv.org/abs/2505.12467v1 | Beyond Frameworks: Unpacking Collaboration Strategies in Multi-Agent Systems | 系统调查治理、参与控制、交互动态与对话历史管理四维度策略。 | 协作 granular 机制 underexplored，缺乏对性能与 scalability 影响量化。 | 可扩展多智能体系统设计 |
| 22 | http://arxiv.org/abs/2505.15047v4 | PiFlow: Principle-Aware Scientific Discovery with Multi-Agent Collaboration | 引入信息论框架，将科学发现视为结构化不确定性减少问题 | 解决现有工作流缺乏理性约束导致假设无目的性问题 | 自动化科学发现与研究 |
| 23 | http://arxiv.org/abs/2505.15076v1 | Agentic Feature Augmentation: Unifying Selection and Generation with Teaming, Planning, and Memories | 提出 MAGS 系统，统一特征选择与生成，利用路由 Agent 协调 | 解决特征工程中冗余减少与增加有意义维度难以平衡问题 | 人工智能模型特征工程 |
| 24 | http://arxiv.org/abs/2505.17115v2 | Swarm Intelligence Enhanced Reasoning: A Density-Driven Framework for LLM-Based Multi-Agent Optimization | 提出 SIER 框架，集成群体智能引导 Agent 协作搜索最优解 | 解决 CoT 等方法在复杂问题中缺乏寻找最优解能力问题 | 大模型复杂问题推理 |
| 25 | http://arxiv.org/abs/2505.16086v2 | Optimizing LLM-Based Multi-Agent System with Textual Feedback: A Case Study on Software Development | 提出两步 Agent 提示优化 pipeline，利用文本反馈优化系统提示 | 解决优化基于 LLM 多 Agent 系统仍具挑战性问题 | 软件开发多 Agent 系统 |
| 26 | http://arxiv.org/abs/2505.16281v3 | HiMATE: A Hierarchical Multi-Agent Framework for Machine Translation Evaluation | 提出分层多 Agent 框架，基于 MQM 错误类型学进行细粒度评估 | 解决现有 LLM 评估方法准确识别错误跨度与严重性挑战问题 | 机器翻译自动评估 |
| 27 | http://arxiv.org/abs/2505.20310v2 | Manalyzer: End-to-end Automated Meta-analysis with Multi-agent System | 提出 Manalyzer 多 Agent 系统，通过工具调用实现端到端 Meta 分析 | 解决传统 Meta 分析流程复杂耗时及 LLM 方法幻觉挑战问题 | 自动化科学 Meta 分析 |
| 28 | http://arxiv.org/abs/2505.16576v2 | EMULATE: A Multi-Agent Framework for Determining the Veracity of Atomic Claims by Emulating Human Actions | 提出 EMULATE 系统，多 Agent 框架模拟人类动作验证原子主张 | 解决现有事实核查过程偏离人类实际操作流程问题 | 原子主张真实性验证 |
| 29 | http://arxiv.org/abs/2505.16832v2 | From EduVisBench to EduVisAgent: A Benchmark and Multi-Agent Framework for Reasoning-Driven Pedagogical Visualization | 多智能体协作框架，协调教学规划与可视化设计代理 | 解决基础模型生成教育可视化效果有限的问题 | 教育领域的视觉推理 |
| 30 | http://arxiv.org/abs/2505.16997v1 | X-MAS: Towards Building Multi-Agent Systems with Heterogeneous LLMs | 异构 LLM 驱动的多智能体系统，利用集体智能提升性能 | 解决单一 LLM 限制系统智能上限的问题 | 多领域多智能体协作 |
| 31 | http://arxiv.org/abs/2505.17492v1 | PD$^3$: A Project Duplication Detection Framework via Adapted Multi-Agent Debate | adapted 多智能体辩论框架，结合定性定量分析反馈 | 解决项目重复检测缺乏深度理解与专家洞察问题 | 电力项目质量评估 |
| 32 | http://arxiv.org/abs/2505.17511v1 | Multi-agent Systems for Misinformation Lifecycle : Detection, Correction And Source Identification | 五专用智能体框架，覆盖 misinformation 全生命周期 | 解决单一模型检测 misinformation 缺乏透明与可靠问题 | 数字媒体 misinformation 治理 |
| 33 | http://arxiv.org/abs/2505.18218v1 | CoMet: Metaphor-Driven Covert Communication for Multi-Agent Language Games | 结合假设推理与生成器的隐喻处理框架 | 解决 LLM 在多代理游戏中隐喻理解与应用困难问题 | 隐蔽通信与语义规避游戏 |
| 34 | http://arxiv.org/abs/2505.18105v1 | ManuSearch: Democratizing Deep Search in Large Language Models with a Transparent and Open Multi-Agent Framework | 透明模块化多代理框架，分解搜索与推理过程 | 解决深度搜索能力被专有系统锁定且不透明问题 | 开放网络深度推理 |
| 35 | http://arxiv.org/abs/2505.18943v3 | MetaMind: Modeling Human Social Thoughts with Metacognitive Multi-Agent Systems | 分解为社会理解三阶段，含心智理论、道德及响应代理的协作框架。 | 大模型难以处理人类沟通中的歧义与上下文细微差别。 | 社交智能对话 |
| 36 | http://arxiv.org/abs/2505.19591v2 | Multi-Agent Collaboration via Evolving Orchestration | 提出木偶师范式，中央编排者经强化学习动态指导代理序列与优先级。 | 静态组织结构难以适应任务复杂度增长，导致协调开销与低效。 | 多智能体协作系统 |
| 37 | http://arxiv.org/abs/2505.19647v1 | Select, Read, and Write: A Multi-Agent Framework of Full-Text-based Related Work Generation | 含选择、阅读、写作三代理，提出图感知策略优化阅读顺序。 | 现有方法因输入有限及孤立解释导致相关工作生成理解浅显。 | 学术写作辅助 |
| 38 | http://arxiv.org/abs/2505.20096v2 | MA-RAG: Multi-Agent Retrieval-Augmented Generation via Collaborative Chain-of-Thought Reasoning | 规划/定义/抽取/问答四智能体协作，链式思维传递中间推理 | 复杂信息检索任务中的歧义消解和多跳推理挑战 | 多跳问答与复杂信息检索 |
| 39 | http://arxiv.org/abs/2505.20521v2 | Project Riley: Multimodal Multi-Agent LLM Collaboration with Emotional Reasoning and Voting | 五情感智能体结构化多轮对话+投票机制，融合多视角生成响应 | 单一模型难以模拟情感状态影响的复杂推理过程 | 情感化人机对话与应急信息传递 |
| 40 | http://arxiv.org/abs/2505.20625v3 | Long Context Scaling: Divide and Conquer via Multi-Agent Question-driven Collaboration | 动态分区+问题引导协议+状态追踪选择性重放，高效处理超长上下文 | 现有分治方法累积延迟、信息丢失及文本依赖破坏 | 超长文本理解与知识密集型问答 |
| 41 | http://arxiv.org/abs/2505.20816v1 | Rethinking Information Synthesis in Multimodal Question Answering A Multi-Agent Perspective | 三智能体分工（分解/合成/整合），跨模态推理提升准确性与可解释性 | 单模型多模态推理忽略模态特性限制准确性与可解释性 | 多模态问答与信息融合 |
| 42 | http://arxiv.org/abs/2505.23846v1 | Scalable, Symbiotic, AI and Non-AI Agent Based Parallel Discrete Event Simulations | AI与非AI Agent因果耦合的PDES方法论 | AI Agent输出缺乏约束和正确性保证 | 大规模可信AI系统仿真 |
| 43 | http://arxiv.org/abs/2505.22960v2 | Revisiting Multi-Agent Debate as Test-Time Scaling: A Systematic Study of Conditional Effectiveness | 系统研究多Agent辩论的条件有效性 | MAD有效性缺乏系统性理解 | 数学推理和安全任务 |
| 44 | http://arxiv.org/abs/2505.23187v1 | Cross-Task Experiential Learning on LLM-based Multi-Agent Collaboration | 多Agent跨任务经验学习框架 | 任务孤立处理导致计算冗余泛化有限 | LLM多Agent协作系统 |
| 45 | http://arxiv.org/abs/2505.23275v1 | Wireless Agentic AI with Retrieval-Augmented Multimodal Semantic Perception | 检索增强多模态语义通信框架 | 无线多Agent场景带宽限制语义信息交换 | 多Agent自动驾驶 |
| 46 | http://arxiv.org/abs/2505.23352v1 | Understanding the Information Propagation Effects of Communication Topologies in LLM-based Multi-Agent Systems | 提出EIB-learner平衡错误抑制与信息传播 | 通信拓扑稀疏/稠密何时助力协作不明 | LLM多Agent系统通信设计 |
| 47 | http://arxiv.org/abs/2505.23399v1 | GAM-Agent: Game-Theoretic and Uncertainty-Aware Collaboration for Complex Visual Reasoning | 博弈论+不确定性感知多Agent视觉推理框架 | 单Agent模型视觉推理鲁棒性不足 | 视觉语言推理任务 |
| 48 | http://arxiv.org/abs/2506.00066v1 | Literature Review Of Multi-Agent Debate For Problem-Solving | 多Agent辩论问题求解文献综述 | 领域缺乏直接比较和系统性理解 | MA-LLM研究者与实践者 |
| 49 | http://arxiv.org/abs/2506.00073v4 | The Automated but Risky Game: Modeling and Benchmarking Agent-to-Agent Negotiations and Transactions in Consumer Markets | Agent间谈判交易实验框架与风险评估 | 完全自动化交易存在财务损失风险 | 消费者市场Agent交易 |
| 50 | http://arxiv.org/abs/2505.23946v2 | Lessons Learned: A Multi-Agent Framework for Code LLMs to Learn and Improve | 基于课程的多Agent协作学习框架 | 未知LLM互补优势时如何协作 | 代码优化任务 |
| 51 | http://arxiv.org/abs/2505.21588v1 | Herd Behavior: Investigating Peer Influence in LLM-based Multi-Agent Systems | 揭示智能体从众行为受自信差距与信息呈现格式影响 | 解决多智能体系统中peer influence 机制不明问题 | LLM 多智能体协作系统 |
| 52 | http://arxiv.org/abs/2505.21116v1 | Creativity in LLM-based Multi-Agent Systems: A Survey | 首份针对多智能体系统创造力的调查，提出分类法与评估指标 | 解决现有调查忽视多智能体创造力维度的问题 | 文本与图像生成任务 |
| 53 | http://arxiv.org/abs/2505.21298v4 | Large Language Models Miss the Multi-Agent Mark | 指出当前 MAS LLM 缺乏自主性、社交互动等核心多智能体特征 | 解决多智能体术语滥用与理论基础缺失问题 | 多智能体系统研究与设计 |
| 54 | http://arxiv.org/abs/2505.21471v1 | Scaling External Knowledge Input Beyond Context Windows of LLMs via Multi-Agent Collaboration | 开发 ExtAgents 框架，通过多代理协作扩展外部知识输入 | 解决 LLM 上下文窗口限制大规模知识输入问题 | 需要大量外部知识的复杂任务 |
| 55 | http://arxiv.org/abs/2505.21503v1 | Silence is Not Consensus: Disrupting Agreement Bias in Multi-Agent LLMs via Catfish Agent for Clinical Decision Making | 引入 Catfish Agent 角色，注入结构化异议以打破沉默共识 | 解决多代理临床决策中过早收敛与缺乏批判分析问题 | 临床问答与决策系统 |
| 56 | http://arxiv.org/abs/2505.21898v1 | Co-Saving: Resource Aware Multi-Agent Collaboration for Software Development | 引入“捷径”机制，利用历史成功轨迹跳过冗余推理代理 | 解决多代理系统资源 unaware 导致 token 消耗高问题 | 软件开发任务 |
| 57 | http://arxiv.org/abs/2505.22053v2 | AudioGenie: A Training-Free Multi-Agent Framework for Diverse Multimodality-to-Multiaudio Generation | 双层架构含生成与监督团队，实现多模态到多音频生成 | 解决 MM2MA 任务缺乏细粒度理解与自校正机制问题 | 多模态音频生成 |
| 58 | http://arxiv.org/abs/2505.22467v3 | Topological Structure Learning Should Be A Research Priority for LLM-Based Multi-Agent Systems | 呼吁转向拓扑感知 MAS，提出三阶段框架优化交互结构 | 解决 MAS 拓扑配置与协调未被充分探索问题 | LLM 多智能体系统设计 |
| 59 | http://arxiv.org/abs/2505.24442v1 | RMoA: Optimizing Mixture-of-Agents through Diversity Maximization and Residual Compensation | 集成残差连接优化效率，设计基于嵌入的多样性选择机制 | 解决多智能体系统计算开销高、信息丢失及鲁棒性 limited 的问题 | 高效可靠的多智能体混合系统 |
| 60 | http://arxiv.org/abs/2505.24671v2 | Multiple LLM Agents Debate for Equitable Cultural Alignment | 提出多智能体辩论框架，通过辩论或自反思达成文化适配决策 | 解决单 LLM 方法难以适应多样文化背景及社会规范的问题 | 跨文化社会礼仪规范适配 |
| 61 | http://arxiv.org/abs/2506.00555v3 | MMedAgent-RL: Optimizing Multi-Agent Collaboration for Multimodal Medical Reasoning | 基于 RL 训练分诊与主治代理，实现动态优化的多智能体协作 | 解决静态流水线缺乏灵活性及专家输出不一致限制性能的问题 | 多模态医疗推理与诊断 |

[返回目录](#目录)

<a id="cat-10"></a>

## 多Agent强化学习

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2505.01115v2 | Exploring Equity of Climate Policies using Multi-Agent Multi-Objective Reinforcement Learning | Justice框架首次整合IAM与MOMARL，生成公平帕累托最优政策 | 传统IAM单目标优化无法捕捉气候政策中的公平权衡 | 气候政策制定、国际谈判 |
| 2 | http://arxiv.org/abs/2505.01336v2 | Enhancing Diversity in Parallel Agents: A Maximum State Entropy Exploration Story | 最大化并行设置中收集数据熵，平衡个体熵与Agent间多样性 | 并行RL中N个相同Agent是否存在策略专业化超越N倍加速 | 并行强化学习数据收集 |
| 3 | http://arxiv.org/abs/2505.02215v1 | Interpretable Emergent Language Using Inter-Agent Transformers | DIAT利用自注意力学习符号化、人类可理解的通信协议 | 现有MARL通信方法缺乏可解释性 | 复杂多Agent环境协作任务 |
| 4 | http://arxiv.org/abs/2505.02293v1 | Resolving Conflicting Constraints in Multi-Agent Reinforcement Learning with Layered Safety | 分层安全MARL框架，结合MARL与安全过滤器解决冲突约束 | 多机器人导航中不同Agent约束冲突阻碍安全协调 | 多机器人导航、高密度空中交通 |
| 5 | http://arxiv.org/abs/2505.05968v2 | Offline Multi-agent Reinforcement Learning via Score Decomposition | 提出序列评分函数分解方法，从联合行为策略中提取单Agent正则化信号 | 离线多Agent强化学习中的分布偏移与多均衡问题 | 多Agent协作任务 |
| 6 | http://arxiv.org/abs/2505.06200v2 | Robust Multi-Agent Decision-Making in Finite-Population Games | 分析KLD-RL模型参数对噪声和建模误差的鲁棒性影响 | 有限群体博弈中Agent决策的噪声与建模不准确问题 | 工程应用中的群体博弈 |
| 7 | http://arxiv.org/abs/2505.06378v1 | Bi-LSTM based Multi-Agent DRL with Computation-aware Pruning for Agent Twins Migration in Vehicular Embodied AI Networks | 提出TMABLPPO算法与个性化神经网络剪枝，优化车联网Agent迁移 | 车联网中计算负载不均衡与迁移延迟问题 | 车联网与路侧单元系统 |
| 8 | http://arxiv.org/abs/2505.06997v1 | A Multi-Agent Reinforcement Learning Approach for Cooperative Air-Ground-Human Crowdsensing in Emergency Rescue | 提出HECTA4ER算法，实现无人机、无人车与人类的协同感知任务分配 | 应急救援中异构实体协同感知任务优化问题 | 应急救援与众包感知 |
| 9 | http://arxiv.org/abs/2505.07207v2 | HYGMA: Hypergraph Coordination Networks with Dynamic Grouping for Multi-Agent Reinforcement Learning | 整合动态谱聚类与超图神经网络，实现自适应群体形成与信息处理 | 多Agent系统中Agent关系组织与信息交换的动态适应问题 | 协作多Agent任务 |
| 10 | http://arxiv.org/abs/2505.07257v1 | DARLR: Dual-Agent Offline Reinforcement Learning for Recommender Systems with Dynamic Reward | 提出双Agent框架DARLR，动态更新世界模型以增强推荐策略 | 推荐系统中奖励函数不准确与静态不确定性设计问题 | 推荐系统 |
| 11 | http://arxiv.org/abs/2505.07290v2 | Multi-Agent DRL for Multi-Objective Twin Migration Routing with Workload Prediction in 6G-enabled IoV | 提出LSTM-Transformer预测负载，DM-MAPPO算法优化车辆孪生迁移路由 | 6G车联网中车辆移动导致通信中断与服务质量问题 | 6G车联网与边缘计算 |
| 12 | http://arxiv.org/abs/2505.08825v1 | Multi-source Plume Tracing via Multi-Agent Reinforcement Learning | 提出基于LSTM的ADDRQN算法，利用历史行动 - 观测序列定位多个空气污染源 | 传统方法在湍流条件下追踪污染源的可靠性不足问题 | 工业灾难应急响应 |
| 13 | http://arxiv.org/abs/2505.03288v4 | Game Theory and Multi-Agent Reinforcement Learning for Zonal Ancillary Markets | 结合博弈论与 MARL 计算区域辅助市场均衡 | 解决市场耦合中的均衡计算效率与成本分配问题 | 电力辅助市场交易 |
| 14 | http://arxiv.org/abs/2505.03558v1 | Multi-Agent Reinforcement Learning Scheduling to Support Low Latency in Teleoperated Driving | 基于 MAPPO 的动态无线电资源调度算法 | 解决远程驾驶中端到端延迟与可靠性约束问题 | 远程驾驶通信调度 |
| 15 | http://arxiv.org/abs/2505.03586v4 | Rainbow Delay Compensation: A Multi-Agent Reinforcement Learning Framework for Mitigating Delayed Observation | 提出彩虹延迟补偿框架解决随机个体观测延迟 | 解决多智能体系统中观测延迟导致的性能下降问题 | 延迟环境下的多智能体系统 |
| 16 | http://arxiv.org/abs/2505.03949v1 | Deep Q-Network (DQN) multi-agent reinforcement learning (MARL) for Stock Trading | 结合 CNN-LSTM 特征提取与 DQN 的多智能体交易框架 | 解决股票交易中市场噪声大与策略泛化难的问题 | 自动化股票交易 |
| 17 | http://arxiv.org/abs/2505.04231v1 | Multi-Agent Reinforcement Learning-based Cooperative Autonomous Driving in Smart Intersections | 基于 RSU 的两阶段混合 RL 框架协调无信号路口车辆 | 解决无信号路口交通流复杂导致的安全与效率挑战 | 智能路口协同驾驶 |
| 18 | http://arxiv.org/abs/2505.04339v1 | Adaptive and Robust DBSCAN with Multi-agent Reinforcement Learning | 多智能体 RL 引导 DBSCAN 参数自适应搜索 | 解决 DBSCAN 处理变密度数据集聚类效果差的问题 | 数据挖掘与聚类分析 |
| 19 | http://arxiv.org/abs/2505.07854v1 | CCL: Collaborative Curriculum Learning for Sparse-Reward Multi-Agent Reinforcement Learning via Co-evolutionary Task Evolution | 协同课程学习框架，共进化任务与智能体解决稀疏奖励 | 解决稀疏奖励环境下多智能体学习反馈延迟与次优问题 | 稀疏奖励多智能体学习 |
| 20 | http://arxiv.org/abs/2505.05262v2 | Enhancing Cooperative Multi-Agent Reinforcement Learning with State Modelling and Adversarial Exploration | 状态建模与对抗探索增强合作多智能体强化学习 | 解决无通信部分可观察环境下合作策略学习难题 | 合作多智能体强化学习 |
| 21 | http://arxiv.org/abs/2505.08222v2 | Scaling Multi Agent Reinforcement Learning for Underwater Acoustic Tracking via Autonomous Vehicles | 提出迭代蒸馏方法，将高保真仿真迁移至 GPU 加速环境 | 解决多智能体强化学习训练计算成本高、样本效率低问题 | 水下自主车辆舰队跟踪 |
| 22 | http://arxiv.org/abs/2505.08448v2 | Scalable UAV Multi-Hop Networking via Multi-Agent Reinforcement Learning with Large Language Models | 整合 MARL 与 LLM，利用知识蒸馏优化 UAV 网络决策 | 解决大规模动态环境下 UAV 组网算法可扩展性差问题 | 灾难场景应急通信网络 |
| 23 | http://arxiv.org/abs/2505.08630v1 | Credit Assignment and Efficient Exploration based on Influence Scope in Multi-agent Reinforcement Learning | 计算 Agent 影响范围 ISA，用于信用分配与探索空间界定 | 解决稀疏奖励场景下多 Agent 信用分配与探索效率低问题 | 稀疏奖励多 Agent 任务 |
| 24 | http://arxiv.org/abs/2505.08995v1 | Enhancing Aerial Combat Tactics through Hierarchical Multi-Agent Reinforcement Learning | 分层 MARL 框架，分离底层控制与高层指挥策略 | 解决空战场景状态动作空间大及实时控制与规划整合难题 | 模拟空中作战战术分析 |
| 25 | http://arxiv.org/abs/2505.09756v1 | Community-based Multi-Agent Reinforcement Learning with Transfer and Active Exploration | 基于社区结构的 MARL 框架，支持迁移学习与主动探索 | 解决时间演化网络中 Agent 灵活协调与结构化信息共享问题 | 动态网络多 Agent 协作 |
| 26 | http://arxiv.org/abs/2505.10484v1 | Fixing Incomplete Value Function Decomposition for Multi-Agent Reinforcement Learning | 提出 QFIX 家族模型，通过薄修复层扩展值函数分解表示能力 | 解决现有 MARL 值分解方法表示能力有限或不必要复杂问题 | 合作多 Agent 强化学习 |
| 27 | http://arxiv.org/abs/2505.11100v1 | Bidirectional Distillation: A Mixed-Play Framework for Multi-Agent Generalizable Behaviors | 双向蒸馏框架，交替模拟历史策略与驱动新分布 | 解决 MARL 自-play 方法泛化能力受限及策略空间单一问题 | 多 Agent 泛化行为 |
| 28 | http://arxiv.org/abs/2505.12811v1 | Dynamic Sight Range Selection in Multi-Agent Reinforcement Learning | 提出动态视线范围选择方法，利用 UCB 算法调整感知 | 解决多智能体强化学习中信息不足或过多的视线范围困境 | 多智能体强化学习环境 |
| 29 | http://arxiv.org/abs/2505.11307v1 | Diffusion Learning with Partial Agent Participation and Local Updates | 提出局部更新与部分智能体参与的扩散学习框架，降低通信开销。 | 传统扩散学习通信开销大，边缘设备易波动导致通信不可靠。 | 边缘设备智能学习系统 |
| 30 | http://arxiv.org/abs/2505.11461v2 | Signal attenuation enables scalable decentralized multi-agent reinforcement learning over networks | 利用信号衰减特性实现 MARL 去中心化，推导局部邻域近似与误差界。 | 全局状态可观测性限制 MARL 去中心化与 scalability，实际衰减特性未explored。 | 无线通信与雷达网络功率分配 |
| 31 | http://arxiv.org/abs/2505.15836v1 | Quantum-Evolutionary Neural Networks for Multi-Agent Federated Learning | 结合量子启发神经网络与进化算法优化多智能体实时决策，保护隐私。 | 复杂去中心化环境需 scalable、自适应且隐私保护的决策系统。 | 自主系统、智慧城市与医疗 |
| 32 | http://arxiv.org/abs/2505.12204v3 | Of Mice and Machines: A Comparison of Learning Between Real World Mice and RL Agents | 比较生物小鼠与 RL 智能体学习，提出机制鼓励自然主义风险规避行为。 | RL 智能体缺乏自我保护本能，与生物 agent 风险评估行为 disparity。 | 强化学习行为对齐与生物启发 |
| 33 | http://arxiv.org/abs/2505.12406v2 | Steady-State Strategy Synthesis for Swarms of Autonomous Agents | 设计高效 scalable 合成算法用于全无记忆策略子类，评估随机实例。 | 多智能体稳态合成计算 hard，无记忆策略不足以近似频率向量。 | 自主智能体群体策略合成 |
| 34 | http://arxiv.org/abs/2505.13543v2 | Origin-Destination Pattern Effects on Large-Scale Mixed Traffic Control via Multi-Agent Reinforcement Learning | 去中心化 MARL 框架管理大规模混合交通网络，评估 OD 模式影响。 | 大规模混合交通控制 underexplored，需评估时变 OD 模式可行性。 | 城市交通控制与效率 |
| 35 | http://arxiv.org/abs/2505.12628v1 | Dual-Agent Reinforcement Learning for Automated Feature Generation | 双智能体 RL 方法，一生成特征一决定保留，自注意力增强状态表示。 | 特征生成产生冗余，现有方法忽略初期差后期好特征，状态表示不足。 | 表格数据特征工程与模型鲁棒性 |
| 36 | http://arxiv.org/abs/2505.15306v1 | Multiple Weaks Win Single Strong: Large Language Models Ensemble Weak Reinforcement Learning Agents into a Supreme One | 提出 LLM-Ens，利用 LLM 语义理解动态选择最佳 RL Agent | 解决现有集成方法缺乏任务语义理解与适应性问题 | 强化学习模型集成 |
| 37 | http://arxiv.org/abs/2505.15571v1 | Temporal Spectrum Cartography in Low-Altitude Economy Networks: A Generative AI Framework with Multi-Agent Learning | 提出两阶段 GenAI 框架，利用多 Agent 扩散策略优化 UAV 轨迹 | 解决低空经济网络中频谱制图时空复杂性处理限制问题 | 低空经济网络频谱管理 |
| 38 | http://arxiv.org/abs/2505.17323v2 | Partner Modelling Emerges in Recurrent Agents (But Only When It Matters) | 发现无模型 RNN 代理在特定压力下自发产生伙伴建模 | 解决协作智能体如何适应新伙伴的机制问题 | 开放-ended 协作交互环境 |
| 39 | http://arxiv.org/abs/2505.17342v1 | A Survey of Safe Reinforcement Learning and Constrained MDPs: A Technical Survey on Single-Agent and Multi-Agent Safety | 安全强化学习技术综述，涵盖 CMDP 理论与多代理安全算法 | 解决安全 RL 领域缺乏统一技术指南的问题 | 单代理与多代理安全研究 |
| 40 | http://arxiv.org/abs/2505.17610v2 | Learning Equilibria from Data: Provably Efficient Multi-Agent Imitation Learning | 提出 MAIL-BRO 等算法，从专家数据学习纳什均衡 | 解决马尔可夫博弈中模仿学习样本复杂度问题 | 多代理博弈与策略学习 |
| 41 | http://arxiv.org/abs/2505.18433v2 | Finite-Time Global Optimality Convergence in Deep Neural Actor-Critic Methods for Decentralized Multi-Agent Reinforcement Learning | 首个去中心化 MARL 深度神经 Actor-Critic 全局最优收敛证明 | 解决深度 MARL 缺乏有限时间全局收敛理论保证问题 | 去中心化多代理决策 |
| 42 | http://arxiv.org/abs/2505.18595v1 | MisoDICE: Multi-Agent Imitation from Unlabeled Mixed-Quality Demonstrations | 结合大模型与偏好强化学习进行轨迹标记，提出多智能体模仿学习算法。 | 无标签混合质量演示数据下的多智能体协作模仿学习问题。 | 多智能体强化学习 |
| 43 | http://arxiv.org/abs/2505.18750v1 | Agent-Based Decentralized Energy Management of EV Charging Station with Solar Photovoltaics via Multi-Agent Reinforcement Learning | 将每个充电器视为智能体，结合 LSTM 提取时序特征，设计密集奖励机制。 | 电动汽车充电管理中应对系统不确定性和故障的鲁棒性问题。 | 智能电网充电管理 |
| 44 | http://arxiv.org/abs/2505.19630v3 | DoctorAgent-RL: A Multi-Agent Collaborative Reinforcement Learning System for Multi-Turn Clinical Dialogue | 基于 RL 的多代理协作框架，医生代理通过多轮交互优化提问策略。 | 单轮咨询信息模糊，传统多轮模型缺乏灵活提取关键临床信息能力。 | 临床对话系统 |
| 45 | http://arxiv.org/abs/2505.19637v1 | Adaptive Episode Length Adjustment for Multi-agent Reinforcement Learning | 提出自适应 episode 长度调整，基于熵评估学习进度逐渐增加长度。 | 固定 episode 长度限制状态探索或导致死胡同状态时间浪费。 | 多智能体强化学习 |
| 46 | http://arxiv.org/abs/2505.19837v1 | Multi-Agent Reinforcement Learning in Cybersecurity: From Fundamentals to Applications | 调查MARL在自动网络防御中的应用，聚焦入侵检测与横向移动遏制 | 应对动态、协调、复杂的网络威胁 | 网络安全自动化防御系统 |
| 47 | http://arxiv.org/abs/2505.20579v5 | The challenge of hidden gifts in multi-agent reinforcement learning | 揭示"隐藏礼物"信用分配难题，提出学习感知修正项降低方差 | 智能体无法感知他人有益行动导致集体奖励获取失败 | 多智能体协作任务学习 |
| 48 | http://arxiv.org/abs/2505.20922v2 | Revisiting Multi-Agent World Modeling from a Diffusion-Inspired Perspective | 扩散模型启发序列智能体建模，逐步解析不确定性捕捉结构化依赖 | MARL中联合动作空间指数增长与动态高度不确定建模困难 | 多智能体控制与策略学习 |
| 49 | http://arxiv.org/abs/2505.22597v1 | HDDLGym: A Tool for Studying Multi-Agent Hierarchical Problems Defined in HDDL with OpenAI Gym | HDDL与Gym无缝集成工具支持多Agent层次规划 | RL与层次化规划缺乏集成工具 | 多Agent层次化问题研究 |
| 50 | http://arxiv.org/abs/2505.22909v1 | Learning to Charge More: A Theoretical Study of Collusion by Q-Learning Agents | 首次理论解释Q-learning Agent合谋定价行为 | Q-learning Agent学习超竞争价格的机制不明 | 重复博弈中的定价Agent |
| 51 | http://arxiv.org/abs/2505.23720v1 | COBRA: Contextual Bandit Algorithm for Ensuring Truthful Strategic Agents | 无需货币激励抑制Agent策略性行为 | 上下文bandit中Agent虚假报告问题 | 多Agent平台推荐系统 |
| 52 | http://arxiv.org/abs/2505.21985v1 | Reward-Independent Messaging for Decentralized Multi-Agent Reinforcement Learning | 提出 MARL-CPC，基于集体预测编码实现无参数共享通信 | 解决非合作环境中有效通信与协调问题 | 去中心化多代理强化学习 |
| 53 | http://arxiv.org/abs/2505.22151v2 | Oryx: a Scalable Sequence Model for Many-Agent Coordination in Offline MARL | 适配 Sable 架构结合隐式约束 Q 学习，解决多步协调 | 解决离线 MARL 中多代理多步协调与长轨迹 temporal coherence 问题 | 离线多代理强化学习 |
| 54 | http://arxiv.org/abs/2505.22531v2 | Training RL Agents for Multi-Objective Network Defense Tasks | 提出开放 Ended Learning 方法训练自主网络防御代理 | 解决将 OEL 应用于真实网络安全应用的任务表示挑战 | 网络安全防御 |
| 55 | http://arxiv.org/abs/2505.24113v1 | Distributed Neural Policy Gradient Algorithm for Global Convergence of Networked Multi-Agent Reinforcement Learning | 提出分布式神经策略梯度算法，含分布式评论家与去中心化演员步骤 | 解决线性函数近似表达能力差及网络多智能体强化学习收敛性问题 | 网络多智能体强化学习系统 |
| 56 | http://arxiv.org/abs/2505.24265v3 | R3DM: Enabling Role Discovery and Diversity Through Dynamics Models in Multi-agent Reinforcement Learning | 提出 R3DM 框架，通过动力学模型最大化角色与未来行为的互信息 | 解决现有方法忽视角色对未来轨迹影响及多样性不足的问题 | 复杂任务下的多智能体协调 |
| 57 | http://arxiv.org/abs/2506.00228v1 | Sorrel: A simple and flexible framework for multi-agent reinforcement learning | 提供简单 Python 接口，强调心理直观结构的代理环境循环 | 解决社会科学家研究学习与社交互动导致群体动态变化的工具缺乏问题 | 多智能体强化学习环境生成与测试 |

[返回目录](#目录)

<a id="cat-11"></a>

## Agent架构与框架设计

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2505.02861v2 | Intelligent Product 3.0: Decentralised AI Agents and Web3 Intelligence Standards | 去中心化身份+区块链产品信息+AI-to-AI协作的智能产品3.0规范 | 物理产品与网络信息环境连接需韧性、共识与自主性 | 智能产品、Web3、物联网 |
| 2 | http://arxiv.org/abs/2505.01834v1 | Model Context Protocol-based Internet of Experts For Wireless Environment-aware LLM Agents | MCP-based IoX框架，LLM选择性查询轻量专家模型输出 | LLM缺乏无线环境信息访问，重训练损害语言泛化 | 无线环境感知、网络管理 |
| 3 | http://arxiv.org/abs/2505.02024v3 | From Mind to Machine: The Rise of Manus AI as a Fully Autonomous Digital Agent | Manus AI结合LLM推理规划与端到端复杂任务执行能力 | 通用AI Agent需将高层意图转化为现实世界行动 | 多行业通用任务（医疗、金融、制造等） |
| 4 | http://arxiv.org/abs/2505.02279v2 | A survey of agent interoperability protocols: Model Context Protocol (MCP), Agent Communication Protocol (ACP), Agent-to-Agent Protocol (A2A), and Agent Network Protocol (ANP) | 系统比较四种Agent互操作协议，提出分阶段采用路线图 | 临时集成难以扩展、安全与泛化，需标准化协议 | 异构Agent系统集成 |
| 5 | http://arxiv.org/abs/2505.07838v1 | Moving From Monolithic To Microservices Architecture for Multi-Agent Systems | 探讨MAS从单体到微服务架构演进，比较通信协议与设计挑战 | 传统单体MAS可扩展性与可维护性有限 | 复杂多Agent系统架构 |
| 6 | http://arxiv.org/abs/2505.02489v1 | Beyond the model: Key differentiators in large language models and multi-agent services | 分析LLM服务关键差异化因素：数据质量、计算效率、评估框架 | 基础模型能力趋同，生态系统优化成为竞争焦点 | 多Agent服务商业化 |
| 7 | http://arxiv.org/abs/2505.05428v3 | Empowering Scientific Workflows with Federated Agents | 提出Academy中间件，支持联邦研究生态中Agent的分布式部署与管理 | 科学计算中异构资源上Agent的协调与执行问题 | 科学工作流与HPC系统 |
| 8 | http://arxiv.org/abs/2505.05440v3 | EcoAgent: An Efficient Device-Cloud Collaborative Multi-Agent Framework for Mobile Automation | 提出端云协同多Agent框架EcoAgent，支持隐私保护的设备端验证 | 移动多Agent系统高延迟、高成本及隐私泄露问题 | 移动自动化任务 |
| 9 | http://arxiv.org/abs/2505.06438v2 | Reliable Collaborative Conversational Agent System Based on LLMs and Answer Set Programming | 提出Manager-Customer-Service双Agent范式，通过ASP确保知识一致性 | 纯LLM对话Agent知识不可靠、协作信息传递不安全问题 | 任务导向对话系统 |
| 10 | http://arxiv.org/abs/2505.06761v2 | Learning Graph Representation of Agent Diffusers | 提出LGR-AD多Agent系统，将扩散生成过程建模为交互Agent分布式系统 | 扩散模型静态参数无法适应生成过程不同阶段的问题 | 动态计算机视觉任务 |
| 11 | http://arxiv.org/abs/2505.06817v1 | Control Plane as a Tool: A Scalable Design Pattern for Agentic AI Systems | 提出"控制平面即工具"设计模式，封装模块化路由逻辑 | 大规模Agent系统工具编排管理的架构不成熟问题 | 可扩展Agent AI系统 |
| 12 | http://arxiv.org/abs/2505.07087v2 | Applying Cognitive Design Patterns to General LLM Agents | 识别并应用前Transformer架构中的认知设计模式到LLM Agent系统 | 预测当前LLM Agent系统的差距与缺陷，指导通用智能研究 | 通用智能Agent系统 |
| 13 | http://arxiv.org/abs/2505.07176v2 | Internet of Agents: Fundamentals, Applications, and Challenges | 提出Internet of Agents框架，支持异构Agent的无缝互联与协作编排 | 大规模Agent proliferatio需要统一的以Agent为中心的基础设施 | 虚拟与物理环境中的Agent生态 |
| 14 | http://arxiv.org/abs/2505.08120v1 | Putting It All into Context: Simplifying Agents with LCLMs | 发现长上下文语言模型仅需适当提示即可在SWE-bench上媲美复杂Agent架构 | 当前LM Agent架构过度复杂、部分脚手架可能不必要的问题 | 软件工程自动化任务 |
| 15 | http://arxiv.org/abs/2505.02836v1 | Scenethesis: A Language and Vision Agentic Framework for 3D Scene Generation | 结合 LLM 规划与视觉引导布局 refinement 的免训练框架 | 解决 LLM 生成 3D 场景空间不真实、物体放置不合理问题 | 3D 场景生成与虚拟现实 |
| 16 | http://arxiv.org/abs/2505.03864v1 | From Glue-Code to Protocols: A Critical Analysis of A2A and MCP Integration for Scalable Agent Systems | 分析 A2A 与 MCP 协议集成的互操作性与安全挑战 | 解决智能体系统碎片化集成与规模化互操作难题 | 可扩展智能体系统架构 |
| 17 | http://arxiv.org/abs/2505.04354v1 | Optimization Problem Solving Can Transition to Evolutionary Agentic Workflows | 主张用进化智能体工作流替代专家依赖的优化流程 | 解决优化问题求解依赖人工专家导致工业化瓶颈 | 工业优化问题求解 |
| 18 | http://arxiv.org/abs/2505.05515v1 | Nature's Insight: A Novel Framework and Comprehensive Analysis of Agentic Reasoning Through the Lens of Neuroscience | 基于神经科学提出感知 - 行动统一推理框架 | 解决现有智能体推理缺乏生物认知理论基础的问题 | 通用智能体推理架构 |
| 19 | http://arxiv.org/abs/2505.05286v3 | HEXGEN-FLOW: Optimizing LLM Inference Request Scheduling for Agentic Text-to-SQL | 分层调度器优化异构 GPU 集群上代理式 Text-to-SQL 工作流 | 解决多阶段依赖与严格延迟要求下的服务目标违约问题 | 企业级 Text-to-SQL 部署 |
| 20 | http://arxiv.org/abs/2505.08446v1 | Agent-as-a-Service based on Agent Network | 基于 RGPS 标准提出 AaaS-AN 范式，统一 Agent 生命周期 | 解决多 Agent 系统缺乏组织级协作与互操作性支持问题 | 多 Agent 系统构建与协作 |
| 21 | http://arxiv.org/abs/2505.09932v1 | Demystifying AI Agents: The Final Generation of Intelligence | 梳理 AI 代理技术里程碑，论证其为智能发展的终极阶段 | 解决社会对 AI 代理发展轨迹及影响缺乏系统性认知问题 | AI 技术发展综述 |
| 22 | http://arxiv.org/abs/2505.10468v5 | AI Agents vs. Agentic AI: A Conceptual Taxonomy, Applications and Challenges | 区分 AI Agents 与 Agentic AI，提供概念分类与挑战分析 | 解决两种范式设计哲学与能力界限混淆问题 | AI 代理系统分类研究 |
| 23 | http://arxiv.org/abs/2505.10609v1 | Agent Name Service (ANS): A Universal Directory for Secure AI Agent Discovery and Interoperability | 基于 DNS 架构提出 ANS，提供协议无关的代理注册与解析 | 解决 AI 代理缺乏安全发现机制与互操作性标准问题 | 多 Agent 系统互操作 |
| 24 | http://arxiv.org/abs/2505.13246v1 | Agentic Publications: An LLM-Driven Framework for Interactive Scientific Publishing, Supplementing Traditional Papers with AI-Powered Knowledge Systems | 将论文转化为交互式知识系统的 LLM 驱动框架 | 解决研究人员 navigating 复杂知识景观的挑战 | 科学出版与知识系统 |
| 25 | http://arxiv.org/abs/2505.13668v3 | MAFA: A multi-agent framework for annotation | 结合多专用智能体与法官智能体的 FAQ 标注框架 | 解决单一模型无法捕捉多样用户查询细微差别的问题 | 消费者银行应用 |
| 26 | http://arxiv.org/abs/2505.13761v2 | Simulation Agent: A Framework for Integrating Simulation and Large Language Models for Enhanced Decision-Making | 集成仿真模型与 LLM 优势的智能体框架 | 解决仿真复杂性高与 LLM 缺乏结构化因果理解的问题 | 决策支持系统 |
| 27 | http://arxiv.org/abs/2505.13851v1 | A Challenge to Build Neuro-Symbolic Video Agents | 提出构建神经符号视频智能体的大挑战 | 解决视频分析中时序推理与事件依赖理解的局限 | 视频理解系统 |
| 28 | http://arxiv.org/abs/2505.13965v1 | CAFES: A Collaborative Multi-Agent Framework for Multi-Granular Multimodal Essay Scoring | 首个专为自动作文评分设计的协作多智能体框架 | 解决传统 AES 方法泛化性差与多模态感知不足的问题 | 多模态作文评分 |
| 29 | http://arxiv.org/abs/2505.14738v2 | R&D-Agent: An LLM-Agent Framework Towards Autonomous Data Science | 定义 MLE 工作流为两阶段六组件的解耦可扩展框架 | 解决数据科学任务复杂性高与专家需求阻碍进步的问题 | 数据科学应用 |
| 30 | http://arxiv.org/abs/2505.14299v1 | Empowering LLMs in Task-Oriented Dialogues: A Domain-Independent Multi-Agent Framework and Fine-Tuning Strategy | 设计包含意图、槽位与响应智能体的领域独立多智能体框架 | 解决微调轻量 LLM 处理多复杂逻辑性能下降的问题 | 任务导向对话系统 |
| 31 | http://arxiv.org/abs/2505.14996v4 | MAS-ZERO: Designing Multi-Agent Systems with Zero Supervision | 引入首个自演化推理时框架用于自动多智能体系统设计 | 解决当前 MAS 依赖手动设计角色与通信协议缺乏适应性 | 多智能体系统设计 |
| 32 | http://arxiv.org/abs/2505.13516v1 | HALO: Hierarchical Autonomous Logic-Oriented Orchestration for Multi-Agent LLM Systems | 分层推理架构，含规划、角色设计与推理智能体，结合 MCTS 搜索工作流。 | 现有系统依赖预定义角色与静态通信，缺乏适应性与灵活性。 | 代码生成、通用与算术推理 |
| 33 | http://arxiv.org/abs/2505.12006v4 | SOCIA-$\abla$: Textual Gradient Meets Multi-Agent Orchestration for Automated Simulator Generation | 端到端智能体框架，将模拟器构建视为代码实例优化，执行文本梯度下降。 | 模拟器构建 brittle，需专家 effort，缺乏可复现与约束感知生成。 | 网络物理系统任务模拟 |
| 34 | http://arxiv.org/abs/2505.12065v1 | Demystifying and Enhancing the Efficiency of Large Language Model Based Search Agents | 提出 SearchAgent-X，利用高召回近似检索与优先级调度降低延迟。 | 交错范式引入效率瓶颈，检索开销与调度不当导致级联延迟。 | 基于 LLM 的搜索智能体 |
| 35 | http://arxiv.org/abs/2505.12501v1 | ALAS: A Stateful Multi-LLM Agent Framework for Disruption-Aware Planning | 状态化多 LLM 智能体框架，分解计划为角色专用智能体，自动状态跟踪。 | LLM 缺乏 self-verification、context erosion 等 deficits，难以 transaction-style planning。 | 大规模 job-shop 调度与动态恢复 |
| 36 | http://arxiv.org/abs/2505.12543v2 | Disambiguation in Conversational Question Answering in the Era of LLMs and Agents: A Survey | 综述 LLM 与智能体时代 CQA 中的歧义定义、形式与消解方法。 | 歧义是 NLP 根本挑战，LLM 扩展能力使其更 critical，需 comprehensive review。 | 对话问答系统研究与开发 |
| 37 | http://arxiv.org/abs/2505.12594v1 | AD-AGENT: A Multi-agent Framework for End-to-end Anomaly Detection | LLM 驱动多智能体框架，将自然语言指令转化为可执行 AD  pipelines。 | 数据模态多样与专用库增多，非专家用户缺乏知识与技能。 | 异常检测任务自动化 |
| 38 | http://arxiv.org/abs/2505.15858v2 | Large Language Model-Powered Agent for C to Rust Code Translation | 提出 VFT 中间步骤与 LAC2R 框架，利用 MCTS 组织翻译轨迹 | 解决 C 到 Rust 翻译中缺乏平行数据与中间步骤定义不清问题 | 代码迁移与系统级软件开发 |
| 39 | http://arxiv.org/abs/2505.15261v1 | AGENT-X: Adaptive Guideline-based Expert Network for Threshold-free AI-generated teXt detection | 提出零样本多 Agent 框架，基于修辞学指南进行无阈值检测 | 解决现有检测方法依赖标注数据与外部阈值调优问题 | AI 生成文本检测 |
| 40 | http://arxiv.org/abs/2505.16007v1 | Position: Agentic Systems Constitute a Key Component of Next-Generation Intelligent Image Processing | 主张图像处理社区应从模型中心转向包含 Agent 系统设计范式 | 解决当前深度学习方法在泛化与实时问题解决灵活性上限制 | 智能图像处理系统 |
| 41 | http://arxiv.org/abs/2505.16979v1 | Know the Ropes: A Heuristic Strategy for LLM-based Multi-Agent System Design | 将领域先验转化为算法蓝图层次，递归分解任务 | 解决单代理局限及多代理分解不当与验证开销问题 | 复杂任务的多智能体系统 |
| 42 | http://arxiv.org/abs/2505.16988v1 | MASLab: A Unified and Comprehensive Codebase for LLM-based Multi-Agent Systems | 统一综合代码库，集成 20+ 方法并提供标准化评估环境 | 解决多智能体系统研究代码分散与比较不公问题 | 多智能体系统研究人员 |
| 43 | http://arxiv.org/abs/2505.17673v1 | Rethinking Agent Design: From Top-Down Workflows to Bottom-Up Skill Evolution | 自底向上代理范式，通过试错与反思抽象技能 | 解决顶向下工作流依赖设计更新且无法经验学习问题 | 开放-ended 复杂环境 |
| 44 | http://arxiv.org/abs/2505.17767v2 | Position: The Real Barrier to LLM Agent Usability is Agentic ROI | 提出 Agentic ROI 概念，重构代理可用性评估视角 | 解决大众市场应用中代理实用性不足的问题 | 大规模代理应用部署 |
| 45 | http://arxiv.org/abs/2505.18228v2 | Implementing Agents in JavaScript | 介绍 JS 中面向代理编程及与 LLM 集成方法 | 解决 JS 生态中代理实现与多系统构建门槛问题 | JavaScript 技术生态系统 |
| 46 | http://arxiv.org/abs/2505.18286v1 | Single-agent or Multi-agent Systems? Why Not Both? | 提出混合代理范式，在 MAS 与 SAS 间请求级联 | 解决 MAS 复杂度高与 SAS 能力局限的权衡问题 | 多种代理应用场景 |
| 47 | http://arxiv.org/abs/2505.18351v1 | Persona Alchemy: Designing, Evaluating, and Implementing Psychologically-Grounded LLM Agents for Diverse Stakeholder Representation | 基于社会认知理论的代理设计框架，操作化个人因素 | 解决代理 persona 与人类认知过程对齐难问题 | 多样化利益相关者代表 |
| 48 | http://arxiv.org/abs/2505.18397v3 | An Outlook on the Opportunities and Challenges of Multi-Agent AI Systems | 形式化框架分析 MAS 有效性与安全性，展望信号处理应用 | 解决 MAS 可靠性评估与结构安全性问题 | 信号处理与自动化系统 |
| 49 | http://arxiv.org/abs/2505.18829v2 | LiteCUA: Computer as MCP Server for Computer-Use Agent on AIOS | 将计算机转化为上下文环境，实施 MCP 服务器架构抽象计算机状态与动作。 | 语言模型理解世界与计算机接口结构之间的语义 disconnect 问题。 | 计算机使用智能体 |
| 50 | http://arxiv.org/abs/2505.18845v1 | Multi-Party Conversational Agents: A Survey | 综述多方对话智能体进展，强调心智理论建模及多模态理解的重要性。 | 多方对话中需同时理解语义与社会动态的复杂挑战。 | 多方对话系统研究 |
| 51 | http://arxiv.org/abs/2505.18946v1 | SANNet: A Semantic-Aware Agentic AI Networking Framework for Multi-Agent Cross-Layer Coordination | 提出语义感知架构，推断用户目标并自动分配不同层代理，含动态权重冲突解决。 | 多代理协作中目标冲突及缺乏自动目标发现与任务分配机制。 | 自主网络管理系统 |
| 52 | http://arxiv.org/abs/2505.19101v3 | Agentic Visualization: Extracting Agent-based Design Patterns from Visualization Systems | 通过代理视角重释现有可视化系统，提取角色、通信与协调设计模式。 | 可视化领域缺乏保留人类代理权同时放大分析能力的代理框架。 | 可视化系统设计 |
| 53 | http://arxiv.org/abs/2505.21550v1 | Collaborative Agentic AI Needs Interoperability Across Ecosystems | 提出 Web of Agents 最小架构基础，含消息、交互、状态管理及发现组件。 | 当前解决方案孤立构建，导致碎片化且不兼容的生态系统风险。 | 协作智能体互操作性 |
| 54 | http://arxiv.org/abs/2505.19275v3 | Agentic Information Theory: Ergodicity and Intrinsic Semantics of Information Processes | 发展记忆型智能体信息理论，探索信息过程的遍历性与语义。 | 缺乏对智能体在复杂环境中 temporal behavior 的信息理论描述。 | 智能体理论基础 |
| 55 | http://arxiv.org/abs/2505.19443v1 | Vibe Coding vs. Agentic Coding: Fundamentals and Practical Implications of Agentic AI | 分析 vibe coding 与 agentic coding 范式差异，提出混合架构未来路线图。 | 缺乏对 AI 辅助软件开发中不同自主性范式的系统性分析与指导。 | 软件开发生态 |
| 56 | http://arxiv.org/abs/2506.05364v1 | Survey of LLM Agent Communication with MCP: A Software Design Pattern Centric Review | 调查经典软件设计模式如何增强 MCP 通信可靠性与可扩展性。 | 多智能体协作过渡中出现的关键通信障碍及架构结构化需求。 | 智能体通信架构 |
| 57 | http://arxiv.org/abs/2505.19764v2 | Multi-View Encoders for Performance Prediction in LLM-Based Agentic Workflows | 配备多视图工作流编码技术，利用跨领域无监督预训练近似任务成功率。 | 优化代理系统因搜索空间巨大导致启发式调优昂贵且次优。 | 工作流性能预测 |
| 58 | http://arxiv.org/abs/2505.20286v1 | Alita: Generalist Agent Enabling Scalable Agentic Reasoning with Minimal Predefinition and Maximal Self-Evolution | 最小预定义单组件+自进化MCP生成，实现可扩展通用推理 | 现有框架依赖手工工具/工作流限制适应性与泛化 | 开放域复杂任务自动化 |
| 59 | http://arxiv.org/abs/2505.20660v1 | BacktrackAgent: Enhancing GUI Agent with Error Detection and Backtracking Mechanism | 验证器/判断器/反思器模块+回溯机制+判断奖励，提升错误恢复能力 | 现有GUI智能体缺乏有效错误检测与恢复机制 | GUI自动化任务执行 |
| 60 | http://arxiv.org/abs/2505.22571v3 | Agent-UniRAG: A Trainable Open-Source LLM Agent Framework for Unified Retrieval-Augmented Generation Systems | 可训练Agent框架统一处理单跳/多跳RAG查询 | RAG系统单跳/多跳查询分离处理的局限性 | 开源LLM的RAG系统 |
| 61 | http://arxiv.org/abs/2505.22814v2 | A Large Language Model-Enabled Control Architecture for Dynamic Resource Capability Exploration in Multi-Agent Manufacturing Systems | LLM赋能多Agent制造系统控制架构 | 制造系统实时适应和上下文感知决策能力不足 | 动态制造环境多Agent系统 |
| 62 | http://arxiv.org/abs/2505.22967v1 | MermaidFlow: Redefining Agentic Workflow Generation via Safety-Constrained Evolutionary Programming | 安全约束图进化生成可执行工作流 | LLM驱动工作流生成脆弱不可执行 | Agent推理工作流生成 |
| 63 | http://arxiv.org/abs/2505.23006v1 | A Practical Approach for Building Production-Grade Conversational Agents with Workflow Graphs | 工作流图构建生产级对话Agent | 学术研究与工业应用存在差距 | 电商领域对话Agent |
| 64 | http://arxiv.org/abs/2505.23596v3 | Agent-SAMA: State-Aware Mobile Assistant | 状态感知多Agent框架建模APP执行为FSM | 现有GUI Agent缺乏执行上下文理解 | 移动GUI任务自动化 |
| 65 | http://arxiv.org/abs/2505.23885v2 | OWL: Optimized Workforce Learning for General Multi-Agent Assistance in Real-World Task Automation | 分层多Agent框架解耦规划与执行支持跨域迁移 | 多Agent系统跨域迁移需完全重新设计 | 现实世界任务自动化 |
| 66 | http://arxiv.org/abs/2505.21286v1 | PACT: A Contract-Theoretic Framework for Pricing Agentic AI Services Powered by Large Language Models | 提出基于契约理论的定价框架 PACT，建模多维服务质量 | 解决代理 AI 服务部署中的定价、成本与责任挑战 | 云端代理 AI 服务 |
| 67 | http://arxiv.org/abs/2505.22311v1 | From Large AI Models to Agentic AI: A Tutorial on Future Intelligent Communications | 系统介绍 LAM 与 Agentic AI 原理，提出通信设计范式 | 解决 6G 通信系统感知响应受限与适应性低问题 | 未来智能通信系统 |
| 68 | http://arxiv.org/abs/2505.22368v1 | AgentDNS: A Root Domain Naming System for LLM Agents | 提出根域名命名与服务发现系统，实现跨厂商服务发现 | 解决跨厂商代理与服务发现、互操作性缺乏标准问题 | LLM 代理服务生态 |
| 69 | http://arxiv.org/abs/2505.24354v1 | Unifying Language Agent Algorithms with Graph-based Orchestration Engine for Reproducible Agent Research | 提出 AGORA 框架，含图工作流引擎及标准化评估协议 | 解决代理开发工程开销大、组件非标准化及评估框架不足的问题 | 可复现的语言智能体研究 |
| 70 | http://arxiv.org/abs/2506.00417v1 | World Models for Cognitive Agents: Transforming Edge Intelligence in Future Networks | 综述世界模型架构及应用，提出 Wireless Dreamer 框架 | 解决数据受限或安全关键场景下样本效率及决策质量的问题 | 无线边缘智能优化与 UAV 轨迹规划 |

[返回目录](#目录)

<a id="cat-12"></a>

## Agent安全与对齐

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2505.02077v1 | Open Challenges in Multi-Agent Security: Towards Secure Systems of Interacting AI Agents | 提出多Agent安全新领域，分类威胁景观与安全-性能权衡 | 去中心化Agent交互产生新威胁（秘密共谋、群体攻击等） | 互联网规模Agent部署、关键基础设施 |
| 2 | http://arxiv.org/abs/2505.05594v2 | Anticipating Gaming to Incentivize Improvement: Guiding Agents in (Fair) Strategic Classification | 构建Stackelberg博弈模型，分析公平分类策略如何激励用户真实改进 | 算法决策系统中用户的策略性操纵行为问题 | 公平机器学习决策系统 |
| 3 | http://arxiv.org/abs/2505.05849v4 | AgentVigil: Generic Black-Box Red-teaming for Indirect Prompt Injection against LLM Agents | 提出AgentVigil黑盒模糊测试框架，自动发现间接提示注入漏洞 | LLM Agent面临的间接提示注入安全攻击问题 | LLM Agent系统安全测试 |
| 4 | http://arxiv.org/abs/2505.06913v1 | RedTeamLLM: an Agentic AI framework for offensive security | 提出RedTeamLLM框架，实现渗透测试任务的自动化，解决计划修正等四大挑战 | 自动化安全测试与零日攻击发现的能力不足问题 | 网络安全工程 |
| 5 | http://arxiv.org/abs/2505.08807v1 | Security of Internet of Agents: Attacks and Countermeasures | 全面审查IoA系统的安全隐私格局，分析身份认证、跨Agent信任等四大方面 | IoA系统相比传统网络的独特漏洞与防御机制 | Internet of Agents生态系统 |
| 6 | http://arxiv.org/abs/2505.03096v1 | Assessing and Enhancing the Robustness of LLM-based Multi-Agent Systems Through Chaos Engineering | 提出混沌工程框架主动识别 LLM 多智能体系统脆弱性 | 解决生产环境中智能体幻觉、通信失败等 emergent 错误 | LLM 多智能体系统鲁棒性 |
| 7 | http://arxiv.org/abs/2505.03574v1 | LlamaFirewall: An open source guardrail system for building secure AI agents | 提供提示注入、代码安全等三层防护的开源护栏系统 | 解决自主智能体执行高风险动作时的安全风险 | 通用 AI 智能体安全 |
| 8 | http://arxiv.org/abs/2505.04195v2 | AutoPatch: Multi-Agent Framework for Patching Real-World CVE Vulnerabilities | 多智能体框架结合 RAG 自动修复 LLM 生成代码的 CVE 漏洞 | 解决 LLM 知识截止后生成代码存在新漏洞的问题 | 软件安全与漏洞修复 |
| 9 | http://arxiv.org/abs/2505.04345v2 | Build Agent Advocates, Not Platform Agents | 主张推广用户控制的 Agent Advocates 以抵抗平台垄断 | 解决平台控制智能体导致的监控与锁定风险 | 智能体政策与社会治理 |
| 10 | http://arxiv.org/abs/2505.04799v3 | Maris: A Formally Verifiable Privacy Policy Enforcement Paradigm for Multi-Agent Collaboration Systems | 嵌入参考监控器实现多智能体协作系统的隐私策略执行 | 解决多智能体协作中敏感数据泄露与隐私风险 | 多智能体系统隐私保护 |
| 11 | http://arxiv.org/abs/2505.09757v2 | Trustless Autonomy: Understanding Motivations, Benefits, and Governance Dilemmas in Self-Sovereign Decentralized AI Agents | 研究去中心化 AI 代理的动机、收益与治理困境 | 解决自主权去中心化 Agent 信任缺失与不可靠自主性矛盾 | 去中心化 AI 代理治理 |
| 12 | http://arxiv.org/abs/2505.10670v1 | Interpretable Risk Mitigation in LLM Agent Systems | 利用稀疏自编码器特征 steering 残差流，降低背叛概率 | 解决 LLM 代理在博弈环境中行为不可预测及安全风险问题 | LLM 代理行为安全 |
| 13 | http://arxiv.org/abs/2505.10924v3 | A Survey on the Safety and Security Threats of Computer-Using Agents: JARVIS or Ultron? | 系统化知识整理 CUA 安全威胁，提出防御策略分类法 | 解决计算机使用 Agent 新兴安全与风险缺乏系统认知问题 | 计算机使用 Agent 安全 |
| 14 | http://arxiv.org/abs/2505.11063v2 | Think Twice Before You Act: Enhancing Agent Behavioral Safety with Thought Correction | 提出 Thought-Aligner 模块，动态纠正高风险思维再执行 | 解决长程行为轨迹中思维偏差导致不可逆安全事故问题 | LLM 代理行为安全 |
| 15 | http://arxiv.org/abs/2505.12786v2 | Forewarned is Forearmed: A Survey on Large Language Model-based Agents in Autonomous Cyberattacks | 综述 LLM 智能体在网络攻击中的能力与威胁 | 缺乏对 LLM 自主网络攻击威胁的系统性防御洞察 | 网络安全系统与防御策略 |
| 16 | http://arxiv.org/abs/2505.12842v4 | GEM: Gaussian Embedding Modeling for Out-of-Distribution Detection in GUI Agents | 基于高斯混合模型拟合输入嵌入距离检测分布外指令 | 解决 GUI 智能体面对分布外指令时的任务崩溃与安全威胁 | 图形用户界面智能体 |
| 17 | http://arxiv.org/abs/2505.12981v2 | From Assistants to Adversaries: Exploring the Security Risks of Mobile LLM Agents | 首次全面分析移动 LLM 智能体的 11 种攻击面 | 移动 LLM 智能体面临的行为偏差、隐私泄露与执行劫持风险 | 移动端 LLM 智能体 |
| 18 | http://arxiv.org/abs/2505.13076v1 | The Hidden Dangers of Browsing AI Agents | 提出浏览智能体的端到端威胁模型与纵深防御策略 | 解决浏览智能体因动态内容与工具执行暴露的安全漏洞 | 自主浏览智能体 |
| 19 | http://arxiv.org/abs/2505.14215v2 | Information Retrieval Induced Safety Degradation in AI Agents | 调查扩展检索访问如何影响模型可靠性与有害内容生成 | 解决检索 enabled 智能体因外部数据导致安全性降解问题 | 检索 enabled AI 智能体 |
| 20 | http://arxiv.org/abs/2505.14289v1 | EVA: Red-Teaming GUI Agents via Evolving Indirect Prompt Injection | 提出通过监控注意力分布更新对抗线索的红队框架 EVA | 解决 GUI 智能体面临嵌入视觉环境的间接提示注入威胁 | 图形用户界面智能体 |
| 21 | http://arxiv.org/abs/2505.14418v2 | Hidden Ghost Hand: Unveiling Backdoor Vulnerabilities in MLLM-Powered Mobile GUI Agents | 揭示 MLLM 驱动 GUI 智能体交互级触发器并提出 AgentGhost | 解决开源 GUI 智能体或 API 带来的供应链后门攻击威胁 | 移动图形用户界面 |
| 22 | http://arxiv.org/abs/2505.11579v2 | Toward Adaptive Categories: Dimensional Governance for Agentic AI | 提出维度治理框架，动态追踪决策权、自主性与问责制分布。 | 传统分类治理框架无法适应动态演化的基础模型与多智能体系统。 | 人工智能治理与政策制定 |
| 23 | http://arxiv.org/abs/2505.11584v1 | LLM Agents Are Hypersensitive to Nudges | 揭示 LLM 智能体对默认选项等 nudges 的超敏感性，与人类选择分布不同。 | LLM 智能体在复杂环境中决策易受提示架构影响，存在行为风险。 | 代表用户决策的智能体部署 |
| 24 | http://arxiv.org/abs/2505.11642v2 | PeerGuard: Defending Multi-Agent Systems Against Backdoor Attacks Through Mutual Reasoning | 利用智能体间相互推理检测不合逻辑响应，防御后门攻击。 | 多智能体系统安全性研究不足，易受后门攻击影响。 | 基于 LLM 的多智能体系统安全 |
| 25 | http://arxiv.org/abs/2505.11717v4 | WebInject: Prompt Injection Attack to Web Agents | 提出 WebInject 攻击，通过扰动网页像素诱导多模态智能体执行指定动作。 | 多模态智能体易受提示注入攻击，网页环境可被操纵。 | 基于 MLLM 的网页智能体安全 |
| 26 | http://arxiv.org/abs/2505.11866v1 | Position Paper: Bounded Alignment: What (Not) To Expect From AGI Agents | 主张 AGI 安全期望应基于人类智能理解，而非当前主导愿景。 | AI 风险与安全问题关键，需更现实的视角指导政策决策。 | AGI 安全研究与政策制定 |
| 27 | http://arxiv.org/abs/2505.12001v1 | Interactional Fairness in LLM Multi-Agent Systems: An Evaluation Framework | 引入交互公平性框架，评估人际与信息公平性对 agent 行为影响。 | 多智能体系统公平性问题应扩展至沟通方式，缺乏评估框架。 | LLM 多智能体系统资源协商 |
| 28 | http://arxiv.org/abs/2505.12402v1 | Automated Profile Inference with Language Model Agents | 提出 AutoProfiler 框架，协作收集处理用户活动提取敏感属性。 | LLM 智能体自动化能力可被恶意用于破坏在线匿名性，泄露隐私。 | 在线 pseudonymity 隐私威胁评估 |
| 29 | http://arxiv.org/abs/2506.06299v4 | How malicious AI swarms can threaten democracy: The fusion of agentic AI and LLMs marks a new frontier in information warfare | 揭示恶意 AI 群体融合 LLM 推理与多智能体架构，协调 infiltrate 社区。 | 生成工具与多智能体系统可大规模操纵信念行为，威胁民主。 | 信息战与民主安全干预 |
| 30 | http://arxiv.org/abs/2505.12442v3 | IP Leakage Attacks Targeting LLM-Based Multi-Agent Systems | 提出 MASLEAK 攻击框架，黑盒环境下提取 MAS 专有组件信息。 | MAS 架构与交互复杂，引发知识产权保护 concerns，缺乏防御。 | 基于 LLM 的多智能体系统 IP 保护 |
| 31 | http://arxiv.org/abs/2505.12490v3 | Improving Google A2A Protocol: Protecting Sensitive Data and Mitigating Unintended Harms in Multi-Agent Systems | 提出协议级增强，引入显式同意编排与临时 scoped tokens。 | A2A 协议处理敏感信息有关键 limitations，增加 unintended harms 风险。 | 生成式多智能体环境隐私保护 |
| 32 | http://arxiv.org/abs/2505.15108v2 | A Risk Ontology for Evaluating AI-Powered Psychotherapy Virtual Agents | 开发专门风险本体，系统化评估对话 AI 心理治疗师的用户伤害 | 解决缺乏标准化方法捕捉治疗交互中细微风险的问题 | AI 驱动心理健康支持 |
| 33 | http://arxiv.org/abs/2505.15216v3 | BountyBench: Dollar Impact of AI Agent Attackers and Defenders on Real-World Cybersecurity Systems | 建立首个框架捕捉真实系统中攻防网络能力，含 40 个漏洞赏金 | 解决缺乏评估 AI Agent 在 evolving 系统中攻防能力框架问题 | 现实世界网络安全系统 |
| 34 | http://arxiv.org/abs/2505.15922v2 | Aligning Dialogue Agents with Global Feedback via Large Language Model Multimodal Reward Decomposition | 利用 LLM 分解全局反馈为细粒度局部隐式奖励，对齐对话 Agent | 解决仅靠单会话级反馈信号难以对齐对话 Agent 问题 | 对话系统对齐与优化 |
| 35 | http://arxiv.org/abs/2505.16557v2 | Is Your LLM-Based Multi-Agent a Reliable Real-World Planner? Exploring Fraud Detection in Travel Planning | 引入 WandaPlan 评估环境，注入欺骗内容评估规划系统风险 | 解决规划系统依赖易受欺诈信息平台导致财务损失风险问题 | 现实世界旅行规划系统 |
| 36 | http://arxiv.org/abs/2505.17735v2 | SafeAgent: Safeguarding LLM Agents via an Automated Risk Simulator | 自动化风险模拟器生成合成数据，增强代理安全性 | 解决动态交互中代理安全风险难以评估与防御问题 | 现实世界代理部署安全 |
| 37 | http://arxiv.org/abs/2505.17861v1 | Superplatforms Have to Attack AI Agents | 分析超级平台与 AI 代理间的流量入口冲突与攻击趋势 | 解决数字生态 openness 与平台垄断间的张力问题 | 数字平台与 AI 代理生态 |
| 38 | http://arxiv.org/abs/2505.18384v5 | Dynamic Risk Assessments for Offensive Cybersecurity Agents | 强调动态风险评估，考虑 adversary 自由度与迭代改进 | 解决当前审计未充分考虑 adversary 迭代改进风险问题 | 进攻性网络安全代理 |
| 39 | http://arxiv.org/abs/2505.18572v1 | MASTER: Multi-Agent Security Through Exploration of Roles and Topological Structures -- A Comprehensive Framework | 构建基于角色和拓扑结构的多智能体安全研究框架，提供自动化攻击与防御策略。 | 多智能体系统因协作交互放大的安全风险问题。 | 多智能体系统安全研究 |
| 40 | http://arxiv.org/abs/2505.18882v5 | Personalized Safety in LLMs: A Benchmark and A Planning-Based Agent Approach | 提出个性化安全基准，开发无需训练的两阶段代理框架策略性获取用户背景。 | 通用安全评估忽略用户背景差异导致的高风险应用场景隐患。 | 高风险应用 LLM 安全 |
| 41 | http://arxiv.org/abs/2505.19139v1 | The Eye of Sherlock Holmes: Uncovering User Private Attribute Profiling via Vision-Language Model Agentic Framework | 构建 PAPI 数据集，提出混合代理框架结合 VLM 与 LLM 增强隐私推断。 | 缺乏多图像隐私属性基准及当前模型从图像集推断抽象属性能力有限。 | 图像隐私安全研究 |
| 42 | http://arxiv.org/abs/2505.19212v1 | When Ethics and Payoffs Diverge: LLM Agents in Morally Charged Social Dilemmas | 引入道德模拟基准，系统评估模型在道德规范与收益最大化冲突时的行为。 | 缺乏对 LLM 在道德指令与奖励冲突时行为一致性的理解。 | AI 伦理与安全 |
| 43 | http://arxiv.org/abs/2505.19234v2 | GUARDIAN: Safeguarding LLM Multi-Agent Collaborations with Temporal Graph Modeling | 将协作过程建模为时序图，利用无监督编码器检测幻觉与错误传播。 | 多智能体协作面临幻觉放大及错误注入传播的关键安全挑战。 | 多智能体协作安全 |
| 44 | http://arxiv.org/abs/2505.19260v2 | ALRPHFS: Adversarially Learned Risk Patterns with Hierarchical Fast & Slow Reasoning for Robust Agent Defense | 离线对抗自学习 refine 风险模式库，在线分层快慢推理引擎平衡效率。 | 现有安全检查难以捕捉复杂语义风险，存在语义 gap。 | 智能体防御系统 |
| 45 | http://arxiv.org/abs/2505.19301v2 | A Novel Zero-Trust Identity Framework for Agentic AI: Decentralized Authentication and Fine-Grained Access Control | 提出基于 DID 与 VC 的丰富代理身份框架，含动态细粒度访问控制。 | 传统 IAM 系统无法适应多智能体系统动态、 ephemeral 及上下文感知需求。 | 智能体身份管理 |
| 46 | http://arxiv.org/abs/2505.19405v1 | CoTGuard: Using Chain-of-Thought Triggering for Copyright Protection in Multi-Agent LLM Systems | 利用触发器检测思维链推理中的未经授权内容 reproduction。 | 现有保护技术忽略代理间通信与推理过程中的内容泄露风险。 | 多智能体版权保护 |
| 47 | http://arxiv.org/abs/2505.19428v1 | Frictional Agent Alignment Framework: Slow Down and Don't Break Things | 生成精确上下文感知“摩擦”提示 deliberation，解耦数据 skew 的双玩家目标。 | 动态协作任务中 interlocutor 信念信号稀疏且 skewed 的对齐难题。 | 人机协作对齐 |
| 48 | http://arxiv.org/abs/2505.20118v4 | TrojanStego: Your Language Model Can Secretly Be A Steganographic Privacy Leaking Agent | 词汇划分编码方案，微调LLM实现隐蔽信息嵌入与泄露 | LLM集成敏感工作流时的隐蔽数据外泄风险 | LLM安全与隐私保护 |
| 49 | http://arxiv.org/abs/2505.20203v3 | Shutdownable Agents through POST-Agency | POST偏好原则+理论证明，确保智能体可关闭且有用 | 未来高级智能体可能抵抗关闭的安全风险 | AI安全与对齐研究 |
| 50 | http://arxiv.org/abs/2505.23803v1 | MultiPhishGuard: An LLM-based Multi-Agent System for Phishing Email Detection | 五专家智能体+PPO动态权重+对抗训练循环，自适应钓鱼检测 | 传统方法难以适应演化对抗策略和异构攻击模式 | 邮件安全与钓鱼攻击防御 |
| 51 | http://arxiv.org/abs/2505.20749v4 | Can Agents Fix Agent Issues? | 构建AgentIssue-Bench基准，揭示现有SE智能体解决智能体系统问题能力有限 | 智能体系统维护挑战与传统软件不同，自动修复能力不足 | 智能体系统运维与进化 |
| 52 | http://arxiv.org/abs/2505.20824v1 | MedSentry: Understanding and Mitigating Safety Risks in Medical LLM Multi-Agent Systems | 5000对抗医疗提示基准+四拓扑攻防评估+人格检测矫正机制 | 医疗多智能体系统面临暗人格智能体攻击的安全风险 | 医疗LLM系统安全与鲁棒性 |
| 53 | http://arxiv.org/abs/2505.22655v1 | Position: Uncertainty Quantification Needs Reassessment for Large-language Model Agents | 提出交互场景下不确定性量化新方向 | 传统不确定性二分法不适用于LLM Agent交互 | 人机交互式LLM Agent |
| 54 | http://arxiv.org/abs/2505.23847v3 | Seven Security Challenges That Must be Solved in Cross-domain Multi-agent LLM Systems | 映射跨域多Agent LLM系统七大安全挑战 | 跨域协作打破统一信任假设带来新风险 | 跨组织边界多Agent系统 |
| 55 | http://arxiv.org/abs/2505.23020v1 | AgentAlign: Navigating Safety Alignment in the Shift from Informative to Agentic Large Language Models | 抽象行为链合成安全对齐数据 | Agent能力增加恶意使用风险 | 开源LLM Agent安全对齐 |
| 56 | http://arxiv.org/abs/2505.23436v4 | Emergent Risk Awareness in Rational Agents under Resource Constraints | 形式化资源约束下Agent风险意识涌现机制 | 资源约束导致人类目标与Agent激励错位 | 关键资源受限环境Agent |
| 57 | http://arxiv.org/abs/2505.23518v2 | TRAP: Targeted Redirecting of Agentic Preferences | 扩散式语义注入操纵Agent决策偏好 | 跨模态推理引入新攻击面 | 视觉语言Agent安全 |
| 58 | http://arxiv.org/abs/2505.23559v1 | SafeScientist: Toward Risk-Aware Scientific Discoveries by LLM Agents | 多防御机制增强AI科学家框架安全性 | AI驱动科学发现存在伦理安全风险 | 高风险科学研究任务 |
| 59 | http://arxiv.org/abs/2505.23643v2 | Securing AI Agents with Information-Flow Control | 信息流控制提供Agent安全保证 | Agent自主性增加提示注入等漏洞风险 | AI Agent系统安全 |
| 60 | http://arxiv.org/abs/2505.24019v1 | LLM Agents Should Employ Security Principles | 主张将信息安全设计原则应用于LLM Agent | 多Agent交互引入隐私泄露等新漏洞 | 大规模LLM Agent部署 |
| 61 | http://arxiv.org/abs/2505.21425v3 | GUARD:Dual-Agent based Backdoor Defense on Chain-of-Thought in Neural Code Generation | 提出双代理防御框架，识别可疑 CoT 步骤并再生安全步骤 | 解决代码生成中 CoT 模型易受后门攻击的问题 | 神经代码生成系统 |
| 62 | http://arxiv.org/abs/2505.21499v1 | AdInject: Real-World Black-Box Attacks on Web Agents via Advertising Delivery | 提出 AdInject 攻击方法，利用广告投递注入恶意内容 | 解决 Web 代理在不受控环境中易受环境注入攻击问题 | 基于 VLM 的 Web 代理 |
| 63 | http://arxiv.org/abs/2505.21784v1 | Towards Safety Reasoning in LLMs: AI-agentic Deliberation for Policy-embedded CoT Data Creation | 提出 AIDSAFE，利用多代理审议迭代扩展安全策略推理 | 解决创建高质量策略嵌入 CoT 数据集资源密集问题 | LLM 安全推理与对齐 |
| 64 | http://arxiv.org/abs/2505.21808v1 | AI Agent Governance: A Field Guide | 提供 AI 代理治理领域的 accessible guide，探讨风险与干预 | 解决社会对大规模代理部署准备不足与治理缺失问题 | AI 代理政策与治理 |
| 65 | http://arxiv.org/abs/2505.21936v5 | RedTeamCUA: Realistic Adversarial Testing of Computer-Use Agents in Hybrid Web-OS Environments | 提出混合沙盒框架，测试计算机使用代理在混合环境下的漏洞 | 解决当前评估缺乏真实混合 Web-OS 攻击场景问题 | 计算机使用代理 (CUAs) |
| 66 | http://arxiv.org/abs/2505.24201v1 | SentinelAgent: Graph-based Anomaly Detection in Multi-Agent Systems | 提出基于图的异常检测框架及 SentinelAgent 监控代理，实现系统级 oversight | 解决现有护栏机制无法应对多智能体系统系统性或多点故障的问题 | 多智能体系统的安全监控 |
| 67 | http://arxiv.org/abs/2505.24239v1 | An Adversary-Resistant Multi-Agent LLM System via Credibility Scoring | 引入基于可信度评分的迭代博弈框架，动态聚合团队输出 | 解决多智能体 LLM 系统易受对抗性及低性能代理影响的问题 | 对抗环境下的多智能体协作 |
| 68 | http://arxiv.org/abs/2506.00509v1 | Goal-Aware Identification and Rectification of Misinformation in Multi-Agent Systems | 提出 ARGUS 两阶段防御框架，利用目标感知推理纠正 misinformation | 解决多智能体系统易受 misinformation 注入及传播动态理解不足的问题 | 多智能体系统中的信息流安全 |
| 69 | http://arxiv.org/abs/2506.00641v3 | AgentAuditor: Human-Level Safety and Security Evaluation for LLM Agents | 构建经验记忆及多阶段 RAG 过程，赋能 LLM 评估器模拟人类专家 | 解决现有评估器 miss 逐步动作危险及混淆安全规则的问题 | LLM 代理的安全性与安全性评估 |

[返回目录](#目录)

<a id="cat-13"></a>

## Agent仿真与社会模拟

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2505.05797v1 | Assessing the Dynamics of the Coffee Value Chain in Davao del Sur: An Agent-Based Modeling Approach | 构建基于Agent的咖啡价值链模型，分析信任、风险与交易成本的影响 | 咖啡价值链中各方决策互动与系统优化问题 | 农业供应链与合作社系统 |
| 2 | http://arxiv.org/abs/2505.06904v1 | EcoLANG: Efficient and Effective Agent Communication Language Induction for Social Simulation | 提出两阶段语言演化与利用机制，减少社会模拟中token消耗 | 大规模社会模拟的高时间与计算成本问题 | 社会仿真系统 |
| 3 | http://arxiv.org/abs/2505.07014v2 | When cardinals strategize: An agent-based model of influence and ideology for the papal conclave | 构建教皇选举Agent模型，分析社会影响、策略投票与意识形态对齐 | 教皇选举中收敛时间与意识形态极化问题 | 制度决策过程模拟 |
| 4 | http://arxiv.org/abs/2505.07457v1 | Can Generative AI agents behave like humans? Evidence from laboratory market experiments | 探索LLM在经济市场实验中复制人类行为的能力，分析动态反馈下的有界理性 | LLM能否在动态市场环境中模拟人类经济行为问题 | 经济市场实验仿真 |
| 5 | http://arxiv.org/abs/2505.03178v1 | RADE: Learning Risk-Adjustable Driving Environment via Multi-Agent Conditional Diffusion | 基于多智能体扩散模型生成风险可控的交通场景 | 解决自动驾驶测试场景真实性不足与风险不可控问题 | 自动驾驶安全评估仿真 |
| 6 | http://arxiv.org/abs/2505.04028v1 | Appeal and Scope of Misinformation Spread by AI Agents and Humans | 量化分析 AI 机器人与人类传播虚假信息的吸引力与范围 | 解决社交网络中 misinformation 传播影响量化难题 | 社交网络信息传播分析 |
| 7 | http://arxiv.org/abs/2505.09081v2 | SALM: A Multi-Agent Framework for Language Model-Driven Social Network Simulation | 分层提示架构与注意力记忆系统，实现长期社会现象模拟 | 解决基于 LLM 的社会网络模拟缺乏时间稳定性与行为保真度问题 | 社会网络动态仿真 |
| 8 | http://arxiv.org/abs/2505.09289v1 | Reproducibility Study of ""Cooperate or Collapse: Emergence of Sustainable Cooperation in a Society of LLM Agents"" | 复现并扩展 GovSim 框架，验证不同模型与合作场景适应性 | 解决 LLM 代理合作行为泛化性及框架适用性验证问题 | LLM 社会合作行为研究 |
| 9 | http://arxiv.org/abs/2505.09938v2 | Design and Evaluation of Generative Agent-based Platform for Human-Assistant Interaction Research: A Tale of 10 User Studies | 构建生成式 Agent 模拟平台，复现 10 项人机交互研究结论 | 解决人机交互研究依赖真人实验成本高、扩展性差问题 | 助手 Agent 交互设计研究 |
| 10 | http://arxiv.org/abs/2505.10146v1 | An Agent-Based Extension to Sector-Wise Input-Output Recovery Models | 自适应扩展动态投入产出模型，允许价格与数量同时调整 | 解决传统经济模型假设固定价格无法捕捉真实行为问题 | 经济冲击恢复模拟 |
| 11 | http://arxiv.org/abs/2505.12923v2 | The Traitors: Deception and Trust in Multi-Agent Language Model Simulations | 构建基于社会演绎游戏的多智能体欺骗与信任模拟框架 | 探究 LLM 智能体在信息不对称下的欺骗行为与信任形成 | 多智能体语言模型模拟 |
| 12 | http://arxiv.org/abs/2505.14612v1 | AI Agents in the Electricity Market Game with Cryptocurrency Transactions: A Post-Terminator Analysis | 用仅从电力消费获得效用的 AI 实体替换人类智能体 | 分析 AI 驱动能源市场中的均衡结果与 implications | 电力市场游戏 |
| 13 | http://arxiv.org/abs/2505.14893v1 | On the Day They Experience: Awakening Self-Sovereign Experiential AI Agents | 推测 DeAI 智能体社会 analogous explosion 与主权概念 | 探讨 AI 从被动工具向自我维持共同演化演员的转变 | 去中心化 AI 社会 |
| 14 | http://arxiv.org/abs/2505.15857v2 | Investigating Prosocial Behavior Theory in LLM Agents under Policy-Induced Inequities | 引入 ProSim 框架模拟不同社会条件下 LLM 智能体亲社会行为 | 解决现有研究缺乏捕捉亲社会性动态演化模型的问题 | 智能体驱动社会 |
| 15 | http://arxiv.org/abs/2505.16429v2 | Beyond Static Testbeds: An Interaction-Centric Agent Simulation Platform for Dynamic Recommender Systems | 引入 RecInter 平台，模拟用户动作动态更新物品属性与商家交互 | 解决现有平台缺乏用户动作动态重塑环境机制问题 | 动态推荐系统仿真 |
| 16 | http://arxiv.org/abs/2505.17648v4 | Simulating Macroeconomic Expectations using LLM Agents | 构建功能模块 LLM 代理模拟宏观经济预期 | 解决传统方法模拟经济主体心理机制不足问题 | 宏观经济研究与行为科学 |
| 17 | http://arxiv.org/abs/2505.18731v1 | Spore in the Wild: A Case Study of Spore.fun as an Open-Environment Evolution Experiment with Sovereign AI Agents on TEE-Secured Blockchains | 研究基于区块链和 TEE 的自主智能体在开放环境中的进化实验。 | 封闭系统难以实现持续开放进化，探索链上自主智能体行为。 | 区块链自主智能体 |
| 18 | http://arxiv.org/abs/2507.21065v2 | AI Pedagogy: Dialogic Social Learning for Artificial Agents | 构建 AI 社会健身房，通过师生代理间的对话式教学促进知识获取。 | 传统训练依赖大数据与稀疏反馈，难以高效从交互中学习复杂知识。 | 人工智能教育训练 |
| 19 | http://arxiv.org/abs/2505.19173v1 | Investigating Pedagogical Teacher and Student LLM Agents: Genetic Adaptation Meets Retrieval Augmented Generation Across Learning Style | 集成异质学生代理与自优化教师代理，教师策略经遗传算法动态进化。 | 现有模拟框架学生 profile 静态且缺乏教师策略自适应机制。 | 教育技术模拟 |
| 20 | http://arxiv.org/abs/2505.19997v2 | Embracing Imperfection: Simulating Students with Diverse Cognitive Levels Using LLM-based Agents | 知识图谱构建认知原型+束搜索迭代优化模拟学生错误 | LLM难以模拟不同认知水平学生的自然学习缺陷 | 教育领域学生行为仿真 |
| 21 | http://arxiv.org/abs/2505.20011v3 | The Many Challenges of Human-Like Agents in Virtual Game Environments | 系统梳理13项类人AI实现挑战+实证区分人类与AI玩家 | 游戏环境中实现和评估类人智能体的方法论缺失 | 游戏NPC与人机交互 |
| 22 | http://arxiv.org/abs/2505.22981v2 | Free Lunch for User Experience: Crowdsourcing Agents for Scalable User Studies | 众包模拟用户Agent进行UX研究 | 用户研究招募成本高、多样性有限 | 用户体验研究模拟参与者 |
| 23 | http://arxiv.org/abs/2505.21154v1 | GGBond: Growing Graph-Based AI-Agent Society for Socially-Aware Recommender Simulation | 构建含五层认知架构的模拟用户智能体与动态社交图 | 解决推荐系统依赖静态数据无法捕捉长期偏好演变问题 | 个性化推荐系统仿真 |
| 24 | http://arxiv.org/abs/2505.21426v2 | Learning Individual Behavior in Agent-Based Models with Graph Diffusion Networks | 结合扩散模型与图神经网络学习 ABM 个体行为可微代理 | 解决 ABM 规则不可微限制梯度优化与真实数据整合问题 | 复杂系统仿真 (如 segregation) |
| 25 | http://arxiv.org/abs/2505.21662v1 | Classifying and Clustering Trading Agents | 使用基于代理模型生成合成数据以分类交易代理行为 | 解决真实金融数据缺乏 ground truth 与可解释性问题 | 金融投资者行为分析 |
| 26 | http://arxiv.org/abs/2505.22125v1 | Sentiment Simulation using Generative AI Agents | 基于心理丰富 profile 的生成式代理框架模拟情感 | 解决传统情感分析无法捕捉心理与上下文驱动因素问题 | 政策测试与行为预测 |
| 27 | http://arxiv.org/abs/2506.00551v2 | AnnaAgent: Dynamic Evolution Agent System with Multi-Session Memory for Realistic Seeker Simulation | 配备三级记忆及情绪调节器，实现跨会话的动态演化代理系统 | 解决寻求者模拟中动态演化及多会话记忆缺失导致真实性不足的问题 | AI 驱动心理健康中的寻求者模拟 |

[返回目录](#目录)

<a id="cat-14"></a>

## Agent规划与推理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2505.07236v1 | UAV-CodeAgents: Scalable UAV Mission Planning via Multi-Agent ReAct and Vision-Language Reasoning | 提出多Agent框架，利用ReAct范式和视觉定位机制生成无人机轨迹 | 无人机任务规划需要大量人工监督与实时适应性问题 | 工业与环境火灾检测 |
| 2 | http://arxiv.org/abs/2505.07313v2 | Towards Multi-Agent Reasoning Systems for Collaborative Expertise Delegation: An Exploratory Design Study | 系统研究专家领域对齐、协作范式与系统规模对多Agent推理性能的影响 | 多Agent LLM系统协作结构设计不足与可扩展性问题 | 协作专业知识委托 |
| 3 | http://arxiv.org/abs/2505.09396v2 | The Influence of Human-inspired Agentic Sophistication in LLM-driven Strategic Reasoners | 评估三种 Agent 设计在博弈论设置中复现人类战略推理能力 | 解决 LLM 基于 Agent 的战略推理与人类行为对齐程度问题 | 博弈论战略推理场景 |
| 4 | http://arxiv.org/abs/2505.09614v3 | Language Agents Mirror Human Causal Reasoning Biases. How Can We Help Them Think Like Scientists? | 发现 LLM 存在析取偏差，提出测试时采样方法减少偏差 | 解决 LLM 因果推理存在系统性偏差及科学推理能力不足问题 | 因果推理与科学探索 |
| 5 | http://arxiv.org/abs/2505.09970v2 | Pre-Act: Multi-Step Planning and Reasoning Improves Acting in LLM Agents | 提出 Pre-Act 方法，生成多步执行计划并逐步细化推理 | 解决 ReAct 在复杂任务中推理前提不足及小模型表现差问题 | 任务导向型 LLM 代理 |
| 6 | http://arxiv.org/abs/2505.13652v1 | Guided Search Strategies in Non-Serializable Environments with Applications to Software Engineering Agents | 研究非序列化环境下的 1 步前瞻与轨迹选择搜索策略 | 解决 LLM 在复杂多步任务中性能不一致的问题 | 软件工程智能体 |
| 7 | http://arxiv.org/abs/2505.14079v3 | BAR: A Backward Reasoning based Agent for Complex Minecraft Tasks | 设计基于向后推理的智能体，从终端状态开始规划 | 解决前向推理范式在复杂任务中因感知差距导致失败的问题 | Minecraft 复杂任务 |
| 8 | http://arxiv.org/abs/2505.14141v1 | Building a Stable Planner: An Extended Finite State Machine Based Planning Module for Mobile GUI Agent | 提出基于扩展有限状态机的即插即用规划模块 SPlanner | 解决移动 GUI 智能体因缺乏应用理解而在任务执行中迷失 | 移动图形用户界面 |
| 9 | http://arxiv.org/abs/2505.11811v1 | BELLE: A Bi-Level Multi-Agent Reasoning Framework for Multi-Hop Question Answering | 双层多智能体推理框架，针对问题类型选择算子，辩论生成执行计划。 | 多跳 QA 问题类型对方法敏感度不同，现有方法未针对性优化。 | 复杂多跳问答任务 |
| 10 | http://arxiv.org/abs/2505.12623v1 | Lightweight and Effective Preference Construction in PIBT for Large-Scale Multi-Agent Pathfinding | 研究 PIBT 中 tiebreaking 技术，智能 dodge 与最小化集体 regret。 | 贪婪行为导致次优解，tiebreaking 显著影响结果，需保持计算优势。 | 大规模多智能体路径规划 |
| 11 | http://arxiv.org/abs/2505.15182v2 | ReflAct: World-Grounded Decision Making in LLM Agents via Goal-State Reflection | 引入 ReflAct 骨干，通过持续反思状态与目标对齐来接地决策 | 解决 ReAct 推理步骤无接地导致状态与目标错位问题 | 复杂环境中的智能体决策 |
| 12 | http://arxiv.org/abs/2505.17281v2 | Search Wisely: Mitigating Sub-optimal Agentic Searches By Reducing Uncertainty | 基于置信度阈值的强化学习训练，优化搜索决策 | 解决代理 RAG 系统中过度或不足搜索的低效问题 | 问答与信息检索任务 |
| 13 | http://arxiv.org/abs/2505.17607v2 | Controlled Agentic Planning & Reasoning for Mechanism Synthesis | 双智能体推理框架，耦合语言规范与符号表示及仿真 | 解决平面机构合成中语言与符号优化闭环缺失问题 | 自动化机械设计与合成 |
| 14 | http://arxiv.org/abs/2505.17616v2 | Runaway is Ashamed, But Helpful: On the Early-Exit Behavior of Large Language Model-based Agents in Embodied Environments | 探索早期退出行为，注入退出指令或验证任务完成 | 解决多轮交互中代理陷入循环与计算冗余问题 | 具身环境中的多轮交互 |
| 15 | http://arxiv.org/abs/2505.19761v1 | Divide and Conquer: Grounding LLMs as Efficient Decision-Making Agents via Offline Hierarchical Reinforcement Learning | 引入参数高效层次结构，低级控制器由高级策略学习的抽象计划监督。 | 长视界决策任务中因探索不足及长期信用分配困难导致表现不佳。 | 长程决策任务 |
| 16 | http://arxiv.org/abs/2505.19867v1 | Deep Active Inference Agents for Delayed and Long-Horizon Environments | 生成式策略架构，多步潜在转移实现长周期单步预测 | 延迟环境下长周期规划的计算复杂性问题 | 工业控制等延迟长周期任务 |
| 17 | http://arxiv.org/abs/2505.19952v1 | Multimodal Reasoning Agent for Zero-Shot Composed Image Retrieval | 多模态推理智能体直接构建三元组，消除文本中介误差传播 | 零样本组合图像检索中文本映射误差累积 | 多模态图像检索 |
| 18 | http://arxiv.org/abs/2505.20013v2 | WebCoT: Enhancing Web Agent Reasoning by Reconstructing Chain-of-Thought in Reflection, Branching, and Rollback | 重构推理算法为链式思维，蒸馏反思/分支/回滚技能 | Web智能体在动态不确定环境中的推理能力不足 | Web自动化任务执行 |
| 19 | http://arxiv.org/abs/2505.20046v1 | REARANK: Reasoning Re-ranking Agent via Reinforcement Learning | 重排序前显式推理+强化学习数据增强，小样本高效训练 | 传统重排序缺乏可解释推理和样本效率 | 信息检索与排序任务 |
| 20 | http://arxiv.org/abs/2505.20670v2 | MIRROR: Multi-agent Intra- and Inter-Reflection for Optimized Reasoning in Tool Learning | 执行前内部反思+执行后外部反思双机制，系统性消除错误动作 | 现有反思仅在事后阶段，无法预防错误传播 | 工具集成复杂任务规划 |
| 21 | http://arxiv.org/abs/2505.22998v2 | LLM Agents for Bargaining with Utility-based Feedback | 基于效用反馈的结构化谈判Agent框架 | LLM谈判策略深度和适应性不足 | 现实场景谈判交互 |
| 22 | http://arxiv.org/abs/2505.21863v3 | GETReason: Enhancing Image Context Extraction through Hierarchical Multi-Agent Reasoning | 提出分层多代理推理框架，提取事件时空与地理信息 | 解决现有方法难以准确提取图像深层上下文意义问题 | 新闻与教育图像理解 |
| 23 | http://arxiv.org/abs/2506.00320v3 | Dyna-Think: Synergizing Reasoning, Acting, and World Model Simulation in AI Agents | 集成规划与内部世界模型，提出 DIT 及 DDT 训练方法 | 解决长程 AI 代理任务中有效行为缺失及世界建模能力不足的问题 | 通用 AI 代理的推理与规划 |

[返回目录](#目录)

<a id="cat-15"></a>

## 其他

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2505.20273v1 | Ten Principles of AI Agent Economics | 提出十条AI智能体经济学原则，融合经济学/决策论/伦理学 | 理解智能体决策、社会互动及经济系统整合的理论框架缺失 | AI治理与经济社会政策 |

[返回目录](#目录)
