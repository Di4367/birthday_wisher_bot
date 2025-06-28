🎉 Birthday Wisher Bot 🎂

This Python automation script reads a list of birthdays from a CSV file, randomly selects a pre-written birthday letter, personalizes it with the recipient's name, and sends a warm birthday wish to their email — **automatically** on their special day!

📌 Features

- Reads birthday data from `birthdays.csv`
- Checks if today matches anyone's birthday
- Selects one of 3 heartwarming templates from `letter_templates/`
- Replaces `[NAME]` with the actual name
- Sends a personalized email through Gmail using SMTP

💡 Project Motivation

I wanted to build something meaningful that saves time yet keeps emotions intact — a thoughtful gesture automated with code.  
Instead of forgetting or rushing to wish someone, let your Python bot send birthday love right on time! 💌

🛠️ Tech Stack

- Python 3.x
- `pandas` for data handling
- `smtplib` for sending emails
- `datetime` for date logic
- Gmail App Passwords for secure email login

🧪 How to Use

1. Add birthdays in the CSV file:

2. Add 3 letters in `letter_templates/` folder:
- Use `[NAME]` as placeholder.

3. Replace your credentials in `main.py`:
```python
MY_EMAIL = "your_email@gmail.com"
MY_PASSWORD = "your_app_password"

