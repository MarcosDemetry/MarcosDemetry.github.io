---
layout: post
title: A Bayesian Match
subtitle: ...Monty Hall Problem and Dominoes
tags: [reflections]
---
## Statistics Teachers Obsession with the Monty Hall Problem
Surely, the elementary course in statistics that you took many years ago had a lecturer that loved explaining the Monty Hall problem. Their eyes would light up as they ask the students “Now, what is the probability of choosing the door that leads to the car if you switch?” Of course, they know that most students will say that the probability is still 50%.

If you are unfamiliar with the Monty Hall problem, not to worry, here it is in short:

_Suppose you're on a game show, and you're given the choice of three doors: Behind one door is a car; behind the others, goats. You pick a door, say No. 1, and the host, who knows what's behind the doors, opens another door, say No. 3, which has a goat. He then says to you, "Do you want to pick door No. 2?" Is it to your advantage to switch your choice?”_ (Wikipedia)[ https://en.wikipedia.org/wiki/Monty_Hall_problem]

The lecturer, now excited beyond belief, reveals that the probability of winning is 66% if you switch! What kind of witchcraft is this, you say?

## The Bayesian (Updating) Solution
Let’s walk through this. The first player in this game is the producers of the show that place a car behind one door and goats behind the remaining two. In game theory lingo, the producers would be called “nature”.

Now, say you pick door #1. To you, the probability that you have chosen the right door is simply 33% (one out of three). This probability would be the same if you chose door #1, #2 or #3. The important thing is that these probabilities together add up to 1. Or, in other words, if all the doors were opened there must be a car behind one of them!
Since you chose door #1, the host can only open #2 or #3. 
Say the host opens door #3 and reveals a goat. As soon as door #3 is opened, we now know for sure that the car is not behind door #3. So the probability of door #3 hiding the car is precisely 0%. So, we know that the probability of the car being behind door #1 is 33% and behind door #3 is 0%. Where’s the remaining probability gone?

Door #2 now has a 66% (i.e. 2/3) probability of having a car behind it! Why? Because by eliminating door #3, the host has done nothing to change the probability of our chosen door having a car behind it, but did tell us “where not to look”.

## A More Intuitive Solution
The solution above sounds like voodoo science, doesn’t it? It’s correct, but it doesn’t feel right in my gut. 

Let’s spice the example up a bit and have 100 doors. Behind one of those doors is a car and behind the other 99 doors are goats. You, the contestant, love the number 19 because it is a special prime number and you pick door #19. As before, the host opens a door and reveals a goat behind it. The host asks if you would like to switch to another door or stay with your chosen door. Say you stay with your chosen door. The host opens another door, and another, and another. The host opens 98 doors. The only doors left are your door (#19) and another door, say #76. Now the host asks if you would like to stick with your chosen door #19 or switch to #76. I WANT TO SWITCH IMMEDIATELY! This host, who knows which door has the car behind it and therefore doesn’t open it has left one door unopened. I, without any knowledge at all, had chosen #19 at random in the beginning of the game. Screw #19. Let’s go #76!

In terms of probabilities, initially, every door had a 1/100 probability (to the contestant) of having a car behind it. Your door, #19, still has a 1/100 probability of making you a winner. However, once the host has opened 98 doors and gotten them “out of the game”, the other last remaining door hides behind it the car with 99% probability.

Now it makes sense to switch.

Of course, the door may still be behind #19 and it would have been an extremely lucky guess on my part. I would rather follow the odds than trust my luck.

## Dominoes: A not so exact analogy
My dad and I have played well over 250 games of dominoes. Each player picks up 7 tiles at random, and the person with the highest double (e.g., 6:6 or 5:5) begins the game by placing it on the board. We play a variation of the All Fives, which means that a player gets points based on the sum of the ends being a multiple of five. For example, if the ends are 6, 4, 3, 2, then their sum is 15 and the player gets 15/5 = 3 points. If a player has no tiles to play, they must pick up tiles from the reserve pile (up to two tiles). If they still don't have anything to play, then it is the other player's turn.

During one of our games, I noticed that much like the Monty Hall problem, if I pick up a tile and still then I am learning information about _my dads tiles_.

Here's an example. A good tile to have in this game is the 5:5, because if the board has, say, 6:6, 4:4, 5:0, 0:0, yielding 5 points, then the player with the 5:5 would get 6 points if they place it on the 5:0. In this situation, if I did not have 6's, 4's, 5's or 0's, I'd have to pick up a tile from the reserve pile. With each tile that I pick up, I get more information about my opponent's tiles _without their cards changing_. Why? Simply because if a tile is not on the board, not in my hands, and not in the reserve pile, it must be with my opponent. I have complete information about the tiles on the board (which are visible to all) and the tiles in my hand. Thus, the only remaining uncertainty lies with the reserve pile and my opponent's hand—which must be mutually exclusive. Any new information about the reserve pile lets me know which cards they don't have!

## And This Relates How?
The Dominoes example is that by revealing tiles from the reserve pile, I gain information about my opponent's tiles without seeing or altering my opponent's tiles!

In this case, my opponent's tiles are like the door that I, the contestant, choose at the beginning of the game. All other tiles that are revealed to me throughout the game are like the Monty Hall host opening doors.

## Stop Talking About Tiles Already
The statistics teacher wasn't wrong to be excited about presenting the Monty Hall problem. Anyone exposed to this problem isn't wrong for being confused, or being critical of the proposed solution. The beauty of it is that this problem that can be described in four sentences has a solution that conveys a message about Bayesian updating and subjective probabilities. The probabilities I assign to things (whether it's cars behind a specific door, or tiles in my opponent's hand) is based on the information available to me—hence the name _subjective_ probabilities. The more information I have (whether it's the host revealing a goat behind a door, or me picking up a tile from the reserve pile), the better informed I am about the thing which I do not know with certainty (whether it's the probability of my chosen door hiding a car behind it, or my opponent's tiles)!

With the risk of seeming like a 15 year-old teenager writing a blog post about their first kiss; _isn't that amazing?_

