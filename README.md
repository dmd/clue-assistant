# Clue Assistant

A single-file web app (`index.html`) for tracking a Clue/Cluedo game and making deductions about who owns each card and what is in the envelope.

## Quick Start

1. Open `index.html` in a browser.
2. Enter player count and names.
3. Select your own cards.
4. Record suggestions and known card facts as the game progresses.

## How to Use It

1. **Setup**
   - Choose 3-6 players.
   - Choose card set (`Classic` with `Mrs. White`/`Pistol`, or `Modern` with `Dr. Orchid`/`Revolver`).
   - Enter unique player names.
   - Mark your own cards.
2. **Record suggestions**
   - Select who suggested.
   - The suggester dropdown rotates so the next player in turn order appears first.
   - Select suspect, weapon, and room.
   - Enter responses in clockwise order (`Pass`, `Showed card`, or `Showed me` with exact card).
3. **Record manual facts**
   - Use **Record Known Card** to add direct facts like `Player X has Card Y` or `Player X does NOT have Card Y`.
4. **Review deductions**
   - The deduction grid shows hard facts (`Y` / `N`) and probabilities for unresolved cells.
   - Suggestions auto-advance to the next suggester for faster turn entry.
5. **Undo / reset**
   - Undo reverts the most recent recorded event.
   - Reset clears the current game.


## Acknowledgements

Thanks to Greg Stoll's Clue Solver project for the algorithmic foundation and inspiration:

- https://github.com/gregstoll/cluesolver

This implementation follows the same algorithm from that project.
