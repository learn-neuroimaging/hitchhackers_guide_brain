# Organizing your files

Having a standard way to organize not only your data but also your code, the
results, the documentation... from the beginning of a project can go a long way
to save you a lot of time down the line (when communicating within or outside
your lab, or when you have to wrap things up when moving to a new project/job).

## Templates

Using the the
[Cookiecutter python package](https://github.com/cookiecutter/cookiecutter) is a
good way to get started to use a standardised folder structure. See for example
an example for
[data science](https://drivendata.github.io/cookiecutter-data-science/)

But there are other possibilities: see
[here](http://nikola.me/folder_structure.html) or
[here](https://eglerean.wordpress.com/2017/05/24/project-management-data-management/).

And some project template on OSF that can be forked and reused:

-   [Research Template to Start New Project (Confirmatory)](https://osf.io/qpdth/)

-   [Research Template to Start New Project (Exploratory)](https://osf.io/nc8ha/)

## The Brain Imaging Data Structure (BIDS)

If you are going to do some MRI, fMRI, MEEG... analysis you will quickly drown
in data if you are not a bit organized, we highly recommend you use the brain
imaging data structure standard ([BIDS](http://bids.neuroimaging.io/)) to
organize your data.

The current version of BIDS covers raw data and some aspects of derivative data
(e.g preprocessed data). In general BIDS also allows you to more easily share
your data and use plenty of analytical [tools](bids-apps.neuroimaging.io/apps/).

If you would like to use BIDS but you have no idea what a JSON file and / or the
length of the specification document scares you, head over to the
[BIDS starter kit](https://github.com/bids-standard/bids-starter-kit) to find
tutorials and scripts to help you rearrange your data.

-   [The Brain Imaging Data Structure (BIDS)](https://neurohackademy.org/course/the-brain-imaging-data-structure-bids/)
    presented by Chris Gorgolewski within Neurohackademy 2018
    -   duration: 56 min
    -   type: [video]
-   [BIDS website](http://bids.neuroimaging.io/)
-   [BIDS apps](https://bids-apps.neuroimaging.io/apps/)
-   [BIDS starter kit](https://github.com/bids-standard/bids-starter-kit)

## KEEPING your files organized

Not matter how clean your starting point is, it won't help if you don't have
good every day practices to make sure everything stays clean.

Some suggestions on how to do that from from
[Danielle Navarro](https://twitter.com/djnavarro).

<iframe src="https://slides.com/djnavarro/workflow/embed" width="576" height="420" scrolling="no" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

And some more from [Marijn van Vliet](https://twitter.com/wmvanvliet)

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">1. We joke about how terrible academic code often is. But as science becomes more dependant on code, it starts to scare me. Here are 7 tips for reducing the chances of having to retract your paper due to bugs in your analysis scripts. <a href="https://twitter.com/hashtag/OHBMx?src=hash&amp;ref_src=twsrc%5Etfw">#OHBMx</a> <a href="https://t.co/1noGYEkecQ">pic.twitter.com/1noGYEkecQ</a></p>&mdash; Marijn van Vliet (@wmvanvliet) <a href="https://twitter.com/wmvanvliet/status/1240907591791886337?ref_src=twsrc%5Etfw">March 20, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<!--
## YODA : keeping track of provenance
-->
