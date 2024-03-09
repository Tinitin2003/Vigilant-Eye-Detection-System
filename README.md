##Vigilant Eye Detection System
Overview
The Vigilant Eye Detection System is designed to monitor individuals for signs of drowsiness, particularly in situations where alertness is crucial, such as while operating vehicles or machinery. This system employs advanced computer vision techniques to analyze eye movements and ascertain whether an individual's eyes are open or closed. In the event of detecting signs of drowsiness, the system promptly triggers an alarm to alert the individual and prevent potential accidents.

Dataset
The project utilizes the MRL dataset for training the vigilant eye detection model. You can access the dataset through the following link: MRL Eye Dataset

Model
The system achieved an impressive 94.6% accuracy using the InceptionV3 model as its base model.

To run the vigilant eye detection system, it is necessary to install several dependencies. Execute the following commands:

bash
Copy code
pip install sklearn
pip install -U scikit-learn
pip install pillow
Main File
The core functionality of the system is implemented in the main file, which captures video from the camera, processes the frames, and analyzes eye movements to detect signs of drowsiness. The system utilizes the InceptionV3 model for comprehensive eye movement analysis.

App Code
The app code utilizes the Pygame library to play an alarm sound upon detecting drowsiness. It seamlessly integrates with OpenCV for video capture and processing.

Layman Explanation
The Vigilant Eye Detection System operates as an additional layer of safety for individuals who may experience drowsiness while driving or working. Essentially, it functions as a vigilant observer, continuously monitoring the individual's eyes through a camera feed. If it detects frequent instances of closed eyes, indicating drowsiness, it activates an alarm to awaken the individual and mitigate potential accidents.

The system learns from a diverse set of examples, distinguishing between open and closed eyes to effectively identify signs of drowsiness. By keeping track of the frequency of eye closures, it intervenes by sounding an alarm when necessary, akin to having a supportive companion in the vehicle or workplace reminding individuals to remain alert and attentive.
