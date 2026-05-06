# 🗂️ Ops Assistant

A friendly, AI-powered Operations & Admin assistant built with HTML and Claude AI. Supports text chat, voice input, file uploads, and text-to-speech responses.

---

## ✨ Features

- **💬 Chat Interface** — Ask anything related to your day-to-day ops work
- **🎤 Voice Input** — Tap the mic, speak your question, and it sends automatically
- **🔊 Text-to-Speech** — The assistant reads its responses aloud
- **📎 File Uploads** — Attach `.txt`, `.csv`, `.pdf`, or `.md` files for summarization and analysis
- **⚡ Quick Actions** — One-tap chips for common tasks like drafting emails, summarizing docs, and planning your week
- **🧠 Conversation Memory** — Remembers the full chat context within each session

---

## 🚀 Getting Started

### View it live

Once deployed to GitHub Pages, open your browser and go to:

```
https://YOUR-USERNAME.github.io/ops-assistant
```

### Add to your Android phone

1. Open the link above in **Chrome on Android**
2. Tap the **3-dot menu** → **"Add to Home Screen"**
3. It will appear as an app icon on your phone

Or use **MIT App Inventor** to package it as a native APK:
1. Go to [appinventor.mit.edu](https://appinventor.mit.edu)
2. Create a new project and add a **WebViewer** component
3. Set the HomeUrl to your GitHub Pages link
4. Build → Download APK → Install on your phone

---

## 🛠️ Deployment (GitHub Pages)

1. Fork or clone this repository
2. Rename `ops-assistant.html` to `index.html` (already done if you cloned this repo)
3. Go to **Settings → Pages**
4. Set source to the `main` branch
5. Your app will be live at `https://YOUR-USERNAME.github.io/ops-assistant`

---

## 🎤 Voice Chat

Voice input uses the browser's built-in **Web Speech API**.

- **Best supported in:** Google Chrome, Microsoft Edge
- **Microphone permission** is required — allow it when prompted
- Speech is transcribed and sent automatically when you stop talking
- The AI response is read aloud using the device's text-to-speech engine

---

## 📋 Quick Actions

| Button | What it does |
|---|---|
| 📄 Summarize doc | Summarizes an uploaded or pasted document |
| ✉️ Draft email | Helps write a professional email |
| 📊 Analyze data | Interprets data and gives key insights |
| 🗓️ Plan my week | Helps prioritize and structure your week |
| 📋 Meeting agenda | Creates a standup or meeting agenda |
| 📝 Process doc | Writes process documentation |

---

## 🔧 Tech Stack

- **Frontend:** Pure HTML, CSS, JavaScript (no frameworks)
- **AI:** [Anthropic Claude API](https://www.anthropic.com) (claude-sonnet-4)
- **Voice:** Web Speech API (SpeechRecognition + SpeechSynthesis)
- **Hosting:** GitHub Pages

---

## 📁 File Structure

```
ops-assistant/
├── index.html       # Main app (all-in-one HTML file)
└── README.md        # This file
```

---

## 🔒 Privacy

- Conversations are not stored anywhere permanently
- Each session starts fresh with no memory of previous sessions
- Voice input is processed entirely by your browser — audio is never sent to any server

---

## 📄 License

MIT License — free to use and modify for personal or commercial projects.
