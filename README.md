# face-mask-detection

![images-500x500](https://user-images.githubusercontent.com/52111130/169091862-65a32f6f-bfe3-40d6-acdd-e70fd8973551.jpeg) 


In the phase of COVID-19 pandemic, it was declared by the World Health Organization (WHO) that the use of face mask is mandatory for the biosafety measure. It caused the problem for current face detection systems. From where the notion to create a system capable of checking whether a person is wearing mask or not arises.
From there I got the idea to build a simple model to detect wither a person is wearing mask or not. A classification model based on the MobileNet architecture and OpenCV’s face detector is used in order to the fulfilment of the project. The training is done over the dataset containing multiple images of faces with and without mask. The experimental result shows wither the human is wearing “mask” or “no mask”.


The basic requirements for the fulfilment of the project are :-
- TensorFlow>=1.15.2
- keras== 2.3.1
- imutils==0.5.3
- NumPy==1.18.2
- opencv-python==4.2.0.*
- matplotlib==3.2.1
- SciPy==1.4.1


The dataset consists of data in the form of two set of images. Masked images and non – mask images. There are in total 1915 images with the mask on and 1918 images without mask.
The dataset is taken from the Kaggle website as well as other open-source images and the model is trained over these images with varying angles and visualization in order to identify face with or without mask.
The dataset is pre-processed and converted into NumPy array format for the computation and uniformity purpose and the labels are converted into categorical values using labelBinarizer a One Hot Encoding method.

