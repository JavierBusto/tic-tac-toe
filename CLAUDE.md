# Tic Tac Toe Project

## Overview
A web-based Tic Tac Toe game playable directly in the browser. Two-player game with win detection, draw detection, and restart functionality.

## Project Setup
- **Repository**: https://github.com/JavierBusto/tic-tac-toe
- **Local Path**: /Users/javier.busto/ClaudeCodeTest
- **Initial Commit**: 99fc198 - Add Tic Tac Toe game

## Current Implementation

### Files
- `index.html` - Single-file game with HTML, CSS, and JavaScript

### Features
- Two-player gameplay (X and O)
- Click to place marks on a 3x3 grid
- Win detection (8 possible win combinations)
- Draw detection (board full with no winner)
- Game status display showing whose turn it is
- Restart button to reset the game
- Dark theme UI with red/blue color scheme

### Game Logic
- Alternates between X and O players
- Prevents moves on already-filled cells
- Detects win on any of 8 combinations: rows, columns, diagonals
- Ends game on win or draw
- Highlights winning cells on victory

## Technology
- Vanilla HTML/CSS/JavaScript (no dependencies)
- Responsive grid layout
- Smooth animations and hover effects

## Next Steps (if needed)
- Add AI opponent for single-player mode
- Add score tracking across multiple games
- Add touch support enhancements for mobile
- Add game history/replay features
