<div align="center">

  <h1>sports</h1>

</div>

### hello

In sports, every centimeter and every second matter. That’s why Roboflow uses sports as a proving ground to stress-test our object detection, segmentation, keypoint detection, and foundational models. This repository includes flexible, reusable tools that work in sports and many other fields.

### challenges

Are you passionate about both computer vision and sports? We invite contributions from anyone who shares that excitement! Together, we can create powerful open-source tools for sports analytics. Here are the core challenges we’re aiming to solve: 

Ball tracking: Tracking a fast, tiny ball across frames is extremely difficult due to rapid motion, small size, and frequent disappearance in high-resolution footage.
Reading jersey numbers: Jersey numbers are hard to read when players turn away, the video is blurry, or other players and objects block the view.
Player tracking: Keeping a consistent ID on each player is challenging because players constantly overlap, collide, and obstruct one another.
Player re-identification: Re-identifying players after they leave and re-enter the frame is tough—especially with moving cameras or visually similar players.
Camera calibration: Precise camera calibration is essential for advanced metrics like speed, movement, and distance, but sports environments make this complex due to shifting angles and dynamic motion.

## Install

pip install git+https://github.com/TheSaiEaranti/sportsvisualization.git

## datasets

| use case                               | dataset                                                                                                                                                           |
|:---------------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ⚽ soccer player detection              | [![Download Dataset](https://app.roboflow.com/images/download-dataset-badge.svg)](https://universe.roboflow.com/roboflow-jvuqo/football-players-detection-3zvbc)  |
| ⚽ soccer ball detection                | [![Download Dataset](https://app.roboflow.com/images/download-dataset-badge.svg)](https://universe.roboflow.com/roboflow-jvuqo/football-ball-detection-rejhg)     |
| ⚽ soccer pitch keypoint detection      | [![Download Dataset](https://app.roboflow.com/images/download-dataset-badge.svg)](https://universe.roboflow.com/roboflow-jvuqo/football-field-detection-f07vi)    |
| 🏀 basketball court keypoint detection | [![Download Dataset](https://app.roboflow.com/images/download-dataset-badge.svg)](https://universe.roboflow.com/roboflow-jvuqo/basketball-court-detection-2)      |
| 🏀 basketball jersey numbers ocr       | [![Download Dataset](https://app.roboflow.com/images/download-dataset-badge.svg)](https://universe.roboflow.com/roboflow-jvuqo/basketball-jersey-numbers-ocr)     |


### demos

https://github.com/roboflow/sports/assets/26109316/7ad414dd-cc4e-476d-9af3-02dfdf029205
