# Chess Game Using C++

This project contains the original C++ chess game and an interactive browser frontend.

## Structure

- chess_ineff.cpp - C++ chess game logic.
- frontend/index.html - chess game interface.
- frontend/style.css - responsive board and UI styling.
- frontend/script.js - interactive board, piece selection, movement and turn handling.

## Run the frontend

Open frontend/index.html directly in a browser, or use VS Code Live Server.

## Run the C++ version

Windows PowerShell:
g++ chess_ineff.cpp -o chess.exe
.\chess.exe

The frontend is currently a browser UI layer. The existing C++ program remains the project logic; a future integration step can connect the browser UI to the C++ backend through a local server/API.
