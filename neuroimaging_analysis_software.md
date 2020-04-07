# neuroimaging analysis software


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
* course/tutorial: Video recordings from the [AFNI bootcamp](https://afni.nimh.nih.gov/pub/dist/doc/htmldoc/educational/bootcamp_recordings.html), with slides, and [example data](https://afni.nimh.nih.gov/pub/dist/doc/htmldoc/background_install/unix_tutorial/misc/install.data.html).

#### ANTs
* [website](http://stnava.github.io/ANTs/)
* [manual/wiki](https://github.com/ANTsX/ANTs/wiki)

#### Nipype
Nipype is best viewed as a way to create and run software-agnostic preprocessing/analysis-pipeline. It becomes very powerful when you need to use different softwares in your analysis.
* [website](https://nipype.readthedocs.io/en/latest/)
* [course/tutorial](https://miykael.github.io/nipype_tutorial/)

#### Dipy
Diffusion neuroimaging in Python
* [website](https://github.com/ohbm/hackathon2019)

#### MRtrix3
Advanced tools for the analysis of diffusion MRI data
* [website](http://www.mrtrix.org/)
* [community forum](http://community.mrtrix.org/)
* [user documentation](https://mrtrix.readthedocs.io/en/latest/)
* [developer documentation](http://www.mrtrix.org/developer-documentation/)
* [manuscript preprint](https://www.biorxiv.org/content/10.1101/551739v1). Includes example code for both C++11 and Python libraries.
* [BATMAN tutorial](https://osf.io/fkyht/). MRtrix3 tutorial available on OSF with an awesome title: B.A.T.M.A.N., the Basic and Advanced Tractography with MRtrix for All Neurophiles

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
