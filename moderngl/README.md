# UI Events with Polygons

This program is meant to practice UI events with the mouse in ModernGL. The idea is to draw a 5-sides polygon and then, provide the ability to move, change number of sides and change the color with mouse events.

The following programs would be useful for your work:
- [`moderngl_window_empty.py`](https://github.com/moderngl/moderngl/blob/main/examples/moderngl_window_empty.py) - for the mouse's support
- [`02_shader.py`](https://github.com/moderngl/moderngl/blob/main/examples/02_shader.py) - for polygon's drawing

## General Instructions
- Implement all your code in the [`uiEvents.py`](./uiEvents.py) file
- The program should support the following mouse events:
  - `left-click` - to move the polygon, it's expected to re-draw the polygon without leaving previous drawn polygons.
  - `Scroll-up` - increases the number of sides (20 is the maximum)
  - `Scroll-down` - decreases the number of sides (5 is the minimum)
  - `right-click` will change to a new random color
- By default, the first 5-sides polygon will be drawn at the center of the window


## Test cases and grading policy

You program will be started as follows:

```
python uiEvents.py
```

then, your program will be graded with the following requirements

- 25% - First polygon drawing
- 25% - Polygon's movement
- 25% - Polygon's sides increase/decrease
- 25% - Polygon's color change