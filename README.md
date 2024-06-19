# Game Bot

This bot automates clicking on enemies in the game using computer vision and mouse automation. It detects enemies on the screen and clicks on them multiple times to ensure they are "killed".
[Watch it here](https://www.youtube.com/shorts/vr0rJGXgs_k)
[Buy it here](https://5123653385506.gumroad.com/l/igirc)

## Requirements

- Python 3.x
- OpenCV
- PyAutoGUI
- NumPy
- Keyboard

## Installation

### Clone the Repository

First, clone the repository to your local machine:

```sh
git clone https://github.com/yourusername/your-repo.git
cd your-repo
```

## Set Up the Virtual Environment

It is recommended to use a virtual environment to manage dependencies. You can set up a virtual environment using the following commands:

```sh
python -m venv myenv
source myenv/bin/activate  # On Windows use `myenv\Scripts\activate`
```
Install Dependencies
Install the required Python packages using pip:

```sh
pip install -r requirements.txt
```

Or you can install the packages individually:

```sh
pip install opencv-python pyautogui numpy keyboard
```

Usage
Prepare Enemy Templates
Ensure you have the enemy templates saved as images in the repository. Place the enemy images in the same directory as the bot script and name them appropriately, for example:

- enemy1.JPG
- enemy2.JPG
- enemy3.JPG
# Run the Bot
To run the bot, use the following command:
```sh
python bot.py
```
