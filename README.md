# CheckingPneumonia
We use Convolutional Neural Networks to check wether someone has Pneumonia or not. For getting high accuracy Transfer Learning has been used. The model has been built using Tensorflow and Keras, and to know more please take a look at the documentation of Keras. 
The Pretrained model is InceptionResnetV2 and a few layers have been added to the top of our pre trained model. 
This is done in order to improve our accuracy. 
Future Improvements involve taking care of precision and recall since my model has almost 79 false positives which might be bad for the particular application. 
The final results are shown as plotted images with their results written below them, A confusion matrix has also been plotted to see how well the model performs. 
The dataset was taken from Kaggle:
https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

