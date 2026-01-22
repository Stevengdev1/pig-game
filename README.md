# Pig Dice Game

A browser-based two-player dice game built with HTML, CSS, and JavaScript.

This project recreates the classic Pig Dice Game, focusing on game logic, state management, DOM manipulation, and user interaction. Players take turns rolling a dice, accumulating points, and deciding when to hold their score with the risk of losing points if they roll a one.

## Purpose

This project was built to:
* Practice JavaScript fundamentals in a real interactive application.
* Work with DOM selection and manipulation.
* Manage application state without frameworks.
* Implement game rules and conditional logic.
* Connect UI updates to JavaScript events.
* Build confidence writing clean, readable JavaScript.

## Game Rules

* The game has two players.
* Players take turns rolling a dice.
* Each roll adds to the player’s current score.
* If a player rolls a 1, their current score resets to 0 and the turn switches.
* A player can choose to Hold, adding their current score to their total score.
* The first player to reach 100 points wins the game.

## Features

* Two-player turn-based gameplay.
* Dice roll generation using JavaScript.
* Dynamic score tracking.
* Active player highlighting.
* Winner state styling.
* New Game reset functionality.
* Responsive, modern UI design.

## Tech Stack

* HTML5
* CSS3
* Vanilla JavaScript (ES6)

## JavaScript Logic Overview

* Game state is managed using variables:
    * scores
    * currentScore
    * activePlayer
    * playing
* Event listeners handle user actions:
    * Roll Dice
    * Hold Score
    * Start New Game
* Functions are used to:
    * Initialize/reset the game.
    * Switch active players.
    * Update the UI dynamically.

* DOM manipulation updates:
    * Scores
    * Dice images
    * Active and winner states
No external libraries or frameworks are used.

## Styling Notes

* Flexbox is used for layout and alignment.
* Glassmorphism-style UI using transparency and blur.
* CSS transitions provide smooth visual feedback.
* Conditional CSS classes visually represent:
    * Active player
    * Winner state
* Buttons are absolutely positioned for consistent gameplay layout.

## Demo

Open the index.html file in your browser to play the game.
No build tools or dependencies required.