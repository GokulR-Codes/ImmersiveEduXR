# 🚀 ImmersiveEduXR

**ImmersiveEduXR** is an AI-powered AR/VR-based EdTech platform that transforms 2D educational content into interactive 3D learning experiences.

This project demonstrates a **frontend MVP prototype** featuring:

* 3D visualization using Three.js
* Multi-domain learning (Engineering, Medical, Architecture, Arts, Science)
* AI Tutor simulation
* File upload + 2D → 3D pipeline simulation
* WebXR-ready design

---

## 🌐 Live Concept

> “Upload diagrams → Convert to 3D → Learn in VR”

---

## 🧠 Features

### 🎯 Multi-Domain Learning

Supports multiple educational fields:

* ⚙ Engineering (CAD, mechanical systems)
* ⊕ Medical (anatomy, DICOM visualization)
* ◫ Architecture (blueprints → 3D walkthroughs)
* ◈ Arts (sketch → sculpture)
* ⬡ Science (molecules, simulations)

---

### 🧩 3D Viewer

* Interactive 3D rendering using **Three.js**
* Rotate, zoom, inspect models
* Domain-specific models generated dynamically
* Real-time property panel (vertices, polygons, format)

---

### 📤 Upload & Conversion Pipeline (Simulated)

* Drag-and-drop file upload UI
* Supported formats:

  * Images: JPG, PNG
  * CAD: STL, OBJ, DXF, DWG
  * Medical: DICOM
  * Science: PDB
* Pipeline stages:

  1. File Validation
  2. Computer Vision Analysis
  3. 3D Mesh Generation
  4. AI Labeling
  5. XR Packaging

---

### 🤖 AI Tutor (Simulated)

* Chat-based assistant for 3D models
* Explains concepts (e.g., gear mechanisms)
* Supports:

  * Real-time Q&A
  * Step-by-step explanation
  * Voice-ready architecture (future)

---

### 🧱 Architecture (Frontend View)

* Canvas-based rendering (Three.js)
* Modular domain switching
* Simulated backend pipeline
* Ready for integration with:

  * FastAPI backend
  * ML models (MiDaS, NeRF)
  * LLM APIs

---

## 🛠 Tech Stack

### Frontend

* HTML5 + CSS3
* JavaScript (Vanilla)
* Three.js (3D rendering)
* WebGL

### Future Integration

* React.js + Three.js
* FastAPI (Python backend)
* OpenCV / Open3D
* PyTorch / TensorFlow
* WebXR (AR/VR support)

---

## 📂 Project Structure

```
immersiveedu.html   # Main frontend MVP file
README.md           # Project documentation
```

---

## ▶️ How to Run

1. Download or clone the repository
2. Open the file:

```
immersiveedu.html
```

3. Run in browser (recommended):

* Chrome / Edge

---

## 🎮 Controls

### 🖱 3D Interaction

* Drag → Rotate model
* Scroll → Zoom in/out
* Double click → Reset view

### 📦 Upload

* Drag & drop files OR click upload box

### 🔄 Domain Switching

* Use tabs to switch between domains

---

## 🧪 Current Limitations

* ❌ No real backend (pipeline is simulated)
* ❌ No actual 2D → 3D conversion yet
* ❌ AI Tutor uses predefined responses
* ❌ No database/storage integration

---

## 🚀 Future Roadmap

### 🔥 Phase 1 (Backend)

* FastAPI server
* File upload API
* Real 2D → 3D conversion (MiDaS + Open3D)

### 🔥 Phase 2 (AI Integration)

* LLM-based tutor (OpenAI / local model)
* Voice (Whisper + TTS)

### 🔥 Phase 3 (XR Expansion)

* WebXR support
* Unity integration
* VR headset compatibility

### 🔥 Phase 4 (Production)

* Cloud deployment (AWS)
* Authentication (JWT)
* Multi-user collaboration

---

## 📊 Datasets (Planned)

* ShapeNet (3D models)
* Objaverse
* NIH Medical Dataset
* Matterport3D
* Google Scanned Objects

---

## 💡 Use Cases

* Engineering education (CAD visualization)
* Medical training (3D anatomy)
* Architecture walkthroughs
* Science simulations
* Creative arts modeling

---

## 🏆 Project Goal

To build a **scalable EdTech platform** that replaces traditional 2D learning with:

> immersive, interactive, AI-powered 3D experiences

---

## 👨‍💻 Author

**Gokul R**

* Cybersecurity & AI Enthusiast
* 3rd Year Information Science Engineering
* Focus: AR/VR + AI + Security

---

## ⭐ Contribution

This is an MVP prototype. Contributions are welcome:

* Backend development
* AI model integration
* XR features
* UI/UX improvements

---

## 📜 License

MIT License

---

## 🚀 Vision

> “The future of education is not reading — it’s experiencing.”

---
