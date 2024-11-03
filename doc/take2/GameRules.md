# Rounds of Play

Play is organized into 1 to several rounds. Each round has a time limit of a few minutes or a manual stop.

# Scoring

Leaderboard shows two rankings:

1. Current
2. Round

A player has 4 humors. They can have up to four points of each humor, integers, 0-4.

Current score = `sum of current humors - unbalance`

Unbalance = `|blood-blackBile|*2 + |phlegm-yellowBile|*2`

Score ranges from 16 down to -8.

# Statue

When a player walks to the statue and remains there for a few seconds (warning sound when they enter range), they will score their humors:

- Current score (positive or negative) is added to round score
- 1/2 of their humors will be removed at random

... and they cannot score their humors again until they leave and reenter the statue area. (Leaving means have to leave for several seconds... or maybe go to an organ before returning to the statue?).

# Organs

When a player enters an organ area, they are exposed to gaining humors.

Areas:

- Blood / Liver
- Phlegm / Brain
- Black Bile / Spleen
- Yellow Bile / Gallbladder

Entering the liver gains you 1 blood every 5 seconds you remain in the liver.

# Attacks

Inside the liver (for example), you can use 2 attacks:

- Oppose: -2 blood for you, -1 blood for one player in the gallbladder.
- Spin: -4 blood for you, -1 of phlegm, black bile, and yellow bile for each other player on the liver.
