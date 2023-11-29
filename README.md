# Emotion Recognition in Speech
## Objectives
This is another Deep Learning (DL) project where the primary focus is on processing audio data. Vocal emotion recognition aims to identify and interpret user emotions and deduce emotional states from speech. To train such an algorithm, you need to primarily use training data in the form of audio data. This system takes user speech as input. 

This project requires the RAVDESS dataset to train the machine learning model with various types of audio. The RAVDESS dataset (Ryerson Audio-Visual Database of Emotional Speech and Song) contains 7356 files with voice samples from 24 professional actors (12 females, 12 males). It includes different speech intensities, such as joyful, calm, angry, sad, surprised, fearful, and disgusted expressions, as well as songs with various emotions, such as sad ones.

## Filename identifiers 

The RAVDESS dataset contains thousands of files that can be identified by their names. 

* Modality (01 = full-AV, 02 = video-only, 03 = audio-only).
* Vocal channel (01 = speech, 02 = song).
* Emotion (01 = neutral, 02 = calm, 03 = happy, 04 = sad, 05 = angry, 06 = fearful, 07 = disgust, 08 = surprised).
* Emotional intensity (01 = normal, 02 = strong). 
* Statement (01 = “Kids are talking by the door”, 02 = “Dogs are sitting by the door”).
* Repetition (01 = 1st repetition, 02 = 2nd repetition).
* Actor (01 to 24. Odd numbered actors are male, even numbered actors are female).

Filename example: 02-01-06-01-02-01-12.mp4 :
Video-only (02)
Speech (01)
Fearful (06)
Normal intensity (01)
Statement “dogs” (02)
1st Repetition (01)
12th Actor (12)
Female, as the actor ID number is even.
APPENDIX 2: The TESS dataset

## ?

In this project, to general Python libraries like NumPy, Pyaudio, and Pandas, we will also use Librosa. Librosa is a Python library for analyzing audio data and music files.