# MS Paint Clone App

This project is an MS Paint clone built using Python and the `tkinter` library. The app provides basic drawing functionalities, including line drawing, pencil drawing, arcs, rectangles, ovals, and text.

## Features

- **Line Drawing**: Draw straight lines by selecting the line tool.
- **Pencil Drawing**: Draw freeform lines with the pencil tool.
- **Arc Drawing**: Draw arcs with specified start and extent angles.
- **Rectangle Drawing**: Draw rectangles with specified coordinates.
- **Oval Drawing**: Draw ovals with specified coordinates.
- **Text Drawing**: Add text to the canvas with a specified font.

## Unique Features

- **Interactive Drawing**: Real-time drawing on canvas with mouse motion and clicks.
- **Multiple Drawing Tools**: Easily switch between different drawing tools using the menu.
- **Customizable Text**: Add styled text with custom fonts to your drawings.

## How to Run

1. Ensure you have Python installed on your system.
2. Save the script as `paint_app.py`.
3. Open a terminal or command prompt.
4. Navigate to the directory where `paint_app.py` is saved.
5. Run the script using the command:
   ```sh
   python paint_app.py

## Usage Instructions
Start Drawing: Click and hold the left mouse button to start drawing.
Change Tools: Use the "Options" menu to switch between different drawing tools.
Line: Draw straight lines.
Pencil: Draw freeform lines.
Arc: Draw arcs with specified start and extent angles.
Rectangle: Draw rectangles with specified coordinates.
Oval: Draw ovals with specified coordinates.
Text: Add text to the canvas.
Quit: Use the "Quit" option in the menu to exit the application.

## Code Overview
The application consists of the following main components:

PaintApp Class: Handles the main drawing logic and GUI setup.
Methods:
- quit_app(): Closes the application.
- set_line_drawing_tool(): Sets the drawing tool to line.
- set_pencil_drawing_tool(): Sets the drawing tool to pencil.
- set_arc_drawing_tool(): Sets the drawing tool to arc.
- set_rectangle_drawing_tool(): Sets the drawing tool to rectangle.
- set_oval_drawing_tool(): Sets the drawing tool to oval.
- set_text_drawing_tool(): Sets the drawing tool to text.
- left_button_down(): Handles left mouse button press events.
- left_button_up(): Handles left mouse button release events.
- motion(): Handles mouse motion events.
- pencil_draw(): Draws freeform lines.
- line_draw(): Draws straight lines.
- arc_draw(): Draws arcs.
- oval_draw(): Draws ovals.
- rect_draw(): Draws rectangles.
- text_draw(): Adds text to the canvas.

## Screenshots
<img align="center" alt="coding" width="650" src="https://github.com/nrkkR/Python_Enhanced-Tic-Tac-Toe/blob/main/py_ttt%20welcome%20screen.png">

## Credits
- Author: Rajdeep Mondal
- GitHub: nrkkR
- LinkedIn: Rajdeep Mondal

Creating this MS Paint clone was a nostalgic trip down memory lane. It was fun to build and even more fun to use. Happy drawing!
