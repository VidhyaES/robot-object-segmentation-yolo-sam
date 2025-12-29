# Robot Object Segmentation Pipeline (YOLOv8 + SAM)

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat&logo=python)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0%2B-orange?style=flat&logo=pytorch)](https://pytorch.org/)
[![YOLOv8](https://img.shields.io/badge/YOLOv8-Ultralytics-green?style=flat&logo=ultralytics)](https://ultralytics.com/)
[![SAM](https://img.shields.io/badge/Segment%20Anything-Meta-blueviolet?style=flat)](https://segment-anything.com/)

Instance segmentation pipeline developed for **semi-humanoid robots** during AI/ML internship — combining YOLOv8-seg for detection and Meta's Segment Anything Model (SAM) with Roboflow's AI-assisted annotation for precise object grasping in dynamic environments.

## 🎯 Project Highlights
- Precise instance segmentation for object detection & pickup tasks
- Leverages **Roboflow** Smart Polygon tool + AI-assisted annotations
- End-to-end training support for **YOLOv8 segmentation models**
- Improves real-time grasping capabilities for robotics applications
- Contributed to semi-humanoid robot autonomy during internship

**Developed & applied at iHub Robotics (Oct 2025 – Present)**

## 🛠️ Tech Stack
- **Core Language**: Python
- **Models**: YOLOv8-seg (Ultralytics), Segment Anything Model (SAM – Meta)
- **Annotation & Dataset**: Roboflow (AI-assisted Smart Polygon)
- **Frameworks**: PyTorch, Ultralytics YOLO
- **Others**: OpenCV (preprocessing), Jupyter notebooks for experiments

## ✨ Features
- Detection → Segmentation workflow for robotics manipulation
- High-precision annotations using Roboflow tools
- Model fine-tuning & training pipeline for custom objects
- Suitable for dynamic, real-world robotic environments

## 🚀 Quick Start

### Prerequisites
- Python 3.8+
- GPU strongly recommended (for training & inference)

### Installation
```bash
# Clone the repository
git clone https://github.com/VidhyaES/robot-object-segmentation-yolo-sam.git
cd robot-object-segmentation-yolo-sam

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

# Install dependencies
pip install -r requirements.txt
