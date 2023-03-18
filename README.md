# Patient-Doctor-Sentiment-Analysis

Click [here][92] to download image data

* The purpose of the program

Depending on people's behaviors, physical characteristics and verbal sentence structures
Developed biometric systems have been actively used in recent years. The uniqueness of the person
Biometric systems based on facial recognition do not require physical contact.
It occupies an important place because it is inaudible. In this study, deep learning-based facial
Realized and adapted recognition and facial expression recognition application for TIP

* Solution of the problem

I identified two different methods to solve the problem. The first method
Facial expression recognition takes advantage of facial distinctive features. These features
The area where it is located is the mouth and lip area, eyes and eyelids. basic of people
There are 6 emotions expressed as: happiness, sadness, surprise, fear,
anger and disgust. The second method is derived from the speech signal in my studies.
Features include filter banks, spectral frequencies, energy, zero-pass ratio,
There is low and high frequency energy and fundamental frequency.

* Comments and suggestions

In case this project is used in the field of medicine, the doctor during the online meeting with the patient
to take a stand according to the mood of the patient and to keep the patient away from misleading elements in the diagnosis of the disease.
could be cleaned. As a suggestion, the datasets and images used can be reproduced.
The trained data and the tested data are compared and it is seen again how successful the system is.
 
 ##
 
Below are the steps you need to do to get it running

#### Step 1 : Clone the repo and Navigate to Python Application

`git clone https://github.com/asimodabas/Patient-Doctor-Sentiment-Analysis.git`

#### Step 2: install OpenCV for python

`pip install opencv-python`

#### Step 3: install NumPy for python

`pip install numpy`

#### 

```
For sentiment analysis with audio : python SentimentAnalysis.py
```

```
For sentiment analysis with Realtime : python SentimentRealtimeAnalysis.py
```

Libraries Used
--------------
  * [Model saving & serialization APIs][10] - Loads a model saved via model.save().
  * [Time & Sleep][14] - Python has built-in support for putting your program to sleep. The time module has a function sleep() that you can use to suspend execution of the calling thread for however many seconds you specify. 
  * [Image data preprocessing][18] - RThe acquired data are usually messy and come from different sources. To feed them to the Machine Learning model (or neural network), they need to be standardized and cleaned up.
  * [OpenCV][17] - It is a large open source library used for applications such as image processing, machine computers, image processing, video analysis. It plays a very important role in real transitions.
  * [NumPy][90] - NumPy is a Python library for working with arrays. It also has the necessary functions for working in the field of linear algebra, Fourier transform and matrices.
  * [SpeechRecognition][91] - Speech recognition and text-to-text program Speech recognition, or speech-to-text, is the process by which a device or program identifies words spoken aloud and converts them into readable text.
  
  [10]: https://keras.io/api/models/model_saving_apis/
  [14]: https://realpython.com/python-sleep/
  [18]: https://www.kaggle.com/code/khotijahs1/cv-image-preprocessing
  [17]: https://pypi.org/project/opencv-python/
  [90]: https://numpy.org/
  [91]: https://pypi.org/project/SpeechRecognition/
  [92]: https://wetransfer.com/downloads/b91a2a2c8a3a7e93ace0d7f34523177220230318022616/4c892b9c1f99eabe12a226ad7fbf294520230318022653/3c4804?trk=TRN_TDL_01&utm_campaign=TRN_TDL_01&utm_medium=email&utm_source=sendgrid
