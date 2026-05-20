<p align="center">
  <a href="README.md">🏡 Home</a> | 
  <b>🚀 Featured Projects</b> | 
  <a href="skills.md">💻 Technical Skills</a>
</p>

---

# 🚀 Featured Projects

Dive deeper into my most impactful applications, hackathon-winning projects, and open-source contributions. 

---

<a id="salus"></a>
## 🛡️ Salus: Privacy-First 'Coordination of Benefits' Engine
**[UofTHacks 13 Winner: Best Use of MongoDB Atlas] | [View Project](https://devpost.com/software/salus-9javs3)**

Salus is a **local-first, universal benefits engine** engineered to solve the complex bureaucracy of medical billing. Designed with a Zero-Trust architecture, it mathematically stacks private insurance with public government aid to eliminate financial toxicity.

*   **Secure Vault:** Utilizes **1Password Passkeys** to decrypt a local browser vault containing sensitive PII. Identity data never touches the server.
*   **Multi-Agent Reasoning:** Orchestrates 4 specialized AI agents using **LangGraph** (Extractor, Actuary, Social Worker, Coordinator) that analyze hospital bills, private insurance rules, and local government laws.
*   **Voice Accessibility:** Integrates **ElevenLabs** for native language text-to-speech, ensuring complex financial advice is accessible to everyone.
*   **Tech Stack:** Next.js, Python FastAPI, Google Gemini 1.5 Pro, MongoDB Atlas Vector Search, LangGraph.

---

<a id="transignal"></a>
## 🏭 TranSignal: Autonomous Supply Chain Resilience Agent
**[Hack The Future] | AI Operations Co-Pilot**

TranSignal is designed to help mid-market manufacturers proactively predict, mitigate, and respond to global supply chain disruptions before SLA breaches or stockouts occur.

*   **Risk Intelligence Engine:** Calculates revenue-at-risk estimation and operational impact modeling using deterministic math against real-time disruption data (e.g., port strikes).
*   **Gemini 2.5 Flash Core:** Uses GenAI to evaluate multi-dimensional supply chain trade-offs, determining the most cost-effective mitigation path (like expedited shipping vs. SLA penalties).
*   **Operations Control Tower:** A Streamlit dashboard featuring geospatial mapping, an interactive reasoning trace, and clear limits for Human-In-The-Loop approval based on automated financial thresholds.
*   **Tech Stack:** Python, FastAPI, Streamlit, Google Gemini 2.5 Flash, PyDeck.

---

<a id="clutter2cash"></a>
## 🧺 Clutter2Cash: Sustainability & Resale AI
**[Built during an MLH Hackathon] | [View Project](https://github.com/Clutter2Cash/clutter2cash)**

Clutter2Cash is an intelligent mobile app that helps users find worth in what is left behind. By taking a photo of an item, the app identifies it, estimates its resale value, and calculates the CO₂ saved by keeping it out of a landfill.

*   **Google Gemini Engine:** The ML core processes uploaded images to instantly categorize the item, determine fair market pricing, and assess the environmental impact.
*   **Passwordless Authentication:** Quick, secure authentication powered by **Auth0**.
*   **Tech Stack:** React Native (Expo), Node.js, Express, MongoDB, Google Gemini API.

---

<a id="python-libraries"></a>
## 🐍 Open Source Python Libraries

I actively maintain several lightweight, highly specialized Python tools published on PyPI.

### 🖼️ `imageconvert`
[![PyPI version](https://img.shields.io/pypi/v/imageconvert.svg)](https://pypi.org/project/imageconvert/)
A robust library for converting modern image formats (JPEG, PNG, WebP, HEIC/AVIF, TIFF) and manipulating PDFs. 
*   **Data Integrity:** Unique in its capability to preserve EXIF metadata, GPS coordinates, and original OS file timestamps during batch conversions.
*   [Documentation](https://ricardos-projects.gitbook.io/imageconvert-docs) | [PyPI](https://pypi.org/project/imageconvert/)

### 🔢 `word-number-converter`
[![PyPI version](https://img.shields.io/pypi/v/word-number-converter.svg)](https://pypi.org/project/word-number-converter/)
A multi-language utility for parsing integers to words and words back to integers.
*   **Global Support:** Handles English, Spanish, French, German, Arabic, Swahili, Japanese, and intricate systems like Traditional/Financial Chinese and Roman Numerals natively without external dependencies.
*   [PyPI](https://pypi.org/project/word-number-converter/)

### 📡 `morsecode-handler`
[![PyPI version](https://img.shields.io/pypi/v/morsecode-handler.svg)](https://pypi.org/project/morsecode-handler/)
A blazing-fast Morse code encoder/decoder that supports 41 languages out-of-the-box (Latin, Cyrillic, Arabic, Hebrew, Greek, Korean).
*   **Developer Friendly:** Ships with a Python API and a built-in CLI interface, featuring strict and lenient parsing modes.
*   [PyPI](https://pypi.org/project/morsecode-handler/)
