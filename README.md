# QA-It: Non-referential It for Question Answering

The QA-It dataset provides manual annotation for the classification of non-referential *it*.
Our dataset is unique because it is annotated on question answer pairs collected from multiple genres, which is useful for developing advanced question answering systems. Our annotation scheme makes clear distinctions between 4 types of pronominal *it*, and provides guidelines for many erroneous cases.

## Reference

* [QA-It: Classifying Non-Referential It for Question Answer Pairs](http://aclweb.org/anthology/P/P16/P16-3020.pdf), Timothy Lee, Alex Lutz, and Jinho D. Choi, In Proceedings of the 54th Annual Meeting of the Association for Computational Linguistics: Student Research Workshop, ACL:SRW'16, 132-137, Berlin, Germany, 2016 ([poster](https://www.slideshare.net/jchoi7s/classifying-nonreferential-it-for-question-answer-pairs)).

## Format

Our corpus is in the TSV format, where each column contains the following contents:

* `0`: the source the data.
* `1`: the genre.
* `2`: the document size (token count).
* `3`: the total count of pronominal *it*.
* `4`: a question answer pair, where the question and the answer are delimited by `>>>>>` and all pronominal *it*s are surrounded by double square brackets, `[[it]]`.
* `5`: the classes of the pronominal *it*s in the question answer pair, where each class is delimited by `,` (e.g., `1,2` implies that the classes of the first and the second pronominal *it*s are `1` and `2`, respectively).

The followings describe the meaning of each class:

* `1`: Non-referential (pleonastic)
* `2`: Referential - nominal
* `3`: Referential - others
* `4`: Error

## Acknowledgement

We gratefully acknowledge the support from the [Emory URC Award](http://www.urc.emory.edu/grants/urc/awards-2015/interdisciplinary-2015.html). Any contents in this material are those of the authors and do not necessarily reflect the views of Emory University.

## Contact

* [Timothy Lee](https://github.com/tlee54)
* [Jinho D. Choi](https://github.com/jdchoi77)
