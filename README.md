
# 📐 AI Math Tutor with Streamlit & Ollama

This project is a **friendly, interactive AI-powered math tutor** built with [Streamlit](https://streamlit.io/) and [Ollama](https://ollama.ai/), offering step-by-step explanations and real-world examples to help users understand math concepts easily.

![screenshot](templates/bg.png) <!-- Replace with an actual screenshot link if deployed -->

---

## 🚀 Features

- 🌟 **Background image support** for a visually appealing interface.
- 🤖 **Conversational AI Tutor** that answers math-related queries step-by-step.
- 🧠 **Persistent chat memory** for contextual responses.
- ✨ **Friendly tone and intuitive explanations** to support all types of learners.
- 🔒 **Role protection:** AI always acts as a Math Tutor, ignoring attempts to override its persona.
- 🗃️ **Custom system prompt** with detailed behavior guidelines.

---

## 📁 Folder Structure

```
.
├── app.py                # Main Streamlit application file
├── templates/
│   └── bg.png            # Background image used for styling
├── README.md             # Project documentation
```

---

## 🛠️ Requirements

Install the following Python packages:

```bash
pip install streamlit ollama
```

---

## ▶️ How to Run

1. Make sure you have [Ollama](https://ollama.ai/) installed and running locally.
2. Save your background image in the `templates/` folder as `bg.png`.
3. Run the app:

```bash
streamlit run app.py
```

---

## 🧠 Note

This tutor is optimized for math learning queries only. Non-math topics will be gently redirected.

---

## 📬 Contact

For any queries or feedback, feel free to reach out via [GitHub](https://github.com/) or your preferred platform.
