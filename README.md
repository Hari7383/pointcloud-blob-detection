# Point Cloud Blob Detection

A 3D point-cloud processing project for detecting and analyzing **blobs (connected regions / clusters)** in point-cloud data.

This project focuses on **geometry-based blob detection** in 3D space, commonly used in industrial inspection, surface analysis, and defect detection.

---

## 🚀 Project Overview

Blob detection in point clouds is used to identify:
✔ Surface defects  
✔ Holes and pits  
✔ Protrusions  
✔ Material deposits  
✔ Clustered geometric regions  

Unlike 2D image blob detection, this project works directly on **3D spatial data** using point-cloud processing techniques.

---

## 🧠 What is a Blob in a Point Cloud?

In this context, a **blob** is:
- A connected cluster of 3D points
- Spatially distinct from surrounding points
- Defined by distance, density, or geometry
- Often representing a physical feature or defect

---

## 🛠️ Tech Stack

- Python 3.8+
- Open3D / PCL / custom point-cloud utilities
- NumPy
- SciPy (for clustering / distance computation)
- Matplotlib / Open3D visualizer

*(Exact library depends on implementation)*

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/Hari7383/pointcloud-blob-detection.git
cd pointcloud-blob-detection
```
Create and activate a virtual environment:
```
python -m venv venv
source venv/bin/activate     # Linux / macOS
venv\Scripts\activate        # Windows
```
