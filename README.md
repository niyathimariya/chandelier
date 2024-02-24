# chandelier
Code defines a simple physics simulation of a hanging rope made up of interconnected dots. Each dot represents a particle in the simulation. The simulation includes the effects of gravity, friction, and interaction with the mouse cursor.
 overview of the main components:

Vector Class: Represents a 2D vector and provides various vector operations such as addition, subtraction, multiplication, distance calculation, etc.

Mouse Class: Handles mouse/touch input events and tracks the cursor position.

Dot Class: Represents a particle in the simulation. It has properties like position, velocity, friction, gravity, mass, and whether it is pinned. It also has methods for updating its position based on physics calculations and drawing on the canvas.

Stick Class: Represents a connection (stick) between two dots. It has properties like the start and end points, length, and tension. It also has a method for updating the position of connected dots based on tension.

Rope Class: Represents a series of connected dots (particles) forming a hanging rope. It has properties like the number of segments, gap between segments, and color. It also has methods for updating and drawing the rope.

App Class: Manages the overall application, including handling canvas resizing, creating multiple ropes, and rendering the simulation. It also initializes a `Mouse` instance and updates/draws the ropes in the animation loop.

randomNumBetween Function: A utility function that generates a random number between a given range.

The code uses the HTML5 Canvas API for drawing and simulation. The `requestAnimationFrame` function is employed for smooth animation rendering. The simulation includes interactive behavior with the mouse, allowing the user to move and interact with the hanging ropes.






