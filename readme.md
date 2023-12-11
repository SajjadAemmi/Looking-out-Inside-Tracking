# Looking-out Inside Tracking

Inside-out vs. outside-in tracking

![Inside-out vs. outside-in tracking](https://xinreality.com/mediawiki/images/5/5a/Inside_out_vs._outside_in_tracking.png)

Early Lighthouse prototype, an inside-out tracking system with 2-dimensional barcodes as fiducial markers.

![Early Lighthouse prototype, an inside-out tracking system with 2-dimensional barcodes as fiducial markers.](https://xinreality.com/mediawiki/images/c/cb/F2Ak4iE.jpg)


## 1. Camera Calibration

#### Install

Execute command below:
```
pip install numpy opencv-python
```

#### Run

Execute `camera_calibration.ipynb` notebook to get camera parameters e.g., **fovx**, **fovy**, **focalLength**, **principalPoint**, **aspectRatio**.


## 2. QRCode Detection

### Option 2.1. OpenCV QRCode Detector

#### Install

Execute command below:
```
pip install numpy opencv-python matplotlib
```

#### Run

Execute `qrcode_detector_opencv.ipynb` notebook to find qrcodes location in image

### Option 2.2. YOLOv8 QRCode Detector

#### Install

Install [QReader](https://pypi.org/project/qreader/)

Then execute command below:
```
pip install numpy opencv-python matplotlib
```

#### Run

Execute `qrcode_detector_opencv.ipynb` notebook to find qrcodes location in image
