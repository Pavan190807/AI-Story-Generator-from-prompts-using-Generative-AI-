# ✨ AI Story Generator

A Streamlit-based web application that uses the **Groq API with LLaMA 3** to generate short, creative stories from user prompts. Just enter your idea, and let the AI turn it into a vivid short story.

---

## 🚀 Live Demo

👉 [Open the App](https://dahwczfcagcvbtrqhzccqu.streamlit.app/)

---

## 📌 Features

* 🧠 AI-generated short stories using Groq’s LLaMA 3 model
* ✍️ Creative writing based on any prompt
* ⚡ Fast and responsive interface built with Streamlit
* 🔐 Secure API key management with `.env` locally and Streamlit Secrets on deployment

---

## 💠 Tech Stack

* [Streamlit](https://streamlit.io/) – UI framework
* [Groq API](https://console.groq.com/) – LLaMA 3 model
* [Python](https://www.python.org/)
* `requests`, `python-dotenv`

---

## 📅 Local Installation

Follow these steps to run the app locally on your machine:

1. **Clone this repository:**

```bash
git clone https://github.com/Pavan190807/AI-Story-Generator-from-prompts-using-Generative-AI-
```

2. **(Optional) Create a virtual environment:**

```bash
python -m venv venv
venv\Scripts\activate  # For Windows
```

3. **Install the required packages:**

```bash
pip install -r requirements.txt
```

4. **Set up the `.env` file:**

Create a `.env` file in the root directory with your Groq API key:

```env
GROQ_API_KEY=your_actual_groq_api_key_here
```

5. **Run the app:**

```bash
streamlit run app.py
```

---

## 🎞️ Project Working

1. Open the web app.
2. Enter a story prompt in the input box (e.g., "A dragon who loves gardening").
3. Click the **Generate Story** button.
4. The app sends your prompt to Groq's LLaMA 3 model via API.
5. The generated story is displayed below the input field.

---

## 📸 Screenshots

### 📚 Home Screen

![Home Screen](<img width="1908" height="981" alt="Image" src="https://github.com/user-attachments/assets/b2e77607-56e3-46dc-8a6f-51415227f472" />)


### 💭 Story Output Example

![Prompt and Output](<img width="1916" height="966" alt="Image" src="https://github.com/user-attachments/assets/8772c981-cf17-4fb5-aadd-020b62c9c718" />)


![Generated Story](<img width="547" height="902" alt="Image" src="https://github.com/user-attachments/assets/3f11adb3-26e0-45dc-bafa-2c8368abaa0e" />)


---

## 🙌 Author

Made by [Chitturi Pavan Kumar](https://github.com/Pavan190807) using Groq API.

---

## 📋 License

This project is licensed under the [MIT License](LICENSE).

---

