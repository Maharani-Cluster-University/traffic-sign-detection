# Traffic-Sign-Recognition-Using-YOLO

This repository contains model and training notebook for traffic sign recognition

## Dataset
The dataset used for training is [German Traffic Sign Recognition Benchmark (GTSRB)](https://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset) containing 43 classes of traffic signs. The training set contains 39209 labeled images and the test set contains 12630 unlabelled images.

![image](https://user-images.githubusercontent.com/35000278/116809754-50276780-ab5d-11eb-87fa-1f513be1f876.png)

## Model

Using and YOLOv5 for training and achieved >93% mAP on the dataset.

![image](https://user-images.githubusercontent.com/35000278/116809984-cd071100-ab5e-11eb-8789-29afd40c0094.png)

## Report

Used [WandB](https://wandb.ai/mdhamani/YOLOv5) to log hyperparameters and output metrics from runs. 

Download the [model](https://mega.nz/file/rV4HDQ5b#UfgDAMlVHvfzSr7PquE8HWx_6jhRmDUGBS-qyfIn_oE)

#create a virtual environment


STEPS: ------------------------
 STEP 1 : Clone 
 STEP 2 : cd project-folder/yolov5
 STEP 3 : python -m venv venv  #create virtual environment
 STEP 4 : pip install torch
          pip install ultralytics
 STEP 4 : source venv/bin/activate  #activate virtual environment
 STEP 5 : any error modulenot found try pip install `module`
 STEP 5 : python detect.py #Run python file


