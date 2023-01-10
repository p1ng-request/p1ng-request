![Banner](https://raw.githubusercontent.com/p1ng-request/p1ng-request/main/banner.gif)
## Something I have been working on 🎯

[check-dead-links.py](https://github.com/p1ng-request/automation-scripts-best-pracitces/blob/main/check-dead-links.py): A Python script to scan dead links from a given web domain.

[npl-scan.py](https://github.com/p1ng-request/automation-scripts/blob/main/nlp-scan.py): Basic Docs automation tool in Python. Features:
+ Scan all the .md files in a given directory and all the sub-directories.
+ Use machine learning models to classify the documentation and make suggestions based on the classification results.
+ Generate a Flesch-Kincaid readability test score for each doc.
+ Sample promot:

> File: what-if-analysis.md
> Score: 29.85
> The document appears to be written at a higher reading level than the target audience. Consider simplifying the language.

[deeper-npl-scan.py](https://github.com/p1ng-request/automation-scripts/blob/main/deeper-nlp-scan.py): Scan docs using NLP
+ Utilizing natural language processing(NLP) techniques to determine complicated words by breaking down the text into individual sentences, followed by computing the Flesch-Kincaid Reading Ease score for each sentence to evaluate readability.
+ Sample prompt:


>Edit data by painting with the **Data Painter** feature, which turns exploratory data analysis processes such as data cleaning and data modeling into clear, intuitive and straightforward tasks.'has a low readability score of 15.65. Consider simplifying the language.

[deeper-ner-scan.py](https://github.com/p1ng-request/automation-scripts/blob/main/deeper-ner-scan.py): Scan docs using NER
+ Apply named entity recognition (NER) to identify specific entities within the text and make suggestions for improvements.
+ Sample prompt:

> File: deployment.md
> Score: 25.892857142857142
> The use of proper names such as (PERSON Customized/NNP Computation/NNP) can sometimes be confusing and can be replaced with more general terms.
