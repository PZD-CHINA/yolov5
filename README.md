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
Training results on valid set: 
![result](./assets/training_result.jpg "result")
Metrics:
![conf](./assets/confusion_matrix.png "conf")

## Inference with `detect.py`
`detect.py` runs inference on a variety of sources.
```bash
python detect.py --weights [path-to-model] --source [path-to-file] 
```

| Input Image | Result Image |
| --- | --- |
| ![infer](./assets/infer.jpg "infer") | ![result](./assets/result.jpg "result") |

## Reference 
- [YOLOv5](https://github.com/ultralytics/yolov5)