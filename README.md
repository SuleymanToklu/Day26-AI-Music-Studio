---
title: AI Music Studio
emoji: 🎶
colorFrom: purple
colorTo: blue
sdk: gradio
sdk_version: 4.31.5
app_file: app.py
pinned: false
---

# 🎶 Day 26: AI Music Studio (Generator & Analyst)

This is the twenty-sixth project of my #30DaysOfAI challenge, following a "2 Models, 1 Package" strategy. This project combines a **Text-to-Music** model and a **Music Source Separation** model into a single AI Music Studio application.

### ✨ "2 Models, 1 Package" Concept
* **Model 1 (The Composer - Text-to-Music):** Uses `facebook/musicgen-small` to generate novel music clips from a user's text prompt.
* **Model 2 (The Producer - Source Separation):** Uses `facebook/demucs` to take an audio track and separate it into its core instrumental stems (drums, bass, vocals, etc.).

### 💻 Tech Stack
-   Python, Gradio, PyTorch, Hugging Face (Transformers)