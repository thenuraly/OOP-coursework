# OOP-coursework
Quick Description:
This is a OOP Python coursework. Game of Tic Tac Toe and result recording .txt file. 

# Start of the course work report:
# INTRODUCTION:

As a topic for my 1st year course-work assignment, I chose the game of tic tac toe. The game is single-player played against the AI. Where the player plays for “X” and goes first, whereas AI plays as “O” and goes second. The AI is very strongly trained, and I am sure that you cannot win it :)

To run the game, PyCharm IDE should be installed to your PC. I used interpreter Python 3.9, which is recommended to use to run this game. Also, libraries such as pygame and time were downloaded, which are also highly recommended in your PC to be downloaded.

Opening the code in the folder, called OOP Project. And Copying the code as well as dowloading images and opening the file game_results copy.txt you can easily start to enjoy the game

# Body/Analysis:

My code is a single, simple OOP file performed by the Polymorphism, Inheritance, and Encapsulation OOP pillars, and 2 of the ways of the desgn patterns called - Singleton and Observer. To my regret I was not able to use Abstraction method which could allow me to "hide" complex implemntations and to show only neccessary functions. I believe, it is because I have chosen simple topic to perform and though I do not need this method.

Going further, I want to show with examples of how I used 3 pillars of OOP with the examples of the code. 
1) Encapsulation:If we will look at the class "Square", we see that attributes such that x, y, content,image and others; methods such as clicked and update are also encapsulates.
2) Inheritance: Our main class called Square here inherits from the base-class of the PyGame called pygame.sprite. Example: class Square(p.sprite.Sprite): (7 line)
3) Polymorphism: here the method def update() (20 line) is the example of the Polymorphism. Square class are added to the square_group sprite group and updated in the game loop using the update() method.


Now, let's talk about 2 different design patterns I used:
1) Singleton: While not explicitly implemented, the use of global variables and methods throughout the code somewhat resembles the Singleton pattern. For example, the board, turn, won, and compMove variables are global and accessible from multiple functions.
2) Observer: The code follows the Observer pattern in the game loop, where it continuously listens for events such as mouse clicks (MOUSEBUTTONDOWN) and updates the game state accordingly. The game loop acts as the subject, while the event-handling code acts as observers that react to changes in the game state.


Overall, my code contains single class filerunning the game onb the PyGame, and it covers almost every requirment.

# Results: 

It was my first time ever using the PyCharm library and creating video-games,which I believe, will be a starting point for me to study more about current library and start studying about more advanced game engines. Personally, I think that I covered almost every topic required to do, and get a solid mark for the job I have done. The most challenging part was the adding .txt file, since I have never done it before 



