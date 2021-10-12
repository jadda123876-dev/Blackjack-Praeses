# Blackjack

Per the rules of Blackjack, specifically Casino blackjack, I feel the need to mention a few things.
  - When playing, you can hit, stand, double down, or quit. 
  - Upon busting (getting higher than the permitted amount in Blackjack, a 21) you lose the round.
  - If you get a Blackjack, you will receive your bet X 1.5.
  - If you get a number that is lower than 21, you can hit or stand. When you hit, you receive another random card.
  - If you stand, the program will continue to draw cards until it either busts, or gets more card value than you, at which case the dealer wins.
  - If you get two Aces off the starting hand, you will receive a "hard" ace and a "soft" ace, meaning that you would have two cards with a total value of 12. One Ace is 11, the other is 1.
  - If you have a "soft" ace, meaning an 11, and you hit, your ace will revert to being a "hard" ace if the card value goes over 21.
# Specifications and Requirements
  - I was permitted to use any language, in which case, I used C# to develop it, seeing as that is the language that I am most comfortable with. It also lends itself nicely to managing the various different portions of this program efficiently.
  - I understand I will be graded on design and overall structure and usability, as well as a small point bump for any additional features added.
  - Had I had extra time, this would have been a Windows form instead of a console program, but as luck would have it, I ran into the busiest week in a while.
  - I did get the chance to add in a couple extra things to make the overall experience slightly more entertaining, in the form of colors and beeps to signify different game states.
# Hurdles and difficulties
  - I encountered an issue with getting the random number generator to actually be "random" and found that by resetting the random number generator regularly between hands, I could effectively "shuffle" the deck.
  - I found some issue in setting up each class, but eventually used Program.cs as the hub, with each other supporting file responsible for a portion of the project.
  - Casino.cs is the bane of my existence, and had I had extra time, I would have searched for an alternate way to write it.

# Building and executing this project
  - In order to build and execute this project, you will need:
      - C# code access
      - VisualStudio IDE
  - Once you open VisualStudio, open the project in your local folder, and click run. Alternatively, there is an executable file you can use.
  - The project has the necessary contained prompts to direct the user once the project is running.
