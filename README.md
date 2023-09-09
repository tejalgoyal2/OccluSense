# OccluSense : Occluded-Object-Detection-for-Autonomous-Vehicles
Autonomous vehicles are the future of transportation, but safety and full autonomy are still evolving. Our study focuses on occluded object detection to enhance AV perception. We trained the YOLOv5 model using transfer learning, utilizing pre-trained weights from the COCO dataset, on a new dataset from Bangladesh.


# Methodology
![image](https://github.com/tejalgoyal2/Occluded-Object-Detection-for-Autonomous-Vehicles/assets/132282123/9a0711ab-3888-42c6-ac1c-b91065b1a028)
- Obtain data
- Annotate images with occluded instances
- Split dataset into train, validation, and test sets
- Preprocess and augment images
- Train three models and tune parameters
- Evaluate and compare results using the test sample
- Refer to figure for an overview of the proposed methodology\
\
\
(The data augmentation was done using [Roboflow](https://universe.roboflow.com))

# Dataset
Used YOLOv5 - small model on pretrained COCO Dataset and done further training on our own dataset.\
Our dataset can be downloaded from Google drive by clicking [here.](https://drive.google.com/file/d/1uLjJvOHPyU1gb2R5FV-6WhzXucuAMAv8/view?usp=share_link)

## The YOLOv5 repository can be cloned from [ultralytics-yolov5](https://github.com/ultralytics/yolov5)

# Performance

![image](https://github.com/tejalgoyal2/Occluded-Object-Detection-for-Autonomous-Vehicles/assets/132282123/2a38d3a6-2e0f-41cd-8b37-7325058932c4)
![image](https://github.com/tejalgoyal2/Occluded-Object-Detection-for-Autonomous-Vehicles/assets/132282123/19b7a1d8-87cc-4563-9c41-9c1748fde890)
![image](https://github.com/tejalgoyal2/Occluded-Object-Detection-for-Autonomous-Vehicles/assets/132282123/10674303-aec7-4923-8cc3-b12de5401476)
(You can also see these on tensor board by downloading the ipynb file and opening it in jupyter or colab - for some reason git is not showing these graph if we open it)



# Research Papers
T. Mostafa, S. J. Chowdhury, M. K. Rhaman and M. G. R. Alam, "Occluded Object Detection for Autonomous Vehicles Employing YOLOv5, YOLOX and Faster R-CNN," 2022 IEEE 13th Annual Information Technology, Electronics and Mobile Communication Conference (IEMCON), Vancouver, BC, Canada, 2022, pp. 0405-0410, doi: 10.1109/IEMCON56893.2022.9946565.
