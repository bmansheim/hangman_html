## Hangman HTML

A [hangman game](https://github.com/rothsandro/one-html-page-challenge/blob/master/entries/hangman.html) that is contained in a single HTML page copied from https://onehtmlpagechallenge.com/.

[![Netlify Status](https://api.netlify.com/api/v1/badges/b7988930-f581-4533-a478-ee5cba78eef5/deploy-status)](https://app.netlify.com/sites/hang-haman/deploys)

This repository is the basis for a GitHub training class for technical writers.

Concepts covered in the course are:

- Setting up git
- Cloning a repostiory
- Committing changes
- Pushing to a remote repository

## What's in the repository?

The repository includes:

- README.md - This readme file
- LICENSE - A copy of the GNU GPLv3 license (choosealicense.com)
- index.html - The HTML file that contains the game code

## What's in the HTML file?

The hangman game consists of a single HTML file. The HTML files includes:

- <style> - The CSS for HTML elements
- <script> - The functions that define the gameplay.

## How do I change the gameplay?

To customize the game, edit the texts in these section of the HTML:
  - `const wordList` - The list of words for the game
  - `game.hasWon()` - The messages for the end of the game
  - `drawResult(faults)` - The messages for incorrect letters
  - `pickedLetter(letter)` - The messages for when you pick a letter