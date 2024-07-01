# Crorepati-app-using-Java

## Overview
The Crorepati App is a Java-based interactive quiz game inspired by popular television quiz shows. Players can test their knowledge across various categories and aim to win virtual money by answering multiple-choice questions correctly.

## Features
- *Multiple Categories:* Choose from a variety of categories such as General Knowledge, Science, History, and more.
- *Lifelines:* Incorporates lifelines such as Audience Poll, 50-50, and Phone-a-Friend to assist players during the game.
- *Progress Tracking:* Track player progress, winnings, and performance statistics.

## Object-Oriented Programming (OOP) Pillars Utilized

### 1. Encapsulation
Encapsulation is fundamental in organizing the app's structure and ensuring data security. Key aspects include:
- *Private Variables:* Instance variables like questionText, correctAnswer, and difficultyLevel are encapsulated within question classes.
- *Getter and Setter Methods:* Public methods ensure controlled access to encapsulated data, maintaining data integrity and security.

### 2. Inheritance
Inheritance is leveraged to establish a hierarchical relationship among different question types:
- *Base Question Class:* Question serves as the base class with common attributes and methods.
- *Derived Classes:* MultipleChoiceQuestion and TrueFalseQuestion inherit from Question, inheriting properties and behaviors while allowing for specialization.

### 3. Polymorphism
Polymorphism is demonstrated through method overriding and dynamic method binding:
- *Polymorphic Methods:* The displayQuestion() method in each question type class behaves uniquely based on its specific implementation.
- *Interface Implementation:* Implementing interfaces such as QuizQuestion ensures flexibility and interchangeability of question types.

### 4. Abstraction
Abstraction simplifies the complexity of underlying operations, focusing on essential functionalities:
- *GameEngine Abstraction:* GameEngine abstracts complex game logic into manageable components like startGame() and answerQuestion().
- *User Interface Abstraction:* Interfaces like UserInterface provide a streamlined experience for interacting with game functionalities.

## Installation
To install and run the Crorepati App locally, follow these steps:

1. *Clone the Repository:*
   
   git clone https://github.com/PavanManjunath23/Crorepati-app-using-Java
   
2. *Compile and Run:*
   
   javac Main.java
   java Main
   

## Usage
- Upon launching the app, select a category and start answering questions.
- Use lifelines strategically to maximize earnings and progress through higher difficulty levels.
- Track your winnings and performance statistics in the app's dashboard.
