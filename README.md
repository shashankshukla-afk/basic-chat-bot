# 🤖 Python Fundamentals Chatbot

A simple, interactive, text-to-speech (TTS) chatbot designed to help users review and test their basic Python programming fundamentals.

This project was developed as a hands-on exercise to practice core Python concepts, including **File I/O**, **Dictionaries**, **Loops**, **Conditional Statements**, and **Error Handling**.

---

## ✨ Features

* **Fundamentals Review:** Provides definitions and explanations for over 30 essential Python topics (Variables, Data Types, Loops, Functions, etc.).
* **Text-to-Speech (TTS):** Uses the `pyttsx3` library to speak the responses, offering an auditory learning experience.
* **Modular Design:** Separates the core application logic (`main_chatbot.py`) from the knowledge base data (`knowledge.py`) using Python modules for clean code.
* **Robust Input:** Uses string cleaning methods to ensure the chatbot accurately recognizes commands regardless of user capitalization or extra spacing.

---

## 🛠️ Installation and Setup

This project requires Python 3.x and the `pyttsx3` library.

### Prerequisites

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/shashankshukla-afk/BASIC_CHATBOT.git](https://github.com/shashankshukla-afk/BASIC_CHATBOT.git)
    cd BASIC_CHATBOT
    ```

2.  **Install Dependencies:**
    ```bash
    pip install pyttsx3
    ```

### Running the Chatbot

1.  Execute the main script from your terminal:
    ```bash
    python main_chatbot.py
    ```
2.  The chatbot will display a list of known questions. Enter a question (e.g., `what is a list`) and listen to the response!

---

## 📚 Core Topics Covered (for Portfolio Reference)

This project successfully implements and demonstrates the following Python fundamentals:

* **Variables and Data Types**
* **Input/Output (I/O)**
* **Operators**
* **Conditional Statements** (`if`, `elif`, `else`)
* **Loops** (`while` loop for conversation flow, `for` loop for printing the menu)
* **Python Collections** (Lists and Dictionaries for the knowledge base)
* **Functions** (`speak()` function for TTS, modularized logic)
* **File I/O (Basic)** (Importing data from `knowledge.py` module)
* **Basic Error Handling** (`try...except` block for input/runtime errors)

---

## 🚀 Future Enhancements

* Convert the `knowledge.py` dictionary into a **JSON file** and load it using the `json` module.
* Implement basic **multi-word keyword matching** to handle slightly different phrasing from the user.
* Add a feature to save the chat history to a text file using File I/O.

---

## 🧑‍💻 Author

**Shashank Shukla**
* GitHub: [shashankshukla-afk](https://github.com/shashankshukla-afk)
