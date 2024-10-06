# **Project Name** - Object Detection Using YOLOv8 for Safety Equipment Detection.

## Project Overview:

This project focuses on using the YOLOv8 (You Only Look Once version 8) object detection model to identify various safety equipment such as glasses, helmet, jacket, goggles, and footwear from images. The project aims to build a robust computer vision system capable of detecting and classifying safety gear in a variety of environments, helping to improve workplace safety monitoring, especially in construction or industrial settings.

## Dataset:

## Data Size: Approximately 3000 images.

**Data Collection:** Images were collected from real-world industrial environments, public datasets, or a combination of both. They represent different settings where safety equipment is worn, such as construction sites, warehouses, and workshops.

**Labels:** Each image is annotated with bounding boxes around the specific safety equipment, namely:

Glasses

Helmet

Jacket

Goggles

Footwear

* The dataset was manually labeled using tools like LabelImg or similar annotation software, ensuring that the bounding boxes tightly enclose the objects of interest.

## Challenges:

* Handling overlapping objects where one item (e.g., helmet and goggles) may occlude another.
* Variability in lighting conditions and angles, which can affect the detection accuracy.
* Balancing between detecting small objects (like glasses) and larger items (like jackets) within the same image.

## Conclusion:

This project successfully demonstrates the application of YOLOv8 in detecting essential safety equipment. The model shows strong potential for real-time deployment in industrial environments to automatically monitor worker safety, reducing human supervision needs. Future work may include further dataset expansion, integrating additional safety items, and optimizing the model for edge devices.



