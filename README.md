# Tic-Tac-Toe 
A classic Tic-Tac-Toe game built with Java Swing using the Model-View-Controller (MVC) design pattern for clean, organized code.

## Features
- **Separated Logic**: Model, View, and Controller are independent.

- **Centered UI**: Uses GridBagLayout so the board stays centered and doesn't stretch when maximized.

- **Auto-Detect**: Detects wins/draws and notifies via popups.

- **Auto-Reset**: Board clears automatically after each game.

## Tech Stack
- **Language**: Java

- **Framework**: Java Swing (GUI)

- **Layout Managers**: GridLayout (for the game board) and GridBagLayout (for UI centering)

## Project Structure

```
📁 TicTacToeProject/
├── 📁 src/
│   ├── Main.java
│   ├── TicTacToeModel.java
│   ├── TicTacToeView.java
│   └── TicTacToeController.java
├── 📁 img/
│   └── tictactoe.png
│ 
├── .gitignore
├── README.md
```

## How to Run

### Command Line

- **Step 1**: Clone the repository
```
git clone https://github.com/yourusername/tictactoe-java.git
```

- **Step 2**: Compile the source
```
javac src/*.java
```

- **Step 3**: Run the game
```
java -cp src Main
```

### IDE (VS Code, IntelliJ, Eclipse)
Simply open the project folder and run the Main.java file.


## Future updates
- May add an AI player and an optional level of difficulty
- UML Class and Sequence Diagram
