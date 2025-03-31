# Rock Paper Scissors Game in C

A simple command-line Rock-Paper-Scissors game written in **C**. The player competes against the computer, which makes a random choice.

## Features
- Uses **randomization** for computer's choice.
- Implements **game logic** using conditional statements.
- Simple and **interactive** console-based interface.

## How It Works
1. The player selects **Rock (r), Paper (p), or Scissors (s)**.
2. The computer randomly selects one of the three choices.
3. The winner is determined based on the standard game rules:
   - **Rock beats Scissors**
   - **Scissors beats Paper**
   - **Paper beats Rock**
4. The result is displayed on the screen.

## Installation & Compilation
### Requirements
- A **C compiler** (e.g., GCC)
- A terminal or command prompt

### Compile the Program
Use the following command to compile the program with GCC:
```sh
gcc rock_paper_scissors.c -o rock_paper_scissors
```

### Run the Program
After compilation, run the game using:
```sh
./rock_paper_scissors
```

## Example Gameplay
```
Enter r for Rock, p for Paper, or s for Scissors: r
You Win! :)
Player chose: r, Computer chose: s
```

## Contributing
Feel free to fork this repository and submit a pull request if you want to improve the game!

## License
This project is open-source.

