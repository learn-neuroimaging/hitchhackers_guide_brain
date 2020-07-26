# Analysis software for MRI

## Generic

??? example "SPM - Software package for the analysis of brain imaging data sequences"
    -   [code repository]( )
    -   [website](https://www.fil.ion.ucl.ac.uk/spm/)
    -   [documentation](https://www.fil.ion.ucl.ac.uk/spm/doc/manual.pdf)
    -   [contact](https://www.fil.ion.ucl.ac.uk/spm/support/)
    -   programming language: {matlab} {octave}
    -   tags: {fMRI} {MEG} {EEG} {SPECT} {PET} {nipype}
    -   [paper](https://doi.org/insert_paper_DOI_here)
    -   RRID:
    -   tutorial:
        -   [URL](http://www.fil.ion.ucl.ac.uk/spm/course/)
        -   programming language: {matlab}
        -   level:
        -   tags:
        -   date:
        -   duration:
        -   by:


<!-- * The first place to look is the [SPM wiki book](https://en.wikibooks.org/wiki/SPM) that could become a even better resource if users contributed even more to it.
* Then you can check the [add-ons for SPM](https://www.fil.ion.ucl.ac.uk/spm/ext/).
* https://www.youtube.com/playlist?list=PLxItDNjOWyDVMOerTs-ZRwtQQSE76ULm5
* Justin O'Brien has a [good tutorial video series](https://www.youtube.com/playlist?list=PLxItDNjOWyDVMOerTs-ZRwtQQSE76ULm5) on how to analyze data with SPM from beginning to the end.
* The spm.mat is the file where SPM stores all the information about your analysis. This [page](http://people.duke.edu/~njs28/spmdatastructure.htm) explains its organization.
* If you want to write scripts and use batches efficiently using SPM see what I wrote [here](./How2Script.md)
* [The clever machine](https://theclevermachine.wordpress.com/category/fmri/) blog has some very useful matlab codes for fMRI analysis
* [Tom Nichols](https://twitter.com/ten_photos) has tagged SPM related posts on his [website](http://blogs.warwick.ac.uk/nichols/) if you are looking for some good code snippets: see for example some of John Ashburner's [gems](http://blogs.warwick.ac.uk/nichols/tag/johns-gems/).
* Check out [Cyril Pernet](https://twitter.com/cyrilrpernet) website for SPM/matlab code: [here](http://www.sbirc.ed.ac.uk/cyril/teaching.html) or [there](http://www.sbirc.ed.ac.uk/cyril/Stats.html)
* Some good tutorials on the CBU if you want to understand [design efficiency](http://imaging.mrc-cbu.cam.ac.uk/imaging/DesignEfficiency), [smoothing](http://imaging.mrc-cbu.cam.ac.uk/imaging/PrinciplesSmoothing), [SPM GLM stats](http://imaging.mrc-cbu.cam.ac.uk/imaging/PrinciplesStatistics) or [how random field theory works to correct for multiple comparison](http://imaging.mrc-cbu.cam.ac.uk/imaging/PrinciplesRandomFields)
* Quite a few others on the web
 # [https://sites.google.com/site/mvlombardo/matlab-tutorials](https://sites.google.com/site/mvlombardo/matlab-tutorials)
 # [http://spm.martinpyka.de/](http://spm.martinpyka.de/)
 # [https://www.mccauslandcenter.sc.edu/crnl/tools/spm8-scripts](https://www.mccauslandcenter.sc.edu/crnl/tools/spm8-scripts)
* But also [too many repos on Github to list them all](https://github.com/search?q=matlab+fmri) but here are some you might come across: [Rik Henson's](https://github.com/MRC-CBU/riksneurotools), the [canlab](https://github.com/canlab) -->



??? example "AFNI - A software suite primarily developed for the analysis and display of anatomical and fMRI data."
    -   [website](https://afni.nimh.nih.gov/)
    -   [documentation](https://afni.nimh.nih.gov/pub/dist/doc/htmldoc/index.html)
    -   [contact](https://afni.nimh.nih.gov/afni/community/board/list.php?1)
    -   programming language: {C}, {python}, {R}, {shell}
    -   tags: {fMRI} {MRI} {nipype}
    -   [paper](https://doi.org/insert_paper_DOI_here)
    -   RRID: insert_RRID_here
    -   tutorial:
        -   [URL](https://afni.nimh.nih.gov/pub/dist/doc/htmldoc/tutorials/main_toc.html)
        - [AFNI bootcamp](https://afni.nimh.nih.gov/pub/dist/doc/htmldoc/educational/bootcamp_recordings.html)
        - [example data](https://afni.nimh.nih.gov/pub/dist/doc/htmldoc/background_install/unix_tutorial/misc/install.data.html)
        -   programming language: {shell}

??? example "FreeSurfer - An open source software suite for processing and analyzing (human) brain MRI images."
    -   [code repository](https://github.com/freesurfer/freesurfer)
    -   [website](https://surfer.nmr.mgh.harvard.edu/)
    -   [documentation](https://surfer.nmr.mgh.harvard.edu/fswiki)
    -   [contact](https://surfer.nmr.mgh.harvard.edu/fswiki/FreeSurferSupport)
    -   programming language: {C}, {C++}, {shell}
    -   tags: {fMRI} {MRI} {nipype}
    -   [paper]
    -   RRID:
    -   tutorial:
        -   [URL](https://surfer.nmr.mgh.harvard.edu/fswiki/Tutorials
        -   [videos](https://surfer.nmr.mgh.harvard.edu/fswiki/CourseDescription)
        -   programming language: {shell}

??? example "FSL - A comprehensive library of analysis tools for FMRI, MRI and DTI brain imaging data."
    -   [code repository](insert GitHub or GitLab URL )
    -   [website](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki)
    -   [documentation](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/Support)
    -   [contact](https://www.jiscmail.ac.uk/cgi-bin/webadmin?A0=fsl)
    -   programming language:
    -   tags: {fMRI} {MRI} {nipype}
    -   [paper]
    -   RRID:
    -   tutorial:
        -   [URL](https://fsl.fmrib.ox.ac.uk/fslcourse/)

## Diffusion MRI

## MRTrix3
-   [MRtrix3](http://www.mrtrix.org/) -   Advanced tools for the analysis of diffusion MRI data.
-   repository URL: [GitHub](https://github.com/MRtrix3)
-   website URL: [http://www.mrtrix.org/](http://www.mrtrix.org/)
-   tutorial URL: [beginner DWI tutorial](https://mrtrix.readthedocs.io/en/latest/getting_started/beginner_dwi_tutorial.html), [basic and advanced tractography with MRtrix tutorial](https://osf.io/fkyht/), [tutorial video1](https://osf.io/fkyht/), [tutorial video2](https://www.youtube.com/watch?v=lQWucXuAXR8)
-   documentation: [user documentation](https://mrtrix.readthedocs.io/en/latest/), [developer documentation](http://www.mrtrix.org/developer-documentation/)
-   programming language: {C++}, {python}
-   paper DOI: doi: 10.1016/j.neuroimage.2019.116137
-   RRID:
-   contact: [discussion forum](https://community.mrtrix.org/)

??? example "insert software name - insert short description"
    -   [code repository](insert GitHub or GitLab URL )
    -   [website](insert URL)
    -   [documentation](insert documentation or wiki URL)
    -   [contact](insert URL to mailing list, slack, forum, mattermost)
    -   programming language: {python}, {matlab/octave}, {C}, ...
    -   tags: {fMRI} {MEG} {EEG} {MRI} {nipype}
    -   [paper](https://doi.org/insert_paper_DOI_here)
    -   RRID: insert_RRID_here
    -   tutorial:
        -   [URL]( insert URL )
        -   programming language:
        -   level:
        -   tags:
        -   date:
        -   duration:
        -   by:





## DIPY

-   [DIPY](https://dipy.org/) -   DIPY is a free and open source software project for computational neuroanatomy, focusing mainly on dMRI analysis.
-   [GitHub](https://github.com/dipy/dipy)
-   [Website](https://dipy.org/)
-   [Tutorial](https://dipy.org/tutorials/)
-   [Documentation](https://dipy.org/documentation/1.1.1./documentation/)
-   programming language: {python}
-   paper DOI: https://doi.org/10.3389/fninf.2014.00008
-   RRID:
-   [mailing list](https://mail.python.org/mailman/listinfo/neuroimaging)

??? example "insert software name - insert short description"
    -   [code repository](insert GitHub or GitLab URL )
    -   [website](insert URL)
    -   [documentation](insert documentation or wiki URL)
    -   [contact](insert URL to mailing list, slack, forum, mattermost)
    -   programming language: {python}, {matlab/octave}, {C}, ...
    -   tags: {fMRI} {MEG} {EEG} {MRI} {nipype}
    -   [paper](https://doi.org/insert_paper_DOI_here)
    -   RRID: insert_RRID_here
    -   tutorial:
        -   [URL]( insert URL )
        -   programming language:
        -   level:
        -   tags:
        -   date:
        -   duration:
        -   by:






## Pipelines

-   [Nipype](https://nipype.readthedocs.io/en/latest/) -   An open-source, community-developed initiative under the umbrella of NiPy, is a Python project that provides a uniform interface to existing neuroimaging software and facilitates interaction between these packages within a single workflow.
-   repository URL: [GitHub](https://github.com/nipy/nipype)
-   website URL: [https://nipype.readthedocs.io/en/latest/](https://nipype.readthedocs.io/en/latest/)
-   tutorial URL: [tutorial1](https://nipype.readthedocs.io/en/0.11.0/users/pipeline_tutorial.html), [tutorial2](https://miykael.github.io/nipype_tutorial/), [examples](https://nipype.readthedocs.io/en/latest/examples.html)
-   documentation:
-   programming language: {python}
-   paper DOI:
-   RRID:
-   contact: [chat](https://gitter.im/nipy/nipype)

??? example "insert software name - insert short description"
    -   [code repository](insert GitHub or GitLab URL )
    -   [website](insert URL)
    -   [documentation](insert documentation or wiki URL)
    -   [contact](insert URL to mailing list, slack, forum, mattermost)
    -   programming language: {python}, {matlab/octave}, {C}, ...
    -   tags: {fMRI} {MEG} {EEG} {MRI} {nipype}
    -   [paper](https://doi.org/insert_paper_DOI_here)
    -   RRID: insert_RRID_here
    -   tutorial:
        -   [URL]( insert URL )
        -   programming language:
        -   level:
        -   tags:
        -   date:
        -   duration:
        -   by:



-   [fMRIPrep](https://fmriprep.readthedocs.io/en/stable/) -   A Robust Preprocessing Pipeline for fMRI Data
-   [GitHub](https://github.com/poldracklab/fmriprep)
-   [website](https://fmriprep.readthedocs.io/en/stable/)
-   [tutorial](http://reproducibility.stanford.edu/fmriprep-tutorial-running-the-docker-image/)
-   documentation:
-   programming language: {python}
-   paper DOI: [https://doi.org/10.1038/s41592-018-0235-4](https://doi.org/10.1038/s41592-018-0235-4)
-   RRID:SCR_001362
-   contact:

??? example "insert software name - insert short description"
    -   [code repository](insert GitHub or GitLab URL )
    -   [website](insert URL)
    -   [documentation](insert documentation or wiki URL)
    -   [contact](insert URL to mailing list, slack, forum, mattermost)
    -   programming language: {python}, {matlab/octave}, {C}, ...
    -   tags: {fMRI} {MEG} {EEG} {MRI} {nipype}
    -   [paper](https://doi.org/insert_paper_DOI_here)
    -   RRID: insert_RRID_here
    -   tutorial:
        -   [URL]( insert URL )
        -   programming language:
        -   level:
        -   tags:
        -   date:
        -   duration:
        -   by:


## Misc

-   [ANTs](http://stnava.github.io/ANTs/) -   ANTs computes high-dimensional mappings to capture the statistics of brain structure and function.
-   repository URL: [GitHub](https://github.com/ANTsX/ANTs)
-   website URL: [http://stnava.github.io/ANTs/](http://stnava.github.io/ANTs/)
-   tutorial URL: [https://github.com/stnava/ANTsTutorial](https://github.com/stnava/ANTsTutorial)
-   documentation: [https://github.com/ANTsX/ANTs](https://github.com/ANTsX/ANTs), [https://github.com/ANTsX/ANTs/wiki](https://github.com/ANTsX/ANTs/wiki)
-   programming language:
-   paper DOI:
-   RRID:
-   contact: [discussion forum](https://sourceforge.net/p/advants/discussion/)

??? example "insert software name - insert short description"
    -   [code repository](insert GitHub or GitLab URL )
    -   [website](insert URL)
    -   [documentation](insert documentation or wiki URL)
    -   [contact](insert URL to mailing list, slack, forum, mattermost)
    -   programming language: {python}, {matlab/octave}, {C}, ...
    -   tags: {fMRI} {MEG} {EEG} {MRI} {nipype}
    -   [paper](https://doi.org/insert_paper_DOI_here)
    -   RRID: insert_RRID_here
    -   tutorial:
        -   [URL]( insert URL )
        -   programming language:
        -   level:
        -   tags:
        -   date:
        -   duration:
        -   by:





-   [BrainSuite](http://brainsuite.org/) -    A collection of open source software tools that enable largely automated processing of MRI of the human brain.
-   repository URL:
-   website URL: [http://brainsuite.org/](http://brainsuite.org/)
-   tutorial URL: [http://brainsuite.org/tutorials/](http://brainsuite.org/tutorials/)
-   documentation:
-   programming language:
-   paper DOI:
-   RRID:
-   contact: [discussion forum](http://forums.brainsuite.org/)

??? example "insert software name - insert short description"
    -   [code repository](insert GitHub or GitLab URL )
    -   [website](insert URL)
    -   [documentation](insert documentation or wiki URL)
    -   [contact](insert URL to mailing list, slack, forum, mattermost)
    -   programming language: {python}, {matlab/octave}, {C}, ...
    -   tags: {fMRI} {MEG} {EEG} {MRI} {nipype}
    -   [paper](https://doi.org/insert_paper_DOI_here)
    -   RRID: insert_RRID_here
    -   tutorial:
        -   [URL]( insert URL )
        -   programming language:
        -   level:
        -   tags:
        -   date:
        -   duration:
        -   by:
