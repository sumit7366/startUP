# 🌾 Farmer Connect — India's Agriculture Super Platform

<p align="center">
  <img src="https://img.shields.io/badge/Platform-AgriTech-green?style=for-the-badge&logo=leaf&logoColor=white" />
  <img src="https://img.shields.io/badge/Made%20for-Indian%20Farmers-orange?style=for-the-badge&logo=india&logoColor=white" />
  <img src="https://img.shields.io/badge/AI%20Powered-Claude%20AI-purple?style=for-the-badge&logo=anthropic&logoColor=white" />
  <img src="https://img.shields.io/badge/Deployed%20on-Vercel-black?style=for-the-badge&logo=vercel&logoColor=white" />
</p>

<p align="center">
  <strong>Empowering Indian Farmers with Technology, Commerce, Community & AI</strong>
</p>

<p align="center">
  <a href="https://farmer-six-sigma.vercel.app/">🌐 Live Website</a> •
  <a href="https://github.com/sumit7366/startUP/raw/main/Farmer.apk">📥 Download APK</a> •
  <a href="mailto:farmerrsupport@gmail.com">✉️ Contact</a>
</p>

---

## 📥 Download App

<p align="center">
  <a href="https://github.com/sumit7366/startUP/raw/main/Farmer.apk">
    <img src="https://img.shields.io/badge/⬇️%20DOWNLOAD%20APK-FARMER%20CONNECT-2ea44f?style=for-the-badge&logo=android&logoColor=white" />
  </a>
</p>

> ✅ Direct APK download — Android device mein seedha install karein. No Play Store required.

---

## 📖 Overview

**Farmer Connect** is an industry-level AgriTech startup platform designed to transform the agriculture ecosystem of India by bringing farmers, buyers, workers, advertisers, local businesses, service providers, shop owners, and everyday local users together into one powerful digital ecosystem.

This platform is **not limited to farmers only** — anyone can use Farmer Connect to:

- 🛒 Buy & sell products
- 📢 Promote local businesses
- 💼 Find jobs or workers
- 🤝 Build professional connections
- 📣 Advertise services
- 💬 Chat and network locally
- 🤖 Access AI-powered assistance

---

## 🚀 Vision

To become **India's largest digital agriculture ecosystem** where every farmer can:

- Sell products directly — no middlemen
- Find agricultural workers easily
- Build strong business networks
- Learn modern farming techniques
- Access AI-powered guidance anytime
- Earn more through digital transformation

---

## 🎯 Mission

Farmer Connect aims to digitize and modernize Indian agriculture through:

- Smart technology & AI
- Direct farmer-to-buyer connections
- Real-time communication tools
- Rural employment opportunities
- Secure online infrastructure
- Mobile-first design for rural accessibility

---

## 🌟 Core Platform Modules

### 🛒 Marketplace System

A complete marketplace where farmers and sellers can:

- Upload agriculture products with images
- Add pricing & product details
- Manage inventory
- Connect directly with buyers
- Filter by category & location

**Features:** Product Listings · Categories & Filters · Product Images · Product Details Page · Seller Profiles · Buyer Interaction · Mobile Responsive UI

---

### 🤝 Agriculture Social Network

A social networking system specially built for farmers and agriculture professionals.

**Features:**
- Create & share posts
- Upload images
- Like & interact with community
- Follow/Unfollow users
- Agriculture community feed
- Networking opportunities

---

### 💬 Real-Time Chat System

Powered by Firebase for instant, reliable messaging.

**Features:**
- One-to-one messaging
- Instant real-time updates
- Premium chat limits
- User chat profiles
- Firebase-powered infrastructure

---

### 👨‍🌾 Agriculture Job Board

A dedicated job system for farmers, workers, and agriculture companies.

**Features:**
- Post jobs
- Apply for jobs
- Worker profiles
- Employment opportunities
- Agriculture workforce network

---

### 🤖 AI Farming Assistant

Powered by **Anthropic Claude AI** — the smartest farming companion.

**AI Capabilities:**
- Crop guidance & advice
- Fertilizer suggestions
- Farming best practices
- Agriculture tips & tricks
- Weather-based advice
- Productivity improvement guidance

---

### 📢 Advertisement Management System

Businesses and advertisers can promote agriculture products and services.

**Features:**
- Ad submission system
- Admin review & approval
- Advertisement dashboard
- Campaign management

---

### 💳 Premium Subscription System

Users can unlock premium features through UPI payments.

| Plan | Price | Savings |
|------|-------|---------|
| Monthly Premium | ₹99/month | — |
| Yearly Premium | ₹799/year | Save ₹389/year |

**Premium Benefits:**
- Extended chat access
- WhatsApp integration
- Premium networking features
- Increased marketplace visibility
- Priority support

