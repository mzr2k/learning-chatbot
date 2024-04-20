**Learning Chatbot**

This project implements a simple interactive chat bot using Python. The bot engages users in conversation, answering questions based on a pre-defined knowledge base stored in a JSON file. If the bot doesn't know the answer to a question, it prompts the user to provide it, thus allowing the bot to learn and expand its knowledge base dynamically. The bot utilizes the `difflib` library to find the best matching question from the knowledge base based on user input. This project is a great starting point for building more sophisticated conversational agents and can be easily extended or integrated into larger applications.

Features:
- Loading and saving of knowledge base from/to JSON files.
- Utilizes fuzzy string matching to find the best matching question.
- Allows users to contribute new questions and answers to expand the knowledge base.
- Provides a simple command-line interface for interaction.

