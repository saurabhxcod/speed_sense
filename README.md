# ⚡ SpeedSense AI — Smart Expense Tracking with AI

> **Your intelligent money companion** — Track, analyze, and optimize your expenses with lightning-fast AI-powered insights.

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-15-black?style=for-the-badge&logo=next.js"/>
  <img src="https://img.shields.io/badge/React-19-blue?style=for-the-badge&logo=react"/>
  <img src="https://img.shields.io/badge/TypeScript-5-blue?style=for-the-badge&logo=typescript"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-3-38B2AC?style=for-the-badge&logo=tailwind-css"/>
  <img src="https://img.shields.io/badge/Prisma-ORM-3982CE?style=for-the-badge&logo=prisma"/>
  <img src="https://img.shields.io/badge/PostgreSQL-Neon-4169E1?style=for-the-badge&logo=postgresql"/>
  <img src="https://img.shields.io/badge/AI-OpenRouter-ff9800?style=for-the-badge&logo=openai"/>
</p>

---

## ✨ Why SpeedSense AI?

| Feature | What It Does |
|---------|--------------|
| 🤖 **AI Categorization** | Automatically tags expenses based on descriptions |
| 📊 **Real-Time Analytics** | Interactive Chart.js dashboards for instant insights |
| 💬 **AI Chat Assistant** | Get explanations, budgeting tips & predictions |
| 🎨 **Modern UI/UX** | Responsive design, animations, and dark/light mode |
| 🔐 **Secure Auth** | Google, GitHub, Facebook, or Email login via Clerk |

---

## 🧠 How AI Powers Your Finances

SpeedSense AI uses **OpenRouter** (OpenAI-compatible API) to:  
- Detect spending patterns  
- Predict upcoming expenses  
- Suggest cost-saving measures  
- Provide instant explanations for financial trends  

---

## 🛠 Tech Stack

**Frontend:** Next.js 15, React 19, TypeScript, Tailwind CSS  
**Backend:** Next.js Server Actions, Prisma ORM, Neon PostgreSQL  
**AI:** OpenRouter API, AI Categorization Engine  
**Auth:** Clerk Authentication  
**Deployment:** Vercel  

---

## 🚀 Quick Start

```bash
# 1️⃣ Clone repo
git clone https://github.com/<your-username>/speedsense-ai.git
cd speedsense-ai

# 2️⃣ Install dependencies
npm install   # or yarn / pnpm

# 3️⃣ Configure environment
cp .env.example .env

# 4️⃣ Push database schema
npx prisma generate
npx prisma db push

# 5️⃣ Start dev server
npm run dev
