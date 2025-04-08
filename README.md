# 🧠 Image Feature Matching with SIFT, Harris Corner Detection, and RANSAC

This project demonstrates the use of **SIFT** and **Harris Corner Detection** to detect keypoints in grayscale images and uses **RANSAC (Random Sample Consensus)** to filter outliers during keypoint matching. The goal is to estimate a transformation between two views of the same scene/object (e.g., a statue) and visualize robust correspondences.

---

## 🧩 Included Methods

- 🟢 **Harris Corner Detection** – Detect corner-like features in grayscale images
- 🔵 **SIFT (Scale-Invariant Feature Transform)** – Extract distinctive and scale/rotation-invariant keypoints and descriptors
- 🔴 **RANSAC** – Filter out false matches and estimate a robust transformation model (homography or affine)

---

## 📸 Sample Use Case

Use this code to:
- Compare two photos of the same statue taken from different angles
- Match architectural features between two building views
- Remove noisy matches caused by viewpoint changes

---

## 📁 Dataset

You can use any pair of grayscale images with overlapping content. Suggested:
- Statue of Liberty from different angles
- Adiyogi statue from the front and side
- Oxford Affine Dataset: [VGG](http://www.robots.ox.ac.uk/~vgg/data/data-affine/)

Place your image pair in the `images/` folder.

---

## 🛠️ Installation

```bash
git clone https://github.com/yourusername/image-matching-ransac
cd image-matching-ransac
pip install -r requirements.txt
