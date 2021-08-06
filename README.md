# Sign language recognition using convolutional neural network

It is a deep learning model which can recognise real time sign gestures of Indian Sign Language and convert it into corresponding text.

## Prerequisites software & libraries for the sign language project are:
Google colab    
Python         
IDE (Jupyter)  
  
### Install the below libraries in the cmd terminal 
Numpy          - pip install numpy
cv2 (openCV)   - pip install opencv-python
Keras          - pip install keras
Tensorflow (as keras uses tensorflow in backend and for image preprocessing) - pip install tensorflow

#### Steps to run the real time sign gesture algorithm:

* Install the dependencies - cv2, Python(3.8), Numpy, Keras, IDE and Tensorflow.
* Download Dataset into drive.
* Run CNN_MODEL in colab.
* Download the finalmodel.h5.
* Open signrealtime file in and paste the link of the above file, and execute the code in Jupyter.

Execute sign_dataset_creation.ipynb to create dataset.
To train the model run CNN_MODEL in Google Colab [Google Colab](https://colab.research.google.com/notebooks/) and upload the created dataset into google drive.
Download the model from colab to obtain finalmodel.h5 file.

##### Note:
* The accuracy of the model may vary on executing the CNN_MODEL.ipynb in colab.
