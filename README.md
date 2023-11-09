# Adding 10 Elements to a List and Clearing It

This project demonstrates the ability to add 10 list elements with increasing font sizes by clicking a button, and it allows you to clear the list with another button. It showcases basic HTML and JavaScript concepts like DOM manipulation, event handling, and button functionality.

## Installation

1. Download the project files to your local machine.

   git clone https://github.com/19Archmiel88/Adding-10-Elements-to-a-List-and-Clearing-It.git
   
2. Open the `index.html` file in your preferred web browser.

## How to Use

1. Click the "Adding 10 Elements" button to add 10 list elements to the page.

   - Each element is labeled as "Element nr X," with X incrementing with each addition.
   - The font size of each element increases as well.

2. Click the "Clear" button to remove all the list elements and reset the font size and order.

## Code Overview

The JavaScript code in `main.js` offers three main functions:

### Initialization (`init`)

- Initializes two buttons: "Adding 10 Elements" and "Clear."
- Creates an unordered list (`ul`) for displaying the list elements.
- Adds event listeners to the buttons: one for adding elements and one for clearing the list.

### Creating List Elements (`createLiElements`)

- Generates 10 list elements and appends them to the unordered list.
- Each element is labeled with a unique order number, and its font size increases incrementally.

### Clearing the List (`cleanList`)

- Removes all list elements from the unordered list.
- Resets the font size and order number back to their initial values.

This project serves as an example of how to add and clear elements in a list using JavaScript.

## Changelog

- Version 1.0: Initial release

## Contributions

Feel free to contribute to this project by suggesting improvements or adding new features. Pull requests are welcome!
