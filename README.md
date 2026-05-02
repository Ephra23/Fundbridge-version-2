# FundBridge 🌍

**Uganda & East Africa's AI-Powered Loan Management Platform**

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/YOUR_USERNAME/fundbridge)

---

## 🚀 Live Demo

> Deployed at: [https://fundbridge.vercel.app](https://fundbridge.vercel.app)

---

## 🔑 Demo Login Credentials

| Role | Email | Password |
|------|-------|----------|
| **Super Admin** | admin@fundbridge.co.ug | password123 |
| **Company Admin** | grace@nakimuli-mf.co.ug | password123 |
| **Client User** | user@business.co.ug | password123 |

---

## ✨ Features

- 🤖 **AI Credit Check** — NIRA + gnuGrid CRB + Mobile Money scoring
- 👥 **Group Lending** — VSLA, Chama, SACCO, table banking
- 📱 **Mobile Money** — MTN MoMo & Airtel Money integration
- 💰 **Savings Module** — Passbook, deposits, withdrawals per member
- 🔌 **Offline Mode** — Works without internet
- 📋 **Collection Sheets** — Printable field sheets for loan officers
- 📊 **Full Accounting** — Summaries, statements, chart of accounts
- 🌍 **Multi-tenant SaaS** — One platform, many lending companies

---

## 🗂️ Project Structure

```
fundbridge/
├── index.html      ← Entire application (HTML + CSS + JS)
├── vercel.json     ← Vercel deployment config
├── .gitignore      ← Git ignore rules
└── README.md       ← This file
```

---

## 🚀 Deploy to Vercel

### Option 1 — One Click
Click the **Deploy with Vercel** button above.

### Option 2 — Manual
1. Fork this repo
2. Go to [vercel.com](https://vercel.com) → New Project
3. Import this repo
4. Settings:
   - **Framework**: Other
   - **Build Command**: *(leave empty)*
   - **Output Directory**: `.`
5. Click **Deploy**

---

## 🛠️ Run Locally

No build step needed — just serve the file:

```bash
# Python (built into every Mac/Linux)
python3 -m http.server 3000
# Open: http://localhost:3000

# Node.js
npx serve .
# Open the URL shown
```

---

## 📋 Roadmap

- [ ] Backend API (Node.js + PostgreSQL)
- [ ] Real NIRA NIN verification
- [ ] Live gnuGrid CRB integration
- [ ] MTN MoMo production API
- [ ] Offline sync (IndexedDB)
- [ ] Mobile app (iOS + Android)

---

## 📄 License

Proprietary — FundBridge Uganda Ltd © 2026
