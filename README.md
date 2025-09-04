# longdrive-prototype0.0
Perfect 👌 here’s a clean **README.md** draft for your chatbot project. You can just copy-paste this into a `README.md` file and upload it to GitHub:

---

# 🚗 Long Drive Chatbot

An experimental **voice-enabled chatbot** that simulates going on a fun, flirty long drive with your crush.
Built using:

* 🧠 **Groq LLM API** (`openai/gpt-oss-120b`)
* 🗣️ **Google Text-to-Speech (gTTS)** for speaking replies
* 💻 Python (works on Colab or local machine)

---

## ✨ Features

* Remembers conversation (chat history).
* Speaks responses aloud using **gTTS**.
* Custom “long drive” personality (fun, flirty, and caring).
* 🚨 Collision Warning System: say `dist X` to simulate distance input (cm). If too close, bot screams in panic 😅.

---

## 📂 Files

* `long_drive_chatbot.ipynb` → Main chatbot notebook (run in Colab or locally).
* `requirements.txt` → Dependencies (`requests`, `gTTS`, `IPython`).
* `README.md` → Project documentation.

---

## 🚀 Usage

### 1. Install dependencies

```bash
pip install requests gTTS
```

### 2. Run the chatbot

* Start conversation:

  ```python
  chat("Hi!")
  ```
* Simulate distance alert:

  ```
  dist 5
  ```
* Exit: type `quit` or `exit`.

---

## 🎯 Example Interaction

```
You: Good morning 😍
Bot: Good morning! I was waiting for you to pick me up. Where are we going first? 💕
```

---

## 🛠️ Future Improvements

* Replace gTTS with **real-time TTS** (like pyttsx3 or ElevenLabs).
* Add **speech recognition** so you can talk instead of typing.
* Deploy as a **web app** with Streamlit/Gradio.

---

## 👨‍💻 Author

Built with ❤️ by Avanish Shukla

---

👉 Do you want me to also make a **requirements.txt** for you (so GitHub users can install everything easily)?
