# 🌙 Moonlit Tales — Bedtime Stories for Kids

A cozy, interactive web application that crafts gentle, age-appropriate bedtime stories in multiple Indian languages with optional AI voice narration. 

Powered by **Sarvam AI** (`sarvam-105b` for storytelling and `bulbul:v3` for natural speech synthesis).

---

## ✨ Features

- **📖 Interactive Storybook UI:** Designed like a bedtime picture book with warm night-sky themes, paper-cut card styling, and dynamic scene emoji illustrations.
- **🪄 Flexible Story Creation:** Pick up to 4 topics (dragons, space, animals, kindness, etc.), input a child's name, or hit **"Surprise Me"** for a completely random tale.
- **🇮🇳 Multi-Language Support:** Generates native text and spoken audio across 11 languages:
  - English, Hindi (हिन्दी), Marathi (मराठी), Bengali (বাংলা), Tamil (தமிழ்), Telugu (తెలుగు), Kannada (ಕನ್ನಡ), Malayalam (മലയാളം), Gujarati (ગુજરાતી), Punjabi (ਪੰਜਾਬੀ), and Odia (ଓଡ଼ିଆ).
- **🎙️ Read Aloud (TTS Narration):**
  - Choose from multiple narrator voices (*Ritu, Priya, Kavya, Shubh, Rohan*, etc.).
  - Adjustable speed (Cosy, Normal, Faster).
  - Page-by-page audio streaming with automatic page turning.
- **👶 Kid-Safe Prompts:** System prompts are strictly engineered to ensure violence-free, wholesome, and gentle bedtime themes suitable for ages 3–12.
- **⚡ Zero Build Tools:** Pure Vanilla HTML5, CSS3, and JavaScript — no Node.js, Webpack, or framework setup required.

---

## 🛠️ Tech Stack & Models

- **LLM:** Sarvam AI — `sarvam-105b` (`/v1/chat/completions`)
- **TTS:** Sarvam AI — `bulbul:v3` (`/text-to-speech`)
- **Frontend:** Vanilla JavaScript (ES6+), Semantic HTML5, Custom CSS

---

## 🚀 Quick Start

### 1. Clone or Download the Repository
```bash
git clone https://github.com/rijuludar/moonlit_tales.git
cd moonlit_tales