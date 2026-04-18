# FossilEye

I built this to see if a computer vision model could learn to tell different fossils apart just from images.

The model detects and draws bounding boxes around fossils in images, and classifies them into one of 7 types.

---

## What it detects

| Fossil Type |
|-------------|
| Ammonite |
| Animal Fossil |
| Belemnite |
| Coral |
| Crinoid |
| Plant Fossil |
| Trilobite |

---

## Results

| Metric | Score |
|--------|-------|
| mAP@50 | 89.5% |
| Precision | ~90% |
| Recall | ~88% |

---

## Built with

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-00FFFF?style=flat&logo=ultralytics&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![Roboflow](https://img.shields.io/badge/Roboflow-7B2FBE?style=flat&logo=roboflow&logoColor=white)

---

## Dataset

Fossil image dataset from Roboflow — 992 labeled images across 7 fossil categories, split 80/10/10.

---

## How to run

1. Clone the repo
2. Run `pip install ultralytics roboflow`
3. Open `Fossil_Detection.ipynb` and run all cells

---

## About

A personal project built through experimentation and trial and error. First time working with object detection.
