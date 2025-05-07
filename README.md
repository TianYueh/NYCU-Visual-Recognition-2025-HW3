# NYCU Computer Vision 2025 Spring HW3  
Student ID: 110550085  
Name: 房天越  
## Introduction
This is the third Homework of NYCU Visual Recognition using Deep Learning.  
In this project, we need to use ResNetXX-FPN as backbone, and use MaskRCNN to improve its performance.  
In my implementation, I applied ResNet50-FPN, and basic MaskRCNN from torchvision.  
## How to install  
First, install anaconda and create a virtual environment, the name is cvhw3 for example.  
```
conda create -n cvhw3 python=3.9 -y
```
Second, activate the virtual environment  
```
conda activate cvhw3
```
Third, install the dependencies in requirements.txt.  
```
pip install -r requirements.txt
```
Fourth, run the training code. You can also modify the parameters in the code.  
```
python training.py
```
Fifth, run the inference code, you can also modify the threshold or some other parameters.  
```
python inference.py
```
## Performance Snapshot
The final result is quite bad, I stuck at some mysterious bugs for three days...
<img width="1037" alt="截圖 2025-05-07 晚上10 45 25" src="https://github.com/user-attachments/assets/66c37772-e24f-4ee5-b651-e9d4ae9ee04a" />

