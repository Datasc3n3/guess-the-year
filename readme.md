# Guess The Year 🎯

A simple and fun **Guess-The-Year** game built with [Streamlit](https://streamlit.io/).  
In this game, a random historical event, movie, song, or trivia clue is presented, and you must guess the correct year it happened.

---

## 📂 Project Structure

```
├── app.py              # Main Streamlit application
├── requirements.txt    # List of Python dependencies
└── README.md           # Project documentation
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/guess-the-year.git
cd guess-the-year
```

### 2. Install dependencies

Make sure you are in the **root directory** (where `requirements.txt` is located), then run:

```bash
pip install -r requirements.txt
```

If you do not have `pip` installed, install Python 3.8 or higher from [python.org/downloads](https://www.python.org/downloads/) first.

### 3. Run the application

From the root folder, launch the Streamlit app using:

```bash
streamlit run app.py
```

This will start a local development server and provide you with a link (usually `http://localhost:8501`) in the terminal.

---

## 🛠 Dependencies

All required packages are listed in `requirements.txt`. Key libraries include:

- **Streamlit**: For building the interactive UI.
- Other supporting packages as listed in `requirements.txt`.

---

## 📖 How It Works

1. Select the number of teams.
2. Scan QR codes to play songs with the Spotify app.
3. Try to guess the year of the song (relative to songs already played).
4. Be the first to reach your goal of number of songs guessed.

---