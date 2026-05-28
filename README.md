# 🚀 Kids Learning App Launcher

A colourful, kid-friendly landing page that **automatically detects** HTML apps from your `embed_files/` folder using the GitHub API — no server needed!

---

## 📁 Repository Structure

```
your-repo/
├── index.html          ← The landing page (edit GITHUB_USERNAME + GITHUB_REPO here)
├── README.md
└── embed_files/        ← Drop your .html app files here!
    ├── math-quiz.html
    ├── spelling-bee.html
    └── any-other-app.html
```

---

## ⚙️ Setup (5 steps)

### 1. Fork or create a new GitHub repository
Make it **public** so GitHub Pages works.

### 2. Add your files
- Upload `index.html` to the **root** of your repo
- Create a folder called `embed_files/`
- Drop your `.html` app files inside `embed_files/`

### 3. Edit `index.html`
Open `index.html` and find these two lines near the bottom:

```js
const GITHUB_USERNAME = 'YOUR_USERNAME';   // ← your GitHub username
const GITHUB_REPO     = 'YOUR_REPO_NAME';  // ← your repo name
```

Change them to match your account, for example:
```js
const GITHUB_USERNAME = 'mrsmith';
const GITHUB_REPO     = 'class-apps';
```

### 4. Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages**
2. Under *Source*, choose **Deploy from a branch**
3. Select `main` branch, `/ (root)` folder
4. Click **Save**

GitHub will give you a URL like:
`https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

### 5. Done! 🎉
Visit your Pages URL. Every `.html` file in `embed_files/` will appear as a card in the carousel automatically.

---

## ➕ Adding New Apps

Just upload a new `.html` file to the `embed_files/` folder on GitHub.  
The landing page auto-detects it via the GitHub Contents API — **no code changes needed**.

---

## 🎨 Customising

| What | Where in `index.html` |
|------|-----------------------|
| Page title | `<title>` tag and `<h1>` |
| Subtitle text | `.subtitle` paragraph |
| Card emojis | `CARD_EMOJIS` array in the script |
| Colour blobs | `.blob` CSS classes |

---

## 🔒 Notes

- Repository must be **public** for the GitHub API to work without authentication
- Apps are displayed in an iframe preview — complex apps with external dependencies may not preview perfectly, but will work when opened directly
- The carousel supports mouse clicks, keyboard arrow keys, and touch swipe on mobile
