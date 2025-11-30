🪨📄✂️ Rock–Paper–Scissors Game

A simple and interactive Rock–Paper–Scissors game built using HTML, CSS, and JavaScript.
The user plays against the computer, and scores update in real-time.

🚀 Live Demo

You can host this project on GitHub Pages (optional).
(Add your link here once deployed)

📸 Screenshots
Game UI

Rock

Paper

Scissors
(You can upload your images to GitHub and link them here)

🛠️ Features

✔️ Click-based game choices (Rock, Paper, Scissor)

✔️ Random computer choice generation

✔️ Live score tracking

✔️ Win/Lose/Draw detection

✔️ Dynamic message updates

✔️ Clean UI with hover effects

📂 Project Structure
📁 Rock-Paper-Scissors
│── index.html
│── style.css
│── logic.js
│── rock.png
│── paper.png
│── scissors.png

📑 How It Works
1. User selects a choice

Clicking a choice triggers the game logic:

choice.addEventListener("click", ()=>{
    let userChoice = choice.getAttribute("id");
    game(userChoice);
});

2. Computer generates a random choice
const options = ["rock", "paper", "scissor"];
const idxChoice = Math.floor(Math.random() * 3);

3. Game result is calculated

The program checks win/lose/draw conditions and updates the message + score.

🎮 How to Play

Click on Rock, Paper, or Scissor.

Computer instantly picks a random move.

The result is shown with a colored message:

🟩 Green → You Win

🟥 Red → You Lose

🟦/Gray → Draw

Scores update after each round.

📦 Installation & Usage

Clone the repository:

git clone https://github.com/your-username/your-repo-name.git


Open the project folder:

cd your-repo-name


Run the game by simply opening index.html in your browser.

🧪 Technologies Used

HTML5

CSS3

JavaScript (Vanilla JS)

🙌 Author

Your Name
(Add GitHub link or social links if you want)

⭐ Like this project?

If you found this useful, consider giving the repository a star on GitHub! 🌟

If you want, I can also:

✅ Create badges (shields.io)
✅ Add GIF demo
✅ Improve styling suggestions
✅ Create a better project description for GitHub

Just tell me!

You said:
Create direct readme file that i copy paste it
ChatGPT said:

Here is your copy–paste ready README.md — clean, simple, and perfect for GitHub.
Just copy everything below and paste into your README.md file.

🪨📄✂️ Rock–Paper–Scissors Game

A simple and interactive Rock–Paper–Scissors game built using HTML, CSS, and JavaScript.
Play against the computer, track your score, and enjoy a clean and responsive UI.

🚀 Live Demo

(Add your GitHub Pages link here if you host it)

📸 Screenshots

(Add images after uploading them to GitHub)

🛠️ Features

Click-based selection (Rock, Paper, Scissor)

Random computer move generation

Live score tracking

Win / Lose / Draw detection

Dynamic message updates

Smooth UI with hover effects

📂 Project Structure
📁 Rock-Paper-Scissors
│── index.html
│── style.css
│── logic.js
│── rock.png
│── paper.png
│── scissors.png

🎮 How to Play

Click on Rock, Paper, or Scissor

Computer selects a random move

Result displays instantly

Scores update automatically

🧠 How It Works

JavaScript listens for user clicks

Generates a random computer choice

Compares both choices

Updates:

Message (Win/Lose/Draw)

Colors (Green/Red/Gray)

Scores

🧪 Technologies Used

HTML

CSS

JavaScript

📦 Installation (Local Setup)
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name


Open index.html in your browser.

🙌 Author

Durgesh Shewale
https://github.com/DurgeshPatil-03