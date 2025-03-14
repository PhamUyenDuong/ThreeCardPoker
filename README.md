# Three Card Poker – Client-Server JavaFX

## Overview
- A dynamic Three Card Poker app with client-server round management, fold/play logic, and CSS-based theming (Default, Look 1, Look 2).
- Implements Player, Dealer, and ThreeCardLogic classes for multi-round gameplay, bet validations, and outcome resolution.

## Key Features
- Client-Server Connection for real-time state updates.
- JavaFX UI with card dealing animations, fold/play actions, exit screen continuity, and easy style switching.
- Runtime Theming: Switch among multiple looks at runtime; codebase includes ~1,000 lines of modular Java & FXML.

## Setup & Run
- Clone: git clone https://github.com/YourUsername/ThreeCardPoker.git
- Open in IDE; confirm JavaFX libraries and Java 11+ are configured.
- Command to run: *mvn compile exec:java*
- Run the JavaFXTemplate class – welcomes you to the bet screen.
- CSS Themes: Go to Options -> New Look to explore different color schemes.

## Usage
- Bet window: Enter Ante + optional Pair Plus; click Done to proceed.
- Game screen: Displays deals, logs bets/actions, and handles multi-round flow.
- Exit screen: “Quit” closes app; “Continue” returns to game.
- Styles: Switch them at any time without restarting the game.


*Thank you for checking out this Three Card Poker project!*
