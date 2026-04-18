# 🧑‍💻 Personal Data Collector (Python)


A simple interactive Python program that collects basic personal information from the user and displays details about the entered data.

# 📌 Features

Takes user input:

Name (string)

Age (integer)

Height (float, in meters)

Favourite number (integer)

Displays:

Data types of each input

Memory ID of each variable

Calculates approximate birth year based on age

# 🚀 How It Works


The program prompts the user to enter personal details.

It stores the inputs in variables of appropriate data types.

It prints:

The type of each variable (e.g., str, int, float)

The memory address using id()


It calculates the birth year using:

birth_year = current_year - age

# 🛠️ Requirements


Python 3.x

# ▶️ How to Run



Navigate to the project folder:

cd personal-data-collector

Run the program:

python main.py
💡 Example Output
Welcome to the interactive personal data collector!

Please enter your name: John
Please enter your age: 20
Please enter your height in meters: 1.75
Please enter your favourite number: 7

Thank you! Here is the information we collected:

<class 'str'> 140123456789456
<class 'int'> 140123456789520
<class 'float'> 140123456789600
<class 'int'> 140123456789680

Your birth year is approximately: 2006 (based on your age of 20)

Thank you for using the personal data collector. Goodbye!
⚠️ Notes
The birth year is an approximation (does not account for whether the birthday has occurred this year).
The program assumes valid input (no error handling for invalid data yet).
📈 Future Improvements
Add input validation (handle incorrect data types)
Use current system date instead of hardcoding the year
Display user-friendly summaries instead of raw id() values
Add GUI version (Tkinter or web-based)
