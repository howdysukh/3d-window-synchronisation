# Multiple Window 3D Scene using Three.js
# Demo 
<img width="1680" alt="Screenshot 2024-03-02 at 10 16 50 AM" src="https://github.com/howdysukh/3d-window-synchronisation/assets/147260152/7934e074-29e4-4a85-8e86-7e96ac9d66b0">

View It Live:- [From Here](https://howdysukh.github.io/3d-window-synchronisation/)

⚠️: Make sure you open the same site in two different windows
## Introduction
This project demonstrates a unique approach to creating and managing a 3D scene across multiple browser windows using Three.js and localStorage. It's designed for developers interested in advanced web graphics and window management techniques.

## Features
- 3D scene creation and rendering with Three.js.
- Synchronization of 3D scenes across multiple browser windows.
- Dynamic window management and state synchronization using localStorage.

## Installation
Clone the repository and open `index.html` in your browser to start exploring the 3D scene.

```
git clone https://github.com/bgstaal/multipleWindow3dScene
```
## Usage
The main application logic is contained within `main.js` and `WindowManager.js`. The 3D scene is rendered in `index.html`, which serves as the entry point of the application.

## Structure and Components
- `index.html`: Entry point that sets up the HTML structure and includes the Three.js library and the main script.
- `WindowManager.js`: Core class managing window creation, synchronization, and state management across multiple windows.
- `main.js`: Contains the logic for initializing the 3D scene, handling window events, and rendering the scene.
- `three.r124.min.js`: Minified version of the Three.js library used for 3D graphics rendering.

## Detailed Functionality
- `WindowManager.js` handles the lifecycle of multiple browser windows, including creation, synchronization, and removal. It uses localStorage to maintain state across windows.
- `main.js` initializes the 3D scene using Three.js, manages the window's resize events, and updates the scene based on window interactions.

## Contributing
Contributions to enhance or expand the project are welcome. Feel free to fork the repository, make changes, and submit pull requests.

## License and Copyright
This project is open-sourced under the MIT License.

Original repo URL: [https://github.com/bgstaal/multipleWindow3dScene](https://github.com/bgstaal/multipleWindow3dScene)
