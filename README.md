# Asterisk HTML5

A modern HTML5 Canvas port of the classic C# WinForms game **Asterisk**, originally created by Mark Heath. 

This single-file web version faithfully recreates the original's frustratingly addictive "Flappy Bird-esque" mechanics while introducing modern visual flair like glowing neon trails, persistent high scores, and randomized level modifiers to keep you on your toes.

## 🚀 Features

* **Zero Dependencies:** Pure HTML, CSS, and vanilla JavaScript in a single file. No build steps or libraries required.
* **Endless Progression:** The number of obstacles increases by 3 every time you beat a level.
* **Level Modifiers:** Random buffs and debuffs alter the gameplay mechanics of entire levels.
* **Persistent High Scores:** Your highest number of completed levels is saved locally in your browser.
* **Neon Aesthetic:** The player's path is drawn as a continuous, glowing line that changes color based on the active level modifier.

## 🎮 How to Play

The goal is to navigate from the left side of the screen to the opening on the right side without crashing into the walls or the floating white square obstacles.

### Controls
* **Press and Hold `ENTER`**: Rise up.
* **Release `ENTER`**: Fall down.

*Note: You cannot touch the top or bottom walls. You must pass exactly through the gap on the right side of the screen to complete the level.*

## 🔮 Level Modifiers

Starting on Level 2, each level has a chance to apply a random modifier that changes the rules of physics or your ship's capabilities. Your trail color indicates the active modifier:

* 🟨 **Normal (Yellow):** Standard speed and physics.
* 🟦 **Shield (Cyan):** You are invincible to the floating white obstacles! (You can still die by hitting the ceiling, floor, or walls).
* 🟩 **Slow (Lime):** Your horizontal speed is cut in half, giving you more time to navigate tight clusters.
* 🟥 **Fast (Red):** Your horizontal speed is doubled. Fast reflexes are required!
* 🟪 **Reverse (Purple):** Controls are inverted! Holding `ENTER` makes you fall, and releasing makes you rise.

## 🛠️ Installation & Usage

Because the game is entirely self-contained, installation is instantaneous:

1. Download or copy the `index.html` file.
2. Double-click the file to open it in any modern web browser (Chrome, Firefox, Edge, Safari).
3. Press **Enter** to start playing!

## 📜 Credits

* **Original C# Game:** [Mark Heath](https://github.com/markheath/asterisk) (Created May 2003)
* **HTML5 Port:** Ported to JavaScript/Canvas with added visual effects and modifier mechanics. 

---
*Happy flying, and try not to crash!*
