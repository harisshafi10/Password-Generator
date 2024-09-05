# Password Generator

A simple and intuitive web-based Password Generator created using HTML, CSS, and JavaScript. This application allows users to generate random, secure passwords based on selected criteria such as length, inclusion of uppercase and lowercase letters, numbers, and symbols.

## Features

- **Customizable Password Length:** Users can adjust the password length using a slider (from 1 to 20 characters).
- **Character Options:** Users can choose to include uppercase letters, lowercase letters, numbers, and symbols.
- **Password Strength Indicator:** Visual feedback on the strength of the generated password.
- **Copy to Clipboard:** Users can easily copy the generated password to their clipboard.

## Project Structure

The project is divided into three main files:

1. **index.html**: The HTML structure of the application, which includes input fields, sliders, and buttons for generating and copying passwords.
2. **style.css**: The CSS file contains styles for the layout, typography, and visual effects (like tooltips and password strength indicators).
3. **script.js**: The JavaScript file handles password generation logic, including randomization of characters, managing user input, and password strength calculation.

## Getting Started

To run the Password Generator locally:

1. Clone or download the repository to your local machine.
2. Open the `index.html` file in your browser.

## How to Use

1. **Set the Password Length:** Use the slider to select the desired length of the password.
2. **Select Character Types:** Check the boxes for:
   - Uppercase letters
   - Lowercase letters
   - Numbers
   - Symbols
3. **Generate Password:** Click the "Generate Password" button.
4. **Copy the Password:** Click the copy button to copy the password to your clipboard.

## Password Strength

The application evaluates the password strength based on:
- The presence of uppercase and lowercase letters
- The inclusion of numbers and symbols
- The total length of the password

Strength is indicated by color:
- **Green:** Strong password
- **Yellow:** Moderate password
- **Red:** Weak password

## Technologies Used

- **HTML5:** For structuring the content.
- **CSS3:** For styling and layout.
- **JavaScript:** For interactive functionality, password generation, and validation.

## License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).
