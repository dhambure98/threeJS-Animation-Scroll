# Three.js Animated Scrolling Bee Model  
This project showcases a 3D animated bee model using **Three.js**, **GLTFLoader**, and **GSAP** for smooth scrolling animations. The model moves and rotates as the user scrolls through different sections of the webpage.  

---

## Demo  
The animated bee model scrolls and rotates as you navigate through the sections of the page, creating a dynamic 3D experience.  

![gif](https://github.com/user-attachments/assets/141edd6a-17e6-40cc-bf36-e59d6e376025)

---

## Features  
- 3D model loading using **GLTFLoader**.  
- Smooth animations with **GSAP**.  
- Responsive resizing with **Three.js**.  
- Dynamic model movement and rotation based on scroll position.  

---

## Technologies Used  
- [Three.js](https://threejs.org/) for 3D rendering.  
- [GLTFLoader](https://threejs.org/docs/#examples/en/loaders/GLTFLoader) for loading the `.glb` model.  
- [GSAP](https://greensock.com/gsap/) for smooth animations.  

---

## Prerequisites  
Ensure you have the following installed:  
- A modern web browser (Chrome, Firefox, or Edge).  
- A local server (e.g., **Live Server** extension for VSCode or **http-server** for Node.js).  

---

## Installation  
1. Clone this repository:  
    ```bash
    git clone https://github.com/your-username/threejs-animated-bee.git
    cd threejs-animated-bee
    ```

2. Ensure the project structure is as follows:
    ```
    threejs-animated-bee/
    ├── index.html
    ├── app.js
    ├── demon_bee_full_texture.glb
    └── images/
    ```

3. Install a local server:  
    ```bash
    npm install -g http-server
    ```

4. Run the local server:  
    ```bash
    http-server -p 8080
    ```
    Then, open your browser and navigate to:  
    ```
    http://localhost:8080
    ```

---

## Usage  
- Scroll down the page to see the bee model move and rotate dynamically.  
- Resize the browser window to see the model adapt responsively.  

---

## Troubleshooting  
1. **Model Not Displaying**  
    - Ensure the file path to `demon_bee_full_texture.glb` is correct.  
    - Confirm that the local server is running and accessible.  
    - Clear browser cache and refresh the page.  

2. **CORS Policy Errors**  
    - Ensure you are using a local server (e.g., **http-server** or **Live Server**).  
    - Directly opening the `index.html` file from the filesystem won't work due to CORS policies.  

---

## Credits  
- Model: `demon_bee_full_texture.glb`  
- Animation: **GSAP**  
- 3D Rendering: **Three.js**  

---

## License  
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.  

---

## Contact  
For questions or collaboration:  
- **Name**: Akila Dhambure
