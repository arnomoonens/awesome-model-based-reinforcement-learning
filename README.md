# Awesome Model-based Reinforcement Learning[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<p align="center">
  <img width="250" src="https://camo.githubusercontent.com/1131548cf666e1150ebd2a52f44776d539f06324/68747470733a2f2f63646e2e7261776769742e636f6d2f73696e647265736f726875732f617765736f6d652f6d61737465722f6d656469612f6c6f676f2e737667" "Awesome!">
</p>

A curated list of awesome Model-based Reinforcement Learning resources. Inspired by [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision), [awesome-adversarial-machine-learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning), [awesome-deep-learning-papers](https://github.com/terryum/awesome-deep-learning-papers), and [awesome-architecture-search](https://github.com/markdtw/awesome-architecture-search)

Model-based Reinforcement Learning is gaining popularity in Robotics community. These are some of the awesome resources!

<p align="center">
  <img src="src/contributing.jpg" width="300">
</p>

## Contributing

This repo is forked from <https://github.com/Lukeeeeee/awesome-model-based-reinforcement-learning,> and I will continue to maintain it by myself.

Markdown format for conference/journal papers:

```markdown
- Paper Name [[pdf]](link) [[code]](link)
  - Author 1, Author 2 and Author 3. *Conference/Journal Year*
```

## Table of Contents

- [Thesis](#thesis)
- [Survey](#survey)
- [Conference Papers](#conference_papers)
- [Journal Papers](#journal_papers)
- [Tutorials](#tutorials)
- [Tools](#tools)

## Thesis

- Efficient Reinforcement Learning using Gaussian Processes. [[pdf]](https://pdfs.semanticscholar.org/c9f2/1b84149991f4d547b3f0f625f710750ad8d9.pdf)
  - Marc Peter Deisenroth.

## Survey

- Survey of Model-Based Reinforcement Learning: Applications on Robotics. [[pdf]](https://link.springer.com/article/10.1007/s10846-017-0468-y)
  - Athanasios S. Polydoros and Lazaros Nalpantidis. *J Intell Robot Syst 2017*
- A Survey on Policy Search for Robotics.
[[pdf]](https://core.ac.uk/download/pdf/84341151.pdf)
  - Marc Peter Deisenroth, Gerhard Neumann and Jan Peters.

## CV/CG

- Curiosity-driven Exploration by Self-supervised Prediction. [[pdf]](https://arxiv.org/pdf/1705.05363.pdf) [[code]](https://github.com/pathak22/noreward-rl)
  - Deepak Pathak, Pulkit Agrawal, Alexei A. Efros and Trevor Darrell. *ICML 2017*

## Conference papers

### Physics Model

- Differentiable Physics and Stable Modes for Tool-Use and Manipulation Planning. [[pdf]](http://www.roboticsproceedings.org/rss14/p44.pdf) [[code]](https://github.com/MarcToussaint/18-RSS-PhysicalManipulation)
  - Marc Toussaint, Kelsey R. Allen, Kevin A. Smith and Joshua B. Tenenbaum. *RSS 2018*
- A convex, smooth and invertible contact model for trajectory optimization. [[pdf]](https://homes.cs.washington.edu/~todorov/courses/amath533/ContactConvex.pdf)
  - Emanuel Todorov. *ICRA 2011*
- A Modular Differentiable Rigid Body Physics Engine. [[pdf]](https://drive.google.com/file/d/1K8t4gQExFXbuG4F9Zd2_30Y5wtpdEST7/view) [[code]](https://github.com/locuslab/lcp-physics)
  - Filipe de Avila Belbute-Peres and J. Zico Kolter. *Deep Reinforcement Learning Symposium, NIPS 2017*
- A DIFFERENTIABLE PHYSICS ENGINE FOR DEEP LEARNING IN ROBOTICS. [[pdf]](https://openreview.net/pdf?id=HkrB8XXte)
  - Jonas Degrave, Michiel Hermans, Joni Dambre and Francis wyffels. *ICLR 2017*
- Discovery of Complex Behaviors through Contact-Invariant Optimization. [[pdf]](https://homes.cs.washington.edu/~todorov/papers/MordatchSIGGRAPH12.pdf)
  - Igor Mordatch, Emanuel Tordorov and Zoran Popovic. *TOG'12*

### Hybrid model-based and model-free algorithm

- Neural Network Dynamics for Model-Based Deep Reinforcement Learning with Model-Free Fine-Tuning. [[pdf]](https://arxiv.org/pdf/1708.02596.pdf) [[code]](https://github.com/nagaban2/nn_dynamics)
  - Anusha Nagabandi, Gregory Kahn, Ronald S. Fearing and Sergey Levine.
- Combining Model-Based and Model-Free Updates for Trajectory-Centric Reinforcement Learning. [[pdf]](https://arxiv.org/pdf/1703.03078.pdf)
  - Yevgen Chebotar, Karol Hausman, Marvin Zhang, Gaurav Sukhatme, Stefan Schaal and Sergey Levine. *ICML 2017*
- Combined Reinforcement Learning via Abstract Representations. [[pdf]](https://arxiv.org/pdf/1809.04506.pdf) [[code]](https://github.com/VinF/deer)
  - Vincent François-Lavet, Yoshua Bengio, Doina Precup and Joelle Pineau. *AAAI 2019*
- When to Trust Your Model: Model-Based Policy Optimization. [[pdf]](https://arxiv.org/pdf/1906.08253.pdf) [[code]](https://github.com/JannerM/mbpo) [[project page]](https://people.eecs.berkeley.edu/~janner/mbpo/)
  - Michael Janner, Justin Fu, Marvin Zhang and Sergey Levine. *NeurIPS 2019*

### Model Predictive Control

- Deep Reinforcement Learning in a Handful of Trials using Probabilistic Dynamics Models. [[pdf]](https://arxiv.org/pdf/1805.12114.pdf) [[code]](https://github.com/kchua/handful-of-trials) [[project page]](https://sites.google.com/view/drl-in-a-handful-of-trials/)
  - Kurtland Chua, Roberto Calandra, Rowan McAllister and Sergey Levine. *NIPS 2018*

### Optimal Control

- Local Gaussian Process Regression for Real-time Model-based Robot Control. [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4650850)
  - Duy Nguyen-Tuong and Jan Peters. *IROS 2008*

### Local model

- Learning Neural Network Policies with Guided Policy Search under Unknown Dynamics. [[pdf]](https://people.eecs.berkeley.edu/~svlevine/papers/mfcgps.pdf) [[code]](https://github.com/cbfinn/gps/blob/master/docs/index.md)
  - Sergey Levine and Pieter Abbeel. *NIPS 2014*

### Learn in latent space

#### Foward Dynamics Model

- Embed to Control: A Locally Linear Latent Dynamics Model for Control from Raw Images. [[pdf]](https://arxiv.org/pdf/1506.07365.pdf) [[code]](https://github.com/ericjang/e2c)
  - Manuel Watter, Jost Tobias Springenberg, Martin Riedmiller and Joschka Boedecker. *ICRA 2017*
- Deep Spatial Autoencoders for Visuomotor Learning. [[pdf]](https://arxiv.org/pdf/1509.06113.pdf) [[code]](https://github.com/cbfinn/gps/blob/master/docs/index.md)
  - Chelsea Finn, Xin Yu Tan, Yan Duan, Trevor Darrell, Sergey Levine and Pieter Abbeel. *ICRA 2016*

### Gaussian Process

- Data-Efficient Reinforcement Learning in Continuous-State POMDPs. [[pdf]](https://papers.nips.cc/paper/6799-data-efficient-reinforcement-learning-in-continuous-state-action-gaussian-pomdps.pdf)
  - Rowan McAllister and Carl Rasmussen. *NIPS 2017*
- Improving PILCO with Bayesian Neural Network Dynamics Models. [[pdf]](http://mlg.eng.cam.ac.uk/yarin/PDFs/DeepPILCO.pdf)
  - Yarin Gal and Rowan Thomas McAllister and Carl Edward Rasmussen. *Data-Efficient Machine Learning workshop, ICML, 2016*
- PILCO: A Model-Based and Data-Efficient Approach to Policy Search. [[pdf]](http://mlg.eng.cam.ac.uk/pub/pdf/DeiRas11.pdf) [[code]](http://mlg.eng.cam.ac.uk/pilco/) [[unofficial code]](https://github.com/nrontsis/PILCO) [[unofficial code 2]](https://github.com/edlanglois/mbbl-pilco)
  - Marc Peter Deisenroth and Carl Rasmussen. *ICML 2011*
- Learning to Control a Low-Cost Manipulator using Data-Efficient Reinforcement Learning. [[pdf]](http://www.roboticsproceedings.org/rss07/p08.pdf)
  - Marc Peter Deisenroth, Carl Edward Rasmussen and Dieter Fox. *RSS 2011*
- Learning Dynamics Across Similar Spatiotemporally-Evolving Physical Systems. [[pdf]](http://proceedings.mlr.press/v78/whitman17a/whitman17a.pdf)
  - Joshua Whitman and Girish Chowdhary. *CoRL 2017*

## Journal papers

## ArXiv only or under review papers

- MOPO: Model-based Offline Policy Optimization. [[pdf]](https://arxiv.org/pdf/2005.13239)
  - Tianhe Yu, Garrett Thomas, Lantao Yu, Stefano Ermon, James Zou, Sergey Levine, Chelsea Finn and Tengyu Ma.
- Model-based Reinforcement Learning: A Survey. [[pdf]](https://arxiv.org/pdf/2006.16712v1)
  - Thomas M. Moerland, Joost Broekens and Catholijn M. Jonker.

## Tutorials

- Deep RL Bootcamp Lecture 9 Model-based Reinforcement Learning. Chelsea Finn (UC Berkeley) [[link]](https://www.youtube.com/watch?v=iC2a7M9voYU)
- Highlight Talk: Gaussian Processes for Data Efficient Learning. Marc Diesenroth [[link]](https://www.youtube.com/watch?v=dWsjjszwfi0)
- CS287-FA19 Advanced Robotics: Lecture 20 Model-Based Reinforcement Learning. Pieter Abbeel (UC Berkeley) [[link 1]](https://www.youtube.com/watch?v=Y2XBiUtZo1k) [[link 2]](https://www.youtube.com/watch?v=HRp6DH5M7Co)
- Reinforcement Learning 7: Planning and Models. Hado Van Hasselt (Deepmind) [[link]](https://www.youtube.com/watch?v=Xrxrd8nl4YI)

## Tools

- [GPFlow](https://github.com/GPflow/GPflow)
- [GPy](https://github.com/SheffieldML/GPy)
- [controlpy](https://github.com/markwmuller/controlpy)
- [python control](https://github.com/python-control/python-control)
- [Baconian](https://github.com/cap-ntu/baconian-project)
- [MBBL](https://github.com/WilsonWangTHU/mbbl)
