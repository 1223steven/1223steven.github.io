---
permalink: /
title: "Mathematics modeling and computer simulation"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Traditionally, the formal modeling of systems has been via a mathematical model, which attempts to find analytical solutions to problems which enables the prediction of the behaviour of the system from a set of parameters and initial conditions.
A computer simulation or a computer model is a computer program that attempts to simulate an abstract model of a particular system. Computer simulations have become a useful part of mathematical modelling of many natural systems in physics, chemistry and biology, human systems in economics, psychology, and social science and in the process of engineering new technology, to gain insight into the operation of those systems.
Computer simulations build on, and are a useful adjunct to purely mathematical models in science, technology and entertainment. The reliability and the trust people put in computer simulations depends on the validity of the simulation model. (from Wikipedia)

My research initerests
======
* Magnetics simulation, modeling and algorithmic analysis
* Numerical analysis on PDEs
* Molecular dynamics
* electronic structure calculation
* Algorithms and analysis on machine learning for PDEs
* Quantum machine learning 
* Asympototics analysis
* Multiscale modeling

Biosketch
======
I am a Ph.D. student of Soochow university [School of Mathematics and Sciences](http://math.suda.edu.cn/), majoring computing mathematics and materials advised by Prof. [Jingrun Chen](http://web.suda.edu.cn/jingrunchen/).
I will be a visiting scholar at Penn State under the supervision of Prof. [Xiantao Li](http://personal.psu.edu/xxl12/), expected 2019-2020, working on the topics of molecular dynimics simulations. 
I have a research grant for the Postgraduate Research and Practice Innovation Program of Jiangsu Province via number KYCX19_1947 working on the algorithms and analysis of magnetic materials.
Also, I have always focused the field of machine learning and prefered the applications to high dimensional PDEs, quantum physics and chemstry.  

Research Papers:
======
1. Jingrun Chen, Cheng Wang, Changjian Xie, 2019, Convergence analysis of a second-order semi-implicit projection method for Landau-Lifshitz equation, ArXiv 1902.09740, https://arxiv.org/pdf/1902.09740.pdf.
1. Changjian Xie, Garcia-Cervera, Cheng Wang, Zhennan Zhou, and Jingrun Chen, 2019, Second-order semi-implicit projection methods for micromagnetics simulations, ArXiv 1907.02358, https://arxiv.org/pdf/1907.02358.pdf.
1. Panchi Li, Changjian Xie, Rui Du, Jingrun Chen, Xiaoping Wang, 2019, Two improved Gauss-Seidel projection methods for Landau-Lifshitz-Gilbert equation, ArXiv 1907.11853, https://arxiv.org/pdf/1907.11853.pdf.

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
