# Secure Facial Authentication System with Anti-Spoofing 🛡️👁️

A robust, multi-layered facial authentication platform designed to replace traditional static facial recognition with a highly secure, liveness-aware system. It ensures that the person attempting to authenticate is physically present, neutralizing spoofing attacks like printed photos, video replays, or digital screen projections.

## ✨ Key Features
* **Face Enrollment & Verification:** AI-based facial feature extraction and highly accurate real-time matching.
* **Liveness Detection:** Tracks dynamic facial features (like Eye Aspect Ratio / Blinks) to verify physical presence.
* **Anti-Spoofing (CNN):** Analyzes skin texture, depth cues, and reflection patterns to distinguish between a real 3D face and a 2D spoof attempt.
* **Security Logs:** Automated tracking of all authentication attempts (access granted/denied) for monitoring.
* **Dark UI / Dashboard:** Professional, intuitive interface for managing user enrollment and authentication logic.

## 🛠️ Technology Stack
* **Backend:** Python, Flask
* **Computer Vision:** OpenCV, MediaPipe
* **Machine Learning:** Scikit-learn (RandomForest), Deep Learning concepts for Anti-Spoofing
* **Frontend:** HTML5, CSS3 (Custom Dark Theme), JavaScript, Bootstrap 5, Chart.js
* **Database:** SQLite / Local DB Storage