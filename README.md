# 💰 Next Expense Tracker

Your intelligent companion for tracking expenses and managing your finances — powered by next-generation AI insights.

---

## ✨ Features

- 📊 **Interactive Dashboard** — Visualize spending patterns with dynamic charts (Chart.js + React ChartJS).
- 🤖 **AI-Powered Insights** — Get personalized tips, warnings, and recommendations on your finances.
- 🏦 **Smart Categorization** — Expenses automatically categorized with AI.
- 🔐 **Secure Authentication** — User sign-up, login, and session management via [Clerk](https://clerk.com).
- 🗄️ **Reliable Database** — Hosted on [Neon](https://neon.tech) (serverless PostgreSQL) with Prisma ORM.
- 🎨 **Modern UI** — Built with [TailwindCSS](https://tailwindcss.com) for a clean and responsive design.
- ⚡ **Next.js 15 + TypeScript** — Performance-first architecture with the latest web technologies.

---

## 🛠️ Tech Stack

- **Framework**: [Next.js 15](https://nextjs.org) + [React 19](https://react.dev)
- **Styling**: [TailwindCSS](https://tailwindcss.com)
- **Database**: [Neon (PostgreSQL)](https://neon.tech) + [Prisma](https://www.prisma.io)
- **Auth**: [Clerk](https://clerk.com)
- **AI**: [OpenAI](https://platform.openai.com), [Groq](https://groq.com), or [OpenRouter](https://openrouter.ai)
- **Charts**: [Chart.js](https://www.chartjs.org) + [react-chartjs-2](https://react-chartjs-2.js.org)

---

## 🚀 Getting Started

1. Clone the repo
git clone https://github.com/SSEFU/expense-tracker.git
cd expense-tracker
2. Install dependencies
bash
Copia codice
npm install
3. Configure environment variables
Create a .env.local file and add your keys:

env
Copia codice
DATABASE_URL="your-neon-database-url"
NEXT_PUBLIC_APP_URL="http://localhost:3000"

OPENAI_API_KEY="your-openai-api-key"
OPENROUTER_API_KEY="your-openrouter-api-key"
GROQ_API_KEY="your-groq-api-key"

CLERK_SECRET_KEY="your-clerk-secret-key"
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY="your-clerk-publishable-key"
4. Setup the database
bash
Copia codice
npx prisma migrate dev
5. Run the app
bash
Copia codice
npm run dev
App runs on http://localhost:3000.
