# ✋ Sign Language for Deaf People – Frontend

A web-based interface that translates sign language gestures into text, enabling seamless communication between deaf individuals and others.
## 🌟 Features
- 🎥 Real-time gesture input via webcam
- 🧠 Integration with ML-based gesture recognition API
- 💬 Instant text translation display
- 📱 Responsive design for mobile and desktop
- 🎨 Clean and accessible UI built with HTML, CSS, and JavaScript

## 🧰 Tech Stack
- **Frontend:** HTML5, CSS3, JavaScript
- **Backend (API):** Python Flask / TensorFlow (connected via REST API)
- **Version Control:** Git & GitHub
- **Tools:** VS Code, Google Teachable Machine / MediaPipe

## 🏗️ Architecture
The frontend sends video frame data to the backend ML model through REST endpoints. The backend processes gestures and returns the translated text, which is dynamically rendered on the UI.

## ⚙️ Installation
```bash
# Clone the repository
git clone https://github.com/BoovaragavanRaju/SignLanguageTranslator-Frontend.git

# Navigate to the project folder
cd SignLanguageTranslator-Frontend

# Open index.html in your browser
