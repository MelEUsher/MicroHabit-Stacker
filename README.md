# Micro-Habit Stacker 

MicroHabit Stacker is a lightweight, performance-optimized single-page application built with React and TypeScript to help users build consistent daily habits through micro-actions.

This application emphasizes clean component architecture, strict typing, and production-grade deployment practices. Engineered with performance optimization and production-grade deployment practices in mind.

---

## Live Demo

https://microhabit-stacker.netlify.app/

---

## Technical Highlights
	-	Built with React + TypeScript using modular component structure
	-	Styled using Tailwind CSS
	-	Client-side state persistence via localStorage
	-	Production deployment via Netlify
	-	Achieved Lighthouse performance score of 100 (desktop & mobile)

---

## 🚀 What It Does
- Pick a **category** and choose micro-habits.
- Daily checklist to **mark habits done/not done.**
- **Streaks + XP** to reward consistency.
- **Tower view** for last 7 days.
- **Badges** for milestones.
- Optional in-tab **reminders** and `.ics` export to calendar.

---

## 🛠 Tech Stack
- **HTML / CSS / JavaScript** (vanilla, no build step)
- **localStorage** for data
- Assets in `public/assets`
- **Deployment** → Vercel (teacher will guide)

---

## 📂 Project Structure

**Where you work:**
- `components/` → UI features  
- `utilities/` → helper logic  
- `data/` → JSON + docs  
- `app.js` → main app logic  
- `styles.css` → global styles  

**Please don’t edit (setup only):**
- `index.html`  
- `.editorconfig`, `.prettierrc`, `.gitignore`  
- `vercel.json`, `LICENSE`, `CONTRIBUTING.md`  
- `.github/` workflows  

---

## 🖥 Run Locally
 This project runs entirely in the browser. You just need a simple local server so `fetch()` calls (e.g., `data/habits.json`) work correctly.  

⚠️ If you try to double-click `index.html` and see JSON or CORS errors, it means you need to use one of the other methods below instead.
NOTE: The port number may vary depending on the method/tool you use. Any http://localhost:<port> that is defaulted works.

### OPTION 1 - Simple Local Server
**macOS/Linux**
cd project-folder
python3 -m http.server 8000
Go to: http://localhost:8000


**Windows (Powershell)**
cd path\to\project
py -m http.server 8000
Go to: http://localhost:8000 

### OPTION 2 - VS Code Live Server (easiest for beginners)
 - Install the Live Server extension in VS Code.
 - Right-click index.html → Open with Live Server.
 - A browser tab will open at http://localhost:5500 (default).
 - Live Server auto-reloads whenever you save changes.

### Option 3 — Node.js (if installed, not necessary for this project - but useful as an alternative for viewing)

```bash
npx serve .
# or
npx http-server .
```

### 🧭 How We Work

- Pick a GitHub issue (ticket).
- Create a branch for that issue.
- Keep changes small and focused.



### 🌱 Branch / PR Flow
- git checkout main 
- git pull
- git checkout -b <YOUR-BRANCH-NAME> 
- git add .
- git commit -m "Commit Message"
- git push -u origin <YOUR-BRANCH-Name>

Then → Open PR → link the issue → move ticket to request review.

### ✅ Definition of Done

- Runs locally at `http://localhost:<port>` (via Python server, Live Server, or Node) with no console errors.
- Keyboard accessible (tab through controls; visible focus).
- Uses helpers in utilities/state.js (no direct localStorage inside components).
- Looks OK at mobile width (375px) in DevTools.
- PR links its ticket.

### 🧪 Quick AI Prompts (for Copilot) - If you’re stuck, here are some quick example prompts you can paste into AI tools for guidance

“Implement calculateCurrentStreak(days) in utilities/streaks.js. Explain edge cases.”

“Render habit chips from data/habits.json into #habit-picker. Explain steps.”

“Add :focus-visible outline for interactive elements in styles.css.”

“Create toast(message) in utilities/notify.js (2s auto-remove).”

### 🗂 Git Commands (Cheat Sheet)

- git clone <repo-url.git> → copies the online repository to your local machine

- git fetch origin → check for updates

- git status → see changes

- git pull → bring updates into local

- git checkout -b new-branch → start a new branch

- git add . → stage all changes

- git commit -m "message" → save staged changes

- git push -u origin branch-name → send branch online

- git branch → list local branches

### 🤝 Contributing

See CONTRIBUTING.md for full guidelines.
Work happens on branches + PRs linked to GitHub Project tickets.
---

## Contributors

- Ellery Dorroh (@ellery_d, @EDORROH, Github)
- Corey Knauer (@coreyk in discord, @cwik1, Github)
- John Caldwell (johncaldwell4 in discord, @johncaldwell4, Github)
- Melissa Usher (@MelissaU in discord, @MelEUsher in Github)
- Rebecca A. Stone (@beckstone on discord and Github)
- Abu H Kamal(@kamal3235, kamal3235 in Github)
- Christina Lerch (@Chris-60191, sunny0221 in github)
- Hope Barnett(@HopeBarnett_04433 on Discord)(@Hope-Barnett on Github)
- Steven Garcia (@Steniel in discord, @Stevengdev1 in github)


---

> "Future Focused: Tiny Tech for Your Future Self" by keeping it **Simple**, making it **Lovable**, and finishing it **Complete**.
