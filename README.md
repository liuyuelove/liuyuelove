# 你好，我是刘越 👋 / Hi, I'm Liu Yue

> **构建企业级 LLM Agent 与 RAG 系统** · 华中师范大学 · 计算机技术硕士（2024–2027）
>
> 落地于两条赛道：**🤖 具身智能机器人 × 🚗 商用车智能驾驶**

## 🤖🚗 机器人 & 车企：双赛道 Agent 落地经验

<table>
<tr>
<td width="50%" valign="top">

<h3>🤖 具身智能 · 银行网点机器人</h3>
<p><strong>广电运通（GRG）· 算法开发部 · 算法实习生</strong><br/>2026.06 – 2026.10</p>
<ul>
<li>分层 Agent 工程架构：应用生命周期 / LangGraph 编排 / 业务规则 / Tool / Adapter / Prompt 与观测能力解耦，支持硬件与外部服务的统一接入、替换与测试</li>
<li>多模态交互链路：人脸 · ASR · 文本 · 数字人 · 机器人动作，融合向量检索 + Reranker 知识问答，串联取号排队与自助设备，支撑迎宾、咨询、办理与巡检闭环</li>
<li><strong>Robot State 状态机</strong>约束导航、巡检、迎宾、办理与会话复位全流程，结合 Prompt 与代码注册 Tool 实现业务识别、推荐与确认式办理</li>
<li>独立搭建 <strong>Agent 测评验证框架</strong>：回放数据集驱动执行，工具调用按名称与参数级匹配，输出准确率、失败分类与耗时报告，支持多模型对比</li>
</ul>

</td>
<td width="50%" valign="top">

<h3>🚗 智能驾驶 · 商用车主动安全</h3>
<p><strong>魔视智能（上海）· 端到端行车算法部 · 大模型应用开发实习生</strong><br/>2026.03 – 2026.06</p>
<ul>
<li>基于 LangGraph StateGraph 构建<strong>多 Agent 工作流引擎</strong>：后装算法迭代 Agent + 商用车安全问答 Agent，贯通数据下载 → 标注 → 训练 → 评估全流程</li>
<li>集成 <strong>Human-in-the-Loop</strong> 人工确认机制，保障行车安全场景下的关键决策可控</li>
<li>二次开发 <strong>Motovis-RAG 知识库引擎</strong>：支持 20+ 文档格式、Elasticsearch 向量检索 + Rerank 双阶段语义检索</li>
<li>提供 OpenAI 兼容 API，支持多 LLM 后端切换与异步任务队列</li>
</ul>

</td>
</tr>
</table>

## 💼 其他实战

| 时间 | 内容 |
| :--- | :--- |
| 2026.03 – 2026.05 | **飞书智能项目管理引擎**（独立开发）：Plugin + Tenant Access Token 双令牌权限体系，4.1W+ 全量工作项 15 并发拉取与分页降级；开发 Feishu-Project AgentSkill，将飞书项目 API 与高阶查询封装为自然语言指令，让通用 LLM 无需微调即可编排 API 调用链路 |
| 2024.09 – 至今 | 华中师范大学 · 硕士 · 计算机技术：研究生数学建模大赛国家三等奖；大创 A 级项目（基于 Apollo 无人驾驶技术服务系统） |

## 📄 论文

**Diff-Ensemble：基于扩散模型的迁移性与隐蔽性对抗攻击研究** — *Under Review, ACM (CCF-A)*

> 提出基于潜变量扩散模型 LDM 的生成式攻击框架，将对抗生成重构为有引导的降噪过程，干预 DDIM 采样轨迹并结合注意力正则化。ImageNet 黑盒攻击 SOTA：11 种目标模型平均攻击成功率 **88.77%**，FID 50.81，较 DiffAttack / AWT 等基线 ASR 相对提升 24.7%–39.7%。

## 🚀 精选项目

| 项目 | 说明 |
| :--- | :--- |
| 🤖 [robot-agent-runtime-docs](https://github.com/liuyuelove/robot-agent-runtime-docs) | 具身智能银行网点机器人大脑：Agent Runtime 设计文档与项目介绍 |
| 🚗 [aftermarket-perception-agent](https://github.com/liuyuelove/aftermarket-perception-agent) | 商用车后装算法迭代 Agent：数据下载→标注→训练→评估全流程工作流 |
| 🧩 LocalDev Agent（待上传 GitHub） | 多智能体协作框架：三层上下文压缩引擎、基于 DAG 的持久化任务管理器、多 Agent 异步协作协议与 Working/Idle 状态机，支持全链路可观测与断电恢复 |

## 🧰 技术栈

**Agent & LLM 应用**

![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/-LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![Ollama](https://img.shields.io/badge/-Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![RAGFlow](https://img.shields.io/badge/-RAGFlow-005571?style=flat-square)
![OpenClaw](https://img.shields.io/badge/-OpenClaw-FF6A00?style=flat-square)

**具身智能 & 机器人**：Robot State 状态机 · 多模态交互（人脸 / ASR / 数字人 / 机器人动作） · Agent 测评验证框架

**检索与数据**

![Elasticsearch](https://img.shields.io/badge/-Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![向量检索 + Rerank](https://img.shields.io/badge/-向量检索%20%2B%20Rerank-4479A1?style=flat-square)

**算法与部署**

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

`Transformer` `MoE` `GQA` `KV Cache` `LoRA / QLoRA` `SFT` `DPO` `模型量化` `推理加速` `云边端部署选型`

## 📊 GitHub 统计

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=liuyuelove&show_icons=true&locale=zh-cn" alt="GitHub stats" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=liuyuelove&layout=compact&locale=zh-cn" alt="Top languages" />
</p>

## 📫 联系我

[![Gmail](https://img.shields.io/badge/-liuzuizuishuai@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:liuzuizuishuai@gmail.com)

---

*如果我的项目对你有帮助，欢迎 Star 支持 ⭐*