---

## 💳 UPI Payment Workflow

The payment system is designed specifically for Indian users.

```
1. User selects subscription plan
       ↓
2. Platform generates UPI payment link
       ↓
3. Google Pay / PhonePe / Paytm opens automatically
       ↓
4. User completes payment
       ↓
5. User uploads payment screenshot
       ↓
6. Admin reviews payment
       ↓
7. ✅ Premium activated successfully
```

---

## 🔥 Tech Stack

| Technology | Purpose |
|------------|---------|
| **Next.js 14** | Full-stack React Framework |
| **TypeScript** | Type Safety |
| **Firebase Auth** | Authentication System |
| **Firestore** | Real-Time Database |
| **Firebase Storage** | Image & File Storage |
| **Tailwind CSS** | Modern UI Design |
| **Claude AI** | AI Farming Assistant |
| **Vercel** | Deployment & Hosting |
| **App Router** | Modern Routing System |

---

## 🏗️ Project Structure

```
farmer-connect/
├── app/
│   ├── (auth)/
│   │   ├── login/page.tsx
│   │   └── register/page.tsx
│   ├── (dashboard)/
│   │   ├── layout.tsx
│   │   ├── feed/page.tsx
│   │   ├── marketplace/
│   │   │   ├── page.tsx
│   │   │   ├── new/page.tsx
│   │   │   └── [id]/page.tsx
│   │   ├── chat/
│   │   │   ├── page.tsx
│   │   │   └── [id]/page.tsx
│   │   ├── jobs/page.tsx
│   │   ├── network/page.tsx
│   │   ├── notifications/page.tsx
│   │   ├── ai-assistant/page.tsx
│   │   ├── subscription/page.tsx
│   │   ├── ads/page.tsx
│   │   └── profile/[[...uid]]/page.tsx
│   ├── (admin)/
│   │   ├── layout.tsx
│   │   ├── dashboard/page.tsx
│   │   ├── payments/page.tsx
│   │   ├── users/page.tsx
│   │   ├── ads/page.tsx
│   │   └── settings/page.tsx
│   ├── api/ai/route.ts
│   ├── contact/page.tsx
│   ├── help/page.tsx
│   ├── privacy/page.tsx
│   ├── terms/page.tsx
│   ├── layout.tsx
│   ├── page.tsx
│   └── globals.css
├── components/
│   └── layout/
│       ├── Sidebar.tsx
│       ├── Header.tsx
│       └── BottomNav.tsx
├── lib/
│   ├── firebase/
│   │   ├── config.ts
│   │   ├── auth.ts
│   │   ├── firestore.ts
│   │   └── storage.ts
│   ├── types/index.ts
│   └── utils/index.ts
├── contexts/
│   └── AuthContext.tsx
├── middleware.ts
├── firestore.rules
├── storage.rules
├── firestore.indexes.json
├── firebase.json
├── tailwind.config.ts
├── next.config.mjs
└── package.json
```

---

## 👥 User Roles & Permissions

| Role | Description |
|------|-------------|
| **Farmer** | Sell products & access marketplace |
| **Buyer** | Browse & purchase products |
| **General User** | Buy & sell access |
| **Worker** | Apply for agriculture jobs |
| **Advertiser** | Submit advertisements |
| **Admin** | Moderate users & content |
| **Master Admin** | Full platform control |

---

## 🔐 Authentication System

**Login Methods:**
- Google Sign-In (one-tap)
- Email & Password Authentication

**Security Features:**
- Protected routes with middleware
- Role-based access control
- Firebase security rules
- Secure cloud storage
- JWT token authentication

---

## 📱 Features Checklist

### Core Features

- ✅ Landing Page
- ✅ Authentication (Google + Email)
- ✅ Marketplace
- ✅ Real-Time Chat
- ✅ Job Board
- ✅ AI Assistant (Claude AI)
- ✅ Notification System
- ✅ Subscription System (UPI)
- ✅ Advertisement Management
- ✅ Admin Dashboard
- ✅ User Management
- ✅ Payment Approval System
- ✅ Mobile Responsive Design
- ✅ Firebase Security Rules
- ✅ Vercel Deployment

---

## 🏢 Business Model & Revenue Streams

| Revenue Source | Details |
|----------------|---------|
| **Premium Subscriptions** | ₹99/month · ₹799/year |
| **Advertisement Revenue** | Business ad placements |
| **Marketplace Fees** | Transaction commission |
| **Business Partnerships** | Brand collaborations |
| **Agri Brand Promotions** | Sponsored content |
| **AI Farming Services** | Advanced AI features |

---

## 🧠 Why Farmer Connect?

### 🚀 Complete Agriculture Ecosystem
Instead of solving one problem, Farmer Connect creates an **entire agriculture digital ecosystem** — marketplace, jobs, social network, AI, and chat all in one place.

