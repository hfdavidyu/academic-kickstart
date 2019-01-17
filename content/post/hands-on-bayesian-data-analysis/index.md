+++
title = "Hands on Bayesian Data Analysis"
date = 2018-03-06T18:31:08+01:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["David Yu"]

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []
categories = []

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects = ["internal-project"]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

This is an introductory workshop on <em>Bayesian Data Analysis</em> aiming at undergrad students who in the near future may work as a researcher in the academia or industry. I will give an 1-hour overview on the difference between Bayesian and frequentist analysis methods, followed by a 2-hour hands-on session on analysing some simulated data. We will learn how to properly fit a line to data points. We will get to know that we have probably mis-understood some of the statistical concepts. No more reduced-Chi-squared, no more F-test, because a single <em>Bayes Theorem</em> rules them all.

Participants should bring their own laptop and get the following installed before coming to the hands-on session. 

<a href="https://www.python.org">Python</a> (better version 2.7.xx)

<a href="https://docs.pymc.io/index.html">PyMC3</a> (the main Bayesian tool we are using)

<a href="http://jupyter.org">Jupyter Notebook</a> (iPython interactive interface used together with your web browser)

<a href="https://pypi.python.org/pypi/pip">Pip</a> (tool to download the following Python packages)
  
- numpy (basic computation)
- scipy (scientific computation)
- matplotlib (for plotting)
- seaborn (for nice contour/corner plots)

You can also choose to install Anaconda for Jupyter following the instruction in the previous <a href="http://ryan-leung.github.io/PHYS4650_Python_Tutorial">Python Training Workshop 2018</a>.

Detailed instruction can be found therein in the links. You are also welcome to contact me (email written below) or Stephen for help.

<a href="https://www.dropbox.com/s/hg3cy6bpdr7b6wm/HKU_Bayesian_Hands-on_2018.ipynb?dl=0">Jupyter Notebook used in the Workshop</a>

<a href="https://www.dropbox.com/s/y4sl4nprkbmxv8w/Bayes.pdf?dl=0">Workshop Sildes</a>

Some recommended readings for Bayesian Data Analysis:

- Data Analysis A Bayesian Tutorial by Sivia & Skilling
- Bayesian Data Analysis by Gelman
- Doing Bayesian Data Analysis by Kruschke