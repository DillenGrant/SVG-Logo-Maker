# SVG-Logo-Maker


## Description

This is a Node.js application that generates SVG logos based on user input. Users can customize the text, text color, shape, and shape background color of the logo.

## Dependencies

This application relies on the following Node.js packages:

- [Inquirer](https://www.npmjs.com/package/inquirer): Used for prompting users for input.
- [File System Module](https://nodejs.org/api/fs.html): Used for creating and writing SVG files.

## Installation

Before running the application, make sure you have Node.js installed on your machine. You can install the required packages using npm:

npm install

## Usage

To generate a custom SVG logo, run the following command in your terminal:

node app.js

The application will prompt you to provide the following information:

1. **Text**: Enter up to three characters for the logo text.
2. **Text Color**: Choose a text color using color keywords or hexadecimal values.
3. **Shape**: Select the shape for your logo (Triangle, Square, or Circle).
4. **Shape Background Color**: Choose a color for the shape background using color keywords or hexadecimal values.

Once you've provided the input, the application will create an SVG file named "logo.svg" in the current directory with your custom logo.

## Shape Classes

The code includes three shape classes that define the properties and rendering of different shapes:

- `Triangle`: Renders a triangle shape.
- `Square`: Renders a square shape.
- `Circle`: Renders a circle shape.

You can further customize these shapes by changing their colors or other properties.

## Unit Testing

The code includes unit tests for each shape class to ensure they render correctly. You can run these tests using the following command:

npm test

## License

This code is provided under the [MIT License](LICENSE).

Feel free to use and modify this code to generate custom logos for your projects. If you have any questions or encounter any issues, please feel free to reach out.

Happy logo generation!