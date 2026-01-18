# 📧 MINI EMAIL SIMULATOR(Python OOP)

This project is a simple **console-based email system** built using Python and Object-Oriented Programming. It simulates how users can send, receive, read, and delete emails.

---

## 🚀 Features

* Create users
* Send emails between users
* View inbox
* Read full emails
* Delete emails
* Automatic timestamps
* Read/Unread status

---

## 🧱 Project Structure

* **Email** → Represents a single email message
* **Inbox** → Stores and manages received emails
* **User** → Represents a user who can send and manage emails
* **main()** → Demonstrates how everything works together

---

## ▶️ How to Run

```bash
python main.py
```

Make sure your file contains the classes and the `main()` function.

---

## 🧩 Step-by-Step Usage

### ✅ Step 1: Create Users

```python
tory = User('Tory')
ramy = User('Ramy')
```

This creates two users, each with their own inbox.

---

### ✅ Step 2: Send Emails

```python
tory.send_email(ramy, 'Hello', 'Hi Ramy, just saying hello!')
ramy.send_email(tory, 'Re: Hello', 'Hi Tory, hope you are fine.')
```

Each call:

* Creates an `Email` object
* Sends it to the receiver’s inbox
* Prints a confirmation message

---

### ✅ Step 3: Check Inbox

```python
tory.check_inbox()
ramy.check_inbox()
```

Displays a personalized inbox header and lists all received emails.

---

### ✅ Step 4: Read an Email

```python
tory.read_email(1)
```

* Opens the first email
* Marks it as **Read**
* Displays full details (sender, subject, time, body)

---

### ✅ Step 5: Delete an Email

```python
tory.delete_email(1)
```

Deletes the selected email from the inbox.

---

## 🧠 Example Output

```
Email sent from Tory to Ramy!
Email sent from Ramy to Tory!

Tory's Inbox:
1. [Unread] From: Ramy | Subject: Re: Hello | Time: 2026-01-18 10:30
```

---

## 🎯 Learning Outcomes

* Real-world use of classes and objects
* Object interaction (User → Inbox → Email)
* Clean separation of responsibilities
* Practice with methods, attributes, and encapsulation

---

## 📌 Future Improvements (Optional)

* Reply feature
* Sent mail folder
* Search emails
* Save emails to file/database
* Menu-driven interface

---

🔥 Built for learning, experimenting, and leveling up Python OOP skills.
