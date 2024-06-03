# Python-Program for Menu-Driven Systems Operations
This Python program provides a menu-driven interface to perform various system operations. Users can select from options to display the local date and time, show the local computer's IP address, list a remote home directory, back up a remote file, and save a web page. The program ensures robust error handling and provides clear feedback to the user.

# Features
1. Show Date and Time
  Displays the current date and time of the local computer.
  
2. Show IP Address
  Retrieves and displays the IP address of the local computer.
  
3. Show Remote Home Directory Listing
  Connects to a specified remote computer and lists the contents of its "Home" directory.
  
4. Backup Remote File
  Prompts the user for a file path on the remote computer and creates a backup copy with a .old suffix.
  
5. Save Web Page
  Asks the user for a URL and saves the content of the web page to a local file.
  
6. Quit
  Exits the program cleanly without error messages.

# Instructions
1. Running the Program
- Execute the program using a Python interpreter.
- A menu will be displayed with options to choose from.

2. Menu Options
- Press the corresponding number for the desired operation (e.g., press 1 to show the date and time).
- Follow the prompts for options that require additional input (e.g., URL for saving a web page).

3. Dependencies
- Ensure you have Python installed on your system.
- Required libraries: socket, paramiko, and requests. Install them using pip if they are not already available.

4. Remote Access Configuration
- The remote computer's IP address, username, and password are hard-coded for simplicity. Modify these values in the source code as needed.

# Conclusion
This program serves as a practical tool for performing basic system operations and demonstrates key programming skills, including network communication, file handling, and user interaction in Python.
