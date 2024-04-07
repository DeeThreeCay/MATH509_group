# Project: Particle detection in microscopy videos based on CNN

This project aims to improve how we track tiny particles in videos from microscopes. Solely
detecting white pixels in each frame does not suffice and has low accuracy, due to the existence
of “false particles” and noises. Our group will mainly attempt to use Convolutional Neural
Network (CNN) as a tool for better particle detection.

Data are retrieved from https://github.com/newby-jay/SSC_Workshop_2021/tree/main.

## Step 1: Understand how data are gathered from video samples

In step 1, despite videos being provided in the dataset, there is a lot of noise and “false white
spots” present in the video, making the task of “labeling true particles” particularly rough. We will
briefly look into some tools that will help us denoise and make extracting true particles easier.

## Step 2: Training CNN with the given data set (also DNN, LSTM, RNN if time allows)

In step 2, we will mainly be using CNN. Rationale behind is due to the vast number of localized
pixel clusters and particles being sparsely distributed. It would intuitively make sense to train a
CNN to lower the dimensionality of data and extract information from local patches. Besides,
prior experiences have led us to believe that CNN has good global optimization properties,
which could be ideal in tackling the problem.

However, it is not guaranteed that CNN is the most suitable NN architecture for this task, nor do
we need to limit ourselves with just one type of NN architecture. Thus, if time allows, we wish to
try out other types of NN such as Deep Neural Networks (DNN), Long-Short Term Memory
(LSTM) and Recurrent Neural Network (RNN), then compare their performances.

## Step 3: Record the accuracy of each NNs using performance measures (e.g. Precision, Recall)

In step 3, the accuracy of the model will be tested against true labels, where “true particles” will
be marked while “false particles” will not. We compare the NN’s output with these answers to
get a performance score.

## Step 4: Further directions/NN architectures that could be researched in the future

Step 4 acts as suggestions for future research directions and improvements.

## Group Members

- Jialin He (1819219)
- Yuanzhe Zhang (1821829)
- Kwok Kiu Dennis Kwong (1823180)

