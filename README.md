# Live Code Editor

A simple in-browser code editor that lets you write and preview HTML, CSS, and JavaScript code in real-time.

## Features

- Three separate textareas for HTML, CSS, and JavaScript input
- Live preview of the combined code output in an iframe
- Syntax icons using Font Awesome for each code section
- Dark-themed UI with responsive layout using Flexbox

## How It Works

- As you type in any of the HTML, CSS, or JS editors, the preview updates instantly.
- The iframe’s content is set by combining the HTML and CSS code, and the JavaScript is executed inside the iframe.
- The `run()` function handles updating the iframe’s content on every key press.

## How to Use

1. Open the `index.html` file in any modern browser.
2. Type your HTML, CSS, and JavaScript code in the respective editors on the left.
3. See the live output instantly on the right panel.
4. Modify code freely to test and experiment with web development.

## Technologies Used

- HTML5
- CSS3 (with Flexbox layout)
- JavaScript (DOM manipulation and iframe contentWindow)
- Font Awesome (for icons)

## Notes

- The JavaScript entered is executed inside the iframe, so errors in JS code might stop script execution.
- No external libraries except Font Awesome are used.
- This is a simple educational tool to experiment with frontend code quickly.

---

Created as a live playground to learn and test HTML, CSS, and JavaScript interactively.
This code editor gives you live output
