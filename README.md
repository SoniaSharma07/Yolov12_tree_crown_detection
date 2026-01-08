# YOLOv12 Object Detection

## Project Overview  
This project trains and evaluates the Ultralytics YOLOv12 model for object detection on a custom dataset, leveraging GPU acceleration and data augmentation techniques.

## Dataset  
- Custom dataset specified via YAML config  
- Includes labeled images for training and validation  
- Supports single-class or multi-class detection

## Training  
- YOLOv12 nano architecture for efficiency  
- Uses Automatic Mixed Precision (AMP) for faster training  
- Data augmentation methods like mosaic and copy-paste applied  
- Configurable batch size and epochs to balance performance and resources

## Inference  
- Load trained weights for detection on new images  
- Adjustable confidence threshold for prediction filtering  
- Visualize detection results with bounding boxes and labels

## Conclusion  
The YOLOv12 model provides an efficient and flexible solution for object detection tasks, suitable for deployment on GPU-enabled environments with customizable training settings.
