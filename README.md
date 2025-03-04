# Password Manager

## Summary
This Python script is a graphical password manager built using the `tkinter` library. It allows users to store and retrieve website credentials (email/username and password) in a secure JSON file. The application includes features such as password generation, data storage, and retrieval. Users can generate strong passwords, save them along with their associated website and email, and later retrieve the stored credentials by searching for the website name.

## Features
- **Graphical User Interface (GUI)**: The application uses `tkinter` to provide a user-friendly interface for managing passwords.
- **Password Generation**: Users can generate a strong, random password of 15 characters using a mix of uppercase and lowercase letters, numbers, and symbols.
- **Data Storage**: Website credentials (website, email, and password) are stored in a JSON file (`data.json`) for secure and persistent storage.
- **Data Retrieval**: Users can search for stored credentials by entering the website name. The application retrieves and displays the associated email and password.
- **Input Validation**: The application checks for empty fields and provides appropriate error messages.
- **Error Handling**: The application handles cases where the data file does not exist or the requested website is not found in the data file.

## How to Use
1. Run the script in a Python environment.
2. Enter the website name, email/username, and password (or generate a password using the "Generate" button).
3. Click "Add" to save the credentials to the JSON file.
4. To retrieve saved credentials, enter the website name and click "Search".
5. The application will display the associated email and password in a pop-up window.

## Requirements
- Python 3.x
- The `tkinter` library (included with Python by default).
- A `logo.png` file for the application logo (optional).

## Running the Program
To run the program, simply execute the script in your Python environment:
```bash
python main.py
```
