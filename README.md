# 🧠 QuizMaster — Interactive Quiz App

A sleek, dark-themed, single-page quiz application built with **HTML, CSS, and vanilla JavaScript**, styled using **Bootstrap 5**. Test your general knowledge across 10 curated questions with a live countdown timer, animated feedback, and a detailed results summary.

![Status](https://img.shields.io/badge/status-active-brightgreen)
![Made with](https://img.shields.io/badge/made%20with-HTML%2C%20CSS%2C%20JS-blue)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-7952B3?logo=bootstrap&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-yellow)

---

## ✨ Features

- 🎯 **10 General Knowledge Questions** — covers geography, science, history, art, and more
- ⏱ **15-Second Timer Per Question** — animated circular countdown with a warning state when time runs low
- 🟢 **Instant Feedback** — correct/wrong answers highlighted immediately with explanations
- 📊 **Live Progress Bar** — tracks quiz progress in real time
- 🏆 **Detailed Results Screen** — final score, breakdown of correct/wrong/skipped answers, and a performance message
- 🔁 **Replay Option** — restart the quiz anytime
- 🎨 **Modern Dark UI** — custom indigo-accented theme with smooth animations and responsive layout

---

## 🚀 Demo

Simply open `quizapp.html` in any modern web browser — no installation or server required.

---

## 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5 | Structure |
| CSS3 (Custom Properties) | Styling & Theming |
| Bootstrap 5.3 | Layout & Responsiveness |
| Vanilla JavaScript | Quiz Logic & Interactivity |

---

## 📂 Project Structure

```
interactive-quiz-app/
├── quizapp.html      # Main application file (HTML + CSS + JS)
└── README.md         # Project documentation
```

---

## ⚙️ How It Works

1. **Start Screen** — Displays quiz info: number of questions, time per question, and points per correct answer
2. **Quiz Screen** — Each question shows 4 options (A–D) with a live timer; selecting an answer locks the question and shows correct/incorrect feedback
3. **Result Screen** — Displays total score, stats (correct/wrong/skipped), and a motivational message based on performance

### Scoring
- ✅ Correct answer → **+10 points**
- ❌ Wrong answer → 0 points
- ⏱ Time expires → counted as **skipped**

---

## 🖥️ Usage

```bash
# Clone the repository
git clone https://github.com/ashwinkasera05/interactive-quiz-app.git

# Navigate to the project folder
cd interactive-quiz-app

# Open in browser
start quizapp.html   # Windows
open quizapp.html    # macOS
```

---

## 🎨 Customization

To add your own questions, edit the `questions` array in `quizapp.html`:

```javascript
const questions = [
  { q: "Your question here?", options: ["A", "B", "C", "D"], answer: 0 },
  // answer = index of correct option (0-3)
];
```

You can also adjust:
- `TIME` — seconds per question
- Color theme via CSS `:root` variables

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to fork the repo and submit a pull request.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👤 Author

**Ashwin Kasera**
[GitHub](https://github.com/ashwinkasera05)
