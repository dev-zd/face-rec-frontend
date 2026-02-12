# FaceRec Pro: Premium Frontend Interface 🛡️✨

A high-performance, aesthetically stunning static web interface for the FaceRec Pro biometric security system. This repository contains the frontend logic that consumes the [FaceRec Backend API](https://github.com/dev-zd/face-rec-backend.git).

---

## 🌟 Key Features

- **Dynamic Dashboard**: Real-time visualization of attendance trends and security metrics using Chart.js.
- **Live Surveillance**: Interactive face detection and identification feed with status indicators.
- **CCTV Monitoring**: Dedicated dual-camera view for traditional security monitoring.
- **Identity Management**: A comprehensive database portal to register, view, and manage student profiles.
- **Missing Reports**: Automated bunk/skipped class detection with precise timestamps.
- **Secure Access**: Premium glassmorphism-styled Login, Signup, and Password Recovery flows.

## 🚀 Tech Stack

- **Structure**: Semantic HTML5
- **Styling**: Vanilla CSS3 (Custom Design System with Glassmorphism)
- **Logic**: Modern JavaScript (ES6+), Fetch API
- **Charts**: [Chart.js](https://www.chartjs.org/)
- **Icons**: [Font Awesome 6](https://fontawesome.com/)
- **Typography**: [Google Fonts (Outfit)](https://fonts.google.com/specimen/Outfit)

## 🛠️ Quick Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/dev-zd/face-rec-frontend.git
   cd face-rec-frontend
   ```

2. **Ensure the Backend is Running**:
   The frontend communicates with `http://localhost:8000`. Make sure your [backend server](https://github.com/dev-zd/face-rec-backend.git) is active.

3. **Launch the Interface**:
   Simply open `index.html` in any modern web browser.
   > [!TIP]
   > For the best experience (and to avoid CORS/Secure Context issues with the webcam), serve the files using a local server (e.g., Live Server in VS Code).

## ⚙️ Configuration

The API base URL is configured in each script as:
```javascript
const API_BASE = "http://localhost:8000";
```
If your backend is hosted elsewhere, update this variable across the HTML files.

## 🔒 Security Note
This frontend uses `localStorage` for session persistence (storing the username). Sensitive operations should always be verified by the backend API.

---

Built with ❤️ by [Devkrishna M Pradeep](https://github.com/dev-zd)
