# A list of tutorials and other resources useful for open science and neuroimaging

* [Brainhack](#brainhack)
* [Open Science](#open-science)
* [GitHub](#github)
* [Shell programming](#shell-programming)
* [Python](#python)
  + [Introduction](#introduction)
  + [Specific topics](#specific-topics)
* [R](#r)
* [Containers](#containers)
* [Other tools for reproducible data-science](#other-tools-for-reproducible-data-science)
* [Open-data platforms](#open-data-platforms)
* [Neuroimaging](#neuroimaging)
  + [Courses and tutorials for the main MRI software packages](#courses-and-tutorials-for-the-main-mri-software-packages)
    - [SPM](#spm)
    - [Freesurfer](#freesurfer)
    - [FSL](#fsl)
    - [AFNI](#afni)
    - [Nipype](#nipype)
    - [Dipy](#dipy)
    - [MRTrix](#mrtrix)
  + [Main EEG and MEG Softwares](#main-eeg-and-meg-softwares)
    - [General Purpose Tools](#general-purpose-tools)
      * [MNE](#mne)
      * [Wonambi](#wonambi)
      * [NeuroKit](#neurokit)
      * [FieldTrip](#fieldtrip)
      * [BrainStorm](#brainstorm)
      * [EEGLab](#eeglab)
      * [SPM](#spm-1)
      * [NutMEG](#nutmeg)
      * [EEGUtils](#eegutils)
      * [EEG.jl](#eegjl)
      * [CarTool](#cartool)
    - [Standalone Tools - Specific Purposes](#standalone-tools---specific-purposes)
      * [NeuroDSP](#neurodsp)
      * [FOOOF](#fooof)
      * [Spectral Connectivity](#spectral-connectivity)
      * [PACTools](#pactools)
      * [Tensor PAC](#tensor-pac)
      * [PyEEG](#pyeeg)
      * [ECoGTools](#ecogtools)
      * [restingIAF](#restingiaf)
      * [Phase Opposition Code](#phase-opposition-code)
      * [ADAM - Amsterdam Decoding and Modeling Toolbox](#adam---amsterdam-decoding-and-modeling-toolbox)
      * [HERMES](#hermes)
      * [SEREEGA - Simualating Event-Related EEG Activity](#sereega---simualating-event-related-eeg-activity)
      * [UNFOLD](#unfold)
      * [ept-TFCE](#ept-tfce)
      * [ERP Reliability Analysis (ERA)](#erp-reliability-analysis-era)
      * [OpenMEEG](#openmeeg)
  + [Quality control](#quality-control)
  + [Analysis](#analysis)
  + [Cloud computing](#cloud-computing)
  + [Reproducible neuroimaging tools](#reproducible-neuroimaging-tools)
    - [The Brain Imaging Data Structure (BIDS)](#the-brain-imaging-data-structure-bids)
    - [Diffusion Microstructure Imaging in Python (Dmipy)](#diffusion-microstructure-imaging-in-python-dmipy)
  + [Other specific topics](#other-specific-topics)
* [Statistics](#statistics)
* [Machine Learning and Deep Learning](#machine-learning-and-deep-learning)
  + [Specific to neuroimaging](#specific-to-neuroimaging)
  + [Softwares for machine learning (or multivariate) analysis in neuroimaging](#softwares-for-machine-learning-or-multivariate-analysis-in-neuroimaging)
    - [pyMVPA](#pymvpa)
    - [nilearn](#nilearn)
    - [neuropredict](#neuropredict)    
    - [TDT](#tdt)
    - [ProNTo](#pronto)
    - [RSA toolbox](#rsa-toolbox)
    - [PCM toolbox](#pcm-toolbox)
    - [cvMANOVA](#cvmanova)
    - [BrainIAK](#brainIAK)
* [Meta analysis](#meta-analysis)
* [Neuroimaging video series](#neuroimaging-video-series)
  + [Mumford brainstats](#mumford-brainstats)
  + [Andrew Jahn](#andrew-jahn)
  + [Center for Brains, Minds and Machines](#center-for-brains-minds-and-machines)
  + [Organization from human brain mapping (OHBM)](#organization-from-human-brain-mapping-ohbm)
  + [fMRIf summer courses from the NIH](#fmrif-summer-courses-from-the-nih)
  + [Conference on Cognitive Computational Neuroscience (CCN)](#conference-on-cognitive-computational-neuroscience-ccn)


The following list is by far not exhaustive, you will be able to find more resources in the following:
* the [Neuroimaging Informatics Tools and Resources Clearinghouse](https://www.nitrc.org/)
* [Mariam Aly's](https://twitter.com/mariam_s_aly) [lab wiki](https://osf.io/kgd9b/wiki/home/)
* [Jonathan Peelle's](@jpeelle) [list of resources for beignners](http://jonathanpeelle.net/mri-resources-for-beginners)
* [Stephan Heunis](https://twitter.com/fmrwhy) has a [list](https://www.fmrwhy.com/2018/06/28/spm12-matlab-scripting-tutorial-4/) to many SPM and matlab material.
* [https://github.com/brainhack101](https://github.com/brainhack101) also has a [collections or links](https://brainhack101.github.io/neurolinks/) to courses, data...
* [open neuroscience](https://openeuroscience.com/) points to a lot of open things related to neuroscience.
* a [list](https://docs.google.com/document/d/1Wt6sZUavq4oQf4t3tpQARcajf-6i4TtHlx_lw-WJD1U/edit#heading=h.rgwbys315r9s) of Scientific Coding Resource put together by neuroconscience.
* [Aya Ben-Yakov](@aya_ben_yakov) compiled a great list of [open-science resources](http://www.mrc-cbu.cam.ac.uk/openscience/resources/) for the CBU in Cambridge.
* [LabHacks](https://github.com/pbeukema/LabHacks) is a list of resources for data driven neuroscientists put together by Patrick Beukema
* a list of [open computational neuroscience resources](‏ https://github.com/asoplata/open-computational-neuroscience-resources/blob/master/README.md) put together by [Austin Soplata](https://twitter.com/austinsoplata)
* a list of [Computational resources](https://github.com/martinagvilas/lists/blob/master/computational_resources.md) put together by [Martina Vilas](https://twitter.com/martinagvilas)


## Brainhack
* [Brainhacking](https://neurohackademy.org/course/brain-hacking/) by Cameron Craddock within Neurohackademy 2018 (59 min)
* Craddock, R. C., Margulies, D. S., Bellec, P., Nichols, B. N., Alcauter, S., Barrios, F. A., … Xu, T. (2016). [Brainhack: a collaborative workshop for the open neuroscience community.](https://doi.org/10.1186/s13742-016-0121-x) GigaScience, 5(1).
* [Introduction to Brainhack](https://www.youtube.com/watch?v=JLJFKV7p74A) by Cameron Craddock within Brainhack Proceedings 2017 (30 min)   
* [Introduction to Neurohackweek 2017](https://neurohackademy.org/course/introduction-to-neurohackweek-4/) by Ariel Rokem within Neurohackweek 2017


## Open Science
* [The Open Science MOOC](https://opensciencemooc.eu/)
* [Panel discussion: fostering open communities](https://neurohackademy.org/course/panel-discussion-fostering-open-communities/) within Neurohackademy 2018 (1 hr 30 min)
* [Science: open for all](https://neurohackademy.org/course/science-open-for-all/) by Kirstie Whitaker within Neurohackademy 2018
* [Surviving and thriving as an open scientist](https://neurohackademy.org/course/surviving-and-thriving-as-an-open-scientist/) by Tal Yarkoni within Neurohackweek 2016


## GitHub
* [A Quick Introduction to Version Control with
Git and GitHub](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004668) by Bilschak et al. (2016)
* [Introduction to git and GitHub](https://www.youtube.com/watch?v=XyMCsEGPcjM&list=PLNt4AJV1JZbfq0vdD4vcITV7x3OqGxLKp) by Chris Gorgolewski within Brainhack Americas (45 min)
* [Git and Github 1 & 2](https://neurohackademy.org/course/git-and-github/) by Bernease Herman within Neurohackweek 2016
* [Git tutorial](https://www.youtube.com/watch?v=0DGCnBZBoc0&index=2&t=5s&list=PLEE6ggCEJ0H0KOlMKx_PUVB_16VoCfGj9) by Eshin Jolly within MIND 2018 (36 min)
* [Pro Git](https://git-scm.com/book/en/v2) by Scott Chacon and Ben Straub
* [What is GitHub and how to use it](https://www.youtube.com/watch?v=AnftV9HBPSc) (17 min)
* [Learn Git Branching](https://learngitbranching.js.org/) Neat interactive introduction to Git, like an online game!

## Shell programming
* [Conquering the command line](http://conqueringthecommandline.com/book/frontmatter)
* [Learn shell](https://www.learnshell.org/)
* [The shell introduction I wish I had](https://dev.to/maxwell_dev/the-shell-introduction-i-wish-i-had-551k) by Max Antonucci
* [The Unix shell](http://swcarpentry.github.io/shell-novice/)
* [Andrew Jahn's Unix introduction](https://www.youtube.com/watch?v=dBDmIhSWfnM&list=PLIQIswOrUH6992C4FDDCNCIaK4R2FIOCB)
* [Bash cheatsheet](https://devhints.io/bash)
* [Explain shell commands](https://explainshell.com/)
* [Check shell scripts](https://www.shellcheck.net/)
* [Vim interactive tutorial](https://www.openvim.com/)


## Python
### Introduction
* [A whirlwind tour of python](https://jakevdp.github.io/WhirlwindTourOfPython/) by Jake Vanderplas
* [Introduction to Python](https://www.youtube.com/watch?v=3y55b_Md-N8&list=PLNt4AJV1JZbfq0vdD4vcITV7x3OqGxLKp&t=0s&index=3) within Brainhack Americas (45 min)
* [Introduction to Python](https://neurohackademy.org/course/introduction-to-python/) by Tal Yarkoni within Neurohackademy 2018 (1 hr 16 min)
* [Python programming](https://neurohackademy.org/course/python-programming/) by Valentina Staneva within Neurohackweek 2016
* [Python tips and tricks](https://neurohackademy.org/course/python-tips-and-tricks/) by Tal Yarkoni within Neurohackweek 2016 (58 min)
* [Scientific computing with Python](https://www.youtube.com/watch?v=RhNfnQlnCEo&index=18&t=0s&list=PLEE6ggCEJ0H0KOlMKx_PUVB_16VoCfGj9) by Luke Chang within MIND 2018 (24 min)
* [An introduction to Python!](https://cogs18.github.io/intro/) is course made by Thomas Donoghue

### Specific topics
* [Cython and numba](https://neurohackademy.org/course/cython-and-numba/) by Ariel Rokem within Neurohackweek 2016
* [Data manipulation in Python/Pandas](https://neurohackademy.org/course/complex-data-structures/) by Tal Yarkoni within Neurohackademy 2018 (1 hr 21 min)
* [High-performance Python](https://neurohackademy.org/course/high-performance-python/) by Ariel Rokem within Neurohackweek 2016
* [Modular Software Design](https://neurohackademy.org/course/modular-software-design/) by Jeremy Freeman within Neurohackweek 2016 (48 min)
* [Python packaging](https://neurohackademy.org/course/python-packaging/) by Ariel Rokem within Neurohackademy 2018 (1 hr 26 min)
* [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/) by Jake Vanderplas
* [Science Hacking 101](https://www.youtube.com/watch?v=Gin8_AITmS0) by Jeremy Manning within MIND 2018
* [Software testing 1](https://neurohackademy.org/course/software-testing/) by Chris Gorgolewski within Neurohackweek
* [Software testing 2](https://neurohackademy.org/course/software-testing-2/) by Chris Gorgolewski within Neurohackweek
* [Testing scientific code](https://neurohackademy.org/course/testing-scientific-code/) by Chris Gorgolewski within Neurohackweek 2017 (43 min)
* [Porting Python 2 code to Python 3 - official](https://docs.python.org/3/howto/pyporting.html)
  * [guide 2 - another migration guide](http://blog.pyspoken.com/2018/02/13/python-2-to-3-migration-guide/)
  * [gudie 3 - migration strategies](http://python3porting.com/strategies.html)
  * [guide 4 - practicalities and packaging](https://python3statement.org/practicalities)


## R
* [Programming with R](https://neurohackademy.org/course/programming-with-r/) by Jeanette Mumford within Neurohackweek 2016   
* [Introduction to Neurohacking in R](https://www.coursera.org/learn/neurohacking) MOOC on coursera


## Containers
* [Docker for scientists 1](https://neurohackademy.org/course/docker-for-scientists/) by Chris Gorgolewski within Neurohackweek 2016 (1 hr 13min)  
* [Docker for scientists 2](https://neurohackademy.org/course/docker/) by Chris Gorgolewski within Neurohackweek
* [Docker tutorial](https://www.youtube.com/watch?v=hUvYdXo5MfU&index=17&t=0s&list=PLEE6ggCEJ0H0KOlMKx_PUVB_16VoCfGj9) by Lucy Owen within MIND 2018 (20 min)
* [Neurodocker](https://github.com/kaczmarj/neurodocker) allows you to easily create containers suited to your neuroimaging needs. Here is a [tutorial](https://miykael.github.io/nipype_tutorial/notebooks/introduction_neurodocker.html) on how to use it.


## Other tools for reproducible data-science
* [From interactive exploration to reproducible data science: Jupyter, Binder, Travis and friends.](https://neurohackademy.org/course/from-interactive-exploration-to-reproducible-data-science-jupyter-binder-travis-and-friends/) by Fernando Perez within Neurohackademy 2018 (1 hr 25 min)
* [Jupyter tutorial](https://www.youtube.com/watch?v=CSkTJRNBTME&index=3&t=4s&list=PLEE6ggCEJ0H0KOlMKx_PUVB_16VoCfGj9) by Eshin Jolly within MIND 2018 (31 min)


## Open-data platforms
* [Allen Institute Data and Software](https://neurohackademy.org/course/allen-institute-data-and-software/) by Nicolas Cain within Neurohackweek 2017 (53 min)
* [Allen Institute Datasets](https://neurohackademy.org/course/allen-institute-datasets/) by Terri Gilbert within Neurohackweek 2016 (1 hr 8min)
* [Allen Institute RNAseq data](https://neurohackademy.org/course/allen-institute-rnaseq-data/) by Jeremy Miller within Neurohackweek 2016 (52 min)
* [AllenSDK and the Allen Brain Observatory](https://neurohackademy.org/course/allensdk-and-the-allen-brain-observatory/) by Nicolas Cain and Justin Kiggins within Neurohackademy 2018 (1 hr 42 min)
* [Integrating Allen Institute Datasets with MRI data](https://neurohackademy.org/course/integrating-allen-institute-datasets-with-mri-data/) by Kirstie Whitaker within Neurohackweek 2016 (28 min)

Some other platforms to get data from:
* [OpenNeuro](https://openneuro.org/)
* [INDI](http://fcon_1000.projects.nitrc.org/) for rawdata
* [neurovault](https://neurovault.org/) for statistical maps
* [BALSA](https://balsa.wustl.edu/)
* [LORIS](https://github.com/aces/Loris/wiki/Open-LORIS)
* [XNAT](https://www.nitrc.org/ir/)
* And there are [many](https://brainhack101.github.io/neurolinks/) other [possibilities](https://en.wikipedia.org/wiki/List_of_neuroscience_databases)

If you are looking for M/EEG data there is good list of options [here](https://github.com/voytekresearch/OpenData)

If you want to share data but your colleagues argue against it:
* [Challenges to open data and how to respond](https://github.com/mozillascience/open-data-training/blob/master/Materials/Handouts/ODChallengesQI.md)


## Neuroimaging
* [Tor Wager's](https://twitter.com/torwager) and Martin Lindquist's 2 parts MOOC on neuroimaging ([part 1](https://en.coursera.org/learn/functional-mri)
 and [part 2](https://en.coursera.org/learn/functional-mri-2))

### Courses and tutorials for the main MRI software packages

#### SPM
* [website](https://www.fil.ion.ucl.ac.uk/spm/)
* [manual](https://www.fil.ion.ucl.ac.uk/spm/doc/)
* [mailing list](https://www.fil.ion.ucl.ac.uk/spm/support/)
* [course/tutorial](http://www.fil.ion.ucl.ac.uk/spm/course/)

#### Freesurfer
* [website](https://surfer.nmr.mgh.harvard.edu/)
* [manual](https://surfer.nmr.mgh.harvard.edu/fswiki)
* [mailing list](https://surfer.nmr.mgh.harvard.edu/fswiki/FreeSurferSupport)
* [course](https://www.youtube.com/channel/UCruQerP8aa-gYttXkAcyveA) and [videos](https://surfer.nmr.mgh.harvard.edu/fswiki/CourseDescription)

#### FSL
* [website](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki)
* [manual](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/Support)
* [mailing list](https://www.jiscmail.ac.uk/cgi-bin/webadmin?A0=fsl)
* [course/tutorial](https://fsl.fmrib.ox.ac.uk/fslcourse/)

#### AFNI
* [website](https://afni.nimh.nih.gov/)
* [manual](https://afni.nimh.nih.gov/pub/dist/doc/htmldoc/index.html)
* [mailing list](https://afni.nimh.nih.gov/afni/community/board/list.php?1)
* [course/tutorial]: Video recordings from the [AFNI bootcamp](https://afni.nimh.nih.gov/pub/dist/doc/htmldoc/educational/bootcamp_recordings.html), with slides, and [example data](https://afni.nimh.nih.gov/pub/dist/doc/htmldoc/background_install/unix_tutorial/misc/install.data.html).

#### Nipype
Nipype is best viewed as a way to create and run software-agnostic preprocessing/analysis-pipeline. It becomes very powerful when you need to use different softwares in your analysis.
* [website](https://nipype.readthedocs.io/en/latest/)
* [manual](https://nipype.readthedocs.io/en/latest/documentation.html)
* [course/tutorial](https://miykael.github.io/nipype_tutorial/)

#### Dipy
Diffusion neuroimaging in Python
* [website](https://github.com/ohbm/hackathon2019)

#### MRtrix
Advanced tools for the analysis of diffusion MRI data
* [website](http://www.mrtrix.org/)
* [documentation](https://mrtrix.readthedocs.io/en/latest/)
* [tutorial](https://osf.io/fkyht/). MRtrix tutorial available on OSF with an awesome title: B.A.T.M.A.N., the Basic and Advanced Tractography with MRtrix for All Neurophiles

### Main EEG and MEG Softwares

The following list has been shamelessly taken from the excellent repo [Open Software for Human Electrophysiology](https://github.com/voytekresearch/OpenTools). Do check it out as it also includes plugins that are not listed here.

#### General Purpose Tools

The following are general purpose platforms, with functionality including: loading data, pre-processing, visualization, standard analysis, and making figures. They are divided in sub-sections depending on the language they use.


![Language](https://img.shields.io/badge/Language-Python-blue.svg)

##### MNE
MNE is a general purpose tool for processing, analyzing and visualizing M/EEG data.

[HomePage](http://martinos.org/mne/stable/index.html)
[Github](https://github.com/mne-tools/mne-python)
[Paper](https://doi.org/10.1016/j.neuroimage.2013.10.027)

##### Wonambi
Wonambi is a general purpose tool for processing, analyzing and visualizing EEG data, including specific tools focused on sleep scoring and analysis.

[HomePage](https://wonambi-python.github.io)
[Github](https://github.com/wonambi-python/wonambi)

##### NeuroKit
NeuroKit is a tool for neurophysiological signal processing.

[HomePage](http://neurokit.readthedocs.io/en/latest/)
[Github](https://github.com/neuropsychology/NeuroKit.py)


![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)

##### FieldTrip
FieldTrip is a general purpose tool for processing, analyzing and visualizing M/EEG and iEEG/ECoG data.

[HomePage](http://www.fieldtriptoolbox.org)
[Github](https://github.com/fieldtrip/fieldtrip)
[Paper](https://doi.org/10.1155/2011/156869)

##### BrainStorm
BrainStorm is a general purpose tool for processing, analyzing and visualizing focused primarily on MEG data, but includes support for EEG & ECoG data.

[HomePage](https://neuroimage.usc.edu/brainstorm/)
[Github](https://github.com/brainstorm-tools/brainstorm3)
[Paper](https://doi.org/10.1155/2011/879716)

##### EEGLab
EEGLab is a general purpose tool for processing, analyzing and visualizing EEG data.

[HomePage](https://sccn.ucsd.edu/eeglab/index.php)
[Paper](https://doi.org/10.1016/j.jneumeth.2003.10.009)

##### SPM
SPM is a general purpose toolbox for neuroimaging, that includes support for processing M/EEG data.

[HomePage](https://www.fil.ion.ucl.ac.uk/spm/)

##### NutMEG
NutMEG is a general purpose tool for processing, analyzing and visualizing MEG data.

[HomePage](https://www.nitrc.org/plugins/mwiki/index.php/nutmeg:MainPage)
[Github](https://github.com/UCSFBiomagneticImagingLab/nutmeg)
[Paper](https://doi.org/10.1155/2011/758973)


![Language](https://img.shields.io/badge/Language-R-lightgrey.svg)

##### EEGUtils
EEGUtils is a general purpose tool for processing, analyzing and visualizing EEG data.

[HomePage](https://craddm.github.io/eegUtils/)
[Github](https://github.com/craddm/eegUtils)


![Language](https://img.shields.io/badge/Language-Julia-green.svg)

##### EEG.jl
EEG.jl is an EEG processing library.

[HomePage](https://eegjl.readthedocs.io/en/latest/)
[Github](https://github.com/rob-luke/EEG.jl)


![Language](https://img.shields.io/badge/Language-C++-yellowgreen.svg)

##### CarTool
CarTool is an EEG analysis toolbox.

[HomePage](https://sites.google.com/site/cartoolcommunity/)
[Paper](https://doi.org/10.1155/2011/813870)

#### Standalone Tools - Specific Purposes


![Language](https://img.shields.io/badge/Language-Python-blue.svg)

##### NeuroDSP
NeuroDSP is a package for calculating a broad range of measures on neural time series, including a range of time-domain measures such as waveform shape analyses.

Note: NeuroDSP is a tool developed by the VoytekLab.

[Github](https://github.com/voytekresearch/neurodsp)

##### FOOOF
FOOOF is a package for parameterizing neural power spectra.

Note: FOOOF is a tool developed by the VoytekLab.

[Github](https://github.com/voytekresearch/fooof)
[Paper](https://doi.org/10.1101/299859)

##### Spectral Connectivity
Spectral connectivity is a package including a group of functional connectivity and coherence related measures.

[HomePage](http://spectral-connectivity.readthedocs.io/en/latest/index.html)
[Github](https://github.com/Eden-Kramer-Lab/spectral_connectivity)

##### PACTools
PACTools is a package for calculating phase-amplitude coupling measures in neural time series.

[HomePage](https://pactools.github.io)
[Github](https://github.com/pactools/pactools)

##### Tensor PAC
Tensor PAC is a tool for calculating phase-amplitude coupling measures, using tensors and parallel computing.

[HomePage](https://etiennecmb.github.io/tensorpac/)
[Github](https://github.com/EtienneCmb/tensorpac)

##### PyEEG
PyEEG includes some implementations of information theoretic and complexity related measures for neural time series.

[Github](https://github.com/forrestbao/pyeeg)
[Paper](https://doi.org/10.1155/2011/406391)

##### ECoGTools
A collection of tools for analyzing ECoG data.

[Github](https://github.com/choldgraf/ecogtools)


![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)

##### restingIAF
RestingIAF is a tool for estimating the peak individual alpha frequency.

[Github](https://github.com/corcorana/restingIAF)
[Paper](https://doi.org/10.1111/psyp.13064)

##### Phase Opposition Code
Phase Opposition is a collection of functions for calculating phase opposition measures.

[HomePage](http://www.cerco.ups-tlse.fr/~rufin/PhaseOppositionCode/)
[Paper](https://doi.org/10.3389/fnins.2016.00426)

##### ADAM - Amsterdam Decoding and Modeling Toolbox
The Amsterdam Decoding and Modeling Toolbox does encoding and decoding model analysis on M/EEG data.

[Github](https://github.com/fahrenfort/ADAM)
[Paper](https://doi.org/10.1007/s12021-013-9186-1)

##### HERMES
HERMES is tool for estimating connectivity measures between M/EEG signals.

[HomePage](http://hermes.ctb.upm.es)
[Github](https://github.com/guiomar/HERMES)
[Paper](https://doi.org/10.3389/fnins.2018.00368)


##### SEREEGA - Simualating Event-Related EEG Activity
SEREEGA is a package for simulating synthetic data that mimic event-related EEG activity.

[Github](https://github.com/lrkrol/SEREEGA)
[Paper](https://doi.org/10.1101/326066)

##### UNFOLD
Unfold is a tool for deconvolving overlapping EEG signals and for non-linear modelling.

[HomePage](https://www.unfoldtoolbox.org)
[Github](https://github.com/unfoldtoolbox/unfold)
[Paper](https://doi.org/10.1101/360156)

##### ept-TFCE
A tool for statistical analysis of already pre-processed M/EEG data, focused mainly around the 'threshold-free cluster enhancement' method.

[Github](https://github.com/Mensen/ept_TFCE-matlab)
[Paper](https://doi.org/10.1016/j.neuroimage.2012.10.027)

##### ERP Reliability Analysis (ERA)
ERA is a tool for calculating reliability estimates for ERP data.

[HomePage](http://peterclayson.com/era-toolbox/)
[Github](https://github.com/peclayson/ERA_Toolbox)
[Paper](https://doi.org/10.1016/j.ijpsycho.2016.10.012)


![Language](https://img.shields.io/badge/Language-C++-yellowgreen.svg)

##### OpenMEEG
OpemMEEG is a package for solving forward problems for EEG & MEG data.

[HomePage](http://openmeeg.github.io)
[Github](https://github.com/openmeeg/openmeeg)
[Paper](https://doi.org/10.1186/1475-925X-9-45)


### Quality control
Be sure to check the newly formed [Neuroimaging quality control task force](https://crossinvalidation.com/2018/07/31/neuroimaging-quality-control-niqc-task-force-to-develop-protocols-tools-and-manuals/)

* [quality control on MRI and fMRI](https://practicalfmri.blogspot.com/2014/08/qa-for-fmri-part-3-facility-qa-what-to.html)
* [COBIDacq](https://practicalfmri.blogspot.com/2017/12/cobidacq.html)
* [In the wikibook neuroimaging data processing](https://en.wikibooks.org/wiki/Neuroimaging_Data_Processing/Data_Quality)
* [References for quality control](https://www.zotero.org/groups/2221093/niqc)

* [MRIQC](https://mriqc.readthedocs.io/en/stable/) MRI quality control. A BIDS app that runs a pipeline to assess the quality of your data.
* [the PCP Quality Assessment Protocol](https://github.com/BIDS-Apps/QAP) is another BIDS app based on the protocol of [the connectome project data}(http://preprocessed-connectomes-project.org/quality-assessment-protocol/)
* [Scripts for quality control of diffusion data](http://davidroalf.com/script_download/)
* [Qoala-t](https://github.com/Qoala-T) for QA for freesurfer segmentations also with an online [shinyapp](https://qoala-t.shinyapps.io/qoala-t_app/)
* [Visual QC](https://github.com/raamana/visualqc) developed by [Pradeep](https://twitter.com/raamana_).


### Analysis
* [Advanced time-series analysis (Dynamic Mode Decomposition)](https://neurohackademy.org/course/advanced-time-series-analysis-dynamic-mode-decomposition/) by Bing Brunton within Neurohackweek 2017 (1 hr 1 min)
* [Advanced time-series analysis](https://neurohackademy.org/course/advanced-time-series-analysis/) by Bing Brunton within Neurohackweek 2016 (1 hr 8 min)
* [Data visualization](https://neurohackademy.org/course/data-visualization/) by Tal Yarkoni within Neurohackademy 2018
* [Efficiency and Design Optimization for fMRI](https://neurohackademy.org/course/efficiency-and-design-optimization-for-fmri/) by Jeanette Mumford within Neurohackweek 2017 (51 min)
* [Image processing](https://neurohackademy.org/course/image-processing/) by Ariel Rokem within Neurohackweek 2016
* [Modeling fMRI data](https://neurohackademy.org/course/modeling-fmri-data/) by Kendrick Kay within Neurohackweek 2016 (1 hr 2 min)
* [NiBabel 101](https://www.youtube.com/watch?v=9ffUQo2mF6w&list=PLNt4AJV1JZbfq0vdD4vcITV7x3OqGxLKp&t=0s&index=4) by Dan Lurie within Brainhack Americas (18 min)
* [Numerical computing for neuroimaging](https://neurohackademy.org/course/numerical-computing-for-neuroimaging/) by JB Poline within Neurohackademy 2018
* [R for statistical analysis of fMRI data](https://neurohackademy.org/course/r-for-statistical-analysis-of-fmri-data/) by Tara Madhyastha within Neurohackademy 2018 (1 hr 26 min)
* [A video series on dynamic causal modeling](https://www.youtube.com/watch?v=q-yypnHgCII&list=PLwiAO9Cs0Tb8wUGAnYY5yIMckB9tc4T3_) by [Kevin Aquino](https://twitter.com/kevin_m_aquino) [6 hrs]
* A blog post [tutorial](https://medium.com/@solopchuk/tutorial-on-active-inference-30edcf50f5dc) on active inference (to get a better grasp on what free energy is)

### Cloud computing
* [Cloud Computing for Neuroimaging 1](https://neurohackademy.org/course/cloud-computing-for-neuroimaging/) by Amanda Tan and Ariel Rokem within Neurohackademy 2018 (3 hr 9 min)
* [Cloud Computing for Neuroimaging 2](https://neurohackademy.org/course/cloud-computing/) by Tara Madhyastha within Neurohackweek 2016
* [Using cloud computing for neuroimaging](https://neurohackademy.org/course/using-cloud-computing-for-neuroimaging/) by Cameron Craddock within Neurohackweek 2016


### Reproducible neuroimaging tools
* ReproNim is a good [site](http://www.reproducibleimaging.org/index.html) to get up to date on doing reproducible neuroimaging research.
* [Advance Unix and Make](https://neurohackademy.org/course/advance-unix-and-make/) by Valentina Staneva and Tara Madhyastha within Neurohackweek 2016  
* [CRN resources](https://neurohackademy.org/course/crn-resources/) by Chris Gorgolewski within Neurohackweek
* [Improving the Reproducibility of Neuroimaging Research](https://neurohackademy.org/course/improving-the-reproducibility-of-neuroimaging-research/) by Russ Poldrack within Neurohackweek 2016 (1 hr 23 min)
* [GNU Make for Neuroimaging Workflows](https://neurohackademy.org/course/gnu-make-for-neuroimaging-workflows/) by Tara Madhyastha within Neurohackweek 2016 (48 min)
* [Introduction to web technologies](https://neurohackademy.org/course/introduction-to-web-technologies/) by Anisha Keshavan within Neurohackademy 2018 (56 min)
* [Neuroimaging pipelines](https://neurohackademy.org/course/neuroimaging-pipelines-2/) by Satra Ghosh within Neurohackweek 2017 (1 hr 33 min)
* [Reproducibility in fMRI: What is the problem? 1](https://neurohackademy.org/course/reproducibility-in-fmri-what-is-the-problem-2/) by Russ Poldrack within Neurohackweek 2017 (1 hr 40 min)
* [Reproducibility in fMRI: What is the problem? 2](https://neurohackademy.org/course/reproducibility-in-fmri-what-is-the-problem-3/) by Russ Poldrack within Neurohackweek 2017
* [Same Data - Different Software - Different Results? Analytic Variability of Group fMRI Results](https://www.pathlms.com/ohbm/courses/8246/sections/12541/video_presentations/116000) by Alexander Bowring (12 mins)
* [Reproducible research pipelines](https://neurohackademy.org/course/reproducible-research-pipelines/) by Chris Gorgolewski and Satra Ghosh within Neurohackweek 2016
* [Software pipelines for reproducible neuroimaging](https://neurohackademy.org/course/software-pipelines-for-reproducible-neuroimaging/) by Satra Ghosh and Chris Gorgolewski within Neurohackademy 2016 (1 hr 14 min)
* [Neuroimaging Workflows & Statistics for reproducibility](https://www.pathlms.com/ohbm/courses/8246/sections/12542/video_presentations/115885) by Dorota Jarecka, Satrajit Ghosh, Celia Greenwood and Jean-Baptiste Poline at OHBM (3 hr 45 min)
* [Tools from the Center for Open Neuroscience](https://www.youtube.com/watch?v=RBaJn2Xtqzg&index=8&t=2278s&list=PLEE6ggCEJ0H0KOlMKx_PUVB_16VoCfGj9) by Yaroslav Halchenko within MIND 2018
* [Code-ocean](https://codeocean.com/) is web based service that uses docker containers to let you run your analysis online. There is [post](https://www.fmrwhy.com/2018/10/31/reproducible-fmri-codeocean/) by [Stephan Heunis](https://twitter.com/fmrwhy) describing how he did that with an SPM pipeline.

#### The Brain Imaging Data Structure (BIDS)
* [The Brain Imaging Data Structure (BIDS)](https://neurohackademy.org/course/the-brain-imaging-data-structure-bids/) presented by Chris Gorgolewski within Neurohackademy 2018 (56 min)
* the [BIDS website](http://bids.neuroimaging.io/)
* the [BIDS apps](bids-apps.neuroimaging.io/apps/)
* the [BIDS starter kit](https://github.com/bids-standard/bids-starter-kit)

#### Diffusion Microstructure Imaging in Python (Dmipy)
The Dmipy software project is dedicated to fasciliting high-level, reproducible diffusion microstructure research.
* The [Dmipy open-source repository](https://github.com/AthenaEPI/dmipy) with many examples on implementing and fitting microstructure models.
* Our Preliminary [Reference Paper](https://hal.inria.fr/hal-01873353/file/dmipy-diffusion-microstructure.pdf)


### Other specific topics
* [Computer Vision](https://neurohackademy.org/course/computer-vision/) by Michael Beyeler within Neurohackademy 2018 (53 min)
* [Finding low-dimensional structure in large-scale neural recordings](https://neurohackademy.org/course/finding-low-dimensional-structure-in-large-scale-neural-recordings/) by Eva Dyer within Neurohackademy 2018 (1 hr 36 min)
* [Interactive Data Visualization with D3](https://neurohackademy.org/course/interactive-data-visualization-with-d3/) by Anisha Keshavan within Neurohackweek 2017 (49 min)
* [Neuroethics](https://neurohackademy.org/course/neuroethics/) by Eran Klein within Neurohackademy 2018 (58 min)
* [Quantitative and diffusion MRI modeling of developmental data](https://neurohackademy.org/course/quantitative-and-diffusion-mri-modeling-of-developmental-data/) by Yason Yeatman within Neurohackweek


## Statistics
* [P-values and reproducibility issues](https://neurohackademy.org/course/p-values-and-reproducibility-issues/) by JB Poline within Neurohackademy 2018 (1 hr 1 min)
* [The evil p value](https://neurohackademy.org/course/the-evil-p-value/) by JB Poline within Neurohackweek 2017 (1 hr 2 min)
* [Statistical Decision Theory](https://www.youtube.com/watch?v=OT1i2SKfGPM&index=2&t=0s&list=PLNt4AJV1JZbcCs84XEbN9XdXBXN9U-kyT) by Joshua Vogelstein within Brainhack-Vienna (starts at 8 min, ends at 48 min)
* A reminder on how random field theory is used to correct for multiple comparison [here](http://imaging.mrc-cbu.cam.ac.uk/imaging/PrinciplesRandomFields).
* [A primer on permutation testing (not only) for MVPA](https://www.pathlms.com/ohbm/courses/8246/sections/12542/video_presentations/116074) by [Carsten Allefeld](https://twitter.com/c_allefeld) at OHBM 2018 (36 min)
* [Cross-validation : what, which and how?](https://www.pathlms.com/ohbm/courses/8246/sections/12542/video_presentations/116075) by [Pradeep Reedy Raamana](https://twitter.com/raamana_) at OHBM 2018 (30 min)
* [Daniel Lakens](https://twitter.com/lakens) MOOC on coursera on [how to improve your statistical inferences](https://www.coursera.org/learn/statistical-inferences)
* [Statistical thinking for the 21st century](http://statsthinking21.org/) by Russ Poldrack: "I am trained as a psychologist and neuroscientist, not a statistician. However, my research on brain imaging for the last 20 years has required the use of sophisticated statistical and computational tools, and this has required me to teach myself many of the fundamental concepts of statistics. Thus, I think that I have a solid feel for what kinds of statistical methods are important in the scientific trenches."

A list of R based web based apps from [shiny apps](http://shinyapps.org/) and [R psychologist](http://rpsychologist.com/) to help better understand:
* [p-values](https://www.shinyapps.org/apps/vs-mpr/)
* [confidence intervals](http://rpsychologist.com/d3/CI/)
* [p curves](https://shinyapps.org/apps/p-checker/) and [why with a decent power and a large effect size, it is relatively unlikely to find a value between p<.01 and p<.05](http://rpsychologist.com/d3/pdist/)
* [null hypothesis significance testing](http://rpsychologist.com/d3/NHST/)
* [p hacking](https://www.shinyapps.org/apps/p-hacker/)
* [positive predictive values](http://shinyapps.org/showapp.php?app=https://tellmi.psy.lmu.de/felix/PPV&by=Michael%20Zehetleitner%20and%20Felix%20Sch%C3%B6nbrodt&title=When%20does%20a%20significant%20p-value%20indicate%20a%20true%20effect?&shorttitle=When%20does%20a%20significant%20p-value%20indicate%20a%20true%20effect?)


## Machine Learning and Deep Learning
* [Deep learning with Keras part 1](https://neurohackademy.org/course/deep-learning-with-keras/) by Ariel Rokem (2hr 3 min)
* [Deep learning with Keras part 2](https://neurohackademy.org/course/neural-networks-part-2/) by Ariel Rokem
* [Machine learning with scikit-learn 1](https://neurohackademy.org/course/machine-learning-with-scikit-learn/) by Jake Vanderplas within Neurohackweek
* [Machine learning with scikit-learn 2](https://neurohackademy.org/course/machine-learning-with-scikit-learn-2/) by Jake Vanderplas within Neurohackweek 2017 (1 hr 20 min)
* [Machine learning with scikit-learn 3](https://neurohackademy.org/course/machine-learning-with-scikit-learn-3/)  by Jake Vanderplas within Neurohackademy (2 hr 22 min)


### Specific to neuroimaging
* [Machine learning for neuroimaging](https://neurohackademy.org/course/machine-learning-for-neuroimaging/) by Chris Holdgraf within Neurohackweek 2017 (1 hr 2 min)
* [Machine learning in neuroimaging](https://neurohackademy.org/course/machine-learning-in-neuroimaging/) by Gael Varoquaux within Neurohackademy 2018 (2 hr 42 min)
* [Synthesizing fMRI using generative adversarial networks: cognitive neuroscience applications, promises and pitfalls](https://neurohackademy.org/course/gans-for-brain-imaging/) by Sanmi Koyejo within Neurohackademy 2018 (1 hr 7 min)

#### Hands-On Deep Learning Examples
* [Introduction to Keras](https://nbviewer.jupyter.org/github/brainhack101/IntroDL/blob/master/IntroToKeras.ipynb) by Anisha Keshavan within [OHBM DL Educational Course 2018](https://brainhack101.github.io/IntroDL/)
* [Introduction to Keras & Interpretability Methods](https://colab.research.google.com/drive/1EgdnWZeNqmzqEmnSR9PUnYXlTjeu1wAU) by Andrew Doyle within [MAIN 2018 Hands-on DL course](https://brainhack101.github.io/introML/dl-course-outline.html)
* [Brain Segmentation in Keras](https://colab.research.google.com/github/tfunck/minc_keras/blob/master/main2018.ipynb) by Thomas Funck within MAIN 2018 Hands-on DL course

### Softwares for machine learning (or multivariate) analysis in neuroimaging
They are divided in sub-sections depending on the language they use.

![Language](https://img.shields.io/badge/Language-Python-blue.svg)

#### pyMVPA
Intended to ease statistical learning analyses of large datasets.
* [website](http://www.pymvpa.org/)
* [manual](http://www.pymvpa.org/docoverview.html)
* [course/tutorial](http://www.pymvpa.org/tutorial.html)

#### nilearn
Nilearn is a Python module for fast and easy statistical learning on NeuroImaging data.
* [website](http://nilearn.github.io/)
* [manual](http://nilearn.github.io/user_guide.html)
* [course/tutorial](http://nilearn.github.io/introduction.html#python-for-neuroimaging-a-quick-start)

#### neuropredict
neuropredict is an easy to use Python tool for comprehensive evaluation of predictive power of popular ML techniques for features-to-target prediction (such as biomarkers to disease and similar variations)
* [code](http://github.com/raamana/neuropredict)
* [docs](http://raamana.github.io/neuropredict)

#### brainIAK
BrainIAK applies advanced machine learning methods and high-performance computing to analyzing neuroimaging data.

* [website](http://brainiak.org/)
* [sample tutorials](http://brainiak.org/events/ohbm2018/brainiak_sample_tutorials/)


![Language](https://img.shields.io/badge/Language-Matlab-orange.svg)

#### TDT
TDT is the The Decoding Toolbox.
* [website](https://sites.google.com/site/tdtdecodingtoolbox/)

#### ProNTo
PRoNTo is the Pattern Recognition for Neuroimaging Toolbox developed at UCL (UK).
* [website](http://www.mlnl.cs.ucl.ac.uk/pronto/prtsoftware.html)
* [manual](http://www.mlnl.cs.ucl.ac.uk/pronto/prtdocs.html)
* [course/tutorial](http://www.mlnl.cs.ucl.ac.uk/pronto/prtcourses.html)

#### RSA toolbox
* [website](https://github.com/rsagroup/rsatoolbox)
* [manual](https://github.com/rsagroup/rsatoolbox/blob/develop/Documentation/toolbox%20documentation.pdf)

#### PCM toolbox
The pattern components modelling toolbox of the [Diedrichsen lab](https://twitter.com/diedrichsenlab)
* [website](https://github.com/jdiedrichsen/pcm_toolbox)
* [manual](https://github.com/jdiedrichsen/pcm_toolbox/blob/master/documentation/pcm_toolbox_manual.pdf)

#### cvMANOVA
From [Carsten Allefeld](https://twitter.com/c_allefeld)
* [website](https://github.com/allefeld/cvmanova)


## Meta analysis
* [Overview_of_Meta-Analysis_Approaches](https://www.pathlms.com/ohbm/courses/8246/sections/12542/video_presentations/116072) by [Tom Nichols](https://twitter.com/ten_photos) at OHBM 2018 with [slides](https://figshare.com/articles/Overview_of_Meta-Analysis_Approaches/6723839) (18 min)
* [ALE and BrainMap](https://www.pathlms.com/ohbm/courses/8246/sections/12542/video_presentations/116066) by Simon B. Eickhoff at OHBM 2018 (22 min)

[NiMARE](https://github.com/neurostuff/NiMARE) is a Python library for coordinate- and image-based meta-analysis. [Chris Gorgolewski](https://twitter.com/ChrisFiloG) wrote a [tutorial](https://www.kaggle.com/chrisfilo/coordinate-and-image-metaanalysis-with-nimare) on how to use it.

For coordinate based meta-analysis:
* [brainmap](http://www.brainmap.org/) with [Sleuth](http://www.brainmap.org/software.html#Sleuth) and [GingerALE](http://www.brainmap.org/software.html#GingerALE)

For image based meta-analysis:
* [IBMA](https://github.com/NeuroimagingMetaAnalysis/ibma) is the Image-Based Meta-Analysis toolbox for SPM.


## Neuroimaging video series
Either on youtube or on some other platform

### Neurohackademy Lectures
Lecture series on neuroimaging and electrophysiology from the [Neurohackademy](https://neurohackademy.org/course_type/lectures/) summer school.

### Mike Cohen's Lectures on Time Series Analysis
Mike Cohen's lecturelets on time series data analysis [here](https://mikexcohen.com/lectures.html). 

### Mumford brainstats
Jeanette Mumford series of videos on neuroimaging analysis on [youtube](https://www.youtube.com/channel/UCZ7gF0zm35FwrFpDND6DWeA). The channel also has [Facebook group](https://www.facebook.com/groups/mumfordbrainstats/).


### Andrew Jahn
[Here](https://www.youtube.com/user/Shala5ha5ka) for the videos with 'tutorials' for FSL, SPM, Freesurfer and AFNI amongst other things.


### Center for Brains, Minds and Machines
[Here](https://www.youtube.com/channel/UCGoxKRfTs0jQP52cfHCyyRQ)


### Organization from human brain mapping (OHBM)
The videos of the lectures and workshops from the previous HBM conferences are available online [here](https://www.pathlms.com/ohbm/courses).


### fMRIf summer courses from the NIH
[Here](https://fmrif.nimh.nih.gov/public/fmri-course/)


### Conference on Cognitive Computational Neuroscience (CCN)
This [conference](https://ccneuro.org/) has the videos from its first edition [here](https://ccneuro.org/2017/index.html@p=602.html)


### INCF

[Here](https://www.youtube.com/channel/UC6FYCVath84rVzs99Ecfxyw)
