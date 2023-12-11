Certainly! Here's a README.md file for your Scrabble game:

```markdown
# Scrabble Game

Welcome to the Scrabble Game! This simple Python program allows players to enter words and calculates their scores based on Scrabble letter-point mappings.

## Instructions

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/scrabble-game.git
   cd scrabble-game
   ```

2. Run the game:
   ```bash
   python scrabble_game.py
   ```

3. Enter words when prompted. The program will calculate and display each player's score after each turn.

4. To end the game, type "no" when asked, "Continue game? (yes/no):".

## Functionality

- **score_word(word):**
  - Calculates the score of a given word based on Scrabble letter-point mappings.

- **play_game():**
  - Allows multiple players to take turns entering words.
  - Displays each player's score after each turn.
  - Ends when players decide to stop.

## Letter-Point Mappings

The game uses the following letter-point mappings:

| Letter | Point |
| ------ | ----- |
| A      | 1     |
| B      | 3     |
| C      | 3     |
| ...    | ...   |
| (space)| 0     |

## Unit Testing

To verify the correctness of the scoring function, unit tests have been provided. Run the tests with:
```bash
python Test.py
```

## Contribution

Feel free to contribute to this project by submitting bug reports, feature requests, or enhancements. Happy coding!
```

 
