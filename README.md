<h1 align="center">Hi, I'm Ye Kai 👋</h1>

<p align="center">
  <b>Software Engineering student at SIT. I build the tools I end up using every day.</b>
</p>

<p align="center">
  <a href="https://tyklol.github.io/yk-site/"><img src="https://img.shields.io/badge/Portfolio-tyklol.github.io-0A66C2?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/ye-kai-tan/"><img src="https://img.shields.io/badge/LinkedIn-ye--kai--tan-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:yekai.tyk@gmail.com"><img src="https://img.shields.io/badge/Email-yekai.tyk%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

### 🧭 About me

I'm Ye Kai, a Year 3 Software Engineering student at SIT in Singapore. Before this I did a Diploma in IT at Singapore Polytechnic since 2019, giving me over 7 years of hands-on experience building software and tinkering with systems.

Most of my side projects start because something annoys me. I got tired of jumping between sketchy PDF websites, so I built an all-in-one toolkit to edit PDFs and download videos or music. I kept missing good deals on Carousell, so I wrote a bot that periodically scrapes listings and pings me on Telegram. Frustrated that existing bus apps didn't meet my needs, I created my own bus timing app with widget and notification support. When my desktop felt too dull, I made desktop pets that walk along open windows. I love seeing a project work end to end, whether that is an Android app on my phone or a robotic car following a line.

Outside of code I'm usually speedcubing, playing badminton or editing videos.

Currently looking for a 12-month software engineering internship from **May 2027 to Apr 2028**.

> 🤖 **Current workflow:** Powered by coffee, strict compiler flags, and an unhealthy emotional bond with Claude Code in the terminal.

---

### 🚀 Featured projects

| Project | What it does | Stack |
|---|---|---|
| **Bench** | A local desktop toolkit with ~70 tools (PDF, media, transcription, files). Each tool is declared once, and that declaration generates its UI form, its REST endpoint and its LLM function-calling schema. A local model chains up to 4 tools from a plain-English request. | Python · FastAPI · JS · SQLite · Ollama |
| **CarouWatcher** | A two-stage Gemini filter over Carousell listings that sends matches to Telegram as one digest. Parallel fetching cut a 20-listing run from ~100 s to 31 s, and when the AI is unavailable the run fails closed. | Python · Selenium · Gemini · Telegram |
| **Desktop Cat** | An Electron desktop pet that walks on real windows. Features per-pixel click-through, native window info through FFI, a utility-AI brain, and hand-written GIF/APNG/WebP decoders. | Electron · TypeScript · koffi |
| [**Robot Car**](https://github.com/tyklol/INF2004-Robot-Car) | An autonomous line-following car on a Pico W running FreeRTOS. Uses PID motor control and encoder/IMU/IR sensing, and streams live telemetry over MQTT to a Next.js dashboard. | C · FreeRTOS · MQTT · Next.js |
| **Semantic course search** | A hybrid MySQL + MongoDB Atlas Vector Search portal that finds modules from plain-English queries. I led the search work and the cloud hosting. | Flask · MongoDB · sentence-transformers |
| **File Manager** | An Android file manager built so that a failed move never leaves a broken copy: verified copy, then fsync, then atomic rename, plus a recoverable bin. No I/O on the main thread. | Java · Android · Media3 |
| **TranslationLens** | An offline Android app. Point the camera at an object to learn its name in another language. | Kotlin · CameraX · ML Kit · TFLite |
| **Clip-to-Shorts** | Turns movie clips into captioned vertical Shorts using Whisper, Gemini, Kokoro TTS and detection-guided cropping. | Python · ffmpeg · Whisper · Gemini |
| [**Smart Haven**](https://github.com/tyklol/inf1005-lamp) | A React + PHP/MySQL smart-home store with an admin panel, prepared statements and a WCAG-tested UI. | React · PHP · MySQL |
| [**Phishing detector**](https://github.com/tyklol/INF1002) | A Naive Bayes email classifier combined with VirusTotal and Hunter.io checks. | Python · Flask · scikit-learn |

➡️ See more on my **[portfolio site](https://tyklol.github.io/yk-site/)**.

---

### 🧰 Tech stack

**Languages**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)

**Backend & data**<br>
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**AI & ML**<br>
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![Whisper](https://img.shields.io/badge/Whisper-412991?style=flat-square&logo=openai&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

**Apps & frontend**<br>
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Embedded & tooling**<br>
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-5BA829?style=flat-square)
![Raspberry Pi Pico](https://img.shields.io/badge/Pico_W-A22846?style=flat-square&logo=raspberrypi&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)

---

### 📫 Get in touch

Reach me at **[yekai.tyk@gmail.com](mailto:yekai.tyk@gmail.com)** or on **[LinkedIn](https://www.linkedin.com/in/ye-kai-tan/)**.
