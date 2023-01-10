![Banner](https://raw.githubusercontent.com/p1ng-request/p1ng-request/main/banner.gif)
## Something I have been working on 🎯

[check-dead-links.py](https://github.com/p1ng-request/automation-scripts-best-pracitces/blob/main/check-dead-links.py): A Python script to scan dead links from a given web domain.

[readability-scan.py](https://github.com/p1ng-request/automation-scripts/blob/main/readability-scan.py): Automated Documentation Scanner. Features:
+ Scan all .md files in a given directory and all the sub-directories.
+ Utilizing natural language processing(NLP) techniques to determine complicated words by breaking down the text into individual sentences.
+ Computing the Flesch-Kincaid Reading Ease score for each sentence to evaluate readability.
+ Sample promot:
+ > File: what-if-analysis.md
> Score: 11.9
> The document appears to be written at a higher reading level than the target audience. Consider simplifying the language.
> The sentence: ' RATH has a data painter feature that allows you to perform exploratory data analysis by painting data dots.' has a low readability score > of 19.71. Consider simplifying the language.

[clearity-scan.py](https://github.com/p1ng-request/automation-scripts/blob/main/clearity-scan.py): Scan docs using NER
+ Apply named entity recognition (NER) to identify specific entities within the text and make suggestions for improvements.
+ Sample prompt:

> File: deployment.md
> Score: 25.892857142857142
> The use of proper names such as (PERSON Customized/NNP Computation/NNP) can sometimes be confusing and can be replaced with more general terms.
