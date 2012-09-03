wikientities
============

Linking Entities in CommonCrawl Dataset onto Wikipedia Concepts. [Live Demo](http://wikientities.appspot.com/)

Introduction
============
This project is our entry to the [CommonCrawl contest](http://commoncrawl.org/first-ever-code-contest/). Our objective is to find those hyperlinks with link target to Wikipedia concepts and build a probabilistic ontology corpus of "anchorText-WikipediaConcept" pairs.

The idea is inspired by [Google's release](http://googleresearch.blogspot.sg/2012/05/from-words-to-concepts-and-back.html) of the [entity linking dataset](http://www-nlp.stanford.edu/pubs/crosswikis-data.tar.bz2/), which provides baseline for research on entity linking and other information retrieval and natural language processing tasks

By constructing a entity linking corpus from CommonCrawl dataset (50 billion webpages), we want to investigate deeper into the filed and try to anwser the questions like:

* What are the most commonly mapped anchor texts in each of the dataset?
* With regards to linking accuracy and richness, which corpus is better
* For common entity linking tasks, whether the combination of both corpus can boost the performance compared with the usage of each individually?

If you find our work interesting, please vote us on [CommonCrawl Contest Website](https://iframe.wizehive.com/voting/view/4f6cd92e-abe0-4178-a52c-4e0b0a22228d/4608/749105/0) and stay tuned for our release of the source code and dataset