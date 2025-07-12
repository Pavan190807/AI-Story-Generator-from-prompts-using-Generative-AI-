# ✨ AI Story Generator
A Streamlit-based web application that uses the Groq API with LLaMA 3 to generate short, creative stories from user prompts. Just enter your idea, and let the AI turn it into a vivid short story.

🚀 Live Demo
You can try the live version here:  
https://dahwczfcagcvbtrqhzccqu.streamlit.app/
📌 Features
  🧠 AI-generated short stories using Groq’s LLaMA 3 model
  ✍️ Creative writing based on any prompt
  ⚡ Fast and responsive interface built with Streamlit
  🔐 Secure API key management with .env locally and Streamlit Secrets on deployment
💠 Tech Stack
  Streamlit – UI framework
  Groq API – LLaMA 3 model
  Python
  requests, python-dotenv
📅 Local Installation
  Follow these steps to run the app locally on your machine:

  1.Clone this repository:
    git clone https://github.com/Pavan190807/AI-Story-Generator-from-prompts-using-Generative-AI-
  2.(Optional) Create a virtual environment:
    python -m venv venv
    venv\Scripts\activate  # For Windows
  3.Install the required packages:
    pip install -r requirements.txt
  4.Set up the .env file:
    Create a .env file in the root directory with your Groq API key:
    GROQ_API_KEY=your_actual_groq_api_key_here
  5.Run the app:
    streamlit run app.py
🎞️ Project Working
1.Open the web app.
2.Enter a story prompt in the input box (e.g., "A dragon who loves gardening").
3.Click the Generate Story button.
4.The app sends your prompt to Groq's LLaMA 3 model via API.
5.The generated story is displayed below the input field.
