# BIOMD0000000322: Kim2011_Oscillator_SimpleI

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000322.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000322.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000322 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Synthetic in vitro transcriptional oscillators.**   
Kim J, Winfree E _Mol. Syst. Biol._ 2011 Feb 1;7:465.
[21283141](http://www.ncbi.nlm.nih.gov/pubmed/21283141) ,  
**Abstract:**   
The construction of synthetic biochemical circuits from simple components
illuminates how complex beha viors can arise in chemistry and builds a
foundation for future biological technologies. A simplified analog of genetic
regulatory networks, in vitro transcriptional circuits, provides a modular
platform for the systematic construction of arbitrary circuits and requires
only two essential enzymes, bacteri ophage T7 RNA polymerase and Escherichia
coli ribonuclease H, to produce and degrade RNA signals. In t his study, we
design and experimentally demonstrate three transcriptional oscillators in
vitro. First, a negative feedback oscillator comprising two switches,
regulated by excitatory and inhibitory RNA si gnals, showed up to five
complete cycles. To demonstrate modularity and to explore the design space fu
rther, a positive-feedback loop was added that modulates and extends the
oscillatory regime. Finally, a three-switch ring oscillator was constructed
and analyzed. Mathematical modeling guided the design p rocess, identified
experimental conditions likely to yield oscillations, and explained the
system's ro bust response to interference by short degradation products.
Synthetic transcriptional oscillators cou ld prove valuable for systematic
exploration of biochemical circuit design principles and for controll ing
nanoscale devices and orchestrating processes within artificial cells.

**Note:**

The paper describes 7 models (MODEL1012090000-6) and all these are submitted
by the authors. This model (MODEL1012090000) corresponds to the Simple model
for both mode I and II (Design I and II). The model reproduces timecourse
figure plotted in the supplementary material (page 10 of Supplementary
material) of the reference publication.

  

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not.

  

To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


