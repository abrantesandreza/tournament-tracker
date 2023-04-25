## Tournament Tracker Application

A Tournament Tracker that sets up a schedule for teams to play each other in a single-elimination style matchups.

## Useful for: 

- Office ping pong tournaments
- Rec league playoffs
- 3v3 basketball leagues
- And many more

## The Scenario

My friends came to me and asked me to create a tournament tracker. They are always playing games and want to determine who is the best. The idea is that I create a bracket tournament system where the computer will tell them who to play in a single-elimination style bracket. At the end, the winner should be identified. Their model is the NCAA Basketball Tournament bracket for March Madness, like this one:


![March Madness Printable Men's Bracket_1](https://user-images.githubusercontent.com/87620471/231030700-fb19444b-7dd4-4c55-a6c9-9a0b29ebc49a.jpg)

## Requirements

1. Tracks games played and their outcome (who won);
2. Multiple competitors play in the tournament;
3. Creates a tournament plan (who plays in what order);
4. Schedules games;
5. A single loss eliminates a player;
6. The last player standing is the winner.

## Questions 

1. How many players will the tournament handle? Is it variable?
  - The application should be able to handle a variable number of players in a tournament.
2. If a tournament has less than the full complement of players, how do we handle it?
  - A tournament with less than the perfect number (a multiple of 2, so 4, 8, 16, 32, etc.) should add in “byes”. Basically, certain people selected at random get to       skip the first round and act as if they won.
3. Should the ordering of who plays each other be random or ordered by input order?
  - The ordering of the tournament should be random.
4. Should we schedule the game or are they just played whenever? 
  - The games should be played in whatever order and whenever the players want to play them.




