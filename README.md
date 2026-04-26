# 🌌 Nyx-v1.0.7: The Ultimate AI-Powered Discord Companion

[![Invite Nyx](https://img.shields.io/badge/Invite-Nyx_Bot-blueviolet?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/oauth2/authorize?client_id=1445058228307361854)
[![GitHub License](https://img.shields.io/github/license/AMD-Syntax/Nyx-v1.0.7?style=for-the-badge)](LICENSE)
[![Python Version](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)

**Nyx-v1.0.7** is a sophisticated, multi-functional Discord bot engineered to revolutionize server interaction. By blending cutting-edge AI capabilities with a robust security framework and an engaging economy system, Nyx serves as an intelligent assistant, a creative powerhouse, and a vigilant guardian for your community.

---

## 🚀 Quick Start

Bring the power of Nyx to your server instantly:

> [!IMPORTANT]
> **[Click here to invite Nyx to your Discord Server](https://discord.com/oauth2/authorize?client_id=1445058228307361854)**

---

## ✨ Core Features

### 🤖 Advanced AI Chat Ecosystem
Nyx leverages state-of-the-art Large Language Models (LLMs) to provide a seamless conversational experience.
*   **Context-Aware Conversations**: Powered by Llama-3 via Groq API for natural, intelligent dialogue.
*   **Real-Time Web Search**: Integrated DuckDuckGo search allows the AI to provide up-to-date information.
*   **Dynamic Personas**: Admins can assign unique personalities to different channels using custom instruction sets.
*   **Voice Integration (TTS)**: High-quality Text-to-Speech that joins voice channels to speak AI responses.

### 🎨 AI Image Generation
Transform text into stunning visual art directly within Discord.
*   **Multi-Model Support**: Access various models and samplers via Pollinations.ai and Prodia.
*   **Parallel Processing**: Generate multiple images simultaneously for rapid creative exploration.
*   **Safety First**: Built-in NSFW detection and channel-specific restrictions to maintain server standards.

### 🛡️ Elite Anti-Scam Protection
One of the most comprehensive security systems available for Discord.
*   **Multi-Layered Detection**: Combines Regex patterns, AI text analysis, and Image Hashing to identify threats.
*   **Comprehensive Coverage**: Protects against phishing, malware, crypto scams, QR code fraud, and fake Nitro links.
*   **Automated Enforcement**: Configurable auto-delete, kick, and ban actions to neutralize threats instantly.
*   **Security Dashboard**: Use `/scam_security` for a password-protected, interactive configuration panel.

### 💰 Economy & Token System
A deeply integrated economic model that drives user engagement.
*   **Tiered Progression**: Level up and earn ranks (Silver, Gold, Diamond) to unlock multipliers and perks.
*   **AI Token Economy**: A sophisticated token system for AI features with 4-hour reset cycles and tiered plans (Free, Plus, Pro).
*   **In-Bot Marketplace**: Earn coins, orbs, and diamonds to purchase items, pets, and additional AI tokens.

---

## 🛠️ Technical Architecture

| Component | Technology |
| :--- | :--- |
| **Language** | Python 3.10+ |
| **Library** | discord.py / disnake |
| **AI Engine** | Groq API (Llama-3.3-70b) |
| **Image Engine** | Prodia / Pollinations.ai |
| **Database** | JSON-based Persistence (Scalable to SQL) |
| **Voice** | FFmpeg-based TTS |

---

## 🗺️ Roadmap: What's Coming Next?

We are committed to the continuous evolution of Nyx. Here is what we are working on:

| Phase | Feature | Description |
| :--- | :--- | :--- |
| **Q2 2026** | **SQL Migration** | Moving from JSON to PostgreSQL for enhanced performance and data integrity. |
| **Q2 2026** | **Web Dashboard** | A sleek web interface for server owners to manage bot settings easily. |
| **Q3 2026** | **Advanced Logging** | Centralized logging system for better transparency and error tracking. |
| **Q3 2026** | **Community Games** | Interactive mini-games to boost server activity and engagement. |
| **Future** | **Custom Command Engine** | Allow users to build their own simple commands within the Nyx framework. |

---

## ⚙️ Installation

1.  **Clone the Repository**:
    ```bash
    git clone https://github.com/AMD-Syntax/Nyx-v1.0.7.git
    cd Nyx-v1.0.7
    ```
2.  **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
3.  **Configure Environment**:
    Create a `.env` file in the root directory:
    ```env
    DISCORD_TOKEN=your_discord_bot_token
    GROQ_API_KEY=your_groq_api_key
    ```
4.  **Launch**:
    ```bash
    python main.py
    ```

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

**Developed with ❤️ by [AMD-Syntax](https://github.com/AMD-Syntax)**