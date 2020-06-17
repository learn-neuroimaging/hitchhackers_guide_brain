# Extracting data from the Allen atlas

The Allen atlas is an amazing resource of regional gene expression in the human brain. It contains a database of expression levels of 20,737 genes represented by 58,692 probes across the complete cortical mantle and is constructed postmortem from the brains of 6 human donors with no history of psychiatric or neuropathological disorders. The donor brains also underwent MRI postmortem and the probe locations mapped into each donor's MRI data in MNI space, providing a great opportunity to correlate regional gene expression with imaging findings!

Data is freely available to download from AIBS [AIBS](http://human.brain-map.org/static/download). 
Extracting appropriate gene expression data from the Allen Atlas has many caveats, detailed in the excellent paper [here](https://doi.org/10.1016/j.neuroimage.2019.01.011) but tools have now been developed to make gene extraction easier. 

The following list includes software/packages and useful resources that can be used to extract gene expression data in imaging space. 

## Abagen

-   Open-source Python software for extracting gene expression data from the ALlen atlas.
-   repository URL: [Github](https://github.com/rmarkello/abagen/)
-   website URL: [http://martinos.org/mne/stable/index.html](http://martinos.org/mne/stable/index.html)
-   tutorial URL: 
-   documentation: [https://abagen.readthedocs.io/en/stable/index.html](https://abagen.readthedocs.io/en/stable/index.html)
-   programming language: {python}
-   paper DOI: [https://doi.org/10.5281/zenodo.3726257.](https://doi.org/10.5281/zenodo.3726257.)

## Matlab repository from Aurina Arnatkeviciute

-   Repository from the Aurina's paper describing best practice when extracting data from the Allen atlas.
-   repository URL: [Github](https://github.com/BMHLab/AHBAprocessing)
-   programming language: {matlab}
-   paper DOI: [https://doi.org/10.1016/j.neuroimage.2019.01.011](https://doi.org/10.1016/j.neuroimage.2019.01.011)
-   contact: aurina.arnatkeviciute@monash.edu