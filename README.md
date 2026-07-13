# Interactive Pixel Reveal Canvas

An interactive HTML5 Canvas animation where an image dynamically reveals itself in pixelated blocks as the cursor moves across the screen. The project uses **GSAP** for smooth animations and **Tweakpane** for real-time customization.

## Features

* 🖱️ Mouse-following interactive reveal effect
* 🎯 Smooth cursor tracking with GSAP animations
* 🧩 Pixel/grid-based image rendering
* ⚪ Optional animated dot overlay
* 🌈 Change images in real time
* 📏 Adjustable grid (box) size
* 🌫️ Optional fade effect
* 🎛️ Live controls using Tweakpane
* 📱 Responsive full-screen canvas


## Project Structure

```text
Interactive-Pixel-Reveal/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Thej02/CherryCompile.git
```

### 2. Open the project

Open the folder in **Visual Studio Code**.

### 3. Install Live Server

If you don't already have it:

* Open Extensions (`Ctrl + Shift + X`)
* Search for **Live Server**
* Install it

### 4. Run the project

Right-click `index.html`

→ **Open with Live Server**

The project will open in your browser.


## Technologies Used

* HTML5
* CSS3
* JavaScript (ES6 Modules)
* HTML5 Canvas API
* GSAP (GreenSock Animation Platform)
* Tweakpane

## Controls

Move your mouse around the screen to interact with the image.

Using the Tweakpane panel, you can:

* Change the displayed image
* Adjust pixel grid size
* Enable or disable fade
* Toggle dot overlay
* Change dot color


## How It Works

1. A high-resolution image is loaded onto an HTML5 canvas.
2. The canvas is divided into small square tiles.
3. Each tile calculates its distance from the cursor.
4. Tiles nearer to the cursor remain fully visible.
5. Tiles farther away shrink, creating a dynamic reveal effect.
6. GSAP smoothly interpolates cursor movement for fluid animation.


## Future Improvements

* Upload custom images
* Touch-screen support
* Multiple animation styles
* Dynamic color palettes
* Particle effects
* Background music
* Export canvas as image
* Performance optimizations for mobile devices


## License

This project is available under the **MIT License**.


## Author

**Thejaswi Nayak**

If you enjoyed this project, consider giving it a ⭐ on GitHub!

