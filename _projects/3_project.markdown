---
layout: page
title: MTCNN
description: Deep Learning for Facial Detection / Extraction
img: /assets/img/girl_w_glasses_keypoints.png
# redirect:
---

Face detection and face extraction project with MTCNN, Keras, and TensorFlow 2.0, in a Python 3+ environment.

A *mutli-tasked cascaded convolutional neural network* shows the ability and speed to detect faces in a variety of images. Additionally, the project's [verison 2](https://github.com/jeremywood-ai/MTCNN/blob/master/MTCNN_Version2_Facial_Extraction.py) allows for image extraction, see the group photo below.

## MODEL
----
"By default the MTCNN bundles a face detection weights model.

"The model is adapted from the Facenet's MTCNN implementation, merged in a single file located inside the folder 'data' relative to the module's path. It can be overriden by injecting it into the MTCNN() constructor during instantiation.

"The model must be numpy-based containing the 3 main keys "pnet", "rnet" and "onet", having each of them the weights of each of the layers of the network," (Brownlee, 2019) mtcnn_weights.npy is the weight file from the library that is trained for the three layers.

For more reference about the network definition, take a close look at the paper from Zhang et al. (2016).

![Girl_from_Version_1](/portfolio/assets/img/girl_w_glasses_keypoints.png)
<div class="col three caption">
    <h5>Girl marked with keypoints and boxed from MTCNN Facial Detection.</h5>
</div>
<br/>

This project is based on Iván de Paz Centeno's MTCNN library [https://github.com/ipazc/mtcnn](https://github.com/ipazc/mtcnn).

![Group](/portfolio/assets/img/groupphoto_Face_Extraction.png){:width="600px"}

<div class="col three caption">
    <h5>Group compilation from MTCNN facial extraction version.</h5>
</div>

### Files
[MTCNN_facial_recognition.py 'MTCNN Version 1 - Facial Recognition](https://github.com/jeremywood-ai/MTCNN/blob/master/MTCNN_facial_recognition.py)

[MTCNN_Version2_Facial_Extraction.py 'MTCNN Version 2 - Face Extraction](https://github.com/jeremywood-ai/MTCNN/blob/master/MTCNN_Version2_Facial_Extraction.py)

[MTCNN Python environment.txt 'Anaconda Full Package List'](https://github.com/jeremywood-ai/MTCNN/blob/master/MTCNN_environment.txt)

### Reference
----
1. Brownlee, Jason. (2019). How to Perform Face Detection with Deep Learning. https://machinelearningmastery.com/how-to-perform-face-detection-with-classical-and-deep-learning-methods-in-python-with-keras/ Machine Learning Mastery.

1. Zhang, K., Zhang, Z., Li, Z., and Qiao, Y. (2016). Joint face detection and alignment using multitask cascaded convolutional networks. IEEE Signal Processing Letters, 23(10):1499–1503.

<!-- [Girl]: /assets/img/girl_w_glasses_keypoints.png
[Group]: /assets/img/groupphoto_Face_Extraction.png -->