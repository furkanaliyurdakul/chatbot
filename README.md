# Chatbot for Trends in AI for BI - Team Pacman

This repository hosts the code for a sophisticated chatbot developed by Team Pacman. The chatbot is part of the coursework for "Trends in AI for Business Informatics" and is designed to assist students in a range of academic tasks including course recommendations, exam queries, and updating personal information.

## Features

- Intelligent Course Recommendations
- Inquiries about Exam Registrations and Grades
- Management of Personal Information (Address and Surname Changes)
- Interactive User Interface with Abort Functionality
- Custom Intent Recognition and Processing

## Prerequisites

- Python 3.x
- NLTK (Natural Language Toolkit)
- SQLite3 for Database Interaction
- FuzzyWuzzy for Fuzzy String Matching
- Numpy

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/furkanaliyurdakul/chatbot.git
2. Navigate to the cloned directory:
   ```bash
   cd chatbot
3. Install the required packages:
    ```bash
    pip install nltk numpy fuzzywuzzy
4. Additional NLTK Downloads
    ```bash
    python -m nltk.downloader wordnet punkt stopwords averaged_perceptron_tagger
Ensure SQLite3 is installed on your system.

## Usage

1.    Launch the Jupyter Notebook or your Python IDE.
2.    Execute the chatbot.ipynb file to start the chatbot.
3.    Interact with the chatbot in the provided interface for various academic-related queries and tasks.

After starting the chatbot, you can interact with it by typing commands related to the features you want to use. Below are the key features and some example phrases you can use:

- **Change Address**
  - Try saying: "I need to update my address", "Change my address to [new address]".

- **Change Surname**
  - Try saying: "Change my surname to [new surname]", "I got married and need to update my surname".

- **Register for an Exam**
  - Try saying: "I want to register for an exam", "How do I enroll in a course?".

- **Deregister from an Exam**
  - Try saying: "I need to deregister from a course", "Withdraw from [course name] exam".

- **Query Exam Status**
  - Try saying: "Am I registered for [course name]?", "What’s my exam status for [course name]?".

- **Query Exam Grade**
  - Try saying: "What's my grade for [course name]?", "Show me my exam results".

- **Suggest Course**
  - Try saying: "Can you suggest a course for me?", "What course should I take next?".

- **Abort Command**
  - Use this to stop the current action or exit a process, say: "Abort", "Stop", "Cancel".

Remember, the chatbot is designed to understand natural language, so feel free to phrase your requests in a way that feels natural to you. It uses keywords from your input to determine the intent and respond accordingly.

## Comparison with Naive Bayes Classifier

The last cell of the of notebook executes a comparison of the two approaches to identify intents.
It is necessary that the previous cells are run so all dependecies and the chatbot object are available.
The output of the function may vary with each run as the test and train set are randomly selected with each creation of the chatbot object.

# Team Pacman:

- [Furkan Ali Yurdakul](https://github.com/furkanaliyurdakul)
- [Marlen Hima](https://github.com/Marlen0307)
- [Michael Nowak](https://github.com/daFaultier)
- [Bruno Hyska](https://github.com/BrunoHyska)