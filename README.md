<div align="center">

# 💼 Rizq Digital — Investment & Referral Platform

**A complete fintech-style web platform with user wallets, tiered investment plans, a multi-level referral system, and a full admin control panel — powered by Firebase real-time data.**

![Status](https://img.shields.io/badge/status-production-success)
![Type](https://img.shields.io/badge/type-FinTech%20Platform-2ecc71)

[![Firebase](https://img.shields.io/badge/Firebase-Auth%20%2B%20Firestore-FFCA28?logo=firebase&logoColor=black)](https://firebase.google.com)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6%2B-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Responsive](https://img.shields.io/badge/design-responsive-blue)]()

</div>

---

## Overview

**Rizq Digital** is a full-featured investment platform front-end with a complete user and admin ecosystem. Users register, fund a wallet, subscribe to investment plans, earn through a multi-level referral structure, and request withdrawals — while administrators manage users, payments, plans, and payouts from a dedicated control panel.

The entire system is wired to **Firebase** (Auth + Firestore) for real-time balances, transactions, and team data, with live `onSnapshot` updates and batched writes for consistency.

> Built by **[DG Technology](https://dgtechnology.com)** — engineered by Faiz Ullah.

---

## Key Features

### User Side
- 🔐 **Authentication** — register, login, forgot-password flows via Firebase Auth
- 💰 **Wallet dashboard** — live balance, deposits, earnings, real-time updates
- 📈 **Investment plans** — multiple tiered plans with configurable returns
- 👥 **Multi-level referral system** — team structure with per-level commission tracking
- 🏆 **Rewards system** — milestone and referral rewards
- 💸 **Withdrawal requests** — users request payouts, tracked through to completion
- 📜 **Transaction history & reports** — full audit trail per user
- 🎫 **Support** — built-in support page

### Admin Side
- 🛡️ **Admin dashboard** — platform oversight with secure admin login
- 👤 **User management** — view and manage all members
- 💳 **Payment & withdrawal management** — approve deposits and payouts
- 📢 **Ad/announcement management** — push platform-wide notices

---

## Tech Stack

| Component | Technology |
|-----------|-----------|
| **Frontend** | HTML5, CSS3, Vanilla JavaScript (ES6 modules) |
| **Backend** | Firebase (serverless) |
| **Auth** | Firebase Authentication |
| **Database** | Firebase Firestore (real-time `onSnapshot`, batched writes) |
| **Design** | Custom responsive UI, Poppins typography, Font Awesome |

---

## Architecture Highlights

**Real-time financial data.** Balances, transactions, and team stats sync live via Firestore listeners — no refresh needed. Multi-document updates use Firestore `writeBatch` to keep wallet and transaction records atomic and consistent.

**Multi-level referral engine.** The team system tracks referrals across multiple levels with distinct commission percentages per tier, recording the full downline structure per user.

**Separation of user & admin.** Independent authentication and a dedicated admin panel keep platform management cleanly isolated from the user experience.

---

## Pages

```
rizq-digital/
├── index.html              # Landing page
├── register / login        # Auth flows
├── dashboard.html          # User wallet & overview
├── plans.html              # Investment plans
├── my-team.html            # Multi-level referral tree
├── rewards.html            # Rewards system
├── withdraw.html           # Withdrawal requests
├── payment.html            # Deposit / funding
├── history.html            # Transaction history
├── reports.html            # User reports
├── profile.html            # Account settings
├── support.html            # Support center
├── admin.html              # Admin control panel
└── ad_admin.html           # Announcement management
```

---

> ⚠️ **Note:** This repository is a technical demonstration of a Firebase-powered financial platform — real-time wallets, referral logic, and admin systems. Credentials and config are environment-specific and not committed.

---

<div align="center">

**Designed & engineered by Faiz Ullah**
Full-Stack Developer · Firebase Specialist · Founder of [DG Technology](https://dgtechnology.com)

📧 contact@faizullah.pk · 🌐 [faizullah.pk](https://faizullah.pk)

*Built with precision by DG Technology* 💙

</div>
