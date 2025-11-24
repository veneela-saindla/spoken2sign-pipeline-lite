# spoken2sign-pipeline-lite

Lightweight baseline spoken-to-sign translation pipeline  
**CSIR-4PI Research Internship Project**

---

## 📌 Overview

This repository contains a **lite, simplified implementation** of a spoken-to-sign language translation pipeline.

It reproduces the **pipeline architecture** from:

**Zuo et al., 2024 — “A Simple Baseline for Spoken-to-Sign Translation with 3D Avatars”**

using:
- Pre-extracted **MediaPipe 33-joint pose keypoints**  
- A **50-video subset** of PHOENIX-2014T  
- Lightweight temporal smoothing  
- Basic co-articulation  
- Skeleton-based rendering

⚠️ This is a **baseline**, not a full reproduction.  
Focus is on **understanding the architecture**, not model accuracy.

---

## 🏗️ Pipeline Stages

1. Speech → Text  
2. Text → Gloss (rule-based)  
3. Gloss → Pose Keypoints  
4. Temporal Preprocessing  
5. Co-articulation  
6. Skeleton Rendering (Matplotlib)

---

## 📂 Repository Structure

