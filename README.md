![Banner](https://raw.githubusercontent.com/p1ng-request/p1ng-request/main/banner.gif)
## Something I have been working on 🎯

[broken-links-checker.py](https://github.com/p1ng-request/automation-scripts-best-pracitces/blob/main/broken-links-checker.py): A Python script to scan dead links from a given web domain.

[nlp-docs-scanner.py](https://github.com/p1ng-request/automation-scripts/blob/main/nlp-docs-scanner.py): Automated Documentation Scanner. Features:
+ Scan all .md files in a given directory and all the sub-directories and use natural language processing(NLP) techniques to determine complicated words by breaking down the text into individual sentences.
+ Grammar and Spelling checks are not implemented since Grammaly gives better results than all open sourced spellcheck libraries (many have been deprecated).
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

+ Install dependencies:
```bash
## Install jre and setup env
## Install python and prerequisites library
brew install python3
pip3 install nltk textstat pyspellchecker markdown textblob language-tool-python
```

[ml-docs-scanner.py](https://github.com/p1ng-request/automation-scripts/blob/main/ml-docs-scanner.py)
+ Utilize Machine Learning techniques to perform grammar and spelling checks within a Python script.
+ However, be aware that the execution speed may be significantly slower compared to other methods.
+ The overall accuracy and quality of the results may be s**t, with a high number of false positives.
+ 
