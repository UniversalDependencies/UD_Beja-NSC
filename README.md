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

This version of the treebank is based on the dependency parsing of the original corpus first file (`BEJ_MV_NARR_01_SHELTER`) and a selection of sentences from a file called (`BEJ_MV_NARR_03_CAMEL`).

The data are spoken data, so the segmentation of sentences is a semantically relevant segmentation of utterances, where punctuation represents the end of intonative units (a single `/` for a minor unit and a double `//` for major units).

In the SUD version of the Treebank, we operate a morphological segmentation allowing us to highlight dependency relations between the stem and its affixes or clitics.

In order to follow the UD guidelines, the segmentation is changed for the conversion to UD and affixes are merged with their stems.
A morph-based “UD-like” version is available [here](https://github.com/UniversalDependencies/UD_Beja-NSC/tree/dev/not-to-release).

**UD_beja-NSC** counts 857 tokens for 56 sentences (with the UD segmentation).
The original SUD corpus counts 1101 tokens for 56 sentences.


# Reference

[A morph-based and a word-based treebank for Beja](https://aclanthology.org/2021.tlt-1.5/), Sylvain Kahane, Martine Vanhove, Rayan Ziane, Bruno Guillaume. Proceedings of the 20th International Workshop on Treebanks and Linguistic Theories (TLT, SyntaxFest 2021).

# Acknowledgments

This treebank has been done in collaboration between Vanhove Martine, Ziane Rayan and Kahane Sylvain. Thanks to Bruno Guillaume for the conversion to UD and the help to finalization.


# Changelog

* 2022-05-15 v 2.10
  * New conversion in UD with a new segmentation based on words.

* 2021-05-15 v2.8
  * Initial release in Universal Dependencies.


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
Contact: Martine.VANHOVE@cnrs.fr; sylvain@kahane.fr
===============================================================================
</pre>
