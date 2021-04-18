# Object detection using TensorFlow 2

Built a Convolution Neural Network having one input layer, 30 hidden layers and one output layer to detect cars, vans, trucks, pedestrians, trams, person sitting and few other miscellaneous objects in an image.

The model is fitted using images of dimensions 160x256 in batches of 64 and is evaluated using the IoU (Intersection over Union) metric.

Dataset used is <ins>KITTI dataset</ins>: https://www.tensorflow.org/datasets/catalog/kitti

The model takes roughly around 50~60 minutes (may vary as per the environment and available resources) to fit on Google Colaboratory notebook running GPU instance.

Model Checkpoints can be added if desired. 


---

In case the notebook preview doesn't load, try: https://nbviewer.jupyter.org/github/nishavak/object-detection/blob/main/object%20detection%20using%20tensorflow.ipynb
