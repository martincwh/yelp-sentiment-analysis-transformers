# Yelp Reviews Sentiment Analysis with Transformers
Text Sentiment Analysis project that predicts the sentiment polarity of Yelp restaurant reviews.


### [1] Description
This project enables the user to input a text restaurant review and output a predicted sentiment polarity rating out of three ratings: "Positive", "Neutral", and "Negative". Its true utility shines when analyzing and predicting large volumes of text reviews and generating an overall sentiment.


### [2] Use Case
From this application, users will be able to generate predicted sentiment polarity ratings for text restaurant reviews. This is especially useful when restaurant managers want to quickly find out the overall sentiment of their business without manually looking through all their reviews. This allows business owners to identify common complaints or areas of improvements and identify positive comments to encourage business development initiatives.


### [3] Repository Contents
1) BERT Model Demonstration.ipynb<br>
The main Jupyter notebook file that demonstrates the capabilities and output of the sentiment analysis model. It is a self-contained file that makes use of the saved BERT model to demonstrate the project. More details on how to run the file are in the file itself. Note: If you are interested in running the model for yourself, please download the _BERT_epoch_2.model located in the Google Drive link under point 5 of the Repository Contents. The model file was too big to be uploaded to Github.

2) BERT Model Details.pdf<br>
A PDF file that contains in-depth details of the development, evaluation, and selection process of the sentiment analysis model. It contains a brief explanation of the BERT model and some evaluation metrics that were used to select the best-trained model.

3) BERT Sentiment Analysis.ipynb<br>
A Jupyter notebook containing the code that was used to train, validate, and test the sentiment analysis model. It begins with some markdowns detailing the motivation of the project as well as some potential use cases. The entire development process of the sentiment analysis model is contained within this file. More in-depth details on the training process can be found in the file itself.

4) requirements.txt<br>
Text file that contains all Python modules and requirements used in the development of this project.

5) unique_data.csv and _BERT_epoch_2.model<br>
The CSV file contains the dataset that was used in this project. There are 102,326 unique restaurant text reviews in the file, of which 60% was allocated to training, 20% to validation, and the remaining 20% to testing.<br><br>The model file contains the selected best model that was trained in BERT Sentiment Analysis.ipynb. This model possessed the highest evaluation metrics out of all other epochs.<br><br>These two files were too large to be uploaded to GitHub. If you are interested in these files, I will leave the download link here: https://drive.google.com/drive/folders/1nxHRYcRG78ISXi1uw3BodOHsWhRG52G5?usp=drive_link


### [4] How to Use
To see the model in action, download the _BERT_epoch_2.model file from the Google Drive link and BERT Model Demonstration.ipynb. Then, follow the instructions in the Python notebook.


### [5] Author
Martin Cheng
