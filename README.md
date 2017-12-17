# Project-IntroML
This is a simple speech recognition system implemented as the course project of Intro to Machine Learning.

We implemented a Hidden Markov Model here to model the time-varying process of producing speech using jupyter notebook.

Dataset stores audio samples of spoken digit chains with varying length. We partition these samples in two groups, one for training and the other for validation, which are stored in two separate folders named train and test. One can load these samples using TRAIN.transcripts and TEST.transcripts. Those files contain words of digits spoken in the corresponding audio files specified by the name at the end of each line.
