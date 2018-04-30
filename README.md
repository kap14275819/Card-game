# Card Game Project 2
## Core Requirements:
#### The core requirements are to have set of cards which will be randomised and then shown to the player. Then the player will be asked whether the next card will 'higher' or 'lower'. Once the player has decided, it will then display whether they are correct or not and if they guess correctly they will win a 'cash' prize. 

## Game Description:
#### This game is about winning a card game to win a prize at the end. This card game is a 'high' or 'low' card game which means that there is a deck of cards which then one is randomly selected and then displayed. Once the user has read this card they have to guess whether the next card will be 'higher' or 'lower'. If the guess is correct they then win a cash prize. In the game also betting has been implemented which allows them to choose a small amount of money to bet with to then reach a score of 1000 or more.

## User Stories:

#### As a user I would like to have a random card selected at the beginning and displayed 
#### As a user I would like to be able to guess whether the next card is higher or lower
#### As a user I should get feedback whether the guess I made was correct or incorrect
#### As a user I would like to have the second random card displayed to show if incorrect or correct
#### As a user I would like to have the name of the card displayed each time instead of a number
#### As a user I would like to be able to place a bet also whilst guessing if higher or lower
#### As a user I should get feedback when I have lost all my money from betting or I have reached the goal set

## Flow Chart:

![flowchart](https://github.com/kap14275819/Card-game-Project-2/blob/master/card%20game.jpg)

## Product Backlog:

### High Level Function Requirements
#### Create set of cards
#### Create randomiser
#### Create a decision for player to input higher or lower
#### Display cash prize when game is won
#### Have a new randomised card displayed each time

### High Level Non-Functional Requirements
#### Give cards actual suits and ranks
#### Allow player betting
#### Allow Input of player name

## Sprint Backlog:

#### As a user I would like to have a random card selected at the beginning and displayed 
#### As a user I would like to be able to guess whether the next card is higher or lower
#### As a user I should get feedback whether the guess I made was correct or incorrect
#### As a user I would like to have the second random card displayed to show if incorrect or correct
#### As a user I would like to have the name of the card displayed each time instead of a number
#### As a user I would like to be able to place a bet also whilst guessing if higher or lower
#### As a user I should get feedback when I have lost all my money from betting or I have reached the goal set

## Design Documentation:
### Process of Implementation:
#### 1. The first step that was taken was to create the randomiser which will randomise the set of numbers/cards which will then be displayed.  
#### 2a. Once the randomiser was completed the decision function was created for the player to then guess whether the next number will be 'higher' or 'lower'.
#### 2b. Another function was also created with this to check the player’s response and if that response was correct to the correlation of the number being higher or lower than the previous one.
#### 3a. If the player wins there has to be some sort of in-game prize, so a 'cash' prize is given if the player correctly guesses the next card to be either 'higher' or 'lower. This is displayed and banked in a variable which stores if for the player to use later.
#### 3b. The banked money that is given at the beginning and during the game allows the player to bet so that they can gain a bigger prize win at the end of each guess. So a small betting function is made to allow players to bet before the game starts. 
#### 3c. A set goal is also created for the player on the betting so that when they reach around £1000 they will end the game instead of having to end the game after each round. Also if the player reaches ZERO in cash then the game will end as the player has no more cash to bet. 
#### 4. Extra implementations were added such as changing the numbers to actual cards shown. For example, "King of Hearts". To have this done two types of randomisers will be added in which has a specific set of words within so that it may print out different set of cards each time. 

## Gantt Chart
![ganttchart](https://github.com/kap14275819/Card-game-Project-2/blob/master/Gannt%20Chart%20porject%202.png)

### IDE used and Features:
#### The type of Integrated Development Environment that was used was 'Repl.it'. This is an online IDE which has various languages to choose from. There is also a compiler on this online IDE so you are also able to run the code, it of course consists of a text editor so you can have the code running and read through the code. It also has a data dictionary and a data file viewer.

#### ![IDE](https://github.com/kap14275819/Card-game-Project-2/blob/master/IDE2.png)

### Debugging Process:
#### The IDE has a small of debugging process as it shows if there are any errors within the code but it does not show all the types of debugging processes. Some of the debugging you must write yourself if you want to check if that part of the program has worked correctly.

## Coding Standards:
#### Coding Standards are mainly used to make sure that your code looks precise and consistent so that you are able to come back to that part of the code and understand what you have wrote in that particular section. This also can ease the difficulty for other people who might be working with you on the program who will also be using the same coding standards. Here are some of examples of coding standards that i used:

### Indentation 
#### While writing my code, i used indentation rather than pressing space several times. I used this quite often, as firstly using the tab button saves more time in coding than pressing space multiple time or holding the button. Secondly, the tab button is universal to all text editors and IDE, so this will not have any problems in not working as each of them use indentation.

### Line Length Under 100
#### If in my code I would be writing a long line of code I would make sure that I would not go over 100 characters in length. The reason I chose to do this is because if I wrote over that amount this would then force the line of code to stretch the screen. This will then have to make me scroll horizontally back and forth to just read the last part of that line of code. By not having lines very long I can save time by not having to scroll to edit.

### Variable Names
#### The Variable names that were used with the code followed a clear standard. All names started with a capitalised letter and the names will be according to what they are storing and not have letters instead, for examples the variable for the input of a player’s name would be "Name". If multiple variables are storing similarly named data, then a number will be added to the end from 1 and then goes up depending on how many variables there will be.

### Commenting
#### Comments will be added on top of each code function, this will be done like this so that it will not make the line longer. By doing this will help me understand what that particular function does and how does it help with the rest of the program. This will help with errors as it may appear that a certain part of the program is not working so I know the function needs to be fixed.

### Curley Brackets
#### My brackets will be places at the end of the line rather than starting a new line as to save space and make the document shorter, it will also make my functions easier to read.

## Research:
#### The types of places that i used for research was usually forums such as 'stackoverflow' which helped on some parts of fixing code but also i used websites such as 'w3schools' which is a coding website and shows multiple different types of coding examples which helped to understand how some of the pieces of code worked. Other forums were also used that are not that known to look through code snippets which helped throughout the process.

## Evaluation and Teamwork:
#### The use of the IDE which helped in the work as the errors showed the problems that occur in the process of creating the game. Without the use of the IDE it would have made the project slightly more difficult but all the work went well and met the criteria set including the extension and adding some extra parts. There were some slight difficult parts to understand and to create but in the end it all came together and worked well. This work was managed by myself as it was an individual project without any teamwork. The research, coding and planning all was personally done which was quite good as it shows that I was able to complete this task without any help needed. The research and planning took its time but ended up all well in the end.

## Relationship between algorithm and code:
#### Since the program had been implemented as an algorithm then the best paradigm would be procedural. This is because the program does the process in computational steps, which is just like an algorithm. This is why the procedural paradigm is similar to the program.

