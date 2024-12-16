# AR Animation with Play/Pause Controls
This project hosts an AR-enabled 3D animation of louvers using `<model-viewer>` and GitHub Pages. The animation includes interactive play/pause controls and is accessible via browsers and Android devices.
## Features
- Display of a `.glb` 3D model using `<model-viewer>`.
- Interactive play/pause controls for the animation.
- AR support for compatible Android devices.
## Access the Animation
To view the animation or AR experience, visit the following links:
### Web Viewer (with Play/Pause Buttons)
- **[3D Animation Viewer](https://iren6182.github.io/AR/)**: Opens the 3D model with play/pause functionality in a browser.
### AR Viewer (Android Devices)
- **[AR Mode](https://iren6182.github.io/AR/)**: Opens the AR viewer to view the model in augmented reality.
## File Structure
The repository is organized as follows:
AR/
├── assets/
│   └── louvers.glb           # The 3D model file
├── js/
│   └── model-viewer.min.js   # Local copy of the Model Viewer library (optional)
├── index.html                # Main HTML file for the project
└── README.md                 # Documentation file
## Usage
1. Open the `index.html` file via GitHub Pages or locally using a web server.
2. For AR functionality, use an Android device with ARCore support.
## Dependencies
- [Model Viewer](https://modelviewer.dev): A web component library for rendering 3D models in the browser with AR capabilities.
## Development
To contribute:
1. Clone this repository:
  ```bash
  git clone https://github.com/iren6182/AR.git
2. Open the project in a code editor like Visual Studio Code.
3. Run a local web server to test the application:
python3 -m http.server

4. Open http://localhost:8000 in your browser to view the project.
