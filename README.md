Android - Phonegap - Javascript app for practicing with Venn diagrams.

Supports shading (3 colors) and sizes.

The color buttons select the shading color; the current color is indicated in the upper right.

Click edge of a circle to select entire circle.

Click point of intersection of two circle to select either the union (in Union mode) or the intersection (in intersection mode).  The mode is toggled with the bottommost button. 

Toggle between shading and sizes with second-to-last button.

If a pink and blue region are selected, the Union button makes the union of the two blue, while the intersection button makes the intersection blue and clears the rest of the shading.

The Tao button shades the complement of the current blue region and clears the rest.

Push and Pop manage a memory stack.  Push places the current blue region in the stack, Pop takes the current region from the top of the stack and colors it pink.

Size From Sum: If the size of the blue region can be determined by adding up known sizes within it, click this button.

Size From Diff: If the size of the purple region can be determined by the difference in sizes between the blue region and the combined blue and purple region, click this button.

Switch: toggle 2 or 3 circle modes

