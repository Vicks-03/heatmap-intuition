
# 🔷 Dot Product Heatmap of Normalized Random Vectors

This project visualizes how directional relationships between vectors can be analyzed using **dot products** and **heatmaps** — serving as an introductory tool to understand **spatial similarity** in vector spaces.

The visualization makes it easy to grasp how aligned, orthogonal, or opposing directions manifest as structured patterns in a matrix — a technique foundational in physics, machine learning, and vector field analysis.

---

## 🎯 Objective

To build a simple but conceptually powerful heatmap by:
- Generating a set of random 3D vectors
- Normalizing them to focus on **direction** only (not magnitude)
- Computing pairwise **dot products** → which represent **cosine of the angle** between each vector pair
- Plotting a **color-coded heatmap** of those dot products to visually interpret vector alignment

This helps us learn how geometric relationships (like angle and orientation) are embedded numerically in dot products and visually in heatmaps.

---

## 🧠 Why Normalized Vectors?

By normalizing vectors (making them unit-length), we ensure that the dot product:
- Lies in the range [-1, 1]
- Equals the cosine of the angle between the two vectors:  
  **dot(u, v) = cos(θ)**

This removes the influence of length/magnitude and purely measures **directional similarity**.

---

## 📊 What the Heatmap Shows

- **1.00 (Red)** → Perfect alignment (cos(0°) = 1)
- **0.00 (White/Neutral)** → Perpendicular vectors (cos(90°) = 0)
- **-1.00 (Blue)** → Opposite direction (cos(180°) = -1)





