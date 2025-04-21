# 2048-game
 
NORTH SOUTH UNIVERSITY
COURSE : CSE 115L     SECTION ; 11

Submitted To: Rejuana Islam 
Prepared By:  AYON HOSSAIN
 ID: 2513295042
 Email: ayon.hossain.251@northsouth.edu
Project Title: 2048 game
Submission Date: 21/04/2025 
Project Report: 2048 Console Game in C
1. Overview
This project is a console-based implementation of the popular 2048 puzzle game, developed in the C programming language. It supports variable board sizes ranging from 2×2 to 8×8 and allows gameplay using standard keyboard controls: W (up), A (left), S (down), and D (right).

To enhance user interaction, the game includes the following features:

Score tracking

One-step undo functionality

Real-time input detection using getch()

Colour-coded tile display for improved visual distinction

2. Project Goals
The primary objectives of this project were to:

Recreate the core mechanics and logic of the original 2048 game.

Allow the user to select and play on different board sizes.

Implement supporting features like scorekeeping, undo, and random tile generation.

Improve user experience through the use of console colours to visually differentiate tiles.



3. Employed Technologies

Tool/Library      	Purpose
stdlib.h    	Memory allocation, random number generation
time.h   	Seed for random tile generation
windows.h	Coloured output and system-related functionality in the console
conio.h	              Real-time keyboard input using getch()
These libraries enabled real-time gameplay, visual feedback, and efficient control over system resources, making the console experience interactive and responsive.

4. Rationale for Language Selection
C was chosen for the following reasons:

Offers low-level control for optimal performance and memory management.

Allows real-time input handling through getch() without needing the Enter key.

Provides granular control over console manipulation using windows.h.

Encourages modular design for improved code readability and maintenance.

5. Core Features
The following are the essential features implemented in the project:

Tile merging and movement in all four directions (W, A, S, D).

Real-time score tracking based on successful merges.

One-step undo functionality for strategic recovery.

Random generation of tiles (2 or 4) after each valid move.

Detection of game-over scenarios (no more valid moves).

Support for multiple board sizes from 2x2 up to 8x8.

6. Current Limitations
Despite offering a robust console-based experience, there are a few limitations:

Currently compatible only with Windows, due to dependencies on windows.h and conio.h.

Only a single undo operation is supported at a time.

No implementation for high score tracking or game state saving/loading.

Lacks a graphical user interface—purely text-based console interaction.

7. Future Enhancements
Planned upgrades for improving functionality and reach include:

Implementing save/load functionality and multi-level undo.

Adding persistent high score tracking via file I/O.

Making the game cross-platform by replacing Windows-specific libraries with alternatives like ncurses.

Developing a graphical version (desktop or web-based).

Enhancing the user interface with better effects and layout organization.

8. Conclusion
This project successfully recreates the essence of the 2048 game within a console environment using C. It showcases effective use of logic design, array manipulation, modular programming, and basic console UI enhancements using colour. While the current implementation is functional and engaging, the outlined future improvements have the potential to transform it into a more polished, cross-platform, and visually engaging application.

 
