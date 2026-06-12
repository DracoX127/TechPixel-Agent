Project Overview: TechPixel AI (PixelGen)
🎯 Executive Summary
TechPixel AI is a specialized, AI-powered workspace designed for Bloxd.io creators and the BloxdHub ecosystem. It bridges the gap between creative ideation and game-world integration by providing an AI-orchestrated pipeline for asset generation, community knowledge retrieval, and world scripting.

🛠 Core Capabilities
1. AI-Powered PixelGen Pipeline
Intelligent Prompt Enhancement: Raw user input is transformed into professionally structured, game-optimized prompts using LLMs.
Asset Lifecycle Management: A persistent gallery allows users to manage, preview, and perform bulk-exports of their generated game assets.
Context-Aware Generation: The engine is tuned to understand Bloxd.io specific aesthetic constraints, such as voxel art styles, isometric perspectives, and mob/item hierarchies.
2. Live Community Intelligence
Search-to-Generate Workflow: Built-in community search (Reddit/Fandom) allows users to research game mechanics or build styles without leaving the design environment.
Real-time Feed: A live, dashboard-integrated feed keeps users updated on Bloxd.io community news and wiki changes, ensuring creations are lore-accurate and trend-aware.
3. Agent-Orchestrated Support
BloxdHub Assistant: A specialized AI agent trained on game documentation, enchantment guides, and scripting syntax. It acts as an interactive "developer manual" for world development.
Multi-Agent Workflow: The system utilizes internal agents (memory filters, detector agents) to maintain long-term context about user preferences and project goals across sessions.
🖥 UI/UX Architectural Philosophy
"Terminal Aesthetic" Design System
The UI utilizes a "Dark-Mode Matrix" aesthetic designed for high-focus development environments:

Color Palette: A deep-night base (#05060e) with vibrant violet (#a78bfa), amber (#fbbf24), and cyan (#67e8f9) accents.
Typography: Strict use of monospaced fonts (JetBrains Mono) for technical data, balanced with Space Grotesk for readability.
Glassmorphism & Motion: High-fidelity glass panels (backdrop-filter) provide depth, while Framer Motion creates a "liquid" user experience through staggered entry animations and smooth layout transitions.
Key UI Components
Live Thinking Feed: Displays step-by-step reasoning logs, allowing users to see the "brain" of the AI in real-time as it researches or generates assets.
Terminal-Inspired Sidebar: A file-explorer style interface for managing chat threads, pinning critical conversations, and archiving project data.
Interactive Widgets: Dashboard components that provide live data (e.g., community feed, search widgets) without requiring page reloads.
⚙️ Technical Foundation
Orchestration: Built on React and Vite for high performance.
Backend & Data: Leverages Base44's backend-as-a-service for secure database operations, user authentication, and real-time activity tracking.
PDF Exporting: Advanced document generation allows users to export conversation history and research reports as professional-grade PDFs directly from the UI.
Persistence: Uses custom entity-based memory to ensure the AI "remembers" user world-building projects and scripting styles between sessions.
