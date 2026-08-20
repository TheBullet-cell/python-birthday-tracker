# 🎂 Birthday Tracker – Python Project #1

## 📌 Description
A simple Birthday Tracker built in Python. This project helps beginners understand dictionaries, while loops, and user input by creating an interactive program that stores and retrieves birthdays.

## ✨ Features
- Store names and birthdays in a dictionary.
- Look up birthdays by name.
- Add new birthdays dynamically.
- Continue running until the user decides to quit.

## 🚀 How to Run
1. Make sure you have Python installed.
2. Clone this repository:
   ```bash
   git clone https://github.com/ZeroBullet/birthday-tracker.git
Run the scirpt:
python birthday_tracker.py

Code:
```python
birthdays = {"Mark": "1990-09-10", "John": "2000-03-15", "Lora": "2001-05-10"}

while True:
    print("Enter a name: ")
    name = input()
    
    if name == "":
        break

    if name in birthdays:
        print(birthdays[name] + " is the birthday of " + name)
    else:
        print("I don't have birthday information for " + name)
        print("What is their birthday?")
        bday = input()
        birthdays[name] = bday
        print("Birthday database updated.")
```

🧠 What I Learned
Dictionaries: How to store and retrieve data using keys.

While Loops: How to keep the program running until the user exits.

If/Else Conditions: How to check if data exists and act accordingly.

User Input: How to get and use input from the user.

🤝 Contributing
Feel free to fork this repository and improve it!


📺 Social
Youtube: @ZeroBulletSecurity

