# SQUARE-ASTEROIDS
Square Asteroids is a retro arcade game built with HTML5 Canvas and Web Audio API. Destroy square asteroids while avoiding collisions. Features neon aesthetics, progressive difficulty levels, responsive mobile controls, and persistent score tracking. Play with arrow keys and spacebar on desktop or touch buttons on mobile. No dependencies required.
# Square Asteroids

A retro arcade game with neon aesthetics, inspired by the classic Asteroids, reimagined with square-shaped obstacles and responsive controls for both desktop and mobile devices.

## Features

🎮 **Classic Arcade Gameplay**
- Destroy square asteroids and avoid collisions
- Progressive difficulty with increasing levels
- Score multiplier system (100 points per asteroid)
- Lives system with ship invulnerability periods

🎨 **Visual Design**
- Neon green (#39ff14) and neon red (#ff073a) color scheme
- CRT scanline effects for authentic retro feel
- Particle explosion effects for destroyed objects
- Smooth vector-based graphics with 60 FPS performance

🔊 **Audio System**
- Synthesized sound effects without external audio files
- Procedural audio engine using Web Audio API
- Distinct sounds for: shooting, explosions, and thrust

📱 **Cross-Platform Controls**
- **Desktop**: Arrow keys to move, Space to shoot
- **Mobile**: Touch controls with on-screen buttons
- Responsive canvas that adapts to screen size
- Touch-optimized UI for tablets and phones

📊 **Game Statistics**
- Persistent high score tracking via localStorage
- Game session history with timestamps
- Level progression tracking
- Clearable game records

## Gameplay

1. **Start Screen**: Choose to start a new game or view statistics
2. **Game Loop**: 
   - Navigate with arrow keys (or touch buttons)
   - Shoot asteroids with spacebar (or touch button)
   - Avoid collisions with asteroids
   - Complete level by destroying all asteroids
3. **Level Progression**: Each level introduces more asteroids with increased speed
4. **Game Over**: Track your score and compete against your high score

## Technical Stack

- **HTML5 Canvas** - Core rendering engine
- **Vanilla JavaScript** - Game logic and physics
- **Web Audio API** - Synthesized sound effects
- **CSS3** - Responsive UI and animations
- **localStorage** - Persistent game data

## How to Play

1. Open `index.html` in a modern web browser
2. Click "Start Game" to begin
3. Use Arrow Keys (↑↓←→) and Space to play
4. Try to beat your high score!

## Browser Compatibility

- Chrome/Chromium 60+
- Firefox 55+
- Safari 11+
- Edge 79+
- Mobile browsers (iOS Safari, Chrome Mobile)

## Credits

Created and powered by **Rajesh Ranjan**


## Game Stats

- **File Size**: Single HTML file (~50KB)
- **Performance**: 60 FPS on most devices
- **Dependencies**: None (vanilla JavaScript)
- **Accessibility**: Keyboard and touch-friendly UI

