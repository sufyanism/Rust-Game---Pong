
# Rust Pong Game
A simple implementation of the classic Pong game built in Rust. This project showcases basic graphics rendering, user input handling, and game physics using the `piston` game engine.

</br>

## Setup & Installation
```
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

</br>

### Tools and Libraries
*	Piston: A modular game engine in Rust. It provides functionalities such as handling events (keyboard, mouse, etc.), rendering graphics, and managing game windows.
*	OpenGL: A widely-used graphics library that helps render 2D and 3D graphics. The opengl_graphics crate is used to interface with OpenGL for rendering.
*	Graphics: A simple library that provides useful primitives (like rectangles) for rendering graphics in a 2D space.

</br>

## Features
- Two-player gameplay with keyboard controls
- Real-time paddle and ball movement
- Basic collision detection and physics
- Score tracking (future implementation planned)

</br>

## Design Overview
The game window contains:
- **Left Paddle:** controlled via `W` (up) and `S` (down)
- **Right Paddle:** controlled via `Up Arrow` and `Down Arrow`
- **Ball:** bounces off paddles and window edges
- **Score:** (to be implemented)

### Gameplay loop:
1. Handle user input to move paddles
2. Update ball position based on velocity
3. Detect collisions with paddles and window bounds
4. Render the current game state

## Screencast
https://github.com/user-attachments/assets/74c81a9e-9154-4d1b-9078-afd82155424f

</br>

## About Me 
✨ I’m **Sufyan bin Uzayr**, an open-source developer passionate about building and sharing meaningful projects.
You can learn more about me and my work at [sufyanism.com](https://sufyanism.com/) or connect with me on [Linkedin](https://www.linkedin.com/in/sufyanism)
</br>

## Your all-in-one learning hub! 
🚀 Explore courses and resources in coding, tech, and development at **zeba.academy** and **code.zeba.academy**. Empower yourself with practical skills through curated tutorials, real-world projects, and hands-on experience. Level up your tech game today! 💻✨

</br>

**Zeba Academy**  is a learning platform dedicated to **coding**, **technology**, and **development**.  
➡ Visit our main site: [zeba.academy](https://zeba.academy)   </br>
➡ Explore hands-on courses and resources at: [code.zeba.academy](https://code.zeba.academy)   </br>
➡ Check out our YouTube for more tutorials: [zeba.academy](https://www.youtube.com/@zeba.academy)  </br>
➡ Follow us on Instagram: [zeba.academy](https://www.instagram.com/zeba.academy/)  </br>

</br>

**Thank you for visiting!** 
