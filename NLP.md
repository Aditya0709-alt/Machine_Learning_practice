## Vector Models and Text Pre-processing for NLP

**Some basic NLP Terms**
- Token: A sequence of words or tokens i.e. punctuations, sub-units of words
- In NLP, we build models in terms of either words or characters
- Vocabulary: A set of all words named vocabulary
- Corpus: A large colletion of writings of a specific kind or specific object/ collection or findings. This is our dataset for training the model
- N-Gram: A collection of N-consecutive items (unigrams, bigrams, etc.) 

**Vectors**
- Magnitude + direction
- When we work with high dimensional data i.e. data where the features and observations are the same in number, direcctio is not intuitive and the direction becomes difficult to determine with the growing number of directions
- As vectors can have many components, we can think of them as points in a Euclidean space. 

**Why do we need vectors**
- Defining rules for raw data or text is complex and working with numbers is always easy
- We map text into vectors, and all the vectors of the same class fall into the same cloud

<img width="1446" alt="Screenshot 2023-02-23 at 9 51 40 PM" src="https://user-images.githubusercontent.com/77115883/220967490-90855b34-a7f4-43ed-a26c-0811f3f14064.png">

**Organizing Documents**
- We can use clustering to organize a large number of documents into groups by converting the documents into vectors

**Bag Of Words**
- The bag-of-words model is a simplifying representation used in natural language processing and information retrieval
- In this model, a text is represented as the bag of its words, disregarding grammar and even word order but keeping multiplicity
- Probabilistic and DL models do not use bag of words approach


