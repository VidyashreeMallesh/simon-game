# Simon Game

This is a web-based implementation of the classic Simon game. The game challenges the player to remember and repeat a sequence of colors, which gets progressively longer with each level.

## How to Play

1.  **Start the Game:** Press any key on your keyboard to begin the game.
2.  **Observe the Sequence:** The game will display a sequence of colors, each accompanied by a distinct sound.
3.  **Repeat the Sequence:** Click the buttons in the same order as the displayed sequence.
4.  **Advance Levels:** If you successfully repeat the sequence, the game will add another color to the sequence, increasing the difficulty.
5.  **Game Over:** If you make a mistake, the game will display "Game Over," and you can restart by pressing any key.

## Project Structure

simon-game/
├── index.html        # Main HTML file for the game
├── styles.css        # CSS stylesheet for styling the game
├── game.js           # JavaScript file containing the game logic
├── sounds/           # Directory containing sound files
│   ├── blue.mp3
│   ├── green.mp3
│   ├── red.mp3
│   ├── yellow.mp3
│   └── wrong.mp3
└── README.md         # Project documentation (this file)

## Technologies Used

* **HTML:** For structuring the web page.
* **CSS:** For styling the game's appearance.
* **JavaScript:** For implementing the game logic and user interactions.
* **jQuery:** For simplifying DOM manipulation and event handling.
* **Audio API:** For playing sound effects.
* **Google Fonts:** For the "Press Start 2P" font.

## Setup

1.  **Clone the Repository:**
    ```bash
    git clone [repository_url]
    cd simon-game
    ```

2.  **Open `index.html`:** Open the `index.html` file in your web browser.

3.  **Ensure Sound Files:** Make sure the `sounds` folder is in the same directory as the `index.html` file and that the sound files (`blue.mp3`, `green.mp3`, `red.mp3`, `yellow.mp3`, and `wrong.mp3`) are present.

## Dependencies

* jQuery (included via CDN in `index.html`)

## Notes

* The game uses sound files located in the `sounds` directory. Ensure these files are present for the game to function correctly.
* The game's difficulty increases with each level, as the sequence length grows.
* The styling can be modified by editing the `styles.css` file.
* The Game logic can be modified by editing the `game.js` file.
* This project is for educational or personal use.