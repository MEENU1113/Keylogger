# Keylogger

This Python project implements a simple keylogger using the pynput library. The keylogger is able to log all keystrokes made by the user and writes them to a file called "log.txt". The program runs in the background and is controlled by a listener that listens for key presses and releases. 
The program makes use of the on_press() and on_release() functions to monitor and log keystrokes. When a key is pressed, its value is added to the keys list, and the write_file() function is called to write the contents of the keys list to the log file. When the "esc" key is pressed, the listener is stopped and the program exits. 
The code is simple to read and understand, and can be easily modified to meet the user's specific requirements.
