# Wordle Solver

A Wordle helper tool that allows users to filter potential word guesses based on letter position, inclusions, and exclusions, just like the game Wordle.

### [Live Demo](https://chunkymonkey00.github.io/wordleSolver/)

## Features

- **Include Letters**: Enter letters that must be in the word (yellow tiles in Wordle).
- **Exclude Letters**: Enter letters that should not be in the word (gray tiles in Wordle).
- **Filter by Position**: Specify letters and their exact positions (green tiles in Wordle).
- **Filter Not at Position**: Specify letters that should not be at certain positions (yellow tiles in Wordle).
- **Reset**: Easily reset the word list at any time to start a new filtering process.

## How to Use

1. Input yellow letters into the **Include Letters** section.
2. Put gray letters in the **Exclude Letters** section.
3. Enter green letters and their position (0-4) in the **Filter by Position** section.
4. Enter yellow letters and their position (0-4) in the **Filter Not at Position** section.
5. Each filter by position clears automatically, so enter one letter at a time. Repeating letters will not affect the list.
6. Use the **Reset** button to start over or after finishing your filtering.

## Project Structure

- **HTML**: The structure of the input fields and layout for filtering word lists.
- **CSS**: Styling for a clean, user-friendly interface.
- **JavaScript**: Logic for filtering the word list based on user input.

## License

This project is open-source and free to use.
