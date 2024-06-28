# React Dots Challenge

This is a simple React project that demonstrates the functionality of adding dots to the screen, undoing the last action, and redoing it.

## Features

- Add a dot to the screen where the user clicks.
- Undo the last dot addition action.
- Redo the last undone action.

## Technologies Used

- React
- useState hook for state management

## How to Use

1. **Click on the Screen**: Click anywhere on the screen to add a new dot at the clicked position.

2. **Undo Button**: Reverts the last dot addition action. Disabled if no dots have been added yet.

3. **Redo Button**: Reapplies the last undone action (after undoing a dot addition). Disabled if there's no action to redo.

## Folder Structure

- `src/App.js`: Contains the main React component with state management for dots.
- `src/App.css`: Stylesheet for the application layout and dot visualization.
