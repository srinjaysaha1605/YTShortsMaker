AI Shorts Maker 🎬

An AI-powered YouTube Shorts creation pipeline built with Google Colab. It automates the process of turning a custom script into a complete short-form video with AI voiceover, Whisper-based transcription, synchronized captions, flexible image sequencing, automatic timing, 9:16 formatting, animations, and final video rendering.

✨ Features
📝 Custom script input
🎙️ AI voiceover generation with Edge TTS
🧠 Whisper-based audio transcription
💬 Automatic short-form captions
🖼️ Upload and arrange any number of images
⏱️ Automatic image timing based on audio duration
📱 Automatic 9:16 YouTube Shorts formatting
🎬 Animated image effects and transitions
👀 Preview stages throughout the pipeline
🎞️ Automatic video + voiceover + captions rendering
🛠️ Built With
Python
Google Colab
Edge TTS
Faster-Whisper
FFmpeg
Pillow
MoviePy
🚀 Workflow
Custom Script
     ↓
Script Processing
     ↓
AI Voiceover
     ↓
Whisper Transcription
     ↓
Caption Generation
     ↓
Image Upload & Ordering
     ↓
9:16 Image Preparation
     ↓
Automatic Image Timing
     ↓
Animated Scenes
     ↓
Voiceover + Video
     ↓
Caption Rendering
     ↓
Final YouTube Short
📌 Notes

The pipeline is designed to keep script structure and image count independent, allowing any number of visuals to be used for a short. Images are automatically ordered numerically (1.jpg, 2.jpg, 3.jpg...) and distributed across the total audio duration.

📂 Output

The generated project files include:

Voiceover audio
Transcription and word timestamps
Caption files (.json, .srt, .ass)
Prepared 9:16 images
Animated scene videos
Final captioned YouTube Short
