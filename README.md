# Depression-Detection-in-speech
Project by Sukesh Shenoy and Megha ghosh 

## Introduction

We have used the DAIC-WOZ Depression Database to train our model. This database is part of a larger corpus, the Distress Analysis Interview Corpus (DAIC) (Gratch et
al.,2014), that contains clinical interviews designed to support the diagnosis of psychological distress
conditions such as anxiety, depression, and post-traumatic stress disorder. The dataset consists of 189 sessions, averaging 16 minutes, between a participant and virtual interviewer called Ellie, controlled by a human interviewer in another room via a "Wizard of Oz" approach. Prior to the interview, each participant completed a psychiatric questionnaire (PHQ-8), from which a binary "truth" classification (depressed, not depressed) was derived. 

We have used Convolutional Neural Networks (CNN) to learn useful characteristic of depression from speech. Convolutional neural networks (CNNs) are a variation of the better known Multilayer Perceptron (MLP) in which node connections are inspired by the visual cortex. CNNs have proven to be a powerful tool in image recognition, video analysis, and natural language processing. More germane to the current effort, successful applications have also been applied to speech analysis. 

A spectrogram is a visual representation of the spectrum of frequencies of a signal as it varies with time. When applied to an audio signal, spectrograms are sometimes called sonographs, voiceprints, or voicegrams. CNNs take images as input. Our CNN model is designed to extract features from a spectrogram which in turn is used for classification of the audio spectrogram into two classes depressed and non depressed respectively. A filter (kernel) is subsequently slid over the spectrogram image and patterns for depressed and non-depressed individuals are learned (based on the aforementioned "truth" dataset).

We have also implemented a Multi-Layer Feed Forward neural network that takes as input Facial Action Coding System (FACS) annotation for depression detection.  FACS is the standard reference in facial  action  annotation,  is  widely  used  in psychology    to  measure  emotion, pain, and behavioral measures of psychopathology, and informs   much work in computer graphics.  FACS  provides a benchmark against which to evaluate automated facial image analysis for detection of depression.




