# Rust Pong Game

A simple implementation of the classic Pong game built in Rust. This project showcases basic graphics rendering, user input handling, and game physics using the `piston` game engine.

![Screenshot or GIF of the game](path/to/screenshot.png)

</br>
https://github.com/user-attachments/assets/74c81a9e-9154-4d1b-9078-afd82155424f

---

## Features

- Two-player gameplay with keyboard controls
- Real-time paddle and ball movement
- Basic collision detection and physics
- Score tracking (future implementation planned)

---

## Design Overview

The game window contains:

- **Left Paddle:** controlled via `W` (up) and `S` (down)
- **Right Paddle:** controlled via `Up Arrow` and `Down Arrow`
- **Ball:** bounces off paddles and window edges
- **Score:** (to be implemented)

Gameplay loop:

1. Handle user input to move paddles
2. Update ball position based on velocity
3. Detect collisions with paddles and window bounds
4. Render the current game state

---

## Prerequisites

- Rust compiler installed. If not, install from [rustup.rs](https://rustup.rs/).

---

## Setup & Installation

```bash
# Clone the repository
git clone https://github.com/sufyanism/Rust-Game---Pong.git
cd Rust-Game---Pong

# Build the project
cargo build

# Run the game
cargo run
# Rust Pong Game.
It simulates a table tennis match where two players control their paddles while attempting to hit the ball past their opponent.
```

### Prerequisites
Set Up the Project “edit name as per choice”
First, create a new Rust project:
`cargo new rust_pong_game_master`
`cd rust_pong_game_master`
`cargo run` 

### Tools and Libraries
*	Piston: A modular game engine in Rust. It provides functionalities such as handling events (keyboard, mouse, etc.), rendering graphics, and managing game windows.
*	OpenGL: A widely-used graphics library that helps render 2D and 3D graphics. The opengl_graphics crate is used to interface with OpenGL for rendering.
*	Graphics: A simple library that provides useful primitives (like rectangles) for rendering graphics in a 2D space.

## Screencast
https://github.com/user-attachments/assets/74c81a9e-9154-4d1b-9078-afd82155424f

