# Emotion_Recognition--Neural-Networks::[68.68% Validation Accuracy]
Human facial expressions can be easily classified into 7 basic emotions: happy, sad, surprise, fear, anger, disgust, and neutral. Our facial emotions are expressed through activation of specific sets of facial muscles.
* The aim is to classify the emotion on a person's face into one of **seven categories**, using deep convolutional neural networks.
* The algorithm is based on the type of database used inorder to get maximium validation accuracy. Further changes in algorithm may be required according to the database used.

# Dependencies
1. NumPy
2. Keras
3. Pandas
4. Tensorflow (as backend)
5. Jupyter
6. openCv2

# Components
* Download the fer2013.tar.gz file from [here](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data)
* Move the downloaded file to the datasets directory inside this repository.
* Trained model Face Detcection -> [haarcascade_frontalface_default.xml](https://github.com/piyush2896/Facial-Expression-Recognition-Challenge/blob/master/face_model.h5)
* Trained model JSON -> [model1.h5](https://github.com/shreyashk09/Emotion-Recognition---Neural-Networks/blob/master/model1.json)

# Methedology


# Application in Action
* To see the applicaion in action, by using pretrained JSON model, run the code [App_Interface](https://github.com/shreyashk09/Emotion-Recognition---Neural-Networks/blob/master/Interface.py)
* To train the model using the database and see the results in step by step, run the code blocks in the [Emotion Recognition - Neural Networks-part2.ipynb](https://github.com/shreyashk09/Emotion-Recognition---Neural-Networks)

