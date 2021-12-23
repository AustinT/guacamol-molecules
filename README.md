# GuacaMol Molecules

This repository is my attempt to compile high-scoring molecules for the GuacaMol
goal-directed benchmark objectives 
([paper](https://pubs.acs.org/doi/abs/10.1021/acs.jcim.8b00839),
[code](https://github.com/BenevolentAI/guacamol)).
I hope that these lists of molecules can be useful for method development.
If you have high-scoring molecules which you would like to add to this repository,
please make a pull request or email me!

## Repository structure

### `/top-mols`

This folder contains sorted lists of the overall top molecules that I am aware
of for each objective. It attempts to answer the question "what are the best
possible molecules that could be produced by any algorithm"? There is no
filtering of any kind performed, and as such many of the top molecules contain
unrealistic substructures. Modifying the objectives to disallow such molecules
could potentially be a valuable research project.

Note that all SMILES are in canonical form.

As of 2021-12-23, the sum of the GuacaMol scores of these molecules is 18.495,
which to my knowledge is higher than the output of any algorithm reported in
the literature.

## Acknowledgements and citations

The lists of molecules come from a variety of sources. In particular I would like to
credit the following repositories/papers:

- [MNCE-RL](https://github.com/Zoesgithub/MNCE-RL) repository
- [GEGL](https://github.com/sungsoo-ahn/genetic-expert-guided-learning) repository and my correspondence with the author.

If you would like to cite this repository in any way, please contact me and
I will try to figure out a fair way to attribute credit.
