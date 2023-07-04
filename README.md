# UAV Object Detection using transfer learning with YOLOv5x [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iremustek/uav-object-detection-yolov5x/blob/main/uav-object-detection_yolov5x.ipynb)

- All work is done through Google Colab with a GPU  (NVIDIA-SMI 525.85.12, CUDA Version: 12.0)

- The related notebook can be found here: [![ Link](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iremustek/uav-object-detection-yolov5x/blob/main/uav-object-detection_yolov5x.ipynb)

## Dataset

Dataset includes:
- images: 314 different drone images
- labels: id and bounding box information of each images [id x y width height]

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
