***

# Be My Valentine

This is a simple web page that displays an animated "Be My Valentine" message with a pulsing heart particle effect in the background. The animation is created using HTML, CSS, and JavaScript.

## How It Works

* **`index.html`**: The main structure of the page. It contains a `<canvas>` element for the animated heart and a `<div>` for the "Be My Valentine" text.
* **`style.css`**: This file styles the page. It sets the background color, imports a custom font (`Tangerine`), and defines the `smoke` and `animate` animations.
    * The `smoke` animation makes the text appear with a fade-in effect.
    * The `animate` keyframe creates a smoky, blurring effect on the text.
* **`script.js`**: This is the core of the animation. It's responsible for drawing the pulsing heart effect on the canvas.
    * It uses a `requestAnimationFrame` loop to continuously update the positions of particles.
    * The particles are traced along a mathematical function that draws a heart shape.
    * The heart's shape and size can be adjusted to fit different devices.

## How to View

1.  Download or copy the three files (`index.html`, `style.css`, and `script.js`).
2.  Place all three files in the same folder.
3.  Open `index.html` in your web browser.

You will see the animated smoky text and the heart particle effect.

***
