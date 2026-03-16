# Organic Pattern Generator - Mobile Ready

An interactive, high-performance web application that generates organic, blob-like patterns using physics simulations and procedural generation. The project features real-time interactivity, generative audio, and advanced customization options for creative coding enthusiasts.

## Description

Organic Pattern Generator is a browser-based art tool that utilizes **D3.js** for force-directed simulations and **HTML5 Canvas** for efficient rendering. It creates fluid, multi-layered shapes that react to mouse or touch input. The application includes a built-in audio engine that produces "bubble" sounds mapped to the size and movement of the organic shapes, providing a multi-sensory experience.

## Features

* **Physics-Based Animation:** Uses `d3-force` for collision detection, gravity, and fluid movement.
* **Procedural Organic Shapes:** Generates unique shapes using quadratic curves and randomized deformation parameters.
* **Interactive Audio:** Integrated Web Audio API engine that triggers procedural sound effects based on user interaction.
* **Real-time Customization:** Extensive GUI (via `lil-gui`) to control blob count, size, gravity, "organicness", and layers.
* **Presets & Sharing:** Support for exporting/importing configuration JSON and downloading generated patterns as PNG.
* **Mobile Optimized:** Fully responsive design with specialized touch event handling and performance scaling.

## Technologies

* **HTML5 / CSS3:** Structure and responsive styling (Tailwind CSS).
* **JavaScript (ES6+):** Core logic and interactivity.
* **D3.js (v7):** Physics simulation and force-directed graph logic.
* **lil-gui:** Lightweight controller interface for real-time parameter tuning.
* **Web Audio API:** Synthesis of procedural audio cues.
* **HTML5 Canvas API:** High-performance rendering of organic paths.
