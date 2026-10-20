<div align="center">
  <img src="https://github.com/leicanxi.png" width="112" alt="leicanxi" />
  <h1>雷灿曦 · leicanxi</h1>
  <p><strong>嵌入式软件工程师 · AI 应用集成</strong></p>
  <p>把大模型接进真实产品：LLM 网关、Android 客户端、后端系统</p>

  <p>
    <a href="https://flowbee.top"><img src="https://img.shields.io/badge/FlowBee-flowbee.top-C96442?style=flat-square" alt="FlowBee" /></a>
    <a href="mailto:63656387@qq.com"><img src="https://img.shields.io/badge/Email-63656387%40qq.com-2F6F6B?style=flat-square" alt="Email" /></a>
    <a href="https://github.com/leicanxi"><img src="https://img.shields.io/badge/GitHub-leicanxi-1F2430?style=flat-square&logo=github" alt="GitHub" /></a>
  </p>
</div>

## 关于我

- 海南大学 · 电子信息工程
- 求职方向：**嵌入式软件工程师**；AI 工程化是差异化能力，不是算法方向
- 能力边界：做过 LLM 网关二次开发与线上运维、Android AI 客户端、FastAPI 后端；没有做过模型训练 / SFT / LoRA
- 关注：系统稳定性、协议与状态一致性、可观测性、低配部署

> 我不是做模型训练或算法研究的。我的 AI 经验集中在**把大模型接进真实产品和研发流程**——这也是我在嵌入式岗位之外，能额外承担的工作。

## 精选项目

| 项目 | 一句话 | 技术栈 |
|---|---|---|
| **[flowbee-api](https://github.com/leicanxi/flowbee-api)** | 跑在 2C/1.9G 小机器上的多模型 LLM 网关：协议兼容、计费、限流、渠道亲和、运营后台 | Go · Gin · React · SQLite/PostgreSQL |
| **[flowbee-chat-plus](https://github.com/leicanxi/flowbee-chat-plus)** | 原生 Android LLM 客户端：多供应商、MCP、工作区、语音、Web 多端 | Kotlin · Compose · Room · Koin |
| **[inkfield](https://github.com/leicanxi/inkfield)** | 「砚田日耕」AI 长期成长规划后端：五层规划模型、状态机、容量分配、事务性 Outbox | Python · FastAPI · PostgreSQL · Celery |
| **[learning-checkin-wechat](https://github.com/leicanxi/learning-checkin-wechat)** | 微信小程序学习打卡：AI 计划、遗忘曲线复习、日历展望、规律性排行 | 小程序 · FastAPI · SQLite · DeepSeek |

> 四个项目都包含架构图、真实截图、快速开始与设计取舍，不是只有代码的空仓库。

## 技术栈

**嵌入式**

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![Keil](https://img.shields.io/badge/Keil%20MDK-394049?style=flat-square)
![LPC1114](https://img.shields.io/badge/LPC1114-Cortex--M0-0091BD?style=flat-square)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)

**后端 / 基础设施**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**客户端 / AI 工程**

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-1F2430?style=flat-square)
![SSE](https://img.shields.io/badge/SSE-Streaming-C96442?style=flat-square)

## 正在做

- **FlowBee**：把多家上游模型收口成一个 OpenAI 兼容入口，持续打磨计费一致性、渠道亲和与低配部署。
- **砚田日耕**：用「长期目标 → 阶段 → 里程碑 → 周计划 → 任务」替代日打卡，AI 提计划、后端做校验。
- **嵌入式**：寄存器级驱动、传感器与存储、低功耗任务链；用 AI 读手册、生成驱动骨架、定位时序问题。

## 一些实践

- **先拿证据再改配置**：用户报「API Key 失效」，先逐把直测上游，再按渠道 × 状态码统计日志，最后定位到 `model_mapping` 漏配，而不是直接换 Key。
- **缓存命中率是可以被工程手段改善的**：把多 Key 渠道拆成一渠道一 Key，再做按用户渠道亲和，DeepSeek 前缀缓存命中率从 52.9% 提升到 67.4%。
- **AI 不拥有真相**：AI 可以提出计划，但容量、截止、状态迁移必须由后端确定性规则校验后才能落库。

## 联系

- GitHub：[leicanxi](https://github.com/leicanxi)
- Email：[63656387@qq.com](mailto:63656387@qq.com)
- FlowBee：[flowbee.top](https://flowbee.top) · [使用文档](https://docs.flowbee.top)

如果你在找嵌入式软件工程师，或者想交流 LLM 网关 / Android 客户端 / 后端设计，欢迎直接联系我。
