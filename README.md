# Wolf app
Wolf is a golf game played with 4 people where the teams rotate every hole.  Scoring is intricate, so I'm going to make a phone app to do the work for me.  

# Game description
Wolf can be played over 9 or 18 holes.  For starters, I'm going to focus on the 9 hole version.

On each hole, one player is the "wolf".  The wolf rotates on every hole, except for the last hole, where the person losing becomes the wolf.  This order is set randomly before play begins.

Tee-off order is via honors golf.  Right after the wolf tees off, they choose who will be their partner.  Those two play "better ball" (not to be confused with scramble); lowest individual score wins the hole.  The winning team each get one point; the losing team lose one point.  

After hitting their tee shot, the wolf can choose to "go it alone".   In this case they are playing against all three other opponents...if they win, they get +3 and their opponents get -1, but if they lose, each person on the other team gets +1 and they get -3.

You can either play with ties not awarding any points (simplest), or having ties carry over...which then makes the next hole worth twice the number of points...carrying over again on another tie to make it 3x points, and so on.  

At the last hole, whoever has the fewest points gets to be the wolf.  If there is a tie, the person who last was the wolf gets to be the wolf.

We typically played $1 a point...if you do the scoring right, the negatives and positives should balance out.

# User Interface
## Startup info
* Need to input 4 golfers names
* "Begin" randomizes rotating wolf selection and chooses first hole tee-off order.

## On each hole
* Indicates any carryover
* Shows tee-off order (based on honors golf)
* Choose wolf partner
* Input scores
* Calculates points for that hole

## Overall display
* shows 9 hole summary with plusses and minuses, and overall standings
* Edit past hole scores?





