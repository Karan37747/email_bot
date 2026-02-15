# email_bot
Automated bulk email sender with attachment support using Python, Gmail SMTP, CSV input, retry logic, and secure environment-based authentication.
# 📧 Email Sender Bot

I have a Python tool that helps me automate sending emails. This Python tool is really good for sending lots of emails that are personalized. I can add files to these emails. The Python tool uses Gmail to send these emails.

It gets the information about who to send the emails to from a file called a CSV file. Then it sends each person a message that's just, for them. The Python tool also keeps track of what happens to each email. If something goes wrong the Python tool tries again to send the email.

This project shows how to manage passwords by using environment variables. It does not use passwords that are written directly in the code. The project uses environment variables, for credential management instead of hard-coded passwords, which is what companies normally do. This way of managing passwords is considered a way to do things in the industry and the project follows this by using secure credential management.

---

## 🚀 Features

* ✅ Bulk email sending via Gmail SMTP

* ✅ Personalized messages using CSV data

* ✅ Attachment support

* ✅ Retry mechanism for failed sends

* They have to keep a record of whether the email was sent or not so that is what the logging of email send status is, for the logging of email send status is very important to track the email send status.

* ✅ Secure App Password handling via environment variables

* ✅ Clean and modular Python code

* ✅ Easy to configure and extend

---

## 🛠️ Tech Stack

* Python 3

* smtplib

* email.message

* csv

* ssl

* logging

* pathlib

---

## 📂 Project Structure

```

email_bot/

│

├── email_bot.py        # Main script

├── recipients.csv      # Recipient list

├── report.pdf          # Attachment file

├── email_log.txt       # Auto-generated log file

└── README.md           # Project documentation

```

---

## 🔐 Security (Important)

This project **does not store your Gmail password, in the code**.

It does not do that. Instead it uses a *environment variable**:

```

EMAIL_APP_PASSWORD

```

This keeps your credentials safe. That makes the project a good fit for GitHub and the way people work on projects in a real production setting. The project is suitable, for GitHub and production style workflows because it keeps your credentials safe.

---

## ⚙️ Setup Instructions

### 1️⃣ Enable Gmail App Password

* Turn ON **2-Step Verification** in your Google account

* Generate an **App Password**

* Copy the 16-digit password

---

### 2️⃣ Set Environment Variable (Windows)

Open CMD and run:

```cmd

setx EMAIL_APP_PASSWORD "your_app_password_here"

```

⚠️ After this:

* Close CMD

* Restart VS Code

---

### 3️⃣ Install Requirements

```bash

pip install pandas

```

*This is only necessary if the script really needs it. The script mostly uses libraries that are already built in*

---

### 4️⃣ Prepare recipients.csv

Example format:

```csv

email,name,company

user1@gmail.com,John Doe,Microsoft

user2@gmail.com,Jane Smith,Google

```

---

### 5️⃣ Run the Script

```bash

python email_bot.py

```

---

## 📝 This Is How It Works

The system is made up of a simple steps.

It starts with the user doing something.

The user does this thing. That is what makes the system work.

The system is called the system because it is a system.

This system has many parts and the parts all work together to make the system work.

The system works because of the way the parts work together.

The system is a system because it does what it is supposed to do.

It does this thing. That is what makes the system a good system.

The system is good, at doing what it does.

This is what the system does.

1. Reads recipient data from CSV

2. Creates personalized email for each user

3. Attaches the specified file

4. Sends email via Gmail SMTP

5. Retries on failure

6. Logs success/failure to `email_log.txt`

---

## 📊 Use Cases

* The company will be giving out internship offers to students. This is an opportunity for students to get some experience in the field they are interested, in. The internship offer distribution process is very important. The internship offer distribution will help students to learn things and gain some valuable experience. The internship offer distribution is something that many students look forward to.

* Automated report sending

* Bulk notifications

* Alert systems

* HR communication automation

---

## ⚠️ Important Notes

* Do not use the password you normally use for Gmail

* You should always use the Gmail App Password when you need to use Gmail. The Gmail App Password is a password that you use with the Gmail app. Always remember to use the Gmail App Password for the Gmail app.

* It is very important to keep the environment variables. The environment variables should always be kept secret. This is because the environment variables have a lot of information that people should not know about. So we have to keep the environment variables at all times. The environment variables are very important. We need to keep them secret.

* ⚠️ Gmail will probably stop your emails if you send a lot of emails quickly so be careful with Gmail when you are sending many emails to people because Gmail does not like it when you send emails too fast, with Gmail.

---

## 🚀 Future Improvements

* HTML email support

* Rate limiting control

* Email open tracking

* Multi-threaded sending

* .env file support

* GUI version

---

## 👨‍💻 Author

**Karan Rattiwal**

CGC UNIVERSITY MOHALI

---

## ⭐ If You Like This Project

Give it a ⭐ on GitHub and feel free to fork and improve!

---
