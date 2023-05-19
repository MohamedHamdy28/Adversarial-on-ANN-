# Adversarial-on-ANN-
Manipulating data to ‘fool’ Artificial Neural Network to misclassify audio commands


Imagine, if you get access to some smart speaker. Your task here is to ‘confuse’ or ‘fool’ Artificial
Neural Network, which classifies audio data from spectrograms. In order not to expose yourself
prematurely, you can modify only 15% of packages (in our case timesteps) in each recording. Try to
manipulate test data and get lowest evaluation metrics for the Artificial Neural Network I prepared for
you.


Directories ‘test_audio’ and ‘train_audio’ contain .wav files, spectrograms were created from them.
ANN were trained on these spectrograms (directories ‘train_spec’ and ‘test_spec’). Python notebook
‘to_spectrograms.ipynb’ is to be used for spectrograms generation. Python notebook test.ipynb’ is to
be used for evaluation of your attack. Directory ‘my_model’ contains Tensorflow model files.


What I did:
- Download project from cloud storage (link),
- Use all techniques and tricks you learned during previous assignments and run exploratory data analysis of training and test sets (no limits, no constraints),
- Explain your findings. Develop a strategy to ‘fool’ ANN. Justify it.
- Use .wav files from ‘test_audio’ and manipulate them to generate new spectrograms for the test set. You can modify up to 15% of timesteps for each file. Use new spectrograms as a test set and evaluate classifiers. Try to get the lowest score possible. Evaluation metric is ‘accuracy’ (0.6906).

