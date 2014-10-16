# MODEL7889395724: beeler_reuter_1977_version06

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL7889395724.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL7889395724.git@20140916`

## Usage

Importing the model package.

`import MODEL7889395724 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This is the model described in the article:  
**Reconstruction of the action potential of ventricular myocardial fibres.**   
Beeler GW, Reuter H. _J Physiol._ 1977 Jun;268(1):177-210. Pubmed ID:
[874889](http://www.ncbi.nlm.nih.gov/pubmed/874889) , [full
text](http://www.pubmedcentral.nih.gov/articlerender.fcgi?artid=1283659) at
PubMed central (PMCID:PMC1283659).  
**Abstract:**   
1\. A mathematical model of membrane action potentials of mammalian
ventricular myocardial fibres is described. The reconstruction model is based
as closely as possible on ionic currents which have been measured by the
voltage-clamp method.  
2\. Four individual components of ionic current were formulated mathematically
in terms of Hodgkin-Huxley type equations. The model incorporates two voltage-
and time-dependent inward currents, the excitatory inward sodium current,
i(Na), and a secondary or slow inward current, i(s), primarily carried by
calcium ions. A time-independent outward potassium current, i(K1), exhibiting
inward-going rectification, and a voltage- and time-dependent outward current,
i(x1), primarily carried by potassium ions, are further elements of the model.  
3\. The i(Na) is primarily responsible for the rapid upstroke of the action
potential, while the other current components determine the configuration of
the plateau of the action potential and the re-polarization phase. The
relative importance of inactivation of i(s) and of activation of i(x1) for
termination of the plateau is evaluated by the model.  
4\. Experimental phenomena like slow recovery of the sodium system from
inactivation, frequency dependence of the action potential duration, all-or-
nothing re-polarization, membrane oscillations are adequately described by the
model.  
5\. Possible inadequacies and shortcomings of the model are discussed.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **Beeler, Reuter, 1977 version 8**
](http://www.cellml.org/models/beeler_reuter_1977_version08)  
The original CellML model was created and curated by:  
**Catherine May Lloyd**   
c.lloyd(at)auckland.ac.nz  
University of Auckland, Auckland Bioengineering Institute  

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


