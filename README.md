# TensorFlow_Experiments
Implementation of ML models on various use cases Using TensorFlow.

<h3>Real_or_Fake_Face_Detector</h3>

<h2> Model Description</h2>
The goal of this project is to successfully recognize a real image and a fake/photoshpped image of a human face. I've implemented the Deep Learning model with the help Google's TensorFlow library and Keras library.

Before feeding the data to the Deep Neural Network, I have used 3 pair of Convolution layer and pooling layer using <b>Conv2D</b> and <b>MaxPooling2D</b>. This layers of Convolution and pooling can vary depending upon various parameters such as the image size or the complexity of problem etc.

<h2>Data</h2>

I have used Kaggel's <i>Real and Fake Face Detection<</i> dataset for this project. The dataset contains 1081 tarning images for <b>Real Face Images</b> and 960 training images for <b>Fake Face Images</b>. The fake image dataset contains data of 3 category:
<ul>Easy</ul>
<ul>Medium</ul>
<ul>Hard</ul>
This is in simple words the degree of how realistically/sophistically the images has been photoshopped. But I haven't used the entire dataset for my project. I took 60 sampels for real images and same amount of samples for fake images(20 from each category).

<h2>Useful Links</h2>
<strong>1.Kaggle dataset link: </strong>https://www.kaggle.com/ciplab/real-and-fake-face-detection/data#
<strong>2.TensorFLow Documentation of "tf.keras" moduel: </strong>https://www.tensorflow.org/api_docs/python/tf/keras