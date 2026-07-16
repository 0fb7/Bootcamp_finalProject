# 📚 Smart Auto-Lecture Note Taker

An end-to-end multimodal pipeline that transforms raw lecture video files into professional, structured study notes. This project was developed as a Capstone Project for the Generative AI Summer Bootcamp at Najran University.

## ⚠️ The Problem
Students are often forced to watch lengthy recorded lectures just to extract key educational information. However, these recordings are rarely smooth; they are frequently disrupted by irrelevant student questions, unexpected internet connection drops, and unpredictable pauses by the instructor. This makes studying directly from raw video recordings a tedious, frustrating, and time-consuming process.

## 🚀 Project Overview
This tool automates the process of note-taking from educational videos, completely bypassing those common interruptions. By leveraging state-of-the-art Generative AI models, it extracts speech from the video, transcribes it, and structures the output into a clean, textbook-style study guide that focuses only on the core educational content.

## 🛠 Technical Pipeline
The project utilizes a modular architecture to ensure efficiency and performance:
*   **Audio Extraction:** Uses MoviePy to isolate audio tracks from video files.
*   **Speech-to-Text:** Employs the OpenAI Whisper model for high-accuracy transcription.
*   **LLM Reasoning:** Processes transcripts through Qwen2.5-1.5B-Instruct (optimized with 4-bit quantization) to generate structured educational content.

## ⏱ Performance Note (T4 GPU)
Optimized for academic efficiency, the pipeline processes data linearly:
*   **Processing Speed:** Every 5 minutes of video take approximately 1 minute to process.

## 📂 File Structure
*   **Copy of BootcampProject.ipynb:** The main notebook containing the pipeline logic.
*   **Raw Transcript (Whisper).txt:** The raw text output extracted from the lecture audio.
*   **Summary of the lecture.md:** The final structured study notes, including summaries, definitions, and review questions.
*   **requirements.txt:** A configuration file listing all necessary dependencies and library versions required to run the project.

## 🎓 Validation
This pipeline has been successfully tested and validated on the latest lecture provided in the Generative AI Summer Bootcamp, demonstrating high accuracy in capturing complex technical concepts.

## 🔗 Connect with the Developer
*   **GitHub:** [https://github.com/0fb7](https://github.com/0fb7)
*   **X (Twitter):** [https://x.com/prog7_](https://x.com/prog7_)
