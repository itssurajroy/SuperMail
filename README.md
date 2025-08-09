# 📧 SuperMail — Gmail Productivity & Tracking Extension

SuperMail is a **Chrome extension** built with **Node.js + TypeScript** (Manifest V3) to enhance your Gmail experience.  
It enables **email tracking**, **scheduled follow-ups**, and **productivity tools** while prioritizing **security, privacy, and reliability**.

---

## ✨ Features

- **Email Open Tracking** — Know when recipients open your email.
- **Click Tracking** — Validate and track safe links clicked from your emails.
- **Scheduled Follow-ups** — Never miss a follow-up with BullMQ + Redis backend.
- **Google OAuth Authentication** — Secure login with Gmail API integration.
- **Persistent Storage** — Encrypted data storage in PostgreSQL.
- **Rate Limiting** — Prevent abuse & stay API-compliant.
- **Prometheus & Sentry Monitoring** — Full observability and error tracking.
- **Secure by Default** — Static analysis, dependency scanning, and secret management.

---

## 🛠 Tech Stack

- **Extension:** Chrome MV3, TypeScript, Webpack
- **Backend:** Node.js, Express, BullMQ, Redis
- **Database:** PostgreSQL with encryption at rest
- **Auth:** Google OAuth 2.0
- **Monitoring:** Prometheus, Sentry
- **Security:** ESLint, npm-audit, GitHub Dependabot, Gitleaks

---

## 🚀 Getting Started

### 1️⃣ Clone Repository
```bash
git clone https://github.com/itssurajroy/SuperMail.git
cd SuperMail
