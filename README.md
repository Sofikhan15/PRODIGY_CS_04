# PRODIGY_CS_04
This Python script implements a basic keystroke logger that captures and saves all keyboard input to a specified log file using the pynput library.

How It Works:
Logging Keystrokes: The script records each key press and saves it to a log file (default is keylog.txt).
Handling Special Keys:
Spaces are logged as ' '.
Enter is logged as a newline.
Keys like Backspace, Shift, Ctrl, and Alt are logged with their labels (e.g., [BACKSPACE]).
Stopping the Logger: The logging will stop when the 'Esc' key is pressed.
Usage:
Install Requirements: Make sure pynput is installed (pip install pynput).
Run the Script: Start the script to begin capturing keystrokes.
Stop the Logger: Press 'Esc' to stop the logger.
Disclaimer:
This script is for educational purposes only. Unauthorized use of keyloggers may violate privacy laws and ethical standards. Always ensure you have permission before using this tool on any system.
