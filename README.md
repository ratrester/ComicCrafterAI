# ComicCrafter AI

## Overview
ComicCrafter AI is a generative AI-based comic generator that creates comic-style stories based on user input prompts. It leverages Large Language Models (LLMs) for story generation and AI-based image generation models to illustrate the stories. The application is optimized to run efficiently on Intel-based edge devices.

## Features
- **Story Generation**: Uses LLMs to generate a structured comic story.
- **Image Generation**: Creates comic-style illustrations using Stable Diffusion.
- **Story & Image Integration**: Merges generated text and images into a structured comic format.
- **Web Application**: User-friendly interface built with Streamlit.
- **Edge Deployment**: Optimized for Intel-based edge devices using OpenVINO.

## Installation
### Prerequisites
- Python 3.8+
- Git
- Virtual environment (optional but recommended)

### Steps
1. **Clone the repository**
   ```sh
   git clone https://github.com/yourusername/ComicCrafter-AI.git
   cd ComicCrafter-AI
   ```
2. **Create and activate a virtual environment** (optional but recommended)
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. **Install dependencies**
   ```sh
   pip install -r requirements.txt
   ```
4. **Run the application**
   ```sh
   streamlit run app.py
   ```

## Usage
1. Open the web app in your browser.
2. Enter a prompt for the comic story.
3. Click 'Generate' to create a structured comic book with AI-generated text and images.
4. Download the final comic in a structured format.

## Technologies Used
- **LLMs**: HuggingFace (Transformers, Pipeline)
- **Image Generation**: Stable Diffusion
- **Programming Language**: Python
- **Frameworks & Deployment**: Streamlit

## Contribution
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m 'Add new feature'`).
4. Push to your branch (`git push origin feature-branch`).
5. Open a pull request.
