# 🌌 Fluid 3D Pipes Screensaver - Three.js

A mesmerizing 3D visualization of fluid pipes that gracefully navigate through a volumetric grid. Built with Three.js, this screensaver-style animation features dynamic color transitions, smooth camera movements, and optimized performance for seamless rendering.

![Screenshot of 3D Pipes Visualization](https://media.licdn.com/dms/image/v2/D4D05AQGcu7OGYC3lyw/feedshare-thumbnail_720_1280/B4DZTqYw0dG8A8-/0/1739099148870?e=1743494400&v=beta&t=Wb3yFcXJK-U0sqAd9f9rl8o_KgiMzoAEjyZ3AQwU8jw)

## 🚀 Live Demo
[Experience the Fluid Pipes](https://2105789.github.io/screensavers/pipe.html)  
*(Hosted on GitHub Pages or your preferred platform)*

## ✨ Features
- **Procedural Pipe Generation**: 20 pipes dynamically navigate through 3D space
- **Smooth Catmull-Rom Curves**: Fluid pipe movements with natural interpolation
- **Dynamic Color Cycling**: HSV-based color transitions with adjustable speed
- **Cinematic Camera**: Orbital camera with automatic rotation
- **Performance Optimized**: Geometry recycling & shader-based effects
- **Responsive Design**: Adapts to any screen size
- **FPS Counter**: Real-time performance monitoring

## 🛠️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/2105789/screensavers.git
   ```
2. Navigate to project directory:
   ```bash
   cd screensavers
   ```
3. Open in browser:
   ```bash
   open pipe.html  # Or double-click the file
   ```

## ⚙️ Usage
The animation runs automatically upon loading. For best experience:
- Fullscreen your browser (F11 key)
- Ensure hardware acceleration is enabled
- Use a modern browser (Chrome/Firefox/Edge recommended)

## 🎨 Customization
Adjust these constants in the code for different effects:
```javascript
const NUM_PIPES = 20;             // Number of concurrent pipes
const GRID_SIZE = [25, 25, 25];   // 3D grid dimensions
const COLOR_CYCLE_SPEED = 0.00005;// Hue transition speed
const TUBE_RADIUS = 12.5;         // Pipe thickness
const CAMERA_DISTANCE = 1200;     // Viewing distance
```

## 🔍 Technical Highlights
- **Three.js** (r128) powered WebGL rendering
- **Shader Materials** for smooth alpha transitions
- **Geometry Recycling** for memory efficiency
- **Procedural Pathfinding** with collision avoidance
- **Responsive Design** with automatic viewport adjustment

## 📚 Documentation
### Key Components
- `Pipe Class`: Handles pathfinding, geometry generation, and color updates
- **Catmull-Rom Splines**: Create smooth pipe curves
- **HSL Color Space**: For natural color transitions
- **Performance Optimizations**:
  - Geometry disposal for memory management
  - Fixed maximum points per pipe
  - Shader-based transparency effects

## 🌟 Contributing
Contributions welcome! Please follow these steps:
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.

## 🙏 Acknowledgments
- Three.js library team
- Inspired by classic screensaver designs
- WebGL community for continuous innovation

---

🛠 **Built with Three.js Magic** | 🌐 *Optimized for Modern Browsers* | 💡 *Perfect for Creative Coding Inspiration*
