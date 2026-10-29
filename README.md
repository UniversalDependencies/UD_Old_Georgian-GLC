# Summary

The Old Georgian UD Treebank (UD_Old_Georgian-GLC) is the first syntactically annotated corpus of Georgian, based on a collection of annotated sentences selected from the Old Georgian Language Corpus (OGLC) available at https://oge.iliauni.edu.ge/.


# Introduction

The Old Georgian UD Treebank (UD_Old_Georgian-GLC) serves as the first syntactically annotated corpus of the Old Georgian language. It includes 1232 utterances (33630 tokens) randomly selected from the OGLC (Doborjginidze et al. 2013), providing detailed annotations encompassing the grammatical structure and dependencies within the sentences.

The treebank's annotations align with the Universal Dependencies (UD) specifications, allowing for greater consistency and compatibility with other UD treebanks. Although the tokenization and segmentation principles of the GLC differ slightly from those of the UD, the UD_Old_Georgian-GLC follows the UD approach, particularly regarding multiword tokens, to minimize differences.

Morpho-syntactic annotations, as discussed in Lobzhanidze (2022), have been automatically adapted to UD requirements. This includes annotations for lemmas (LEMMA), part-of-speech categories (UPOS; XPOS), morphological features (FEATS), transliteration, and tokenization issues (MISC). Furthermore, heads of words (HEADS), dependency relations (DEPREL), and enhanced dependency graphs (DEPS) were automatically converted and then reviewed and manually corrected.

The current treebank is divided into three datasets for training, development, and evaluation, with complete source documents assigned to individual partitions to minimize data leakage:
Training set (train): 734 sentences, 20937 syntactic words.
Development set (dev): 122 sentences, 2577 syntactic words.
Test set (test): 376 sentences, 10116 syntactic words.

# Contributors

The development, annotation, expansion, and refinement of the Old Georgian UD Treebank have been carried out by the following contributors:
Nino Doborjginidze
Natia Dundua
Anamaria Glonti
Irina Lobzhanidze

# Acknowledgments

The UD_Old_Georgian-GLC release is based on the data from the Georgian Language Corpus (GLC) developed with the financial support of the Shota Rustaveli National Science Foundation (Project Nos. DP2016_23, LE/17/1-30/13, AR/320/4-105/11, Y-04-10).

Special gratitudes goes to Prof. Dr. Dan Zeman for his invaluable contributions in making the language and dataset available on GitHub and offering valuable suggestions.

## References

Doborjginidze, N., Lobzhanidze. (2012-2026). Georgian language corpus. See, https://oge.iliauni.edu.ge/. Accessed 18 April 2026.

Doborjginidze, N., Lobzhanidze, I., Mirianashvili, G. (2014). Corpus of Georgian Chronicles. See, http://corpora.iliauni.edu.ge/. Accessed 18 April 2026.

Lobzhanidze, I. (2022). Finite-State Computational Morphology: An Analyzer and Generator for Georgian. Cham: Springer.


# Changelog

* 2026-14-18 v2.18
  * Update to README.md
  * Addition of 151 test utterances 

* 2025-11-15 v2.17
  * Initial release in Universal Dependencies.

<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.18
License: CC BY-SA 4.0
Includes text: yes
Parallel: no
Genre: fiction
Lemmas: automatic with corrections
UPOS: converted with corrections
XPOS: automatic with corrections
Features: automatic with corrections
Relations: automatic with corrections
Contributors: Lobzhanidze, Irina
Contributing: here
Contact: irina_lobzhanidze@iliauni.edu.ge
===============================================================================
</pre>
