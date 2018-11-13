## Key Concept
- **Strict Dominance**
- **Rational Players**

## Problem Settings
* Two suspects are arrested because they were sneaking around the headquatre of the bank of Japan in Tokyo.
* The police think that they were trying to steal huge money from there. However, the police can only prove that the suspects were bringing the confidential map of the building.
* Thus, the police need one of criminals to confess or betray the other.

## Confliction in Benefit
* If no one confess, the police can only charge the prisoners for stealing the confidential map of the building.
	- Punishment: 1 month in jail each
* If one confesses and the other does not, the police will be merciful on the one confess and severely punish the quiet one
	- Punishment: 12 months in jail for the quiet one; 0 month for the confess one
* If both confess, the police punish both of them equally
	- Punishment: 8 months in jail each

## Question
* Suppose the thieves only want to minimise the extent of punishments on them in jail. Should they confess to the police?

## Note
* They are unavailable to communicate each other! So they need to decide themselves. No cooperation holds.

## Prisoners' Dilemma
Please look at the picture below.

![table1](https://github.com/Rowing0914/GameTheory_Python/blob/master/Prisoners_Dilemma/images/1.PNG)

We have just written down the situation of the suspects. As you can see, there might be some optimal options within the given table.
Let's look at the each option carefully.

### Viewpoit of Player1
- Case 1: Given Player2's Keep Quiet option
![table2](https://github.com/Rowing0914/GameTheory_Python/blob/master/Prisoners_Dilemma/images/2.PNG)
- Case 2: Given Player2's Confess option
![table2](https://github.com/Rowing0914/GameTheory_Python/blob/master/Prisoners_Dilemma/images/3.PNG)
Either way, obviously Player1 should act on the confess unless the person is not completely rational.

### Concept: Strict Dominance
* Strategy x strictly dominates strategy y for a player if x generates a greater payoff than y regardless of what the other players do.
* Rational players never play strictly dominated(not dominates!!) strategies.

## Conclusion of the Game
In prisoners' dilemma, normally two rational players decide on the action depending on their own interests.
Hence, in this case, they both end up with choosing "Confess" as we confirmed looking at the Player1's view.
If you check with Player2, surely you can observe the same outcome.
