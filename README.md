# BAD-Conventions
Bayesian Action Decoder (BAD) Hanabi Conventions

* Welcome! The goals of this guide is:
1. To understand and document what conventions the BAD AI's are using to play Hanabi
2. Expand it out to 3p+ modes
3. Build on the BAD Conventions found

The AI always discards the "freshest" slot, unless told otherwise, which we will call slot 1. 
When choosing to play a card the order is slot 1 (freshest slot) then oldest to newest.

The AI is giving separate actions/meanings to both Color and Rank Clues

Things you can tell your partner about their freshest card:
1. It is now playable
2. It is trash
3. It is a card that should be saved

Color clues:
Red & Yellow: 
* Slot 1 is immediately playable

Blue & White: 
* Slot 1 is Trash

Green: 
* Slot 1 should be saved

Rank clues that touch slot 1:

Rank 1
* Play all cards touched by 1, unless told otherwise

Rank 2
* Follows normal play clues and isn't a save. 

Rank 3, 4, 5
* Should be treated as a save 
