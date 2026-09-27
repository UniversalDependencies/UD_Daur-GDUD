# Summary

UD_Daur-GDUD is a treebank of Daur (also called Dagur), a Mongolic language spoken in northeastern China, based on grammatical example sentences derived from a reference grammar.


# Introduction

The Daur GDUD (Grammar-Derived Universal Dependencies) treebank contains 95 sentences of Daur (ISO 639-3: dta), a Mongolic language spoken by the Daur people primarily in Heilongjiang and Inner Mongolia (China), with a smaller community in Xinjiang. Daur is one of the more divergent members of the Mongolic family and has been in extensive contact with Manchu, Chinese, and other neighboring languages. The data consist of grammatical example sentences drawn from a reference grammar of Daur, presented in Latin transliteration and accompanied by English translations.

All sentences are manually annotated with lemmas, universal part-of-speech tags (UPOS), morphological features, and dependency relations, following the Universal Dependencies (UD) guidelines. The annotation prioritizes UD core morphological features and dependency relations. The language-specific features `PartType` (Emp, Int) and `ExtPos` are used in a small number of cases, following the analysis of the reference grammar. Additional Daur-specific morphological distinctions that do not correspond to any value in the universal feature inventory are encoded in the MISC column, in accordance with UD conventions.

## Data split

Because the treebank is small (well below the 20K-word threshold), all sentences are provided as test data.

## Morphological annotation

All UD core features used in the treebank take standard universal values, including `Evident=Nfh` on non-firsthand verbal forms. The language-specific features `PartType=Emp` and `PartType=Int` are used on emphatic and interrogative particles.

## Dependency annotation

UD core relations are used throughout the treebank.


# Acknowledgments

The Daur GDUD treebank was created by Wenchao Li and Haitao Liu, based on grammatical example sentences from a reference grammar of Daur. The annotation of lemmas, part-of-speech tags, morphological features, and dependency relations was carried out manually following the Universal Dependencies guidelines.

We thank Daniel Zeman for his guidance in setting up the treebank repository and for his help with the Universal Dependencies workflow, and the Universal Dependencies community for their support.


# Changelog

* 2026-11-15 v2.19
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.19
License: CC BY-SA 4.0
Includes text: yes
Parallel: no
Genre: grammar-examples
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Li, Wenchao; Liu, Haitao
Contributing: here
Contact: widelia@zju.edu.cn
===============================================================================
</pre>
