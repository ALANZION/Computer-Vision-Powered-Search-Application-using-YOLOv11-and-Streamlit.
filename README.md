# Computer-Vision-Powered-Search-Application-using-YOLOv11-and-Streamlit.

## Aim
To design and develop a Computer Vision Powered Search Application that utilizes deep learning (YOLOv11) to index local image repositories, detect objects within images, and enable users to perform semantic searches (e.g., finding all images containing a "truck" or "person") through an interactive web-based dashboard.

## Requirements
```
ultralytics
streamlit
opencv-python
pyyaml
torch
torchvision
pillow
pandas
numpy
```
## Libraries & Frameworks
```
Deep Learning: ultralytics (YOLOv11), torch, torchvision
Web Framework: streamlit
Image Processing: opencv-python, pillow
Data Handling: pandas, numpy
Utilities: pyyaml
```
## Environment Setup

# Create the environment
conda create -n yolo_image_search_gpu python=3.11 -y

# Activate the environment
conda activate yolo_image_search_gpu

# Install PyTorch with CUDA support
conda install pytorch==2.5.1 torchvision==0.20.1 pytorch-cuda=12.4 -c pytorch -c nvidia

# Install remaining dependencies
pip install -r requirements.txt

