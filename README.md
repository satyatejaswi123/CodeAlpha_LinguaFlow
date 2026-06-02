# 🌐 LinguaFlow — Language Translation Tool

> **CodeAlpha AI Internship — Task 1**

A sleek, AI-powered language translation web app built with HTML, CSS, and JavaScript. Supports 30+ languages with real-time translation, text-to-speech, language detection, and a dark/light theme toggle.

---

## 🚀 Features

- 🌍 **30+ Languages** — including Hindi, Telugu, Tamil, Kannada, French, Japanese, Arabic, and more
- 🔍 **Auto Language Detection** — detects the language of your input automatically
- 🔊 **Text-to-Speech** — listen to both input and translated text
- 📋 **Copy to Clipboard** — copy translated text with one click
- 🔄 **Swap Languages** — instantly swap source and target languages
- 🕓 **Translation History** — view and reload your last 8 translations
- 🌙 **Dark / Light Theme** — toggle between themes; preference is saved locally
- ⌨️ **Keyboard Shortcut** — press `Ctrl + Enter` to translate quickly
- 📱 **Responsive Design** — works on desktop and mobile

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Structure |
| CSS3 | Styling, animations, theming |
| JavaScript (Vanilla) | Logic, API calls, TTS |
| [MyMemory API](https://mymemory.translated.net/) | Free translation API (no key required) |
| Web Speech API | Text-to-speech functionality |

---

## 📁 Project Structure

```
CodeAlpha_LanguageTranslationTool/
│
├── index.html   # Main app (single file)
└── README.md                        # Project documentation
```

---

## ▶️ How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/satyatejaswi123/CodeAlpha_LinguaFlow.git
   ```

2. **Open the file in your browser:**
   ```bash
   cd CodeAlpha_LanguageTranslationTool
   open index.html
   ```

   Or simply **double-click** `index.html` — no server or installation needed!

---

## 🖥️ Screenshots

> *(Add your own screenshots here after running the app)*
## 🌙 Dark Mode

![Dark Mode](screenshots/dark.png)

## ☀️ Light Mode

![Light Mode](screenshots/light.png)
---

## 🔗 API Used

This project uses the **[MyMemory Translation API](https://mymemory.translated.net/)** — a free, open translation API that requires no API key for basic usage.

**Endpoint:**
```
https://api.mymemory.translated.net/get?q={text}&langpair={source}|{target}
```

---

## 📌 How to Use

1. Enter text in the **Input Text** box
2. Select **Source** and **Target** languages (or use Auto Detect)
3. Click **✦ Translate** or press `Ctrl + Enter`
4. View the translation on the right
5. Use **🔊 Listen** to hear the text, or **📋 Copy** to copy it

---

## 🎓 About

This project was built as part of the **CodeAlpha Artificial Intelligence Virtual Internship Program**.

- 🏢 Company: [CodeAlpha](https://www.codealpha.tech)
- 📌 Task: Task 1 — Language Translation Tool
- 👤 Intern: *Satya Tejaswi Tummala*

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
