# Visual-Recognition-via-Vision-Language-Model-Transfer


## Claimed
Nanyang Technology University

## Version
Python 3.8

## Guides
### Env
Install pytorch 1.8.1 first, then install 1.7.1

***
-r requirements.txt
***
* This shall be the final env 'master'
### 0.1 version
Jan 16 23.  
Only train the Fast RCNN part first, on COCO2017. The environment 'ResNet50_RCNN' version is different due to the update. 
* still python 3.8
* torch==1.10
* torchvision==0.11.1
Using pre-trained [ResNet50.pth](https://download.pytorch.org/models/resnet50-19c8e357.pth), to train my ResNet50-FasterRCNN.pth
### 0.2 version
Jan 26.  
Full update for libs. Also making the coco dataset in this project.  
Project Folder  
└───the code notebook (.py / .ipynb)  
│  
└───COCOdataset2017     
    └───images  
    │   └───train  
    │   │    │   000000000009.jpg  
    │   │    │   000000000025.jpg  
    │   │    │   ...  
    │   └───val     
    │        │   000000000139.jpg  
    │        │   000000000285.jpg  
    │        │   ...  
    └───annotations  
        │   instances_train.json  
        │   instances_val.json  
```
pip install git+https://github.com/philferriere/cocoapi.git#egg=pycocotools^&subdirectory=PythonAPI
```
