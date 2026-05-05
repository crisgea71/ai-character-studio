# 🎬 AI Character Studio

> Generate viral 3-clip video stories for any character — powered by AI

**AI Character Studio** is a web-based content creation tool that generates complete 3-clip Kling AI video stories for social media. Pick a character, choose a humor style and weekly theme, and get ready-to-film Kling prompts + captions for Instagram, TikTok, X, and YouTube Shorts.

🔗 **Live demo:** [ai-character-studio.netlify.app](https://ai-character-studio.netlify.app)

---

## ✨ Features

- 🎭 **6 built-in characters** — Grandpa, Baby CEO, Dramatic Cat, Karen, Confused Robot, Old Wizard
- ➕ **Add custom characters** — describe any character and the AI generates stories in their style
- 🎬 **3-clip story format** — Setup + Chaos + Punchline (~26 seconds total, ready to edit in CapCut)
- 😂 **5 humor styles** — Absurd-Ironic, Dry Humour, Slapstick, Dark Comedy, Wholesome
- 🎯 **9 weekly themes** — Technology, Nature, Sport, Vacation, Animals, Social, Food, Shopping, Kids
- 📱 **4 platforms** — Instagram, TikTok, X (Twitter), YouTube Shorts
- 📋 **Copy-ready content** — Kling prompts, captions, hashtags, story polls, sound suggestions
- 📅 **Mac Calendar reminders** — .ics file for posting schedule
- 📚 **Story history** — never repeats the same situation
- 🔒 **Paywall** — 3 free stories, password for full access

---

## 🚀 How It Works

```
1. Choose your character
2. Pick humor style + weekly theme
3. Click a day of the week
4. Get 3 complete story ideas
5. Each story = 3 Kling AI prompts ready to film
6. Edit clips in CapCut
7. Post on all platforms with ready-made captions
```

---

## 🛠️ Tech Stack

- **Frontend** — Vanilla HTML, CSS, JavaScript (single file, no framework)
- **Backend** — Netlify Functions (Node.js serverless)
- **AI** — Groq API (Llama 3.3 70B)
- **Hosting** — Netlify (free tier)

---
---

## 🎨 Development Approach

This project showcases **AI-assisted rapid prototyping**:

- ⚡ Built in **3 days** from concept to deployed product
- 🤖 Developed with **Claude AI** assistance (code generation, debugging, optimization)
- 🎯 Focus: **solve real creator problems fast**, not perfect code
- 💰 **$0 cost** to build (free APIs + free hosting)

**Philosophy:** AI is a productivity tool (like calculators for math). I build useful products quickly by leveraging AI for code, focusing my energy on product strategy and user experience.

---

## 📁 Project Structure

```
ai-studio/
├── index.html              # Main app (frontend)
├── netlify.toml            # Netlify configuration
└── netlify/
    └── functions/
        └── generate.js     # Serverless function (API calls)
```

---

## 🔧 Setup & Deploy

### 1. Clone the repo
```bash
git clone https://github.com/YOUR_USERNAME/ai-character-studio.git
cd ai-character-studio
```

### 2. Add your Groq API key
Open `netlify/functions/generate.js` and replace:
```javascript
const GROQ_KEY = 'your_groq_api_key_here';
```
Get a free key at [console.groq.com](https://console.groq.com)

### 3. Set your access password
In `index.html`, find and change:
```javascript
var ACCESS_PASS = 'your_password_here';
```

### 4. Deploy to Netlify
- Go to [netlify.com](https://netlify.com)
- Drag and drop the `ai-studio` folder
- Done! Your app is live.

### 5. Run locally
```bash
cd ai-studio
python3 -m http.server 3000
# Open http://localhost:3000
```

---

## 💡 Content Strategy

Each story follows the **3-clip viral formula:**

| Clip | Name | Duration | Purpose |
|------|------|----------|---------|
| Clip 1 | The Setup | 8-9 sec | Character confidently starts something ridiculous |
| Clip 2 | The Chaos | 9-10 sec | Everything goes wrong, escalates |
| Clip 3 | The Punchline | 6-8 sec | Twist ending + dignity moment |

**Total: ~26 seconds** — perfect for Instagram Reels, TikTok, YouTube Shorts

---

## 📊 Posting Strategy

```
Film in Kling → Edit in CapCut → Post on TikTok first
→ Wait 30 min → Instagram → X → YouTube Shorts
```

---

## 🔒 Access Control

- **Free:** 3 story generations
- **Full access:** Password protected
- Change the password in `index.html`: `var ACCESS_PASS = 'your_password';`

---

## 📄 License

MIT License — free to use and modify.

---

## 🙏 Credits

Built with [Groq](https://groq.com) · Deployed on [Netlify](https://netlify.com) · Videos generated with [Kling AI](https://klingai.com)

---

---

## 👩‍💻 About the Developer

**Cristina Geafar**  
Frontend Developer | AI-Powered Web Apps | Rapid Prototyping

- 🌐 Portfolio: [www.cristinageafar.com](https://www.cristinageafar.com)
- 💼 GitHub: [@crisgea71](https://github.com/crisgea71)
- 📧 Contact: [your-email@example.com] *(add your real email sau șterge linia)*
- 📍 Location: Constanța, Romania (open to remote/relocation)

**Looking for:**
- Freelance AI integration projects
- Remote frontend/AI development roles
- Opportunities in UAE/Oman tech ecosystems

---

**⭐ If this project helped you, star the repo!**  
**💬 Questions? Open an issue or reach out directly.**

---

*Last updated: May 2026*
