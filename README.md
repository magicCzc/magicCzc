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

### 🏆 我的 AIOps 项目体系

| 项目 | 定位 | 关键能力 | 技术栈 |
|------|------|----------|--------|
| **[K8sskill](https://github.com/magicCzc/K8sskill)** | K8s 集群诊断 Agent | 封装 K8sGPT，提供自然语言故障诊断与修复建议，让 AI 能感知集群异常 | Python, K8sGPT, Docker |
| **[Zabbix-MCP](https://github.com/magicCzc/Zabbix-MCP)** | 监控数据只读中台 | REST/CLI 双接口，RBAC 权限、审计日志，核心原则 READ_ONLY=1 全局只读 | Python, FastAPI, Zabbix API |
| **[ELK-MCP](https://github.com/magicCzc/ELK-MCP)** | 日志检索网关 | 兼容 ES 6.5.4，字段精简 + 分页上限 + 长消息截断，为 Dify 工作流提供稳定日志能力 | Python, FastAPI, Elasticsearch |
| **[grafana-query-mcp](https://github.com/magicCzc/grafana-query-mcp)** | 时序数据服务 | 多数据源自动选择、SSE 流式分页、内置异常检测（动态阈值） | Python, FastAPI, Grafana API |
| **[dbskiter](https://github.com/magicCzc/dbskiter)** | 数据库 CLI 工具箱 | 慢查询分析、索引推荐、健康监控、安全审计、锁分析 | Python, MySQL, Oracle |

**典型工作流**：Zabbix 告警 → n8n/Dify 触发 → K8sskill 巡检 Pod → Zabbix-MCP 查指标 → grafana-query-mcp 聚合时序 → ELK-MCP 检索日志 → dbskiter 诊断数据库 → RAGflow 匹配历史案例 → 输出根因报告并推送钉钉

📈 **成果**：平台已内部运行 6 个月，将 MTTR 从 15 分钟降至 3 分钟

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
