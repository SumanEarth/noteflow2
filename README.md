# ✦ NoteFlow 2.0

Markdown-first note-taking with multi-provider AI and GitHub Gist sync.

## Features

- 📝 **Full Markdown editor** — live split view like Obsidian/Joplin
- 🤖 **Multi-provider AI** — Claude, OpenRouter (free), Ollama (local), OpenAI, Gemini
- ☁️ **GitHub Gist sync** — auto every 5 mins + on tab close
- 🔒 **PIN lock screen**
- 📱 **Mobile responsive** — bottom nav with Edit/Preview/AI tabs
- 🌙 **Auto dark/light mode**
- 🔍 **Full-text search**
- ⌨️ **Keyboard shortcuts** — Ctrl+B, Ctrl+I, Tab indent, auto-continue lists
- ✅ **Interactive checkboxes** in preview
- 📊 **Tables, code blocks, blockquotes** with syntax highlighting

## AI Quick Actions
- 📋 Summarize · ✨ Improve · 🇧🇩 Bangla translation
- 💻 Code Help · 🐛 Debug · ✦ Generate from prompt
- • Make Bullet List · ⊞ Make Table · 📖 Explain · ↕ Make Longer

## Free AI Options
| Provider | Free? | How |
|----------|-------|-----|
| OpenRouter | ✅ Free models | No key needed for some |
| Ollama | ✅ Local | Run on your PC via Tailscale |
| Claude | Free tier | console.anthropic.com |
| Gemini | Free tier | aistudio.google.com |
| OpenAI | Paid | platform.openai.com |

## Deploy to Vercel

### From PC
```bash
git init && git add . && git commit -m "NoteFlow 2.0"
git remote add origin https://github.com/YOUR_USERNAME/noteflow2.git
git push -u origin main
```
Then import at vercel.com → Deploy.

### From Phone
1. Install GitHub Mobile
2. Create repo `noteflow2`
3. Upload `index.html` + `vercel.json`
4. Go to vercel.com → Import → Deploy ✅

## Setup

1. **PIN**: Default is `1234` — change in ⚙ Settings
2. **AI**: Click ✦ AI → select provider → paste API key
3. **Sync**: ⚙ Settings → GitHub token → Save & Sync ↑
4. **Auto-sync**: Enable in Settings (every 5 mins + on tab close)

## Keyboard Shortcuts
| Key | Action |
|-----|--------|
| Ctrl+N | New note |
| Ctrl+B | Bold |
| Ctrl+I | Italic |
| Tab | Indent |
| Enter in list | Continue list |

## File Structure
```
noteflow2/
├── index.html    ← entire app (single file)
├── vercel.json   ← Vercel config
└── README.md
```

## License
MIT
