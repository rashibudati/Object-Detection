# Object-Detection
A simple experiment to practice object detection via webcam using YOLO2. 

# Video analysis demo

## Requirements

### Python
* openCV with video support ([Instruction](https://docs.opencv.org/trunk/d7/d9f/tutorial_linux_install.html))
* tensorflow ([Instruction](https://www.tensorflow.org/install/install_linux))
* pafy (for direct video links)


All requirements are listed in [requirements](requirements.txt) file, 
So  all required packages can be installed by _pip_

**Update:** Since [this](https://github.com/skvark/opencv-python/releases/tag/11) release opencv-python ships with FFmpeg, V4L and V4L2. So i have added it to [requirements](requirements.txt).
```bash
pip install -r requirements.txt
```

### Models data
* download and extract [data.tar.gz](https://s3.amazonaws.com/video-analysis-demo/data.tar.gz) to source folder

## Running

### Local demo
To evaluate video file run
```bash
python eval.py 

