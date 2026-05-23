# Strategic Tic-Tac-Toe (Chinese Variation)

## 💻 Overview
An advanced implementation in **C# Windows Forms** of a strategic "Tic-Tac-Toe" variant using pieces of varying sizes (Gobblet-style). Players place pieces of different sizes on a 3x3 grid, where larger pieces can capture/cover smaller ones. This adds an extra layer of tactical complexity compared to the classic game.

---

## 🤍 Tech Stack
* **Language:** C#
* **Framework:** .NET Framework / Windows Forms (WinForms)
* **Core Concepts:** Game Matrices, Dynamic Event Handling, State Management

![C#](https://img.shields.io/badge/C%23-Language-%23FF69B4.svg?style=for-the-badge&logo=csharp&logoColor=white) ![UI/UX](https://img.shields.io/badge/UI-WinForms-%23333333.svg?style=for-the-badge)

---

## 🎀 Core Functionality
* **Dynamic Piece Management:** Interface allowing the selection of pieces with three different sizes (Small, Medium, Large) for both players (Green vs. Black).
* **Game Logic (Engine):** Implemented via a dedicated `Matrice` class that validates moves, checks winning conditions, and detects draws.
* **Visual Interaction:** Utilizes custom `Cursor` pointers to provide immediate visual feedback when a player "picks up" a piece to move it.
* **Game State Control:** A "New Game" button that fully resets the board, score, and game state without restarting the application.

---

## 📂 Project Structure
* **`Form1.cs`**: Manages the UI, renders the game board (programmatically generated buttons), and handles the move flow.
* **`Matrice.cs`**: The game's "brain"; contains the rules for placing pieces, checking winning lines, and tracking the current state of the board.
* **`IncarcaImagini()`**: Method for loading graphical resources (images for each piece size).
* **`PuneBila()`**: Main function that updates the board and checks game status after every action.

---

## Visual Demonstration
| Interface | Gameplay (Covering Logic) |
| :---: | :---: |
|<img width="600" src="https://github.com/user-attachments/assets/e5aa9b90-449d-4503-8283-2badd5b2403d" /> | <img width="600" src="https://github.com/user-attachments/assets/71666cc5-3d9d-4bff-8de3-4a3817b4b4ff" /> |

---

## How to Run
1. **Compile:** Open the solution in Visual Studio and perform a *Build*.
2. **Launch:** Run the compiled executable.
3. **Play:** * Select a piece from the left panel (Green or Black).
    * Click on the 3x3 grid to place the selected piece.
    * Strategy is key: you can cover opponent pieces to take control of the board!

---

© 2026 Strategic Tic-Tac-Toe | Developed by [**𝐋𝐞𝐨𝐧𝐭𝐞 𝐏𝐚𝐭𝐫𝐢𝐜𝐢𝐚-𝐌𝐢𝐫𝐚𝐛𝐞𝐥𝐚**](https://patrrrrrrricia.github.io/glowing-button/)
