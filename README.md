# 📚 Smart Auto-Lecture Note Taker

An end-to-end multimodal pipeline that transforms raw lecture video files into professional, structured study notes. This project was developed as a Capstone Project for the Generative AI Summer Bootcamp at Najran University.

## 🚀 Project Overview
This tool automates the tedious process of note-taking from educational videos. By leveraging state-of-the-art Generative AI models, it extracts speech from video, transcribes it, and structures the output into a textbook-style study guide.

## 🛠 Technical Pipeline
The project utilizes a modular architecture to ensure efficiency and performance:
1. **Audio Extraction**: Uses `MoviePy` to isolate audio tracks from video files.
2. **Speech-to-Text**: Employs the `OpenAI Whisper` model for high-accuracy transcription.
3. **LLM Reasoning**: Processes transcripts through `Qwen2.5-1.5B-Instruct` (optimized with 4-bit quantization) to generate structured educational content.

## ⏱ Performance Note (T4 GPU)
Optimized for academic efficiency, the pipeline processes data linearly:
- **Processing Speed**: Every 5 minutes of video take approximately 1 minute to process.
- **Typical Load**: A 45-minute lecture is fully processed in about 15–18 minutes.

## 📂 File Structure
* `Copy of BootcampProject.ipynb`: The main notebook containing the pipeline logic.
* `Raw Transcript (Whisper).txt`: The raw text output extracted from the lecture audio.
* `Summary of the lecture.md`: The final structured study notes, including summaries, definitions, and review questions.

## 🎓 Validation
This pipeline has been successfully tested and validated on the latest lecture provided in the Generative AI Summer Bootcamp, demonstrating high accuracy in capturing complex technical concepts.

## 🔗 Connect with the Developer
- **GitHub**: (https://github.com/0fb7)
- **X (Twitter)**: (https://x.com/prog7_)

---
*This project directly reinforces the Multimodal Data and Software Development.
