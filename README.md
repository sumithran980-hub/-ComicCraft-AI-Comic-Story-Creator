# ComicCraft - AI Comic Story Creator using Gemini Models

ComicCraft is a web-based application that uses AI to generate personalized comic book stories and illustrations based on user-provided prompts.

## 🚀 Features
- Takes user inputs: Story Prompt, Character Name, Setting, Tone, Art Style
- Uses Google Gemini AI for story generation
- Uses Stable Diffusion + Hugging Face Diffusers for image generation
- Generates panel-by-panel storyline with illustrations
- Preview comic on web interface
- Download full comic in PDF format with images and narration
- Built with FastAPI backend and clean HTML/CSS frontend

## 🛠️ Tech Stack
- **Backend:** FastAPI
- **AI Models:** Google Gemini, Stable Diffusion
- **Libraries:** Hugging Face Diffusers
- **Frontend:** HTML, CSS, JavaScript
- **Output:** PDF generation

## 📖 How it Works
1. User enters story details (prompt, character, setting, tone)
2. Gemini AI generates comic story script
3. Stable Diffusion generates images for each panel
4. User can preview the comic
5. Download final comic as PDF

## 📦 Installation
```bash
pip install fastapi uvicorn google-generativeai diffusers
uvicorn main:app --reload
