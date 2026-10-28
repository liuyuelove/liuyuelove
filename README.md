<div align="center">
  <img src="./assets/banner.png" alt="不努力日记 · 大学生歪脖 coding" width="100%" />
</div>

<div align="center">

### 你好，我是不努力日记 👋

大学生 · 歪脖 coding　|　在产线上写 Agent，在日记里记 Bug

</div>

- 🔭 **现在在做**：生产级 LLM Agent / RAG / 多智能体编排
- 🏭 **两段产线实战**：🤖 具身智能银行网点机器人（广电运通 GRG）× 🚗 商用车主动安全多 Agent 平台（魔视智能）
- 🧠 **正在做**：LocalDev Agent · 三层上下文压缩 · Human-in-the-Loop
- 📄 **一篇论文**：Diff-Ensemble，ACM CCF-A 在审

我关心的是：**Agent 怎么在真实业务里稳定地跑起来**——上下文怎么压缩、工具怎么评测、流程怎么恢复、人在什么位置介入。

> 不做 Demo 级 Agent，做能在产线上跑的 Agent。

---

## 🚀 精选项目

<table>
<tr>
<td width="50%" valign="top">

<h3>🤖 robot-agent-runtime-docs</h3>

<p>具身智能银行网点机器人的「大脑」：分层 Agent Runtime、Robot State 状态机与可回放的评测框架。</p>

<p>
<img src="https://img.shields.io/badge/LangGraph-4F5D2F?style=flat-square&logo=langgraph&logoColor=white" />
<img src="https://img.shields.io/badge/RAG-4F5D2F?style=flat-square" />
<img src="https://img.shields.io/badge/Robot%20State-1A2019?style=flat-square" />
</p>

<a href="https://github.com/liuyuelove/robot-agent-runtime-docs"><b>查看项目 →</b></a>

</td>
<td width="50%" valign="top">

<h3>🚗 aftermarket-perception-agent</h3>

<p>商用车后装算法迭代 Agent：把「数据下载 → 标注 → 训练 → 评估」串成一条可人工确认的自动化工作流。</p>

<p>
<img src="https://img.shields.io/badge/LangGraph-4F5D2F?style=flat-square&logo=langgraph&logoColor=white" />
<img src="https://img.shields.io/badge/Multi--Agent-5B7C8C?style=flat-square" />
<img src="https://img.shields.io/badge/HITL-1A2019?style=flat-square" />
</p>

<a href="https://github.com/liuyuelove/aftermarket-perception-agent"><b>查看项目 →</b></a>

</td>
</tr>
</table>

<h3>🧩 LocalDev Agent　<img src="https://img.shields.io/badge/Open%20Source-4F5D2F?style=flat-square&logo=github&logoColor=white" /></h3>

> 面向长任务的多 Agent 协作框架：三层上下文压缩、DAG 持久化任务、异步协作协议与 Working/Idle 状态机，支持全链路可观测与断电恢复。
>
> **一句话：Agent 跑得久，也跑得回来。**

<p>
<img src="https://img.shields.io/badge/Multi--Agent-4F5D2F?style=flat-square" />
<img src="https://img.shields.io/badge/DAG-5B7C8C?style=flat-square" />
<img src="https://img.shields.io/badge/Context%20Compression-1A2019?style=flat-square" />
<img src="https://img.shields.io/badge/Observability-6E6A60?style=flat-square" />
</p>

<a href="https://github.com/liuyuelove/localdev_agent"><b>查看项目 →</b></a>　<sub>如果对你有帮助，欢迎 Star ⭐</sub>

---

## 🏭 两段产线实战

<table>
<tr>
<td width="50%" valign="top">

<h3>🤖 具身智能银行网点机器人</h3>

<p><b>广电运通 GRG</b> · 算法开发<br/>
<sub>2026.06 – 2026.10</sub></p>

<ul>
<li>从 0 到 1 设计分层 Agent 架构：生命周期 / LangGraph 编排 / 业务规则 / Tool / Adapter / Prompt 解耦</li>
<li>打通人脸 · ASR · 数字人 · 机器人动作的多模态链路，支撑迎宾、咨询、办理、巡检闭环</li>
<li>自研 Agent 测评框架：回放驱动、工具调用参数级匹配、失败分类与多模型对比</li>
</ul>

</td>
<td width="50%" valign="top">

<h3>🚗 商用车主动安全多 Agent 平台</h3>

<p><b>魔视智能</b> · 大模型应用开发<br/>
<sub>2026.03 – 2026.06</sub></p>

