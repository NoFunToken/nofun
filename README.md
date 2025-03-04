# NOFUN 💊

<div align="center">
  <img src="./docs/static/img/pfp.png" alt="" width="100%" />
</div>

## ✨ Features

-   🛠️ Full-featured Twitter
-   🔗 Support for openai models
-   🤖 AI Chatbot Integration: Powered by the nofun AI chatbot, delivering sarcastic, no-nonsense responses.
-   🚀 Solana-Powered: High-speed, low-cost transactions for a seamless user experience.
-   💼 Community-Centric Utility: A straightforward, efficient token designed to engage without the hype.
-   🚀 Custom CA – Set both the start and end of your contract address for full customization.
-   🛡️ Anti-Snipe Launcher – Drop on Pump.fun without getting sniped, ensuring a fair launch for devs and buyers.
-   📦 Just works!

## 🎯 Use Cases

-	🤖 Deadpan Chatbots: Perfect for creating sarcastic, no-nonsense AI interactions that reject fun and focus on efficiency.
-	🚫 Anti-Fun Ecosystems: Power projects that embrace seriousness and steer clear of hype and memes.
-	📊 Straightforward Business Tools: Use the nofun AI for handling tasks and processes with brutal honesty and zero fluff.
-	🎮 Dry-Humor NPCs: Integrate nofun AI into games for NPCs that deliver dry, sarcastic, and unapologetically blunt dialogue.

## 🚀 Quick Start

### Prerequisites

-   [Python 2.7+](https://www.python.org/downloads/)
-   [Node.js 22+](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
-   [pnpm](https://pnpm.io/installation)

### Edit the .env file

Copy .env.example to .env and fill in the appropriate values

```
cp .env.example .env
```

### Automatically Start NOFUN

This will run everything to setup the project and start the bot with the default character.

```bash
sh scripts/start.sh
```

### Edit the character file

1. Open `packages/agent/src/character.ts` to modify the default NOFUN. Uncomment and edit.

### Manually Start NOFUN

```bash
pnpm i
pnpm build
pnpm start

# The project iterates fast, sometimes you need to clean the project if you are coming back to the project
pnpm clean
```

#### Additional Requirements

You may need to install Sharp. If you see an error when starting up, try installing it with the following command:

```
pnpm install --include=optional sharp
```

### Community & contact

-   [GitHub Issues](https://github.com/NoFunToken/nofun/tree/main/github). Best for: bugs you encounter using NOFUN, and feature proposals.
-   [X.com](https://x.com/home). Best for: sharing your thoughts and engaging with the community.
