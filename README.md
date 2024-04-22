# Summary

Italian-Old is a treebank containing **Dante Alighieri's Comedy**, based on the 1994 Petrocchi edition and taken from the [**DanteSearch corpus**](https://dantesearch.dantenetwork.it), originally created at the University of Pisa, Italy. The syntactic annotation has been done from scratch, following UD annotation scheme.

It is a treebank of Old Italian, specifically Florentine. The Comedy was composed between approximately 1306 and 1321.


# Introduction

This treebank includes 1 228 sentences (41 367 tokens, counting only single tokens and not considering multi-token words) and is a literary text (poetry). It contains only the first Cantica of the Comedy, Inferno. We are currently working on annotating Purgatorio and Paradiso.

The treebank is split into three subsets, `dev`, `test` and `train`, with a respective approximate ratio of 10%/10%/80%.
The distribution of the Inferno with respect to the subsets is as follows:

* `train`: 1-18 Canti
* `dev`: 19-26 Canti
* `test`: 27-34 Canti

!!! Since the Italian-Old treebank is going to be expanded to include Purgatorio and Paradiso, its structure is subject to changes.


# Acknowledgments

This work has been carried out in collaboration with the research center CIRCSE (Università Cattolica del Sacro Cuore di Milano) with the support of the University of Pavia.
We extend our gratitude to all the individuals who made this work possible.

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
