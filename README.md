# Vehicle Cut-In Detection

This project was made by Ved Verma for Intel Unnati Industrial Training 2024.

## Description

A Python-based project that combines YOLO object detection and SORT tracking to identify and track vehicles. Calculates and estimates a time to collision. Ideal for enhancing road safety and autonomous driving applications.

## Installation

Use the following command to install the necessary packages

```bash
pip install -r requirements.txt
```

## Usage

In order to use the project for your input video. Change this code segment in `vcid.ipynb`:

```python
cap = cv2.VideoCapture('00000_1.mp4') 
```

## Output

A video file `output.mp4` will be generated in the project containing the output of the project.

## Sample Video and Ouput

[Sample Video](https://drive.google.com/file/d/1gjCVNPVE56zs3UaUrax2g6kNVNxnsZCc/view?usp=drive_link)

[Sample Output](https://drive.google.com/file/d/1Iq201GJsvFS0FZoLsjMwVbKi3hS1t749/view?usp=drive_link)

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.