# Fall-Detection-Research-Paper-Implementation

#### -- Project Status: [Completed]

## Project Intro/Objective
In this project, I implemented a Feb, 2022 research paper titled “A Novel Vision-Based Fall Detection Scheme Using Keypoints of Human Skeleton with Long Short-Term Memory Network” to perform fall detection. The research paper proposed a framework of a CNN and a LSTM network for fall detection. The point of the CNN is to exploit the spatial correlation while the LSTM identifies the long-term dependencies among the features. Additionally, the CNN is wrapped in a TimeDistributed wrapper in order to help solve the sequence learning problem and would result in a set of features organized sequentially.


### Methods Used
* Deep Learning
* Data Visualization
* Transfer Learning
* 1D Convolutional layers
* TimeDistributed Wrapper
* MaxPooling layers
* Dense layers
* LSTMs
* CNNs
* EarlyStopping callback

### Technologies
* Python
* TensorFlow
* pandas
* numpy
* matplotlib
* jupyter

## Project Description
I implemented fall detection in a two-stage process. First, I used MoveNet to generate keypoints from videos. MoveNet is a bottom-up estimation model which means that it detects all parts in the image first. Then it groups the parts to distinct persons. Then I fed those keypoints into a neural network that consisted of a TimeDistributed CNN and an LSTM. The TimeDistributed CNN was able to make use of the spatial correlation of the feature vector. Then the LSTM was able to identify the long-term dependencies among the features. A link to the code for my project can be found in the description.

### Dataset Location
The Raw Data can be found [here]([https://www.kaggle.com/puneet6060/intel-image-classification](http://fenix.univ.rzeszow.pl/~mkepski/ds/uf.html))

## Featured Notebooks/Analysis/Deliverables
* [Notebook]([https://github.com/lukemonington/landscape_classification/blob/main/main.ipynb](https://github.com/lukemonington/Fall-Detection-Research-Paper-Implementation/blob/main/main%20ai.ipynb))


## Contributing Members

**[Luke Monington](https://github.com/lukemonington)**

## Contact
* I can be reached at lukemonington@aol.com.
