# X3 Chatbot | Candyx3

X3 Chatbot is a smart and stylish AI assistant built for the web. It allows users to chat naturally, upload files for better context, and receive quick, intelligent responses. With a clean design, light/dark theme toggle, and mobile-friendly layout, it’s great for brainstorming ideas, solving problems, or just having fun conversations. The bot is powered by the Google Gemini API and runs entirely in your browser—no backend setup required.





## 🖼️ App Preview

[X3 Chatbot Screenshot](x3chatbot.png)



##💻Live Demo

Web - https://x3chat.netlify.app/





## ✨ Features

- 🌗 Light and Dark theme support  
- 💬 Smooth chatbot interaction with typing animation  
- 📁 File upload support (images, PDFs, text, etc.)  
- 🧠 Gemini API integration for smart replies  
- 📱 Fully responsive and mobile-friendly design  
- ⚡ Quick-start suggestion prompts  




## 🚀 How to Use

1. Open `index.html` in any modern web browser
2. Replace the demo API key in `script.js` with your own Google Gemini API key:
   const API_KEY = "YOUR_API_KEY_HERE";





## 🧪 API Key Notes
This project requires a Google Gemini API key.
You can get one from Google AI Studio.





## 💡 How it Works
1. Gemini API Integration
        Using the Generative Language API (Gemini), the app sends a user’s prompt and receives an AI-generated response. This is handled in script.js with a fetch request.

2. File Upload & Embedding
        Uploaded files (images, PDFs, etc.) are converted to base64 and injected as context to improve AI relevance.

3. Typing Simulation
        The app uses a simple setTimeout mechanism to simulate typing for a more realistic conversation experience.

4. Theme Switching
        A toggle button saves light/dark theme preference using localStorage.





## 🧩 Tech Stack

HTML5
CSS3 (with custom themes)
Vanilla JavaScript
Google Gemini API (Generative Language API)




## 📦 Code Structure


x3chatbot
├── index.html         # Main app structure
├── style.css          # App styling and themes
├── script.js          # Chat logic and Gemini API integration
├── image.png          # Avatar/favicon image
├── x3chatbot.png      # App screenshot




## 👨‍💻 About the Creator

Made with ❤️ by Chandru KB
Check out more of my work on my portfolio(https://candyx3.github.io/portfolio/).





## ⚠️ Disclaimer
X3 is powered by AI and may not always get things right. Always double-check important info.
