# Traffic-Sign-Recognition
Refer this link to under stand the basic working of the project. \
1. https://www.computervision.zone/courses/traffic-sign-classification/ 
2. https://sid.erda.dk/public/archives/daaeac0d7ce1152aea9b61d9f1e19370/published-archive.html 

Note: There have been a number of changes made to the project; it is not an exact replica of the one stated above. In contrast to the reference project, which uses Pickle to store its module files, this project utilises HDF5 (Hierarchical Data Format), a more recent Python package, to preserve its trained modules and integrate it with the most recent version of Python. \

A voice announcement function in _voicePrompt.py_ announces the identified traffic song. \

# Download the following Modules and Packages
1. pip install numpy 
2. pip install pandas 
3. pip install opencv-python
4. pip install keras
5. pip install tesorflow
6. pip install matplotlib
7. pip install cv2
8. pip install h5py
9. pip install pyttsx3
`````
The project is focused on training and classifying traffic signs using Convolutional Neural Networks (CNNs). The classification is done in real-time using a simple webcam and OpenCV library. CNNs are known for their ability to effectively generalize and classify data with high accuracy, making them suitable for this task.\
\
The project involves training the CNN model using TensorFlow and Keras frameworks. The training data consists of over 35,000 images of 43 different classes of traffic signs. The goal is to build a model that can accurately classify traffic signs based on their visual features.\
\
Overall, the project aims to empower individuals to develop robust traffic sign classification models using CNNs and provides insights into the training process and data requirements for achieving accurate results.\
`````
