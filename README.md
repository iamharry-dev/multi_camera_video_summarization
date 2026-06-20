<h1 align="center">📹 Multi-Camera Video Summarization</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white"/>
  <img src="https://img.shields.io/badge/Multiprocessing-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
</p>

<p align="center">
  <b>Summarize multiple camera feeds simultaneously — merge keyframes across sources.</b>
</p>

---

## 🎯 What It Does

| Feature | Description |
|---------|-------------|
| 🎥 **Multi-Camera** | Process 8+ camera feeds in parallel |
| 🔄 **Parallel Processing** | multiprocessing for speed |
| 🎬 **Merged Output** | Single combined summary video |
| 📊 **DPP Algorithm** | Diversity-aware keyframe selection |
| ⚙️ **Configurable** | Set number of cameras via config.ini |

---

## 📁 Project Structure

```
multi-camera-video-summarization/
├── README.md
├── requirements.txt
├── config.ini               # Camera configuration
├── create_data.py           # Parallel dataset generation
├── extract_frames.py        # Frame extraction
├── updated.py               # Multi-camera summarization
├── utils/                   # Utility functions
├── dataset/                 # H5 datasets per camera
└── log/                     # Output videos
```

---

## 🚀 Quick Start

```bash
git clone https://github.com/iamharry-dev/multi-camera-video-summarization.git
cd multi-camera-video-summarization
pip install -r requirements.txt
# Edit config.ini to set number of cameras
python create_data.py
python updated.py
```

---

## 📊 Sample Output

```
Processing 8 cameras in parallel...
Camera 0: 1200 frames → 600 keyframes
Camera 1: 1150 frames → 575 keyframes
...
Merging keyframes across cameras...
✅ Combined summary: output/combined_summary.mp4
Total duration: 4:00:00 → 45:00 (81% reduction)
```

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|------------|
| Algorithm | DPP |
| Deep Learning | PyTorch |
| Video I/O | OpenCV |
| Parallelism | multiprocessing |
| Configuration | configparser |

---

## 👤 Author

**Hariprasath L.** — Data Scientist | ML Engineer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/harry-freelancer)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/iamharry-dev)

---

<p align="center">⭐ </p>
