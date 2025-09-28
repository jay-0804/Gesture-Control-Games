Gesture Control Games

This repository contains Python-based gesture-controlled interfaces for three popular games: Flappy Bird, Chrome Dino, and Hill Climb. Using your webcam, control these games with simple hand gestures for a fun, hands-free experience!

Setup Instructions

Clone the repository:

git clone <your-repo-url>
cd <repo-folder>


(Optional) Create and activate a virtual environment:

python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate


Install required Python packages:

pip install -r requirements.txt


If you don’t have requirements.txt, install manually:

pip install opencv-python cvzone pyautogui


Run the controller scripts for your desired game:

python flappy_controller.py
python dino_controller.py
python hillclimb_controller.py

How to Use

Ensure your webcam is connected and working.

Focus the game window before running the gesture controller script.

Run the desired controller script (examples above).

Press q in the controller window to quit.

Gesture Controls
Flappy Bird

Raise exactly one finger (index finger) to flap (simulate spacebar press).

Chrome Dino

Left hand index finger up: Jump (spacebar press)

Right hand index finger up: Duck (down arrow press)

Make sure the Dino game window is focused!

Hill Climb

Right hand:

5 fingers up = Hold right arrow (move forward)

0 fingers up = Hold left arrow (move backward)

Left hand: Same as right hand controls (can be customized).

Notes

Use in a well-lit environment for better hand detection.

Keep your hand visible to the webcam.

The scripts simulate keyboard input, so ensure the game window is active and focused.
