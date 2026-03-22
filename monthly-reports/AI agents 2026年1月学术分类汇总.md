# AI agents 2026年1月学术分类汇总

共收录 868 篇论文，按研究方向分类整理如下。

## 目录

- [Agent安全与对齐（100篇）](#cat-01)
- [多Agent协作与通信（67篇）](#cat-02)
- [Agent工具使用与环境交互（34篇）](#cat-03)
- [Agent评测与基准（107篇）](#cat-04)
- [Agent学习与自进化（72篇）](#cat-05)
- [多Agent强化学习（50篇）](#cat-06)
- [Agent架构与框架设计（99篇）](#cat-07)
- [Agent记忆与知识管理（63篇）](#cat-08)
- [具身智能Agent（19篇）](#cat-09)
- [人机协作Agent（28篇）](#cat-10)
- [基于Agent的应用系统（152篇）](#cat-11)
- [Agent仿真与社会模拟（32篇）](#cat-12)
- [Agent规划与推理（39篇）](#cat-13)
- [Agent可解释性与透明度（5篇）](#cat-14)
- [低代码/无代码Agent平台（1篇）](#cat-15)

<a id="cat-01"></a>

## Agent安全与对齐

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2601.00911v2 | Device-Native Autonomous Agents for Privacy-Preserving Negotiations | 设备端自主Agent系统，零知识证明保护隐私 | 中心化服务器路由敏感数据的安全风险 | 保险和B2B商务谈判场景 |
| 2 | http://arxiv.org/abs/2601.00240v2 | When Agents See Humans as the Outgroup: Belief-Dependent Bias in LLM-Powered Agents | 发现Agent将人类视为外群体的偏见风险，形式化信念投毒攻击 | LLM Agent的群体间偏见及信念依赖脆弱性 | 人机交互场景中的Agent安全 |
| 3 | http://arxiv.org/abs/2601.00360v1 | Mapping Human Anti-collusion Mechanisms to Multi-agent AI | 人类反共谋机制分类映射到多Agent AI干预 | 多Agent系统 emergent 共谋策略风险 | 多Agent AI系统治理 |
| 4 | http://arxiv.org/abs/2601.00477v1 | Security in the Age of AI Teammates: An Empirical Study of Agentic Pull Requests on GitHub | 大规模实证分析Agent-authored PR的安全贡献与审查 | 自主编码Agent对软件安全的实际贡献特征 | GitHub开源软件工程项目 |
| 5 | http://arxiv.org/abs/2601.00513v1 | When Small Models Are Right for Wrong Reasons: Process Verification for Trustworthy Agents | 推理完整性评分RIS，过程验证揭示正确但推理错误现象 | 小模型输出正确但推理 flawed 的可靠性危机 | 7-9B参数自主Agent部署 |
| 6 | http://arxiv.org/abs/2601.00516v1 | Trajectory Guard -- A Lightweight, Sequence-Aware Model for Real-Time Anomaly Detection in Agentic AI | 孪生循环自编码器混合损失，联合学习任务轨迹对齐与序列有效性 | 现有异常检测稀释异常步骤忽略序列结构 | 生产部署中Agent实时安全验证 |
| 7 | http://arxiv.org/abs/2601.01008v1 | An Explainable Agentic AI Framework for Uncertainty-Aware and Abstention-Enabled Acute Ischemic Stroke Imaging Decisions | 模块化Agent流水线，不确定性驱动自然涌现弃权决策 | 现有方法黑盒预测缺乏不确定性感知与弃权机制 | 急性缺血性卒中影像决策 |
| 8 | http://arxiv.org/abs/2601.01576v2 | OpenNovelty: An LLM-powered Agentic System for Verifiable Scholarly Novelty Assessment | 四阶段流程基于检索真实论文确保可验证判断 | 同行评审中新颖性评估需对照海量快速演变文献 | 学术论文新颖性评估 |
| 9 | http://arxiv.org/abs/2601.01685v1 | Lying with Truths: Open-Channel Multi-Agent Collusion for Belief Manipulation via Generative Montage | 生成蒙太奇Writer-Editor-Director框架，仅用真实证据片段操纵信念 | 共谋Agent通过公开渠道引导受害者信念的新型攻击 | LLM Agent动态信息环境交互 |
| 10 | http://arxiv.org/abs/2601.01723v1 | Structural Representations for Cross-Attack Generalization in AI Agent Threat Detection | 结构标记化编码执行流模式而非对话内容，门控多视图融合 | 标准对话标记化在结构攻击上泛化失败 | AI Agent威胁检测 |
| 11 | http://arxiv.org/abs/2601.01791v2 | Rethinking Secure Semantic Communications in the Age of Generative and Agentic AI: Threats and Opportunities | 系统分类语义通信中的窃听威胁模型 | GenAI/Agentic AI增强的隐私泄露风险 | 6G语义通信系统安全 |
| 12 | http://arxiv.org/abs/2601.03294v1 | AgentMark: Utility-Preserving Behavioral Watermarking for Agents | 规划决策层嵌入多比特标识符的行为水印 | LLM Agent知识产权保护与监管溯源 | 自主Agent系统IP保护 |
| 13 | http://arxiv.org/abs/2601.04243v1 | Integrating Multi-Agent Simulation, Behavioral Forensics, and Trust-Aware Machine Learning for Adaptive Insider Threat Detection | 多Agent模拟+SIEM+心智理论推理混合框架 | 内部威胁检测灵敏度与精度平衡 | 企业网络安全监测 |
| 14 | http://arxiv.org/abs/2601.02750v1 | Ahead of the Spread: Agent-Driven Virtual Propagation for Early Fake News Detection | LLM Agent驱动虚拟传播证据生成 | 早期阶段缺乏可观察传播信号 | 社交媒体假新闻检测 |
| 15 | http://arxiv.org/abs/2602.06048v1 | Multi-Agent-Driven Cognitive Secure Communications in Satellite-Terrestrial Networks | 双层协调防御系统+生成对抗网络 | 恶意窃听者对卫星地面网络私人信息威胁 | 卫星地面网络安全通信 |
| 16 | http://arxiv.org/abs/2601.04886v2 | Analyzing Message-Code Inconsistency in AI Coding Agent-Authored Pull Requests | 分析23,247个Agent PR发现PR消息-代码不一致类型与影响 | AI编码Agent生成的PR描述与代码变更不一致 | AI编码Agent与人类协作 |
| 17 | http://arxiv.org/abs/2601.05214v1 | Internal Representations as Indicators of Hallucinations in Agent Tool Selection | 利用LLM内部表示实时检测工具调用幻觉 | Agent工具选择幻觉导致结果不一致且绕过安全控制 | 生产系统Agent工具调用可靠性 |
| 18 | http://arxiv.org/abs/2601.05384v1 | Conformity and Social Impact on AI Agents | 研究多Agent环境中AI Agent的从众行为与社会影响 | AI Agent决策存在可被恶意操纵的根本安全漏洞 | 多Agent系统集体部署安全 |
| 19 | http://arxiv.org/abs/2601.07853v1 | FinVault: Benchmarking Financial Agent Safety in Execution-Grounded Environments | 首个执行基础安全基准：31个监管案例驱动沙盒场景 | 现有安全评估未捕获真实工作流与状态变更行动的执行基础风险 | 金融Agent安全评估 |
| 20 | http://arxiv.org/abs/2601.05504v2 | Memory Poisoning Attack and Defense on Memory Based LLM-Agents | 系统评估记忆毒化攻击与防御，提出输入/输出调节与记忆净化 | 基于记忆的LLM-Agent易受记忆毒化攻击，现实部署鲁棒性未研究 | 生产环境记忆增强LLM Agent安全 |
| 21 | http://arxiv.org/abs/2601.05539v1 | LIDL: LLM Integration Defect Localization via Knowledge Graph-Enhanced Multi-Agent Analysis | 知识图谱增强多Agent分析定位LLM集成缺陷 | 现有缺陷定位技术无法识别LLM特定集成缺陷 | LLM集成软件缺陷定位 |
| 22 | http://arxiv.org/abs/2601.06223v1 | Toward Safe and Responsible AI Agents: A Three-Pillar Model for Transparency, Accountability, and Trustworthiness | 基于透明度、问责制与可信度的三支柱模型框架 | 安全Agent自主性需通过渐进验证实现而非立即全自动化 | 负责任AI Agent发展与运营 |
| 23 | http://arxiv.org/abs/2601.03605v1 | DiVA: Fine-grained Factuality Verification with Agentic-Discriminative Verifier | 混合生成搜索与判别评分，细粒度事实验证。 | 解决现有事实验证仅二元判断，缺乏细粒度。 | LLM 事实性验证 |
| 24 | http://arxiv.org/abs/2601.04034v1 | HoneyTrap: Deceiving Large Language Model Attackers to Honeypot Traps with Resilient Multi-Agent Defense | 四防御代理协作，欺骗性防御越狱攻击。 | 现有反应式防御难以应对多轮渐进越狱。 | LLM 安全与越狱防御 |
| 25 | http://arxiv.org/abs/2601.04170v1 | Agent Drift: Quantifying Behavioral Degradation in Multi-Agent LLM Systems Over Extended Interactions | 提出代理漂移概念及稳定性指数量化框架。 | 多代理系统长期交互行为退化未被 examined。 | 多代理系统稳定性 |
| 26 | http://arxiv.org/abs/2601.04171v1 | Agentic Rubrics as Contextual Verifiers for SWE Agents | 专家代理创建上下文 rubric，无需执行验证。 | 代码执行验证扩展难，启发式方法缺乏上下文。 | 软件工程代理验证 |
| 27 | http://arxiv.org/abs/2601.05293v1 | A Survey of Agentic AI and Cybersecurity: Challenges, Opportunities and Use-case Prototypes | 系统综述代理 AI 在网络安全中的挑战与用例。 | 现有治理机制不适应自主长周期 AI 系统。 | 网络安全与代理 AI |
| 28 | http://arxiv.org/abs/2601.04566v2 | BackdoorAgent: A Unified Framework for Backdoor Attacks on LLM-based Agents | 统一框架分析代理工作流中的后门威胁。 | 现有研究孤立分析攻击向量，缺乏跨阶段视角。 | 代理后门攻击与防御 |
| 29 | http://arxiv.org/abs/2601.04583v1 | Autonomous Agents on Blockchains: Standards, Execution Models, and Trust Boundaries | 系统化合链上代理互操作模式与威胁模型。 | 缺乏标准接口保障链上执行安全与治理。 | 区块链与自主代理 |
| 30 | http://arxiv.org/abs/2601.07263v1 | When Bots Take the Bait: Exposing and Mitigating the Emerging Social Engineering Attack in Web Automation Agent | AgentBait攻击范式和SUPERVISOR运行时缓解模块 | Web自动化Agent的社会工程攻击风险 | Web自动化框架/Browser Use等 |
| 31 | http://arxiv.org/abs/2601.08012v1 | Towards Verifiably Safe Tool Use for LLM Agents | STPA识别危害，增强MCP框架结构化标签 | 当前方法无法保证系统安全，需大量人工标注 | LLM Agent工具使用安全 |
| 32 | http://arxiv.org/abs/2601.08235v3 | MPCI-Bench: A Benchmark for Multimodal Pairwise Contextual Integrity Evaluation of Language Model Agents | 首个多模态配对上下文完整性基准，三原则迭代精炼 | 现有CI基准文本中心忽略多模态隐私风险 | 多模态Agent隐私/MPCI-Bench |
| 33 | http://arxiv.org/abs/2601.05755v2 | VIGIL: Defending LLM Agents Against Tool Stream Injection via Verify-Before-Commit | 提出验证前提交协议，平衡推理灵活性与工具流注入防御。 | 防御开放环境中 LLM Agent 面临的间接提示注入攻击。 | LLM Agent 安全防御 |
| 34 | http://arxiv.org/abs/2601.05918v1 | Agentic LLMs as Powerful Deanonymizers: Re-identification of Participants in the Anthropic Interviewer Dataset | 揭示 LLM Agent 利用网络搜索轻松重识别匿名访谈数据的风险。 | 警示 LLM Agent 时代发布丰富定性数据的隐私泄露风险。 | 数据隐私与安全政策 |
| 35 | http://arxiv.org/abs/2601.06838v1 | CHASE: LLM Agents for Dissecting Malicious PyPI Packages | 高可靠性多 Agent 架构，结合计划执行模型与确定性安全工具。 | 解决 LLM 用于安全关键恶意软件检测中的幻觉与上下文混淆。 | 软件供应链安全检测 |
| 36 | http://arxiv.org/abs/2601.06910v1 | PenForge: On-the-Fly Expert Agent Construction for Automated Penetration Testing | 动态构建专家 Agent 进行上下文感知利用，而非依赖预准备 Agent。 | 解决单一通用 Agent 复杂场景挣扎或专用 Agent 无法适应多样漏洞。 | 自动化渗透测试 |
| 37 | http://arxiv.org/abs/2601.08333v1 | Semantic Laundering in AI Agent Architectures: Why Tool Boundaries Do Not Confer Epistemic Warrant | 形式化语义洗钱架构失败模式，证明工具边界无法赋予认识论担保。 | 解决智能体架构中信息传输与认识论 justification 混淆问题。 | AI 智能体架构设计 |
| 38 | http://arxiv.org/abs/2601.10758v1 | Too Helpful to Be Safe: User-Mediated Attacks on Planning and Web-Use Agents | 研究用户中介攻击，揭示智能体默认过于 helpful 而绕过安全约束。 | 解决智能体因过度执行工作流导致不必要数据披露与危害问题。 | 规划与 Web 使用智能体 |
| 39 | http://arxiv.org/abs/2601.09292v1 | Blue Teaming Function-Calling Agents | 评估开源 LLM 函数调用能力对抗攻击的鲁棒性及防御有效性。 | 解决模型默认不安全及防御措施难以在现实场景应用问题。 | 函数调用智能体 |
| 40 | http://arxiv.org/abs/2601.12449v1 | AgenTRIM: Tool Risk Mitigation for Agentic AI | 离线重建+在线最小权限工具访问过滤 | Agent工具权限不平衡导致安全风险和性能下降 | LLM工具调用Agent系统 |
| 41 | http://arxiv.org/abs/2601.12616v1 | Allocating Corrective Control to Mitigate Multi-agent Safety Violations Under Private Preferences | HOCBF+隐私保护拍卖机制分配校正控制 | 多Agent安全违规时需协调校正且不泄露隐私 | 多机器人/多Agent安全系统 |
| 42 | http://arxiv.org/abs/2601.12822v1 | MirrorGuard: Toward Secure Computer-Use Agents via Simulation-to-Real Reasoning Correction | 神经符号仿真训练拦截不安全推理链 | 恶意指令触发Agent不安全系统级操作 | 计算机使用Agent（CUA） |
| 43 | http://arxiv.org/abs/2601.13186v1 | Prompt Injection Mitigation with Agentic AI, Nested Learning, and AI Sustainability via Semantic Caching | 语义缓存+五指标TIVS-O评估框架 | 多Agent设置中提示注入传播放大，缺乏可审计性 | 多Agent LLM部署安全 |
| 44 | http://arxiv.org/abs/2601.13268v1 | Improving the Safety and Trustworthiness of Medical AI via Multi-Agent Evaluation Loops | 多Agent迭代对齐，AMA伦理原则+五级风险评估 | 医疗LLM伦理完整性和安全合规阻碍临床部署 | 医疗AI安全治理 |
| 45 | http://arxiv.org/abs/2601.13518v2 | AgenticRed: Optimizing Agentic Systems for Automated Red-teaming | AgenticRed自动化红队系统演化，无需人工干预 | 现有红队依赖人工工作流，存在偏见且探索成本高 | AI安全评估与红队测试 |
| 46 | http://arxiv.org/abs/2601.13612v1 | PINA: Prompt Injection Attack against Navigation Agents | PINA自适应提示优化框架，黑盒长上下文攻击 | 导航Agent提示注入脆弱性未探索，物理导航风险高 | 具身导航Agent安全 |
| 47 | http://arxiv.org/abs/2601.09869v1 | A Scoping Review of the Ethical Perspectives on Anthropomorphising Large Language Model-Based Conversational Agents | 映射拟人化伦理观点，综合概念基础、伦理挑战及方法论，提出治理建议。 | 解决拟人化交互定义碎片化及缺乏链接交互效应与治理指导的实证工作。 | LLM 对话代理伦理治理 |
| 48 | http://arxiv.org/abs/2601.09923v2 | CaMeLs Can Use Computers Too: System-level Security for Computer Use Agents | 单次规划生成执行图，架构隔离防止指令注入，防御 Branch Steering 攻击。 | 解决计算机使用代理需连续观察 UI 状态与安全隔离要求之间的冲突。 | 计算机使用代理安全 |
| 49 | http://arxiv.org/abs/2601.10156v1 | ToolSafe: Enhancing Tool Invocation Safety of LLM-based agents via Proactive Step-level Guardrail and Feedback | 构建 TS-Bench 基准，多任务 RL 训练 guardrail 模型，主动检测不安全调用。 | 解决 LLM 代理扩展能力放大安全风险及缺乏实时 step-level 监控干预问题。 | LLM 代理工具调用安全 |
| 50 | http://arxiv.org/abs/2601.10338v1 | Agent Skills in the Wild: An Empirical Study of Security Vulnerabilities at Scale | 大规模实证分析 agent skills 生态，发现普遍安全风险及漏洞模式。 | 解决 agent skills 执行隐式信任最小审查创建显著未特征化攻击面问题。 | AI 代理框架技能安全 |
| 51 | http://arxiv.org/abs/2601.10440v1 | AgentGuardian: Learning Access Control Policies to Govern AI Agent Behavior | 监控执行迹学习合法行为，衍生自适应策略监管工具调用及控制流。 | 解决确保 AI 代理仅执行授权动作及适当处理输入以维持系统完整性问题。 | AI 代理行为治理与安全 |
| 52 | http://arxiv.org/abs/2601.10809v1 | A Concise Agent is Less Expert: Revealing Side Effects of Using Style Features on Conversational Agents | 系统研究跨特征风格副作用，发现提示简洁性显著降低感知专业性。 | 解决风格特征如友好简洁用于提示 steer 行为但 unintended 副作用未被理解。 | 对话代理风格控制 |
| 53 | http://arxiv.org/abs/2601.10955v2 | Beyond Max Tokens: Stealthy Resource Amplification via Tool Calling Chains in LLM Agents | 揭示工具调用链中的隐蔽资源放大攻击方法。 | 解决 Agent 工具交互层面的经济拒绝服务攻击。 | LLM Agent 安全防御 |
| 54 | http://arxiv.org/abs/2601.11369v2 | Institutional AI: Governing LLM Collusion in Multi-Agent Cournot Markets via Public Governance Graphs | 治理图机制设计防止多 Agent 市场合谋。 | 解决多 Agent 系统收敛于社会有害均衡问题。 | 多 Agent 经济博弈 |
| 55 | http://arxiv.org/abs/2601.11496v1 | The Poisoned Apple Effect: Strategic Manipulation of Mediated Markets via Technology Expansion of AI Agents | 揭示技术扩展导致的市场策略操纵“毒苹果”效应。 | 解决静态监管框架易受技术扩展操纵问题。 | 经济市场监管 |
| 56 | http://arxiv.org/abs/2601.11893v1 | Taming Various Privilege Escalation in LLM-Based Agent Systems: A Mandatory Access Control Framework | 强制访问控制框架监控 Agent-工具交互信息流。 | 解决基于自然语言攻击导致的权限升级漏洞。 | LLM Agent 系统安全 |
| 57 | http://arxiv.org/abs/2601.12091v1 | Mitigating Cultural Bias in LLMs via Multi-Agent Cultural Debate | 多智能体文化辩论框架减轻 LLM 文化偏见。 | 解决非西方语言提示仅转移而非消除偏见。 | 跨文化公平性 |
| 58 | http://arxiv.org/abs/2601.15322v2 | Replayable Financial Agents: A Determinism-Faithfulness Assurance Harness for Tool-Using LLM Agents | 确定性 - 忠实度保证框架测量轨迹与决策确定性。 | 解决金融审计重放中 Agent 结果不一致问题。 | 金融服务合规 |
| 59 | http://arxiv.org/abs/2601.12349v2 | Zero-Permission Manipulation: Can We Trust Large Multimodal Model Powered GUI Agents? | 揭示 GUI Agent 观察 - 动作间隙的零权限攻击。 | 解决视觉原子性假设无效导致的安全漏洞。 | 移动平台 GUI Agent |
| 60 | http://arxiv.org/abs/2602.12285v1 | From Biased Chatbots to Biased Agents: Examining Role Assignment Effects on LLM Agent Robustness | 系统案例研究展示基于人口统计的角色分配改变代理行为 | 解决角色诱导偏见在代理任务性能中未被探索的问题 | LLM 代理鲁棒性 |
| 61 | http://arxiv.org/abs/2601.14606v1 | An LLM Agent-based Framework for Whaling Countermeasures | 构建个性化防御配置文件并使用基于大模型的代理 | 解决针对高校教职员工的 Whaling 攻击威胁 | 高校 Whaling 防御 |
| 62 | http://arxiv.org/abs/2601.14660v1 | NeuroFilter: Privacy Guardrails for Conversational LLM Agents | 提出 guardrail 框架通过映射规范违规到激活空间简单方向 | 解决现有防御依赖 LLM 中介检查阶段增加延迟成本 | 对话 LLM 代理隐私 |
| 63 | http://arxiv.org/abs/2601.14662v1 | Query-Efficient Agentic Graph Extraction Attacks on GraphRAG Systems | 提出利用新颖性引导探索利用策略的代理图提取攻击框架 | 解决查询预算约束下隐藏图结构重建可行性未探索 | GraphRAG 系统安全 |
| 64 | http://arxiv.org/abs/2601.14667v1 | INFA-Guard: Mitigating Malicious Propagation via Infection-Aware Safeguarding in LLM-Based Multi-Agent Systems | 提出明确识别并解决被感染代理作为 distinct 威胁类别 | 解决传统防护依赖二元范式未能account for 被感染代理 | 多代理系统恶意传播 |
| 65 | http://arxiv.org/abs/2602.13213v1 | Agentic AI for Commercial Insurance Underwriting with Adversarial Self-Critique | 呈现包含对抗性自我批评机制的决策否定人机回路系统 | 解决 regulated 环境下现有解决方案缺乏综合推理能力 | 商业保险承保 |
| 66 | http://arxiv.org/abs/2601.15059v1 | The Responsibility Vacuum: Organizational Failure in Scaled Agent Systems | 定义责任真空为决策发生但责任无法 attributed 的状态 | 解决 scaled 代理部署中责任归属结构性失败 | 规模化代理系统组织 |
| 67 | http://arxiv.org/abs/2601.15232v1 | When Agents Fail: A Comprehensive Study of Bugs in LLM Agents with Automated Labeling | 首个LLM agent bug综合研究，构建BugReAct自动标注agent | 理解agent开发中的bug类型、根因和影响，降低调试成本 | LLM agent开发调试 |
| 68 | http://arxiv.org/abs/2601.15630v1 | Agentic AI Governance and Lifecycle Management in Healthcare | UALM蓝图映射五个控制平面层，支持分阶段采用成熟度模型 | 解决医疗组织中agent蔓延、责任不清、控制不一致问题 | 医疗健康领域agent治理 |
| 69 | http://arxiv.org/abs/2601.15703v1 | Agentic Uncertainty Quantification | 双过程AUQ框架将言语化不确定性转化为主动双向控制信号 | 解决agent幻觉螺旋传播和不确定性量化被动诊断问题 | 长程推理agent可靠性 |
| 70 | http://arxiv.org/abs/2601.15778v1 | Agentic Confidence Calibration | HTC框架提取轨迹级过程特征，实现可解释可迁移校准 | 解决agent系统在失败时过度自信的根本部署障碍 | 高风险场景agent部署 |
| 71 | http://arxiv.org/abs/2601.16472v1 | Secure Intellicise Wireless Network: Agentic AI for Coverless Semantic Steganography Communication | AgentSemSteCom方案无需cover图像和私有语义密钥 | 解决语义隐写通信中私有语义密钥可能被智能窃听者推断问题 | 6G智能无线网络通信安全 |
| 72 | http://arxiv.org/abs/2601.18105v1 | Mitigating the OWASP Top 10 For Large Language Models Applications using Intelligent Agents | 利用智能代理主动识别并 counteract OWASP Top 10 威胁 | LLM 应用面临的数据完整性与保密性安全风险 | LLM 应用安全防护 |
| 73 | http://arxiv.org/abs/2601.18113v3 | MalURLBench: A Benchmark Evaluating Agents' Vulnerabilities When Processing Web URLs | 首个评估 LLM 处理恶意 URL 漏洞的基准，含 6 万攻击实例 | 代理处理伪装恶意 URL 时缺乏检测能力 | Web 代理安全评估 |
| 74 | http://arxiv.org/abs/2601.18842v2 | GUIGuard: Toward a General Framework for Privacy-Preserving GUI Agents | 三阶段框架保护 GUI 代理隐私，识别敏感区域 | 截图传输远程模型导致严重隐私风险 | 隐私保护 GUI 代理 |
| 75 | http://arxiv.org/abs/2601.18386v1 | ARMOR: Agentic Reasoning for Methods Orchestration and Reparameterization for Robust Adversarial Attacks | VLM 引导代理协调对抗原语，自适应重参数化 | 现有攻击套件静态固定，缺乏战略适应 | 对抗攻击生成 |
| 76 | http://arxiv.org/abs/2601.18847v1 | MulVul: Retrieval-augmented Multi-Agent Code Vulnerability Detection via Cross-Model Prompt Evolution | 跨模型提示进化自动化生成专用漏洞检测提示 | 单一模型难以处理异构漏洞模式 | 代码漏洞检测 |
| 77 | http://arxiv.org/abs/2601.18491v1 | AgentDoG: A Diagnostic Guardrail Framework for AI Agent Safety and Security | 诊断护栏框架细粒度监控代理轨迹与根因 | 现有护栏缺乏代理风险意识与透明度 | 代理安全与风控 |
| 78 | http://arxiv.org/abs/2601.18754v1 | $Î±^3$-SecBench: A Large-Scale Evaluation Suite of Security, Resilience, and Trust for LLM-based UAV Agents over 6G Networks | 大规模评估套件测试 UAV 代理安全韧性与信任 | 缺乏对 adversarial 条件下安全自主性的系统评估 | 无人机代理安全 |
| 79 | http://arxiv.org/abs/2601.17344v1 | The Shadow Self: Intrinsic Value Misalignment in Large Language Model Agents | 形式化失控风险，提出内在价值错位评估框架 IMPRESS | 现实 benign 设置下智能体价值错位风险未充分探索 | LLM 智能体安全与价值对齐 |
| 80 | http://arxiv.org/abs/2601.17406v1 | Fingerprinting AI Coding Agents on GitHub | 首个 AI 编码智能体指纹研究，分析行为签名识别代理贡献 | 代码作者归属对仓库治理和研究有效性至关重要 | GitHub 代码仓库治理 |
| 81 | http://arxiv.org/abs/2601.17481v1 | Lattice: Generative Guardrails for Conversational Agents | 自构建持续改进护栏框架，迭代模拟优化与闭环自适应 | 现有护栏使用静态规则无法适应新威胁 | 对话 AI 系统安全防护 |
| 82 | http://arxiv.org/abs/2601.17548v1 | Prompt Injection Attacks on Agentic Coding Assistants: A Systematic Analysis of Vulnerabilities in Skills, Tools, and Protocol Ecosystems | 提示注入攻击系统分析，三维分类法与防御深度框架 | 代理编码助手扩展能力面引入关键安全漏洞 | 代理编码助手安全 |
| 83 | http://arxiv.org/abs/2601.17549v1 | Breaking the Protocol: Security Analysis of the Model Context Protocol Specification and Prompt Injection Vulnerabilities in Tool-Integrated LLM Agents | 首个 MCP 协议规范安全分析，提出向后兼容扩展 MCPSec | MCP 协议架构选择放大攻击成功率 | 工具集成 LLM 智能体协议安全 |
| 84 | http://arxiv.org/abs/2601.17566v1 | Sponge Tool Attack: Stealthy Denial-of-Efficiency against Tool-Augmented Agentic Reasoning | 海绵工具攻击，重写输入提示使推理轨迹冗长消耗计算 | 工具增强智能体推理易受恶意操纵工具调用过程 | 工具增强智能体效率安全 |
| 85 | http://arxiv.org/abs/2601.17887v1 | When Personalization Legitimizes Risks: Uncovering Safety Vulnerabilities in Personalized Dialogue Agents | 揭示意图合法化安全失败， benign 个人记忆 bias 意图推断 | 个性化代理优先效用忽视记忆安全 implications | 个性化对话智能体安全 |
| 86 | http://arxiv.org/abs/2601.21083v3 | OpenSec: Measuring Incident Response Agent Calibration Under Adversarial Evidence | 引入 OpenSec 环境，评估 IR Agent 在对抗证据下的校准 | 解决防御性 Agent 在提示注入下的过度触发问题 | 安全事件响应 Agent |
| 87 | http://arxiv.org/abs/2601.21233v1 | Just Ask: Curious Code Agents Reveal System Prompts in Frontier LLMs | 提出 JustAsk 框架，自主发现提取系统提示策略 | 暴露代码 Agent 交互中系统提示被提取的安全风险 | 前沿 LLM 与自主代码 Agent |
| 88 | http://arxiv.org/abs/2602.13234v1 | Stay in Character, Stay Safe: Dual-Cycle Adversarial Self-Evolution for Safety Role-Playing Agents | 提出双周期对抗自进化框架，平衡角色 fidelity 与安全 | 解决角色扮演 Agent 强 persona 约束下易被越狱问题 | 安全角色扮演 Agent |
| 89 | http://arxiv.org/abs/2601.19174v1 | SHIELD: An Auto-Healing Agentic Defense Framework for LLM Resource Exhaustion Attacks | 多智能体自动愈合防御框架，动态更新知识库 | LLM 系统面临的海绵攻击和资源耗尽威胁 | LLM 服务安全防护 |
| 90 | http://arxiv.org/abs/2601.20184v1 | Securing AI Agents in Cyber-Physical Systems: A Survey of Environmental Interactions, Deepfake Threats, and Defenses | 综述 CPS 中 AI 代理的安全威胁与防御框架 | 生成式 AI 引入的新安全风险超出传统模型 | 信息物理系统安全 |
| 91 | http://arxiv.org/abs/2601.20346v2 | Multimodal Multi-Agent Ransomware Analysis Using AutoGen | 多模态多智能体框架，融合静态动态网络源信息 | 传统检测方法单独使用不足以应对勒索软件 | 网络安全勒索软件分析 |
| 92 | http://arxiv.org/abs/2601.22997v1 | TriCEGAR: A Trace-Driven Abstraction Mechanism for Agentic AI | 提出轨迹驱动的抽象机制，自动从执行日志构建行为 MDP 进行验证。 | 解决智能体行为依赖非确定性环境导致难以保证安全性的问题。 | 智能体运行时验证与保障 |
| 93 | http://arxiv.org/abs/2602.00213v1 | TessPay: Verify-then-Pay Infrastructure for Trusted Agentic Commerce | 构建“先验证后支付”架构，分离控制验证与结算平面。 | 解决代理商务中任务委托、支付结算及审计机制缺乏信任基础的问题。 | 自主智能体商业交易 |
| 94 | http://arxiv.org/abs/2603.05517v1 | Traversal-as-Policy: Log-Distilled Gated Behavior Trees as Externalized, Verifiable Policies for Safe, Robust, and Efficient Agents | 将执行日志蒸馏为可执行门控行为树，作为外部化可验证策略。 | 解决长程策略隐含在权重中导致安全性事后补救及效率低的问题。 | 安全鲁棒的自主智能体 |
| 95 | http://arxiv.org/abs/2601.23211v1 | Multi-Agent Systems Should be Treated as Principal-Agent Problems | 主张用委托 - 代理问题视角研究多智能体系统的信息不对称与目标不一致。 | 解决智能体因目标分歧产生欺骗行为导致代理损失的问题。 | 多智能体系统理论分析 |
| 96 | http://arxiv.org/abs/2602.00428v2 | When Agents ""Misremember"" Collectively: Exploring the Mandela Effect in LLM-based Multi-Agent Systems | 研究多智能体系统中的曼德拉效应，提出提示及模型级防御策略。 | 解决智能体群体因社会影响及错误信息强化导致集体记忆偏差的问题。 | 多智能体系统可靠性 |
| 97 | http://arxiv.org/abs/2602.00755v1 | Evolving Interpretable Constitutions for Multi-Agent Coordination | 提出宪法进化框架，自动发现多智能体 LLM 系统中的行为规范。 | 解决固定原则难以应对多智能体 emergent 社会动态及对齐挑战的问题。 | 多智能体协调与对齐 |
| 98 | http://arxiv.org/abs/2602.00851v2 | Persuasion Propagation in LLM Agents | 研究用户说服如何影响长程任务中智能体的下游行为传播。 | 解决长程任务智能体受信念级干预影响导致行为不一致的问题。 | 智能体行为安全性 |
| 99 | http://arxiv.org/abs/2601.22149v1 | StepShield: When, Not Whether to Intervene on Rogue Agents | 引入 StepShield 基准，评估违规检测的时间点而非仅是否检测，提出时间指标。 | 解决现有安全基准混淆早期干预与事后分析，无法衡量检测时机的问题。 | 代码智能体安全 |
| 100 | http://arxiv.org/abs/2601.22569v1 | Whispers of Wealth: Red-Teaming Google's Agent Payments Protocol via Prompt Injection | 执行 AI 红队评估 AP2，识别 indirect 和 direct 提示注入漏洞，引入两种攻击技术。 | 解决基于 LLM 代理支付系统依赖上下文推理暴露于 prompt-driven 操纵问题。 | 代理支付协议安全 |

[返回目录](#目录)

<a id="cat-02"></a>

## 多Agent协作与通信

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2601.00219v2 | μACP: A Formal Calculus for Expressive, Resource-Constrained Agent Communication | 四动词基元编码FIPA协议，资源约束下形式化演算 | 语义丰富性与资源效率的权衡 | 边缘原生多智能体系统 |
| 2 | http://arxiv.org/abs/2601.11583v1 | Bit-politeia: An AI Agent Community in Blockchain | 区块链上AI Agent社区，民主集中制集群分层架构 | 学术评估中的马太效应与奖励黑客问题 | 科研资源公平分配系统 |
| 3 | http://arxiv.org/abs/2601.00482v1 | Multi-Agent Coordinated Rename Refactoring | 多Agent框架自动化协调重命名，范围推断Agent+计划执行Agent+复制Agent | 开发者手动传播重命名跨文件繁琐易错 | 软件开发中的代码重构任务 |
| 4 | http://arxiv.org/abs/2601.00548v2 | Optimal Transport-Based Decentralized Multi-Agent Distribution Matching | 最优运输分散控制框架，每Agent仅用本地信息决策 | 多Agent系统实现规定终端空间分布 | 分散式多Agent分布匹配 |
| 5 | http://arxiv.org/abs/2601.11587v1 | Evidence-Grounded Multi-Agent Planning Support for Urban Carbon Governance via RAG | 四专业Agent对齐规划工作流，标准RAG证据落地 | LLM事实可靠性与证据可追溯性专业使用障碍 | 城市碳治理规划 |
| 6 | http://arxiv.org/abs/2601.01233v1 | Atomizer: An LLM-based Collaborative Multi-Agent Framework for Intent-Driven Commit Untangling | 意图导向思维链+分组者-审查者协作精炼循环 | 现有方法过度依赖结构信息缺乏语义意图理解 | 软件提交解耦与维护 |
| 7 | http://arxiv.org/abs/2601.01831v1 | ARIES: A Scalable Multi-Agent Orchestration Framework for Real-Time Epidemiological Surveillance and Outbreak Monitoring | 分层指挥结构编排可扩展Agent集群 | 通用AI在流行病学领域的幻觉与数据孤岛 | 全球健康监测与疫情预警 |
| 8 | http://arxiv.org/abs/2601.02021v1 | AgentVNE: LLM-Augmented Graph Reinforcement Learning for Affinity-Aware Multi-Agent Placement in Edge Agentic AI | LLM识别语义约束+图神经网络捕获拓扑相似性 | 资源受限边缘基础设施上的多Agent服务部署 | 边缘计算多Agent系统 |
| 9 | http://arxiv.org/abs/2601.02454v1 | The Rise of Agentic Testing: Multi-Agent Systems for Robust Software Quality Assurance | 测试生成-执行分析-审查优化三Agent闭环系统 | AI测试生成器产生无效/冗余测试 | 软件质量保证与CI/CD |
| 10 | http://arxiv.org/abs/2601.03073v1 | Understanding Multi-Agent Reasoning with Large Language Models for Cartoon VQA | 视觉-语言-批评三Agent协作架构 | 标准LLM难以解释夸张视觉抽象与叙事情境 | 卡通图像视觉问答 |
| 11 | http://arxiv.org/abs/2601.04694v1 | ResMAS: Resilience Optimization in LLM-based Multi-agent Systems | 两阶段框架：拓扑生成器+拓扑感知提示优化增强韧性 | LLM多Agent系统在扰动下的韧性不足问题 | 分布式LLM多Agent协作系统 |
| 12 | http://arxiv.org/abs/2601.04742v1 | Tool-MAD: A Multi-Agent Debate Framework for Fact Verification with Diverse Tool Augmentation and Adaptive Retrieval | 多Agent辩论+异构外部工具+自适应查询优化 | LLM事实验证中的幻觉与检索适应性不足 | 事实验证与事实核查应用 |
| 13 | http://arxiv.org/abs/2601.04861v2 | Orchestrating Intelligence: Confidence-Aware Routing for Efficient Multi-Agent Collaboration across Multi-Scale Models | OI-MAS状态依赖路由+置信度感知模型选择 | 多Agent系统计算效率低，LLM部署均匀浪费 | 高效多Agent协作系统 |
| 14 | http://arxiv.org/abs/2601.04884v1 | Precomputing Multi-Agent Path Replanning using Temporal Flexibility: A Case Study on the Dutch Railway Network | FlexSIPP算法预计算延迟Agent所有可能计划，利用时间灵活性 | 多Agent计划执行中延迟导致冲突与级联延误 | 铁路网络列车重规划 |
| 15 | http://arxiv.org/abs/2601.05465v1 | PRISMA: Reinforcement Learning Guided Two-Stage Policy Optimization in Multi-Agent Architecture for Open-Domain Multi-Hop Question Answering | 解耦RL框架：Plan-Retrieve-Inspect-Solve-Memoize架构+两阶段GRPO | 检索崩溃与学习不稳定阻碍RAG系统可靠部署 | 开放域多跳问答 |
| 16 | http://arxiv.org/abs/2601.19921v1 | Demystifying Multi-Agent Debate: The Role of Confidence and Diversity | 多样性感知初始化+置信度调节辩论协议 | 普通MAD常表现不如简单多数投票尽管计算成本更高 | LLM多Agent辩论系统 |
| 17 | http://arxiv.org/abs/2601.15299v1 | MALTopic: Multi-Agent LLM Topic Modeling Framework | 多代理分工处理主题建模，整合结构化数据。 | 传统方法忽略结构化数据，主题抽象难解释。 | survey 数据分析与主题建模 |
| 18 | http://arxiv.org/abs/2601.03846v1 | When Numbers Start Talking: Implicit Numerical Coordination Among LLM-Based Agents | 博弈论研究 LLM 代理隐式数值协调。 | 理解多代理环境中非语言信号的协调机制。 | 多代理博弈与协调 |
| 19 | http://arxiv.org/abs/2601.04404v1 | 3D-Agent:Tri-Modal Multi-Agent Collaboration for Scalable 3D Object Annotation | 三模态多代理协作， scalable 3D 对象标注。 | 3D 标注面临空间复杂性与视角不一致。 | 3D 对象标注与自动驾驶 |
| 20 | http://arxiv.org/abs/2601.04516v1 | LinguaGame: A Linguistically Grounded Game-Theoretic Paradigm for Multi-Agent Dialogue Generation | 语言博弈论范式，训练-free 均衡近似。 | 提高多代理对话中的沟通效率与意图传达。 | 多代理对话生成 |
| 21 | http://arxiv.org/abs/2601.09746v1 | Multi-Agent Cooperative Learning for Robust Vision-Language Alignment under OOD Concepts | 四核心智能体协作，结构化消息传递，自适应动态平衡机制 | 视觉语言模型处理分布外概念时的跨模态对齐崩溃 | 视觉语言模型/VISTA-Beyond数据集 |
| 22 | http://arxiv.org/abs/2601.07611v2 | DIAGPaper: Diagnosing Valid and Specific Weaknesses in Scientific Papers via Multi-Agent Reasoning | 定制器-反驳-优先级三模块集成，作者Agent与评审Agent辩论 | 多Agent系统表面模拟人类角色，忽略验证和优先级 | 科学论文弱点诊断/DIAGPaper |
| 23 | http://arxiv.org/abs/2601.08129v3 | Emergent Coordination in Multi-Agent Systems via Pressure Fields and Temporal Decay | 压力场梯度隐式协调，时间衰减防止过早收敛 | 显式编排模式协调开销随Agent数量扩展差 | 多Agent系统协调/会议室调度 |
| 24 | http://arxiv.org/abs/2601.08156v1 | Project Synapse: A Hierarchical Multi-Agent Framework with Hybrid Memory for Autonomous Resolution of Last-Mile Delivery Disruptions | 分层多Agent架构，中央监督Agent任务分解 | 最后一公里配送中断自主解决 | 物流配送/30个复杂中断场景 |
| 25 | http://arxiv.org/abs/2601.08237v1 | The End of Reward Engineering: How LLMs Are Redefining Multi-Agent Coordination | 从手工数值奖励转向语言目标规范的概念框架 | 多Agent强化学习中奖励工程根本性挑战 | 多Agent协调/RLVR范式 |
| 26 | http://arxiv.org/abs/2601.05746v1 | DynaDebate: Breaking Homogeneity in Multi-Agent Debate with Dynamic Path Generation | 动态路径生成与分配，引入路径生成 Agent 增强辩论多样性。 | 解决多 Agent 辩论中推理路径同质化导致错误一致的问题。 | 多 Agent 辩论系统 |
| 27 | http://arxiv.org/abs/2601.06453v1 | ConSensus: Multi-Agent Collaboration for Multimodal Sensing | 免训练多 Agent 协作框架，分解多模态传感任务为专用 Agent。 | 解决单一大模型跨模态推理不一致与先验知识偏差问题。 | 多模态传感与生理感知 |
| 28 | http://arxiv.org/abs/2601.06733v1 | Logic-Driven Semantic Communication for Resilient Multi-Agent Systems | 形式化定义 MAS 韧性，设计去中心化算法实现认知与行动韧性。 | 解决去中心化 MAS 在动态条件下持续感知适应与恢复能力不足。 | 6G 网络去中心化多 Agent 系统 |
| 29 | http://arxiv.org/abs/2601.09264v1 | Coordinated Pandemic Control with Large Language Model Agents as Policymaking Assistants | 提出 LLM 多智能体 policymaking 框架，支持跨区域协调与主动 pandemic 控制。 | 解决人类驱动响应碎片化及政策孤立制定问题。 | 跨区域 pandemic 控制 |
| 30 | http://arxiv.org/abs/2601.09295v2 | MACRO-LLM: LLM-Empowered Multi-Agent Collaborative Reasoning under Spatiotemporal Partial Observability | 交错空间与时间推理，通过 CoProposer、Negotiator 与 Introspector 模块协作。 | 解决物理分散导致的空间与时间部分可观测性瓶颈。 | 复杂长程任务协作 |
| 31 | http://arxiv.org/abs/2601.22168v1 | Stablecoin Design with Adversarial-Robust Multi-Agent Systems via Trust-Weighted Signal Aggregation | MVF-Composer信任加权多Agent稳定币控制器 | 算法稳定币在极端波动下易崩溃，缺乏对抗鲁棒性 | DeFi金融稳定币系统 |
| 32 | http://arxiv.org/abs/2601.12542v2 | Rethinking the AI Scientist: Interactive Multi-Agent Workflows for Scientific Discovery | Deep Research多Agent系统，分钟级周转 | 现有AI科研系统专有且批处理，无法实时交互 | 科学发现与研究辅助 |
| 33 | http://arxiv.org/abs/2601.12580v1 | Semantic Fusion: Verifiable Alignment in Decentralized Multi-Agent Systems | 语义融合框架，局部本体验证维持全局一致性 | 去中心化系统缺乏形式化语义协调机制 | 去中心化多Agent系统 |
| 34 | http://arxiv.org/abs/2601.13685v2 | Toward Agentic AI: Task-Oriented Communication for Hierarchical Planning of Long-Horizon Tasks | HiTOC层次化任务导向通信，条件变分信息瓶颈 | 现有通信方案无法处理不同子任务的不同目标 | 边缘服务器-机器人层次系统 |
| 35 | http://arxiv.org/abs/2601.09434v1 | SC-MAS: Constructing Cost-Efficient Multi-Agent Systems with Edge-Level Heterogeneous Collaboration | 提出边级异构协作框架，动态选择代理角色与协作策略，优化成本与性能。 | 解决多智能体系统协作模式单一及推理成本过高的问题。 | 通用多智能体系统 |
| 36 | http://arxiv.org/abs/2601.10102v2 | When Personas Override Payoffs: Role Identity Bias in Multi-Agent LLM Decision-Making | 揭示角色身份偏差根本改变战略推理，persona 存在时偏向社会偏好结果。 | 解决多智能体系统中设计选择如 persona 影响战略推理与均衡达成的问题。 | 多智能体战略决策任务 |
| 37 | http://arxiv.org/abs/2601.10120v1 | TopoDIM: One-shot Topology Generation of Diverse Interaction Modes for Multi-Agent Systems | 一次性拓扑生成多样交互模式，去中心化执行增强适应性及隐私。 | 解决时空交互范式多轮对话导致高延迟计算及通信拓扑优化关键性问题。 | 多智能体通信拓扑优化 |
| 38 | http://arxiv.org/abs/2601.10560v1 | Learning Latency-Aware Orchestration for Parallel Multi-Agent Systems | 延迟感知编排框架，显式优化关键执行路径，构建低延迟执行拓扑图。 | 解决多步执行重复模型调用导致高推理延迟限制时间敏感场景可扩展性。 | 并行多智能体系统编排 |
| 39 | http://arxiv.org/abs/2601.11007v1 | AdaMARP: An Adaptive Multi-Agent Interaction Framework for General Immersive Role-Playing | 自适应多智能体角色扮演框架，含场景管理器。 | 解决现有系统沉浸感不足及多角色编排困难。 | 沉浸式叙事角色扮演 |
| 40 | http://arxiv.org/abs/2601.11327v1 | Can Small Agent Collaboration Beat a Single Big LLM? | 研究小模型工具增强协作能否超越大单体模型。 | 解决模型规模与工具增强对性能影响的权衡。 | 多 Agent 协作策略 |
| 41 | http://arxiv.org/abs/2601.14351v1 | If You Want Coherence, Orchestrate a Team of Rivals: Multi-Agent Models of Organizational Intelligence | 复用企业组织结构，独立代理团队具有严格角色边界 | 解决代理智能易错及缺乏系统性偏差 counter-action 问题 | 组织智能多代理模型 |
| 42 | http://arxiv.org/abs/2601.14230v1 | MASCOT: Towards Multi-Agent Socio-Collaborative Companion Systems | 引入双层优化策略协调个体与集体行为 | 解决多代理系统常受 persona collapse 及社会奉承困扰 | 社会协作伴侣系统 |
| 43 | http://arxiv.org/abs/2601.14245v2 | XR: Cross-Modal Agents for Composed Image Retrieval | 编排三种专用代理类型通过渐进协调推理重构检索 | 解决基于嵌入方法视角狭窄及缺乏语义推理问题 | 组合图像检索 |
| 44 | http://arxiv.org/abs/2601.14652v4 | MAS-Orchestra: Understanding and Improving Multi-Agent Reasoning Through Holistic Orchestration and Controlled Benchmarks | 将多代理编排 formulate 为具有整体编排的函数调用 RL 问题 | 解决当前自动多代理系统设计方法交付不足的问题 | 多代理推理编排 |
| 45 | http://arxiv.org/abs/2601.15047v1 | Game-Theoretic Lens on LLM-based Multi-Agent Systems | 通过博弈论 lens 呈现 LLM 基于多代理系统的综合 survey | 解决当前研究碎片化缺乏统一理论基础 | LLM 多代理系统综述 |
| 46 | http://arxiv.org/abs/2601.15077v1 | Multi-Agent Constraint Factorization Reveals Latent Invariant Solution Structure | 基于算子理论解释MAS为何优于单agent，约束因子化组合 | 解释多LLM智能体系统为何表现更优的机制问题 | 多智能体协作系统理论分析 |
| 47 | http://arxiv.org/abs/2601.15519v2 | TransportAgents: a multi-agents LLM framework for traffic accident severity prediction | 混合多agent框架整合类别特定LLM推理与MLP融合模块 | 解决单agent架构处理异构事故数据的偏见和不稳定预测 | 交通事故严重性预测 |
| 48 | http://arxiv.org/abs/2601.15743v1 | Materealize: a multi-agent deliberation system for end-to-end material design and synthesis | 编排结构生成、属性预测、可合成性预测和合成规划工具 | 桥接计算发现与实验实现，非专家获取可操作材料设计输出 | 无机材料设计与合成 |
| 49 | http://arxiv.org/abs/2601.16596v1 | Attention-MoA: Enhancing Mixture-of-Agents via Inter-Agent Semantic Attention and Deep Residual Synthesis | 通过agent间语义注意力重新定义协作，跨层残差模块自适应早停 | 解决现有MoA方法未能促进agent间深度语义交互限制 | 推理时协作LLM系统 |
| 50 | http://arxiv.org/abs/2601.18077v2 | Sparks of Cooperative Reasoning: LLMs as Strategic Hanabi Agents | 基准测试 17 个 LLM 在 Hanabi 游戏中的协作推理 | 不完全信息下的理论心推理与战略沟通失败 | 策略性卡牌游戏协作 |
| 51 | http://arxiv.org/abs/2601.18735v1 | Why Keep Your Doubts to Yourself? Trading Visual Uncertainties in Multi-Agent Bandit Systems | Agora 框架将协调重构为去中心化不确定性市场 | 现有范式忽略成本且崩溃不确定性结构 | 多代理视觉智能协调 |
| 52 | http://arxiv.org/abs/2601.19082v1 | More at Stake: How Payoff and Language Shape LLM Agent Strategies in Cooperation Dilemmas | 研究报酬 magnitude 与语言 context 塑造代理策略 | 缺乏理解 LLM 在 interactive 设置中的战略行为 | 社会困境中的代理策略 |
| 53 | http://arxiv.org/abs/2601.17152v1 | Dynamic Role Assignment for Multi-Agent Debate | 动态角色分配框架，运行元辩论选择合适智能体填充角色 | 模型 specialization 未用于决定角色分配 | 多智能体辩论系统 |
| 54 | http://arxiv.org/abs/2601.17311v2 | Phase Transition for Budgeted Multi-Agent Synergy | 最小化可校准理论预测固定预算下多智能体协同机制相变 | 固定预算下多智能体系统帮助、饱和或崩溃机制不明 | 多智能体系统预算分配设计 |
| 55 | http://arxiv.org/abs/2601.21469v1 | Adaptive Confidence Gating in Multi-Agent Collaboration for Efficient and Optimized Code Generation | 提出 DebateCoder，多 Agent 协作框架提升 SLM 推理能力 | 解决资源受限环境下小模型代码生成的推理瓶颈 | 自动化软件工程与代码生成 |
| 56 | http://arxiv.org/abs/2601.21700v2 | Toward Culturally Aligned LLMs through Ontology-Guided Multi-Agent Reasoning | 提出 OG-MAR，本体引导多 Agent 推理实现文化对齐 | 解决 LLM 因预训练数据偏差导致的文化价值 misalignment | 文化敏感决策与价值对齐 |
| 57 | http://arxiv.org/abs/2601.21742v1 | Epistemic Context Learning: Building Trust the Right Way in LLM-Based Multi-Agent Systems | 提出 ECL，基于历史交互构建同伴 profile 估计可靠性 | 解决多 Agent 系统中盲目 conform 与评估同伴能力不足问题 | 多 Agent 系统信任与协作 |
| 58 | http://arxiv.org/abs/2601.19170v1 | Multi-Agent Procedural Graph Extraction with Structural and Logical Refinement | 多智能体分阶段提取，结构与逻辑反馈 refinement | 自然语言流程图中结构无效和逻辑流误解问题 | 工作流程图自动提取 |
| 59 | http://arxiv.org/abs/2601.19793v1 | CASTER: Breaking the Cost-Performance Barrier in Multi-Agent Orchestration via Context-Aware Strategy for Task Efficient Routing | 上下文感知路由策略，动态选择模型以降低成本 | 图基多智能体系统中静态模型分配效率低 | 多智能体任务编排 |
| 60 | http://arxiv.org/abs/2602.00127v1 | ALIGN: Aligned Delegation with Performance Guarantees for Multi-Agent LLM Reasoning | 对齐委托博弈，理论保证集成优于单代理生成 | 推理时集成方法缺乏性能提升的形式保证 | 多代理 LLM 推理任务 |
| 61 | http://arxiv.org/abs/2602.00197v2 | Rank-and-Reason: Multi-Agent Collaboration Accelerates Zero-Shot Protein Mutation Prediction | 提出两阶段智能体框架，结合计算专家与虚拟生物学家进行排序与推理。 | 解决蛋白质突变预测中忽略生物物理约束及人工审计低效的问题。 | 蛋白质工程与生物制药 |
| 62 | http://arxiv.org/abs/2601.22974v1 | MiTa: A Hierarchical Multi-Agent Collaboration Framework with Memory-integrated and Task Allocation | 构建分层记忆集成任务分配框架，管理者协调全局任务与 episodic 记忆。 | 解决多智能体系统中记忆不一致及行为冲突导致的低效问题。 | 复杂多智能体协作任务 |
| 63 | http://arxiv.org/abs/2601.23219v1 | MonoScale: Scaling Multi-Agent System with Monotonic Improvement | 提出扩展感知更新框架，生成熟悉化任务引导路由实现单调性能提升。 | 解决 naive 扩展智能体池导致路由器冷启动及性能崩溃的问题。 | 大规模多智能体系统扩展 |
| 64 | http://arxiv.org/abs/2602.00687v1 | V2X-DSC: Multi-Agent Collaborative Perception with Distributed Source Coding Guided Communication | 提出 V2X-DSC，利用分布式信源编码视角进行带宽约束下的特征融合。 | 解决协作感知中密集 BEV 特征共享面临严格带宽约束的问题。 | 车路协同与协作感知 |
| 65 | http://arxiv.org/abs/2601.22041v1 | Learning to Communicate Across Modalities: Perceptual Heterogeneity in Multi-Agent Systems | 研究异构多步二元通信游戏，分析多模态系统如何在感知未对齐下收敛到一致消息。 | 解决现实设置中感知异质性被忽视的问题，研究跨模态表示适应。 | 多模态多智能体系统 |
| 66 | http://arxiv.org/abs/2601.22129v2 | Learning to Recommend Multi-Agent Subgraphs from Calling Trees | 将 MAS 中的代理推荐公式化为约束决策问题，基于历史调用树进行效用优化。 | 解决现有推荐系统无法处理代理编排的结构化、顺序和交互依赖 nature。 | 多智能体系统编排 |
| 67 | http://arxiv.org/abs/2601.22623v1 | SYMPHONY: Synergistic Multi-agent Planning with Heterogeneous Language Model Assembly | 提出 SYMPHONY，集成 heterogeneous 语言模型代理池， leveraging 多样推理模式。 | 解决单代理范式限制 exploration 能力及生成分支多样性不足问题。 | 多代理规划 |

[返回目录](#目录)

<a id="cat-03"></a>

## Agent工具使用与环境交互

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2601.00254v1 | An Empirical Evaluation of LLM-Based Approaches for Code Vulnerability Detection: RAG, SFT, and Dual-Agent Systems | 双Agent架构审计优化输出，RAG整合领域知识 | 代码漏洞检测中LLM实用性与准确性 | 软件安全与代码库检测 |
| 2 | http://arxiv.org/abs/2601.02046v3 | Agentic Retoucher for Text-To-Image Generation | 感知-推理-行动循环的层次化决策框架 | 文本到图像生成中的小规模失真问题 | T2I扩散模型后处理修正 |
| 3 | http://arxiv.org/abs/2601.02643v2 | AWARE-US: Preference-Aware Infeasibility Resolution in Tool-Calling Agents | 三种LLM方法从对话推断约束重要性 | 查询不可行时违反用户意图的松弛 | 结构化数据库工具调用Agent |
| 4 | http://arxiv.org/abs/2601.04888v1 | SmartSearch: Process Reward-Guided Query Refinement for Search Agents | 过程奖励+查询优化+三阶段课程学习框架 | 搜索Agent中间查询质量被忽视导致检索效果差 | 知识密集型搜索任务 |
| 5 | http://arxiv.org/abs/2601.05163v1 | DocDancer: Towards Agentic Document-Grounded Information Seeking | 工具驱动Agent框架显式建模文档探索与理解 | 现有DocQA Agent工具利用不足且依赖闭源模型 | 文档问答与信息检索 |
| 6 | http://arxiv.org/abs/2601.05432v1 | Thinking with Map: Reinforced Parallel Map-Augmented Agent for Geolocalization | 地图增强Agent循环+两阶段优化：Agent RL+并行测试时缩放 | 现有LVLM地理定位方法忽视人类常用地图策略 | 图像地理定位任务 |
| 7 | http://arxiv.org/abs/2601.07264v1 | The Confidence Dichotomy: Analyzing and Mitigating Miscalibration in Tool-Use Agents | 强化学习微调框架联合优化任务准确性和校准 | 工具使用Agent的言语校准动态未探索 | 工具集成Agent工作流 |
| 8 | http://arxiv.org/abs/2601.09750v1 | SAGE: Tool-Augmented LLM Task Solving Strategies in Scalable Multi-Agent Environments | 基于OPACA框架的工具发现执行，多Agent提示策略 | 领域特定工具集成困难，LLM理解使用不可靠 | 可扩展多Agent环境/SAGE接口 |
| 9 | http://arxiv.org/abs/2601.05808v1 | EnvScaler: Scaling Tool-Interactive Environments for LLM Agent via Programmatic Synthesis | 自动化框架通过程序化合成扩展工具交互环境规模。 | 解决 LLM Agent 训练缺乏丰富多样工具交互沙盒的问题。 | LLM Agent 训练环境构建 |
| 10 | http://arxiv.org/abs/2601.08259v1 | Unleashing Tool Engineering and Intelligence for Agentic AI in Next-Generation Communication Networks | 提出工具智能框架，桥接抽象推理与物理执行，涵盖工具全生命周期工程。 | 解决大模型从被动聊天到自主操作的能力 gap。 | 下一代通信网络 |
| 11 | http://arxiv.org/abs/2601.08276v1 | ToolACE-MCP: Generalizing History-Aware Routing from MCP Tools to the Agent Web | 提出历史感知路由管道，利用依赖图合成多轮轨迹训练轻量路由智能体。 | 解决开放生态中工具规模扩展性与通用性瓶颈。 | Agent Web 与 MCP 生态 |
| 12 | http://arxiv.org/abs/2601.09770v1 | GUI-Eyes: Tool-Augmented Perception for Visual Grounding in GUI Agents | 强化学习框架支持主动视觉感知，策略性调用裁剪或缩放工具增强观察。 | 解决 GUI 自动化中静态视觉输入及被动感知导致的信息不足问题。 | GUI 自动化任务 |
| 13 | http://arxiv.org/abs/2601.11109v2 | Vision-as-Inverse-Graphics Agent via Interleaved Multimodal Reasoning | 闭环写 - 跑 - 渲染 - 比较过程重建可编辑图形场景。 | 解决 VLM 缺乏细粒度空间物理 grounding 能力。 | 3D 重建与场景编辑 |
| 14 | http://arxiv.org/abs/2602.00028v1 | ELLMPEG: An Edge-based Agentic LLM Video Processing Tool | 边缘端 Agent 生成并验证 FFmpeg 视频处理命令。 | 解决云部署 LLM 高成本隐私风险及 API 依赖。 | 边缘视频处理 |
| 15 | http://arxiv.org/abs/2601.12146v2 | From LLMs to Agents in Programming: The Impact of Providing an LLM with a Compiler | 集成编译器使 LLM 迭代开发可运行程序。 | 解决生成代码质量不达标及编译失败问题。 | 软件开发 Agent |
| 16 | http://arxiv.org/abs/2603.06582v1 | Agentic SPARQL: Evaluating SPARQL-MCP-powered Intelligent Agents on the Federated KGQA Benchmark | 探索基于 SPARQL-MCP 的智能代理促进联合 SPARQL 查询 | 解决复杂任务需访问外部工具和数据源的问题 | 联合知识图谱问答 |
| 17 | http://arxiv.org/abs/2601.15356v2 | Q-Probe: Scaling Image Quality Assessment to High Resolution via Context-Aware Agentic Probing | 提出通过上下文感知探测将 IQA 扩展至高分辨率的代理框架 | 解决现有 RL 基于 IQA 模型依赖粗粒度全局视图问题 | 高分辨率图像质量评估 |
| 18 | http://arxiv.org/abs/2601.14790v1 | CI4A: Semantic Component Interfaces for Agents Empowering Web Automation | 引入语义封装机制将 UI 组件复杂交互逻辑抽象为工具原语 | 解决大模型处理细粒度低层 Web 组件操作受限问题 | Web 自动化代理 |
| 19 | http://arxiv.org/abs/2601.15724v1 | VideoThinker: Building Agentic VideoLLMs with LLM-Guided Tool Reasoning | 在caption空间生成多步工具使用序列，反演ground到视频 | 解决长视频理解中静态推理导致的时间定位弱和信息丢失 | 长形式视频理解 |
| 20 | http://arxiv.org/abs/2601.16206v2 | LLM-in-Sandbox Elicits General Agentic Intelligence | LLM在代码沙盒内探索，激发非代码领域通用智能 | 证明强LLM无需额外训练可利用沙盒完成非代码任务 | 跨领域通用agent智能 |
| 21 | http://arxiv.org/abs/2601.18305v1 | SwipeGen: Bridging the Execution Gap in GUI Agents via Human-like Swipe Synthesis | 合成类人滑动交互，提升 GUI 代理执行准确率 | 现有代理滑动策略简化，无法复制人类行为 | GUI 自动化交互 |
| 22 | http://arxiv.org/abs/2601.18543v2 | GenAgent: Scaling Text-to-Image Generation via Agentic Multimodal Reasoning | 代理多模态推理迭代 refine 输出，解耦理解与生成 | 统一模型训练成本高，理解生成权衡难 | 文本到图像生成 |
| 23 | http://arxiv.org/abs/2601.19066v1 | Dynamic Cogeneration of Bug Reproduction Test in Agentic Program Repair | 代理协同生成修复与 Bug 复现测试，减少工程 effort | 规范 APR 系统分离生成测试与修复，效率低 | 自动程序修复 |
| 24 | http://arxiv.org/abs/2601.17735v1 | ReFuGe: Feature Generation for Prediction Tasks on Relational Databases with LLM Agents | 代理框架生成信息关系特征，迭代反馈循环直至性能收敛 | 关系数据库预测任务生成特征需推理复杂模式无监督 | 关系数据库预测任务 |
| 25 | http://arxiv.org/abs/2601.20380v1 | OmegaUse: Building a General-Purpose GUI Agent for Autonomous Task Execution | 提出 OmegaUse，通用 GUI Agent，支持移动和桌面平台自主任务执行 | 解决 GUI Agent 跨终端能力评估与高效训练问题 | 通用计算机/手机操作任务 |
| 26 | http://arxiv.org/abs/2601.21123v2 | CUA-Skill: Develop Skills for Computer Using Agent | 构建 CUA-Skill 技能库，编码人类计算机交互知识为技能 | 解决现有 Agent 系统缺乏可复用结构化技能抽象问题 | 计算机使用 Agent (CUA) |
| 27 | http://arxiv.org/abs/2601.20144v2 | Trajectory2Task: Training Robust Tool-Calling Agents with Synthesized Yet Verifiable Data for Complex User Intents | 可验证数据生成流水线，覆盖模糊与不可行意图 | 真实场景中用户意图复杂且训练数据代表性不足 | 工具调用代理训练 |
| 28 | http://arxiv.org/abs/2601.20323v1 | ECG-Agent: On-Device Tool-Calling Agent for ECG Multi-Turn Dialogue | 首个 LLM 工具调用代理，支持多轮心电图对话 | 现有模型缺乏多轮对话与设备端效率 | 医疗心电图分析 |
| 29 | http://arxiv.org/abs/2602.00492v1 | HIDAgent: A Toolkit Enabling ""Personal Agents"" on HID-Compatible Devices | 开发 HIDAgent 工具包，使 UI 智能体通过模拟物理键鼠操作 HID 设备。 | 解决 UI 智能体控制依赖特定 API 限制平台及用例探索的问题。 | 个人智能体与 UI 自动化 |
| 30 | http://arxiv.org/abs/2602.00592v1 | DockSmith: Scaling Reliable Coding Environments via an Agentic Docker Builder | 提出 DockSmith，将环境构建作为核心智能体能力训练 Docker 构建。 | 解决可靠 Docker 环境构建是扩展执行接地训练与评估瓶颈的问题。 | 软件工程环境构建 |
| 31 | http://arxiv.org/abs/2601.22037v2 | Optimizing Agentic Workflows using Meta-tools | 引入 AWO 框架，识别并优化冗余工具执行模式，将其转换为确定性元工具。 | 解决代理工作流中迭代推理步骤多、成本高及幻觉导致失败的问题。 | 代理工作流优化 |
| 32 | http://arxiv.org/abs/2601.22352v1 | Recoverability Has a Law: The ERR Measure for Tool-Augmented Agents | 形式化可恢复性通过 ERR，推导其与效率分数的一阶关系，提出恢复动力学定律。 | 解决代理工具调用失败后自我恢复行为缺乏形式解释的问题。 | 工具增强代理 |
| 33 | http://arxiv.org/abs/2601.22571v2 | PerfGuard: A Performance-Aware Agent for Visual Content Generation | 提出 PerfGuard，系统 modeling 工具性能边界并集成到任务规划和调度中。 | 解决现有框架 assume 工具执行 invariably 成功且无法 adapt 迭代更新问题。 | 视觉内容生成 |
| 34 | http://arxiv.org/abs/2602.02548v1 | ToolTok: Tool Tokenization for Efficient and Generalizable GUI Agents | 提出 ToolTok， modeling 操作为 progressive 工具使用序列， devise 工具 aligned 人类交互习惯。 | 解决 coordinate-based 视觉 grounding 难以 generalize 及 coordinate-free 数据稀缺问题。 | GUI 智能体 |

[返回目录](#目录)

<a id="cat-04"></a>

## Agent评测与基准

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2601.00268v1 | Beyond Perfect APIs: A Comprehensive Evaluation of LLM Agents Under Real-World API Complexity | WildAGTEval基准涵盖60种API复杂度场景 | 理想化API假设与真实世界复杂性的差距 | LLM Agent函数调用能力评估 |
| 2 | http://arxiv.org/abs/2601.03281v1 | $α^3$-Bench: A Unified Benchmark of Safety, Robustness, and Efficiency for LLM-Based UAV Agents over 6G Networks | α³指标统一六维度评估，6G网络条件动态测试 | UAV Agent在真实网络约束下的安全性与效率 | 6G网络下的无人机自主任务 |
| 3 | http://arxiv.org/abs/2601.00481v1 | MAESTRO: Multi-Agent Evaluation Suite for Testing, Reliability, and Observability | 标准化MAS配置执行统一接口，导出框架无关执行轨迹 | MAS执行结构性稳定但时间可变导致性能差异 | LLM多Agent系统测试与可靠性 |
| 4 | http://arxiv.org/abs/2601.00596v1 | Beyond IVR: Benchmarking Customer Support LLM Agents for Business-Adherence | JourneyBench基准图表示生成支持场景，用户旅程覆盖评分 | 现有基准忽略多步策略遵循与任务依赖导航 | 客户服务LLM Agent业务合规性 |
| 5 | http://arxiv.org/abs/2603.04403v1 | FinRetrieval: A Benchmark for Financial Data Retrieval by AI Agents | 500金融检索问题基准，14配置Agent响应与工具调用轨迹 | 缺乏评估Agent从结构化数据库检索数值能力基准 | 金融研究AI Agent系统 |
| 6 | http://arxiv.org/abs/2601.06112v1 | ReliabilityBench: Evaluating LLM Agent Reliability Under Production-Like Stress Conditions | 统一可靠性表面R(k,ε,λ)，行动变形关系与混沌工程故障注入 | 现有基准仅报告单次运行成功率忽略生产可靠性 | LLM Agent生产环境压力测试 |
| 7 | http://arxiv.org/abs/2601.01366v1 | KGCE: Knowledge-Augmented Dual-Graph Evaluator for Cross-Platform Educational Agent Benchmarking with Multimodal Language Models | 知识库增强+双图评估框架分解子目标验证完成状态 | 现有基准缺乏教育场景跨平台任务细粒度评估 | 教育场景多模语言Agent |
| 8 | http://arxiv.org/abs/2601.02439v5 | WebGym: Scaling Training Environments for Visual Web Agents with Realistic Tasks | 近30万任务的大规模开源Web Agent训练环境 | 人工或小规模任务集不足以支持稳健策略学习 | 视觉Web Agent训练 |
| 9 | http://arxiv.org/abs/2601.02598v2 | LongDA: Benchmarking LLM Agents for Long-Document Data Analysis | 505个基于真实分析实践的查询基准 | 导航长文档与复杂数据是主要瓶颈 | 文档密集型数据分析 |
| 10 | http://arxiv.org/abs/2601.02854v1 | M3MAD-Bench: Are Multi-Agent Debates Really Effective Across Domains and Modalities? | 多领域多模态多维度统一可扩展基准 | 评估设置碎片化且限于单模态场景 | 多Agent辩论方法评估 |
| 11 | http://arxiv.org/abs/2601.02941v1 | SastBench: A Benchmark for Testing Agentic SAST Triage | 真实CVE作为真阳性+过滤SAST发现作为假阳性 | 现有基准无法模拟真实SAST发现分布 | SAST三 Agent测试 |
| 12 | http://arxiv.org/abs/2601.03113v1 | A Probabilistic Digital Twin of UK En Route Airspace for Training and Evaluating AI Agents for Air Traffic Control | 首个概率数字孪生+结构化保证案例 | 安全关键领域AI Agent开发与评估环境 | 空中交通管制Agent |
| 13 | http://arxiv.org/abs/2601.04790v1 | Belief in Authority: Impact of Authority in Multi-Agent Evaluation Framework | 首次系统分析多Agent评估中基于角色的权威偏差 | 多Agent系统中权威角色对交互影响未探索 | 多Agent评估框架设计 |
| 14 | http://arxiv.org/abs/2601.05039v1 | FinDeepForecast: A Live Multi-Agent System for Benchmarking Deep Research Agents in Financial Forecasting | 首个实时端到端多Agent系统自动生成金融预测任务基准 | 金融领域深度研究Agent预测性能缺乏全面实时评估 | 金融预测研究与Agent基准测试 |
| 15 | http://arxiv.org/abs/2601.05111v1 | Agent-as-a-Judge | 首次全面综述Agent-as-a-Judge演进，建立发展分类法 | 缺乏统一框架导航Agent评估系统快速演进的格局 | AI评估与Agent评估系统 |
| 16 | http://arxiv.org/abs/2601.03515v1 | Mem-Gallery: Benchmarking Multimodal Long-Term Conversational Memory for MLLM Agents | 多模态长程对话记忆基准，评估提取推理管理。 | 现有基准缺乏多模态长程记忆评估能力。 | 多模态大语言模型代理 |
| 17 | http://arxiv.org/abs/2601.03556v1 | Do Autonomous Agents Contribute Test Code? A Study of Tests in Agentic Pull Requests | 实证研究代理 PR 中的测试代码包含情况。 | 理解代理驱动工作流中的测试行为与质量。 | 自主软件开发与测试 |
| 18 | http://arxiv.org/abs/2601.03731v2 | From Laboratory to Real-World Applications: Benchmarking Agentic Code Reasoning at the Repository Level | 白盒诊断基准，执行驱动变异验证仓库级推理。 | 现有基准缺乏真实仓库级逻辑一致性评估。 | 代码推理与软件工程代理 |
| 19 | http://arxiv.org/abs/2601.04288v1 | Human-in-the-Loop Testing of AI Agents for Air Traffic Control with a Regulated Assessment Framework | 基于 regulator-certified 模拟器的代理评估框架。 | 学术评估与实际空管操作环境不一致。 | 空中交通管制代理评估 |
| 20 | http://arxiv.org/abs/2601.04126v2 | InfiniteWeb: Scalable Web Environment Synthesis for GUI Agent Training | 自动生成大规模功能 web 环境用于训练。 | 解决 GUI 代理训练缺乏合适环境的问题。 | GUI 代理训练环境 |
| 21 | http://arxiv.org/abs/2601.04424v1 | Gavel: Agent Meets Checklist for Evaluating LLMs on Long-Context Legal Summarization | 基于 checklist 的多值评估框架与代理 scaffold。 | 长上下文法律摘要缺乏细粒度评估方法。 | 法律摘要与长上下文评估 |
| 22 | http://arxiv.org/abs/2602.17669v1 | Evaluating Text-based Conversational Agents for Mental Health: A Systematic Review of Metrics, Methods and Usage Contexts | 系统综述心理健康对话代理评估指标方法。 | 评估实践碎片化，缺乏文化适应性。 | 心理健康对话代理 |
| 23 | http://arxiv.org/abs/2601.07136v1 | A Large-Scale Study on the Development and Issues of Multi-Agent AI Systems | 首个大规模开源MAS实证研究，分析42K提交和4.7K问题 | 多Agent系统发展和维护实践缺乏了解 | LangChain/CrewAI/AutoGen等开源MAS |
| 24 | http://arxiv.org/abs/2601.07367v2 | FOCAL: A Novel Benchmarking Technique for Multi-modal Agents | 端到端推理基准和组件级误差传播分析框架 | 多模态Agent级联管道误差传播 | 多模态Agent（语音+文本） |
| 25 | http://arxiv.org/abs/2601.07651v2 | Active Evaluation of General Agents: Problem Definition and Comparison of Baseline Algorithms | 主动评估形式化定义和概念框架，在线排名算法比较 | 通用Agent评估复杂度和成本显著上升 | 通用Agent评估/Elo和Soft Condorcet |
| 26 | http://arxiv.org/abs/2601.08118v2 | MirrorBench: A Benchmark to Evaluate Conversational User-Proxy Agents for Human-Likeness | 三词汇多样性指标和三LLM评判指标，人机校准控制 | 用户代理Agent产生冗长不真实话语 | 对话用户代理Agent/MirrorBench |
| 27 | http://arxiv.org/abs/2601.08173v1 | The Agent's First Day: Benchmarking Learning, Exploration, and Scheduling in the Workplace Scenarios | 动态评估环境模拟"受训"Agent持续探索新设置 | 现有研究忽略随机真实世界部署的鲁棒性 | 工作场所场景/EvoEnv |
| 28 | http://arxiv.org/abs/2601.19935v1 | Mem2ActBench: A Benchmark for Evaluating Long-Term Memory Utilization in Task-Oriented Autonomous Agents | 评估Agent主动利用长期记忆执行工具动作的能力 | 现有基准仅测试被动检索孤立事实 | 任务导向自主Agent/2029个会话 |
| 29 | http://arxiv.org/abs/2601.05899v1 | TowerMind: A Tower Defence Game Learning Environment and Benchmark for LLM as Agents | 轻量级塔防游戏环境，支持多模态观察与 LLM 规划能力评估。 | 提供低计算需求且支持文本观察的 RTS 游戏 Agent 基准。 | LLM 规划与决策能力评估 |
| 30 | http://arxiv.org/abs/2601.06328v1 | ToolGym: an Open-world Tool-using Environment for Scalable Agent Testing and Data Curation | 开放世界工具使用环境，合成多工具工作流注入中断测试鲁棒性。 | 解决工具使用 Agent 在开放世界设置中测试与训练数据缺乏问题。 | 工具使用 Agent 测试与训练 |
| 31 | http://arxiv.org/abs/2601.06663v2 | SafePro: Evaluating the Safety of Professional-Level AI Agents | 综合基准评估专业活动中 AI Agent 的安全对齐与风险。 | 填补现有安全评估未覆盖专业设置复杂决策过程的空白。 | 专业级 AI Agent 安全评估 |
| 32 | http://arxiv.org/abs/2601.06818v1 | AgentHallu: Benchmarking Automated Hallucination Attribution of LLM-based Agents | 综合基准评估 LLM Agent 多步工作流中幻觉步骤定位与归因。 | 填补多步工作流中诊断幻觉起源步骤的研究任务空白。 | LLM Agent 幻觉检测与归因 |
| 33 | http://arxiv.org/abs/2601.06943v1 | Watching, Reasoning, and Searching: A Video Deep Research Benchmark on Open Web for Agentic Video Reasoning | 首个视频深度研究基准，要求跨帧视觉锚点提取与交互式 Web 检索。 | 解决真实视频问答中答案分布开放 Web 需多跳推理验证的 gap。 | 视频深度研究 Agent |
| 34 | http://arxiv.org/abs/2601.07880v1 | Sola-Visibility-ISPM: Benchmarking Agentic AI for Identity Security Posture Management Visibility | 首个基准评估 Agentic AI 系统在真实企业身份环境中的可见性任务。 | 解决缺乏标准化方式评估 Agentic AI 系统执行 ISPM 可见性任务。 | 身份安全姿态管理 |
| 35 | http://arxiv.org/abs/2601.08406v1 | WebTrap Park: An Automated Platform for Systematic Security Evaluation of Web Agents | 实例化三大安全风险源为 1226 个可执行任务，实现无需修改智能体的动作评估。 | 解决 Web 智能体安全评估碎片化与难以标准化问题。 | Web 智能体安全 |
| 36 | http://arxiv.org/abs/2601.08462v1 | M3-BENCH: Process-Aware Evaluation of LLM Agents Social Behaviors in Mixed-Motive Games | 提出过程感知评估框架，协同分析行为轨迹、推理过程与通信内容。 | 解决现有基准忽视决策推理与交互过程信息的问题。 | 混合动机游戏中的智能体 |
| 37 | http://arxiv.org/abs/2601.08470v1 | Towards Safer Mobile Agents: Scalable Generation and Evaluation of Diverse Scenarios for VLMs | 利用图像编辑模型生成包含异常物体的可扩展危险场景基准 MovSafeBench。 | 解决现有基准覆盖多样 hazardous 场景不足的问题。 | 视觉语言模型与移动系统 |
| 38 | http://arxiv.org/abs/2601.08536v2 | DeepResearch Bench II: Diagnosing Deep Research Agents via Rubrics from Expert Report | 基于专家报告构建 9430 个细粒度二元 rubrics，评估信息召回、分析与展示。 | 解决深度研究系统评估标准粗糙及 LLM 自评偏差问题。 | 深度研究系统 |
| 39 | http://arxiv.org/abs/2601.08988v1 | ART: Action-based Reasoning Task Benchmarking for Medical AI Agents | 挖掘真实 EHR 数据创建挑战任务，针对检索、聚合与条件逻辑错误。 | 解决现有基准不足以评估医疗智能体基于动作的推理性能问题。 | 医疗 AI 智能体 |
| 40 | http://arxiv.org/abs/2601.09032v1 | The Hierarchy of Agentic Capabilities: Evaluating Frontier Models on Realistic RL Environments | 提出实证推导的智能体能力层级，评估前沿模型在真实工作场所任务表现。 | 解决从单轮响应评估到多步任务完成评估的转型问题。 | 真实工作场所环境 |
| 41 | http://arxiv.org/abs/2601.09393v1 | AI-NativeBench: An Open-Source White-Box Agentic Benchmark Suite for AI-Native Systems | 引入首个以应用为中心的白色盒基准，基于 MCP 与 A2A 标准分析工程特征。 | 解决传统黑盒评估范式对系统级执行动态盲目问题。 | AI-Native 系统 |
| 42 | http://arxiv.org/abs/2601.12369v2 | Can Deep Research Agents Retrieve and Organize? Evaluating the Synthesis Gap with Expert Taxonomies | 提出TaxoBench基准，评估Agent检索和组织能力 | 现有基准忽视层级分类结构，无法评估Agent核心能力 | 深度研究Agent系统 |
| 43 | http://arxiv.org/abs/2601.12661v1 | MedConsultBench: A Full-Cycle, Fine-Grained, Process-Aware Benchmark for Medical Consultation Agents | 原子信息单元追踪，22项细粒度指标 | 现有评测忽视端到端流程完整性和临床安全 | 医疗咨询Agent系统 |
| 44 | http://arxiv.org/abs/2601.13217v1 | Beyond Single-shot Writing: Deep Research Agents are Unreliable at Multi-turn Report Revision | Mr Dre多轮报告修订评估套件 | 现有基准忽视迭代修订，Agent修订时内容回退 | 深度研究Agent系统 |
| 45 | http://arxiv.org/abs/2601.13243v1 | A Comprehensive Evaluation of LLM Reasoning: From Single-Model to Multi-Agent Paradigms | MIMeBench基准评估语义抽象和对比判别能力 | 推理范式效果与成本权衡不清楚，缺乏开放基准 | LLM推理系统评估 |
| 46 | http://arxiv.org/abs/2601.13295v2 | CooperBench: Why Coding Agents Cannot be Your Teammates Yet | CooperBench协作编码基准，揭示协调诅咒 | 编码Agent协作时成功率下降30%，缺乏社交智能 | 协作编码Agent系统 |
| 47 | http://arxiv.org/abs/2601.13591v1 | DSAEval: Evaluating Data Science Agents on a Wide Range of Real-World Data Science Problems | DSAEval基准641问题，多模态感知+多查询交互 | 数据科学问题开放无标准答案，评估困难 | 数据科学Agent系统 |
| 48 | http://arxiv.org/abs/2601.09503v1 | What Do LLM Agents Know About Their World? Task2Quiz: A Paradigm for Studying Environment Understanding | 提出 Task2Quiz 范式，解耦任务执行与世界状态理解，自动化评估环境认知。 | 解决现有评估仅关注任务成功而忽视环境理解 grounding 的问题。 | LLM 智能体环境理解能力 |
| 49 | http://arxiv.org/abs/2601.11637v1 | Evaluating Self-Correcting Vision Agents Through Quantitative and Qualitative Metrics | 引入诊断微基准，解耦任务成功率与修正成功率，量化修正收益递减。 | 解决多模态智能体自我修正能力缺乏定量极限与瓶颈表征的问题。 | 视觉语言智能体自我修正 |
| 50 | http://arxiv.org/abs/2601.09688v1 | DeepResearchEval: An Automated Framework for Deep Research Task Construction and Agentic Evaluation | persona-driven 任务生成，自适应点对点质量评估及主动事实核查。 | 解决深度研究系统评估依赖静态维度及缺失引用时事实验证难的问题。 | 深度研究智能体评估 |
| 51 | http://arxiv.org/abs/2601.09937v1 | From SERPs to Agents: A Platform for Comparative Studies of Information Interaction | UXLab 系统支持无代码配置实验设计，可视化管理从招募到后端比较。 | 解决部署管理不同信息访问系统进行对比用户研究的技术 overhead 障碍。 | 信息交互用户研究 |
| 52 | http://arxiv.org/abs/2601.10343v2 | OctoBench: Benchmarking Scaffold-Aware Instruction Following in Repository-Grounded Agentic Coding | 基准测试 scaffold-aware 指令遵循，提供自动化观察评分工具包。 | 解决编码 scaffold 指定指令遵循能力未被充分检查及约束异构持久问题。 | 仓库 grounded 代理编码 |
| 53 | http://arxiv.org/abs/2601.10504v1 | DR-Arena: an Automated Evaluation Framework for Deep Research Agents | 全自动评估框架，构建实时信息树，自适应演化循环动态升级任务复杂度。 | 解决当前基准依赖静态数据集导致任务通用性有限及时态不对齐问题。 | 深度研究代理能力评估 |
| 54 | http://arxiv.org/abs/2601.11044v2 | AgencyBench: Benchmarking the Frontiers of Autonomous Agents in 1M-Token Real-World Contexts | 综合基准评估 6 种核心能力，含 1M token 长上下文。 | 解决现有基准缺乏长周期真实场景评估问题。 | 自主 Agent 能力评估 |
| 55 | http://arxiv.org/abs/2601.11077v1 | ABC-Bench: Benchmarking Agentic Backend Coding in Real-World Development | 评估 Agent 后端编码全生命周期及容器化部署。 | 解决现有基准忽视动态环境和全流程工程要求。 | 后端开发 Agent 评估 |
| 56 | http://arxiv.org/abs/2601.11354v1 | AstroReason-Bench: Evaluating Unified Agentic Planning across Heterogeneous Space Planning Problems | 评估 Agent 在物理约束空间规划问题中的表现。 | 解决现有基准缺乏物理约束真实领域探索。 | 太空规划问题评估 |
| 57 | http://arxiv.org/abs/2601.11421v1 | The Great March 100: 100 Detail-oriented Tasks for Evaluating Embodied AI Agents | 100 个细节导向任务评估具身 Agent 长尾行为。 | 解决现有数据集任务设计缺乏系统性原则。 | 具身机器人学习 |
| 58 | http://arxiv.org/abs/2601.11854v2 | ATOD: An Evaluation Framework and Benchmark for Agentic Task-Oriented Dialogue Systems | 基准与评估框架支持长程推理与多目标协调。 | 解决现有基准缺乏对 Agent 行为系统支持。 | 任务导向对话系统 |
| 59 | http://arxiv.org/abs/2601.11868v1 | Terminal-Bench: Benchmarking Agents on Hard, Realistic Tasks in Command Line Interfaces | 89 个命令行硬任务基准评估真实工作流能力。 | 解决现有基准不够难或无法测量真实任务。 | 命令行 Agent 评估 |
| 60 | http://arxiv.org/abs/2601.11903v1 | AEMA: Verifiable Evaluation Framework for Trustworthy and Controlled Agentic LLM Systems | 过程感知可审计框架聚合多步评估记录。 | 解决企业级多 Agent 评估缺乏稳定性与自动化。 | 可信 Agent 系统评估 |
| 61 | http://arxiv.org/abs/2601.12294v1 | ToolPRMBench: Evaluating and Advancing Process Reward Models for Tool-using Agents | 大规模基准评估工具使用 Agent 的过程奖励模型。 | 解决缺乏系统可靠评估 PRM 的基准。 | 工具使用 Agent 评估 |
| 62 | http://arxiv.org/abs/2601.12346v1 | MMDeepResearch-Bench: A Benchmark for Multimodal Deep Research Agents | 评估多模态理解与引用接地报告生成的基准。 | 解决现有基准缺失端到端多模态证据使用。 | 深度研究 Agent 评估 |
| 63 | http://arxiv.org/abs/2601.13722v1 | OP-Bench: Benchmarking Over-Personalization for Memory-Augmented Personalized Conversational Agents | 形式化过度个性化为三种类型并构建包含 1700 实例的基准测试 | 解决现有基准忽视个性化使用是否适当的问题 | 记忆增强对话代理 |
| 64 | http://arxiv.org/abs/2601.13880v1 | LifeAgentBench: A Multi-dimensional Benchmark and Agent for Personal Health Assistants in Digital Health | 引入大规模 QA 基准用于长周期跨维度生活方式健康推理 | 解决当前大模型在此设置下能力缺乏系统基准的问题 | 数字健康个人助理 |
| 65 | http://arxiv.org/abs/2601.14242v3 | APEX-Agents | 引入 AI 生产力指数基准评估代理执行长周期跨应用任务 | 解决缺乏评估代理在真实工作环境执行能力的基准 | 投资银行/咨询/法律任务 |
| 66 | http://arxiv.org/abs/2601.14691v2 | Gaming the Judge: Unfaithful Chain-of-Thought Can Undermine Agent Evaluation | 展示 LLM 法官易受代理推理轨迹操纵 | 解决非可验证设置中依赖代理轨迹判断的假设脆弱性 | 代理评估可靠性 |
| 67 | http://arxiv.org/abs/2601.15679v1 | Improving Methodologies for Agentic Evaluations Across Domains: Leakage of Sensitive Information, Fraud and Cybersecurity Threats | 国际网络联合测试，对齐多国资深AI测量评估方法 | 理解agentic测试方法论问题，推进评估科学发展 | 跨领域agent安全评估 |
| 68 | http://arxiv.org/abs/2601.15777v1 | UXCascade: Scalable Usability Testing with Simulated User Agents | 多层次分析工作流提取聚合agent生成的可用性反馈 | 解决模拟用户agent输出非结构化导致可操作洞察模糊问题 | UX可用性测试 |
| 69 | http://arxiv.org/abs/2601.16280v1 | When Agents Fail to Act: A Diagnostic Framework for Tool Invocation Reliability in Multi-Agent LLM Systems | 12类错误分类体系，系统性评估1980个确定性测试实例 | 评估智能agent系统程序可靠性，识别生产部署可靠性阈值 | 企业自动化多agent系统 |
| 70 | http://arxiv.org/abs/2601.16344v1 | DSGym: A Holistic Framework for Evaluating and Training Data Science Agents | 标准化框架评估训练数据科学agent，模块化架构易扩展 | 解决现有基准评估接口碎片化、任务覆盖窄、数据 grounding缺乏 | 数据科学agent评估与训练 |
| 71 | http://arxiv.org/abs/2601.17087v2 | Lost in Simulation: LLM-Simulated Users are Unreliable Proxies for Human Users in Agentic Evaluations | 跨四国用户研究，发现LLM模拟用户缺乏稳健性且存在系统性校准偏差 | 揭示当前评估实践可能 misrepresent agent能力 across diverse用户群体 | agent评估中的用户模拟 |
| 72 | http://arxiv.org/abs/2601.18137v1 | DeepPlanning: Benchmarking Long-Horizon Agentic Planning with Verifiable Constraints | 引入全局约束优化基准，评估长程规划能力 | 现有基准忽视全局约束与主动信息收集 | 长程任务规划评估 |
| 73 | http://arxiv.org/abs/2601.18225v1 | ShopSimulator: Evaluating and Exploring RL-Driven LLM Agent for Shopping Assistants | 大规模中文购物仿真环境，评估 RL 驱动代理 | 缺乏统一仿真环境捕捉个性化与多轮对话 | 电商购物助手评估 |
| 74 | http://arxiv.org/abs/2601.18341v1 | Agentic Much? Adoption of Coding Agents on GitHub | 大规模实证分析 GitHub 编码代理采用率与影响 | 缺乏对新兴编码代理实际采用情况的研究 | 软件开发生态分析 |
| 75 | http://arxiv.org/abs/2601.18345v1 | Promises, Perils, and (Timely) Heuristics for Mining Coding Agent Activity | 文档挖掘编码代理活动的启发式方法与风险 | 缺乏研究编码代理对软件工程实践的影响 | 软件仓库挖掘 |
| 76 | http://arxiv.org/abs/2601.18700v1 | TEA-Bench: A Systematic Benchmarking of Tool-enhanced Emotional Support Dialogue Agent | 首个工具增强情感支持对话代理交互基准 | 现有系统忽视外部工具在情感支持中的事实 grounding | 情感支持对话评估 |
| 77 | http://arxiv.org/abs/2601.18749v1 | Let's Make Every Pull Request Meaningful: An Empirical Analysis of Developer and Agentic Pull Requests | 实证分析开发者与代理 PR 的合并结果差异 | 代理生成 PR 合并率低于人类，质量需提升 | 软件开发协作分析 |
| 78 | http://arxiv.org/abs/2601.19120v3 | RobustExplain: Evaluating Robustness of LLM-Based Explanation Agents for Recommendation | 系统评估框架测量 LLM 推荐解释的鲁棒性 | 用户行为噪声导致解释稳定性与信任担忧 | 推荐系统解释评估 |
| 79 | http://arxiv.org/abs/2601.16685v1 | AgentsEval: Clinically Faithful Evaluation of Medical Imaging Reports via Multi-Agent Reasoning | 多智能体流式推理框架，模拟放射科医生协作诊断流程 | 医疗报告生成评估缺乏临床逻辑和可信度 | 医疗影像报告生成系统 |
| 80 | http://arxiv.org/abs/2601.16690v1 | EMemBench: Interactive Benchmarking of Episodic Memory for VLM Agents | 基于智能体轨迹生成问题的程序化基准，覆盖多种记忆技能 | 长时记忆评估缺乏交互性和可控性 | VLM 智能体长时记忆能力 |
| 81 | http://arxiv.org/abs/2601.16964v1 | AgentDrive: An Open Benchmark Dataset for Agentic AI Reasoning with LLM-Generated Scenarios in Autonomous Systems | 30 万 LLM 生成驾驶场景基准，因子化场景空间与多维推理测试 | 缺乏大规模结构化安全关键基准训练评估自主智能体 | 自动驾驶系统推理能力 |
| 82 | http://arxiv.org/abs/2601.16973v1 | VisGym: Diverse, Customizable, Scalable Environments for Multimodal Agents | 17 个环境健身房，覆盖符号谜题到导航操作，提供多步求解器 | 多模态模型在多步视觉交互中表征不足 | 多模态智能体训练与评估 |
| 83 | http://arxiv.org/abs/2601.17722v1 | EntWorld: A Holistic Environment and Benchmark for Verifiable Enterprise GUI Agents | 大规模企业 GUI 智能体基准，基于 schema 逆向工程业务逻辑 | 现有基准未捕捉专业企业工作流复杂性与严谨性 | 企业级数字智能体评估 |
| 84 | http://arxiv.org/abs/2601.18827v1 | Automated structural testing of LLM-based agents: methods, framework, and case studies | 利用 traces 捕获轨迹，mocking  enforce 可复现行为，添加 assertions 自动化验证 | 当前测试方法依赖手动评估，难自动化根因分析 | LLM 基于智能体测试 |
| 85 | http://arxiv.org/abs/2601.20412v1 | Beyond Accuracy: A Cognitive Load Framework for Mapping the Capability Boundaries of Tool-use Agents | 引入认知负荷框架，分解任务复杂度为内在和外在负荷 | 揭示工具使用 Agent 的真实能力边界与瓶颈 | 工具使用型 AI Agent 评估 |
| 86 | http://arxiv.org/abs/2601.20613v2 | AgentIF-OneDay: A Task-level Instruction-Following Benchmark for General AI Agents in Daily Scenarios | 构建 AgentIF-OneDay 基准，覆盖日常工作生活学习多样任务 | 评估通用 Agent 在日常生活场景中的指令跟随能力 | 通用 AI Agent 日常任务处理 |
| 87 | http://arxiv.org/abs/2601.20617v1 | Agent Benchmarks Fail Public Sector Requirements | 定义公共部门 Agent 基准标准，分析现有基准不足 | 确保 Agent 基准满足公共部门法律与程序要求 | 公共部门 AI Agent 部署 |
| 88 | http://arxiv.org/abs/2601.20650v2 | OS-Marathon: Benchmarking Computer-Use Agents on Long-Horizon Repetitive Tasks | 建立 OS-Marathon 基准，评估长周期重复性计算机使用任务 | 解决长周期重复工作流缺乏评估基准的问题 | 专业场景下的计算机使用 Agent |
| 89 | http://arxiv.org/abs/2601.20730v3 | AgentLongBench: A Controllable Long Benchmark For Long-Contexts Agents via Environment Rollouts | 通过环境 rollout 评估长上下文 Agent，模拟动态交互 | 揭示 Agent 在动态信息合成而非静态检索上的弱点 | 长上下文自主 Agent |
| 90 | http://arxiv.org/abs/2601.20975v1 | DeepSearchQA: Bridging the Comprehensiveness Gap for Deep Research Agents | 构建 DeepSearchQA 基准，评估多步信息搜索任务的 exhaustive 答案 | 测试 Agent 系统性整理碎片信息与推理停止标准能力 | 深度研究与信息搜索 Agent |
| 91 | http://arxiv.org/abs/2601.21570v1 | EmboCoach-Bench: Benchmarking AI Agents on Developing Embodied Robots | 构建 EmboCoach-Bench，评估 Agent 自主工程具身策略能力 | 解决具身 AI  scaling 依赖人工监督与调参瓶颈 | 具身机器人策略开发 |
| 92 | http://arxiv.org/abs/2601.21800v2 | BioAgent Bench: An AI Agent Evaluation Suite for Bioinformatics | 引入 BioAgent Bench，评估 Agent 在生物信息学任务性能 | 解决生物信息学工作流中 Agent 鲁棒性与隐私评估缺失 | 生物信息学 AI Agent |
| 93 | http://arxiv.org/abs/2601.19507v1 | Automated Safety Benchmarking: A Multi-agent Pipeline for LVLMs | 四代理协作流水线，自动化构建高质量安全基准 | 现有 LVLM 安全基准构建耗时且静态复杂 | 大视觉语言模型安全评估 |
| 94 | http://arxiv.org/abs/2601.19583v1 | Toward Architecture-Aware Evaluation Metrics for LLM Agents | 架构感知评估方法，链接组件与可观察行为 | 现有评估忽略架构组件对行为的影响 | LLM 代理系统评估 |
| 95 | http://arxiv.org/abs/2601.20882v1 | DevOps-Gym: Benchmarking AI Agents in Software DevOps Cycle | 首个端到端基准，评估代理在 DevOps 核心工作流能力 | 现有基准缺乏 DevOps 环境与工具接口 | 软件 DevOps 周期自动化 |
| 96 | http://arxiv.org/abs/2601.20886v2 | IDE-Bench: Evaluating Large Language Models as IDE Agents on Real-World Software Engineering Tasks | IDE 原生工具接口基准，评估真实软件工程任务 | 缺乏评估 AI IDE 代理在真实全栈环境的框架 | 集成开发环境 (IDE) 代理 |
| 97 | http://arxiv.org/abs/2602.00133v1 | PredictionMarketBench: A SWE-bench-Style Framework for Backtesting Trading Agents on Prediction Markets | 预测市场交易代理基准，事件驱动回放历史数据 | 缺乏评估算法与 LLM 交易代理的标准框架 | 预测市场交易策略 |
| 98 | http://arxiv.org/abs/2601.20316v1 | Less is More: Benchmarking LLM Based Recommendation Agents | 系统基准测试，挑战长上下文优于短上下文假设 | 推荐代理中上下文长度与质量关系不明 | LLM 推荐系统 |
| 99 | http://arxiv.org/abs/2601.20335v2 | MobileBench-OL: A Comprehensive Chinese Benchmark for Evaluating Mobile GUI Agents in Real-World Environment | 在线基准，包含噪声鲁棒性与复杂推理评估 | 现有基准忽略真实环境噪声与推理能力 | 移动 GUI 代理评估 |
| 100 | http://arxiv.org/abs/2601.22984v1 | Why Your Deep Research Agent Fails? On Hallucination Evaluation in Full Research Trajectory | 提出 PIES 分类法与 DeepHalluBench，审计全研究轨迹中的幻觉。 | 解决现有基准仅评估结果而忽略中间过程幻觉积累的问题。 | 深度研究智能体评估 |
| 101 | http://arxiv.org/abs/2602.00352v1 | DETOUR: An Interactive Benchmark for Dual-Agent Search and Reasoning | 引入 DETOUR 基准，模拟双智能体多轮对话搜索过程评估回忆能力。 | 解决现有基准局限于单轮设置无法真实模拟 tip-of-the-tongue 搜索的问题。 | 信息检索与对话智能体 |
| 102 | http://arxiv.org/abs/2602.00409v1 | Are Coding Agents Generating Over-Mocked Tests? An Empirical Study | 实证研究编码智能体生成测试中 mock 的使用情况及其质量影响。 | 解决智能体生成测试过度使用 mock 导致测试难维护及验证效果差的问题。 | 软件测试与编码智能体 |
| 103 | http://arxiv.org/abs/2602.00456v1 | Benchmarking Agents in Insurance Underwriting Environments | 提出 UNDERWRITE 基准，模拟真实企业挑战评估保险承保智能体。 | 解决现有基准缺乏专有业务知识及真实复杂性导致评估不现实的问题。 | 保险承保与企业应用 |
| 104 | http://arxiv.org/abs/2602.00575v1 | Agentic Reward Modeling: Verifying GUI Agent via Online Proactive Interaction | 引入 VAGEN，利用验证智能体主动探测环境证据评估 GUI 任务。 | 解决被动视觉观察无法捕捉潜在系统状态导致评估不准确的问题。 | GUI 智能体评估与验证 |
| 105 | http://arxiv.org/abs/2601.21872v1 | WebArbiter: A Principle-Guided Reasoning Process Reward Model for Web Agents | 提出基于原则的推理过程奖励模型，生成结构化理由并给出偏好裁决，支持推理时扩展。 | 解决基于结果的监督稀疏延迟问题，提供可解释的推理过程奖励信号。 | Web 导航智能体 |
| 106 | http://arxiv.org/abs/2601.21961v2 | How do Visual Attributes Influence Web Agents? A Comprehensive Evaluation of User Interface Design Factors | 引入 VAF 评估管道，量化网页视觉属性因素如何影响 Web 智能体决策。 | 解决对视觉属性如何塑造智能体决策缺乏系统理解的问题。 | Web 智能体与 UI 设计 |
| 107 | http://arxiv.org/abs/2601.22027v1 | CAR-bench: Evaluating the Consistency and Limit-Awareness of LLM Agents under Real-World Uncertainty | 引入 CAR-bench，评估车载助手领域智能体的一致性、不确定性处理和能力意识。 | 解决现有基准忽略现实世界用户-facing 应用中可靠性问题。 | 车载语音助手 |

[返回目录](#目录)

<a id="cat-05"></a>

## Agent学习与自进化

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2601.00290v1 | ClinicalReTrial: A Self-Evolving AI Agent for Clinical Trial Protocol Optimization | 闭环奖励驱动优化框架，层次化记忆捕获迭代反馈 | 临床试验协议设计缺陷导致失败 | 药物研发临床试验优化 |
| 2 | http://arxiv.org/abs/2601.01126v2 | RoboPhD: Self-Improving Text-to-SQL Through Autonomous Agent Evolution | ELO选择机制适者生存，18次迭代从70行进化到1500行 | Text-to-SQL性能提升需大量人工指导 | Text-to-SQL系统自主改进 |
| 3 | http://arxiv.org/abs/2601.01498v1 | From Failure to Mastery: Generating Hard Samples for Tool-use Agents | HardGen动态API图基于失败案例合成硬轨迹，闭环评估反馈 | 现有数据生成方法产生简单同质轨迹缺乏复杂逻辑依赖 | 工具使用Agent训练数据生成 |
| 4 | http://arxiv.org/abs/2601.04237v1 | SAGE-32B: Agentic Reasoning via Iterative Distillation | 迭代蒸馏两阶段训练，逆推理方法预测规划潜在失败 | 聊天模型缺乏Agent循环任务分解工具使用错误恢复 | Agent推理与长程规划任务 |
| 5 | http://arxiv.org/abs/2601.02201v1 | CORE: Code-based Inverse Self-Training Framework with Graph Expansion for Virtual Agents | 语义代码抽象自动推断奖励函数+策略图扩展 | 行为克隆多样性低与强化学习奖励设计依赖 | 多模态虚拟Agent训练 |
| 6 | http://arxiv.org/abs/2601.03192v2 | MemRL: Self-Evolving Agents via Runtime Reinforcement Learning on Episodic Memory | 非参数方法+两阶段检索机制 | 微调计算昂贵与现有记忆方法检索噪声 | Agent运行时持续改进 |
| 7 | http://arxiv.org/abs/2601.03641v2 | Agent-Dice: Disentangling Knowledge Updates via Geometric Consensus for Agent Continual Learning | 几何共识过滤冲突梯度，曲率加权共享语义。 | 解决代理持续学习中的稳定性与可塑性 dilemma。 | 代理持续学习与知识更新 |
| 8 | http://arxiv.org/abs/2601.03743v1 | O-Researcher: An Open Ended Deep Research Model via Multi-Agent Distillation and Agentic RL | 多代理蒸馏合成研究数据，结合 RL 训练。 | 解决开源模型缺乏高质量研究级训练数据。 | 开源大模型研究与训练 |
| 9 | http://arxiv.org/abs/2601.03790v2 | NeoAMT: Neologism-Aware Agentic Machine Translation with Reinforcement Learning | 基于 Wiktionary 搜索工具，RL 训练新词翻译。 | 解决含新词句子的机器翻译质量低下。 | 机器翻译与新词处理 |
| 10 | http://arxiv.org/abs/2601.04611v1 | Character-R1: Enhancing Role-Aware Reasoning in Role-Playing Agents via RLVR | RLVR 增强角色感知推理，综合奖励信号。 | 角色扮演代理缺乏内部认知一致性。 | 角色扮演代理 |
| 11 | http://arxiv.org/abs/2601.04620v1 | AgentDevel: Reframing Self-Evolving LLM Agents as Release Engineering | 将代理进化重构为发布工程，回归感知。 | 代理自改进轨迹不稳定且难审计。 | 代理开发与发布工程 |
| 12 | http://arxiv.org/abs/2601.07232v1 | Yes FLoReNce, I Will Do Better Next Time! Agentic Feedback Reasoning for Humorous Meme Detection | 闭环学习中推理Agent受评判Agent批判，反馈存入知识库 | 幽默理解缺乏自我批判和推理 refinement 能力 | 幽默模因检测/PrideMM数据集 |
| 13 | http://arxiv.org/abs/2601.07262v2 | ColorBrowserAgent: Complex Long-Horizon Browser Agent with Adaptive Knowledge Evolution | 人在回路知识适应和知识对齐渐进摘要双机制 | 网站异质性和长程交互不稳定性 | Web自动化/WebArena和WebChoreArena |
| 14 | http://arxiv.org/abs/2601.08158v1 | WISE-Flow: Workflow-Induced Structured Experience for Self-Evolving Conversational Service Agents | 工作流中心框架将历史交互转化为可复用程序经验 | 服务Agent易错、重复失败模式、运行变异性大 | 用户-facing服务环境/ToolSandbox |
| 15 | http://arxiv.org/abs/2601.05787v2 | From Off-Policy to On-Policy: Enhancing GUI Agents via Bi-level Expert-to-Policy Assimilation | 双层专家到策略同化，将静态专家轨迹转化为策略对齐指导。 | 解决 GUI Agent 训练中专家轨迹与学习者分布不匹配问题。 | 图形用户界面自动化 Agent |
| 16 | http://arxiv.org/abs/2601.06021v1 | Chaining the Evidence: Robust Reinforcement Learning for Deep Search Agents with Citation-Aware Rubric Rewards | 引用感知 Rubric 奖励，强调推理全面性与证据链连接。 | 解决深度搜索 Agent 中奖励稀疏导致的捷径利用与幻觉问题。 | 深度搜索与 research Agent |
| 17 | http://arxiv.org/abs/2601.09742v1 | Adaptive Orchestration: Scalable Self-Evolving Multi-Agent Systems | 动态专家混合架构，实时对话分析 hiring 专用子 Agent。 | 解决单体 Agent 上下文污染与静态 Agent 群延迟资源开销问题。 | 可扩展自进化多 Agent 系统 |
| 18 | http://arxiv.org/abs/2601.06794v1 | No More Stale Feedback: Co-Evolving Critics for Open-World Agent Learning | 共同进化评论家框架，同步优化策略与评论家避免反馈过时。 | 解决在线 RL 中静态评论家无法适应策略演变导致反馈效用下降。 | 开放世界 Agent 强化学习 |
| 19 | http://arxiv.org/abs/2601.06860v2 | ET-Agent: Incentivizing Effective Tool-Integrated Reasoning Agent via Behavior Calibration | 行为校准训练框架，通过自进化数据飞轮校准工具使用行为。 | 解决 TIR 任务中 Agent 行为模式无效如冗余或不足工具调用问题。 | 工具集成推理 Agent |
| 20 | http://arxiv.org/abs/2601.06922v1 | TreePS-RAG: Tree-based Process Supervision for Reinforcement Learning in Agentic RAG | 在线基于树的 RL 框架，通过蒙特卡洛估计实现细粒度过程优势。 | 解决 Agentic RAG 中仅依赖稀疏最终奖励限制逐步信用分配问题。 | 检索增强生成 (RAG) Agent |
| 21 | http://arxiv.org/abs/2601.07055v1 | Dr. Zero: Self-Evolving Search Agents without Training Data | 无数据自进化框架，Proposer 与 Solver 自动课程 refinement。 | 解决多轮搜索 Agent 在无训练数据下自进化问题多样性与计算成本。 | 无训练数据搜索 Agent |
| 22 | http://arxiv.org/abs/2601.08271v1 | Sparsity Is Necessary: Polynomial-Time Stability for Agentic LLMs in Large Action Spaces | 形式化稀疏智能体控制，证明稀疏策略在巨大动作空间下的多项式时间稳定性。 | 解决大动作空间下提示词控制器的不稳定性问题。 | 工具增强型 LLM 系统 |
| 23 | http://arxiv.org/abs/2601.08280v1 | Greedy Is Enough: Sparse Action Discovery in Agentic LLMs | 将动作发现 formulate 为块稀疏恢复问题，证明贪心算法可高效恢复相关动作集。 | 解决巨大动作空间中仅小部分动作有效的筛选问题。 | 工具增强型语言模型 |
| 24 | http://arxiv.org/abs/2601.08605v1 | ExpSeek: Self-Triggered Experience Seeking for Web Agents | shift 经验干预为步级主动寻求，利用熵阈值确定干预时机与内容。 | 解决被动注入经验无法适应动态上下文观察的问题。 | Web 智能体 |
| 25 | http://arxiv.org/abs/2601.08955v2 | Imagine-then-Plan: Agent Learning from Adaptive Lookahead with World Models | 提出统一框架，通过自适应前瞻机制与世界模型交互生成想象轨迹。 | 解决复杂任务规划下世界模型潜力未充分利用问题。 | 智能体学习任务 |
| 26 | http://arxiv.org/abs/2601.11631v1 | Compress to Focus: Efficient Coordinate Compression for Policy Optimization in Multi-Turn GUI Agents | 提出坐标压缩策略优化，耦合视觉压缩与策略优化以缓解上下文膨胀。 | 解决多轮 GUI 智能体交互历史积累导致严重上下文膨胀问题。 | 多轮 GUI 智能体 |
| 27 | http://arxiv.org/abs/2601.09259v1 | MAXS: Meta-Adaptive Exploration with LLM Agents | 采用前瞻策略扩展推理路径，结合轨迹收敛机制控制计算成本。 | 解决代理推理中局部短视生成及轨迹不稳定性问题。 | 多工具推理任务 |
| 28 | http://arxiv.org/abs/2601.12988v1 | PaperGuide: Making Small Language-Model Paper-Reading Agents More Efficient | Draft-and-Follow策略优化，分层RL缩小知行差距 | 现有方法探索过度低效，依赖重工程提示 | 论文阅读Agent系统 |
| 29 | http://arxiv.org/abs/2601.13060v1 | MagicGUI-RMS: A Multi-Agent Reward Model System for Self-Evolving GUI Agents via Automated Feedback Reflux | 领域+通用双奖励模型，自动数据回流机制 | GUI Agent轨迹评估依赖人工，训练数据难以规模化 | 自进化GUI交互Agent |
| 30 | http://arxiv.org/abs/2601.13572v1 | Behavior Knowledge Merge in Reinforced Agentic Models | RAM分布感知合并框架，分离共享/独特参数更新 | 现有合并方法针对SFT，RL任务向量稀疏导致稀释 | 多任务强化Agent模型合并 |
| 31 | http://arxiv.org/abs/2601.09515v1 | SERM: Self-Evolving Relevance Model with Agent-Driven Learning from Massive Query Streams | 多代理模块挖掘分布 shifts 样本，两级 agreement 框架提供可靠伪标签。 | 解决大规模查询流中信息样本稀疏及伪标签不可靠的自进化难题。 | 工业级搜索相关性模型 |
| 32 | http://arxiv.org/abs/2601.09694v1 | LLMs can Compress LLMs: Adaptive Pruning by Agents | 基础模型作为自适应修剪代理，智能选择层修剪，保留关键知识路径。 | 解决修剪后 LLM 事实知识严重退化及依赖均匀启发式确定稀疏率问题。 | LLM 模型压缩与修剪 |
| 33 | http://arxiv.org/abs/2601.11658v1 | Towards AGI A Pragmatic Approach Towards Self Evolving Agent | 分层自进化多智能体框架，集成课程学习与遗传算法。 | 解决部署后 Agent 能力静态无法自主扩展问题。 | 通用人工智能系统 |
| 34 | http://arxiv.org/abs/2601.11100v1 | ReCreate: Reasoning and Creating Domain Agents Driven by Experience | 经验驱动框架，利用交互历史自动创建领域 Agent。 | 解决人工设计 Agent 劳动密集且难以适应任务。 | 领域 Agent 自动创建 |
| 35 | http://arxiv.org/abs/2601.13702v1 | IGAA: Intent-Driven General Agentic AI for Edge Services Scheduling using Generative Meta Learning | 利用元学习范式使代理能从 prior 经验中持续学习以实现泛化调度 | 解决现有调度代理缺乏对新场景泛化能力的问题 | 边缘服务调度 |
| 36 | http://arxiv.org/abs/2601.14349v1 | MARBLE: Multi-Agent Reasoning for Bioinformatics Learning and Evolution | 耦合文献感知参考选择与结构化辩论驱动架构推理 | 解决生物信息学模型改进缓慢、劳动密集及难复现问题 | 生物信息学模型优化 |
| 37 | http://arxiv.org/abs/2601.14615v1 | SearchGym: Bootstrapping Real-World Search Agents via Cost-Effective and High-Fidelity Environment Simulation | 提出模拟环境通过严格生成管道构建可验证知识图谱 | 解决通过 RL 训练搜索代理面临的高成本及数据不对齐 | 现实世界搜索代理 |
| 38 | http://arxiv.org/abs/2601.15120v2 | Emerging from Ground: Addressing Intent Deviation in Tool-Using Agents via Deriving Real Calls into Virtual Trajectories | RISE方法从真实工具调用合成虚拟轨迹和负样本 | 解决工具使用agent的意图偏差和评估困难问题 | 工具使用智能体训练 |
| 39 | http://arxiv.org/abs/2601.15808v1 | Inference-Time Scaling of Verification: Self-Evolving Deep Research Agents via Test-Time Rubric-Guided Verification | DeepVerifier基于rubric的验证器，测试时自进化无需额外训练 | 解决深度研究agent策略能力提升依赖后训练的问题 | 自动化知识发现与问题解决 |
| 40 | http://arxiv.org/abs/2601.15876v2 | EvoCUA: Evolving Computer Use Agents via Learning from Scalable Synthetic Experience | 数据生成与策略优化整合到自持续进化循环，可扩展沙盒rollout | 解决静态数据缩放限制，捕获长程计算机任务因果动态 | 原生计算机使用agent |
| 41 | http://arxiv.org/abs/2601.16443v3 | Endless Terminals: Scaling RL Environments for Terminal Agents | 全自动pipeline程序化生成终端使用任务，无需人工标注 | 解决当前终端基准为评估而非训练设计，RL需要可扩展pipeline | 终端使用agent训练 |
| 42 | http://arxiv.org/abs/2601.16489v1 | EvoConfig: Self-Evolving Multi-Agent Systems for Efficient Autonomous Environment Configuration | 专家诊断模块细粒度执行后分析，自进化机制实时动态调整修复优先级 | 解决大规模环境配置低效，难以处理复杂错误导致配置失败 | 软件工程师任务运行环境配置 |
| 43 | http://arxiv.org/abs/2601.16530v1 | Curate-Train-Refine: A Closed-Loop Agentic Framework for Zero Shot Classification | 迭代agentic循环中LLM策划训练数据，分析成功失败，合成针对性样本 | 解决LLM和高容量编码器推理成本延迟限制实际部署问题 | 零样本分类任务 |
| 44 | http://arxiv.org/abs/2601.18202v1 | SAGE: Steerable Agentic Data Generation for Deep Search with Execution Feedback | 代理管道自动生成难度可控的深度搜索 QA 对 | 人工标注深搜数据成本高，轨迹复杂 | 深度搜索代理训练数据 |
| 45 | http://arxiv.org/abs/2601.18217v1 | Paying Less Generalization Tax: A Cross-Domain Generalization Study of RL Training for LLM Agents | 识别状态信息丰富度与规划复杂度影响跨域泛化 | 代理在未知测试域泛化能力不足 | RL 训练策略优化 |
| 46 | http://arxiv.org/abs/2601.18226v2 | Yunjue Agent Tech Report: A Fully Reproducible, Zero-Start In-Situ Self-Evolving Agent System for Open-Ended Tasks | 原位自进化范式，迭代合成优化工具无监督学习 | 开放环境中任务分布漂移，外部监督稀缺 | 开放任务自进化系统 |
| 47 | http://arxiv.org/abs/2601.18418v2 | daVinci-Dev: Agent-native Mid-training for Software Engineering | 代理原生中期训练，利用环境原生轨迹数据 | 静态训练数据与动态开发环境分布不匹配 | 软件工程代理训练 |
| 48 | http://arxiv.org/abs/2601.18467v2 | OffSeeker: Online Reinforcement Learning Is Not All You Need for Deep Research Agents | 离线训练套件生成大规模研究查询与轨迹 | 在线 RL 成本高，高质量研究轨迹稀缺 | 深度研究代理训练 |
| 49 | http://arxiv.org/abs/2601.18510v1 | Just-In-Time Reinforcement Learning: Continual Learning in LLM Agents Without Gradient Updates | 测试时策略优化无需梯度更新，动态记忆经验 | 部署后权重冻结导致持续适应困难 | 代理持续学习 |
| 50 | http://arxiv.org/abs/2602.13218v1 | Scaling the Scaling Logic: Agentic Meta-Synthesis of Logic Reasoning | 代理元合成框架，迭代合成修复可执行生成器 - 验证器程序对 | 逻辑推理训练信号扩展受限，依赖专家代码 | 逻辑推理模型训练数据合成 |
| 51 | http://arxiv.org/abs/2601.17332v1 | TheoremForge: Scaling up Formal Data Synthesis with Low-Budget Agentic Workflow | 低成本形式数据合成管道，解耦提取策略从失败轨迹恢复信号 | 形式数学智能体工作流成本高，开源语料稀缺 | 形式数学模型训练数据合成 |
| 52 | http://arxiv.org/abs/2601.17596v1 | Learning to Ideate for Machine Learning Engineering Agents | 双智能体框架分离构思与实现，RL 训练构思器生成更有效想法 | 现有 MLE 智能体难以迭代优化实现算法有效性 | 机器学习工程智能体 |
| 53 | http://arxiv.org/abs/2601.17829v1 | Linguistic and Argument Diversity in Synthetic Data for Function-Calling Agents | 优化通用多样性指标生成合成数据集，无需手工规则 | 函数调用代理训练缺乏高质量多样数据 | 函数调用智能体训练 |
| 54 | http://arxiv.org/abs/2601.20714v1 | Adapting the Behavior of Reinforcement Learning Agents to Changing Action Spaces and Reward Functions | 提出 MORPHIN 框架，支持 Reward 和动作空间变化的在线适应 | 解决 RL Agent 在非平稳环境中的适应与遗忘问题 | 动态环境下的强化学习 Agent |
| 55 | http://arxiv.org/abs/2601.20732v3 | Continual GUI Agents | 提出 GUI-AiF 框架，通过新奖励稳定 GUI 分布shift 下的持续学习 | 解决 GUI 环境变化导致 Agent 性能下降问题 | 持续学习的 GUI 操作 Agent |
| 56 | http://arxiv.org/abs/2601.20789v2 | SERA: Soft-Verified Efficient Repository Agents | 提出 SERA 方法，低成本训练专用代码仓库 Agent | 解决开源代码 Agent 训练成本高与私有库 specialization 难问题 | 私有代码库专用的编码 Agent |
| 57 | http://arxiv.org/abs/2601.21557v2 | Meta Context Engineering via Agentic Skill Evolution | 提出 MCE 框架，协同进化 CE 技能与上下文 artifacts | 超越静态上下文工程启发式，优化推理时上下文 | 大语言模型推理时上下文优化 |
| 58 | http://arxiv.org/abs/2601.21558v2 | ASTRA: Automated Synthesis of agentic Trajectories and Reinforcement Arenas | 提出 ASTRA，全自动端到端框架训练工具增强 Agent | 解决工具使用 Agent 训练依赖人工与非验证环境问题 | 工具增强语言模型 Agent |
| 59 | http://arxiv.org/abs/2601.19290v1 | MetaGen: Self-Evolving Roles and Topologies for Multi-Agent LLM Reasoning | 推理时自适应角色空间和协作拓扑，无需训练 | 固定角色库导致任务不匹配及推理成本过高问题 | 多智能体复杂推理任务 |
| 60 | http://arxiv.org/abs/2601.20209v1 | Spark: Strategic Policy-Aware Exploration via Dynamic Branching for Long-Horizon Agentic Learning | 关键状态动态分支探索，资源高效采样 | 长 horizon 任务训练缺乏高质量轨迹且资源浪费 | 具身规划与强化学习 |
| 61 | http://arxiv.org/abs/2601.20375v1 | LLM-AutoDP: Automatic Data Processing via LLM Agents for Model Fine-tuning | 代理自动生成优化数据处理策略，无需人工干预 | 领域数据低质量样本处理成本高且涉及隐私 | 模型微调数据预处理 |
| 62 | http://arxiv.org/abs/2601.22964v1 | EvoClinician: A Self-Evolving Agent for Multi-Turn Medical Diagnosis via Test-Time Evolutionary Learning | 提出“诊断 - 评分 - 进化”循环，使智能体在测试时自我进化诊断策略。 | 解决医疗 AI 缺乏多轮问诊能力及资源管理效率低的问题。 | 多轮医疗诊断系统 |
| 63 | http://arxiv.org/abs/2602.02559v1 | Experience-Driven Multi-Agent Systems Are Training-free Context-aware Earth Observers | 引入 GeoEvolver，通过结构化交互获取地球观测 expertise 无需参数更新。 | 解决智能体缺乏细粒度工具级 expertise 导致执行错误传播的问题。 | 地球观测与遥感任务 |
| 64 | http://arxiv.org/abs/2602.00359v2 | Position: Agentic Evolution is the Path to Evolving LLMs | 主张智能体进化是 LLM 适应开放环境的必然路径，提出 A-Evolve 框架。 | 解决静态训练无法跟上持续部署环境变化导致 train-deploy 差距的问题。 | LLM 持续适应与进化 |
| 65 | http://arxiv.org/abs/2601.22136v1 | SWE-Replay: Efficient Test-Time Scaling for Software Engineering Agents | 引入 SWE-Replay，通过回收先前试验轨迹，动态选择探索或利用 archived 经验。 | 解决软件工程代理测试时扩展计算成本高及价值估计噪声问题。 | 软件工程智能体 |
| 66 | http://arxiv.org/abs/2601.22154v1 | DynaWeb: Model-Based Reinforcement Learning of Web Agents | 引入 DynaWeb，通过与世界模型交互训练 Web 代理，支持 simulated interaction。 | 解决与 live internet 交互低效、成本高且风险大的训练挑战。 | Web 智能体训练 |
| 67 | http://arxiv.org/abs/2601.22436v2 | Large Language Model Agents Are Not Always Faithful Self-Evolvers | 系统调查经验忠实性，发现代理 consistently 依赖 raw 经验但 often  disregard  condensed 经验。 | 解决自进化代理是否 faithfully 依赖给定经验指导行为 unclear 的问题。 | 自进化 LLM 代理 |
| 68 | http://arxiv.org/abs/2601.22491v1 | SSL: Sweet Spot Learning for Differentiated Guidance in Agentic Optimization | 引入 SSL，通过 progressively amplified, tiered 奖励引导策略 toward 解空间 sweet-spot 区域。 | 解决现有方法 employ 二元奖励无法 capture 相同结果轨迹质量差异问题。 | 代理优化 |
| 69 | http://arxiv.org/abs/2601.22511v2 | Mock Worlds, Real Skills: Building Small Agentic Language Models with Synthetic Tasks, Simulated Environments, and Rubric-Based Rewards | 提出 SYNTHAGENT，jointly 合成多样工具使用训练数据并模拟完整环境。 | 解决开源代理训练数据狭窄及真实 API 缺乏多样性不稳定问题。 | 小型代理语言模型 |
| 70 | http://arxiv.org/abs/2601.22607v3 | From Self-Evolving Synthetic Data to Verifiable-Reward RL: Post-Training Multi-turn Interactive Tool-Using Agents | 提出统一框架结合 self-evolving 数据代理与 verifier-based RL，合成 tool-grounded 对话。 | 解决高质量多轮工具使用数据合成难扩展及 RL 信号噪声问题。 | 多轮交互式工具代理 |
| 71 | http://arxiv.org/abs/2601.22758v1 | AutoRefine: From Trajectories to Reusable Expertise for Continual LLM Agent Refinement | 引入 AutoRefine，提取并维护 dual-form 经验模式， continuous  maintenance 机制防止 repository 退化。 | 解决代理 fail  to  accumulate  knowledge 及经验积累导致 repository 退化问题。 | 持续 LLM 代理 refinement |
| 72 | http://arxiv.org/abs/2601.22781v1 | Learning with Challenges: Adaptive Difficulty-Aware Data Generation for Mobile GUI Agent Training | 提出 MobileGen， adaptively  align 训练难度与 GUI 代理 capability  frontier。 | 解决现有方法 lack  fine-grained 控制 task 难度限制 learning  effectiveness 问题。 | 移动 GUI 代理训练 |

[返回目录](#目录)

<a id="cat-06"></a>

## 多Agent强化学习

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2601.00321v1 | Offline Multi-Agent Reinforcement Learning for 6G Communications: Fundamentals, Applications and Future Directions | 基于保守Q学习的离线MARL算法，元学习适应动态环境 | 在线RL在多Agent环境中的成本与安全性限制 | 6G通信网络资源管理 |
| 2 | http://arxiv.org/abs/2601.00538v2 | Parametrized Sharing for Multi-Agent Hybrid DRL for Multiple Multi-Functional RISs-Aided Downlink NOMA Networks | 参数化共享多Agent混合DRL，PPO+DQN处理连续离散变量 | 多MF-RIS辅助NOMA网络能效最大化 | 无线通信下行链路网络 |
| 3 | http://arxiv.org/abs/2601.01155v2 | ORION: Option-Regularized Deep Reinforcement Learning for Cooperative Multi-Agent Online Navigation | 选项批评家框架学习高层协作模式，双阶段协作策略 | 部分已知环境中多Agent导航需平衡路径最优与信息共享 | 仓库工厂多机器人协作导航 |
| 4 | http://arxiv.org/abs/2601.06122v1 | COVR:Collaborative Optimization of VLMs and RL Agent for Visual-Based Control | VLM与RL策略协作优化相互增强，探索驱动动态过滤器 | 视觉RL样本效率低，现有工作忽略RL数据增强VLM | 视觉控制任务 |
| 5 | http://arxiv.org/abs/2601.02449v2 | Stigmergic Swarming Agents for Fast Subgraph Isomorphism | 蚁群优化启发的 stigmergy 群体搜索方法 | NP完全子图同构问题的指数级复杂度 | 图匹配与模式识别 |
| 6 | http://arxiv.org/abs/2601.03301v1 | PC2P: Multi-Agent Path Finding via Personalized-Enhanced Communication and Crowd Perception | 个性化增强通信+局部人群感知+区域死锁破解 | 分布式MAPF在多样环境条件下扩展不足 | 多Agent路径规划 |
| 7 | http://arxiv.org/abs/2601.04767v1 | AT²PO: Agentic Turn-based Policy Optimization via Tree Search | 轮次级树结构+熵引导树扩展+轮次信用分配 | 多轮Agent RL探索多样性有限与信用分配稀疏 | 多轮任务Agent强化学习 |
| 8 | http://arxiv.org/abs/2601.05087v1 | Online Bayesian Learning of Agent Behavior in Differential Games | 在线贝叶斯博弈论方法识别多Agent动力系统行为 | 有限噪声数据下Agent行为预测与不确定性量化 | 自适应交互与实时决策 |
| 9 | http://arxiv.org/abs/2601.05407v1 | Interactive Distillation for Cooperative Multi-Agent Reinforcement Learning | HINT框架：分层RL教师+伪离策略RL+性能过滤 | 知识蒸馏在MARL中面临教师策略合成与观察空间不匹配 | 合作多Agent强化学习 |
| 10 | http://arxiv.org/abs/2601.05427v2 | Betting on Equilibrium: Monitoring Strategic Behavior in Multi-Agent Systems | 序贯测试框架监测重复博弈中观察行为是否与均衡一致 | 多Agent系统中行为漂移实时检测仍是开放挑战 | 多Agent系统战略行为监测 |
| 11 | http://arxiv.org/abs/2601.05509v1 | How Exploration Breaks Cooperation in Shared-Policy Multi-Agent Reinforcement Learning | 揭示共享策略DQN中标准探索导致合作系统性崩溃 | 共享策略MARL在动态社会困境中的根本失败模式 | 社会与经济环境中多Agent学习系统 |
| 12 | http://arxiv.org/abs/2601.03451v1 | Microeconomic Foundations of Multi-Agent Learning | 提出两阶段激励模型，实现次线性社会福利遗憾。 | 解决市场内生数据下多智能体学习的激励对齐。 | 市场与保险中的 AI 系统 |
| 13 | http://arxiv.org/abs/2601.04177v2 | Hierarchical GNN-Based Multi-Agent Learning for Dynamic Queue-Jump Lane and Emergency Vehicle Corridor Formation | 分层 GNN 多代理 RL，协调应急车道形成。 | 现有策略无法适应动态交通拥堵条件。 | 智能交通与应急车辆 |
| 14 | http://arxiv.org/abs/2601.04401v1 | Transformer-based Multi-agent Reinforcement Learning for Separation Assurance in Structured and Unstructured Airspaces | Transformer 编码器 MARL，相对极化状态空间。 | 现有 MARL 过拟合特定空域结构，泛化差。 | 空中交通分离保证 |
| 15 | http://arxiv.org/abs/2601.07122v1 | Enhancing Cloud Network Resilience via a Robust LLM-Empowered Multi-Agent Reinforcement Learning Framework | LLM赋能的分层多Agent强化学习框架，含HITL支持 | 云网络防御策略缺乏鲁棒性和可解释性 | 云网络安全防御/CyberOps-Bots |
| 16 | http://arxiv.org/abs/2601.07142v1 | Dynamics of Multi-Agent Actor-Critic Learning in Stochastic Games: from Multistability and Chaos to Stable Cooperation | 熵正则化驱动动力学收敛，揭示直接互惠与合作涌现的联系 | 多Agent强化学习中稳健协调与合作的挑战 | 随机博弈/Actor-Critic智能体 |
| 17 | http://arxiv.org/abs/2601.07152v1 | Agents of Diffusion: Enhancing Diffusion Language Models with Multi-Agent Reinforcement Learning for Structured Data Generation | 提示优化Agent与评判Agent协作引导扩散模型生成 | 扩散语言模型缺乏结构保持的归纳偏置 | 结构化数据生成/JSON记录生成 |
| 18 | http://arxiv.org/abs/2601.07376v1 | OpenTinker: Separating Concerns in Agentic Reinforcement Learning | 算法设计、执行和Agent-环境交互关注点分离 | 依赖单体端到端RL管道 | LLM Agent强化学习基础设施 |
| 19 | http://arxiv.org/abs/2601.07463v2 | Puzzle it Out: Local-to-Global World Model for Offline Multi-Agent Reinforcement Learning | 局部到全局世界模型，不确定性感知采样机制 | 离线MARL策略过于保守难以泛化 | 离线多Agent强化学习/LOGO框架 |
| 20 | http://arxiv.org/abs/2601.07516v1 | Controlling Multimodal Conversational Agents with Coverage-Enhanced Latent Actions | 学习紧凑潜在动作空间，跨模态投影器增强覆盖 | RL微调MCAs面临极大文本token空间挑战 | 多模态对话Agent |
| 21 | http://arxiv.org/abs/2601.06425v1 | HiDVFS: A Hierarchical Multi-Agent DVFS Scheduler for OpenMP DAG Workloads | 分层多 Agent DVFS 调度器，基于性能感知优化任务分配。 | 解决多核嵌入式系统中泄漏功耗与过热导致的性能问题。 | 并行系统任务调度 |
| 22 | http://arxiv.org/abs/2601.06485v1 | Coupling Smoothed Particle Hydrodynamics with Multi-Agent Deep Reinforcement Learning for Cooperative Control of Point Absorbers | 耦合 SPH 与多 Agent 深度强化学习，实现波浪能转换器协同控制。 | 解决波浪能转换器阵列中复杂非线性交互导致效率低的问题。 | 海洋波浪能 harvesting |
| 23 | http://arxiv.org/abs/2601.06487v2 | ArenaRL: Scaling RL for Open-Ended Agents via Tournament-based Relative Ranking | 基于锦标赛相对排名的 RL 范式，shift 从点对点评分到组内排序。 | 解决开放端 Agent 任务中奖励模型区分度坍塌与优化停滞问题。 | 开放端复杂任务 Agent |
| 24 | http://arxiv.org/abs/2601.08327v1 | Safe Heterogeneous Multi-Agent RL with Communication Regularization for Coordinated Target Acquisition | 引入图通信与轨迹感知安全过滤器，集成异构智能体协同获取目标。 | 解决部分可观测下异构团队协同目标获取的安全性与稳定性。 | 多智能体协同环境 |
| 25 | http://arxiv.org/abs/2601.12518v1 | Cooperative Multi-agent RL with Communication Constraints | 基策略预测技术减少通信轮次 | 通信受限时重要性采样不稳定，梯度估计失效 | 分布式多Agent强化学习系统 |
| 26 | http://arxiv.org/abs/2601.12886v1 | Communication Methods in Multi-Agent Reinforcement Learning | 29篇文献综述，评估五类通信方法优劣 | 缺乏通信方法系统对比和标准化基准 | 多Agent强化学习研究者 |
| 27 | http://arxiv.org/abs/2601.13642v1 | Sample Complexity of Average-Reward Q-Learning: From Single-agent to Federated Reinforcement Learning | 首个联邦Q学习算法，证明样本和通信复杂度 | 平均奖励设置下Q学习理论保证有限 | 联邦多Agent强化学习 |
| 28 | http://arxiv.org/abs/2601.09667v2 | Collaborative Multi-Agent Test-Time Reinforcement Learning for Reasoning | 测试时注入结构化文本经验，多专家团队讨论达成共识，避免训练不稳定。 | 解决多代理强化学习训练资源密集、不稳定及奖励稀疏高方差问题。 | 复杂推理任务多智能体 |
| 29 | http://arxiv.org/abs/2601.11401v1 | Factored Value Functions for Graph-Based Multi-Agent Reinforcement Learning | 扩散价值函数分解全局价值，适配图结构 MDP。 | 解决大规模 MARL 中信用分配与全局价值弱信号。 | 图基于多智能体 RL |
| 30 | http://arxiv.org/abs/2601.11809v1 | Multi-agent DRL-based Lane Change Decision Model for Cooperative Planning in Mixed Traffic | 混合多智能体车道变更决策模型促进协作编队。 | 解决混合交通中 CAV 稀疏分布难形成编队。 | 混合交通流规划 |
| 31 | http://arxiv.org/abs/2602.13211v1 | An Overlay Multicast Routing Method Based on Network Situational Aware-ness and Hierarchical Multi-Agent Reinforcement Learning | 分层多智能体 RL 优化覆盖多播路由路径规划。 | 解决传统 OM 不适应动态流量及多目标耦合。 | 网络路由优化 |
| 32 | http://arxiv.org/abs/2601.15141v1 | CLEANER: Self-Purified Trajectories Boost Agentic Reinforcement Learning | SAAR机制利用自纠错能力构建纯净轨迹，自适应替换粒度 | 解决小参数模型探索阶段执行失败导致的噪声轨迹问题 | 参数受限的Agent强化学习 |
| 33 | http://arxiv.org/abs/2601.17069v1 | Multi-Agent Deep Reinforcement Learning Under Constrained Communications | D-GAT通过多跳通信执行全局状态推断，完全分布式DG-MAPPO | 消除对集中式训练或全局可观测性的依赖，仅通过peer-to-peer通信 | 分布式多agent协作任务 |
| 34 | http://arxiv.org/abs/2601.18284v1 | VissimRL: A Multi-Agent Reinforcement Learning Framework for Traffic Signal Control Based on Vissim | 封装 Vissim 接口提供标准化多代理训练环境 | 高保真模拟器在 RL 研究中利用不足 | 交通信号控制 |
| 35 | http://arxiv.org/abs/2601.18419v1 | Emergent Cooperation in Quantum Multi-Agent Reinforcement Learning Using Communication | 通信协议促进量子多代理强化学习 emergent cooperation | 量子多代理强化学习中通信研究有限 | 量子多代理系统 |
| 36 | http://arxiv.org/abs/2601.18580v1 | K-Myriad: Jump-starting reinforcement learning with unsupervised parallel agents | 无监督并行代理最大化集体状态熵，多样化探索 | 并行化通常忽视多样化探索策略优势 | 强化学习初始化 |
| 37 | http://arxiv.org/abs/2601.18733v1 | Advances and Innovations in the Multi-Agent Robotic System (MARS) Challenge | 多代理机器人系统挑战赛，评估具身规划与控制 | 多代理协作在复杂任务场景中面临挑战 | 具身多代理机器人 |
| 38 | http://arxiv.org/abs/2601.17454v1 | Embodiment-Induced Coordination Regimes in Tabular Multi-Agent Q-Learning | 表格多智能体 Q 学习中评估体现约束对协调机制的影响 | 集中式价值学习在体现约束下优势未受控测试 | 多智能体强化学习协调理论 |
| 39 | http://arxiv.org/abs/2601.17678v1 | DIML: Differentiable Inverse Mechanism Learning from Behaviors of Multi-Agent Learning Trajectories | 基于似然框架区分多智能体学习动态模型，从行为恢复机制 | 现有方法难以从观察设置推断非结构化机制 | 多智能体激励机制学习 |
| 40 | http://arxiv.org/abs/2601.17687v2 | Agentic reinforcement learning empowers next-generation chemical language models for molecular design and synthesis | 利用代理强化学习解耦化学推理与知识存储，本地小模型高性能 | 小模型幻觉与大模型隐私成本间的权衡 | 分子设计与化学合成 |
| 41 | http://arxiv.org/abs/2601.20578v2 | Inequality in Congestion Games with Learning Agents | 建模不同学习率的通勤者为 RL Agent，分析网络扩展的不平等 | 揭示交通网络扩展中效率与公平的权衡 | 交通拥堵博弈与通勤策略 |
| 42 | http://arxiv.org/abs/2601.21523v1 | Explicit Credit Assignment through Local Rewards and Dependence Graphs in Multi-Agent Reinforcement Learning | 利用交互图区分个体贡献，结合全局与局部奖励优点 | 解决 MARL 中全局奖励噪声大与局部奖励次优问题 | 多 Agent 强化学习协作 |
| 43 | http://arxiv.org/abs/2601.19388v2 | Judgelight: Trajectory-Level Post-Optimization for Multi-Agent Path Finding via Closed-Subwalk Collapsing | 轨迹后优化层，折叠闭合子路径去除冗余移动 | 学习式 MAPF 求解器轨迹存在不必要振荡运动 | 仓库自动化与多机器人协调 |
| 44 | http://arxiv.org/abs/2602.00558v1 | NetWorld: Communication-Based Diffusion World Model for Multi-Agent Reinforcement Learning in Wireless Networks | 提出 NetWorld，基于扩散世界模型实现无线网络 MARL 少 Shot 泛化。 | 解决 MARL 需要昂贵真实交互及缺乏跨任务泛化能力的问题。 | 无线网络资源分配 |
| 45 | http://arxiv.org/abs/2602.00766v1 | Communications-Incentivized Collaborative Reasoning in NetGPT through Agentic Reinforcement Learning | 提出 NetGPT 框架，通过智能体强化学习优化协作推理策略。 | 解决通信系统中 AI 部署孤立缺乏内在适应性及多智能体协作的问题。 | 下一代无线通信网络 |
| 46 | http://arxiv.org/abs/2601.21919v1 | Self-Compression of Chain-of-Thought via Multi-Agent Reinforcement Learning | 提出 SCMA 框架，通过分割和评分 Agent 选择性惩罚冗余块，保留关键逻辑。 | 解决推理冗余导致的推断开销问题，平衡简洁性与准确性。 | 大型推理模型 |
| 47 | http://arxiv.org/abs/2601.21972v3 | Learning Decentralized LLM Collaboration with Multi-Agent Actor Critic | 提出 MAAC 方法优化去中心化 LLM 协作，分析集中式与去中心化批评者的优劣。 | 解决预定义执行协议依赖中心化及蒙特卡洛方法高方差问题。 | 去中心化 LLM 协作 |
| 48 | http://arxiv.org/abs/2601.22292v1 | Learning Reward Functions for Cooperative Resilience in Multi-Agent Systems | 关注合作韧性，引入从排名轨迹学习奖励函数的框架， guided by 韧性指标。 | 解决混合动机设置中代理如何 safeguard 集体功能的问题。 | 混合动机多智能体系统 |
| 49 | http://arxiv.org/abs/2601.22297v1 | Prepare Reasoning Language Models for Multi-Agent Debate with Self-Debate Reinforcement Learning | 提出 SDRL，训练单个 LLM 具备独立解决问题及从 MAD 多样化推理轨迹学习的能力。 | 解决当前 RLVR 方法未明确准备模型 synthesis 和利用辩论中不同理由的问题。 | 多智能体辩论 |
| 50 | http://arxiv.org/abs/2602.11187v1 | TDPNavigator-Placer: Thermal- and Wirelength-Aware Chiplet Placement in 2.5D Systems Through Multi-Agent Reinforcement Learning | 提出 TDPNavigator-Placer，MARL 框架 dynamically 优化 placement 基于 chiplet 热设计功率。 | 解决 wirelength 减少与 thermal 管理 inherently  conflicting  objectives 问题。 | 2.5D 系统芯片放置 |

[返回目录](#目录)

<a id="cat-07"></a>

## Agent架构与框架设计

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2601.00339v1 | Bio-inspired Agentic Self-healing Framework for Resilient Distributed Computing Continuum Systems | 仿生四阶段自愈框架，LM Agent自主故障隔离与恢复 | 分布式计算系统频繁故障影响服务连续性 | 分布式计算连续体系统 |
| 2 | http://arxiv.org/abs/2601.00743v1 | An Agentic Framework for Neuro-Symbolic Programming | AgenticDomiKnowS将自由形式任务描述翻译为完整神经符号程序 | 神经符号编程集成耗时且需特定语法熟练度 | 神经符号程序开发 |
| 3 | http://arxiv.org/abs/2601.01101v1 | An Agentic Software Framework for Data Governance under DPDP | KYU Agent+Compliance Agent协作，动态策略执行与领域感知匿名化 | 传统合规工具硬编码规则不灵活，单体架构黑盒行为 | 印度DPDP法案下数据治理 |
| 4 | http://arxiv.org/abs/2601.01298v1 | Warp-Cortex: An Asynchronous, Memory-Efficient Architecture for Million-Agent Cognitive Scaling on Consumer Hardware | 异步架构解耦Agent逻辑与物理内存，权重共享拓扑突触 | 当前框架线性内存扩展消费者硬件不可行 | 消费级硬件百万Agent认知扩展 |
| 5 | http://arxiv.org/abs/2601.01522v1 | Bayesian Orchestration of Multi-LLM Agents for Cost-Aware Sequential Decision-Making | 贝叶斯成本感知多LLM编排，LLM作为近似似然模型聚合 | 单一LLM查询后验阈值置信度不足以处理序列决策成本 | 招聘医疗分诊欺诈检测序列决策 |
| 6 | http://arxiv.org/abs/2601.01743v1 | AI Agent Systems: Architectures, Applications, and Evaluation | 提出统一分类法涵盖Agent组件、编排模式和部署设置 | Agent系统设计权衡与评估复杂性 | 通用Agent系统设计与评估 |
| 7 | http://arxiv.org/abs/2601.01857v3 | Jenius Agent: Towards Experience-Driven Accuracy Optimization in Real-World Scenarios | 自适应提示生成与分层记忆机制 | 工具调用、状态跟踪和上下文管理失败 | 真实世界长程任务执行 |
| 8 | http://arxiv.org/abs/2601.02577v1 | Orchestral AI: A Framework for Agent Orchestration | 统一类型安全接口跨主要LLM提供商 | 碎片化API与 incompatible 消息格式 | 可移植可靠Agent系统开发 |
| 9 | http://arxiv.org/abs/2601.02695v1 | EvoRoute: Experience-Driven Self-Routing LLM Agent Systems | 自演化模型路由动态选择帕累托最优LLM | 性能-成本-延迟的Agent系统三难困境 | 复杂多轮任务Agent系统 |
| 10 | http://arxiv.org/abs/2601.02749v1 | The Path Ahead for Agentic AI: Challenges and Opportunities | 综合框架描述核心组件与架构过渡 | 从语言理解到自主行动的技术差距 | 通用Agentic AI发展 |
| 11 | http://arxiv.org/abs/2601.03328v1 | LLM-Enabled Multi-Agent Systems: Empirical Evaluation and Insights into Emerging Design Patterns & Paradigms | 形式化新兴设计模式与范式文献 | 从原型到生产成熟度的过渡挑战 | 多Agent系统开发 |
| 12 | http://arxiv.org/abs/2601.03197v1 | Software-Defined Agentic Serving | SDN启发框架基于运行时状态控制通信属性 | 现有服务范式无法适应动态服务条件 | 多Agent LLM管道服务 |
| 13 | http://arxiv.org/abs/2601.03204v1 | InfiAgent: An Infinite-Horizon Framework for General-Purpose Autonomous Agents | 文件中心状态抽象外部化持久状态 | 无界上下文增长与累积错误导致长程任务崩溃 | 通用自主长程Agent |
| 14 | http://arxiv.org/abs/2601.03359v1 | Enhancing LLM Instruction Following: An Evaluation-Driven Multi-Agentic Workflow for Prompt Instructions Optimization | 多Agent工作流解耦主任务描述与约束优化 | 传统提示优化忽略作为接受标准的细粒度约束 | LLM指令遵循优化 |
| 15 | http://arxiv.org/abs/2601.04692v1 | See, Explain, and Intervene: A Few-Shot Multimodal Agent Framework for Hateful Meme Moderation | 任务特定生成多模态Agent，少样本适应不同 meme 类型 | 仇恨meme检测、解释和干预在有限数据条件下 | 社交媒体内容审核系统 |
| 16 | http://arxiv.org/abs/2601.04703v1 | Beyond Monolithic Architectures: A Multi-Agent Search and Knowledge Optimization Framework for Agentic Search | M-ASK框架解耦搜索行为Agent与知识管理Agent | 单一Agent架构的结构瓶颈与学习不稳定 | 复杂信息搜索任务 |
| 17 | http://arxiv.org/abs/2601.04748v2 | When Single-Agent with Skills Replace Multi-Agent Systems and When They Fail | 技能选择编译多Agent为单Agent，发现容量相变现象 | 多Agent系统计算开销大，技能库扩展的极限 | 可扩展技能型Agent设计 |
| 18 | http://arxiv.org/abs/2601.05016v1 | From Idea to Co-Creation: A Planner-Actor-Critic Framework for Agent Augmented 3D Modeling | Planner-Actor-Critic架构+人类监督+批评者引导反思 | 单提示Agent直接执行建模命令质量有限 | 创意3D建模与人机协作 |
| 19 | http://arxiv.org/abs/2601.05109v1 | Nalar: An agent serving framework | 工作流规范与执行分离+轻量存根+两级控制架构 | LLM Agent应用高效服务部署因异构组件与动态控制流困难 | 异构Agent应用服务部署 |
| 20 | http://arxiv.org/abs/2601.05191v2 | AgentCompress: Task-Aware Compression for Affordable Large Language Model Agents | 任务感知动态压缩+轻量神经控制器路由请求到适当量化模型 | LLM计算需求高使预算有限机构无法使用 | 低成本LLM Agent部署 |
| 21 | http://arxiv.org/abs/2601.10738v1 | CTHA: Constrained Temporal Hierarchical Architecture for Stable Multi-Agent LLM Systems | 约束时序层次架构：消息契约+权威流形+仲裁者分辨率约束 | 多时间尺度Agent架构中协调稳定性受损导致层间冲突 | 大规模复杂任务执行的多Agent LLM系统 |
| 22 | http://arxiv.org/abs/2601.08219v1 | A Preliminary Agentic Framework for Matrix Deflation | LLM 生成 SVD 更新，VLM 决策，无需固定阈值。 | 解决矩阵 deflate 过程中的阈值设定与稳定性。 | 矩阵计算与数值算法 |
| 23 | http://arxiv.org/abs/2601.03624v2 | Architecting Agentic Communities using Design Patterns | 基于设计模式构建代理社区，形式化治理。 | 缺乏企业级多代理系统的系统架构指导。 | 企业级多代理生态系统 |
| 24 | http://arxiv.org/abs/2601.04426v1 | XGrammar 2: Dynamic and Efficient Structured Generation Engine for Agentic LLMs | 动态调度语义与 JIT 编译，加速结构化生成。 | 现有引擎难以处理动态结构化生成任务。 | 代理结构化生成引擎 |
| 25 | http://arxiv.org/abs/2601.04544v1 | TCAndon-Router: Adaptive Reasoning Router for Multi-Agent Collaboration | 自适应推理路由，支持动态代理 onboard。 | 静态路由难以整合新代理且易冲突。 | 多代理协作路由 |
| 26 | http://arxiv.org/abs/2601.04556v1 | 4D-ARE: Bridging the Attribution Gap in LLM Agent Requirements Engineering | 四维归因驱动代理需求工程方法论。 | 设计时未指定代理应推理的领域知识。 | 代理需求工程 |
| 27 | http://arxiv.org/abs/2601.07143v1 | EZBlender: Efficient 3D Editing with Plan-and-ReAct Agent | Plan-and-ReAct混合框架，规划分解与反应式局部自主结合 | 3D编辑中精度与响应速度的权衡问题 | Blender 3D建模/EZBlender智能体 |
| 28 | http://arxiv.org/abs/2601.07309v1 | ARM: Role-Conditioned Neuron Transplantation for Training-Free Generalist LLM Agent Merging | 激活引导的角色条件神经元移植三步框架 | 专用Agent无法稳健适应其他环境 | 交互式LLM Agent合并 |
| 29 | http://arxiv.org/abs/2601.07477v2 | JudgeFlow: Agentic Workflow Optimization via Block Judge | 评估-评判-优化-更新流水线，块级责任评分 | 缺乏细粒度信号导致低效修改 | LLM Agent工作流优化 |
| 30 | http://arxiv.org/abs/2601.07526v2 | MegaFlow: Large-Scale Distributed Orchestration System for the Agentic Era | 三独立服务抽象（模型/Agent/环境），统一接口交互 | 缺乏支持复杂Agent任务大规模训练评估的基础设施 | Agent训练部署/MegaFlow系统 |
| 31 | http://arxiv.org/abs/2601.07779v1 | OS-Symphony: A Holistic Framework for Robust and Generalist Computer-Using Agent | 反思记忆Agent和多功能工具Agent双创新协调 | 长程工作流鲁棒性和新领域泛化能力不足 | 计算机使用Agent/OSWorld基准 |
| 32 | http://arxiv.org/abs/2601.06235v1 | An Intelligent AI glasses System with Multi-Agent Architecture for Real-Time Voice Processing and Task Execution | 双 Agent 架构集成实时语音处理与本地 LLM 任务执行。 | 实现 AI 眼镜系统的实时语音命令处理与跨平台任务执行。 | 智能穿戴设备与 AI 眼镜 |
| 33 | http://arxiv.org/abs/2601.05890v1 | StackPlanner: A Centralized Hierarchical Multi-Agent System with Task-Experience Memory Management | 分层多 Agent 框架解耦协调与执行，显式控制任务级记忆。 | 解决中心 Agent 长程协作中上下文膨胀与经验复用难题。 | 复杂知识密集型任务协作 |
| 34 | http://arxiv.org/abs/2601.06007v2 | Don't Break the Cache: An Evaluation of Prompt Caching for Long-Horizon Agentic Tasks | 全面评估提示缓存策略，优化长程 Agent 任务的 API 成本与延迟。 | 解决多轮 Agent 任务中上下文窗口增大导致的成本与延迟问题。 | 长程 Agentic 任务优化 |
| 35 | http://arxiv.org/abs/2601.06424v1 | Can a Unimodal Language Agent Provide Preferences to Tune a Multimodal Vision-Language Model? | 单模态语言 Agent 提供偏好反馈优化多模态模型文本生成。 | 探索可扩展路径为现有 LLM 添加多模态能力。 | 多模态模型优化与协作 |
| 36 | http://arxiv.org/abs/2601.08343v1 | When KV Cache Reuse Fails in Multi-Agent Systems: Cross-Candidate Interaction is Crucial for LLM Judges | 揭示 KV 缓存复用在 Judge -centric 推理中的失败模式，强调跨候选交互重要性。 | 解决多智能体系统中 Judge 选择不一致与效率权衡问题。 | 多智能体 LLM 系统 |
| 37 | http://arxiv.org/abs/2601.08815v2 | Agent Contracts: A Formal Framework for Resource-Bounded Autonomous AI Systems | 扩展合同隐喻至资源有界执行，统一输入输出、资源约束与时序边界。 | 解决缺乏形式化资源治理机制以约束智能体消耗与操作时间问题。 | 自主 AI 系统部署 |
| 38 | http://arxiv.org/abs/2601.09150v4 | World Craft: Agentic Framework to Create Visualizable Worlds via Text | 提出智能体世界创建框架，通过文本描述创建可执行可视化 AI Town。 | 解决非专家难以自定义可视化环境及编程技能缺乏问题。 | 环境创建与游戏场景 |
| 39 | http://arxiv.org/abs/2601.12560v1 | Agentic Artificial Intelligence (AI): Architectures, Taxonomies, and Evaluation of Large Language Model Agents | 统一分类法：感知/大脑/规划/行动/工具/协作 | Agent设计多样，缺乏统一架构导航 | LLM Agent系统设计者 |
| 40 | http://arxiv.org/abs/2601.12967v1 | Sutradhara: An Intelligent Orchestrator-Engine Co-design for Tool-based Agentic Inference | 编排器-引擎协同设计，工具感知提示分割 | 工具调用占延迟30-80%，KV缓存命中率崩溃 | 生产级工具型Agent推理 |
| 41 | http://arxiv.org/abs/2601.12979v2 | The Bitter Lesson of Diffusion Language Models for Agentic Workflows: A Comprehensive Reality Check | DiffuAgent框架评估扩散模型Agent能力 | 扩散LLM在Agent工作流中系统性失败 | 扩散模型Agent应用 |
| 42 | http://arxiv.org/abs/2601.12996v1 | OFA-MAS: One-for-All Multi-Agent System Topology Design based on Mixture-ofExperts Graph Generative Models | OFA-TAD单一通用模型生成自适应协作图 | 现有方法一任务一模型，泛化差且无法共享知识 | 跨领域多Agent系统拓扑 |
| 43 | http://arxiv.org/abs/2601.13383v1 | A Lightweight Modular Framework for Constructing Autonomous Agents Driven by Large Language Models: Design, Implementation, and Applications in AgentForge | AgentForge轻量模块化框架，可组合技能抽象 | 现有框架架构僵化、供应商锁定、复杂度高 | LLM Agent快速原型开发 |
| 44 | http://arxiv.org/abs/2601.13671v1 | The Orchestration of Multi-Agent Systems: Architectures, Protocols, and Enterprise Adoption | 统一编排框架，MCP+A2A双协议标准化 | 多Agent系统缺乏互操作通信基础和治理框架 | 企业级多Agent生态系统 |
| 45 | http://arxiv.org/abs/2601.09822v2 | LLM-Based Agentic Systems for Software Engineering: Challenges and Opportunities | 系统综述 LLM 多智能体系统在软件开发生命周期应用及挑战机遇。 | 解决软件工程领域缺乏对 agentic 系统现状、框架及协议的系统认知。 | 软件工程领域研究者 |
| 46 | http://arxiv.org/abs/2601.09883v1 | Beyond Rule-Based Workflows: An Information-Flow-Orchestrated Multi-Agents Paradigm via Agent-to-Agent Communication from CORAL | 信息流编排器监控进度并通过自然语言动态协调，无需预定义工作流。 | 解决规则基工作流需大量人工编码状态且无法覆盖复杂现实任务空间问题。 | 通用多智能体任务编排 |
| 47 | http://arxiv.org/abs/2601.10025v1 | Structured Personality Control and Adaptation for LLM Agents | 基于荣格心理类型建模人格，整合主导辅助协调及强化补偿机制。 | 解决 LLM 人格表达难以兼具细微差别与适应性及长期演化的问题。 | 人机交互中的人格化代理 |
| 48 | http://arxiv.org/abs/2601.10122v1 | Role-Playing Agents Driven by Large Language Models: Current Status, Challenges, and Future Trends | 综述 RPLA 技术演进，总结心理量表驱动建模及记忆增强提示等关键路径。 | 解决角色扮演的语言代理缺乏系统性视角及方法论洞察的问题。 | 角色扮演语言代理研究 |
| 49 | http://arxiv.org/abs/2601.11672v1 | From Everything-is-a-File to Files-Are-All-You-Need: How Unix Philosophy Informs the Design of Agentic AI Systems | 借鉴 Unix 哲学设计以文件和代码为中心的 Agent 交互模型。 | 解决异构资源在 Agent 系统中接口不一致问题。 | 自主软件 Agent 系统 |
| 50 | http://arxiv.org/abs/2601.11147v1 | Do We Always Need Query-Level Workflows? Rethinking Agentic Workflow Generation for Multi-Agent Systems | 提出 SCALE 框架，低成本生成任务级工作流。 | 解决查询级工作流生成成本高且非必要问题。 | 多智能体系统工作流 |
| 51 | http://arxiv.org/abs/2601.11687v1 | Semantic Caching and Intent-Driven Context Optimization for Multi-Agent Natural Language to Code Systems | 语义缓存与意图驱动上下文优化降低 Token 消耗。 | 解决生产环境 NL2Code 系统成本高延迟大问题。 | 企业数据分析系统 |
| 52 | http://arxiv.org/abs/2601.11816v1 | POLARIS: Typed Planning and Governed Execution for Agentic AI in Back-Office Automation | 类型化计划合成与验证执行确保后台自动化合规。 | 解决通用多智能体设置缺乏可审计性与策略对齐。 | 企业后台自动化 |
| 53 | http://arxiv.org/abs/2601.12307v1 | Rethinking the Value of Multi-Agent Workflow: A Strong Single Agent Baseline | 提出 OneFlow 算法自动定制单 Agent 执行工作流。 | 解决同质多 Agent 工作流可被单 Agent 模拟。 | 多 Agent 工作流优化 |
| 54 | http://arxiv.org/abs/2601.12348v1 | Generative AI Agents for Controllable and Protected Content Creation | 多智能体框架结合可控合成与数字水印保护。 | 解决生成式 AI 可控性与内容保护挑战。 | 可信创意工作流 |
| 55 | http://arxiv.org/abs/2601.13719v1 | Hierarchical Long Video Understanding with Audiovisual Entity Cohesion and Agentic Search | 整合音视频实体凝聚与分层视频索引，结合代理搜索机制 | 解决长视频理解中上下文窗口过长导致的信息碎片化问题 | 长视频理解 |
| 56 | http://arxiv.org/abs/2601.13933v1 | VulnResolver: A Hybrid Agent Framework for LLM-Based Automated Vulnerability Issue Resolution | 结合自主代理适应性与工作流引导修复稳定性的混合框架 | 解决自动漏洞修复依赖手动标注及忽视语义上下文的问题 | 自动化漏洞问题 resolution |
| 57 | http://arxiv.org/abs/2601.14053v1 | LLMOrbit: A Circular Taxonomy of Large Language Models -From Scaling Walls to Agentic AI Systems | 提出涵盖 2019-2025 年大模型景观的综合圆形分类法 | 解决缺乏导航大模型 landscape 包括代理系统的分类法 | 大模型与代理系统综述 |
| 58 | http://arxiv.org/abs/2601.14171v1 | Paper2Rebuttal: A Multi-Agent Framework for Transparent Author Response Assistance | 将反驳生成重构为以证据为中心的规划任务 | 解决直接文本生成导致的幻觉及缺乏可验证 grounding 问题 | 学术作者回复协助 |
| 59 | http://arxiv.org/abs/2601.14192v1 | Toward Efficient Agents: Memory, Tool learning, and Planning | 从记忆、工具学习和规划三方面调查代理效率 | 解决代理效率在现实部署中常被忽视的问题 | 代理系统效率综述 |
| 60 | http://arxiv.org/abs/2601.14567v1 | Agent Identity URI Scheme: Topology-Independent Naming and Capability-Based Discovery for Multi-Agent Systems | 提出 agent://URI 方案通过三个正交组件解耦身份与拓扑 | 解决代理身份绑定网络位置导致迁移及联邦问题 | 多代理系统身份管理 |
| 61 | http://arxiv.org/abs/2601.14735v2 | Optimizing FaaS Platforms for MCP-enabled Agentic Workflows | 提出基于 FaaS 的架构编排 MCP 启用的代理工作流 | 解决可扩展云部署及代理工作流状态管理挑战 | 代理工作流云部署 |
| 62 | http://arxiv.org/abs/2601.14914v1 | CodeDelegator: Mitigating Context Pollution via Role Separation in Code-as-Action Agents | 提出通过角色 specialization 分离规划与实现的多代理框架 | 解决单一代理导致上下文污染损害长周期性能问题 | 代码即行动代理 |
| 63 | http://arxiv.org/abs/2601.14982v1 | Interoperable Architecture for Digital Identity Delegation for AI Agents with Blockchain Integration | 引入统一框架实现有界可审计 least-privilege 委托 | 解决数字身份系统中可验证委托未 resolved 问题 | AI 代理数字身份委托 |
| 64 | http://arxiv.org/abs/2601.15074v1 | SmartOracle -- An Agentic Approach to Mitigate Noise in Differential Oracles | 将手动 triage 工作流 decompose 为专用大模型子代理 | 解决差分测试中 oracle 构建昂贵耗时及易误报问题 | 差分 Oracle 噪声缓解 |
| 65 | http://arxiv.org/abs/2601.15153v1 | How to Build AI Agents by Augmenting LLMs with Codified Human Expert Domain Knowledge? A Software Engineering Framework | 软件工程框架捕获人类领域知识，增强LLM实现专家级输出 | 解决领域专家知识瓶颈，非专家实现专业领域可视化 | 工程领域数据可视化 |
| 66 | http://arxiv.org/abs/2601.16087v1 | Controlling Long-Horizon Behavior in Language Model Agents with Explicit State Dynamics | agent级情感子系统维护连续VAD状态，外部于语言模型 | 解决LLM agent长程交互中语气和人设突变缺乏时间结构问题 | 多轮对话agent行为控制 |
| 67 | http://arxiv.org/abs/2601.16286v2 | SemanticALLI: Caching Reasoning, Not Just Responses, in Agentic Systems | 将生成分解为AIR和VS，结构化中间表示作为可缓存工件 | 解决agent pipeline频繁重构相同中间逻辑的隐藏低效问题 | 营销智能平台agentic系统 |
| 68 | http://arxiv.org/abs/2601.16648v1 | A Cognitive Framework for Autonomous Agents: Toward Human-Inspired Design | 整合巴甫洛夫和工具过程的人类启发RL架构，RF刺激作为条件线索 | 解决现有工程方案几乎完全依赖工具学习，忽视人类双系统机制 | 自主系统决策 |
| 69 | http://arxiv.org/abs/2601.18081v1 | DRPG (Decompose, Retrieve, Plan, Generate): An Agentic Framework for Academic Rebuttal | 四步代理框架自动生成学术反驳，规划器准确率超 98% | 现有方法长上下文理解差，回复缺乏针对性 | 学术同行评审与反驳 |
| 70 | http://arxiv.org/abs/2601.18130v1 | RouteMoA: Dynamic Routing without Pre-Inference Boosts Efficient Mixture-of-Agents | 动态路由无需预推理，轻量评分筛选候选模型 | 混合代理稠密拓扑成本高、延迟大 | 高效混合代理系统 |
| 71 | http://arxiv.org/abs/2601.18157v2 | Agentic Very Long Video Understanding | EGAgent 基于实体场景图实现长视频跨模态推理 | 现有方法上下文窗口受限，缺乏长程组合推理 | 超长视频理解与回忆 |
| 72 | http://arxiv.org/abs/2601.18267v1 | Orchestrating Specialized Agents for Trustworthy Enterprise RAG | ADORE 框架协调专用代理，内存锁定合成报告 | 一次性检索生成摘要浅，缺乏可追溯性 | 企业知识工作与 RAG |
| 73 | http://arxiv.org/abs/2601.18320v1 | MultiVis-Agent: A Multi-Agent Framework with Logic Rules for Reliable and Comprehensive Cross-Modal Data Visualization | 逻辑规则增强多代理框架，提供数学可靠性保证 | 单模态输入与一次性生成导致可靠性挑战 | 跨模态数据可视化 |
| 74 | http://arxiv.org/abs/2602.13222v1 | Computability of Agentic Systems | Quest Graph 形式化框架分析有限上下文代理能力 | 缺乏分析代理系统根本能力的形式化方法 | 代理系统理论分析 |
| 75 | http://arxiv.org/abs/2601.16746v2 | SWE-Pruner: Self-Adaptive Context Pruning for Coding Agents | 任务感知自适应剪枝框架，轻量神经筛选器动态选择相关代码行 | 长交互上下文导致高成本和逻辑结构破坏 | 编码智能体长上下文处理 |
| 76 | http://arxiv.org/abs/2601.16863v1 | Mixture-of-Models: Unifying Heterogeneous Agents via N-Way Self-Evaluating Deliberation | 运行时模型混合架构，动态专家经纪人与 N 路自我评估审议 | 静态专家混合无法动态绑定异构模型角色 | 消费级模型 ensemble 性能提升 |
| 77 | http://arxiv.org/abs/2601.17435v1 | Towards a Declarative Agentic Layer for Intelligent Agents in MCP-Based Server Ecosystems | 声明式智能体层 DALIA，形式化可执行能力与确定性任务图 | 缺乏明确架构结构链接目标能力执行导致可靠性问题 | MCP 基于服务器生态系统 |
| 78 | http://arxiv.org/abs/2601.17737v2 | The Script is All You Need: An Agentic Framework for Long-Horizon Dialogue-to-Cinematic Video Generation | 端到端代理框架，ScripterAgent 翻译对话为电影脚本指导 DirectorAgent | 视频模型难以从高层概念生成长形式连贯叙事 | 对话到电影视频生成 |
| 79 | http://arxiv.org/abs/2601.17744v1 | Faramesh: A Protocol-Agnostic Execution Control Plane for Autonomous Agent Systems | 协议无关执行控制平面，强制执行时授权与非绕过行动授权边界 | 自主智能体系统缺乏强制执行检查点导致现实副作用 | 自主智能体系统治理 |
| 80 | http://arxiv.org/abs/2601.17833v1 | An Effective and Cost-Efficient Agentic Framework for Ethereum Smart Contract Auditing | 自动化审计智能体 Heimdallr，函数级重组代码最小化上下文开销 | 现有方案无法识别复杂业务逻辑漏洞或成本高 | 以太坊智能合约审计 |
| 81 | http://arxiv.org/abs/2601.17879v1 | Self-Manager: Parallel Agent Loop for Long-form Deep Research | 并行智能体循环，主线程创建子线程隔离上下文异步并发执行 | 现有智能体单上下文窗口顺序执行导致相互干扰阻塞 | 长形式深度研究任务 |
| 82 | http://arxiv.org/abs/2601.20764v1 | Agentic Fog: A Policy-driven Framework for Distributed Intelligence in Fog Computing | 提出 Agentic Fog 模型，雾节点为策略驱动自主 Agent | 解决雾计算中部分可观测与动态负载的自适应控制 | 雾计算与边缘基础设施 |
| 83 | http://arxiv.org/abs/2601.21473v1 | ScaleSim: Serving Large-Scale Multi-Agent Simulation with Invocation Distance-Based Memory Management | 提出 ScaleSim，基于调用距离的内存管理服务于大规模 MAS | 解决 LLM 多 Agent 模拟扩展中的 GPU 内存压力 | 大规模多 Agent 模拟服务 |
| 84 | http://arxiv.org/abs/2601.21822v1 | CORE:Toward Ubiquitous 6G Intelligence Through Collaborative Orchestration of Large Language Model Agents Over Hierarchical Edge | 提出 CORE 框架，分层边缘上协作编排多 LLM Agent | 解决 6G 网络中碎片化资源不足以支撑复杂推理问题 | 6G 网络与边缘计算智能 |
| 85 | http://arxiv.org/abs/2601.19121v3 | LLMs as Orchestrators: Constraint-Compliant Multi-Agent Optimization for Recommendation Systems | 提出 DualAgent-Rec 双智能体框架，LLM 协调资源分配 | 推荐系统多目标优化中硬约束难以满足的问题 | 电商推荐系统 |
| 86 | http://arxiv.org/abs/2601.19155v1 | LocationAgent: A Hierarchical Agent for Image Geolocation via Decoupling Strategy and Evidence from Parametric Knowledge | 设计 RER 架构，分离推理与证据验证，防止漂移 | 图像地理定位中的事实幻觉和泛化瓶颈问题 | 图像地理定位任务 |
| 87 | http://arxiv.org/abs/2601.19204v1 | MATA: A Trainable Hierarchical Automaton System for Multi-Agent Visual Reasoning | 可训练分层自动机系统，超智能体选择最优子智能体 | 视觉推理中隐式推理难解释及幻觉问题 | 复杂视觉推理任务 |
| 88 | http://arxiv.org/abs/2601.19311v2 | Balancing Sustainability And Performance: The Role Of Small-Scale LLMs In Agentic Artificial Intelligence Systems | 对比分析小规模模型在代理系统中的能效与性能 | 大模型推理能耗高带来的可持续性挑战 | 绿色 AI 系统设计 |
| 89 | http://arxiv.org/abs/2601.19752v1 | Agentic Design Patterns: A System-Theoretic Framework | 系统理论框架，分解五大核心子系统与 12 种模式 | 代理设计缺乏严谨系统理论基础导致不可靠 | 鲁棒 AI 代理工程设计 |
| 90 | http://arxiv.org/abs/2602.00585v1 | Exploring Information Seeking Agent Consolidation | 研究数据级与参数级策略整合异构信息寻求智能体为单一基础模型。 | 解决现有信息寻求智能体专用化限制可扩展性及跨域泛化的问题。 | 信息寻求智能体整合 |
| 91 | http://arxiv.org/abs/2602.00785v1 | World Models as an Intermediary between Agents and the Real World | 主张用世界模型作为智能体与现实世界的中介克服高成本动作瓶颈。 | 解决复杂高成本领域中执行动作获取奖励信号 expense 过高的问题。 | 机器人学与科学实验 |
| 92 | http://arxiv.org/abs/2602.00887v1 | EffGen: Enabling Small Language Models as Capable Autonomous Agents | 提出 effGen 框架，优化小语言模型实现高效安全本地部署。 | 解决现有智能体系统依赖大模型导致高 token 成本及隐私担忧的问题。 | 小模型自主智能体 |
| 93 | http://arxiv.org/abs/2601.21879v1 | astra-langchain4j: Experiences Combining LLMs and Agent Programming | 概述 ASTRA 编程语言与 LLM 集成的原型开发经验，探讨传统工具包对新平台设计的影响。 | 探索生成式 AI 如何影响传统 Agent 工具包及反之亦然的设计经验。 | 智能体编程工具包 |
| 94 | http://arxiv.org/abs/2601.21916v1 | JADE: Bridging the Strategic-Operational Gap in Dynamic Agentic RAG | 提出 JADE 框架，联合优化动态工作流中的规划与执行，实现端到端学习。 | 解决规划策略与局部执行器之间的战略 - 操作不匹配问题。 | 动态 RAG 工作流 |
| 95 | http://arxiv.org/abs/2601.22001v1 | Heterogeneous Computing: The Key to Powering the Future of AI Agent Inference | 引入操作强度和容量足迹指标， motivating  disaggregated serving 和系统级异构性。 | 解决 AI 智能体推断中的内存容量和带宽瓶颈问题。 | 大规模智能体推断系统 |
| 96 | http://arxiv.org/abs/2601.22269v1 | JAF: Judge Agent Forest | 引入 JAF，法官代理对一组查询 - 响应对进行联合推理，而非孤立评估。 | 解决法官代理仅作为局部评估者，无法 discern 跨实例模式的问题。 | 代理自我 refinement |
| 97 | http://arxiv.org/abs/2601.22290v1 | The Six Sigma Agent: Achieving Enterprise-Grade Reliability in LLM Systems Through Consensus-Driven Decomposed Execution | 引入 Six Sigma Agent，通过任务分解、微代理采样和共识投票实现企业级可靠性。 | 解决 LLM 概率性本质带来的企业部署可靠性挑战。 | 企业级 LLM 系统 |
| 98 | http://arxiv.org/abs/2601.22305v1 | BayesFlow: A Probability Inference Framework for Meta-Agent Assisted Workflow Generation | 将工作流生成 cast 为贝叶斯推断，引入 BWG 采样框架构建工作流。 | 解决 prior 方法将任务 cast 为优化问题缺乏理论基础的问题。 | 自动工作流生成 |
| 99 | http://arxiv.org/abs/2601.22705v1 | CONCUR: High-Throughput Agentic Batch Inference of LLM via Congestion-Based Concurrency Control | 提出 CONCUR， lightweight 控制层 regulate 代理 admission 以 bound  aggregate 缓存压力。 | 解决 batch 推断中 KV 缓存 middle-phase thrashing 导致 throughput 降级问题。 | 代理批量推断 |

[返回目录](#目录)

<a id="cat-08"></a>

## Agent记忆与知识管理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2601.11585v1 | Entropic Context Shaping: Information-Theoretic Filtering for Context-Aware LLM Agents | 熵上下文整形框架，信息论度量上下文效用 | 区分有用信息与误导性干扰 | 多轮对话上下文选择任务 |
| 2 | http://arxiv.org/abs/2601.06115v1 | Dreaming Is Not a Bug: A Jung-Inspired Dream Layer for Multi-Agent LLM Companions | 荣格启发梦层，人工集体无意识共享梦池增强边缘案例 | 控制离线幻觉作为学习资源而非可靠性缺陷 | 多Agent LLM伴侣系统 |
| 3 | http://arxiv.org/abs/2601.01885v1 | Agentic Memory: Learning Unified Long-Term and Short-Term Memory Management for Large Language Model Agents | 统一LTM/STM管理并暴露为工具操作 | 有限上下文窗口导致的长程推理限制 | LLM Agent长程任务 |
| 4 | http://arxiv.org/abs/2601.02553v3 | SimpleMem: Efficient Lifelong Memory for LLM Agents | 语义无损压缩三阶段流水线 | 全历史保留冗余与迭代推理高token成本 | LLM Agent长程交互 |
| 5 | http://arxiv.org/abs/2601.02732v1 | Agentic Memory Enhanced Recursive Reasoning for Root Cause Localization in Microservices | 递归推理引擎+Agentic Memory跨警报复用 | 浅层症状推理与跨警报复用缺乏 | 微服务系统根因定位 |
| 6 | http://arxiv.org/abs/2601.02744v3 | SYNAPSE: Empowering LLM Agents with Episodic-Semantic Memory via Spreading Activation | 动态图记忆+扩散激活+三重混合检索 | 长期Agent记忆的 disconnected 性质 | 复杂时序与多跳推理任务 |
| 7 | http://arxiv.org/abs/2601.02845v1 | TiMem: Temporal-Hierarchical Memory Consolidation for Long-Horizon Conversational Agents | 时序记忆树组织对话+语义引导整合 | 跨层级时序结构化信息支持有限 | 长程对话Agent个性化 |
| 8 | http://arxiv.org/abs/2601.03236v1 | MAGMA: A Multi-Graph based Agentic Memory Architecture for AI Agents | 多正交图表示记忆项+策略引导遍历检索 | 单一记忆存储纠缠时序因果实体信息 | 长程推理Agent记忆 |
| 9 | http://arxiv.org/abs/2601.04726v1 | Memory Matters More: Event-Centric Memory as a Logic Map for Agent Searching and Reasoning | CompassMem将记忆组织为事件图，显式逻辑关系链接 | 现有记忆方法难以捕获经验间逻辑关系 | 长程推理与决策的LLM Agent |
| 10 | http://arxiv.org/abs/2601.04786v2 | AgentOCR: Reimagining Agent History via Optical Self-Compression | 视觉令牌表示历史+分段光学缓存+Agent自压缩 | 多轮交互历史文本膨胀导致token预算与内存过大 | 多轮交互Agent系统部署 |
| 11 | http://arxiv.org/abs/2601.05107v1 | Controllable Memory Usage: Balancing Anchoring and Innovation in Long-Term Human-Agent Interaction | SteeM框架允许用户动态调节记忆依赖程度 | 现有系统记忆使用"全或无"导致记忆锚定或利用不足 | 长期人机交互与个性化Agent |
| 12 | http://arxiv.org/abs/2601.05215v2 | MineNPC-Task: Task Suite for Memory-Aware Minecraft Agents | 用户编写基准与评估harness测试开放世界Minecraft中记忆感知Agent | 缺乏记忆感知具身Agent的透明可复现评估 | Minecraft中记忆感知具身Agent |
| 13 | http://arxiv.org/abs/2601.03785v2 | Membox: Weaving Topic Continuity into Long-Range Memory for LLM Agents | 主题织机分层记忆，保持对话主题连续性。 | 现有记忆系统破坏对话叙事与因果流。 | 长程对话与记忆管理 |
| 14 | http://arxiv.org/abs/2601.04463v1 | Beyond Static Summarization: Proactive Memory Extraction for LLM Agents | 主动记忆提取，循环反馈 loop 验证事实。 | 静态总结缺乏反馈，导致信息丢失累积。 | 代理长期记忆管理 |
| 15 | http://arxiv.org/abs/2601.07190v1 | Active Context Compression: Autonomous Memory Management in LLM Agents | Focus Agent自主决定知识 Consolidation 和原始历史剪枝 | LLM Agent长程任务的上下文膨胀问题 | 软件工程任务/SWE-bench Lite |
| 16 | http://arxiv.org/abs/2601.07468v1 | Beyond Dialogue Time: Temporal Semantic Memory for Personalized LLM Agents | 语义时间线建模和持续性记忆构建利用 | 记忆时间维度建模不准确和碎片化 | 个性化LLM Agent/LongMemEval和LoCoMo |
| 17 | http://arxiv.org/abs/2601.07470v1 | Learning How to Remember: A Meta-Cognitive Management Method for Structured and Transferable Agent Memory | 记忆抽象作为可学习认知技能，分层抽象级别组织 | 固定表示记忆限制泛化和导致负迁移 | LLM Agent长程决策/ALFWorld等 |
| 18 | http://arxiv.org/abs/2601.07582v2 | ES-Mem: Event Segmentation-Based Memory for Long-Term Dialogue Agents | 动态事件分割模块和分层记忆架构 | 记忆粒度僵化和扁平检索忽略话语结构线索 | 长程对话Agent/ES-Mem框架 |
| 19 | http://arxiv.org/abs/2601.07978v2 | Cost and accuracy of long-term memory in Distributed Multi-Agent Systems based on Large Language Models | 灵活测试台比较mem0向量记忆和Graphiti图知识图谱 | 网络约束下长期记忆系统评估有限 | 分布式多Agent系统/LoCoMo基准 |
| 20 | http://arxiv.org/abs/2601.08079v1 | MemoBrain: Executive Memory as an Agentic Brain for Reasoning | 依赖感知记忆构建，剪枝无效步骤折叠完成子轨迹 | 长程推理中推理痕迹积累破坏逻辑连续性 | 工具增强Agent推理/GAIA等基准 |
| 21 | http://arxiv.org/abs/2601.08160v1 | SwiftMem: Fast Agentic Memory via Query-aware Indexing | 查询感知索引，时间和语义维度亚线性检索 | 现有记忆框架 exhaustive 检索导致延迟瓶颈 | 记忆增强LLM Agent/LoCoMo等 |
| 22 | http://arxiv.org/abs/2601.06282v1 | Amory: Building Coherent Narrative-Driven Agent Memory through Agentic Reasoning | 离线时间增强推理，构建结构化叙事记忆与语义记忆。 | 解决长程对话中记忆碎片化缺乏连贯性与 subtlety 的问题。 | 长程对话 Agent 记忆 |
| 23 | http://arxiv.org/abs/2601.06377v1 | HiMem: Hierarchical Long-Term Memory for LLM Long-Horizon Agents | 层次化长程记忆框架，支持记忆构建、检索与动态更新。 | 解决现有记忆系统在持续交互下适应性、扩展性与自进化不足。 | 长程对话 LLM Agent |
| 24 | http://arxiv.org/abs/2601.06490v1 | Bi-Mem: Bidirectional Construction of Hierarchical Memory for Personalized LLMs via Inductive-Reflective Agents | 双向构建层次化记忆，归纳与反思 Agent 确保全局 - 局部对齐。 | 解决聚类中对话噪声与记忆幻觉放大导致 persona 不对齐问题。 | 个性化 LLM 长程对话 |
| 25 | http://arxiv.org/abs/2601.06789v2 | MemGovern: Enhancing Code Agents through Learning from Governed Human Experiences | 经验治理框架将 GitHub 数据转化为 Agent 友好经验卡。 | 解决 SWE Agent 忽略开放世界人类历史经验导致的封闭世界限制。 | 软件工程 Agent 记忆增强 |
| 26 | http://arxiv.org/abs/2601.06973v1 | LLMs Can't Play Hangman: On the Necessity of a Private Working Memory for Language Agents | 引入显式私有工作记忆架构，恢复交互式任务中的一致性。 | 解决标准聊天接口缺乏私有工作记忆导致隐藏状态维护失败。 | 交互式语言 Agent 架构 |
| 27 | http://arxiv.org/abs/2601.08323v2 | AtomMem : Learnable Dynamic Agentic Memory with Atomic Memory Operation | 将记忆管理重构为动态决策问题，分解为原子 CRUD 操作并通过 RL 学习策略。 | 解决静态手工记忆工作流限制性能与泛化能力问题。 | 长程问题解决智能体 |
| 28 | http://arxiv.org/abs/2601.08699v1 | RAGShaper: Eliciting Sophisticated Agentic RAG Skills via Automated Data Synthesis | 自动化构建含对抗干扰的 RAG 任务与智能体轨迹，强制纠错与噪声拒绝。 | 解决缺乏反映真实检索环境噪声的高质量训练数据问题。 | 检索增强生成智能体 |
| 29 | http://arxiv.org/abs/2601.08816v2 | MemRec: Collaborative Memory-Augmented Agentic Recommender System | 架构解耦推理与记忆管理，引入专用 LM 管理动态协作记忆图。 | 解决孤立记忆忽略协作信号及认知负荷过载问题。 | 推荐系统 |
| 30 | http://arxiv.org/abs/2601.14287v1 | Chain-of-Memory: Lightweight Memory Construction with Dynamic Evolution for LLM Agents | 提倡轻量构建 paired  sophisticated 利用，通过动态进化组织检索片段。 | 解决复杂记忆构建成本高及简单拼接无法桥接检索与推理问题。 | LLM 智能体长程决策 |
| 31 | http://arxiv.org/abs/2602.06051v3 | CAST: Character-and-Scene Episodic Memory for Agents | 提出基于角色与场景的记忆架构，构建 3D 场景并组织为角色 profile。 | 解决现有记忆系统难以表示与检索连贯事件的问题。 | 开放与时敏对话问题 |
| 32 | http://arxiv.org/abs/2602.06052v3 | Rethinking Memory Mechanisms of Foundation Agents in the Second Half: A Survey | 提供基础智能体记忆统一视图，分析记忆实例化、操作及评估基准。 | 解决长程动态环境中上下文爆炸及信息积累管理挑战。 | 基础智能体研究 |
| 33 | http://arxiv.org/abs/2601.13247v1 | Aligning Agentic World Models via Knowledgeable Experience Learning | WorldMind构建符号世界知识仓库，统一过程/目标经验 | LLM缺乏物理世界程序性基础，产生物理幻觉 | 具身Agent世界模型对齐 |
| 34 | http://arxiv.org/abs/2601.15311v3 | Aeon: High-Performance Neuro-Symbolic Memory Management for Long-Horizon LLM Agents | 神经符号认知操作系统，结构化记忆为 Memory Palace 与 Trace，优化检索。 | 解决长程交互中上下文窗口扩展导致推理能力退化及记忆无序问题。 | 长程 LLM 智能体记忆管理 |
| 35 | http://arxiv.org/abs/2601.09636v1 | PersonalAlign: Hierarchical Implicit Intent Alignment for Personalized GUI Agent with Long-Term User-Centric Records | 分层意图记忆代理，利用长期用户记录解析模糊指令并预测潜在惯例。 | 解决 GUI 代理难以对齐用户复杂隐式意图及缺乏长期个性化上下文问题。 | 个性化 GUI 智能体 |
| 36 | http://arxiv.org/abs/2601.09913v1 | Continuum Memory Architectures for Long-Horizon LLM Agents | 定义连续记忆架构，维护更新内部状态，支持持久存储与时序链接。 | 解决 RAG 将记忆视为无状态查找表导致无法积累、突变或消歧的问题。 | 长程 LLM 智能体记忆 |
| 37 | http://arxiv.org/abs/2601.10402v4 | Toward Ultra-Long-Horizon Agentic Science: Cognitive Accumulation for Machine Learning Engineering | 引入分层认知缓存，动态蒸馏瞬态执行迹为稳定知识，解耦执行与策略。 | 解决 LLM 易被高维延迟反馈环境执行细节淹没无法巩固稀疏反馈问题。 | 超长程机器学习工程代理 |
| 38 | http://arxiv.org/abs/2601.11653v1 | AI Agents Need Memory Control Over More Context | 引入 Agent Cognitive Compressor，生物启发记忆控制器替换 transcript replay。 | 解决持久记忆通过 transcript replay 导致无边界上下文增长及噪声回忆问题。 | 长程多轮工作流代理 |
| 39 | http://arxiv.org/abs/2601.10702v1 | Grounding Agent Memory in Contextual Intent | STITCH 记忆系统用结构化检索 cue 索引轨迹步，按意图兼容性过滤记忆。 | 解决长程目标导向交互中相似实体事实 recur 导致记忆检索上下文错配问题。 | 长程目标导向代理记忆 |
| 40 | http://arxiv.org/abs/2601.11888v1 | Agentic-R: Learning to Retrieve for Agentic Search | 迭代训练检索器，利用全局答案正确性衡量效用。 | 解决相似段落对最终答案生成未必有用问题。 | 多步搜索 Agent 检索 |
| 41 | http://arxiv.org/abs/2601.11913v1 | LSTM-MAS: A Long Short-Term Memory Inspired Multi-Agent System for Long-Context Understanding | 模仿 LSTM 门控机制的多智能体系统处理长上下文。 | 解决长上下文处理中错误积累与幻觉传播。 | 长文本理解 Agent |
| 42 | http://arxiv.org/abs/2601.12030v1 | ARC: Active and Reflection-driven Context Management for Long-Horizon Information Seeking Agents | 主动反思驱动上下文管理，动态重组工作状态。 | 解决长程交互中上下文退化与连贯性失败。 | 长程信息搜索 Agent |
| 43 | http://arxiv.org/abs/2601.15709v1 | AgentSM: Semantic Memory for Agentic Text-to-SQL | 捕获执行轨迹为结构化程序指导未来推理，而非原始scratchpad | 解决企业级Text-to-SQL效率低、不稳定、重复交互问题 | 企业级Text-to-SQL系统 |
| 44 | http://arxiv.org/abs/2601.18204v1 | MemWeaver: Weaving Hybrid Memories for Traceable Long-Horizon Agentic Reasoning | 统一记忆框架整合图记忆、经验记忆与段落记忆 | 非结构化检索导致时间冲突与推理脆弱 | 长程交互记忆管理 |
| 45 | http://arxiv.org/abs/2601.18285v1 | U-Fold: Dynamic Intent-Aware Context Folding for User-Centric Agents | 动态上下文折叠保留细粒度约束与 evolving intent | 现有折叠方法丢弃关键事实与意图跟踪失败 | 用户中心长对话管理 |
| 46 | http://arxiv.org/abs/2601.18642v2 | FadeMem: Biologically-Inspired Forgetting for Efficient Agent Memory | 生物启发遗忘机制，自适应指数衰减管理记忆 | 当前 AI 系统二元保留策略导致信息过载 | 代理记忆效率优化 |
| 47 | http://arxiv.org/abs/2601.16872v2 | From Atom to Community: Structured and Evolving Agent Memory for User Behavior Modeling | 结构化演进智能体记忆，原子记忆单元与社区原型记忆传播 | 用户偏好表示 conflated 且 naive 覆盖导致遗忘 | 推荐系统与用户行为建模 |
| 48 | http://arxiv.org/abs/2601.20465v1 | BMAM: Brain-inspired Multi-Agent Memory Framework | 提出脑启发多 Agent 记忆框架，分解为情景、语义等子系统 | 解决长交互 horizon 下信息保持与行为一致性问题 | 长周期任务处理的语言模型 Agent |
| 49 | http://arxiv.org/abs/2601.20831v1 | MemCtrl: Using MLLMs as Active Memory Controllers on Embodied Agents | 提出 MemCtrl，用 MLLM 在线剪枝记忆，决定保留或丢弃 | 解决具身 Agent 在线操作下的严格内存与计算约束 | 资源受限的具身 Agent |
| 50 | http://arxiv.org/abs/2601.21545v1 | ShardMemo: Masked MoE Routing for Sharded Agentic LLM Memory | 提出 ShardMemo，预算分层记忆服务与掩码 MoE 路由 | 解决 Agent 内存体积增长与并行访问的瓶颈 | 长周期状态与多 Agent 执行记忆 |
| 51 | http://arxiv.org/abs/2601.21714v1 | E-mem: Multi-agent based Episodic Context Reconstruction for LLM Agent Memory | 提出 E-mem，从记忆预处理转向情景上下文重构 | 解决记忆压缩破坏复杂序列依赖与上下文完整性问题 | 长周期高精度问题求解 Agent |
| 52 | http://arxiv.org/abs/2601.21797v1 | Enhancing Conversational Agents via Task-Oriented Adversarial Memory Adaptation | 提出 AMA，通过模拟任务执行对齐记忆构建与更新 | 解决离线记忆准备与下游任务需求 misalignment 问题 | 长对话处理与记忆系统 |
| 53 | http://arxiv.org/abs/2601.19199v2 | MAGNET: Towards Adaptive GUI Agents with Memory-Driven Knowledge Evolution | 双层记忆机制，动态进化记忆以适配 UI 变化 | 移动 GUI 代理因界面更新导致的任务执行失败 | 移动应用自动化任务 |
| 54 | http://arxiv.org/abs/2601.19306v1 | Curiosity Driven Knowledge Retrieval for Mobile Agents | 好奇心驱动检索，结构化 AppCards 补偿知识盲区 | 移动代理在复杂应用中知识不全和泛化弱问题 | 智能手机自动化任务 |
| 55 | http://arxiv.org/abs/2601.20162v1 | Me-Agent: A Personalized Mobile Agent with Two-Level User Habit Learning for Enhanced Interaction | 两级用户习惯学习，提示级与记忆级个性化 | 移动代理忽略个性化需求导致交互受限 | 个性化移动交互 |
| 56 | http://arxiv.org/abs/2601.20352v2 | AMA: Adaptive Memory via Multi-Agent Collaboration | 多智能体协作管理记忆，动态对齐检索粒度 | 现有记忆系统检索粒度僵化且逻辑不一致 | 长上下文交互与推理 |
| 57 | http://arxiv.org/abs/2601.23014v2 | Mem-T: Densifying Rewards for Long-Horizon Memory Agents | 提出树引导强化学习框架，将稀疏奖励转化为密集步级监督。 | 解决长程记忆操作中奖励稀疏延迟导致端到端优化困难的问题。 | 长程记忆智能体训练 |
| 58 | http://arxiv.org/abs/2602.00415v1 | PolarMem: A Training-Free Polarized Latent Graph Memory for Verifiable Multimodal Agents | 引入极化潜在图记忆，显式存储验证否定作为主要认知状态。 | 解决概率视觉语言模型混淆语义亲和与事实存在及无法编码否定约束的问题。 | 可验证多模态智能体 |
| 59 | http://arxiv.org/abs/2602.00454v1 | Cross-Modal Memory Compression for Efficient Multi-Agent Debate | 引入 DebateOCR，用紧凑图像表示替换长文本辩论痕迹压缩历史。 | 解决多轮辩论中上下文快速增长超出限制及重复总结导致信息丢失的问题。 | 多智能体辩论系统 |
| 60 | http://arxiv.org/abs/2602.00471v1 | Dual Latent Memory for Visual Multi-agent System | 提出 L2-VMAS，解耦感知与思考并动态合成双潜在记忆。 | 解决视觉多智能体系统中文本通信导致信息瓶颈及性能下降的问题。 | 视觉多智能体系统 |
| 61 | http://arxiv.org/abs/2602.21220v1 | Field-Theoretic Memory for AI Agents: Continuous Dynamics for Context Preservation | 提出场论记忆系统，将信息视为由偏微分方程控制的连续场。 | 解决离散数据库记忆难以处理长上下文及多智能体场耦合的问题。 | 长上下文 AI 智能体 |
| 62 | http://arxiv.org/abs/2601.22361v1 | MERMAID: Memory-Enhanced Retrieval and Reasoning with Multi-Agent Iterative Knowledge Grounding for Veracity Assessment | 提出 MERMAID，紧密耦合检索与推理，集成持久记忆模块减少冗余搜索。 | 解决现有方法将证据检索视为静态孤立步骤且无法跨 claim 复用证据问题。 | 真实性评估 |
| 63 | http://arxiv.org/abs/2601.22528v1 | Darwinian Memory: A Training-Free Self-Regulating Memory System for GUI Agent Evolution | 提出 DMS，构建记忆为动态生态系统， governed by 生存竞争法则， pruning 次优路径。 | 解决现有记忆范式难以适应动态 GUI 环境及上下文污染问题。 | GUI 智能体 |

[返回目录](#目录)

<a id="cat-09"></a>

## 具身智能Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2601.00465v1 | Space Debris Removal using Nano-Satellites controlled by Low-Power Autonomous Agents | 低功耗自主Agent控制纳米卫星群自主脱轨 | 太空碎片威胁卫星安全运行 | 太空碎片清理任务 |
| 2 | http://arxiv.org/abs/2601.00555v1 | LLM-Based Agentic Exploration for Robot Navigation & Manipulation with Skill Orchestration | LLM在路口产生约束离散动作，ROS状态机执行门控运动原语 | 室内购物任务端到端执行从指令到多店导航 | 室内机器人导航与操作 |
| 3 | http://arxiv.org/abs/2601.01416v1 | AirSpatialBot: A Spatially-Aware Aerial Agent for Fine-Grained Vehicle Attribute Recognization and Retrieval | 空间感知VLM两阶段训练，动态整合任务规划与空间理解 | 现有遥感VLM空间理解能力有限 | 无人机车辆属性识别检索 |
| 4 | http://arxiv.org/abs/2601.02427v1 | NitroGen: An Open Foundation Model for Generalist Gaming Agents | 4万小时1000+游戏视频训练，统一视觉-动作模型大规模行为克隆 | 缺乏跨游戏泛化能力的通用游戏Agent基础模型 | 通用游戏Agent |
| 5 | http://arxiv.org/abs/2601.02779v1 | Hierarchical Preemptive Holistic Collaborative Systems for Embodied Multi-Agent Systems: Framework, Hybrid Stability, and Scalability Analysis | 三阶段滚动 horizon 机制+Shadow Agent协议 | 去中心化局部极小值与中心化计算复杂性 | 约束物理环境具身多Agent |
| 6 | http://arxiv.org/abs/2601.04191v1 | Embedding Autonomous Agents in Resource-Constrained Robotic Platforms | AgentSpeak 代理集成至资源受限机器人。 | 嵌入式设备缺乏本地自主决策能力。 | 资源受限机器人平台 |
| 7 | http://arxiv.org/abs/2601.13142v1 | TVWorld: Foundations for Remote-Control TV Agents | TVWorld基准+拓扑感知训练框架 | 现有Agent缺乏拓扑感知，长程TV导航能力不足 | 遥控器电视交互Agent |
| 8 | http://arxiv.org/abs/2601.12358v1 | From Prompts to Pavement: LMMs-based Agentic Behavior-Tree Generation Framework for Autonomous Vehicles | LMM 生成自适应行为树规划自动驾驶行为。 | 解决传统行为树静态且需人工调优限制。 | 自动驾驶车辆 |
| 9 | http://arxiv.org/abs/2601.13801v1 | HoverAI: An Embodied Aerial Agent for Natural Human-Drone Interaction | 集成无人机移动性、独立视觉投影和实时对话 AI 于统一平台 | 解决人类占据空间中无人机意图沟通机制不足的问题 | 人机无人机交互 |
| 10 | http://arxiv.org/abs/2601.14091v1 | Zero-shot adaptable task planning for autonomous construction robots: a comparative study of lightweight single and multi-AI agent systems | 提出四种模型使用轻量开源大模型增强任务规划适应性 | 解决建筑机器人成本高及难以适应动态任务的问题 | 自主建筑机器人 |
| 11 | http://arxiv.org/abs/2601.14437v1 | Agentic AI Meets Edge Computing in Autonomous UAV Swarms | 调查集成基于大模型的代理 AI 与边缘计算实现可扩展自主性 | 解决基础设施约束及多代理协调计算需求限制部署 | 自主无人机群 |
| 12 | http://arxiv.org/abs/2601.14681v1 | FARE: Fast-Slow Agentic Robotic Exploration | 集成代理级语义推理与快速局部控制的分层自主探索框架 | 解决自主机器人探索中语义推理与几何决策耦合问题 | 自主机器人探索 |
| 13 | http://arxiv.org/abs/2601.20776v1 | Learning From a Steady Hand: A Weakly Supervised Agent for Robot Assistance under Microscopy | 利用弱监督框架融合校准感知与导纳控制，辅助显微操作 | 提高显微镜引导生物微操作的可靠性与精度 | 显微镜下的机器人辅助操作 |
| 14 | http://arxiv.org/abs/2601.19510v2 | ALRM: Agentic LLM for Robotic Manipulation | 集成策略生成与代理执行，支持代码即策略模式 | 机器人控制中缺乏模块化代理执行机制 | 机器人操作任务 |
| 15 | http://arxiv.org/abs/2601.20334v1 | Demonstration-Free Robotic Control via LLM Agents | 应用软件工程代理框架直接控制具身操作，无需演示 | 视觉语言动作模型需要特定演示且泛化差 | 机器人操作控制 |
| 16 | http://arxiv.org/abs/2601.20367v1 | Unsupervised Anomaly Detection in Multi-Agent Trajectory Prediction via Transformer-Based Models | 多智能体 Transformer 建模正常驾驶，检测偏差 | 监督标记安全关键场景不切实际且规则简单 | 自动驾驶安全场景 |
| 17 | http://arxiv.org/abs/2603.00016v2 | Beyond Static Instruction: A Multi-agent AI Framework for Adaptive Augmented Reality Robot Training | 提出多智能体框架，动态适应 AR 机器人训练环境至学习者需求。 | 解决当前 AR 接口静态无法适应学习者多样认知 profile 的问题。 | 增强现实与机器人训练 |
| 18 | http://arxiv.org/abs/2601.22082v1 | Auditorily Embodied Conversational Agents: Effects of Spatialization and Situated Audio Cues on Presence and Social Perception | 探索听觉体现，通过空间定位语音和环境交互音效传达体现感。 | 解决无视觉模态下（如耳机）如何增强对话代理存在感的问题。 | 听觉对话代理 |
| 19 | http://arxiv.org/abs/2601.22647v1 | Test-Time Mixture of World Models for Embodied Agents in Dynamic Environments | 提出 TMoW，在测试时更新世界模型路由函数， enabling 代理 recombine 现有模型。 | 解决 conventional MoE 部署后 rigid 难以适应 unseen  domains 问题。 | 动态环境具身代理 |

[返回目录](#目录)

<a id="cat-10"></a>

## 人机协作Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2601.00475v1 | Progressive Ideation using an Agentic AI Framework for Human-AI Co-Creation | MIDAS分布式Agent团队模拟人类元认知创意工作流 | 单AI系统产生语义聚类创意缺乏多样性 | 工程设计中的人机协同创意 |
| 2 | http://arxiv.org/abs/2601.02871v2 | SimRPD: Optimizing Recruitment Proactive Dialogue Agents through Simulator-Based Data Evaluation and Selection | 高保真用户模拟器+Chain-of-Intention评估框架 | 高质量目标导向领域特定训练数据稀缺 | 招聘主动对话Agent |
| 3 | http://arxiv.org/abs/2601.06158v2 | PsyAgent: Constructing Human-like Agents Based on Psychological Modeling and Contextual Interaction | Big Five特质先验+社会结构条件耦合 | 人类Agent表达稳定特质同时适应角色规范 | 人格化规范感知Agent |
| 4 | http://arxiv.org/abs/2601.04657v1 | Model of Spatial Human-Agent Interaction with Consideration for Others | 提出考虑他人的空间交互计算模型，量化调整参数 | 机器人在公共空间与人交互时不打扰行人 | 公共空间通信机器人与行人交互 |
| 5 | http://arxiv.org/abs/2601.07181v1 | ShowUI-Aloha: Human-Taught GUI Agent | 四组件流水线将人类屏幕录制转化为结构化可执行任务 | GUI自动化缺乏可扩展的高质量训练数据 | 桌面环境GUI自动化/ShowUI-Aloha |
| 6 | http://arxiv.org/abs/2601.06407v1 | Value of Information: A Framework for Human-Agent Communication | 信息价值框架动态权衡提问效用增益与用户认知成本。 | 解决用户请求未指定时 Agent 行动或打断澄清的决策困境。 | 人机交互与协作决策 |
| 7 | http://arxiv.org/abs/2601.13479v1 | Exploring Learners' Expectations and Engagement When Collaborating with Constructively Controversial Peer Agents | 混合方法研究建设性争议同伴Agent对学习影响 | 同伴Agent设计对学习过程影响不明确 | 异步在线协作学习 |
| 8 | http://arxiv.org/abs/2601.09928v1 | In-Browser Agents for Search Assistance | 混合架构客户端运行，自适应概率模型学习用户策略，SLM 生成建议。 | 解决集中式模型需传输敏感浏览数据限制用户控制及隐私的问题。 | 浏览器内搜索辅助代理 |
| 9 | http://arxiv.org/abs/2601.12134v1 | Human-Human-AI Triadic Programming: Uncovering the Role of AI Agent and the Value of Human Partner in Collaborative Learning | 人 - 人-AI 三方编程增强协作学习与社会存在感。 | 解决 AI 替代人类协作忽视社会学习方面。 | 编程协作学习 |
| 10 | http://arxiv.org/abs/2601.13865v1 | Understanding Human-Multi-Agent Team Formation for Creative Work | 探索用户如何形成人机多代理团队以解决复杂创意工作流 | 解决多代理交互增加复杂性及意外行为风险的问题 | 创意工作协作 |
| 11 | http://arxiv.org/abs/2601.14544v1 | AI Agents vs. Human Investigators: Balancing Automation, Security, and Expertise in Cyber Forensic Analysis | 比较 AI 代理与人类调查员在数字取证分析中的有效性 | 解决 AI 系统基于偏差不完整数据产生误导结果风险 | 网络取证分析 |
| 12 | http://arxiv.org/abs/2601.15034v1 | Visual and Cognitive Demands of a Large Language Model-Powered In-vehicle Conversational Agent | 评估先进大模型对话代理在道路驾驶中的视觉认知需求 | 解决驾驶员分心导致车祸需严格评估新车载技术 | 车载对话代理 |
| 13 | http://arxiv.org/abs/2601.16356v1 | The Behavioral Fabric of LLM-Powered GUI Agents: Human Values and Interaction Outcomes | 14个web任务测试床，注入12个人类偏好和价值观作为persona | 研究用户偏好和价值观如何影响agent决策和行动轨迹 | Web GUI自动化任务 |
| 14 | http://arxiv.org/abs/2601.16392v1 | Toward Agentic Software Project Management: A Vision and Roadmap | 提出Agentic PM作为多agent系统，四种工作模式不同自主级别 | 软件项目管理向SE 3.0演进，保持人类为核心 | 软件项目管理 |
| 15 | http://arxiv.org/abs/2601.16583v1 | Who You Explain To Matters: Learning by Explaining to Conversational Agents with Different Pedagogical Roles | 比较三种教学角色agent(Tutee/Peer/Challenger)对学习动态影响 | 阐明不同教学角色如何影响学习者交互模式、学习成果和体验 | 教育学习支持 |
| 16 | http://arxiv.org/abs/2601.18239v1 | Probing the Future of Meta-Analysis: Eliciting Design Principles via an Agentic Research IDE | 研究 IDE 嵌入多代理后端，支持假设断点验证 | 现有工具脱离认知循环，导致知识产权丧失 | 学术研究与元分析 |
| 17 | http://arxiv.org/abs/2601.18772v1 | Are Conversational AI Agents the Way Out? Co-Designing Reader-Oriented News Experiences with Immigrants and Journalists | 共同设计移民读者导向的新闻体验，协调责任 | 移民读者参与主流新闻困难，价值对齐矛盾 | 新闻阅读体验设计 |
| 18 | http://arxiv.org/abs/2601.20487v2 | Normative Equivalence in Human-AI Cooperation: Behaviour, Not Identity, Drives Cooperation in Mixed-Agent Groups | 发现混合群体中合作规范取决于行为而非身份（人/AI） | 理解 AI Agent 融入人类小组对合作规范的影响 | 人机混合协作小组 |
| 19 | http://arxiv.org/abs/2601.21194v1 | Human-Agent versus Human Pull Requests: A Testing-Focused Characterization and Comparison | 实证比较人类-Agent 与人类 PR 的测试频率与质量 | 揭示人机协作如何塑造软件开发中的测试实践 | 软件开发与代码审查 |
| 20 | http://arxiv.org/abs/2601.19287v1 | Understanding Dominant Themes in Reviewing Agentic AI-authored Code | 大规模实证研究，分析代理生成代码的审查主题 | 缺乏对实践中审查者如何响应 AI 生成代码的了解 | 开源社区代码审查 |
| 21 | http://arxiv.org/abs/2602.10122v1 | A Practical Guide to Agentic AI Transition in Organizations | 提出组织向代理 AI 过渡的实用框架与人机环模型 | 组织缺乏将代理 AI 规模化 operationalize 的指导 | 企业组织流程自动化 |
| 22 | http://arxiv.org/abs/2601.19636v1 | Who Said CVE? How Vulnerability Identifiers Are Mentioned by Humans, Bots, and Agents in Pull Requests | 比较代理、机器人与人类在 PR 中提及漏洞 ID 的差异 | 实践中漏洞标识符的使用情况未被充分理解 | 软件安全维护流程 |
| 23 | http://arxiv.org/abs/2601.20106v1 | Are We All Using Agents the Same Way? An Empirical Study of Core and Peripheral Developers Use of Coding Agents | 实证研究核心与外围开发者使用编码代理的差异 | 自主编码代理时代开发者协作动态尚不清楚 | 软件开发团队协作 |
| 24 | http://arxiv.org/abs/2601.20109v1 | Beyond Bug Fixes: An Empirical Investigation of Post-Merge Code Quality Issues in Agent-Generated Pull Requests | 分析合并后代理生成 PR 的代码质量问题 | 代理生成 PR 合并后的代码质量未被充分探索 | 软件代码质量管理 |
| 25 | http://arxiv.org/abs/2601.20160v1 | How do Agents Refactor: An Empirical Study | 分析代理重构 PR 的类型及对代码质量的影响 | 缺乏对代理如何执行 Java 重构的实践分析 | 软件重构任务 |
| 26 | http://arxiv.org/abs/2601.20171v1 | Who Writes the Docs in SE 3.0? Agent vs. Human Documentation Pull Requests | 分析代理与人类在文档 PR 中的贡献与审查差异 | 代理在文档任务中的角色未被充分探索 | 软件文档工作流 |
| 27 | http://arxiv.org/abs/2602.00496v2 | From Junior to Senior: Allocating Agency and Navigating Professional Growth in Agentic AI-Mediated Software Engineering | 研究初级与高级开发者在 AI 介导软件工程中的代理权分配与成长。 | 解决组织政策约束代理权及新手过度依赖或回避 AI 工具的问题。 | 软件工程与人机协作 |
| 28 | http://arxiv.org/abs/2601.22788v3 | FACET: Multi-Agent AI Supporting Teachers in Scaling Differentiated Learning for Diverse Students | 引入 FACET，teacher-facing 多代理框架， support  differentiation  accounting  for  motivation 等。 | 解决教师 workload 造成 differentiated instruction  barriers 及当前 AI 工具 ignore 其他 aspects 问题。 | 教育差异化学习 |

[返回目录](#目录)

<a id="cat-11"></a>

## 基于Agent的应用系统

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2601.00930v1 | AlignUSER: Human-Aligned LLM Agents via World Models for Recommender System Evaluation | 世界模型驱动Agent从人类交互学习，反事实轨迹对齐人类角色 | 离线指标与真实用户行为差距，交互数据稀缺 | 推荐系统评估 |
| 2 | http://arxiv.org/abs/2601.00770v1 | LLM Agents for Combinatorial Efficient Frontiers: Investment Portfolio Optimization | 新颖Agent框架实现CCPO，自动化大型工作流与算法开发 | 基数约束均值方差投资组合优化求解困难 | 金融机构投资组合优化 |
| 3 | http://arxiv.org/abs/2601.01118v1 | ScienceDB AI: An LLM-Driven Agentic Recommender System for Large-Scale Scientific Data Sharing Services | 科学意图感知器+结构化记忆压缩器+可信RAG两阶段检索 | 科学数据集领域知识复杂传统推荐不足 | 科学数据共享服务平台 |
| 4 | http://arxiv.org/abs/2601.01357v1 | Towards LLM-enabled autonomous combustion research: A literature-aware agent for self-corrective modeling workflows | FlamePilot原子工具确保CFD稳健设置执行，从科学文章学习 | 燃烧建模领域缺乏文献知识与执行能力整合 | 燃烧建模研究 |
| 5 | http://arxiv.org/abs/2601.01891v1 | Agentic AI in Remote Sensing: Foundations, Taxonomy, and Emerging Systems | 首篇遥感领域Agent综合综述与分类法 | 缺乏序列规划和主动工具编排能力 | 地球观测与地理空间分析 |
| 6 | http://arxiv.org/abs/2601.02757v1 | LLM Agent Framework for Intelligent Change Analysis in Urban Environment using Remote Sensing Imagery | ChangeGPT分层结构减轻幻觉 | 缺乏处理多样查询与综合分析的智能 | 遥感城市环境变化监测 |
| 7 | http://arxiv.org/abs/2601.02814v1 | Causal-Enhanced AI Agents for Medical Research Screening | 因果图增强RAG+双级知识图谱 | 系统综述任务中AI幻觉率28-40% | 医学研究文献筛选 |
| 8 | http://arxiv.org/abs/2601.03250v1 | A Versatile Multimodal Agent for Multimedia Content Generation | 技能习得理论建模+两阶段相关性策略 | 当前AIGC模型无法端到端完成真实应用任务 | 多媒体内容自动生成 |
| 9 | http://arxiv.org/abs/2601.03436v1 | MARVEL: A Multi Agent-based Research Validator and Enabler using Large Language Models | 快速路径+DeepSearch模式+全局证据分类账 | 科学组数字助手需求增长 | 领域感知科研辅助 |
| 10 | http://arxiv.org/abs/2601.04687v1 | WebCryptoAgent: Agentic Crypto Trading with Web Informatics | 分解为模态特定Agent，解耦控制架构分离战略与实时风险控制 | 加密货币交易中整合多源web信息与快速应对市场冲击 | 加密货币交易决策系统 |
| 11 | http://arxiv.org/abs/2601.04794v1 | APEX: Academic Poster Editing Agentic Expert | 首个交互式学术海报编辑Agent框架，多级API编辑 | 现有海报生成方法单次通过且非交互式 | 学术海报设计与编辑 |
| 12 | http://arxiv.org/abs/2601.06204v3 | Cascading multi-agent anomaly detection in surveillance systems via vision-language models and embedding-based classification | 级联多Agent框架统一重建、检测与视觉语言推理 | 视觉异常检测实时性与语义可解释性难以兼顾 | 智能视频监控与异常检测系统 |
| 13 | http://arxiv.org/abs/2601.04879v1 | Mind2Report: A Cognitive Deep Research Agent for Expert-Level Commercial Report Synthesis | 认知深度研究Agent模拟商业分析师，动态记忆支持长程过程 | 现有深度研究Agent报告质量、可靠性与覆盖有限 | 商业报告合成与决策支持 |
| 14 | http://arxiv.org/abs/2601.06216v1 | LLM Agents in Law: Taxonomy, Applications, and Challenges | 法律领域LLM Agent全面综述，结构化分类应用与挑战 | 独立模型部署在法律领域面临幻觉、信息过时与可验证性限制 | 法律实践与 autonomous legal assistants |
| 15 | http://arxiv.org/abs/2601.05483v1 | MMUEChange: A Generalized LLM Agent Framework for Intelligent Multi-Modal Urban环境 Change Analysis | 多模态Agent框架灵活整合异构城市数据+模态控制器 | 当前城市环境变化分析依赖刚性单模态方法 | 城市环境变化分析与政策制定 |
| 16 | http://arxiv.org/abs/2601.05520v1 | CHisAgent: A Multi-Agent Framework for Event Taxonomy Construction in Ancient Chinese Cultural Systems | 三阶段角色专用Agent：Inducer+Expander+Enricher构建历史分类法 | 手动分类法构建成本高且难以扩展，LLM历史文化推理能力有限 | 中国古代历史文化知识组织 |
| 17 | http://arxiv.org/abs/2601.03484v1 | From Bits to Chips: An LLM-based Hardware-Aware Quantization Agent for Streamlined Deployment of LLMs | LLM 自动调优量化超参数与硬件配置。 | 解决大模型量化部署复杂且对用户不友好。 | 大模型部署与硬件适配 |
| 18 | http://arxiv.org/abs/2601.03513v1 | Deploy-Master: Automating the Deployment of 50,000+ Agent-Ready Scientific Tools in One Day | 一站式代理工作流，自动发现构建验证科学工具。 | 解决科学软件编译配置难，限制 AI4S 集成。 | 科学计算与 AI4S 工作流 |
| 19 | http://arxiv.org/abs/2601.03768v1 | Agentic Proof Automation: A Case Study | LLM 代理处理证明工程，人类提供策略。 | 解决定理证明脚本编写劳动密集型问题。 | 形式化证明与数学工程 |
| 20 | http://arxiv.org/abs/2601.04285v1 | A Future Capabilities Agent for Tactical Air Traffic Control | 规则基代理嵌入随机数字孪生，冲突解决。 | 平衡空中交通管制的安全保证与可解释性。 | 空中交通管制系统 |
| 21 | http://arxiv.org/abs/2601.04327v1 | ParaCodex: A Profiling-Guided Autonomous Coding Agent for Reliable Parallel Code Generation and Translation | 剖析引导自主编码代理，生成并行代码。 | HPC 并行代码生成正确性与性能难保证。 | 高性能计算与代码生成 |
| 22 | http://arxiv.org/abs/2601.04491v1 | A Closed-Loop Multi-Agent System Driven by LLMs for Meal-Level Personalized Nutrition Management | LLM 多代理控制器，闭环个性化营养管理。 | 现有系统分离食物记录分析与推荐。 | 个性化营养管理 |
| 23 | http://arxiv.org/abs/2601.04497v1 | Vision-Language Agents for Interactive Forest Change Analysis | LLM 驱动代理，集成森林变化分析任务。 | 遥感图像变化解释缺乏语义 captioning。 | 森林变化监测与遥感 |
| 24 | http://arxiv.org/abs/2601.04500v1 | GUITester: Enabling GUI Agents for Exploratory Defect Discovery | 多代理框架解耦导航与验证，主动探测缺陷。 | MLLM 代理优先任务完成，忽略异常报告。 | GUI 测试与缺陷发现 |
| 25 | http://arxiv.org/abs/2601.04505v2 | CircuitLM: A Multi-Agent LLM-Aided Design Framework for Generating Circuit Schematics from Natural Language Prompts | 多代理流水线，生成结构化电路原理图。 | LLM 生成电路图易幻觉且违反物理约束。 | 电子设计自动化 |
| 26 | http://arxiv.org/abs/2601.07252v1 | SwarmFoam: An OpenFOAM Multi-Agent System Based on Multiple Types of Large Language Models | 多模态感知、智能纠错、RAG集成的CFD模拟多Agent框架 | 现有LLM多Agent系统处理复杂几何能力有限 | 计算流体力学模拟/SwarmFoam |
| 27 | http://arxiv.org/abs/2601.07296v1 | LRAS: Advanced Legal Reasoning with Agentic Search | 从封闭循环推理转向动态交互式主动探究 | 法律LLM缺乏知识边界自我意识 | 法律推理领域/LRAS框架 |
| 28 | http://arxiv.org/abs/2601.07315v3 | VLM-CAD: VLM-Optimized Collaborative Agent Design Workflow for Analog Circuit Sizing | Image2Net注释电路图，ExTuRBO可解释贝叶斯优化 | 模拟电路尺寸调整缺乏原理可解释性 | 模拟混合信号电路设计/VLM-CAD |
| 29 | http://arxiv.org/abs/2601.07342v1 | Agentic Diagnostic Reasoning over Telecom and Datacenter Infrastructure | LLM通过MCP协议约束工具空间进行逐步调查 | 传统根因分析维护成本高且紧耦合基础设施模型 | 电信和数据中心基础设施诊断 |
| 30 | http://arxiv.org/abs/2601.07528v1 | From RAG to Agentic RAG for Faithful Islamic Question Answering | 结构化工具调用进行迭代证据寻求和答案修订 | 伊斯兰问答中无依据回答可能带来严重宗教后果 | 伊斯兰问答/ISLAMICFAITHQA基准 |
| 31 | http://arxiv.org/abs/2601.16993v2 | BibAgent: An Agentic Framework for Traceable Miscitation Detection in Scientific Literature | 检索-推理-自适应证据聚合，证据委员会机制处理付费墙 | 系统性引用验证不可行，现有工具受限于摘要分析 | 科学文献引用验证/BibAgent框架 |
| 32 | http://arxiv.org/abs/2601.07711v1 | Is Agentic RAG worth it? An experimental comparison of RAG approaches | Enhanced RAG与Agentic RAG多场景多维度实证比较 | 两种RAG范式优劣条件不清晰 | RAG系统设计与选择 |
| 33 | http://arxiv.org/abs/2601.08192v2 | Route, Retrieve, Reflect, Repair: Self-Improving Agentic Framework for Visual Detection and Linguistic Reasoning in Medical Imaging | 四协调Agent分解医疗影像工作流，迭代修订输出 | 医疗影像系统单程黑盒缺乏推理控制和安全 | 医学影像分析/胸部X光分析 |
| 34 | http://arxiv.org/abs/2601.06232v1 | Multi-Agent Framework for Controllable and Protected Generative Content Creation: Addressing Copyright and Provenance in AI-Generated Media | 多 Agent 框架集成水印与版权保护，确保内容可控与可追溯。 | 解决生成式 AI 内容的版权侵权与来源追溯难题。 | 生成式内容创作与版权保护 |
| 35 | http://arxiv.org/abs/2601.05777v1 | EET: Experience-Driven Early Termination for Cost-Efficient Software Engineering Agents | 经验驱动的早期终止机制，减少无效迭代以降低 Agent 成本。 | 降低软件工程 Agent 的货币成本同时保持任务性能。 | 软件工程自动化 Agent |
| 36 | http://arxiv.org/abs/2601.06241v1 | Agentic AI Microservice Framework for Deepfake and Document Fraud Detection in KYC Pipelines | 微服务框架集成多模态检测与策略驱动风险引擎。 | 解决传统 KYC 系统缺乏扩展性与对抗适应性 fraud 检测问题。 | 金融身份验证与反欺诈 |
| 37 | http://arxiv.org/abs/2601.06268v2 | Automated QoR improvement in OpenROAD with coding agents | 自主代码 Agent 系统读取 OpenROAD 并提出执行 PPA 改进。 | 解决 EDA 开发中专家工程资源稀缺限制技术创新的问题。 | 电子设计自动化 (EDA) |
| 38 | http://arxiv.org/abs/2601.06373v1 | DemMA: Dementia Multi-Turn Dialogue Agent with Expert-Guided Reasoning and Action Simulation | 专家指导构建临床基础痴呆人格，模拟非语言行为与认知障碍。 | 解决 LLM 模拟痴呆患者缺乏高保真认知与情感动态的问题。 | 医疗培训与痴呆症模拟 |
| 39 | http://arxiv.org/abs/2601.06498v1 | Spec-o3: A Tool-Augmented Vision-Language Agent for Rare Celestial Object Candidate Vetting via Automated Spectral Inspection | 工具增强视觉语言 Agent，通过交错多模态思维链进行光谱检查。 | 解决罕见天体候选者最终审查依赖人工且无法扩展的瓶颈。 | 天文学光谱数据分析 |
| 40 | http://arxiv.org/abs/2601.06606v1 | CEDAR: Context Engineering for Agentic Data Science | 上下文工程应用，自动化数据科学任务与代码块生成。 | 解决 LLM 解决数据科学问题中的任务复杂性与上下文限制。 | 自动化数据科学任务 |
| 41 | http://arxiv.org/abs/2601.06640v1 | Agentic AI Empowered Intent-Based Networking for 6G | 分层多 Agent 框架自主分解自然语言意图配置网络切片。 | 解决 6G 网络中意图翻译缺乏可解释性与操作约束执行问题。 | 6G 网络自动化编排 |
| 42 | http://arxiv.org/abs/2601.06776v1 | From Text to Simulation: A Multi-Agent LLM Workflow for Automated Chemical Process Design | 多 Agent 工作流实现从文本规范到计算验证软件配置的端到端自动化。 | 解决化学过程设计中将流程图转换为可执行仿真耗时费力问题。 | 化学工程过程设计 |
| 43 | http://arxiv.org/abs/2601.08288v1 | OpenMic: A Multi-Agent-Based Stand-Up Comedy Generation System | 构建端到端多智能体系统，迭代优化幽默、 timing 与表演性，生成脱口秀视频。 | 解决中文脱口秀生成缺乏文化根基与长程推理问题。 | 中文脱口秀生成 |
| 44 | http://arxiv.org/abs/2601.18799v1 | Agentic Digital Twins: A Taxonomy of Capabilities for Understanding Possible Futures | 提出智能体数字孪生能力分类法，分析从被动工具到本体重构的演进。 | 解决数字孪生从镜像世界到新本体架构师的转型理解问题。 | 数字孪生系统 |
| 45 | http://arxiv.org/abs/2601.08641v3 | Resisting Manipulative Bots in Meme Coin Copy Trading: A Multi-Agent Approach with Chain-of-Thought Reasoning | 提出基于多智能体与 CoT 推理的抗操纵跟单交易系统。 | 解决 meme 币市场中机器人操纵与价值提取问题。 | 加密货币跟单交易 |
| 46 | http://arxiv.org/abs/2601.08676v2 | Advancing ESG Intelligence: An Expert-level Agent and Comprehensive Benchmark for Sustainable Finance | 引入分层多智能体系统与专用工具集，生成深度 ESG 分析报告。 | 解决专业 ESG 分析受数据碎片化及工作流复杂阻碍问题。 | 可持续金融分析 |
| 47 | http://arxiv.org/abs/2601.09027v2 | Agentic AI and Machine Learning for Accelerated Materials Discovery and Applications | 综述 AI 与智能体 AI 在材料发现及相关领域的应用进展与核心概念。 | 解决高效发现需求与核心概念及应用场景的梳理问题。 | 材料发现与化学 |
| 48 | http://arxiv.org/abs/2601.17002v1 | RAM-SD: Retrieval-Augmented Multi-agent framework for Sarcasm Detection | 通过四阶段流程结合检索与多智能体互补分析，实现可解释讽刺检测。 | 解决讽刺检测依赖细微上下文理解与多样化分析需求问题。 | 自然语言处理任务 |
| 49 | http://arxiv.org/abs/2601.09129v1 | KryptoPilot: An Open-World Knowledge-Augmented LLM Agent for Automated Cryptographic Exploitation | 集成动态开放世界知识获取与治理子系统，实现自动化密码利用。 | 解决 LLM 智能体在高难度密码 CTF 挑战中知识粒度不足问题。 | 网络安全 CTF 竞赛 |
| 50 | http://arxiv.org/abs/2601.11634v1 | When Rules Fall Short: Agent-Driven Discovery of Emerging Content Issues in Short Video Platforms | 提出基于多模态 LLM 智能体的自动问题发现方法，更新标注策略。 | 解决传统人工发现新兴内容问题速度慢导致策略更新延迟问题。 | 短视频平台内容治理 |
| 51 | http://arxiv.org/abs/2601.14288v1 | DeepInflation: an AI agent for research and model discovery of inflation | 集成 LLM 与符号回归引擎及 RAG 知识库，自动探索验证通胀势 landscape。 | 解决通胀宇宙学研究中模型发现与理论背景 grounding 问题。 | 宇宙学研究 |
| 52 | http://arxiv.org/abs/2601.09342v2 | Improving Implicit Hate Speech Detection via a Community-Driven Multi-Agent Framework | 构建包含 Moderator 与动态 Community Agents 的多智能体系统，整合社会文化上下文。 | 解决隐式仇恨言语检测缺乏身份感知 moderation 问题。 | 内容审核与 moderation |
| 53 | http://arxiv.org/abs/2601.09413v1 | Speech-Hands: A Self-Reflection Voice Agentic Approach to Speech Recognition and Audio Reasoning with Omni Perception | 重构问题为显式自反思决策，学习何时信任自身或咨询外部音频感知。 | 解决 Omni 模型微调后因噪声假设导致性能下降问题。 | 语音识别与音频推理 |
| 54 | http://arxiv.org/abs/2601.12522v2 | Improved Bug Localization with AI Agents Leveraging Hypothesis and Dynamic Cognition | CogniGent多Agent因果推理和假设测试 | 传统方法忽视代码组件连接，LLM缺乏因果推理能力 | 软件缺陷定位与调试 |
| 55 | http://arxiv.org/abs/2601.12607v1 | A Cloud-based Multi-Agentic Workflow for Science | 云端领域无关多Agent科学工作流框架 | LLM无法执行复杂任务，工作流平衡困难 | 科学计算与研究辅助 |
| 56 | http://arxiv.org/abs/2601.12754v1 | PAIR-SAFE: A Paired-Agent Approach for Runtime Auditing and Refining AI-Mediated Mental Health Support | 响应者+监督者双Agent，MITI-4临床框架审计 | LLM心理支持响应过度指令化、临床不一致 | AI心理健康咨询支持 |
| 57 | http://arxiv.org/abs/2601.12815v5 | Multimodal Multi-Agent Empowered Legal Judgment Prediction | JurisMMA框架分解审判任务，多模态数据集 | 传统方法难以处理多重指控和多样证据 | 法律判决预测系统 |
| 58 | http://arxiv.org/abs/2601.13114v1 | IntAgent: NWDAF-Based Intent LLM Agent Towards Advanced Next Generation Networks | 意图工具引擎集成NWDAF分析，3GPP合规数据源 | 现有方法缺乏实时网络分析支持意图履行 | 下一代网络运营自动化 |
| 59 | http://arxiv.org/abs/2601.13481v1 | Towards Efficient and Robust Linguistic Emotion Diagnosis for Mental Health via Multi-Agent Instruction Refinement | APOLO多Agent指令优化框架，五角色协作闭环 | 情感共病和临床线索探索低效，提示设计敏感 | 心理健康语言情感诊断 |
| 60 | http://arxiv.org/abs/2601.13508v1 | CatMaster: An Agentic Autonomous System for Computational Heterogeneous Catalysis Research | LLM驱动Agent生成完整计算工作空间，持久项目记录 | DFT工作流成本高、迭代敏感、记录难维护 | 计算催化研究系统 |
| 61 | http://arxiv.org/abs/2601.13559v1 | AgentGC: Evolutionary Learning-based Lossless Compression for Genomics Data with LLM-driven Multiple Agent | 三层多Agent进化学习压缩框架，三模式支持 | 现有学习压缩方法不可进化，建模低级且适应性有限 | 基因组数据压缩管理 |
| 62 | http://arxiv.org/abs/2601.13589v1 | Motion-to-Response Content Generation via Multi-Agent AI System with Real-Time Safety Verification | 四Agent协作 pipeline，显式安全验证循环 | 传统情感识别仅分类，缺乏安全可控内容生成 | 儿童媒体/治疗/情感响应设备 |
| 63 | http://arxiv.org/abs/2601.13597v2 | AI IDEs or Autonomous Agents? Measuring the Impact of Coding Agents on Software Development | 纵向因果研究，差异中差分分析Agent采用影响 | 编码Agent真实影响不清，尤其对比IDE助手 | 开源软件项目开发 |
| 64 | http://arxiv.org/abs/2601.13653v1 | TimeART: Towards Agentic Time Series Reasoning via Tool-Augmentation | TimeART融合工具分析与LLM推理，四阶段训练策略 | 时间序列分析依赖人工，成本高且缺乏自动化 | 时间序列问答系统 |
| 65 | http://arxiv.org/abs/2601.09440v1 | DepRadar: Agentic Coordination for Context Aware Defect Impact Analysis in Deep Learning Libraries | 协调四 specialized 代理分析缺陷语义，结合静态分析与领域规则评估影响。 | 解决深度学习库缺陷影响分析难及下游用户受影响评估复杂的问题。 | 深度学习库维护与用户 |
| 66 | http://arxiv.org/abs/2601.09771v1 | PCN-Rec: Agentic Proof-Carrying Negotiation for Reliable Governance-Constrained Recommendation | 证明携带协商管道分离自然语言推理与确定性执行，确保证书可验证。 | 解决 LLM 推荐系统难以可靠满足治理约束如多样性要求的问题。 | 受治理约束的推荐系统 |
| 67 | http://arxiv.org/abs/2601.09680v1 | Automating Supply Chain Disruption Monitoring via an Agentic AI Approach | 七专用代理自主监控分析响应 disruptions，映射多层供应商网络。 | 解决供应链缺乏 Tier-1 以外可见性及被动恢复而非主动韧性的问题。 | 供应链 disruption 监控 |
| 68 | http://arxiv.org/abs/2601.09980v1 | Performance of AI agents based on reasoning language models on ALD process optimization tasks | 推理 LLM 代理迭代交互 ALD 反应器，无先验知识自主优化剂量时间。 | 解决原子层沉积工艺优化需专家知识及缺乏自主 unsupervised 优化问题。 | 化学工艺优化任务 |
| 69 | http://arxiv.org/abs/2601.10020v1 | EHRNavigator: A Multi-Agent System for Patient-Level Clinical Question Answering over Heterogeneous Electronic Health Records | 多代理框架利用 AI 代理跨异构多模态 EHR 数据执行患者级问答。 | 解决现有 QA 系统仅评估基准数据集限制实际临床部署相关性的问题。 | 电子健康记录临床问答 |
| 70 | http://arxiv.org/abs/2601.10131v2 | M^4olGen: Multi-Agent, Multi-Stage Molecular Generation under Precise Multi-Property Constraints | 片段级检索增强两阶段框架，多代理推理器执行检索锚定片段编辑。 | 解决 LLM 难以精确多目标控制及无数值推理外部结构反馈的分子生成。 | 多属性约束分子生成 |
| 71 | http://arxiv.org/abs/2601.10161v2 | AWED-FiNER: Agents, Web applications, and Expert Detectors for Fine-grained Named Entity Recognition across 36 Languages for 6.6 Billion Speakers | 代理工具路由多语文本至专家模型，提供 36 种语言细粒度 NER 解决方案。 | 解决多语言细粒度命名实体识别缺乏覆盖广泛语言及资源受限部署问题。 | 多语言 NER 任务 |
| 72 | http://arxiv.org/abs/2601.10194v1 | Autonomous Quantum Simulation through Large Language Model Agents | LLM 代理自主执行张量网络模拟，结合 in-context 学习与多代理分解。 | 解决量子模拟有效使用需多年研究生训练 expertise 及自动化程度低问题。 | 量子多体系统模拟 |
| 73 | http://arxiv.org/abs/2601.10220v1 | Agentic Pipelines in Embedded Software Engineering: Emerging Practices and Challenges | 定性研究识别嵌入式软件工程采用生成式 AI 的 emergent 实践与挑战。 | 解决嵌入式环境严格确定性可靠性要求对采用生成式技术构成的独特挑战。 | 嵌入式软件工程团队 |
| 74 | http://arxiv.org/abs/2601.10223v1 | STEAMROLLER: A Multi-Agent System for Inclusive Automatic Speech Recognition for People who Stutter | 三阶段架构含 ASR 转录、多代理文本修复及语音合成，迭代优化转录。 | 解决当前 ASR 系统主要训练于流利语音导致口吃者被系统性排除问题。 | 口吃者语音识别辅助 |
| 75 | http://arxiv.org/abs/2601.11650v2 | Large Language Model Agent for User-friendly Chemical Process Simulations | LLM 代理集成 AVEVA Process Simulation，通过 MCP 协议自然语言交互。 | 解决构建解释模拟耗时需专家知识限制 inexperienced 用户早期探索问题。 | 化学过程模拟教育与实践 |
| 76 | http://arxiv.org/abs/2601.10581v1 | From Single to Multi-Agent Reasoning: Advancing GeneGPT for Genomics QA | 多代理框架高效协调专用代理处理复杂基因组查询，灵活架构扩展领域。 | 解决 GeneGPT 受 rigid API 依赖限制及适应性强提取专家知识需求问题。 | 基因组问答任务 |
| 77 | http://arxiv.org/abs/2601.10820v1 | Towards Reliable ML Feature Engineering via Planning in Constrained-Topology of LLM Agents | 规划器引导的约束拓扑多智能体框架，生成代码。 | 解决生产级特征工程中数据稀缺和协作不佳问题。 | 机器学习团队特征工程 |
| 78 | http://arxiv.org/abs/2601.10865v1 | Multi-Agent Taint Specification Extraction for Vulnerability Detection | 结合 LLM 语义理解与静态分析提取污点规范。 | 解决 JavaScript 动态特性导致污点分析困难问题。 | 软件安全漏洞检测 |
| 79 | http://arxiv.org/abs/2602.06975v1 | BiomechAgent: AI-Assisted Biomechanical Analysis Through Code-Generating Agents | 代码生成 Agent 实现自然语言查询生物力学数据。 | 解决临床医生无编程 expertise 分析运动数据难。 | 生物力学临床分析 |
| 80 | http://arxiv.org/abs/2602.00019v1 | AutoBinder Agent: An MCP-Based Agent for End-to-End Protein Binder Design | 基于 MCP 协议协调多工具进行端到端药物设计。 | 解决药物发现工作流碎片化及集成开销高问题。 | 蛋白质结合剂设计 |
| 81 | http://arxiv.org/abs/2601.11688v1 | SpecMap: Hierarchical LLM Agent for Datasheet-to-Code Traceability Link Recovery in Systems Engineering | 分层映射方法恢复数据表与代码间的追溯链接。 | 解决嵌入式系统手动映射规范与代码不可行。 | 系统工程追溯性 |
| 82 | http://arxiv.org/abs/2601.11958v1 | Autonomous Market Intelligence: Agentic AI Nowcasting Predicts Stock Returns | 完全 Agent 自主搜索网络预测股票回报。 | 解决传统现在预测框架存在前瞻偏差问题。 | 金融市场情报 |
| 83 | http://arxiv.org/abs/2601.12024v1 | A Multi-Agent System for Generating Actionable Business Advice | 多智能体框架将评论转化为可操作商业建议。 | 解决现有分析方法缺乏深度推理与准确性。 | 商业决策支持 |
| 84 | http://arxiv.org/abs/2601.12148v3 | Many Hands Make Light Work: An LLM-based Multi-Agent System for Detecting Malicious PyPI Packages | 协作 LLM 多智能体系统检测恶意 PyPI 包。 | 解决传统规则工具忽视源代码语义模式。 | 软件供应链安全 |
| 85 | http://arxiv.org/abs/2602.00030v2 | RAPTOR-AI for Disaster OODA Loop: Hierarchical Multimodal RAG with Experience-Driven Agentic Decision-Making | 分层多模态 RAG 支持灾害响应 OODA 循环决策。 | 解决传统系统难以合成碎片化多模态灾害数据。 | 人道主义灾难救援 |
| 86 | http://arxiv.org/abs/2601.13694v1 | Generative Intent Prediction Agentic AI empowered Edge Service Function Chain Orchestration | 提出生成式意图预测代理，将被动执行转变为主动预测与编排 | 解决边缘网络中高用户移动性和隐式服务意图带来的管理挑战 | 边缘服务功能链编排 |
| 87 | http://arxiv.org/abs/2601.13843v1 | Small Models, Big Impact: Tool-Augmented AI Agents for Wireless Network Planning | 编排专用计算工具而非将领域知识编码于模型参数中 | 解决大模型计算需求大及生成技术错误信息的问题 | 无线网络规划 |
| 88 | http://arxiv.org/abs/2601.14434v2 | CMind: An AI Agent for Localizing C Memory Bugs | 结合大模型推理与模仿人类行为的引导决策 | 解决 C 程序内存 bug 定位依赖人工 expertise 问题 | C 内存 bug 定位 |
| 89 | http://arxiv.org/abs/2601.14470v1 | Tokenomics: Quantifying Where Tokens Are Used in Agentic Software Engineering | 分析软件开发生命周期中代理系统的 token 消耗模式 | 解决操作效率及资源消耗理解不足阻碍实际采用 | 代理软件工程 |
| 90 | http://arxiv.org/abs/2601.14601v1 | Holmes: An Evidence-Grounded LLM Agent for Auditable DDoS Investigation in Cloud Networks | 将模型重构为虚拟 SRE 调查员而非端到端分类器 | 解决现有方法输出黑盒分数及泛化性差的问题 | 云网络 DDoS 调查 |
| 91 | http://arxiv.org/abs/2601.14637v2 | Forest-Chat: Adapting Vision-Language Agents for Interactive Forest Change Analysis | 构建多级变化解释视觉语言骨干与大模型编排 | 解决遥感图像变化解释中像素级检测与语义解释挑战 | 森林变化分析 |
| 92 | http://arxiv.org/abs/2603.06583v1 | XInsight: Integrative Stage-Consistent Psychological Counseling Support Agents for Digital Well-Being | 呈现咨询启发的多代理框架建模心理支持为阶段一致工作流 | 解决大多数 LLM 驱动聊天机器人不透明且弱 grounded 问题 | 数字健康心理支持 |
| 93 | http://arxiv.org/abs/2601.15109v2 | An Agentic Operationalization of DISARM for FIMI Investigation on Social Media | 框架无关的agent协作管道，检测并映射操纵行为到DISARM分类 | 规模化FIMI分析工作，提升态势感知和数据互操作性 | 社交媒体信息操纵调查 |
| 94 | http://arxiv.org/abs/2601.15195v1 | Where Do AI Coding Agents Fail? An Empirical Study of Failed Agentic Pull Requests in GitHub | 大规模研究33k agent-authored PRs，构建拒绝模式分类体系 | 分析AI编码agent PR失败原因，揭示人机协作关键因素 | GitHub代码贡献场景 |
| 95 | http://arxiv.org/abs/2601.16238v1 | VibeTensor: System Software for Deep Learning, Fully Generated by AI Agents | LLM编码agent生成完整深度学习系统软件栈 | 验证coding agent可生成从语言绑定到CUDA内存管理的 coherent系统 | 深度学习系统软件开发 |
| 96 | http://arxiv.org/abs/2602.00082v1 | Design and Empirical Study of a Large Language Model-Based Multi-Agent Investment System for Chinese Public REITs | 四类分析agent协作，预测agent整合信号，决策agent生成调仓信号 | 提升REITs交易风险调整收益，小模型微调接近或优于大模型 | 中国公募REITs投资 |
| 97 | http://arxiv.org/abs/2601.16376v2 | Polymer-Agent: Large Language Model Agent for Polymer Design | 闭环聚合物结构 - 属性预测器集成终端，SMILES序列 guided by合成可及性 | 解决实验室研究人员无法访问代码模型提取结构和属性问题 | 早期聚合物发现 |
| 98 | http://arxiv.org/abs/2601.16409v2 | Gen-DBA: Generative Database Agents | 单一通用基础模型优化数据库，具备agentic能力 | 解决ML4DB窄专用模型可移植性和泛化能力有限问题 | 数据库系统优化 |
| 99 | http://arxiv.org/abs/2601.17084v1 | ChemNavigator: Agentic AI Discovery of Design Rules for Organic Photocatalysts | 多agent架构镜像科学方法，自主推导结构 - 属性关系 | 克服化学空间巨大和依赖人类直觉进行分子设计的限制 | 有机光催化剂发现 |
| 100 | http://arxiv.org/abs/2601.16565v1 | Agentic AI-RAN Empowering Synergetic Sensing, Communication, Computing, and Control | 任务导向Agentic AI-RAN架构在单边缘节点内实现SC3任务执行 | 解决资源受限边缘环境中异构工作负载协调根本问题 | 6G低空无线网络 |
| 101 | http://arxiv.org/abs/2602.15859v1 | From Transcripts to AI Agents: Knowledge Extraction, RAG Integration, and Robust Evaluation of Conversational AI Assistants | 从通话记录端到端构建对话代理，RAG  grounding | 噪声数据与碎片化知识导致可靠手递困难 | 客服对话助手构建 |
| 102 | http://arxiv.org/abs/2601.18381v1 | AI Agent for Reverse-Engineering Legacy Finite-Difference Code and Translating to Devito | 混合 LangGraph 架构逆向工程遗留代码至 Devito | 遗留有限差分代码转换困难，缺乏上下文 | 科学计算代码迁移 |
| 103 | http://arxiv.org/abs/2601.18496v2 | DEEPMED: Building a Medical DeepResearch Agent via Multi-hop Med-Search Data and Turn-Controlled Agentic Training & Inference | 医疗深搜代理，难度感知回合惩罚抑制过度工具调用 | 通用深搜模型缺乏临床上下文推理能力 | 医疗深度研究 |
| 104 | http://arxiv.org/abs/2601.18563v1 | An LLM-Agent-Based Framework for Age of Information Optimization in Heterogeneous Random Access Networks | Reflex-Core 框架优化异构网络信息年龄 | 现有策略假设理想化，收敛慢泛化差 | 物联网随机接入网络 |
| 105 | http://arxiv.org/abs/2602.06980v2 | Potential Role of Agentic Artificial Intelligence in Toxicologic Pathology | 探讨代理 AI 在毒理病理报告中的协调工作流 | 非临床研究数据碎片化，报告时效性挑战 | 毒理病理学报告 |
| 106 | http://arxiv.org/abs/2601.16886v1 | MAGE-KT: Multi-Agent Graph-Enhanced Knowledge Tracing with Subgraph Retrieval and Asymmetric Fusion | 多智能体图增强知识追踪，检索紧凑高价值子图融合 | 知识概念关系表示不足，全图编码计算成本高 | 学生知识追踪与成绩预测 |
| 107 | http://arxiv.org/abs/2601.17303v1 | Decentralized Multi-Agent Swarms for Autonomous Grid Security in Industrial IoT: A Consensus-based Approach | 去中心化多智能体 swarm 架构，边缘网关自主 AI 代理分布式免疫 | 集中式安全监控延迟高，易被攻击者利用 | 工业物联网网络安全 |
| 108 | http://arxiv.org/abs/2601.17346v1 | Multi-Agent Learning Path Planning via LLMs | 多智能体学习路径规划框架，基于角色规则协作分析学习 profile | 现有学习路径规划缺乏透明度、适应性和可解释性 | 高等教育个性化学习系统 |
| 109 | http://arxiv.org/abs/2601.17413v1 | When AI Agents Touch CI/CD Configurations: Frequency and Success | 分析智能体 PR 中 CI/CD 配置修改频率与成功率，发现配置专业化 | 智能体与 CI/CD 配置交互研究不足 | 软件开发与 DevOps 自动化 |
| 110 | http://arxiv.org/abs/2601.17471v1 | PatchIsland: Orchestration of LLM Agents for Continuous Vulnerability Repair | 持续漏洞修复系统，集成模糊测试管道，多智能体 ensemble 覆盖广 | 现有自动漏洞修复不适用于持续模糊测试环境 | 软件漏洞持续修复 |
| 111 | http://arxiv.org/abs/2601.17581v2 | How AI Coding Agents Modify Code: A Large-Scale Study of GitHub Pull Requests | 大规模实证分析智能体 PR 与人类贡献在代码修改描述上的差异 | 缺乏智能体生成 PR 与人类贡献差异的实证证据 | 开源软件开发工作流 |
| 112 | http://arxiv.org/abs/2601.17617v2 | Agentic Search in the Wild: Intents and Trajectory Dynamics from 14M+ Real Search Requests | 大规模日志分析智能体搜索会话，提出上下文驱动术语采用率 | IR 社区缺乏对智能体搜索会话展开实证理解 | 搜索引擎智能体行为分析 |
| 113 | http://arxiv.org/abs/2601.17627v1 | Code Change Characteristics and Description Alignment: A Comparative Study of Agentic versus Human Pull Requests | 比较智能体与人类 PR 代码变更特征与消息质量，发现微观精度宏观沟通差距 | 智能体贡献与人类对比研究不足，影响可靠性评估 | 软件开发代码审查 |
| 114 | http://arxiv.org/abs/2602.00103v1 | Autonomous Multi-Agent AI for High-Throughput Polymer Informatics: From Property Prediction to Generative Design Across Synthetic and Bio-Polymers | 集成多智能体 AI 生态系统，统一高通量材料工作流与计算建模 | 聚合物发现缺乏统一高效端到端任务执行框架 | 高分子材料科学与发现 |
| 115 | http://arxiv.org/abs/2601.17692v1 | LegalMALR:Multi-Agent Query Understanding and LLM-Based Reranking for Chinese Statute Retrieval | 多智能体查询理解系统与零样本 LLM 重排序模块集成 | 真实法律查询隐式多issue，常规 RAG 难以恢复法定要素 | 中国法律条文检索 |
| 116 | http://arxiv.org/abs/2601.17762v1 | Multi-Agent End-to-End Vulnerability Management for Mitigating Recurring Vulnerabilities | 多智能体框架端到端重复漏洞管理，集成知识库与上下文检索工具 | 现有自动方法不足以捕捉上下文依赖与历史知识 | 软件漏洞管理与修复 |
| 117 | http://arxiv.org/abs/2601.17817v1 | Multi-Agent Collaborative Intrusion Detection for Low-Altitude Economy IoT: An LLM-Enhanced Agentic AI Framework | 多智能体协作入侵检测框架，利用专用 LLM 增强智能体处理数据 | 传统 IDS 不适用于低空经济 IoT 动态三维移动模式 | 低空经济物联网安全 |
| 118 | http://arxiv.org/abs/2601.17842v2 | EFT-CoT: A Multi-Agent Chain-of-Thought Framework for Emotion-Focused Therapy | 基于情绪聚焦治疗的多智能体思维链框架，八专用智能体建模关键过程 | 现有 MHQA 依赖 CBT，缺乏具身体验与初级情绪处理支持 | 心理健康问答与支持 |
| 119 | http://arxiv.org/abs/2601.17920v1 | Agentic AI for Self-Driving Laboratories in Soft Matter: Taxonomy, Benchmarks,and Open Challenges | 综述软物质自驱动实验室 AI 问题，提出能力驱动分类法与基准 | 自驱动实验室 autonomy 缺乏统一 AI 原则连接与基准 | 软物质自驱动实验室 |
| 120 | http://arxiv.org/abs/2601.18833v1 | Agentic Business Process Management Systems | 提出代理业务过程管理系统架构愿景，集成 autonomy 推理学习 | 业务过程管理从自动化向 autonomy 转变缺乏平台支持 | 业务过程管理与执行 |
| 121 | http://arxiv.org/abs/2601.20404v1 | On the Impact of AGENTS.md Files on the Efficiency of AI Coding Agents | 分析 AGENTS.md 文件对 AI 编码 Agent 运行时和 Token 消耗的影响 | 优化代码仓库配置以提升 AI 编码 Agent 效率 | 软件开发与 GitHub 工作流 |
| 122 | http://arxiv.org/abs/2601.20709v1 | MedViz: An Agent-based, Visual-guided Research Assistant for Navigating Biomedical Literature | 集成多 AI Agent 与交互可视化，支持生物医学文献探索 | 改善传统搜索引擎对大规模文献的全局探索支持 | 生物医学研究人员 |
| 123 | http://arxiv.org/abs/2601.21113v1 | Planner-Auditor Twin: Agentic Discharge Planning with FHIR-Based LLM Planning, Guideline Recall, Optional Caching and Self-Improvement | 提出 Planner-Auditor 框架，解耦生成与确定性验证 | 减少临床出院计划中的幻觉与遗漏，提升安全性 | 医疗临床出院规划 |
| 124 | http://arxiv.org/abs/2601.21253v1 | CovAgent: Overcoming the 30% Curse of Mobile Application Coverage with Agentic AI and Dynamic Instrumentation | 提出 CovAgent，利用 Agent 检查代码逻辑生成动态插桩脚本 | 突破 Android 应用 UI 测试覆盖率 30% 的限制 | Android 应用自动化测试 |
| 125 | http://arxiv.org/abs/2601.21347v1 | Towards Robust Dysarthric Speech Recognition: LLM-Agent Post-ASR Correction Beyond WER | 引入 LLM Agent 进行后 ASR 校正，关注语义 fidelity | 解决构音障碍语音识别中 WER 与语义不匹配问题 | 医疗辅助与语音识别 |
| 126 | http://arxiv.org/abs/2601.21372v1 | NEMO: Execution-Aware Optimization Modeling via Autonomous Coding Agents | 系统 NEMO 将自然语言决策问题转化为可执行优化模型 | 解决现有方法生成代码无效或不可执行的问题 | 自动化优化建模 |
| 127 | http://arxiv.org/abs/2601.21403v1 | DataCross: A Unified Benchmark and Agent Framework for Cross-Modal Heterogeneous Data Analysis | 提出 DataCross 框架，协调子 Agent 分析异构数据模态 | 激活非结构化视觉文档中的“僵尸数据”进行跨模态分析 | 企业决策与数据科学 |
| 128 | http://arxiv.org/abs/2601.21609v1 | RecNet: Self-Evolving Preference Propagation for Agentic Recommender Systems | 提出 RecNet，自进化偏好传播框架，主动传播实时更新 | 解决推荐系统中显式交互稀疏与实时相互影响建模难问题 | 代理推荐系统 |
| 129 | http://arxiv.org/abs/2601.19138v1 | AgenticSCR: An Autonomous Agentic Secure Code Review for Immature Vulnerabilities Detection | 引入安全语义记忆的智能体，自主检测代码漏洞 | 预提交阶段不成熟漏洞检测率低、上下文受限问题 | 软件安全代码审查 |
| 130 | http://arxiv.org/abs/2601.19263v1 | A Reconfigurable Framework for AI-FPGA Agent Integration and Acceleration | 运行时软件代理动态划分模型，硬件加速推理 | AI  workload 映射到 FPGA 的复杂性和数据编排问题 | AI-FPGA 硬件集成加速 |
| 131 | http://arxiv.org/abs/2602.13227v1 | An Agentic AI Control Plane for 6G Network Slice Orchestration, Monitoring, and Trading | 代理 AI 控制平面，市场感知编排与自然语言接口 | 5G 静态策略无法适应 6G 动态多域环境 | 6G 网络切片管理 |
| 132 | http://arxiv.org/abs/2601.19607v1 | ComAgent: Multi-LLM based Agentic AI Empowered Intelligent Wireless Networks | 多 LLM 代理闭环循环，自动生成求解器公式 | 手动将高层意图转化为数学公式的瓶颈 | 无线通信网络优化 |
| 133 | http://arxiv.org/abs/2601.19747v1 | Veri-Sure: A Contract-Aware Multi-Agent Framework with Temporal Tracing and Formal Verification for Correct RTL Code Generation | 设计契约对齐意图，形式化验证保证 RTL 正确性 | LLM 生成 RTL 代码的硅级正确性瓶颈 | 电子设计自动化 (EDA) |
| 134 | http://arxiv.org/abs/2601.20005v1 | OptAgent: an Agentic AI framework for Intelligent Building Operations | 物理信息机器学习环境，11 个专家代理协调能源操作 | 建筑能源操作依赖人工工程工作流 | 建筑能源管理与脱碳 |
| 135 | http://arxiv.org/abs/2601.20048v2 | Insight Agents: An LLM-Based Multi-Agent System for Data Insights | 分层多智能体结构，经理代理路由与工人代理执行 | 电商卖家难以利用丰富数据做出商业决策 | 电商数据洞察系统 |
| 136 | http://arxiv.org/abs/2601.20194v1 | An Autonomous Agent Framework for Feature-Label Extraction from Device Dialogues and Automatic Multi-Dimensional Device Hosting Planning Based on Large Language Models | 双层合作架构，记忆标签提取与推理驱动规划 | 传统家电缺乏主动感知与个性化空气管理能力 | 智能家居空气系统 |
| 137 | http://arxiv.org/abs/2601.20206v1 | Towards Intelligent Urban Park Development Monitoring: LLM Agents for Multi-Modal Information Fusion and Analysis | 多模态 LLM 代理框架，水平垂直数据对齐机制 | 传统遥感方法难以满足城市规划高阶分析需求 | 城市公园发展监测 |
| 138 | http://arxiv.org/abs/2601.20230v2 | Unit-Based Agent for Semi-Cascaded Full-Duplex Dialogue Systems | 分解对话为最小单元，独立处理与预测转换 | 全双语音交互缺乏自然的多轮对话能力 | 人机语音对话系统 |
| 139 | http://arxiv.org/abs/2601.22952v1 | Sifting the Noise: A Comparative Study of LLM Agents in Vulnerability False Positive Filtering | 比较三种 LLM 智能体框架在过滤静态安全测试误报上的效果。 | 解决安全测试工具误报率高导致人工分类负担重的问题。 | 软件安全与漏洞检测 |
| 140 | http://arxiv.org/abs/2601.23009v1 | SolAgent: A Specialized Multi-Agent Framework for Solidity Code Generation | 集成双循环优化机制，内环保功能正确，外环除安全漏洞。 | 解决大模型生成智能合约代码存在漏洞及功能错误的问题。 | 区块链智能合约开发 |
| 141 | http://arxiv.org/abs/2602.02564v1 | Label Curation Using Agentic AI | 提出 AURA 框架，协调多智能体生成验证标签无需真实标签。 | 解决大规模多模态数据标注成本高、速度慢及标注者 variability 问题。 | 大规模数据标注与清洗 |
| 142 | http://arxiv.org/abs/2602.00299v2 | Agentic Framework for Epidemiological Modeling | 引入 EPIAGENT，将疾病进展建模为迭代程序合成问题自动构建模拟器。 | 解决传统流行病模型依赖固定类别难以适应路径株及政策演变的问题。 | 公共卫生与流行病建模 |
| 143 | http://arxiv.org/abs/2602.00307v2 | Autonomous Data Processing using Meta-Agents | 提出 ADP-MA，通过分层智能体编排动态构建执行及优化数据处理管道。 | 解决传统数据处理管道静态手工构建限制适应 evolving 需求的问题。 | 自主数据处理管道 |
| 144 | http://arxiv.org/abs/2602.15039v1 | GRACE: an Agentic AI for Particle Physics Experiment Design and Simulation | 提出 GRACE，基于自然语言提示自动提取实验结构并探索设计修改。 | 解决高能物理实验设计依赖人工及难以提出非显而易见修改的问题。 | 粒子物理实验设计与仿真 |
| 145 | http://arxiv.org/abs/2602.00663v2 | SEISMO: Increasing Sample Efficiency in Molecular Optimization with a Trajectory-Aware LLM Agent | 引入 SEISMO，基于完整优化轨迹条件进行在线分子结构优化。 | 解决分子属性评估依赖昂贵 oracle 导致优化样本效率低的问题。 | 药物发现与分子优化 |
| 146 | http://arxiv.org/abs/2602.00751v1 | Engineering AI Agents for Clinical Workflows: A Case Study in Architecture,MLOps, and Governance | 提出“Maria”平台，整合清洁架构与事件驱动架构实现可信临床 AI。 | 解决临床 AI 集成中架构脆弱及缺乏系统监督导致责任真空的问题。 | 医疗健康临床工作流 |
| 147 | http://arxiv.org/abs/2602.02585v1 | Agentic Observability: Automated Alert Triage for Adobe E-Commerce | 部署智能体可观测性框架，自主执行告警分类减少平均恢复时间。 | 解决企业系统复杂依赖导致手动告警分类瓶颈及 MTTR 高的问题。 | 企业运维与电子商务 |
| 148 | http://arxiv.org/abs/2602.00164v1 | Why Are AI Agent Involved Pull Requests (Fix-Related) Remain Unmerged? An Empirical Study | 实证研究 AI 代理参与的修复相关 PR，分析集成结果、延迟及阻碍因素。 | 解决 AI 编码代理在现实设置中实际有效性依赖 maintainer 接受度的问题。 | 软件维护与 AI 协作 |
| 149 | http://arxiv.org/abs/2601.22382v1 | Purely Agentic Black-Box Optimization for Biological Design | 引入 PABLO，分层代理系统使用科学 LLM 生成并迭代 refine 生物候选者。 | 解决现有方法依赖原始结构数据难以利用丰富科学文献的问题。 | 生物设计优化 |
| 150 | http://arxiv.org/abs/2601.22386v1 | Specialists or Generalists? Multi-Agent and Single-Agent LLMs for Essay Grading | 评估单代理与多代理 LLM 架构用于作文评分，多代理分解为内容、结构、语言专家。 | 解决架构选择如何影响不同作文质量水平性能了解不足的问题。 | 自动作文评分 |
| 151 | http://arxiv.org/abs/2602.00169v2 | Towards Agentic Intelligence for Materials Science | 提出以 pipeline 为中心的视图， spanning 从语料库 curation 到 goal-conditioned 代理 interfacing 实验平台。 | 解决需要超越任务隔离模型 toward 规划、行动和学习的代理系统问题。 | 材料科学发现 |
| 152 | http://arxiv.org/abs/2601.22638v1 | ScholarPeer: A Context-Aware Multi-Agent Framework for Automated Peer Review | 引入 ScholarPeer，search-enabled 多代理框架， emulate 高级研究者认知过程。 | 解决当前系统 struggle with 表面批评且缺乏外部 context 评估新颖性问题。 | 自动同行评审 |

[返回目录](#目录)

<a id="cat-12"></a>

## Agent仿真与社会模拟

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2601.00994v1 | ElecTwit: A Framework for Studying Persuasion in Multi-Agent Social Systems | ElecTwit仿真框架模拟社交媒体政治选举互动 | 基于游戏的仿真限制真实社会情境 | 多Agent社会系统说服研究 |
| 2 | http://arxiv.org/abs/2601.04245v1 | AI Agents as Policymakers in Simulated Epidemics | 生成式AI Agent嵌入SEIR环境模拟政策决策 | 探索AI Agent作为决策计算模型的潜力 | 流行病政策设计与研究 |
| 3 | http://arxiv.org/abs/2601.04716v1 | Fame Fades, Nature Remains: Disentangling the Character Identity of Role-Playing Agents | 提出角色身份二维构念：参数身份与属性身份 | 角色扮演Agent角色身份形式化不足 | LLM角色扮演Agent系统 |
| 4 | http://arxiv.org/abs/2601.05302v2 | Effects of personality steering on cooperative behavior in Large Language Model agents | 基于大五框架研究人格引导对LLM Agent协作行为影响 | 人格引导如何影响控制条件下协作尚不清楚 | 战略与社会交互中的LLM Agent |
| 5 | http://arxiv.org/abs/2601.05606v1 | Conformity Dynamics in LLM Multi-Agent Systems: The Roles of Topology and Self-Social Weighting | 系统研究网络拓扑如何塑造LLM多Agent系统中的从众动力学 | 从众作为集体决策中基本但未探索的机制 | LLM多Agent系统集体决策 |
| 6 | http://arxiv.org/abs/2601.05656v2 | HAG: Hierarchical Demographic Tree-based Agent Generation for Topic-Adaptive Simulation | 层次Agent生成框架：主题自适应树+微观层面一致性保证 | 现有方法无法同时实现宏观分布对齐与微观个体理性 | 高保真Agent初始化用于Agent-Based Modeling |
| 7 | http://arxiv.org/abs/2601.05714v1 | Metastable opinion dynamics with hidden preferences: an Ising model with neutral agents | 新型Ising框架明确分离私人偏好与公开表达意见，纳入中性Agent | 经典社会物理Ising模型未捕获内部信念、社会从众与中性间张力 | 复杂交互系统集体意见转变研究 |
| 8 | http://arxiv.org/abs/2601.04554v1 | Exploring Recommender System Evaluation: A Multi-Modal User Agent Framework for A/B Testing | 多模态用户代理框架，模拟 A/B 测试。 | 在线 A/B 测试成本高且损害用户体验。 | 推荐系统评估 |
| 9 | http://arxiv.org/abs/2601.06557v1 | Modeling Descriptive Norms in Multi-Agent Systems: An Auto-Aggregation PDE Framework with Adaptive Perception Kernels | 基于 PDE 的自动聚合模型，模拟自主多 Agent 系统中描述性规范动态。 | 捕捉多 Agent 系统中规范收敛与违反的非局部感知动态。 | 社会规范动态模拟 |
| 10 | http://arxiv.org/abs/2601.06692v1 | The Axiom of Consent: Friction Dynamics in Multi-Agent Coordination | 基于同意公理的形式框架，分析多 Agent 协调中的摩擦动态。 | 解决异构偏好与不对称利益下多 Agent 协调失败与摩擦问题。 | 多 Agent 协调与治理 |
| 11 | http://arxiv.org/abs/2601.06920v1 | Calibrating Agent-Based Financial Markets Simulators with Pretrainable Automatic Posterior Transformation-Based Surrogates | 预训练神经密度估计器替代传统代理，校准基于 Agent 的金融市场模拟器。 | 解决 ABM 校准中迭代评估计算成本高与代理难以共享优化经验。 | 金融市场模拟器校准 |
| 12 | http://arxiv.org/abs/2601.08829v1 | Modeling LLM Agent Reviewer Dynamics in Elo-Ranked Review System | 探索 Elo 排名评审系统中 LLM 智能体评审员动态，模拟多轮交互。 | 解决评审系统中智能体策略适应性与决策准确性评估问题。 | 学术论文评审系统 |
| 13 | http://arxiv.org/abs/2602.00017v1 | SafeTalkCoach: Diversity-Driven Multi-Agent Simulation for Parent-Teen Health Conversations | 构建多样性驱动的多智能体对话生成框架，模拟亲子性健康对话。 | 解决真实亲子健康对话数据稀缺且难以收集的问题。 | 健康沟通实践 |
| 14 | http://arxiv.org/abs/2601.12441v1 | The Dynamic and Endogenous Behavior of Re-Offense Risk: An Agent-Based Simulation Study of Treatment Allocation in Incarceration Diversion Programs | 将再犯风险建模为人机系统交互的动态演化 | 风险评估工具视风险为静态属性，忽视社会互动影响 | 司法矫正治疗分配政策 |
| 15 | http://arxiv.org/abs/2601.12628v1 | Constructing a Dataset to Support Agent-Based Modeling of Online Interactions: Users, Topics, and Interaction Networks | 基于Reddit构建实证Agent社交模拟数据集 | ABM依赖手工规则，缺乏实证数据校准 | 在线社交互动模拟 |
| 16 | http://arxiv.org/abs/2601.10970v1 | Modeling Multi-Party Interaction in Couples Therapy: A Multi-Agent Simulation Approach | 多模态多智能体模拟系统，建模夫妻治疗互动。 | 解决传统培训无法捕捉真实夫妻动态复杂性。 | 心理咨询师培训 |
| 17 | http://arxiv.org/abs/2601.15319v1 | Large Language Models as Simulative Agents for Neurodivergent Adult Psychometric Profiles | LLM 模拟神经多样性成人心理测量反应。 | 解决标准心理测量工具区分敏感度有限问题。 | 心理测量研究模拟 |
| 18 | http://arxiv.org/abs/2601.14296v2 | From Agent Simulation to Social Simulator: A Comprehensive Review (Part 2) | 综述从 Agent 仿真到社会模拟的计算实验方法。 | 解决传统 ABM 难以深入揭示系统运行原理。 | 复杂系统社会模拟 |
| 19 | http://arxiv.org/abs/2601.14566v1 | SCSimulator: An Exploratory Visual Analytics Framework for Partner Selection in Supply Chains through LLM-driven Multi-Agent Simulation | 集成 LLM 驱动多代理模拟与人机协作进行供应链伙伴选择 | 解决传统方法无法捕捉现实复杂性及引入主观偏差 | 供应链伙伴选择 |
| 20 | http://arxiv.org/abs/2601.15114v1 | From Who They Are to How They Act: Behavioral Traits in Generative Agent-Based Models of Social Media | 引入行为特征层调节agent发帖、转发、评论等参与倾向 | 解决生成式agent行为同质化问题，实现异质参与模式 | 社交媒体信息传播模拟 |
| 21 | http://arxiv.org/abs/2601.15437v1 | Exploring Implicit Perspectives on Autism in Large Language Models Through Multi-Agent Simulations | 多agent系统模拟自闭症与非自闭症agent社交场景 | 揭示LLM对自闭症的隐性偏见和假设，提出双共情问题框架 | 自闭症相关交互场景 |
| 22 | http://arxiv.org/abs/2601.18027v1 | Sentipolis: Emotion-Aware Agents for Social Simulations | 集成连续 PAD 情感表示与双速情感动力学 | 解决 LLM 代理情感遗忘与长期连续性弱 | 社会仿真与群体动态研究 |
| 23 | http://arxiv.org/abs/2601.18275v1 | When Nobody Around Is Real: Exploring Public Opinions and User Experiences On the Multi-Agent AI Social Platform | 研究多代理社交平台用户体验与公众舆论 | AI 主导社交环境引发注意力过载与同质化 | 多代理社交 platforms |
| 24 | http://arxiv.org/abs/2601.16778v2 | GTA: Generative Traffic Agents for Simulating Realistic Mobility Behavior | 基于 LLM 和人物角色的生成式交通智能体，模拟大规模出行选择 | 传统方法依赖手工假设，难以评估新技术政策影响 | 城市规划与可持续交通模拟 |
| 25 | http://arxiv.org/abs/2601.20538v2 | Interpreting Emergent Extreme Events in Multi-Agent Systems | 提出解释多 Agent 系统 emergent 极端事件的首个框架 | 归因极端事件起源，提升系统安全性 | LLM 驱动的多 Agent 社会模拟 |
| 26 | http://arxiv.org/abs/2601.19778v1 | Reimagining Peer Review Process Through Multi-Agent Mechanism Design | 建模研究社区为随机多智能体系统，设计激励协议 | 同行评审在投稿增长下失效的机制设计问题 | 学术研究评审系统 |
| 27 | http://arxiv.org/abs/2602.02534v1 | DualMind: Towards Understanding Cognitive-Affective Cascades in Public Opinion Dissemination via Multi-Agent Simulation | LLM 驱动多智能体平台，模拟认知 - 情感级联 | 现有框架忽略情感响应与认知信念的交互 | 公共舆论传播仿真 |
| 28 | http://arxiv.org/abs/2602.00685v1 | HumanStudy-Bench: Towards AI Agent Design for Participant Simulation | 提出 HUMANSTUDY-BENCH，编排智能体重建 Published 人类受试者实验。 | 解决现有评估混淆基础模型能力与实验实例化导致行为不稳定问题。 | 社会科学与参与者模拟 |
| 29 | http://arxiv.org/abs/2601.21936v1 | AgenticSimLaw: A Juvenile Courtroom Multi-Agent Debate Simulation for Explainable High-Stakes Tabular Decision Making | 引入角色结构化的多Agent 辩论框架，定义代理角色和交互协议，提供透明决策过程。 | 解决高风险表格决策任务中的黑盒问题，提供可审计的决策过程。 | 少年法庭决策模拟 |
| 30 | http://arxiv.org/abs/2601.21977v1 | From Particles to Agents: Hallucination as a Metric for Cognitive Friction in Spatial Simulation | 提出代理环境模拟，将 AI 幻觉作为诊断工具，揭示建筑空间中的语义模糊。 | bridging 传统物理模拟与认知代理，挑战当前 HCI 范式。 | 空间模拟与建筑设计 |
| 31 | http://arxiv.org/abs/2601.22288v1 | PersonaCite: VoC-Grounded Interviewable Agentic Synthetic AI Personas for Verifiable User and Design Research | 提出 PersonaCite，通过检索增强交互将 AI 角色重构为证据边界研究仪器。 | 解决基于提示的角色产生不可验证响应且掩盖证据基础的问题。 | 用户与设计研究 |
| 32 | http://arxiv.org/abs/2601.22547v1 | PersonaAct: Simulating Short-Video Users with Personalized Agents for Counterfactual Filter Bubble Auditing | 提出 PersonaAct，模拟 persona-conditioned 多模态代理用于审计 filter bubbles。 | 解决真实用户研究成本高及现有模拟器无法 reproduce 真实行为问题。 | 短视频推荐审计 |

[返回目录](#目录)

<a id="cat-13"></a>

## Agent规划与推理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2601.02196v2 | ACDZero: MCTS Agent for Mastering Automated Cyber Defense | MCTS规划+图神经网络嵌入的网络观察 | 复杂网络中深度强化学习探索效率低 | 自动化网络防御 |
| 2 | http://arxiv.org/abs/2601.02714v1 | Time-Scaling Is What Agents Need Now | 时间扩展架构设计优化推理 unfold 能力 | 搜索完整性与效率限制 | 深度推理与问题解决Agent |
| 3 | http://arxiv.org/abs/2601.03164v2 | WebAnchor: Anchoring Agent Planning to Stabilize Long-Horizon Web Reasoning | 两阶段RL框架解耦规划与执行 | 长程Web推理中规划仍是瓶颈 | 长程Web信息搜索Agent |
| 4 | http://arxiv.org/abs/2601.04853v1 | RAAR: Retrieval Augmented Agentic Reasoning for Cross-Domain Misinformation Detection | 检索增强+多Agent协作构建可验证多步推理路径 | 跨领域虚假信息检测泛化能力不足 | 跨领域虚假信息检测 |
| 5 | http://arxiv.org/abs/2601.04878v1 | Higher-Order Knowledge Representations for Agentic Scientific Reasoning | 超图知识表示编码多实体关系，Agent超图遍历工具 | 传统知识图谱无法捕获高阶交互关系 | 科学发现与假设生成 |
| 6 | http://arxiv.org/abs/2601.03905v2 | Current Agents Fail to Leverage World Model as Tool for Foresight | 实证评估代理利用世界模型进行预测的能力。 | 代理难以决定何时模拟及整合预测结果。 | 代理认知与世界模型 |
| 7 | http://arxiv.org/abs/2601.04035v1 | MobileDreamer: Generative Sketch World Model for GUI Agent | 文本草图世界模型，支持 GUI 代理前瞻。 | 解决 GUI 代理缺乏长程任务预测能力。 | 移动 GUI 自动化代理 |
| 8 | http://arxiv.org/abs/2601.07577v1 | Beyond Entangled Planning: Task-Decoupled Planning for Long-Horizon Agents | 任务解耦规划，有向无环图子目标分解，范围限定上下文 | 长程Agent规划中纠缠上下文导致错误传播 | 长程Agent任务/TravelPlanner等 |
| 9 | http://arxiv.org/abs/2601.05930v1 | Can We Predict Before Executing Machine Learning Agents? | 内部化执行先验，用预测推理替代昂贵的物理执行检查。 | bypass 机器学习 Agent 中的执行瓶颈加速假设评估。 | 自主机器学习 Agent |
| 10 | http://arxiv.org/abs/2601.06502v2 | DRAGON: LLM-Driven Decomposition and Reconstruction Agents for Large-Scale Combinatorial Optimization | LLM 驱动分解与重构 Agent，将大规模组合优化分解为子问题。 | 解决 LLM 求解组合优化问题时可扩展性与泛化性受限问题。 | 大规模组合优化问题 |
| 11 | http://arxiv.org/abs/2601.08282v1 | D$^2$Plan: Dual-Agent Dynamic Global Planning for Complex Retrieval-Augmented Reasoning | 提出双智能体动态全局规划范式，Reasoner 与 Purifier 协作构建显式计划。 | 解决检索增强推理中搜索链无效及推理被干扰问题。 | 复杂多跳推理任务 |
| 12 | http://arxiv.org/abs/2601.08621v1 | GraphSearch: Agentic Search-Augmented Reasoning for Zero-Shot Graph Learning | 扩展搜索增强推理至图学习，结合图感知查询规划器与检索器。 | 解决利用图结构信号进行零样本图学习的检索与推理问题。 | 图结构化数据学习 |
| 13 | http://arxiv.org/abs/2601.08742v1 | Inferring Latent Intentions: Attributional Natural Language Inference in LLM Agents | 扩展 NLI 为归因 NLI，评估智能体 abduction 意图推断与 deduction 验证能力。 | 解决传统 NLI 无法捕捉多智能体环境中意图驱动推理问题。 | 多智能体交互环境 |
| 14 | http://arxiv.org/abs/2601.08747v2 | To Retrieve or To Think? An Agentic Approach for Context Evolution | 提出代理上下文进化框架，动态决定寻求新证据或利用现有知识推理。 | 解决 indiscriminate 检索导致计算成本增加与上下文噪声问题。 | 知识密集型推理任务 |
| 15 | http://arxiv.org/abs/2601.09382v1 | Long-term Task-oriented Agent: Proactive Long-term Intent Maintenance in Dynamic Environments | 形式化主动性为意图条件监控与事件触发跟进，桥接静态需求与动态环境。 | 解决当前智能体仅响应即时查询无法维护长期意图问题。 | 动态环境任务交互 |
| 16 | http://arxiv.org/abs/2601.12538v1 | Agentic Reasoning for Large Language Models | 三层框架：基础/自进化/集体多Agent推理 | LLM在开放动态环境中推理能力不足 | 通用LLM Agent推理系统 |
| 17 | http://arxiv.org/abs/2602.11170v1 | PRIME: Policy-Reinforced Iterative Multi-agent Execution for Algorithmic Reasoning in Large Language Models | 执行者/验证者/协调者三Agent迭代验证 | LLM算法推理能力有限，错误传播导致失败 | 算法推理与符号任务 |
| 18 | http://arxiv.org/abs/2601.13115v1 | Agentic Conversational Search with Contextualized Reasoning via Reinforcement Learning | RL训练交错搜索与推理，适应多轮对话意图演化 | 现有方法静态流水线，无法联合优化多轮交互 | 对话式搜索Agent |
| 19 | http://arxiv.org/abs/2601.10029v2 | PaperScout: An Autonomous Agent for Academic Paper Search with Process-Aware Sequence-Level Policy Optimization | 将论文搜索重构为序列决策，引入过程感知序列级策略优化方法。 | 解决静态工作流难处理复杂条件查询及 RL 粒度不匹配导致训练不稳定。 | 学术论文搜索代理 |
| 20 | http://arxiv.org/abs/2601.10137v1 | Step-by-Step Causality: Transparent Causal Discovery with Multi-Agent Tree-Query and Adversarial Confidence Estimation | 树结构多专家 LLM 框架，将因果发现简化为关于后门路径等的短查询序列。 | 解决经典约束基方法误差传播及 LLM 因果 oracle 行为不透明无置信度问题。 | 无数据因果发现任务 |
| 21 | http://arxiv.org/abs/2601.11037v1 | BAPO: Boundary-Aware Policy Optimization for Reliable Agentic Search | 边界感知策略优化，培养 Agent 承认不知道的能力。 | 解决 Agent 推理越界导致不可靠回答的风险。 | 基于搜索的 Agent 推理 |
| 22 | http://arxiv.org/abs/2601.14027v1 | Numina-Lean-Agent: An Open and General Agentic Reasoning System for Formal Mathematics | 直接使用通用编码代理作为形式数学推理器 | 解决现有方法依赖特定管道及训练形式证明器的限制 | 形式数学定理证明 |
| 23 | http://arxiv.org/abs/2601.14224v1 | Rerank Before You Reason: Analyzing Reranking Tradeoffs through Effective Token Cost in Deep Search Agents | 研究如何在深度搜索管道中分配推理预算，聚焦列表重排序 | 解决扩展测试时计算引发的显著效率担忧 | 深度搜索代理 |
| 24 | http://arxiv.org/abs/2601.16400v1 | Clarify or Answer: Reinforcement Learning for Agentic VQA with Context Under-specification | CoA agent分别建模询问或回答决策，GRPO-CR优化澄清问题生成 | 解决现实VQA上下文依赖导致直接回答产生自信但错误预测 | 视觉问答系统 |
| 25 | http://arxiv.org/abs/2601.16478v1 | DeepEra: A Deep Evidence Reranking Agent for Scientific Retrieval-Augmented Generated Question Answering | 集成逐步推理，实现超越表面语义的候选段落更精确评估 | 解决现有检索rerank方法易受语义相似但逻辑无关段落影响 | 科学问答RAG系统 |
| 26 | http://arxiv.org/abs/2601.16486v1 | Timely Machine: Awareness of Time Makes Test-Time Scaling Agentic | 重新定义测试时间为挂钟时间，模型根据时间预算动态调整策略 | 解决agent场景中工具延迟使传统生成长度定义失效问题 | 时间约束推理任务 |
| 27 | http://arxiv.org/abs/2601.16649v1 | LUMINA: Long-horizon Understanding for Multi-turn Interactive Agents | 预言反事实框架测量特定技能对agent性能的关键性 | 理解推进底层能力对多轮长程agent问题成功相对重要性 | 多轮交互agent长程理解 |
| 28 | http://arxiv.org/abs/2601.18296v1 | Temp-R1: A Unified Autonomous Agent for Complex Temporal KGQA via Reverse Curriculum Reinforcement Learning | 反向课程 RL 训练自主代理处理时序知识图谱 | 时序约束与多跳依赖导致推理认知过载 | 时序知识图谱问答 |
| 29 | http://arxiv.org/abs/2601.16965v1 | Spatial-Agent: Agentic Geo-spatial Reasoning with Scientific Core Concepts | 基于空间信息理论，将问题解析为可执行 GeoFlow 图工作流 | 现有智能体依赖搜索匹配，幻觉空间关系 | 地理空间分析与城市规划 |
| 30 | http://arxiv.org/abs/2601.20676v1 | Efficient Multimodal Planning Agent for Visual Question-Answering | 训练多模态规划 Agent，动态分解 mRAG  pipeline | 平衡 VQA 任务中效率与效果，减少冗余计算 | 视觉问答与多模态检索 |
| 31 | http://arxiv.org/abs/2601.21162v1 | A2RAG: Adaptive Agentic Graph Retrieval for Cost-Aware and Reliable Reasoning | 提出 A2RAG，自适应控制器验证证据充分性并触发细化 | 解决 Graph-RAG 中混合难度工作流与提取丢失问题 | 多跳问答与知识图谱检索 |
| 32 | http://arxiv.org/abs/2601.21352v1 | BEAP-Agent: Backtrackable Execution and Adaptive Planning for GUI Agents | 提出 BEAP-Agent，支持长范围多级状态回溯的 DFS 框架 | 解决 GUI Agent 错误探索路径后无法恢复导致失败问题 | 长周期 GUI 任务探索 |
| 33 | http://arxiv.org/abs/2601.21699v1 | Can David Beat Goliath? On Multi-Hop Reasoning with Resource-Constrained Agents | 提出 DAVID-GRPO，预算高效 RL 框架稳定小模型学习 | 解决资源受限下小模型多跳推理低成本低精度问题 | 资源受限的多跳推理 Agent |
| 34 | http://arxiv.org/abs/2601.23273v1 | UPA: Unsupervised Prompt Agent via Tree-Based Search and Selection | 提出无监督提示智能体，基于树搜索与 BTL 模型进行提示优化。 | 解决提示优化依赖监督奖励信号在实际场景中不可用的问题。 | 自动化提示工程优化 |
| 35 | http://arxiv.org/abs/2602.00528v1 | How Far Are LLMs from Professional Poker Players? Revisiting Game-Theoretic Reasoning with Agentic Tool Use | 提出 ToolPoker，结合外部求解器实现 GTO 一致动作及专业解释。 | 解决 LLM 在扑克任务中依赖启发式及知行差距导致策略失败的问题。 | 博弈论推理与决策 |
| 36 | http://arxiv.org/abs/2602.00845v2 | Optimizing Agentic Reasoning with Retrieval via Synthetic Semantic Information Gain Reward | 引入 InfoReasoner，通过合成语义信息增益奖励激励有效信息寻求。 | 解决优化检索过程缺乏密集原则性奖励信号导致效率低的问题。 | 检索增强推理智能体 |
| 37 | http://arxiv.org/abs/2602.00929v1 | Learning Abstractions for Hierarchical Planning in Program-Synthesis Agents | 引入 TheoryCoder-2，利用 LLM 上下文学习主动学习可复用抽象。 | 解决现有系统依赖人工提供抽象导致泛化能力及样本效率低的问题。 | 程序合成与分层规划 |
| 38 | http://arxiv.org/abs/2601.22311v1 | Why Reasoning Fails to Plan: A Planning-Centric Analysis of Long-Horizon Decision Making in LLM Agents | 引入 FLARE，强制显式 lookahead、价值传播和有限承诺，使下游结果影响早期决策。 | 解决逐步推理导致短视承诺在长 horizon 规划中失败的问题。 | 长 horizon 决策 |
| 39 | http://arxiv.org/abs/2601.22701v1 | Best-of-Q: Improving VLM agents with Q-function Action Ranking at Inference | 引入新 paradigm， decouple VLM 作为 action proposer 与最终 action selection，用 Q-function 重排序。 | 解决 VLM 难以 adapt 快速变化环境且 fine-tuning 需要 expansive 训练问题。 | VLM 智能体 |

[返回目录](#目录)

<a id="cat-14"></a>

## Agent可解释性与透明度

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2601.02314v1 | Project Ariadne: A Structural Causal Framework for Auditing Faithfulness in LLM Agents | 结构因果模型+反事实逻辑审计推理因果完整性 | 推理链是真实驱动还是事后合理化 | 高风险自主决策Agent |
| 2 | http://arxiv.org/abs/2601.03671v1 | NeuronScope: A Multi-Agent Framework for Explaining Polysemantic Neurons in Language Models | 多代理迭代激活引导，分解多义神经元语义。 | 单 pass 方法难以捕捉神经元多义性行为。 | 语言模型神经元解释 |
| 3 | http://arxiv.org/abs/2601.12618v1 | Disagreement as Data: Reasoning Trace Analytics in Multi-Agent Systems | 用余弦相似度量化Agent推理痕迹分歧 | 缺乏方法分析LLM多Agent协作中的解释性数据 | 教育研究与定性编码 |
| 4 | http://arxiv.org/abs/2601.15075v2 | The Why Behind the Action: Unveiling Internal Drivers via Agentic Attribution | 提出通用代理归因框架识别驱动代理行为的内部因素 | 解决现有研究聚焦失败归因不足以解释行为原因 | 代理行为归因 |
| 5 | http://arxiv.org/abs/2601.17168v1 | Interpreting Agentic Systems: Beyond Model Explanations to System-Level Accountability | 评估现有解释技术在智能体系统的适用性，提出系统级问责方向 | 静态模型解释技术不适用于动态智能体系统 | 智能体系统安全与问责 |

[返回目录](#目录)

<a id="cat-15"></a>

## 低代码/无代码Agent平台

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2601.07504v1 | FROAV: A Framework for RAG Observation and Agent Verification -- Lowering the Barrier to LLM Agent Research | 可视化工作流编排和综合评估框架的即插即用架构 | LLM Agent工作流开发评估迭代门槛高 | LLM Agent研究/FROAV平台 |

[返回目录](#目录)
