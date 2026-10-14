hand strength also to be affected by:
	- our current chip count (high)
	- chip count of all other players at given time (high)
		- create ranking, update after each round
	- round number (weak)



how to decide when to bluff, other bots confident --> we bet less (now), could be better if we implement bluffs and calling opponents bluffs depending on opponents stack compared to max

		like if opponent has 5k and bets most of it --> likely not bluffing
		if opponent has not much and bets most of it --> increase chance of bluff (**2) and adjust accordingly
			decrease effect of opponent confidence on our bet
				and depending on states of other opponents stacks, multiply our confidence by a lot and raise
				counts towards us having a low stack and exponentially increasing confidence, bot gets drunk

		our stack close to 6k, maybe within 1.5k, reduce effectiveness of confidence on bet, play safe bot becomes sensible 