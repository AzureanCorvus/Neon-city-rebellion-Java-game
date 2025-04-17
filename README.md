# Neon-city-rebellion-Java-game

A 2D top-down cyberpunk shooter game built with Java
Features

    Fast-paced arcade shooter gameplay
    Multiple enemy types (normal, fast, tank)
    Power-up system (health, rapid fire, shields)
    Wave-based progression with increasing difficulty
    Neon cyberpunk visual effects
    Sound effects and background music

Requirements

    JDK 17 or higher
    IntelliJ IDEA (recommended) or other Java IDE

Installation

    Clone or download this repository
    Open the project in IntelliJ IDEA or your preferred IDE
    Make sure JDK 17+ is configured for the project
    Build the project

Controls

    Movement: WASD or Arrow Keys
    Shooting: Space Bar
    Menu Navigation: Arrow Keys + Enter

Game Assets

Place your game assets in the src/main/resources/assets directory:

    Images in src/main/resources/assets/images/
    Sounds in src/main/resources/assets/sounds/
    Music in src/main/resources/assets/music/

Sample placeholder assets are provided, but you should replace them with your own assets.
Architecture

The game follows a clean object-oriented architecture:

    Main: Entry point
    GameWindow/GamePanel: Core game container
    Entity System: Player, Enemy, Bullet, PowerUp classes
    State System: Menu, Play, GameOver states
    Asset Management: Loading and caching images and sounds
    Utility Classes: Collision detection, constants

Customization

You can easily customize and extend the game:

    Add new enemy types by extending the Enemy class
    Create new power-ups by extending the PowerUp class
    Adjust game balance in the Constants class
    Add new visual effects to the rendering methods

Credit

Developed as a demonstration of Java game development with proper architecture and clean code.
License
This project is provided for educational purposes.
