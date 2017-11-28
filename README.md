# voice_emotion_AI
Neural network to detect happy &amp; angry emotion in voices (Keras, Tensorflow backend)

Voice dataset from:
1) English voice: http://smartlaboratory.org/ravdess/
2) German voice: http://emodb.bilderbar.info/start.html

# Voice_Sentiment_Data.ipynb
data processing step

# Voice_Sentiment_Train.ipynb
training with voice spectrograms

# End-to-end models
End-to-end folder contains jupyter notebooks which try several end-to-end models to take in raw audio signal as input (instead of spectrograms)

Findings: 
a) Spectrogram models seem to perform better than end-to-end models, possibly due to the case that information on several frequencies are not as comprehensively captured as compared to spectrogram models.

b) Model trained on classifying happy/angry voices are able to pick up other related emotion pairs like surprised/disgust, possibly due to overlap in voice information in similar emotions like (happy-surprised) & (angry-disgust).