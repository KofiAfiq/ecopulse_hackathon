# 🌿 EcoPulse — Preventive JMB Waste Facility & AI CCTV Command Center

[![Live Demo](https://img.shields.io/badge/Demo-Live%20Online-10B981?style=for-the-badge&logo=google-chrome&logoColor=white)](#-live-online-prototype)
[![Hackathon](https://img.shields.io/badge/Hackathon-Sime%20Darby%20Property-0284C7?style=for-the-badge)](#)
[![Three.js](https://img.shields.io/badge/Three.js-r128%203D%20Digital%20Twin-F59E0B?style=for-the-badge&logo=three.js&logoColor=white)](#)
[![TailwindCSS](https://img.shields.io/badge/Tailwind-CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)](#)

> **EcoPulse** transforms traditional, reactive residential waste collection into a proactive, root-cause facility management ecosystem for Sime Darby Property townships (City of Elmina, Bandar Bukit Raja, Ara Damansara).

---

## 🌟 Interactive Live Online Links

| Component | Description | File |
| :--- | :--- | :--- |
| 🏢 **Command Center** | AI CCTV Simulator, IoT Odor (D/T) Panel, JMB Incident Queue & Root-Cause Analytics | [`index.html`](index.html) |
| 🌐 **3D Digital Twin Scanner** | Real-time volumetric spatial sweep of the Rumah Sampah room with sensor overlays | [`digital-twin.html`](digital-twin.html) |
| 🎬 **3D Animated Story Demo** | Cinematic 3D sequence with AI voiceover and subtitles showcasing resident interaction | [`animation.html`](animation.html) |

---

## 🚀 Key Modules & Capabilities

### 1. 🏢 AI CCTV & IoT Odor Command Center (`index.html`)
- **IoT Dilution-to-Threshold (D/T) Odor Simulation**: Models NH₃ and H₂S gas spikes under Malaysian ambient temperatures, auto-triggering bio-enzyme sprays at 7 D/T before residents complain.
- **YOLOv8 + SVM Overlap Bounding Boxes**: Evaluates disposal behavior (88% overlap for clean disposal, 0% for floor dumps, preventive LED redirection when bins are full).
- **Day / Night IR / UV Contamination Modes**: Highlights organic leachate, ammonia residues, and pet litter contamination.
- **6-Step JMB Governance Pipeline**: Transparent facility dispatch workflow advancing incidents from detection to cleaner rebalancing.
- **Root-Cause Remediation Plan**: Rebalances bin capacities and adjusts cleaner schedules based on historical overflow data.

### 2. 🌐 3D Digital Twin Scanner (`digital-twin.html`)
- Built with **Three.js (WebGL)**: Real-time 3D interactive view of an apartment waste room (Rumah Sampah).
- **Spatial Volumetric Raycasting**: Visualizes 4 color-coded bins (General, Plastic, Paper, Glass/E-Waste) with fill level indicators.
- **Sensors HUD**: Displays live D/T odor metrics, temperature, ammonia levels, and automated ventilation status.
- **Interactive Controls**: Orbit, pan, zoom, click bins to inspect status, and toggle UV / thermal overlay filters.

### 3. 🎬 3D Cinematic Story Presentation (`animation.html`)
- **Cinematic Camera Choreography**: Automated Three.js camera transitions highlighting key hackathon user journeys.
- **AI Audio Voiceover (`intro_voiceover.mp3`)**: Synchronized narration explaining the human behavior and facility benefits.
- **Live Captions & Monospace Telemetry**: Real-time bounding box reticles, event logs, and status readouts.

---

## 📦 Repository Structure

```text
ecopulse-github-release/
├── index.html              # Main Command Center & Analytics Dashboard
├── digital-twin.html       # 3D Digital Twin Three.js Viewer
├── animation.html          # 3D Cinematic Presentation Demo
├── intro_voiceover.mp3     # High-fidelity AI narration audio track
├── .nojekyll               # Disables Jekyll processing for GitHub Pages
└── README.md               # Project documentation & presentation guide
```

---

## 🌐 How to Host on GitHub Pages (Free, 24/7 Forever)

1. **Create a GitHub Repository**:
   - Go to [GitHub.com](https://github.com/new) and name your repository (e.g., `ecopulse`).
   - Set it to **Public**.
2. **Upload Files**:
   - Drag and drop all files from this folder (`index.html`, `digital-twin.html`, `animation.html`, `intro_voiceover.mp3`, `.nojekyll`, and `README.md`) into your GitHub repo, then click **Commit changes**.
3. **Turn On GitHub Pages**:
   - Click **Settings** (gear icon) in your repo.
   - Click **Pages** in the left sidebar.
   - Under **Branch**, select `main` (or `master`) and `/ (root)`, then click **Save**.
   - Within 30 seconds, your site is permanently live at:
     ```text
     https://<your-username>.github.io/<repo-name>/
     ```

---

## 👥 Hackathon Team & Acknowledgments

- **Hackathon**: Sime Darby Property • University Hackathon 2026
- **Project**: EcoPulse — Intelligent Waste Room & CCTV Facility Management
- **Target Townships**: City of Elmina, Bandar Bukit Raja, Ara Damansara
