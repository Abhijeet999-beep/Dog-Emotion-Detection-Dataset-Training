# Dog-Emotion-Detection Dataset Training
This repository contains a custom object detection model trained to classify 5 dog emotions — **Happy**, **Alert**, **Frown**, **Relax**, and **Angry** — using the **YOLOv11** model from [Ultralytics](https://github.com/ultralytics/ultralytics). The dataset was annotated using **Roboflow** and formatted to work seamlessly with YOLOv11.

## 📌 Project Motivation

Dogs communicate their emotions through subtle facial cues and body language. However, recognizing these emotional states is often subjective and difficult for humans. This project aims to:

- Build an **AI-powered tool** to automatically detect and classify common dog emotions.
- Support **pet owners, trainers, and veterinarians** in better understanding canine behavior.
- Lay the foundation for **future emotion-to-voice translation systems**.

---

## 🧠 Model Summary

| Property            | Details                        |
|---------------------|--------------------------------|
| Architecture        | YOLOv11 (Ultralytics)          |
| Dataset Tool        | Roboflow                       |
| Classes             | `Happy`, `Alert`, `Frown`, `Relax`, `Angry` |
| Input Size          | 320x320                        |
| Dataset Split       | `70%` train, `20%` valid, `10%` test |
| Annotation Format   | YOLOv5-compatible (`.txt`)     |

dataset link:
https://drive.google.com/file/d/1TI3cvUWpjHNjQxfTAmTGQ8moxPrQFYPW/view?usp=sharing 
---



