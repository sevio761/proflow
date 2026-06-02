# 🚀 ProFlow - All-in-One B2B SaaS Platform

**ProFlow** is a unified Chrome extension + web dashboard SaaS platform for B2B teams.

## ✨ Features

- 🎯 **Lead Generation** - LinkedIn & website scraping, email verification
- 📧 **Email Outreach** - Bulk campaigns with open/click tracking
- 🔍 **SEO Auditing** - On-page analysis & keyword ranking
- 👥 **Recruiting** - Auto-fill applications & LinkedIn sourcing
- 📋 **Compliance** - Audit logs & reporting

## 🛠️ Tech Stack

- **Frontend**: React 18 + TypeScript + Vite
- **Backend**: Node.js 20 + Express + TypeScript
- **Database**: PostgreSQL 15
- **Cache**: Redis 7
- **Auth**: JWT + bcrypt
- **Payment**: Stripe

## 🚀 Quick Start

### Prerequisites
- Node.js 20+
- Docker & Docker Compose

### Setup

```bash
git clone https://github.com/sevio761/proflow.git
cd proflow
npm run setup
npm run dev
```

Services available:
- API: http://localhost:5000
- Dashboard: http://localhost:3000
- Database: localhost:5432
- Redis: localhost:6379

## 📦 Project Structure

```
packages/
├── extension/     # Chrome Extension
├── backend/       # API Server
├── web/           # Dashboard
└── shared/        # Shared types
```

## 💰 Pricing

- Starter: $99/mo (1 user)
- Professional: $299/mo (3 users)
- Agency: $999/mo (10 users)
- Enterprise: $3000+/mo (unlimited)

## 🔐 Security

- JWT authentication
- bcrypt password hashing
- HTTPS enforced
- GDPR compliant

## 📞 Contact

Email: donkoff90@gmail.com

## 📄 License

MIT
