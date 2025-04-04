#   Colorful Canvas with JavaScript

This guide introduces creating colorful graphics using the HTML5 Canvas and JavaScript.

##   Setup

1.  **HTML:**
    * Add a `<canvas id="draw" width="800" height="800"></canvas>` to your HTML.

2.  **JavaScript:**
    * Get the canvas: `const canvas = document.getElementById('#draw');`
    * Get the 2D context: `const ctx = canvas.getContext('2d');`

    ```javascript
    ctx.fillStyle = 'lightblue';
    ctx.fillRect(10, 10, 100, 50);

    ctx.strokeStyle = 'purple';
    ctx.strokeRect(120, 10, 100, 50);

    ctx.beginPath();
    ctx.fillStyle = 'orange';
    ctx.fill();
    ctx.closePath();
