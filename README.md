# 🪄 Prompt AI Optimizer

> **A professional AI-powered prompt engineering tool** built with React, featuring live animated wallpapers, multi-domain optimization, chat assistant, and analytics dashboard.

---

## 📌 Overview

**Prompt AI Optimizer** is a browser-based tool that helps users craft high-quality prompts for AI models. It auto-detects the domain of your input, applies structured guidelines, and scores the output for clarity, specificity, and actionability — all in a visually immersive interface.

**Developed by:** Neelimapasala

---

## ✨ Features

### 🎯 Core Functionality
- **Prompt Optimizer** — Paste any rough prompt and get a structured, domain-optimized version with quality scoring
- **Auto Domain Detection** — Automatically identifies your prompt's domain (creative, code, business, research, etc.)
- **Quality Scoring** — Rates your refined prompt from 0–100% based on clarity, structure, specificity, and more
- **Template Library** — 8 ready-to-use prompt templates across writing, code, business, legal, and more
- **History & Favorites** — Browse past optimized prompts and save your best ones

### 🤖 AI Chat Assistant
- Floating chat panel for prompt engineering tips and guidance
- Contextual responses based on your current domain and quality score

### 🎨 Live Animated Wallpapers
8 dynamic canvas-based backgrounds to personalize your workspace:

| Theme | Description |
|---|---|
| Neural Network | Abstract particle network with connections |
| Cosmic Space | Deep space particle field |
| Matrix Code | Digital green rain effect |
| Aurora Borealis | Northern lights atmosphere |
| Ocean Deep | Underwater blue particles |
| Sunset Horizon | Warm gradient glow |
| Mystic Forest | Green woodland ambiance |
| Galaxy Core | Purple cosmic starfield |

### ⚙️ Settings & Export
- Adjustable **temperature** and **max tokens** parameters
- Export optimized prompts as `.txt`, `.md`, or `.json`
- Download prompts with embedded metadata (domain, score, timestamp)

### 📊 Analytics Dashboard
- Total prompts processed
- Time saved tracker
- Average quality score
- Domain distribution bar chart

---

## 🗂️ Project Structure

```
prompt-ai-optimizer/
│
├── index.html          # Single-file app (React + Tailwind via CDN)
│
└── README.md           # Project documentation
```

> This is a **single-file application** — all logic, styles, and components are contained in `index.html`.

---

## 🚀 Getting Started

### Prerequisites
No build tools or package installation required. Just a modern web browser.

### Running Locally

1. **Clone or download** the repository:
   ```bash
   git clone https://github.com/your-username/prompt-ai-optimizer.git
   cd prompt-ai-optimizer
   ```

2. **Open `index.html`** directly in your browser:
   ```bash
   # macOS
   open index.html

   # Windows
   start index.html

   # Linux
   xdg-open index.html
   ```

3. That's it! No server setup needed.

---

## 🧠 Supported Domains

| Domain | Use Cases |
|---|---|
| ✨ Creative Writing | Poetry, stories, scripts, dialogue, fiction |
| 💻 Code Generation | Functions, components, algorithms, APIs |
| 📊 Business | Strategy, proposals, market analysis, ROI |
| 🔬 Research | Academic papers, hypothesis, methodology |
| 📚 Education | Lessons, tutorials, study guides, curricula |
| ⚙️ Technical | System design, API docs, infrastructure |
| 📢 Marketing | Campaigns, ads, social media, conversions |
| ⚖️ Legal | Contracts, policies, compliance documents |

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **React 18** | UI components and state management |
| **Tailwind CSS** | Utility-first styling |
| **HTML5 Canvas** | Live animated wallpapers |
| **Babel Standalone** | In-browser JSX transpilation |
| **Font Awesome 6** | Icons |
| **Google Fonts (Inter)** | Typography |

All dependencies are loaded via **CDN** — no `npm install` needed.

---

## 📖 How to Use

1. **Navigate** to the **Optimizer** page from the nav bar
2. **Type or paste** your rough prompt into the text area
3. The tool **auto-detects** the domain — or select one manually
4. Click **Optimize Prompt**
5. Review the **refined prompt** and **quality score**
6. **Copy**, **save to favorites**, or **export** as a file

### 💡 Tips for Better Prompts
- Be specific about your desired outcome
- Include context and background information
- Define the target audience
- Specify output format (JSON, markdown, plain text)
- Add examples when possible
- Set clear constraints or limitations

---

## 🖥️ Pages

| Page | Description |
|---|---|
| **Home** | Overview with stats and quick domain cards |
| **Optimizer** | Main prompt engineering tool with history & favorites tabs |
| **Templates** | Browse and load 8 ready-made prompt templates |
| **Analytics** | View your usage stats and domain distribution |

---

## 🔮 Future Improvements

- [ ] Integrate a real AI API (Anthropic Claude, OpenAI GPT) for deeper optimization
- [ ] User authentication and cloud sync for history/favorites
- [ ] More templates and domain-specific fine-tuning
- [ ] Side-by-side A/B comparison of prompt versions
- [ ] Browser extension version
- [ ] Dark/light theme toggle

---

## 📄 License

© 2026 Prompt AI Optimizer | Developed by **Neelimapasala** | All Rights Reserved.

---

## 🙌 Acknowledgements

- [React](https://react.dev/) — UI library
- [Tailwind CSS](https://tailwindcss.com/) — CSS framework
- [Font Awesome](https://fontawesome.com/) — Icon library
- [Google Fonts](https://fonts.google.com/) — Inter typeface
