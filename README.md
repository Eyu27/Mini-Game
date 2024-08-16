# Mini-Game

Maze Game
This is a browser-based maze game where the player controls a small object ("thingie") and navigates it through a randomly generated maze to reach the goal ("home"). The game supports multiple input methods such as keyboard, touch controls, device tilt, and even gamepad for a more interactive experience.

Features
Random Maze Generation: Each time you play, a new maze is generated using a recursive backtracking algorithm.
Multiple Control Options:
Keyboard Controls: Use arrow keys or WASD to move.
Touch Controls: On-screen buttons for up, down, left, and right.
Device Tilt Controls: Control the "thingie" by tilting your mobile device.
Gamepad Support: Connect your game controller and use it to navigate the maze.
Emoji Feedback: A dynamic emoji updates based on your performance, reacting with happiness, frustration, or other expressions as you play.
Responsive Design: The game adapts to various screen sizes, making it enjoyable on desktops, tablets, and mobile devices.
How to Play
Start the Game: Open the game in your browser.
Control the Thingie:
Use the arrow keys or WASD to move up, down, left, or right.
On touch devices, tap the on-screen directional buttons.
If supported, you can tilt your device to move the thingie.
You can also use a connected gamepad to control movement.
Navigate the Maze: Your goal is to move the "thingie" through the maze and reach the "home" area while avoiding barriers.
Reach the Goal: Once you reach the "home" area, you win! The maze will reset, and a new challenge begins.
Technical Details
Language: JavaScript (vanilla)
Maze Algorithm: Recursive backtracking
User Interface: HTML5 and CSS3
Input Handling: Supports keyboard events, touch events, device orientation (tilt), and gamepad API.
Installation and Running
Clone the Repository:
bash
Copy code
git clone https://github.com/yourusername/maze-game.git
Open the Project:
Open the index.html file in your preferred browser.
No additional setup is required—just launch the game and start playing!

Customization
You can easily modify the game by adjusting some of the constants in the script:

step: The distance the "thingie" moves with each step.
size: The size of each grid cell in the maze.
mazeHeight and mazeWidth: The dimensions of the maze.
You can also change the appearance of the "thingie," barriers, and the goal by editing the CSS styles.

Future Improvements
Adding different difficulty levels.
Implementing a timer and scoring system.
Adding sound effects for movement and when reaching the goal.
License
This project is licensed under the MIT License.
