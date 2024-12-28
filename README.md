# Car Damage and Parts Detection Project

This project leverages machine learning models to detect damaged areas on a car and identify the car parts affected by the damage. Using Roboflow's API and pre-trained models for car damage detection and parts segmentation, this application processes input images to highlight damage and list the probable parts involved.

---

## Features

- **Car Damage Detection:** Identifies and marks areas of damage in an uploaded image.
- **Car Parts Segmentation:** Detects car parts within the damaged area to specify the components affected.
- **Visualization:** Provides annotated images highlighting the damage and affected parts.
- **Dynamic Cropping:** Automatically crops and processes only the damaged area for parts segmentation, improving accuracy.

---

## Requirements

The following Python libraries are required to run this project:

- `roboflow`
- `supervision`
- `opencv-python`
- `tempfile`
- `os`
