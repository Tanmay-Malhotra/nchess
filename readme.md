a chess thingy or smth
george hotz 🤲🤲

establish the search tree
use a neural net to prune the search tree 

V = f(state)

State(Board)

8x8x4 + 1

1: whose turn it is to move ??


A chessboard is an 8x8 grid with 64 squares, and each square can contain different pieces or be empty. The "4" in the 8x8x4 representation typically corresponds to different features or layers of the board's state. In most cases, these layers are used to track different aspects of the game. Here's a common interpretation of what the "4" layers might represent:

White pieces: 
A binary layer where each bit represents whether a white piece is on a particular square (1 for present, 0 for absent).

Black pieces: 
A binary layer representing the presence of black pieces in the same way.

Piece type: 
A binary layer representing whether the piece on a square is a certain type (e.g., a pawn, rook, etc.). This layer could encode specific piece types if extended.

Additional information (e.g., castling rights or en passant): This layer might track game-specific details, such as castling availability, en passant targets, or which player's turn it is.

