# Emergent-SCOPR

**Objective**: An Emergent project, in collaboration with SCOPR, aims to support prospective home-buyers in the home-buying process through the development of AI-based models. Four models have been developed using YOLOv8 and InceptionV3.

## Models
1. **Doors and windows**
    - YOLOv8 was used for the task of object detection to develop a model for detecting and counting the number of doors and windows.
    - The model was trained on house images from Roboflow.
2. **Condition of roof base**
    - YOLOv8 was used for segmentation to develop a model for detecting and classifying roof base conditions.
    - Annotations were created using the CVAT software.
    - A mAP@0.5 of 0.724 was achieved across all classes on the validation set.
4. **Roof materials**
   - A pre-trained InceptionV3 model was used to develop a model to detect roof materials.
   - An accuracy score of 0.758 was achieved on the validation set.
6. **State of roof tiles**
   - A pre-trained InceptionV3 model was used to develop a model to detect the state of roof tiles.
   - An accuracy score of 0.650 was achieved on the validation set.