<ul>
<li>基于 LangGraph StateGraph 构建多 Agent 工作流，贯通数据下载 → 标注 → 训练 → 评估全流程</li>
<li>集成 Human-in-the-Loop 人工确认，保障行车安全场景下的关键决策可控</li>
<li>二次开发 Motovis-RAG：20+ 文档格式、Elasticsearch 向量检索 + Rerank 双阶段召回、OpenAI 兼容 API</li>
</ul>

</td>
</tr>
</table>

---

## 🧰 技术栈

**Agent & LLM**

![LangChain](https://img.shields.io/badge/LangChain-4F5D2F?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-4F5D2F?style=flat-square&logo=langgraph&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-4F5D2F?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-1A2019?style=flat-square&logo=ollama&logoColor=white)
![RAGFlow](https://img.shields.io/badge/RAGFlow-5B7C8C?style=flat-square)
![OpenClaw](https://img.shields.io/badge/OpenClaw-5B7C8C?style=flat-square)

**检索 & 数据**

![Elasticsearch](https://img.shields.io/badge/Elasticsearch-5B7C8C?style=flat-square&logo=elasticsearch&logoColor=white)
![Vector Search + Rerank](https://img.shields.io/badge/Vector%20Search%20%2B%20Rerank-5B7C8C?style=flat-square)

**模型 & 训练**

![Python](https://img.shields.io/badge/Python-1A2019?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-1A2019?style=flat-square&logo=pytorch&logoColor=white)

`Transformer` `MoE` `GQA` `KV Cache` `LoRA / QLoRA` `SFT` `DPO` `模型量化` `推理加速` `云边端部署`

**具身 & 多模态**

![Robot State](https://img.shields.io/badge/Robot%20State-6E6A60?style=flat-square)
![Multimodal](https://img.shields.io/badge/Multimodal-6E6A60?style=flat-square)
![Agent Eval](https://img.shields.io/badge/Agent%20Eval-6E6A60?style=flat-square)

---

## 📄 论文

**Diff-Ensemble：基于扩散模型的迁移性与隐蔽性对抗攻击研究**  
<sub>Under Review · ACM（CCF-A）</sub>

![CCF-A](https://img.shields.io/badge/CCF--A-4F5D2F?style=flat-square)
![ImageNet](https://img.shields.io/badge/ImageNet-1A2019?style=flat-square)
![ASR 88.77%](https://img.shields.io/badge/ASR-88.77%25-B8571A?style=flat-square)

> 提出基于潜变量扩散模型 LDM 的生成式攻击框架，将对抗生成重构为有引导的降噪过程，干预 DDIM 采样轨迹并结合注意力正则化。ImageNet 黑盒攻击 SOTA：11 种目标模型平均攻击成功率 **88.77%**，FID 50.81，较 DiffAttack / AWT 等基线 ASR 相对提升 **24.7%–39.7%**。

---

## 📊 GitHub

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=liuyuelove&show_icons=true&bg_color=FBF8F1&title_color=4F5D2F&text_color=5B5A50&icon_color=E07A2E&border_color=E5DFD0&locale=zh-cn" alt="GitHub stats" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=liuyuelove&layout=compact&bg_color=FBF8F1&title_color=4F5D2F&text_color=5B5A50&border_color=E5DFD0&locale=zh-cn" alt="Top languages" />
</p>

---

<details>
<summary><b>🎓 教育 &amp; 其他经历</b></summary>

<br/>

- 🎓 **华中师范大学** · 计算机技术硕士（2024.09 – 2027.06）
- 🎓 **武汉纺织大学** · 信息与计算科学（2020.09 – 2024.06）
- 🏆 研究生数学建模大赛国家三等奖 · 大创 A 级项目（基于 Apollo 无人驾驶技术服务系统）
- 🧩 **飞书智能项目管理引擎**（独立开发）：Plugin + Tenant Access Token 双令牌权限体系，4.1W+ 工作项 15 并发拉取与分页降级；Feishu-Project AgentSkill 将飞书项目 API 与高阶查询封装为自然语言指令，让通用 LLM 无需微调即可编排 API 调用链路。

</details>

---

## 🌐 找到我

<p>
<a href="mailto:liuzuizuishuai@gmail.com"><img src="https://img.shields.io/badge/Gmail-liuzuizuishuai%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>
<a href="https://github.com/liuyuelove"><img src="https://img.shields.io/badge/GitHub-liuyuelove-1A2019?style=flat-square&logo=github&logoColor=white" /></a>
</p>

---

<div align="center">
<sub>不努力是假的，写 Agent 是真的。 · 如果这些项目对你有帮助，欢迎 Star ⭐</sub>
</div>
