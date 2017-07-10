[//]: # (Image References)

[image1]: ./images/obamas_with_keypoints.png "Facial Keypoint Detection"

## Facial Keypoint Detection (work in progress)

In this project, I combine my knowledge of computer vision techniques and deep learning to build an end-to-end facial keypoint recognition system. Facial keypoints include points around the eyes, nose, and mouth on any face and are used in many applications, from facial tracking to emotion recognition. My completed solution can take in any image containing faces and identify the location of each face and their facial keypoints, as shown below.

![Facial Keypoint Detection][image1]

The project is broken up into a few main parts in one Jupyter notebook:

__Part 1__ : Investigating OpenCV, pre-processing, and face detection

__Part 2__ : Training a Convolutional Neural Network (CNN) to detect facial keypoints

__Part 3__ : Putting parts 1 and 2 together to identify facial keypoints on any image!


### Data

I am using the facial keypoints detection dataset from Kaggle. The training and test set are already uploaded to the subdirectory `data`.


#### Step 1:  Face detection and Eye detection
Implement face and eye detection.

#### Step 2: De-noise an image for better face detection
De-noise an image for better face detection.

#### Step 3: Canny Edge Detection and Gaussian Blur
Blur and edge detect a test image.

#### Step 4: Automatically hide the identity of a person (blur a face)
Automatically detect the face of a person in a test image, then blur their face to mask their identity.

#### Step 5:  Build a Convolutional Neural Network (CNN)
Design a convolutional network architecture for learning correspondence between input faces and facial keypoints.
Compile and train the CNN on the dataset.
Visualize the loss function.

#### Step 6:  Complete a facial keypoints detector and complete the CV pipeline
Combine OpenCV face detection with trained convnet facial keypoint detector to detect facial keypoints on any image
that contains one or multiple human faces.
