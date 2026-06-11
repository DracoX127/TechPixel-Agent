# TechPixel Agent (v1.1) — Bloxd.io Dev Assistant (v1.1)

TechPixel Agent is a specialized, terminal-inspired integrated development environment (IDE) and AI assistant tailored exclusively for **Bloxd.io** modding and scripting via the **WorldCode** framework. Driven by an optimized execution model, it helps creators draft, test, and deploy custom game mechanics up to 10x faster.

---

## 🖥️ Complete Feature Breakdown

### 🛠️ Native WorldCode Templates (One-Click Initialization)
The workspace features a grid of pre-configured code boilerplates ready to run or modify instantly:
* **`killstreak.js`**: Generates a kill streak reward system for tracking consecutive player kills and awarding custom scaling rewards.
* **`spawn_entity.js`**: Implements spatial coordinate parsing to dynamically spawn entities at a player's exact position.
* **`team_balance.js`**: Provides server-side auto-balancing algorithms for competitive PvP matchmaking.
* **`shop_gui.js`**: Builds an interactive graphical user interface featuring multiple item slots and support for custom in-game currencies.
* **`api_lookup.ts`**: A dedicated utility to instantly reference, explain, and query the latest Bloxd.io WorldCode API functions.
* **`leaderboard.js`**: Sets up volatile, round-based competitive data tracking that automatically resets at the end of each round.

### 🧠 Advanced Agent Runtime & Search Controls
Fine-tune how the AI processes your scripts using built-in bottom-bar toggles:
* **Runtime Core Engine**: Powered by the `gpt-4o` model optimized for complex programming and logic debugging.
* **Granular Search Modes**: 
  * `auto`: Automatically scales context depth based on query complexity.
  * `deep`: Conducts exhaustive logical code audits and deeper multi-step reasoning.
  * `balanced`: Strikes an efficient middle ground between rapid generation speed and analytical depth.
* **`web:on` (Always-On Web Search)**: An integrated live-sync engine that continuously crawls live game update logs and external repositories during code generation to prevent generic API hallucinations.
* **`memory: active`**: A persistent memory core that tracks terminal history and active file schemas across separate conversational threads.

### 🎛️ Terminal-Inspired IDE UI Layout
* **Unified Sidebar Explorer**: Includes an organizational system featuring:
  * A dedicated `+ new_conversation()` button to clear scopes and initialize fresh tasks.
  * A `CHATS` repository keeping your workspace clean, categorized by `// World Code` protocols.
* **ASCII Terminal Branding**: Features a distinctive retro matrix/terminal layout displaying the `TECHPIXEL` ASCII block logo upon initialization.
* **Command-Line Interface (CLI) Prompt Bar**: Supports rich-text natural language queries (`"ask anything about bloxd.io, worldcode, mods..."`) combined with keyboard shortcut execution (`Ctrl + Enter` or `[run]` button) to keep your workflow fluid.
* **User Profile & Cloud Connection Profile**: Features a persistent connection status panel (`TECHPIXEL AI · CONNECTED`) tracking the active developer's profile and credentials securely at the base of the sidebar.

---

## ⚙️ Workspace Configuration Overview

```ini
[SYSTEM_ENVIRONMENT]
version       = "1.1"
engine_core   = "gpt-4o"
target_scope  = "Bloxd.io / WorldCode"
web_search    = "ENABLED (Live Sync)"
ai_memory     = "ACTIVE (Persistent)"
bash_terminal = "techpixel-ai"
