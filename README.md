# Deliverable-Blackjack-
black jack card game 
[Deliverable-1.docx](https://github.com/user-attachments/files/15749021/Deliverable-1.docx)
 Project design and development 
This project’s objective is to use the Apache NetBeans IDE to create a blackjack card game. The ultimate goal is to develop a fully working game with basic game mechanics and a user interface that lets players play blackjack against a dealer.

Description
In the card game known as blackjack, or 21 for short, players' goal is to have a hand value that is as near to 21 as possible without going over. After receiving their first two cards, each player has the option to "hit" (draw further cards) or "stand" (keep the hand they already have). The goal is to have a hand value that is higher than the dealer's without going over 21, and the dealer also plays by certain restrictions.

Current Base Code
This project's first foundation code was created in Java. A basic command-line interface for dealing cards and figuring out hand values is included. There are now basic classifications like Deck, Hand, and Card. The coding style adheres to Java standards, using PascalCase for class names and CamelCase for variable names. Future work may take into account design patterns like Strategy for various game rules and Singleton for deck management.
 
Project Scope:-
Team members –
1.	Preet Pineshkumar Patel – Developer 
2.	Dhananjay Raghunath Yadav – Code tester 
3.	 Jeet Patel – Documentation.

Technical Scope
The project will include a graphical user interface (GUI) to enhance user interaction, using JavaFX or Swing. The game will be complete when players can register, play multiple rounds, view their scores, and receive notifications of wins or losses.
High-Level Requirements
User registration: The ability to register and log in is a need for players.
Keep score and player details indefinitely.
Play the game by following the basic rules of blackjack (hit, stand, bust, etc.).
Dealers adhere to basic blackjack rules in their play reasoning.
User Interface: Create a graphical user interface (GUI) to show the dealer hand, player hands, and controls for the game's operations.
Track and show player scores and game results with score tracking.
scores are kept on file for players who have registered.
Alerts:
Update players in real time on the status of the match (win, defeat, draw, etc.).
Inform players of their hand worth as of right now.

Design Considerations
Encapsulation:
The Card class, which has private fields and public getters, incorporates a card's attributes (suit, rank). 
The Deck class is responsible for organizing the deck, handling card shuffles and deals, and encapsulating the list.

Delegation:
• The Dealer and Player classes get tasks from the Game class, which maintains a manageable and modular game logic. 
• The Card class is responsible for handling card-related actions, whereas the Hand class calculates hand values.


Flexibility/Maintainability:
The codebase is extendable through the use of abstract classes and interfaces to specify common behaviors. 
Following SOLID guidelines to make sure the code is simple to edit and expand in subsequent versions.

Summary
This design document describes how to use the Apache NetBeans IDE to create a blackjack game. The project entails developing a playable and intuitive game that adheres to blackjack rules, keeps score, and has an interactive graphical user interface. Robust object-oriented concepts will be implemented, Java coding standards will be followed, and an organized Git repository will be used to oversee the development process.

