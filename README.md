🎨 AI Image Generator Using Stable Diffusion

An AI-powered web application that generates high-quality images from natural language text prompts using Stable Diffusion v1.5 and Hugging Face Diffusers. The application is built with Python and Streamlit, providing a clean and interactive user interface for real-time image generation.

🚀 Project Overview

This project demonstrates the capabilities of Generative AI by converting user text prompts into realistic AI-generated images. It uses the Stable Diffusion v1.5 model to perform text-to-image synthesis and offers a simple web interface for seamless interaction.

✨ Features

* 🖼️ Text-to-Image Generation
* 🤖 Stable Diffusion v1.5 Model
* ⚡ Fast Image Generation
* 🎨 Clean & Modern Streamlit UI
* 📥 Download Generated Images
* 💻 CPU and GPU Support
* 🐳 Docker Ready
* 📂 Easy Deployment

🛠️ Technology Stack

* Python
* Streamlit
* Hugging Face Diffusers
* Stable Diffusion v1.5
* PyTorch
* Pillow (PIL)
* Docker
* Git & GitHub

📂 Project Structure

PRODIGY_GA_02/
│── .streamlit/
│── assets/
│── app.py
│── requirements.txt
│── Dockerfile
│── .gitignore
│── .dockerignore
│── README.md

⚙️ Installation

Clone Repository

git clone https://github.com/<your-username>/PRODIGY_GA_02.git
cd PRODIGY_GA_02

Create Virtual Environment

python -m venv .venv

Activate Virtual Environment

Windows

.venv\Scripts\activate

Linux / macOS

source .venv/bin/activate

Install Dependencies

pip install -r requirements.txt

Run Application

streamlit run app.py

🎯 Usage

1. Launch the Streamlit application.
2. Enter a descriptive text prompt.
3. Click Generate Image.
4. Wait for the AI model to create the image.
5. Preview and download the generated image.

📸 Sample Prompt

A futuristic cyberpunk city at night with neon lights and flying cars

📦 Model Used

* Stable Diffusion v1.5
* Hugging Face Diffusers
* PyTorch Backend

🐳 Docker

Build the Docker image:

docker build -t ai-image-generator .

Run the container:

docker run -p 8501:8501 ai-image-generator

📚 Learning Outcomes

* Text-to-Image Generation
* Stable Diffusion Architecture
* Hugging Face Diffusers
* Streamlit Web Application Development
* Generative AI Deployment
* Docker Containerization
* Git & GitHub Version Control

👨‍💻 Developer

Meghana R

Information Science & Engineering Student

📄 License

This project is developed for learning and educational purposes as part of the Prodigy InfoTech Generative AI Internship.
