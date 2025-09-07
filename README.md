AI Voice Notes: Real-time Dictation and Smart Note-Taking
This is a sophisticated web-based dictation application that goes beyond simple transcription. It uses the browser's native speech recognition alongside the Gemini API to not only transcribe your speech in real time but also clean and polish it into a well-structured, professional note using Markdown. The app's animated and responsive design provides a smooth and intuitive user experience.
✨ Features
 * Real-time Transcription: Converts spoken words into text instantly using the Web Speech API.
 * AI-Powered Notes: Integrates with the Gemini API to automatically perform three key functions:
   * Raw Transcript: Captures every spoken word verbatim.
   * Cleaned Transcript: Removes filler words, stutters, and grammatical errors.
   * Polished Note: Formats the final text with Markdown (headings, lists, bolding) to create a clear, professional summary.
 * Dynamic Visuals: Includes a live audio waveform visualizer and a pulsating record button to provide real-time feedback.
 * Intuitive Interface: A clean, minimalist design with a responsive layout that works perfectly on desktop and mobile devices.
 * User-Configurable: A built-in settings modal allows you to easily set your Gemini API key and select a model.
 * Convenient Actions:
   * Copy the content from any of the three editor panels to the clipboard with a single click.
   * Toggle between light and dark themes.
   * Select your preferred microphone from a dropdown list.
 * Keyboard Shortcuts:
   * Space Bar: Start or stop recording.
   * Escape: Cancel the current recording.
   * Ctrl + C: Copy the content of the "Polished Note" panel.
💻 Technology Stack
 * HTML5 & CSS3: For a responsive, modern, and animated user interface.
 * Vanilla JavaScript: Powers all the application logic, including UI animations and API interactions.
 * Web Speech API: Provides browser-native speech recognition for accurate, low-latency transcription.
 * Gemini API: Used to process the raw transcript and generate the cleaned and polished notes.
 * Marked.js: A JavaScript library used to parse and render Markdown content.
 * Font Awesome: For all the clean, modern icons used throughout the app.
🚀 How to Use
 * Set Up:
   * Click the Settings gear icon in the top right corner.
   * Enter your Gemini API Key and a model name (e.g., gemini-1.5-pro-latest) in the modal. Click "Save and Close."
 * Start Recording:
   * Click the central microphone button or press the Space Bar on your keyboard.
   * A live waveform will appear, and the timer will start.
 * Transcribe & Polish:
   * Speak clearly into your microphone. Your words will begin to appear in the "Raw Transcript" panel.
   * When you are done, click the Stop button (or press the Space Bar again).
   * The app will automatically process your audio, populate the "Cleaned Transcript" panel, and format your final note in the "Polished Note" panel.
🤝 Contributing
We welcome contributions! Please feel free to open an issue or submit a pull request with new features, bug fixes, or improvements.
📄 License
This project is licensed under the MIT License.
