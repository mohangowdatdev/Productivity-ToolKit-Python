# Python Productivity Toolkit Widget

## Overview

The Python Productivity Toolkit Widget is a collection of productivity tools designed to improve efficiency while working. This minimalistic and easy-to-use project includes the following features:

- 🗒️ Notepad
- 🔳 Whiteboard
- ⏱️ Work Timer (Pomodoro)
- 📱 URL to QR Code Converter

The widget has a minimal interface that can hide in the background, making it a convenient addition to your workflow.

## Features

1. **Notepad 🗒️**
   - A simple text editor to jot down notes.
   - Save and clear functionality.

2. **Whiteboard 🔳**
   - A digital canvas for drawing and brainstorming.
   - Color picker and clear button included.

3. **Work Timer (Pomodoro) ⏱️**
   - A Pomodoro timer to help manage work sessions and breaks.
   - Start and stop controls with a live clock display.

4. **URL to QR Code Converter 📱**
   - Convert any URL or text into a QR code.
   - Display the generated QR code in a window.

## Installation

### Prerequisites

- Python 3.x
- Tkinter (usually included with Python)
- qrcode library
- Pillow library

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/mohangowdatdev/Productivity-ToolKit-Python.git
   cd Productivity-ToolKit-Python
   ```

2. **Install required libraries:**
   ```bash
   pip install qrcode[pil] Pillow
   ```

3. **Run the main application:**
   ```bash
   python main.py
   ```

## Usage

### Main Application

- Run `main.py` to launch the toolkit.
- A window with four buttons will appear: Notepad, Whiteboard, QR Code, and Timer.
- Click any button to open the respective tool.

### Notepad

- Type your notes in the text area.
- Use the "Save" button to save the content to `notepad.txt`.
- Use the "Clear" button to clear the text area.

### Whiteboard

- Draw on the canvas with your mouse.
- Use the color picker to change the drawing color.
- Use the "Clear" button to clear the canvas.

### Work Timer (Pomodoro)

- The timer starts at 25 minutes (1500 seconds).
- Click "Start" to begin the countdown.
- Click "Stop" to pause the timer.
- The current time is displayed at the bottom.

### URL to QR Code Converter

- Enter a URL or text in the terminal prompt.
- A QR code will be generated and displayed in a new window.
- Type 'exit' to close the application.

## Code Overview

### `main.py`

This script creates the main window with buttons to access each tool.

### `notepad.py`

A simple notepad application using Tkinter, allowing text input, saving, and clearing.

### `qr-code.py`

A script to generate a QR code from a given URL or text input, displaying the QR code in a new window.

### `whiteboard.py`

A digital whiteboard application using Tkinter, allowing drawing with different colors and clearing the canvas.

### `work-timer.py`

A Pomodoro timer implemented with Tkinter, featuring start, stop, and live clock display.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

This project was developed as part of an internship training program. Special thanks to the trainers and mentors for their guidance and support.
