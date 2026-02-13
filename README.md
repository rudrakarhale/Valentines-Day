# Valentines-Day
A Valentine's Day proposal for your crush ;)

A cute, interactive, and modern Valentine's Day proposal webpage. Built with HTML, CSS, and vanilla JavaScript, this project features smooth animations, a floating background, and a playfully evasive "No" button that makes it impossible to reject the question!

## Features

* **Foolproof "No" Button:** The "No" button uses a deterministic 5-step path (based on screen percentages) to smoothly dodge the user's cursor or touch, ensuring it never goes off-screen and can't be clicked.
* **Floating Background:** A continuous, lightweight CSS/JS animation of floating hearts in the background.
* **Celebration Screen:** Clicking the "Yes" button triggers a fullscreen celebration with animated confetti and a sweet message.
* **Modern UI:** Soft pink/red color theme, glassmorphism card effects, and glowing hover states.
* **Fully Responsive:** Works perfectly on both desktop browsers and mobile touch screens.

## How to Run

This project is completely frontend-based with zero dependencies. 

1. Clone or download this repository.
2. Open the `index.html` file in any modern web browser (Chrome, Safari, Edge, Firefox).
3. Try to click "No"!

## Customization

If you want to reuse or customize this code, you can easily change the following in the `index.html` file:

* **The Name:** Search for `Rudra` in the HTML body and replace it with your own name.
* **The Emojis:** In the JavaScript, look for the `createBackgroundHeart()` and `createConfetti()` functions to swap out the arrays of emojis (e.g., `['red heart', 'pink heart', 'dual pink heart', 'flower']`).
* **The Jump Path:** In the `dodgeCursor()` function, you can modify the `paths` array to change exactly where the "No" button jumps.

## Tech Stack

* **HTML5** * **CSS3** (Keyframe animations, Flexbox, UI styling)
* **JavaScript** (Vanilla JS for DOM manipulation, event listeners, and logic)


Created with love for Valentine's Day by Rudra.
