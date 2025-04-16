**NLP and Deep Learning Projects**

**Student Information**
Name: [Venkata nanda krishna yaram]

Student ID: [700765514]

**Project Overview**
This project explores multiple tasks in the domain of Natural Language Processing (NLP) and Deep Learning. The following tasks are covered:

NLP Preprocessing Pipeline

Named Entity Recognition (NER) using SpaCy

Scaled Dot-Product Attention

Sentiment Analysis using HuggingFace Transformers

Each task demonstrates a different NLP or deep learning technique, from preprocessing text to extracting entities, implementing attention mechanisms, and performing sentiment classification using pre-trained models.

**Table of Contents**

NLP Preprocessing Pipeline

Named Entity Recognition with SpaCy

Scaled Dot-Product Attention

Sentiment Analysis using HuggingFace Transformers

Conclusion

**1. NLP Preprocessing Pipeline**
Objective:
Implement a basic preprocessing pipeline for NLP tasks, which includes tokenization, stopword removal, and stemming.

Steps Implemented:
Tokenization: The sentence is split into individual words.

Stopword Removal: Common stopwords like "the", "is", "in" are removed to retain only meaningful words.

Stemming: Each word is reduced to its root form (e.g., "running" becomes "run").

Result:
The pipeline produces:

A list of tokens

A list with stopwords removed

A final list of stemmed words

**2. Named Entity Recognition (NER) using SpaCy**
Objective:
Implement Named Entity Recognition (NER) using the SpaCy library to identify entities in a given sentence.

Steps Implemented:
Load SpaCy's Pretrained Model: We load a pre-trained model for NER tasks.

Identify Entities: Using the model, we identify named entities such as persons, organizations, and locations.

Extract and Print Entities: For each entity, we print the text, label, and position (start and end) in the sentence.

Example Sentence:
"Barack Obama served as the 44th President of the United States and won the Nobel Peace Prize in 2009."

Expected Output:
For each recognized entity, we display:

The entity text (e.g., "Barack Obama")

The entity label (e.g., PERSON)

The start and end positions in the sentence.

**3. Scaled Dot-Product Attention**
Objective:
Implement the scaled dot-product attention mechanism, a core component of transformer models.

Steps Implemented:
Dot Product Calculation: Compute the dot product between the Query (Q) and the transpose of the Key (K).

Scaling: The result is scaled by dividing by the square root of the key dimension (d_k).

Softmax: Apply the softmax function to obtain attention weights.

Weighted Sum: Multiply the attention weights by the Value (V) matrix to get the output.

Result:
The output consists of:

Attention weights matrix (after softmax)

The final output matrix after applying the attention weights to the value matrix.

**4. Sentiment Analysis using HuggingFace Transformers**
Objective:
Use a pre-trained sentiment analysis pipeline from HuggingFace to classify the sentiment of a sentence.

Steps Implemented:
Load Pre-trained Model: Load the pre-trained sentiment analysis pipeline using HuggingFace's pipeline function.

Input Sentence: The sentence "Despite the high price, the performance of the new MacBook is outstanding" is provided for sentiment analysis.

Get Sentiment Label and Confidence Score: The pipeline returns the sentiment label (positive/negative) and the confidence score.

Example Sentence:
"Despite the high price, the performance of the new MacBook is outstanding."

Expected Output:
The result includes:

Sentiment label (e.g., POSITIVE)

Confidence score (e.g., 0.9998)

**Conclusion**
This project demonstrates the implementation of various techniques in Natural Language Processing and Deep Learning:

NLP Preprocessing: We performed tokenization, stopword removal, and stemming to prepare text for analysis.

Named Entity Recognition: Using SpaCy, we identified and categorized entities in a given sentence.

Scaled Dot-Product Attention: Implemented the attention mechanism commonly used in transformer architectures.

Sentiment Analysis: We leveraged HuggingFace's pre-trained sentiment analysis models to classify the sentiment of text.

These implementations serve as fundamental building blocks for more complex NLP and deep learning models, showcasing practical applications in text preprocessing, entity recognition, and sentiment classification.

