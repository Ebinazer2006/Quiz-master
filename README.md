🧠 Quiz Master
Quiz Master is a web-based quiz game that allows users to test their knowledge across categories with varying difficulty levels. It features login-based access, animated UI, interactive question flow, and result tracking — all built with HTML, CSS, and JavaScript.

🌟 Features
🔐 Login/Logout System (via auth.js)
LocalStorage-based authentication to enter the quiz zone.

📚 Category-Based Quizzes
Select from predefined quiz types with shuffled questions from question.js.

🎮 Game Interface (main.js)
Timer-based quiz with score tracking, question transitions, and answer validation.

🧠 10 Questions Per Round
Random questions are picked per session, ensuring variety.

🏁 Final Score Display
After answering 10 questions, users get a score popup with performance remarks.

🎨 Custom Themed Layout
Styled via btn_style.css and additional st2.css, st3.css, etc., for different modes or levels.

🛠️ Tech Stack
Frontend: HTML5, CSS3, JavaScript (Vanilla)

Storage: LocalStorage (for login sessions & temporary score storage)

🗂️ Key Files
File	Purpose
File / Page	Description
index.html -->	Login page that grants access to the quiz interface.
auth.js -->	Handles login/logout using LocalStorage.
main.js -->	Controls the quiz logic (question flow, scoring, UI updates).
question.js -->	Stores all quiz questions and correct answers.
btn_func.js -->	Manages button click functionality and state changes.
btn_style.css -->	CSS for button visuals and hover effects.
style.css -->	Common styles across the app (layout, fonts, etc.).
img_pzl.html -->	Image puzzle game – separate from quiz.
mmry_mtch.html -->	Memory match mini-game.
wrd_pzl.html -->	Word puzzle game interface.
wck_mol.html -->	Likely a separate activity/mini-quiz module.
sample.html -->	Sample quiz layout or a UI prototype.
st2.html to st9.html -->	Different quiz stages/themes/interfaces.
st2.css to st9.css -->	Corresponding CSS files for each themed stage.
st4.html  -->	Additional quiz interface.
st5.html -->	Extended or styled version of the quiz.
st6.html -->	Custom quiz interface for specific layout.
st7.html -->	Another styled page variant.
st8.css -->	Supporting stylesheet.

🔁 How It Works
User logs in through index.html (validated in auth.js)

Questions are selected from question.js and randomized.

User interacts via the UI in main.js, selecting answers and receiving immediate feedback.

At the end of the quiz, the score is displayed with feedback.

User can retry or logout.

🧪 Future Enhancements
Replace LocalStorage with database-backed login

Add category filters and user performance history

Enable leaderboard and league system

Timer with difficulty-based scoring

Sound effects and background themes

👨‍💻 Developed By
Ajay J
BSc Computer Technology - 3rd Year,
Dr. NGP Arts and Science College
mini Project – 2025
