AetherTech 🚀
AI-Powered Browser Assistant & Productivity Platform

🎯 The Problem
Modern knowledge workers juggle 10+ tools — browser, search, notes, calendar, chat, file storage — just to complete one task like "research X and summarize it." There's no unified workspace combining AI-powered search, browsing assistance, memory, and productivity in one place.

AetherTech solves this by providing a single AI layer over your browser and documents.

✨ What We Built
🧠 Universal Search — Natural-language search across web + your personal docs with citations

🧩 Chrome Extension — AI Sidebar, Command Bar (⌘K), page summarization, screenshot analysis

🤖 AI Agents — Research, Writing, Fact-Check, Vision, and Planner agents working together

💾 Memory System — Long-term recall of past conversations and notes

📊 Web Dashboard — AI Notes, Tasks, Knowledge Graph visualization, Memory Timeline

🔐 Security — Google OAuth, RBAC (Admin/Member), Audit Logs, rate limiting

⚡ Quick Start
bash
git clone https://github.com/your-org/aethertech.git
cp .env.example .env  # Add your API keys
docker-compose up -d
cd backend/api-gateway && npm run prisma:deploy
Then visit http://localhost:3000 and load the extension from ./extension/dist.

🗺️ Phase 2 Roadmap
Forked Chromium engine, custom web crawler, Kubernetes, ERP/CRM/HRMS integrations, AR/VR/IoT/robotics — all documented as future work.
