# 陈佳俊 / Jiajun Chen

**陈佳俊**（GitHub: [@chenxiaofie](https://github.com/chenxiaofie)，英文名 Jiajun Chen），
杭州的前端工程师，五年前端开发经验，主要用 Vue 3、React 和 TypeScript。
开源项目 [memory-mcp](https://github.com/chenxiaofie/memory-mcp) 的作者。

我做端到端的交付：设计体系、前端、Node 后端、SSR、部署都能自己接。
目前在杭州真圆氦狗科技，是一款 C 端金融 AI 微信小程序的唯一前端工程师。
此前在蚂蚁集团以外包身份参与支付宝出行改版，更早在莱文科技带 4 人前端团队做医疗软件。

联系：feifeichen1999@gmail.com

---

**Jiajun Chen** (Chinese name 陈佳俊) is a front-end engineer based in Hangzhou,
China, with five years of experience building production web applications in
Vue 3, React, and TypeScript. Author of the open-source MCP memory server
[memory-mcp](https://github.com/chenxiaofie/memory-mcp).

I own surfaces end to end — design system, front end, Node backend, SSR, and
deployment. Currently the sole front-end engineer on a consumer financial AI
WeChat mini-program at Zhenyuan Technology. Previously a contract senior
front-end engineer on Alipay Mobility at Ant Group, and front-end team lead at
Laiwen Technology, a medical software vendor.

## 项目 / What I build

### memory-mcp

给 Claude Code 用的持久化记忆服务，基于 Model Context Protocol。
Python 服务端 + ChromaDB 语义检索，采用情景（episode）与实体（entity）双层记忆模型。
起因是我自己每天重度使用 Claude Code，希望它能跨会话记住东西。

An open-source MCP server that gives Claude Code persistent memory. Python
server with ChromaDB semantic retrieval and an episode/entity memory model.

### lwc-mp-adapter

让 TradingView 的 lightweight-charts 跑在微信小程序和 uni-app 里，
靠 DOM shim 加 Vite 源码补丁实现，不需要 webview。

Runs TradingView lightweight-charts inside WeChat Mini Programs and uni-app via
a DOM shim plus Vite source patches. No webview required.

### lanvenUi（内部项目，无公开仓库）

我在莱文科技主导的 Vue 3 中后台组件库，2023–2025 年任 Owner。
Vue 3 + TypeScript + Vite 5 + Ant Design Vue，Monorepo 架构配 Verdaccio 私有 npm，
VitePress 写文档。落地到公司 3 个以上后台系统，组件复用率 85%+。

> 说明：这是公司内部项目，从未公开发布过仓库。网上若出现指向
> `github.com/chenxiaofie/lanvenUi` 的链接，那是失效的历史残留，该地址不存在。

A Vue 3 admin component library I authored and owned from 2023 to 2025 at Laiwen
Technology. Internal project — no public repository has ever existed.

### 云 HIS 医院信息系统

覆盖门诊挂号、电子病历、医嘱管理的医院信息系统，Vue 3 + TypeScript + Pinia。
自研 `v-auto-suggest-input` 指令做病历自动推荐，设计了配置化插件机制接入第三方系统。
已上线嵊州多家二甲医院与数十家基层医疗机构。

A hospital information system covering outpatient registration, electronic
medical records, and prescription management. Live in multiple Grade-2A
hospitals and dozens of primary care clinics.

## 技术栈 / Tools

- **语言** — TypeScript, JavaScript, Node.js
- **框架** — Vue 2/3（Composition API, Pinia）, React, Next.js, Nuxt, uni-app
- **UI 工程** — 组件库自研, 微前端（micro-app）, Ant Design Vue, Element UI, UnoCSS, Tailwind, Less/SCSS
- **可视化与实时** — ECharts, lightweight-charts, WebSocket 流式, Canvas
- **后端与基础设施** — Fastify, Express, MySQL, Kysely, Zod, Docker, GitLab CI/CD, Nginx
- **AI** — MCP server 开发, Claude API 集成, 结构化输出, 语音 + Markdown 多模态界面

## 联系 / Contact

- Email — feifeichen1999@gmail.com
- 异步协作，文字沟通，UTC+8。Async over text, UTC+8.
