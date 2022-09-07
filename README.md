# Automatic-Term-Recognition
<sub>Funfact, this paper was about to be published in a scientific journal, but due to force majeure clause never got translated in English (Report is written in Greek).</sub>
## Files Info

>-With [Python Preprocessing Corpuses.ipynb](https://github.com/ialexandridis/Automatic-Term-Recognition/blob/main/Python%20Preprocessing%20Corpuses.ipynb) the texts were pre-processed (lowercase letters, punct marks, numbers and stopwards removal, part of speech tagging, convert to .csv)<br>
>-With [Python Used to Compare Algorithms Result.ipynb](https://github.com/ialexandridis/Automatic-Term-Recognition/blob/main/Python%20Used%20to%20Compare%20Algorithms%20Result%20.ipynb) the results obtained from the algorithms in weka were compared and saved in [ALGORITHM COMPARISONS.xlsx](https://github.com/ialexandridis/Automatic-Term-Recognition/blob/main/ALGORITHM%20COMPARISONS.xlsx)<br>
>-In [CORPORA.xlsx](https://github.com/ialexandridis/Automatic-Term-Recognition/blob/main/CORPORA.xlsx) there are 4 sheets, 2 which show in detail how the calculations of the characteristics were done (special terms corpora and random text corpora), as well as the 2 final train and test files used in weka.

## More
For the special terms corpora, 6 document texts were used, all related to the field of IT, as they have direct content with the field we chose. All possible fields were included as we focused in a balanced way on software and hardware issues.<br>
All the special terms corpora were about 24,000 words in total and we kept the unique words where it ended up being 5440. In the general text corpora we selected texts from news of 2018 from a multitude of thematic articles. The word total was about 40,000 words.<br>
The selection of features was mainly based on the usual practices followed and suggested by citation. Most of them are statistics (statistical), two are linguistic and one is mixed. <br>
Features:
1. Relative Frequency of Word<br>
2. Term Frequency<br>
3. TF*IDF<br>
4. DF<br>
5. Entropy<br>
6. Part of speech<br>

Algorithms used:
1. IBK with KNN = 1,4,8<br>
2. Bagging<br>
3. Random Tree<br>
4. Random Forest<br>
5. Logistic Regression<br>
6. Naive Bayes<br>
7. J48<br>








