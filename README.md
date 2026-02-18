# 🌀 Mandelbulb Fractal Explorer

A stunning 3D fractal visualization of the Mandelbulb implemented in Unity using advanced raymarching techniques.

![Mandelbulb Banner](Images/banner.png)
*Add your beautiful Mandelbulb renders here!*

## ✨ What is the Mandelbulb?

The Mandelbulb is a three-dimensional fractal, constructed by extending the Mandelbrot set into 3D space. First discovered in 2009, it creates breathtaking organic structures with infinite detail at every scale. This project brings this mathematical marvel to life through real-time rendering.

## 🎮 Features

- **Real-time Raymarching** - Smooth, high-quality rendering of the fractal
- **Interactive Exploration** - Navigate through the infinite complexity of the Mandelbulb
- **Custom Shaders** - Optimized ShaderLab implementation for Unity
- **Dynamic Parameters** - Adjust fractal parameters in real-time
- **Beautiful Visuals** - Experience the mesmerizing beauty of 3D fractals

## 📸 Gallery

<!-- Add your screenshots here -->
*Coming soon - Add your amazing renders!*

## 🚀 Getting Started

### Prerequisites

- Unity 2020.3 LTS or later
- Basic understanding of Unity Editor

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Anton-Denis/Mandelbulb.git
   ```

2. Open the project in Unity Hub

3. Open the main scene in the `Assets/Scenes` folder

4. Press Play and explore!

## 🎯 Usage

1. **Navigate** - Use WASD keys to move through the fractal space
2. **Look Around** - Move your mouse to change the camera direction
3. **Adjust Parameters** - Use the inspector to modify fractal properties:
   - Power - Changes the complexity of the fractal
   - Iterations - Affects the level of detail
   - Color scheme - Customize the visual appearance

## 🔬 Technical Details

### Raymarching Implementation

This project uses **sphere tracing**, a raymarching technique perfect for rendering implicit surfaces like fractals. Instead of traditional polygon-based rendering, rays are cast from the camera and "march" through the scene, calculating the distance to the fractal surface at each step.

### The Mandelbulb Formula

The Mandelbulb is calculated using spherical coordinates with the power-8 formula:
- Each point is tested through iterative calculations
- Points are colored based on escape time or orbit trap techniques
- Distance estimation ensures efficient rendering

### Performance Optimization

- Efficient distance estimation functions
- Adaptive step sizes for optimal performance
- Minimal shader instructions per ray

## 🛠️ Built With

- **Unity** - Game engine and rendering framework
- **ShaderLab** - Custom shader implementation
- **HLSL** - High-Level Shading Language for GPU computation

## 🎨 Customization

Feel free to experiment with:
- Different fractal formulas (Mandelbox, Julia sets, etc.)
- Lighting and color schemes
- Post-processing effects
- Animation parameters

## 📚 Resources

Learn more about fractals and raymarching:
- [Raymarching Distance Fields](http://iquilezles.org/articles/raymarchingdf/)
- [The Mandelbulb](https://www.skytopia.com/project/fractal/mandelbulb.html)
- [Distance Functions by Inigo Quilez](https://iquilezles.org/articles/distfunctions/)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📝 License

This project is open source and available for educational and personal use.

## 👤 Author

**Anton-Denis**
- GitHub: [@Anton-Denis](https://github.com/Anton-Denis)

## ⭐ Show Your Support

If you find this project interesting, please consider giving it a star! It helps others discover the beauty of fractals.

---

*Made with ❤️ and mathematics*