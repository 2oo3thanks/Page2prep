# Page2prep
Page2Prep is an intelligent web app that helps students transform their study materials into interactive flashcards—just upload a PDF, and the app takes care of the rest!Whether you're prepping for exams, reviewing lecture notes, or organizing your reading, Page2Prep gives you an edge in a few clicks.
# 📘 Page2Prep

**Page2Prep** is a smart web application that turns your PDF files into interactive flashcards using OCR (Optical Character Recognition) and NLP (Natural Language Processing). Perfect for students who want to convert their notes, handouts, or textbooks into effective study material—fast.

---

## ✨ Features

- 🧠 **AI-Powered Flashcard Generator** – Extracts named entities from your PDF using OCR and spaCy NLP
- 📄 **PDF to Flashcards** – Upload scanned or digital PDFs and generate question-answer pairs
- 🎴 **Practice Mode** – Practice flashcards with:
  - Shuffle
  - Score tracking
  - Timed quiz mode
  - Spaced repetition buttons (Easy, Medium, Hard)
- 🎨 **Minimal UI** – Built with Streamlit, using Rubik font, modern styling, and a clean layout
- ☁️ **Deployed with Streamlit Cloud** – No installation needed, just share the link!

---

## 📂 Project Structure

```bash
├── app.py                # Main Streamlit app
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation (this file)
```

---

## 🛠️ Installation (For Local Use)

1. Clone the repository:
```bash
git clone https://github.com/yourusername/page2prep.git
cd page2prep
```

2. Create a virtual environment and activate it (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the app:
```bash
streamlit run app.py
```

---

## ☁️ Deployment (Streamlit Cloud)

1. Push this code to a public GitHub repo.
2. Go to [Streamlit Cloud](https://streamlit.io/cloud).
3. Connect your GitHub, select your repo, and deploy.

---

## 🧠 How It Works

- **OCR (Tesseract)** extracts raw text from scanned PDFs.
- **spaCy NLP** detects important entities (names, dates, places, etc.).
- These entities are used to auto-generate flashcard questions and answers.
- Users practice the flashcards in a gamified environment.

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgements

- [spaCy](https://spacy.io/)
- [Tesseract OCR](https://github.com/tesseract-ocr/tesseract)
- [Streamlit](https://streamlit.io/)
- Icons by [Streamline HQ](https://streamlinehq.com/)

---

> Built with 💡 to make learning easier. Start your smart study session now with **Page2Prep**!
> 
