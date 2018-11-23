# A list of tutorials and other resources useful for open science and neuroimaging

* [Brainhack](#brainhack)
* [Open Science](#open-science)
* [GitHub](#github)
* [Python](#python)
  + [Introduction](#introduction)
  + [Specific topics](#specific-topics)
* [R](#r)
* [Containers](#containers)
* [Other tools for reproducible data-science](#other-tools-for-reproducible-data-science)
* [Open-data platforms](#open-data-platforms)
* [Neuroimaging](#neuroimaging)
  + [Courses and tutorials for the main software packages](#courses-and-tutorials-for-the-main-software-packages)
    - [SPM](#spm)
    - [Freesurfer](#freesurfer)
    - [FSL](#fsl)
    - [AFNI](#afni)
    - [Nipype](#nipype)
  + [Analysis](#analysis)
  + [Cloud computing](#cloud-computing)
  + [Reproducible neuroimaging tools](#reproducible-neuroimaging-tools)
    - [The Brain Imaging Data Structure (BIDS)](#the-brain-imaging-data-structure-bids)
  + [Other specific topics](#other-specific-topics)
* [Statistics](#statistics)
* [Machine Learning and Deep Learning](#machine-learning-and-deep-learning)
  + [Specific to neuroimaging](#specific-to-neuroimaging)
  + [Softwares for machine learning (or multivariate) analysis in neuroimaging](#softwares-for-machine-learning-or-multivariate-analysis-in-neuroimaging)
    - [Matlab based](#matlab-based)
      * [TDT](#tdt)
      * [ProNTo](#pronto)
      * [RSA toolbox](#rsa-toolbox)
      * [PCM toolbox](#pcm-toolbox)
      * [cvMANOVA](#cvmanova)
    - [Python based](#python-based)
      * [pyMVPA](#pymvpa)
      * [nilearn](#nilearn)
* [Meta analysis](#meta-analysis)
* [Neuroimaging video series](#neuroimaging-video-series)
  + [Mumford brainstats](#mumford-brainstats)
  + [Andrew Jahn](#andrew-jahn)
  + [Center for Brains, Minds and Machines](#center-for-brains-minds-and-machines)
  + [Organization from human brain mapping (OHBM)](#organization-from-human-brain-mapping-ohbm)
  + [fMRIf summer courses from the NIH](#fmrif-summer-courses-from-the-nih)
  + [Conference on Cognitive Computational Neuroscience (CCN)](#conference-on-cognitive-computational-neuroscience-ccn)


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


## Python
### Introduction
* [A whirlwind tour of python](https://jakevdp.github.io/WhirlwindTourOfPython/) by Jake Vanderplas
* [Introduction to Python](https://www.youtube.com/watch?v=3y55b_Md-N8&list=PLNt4AJV1JZbfq0vdD4vcITV7x3OqGxLKp&t=0s&index=3) within Brainhack Americas (45 min)
* [Introduction to Python](https://neurohackademy.org/course/introduction-to-python/) by Tal Yarkoni within Neurohackademy 2018 (1 hr 16 min)
* [Python programming](https://neurohackademy.org/course/python-programming/) by Valentina Staneva within Neurohackweek 2016
* [Python tips and tricks](https://neurohackademy.org/course/python-tips-and-tricks/) by Tal Yarkoni within Neurohackweek 2016 (58 min)
* [Scientific computing with Python](https://www.youtube.com/watch?v=RhNfnQlnCEo&index=18&t=0s&list=PLEE6ggCEJ0H0KOlMKx_PUVB_16VoCfGj9) by Luke Chang within MIND 2018 (24 min)


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

Some other platforms to get data from
* [OpenNeuro](https://openneuro.org/)
* [INDI](http://fcon_1000.projects.nitrc.org/) for rawdata
* [neurovault](https://neurovault.org/) for statistical maps
* [BALSA](https://balsa.wustl.edu/)
* [LORIS](https://github.com/aces/Loris/wiki/Open-LORIS)
* [XNAT](https://www.nitrc.org/ir/)
* And there are [many](https://brainhack101.github.io/neurolinks/) other [possibilities](https://en.wikipedia.org/wiki/List_of_neuroscience_databases)


## Neuroimaging
* [Tor Wager's](https://twitter.com/torwager) and Martin Lindquist's 2 parts MOOC on neuroimaging ([part 1](https://en.coursera.org/learn/functional-mri)
 and [part 2](https://en.coursera.org/learn/functional-mri-2))

### Courses and tutorials for the main software packages

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


### Softwares for machine learning (or multivariate) analysis in neuroimaging

#### Matlab based

##### TDT
TDT is the The Decoding Toolbox.
* [website](https://sites.google.com/site/tdtdecodingtoolbox/)

##### ProNTo
PRoNTo is the Pattern Recognition for Neuroimaging Toolbox developed at UCL (UK).
* [website](http://www.mlnl.cs.ucl.ac.uk/pronto/prtsoftware.html)
* [manual](http://www.mlnl.cs.ucl.ac.uk/pronto/prtdocs.html)
* [course/tutorial](http://www.mlnl.cs.ucl.ac.uk/pronto/prtcourses.html)

##### RSA toolbox
* [website](https://github.com/rsagroup/rsatoolbox)
* [manual](https://github.com/rsagroup/rsatoolbox/blob/develop/Documentation/toolbox%20documentation.pdf)

##### PCM toolbox
The pattern components modelling toolbox of the [Diedrichsen lab](https://twitter.com/diedrichsenlab)
* [website](https://github.com/jdiedrichsen/pcm_toolbox)
* [manual](https://github.com/jdiedrichsen/pcm_toolbox/blob/master/documentation/pcm_toolbox_manual.pdf)

##### cvMANOVA
From [Carsten Allefeld](https://twitter.com/c_allefeld)
* [website](https://github.com/allefeld/cvmanova)

#### Python based

##### pyMVPA
Intended to ease statistical learning analyses of large datasets.
* [website](http://www.pymvpa.org/)
* [manual](http://www.pymvpa.org/docoverview.html)
* [course/tutorial](http://www.pymvpa.org/tutorial.html)

##### nilearn
Nilearn is a Python module for fast and easy statistical learning on NeuroImaging data.
* [website](http://nilearn.github.io/)
* [manual](http://nilearn.github.io/user_guide.html)
* [course/tutorial](http://nilearn.github.io/introduction.html#python-for-neuroimaging-a-quick-start)


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
