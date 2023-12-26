# NLP_Project

A university group project applying machine learning to horse racing predictions. This was a collaborative Google Colab notebook so coding styles may vary throughout. 

Used Python and PyTorch as well as the GPU available in the notebook.

Scraped numerical and textual data of each horse using BeautifulSoup and Selenium from betting site. 

To embed the text: 
- fine-tuned a pre-trained BERT model
- Bag of Words of the top 100 TF-IDF scoring words

Concatenated the numerical data and textual data and fed into MLP. 

Implemented early stopping, dropout and normalised our data to prevent overfitting. 

Received grade of 95% for this project. 
