# Alien Invasion Game

This is a simple 2D shooting game written in Python using the [Pygame](https://www.pygame.org/news) library.  
The game is inspired by the classic alien invasion concept — your mission is to control a spaceship, shoot down incoming alien fleets, and achieve the highest score possible!

## Features

- Player-controlled spaceship that can move left and right
- Bullets to destroy aliens
- Multiple waves of aliens
- Increasing difficulty
- Score tracking
- Simple sound effects and graphics

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/alien-invasion.git
   cd alien-invasion
   ```

2. **Install dependencies**

   Make sure you have Python installed (version 3.7 or higher recommended).  
   Install Pygame using pip:

   ```bash
   pip install pygame
   ```

## How to Play

- Run the game with:

  ```bash
  python alien_invasion.py
  ```

- Use the **arrow keys** (← →) to move your spaceship.
- Press the **space bar** to shoot bullets.
- Avoid letting the aliens reach the bottom.
- Try to beat your high score!

## Folder Structure

```
alien-invasion/
│
├── main.py                # Main game file
├── settings.py            # Game settings
├── ship.py                # Spaceship class
├── alien.py               # Alien class
├── bullet.py              # Bullet class
├── button.py              # Button class
├── alien_bullet.py        # Aliens class
├── explosion.py           # Explosion class
├── fruit.py               # Health class
├── scoreboard.py          # Scoreboard class
├── images/                # Game images (spaceship, aliens, background)
├── sounds/                # Sound effects (optional)
└── README.md              # Project documentation
```

## Requirements

- Python 3.7+
- Pygame

## Contributing

Pull requests are welcome! If you have ideas to improve the game, feel free to fork this repository and submit a PR.

## License

This project is licensed under the MIT License.

## Acknowledgements

- Created as a practice project to learn Python and Pygame.
- Inspired by the *Alien Invasion* game project in the book *Python Crash Course* by Eric Matthes.

---

**Have fun playing! 🚀👾**
