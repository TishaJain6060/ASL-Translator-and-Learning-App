# ASL-Translator-and-Learning-App

This is an App that recognizes and responds to the American Sign Language. More than an app, it functions as a learning tool for speakers wishing to learn the language and even as a translation tool that converts ASL to english through YOLO object detection.

With rapid rise in technology, there has been an increasing sensitivty placed upon developing systems that aid people with disabilities better integrate and gel in our society. It can be quite diificulty, for instance, for deaf people or people with hearing impairment to communicate as sign langage is not a skill that the general public learns. So this project aim to bridge that gap by recognizing these different signs and communicating it to people who don’t know sign lanuage. The app responds to finger-spelling (spelling out words) to convey sentences. Outputs will be in form of images and vocal replies to accommodate user disabilites, if any.

# Steps involved

Capturing different hand sign images and segregating into training and testing dataset to train the model.
Each image received a region of interest (ROI) which contained the hand sign. To this, I applied Gaussian Blur to extract the image features.
Used Convolutional Neural Network (CNN) to build my model.
Converted input images to Grayscale and applied Gaussian Blur for prepreocessing the data.
Trained the model according to the different assigned values of each hand sign.

# Installing necessary libraries

For windows:

To get the text-to-speech output function

(To be executed in command prompt/cmt/terminal) <br />
pip install speechRecognition <br />
pip install pyttsx3 <br />
pip install pyaudio <br />

(If an issue occurs while installing PyAudio, use .whl file from link- <br />
https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio)

Or run the following: <br />
pip install pipwin <br />
pipwin install pyaudio <br />

Remaining libraries:

pip install numpy
pip install os-sys
pip install opencv-python
pip install tensorflow 
 or pip3 install --upgrade https://storage.googleapis.com/tensorflow/linux/cpu/tensorflow-0.8.0-cp34-cp34m-linux_x86_64.whl
PIL -> pip install Pillow


# Functions Performed

The app can respond to all 26 letters of the English alphabet and some common words such as Mother, Father, Friend, Hello, Thank you, Yes, No, I Love You, Hungry and so on.

# User Manual
To be inserted

# Youtube video
for complete demo, check out: https://www.youtube.com/watch?v=y31tFS5UqPU
