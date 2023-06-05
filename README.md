# Facial-Reconstruction-from-speech-FY
## Introduction
In this project, we perform the task of reconstructing  a facial image of a person from a short audio recording  of that person speaking.
There is a strong correlation between speech of a  person and his/her appearance, part of which is  a direct  result of the mechanics of speech production: age,  gender (which affects the pitch of our voice), the shape  of the mouth, facial bone structure, thin or full lips —  all can affect the sound we   generate. In addition, other  voice-appearance correlations stem from the way in  which we talk:language, accent, speed, pronunciations.  In this project, our goal is to predict a recognizable  image   of the speaker’s face and to capture dominant  facial traits of the person that are correlated with the  input speech.
## Speech2Face: Learning the Face Behind a Voice
How much can we infer about a person's looks from the way they speak? In this paper, we study the task of reconstructing a facial image of a person from a short audio recording of that person speaking. We design and train a deep neural network to perform this task using millions of natural Internet/Youtube videos of people speaking. During training, our model learns voice-face correlations that allow it to produce images that capture various physical attributes of the speakers such as age, gender and ethnicity. This is done in a self-supervised manner, by utilizing the natural co-occurrence of faces and speech in Internet videos, without the need to model attributes explicitly. We evaluate and numerically quantify how-and in what manner-our Speech2Face reconstructions, obtained directly from audio, resemble the true face images of the speakers.
https://speech2face.github.io/
## How To use This Code
Every lines in this code is written with comments to make it easier to understand. code should be run from start to end on google colab as python uses line  by line interpreter.
## Limitation
Likewise, Speech2Face can’t generate specific faces. From my voice, it won’t know that I have a scar on my chin, or that I have blond hair. But it will know that I’m a Caucasian male of a certain age, with a certain bone structure, and that I speak English. In many cases, this is enough to create a face that looks quite similar to mine.
