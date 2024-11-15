# Application of LLM for classification of SMS text messages as spam or ham.

1. Project Description
•	Goal of the project is to develop a functional model for classifying spam or ham SMS text message in real world application.
•	Using NLP for feature extraction and feature engineering, we prep our data for ingestion into pre-trained models (BERT)
•	Working with the constraint of computational power and funding, the final decision is to use BERT's pre-trained model to output final pooled vectors, which contains the final weights
•	Additional tuning consisted of feeding our vectorized data into a local neural network model by using the concept of training transfer
2. Features
•	Text preprocessing and utilize feature extraction techniques such as TF-IDF, Word2Vec, and word embeddings.
•	Main KPIs include accuracy and precision
3. Usage
•	Upload your data and load into the model, pulling from github is the easiest, and replace 'url=xxxx' with your raw data
•	Run through the commands for text preprocessing, vectorization by BERT, and final training/validation/testing using local neural network
4. Data
•	Data consists of over 5000 samples of fraudulent and realistic message (87:13)
•	Obtained from Kaggle
•	The data was preprocessed to remove stop words, special characters, normalize text, handle missing values, etc.
5. Model Details
•	This model utilize the pre-trained weights of BERT to output vectors of our dataset.
•	To overcome the inability to train our own LLM or even the BERT header, we fed the vectorized data into a local neural network for final classification.
6. Evaluation - WIP
•	Further iteration will include ensemble voting process to further refine classification abilities.
7. Contributing
•	Jeremiah Fowler, Tim Burke, Navya Kanaka
8. License
•	This project uses TensorFlow, Keras, and BERT
9. Contact/Author
•	For any questions or inquiries, feel free to reach out to me at jin.ken.bai@gmail.com or connect with me on LinkedIn



