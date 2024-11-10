---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Since November 2023 I am a postdoctoral researcher at TU Wien with [Maria Christakis](https://mariachris.github.io/). I received my PhD from TU Munich, where I was co-advised by [Eva Darulova](https://malyzajko.github.io/) and [Helmut Seidl](https://www.cs.cit.tum.de/pl/personen/helmut-seidl/). Before that I was a graduate student in [Max-Planck Institute for Software Systems (MPI-SWS)](https://mpi-sws.org/) and [Saarland University](https://www.graduateschool-computerscience.de/).

My research interests span over various topics in formal methods and software engineering. I am passionate about static analysis, in my book, *AI stands for abstract interpretation*. During my PhD, I focused on analysing and optimising numerical programs, now exploring new domains. I am curious about program synthesis, optimization, repair and testing and how they can help make software reliable and understandable.

# Service
**Recent / upcoming:** CAV'25, PLDI SRC'24, SAS'24, ASE Tool Demo'24, ISSTA'24 (publicity chair)

Older: SAS'20 (subreview), FAOC Journal'21, AEC @ POPL'21, CAV'21, CGO'22, PLDI'23

# Teaching
## TU Wien
* Seminar in Software Engineering: SS24, WS24/25

## TU Munich
* Program Optimization: WS18/19, WS19/20, WS20/21, WS21/22, WS22/23
* Virtual Machines: SS19, SS20, SS21, SS23
* The Tyranny of Types: Curse or Blessing? (Seminar) SS22
* Program Synthesis Seminar: SS18, SS19, SS20
* Introduction to Informatics 2 (WS17/18)

# Publications
* [**Interrogation Testing of Program Analyzers for Soundness and Precision Issues**](https://aisychev.github.io/papers/ase24-sherlock.pdf) D.Kaindlstorfer, A.Isychev, V.Wüstholz, M.Christakis, ASE'24
* [**Constraint-Based Test Oracles for Program Analyzers**](https://aisychev.github.io/papers/ase24-minotaur.pdf) M.Fleischmann, D.Kaindlstorfer, A.Isychev, V.Wüstholz, M.Christakis, ASE'24
* [**Scaling up Roundoff Analysis of Functional Data Structure Programs**](https://dl.acm.org/doi/10.1007/978-3-031-44245-2_17) A.Isychev, E.Darulova, SAS'23
* [**Regime Inference for Sound Floating-Point Optimizations**](https://dl.acm.org/doi/10.1145/3477012) R.Rabe, A.Izycheva, E.Darulova, EMSOFT'21
* [**Counterexample- and Simulation-Guided Floating-Point Loop Invariant Synthesis**](https://dl.acm.org/doi/10.1007/978-3-030-65474-0_8) A.Izycheva, E.Darulova, H.Seidl, SAS'20; Recording of the talk
* [**Synthesizing Efficient Low-Precision Kernels**](https://link.springer.com/chapter/10.1007/978-3-030-31784-3_17) A.Izycheva, E.Darulova, H.Seidl, ATVA'19
* [**Daisy - Framework for Analysis and Optimization of Numerical Programs (Tool Paper)**](https://link.springer.com/chapter/10.1007/978-3-319-89960-2_15) E.Darulova, A.Izycheva, F.Nasir, F.Ritter, H.Becker, R.Bastian, TACAS'18
* [**On Sound Relative Error Bounds for Floating-Point Arithmetic**](https://dl.acm.org/citation.cfm?id=3168462) A. Izycheva, E. Darulova, FMCAD'17 (extended version on [arXiv](https://arxiv.org/pdf/1707.02121))


# Theses
* Doctoral Thesis @ TU Munich [**Improving Analysis and Optimization of Finite-Precision Programs**](https://aisychev.github.io/papers/Anastasia-Isychev-dissertation.pdf)
* Master Thesis @ MPI-SWS and UdS [**Estimation of Relative Error Bounds for Floating-Point Arithmetic Expressions**](https://aisychev.github.io/papers/Anastasia-Isychev-mscthesis.pdf)

<!-- 
A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
