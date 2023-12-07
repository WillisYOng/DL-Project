Model Card

Model Details

Willis Ong and Aryan Barik
December 6, 2023
Model Version: Word2vec 0.11.1
Model type: Word Embeddings
Used Continuous Bag of Words and Skipgram (n-gram)
License: Word2Vec uses the Apache License

Intended use

Primary intended uses: To get recommendations based on user's input: a movie title.

Primary intended users: People who would like to get a movie recommendation based on the movie title provided. 

Metrics

Model performance measures: Cosine Similarity

Evaluation data

Datasets: IMDb Movies Dataset

Motivation: Create a recommender system to recommend movies

Preprocessing: Removed punctuation, replaced null descriptions with empty spaces. 

Training data: Movie Overviews from IMDB dataset. 

Ethical considerations: Our lack of knowledge in the diversity of viewpoints of the writing of the movie overviews may have lead to biases in the dataset. 

Use Cases: Can be used to recommend movies to people based on given movie title. 

Caveats and recommendations: Recommendations might be inaccurate due to the way similarity was calculated.


