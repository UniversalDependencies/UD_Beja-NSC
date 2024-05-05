# Summary

A Universal Dependencies corpus for Beja, North-Cushitic branch of the Afro-Asiatic phylum mainly spoken in Sudan, Egypt and Eritrea.


# Introduction

The treebank is an automatic conversion of the [SUD_beja-NSC](https://github.com/surfacesyntacticud/SUD_Beja-NSC), which was extracted from Martine Vanhove's corpus in Elan format (https://corpafroas.huma-num.fr/Archives/corpus.php).

Sentences are annotated with the following metadata :
+ `sent_id` (which indicates the source file and the segmentation identifier in the source file)
+ `text` (lexical tokenization)
+ `text_en` (english interpretation)
+ `text_tokenized` (morphological tokenization)

# Structure

The data are spoken data, so the segmentation of sentences is a semantically relevant segmentation of utterances, where punctuation represents the end of intonative units (a single `/` for a minor unit and a double `//` for major units).

In the SUD version of the Treebank, we operate a morphological segmentation allowing us to highlight dependency relations between the root and its affixes or clitics.

In order to follow the UD guidelines, the segmentation is changed for the conversion to UD and affixes are merged with their root.
A morph-based “UD-like” version is available [here](https://github.com/UniversalDependencies/UD_Beja-NSC/tree/dev/not-to-release).

# Reference

[A morph-based and a word-based treebank for Beja](https://aclanthology.org/2021.tlt-1.5/), Sylvain Kahane, Martine Vanhove, Rayan Ziane, Bruno Guillaume. Proceedings of the 20th International Workshop on Treebanks and Linguistic Theories (TLT, SyntaxFest 2021).

# Acknowledgments

This treebank has been done in collaboration between Vanhove Martine, Ziane Rayan and Kahane Sylvain. Thanks to Bruno Guillaume for the conversion to UD and the help to finalization.


# Changelog

* 2024-05-15 v2.14
 * 300 new sentences
 * Original annotation in mSUD (https://github.com/surfacesyntacticud/mSUD_Beja-NSC), see LREC-COLING 2024 paper: [Joint Annotation of Morphology and Syntax in Dependency Treebanks](https://inria.hal.science/hal-04550108)

* 2023-11-15 v2.13
 * Two samples added (06_foreigner and 11_coffee).

* 2022-05-15 v2.10
  * New conversion in UD with a new segmentation based on words.

* 2021-05-15 v2.8
  * Initial release in Universal Dependencies. Two samples (01_shelter and 03_camel).


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.8
License: CC BY-SA 4.0
Includes text: yes
Genre: spoken
Lemmas: not available
UPOS: converted from manual
XPOS: manual native
Features: converted from manual
Relations: converted from manual
Contributors: Vanhove, Martine; Ziane, Rayan; Kahane, Sylvain; Guillaume, Bruno
Contributing: elsewhere
Contact: martine.vanhove@cnrs.fr; sylvain@kahane.fr
===============================================================================
</pre>
