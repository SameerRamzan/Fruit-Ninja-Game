# Fruit Slicing Game (Inspired by Fruit Ninja)

## Description

This project implements a "Fruit Ninja" style game where players use hand gestures, tracked via a webcam, to slice fruits appearing on the screen. It utilizes MediaPipe for hand landmark detection to identify hand movements and slice actions.

The repository provides two versions of the game:

1.  **Web-based version (`game.html`):** Runs directly in modern web browsers.
2.  **Python-based version (`game.ipynb`):** Uses OpenCV and is designed to be run in a Jupyter Notebook environment.

## Features

*   Real-time hand tracking using MediaPipe.
*   Fruit slicing mechanic based on hand swipe gestures.
*   Score tracking.
*   Sound effects for slicing and game over (in the web version).
*   Game restart functionality (in the web version).
*   Two implementations: HTML/JavaScript for web and Python/OpenCV for desktop.

## Installation

### Web Version (`game.html`)

1.  **No installation required.**
2.  Simply download or clone this repository.
3.  Ensure you have a modern web browser (like Chrome, Firefox, Edge) with webcam access enabled.
4.  An internet connection is required to load external libraries (MediaPipe, Tone.js) from CDNs.

### Python Version (`game.ipynb`)

1.  **Prerequisites:**
    *   Python 3.x
    *   `pip` (Python package installer)
2.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```
3.  **Install required Python libraries:**
    ```bash
    pip install opencv-python mediapipe
    ```
4.  **Jupyter Environment:**
    *   You'll need Jupyter Notebook or JupyterLab to run the `.ipynb` file. If you don't have it, you can install it via pip:
        ```bash
        pip install notebook
        # or for JupyterLab
        pip install jupyterlab
        ```

## Usage

### Web Version (`game.html`)

1.  Open the `game.html` file in your web browser.
2.  Allow webcam access when prompted by the browser.
3.  The game will start automatically. Use your hand (specifically, the movement of your index finger is tracked) to "slice" the fruits that appear on the screen.
4.  The game runs for 30 seconds. Your score will be displayed.
5.  Click the "Restart" button to play again.

### Python Version (`game.ipynb`)

1.  Start your Jupyter environment:
    ```bash
    jupyter notebook
    # or
    jupyter lab
    ```
2.  Open the `game.ipynb` notebook.
3.  Run the cells in the notebook sequentially.
4.  A window will appear showing your webcam feed and the game in action.
5.  Use your hand gestures to slice the fruits.
6.  To quit the game, ensure the game window is active and press the 'q' key.

## Contributing

Contributions are welcome! If you have ideas for improvements or want to report a bug, please feel free to open an issue or submit a pull request.

(Further details on contribution guidelines can be added here if the project owner has specific requirements.)
