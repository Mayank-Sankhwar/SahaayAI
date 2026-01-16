# <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Telephone%20Receiver.png" alt="Telephone" width="45" height="45" /> SahaayAI 

> **Bridging the Digital Divide:** Providing 24/7 AI-driven intelligence to low-connectivity areas through the power of a simple phone call.

<div align="center">
  <img src="https://capsule-render.vercel.app/render?type=soft&color=auto&height=200&section=header&text=SahaayAI&fontSize=80&animation=fadeIn&fontAlignY=38" width="100%" />
</div>

<p align="center">
  <a href="#-mission">Mission</a> •
  <a href="#-features">Features</a> •
  <a href="#-how-it-works">Architecture</a> •
  <a href="#-tech-stack">Tech Stack</a> •
  <a href="#-installation--setup">Setup</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge&logo=github" />
  <img src="https://img.shields.io/badge/Connectivity-Low_Bandwidth-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Language-Multilingual-blue?style=for-the-badge" />
</p>

---

## 🎙️ The Mission
In regions where high-speed internet is a luxury, information remains locked behind digital barriers. **SahaayAI** acts as an intelligent bridge, allowing users to speak their queries in their native tongue and receive answers via a traditional phone call—turning any mobile phone into a gateway to global knowledge.

---

## 🚀 Features

| Feature | Description |
| :--- | :--- |
| **🎤 Native Voice Input** | Capture queries effortlessly through a mic-enabled web interface. |
| **🌐 Real-time Intelligence** | Dynamic web-scraping focused on Government Schemes and local news. |
| **🧠 Neural Synthesis** | Natural-sounding AI voice responses that feel human, not robotic. |
| **📞 Seamless Call-Back** | Automatic VoIP triggers deliver answers directly to the user's handset. |
| **📩 SMS Summaries** | Persistent text records sent immediately after the call ends. |

---

## ⚙️ How It Works

```mermaid
graph LR
    A[🎙️ User Speech] --> B(Language Detection)
    B --> C{🧠 Gemini LLM}
    C --> D[🌐 Tavily Search]
    D --> E(🔊 Voice Synthesis)
    E --> F[📞 Twilio Call/SMS]
    F --> G[📱 User Mobile]
    
    style C fill:#6E40C9,stroke:#fff,stroke-width:2px,color:#fff
    style G fill:#238636,stroke:#fff,stroke-width:2px,color:#fff
