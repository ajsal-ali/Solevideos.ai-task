# Automated Face & Hand Segmentation

This repository contains a fully automated pipeline that detects faces and hands in images, then generates precise segmentation masks using Meta’s Segment Anything Model (SAM2.1) combined with MediaPipe. A minimal Gradio interface lets you upload any photo and instantly compare the raw bounding‐box detections against the refined segmentation overlays.

## Installation

First, clone the repository and install the required packages:

```bash
git clone https://github.com/yourusername/face‑hand‑segmentation.git
cd face‑hand‑segmentation
pip install -r requirements.txt
