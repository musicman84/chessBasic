# chessBasic
Simple chess game.
Currently the computer will pick legal moves at random (if the game is not being played 2 player).
Rules implemented are:
*Player turn taking
*Moving a piece onto a space occupied by an opponents piece removes the opponents piece from the game
*All basic moves are fully implemented
*Check
*check-mate

Rules yet to be implemented are:

*En passant
*Castling
*Piece promotion
*draws

Instructions to play:
*On startup, enter number of players
*Select view of board (from white's view or black's) {Dev note- could added dynamic view option - view from player whose turn it is}
#Board will then be displayerd. '..' is an empty space, 'W' or 'B' first letter specifies that the piece is white or black respectively
#second letter specifes the piece as:
    p = pawn
    r = rook
    n = knight
    b = bishop
    k = king
    q = queen
*Player 1's turn (white pieces) - select piece to move by cooardinates (coloumn letter, row number) for example A2 (or a2), then select..
*.. piece destination using the same coordinates system
*Player 2's turn (black pieces) - see above
