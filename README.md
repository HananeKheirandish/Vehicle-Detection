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

![112](https://github.com/HananeKheirandish/Vehicle-Detection/assets/76804160/1cb57464-416f-490d-9723-428a421ccdaa)

![126](https://github.com/HananeKheirandish/Vehicle-Detection/assets/76804160/804c512c-4517-4920-b0cd-e4d3113acf61)
![121](https://github.com/HananeKheirandish/Vehicle-Detection/assets/76804160/0b8adf21-ff9d-40f3-b309-f57d2bfa3923)
