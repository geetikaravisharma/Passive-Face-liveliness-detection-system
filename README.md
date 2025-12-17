# 🧠 Face Liveness Detection

This project is a browser-based **face liveness detection system** built using React and TensorFlow.js. It identifies whether the user in front of the camera is a real person or a spoof (e.g., photo, video, or mask).

---

## 🚀 Features

- ✅ Real-time face liveness detection
- ✅ Uses a TensorFlow.js model (`model.json` and shard binaries)
- ✅ Runs completely in-browser
- ✅ Built with React.js
- ✅ No server/backend required

---

## 📂 Project Structure

```
📁 Face-Liveness-Detection
├── App.js
├── App.css
├── App.test.js
├── index.js
├── index.css
├── logo.svg
├── model.json
├── group1-shard1of3.bin
├── group1-shard2of3.bin
├── group1-shard3of3.bin
├── reportWebVitals.js
└── setupTests.js
```

---

## 🛠️ Getting Started

### Prerequisites

- Node.js and npm installed

### Setup Instructions

1. Clone the repository:

```bash
git clone https://github.com/geetikaravisharma/Passive-Face-liveliness-detection-system.git
cd Face-Liveness-Detection
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm start
```

Now visit `http://localhost:3000` in your browser to test the app.

---

## 💡 How It Works

- Accesses your webcam using `getUserMedia`
- Processes video frames using a TensorFlow.js model
- Predicts whether the face is **real** or **fake**
- Outputs the result on the UI instantly

---

## 📌 Use Cases

- Aadhaar authentication
- Attendance systems
- Secure login portals
- Anti-spoofing in online exams or banking apps

---

## 📈 Future Improvements

- Aadhaar face matching integration
- Improved spoof detection for videos/masks
- Backend support for logging and analytics
- Deployment via Vercel or Firebase

---

