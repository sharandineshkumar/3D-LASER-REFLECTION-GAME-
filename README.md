n
# 🔮 3D Laser Reflection Puzzle Game
An immersive, interactive 3D puzzle game built with React and Three.js where players strategically position and rotate mirrors to guide laser beams to target receivers.
![React](https://img.shields.io/badge/React-18.2.0-61DAFB?logo=react&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-0.158.0-000000?logo=three.js&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-4.4.9-646CFF?logo=vite&logoColor=white)
## 🎮 Live Demo
👉 [Play Now](https://sharandineshkumar.github.io/3D-LASER-REFLECTION-GAME-/)
## ✨ Features
- **🪞 Mirror Manipulation** – Select, rotate, and move mirrors in 3D space to redirect laser beams
- **🎯 Progressive Levels** – Multiple challenging levels with increasing difficulty
- **⌨️ Intuitive Controls** – Keyboard support for seamless gameplay
  - `Arrow Keys` – Move mirrors (Left/Right/Forward/Backward)
  - `W/S` – Move mirrors Up/Down
  - `Q/E` – Rotate mirrors
- **🖱️ Orbit Controls** – Pan, zoom, and rotate the camera for the perfect viewing angle
- **⏱️ Game Stats** – Track your moves and time for each level
- **🌟 Stunning Visuals** – Beautiful 3D graphics with dynamic lighting, starfield background, and atmospheric fog
- **📱 Responsive Design** – Modern, clean UI that adapts to different screen sizes
## 🛠️ Tech Stack
| Technology | Purpose |
|------------|---------|
| **React** | UI Framework |
| **Three.js** | 3D Graphics Engine |
| **@react-three/fiber** | React renderer for Three.js |
| **@react-three/drei** | Useful helpers for react-three-fiber |
| **Vite** | Build Tool & Dev Server |
## 🚀 Getting Started
### Prerequisites
- Node.js (v16 or higher)
- npm or yarn
### Installation
```bash
# Clone the repository
git clone [https://github.com/sharandineshkumar/3D-LASER-REFLECTION-GAME-.git](https://github.com/sharandineshkumar/3D-LASER-REFLECTION-GAME-.git)
# Navigate to project directory
cd 3D-LASER-REFLECTION-GAME-
# Install dependencies
npm install
# Start development server
npm run dev
Build for Production
bash
npm run build
🎯 How to Play
Select a Mirror – Click on any mirror to select it (it will glow when selected)
Position the Mirror – Use arrow keys to move the mirror in the X-Z plane
Rotate the Mirror – Press Q or E to rotate and adjust the reflection angle
Guide the Laser – Direct the laser beam from the emitter to the receiver
Complete the Level – When the laser hits the receiver, you win! 🎉
📁 Project Structure
src/
├── components/
│   ├── Emitter.jsx      # Laser emitter component
│   ├── GameFloor.jsx    # 3D floor/platform
│   ├── GameScene.jsx    # Main 3D scene manager
│   ├── GameUI.jsx       # User interface overlay
│   ├── LaserBeam.jsx    # Laser beam with reflections
│   ├── Mirror.jsx       # Interactive mirror component
│   ├── Obstacle.jsx     # Obstacle blocks
│   ├── Receiver.jsx     # Target receiver
│   └── WinOverlay.jsx   # Victory screen
├── data/
│   └── levels.js        # Level configurations
├── App.jsx              # Main application
├── main.jsx             # Entry point
└── styles.css           # Global styles
🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check issues page.

📄 License
This project is open source and available under the 
MIT License
.

👨‍💻 Author
SharanDineshKumar
