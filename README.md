<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,50:1e0533,100:8b5cf6&height=210&section=header&text=Chill%20Space%20v3&fontSize=50&fontColor=ffffff&fontAlignY=40&desc=The%20Ultimate%20Collaboration%20Hub%20%E2%80%A2%20Connect.%20Code.%20Vibe.&descAlignY=60&descSize=17&animation=fadeIn" />

<br/>

[![TypeScript](https://img.shields.io/badge/TypeScript-97.8%25-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://github.com/Bhogi123-T/Chill-Space)
[![Rust](https://img.shields.io/badge/Rust-1.4%25-CE422B?style=for-the-badge&logo=rust&logoColor=white)](https://github.com/Bhogi123-T/Chill-Space)

[![Live Demo](https://img.shields.io/badge/🔴%20Live%20Demo-tamizh--loginpage.netlify.app-8b5cf6?style=for-the-badge)](https://tamizh-loginpage.netlify.app/)
[![Author](https://img.shields.io/badge/Author-Bhogeswara%20Rao%20T-8b5cf6?style=flat-square)](https://github.com/Bhogi123-T)
![Status](https://img.shields.io/badge/Backend%20Integration-In%20Progress-orange?style=flat-square)

</div>

---

## 📌 Overview

**Chill Space v3** is a high-performance digital collaboration workspace built for builders, gamers, students, and friends. It is not just another chat app — it is a full-featured platform with real-time communication, a Monaco-powered in-browser code playground, a gamified focus mode, and an arcade center, all wrapped in a premium glassmorphism UI.

The stack is intentionally powerful: **Next.js 16** on the frontend, **Supabase** for real-time data, and a **Rust (Actix-Web)** backend for high-performance code execution.

---

## 🔴 Live Demo

> **[tamizh-loginpage.netlify.app](https://tamizh-loginpage.netlify.app/)** *(Backend Integration In Progress)*

---

## ✨ Features

### 🎨 Ultra-Premium UI
- **Glassmorphism design** — frosted glass cards, modals, and sidebars throughout
- **Deep dark theme** — `#0a0a0a` background with `#8b5cf6` violet accent system
- **Fluid animations** — powered by **Framer Motion** for a native desktop feel
- Consistent aesthetic across Arcade, Code, Chat, and Focus pages

### 💬 Real-Time Communication
- **Live chat** powered by Supabase Realtime subscriptions
- **Rich media** — send PDFs, images, and text files with instant previews
- **Smart mentions** — tag users `@username` or files `@[document.pdf]`
- **Direct Messages** — private 1-on-1 conversations with unread indicators

### 💻 Code Playground
- **Monaco Editor** — full VS Code-quality editing experience in the browser
- **Multi-language support** — Python, Java, JavaScript (TypeScript, Rust, Go, C++ coming)
- **Rust backend** — Actix-Web service for fast, isolated code execution
- **Error parsing** — clean, readable error displays instead of raw stack traces

### 🎮 Arcade Center
- **Galaxy Match** — cosmic-themed memory puzzle game
- More coming: Word Chain, Code Trivia, Typing Race

### 🧘 Focus Mode
- **Gamified productivity** — earn XP for staying in focused sessions
- **Streak tracking** with persistent Supabase storage

### 🔒 Security
- Protected routes — all dashboard pages require authenticated sessions
- Next.js middleware redirects unauthenticated users to login instantly

---

## 🏗️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend Framework | Next.js 16 (App Router) · React 19 |
| Styling | Tailwind CSS v4 |
| Animations | Framer Motion |
| Code Editor | Monaco Editor |
| Database & Auth | Supabase (Postgres + Auth + Realtime) |
| Backend | **Rust — Actix-Web** (code execution service) |
| State Management | Custom Global Store (Context API) |
| Deployment | Netlify (Frontend) · Hugging Face (Backend) |

---

## 🏗️ Project Structure

```
Chill-Space/
├── Frontend/               # Next.js 16 application
│   ├── src/app/
│   │   ├── (auth)/         # Login, Signup pages
│   │   └── (dashboard)/    # Protected routes
│   │       ├── home/
│   │       ├── chat/       # Real-time messaging
│   │       ├── code/       # Code Playground
│   │       ├── games/      # Arcade Center
│   │       ├── focus/      # Focus Mode + XP
│   │       └── profile/
│   └── src/utils/          # Global store, middleware, utilities
├── backend/                # Rust Actix-Web code execution API
│   └── src/
├── Mobile/                 # React Native mobile app
├── Docs/                   # Technical architecture docs
│   ├── CODE_EDITOR.md
│   └── RUST_BACKEND.md
├── frontend.env.example
└── netlify.toml
```

---

## 🚀 Quick Start

### Frontend

```bash
cd Frontend
npm install
cp ../frontend.env.example .env.local
# Fill in your Supabase credentials in .env.local
npm run dev
```

### Backend (Rust)

```bash
cd backend
cargo run
```

### Environment Variables

```env
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
```

---

## 📡 Backend Deployment (Hugging Face)

```bash
git subtree pull --prefix backend hf main --squash
git subtree push --prefix backend hf main
```

---

## 📚 Documentation

| Doc | Description |
|-----|-------------|
| [`Docs/CODE_EDITOR.md`](Docs/CODE_EDITOR.md) | Code Playground architecture & Monaco integration |
| [`Docs/RUST_BACKEND.md`](Docs/RUST_BACKEND.md) | Rust Actix-Web backend setup & API reference |

---

## 🗺️ Roadmap

- [ ] TypeScript, Rust, Go, C++ in Code Playground
- [ ] Word Chain · Code Trivia · Typing Race (Arcade)
- [ ] Mobile app (React Native) — `Mobile/` folder
- [ ] Full backend integration with live deployment

---

## 🤝 Contributing

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:8b5cf6,100:0a0a0a&height=100&section=footer&animation=fadeIn" />

**Built by [Bhogeswara Rao T](https://github.com/Bhogi123-T) · Chennai, India**

*Connect. Code. Vibe.* 💜

</div>
