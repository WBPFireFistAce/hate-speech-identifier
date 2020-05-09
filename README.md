# hate-speech-identifier

This is a simple hate speech identifier that uses a free hate speech data set from https://data.world/thomasrdavidson/hate-speech-and-offensive-language

The model itself uses embedding, 1D Convolutional Neural Networks and Long Short Term Memory layers, with ~93% classification accuracy. For the purposes of this exercise rows that are labelled to contain offensive language, but are not hateful, are dropped.
Run train.py if you have all the necessary dependencies and libraries as outlined in requirements.txt installed. 
