# PokémonGuessr

PokémonGuessr is a daily challenge for trainers who think they know it all! Each day, a new mystery Pokémon from the original 151 is chosen, and you have 15 tries to guess its name.

---

## How to Play

1.  **Guess a Pokémon:** Start typing a Pokémon's name into the input field. Suggestions will appear as you type. Click on a suggestion to make your guess.
2.  **Get Clues:** After each guess, a new row will appear in the table, comparing your guessed Pokémon's stats and type to the target Pokémon.
3.  **Analyze the Colors:**
    * **Green:** Perfect match! You got the stat, type, or Pokémon name exactly right.
    * **Yellow:** Close! For stats, this means the value is within 10 of the target.
    * **Orange:** (For Type only) Partial match! One or more of your guessed Pokémon's types are present in the target Pokémon's types, but it's not a complete match.
    * **Red:** No match! The stat or type is completely different from the target.
4.  **Arrows (for Stats, Height, Weight):**
    * ⬆️: The guessed value is lower than the target value.
    * ⬇️: The guessed value is higher than the target value.
    * No arrow: The guessed value is exactly the same as the target value (and the cell will be green).
5.  **Win or Lose:**
    * If you guess the correct Pokémon, you win!
    * If you run out of 15 tries, you lose, and the correct Pokémon will be revealed.
6.  **Play Again:** After the game ends (win or lose), you'll have the option to play again, which will start a new game with a new mystery Pokémon for the current day.

---

## Features

* **Daily Challenge:** A new mystery Pokémon from Generation 1 is chosen daily.
* **Autocomplete Suggestions:** Helps you find Pokémon names easily as you type.
* **Detailed Comparison:** Provides feedback on Type, HP, Attack, Defense, Special Attack, Special Defense, Speed, Height, and Weight.
* **Color-Coded Feedback:** Quickly understand how close your guess is with green, yellow, orange, and red indicators.
* **Stat Trend Indicators:** Arrows show if your guessed Pokémon's stats are higher or lower than the target.
* **Dark Mode:** Toggle between light and dark themes for comfortable play in any environment.
* **Duplicate Guess Prevention:** You can't guess the same Pokémon twice in one game.

---

## Technologies Used

* **HTML5:** Structure of the web page.
* **CSS3:** Styling and responsive design.
* **JavaScript (ES6+):** Game logic, API interaction, and DOM manipulation.
* **PokeAPI:** For fetching Pokémon data (limited to the first 151 Pokémon).
* **Google Fonts ('Press Start 2P'):** For the retro, pixelated font style.

---

## Setup (For Local Development)

To run this game locally:

1.  Save the entire provided HTML code into a file named `index.html`.
2.  Open `index.html` in your web browser.

No external build tools or server is required, as all assets are loaded via CDN or are self-contained within the HTML file.
