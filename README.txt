CIFAR-10 is an established computer-vision dataset used for object recognition. It is a subset of the 80 million tiny images dataset and consists of 60,000 32x32 color images containing one of 10 object classes, with 6000 images per class. There are 50000 training images and 10000 test images.
I downloaded this cifar10 dataset from Keras datasets directly. Here Convolutional Neural Network (CNN) is used for this object(image) recognition project.

Results:

Epoch 12/15
50000/50000 [==============================] - 63s 1ms/step - loss: 0.5809 - acc: 0.7916 - val_loss: 0.9633 - val_acc: 0.6944
Epoch 00012: early stopping


-------------------------------------------------


precision    recall  f1-score   support

          0       0.75      0.74      0.75      1000
          1       0.86      0.81      0.83      1000
          2       0.62      0.50      0.55      1000
          3       0.49      0.48      0.49      1000
          4       0.57      0.71      0.63      1000
          5       0.58      0.61      0.59      1000
          6       0.72      0.82      0.76      1000
          7       0.80      0.69      0.74      1000
          8       0.80      0.79      0.79      1000
          9       0.80      0.80      0.80      1000

avg / total       0.70      0.69      0.69     10000



