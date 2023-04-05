# Keyword-Extraction

# Introduction

Keyword extraction algorithms are methods that find relevant keywords or key phrases from text documents. They are useful for summarizing, indexing, and searching text documents. 

# Approaches 

In this experiment we explore the different approaches to build a hot keyword extractor and compare between them. we explore different three approaches:

|   | Statistical | Graph-based | Deep-Learning |
| - | ----------- | ----------- | ------------- | 
|   | compute statistics for keywords and use those statistics to score them |  graph of words or phrases and use graph algorithms to rank them | Using Embedding and similarty function to compute the keywords | 
| Based | Statical properties | Statical properties | Semantic Meaning | 
| Inference Time | Low | Low | High  | 
| Examples | word frequency, word collocation, co-occurrence, TF-IDF, and YAKE. |  TextRank, Multi-word Keyword Scoring Strategy, ExpandRank, PositionRank, and Word Attraction Rank. | KeyBERT |

One or two algoritms are picked from each approach to be tested.