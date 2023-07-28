# Turtle Control with Keyboard 🎮

This Python script allows you to control a turtle using keyboard keys.

## How to Use 📝

1. Install Python and ensure the Turtle module is available (usually comes pre-installed with Python).
2. Copy and paste the code into your Python environment.
3. Run the script.

## Control Keys 🕹️

- **W**: Move the turtle forward.
- **S**: Move the turtle backward.
- **A**: Turn the turtle to the left.
- **D**: Turn the turtle to the right.
- **C**: Clear the drawing and reset the turtle's position.

## How It Works 🐢

- The turtle is represented by an arrow shape on the screen.
- Press the corresponding keys (W, S, A, D, C) to control the turtle's movement and drawing.
- **W** and **S** move the turtle forward and backward by 10 units, respectively.
- **A** and **D** turn the turtle to the left and right by 10 degrees, respectively.
- **C** clears the drawing and resets the turtle's position to the center.

## Explanation of the Code 📄

The code uses the Python Turtle module to create a turtle object named `tim`. It also creates a screen object named `screen` for capturing keyboard inputs.

The functions `move_forward()`, `move_backward()`, `turn_right()`, `turn_left()`, and `clear()` are defined to handle the corresponding keyboard inputs.

The `listen()` method is called on the screen to enable keyboard listening. The `onkey()` method is used to assign the functions to specific keys (W, S, A, D, C).

The turtle responds to the keyboard inputs by moving and drawing on the screen based on the pressed keys.

## How to Exit 🚪

The script listens to keyboard inputs and responds to the specified keys. To exit the program, click anywhere on the Turtle graphics window.

## Have Fun! 🚀

Enjoy controlling the turtle and creating various patterns and shapes with Python's Turtle module!
