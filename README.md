# 🛡️ ORACLEAI STUDIO — Gemma 4 Good Hackathon 2026

**Vertex Coders LLC — Miami, Florida, USA**

---

## 🌐 Live Demo

🔗 **[ORACLEAI STUDIO — LIVE DEMO](https://kaggle-hackathon-gemma4.netlify.app/)**

> Click the link above to experience the full multimodal AI platform.

---

## 📱 Mobile Ecosystem

| Platform | Link |
|----------|------|
| **Android App (Phone)** | [https://play.google.com/store/apps/details?id=com.vertex.sentinel_mobile) |
| **Wear OS (Galaxy Watch 5)** | [https://play.google.com/store/apps/details?id=com.vertex.sentinel_mobile) |

---

## 🧠 What is OracleAI Studio?

OracleAI Studio is a **full-stack multimodal AI platform** powered by **Google Gemma 4** (26B A4B). It provides:

- **14 specialized AI agents** (Education, Health, Coding, Mental Health, Nutrition, Blind Guide, ASL Translator, Sentinel Security, and more)
- **Multimodal file processing**: Images, PDFs, DOCX, CSV, JSON, Audio (MP3/WAV), Video (MP4/YouTube)
- **Real-time vision**: Live camera analysis, fall detection, ASL translation, scene narration
- **Mobile ecosystem**: Android + Wear OS apps with vital signs monitoring and emergency AI alerts
- **9 languages**: ES, EN, FR, PT, IT, ZH, KO, RU, HU

---

## 🏗️ Architecture

User → Angular 19 (Netlify) → FastAPI (HuggingFace) → Google AI (Gemma 4) → Response
↓
┌───────┴───────┐
↓ ↓
SQLite DB WebSocket
(History) (Vision)


### Backend (Hugging Face Spaces)
- FastAPI async endpoints
- OpenCV video frame extraction
- Pandas CSV analytics
- Speech-to-text transcription
- MediaPipe pose detection

### Frontend (Netlify)
- Angular 19 standalone + Signals
- Drag & drop file upload
- Live camera vision
- Text-to-speech output
- Cyberpunk terminal UI

### Mobile (Android + Wear OS)
- Kotlin + Jetpack Compose
- MVVM architecture
- Real-time vital signs (Galaxy Watch 5)
- Fall detection + SOS
- Gemma 4 health alerts

---

## 🎯 Problem Solved

**The Gap:** Advanced AI is powerful but inaccessible to most people — behind paywalls, complex interfaces, or limited to text-only.

**Our Solution:** OracleAI Studio is **100% free, no account required, multimodal, and runs on any device** (web, phone, watch). It democratizes AI access for:

- 👩‍🎓 **Students** needing adaptive learning
- 👨‍⚕️ **Underserved communities** with no doctor access
- ♿ **Visually/hearing impaired** users (Blind Guide, ASL Translator)
- 👴 **Elderly** needing fall detection + emergency alerts
- 🌍 **Non-English speakers** (9 languages supported)

---

## 📊 Impact Metrics (Live)

| Metric | Value |
|--------|-------|
| Total queries | 229+ |
| Education mode | 210+ |
| Health queries | 6 |
| Documents processed | 13+ |
| AI modes | 14 |
| Languages | 9 |
| Platforms | Web + Android + Wear OS |

---

## 🛠️ Technologies Used

| Category | Technologies |
|----------|--------------|
| **AI Model** | Google Gemma 4 26B A4B (via Google AI API) |
| **Backend** | FastAPI, Python, Hugging Face Spaces |
| **Frontend** | Angular 19, Tailwind CSS, Netlify |
| **Mobile** | Kotlin, Jetpack Compose, Wear OS Compose |
| **Computer Vision** | OpenCV, MediaPipe |
| **Data Analysis** | Pandas, Matplotlib |
| **Audio** | SpeechRecognition, FFmpeg |
| **Database** | SQLite |
| **Real-time** | WebSockets |

---

## 📂 GitHub Repository

🔗 **[github.com/Denisijcu/oracleai-studio](https://github.com/Denisijcu)** *(public repo with full source code)*

---

## 👨‍💻 Team

| Role | Name |
|------|------|
| **Founder & Lead Developer** | Denis Sanchez Leyva |
| **AI Architecture & Debugging** | Gemini, Claude, Grok & more ... |
| **Company** | Vertex Coders LLC |

---

## 🏆 Why We Should Win

1. **Complete ecosystem** — Not just a demo, but a production-ready platform across web, phone, and watch
2. **Real social impact** — Accessibility, healthcare, education, elder care
3. **Technical depth** — Multimodal, real-time, mobile native, cloud backend
4. **Beautiful UX** — Cyberpunk terminal interface that users love
5. **100% free & open** — No paywalls, no data selling, accessible to all

---

## 📎 Submission Links

- 🌐 **Live Demo:** https://oracle-gemma4-studio.netlify.app
- 📱 **Android App:** [Vertex Sentinel on Play Store](https://play.google.com/store/apps/details?id=com.vertex.centinel)
- ⌚ **Wear OS App:** [Vertex Sentinel Wear on Play Store](https://play.google.com/store/apps/details?id=com.vertex.sentinel.wear)
- 🤗 **Hugging Face Space:** https://huggingface.co/spaces/Denisijcu/oracle-hub-backend
- 💻 **GitHub:** https://github.com/Denisijcu

---

**Made with 🔥 in Miami — Vertex Coders LLC**
