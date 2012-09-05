wikientities
============

Linking Entities in CommonCrawl Dataset onto Wikipedia Concepts. [Live Demo](http://wikientities.appspot.com/)

Introduction
============
This project is our entry to the [CommonCrawl contest](http://commoncrawl.org/first-ever-code-contest/). The idea is inspired by [Google's release](http://googleresearch.blogspot.sg/2012/05/from-words-to-concepts-and-back.html) of the [entity linking dataset](http://www-nlp.stanford.edu/pubs/crosswikis-data.tar.bz2/), which provides baseline for research on entity linking and other information retrieval and natural language processing tasks.

Human language is ambiguous, and synonymy and polysemy are fundamental problems in natural language processing (NLP) and information retrieval (IR). One of the approaches for Word Sense Disambiguation (WSD) is utilizing external ontologies, e.g. Wikipedia to determine the meaning of a word based on the probabilities that it can be mapped each of the possible Wikipedia concepts. Our entry aims to build such a corpus of anchortext-WikipediaConcept-Count triples from the CommonCrawl dataset, so as to benifit research on WSD, NLP and IR. More specifically, we extract all anchortexts (the text you click on in a webpage link) which point to a Wikipedia page, together with the corresponding Wikipedia page. Based on the corpus, we developed this web application to demonstrate the anchortext-WikipediaConcept-Count structure.

Application scenarios
=====================
* Given a concept (represented as a wikipedia page), it can tell what are the most common terms people use to describe the concept. This can be seen as an "Explicit Topic Modeling". [Example](http://wikientities.appspot.com/concept?concept_name=http%3A%2F%2Fen.wikipedia.org%2Fwiki%2Ffilm)

* Given a sentence, it can help identify entities (person, locatin, organization) in the sentence and map them onto Wikipedia concepts

* CommonCrawl vs. Google, with regards to anchortext-WikipediaConcept-Count corpus richness and precision

* For entity linking tasks, will the combination of both corpus boost the performance compared with the usage of each dataset individually?

Code: https://github.com/chrishan/wikientities

Live Demo: http://wikientities.appspot.com/

Help Spread
============
If you find our work interesting, please vote [our entry on CommonCrawl Contest Website](https://iframe.wizehive.com/voting/view/4f6cd92e-abe0-4178-a52c-4e0b0a22228d/4608/751297/0) and stay tuned for our release of the dataset.