![Banner](https://raw.githubusercontent.com/p1ng-request/p1ng-request/main/banner.gif)
## Something I have been working on 🎯

[check-dead-links.py](https://github.com/p1ng-request/automation-scripts-best-pracitces/blob/main/check-dead-links.py): A Python script to scan dead links from a given web domain.

[docs-scan.py](https://github.com/p1ng-request/automation-scripts/blob/main/docs-scan.py): Automated Documentation Scanner. Features:
+ Scan all .md files in a given directory and all the sub-directories.
+ Utilizing natural language processing(NLP) techniques to determine complicated words by breaking down the text into individual sentences.
+ Evaluate **readability**: the Flesch-Kincaid Reading Ease score.
+ Evalute the **objectivity**: by computing the Automated Readability Index (ARI) and Flesch-Kincaid Grade Level.
+ Evalute **clearity**: Apply named entity recognition (NER) to identify specific words within the text and make suggestions for improvements.
+ Sample promot:

> File: test.md
> Score: 11.9
>The document appears to be written at a lower reading level than the target audience. Consider using more complex vocabulary.
> The document appears to be written in a subjective or non-technical language. Consider changing the language.
> The document appears to be written at a higher reading level than the target audience. Consider simplifying the language.
> The sentence: ' RATH has a data painter feature that allows you to perform exploratory data analysis by painting data dots.' has a low readability score > of 19.71. Consider simplifying the language.
> The use of proper names such as (PERSON Click/NNP) can sometimes be confusing and can be replaced with more general terms.

+ Install dependencies:
```bash
pip3 install nltk textstat pyspellchecker markdown textblob
```
> Python and jre are required for the env
