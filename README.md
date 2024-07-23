# Python Birthday Wisher Project
This Python project automates sending personalized birthday wishes to your loved ones via email!

** Features: **

Stores birthdays in a user-friendly format (Excel sheet - bdata.xlsx).
Uses the smtplib library to send email greetings through your Gmail account.
Leverages the pandas library to efficiently manage and manipulate birthday data.
Utilizes the datetime library for date and time calculations to identify upcoming birthdays.

** Project Structure: **

data.xlsx: This Excel spreadsheet stores birthday information in a tabular format. It includes columns for names, email addresses, and a message to personalize the greetings.



birthday_wisher.ipynb: This Python script is the core of the project. It will:
Load birthday data from the data.xlsx file using pandas.
Identify upcoming birthdays using datetime calculations.
Generate personalized birthday messages for each recipient using their names and the message from the spreadsheet.
Send email greetings through Gmail's SMTP server using smtplib.
Benefits:

Never forget a birthday again! Automate sending well wishes to ensure your loved ones feel remembered on their special day.
Personalized greetings: Craft unique messages for each recipient using their names and a pre-written message.
Easy to use: This project utilizes readily available tools like Excel and Gmail.

