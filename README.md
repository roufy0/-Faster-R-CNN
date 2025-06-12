# Object Detection with Faster R-CNN 

This project demonstrates how to train and evaluate a **Faster R-CNN** object detection model using PyTorch and the PASCAL VOC dataset. The model learns to detect 20 common object categories like "person", "car", "dog", "bottle", and more.

##  Dataset

- **PASCAL VOC 2007/2012**
- Includes:
  - Image + XML annotation pairs
  - 20 labeled object categories
- Auto-downloaded via `torchvision.datasets.VOCDetection`

##  Tech Stack

- Python
- PyTorch
- Torchvision
- Matplotlib
- VOC dataset

##  Model Details

- **Base model**: `torchvision.models.detection.FasterRCNN`
- Uses `AnchorGenerator` for region proposals
- Applies transformations with `torchvision.transforms.functional`

##  Project Highlights

-  Loading and preprocessing PASCAL VOC
-  Fine-tuning Faster R-CNN
-  Custom DataLoader with bounding boxes
-  Visualization of predicted bounding boxes with confidence scores
