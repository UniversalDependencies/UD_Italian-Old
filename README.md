# Summary

Italian-Old is a treebank containing **Dante Alighieri's Comedy**, based on the 1994 Petrocchi edition and taken from the [**DanteSearch corpus**](https://dantesearch.dantenetwork.it), originally created at the University of Pisa, Italy. The syntactic annotation has been done from scratch, following UD annotation scheme.

It is a treebank of Old Italian, specifically Florentine. The Comedy was composed between approximately 1306 and 1321.


# Introduction

This treebank includes 2 402 sentences (82 644 tokens, counting only single tokens and not considering multi-token words) and is a literary text (poetry). It contains only Inferno and Purgatorio. Specifically, Inferno includes 1 228 sentences and 41 367 tokens and Purgatorio consists of 1 174 sentences and 41 277 tokens. We are currently working on annotating Paradiso.

The treebank is split into three subsets, `dev`, `test` and `train`, with approximate ratios of 10%, 10%, and 80%, respectively, for Inferno and Purgatorio. These subsets are then merged into unique `dev`, `test` and `train` sets.

The distribution of Inferno (tokens: 41367) with respect to the subsets is as follows:
* `train`: 1002 sentences (OldItalian_Dante_Inferno-1; OldItalian_Dante_Inferno-1002) - 33103 tokens
* `dev`: 107 sentences (OldItalian_Dante_Inferno-1003; OldItalian_Dante_Inferno-1109) - 4136 tokens
* `test`: 119 sentences (OldItalian_Dante_Inferno-1110; OldItalian_Dante_Inferno-1228) - 4128 tokens

The distribution of Purgatorio (tokens: 41277) with respect to the subsets is as follows:
* `train`: 958 sentences (OldItalian_Dante_Purgatorio-1; OldItalian_Dante_Purgatorio-958) - 33031 tokens
* `dev`: 100 sentences (OldItalian_Dante_Purgatorio-959; OldItalian_Dante_Purgatorio-1058) - 4130 tokens
* `test`: 116 sentences (OldItalian_Dante_Purgatorio-1059; OldItalian_Dante_Purgatorio-1174) - 4116 tokens

**Since the Italian-Old treebank is going to be expanded to include Paradiso, its structure is subject to changes.**


# Acknowledgments

This work has been carried out in collaboration with the research center CIRCSE (Università Cattolica del Sacro Cuore di Milano).
We extend our gratitude to all the individuals who made this work possible. 
The annotation of the sonnet by Arnaut Daniel (Purgatorio, XXVI vv.140-147) was carried out by Michele Tron.


For any doubts, suggestions, or reports, please do not hesitate to contact the person in charge: claudia.corbetta@unibg.it.


## References

To cite the treebank please refer to:

* C. Corbetta, M. Passarotti, F. M. Cecchini, G. Moretti, Highway to Hell. Towards a Universal Dependencies Treebank for Dante Alighieri’s Comedy, F. Boschetti, G. Lebani, B. Magnini, N. Novielli (Eds.), Proceedings of the Ninth Italian Conference on Computational Linguistics (CLiC-it 2023, Venice,
Italy, Nov 30 - Dec 2 2023), Associazione italiana di linguistica computazionale (AILC).

Other:

* D. Alighieri, La Commedia secondo l’antica vulgata voll. i–iv, number 7 in Edizione nazionale delle Opere di Dante Alighieri a cura della Società Dantesca Italiana, Le Lettere, Florence, Italy, 1994. URL: https://www.lelettere.it/libro/9788871661483, editor: Giorgio Petrocchi.

# Changelog

* 2023-11-15 v2.13
        * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.13
License: CC BY-SA 4.0
Includes text: yes
Genre: poetry
Lemmas: converted with corrections
UPOS: converted with corrections
XPOS: automatic
Features: converted with corrections
Relations: manual native
Contributors: Corbetta, Claudia; Passarotti, Marco; Cecchini, Flavio Massimiliano; Moretti, Giovanni
Contributing: here
Contact: claudia.corbetta@unibg.it
===============================================================================
</pre>
