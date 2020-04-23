# Data repositories

This section contains links to "open" data resources, that can be accessed for research purposes. For some of them, a formal request to the organization or to the data curation team may be required.

This [Wikipedia](https://en.wikipedia.org/wiki/List_of_neuroscience_databases) also has a nice list with some more suggestions.

<!-- [ElectrophysiologyData](https://github.com/voytekresearch/OpenData) -   Open datasets in electrophysiology -->

## Generic

### Open science framework

OSF is a platform to support research and enable collaboration. Used to discover projects, data, materials, and collaborators helpful to your own research.

??? example "OSF - The interface can be slow and clunky but it can definitely be used to host and share data... and many other things."
    -   [database repository](https://ebrains.eu/)
    -   documentation
    -   contact
    -   data type: pretty much anything goes
    -   tags:
    -   datalad compatible:
    -   paper
    -   RRID: [SCR_017419](https://scicrunch.org/resources/Tools/record/nlx_144509-1/SCR_017419/resolver?q=open%20science%20framework&l=open%20science%20framework)

### eBrains

??? example "eBrains - For human & non-human data sets matching specific criteria"
    -   [database repository](https://ebrains.eu/)
    -   documentation
    -   contact
    -   data type: {human} {non-human} {fMRI} {MRI} {EEG} {DWI} {histology}
    -   tags:
    -   datalad compatible:
    -   paper
    -   RRID:

## NeuroImaging

You first go to should be the [data section](https://www.nitrc.org/search/?type_of_search=group&q=category%3A%27Data%27) of the [Neuroimaging Tools
an Resources Collaboratory](https://www.nitrc.org/).

### MRI/fMRI

#### OpenNeuro

Open platform for analyzing and sharing neuroimaging data from human brain imaging research studies. Brain Imaging Data Structure (BIDS) compliant database. Formerly known as OpenfMRI. Platform for sharing MRI, MEG, EEG, iEEG, and ECoG data.

??? example "OpenNeuro - A go to for MRI, MEG, EEG, iEEG, and ECoG data"
    -   [database repository](https://openneuro.org/)
    -   documentation
    -   contact
    -   data type: {MRI} {EEG} {iEEG} {ECoG} {human}
    -   datalad compatible: yes  
    -   tags:
    -   paper
    -   RRID: [SCR_005031](https://scicrunch.org/resources/Any/record/nlx_144509-1/SCR_005031/resolver?q=openneuro&l=openneuro)

#### GIN

The G-Node Data Infrastructure Services is provides a platform for comprehensive and reproducible management and sharing of neuroscience data. Building on well established versioning technology, GIN offers the power of a web based repository management service combined with a distributed file storage.

Comments:

-   Very similar to github but for data.

-   As it is based in Europe, this can an interesting option for GDPR compliance.

??? example "GIN - The equivalent of github but for data. Based in Europe."
    -   [database repository](https://gin.g-node.org/)
    -   documentation
    -   contact
    -   data type: {MRI} {EEG} {iEEG} {ECoG} {human} {non-human}
    -   datalad compatible: yes
    -   tags:
    -   paper: [10.12751/incf.ni2017.0040](10.12751/incf.ni2017.0040)
    -   RRID: [SCR_015864](https://scicrunch.org/resources/Tools/record/nlx_144509-1/SCR_015864/resolver?q=GIN&l=GIN)

#### Neurovault

A data repository where researchers can publicly store and share unthresholded statistical brain activation maps produced by MRI and PET studies.

??? example "Neurovault - The place for your group results."
    -   [database repository](https://neurovault.org/)
    -   documentation
    -   contact
    -   data type: {MRI} {PET} {human} {non-human}
    -   datalad compatible: yes
    -   tags:
    -   paper:
    -   RRID: [SCR_003806](https://scicrunch.org/resources/Tools/record/nlx_144509-1/SCR_003806/resolver?q=Neurovault&l=Neurovault)

#### INDI

??? example "INDI - International Neuroimaging Data-Sharing Initiative for rawdata"
    -   [database repository](http://fcon_1000.projects.nitrc.org/)
    -   documentation
    -   contact
    -   data type: {MRI} {PET} {human} {non-human}
    -   datalad compatible: yes
    -   tags:
    -   paper:
    -   RRID:

#### BALSA

??? example "BALSA - A database for neuroimaging and neuroanatomical datasets for human and primate species."
    -   [database repository](https://balsa.wustl.edu/)
    -   documentation
    -   contact
    -   data type:
    -   datalad compatible:
    -   tags:
    -   paper:
    -   RRID:

#### NITRC-IR

XNAT-based image registry that supports both NIfTI and DICOM images to promote re-use and integration of NIH funded data. It allows users to search for and freely download publicly available data sets relating to normal subjects and those with diagnoses such as: schizophrenia, ADHD, autism, and Parkinson's disease.

??? example "NITRC-IR - Data repository for neuroimaging data in DlCOM and NIFTI formats."
    -   [database repository](https://www.nitrc.org/ir/)
    -   documentation
    -   contact
    -   data type: {MRI} {human} {healthy} {schizophrenia} {ADHD} {autism} {Parkinson}
    -   datalad compatible:
    -   tags:
    -   paper:
    -   RRID: [SCR_004162](https://scicrunch.org/resources/Tools/record/nlx_144509-1/SCR_004162/resolver?q=NITRC-IR&l=NITRC-IR)

#### NITRC-R

??? example "NITRC-R - "
    -   [database repository](https://www.nitrc.org/search/?type_of_search=group&q=category%3A%27Data%27)
    -   documentation
    -   contact
    -   data type:
    -   datalad compatible:
    -   tags:
    -   paper:
    -   RRID:

#### ABIDE

Resting state functional magnetic resonance imaging (R-fMRI) datasets from 539 individuals with autism spectrum disorder (ASD) and 573 typical controls. This initiative involved 16 international sites, sharing 20 samples yielding 1112 datasets composed of both MRI data and an extensive array of phenotypic information common across nearly all sites. This effort is expected to facilitate discovery science and comparisons across samples. All datasets are anonymous, with no protected health information included.

??? example "ABIDE - the Autism Brain Imaging Data Exchange"
    -   [database repository](http://fcon_1000.projects.nitrc.org/indi/abide/)
    -   documentation
    -   contact
    -   data type: {human} {healthy} {autism} {fMRI} {MRI} {resting state}
    -   tags:
    -   paper
    -   RRID: [SCR_003612](https://scicrunch.org/resources/Any/record/nlx_144509-1/SCR_003612/resolver?q=abide&l=abide)

#### ADNI
Database of the results of the Alzheimer's Disease Neuroimaging Initiative study. ADNI is an initiative to develop biomarker-based methods to detect and track the progression of Alzheimer's disease (AD) that provides access to qualified scientists to their database of imaging, clinical, genomic, and biomarker data.

??? example "ADNI - Alzheimer's Disease Neuroimaging Initiative"
     -   [database repository](http://adni.loni.usc.edu/data-samples/access-data/)
     -   documentation
     -   contact
     -   data type: {human} {alzheimer} {MRI} {fMRI} {PET}   
     -   tags:
     -   paper
     -   RRID: [SCR_003007](https://scicrunch.org/resources/Any/record/nlx_144509-1/SCR_003007/resolver?q=adni&l=adni)

#### fNIRS

## Electrophysiology

### Surface (EEG/MEG)

### Intracranial (ECoG / iEEG / LFP / Single cell)




<!-- #### LORIS

-   [LORIS](https://github.com/aces/Loris/wiki/Open-LORIS) -   Open datasets available through LORIS projects  

??? example "LORIS - "
    -   [database repository]()
    -   documentation
    -   contact
    -   data type:
    -   datalad compatible:
    -   tags:
    -   paper:
    -   RRID: []() -->
