# 🚀 **Lazorkit Gasless Solana Wallet**

**A high-quality starter template for building seedless and gasless Solana apps using the Lazorkit SDK.**


---

🔗 Quick Links

🌐 **Live Demo:** **https://lazorkit-gasless-solwallet-demo.vercel.app**

🎥 **Video Demo:** **(Add YouTube link here)**



---

⚙️ Quick Start Guide

**1. Installation**

git clone https://github.com/Saroz900/lazorkit-gasless-solwallet-demo.git
cd lazorkit-gasless-solwallet-demo
npm install


---

**2. Environment Setup**

**Create a .env.local file and add:**

NEXT_PUBLIC_LAZORKIT_PROJECT_ID=your_project_id
NEXT_PUBLIC_SOLANA_RPC=https://api.devnet.solana.com


---

**3. Run the App**

npm run dev

**App will be live at:** **http://localhost:3000**


---

📖 Step-by-Step Tutorials

**1. Create a Passkey Wallet**

**Lazorkit replaces traditional seed phrases with secure biometric authentication.**

const wallet = await lazorkit.createPasskey();
// Uses FaceID / TouchID to generate a secure wallet instantly

**✔ No seed phrase**
**✔ No wallet installation**
**✔ Instant onboarding**


---

**2. Trigger a Gasless Transaction**

**Transactions are sponsored using a Paymaster, so users don’t need SOL.**

const signature = await lazorkit.sendGaslessTransaction(tx);
// Users can transact with 0 SOL balance

**✔ Zero gas for users**
**✔ Better UX for non-crypto users**


---

🛠️ Tech Stack

**Next.js**

**Solana Devnet**

**Lazorkit SDK**

**Tailwind CSS**



---

🏆 Submission

**Built and submitted for the Lazorkit Bounty Challenge (2025–2026).**


