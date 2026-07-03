# Java Click-A-Dot Game
Java Swing reaction game with clickable moving targets, score tracking, size/speed controls, and save-score functionality.

This is a Java Swing reaction game where the player clicks randomly appearing dots before they disappear. The game tracks the player’s score, allows the target size and speed to be adjusted with sliders, and includes a menu option for saving scores to a file.

## Features

- Java Swing graphical user interface
- Clickable target/dot game board
- Random target spawning
- Score tracking
- Start button for beginning a new game
- Adjustable target size slider
- Adjustable target speed slider
- File menu with save-score and exit options
- Score saving through a file chooser
- Mouse input handling
- Timer-based game updates

## Tech Stack

- Java
- Java Swing
- AWT event handling

## Project Structure

```text
java-click-a-dot-game/
├── README.md
├── .gitignore
├── src/
│   └── cs2110/
│       ├── GameComponent.java
│       └── GameMain.java
└── summary.txt
```

## How to Run

Make sure Java is installed.

Compile the source files:

```bash
javac -d out src/cs2110/*.java
```

Run the game:

```bash
java -cp out cs2110.GameMain
```

A game window titled `Click-a-Dot` should open.

## How to Play

1. Click **Start** to begin a new game.
2. Click the blue dots as they appear.
3. A clicked dot turns red and increases the score.
4. Use the **Size** slider to change the target size.
5. Use the **Speed** slider to change how quickly targets move.
6. Use **File → Save score** to append the current score to a file.
7. Use **File → Exit** to close the game.

## Notes

The project focuses on Java Swing GUI programming, event handling, timers, mouse input, property change listeners, and file output.
