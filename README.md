The TOROT Treebank
==================

The _TOROT Treebank_ is a dependency treebank with morphosyntactic and
information-structure annotation. It includes texts in several stages of Slavic and is freely available under a [Creative Commons
Attribution-NonCommercial-ShareAlike 3.0 License](
http://creativecommons.org/licenses/by-nc-sa/3.0/us/).

Please cite as

> Hanne Martine Eckhoff and Aleksandrs Berdicevskis. 2015. 'Linguistics vs. digital editions: The Tromsø Old Russian and OCS Treebank'. Scripta & e-Scripta 2015 14–15, pp. 9-25.

Releases of the ISWOC Treebank are hosted on
[Github](https://github.com/torottreebank/treebank-releases).

Contents
--------

The following texts are included in this release of the treebank:

  Text                                                | Language                    | Filename    | Size
  ----                                                | --------                    | --------    | ----
  Codex Suprasliensis                            	  | Old Church Slavonic         | supr        | 70127 tokens
  Codex Zographensis                                  | Old Church Slavonic			| zogr        | 1098 tokens
  Afanasij Nikitin’s journey beyond three seas        | Old Russian                 | afnik       | 6842 tokens
  Charter of Prince Jurij Svjatoslavich of Smolensk on the alliance with Poland and Lithuania, 1386 | Old Russian | smol-pol-lit | 342 tokens
  Domostroj                                           | Old Russian                 | domo        | 23452 tokens
  Life of Sergij of Radonezh                          | Old Russian                 | sergrad     | 20361 tokens
  Missive from Prince Ivan of Pskov, 1463–1465        | Old Russian                 | pskov-ivan   | 335 tokens
  Missive from the Archbishop of Riga to the Prince of Smolensk | Old Russian       | rig-smol1281 | 171 tokens
  Mstislav’s letter                                   |Old Russian                  | mst   	  | 158 tokens
  Novgorod’s treaty with Grand Prince Jaroslav Jaroslavich, 1266 |Old Russian       | novgorod-jaroslav | 423 tokens
  Russkaja pravda                                     | Old Russian                 | rusprav     | 4174 tokens
  Statute of Prince Vladimir                          | Old Russian                 | ust-vlad    | 495 tokens
  The 1229 Treaty between Smolensk, Riga and Gotland (version A) | Old Russian      | riga-goth   | 1421 tokens
  The First Novgorod Chronicle, Synodal manuscript    | Old Russian                 | nov-sin     | 7877  tokens
  The Kiev Chronicle, Codex Hypatianus                | Old Russian   				| kiev-hyp     | 544 tokens
  The Life of Avvakum                                 | Old Russian                 | avv         | 22832 tokens 
| The Primary Chronicle, Codex Hypatianus             | Old Russian                 | pvl-hyp     | 3610 tokens
  The Primary Chronicle, Codex Laurentianus           | Old Russian                 | lav         | 56712 tokens
  The Suzdal Chronicle, Codex Laurentianus            | Old Russian                 | suz-lav     | 17284 tokens 
  The Tale of Dracula                                 | Old Russian                 | drac        | 2487 tokens
  The Tale of Luka Kolocskij                          | Old Russian                 | luk-koloc   | 906 tokens
  The taking of Pskov                                 | Old Russian                 | pskov       | 2326 tokens
  The tale of the fall of Constantinople              | Old Russian                 | const       | 9258 tokens
  Uspenskij sbornik                                   | Old Russian                 | usp-sbor    | 25189 tokens
  Varlaam’s donation charter to the Xutyn monastery   | Old Russian                 | varlaam     | 148 tokens
  Vesti-Kuranty                                       | Old Russian                 | vest-kur    | 1145 tokens

(The 'size' column in the table above shows the number of annotated tokens in
a text. The number of tokens will be slightly larger than the number of words
in the original printed edition as some words have been split into multiple
tokens and some tokens have been inserted during annotation.)

Please see the XML files for detailed metadata and a full list of contributors.

Data formats
------------

The texts are available on two formats:

1. PROIEL XML: These files are the authoritative source files and the only ones
that contain all available annotation. They contain the complete morphological,
syntactic and information-structure annotation, as well as the complete text,
including punctuation, section headers etc. The schema is defined in
[`proiel.xsd`](https://github.com/proiel/proiel-treebank/blob/master/proiel.xsd).

2. [CoNLL-X format](http://nextens.uvt.nl/depparse-wiki/DataFormat)
