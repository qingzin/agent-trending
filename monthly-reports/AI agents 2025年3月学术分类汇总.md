# AI agents 2025年3月学术分类汇总

共收录 388 篇论文，按研究方向分类整理如下。

## 目录

- [Agent评测与基准（34篇）](#cat-01)
- [Agent架构与框架设计（40篇）](#cat-02)
- [Agent规划与推理（17篇）](#cat-03)
- [多Agent协作与通信（50篇）](#cat-04)
- [具身智能Agent（19篇）](#cat-05)
- [Agent仿真与社会模拟（23篇）](#cat-06)
- [多Agent强化学习（52篇）](#cat-07)
- [Agent学习与自进化（22篇）](#cat-08)
- [Agent记忆与知识管理（5篇）](#cat-09)
- [Agent安全与对齐（32篇）](#cat-10)
- [基于Agent的应用系统（58篇）](#cat-11)
- [Agent工具使用与环境交互（13篇）](#cat-12)
- [人机协作Agent（17篇）](#cat-13)
- [低代码/无代码Agent平台（3篇）](#cat-14)
- [Agent可解释性与透明度（2篇）](#cat-15)
- [其他-Agent综述与研究展望（1篇）](#cat-16)

<a id="cat-01"></a>

## Agent评测与基准

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2503.07010v2 | ProjectEval: A Benchmark for Programming Agents Automated Evaluation on Project-Level Code Generation | 模拟用户交互的项目级代码生成自动评估基准 | 现有基准缺乏用户视角自动评估和结果可解释性 | 编程Agent项目级代码生成能力评估 |
| 2 | http://arxiv.org/abs/2503.07459v2 | MedAgentsBench: Benchmarking Thinking Models and Agent Frameworks for Complex Medical Reasoning | 聚焦多步临床推理的医疗Agent基准 | 现有医疗基准问题简单、评估协议不一致 | 复杂医疗推理、诊断和治疗规划 |
| 3 | http://arxiv.org/abs/2503.07832v1 | RefactorBench: Evaluating Stateful Reasoning in Language Agents Through Code | 100个手工多文件重构任务的Agent基准 | 当前Agent在简单组合任务上表现差 | 代码重构中的状态推理能力评估 |
| 4 | http://arxiv.org/abs/2503.07919v3 | BEARCUBS: A benchmark for computer-using web agents | 111个信息寻求问题的真实网页Agent基准 | 真实网页交互 unpredictability 和多模态交互评估 | 计算机使用网页Agent能力评估 |
| 5 | http://arxiv.org/abs/2503.08193v1 | Guess What I am Thinking: A Benchmark for Inner Thought Reasoning of Role-Playing Language Agents | 角色Agent内部思维推理的ROLETHINK基准 | 角色扮演Agent内部思维过程未探索 | 角色扮演语言Agent思维生成评估 |
| 6 | http://arxiv.org/abs/2503.08241v1 | HASARD: A Benchmark for Vision-Based Safe Reinforcement Learning in Embodied Agents | 首个纯第一人称视觉的安全RL基准 | 现有视觉3D基准仅考虑简单导航任务 | 具身Agent安全强化学习评估 |
| 7 | http://arxiv.org/abs/2503.08669v2 | SOPBench: Evaluating Language Agents at Following Standard Operating Procedures and Constraints | 167个工具/函数的SOP遵循自动评估流水线 | Agent遵循领域特定SOP和约束能力未充分探索 | 客户服务等领域Agent合规性评估 |
| 8 | http://arxiv.org/abs/2503.09385v2 | PCLA: A Framework for Testing Autonomous Agents in the CARLA Simulator | 首个专为CARLA环境测试自主Agent的开源框架 | 研究者测试Leaderboard Agent面临定制化挑战 | CARLA模拟器中自动驾驶Agent测试 |
| 9 | http://arxiv.org/abs/2503.01935v1 | MultiAgentBench: Evaluating the Collaboration and Competition of LLM agents | 综合基准评估多智能体协作与竞争动态 | 现有基准缺乏多智能体协调动态评估 | LLM 多智能体系统评估 |
| 10 | http://arxiv.org/abs/2503.04798v2 | Advancing MAPF towards the Real World: A Scalable Multi-Agent Realistic Testbed (SMART) | 基于物理引擎的可扩展 MAPF 测试床 | 填补实验室算法与真实机器人性能差距 | 多智能体路径规划评估 |
| 11 | http://arxiv.org/abs/2503.02403v2 | AutoEval: A Practical Framework for Autonomous Evaluation of Mobile Agents | UI 状态变化表示自动生成任务奖励信号 | 解决移动代理评估需大量人工努力问题 | 移动智能体自动化评估 |
| 12 | http://arxiv.org/abs/2503.03056v1 | A2Perf: Real-World Autonomous Agents Benchmark | 提供接近真实域的环境与多维指标 | 缺乏定义环境数据集指标的统一基准 | 现实世界自主代理评估 |
| 13 | http://arxiv.org/abs/2503.03586v2 | Benchmarking LLMs and LLM-based Agents in Practical Vulnerability Detection for Code Repositories | 引入 JitVul 基准，链接函数与漏洞引入/修复提交 | 解决现有基准缺乏过程间上下文及配对评估的问题 | 代码仓库漏洞检测 |
| 14 | http://arxiv.org/abs/2503.04479v3 | ToolFuzz -- Automated Agent Tool Testing | 提出首个自动测试工具文档的方法，发现描述错误 | 解决工具文档指定不清影响智能体准确性的问题 | 智能体工具文档测试 |
| 15 | http://arxiv.org/abs/2503.05143v1 | FedMABench: Benchmarking Mobile Agents on Decentralized Heterogeneous User Data | 引入首个联邦训练与评估移动智能体的基准 | 解决缺乏标准化基准阻碍联邦移动智能体进展的问题 | 移动智能体联邦学习 |
| 16 | http://arxiv.org/abs/2503.06047v1 | DSGBench: A Diverse Strategic Game Benchmark for Evaluating LLM-based Agents in Complex Decision-Making Environments | 引入 DSGBench，包含六个复杂战略游戏及细粒度评分 | 解决现有基准关注单目标或评估指标过宽的问题 | 复杂决策环境智能体 |
| 17 | http://arxiv.org/abs/2504.06277v1 | Dynamic Evaluation Framework for Personalized and Trustworthy Agents: A Multi-Session Approach to Preference Adaptability | 提出动态评估框架，模拟用户偏好适应性 | 解决现有评估方法无法捕捉用户交互动态演变的问题 | 个性化可信智能体 |
| 18 | http://arxiv.org/abs/2503.06745v1 | Beyond Black-Box Benchmarking: Observability, Analytics, and Optimization of Agentic Systems | 引入分类法及基于运行时日志的基准，超越黑盒评估 | 解决传统评估难以处理非确定性及动态行为的问题 | 智能体系统可观测性 |
| 19 | http://arxiv.org/abs/2503.16416v1 | Survey on Evaluation of LLM-based Agents | 首个LLM Agent评估方法全面综述，四维度分析 | Agent评估方法缺乏系统梳理 | LLM Agent评估研究 |
| 20 | http://arxiv.org/abs/2503.10105v1 | StepMathAgent: A Step-Wise Agent for Evaluating Mathematical Processes through Tree-of-Error | 提出基于错误树的逐步数学过程评估代理，包含内外核心模块 | 解决现有评估方法仅关注最终答案导致不准确且不可解释的问题 | 数学能力评估 |
| 21 | http://arxiv.org/abs/2503.10248v1 | LLM Agents Display Human Biases but Exhibit Distinct Learning Patterns | 调查 LLM 在经验决策任务中的选择模式，对比人类行为偏差 | 解决 LLM 模拟人类决策学习环境的局限性及行为差异问题 | 人类行为模拟与评估 |
| 22 | http://arxiv.org/abs/2503.12374v3 | Beyond Final Code: A Process-Oriented Error Analysis of Software Development Agents in Real-World GitHub Scenarios | 对软件开发智能体的解决过程进行实证研究，识别 prevalent 错误 | 现有评估仅关注静态代码，缺乏动态问题解决过程洞察 | 软件工程智能体 |
| 23 | http://arxiv.org/abs/2503.12651v1 | VeriLA: A Human-Centered Evaluation Framework for Interpretable Verification of LLM Agent Failures | 引入以人为本的评估框架，系统评估智能体失败使其可解释 | 智能体执行失败不透明，人工干预成本高 | LLM 智能体失败验证 |
| 24 | http://arxiv.org/abs/2503.13657v3 | Why Do Multi-Agent LLM Systems Fail? | 引入 MAST-Data 数据集与失败分类法，系统识别分析失败模式 | 多智能体 LLM 系统性能增益小，缺乏失败原理理解 | 多智能体 LLM 系统 |
| 25 | http://arxiv.org/abs/2504.13861v3 | 3MDBench: Medical Multimodal Multi-agent Dialogue Benchmark | 首创医疗多模态多Agent对话评估基准框架 | LVLM在远程医疗咨询中的诊断和对话能力评估 | 远程医疗 telemedicine |
| 26 | http://arxiv.org/abs/2503.20749v7 | Can LLM Agents Simulate Multi-Turn Human Behavior? Evidence from Real Online Customer Behavior Data | 首个大规模定量评估LLM模拟人类行为的基准 | LLM Agent在多轮交互中行为准确性不足问题 | 在线购物行为模拟 |
| 27 | http://arxiv.org/abs/2503.21138v5 | A Computational Theory for Efficient Mini Agent Evaluation with Causal Guarantees | 提出Agent评估计算理论，构建评估模型加速评估 | Agent实验评估成本高、耗时长的问题 | 多领域Agent评估 |
| 28 | http://arxiv.org/abs/2503.22458v2 | Evaluating LLM-based Agents for Multi-Turn Conversations: A Survey | 建立多轮对话Agent评估的双分类体系框架 | 多轮对话Agent评估方法缺乏系统化分类 | 多轮对话Agent评估 |
| 29 | http://arxiv.org/abs/2503.23145v2 | CodeARC: Benchmarking Reasoning Capabilities of LLM Agents for Inductive Program Synthesis | 首创大规模归纳程序合成交互式评估基准 | 现有评估协议无反馈，无法反映逆向工程等真实场景 | 归纳程序合成 |
| 30 | http://arxiv.org/abs/2503.18129v2 | GeoBenchX: Benchmarking LLMs in Agent Solving Multistep Geospatial Tasks | 建立地理空间任务基准，评估 LLM 工具调用能力 | 缺乏评估 LLM 解决多步地理空间任务的标准 | 商业 GIS 从业者任务 |
| 31 | http://arxiv.org/abs/2503.18825v4 | EconEvals: Benchmarks and Litmus Tests for Economic Decision-Making by LLM Agents | 开发经济学基准与石蕊测试，量化 LLM 选择行为 | 缺乏衡量 LLM 经济决策能力与倾向的评估方法 | LLM 经济决策评估 |
| 32 | http://arxiv.org/abs/2503.19711v1 | Writing as a testbed for open ended agents | 建立自主写作 Agent 基准框架，分析行动多样性 | 开放-ended 任务解决方案空间大，成功定义不明确 | 开放域写作任务 |
| 33 | http://arxiv.org/abs/2503.23452v2 | VideoGen-Eval: Agent-based System for Video Generation Evaluation | 集成 LLM 内容结构化与 MLLM 判断，动态评估视频生成 | 现有评估系统提示简单，指标与人类偏好不对齐 | 视频生成模型评估 |
| 34 | http://arxiv.org/abs/2504.00255v2 | SciReplicate-Bench: Benchmarking LLMs in Agent-driven Algorithmic Reproduction from Research Papers | 构建基准评估 LLM 从论文生成代码能力，双 agent 框架 | 算法复现需理解文献与编码，现有模型准确率低 | 科学论文算法复现与代码生成 |

[返回目录](#目录)

<a id="cat-02"></a>

## Agent架构与框架设计

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2503.07044v2 | DatawiseAgent: A Notebook-Centric LLM Agent Framework for Adaptive and Robust Data Science Automation | 笔记本中心的多阶段有限状态转换器架构 | 任务范围窄、泛化能力有限、过度依赖SOTA模型 | 数据科学自动化任务 |
| 2 | http://arxiv.org/abs/2503.08308v1 | Seeing and Reasoning with Confidence: Supercharging Multimodal LLMs with an Uncertainty-Aware Agentic Framework | 整合外部视觉模型与不确定性量化的无训练框架 | CoT标注成本高、外部工具输出不可靠 | 多模态LLM视觉问答推理 |
| 3 | http://arxiv.org/abs/2503.09263v1 | COLA: A Scalable Multi-Agent Framework For Windows UI Task Automation | 场景感知任务调度器的协作多Agent框架 | 静态架构无法适应异构需求、工作流缺乏容错 | Windows GUI操作自动化 |
| 4 | http://arxiv.org/abs/2504.06272v1 | RAVEN: An Agentic Framework for Multimodal Entity Discovery from Large-Scale Video Collections | 自适应框架合成视听文本模态信息 | 大规模视频集合中多模态实体发现 | 视频内容检索与发现 |
| 5 | http://arxiv.org/abs/2503.02068v1 | Interactive Debugging and Steering of Multi-Agent AI Systems | 交互式调试工具支持消息重置与配置迭代 | 解决多智能体系统错误定位与调试难 | 多智能体 AI 系统开发 |
| 6 | http://arxiv.org/abs/2503.02519v4 | Generator-Assistant Stepwise Rollback Framework for Large Language Model Agent | 生成器与助手协作触发错误回滚机制 | 解决逐步推理中错误传播不可逆问题 | 大语言模型智能体决策 |
| 7 | http://arxiv.org/abs/2503.03459v2 | Unified Mind Model: Reimagining Autonomous Agents in the LLM Era | 提出统一心智模型 (UMM) 认知架构，指导人类级智能体创建 | 解决基于 LLM 的智能体缺乏理论基础的问题 | 通用自主智能体构建 |
| 8 | http://arxiv.org/abs/2503.05659v2 | A Survey of Large Language Model Empowered Agents for Recommendation and Search: Towards Next-Generation Information Retrieval | 系统 review 并分类 LLM 智能体在推荐搜索中的研究 | 解决缺乏对 LLM 智能体在信息检索中作用的系统 review | 推荐与搜索系统 |
| 9 | http://arxiv.org/abs/2503.06410v1 | Performant LLM Agentic Framework for Conversational AI | 结合 LLM 推理与向量评分机制，优化图工作流遍历 | 解决复杂工作流中对齐错误及上下文过大导致幻觉问题 | 语音 AI 行业对话系统 |
| 10 | http://arxiv.org/abs/2503.07675v2 | DynTaskMAS: A Dynamic Task Graph-driven Framework for Asynchronous and Parallel LLM-based Multi-Agent Systems | 通过动态任务图编排异步并行操作，优化资源利用 | 解决现有框架缺乏并行执行及动态任务管理机制问题 | 高性能 LLM 多智能体系统 |
| 11 | http://arxiv.org/abs/2503.15029v1 | DRoPE: Directional Rotary Position Embedding for Efficient Agent Interaction Modeling | 方向旋转位置嵌入，编码相对角度信息 | 轨迹生成准确性、时间、内存效率三角困境 | 自动驾驶/轨迹生成 |
| 12 | http://arxiv.org/abs/2503.15764v2 | Towards Agentic AI Networking in 6G: A Generative Foundation Model-as-Agent Approach | AgentNet框架，GFM-as-Agent交互式知识库 | 网络AI自主方案发现与环境适应局限 | 6G网络/工业数字孪生 |
| 13 | http://arxiv.org/abs/2503.15937v5 | Advancing Mobile GUI Agents: A Verifier-Driven Approach to Practical Deployment | V-Droid验证器驱动范式，LLM评估候选动作 | 移动GUI Agent延迟高、成功率低 | 移动自动化/Android任务 |
| 14 | http://arxiv.org/abs/2503.20793v2 | Semantic Web and Software Agents -- A Forgotten Wave of Artificial Intelligence? | 回顾语义网与软件Agent历史，分析学术影响 | 被遗忘的AI浪潮对现代Agent开发启示 | 软件Agent发展历史 |
| 15 | http://arxiv.org/abs/2504.01963v1 | LLMs Working in Harmony: A Survey on the Technological Aspects of Building Effective LLM-Based Multi Agent Systems | 系统综述 LLM 多智能体系统的架构、记忆、规划等关键技术 | 解决多智能体系统可扩展性、实时响应及协作约束挑战 | LLM 多智能体系统构建 |
| 16 | http://arxiv.org/abs/2503.11069v2 | API Agents vs. GUI Agents: Divergence and Convergence | 首次全面比较 API 与 GUI 基于 LLM 代理的架构差异与融合 | 解决 practitioner 在选择或过渡两种自动化范式时的决策困难 | LLM 驱动任务自动化 |
| 17 | http://arxiv.org/abs/2503.11301v1 | GNNs as Predictors of Agentic Workflow Performances | 将代理工作流公式化为计算图，倡导 GNN 作为性能预测器 | 解决优化代理工作流因大量调用 LLM 导致成本高效率低的问题 | 代理工作流优化 |
| 18 | http://arxiv.org/abs/2503.11951v3 | SagaLLM: Context Management, Validation, and Transaction Guarantees for Multi-Agent LLM Planning | 集成 Saga 事务模式与持久记忆，确保工作流一致性与恢复 | 解决当前 LLM 规划系统自验证不可靠、上下文丢失及缺乏事务保障问题 | 多代理 LLM 规划 |
| 19 | http://arxiv.org/abs/2503.12217v1 | TFHE-Coder: Evaluating LLM-agentic Fully Homomorphic Encryption Code Generation | 提出编译器集成框架，评估 LLM 智能体优化 TFHE 代码生成 | 全同态加密代码生成的复杂性与可用性挑战 | 隐私保护计算 |
| 20 | http://arxiv.org/abs/2503.16514v1 | VeriMind: Agentic LLM for Automated Verilog Generation with a Novel Evaluation Metric | 采用结构化推理方法，生成 Verilog 代码并提出 pass@ARC 指标 | 手动编写 Verilog 代码复杂耗时，需专家知识 | 硬件设计与 RTL 开发 |
| 21 | http://arxiv.org/abs/2503.12687v1 | AI Agents: Evolution, Architecture, and Real-World Applications | 审查关键智能体范式，提出平衡有效性、效率、鲁棒性的评估框架 | 当前评估基准局限性，缺乏 holistic 评估框架 | AI 智能体综述 |
| 22 | http://arxiv.org/abs/2503.12871v3 | A Reference Architecture for Autonomous Networks: An Agent-Based Approach | 提出网络智能体参考架构，指定实现所需功能 | 自主网络开发缺乏严谨方法论与参考架构 | 自主网络 |
| 23 | http://arxiv.org/abs/2503.13444v3 | VideoMind: A Chain-of-LoRA Agent for Temporal-Grounded Video Reasoning | 提出 Chain-of-LoRA 机制，统一基模型与多 LoRA 适配器实现角色切换 | 视频多模态推理受限，缺乏精确 grounded 理解 | 视频推理 |
| 24 | http://arxiv.org/abs/2503.13754v2 | From Autonomous Agents to Integrated Systems, A New Paradigm: Orchestrated Distributed Intelligence | 引入 Orchestrated Distributed Intelligence 范式，重构 AI 为协调网络 | 静态记录系统需转变为动态行动导向环境 | 集成系统与人类工作流 |
| 25 | http://arxiv.org/abs/2503.20479v1 | A multi-agentic framework for real-time, autonomous freeform metasurface design | MetaChat框架实现语义描述到光子器件布局的自动转化 | 纳米光子学设计依赖专家、耗时且次优的问题 | 超表面/纳米光子学设计 |
| 26 | http://arxiv.org/abs/2503.20536v1 | Knowledge-Based Multi-Agent Framework for Automated Software Architecture Design | MAAD框架模拟人类角色实现架构设计自动化 | 软件架构设计依赖专家经验、成本高昂问题 | 软件架构设计 |
| 27 | http://arxiv.org/abs/2503.20776v2 | Feature4X: Bridging Any Monocular Video to 4D Agentic AI with Versatile Gaussian Feature Fields | 首创将视频基础模型特征蒸馏到4D高斯特征场 | 2D模型难以扩展到3D/4D场景交互的问题 | 4D动态场景交互 |
| 28 | http://arxiv.org/abs/2503.21460v1 | Large Language Model Agent: A Survey on Methodology, Applications and Challenges | 系统化解构LLM Agent系统的方法论中心分类法 | LLM Agent研究领域碎片化、缺乏统一视角 | LLM Agent研究综述 |
| 29 | http://arxiv.org/abs/2504.13865v2 | A Survey on (M)LLM-Based GUI Agents | 系统分析GUI Agent四大核心组件和评估方法 | GUI Agent领域缺乏系统性综述和标准化评估 | GUI Agent研究综述 |
| 30 | http://arxiv.org/abs/2503.22241v3 | Agent-Centric Personalized Multiple Clustering with Multi-Modal LLMs | 多模态LLM Agent遍历关系图搜索用户兴趣聚类 | CLIP嵌入缺乏对用户兴趣的深度上下文理解 | 个性化数据聚类 |
| 31 | http://arxiv.org/abs/2503.22931v2 | Factored Agents: Decoupling In-Context Learning and Memorization for Robust Tool Use | 因子化架构解耦规划器和记忆器两个专用组件 | 单体Agent设计中API字段错误和动态环境规划次优 | 工具使用Agent |
| 32 | http://arxiv.org/abs/2503.23037v3 | Agentic Large Language Models, a survey | 按推理-行动-交互三类别组织代理式LLM文献 | 代理式LLM研究领域缺乏系统性整理和研究议程 | 代理式LLM研究综述 |
| 33 | http://arxiv.org/abs/2504.08747v1 | GridMind: A Multi-Agent NLP Framework for Unified, Cross-Modal NFL Data Insights | 多 Agent 框架统一多模态数据，支持自然语言查询 | 多模态体育数据整合难， conventional 系统处理受限 | NFL 数据分析与查询 |
| 34 | http://arxiv.org/abs/2503.19889v2 | A Multi-Agent Framework Integrating Large Language Models and Generative AI for Accelerated Metamaterial Design | 分层 Agent 团队协同，整合 LLM 推理与生成 AI 精度 | 超材料设计受限于试错法与数据互操作性有限 | 超材料设计自动化 |
| 35 | http://arxiv.org/abs/2503.20028v1 | OmniNova:A General Multimodal Agent Framework | 分层多 Agent 架构，动态任务路由与多层 LLM 集成 | 编排多 LLM 驱动 Agent 处理复杂任务协调难 | 研究、数据分析与 Web 交互 |
| 36 | http://arxiv.org/abs/2503.23350v4 | A Survey of WebAgents: Towards Next-Generation AI Agents for Web Automation with Large Foundation Models | 综述 WebAgent 架构、训练与可信性，展望研究方向 | 网页任务重复耗时，需自主 agent 提升效率 | 网页自动化与基础模型应用 |
| 37 | http://arxiv.org/abs/2503.23948v1 | AI2Agent: An End-to-End Framework for Deploying AI Projects as Autonomous Agents | 端到端框架自动化 AI 项目部署，自适调试与案例积累 | AI 项目部署环境配置复杂，依赖冲突多 | AI 项目自动化部署与管理 |
| 38 | http://arxiv.org/abs/2503.24047v3 | Towards Scientific Intelligence: A Survey of LLM-based Scientific Agents | 综述 LLM 科学代理架构、设计与伦理，区别于通用代理 | 科学研究复杂，需专用代理管理数据与加速发现 | 科学研究自动化与智能代理 |
| 39 | http://arxiv.org/abs/2503.24078v3 | A Complete Mental Temporal Logic for Intelligent Agent | 提出 BPICTL 逻辑，泛化 CTL 引入心理模态 | 智能体推理缺乏完整 mental temporal 逻辑支持 | 智能体逻辑形式化与推理 |
| 40 | http://arxiv.org/abs/2504.01990v2 | Advances and Challenges in Foundation Agents: From Brain-Inspired Intelligence to Evolutionary, Collaborative, and Safe Systems | 综述基础代理模块化架构，整合认知科学与神经科学 | 代理设计评估复杂，需模块化与安全性保障 | 基础智能体架构与安全系统 |

[返回目录](#目录)

<a id="cat-03"></a>

## Agent规划与推理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2503.07129v2 | ASTRA: A Negotiation Agent with Adaptive and Strategic Reasoning via Tool-integrated Action for Dynamic Offer Optimization | 基于对手建模和Tit-for-Tat互惠原则的谈判框架 | 有界理性、适应性低、战略推理有限 | 动态谈判场景中的报价优化 |
| 2 | http://arxiv.org/abs/2503.07783v1 | Sensemaking in Novel Environments: How Human Cognition Can Inform Artificial Agents | 基于符号关系的统一意义构建概念框架 | 人工Agent在新环境中理解对象/事件/情境 | 新环境中的Agent认知与理解 |
| 3 | http://arxiv.org/abs/2503.09572v3 | Plan-and-Act: Improving Planning of Agents for Long-Horizon Tasks | 显式规划整合和合成数据生成的规划框架 | LLM未固有训练生成准确计划、长视野任务困难 | Web导航等长视野规划任务 |
| 4 | http://arxiv.org/abs/2503.02682v2 | MPO: Boosting LLM Agents with Meta Plan Optimization | 利用元计划直接 Incorporate 显式指导 | 解决规划幻觉与新智能体需重训练问题 | LLM 智能体交互规划 |
| 5 | http://arxiv.org/abs/2503.03505v2 | Parallelized Planning-Acting for Efficient LLM-based Multi-Agent Systems in Minecraft | 提出并行规划 - 执行框架，支持双线程中断执行 | 解决序列化执行限制实时响应与动态适应的问题 | Minecraft 多智能体系统 |
| 6 | http://arxiv.org/abs/2503.04094v1 | PokéChamp: an Expert-level Minimax Language Agent | 利用 LLM 增强 minimax 树搜索，替换关键模块 | 解决部分可观察性及搜索空间过大问题 | 宝可梦对战游戏 |
| 7 | http://arxiv.org/abs/2503.05383v5 | AVA: Attentive VLM Agent for Mastering StarCraft II | 引入 RGB 视觉输入和自然语言观察，对齐人类体验 | 解决传统框架抽象状态表示偏离人类感知的问题 | 星际争霸 II 游戏 |
| 8 | http://arxiv.org/abs/2503.06951v2 | ReAgent: Reversible Multi-Agent Reasoning for Knowledge-Enhanced Multi-Hop QA | 引入可逆多智能体协作框架，支持显式回溯机制 | 解决 CoT 不可逆导致多跳推理错误积累的问题 | 多跳问答任务 |
| 9 | http://arxiv.org/abs/2503.14269v1 | DARS: Dynamic Action Re-Sampling to Enhance Coding Agent Performance by Adaptive Tree Traversal | 动态动作重采样，自适应树遍历恢复次优决策 | 编码Agent次优决策恢复效率低 | 软件工程/代码开发Agent |
| 10 | http://arxiv.org/abs/2503.16032v1 | Agentic Keyframe Search for Video Question Answering | 语言Agent引导经典搜索算法识别关键帧 | 视频QA计算成本高、理解需求大 | 视频理解/问答 |
| 11 | http://arxiv.org/abs/2503.16788v1 | Does Chain-of-Thought Reasoning Help Mobile GUI Agent? An Empirical Study | 首个推理VLM在移动GUI Agent有效性实证研究 | 推理能力对移动GUI Agent实际影响不明 | 移动GUI自动化 |
| 12 | http://arxiv.org/abs/2503.16874v2 | MARS: Multi-Agent Adaptive Reasoning with Socratic Guidance for Automated Prompt Optimization | 五Agent苏格拉底式对话优化提示，POMDP建模 | 自动提示优化模板僵化、探索低效 | 提示工程/LLM优化 |
| 13 | http://arxiv.org/abs/2503.10009v3 | OR-LLM-Agent: Automating Modeling and Solving of Operations Research Optimization Problems with Reasoning LLM | 基于推理 LLM 构建三阶段代理框架，自动化 OR 问题建模与求解 | 解决非推理 LLM 在运筹优化问题求解能力受限的问题 | 运筹优化问题求解 |
| 14 | http://arxiv.org/abs/2503.11074v2 | Exploring the Necessity of Reasoning in LLM-based Agent Scenarios | 提出 LaRMA 框架，探索 LRMs 与 LLMs 在代理场景中的必要性 | 解决执行导向 LLM 与推理导向 LRM 在代理任务中的平衡问题 | LLM 基于代理场景 |
| 15 | http://arxiv.org/abs/2503.19815v1 | Thinking agents for zero-shot generalization to qualitatively novel tasks | 训练 Agent 利用世界模型进行心理模拟解决新任务 | 智能体解决从未遇到的真正新颖问题能力不足 | 零 shot 泛化到新任务 |
| 16 | http://arxiv.org/abs/2503.23415v1 | An Analysis of Decoding Methods for LLM-based Agents for Faithful Multi-Hop Question Answering | 分析 ReAct 框架与解码策略组合对事实忠实度的影响 | LLM 生成内容幻觉，难以忠实于检索信息 | 多跳问答与知识密集型任务 |
| 17 | http://arxiv.org/abs/2503.23508v1 | Re-Aligning Language to Visual Objects with an Agentic Workflow | 代理工作流自适应调整图文提示，循环改进描述 | VLM 幻觉导致对象描述不准，影响视觉语言对齐 | 基于语言的对象检测与数据对齐 |

[返回目录](#目录)

<a id="cat-04"></a>

## 多Agent协作与通信

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2503.07217v3 | ReelWave: Multi-Agentic Movie Sound Generation through Multimodal LLM Conversation | 声音导演Agent监督的多Agent电影音频生成框架 | 多场景电影中屏幕内外声音的时间对齐生成 | 电影制作中的音频内容生成 |
| 2 | http://arxiv.org/abs/2503.07686v1 | Adaptive routing protocols for determining optimal paths in AI multi-agent systems: a priority- and learning-enhanced approach | 优先级和强化学习增强的自适应路由算法 | 复杂多Agent网络中上下文感知的自适应路由需求 | AI多Agent系统网络通信优化 |
| 3 | http://arxiv.org/abs/2503.07314v1 | Automated Movie Generation via Multi-Agent CoT Planning | 多Agent链式思维规划的电影自动生成框架 | 长视频生成缺乏自动规划、人工成本高 | 多场景长视频/电影自动生成 |
| 4 | http://arxiv.org/abs/2503.07702v2 | A Reliable Self-Organized Distributed Complex Network for Communication of Smart Agents | 强化学习训练Agent自组织形成通信网络 | IoT网络动态场景中可靠连接与能耗优化 | 物联网、车联网等动态通信网络 |
| 5 | http://arxiv.org/abs/2503.08199v2 | A Cascading Cooperative Multi-agent Framework for On-ramp Merging Control Integrating Large Language Models | 级联合作多Agent框架整合RL和LLM | 传统RL难以复制人类行为、多Agent协调不足 | 复杂驾驶环境中的匝道合并控制 |
| 6 | http://arxiv.org/abs/2503.08421v2 | Learning to Detect Objects from Multi-Agent LiDAR Scans without Manual Labels | 利用多Agent互补观测的无监督3D目标检测 | 数据稀疏和视角有限导致伪标签质量低 | 多Agent协作感知中的3D目标检测 |
| 7 | http://arxiv.org/abs/2503.09039v1 | Incentive Analysis for Agent Participation in Federated Learning | 联邦学习中Agent参与决策与均衡行为分析 | Agent选择全球训练或独立本地训练的决策 | 联邦学习系统中的Agent参与激励 |
| 8 | http://arxiv.org/abs/2503.09369v1 | Task Allocation for Multi-agent Systems via Unequal-dimensional Optimal Transport | 不等维最优运输框架的大规模任务分配 | 确定最小化整体运输成本的最优部署策略 | 无人机时间敏感医疗配送等任务 |
| 9 | http://arxiv.org/abs/2503.09400v2 | Networked Communication for Decentralised Cooperative Agents in Mean-Field Control | 平均场控制中分散合作Agent的网络通信算法 | 合作平均场控制研究少于非合作平均场博弈 | 大规模集体行为的工程化 |
| 10 | http://arxiv.org/abs/2503.09403v2 | Multi-Agent Image Restoration | 模拟人类专家团队的三阶段多Agent图像恢复 | 专用和全能IR模型难以处理复杂混合退化 | 真实世界复杂图像恢复任务 |
| 11 | http://arxiv.org/abs/2503.00717v1 | LLMDR: LLM-Driven Deadlock Detection and Resolution in Multi-Agent Pathfinding | 集成 LLM 推理与优先规划解决死锁 | 提升学习式路径规划在复杂场景的可扩展性 | 多智能体路径规划 (MAPF) |
| 12 | http://arxiv.org/abs/2503.02390v3 | ReSo: A Reward-driven Self-organizing LLM-based Multi-Agent System for Reasoning Tasks | 奖励驱动的两阶段智能体选择过程 | 解决现有 MAS 框架灵活性与可扩展性差 | 复杂推理任务多智能体系统 |
| 13 | http://arxiv.org/abs/2503.02445v7 | BRIDGE: Bootstrapping Text to Control Time-Series Generation via Multi-Agent Iterative Optimization and Diffusion Modeling | 多智能体迭代优化结合扩散模型 | 跨域时间序列生成的可控性与数据稀缺 | 时间序列数据生成 |
| 14 | http://arxiv.org/abs/2503.02954v1 | Reliable and Efficient Multi-Agent Coordination via Graph Neural Network Variational Autoencoders | GNN-VAE 编码图问题解至潜空间加速协调 | 解决密集机器人交通中集中式协调慢问题 | 多机器人导航协调 |
| 15 | http://arxiv.org/abs/2503.03779v2 | Accelerating Focal Search in Multi-Agent Path Finding with Tighter Lower Bounds | 双 ECBS 算法确定最大下界加速搜索 | 解决传统 focal 搜索早期下界增长慢问题 | 多智能体路径规划搜索 |
| 16 | http://arxiv.org/abs/2503.04827v1 | Preserving Cultural Identity with Context-Aware Translation Through Multi-Agent AI Systems | 利用多智能体框架进行文化自适应翻译，保留语言细微差别 | 解决现有翻译模型忽视文化细微差别和历史意义的问题 | 濒危语言社区翻译 |
| 17 | http://arxiv.org/abs/2503.05473v2 | The Society of HiveMind: Multi-Agent Optimization of Foundation Model Swarms to Unlock the Potential of Collective Intelligence | orchestrate 多个基础模型交互，模仿动物群体行为 | 解决单一模型逻辑推理能力不足及可扩展性问题 | 集体智能与模型 swarm |
| 18 | http://arxiv.org/abs/2503.14340v2 | MANTRA: Enhancing Automated Method-Level Refactoring with Contextual RAG and Multi-Agent LLM Collaboration | 上下文感知RAG+多Agent协作+言语强化学习 | 代码重构自动化程度低、正确性难保证 | 软件重构/Java项目 |
| 19 | http://arxiv.org/abs/2503.14948v2 | ChatStitch: Visualizing Through Structures via Surround-View Unsupervised Deep Image Stitching with Collaborative LLM-Agents | 认知闭环交互多Agent框架+环绕视图无监督图像拼接 | 环绕视图感知单向交互瓶颈、畸变传播 | 自动驾驶/视觉感知 |
| 20 | http://arxiv.org/abs/2503.15079v1 | LogiAgent: Automated Logical Testing for REST Systems with LLM-Based Multi-Agents | 三Agent协作生成、执行、验证API测试场景 | REST API逻辑问题检测被忽视 | Web服务/API测试 |
| 21 | http://arxiv.org/abs/2503.15272v1 | MAMM-Refine: A Recipe for Improving Faithfulness in Generation with Multi-Agent Collaboration | 多Agent多模型协作迭代检测、批评、修正 | 长文本生成事实不一致问题 | 摘要生成/问答 |
| 22 | http://arxiv.org/abs/2503.16905v2 | MAPS: Multi-Agent Personality Shaping for Collaborative Reasoning | Big Five人格理论塑造Agent多样性+批评Agent反思 | 多Agent协作行为同质化、缺乏反思 | 协作推理/问题解决 |
| 23 | http://arxiv.org/abs/2503.17460v2 | ConvoGen: Enhancing Conversational AI with Synthetic Data: A Multi-Agent Approach | 动态更新少样本中心迭代采样生成对话数据 | 对话AI训练评估数据质量与多样性 | 对话AI/数据增强 |
| 24 | http://arxiv.org/abs/2503.10719v2 | Long-Video Audio Synthesis with Multi-Agent Collaboration | 提出多智能体框架模拟专业配音流程，含场景分割与脚本生成 | 解决长视频音频合成中的语义动态 shifts 与时间对齐问题 | 长视频音频合成 |
| 25 | http://arxiv.org/abs/2503.10200v5 | LVAgent: Long Video Understanding by Multi-Round Dynamical Collaboration of MLLM Agents | 首创多轮动态协作 MLLM 代理框架，含选择、感知、行动、反思 | 解决单一 MLLM 对长视频时序上下文建模理解有限的问题 | 长视频理解 |
| 26 | http://arxiv.org/abs/2503.11290v3 | EmoAgent: A Multi-Agent Framework for Diverse Affective Image Manipulation | 提出规划、编辑、评论三阶段协作代理，建模一对多情感映射 | 解决现有情感图像操纵方法依赖刚性一对一映射的问题 | 情感图像操纵 |
| 27 | http://arxiv.org/abs/2503.12029v1 | Is Multi-Agent Debate (MAD) the Silver Bullet? An Empirical Analysis of MAD in Code Summarization and Translation | 实证分析 MAD 在代码总结与翻译中的有效性，提出两项增强 | 解决复杂任务需要多样 expertise 及多步推理的 LLM 能力不足问题 | 软件工程代码任务 |
| 28 | http://arxiv.org/abs/2503.12333v1 | GameChat: Multi-LLM Dialogue for Safe, Agile, and Socially Optimal Multi-Agent Navigation in Constrained Environments | 使用自然语言通信解决冲突，实现社会最优的多机器人导航 | 去中心化设置中自利代理的空间对称冲突 | 多机器人导航 |
| 29 | http://arxiv.org/abs/2503.12722v1 | Identifying Cooperative Personalities in Multi-agent Contexts through Personality Steering with Representation Engineering | 利用表示工程 steering 大五人格特质，分析对合作的影响 | LLM 在多智能体设置中协调困难，导致次优结果 | 多智能体协作 |
| 30 | http://arxiv.org/abs/2503.12757v2 | MAP: Multi-user Personalization with Collaborative LLM-powered Agents | 多智能体系统实现多用户个性化，通过代理间交互解决冲突 | 多用户设置中 diverse 偏好与冲突指令的协调 | 多用户个性化 |
| 31 | http://arxiv.org/abs/2503.13577v1 | When Should We Orchestrate Multiple Agents? | 设计框架在现实条件下编排智能体，理论证明编排有效性条件 | 编排策略常高估性能低估成本，缺乏现实条件框架 | 多智能体编排 |
| 32 | http://arxiv.org/abs/2503.13415v1 | A Comprehensive Survey on Multi-Agent Cooperative Decision-Making: Scenarios, Approaches, Challenges and Perspectives | 全面调查多智能体协作决策仿真环境与主流智能决策方法 | 缺乏对多智能体协作决策场景与方法的系统性综述 | 多智能体协作决策 |
| 33 | http://arxiv.org/abs/2503.20666v1 | TAMA: A Human-AI Collaborative Thematic Analysis Framework Using Multi-Agent LLMs for Clinical Interviews | 多Agent LLM协作框架实现人机协同主题分析 | 临床访谈主题分析资源密集、效率低的问题 | 临床医疗访谈分析 |
| 34 | http://arxiv.org/abs/2503.20772v3 | Welfare and Cost Aggregation for Multi-Agent Control: When to Choose Which Social Cost Function, and Why? | 基于社会选择理论指导多Agent社会成本函数选择 | 多Agent系统中社会成本函数选择缺乏理论依据 | 能源/水资源/交通管理 |
| 35 | http://arxiv.org/abs/2503.21720v1 | Collab: Controlled Decoding using Mixture of Agents for LLM Alignment | 多Agent混合解码策略实现推理时对齐全 | RLHF计算成本高，单Agent解码适应性差 | LLM对齐 |
| 36 | http://arxiv.org/abs/2503.22038v1 | Debate-Driven Multi-Agent LLMs for Phishing Email Detection | 多Agent辩论机制模拟论证提升钓鱼邮件检测 | 传统检测方法依赖预定义模式或大数据集训练 | 钓鱼邮件检测 |
| 37 | http://arxiv.org/abs/2503.22473v1 | WorkTeam: Constructing Workflows from Natural Language with Multi-Agents | 三Agent协作框架从自然语言构建工作流 | 单LLM Agent在复杂任务上性能下降的问题 | 企业工作流构建 |
| 38 | http://arxiv.org/abs/2503.22512v4 | Unlocking LLM Repair Capabilities Through Cross-Language Translation and Multi-Agent Refinement | 跨语言翻译配合多Agent迭代修复范式 | LLM在冷门编程语言上修复能力不足的问题 | 多语言程序修复 |
| 39 | http://arxiv.org/abs/2503.23138v1 | EncGPT: A Multi-Agent Workflow for Dynamic Encryption Algorithms | 规则/加密/解密三Agent动态生成和应用加密规则 | 现有加密算法难以平衡成本和安全性的问题 | 通信加密 |
| 40 | http://arxiv.org/abs/2503.17671v2 | ComfyGPT: A Self-Optimizing Multi-Agent System for Comprehensive ComfyUI Workflow Generation | 四智能体协作系统，强化学习优化工作流生成 | ComfyUI 节点连接复杂，用户管理困难 | ComfyUI 工作流生成 |
| 41 | http://arxiv.org/abs/2503.18132v2 | MathAgent: Leveraging a Mixture-of-Math-Agent Framework for Real-World Multimodal Mathematical Error Detection | 混合数学 Agent 框架，三阶段 specialized agents 协作 | 多模态数学内容中学生错误识别与分类难 | K-12 教育数学错误检测 |
| 42 | http://arxiv.org/abs/2503.18589v2 | Unified Uncertainty-Aware Diffusion for Multi-Agent Trajectory Modeling | 统一扩散模型处理轨迹完成，提供状态级不确定性估计 | 多智能体轨迹建模忽略不确定性及轨迹完成任务 | 体育数据集轨迹预测 |
| 43 | http://arxiv.org/abs/2503.18891v1 | AgentDropout: Dynamic Agent Elimination for Token-Efficient and High-Performance LLM-Based Multi-Agent Collaboration | 动态消除冗余 Agent 与通信，优化通信图邻接矩阵 | 多智能体系统通信效率低，任务性能次优 | LLM 多智能体协作 |
| 44 | http://arxiv.org/abs/2503.19391v1 | TraF-Align: Trajectory-aware Feature Alignment for Asynchronous Multi-agent Perception | 学习特征流路径，预测物体特征级轨迹对齐 | 合作感知中代理间延迟导致空间语义特征未对齐 | 异步合作感知 (V2X) |
| 45 | http://arxiv.org/abs/2503.23170v1 | AstroAgents: A Multi-Agent AI for Hypothesis Generation from Mass Spectrometry Data | 八 agent 协作系统，结合数据分析师与领域科学家 agent 生成假设 | 质谱数据复杂且存在污染，难以交叉匹配 prior studies 生成假设 | 天体生物学与质谱数据分析 |
| 46 | http://arxiv.org/abs/2503.23314v2 | SPIO: Ensemble and Selective Strategies via LLM-Based Multi-Agent Planning in Automated Data Science | 替换刚性工作流为自适应多路径规划，集成优化 agent | 自动化数据科学工作流刚性导致探索受限、结果次优 | 自动化数据科学与机器学习流程 |
| 47 | http://arxiv.org/abs/2503.23315v1 | AI Agents in Engineering Design: A Multi-Agent Framework for Aesthetic and Aerodynamic Car Design | 集成 AI 设计 agent 到传统工程流程，自动化 sketch 与仿真 | 传统汽车设计流程耗时久，手动任务效率低 | 汽车工程设计与空气动力学模拟 |
| 48 | http://arxiv.org/abs/2503.23329v2 | A Multi-Agent Framework with Automated Decision Rule Optimization for Cross-Domain Misinformation Detection | 多专家 agent 分析新闻，自动优化跨域决策规则 | 跨域虚假信息检测泛化性差，依赖人工规则 | 跨领域虚假信息检测 |
| 49 | http://arxiv.org/abs/2503.23427v3 | CoRanking: Collaborative Ranking with Small and Large Ranking Agents | 小模型预排序结合大模型重排序，引入顺序调整器 | 大模型列表排序效率低且存在位置偏差 | 信息检索与文档排序 |
| 50 | http://arxiv.org/abs/2503.23781v3 | DebFlow: Automating Agent Creation via Agent Debate | 利用辩论机制优化工作流，集成反思改进经验 | 现有工作流自动生成推理能力有限，资源消耗高 | 自动化 Agent 创建与工作流优化 |

[返回目录](#目录)

<a id="cat-05"></a>

## 具身智能Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2503.07323v2 | Navigating Motion Agents in Dynamic and Cluttered Environments through LLM Reasoning | 无需训练的LLM空间推理多Agent导航框架 | 动态杂乱环境中多Agent自主导航受限 | 室内平面图等多Agent导航场景 |
| 2 | http://arxiv.org/abs/2503.08302v1 | General-Purpose Aerial Intelligent Agents Empowered by Large Language Models | 首个LLM推理与机器人自主紧密集成的空中Agent | 无人机系统因软硬件协同设计挑战限于预定义任务 | 甘蔗监测、电网巡检等开放环境任务 |
| 3 | http://arxiv.org/abs/2503.08306v4 | Reasoning in visual navigation of end-to-end trained agents: a dynamical systems approach | 真实机器人大规模实验分析端到端Agent推理行为 | 基准仍以仿真为主、真实机器人细粒度行为研究少 | 真实环境中的视觉导航Agent |
| 4 | http://arxiv.org/abs/2503.09035v1 | ManeuverGPT Agentic Control for Safe Autonomous Stunt Maneuvers | 三Agent架构生成执行高动态特技机动 | 下一代主动安全功能需执行规避危险机动 | 自动驾驶车辆高敏捷性运动控制 |
| 5 | http://arxiv.org/abs/2503.00729v1 | CLEA: Closed-Loop Embodied Agent for Enhancing Task Execution in Dynamic Environments | 闭环架构结合任务规划与执行批评机制 | 动态环境中长期任务执行可靠性低 | 机器人具身任务执行 |
| 6 | http://arxiv.org/abs/2503.03196v2 | SpiritSight Agent: Advanced GUI Agent with One Look | 多级别数据集与通用块解析方法 | 解决视觉 GUI 代理元素定位精度低问题 | 跨平台 GUI 导航任务 |
| 7 | http://arxiv.org/abs/2503.06791v2 | AutoMisty: A Multi-Agent LLM Framework for Automated Code Generation in the Misty Social Robot | 引入多智能体协作框架，从自然语言生成机器人代码 | 解决社交机器人 API 对无编程经验用户不可访问问题 | Misty 社交机器人 |
| 8 | http://arxiv.org/abs/2503.16545v1 | EmpathyAgent: Can Embodied Agents Conduct Empathetic Actions? | 首个具身Agent共情行为评估基准，1万多模态样本 | 具身Agent共情能力评估缺失 | 具身智能/人机交互 |
| 9 | http://arxiv.org/abs/2503.16394v1 | Do Visual Imaginations Improve Vision-and-Language Navigation Agents? | 文本到图像扩散模型合成子目标视觉表征 | VLN Agent仅依赖语言指令理解不足 | 视觉语言导航 |
| 10 | http://arxiv.org/abs/2503.16408v1 | RoboFactory: Exploring Embodied Agent Collaboration with Compositional Constraints | 组合约束概念+自动化数据收集框架 | 具身多Agent系统训练数据生成困难 | 机器人协作/多Agent操作 |
| 11 | http://arxiv.org/abs/2503.16711v3 | Depth Matters: Multimodal RGB-D Perception for Robust Autonomous Agents | RGB+深度信息早期融合增强转向命令预测 | 纯RGB感知自主Agent鲁棒性不足 | 自动驾驶/机器人控制 |
| 12 | http://arxiv.org/abs/2503.09758v1 | Multi-Agent LLM Actor-Critic Framework for Social Robot Navigation | 提出去中心化多智能体 LLM 演员 - 评论家框架，平衡局部自主与全局监督 | 解决机器人在人类环境中导航的适应性与社会合规性问题 | 社会机器人导航 |
| 13 | http://arxiv.org/abs/2503.10628v1 | Uncertainty in Action: Confidence Elicitation in Embodied Agents | 提出 elicitation 与 execution 策略，结构化评估具身代理信心 | 解决动态多模态环境中具身代理表达信心与校准不确定性的挑战 | 具身智能体信心评估 |
| 14 | http://arxiv.org/abs/2503.11170v1 | DeskVision: Large Scale Desktop Region Captioning for Advanced GUI Agents | 提出 AutoCaptioner  pipeline 生成大规模桌面 GUI 数据集 DeskVision | 解决 GUI 数据限制阻碍桌面/电脑使用场景代理发展的问题 | 桌面 GUI 代理 |
| 15 | http://arxiv.org/abs/2503.12533v2 | Being-0: A Humanoid Robotic Agent with Vision-Language Models and Modular Skills | 分层智能体框架，集成基础模型与模块化技能库 | 长 horizon 任务中组件直接结合导致的鲁棒性差 | 人形机器人 |
| 16 | http://arxiv.org/abs/2503.22122v1 | REMAC: Self-Reflective and Self-Evolving Multi-Agent Collaboration for Long-Horizon Robot Manipulation | 自反思和自进化模块实现场景无关的多机器人规划 | 长视野机器人任务适应性和效率不足问题 | 长视野机器人操作 |
| 17 | http://arxiv.org/abs/2503.17703v2 | RAIDER: Tool-Equipped Large Language Model Agent for Robotic Action Issue Detection, Explanation and Recovery | 集成 LLM 与接地工具，动态生成上下文感知问题 | 机器人动作问题检测、解释与恢复能力不足 | 机器人动作_issue_检测与恢复 |
| 18 | http://arxiv.org/abs/2503.23601v1 | Exploring GPT-4 for Robotic Agent Strategy with Real-Time State Feedback and a Reactive Behaviour Framework | GPT-4 驱动机器人行为，结合实时状态反馈与反应框架 | 大模型生成任务可执行性差，缺乏安全与状态反馈 | 人形机器人任务规划与控制 |
| 19 | http://arxiv.org/abs/2503.24110v2 | Grounding Agent Reasoning in Image Schemas: A Neurosymbolic Approach to Embodied Cognition | 利用 image schemas 形式化表征，连接具身认知与 agent 系统 | 代理推理难捕捉人类基本概念结构，交互不直观 | 具身认知与神经符号系统 |

[返回目录](#目录)

<a id="cat-06"></a>

## Agent仿真与社会模拟

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2503.07364v1 | Artificial Utopia: Simulation and Intelligent Agents for a Democratised Future | 用AI仿真测试政治经济政策的"人工乌托邦"研究议程 | 自上而下系统难以应对21世纪挑战 | 公民大会、民主企业等制度仿真 |
| 2 | http://arxiv.org/abs/2503.09639v4 | Can A Society of Generative Agents Simulate Human Behavior and Inform Public Health Policy? A Case Study on Vaccine Hesitancy | 100个生成Agent模拟疫苗犹豫的社会仿真框架 | 减少真实人类试验依赖评估公共政策 | 疫苗犹豫等公共卫生政策仿真 |
| 3 | http://arxiv.org/abs/2503.03800v1 | Multi-Agent Systems Powered by Large Language Models: Applications in Swarm Intelligence | 将 LLM 集成到 NetLogo 模拟平台，替换硬编码程序 | 解决传统 swarm 智能模拟缺乏自适应行为生成的问题 | 蚁群觅食与鸟群飞行模拟 |
| 4 | http://arxiv.org/abs/2503.08709v1 | Simulating Influence Dynamics with LLM Agents | 集成意见动力学原则与 LLM，模拟社会网络影响 | 解决研究社会现象无需 extensive 编码 expertise 的问题 | 社会科学与心理学研究 |
| 5 | http://arxiv.org/abs/2503.14620v1 | Retrieval-Augmented Simulacra: Generative Agents for Up-to-date and Knowledge-Adaptive Simulations | 搜索扩展生成机制模拟人类搜索行为 | SNS虚拟环境中Agent发帖回复自然度 | 社交网络行为仿真 |
| 6 | http://arxiv.org/abs/2504.07112v4 | Are AI Agents interacting with Online Ads? | 分析AI Agent与在线广告交互模式与决策策略 | AI主导数字环境中广告设计策略 | 在线广告/旅行酒店预订 |
| 7 | http://arxiv.org/abs/2503.16021v4 | Imitating AI agents increase diversity in homogeneous information environments but can reduce it in heterogeneous ones | 大规模仿真框架分析AI模仿对信息环境影响 | AI模仿对民主信息环境的系统级影响 | 新闻环境/信息多样性 |
| 8 | http://arxiv.org/abs/2503.10796v1 | Design and Analysis of an Extreme-Scale, High-Performance, and Modular Agent-Based Simulation Platform | 引入 BioDynaMo 及 TeraAgent，实现十亿级智能体分布式仿真 | 解决现有仿真平台性能低及模块化差导致的大规模模拟限制 | 大规模智能体仿真 |
| 9 | http://arxiv.org/abs/2503.11452v2 | Deep Learning Agents Trained For Avoidance Behave Like Hawks And Doves | 分析深度学习和避行为代理在对称网格世界中的策略演化 | 解决理解深度学习代理在简单避免游戏中启发式最优策略的问题 | 博弈行为模拟 |
| 10 | http://arxiv.org/abs/2503.12731v1 | Navigating Heat Exposure: Simulation of Route Planning Based on Visual Language Model Agents | 提出 VLM 驱动的 PPPM 框架，模拟热适应性行人路由 | 现有方法未考虑热应激下的个体生理变异与环境感知 | 城市气候适应规划 |
| 11 | http://arxiv.org/abs/2503.13356v1 | Agents Play Thousands of 3D Video Games | 提出 PORTAL 框架，通过语言引导策略生成玩 3D 游戏 | 传统强化学习方法计算负担重，缺乏战略深度 | 游戏 AI 开发 |
| 12 | http://arxiv.org/abs/2503.13402v1 | Toward Generative 6G Simulation: An Experimental Multi-Agent LLM and ns-3 Integration | 结合多智能体框架与 ns-3，自动化生成与调试 5G 网络场景 | 6G 网络缺乏全栈仿真环境评估复杂技术发展 | 6G 网络仿真 |
| 13 | http://arxiv.org/abs/2503.22726v1 | InfoBid: A Simulation Framework for Studying Information Disclosure in Auctions with Large Language Model-based Agents | 首个集成LLM智能体研究拍卖信息不对称的仿真框架 | 信息披露策略对拍卖效率和收益的权衡问题 | 在线广告拍卖系统 |
| 14 | http://arxiv.org/abs/2503.20665v1 | Agent-Based Analysis of the Impact of Near Real-Time Data and Smart Balancing on the Frequency Stability of Power Systems | 多Agent蒙特卡洛仿真分析智能平衡对电网频率影响 | 近实时数据发布对电力系统频率稳定性的影响 | 电力系统/电网管理 |
| 15 | http://arxiv.org/abs/2503.22678v2 | Self-Evolving Multi-Agent Simulations for Realistic Clinical Interactions | MedAgentSim仿真环境支持医生-患者-测量三Agent动态诊断 | 现有方法缺乏多轮对话和主动检查请求的真实诊断流程 | 临床诊断交互 |
| 16 | http://arxiv.org/abs/2504.08742v1 | Simulating Filter Bubble on Short-video Recommender System with Large Language Model Agents | LLM 模拟用户 - 推荐交互，揭示过滤泡形成机制 | 短视频推荐系统中过滤泡形成 dynamics 不明 | 短视频推荐系统仿真 |
| 17 | http://arxiv.org/abs/2503.18389v1 | Agent-based Modeling meets the Capability Approach for Human Development: Simulating Homelessness Policy-making | 结合能力方法与 ABM/RL，评估政策扩展能力 | 无家可归者政策制定缺乏非侵入式评估框架 | 无家可归者政策模拟 |
| 18 | http://arxiv.org/abs/2503.22718v1 | LLM-ABM for Transportation: Assessing the Potential of LLM Agents in System Analysis | 集成 LLM 代理进入交通系统仿真，评估系统动态 | 传统交通 ABM 依赖数学模型，理论与实际受限 | 交通规划与系统分析 |
| 19 | http://arxiv.org/abs/2503.22719v1 | LLM-based Agent Simulation for Maternal Health Interventions: Uncertainty Estimation and Decision-focused Evaluation | LLM 驱动仿真预测受益人行为，提出不确定性估计方法 | 数据稀缺 healthcare 设置中传统 ABM 需大量领域知识 | 孕产妇健康干预模拟 |
| 20 | http://arxiv.org/abs/2503.23147v1 | Agent-Based Modeling and Deep Neural Networks for Establishing Digital Twins of Secure Facilities under Sensing Restrictions | 结合 ABM 与 DNN 生成合成轨迹，训练 VR 环境 NPC 行为 | 高安全设施无法部署传感器收集人类活动数据 | 核设施数字孪生与内部威胁模拟 |
| 21 | http://arxiv.org/abs/2503.23631v2 | Intrinsically-Motivated Humans and Agents in Open-World Exploration | 比较人类与 agent 在开放世界探索中的内在动机差异 | 人类与 agent 探索行为存在差距，动机设计不明 | 开放世界探索与内在奖励设计 |
| 22 | http://arxiv.org/abs/2503.24199v2 | Agent-Based Simulations of Online Political Discussions: A Case Study on Elections in Germany | 结合历史上下文与动机约束，模拟用户政治讨论交互 | 社交媒体用户 engagement 受历史与奖励驱动复杂 | 在线政治讨论与社会模拟 |
| 23 | http://arxiv.org/abs/2503.24228v1 | PAARS: Persona Aligned Agentic Retail Shoppers | 挖掘 persona 创建购物 agent，群体 level 对齐人类行为 | LLM 存在偏差，需合成 agent 群体近似真实人类 | 电商行为模拟与 A/B 测试 |

[返回目录](#目录)

<a id="cat-07"></a>

## 多Agent强化学习

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2503.07397v1 | Q-MARL: A quantum-inspired algorithm using neural消息传递 for large-scale multi-agent reinforcement learning | 量子启发的去中心化神经消息传递架构 | 大规模多Agent强化学习扩展性差 | 数千Agent协作/竞争场景 |
| 2 | http://arxiv.org/abs/2503.08493v1 | Hierarchical Multi Agent DRL for Soft Handovers Between Edge Clouds in Open RAN | 分层多Agent强化学习动态确定功能分割配置 | 过渡用户边缘云间无缝服务连续性挑战 | 开放无线接入网络中的边缘云切换 |
| 3 | http://arxiv.org/abs/2503.09309v2 | Steering No-Regret Agents in MFGs under Model Uncertainty | 模型不确定性下平均场博弈的引导奖励设计 | 大群体和模型不确定性场景适用性有限 | 大群体系统中的Agent行为引导 |
| 4 | http://arxiv.org/abs/2503.00372v1 | Nucleolus Credit Assignment for Effective Coalitions in Multi-agent Reinforcement Learning | 基于核仁理论的信用分配，自动划分子联盟 | 解决大任务中单联盟性能次优问题 | 复杂复合任务的多智能体协作 |
| 5 | http://arxiv.org/abs/2503.00684v1 | Factorized Deep Q-Network for Cooperative Multi-Agent Reinforcement Learning in Victim Tagging | 使用因子化深 Q 网络优化受害者标记时间 | 大规模伤亡事件中快速自适应决策 | 紧急医疗响应多智能体系统 |
| 6 | http://arxiv.org/abs/2503.01017v1 | Real-World Deployment and Assessment of a Multi-Agent Reinforcement Learning-Based Variable Speed Limit Control System | 首个 MARL 可变限速系统实地部署 | 提升交通流警告准确率与响应速度 | 高速公路交通控制 |
| 7 | http://arxiv.org/abs/2503.01069v1 | Multi-Agent Reinforcement Learning with Long-Term Performance Objectives for Service Workforce Optimization | 构建统一劳动力优化模拟器支持 MARL | 解决子问题独立假设不符合现实场景 | 服务 workforce 优化 |
| 8 | http://arxiv.org/abs/2503.01440v1 | Trajectory-Class-Aware Multi-Agent Reinforcement Learning | 识别轨迹类别辅助策略泛化 | 解决多任务场景下策略泛化挑战 | 多任务多智能体强化学习 |
| 9 | http://arxiv.org/abs/2503.01458v1 | SrSv: Integrating Sequential Rollouts with Sequential Value Estimation for Multi-agent Reinforcement Learning | 序列展开与序列价值估计框架 | 解决大规模场景信用分配与可扩展性 | 大规模协作多智能体系统 |
| 10 | http://arxiv.org/abs/2503.02077v3 | M3HF: Multi-agent Reinforcement Learning from Multi-phase Human Feedback of Mixed Quality | 整合多阶段混合质量人类反馈 | 解决复杂协调环境中奖励函数设计难 | 多智能体强化学习训练 |
| 11 | http://arxiv.org/abs/2503.02189v4 | Adaptive Traffic Signal Control based on Multi-Agent Reinforcement Learning. Case Study on a simulated real-world corridor | 多智能体 PPO 算法实现自适应信号控制 | 提升真实世界走廊交通信号控制性能 | 城市交通信号控制 |
| 12 | http://arxiv.org/abs/2503.05805v3 | Multi-agent Auto-Bidding with Latent Graph Diffusion Models | 结合图嵌入与潜扩散模型优化竞价策略 | 大规模拍卖环境下动态优化竞价策略 | 广告自动竞价系统 |
| 13 | http://arxiv.org/abs/2503.02437v2 | Decentralized Reinforcement Learning for Multi-Agent Multi-Resource Allocation via Dynamic Cluster Agreements | 动态集群共识机制减少全局信息依赖 | 去中心化 heterogeneous 资源分配挑战 | 多智能体资源分配 |
| 14 | http://arxiv.org/abs/2503.02693v1 | Federated Learning for Privacy-Preserving Feedforward Control in Multi-Agent Systems | 联邦学习集成至前馈控制保护隐私 | 解决多智能体数据收集隐私与通信成本 | 自动驾驶多智能体控制 |
| 15 | http://arxiv.org/abs/2503.02992v2 | RAILGUN: A Unified Convolutional Policy for Multi-Agent Path Finding Across Different Environments and Tasks | 首个基于 CNN 的集中式学习策略 | 解决学习式 MAPF 泛化性与 agent 数量可变 | 多智能体路径规划 |
| 16 | http://arxiv.org/abs/2503.03391v1 | Multi-Agent DRL for Queue-Aware Task Offloading in Hierarchical MEC-Enabled Air-Ground Networks | 提出 MAPPO-BD 算法优化无人机轨迹与任务卸载决策 | 解决空地面网络中能源最小化与队列延迟约束问题 | 6G 移动边缘计算网络 |
| 17 | http://arxiv.org/abs/2503.03796v2 | Human Implicit Preference-Based Policy Fine-tuning for Multi-Agent Reinforcement Learning in USV Swarm | 提出基于人类反馈的 MARL 方法，解决信用分配挑战 | 解决专家直觉难以编码进奖励函数的问题 | 无人水面艇集群 |
| 18 | http://arxiv.org/abs/2503.04679v1 | Multi-Agent Inverse Q-Learning from Demonstrations | 提出 MAMQL 框架，学习边缘化批评家以平衡目标 | 解决多 agent 环境中奖励指定错误及目标不一致问题 | 多智能体逆强化学习 |
| 19 | http://arxiv.org/abs/2503.05970v3 | Partially Decentralized Multi-Agent Q-Learning via Digital Cousins for Wireless Networks | 提出 M-MEMQ，利用数字孪生环境优化分布式无线网络 | 解决大状态空间及全局信息不可访问的挑战 | 无线通信网络优化 |
| 20 | http://arxiv.org/abs/2503.07662v1 | HIPPO-MAT: Decentralized Task Allocation Using GraphSAGE and Multi-Agent Deep Reinforcement Learning | 集成 GNN 与 IPPO，实现去中心化任务分配 | 解决异构多智能体系统中连续任务分配问题 | 无人机与地面车辆集群 |
| 21 | http://arxiv.org/abs/2503.06747v1 | Fully-Decentralized MADDPG with Networked Agents | 适应 MADDPG 应用网络化通信，去中心化训练 | 解决多 agent 强化学习中计算成本高的问题 | 合作/对抗多智能体系统 |
| 22 | http://arxiv.org/abs/2503.14576v3 | SocialJax: An Evaluation Suite for Multi-agent Reinforcement Learning in Sequential Social Dilemmas | JAX实现的社会困境多Agent评估套件，50倍加速 | 多Agent强化学习评估计算资源消耗大 | 多Agent强化学习研究 |
| 23 | http://arxiv.org/abs/2503.15172v1 | Multi-Agent Actor-Critic with Harmonic Annealing Pruning for Dynamic Spectrum Access Systems | 谐波退火稀疏调度器+渐进神经网络剪枝 | 边缘设备部署MADRL计算成本高 | 动态频谱访问/边缘计算 |
| 24 | http://arxiv.org/abs/2503.15703v2 | Predicting Multi-Agent Specialization via Task Parallelizability | 基于任务并行性的专业化预测闭式边界 | 多Agent系统何时鼓励专业化vs通才 | 多Agent强化学习策略设计 |
| 25 | http://arxiv.org/abs/2503.15947v1 | Unreal-MAP: Unreal-Engine-Based General Platform for Multi-Agent Reinforcement Learning | 基于虚幻引擎的MARL通用平台，用户友好 | MARL算法与自定义任务整合困难 | 多Agent强化学习研究 |
| 26 | http://arxiv.org/abs/2503.09755v1 | Distributionally Robust Multi-Agent Reinforcement Learning for Dynamic Chute Mapping | 提出分布鲁棒多智能体强化学习框架，增强策略对诱导率变化的韧性 | 解决动态包裹诱导率不确定导致的分拣效率低问题 | 亚马逊机器人仓库分拣 |
| 27 | http://arxiv.org/abs/2503.10049v1 | Enhancing Multi-Agent Systems via Reinforcement Learning with LLM-based Planner and Graph-based Policy | 结合 LLM 规划器与基于图的协作元策略，实现高效多智能体协作 | 解决 MARL 处理复杂任务难及奖励函数设计难的问题 | 复杂任务多智能体系统 |
| 28 | http://arxiv.org/abs/2503.10186v2 | Convergence and Connectivity: Dynamics of Multi-Agent Q-Learning in Random Networks | 研究随机网络中多智能体 Q 学习动态，建立收敛充分条件 | 解决多智能体学习算法随数量增加难以收敛至均衡的问题 | 随机网络多智能体学习 |
| 29 | http://arxiv.org/abs/2503.10907v1 | H2-MARL: Multi-Agent Reinforcement Learning for Pareto Optimality in Hospital Capacity Strain and Human Mobility during Epidemic | 设计乡镇级感染模型与双目标奖励，实现医院容量与 mobility 帕累托最优 | 解决 epidemic 控制中医院容量 strain 与 mobility 限制平衡问题 | 流行病控制与城市管理 |
| 30 | http://arxiv.org/abs/2503.11726v1 | SPECTra: Scalable Multi-Agent Reinforcement Learning with Permutation-Free Networks | 提出新型代理网络与非线性混合网络，确保置换等价与可扩展性 | 解决 MARL 中状态空间指数增长及架构固定限制可变数量实体问题 | cooperative MARL |
| 31 | http://arxiv.org/abs/2503.11829v2 | Learning Closed-Loop Parametric Nash Equilibria of Multi-Agent Collaborative Field Coverage | 证明协作场覆盖问题可公式化为 Markov Potential Game | 解决多智能体 RL 非平稳性及耦合性导致的训练慢问题 | 多智能体协作场覆盖 |
| 32 | http://arxiv.org/abs/2503.13077v1 | Towards Better Sample Efficiency in Multi-Agent Reinforcement Learning via Exploration | 提出自监督内在奖励与随机网络蒸馏，提高采样效率 | 多智能体强化学习训练时间过长，采样效率低 | 多智能体强化学习 |
| 33 | http://arxiv.org/abs/2503.14555v1 | A Generalist Hanabi Agent | 提出 R3D2 通用智能体， reformulate 任务为文本，处理动态空间 | 传统 MARL 系统无法与不熟悉合作者协作或泛化 | 合作卡牌游戏 Hanabi |
| 34 | http://arxiv.org/abs/2503.20462v1 | Multi-agent Uncertainty-Aware Pessimistic Model-Based Reinforcement Learning for Connected Autonomous Vehicles | 提出MA-PMBRL框架，结合悲观优化与PAC保证 | 多智能体MBRL不确定性估计和策略可靠性问题 | 联网自动驾驶车辆 |
| 35 | http://arxiv.org/abs/2503.20507v3 | Harmonia: A Multi-Agent Reinforcement Learning Approach to Data Placement and Migration in Hybrid Storage Systems | 双Agent协同优化数据放置和迁移策略 | 混合存储系统中数据管理策略次优问题 | 混合存储系统 |
| 36 | http://arxiv.org/abs/2503.20688v1 | Graph-Enhanced Model-Free Reinforcement Learning Agents for Efficient Power Grid Topological Control | 图增强无模型RL优化电网拓扑控制 | 电网管理复杂性增加，需确保稳定性和效率 | 电力电网拓扑控制 |
| 37 | http://arxiv.org/abs/2503.21200v1 | Learning Generalizable Skills from Offline Multi-Task Data for Multi-Agent Cooperation | HiSSD分层框架联合学习通用和任务特定技能 | 离线多任务MARL技能泛化到未见任务的问题 | 多Agent协作任务 |
| 38 | http://arxiv.org/abs/2503.22162v1 | Cooperative Hybrid Multi-Agent Pathfinding Based on Shared Exploration Maps | 混合框架集成D*Lite全局搜索与多Agent强化学习 | 动态环境中标准集中规划或纯RL难以兼顾质量和灵活性 | 多机器人/仓储物流 |
| 39 | http://arxiv.org/abs/2503.22779v3 | Policy Optimization and Multi-agent Reinforcement Learning for Mean-variance Team Stochastic Games | 提出MV-MAPI和MV-MATRPO算法解决均值方差团队博弈 | 方差度量非加和非马尔可夫，多Agent同时更新导致非平稳 | 多微电网能源管理 |
| 40 | http://arxiv.org/abs/2503.22867v2 | Markov Potential Game Construction and Multi-Agent Reinforcement Learning with Applications to Autonomous Driving | 提供MG构建为MPG的充分条件，保证纯NE存在和收敛 | 一般和MG中寻求纳什均衡非常困难 | 自动驾驶 |
| 41 | http://arxiv.org/abs/2503.22958v3 | Late Breaking Results: Breaking Symmetry- Unconventional Placement of Analog Circuits using Multi-Level Multi-Agent Reinforcement Learning | 首个多Agent RL应用于模拟电路布局自动化 | 传统对称放置方法因LDE非线性效应性能不足 | 模拟电路布局设计 |
| 42 | http://arxiv.org/abs/2503.17803v1 | A Roadmap Towards Improving Multi-Agent Reinforcement Learning With Causal Discovery And Inference | 探索因果推理在 MARL 中的应用机会与挑战 | MARL 中因果推理应用尚未充分探索 | 多智能体强化学习研究 |
| 43 | http://arxiv.org/abs/2503.18201v1 | Iterative Multi-Agent Reinforcement Learning: A Novel Approach Toward Real-World Multi-Echelon Inventory Optimization | 迭代多智能体强化学习 (IMARL)，提升可扩展性 | 多级库存优化复杂性高，DRL 受维度灾难限制 | 供应链多级库存优化 |
| 44 | http://arxiv.org/abs/2503.18816v2 | Learning Multi-Robot Coordination through Locality-Based Factorized Multi-Agent Actor-Critic Algorithm | 基于局部性的因子化多智能体 Actor-Critic 算法 | 全局奖励信息无法准确反映去中心化系统中个体动作质量 | 多机器人协调学习 |
| 45 | http://arxiv.org/abs/2503.21807v1 | LERO: LLM-driven Evolutionary framework with Hybrid Rewards and Enhanced Observation for Multi-Agent Reinforcement Learning | LLM 驱动进化框架，混合奖励与增强观测解决 MARL 瓶颈 | MARL 中信用分配与部分可观测性关键瓶颈 | 多智能体粒子环境 |
| 46 | http://arxiv.org/abs/2503.19418v1 | Multi-Agent Deep Reinforcement Learning for Safe Autonomous Driving with RICS-Assisted MEC | 驾驶安全启用多智能体 DRL，利用 RICS  mitigating 干扰 | 传统算法假设准静态信道，动态环境适应差 | 安全自动驾驶网络 |
| 47 | http://arxiv.org/abs/2503.23218v2 | Multi-Agent Reinforcement Learning for Graph Discovery in D2D-Enabled Federated Learning | 去中心化 RL 发现 D2D 图，促进关键数据点通信 | 联邦学习中数据隐私与通信效率的平衡问题 | 设备到设备 federated learning 网络 |
| 48 | http://arxiv.org/abs/2503.23290v1 | Efficient Twin Migration in Vehicular Metaverses: Multi-Agent Split Deep Reinforcement Learning with Spatio-Temporal Trajectory Generation | 多 agent 分割 DRL 框架结合时空轨迹生成，优化迁移决策 | 车辆快速移动导致数字孪生迁移延迟高、资源异构 | 车载元宇宙与车辆数字孪生 |
| 49 | http://arxiv.org/abs/2503.23615v1 | An Organizationally-Oriented Approach to Enhancing Explainability and Control in Multi-Agent Reinforcement Learning | 引入组织角色与目标到 MARL，增强行为可解释性 | MARL 个体行为难解释，缺乏组织层面控制 | 多 agent 强化学习与组织行为模拟 |
| 50 | http://arxiv.org/abs/2503.23626v1 | A Constrained Multi-Agent Reinforcement Learning Approach to Autonomous Traffic Signal Control | 提出 MAPPO-LCE 算法，整合拉格朗日乘子平衡奖励与约束 | 传统交通信号控制无法适应动态模式，缺乏约束 | 城市交通信号自适应控制 |
| 51 | http://arxiv.org/abs/2503.23669v2 | Multi-Agent Deep Reinforcement Learning for Optimized Multi-UAV Coverage and Power-Efficient UE Connectivity | 多 UAV 部署最大化覆盖，MADDPG 优化功率分配 | 灾难等场景下网络覆盖不足，干扰严重 | 无人机通信网络覆盖优化 |
| 52 | http://arxiv.org/abs/2503.24296v1 | Fair Dynamic Spectrum Access via Fully Decentralized Multi-Agent Reinforcement Learning | 提出 FSRL 方案，结合风险控制与公平奖励结构 | 去中心化无线网络频谱接入缺乏公平性协调 | 动态频谱接入与无线网络 |

[返回目录](#目录)

<a id="cat-08"></a>

## Agent学习与自进化

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2503.07693v1 | Fully Autonomous Programming using Iterative Multi-Agent Debugging with Large Language Models | SEIDR多Agent调试框架克服"差一点"综合征 | LLM生成代码接近正确但因小错误失败 | 程序合成与自动调试 |
| 2 | http://arxiv.org/abs/2503.09501v3 | ReMA: Learning to Meta-think for LLMs with Multi-Agent Reinforcement Learning | 分层元思考Agent和推理Agent的多Agent强化学习 | 单Agent工作缺乏获取元思考的专门设计 | 复杂推理任务中的LLM元思考能力 |
| 3 | http://arxiv.org/abs/2503.01490v1 | Improving Retrospective Language Agents via Joint Policy Gradient Optimization | 联合优化任务规划与自反思进化能力 | 微调代理缺乏自我反思与改进潜力 | 自主语言智能体 |
| 4 | http://arxiv.org/abs/2503.01976v2 | Learning a Game by Paying the Agents | 通过支付信号学习智能体效用函数 | 无需先验知识引导无后悔智能体至均衡 | 博弈论中的智能体引导 |
| 5 | http://arxiv.org/abs/2503.02197v2 | ATLaS: Agent Tuning via Learning Critical Steps | 仅微调专家轨迹中的关键步骤 | 避免全轨迹克隆导致的过拟合与泛化弱 | LLM 智能体微调 |
| 6 | http://arxiv.org/abs/2503.02268v3 | AppAgentX: Evolving GUI Agents as Proficient Smartphone Users | 记忆机制识别重复动作演化为高层动作 | 解决 LLM 代理 routine 任务效率低问题 | 智能手机 GUI 智能体 |
| 7 | http://arxiv.org/abs/2503.04940v2 | VQEL: Enabling Self-Play in Emergent Language Games via Agent-Internal Vector Quantization | 引入向量量化到消息生成，支持离散内部表示自博弈 | 解决符号采样不可微及训练稳定性问题 | 涌现语言通信协议 |
| 8 | http://arxiv.org/abs/2503.06580v1 | Agent models: Internalizing Chain-of-Action Generation into Reasoning models | 提出 AutoCoA 框架，内部化动作链生成 | 解决传统工作流依赖外部提示限制自主性的问题 | 通用领域问答任务 |
| 9 | http://arxiv.org/abs/2503.15478v1 | SWEET-RL: Training Multi-Turn LLM Agents on Collaborative Reasoning Tasks | 步级评估RL算法，训练时信息优化批评模型 | 多轮RL信用分配无效、泛化能力利用不足 | 协作内容创作/前后端开发 |
| 10 | http://arxiv.org/abs/2503.15781v1 | UAS Visual Navigation in Large and Unseen Environments via a Meta Agent | 元课程训练+增量自适应强化学习ISAR算法 | 无人机大范围环境导航迁移能力不足 | 无人机导航/城市规划 |
| 11 | http://arxiv.org/abs/2503.16024v2 | The Lighthouse of Language: Enhancing LLM Agents via Critique-Guided Improvement | CGI双玩家框架，批评模型生成细粒度自然语言反馈 | 数值奖励信号上下文指导有限 | 交互式环境决策 |
| 12 | http://arxiv.org/abs/2503.16814v5 | From Belief Entrenchment to Robust Reasoning in LLM Agents | DReaMAD框架，战略先验知识+视角多样性 | 多Agent辩论信念固化强化共享错误 | LLM Agent推理 |
| 13 | http://arxiv.org/abs/2503.17085v1 | Deterministic AI Agent Personality Expression through Standard Psychological Diagnostics | 标准心理框架实现确定性一致个性表达 | AI Agent表达通用化缺乏吸引力 | 人机交互/个性化Agent |
| 14 | http://arxiv.org/abs/2503.12434v2 | A Survey on the Optimization of Large Language Model-based Agents | 全面综述 LLM 智能体优化方法，分类为参数驱动和无参数方法 | 缺乏针对智能体功能的系统化优化综述 | LLM 智能体优化 |
| 15 | http://arxiv.org/abs/2503.12532v2 | STEVE: A Step Verification Pipeline for Computer-use Agent Training | 设计步骤验证流水线，利用二值标签优化计算机使用智能体 | 行为克隆训练需要大量高质量轨迹数据 | 计算机使用智能体 |
| 16 | http://arxiv.org/abs/2503.13194v3 | A representational framework for learning and encoding structurally enriched trajectories in complex agent environments | 提出结构丰富轨迹（SETs），扩展传统轨迹概念化 | 复杂场景中代理决策优化与泛化能力受损 | 复杂代理环境 |
| 17 | http://arxiv.org/abs/2503.13817v1 | VARP: Reinforcement Learning from Vision-Language Model Feedback with Agent Regularized Preferences | 叠加轨迹草图揭示路径，正则化奖励学习以对齐代理策略 | 连续控制机器人奖励函数设计导致错位或奖励黑客 | 连续控制机器人 |
| 18 | http://arxiv.org/abs/2503.21047v1 | World Model Agents with Change-Based Intrinsic Motivation | 将CBET内在动机适配到世界模型算法 | 稀疏奖励环境下RL学习困难的问题 | 稀疏奖励RL环境 |
| 19 | http://arxiv.org/abs/2503.21620v5 | UI-R1: Enhancing Efficient Action Prediction of GUI Agents by Reinforcement Learning | 首个探索规则基RL增强MLLM的GUI动作预测框架 | GUI Agent任务中多模态推理能力不足问题 | 移动设备GUI自动化 |
| 20 | http://arxiv.org/abs/2503.21949v1 | Reward Design for Reinforcement Learning Agents | 提出教师驱动、自适应和元学习三种奖励设计方法 | RL任务中奖励函数设计复杂且易产生意外后果 | 强化学习Agent |
| 21 | http://arxiv.org/abs/2503.18494v1 | Verbal Process Supervision Elicits Better Coding Agents | 言语过程监督 (VPS) 增强代码理解与推理 Agent | 复杂软件工程挑战下代码生成系统表现挣扎 | 复杂软件工程任务 |
| 22 | http://arxiv.org/abs/2503.18665v2 | Boosting Virtual Agent Learning and Reasoning: A Step-Wise, Multi-Dimensional, and Generalist Reward Model with Benchmark | 步级多维通用奖励模型，提供细粒度训练信号 | 当前训练范式依赖结果监督，人工标注劳动密集 | 通用虚拟 Agent (GVA) 训练 |

[返回目录](#目录)

<a id="cat-09"></a>

## Agent记忆与知识管理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2503.08026v2 | In Prospect and Retrospect: Reflective Memory Management for Long-term Personalized Dialogue Agents | 前瞻和反思双向反射的长期记忆管理机制 | 记忆粒度僵化、检索机制无法适应多样对话 | 长期个性化对话Agent |
| 2 | http://arxiv.org/abs/2503.13514v1 | RAG-KG-IL: A Multi-Agent Hybrid Framework for Reducing Hallucinations and Enhancing LLM Reasoning through RAG and Incremental Knowledge Graph Learning Integration | 集成 RAG、KG 与增量学习，实现连续知识更新与结构化知识整合 | 解决 LLM 推理结构化数据难、处理动态知识及幻觉问题 | 关键领域推理与知识整合 |
| 3 | http://arxiv.org/abs/2503.13275v2 | Knowledge-Aware Iterative Retrieval for Multi-Agent Systems | 解耦外部源与内部知识缓存，动态更新指导查询生成 | LLM 缺乏显式推理能力，易受偏差强化循环影响 | 开放域问答 |
| 4 | http://arxiv.org/abs/2503.21760v2 | MemInsight: Autonomous Memory Augmentation for LLM Agents | 自主记忆增强方法提升语义数据表示和检索 | LLM Agent记忆规模增长和语义结构化挑战 | 多任务LLM Agent |
| 5 | http://arxiv.org/abs/2503.19271v2 | MARS: Memory-Enhanced Agents with Reflective Self-improvement | 集成迭代反馈、反思机制及基于遗忘曲线记忆优化 | LLM 动态环境中连续决策、长时记忆及上下文受限 | 多任务与长跨度信息处理 |

[返回目录](#目录)

<a id="cat-10"></a>

## Agent安全与对齐

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2503.08175v1 | Privacy-Enhancing Paradigms within Federated Multi-Agent Systems | 嵌入隐私增强Agent的联邦多Agent系统范式 | 异构隐私协议、多方对话结构差异、动态网络 | 敏感领域的联邦多Agent系统 |
| 2 | http://arxiv.org/abs/2503.09648v1 | A Survey on Trustworthy LLM Agents: Threats and Countermeasures | 可信赖Agent的TrustAgent综合研究框架 | Agent和MAS引入LLM无法覆盖的复杂可信问题 | LLM Agent和多Agent系统安全性 |
| 3 | http://arxiv.org/abs/2503.09241v1 | In-Context Defense in Computer Agents: An Empirical Study | 利用上下文学习和CoT推理的上下文防御方法 | 计算机Agent易受上下文欺骗攻击 | 视觉语言模型计算机Agent安全防护 |
| 4 | http://arxiv.org/abs/2503.00355v1 | Structured Reasoning for Fairness: A Multi-Agent Approach to Bias Detection in Textual Data | 提出多智能体框架，解耦事实与观点并评分 | 检测文本偏差，提升大模型可信度 | 大模型文本公平性检测 |
| 5 | http://arxiv.org/abs/2504.06269v1 | EXCLAIM: An Explainable Cross-Modal Agentic System for Misinformation Detection with Hierarchical Retrieval | 结合多粒度检索与多智能体推理架构 | 检测图文不符的上下文错误信息 | 跨模态虚假信息检测 |
| 6 | http://arxiv.org/abs/2503.01734v2 | Adversarial Agents: Black-Box Evasion Attacks with Reinforcement Learning | RL 智能体学习生成对抗样本攻击策略 | 提升黑盒 evasion 攻击效率与成功率 | 机器学习模型安全性测试 |
| 7 | http://arxiv.org/abs/2503.02116v1 | Multi-Agent Fact Checking | 分布式事实检查器学习不可靠参数 | 解决分布式事实检查中代理可靠性未知 | 假新闻检测系统 |
| 8 | http://arxiv.org/abs/2503.02512v1 | LTL Verification of Memoryful Neural Agents | 支持有记忆神经多智能体系统 LTL 验证 | 解决部分可观测环境下无界规格验证 | 神经多智能体系统验证 |
| 9 | http://arxiv.org/abs/2503.03704v5 | Memory Injection Attacks on LLM Agents via Query-Only Interaction | 提出 MINJA 攻击，仅通过查询注入恶意记录到记忆库 | 解决攻击者无法直接修改记忆库的限制 | LLM 智能体记忆安全 |
| 10 | http://arxiv.org/abs/2503.04392v2 | AgentSafe: Safeguarding Large Language Model-based Multi-agent Systems via Hierarchical Data Management | 通过分层信息管理和记忆保护增强 MAS 安全性 | 解决未授权访问和数据泄露等安全威胁 | 多智能体系统安全 |
| 11 | http://arxiv.org/abs/2503.04957v1 | SafeArena: Evaluating the Safety of Autonomous Web Agents | 提出 SafeArena 基准，评估 Web 智能体的故意滥用风险 | 解决 Web 智能体被用于恶意目的的风险评估问题 | 自主 Web 智能体安全 |
| 12 | http://arxiv.org/abs/2503.06812v1 | Can Proof Assistants Verify Multi-Agent Systems? | 提出 Soda 语言，支持编译到 Lean 进行形式化验证 | 解决多智能体系统交互协议设计与验证挑战 | 多智能体系统验证 |
| 13 | http://arxiv.org/abs/2503.15552v2 | Personalized Attacks of Social Engineering in Multi-turn Conversations: LLM Agents for Simulation and Detection | SE-VSim模拟社会工程攻击，SE-OmniGuard个性化防护 | 多轮对话中社会工程攻击检测复杂 | 社交媒体安全/用户防护 |
| 14 | http://arxiv.org/abs/2503.16248v3 | Real AI Agents with Fake Memories: Fatal Context Manipulation Attacks on Web3 Agents | 上下文操纵攻击，记忆注入比提示注入更危险 | Web3 Agent金融协议交互安全风险 | Web3/区块链金融Agent |
| 15 | http://arxiv.org/abs/2503.17332v4 | CVE-Bench: A Benchmark for AI Agents' Ability to Exploit Real-World Web Application Vulnerabilities | 基于CVE的真实世界网络安全基准，沙箱框架 | 缺乏真实漏洞评估LLM Agent攻击能力 | 网络安全/漏洞评估 |
| 16 | http://arxiv.org/abs/2503.09780v3 | AgentDAM: Privacy Leakage Evaluation for Autonomous Web Agents | 引入 AgentDAM 基准，评估 Web 导航代理是否遵循数据最小化隐私原则 | 解决自主 AI 代理 inadvertent 使用不必要敏感信息的问题 | 自主 Web 导航代理 |
| 17 | http://arxiv.org/abs/2503.10809v3 | MIP against Agent: Malicious Image Patches Hijacking Multimodal OS Agents | 揭示恶意图像补丁攻击向量，可劫持 OS 代理执行有害操作 | 解决 OS 代理直接交互操作系统带来的安全漏洞与操纵风险 | 多模态 OS 代理安全 |
| 18 | http://arxiv.org/abs/2503.11517v1 | Prompt Injection Detection and Mitigation via AI Multi-Agent NLP Frameworks | 设计多智能体 NLP 框架，通过分层检测与执行机制应对提示注入 | 解决生成式 AI 系统因提示注入导致意外输出与策略 breaches 问题 | 生成式 AI 安全 |
| 19 | http://arxiv.org/abs/2503.12163v2 | AgentDroid: A Multi-Agent Framework for Detecting Fraudulent Android Applications | 基于多模态分析与多智能体系统，检测欺诈性 Android 应用 | 解决传统检测方法无法处理多模态数据及高误报率的问题 | Android 欺诈应用检测 |
| 20 | http://arxiv.org/abs/2503.12188v2 | Multi-Agent Systems Execute Arbitrary Malicious Code | 揭示多智能体系统易受对抗内容劫持，导致任意代码执行 | 多智能体系统交互未信任输入时的安全 breaches | 多智能体系统安全 |
| 21 | http://arxiv.org/abs/2503.15546v1 | Enforcing Cybersecurity Constraints for LLM-driven Robot Agents for Online Transactions | 结合区块链与多因素认证的安全架构，保护在线交易 | LLM 驱动机器人系统进行在线交易的安全风险 | 在线交易机器人 |
| 22 | http://arxiv.org/abs/2503.15547v2 | Prompt Flow Integrity to Prevent Privilege Escalation in LLM Agents | 提出 Prompt Flow Integrity 系统，防止 LLM 智能体权限升级 | 用户提示被不安全解释导致的非确定性行为风险 | LLM 智能体安全 |
| 23 | http://arxiv.org/abs/2503.22738v2 | ShieldAgent: Shielding Agents via Verifiable Safety Policy Reasoning | 首个通过逻辑推理执行安全策略的防护Agent | 基础模型Agent易受恶意指令攻击的安全问题 | 自主Agent安全防护 |
| 24 | http://arxiv.org/abs/2503.21237v1 | Bias-Aware Agent: Enhancing Fairness in AI-Driven Knowledge Retrieval | 利用偏见检测器工具识别和突出检索内容中的偏见 | AI Agent知识检索中的偏见和公平性问题 | 信息检索系统 |
| 25 | http://arxiv.org/abs/2503.18455v1 | SEAlign: Alignment Training for Software Engineering Agent | 利用软件工程工作流特征，MCTS 细粒度对齐 | 代码生成模型与实际软件开发任务不对齐 | 现实世界软件工程任务 |
| 26 | http://arxiv.org/abs/2503.18492v2 | VeriSafe Agent: Safeguarding Mobile GUI Agent via Logic-based Action Verification | 形式化验证系统，逻辑基础保障移动 GUI 动作安全 | LFM 基于移动 GUI 自动化不可靠，易出错 | 移动 GUI 自动化任务 |
| 27 | http://arxiv.org/abs/2503.18666v3 | AgentSpec: Customizable Runtime Enforcement for Safe and Reliable LLM Agents | 轻量级领域特定语言，指定并执行运行时约束 | LLM Agent 自主性引入安全、法律及有害行动风险 | 代码、具身、自动驾驶 Agent |
| 28 | http://arxiv.org/abs/2503.20105v1 | Direct Post-Training Preference Alignment for Multi-Agent Motion Generation Models Using Implicit Feedback from Pre-training Demonstrations | 利用预训练演示隐式反馈构建偏好排名，零人类成本对齐 | 预训练模型生成行为偏离人类偏好，标注成本高 | 多智能体运动生成 |
| 29 | http://arxiv.org/abs/2503.23434v2 | Towards Trustworthy GUI Agents: A Survey | 识别执行差距，分解感知、推理、交互信任维度 | GUI 代理执行不可逆操作，缺乏可信性评估 | 图形用户界面自动化代理 |
| 30 | http://arxiv.org/abs/2503.23804v3 | DrunkAgent: Stealthy Memory Corruption in LLM-Powered Recommender Agents | 提出黑盒攻击框架，通过腐蚀记忆更新促进目标物品 | LLM 推荐代理记忆机制存在 adversarial 攻击面 | 推荐系统安全与记忆鲁棒性 |
| 31 | http://arxiv.org/abs/2504.03726v1 | Detecting Malicious AI Agents Through Simulated Interactions | 模拟交互检测恶意 AI 助手，提出意图感知提示方法 | 恶意 AI 助手利用用户弱点操纵，检测困难 | 恶意 AI 代理检测与防御 |
| 32 | http://arxiv.org/abs/2504.00218v2 | Agents Under Siege: Breaking Pragmatic Multi-Agent LLM Systems with Optimized Prompt Attacks | 设计排列不变对抗攻击，优化提示分布绕过安全机制 | 多 agent 系统通信存在新型对抗风险，防御失效 | 多 Agent LLM 系统安全与攻击 |

[返回目录](#目录)

<a id="cat-11"></a>

## 基于Agent的应用系统

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2503.08464v2 | An Autonomous RL Agent Methodology for Dynamic Web UI Testing in a BDD Framework | BDD框架内集成自主RL Agent进行UI测试 | 现代软件应用需要高效可靠的UI测试方法 | Web应用程序的用户界面测试 |
| 2 | http://arxiv.org/abs/2503.08979v1 | Agentic AI for Scientific Discovery: A Survey of Progress, Challenges, and Future Directions | Agent AI科学发现的全面综述与分类 | 科学发现自动化缺乏系统性梳理 | 化学、生物、材料科学等研究领域 |
| 3 | http://arxiv.org/abs/2503.09252v2 | Large-scale Regional Traffic Signal Control Based on Single-Agent Reinforcement Learning | 单Agent RL协调大面积交通信号控制 | 城市化导致交通拥堵严重影响生活质量 | 大规模区域交通信号控制 |
| 4 | http://arxiv.org/abs/2503.09474v2 | Surgical AI Copilot: Energy-Based Fourier Gradient Low-Rank Adaptation for Surgical LLM Agent Reasoning and Planning | 图像引导垂体手术的LLM Agent对话规划执行 | 缺乏手术Agent数据集和鲁棒参数高效微调技术 | 图像引导手术中的实时决策支持 |
| 5 | http://arxiv.org/abs/2503.00821v1 | AI Agents for Ground-Based Gamma Astronomy | 基于指令微调 LLM 构建天文系统管理代理 | 应对下一代天文仪器复杂性与管理挑战 | 地面伽马射线天文台 |
| 6 | http://arxiv.org/abs/2503.02398v2 | PersonaX: A Recommendation Agent Oriented User Modeling Framework for Long Behavior Sequence | 离线多角色画像生成与检索解耦推理 | 解决长序列用户建模上下文限制与延迟 | 个性化推荐智能体 |
| 7 | http://arxiv.org/abs/2503.04817v1 | Multi-Agent System for AI-Assisted Extraction of Narrative Arcs in TV Series | 多智能体系统提取分析电视剧叙事弧 | 解决复杂故事情节追踪与分析困难 | 电视系列剧叙事分析 |
| 8 | http://arxiv.org/abs/2503.03215v2 | COSINT-Agent: A Knowledge-Driven Multimodal Agent for Chinese Open Source Intelligence | 集成 EES-KG 知识图谱与多模态大模型，实现系统化情报推理 | 解决开源情报中多模态数据上下文推理与整合难题 | 中文开源情报分析 |
| 9 | http://arxiv.org/abs/2503.04417v1 | From Idea to CAD: A Language Model-Driven Multi-Agent System for Collaborative Design | 镜像团队结构，利用 VLM 多智能体系统生成 CAD 模型 | 解决 CAD 建模需要深厚专业知识及团队协作的问题 | 工业产品设计与 3D 打印 |
| 10 | http://arxiv.org/abs/2503.05242v1 | MM-StoryAgent: Immersive Narrated Storybook Video Generation with a Multi-Agent Paradigm across Text, Image and Audio | 设计多智能体框架，跨模态生成沉浸式故事视频 | 解决故事吸引力、表达力及评估基准缺乏的问题 | 儿童故事书视频生成 |
| 11 | http://arxiv.org/abs/2503.05347v2 | GEMA-Score: Granular Explainable Multi-Agent Scoring Framework for Radiology Report Evaluation | 提出 GEMA-Score，通过多智能体工作流评估放射报告 | 解决现有指标无法反映生成报告临床可靠性的问题 | 放射学报告评估 |
| 12 | http://arxiv.org/abs/2503.05397v1 | Multi Agent based Medical Assistant for Edge Devices | 利用小型任务特定智能体优化资源，实现端侧部署 | 解决医疗应用隐私、延迟及依赖互联网的问题 | 端侧医疗健康助手 |
| 13 | http://arxiv.org/abs/2503.05854v1 | Accelerating Earth Science Discovery via Multi-Agent LLM Systems | 展示 MAS 驱动工作流管理复杂地球科学数据集 | 解决数据格式复杂、元数据不一致及未处理数据集问题 | 地球科学数据发现 |
| 14 | http://arxiv.org/abs/2503.06664v1 | Exploring LLM Agents for Cleaning Tabular Machine Learning Datasets | 利用 LLM 识别并纠正表格数据中的错误条目 | 解决数据清洗依赖领域专家及自动化挑战的问题 | 机器学习数据清洗 |
| 15 | http://arxiv.org/abs/2503.07673v1 | The potential role of AI agents in transforming nuclear medicine research and cancer management in India | 探讨 AI 智能体在印度核医学癌症管理中的潜力 | 解决医疗基础设施限制及高人口密度挑战 | 印度核医学与癌症管理 |
| 16 | http://arxiv.org/abs/2503.16547v1 | Empowering Medical Multi-Agents with Clinical Consultation Flow for Dynamic Diagnosis | 临床咨询流程+强化学习模拟完整问诊过程 | 医疗诊断多模态信息整合与动态交互 | 医疗诊断/多模态医疗 |
| 17 | http://arxiv.org/abs/2503.15204v1 | When Pigs Get Sick: Multi-Agent AI for Swine Disease Detection | RAG+自适应问答+置信度加权决策融合 | 兽医资源有限、疾病识别延迟 | 畜牧业/动物疾病检测 |
| 18 | http://arxiv.org/abs/2503.15876v1 | DeepPsy-Agent: A Stage-Aware and Deep-Thinking Emotional Support Agent System | 三阶段帮助理论+深度思考分析+阶段转移检测 | AI心理支持动态对话管理与深度推理 | 心理健康/心理咨询 |
| 19 | http://arxiv.org/abs/2503.16698v1 | APPA : Agentic Preformulation Pathway Assistant | LLM+实验数据库+ML模型整合药物预制剂策略 | 药物制剂开发手动收集分析证据耗时 | 制药研发/药物开发 |
| 20 | http://arxiv.org/abs/2503.16734v1 | Towards Agentic Recommender Systems in the Era of Multimodal Large Language Models | 系统分析LLM-ARS核心概念、架构与研究问题 | 推荐系统如何整合Agent能力提升体验 | 推荐系统/多模态LLM |
| 21 | http://arxiv.org/abs/2503.16780v1 | A-IDE : Agent-Integrated Denoising Experts | LLM Agent动态路由LDCT扫描到专用专家模型 | 单一去噪模型跨解剖结构泛化困难 | 医学影像/低剂量CT |
| 22 | http://arxiv.org/abs/2503.18968v3 | MedAgent-Pro: Towards Evidence-based Multi-modal Medical Diagnosis via Reasoning Agentic Workflow | 分层诊断结构+RAG检索指南+工具验证每步 | 医疗诊断缺乏定量分析与证据支持 | 医疗诊断/多模态医学 |
| 23 | http://arxiv.org/abs/2503.17553v1 | Autonomous Radiotherapy Treatment Planning Using DOLA: A Privacy-Preserving, LLM-Based Optimization Agent | 本地部署LLM+RAG+RL优化放疗计划保护隐私 | 放疗计划主观决策、规划者间差异 | 医疗/放射治疗 |
| 24 | http://arxiv.org/abs/2503.10120v1 | Hybrid Agents for Image Restoration | 提出快慢反馈混合修复代理规则，统一多种修复模式 | 解决非专业用户交互不足及复杂现实应用修复能力受限问题 | 图像修复 |
| 25 | http://arxiv.org/abs/2503.10265v2 | SurgRAW: Multi-Agent Workflow with Chain of Thought Reasoning for Robotic Surgical Video Analysis | 提出临床对齐的 CoT 驱动代理工作流，含分层推理与面板讨论 | 解决手术 AI 方法碎片化及 VLM 幻觉与领域差距问题 | 机器人手术视频分析 |
| 26 | http://arxiv.org/abs/2503.10876v1 | Teamwork makes the dream work: LLMs-Based Agents for GitHub README.MD Summarization | 提出 Metagente 多智能体框架，通过评估反馈合作自优化系统 | 解决单一 LLM 潜力未充分挖掘及 README 总结准确性问题 | 软件工程文档总结 |
| 27 | http://arxiv.org/abs/2503.11060v2 | BannerAgency: Advertising Banner Design with Multimodal LLM Agents | 提出无训练框架，MLLM 代理协作生成可编辑的横幅广告组件 | 解决广告横幅设计搜索空间大及像素输出限制可编辑性问题 | 广告横幅设计 |
| 28 | http://arxiv.org/abs/2503.11733v2 | LLM Agents for Education: Advances and Applications | 系统综述 LLM 代理在教育中的进展，涵盖反馈生成、课程设计等 | 解决教育场景中部署 LLM 代理的伦理、幻觉及生态系统集成挑战 | 教育领域应用 |
| 29 | http://arxiv.org/abs/2503.11346v1 | AIstorian lets AI be a historian: A KG-powered multi-agent system for accurate biography generation | 引入 KG 驱动 RAG 与反幻觉多代理，实现准确传记生成 | 解决现有 LLM 在历史写作风格、事实忠实度及碎片信息处理难题 | 历史研究与传记生成 |
| 30 | http://arxiv.org/abs/2503.11739v1 | CoLLMLight: Cooperative Large Language Model Agents for Network-Wide Traffic Signal Control | 构建时空图捕捉交通动态，引入复杂度感知推理机制 | 解决现有 LLM 方法缺乏代理间协调限制网络-wide 优化问题 | 交通信号控制 |
| 31 | http://arxiv.org/abs/2503.13524v1 | Agent-Enhanced Large Language Models for Researching Political Institutions | 展示增强预定义函数的 LLM 作为动态代理简化数据收集分析 | 解决政治制度研究中复制、测试及扩展实证研究的成本问题 | 政治科学研究 |
| 32 | http://arxiv.org/abs/2503.12077v1 | V-Stylist: Video Stylization via Collaboration and Reflection of MLLM Agents | 提出视频解析、风格解析、风格艺术家三角色协作工作流 | 解决现有视频风格化方法难以处理复杂过渡及开放风格描述问题 | 视频风格化 |
| 33 | http://arxiv.org/abs/2503.12255v1 | Agentic Search Engine for Real-Time IoT Data | 利用 LLM 和 RAG 构建 IoT 智能搜索引擎，处理实时数据查询 | IoT 系统碎片化导致的数据共享与协调管理限制 | 物联网数据搜索 |
| 34 | http://arxiv.org/abs/2503.12721v2 | Can Reasoning Models Reason about Hardware? An Agentic HLS Perspective | 提出基于 LLM 的优化智能体框架，自动重构代码并插入 pragmas | 高级综合设计空间探索依赖人工定义 pragmas | 硬件设计优化 |
| 35 | http://arxiv.org/abs/2503.13205v1 | MAP: Evaluation and Multi-Agent Enhancement of Large Language Models for Inpatient Pathways | 提出多智能体住院路径框架，包含分诊、诊断、治疗代理 | 住院路径需要复杂临床决策，缺乏大规模数据集 | 医疗住院路径 |
| 36 | http://arxiv.org/abs/2503.13269v2 | DAgent: A Relational Database-Driven Data Analysis Report Generation Agent | 集成规划、工具、记忆模块，生成关系数据库分析报告 | 现有方法无法处理需多步推理与跨表关联的复杂分析任务 | 数据分析报告生成 |
| 37 | http://arxiv.org/abs/2503.13279v1 | Goal2Story: A Multi-Agent Fleet based on Privately Enabled sLLMs for Impacting Mapping on Requirements Elicitation | 采用影响映射框架，仅使用成本效益 sLLM 进行目标驱动需求 elicitation | 当前研究侧重功能 RE，缺乏从目标到用户故事的桥梁 | 软件需求工程 |
| 38 | http://arxiv.org/abs/2503.13856v1 | MDTeamGPT: A Self-Evolving LLM-based Multi-Agent Framework for Multi-Disciplinary Team Medical Consultation | 使用共识聚合与残差讨论结构，积累咨询经验自我进化 | 多角色协作导致对话历史过长，认知负担重 | 多学科医疗会诊 |
| 39 | http://arxiv.org/abs/2503.13964v1 | MDocAgent: A Multi-Modal Multi-Agent Framework for Document Understanding | 五 specialized 代理 engage 多模态上下文检索，综合文本与视觉信息 | 现有方法优先单模态信息，难以处理复杂多模态推理 | 文档问答 |
| 40 | http://arxiv.org/abs/2503.14251v1 | Towards a Barrier-free GeoQA Portal: Natural Language Interaction with Geospatial Data Using Multi-Agent LLMs and Semantic Search | 多智能体 LLM 框架实现与地理空间数据的无缝自然语言交互 | 地理门户复杂功能与重叠层挑战非专家用户 | 地理空间数据访问 |
| 41 | http://arxiv.org/abs/2503.20950v1 | DEMENTIA-PLAN: An Agent-Based Framework for Multi-Knowledge Graph Retrieval-Augmented Generation in Dementia Care | 多知识图谱架构配合自反思规划Agent | 轻度痴呆患者记忆丧失和情绪不稳定问题 | 痴呆症护理 |
| 42 | http://arxiv.org/abs/2503.21080v7 | EmoDebt: Bayesian-Optimized Emotional Intelligence for Strategic Agent-to-Agent Debt Recovery | 贝叶斯优化情感智能引擎实现自适应谈判策略 | 债务催收中LLM Agent易被对抗性情绪模拟利用 | 债务回收谈判 |
| 43 | http://arxiv.org/abs/2503.21735v4 | GateLens: A Reasoning-Enhanced LLM Agent for Automotive Software Release Analytics | 使用关系代数作为自然语言推理与代码的中间表示 | LLM在表格数据分析中推理和结构化处理能力不足 | 汽车软件发布分析 |
| 44 | http://arxiv.org/abs/2503.22164v2 | PharmAgents: Building a Virtual Pharma with Large Language Model Agents | 虚拟制药生态系统模拟完整药物发现工作流 | 小分子药物开发复杂、资源密集、耗时长 | 药物发现 |
| 45 | http://arxiv.org/abs/2504.08752v1 | Patience is all you need! An agentic system for performing scientific literature review | LLM系统执行科学文献搜索和信息提炼 | 科学研究中文献检索和信息分析依赖专家知识 | 科学文献综述 |
| 46 | http://arxiv.org/abs/2504.08754v5 | Towards Personalized Conversational Sales Agents: Contextual User Profiling for Strategic Action | CSI Agent主动推断上下文用户画像并策略性选择行动 | 传统CRS仅关注偏好 elicitation，忽略复杂决策因素 | 对话式电商销售 |
| 47 | http://arxiv.org/abs/2503.22877v2 | Understanding Inequality of LLM Fact-Checking over Geographic Regions with Agent and Retrieval models | 评估LLM事实检查在不同地理区域的表现差异 | LLM事实检查在全球南北方之间存在显著性能差距 | 全球事实检查 |
| 48 | http://arxiv.org/abs/2503.17753v3 | Building Resource-Constrained Language Agents: A Korean Case Study on Chemical Toxicity Information | 上下文高效架构，分层搜索减少 Token 消耗 | 资源受限环境下专用领域语言 Agent 部署难 | 韩语化学毒性信息查询 |
| 49 | http://arxiv.org/abs/2503.17850v1 | CP-AgentNet: Autonomous and Explainable Communication Protocol Design Using Generative Agents | 生成式 Agent 自主设计通信协议，减少人工 effort | DRL 协议设计黑盒、数据 hungry、需专家知识 | 通信网络协议设计 |
| 50 | http://arxiv.org/abs/2503.18461v1 | MuMA: 3D PBR Texturing via Multi-Channel Multi-View Generation and Agentic Post-Processing | 多通道多视图生成，Agent 后处理模拟艺术家技巧 | 3D 生成 PBR 纹理数据有限，多通道材料建模难 | 3D PBR 纹理生成 |
| 51 | http://arxiv.org/abs/2504.03699v4 | Enhancing Clinical Decision-Making: Integrating Multi-Agent Systems with Ethical AI Governance | 模块化 Agent 分析实验室结果，集成伦理 AI 治理 | 确保临床决策支持系统可靠有效及患者护理 | 重症监护临床决策 |
| 52 | http://arxiv.org/abs/2503.19584v3 | Multi-agent Application System in Office Collaboration Scenarios | 分离 Plan 与 Solver 架构，增强多意图多轮对话能力 | 办公协作效率与工作质量提升需求 | 办公协作场景 |
| 53 | http://arxiv.org/abs/2503.19752v1 | Inducing Personality in LLM-Based Honeypot Agents: Measuring the Effect on Human-Like Agenda Generation | 基于五因素模型提示 schema 诱导 LLM  distinct 人格 | 网络欺骗中需要高保真 engagement 延长攻击观察 | 网络欺骗 honeypot 代理 |
| 54 | http://arxiv.org/abs/2503.20036v2 | Agents in the Sandbox: End-to-End Crash Bug Reproduction for Minecraft | 端到端框架自动化复现 Minecraft 崩溃 bug | 游戏崩溃 bug 复现手动、耗时且难自动化 | Minecraft 游戏测试 |
| 55 | http://arxiv.org/abs/2503.23374v1 | RuleAgent: Discovering Rules for Recommendation Denoising with Autonomous Language Agents | 语言 agent 自主发现推荐去噪规则，引入 LossEraser 策略 | 推荐系统隐式反馈噪声大，人工规则泛化性差 | 推荐系统数据清洗与去噪 |
| 56 | http://arxiv.org/abs/2503.23421v1 | A Multi-agent Onboarding Assistant based on Large Language Models, Retrieval Augmented Generation, and Chain-of-Thought | 结合 RAG 与 CoT 的多 agent 入职助手，提供上下文支持 | 软件工程入职成本高，传统方法更新慢 | 软件开发团队入职培训 |
| 57 | http://arxiv.org/abs/2504.03723v2 | VFlow: Discovering Optimal Agentic Workflows for Verilog Generation | 多群体协同进化算法优化 Verilog 生成工作流 | 硬件设计自动化生成代码质量低，效率差 | 硬件设计与 Verilog 代码生成 |
| 58 | http://arxiv.org/abs/2503.23803v2 | Thinking Longer, Not Larger: Enhancing Software Engineering Agents via Scaling Test-Time Compute | 统一测试时计算缩放框架，内部与外部策略结合 | 开源模型代码推理性能差，依赖大模型资源 | 软件工程代理与代码修复 |

[返回目录](#目录)

<a id="cat-12"></a>

## Agent工具使用与环境交互

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2503.10689v2 | Learning to Contextualize Web Pages for Enhanced Decision Making by LLM Agents | 解耦网页理解与决策的上下文化模块 | Agent难以理解处理复杂网页结构 | Web自动化任务中的LLM Agent决策 |
| 2 | http://arxiv.org/abs/2503.09089v2 | LocAgent: Graph-Guided LLM Agents for Code Localization | 图引导的多跳推理代码定位框架 | 复杂代码库中高效导航识别相关代码段困难 | 软件维护中的代码变更定位 |
| 3 | http://arxiv.org/abs/2503.00401v2 | Smoothing Grounding and Reasoning for MLLM-Powered GUI Agents with Query-Oriented Pivot Tasks | 提出查询推理桥接 GUI 定位与推理任务 | 解决资源受限下定位与推理格式差异 | 多模态大模型 GUI 智能体 |
| 4 | http://arxiv.org/abs/2503.04830v3 | Cite Before You Speak: Enhancing Context-Response Grounding in E-commerce Conversational LLM-Agents | 引入引用体验和多 UX 推理系统，增强回复的事实依据 | 解决 LLM 幻觉及客户难以验证生成信息的问题 | 电商购物对话代理 |
| 5 | http://arxiv.org/abs/2503.04188v2 | Measuring temporal effects of agent knowledge by date-controlled tool use | 使用日期控制工具评估 LLM 智能体知识的时间效应 | 解决搜索引擎时间性影响智能体响应质量的问题 | 科学出版物摘要写作 |
| 6 | http://arxiv.org/abs/2503.14432v2 | PLAY2PROMPT: Zero-shot Tool Instruction Optimization for LLM Agents via Tool Play | 通过"玩"工具自动探索输入输出行为生成文档 | 零样本场景下工具使用文档缺失/噪声 | LLM Agent工具集成 |
| 7 | http://arxiv.org/abs/2503.14713v1 | TestForge: Feedback-Driven, Agentic Test Suite Generation | 迭代式测试生成，基于执行反馈持续优化 | 自动化测试生成成本高、可读性差 | 软件测试/单元测试 |
| 8 | http://arxiv.org/abs/2504.08739v1 | Enhancing Product Search Interfaces with Sketch-Guided Diffusion and Language Agents | 草图引导扩散+多模态Agent个性化产品搜索 | 图像搜索用户体验与个性化不足 | 电商/产品搜索 |
| 9 | http://arxiv.org/abs/2503.10613v1 | CoSTA$\ast$: Cost-Sensitive Toolpath Agent for Multi-turn Image Editing | 结合 LLM 子任务树与 A*搜索，寻找成本敏感的工具路径 | 解决多轮图像编辑中工具路径探索昂贵及成本质量平衡问题 | 多轮图像编辑 |
| 10 | http://arxiv.org/abs/2503.10970v1 | TxAgent: An AI Agent for Therapeutic Reasoning Across a Universe of Tools | 利用 211 种工具库进行多步推理与实时生物医学知识检索 | 解决个性化治疗推荐中药物相互作用与禁忌症分析难题 | 精准治疗推荐 |
| 11 | http://arxiv.org/abs/2503.13843v2 | WebNav: An Intelligent Agent for Voice-Controlled Web Navigation | 双 LLM 架构翻译自然语言命令为 GUI 精确 executable 动作 | 现代 Web 界面 accessibility 缺乏，传统方法灵活性不足 | Web 导航自动化 |
| 12 | http://arxiv.org/abs/2503.17709v1 | GUI-Xplore: Empowering Generalizable GUI Agents with One Exploration | 探索 - 推理框架，结合预记录视频与层次化任务 | GUI 智能体跨应用与任务泛化能力有限 | 跨应用 GUI 交互任务 |
| 13 | http://arxiv.org/abs/2503.20201v1 | Open Deep Search: Democratizing Search with Open-source Reasoning Agents | 增强开源 LLM 推理能力， judiciously 使用 Web 搜索工具 | 专有搜索 AI 解决方案与开源 counterparts 差距增大 | 开放源搜索与推理 |

[返回目录](#目录)

<a id="cat-13"></a>

## 人机协作Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2503.01608v1 | RevTogether: Supporting Science Story Revision with Multiple AI Agents | 多智能体模拟情感并提供修订建议 | 辅助非专家作者修订科学故事 | 科学传播与写作辅助 |
| 2 | http://arxiv.org/abs/2503.01767v1 | Designing VR Simulation System for Clinical Communication Training with LLMs-Based Embodied Conversational Agents | VR 结合 LLM 具身对话代理支持动态交互 | 解决临床沟通培训 content 固定缺乏定制 | 医疗职业教育培训 |
| 3 | http://arxiv.org/abs/2503.02692v1 | FinArena: A Human-Agent Collaboration Framework for Financial Market Analysis and Forecasting | 结合多模态数据分析与用户风险偏好 | 提升股票趋势预测与个性化投资决策 | 金融市场分析与投资 |
| 4 | http://arxiv.org/abs/2503.04692v1 | The Influence of Prior Discourse on Conversational Agent-Driven Decision-Making | 探索对话智能体如何利用认知偏差影响决策 | 解决对话 nudging 策略中先前任务复杂性影响的问题 | 行为经济学与决策 |
| 5 | http://arxiv.org/abs/2503.05039v1 | Bridging the AI Adoption Gap: Designing an Interactive Pedagogical Agent for Higher Education Instructors | 设计交互式教学代理，支持不同 AI 素养的教师 | 解决教师采用 AI 工具不一致及缺乏支持的问题 | 高等教育教师 |
| 6 | http://arxiv.org/abs/2503.09794v1 | Augmenting Teamwork through AI Agents as Spatial Collaborators | 提出空间感知 AI 代理应动态生成资源以支持人类团队协作 | 解决 AR 环境中 AI 仅作为静态工具而非自适应队友的问题 | 增强现实中的团队协作 |
| 7 | http://arxiv.org/abs/2503.12499v2 | PTFA: An LLM-based Agent that Facilitates Online Consensus Building through Parallel Thinking | 利用 LLM 并行执行六顶思考帽角色，促进在线共识构建 | 共识构建因利益相关者意见多样而具有挑战性 | 在线群体决策 |
| 8 | http://arxiv.org/abs/2503.14263v1 | Conversational Agents as Catalysts for Critical Thinking: Challenging Social Influence in Group Decision-making | 调查 LLM 驱动的 devil's advocate 系统对权力不平衡群体动态的影响 | 社会影响与权力动态 suppress 少数观点，导致群体思维 | 群体决策 |
| 9 | http://arxiv.org/abs/2503.21365v1 | CA+: Cognition Augmented Counselor Agent Framework for Long-term Dynamic Client Engagement | 认知增强咨询框架实现长期客户参与 | AI咨询系统难以维持长期有效客户参与 | 心理咨询服务 |
| 10 | http://arxiv.org/abs/2504.03693v2 | Agentic Business Process Management: Practitioner Perspectives on Agent Governance in Business Processes | 调研从业者观点，提出 AI Agent 治理六项建议 | 组织内 AI Agent 有效安全部署的治理挑战 | 业务流程管理 (BPM) |
| 11 | http://arxiv.org/abs/2503.18238v3 | Collaborating with AI Agents: Field Experiments on Teamwork, Productivity, and Performance | 大规模实验揭示人机协作提升生产力机制 | 人机协作对生产力、绩效影响机制不明 | 广告创作团队协作 |
| 12 | http://arxiv.org/abs/2503.19274v1 | CoMAC: Conversational Agent for Multi-Source Auxiliary Context with Sparse and Symmetric Latent Interactions | 多源辅助上下文对话 Agent，双向信息共享 | 难以高效提取多源信息并结合对话能力与事实 | 多源上下文对话生成 |
| 13 | http://arxiv.org/abs/2503.19328v2 | Substance over Style: Evaluating Proactive Conversational Coaching Agents | 评估多轮 coaching  agents，揭示用户重视核心功能 | Coaching 任务目标未定义，评估标准主观，多轮交互复杂 | 对话式 Coaching 代理 |
| 14 | http://arxiv.org/abs/2503.19334v1 | Design of Seamless Multi-modal Interaction Framework for Intelligent Virtual Agents in Wearable Mixed Reality Environment | 无缝多模态交互框架，集成空间映射与虚拟角色动画 | 可穿戴 MR 环境中虚拟 Agent 交互体验不连贯 | 博物馆等 MR 交互应用 |
| 15 | http://arxiv.org/abs/2503.19537v1 | Agent-Initiated Interaction in Phone UI Automation | 定义 Agent 发起交互任务，检测需求并生成消息 | 复杂任务需用户交互，对齐用户期望建立信任难 | 手机 UI 自动化 |
| 16 | http://arxiv.org/abs/2503.23153v1 | Conversational Agents for Older Adults' Health: A Systematic Literature Review | 系统综述老年人健康对话代理的研究现状与期望 | 现有综述缺乏 HCI 视角，老年人接受度低 | 老年人健康管理与对话系统 |
| 17 | http://arxiv.org/abs/2504.13871v1 | Human aversion? Do AI Agents Judge Identity More Harshly Than Performance | 研究 LLM 代理如何评估人类输入，发现反向算法厌恶 | 混合决策系统中 AI 代理对人类建议权重偏低 | 人机协作决策与信任机制 |

[返回目录](#目录)

<a id="cat-14"></a>

## 低代码/无代码Agent平台

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2503.02950v2 | LiteWebAgent: The Open-Source Suite for VLM-Based Web-Agent Applications | 开源套件结合最小后端与可扩展研究组件 | 填补 Web 代理生态中生产就绪方案空白 | VLM Web 智能体应用开发 |
| 2 | http://arxiv.org/abs/2503.03686v1 | MAS-GPT: Training LLMs to Build LLM-based Multi-Agent Systems | 将 MAS 构建重构为生成语言任务，单次推理生成 MAS | 解决现有方法依赖手动配置及推理成本高的问题 | 多智能体系统自动构建 |
| 3 | http://arxiv.org/abs/2503.11444v1 | Cerebrum (AIOS SDK): A Platform for Agent Development, Deployment, Distribution, and Discovery | 提供模块化四层架构 SDK 与社区驱动 Agent Hub，标准化开发 | 解决自主 LLM 代理领域缺乏标准化开发部署分发工具的问题 | 代理开发与部署 |

[返回目录](#目录)

<a id="cat-15"></a>

## Agent可解释性与透明度

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2503.14557v1 | Generating Causal Explanations of Vehicular Agent Behavioural Interactions with Learnt Reward Profiles | 学习代理奖励指标权重，因果推断代理交互解释 | 难以在不捕获代理重要性下做出准确因果推断 | 自动驾驶车辆 |
| 2 | http://arxiv.org/abs/2503.23326v3 | Exploring Explainable Multi-agent MCTS-minimax Hybrids in Board Game Using Process Mining | 集成浅层 minimax 到 MCTS  rollout，用过程挖掘解释策略 | MCTS 搜索树选择性高易遗漏关键步，行为难解释 | 棋盘游戏 AI 与决策解释 |

[返回目录](#目录)

<a id="cat-16"></a>

## 其他-Agent综述与研究展望

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2503.19213v1 | A Survey of Large Language Model Agents for Question Answering | 系统综述 LLM Agent 在 QA 任务中的设计与挑战 | 传统 Agent 数据需求大，泛化新环境难 | 问答 (QA) 任务 |

[返回目录](#目录)
