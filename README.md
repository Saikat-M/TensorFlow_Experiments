# TensorFlow_Experiments
Implementation of ML/DL models on various use cases Using TensorFlow.

<h2>Real_or_Fake_Face_Detector</h2>

<h3> Model Description</h3>
The goal of this project is to successfully recognize a real image and a fake/photoshpped image of a human face. I've implemented a Deep Learning model with the help TensorFlow and Keras.


Before feeding the data to the Deep Neural Network, I have used 3 pair of Convolution and pooling layers using <b>Conv2D</b> and <b>MaxPooling2D</b> functions. The number of Convolution and pooling layers can vary depending upon various parameters such as the image size or the complexity of problem etc.

<h3>Data</h3>

I have used Kaggel's <i>Real and Fake Face Detection</i> dataset for this project. The dataset contains 1081 tarning images for <b>Real Face Images</b> and 960 training images for <b>Fake Face Images</b>. The fake image dataset contains data of 3 category:
<li>Easy</li>
<li>Medium</li>
<li>Hard</li>
In simple words this is the degree of how realistically/sophistically the images has been photoshopped. But I haven't used the entire dataset for my project. I took 60 sampels for real images and same amount of samples for fake images(20 from each category). I have provided the .zip file of this reduced dataset in the repo.

<h3>Useful Links</h3>
<strong>1.Google's dataset search engine: </strong>https://datasetsearch.research.google.com/

<strong>2.Kaggle dataset link: </strong>https://www.kaggle.com/ciplab/real-and-fake-face-detection/data#
                                                                                                                                                                                                                                                                                          
                                                                                                                                                                                                                                                                                 <strong>3.TensorFLow Documentation of "tf.keras" moduel: </strong>https://www.tensorflow.org/api_docs/python/tf/keras
