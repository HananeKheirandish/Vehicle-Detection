## Vehicle Detection
I did this project with using Yolo Algorithm. In this project; five types of vehicles including cars, trucks, motorcycle, buses and bicycles have been identified.

## ***cloning & installing***
git clone https://github.com/HananeKheirandish/Vehicle-Detection  # clone

cd Vehicle-Detection

pip install -r requirements.txt  # install

## ***Train***
python  train.py  --img 640  --epochs 60  --data dataset.yaml  --weights yolov5l.pt  --batch-size 16

## ***Inference***
python detect.py --weights runs/train/exp3/weights/best.pt  --source test1.jpg

