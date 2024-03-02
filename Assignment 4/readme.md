Deck of Cards Java Program
Overview
This Java program is designed to simulate a deck of 52 cards and provides various functionalities to interact with the deck. The program utilizes a menu-driven approach to offer options such as displaying the deck, shuffling, drawing cards, comparing cards, finding cards by rank and suit, and dealing a hand of cards.

Classes
1. Deck Class
The Deck class represents a deck of cards and includes methods for creating, displaying, and manipulating the deck.
Public Methods
createDeck(): Initializes the deck with 52 cards.
displayMenu(): Presents a menu for the user to interact with the deck.
Private Methods
printDeck(): Prints all the cards in the deck.
shuffleDeck(): Shuffles the cards in the deck.
drawCard(): Draws a card from the deck.
emptyDeck(): Clears all cards from the deck.
printCard(): Prints a specific card from the deck.
compareCard(): Compares two cards based on their indices in the deck.
sameCard(): Checks if two specified cards in the deck are the same.
findCard(): Finds a card in the deck based on user-specified rank and suit.
dealHand(): Deals a random hand of 5 cards from the deck.

3. Main Class
The Main class contains the main method to initialize the deck and start the menu-driven interface.
Usage
Compile the Java files using a Java compiler.
Run the Main class.
Follow the on-screen menu prompts to interact with the deck.
Notes
The program utilizes the Vector class to manage the deck of cards.
The menu provides a user-friendly interface for various card-related operations.
Ensure input validation for user inputs to enhance the program's robustness.
