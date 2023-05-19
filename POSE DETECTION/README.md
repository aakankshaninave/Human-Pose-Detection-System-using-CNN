#Human Action/Pose Detection System


This is a group project for Continuous Assesment at DIEMS. We have used openCV2 to perform live predictions on live data.


## Model Description

**Overview**
Human Pose estimation is a computer vision task that represents the orientation of a person in a graphical format. This technique is widely applied to predict a person’s body parts or joint position. It is one of the most exciting areas of research in computer vision that has gained a lot of traction because of its abundance of applications that can benefit from such a technology.

Detection of people has long been a primary centre of discussion for various applications in traditional object detection. With recent developments in machine-learning algorithms, computers can now understand human body language by performing pose detection and pose tracking. The accuracy of these detections and the hardware requirements to run them has now reached a point where it has become commercially viable.

**Understanding the Data**

About Dataset
Context
Yoga is a very well-known practice to curb anxiety and relieve stress. There are many yoga poses but the very well-known ones are the downward dog pose, goddess pose, tree pose, plank pose and the warrior pose. Smart technology can be used to classify between them.

Content
The dataset is divided into train and test subdirectories, with 5 sub folders in each directory corresponding to the 5 classes of yoga poses. The images are extracted from bing using their API functionality so they may not be very accurate (watermarks, text may exist)

Inspiration
I was working on a project that instructs users how to perform a yoga pose and wanted to train a classifier for the same. That is what lead to scraping of the images. I hope it will be useful.

**Model Fitting :** During the modeling process, we choose multiple different evaluation metrics to evaluate the performance of models based on the nature of our data:

The dataset is divided into TRAIN,TEST sub directories for easy access. The train-test split after extraction was done was 70-30.


## DeepLearning Approach

Pose Detection On Real-Time Webcam Feed using opencv also using classification.
The results on the images were pretty good, now we will try the function on a real-time webcam feed and a video. Depending upon whether you want to run pose detection on a video stored in the disk or on the webcam feed, you can comment and uncomment the initialization code of the VideoCapture object accordingly.



## Dependencies

All you need is Google Colab or JuypterNoteBook or VSCode and the required dataset to execute this on device.