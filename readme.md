VIP ZONE 🧬

Turn your creativity into a programmable asset.

VIP ZONE is a Proof-of-Concept dApp built for the Story Protocol Surreal World Assets Buildathon. It provides a gamified interface for creators to mint, license, and track AI-generated content.

![Dashboard Preview]([Insert Screenshot Link Here])
⚡ Features

    Seamless IP Registration: Abstracts the complexity of the Story Protocol SDK into a single "Create" button.

    Dynamic Dashboard: Interactive "Control Room" to monitor asset valuation and social metrics.

    Automated Licensing: Pre-configured PIL (Programmable IP License) for viral remixing.

    Premium "Agent Mode": (Simulation) AI-driven updates for asset metadata.

🛠 Getting Started

    Clone the repo:
    Bash

git clone https://github.com/yourusername/vip-zone.git
cd vip-zone

Install dependencies:
Bash

npm install

Setup Environment: Create a .env.local file and add your WalletConnect ID:
Bash

NEXT_PUBLIC_WC_PROJECT_ID=your_id_here

Run the development server:
Bash

    npm run dev


📦 Production Dependencies (Main)

These are required for the app to run:

    Framework:

        next

        react

        react-dom

    Web3 & Blockchain:

        @rainbow-me/rainbowkit (Wallet connection UI)

        wagmi (Hooks for Ethereum)

        viem (Low-level Ethereum interactions)

        @tanstack/react-query (State management for Wagmi)

        @story-protocol/core-sdk (Story Protocol interactions)

    UI & Animations:

        framer-motion (The "Liquid Glass" animations)

        @heroicons/react (The icons used in the menu)
        

🛠️ Development Dependencies (Dev)

    Styling (The Engine):

        tailwindcss (We specifically forced version 3.4.17)

        postcss

        autoprefixer

    Language & Tools:

        typescript

        @types/react

        @types/node

        @types/react-dom

        eslint

        eslint-config-next
        
🏆 Hackathon Tracks

    Creative Front-End / UX: Focused on abstracting Web3 complexity into a "Liquid Glass" consumer experience.

