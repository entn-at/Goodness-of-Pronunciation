# Goodness-of-Pronunciation
This code reflects the work described in the InterSpeech 2019 submitted paper on "An improved goodness of pronunciation (GoP) measure for pronunciation evaluation with DNN-HMM system considering HMM transition probabilities"

# Requirements
* Python (tested with v.2.7.5 & v.3.5.7)
* Kaldi ASR toolkit (for documentation checkout : http://kaldi-asr.org/)

# Code Requirements
* A file by the name _alignment.txt_ needs to be generated which should contain the forced-alignment of the learner's uttered speech.
* Another file by the name _posterior.ark_ needs to be generated which should contain the posterior-probability of the learner's uttered speech.
* A completely _Trained Acoustic Model_ on _NNET2_ (For example : Librispeech, Fisher-English, etc.).
