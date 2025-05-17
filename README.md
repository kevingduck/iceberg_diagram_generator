# Icebergify! 🌊❄️

A simple web app to generate "iceberg" diagrams for any topic using Google's Gemini AI.

<img width="794" alt="image" src="https://github.com/user-attachments/assets/c719b276-a14c-4634-a773-a41db9c071d7" />

## Features

*   Enter any topic to generate an iceberg diagram.
*   Displays content in tiered levels, from common knowledge to obscure facts.
*   Items within each tier are displayed as short, side-by-side keywords/phrases.
*   Responsive design for desktop and mobile.

## How to Use

1.  **Get a Google Gemini API Key:**
    *   You'll need an API key from Google AI Studio: [https://aistudio.google.com/app/apikey](https://aistudio.google.com/app/apikey)
2.  **Open the App:**
    *   Download `index.html` (or the main HTML file) and the `iceberg.png` image.
    *   Place `iceberg.png` in the same directory as the HTML file.
    *   Open the HTML file in your web browser.
    *   Alternatively, if hosted (e.g., on GitHub Pages), simply visit the URL.
3.  **Enter Your API Key:**
    *   Paste your Google Gemini API Key into the designated input field on the page.
4.  **Enter a Topic:**
    *   Type the topic you want an iceberg for (e.g., "Coffee", "Super Mario", "Quantum Physics").
5.  **Generate:**
    *   Click the "Generate Iceberg" button.
    *   Wait a few moments for the AI to generate and display the iceberg.

## Customization (Optional)

*   **Iceberg Image:** You can replace `iceberg.png` with your own image. If you do, you may need to adjust the CSS positioning of the text overlay boxes (`.tier-X` classes in the `<style>` section of the HTML) to match your new image.
*   **Number of Items/Tiers:** The number of tiers and items per tier can be adjusted within the `getIcebergPrompt` function in the JavaScript code if you wish to modify the defaults.

## Running Locally / Development

*   No special build steps are required for this single HTML file app.
*   Just ensure the `iceberg.png` image is in the same directory or update the path in the HTML.

## Important Note on API Keys

This application requires you to provide your own Google Gemini API key directly in the browser. Your API key is used only for making requests to the Gemini API from your browser session and is not stored by this application. Be mindful of API usage costs associated with your Google Cloud account.

---

Enjoy exploring the depths of your favorite topics!


