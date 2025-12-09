# Scientific-Calculator
A powerful, single file scientific computing environment featuring a numerical calculus engine, graphing calculator, matrix operations, and a programmer's base converterwrapped in a modern glassmorphism UI.
# 🧮 Quantum Math Workstation V2 Pro

![Version](https://img.shields.io/badge/version-2.0-blue) ![Tech](https://img.shields.io/badge/built%20with-Vanilla%20JS-yellow) ![License](https://img.shields.io/badge/license-MIT-green)

**Quantum Math Workstation** is an advanced, all-in-one mathematical suite that runs entirely in the browser. Built with zero external dependencies, it combines a scientific calculator with numerical analysis tools, data visualization, and linear algebra capabilities.



[Image of scientific calculator interface]


## ✨ Key Features

### 1. 🔬 Advanced Scientific Calculator
- **Full Scientific Suite:** Trigonometry (DEG/RAD), Logarithms, Roots, and Powers.
- **Calculus Engine:** Built-in numerical analysis algorithms.
  - **Derivative:** `deriv(x^2, 3)` calculates the slope at a specific point using the Finite Difference method.
  - **Integration:** `integ(x^2, 0, 5)` calculates the area under the curve using Simpson's Rule.
- **Smart Parsing:** Handles implicit multiplication (e.g., `2x` becomes `2*x`) and nested expressions.

### 2. 📈 Interactive Graphing Engine
- Plots custom functions of $x$ (e.g., `sin(x) * x`) in real-time.
- Built on HTML5 Canvas for high-performance rendering.
- Auto-scaling grid system.

### 3. 💻 Programmer's Base Converter
- **4-Way Sync:** Instantly converts between Decimal, Hexadecimal, Octal, and Binary.
- Type in any field to update all others simultaneously.

### 4. 🧮 Matrix Operations
- Supports 2x2 and 3x3 matrices.
- **Operations:** Addition, Multiplication, Determinant, and Inverse calculations.
- Error handling for dimension mismatches and singular matrices.

### 5. 🎨 Modern UI/UX
- **Glassmorphism Design:** Translucent panels with background blur (`backdrop-filter`).
- **Responsive Layout:** CSS Grid architecture that adapts from desktop to mobile.
- **Session History:** Logs all calculations and results for quick reference.

## 🚀 Quick Start

No installation or build process is required. This is a standalone solution.
Run it Simply double-click index.html to open it in any modern web browser.
1. **Clone the repo**
   ```bash
   git clone [https://github.com/yourusername/quantum-math-workstation.git](https://github.com/yourusername/quantum-math-workstation.git)
