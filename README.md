# Urban Sounds: a practice problem using a neural network model to identify sounds

I'm a bit of an audiophile, and wanted to try my hand at machine learning using a neural netwrok model. This common data science practice propblem uses a set of 4-second sound recordings that fall into ten catigories - jackhammer, children playing, gun shot, etc. The challenge is to train a model on a set of about 8,000 labeld sound files so that it can identify unlabeld sound files. I used the Librosa library in Python to extract frequency-based melodic eliments from the sound files, and then Keras/TensorFlow to make and train a neural network. I'm still refining the model by (A) evaluating and optomizing the hyperparamiters of the machine leanring model and (B) expiramenting with other data I can evaluate from the sound files.

This model uses TensorFlow / Keras, and GridSearchCV in scikit-learn to find optimal hyperparamiters.  
