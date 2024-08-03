# Chess Game

This is a web-based chess game built using Node.js, Express, and Socket.io. The game allows two players to play chess in real-time, with additional features to highlight possible moves and captures for each piece.

## Features

- Real-time multiplayer chess game.
- Two players can come up and play a real time chess game online.
- Supports drag and drop feature.

- Displays the current state of the chessboard.
- Supports spectating mode if more than two players connect.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**

   ```sh
   git clone https://github.com/Mayank233444/ChessGame.git
   cd chess-game

2. **Install the dependencies:**
   
   ```sh
   npm install

3. **Start the server:**
   ```sh
   npm start

4. **Open your browser and navigate to:**
   ```sh
   http://localhost:3000

## Usage/Examples

1. **Playing the game**

- The first two connections will be assigned the roles of "white" and "black" players.

- Any additional connections will join as spectators.

- Drag on a piece for its possible moves and captures.

2. **Controls**

- Drag the piece you want to move and drop it to the desired valid move position.
 - After a checkmate the player will unable to move.

## Dependencies

- Node.js
- Express
- Socket.io
- chess.js


## Contributing

Contributions are always welcome!

 **If you want to contribute to this project, please follow these steps:**

- Fork the repository.
- Create a new branch (`git checkout -b feature-branch`).
- Make your changes.
- Commit your changes (`git commit -m 'Add some feature'`).
- Push to the branch (`git push origin feature-branch`).
- Open a pull request.

