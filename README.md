Update: In March 2025 I decided to revisit this project so the implementation is a better reflection of my current skill level (the project was originally written in November 23). My planned upgrades include improving the logic (more functional/modular, less five paragraph essay functions), adding the remaining rules to make it a full chess game, and converting from a cli to gui (likely using pygame). Stay tuned!

This program plays an abstract board game on the command line that is a variant of chess. The starting position for the game is the normal starting positon for standard chess, and, like standard chess, white moves first. The winner is the first player to capture all of an opponent's pieces of one type: e.g. capturing all of the opponent's knights would win the game or caputuring all of the opponent's pawns would win the game. The king is not a special piece in this game -- there is no check or checkmate. Pieces move and capture the same as in standard chess, except there is no castling, en passant or pawn promotion. Each pawn can move two spaces forward on its first move but not on subsequent moves. 
