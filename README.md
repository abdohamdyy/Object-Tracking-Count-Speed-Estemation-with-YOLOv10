# Object-Tracking-Count-Speed-Estemation-with-YOLOv10

This repository contains a Python script that leverages YOLOv10 for object tracking, counting, and speed estimation in a video. The code is designed to run in a Google Colab notebook, and it uses the `ultralytics` library along with `supervision` to process and analyze video frames in real-time.

## Overview

The project uses YOLOv10, a powerful object detection model, to identify and track objects in a video stream. Additionally, it calculates the speed of tracked objects by measuring the time they take to travel between two horizontal lines placed in the video.

### Key Features

- **Object Detection:** YOLOv10 model is used for detecting objects within the video frames.
- **Object Tracking:** The `ByteTrack` tracker is utilized for persistent tracking of detected objects across frames.
- **Speed Estimation:** Speed is calculated based on the time taken by objects to cross predefined lines in the video.

## Installation

To run the code, you need to install the required libraries. Use the following command to install the necessary dependencies:

```bash
!pip install -q supervision ultralytics
```

## Usage

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/Object-Tracking-Count-Speed-Estimation-with-YOLOv10.git
   ```

2. **Upload to Google Colab:**

   You can upload the notebook from this repository directly into Google Colab for easy execution.

3. **Prepare your video:**

   Place your target video in the appropriate directory. Update the `Video_Path` and `target_video` variables in the script with the correct paths.

4. **Run the script:**

   Execute the code in the notebook. The script will process the video, track the objects, and estimate their speeds.

   - The video is annotated with bounding boxes and speed labels.
   - The output video is saved at the specified `target_video` path.

5. **Analyze the results:**

   The processed video with annotations will be saved and can be reviewed to analyze object movements and speeds.

## Code Explanation

For a detailed walkthrough of the code, you can watch the explanation video on YouTube: [Code Explanation Video](https://www.youtube.com/watch?v=jJXK1Q-tQZg&t=167s)


## Contribution

Feel free to fork this repository and submit pull requests. Any contributions to improve the performance, accuracy, or functionality of the code are welcome.
