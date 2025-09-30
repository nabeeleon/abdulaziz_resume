## Abdulaziz Tawfik — Cybersecurity Engineer Resume Site

Static, responsive resume website with dark mode, animations, and interactive UI.

### Local Development

1. Open a terminal in this folder
2. Run a local server:
   - Python 3: `python -m http.server 8000`
   - Node: `npx serve .`
3. Visit `http://localhost:8000`

### Deploy to Vercel

Option A: One‑click (recommended)
1. Push this project to GitHub/GitLab/Bitbucket
2. Go to Vercel and “New Project” → import the repo
3. Framework preset: “Other” (no build step)
4. Output/public directory: `/` (root)
5. Deploy

Option B: Vercel CLI
```
npm i -g vercel
vercel login
vercel --prod
```

### Project Structure

```
index.html      # Site markup
styles.css      # Design system, animations, responsive rules
script.js       # Interactivity, theme toggle, effects
vercel.json     # Vercel config (static)
```

### Meta

- Author: Abdulaziz Tawfik
- License: MIT

