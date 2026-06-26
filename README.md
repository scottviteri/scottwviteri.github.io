# Scott Viteri - Personal Website & ML Visualization Platform

🚀 **Live at:** [scottwviteri.github.io](https://scottwviteri.github.io)

## Overview

An interactive portfolio website featuring cutting-edge machine learning visualizations and algorithmic art. This site combines research interests in reinforcement learning and transformer architectures with creative coding and interactive educational tools.

## 🎨 Features

### Interactive ML Visualizations

1. **Transformer Attention Visualization**
   - Multi-head attention mechanism visualization
   - Interactive token processing
   - Real-time attention weight heatmaps
   - Support for different transformer architectures (BERT-style, simple attention)

2. **Reinforcement Learning Playground**
   - Train agents in real-time using various RL algorithms
   - Algorithms: Q-Learning, SARSA, DQN, Policy Gradient
   - Environments: Grid World, Cliff Walking, Maze Navigation
   - Live training metrics and Q-table visualization

3. **Neural Network Builder**
   - Build custom neural network architectures
   - Interactive backpropagation visualization
   - Real-time training on various datasets
   - Activation function comparisons
   - Layer-wise activation monitoring

4. **Optimization Landscapes**
   - 3D visualization of loss surfaces
   - Compare optimization algorithms (SGD, Momentum, Adam, RMSprop)
   - Interactive rotation and zoom
   - Real-time optimization path tracking

5. **Algorithmic Art Lab**
   - Flow fields with Perlin noise
   - Particle systems with physics
   - Fractal tree generation
   - Neural network pattern visualization
   - Wave interference patterns

6. **4D Rotation Playground**
   - Interactive tesseract visualization for building 4D rotation intuition
   - Six diagnostic coordinate-plane projections + depth-based coloring
   - K₄ graph and text command control for choosing rotation planes (including Clifford pairs)
   - Leveled match-the-target game with progressive removal of scaffolding
   - Full provenance not applicable here — pure geometric playground

## 🛠️ Technologies Used

- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **Visualization Libraries:** 
  - Canvas API for custom graphics
  - p5.js for creative coding
  - Custom 3D projection mathematics
- **Design:** 
  - Responsive design for all devices
  - GPU-accelerated animations
  - Modern gradient aesthetics
  - Dark theme optimized for long viewing sessions

## 📁 Project Structure

```
scottwviteri.github.io/
├── index.html                 # Main landing page with neural network background
├── transformer-viz.html       # Transformer attention visualization
├── rl-playground.html        # Reinforcement learning environment
├── neural-network.html       # Neural network builder and trainer
├── optimization.html         # 3D optimization landscape viewer
├── algorithmic-art.html      # Generative art laboratory
├── CNAME                     # Custom domain configuration
└── README.md                 # Project documentation
```

## 🚀 Getting Started

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/scottviteri/scottwviteri.github.io.git
cd scottwviteri.github.io
```

2. Start a local server (Python):
```bash
python -m http.server 8000
# or for Python 2
python -m SimpleHTTPServer 8000
```

3. Open your browser and navigate to:
```
http://localhost:8000
```

### Deployment

The site is automatically deployed via GitHub Pages. Any push to the `main` branch will trigger a deployment.

## 🎯 Key Features by Page

### Home Page (`index.html`)
- Animated neural network background with mouse interaction
- Smooth scroll navigation
- Project showcase cards
- Research timeline
- Responsive design

### Transformer Visualization (`transformer-viz.html`)
- Input text tokenization
- Attention matrix computation
- Multi-head attention support
- Token embedding visualization
- Interactive heatmaps

### RL Playground (`rl-playground.html`)
- Real-time agent training
- Multiple RL algorithms
- Customizable hyperparameters
- Reward history tracking
- Success rate metrics

### Neural Network Builder (`neural-network.html`)
- Drag-and-drop layer construction
- Multiple activation functions
- Dataset selection (XOR, Circles, Spiral)
- Loss curve visualization
- Weight visualization

### Optimization Landscapes (`optimization.html`)
- Famous optimization test functions (Rosenbrock, Himmelblau, etc.)
- 3D surface rendering
- Multiple optimizer comparison
- Interactive camera controls
- Convergence metrics

### Algorithmic Art Lab (`algorithmic-art.html`)
- Multiple generative art modes
- Real-time parameter adjustment
- Preset configurations
- Export artwork functionality
- Performance monitoring

## 🎨 Design Philosophy

The website follows these design principles:

1. **Educational First**: Every visualization is designed to teach ML concepts intuitively
2. **Performance**: Optimized rendering with requestAnimationFrame and efficient algorithms
3. **Accessibility**: Clear contrast ratios, readable fonts, keyboard navigation support
4. **Interactivity**: Every visualization responds to user input for exploration
5. **Aesthetics**: Modern, clean design with consistent color schemes

## 📈 Performance Optimizations

- Canvas-based rendering for smooth 60fps animations
- Efficient particle systems with object pooling
- Throttled event handlers
- Progressive enhancement approach
- Lazy loading for heavy visualizations

## 🔮 Future Enhancements

- [ ] Add WebGL rendering for more complex 3D visualizations
- [ ] Implement save/load functionality for neural network configurations
- [ ] Add more RL environments (CartPole, MountainCar)
- [ ] Create shareable links for specific configurations
- [ ] Add tutorial mode for each visualization
- [ ] Implement collaborative features for shared learning
- [ ] Mobile app versions of key visualizations

## 🤝 Contributing

Interested in contributing? Feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the MIT License.

## 👤 Author

**Scott Viteri**
- PhD Student at Stanford University
- Research Focus: Reinforcement Learning & Transformer Architectures
- GitHub: [@scottviteri](https://github.com/scottviteri)
- Email: scottviteri@stanford.edu

## 🙏 Acknowledgments

- Stanford AI Lab for research inspiration
- The open-source ML community for algorithm implementations
- p5.js community for creative coding resources

---

⭐ Star this repository if you find it helpful!

🔬 Built with passion for making ML concepts accessible and beautiful
