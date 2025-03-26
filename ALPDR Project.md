# Automated Vehicle License Plate Detection and Recognition Using YOLO and CNN

## Contributors
- **Project Supervisors:** Dr. Usman Nazir, Dr. Sana Bashir  
- **Team Members:** Umer Mansoor, Wajahat Siddique, Nayab Bashir  
- **Affiliation:** Knowledge Streams, Lahore, Pakistan  

---

## Preview
##### Download Poster in PDF: [ALPDR Poster.pdf](https://github.com/user-attachments/files/19475975/ALPDR.Poster.pdf)  
![image](https://github.com/user-attachments/assets/d0df8e70-6761-476d-a705-ec5d2787d827)


---

## Tools and Technologies Used
- **Machine Learning Frameworks:** TensorFlow
- **Object Detection Model:** YOLOv8
- **Character Recognition Models:** CNN, MobileNet, Inception V3, ResNet50
- **Programming Language:** Python
- **Libraries:** OpenCV, NumPy, Matplotlib, Pandas
- **Dataset:** [Vehicle Number Plate Dataset](https://github.com/umarsaeed12/Pakistan-Vehicle-Number-Plate-Dataset)

---

## Problem Statement
With the exponential increase in vehicular density, there is a growing need for automated systems to manage traffic efficiently and enhance security. Manual license plate monitoring is tedious and prone to errors. A robust automated system is required to:
- Reduce human intervention.
- Improve traffic management and law enforcement.
- Detect and recognize license plates with high accuracy in dynamic urban scenarios.

---

## Solution
Our project implements an advanced **Automated Vehicle License Plate Detection and Recognition System** using deep learning models. The approach consists of:
1. **License Plate Detection:** YOLOv8 is used for real-time object detection, balancing speed and accuracy.
2. **Character Recognition:** Various deep learning models (CNN, MobileNet, Inception V3, ResNet50) are evaluated, with CNN emerging as the best performer.
3. **Evaluation Metrics:** The system is assessed using Precision, Accuracy, Recall, F1-Score, and Loss.

### Methodology
- **Step 1:** Extract frames from video.
- **Step 2:** Apply YOLO-based detection to locate license plates.
- **Step 3:** Preprocess the cropped plate images.
- **Step 4:** Segment individual characters.
- **Step 5:** Apply CNN-based recognition to predict characters.
- **Step 6:** Output the recognized license plate.

![Image](https://github.com/user-attachments/assets/944fb52f-cd20-4312-b5e8-90c32f18ff79)
---

## Results
- The system achieves **high accuracy** in detecting and recognizing vehicle license plates.
- **Loss graph** shows significant convergence over training epochs.
- Performance comparison of character recognition models:
  
  | Model       | Accuracy  | Precision | Recall | F1-Score |
  |------------|-----------|-----------|--------|----------|
  | CNN        | 0.9215    | 0.8903    | 0.8724 | 0.8816   |
  | MobileNet  | 0.8972    | 0.8791    | 0.8602 | 0.8695   |
  | Inception V3 | 0.8845 | 0.8723    | 0.8498 | 0.8609   |

![Image](https://github.com/user-attachments/assets/dd6bb007-85c7-410f-9470-71527e22405a)
---

## Project Links

- **Dataset Link:** [Vehicle Number Plate Dataset](https://github.com/umarsaeed12/Pakistan-Vehicle-Number-Plate-Dataset)
---
💼 LinkedIn: [My LinkedIn Profile](https://linkedin.com/in/wajahatsiddique) 

