# Card Game Project 2

## Game Description:
#### ThIs game is about winning a card game to win a prize at the end. This card game is a 'high' or 'low' card game which means that there is a deck of cards which then one is randomly selected and then displayed. Once the user has read this card they have to guess whether the next card will be 'higher' or 'lower'. If the guess is correct they then win a cash pize. In the game also betting has been implemented which allows them to choose a small amount of money to bet with to then reach a score of 1000 or more.

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
#### The first thing that was first done was to create a randomiser which can randomise a set of numbers which then will be displayed. Once that was done the decision function was created for the player to guess whether the next number will be 'higher' or 'lower'. Once the player was allowed to input 'higher' or 'lower', then another function was created to check if the player was correct and then the next number is displayed to the player. At the end it then displays a 'cash' prize which the player has won. For the extras items implemented was the betting which, allowed the player to place a bet before the the second card has been reavealed and to make the numbers to actual cards. For example, "King of Hearts". This is what will be displayed, this was done by having two types of randomiser which has a specific set of words which were the rank of the card and the suit. This then made the game feel like it was showing an actual set of cards instead of numbers. The betting also allowed the player to play more games instead of playing one round and then winning a cash prize. The goal now was to achieve around £1000 which was the cash goal for each player. Once they have reached above or at that score the game would end but if they have lost it all then the game will end showing that they have lost all their money.

### IDE used and Features:
#### The type of Intergrated Development Enviroment that was used was 'Repl.it'. This is an online IDE which has various languages to choose from. There is also a compiler on this online IDE so you are able to run the code, it of course consists of a text editor. It also has a data dictionary and a data file viwer.

### Debugging Process:
#### The IDE has a small of debugging process as it shows if there are any errors within the code but it does not show all the types of debugging processes. Some of the debugging you must write yourself if you want to check if that part of the program has worked correctly.

### Coding Standards:
#### While writing my code, indenting was used more often than spacing this is mainly because it saves time instead of repeatedly pressing or holding the space button. Also commenting throughtout the code was done so that when looked over it can show what this part of code does exactly and how it works with the rest of the game.

### Evalutation:
#### The use of the IDE which helped in the work as the errors showed the problems that occur in the process of creating the game. But all the work went well and met the critera set including the extension and adding some extra parts. There were some slight difficult parts to understand and to create but in the end it all came together and worked well.

### Relationship between algorithm and code:
#### Since the program had been implemented as an algorithm then the best paradigm would be procedural. This is because the program does the process in computational steps, which is just like an algorithm. 
