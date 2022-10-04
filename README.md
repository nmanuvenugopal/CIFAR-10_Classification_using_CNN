# CIFAR-10_Classification_using_CNN
Implemented a CNN model to classify the objects to 10 different classes

1. Plotted the graph for loss and validation loss.
2. Prevented the overfitting by using Earlystopping with patience of 2.

![image](https://user-images.githubusercontent.com/99719105/193788460-2a5d29c1-1e1c-4bf5-82ba-7709039060c2.png)

3. Plotted the grapbh between the accuracy and validation accuracy.
![image](https://user-images.githubusercontent.com/99719105/193788910-d5ae2fbd-d166-41fd-9d2c-716eb6329552.png)

4. Attained a accuracy of 70 percent approximtely. Same have been validated with means of Classification report
![image](https://user-images.githubusercontent.com/99719105/193789209-090a1980-fe79-4602-9154-061a79a77316.png)

5. Plotted the confusion matrix to see for which class the model is performing prediction better and poor.
![image](https://user-images.githubusercontent.com/99719105/193789575-692880be-607e-4f27-9a66-99ba2bc8122e.png)


5. Important Note: tensorflow\python\keras\engine\sequential.py:455: UserWarning: model.predict_classes() is deprecated and will be removed after 2021-01-01. Please use instead:* np.argmax(model.predict(x), axis=-1), if your model does multi-class classification (e.g. if it uses a softmax last-layer activation).* (model.predict(x) > 0.5).astype("int32"), if your model does binary classification (e.g. if it uses a sigmoid last-layer activation).
ref: https://stackoverflow.com/questions/68836551/keras-attributeerror-sequential-object-has-no-attribute-predict-classes


