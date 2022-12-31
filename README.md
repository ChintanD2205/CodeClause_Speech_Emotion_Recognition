# CodeClause_Speech_Emotion_Recognition

Install the required libraries:
	To start with, you will need to install the required libraries for this task.

Collect and preprocess the data:
	Next, you will need to collect and preprocess the data that you will use to train and test your emotion recognition model. You can use a dataset of audio files that have been labeled with the corresponding emotion. Before you can use the data, you will need to preprocess it. This involves extracting features from the audio files, such as the Mel-Frequency Cepstral Coefficients (MFCCs) or the spectral centroid, which are commonly used in speech emotion recognition tasks. You can use the Librosa library to extract these features from the audio files.

Train and test the model:
	Once you have extracted the features from the audio files, you can use them to train and test a machine learning model. You can use any machine learning algorithm that you are comfortable with, such as a support vector machine (SVM) or a random forest. You will need to split your data into a training set and a test set, and use the training set to train the model. You can then use the test set to evaluate the performance of the model.

Evaluate the model:
	Once you have trained and tested your model, you will need to evaluate its performance. You can use metrics such as accuracy, precision, and recall to evaluate the model's performance.
Deploy the model:
	If the model performs well, you can deploy it for use in a real-world application. You can use the trained model to predict the emotion of a given audio file.
  
For this task as I was a rookie to the field of Audio Processing in Python, I reached out to YouTube and gained the adequate knowledge of processing audio files using the librosa library, loading the files, playing an audio file, plotting raw audio, plotting spectograms and mel-spectograms, feature extraction - mfcc & chroma.


RAVDESS Dataset : 
(https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio)

References for training and error solving:
Audio Data Processing : https://www.youtube.com/watch?v=ZqpSb5p1xQo , https://www.youtube.com/watch?v=MhOdbtPhbLU
Chroma Feature : https://www.researchgate.net/publication/330796993_Chroma_Feature_Extraction
Librosa Documentation : https://librosa.org/doc/latest/install.html
Acmegrade Machine Learning Training

https://stackoverflow.com/questions/60043276/valueerror-with-n-samples-0-test-size-0-2-and-train-size-none-the-resulting-t
https://cloudxlab.com/assessment/displayslide/2503/numpy-arrays-attributes-of-a-numpy-array
https://www.freecodecamp.org/news/how-to-fix-typeerror-only-size-1-arrays-can-be-converted-to-python-scalars/#:~:text=Error%20in%20Python%3F-,The%20%22TypeError%3A%20only%20size%2D1%20arrays%20can%20be%20converted,that%20accepts%20only%20one%20parameter.&text=The%20code%20above%20throws%20the,the%20NumPy%20int()%20method.
https://stackoverflow.com/questions/4674473/valueerror-setting-an-array-element-with-a-sequence
https://stackoverflow.com/questions/72436576/futurewarning-of-librosa-from-version-0-10-passing-these-as-positional-argumen
https://towardsdatascience.com/using-k-nearest-neighbours-to-predict-the-genre-of-spotify-tracks-796bbbad619f


 
