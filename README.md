Drowsiness Detection System
Overview
This project is designed to detect drowsiness in individuals, especially those operating vehicles or machinery. It utilizes computer vision techniques to analyze eye movements and determine if a person's eyes are open or closed. If signs of drowsiness are detected, the system triggers an alarm to alert the individual.

Dataset
The project uses the MRL dataset for training the drowsiness detection model. You can access the dataset through this link.(http://mrl.cs.vsb.cz/eyedataset)

Model
Achieved an impressive 94.6% accuracy using InceptionV3 as the Base model.

To run the drowsiness detection system, you need to install several dependencies. Use the following commands:

Copy code
pip install sklearn
pip install -U scikit-learn 
pip install pillow
Main File
The core functionality of the system is implemented in the main file. This file captures video from the camera, processes the frames, and analyzes eye movements to detect drowsiness. The system utilizes the InceptionV3 model for eye movement analysis.

App Code
The app code uses the Pygame library to play an alarm sound when drowsiness is detected. It also integrates with OpenCV for video capture and processing.

Layman Explanation
The drowsiness detection system works like an extra set of eyes for people who might feel sleepy while driving or working. It continuously watches their eyes through a camera. If it notices that their eyes are closing too often, it sounds an alarm to wake them up and prevent accidents.

The system learns from many examples of open and closed eyes to understand the difference. It keeps track of how often the person's eyes are closed, and if it notices they're closing too much, it makes a noise to alert them.

Overall, it's like having a helpful friend in the car or workplace who reminds you to stay awake and alert.