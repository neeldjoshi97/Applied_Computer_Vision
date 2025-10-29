# Applied Computer Vision — Showcase

Welcome to my portfolio of end results from the **Computer Vision for Engineers** course. This repository highlights key image processing tasks with brief descriptions.

---

## 🧠 Overview

Each task demonstrates a specific computer vision technique. Click on a task to view its details:

| Task | Description |
|------|-------------|
| [Object Identification](#-object-identification) | Recognising different types of spare parts and colour coding them |
| [Fault Detection](#fault-detection) | Detect and highlight faulty objects on production line |
| [PCB Trace Detection](#trace-detection) | Detect and highlight faulty objects on production line |
| [Gamma Correction](#gamma-correction) | Improve image visibility |
| [Crack Detection](#crack-detection) | Detect cracks generated in structural elements |
| [Image Stitching](#image-stitching) | Generating maps from aerial images |
| [Edge Detection](#edge-detection) | Extracting edges using Canny and Sobel operators |

---

## 🧹 Object Identification

| Before | After |
|--------|-------|
| ![Before processing](images\obj_identification\all-parts.png) | ![After Processing](images\obj_identification\all-parts-output.png) |

**Blue**: Ring Terminal

**Red**: Spade Terminal

**Violet**: Washer

**Green**: Internal Lock Washer

**Yellow**: External Lock Washer

---

## 🎯 Fault Detection

| Input | Fault Detection |
|----------------|------------------|
| ![Original](images/fault_detection/spade-terminal.png) | ![Detected](images/fault_detection/result.png) |

**Black**: Accepted

**Red**: Rejected

---

## 🎯 PCB Trace Detection

| Input | Trace Detection |
|----------------|------------------|
| ![Before](images/trace_detection/circuit.png) | ![After](images/trace_detection/circuit_output.png) |

---

## 🧹 Gamma Correction

| Before | After |
|--------|-------|
| ![Input](images/gamma_correction/carnival.jpg) | ![Output](images/gamma_correction/carnival_gcorrected.jpg) |

---

## 🎯 Crack Detection
| Input | Crack Detection |
|----------------|------------------|
| ![Before](images/crack_detection/wall1-original.png) | ![After](images/crack_detection/wall1-cracks.png) |

---

## 🎯 Locating Cancer

| Input | Cancer Detection |
|----------------|------------------|
| ![Before](images/locating_cancer/x-ray-new.png) | ![After](images/locating_cancer/x-ray-color.png) |

---

## 🧩 Image Stitching

| Output |
|------------------|
![Stitched](images/image_stitching/pittsburgh-stitched.jpg) |

---

## ✂️ Edge Detection

| Original | Edges |
|----------|-------|
| ![Original](images/edge_detection/gear.png) | ![Edges](images/edge_detection/gear-canny.png) |

**Method**: Canny Edge Detector  
**Thresholds**: Low = 97, High = 78

---

## 📜 License

This work is licensed under the Creative Commons CC by 4.0 License.