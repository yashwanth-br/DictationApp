# AI Voice Dictation & Notes App

A simple, powerful, single-file web application that uses the Google Gemini API to transcribe and polish your voice notes in real-time. Record your thoughts, and let AI turn them into clean, well-formatted text.

![DictationApp Screenshot](https://i.imgur.com/your-screenshot-url.png)
*(Optional: Replace the URL above with a link to a screenshot of your app)*

---

## ✨ Features

-   **🎙️ Live Audio Recording:** Capture voice notes directly in your browser.
-   **🎤 Microphone Selector:** Choose your preferred input device from a dropdown list of all connected microphones.
-   **🎧 External Device Control:** Start and stop recordings using media controls from your earbuds or keyboard.
-   **🌊 Real-time Visualization:** See your voice visualized as a waveform while you speak.
-   **🤖 Multi-Stage AI Processing:**
    -   **Raw Transcript:** Get a raw, word-for-word transcript of your recording.
    -   **Cleaned Transcript:** An intermediate version that removes filler words and stutters while preserving the conversational flow.
    -   **Polished Note:** A final, well-formatted note with corrected grammar and markdown structure.
-   **❌ Cancel Recording:** Discard a recording with a single click without sending it to the API.
-   **📋 Copy to Clipboard:** Easily copy text from any of the three panes.
-   **🔇 Silence Detection:** Intelligently detects if a recording is silent to provide instant feedback and save API calls.
-   **🌗 Light & Dark Modes:** Toggle between themes for comfortable viewing.
-   **📁 Single File, No Dependencies:** Runs entirely from a single HTML file with no installation required.

---

## 🚀 How to Use

Because this application requires microphone access, you must serve it from a local web server. The easiest way to do this is with the **Live Server** extension in Visual Studio Code.

### Prerequisites

-   A modern web browser (Chrome, Firefox, Edge, etc.).
-   A Google Gemini API Key. You can get one for free from [Google AI Studio](https://aistudio.google.com/).
-   [Visual Studio Code](https://code.visualstudio.com/) with the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension installed.

### Steps

1.  **Clone the Repository or Download the File:**
    ```bash
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    cd your-repository-name
    ```
    Or, simply download the `DictationApp.html` file.

2.  **Add Your API Key:**
    -   Open `DictationApp.html` in a text editor like VS Code.
    -   Find the following line in the `<script>` section:
        ```javascript
        const GEMINI_API_KEY = "YOUR_API_KEY_HERE";
        ```
    -   Replace `"YOUR_API_KEY_HERE"` with your actual Google Gemini API key.

3.  **Launch with Live Server:**
    -   Right-click the `DictationApp.html` file inside VS Code.
    -   Select "**Open with Live Server**".
    -   Your browser will automatically open with the application running.

4.  **Start Recording:**
    -   The browser will ask for microphone permission when the page loads. Click **Allow**.
    -   Select your desired microphone from the dropdown.
    -   Click the red microphone button to start and stop recording!

---

## 🛠️ Technologies Used

-   **HTML5**
-   **CSS3**
-   **Vanilla JavaScript**
-   **Google Gemini API:** For AI-powered transcription and text polishing.
-   **Web Audio API:** For audio visualization.
-   **Media Session API:** For earbud/keyboard media controls.
-   **Marked.js:** To convert the AI's markdown response into formatted HTML.
-   **Font Awesome:** For icons.

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
