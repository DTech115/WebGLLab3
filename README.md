# WebGLLab3Part1
## Diti Nesimi
## Sep. 14, 2026
## Learned how rotation works properly thanks to the axes

## 1. Replace lookAt() with translate(). Is there any change in the display? Why or why not?
No, the axis lines remain as the same transformation is produced by both.
## 2. Remove Both Transformations. What happens? Why?
The axis lines disappear completely because now the geometry is on/behind the camera as its set to default position.
## 4. Investigate the Perspective Projection. What happens to the display?
### A. 
The screen is flattened a little bit & appears stretched out instead of symmetric.
### B.
The screen is stretched vertically & loses its symmetry.
## 10. Top View. If you wanted to keep the X-axis and Y-axis in their original orientation while still seeing the tops of the cubes, how would you change your code?
I'd reduce the angle that the rotation is on, only the x, so that the top of the cube is viewable but the axes remain visible.