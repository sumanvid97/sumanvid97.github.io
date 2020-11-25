---
layout: default
title: Research
---

### Data Informed Network Simulation | Microsoft Research India
*Research Internship under Dr. [N. Natarajan](https://scholar.google.com/citations?hl=en&user=ZBkUp20AAAAJ), Dr. [S. Sellamanickam](https://www.microsoft.com/en-us/research/people/ssrajan/) and Dr. [V. Padmanabhan](https://www.microsoft.com/en-us/research/people/padmanab/)* \\
*(Summer 2019)* 

<img src="/images/ibox.png" style="width:80%;"/>

I formulated a data-driven network simulator which can learn the behaviour of an ensemble of per-packet-level network traces from unicast communications between a sender and a receiver (e.g., file transfer, real-time calls). Probabilistic and neural versions of a state space modeling approach were devised to estimate a sequence of (domain-agnostic) network states, conditioned on past state(s). Experiments were performed with data from a pre-configured ```ns-2```, and real network traces from Skype calls. I evaluated state-space models along with the deepAR forecasting model for unseen data on metrics capturing realism, like CDFs for per-packet delays, packet loss rates, and Hellinger scores from state-transition matrices. For model applicability, I derived a log-likelihood score for a given unseen input trace, based on training data.


### Super-resolution of Rainfall Projections using CNNs | IIT Bombay
*Bachelor's Thesis under Prof. [Amit Sethi](https://www.ee.iitb.ac.in/~asethi/) and Prof. [Subimal Ghosh](https://www.civil.iitb.ac.in/~subimal/)* \\
*(Sept 2018 - Apr 2019)* \\
[[poster]](/docs/btp_poster.pdf) [[report]](/docs/btp_report.pdf)

<img src="/images/btp_plot.png" style="width:80%;"/>

I leveraged computer vision techniques to predict daily observed rainfall projections at high (~25 km<sup>2</sup>) resolution for the Indian landmass, from reanalysis simulations of climate variables at low (~250 km<sup>2</sup>) resolution. Owing to the 10x scaling factor and varying local rainfall patterns throughout India, only the central zone (among the seven meteorologically homogeneous zones) was subjected to subsequent experimentations. I designed custom CNN architectures with dense blocks, dilated & transpose convolutions, and cyclic learning rate schedulers to achieve MSE of 5 mm/day (better than the baseline kernel regression approach) throughout the test data. 

