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

<!-- TODO -->

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
    -   RRID: 
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

??? example "MRtrix3 - Advanced tools for the analysis of diffusion MRI data."
    -   [GitHub]([insert GitHub or GitLab URL ](https://github.com/MRtrix3))
    -   [website]([insert URL](http://www.mrtrix.org/))
    -   [documentation](https://mrtrix.readthedocs.io/en/latest/)
    -   [developer documentation](http://www.mrtrix.org/developer-documentation/)
    -   [discussion forum](https://community.mrtrix.org/)
    -   programming language:  {C++}, {python}
    -   tags: {dMRI}
    -   [paper](doi: 10.1016/j.neuroimage.2019.116137)
    -   RRID: insert_RRID_here
    -   tutorial:
        -   [beginner DWI tutorial](https://mrtrix.readthedocs.io/en/latest/getting_started/beginner_dwi_tutorial.html)
        -   programming language:
        -   level: beginner
        -   tags:
        -   date:
        -   duration:
        -   by:
    -   tutorial:
        -   [basic and advanced tractography with MRtrix tutorial](https://osf.io/fkyht/)
        -   programming language:
        -   level:
        -   tags:
        -   date:
        -   duration:
        -   by:
    -   [tutorial video1](https://osf.io/fkyht/), 
    -   [tutorial video2](https://www.youtube.com/watch?v=lQWucXuAXR8)

??? example "DIPY - a free and open source software project for computational neuroanatomy, focusing mainly on dMRI analysis"
    -   [gitHub](https://github.com/dipy/dipy)
    -   [website](https://dipy.org/)
    -   [documentation](https://dipy.org/documentation/1.1.1./documentation/)
    -   [contact](https://mail.python.org/mailman/listinfo/neuroimaging)
    -   programming language: {python}
    -   tags: {dMRI}
    -   paper: https://doi.org/10.3389/fninf.2014.00008
    -   RRID:
    -   [tutorial](https://dipy.org/tutorials/)

## Pipelines

??? example "Nipype - provides a uniform interface to existing neuroimaging software and facilitates interaction between these packages within a single workflow."
    -   [website](https://nipype.readthedocs.io/en/latest/) -   
    -   [GitHub](https://github.com/nipy/nipype)
    -   [documentation](https://nipype.readthedocs.io/en/latest/)
    -   [contact](https://gitter.im/nipy/nipype)
    -   programming language: {python}
    -   tags: {fMRI} {MRI}
    -   paper DOI:
    -   RRID:
    -   tutorial:
        -   [tutorial 1](https://nipype.readthedocs.io/en/0.11.0/users/pipeline_tutorial.html), 
        -   [tutorial 2](https://miykael.github.io/nipype_tutorial/), 
        -   [examples](https://nipype.readthedocs.io/en/latest/examples.html)
        -   programming language:
        -   level:
        -   tags:
        -   date:
        -   duration:
        -   by:

??? example "fMRIPrep - A Robust Preprocessing Pipeline for fMRI Data"
    -   [GitHub](https://github.com/poldracklab/fmriprep)
    -   [website](https://fmriprep.readthedocs.io/en/stable/)
    -   [documentation] :
    -   [contact] :
    -   [tutorial](http://reproducibility.stanford.edu/fmriprep-tutorial-running-the-docker-image/)
    -   programming language: {python}
    -   tags: {fMRI} {nipype}
    -   paper DOI: [https://doi.org/10.1038/s41592-018-0235-4](https://doi.org/10.1038/s41592-018-0235-4)
    -   RRID: SCR_001362
    -   tutorial:
        -   [URL]( insert URL )
        -   programming language:
        -   level:
        -   tags:
        -   date:
        -   duration:
        -   by:

## Misc

??? example "ANTs - To compute high-dimensional mappings to capture the statistics of brain structure and function"  
    -   [GitHub](https://github.com/ANTsX/ANTs)
    -   [website](http://stnava.github.io/ANTs/)
    -   [documentation](https://github.com/ANTsX/ANTs/wiki)
    -   [contact](https://sourceforge.net/p/advants/discussion/)
    -   programming language:
    -   tags: {fMRI} {MRI} {nipype}
    -   paper DOI:
    -   RRID:
    -   tutorial: 
        -   [URL](https://github.com/stnava/ANTsTutorial)
        -   programming language:
        -   level:
        -   tags:
        -   date:
        -   duration:
        -   by:

??? example "BrainSuite - A collection of open source software tools that enable largely automated processing of MRI of the human brain."
        -   [website](http://brainsuite.org/)
        -   documentation:
        -   [contact](http://forums.brainsuite.org/)
        -   programming language:
        -   tags: 
        -   paper DOI:
        -   RRID:
        -   tutorial
            -    [URL](http://brainsuite.org/tutorials/)
        -   programming language:
        -   level:
        -   tags:
        -   date:
        -   duration:
        -   by:
