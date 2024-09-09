# Navigation

Navigation is a dynamic web-based project that generates and animates shapes based on various configurations and roundness levels. The project utilizes HTML, CSS, and JavaScript to create an interactive visual experience where shapes change positions, sizes, and border-radius configurations every few seconds.

## Features

- Dynamic generation of multiple shapes.
- Configurations change based on predefined combinations.
- Smooth transitions for shape positions, sizes, and roundness.
- Visual effects using CSS animations and JavaScript for randomness.
- Fully responsive and works on all screen sizes.

## Project Structure

- `index.html`: The main HTML file that serves the webpage structure and loads the required CSS and JavaScript files.
- `styles.css`: The stylesheet responsible for positioning, coloring, and animating the shapes on the page.
- `index.js`: The JavaScript file that defines the logic for randomizing and updating the configurations and roundness of the shapes.

## Installation

To use this project, follow the steps below:

1. Clone the repository:
    ```bash
    git clone https://github.com/maydaythecoder/navigation.git
    ```

2. Navigate to the project folder:
    ```bash
    cd navigation
    ```

3. Open `index.html` in your browser:
    ```bash
    open index.html
    ```

## How It Works

- The project generates a grid of shapes that change positions, sizes, and roundness every 3 seconds.
- CSS `transition` properties are used to animate the shape changes smoothly.
- JavaScript is used to randomly pick a configuration and apply it to the `wrapper` container, which controls the positioning and appearance of the shapes.
- Shapes are created using `div` elements styled in CSS with background colors and varying z-index levels to create a layered visual effect.

### Configurations

The project uses a series of predefined configurations and roundness settings that alter the layout and appearance of the shapes. These settings are randomized periodically to create a visually engaging animation.

## Demo

A live demo of this project can be viewed by opening the `index.html` file in your browser after cloning the repository.

## Contributions

Feel free to fork the project, submit pull requests, or report issues if you find any bugs or have suggestions for improvements.

