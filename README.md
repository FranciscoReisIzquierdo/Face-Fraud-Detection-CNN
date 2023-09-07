# Face-Fraud-Detection-CNN

The rapid advancements in artificial intelligence (AI) have unleashed a world of possibilities, enabling machines to generate incredibly realistic images, including human faces. While this technological progress brings immense benefits, it also presents new challenges, particularly in the realm of fraud detection. With the proliferation of AI-generated faces, distinguishing between genuine and fabricated identities has become increasingly complex.

In this project, we delve into the fascinating realm of fraud face detection, where Convolutional Neural Networks (CNNs) have emerged as a powerful tool. CNNs, a subset of deep learning algorithms inspired by the human visual system, have revolutionized computer vision tasks and exhibit great promise in identifying fraudulent or synthetic faces. By training a CNN model specifically designed to discern the subtle discrepancies between AI-generated and real face images, we can unmask the fakes and fortify our defenses against identity-related fraud.

The goal of this project is to shed light on the potential of CNNs in combatting the rising tide of AI-generated face fraud. By leveraging the power of deep learning and computer vision, we can build systems capable of unmasking the fakes and preserving the integrity of our digital identities. Let us embark on this journey to understand how CNN models are leading the charge in this crucial battle between truth and deception.

### Face Fraud Detection using CNN with the following files:
* 140k-real-and-fake-images
* MyDataset
  
#### In total there are 140k images, belonging to one of the follow classes:
* real -> 70k images
* fake -> 70k images

#### The data is split in the following datasets:

##### Train Dataset (100k images):
* *training fake -> 50k images*
* *training real -> 50k images*

##### Test Dataset (20k images):
* *test fake -> 10k images*
* *test real -> 10k images*

##### Validation Dataset (20k images):
* *valid fake -> 10k images*
* *valid real -> 10k images*

#### There is also a folder containg 100 images that were retreived by me, for the purpose to evaluate the accuracy of the model built and trained on images of my choice.
##### MyDataset:
* 50 real celebreties face images
* 50 AI generated face images from: https://this-person-does-not-exist.com/en

#### Files can be found here:
* 140k-real-and-fake-images: https://www.kaggle.com/datasets/xhlulu/140k-real-and-fake-faces
* MyDataset: https://github.com/FranciscoReisIzquierdo/Face-Fraud-Detection-CNN/tree/main/Datasets/Faces%20MyDataset

#### Environment: https://www.kaggle.com/
#### Disclouser: Some of the paths to the saved models and/or datasets may be wrong depending on the environment
