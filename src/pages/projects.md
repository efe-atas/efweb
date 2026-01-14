---
layout: '~/layouts/MarkdownLayout.astro'
title: Projects
description: A list of my projects.
---

| Project | Technologies | Link |
|---------|--------------|------|
| **CT-based Stroke Segmentation** | PyTorch, UNet, OpenCV | — |
| **Cattle Behavior Detection** | YOLOv11, 3D-CNN | — |
| **School Course Scheduler** | React, Tailwind CSS | [Live](https://scheduler.efeatas.dev) |
| **Image Processing & 2D DCT** | Python, OpenCV | — |

---

## CT-based Stroke Segmentation and Classification

![CT Brain Scan](https://images.unsplash.com/photo-1559757175-5700dde675bc?w=800&h=400&fit=crop)

`PyTorch` `UNet` `OpenCV` `Medical Imaging`

Designed and trained a **UNet-based segmentation model** to distinguish between ischemic and hemorrhagic strokes. The system applies advanced image preprocessing techniques and extends with a classification head for end-to-end diagnosis. Segmentation masks are visualized as overlays on CT images for clinical interpretation.

**Key Features:**
- Deep learning segmentation for stroke detection
- Automated ischemic vs hemorrhagic classification
- Visual overlay generation for medical professionals

---

## Cattle Behavior Detection System

![Cattle in Field](https://images.unsplash.com/photo-1500595046743-cd271d694d30?w=800&h=400&fit=crop)

`YOLOv11` `OpenCV` `3D-CNN` `Multi-Object Tracking`

Built a complete **behavior analysis pipeline** combining YOLOv11 for real-time detection, advanced tracking algorithms (ByteTrack, BoT-SORT), and 3D-CNN for temporal modeling. Custom cattle video dataset was labeled and temporal evaluation metrics were designed for accuracy assessment.

**Key Features:**
- Real-time cattle detection and tracking
- Temporal behavior classification with 3D-CNN
- Optimized for edge device deployment

---

## School Course Scheduler

![Calendar Planning](https://images.unsplash.com/photo-1506784983877-45594efa4cbe?w=800&h=400&fit=crop)

`React` `Tailwind CSS` → [**scheduler.efeatas.dev**](https://scheduler.efeatas.dev)

A responsive **course scheduling web application** built with modern React and Tailwind CSS. Features intuitive drag-and-drop interface for schedule management with real-time conflict detection and resolution.

**Key Features:**
- Drag-and-drop course placement
- Automatic conflict detection
- Clean, modern UI design

---

## Image Processing and 2D DCT Implementation

![Digital Processing](https://images.unsplash.com/photo-1635070041078-e363dbe005cb?w=800&h=400&fit=crop)

`Python` `OpenCV`

Implemented **fundamental image manipulation functions** using OpenCV, including custom 2D Discrete Cosine Transform (DCT) algorithm coded from scratch. This project demonstrates deep understanding of signal processing and compression techniques.

**Key Features:**
- Custom image manipulation library
- DCT implementation from mathematical foundations
- Compression technique demonstration
