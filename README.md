## Jump Hero - Mediapipe 🎮

Jump Hero is an interactive motion-controlled game where the player controls a hero using real-life jumps detected via Mediapipe and OpenCV. The game runs on Pygame and supports obstacle avoidance, scoring, and background music.

## 📌 Features

Motion Control: The hero jumps when you jump!

Obstacle Avoidance: Dodge incoming obstacles.

Scoring System: Track your score based on survival time.

Game Restart Option: Restart after game over.

Background Music & Sound Effects: Enhances gameplay experience.

## 🚀 Installation & Setup

1️⃣ Clone the Repository

git clone <repo_link>
cd Jump-Hero-Mediapipe

2️⃣ Create Virtual Environment

python -m venv venv  # or python3 -m venv venv

3️⃣ Activate Virtual Environment

Windows (CMD / PowerShell)

venv\Scripts\activate

WSL/Linux/macOS

source venv/bin/activate

4️⃣ Install Dependencies

pip install -r requirements.txt

5️⃣ Run the Game

python main.py

## 🛠 Requirements

Python 3.x

Mediapipe (for motion tracking)

OpenCV (for video processing)

Pygame (for game rendering)

Install all dependencies using:

pip install -r requirements.txt

## 🎵 Add Background Music

Place an .mp3 file inside the project folder.

Update main.py:

import pygame.mixer
pygame.mixer.init()
pygame.mixer.music.load("your_music.mp3")
pygame.mixer.music.play(-1)  # Loop forever

## 🕹 Controls

Jump IRL = Hero Jumps

Press R = Restart the game after game over

Press ESC = Quit game

## 📢 Contributing

Feel free to fork this project, add features, and create pull requests!

## 📜 License

This project is open-source under the MIT License.

🎯 Made with ❤️ using Python, Mediapipe & Pygame
