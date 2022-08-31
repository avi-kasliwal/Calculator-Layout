# Calculator Layout Boss Challenge

This is my attempt to the iOS dev course from app bewery on **Layouts**.
Use the concepts of Auto Layout, Stack Views, Constraints, Alignment to create the following UI.

## Portrait

![Portrait](Documentation/Portrait.png)

## Landscape

![Landscape](Documentation/Landscape.png)

## My Approach

1. Created `Vertical Stack` and used distribution = "fill equally", and constrained it to safe area view - all 4 corners.
2. Created `Horizontal Stack` for each row and constraint them to trailing and leading of the super view.
3. For last row - inserted **0** into a `Horizontal Stack` and **.**, **=** in another `Horizontal Stack` and then distributed them as "fill equally" to make **0** twice as big as the other ones.
4. Edited the constraint for Result from - trailing 20 points.

This is my attempt for Layout's Assignment from the course - App Brewery's Complete App Development Bootcamp

## Result

### Potrait

![PotraitResult](./Result%20Image/Potrait.png)

### Landscape

![LandScapeResult](./Result%20Image/Landscape.png)
