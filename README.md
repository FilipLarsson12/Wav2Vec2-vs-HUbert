# Wav2Vev2 vs Hubert for emotion recognition in speech

This is a study comparing the Wav2Vec2 model developed by Meta and Hubert (Hidden-unit BERT) developed by Google.

We use the RAVDESS dataset which has several male and female speakers uttering one of two sentences in each audio sample with a certain emotion.

In total the dataset we use have 8 different emotions: "surprised", "sad", "neutral", "happy", "fearful", "disgust", "calm" and "angry.

We had 1440 samples in total and used a 80/10/10 train-val-test split. We achieved around 88% accuracy on the test set for both models. 
