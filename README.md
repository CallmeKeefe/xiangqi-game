# Xiangqi — Chinese Chess

A standalone browser-based Xiangqi (Chinese chess) game, implemented in a single HTML file.

## Features

- Play locally against another person or against the built-in AI.
- Choose to play Red or Black against the AI.
- Select AI difficulty from Beginner through Expert.
- Undo a move, start a new game, and toggle sound.
- View the board, turn indicator, check/win status, move history, and in-page game analysis.

## Run locally

No build tool or package installation is required.

1. Download or clone this repository.
2. Open [`xiangqi_pro.html`](./xiangqi_pro.html) in a modern browser.
3. Select a mode and difficulty, then play.

The page loads Google Fonts over the network for typography; the game itself is contained in the HTML file.

## Limitations

- The game runs in the browser and does not provide online multiplayer or a hosted game service.
- AI strength labels are application settings, not a claim of tournament-engine strength.
- The analysis panel is an in-page heuristic/game analysis feature, not an independently verified professional engine.

## Contributing

Keep the game playable as a self-contained HTML file unless a deliberate project change introduces a build system. Test legal moves, check/checkmate handling, undo/new-game behavior, both player colors, and all difficulty settings after changes.
