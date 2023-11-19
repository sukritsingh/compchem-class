Installation
------------

The recommended way to install `OpenMM` is via  [Conda](https://docs.continuum.io/anaconda/install).
Follow this [link](https://docs.continuum.io/anaconda/install) to install `Conda` on your local computer or cluster.
Alternatively, you can also use [Miniconda](https://docs.conda.io/en/latest/miniconda.html), which
has a smaller memory footprint.

Afterwards, use this command to install `OpenMM`:
`conda install -c conda-forge openmm`. For more details - check out the online
[documentation](http://docs.openmm.org/latest/userguide/application/01_getting_started.html#installing-openmm).

We also use a range of other packages in this tutorial for analysis purpose,
you can install them together via:
`conda install -c conda-forge pandas numpy mdtraj nglview pdbfixer`.

Later in the tutorial we'll be using markov models to parse large simulation datasets.
To install [MSMBuilder](https://github.com/msmbuilder/msmbuilder2022), use `conda install -c conda-forge testmsm `.

