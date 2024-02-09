# Restaurant Reviews (Natural Language Processing - Bag of Words Model)

Using a bag of words model to evaluate restaurant reviews.

## Natural Language Processing

Natural Language Processing (NLP) is a field of artificial intelligence (AI) concerned with the interaction between computers and humans through natural language. It involves the development of algorithms and techniques that enable computers to understand, interpret, and generate human language data.

One fundamental concept in NLP is the Bag of Words (BoW) model. The BoW model represents text data as a collection of words, disregarding grammar and word order but maintaining information about word frequency. Here's how the BoW model works:

1. Tokenization - The first step is to break down a piece of text into individual words or tokens. This process involves splitting the text into meaningful units, such as words or punctuation marks.

2. Vocabulary Creation - Once tokenized, the unique words in the text are collected to form a vocabulary. Each unique word in the vocabulary represents a dimension in the vector space model.

3. Vectorization - After creating the vocabulary, each document in the corpus (collection of documents) is represented as a vector, where each dimension corresponds to a word in the vocabulary, and the value of each dimension represents the frequency of the corresponding word in the document.

4. Sparse Matrix Representation - Since most documents contain only a subset of the words present in the entire vocabulary, the resulting vectors are typically sparse, meaning most of the dimensions are zero. These vectors are often represented using sparse matrix formats to conserve memory and computational resources.

5. Analysis and Modeling - Once the documents are represented as vectors, various NLP tasks can be performed, such as sentiment analysis, document classification, and information retrieval. Machine learning algorithms, such as Naive Bayes, Support Vector Machines (SVM), or deep learning models, can be trained on these vectorized representations to perform specific tasks.

The Bag of Words model is a simple yet powerful representation for text data, but it has its limitations. It does not consider the semantic meaning or context of words, which can lead to loss of information. Additionally, it treats all words as independent features, disregarding relationships and dependencies between words. Despite these limitations, the Bag of Words model serves as a foundational concept in NLP and forms the basis for more sophisticated techniques like word embeddings and neural language models.

## Model Evaluation

Here's a breakdown of the performance metrics based on the confusion matrix:

- True Positives (TP) - 91 instances were correctly classified as positive.
- False Positives (FP) - 42 instances were incorrectly classified as positive.
- True Negatives (TN) - 55 instances were correctly classified as negative.
- False Negatives (FN) - 12 instances were incorrectly classified as negative.

The accuracy score of 0.73 indicates that the Bag of Words (BoW) model correctly classified approximately 73% of the instances in the dataset.

Accuracy is a measure of the overall correctness of the model's predictions and is calculated as the ratio of the number of correct predictions to the total number of predictions made.

In this case, an accuracy score of 0.73 suggests that the BoW model is performing reasonably well.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.