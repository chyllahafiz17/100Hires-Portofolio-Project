# 100Hires-Portofolio-Project
---
## IDE Setup and Tool Integration
---
### Tools Installed
* Cursor IDE 
* Claude Code Extension (`anthropic.claude-code`)
* Codex Extension (`openai.chatgpt`)
* Git

### Steps Completed
1. Downloaded and installed Cursor IDE directly from `cursor.com`.
2. Navigated to the Extensions tab (Ctrl+Shift+X) to integrate the specified AI assistants.
3. Installed the Claude Code add-on and authenticated via the browser prompt.
4. Installed the Codex add-on and completed the OpenAI OAuth login process.
5. Created a new public repository on GitHub.
6. Initialized a local Git repository within the Cursor workspace, created this `README.md`, and documented the workflow.
7. Staged the files, committed the changes, and pushed the branch to the remote GitHub repository.

### Issues Encountered & Resolutions

* **Claude Code Marketplace Visibility:** The official Claude Code extension did not immediately populate in Cursor's standard marketplace search interface.
  * **Resolution:** I recognized this as a known indexing issue with the Cursor marketplace. Instead of relying on the search bar, I bypassed it by using the Command Palette to trigger the direct extension identifier (`cursor:extension/anthropic.claude-code`), which forced the installation.
* **Codex Naming Convention:** Searching strictly for "Codex" returned several third-party and community forks, making it unclear which was the intended target.
  * **Resolution:** I filtered the search results by publisher to locate the official tool. The correct official extension provided by OpenAI is currently registered under the identifier `openai.chatgpt`, branded as "Codex - OpenAI's coding agent." I verified the publisher before installing.
