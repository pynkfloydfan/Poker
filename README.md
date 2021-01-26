# Poker Calculator

 Calculate probabilities of winning at any stage of a poker hand against any number of other players.

 The functionality works by running a monte carlo simulation and averaging the results to calculate the probability. It is not yet optimised and can take some time to run.

There are three key classes here:  
 - the **Card** class: creates each playing card  
 - the **Deck** class: stores the order of the deck of cards and has methods for drawing and shuffling the cards  
 - the **Player** class that stores the poker player's cards and provides methods
 for calculating  their best hand and win probabilities

*This still needs to be refactored*