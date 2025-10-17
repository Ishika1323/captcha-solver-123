# Simple Captcha Solver UI

This project provides a basic, single-file web application that serves as a user interface for solving image-based captchas. It's designed to be lightweight, responsive, and easy to deploy.

## Features

*   **Image Loading:** Dynamically loads captcha images.
    *   Defaults to a local `sample.png` if no specific URL is provided.
    *   Can load images from an external URL via a query parameter (`?url=https://example.com/captcha.png`) or through a user input field.
*   **User Input:** Provides an input field for the user to type in their captcha solution.
*   **Verification (Conceptual):** Includes a basic client-side verification mechanism to simulate checking the user's answer against a pre-defined solution (for the default `sample.png`).
*   **Responsive Design:** Built with Tailwind CSS for a modern and mobile-friendly user experience.
*   **Single File:** All code (HTML, CSS via CDN, JavaScript) is contained within a single `index.html` file for simplicity.

## How to Use

1.  **Download:** Save `index.html`, `README.md`, and `LICENSE` files, along with `sample.png`, into a single directory.
2.  **Open in Browser:** Simply open `index.html` in your web browser.

### Loading Custom Captchas

*   **Via URL Parameter:** You can provide a captcha image URL directly in the browser's address bar. For example:
    `index.html?url=https://your-domain.com/path/to/your/captcha.png`
*   **Via Input Field:** Paste an image URL into the "Image URL" input field and click "Load Image".

### Solving the Captcha

1.  Observe the captcha image displayed.
2.  Type your solution into the "Enter Captcha" input field.
3.  Click the "Check Answer" button or press `Enter`.
4.  The application will indicate whether your answer is "Correct!" or "Incorrect!".

## Development

This application is built using:
*   HTML5
*   Tailwind CSS (via CDN)
*   Vanilla JavaScript

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
