# AI agents 2025年12月学术分类汇总

共收录 608 篇论文，按研究方向分类整理如下。

## 目录

- [基于Agent的应用系统（115篇）](#cat-01)
- [Agent评测与基准（55篇）](#cat-02)
- [Agent安全与对齐（81篇）](#cat-03)
- [Agent学习与自进化（50篇）](#cat-04)
- [多Agent强化学习（41篇）](#cat-05)
- [Agent工具使用与环境交互（26篇）](#cat-06)
- [Agent架构与框架设计（66篇）](#cat-07)
- [Agent仿真与社会模拟（26篇）](#cat-08)
- [多Agent协作与通信（61篇）](#cat-09)
- [人机协作Agent（20篇）](#cat-10)
- [Agent可解释性与透明度（6篇）](#cat-11)
- [Agent规划与推理（18篇）](#cat-12)
- [Agent记忆与知识管理（23篇）](#cat-13)
- [具身智能Agent（18篇）](#cat-14)
- [低代码/无代码Agent平台（1篇）](#cat-15)
- [其他-Agent综述与研究进展（1篇）](#cat-16)

<a id="cat-01"></a>

## 基于Agent的应用系统

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2512.01234v2 | Proactive Agentic Whiteboards: Enhancing Diagrammatic Learning | DrawDash通过TAB补全模式，语音驱动实时完善教学图表 | 教师实时绘图认知负荷高，图表不完整影响学生理解 | 教育场景/教师授课 |
| 2 | http://arxiv.org/abs/2512.01270v1 | Egent: An Autonomous Agent for Equivalent Width Measurement | 结合经典Voigt拟合与LLM视觉检查的自主测量Agent | 光谱等效宽度测量需专家数月工作，效率低下 | 天文学/光谱分析 |
| 3 | http://arxiv.org/abs/2512.01453v1 | Reinventing Clinical Dialogue: Agentic Paradigms for LLM Enabled Healthcare Communication | 提出临床Agent认知架构分类：潜在空间/涌现规划/落地合成/可验证工作流 | 医疗对话需共情与精确平衡，反应式LLM缺乏事实准确性 | 医疗健康沟通 |
| 4 | http://arxiv.org/abs/2512.01693v1 | LLM-Driven Multi-Agent Curation and Expansion of Metal-Organic Frameworks Database | LitMOF多Agent框架从文献验证并修复晶体结构错误 | MOF数据库近半条目有结构错误，影响数据驱动发现 | 材料科学/MOF数据库 |
| 5 | http://arxiv.org/abs/2602.17017v1 | Sales Research Agent and Sales Research Bench | 销售研究Agent连接实时CRM数据，Sales Research Bench八维度评分 | 企业需AI回答销售问题，现有模型缺乏透明可重复质量证据 | 企业销售/CRM系统 |
| 6 | http://arxiv.org/abs/2512.02436v1 | Semantic Trading: Agentic AI for Clustering and Relationship Discovery in Prediction Markets | Agent自主聚类市场并发现相关性，交易策略周收益约20% | 预测市场因重叠问题、隐式等价导致碎片化 | 预测市场/Polymarket |
| 7 | http://arxiv.org/abs/2512.02608v1 | Investigating the Integrated Digital Interventions Delivered by a Therapeutic Companion Agent for Young Adults with Symptoms of Depression: A Proof-of-Concept Study | 治疗伴侣Agent整合EMA/EMI/行为激活/游戏化 | 数字干预低参与度和依从性挑战 | 抑郁症青年患者 |
| 8 | http://arxiv.org/abs/2512.02654v1 | Cybersecurity AI: The World's Top AI Agent for Security Capture-the-Flag (CTF) | alias1模型架构实现企业级安全操作成本效率 | CTF竞赛AI主导，传统竞赛形式过时 | 网络安全CTF竞赛 |
| 9 | http://arxiv.org/abs/2512.02814v2 | Radiologist Copilot: An Agentic Framework Orchestrating Specialized Tools for Reliable Radiology Reporting | 编排专用工具完成放射学报告全流程 | 放射学报告多阶段规划密集型工作流 | 临床放射学报告 |
| 10 | http://arxiv.org/abs/2512.06006v1 | Simple Agents Outperform Experts in Biomedical Imaging Workflow Optimization | 简单Agent框架自动生成适配代码超越人类专家 | 生物医学成像工具适配最后一步瓶颈 | 生物医学成像管道 |
| 11 | http://arxiv.org/abs/2512.03278v2 | Thucy: An LLM-based Multi-Agent System for Claim Verification across Relational Databases | 跨数据库跨表多Agent声明验证，提供SQL证据 | 现有验证系统仅操作小单表数据库 | 事实核查/声明验证 |
| 12 | http://arxiv.org/abs/2512.03476v1 | ATHENA: Agentic Team for Hierarchical Evolutionary Numerical Algorithms | HENA循环知识驱动诊断，自主识别数学对称性 | 科学计算理论与实现差距 | 科学计算/科学机器学习 |
| 13 | http://arxiv.org/abs/2512.04207v2 | Orchestrator Multi-Agent Clinical Decision Support System for Secondary Headache Diagnosis in Primary Care | 编排器-专家架构，七领域专用Agent结构化证据推理 | 初级保健中继发性头痛识别困难 | 临床头痛诊断 |
| 14 | http://arxiv.org/abs/2512.08659v1 | An Agentic AI System for Multi-Framework Communication Coding | MOSAIC系统编排4个核心Agent，代码本引导RAG与动态few-shot提示 | 临床沟通标注劳动密集、不一致、难以跨框架和领域扩展 | 医疗健康领域的临床沟通分析 |
| 15 | http://arxiv.org/abs/2512.08674v2 | Multi-Agent Intelligence for Multidisciplinary Decision-Making in Gastrointestinal Oncology | 分层多Agent框架模拟人类多学科团队协作，整合内窥镜影像和放射数据 | 多模态临床推理面临上下文稀释和幻觉，复杂病史处理困难 | 胃肠道肿瘤多学科临床决策支持 |
| 16 | http://arxiv.org/abs/2512.09964v1 | Development of an Agentic AI Model for NGS Downstream Analysis Targeting Researchers with Limited Biological Background | 基于Llama 3 70B和RAG的Agent，自动化NGS下游分析并提供文献支持解释 | 缺乏计算和生物学专家背景的研究者难以进行NGS下游分析 | 生物信息学与基因组研究 |
| 17 | http://arxiv.org/abs/2512.09440v1 | Knowledge-Augmented Large Language Model Agents for Explainable Financial Decision-Making | 知识增强LLM Agent结合外部知识检索和多头注意力构建逻辑链 | 传统金融决策方法依赖参数化知识，缺乏事实一致性和推理链 | 金融文本处理与可解释决策 |
| 18 | http://arxiv.org/abs/2512.09882v2 | Comparing AI Agents to Cybersecurity Professionals in Real-World Penetration Testing | ARTEMIS多Agent框架在真实企业网络渗透测试中超越9/10人类参与者 | 缺乏AI Agent与人类网络安全专业人员在真实环境中的综合评估 | 企业网络安全与渗透测试 |
| 19 | http://arxiv.org/abs/2512.10034v1 | DynaMate: An Autonomous Agent for Protein-Ligand Molecular Dynamics Simulations | 模块化多Agent框架自主设计和执行蛋白质-配体MD工作流，支持自由能计算 | MD设置技术复杂包括参数化和软件配置，阻碍广泛高效使用 | 药物发现与蛋白质工程分子建模 |
| 20 | http://arxiv.org/abs/2512.04529v2 | SlideGen: Collaborative Multimodal Agents for Scientific Slide Generation | 多模态 Agent 协作框架，生成可编辑 PPT | 现有方法忽略幻灯片视觉设计与逻辑流 | 学术幻灯片生成 |
| 21 | http://arxiv.org/abs/2512.05073v1 | David vs. Goliath: Can Small Models Win Big with Agentic AI in Hardware Design? | 小模型结合 Agent 框架在硬件设计上媲美大模型 | 大模型推理计算与能源成本高 | 硬件设计 |
| 22 | http://arxiv.org/abs/2512.05502v1 | GRASP: Graph Reasoning Agents for Systems Pharmacology with Human-in-the-Loop | 多 Agent 图推理框架，编码 QSP 模型为知识图谱 | 定量系统药理学建模耗时且依赖专家 | 药物开发建模 |
| 23 | http://arxiv.org/abs/2512.06046v1 | Beyond Prototyping: Autonomous, Enterprise-Grade Frontend Development from Pixel to Production via a Specialized Multi-Agent Framework | 自主前端开发 Agent 框架，从像素到生产 | 通用代码助手无法满足企业级交付要求 | 企业前端开发 |
| 24 | http://arxiv.org/abs/2512.05824v1 | Multimodal Oncology Agent for IDH1 Mutation Prediction in Low-Grade Glioma | 多模态肿瘤 Agent，整合组织学工具与临床推理 | 低级别胶质瘤 IDH1 突变预测需多源信息 | 医疗诊断 |
| 25 | http://arxiv.org/abs/2512.06247v2 | DUET: Agentic Design Understanding via Experimentation and Testing | 模仿专家通过迭代实验和工具测试理解硬件设计，而非仅读取代码。 | LLM 难以从 RTL 语法推断复杂动态行为，限制下游任务完成。 | 硬件设计/RTL 代码理解 |
| 26 | http://arxiv.org/abs/2512.15736v1 | Anubuddhi: A Multi-Agent AI System for Designing and Simulating Quantum Optics Experiments | 多智能体系统通过语义检索组合光学布局，经物理仿真验证设计。 | 量子光学实验设计需专业知识，缺乏无需编程的自然语言设计工具。 | 量子光学实验设计 |
| 27 | http://arxiv.org/abs/2512.06396v1 | AgenticCyber: A GenAI-Powered Multi-Agent System for Multimodal Threat Detection and Adaptive Response in Cybersecurity | 编排专用智能体并发监控云日志、视频和音频，实现自适应响应。 | 分布式环境中多模数据流的实时威胁检测与响应延迟问题。 | 企业网络与 IoT 安全 |
| 28 | http://arxiv.org/abs/2512.06590v1 | Towards Efficient Hypergraph and Multi-LLM Agent Recommender Systems | 引入超图编码器捕捉复杂多行为关系，仅检索相关 token 降低开销。 | 生成式推荐系统存在的幻觉问题及实际场景中高计算成本问题。 | 电商与社交媒体推荐 |
| 29 | http://arxiv.org/abs/2512.09944v3 | Echo-CoPilot: A Multiple-Perspective Agentic Framework for Reliable Echocardiography Interpretation | 多视角工作流结合知识图谱引导测量选择，自对比模型解决冲突。 | 超声心动图解释需整合多视图证据，现有模型在工具噪声下失效。 | 医疗/超声心动图解释 |
| 30 | http://arxiv.org/abs/2512.06902v1 | BabelCoder: Agentic Code Translation with Specification Alignment | 分解任务为翻译、测试和 refinement 专用智能体，协作提升质量。 | 自动代码翻译准确性有限，未能有效利用代码上下文与结构线索。 | 软件迁移/代码翻译 |
| 31 | http://arxiv.org/abs/2512.07022v1 | "Reformulate, Retrieve, Localize: Agents for Repository-Level Bug Localization" | 利用 LLM 提取关键信息 reformulate 查询，编排 BM25 检索自动化定位。 | 传统 bug 定位依赖未变描述含噪声，LLM 改革查询效果未探索。 | 软件工程/Bug 定位 |
| 32 | http://arxiv.org/abs/2512.07081v2 | ClinNoteAgents: An LLM Multi-Agent System for Predicting and Interpreting Heart Failure 30-Day Readmission from Clinical Notes | 多智能体框架将自由文本笔记转化为结构化风险因素及临床抽象。 | 临床笔记含丰富信息但利用不足，传统模型依赖专家规则。 | 医疗/心衰再入院预测 |
| 33 | http://arxiv.org/abs/2512.07909v1 | Agentic Artificial Intelligence for Ethical Cybersecurity in Uganda: A Reinforcement Learning Framework for Threat Detection in Resource-Constrained Environments | 集成 RL、显式伦理治理层及人工监督，交付自适应可信网络安全。 | 资源受限环境规则基 IDS 缺乏适应性及伦理保障，导致漏报误报。 | 网络安全/资源受限环境 |
| 34 | http://arxiv.org/abs/2512.07351v1 | DeepAgent: A Dual Stream Multi Agent Fusion for Robust Multimodal Deepfake Detection | 双智能体分别检查视频符号及音视频不一致，随机森林融合决策。 | 合成媒体检测单模型易受模态不匹配、噪声及操纵影响。 | 数字内容验证/深伪检测 |
| 35 | http://arxiv.org/abs/2512.07533v1 | VulnLLM-R: Specialized Reasoning LLM with Agent Scaffold for Vulnerability Detection | 训练 7B 推理模型，构建代理 scaffold，超越静态分析工具及大模型。 | 现有推理模型在漏洞检测性能有限，缺乏项目级检测能力。 | 软件安全/漏洞检测 |
| 36 | http://arxiv.org/abs/2512.07921v1 | DeepCode: Open Agentic Coding | 通过原则性信息流管理，编排四种信息操作最大化任务相关信号。 | 文档到代码库合成面临信息过载与 LLM 上下文瓶颈的根本冲突。 | 科学复现/代码生成 |
| 37 | http://arxiv.org/abs/2512.07785v1 | Automating High Energy Physics Data Analysis with LLM-Powered Agents | 混合系统结合 LLM 监督编码代理与 Snakemake 工作流管理器自动化分析。 | 高能物理数据分析需专家知识，缺乏系统化基准测试模型能力。 | 高能物理/数据分析 |
| 38 | http://arxiv.org/abs/2512.10313v2 | EpiPlanAgent: Agentic Automated Epidemic Response Planning | 多智能体框架自动化生成并验证数字应急响应计划 | 传统疫情响应规划依赖人工，耗时且完整性不足 | 公共卫生疫情应急响应规划 |
| 39 | http://arxiv.org/abs/2512.14735v1 | PyFi: Toward Pyramid-like Financial Image Understanding for VLMs via Adversarial Agents | 提出金字塔式金融图像理解框架，利用对抗智能体合成数据 | 视觉语言模型缺乏复杂金融视觉推理能力及标注数据 | 金融领域视觉问答与推理任务 |
| 40 | http://arxiv.org/abs/2512.10441v1 | Decoding Student Minds: Leveraging Conversational Agents for Psychological and Learning Analysis | 结合多模态数据实时分类学生认知与情感状态 | 现有聊天机器人仅限辅导或情感支持，缺乏综合状态推断 | 教育场景学生学习与心理状态分析 |
| 41 | http://arxiv.org/abs/2512.11143v1 | Automated Penetration Testing with LLM Agents and Classical Planning | 整合经典规划与 LLM 智能体，提供外部结构化“大脑” | LLM 智能体难以维持长程计划与复杂推理，效率低 | 网络安全自动化渗透测试 |
| 42 | http://arxiv.org/abs/2512.11271v1 | TriFlow: A Progressive Multi-Agent Framework for Intelligent Trip Planning | 三阶段流水线统一结构化推理与语言灵活性，渐进缩小搜索空间 | 现有代理难以满足约束、协调工具，计划不可行或成本高 | 现实世界旅行行程规划 |
| 43 | http://arxiv.org/abs/2512.11935v1 | AGAPI-Agents: An Open-Access Agentic AI Platform for Accelerated Materials Design on AtomGPT.org | 集成开源 LLM 与材料科学 API，自主构建执行多步工作流 | 材料研究受限于碎片化生态、复现性差及商业模型依赖 | 加速材料设计与科学发现 |
| 44 | http://arxiv.org/abs/2512.11398v1 | AutoFSM: A Multi-agent Framework for FSM Code Generation with IR and SystemC-Based Testing | 引入中间表示减少语法错误，集成 SystemC 建模与自动测试 | LLM 生成 Verilog 代码语法错误多，调试效率低，依赖基准 | 硬件设计有限状态机代码生成 |
| 45 | http://arxiv.org/abs/2512.11611v1 | Using GUI Agent for Electronic Design Automation | 首个系统研究部署 GUI 智能体于 EDA 工作流，提出 EDAgent 指标 | 专业 CAD 套件是现有智能体最弱领域，远未替代专家 | 电子设计自动化（EDA）工作流程 |
| 46 | http://arxiv.org/abs/2512.11682v1 | MedAI: Evaluating TxAgent's Therapeutic Agentic Reasoning in the NeurIPS CURE-Bench Competition | 评估治疗推理系统，分析检索质量对工具调用与性能影响 | 医疗应用安全约束严格，推理迹线与工具序列准确性关键 | 临床治疗决策与药物推荐系统 |
| 47 | http://arxiv.org/abs/2512.14744v1 | VERAFI: Verified Agentic Financial Intelligence through Neurosymbolic Policy Generation | 神经符号策略生成框架，结合检索与自动推理策略验证 | 金融 AI 存在计算错误与违规，即使检索完美仍生成错误 | 金融合规、投资决策与风险管理 |
| 48 | http://arxiv.org/abs/2601.02375v1 | LeafTutor: An AI Agent for Programming Assignment Tutoring | AI 辅导智能体提供逐步编程指导，评估显示可比人类导师 | STEM 学位注册率高导致合格导师短缺，需求增加 | STEM 教育编程作业辅导 |
| 49 | http://arxiv.org/abs/2512.12048v1 | Context-Aware Agentic Power Resources Optimisation in EV using Smart2ChargeApp | 上下文敏感多智能体协调框架，动态分配 EV 充电资源 | 动态环境条件下智能 EV 充电生态系统资源分配优化难 | 智能电动汽车充电协调与可持续交通 |
| 50 | http://arxiv.org/abs/2512.12196v1 | AutoMV: An Automatic Multi-Agent System for Music Video Generation | 多智能体系统直接从歌曲生成完整 MV，解决时间一致性 | 现有方法生成短片断，无法对齐音乐结构、节拍或歌词 | 全长音乐视频（MV）自动生成 |
| 51 | http://arxiv.org/abs/2512.12400v1 | Agentic AI for 6G: A New Paradigm for Autonomous RAN Security Compliance | 利用 LLM 代理集成 RAG 管道，实现智能自主的安全合规执行 | 解决传统方法难以跟上不断演变的规范和实时变化问题 | 电信网络安保合规 |
| 52 | http://arxiv.org/abs/2512.13059v1 | An Open and Reproducible Deep Research Agent for Long-Form Question Answering | 结合开源 LLM 与 Web 搜索 API 执行迭代检索推理合成，应用偏好 tuning | 解决真实开放域设置中长形式问答推理质量不足问题 | 深度研究问答系统 |
| 53 | http://arxiv.org/abs/2601.10718v1 | Japanese AI Agent System on Human Papillomavirus Vaccination: System Design | 开发双用途 AI 代理系统，提供验证信息同时生成基于交互的分析报告 | 解决 HPV 疫苗犹豫及 misinformation  exacerbated by 社交媒体问题 | 公共卫生疫苗沟通 |
| 54 | http://arxiv.org/abs/2512.13671v1 | AgentIAD: Tool-Augmented Single-Agent for Industrial Anomaly Detection | 提出工具驱动代理框架，配备感知变焦器与比较检索器进行多阶段检查 | 解决工业异常检测中正常参考样本稀缺及缺陷 subtle localized 问题 | 工业异常检测系统 |
| 55 | http://arxiv.org/abs/2512.14762v1 | Workflows vs Agents for Code Translation | 比较结构化流程与自主代理方法，代理方法更有效解决初始语法错误 | 解决 LLM 训练 HDL 代码有限导致 end-to-end 转译 brittle 易 syntax 错误问题 | MATLAB 到 HDL 代码翻译 |
| 56 | http://arxiv.org/abs/2512.14043v1 | Evaluating Small Language Models for Agentic On-Farm Decision Support Systems | 基准测试 20 个开源 SLM，开发集成五任务专用代理的 agentic AI 系统 | 解决 LLM 计算 demand 限制 access 几乎 exclusively 通过 cloud-based 服务问题 | 奶牛养殖决策支持 |
| 57 | http://arxiv.org/abs/2512.14321v1 | Multi-Agent Medical Decision Consensus Matrix System: An Intelligent Collaborative Framework for Oncology MDT Consultations | 部署 7 个 specialized LLM  agents 模拟 MDT，引入共识矩阵量化一致 | 癌症诊疗缺乏结构化共识量化与决策追溯机制 | 肿瘤多学科会诊 (MDT) |
| 58 | http://arxiv.org/abs/2512.14417v1 | PortAgent: LLM-driven Vehicle Dispatching Agent for Port Terminals | 虚拟专家团队 (VET) 自动化 VDS 迁移，无需专家干预 | 港口车辆调度系统跨终端迁移难、依赖专家 | 自动化集装箱码头 |
| 59 | http://arxiv.org/abs/2512.14846v1 | MALCDF: A Distributed Multi-Agent LLM Framework for Real-Time Cyber | 四个 LLM 智能体协作实时网络防御，加密本体对齐消息 | 传统集中式安全工具漏报自适应多向量攻击 | 实时网络入侵检测与防御 |
| 60 | http://arxiv.org/abs/2512.14910v1 | AgroAskAI: A Multi-Agentic AI Framework for Supporting Smallholder Farmers' Enquiries Globally | 模块化角色专用架构，责任链协调自主智能体 | 小农户缺乏动态协作推理与气候适应决策支持 | 全球小农户气候适应决策 |
| 61 | http://arxiv.org/abs/2512.14990v3 | Imitation Game: Reproducing Deep Learning Bugs Leveraging an Intelligent Agent | RepGen 自动化复现 DL bug，迭代生成 - 验证 -  refine 机制 | DL  bug 复现难、非确定性高、手动复现率低 | 深度学习系统调试与维护 |
| 62 | http://arxiv.org/abs/2512.15231v2 | CangLing-KnowFlow: A Unified Knowledge-and-Flow-fused Agent for Comprehensive Remote Sensing Applications | 融合程序知识库、动态工作流调整与进化记忆模块 | 遥感处理缺乏统一框架管理 diverse 端到端工作流 | 遥感数据自动化处理与解释 |
| 63 | http://arxiv.org/abs/2512.15398v1 | Mapis: A Knowledge-Graph Grounded Multi-Agent Framework for Evidence-Based PCOS Diagnosis | 基于知识图谱的多智能体框架，模拟临床诊断流程 | 现有 PCOS 检测工具依赖大数据且缺乏可解释性 | 多囊卵巢综合征 (PCOS) 诊断 |
| 64 | http://arxiv.org/abs/2512.15930v1 | Scalable Agentic Reasoning for Designing Biologics Targeting Intrinsically Disordered Proteins | 锦标赛推理框架，协调多智能体探索巨大设计空间 | IDP 缺乏稳定结构难成药，需自主系统推理构象 | 靶向无序蛋白的生物药设计 |
| 65 | http://arxiv.org/abs/2512.19742v1 | On-device Large Multi-modal Agent for Human Activity Recognition | 集成 LLM 增强 HAR 性能，提供推理与问答能力 | 传统 HAR 缺乏可解释性与人性化交互 | 医疗保健与智能环境活动识别 |
| 66 | http://arxiv.org/abs/2512.16063v1 | A Multi-Agent Large Language Model Framework for Automated Qualitative Analysis | 三智能体框架 (CoTI) 自动化定性主题分析 | 定性主题分析劳动密集、主观且难扩展 | 慢性病患者体验 qualitative 分析 |
| 67 | http://arxiv.org/abs/2512.16108v1 | WeMusic-Agent: Efficient Conversational Music Recommendation via Knowledge Internalization and Agentic Boundary Learning | 知识内化与智能体边界学习，智能决定何时调用工具 | 对话音乐推荐难平衡领域知识与工具集成 | 个性化对话音乐推荐 |
| 68 | http://arxiv.org/abs/2512.16171v1 | Science Consultant Agent | 结合问卷、文献推荐与原型生成的 AI 工具 | practitioners 选择实施 AI 建模策略效率低 | 产品经理、开发者与研究人员 |
| 69 | http://arxiv.org/abs/2512.16214v2 | PDE-Agent: A toolchain-augmented multi-agent framework for PDE solving | 工具链增强多智能体协作，自动化求解偏微分方程 | 传统 PDE 求解繁琐，依赖专家知识与手动设置 | 工程与科学 research 中的 PDE 求解 |
| 70 | http://arxiv.org/abs/2512.16300v1 | Code-in-the-Loop Forensics: Agentic Tool Use for Image Forgery Detection | 多轮交互框架，智能体自主生成执行低级工具检测伪造 | 现有方法难统一低级 artifacts 与高级语义知识 | 图像伪造检测 (IFD) |
| 71 | http://arxiv.org/abs/2512.16614v1 | "Don't Guess, Escalate: Towards Explainable Uncertainty-Calibrated AI Forensic Agents" | 构建不确定性校准的法证代理框架，组合检测器 | 多媒体取证中真实性验证的可靠性问题 | 多媒体取证领域 |
| 72 | http://arxiv.org/abs/2512.17092v1 | Data Augmentation Supporting a Conversational Agent Designed for Smoking Cessation Support Groups | 采用两级数据增强策略提升戒烟对话代理性能 | 特定领域高质量对话数据稀缺 | 戒烟支持群体 |
| 73 | http://arxiv.org/abs/2512.17308v1 | Large Language Models as Pokémon Battle Agents: Strategic Play and Content Generation | 评估 LLM 作为宝可梦战斗代理的战略决策能力 | 战略决策游戏缺乏动态对手与内容生成 | 回合制战略游戏 |
| 74 | http://arxiv.org/abs/2512.17445v1 | LangDriveCTRL: Natural Language Controllable Driving Scene Editing with Multi-modal Agents | 利用多模态代理管道实现自然语言控制驾驶场景编辑 | 驾驶视频合成缺乏细粒度编辑与真实性 | 驾驶场景合成与编辑 |
| 75 | http://arxiv.org/abs/2512.17462v1 | Behavioural Effects of Agentic Messaging: A Case Study on a Financial Service Application | 评估代理个性化消息对金融应用用户行为影响 | 传统规则系统缺乏自适应用户级决策 | 金融服务客户沟通 |
| 76 | http://arxiv.org/abs/2512.18352v2 | LLM-based Few-Shot Early Rumor Detection with Imitation Agent | 结合自主代理与 LLM 实现少-shot 早期谣言检测 | 时间序列数据稀缺且 LLM 计算成本高 | 社交媒体谣言检测 |
| 77 | http://arxiv.org/abs/2512.18436v1 | VeruSAGE: A Study of Agent-Based Verification for Rust Systems | 研究 LLM 代理开发 Rust 系统正确性证明能力 | LLM 严格推理与证明代码正确性能力存疑 | 系统软件验证 |
| 78 | http://arxiv.org/abs/2512.18440v1 | An Agentic AI Framework for Training General Practitioner Student Skills | 提出代理框架训练全科医学生技能 | 虚拟模拟患者缺乏医学准确性与反馈 | 医学教育与培训 |
| 79 | http://arxiv.org/abs/2512.18450v1 | Agent-Based Output Drift Detection for Breast Cancer Response Prediction in a Multisite Clinical Decision Support System | 提出基于代理框架检测多站点临床 AI 输出漂移 | 集中监控忽略站点特定漂移动态 | 临床决策支持系统 |
| 80 | http://arxiv.org/abs/2512.22113v1 | Agentic Structured Graph Traversal for Root Cause Analysis of Code-related Incidents in Cloud Applications | LLM驱动的结构化图遍历进行云事故根因分析 | 云应用中代码和配置相关故障诊断困难 | 云应用生产环境事故诊断 |
| 81 | http://arxiv.org/abs/2512.22529v1 | Multi-AI Agent Framework Reveals the "Oxide Gatekeeper" in Aluminum Nanoparticle Oxidation | 人机闭环框架中AI Agent验证机器学习势函数演化 | 铝纳米粒子氧化原子机制计算瓶颈 | 科学发现与能源纳米材料设计 |
| 82 | http://arxiv.org/abs/2512.22579v1 | SANet: A Semantic-aware Agentic AI Networking Framework for Cross-layer Optimization in 6G | 语义感知AgentNet架构实现跨层网络优化 | 去中心化Agent目标冲突导致优化困难 | 6G无线网络管理与优化 |
| 83 | http://arxiv.org/abs/2601.10726v1 | Building AI Agents to Improve Job Referral Requests to Strangers | 改进Agent与评估Agent协作优化求职推荐请求 | 求职者向陌生人请求推荐的成功率低 | 专业在线社区求职推荐 |
| 84 | http://arxiv.org/abs/2512.22895v1 | SAMP-HDRL: Segmented Allocation with Momentum-Adjusted Utility for Multi-agent Portfolio Management via Hierarchical Deep Reinforcement Learning | 动态资产分组与上下层Agent协调投资组合管理 | 非平稳市场中投资组合优化困难、DRL可解释性低 | 多市场制度下的投资组合管理 |
| 85 | http://arxiv.org/abs/2512.23010v2 | Masgent: An AI-assisted Materials Simulation Agent | 统一平台整合结构操作、DFT工作流、MLP模拟 | 材料模拟需大量脚本、多步骤、HPC专业知识 | 密度泛函理论与机器学习势模拟 |
| 86 | http://arxiv.org/abs/2512.23292v2 | Agentic Physical AI toward a Domain-Specific Foundation Model for Nuclear Reactor Control | 物理论证驱动策略优化的小型语言模型 | 通用基础模型在安全关键控制中违反物理约束 | 核反应堆控制领域专用基础模型 |
| 87 | http://arxiv.org/abs/2512.23294v1 | Agentic AI-Enhanced Semantic Communications: Foundations, Architecture, and Applications | 统一Agent增强语义通信框架覆盖应用/语义/云边层 | 6G网络从比特传输转向语义信息交换需智能体 | 6G语义通信与多车辆/机器人协作 |
| 88 | http://arxiv.org/abs/2512.23502v2 | Hierarchical Decision Mamba Meets Agentic AI: A Novel Approach for RAN Slicing in 6G | 超级Agent用LLM解释意图+HDM协调切片Agent | 现有RAN切片方法依赖静态映射缺乏自然语言理解 | 6G无线接入网络切片资源调度 |
| 89 | http://arxiv.org/abs/2512.23545v1 | PathFound: An Agentic Multimodal Model Activating Evidence-seeking Pathological Diagnosis | 证据寻求推理通过初诊-证据寻求-终诊三阶段 | 病理基础模型依赖静态推理无重新评估或目标证据获取 | 病理诊断全切片图像分析 |
| 90 | http://arxiv.org/abs/2512.18658v1 | Does It Tie Out? Towards Autonomous Legal Agents in Venture Capital | characterize 资本化表核对任务，提出世界模型架构以实现法律工作流自动化。 | 解决法律尽职调查中多文档推理及证据可追溯性难题。 | 风险投资领域的法律尽职调查 |
| 91 | http://arxiv.org/abs/2512.18669v1 | IntelliCode: A Multi-Agent LLM Tutoring System with Centralized Learner Modeling | 构建围绕集中式学习者状态的多智能体辅导系统，协调六个专用代理。 | 解决传统 LLM 导师缺乏持久知识表示及长期教学支持问题。 | 编程教育与个性化学习辅导 |
| 92 | http://arxiv.org/abs/2512.18847v3 | El Agente Cuantico: Automating quantum simulations | 引入多智能体 AI 系统，将自然语言意图转化为跨异构框架的量子模拟计算。 | 解决量子模拟访问壁垒高及软件工具复杂性问题。 | 物理学与化学领域的量子系统模拟 |
| 93 | http://arxiv.org/abs/2512.19458v1 | An Agentic Framework for Autonomous Materials Computation | 提出领域专用代理，嵌入领域知识确保物理连贯的多步工作流。 | 解决 LLM 静态知识及幻觉阻碍自主研究应用的问题。 | 第一性原理材料计算的自动化 |
| 94 | http://arxiv.org/abs/2512.19864v2 | HARMON-E: Hierarchical Agentic Reasoning for Multimodal Oncology Notes to Extract Structured Data | 提出智能体框架，系统分解复杂肿瘤数据提取为模块化自适应任务。 | 解决非结构化笔记中提取结构化肿瘤数据困难及成本高的问题。 | 大规模临床肿瘤数据的结构化提取 |
| 95 | http://arxiv.org/abs/2601.00818v1 | Agentic AI for Autonomous, Explainable, and Real-Time Credit Risk Decision-Making | 提出 Agentic AI 框架，多智能体系统结合 RL 及自然语言推理评估风险。 | 解决传统模型缺乏自适应推理及自主性无法满足现代金融操作问题。 | 金融服务的实时信用风险决策 |
| 96 | http://arxiv.org/abs/2512.20186v1 | Edge-Served Congestion Control for Wireless Multipath Transmission with a Transformer Agent | 提出 Jazz 系统，利用 Transformer 代理解耦决策与数据路径优化传输。 | 解决 OS 内核拥塞控制开发 overhead 高及部分可观测性问题。 | 无线多径传输网络的拥塞控制 |
| 97 | http://arxiv.org/abs/2512.21360v1 | From Visual Perception to Deep Empathy: An Automated Assessment Framework for House-Tree-Person Drawings Using Multimodal LLMs and Multi-Agent Collaboration | 提出多智能体框架，整合社会心理视角纠正视觉幻觉生成心理报告。 | 解决 HTP 测试评分标准异质及依赖考官主观经验问题。 | 临床心理学中的投射评估自动化 |
| 98 | http://arxiv.org/abs/2512.20550v1 | LLM-Based Authoring of Agent-Based Narratives through Scene Descriptions | 提出系统，将场景结构序列化为自然语言提示生成基于代理的叙事。 | 解决虚拟代理活动原型设计中高门槛及迭代慢的问题。 | 基于代理的叙事内容生成与原型设计 |
| 99 | http://arxiv.org/abs/2512.20586v1 | Automated stereotactic radiosurgery planning using a human-in-the-loop reasoning large language model agent | 开发 SAGE 代理，利用思维链推理改进自动 SRS 治疗计划。 | 解决黑盒 AI 系统因透明度担忧限制临床采用问题。 | 立体定向放射外科治疗计划自动化 |
| 100 | http://arxiv.org/abs/2512.20789v1 | X-GridAgent: An LLM-Powered Agentic AI System for Assisting Power Grid Analysis | 提出 X-GridAgent 系统，集成领域工具与数据库自动化电力系统分析。 | 解决传统分析工具需大量领域专家及手动 effort 限制适应性问题。 | 电力系统运行的智能分析与自动化管理 |
| 101 | http://arxiv.org/abs/2512.20975v2 | SPOT!: Map-Guided LLM Agent for Unsupervised Multi-CCTV Dynamic Object Tracking | 地图引导 LLM 智能体，在无监督下跨摄像头追踪车辆。 | 解决多 CCTV 环境盲区导致的轨迹丢失与 ID 切换问题。 | 智能交通监控 |
| 102 | http://arxiv.org/abs/2512.20991v1 | FinAgent: An Agentic AI Framework Integrating Personal Finance and Nutrition Planning | 模块化多智能体架构，结合个人财务与饮食优化。 | 解决预算有限下的营养充足与成本平衡问题。 | 家庭财务与健康管理 |
| 103 | http://arxiv.org/abs/2512.20996v1 | TrafficSimAgent: A Hierarchical Agent Framework for Autonomous Traffic Simulation with MCP Control | 分层专家智能体框架，自然语言驱动交通仿真实验。 | 降低非专家用户使用交通仿真平台的门槛。 | 交通优化与政策制定 |
| 104 | http://arxiv.org/abs/2512.20997v1 | LLM-Empowered Agentic AI for QoE-Aware Network Slicing Management in Industrial IoT | 集成 RAG 与 DRL 的智能体，动态管理异构网络切片。 | 解决工业物联网动态负载下的低延迟与高可靠性需求。 | 工业物联网网络管理 |
| 105 | http://arxiv.org/abs/2512.23737v1 | Governing Cloud Data Pipelines with Agentic AI | 策略感知控制架构，集成有界智能体治理数据管道。 | 解决云数据管道恢复时间长、资源利用低问题。 | 企业云数据工程 |
| 106 | http://arxiv.org/abs/2512.23742v2 | AgenticTCAD: A LLM-based Multi-Agent Framework for Automated TCAD Code Generation and Device Optimization | 自然语言驱动多智能体框架，端到端自动设备设计。 | 解决 TCAD 模拟中开源资源稀缺导致代码生成难问题。 | 半导体器件设计 |
| 107 | http://arxiv.org/abs/2512.21878v1 | MASFIN: A Multi-Agent System for Decomposed Financial Reasoning and Forecasting | 模块化多智能体，集成结构化指标与非结构化新闻。 | 解决金融预测中信号整合与可复现性问题。 | 量化金融 forecasting |
| 108 | http://arxiv.org/abs/2602.23373v1 | An Agentic LLM Framework for Adverse Media Screening in AML Compliance | 利用LLM代理搜索检索文档，计算负面媒体指数 | 解决传统关键词搜索高误报率与人工审查成本问题 | AML合规筛查 |
| 109 | http://arxiv.org/abs/2512.23875v1 | From Illusion to Insight: Change-Aware File-Level Software Defect Prediction Using Agentic AI | 提出变更感知预测任务与多智能体辩论框架 | 解决传统缺陷预测标签持久性偏差问题 | 软件缺陷预测 |
| 110 | http://arxiv.org/abs/2512.23961v1 | An Comparative Analysis about KYC on a Recommendation System Toward Agentic Recommendation System | 利用代理AI进行KYC评估并优化推荐系统 | 解决金融推荐系统中客户身份验证与内容匹配问题 | 金融推荐系统 |
| 111 | http://arxiv.org/abs/2601.00868v1 | SmartFlow Reinforcement Learning and Agentic AI for Bike-Sharing Optimisation | 整合RL与代理AI，分层优化单车调度与通信 | 解决城市单车共享动态 rebalancing 问题 | 城市交通物流 |
| 112 | http://arxiv.org/abs/2512.24630v1 | How Do Agentic AI Systems Address Performance Optimizations? A BERTopic-Based Analysis of Pull Requests | 实证分析代理生成PR中的性能优化主题与接受率 | 解决代理系统如何处理性能 concerns 不明确问题 | 软件工程实践 |
| 113 | http://arxiv.org/abs/2512.24636v1 | How Do Agentic AI Systems Deal With Software Energy Concerns? A Pull Request-Based Study | 分析代理 authored PR 中的能源意识与优化技术 | 解决代理系统识别与处理软件能源 concerns 不明确问题 | 软件工程实践 |
| 114 | http://arxiv.org/abs/2512.25055v1 | Context-aware LLM-based AI Agents for Human-centered Energy Management Systems in Smart Buildings | 三模块闭环框架实现上下文感知能源管理 | 解决现有能源管理系统缺乏自然语言交互与智能分析问题 | 智能建筑能源管理 |
| 115 | http://arxiv.org/abs/2601.06093v2 | GenAITEd Ghana: A First-of-Its-Kind Context-Aware and Curriculum-Aligned Conversational AI Agent for Teacher Education | 多代理检索增强对话AI，对齐课程与伦理约束 | 解决全球南方教师教育缺乏负责任AI operationalization 问题 | 教师教育 |

[返回目录](#目录)

<a id="cat-02"></a>

## Agent评测与基准

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2512.10971v1 | AI-Trader: Benchmarking Autonomous Agents in Real-Time Financial Markets | 首个全自动、实时、数据无污染的交易Agent评测基准 | 缺乏金融领域Agent系统性基准，通用智能≠交易能力 | 金融市场/交易Agent |
| 2 | http://arxiv.org/abs/2512.01822v2 | InnoGym: Benchmarking the Innovation Potential of AI Agents | 首个评估Agent创新潜力的基准，含性能增益+新颖性双指标 | 现有基准只测正确性，忽略解决方案方法多样性 | 工程与科学领域Agent |
| 3 | http://arxiv.org/abs/2512.01948v2 | How Far Are We from Genuinely Useful Deep Research Agents? | FINDER基准含100任务419检查项，提出DEFT失败分类法 | 现有DRAs基准任务复杂度高、指标主观，不反映用户需求 | 深度研究Agent |
| 4 | http://arxiv.org/abs/2512.02230v1 | Benchmarking LLM Agents for Wealth-Management Workflows | 财富管理12任务对基准，含高/低自主性变体，确定性评分 | 缺乏有意义的Agent财富管理工作适配性评估集 | 财富管理助理 |
| 5 | http://arxiv.org/abs/2512.04123v3 | Measuring Agents in Production | 首个生产环境Agent系统性研究MAP，20案例+306从业者调查 | 生产Agent技术方法缺乏理解 | 工业界Agent部署 |
| 6 | http://arxiv.org/abs/2512.03042v2 | PPTArena: A Benchmark for Agentic PowerPoint Editing | PPT编辑基准，100 decks/2125 slides/800+目标编辑 | 可靠PPT编辑缺乏标准化基准 | PowerPoint编辑Agent |
| 7 | http://arxiv.org/abs/2512.03318v1 | Evaluating Generalization Capabilities of LLM-Based Agents in Mixed-Motive Scenarios Using Concordia | Concordia环境评估零样本混合动机场景合作泛化 | 现有评估方法无法测量社交情境泛化 | LLM社交Agent |
| 8 | http://arxiv.org/abs/2512.03955v1 | Benchmark for Planning and Control with Large Language Model Agents: Blocksworld with Model Context Protocol | Blocksworld基准五复杂度类别，MCP标准工具接口 | LLM Agent规划执行缺乏标准化基准 | LLM规划控制Agent |
| 9 | http://arxiv.org/abs/2512.04324v1 | DAComp: Benchmarking Data Agents across the Full Data Intelligence Lifecycle | 210任务基准覆盖数据工程+分析全生命周期 | 企业数据智能工作流缺乏评估 | 企业数据Agent |
| 10 | http://arxiv.org/abs/2512.04343v1 | The Personalization Paradox: Semantic Loss vs. Reasoning Gains in Agentic AI Q&A | 发现个性化改进推理但降低语义相似度的权衡 | 现有评估方法不适合用户特定响应 | 个性化Agent问答 |
| 11 | http://arxiv.org/abs/2512.07828v2 | The Adoption and Usage of AI Agents: Early Evidence from Perplexity | 首次大规模实地研究AI Agent采用率和使用模式，提出分层Agent分类法 | 谁在使用Agent、使用强度如何、用于什么场景 | 通用AI Agent用户研究与市场分析 |
| 12 | http://arxiv.org/abs/2512.08273v1 | AgentEval: Generative Agents as Reliable Proxies for Human Evaluation of AI-Generated Content | 生成式Agent作为人类评估代理，模拟人类判断评估AI生成内容 | 人工评估成本高、耗时长，需要高效自动化评估方案 | 企业内容生成与质量评估场景 |
| 13 | http://arxiv.org/abs/2512.14720v1 | SoMe: A Realistic Benchmark for LLM-based Social Media Agents | 首个社交媒体Agent基准，包含8类任务、900万+帖子和1.7万+标注查询 | 缺乏综合评估LLM Agent理解媒体内容和用户决策能力的基准 | 社交媒体平台智能Agent评估 |
| 14 | http://arxiv.org/abs/2512.08868v2 | EcomBench: Towards Holistic Evaluation of Foundation Agents in E-commerce | 电商领域整体基准，基于真实用户需求，涵盖多任务类别和三难度级别 | 现有基准集中于学术场景，忽视真实应用中的动态市场和复杂决策 | 电商领域基础Agent能力评估 |
| 15 | http://arxiv.org/abs/2512.09372v1 | Intelligent Resilience Testing for Decision-Making Agents with Dual-Mode Surrogate Adaptation | IRTest统一在线自适应测试框架，双模式代理适应缩小代理与真实Agent差距 | 决策Agent测试因系统架构未知和高维场景空间而困难 | 决策Agent的弹性测试与评估 |
| 16 | http://arxiv.org/abs/2512.10195v1 | AutoMedic: An Automated Evaluation Framework for Clinical Conversational Agents with Medical Dataset Grounding | AutoMedic多Agent模拟框架将静态QA数据集转换为虚拟患者档案，支持多轮临床对话评估 | 动态交互式临床场景评估因患者状态和交互轨迹组合空间巨大而困难 | 临床对话Agent自动化评估 |
| 17 | http://arxiv.org/abs/2512.04416v2 | DataGovBench: Benchmarking LLM Agents for Real-World Data Governance Workflows | 提出 DataGovBench 基准，采用逆向目标方法合成噪声 | 现有基准缺乏数据治理工作流评估 | 数据治理工作流 |
| 18 | http://arxiv.org/abs/2512.05930v1 | PRiSM: An Agentic Multimodal Benchmark for Scientific Reasoning via Python-Grounded Evaluation | Python 接地评估的科学推理多模态基准 | 现有基准缺乏中间推理步骤与科学正确性验证 | 科学推理评估 |
| 19 | http://arxiv.org/abs/2512.06710v1 | Stochasticity in Agentic Evaluations: Quantifying Inconsistency with Intraclass Correlation | 采用组内相关系数 (ICC) 量化评估方差，区分真实能力与测量噪声。 | 当前评估实践掩盖结果方差，无法区分能力提升与幸运采样。 | 智能体系统评估 |
| 20 | http://arxiv.org/abs/2512.07436v2 | LocalSearchBench: Benchmarking Agentic Search in Real-World Local Life Services | 首个本地生活服务代理搜索基准，含多跳 QA 任务及统一交互环境。 | 现有研究聚焦通用检索，垂直领域真实查询模糊且需多跳推理。 | 本地生活服务/搜索 |
| 21 | http://arxiv.org/abs/2512.07497v2 | How Do LLMs Fail In Agentic Scenarios? A Qualitative Analysis of Success and Failure Scenarios of Various LLMs in Agentic Simulations | 细粒度行为分析揭示成功策略及 recurrent 失败模式，强调交互 grounding。 | 模型规模不预测代理鲁棒性，需强调交互式 grounding 及恢复行为。 | 代理仿真/失败分析 |
| 22 | http://arxiv.org/abs/2512.07631v1 | The Agent Capability Problem: Predicting Solvability Through Information-Theoretic Bounds | 引入代理能力问题框架，通过信息获取预测资源约束下问题可解性。 | 自主代理何时 commit 资源到任务，需预测资源需求而非依赖启发式。 | 代理任务规划/资源管理 |
| 23 | http://arxiv.org/abs/2512.10218v2 | Does SWE-Bench-Verified Test Agent Ability or Model Memory? | 揭示基准测试可能反映模型记忆而非解题能力，呼吁使用新数据集 | 基准数据污染导致评估结果失真，无法反映真实代理能力 | SWE-Bench-Verified 基准测试及 LLM 评估 |
| 24 | http://arxiv.org/abs/2512.15751v1 | GLOW: Graph-Language Co-Reasoning for Agentic Workflow Performance Prediction | 结合 GNN 与 LLM 预测智能体工作流性能，捕捉拓扑依赖 | 执行评估成本高，现有预测方法无法捕捉拓扑与语义逻辑 | 智能体工作流（AWs）性能预测 |
| 25 | http://arxiv.org/abs/2512.11589v2 | A Study of Library Usage in Agent-Authored Pull Requests | 实证研究智能体生成 PR 中的库使用频率、依赖与版本实践 | 缺乏对智能体在真实软件开发中如何使用库的了解 | 智能体生成代码的生态系统交互分析 |
| 26 | http://arxiv.org/abs/2512.12634v2 | Modular and Multi-Path-Aware Offline Benchmarking for Mobile GUI Agents | 提出模块化多路径感知离线基准框架，实现高保真可扩展评估 | 解决现有基准单路径惩罚有效替代动作及在线评估不可复现问题 | 移动 GUI 代理评估 |
| 27 | http://arxiv.org/abs/2512.12730v2 | NL2Repo-Bench: Towards Long-Horizon Repository Generation Evaluation of Coding Agents | 设计长程仓库生成基准，评估代理自主设计架构及管理依赖能力 | 解决现有基准无法严格评估构建完整软件系统所需长程能力问题 | 编码代理能力评估 |
| 28 | http://arxiv.org/abs/2512.12791v2 | Beyond Task Completion: An Assessment Framework for Evaluating Agentic AI Systems | 提出端到端代理评估框架，涵盖 LLM、记忆、工具和环境四大支柱 | 解决现有评估依赖二元任务完成指标忽略行为不确定性问题 | 多代理系统评估 |
| 29 | http://arxiv.org/abs/2512.13297v1 | MedInsightBench: Evaluating Medical Analytics Agents Through Multi-Step Insight Discovery in Multimodal Medical Data | 引入首个包含 332 个医疗案例基准，评估 LMM 及代理框架发现洞察能力 | 解决缺乏高质量数据集评估多模态模型发现医疗洞察能力问题 | 医疗数据分析代理 |
| 30 | http://arxiv.org/abs/2512.14014v1 | MobileWorldBench: Towards Semantic World Modeling For Mobile Agents | 引入基准评估 VLM 作为移动 GUI 代理世界模型能力，发布大规模数据集 | 解决 pixel-space 世界模型在 GUI 设置预测 complex 视觉 elements 困难问题 | 移动代理世界建模 |
| 31 | http://arxiv.org/abs/2601.03260v1 | SciNetBench: A Relation-Aware Benchmark for Scientific Literature Retrieval Agents | 提出首个科学网络关系感知基准，系统评估三级关系检索能力 | 解决现有检索代理 focus 内容 level 相似性 unable  decode 关键 relational 动态问题 | 科学文献检索代理 |
| 32 | http://arxiv.org/abs/2512.15144v3 | MCPZoo: A Large-Scale Dataset of Runnable Model Context Protocol Servers for AI Agent | 最大规模 MCP 服务器数据集，含 1.6 万可运行实例 | 缺乏大规模可访问 MCP 数据集阻碍实证研究 | MCP 基于系统研究与安全分析 |
| 33 | http://arxiv.org/abs/2512.15688v1 | BashArena: A Control Setting for Highly Privileged AI Agents | 提供 637 个 Linux 管理任务及 4 种破坏目标的控制测试场 | 高权限自主智能体若错位可能造成严重损害 | 安全关键环境中的 AI 控制研究 |
| 34 | http://arxiv.org/abs/2512.16250v1 | AMUSE: Audio-Visual Benchmark and Alignment Framework for Agentic Multi-Speaker Understanding | 针对多说话人场景的基准与对齐框架，评估 agentic 推理 | 多模态模型在多说话人对话场景推理弱 | 多说话人音频 - 视频理解任务 |
| 35 | http://arxiv.org/abs/2512.16381v1 | A Network Arena for Benchmarking AI Agents on Network Troubleshooting | 最大公开基准 NIKA，零努力重放真实网络场景 | 缺乏标准化基准评估动态网络设置中的 LLM 智能体 | 网络故障诊断与排查智能体 |
| 36 | http://arxiv.org/abs/2512.16444v1 | StarCraft+: Benchmarking Multi-agent Algorithms in Adversary Paradigm | 建立算法对算法环境 SC2BA，刷新 MARL 基准 | 固定内置 AI 对手导致算法评估多样性不足 | 多智能体强化学习算法评估 |
| 37 | http://arxiv.org/abs/2512.16978v1 | A Benchmark and Agentic Framework for Omni-Modal Reasoning and Tool Use in Long Videos | 提出 LongShOTBench 基准与 LongShOTAgent 系统 | 长视频多模态理解缺乏统一评估与代理框架 | 长视频理解与代理 |
| 38 | http://arxiv.org/abs/2512.17776v4 | DEER: A Benchmark for Evaluating Deep Research Agents on Expert Report Generation | 提出 DEER 基准，系统化评估专家级研究报告 | 深度研究报告质量评估缺乏多维标准 | 深度研究代理系统 |
| 39 | http://arxiv.org/abs/2512.17838v1 | ReX-MLE: The Autonomous Agent Benchmark for Medical Imaging Challenges | 提出 ReX-MLE 基准，评估医学成像端到端工作流 | 现有基准未涵盖医学成像领域特定挑战 | 医学成像自主代理 |
| 40 | http://arxiv.org/abs/2512.18080v2 | From Prompt to Product: A Human-Centered Benchmark of Agentic App Generation Systems | 提出以人为本基准，评估提示生成应用系统 | 视觉 polish 与功能可靠性评估标准缺失 | 提示生成应用系统 |
| 41 | http://arxiv.org/abs/2512.18470v4 | SWE-EVO: Benchmarking Coding Agents in Long-Horizon Software Evolution Scenarios | 提出 SWE-EVO 基准，评估长程软件进化场景 | 现有基准聚焦孤立单 issue 任务 | 软件进化编码代理 |
| 42 | http://arxiv.org/abs/2512.19234v1 | DeliveryBench: Can Agents Earn Profit in Real World? | 提出 DeliveryBench，基于真实外卖职业的城市级具身基准。 | 解决现有基准缺乏丰富现实约束及长期目标捕捉能力问题。 | 具身智能体在现实约束下的决策评估 |
| 43 | http://arxiv.org/abs/2512.19432v3 | MobileWorld: Benchmarking Autonomous Mobile Agents in Agent-User Interactive and MCP-Augmented Environments | 引入 MobileWorld 基准，强调长程跨应用工作流及用户交互。 | 解决现有移动基准饱和及缺乏真实模糊指令场景问题。 | 自主移动智能体的能力评估 |
| 44 | http://arxiv.org/abs/2512.20083v1 | Detecting Non-Optimal Decisions of Embodied Agents via Diversity-Guided Metamorphic Testing | 提出 NoD-DGMT 框架，通过多样性引导的蜕变测试检测非最优决策。 | 解决当前评估方法忽视生成计划非功能最优性导致资源浪费问题。 | 具身智能体任务规划的最优性评估 |
| 45 | http://arxiv.org/abs/2512.20798v3 | A Benchmark for Evaluating Outcome-Driven Constraint Violations in Autonomous AI Agents | 引入新基准，包含 40 个场景评估结果驱动的约束违反情况。 | 解决现有安全基准缺乏捕捉现实生产设置中 emergent 违规问题。 | 自主 AI 代理的安全性与对齐评估 |
| 46 | http://arxiv.org/abs/2512.20959v1 | Can Agentic AI Match the Performance of Human Data Scientists? | 设计隐藏变量预测任务，对比 Agent 与人类数据科学家性能。 | 验证 Agentic AI 是否具备人类领域知识洞察力。 | 数据科学工作流 |
| 47 | http://arxiv.org/abs/2512.22256v1 | Agentic Software Issue Resolution with Large Language Models: A Survey | 系统 survey 126 项研究，建立基准、技术与实证分类法。 | 梳理 LLM 智能体在软件问题修复领域的进展与挑战。 | 软件工程研究社区 |
| 48 | http://arxiv.org/abs/2512.21373v1 | AInsteinBench: Benchmarking Coding Agents on Scientific Repositories | 基于真实科研仓库的大规模基准，评估端到端科学计算能力。 | 填补科学计算开发智能体评估的空白。 | 科学计算软件生态 |
| 49 | http://arxiv.org/abs/2512.21302v1 | AndroidLens: Long-latency Evaluation with Nested Sub-targets for Android GUI Agents | 包含 571 个长延迟任务的评估框架，细粒度进度测量。 | 解决现有 GUI 智能体基准任务简单、指标粗糙问题。 | 移动 GUI 自动化 |
| 50 | http://arxiv.org/abs/2512.21613v1 | AMS-IO-Bench and AMS-IO-Agent: Benchmarking and Structured Reasoning for Analog and Mixed-Signal Integrated Circuit Input/Output Design | 领域专用智能体，连接自然语言与工业级 AMS 设计交付物。 | 解决模拟电路 I/O 子系统设计自动化难题。 | 集成电路设计 |
| 51 | http://arxiv.org/abs/2512.21757v1 | How Do Agents Perform Code Optimization? An Empirical Study | 实证研究对比 Agent 与人类性能优化提交。 | 揭示 AI 生成性能 PR 在验证与维护上的局限。 | 软件开发性能优化 |
| 52 | http://arxiv.org/abs/2512.21907v2 | SpatialBench: Can Agents Analyze Real-World Spatial Biology Data? | 146 个可验证问题基准，评估空间生物学数据分析能力。 | 解决空间转录组计算分析瓶颈评估缺失问题。 | 生物计算分析 |
| 53 | http://arxiv.org/abs/2601.02399v1 | ProSoftArena: Benchmarking Hierarchical Capabilities of Multimodal Agents in Professional Software Environments | 构建专业软件环境多模态代理能力层级基准 | 解决现有基准局限于浏览器及基础应用问题 | 专业软件工作流 |
| 54 | http://arxiv.org/abs/2512.24565v3 | MCPAgentBench: A Real-world Task Benchmark for Evaluating LLM Agent MCP Tool Use | 基于真实MCP定义构建基准，测试工具选择与区分能力 | 解决现有MCP评估依赖外部服务及缺乏难度意识问题 | LLM代理工具使用 |
| 55 | http://arxiv.org/abs/2512.24851v2 | VLN-MME: Diagnosing MLLMs as Language-guided Visual Navigation agents | 统一评估框架探测MLLM作为零样本具身导航代理潜力 | 解决MLLM在具身导航中 sequential decision-making 能力未知问题 | 视觉语言导航 |

[返回目录](#目录)

<a id="cat-03"></a>

## Agent安全与对齐

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2512.01295v2 | Systems Security Foundations for Agentic Computing | 从系统安全视角分析Agent端到端安全属性，11个真实攻击案例 | Agent与第三方服务器交互存在数据泄露等安全风险 | Agent系统开发者 |
| 2 | http://arxiv.org/abs/2512.03097v1 | Many-to-One Adversarial Consensus: Exposing Multi-Agent Collusion Risks in AI-Based Healthcare | 揭示多Agent共谋风险，验证Agent可恢复100%准确性 | 多Agent协作中对手可制造虚假共识导致有害处方 | AI医疗系统 |
| 3 | http://arxiv.org/abs/2512.02261v1 | TradeTrap: Are LLM-based Trading Agents Truly Reliable and Faithful? | TradeTrap统一评估框架，压力测试四大核心组件鲁棒性 | 交易Agent在对抗/故障条件下可靠性未经检验 | 金融交易Agent |
| 4 | http://arxiv.org/abs/2512.02282v1 | DialogGuard: Multi-Agent Psychosocial Safety Evaluation of Sensitive LLM Responses | 多Agent框架评估五维度心理社会风险，双Agent校正效果最佳 | LLM在心理健康等敏感服务中社会安全性评估薄弱 | 面向弱势群体的Web应用 |
| 5 | http://arxiv.org/abs/2512.02321v1 | LeechHijack: Covert Computational Resource Exploitation in Intelligent Agent Systems | LeechHijack攻击利用MCP隐式信任，寄生用户计算预算 | MCP开放生态中第三方工具存在隐式毒性攻击风险 | MCP生态系统 |
| 6 | http://arxiv.org/abs/2512.03109v1 | E-valuator: Reliable Agent Verifiers with Sequential Hypothesis Testing | e-valuator将验证器分数转为决策规则， provable 控制误报率 | 启发式验证分数用于决策时无正确性保证 | Agent轨迹评估 |
| 7 | http://arxiv.org/abs/2512.02445v1 | When Refusals Fail: Unstable Safety Mechanisms in Long-Context LLM Agents | 发现长上下文Agent安全机制不稳定，100K token时性能下降超50% | 长上下文Agent能力与安全评估研究空白，拒绝率不可预测 | 长程多步任务Agent |
| 8 | http://arxiv.org/abs/2512.02530v2 | Aetheria: A multimodal interpretable content safety framework based on multi-agent debate and collaboration | Aetheria五Agent协作辩论，RAG知识检索，生成可追溯审计报告 | 现有审核系统基于单模型/固定流水线，难识别隐式风险 | 多模态内容安全 |
| 9 | http://arxiv.org/abs/2512.02682v1 | Beyond Single-Agent Safety: A Taxonomy of Risks in LLM-to-LLM Interactions | 从模型级安全到系统级安全，提出ESRH框架 | 多LLM交互中局部合规聚合为集体失败 | LLM-to-LLM生态系统 |
| 10 | http://arxiv.org/abs/2512.02981v1 | InEx: Hallucination Mitigation via Introspection and Cross-Modal Multi-Agent Collaboration | 内省推理+跨模态多Agent协作，训练免费 | MLLM幻觉问题 | 多模态大语言模型 |
| 11 | http://arxiv.org/abs/2512.03180v1 | AGENTSAFE: A Unified Framework for Ethical Assurance and Governance in Agentic AI | 统一治理框架，将风险分类转化为设计/运行时/审计控制 | 现有治理方法碎片化，缺乏端到端管道 | LLM基Agent系统 |
| 12 | http://arxiv.org/abs/2512.04129v1 | Tipping the Dominos: Topology-Aware Multi-Hop Attacks on LLM-Based Multi-Agent Systems | TOMA拓扑感知多跳攻击，优化污染传播 | MAS安全评估局限于有限攻击场景 | LLM多Agent系统 |
| 13 | http://arxiv.org/abs/2512.03694v1 | SRPG: Semantically Reconstructed Privacy Guard for Zero-Trust Privacy in Educational Multi-Agent Systems | 双流重建机制，严格消毒+上下文重建解耦教学内容与隐私 | 教育MAS中未成年人PII泄露风险 | 教育多Agent系统 |
| 14 | http://arxiv.org/abs/2512.03931v1 | Autonomous Agents and Policy Compliance: A Framework for Reasoning About Penalties | 扩展AOPL整合ASP，基于惩罚推理区分非合规计划 | 政策感知Agent推理潜在惩罚 | 政策合规自主Agent |
| 15 | http://arxiv.org/abs/2512.08104v2 | AgentCrypt: Advancing Privacy and (Secure) Computation in AI Agent Collaboration | 三层隐私保护框架，从 unrestricted 到同态加密，解耦安全与概率推理 | Agent协作中隐私泄露风险，传统访问控制不足 | AI Agent协作平台与隐私合规场景 |
| 16 | http://arxiv.org/abs/2512.08139v1 | Robust Agents in Open-Ended Worlds | 利用开放性和多Agent学习方法训练鲁棒Agent，提出Maestro对抗课程生成 | Agent在陌生环境和分布外输入下的泛化与鲁棒性 | 开放世界中的RL Agent和LLM鲁棒性 |
| 17 | http://arxiv.org/abs/2512.08326v1 | Argus: A Multi-Agent Sensitive Information Leakage Detection Framework Based on Hierarchical Reference Relationships | 三层检测机制整合关键内容、文件上下文和项目引用关系 | 代码仓库敏感信息泄露检测误报率高，人工筛选负担重 | 代码安全审计与敏感信息检测 |
| 18 | http://arxiv.org/abs/2512.08737v1 | Insured Agents: A Decentralized Trust Insurance Mechanism for Agentic Economy | 保险Agent为操作Agent质押 Stake，通过TEE进行隐私保护审计 | LLM Agent不可靠、易被操纵，传统声誉机制在模型快速漂移下失效 | 开放网络中的Agent经济与交易信任 |
| 19 | http://arxiv.org/abs/2512.23717v1 | HarmTransform: Transforming Explicit Harmful Queries into Stealthy via Multi-Agent Debate | 多Agent辩论框架系统地将有害查询转换为更隐蔽形式，保留恶意意图 | 当前安全训练数据忽视隐蔽威胁，用户可通过委婉重述绕过安全机制 | LLM安全对齐与对抗训练数据生成 |
| 20 | http://arxiv.org/abs/2512.09321v3 | ObliInjection: Order-Oblivious Prompt Injection Attack to LLM Agents with Multi-source Data | 首个针对多源输入数据LLM Agent的提示注入攻击，提出顺序无关损失和orderGCG算法 | 现有点注入攻击假设单源输入或忽略多源数据段顺序不确定性 | 多源数据LLM应用与Agent安全 |
| 21 | http://arxiv.org/abs/2512.09756v1 | MOA: Multi-Objective Alignment for Role-Playing Agents | MOA多目标对齐框架，同时训练多个细粒度评分标准优化角色扮演Agent | 角色扮演Agent需同时掌握多冲突技能，现有SFT过拟合表面线索、RL难学多维度 | 角色扮演对话Agent与多轮交互 |
| 22 | http://arxiv.org/abs/2512.04611v1 | PBFuzz: Agentic Directed Fuzzing for PoV Generation | 代理定向模糊测试框架，模拟专家生成漏洞证明 | 现有方法难以高效满足可达性与触发约束 | 软件安全漏洞挖掘 |
| 23 | http://arxiv.org/abs/2512.04668v3 | Topology Matters: Measuring Memory Leakage in Multi-Agent LLMs | MAMA 框架量化网络拓扑对多 Agent 内存泄漏的影响 | 多 Agent LLM 系统中内存泄漏效应未被量化 | 多 Agent 系统安全 |
| 24 | http://arxiv.org/abs/2512.04691v1 | Towards Ethical Multi-Agent Systems of Large Language Models: A Mechanistic Interpretability Perspective | 从机械可解释性视角提出伦理多 Agent 系统研究议程 | 多 Agent 系统存在显著伦理挑战 | 伦理 AI 系统 |
| 25 | http://arxiv.org/abs/2512.04785v1 | ASTRIDE: A Security Threat Modeling Platform for Agentic-AI Applications | 扩展 STRIDE 框架，自动化 Agent 系统威胁建模 | 传统框架无法捕捉 Agent 特有新威胁 | Agent 应用安全 |
| 26 | http://arxiv.org/abs/2512.04822v1 | Enabling Ethical AI: A case study in using Ontological Context for Justified Agentic AI Decisions | 构建可检查语义层，实现可辩护的 Agent 决策 | 缺乏基于显式证据的可解释决策机制 | 伦理 AI 决策 |
| 27 | http://arxiv.org/abs/2512.04864v1 | Are Your Agents Upward Deceivers? | 定义并评估 Agent 向上欺骗行为基准 | Agent 在约束下可能隐瞒失败或执行未请求动作 | Agent 安全性评估 |
| 28 | http://arxiv.org/abs/2512.04895v1 | Chameleon: Adaptive Adversarial Agents for Scaling-Based Visual Prompt Injection in Multimodal AI Systems | 自适应对抗框架，利用缩放漏洞进行视觉提示注入 | 静态攻击无法利用多模态预处理漏洞 | 多模态系统安全 |
| 29 | http://arxiv.org/abs/2512.05013v1 | Detecting Perspective Shifts in Multi-agent Systems | TDKPS 框架嵌入跨时间 Agent，检测行为变化 | 缺乏监控黑盒多 Agent 系统行为动态的原则框架 | 多 Agent 系统监控 |
| 30 | http://arxiv.org/abs/2512.05065v3 | Personalizing Agent Privacy Decisions via Logical Entailment | ARIEL 框架结合逻辑蕴含实现个性化隐私推理 | 仅靠 LLM 无法捕捉用户隐私偏好 | Agent 隐私决策 |
| 31 | http://arxiv.org/abs/2512.05449v1 | The Seeds of Scheming: Weakness of Will in the Building Blocks of Agentic Systems | 引入 akrasia 概念分析 Agent 不一致性与目标漂移 | 模型知道正确答案但未能行动的不一致现象 | Agent 对齐与一致性 |
| 32 | http://arxiv.org/abs/2512.05951v2 | Trusted AI Agents in the Cloud | Omega 系统实现端到端隔离与可验证信任 | 云环境中非信任组件导致数据泄漏与篡改 | 云 Agent 部署 |
| 33 | http://arxiv.org/abs/2512.06196v1 | ARCANE: A Multi-Agent Framework for Interpretable and Configurable Alignment | 将对齐构建为多智能体协作，动态生成可验证的自然语言规则集。 | 长程任务中智能体与利益相关者偏好对齐及可解释性问题。 | 长程任务 AI 系统 |
| 34 | http://arxiv.org/abs/2512.06713v2 | Look Twice before You Leap: A Rational Agent Framework for Localized Adversarial Anonymization | 提出仲裁者作为理性守门人，验证攻击者推理以过滤无效隐私增益。 | 本地小模型匿名化中贪婪策略导致效用崩溃及隐私悖论问题。 | 文本匿名化/隐私保护 |
| 35 | http://arxiv.org/abs/2512.06716v2 | Cognitive Control Architecture (CCA): A Lifecycle Supervision Framework for Robustly Aligned AI Agents | 构建双层防御系统，通过意图图 enforced 控制流及分层裁决器检测偏差。 | 自主 LLM 智能体易受间接提示注入攻击，现有防御架构碎片化。 | AI 智能体安全防御 |
| 36 | http://arxiv.org/abs/2512.06914v2 | SoK: Trust-Authorization Mismatch in LLM Agent Interactions | 提出 B-I-P 框架，映射现有攻击防御，指出动态信任与静态授权失配。 | 静态权限与智能体波动运行时可信度结构性脱节的安全风险。 | LLM 智能体交互安全 |
| 37 | http://arxiv.org/abs/2601.02371v2 | Permission Manifests for Web Agents | 引入 agent-permissions.json 清单，网站指定允许交互，代理自动实施。 | 现有治理机制不适配 LLM 网页代理，网站依赖 blanket blocking。 | 网页代理/自动化交互 |
| 38 | http://arxiv.org/abs/2512.07725v1 | Privacy Practices of Browser Agents | 评估八个浏览器代理隐私行为，识别 30 个漏洞包括禁用隐私功能。 | 浏览器代理自动化能力使其成为高风险失败点，可能导致隐私 harm。 | 浏览器代理/隐私保护 |
| 39 | http://arxiv.org/abs/2512.14737v1 | Zero-Knowledge Audit for Internet of Agents: Privacy-Preserving Communication Verification with Model Context Protocol | 结合零知识证明与 MCP，实现隐私保护的可验证通信审计 | 智能体通信审计与隐私保护存在冲突，难以兼顾 | 智能体通信隐私与合规性审计 |
| 40 | http://arxiv.org/abs/2512.11147v1 | MiniScope: A Least Privilege Framework for Authorizing Tool Calling Agents | 自动重构权限层级，强制执行最小权限原则 | LLM 不可靠性导致工具调用存在安全风险，缺乏严格保障 | 工具调用智能体的权限管理与安全 |
| 41 | http://arxiv.org/abs/2512.11933v1 | The Agentic Regulator: Risks for AI in Finance and a Proposed Agent-based Framework for Governance | 提出模块化治理架构，四层监管块适应快速演化的模型 | 现有框架假设静态算法，无法应对连续学习与 emergent 行为 | 金融市场生成式与智能体 AI 治理 |
| 42 | http://arxiv.org/abs/2512.11421v1 | Towards Trustworthy Multi-Turn LLM Agents via Behavioral Guidance | 行为指导框架，学习可验证观察 - 动作映射，强制约束输出 | 多轮任务中 LLM 行为缺乏可靠性与可验证性 | 多轮 LLM 智能体任务完成可靠性 |
| 43 | http://arxiv.org/abs/2512.12594v2 | ceLLMate: Sandboxing Browser AI Agents | 提出浏览器级沙盒框架，在 HTTP 层限制代理环境权限以减少注入攻击影响 | 解决浏览器使用代理易受提示注入攻击泄露隐私或执行意外动作问题 | 浏览器自动化代理 |
| 44 | http://arxiv.org/abs/2512.12806v1 | Fault-Tolerant Sandboxing for AI Coding Agents: A Transactional Approach to Safe Autonomous Execution | 提出容错沙盒框架，通过策略拦截层和事务性文件系统快照机制保证安全 | 解决自主代码代理执行破坏性命令及系统状态不一致的安全风险 | 自主编码代理执行 |
| 45 | http://arxiv.org/abs/2512.13526v1 | Async Control: Stress-testing Asynchronous Control Measures for LLM Agents | 调查异步监控，开发集成监控器在低误报率下实现低漏报率检测破坏 | 解决软件工程代理访问敏感数据可能故意破坏代码库的安全风险 | LLM 软件工程代理 |
| 46 | http://arxiv.org/abs/2512.15790v1 | Bilevel Optimization for Covert Memory Tampering in Heterogeneous Multi-Agent Architectures (XAMT) | 形式化攻击生成为双层优化问题，最小化扰动最大化系统行为 divergence | 解决 heterogeneous MAS 依赖 centralized 记忆组件 critical shared 漏洞问题 | 多代理系统对抗鲁棒性 |
| 47 | http://arxiv.org/abs/2512.14448v1 | Reasoning-Style Poisoning of LLM Agents via Stealthy Style Transfer: Process-Level Attacks and Runtime Monitoring in RSV Space | 提出推理风格投毒 (RSP) 攻击及 RSV 运行时监控 | 现有攻击忽略推理过程风格，缺乏过程级防御 | 依赖外部检索的 LLM 智能体 |
| 48 | http://arxiv.org/abs/2512.14860v1 | Penetration Testing of Agentic AI: A Comparative Security Analysis Across Models and Frameworks | 首个多模型多框架 Agent 渗透测试对比分析 | 传统 LLM 防护无法解决 Agent 特有安全漏洞 | 企业级 Agent 系统部署 |
| 49 | http://arxiv.org/abs/2512.15892v1 | VET Your Agent: Towards Host-Independent Autonomy via Verifiable Execution Traces | 引入 VET 框架实现主机独立的代理输出认证 | 主机可篡改模型输入输出， undermining 自主性 | 高利害领域自主智能体 (金融/治理) |
| 50 | http://arxiv.org/abs/2512.16279v1 | QuadSentinel: Sequent Safety for Machine-Checkable Control in Multi-agent Systems | 四智能体守卫，将自然语言策略编译为机器可检查规则 | 自然语言安全策略模糊，运行时执行不可靠 | 使用工具的多智能体系统安全 |
| 51 | http://arxiv.org/abs/2512.16962v1 | MemoryGraft: Persistent Compromise of LLM Agents via Poisoned Experience Retrieval | 利用记忆投毒攻击，植入恶意成功体验到长期记忆 | 智能体依赖长期记忆与 RAG 引入新攻击面 | 依赖经验学习的 LLM 智能体 |
| 52 | http://arxiv.org/abs/2512.16310v2 | Agent Tools Orchestration Leaks More: Dataset, Benchmark, and Mitigation | 定义工具编排隐私风险 (TOP-R)，提出缓解策略 | 单智能体多工具架构聚合非敏感片段泄露敏感信息 | 使用工具的单智能体系统隐私 |
| 53 | http://arxiv.org/abs/2512.16433v1 | Emergent Bias and Fairness in Multi-Agent Decision Systems | 大规模仿真揭示多智能体系统中 emergent bias 模式 | 缺乏有效评估方法估计多智能体预测系统 bias 风险 | 金融 tabular 领域多智能体决策 |
| 54 | http://arxiv.org/abs/2512.16532v1 | From Personalization to Prejudice: Bias and Discrimination in Memory-Enhanced AI Agents for Recruitment | 揭示记忆增强个性化代理中偏见引入与放大机制 | 记忆增强代理在招聘场景中的歧视风险 | 招聘领域 AI 代理 |
| 55 | http://arxiv.org/abs/2512.17041v1 | Security Risks of Agentic Vehicles: A Systematic Analysis of Cognitive and Cross-Layer Threats | 分析代理车辆认知层与跨层安全威胁，提出架构 | 现有框架未涵盖车辆安全关键型跨层风险 | 自动驾驶与代理车辆 |
| 56 | http://arxiv.org/abs/2512.17146v1 | Biosecurity-Aware AI: Agentic Risk Auditing of Soft Prompt Attacks on ESM-Based Variant Predictors | 引入 SAGE 框架审计基因组基础模型对抗漏洞 | 基因组模型在对抗操纵下的安全性未探索 | 生物安全与基因组模型 |
| 57 | http://arxiv.org/abs/2512.17259v1 | Verifiability-First Agents: Provable Observability and Lightweight Audit Agents for Controlling Autonomous LLM Systems | 提出可验证优先架构，嵌入轻量审计代理 | 自主 LLM 系统可控性与可审计性不足 | 自主 LLM 系统控制 |
| 58 | http://arxiv.org/abs/2512.17538v1 | Binding Agent ID: Unleashing the Power of AI Agents with accountability and credibility | 提出 BAID 基础设施，建立可验证用户代码绑定 | 自主代理缺乏可追溯问责机制 | 自主 AI 代理身份管理 |
| 59 | http://arxiv.org/abs/2512.18043v1 | Securing Agentic AI Systems -- A Multilayer Security Framework | 提出 MAAIS 多层安全框架，覆盖 AI 生命周期 | 现有框架未充分解决代理 AI 独特安全风险 | 企业级代理 AI 系统 |
| 60 | http://arxiv.org/abs/2512.22387v2 | AI-Generated Code Is Not Reproducible (Yet): An Empirical Study of Dependency Gaps in LLM-Based Coding Agents | 三层依赖框架量化代码执行可复现性 | LLM生成代码依赖声明不完整导致执行失败 | Python/JavaScript/Java代码生成Agent |
| 61 | http://arxiv.org/abs/2512.22883v1 | Agentic AI for Cyber Resilience: A New Security Paradigm and Its System-Theoretic Foundations | 从预防转向弹性，Agent参与感知推理行动适应 | 传统安全架构基于静态规则无法应对自主Agent | 网络与网络物理系统安全 |
| 62 | http://arxiv.org/abs/2512.22894v2 | DECEPTICON: How Dark Patterns Manipulate Web Agents | 700任务环境量化黑暗模式对Agent的操纵风险 | 黑暗模式有效引导Agent轨迹产生恶意结果 | Web导航Agent安全性测试 |
| 63 | http://arxiv.org/abs/2512.22933v3 | Multimodal Fact-Checking: An Agent-based Approach | 五Agent协作模拟人类事实核查工作流 | 多模态 misinformation传播快、现有系统推理浅 | 社交媒体多模态事实核查 |
| 64 | http://arxiv.org/abs/2512.23128v1 | It's a TRAP! Task-Redirecting Agent Persuasion Benchmark for Web Agents | 6前沿模型评估提示注入攻击易感性 | Web Agent易受界面隐藏对抗指令误导偏离原任务 | Web Agent提示注入安全基准 |
| 65 | http://arxiv.org/abs/2512.23132v1 | Multi-Agent Framework for Threat Mitigation and Resilience in AI-Based Systems | 多Agent RAG系统构建本体驱动威胁图 | 传统网络安全缺乏ML特定威胁建模 | AI/基础模型/多模态/RAG系统安全 |
| 66 | http://arxiv.org/abs/2601.00848v1 | Temporal Attack Pattern Detection in Multi-Agent AI Workflows: An Open Framework for Training Trace-Based Security Models | OpenTelemetry追踪分析检测多Agent工作流时序攻击 | 多Agent协调攻击与违规检测缺乏可复现框架 | 多Agent AI工作流安全监控 |
| 67 | http://arxiv.org/abs/2512.23480v1 | Agentic AI for Autonomous Defense in Software Supply Chain Security: Beyond Provenance to Vulnerability Mitigation | LLM推理+RL+多Agent协调主动识别移除漏洞 | 软件供应链攻击聚焦可信流程，传统事后完整性机制失效 | 软件供应链安全CI/CD环境 |
| 68 | http://arxiv.org/abs/2512.23557v1 | Toward Trustworthy Agentic AI: A Multimodal Framework for Preventing Prompt Injection Attacks | 跨Agent多模态溯源感知防御框架净化提示验证输出 | 多Agent环境中多模态提示注入攻击风险增加 | LangChain/GraphChain式多Agent编排安全 |
| 69 | http://arxiv.org/abs/2512.18733v1 | Explainable and Fine-Grained Safeguarding of LLM Multi-Agent Systems via Bi-Level Graph Anomaly Detection | 提出 XG-Guard 框架，利用双层代理编码器检测多智能体系统中的恶意代理。 | 解决现有防御方法缺乏细粒度 lexical 线索及可解释性问题。 | 多智能体系统的安全防护与异常检测 |
| 70 | http://arxiv.org/abs/2512.21354v1 | Reflection-Driven Control for Trustworthy Code Agents | 引入反射驱动控制模块，将自我反思提升为代理推理过程中的显式步骤。 | 解决 LLM 代理缺乏可靠安全控制及输出不可预测问题。 | 安全关键的代码生成任务 |
| 71 | http://arxiv.org/abs/2512.22211v1 | With Great Capabilities Come Great Responsibilities: Introducing the Agentic Risk & Capability Framework for Governing Agentic AI Systems | 引入 ARC 框架，提供基于能力的视角来识别和缓解智能体风险。 | 解决组织在治理自主 AI 系统时难以全面识别评估风险的问题。 | 智能体 AI 系统的组织治理与风险管理 |
| 72 | http://arxiv.org/abs/2512.19117v2 | Stop saying LLM: Large Discourse Models (LDM) and Artificial Discursive Agent (ADA)? | 提出认识论转变，用 LDM 和 ADA 替代 LLM 类别，基于本体三元组。 | 解决公众对生成模型恐惧/迷恋二分法及治理缺失问题。 | 人工智能的社会治理与监管框架 |
| 73 | http://arxiv.org/abs/2512.20275v1 | Graph-Symbolic Policy Enforcement and Control (G-SPEC): A Neuro-Symbolic Framework for Safe Agentic AI in 5G Autonomous Networks | 提出 G-SPEC 神经符号框架，用确定性验证约束概率规划。 | 解决 LLM 代理引入拓扑幻觉及策略不合规等随机风险问题。 | 5G 自主网络中的智能体安全控制 |
| 74 | http://arxiv.org/abs/2601.06062v1 | From Values to Frameworks: A Qualitative Study of Ethical Reasoning in Agentic AI Practitioners | 通过定性访谈调查从业者伦理推理，识别三种 distinct 推理框架。 | 解决缺乏对从业者如何在设计自主系统时权衡伦理困境的了解。 | 智能体开发从业者与伦理治理 |
| 75 | http://arxiv.org/abs/2512.20986v1 | AegisAgent: An Autonomous Defense Agent Against Prompt Injection Attacks in LLM-HARs | 自主感知语义不一致，动态生成验证修复计划。 | 防御 LLM 驱动的人体活动识别系统中的提示注入攻击。 | 可穿戴传感应用 |
| 76 | http://arxiv.org/abs/2512.21250v1 | CoTDeceptor:Adversarial Code Obfuscation Against CoT-Enhanced LLM Code Agents | 构建多阶段混淆策略链，破坏 CoT 驱动的检测逻辑。 | 揭示 CoT 增强型代码检测智能体的系统性弱点。 | 软件供应链安全 |
| 77 | http://arxiv.org/abs/2512.23738v1 | Enforcing Temporal Constraints for LLM Agents | 领域特定语言表达时序属性，SMT 求解检测违规。 | 防止智能体违反时序安全策略（如先认证后访问）。 | 安全关键应用 |
| 78 | http://arxiv.org/abs/2512.21818v1 | Analyzing Code Injection Attacks on LLM-based Multi-Agent Systems in Software Development | 分析多智能体系统代码注入漏洞，提出缓解架构。 | 揭示自主软件工程中多智能体系统的安全脆弱性。 | 软件开发多智能体系统 |
| 79 | http://arxiv.org/abs/2512.23809v1 | Zero-Trust Agentic Federated Learning for Secure IIoT Defense Systems | 结合TPM认证与SHAP加权聚合，实现零信任联邦学习 | 解决IIoT拜占庭攻击与代理认证漏洞问题 | 工业物联网防御系统 |
| 80 | http://arxiv.org/abs/2512.24040v1 | ROAD: Reflective Optimization via Automated Debugging for Zero-Shot Agent Alignment | 利用多智能体架构将失败日志转化为决策树协议 | 解决冷启动阶段缺乏标注数据集进行对齐优化问题 | 零样本代理对齐 |
| 81 | http://arxiv.org/abs/2512.24415v1 | Language Model Agents Under Attack: A Cross Model-Benchmark of Profit-Seeking Behaviors in Customer Service | 跨域基准测试客户服务代理的利润寻求攻击 | 解决 helpful 交互风格被利用导致未授权让步问题 | 客户服务代理 |

[返回目录](#目录)

<a id="cat-04"></a>

## Agent学习与自进化

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2512.01311v2 | CuES: A Curiosity-driven and Environment-grounded Synthesis Framework for Agentic RL | 好奇心驱动、环境落地的任务生成框架，无需手工种子 | 任务稀缺限制Agent强化学习扩展，新环境无预定义任务 | 工具增强环境中的Agent |
| 2 | http://arxiv.org/abs/2512.01945v2 | Agentic Policy Optimization via Instruction-Policy Co-Evolution | INSPO指令 - 策略协同进化，动态优化指令作为RL循环组件 | 静态手工指令对基础模型可能次优，随策略改进需变化 | 多轮检索与推理任务 |
| 3 | http://arxiv.org/abs/2512.02289v3 | Multi-Objective Agentic Rewrites for Unstructured Data Processing | MOAR多目标优化器，30+重写指令，全局搜索算法 | DocETL只优化准确性，忽略成本；算子交互不可预测 | 非结构化数据处理 |
| 4 | http://arxiv.org/abs/2512.02543v1 | In-Context Distillation with Self-Consistency Cascades: A Simple, Training-Free Way to Reduce LLM Agent Costs | 上下文蒸馏+自一致性级联，无需训练降低成本2-2.5倍 | 大规模执行Agent使用高容量LLM推理成本高 | 多步具身推理/API工作流 |
| 5 | http://arxiv.org/abs/2512.02731v1 | Self-Improving AI Agents through Self-Play | 形式化GVU算子，推导方差不等式保证自改进稳定性 | 自改进Agent的稳定性条件 | 自改进AI系统 |
| 6 | http://arxiv.org/abs/2512.03293v1 | Prior preferences in active inference agents: soft, hard, and goal shaping | 四种偏好分布定义方式，目标塑造促进利用 | 主动推理Agent偏好分布指定缺乏关注 | 主动推理Agent |
| 7 | http://arxiv.org/abs/2512.03438v1 | Multimodal Reinforcement Learning with Agentic Verifier for AI Agents | Argos验证Agent选择评分函数评估响应/定位/推理质量 | 多模态RL缺乏细粒度奖励信号 | 多模态推理Agent |
| 8 | http://arxiv.org/abs/2512.03549v1 | PARC: An Autonomous Self-Reflective Coding Agent for Robust Execution of Long-Horizon Tasks | 分层多Agent架构+自评估自反馈机制 | 长视野计算任务自主鲁棒执行 | 计算科学/数据科学任务 |
| 9 | http://arxiv.org/abs/2512.04220v2 | On Group Relative Policy Optimization Collapse in Agent Search: The Lazy Likelihood-Displacement | 发现LLD现象，提出LLDS正则化稳定训练 | GRPO工具集成RL训练崩溃 | 工具集成搜索Agent |
| 10 | http://arxiv.org/abs/2512.08870v2 | Fed-SE: Federated Self-Evolution for Privacy-Constrained Multi-Environment LLM Agents | 联邦自进化框架，本地参数高效微调+全局低秩子空间聚合 | 隐私约束下Agent难以跨动态环境集中优化和协同进化 | 多环境LLM Agent的隐私保护学习 |
| 11 | http://arxiv.org/abs/2512.09108v1 | Evolving Excellence: Automated Optimization of LLM-based Agents | ARTEMIS无代码进化优化平台，通过语义感知遗传算子联合优化Agent配置 | LLM Agent因次优配置表现不佳，手动调优提示和参数需数周时间 | 各类LLM Agent系统自动优化 |
| 12 | http://arxiv.org/abs/2512.09706v1 | Training One Model to Master Cross-Level Agentic Actions via Reinforcement Learning | CrossAgent统一模型掌握异质动作空间，自主为每步选择最有效接口 | 现有Agent局限于静态预定义动作空间，动态环境中交互粒度适应性差 | 开放世界Minecraft等动态环境任务 |
| 13 | http://arxiv.org/abs/2512.10047v1 | Detailed balance in large language model-driven agents | 基于最小作用量原理估计LLM生成方向性，发现LLM生成转移中的详细平衡 | 缺乏理论框架理解LLM驱动Agent的宏观动力学 | LLM Agent动力学理论与统一分析 |
| 14 | http://arxiv.org/abs/2512.04868v1 | SEAL: Self-Evolving Agentic Learning for Conversational Question Answering over Knowledge Graphs | 自进化代理学习框架，集成记忆与反思模块 | 知识图谱问答中结构不准确与计算成本高 | 知识图谱问答 |
| 15 | http://arxiv.org/abs/2512.04987v1 | Nex-N1: Agentic Models Trained via a Unified Ecosystem for Large-Scale Environment Construction | 统一生态系统构建大规模环境，训练 Nex-N1 模型 | 缺乏可扩展基础设施构建高质量交互信号 | 大规模 Agent 训练 |
| 16 | http://arxiv.org/abs/2512.08980v2 | Training Multi-Image Vision Agents via End2End Reinforcement Learning | 端到端 RL 训练多图像视觉 Agent，引入视觉反思工具 | 开源方法限于单图像，缺乏多图像 QA 能力 | 多图像视觉问答 |
| 17 | http://arxiv.org/abs/2512.06060v1 | Reinforcement Learning Integrated Agentic RAG for Software Test Cases Authoring | RL 集成 Agentic RAG，从 QE 反馈持续改进 | conventional 系统无法随时间增强性能 | 软件测试用例生成 |
| 18 | http://arxiv.org/abs/2512.06432v1 | HiveMind: Contribution-Guided Online Prompt Optimization of LLM Multi-Agent Systems | 基于 Shapley 值量化贡献，自主优化低效智能体提示，降低计算成本。 | 多智能体系统中个体有效性评估难及在线优化低效智能体的挑战。 | 金融交易/软件工程 |
| 19 | http://arxiv.org/abs/2512.14708v1 | SGEMAS: A Self-Growing Ephemeral Multi-Agent System for Unsupervised Online Anomaly Detection via Entropic Homeostasis | 耦合结构可塑性与变分自由能目标，系统自然演化最小化预测误差。 | 生理信号监测深度学习拓扑静态且能耗恒定，缺乏动态适应性。 | 生物医学/异常检测 |
| 20 | http://arxiv.org/abs/2512.07094v2 | VIGIL: A Reflective Runtime for Self-Healing Agents | 反射运行时监督兄弟智能体，维护情感银行，生成 guarded prompt 更新。 | 部署系统缺乏运行时自省，无法诊断失败模式及无干预自我改进。 | 智能体运行时维护 |
| 21 | http://arxiv.org/abs/2512.20640v1 | Reflection-Driven Self-Optimization 6G Agentic AI RAN via Simulation-in-the-Loop Workflows | 集成代理 AI 与高保真网络仿真，闭环架构实现自校正系统。 | 当前框架缺乏实证验证与自我改进机制，无法逃逸局部最优。 | 6G 网络/无线接入网 |
| 22 | http://arxiv.org/abs/2512.07478v2 | Enhancing Agentic RL with Progressive Reward Shaping and Value-based Sampling Policy Optimization | 提出渐进式奖励塑造及基于价值采样策略优化，解决稀疏奖励与梯度退化。 | 代理 RL 中稀疏非指导性奖励限制中间步骤指导及收敛速度。 | 工具集成推理任务 |
| 23 | http://arxiv.org/abs/2512.11277v1 | When Actions Teach You to Think: Reasoning-Action Synergy via Reinforcement Learning in Conversational Agents | 利用 RL 直接从任务结果学习推理策略，统一推理与动作学习 | 收集高质量推理迹线成本高，SFT 泛化能力有限 | 对话智能体的推理与工具调用优化 |
| 24 | http://arxiv.org/abs/2512.11485v3 | Mistake Notebook Learning: Batch-Clustered Failures for Training-Free Agent Adaptation | 从批量聚类失败中提炼通用指导，更新外部记忆 | 智能体无法系统地从错误中学习，重复相同错误 | 无训练参数的智能体自适应与进化 |
| 25 | http://arxiv.org/abs/2512.12216v2 | Training Versatile Coding Agents in Synthetic Environments | SWE-Playground 管线从头合成项目与任务，支持多样编码任务 | 依赖现有 GitHub 仓库灵活性低，仅限 issue 解决任务 | 多样化软件工程师任务智能体训练 |
| 26 | http://arxiv.org/abs/2512.12548v2 | World Models Unlock Optimal Foraging Strategies in Reinforcement Learning Agents | 证明配备学习世界模型的人工觅食者自然收敛于边际价值定理策略 | 解决生物觅食者最优补丁离开决策的计算机制不明问题 | 强化学习决策系统 |
| 27 | http://arxiv.org/abs/2512.13043v2 | GTR-Turbo: Merged Checkpoint is Secretly a Free Teacher for Agentic VLM Training | 合并 RL 训练检查点权重作为免费教师指导后续 RL，无需昂贵教师模型 | 解决多模态代理多轮 RL 受稀疏奖励及长程信用分配阻碍问题 | 多模态代理训练 |
| 28 | http://arxiv.org/abs/2512.15784v1 | Beyond Training: Enabling Self-Evolution of Agents with MOBIMEM | 提出以记忆为中心代理系统，三种记忆原语解耦代理进化与模型权重 | 解决当前模型中心代理架构部署后难以自我进化需持续重训练问题 | 移动桌面自动化代理 |
| 29 | http://arxiv.org/abs/2512.13874v1 | SAGE: Training Smart Any-Horizon Agents for Long Video Reasoning with Reinforcement Learning | 提出任何视野代理系统，简单问题单轮处理复杂问题多轮推理，RL 后训练 | 解决 SOTA 模型训练单轮预测处理大量帧资源消耗大缺乏灵活性问题 | 长视频推理系统 |
| 30 | http://arxiv.org/abs/2512.14895v1 | Imitation Learning for Multi-turn LM Agents via On-policy Expert Corrections | 提出 on-policy expert corrections (OECs) 解决 covariate shift | 多轮 LM 智能体模仿学习存在分布偏移问题 | 软件工程多轮交互任务 |
| 31 | http://arxiv.org/abs/2512.15374v1 | SCOPE: Prompt Evolution for Enhancing Agent Effectiveness | 双流机制在线优化提示，平衡战术具体性与战略一般性 | 静态提示无法有效管理 massive 动态上下文 | 动态上下文环境中的 LLM 智能体 |
| 32 | http://arxiv.org/abs/2512.15943v2 | Small Language Models for Efficient Agentic Tool Calling: Outperforming Large Models with Targeted Fine-tuning | 针对性微调小语言模型 (SLM) 执行工具调用任务 | 大模型计算成本高，阻碍企业规模化应用 | 企业级生成式 AI 生产系统集成 |
| 33 | http://arxiv.org/abs/2512.16848v2 | Meta-RL Induces Exploration in Language Agents | 提出 LaMer 框架，通过元强化学习诱导代理主动探索 | RL 训练代理在需要主动探索任务中表现不佳 | 多轮长程任务语言代理 |
| 34 | http://arxiv.org/abs/2512.17008v2 | Turn-PPO: Turn-Level Advantage Estimation with PPO for Improved Multi-Turn RL in Agentic LLMs | 提出 turn-PPO，基于回合级 MDP 优化多轮 RL | 直接应用 GRPO 到多轮任务存在局限性 | 多轮交互 LLM 代理 |
| 35 | http://arxiv.org/abs/2512.17102v2 | Reinforcement Learning for Self-Improving Agent with Skill Library | 提出 SAGE 框架，通过 RL 增强技能库自进化能力 | 技能库依赖提示词导致实现不一致 | 复杂推理与多轮交互代理 |
| 36 | http://arxiv.org/abs/2512.17180v2 | Conservative Bias in Multi-Teacher Learning: Why Agents Prefer Low-Reward Advisors | 揭示交互 RL 中代理偏好保守低奖励教师现象 | 多教师场景下教师选择动态机制不明 | 人机协作与机器人训练 |
| 37 | http://arxiv.org/abs/2512.22200v1 | Emotion-Inspired Learning Signals (EILS): A Homeostatic Framework for Adaptive Autonomous Agents | 提出 EILS 框架，模拟生物情绪作为内部反馈 | 标准代理缺乏内部自主性与非平稳适应 | 开放环境自主代理 |
| 38 | http://arxiv.org/abs/2512.18552v1 | Toward Training Superintelligent Software Agents through Self-Play SWE-RL | 提出 SSR 范式，通过自博弈训练超级智能软件代理 | 代理训练依赖人类知识标注数据 | 软件代理自我进化 |
| 39 | http://arxiv.org/abs/2512.22435v1 | AnalogSAGE: Self-evolving Analog Design Multi-Agents with Stratified Memory and Grounded Experience | 分层记忆与仿真反馈驱动的自进化多Agent框架 | 模拟电路设计依赖人类直觉，自动化程度低 | 模拟电路拓扑生成与参数调优 |
| 40 | http://arxiv.org/abs/2512.22733v1 | FoldAct: Efficient and Stable Context Folding for Long-Horizon Search Agents | 分离损失计算与全上下文一致性损失解决非平稳观测 | 长程RL中上下文增长导致策略依赖分布偏移 | 长视野搜索Agent训练 |
| 41 | http://arxiv.org/abs/2512.23760v1 | Audited Skill-Graph Self-Improvement for Agentic LLMs via Verifiable Rewards, Experience Synthesis, and Continual Memory | 可审计技能图累积可验证可复用能力 | 自改进Agent存在奖励黑客、行为漂移、不可审计 | 持续任务流下的Agent自改进 |
| 42 | http://arxiv.org/abs/2512.23366v1 | AGRO-SQL: Agentic Group-Relative Optimization with High-Fidelity Data Synthesis | 迭代数据工厂合成RL数据+群体相对策略优化 | Text-to-SQL系统缺乏高质量训练数据与复杂推理能力 | BIRD/Spider基准Text-to-SQL系统 |
| 43 | http://arxiv.org/abs/2512.23611v1 | Close the Loop: Synthesizing Infinite Tool-Use Data via Multi-Agent Role-Playing | 三Agent协作自进化合成多样验证轨迹无需人工标注 | 工具调用依赖昂贵人工标注、泛化差、质量上限低 | Berkeley Function-Calling Leaderboard工具使用 |
| 44 | http://arxiv.org/abs/2512.19682v2 | GenEnv: Difficulty-Aligned Co-Evolution Between LLM Agents and Environment Simulators | 建立智能体与环境模拟器之间的难度对齐协同进化游戏。 | 解决真实世界交互数据成本高及静态性质瓶颈问题。 | LLM 智能体的高效训练与能力扩展 |
| 45 | http://arxiv.org/abs/2512.21598v1 | From Shallow Humor to Metaphor: Towards Label-Free Harmful Meme Detection via LMM Agent Self-Improvement | 无标签框架，利用浅层 meme 迭代提升复杂检测能力。 | 解决有害 meme 检测依赖大规模标注数据问题。 | 社交媒体内容审核 |
| 46 | http://arxiv.org/abs/2512.21708v1 | MoRAgent: Parameter Efficient Agent Tuning with Mixture-of-Roles | 混合角色框架，三组 LoRA 分别负责推理、执行、总结。 | 解决智能体任务参数高效微调方法缺失问题。 | LLM 智能体微调 |
| 47 | http://arxiv.org/abs/2512.21782v1 | Accelerating Scientific Discovery with Autonomous Goal-evolving Agents | 双层架构，外环分析结果并提出新目标。 | 解决科学发现中目标函数设计自动化缺失问题。 | 科学发现自动化 |
| 48 | http://arxiv.org/abs/2512.21919v1 | SWE-RM: Execution-free Feedback For Software Engineering Agents | 混合专家奖励模型，提供执行无关的细粒度反馈。 | 解决软件工程中执行反馈稀疏与 RL 训练难问题。 | 软件工程智能体 |
| 49 | http://arxiv.org/abs/2512.22322v2 | SmartSnap: Proactive Evidence Seeking for Self-Verifying Agents | 主动自我验证范式，智能体 curated 快照证据。 | 解决复杂 GUI 任务验证成本高与可靠性低问题。 | 移动任务自动化 |
| 50 | http://arxiv.org/abs/2512.23880v2 | CASCADE: Cumulative Agentic Skill Creation through Autonomous Development and Evolution | 实现代理通过元技能自主掌握工具与编码知识 | 解决LLM代理依赖预定义工具及适应性差问题 | 科学研究任务 |

[返回目录](#目录)

<a id="cat-05"></a>

## 多Agent强化学习

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2512.01321v1 | Extending NGU to Multi-Agent RL: A Preliminary Study | 将NGU算法扩展至多Agent环境，共享经验缓冲区效果最佳 | 稀疏奖励下多Agent探索效率低，学习不稳定 | 多Agent强化学习环境 |
| 2 | http://arxiv.org/abs/2512.02406v1 | Dynamic Configuration of On-Street Parking Spaces using Multi Agent Reinforcement Learning | 两层MARL框架，车道级+街区级Agent，LSTM+图注意力网络 | 路侧停车限制道路宽度加剧交通拥堵 | 城市交通/停车管理 |
| 3 | http://arxiv.org/abs/2512.02442v1 | A Visual Analytics System to Understand Behaviors of Multi Agents in Reinforcement Learning | MARLViz可视化分析系统，展示不同环境下Agent行为差异 | 多Agent交互复杂，现有分析方法难以充分反映解释复杂性 | MARL环境分析 |
| 4 | http://arxiv.org/abs/2512.02535v1 | AID: Agent Intent from Diffusion for Multi-Agent Informative Path Planning | AID用扩散模型生成非自回归长程轨迹，DPPO微调 | 自回归意图预测器计算昂贵、易累积误差 | 环境监测/搜救路径规划 |
| 5 | http://arxiv.org/abs/2512.03166v1 | Multi-Agent Reinforcement Learning and Real-Time Decision-Making in Robotic Soccer for Virtual Environments | 分层RL+平均场理论，实现可扩展多Agent协作 | 动态对抗环境中实时决策和维度灾难 | 虚拟机器人足球 |
| 6 | http://arxiv.org/abs/2512.03528v3 | Multi-Agent Reinforcement Learning with Communication-Constrained Priors | 通信约束先验区分有损无损消息，双互信息估计器 | 现实场景有损通信影响协作策略学习 | 通信受限多Agent系统 |
| 7 | http://arxiv.org/abs/2512.03835v1 | Multi-Agent Deep Reinforcement Learning for UAV-Assisted 5G Network Slicing: A Comparative Study of MAPPO, MADDPG, and MADQN | MAPPO/MADDPG/MADQN对比，CTDE架构优化UAV定位资源分配 | 5G网络切片多目标联合优化 | 5G无人机网络 |
| 8 | http://arxiv.org/abs/2512.04405v1 | Towards 6G Native-AI Edge Networks: A Semantic-Aware and Agentic Intelligence Paradigm | 语义通信+Agent智能统一分类，多AgentRL+基础模型辅助RAN | 现有AI驱动O-RAN方案比特中心任务孤岛 | 6G无线网络 |
| 9 | http://arxiv.org/abs/2512.08132v1 | Multi-agent learning under uncertainty: Recurrence vs. concentration | 分析不确定下多Agent学习的收敛景观，量化强单调博弈中的集中度 | 随机模型下多Agent学习是否收敛及长期行为特征 | 多Agent博弈与强化学习理论研究 |
| 10 | http://arxiv.org/abs/2512.08341v1 | Multi-Agent Deep Reinforcement Learning for Collaborative UAV Relay Networks under Jamming Atatcks | CTDE框架下多Agent强化学习，Agent自发学习抗干扰策略 | 无人机群在对抗环境中最大化吞吐量同时避免碰撞 | 战术通信网络与无人机中继系统 |
| 11 | http://arxiv.org/abs/2512.08877v2 | IPPO Learns the Game, Not the Team: A Study on Generalization in Heterogeneous Agent Teams | 发现IPPO基线在异质多Agent设置中可泛化到新队友算法，无需队友多样性训练 | 自训练PPO Agent是学习通用协调策略还是过拟合训练伙伴行为 | 异质Agent团队协作与泛化能力 |
| 12 | http://arxiv.org/abs/2512.04653v1 | Semi Centralized Training Decentralized Execution Architecture for Multi Agent Deep Reinforcement Learning in Traffic Signal Control | 半集中训练去中心化执行架构，区域参数共享 | 完全集中或分散架构在交通信号控制中的局限 | 交通信号控制 |
| 13 | http://arxiv.org/abs/2512.04918v1 | Multi-Agent Reinforcement Learning for Intraday Operating Rooms Scheduling under Uncertainty | 合作马尔可夫博弈框架，集中训练去中心化执行 | 日内手术室调度下的多目标不确定性决策 | 医疗手术室调度 |
| 14 | http://arxiv.org/abs/2512.04949v2 | CARL: Focusing Agentic Reinforcement Learning on Critical Actions | 关注关键动作的强化学习算法，利用熵作为启发式 | 长视界任务中常规策略优化假设动作贡献相等 | 长视界 Agent 推理 |
| 15 | http://arxiv.org/abs/2512.05447v2 | Distributed scalable coupled policy algorithm for networked multi-agent reinforcement learning | 分布式可扩展耦合策略算法，基于邻居平均 Q 函数 | 网络多 Agent 强化学习中策略相互依赖挑战 | 网络多 Agent 系统 |
| 16 | http://arxiv.org/abs/2512.06645v1 | Analyzing Collision Rates in Large-Scale Mixed Traffic Control via Multi-Agent Reinforcement Learning | 调查 MARL 治理的混合交通控制网络中影响碰撞率的主要因素。 | 混合交通系统中人机车辆交互下的碰撞风险与安全性问题。 | 智能交通系统 |
| 17 | http://arxiv.org/abs/2512.06990v1 | Utilizing Multi-Agent Reinforcement Learning with Encoder-Decoder Architecture Agents to Identify Optimal Resection Location in Glioblastoma Multiforme Patients | 使用 RL 系统生成切除、放疗、化疗模型，反馈循环优化切除位置。 | 缺乏 AI 支持异质性脑肿瘤治疗规划，现有方案计算成本高。 | 医疗/脑肿瘤治疗规划 |
| 18 | http://arxiv.org/abs/2512.07417v1 | Adaptive Tuning of Parameterized Traffic Controllers via Multi-Agent Reinforcement Learning | 多智能体自适应调整状态反馈控制器参数，结合反应性与适应性。 | 传统交通管理策略缺乏适应性，无法应对复杂时变交通动态。 | 交通网络/拥堵缓解 |
| 19 | http://arxiv.org/abs/2512.07588v1 | Understanding Individual Decision-Making in Multi-Agent Reinforcement Learning: A Dynamical Systems Approach | 将 MARL 建模为耦合随机动力系统，分析个体层面行为稳定性与敏感性。 | 分析 MARL 个体决策行为难，传统方法忽略 inherent 随机性。 | 多智能体学习系统 |
| 20 | http://arxiv.org/abs/2512.10439v1 | HypeR Adaptivity: Joint $hr$-Adaptive Meshing via Hypergraph Multi-Agent Deep Reinforcement Learning | 联合优化网格重定位与细化，利用超图多智能体强化学习 | 传统自适应网格计算瓶颈高，精度受限于各向同性细化 | 偏微分方程有限元求解网格生成 |
| 21 | http://arxiv.org/abs/2512.10835v1 | Learning Controllable and Diverse Player Behaviors in Multi-Agent Environments | 定义 N 维连续行为空间，单策略复现多样玩家风格 | 现有方法依赖人类数据或需训练多个模型，缺乏可控性 | 游戏测试、平衡及人类行为模拟 |
| 22 | http://arxiv.org/abs/2512.11179v2 | Bandwidth-constrained Variational Message Encoding for Cooperative Multi-agent Reinforcement Learning | 变分消息编码模块，在带宽约束下控制压缩强度 | 硬带宽约束下 naive 降维损害协调性能，缺乏控制机制 | 带宽受限的多智能体协作通信 |
| 23 | http://arxiv.org/abs/2512.11781v2 | Agile Flight Emerges from Multi-Agent Competitive Racing | 多智能体竞争与稀疏高层目标涌现敏捷飞行与策略 | 单智能体进度奖励在复杂环境中表现差，sim-to-real 转移弱 | 物理世界无人机敏捷飞行控制 |
| 24 | http://arxiv.org/abs/2512.16408v1 | NDRL: Cotton Irrigation and Nitrogen Application with Nested Dual-Agent Reinforcement Learning | 嵌套双智能体 RL，父子智能体协同优化水氮组合 | 水氮组合优化复杂， mild  stress 信号难量化 | 棉花灌溉与氮肥施用管理 |
| 25 | http://arxiv.org/abs/2512.16813v1 | Coordinated Anti-Jamming Resilience in Swarm Networks via Multi-Agent Reinforcement Learning | 基于 QMIX 算法提升 swarm 网络在干扰下的通信韧性 | 反应式干扰器对机器人集群网络的威胁 | 机器人集群通信网络 |
| 26 | http://arxiv.org/abs/2512.17187v2 | MAPPO-LCR: Multi-Agent Proximal Policy Optimization with Local Cooperation Reward in Spatial Public Goods Games | 引入局部合作奖励改进 MAPPO 在公共物品博弈表现 | 现有方法难以表征大群体交互中的收益耦合 | 空间公共物品博弈 |
| 27 | http://arxiv.org/abs/2512.17444v1 | Assessing Long-Term Electricity Market Design for Ambitious Decarbonization Targets using Multi-Agent Reinforcement Learning | 利用 MARL 模拟发电公司投资决策与市场机制 | 长期电力市场设计缺乏高级评估工具 | 电力市场与脱碳政策 |
| 28 | http://arxiv.org/abs/2512.17688v2 | Convergence Guarantees for Federated SARSA with Local Training and Heterogeneous Agents | 提供异构 FedSARSA 收敛性保证与复杂度界 | 联邦 SARSA 在异构环境下的理论分析缺失 | 联邦强化学习系统 |
| 29 | http://arxiv.org/abs/2512.18558v1 | Distributionally Robust Multi-Agent Reinforcement Learning for Intelligent Traffic Control | 开发分布鲁棒 MARL 框架用于交通信号控制 | 学习式控制在不典型交通条件下表现差 | 智能交通信号控制 |
| 30 | http://arxiv.org/abs/2512.22560v1 | RollArt: Scaling Agentic RL Training via Disaggregated Infrastructure | 异构硬件亲和性映射与细粒度异步训练系统 | 多任务Agent RL训练资源利用率低、同步开销大 | 大规模Agent强化学习训练基础设施 |
| 31 | http://arxiv.org/abs/2512.22832v1 | MARPO: A Reflective Policy Optimization for Multi Agent Reinforcement Learning | 反射机制利用后续轨迹提升样本效率 | 多Agent强化学习样本效率低、训练不稳定 | 经典多Agent环境策略优化 |
| 32 | http://arxiv.org/abs/2512.22857v1 | AutoForge: Automated Environment Synthesis for Agentic Reinforcement Learning | 统一流水线自动合成高难度可验证任务环境 | 模拟环境合成半自动化、任务难度不足 | Agent强化学习环境构建 |
| 33 | http://arxiv.org/abs/2512.22876v1 | Reinforcement Networks: novel framework for collaborative Multi-Agent Reinforcement Learning tasks | 将Agent组织为DAG图结构扩展分层RL | 多组件AI系统端到端训练缺乏灵活架构 | 协作多Agent强化学习任务 |
| 34 | http://arxiv.org/abs/2512.22941v1 | Heterogeneity in Multi-Agent Reinforcement Learning | 系统定义量化五种异质性类型并设计参数共享算法 | MARL领域缺乏异质性严格定义与深入理解 | 多Agent强化学习异质性研究 |
| 35 | http://arxiv.org/abs/2512.18892v1 | Structural Reinforcement Learning for Heterogeneous Agent Macroeconomics | 提出结构强化学习方法，代理直接从模拟路径学习均衡价格动态。 | 解决异质代理模型中聚合风险及市场出清条件的求解难题。 | 宏观经济学中的异质代理模型求解 |
| 36 | http://arxiv.org/abs/2512.20135v2 | MolAct: An Agentic RL Framework for Molecular Editing and Property Optimization | 提出 MolAct 框架，将分子设计形式化为智能体强化学习问题。 | 解决分子编辑优化需迭代改进性质同时保持化学有效性问题。 | 分子编辑与属性优化的多步决策 |
| 37 | http://arxiv.org/abs/2512.20201v1 | Joint Design of Embedded Index Coding and Beamforming for MIMO-based Distributed Computing via Multi-Agent Reinforcement Learning | 提出低复杂度 MARL 框架，使分散代理在本地观察下管理混合动作空间。 | 解决无线 MIMO 系统中 EIC 与波束成形联合设计 NP-hard 问题。 | 分布式计算系统中的通信负载优化 |
| 38 | http://arxiv.org/abs/2512.21024v1 | Policy-Conditioned Policies for Multi-Agent Task Solving | 用 LLM 解释源代码策略，实现程序化迭代最佳响应。 | 解决深度强化学习中策略不透明导致的适应性问题。 | 多智能体任务求解 |
| 39 | http://arxiv.org/abs/2512.24325v1 | MaRCA: Multi-Agent Reinforcement Learning for Dynamic Computation Allocation in Large-Scale Recommender Systems | 建模推荐阶段为合作代理，端到端优化计算资源分配 | 解决多阶段计算资源分配忽略依赖性问题 | 大规模推荐系统 |
| 40 | http://arxiv.org/abs/2512.24609v1 | Reinforcement Learning-Augmented LLM Agents for Collaborative Decision Making and Performance Optimization | 采用CTDE与GRPO联合优化代理策略，平衡质量与协调成本 | 解决LLM代理缺乏协作意识及全局性能优化难问题 | 协作写作与编码 |
| 41 | http://arxiv.org/abs/2512.24827v2 | Discovering Coordinated Joint Options via Inter-Agent Relative Dynamics | 联合状态抽象压缩空间，发现强协调行为选项 | 解决多智能体选项设计牺牲协调性问题 | 多智能体规划 |

[返回目录](#目录)

<a id="cat-06"></a>

## Agent工具使用与环境交互

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2602.17046v1 | Dynamic System Instructions and Tool Exposure for Efficient Agentic LLMs | ITR动态检索最小系统指令和工具子集，减少95%上下文token | Agent长程运行成本高、工具选择错误率高 | 长程自主Agent |
| 2 | http://arxiv.org/abs/2512.01763v2 | HiconAgent: History Context-aware Policy Optimization for GUI Agents | 历史上下文感知策略优化，动态采样+锚点引导压缩 | GUI Agent使用全历史导致计算开销大、无关信息干扰 | GUI导航任务 |
| 3 | http://arxiv.org/abs/2512.02423v1 | GUI Exploration Lab: Enhancing Screen Navigation in Agents via Multi-Turn Reinforcement Learning | GUI Exploration Lab仿真环境引擎，多轮RL开发探索策略 | 真实GUI环境复杂专有，难获全面环境信息用于训练评估 | GUI Agent导航研究 |
| 4 | http://arxiv.org/abs/2512.10977v1 | Agentic Operator Generation for ML ASICs | TritorX系统生成481个ATen算子内核通过2万+测试 | 新加速器平台PyTorch后端生成 | ML加速器平台 |
| 5 | http://arxiv.org/abs/2512.09081v1 | AgentComp: From Agentic Reasoning to Compositional Mastery in Text-to-Image Models | 利用LLM的推理和工具使用能力自主构建组合数据集，优化文本到图像模型 | 文本到图像模型难以准确捕捉对象关系和属性绑定等组合性细节 | 文本到图像生成与组合性推理 |
| 6 | http://arxiv.org/abs/2512.04535v2 | GTM: Simulating the World of Tools for AI Agents | 通用工具模型 GTM，模拟工具执行无需真实调用 | 真实工具交互训练成本高、速度慢 | Agent 工具训练 |
| 7 | http://arxiv.org/abs/2512.05111v1 | ARM-Thinker: Reinforcing Multimodal Generative Reward Models with Agentic Tool Use and Visual Reasoning | 代理多模态奖励模型，自主调用工具验证证据 | 现有奖励模型存在幻觉且缺乏视觉 grounding | 多模态奖励建模 |
| 8 | http://arxiv.org/abs/2512.05774v1 | Active Video Perception: Iterative Evidence Seeking for Agentic Long Video Understanding | 证据寻求框架，迭代计划 - 观察 - 反射过程 | 长视频理解依赖查询无关 captioner，浪费计算 | 长视频理解 |
| 9 | http://arxiv.org/abs/2512.06373v1 | VG-Refiner: Towards Tool-Refined Referring Grounded Reasoning via Agentic Reinforcement Learning | 引入两阶段思考重思机制，显式分析并响应工具反馈以修正推理。 | 工具输出不可靠导致多模态推理模型产生幻觉推理的问题。 | 视觉指代与接地推理 |
| 10 | http://arxiv.org/abs/2512.13278v1 | AutoTool: Dynamic Tool Selection and Integration for Agentic Reasoning | 赋予 LLM 代理动态工具选择能力，双阶段优化管道稳定推理及工具选择 | 解决现有方法假设固定工具库存限制代理适应新或 evolving 工具集问题 | 代理推理工具调用 |
| 11 | http://arxiv.org/abs/2512.13438v1 | From User Interface to Agent Interface: Efficiency Optimization of UI Representations for LLM Agents | 提出 UIFormer 框架，合成 UI 转换程序优化 token 效率与完整性协同 | 解决低效 UI 表示造成性能瓶颈及缺乏布尔 oracle 验证语义正确性问题 | LLM 代理 UI 导航 |
| 12 | http://arxiv.org/abs/2512.14429v1 | Seismology modeling agent: A smart assistant for geophysical researchers | 首个 SPECFEM 的 MCP 服务器套件，实现意图驱动对话交互 | 地震波模拟软件学习曲线陡、手动操作复杂 | 地球物理研究人员 |
| 13 | http://arxiv.org/abs/2512.15834v1 | Optimizing Agentic Language Model Inference via Speculative Tool Calls | 推测性工具调用优化，强制序列驻留推理引擎 | 工具交互引入推理性能瓶颈 | 依赖外部工具的 LM 智能体推理 |
| 14 | http://arxiv.org/abs/2512.16262v1 | Learning to Wait: Synchronizing Agents with the Physical World | 扩展 Code-as-Action 至时间域，预测精确等待时长 | 现实任务存在动作延迟，造成时间间隙 (Temporal Gap) | 开放环境中的自主智能体 |
| 15 | http://arxiv.org/abs/2602.23368v1 | Keyword search is all you need: Achieving RAG-Level Performance without vector databases using agentic tool use | 证明代理关键词搜索可达 RAG 性能无需向量库 | RAG 系统存在检索质量依赖与集成成本 | 问答与知识检索系统 |
| 16 | http://arxiv.org/abs/2512.18360v1 | LLM Agents Implement an NLG System from Scratch: Building Interpretable Rule-Based RDF-to-Text Generators | 多代理协作构建可解释规则基于 RDF 文本生成器 | 传统 NLG 依赖监督数据且不可解释 | RDF 到文本生成 |
| 17 | http://arxiv.org/abs/2512.22351v2 | VULCAN: Tool-Augmented Multi Agents for Iterative 3D Object Arrangement | MCP-API与多Agent协作实现3D场景操作 | MLLM在3D场景操作中的视觉定位弱、迭代错误多 | 3D物体排列与场景操纵任务 |
| 18 | http://arxiv.org/abs/2512.23044v2 | Video-Browser: Towards Agentic Open-web Video Browsing | 金字塔感知过滤元数据后按需放大视觉感知 | 开放视频探索规模与细粒度视觉验证难以兼顾 | 开放网络视频浏览研究 |
| 19 | http://arxiv.org/abs/2512.23236v3 | KernelEvolve: Scaling Agentic Kernel Coding for Heterogeneous AI Accelerators at Meta | 图搜索选择策略跨多编程抽象自动生成优化内核 | DLRM内核开发面临架构/硬件异构性瓶颈 | 异构AI加速器内核编码优化 |
| 20 | http://arxiv.org/abs/2512.23424v1 | AKG kernel Agent: A Multi-Agent Framework for Cross-Platform Kernel Synthesis | 多Agent系统自动化内核生成迁移与性能调优 | 手动优化无法跟上AI模型计算需求与硬件更新 | 跨平台高性能计算内核合成 |
| 21 | http://arxiv.org/abs/2512.23646v2 | Active Perception Agent for Omnimodal Audio-Video Understanding | 动态规划自主编排工具调用主动多模态探究 | 全模态大模型细粒度跨模态理解与多模态对齐困难 | 音频视频理解基准测试 |
| 22 | http://arxiv.org/abs/2512.20957v5 | One Tool Is Enough: Reinforcement Learning for Repository-Level LLM Agents | 单工具强化学习训练 LLM 智能体，简化仓库级代码定位。 | 解决大仓库代码定位难、多工具控制复杂问题。 | 软件仓库维护 |
| 23 | http://arxiv.org/abs/2512.22009v1 | iSHIFT: Lightweight Slow-Fast GUI Agent with Adaptive Perception | 隐式慢快混合推理，灵活 token 引导注意力。 | 解决 GUI 智能体效率与细粒度交互精度平衡问题。 | 移动/桌面 GUI 自动化 |
| 24 | http://arxiv.org/abs/2512.22047v1 | MAI-UI Technical Report: Real-World Centric Foundation GUI Agents | 全尺寸基础 GUI 智能体家族，原生设备云协作。 | 解决 GUI 智能体现实部署中交互与架构限制。 | 人机交互基础模型 |
| 25 | http://arxiv.org/abs/2512.23647v1 | Nested Browser-Use Learning for Agentic Information Seeking | 提出嵌套浏览器学习框架，解耦交互控制与页面探索 | 解决浏览器交互复杂性及深层信息获取难问题 | 深度信息搜索任务 |
| 26 | http://arxiv.org/abs/2601.00086v2 | RIMRULE: Improving Tool-Using Language Agents via MDL-Guided Rule Learning | 神经符号方法，从失败轨迹蒸馏规则注入提示 | 解决LLM在特定领域工具使用可靠性差问题 | 领域特定工具使用 |

[返回目录](#目录)

<a id="cat-07"></a>

## Agent架构与框架设计

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2512.01434v1 | A Flexible Multi-Agent LLM-Human Framework for Fast Human Validated Tool Building | CollabToolBuilder四Agent协作（Coach/Coder/Critic/Capitalizer）+人在回路 | 复杂迭代任务需大量人工反馈，领域适配成本高 | 科学文档生成等迭代任务 |
| 2 | http://arxiv.org/abs/2512.01939v1 | An Empirical Study of Agent Developer Practices in AI Agent Frameworks | 首个Agent框架实证研究，分析11910条开发者讨论 | 80%开发者难选合适框架，框架设计问题缺乏关注 | Agent框架开发者 |
| 3 | http://arxiv.org/abs/2512.02227v1 | Orchestration Framework for Financial Agents: From Algorithmic Trading to Agentic Trading | 将传统量化交易系统组件映射为Agent（规划/风控/执行等） | 构建有效交易系统需专业团队多年开发，门槛高 | 金融交易/公众用户 |
| 4 | http://arxiv.org/abs/2512.02228v1 | STRIDE: A Systematic Framework for Selecting AI Modalities -- Agentic AI, AI Assistants, or LLM Calls | STRIDE框架 principled 推荐三种模态选择，准确率92% | indiscriminately部署Agent导致成本高、复杂度大、风险高 | 企业自动化/SRE/合规 |
| 5 | http://arxiv.org/abs/2512.02410v1 | Decentralized Multi-Agent System with Trust-Aware Communication | DMAS去中心化架构，区块链支撑，信任感知通信协议 | 中心化MAS存在单点故障、审查脆弱、扩展性限制 | 互联网Agent基础设施 |
| 6 | http://arxiv.org/abs/2512.02593v1 | Spoken Conversational Agents with Large Language Models | 从级联ASR/NLU到端到端语音原生LLM系统架构 | 语音对话Agent的跨模态对齐与联合训练 | 开放域和任务导向语音助手 |
| 7 | http://arxiv.org/abs/2512.02605v1 | IACT: A Self-Organizing Recursive Model for General AI Agents: A Technical White Paper on the Architecture Behind kragent.ai | 动态递归Agent拓扑，双向状态对话替代单向函数调用 | 静态硬编码Agent工作流的局限性 | 通用自主Agent系统 |
| 8 | http://arxiv.org/abs/2512.03571v1 | EnCompass: Enhancing Agent Programming with Search Over Program Execution Paths | 概率天使非确定性PAN模型，解耦工作流和推理策略 | Agent编程纠缠核心逻辑和推理策略 | Agent编程开发 |
| 9 | http://arxiv.org/abs/2512.03887v2 | A Hierarchical Tree-based approach for creating Configurable and Static Deep Research Agent (Static-DRA) | 可配置分层树静态工作流，Depth/Breadth参数控制研究强度 | 复杂多轮研究任务超越静态RAG限制 | 深度研究Agent |
| 10 | http://arxiv.org/abs/2512.04388v4 | Learning to Orchestrate Agents in Natural Language with the Conductor | Conductor模型RL学习协调策略，动态测试时扩展 | 多LLM协调策略缺乏自动发现 | 多LLM协作系统 |
| 11 | http://arxiv.org/abs/2512.08286v1 | Empowering smart app development with SolidGPT: an edge-cloud hybrid AI agent framework | 边缘-云混合开发者助手，支持本地代码库语义搜索和隐私优先设计 | 云工具数据暴露风险与本地方案上下文理解不足的矛盾 | 移动与软件工程开发工作流 |
| 12 | http://arxiv.org/abs/2512.08769v1 | A Practical Guide for Designing, Developing, and Deploying Production-Grade Agentic AI Workflows | 提出9项生产级Agent工作流最佳实践，涵盖工具优先设计到容器化部署 | 组织难以设计可靠、可观察、可维护且符合安全治理要求的Agent系统 | 企业与研究机构的Agent系统生产部署 |
| 13 | http://arxiv.org/abs/2512.09458v1 | Architectures for Building Agentic AI | 提出Agent系统可靠性是架构属性，定义组件化和接口设计原则 | 缺乏Agent系统架构设计指导，可靠性与失效模式分析不足 | 通用Agentic AI系统架构设计 |
| 14 | http://arxiv.org/abs/2512.09543v2 | SWEnergy: An Empirical Study on Energy Efficiency in Agentic Issue Resolution Frameworks with SLMs | 实证研究SLM在Agent框架中的能效，发现框架架构是能耗主要驱动因素 | 当前Agent框架为强大LLM设计，与SLM配合时能耗高且任务解决率近零 | 资源受限环境下的软件问题自动解决 |
| 15 | http://arxiv.org/abs/2512.09548v1 | Supporting Dynamic Agentic Workloads: How Data and Agents Interact | 提出Agent-Centric Data Fabric架构，利用注意力引导检索和语义微缓存 | 传统数据库难以服务动态、上下文驱动、协作的Agent工作负载 | 多Agent系统的数据管理与优化 |
| 16 | http://arxiv.org/abs/2512.22135v1 | SoDA: An Efficient Interaction Paradigm for the Agentic Web | SoDA正交解耦存储、计算和交互，实现数据作为持久资产、模型作为瞬态工具 | 现有交互模式无法解决数据锁定和认知过载，从杀时间到省时间转变 | Agentic Web用户主权交互范式 |
| 17 | http://arxiv.org/abs/2512.04469v1 | Mathematical Framing for Different Agent Strategies | 引入统一数学框架，提出自由度概念比较策略 | 缺乏比较不同 Agent 策略的严谨语言 | Agent 策略设计 |
| 18 | http://arxiv.org/abs/2512.04702v2 | POLARIS: Is Multi-Agentic Reasoning the Next Wave in Engineering Self-Adaptive Systems? | 三层多 Agent 自适应框架，集成适配器、推理与元学习层 | 传统自适应系统难以应对新兴未知不确定性 | 自适应性系统工程 |
| 19 | http://arxiv.org/abs/2512.05374v1 | Please Don't Kill My Vibe: Empowering Agents with Data Flow Control | 提出数据流控制抽象，原生执行 DFC 策略 | Agent 工作流缺乏管理 undesirable 数据流的机制 | Agent 系统架构 |
| 20 | http://arxiv.org/abs/2512.05815v1 | Optimal Safety-Aware Scheduling for Multi-Agent Aerial 3D Printing with Utility Maximization under Dependency Constraints | 多 UAV 空中 3D 打印协调与任务规划框架 | 多 UAV 协作中的冲突与依赖约束 | 空中 3D 打印 |
| 21 | http://arxiv.org/abs/2512.06404v1 | GENIUS: An Agentic AI Framework for Autonomous Design and Execution of Simulation Protocols | 融合知识图谱与分层 LLM，由有限状态错误恢复机监督协议生成。 | 原子模拟设置与调试需专家知识，限制集成计算材料工程应用。 | 材料发现/原子模拟 |
| 22 | http://arxiv.org/abs/2512.06659v1 | The Evolution of Agentic AI in Cybersecurity: From Single LLM Reasoners to Multi-Agent Systems and Autonomous Pipelines | 提出网络安全中代理 AI 的五代分类法，追踪能力与风险演变。 | 单一模型无法胜任真实 SOC 环境，需向多智能体协作框架演进。 | 网络安全运营中心 |
| 23 | http://arxiv.org/abs/2512.06749v3 | DoVer: Intervention-Driven Auto Debugging for LLM Multi-Agent Systems | 增强假设生成并通过针对性干预主动验证，关注任务解决而非归因。 | 多智能体系统调试难，基于日志的失败定位缺乏验证且归因不当。 | LLM 多智能体系统调试 |
| 24 | http://arxiv.org/abs/2512.07665v1 | Reliable agent engineering should integrate machine-compatible organizational principles | 考察 LLM 代理与组织科学框架平行性，提出可靠性工程原则。 | 代理嵌入社会面临协调、控制及问责问题，需平衡能力与限制。 | 代理工程/可靠性设计 |
| 25 | http://arxiv.org/abs/2512.10350v5 | Geometric Dynamics of Agentic Loops in Large Language Models | 将智能体循环形式化为语义空间离散动力系统，分类动态机制 | 迭代式 LLM 系统时间动态未表征，难以预测稳定性 | 自修正、思维链等迭代式 LLM 系统 |
| 26 | http://arxiv.org/abs/2512.10398v6 | Confucius Code Agent: Scalable Agent Scaffolding for Real-World Codebases | 基于 Confucius SDK 构建可扩展软件工程智能体，支持元智能体优化 | 研究级代理难以扩展至生产级 workload，缺乏可解释性 | 大规模代码库的软件工程任务 |
| 27 | http://arxiv.org/abs/2512.10501v2 | Zero-shot 3D Map Generation with LLM Agents: A Dual-Agent Architecture for Procedural Content Generation | 双智能体架构（Actor-Critic）实现零样本 PCG 参数配置 | 大模型难以 bridging 语义指令与严格参数规范间的差距 | 程序化内容生成（PCG）3D 地图构建 |
| 28 | http://arxiv.org/abs/2512.10937v2 | Agent policies from higher-order causal functions | 建立智能体策略与高阶因果函数对应，桥接 AI 与物理因果 | 缺乏统一形式化语言管理复杂超博弈结构与均衡 | 多智能体系统战略博弈与因果推理 |
| 29 | http://arxiv.org/abs/2512.11270v1 | A-LAMP: Agentic LLM-Based Framework for Automated MDP Modeling and Policy Generation | 自动将自然语言任务转化为 MDP  formulation 并训练策略 | 现实任务 RL 应用建模错误多，代码脆弱，目标不一致 | 强化学习环境的自动化建模与策略生成 |
| 30 | http://arxiv.org/abs/2512.11426v1 | AgentBalance: Backbone-then-Topology Design for Cost-Effective Multi-Agent Systems under Budget Constraints | 先骨干后拓扑设计，在显式预算下构建成本效益多智能体系统 | 现有设计常忽略显式 token 成本与延迟预算，导致次优 | 大规模 Web 应用多智能体系统部署 |
| 31 | http://arxiv.org/abs/2512.12360v1 | VideoARM: Agentic Reasoning over Hierarchical Memory for Long-Form Video Understanding | 提出分层记忆上的代理推理范式，自适应观察思考行动记忆循环 | 解决长视频理解中时序结构复杂及多模态线索密集问题 | 长视频理解场景 |
| 32 | http://arxiv.org/abs/2512.12716v1 | CoDA: A Context-Decoupled Hierarchical Agent with Reinforcement Learning | 提出上下文解耦分层代理，分离高层规划与低层执行，联合优化两角色 | 解决长文本输出积累导致上下文爆炸及推理失败问题 | 复杂多步任务求解 |
| 33 | http://arxiv.org/abs/2512.15787v1 | Toward Agentic Environments: GenAI and the Convergence of AI, Sustainability, and Human-Centric Spaces | 提出代理环境概念框架，利用 GenAI 多代理边缘计算减少技术环境影响 | 解决 prevailing cloud-centric 部署 AI 携带 substantial 环境 footprint 问题 | 可持续 AI 生态系统 |
| 34 | http://arxiv.org/abs/2512.14142v1 | Astraea: A State-Aware Scheduling Engine for LLM-Powered Agents | 提出状态感知分层调度算法，集成请求历史状态与未来预测，自适应 KV 缓存 | 解决现有系统 focus  per-segment  optimization  prevent  minimizing  end-to-end  latency 问题 | LLM 代理推理服务引擎 |
| 35 | http://arxiv.org/abs/2512.15044v1 | Agentic AI for Integrated Sensing and Communication: Analysis, Framework, and Case Study | 提出 agentic ISAC 框架，利用 GenAI 实现感知 - 推理 - 行动循环 | 6G ISAC 系统动态复杂，需更智能自主处理 | 第六代移动通信集成感知通信 |
| 36 | http://arxiv.org/abs/2601.08838v1 | Companion Agents: A Table-Information Mining Paradigm for Text-to-SQL | 引入伴随智能体挖掘数据库隐含信息，缓存查询相关知识 | 工业场景数据库标注缺失，Text-to-SQL 准确率受限 | 标注稀缺的 Text-to-SQL 任务 |
| 37 | http://arxiv.org/abs/2512.16970v1 | PAACE: A Plan-Aware Automated Agent Context Engineering Framework | 提出计划感知上下文工程框架，优化代理状态演化 | 复杂工作流中上下文膨胀与注意力稀释问题 | 长程任务 LLM 代理 |
| 38 | http://arxiv.org/abs/2512.17060v1 | On the Role of Contextual Information and Ego States in LLM Agent Behavior for Transactional Analysis Dialogues | 整合交易分析理论与上下文检索增强代理行为 | 当前代理缺乏心理深度与一致性 | 社会行为模拟对话 |
| 39 | http://arxiv.org/abs/2512.17221v3 | DAVE: A VLM Vision Encoder for Document Understanding and Web Agents | 提出 DAVE 视觉编码器，专为文档与 Web 代理优化 | VLM 视觉编码器缺乏文档结构空间信息 | 文档理解与 Web 代理 |
| 40 | http://arxiv.org/abs/2512.18126v1 | "Efficient Mixture-of-Agents Serving via Tree-Structured Routing, Adaptive Pruning, and Dependency-Aware Prefill-Decode Overlap" | 通过树状路由与自适应剪枝优化混合代理服务 | 混合代理推理通信密集且硬件利用率低 | 混合代理推理服务 |
| 41 | http://arxiv.org/abs/2512.18202v1 | Sophia: A Persistent Agent Framework of Artificial Life | 提出 Sophia 持久代理框架，引入 System 3 元层 | 现有架构缺乏持久身份与长期适应机制 | 人工生命与持久代理 |
| 42 | http://arxiv.org/abs/2512.18337v2 | Towards Efficient Agents: A Co-Design of Inference Architecture and System | 提出 AgentInfer 框架，协同设计推理架构与系统 | 代理部署受限于系统性延迟累积 | 长程推理任务代理 |
| 43 | http://arxiv.org/abs/2601.09728v1 | Eliminating Agentic Workflow for Introduction Generation with Parametric Stage Tokens | 将工作流逻辑参数化为阶段Token单次推理生成 | 预定义Agent工作流推理链长、错误累积、连贯性差 | 研究论文引言生成 |
| 44 | http://arxiv.org/abs/2512.23189v2 | The Dawn of Agentic EDA: A Survey of Autonomous Digital Chip Design | 首次系统框架将Agentic EDA定义为约束神经符号优化 | 芯片设计复杂度超越人类能力，需从L2到L3范式转变 | 自主数字芯片设计RTL-to-GDSII流程 |
| 45 | http://arxiv.org/abs/2512.23631v2 | BOAD: Discovering Hierarchical Software Engineering Agents via Bandit Optimization | 多臂老虎机公式化层次发现自动探索子Agent设计 | 单体Agent处理长程SWE问题保留无关上下文导致泛化差 | SWE-bench软件工程任务 |
| 46 | http://arxiv.org/abs/2512.18599v1 | SimpleCall: A Lightweight Image Restoration Agent in Label-Free Environments with MLLM Perceptual Feedback | 提出基于策略优化的轻量级恢复框架，利用 MLLM 感知反馈进行无标签训练。 | 解决现有恢复代理效率瓶颈及对标注数据的依赖问题。 | 无标签环境下的图像恢复任务 |
| 47 | http://arxiv.org/abs/2601.00809v1 | A Modular Reference Architecture for MCP-Servers Enabling Agentic BIM Interaction | 引入 MCP 服务器模块化参考架构，实现 API 无关的 BIM 交互。 | 解决当前 BIM 侧实现特定于工具且临时性限制复用问题。 | 建筑信息模型（BIM）的智能体交互 |
| 48 | http://arxiv.org/abs/2512.19769v1 | A Declarative Language for Building And Orchestrating LLM-Powered Agent Workflows | 提出声明式系统，分离代理工作流规范与实现，支持多后端执行。 | 解决现有系统紧耦合特定语言及部署模型限制复用问题。 | 企业级 LLM 代理工作流的构建与编排 |
| 49 | http://arxiv.org/abs/2512.19084v1 | `$γ(3,4)$ `Attention' in Cognitive Agents: Ontology-Free Knowledge Representations With Promise Theoretic Semantics | 建立向量 ML 与知识图表示之间的桥梁，无需依赖语言模型。 | 解决复杂本体依赖及不确定性条件下推理的数据压缩问题。 | 认知智能体的知识表示与推理架构 |
| 50 | http://arxiv.org/abs/2512.20111v1 | ABBEL: LLM Agents Acting through Belief Bottlenecks Expressed in Language | 提出 ABBEL 框架，用语言表达的信念状态替代长交互历史维持简洁上下文。 | 解决长序列决策任务中保持完整交互历史计算不可行问题。 | 多步交互任务中的上下文压缩与管理 |
| 51 | http://arxiv.org/abs/2512.20469v1 | Bohrium + SciMaster: Building the Infrastructure and Ecosystem for Agentic Science at Scale | 提出基础设施与生态方法，Bohrium 作为 hub，SciMaster 编排工作流。 | 解决扩展智能体科学时工作流难观察复现及工具非 agent-ready 问题。 | 大规模科学工作流的自动化与生态构建 |
| 52 | http://arxiv.org/abs/2512.20848v1 | Nemotron 3 Nano: Open, Efficient Mixture-of-Experts Hybrid Mamba-Transformer Model for Agentic Reasoning | 提出 Nemotron 3 Nano 模型，混合 MoE Mamba-Transformer 架构优化代理推理。 | 解决现有开源模型推理吞吐量低及激活参数多问题。 | 高效能代理推理的基础模型架构 |
| 53 | http://arxiv.org/abs/2512.20985v1 | A Blockchain-Monitored Agentic AI Architecture for Trusted Perception-Reasoning-Action Pipelines | 结合 LangChain 多智能体与许可链，确保行动可审计。 | 解决自主决策系统中的信任、监督与信息完整性问题。 | 医疗/供应链/智慧城市 |
| 54 | http://arxiv.org/abs/2512.21039v2 | Agentic Multi-Persona Framework for Evidence-Aware Fake News Detection | 多角色智能体框架，融合文本、视觉与上下文信号。 | 解决多模态假新闻检测中的泛化性与可解释性问题。 | 社交媒体信息 integrity |
| 55 | http://arxiv.org/abs/2512.21578v3 | NEMO-4-PAYPAL: Leveraging NVIDIA's Nemo Framework for empowering PayPal's Commerce Agent | 优化搜索发现智能体，微调 Nemotron 小模型。 | 解决检索组件延迟高、成本大问题。 | 电商支付平台 |
| 56 | http://arxiv.org/abs/2512.21720v1 | An Information Theoretic Perspective on Agentic System Design | 信息论视角，量化压缩器与预测器互信息。 | 指导压缩器 - 预测器系统设计以优化下游性能。 | 多 LLM 架构设计 |
| 57 | http://arxiv.org/abs/2512.23743v1 | Hybrid-Code: A Privacy-Preserving, Redundant Multi-Agent Framework for Reliable Local Clinical Coding | 混合神经符号框架，冗余验证确保本地临床编码可靠。 | 解决云 LLM 临床编码的隐私风险与延迟瓶颈。 | 医疗健康本地部署 |
| 58 | http://arxiv.org/abs/2512.22101v1 | A2P-Vis: an Analyzer-to-Presenter Agentic Pipeline for Visual Insights Generation and Reporting | 双部分多智能体管道，从原始数据到可视化报告。 | 解决数据科学管道中视觉证据生成与报告组装缺口。 | 数据可视化报告 |
| 59 | http://arxiv.org/abs/2512.24008v2 | SPARK: Search Personalization via Agent-Driven Retrieval and Knowledge-sharing | 协调基于角色的LLM代理实现任务特定检索与个性化 | 解决静态 profile 无法建模用户动态需求问题 | 个性化搜索系统 |
| 60 | http://arxiv.org/abs/2512.24113v1 | CogRec: A Cognitive Recommender Agent Fusing Large Language Models and Soar for Explainable Recommendation | 融合LLM与Soar认知架构，实现可解释在线学习 | 解决LLM黑盒特性及认知架构知识获取难问题 | 可解释推荐系统 |
| 61 | http://arxiv.org/abs/2512.24189v1 | SCP: Accelerating Discovery with a Global Web of Autonomous Scientific Agents | 建立科学上下文协议标准，整合资源与实验生命周期 | 解决科学工具集成开销大及跨平台协作难问题 | 自主科学发现 |
| 62 | http://arxiv.org/abs/2512.24615v1 | Youtu-Agent: Scaling Agent Productivity with Automated Generation and Hybrid Policy Optimization | 模块化框架支持代理自动生成与混合策略优化 | 解决高质量代理构建成本高及动态适应能力差问题 | 通用代理任务 |
| 63 | http://arxiv.org/abs/2512.24618v2 | Youtu-LLM: Unlocking the Native Agentic Potential for Lightweight Large Language Models | 轻量模型从头预训练，培养原生推理与规划能力 | 解决小模型依赖蒸馏及缺乏内在代理能力问题 | 轻量级代理任务 |
| 64 | http://arxiv.org/abs/2512.24856v1 | Advances in Agentic AI: Back to the Future | 恢复概念清晰度，提供结构化分析框架区分M1/M2 | 解决Agentic AI discourse 碎片化及概念混淆问题 | 领域理论发展 |
| 65 | http://arxiv.org/abs/2512.24873v3 | Let It Flow: Agentic Crafting on Rock and Roll, Building the ROME Model within an Open Agentic Learning Ecosystem | 构建代理学习生态系统，优化代理模型生产管线 | 解决开源社区缺乏端到端代理开发生态系统问题 | 代理模型开发 |
| 66 | http://arxiv.org/abs/2601.00097v3 | The Agentic Leash: Extracting Causal Feedback Fuzzy Cognitive Maps with LLMs | 代理系统提取因果反馈模糊认知地图，保持动态平衡 | 解决从文本提取因果结构及保持系统自主性问题 | 因果推理与建模 |

[返回目录](#目录)

<a id="cat-08"></a>

## Agent仿真与社会模拟

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2512.01610v1 | Agent-Kernel: A MicroKernel Multi-Agent System Framework for Adaptive Social Simulation Powered by LLMs | 社会中心模块化微内核架构，解耦核心功能与仿真逻辑 | 现有框架无法支持人口动态变化、大规模异构Agent仿真 | 社会仿真/群体行为 |
| 2 | http://arxiv.org/abs/2512.02195v1 | A Knowledge-Based Language Model: Deducing Grammatical Knowledge in a Multi-Agent Language Acquisition Simulation | MODOMA成人与儿童Agent交互实现无监督语言习得 | 计算语言习得实验缺乏可控环境与显式知识表示 | 语言习得研究 |
| 3 | http://arxiv.org/abs/2512.02358v1 | Beyond Playtesting: A Generative Multi-Agent Simulation System for Massively Multiplayer Online Games | LLM生成Agent仿真系统，SFT+RL适配真实玩家行为 | 传统优化成本高、离线仿真保真度低，无法模仿真实玩家 | MMO游戏数值设计 |
| 4 | http://arxiv.org/abs/2512.02561v1 | EZYer: A simulacrum of high school with generative agent | EZYer三模块（教师/学生/控制器）四角色协作生成课件笔记 | 现有教育工具服务不完整、性能不足、交互性弱 | 高中教育/在线学习 |
| 5 | http://arxiv.org/abs/2512.08345v1 | The High Cost of Incivility: Quantifying Interaction Inefficiency via Multi-Agent Monte Carlo Simulations | LLM多Agent系统模拟对抗性辩论，量化"毒性延迟"对效率影响 | 职场毒性对运营效率的直接影响难以量化和伦理研究困难 | 组织行为研究与企业效率分析 |
| 6 | http://arxiv.org/abs/2512.09939v1 | Norm-Governed Multi-Agent Decision-Making in Simulator-Coupled Environments:The Reinsurance Constrained Multi-Agent Simulation Process (R-CMASP) | 引入规范可行性层与模拟器耦合的多 Agent 模型 | 确定性自动化缺乏制度风险转移所需的认知灵活性 | 再保险决策模拟 |
| 7 | http://arxiv.org/abs/2512.04988v1 | Strategic Self-Improvement for Competitive Agents in AI Labour Markets | 模拟零工经济中 Agent 竞争与战略自我改进 | 缺乏捕捉 Agent 劳动力市场经济力的框架 | AI 劳动力市场模拟 |
| 8 | http://arxiv.org/abs/2512.05671v1 | MedTutor-R1: Socratic Personalized Medical Teaching with Multi-Agent Simulation | 多 Agent 教学模拟器，训练苏格拉底式导师 | 临床培训需求上升与专家指导稀缺之间的矛盾 | 医学教育 |
| 9 | http://arxiv.org/abs/2512.05812v3 | Toward Efficient and Robust Behavior Models for Multi-Agent Driving Simulation | 实例为中心场景表示，对抗逆强化学习行为模型 | 多 Agent 驾驶模拟需真实且高效的行为模型 | 驾驶仿真 |
| 10 | http://arxiv.org/abs/2512.15728v1 | FedSight AI: Multi-Agent System Architecture for Federal Funds Target Rate Prediction | 多 Agent 框架模拟 FOMC 审议预测利率 | 联邦基金目标利率预测需模拟委员会推理 | 货币政策预测 |
| 11 | http://arxiv.org/abs/2512.07195v1 | MASim: Multilingual Agent-Based Simulation for Social Science | 首个多语言代理仿真框架，支持具多样社会语言 profile 生成代理交互。 | 现有仿真多为单语，无法建模跨语言交互这一真实社会基本属性。 | 社会科学/舆论模拟 |
| 12 | http://arxiv.org/abs/2512.10665v1 | On the Dynamics of Multi-Agent LLM Communities Driven by Value Diversity | 基于价值观多样性构建多智能体社区，模拟集体行为演化 | 价值多样性如何塑造 AI 社区集体行为尚不明确 | 多智能体 LLM 社区集体智能模拟 |
| 13 | http://arxiv.org/abs/2512.11942v1 | Hypergame Rationalisability: Solving Agent Misalignment In Strategic Play | 声明式逻辑语言编码超博弈结构，自动化寻找信念结构 | 缺乏统一形式化语言管理复杂超博弈结构与均衡 | 多智能体系统战略博弈与信念对齐 |
| 14 | http://arxiv.org/abs/2512.11943v1 | How AI Agents Follow the Herd of AI? Network Effects, History, and Machine Optimism | 研究 AI 智能体在网络效应博弈中的决策，揭示历史数据影响 | 多 AI 智能体框架中网络效应驱动的战略互动未充分探索 | 网络效应驱动的多智能体决策模拟 |
| 15 | http://arxiv.org/abs/2512.13481v2 | neuralFOMO: Can LLMs Handle Being Second Best? Measuring Envy-Like Preferences in Multi-Agent Settings | 评估 LLM 在多代理设置下社会比较下是否表现出嫉妒偏好，适应心理问卷 | 解决 LLM 在多代理交互中嫉妒作用未探索及竞争 disposition 设计问题 | 多代理 LLM 系统安全 |
| 16 | http://arxiv.org/abs/2602.22222v1 | TWICE: An LLM Agent Framework for Simulating Personalized User Tweeting Behavior with Long-term Temporal Features | 利用长程 temporal 及 personalized 特征，集成个性化画像事件驱动记忆 | 解决现有用户模拟器集中于集体行为难以 modeling temporal 特征问题 | 社交媒体用户模拟 |
| 17 | http://arxiv.org/abs/2512.17066v1 | "Realistic threat perception drives intergroup conflict: A causal, dynamic analysis using generative-agent simulations" | 利用生成式代理模拟因果分析威胁驱动冲突 | 人类冲突中物质与象征威胁交互机制不明 | 社会冲突仿真研究 |
| 18 | http://arxiv.org/abs/2512.17979v2 | Adaptive Agents in Spatial Double-Auction Markets: Modeling the Emergence of Industrial共生 | 基于 RL 代理模拟空间双向拍卖市场中工业共生 | 现有模型忽略空间结构与自适应企业行为交互 | 工业共生与经济市场 |
| 19 | http://arxiv.org/abs/2512.17900v1 | Diffusion Forcing for Multi-Agent Interaction Sequence Modeling | 提出 MAGNet 框架，生成多智能体交互运动序列 | 多人生成交互建模难以泛化与长序列生成 | 机器人与社会计算 |
| 20 | http://arxiv.org/abs/2512.22608v2 | Beyond Isolated Investor: Predicting Startup Success via Roleplay-Based Collective Agents | 角色扮演Agent模拟VC群体投资决策动态 | 创业成功预测忽略投资者群体集体动态 | 风险投资创业融资预测 |
| 21 | http://arxiv.org/abs/2512.23445v1 | Assessing behaviour coverage in a multi-agent system simulation for autonomous vehicle testing | 行为覆盖度分析评估自动驾驶多Agent仿真 | 自动驾驶系统测试需全面评估多样化复杂场景 | 自动驾驶车辆测试仿真 |
| 22 | http://arxiv.org/abs/2512.18803v1 | Quantifying the Lifelong Impact of Resilience Interventions via Agent-Based LLM Simulation | 引入 LALS 框架，通过数字克隆模拟多十年反事实生活轨迹。 | 解决社会科学中长期因果影响难以通过传统研究确立的问题。 | 心理干预对社会结果的长期影响模拟 |
| 23 | http://arxiv.org/abs/2512.19933v1 | PRISM: A Personality-Driven Multi-Agent Framework for Social Media Simulation | 引入 PRISM 框架，耦合 SDE 与 personality-conditional POMDP 模拟意见动态。 | 解决传统 ABM 因同质假设无法捕捉心理异质性驱动极化问题。 | 社交媒体生态系统中的舆论演化模拟 |
| 24 | http://arxiv.org/abs/2512.21467v1 | The Peter Principle Revisited: An Agent-Based Model of Promotions, Efficiency, and Mitigation Policies | 大规模基于智能体模型，模拟五级层级晋升动态。 | 研究彼得原理 emergence 及缓解策略。 | 组织管理仿真 |
| 25 | http://arxiv.org/abs/2512.22082v1 | Agent-based simulation of online social networks and disinformation | 生成模块生成上下文感知帖子，红模块 orchestrate 虚假信息。 | 解决 OSN 研究数据获取难与伦理约束问题。 | 社交网络与虚假信息研究 |
| 26 | http://arxiv.org/abs/2512.24145v3 | When Does Pairing Seeds Reduce Variance? Evidence from a Multi-Agent Economic Simulation | 分析共享随机种子下多智能体经济模拟的方差结构 | 解决独立评估掩盖系统性差异的统计问题 | 多智能体经济模拟 |

[返回目录](#目录)

<a id="cat-09"></a>

## 多Agent协作与通信

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2512.01853v2 | COACH: Collaborative Agents for Contextual Highlighting -- A Multi-Agent Framework for Sports Video Analysis | 可重构MAS，各Agent作为专用"认知工具"灵活组合 | 端到端模型缺乏时序层次理解、泛化差、可解释性低 | 体育视频分析 |
| 2 | http://arxiv.org/abs/2512.02405v1 | WISE: Weighted Iterative Society-of-Experts for Robust Multimodal Multi-Agent Debate | WISE多Agent辩论框架，Solver+Reflector分工，改进Dawid-Skene聚合 | 多Agent辩论多用于语言任务，多模态问题有效性未探索 | 视觉 - 语言推理任务 |
| 3 | http://arxiv.org/abs/2512.02485v1 | UCAgents: Unidirectional Convergence for Visual Evidence Anchored Multi-Agent Medical Decision-Making | UCAgents层级框架强制单向收敛，结构化证据审计 | 多Agent辩论放大文本噪声，推理脱离可验证图像证据 | 医疗诊断/VLM |
| 4 | http://arxiv.org/abs/2602.19040v1 | Adaptive Multi-Agent Reasoning for Text-to-Video Retrieval | 自适应多Agent检索框架，四Agent动态协调+检索性能记忆 | 现有方法难以处理涉及时序/逻辑/因果关系的复杂查询 | 文本 - 视频检索 |
| 5 | http://arxiv.org/abs/2512.02812v1 | Enhancing Automated Paper Reproduction via Prompt-Free Collaborative Agents | 无提示协作Agent框架，验证+精炼双Agent自动改进 | 论文复现缺乏验证机制和手动提示依赖 | 学术论文代码复现 |
| 6 | http://arxiv.org/abs/2512.10975v1 | GRAND: Guidance, Rebalancing, and Assignment for Networked Dispatch in Multi-Agent Path Finding | GNN策略+最小成本流+局部分配，分层调度 | 大型机器人车队任务调度拥堵 | 仓库物流机器人 |
| 7 | http://arxiv.org/abs/2512.03285v1 | A Gossip-Enhanced Communication Substrate for Agentic AI: Toward Decentralized Coordination in Large-Scale Multi-Agent Systems | 重访gossip协议作为Agent通信补充基质 | 大规模自适应系统缺乏灵活去中心化协调 | 大规模多Agent系统 |
| 8 | http://arxiv.org/abs/2512.03445v1 | Multi-Aspect Knowledge-Enhanced Medical Vision-Language Pretraining with Multi-Agent Data Generation | MAGEN多Agent数据生成+O-MAKE本体知识增强预训练 | 医疗VLP数据噪声和长文本复杂性 | 医学图像分析 |
| 9 | http://arxiv.org/abs/2512.03466v1 | AsymPuzl: An Asymmetric Puzzle for multi-agent cooperation | 非对称谜题环境隔离信息不对称下通信 | 现有设置强调开放角色扮演而非控制评估 | 多轮多Agent协作 |
| 10 | http://arxiv.org/abs/2512.03639v1 | Context-Triggered Contingency Games for Strategic Multi-Agent Interaction | 上下文触发应急游戏，两层架构保证高层目标 | 自主多Agent系统可靠高效交互 | 自动驾驶/机器人导航 |
| 11 | http://arxiv.org/abs/2512.08281v1 | Probabilistic Multi-Agent Aircraft Landing Time Prediction | 概率多Agent框架预测多架飞机着陆时间分布，考虑空中交互影响 | 飞机轨迹不确定性和多Agent交互影响着陆时间预测 | 空中交通管理与机场资源调度 |
| 12 | http://arxiv.org/abs/2512.08296v2 | Towards a Science of Scaling Agent Systems | 推导Agent系统定量扩展原则，识别工具-协调权衡等三种效应 | Agent系统性能决定原则不明，多Agent协调策略选择困难 | 大规模Agent系统设计与优化 |
| 13 | http://arxiv.org/abs/2512.08476v1 | A Multi-Agent LLM Framework for Design Space Exploration in Autonomous Driving Systems | 多Agent LLM框架整合多模态推理与3D仿真，自动化解释执行输出 | 自动驾驶系统设计空间探索需人工评估输出，难以处理多模态结果 | 自动驾驶系统设计与自动化探索 |
| 14 | http://arxiv.org/abs/2512.08545v1 | Curriculum Guided Massive Multi Agent System Solving For Robust Long Horizon Tasks | 64×64轻量Agent网格分层架构，空间课程逐步扩展操作区域 | LLM和多Agent系统难以处理长视野推理任务且计算成本攀升 | 机器人操作与长程规划任务 |
| 15 | http://arxiv.org/abs/2512.08743v3 | Single-Agent Scaling Fails Multi-Agent Intelligence: Towards Foundation Models with Native Multi-Agent Intelligence | 实证证明单Agent扩展不能自动产生多Agent智能，提出四核心能力 | 基础模型缺乏原生多Agent智能，理解、规划、通信、适应能力不足 | 基础模型与多Agent系统研发 |
| 16 | http://arxiv.org/abs/2512.11001v1 | Query Optimization Beyond Data Systems: The Case for Multi-Agent Systems | 提出面向多Agent工作流的下一代查询优化框架愿景 | 当前Agent架构临时性强，缺乏通用性、可扩展性和系统优化 | 多Agent工作流与异构数据源查询优化 |
| 17 | http://arxiv.org/abs/2512.10166v1 | Emergent Collective Memory in Decentralized Multi-Agent AI Systems | 展示去中心化多Agent系统中集体记忆如何通过个体记忆与环境痕迹交互涌现 | 个体记忆与环境痕迹通信如何相互作用产生空间分布式集体记忆 | 去中心化多Agent系统协调与记忆 |
| 18 | http://arxiv.org/abs/2512.04488v2 | Persona-based Multi-Agent Collaboration for Brainstorming | 基于角色的多 Agent 头脑风暴框架，评估角色配对影响 | 通用多 Agent 协作缺乏多样性与深度 | 创意头脑风暴 |
| 19 | http://arxiv.org/abs/2512.13704v1 | Adjudicator: Correcting Noisy Labels with a KG-Informed Council of LLM Agents | KG informed 代理委员会辩论投票纠正标签噪声 | 生产 ML 系统中标签噪声降低性能与信任 | 数据验证与清洗 |
| 20 | http://arxiv.org/abs/2512.05788v1 | Task-Specific Trust Evaluation for Multi-Hop Collaborator Selection via GNN-Aided Distributed Agentic AI | GNN 辅助分布式代理 AI，评估多跳协作信任 | 多跳协作信任评估复杂且动态 | 网络设备协作 |
| 21 | http://arxiv.org/abs/2512.06256v1 | Convergence of Outputs When Two Large Language Models Interact in a Multi-Agentic Setup | 研究无外部输入下两 LLM 多轮交互的输出收敛与重复现象。 | 多智能体设置中模型交互导致的对话重复与方向迷失问题。 | 多 LLM 交互系统 |
| 22 | http://arxiv.org/abs/2512.06595v1 | ChargingBoul: A Competitive Negotiating Agent with Novel Opponent Modeling | 基于出价模式分类对手，动态调整策略并在后期应用让步政策。 | 自动化谈判中平衡让步与对手建模以最大化效用并达成协议。 | 电子商务/资源分配 |
| 23 | http://arxiv.org/abs/2512.07132v1 | DART: Leveraging Multi-Agent Disagreement for Tool Recruitment in Multimodal Reasoning | 利用多辩论视觉智能体间分歧识别有用工具，引入新信息解决分歧。 | 知道调用哪些视觉工具及何时调用具有挑战性，易导致幻觉。 | 多模态推理/工具调用 |
| 24 | http://arxiv.org/abs/2512.07462v2 | "Understanding LLM Agent Behaviours via Game Theory: Strategy Recognition, Biases and Multi-Agent Dynamics" | 扩展 FAIRGAME 框架，通过博弈环境评估 LLM 战略行为及意图。 | 需理解 LLM 作为自主决策者的战略行为以保障安全与协调。 | AI 治理/多智能体系统 |
| 25 | http://arxiv.org/abs/2512.11213v1 | FutureWeaver: Planning Test-Time Compute for Multi-Agent Systems with Modularized Collaboration | 模块化协作框架，规划优化多智能体系统测试时计算分配 | 缺乏原则性机制在预算约束下分配计算以促进协作 | 多智能体系统推理时计算资源优化 |
| 26 | http://arxiv.org/abs/2512.12950v1 | Building from Scratch: A Multi-Agent Framework with Human-in-the-Loop for Multilingual Legal Terminology Mapping | 提出人机协作多代理框架，AI 处理重复任务人类提供监督与法律判断 | 解决中英日法律术语映射中同源异义词挑战及资源工具有限问题 | 多语言法律术语库 |
| 27 | http://arxiv.org/abs/2512.12989v1 | Quantigence: A Multi-Agent AI Framework for Quantum Security Research | 提出理论驱动多代理框架，分解角色协调分析，集成外部知识优先漏洞 | 解决后量子密码迁移受研究速度标准演进及异构部署环境阻碍问题 | 量子安全研究分析 |
| 28 | http://arxiv.org/abs/2512.22149v2 | Adaptive GPU Resource Allocation for Multi-Agent Collaborative Reasoning in Serverless Environments | 提出自适应 GPU 资源分配框架，动态分配基于负载特征代理优先级 | 解决无服务器 GPU 平台部署多代理系统资源分配挑战及成本问题 | 无服务器多代理系统 |
| 29 | http://arxiv.org/abs/2512.13154v1 | MAC: A Multi-Agent Framework for Interactive User Clarification in Multi-turn Conversations | 提出交互式多代理框架，自主协调多代理协同与用户交互解决歧义 | 解决对话代理遇到模糊用户请求时确定哪个代理发起澄清困难问题 | 多轮对话歧义消除 |
| 30 | http://arxiv.org/abs/2512.13930v1 | Hierarchical Multi-agent Large Language Model Reasoning for Autonomous Functional Materials Discovery | 引入 MASTER 主动学习框架，LLM 自主设计执行解释原子模拟，分层策略 | 解决大多数方法自动化 procedural 任务未 engage 科学 reasoning 限制 autonomy 问题 | 功能材料自主发现 |
| 31 | http://arxiv.org/abs/2512.13956v2 | AOI: Context-Aware Multi-Agent Operations via Dynamic Scheduling and Hierarchical Memory Compression | 集成三专用代理与 LLM 上下文压缩器，动态任务调度三层记忆架构 | 解决云原生架构复杂性导致 operational 数据 overwhelming 及 context 丢失问题 | IT 基础设施自主运维 |
| 32 | http://arxiv.org/abs/2512.13982v2 | FocalComm: Hard Instance-Aware Multi-Agent Perception | 提出协作感知框架，聚焦交换 hard-instance-oriented 特征，动态加权融合 | 解决现有 CP 方法优化车辆检测指标在 pedestrian 等 small safety-critical 对象表现不佳问题 | 自动驾驶协作感知 |
| 33 | http://arxiv.org/abs/2512.14079v1 | Grammar Search for Multi-Agent Systems | 提出结构化框架通过 fixed 简单 composable 组件探索空间，优于 free-form 搜索 | 解决 automatic search  for  MAS 依赖 LLM-based  free-form 搜索 code  space 问题 | 多代理系统自动搜索 |
| 34 | http://arxiv.org/abs/2512.15310v1 | SynthSeg-Agents: Multi-Agent Synthetic Data Generation for Zero-Shot Weakly Supervised Semantic Segmentation | 双智能体框架生成合成训练数据，无需真实图像 | 弱监督分割依赖真实样本，生成模型 augmentation 有限 | 零样本弱监督语义分割 |
| 35 | http://arxiv.org/abs/2601.08839v1 | Recursive Knowledge Synthesis for Multi-LLM Systems: Stability Analysis and Tri-Agent Audit Framework | 三智能体交叉验证框架，实现递归知识合成 (RKS) | 多模型 LLM 系统稳定性与可解释性不足 | 公共部署的多 LLM 系统 |
| 36 | http://arxiv.org/abs/2512.16167v2 | Ev-Trust: An Evolutionary Stable Trust Mechanism for Decentralized LLM-Based Multi-Agent Service Economies | 基于进化博弈论的信任机制，将可信度转化为生存优势 | 自利智能体欺骗行为导致系统性信任崩溃 | 去中心化 LLM 多智能体服务经济 |
| 37 | http://arxiv.org/abs/2512.16325v1 | QUIDS: Quality-informed Incentive-driven Multi-agent Dispatching System for Mobile Crowdsensing | 质量感知激励驱动调度，优化感知覆盖与可靠性 | 非专用车辆众包 sensing 质量与动态参与难保障 | 移动众包感知系统 |
| 38 | http://arxiv.org/abs/2512.16465v2 | cuPilot: A Strategy-Coordinated Multi-agent Framework for CUDA Kernel Evolution | 策略协调多智能体框架，引入策略作为中间语义表示 | 现有自动 kernel 优化方法性能不足，agent 设计次优 | CUDA 内核自动优化与演化 |
| 39 | http://arxiv.org/abs/2512.16698v1 | Do Multi-Agents Solve Better Than Single? Evaluating Agentic Frameworks for Diagram-Grounded Geometry Problem Solving and Reasoning | 系统评估单代理与多代理在几何解题上的性能差异 | 多代理设计在视觉数学任务中的效益不明确 | 视觉数学推理任务 |
| 40 | http://arxiv.org/abs/2512.18094v1 | Rethinking Multi-Agent Intelligence Through the Lens of Small-World Networks | 将小世界网络拓扑作为多代理系统设计先验 | 现有 LLM 多代理系统通信拓扑缺乏结构指导 | 多代理辩论与协作 |
| 41 | http://arxiv.org/abs/2512.21352v1 | Multi-Agent LLM Committees for Autonomous Software Beta Testing | 提出多代理委员会框架，通过投票协议达成共识 | 单代理测试存在幻觉与行为不一致 | 软件 Beta 测试 |
| 42 | http://arxiv.org/abs/2512.22336v1 | Agent2World: Learning to Generate Symbolic World Models via Adaptive Multi-Agent Feedback | 三阶段多Agent框架，通过自适应反馈生成符号世界模型 | LLM生成世界模型缺乏大规模可验证监督 | PDDL规划域与可执行模拟器生成 |
| 43 | http://arxiv.org/abs/2512.22536v1 | CoAgent: Collaborative Planning and Consistency Agent for Coherent Video Generation | 计划-合成-验证流水线保持视频叙事连贯性 | 文本到视频生成中身份漂移、场景不一致 | 长形式视频生成 |
| 44 | http://arxiv.org/abs/2512.23300v1 | AI4Reading: Chinese Audiobook Interpretation System Based on Multi-Agent Collaboration | 11专业Agent协作生成播客式有声书解读 | 有声书解读手动创建耗时耗力 | 中文有声书解读系统 |
| 45 | http://arxiv.org/abs/2512.23320v1 | Multi Agents Semantic Emotion Aligned Music to Image Generation with Music Derived Captions | 多Agent协作细化音乐描述并强制语义情感对齐 | 音乐触发视觉意象外部化困难 | 音乐条件图像生成 |
| 46 | http://arxiv.org/abs/2512.18622v1 | A Multi-agent Text2SQL Framework using Small Language Models and Execution Feedback | 提出 MATS 框架，利用多智能体机制分配角色，基于执行反馈的 RL 对齐小模型。 | 解决小模型在 Text2SQL 任务中泛化能力不足及隐私成本问题。 | 本地部署的小模型 Text2SQL 场景 |
| 47 | http://arxiv.org/abs/2512.19841v1 | A Multi-Agent Retrieval-Augmented Framework for Work-in-Progress Predictio | 提出检索增强的多智能体框架，结合 RAG 与协作推理进行 WiP 预测。 | 解决结构化事件日志语义丰富度不足及预测鲁棒性问题。 | 预测性过程监控与工作进度预测 |
| 48 | http://arxiv.org/abs/2512.20688v1 | Mechanism-Based Intelligence (MBI): Differentiable Incentives for Rational Coordination and Guaranteed Alignment in Multi-Agent Systems | 引入 MBI 范式，利用可微价格机制计算动态激励信号保证对齐。 | 解决多智能体系统协调计算不可行及激励对齐问题。 | 多智能体系统的理性协调与全局对齐 |
| 49 | http://arxiv.org/abs/2512.20184v1 | Reaching Agreement Among Reasoning LLM Agents | 提出 Aegean 共识协议，解决多智能体细化问题，实现增量法定人数检测。 | 解决现有编排依赖静态启发式工作流浪费资源及延迟高问题。 | 多智能体推理系统中的共识达成 |
| 50 | http://arxiv.org/abs/2512.20618v1 | LongVideoAgent: Multi-Agent Reasoning with Long Videos | 提出多智能体框架，主 LLM 协调接地代理与视觉代理处理长视频。 | 解决现有方法压缩内容为有损摘要或依赖有限工具集问题。 | 长视频问答中的多模态推理任务 |
| 51 | http://arxiv.org/abs/2512.20845v1 | MAR:Multi-Agent Reflexion Improves Reasoning Abilities in LLMs | 引入多智能体多人格辩论者生成反思，避免单 LLM 自我反思退化。 | 解决同一 LLM 持续反思导致思维退化重复错误的问题。 | LLM 推理能力的反思改进 |
| 52 | http://arxiv.org/abs/2512.20936v1 | Reasoning-Driven Amodal Completion: Collaborative Agents and Perceptual Evaluation | 提出协作多智能体推理框架，解耦语义规划与视觉合成。 | 解决不可见部分推断中的语义一致性与结构完整性问题。 | 视觉补全任务 |
| 53 | http://arxiv.org/abs/2512.20973v1 | DAO-Agent: Zero Knowledge-Verified Incentives for Decentralized Multi-Agent Coordination | 集成 DAO 治理与零知识证明，实现去中心化激励验证。 | 解决信任less 环境中贡献测量与激励分配难题。 | 去中心化协作系统 |
| 54 | http://arxiv.org/abs/2512.21431v1 | Cerberus: Multi-Agent Reasoning and Coverage-Guided Exploration for Static Detection of Runtime Errors | LLM 生成输入触发错误，无需执行进行覆盖率预测。 | 解决代码片段集成前运行时错误检测难题。 | 静态代码分析 |
| 55 | http://arxiv.org/abs/2512.21481v1 | The AI Committee: A Multi-Agent Framework for Automated Validation and Remediation of Web-Sourced Data | 模型无关多智能体系统，自动化验证与修复网络数据。 | 解决网络数据采集中的幻觉、遗漏与语义误读。 | 研究数据集构建 |
| 56 | http://arxiv.org/abs/2512.21623v1 | Democratizing Drug Discovery with an Orchestrated, Knowledge-Driven Multi-Agent Team for User-Guided Therapeutic Design | 编排生物、化学、药理智能体，统一自主发现引擎。 | 解决治疗发现中领域碎片化与执行差距问题。 | 药物研发 |
| 57 | http://arxiv.org/abs/2512.21794v2 | Multi-agent Adaptive Mechanism Design | 分布鲁棒自适应机制，联合解决真实性与成本最优。 | 解决无先验知识下多智能体真实报告 elicitation 问题。 | 机制设计与博弈 |
| 58 | http://arxiv.org/abs/2601.11578v2 | Multi-Agent LLMs for Generating Research Limitations | 多角色代理协作提取显式与隐性研究局限性 | 解决零样本LLM生成局限性 superficial 问题 | 科学研究评估 |
| 59 | http://arxiv.org/abs/2512.24613v1 | Group Deliberation Oriented Multi-Agent Conversational Model for Complex Reasoning | 三级角色分工架构，生成验证整合推理结论 | 解决单LLM在复杂推理任务中能力局限问题 | 复杂推理任务 |
| 60 | http://arxiv.org/abs/2512.24754v1 | AstroReview: An LLM-driven Multi-Agent Framework for Telescope Proposal Peer Review and Refinement | 三阶段代理框架自动化望远镜提案同行评审 | 解决提案量大导致评审瓶颈及公平性问题 | 天文学提案评审 |
| 61 | http://arxiv.org/abs/2512.25015v1 | MAMA-Memeia! Multi-Aspect Multi-Agent Collaboration for Depressive Symptoms Identification in Memes | 基于认知分析疗法的多方面多代理讨论框架 | 解决 memes 中抑郁症状识别及多模态理解问题 | 社交媒体心理健康 |

[返回目录](#目录)

<a id="cat-10"></a>

## 人机协作Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2512.02329v1 | Towards autonomous normative multi-agent systems for Human-AI software engineering teams | 规范驱动的多Agent系统，用道义模态 regulating 人机协作 | 软件开发需超越当前流程的速度、可靠性、适应性 | 人机软件工程团队 |
| 2 | http://arxiv.org/abs/2512.02589v2 | PaperDebugger: A Plugin-Based Multi-Agent System for In-Editor Academic Writing, Review, and Editing | PaperDebugger编辑器内多Agent插件，Kubernetes编排+MCP工具链 | 现有助手外置于编辑器，无法深度交互文档状态结构历史 | 学术写作/LaTeX编辑 |
| 3 | http://arxiv.org/abs/2512.03262v2 | Is Vibe Coding Safe? Benchmarking Vulnerability of Agent-Generated Code in Real-World Tasks | SUSVIBES基准200任务，评估Agent生成代码安全性 | Vibe Coding输出安全性未知 | 软件工程任务 |
| 4 | http://arxiv.org/abs/2512.04367v1 | AgentBay: A Hybrid Interaction Sandbox for Seamless Human-AI Intervention in Agentic Systems | 混合控制接口+自适应流协议ASP，AI/人工无缝切换 | 现实异常下Agent脆弱需HITL监督 | 任务关键Agent系统 |
| 5 | http://arxiv.org/abs/2512.09511v2 | Exploring Community-Powered Conversational Agent for Health Knowledge Acquisition | CanAnswer对话Agent整合社区内容，促进年轻人健康知识获取 | 在线社区内容碎片化、质量参差、术语陌生，学习健康知困难 | 结直肠癌等健康知识获取与学习 |
| 6 | http://arxiv.org/abs/2512.07474v1 | Living the Novel: A System for Generating Self-Training Timeline-Aware Conversational Agents from Novels | 两阶段训练 pipeline，深度角色对齐及故事时间感知知识图谱约束。 | 通用 LLM 角色漂移及能力超出故事世界约束导致叙事不连贯。 | 叙事系统/ conversational agents |
| 7 | http://arxiv.org/abs/2512.10918v2 | CompanionCast: Toward Social Collaboration with Multi-Agent Systems in Shared Experiences | 编排多专用智能体作为社交协作者，增强共享体验存在感 | 现有系统缺乏社交意识与多方互动，难以复制群体动态 | 体育观看等共享媒体体验社交协作 |
| 8 | http://arxiv.org/abs/2512.11276v3 | Words to Describe What I'm Feeling: Exploring the Potential of AI Agents for High Subjectivity Decisions in Advance Care Planning | 智能体作为个人倡导者，随时间建立相互理解 | 丧失决策能力时个人价值观难以在预立医疗计划中代表 | 预立医疗计划（ACP）高主观性决策支持 |
| 9 | http://arxiv.org/abs/2512.11979v1 | Designing The Internet of Agents: A Framework for Trustworthy, Transparent, and Collaborative Human-Agent Interaction (HAX) | HAX 框架整合行为启发式与 SDK，重构多智能体系统为同事 | 生成式自主智能体兴起需重构人机协作信任与透明基础 | 可信透明的人机协作交互设计 |
| 10 | http://arxiv.org/abs/2512.19707v2 | Bidirectional human-AI collaboration in brain tumour assessments improves both expert human and AI agent performance | 揭示人机partnership 双向提升准确性与元认知能力，AI 支持人类亦受益 | 解决医疗评估中单一智能体性能瓶颈，最大化 AI 医疗价值 | 脑肿瘤医疗评估 |
| 11 | http://arxiv.org/abs/2512.12719v1 | Towards AI Agents Supported Research Problem Formulation | 探索 AI 代理支持 SE 研究人员早期研究问题 formulation，预填属性对齐视角 | 解决研究问题 formulaton  poorly 导致实际相关性 compromised 问题 | 软件工程研究立项 |
| 12 | http://arxiv.org/abs/2512.14012v1 | Professional Software Developers Don't Vibe, They Control: AI Agent Use for Coding in 2025 | 调查经验开发者使用代理动机策略，发现保留 agency 控制代理行为 leveraging  expertise | 解决 agents 在 professional software 开发中 roles  remains in  question 问题 | 专业软件开发协作 |
| 13 | http://arxiv.org/abs/2512.15343v1 | Exploring User Acceptance and Concerns toward LLM-powered Conversational Agents in Immersive Extended Reality | 大规模众包研究 XR 中 LLM 对话智能体的用户接受度与隐私担忧 | 用户易披露敏感信息，缺乏以用户为中心的理解 | 沉浸式扩展现实中的对话智能体 |
| 14 | http://arxiv.org/abs/2512.22496v1 | Hierarchical Pedagogical Oversight: A Multi-Agent Adversarial Framework for Reliable AI Tutoring | 五幕辩论式对抗多Agent框架进行教学监督 | AI导师易认可错误答案或直接给出答案 | 中学数学辅导对话评估 |
| 15 | http://arxiv.org/abs/2512.22790v1 | ChatGraPhT: A Visual Conversation Interface for Multi-Path Reflection with Agentic LLM Support | 节点链接可视化界面支持分支合并与反思 | 线性对话界面限制复杂知识工作中的反思 | 复杂开放式任务中的反思性对话 |
| 16 | http://arxiv.org/abs/2512.23372v1 | A Design Space for Intelligent Agents in Mixed-Initiative Visual Analytics | 六维度设计空间表征Agent感知/理解/行动/通信 | 混合主动VA系统中智能Agent设计原则理解有限 | 混合主动视觉分析系统 |
| 17 | http://arxiv.org/abs/2601.09715v1 | Introducing Axlerod: An LLM-based Chatbot for Assisting Independent Insurance Agents | NLP 与 RAG 结合，解析意图并访问结构化保单数据库。 | 提高独立保险代理人的操作效率与响应速度。 | 保险行业 |
| 18 | http://arxiv.org/abs/2512.23844v1 | From Correctness to Collaboration: Toward a Human-Centered Framework for Evaluating AI Agent Behavior in Software Engineering | 提出以人为本的Agent行为评估分类与上下文适应框架 | 解决现有基准忽略人机协作 nuanced 行为问题 | 企业软件工程 |
| 19 | http://arxiv.org/abs/2602.15831v1 | A2H: Agent-to-Human Protocol for AI Agent | 统一协议使人类作为可解析实体被代理发现与通信 | 解决现有协议忽略人类作为系统内集成参与者问题 | 人机交互基础设施 |
| 20 | http://arxiv.org/abs/2601.00121v1 | Ask, Clarify, Optimize: Human-LLM Agent Collaboration for Smarter Inventory Control | 混合框架解耦语义推理与数学计算，引入人类模仿者 | 解决LLM直接求解库存优化存在幻觉税问题 | 库存控制管理 |

[返回目录](#目录)

<a id="cat-11"></a>

## Agent可解释性与透明度

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2512.02393v2 | Process-Centric Analysis of Agentic Software Systems | Graphectory编码时序语义关系，实时监测干预提升解决率6.9%-23.5% | 现有评估只关注结果，无法解释Agent如何推理规划行动 | SWE-agent/OpenHands工作流 |
| 2 | http://arxiv.org/abs/2512.12597v1 | AgentSHAP: Interpreting LLM Agent Tool Importance with Monte Carlo Shapley Value Estimation | 首个基于蒙特卡洛 Shapley 值解释 LLM 代理工具重要性的框架 | 解决现有 XAI 方法无法解释代理工具贡献的盲点问题 | LLM 代理工具调用 |
| 3 | http://arxiv.org/abs/2512.17896v2 | XAgen: An Explainability Tool for Identifying and Correcting Failures in Multi-Agent Workflows | 设计 XAgen 工具，支持日志可视化与错误检测 | 多代理工作流失败原因不透明难调试 | 多代理工作流开发 |
| 4 | http://arxiv.org/abs/2512.21066v3 | Agentic Explainable Artificial Intelligence (Agentic XAI) Approach To Explore Better Explanation | 结合 SHAP 与多模态 LLM 迭代优化，生成增强解释。 | 解决技术解释难以向 laypersons 传达信任的问题。 | 农业推荐系统 |
| 5 | http://arxiv.org/abs/2512.21699v1 | Towards Responsible and Explainable AI Agents with Consensus-Driven Reasoning | 多模型共识与推理层治理，生成可审计决策。 | 解决自主系统决策理由不透明与责任缺失问题。 | 生产级智能体工作流 |
| 6 | http://arxiv.org/abs/2601.06064v1 | Socio-technical aspects of Agentic AI | 社会技术分析，连接核心组件与社会背景。 | 解决 Agentic AI 社会伦理与治理整合薄弱问题。 | 社会影响与治理 |

[返回目录](#目录)

<a id="cat-12"></a>

## Agent规划与推理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2512.02395v2 | Skywork-R1V4: Toward Agentic Multimodal Intelligence through Interleaved Thinking with Images and DeepResearch | 30B多模态Agent，图像操作与网络搜索交织推理，仅SFT训练 | 现有多模态Agent将图像与搜索割裂，依赖昂贵RL | 复杂多步多模态任务 |
| 2 | http://arxiv.org/abs/2512.03500v1 | EEA: Exploration-Exploitation Agent for Long Video Understanding | 语义引导分层树搜索，平衡探索利用 | 长视频理解计算开销和信息覆盖不全 | 长视频理解 |
| 3 | http://arxiv.org/abs/2512.08366v2 | Reflecting with Two Voices: A Co-Adaptive Dual-Strategy Framework for LLM-Based Agent Decision Making | DuSAR双策略框架，高层全局计划与局部策略通过反思机制协同 | LLM Agent依赖外部演示导致泛化差、计算开销高 | 家庭模拟和真实Web环境任务执行 |
| 4 | http://arxiv.org/abs/2512.08511v2 | Thinking with Images via Self-Calling Agent | sCoT将多模态CoT重构为语言-only CoT与自调用，主Agent调用参数共享子Agent | 多模态CoT通过强化学习优化依赖稀缺高质量推理数据 | 视觉推理任务与多模态理解 |
| 5 | http://arxiv.org/abs/2512.09629v1 | An End-to-end Planning Framework with Agentic LLMs and PDDL | 端到端规划框架，LLM将自然语言转换为PDDL模型，子模块迭代优化 | LLM在规划任务中难以处理时间约束、最优性及人类规范中的歧义 | 通用规划任务如Blocksworld和汉诺塔 |
| 6 | http://arxiv.org/abs/2512.07898v1 | MARINE: Theoretical Optimization and Design for Multi-Agent Recursive IN-context Enhancement | 多 Agent 递归上下文增强，将 pass@N 转为 pass@1 | 实际约束限制输出为单响应，未实现性能潜力 | 测试时推理增强 |
| 7 | http://arxiv.org/abs/2512.10534v3 | Achieving Olympia-Level Geometry Large Language Model Agent via Complexity Boosting Reinforcement Learning | 引入复杂度提升强化学习，迭代提出辅助构造并验证 | 几何问题启发式弱，依赖大规模数据合成与搜索 | 国际数学奥林匹克几何问题求解 |
| 8 | http://arxiv.org/abs/2512.10739v2 | Long-horizon Reasoning Agent for Olympiad-Level Mathematical Problem Solving | 多轮分层推理智能体，维护引理记忆突破上下文约束 | 超难数学问题推理复杂度超出单轮上下文探索空间 | 国际数学奥林匹克非几何问题求解 |
| 9 | http://arxiv.org/abs/2512.12692v1 | WebOperator: Action-Aware Tree Search for Autonomous Agents in Web Environment | 引入动作感知树搜索框架，支持可靠回溯与战略探索，防止意外副作用 | 解决 Web 环境中代理缺乏远见、难以纠正错误或系统探索替代路径问题 | 自主 Web 操作代理 |
| 10 | http://arxiv.org/abs/2512.14766v1 | GR-Agent: Adaptive Graph Reasoning Agent under Incomplete Knowledge | 构建交互式环境形式化 KGQA 为代理环境交互，维护潜在支持推理证据记忆 | 解决现有方法假设 complete  KGs 忽略 reality  of  incomplete  KGs 限制 reasoning 问题 | 知识图谱问答代理 |
| 11 | http://arxiv.org/abs/2512.14474v1 | Model-First Reasoning LLM Agents: Reducing Hallucinations through Explicit Problem Modeling | 两阶段范式：先构建显式问题模型再生成计划 | LLM 复杂规划任务中约束违反率高、幻觉多 | 多步规划与资源分配任务 |
| 12 | http://arxiv.org/abs/2512.20362v2 | CRAFT: Continuous Reasoning and Agentic Feedback Tuning for Multimodal Text-to-Image Generation | 引入 CRAFT 框架，将提示转化为显式视觉约束集并进行针对性更新。 | 解决现有方法依赖隐式整体批评导致行为难解释控制问题。 | 多模态文本到图像生成的推理优化 |
| 13 | http://arxiv.org/abs/2512.20458v2 | Laser: Governing Long-Horizon Agentic Search via Structured Protocol and Context Register | 引入 Laser 框架，定义符号动作协议组织代理行为并维护紧凑上下文寄存器。 | 解决现有框架依赖非结构化推理导致轨迹不稳定及上下文溢出问题。 | 长程智能体搜索任务的稳定与扩展 |
| 14 | http://arxiv.org/abs/2512.20745v3 | AgentMath: Empowering Mathematical Reasoning for Large Language Models via Tool-Augmented Agent | 提出 AgentMath 框架，无缝集成 LLM 推理与代码解释器计算精度。 | 解决 LRMs 计算效率低及解决复杂数学运算准确性不足问题。 | 复杂数学竞赛问题的自动求解 |
| 15 | http://arxiv.org/abs/2512.21309v2 | A Plan Reuse Mechanism for LLM-Driven Agent | 利用意图分类评估请求相似性，实现计划复用。 | 降低 LLM 驱动智能体生成计划的延迟。 | 个人助理/IoT 管理 |
| 16 | http://arxiv.org/abs/2512.24329v1 | World model inspired sarcasm reasoning with large language model agents | 分解语义不一致与意图评分，量化讽刺检测 | 解决黑盒模型难以解释讽刺认知因素问题 | 自然语言处理 |
| 17 | http://arxiv.org/abs/2512.24330v2 | SenseNova-MARS: Empowering Multimodal Agentic Reasoning and Search via Reinforcement Learning | 动态整合图像/文本搜索工具，增强多模态推理 | 解决VLM工具调用与连续推理 interleaving 能力不足问题 | 视觉问答与搜索 |
| 18 | http://arxiv.org/abs/2512.24957v2 | AMAP Agentic Planning Technical Report | 时空理解代理，支持异步 rollout 与级联训练 | 解决约束性兴趣点发现与行程规划复杂任务问题 | 时空任务规划 |

[返回目录](#目录)

<a id="cat-13"></a>

## Agent记忆与知识管理

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2512.02425v1 | WorldMM: Dynamic Multimodal Memory Agent for Long Video Reasoning | WorldMM三种记忆（情景/语义/视觉），自适应检索多时间粒度 | 长视频理解受限于上下文容量，文本摘要丢失视觉细节 | 长视频问答推理 |
| 2 | http://arxiv.org/abs/2512.03627v1 | MemVerse: Multimodal Memory for Lifelong Learning Agents | 分层检索记忆+周期性蒸馏，支持持续巩固和自适应遗忘 | Agent无法记忆导致灾难性遗忘 | 终身学习Agent |
| 3 | http://arxiv.org/abs/2512.11907v1 | Structured Personalization: Modeling Constraints as Matroids for Data-Minimal LLM Agents | 将用户知识图约束编译为宏观面，证明层次和配额约束形成有效层状拟阵 | 个性化需在任务效用和数据披露间权衡，现实约束违反标准子集选择假设 | LLM Agent个性化与数据最小化 |
| 4 | http://arxiv.org/abs/2512.05470v1 | Everything is Context: Agentic File System Abstraction for Context Engineering | 文件系统中抽象用于上下文工程，统一管理异构上下文 | 现有实践碎片化，限制可追溯性与问责制 | 上下文工程管理 |
| 5 | http://arxiv.org/abs/2512.06688v1 | PersonaMem-v2: Towards Personalized Intelligence via Learning Implicit User Personas and Agentic Memory | 训练代理记忆系统维护单一可读记忆，随用户增长，减少输入 token。 | 前沿 LLM 在隐式个性化任务中推理能力不足，长上下文效率低。 | 个性化智能/聊天机器人 |
| 6 | http://arxiv.org/abs/2512.07287v2 | Experience-Evolving Multi-Turn Tool-Use Agent with Hybrid Episodic-Procedural Memory | 混合情景 - 程序记忆策略，自适应重用部分重叠成功经验进化策略。 | 多轮代理面临决策上下文 shifting，全轨迹太具体工具级 reuse 忽略上下文。 | 多轮工具使用任务 |
| 7 | http://arxiv.org/abs/2512.10371v1 | AgentProg: Empowering Long-Horizon GUI Agents with Program-Guided Context Management | 将交互历史重构为程序结构，指导上下文保留与丢弃 | 长程 GUI 任务中交互历史膨胀导致上下文开销过大 | 移动端 GUI 长程任务自动化 |
| 8 | http://arxiv.org/abs/2512.10696v1 | Remember Me, Refine Me: A Dynamic Procedural Memory Framework for Experience-Driven Agent Evolution | 提出动态程序记忆框架，支持经验蒸馏、自适应复用与效用优化 | 现有记忆框架被动积累，缺乏动态推理与自我进化机制 | 经验驱动的智能体终身学习与进化 |
| 9 | http://arxiv.org/abs/2601.06037v4 | TeleMem: Building Long-Term and Multimodal Memory for Agentic AI | 统一长期多模态记忆系统，叙事动态提取与结构化写入 | RAG 缺乏可靠更新机制，导致幻觉、低效及多模态支持弱 | 智能体长期交互与多模态上下文理解 |
| 10 | http://arxiv.org/abs/2512.12686v1 | Memoria: A Scalable Agentic Memory Framework for Personalized Conversational AI | 集成动态会话摘要与加权知识图谱用户建模引擎，实现持久化记忆 | 解决 LLM 在扩展用户交互中缺乏连续性、个性化和长期上下文问题 | 个性化对话 AI 系统 |
| 11 | http://arxiv.org/abs/2512.12818v1 | Hindsight is 20/20: Building Agent Memory that Retains, Recalls, and Reflects | 将代理记忆视为结构化推理基底，组织为四个逻辑网络支持保留召回反思 | 解决当前记忆系统混淆证据与推断、难以组织长程信息及解释推理问题 | 长程对话记忆系统 |
| 12 | http://arxiv.org/abs/2512.12856v1 | Forgetful but Faithful: A Cognitive Memory Architecture and Benchmark for Privacy-Aware Generative Agents | 提出记忆感知保留 schema 及六种遗忘策略，平衡性能隐私与计算效率 | 解决生成式代理长期交互中记忆管理成为性能与隐私瓶颈问题 | 隐私敏感生成代理 |
| 13 | http://arxiv.org/abs/2512.13564v2 | Memory in the Age of AI Agents | 提供代理记忆研究最新景观，从形式功能动态统一视角审视代理记忆 | 解决代理记忆研究领域碎片化及术语定义 loosely  obscuring 概念清晰度问题 | 代理记忆研究综述 |
| 14 | http://arxiv.org/abs/2512.15813v1 | CodeMem: Architecting Reproducible Agents via Dynamic MCP and Procedural Memory | 通过代码实现程序性记忆，构建可重用确定性工作流 | 工具使用智能体动作空间有限、概率不稳定 | 重复性任务的可靠智能体工作流 |
| 15 | http://arxiv.org/abs/2512.23343v1 | AI Meets Brain: Memory Systems from Cognitive Neuroscience to Autonomous Agents | 系统综合认知神经科学与LLM Agent记忆知识 | 跨学科壁垒导致现有工作难吸收人类记忆机制精髓 | 自主Agent记忆系统设计 |
| 16 | http://arxiv.org/abs/2512.18746v1 | MemEvolve: Meta-Evolution of Agent Memory Systems | 提出元进化框架，共同进化代理的经验知识及其记忆架构。 | 解决记忆系统架构静态无法适应多样任务上下文的问题。 | 自进化智能体系统的记忆优化 |
| 17 | http://arxiv.org/abs/2512.18950v1 | Learning Hierarchical Procedural Memory for LLM Agents through Bayesian Selection and Contrastive Refinement | 提出 MACLA 框架，通过贝叶斯选择和对比细化维护外部层次过程记忆。 | 解决 LLM 参数更新成本高及样本效率低的问题。 | 无需更新 LLM 参数的持续改进代理 |
| 18 | http://arxiv.org/abs/2512.19396v1 | EchoTrail-GUI: Building Actionable Memory for GUI Agents via Critic-Guided Self-Exploration | 引入 EchoTrail-GUI，通过批评引导的自探索构建动态可访问记忆。 | 解决 GUI 代理缺乏机制从过去成功中系统学习的问题。 | 图形用户界面自动化任务 |
| 19 | http://arxiv.org/abs/2512.20092v1 | Memory-T1: Reinforcement Learning for Temporal Reasoning in Multi-session Agents | 引入 Memory-T1，利用 RL 学习时间感知记忆选择策略。 | 解决长对话历史积累噪声导致当前模型难以识别时间相关信息问题。 | 多会话对话中的时间推理任务 |
| 20 | http://arxiv.org/abs/2512.20237v1 | MemR$^3$: Memory Retrieval via Reflective Reasoning for LLM Agents | 构建 MemR^3 系统，包含路由器和全局证据缺口追踪器实现闭环控制。 | 解决现有记忆系统主要优化压缩存储而忽视检索显式控制问题。 | LLM 代理的记忆检索与推理优化 |
| 21 | http://arxiv.org/abs/2512.20884v1 | The Silent Scholar Problem: A Probabilistic Framework for Breaking Epistemic Asymmetry in LLM Agents | 提出概率框架，建模代理信念为 Beta-Bernoulli 分布驱动双向知识交换。 | 解决自主代理单向消费内容导致冗余推理及集体智慧停滞问题。 | LLM 代理间的知识交换与不确定性管理 |
| 22 | http://arxiv.org/abs/2512.21567v1 | Beyond Heuristics: A Decision-Theoretic Framework for Agent Memory Management | 决策理论框架，分解即时访问与分层存储维护。 | 解决启发式记忆管理缺乏长期效用洞察问题。 | LLM 系统记忆管理 |
| 23 | http://arxiv.org/abs/2512.22087v1 | Context as a Tool: Context Management for Long-Horizon SWE-Agents | 上下文管理作为 callable 工具，主动压缩历史轨迹。 | 解决长程交互中上下文爆炸与语义漂移问题。 | 软件工程智能体 |

[返回目录](#目录)

<a id="cat-14"></a>

## 具身智能Agent

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2512.02631v1 | SeeNav-Agent: Enhancing Vision-Language Navigation with Visual Prompt and Step-Level Policy Optimization | 双视图视觉提示+步级强化微调SRGPO | VLN Agent感知/推理/规划错误 | 视觉语言导航任务 |
| 2 | http://arxiv.org/abs/2512.04221v2 | MoReGen: Multi-Agent Motion-Reasoning Engine for Code-based Text-to-Video Synthesis | 多Agent LLM+物理模拟器+渲染器生成物理准确视频 | T2V生成缺乏物理有效性 | 文本到视频合成 |
| 3 | http://arxiv.org/abs/2512.08629v1 | See-Control: A Multimodal Agent Framework for Smartphone Interaction with a Robotic Arm | 通过低自由度机械臂直接物理交互操作手机，平台无关解决方案 | 现有方法依赖ADB仅限Android设备，无法跨平台操作 | 家庭机器人与智能手机交互任务 |
| 4 | http://arxiv.org/abs/2512.04770v2 | Embodied Co-Design for Rapidly Evolving Agents: Taxonomy, Frontiers, and Challenges | 系统综述具身协同设计，提出分层分类法 | 缺乏对形态与控制器联合优化的系统概述 | 虚拟与物理机器人 |
| 5 | http://arxiv.org/abs/2512.04797v1 | SIMA 2: A Generalist Embodied Agent for Virtual Worlds | 通用具身 Agent，理解并在 3D 虚拟世界行动 | prior work 限于简单指令，缺乏复杂交互 | 虚拟世界游戏 |
| 6 | http://arxiv.org/abs/2512.06721v1 | ProAgent: Harnessing On-Demand Sensory Contexts for Proactive LLM Agent Systems | 采用按需分层感知持续 sensing 环境，上下文感知推理器映射用户需求。 | 现有 LLM 智能体主要遵循被动范式，依赖显式指令增加用户负荷。 | 增强现实/主动助手 |
| 7 | http://arxiv.org/abs/2512.07410v2 | InterAgent: Physics-based Multi-agent Command Execution via Diffusion on Interaction Graphs | 自回归扩散变压器解耦本体/外感/动作，交互图捕捉细粒度空间依赖。 | 现有人形代理方法局限于单智能体，忽略多智能体物理合理交互。 | 人形机器人/多智能体控制 |
| 8 | http://arxiv.org/abs/2512.10605v1 | LEO-RobotAgent: A General-purpose Robotic Agent for Language-driven Embodied Operator | 通用语言驱动智能体框架，支持多类型机器人跨场景任务 | 现有研究聚焦单任务单机器人，缺乏泛化性与通用结构 | 无人机、机械臂等多平台机器人任务 |
| 9 | http://arxiv.org/abs/2512.11584v1 | Atomic Action Slicing: Planner-Aligned Options for Generalist VLA Agents | 将长程演示分解为短原子动作，提升规划器与策略学习效果 | 视觉 - 语言 - 动作模型泛化差，新技能组合任务表现不佳 | 通用视觉 - 语言 - 动作（VLA）机器人策略 |
| 10 | http://arxiv.org/abs/2512.15776v1 | Emergence: Overcoming Privileged Information Bias in Asymmetric Embodied Agents via Active Querying | 提出基于主动查询的不对称辅助推理框架，减少沟通接地错误 | 解决知识者代理因缺乏心理理论无法引导传感器受限代理问题 | embodied AI 协作场景 |
| 11 | http://arxiv.org/abs/2512.13262v1 | Post-Training and Test-Time Scaling of Generative Agent Behavior Models for Interactive Autonomous Driving | 提出群相对行为优化及 Warm-K 采样策略，提升安全性保持行为真实 | 解决模仿学习模型继承数据集偏差及开环评估忽略闭环误差问题 | 交互式自动驾驶 |
| 12 | http://arxiv.org/abs/2512.14234v1 | ViBES: A Conversational Agent with Behaviorally-Intelligent 3D Virtual Body | 提出 SLB 模型混合模态专家 backbone，联合规划语言与运动执行 dialogue-conditioned 动作 | 解决 prior  systems  model  human  behavior  as  translation  task 缺乏 agentic  decision-making 问题 | 3D 虚拟对话代理 |
| 13 | http://arxiv.org/abs/2512.14442v1 | A4-Agent: An Agentic Framework for Zero-Shot Affordance Reasoning | 三阶段 pipeline(Dreamer/Thinker/Spotter) 解耦 affordance 预测 | 端到端模型泛化差，依赖标注数据 | 具身 AI 交互区域预测 |
| 14 | http://arxiv.org/abs/2512.18571v1 | ESearch-R1: Learning Cost-Aware MLLM Agents for Interactive Embodied Search via Reinforcement Learning | 提出 ESearch-R1，统一交互式对话与物理导航 | 代理难以平衡物理探索与人类交互成本 | 具身搜索任务 |
| 15 | http://arxiv.org/abs/2512.19453v1 | MaP-AVR: A Meta-Action Planner for Agents Leveraging Vision Language Models and Retrieval-Augmented Generation | 提出元动作规划器，抽象规划结果为元动作集，结合 RAG 技术。 | 解决技能集泛化能力不足及 LLM 产生 desired 格式困难问题。 | 具身机器人日常复杂任务管理 |
| 16 | http://arxiv.org/abs/2512.21220v2 | RoboSafe: Safeguarding Embodied Agents via Executable Safety Logic | 混合长短时安全记忆，执行基于谓词的安全逻辑。 | 防御具身智能体在动态环境中的隐性风险指令。 | 物理机器人系统 |
| 17 | http://arxiv.org/abs/2512.24461v1 | Align While Search: Belief-Guided Exploratory Inference for World-Grounded Embodied Agents | 测试时自适应代理，通过信念细化进行探索推理 | 解决部分可观测环境下代理与潜在世界状态对齐问题 | 具身智能任务 |
| 18 | http://arxiv.org/abs/2512.24504v2 | Thinking on Maps: How Foundation Model Agents Explore, Remember, and Reason Map Environments | 交互式评估框架分析代理在符号地图环境的探索记忆推理 | 解决静态地图输入忽略空间理解交互性问题 | 地图环境推理 |

[返回目录](#目录)

<a id="cat-15"></a>

## 低代码/无代码Agent平台

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2512.09142v2 | SDialog: A Python Toolkit for End-to-End Agent Building, User Simulation, Dialog Generation, and Evaluation | 统一对话生成、评估和可解释性的端到端框架，支持多后端混合实验 | 缺乏统一的对话Agent构建、基准测试和理解工具 | 对话式Agent研究与开发 |

[返回目录](#目录)

<a id="cat-16"></a>

## 其他-Agent综述与研究进展

| 序号 | 论文网址 | 论文题目 | 核心创新 | 主要解决的问题 | 针对（应用场景/目标对象） |
|------|----------|----------|----------|----------------|--------------------------|
| 1 | http://arxiv.org/abs/2512.16301v3 | Adaptation of Agentic AI: A Survey of Post-Training, Memory, and Skills | 统一适应概念，梳理后训练、记忆与技能系统四大范式 | 研究领域碎片化，缺乏统一适应 notion | 智能体适应性与工具协同研究 |

[返回目录](#目录)
