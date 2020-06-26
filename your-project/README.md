<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Blackjack Game
*Pol Lorente*

*Data Analitycs Ironhack bootcamp. June 2020*
*26/06/2020*

## Content
- [Project Description](#project-description)
- [Rules](#rules)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description
The project consists on the creation of a computer game of Blackjack for one or more players. Players introduce their initial money and with bets are playing against the Dealer. If a player loses all the money, he/she is eliminated.

## Rules
Blackjack, also known as twenty-one, is the second most popular gambling game, after Poker.
The players do not compete against each other. Instead, they compete one-to-one against the Dealer.
Players initially place their bets at the start of a round, and then they are dealt two face-up cards.
Players, by drawing new cards may try to score as close to 21 as they can, without surpassing it. If they do, they lose the bet. If they don’t, their final score is checked against the Dealer’s.

Each card is worth the following: 
- Face cards: 10.
- Aces: 1 or 11 at the Player’s  election.
- Other cards: pip value.

The Dealer’s play is automatic, when it reaches 17 or more, it must stand.
Players win if they beat the Dealer’s score, and lose if they don’t. Ties are possible.
The most valuable hand is Blackjack: an Ace/Face pair. It beats anything except another Blackjack.


## Workflow
The workflow I used is displayed in the presentation, but an overview can be find as the following:

1. Define deck and deck population
2. Introduce players: number, names and money of each (list and dictionary)
3. A new round: Players place their bets.
4. Dealer places 2 cards face up to each player. The dealer receives one faceup and one face down.
5. Check for Blackjacks. If Dealer has Blackjack the round is over and jumps to the final score.
6. Players’ turn. Hit or stand for each.
7. Dealer reveals his second hand and has the turn.
8. Final score and payments
9. Round End. Players with no money are eliminated. Players are asked for a new round. If they want, a new round starts.
10. If players choose to leave, the final wallet of each is displayed, including eliminated players (0€).

## Organization
I used the standard Trello table to organize myself. 
First I created a pseudo-code which finally resulted in the workflow I presented before.
Second, the code was written, using functions for the different steps detected in the workflow.
Finally, game testing was made and the presentation slides were prepared, as well as the Readme File.

Functions are my code standard blocks. For almost each step of the workflow there is at least a function describing what to do.
There is the main code which all all the main functions in an ordered manner.

## Links

[Repository](https://github.com/lorentepol/Project-Week-1-Build-Your-Own-Game/)  
[Slides](https://drive.google.com/file/d/1VjmsyLo6ml1gBoksZpvDp2TwE8OdaTYd/view?usp=sharing)  
[Trello](https://trello.com/b/wwtTpfGz/project-1-blackjack)

[Additional: Game Rules and Strategy for Blackjack](https://bicyclecards.com/how-to-play/blackjack/)  
