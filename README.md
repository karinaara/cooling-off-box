# 🕊️ Cooling-off Box — Emotional Decision Simulator

[![Live Demo](https://img.shields.io/badge/Demo-Live%20App-brightgreen?style=for-for-badge&logo=netlify)](https://cooling-off-box.netlify.app/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

> A lightweight, client-side web application designed to prevent impulsive decisions made during intense emotional states by combining locked cooling timers, Socratic reflection, and automated emotional clarity scoring.

🌐 **Live Demo:** [https://cooling-off-box.netlify.app/](https://cooling-off-box.netlify.app/)

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Key Features](#-key-features)
- [How It Works](#-how-it-works)
- [Tech Stack](#-tech-stack)
- [Privacy & Security](#-privacy--security)
- [Getting Started Locally](#-getting-started-locally)

---

## 📖 Overview

Making decisions while experiencing peak emotions—such as anger, over-excitement, panic, or anxiety—often leads to regret. **Cooling-off Box** acts as a cognitive circuit breaker. It enforces a mandatory reflection period where users answer structured Socratic prompts to generate an objective **Clarity Score** before executing any critical action.

---

## 📸 Preview

<img width="1901" height="907" alt="image" src="https://github.com/user-attachments/assets/7d2ede6f-3a3e-48c1-9250-3c5d549606ae" />

---

## 🌟 Key Features

- **🧠 4 Tailored Emotion Modes:** Customized Socratic questioning workflows for **Anger**, **Over-excitement**, **Panic**, and **Anxiety**.
- **⏳ Locked Cooling Timer:** Prevents hasty execution by enforcing a mandatory reflection pause until the timer expires.
- **📊 Clarity Score Calculation:** Analyzes responses to evaluate emotional bias and offers objective, actionable guidance.
- **🔒 100% Client-Side Privacy:** Built with a privacy-first architecture using the `localStorage` API. Zero data is sent to external servers.
- **🌐 Multilingual Support:** Seamlessly toggle between **English** and **Indonesian**.
- **🎨 Dynamic & Responsive UI:** Light and Dark theme toggling with calming ambient background gradients and Glassmorphism design.

---

## 🔄 How It Works

1. **Select Emotion & Duration:** Choose your current emotional state and set your cooling period.
2. **Socratic Reflection:** Work through guided questions while the timer locks the final action.
3. **Clarity Assessment:** Receive a real-time Clarity Score evaluating emotional bias.
4. **Grounded Decision:** Review your reflection summary and proceed with a balanced mindset.

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3 (CSS Variables, Glassmorphic UI, Flexbox & CSS Grid)
- **Logic:** Vanilla JavaScript (ES6+)
- **Storage:** Web Storage API (`localStorage`)
- **Hosting:** [Netlify](https://www.netlify.com/)

---

## 🔒 Privacy & Security

**Cooling-off Box** operates strictly inside your browser:
- **No Remote Databases:** No personal entries or logs ever leave your local device.
- **No Analytics Tracking:** Your reflective thought process remains completely confidential.
- **Offline Ready:** Works locally without relying on external API endpoints.

---

## 🚀 Getting Started Locally

Follow these steps to set up and run the project locally:

### 1. Clone the Repository
```bash
git clone [https://github.com/karinaara/cooling-off-box.git](https://github.com/karinaara/cooling-off-box.git)
cd cooling-off-box
