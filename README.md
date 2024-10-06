# Wordle Clone

## Overview

This project is a clone of the popular word-guessing game Wordle. It challenges users to guess a five-letter word within six attempts. After each guess, the game provides feedback on the correctness of each letter, indicated by color-coding:

- **Green**: The letter is correct and in the correct position.
- **Orange**: The letter is correct but in the wrong position.
- **Grey**: The letter is incorrect.

This implementation consists of a backend server built with Node.js and Express, and a front-end interface that interacts with the backend to provide the game experience.

## How to Play

1. **Guess the Word**: Type in a five-letter word and press **Enter**.
2. **Receive Feedback**: After each guess, each letter's background color will change to indicate whether it's correct, misplaced, or incorrect.
3. **Correct the Word**: Use the feedback to correct your next guess. You have six attempts to guess the correct word.

## Published Website

Visit the live game here: [Wordle Clone](https://fifth-fresh-ketch.glitch.me/)

## Dependencies

- **Node.js**: JavaScript runtime environment.
- **Express.js**: Web framework for Node.js to create the server.
- **Animate.css**: Library for animations to enhance user interaction.
