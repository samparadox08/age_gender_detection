# age_gender_detection
# Objective :
To build a gender and age detector that can approximately guess the gender and age of the person (face) in a picture or through webcam.

# About the Project :
In this Python Project, I had used Deep Learning to accurately identify the gender and age of a person from a single image of a face. I used the models trained by Tal Hassner and Gil Levi. The predicted gender may be one of ‘Male’ and ‘Female’, and the predicted age may be one of the following ranges- (0 – 2), (4 – 6), (8 – 12), (15 – 20), (25 – 32), (38 – 43), (48 – 53), (60 – 100) (8 nodes in the final softmax layer). It is very difficult to accurately guess an exact age from a single image because of factors like makeup, lighting, obstructions, and facial expressions. And so, I made this a classification problem instead of making it one of regression.

# Dataset :
For this python project, I had used the Adience dataset; the dataset is available in the public domain and you can find it here. This dataset serves as a benchmark for face photos and is inclusive of various real-world imaging conditions like noise, lighting, pose, and appearance. The images have been collected from Flickr albums and distributed under the Creative Commons (CC) license. It has a total of 26,580 photos of 2,284 subjects in eight age ranges (as mentioned above) and is about 1GB in size. The models I used had been trained on this dataset.

# Additional Python Libraries Required :
# OpenCV
   pip install opencv-python
# argparse
   pip install argparse

# Steps-To-Follow:
Clone the repository:
   git clone https://github.com/samparadox08/age_gender_detection.git

Open your Command Prompt or Terminal and change directory to the folder where all the files are present.

Detecting Gender and Age of face in Image Use Command :
   
   python detect.py --image <image_name>

Note: The Image should be present in same folder where all the files are present.

Detecting Gender and Age of face through webcam Use Command :
  
  python detect.py

Press Ctrl + C to stop the program execution.
