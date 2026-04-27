<h1 align="center">👋 Hi, I'm MagicCzc</h1>
<h3 align="center">🔧 运维开发工程师 | 🤖 AIOps 实践者 | 📝 技术博主</h3>

<p align="center">
  <a href="https://blog.csdn.net/m0_63875580" target="_blank"><img src="https://img.shields.io/badge/CSDN-博客-c14438?logo=csdn&logoColor=white"></a>
  <a href="https://github.com/magicCzc" target="_blank"><img src="https://img.shields.io/badge/GitHub-主页-181717?logo=github"></a>
  <a href="mailto:910445306@qq.com"><img src="https://img.shields.io/badge/Email-联系-00599C?logo=gmail"></a>
</p>
---

### 🧑‍💻 关于我

- 🔧 **运维开发工程师**，专注 **AIOps（智能运维）** 与系统自动化
- 🤖 实践方向：AIOps / 数据库智能运维 / LLM 故障诊断/根因分析（n8n+ dify + RAGflow + skill）
- 📦 开源项目：[Zabbix-MCP](https://github.com/magicCzc/Zabbix-MCP)、[grafana-query-mcp](https://github.com/magicCzc/grafana-query-mcp)、[dbskiter](https://github.com/magicCzc/dbskiter)、[K8sskill](https://github.com/magicCzc/K8sskill)
- 📝 CSDN 博客：22 篇原创
- 🎯 希望用 AI 让运维更高效、更省心

---

### 🛠️ 技术栈（真实落地）

| 领域 | 技术 |
|------|------|
| **编程语言** | Python (主力) / PowerShell / Shell |
| **后端框架** | FastAPI / Uvicorn |
| **AIOps 编排** | n8n / Dify / RAGflow / K8sGPT |
| **监控 & 可观测** | Zabbix API / Grafana API / Prometheus (/metrics) / 异常检测（动态阈值） |
| **数据库工具** | MySQL / Oracle / PostgreSQL（通过 dbskiter 提供 CLI） |
| **数据处理** | SSE 流式分页 / 异步任务 |

> 容器编排(K8s/Docker)、CI/CD(Jenkins)等能力在工作经历中实践，代码仓库暂不直接体现。

---

### 📌 核心项目 & 在 AIOps 体系中的定位

| 项目 | 角色 | 简介 |
|------|------|------|
| **[K8sskill](https://github.com/magicCzc/K8sskill)** | K8s 集群诊断 Agent | 将 **K8sGPT** 封装为云原生 Agent，让 AI 能感知集群异常与资源状态 |
| **[Zabbix-MCP](https://github.com/magicCzc/Zabbix-MCP)** | 监控数据中台 | Zabbix **只读查询中台** (REST/CLI)，为 AI 提供安全、可靠的监控指标与告警数据 |
| **[ELK-MCP](https://github.com/magicCzc/ELK-MCP)** | 日志检索网关 | 兼容 **Elasticsearch**，提供 Dify 标准接口，支持多租户和权限控制 |
| **[grafana-query-mcp](https://github.com/magicCzc/grafana-query-mcp)** | 时序数据服务 | **Grafana** 查询转换与分页服务，统一时序数据接口，支持 SSE 流式返回 |
| **[dbskiter](https://github.com/magicCzc/dbskiter)** | 数据库 CLI 工具箱 | 提供慢查询分析、索引推荐、健康检查等数据库核心运维功能 |

> **典型工作流**：监控告警 → **n8n/Dify** 触发 → `K8sskill` 巡检 Pod → `Zabbix-MCP` 查指标 → `grafana-query-mcp` 聚合时序 → `ELK-MCP` 检索日志 → `dbskiter` 深度诊断数据库 → **RAGflow** 匹配案例 → 输出根因报告并推送。  
> 平台已内部运行 6 个月，将 **MTTR** 从 15 分钟降至 3 分钟。

---

### 📊 GitHub 统计

<p align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=magicCzc&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=magicCzc&layout=compact&theme=tokyonight&hide=html,css"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=magicCzc&theme=react-dark&bg_color=0d1117&hide_border=true"/>
</p>

---

### 📫 联系我

- 技术交流 / 内推 / 合作：**[910445306@qq.com](mailto:910445306@qq.com)**
- 技术博客：[CSDN @MagicCzc](https://blog.csdn.net/m0_63875580) 每周更新运维 & AIOps 实战

<p align="center">
  <i>✨ 保持好奇，持续交付 ✨</i>
</p>
