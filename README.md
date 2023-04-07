# Handwritten-Character-and-digit-recgnition-along-with-sing-language-recognition
This project is designed to help blind and deaf lead an eassier life while doing real time detection.
Right now the focus is now doing detection on input image but will soon do detection using camera.
In this project, user can upload image of digit/character/sign language and the program will recognise it and give an ouput as audio for digit and character for the blind

The Jupyter notebook contains code for Multitudinous Object Detection, which is a Python-based application that detects multiple objects present in an image and also performs sign language recognition. It is a graphical user interface (GUI) application that displays the results of object detection and sign language recognition on the screen.

Libraries Used
The following libraries were used in this project:

tkinter
PIL
cv2
keras
tensorflow
random
google_trans_new
gtts
IPython.display
pygame
Files
The following files are used in this project:

sl_keras_model.h5 - trained model to classify sign language
char_model.h5 - trained model to recognize English characters
model_digit.h5 - trained model to recognize digits
Usage
To use this application:

Clone this repository and open the Jupyter notebook in Jupyter Notebook or Jupyter Lab.
Run the notebook cell-by-cell using "Shift+Enter".
Select an image file for object detection.
The application will detect the objects present in the image and show them on the screen.
Use the button "Recognize Sign Language" to perform sign language recognition on the image.
The application will display the recognized sign language character.
Use the button "Recognize Text" to perform character and digit recognition on the image.
The application will display the recognized characters or digits on the screen.
You can use the button "Text to Speech" to convert the recognized text to speech.
Note: The application might take some time to detect objects and perform recognition depending on the size and complexity of the input image.
