# Readme for SVG Bouncing Balls Animation


![explosion_gif](https://user-images.githubusercontent.com/59121834/225051905-65131869-80d0-4351-b431-4835c515fae7.gif)

This is a simple JavaScript program that creates an animation of bouncing balls inside an SVG element. When the user clicks the screen, the animation starts or stops.

## How to Run the Program

To run the program, you can copy the code and paste it into a text editor, then save the file with an .html extension. Then, you can open the file in a web browser by double-clicking on it.

Alternatively, you can copy the code and paste it into an online code editor like CodePen or JSFiddle and run it from there.

## How the Program Works

The program uses SVG to draw a circle for each ball, and animates the balls using simple physics equations. The program defines some global parameters, including the number of balls, the friction coefficient, the density, and the maximum radius of the balls, among others.

The program initializes the positions, velocities, radii, friction coefficients, and masses of each ball randomly. Then, it creates SVG circles for each ball and sets their attributes, including the position, velocity, and radius.

When the user clicks the screen, the program starts or stops the animation by calling the stop_and_go function. This function sets a boolean variable run to true or false and calls the update function.

The update function updates the positions and velocities of the balls based on their current positions, velocities, and properties like friction and gravity. It then updates the attributes of the SVG circles to reflect the new positions and velocities. If the run variable is true, it calls itself after a short delay using the setTimeout function, creating a loop that keeps the animation running until the user clicks the screen again.

## Customizing the Program

You can customize the program by changing the global parameters, including the number of balls, the friction coefficient, the density, and the maximum radius of the balls, among others. You can also change the SVG attributes of the balls, including the fill and stroke colors, and the cursor style. Additionally, you can modify the HTML and CSS to change the appearance and behavior of the program.

