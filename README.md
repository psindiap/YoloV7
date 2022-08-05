# Training a YoloV7 model on a custom dataset

We followed the tutorial from the official Yolov7 repository (https://github.com/WongKinYiu/yolov7) by WongKinYiu. We added some of our own annotated images in the dataset and also borrowed a few from the datasets available at Roboflow to make **our own custom dataset** of size over **2k** on Cats and Dogs.


# **Results**

The model correctly detects cats and dogs in an image, even multiple instances, with a confidence of at least **70%**. However some scope still remians for improvement as if we provide images of anything else but Cats and Dogs, it tries to classify it as one of the two, forcibly. A larger dataset, greater number of epochs and a variety of multiple classes available can help improve performance.
