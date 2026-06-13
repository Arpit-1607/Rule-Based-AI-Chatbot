# 🤖 Rule-Based AI Chatbot

A simple and interactive Rule-Based AI Chatbot developed using Python. This chatbot uses dictionary-based responses and control flow logic to simulate human conversation. It continuously interacts with users until an exit command is given.

---

## 📌 Project Overview

This project demonstrates the fundamental concepts of Artificial Intelligence using deterministic logic instead of machine learning. The chatbot processes user inputs and responds based on predefined rules.

The project focuses on:

- Control Flow
- Decision Making
- Dictionary Mapping
- Input Sanitization
- Continuous Interaction Loop

---

## ✨ Features

✅ Greeting Responses

✅ Exit Commands

✅ Random Responses

✅ Date and Time Support

✅ Joke Generator

✅ User-Friendly Interface

✅ Continuous Chat Loop

✅ Dictionary-Based Intent Matching

✅ Default Response for Unknown Inputs

---

## 🛠 Technologies Used

- Python 3.x
- Random Module
- Datetime Module

---

## 📂 Project Structure

```
Rule-Based-AI-Chatbot/
│
├── chatbot.py
├── README.md
├── chat_history.txt
├── screenshots/
│     └── output.png
└── requirements.txt
```

---

## 🚀 Installation

### Clone the repository

```bash
git clone https://github.com/Arpit-1607/Rule-Based-AI-Chatbot.git
```

### Navigate to the project directory

```bash
cd Rule-Based-AI-Chatbot
```

### Run the chatbot

```bash
python chatbot.py
```

---

## 💬 Available Commands

| User Input | Bot Response |
|------------|--------------|
| hello | Greeting message |
| how are you | Bot status |
| name | Bot introduction |
| joke | Random joke |
| date | Current date |
| time | Current time |
| help | List of commands |
| bye | Goodbye message |
| exit | Close chatbot |

---

## 🖥 Example Output

```text
========================================
🤖 DecodeBot Started
Type 'exit' to quit
========================================

You: hello
Bot: Hi there!

You: joke
Bot: Python is my favorite snake.

You: how are you
Bot: Awesome!

You: exit
Bot: Goodbye! 👋
```

---

## ⚙ Working Principle

1. User enters a message.
2. Input is converted to lowercase and sanitized.
3. The chatbot searches for a matching key.
4. A predefined response is returned.
5. If no match is found, a default message is displayed.
6. The loop continues until the user enters `exit`.

---

## 📈 Future Improvements

- GUI Interface using Tkinter
- Voice-Based Assistant
- Weather API Integration
- Calculator Feature
- To-Do List Management
- Quiz System
- Chat History Storage
- Machine Learning Integration

---

## 🎯 Learning Outcomes

Through this project, I learned:

- Python Programming
- Conditional Statements
- Dictionaries
- Loops
- User Input Handling
- Rule-Based AI Systems

---

## 📸 Screenshots

Add screenshots of the chatbot output here.

---

## 👨‍💻 Author

**Arpit Yadav**

GitHub: https://github.com/Arpit-1607

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

---

## 📜 License

This project is open-source and available under the MIT License.
