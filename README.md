# Awesome 3D Space Experience

Explore the cosmos with this immersive 3D space experience built using HTML, CSS, and Three.js. This project creates an engaging visual representation of space, featuring dynamic particles and a spaceship that responds to user interactions.

## Features

- **3D Space Simulation**: A visually stunning simulation of space with thousands of particles.
- **Interactive Spaceship**: A spaceship model that moves and rotates based on mouse movement.
- **Dynamic Text**: Informative and engaging text that changes periodically to enhance the experience.
- **Zoom Control**: Users can zoom in and out to explore space more closely or view it from afar.

## Technologies Used

- HTML
- CSS
- JavaScript
- [Three.js](https://threejs.org/)

## Setup Instructions

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone (https://github.com/cherry-1729-9090/3DWebsite.git)
   ```

2. **Navigate to the project directory**:
   ```bash
   cd awesome-3d-space-experience
   ```

3. **Open `index.html` in your web browser**.

## Code Explanation

### HTML

The HTML file sets up the structure of the webpage, including the canvas for rendering the 3D scene and a `div` for displaying text information.

### CSS

The CSS file ensures that the canvas takes up the entire screen and styles the text to be visually appealing.

### JavaScript

The JavaScript code is responsible for creating and animating the 3D scene using Three.js. It includes:

- **Scene Initialization**: Sets up the Three.js scene, camera, and renderer.
- **Particle Creation**: Generates thousands of particles with random positions and colors.
- **Spaceship Model**: Creates a simple spaceship model using Three.js geometry and material.
- **Event Listeners**: Handles mouse movement and scroll events to interact with the scene.
- **Animation Loop**: Continuously updates the scene, including particle and spaceship movements, as well as camera zoom.

## Screenshots

Include screenshots of your application here to showcase different features and the overall visual experience.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
