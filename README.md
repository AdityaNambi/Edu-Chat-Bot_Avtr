# Edu-Chat-Bot_Avtr
AI Avatar Generator: Generate short educational videos from any topic using GPT-Neo for text, gTTS for voice, Stable Diffusion for avatar creation, and SadTalker for lip-synced video animation—all in one pipeline.


📘 Project Description
This project automates the creation of educational talking-head videos using state-of-the-art AI models. From just a simple text topic input, it generates:

A script using a large language model,

A voiceover using text-to-speech,

A realistic avatar using image generation,

And a fully animated lip-synced video using SadTalker.

It enables teachers, students, and content creators to generate video lessons quickly and easily — no camera, mic, or editing software required.

🎯 Objective
To design a fully AI-powered pipeline that:

Accepts any educational topic as input,

Generates engaging, human-like teaching videos,

Simplifies content creation for digital learning platforms.

This tool serves as an accessible, low-cost alternative to traditional educational video production.

⚙️ Key Features
✅ GPT-Neo (EleutherAI/gpt-neo-1.3B) – Generates detailed explanations for any input topic
✅ gTTS – Converts the generated script into natural-sounding speech
✅ Stable Diffusion – Creates a high-quality avatar based on a prompt
✅ SadTalker – Lip-syncs the avatar to the audio for a dynamic talking-head video
✅ 15-second video cap to ensure smooth rendering and performance in demos

🚀 Use Cases
📚 EdTech Content: Auto-generate explainers or revision videos for any subject

👨‍🏫 Teachers: Create quick lectures without recording yourself

🎓 Students: Generate summaries of complex topics as video notes

🎥 YouTubers: Create avatar-based video content quickly

🌐 Multilingual Projects: Translate script + voice using gTTS options

🛠 Technologies Used
Tech	Purpose
GPT-Neo	Language generation
gTTS	Text-to-speech conversion
Stable Diffusion	Avatar generation
SadTalker	Video synthesis & lip syncing
PyTorch	ML model execution
Google Colab	GPU-powered runtime

📊 Output
After providing a topic, the pipeline generates:

script.txt – Generated topic explanation

audio.mp3 – Voice narration

avatar.jpg – Generated avatar image

avatar##audio_enhanced.mp4 – Final talking-head video

⚠️ Notes
Works best in Google Colab with GPU

SadTalker + Stable Diffusion requires significant VRAM (>= 8GB recommended)

Audio is trimmed to 15 seconds for faster inference and demo scope

📄 License
MIT License – Free for academic and non-commercial use.
For commercial use, please ensure compliance with respective model licenses (e.g., SadTalker, GPT-Neo, Diffusers).

