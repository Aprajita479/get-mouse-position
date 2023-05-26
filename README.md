# Get Mouse Position

This project provides a simple HTML page that displays the current position of the mouse cursor. The coordinates are dynamically updated as the user moves the mouse.

## Usage

To use this project, follow these steps:

1. Clone the repository or download the source code files.
2. Open the `index.html` file in a web browser.
3. Move the mouse cursor within the browser window.
4. The coordinates of the mouse cursor will be displayed in the output area.

## Files

The project consists of the following files:

- `index.html`: This file contains the HTML structure and layout of the page. It includes references to external stylesheets and JavaScript files.
- `script.js`: This JavaScript file handles the mouse movement event and updates the output area with the current coordinates.
- `style.css`: This CSS file defines the styles and layout for the HTML elements on the page.

## How It Works
The script.js file adds an event listener to the window object for the mousemove event. Whenever the mouse is moved within the browser window, the event listener is triggered, and the e parameter (event object) contains information about the mouse position.

The clientX property of the event object represents the X coordinate of the mouse cursor, and the clientY property represents the Y coordinate. These coordinates are then dynamically displayed on the webpage by updating the content of the output element.

## Dependencies

The project relies on the following dependencies:

- [Google Fonts](https://fonts.googleapis.com/css2?family=Poppins:wght@500&display=swap): This project uses the Poppins font from Google Fonts to style the text.

## License

This project is licensed under the [MIT License](LICENSE).Feel free to modify and use the code according to your needs. Contributions are also welcome.

## Acknowledgments

This project was inspired by the need to demonstrate how to retrieve and display the mouse position in a web page. Special thanks to the developers who have contributed to the libraries and resources used in this project.
