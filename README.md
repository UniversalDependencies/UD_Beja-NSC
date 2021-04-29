# Summary

A Universal Dependencies corpus for Beja, North-Cushitic branch of the Afro-Asiatic phylum mainly spoken in Sudan, Egypt and Eritrea.


# Introduction

The treebank is an automatic conversion of the SUD_beja-NSC, which was extracted from Martine Vanhove's corpus in Elan format (https://corpafroas.huma-num.fr/Archives/corpus.php).

Sentences are annotated with the following metadata :
+ sent_id (which indicates the source file and the segmentation identifier in the source file)
+ text (lexical tokenization)
+ text_en (english interpretation)
+ text_tokenized (morphological tokenization)


# Structure

This version of the treebank is based on the dependency parsing of the original corpus first file (BEJ_MV_NARR_01_SHELTER) and a selection of sentences from a file called (BEJ_MV_NARR_03_CAMEL). It counts 1157 tokens for 56 sentences.

The data are spoken data, so the segmentation of sentences is a semantically relevant segmentation of utterances, where punctuation represents the end of intonative units (a single / for a minor unit and a double // for major units).

We operate a morphological segmentation allowing us to highlight dependency relations between the stem and its affixes or clitics.


# Acknowledgments

This treebank has been done in collaboration between Vanhove Martine, Ziane Rayan and Kahane Sylvain. Thanks to Bruno Guillaume for the conversion to UD and the help to finalization.


# Changelog

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
