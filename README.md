# 🛡️ IndySafeChat

**IndySafeChat** is an AI-powered chatbot designed to help Indianapolis residents report public safety issues quickly, anonymously, and intelligently — all through natural language. Whether it's a pothole, suspicious activity, or gunshots heard nearby, users can report it instantly and receive safety guidance, without needing to make a phone call or fill out forms.

---

## 🚀 Demo

> Visit: [http://localhost:5000](http://localhost:5000)  
> (Run the Flask app locally to test)

---

## 💡 Features

- 🔍 Accepts natural language safety reports.
- 🗂️ Categorizes incidents (e.g., vandalism, traffic, noise, danger).
- 📍 Accepts optional location input to contextualize the concern.
- 🧠 Powered by a **fine-tuned Qwen 1.5 Chat model** with LoRA adapters.
- 🧯 Returns real-time safety tips and response suggestions.
- 💬 Simple web interface with chat-style UX.

---

## 🧰 Built With

- **Python** — Core backend language.
- **Flask** — For handling routes and serving the web app.
- **Transformers** — Hugging Face library to load Qwen model.
- **PEFT + LoRA** — For lightweight, efficient model fine-tuning.
- **safetensors** — To store and load the LoRA adapter safely.
- **HTML, CSS, JavaScript** — For the chatbot frontend.
- **PyTorch** — Underlying deep learning framework.
- **Windows (Local)** — Development and model running environment.

---

## 📦 Installation

1. **Clone the repo**
```bash
git clone https://github.com/yourusername/indysafechat.git
cd indysafechat
--
indysafechat/
├── app.py
├── chatbot/
│   └── qwen_model.py
├── qwen-lora-safety-model/
│   └── ... (LoRA adapter + tokenizer files)
├── templates/
│   └── index.html
├── static/
│   └── style.css
└── requirements.txt
