# Parking Space Detection

Detect parking spaces in camera images and video, and classify each as **empty** or **occupied**.

## Methods
- Object detection with YOLOv8
- Comparison: classification (CNN) vs. detection vs. segmentation
- Image processing and video analysis with OpenCV
- IoT design: camera → edge device → MQTT → dashboard

## Dataset
- PKLot (Almeida et al., 2015) — CC BY 4.0
- CNRPark-EXT — for testing on a new parking lot

## Folder structure
- notebooks/ — Colab notebooks
- data/ — dataset (not uploaded)
- models/ — trained models (not uploaded)
- results/ — charts, screenshots, demo videos

## Status
- [x] Project setup
- [ ] Dataset downloaded and explored
- [ ] YOLOv8 model trained
- [ ] Video demo
- [ ] Classification vs. segmentation comparison
- [ ] IoT simulation