# MCQMaster

**MCQMaster** is an interactive web-based quiz tool built with pure HTML, CSS, and JavaScript. It allows users to practice multiple-choice questions (MCQs) by loading them from a simple `.txt` file. The app presents one question at a time, provides instant feedback, tracks progress, and allows review of all questions at the end. Great for students, self-learners, and educators alike!

---

## 🚀 Features

- ✅ Select and submit answers interactively  
- 🎯 Immediate feedback: Know right away if you're correct  
- 📊 Score tracking (on first attempt only)  
- 🎉 Confetti and sounds for correct/incorrect responses  
- 📁 Download all incorrectly answered questions  
- 🔁 Review mode to go over all questions at once  
- 🧭 Question navigation buttons with color-coded feedback  
- ⚡ Fast and lightweight—no frameworks required

---

## 📄 Text File Format (`questions.txt`)

Add your questions in the following format (make sure to use **plain text** with UTF-8 encoding):


Each question block must include:
- The question
- Four options (A–D)
- A line specifying the correct answer in the format: `Correct Answer: [A/B/C/D]`

---

## 🖥️ How to Run

To run **MCQMaster**:

1. Clone or download this repository.
2. Ensure your `questions.txt` file is in the **same directory** as `index.html`.
3. **Important:** You must use a **local server** to run the app due to browser restrictions on `fetch()` for local files.

### 👉 Use VS Code + Live Server (Recommended)

- Install the [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
- Right-click `index.html` → “Open with Live Server”

---

## 🔧 Customization Tips

- 🔊 Swap out `correct.mp3` and `wrong.mp3` with your own audio
- 🎨 Update styles in the `<style>` section of `index.html`
- 📚 Easily replace `questions.txt` for new quizzes (no need to edit JavaScript)

---

## ✨ Future Improvements (Contributions Welcome!)

- ⏱️ Timer for each question
- 🖼️ Support for image-based questions
- 🧾 Markdown support
- 🗂️ Multiple quiz categories

---

## 📜 License

MIT License — free to use, modify, and share.
