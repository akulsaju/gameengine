# Advanced 2D Game Engine

## Overview

The Advanced 2D Game Engine is a customizable game engine developed using Pygame. It features dynamic weather effects, advanced AI behaviors, basic networking, and a save/load system. The engine provides a base for creating 2D games with enhanced visual effects and interactive elements.

## Features

- **Dynamic Weather Effects**: Includes rain and snow effects to enhance the visual experience.
- **Advanced AI Behaviors**: Enemies can switch between patrol and chase modes.
- **Customizable Shaders**: Placeholder functions for applying basic shader effects like blur and sepia.
- **Save/Load System**: Save and load game state using JSON files.
- **Networking**: Basic server-client architecture for multiplayer or networked games.
- **Particle Effects**: Adds visual effects with particles to enhance gameplay dynamics.

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/akulsaju/gameengine.git
   cd your-repository
   ```

2. **Install Dependencies**

   Make sure you have Python and Pygame installed. You can install Pygame using pip:

   ```bash
   pip install pygame
   ```

   Additionally, ensure you have the required sound files (`background_music.mp3`, `hit_sound.wav`, and `power_up_sound.wav`) in the project directory.

## Usage

1. **Run the Game**

   ```bash
   python game_engine.py
   ```

2. **Controls**

   - **Arrow Keys**: Move the player
   - **S**: Save the game
   - **L**: Load the game
   - **P**: Pause background music
   - **R**: Resume background music

3. **Networking**

   The server will start automatically in a separate thread. To connect clients, you need to implement the client-side logic separately.

## File Structure

- `game_engine.py`: Main script for running the game engine.
- `savegame.json`: Game save file (automatically created).
- `background_music.mp3`: Background music file.
- `hit_sound.wav`: Sound effect for player-enemy collisions.
- `power_up_sound.wav`: Sound effect for power-ups.

## Customization

- **Weather Effects**: Modify the `draw_weather()` function in `game_engine.py` to customize weather effects.
- **AI Behaviors**: Adjust the `update()` method in the `Enemy` class to change enemy AI behavior.
- **Shaders**: Implement actual shader effects in the `apply_shader()` function.

## Contributing

Feel free to contribute to this project by submitting issues or pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. 

## Contact

For any questions or feedback, please reach out to [akul_saju@hotmail.com](mailto:akul_saju@hotmail.com).

---

Happy gaming!
