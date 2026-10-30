# Quiz Master 🧠

A simple quiz website where you enter your name, answer timed questions, and see your result with a short performance analysis. It is built with **HTML, CSS and JavaScript**, and uses **Firebase** to save results and show a leaderboard.

---

## What this project does

- Asks the player to enter their name before starting.
- Gives **50 questions** from **5 topics**.
- Each question has a **15-second timer**.
- Shows a **progress bar** and live stats while playing: score, correct, wrong, and answered.
- The **Next Question** button works only after an answer is chosen.
- At the end, shows the final statistics: total questions, correct, wrong, and percentage.
- Gives an **AI Performance Analysis**: performance level, predicted performance, weak area, and a recommendation.
- Saves the result online and shows **Recent Results** and a **Global Leaderboard**.
- A **Play Again** button restarts the quiz.

---

## Screens

| Screen | What you see |
|--------|--------------|
| Start screen | Title, name box, quiz info (50 questions, 15s per question, 5 topics) and the Start button |
| Quiz screen | Question number, timer, progress bar, live stats, question with answer options |
| Result screen | Final stats, performance analysis, recent results, leaderboard and Play Again button |

---

## Technologies used

- HTML
- CSS
- JavaScript (ES modules)
- Firebase (to save results and load the leaderboard)
- Git and GitHub

---

## Project files

| File | Purpose |
|------|---------|
| `index.html` | Page structure of all three screens |
| `style.css` | Design and layout |
| `script.js` | Quiz logic, timer, scoring, analysis and Firebase code |
| `favicon.svg` | Icon shown on the browser tab |
| `README.md` | This file |

---

## How to run it on your computer

1. Download or clone the project:

   ```
   git clone https://github.com/Shubham-34/Quiz.git
   ```

2. Open the project folder in VS Code.
3. Install the **Live Server** extension.
4. Right-click `index.html` and choose **Open with Live Server**.
5. The quiz opens in your browser.

Note: The page loads `script.js` as a module, so open it through a local server (like Live Server). Double-clicking `index.html` may not work.

An internet connection is needed to save results and see the leaderboard.

---

## How to play

1. Type your name and click **Start Quiz**.
2. Read the question and choose an answer within 15 seconds.
3. Click **Next Question** to continue.
4. After the last question, check your result, analysis and the leaderboard.
5. Click **Play Again** to try once more.

---

## Limitations

- The leaderboard needs internet and a working Firebase setup.
- There is no login, so anyone can enter any name.
- The questions are fixed in the code.

---

## Future ideas

- Choose a topic or difficulty level.
- Add a login for players.
- Show the correct answers at the end for review.
- Add sound effects and more questions.

---

## Author

**Shubham Manhas**
UID: 26MCI10131
MCA (AI&ML), Chandigarh University
