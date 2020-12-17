# Distributed Market Basket Analysis
> PySpark implementation of Apriori Algorithm.

[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)
[![Generic badge](https://img.shields.io/badge/Framework-PySpark-red.svg)](https://shields.io/)
[![Generic badge](https://img.shields.io/badge/Written%20in-Python-green.svg)](https://shields.io/)

Apriori is an algorithm for frequent item set mining and association rule learning over relational databases. It proceeds by identifying the frequent individual items in the database and extending them to larger and larger item sets as long as those item sets appear sufficiently often in the database.

![](Apriori_image.png)

## Objectives:
* Read data and generate frequent items (Support = 85)
* Candidate itemset generation
* Frequent itemset generation (2, 3 and 4 items)
* Association rules generation (Confidence = 90%)

## Input
Online browsing behavior dataset from "browsing.txt" has been used as the input data for the analysis.

## Output

A text file containing the association rules.

## Limitations of Apriori Algorithm

Apriori algorithm suffers from some weakness in spite of being clear and simple. The main limitation is costly wasting of time to hold a vast number of candidate sets with much frequent itemsets, low minimum support or large itemsets.

## Release History

* 0.1.1
    * CHANGE: Update docs (module code remains unchanged)
* 0.1.0
    * The first proper release
* 0.0.1
    * Work in progress

## Meta

Author: [Prasad Hajare](https://www.itsprasad.com/), MS Computer Science

Distributed under the [MIT License](LICENSE).


<!-- Markdown link & img dfn's -->
[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[wiki]: https://github.com/yourname/yourproject/wiki
