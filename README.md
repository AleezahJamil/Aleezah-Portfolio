# Aleezah Jamil — AI Engineer Portfolio

A premium, cinematic portfolio website for **Aleezah Jamil** featuring an interactive 115-frame scroll-driven portrait animation, dark burgundy editorial aesthetics, and detailed showcases for AI, Machine Learning, and Backend Engineering projects.

---

## 🚀 Deployment & Hosting

- **Entry File:** `index.html`
- **Build Command:** *None required (Static HTML/CSS/JS)*
- **Output Directory:** `/` (Root directory)

### Deploying to GitHub Pages
1. Push this repository to GitHub.
2. Go to **Settings** > **Pages** in your GitHub repository.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
4. Select the `main` branch and `/ (root)` folder.
5. Click **Save**. Your site will be live at `https://<your-username>.github.io/<repository-name>/`.

---

## 💻 Running Locally

Since the site loads 115 PNG animation frames dynamically, serve the root directory with any standard HTTP web server:

### Option 1: Python HTTP Server (Recommended)
```bash
python -m http.server 8000
```
Then open `http://localhost:8000` in your web browser.

### Option 2: Node.js `npx serve`
```bash
npx serve .
```

### Option 3: VS Code Live Server
Open `index.html` in VS Code and click **Go Live** via the Live Server extension.

---

## 📁 Project Structure

```text
├── index.html          # Main entry file containing structure, styling, & scroll engine
├── frames/             # 115 scroll animation PNG frames (scene00001.png - scene00115.png)
├── .gitignore          # Git ignore rules for OS/IDE temp files
└── README.md           # Project documentation & deployment guide
```

---

## 🛡️ License

© 2026 Aleezah Jamil. All rights reserved.
