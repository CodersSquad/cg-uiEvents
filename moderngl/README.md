# Draw, move, modify and re-color a polygon

This program should be able to draw an initial 5 sides and then modify it with mouse interactions; the user should be able to move, change color and increase or decrease the number of sides.

The following programs would be useful for your work:
- [`moderngl_window_empty.py`](https://github.com/moderngl/moderngl/blob/main/examples/moderngl_window_empty.py) - for the mouse's support
- [`02_shader.py`](https://github.com/moderngl/moderngl/blob/main/examples/02_shader.py) - for polygon's drawing

## General Instructions
- Implement all your code in the [`uiEvents.py`](./uiEvents.py) file
- The program should support the following mouse events:
  - `Pressed left-click and move` - should move the polygon, it's expected to re-draw the polygon without leaving previous drawn polygons.
  - `Scroll-up` - increases the number of sides (20 is the maximum)
  - `Scroll-down` - decreases the number of sides (5 is the minimum)
- By default, the first 5-sides polygon will be drawn at the center of the window


## Test cases
Your program will be graded with the following requirements

- 25% - First polygon drawing
- 25% - Polygon's movement
- 25% - Polygon's sides increase/decrease
- 25% - Polygon's color change