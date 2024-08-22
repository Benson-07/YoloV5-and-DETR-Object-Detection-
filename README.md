# YoloV5-and-DETR-Object-Detection-
This repository provides a Jupyter Notebook for real-time object detection using YOLOv5 and DETR models. Users can select from different model types and variants, and see detection results with bounding boxes and inference time directly on their webcam feed.


1)Features
Model Selection: Choose between YOLOv5 and DETR.
Variant Selection: Select from various models and their variants.
Real-Time Detection: Perform object detection in real-time using a webcam.
Display Information: View the current model and variant, along with inference time, directly on the video feed.

2)Installation
To use this code, you'll need to install the required Python libraries. You can install them using pip
pip install torch torchvision transformers ipywidgets opencv-python-headless
Note: For YOLOv5, you may need to have git installed to clone the YOLOv5 repository.

3)Usage

3.1 Launch Jupyter Notebook:
Open a terminal and start Jupyter Notebook with:

3.2 Open and Run the Notebook:
Open the provided Jupyter Notebook file in the Jupyter interface.

3.3 Interact with the Interface:

   *Select the model type (YOLOv5 or DETR) from the first dropdown.
   *Choose the model variant from the second dropdown.
   *Click the "Start Detection" button to begin real-time object detection.
   
4)Stopping Detection:
Press the 'q' key in the video feed window to stop detection and close the webcam feed.

5)Model Variants
5.1YOLOv5:

  yolov5s: Small model for faster inference.
  yolov5m: Medium model with a balance between speed and accuracy.
  yolov5l: Large model with higher accuracy.
  yolov5x: Extra-large model with the highest accuracy.
5.2 DETR:

  facebook/detr-resnet-50: Standard DETR model with ResNet-50 backbone.
  facebook/detr-resnet-101: Enhanced DETR model with ResNet-101 backbone.
Press the 'q' key in the video feed window to stop detection and close the webcam feed.
