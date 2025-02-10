# Rock-Paper-Scissors Game

A simple Rock-Paper-Scissors game implemented using Blazor, where the user plays against the computer. The game allows users to select Rock, Paper, or Scissors and displays the result of each round, as well as the running score.

## Features

- Choose between Rock, Paper, or Scissors with icons.
- The computer randomly selects one of the three choices.
- Displays the result of each round (win, lose, or tie).
- Tracks the score for both the user and the computer.

## Installation

To run this project, you need to have [ASP.NET Core](https://dotnet.microsoft.com/download) installed.

1. Clone the repository:
    ```bash
    git clone https://github.com/Princemashumu/RockPaperScissors.git
    ```
2. Navigate to the project folder:
    ```bash
    cd RockPaperScissors
    ```
3. Build and run the project:
    ```bash
    dotnet run
    ```

4. Open your browser and navigate to `https://localhost:5001` to play the game.

## How It Works

1. **User Interaction:**
   - The user can click on one of the three icons representing Rock, Paper, or Scissors.

   **Icons:**
   - 🪨 **Rock**: Represents the rock move.
   - 📄 **Paper**: Represents the paper move.
   - ✂️ **Scissors**: Represents the scissors move.

2. **Game Logic:**
   - After the user selects their move, the computer randomly chooses one of the three options.
   - The winner is determined by the standard Rock-Paper-Scissors rules:
     - Rock beats Scissors
     - Scissors beats Paper
     - Paper beats Rock
     - If both the user and the computer choose the same, it's a tie.

3. **Scoreboard:**
   - The game keeps track of the score for both the user and the computer, which is displayed at the bottom of the screen.

4. **Result Display:**
   - The result of each round (win, lose, or tie) is shown below the choices.

## Icons

We are using [FontAwesome](https://fontawesome.com/) icons for the game buttons. You can integrate these icons easily with the following steps:

1. Add FontAwesome CDN link to your `_Host.cshtml` file in the `<head>` section:

```html
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css" rel="stylesheet">
