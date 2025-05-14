# Included Without Limitations

*An AI-powered tool for accessible image captioning and speech synthesis, designed to break barriers in digital inclusivity.*

---

## 🧠 Problem Statement

Equity, Diversity, and Inclusion (EDI) are essential principles that require practical, technology-driven solutions. One major barrier faced by individuals with visual impairments, neurodivergence, or limited language comprehension is the lack of accessible, meaningful content in visual media.

Most existing solutions are either outdated, overly technical, or lack the real-time accessibility that modern AI can offer.

---

## 💡 Solution Overview

**Included Without Limitations** bridges the accessibility gap by combining AI image captioning and speech synthesis into one intuitive tool:

* 🖼 Generate descriptive captions for uploaded images
* 🗣 Convert captions to realistic speech using Eleven Labs
* 🔊 Offer voice options (Male & Female)
* ✅ Provide a clean, accessible, and responsive UI

This enables better access to digital content for visually impaired users, non-native speakers, and neurodivergent users.

---

## ⚙️ Tech Stack

### Frontend

* HTML5, CSS3 (Bootstrap 5)
* JavaScript (ES6)

### Backend / AI

* Gradio Inference Client (image captioning)
* Hugging Face Model
* Eleven Labs API (text-to-speech)

---

## 🚀 Getting Started

### ✅ Prerequisites

* A modern web browser
* Internet connection
* API keys:

  * Hugging Face token (for image captioning)
  * Eleven Labs API key (for speech synthesis)

### 🛠 Setup

```bash
git clone https://github.com/yabek9000/included-without-limitations.git
cd included-without-limitations
```

Open `index.html` in your browser (or use Live Server).

Inside the `<script>` tag:

* Replace `YOUR_HUGGINGFACE_API_TOKEN_HERE` with your actual Hugging Face token.
* Replace `YOUR_ELEVENLABS_API_KEY_HERE` with your Eleven Labs API key.

---

## 🖼 How It Works

* Upload an image using the file input.
* The app sends the image to a Hugging Face captioning model.
* The caption is auto-generated and displayed.
* Click “Generate & Speak” to convert the caption to speech.
* The generated audio is played through the integrated player.

---

## 🔒 Security Notice

This project uses frontend-stored API keys for demonstration purposes only.
**Do not expose your real credentials in a public deployment.**
For production use, implement a secure backend or proxy.

---

## ✅ Features

* ✨ AI-powered image caption generation
* 🗣 Natural-sounding voice synthesis
* 🔄 Male and female voice selection
* 💬 Inclusive UX with accessibility-first design
* 📱 Fully responsive and mobile-friendly interface

---

## 📈 Real-World Impact

This project helps increase digital equity for:

* People with visual impairments
* Neurodivergent users
* Language learners
* Users from diverse cultural and educational backgrounds

---

## 👥 Contributors

* **Taseen** ([@yabek9000](https://github.com/yabek9000))
* **Gabrielius** ([@GabrieliusUosis](https://github.com/GabrieliusUosis))
* **Chetas** ([@Chets45](http://github.com/Chets45))
---

## 📄 License

This project is intended for educational and demonstration use during the
**AI Hackathon – 14/05/2025 – DigiTechNetwork**.

Please refer to the licensing terms of Hugging Face and Eleven Labs APIs for any production or commercial use.

---

> Created with purpose, powered by AI — **Included Without Limitations**.
