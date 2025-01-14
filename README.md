# Rock Paper Scissors Game

This is a simple and interactive Rock Paper Scissors game implemented using HTML, CSS, and JavaScript. The game allows users to play against a computer opponent and keeps track of scores for both players.

---

## Features

1. **Interactive Gameplay**:
   - Players can click on one of the three choices: Rock, Paper, or Scissors.
   - The game generates a random choice for the computer and compares it with the player's choice to determine the winner.

2. **Scoreboard**:
   - Tracks the scores of the player and the computer.

3. **Dynamic Messaging**:
   - Displays messages to indicate the result of each round (win, lose, or draw).

4. **Responsive Design**:
   - Adjusts layout and sizes for smaller screens to provide an optimal experience across devices.

---

## Technologies Used

- **HTML**: Structure of the game interface.
- **CSS**: Styling and layout, including responsiveness.
- **JavaScript**: Game logic and interactivity.

---

## How to Run the Project

1. **Download or Clone the Repository**:
   ```bash
   git clone <repository-url>
   ```

2. **Navigate to the Project Folder**:
   ```bash
   cd rock-paper-scissors
   ```

3. **Open the `index.html` File in a Web Browser**:
   - Double-click on `index.html` or open it through your preferred browser.

---

## File Structure

```
rock-paper-scissors/
|-- index.html        # Main HTML file
|-- style.css         # CSS file for styling
|-- app.js            # JavaScript file for game logic
|-- images/           # Folder containing choice images (rock.png, paper.png, scissors.png)
```

---

## Gameplay Instructions

1. Open the game in your browser.
2. Choose one of the options:
   - Rock
   - Paper
   - Scissors
3. The computer will automatically make its choice.
4. The game will display the result and update the scores.
5. Play as many rounds as you like!

---

## How It Works

1. **Game Logic**:
   - Each choice (rock, paper, scissors) has a defined interaction with the others:
     - Rock beats Scissors
     - Paper beats Rock
     - Scissors beat Paper
   - If both the player and computer make the same choice, it’s a draw.

2. **Computer Choice**:
   - The computer’s choice is randomly generated using JavaScript.

3. **Dynamic Updates**:
   - Scores and messages are updated in real-time using DOM manipulation.

---

## Responsive Design

- The game layout adjusts for smaller screens using CSS media queries.
- Buttons and text scale dynamically to ensure usability on mobile devices.

---

## Screenshots

1. **Desktop View**:
   ![Desktop View](./screenshots/desktop-view.png)

2. **Mobile View**:
   ![Mobile View](./screenshots/mobile-view.png)

(Note: Replace the image paths with actual screenshot file paths after taking screenshots.)

---

## Future Enhancements

1. Add more game options.
2. Include sound effects for game events.
3. Provide an option to reset the scores.
4. Add animations for a better user experience.


