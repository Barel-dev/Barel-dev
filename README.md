<h1 align="center">Hi, I'm Barel 👋</h1>

<p align="center">
  <a href="https://github.com/Barel-dev">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=10B981&center=true&vCenter=true&width=620&lines=Backend+%26+Full-Stack+Developer;CS+student+%40+Sapir+Academic+College;I+ship+real-world+apps+end-to-end;Day+trader+who+builds+his+own+tools" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  📍 Sderot, Israel
  &nbsp;·&nbsp;
  🎓 B.Sc. Computer Science at Sapir Academic College (2027)
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/barel-berhayev-b9120139b/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:barel57000@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

### 👨‍💻 About me

I'm a Computer Science student at **Sapir Academic College**, leaning hard into **backend** and **full-stack** work. I'm also a **day trader**, so most of what I build sits where **finance, data, and AI** meet. I like shipping things that actually work end to end, from the data layer to a deployed UI.

- 🤖 Lately building **multi-agent AI products** and **real-time data systems**.
- 🧪 Big on clean code, real-world architecture, and tests that mean something.
- 💼 **Open to Junior Backend / Software Engineering roles.**

### 🛠️ Tech I work with

**Languages**

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend & Data**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)

**AI & Auth**

![Anthropic Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![NextAuth.js](https://img.shields.io/badge/NextAuth.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=flat-square&logo=clerk&logoColor=white)

**Testing & Deploy**

![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

### 🚀 Featured Projects

#### 📈 [Stockify](https://github.com/Barel-dev/Stockify): Real-Time Market Intelligence &nbsp;·&nbsp; [**Live Demo →**](https://stockifyy.vercel.app/)

A full-stack dashboard that breaks down any **stock, crypto, or forex** asset in seconds: live quotes, technicals, fundamentals, news, AI analysis, and strategy backtesting.

- ⚡ **Real-time price layer** over a **WebSocket** feed (Finnhub) plus a **Server-Sent Events** market stream, with no client-side polling.
- 🧪 **Backtesting engine** for **RSI, SMA crossover, and MACD** strategies, computing **Sharpe ratio, max drawdown, and win rate** with equity curves.
- 🤖 AI **bull/bear thesis** generation via **Claude**, grounded in live quotes and news.
- 🗺️ Sector **heatmap** and a **portfolio tracker** benchmarked against the S&P 500.
- 🧱 Tiered **Redis caching** with graceful fallback to stay within API rate limits. Backed by **62 tests** and shipped as an installable **PWA**.

`Next.js 15` · `React 19` · `TypeScript` · `Tailwind` · `Clerk` · `Supabase` · `Upstash Redis` · `Claude`

#### 🤖 [TaskAgent](https://github.com/Barel-dev/Taskagent): AI Multi-Agent Task Manager &nbsp;·&nbsp; [**Live Demo →**](https://taskagent-amber.vercel.app)

A task manager where specialized agents don't just organize your work, they **do** it. Describe a goal, and the agents plan it, break it into steps, and **search the live web to actually carry tasks out**.

- 🧠 A suite of **specialized Gemini agents**: Plan, Breakdown, **Do-it** (executes via live Google Search grounding), Prioritizer, Daily Briefing, Summary, plus **Email** and **Schedule**.
- 📧 **Gmail & Google Calendar** integration: agents draft emails and propose calendar slots, then act **only after you approve** (no auto-send).
- 🗂️ Three workspace views (**list**, drag-and-drop **Kanban**, and a **calendar**) with tags, smart due-dates, filtering, and a chat assistant.
- 🔒 Google **OAuth (NextAuth v5)**, a fully-typed REST API with per-user authorization, structured **Gemini + Zod** output, and DB-backed rate limiting.
- ✅ **Test-driven** against a real Postgres branch (no mocks), verifying cross-user data isolation.

`Next.js 15` · `TypeScript` · `Prisma` · `PostgreSQL (Neon)` · `NextAuth v5` · `Google Gemini` · `Vitest`

#### 📓 TradeJournal: TradeZella-Style Trading Journal &nbsp;·&nbsp; ![Private](https://img.shields.io/badge/repo-private-6e7681?style=flat-square)

A day trader's journal & analytics platform I built for my own trading. *Private repo, available on request.*

- 📥 **CSV import** (auto-maps broker headers and FIFO-matches fills into round-trips) plus **Alpaca** broker sync and manual entry.
- 📊 Dashboard with **equity curve**, a **performance / Zella-style score radar**, win/loss breakdown, and a P&L **calendar**.
- 📒 **Daily journal**, **playbooks** (strategies auto-linked to trades), a **progress tracker** with goals & streaks, and **trade replay**.
- 📈 Deep **reports**: weekday × hour heatmaps, R-multiple distribution, setup/symbol analysis, and period-over-period comparison.
- ⌨️ Position sizer, ⌘K command palette, global filters, and light/dark theme. Runs zero-setup locally or on **Supabase**.

`Next.js 15` · `React 19` · `TypeScript` · `Tailwind` · `Recharts` · `SWR` · `Supabase` · `Lightweight Charts`

### 📊 GitHub Stats

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Barel-dev&hide_border=true&background=00000000&stroke=10b981&ring=10b981&fire=10b981&currStreakLabel=10b981&currStreakNum=8b949e&sideNums=8b949e&sideLabels=8b949e&dates=768390" alt="GitHub Streak" />
</p>

### 🌱 Currently learning

- Designing **distributed systems** with PostgreSQL as the primary datastore.
- Production-quality **Java backend** patterns (Spring Boot, virtual threads).
- Trade-offs in real-time systems: **WebSocket vs SSE vs polling**, caching strategies, and rate limiting.

<p align="center"><i>💬 Open to Junior Backend / Software Engineering roles. Let's build something.</i></p>
