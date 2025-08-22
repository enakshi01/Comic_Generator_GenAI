# 🎨 OnceUponAI - An Enchanted Start To Every Story

An AI-powered **Comic Strip Generator** that transforms any scenario into a 26-panel illustrated comic, complete with captions, styled artwork, and optional narration.  

## 🚀 Features
- 🖼️ **Panel Generation** – Splits a scenario into exactly 26 panels with captions.  
- 🎭 **Genre & Style Classification** – Auto-detects genre and assigns a matching non-photorealistic art style.  
- 🤖 **AI Storytelling** – Uses Google Gemini (`gemini-2.0-flash`) to craft panel narratives.  
- 🎨 **Artwork Creation** – Leverages Stability AI to render custom images per panel.  
- ✍️ **Text Overlay** – Uses `PIL` to add captions and speech bubbles to panels.  
- 🔊 **Narration (TTS)** – Converts text to audio narration for the comic strip.  
- 📚 **End-to-End Automation** – From input prompt → complete comic PDF/visual output.

---

## 🛠️ Tech Stack
- **Python 3.9+**
- [LangChain](https://www.langchain.com/) – Prompt orchestration  
- [Google Generative AI (Gemini)](https://ai.google.dev/) – Scenario → panel breakdown  
- [Stability AI SDK](https://platform.stability.ai/) – AI image generation  
- [Pillow (PIL)](https://pillow.readthedocs.io/) – Image editing  
- [TTS](https://github.com/coqui-ai/TTS) – Text-to-speech audio  
- [dotenv](https://pypi.org/project/python-dotenv/) – API key management  

---

## ⚙️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/OnceUponAI.git
   cd OnceUponAI
