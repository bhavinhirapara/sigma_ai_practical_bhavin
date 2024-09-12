# About
This repository contain yolo model finetuning and inferance code, Also contain motion detection using OpenCV and image segmentation usin pytoch deeplabv3 model.

# Usage
First clone this repo.
``` git clone https://github.com/bhavinhirapara/sigma_ai_practical_bhavin.git ```

Upload both .ipynb fine to google colab and exicute cell by cell

# Explaination
1. Yolo model finetuning (YOLO.ipynb): I load very simple and small cat and dog dataset from roboflow, Then load yolov8n.pt pre-trained model from ultralytics and finetune model on our dataset, Once training done I load trained model from local and infereance using 3 tesing images.

2. Motion detection (Motion_detection.ipynb): Firstly load video using Opencv to extract frame and store each extracted frame into list. Then use Opencv background substraction model for background substraction. Once done with background substraction I load deeplabv3 pytorch pre-trained model for image segmentation and display segmented image with color overlay.

# !Important!
1. Replace the required path for images and video
2. In Yolo, Configure the path of train and valid folder in data.yaml for finetuning.
