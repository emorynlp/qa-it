# QA-It: Non-referential It for Question Answering

This project provides the QA-It corpus that can be used for the classification of non-referential *it*. Our dataset is unique; it is annotated on question answer pairs collected from multiple genres, which is useful for developing advanced question answering systems. Our annotation scheme makes clear distinctions between 4 types of pronominal *it*, and provides guidelines for many erroneous cases.

* [QA-It: Classifying Non-Referential It for Question Answer Pairs](http://aclweb.org/anthology/P/P16/P16-3020.pdf), Timothy Lee, Alex Lutz, Jinho D. Choi, In Proceedings of the 54th Annual Meeting of the Association for Computational Linguistics: Student Research Workshop, ACL'16, Berlin, Germany, 2016 ([poster](http://nlp.mathcs.emory.edu/doc/acl-2016-lee-poster.pdf)).
* Corpus: [v1.0](https://github.com/emorynlp/qa-it/blob/master/qa-it-v1.0.tsv) (last updated: 10/20/2016).

## Format

Our corpus is in the TSV format, where each column contains the following contents:

* `0`: the source the data.
* `1`: the genre.
* `2`: the document size (token count).
* `3`: the total count of pronominal *it*.
* `4`: a question answer pair, where the question and the answer are delimited by `>>>>>` and all pronominal *it*s are surrounded by double square brackets (e.g., `[[it]]`).
* `5`: the classes of the pronominal *it*s in the question answer pair, where each class is delimited by `,` (e.g., `1,2` implies that the classes of the first and the second pronominal *it*s are `1` and `2`, respectively).

The followings describe the meaning of each class:

* `1`: Non-referential (pleonastic)
* `2`: Referential - nominal
* `3`: Referential - others
* `4`: Error
