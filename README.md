# edit
AI Code Studio For Quick Single HTML
# AI Code Studio (Gemini Powered)

**AI Code Studio** is a lightweight, single-file HTML Integrated Development Environment (IDE) powered by Google's Gemini API. It allows you to write, edit, and debug HTML/JS/CSS code with the help of an advanced AI assistant that understands your code context, console logs, and even images.

![License](https://img.shields.io/badge/license-MIT-blue.svg)

## 🌟 Features

*   **Single File Architecture**: No backend, no Node.js, no Python required. Just one `index.html` file.
*   **Multimodal Input**: Upload images (screenshots, mockups) alongside your text prompts to guide the AI (e.g., "Make the website look like this image").
*   **Google Search Grounding**: Enable "Web Search" to let the AI fetch real-time data (e.g., "Add the latest stock price of AAPL to the page") using Gemini tools.
*   **Context-Aware Debugging**: The AI automatically reads your code, conversation history, and **browser console logs** to fix errors intelligently.
*   **Time Machine**: Built-in version control allows you to instantly revert to previous code states.
*   **Mobile Friendly**: Fully responsive design optimized for coding on phones and tablets.
*   **Import/Export**: Save your work as `.html` files or load existing projects.

## 🚀 Getting Started

### Prerequisites
You need a **Google Gemini API Key**.
1.  Go to [Google AI Studio](https://aistudio.google.com/).
2.  Create a new API Key.

### Installation
1.  Download the `index.html` file from this repository.
2.  Open `index.html` in any modern web browser (Chrome, Edge, Firefox, Safari).

### Usage
1.  **Enter API Key**: Paste your Gemini API Key in the top-right input field and click the Save (💾) icon.
2.  **Write/Import Code**: Paste your HTML code into the "Source Code" panel or use the "Import" button.
3.  **Prompt the AI**:
    *   *Text*: "Change the background to dark blue."
    *   *Image*: Click the 🖼️ icon to upload a design mockup and ask "Style the button like this image."
    *   *Search*: Check "🌐 Web Search" and ask "Display the current weather in Tokyo."
4.  **Preview**: The right panel updates automatically. Console errors are fed back to the AI for the next turn.

## 🔒 Privacy & Security

*   **Client-Side Only**: This tool runs entirely in your browser.
*   **Direct API Calls**: Your API Key and code are sent directly from your browser to Google's servers. No intermediate server stores your data.
*   **Local Storage**: Your API Key is saved in your browser's `localStorage` for convenience.

## 🛠 Tech Stack

*   **Frontend**: Pure HTML5, CSS3, Vanilla JavaScript.
*   **AI Model**: Google Gemini 1.5 Pro / Flash & Gemini 3 Pro (Preview).

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
*Created for developers who want a portable, AI-assisted coding environment.*
