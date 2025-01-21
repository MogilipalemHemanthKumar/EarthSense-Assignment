
# YOLOv11n Thermal Dataset Training

This repository contains the code and results for training a YOLOv11n model on the **Thermal Dogs and People Dataset** from RoboFlow. The model was trained to detect dogs and people in thermal images, achieving high precision and recall. Below are the details of the training and results.

## Dataset
- **Source**: RoboFlow
- **Dataset**: Thermal Dogs and People
- **Classes**: Dog, Person
- **Images**: 20 images used for training and evaluation.

## Model Details
- **Model**: YOLOv11n (nano variant)
- **Training Duration**: 20 epochs
- **Framework**: Ultralytics

## Results
| Class    | Images | Instances | Precision | Recall | mAP50 | mAP50-95 |
|----------|--------|-----------|-----------|--------|--------|-----------|
| **all**  | 20     | 27        | 0.947     | 0.955  | 0.975  | 0.842     |
| **dog**  | 11     | 11        | 0.908     | 0.909  | 0.955  | 0.871     |
| **person** | 11   | 16        | 0.985     | 1.000  | 0.995  | 0.814     |

- **Box Precision (P)**: 0.947
- **Box Recall (R)**: 0.955
- **mAP50**: 0.975
- **mAP50-95**: 0.842


