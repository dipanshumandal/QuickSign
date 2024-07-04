# QuickSign

QuickSign is a simple web-based application that allows users to create and save digital signatures. Users can change the pen color, pen thickness, and the background color of the canvas. The signatures can be saved locally and retrieved later for use.

## Table of Contents

- [Usage](#usage)
- [Features](#features)

## Usage

1. **Open the application**: Open it in your web browser.
2. **Set pen color**: Use the color picker under "Pen Ink Colour" to choose your preferred pen color.
3. **Set background color**: Use the color picker under "Background" to set the background color of the canvas.
4. **Set pen thickness**: Select the desired pen thickness from the dropdown menu under "Pen Thickness".
5. **Draw your signature**: Click and drag your mouse on the canvas to draw your signature.
6. **Clear the canvas**: Click the "Clear" button to erase the canvas.
7. **Save your signature**: Click the "Save & download" button to save your signature as a PNG file.
8. **Retrieve a saved signature**: Click the "Retrieve saved signature" button to reload a previously saved signature from local storage.

## Features

- **Pen Color Picker**: Allows users to change the pen color.
- **Background Color Picker**: Allows users to change the background color of the canvas.
- **Pen Thickness Selector**: Users can select different pen thicknesses.
- **Clear Canvas**: Users can clear the canvas with a single click.
- **Save & Download**: Users can save their signature as a PNG file.
- **Retrieve Saved Signature**: Users can reload a previously saved signature from local storage.

## Code Explanation

The HTML and JavaScript code structure is as follows:

### HTML Structure

- The HTML file includes the main structure of the web application:
  - A `toptop` div for displaying the logo or image.
  - A `main` div containing:
    - Color pickers for pen ink and background.
    - A dropdown menu for selecting pen thickness.
    - A canvas for drawing the signature.
    - Buttons for clearing the canvas, saving the signature, and retrieving a saved signature.

### JavaScript Functionality

- **Event Listeners**:
  - Color pickers change the pen ink and background colors.
  - The canvas listens for mouse events to handle drawing.
  - Buttons handle clearing the canvas, saving the signature, and retrieving saved signatures.

- **Drawing Functionality**:
  - The pen color and thickness can be adjusted dynamically.
  - The drawing starts on `mousedown` and stops on `mouseup`.

- **Saving and Retrieving Signatures**:
  - Signatures are saved to and retrieved from local storage.
  - The saved signature is stored as a data URL.


