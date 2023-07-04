# UAV Object Detection using transfer learning with YOLOv5x [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iremustek/uav-object-detection-yolov5x/blob/main/uav-object-detection_yolov5x.ipynb)

This project focuses on performing UAV object detection using transfer learning with YOLOv5x. The work is conducted on Google Colab, utilizing a GPU for accelerated computations (NVIDIA-SMI 525.85.12, CUDA Version: 12.0).

 [![ Link](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iremustek/uav-object-detection-yolov5x/blob/main/uav-object-detection_yolov5x.ipynb)

## Dataset

The dataset consists of the following components:
- images: A collection of 314 diverse drone images.
- labels: Each image is annotated with an ID and bounding box information, specifying the position and dimensions of detected objects in the images (format: [ID, x, y, width, height]).

## Folder Tree 

After the train-test-validation split is done, the overall folder tree will be like that:

```
└── uav-object-detection-yolov5x /
    ├── data/
    │   ├── images/
    │   │   ├── train
    │   │   ├── test
    │   │   └── val
    │   └── labels/
    │       ├── train
    │       ├── test
    │       └── val   
    └── uav-object-detection-yolov5x.ipynb
```
