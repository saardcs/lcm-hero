# 🎮 LCM Hero

An interactive web app designed to help students practice math concepts, specifically combinations and the least common multiple (LCM), in a fun and engaging way.

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://lcm-hero.streamlit.app)

---

## 📘 About

LCM Hero challenges students to solve math problems related to combinations and LCM (Least Common Multiple). As students progress through different levels, they solve puzzles involving character combinations and LCM calculations, with each correct answer helping them level up.

---

## 🎓 Educational Use

- **Target Audience**: Thai Mathayom 1–3 students
- **Key Concepts**: Combinations, LCM (Least Common Multiple)
- **Learning Objective**: Students practice logical thinking, mathematical problem-solving, and understanding combinations and multiples.
- **Great for**: Classroom use, self-paced learning, or as a fun challenge!

---

## 🧠 How It Works

1. **Combination Problem**: Students are presented with a problem where they need to calculate how many combinations of characters are possible, based on certain restrictions (e.g., no repeats, use of numbers and letters).
   
2. **LCM Problem**: For higher scores, students solve LCM problems, determining the least common multiple of two numbers.

3. Students input their answers and, if correct, earn points and unlock higher ranks.

---

## 📊 Ranks & Scoring

| Score       | Rank               |
|-------------|--------------------|
| 0–4         | 🐣 Novice Cipherer  |
| 5–9         | 🔓 Puzzle Adept     |
| 10          | 🧠 Master of Numbers |

---

## 🚀 Getting Started

1. Make sure you have **Python 3.9+** installed.
2. Install required packages:

    ```bash
    pip install streamlit qrcode pillow
    ```

3. Save the script (e.g., `streamlit-app.py`).
4. Place your rank and level images (`level0.webp`, `level1.webp`, `level2.webp`) in the same directory.
5. Run the app:

    ```bash
    streamlit run streamlit-app.py
    ```

---

## File Structure
```plaintext
/lcm-hero
├── streamlit-app.py     # Main Streamlit app script
├── level0.webp          # Novice Cipherer rank image
├── level1.webp          # Puzzle Adept rank image
├── level2.webp          # Master of Numbers rank image
└── 3char.png            # Image representing 3-character codes
├── 4char.png            # Image representing 4-character codes
└── 5char.png            # Image representing 5-character codes
```
---

## Future Improvements

- Add more levels and problems to challenge users.
- Track historical performance and show user progress over time.
- Improve UI with animations and dynamic feedback.

---

## License

MIT License – free to use for teachers and students.
