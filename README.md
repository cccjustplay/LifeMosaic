# 🧩 LifeMosaic (浮生拼图)

> **LifeMosaic** helps you perceive the flow of time. It transforms your daily fragments into a visualized life heatmap and AI-curated biography.
>
> **记录瞬间，感知岁月。** 这是一个隐私优先、本地运行的时光记录应用。

![License](https://img.shields.io/badge/license-MIT-blue.svg) ![Tech](https://img.shields.io/badge/tech-Next.js%20%7C%20IndexedDB%20%7C%20PWA-black)

## ✨ Core Philosophy (核心理念)

Life rushes by. We experience a lot, but remember little. LifeMosaic is designed to fix that:

1.  **Mosaic View**: Visualize your life as a GitHub-style contribution graph. Each tile represents a day, colored by your mood and decorated by your key events.
2.  **Frictionless Record**: No pressure to write long essays. Just pick a mood, rate the day, and jot down 3 bullet points.
3.  **AI Reflection**: Bring Your Own Key (BYOK). Let AI be your biographer, generating weekly and yearly reviews from your fragments.
4.  **Privacy First**: Your life belongs to you. All data lives in your browser (IndexedDB). No tracking, no unauthorized cloud uploads.

## 📸 Screenshots (Concept)

| Year View (Heatmap) | Daily Input (Card) | AI Review (Report) |
| :---: | :---: | :---: |
| *(Placeholders for Year View)* | *(Placeholders for Input)* | *(Placeholders for Review)* |

## 🚀 Features

- **The Mosaic System**: A 4-layer visual rendering engine (Color=Mood, Icon=Event, Border=Importance, Dot=Media).
- **Smart Input**: Drag & drop photos to auto-detect dates/locations (Web API).
- **AI Integration**: Plug in your OpenAI/Claude/Ollama keys to summarize daily logs and generate reports.
- **Local First**: Built on IndexedDB. Images are compressed and stored locally.
- **PWA Support**: Installable on iOS/Android via browser. Offline ready.

## 🛠 Tech Stack

- **Framework**: React / Next.js
- **State Management**: Zustand / Jotai
- **Local Database**: Dexie.js (IndexedDB wrapper)
- **UI Component**: TailwindCSS + Shadcn/UI
- **AI Integration**: Vercel AI SDK / LangChain.js

## 🗺 Roadmap

### Phase 1: The Foundation (Current Focus)
- [ ] Implement the Heatmap Visualization (Year/Month views).
- [ ] Build the "Mosaic" rendering logic (Mood/Icon/Border layers).
- [ ] Local storage implementation with Image compression.
- [ ] BYOK AI integration for text summarization.
- [ ] Mobile responsive design (Click vs Hover interactions).

### Phase 2: Synchronization
- [ ] Data Export/Import (JSON).
- [ ] Optional Sync Backend (CouchDB / Self-hosted compatible).
- [ ] "On This Day" feature.

### Phase 3 & 4: Native & Ecosystem
- [ ] Native App wrappers (Tauri/Capacitor).
- [ ] Desktop Widgets.
- [ ] Wechat Mini-program.

## 🤝 Contributing

This is a personal project driven by passion. PRs are welcome!
