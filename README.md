
# DogVsCatClassifier
Classifies Dogs and Cats where (0)--->CATS  and (1)----->DOGS
# The Libraries Included
1. TensorFlow
2. Keras
3. Matplotlib
4. ComputerVision
# Data Collection
1. I collected the data from Kaggle so their is no need to clean or pre process it.It already doner by some other person.
# Model Fitting
With the help of tensorflow and keras we added a layers to CNN First is Convo2D, MaxPooling2D,Flatten,Dense
Since the data is very Large it can't be applied directly top machine ,so we divide it to batches of each of size 32.
And There was images around 20000 in training. so 20000/32 i.e 625 batches.
And then we add the layers.
and then we compile and train the model with 10 **epoch**. Since the first epoch give  less accuracy but as we continue and in the 10th epoch the accuracy become very high.
# Model Testing
Now we take some data From internet And Put with the help of cv2 there
Now model predicted the data.
![ss8](https://github.com/deepakgwalani1999/DogVsCatClassifier/assets/47658896/a124ed80-362e-4b0d-a040-c71a7ea01476)
![ss9](https://github.com/deepakgwalani1999/DogVsCatClassifier/assets/47658896/3a6f86bd-b803-443d-b619-573b498398e6)
![ss10](https://github.com/deepakgwalani1999/DogVsCatClassifier/assets/47658896/f2345ee7-78e6-43b5-8ec9-c9838361bdb1)
![ss11](https://github.com/deepakgwalani1999/DogVsCatClassifier/assets/47658896/3ea09aea-74ab-42a2-b29b-c5b2108f733f)




