# Quiz Console App

A simple console-based quiz application built in Java t
## Features

- **Interactive Quiz**: Users answer multiple-choice questions through the console
- **Score Calculation**: Automatically calculates and displays the user's final score
- **Question Management**: Questions are structured using a `Question` class with multiple-choice options
- **Simple Interface**: Easy-to-use command-line interface

## Project Structure

- **Main.java** - Entry point of the application
- **Question.java** - Data model representing a single quiz question with id, question text, four options, and correct answer
- **QuestionService.java** - Service class that manages quiz questions, user interactions, and score calculation

## How to Run

1. Compile the Java files:

   ```bash
   javac Main.java Question.java QuestionService.java
   ```

2. Run the application:

   ```bash
   java Main
   ```

3. Answer each question by entering your choice (1-4 or the option text)

4. After answering all questions, your final score will be displayed