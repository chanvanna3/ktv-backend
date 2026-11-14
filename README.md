# ktv-backend

YouTube AI Karaoke Studio (Backend API) • Produced by [សំបុករៀន (Sombokrean)](https://www.sombokrean.com/)

High-Precision AI Stem Separation API with Real-Time Progress Tracking & Auto Vocal Removal.

## Features
- **AI Stem Separation Engine:** Powered by Meta's **HT-Demucs** deep neural network (95%+ vocal isolation).
- **FastAPI Core:** Non-blocking async audio processing and streaming API.
- **Whisper AI / YouTube Lyrics:** Synchronized timestamped karaoke lyrics in Khmer and English.
- **Cross-Browser History Sync:** Multi-client singing history and trending songs storage.
- **Docker Ready:** Optimized Dockerfile with ffmpeg, PyTorch CPU, and pre-cached Demucs weights.

## Deployment on Render.com
1. Connect this repository `chanvanna3/ktv-backend` to Render.
2. Select **Web Service** with **Docker** runtime.
3. Add environment variables (e.g. `YOUTUBE_API_KEY`, `DEMUCS_MODEL=htdemucs`).
4. Copy the service URL to set as `VITE_API_URL` on your frontend deployment!
