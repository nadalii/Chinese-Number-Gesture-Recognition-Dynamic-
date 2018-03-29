# Chinese-Number-Gesture-Recognition-Dynamic-
This is the second of my Chinese Number Gesture Recognition project, the objects we detected in this repository are gestures represented by static images.

In this repository, I constructed a Conv3D neural network by myself to detect both static and dynamic gestures. The main idea of my project is using fixed serial of images (frames) to represent a move (dynamic gesture). Therefore, the input of my network should be a 5-dimension array, that's the reason why I choose conv3d. There are 20 classes shows the number gestures from 0 to 100 (the standard sample is given in main folder). The data of this part is collected by myself as well, it contains both simple background and complex background.

My model is in "Conv3D.ipynb" and I also create "EvaluateConv3D.ipynb" to evaluate the preformance of this model on test data. All procession is running on GPU device. It preforms well so far and I'm still updating my dataset to make my model more rubsty.
