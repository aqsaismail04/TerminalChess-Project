# TerminalChess-Project
Console Chess Game in C++ A text-based, two-player chess game built in C++. Play chess directly in your terminal with full move validation, check/checkmate detection, and undo/redo functionality. Perfect for learning C++ game logic and practicing board-based algorithms.


Console Chess Game in C++

A fully functional console-based chess game for two players with check, checkmate, undo, and redo functionality. Built in C++ for Windows.

Features

Two-player mode: White vs Black

Board displayed in console with coordinates (A–H, 1–8)

Undo and Redo previous moves

Check and checkmate detection

Simple text-based interface

How to Play

Compile the program:

g++ Chess.cpp -o Chess


Run the program:

./Chess   # or Chess.exe on Windows


Follow on-screen instructions:

Type Y to start the game or N to exit

Enter moves in format: E2 E4 (source → destination)

Commands:

Q → Quit the game

U → Undo last move

R → Redo last undone move

Game Rules Implemented

Valid moves for all pieces (pawn, rook, knight, bishop, queen, king)

Check detection (alerts if your king is in danger)

Checkmate detection (ends the game if no moves can save the king)

Limitations

No AI (2-player only)

Castling, en passant, and pawn promotion are not implemented

Uses system("pause") → Windows-only
