# traffic_signs_detection

## Overview
Traffic_signs_detection is a project aimed at developing a robust system for detecting traffic signs using a custom-trained YOLOv8 model. This project utilizes the YOLOv8 object detection architecture trained on custom traffic signs image datasets to create an efficient traffic sign detection system. Once trained, the model is then used to detect traffic signs from sample footage.

## Project Structure
The project is organized into the following main components:

1. Dataset Collection and Preprocessing: Traffic signs image datasets are collected and preprocessed to prepare them for training the YOLOv8 model.

2. Training YOLOv8: The YOLOv8 architecture is trained on the collected traffic signs image dataset to accurately detect traffic signs.

3. Model Evaluation: The trained model's performance is evaluated using various metrics to ensure its effectiveness in detecting traffic signs.

4. Deployment: The trained model is deployed to create the traffic-signs detection system, which has the ability to take real-time video feeds for traffic sign detection.

## Dataset
The dataset used for training the YOLOv8 model consists of traffic signs images. The dataset includes images with annotated bounding boxes around traffic signs to facilitate supervised training. You can access the dataset from [here](https://www.kaggle.com/datasets/valentynsichkar/traffic-signs-dataset-in-yolo-format).

## Training
The YOLOv8 model is trained using the collected traffic signs image dataset. Training involves optimizing the model's parameters to minimize detection loss and improve its ability to accurately detect traffic signs. The model was trained for 10 epochs with a batch size of 30. You can access the model training source code from [here](https://github.com/umairsiddique3171/traffic_signs_detection/tree/main/custom_yolov8).

## Model Evaluation
The trained YOLOv8 model achieved precision, recall, and mAP of 0.952, 0.838, and 0.941, respectively, on 78 validation images with 119 instances. Model speed per frame is given as :
- 0.6 ms preprocess
- 14.1 ms inference
- 0.0 ms loss
- 2.8 ms postprocess

## Sample Video Detection
Once trained and evaluated, the model is used to detect traffic signs from sample footage. You can see the results as under :

https://github.com/umairsiddique3171/traffic_signs_detection/assets/148565997/0fc049de-cf93-4e18-a8db-f1361a3114a2

## Conclusion
Traffic-signs-yolov8_detection demonstrates the effectiveness of using custom-trained YOLOv8 models for traffic sign detection. By leveraging deep learning techniques, this project offers a reliable solution for enhancing traffic management and safety.

## License 
This project is licensed under the [MIT License](https://github.com/umairsiddique3171/traffic_signs_detection/blob/main/LICENSE).

## Author 
[@umairsiddique3171](https://github.com/umairsiddique3171)



