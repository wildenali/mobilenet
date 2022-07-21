1. Create virtual environment
    - virtualenv env
    - env\Scripts\activate

2. Install dependecies
    - pip install -r requirements.txt

3. Run Script
    - python mobilenet_ssd_video.py --prototxt MobileNetSSD_deploy.prototxt --weights MobileNetSSD_deploy.caffemodel
    - python sample_img.py --prototxt MobileNetSSD_deploy.prototxt --weights MobileNetSSD_deploy.caffemodel

source:
https://github.com/djmv/MobilNet_SSD_opencv
https://ebenezertechs.com/mobilenet-ssd-using-opencv-3-4-1-deep-learning-module-python/