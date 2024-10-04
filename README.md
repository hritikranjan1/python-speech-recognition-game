## 🎙️ Speech Recognition Guessing Game

This Python project is a fun, speech-based guessing game where you speak your guesses via microphone. The game transcribes your spoken guesses and checks if you can correctly guess the randomly chosen word from a predefined list.
📝 Table of Contents

  - Introduction
   - Features
  - Prerequisites
  - Installation
  - Usage
  - Contributing
  - License

## 📖 Introduction

This project utilizes speech recognition to allow users to guess words by speaking into their microphone. The game listens to the user's guesses and provides feedback based on the recognized text. It's built using Python and Google's speech recognition API.
## ✨ Features

  - Speech-based word guessing game
  - Uses Google’s speech recognition API to transcribe spoken words
  - Multiple attempts allowed for guessing the correct word
  - Error handling for unrecognizable speech and API issues

#  🛠️ Prerequisites

Before running the project, make sure you have the following installed:

  - Python 3.x
  - A working microphone
  - An active internet connection (for speech recognition)

Optional but recommended:

  - Virtual environment setup for isolated project dependencies
## 🚀 Installation
1. Clone the repository:

       git clone https://github.com/your-username/python-speech-recognition-game.git
       cd python-speech-recognition-game
2.Set up a virtual environment (optional):

    python3 -m venv myenv
    source myenv/bin/activate  # For Linux/macOS
    myenv\Scripts\activate     # For Windows
3.Install the dependencies: Install the necessary Python libraries:

    pip install -r requirements.txt
4.Install PyAudio (if not installed automatically):

If you face issues installing PyAudio, on Ubuntu/Linux you may need to install portaudio:

    sudo apt-get install portaudio19-dev
    pip install pyaudio
## 🎮 Usage

  1. Run the game: Ensure your microphone is connected and functional, then run the guessing game:

    python guessing_game.py

2. Gameplay Instructions:

    - The game will randomly select a word from a predefined list.
    - You have 3 attempts to guess the word correctly by speaking into the microphone.
    - After each guess, the speech will be transcribed and matched against the word.
   -  If you guess correctly, you win; otherwise, you have more attempts to try again.

3. Word List: The game will randomly pick from the following words: apple, banana, grape, orange, mango, lemon.

## 🤝 Contributing

We welcome contributions to improve the game or add new features. Feel free to submit:

  - Issues
  - Pull requests
Steps to Contribute:

    - Fork the repository.
    - Create a new branch with your feature or bug fix: git checkout -b my-feature-branch.
    - Commit your changes: git commit -m 'Add some feature'.
    - ush to the branch: git push origin my-feature-branch.
    - Open a pull request.
   
 ##  📝 License

This project is licensed under the MIT License. See the LICENSE file for details.
## 📧 Contact

For any issues or feature requests, feel free to contact me via GitHub or open an issue in this repository.
    - Name: Hritik ranjan
    - Telegram: https://t.me/codewithluv143
    - LinkedIn: https://www.linkedin.com/in/hritik-ranjan-05a835230/
    - X:https://x.com/luvranjan143
-
