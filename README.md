# hate-speech-identifier

This is a simple hate speech identifier that uses a free hate speech data set from https://data.world/thomasrdavidson/hate-speech-and-offensive-language

The model itself uses embedding, 1D Convolutional Neural Networks and Long Short Term Memory layers, with ~93% classification accuracy. For the purposes of this project, rows that are labelled to contain offensive language, but are not hateful, are dropped.

Run train.py if you have all the necessary dependencies and libraries as outlined in requirements.txt installed. 

I have a specialization in front-end, which you can clearly see if you take a look around my GitHub, but I've recently been learning more about Machine Learning and Data Science so I wanted to put my skills to the test. Ideally, I would've created a front-end for this project for users to report hate speech too because that's where I'm at my best, but my inner engineer wanted to try out tinkering with CNNs and LSTM layers.

I tackled sub-problem 4 which suggested creating a classifier for hate speech and misinformation. I chose just hate speech taken from Twitter. The accuracy is already pretty good, but, as with most things in life, it can definitely be improved. Assuming all other sub-problems have been solved, we can create an API and connect it to the database which can feed guaranteed hate speech to the model for training as well as get accurate predictions from user-reported Tweets and classify them as either hate speech or not. With an ever-growing database, the model is sure to reach a point where only the most obscure hate speech will slip by.
