# Dog Cat Detection with YOLOv5

Simple project that applied YOLOv5 in detection of dogs cats. See the [YOLOv5 Docs](https://docs.ultralytics.com/yolov5) for full documentation on training, testing and deployment.

## Environment and Dependencies
- Python 3.8

Install requirements
```bash
pip install -r requirements.txt
```

## Data
- Data used for this project can be found [here.](https://www.kaggle.com/datasets/andrewmvd/dog-and-cat-detection)

## Training
```bash
python train.py
```
the results are stored in ./runs/train/exp

Training results on valid set: 
![result](./runs/train/exp7/train_batch0.jpg "result")
Metrics:
![conf](./runs/train/exp7/labels_correlogram.jpg "conf")

## detect
`detect.py` runs inference on a variety of sources.
```bash
python detect.py  --source [path-to-file] 
```

| Input Image | Result Image |
| --- | --- |
| ![infer](./assets/infer.jpg "infer") | ![result](./assets/result.jpg "result") |
| ![infer](./assets/infer.jpg "infer") | ![result](./assets/result.jpg "result") |

## Reference 
- [YOLOv5](https://github.com/ultralytics/yolov5)