# Deep-Learning-Journey

This Repo is meant for enthusaists in deep learning who want to explore the field via scientific papers and literature. This repo is not intended to be a guide for practical application of Deep Learning practices. However, through the literature and discussions included in this repo (posted in a progressive manner every week), anyone interested in deep learning shall be able to gain a better understanding of concepts and theory which will definitely lead towards successful implementations of deep learning systems.

Every week the contributors of this repo shall be posting papers from the field with their summary, confusions and discussion questions. The papers as well as the summaries can be found in relevant folders. We recommend going through those reviews after you have read the paper once and try to write your own reviews. 

Also, if you are new to reading technical/academic papers, please follow the link below. 

https://web.stanford.edu/class/ee384m/Handouts/HowtoReadPaper.pdf


### Week 1

In this week, we will look into an original paper on back propagation and also a survey paper on Deep Learning. We assume that at this point, you do not have a very deep understanding of these topics. Therefore, these two papers should get you started in tackling other complex topics to come. Depending on how much backgorund you have, you can skim through the materials in this week. If you are very new to the topic, please follow the links below to get an intuitive understanding of the concepts first before diving into paper which is full of technical terms and mathematical equations without full descriptions. 

We have also included the papers itself and our reviews in the week1 folder above to get a better understanding on how to tackle such papers. 

#### Paper 1: Learning representations by back-propagating errors
A walk down of the original paper: 

https://www.youtube.com/watch?v=oq6Z76Gl0ho&fbclid=IwAR3PRRjftjkfpTK_DvNA6l0VZ_40vGknDfssiFv-d4qJ674D9rCbyt2gWL8

Two very good videos on what back propagation actually is. Understanding intuitively:
1. https://www.youtube.com/watch?v=Ilg3gGewQ5U&fbclid=IwAR1vbfFjZR6tJolK-0_OX4UpqmmjUwaTkA6BZ3QB2n9-rcPtulRk75kwugs
2. https://www.youtube.com/watch?v=tIeHLnjs5U8&fbclid=IwAR1eazMuzQSc1Ca3kctCGd0f-LZstBtPfqqQLUE2coFV-WqYJTduxfNnNgo

#### Paper 2: Deep Learning
Link to the paper: https://www.ncbi.nlm.nih.gov/pubmed/26017442

If you want to get a very basic understanding of neural network first:

https://www.youtube.com/watch?v=aircAruvnKk

Understand what Supervised Learning is below:

https://www.youtube.com/watch?v=4qVRBYAdLAo

Dive into more complex topics such as Convolutional Neural Network (CNN) and Recurrent Neural Network (RNN):

CNN

1. https://www.youtube.com/watch?v=x_VrgWTKkiM, http://cs231n.github.io/convolutional-networks/

2. http://cs231n.github.io/convolutional-networks/

RNN

1. https://www.youtube.com/watch?v=UNmqTiOnRfg

2. https://medium.com/explore-artificial-intelligence/an-introduction-to-recurrent-neural-networks-72c97bf0912

### Week 2

This week we read 3 papers about image recognition using CNN. One of the main reasons we use CNN for image recognition tasks instead of deep neural networks is the high number of pixel values in images. For instance, a 400*400 pixel image has 160000 pixels and if we have 500 neurons in the first input layer, we end up having a total of 80 million connections only for the first layer. CNNs help solve this problem using partially connected layers as we will discover in the papers below.
We are writing two reviews for these papers. One for the Paper 3 and a single review for Paper 1 and 2 but by only focusing on the Section 2 of Paper 2.

#### Paper 1: Handwritten Zip Code Recognition with Multilayer Networks

#### Paper 2: Gradient-Based Learning Applied to Document Recognition

#### Paper 3: ImageNet Classification with Deep Convolutional Neural Networks

Helpful YouTube links:

1. https://www.youtube.com/watch?v=2-Ol7ZB0MmU
2. https://www.youtube.com/watch?v=H-HVZJ7kGI0
3. https://www.youtube.com/watch?v=YRhxdVk_sIs
4. https://www.youtube.com/watch?v=umGJ30-15_A

Blog posts:

1. https://medium.com/dataseries/basic-overview-of-convolutional-neural-network-cnn-4fcc7dbb4f17
2. http://cs231n.github.io/convolutional-networks/
3. https://ujjwalkarn.me/2016/08/11/intuitive-explanation-convnets/


### Week 3

This week we will mostly be focusing on 2 relatively new papers on convolutional neural network. However, we have also included some supplementaly readings for those who wants to understand how it all came into existence. Some of these old papers gave an indepth understanding of the inspiration behind CNN and its analogy with human brain cells such as simple cells and complex cells. 

The first paper we are going to be focusing on is on ResNet, which is relatively new concept. The authors introduce a technique of training deep neural network by introducing the concept of identity mapping and residual learning. Using that, the authors were able to go as deep as 1000 layers, without much overfitting issue.

The second paper focuses on similar concept where the authors argue that deep neural network help improve the accuracy of the model. They do not introduce new paradigm. However, they do increase the depth of the network substantially than past CNN models.

ResNet

Youtube Videos: 

1. https://www.youtube.com/watch?v=0tBPSxioIZE

2. https://www.youtube.com/watch?v=lugkZaFj4x8

3. https://www.youtube.com/watch?v=sAzL4XMke80

Blog Posts:

1. https://towardsdatascience.com/introduction-to-resnets-c0a830a288a4


### Week 4

This week we will be switching our gear a little bit and working on understanding some relatively new Recurrent Neural Netowrk such as Long-Short Term Memory (LSTM). 

The first paper by Greff et. al. does a good job of explaining the basic structuee of the LSTM network. It can be a little bit complicated to follow on the first try, however, re-reading and looking at some supplementary resources will help in better understanding of the network. 

The second paper by Bhanadanau et. al. is more application focused which introduces a basic approach of using RNN for machine translation. It is slightly easier to follow. 

LSTM 

Blogposts:

1. https://colah.github.io/posts/2015-08-Understanding-LSTMs/


Youtube Videos:

1. https://www.youtube.com/watch?v=WCUNPb-5EYI

Supplementary Paper:

1. http://ai.dinfo.unifi.it/paolo//ps/tnn-94-gradient.pdf