### 🤖 AI + Agriculture Combination
The platform integrates **Claude AI** directly into farming workflows for real-time, intelligent crop and farming guidance.

### 📱 Mobile-First India Focus
Built specifically for **Indian mobile users and rural accessibility** — fast, lightweight, and optimized for low-bandwidth conditions.

### 💳 India-Friendly Payment System
**UPI-first payment flow** (Google Pay, PhonePe, Paytm) for easier adoption across rural India.

### 🔒 Secure & Scalable
Built with **Firebase cloud infrastructure** for enterprise-grade security and unlimited scalability.

### 🌍 Massive Market Opportunity
India has over **140+ million farmers**, making AgriTech one of the fastest-growing startup sectors in the country.

---

## 📈 Future Roadmap

| Feature | Status |
|---------|--------|
| 🌦️ Live Weather Integration | Planned |
| 🛰️ Satellite Crop Monitoring | Planned |
| 📊 Farmer Analytics Dashboard | Planned |
| 🧾 Invoice & Billing System | Planned |
| 🌐 Multi-Language Support (Hindi, Tamil, Telugu…) | Planned |
| 📦 Logistics & Delivery Integration | Planned |
| 📍 Geo-Location Based Marketplace | Planned |
| 🎥 Video Learning Platform | Planned |
| 🛍️ Agri Equipment Rental | Planned |
| 🏦 Agriculture Loan Integration | Planned |

---

## 🏗️ Architecture Overview

```
┌─────────────────────────────────────────────────────┐
│                  FARMER CONNECT                      │
│              Next.js 14 + App Router                 │
└──────────────┬──────────────────────┬───────────────┘
               │                      │
    ┌──────────▼──────────┐  ┌────────▼──────────────┐
    │   Firebase Backend  │  │    Anthropic Claude    │
    │  Auth · Firestore   │  │     AI Assistant       │
    │  Storage · Rules    │  │   /api/ai/route.ts     │
    └──────────┬──────────┘  └───────────────────────┘
               │
    ┌──────────▼──────────────────────────────────────┐
    │                 Vercel Hosting                   │
    │         https://farmer-six-sigma.vercel.app      │
    └─────────────────────────────────────────────────┘
```

---

## 🚀 Getting Started (Development)

### Prerequisites

- Node.js 18+
- npm or yarn
- Firebase account
- Anthropic API key

### Installation

```bash
# Clone the repository
git clone https://github.com/sumit7366/startUP.git

# Navigate to project directory
cd farmer-connect

# Install dependencies
npm install

# Create environment file
cp .env.example .env.local
```

### Environment Variables

Create a `.env.local` file in the root directory:

```env
# Firebase Configuration
NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_auth_domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_storage_bucket
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id

# Anthropic Claude AI
ANTHROPIC_API_KEY=your_anthropic_api_key
```

### Run Development Server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Build for Production

```bash
npm run build
npm start
```

---

## 📲 Mobile App (Android APK)

Farmer Connect is available as a native Android APK.

<p align="center">
  <a href="https://github.com/sumit7366/startUP/raw/main/Farmer.apk">
    <img src="https://img.shields.io/badge/⬇️%20DOWNLOAD%20APK-FARMER%20CONNECT-2ea44f?style=for-the-badge&logo=android&logoColor=white" />
  </a>
</p>

**Installation Steps:**
1. Click the download button above
2. Open the downloaded `Farmer.apk` file on your Android device
3. Allow "Install from unknown sources" if prompted
4. Tap Install
5. Open Farmer Connect and register/login

> The platform architecture is fully compatible with future **Android and iOS app** deployment via React Native or Capacitor.

---

## 📞 Support & Contact

| Channel | Details |
|---------|---------|
| 📞 Phone | [7366006363](tel:7366006363) |
| ✉️ Email | [farmerrsupport@gmail.com](mailto:farmerrsupport@gmail.com) |
| 🌐 Website | [farmer-six-sigma.vercel.app](https://farmer-six-sigma.vercel.app/) |
| 📥 APK Download | [Download Here](https://github.com/sumit7366/startUP/raw/main/Farmer.apk) |

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is proprietary software. All rights reserved.

© 2024 Farmer Connect. Made with ❤️ for Indian Farmers.

---

## ❤️ Built For Indian Farmers

Farmer Connect is not just a website — it is a **mission** to digitally empower Indian farmers, improve agriculture business opportunities, and create a connected farming ecosystem powered by modern technology and AI.

---

<p align="center">
  <strong>🇮🇳 Jai Kisan • Jai Bharat 🌾</strong>
  <br/>
  <em>Made with ❤️ for the Future of Indian Agriculture</em>
</p>
