# BIOMD0000000228: 

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000228.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000228.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000228 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This is the extended model described the article:  
**Bifurcation analysis of the regulatory modules of the mammalian G1/S transition.**   
Swat M, Kel A, Herzel H. _Bioinformatics_ 2004 Jul 10;20(10):1506-11. PMID:
[15231543](http://www.ncbi.nlm.nih.gov/pubmed/15231543) , doi: [10.1093/bioinf
ormatics/bth110](http://dx.doi.org/10.1093/bioinformatics/bth110)  
**Abstract:**   
MOTIVATION: Mathematical models of the cell cycle can contribute to an
understanding of its basic mechanisms. Modern simulation tools make the
analysis of key components and their interactions very effective. This paper
focuses on the role of small modules and feedbacks in the gene-protein network
governing the G1/S transition in mammalian cells. Mutations in this network
may lead to uncontrolled cell proliferation. Bifurcation analysis helps to
identify the key components of this extremely complex interaction network.  
RESULTS: We identify various positive and negative feedback loops in the
network controlling the G1/S transition. It is shown that the positive
feedback regulation of E2F1 and a double activator-inhibitor module can lead
to bistability. Extensions of the core module preserve the essential features
such as bistability. The complete model exhibits a transcritical bifurcation
in addition to bistability. We relate these bifurcations to the cell cycle
checkpoint and the G1/S phase transition point. Thus, core modules can explain
major features of the complex G1/S network and have a robust decision taking
function.

This model originates from BioModels Database: A Database of Annotated
Published Models. It is copyright (c) 2005-2010 The BioModels Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use [Le Novère N., Bornstein B., Broicher
A., Courtot M., Donizelli M., Dharuri H., Li L., Sauro H., Schilstra M.,
Shapiro B., Snoep J.L., Hucka M. (2006) BioModels Database: A Free,
Centralized Database of Curated, Published, Quantitative Kinetic Models of
Biochemical and Cellular Systems Nucleic Acids Res., 34: D689-D691.](http://ww
w.pubmedcentral.nih.gov/articlerender.fcgi?tool=pubmed&pubmedid=16381960)


