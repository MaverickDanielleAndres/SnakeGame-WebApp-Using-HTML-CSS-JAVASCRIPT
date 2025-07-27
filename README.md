<img width="1000" height="869" alt="image" src="https://github.com/user-attachments/assets/12f985b8-7dca-4205-9d83-4782ef2fc6c3" />
# 🐍 Ultra Snake Game

An enhanced version of the classic Snake game with modern features, power-ups, and challenging gameplay. Built with HTML, CSS, and JavaScript in a single file.

## 🎮 Features

- **Classic Snake Gameplay**: Control the snake using arrow keys
- **Scoring System**: Earn points by eating food
- **Top Score Tracking**: Persistent high score storage using localStorage
- **Level Progression**: Game gets faster as you level up
- **Power-ups**: Special items with unique effects
- **Collision Detection**: Game over when hitting walls or yourself
- **Visual Effects**: Particle animations and smooth graphics
- **Responsive Design**: Works on different screen sizes
- **Help Modal**: In-game instructions accessible via help button

## 🚀 How to Play

1. Open `index.html` in any modern web browser
2. Click "START GAME" to begin
3. Use the **Arrow Keys** to control the snake:
   - ↑ Up Arrow: Move Up
   - ↓ Down Arrow: Move Down
   - ← Left Arrow: Move Left
   - → Right Arrow: Move Right
4. Press **SPACE** to pause/resume the game
5. Press **R** to restart the game

## 🎯 Game Mechanics

### Basic Gameplay
- Eat the red food to grow longer and score points
- Avoid hitting the walls or the snake's own body
- Each food item increases your score by 10 points × current level
- Every 5 foods eaten increases your level and game speed

### Power-ups
- ⚡ **Speed Boost**: Temporarily increases snake speed
- 🐢 **Slow Down**: Temporarily decreases snake speed
- 💎 **Extra Points**: Instant bonus points
- 🛡️ **Shield**: Temporary protection from collisions

### Scoring
- **Food**: 10 points × level multiplier
- **Power-up (Extra Points)**: 50 points × level multiplier
- **Speed Boost Multiplier**: Double points while active

## 🛠️ Technical Details

### Technologies Used
- **HTML5 Canvas**: For rendering the game graphics
- **CSS3**: For styling and animations
- **JavaScript (ES6)**: For game logic and interactivity
- **localStorage**: For persistent high score storage

### Game Architecture
- Single HTML file with embedded CSS and JavaScript
- Object-oriented approach for game entities
- Efficient collision detection algorithms
- Particle system for visual effects
- Modular code structure for maintainability

## 🎨 UI/UX Features

- **Modern Gradient Design**: Animated background with smooth transitions
- **Responsive Layout**: Adapts to different screen sizes
- **Real-time Stats**: Current score, top score, level, and snake length
- **Modal Help System**: Accessible game instructions
- **Visual Feedback**: Particle effects for interactions
- **Game States**: Start, pause, resume, and game over states

## 📱 Controls

| Key | Action |
|-----|--------|
| ↑ Arrow | Move Up |
| ↓ Arrow | Move Down |
| ← Arrow | Move Left |
| → Arrow | Move Right |
| Space | Pause/Resume |
| R | Restart Game |
| ? Button | Show Help Modal |

## 🏆 Scoring System

- **Current Score**: Points earned in the current game
- **Top Score**: Highest score achieved (saved in browser)
- **Level**: Current difficulty level (increases every 5 foods)
- **Length**: Current snake length (grows when eating food)

## 🔧 Customization

The game can be easily customized by modifying these variables in the JavaScript code:

- `gridSize`: Size of each grid cell
- `tileCount`: Number of tiles on the game board
- `baseSpeed`: Initial game speed in milliseconds
- `POWER_UP_TYPES`: Available power-up types and effects

## 🌟 Advanced Features

- **Smooth Animations**: Canvas-based rendering with particle effects
- **Dynamic Difficulty**: Speed increases with each level
- **Power-up System**: Strategic gameplay elements
- **Collision Physics**: Accurate wall and self-collision detection
- **Visual Polish**: Gradient effects, rounded corners, and smooth transitions
- **Performance Optimized**: Efficient rendering and game loop

## 📝 Development Notes

This game is built as a single HTML file with no external dependencies, making it easy to deploy and share. The code is organized into logical sections:

1. **Game State Management**: Variables and initialization
2. **Rendering System**: Canvas drawing functions
3. **Game Logic**: Update loop and collision detection
4. **User Interface**: Event handlers and DOM manipulation
5. **Storage**: localStorage integration for high scores

## 🎯 Future Enhancements

Potential features that could be added:
- Sound effects and background music
- Multiple difficulty settings
- Leaderboard system
- Different snake skins
- Obstacles and enemies
- Mobile touch controls
- Multiplayer mode

## 📄 License

This project is open source and available under the MIT License.

## 🙏 Acknowledgments

- Inspired by the classic Snake game
- Built with modern web technologies
- Designed for educational and portfolio purposes
