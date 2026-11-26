# IR-TP2-Term-Weighting
## 5. Analysis Questions

### Question 19
No, a term with high TF does not always have a high TF-IDF weight. TF-IDF depends on both TF and IDF. If a term appears in many documents, its IDF is low.

### Question 20
Normalized TF takes document length into account. It divides the term frequency by the total number of words in the document. This makes comparisons between documents easier.

### Question 21
When a term appears in every document, IDF-1 becomes 0. IDF-2 is approximately 0.3010 because of the smoothing formula.

### Question 22
The term "system" is an example. It appears 3 times in D2 and in 3 documents. Its IDF is low, so its TF-IDF weight remains relatively low.

### Question 23
Keeping the vocabulary order consistent ensures that each column represents the correct term. It prevents errors when comparing documents and calculating TF-IDF values.
