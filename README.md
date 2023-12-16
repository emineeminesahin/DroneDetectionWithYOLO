## Data
https://drive.google.com/file/d/1YuRWsIc6-GhX2yucxL_HsSplGPPK2mX1/view?usp=sharing

## Weight
https://drive.google.com/file/d/1xo_uVTUDjxl1kXJDpljubLYxyytQVMIt/view?usp=sharing

In addition to the many advantages of Unmanned Aerial Vehicle (UAV) technology, which is becoming widespread day by day due to its accessibility and ease of use, it poses a growing threat to public security due to illegal uncontrolled use such as malicious and terrorist attacks, drug smuggling. In this study, YOLO (You Only Look Once) deep learning architecture models (YOLOv3, YOLOv3-tiny, YOLOv4, YOLOv4-tiny, YOLOv5x, YOLOv5s, YOLOv6-L, YOLOv6-S, YOLOv7-X, YOLOv7, YOLOv8l, YOLOv8s) were targeted for UAV detection. As a result, the performance analysis of the YOLO models was carried out and the most suitable model was searched by comparing their accuracy analysis. It was realized on Google Colaboratory with the support of Tesla-T4 GPU, using the Python programming language, using images containing UAVs taken with cameras. 11,907 labeling operations were performed in the training data and 3100 labeling operations were performed in the validation data. For training, 14.149 photos, whose data augmented with Roboflow, were separated as 80% training 20% validation data. During the training, transfer training was carried out with the YOLO architecture by using the weights previously trained with the MS COCO dataset. Among the calculated error matrix analyses, the best F1-Score value belongs to YOLOv6-L with 0.98.For YOLOv6-S, YOLOv5x, YOLOv8l, YOLOv8s, YOLOv7-X, YOLOv7, YOLOv5s, YOLOv4, YOLOv3-tiny, YOLOv3 and YOLOv4-tiny models, 0.97, 0.97, 0.96, 0.96, 0.95, 0.95, 0.95, 0.90, 0.76, 0.69 and 0.61 F1-Score performance results were obtained, respectively. According to the most preferred mAP accuracy criteria in the analysis of model accuracy of YOLO architecture in deep learning, values of 0.97, 0.97, 0.97, 0.97, 0.97, 0.94, 0.78, 0.66 and 0.58 were obtained for YOLOv8s, YOLOv7-X, YOLOv7, YOLOv6-L, YOLOv5s, YOLOv4, YOLOv3, YOLOv4-tiny and YOLOv3-tiny, respectively. The models that achieved the best mAP value were YOLOv8l, YOLOv6-S and YOLOv5x with 0.98.

![Image](https://github.com/emineeminesahin/DroneDetectionWithYOLO/blob/main/images/Training%20data.png)

**Distribution of 11.907 bounding boxes in the training data according to their size** 

![Image](https://github.com/emineeminesahin/DroneDetectionWithYOLO/blob/main/images/validation%20data.png)

**Distribution of 3100 bounding boxes in the validation data according to their size**

![Image](https://github.com/emineeminesahin/DroneDetectionWithYOLO/blob/main/images/mAp.png)

**mAp values og the models**

![Image](https://github.com/emineeminesahin/DroneDetectionWithYOLO/blob/main/images/f1-score.png)

**FPS values of the models**
