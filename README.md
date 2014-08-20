hive-pong
=========

A group pong game. 


Trying to come up with a cool project that would help me learn node.js, I spent some time thinking about the base nature of node.js. At it's heart it is a constantly updating page. User's or programs can constantly update the shape and status of the page. In my mind that means games can be played on something like this. One could play a game of poker, or shoot dice, with people placing bets. In fact, I like the idea of shooting dice. That might be an easier project to start with. But let's explore this other idea I have. 

In 1991, Loren Carpenter gathered 5000 developers into an auditorium. Each member had a paddle, red on one side, green on the other. After an orientation that let players grok that a camera was recording the paddles, Carpenter displayed a game of pong. Kevin Kelly explains it well...

"Loren Carpenter boots up the ancient video game of Pong onto the immense screen. Pong was the first commercial video game to reach pop consciousness. It's a minimalist arrangement: a white dot bounces inside a square; two movable rectangles on each side act as virtual paddles. In short, electronic ping-pong. In this version, displaying the red side of your wand moves the paddle up. Green moves it down. More precisely, the Pong paddle moves as the average number of red wands in the auditorium increases or decreases. Your wand is just one vote.

Carpenter doesn't need to explain very much. Every attendee at this 1991 conference of computer graphic experts was probably once hooked on Pong. His amplified voice booms in the hall, "Okay guys. Folks on the left side of the auditorium control the left paddle. Folks on the right side control the right paddle. If you think you are on the left, then you really are. Okay? Go!""  

---Kevin Kelly, 'Out of Control'

So my thought was what if I built a pong app using node.js where dozens of people could log on and participate as the mob did. That would be fun. I could also add video so people could see their team members. So let's break this down. 

Build a pong game. 
Hook it up to node.js
Allow multiple players to vote on the direction of the paddle. 
Add video of players to increase hive-mind aspect. 

So video in this context summons visions of all the penises I saw in my chat roulette days. So maybe I could add a kick function while I'm at it.  

Let's start with 

BUILD A PONG GAME
Let's start the pong game by building an html pong table. 
