In this project, we will be converting an audio file into a text file, in which the speakers are differentiated from one another. 
We used machine learning and deep learning in this project by using librosa, matplotlib and  tensorflow.


SPEAKER CHANGE DETECTION:

The mechanism proposed here is for real-time speaker change detection in conversations, which firstly trains a neural network text-independent speaker classifier using in domain speaker data.


Here, on coming to the observation point of view, Librosa converts the signal to mono, meaning the channel will always be 1.

EXTRACTING THE FEATURES:

Here we will be using Mel-Frequency Cepstral Coefficients(MFCC) from the audio samples. The MFCC summarises the frequency distribution across the window size, so it is possible to analyse both the frequency and time characteristics of the sound. These audio representations will allow us to identify features for classification.


And finally, the steps involved in testing some audio data are as follows......

•	Preprocess the new audio data,
•	predict the classes,
•	Invere transform your Predicted Label.

