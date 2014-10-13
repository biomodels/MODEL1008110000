

This is the model described in the article:  
**Stimulus specificity of gene expression programs determined by temporal control of IKK activity.**   
by Werner SL, Barken D, Hoffmann A. Science. 2005 Sep 16;309(5742):1857-61;
PMID: [16166517](http://www.ncbi.nlm.nih.gov/pubmed/16166517) , DOI=
[10.1126/science.1113319](http://dx.doi.org/10.1126/science.1113319)  
Abstract:  
A small number of mammalian signaling pathways mediate a myriad of distinct
physiological responses to diverse cellular stimuli. Temporal control of the
signaling module that contains IkappaB kinase (IKK), its substrate inhibitor
of NF-kappaB (IkappaB), and the key inflammatory transcription factor NF-
kappaB can allow for selective gene activation. We have demonstrated that
different inflammatory stimuli induce distinct IKK profiles, and we examined
the underlying molecular mechanisms. Although tumor necrosis factor-alpha
(TNFalpha)-induced IKK activity was rapidly attenuated by negative feedback,
lipopolysaccharide (LPS) signaling and LPS-specific gene expression programs
were dependent on a cytokine-mediated positive feedback mechanism. Thus, the
distinct biological responses to LPS and TNFalpha depend on signaling pathway-
specific mechanisms that regulate the temporal profile of IKK activity.

The model was implemented according to the description in the supplemental
materials and by comparison to the matlab files provided by Prof. Hoffmann. It
includes a delay for the induced transcription of IκBε mRNA. For the IKK input
one of the randomly generated profiles was used. In its current form the model
could not reproduce the time courses given in the article, as first the IKK
activity profiles cannot easily be described by the same fitting functions in
SBML and second the time delay limits simulation to tools, for which the
current converters do not provide full SBML export.

Originally created by libAntimony v1.4 (using libSBML 3.4.1)

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

