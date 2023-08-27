# Day_10_Class_Assingment

The code starts by defining an array called Color that holds various color names.

There's a variable called index that keeps track of which color is currently being used from the Color array.

The code gets references to specific HTML elements using getElementById, querySelector, and querySelectorAll. These elements include a circle, a shape, and buttons with IDs "color" and "changeShape".

An event listener is attached to the "Change Color" button (Changecolor). When the button is clicked, the background color of the circle (circle) element is changed to the color at the current index in the Color array. The index is then incremented to move to the next color for the next click. If the end of the array is reached, the index is reset to start from the first color.

The code uses a variable called Tringle to keep track of whether the shape is a triangle. When the "Change Shape" button (changeShape) is clicked, the code checks if Tringle is false. If it is, it changes the class of the shape element to "triangle", effectively changing the shape. If Tringle is already true, the shape class is changed back to "shape", restoring the original circular shape.
