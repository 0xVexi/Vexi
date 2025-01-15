# Vexi Blockchain Powered by ElizaOS 🤖

<div align="center">
  <img src="./docs/static/img/bnjaanna.png" alt="Eliza Banner" width="100%" />
</div>

<div align="center">

📖 [Documentation](https://elizaos.github.io/eliza/) | 🎯 [Examples](https://github.com/thejoven/awesome-eliza)

</div>

## 🌍 README Translations

[中文说明](./README_CN.md) | [日本語の説明](./README_JA.md) | [한국어 설명](./README_KOR.md) | [Persian](./README_FA.md) | [Français](./README_FR.md) | [Português](./README_PTBR.md) | [Türkçe](./README_TR.md) | [Русский](./README_RU.md) | [Español](./README_ES.md) | [Italiano](./README_IT.md) | [ไทย](./README_TH.md) | [Deutsch](./README_DE.md) | [Tiếng Việt](./README_VI.md) | [עִברִית](https://github.com/elizaos/Elisa/blob/main/README_HE.md) | [Tagalog](./README_TG.md) | [Polski](./README_PL.md) | [Arabic](./README_AR.md) | [Hungarian](./README_HU.md) | [Srpski](./README_RS.md) | [Română](./README_RO.md) | [Nederlands](./README_NL.md) | [Ελληνικά](./README_GR.md)

## 🚩 Overview

<div align="center">
  <img src="./docs/static/img/eliza_diagram.png" alt="Eliza Diagram" width="100%" />
</div>

## ✨ Features of Vexi

🛠️ Seamless Integrations: Full-featured connectors for Discord and Twitter (X).

🔗 Model Agnostic: Support for every major AI model (Llama, Grok, OpenAI, Anthropic, Gemini, and more).

👥 Multi-Agent Collaboration: Engage in dynamic conversations with multiple agents and manage custom rooms.

📚 Document Interaction: Effortlessly ingest and interact with your files or databases.

💾 Memory & Storage: Persistent retrievable memory and document management.

🚀 Extensibility: Build your own actions, plugins, and client extensions.

📦 Plug-and-Play: Optimized to work out-of-the-box!

## 🎯 Use Cases for Vexi

🤖 Chatbots: Elevate your digital presence with intelligent chat responses.

🕵️ Autonomous Agents: Let Vexi handle tasks with minimal supervision.

📈 Business Automation: Streamline workflows and optimize processes.

🎮 Game NPCs: Bring characters to life in interactive gaming environments.

🧠 Trading Bots: Integrate Vexi into your trading strategies for smarter decisions.

## 🚀 Getting Started with Vexi

# Prerequisites

Python: 3.7+

Node.js: 18+

pnpm: Installed globally

Note for Windows Users: WSL 2 is required.


Use the Starter Kit (Recommended)

Clone the Vexi Starter Repository:


bash

Copy code

git clone https://github.com/vexios/vexi-starter.git  

cd vexi-starter  

Setup Environment Variables:


bash

Copy code

cp .env.example .env  

Install Dependencies and Start Vexi:


bash

Copy code

pnpm i && pnpm build && pnpm start 

Manually Start Vexi (Advanced)

Clone the Vexi Repository:


bash

Copy code

git clone https://github.com/vexios/vexi.git  

Checkout the Latest Release:


bash

Copy code

git checkout $(git describe --tags --abbrev=0)  

Setup the Environment File:


bash
Copy code
cp .env.example .env  
(Optional: Use JSON-based character files for managing multiple agents.)

Install Dependencies:

bash
Copy code
pnpm i  
pnpm build  
Start Vexi:

bash
Copy code
pnpm start  
Quick Web Access
Once Vexi is running, start the client to chat with your agent:

bash
Copy code
pnpm start:client  
Customization and Advanced Setup
Modify the Default Character: Edit src/defaultCharacter.ts or use:

bash
Copy code
pnpm start --characters="path/to/your/character.json"  
Integrate with X (Twitter): Update your character configuration:

json
Copy code
"clients": ["twitter"]  
Optional Sharp Installation: If startup errors occur, install Sharp:

bash
Copy code
pnpm install --include=optional sharp  
Automated Start Script
Run Vexi with a single command:

bash
Copy code
sh scripts/start.sh  
Community & Support
GitHub Issues: Report bugs or propose features.
Discord: Join the community to share your Vexi applications and collaborate

## Contributors

<a href="https://github.com/elizaos/eliza/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=elizaos/eliza" />
</a>

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=elizaos/eliza&type=Date)](https://star-history.com/#elizaos/eliza&Date)
