# Quizler: A Python Quiz Game

Quizler is a Python-based quiz game that tests your knowledge on a variety of topics with a focus on computer science. Utilizing a clean graphical user interface (GUI) built with Tkinter, players can answer True/False questions and receive immediate feedback on their answers. Questions are dynamically fetched from the Open Trivia Database, ensuring a wide range of questions for endless fun.

## Features

- Fetches questions in real-time from the Open Trivia Database.
- Offers a graphical user interface using Tkinter for an interactive quiz experience.
- Tracks and displays the user's score in real-time.
- Provides immediate feedback on each answer.
- Displays a final score at the end of the quiz.

## Prerequisites

Before running Quizler, you'll need to have Python 3 installed on your system. Additionally, the project uses the `requests` module to fetch questions from the web, which can be installed via pip if you don't already have it:

```bash
pip install requests
```

## Setup

To get Quizler up and running on your local machine, follow these steps:

1. Clone the repository or download the source code.
2. Ensure you have Python 3.x installed.
3. Install the `requests` module using pip if you haven't already.

## Running the Game

To start the quiz game, navigate to the project's root directory in your terminal and run:

```bash
python main.py
```

This command initiates the game, fetching a set of questions and presenting them through a graphical interface.

## How to Play

- After launching the game, the quiz will automatically proceed to the first question.
- Choose your answer by clicking the "True" or "False" button.
- Your score will update in real-time at the top right corner of the window.
- After answering all questions, your final score will be displayed.

## Contributions

Contributions to Quizler are welcome! If you've got an idea for a new feature or found a bug, feel free to fork the repository, make your changes, and submit a pull request.
