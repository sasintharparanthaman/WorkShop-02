# WorkShop-02

# Real-Time Object Detection using YOLOv4 and OpenCV

This project demonstrates real-time object detection using the YOLOv4 (You Only Look Once) deep learning model with OpenCV and your webcam.

The script processes video frames in real time, detects objects using YOLOv4, and displays bounding boxes and labels for the detected items.

## Features

- Real-time object detection using webcam
- Pre-trained YOLOv4 model on COCO dataset (80 classes)
- Bounding boxes and confidence scores shown on screen

## Requirements

- Python 3.x
- OpenCV (`opencv-python`)
- NumPy

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/yolov4-realtime-detection.git
   cd yolov4-realtime-detection
   ```

2. Install required packages:

   ```bash
   pip install opencv-python numpy
   ```

3. Download the following files and place them in the project folder:

   - [yolov4.weights](https://pjreddie.com/media/files/yolov4.weights)
   - [yolov4.cfg](https://github.com/AlexeyAB/darknet/blob/master/cfg/yolov4.cfg)
   - [coco.names](https://github.com/pjreddie/darknet/blob/master/data/coco.names)

## Usage

Run the detection script:

```bash
python yolov4_realtime_detection.py
```

Press **`q`** to quit the application.

## Project Files

- `yolov4_realtime_detection.py` - Main Python script
- `yolov4.weights` - Pre-trained YOLOv4 weights
- `yolov4.cfg` - YOLOv4 configuration file
- `coco.names` - Class labels (COCO dataset)

## Example

When you run the script, a webcam window will open showing real-time detection with labeled bounding boxes.

*(Optional: Include a screenshot or gif here)*

## License

This project is open-source and available under the MIT License.

## Acknowledgments

- [YOLO by Joseph Redmon](https://pjreddie.com/darknet/yolo/)
- [OpenCV DNN Module](https://docs.opencv.org/)
