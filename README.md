# yolo-license-plate-detection

Inspiration

 [![Inspiration](https://img.youtube.com/vi/NXjCJZxeaQA/0.jpg)](https://www.youtube.com/watch?v=NXjCJZxeaQA)

Forked from [this repository](https://github.com/alitourani/yolo-license-plate-detection).

## 🔨 Environment

- Python 3.10
- You Only Look Once (YOLO) v.3
- requirements.txt

## Execution

You can download the weights file from [this](https://drive.google.com/file/d/1vXjIoRWY0aIpYfhj3TnPUGdmJoHnWaOc/ "this") link.

### Test on a single image:

```
python plate_detector_main.py --image=bird.jpg
```

### Test on an images directory:

```
python plate_detector_main.py --image-dir=./image-directory
```

### Test on a single video file:

```
python plate_detector_main.py --video=cars.mp4
```

### Test on the webcam:

```
python plate_detector_main.py
```

