# 🌌 Pro-Logic Scientific Calculator

A high-performance, interactive scientific calculator designed for professionals who value both aesthetics and precision. This application solves the common "visibility issue" in dark-themed tools by using a high-contrast safety color palette and a clean, monospaced interface.

## 🔗 Live Demo
[animated-pro-scientific-calculator.netlify.app]

## ✨ Key Features

* **High-Contrast UI:** Pure white digits and safety-orange operators for 100% instant readability.
* **Scientific Suite:** Full support for Trigonometry (sin, cos, tan), Logarithms (log, ln), Square Roots, Exponents, and Factorials.
* **Animated "Plexus" Background:** A custom HTML5 Canvas engine that renders moving, interconnected particles behind a frosted glass interface.
* **Tactile Response:** Smooth CSS animations and button scaling that provide immediate visual feedback on every interaction.
* **Keyboard Synergy:** Fully mapped to your physical keyboard (Enter, Backspace, Escape, and Operators).

## 🧠 Technical Architecture



### The Parsing Logic
Instead of a simple input-output model, this app uses a **String-to-Math Translator**. It cleans user-friendly symbols (like `×` and `÷`) and converts them into JavaScript-executable logic, allowing for complex order of operations without calculation errors.

### Performance Design
* **Glassmorphism:** Uses `backdrop-filter: blur()` to separate the calculator layer from the background animation.
* **Vector Scaling:** Built with CSS Grid to ensure it remains pixel-perfect on mobile, tablet, and desktop screens.

## 🛠️ Built With
* **Vanilla JavaScript (ES6+)** - Core logic and calculation engine.
* **HTML5 Canvas** - Dynamic background rendering.
* **CSS3** - Custom Grid layout and Glassmorphic effects.
* **Google Fonts** - Roboto Mono for technical clarity.

## 📝 License
Distributed under the MIT License.
