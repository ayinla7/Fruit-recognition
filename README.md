# Fruit-recognition
Recognition of images of fruits using Convolutional Neural Network (CNN) with 97.75% Accuracy.


APPLICATION OF ARTIFICIAL NEURAL NETWORK IN FRUITS AND VEGETABLES RECOGNITION USING CONVOLUTIONAL NEUTRAL NETWORK
BY AYINLA KWAMDEEN OLAMILEKAN – 11562036
Ayinlak@uni.coventry.ac.uk
A machine that is able to identify fruits and vegetables correctly can be useful for Mainstream farmers and food processing Industries as it would help speed up rate of Identifying/grouping fruits during production. Artificial neural network can be used to classify and predict fruits as they are entered into the machine. 
Using a dataset containing total of 90483 images of sample fruits and vegetables of 131 Classes (Fruit types), Training set size is 67692 images, while Test set contains 22688 images (one fruit or vegetable per image), also all Image are 100x100 pixels in size. All files are about 1.3GB in size.
Dataset can be accessed on Kaggle via - https://www.kaggle.com/moltean/fruits
AIM
In a large dataset containing variety of Fruits and Vegetable, the Aim is to get a machine that is able to predict correctly and recognize the type of fruit that is inputted.  
TASKS
For object identification/detection, Classification would be used to allow the machine learn the features of inputs and be able to identify them using Prediction. All these will be achieved using deep neural networks Architecture, Convolutional Neural network. 
ARCHITECTURE
Convolutional neural network architecture is a Feedforward network architecture used for computer vision that allows machine to analyze visual images. 
Each input image goes through Convolutional layer, filters and pooling layer before activation function will classify output in probabilities. Using its Pooling Layer to simplify inputs from Convolution layer and reduces parameters for better processing of complex images.
ReLU would be used as its Activation Function.
Five Steps would be followed, which includes, Data reading, data pre-processing, creating a CNN model, Learning the model parameters and Evaluation (Prediction).
RELATED ISSUES
•	A CNN is relatively slower compared to other Architectures. 
•	Having several layers for training process takes a lot of time if the computer doesn’t have a good Graphics processing unit (GPU).
