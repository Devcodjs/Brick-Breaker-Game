**🧱 Brick Breaker Game (C++ Console Edition)**
A simple and fun Brick Breaker game built entirely using C++ and Windows Console API.
This project demonstrates console-based animation, keyboard input handling, and game logic implementation using basic C++.

**🎮 Game Overview**
In this game, you control a paddle (slider) at the bottom of the screen to bounce a ball upwards and break all the bricks arranged at the top.
objective:
Break all the bricks without letting the ball touch the bottom boundary.
The game ends when you either break all the bricks (WIN) or miss the ball (LOSE).

**🧩 Features**
🧱 24 visible bricks arranged in 3 rows
🎚️ Multiple difficulty levels:
Easy – Large paddle, slow ball
Medium – Normal paddle, regular speed
Hard – Small paddle, fast ball
🎨 Colored graphics using console text colors
⚡ Real-time movement and keyboard controls
🧠 Simple but effective game logic using loops, conditionals, and enums
🏆 Score tracking system

**🎮 Controls**
   Key                    	Action
A / Left Arrow	       Move paddle left
D / Right Arrow	       Move paddle right
Space	                 Launch the ball
Esc                    Pause / Exit the game


**📈 Scoring System**
Breaking a brick = +10 points
Total bricks = 24
Maximum possible score = 240 points


**🧠 Game Logic Summary**
Bricks are drawn in fixed positions and stored in an array.
Paddle position is updated using keyboard input (A / D).
Ball movement is based on a direction system:

Direction codes:
1 = up-right, 2 = up-left, 3 = down-left, 4 = down-right

The ball bounces off:
Screen borders
Paddle (reverses direction)
Bricks (removes brick + adds score)

The game loop continues until:
All bricks are destroyed (You Win)
Ball crosses bottom line (You Lose)


**💡 Difficulty Settings**
Difficulty	   Paddle Length        	Ball Speed	      Movement Step
Easy	             13	                  50 ms	                 5
Medium	           9                    30 ms                  7
Hard	             5	                  15 ms                  9





