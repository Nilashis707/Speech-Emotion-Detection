# Speech-Emotion-Detection
An ML model to recognise the emotion in any audio

We first preprocess the audio files and plot their waveforms and log mel spectrogram. The mel spectrogram values are then extracted and organised in a pandas dataframe. Both the plots and the mel spectrogram values are then passed into a neural network for prediction.

Libraries used - Numpy, Pandas, Scikit, Tensorflow, Keras, Librosa

The dataset used for this project is RAVDESS Dataset which can be downloaded from here https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio

Few samples of log mel spectrogram plots-

![MelSpec_FemaleSurprised](https://user-images.githubusercontent.com/84060696/172302426-331740b1-0237-4636-a281-e24ce3b4439b.png)   ![MelSpec_FemaleSad](https://user-images.githubusercontent.com/84060696/172302499-ec654304-9614-447f-9648-3f086216761a.png)

![MelSpec_FemaleFearful](https://user-images.githubusercontent.com/84060696/172302573-784541eb-79d1-417f-9c9c-9f26a2d97fdb.png)      ![MelSpec_FemaleCalm](https://user-images.githubusercontent.com/84060696/172302595-b5ecc9fb-0bd4-4e8e-907a-7616db6464fb.png)


