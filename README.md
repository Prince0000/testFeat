# Fullscreen Calculator with Drawing & Graphing

A modern, responsive fullscreen calculator with drawing and graphing capabilities, built with HTML, CSS, and JavaScript. This calculator features a clean design with a gradient background, smooth animations, and interactive drawing tools.

## Features

- Fullscreen responsive design
- Basic arithmetic operations (+, -, \*, /)
- Support for decimal numbers
- Parentheses for complex calculations
- Clear function (C)
- Backspace function (⌫)
- Error handling for invalid expressions
- Modern color scheme with visual feedback
- Smooth animations and transitions
- Drawing capabilities:
  - Freehand drawing
  - Color picker
  - Save drawings as PNG
  - Clear canvas option
- Graphing capabilities:
  - Plot mathematical functions
  - Grid system with axes
  - Switch between drawing and graphing modes
  - Interactive coordinate system

## Color Scheme

- Background: Gradient from `#2c3e50` to `#3498db`
- Calculator body: `#34495e`
- Display background: `#2c3e50`
- Regular buttons: `#2c3e50`
- Operation buttons: `#e74c3c`
- Clear button: `#e67e22`
- Equals button: `#27ae60`

## Modes

### Calculator Mode

- All previous calculator features

### Drawing Mode

- Freehand drawing with customizable colors
- Save drawings as PNG files
- Clear canvas option
- Smooth drawing experience

### Graphing Mode

- Plot mathematical expressions
- Coordinate grid system
- Support for basic mathematical functions
- Real-time graph updates

## Usage

1. Open `index.html` in a web browser
2. Use the calculator by:
   - Clicking number buttons (0-9) to input numbers
   - Using operation buttons (+, -, \*, /) for calculations
   - Using parentheses for grouping expressions
   - Clicking '=' to see the result
   - Clicking 'C' to clear the display
   - Using '⌫' to delete the last character

### Drawing Features:

1. Click "Drawing Mode" to activate the drawing canvas
2. Use the color picker to select drawing color
3. Draw freely on the canvas with your mouse
4. Click "Clear" to reset the canvas
5. Click "Save" to download your drawing as PNG

### Graphing Features:

1. Click "Graph Mode" to switch to graphing
2. Enter a mathematical expression in the calculator (using 'x' as variable)
3. Press '=' to plot the graph
4. Use the grid system for reference
5. Clear and save options work for graphs as well

## Responsive Design

The calculator is fully responsive and works on:

- Desktop computers
- Tablets
- Mobile phones

## Technical Details

- Built with vanilla HTML, CSS, and JavaScript
- Uses CSS Grid for button layout
- Implements CSS Flexbox for vertical alignment
- Features CSS transitions for smooth animations
- Uses JavaScript's eval() function for calculations
- Canvas API for drawing functionality
- Mathematical expression parsing and plotting
- Dynamic grid system for graphing
- PNG export capability

## Note

This calculator uses JavaScript's `eval()` function for calculations. While this is suitable for learning purposes, in a production environment, you might want to implement a more secure method of evaluating expressions.

## Installation

1. Clone the repository or download the files
2. Open `index.html` in your web browser
3. No additional installation or dependencies required

## Browser Support

Works on all modern browsers including:

- Chrome
- Firefox
- Safari
- Edge
