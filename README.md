# BIOMD0000000459: MODEL1302080001

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000459.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000459.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000459 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Liebal2012 - B.subtilis post-transcription instability model

An important transcription factor of B.subsilis is sigma B . Liebal et al.
(2012) have performed experiments in B.subtilis wild type and mutant straits
to test and validate a mathematical model of the dynamics of sigma B activity.
The following three models were constructed and their ability to fit the
experimental data were tested. 1) Transcription inhibition model
(MODEL1212180000), 2) sigma B proteolysis model (MODEL1302080000) and 3) Post-
transcriptional instability model (MODEL1302080001). This model corresponds to
the post-transcription instability model (MODEL1302080001).

This model is described in the article:

[Proteolysis of beta-galactosidase following SigmaB activation in Bacillus
subtilis.](http://identifiers.org/pubmed/22511268)

Liebal UW, Sappa PK, Millat T, Steil L, Homuth G, Völker U, Wolkenhauer O.

2012 Jun;8(6):1806-14.

Abstract:

In Bacillus subtilis the σ(B) mediated general stress response provides
protection against various environmental and energy related stress conditions.
To better understand the general stress response, we need to explore the
mechanism by which the components interact. Here, we performed experiments in
B. subtilis wild type and mutant strains to test and validate a mathematical
model of the dynamics of σ(B) activity. In the mutant strain BSA115, σ(B)
transcription is inducible by the addition of IPTG and negative control of
σ(B) activity by the anti-sigma factor RsbW is absent. In contrast to our
expectations of a continuous β-galactosidase activity from a ctc::lacZ fusion,
we observed a transient activity in the mutant. To explain this experimental
finding, we constructed mathematical models reflecting different hypotheses
regarding the regulation of σ(B) and β-galactosidase dynamics. Only the model
assuming instability of either ctc::lacZ mRNA or β-galactosidase protein is
able to reproduce the experiments in silico. Subsequent Northern blot
experiments revealed stable high-level ctc::lacZ mRNA concentrations after the
induction of the σ(B) response. Therefore, we conclude that protein
instability following σ(B) activation is the most likely explanation for the
experimental observations. Our results thus support the idea that B. subtilis
increases the cytoplasmic proteolytic degradation to adapt the proteome in
face of environmental challenges following activation of the general stress
response. The findings also have practical implications for the analysis of
stress response dynamics using lacZ reporter gene fusions, a frequently used
strategy for the σ(B) response.

Figure 3a of the reference article has been reproduced. beta-galactosidase
(lacz in model) activity at different concentrations of IPTG (100M, 200M and
1000M) has been reproduced. SED-ML (Simulation Experiment Description Markup
Language) file is available for this model (see curation tab).

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[MODEL1302080001](http://identifiers.org/biomodels.db/MODEL1302080001) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


