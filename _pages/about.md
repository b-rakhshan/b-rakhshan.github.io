---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a first year PhD student in the theory group at the [Department of Computer Science and Operations Research (DIRO) Université de Montréal](https://diro.umontreal.ca/english/home/) and [MILA](https://mila.quebec/en/), where I am fortunate to be advised by [Guillaume Rabusseau](https://www-labs.iro.umontreal.ca/~grabus/). My research interests lie in the theoretical foundations of machine learning, particulary Randomized algorithms and Tensor Decompositions.
During Summer and Fall 2019, I interned at MILA. 

Prior to joining MILA, I was a PhD student at [Mathematics Department, Purdue University](https://www.math.purdue.edu/) where I was advised by [Petros Drineas](https://www.cs.purdue.edu/homes/pdrineas/), you can read my story [here](https://www.purdueexponent.org/campus/article_c29e92e2-cf28-583e-9b4f-8cc818a4d4fc.html?fbclid=IwAR2lSQvOWthN78ovRYYU2TWJgqFJDEENYLxl94ZPaD33-NsWXe_9mfgu_N8). 

Research
======
I am broadly interested in the theory behind Big Data and Machine Learning problems. My research is focused on developing fast and efficient randomized algorithms with tensor networks for large-scale problems. My goal is developing algorithms with provable guarantees, accurate and fast solutions to computationally expensive methods by leveraging dimensionality reduction and tensor decompositions' techniques

News
======
1. December 2020: Microsoft Diversity Award recipient. 
1. January 2020: Our [paper](http://proceedings.mlr.press/v108/rakhshan20a.html) got accepted in AISTATS 2020! [[code]](https://github.com/b-rakhshan/Tensorized_Random_Projection)

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
