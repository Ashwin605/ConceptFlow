# DevForge Animator (Advanced Edition)

A premium, text-driven educational animation platform built for the DevForge Hackathon.

## 🌟 Advanced Features

- **Premium Glassmorphism UI**: Modern dark theme with blur effects, gradients, and smooth animations.
- **Text-to-Speech Narrator**: Automatically narrates the educational steps as the animation plays.
- **Code Visualization**: Displays the underlying Python/Pseudo-code for the generated animation.
- **Visual Polish**: Enhanced rendering with drop shadows, rounded corners, and 3D gradients.
- **Scene Breakdown**: Interactive step-by-step list that highlights the current action.

## 🚀 Core Capabilities

- **Natural Language Input**: Type "Animate bubble sort" and get a narrated scene.
- **Rule-Based Engine**: Supports 6 complex test cases.
- **Live Preview**: Canvas-based rendering with full playback controls.
- **Video Export**: Record and download `.webm` videos directly from the browser.

## 🛠 Tech Stack

- **Frontend**: HTML5, CSS3 (Variables, Flexbox), Vanilla JavaScript (ES6). No frameworks.
- **Backend**: Python 3, Flask.
- **Rendering**: HTML5 Canvas API.

## 📦 Installation

1. **Prerequisites**: Python 3.8+.

2. **Install Dependencies**:
   ```bash
   pip install flask flask-cors
   ```

3. **Start the Server**:
   ```bash
   python app.py
   ```
   The server will run at `http://localhost:5000`.

4. **Open the App**:
   Visit `http://localhost:5000` in your browser.

## 🧪 Test Cases (Try These!)

1.  **Bubble Sort**
    > "Animate bubble sort"
    *Narrated walkthrough of the sorting algorithm.*

2.  **Sine Wave**
    > "Plot a sine graph and move a dot along it"
    *Visualizes amplitude and phase with code display.*

3.  **Pythagoras Theorem**
    > "Show Pythagoras theorem"
    *Geometric proof animation.*

4.  **Vector Addition**
    > "Visualize vector addition with arrows"
    *Step-by-step vector math.*

5.  **Sphere Expansion**
    > "Animate a circle expanding into a sphere"
    *Demonstrates 3D shading effects.*

6.  **Matrix Multiplication**
    > "Visualize matrix multiplication step-by-step"
    *Complex multi-step animation with highlighting.*

## 🎥 Video Export

1.  Generate a scene.
2.  Click the **Export Video** button.
3.  The scene will play automatically from the start.
4.  Once finished, the `.webm` file will download automatically.

## 🔮 Future Work

- Integrate OpenAI API to generate JSON from *any* prompt.
- Implement server-side rendering using Puppeteer + ffmpeg.
- Add more object types (polygons, images).
