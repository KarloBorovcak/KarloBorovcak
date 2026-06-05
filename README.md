# Hi, I'm Karlo 👋

**I build production AI agents — the kind that ship, not just demo.**

I'm a software engineer in Croatia who takes LLM agents from prototype to production: tools, streaming, evaluation, human-in-the-loop, reliability, cost. My flagship is **Henri**, an analytics agent I built end-to-end (agent + tools + frontend) and put in front of real users — but the craft travels to any domain, and I build in a few of them.

---

### 🤖 Flagship: Henri

A conversational AI agent that turns messy ecommerce & marketing data into clear answers. You ask it things like *"why did my ROAS drop last month?"* and it reasons over real data and replies with analysis, interactive charts, and recommendations. It's my case study in what production agent engineering actually takes:

Under the hood I built:

- **A LangGraph agent** with **25+ tools** spanning Facebook/Google/TikTok ads, Shopify, Klaviyo, LTV & cohort analytics, competitor intelligence, web search, and a stateful Python sandbox for custom analysis
- **Real-time streaming** over SSE — text, charts, and reasoning traces stream in live
- **Human-in-the-loop** flows (e.g. the agent proposes an ad-budget change and waits for your approval before acting)
- **Durable conversations** via a Postgres checkpointer + Redis run state — disconnect and resume without losing context
- **The full frontend** (Next.js / React / TypeScript): the chat UI, live **Highcharts** rendering, and a **voice mode** with low-latency AAC audio streaming (MediaSource Extensions, with an iOS Safari fallback)

---

### 🛠️ Tech I work with

**AI / Agents** · LangGraph · LangChain · OpenAI · Tavily · RAG · tool-calling · agent eval
**Backend** · Python · FastAPI · Celery · Redis · PostgreSQL · SQLAlchemy
**Frontend** · TypeScript · Next.js · React · Chakra UI · Highcharts
**Infra / Data** · AWS (Lambda, S3, ECS, RDS) · ClickHouse · Terraform

---

### 🚧 Currently building

- An open-source LangGraph starter showing the production patterns most tutorials skip — typed tools, token streaming, an eval harness, retries, and cost tracking _(in progress)_
- Writing up what actually breaks when you put LLM agents in production

---

### ✍️ I'm starting to write & build in public

I'm sharing what I've learned shipping AI agents to production — the parts that actually break, not the demos.

- 📝 Blog: _coming soon_
- 🐦 X / Twitter: [@karloborovcak](https://x.com/karloborovcak)
- 💼 LinkedIn: [karlo-borovcak](https://www.linkedin.com/in/karlo-borovcak)
- 📫 Reach me: borovcak.karlo@gmail.com

---

_Building in public. Follow along._
