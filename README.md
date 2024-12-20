# Flip Card Memory Game

This project is a simple and fun flip card memory game implemented using HTML, CSS, and JavaScript. The game involves flipping cards to find matching pairs. Once all pairs are matched, the game is won!

---

## Features

- A responsive grid layout for the game board.
- Cards flip with a 3D animation effect.
- Includes a reset button to restart the game at any time.
- Keeps track of matched pairs to determine when the game is won.
- Displays unique images for each pair of cards.

---

## How to Play

1. Open the game in a web browser.
2. Click on any card to flip it and reveal the image.
3. Try to find the matching pair by flipping another card.
4. If the cards match, they will remain flipped.
5. If the cards don’t match, they will flip back.
6. Continue until all pairs are matched to win the game.

---

## Folder Structure

```
project-folder/
|— index.html          # Main HTML file for the game
|— styles.css          # CSS for styling the game (embedded in HTML in this project)
|— script.js           # JavaScript for game logic (embedded in HTML in this project)
|— images/             # Folder containing card images
```

---

## Setup

1. Clone the repository or download the project files.
2. Place your card images in the `images/` directory. Ensure the file names match those specified in the `cardImages` array in the JavaScript section.
3. Open the `index.html` file in a web browser to play the game.

---

## Customization

- **Card Images:** Update the `cardImages` array in the JavaScript to include paths to your custom images.
- **Grid Layout:** Modify the CSS `grid-template-columns` property in the `.game-board` class to adjust the grid size.
- **Animations:** Customize the CSS transitions for card flipping.

---

## Technologies Used

- **HTML**: For the structure of the game.
- **CSS**: For styling and animations.
- **JavaScript**: For the game logic and DOM manipulation.

---

## Future Enhancements

- Add a timer to track how quickly the game is completed.
- Include a counter to track the number of moves.
- Provide different difficulty levels by varying the number of cards.

---

## License

This project is open-source and available for use and modification under the [MIT License](LICENSE).

---

Enjoy playing the Flip Card Memory Game!

