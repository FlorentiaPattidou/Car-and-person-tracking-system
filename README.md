# Car-and-person-tracking-system
YOLOv8-based object detection system for cars and pedestrians  on the KITTI tracking dataset. Includes detection pipeline,  evaluation with IoU matching, and frame-by-frame metrics.

## Dataset
This project uses the KITTI Tracking Dataset.
Download from: https://www.cvlibs.net/datasets/kitti/eval_tracking.php

Expected folder structure:
KITTI/
├── data_tracking_image_2/
│   └── training/
│       └── image_02/
│           ├── 0000/
│           └── 0001/
└── data_tracking_label_2/
    └── training/
        └── label_02/
            ├── 0000.txt
            └── 0001.txt
