# vibeegames

vibeegames is an **open GitHub organization** dedicated to creating **AI‑driven games** using **vibe coding**. Anyone can join, add a repo, and build a game—**as long as every line of code is generated via AI** (no manual typing!).

---

## 🎮 What Is Vibe Coding?  
Vibe coding means you never write code by hand—instead, you prompt an AI assistant to generate every function, class, and asset. This keeps your workflow fresh, creative, and 100% “vibe.”

---

## 🚀 Getting Started  

1. **Join the Org**  
   - Click **“Join vibeegames”** on our GitHub page or open an issue to request membership.  
2. **Create a New Repo**  
   - Name it `game-<your-game-name>` (e.g. `game-space-explorer`).  
   - Add a top‑level `README.md` describing your game concept and AI‑prompt workflow.  
3. **Code Exclusively with AI**  
   - Use an AI assistant for every line.  
   - **No manual edits**—we’re tracking your prompts and AI responses, not your keyboard strokes!

---

## 🛠️ Tools & Setup  

### 1. VS Code + Cline Extension  
- Install VS Code:  
  ```bash
  https://code.visualstudio.com/
  ```  
- Add **Cline** (the AI‑assistant extension):  
  ```bash
  code --install-extension clinedev.cline
  ```

### 2. Claude Sonnet (AI Model)  
- Access **Claude Sonnet** via your preferred API key.  
- In your VS Code `settings.json`, point Cline to Sonnet:
  ```json
  {
    "cline.apiProvider": "vscode-lm",
    "cline.model": "claude-sonnet-v1",
    "vscode-lm.apiKey": "<YOUR_CLAUDE_API_KEY>"
  }
  ```

---

## 🎓 Student Perks: Free AI Access  
If you’re a student, you can unlock **free AI‑powered coding** through:  
1. **GitHub Student Developer Pack**  
   - Sign up at https://education.github.com/pack  
   - Receive **GitHub Copilot Pro** at no cost.  
2. **VS Code LM API**  
   - Use your Copilot Pro credentials as your VS Code LM API key.  
   - Configure Cline to point at the VS Code LM endpoint—so Claude Sonnet runs for free!

---

## 📋 Repository Guidelines  

- **Game Scope**: Any genre or engine—2D, 3D, text‑based, physics puzzles, etc.—as long as it’s vibe‑coded.  
- **Licensing**: Default to **MIT**. You can choose another OSI‑approved license, but be explicit in your repo.  
- **Documentation**:  
  - Include your **prompt log** (e.g. `prompts.log`) so reviewers can see how you drove the AI.  
  - Write a clear **README** with play instructions, controls, and credits.  
- **Assets**: Generated via AI (e.g. DALL·E, Stable Diffusion) or hand‑crafted—but your game logic must be AI‑written.

---

## 🤝 Code of Conduct  
We follow the [Contributor Covenant v2.1](https://www.contributor-covenant.org/). Please be respectful, inclusive, and constructive.

---

## 🙌 How to Contribute  

1. **Fork & Clone** your `game-…` repo locally.  
2. **Prompt your AI** via Cline to scaffold your game structure, assets, and logic.  
3. **Commit** often, with messages reflecting your prompts:  
   ```plaintext
   feat: Prompted "create player movement system in JavaScript with arrow-key controls"
   ```  
4. **Push** to your remote—CI will auto‑build, run tests, and deploy demos (if configured).  
5. **Submit a PR** to `main` if you want help or review, or simply publish and share your GitHub Pages link.

---

## 📜 License  
Unless otherwise noted, all repos in vibeegames default to the **MIT License**. See [LICENSE‑MIT](https://opensource.org/licenses/MIT) for details.  
