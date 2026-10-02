<p align="center">
  <img src="src/assets/logo.png" width="120" height="120" alt="WellLearn Logo" />
</p>

<h1 align="center">WellLearn</h1>

<p align="center">
  <strong>Intelligent Real-Time Study & Learning Companion</strong>
</p>

<p align="center">
  An interactive, multimodal desktop study assistant designed to accelerate understanding during online lectures, technical courses, coding tutorials, and mock interview practice.
</p>

---

## 📖 About WellLearn

**WellLearn** is an educational learning assistant that sits quietly on your screen while you study. Powered by **Google Gemini Live**, it processes both audio and visual inputs in real-time to help students, developers, and lifelong learners grasp complex subjects faster.

Whether attending online lectures, reviewing documentation, solving coding exercises, or practicing for technical discussions, WellLearn listens, reads along, and provides natural, easy-to-understand explanations instantly.

---

## ✨ Key Features

- **🎧 Real-Time Audio Comprehension**: Listens to online lectures, webinars, and discussions through system audio or microphone, breaking down key takeaways on the fly.
- **🖥️ Multimodal Visual Learning**: Understands diagrams, slides, lecture materials, and code on your screen with on-demand visual analysis.
- **🎯 Interactive Study & Practice**: Simulates real-time technical questions and mock interview discussions, delivering conversational, clear, humanized guidance.
- **🪟 Discreet Floating Overlay**: Minimalist, semi-transparent, always-on-top window designed to stay in view without obstructing notes, slides, or IDEs.
- **⚡ Ultra-Low Latency**: Sub-second response streaming powered by Gemini Live bidirectional WebSocket audio/text.
- **🛡️ Private & Local First**: Your API keys and configuration remain stored locally on your machine.

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
| :--- | :--- |
| **`Ctrl` + `Up` / `Down` / `Left` / `Right`** | Move overlay window |
| **`Ctrl` + `\`** | Toggle window visibility |
| **`Ctrl` + `M`** | Toggle click-through mode (transparent to clicks) |
| **`Ctrl` + `Enter`** | Next response / advance turn |
| **`Ctrl` + `[` / `]`** | Previous / Next response history |
| **`Ctrl` + `Shift` + `Up` / `Down`** | Scroll response text |
| **`Ctrl` + `Shift` + `E`** | Emergency erase / clear current text |

---

## 🚀 Getting Started

### Prerequisites

- **Node.js** (v18 or higher recommended)
- **Google Gemini API Key** (Free tier available at [Google AI Studio](https://aistudio.google.com/apikey))

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/userhemanth/WellLearn.git
   cd WellLearn/cheating-daddy
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Launch the application:**
   ```bash
   npm start
   ```

---

## 💡 How to Use for Study & Preparation

1. **Set Up Your API Key**: Enter your Gemini API key in the main setup window.
2. **Personalize Your Study Profile**: Select your learning profile (Interview Preparation, Technical Learning, Meeting, etc.) and add any relevant coursework, syllabus, or background notes in Customize.
3. **Select Audio Mode**: Choose **Both (Speaker & Microphone)**, **Speaker Only**, or **Microphone Only** depending on whether you're listening to an online lecture or speaking practice questions.
4. **Start Session**: Click **Start Session**. Position the translucent overlay beside your lecture video or study material.
5. **Study Continuously**: WellLearn listens and reads along, generating immediate, structured notes and conceptual breakdowns as you learn.

---

## 🎙️ Audio Capture Modes

- **Windows**: Dual-stream Web Audio mixer capturing system loopback (lecture audio) and microphone without acoustic feedback.
- **macOS**: System audio capture via core audio dump and microphone input.
- **Linux**: PulseAudio/ALSA loopback and microphone input.

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
