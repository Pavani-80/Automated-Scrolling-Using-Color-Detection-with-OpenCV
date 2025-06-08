📌 Color Detection-Based Scrolling Automation
A real-time Python project that uses a webcam and OpenCV to detect green-colored objects and trigger keyboard events using pyautogui. Designed to simulate hands-free scrolling or actions like pressing the spacebar.
🚀 Features
🎥 Real-time webcam input

🎯 Green color detection using HSV filtering

⌨️ Triggers keyboard events (space, up, down)

🧠 Contour analysis for detecting object motion

🤖 Hands-free automation concept

📂 Project Structure
bash
Copy
Edit
.
├── scroll_by_color.py     # Main script
├── requirements.txt       # Required packages (optional)
└── README.md              # You're here
🛠️ Tech Stack
Language: Python

Libraries: OpenCV, NumPy, PyAutoGUI

🔧 Requirements
Install the required libraries using pip:

pip install opencv-python numpy pyautogui
📜 How It Works
HSV Color Filtering: Detects green shades within the specified HSV range.

Contour Detection: Locates moving green object in the frame.

Motion Tracking: Detects upward movement of the object.

Automation: Simulates a keyboard press (like space, down, or up).

▶️ Running the Program

python scroll_by_color.py
To stop, press q on the webcam window.

🎛️ Customize Actions
To change the key triggered by green object movement:

pyautogui.press('space')  # Change to 'down' or 'up'
📌 Example Use Cases
Touchless document scrolling during presentations

Accessibility tool for users with mobility limitations

Gesture-based control experiments

